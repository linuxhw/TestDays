Linux in Belarus - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belarus/Desktop/README.md) and [notebooks](/Location/Belarus/Notebook/README.md).

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

Total: 1535

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [c11c9964fa](https://linux-hardware.org/?probe=c11c9964fa) | Apr 27, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [8bca3fa04b](https://linux-hardware.org/?probe=8bca3fa04b) | Apr 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [94bd5fe556](https://linux-hardware.org/?probe=94bd5fe556) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [50c44b15eb](https://linux-hardware.org/?probe=50c44b15eb) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [9cb44b75f5](https://linux-hardware.org/?probe=9cb44b75f5) | Apr 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9f5fa03bfd](https://linux-hardware.org/?probe=9f5fa03bfd) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [f87a34e474](https://linux-hardware.org/?probe=f87a34e474) | Apr 19, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [84dbb8ae74](https://linux-hardware.org/?probe=84dbb8ae74) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [9cacd6f238](https://linux-hardware.org/?probe=9cacd6f238) | Apr 19, 2023 |
| TECNO         | MEGABOOK T1                 | Notebook    | [733d7d5584](https://linux-hardware.org/?probe=733d7d5584) | Apr 18, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [a02f8565dd](https://linux-hardware.org/?probe=a02f8565dd) | Apr 14, 2023 |
| ASUSTek       | X75VCP                      | Notebook    | [5ecb1bb650](https://linux-hardware.org/?probe=5ecb1bb650) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [5c23d1d7f7](https://linux-hardware.org/?probe=5c23d1d7f7) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [be2a3d30f2](https://linux-hardware.org/?probe=be2a3d30f2) | Apr 08, 2023 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [71c25d2dce](https://linux-hardware.org/?probe=71c25d2dce) | Apr 07, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [ca3f0771ce](https://linux-hardware.org/?probe=ca3f0771ce) | Apr 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [24ac3864d2](https://linux-hardware.org/?probe=24ac3864d2) | Apr 04, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [1789a17694](https://linux-hardware.org/?probe=1789a17694) | Apr 03, 2023 |
| Gigabyte      | B360M H                     | Desktop     | [cc5feeb3eb](https://linux-hardware.org/?probe=cc5feeb3eb) | Apr 03, 2023 |
| Biostar       | B365MHC                     | Desktop     | [95107f0e65](https://linux-hardware.org/?probe=95107f0e65) | Apr 02, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [6dafdf20a5](https://linux-hardware.org/?probe=6dafdf20a5) | Apr 02, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [f811a203a0](https://linux-hardware.org/?probe=f811a203a0) | Apr 02, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [f278e6aad0](https://linux-hardware.org/?probe=f278e6aad0) | Apr 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [51f6d77f50](https://linux-hardware.org/?probe=51f6d77f50) | Mar 30, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [e5433e75fb](https://linux-hardware.org/?probe=e5433e75fb) | Mar 29, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [06ad8e8099](https://linux-hardware.org/?probe=06ad8e8099) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | Desktop     | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| Dell          | System XPS L702X            | Notebook    | [2c8aed8334](https://linux-hardware.org/?probe=2c8aed8334) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| HP            | Notebook                    | Notebook    | [f18d14ac70](https://linux-hardware.org/?probe=f18d14ac70) | Mar 28, 2023 |
| HP            | 250 G1                      | Notebook    | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| Lenovo        | 3000 G530 4151/200          | Notebook    | [4c0751aa89](https://linux-hardware.org/?probe=4c0751aa89) | Mar 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6ae381093b](https://linux-hardware.org/?probe=6ae381093b) | Mar 26, 2023 |
| MSI           | X79A-GD45 Plus              | Desktop     | [0a5446e862](https://linux-hardware.org/?probe=0a5446e862) | Mar 26, 2023 |
| Getac         | B300-H                      | Notebook    | [28a9b0b0c7](https://linux-hardware.org/?probe=28a9b0b0c7) | Mar 25, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [c4b7067187](https://linux-hardware.org/?probe=c4b7067187) | Mar 24, 2023 |
| Iskratel, ... | IN6011AX                    | Desktop     | [037350830e](https://linux-hardware.org/?probe=037350830e) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [8023b22765](https://linux-hardware.org/?probe=8023b22765) | Mar 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [5e9cf8fb44](https://linux-hardware.org/?probe=5e9cf8fb44) | Mar 22, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [7d8950b25b](https://linux-hardware.org/?probe=7d8950b25b) | Mar 21, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [c58012d73d](https://linux-hardware.org/?probe=c58012d73d) | Mar 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [43940eb778](https://linux-hardware.org/?probe=43940eb778) | Mar 20, 2023 |
| HP            | Pavilion dv7                | Notebook    | [d42628a0e9](https://linux-hardware.org/?probe=d42628a0e9) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| ASUSTek       | X555LB                      | Notebook    | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b5746d500d](https://linux-hardware.org/?probe=b5746d500d) | Mar 13, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [0e89d9279d](https://linux-hardware.org/?probe=0e89d9279d) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | Notebook    | [8541575b10](https://linux-hardware.org/?probe=8541575b10) | Mar 12, 2023 |
| Intel         | JSL MRD                     | Desktop     | [28832d0a36](https://linux-hardware.org/?probe=28832d0a36) | Mar 11, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [249f986099](https://linux-hardware.org/?probe=249f986099) | Mar 09, 2023 |
| HP            | Compaq 610                  | Notebook    | [3f5ffc0582](https://linux-hardware.org/?probe=3f5ffc0582) | Mar 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [48dc89b146](https://linux-hardware.org/?probe=48dc89b146) | Mar 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [546d7b3f27](https://linux-hardware.org/?probe=546d7b3f27) | Mar 07, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3fb642aac7](https://linux-hardware.org/?probe=3fb642aac7) | Mar 06, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [efd6fd1985](https://linux-hardware.org/?probe=efd6fd1985) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e682158c7f](https://linux-hardware.org/?probe=e682158c7f) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [268e27cc20](https://linux-hardware.org/?probe=268e27cc20) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [e8325b5ff1](https://linux-hardware.org/?probe=e8325b5ff1) | Mar 03, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [9cd0a2ea25](https://linux-hardware.org/?probe=9cd0a2ea25) | Mar 01, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [630c0e41b1](https://linux-hardware.org/?probe=630c0e41b1) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c85bd630f0](https://linux-hardware.org/?probe=c85bd630f0) | Feb 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [5b524ddbb0](https://linux-hardware.org/?probe=5b524ddbb0) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [9b00bf7704](https://linux-hardware.org/?probe=9b00bf7704) | Feb 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dc6a6f7872](https://linux-hardware.org/?probe=dc6a6f7872) | Feb 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [788044d53c](https://linux-hardware.org/?probe=788044d53c) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| Partner       | S1-J1900                    | Desktop     | [0dd4327553](https://linux-hardware.org/?probe=0dd4327553) | Feb 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [faa600d8e5](https://linux-hardware.org/?probe=faa600d8e5) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [dfa8cae135](https://linux-hardware.org/?probe=dfa8cae135) | Feb 17, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [3faff8d320](https://linux-hardware.org/?probe=3faff8d320) | Feb 17, 2023 |
| ASUSTek       | P5GD1 PRO                   | Desktop     | [043021ca86](https://linux-hardware.org/?probe=043021ca86) | Feb 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [44e18a0f72](https://linux-hardware.org/?probe=44e18a0f72) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [0da8e9ac4c](https://linux-hardware.org/?probe=0da8e9ac4c) | Feb 14, 2023 |
| Intel         | NUC7i3BNB J22859-316        | Mini pc     | [fc5fbe9d48](https://linux-hardware.org/?probe=fc5fbe9d48) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [5644272d9e](https://linux-hardware.org/?probe=5644272d9e) | Feb 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [a1549a7701](https://linux-hardware.org/?probe=a1549a7701) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Intel         | SKYBAY                      | Desktop     | [7f8e95e496](https://linux-hardware.org/?probe=7f8e95e496) | Feb 02, 2023 |
| Intel         | SKYBAY                      | Desktop     | [a75cb78ad9](https://linux-hardware.org/?probe=a75cb78ad9) | Feb 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASUSTek       | Z170M-E D3                  | Desktop     | [2b466d1b19](https://linux-hardware.org/?probe=2b466d1b19) | Jan 29, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f94175d8c](https://linux-hardware.org/?probe=6f94175d8c) | Jan 28, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [add8440e16](https://linux-hardware.org/?probe=add8440e16) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f4e06ff0b2](https://linux-hardware.org/?probe=f4e06ff0b2) | Jan 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | Notebook    | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [04d36be1ec](https://linux-hardware.org/?probe=04d36be1ec) | Jan 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d0a00b398c](https://linux-hardware.org/?probe=d0a00b398c) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [7c116ff037](https://linux-hardware.org/?probe=7c116ff037) | Jan 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | Notebook    | [4606ff1dab](https://linux-hardware.org/?probe=4606ff1dab) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [18654d5f58](https://linux-hardware.org/?probe=18654d5f58) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [43e346516e](https://linux-hardware.org/?probe=43e346516e) | Jan 09, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [d30caadc06](https://linux-hardware.org/?probe=d30caadc06) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [325952460c](https://linux-hardware.org/?probe=325952460c) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [ac63fca6cb](https://linux-hardware.org/?probe=ac63fca6cb) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d23fb14f2e](https://linux-hardware.org/?probe=d23fb14f2e) | Jan 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| MSI           | MS-7519                     | Desktop     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [7b9bc5bc99](https://linux-hardware.org/?probe=7b9bc5bc99) | Jan 02, 2023 |
| Unknown       | Intel X79                   | Desktop     | [f26c05e261](https://linux-hardware.org/?probe=f26c05e261) | Dec 31, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cc1d0776d5](https://linux-hardware.org/?probe=cc1d0776d5) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6f0f984312](https://linux-hardware.org/?probe=6f0f984312) | Dec 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [d196b92cff](https://linux-hardware.org/?probe=d196b92cff) | Dec 27, 2022 |
| ASRock        | Brazos                      | Desktop     | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | Notebook    | [9f1751d2e5](https://linux-hardware.org/?probe=9f1751d2e5) | Dec 22, 2022 |
| Pegatron      | A17                         | Notebook    | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [077f863ca3](https://linux-hardware.org/?probe=077f863ca3) | Dec 15, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a096df53ed](https://linux-hardware.org/?probe=a096df53ed) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [fcd4a2d840](https://linux-hardware.org/?probe=fcd4a2d840) | Dec 11, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b463c25c4d](https://linux-hardware.org/?probe=b463c25c4d) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1c80b48ea0](https://linux-hardware.org/?probe=1c80b48ea0) | Dec 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ad6dc99c8a](https://linux-hardware.org/?probe=ad6dc99c8a) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| HP            | 550                         | Notebook    | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d6829bfb6d](https://linux-hardware.org/?probe=d6829bfb6d) | Dec 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c3f0c49c7c](https://linux-hardware.org/?probe=c3f0c49c7c) | Dec 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cb93839085](https://linux-hardware.org/?probe=cb93839085) | Dec 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2de79b83d5](https://linux-hardware.org/?probe=2de79b83d5) | Nov 28, 2022 |
| ASUSTek       | K70AB                       | Notebook    | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| HASEE Comp... | V1x0PNPx                    | Notebook    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | UX31A                       | Notebook    | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [f236aa0a8b](https://linux-hardware.org/?probe=f236aa0a8b) | Nov 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [09c253d548](https://linux-hardware.org/?probe=09c253d548) | Nov 07, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [9d1fda5ecb](https://linux-hardware.org/?probe=9d1fda5ecb) | Nov 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [77bdbb310f](https://linux-hardware.org/?probe=77bdbb310f) | Oct 31, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4b5140c9f3](https://linux-hardware.org/?probe=4b5140c9f3) | Oct 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [25003181f1](https://linux-hardware.org/?probe=25003181f1) | Oct 27, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2481764903](https://linux-hardware.org/?probe=2481764903) | Oct 27, 2022 |
| HP            | Compaq 610                  | Notebook    | [5adc7e0aba](https://linux-hardware.org/?probe=5adc7e0aba) | Oct 26, 2022 |
| HP            | Compaq 610                  | Notebook    | [9a584886fe](https://linux-hardware.org/?probe=9a584886fe) | Oct 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6e83c73646](https://linux-hardware.org/?probe=6e83c73646) | Oct 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [14b0f43bd5](https://linux-hardware.org/?probe=14b0f43bd5) | Oct 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| ASUSTek       | T101MT                      | Notebook    | [d0fc7c3dae](https://linux-hardware.org/?probe=d0fc7c3dae) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [99df624686](https://linux-hardware.org/?probe=99df624686) | Oct 03, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [25e3064dd2](https://linux-hardware.org/?probe=25e3064dd2) | Sep 29, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [2935c5bedd](https://linux-hardware.org/?probe=2935c5bedd) | Sep 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [254a78c371](https://linux-hardware.org/?probe=254a78c371) | Sep 26, 2022 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [372160583e](https://linux-hardware.org/?probe=372160583e) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a861ca9999](https://linux-hardware.org/?probe=a861ca9999) | Sep 19, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [8f6b96ba44](https://linux-hardware.org/?probe=8f6b96ba44) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| ASUSTek       | X550MD                      | Notebook    | [69cce160a1](https://linux-hardware.org/?probe=69cce160a1) | Sep 16, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [a856637b19](https://linux-hardware.org/?probe=a856637b19) | Sep 15, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [cb17ac9b4e](https://linux-hardware.org/?probe=cb17ac9b4e) | Sep 05, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8b8ba6c7f9](https://linux-hardware.org/?probe=8b8ba6c7f9) | Sep 05, 2022 |
| Toshiba       | Satellite C850-C5K          | Notebook    | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d9d75bc1f0](https://linux-hardware.org/?probe=d9d75bc1f0) | Aug 29, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [2ee74a388d](https://linux-hardware.org/?probe=2ee74a388d) | Aug 25, 2022 |
| HP            | Compaq 610                  | Notebook    | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [1d2367ccf7](https://linux-hardware.org/?probe=1d2367ccf7) | Aug 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | Notebook    | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Compaq 610                  | Notebook    | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [3decfcd64a](https://linux-hardware.org/?probe=3decfcd64a) | Aug 14, 2022 |
| Huanan        | X99-BD4 V1.33               | Desktop     | [a250b39eec](https://linux-hardware.org/?probe=a250b39eec) | Aug 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [b73567b27b](https://linux-hardware.org/?probe=b73567b27b) | Aug 09, 2022 |
| Sony          | SVF1521L1RW                 | Notebook    | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [4b4e4d693e](https://linux-hardware.org/?probe=4b4e4d693e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [c8562d4bac](https://linux-hardware.org/?probe=c8562d4bac) | Jul 27, 2022 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [e899f43a3f](https://linux-hardware.org/?probe=e899f43a3f) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [4e757278be](https://linux-hardware.org/?probe=4e757278be) | Jul 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [1ee2492f24](https://linux-hardware.org/?probe=1ee2492f24) | Jul 23, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [2d2a17094e](https://linux-hardware.org/?probe=2d2a17094e) | Jul 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [7142849ed0](https://linux-hardware.org/?probe=7142849ed0) | Jul 17, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | Notebook    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e5638d3552](https://linux-hardware.org/?probe=e5638d3552) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [3f20ad2267](https://linux-hardware.org/?probe=3f20ad2267) | Jul 11, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [b7adccb849](https://linux-hardware.org/?probe=b7adccb849) | Jul 09, 2022 |
| Samsung       | 535U3C                      | Notebook    | [80b2b79e75](https://linux-hardware.org/?probe=80b2b79e75) | Jul 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| HP            | Compaq 610                  | Notebook    | [62287cff21](https://linux-hardware.org/?probe=62287cff21) | Jul 06, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [26cbd669e4](https://linux-hardware.org/?probe=26cbd669e4) | Jul 05, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [2fb330049e](https://linux-hardware.org/?probe=2fb330049e) | Jul 04, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [2b31833bfe](https://linux-hardware.org/?probe=2b31833bfe) | Jul 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [06d4d79742](https://linux-hardware.org/?probe=06d4d79742) | Jul 01, 2022 |
| Biostar       | TA790GX 128M                | Desktop     | [c7021e0b8c](https://linux-hardware.org/?probe=c7021e0b8c) | Jul 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| Prestigio     | Multipad Visconte V         | Notebook    | [fd38a70070](https://linux-hardware.org/?probe=fd38a70070) | Jun 29, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [8cb88942e3](https://linux-hardware.org/?probe=8cb88942e3) | Jun 28, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [3417dd6a9a](https://linux-hardware.org/?probe=3417dd6a9a) | Jun 28, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [e52ad13385](https://linux-hardware.org/?probe=e52ad13385) | Jun 25, 2022 |
| Getac         | B300-H                      | Notebook    | [ff8382e269](https://linux-hardware.org/?probe=ff8382e269) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Getac         | B300-H                      | Notebook    | [d0b0703736](https://linux-hardware.org/?probe=d0b0703736) | Jun 23, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [6dd752fab5](https://linux-hardware.org/?probe=6dd752fab5) | Jun 23, 2022 |
| Dell          | 0PGMR1 A00                  | All in one  | [bf057e65d8](https://linux-hardware.org/?probe=bf057e65d8) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | Notebook    | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [701de0d7ad](https://linux-hardware.org/?probe=701de0d7ad) | Jun 15, 2022 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d381bbec9f](https://linux-hardware.org/?probe=d381bbec9f) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [8e7a43f724](https://linux-hardware.org/?probe=8e7a43f724) | Jun 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [595e4c8656](https://linux-hardware.org/?probe=595e4c8656) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [0ee020dd5a](https://linux-hardware.org/?probe=0ee020dd5a) | Jun 09, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [e057e3b6d8](https://linux-hardware.org/?probe=e057e3b6d8) | Jun 07, 2022 |
| HP            | Mini 110-4100               | Notebook    | [62932d62d5](https://linux-hardware.org/?probe=62932d62d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [88d5e21b42](https://linux-hardware.org/?probe=88d5e21b42) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd317d92a3](https://linux-hardware.org/?probe=dd317d92a3) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| ECS           | IC780M-A2                   | Desktop     | [135f0a4328](https://linux-hardware.org/?probe=135f0a4328) | May 21, 2022 |
| MSI           | MS-7309                     | Desktop     | [9093ca0773](https://linux-hardware.org/?probe=9093ca0773) | May 20, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [ec4bd74f0b](https://linux-hardware.org/?probe=ec4bd74f0b) | May 13, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [46481247b1](https://linux-hardware.org/?probe=46481247b1) | May 12, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2a916e3eb5](https://linux-hardware.org/?probe=2a916e3eb5) | May 09, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [fbe61c70ff](https://linux-hardware.org/?probe=fbe61c70ff) | May 09, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [76e67361ea](https://linux-hardware.org/?probe=76e67361ea) | May 08, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [8926d96550](https://linux-hardware.org/?probe=8926d96550) | May 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [7fb6e94bab](https://linux-hardware.org/?probe=7fb6e94bab) | Apr 27, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ff5ff260a0](https://linux-hardware.org/?probe=ff5ff260a0) | Apr 26, 2022 |
| ASUSTek       | ROG Maximus XI CODE         | Desktop     | [8cca49b0ee](https://linux-hardware.org/?probe=8cca49b0ee) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [ab464ae6a9](https://linux-hardware.org/?probe=ab464ae6a9) | Apr 15, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [8a1cecc21c](https://linux-hardware.org/?probe=8a1cecc21c) | Apr 11, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [90a9483531](https://linux-hardware.org/?probe=90a9483531) | Apr 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| ASUSTek       | X541NC                      | Notebook    | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [50780eda28](https://linux-hardware.org/?probe=50780eda28) | Mar 30, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c7d6879a86](https://linux-hardware.org/?probe=c7d6879a86) | Mar 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [803a20d0cb](https://linux-hardware.org/?probe=803a20d0cb) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [ef7133f14a](https://linux-hardware.org/?probe=ef7133f14a) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [b7679b78be](https://linux-hardware.org/?probe=b7679b78be) | Mar 25, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [49853bb240](https://linux-hardware.org/?probe=49853bb240) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | Notebook    | [06883f214a](https://linux-hardware.org/?probe=06883f214a) | Mar 25, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a8e8d6dd5e](https://linux-hardware.org/?probe=a8e8d6dd5e) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [db687b8693](https://linux-hardware.org/?probe=db687b8693) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| ASRock        | FM2A55M-VG3                 | Desktop     | [96683b7f45](https://linux-hardware.org/?probe=96683b7f45) | Mar 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [517ef58b87](https://linux-hardware.org/?probe=517ef58b87) | Mar 11, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [69fd2b147f](https://linux-hardware.org/?probe=69fd2b147f) | Mar 11, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [55ce4f1460](https://linux-hardware.org/?probe=55ce4f1460) | Mar 11, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [a6fc7b9f12](https://linux-hardware.org/?probe=a6fc7b9f12) | Mar 10, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [800bc08dbd](https://linux-hardware.org/?probe=800bc08dbd) | Mar 09, 2022 |
| HP            | Mini 110-4100               | Notebook    | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [da3962a1da](https://linux-hardware.org/?probe=da3962a1da) | Mar 03, 2022 |
| HP            | 635                         | Notebook    | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [bdba90c583](https://linux-hardware.org/?probe=bdba90c583) | Mar 03, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d2e96e523e](https://linux-hardware.org/?probe=d2e96e523e) | Mar 03, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7ce556e43a](https://linux-hardware.org/?probe=7ce556e43a) | Feb 26, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [39389b9ddf](https://linux-hardware.org/?probe=39389b9ddf) | Feb 26, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [34e4b434b4](https://linux-hardware.org/?probe=34e4b434b4) | Feb 20, 2022 |
| Sony          | VPCF119FX                   | Notebook    | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| ASUSTek       | K50C                        | Notebook    | [01079b722b](https://linux-hardware.org/?probe=01079b722b) | Feb 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [8bb8c751f8](https://linux-hardware.org/?probe=8bb8c751f8) | Feb 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [601f46e5a4](https://linux-hardware.org/?probe=601f46e5a4) | Feb 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7966e303e6](https://linux-hardware.org/?probe=7966e303e6) | Feb 07, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a32dfea06a](https://linux-hardware.org/?probe=a32dfea06a) | Feb 07, 2022 |
| ASRock        | B560M Steel Legend          | Desktop     | [e2a7b380d8](https://linux-hardware.org/?probe=e2a7b380d8) | Feb 06, 2022 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [d7796dd19f](https://linux-hardware.org/?probe=d7796dd19f) | Feb 05, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [ce0fa6ccd3](https://linux-hardware.org/?probe=ce0fa6ccd3) | Feb 03, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [583a1313c8](https://linux-hardware.org/?probe=583a1313c8) | Feb 01, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [0bcf18e1fc](https://linux-hardware.org/?probe=0bcf18e1fc) | Feb 01, 2022 |
| HP            | Compaq 8710w (GC124EA#AC... | Notebook    | [b21e187792](https://linux-hardware.org/?probe=b21e187792) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [ed633ddd09](https://linux-hardware.org/?probe=ed633ddd09) | Jan 29, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [607ade73d0](https://linux-hardware.org/?probe=607ade73d0) | Jan 29, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [1a2d6520d3](https://linux-hardware.org/?probe=1a2d6520d3) | Jan 29, 2022 |
| MSI           | H87M-E35                    | Desktop     | [0cfdd2b772](https://linux-hardware.org/?probe=0cfdd2b772) | Jan 28, 2022 |
| HP            | Presario CQ57               | Notebook    | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [abed2f64a1](https://linux-hardware.org/?probe=abed2f64a1) | Jan 26, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [84bd3ccecf](https://linux-hardware.org/?probe=84bd3ccecf) | Jan 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e00760f649](https://linux-hardware.org/?probe=e00760f649) | Jan 21, 2022 |
| MSI           | B150M PRO-VH                | Desktop     | [de22d479a4](https://linux-hardware.org/?probe=de22d479a4) | Jan 20, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [291a3e234b](https://linux-hardware.org/?probe=291a3e234b) | Jan 14, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [8f9c010abb](https://linux-hardware.org/?probe=8f9c010abb) | Jan 10, 2022 |
| Kllisre       | X79 V1.2                    | Desktop     | [239547a419](https://linux-hardware.org/?probe=239547a419) | Jan 09, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | G7 7700                     | Notebook    | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| MSI           | GT75 Titan 8RG              | Notebook    | [77e24243cf](https://linux-hardware.org/?probe=77e24243cf) | Jan 02, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [5d9026b1c0](https://linux-hardware.org/?probe=5d9026b1c0) | Jan 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| MSI           | MS-7922                     | Desktop     | [d0837f687b](https://linux-hardware.org/?probe=d0837f687b) | Dec 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003KRT     | Notebook    | [62e3c3073b](https://linux-hardware.org/?probe=62e3c3073b) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| Gigabyte      | M61SME-S2                   | Desktop     | [be9f6cac13](https://linux-hardware.org/?probe=be9f6cac13) | Dec 20, 2021 |
| ASUSTek       | X540UA                      | Notebook    | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HONOR         | BMH-WCX9                    | Notebook    | [46395a1450](https://linux-hardware.org/?probe=46395a1450) | Dec 19, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [7f0853c09e](https://linux-hardware.org/?probe=7f0853c09e) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| MSI           | GL63 9SC                    | Notebook    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK NH532              | Notebook    | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| BenQ          | Joybook R56                 | Notebook    | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3616fc5b0e](https://linux-hardware.org/?probe=3616fc5b0e) | Dec 12, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | Notebook    | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [a2e037ba0e](https://linux-hardware.org/?probe=a2e037ba0e) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f9ada169fd](https://linux-hardware.org/?probe=f9ada169fd) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d39826b60](https://linux-hardware.org/?probe=7d39826b60) | Dec 09, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [7304efa5d7](https://linux-hardware.org/?probe=7304efa5d7) | Dec 01, 2021 |
| LG Electro... | R510                        | Notebook    | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [00c297540d](https://linux-hardware.org/?probe=00c297540d) | Nov 27, 2021 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [0162ece16f](https://linux-hardware.org/?probe=0162ece16f) | Nov 25, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | Notebook    | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [488cdb831c](https://linux-hardware.org/?probe=488cdb831c) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Fujitsu       | D3034-A1 S26361-D3034-A1... | Server      | [8cf8f98a53](https://linux-hardware.org/?probe=8cf8f98a53) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [696ee320dd](https://linux-hardware.org/?probe=696ee320dd) | Nov 11, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [039315b907](https://linux-hardware.org/?probe=039315b907) | Nov 10, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [e290db920f](https://linux-hardware.org/?probe=e290db920f) | Nov 08, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [3533adc65b](https://linux-hardware.org/?probe=3533adc65b) | Nov 07, 2021 |
| HP            | ProBook 455 G1              | Notebook    | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [5010ca9e9a](https://linux-hardware.org/?probe=5010ca9e9a) | Nov 06, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| ASUSTek       | V241EA                      | All in one  | [ffb4ed2207](https://linux-hardware.org/?probe=ffb4ed2207) | Nov 02, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [0233ae7054](https://linux-hardware.org/?probe=0233ae7054) | Oct 31, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [04c5f1689d](https://linux-hardware.org/?probe=04c5f1689d) | Oct 27, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [0f23350175](https://linux-hardware.org/?probe=0f23350175) | Oct 27, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a56c0a6b4d](https://linux-hardware.org/?probe=a56c0a6b4d) | Oct 26, 2021 |
| Samsung       | R508                        | Notebook    | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| HP            | Notebook                    | Notebook    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [8061e7314a](https://linux-hardware.org/?probe=8061e7314a) | Oct 23, 2021 |
| HP            | 86F0 11000                  | All in one  | [75738404ae](https://linux-hardware.org/?probe=75738404ae) | Oct 21, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | Notebook    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Lenovo        | S10-3                       | Notebook    | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f874da9f03](https://linux-hardware.org/?probe=f874da9f03) | Oct 12, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9fd17a6579](https://linux-hardware.org/?probe=9fd17a6579) | Oct 09, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [9b4b3c9f77](https://linux-hardware.org/?probe=9b4b3c9f77) | Oct 09, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [b99c6d022e](https://linux-hardware.org/?probe=b99c6d022e) | Oct 05, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0d6bbd5c75](https://linux-hardware.org/?probe=0d6bbd5c75) | Oct 05, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [264badf289](https://linux-hardware.org/?probe=264badf289) | Oct 01, 2021 |
| HP            | Pavilion dv4000 (PX306UA... | Notebook    | [fdc2b74a29](https://linux-hardware.org/?probe=fdc2b74a29) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | Notebook    | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| Intel         | H61M-S1                     | Desktop     | [ba0b4c102b](https://linux-hardware.org/?probe=ba0b4c102b) | Sep 30, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [b6f5c877d4](https://linux-hardware.org/?probe=b6f5c877d4) | Sep 29, 2021 |
| HP            | 86F0 11000                  | All in one  | [d94d1dcab2](https://linux-hardware.org/?probe=d94d1dcab2) | Sep 29, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e8c44e9282](https://linux-hardware.org/?probe=e8c44e9282) | Sep 26, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [bea6762fb6](https://linux-hardware.org/?probe=bea6762fb6) | Sep 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [f21200b164](https://linux-hardware.org/?probe=f21200b164) | Sep 23, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [80b6244981](https://linux-hardware.org/?probe=80b6244981) | Sep 21, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [bc0974da01](https://linux-hardware.org/?probe=bc0974da01) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9cf1061bcb](https://linux-hardware.org/?probe=9cf1061bcb) | Sep 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [f8bb575441](https://linux-hardware.org/?probe=f8bb575441) | Sep 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [a64387b07d](https://linux-hardware.org/?probe=a64387b07d) | Sep 15, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [01cd639b37](https://linux-hardware.org/?probe=01cd639b37) | Sep 11, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [04e9d9ef11](https://linux-hardware.org/?probe=04e9d9ef11) | Sep 10, 2021 |
| HP            | ProBook 4515s               | Notebook    | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | Notebook    | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | G71V                        | Notebook    | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [248b63572e](https://linux-hardware.org/?probe=248b63572e) | Sep 08, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| Samsung       | R508                        | Notebook    | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| HP            | Compaq 610                  | Notebook    | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [11fce4275a](https://linux-hardware.org/?probe=11fce4275a) | Sep 01, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [989a6f27be](https://linux-hardware.org/?probe=989a6f27be) | Aug 29, 2021 |
| Biostar       | A960D+V3                    | Desktop     | [f65660cdbe](https://linux-hardware.org/?probe=f65660cdbe) | Aug 26, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [89dcb140f5](https://linux-hardware.org/?probe=89dcb140f5) | Aug 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [46407e3bfe](https://linux-hardware.org/?probe=46407e3bfe) | Aug 24, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [7928c7e6e6](https://linux-hardware.org/?probe=7928c7e6e6) | Aug 23, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [d74e3d1835](https://linux-hardware.org/?probe=d74e3d1835) | Aug 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [240d31631f](https://linux-hardware.org/?probe=240d31631f) | Aug 19, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6bcc5abfa7](https://linux-hardware.org/?probe=6bcc5abfa7) | Aug 18, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [735e9cba22](https://linux-hardware.org/?probe=735e9cba22) | Aug 18, 2021 |
| Biostar       | Hi-Fi A75S3                 | Desktop     | [f75bdb68fa](https://linux-hardware.org/?probe=f75bdb68fa) | Aug 14, 2021 |
| Acer          | Veriton N4660G              | Desktop     | [7ee989172f](https://linux-hardware.org/?probe=7ee989172f) | Aug 13, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [9b490356cb](https://linux-hardware.org/?probe=9b490356cb) | Aug 11, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [21914d4123](https://linux-hardware.org/?probe=21914d4123) | Aug 11, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [52a8d13536](https://linux-hardware.org/?probe=52a8d13536) | Aug 08, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [11621d5877](https://linux-hardware.org/?probe=11621d5877) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | Notebook    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [6e05bc86aa](https://linux-hardware.org/?probe=6e05bc86aa) | Aug 06, 2021 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [94d76843e6](https://linux-hardware.org/?probe=94d76843e6) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EQS33800     | Notebook    | [2e1468bf31](https://linux-hardware.org/?probe=2e1468bf31) | Aug 02, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [6d45e5794a](https://linux-hardware.org/?probe=6d45e5794a) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c90b5a2e7d](https://linux-hardware.org/?probe=c90b5a2e7d) | Jul 28, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [92c5d52e50](https://linux-hardware.org/?probe=92c5d52e50) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| MSI           | H110M PRO-D                 | Desktop     | [960c966e4b](https://linux-hardware.org/?probe=960c966e4b) | Jul 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| ASRock        | B365 Pro4                   | Desktop     | [af87c52a43](https://linux-hardware.org/?probe=af87c52a43) | Jul 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ab8b0d224b](https://linux-hardware.org/?probe=ab8b0d224b) | Jul 16, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [30dd6fa596](https://linux-hardware.org/?probe=30dd6fa596) | Jul 14, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [ce3b5ecb17](https://linux-hardware.org/?probe=ce3b5ecb17) | Jul 13, 2021 |
| MSI           | MS-7369                     | Desktop     | [caf783ce91](https://linux-hardware.org/?probe=caf783ce91) | Jul 10, 2021 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cda1d2d081](https://linux-hardware.org/?probe=cda1d2d081) | Jul 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [a9b1ac4bdb](https://linux-hardware.org/?probe=a9b1ac4bdb) | Jul 07, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Sony          | SVE1512N1RW                 | Notebook    | [9cfa353121](https://linux-hardware.org/?probe=9cfa353121) | Jul 05, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [09ee8c08c7](https://linux-hardware.org/?probe=09ee8c08c7) | Jul 05, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a0792e787d](https://linux-hardware.org/?probe=a0792e787d) | Jun 30, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [945132609d](https://linux-hardware.org/?probe=945132609d) | Jun 30, 2021 |
| Intel         | H61M-S1                     | Desktop     | [10ef09acce](https://linux-hardware.org/?probe=10ef09acce) | Jun 28, 2021 |
| Samsung       | RV413/RV513                 | Notebook    | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [48f732d759](https://linux-hardware.org/?probe=48f732d759) | Jun 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b34ddd69c9](https://linux-hardware.org/?probe=b34ddd69c9) | Jun 21, 2021 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7fe08a233a](https://linux-hardware.org/?probe=7fe08a233a) | Jun 20, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Intel         | SHARKBAY                    | Desktop     | [f6436bedb8](https://linux-hardware.org/?probe=f6436bedb8) | Jun 16, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ec0c189e56](https://linux-hardware.org/?probe=ec0c189e56) | Jun 15, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a1f4d070a3](https://linux-hardware.org/?probe=a1f4d070a3) | Jun 14, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0c5e09b00c](https://linux-hardware.org/?probe=0c5e09b00c) | Jun 14, 2021 |
| MSI           | MS-7369                     | Desktop     | [9852368309](https://linux-hardware.org/?probe=9852368309) | Jun 13, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [c2803c157e](https://linux-hardware.org/?probe=c2803c157e) | Jun 13, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8380ef5fcb](https://linux-hardware.org/?probe=8380ef5fcb) | Jun 11, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| HP            | Pavilion 15                 | Notebook    | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [4405336208](https://linux-hardware.org/?probe=4405336208) | Jun 01, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [8bdfad6e5a](https://linux-hardware.org/?probe=8bdfad6e5a) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| ASUSTek       | X541UJ                      | Notebook    | [22f4d0228f](https://linux-hardware.org/?probe=22f4d0228f) | May 16, 2021 |
| Timi          | TM1703                      | Notebook    | [a8c47ad7f6](https://linux-hardware.org/?probe=a8c47ad7f6) | May 15, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ECS           | Livermore8                  | Desktop     | [fba5a0dbb7](https://linux-hardware.org/?probe=fba5a0dbb7) | May 12, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3eefcf4b58](https://linux-hardware.org/?probe=3eefcf4b58) | May 11, 2021 |
| Lenovo        | Z710 20250                  | Notebook    | [f3d7663214](https://linux-hardware.org/?probe=f3d7663214) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [06af60abdc](https://linux-hardware.org/?probe=06af60abdc) | May 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [b71c62e752](https://linux-hardware.org/?probe=b71c62e752) | May 09, 2021 |
| Biostar       | H81MLC                      | Desktop     | [d8da680e51](https://linux-hardware.org/?probe=d8da680e51) | May 08, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ec9321bd41](https://linux-hardware.org/?probe=ec9321bd41) | May 08, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [06558373ef](https://linux-hardware.org/?probe=06558373ef) | May 07, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [46872b4b26](https://linux-hardware.org/?probe=46872b4b26) | May 02, 2021 |
| HP            | ProBook 4525s               | Notebook    | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| Dell          | 0CRH6C A02                  | Desktop     | [69cbbfec14](https://linux-hardware.org/?probe=69cbbfec14) | Apr 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [fb5b8d0021](https://linux-hardware.org/?probe=fb5b8d0021) | Apr 29, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [7ec9efef18](https://linux-hardware.org/?probe=7ec9efef18) | Apr 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [3f2270faad](https://linux-hardware.org/?probe=3f2270faad) | Apr 26, 2021 |
| Intel         | H61M-S1                     | Desktop     | [36129cbfda](https://linux-hardware.org/?probe=36129cbfda) | Apr 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [644dd10952](https://linux-hardware.org/?probe=644dd10952) | Apr 22, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [1832412dab](https://linux-hardware.org/?probe=1832412dab) | Apr 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b60d916c33](https://linux-hardware.org/?probe=b60d916c33) | Apr 19, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [309d8603b2](https://linux-hardware.org/?probe=309d8603b2) | Apr 15, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d945be0db8](https://linux-hardware.org/?probe=d945be0db8) | Apr 15, 2021 |
| ASUSTek       | P5Q-EM                      | Desktop     | [d6c3e7cb89](https://linux-hardware.org/?probe=d6c3e7cb89) | Apr 15, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [1e11286470](https://linux-hardware.org/?probe=1e11286470) | Apr 15, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [099a3d1264](https://linux-hardware.org/?probe=099a3d1264) | Apr 15, 2021 |
| HP            | ProBook 445 G6              | Notebook    | [520083c016](https://linux-hardware.org/?probe=520083c016) | Apr 14, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [15bd22b48d](https://linux-hardware.org/?probe=15bd22b48d) | Apr 11, 2021 |
| HP            | 304Ah                       | Desktop     | [66228ce4df](https://linux-hardware.org/?probe=66228ce4df) | Apr 09, 2021 |
| HP            | 304Ah                       | Desktop     | [5d8e8d559a](https://linux-hardware.org/?probe=5d8e8d559a) | Apr 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8de936a2ca](https://linux-hardware.org/?probe=8de936a2ca) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ebd6174247](https://linux-hardware.org/?probe=ebd6174247) | Apr 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [0362943e9e](https://linux-hardware.org/?probe=0362943e9e) | Apr 02, 2021 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [a3e8c4ecb4](https://linux-hardware.org/?probe=a3e8c4ecb4) | Mar 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [3228126df8](https://linux-hardware.org/?probe=3228126df8) | Mar 29, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [1dc07212db](https://linux-hardware.org/?probe=1dc07212db) | Mar 28, 2021 |
| Gigabyte      | GA-770T-D3L                 | Desktop     | [eeeb3a5b5d](https://linux-hardware.org/?probe=eeeb3a5b5d) | Mar 27, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [35964432d7](https://linux-hardware.org/?probe=35964432d7) | Mar 26, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | Notebook    | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| HP            | ProBook 4525s               | Notebook    | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [02a403c967](https://linux-hardware.org/?probe=02a403c967) | Mar 24, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [3157cd3bfe](https://linux-hardware.org/?probe=3157cd3bfe) | Mar 23, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | Notebook    | [97df6a4a9a](https://linux-hardware.org/?probe=97df6a4a9a) | Mar 23, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d2e63cfaa6](https://linux-hardware.org/?probe=d2e63cfaa6) | Mar 22, 2021 |
| Dell          | 0P4T42 A01                  | All in one  | [2f14bf6c71](https://linux-hardware.org/?probe=2f14bf6c71) | Mar 22, 2021 |
| ASUSTek       | P5B                         | Desktop     | [a24c9c6d6a](https://linux-hardware.org/?probe=a24c9c6d6a) | Mar 22, 2021 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c947af2b99](https://linux-hardware.org/?probe=c947af2b99) | Mar 21, 2021 |
| ASUSTek       | UX31A                       | Notebook    | [c6506a0289](https://linux-hardware.org/?probe=c6506a0289) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [18d693f712](https://linux-hardware.org/?probe=18d693f712) | Mar 21, 2021 |
| ASUSTek       | N752VX                      | Notebook    | [48cb617015](https://linux-hardware.org/?probe=48cb617015) | Mar 20, 2021 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [3e2336037f](https://linux-hardware.org/?probe=3e2336037f) | Mar 20, 2021 |
| Acer          | Aspire 5551G                | Notebook    | [1002c3efd0](https://linux-hardware.org/?probe=1002c3efd0) | Mar 19, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [3c9720e16b](https://linux-hardware.org/?probe=3c9720e16b) | Mar 18, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [c63de512e5](https://linux-hardware.org/?probe=c63de512e5) | Mar 18, 2021 |
| HP            | 250 G1                      | Notebook    | [7b14b4e7e5](https://linux-hardware.org/?probe=7b14b4e7e5) | Mar 18, 2021 |
| HP            | ProBook 4525s               | Notebook    | [f9830feb98](https://linux-hardware.org/?probe=f9830feb98) | Mar 17, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | Notebook    | [d2dde464de](https://linux-hardware.org/?probe=d2dde464de) | Mar 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [12eebe7515](https://linux-hardware.org/?probe=12eebe7515) | Mar 17, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [e688898ed8](https://linux-hardware.org/?probe=e688898ed8) | Mar 17, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [8e8d411ccb](https://linux-hardware.org/?probe=8e8d411ccb) | Mar 17, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [658c4e0d17](https://linux-hardware.org/?probe=658c4e0d17) | Mar 17, 2021 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [1b6cfd046e](https://linux-hardware.org/?probe=1b6cfd046e) | Mar 17, 2021 |
| Prestigio     | PSB141C03                   | Notebook    | [82f601055a](https://linux-hardware.org/?probe=82f601055a) | Mar 17, 2021 |
| ASRock        | 990FX Extreme4              | Desktop     | [d1536bcdfa](https://linux-hardware.org/?probe=d1536bcdfa) | Mar 17, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [863c6c5d68](https://linux-hardware.org/?probe=863c6c5d68) | Mar 17, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [51bf91aae7](https://linux-hardware.org/?probe=51bf91aae7) | Mar 14, 2021 |
| HP            | Mini 210-4000               | Notebook    | [9301f9c8ef](https://linux-hardware.org/?probe=9301f9c8ef) | Mar 12, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [72f398fcff](https://linux-hardware.org/?probe=72f398fcff) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [83f50b266f](https://linux-hardware.org/?probe=83f50b266f) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [ed293423f3](https://linux-hardware.org/?probe=ed293423f3) | Mar 11, 2021 |
| HP            | ProBook 4525s               | Notebook    | [912c2f075f](https://linux-hardware.org/?probe=912c2f075f) | Mar 09, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f63d1b8f0b](https://linux-hardware.org/?probe=f63d1b8f0b) | Mar 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [28a8889148](https://linux-hardware.org/?probe=28a8889148) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1df473b11e](https://linux-hardware.org/?probe=1df473b11e) | Mar 03, 2021 |
| Dell          | System XPS L702X            | Notebook    | [1cce147fd2](https://linux-hardware.org/?probe=1cce147fd2) | Feb 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [902d3d474e](https://linux-hardware.org/?probe=902d3d474e) | Feb 25, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [390003cc95](https://linux-hardware.org/?probe=390003cc95) | Feb 24, 2021 |
| MSI           | MS-7250                     | Desktop     | [bd7bbadaad](https://linux-hardware.org/?probe=bd7bbadaad) | Feb 23, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [77748ba0e4](https://linux-hardware.org/?probe=77748ba0e4) | Feb 22, 2021 |
| ASUSTek       | K50C                        | Notebook    | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [8d2b36f7c1](https://linux-hardware.org/?probe=8d2b36f7c1) | Feb 20, 2021 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [80cea1a03a](https://linux-hardware.org/?probe=80cea1a03a) | Feb 19, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | Notebook    | [0f4f85b4c1](https://linux-hardware.org/?probe=0f4f85b4c1) | Feb 19, 2021 |
| Packard Be... | EasyNote TM86               | Notebook    | [f548aa653a](https://linux-hardware.org/?probe=f548aa653a) | Feb 18, 2021 |
| Acer          | Extensa 5230                | Notebook    | [b128a06266](https://linux-hardware.org/?probe=b128a06266) | Feb 17, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [1a52fb16f9](https://linux-hardware.org/?probe=1a52fb16f9) | Feb 16, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [8bb7ec1035](https://linux-hardware.org/?probe=8bb7ec1035) | Feb 15, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [c5877ecd52](https://linux-hardware.org/?probe=c5877ecd52) | Feb 14, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [c500f1eff8](https://linux-hardware.org/?probe=c500f1eff8) | Feb 14, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [76e29e229d](https://linux-hardware.org/?probe=76e29e229d) | Feb 13, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [6262cc3afd](https://linux-hardware.org/?probe=6262cc3afd) | Feb 13, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6969353956](https://linux-hardware.org/?probe=6969353956) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | Notebook    | [3a64cfa43e](https://linux-hardware.org/?probe=3a64cfa43e) | Feb 13, 2021 |
| HP            | Mini 210-4000               | Notebook    | [966136f01f](https://linux-hardware.org/?probe=966136f01f) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | Notebook    | [2e31ed1ec6](https://linux-hardware.org/?probe=2e31ed1ec6) | Feb 13, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [bbc60c2820](https://linux-hardware.org/?probe=bbc60c2820) | Feb 13, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [8f8fd2975a](https://linux-hardware.org/?probe=8f8fd2975a) | Feb 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [440af1645f](https://linux-hardware.org/?probe=440af1645f) | Feb 13, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [02fd7c81f6](https://linux-hardware.org/?probe=02fd7c81f6) | Feb 11, 2021 |
| Acer          | Extensa 7630EZ              | Notebook    | [9a0378eb4d](https://linux-hardware.org/?probe=9a0378eb4d) | Feb 11, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [bbd0961627](https://linux-hardware.org/?probe=bbd0961627) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [6487d4bd7c](https://linux-hardware.org/?probe=6487d4bd7c) | Feb 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8c35b025b2](https://linux-hardware.org/?probe=8c35b025b2) | Feb 08, 2021 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [cbd3e60242](https://linux-hardware.org/?probe=cbd3e60242) | Feb 07, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [d9218caa35](https://linux-hardware.org/?probe=d9218caa35) | Feb 05, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [f4611ac89e](https://linux-hardware.org/?probe=f4611ac89e) | Feb 04, 2021 |
| HP            | 635                         | Notebook    | [e83d58e706](https://linux-hardware.org/?probe=e83d58e706) | Feb 03, 2021 |
| Acer          | Aspire 5551G                | Notebook    | [811535132b](https://linux-hardware.org/?probe=811535132b) | Feb 02, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [e86c3d781d](https://linux-hardware.org/?probe=e86c3d781d) | Jan 31, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [6f78493e97](https://linux-hardware.org/?probe=6f78493e97) | Jan 29, 2021 |
| Lenovo        | ThinkPad T410 2537V28       | Notebook    | [126c75190e](https://linux-hardware.org/?probe=126c75190e) | Jan 22, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [e04d0e066e](https://linux-hardware.org/?probe=e04d0e066e) | Jan 22, 2021 |
| HP            | 255 G2                      | Notebook    | [3ebc0a9b9b](https://linux-hardware.org/?probe=3ebc0a9b9b) | Jan 21, 2021 |
| MSI           | 760GM-P33                   | Desktop     | [f7dbe6391b](https://linux-hardware.org/?probe=f7dbe6391b) | Jan 21, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14022d5350](https://linux-hardware.org/?probe=14022d5350) | Jan 20, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [48644938e9](https://linux-hardware.org/?probe=48644938e9) | Jan 17, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [b3bfbdace0](https://linux-hardware.org/?probe=b3bfbdace0) | Jan 10, 2021 |
| ASUSTek       | N550JK                      | Notebook    | [f12a646f8b](https://linux-hardware.org/?probe=f12a646f8b) | Jan 09, 2021 |
| Acer          | Extensa 2511G               | Notebook    | [ca3628282a](https://linux-hardware.org/?probe=ca3628282a) | Jan 06, 2021 |
| HP            | Mini 5102                   | Notebook    | [76f0b2193f](https://linux-hardware.org/?probe=76f0b2193f) | Jan 06, 2021 |
| HP            | Laptop 15-db1xxx            | Notebook    | [76f271acf1](https://linux-hardware.org/?probe=76f271acf1) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b005d0780d](https://linux-hardware.org/?probe=b005d0780d) | Jan 04, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [7c04f61d39](https://linux-hardware.org/?probe=7c04f61d39) | Jan 04, 2021 |
| Samsung       | SR58P                       | Notebook    | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| MSI           | 760GM-P33                   | Desktop     | [9af10be990](https://linux-hardware.org/?probe=9af10be990) | Jan 03, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [f49ba1df9c](https://linux-hardware.org/?probe=f49ba1df9c) | Jan 01, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [997fd6a726](https://linux-hardware.org/?probe=997fd6a726) | Dec 30, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [8eb79a3a10](https://linux-hardware.org/?probe=8eb79a3a10) | Dec 29, 2020 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [1b0941ddec](https://linux-hardware.org/?probe=1b0941ddec) | Dec 26, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| Gigabyte      | P35-S3G                     | Desktop     | [be95d225fe](https://linux-hardware.org/?probe=be95d225fe) | Dec 22, 2020 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [cf0c42c323](https://linux-hardware.org/?probe=cf0c42c323) | Dec 18, 2020 |
| HP            | 81BA                        | All in one  | [00a2be4ed1](https://linux-hardware.org/?probe=00a2be4ed1) | Dec 18, 2020 |
| Gigabyte      | GA-MA770-DS3                | Desktop     | [43c86b0f1e](https://linux-hardware.org/?probe=43c86b0f1e) | Dec 18, 2020 |
| HP            | 81BA                        | All in one  | [1c8a356387](https://linux-hardware.org/?probe=1c8a356387) | Dec 17, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [f4ae75d77c](https://linux-hardware.org/?probe=f4ae75d77c) | Dec 16, 2020 |
| Dell          | Inspiron 5748               | Notebook    | [091c74353b](https://linux-hardware.org/?probe=091c74353b) | Dec 16, 2020 |
| Lenovo        | B5400 20278                 | Notebook    | [56ea17c80b](https://linux-hardware.org/?probe=56ea17c80b) | Dec 15, 2020 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [5e1b23e45c](https://linux-hardware.org/?probe=5e1b23e45c) | Dec 14, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [b987e4cc7c](https://linux-hardware.org/?probe=b987e4cc7c) | Dec 11, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [f6e40ea1a0](https://linux-hardware.org/?probe=f6e40ea1a0) | Dec 11, 2020 |
| Samsung       | R530/R730                   | Notebook    | [eaf1fed190](https://linux-hardware.org/?probe=eaf1fed190) | Dec 11, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d0d9126db4](https://linux-hardware.org/?probe=d0d9126db4) | Dec 08, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [c6b4560c3e](https://linux-hardware.org/?probe=c6b4560c3e) | Dec 07, 2020 |
| Prestigio     | PSB141C03                   | Notebook    | [4087902d18](https://linux-hardware.org/?probe=4087902d18) | Dec 07, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [a566f76ca4](https://linux-hardware.org/?probe=a566f76ca4) | Dec 07, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [27a4e636f6](https://linux-hardware.org/?probe=27a4e636f6) | Dec 02, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [54886a9cc0](https://linux-hardware.org/?probe=54886a9cc0) | Nov 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [91ff5fdd53](https://linux-hardware.org/?probe=91ff5fdd53) | Nov 28, 2020 |
| ASUSTek       | P5K WS                      | Desktop     | [89a2e1b515](https://linux-hardware.org/?probe=89a2e1b515) | Nov 28, 2020 |
| ASUSTek       | K52N                        | Notebook    | [94f1b7362b](https://linux-hardware.org/?probe=94f1b7362b) | Nov 25, 2020 |
| Acer          | Aspire E1-530               | Notebook    | [e343493113](https://linux-hardware.org/?probe=e343493113) | Nov 25, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | Notebook    | [b265ff82a7](https://linux-hardware.org/?probe=b265ff82a7) | Nov 21, 2020 |
| Lenovo        | ThinkPad E15 20RD0014RT     | Notebook    | [81de71766f](https://linux-hardware.org/?probe=81de71766f) | Nov 21, 2020 |
| Prestigio     | PSB141C02                   | Notebook    | [08aa1ee2ff](https://linux-hardware.org/?probe=08aa1ee2ff) | Nov 20, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [bada67f585](https://linux-hardware.org/?probe=bada67f585) | Nov 20, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [05314304a4](https://linux-hardware.org/?probe=05314304a4) | Nov 19, 2020 |
| ASUSTek       | V200IB                      | Desktop     | [910d5a3bfd](https://linux-hardware.org/?probe=910d5a3bfd) | Nov 19, 2020 |
| Lenovo        | G50-30 80G0                 | Notebook    | [9687208571](https://linux-hardware.org/?probe=9687208571) | Nov 19, 2020 |
| ASUSTek       | X541UAK                     | Notebook    | [c914110be9](https://linux-hardware.org/?probe=c914110be9) | Nov 19, 2020 |
| Acer          | Aspire E1-532G              | Notebook    | [dd90b2f3e2](https://linux-hardware.org/?probe=dd90b2f3e2) | Nov 18, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6abee99a84](https://linux-hardware.org/?probe=6abee99a84) | Nov 18, 2020 |
| Gigabyte      | H81M-S2H                    | Desktop     | [72f585d3fd](https://linux-hardware.org/?probe=72f585d3fd) | Nov 18, 2020 |
| ASUSTek       | V200IB                      | All in one  | [e20ac63341](https://linux-hardware.org/?probe=e20ac63341) | Nov 18, 2020 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [f8de57d305](https://linux-hardware.org/?probe=f8de57d305) | Nov 16, 2020 |
| Samsung       | R508                        | Notebook    | [937a0199e0](https://linux-hardware.org/?probe=937a0199e0) | Nov 16, 2020 |
| ASUSTek       | K52N                        | Notebook    | [a96cd62a24](https://linux-hardware.org/?probe=a96cd62a24) | Nov 14, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [225c61e941](https://linux-hardware.org/?probe=225c61e941) | Nov 13, 2020 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [4eefad2a8b](https://linux-hardware.org/?probe=4eefad2a8b) | Nov 13, 2020 |
| Dell          | Inspiron 5521               | Notebook    | [1080310f19](https://linux-hardware.org/?probe=1080310f19) | Nov 11, 2020 |
| Intel         | SharkBay Platform           | Notebook    | [21647cb222](https://linux-hardware.org/?probe=21647cb222) | Nov 09, 2020 |
| Unknown       | Unknown                     | Notebook    | [091af6961a](https://linux-hardware.org/?probe=091af6961a) | Nov 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [5da1ec78a0](https://linux-hardware.org/?probe=5da1ec78a0) | Nov 07, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [df41815a21](https://linux-hardware.org/?probe=df41815a21) | Nov 06, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | Notebook    | [412e6eca38](https://linux-hardware.org/?probe=412e6eca38) | Nov 05, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | Notebook    | [6fb42db6e5](https://linux-hardware.org/?probe=6fb42db6e5) | Nov 05, 2020 |
| ASRock        | Z370M Pro4                  | Desktop     | [85e45a95e0](https://linux-hardware.org/?probe=85e45a95e0) | Nov 04, 2020 |
| Intel         | SharkBay Platform           | Notebook    | [dcd49fdf3b](https://linux-hardware.org/?probe=dcd49fdf3b) | Nov 04, 2020 |
| Samsung       | R508                        | Notebook    | [7915a99545](https://linux-hardware.org/?probe=7915a99545) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [45666ff7af](https://linux-hardware.org/?probe=45666ff7af) | Nov 01, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [830c1ed47a](https://linux-hardware.org/?probe=830c1ed47a) | Nov 01, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f5328a95d5](https://linux-hardware.org/?probe=f5328a95d5) | Oct 31, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [557aca340e](https://linux-hardware.org/?probe=557aca340e) | Oct 27, 2020 |
| Olimex        | A20-OLinuXino-LIME2         | Soc         | [5a543f3e3e](https://linux-hardware.org/?probe=5a543f3e3e) | Oct 26, 2020 |
| MSI           | 760GM-P33                   | Desktop     | [c611e5bbe5](https://linux-hardware.org/?probe=c611e5bbe5) | Oct 26, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7ae3293c6d](https://linux-hardware.org/?probe=7ae3293c6d) | Oct 26, 2020 |
| Timi          | TM1701                      | Notebook    | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [92fa11d82d](https://linux-hardware.org/?probe=92fa11d82d) | Oct 25, 2020 |
| Dell          | Inspiron 15 5501            | Notebook    | [6a18afe215](https://linux-hardware.org/?probe=6a18afe215) | Oct 25, 2020 |
| ASUSTek       | H81M-E                      | Desktop     | [e149fb7dc2](https://linux-hardware.org/?probe=e149fb7dc2) | Oct 23, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b0e3f9ed28](https://linux-hardware.org/?probe=b0e3f9ed28) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [f21f5a008c](https://linux-hardware.org/?probe=f21f5a008c) | Oct 21, 2020 |
| Gigabyte      | Z390 D                      | Desktop     | [1610651aa5](https://linux-hardware.org/?probe=1610651aa5) | Oct 21, 2020 |
| HP            | 250 G2                      | Notebook    | [164b391add](https://linux-hardware.org/?probe=164b391add) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [50cb6d53ef](https://linux-hardware.org/?probe=50cb6d53ef) | Oct 18, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [0e1b75fc55](https://linux-hardware.org/?probe=0e1b75fc55) | Oct 18, 2020 |
| Acer          | Unknown                     | Notebook    | [5dc51268a1](https://linux-hardware.org/?probe=5dc51268a1) | Oct 17, 2020 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [2fa1f3048b](https://linux-hardware.org/?probe=2fa1f3048b) | Oct 13, 2020 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [ee0649427b](https://linux-hardware.org/?probe=ee0649427b) | Oct 12, 2020 |
| Prestigio     | PSB141C03                   | Notebook    | [eb6b709b25](https://linux-hardware.org/?probe=eb6b709b25) | Oct 12, 2020 |
| Lenovo        | ThinkPad T400 7417CTO       | Notebook    | [41f5d8bbb1](https://linux-hardware.org/?probe=41f5d8bbb1) | Oct 12, 2020 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [479a1ad655](https://linux-hardware.org/?probe=479a1ad655) | Oct 11, 2020 |
| MSI           | MS-7250                     | Desktop     | [c4ef765de1](https://linux-hardware.org/?probe=c4ef765de1) | Oct 10, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [eefad2dd0f](https://linux-hardware.org/?probe=eefad2dd0f) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [1d6ca8e5fc](https://linux-hardware.org/?probe=1d6ca8e5fc) | Oct 09, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b0244dd7f4](https://linux-hardware.org/?probe=b0244dd7f4) | Oct 08, 2020 |
| ASUSTek       | H61M-K                      | Desktop     | [f813fe20d2](https://linux-hardware.org/?probe=f813fe20d2) | Oct 04, 2020 |
| Dell          | G5 5587                     | Notebook    | [7ec299e574](https://linux-hardware.org/?probe=7ec299e574) | Oct 03, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [4308201e9f](https://linux-hardware.org/?probe=4308201e9f) | Sep 28, 2020 |
| ASRock        | 970 Pro3                    | Desktop     | [c4459c622c](https://linux-hardware.org/?probe=c4459c622c) | Sep 27, 2020 |
| Samsung       | R518                        | Notebook    | [c4db2214cd](https://linux-hardware.org/?probe=c4db2214cd) | Sep 27, 2020 |
| Timi          | TM1709                      | Notebook    | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| HP            | 250 G2                      | Notebook    | [0721c128e6](https://linux-hardware.org/?probe=0721c128e6) | Sep 22, 2020 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [271a7bcbeb](https://linux-hardware.org/?probe=271a7bcbeb) | Sep 19, 2020 |
| ASUSTek       | P5KPL-C                     | Desktop     | [6812da21fd](https://linux-hardware.org/?probe=6812da21fd) | Sep 15, 2020 |
| HP            | 304Ah                       | Desktop     | [5acd57b9db](https://linux-hardware.org/?probe=5acd57b9db) | Sep 15, 2020 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [586f647e41](https://linux-hardware.org/?probe=586f647e41) | Sep 13, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [52a401fb4d](https://linux-hardware.org/?probe=52a401fb4d) | Sep 08, 2020 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [a827ce3df1](https://linux-hardware.org/?probe=a827ce3df1) | Sep 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [41ed89087e](https://linux-hardware.org/?probe=41ed89087e) | Aug 31, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ed88384ae9](https://linux-hardware.org/?probe=ed88384ae9) | Aug 31, 2020 |
| MSI           | PS42 Modern 8RA             | Notebook    | [ab71a04043](https://linux-hardware.org/?probe=ab71a04043) | Aug 29, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [22adb53a27](https://linux-hardware.org/?probe=22adb53a27) | Aug 29, 2020 |
| Dell          | Precision 7540              | Notebook    | [8e97d27134](https://linux-hardware.org/?probe=8e97d27134) | Aug 27, 2020 |
| ASUSTek       | U36SG                       | Notebook    | [103ce98981](https://linux-hardware.org/?probe=103ce98981) | Aug 27, 2020 |
| ASRock        | H61M-HVS                    | Desktop     | [4052b1ff8b](https://linux-hardware.org/?probe=4052b1ff8b) | Aug 25, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [aaae1d3e78](https://linux-hardware.org/?probe=aaae1d3e78) | Aug 24, 2020 |
| Dell          | Vostro 5490                 | Notebook    | [873e3c07c7](https://linux-hardware.org/?probe=873e3c07c7) | Aug 24, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a7b737f065](https://linux-hardware.org/?probe=a7b737f065) | Aug 23, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [494bb32560](https://linux-hardware.org/?probe=494bb32560) | Aug 23, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [9c05eb6ed3](https://linux-hardware.org/?probe=9c05eb6ed3) | Aug 20, 2020 |
| ASRock        | 990FX Extreme4              | Desktop     | [9d89158c0c](https://linux-hardware.org/?probe=9d89158c0c) | Aug 19, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [42cfca7021](https://linux-hardware.org/?probe=42cfca7021) | Aug 14, 2020 |
| Acer          | Aspire 4810T                | Notebook    | [5ff79d2a64](https://linux-hardware.org/?probe=5ff79d2a64) | Aug 09, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [16796af2c3](https://linux-hardware.org/?probe=16796af2c3) | Aug 06, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [6ca9ef29fc](https://linux-hardware.org/?probe=6ca9ef29fc) | Aug 02, 2020 |
| ASUSTek       | P8H61 R2.0                  | Desktop     | [b9790bef81](https://linux-hardware.org/?probe=b9790bef81) | Aug 02, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [9b0eb8f018](https://linux-hardware.org/?probe=9b0eb8f018) | Aug 01, 2020 |
| Timi          | TM1701                      | Notebook    | [71882c9121](https://linux-hardware.org/?probe=71882c9121) | Jul 31, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [d38b29e9f6](https://linux-hardware.org/?probe=d38b29e9f6) | Jul 29, 2020 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [8d5ce15006](https://linux-hardware.org/?probe=8d5ce15006) | Jul 29, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [b5e0ef963b](https://linux-hardware.org/?probe=b5e0ef963b) | Jul 26, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [def2e542ec](https://linux-hardware.org/?probe=def2e542ec) | Jul 25, 2020 |
| ASUSTek       | P8H77-V                     | Desktop     | [ad01a90f9c](https://linux-hardware.org/?probe=ad01a90f9c) | Jul 23, 2020 |
| Timi          | TM1701                      | Notebook    | [024ed71324](https://linux-hardware.org/?probe=024ed71324) | Jul 22, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [791afa1495](https://linux-hardware.org/?probe=791afa1495) | Jul 16, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [220af5d9fe](https://linux-hardware.org/?probe=220af5d9fe) | Jul 15, 2020 |
| Acer          | Aspire E1-731               | Notebook    | [e055f89ff6](https://linux-hardware.org/?probe=e055f89ff6) | Jul 15, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [acd59fc735](https://linux-hardware.org/?probe=acd59fc735) | Jul 15, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [744a29218a](https://linux-hardware.org/?probe=744a29218a) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [986a151279](https://linux-hardware.org/?probe=986a151279) | Jul 09, 2020 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [322ef5e555](https://linux-hardware.org/?probe=322ef5e555) | Jul 06, 2020 |
| HP            | ProBook 445 G6              | Notebook    | [e82b679ba1](https://linux-hardware.org/?probe=e82b679ba1) | Jul 05, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [caebcd4a78](https://linux-hardware.org/?probe=caebcd4a78) | Jul 03, 2020 |
| Intel         | Braswell Platform           | Tablet      | [009bee9446](https://linux-hardware.org/?probe=009bee9446) | Jul 01, 2020 |
| Intel         | Braswell Platform           | Tablet      | [00c847073c](https://linux-hardware.org/?probe=00c847073c) | Jul 01, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [a6dcbcadc4](https://linux-hardware.org/?probe=a6dcbcadc4) | Jun 30, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [0e0fe8368c](https://linux-hardware.org/?probe=0e0fe8368c) | Jun 30, 2020 |
| HP            | Stream x360 Convertible ... | Convertible | [95bded4004](https://linux-hardware.org/?probe=95bded4004) | Jun 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [df5777de6d](https://linux-hardware.org/?probe=df5777de6d) | Jun 29, 2020 |
| LG Electro... | R510                        | Notebook    | [51967b227c](https://linux-hardware.org/?probe=51967b227c) | Jun 29, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [b439507f1a](https://linux-hardware.org/?probe=b439507f1a) | Jun 25, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [4d3573e05d](https://linux-hardware.org/?probe=4d3573e05d) | Jun 18, 2020 |
| ASRock        | N68C-GS FX                  | Desktop     | [31fcf823d4](https://linux-hardware.org/?probe=31fcf823d4) | Jun 18, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [566a257192](https://linux-hardware.org/?probe=566a257192) | Jun 07, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [59c6b9d06f](https://linux-hardware.org/?probe=59c6b9d06f) | Jun 06, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [f1a595ed8a](https://linux-hardware.org/?probe=f1a595ed8a) | Jun 05, 2020 |
| ASUSTek       | X541UJ                      | Notebook    | [4116c24ad8](https://linux-hardware.org/?probe=4116c24ad8) | Jun 03, 2020 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [53eafad041](https://linux-hardware.org/?probe=53eafad041) | Jun 02, 2020 |
| HP            | ProBook 4740s               | Notebook    | [bac1c80c34](https://linux-hardware.org/?probe=bac1c80c34) | Jun 02, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [b73508569c](https://linux-hardware.org/?probe=b73508569c) | May 30, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [178a726d73](https://linux-hardware.org/?probe=178a726d73) | May 28, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [dbfbd4b70e](https://linux-hardware.org/?probe=dbfbd4b70e) | May 28, 2020 |
| ASUSTek       | S551LB                      | Notebook    | [4aed54f228](https://linux-hardware.org/?probe=4aed54f228) | May 28, 2020 |
| HP            | 255 G2                      | Notebook    | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire VN7-592G             | Notebook    | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| HP            | Notebook                    | Notebook    | [672d0acfa1](https://linux-hardware.org/?probe=672d0acfa1) | May 26, 2020 |
| HP            | Notebook                    | Notebook    | [1fa50923d3](https://linux-hardware.org/?probe=1fa50923d3) | May 26, 2020 |
| ASRock        | P43D1600Twins-1394          | Desktop     | [9eb0959f24](https://linux-hardware.org/?probe=9eb0959f24) | May 25, 2020 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [ed7fe704dd](https://linux-hardware.org/?probe=ed7fe704dd) | May 25, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [670301a3f3](https://linux-hardware.org/?probe=670301a3f3) | May 25, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f27378d43f](https://linux-hardware.org/?probe=f27378d43f) | May 25, 2020 |
| Acer          | AOA150                      | Notebook    | [4879ee6a95](https://linux-hardware.org/?probe=4879ee6a95) | May 24, 2020 |
| Gigabyte      | P55M-UD4                    | Desktop     | [cb5f5644c1](https://linux-hardware.org/?probe=cb5f5644c1) | May 21, 2020 |
| ASRock        | Z77 Extreme3                | Desktop     | [46d7fb23b0](https://linux-hardware.org/?probe=46d7fb23b0) | May 21, 2020 |
| Digma         | CITI 1804 CS1069EW          | Tablet      | [ea033fde6a](https://linux-hardware.org/?probe=ea033fde6a) | May 15, 2020 |
| Prestigio     | Multipad Visconte V         | Notebook    | [d3f3e2e2b4](https://linux-hardware.org/?probe=d3f3e2e2b4) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e82eb79af2](https://linux-hardware.org/?probe=e82eb79af2) | May 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [06d027143f](https://linux-hardware.org/?probe=06d027143f) | May 11, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [ff446033f4](https://linux-hardware.org/?probe=ff446033f4) | May 07, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [9b3d9029ea](https://linux-hardware.org/?probe=9b3d9029ea) | May 03, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [fbdced7593](https://linux-hardware.org/?probe=fbdced7593) | Apr 30, 2020 |
| Timi          | TM1613                      | Notebook    | [5f55af6b8d](https://linux-hardware.org/?probe=5f55af6b8d) | Apr 27, 2020 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [828fc9a788](https://linux-hardware.org/?probe=828fc9a788) | Apr 26, 2020 |
| MSI           | MS-7250                     | Desktop     | [9aafa9594b](https://linux-hardware.org/?probe=9aafa9594b) | Apr 18, 2020 |
| ASUSTek       | N551JM                      | Notebook    | [cd375242d3](https://linux-hardware.org/?probe=cd375242d3) | Apr 15, 2020 |
| MSI           | MS-7507                     | Desktop     | [f33b052aed](https://linux-hardware.org/?probe=f33b052aed) | Apr 14, 2020 |
| Gigabyte      | D525TUD                     | Desktop     | [16b44a22f0](https://linux-hardware.org/?probe=16b44a22f0) | Apr 13, 2020 |
| Acer          | Aspire A315-42G             | Notebook    | [e050431a72](https://linux-hardware.org/?probe=e050431a72) | Apr 09, 2020 |
| Acer          | Aspire A315-42G             | Notebook    | [13a642b394](https://linux-hardware.org/?probe=13a642b394) | Apr 09, 2020 |
| HP            | ProBook 4710s               | Notebook    | [56f533f0f5](https://linux-hardware.org/?probe=56f533f0f5) | Apr 07, 2020 |
| HP            | Notebook                    | Notebook    | [d32a1f4247](https://linux-hardware.org/?probe=d32a1f4247) | Mar 30, 2020 |
| Acer          | Aspire 4810T                | Notebook    | [b7d82235f8](https://linux-hardware.org/?probe=b7d82235f8) | Mar 22, 2020 |
| Acer          | TravelMate P259-M           | Notebook    | [596bd79c7a](https://linux-hardware.org/?probe=596bd79c7a) | Mar 22, 2020 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [b0522c8711](https://linux-hardware.org/?probe=b0522c8711) | Mar 19, 2020 |
| Lenovo        | ThinkPad T61 7661WPF        | Notebook    | [ce22405483](https://linux-hardware.org/?probe=ce22405483) | Mar 19, 2020 |
| ASUSTek       | K52N                        | Notebook    | [a1fea085d9](https://linux-hardware.org/?probe=a1fea085d9) | Mar 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e0fa6f7e5](https://linux-hardware.org/?probe=0e0fa6f7e5) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0c7024795f](https://linux-hardware.org/?probe=0c7024795f) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [526830e223](https://linux-hardware.org/?probe=526830e223) | Mar 17, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [e37fc99e67](https://linux-hardware.org/?probe=e37fc99e67) | Mar 11, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [efbd3772bc](https://linux-hardware.org/?probe=efbd3772bc) | Mar 09, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [123e49a129](https://linux-hardware.org/?probe=123e49a129) | Mar 07, 2020 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a451b0d94d](https://linux-hardware.org/?probe=a451b0d94d) | Mar 07, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [2938ca5aec](https://linux-hardware.org/?probe=2938ca5aec) | Mar 03, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [7c909cb955](https://linux-hardware.org/?probe=7c909cb955) | Mar 01, 2020 |
| Acer          | Extensa 5220                | Notebook    | [3ac52b68ad](https://linux-hardware.org/?probe=3ac52b68ad) | Mar 01, 2020 |
| Dell          | Inspiron 3576               | Notebook    | [c0fb2f48aa](https://linux-hardware.org/?probe=c0fb2f48aa) | Feb 29, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [a5cca23283](https://linux-hardware.org/?probe=a5cca23283) | Feb 29, 2020 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [18f5afd1ed](https://linux-hardware.org/?probe=18f5afd1ed) | Feb 28, 2020 |
| ASRock        | 960GC-GS FX                 | Desktop     | [88acae56fa](https://linux-hardware.org/?probe=88acae56fa) | Feb 28, 2020 |
| Packard Be... | DOT S                       | Notebook    | [cd2b5a2715](https://linux-hardware.org/?probe=cd2b5a2715) | Feb 28, 2020 |
| Packard Be... | DOT S                       | Notebook    | [8db7395b33](https://linux-hardware.org/?probe=8db7395b33) | Feb 27, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [9192ccbb93](https://linux-hardware.org/?probe=9192ccbb93) | Feb 26, 2020 |
| Timi          | TM1701                      | Notebook    | [4185035b5f](https://linux-hardware.org/?probe=4185035b5f) | Feb 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [619c9af84e](https://linux-hardware.org/?probe=619c9af84e) | Feb 25, 2020 |
| HP            | Pavilion g6                 | Notebook    | [4e0759261c](https://linux-hardware.org/?probe=4e0759261c) | Feb 24, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [8e0229807b](https://linux-hardware.org/?probe=8e0229807b) | Feb 24, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [dda987c8c9](https://linux-hardware.org/?probe=dda987c8c9) | Feb 24, 2020 |
| Acer          | Aspire E1-571G              | Notebook    | [9951bcb215](https://linux-hardware.org/?probe=9951bcb215) | Feb 23, 2020 |
| Packard Be... | DOT S                       | Notebook    | [ef2c3a6924](https://linux-hardware.org/?probe=ef2c3a6924) | Feb 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f3185269f](https://linux-hardware.org/?probe=3f3185269f) | Feb 18, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [fe39ad1f52](https://linux-hardware.org/?probe=fe39ad1f52) | Feb 13, 2020 |
| ASUSTek       | K70AE                       | Notebook    | [1c9b37e0bf](https://linux-hardware.org/?probe=1c9b37e0bf) | Feb 12, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [8d3edd49c5](https://linux-hardware.org/?probe=8d3edd49c5) | Feb 11, 2020 |
| Dell          | System XPS L702X            | Notebook    | [17383a48fc](https://linux-hardware.org/?probe=17383a48fc) | Feb 06, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | Notebook    | [1864afd83f](https://linux-hardware.org/?probe=1864afd83f) | Feb 03, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [8b15a6370b](https://linux-hardware.org/?probe=8b15a6370b) | Feb 01, 2020 |
| Acer          | Aspire V5-561G              | Notebook    | [a646ea611f](https://linux-hardware.org/?probe=a646ea611f) | Jan 29, 2020 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | Notebook    | [cd7471d773](https://linux-hardware.org/?probe=cd7471d773) | Jan 25, 2020 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [38709aec79](https://linux-hardware.org/?probe=38709aec79) | Jan 25, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [c97d5c5a5e](https://linux-hardware.org/?probe=c97d5c5a5e) | Jan 24, 2020 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [659e0d3a62](https://linux-hardware.org/?probe=659e0d3a62) | Jan 24, 2020 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [1c4e4c5a2d](https://linux-hardware.org/?probe=1c4e4c5a2d) | Jan 24, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [3e955a15c1](https://linux-hardware.org/?probe=3e955a15c1) | Jan 22, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [adc392749f](https://linux-hardware.org/?probe=adc392749f) | Jan 22, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [485f1149df](https://linux-hardware.org/?probe=485f1149df) | Jan 20, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [87c3bdc009](https://linux-hardware.org/?probe=87c3bdc009) | Jan 19, 2020 |
| ASUSTek       | X705UQR                     | Notebook    | [bc34d4d0e9](https://linux-hardware.org/?probe=bc34d4d0e9) | Jan 19, 2020 |
| ASUSTek       | UL30A                       | Notebook    | [f9f8ddf425](https://linux-hardware.org/?probe=f9f8ddf425) | Jan 14, 2020 |
| ASRock        | Z77 Extreme4-M              | Desktop     | [14e729f5aa](https://linux-hardware.org/?probe=14e729f5aa) | Jan 13, 2020 |
| ASUSTek       | X540SA                      | Notebook    | [22047ce8bb](https://linux-hardware.org/?probe=22047ce8bb) | Jan 11, 2020 |
| HP            | Unknown                     | Notebook    | [7845d03a39](https://linux-hardware.org/?probe=7845d03a39) | Jan 11, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [87e363c1ed](https://linux-hardware.org/?probe=87e363c1ed) | Jan 10, 2020 |
| Biostar       | NF520-A2 TE                 | Desktop     | [cd41d93f63](https://linux-hardware.org/?probe=cd41d93f63) | Jan 06, 2020 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [a3ff07d84b](https://linux-hardware.org/?probe=a3ff07d84b) | Jan 04, 2020 |
| HP            | ProBook 455 G1              | Notebook    | [08dcbaa82a](https://linux-hardware.org/?probe=08dcbaa82a) | Jan 02, 2020 |
| HP            | ProBook 4530s               | Notebook    | [48ca791cd2](https://linux-hardware.org/?probe=48ca791cd2) | Jan 02, 2020 |
| Samsung       | R519/R719                   | Notebook    | [1a0ac991d0](https://linux-hardware.org/?probe=1a0ac991d0) | Jan 01, 2020 |
| ASUSTek       | K53Z                        | Notebook    | [51da8ec92c](https://linux-hardware.org/?probe=51da8ec92c) | Jan 01, 2020 |
| Unknown       | Unknown                     | Phone       | [fb11f725d3](https://linux-hardware.org/?probe=fb11f725d3) | Dec 31, 2019 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [54845cd095](https://linux-hardware.org/?probe=54845cd095) | Dec 29, 2019 |
| Acer          | Veriton N4660G              | Desktop     | [9afe548805](https://linux-hardware.org/?probe=9afe548805) | Dec 29, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [e96c98384b](https://linux-hardware.org/?probe=e96c98384b) | Dec 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [9f38052441](https://linux-hardware.org/?probe=9f38052441) | Dec 28, 2019 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [c77563a5fb](https://linux-hardware.org/?probe=c77563a5fb) | Dec 23, 2019 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [02221c3f6b](https://linux-hardware.org/?probe=02221c3f6b) | Dec 19, 2019 |
| ASRock        | Z390 Phantom Gaming SLI     | Desktop     | [60a1413416](https://linux-hardware.org/?probe=60a1413416) | Dec 19, 2019 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [2575da9f64](https://linux-hardware.org/?probe=2575da9f64) | Dec 18, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [57160cc915](https://linux-hardware.org/?probe=57160cc915) | Dec 16, 2019 |
| Samsung       | R508                        | Notebook    | [f2d52e0253](https://linux-hardware.org/?probe=f2d52e0253) | Dec 12, 2019 |
| ASUSTek       | X540NV                      | Notebook    | [e1396088af](https://linux-hardware.org/?probe=e1396088af) | Dec 11, 2019 |
| ASUSTek       | X540NV                      | Notebook    | [0649347201](https://linux-hardware.org/?probe=0649347201) | Dec 11, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c6838b1dba](https://linux-hardware.org/?probe=c6838b1dba) | Dec 11, 2019 |
| Packard Be... | DOT S                       | Notebook    | [5bd4609615](https://linux-hardware.org/?probe=5bd4609615) | Dec 09, 2019 |
| HP            | Pavilion 17                 | Notebook    | [e5c53c61e8](https://linux-hardware.org/?probe=e5c53c61e8) | Dec 08, 2019 |
| Lenovo        | ThinkPad SL510 2875RS2      | Notebook    | [4b5548d0bb](https://linux-hardware.org/?probe=4b5548d0bb) | Dec 05, 2019 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [3d3f27a3f9](https://linux-hardware.org/?probe=3d3f27a3f9) | Dec 04, 2019 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [559d304205](https://linux-hardware.org/?probe=559d304205) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | Notebook    | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Pavilion 15                 | Notebook    | [03188ddfb3](https://linux-hardware.org/?probe=03188ddfb3) | Dec 03, 2019 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [08835d6477](https://linux-hardware.org/?probe=08835d6477) | Dec 03, 2019 |
| ASRock        | G31M-S                      | Desktop     | [674951f8cf](https://linux-hardware.org/?probe=674951f8cf) | Dec 03, 2019 |
| MSI           | 760GM-P33                   | Desktop     | [b14d738927](https://linux-hardware.org/?probe=b14d738927) | Dec 02, 2019 |
| Dell          | Inspiron 5559               | Notebook    | [5a4aaf46f2](https://linux-hardware.org/?probe=5a4aaf46f2) | Dec 02, 2019 |
| HP            | ProBook 450 G5              | Notebook    | [9441c13ce5](https://linux-hardware.org/?probe=9441c13ce5) | Dec 02, 2019 |
| MSI           | GP72 7RDX                   | Notebook    | [445ae9719a](https://linux-hardware.org/?probe=445ae9719a) | Dec 02, 2019 |
| Dell          | Latitude E5450              | Notebook    | [9d71909e26](https://linux-hardware.org/?probe=9d71909e26) | Dec 02, 2019 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [15a59f41a1](https://linux-hardware.org/?probe=15a59f41a1) | Nov 27, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [320dde739d](https://linux-hardware.org/?probe=320dde739d) | Nov 27, 2019 |
| Acer          | Aspire E1-530               | Notebook    | [47bc99ddc7](https://linux-hardware.org/?probe=47bc99ddc7) | Nov 27, 2019 |
| Lenovo        | Remore CRB No DPK           | All in one  | [cd624c7ba5](https://linux-hardware.org/?probe=cd624c7ba5) | Nov 27, 2019 |
| Acer          | Aspire E1-532               | Notebook    | [ecb10a3db1](https://linux-hardware.org/?probe=ecb10a3db1) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a7b57eaddf](https://linux-hardware.org/?probe=a7b57eaddf) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | Desktop     | [bcb59e4acf](https://linux-hardware.org/?probe=bcb59e4acf) | Nov 27, 2019 |
| Gigabyte      | H81M-S2H                    | Desktop     | [67a75ff7c4](https://linux-hardware.org/?probe=67a75ff7c4) | Nov 26, 2019 |
| ASUSTek       | V200IB                      | All in one  | [da374c3c83](https://linux-hardware.org/?probe=da374c3c83) | Nov 26, 2019 |
| ASUSTek       | V200IB                      | Desktop     | [61357ecaed](https://linux-hardware.org/?probe=61357ecaed) | Nov 26, 2019 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3baee5b588](https://linux-hardware.org/?probe=3baee5b588) | Nov 26, 2019 |
| Acer          | Aspire E1-530               | Notebook    | [e6b4056c8c](https://linux-hardware.org/?probe=e6b4056c8c) | Nov 26, 2019 |
| ASRock        | H61M-VG4                    | Desktop     | [787fad97da](https://linux-hardware.org/?probe=787fad97da) | Nov 26, 2019 |
| Toshiba       | SATEGO X200                 | Notebook    | [087c0e291d](https://linux-hardware.org/?probe=087c0e291d) | Nov 25, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [b85f41a113](https://linux-hardware.org/?probe=b85f41a113) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [5ded5e4dc0](https://linux-hardware.org/?probe=5ded5e4dc0) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [b0e6d88437](https://linux-hardware.org/?probe=b0e6d88437) | Nov 23, 2019 |
| Packard Be... | EasyNote TK36               | Notebook    | [f86cacb590](https://linux-hardware.org/?probe=f86cacb590) | Nov 23, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belarus/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 123       | 11.17%  |
| ROSA R11                     | 106       | 9.63%   |
| ROSA R8.1                    | 81        | 7.36%   |
| Ubuntu 20.04                 | 62        | 5.63%   |
| ROSA R9                      | 49        | 4.45%   |
| ROSA R11.1                   | 47        | 4.27%   |
| Ubuntu 18.04                 | 39        | 3.54%   |
| ROSA R8                      | 37        | 3.36%   |
| ROSA 12.2                    | 31        | 2.82%   |
| OpenMandriva 4.2             | 24        | 2.18%   |
| ROSA 12.3                    | 19        | 1.73%   |
| Manjaro                      | 17        | 1.54%   |
| Ubuntu 22.04                 | 16        | 1.45%   |
| Fedora 36                    | 15        | 1.36%   |
| Debian 11                    | 15        | 1.36%   |
| Linux Mint 19.3              | 13        | 1.18%   |
| OpenMandriva 4.3             | 12        | 1.09%   |
| Linux Mint 20.3              | 12        | 1.09%   |
| KDE neon 20.04               | 12        | 1.09%   |
| Fedora 35                    | 12        | 1.09%   |
| Arch Rolling                 | 12        | 1.09%   |
| Arch                         | 11        | 1%      |
| Fedora 34                    | 10        | 0.91%   |
| Linux Mint 21.1              | 9         | 0.82%   |
| Kubuntu 20.04                | 9         | 0.82%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.73%   |
| Fedora 37                    | 8         | 0.73%   |
| Ubuntu 22.10                 | 7         | 0.64%   |
| OpenMandriva 23.03           | 6         | 0.54%   |
| Fedora 32                    | 6         | 0.54%   |
| Fedora 31                    | 6         | 0.54%   |
| Debian 10                    | 6         | 0.54%   |
| Xubuntu 20.04                | 5         | 0.45%   |
| Ubuntu 21.04                 | 5         | 0.45%   |
| ROSA 12.4                    | 5         | 0.45%   |
| Manjaro 20.2.1               | 5         | 0.45%   |
| Linux Mint 20                | 5         | 0.45%   |
| Linux Mint 19.1              | 5         | 0.45%   |
| Linux Mint 19                | 5         | 0.45%   |
| Fedora 33                    | 5         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| ROSA             | 424       | 43.67%  |
| Ubuntu           | 138       | 14.21%  |
| Linux Mint       | 64        | 6.59%   |
| Fedora           | 47        | 4.84%   |
| OpenMandriva     | 46        | 4.74%   |
| Manjaro          | 41        | 4.22%   |
| Endless          | 38        | 3.91%   |
| Debian           | 29        | 2.99%   |
| Arch             | 22        | 2.27%   |
| Kubuntu          | 16        | 1.65%   |
| KDE neon         | 16        | 1.65%   |
| Xubuntu          | 11        | 1.13%   |
| Gentoo           | 10        | 1.03%   |
| openSUSE         | 9         | 0.93%   |
| LMDE             | 7         | 0.72%   |
| Elementary       | 6         | 0.62%   |
| Pop!_OS          | 5         | 0.51%   |
| Zorin            | 4         | 0.41%   |
| Lubuntu          | 4         | 0.41%   |
| Kali             | 4         | 0.41%   |
| Ubuntu MATE      | 3         | 0.31%   |
| Clear Linux      | 3         | 0.31%   |
| BlackPanther     | 3         | 0.31%   |
| ArcoLinux        | 3         | 0.31%   |
| MX               | 2         | 0.21%   |
| CentOS           | 2         | 0.21%   |
| ALT Linux        | 2         | 0.21%   |
| Ubuntu Unity     | 1         | 0.1%    |
| Ubuntu Budgie    | 1         | 0.1%    |
| Solus            | 1         | 0.1%    |
| RHEL             | 1         | 0.1%    |
| Q4OS             | 1         | 0.1%    |
| Peppermint       | 1         | 0.1%    |
| Parrot           | 1         | 0.1%    |
| org.kde.Platform | 1         | 0.1%    |
| Mageia           | 1         | 0.1%    |
| Devuan           | 1         | 0.1%    |
| Deepin           | 1         | 0.1%    |
| Android          | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 60        | 4.86%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 42        | 3.4%    |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 39        | 3.16%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 31        | 2.51%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 27        | 2.19%   |
| 5.10.14-desktop-1omv4002            | 23        | 1.86%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 20        | 1.62%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 19        | 1.54%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 18        | 1.46%   |
| 5.4.83-generic-2rosa-x86_64         | 16        | 1.3%    |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 16        | 1.3%    |
| 4.15.0-desktop-45.1rosa-i586        | 15        | 1.22%   |
| 5.4.0-42-generic                    | 13        | 1.05%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 13        | 1.05%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 12        | 0.97%   |
| 5.16.7-desktop-1omv4003             | 11        | 0.89%   |
| 5.15.0-56-generic                   | 11        | 0.89%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 11        | 0.89%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 10        | 0.81%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 10        | 0.81%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 10        | 0.81%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 9         | 0.73%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 8         | 0.65%   |
| 5.4.32-generic-2rosa-x86_64         | 7         | 0.57%   |
| 4.9.155-nrj-laptop-1rosa-x86_64     | 7         | 0.57%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 7         | 0.57%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 7         | 0.57%   |
| 5.9.16-1-MANJARO                    | 6         | 0.49%   |
| 5.8.0-14-generic                    | 6         | 0.49%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 6         | 0.49%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 6         | 0.49%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 6         | 0.49%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 6         | 0.49%   |
| 5.4.0-58-generic                    | 5         | 0.41%   |
| 5.4.0-48-generic                    | 5         | 0.41%   |
| 5.3.0-28-generic                    | 5         | 0.41%   |
| 5.0.0-37-generic                    | 5         | 0.41%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 5         | 0.41%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 5         | 0.41%   |
| 4.15.0-desktop-54.1rosa-x86_64      | 5         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 138       | 11.47%  |
| 5.4.0   | 82        | 6.82%   |
| 4.9.60  | 71        | 5.9%    |
| 4.9.20  | 49        | 4.07%   |
| 5.15.0  | 39        | 3.24%   |
| 4.9.124 | 33        | 2.74%   |
| 5.8.0   | 31        | 2.58%   |
| 5.10.74 | 31        | 2.58%   |
| 4.9.155 | 27        | 2.24%   |
| 4.1.38  | 27        | 2.24%   |
| 5.11.0  | 25        | 2.08%   |
| 5.10.0  | 25        | 2.08%   |
| 4.1.34  | 25        | 2.08%   |
| 5.10.14 | 23        | 1.91%   |
| 5.0.0   | 23        | 1.91%   |
| 4.9.9   | 22        | 1.83%   |
| 4.9.76  | 22        | 1.83%   |
| 5.4.83  | 20        | 1.66%   |
| 5.3.0   | 20        | 1.66%   |
| 5.13.0  | 20        | 1.66%   |
| 5.19.0  | 14        | 1.16%   |
| 4.9.41  | 14        | 1.16%   |
| 4.18.0  | 13        | 1.08%   |
| 5.16.7  | 11        | 0.91%   |
| 5.15.75 | 11        | 0.91%   |
| 4.19.0  | 9         | 0.75%   |
| 4.13.0  | 9         | 0.75%   |
| 5.9.16  | 8         | 0.67%   |
| 5.4.32  | 8         | 0.67%   |
| 4.9.95  | 7         | 0.58%   |
| 6.1.0   | 6         | 0.5%    |
| 5.15.79 | 6         | 0.5%    |
| 4.9.87  | 6         | 0.5%    |
| 4.9.111 | 6         | 0.5%    |
| 6.1.1   | 5         | 0.42%   |
| 6.2.6   | 4         | 0.33%   |
| 6.2.2   | 4         | 0.33%   |
| 5.14.0  | 4         | 0.33%   |
| 4.9.34  | 4         | 0.33%   |
| 4.8.17  | 4         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 214       | 19.23%  |
| 4.15    | 138       | 12.4%   |
| 5.4     | 126       | 11.32%  |
| 5.10    | 95        | 8.54%   |
| 5.15    | 81        | 7.28%   |
| 4.1     | 55        | 4.94%   |
| 5.8     | 39        | 3.5%    |
| 5.11    | 35        | 3.14%   |
| 5.3     | 29        | 2.61%   |
| 5.13    | 29        | 2.61%   |
| 5.19    | 24        | 2.16%   |
| 5.0     | 24        | 2.16%   |
| 6.1     | 23        | 2.07%   |
| 5.9     | 19        | 1.71%   |
| 5.16    | 18        | 1.62%   |
| 6.2     | 17        | 1.53%   |
| 4.18    | 16        | 1.44%   |
| 4.19    | 15        | 1.35%   |
| 6.0     | 14        | 1.26%   |
| 5.18    | 14        | 1.26%   |
| 5.14    | 12        | 1.08%   |
| 5.6     | 11        | 0.99%   |
| 5.17    | 9         | 0.81%   |
| 4.13    | 9         | 0.81%   |
| 5.12    | 8         | 0.72%   |
| 4.8     | 8         | 0.72%   |
| 5.7     | 5         | 0.45%   |
| 4.4     | 5         | 0.45%   |
| 4.14    | 5         | 0.45%   |
| 5.5     | 4         | 0.36%   |
| 4.17    | 3         | 0.27%   |
| 4.16    | 3         | 0.27%   |
| 4.10    | 2         | 0.18%   |
| 5.1     | 1         | 0.09%   |
| 4.20    | 1         | 0.09%   |
| 4.12    | 1         | 0.09%   |
| 3.4     | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 857       | 90.5%   |
| i686   | 88        | 9.29%   |
| armv7l | 2         | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE4       | 278       | 27.55%  |
| KDE5       | 247       | 24.48%  |
| GNOME      | 231       | 22.89%  |
| Unknown    | 77        | 7.63%   |
| XFCE       | 48        | 4.76%   |
| X-Cinnamon | 40        | 3.96%   |
| LXQt       | 24        | 2.38%   |
| MATE       | 17        | 1.68%   |
| KDE        | 15        | 1.49%   |
| Cinnamon   | 11        | 1.09%   |
| Pantheon   | 5         | 0.5%    |
| LXDE       | 5         | 0.5%    |
| i3         | 2         | 0.2%    |
| Deepin     | 2         | 0.2%    |
| Unity      | 1         | 0.1%    |
| Trinity    | 1         | 0.1%    |
| sway       | 1         | 0.1%    |
| Openbox    | 1         | 0.1%    |
| chadwm     | 1         | 0.1%    |
| Budgie     | 1         | 0.1%    |
| bspwm      | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 794       | 82.28%  |
| Wayland | 120       | 12.44%  |
| Unknown | 40        | 4.15%   |
| Tty     | 11        | 1.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 280       | 28%     |
| SDDM    | 255       | 25.5%   |
| Unknown | 234       | 23.4%   |
| GDM     | 112       | 11.2%   |
| LightDM | 50        | 5%      |
| GDM3    | 36        | 3.6%    |
| TDM     | 29        | 2.9%    |
| MDM     | 2         | 0.2%    |
| SLiM    | 1         | 0.1%    |
| GREETD  | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 416       | 42.67%  |
| ru_RU       | 345       | 35.38%  |
| en_US       | 165       | 16.92%  |
| be_BY       | 15        | 1.54%   |
| en_GB       | 11        | 1.13%   |
| C           | 9         | 0.92%   |
| ru_RU.UTF_8 | 6         | 0.62%   |
| ru_UA       | 3         | 0.31%   |
| ru_BY       | 2         | 0.21%   |
| cv_RU       | 2         | 0.21%   |
| en_CA       | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 559       | 57.99%  |
| EFI  | 405       | 42.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 630       | 62.94%  |
| Unknown | 242       | 24.18%  |
| Btrfs   | 66        | 6.59%   |
| Overlay | 46        | 4.6%    |
| Xfs     | 5         | 0.5%    |
| Ext3    | 4         | 0.4%    |
| Tmpfs   | 2         | 0.2%    |
| F2fs    | 2         | 0.2%    |
| Ext2    | 2         | 0.2%    |
| Zfs     | 1         | 0.1%    |
| SAMSUNG | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 346       | 34.53%  |
| Unknown | 334       | 33.33%  |
| GPT     | 322       | 32.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 836       | 86.19%  |
| Yes       | 134       | 13.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 656       | 66.46%  |
| Yes       | 331       | 33.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 208       | 22.25%  |
| Lenovo              | 122       | 13.05%  |
| Hewlett-Packard     | 115       | 12.3%   |
| Gigabyte Technology | 96        | 10.27%  |
| Acer                | 75        | 8.02%   |
| ASRock              | 72        | 7.7%    |
| MSI                 | 49        | 5.24%   |
| Dell                | 43        | 4.6%    |
| Samsung Electronics | 36        | 3.85%   |
| Intel               | 13        | 1.39%   |
| Biostar             | 12        | 1.28%   |
| Toshiba             | 10        | 1.07%   |
| Timi                | 9         | 0.96%   |
| Sony                | 7         | 0.75%   |
| Prestigio           | 5         | 0.53%   |
| Packard Bell        | 5         | 0.53%   |
| Apple               | 5         | 0.53%   |
| HONOR               | 4         | 0.43%   |
| Fujitsu             | 4         | 0.43%   |
| Unknown             | 4         | 0.43%   |
| Fujitsu Siemens     | 3         | 0.32%   |
| ECS                 | 3         | 0.32%   |
| Nvidia              | 2         | 0.21%   |
| HUAWEI              | 2         | 0.21%   |
| EPoX Computer       | 2         | 0.21%   |
| BenQ                | 2         | 0.21%   |
| ZOTAC               | 1         | 0.11%   |
| ViewSonic           | 1         | 0.11%   |
| VIA Technologies    | 1         | 0.11%   |
| TECNO               | 1         | 0.11%   |
| Supermicro          | 1         | 0.11%   |
| Quanta              | 1         | 0.11%   |
| Pegatron            | 1         | 0.11%   |
| Partner             | 1         | 0.11%   |
| Olimex              | 1         | 0.11%   |
| Notebook            | 1         | 0.11%   |
| Microsoft           | 1         | 0.11%   |
| LTD Delovoy Office  | 1         | 0.11%   |
| LG Electronics      | 1         | 0.11%   |
| Kllisre             | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo G50-30 80G0                      | 7         | 0.75%   |
| HP Notebook                             | 6         | 0.64%   |
| Unknown                                 | 6         | 0.64%   |
| ASRock N68C-GS FX                       | 5         | 0.53%   |
| Acer Extensa 5220                       | 5         | 0.53%   |
| Timi TM1701                             | 4         | 0.43%   |
| Samsung RV413/RV513                     | 4         | 0.43%   |
| MSI MS-7369                             | 4         | 0.43%   |
| Lenovo IdeaPad 320-15IAP 80XR           | 4         | 0.43%   |
| HP ProBook 455 G1                       | 4         | 0.43%   |
| HP Pavilion g6                          | 4         | 0.43%   |
| Gigabyte 970A-DS3P                      | 4         | 0.43%   |
| ASUS X540NV                             | 4         | 0.43%   |
| ASUS All Series                         | 4         | 0.43%   |
| ASRock N68-VS3 UCC                      | 4         | 0.43%   |
| Acer Aspire E1-571G                     | 4         | 0.43%   |
| MSI MS-7309                             | 3         | 0.32%   |
| Lenovo IdeaPad Z570 HuronRiver Platform | 3         | 0.32%   |
| Lenovo IdeaPad 100-15IBY 80MJ           | 3         | 0.32%   |
| Lenovo G570 20079                       | 3         | 0.32%   |
| Lenovo G500 20236                       | 3         | 0.32%   |
| Lenovo B590 20206                       | 3         | 0.32%   |
| Lenovo B50-30 20382                     | 3         | 0.32%   |
| HP ProBook 450 G5                       | 3         | 0.32%   |
| HP Pavilion dv6                         | 3         | 0.32%   |
| HP Pavilion 15                          | 3         | 0.32%   |
| HP Laptop 15s-eq2xxx                    | 3         | 0.32%   |
| HP 635                                  | 3         | 0.32%   |
| Gigabyte M61SME-S2                      | 3         | 0.32%   |
| Gigabyte H81M-S2H                       | 3         | 0.32%   |
| Gigabyte GA-MA74GM-S2H                  | 3         | 0.32%   |
| Gigabyte GA-780T-D3L                    | 3         | 0.32%   |
| Gigabyte B450M S2H                      | 3         | 0.32%   |
| Gigabyte B450M DS3H                     | 3         | 0.32%   |
| Dell Inspiron 7577                      | 3         | 0.32%   |
| ASUS ZenBook UX431DA_UM431DA            | 3         | 0.32%   |
| ASUS X541UAK                            | 3         | 0.32%   |
| ASUS TUF B450-PRO GAMING                | 3         | 0.32%   |
| ASUS P8H77-V                            | 3         | 0.32%   |
| ASRock N68C-GS4 FX                      | 3         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 49        | 5.24%   |
| Lenovo IdeaPad        | 38        | 4.06%   |
| HP ProBook            | 31        | 3.32%   |
| Lenovo ThinkPad       | 28        | 2.99%   |
| Dell Inspiron         | 26        | 2.78%   |
| HP Pavilion           | 25        | 2.67%   |
| ASUS VivoBook         | 23        | 2.46%   |
| Acer Extensa          | 13        | 1.39%   |
| HP Laptop             | 11        | 1.18%   |
| ASUS PRIME            | 9         | 0.96%   |
| Toshiba Satellite     | 8         | 0.86%   |
| ASUS ZenBook          | 8         | 0.86%   |
| Lenovo G50-30         | 7         | 0.75%   |
| Gigabyte B450M        | 7         | 0.75%   |
| ASUS ROG              | 7         | 0.75%   |
| HP Notebook           | 6         | 0.64%   |
| HP EliteBook          | 6         | 0.64%   |
| HP Compaq             | 6         | 0.64%   |
| Unknown               | 6         | 0.64%   |
| Lenovo Legion         | 5         | 0.53%   |
| HP 250                | 5         | 0.53%   |
| Dell Vostro           | 5         | 0.53%   |
| ASUS TUF              | 5         | 0.53%   |
| ASRock N68C-GS        | 5         | 0.53%   |
| ASRock N68-VS3        | 5         | 0.53%   |
| Timi TM1701           | 4         | 0.43%   |
| Samsung RV413         | 4         | 0.43%   |
| MSI MS-7369           | 4         | 0.43%   |
| Lenovo G580           | 4         | 0.43%   |
| Gigabyte Z390         | 4         | 0.43%   |
| Gigabyte 970A-DS3P    | 4         | 0.43%   |
| Dell XPS              | 4         | 0.43%   |
| ASUS X540NV           | 4         | 0.43%   |
| ASUS P8H77-V          | 4         | 0.43%   |
| ASUS ASUS             | 4         | 0.43%   |
| ASUS All              | 4         | 0.43%   |
| Acer TravelMate       | 4         | 0.43%   |
| Packard Bell EasyNote | 3         | 0.32%   |
| MSI MS-7309           | 3         | 0.32%   |
| Lenovo G570           | 3         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 97        | 10.37%  |
| 2012    | 96        | 10.27%  |
| 2013    | 92        | 9.84%   |
| 2018    | 85        | 9.09%   |
| 2017    | 65        | 6.95%   |
| 2010    | 61        | 6.52%   |
| 2020    | 55        | 5.88%   |
| 2019    | 52        | 5.56%   |
| 2014    | 51        | 5.45%   |
| 2009    | 51        | 5.45%   |
| 2007    | 47        | 5.03%   |
| 2015    | 42        | 4.49%   |
| 2008    | 40        | 4.28%   |
| 2021    | 33        | 3.53%   |
| 2016    | 29        | 3.1%    |
| 2006    | 19        | 2.03%   |
| 2022    | 10        | 1.07%   |
| 2005    | 7         | 0.75%   |
| Unknown | 2         | 0.21%   |
| 2003    | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 585       | 62.57%  |
| Desktop        | 325       | 34.76%  |
| All in one     | 8         | 0.86%   |
| Convertible    | 5         | 0.53%   |
| Mini pc        | 4         | 0.43%   |
| Tablet         | 3         | 0.32%   |
| Server         | 3         | 0.32%   |
| Phone          | 1         | 0.11%   |
| System on chip | 1         | 0.11%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 896       | 95.42%  |
| Enabled  | 43        | 4.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 935       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 267       | 27.75%  |
| 4.01-8.0    | 218       | 22.66%  |
| 8.01-16.0   | 144       | 14.97%  |
| 16.01-24.0  | 128       | 13.31%  |
| 1.01-2.0    | 88        | 9.15%   |
| 32.01-64.0  | 43        | 4.47%   |
| 2.01-3.0    | 41        | 4.26%   |
| 0.51-1.0    | 20        | 2.08%   |
| 24.01-32.0  | 6         | 0.62%   |
| 64.01-256.0 | 6         | 0.62%   |
| 0.01-0.5    | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 380       | 35.15%  |
| 0.51-1.0   | 259       | 23.96%  |
| 2.01-3.0   | 189       | 17.48%  |
| 4.01-8.0   | 105       | 9.71%   |
| 3.01-4.0   | 92        | 8.51%   |
| 8.01-16.0  | 26        | 2.41%   |
| 0.01-0.5   | 22        | 2.04%   |
| 16.01-24.0 | 4         | 0.37%   |
| 24.01-32.0 | 2         | 0.19%   |
| 32.01-64.0 | 1         | 0.09%   |
| Unknown    | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 619       | 63.55%  |
| 2      | 245       | 25.15%  |
| 3      | 74        | 7.6%    |
| 4      | 19        | 1.95%   |
| 5      | 10        | 1.03%   |
| 0      | 4         | 0.41%   |
| 9      | 2         | 0.21%   |
| 6      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 546       | 57.72%  |
| Yes       | 400       | 42.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 827       | 88.35%  |
| No        | 109       | 11.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 693       | 73.8%   |
| No        | 246       | 26.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 511       | 53.9%   |
| No        | 437       | 46.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belarus | 935       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Minsk        | 437       | 42.43%  |
| Vitebsk      | 102       | 9.9%    |
| Gomel        | 96        | 9.32%   |
| Mogilev      | 61        | 5.92%   |
| Hrodna       | 57        | 5.53%   |
| Brest        | 56        | 5.44%   |
| Orsha        | 18        | 1.75%   |
| Polatsk      | 16        | 1.55%   |
| Babruysk     | 16        | 1.55%   |
| Borisov      | 10        | 0.97%   |
| Mazyr        | 8         | 0.78%   |
| Lida         | 8         | 0.78%   |
| Baranovichi  | 8         | 0.78%   |
| Zhlobin      | 7         | 0.68%   |
| Slutsk       | 7         | 0.68%   |
| Zhodzina     | 6         | 0.58%   |
| Bogushevichi | 6         | 0.58%   |
| Vawkavysk    | 5         | 0.49%   |
| Klyetsk      | 5         | 0.49%   |
| Pinsk        | 4         | 0.39%   |
| Navapolatsk  | 4         | 0.39%   |
| Chashniki    | 4         | 0.39%   |
| Syanno       | 3         | 0.29%   |
| Smalyavichy  | 3         | 0.29%   |
| Slonim       | 3         | 0.29%   |
| Salihorsk    | 3         | 0.29%   |
| Rahachow     | 3         | 0.29%   |
| Fedorovka    | 3         | 0.29%   |
| Dubovka      | 3         | 0.29%   |
| Baran'       | 3         | 0.29%   |
| Aleksandrovo | 3         | 0.29%   |
| Svyetlahorsk | 2         | 0.19%   |
| Snitovo      | 2         | 0.19%   |
| Rechytsa     | 2         | 0.19%   |
| Pruzhany     | 2         | 0.19%   |
| Ogorodniki   | 2         | 0.19%   |
| Murava       | 2         | 0.19%   |
| Masty        | 2         | 0.19%   |
| Maladzyechna | 2         | 0.19%   |
| Lyepyel'     | 2         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 222       | 353    | 16.78%  |
| Seagate             | 220       | 340    | 16.63%  |
| Samsung Electronics | 180       | 257    | 13.61%  |
| Toshiba             | 134       | 208    | 10.13%  |
| Kingston            | 87        | 116    | 6.58%   |
| Hitachi             | 85        | 111    | 6.42%   |
| HGST                | 48        | 75     | 3.63%   |
| SK hynix            | 34        | 41     | 2.57%   |
| Intel               | 33        | 50     | 2.49%   |
| Crucial             | 27        | 35     | 2.04%   |
| Unknown             | 23        | 31     | 1.74%   |
| SanDisk             | 21        | 28     | 1.59%   |
| Patriot             | 17        | 22     | 1.28%   |
| Gigabyte Technology | 13        | 15     | 0.98%   |
| A-DATA Technology   | 13        | 14     | 0.98%   |
| Fujitsu             | 12        | 19     | 0.91%   |
| OCZ                 | 11        | 12     | 0.83%   |
| GOODRAM             | 10        | 10     | 0.76%   |
| Micron Technology   | 9         | 15     | 0.68%   |
| KingSpec            | 9         | 17     | 0.68%   |
| China               | 9         | 11     | 0.68%   |
| SPCC                | 8         | 13     | 0.6%    |
| Transcend           | 5         | 7      | 0.38%   |
| Silicon Motion      | 5         | 6      | 0.38%   |
| Plextor             | 5         | 6      | 0.38%   |
| Apacer              | 5         | 6      | 0.38%   |
| Netac               | 4         | 5      | 0.3%    |
| Maxtor              | 4         | 4      | 0.3%    |
| KIOXIA              | 4         | 19     | 0.3%    |
| JMicron Technology  | 4         | 4      | 0.3%    |
| XrayDisk            | 3         | 3      | 0.23%   |
| XPG                 | 3         | 3      | 0.23%   |
| Smartbuy            | 3         | 3      | 0.23%   |
| KingDian            | 3         | 5      | 0.23%   |
| Apple               | 3         | 3      | 0.23%   |
| TO Exter            | 2         | 3      | 0.15%   |
| Team                | 2         | 2      | 0.15%   |
| Phison Electronics  | 2         | 2      | 0.15%   |
| LITEONIT            | 2         | 2      | 0.15%   |
| Lexar               | 2         | 2      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB           | 24        | 1.68%   |
| Toshiba DT01ACA050 500GB           | 21        | 1.47%   |
| Seagate ST1000LM035-1RK172 970GB   | 20        | 1.4%    |
| Kingston SA400S37120G 120GB SSD    | 19        | 1.33%   |
| Seagate ST500LT012-1DG142 500GB    | 17        | 1.19%   |
| Samsung SSD 860 EVO 250GB          | 17        | 1.19%   |
| Toshiba DT01ACA100 1TB             | 15        | 1.05%   |
| Samsung SSD 860 EVO 500GB          | 15        | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 14        | 0.98%   |
| Toshiba DT01ACA200 2TB             | 12        | 0.84%   |
| HGST HTS545050A7E680 500GB         | 12        | 0.84%   |
| Kingston SA400S37240G 240GB SSD    | 11        | 0.77%   |
| Seagate ST9320325AS 320GB          | 10        | 0.7%    |
| Crucial CT120BX500SSD1 120GB       | 10        | 0.7%    |
| Seagate ST500DM002-1BD142 500GB    | 9         | 0.63%   |
| Samsung NVMe SSD Drive 256GB       | 9         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB           | 8         | 0.56%   |
| Toshiba MQ04ABF100 1TB             | 8         | 0.56%   |
| Toshiba MQ01ABD100 1TB             | 8         | 0.56%   |
| SK hynix NVMe SSD Drive 512GB      | 8         | 0.56%   |
| Samsung SSD 850 EVO 250GB          | 8         | 0.56%   |
| Hitachi HTS543232A7A384 320GB      | 8         | 0.56%   |
| Toshiba MQ01ABD032 320GB           | 7         | 0.49%   |
| Seagate ST9500325AS 500GB          | 7         | 0.49%   |
| Kingston SUV400S37120G 120GB SSD   | 7         | 0.49%   |
| Toshiba MQ01ABD075 752GB           | 6         | 0.42%   |
| Seagate ST9250315AS 250GB          | 6         | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB     | 6         | 0.42%   |
| Patriot Burst 120GB SSD            | 6         | 0.42%   |
| OCZ VERTEX4 128GB SSD              | 6         | 0.42%   |
| Hitachi HTS547550A9E384 500GB      | 6         | 0.42%   |
| Hitachi HTS545050B9A300 500GB      | 6         | 0.42%   |
| Hitachi HDS721010CLA330 1TB        | 6         | 0.42%   |
| HGST HTS541010B7E610 1TB           | 6         | 0.42%   |
| HGST HTS541010A9E680 1TB           | 6         | 0.42%   |
| WDC WD10EZRZ-00HTKB0 1TB           | 5         | 0.35%   |
| Toshiba HDWD110 1TB                | 5         | 0.35%   |
| Toshiba DT01ACA300 3TB             | 5         | 0.35%   |
| Seagate ST500LT012-9WS142 500GB    | 5         | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB     | 5         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 219       | 338    | 28.89%  |
| WDC                 | 203       | 307    | 26.78%  |
| Toshiba             | 127       | 197    | 16.75%  |
| Hitachi             | 85        | 111    | 11.21%  |
| Samsung Electronics | 49        | 76     | 6.46%   |
| HGST                | 48        | 75     | 6.33%   |
| Fujitsu             | 12        | 19     | 1.58%   |
| Maxtor              | 4         | 4      | 0.53%   |
| JMicron Technology  | 4         | 4      | 0.53%   |
| WD MediaMax         | 1         | 1      | 0.13%   |
| USB3.0              | 1         | 1      | 0.13%   |
| Unknown             | 1         | 1      | 0.13%   |
| SINTECHI            | 1         | 1      | 0.13%   |
| SAGE                | 1         | 1      | 0.13%   |
| External            | 1         | 1      | 0.13%   |
| Apple               | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 75        | 106    | 21.13%  |
| Kingston            | 64        | 88     | 18.03%  |
| Crucial             | 26        | 34     | 7.32%   |
| Patriot             | 15        | 20     | 4.23%   |
| WDC                 | 13        | 32     | 3.66%   |
| SanDisk             | 13        | 20     | 3.66%   |
| OCZ                 | 11        | 12     | 3.1%    |
| Intel               | 11        | 12     | 3.1%    |
| Gigabyte Technology | 10        | 12     | 2.82%   |
| KingSpec            | 9         | 17     | 2.54%   |
| GOODRAM             | 9         | 9      | 2.54%   |
| China               | 9         | 11     | 2.54%   |
| A-DATA Technology   | 9         | 10     | 2.54%   |
| SPCC                | 8         | 13     | 2.25%   |
| SK hynix            | 7         | 9      | 1.97%   |
| Transcend           | 5         | 7      | 1.41%   |
| Plextor             | 5         | 6      | 1.41%   |
| Apacer              | 5         | 6      | 1.41%   |
| Netac               | 4         | 5      | 1.13%   |
| XrayDisk            | 3         | 3      | 0.85%   |
| Unknown             | 3         | 3      | 0.85%   |
| Toshiba             | 3         | 3      | 0.85%   |
| Smartbuy            | 3         | 3      | 0.85%   |
| KingDian            | 3         | 5      | 0.85%   |
| TO Exter            | 2         | 3      | 0.56%   |
| Team                | 2         | 2      | 0.56%   |
| Seagate             | 2         | 2      | 0.56%   |
| Micron Technology   | 2         | 2      | 0.56%   |
| LITEONIT            | 2         | 2      | 0.56%   |
| Lexar               | 2         | 2      | 0.56%   |
| Corsair             | 2         | 6      | 0.56%   |
| Zheino              | 1         | 2      | 0.28%   |
| Union Memory        | 1         | 1      | 0.28%   |
| PNY                 | 1         | 5      | 0.28%   |
| OSCOO               | 1         | 1      | 0.28%   |
| OCZ-VERTEX3         | 1         | 2      | 0.28%   |
| OCZ-VERTEX          | 1         | 1      | 0.28%   |
| MSS4FV-MP           | 1         | 1      | 0.28%   |
| M500                | 1         | 1      | 0.28%   |
| LT                  | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 659       | 1138   | 54.87%  |
| SSD     | 326       | 492    | 27.14%  |
| NVMe    | 191       | 268    | 15.9%   |
| MMC     | 21        | 30     | 1.75%   |
| Unknown | 4         | 4      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 789       | 1612   | 77.35%  |
| NVMe | 191       | 267    | 18.73%  |
| MMC  | 21        | 30     | 2.06%   |
| SAS  | 19        | 23     | 1.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 649       | 1104   | 66.63%  |
| 0.51-1.0   | 252       | 383    | 25.87%  |
| 1.01-2.0   | 42        | 88     | 4.31%   |
| 2.01-3.0   | 11        | 18     | 1.13%   |
| 3.01-4.0   | 10        | 12     | 1.03%   |
| 4.01-10.0  | 7         | 21     | 0.72%   |
| 10.01-20.0 | 3         | 4      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 258       | 24.74%  |
| 251-500        | 254       | 24.35%  |
| 501-1000       | 136       | 13.04%  |
| 1-20           | 106       | 10.16%  |
| 51-100         | 95        | 9.11%   |
| 1001-2000      | 71        | 6.81%   |
| 21-50          | 69        | 6.62%   |
| More than 3000 | 23        | 2.21%   |
| Unknown        | 20        | 1.92%   |
| 2001-3000      | 11        | 1.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 470       | 44.26%  |
| 21-50          | 159       | 14.97%  |
| 101-250        | 118       | 11.11%  |
| 51-100         | 118       | 11.11%  |
| 251-500        | 80        | 7.53%   |
| 501-1000       | 56        | 5.27%   |
| 1001-2000      | 21        | 1.98%   |
| Unknown        | 20        | 1.88%   |
| 2001-3000      | 10        | 0.94%   |
| More than 3000 | 9         | 0.85%   |
| 0              | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 7         | 9      | 2.64%   |
| HGST HTS545050A7E680 500GB         | 7         | 8      | 2.64%   |
| Seagate ST9320325AS 320GB          | 6         | 7      | 2.26%   |
| Seagate ST9500325AS 500GB          | 5         | 6      | 1.89%   |
| Toshiba MQ01ABF050 500GB           | 4         | 5      | 1.51%   |
| Toshiba DT01ACA100 1TB             | 4         | 5      | 1.51%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 1.51%   |
| Seagate ST500LT012-9WS142 500GB    | 4         | 4      | 1.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 5      | 1.51%   |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 1.51%   |
| Hitachi HDP725050GLA360 500GB      | 4         | 8      | 1.51%   |
| WDC WD20EARS-00MVWB0 2TB           | 3         | 6      | 1.13%   |
| Toshiba MQ01ABD032 320GB           | 3         | 3      | 1.13%   |
| Toshiba DT01ACA200 2TB             | 3         | 5      | 1.13%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 1.13%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 10     | 1.13%   |
| Samsung Electronics HD160JJ/ 160GB | 3         | 3      | 1.13%   |
| Hitachi HDS721010CLA330 1TB        | 3         | 4      | 1.13%   |
| WDC WD5000AAKS-00A7B0 500GB        | 2         | 2      | 0.75%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 2         | 6      | 0.75%   |
| WDC WD30EFRX-68EUZN0 3TB           | 2         | 3      | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 2      | 0.75%   |
| Toshiba MK3259GSXP 320GB           | 2         | 3      | 0.75%   |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.75%   |
| Seagate ST9120822AS 120GB          | 2         | 3      | 0.75%   |
| Seagate ST3500320AS 500GB          | 2         | 3      | 0.75%   |
| Seagate ST340016A 40GB             | 2         | 3      | 0.75%   |
| Seagate ST3250820AS 250GB          | 2         | 2      | 0.75%   |
| Seagate ST3160812A 160GB           | 2         | 4      | 0.75%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 2      | 0.75%   |
| Samsung Electronics SP0802N 80GB   | 2         | 2      | 0.75%   |
| Samsung Electronics HD161HJ 160GB  | 2         | 3      | 0.75%   |
| Samsung Electronics HD103SJ 1TB    | 2         | 2      | 0.75%   |
| OCZ VERTEX4 128GB SSD              | 2         | 2      | 0.75%   |
| Hitachi HTS722010K9SA00 100GB      | 2         | 2      | 0.75%   |
| Hitachi HTS547575A9E384 752GB      | 2         | 2      | 0.75%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 0.75%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 2      | 0.75%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 3      | 0.75%   |
| Hitachi HDS721010DLE630 1TB        | 2         | 2      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 87     | 25.29%  |
| WDC                 | 59        | 76     | 22.96%  |
| Hitachi             | 43        | 56     | 16.73%  |
| Toshiba             | 24        | 32     | 9.34%   |
| Samsung Electronics | 22        | 32     | 8.56%   |
| HGST                | 11        | 12     | 4.28%   |
| Fujitsu             | 6         | 8      | 2.33%   |
| Kingston            | 5         | 5      | 1.95%   |
| OCZ                 | 4         | 4      | 1.56%   |
| Crucial             | 3         | 3      | 1.17%   |
| SK hynix            | 2         | 2      | 0.78%   |
| Maxtor              | 2         | 2      | 0.78%   |
| WD MediaMax         | 1         | 1      | 0.39%   |
| SanDisk             | 1         | 1      | 0.39%   |
| PNY                 | 1         | 4      | 0.39%   |
| OCZ-VERTEX3         | 1         | 2      | 0.39%   |
| Micron Technology   | 1         | 1      | 0.39%   |
| LITEONIT            | 1         | 1      | 0.39%   |
| KingSpec            | 1         | 6      | 0.39%   |
| Intel               | 1         | 1      | 0.39%   |
| Corsair             | 1         | 3      | 0.39%   |
| Apacer              | 1         | 1      | 0.39%   |
| A-DATA Technology   | 1         | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 87     | 28.14%  |
| WDC                 | 59        | 76     | 25.54%  |
| Hitachi             | 43        | 56     | 18.61%  |
| Toshiba             | 24        | 32     | 10.39%  |
| Samsung Electronics | 20        | 30     | 8.66%   |
| HGST                | 11        | 12     | 4.76%   |
| Fujitsu             | 6         | 8      | 2.6%    |
| Maxtor              | 2         | 2      | 0.87%   |
| WD MediaMax         | 1         | 1      | 0.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 212       | 304    | 89.08%  |
| SSD  | 23        | 34     | 9.66%   |
| NVMe | 3         | 3      | 1.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-80HXZT3 500GB        | 1         | 1      | 10%     |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 10%     |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 10%     |
| Samsung Electronics SP0802N 80GB    | 1         | 1      | 10%     |
| Samsung Electronics HM500JI 500GB   | 1         | 1      | 10%     |
| Samsung Electronics HD252HJ 250GB   | 1         | 1      | 10%     |
| Maxtor STM380211AS 80GB             | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 10%     |
| HGST HTS545050B7E660 500GB          | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| Seagate             | 2         | 2      | 20%     |
| Maxtor              | 1         | 1      | 10%     |
| Hitachi             | 1         | 1      | 10%     |
| HGST                | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 555       | 1087   | 51.34%  |
| Detected | 281       | 494    | 25.99%  |
| Malfunc  | 235       | 341    | 21.74%  |
| Failed   | 10        | 10     | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 624       | 56.37%  |
| AMD                              | 203       | 18.34%  |
| Samsung Electronics              | 65        | 5.87%   |
| Nvidia                           | 51        | 4.61%   |
| SK hynix                         | 26        | 2.35%   |
| Kingston Technology Company      | 24        | 2.17%   |
| JMicron Technology               | 20        | 1.81%   |
| SanDisk                          | 19        | 1.72%   |
| Marvell Technology Group         | 11        | 0.99%   |
| Silicon Motion                   | 9         | 0.81%   |
| Phison Electronics               | 8         | 0.72%   |
| Micron Technology                | 8         | 0.72%   |
| ASMedia Technology               | 8         | 0.72%   |
| Toshiba America Info Systems     | 6         | 0.54%   |
| VIA Technologies                 | 4         | 0.36%   |
| Silicon Integrated Systems [SiS] | 4         | 0.36%   |
| KIOXIA                           | 4         | 0.36%   |
| Realtek Semiconductor            | 3         | 0.27%   |
| ADATA Technology                 | 3         | 0.27%   |
| Lenovo                           | 2         | 0.18%   |
| Synopsys                         | 1         | 0.09%   |
| Silicon Image                    | 1         | 0.09%   |
| Integrated Technology Express    | 1         | 0.09%   |
| Broadcom / LSI                   | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 101       | 7.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 62        | 4.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 46        | 3.42%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 45        | 3.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 44        | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 34        | 2.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 34        | 2.53%   |
| Nvidia MCP61 SATA Controller                                                            | 33        | 2.45%   |
| Nvidia MCP61 IDE                                                                        | 33        | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 33        | 2.45%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 32        | 2.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 30        | 2.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 25        | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 24        | 1.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 22        | 1.63%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 21        | 1.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 21        | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 19        | 1.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19        | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 18        | 1.34%   |
| Samsung NVMe SSD Controller 980                                                         | 17        | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15        | 1.11%   |
| Intel SSD 660P Series                                                                   | 14        | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 14        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 14        | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 13        | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 13        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 12        | 0.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 12        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 0.89%   |
| AMD FCH IDE Controller                                                                  | 12        | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 11        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 11        | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 10        | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10        | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 9         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 702       | 60.31%  |
| IDE  | 229       | 19.67%  |
| NVMe | 192       | 16.49%  |
| RAID | 40        | 3.44%   |
| SCSI | 1         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 665       | 71.12%  |
| AMD    | 268       | 28.66%  |
| ARM    | 2         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 15        | 1.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.38%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.06%   |
| AMD E-450 APU with Radeon HD Graphics         | 10        | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.74%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 7         | 0.74%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.64%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 6         | 0.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.64%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 0.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 6         | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.64%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+    | 6         | 0.64%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.53%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 5         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.53%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.53%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.53%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 5         | 0.53%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.53%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.53%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 0.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.53%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.53%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 5         | 0.53%   |
| AMD Athlon II X2 240 Processor                | 5         | 0.53%   |
| AMD A4-4300M APU with Radeon HD Graphics      | 5         | 0.53%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 4         | 0.43%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 4         | 0.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.43%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 4         | 0.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 152       | 16.19%  |
| Intel Core i7           | 100       | 10.65%  |
| Intel Celeron           | 81        | 8.63%   |
| Intel Core i3           | 79        | 8.41%   |
| Intel Pentium           | 58        | 6.18%   |
| AMD Ryzen 5             | 45        | 4.79%   |
| Intel Core 2 Duo        | 43        | 4.58%   |
| Other                   | 38        | 4.05%   |
| Intel Atom              | 37        | 3.94%   |
| AMD Athlon 64 X2        | 24        | 2.56%   |
| AMD FX                  | 21        | 2.24%   |
| AMD Athlon II X2        | 21        | 2.24%   |
| Intel Pentium Dual-Core | 16        | 1.7%    |
| AMD Ryzen 7             | 16        | 1.7%    |
| Intel Xeon              | 14        | 1.49%   |
| AMD Ryzen 3             | 13        | 1.38%   |
| AMD E                   | 13        | 1.38%   |
| AMD A4                  | 12        | 1.28%   |
| AMD A6                  | 11        | 1.17%   |
| AMD Athlon II X3        | 10        | 1.06%   |
| Intel Pentium Dual      | 8         | 0.85%   |
| AMD E1                  | 8         | 0.85%   |
| AMD A10                 | 8         | 0.85%   |
| AMD A8                  | 7         | 0.75%   |
| Intel Pentium Silver    | 6         | 0.64%   |
| Intel Genuine           | 6         | 0.64%   |
| Intel Core i9           | 6         | 0.64%   |
| AMD Phenom II X4        | 6         | 0.64%   |
| AMD Athlon              | 6         | 0.64%   |
| Intel Pentium 4         | 5         | 0.53%   |
| Intel Celeron Dual-Core | 5         | 0.53%   |
| AMD Athlon X4           | 5         | 0.53%   |
| AMD Turion II           | 4         | 0.43%   |
| AMD E2                  | 4         | 0.43%   |
| AMD Athlon II X4        | 4         | 0.43%   |
| AMD Athlon II           | 4         | 0.43%   |
| Intel Core 2 Solo       | 3         | 0.32%   |
| Intel Core 2            | 3         | 0.32%   |
| AMD Ryzen 9             | 3         | 0.32%   |
| AMD Phenom II           | 3         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 475       | 50%     |
| 4       | 263       | 27.68%  |
| 6       | 64        | 6.74%   |
| 1       | 54        | 5.68%   |
| Unknown | 35        | 3.68%   |
| 8       | 33        | 3.47%   |
| 3       | 17        | 1.79%   |
| 12      | 4         | 0.42%   |
| 10      | 4         | 0.42%   |
| 14      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 933       | 99.79%  |
| 2      | 2         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 476       | 50%     |
| 1       | 441       | 46.32%  |
| Unknown | 35        | 3.68%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 899       | 95.94%  |
| Unknown        | 21        | 2.24%   |
| 32-bit         | 17        | 1.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 14.3%   |
| 0x206a7    | 73        | 7.56%   |
| 0x306a9    | 62        | 6.42%   |
| 0x1067a    | 46        | 4.77%   |
| 0x306c3    | 37        | 3.83%   |
| 0x010000c8 | 36        | 3.73%   |
| 0x806ea    | 25        | 2.59%   |
| 0x806c1    | 23        | 2.38%   |
| 0x30678    | 22        | 2.28%   |
| 0x906ea    | 21        | 2.18%   |
| 0x06001119 | 18        | 1.87%   |
| 0x806ec    | 17        | 1.76%   |
| 0x40651    | 17        | 1.76%   |
| 0x106ca    | 17        | 1.76%   |
| 0x6fd      | 16        | 1.66%   |
| 0x406e3    | 15        | 1.55%   |
| 0x05000119 | 14        | 1.45%   |
| 0x010000c7 | 13        | 1.35%   |
| 0x906e9    | 12        | 1.24%   |
| 0x506e3    | 12        | 1.24%   |
| 0x506c9    | 12        | 1.24%   |
| 0x306d4    | 12        | 1.24%   |
| 0x806e9    | 11        | 1.14%   |
| 0x10676    | 10        | 1.04%   |
| 0x06000852 | 10        | 1.04%   |
| 0x10661    | 9         | 0.93%   |
| 0x08108102 | 9         | 0.93%   |
| 0x706a1    | 8         | 0.83%   |
| 0x20652    | 8         | 0.83%   |
| 0x106c2    | 8         | 0.83%   |
| 0x03000027 | 8         | 0.83%   |
| 0x706e5    | 7         | 0.73%   |
| 0x6fb      | 7         | 0.73%   |
| 0x406c4    | 7         | 0.73%   |
| 0x406c3    | 7         | 0.73%   |
| 0x20655    | 7         | 0.73%   |
| 0x08608103 | 7         | 0.73%   |
| 0x08101016 | 7         | 0.73%   |
| 0x0800820d | 7         | 0.73%   |
| 0x906ed    | 6         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 121       | 12.87%  |
| SandyBridge      | 79        | 8.4%    |
| IvyBridge        | 71        | 7.55%   |
| K10              | 62        | 6.6%    |
| Haswell          | 62        | 6.6%    |
| Penryn           | 61        | 6.49%   |
| Core             | 43        | 4.57%   |
| Silvermont       | 40        | 4.26%   |
| Piledriver       | 37        | 3.94%   |
| Skylake          | 33        | 3.51%   |
| K8 Hammer        | 31        | 3.3%    |
| Bonnell          | 30        | 3.19%   |
| TigerLake        | 24        | 2.55%   |
| Zen+             | 23        | 2.45%   |
| Zen 2            | 20        | 2.13%   |
| Zen              | 20        | 2.13%   |
| Unknown          | 18        | 1.91%   |
| Bobcat           | 17        | 1.81%   |
| Westmere         | 16        | 1.7%    |
| IceLake          | 14        | 1.49%   |
| Goldmont         | 14        | 1.49%   |
| Goldmont plus    | 13        | 1.38%   |
| Broadwell        | 13        | 1.38%   |
| Zen 3            | 12        | 1.28%   |
| K10 Llano        | 9         | 0.96%   |
| Excavator        | 8         | 0.85%   |
| NetBurst         | 7         | 0.74%   |
| Puma             | 6         | 0.64%   |
| Nehalem          | 6         | 0.64%   |
| Jaguar           | 6         | 0.64%   |
| P6               | 5         | 0.53%   |
| CometLake        | 5         | 0.53%   |
| Bulldozer        | 4         | 0.43%   |
| Alderlake Hybrid | 4         | 0.43%   |
| Steamroller      | 3         | 0.32%   |
| Tremont          | 2         | 0.21%   |
| K8 & K10 hybrid  | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 512       | 44.48%  |
| Nvidia                           | 379       | 32.93%  |
| AMD                              | 253       | 21.98%  |
| Silicon Integrated Systems [SiS] | 3         | 0.26%   |
| ASPEED Technology                | 2         | 0.17%   |
| Matrox Electronics Systems       | 1         | 0.09%   |
| ATI Technologies                 | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 61        | 5.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 48        | 3.96%   |
| Intel UHD Graphics 620                                                                   | 27        | 2.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 2.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 21        | 1.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 1.24%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 15        | 1.24%   |
| AMD Renoir                                                                               | 15        | 1.24%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 15        | 1.24%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 13        | 1.07%   |
| Intel HD Graphics 620                                                                    | 12        | 0.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 0.99%   |
| Intel HD Graphics 5500                                                                   | 11        | 0.91%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 0.83%   |
| Intel HD Graphics 630                                                                    | 10        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10        | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.83%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 0.83%   |
| Intel HD Graphics 500                                                                    | 9         | 0.74%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 9         | 0.74%   |
| AMD Lucienne                                                                             | 9         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.66%   |
| Nvidia GM108M [GeForce MX110]                                                            | 8         | 0.66%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 8         | 0.66%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 8         | 0.66%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 8         | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.66%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 8         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 308       | 32.84%  |
| 1 x Nvidia      | 213       | 22.71%  |
| 1 x AMD         | 172       | 18.34%  |
| Intel + Nvidia  | 153       | 16.31%  |
| Intel + AMD     | 43        | 4.58%   |
| 2 x AMD         | 29        | 3.09%   |
| AMD + Nvidia    | 10        | 1.07%   |
| 1 x SiS         | 3         | 0.32%   |
| Other           | 2         | 0.21%   |
| 2 x Nvidia      | 1         | 0.11%   |
| 2 x Intel       | 1         | 0.11%   |
| Nvidia + ASPEED | 1         | 0.11%   |
| 1 x Matrox      | 1         | 0.11%   |
| 1 x ASPEED      | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 758       | 78.79%  |
| Proprietary | 162       | 16.84%  |
| Unknown     | 42        | 4.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 337       | 34.6%   |
| 1.01-2.0   | 231       | 23.72%  |
| 0.01-0.5   | 214       | 21.97%  |
| 0.51-1.0   | 97        | 9.96%   |
| 3.01-4.0   | 57        | 5.85%   |
| 7.01-8.0   | 14        | 1.44%   |
| 5.01-6.0   | 14        | 1.44%   |
| 2.01-3.0   | 5         | 0.51%   |
| 8.01-16.0  | 4         | 0.41%   |
| 4.01-5.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 162       | 16.82%  |
| AU Optronics            | 127       | 13.19%  |
| Goldstar                | 92        | 9.55%   |
| LG Display              | 83        | 8.62%   |
| BOE                     | 83        | 8.62%   |
| Chimei Innolux          | 79        | 8.2%    |
| Chi Mei Optoelectronics | 47        | 4.88%   |
| Dell                    | 38        | 3.95%   |
| Philips                 | 37        | 3.84%   |
| BenQ                    | 28        | 2.91%   |
| AOC                     | 22        | 2.28%   |
| ViewSonic               | 15        | 1.56%   |
| PANDA                   | 15        | 1.56%   |
| Lenovo                  | 12        | 1.25%   |
| Hewlett-Packard         | 12        | 1.25%   |
| LG Philips              | 10        | 1.04%   |
| HannStar                | 9         | 0.93%   |
| CPT                     | 9         | 0.93%   |
| Acer                    | 9         | 0.93%   |
| NEC Computers           | 7         | 0.73%   |
| Ancor Communications    | 7         | 0.73%   |
| Unknown                 | 6         | 0.62%   |
| Sony                    | 6         | 0.62%   |
| Sharp                   | 6         | 0.62%   |
| Iiyama                  | 6         | 0.62%   |
| Apple                   | 6         | 0.62%   |
| LG Electronics          | 4         | 0.42%   |
| XYK                     | 3         | 0.31%   |
| ASUSTek Computer        | 3         | 0.31%   |
| Plain Tree Systems      | 2         | 0.21%   |
| LGD                     | 2         | 0.21%   |
| Toshiba                 | 1         | 0.1%    |
| SKK                     | 1         | 0.1%    |
| Seiko/Epson             | 1         | 0.1%    |
| Quanta Display          | 1         | 0.1%    |
| PCL                     | 1         | 0.1%    |
| Packard Bell            | 1         | 0.1%    |
| MStar                   | 1         | 0.1%    |
| MiTAC                   | 1         | 0.1%    |
| Mi                      | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 1.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 11        | 1.13%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 1.02%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.61%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.61%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.61%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                     | 6         | 0.61%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 6         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.61%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 5         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.51%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 4         | 0.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.41%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 4         | 0.41%   |
| Goldstar L1919S GSM4AF2 1280x1024 376x301mm 19.0-inch                    | 4         | 0.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.41%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 4         | 0.41%   |
| XYK DVI XYK2360 1920x1080 477x268mm 21.5-inch                            | 3         | 0.31%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 3         | 0.31%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 368       | 39.02%  |
| 1366x768 (WXGA)    | 252       | 26.72%  |
| 1280x1024 (SXGA)   | 61        | 6.47%   |
| 1600x900 (HD+)     | 47        | 4.98%   |
| 1440x900 (WXGA+)   | 32        | 3.39%   |
| 3840x2160 (4K)     | 30        | 3.18%   |
| 1280x800 (WXGA)    | 28        | 2.97%   |
| 1680x1050 (WSXGA+) | 27        | 2.86%   |
| 2560x1440 (QHD)    | 24        | 2.55%   |
| 1024x600           | 20        | 2.12%   |
| 2560x1080          | 10        | 1.06%   |
| 1920x1200 (WUXGA)  | 7         | 0.74%   |
| 1024x768 (XGA)     | 5         | 0.53%   |
| 2560x1600          | 4         | 0.42%   |
| 1360x768           | 4         | 0.42%   |
| 3440x1440          | 3         | 0.32%   |
| 2288x1287          | 3         | 0.32%   |
| 3840x2400          | 2         | 0.21%   |
| 1600x1200          | 2         | 0.21%   |
| 1152x864           | 2         | 0.21%   |
| Unknown            | 2         | 0.21%   |
| 4480x1200          | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3072x1920          | 1         | 0.11%   |
| 2880x1800          | 1         | 0.11%   |
| 2736x1824          | 1         | 0.11%   |
| 2160x1440          | 1         | 0.11%   |
| 2048x1536          | 1         | 0.11%   |
| 1920x540           | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1400x1050          | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 372       | 38.55%  |
| 17      | 82        | 8.5%    |
| 23      | 67        | 6.94%   |
| 21      | 67        | 6.94%   |
| 19      | 52        | 5.39%   |
| 13      | 48        | 4.97%   |
| 24      | 42        | 4.35%   |
| 14      | 41        | 4.25%   |
| 27      | 33        | 3.42%   |
| Unknown | 25        | 2.59%   |
| 18      | 20        | 2.07%   |
| 10      | 20        | 2.07%   |
| 22      | 17        | 1.76%   |
| 20      | 13        | 1.35%   |
| 34      | 12        | 1.24%   |
| 31      | 9         | 0.93%   |
| 16      | 8         | 0.83%   |
| 40      | 6         | 0.62%   |
| 11      | 6         | 0.62%   |
| 72      | 4         | 0.41%   |
| 54      | 4         | 0.41%   |
| 12      | 4         | 0.41%   |
| 142     | 3         | 0.31%   |
| 84      | 2         | 0.21%   |
| 52      | 2         | 0.21%   |
| 46      | 2         | 0.21%   |
| 55      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |
| 8       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 459       | 48.21%  |
| 401-500        | 133       | 13.97%  |
| 501-600        | 130       | 13.66%  |
| 351-400        | 97        | 10.19%  |
| 201-300        | 57        | 5.99%   |
| Unknown        | 25        | 2.63%   |
| 701-800        | 12        | 1.26%   |
| 601-700        | 12        | 1.26%   |
| 1001-1500      | 9         | 0.95%   |
| 801-900        | 6         | 0.63%   |
| 1501-2000      | 6         | 0.63%   |
| More than 2000 | 3         | 0.32%   |
| 101-200        | 2         | 0.21%   |
| 901-1000       | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 694       | 76.26%  |
| 16/10   | 101       | 11.1%   |
| 5/4     | 58        | 6.37%   |
| Unknown | 23        | 2.53%   |
| 4/3     | 13        | 1.43%   |
| 21/9    | 12        | 1.32%   |
| 3/2     | 5         | 0.55%   |
| 1.00    | 4         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 374       | 38.92%  |
| 201-250        | 162       | 16.86%  |
| 151-200        | 81        | 8.43%   |
| 81-90          | 65        | 6.76%   |
| 141-150        | 43        | 4.47%   |
| 121-130        | 41        | 4.27%   |
| 301-350        | 33        | 3.43%   |
| Unknown        | 25        | 2.6%    |
| 71-80          | 22        | 2.29%   |
| 351-500        | 21        | 2.19%   |
| 41-50          | 21        | 2.19%   |
| More than 1000 | 16        | 1.66%   |
| 131-140        | 15        | 1.56%   |
| 251-300        | 14        | 1.46%   |
| 501-1000       | 9         | 0.94%   |
| 51-60          | 6         | 0.62%   |
| 111-120        | 6         | 0.62%   |
| 61-70          | 4         | 0.42%   |
| 91-100         | 2         | 0.21%   |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 331       | 35.25%  |
| 101-120       | 324       | 34.5%   |
| 121-160       | 202       | 21.51%  |
| Unknown       | 25        | 2.66%   |
| 161-240       | 23        | 2.45%   |
| 1-50          | 21        | 2.24%   |
| More than 240 | 13        | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 823       | 87.09%  |
| 2     | 88        | 9.31%   |
| 0     | 31        | 3.28%   |
| 3     | 3         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 573       | 40.7%   |
| Qualcomm Atheros                       | 256       | 18.18%  |
| Intel                                  | 241       | 17.12%  |
| Broadcom                               | 108       | 7.67%   |
| Nvidia                                 | 38        | 2.7%    |
| Marvell Technology Group               | 32        | 2.27%   |
| Ralink Technology                      | 21        | 1.49%   |
| Ralink                                 | 21        | 1.49%   |
| TP-Link                                | 20        | 1.42%   |
| Broadcom Limited                       | 16        | 1.14%   |
| Huawei Technologies                    | 8         | 0.57%   |
| D-Link                                 | 8         | 0.57%   |
| MediaTek                               | 7         | 0.5%    |
| VIA Technologies                       | 5         | 0.36%   |
| Xiaomi                                 | 4         | 0.28%   |
| Qualcomm Atheros Communications        | 4         | 0.28%   |
| JMicron Technology                     | 4         | 0.28%   |
| D-Link System                          | 4         | 0.28%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.21%   |
| Sierra Wireless                        | 3         | 0.21%   |
| Attansic Technology                    | 3         | 0.21%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.14%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.14%   |
| Qualcomm                               | 2         | 0.14%   |
| IMC Networks                           | 2         | 0.14%   |
| Hewlett-Packard                        | 2         | 0.14%   |
| Fibocom                                | 2         | 0.14%   |
| Aquantia                               | 2         | 0.14%   |
| Texas Instruments                      | 1         | 0.07%   |
| STMicroelectronics                     | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Samsung Electronics                    | 1         | 0.07%   |
| Philips (or NXP)                       | 1         | 0.07%   |
| Motorola PCS                           | 1         | 0.07%   |
| Microsoft                              | 1         | 0.07%   |
| Mercucys                               | 1         | 0.07%   |
| Lenovo                                 | 1         | 0.07%   |
| HTC (High Tech Computer)               | 1         | 0.07%   |
| HMD Global                             | 1         | 0.07%   |
| Ericsson Business Mobile Networks      | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 408       | 25.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 106       | 6.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 2.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 2.3%    |
| Intel Wireless 8265 / 8275                                              | 36        | 2.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 1.74%   |
| Nvidia MCP61 Ethernet                                                   | 26        | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 1.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 1.24%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 1.12%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1%      |
| Ralink MT7601U Wireless Adapter                                         | 15        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 14        | 0.87%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 13        | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 12        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 12        | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 10        | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 10        | 0.62%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.56%   |
| Intel Wireless 7260                                                     | 9         | 0.56%   |
| Intel I211 Gigabit Network Connection                                   | 9         | 0.56%   |
| Intel Ethernet Connection (2) I219-V                                    | 9         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 8         | 0.5%    |
| Intel Wireless 7265                                                     | 8         | 0.5%    |
| Intel WiFi Link 5100                                                    | 8         | 0.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 7         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 205       | 28.16%  |
| Qualcomm Atheros                | 204       | 28.02%  |
| Realtek Semiconductor           | 136       | 18.68%  |
| Broadcom                        | 79        | 10.85%  |
| Ralink Technology               | 21        | 2.88%   |
| Ralink                          | 21        | 2.88%   |
| TP-Link                         | 18        | 2.47%   |
| Broadcom Limited                | 10        | 1.37%   |
| D-Link                          | 8         | 1.1%    |
| MediaTek                        | 7         | 0.96%   |
| Qualcomm Atheros Communications | 4         | 0.55%   |
| Sierra Wireless                 | 3         | 0.41%   |
| IMC Networks                    | 2         | 0.27%   |
| Fibocom                         | 2         | 0.27%   |
| Texas Instruments               | 1         | 0.14%   |
| Qualcomm                        | 1         | 0.14%   |
| Philips (or NXP)                | 1         | 0.14%   |
| Microsoft                       | 1         | 0.14%   |
| Mercucys                        | 1         | 0.14%   |
| Marvell Technology Group        | 1         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.14%   |
| D-Link System                   | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 7.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 5.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 5.05%   |
| Intel Wireless 8265 / 8275                                              | 36        | 4.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 4.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 21        | 2.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 2.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 2.73%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 2.46%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.19%   |
| Ralink MT7601U Wireless Adapter                                         | 15        | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 13        | 1.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 1.5%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 10        | 1.37%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 9         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.23%   |
| Intel Wireless 7260                                                     | 9         | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.09%   |
| Intel Wireless 7265                                                     | 8         | 1.09%   |
| Intel WiFi Link 5100                                                    | 8         | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.96%   |
| Intel Wireless 8260                                                     | 7         | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.96%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.68%   |
| Intel Wireless 3165                                                     | 5         | 0.68%   |
| Intel Centrino Wireless-N 130                                           | 5         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.55%   |
| Ralink RT5370 Wireless Adapter                                          | 4         | 0.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 537       | 62.51%  |
| Qualcomm Atheros                       | 84        | 9.78%   |
| Intel                                  | 76        | 8.85%   |
| Broadcom                               | 42        | 4.89%   |
| Nvidia                                 | 38        | 4.42%   |
| Marvell Technology Group               | 31        | 3.61%   |
| Broadcom Limited                       | 6         | 0.7%    |
| VIA Technologies                       | 5         | 0.58%   |
| Huawei Technologies                    | 5         | 0.58%   |
| Xiaomi                                 | 4         | 0.47%   |
| JMicron Technology                     | 4         | 0.47%   |
| Sundance Technology Inc / IC Plus      | 3         | 0.35%   |
| D-Link System                          | 3         | 0.35%   |
| Attansic Technology                    | 3         | 0.35%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.23%   |
| TP-Link                                | 2         | 0.23%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.23%   |
| Aquantia                               | 2         | 0.23%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.12%   |
| Samsung Electronics                    | 1         | 0.12%   |
| Qualcomm                               | 1         | 0.12%   |
| Motorola PCS                           | 1         | 0.12%   |
| Lenovo                                 | 1         | 0.12%   |
| HTC (High Tech Computer)               | 1         | 0.12%   |
| HMD Global                             | 1         | 0.12%   |
| Davicom Semiconductor                  | 1         | 0.12%   |
| ASIX Electronics                       | 1         | 0.12%   |
| Apple                                  | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 408       | 46.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 106       | 12.2%   |
| Nvidia MCP61 Ethernet                                                          | 26        | 2.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 14        | 1.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 12        | 1.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 1.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 10        | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 10        | 1.15%   |
| Intel I211 Gigabit Network Connection                                          | 9         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                           | 9         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 8         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.69%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 0.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 0.69%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 6         | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.58%   |
| Intel 82579V Gigabit Network Connection                                        | 5         | 0.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 0.46%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 4         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 4         | 0.46%   |
| Nvidia MCP65 Ethernet                                                          | 4         | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.46%   |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.46%   |
| Huawei ATU-L21                                                                 | 4         | 0.46%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.46%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 3         | 0.35%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 3         | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.35%   |
| Nvidia MCP55 Ethernet                                                          | 3         | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 3         | 0.35%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 3         | 0.35%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 825       | 54.1%   |
| WiFi     | 693       | 45.44%  |
| Modem    | 6         | 0.39%   |
| Unknown  | 1         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 589       | 59.92%  |
| Ethernet | 394       | 40.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 548       | 58.48%  |
| 1     | 368       | 39.27%  |
| 0     | 13        | 1.39%   |
| 3     | 7         | 0.75%   |
| 4     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 925       | 98.3%   |
| Yes  | 16        | 1.7%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 166       | 32.05%  |
| Realtek Semiconductor           | 77        | 14.86%  |
| Qualcomm Atheros Communications | 60        | 11.58%  |
| Broadcom                        | 34        | 6.56%   |
| IMC Networks                    | 33        | 6.37%   |
| Lite-On Technology              | 27        | 5.21%   |
| Cambridge Silicon Radio         | 24        | 4.63%   |
| Foxconn / Hon Hai               | 22        | 4.25%   |
| ASUSTek Computer                | 14        | 2.7%    |
| Ralink                          | 13        | 2.51%   |
| Foxconn International           | 10        | 1.93%   |
| Toshiba                         | 7         | 1.35%   |
| Hewlett-Packard                 | 7         | 1.35%   |
| Apple                           | 4         | 0.77%   |
| Ralink Technology               | 3         | 0.58%   |
| Taiyo Yuden                     | 2         | 0.39%   |
| Qcom                            | 2         | 0.39%   |
| MediaTek                        | 2         | 0.39%   |
| Integrated System Solution      | 2         | 0.39%   |
| Dell                            | 2         | 0.39%   |
| USI                             | 1         | 0.19%   |
| TP-Link                         | 1         | 0.19%   |
| Realtek                         | 1         | 0.19%   |
| Micro Star International        | 1         | 0.19%   |
| Marvell Semiconductor           | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |
| Alps Electric                   | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 69        | 13.29%  |
| Realtek Bluetooth Radio                             | 55        | 10.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 36        | 6.94%   |
| Intel AX201 Bluetooth                               | 28        | 5.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 24        | 4.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 3.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 3.66%   |
| Intel AX200 Bluetooth                               | 16        | 3.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 15        | 2.89%   |
| Ralink RT3290 Bluetooth                             | 13        | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 2.31%   |
| IMC Networks Bluetooth Radio                        | 11        | 2.12%   |
| Lite-On Bluetooth Device                            | 10        | 1.93%   |
| Foxconn International BCM43142A0 Bluetooth module   | 10        | 1.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 1.73%   |
| IMC Networks Bluetooth Device                       | 8         | 1.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 8         | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.35%   |
| Broadcom BCM2070 Bluetooth Device                   | 7         | 1.35%   |
| Qualcomm Atheros Bluetooth                          | 6         | 1.16%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.16%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.96%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.96%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.77%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.77%   |
| Toshiba RT Bluetooth Radio                          | 3         | 0.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.58%   |
| IMC Networks Wireless_Device                        | 3         | 0.58%   |
| IMC Networks Bluetooth USB Host Controller          | 3         | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.58%   |
| Foxconn / Hon Hai BCM43142A0                        | 3         | 0.58%   |
| Foxconn / Hon Hai BCM20702A0                        | 3         | 0.58%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 3         | 0.58%   |
| ASUS BT-270 Bluetooth Adapter                       | 3         | 0.58%   |
| ASUS BT-253 Bluetooth Adapter                       | 3         | 0.58%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.39%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 2         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 642       | 52.75%  |
| AMD                              | 260       | 21.36%  |
| Nvidia                           | 227       | 18.65%  |
| C-Media Electronics              | 17        | 1.4%    |
| Creative Labs                    | 11        | 0.9%    |
| Logitech                         | 9         | 0.74%   |
| JMTek                            | 7         | 0.58%   |
| Texas Instruments                | 5         | 0.41%   |
| Silicon Integrated Systems [SiS] | 4         | 0.33%   |
| Generalplus Technology           | 3         | 0.25%   |
| Conexant Systems                 | 3         | 0.25%   |
| Tenx Technology                  | 2         | 0.16%   |
| SteelSeries ApS                  | 2         | 0.16%   |
| M-Audio                          | 2         | 0.16%   |
| GYROCOM C&C                      | 2         | 0.16%   |
| ESS Technology                   | 2         | 0.16%   |
| Yamaha                           | 1         | 0.08%   |
| VIA Technologies                 | 1         | 0.08%   |
| ROCCAT                           | 1         | 0.08%   |
| Realtek Semiconductor            | 1         | 0.08%   |
| Plantronics                      | 1         | 0.08%   |
| Pixart Imaging                   | 1         | 0.08%   |
| NXP Semiconductors               | 1         | 0.08%   |
| Kingston Technology              | 1         | 0.08%   |
| iCreate Technologies             | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |
| GN Netcom                        | 1         | 0.08%   |
| FIFINE Microphones               | 1         | 0.08%   |
| Edifier Technology               | 1         | 0.08%   |
| Creative Technology              | 1         | 0.08%   |
| BR25                             | 1         | 0.08%   |
| BEHRINGER International          | 1         | 0.08%   |
| ATI Technologies                 | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |
| Unknown                          | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 84        | 5.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 81        | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 59        | 4.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 59        | 4.09%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 58        | 4.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 51        | 3.53%   |
| AMD FCH Azalia Controller                                                                         | 48        | 3.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 2.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 35        | 2.43%   |
| Nvidia MCP61 High Definition Audio                                                                | 32        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 2.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 28        | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 28        | 1.94%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 1.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 1.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 1.52%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 21        | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 21        | 1.46%   |
| Nvidia High Definition Audio Controller                                                           | 17        | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.18%   |
| AMD Trinity HDMI Audio Controller                                                                 | 16        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 0.9%    |
| AMD Wrestler HDMI Audio                                                                           | 13        | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 13        | 0.9%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 12        | 0.83%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 12        | 0.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 12        | 0.83%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 12        | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 12        | 0.83%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 10        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 183       | 21.55%  |
| Samsung Electronics   | 155       | 18.26%  |
| SK hynix              | 123       | 14.49%  |
| Kingston              | 115       | 13.55%  |
| Micron Technology     | 58        | 6.83%   |
| Crucial               | 53        | 6.24%   |
| Elpida                | 24        | 2.83%   |
| Ramaxel Technology    | 16        | 1.88%   |
| Nanya Technology      | 15        | 1.77%   |
| A-DATA Technology     | 13        | 1.53%   |
| Patriot               | 11        | 1.3%    |
| Corsair               | 11        | 1.3%    |
| G.Skill               | 8         | 0.94%   |
| Transcend             | 7         | 0.82%   |
| Silicon Power         | 7         | 0.82%   |
| Goodram               | 7         | 0.82%   |
| ASint Technology      | 7         | 0.82%   |
| GeIL                  | 4         | 0.47%   |
| 48spaces              | 4         | 0.47%   |
| Unknown               | 4         | 0.47%   |
| Team                  | 3         | 0.35%   |
| Apacer                | 3         | 0.35%   |
| Unknown (ABCD)        | 2         | 0.24%   |
| TakeMS                | 2         | 0.24%   |
| Qumo                  | 2         | 0.24%   |
| Kllisre               | 2         | 0.24%   |
| Kingmax               | 2         | 0.24%   |
| Wilk Elektronik       | 1         | 0.12%   |
| Wilk                  | 1         | 0.12%   |
| SHARETRONIC           | 1         | 0.12%   |
| Qimonda               | 1         | 0.12%   |
| PNY                   | 1         | 0.12%   |
| Kingmax Semiconductor | 1         | 0.12%   |
| Goldkey               | 1         | 0.12%   |
| AMD                   | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s  | 12        | 1.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s   | 10        | 1.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 8         | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s   | 8         | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s   | 8         | 0.86%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 7         | 0.75%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s   | 7         | 0.75%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 6         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s           | 6         | 0.64%   |
| Unknown RAM Module 1024MB DIMM SDRAM                    | 6         | 0.64%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s   | 6         | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s   | 6         | 0.64%   |
| Kingston RAM ACR16D3LS1NGG/4G 4GB SODIMM DDR3 1600MT/s  | 6         | 0.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s              | 5         | 0.54%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 5         | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2                     | 5         | 0.54%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s           | 5         | 0.54%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s  | 5         | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s   | 5         | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s   | 5         | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s   | 5         | 0.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s   | 5         | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s            | 4         | 0.43%   |
| Unknown RAM Module 2GB DIMM 800MT/s                     | 4         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s           | 4         | 0.43%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                  | 4         | 0.43%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 4         | 0.43%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 4         | 0.43%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s  | 4         | 0.43%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s  | 4         | 0.43%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s  | 4         | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s  | 4         | 0.43%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s         | 4         | 0.43%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s   | 4         | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s   | 4         | 0.43%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR 975MT/s    | 4         | 0.43%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s | 4         | 0.43%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s    | 4         | 0.43%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s    | 4         | 0.43%   |
| Kingston RAM 99U5469-070.A00LF 4GB SODIMM DDR3 1600MT/s | 4         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 311       | 42.6%   |
| DDR4    | 192       | 26.3%   |
| DDR2    | 75        | 10.27%  |
| Unknown | 74        | 10.14%  |
| SDRAM   | 48        | 6.58%   |
| LPDDR4  | 14        | 1.92%   |
| DDR     | 9         | 1.23%   |
| DRAM    | 4         | 0.55%   |
| LPDDR3  | 2         | 0.27%   |
| LPDDR5  | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 434       | 60.45%  |
| DIMM         | 268       | 37.33%  |
| Row Of Chips | 16        | 2.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 299       | 35.85%  |
| 2048  | 218       | 26.14%  |
| 8192  | 161       | 19.3%   |
| 16384 | 69        | 8.27%   |
| 1024  | 66        | 7.91%   |
| 512   | 14        | 1.68%   |
| 32768 | 4         | 0.48%   |
| 256   | 2         | 0.24%   |
| 16    | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 205       | 25.95%  |
| 2667    | 66        | 8.35%   |
| 3200    | 62        | 7.85%   |
| 1333    | 61        | 7.72%   |
| 2400    | 47        | 5.95%   |
| 800     | 46        | 5.82%   |
| Unknown | 44        | 5.57%   |
| 667     | 43        | 5.44%   |
| 1334    | 41        | 5.19%   |
| 2133    | 17        | 2.15%   |
| 1067    | 15        | 1.9%    |
| 4199    | 14        | 1.77%   |
| 1066    | 13        | 1.65%   |
| 533     | 12        | 1.52%   |
| 400     | 12        | 1.52%   |
| 3600    | 10        | 1.27%   |
| 1867    | 10        | 1.27%   |
| 3266    | 8         | 1.01%   |
| 2048    | 8         | 1.01%   |
| 3466    | 6         | 0.76%   |
| 1866    | 6         | 0.76%   |
| 333     | 6         | 0.76%   |
| 4267    | 5         | 0.63%   |
| 49926   | 2         | 0.25%   |
| 8400    | 2         | 0.25%   |
| 4266    | 2         | 0.25%   |
| 3733    | 2         | 0.25%   |
| 3400    | 2         | 0.25%   |
| 2666    | 2         | 0.25%   |
| 1800    | 2         | 0.25%   |
| 1639    | 2         | 0.25%   |
| 266     | 2         | 0.25%   |
| 65535   | 1         | 0.13%   |
| 6400    | 1         | 0.13%   |
| 3866    | 1         | 0.13%   |
| 3800    | 1         | 0.13%   |
| 3007    | 1         | 0.13%   |
| 3000    | 1         | 0.13%   |
| 2733    | 1         | 0.13%   |
| 2187    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Canon                 | 6         | 27.27%  |
| Seiko Epson           | 5         | 22.73%  |
| Hewlett-Packard       | 5         | 22.73%  |
| Samsung Electronics   | 3         | 13.64%  |
| Ricoh                 | 1         | 4.55%   |
| QinHeng Electronics   | 1         | 4.55%   |
| Lexmark International | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| Canon LBP6030w/6018w              | 2         | 8.7%    |
| Seiko Epson M100 Series           | 1         | 4.35%   |
| Seiko Epson L805 Series           | 1         | 4.35%   |
| Seiko Epson L365 Series           | 1         | 4.35%   |
| Seiko Epson L222 Series           | 1         | 4.35%   |
| Seiko Epson L1250 Series          | 1         | 4.35%   |
| Samsung SCX-4300 Series           | 1         | 4.35%   |
| Samsung SCX-4200 series           | 1         | 4.35%   |
| Samsung Laser Printer             | 1         | 4.35%   |
| Ricoh SP 210SU                    | 1         | 4.35%   |
| QinHeng CH340S                    | 1         | 4.35%   |
| Lexmark International Z35 Printer | 1         | 4.35%   |
| HP LaserJet P2055 series          | 1         | 4.35%   |
| HP LaserJet P1006                 | 1         | 4.35%   |
| HP LaserJet P1005                 | 1         | 4.35%   |
| HP LaserJet 1300                  | 1         | 4.35%   |
| HP DeskJet 840c                   | 1         | 4.35%   |
| Canon MF4410                      | 1         | 4.35%   |
| Canon MF4010 series               | 1         | 4.35%   |
| Canon MF3010                      | 1         | 4.35%   |
| Canon LBP6020                     | 1         | 4.35%   |
| Canon G1000 series                | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 66.67%  |
| Ultima Electronics | 1         | 16.67%  |
| Seiko Epson        | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 16.67%  |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 16.67%  |
| Canon CanoScan LiDE 600F                                                              | 1         | 16.67%  |
| Canon CanoScan LiDE 60                                                                | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                                                | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 137       | 22.03%  |
| IMC Networks                           | 85        | 13.67%  |
| Realtek Semiconductor                  | 36        | 5.79%   |
| Logitech                               | 35        | 5.63%   |
| Quanta                                 | 34        | 5.47%   |
| Suyin                                  | 31        | 4.98%   |
| Sunplus Innovation Technology          | 27        | 4.34%   |
| Z-Star Microelectronics                | 24        | 3.86%   |
| Acer                                   | 24        | 3.86%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 3.7%    |
| Syntek                                 | 22        | 3.54%   |
| Silicon Motion                         | 22        | 3.54%   |
| Microdia                               | 21        | 3.38%   |
| Bison Electronics                      | 17        | 2.73%   |
| Lite-On Technology                     | 16        | 2.57%   |
| Alcor Micro                            | 11        | 1.77%   |
| Apple                                  | 8         | 1.29%   |
| Luxvisions Innotech Limited            | 5         | 0.8%    |
| Samsung Electronics                    | 4         | 0.64%   |
| Microsoft                              | 3         | 0.48%   |
| lihappe8                               | 3         | 0.48%   |
| Lenovo                                 | 3         | 0.48%   |
| Importek                               | 3         | 0.48%   |
| DigiTech                               | 3         | 0.48%   |
| Cubeternet                             | 3         | 0.48%   |
| Aveo Technology                        | 3         | 0.48%   |
| Ricoh                                  | 2         | 0.32%   |
| Primax Electronics                     | 2         | 0.32%   |
| Arkmicro Technologies                  | 2         | 0.32%   |
| SunplusIT                              | 1         | 0.16%   |
| Sonix Technology                       | 1         | 0.16%   |
| Shine-optics                           | 1         | 0.16%   |
| Razer USA                              | 1         | 0.16%   |
| Pixart Imaging                         | 1         | 0.16%   |
| Nokia Mobile Phones                    | 1         | 0.16%   |
| KYE Systems (Mouse Systems)            | 1         | 0.16%   |
| Intel                                  | 1         | 0.16%   |
| Genesys Logic                          | 1         | 0.16%   |
| GEMBIRD                                | 1         | 0.16%   |
| Fly                                    | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam   | 28        | 4.49%   |
| Chicony Integrated Camera            | 15        | 2.4%    |
| Logitech Webcam C270                 | 14        | 2.24%   |
| Realtek Integrated_Webcam_HD         | 12        | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam    | 12        | 1.92%   |
| Chicony USB2.0 VGA UVC WebCam        | 12        | 1.92%   |
| Chicony HD WebCam                    | 11        | 1.76%   |
| Sunplus HD Webcam                    | 10        | 1.6%    |
| IMC Networks Integrated Camera       | 10        | 1.6%    |
| Chicony Lenovo EasyCamera            | 10        | 1.6%    |
| Syntek Integrated Camera             | 8         | 1.28%   |
| Acer Lenovo EasyCamera               | 8         | 1.28%   |
| Syntek EasyCamera                    | 7         | 1.12%   |
| IMC Networks USB2.0 UVC HD Webcam    | 7         | 1.12%   |
| Acer Lenovo Integrated Webcam        | 7         | 1.12%   |
| Microdia Integrated_Webcam_HD        | 6         | 0.96%   |
| Logitech Webcam C310                 | 6         | 0.96%   |
| Chicony EasyCamera                   | 6         | 0.96%   |
| Z-Star A4 TECH USB2.0 PC Camera J    | 5         | 0.8%    |
| Syntek Lenovo EasyCamera             | 5         | 0.8%    |
| Suyin HP TrueVision HD               | 5         | 0.8%    |
| Silicon Motion WebCam SC-0311139N    | 5         | 0.8%    |
| Quanta HP HD Camera                  | 5         | 0.8%    |
| Quanta HD Webcam                     | 5         | 0.8%    |
| Lite-On Integrated Camera            | 5         | 0.8%    |
| Lite-On HP HD Camera                 | 5         | 0.8%    |
| IMC Networks UVC VGA Webcam          | 5         | 0.8%    |
| IMC Networks Integrated Webcam       | 5         | 0.8%    |
| Chicony USB2.0 HD UVC WebCam         | 5         | 0.8%    |
| Chicony HP HD Camera                 | 5         | 0.8%    |
| Bison Lenovo Integrated Webcam       | 5         | 0.8%    |
| Z-Star Venus USB2.0 Camera           | 4         | 0.64%   |
| Suyin HD Video WebCam                | 4         | 0.64%   |
| Silicon Motion WebCam SC-03FFL11939N | 4         | 0.64%   |
| Realtek USB Camera                   | 4         | 0.64%   |
| Quanta HP TrueVision HD Camera       | 4         | 0.64%   |
| Microdia Camera                      | 4         | 0.64%   |
| Chicony VGA Webcam                   | 4         | 0.64%   |
| Chicony HP Truevision HD camera      | 4         | 0.64%   |
| Chicony HP Truevision HD             | 4         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 28.57%  |
| Synaptics                  | 15        | 21.43%  |
| Elan Microelectronics      | 13        | 18.57%  |
| Shenzhen Goodix Technology | 10        | 14.29%  |
| AuthenTec                  | 6         | 8.57%   |
| STMicroelectronics         | 3         | 4.29%   |
| Upek                       | 2         | 2.86%   |
| LighTuning Technology      | 1         | 1.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 9         | 12.86%  |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 5.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 5.71%   |
| Elan ELAN:ARM-M4                                                           | 4         | 5.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.29%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 4.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.29%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 4.29%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.86%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.86%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.86%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 2.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.43%   |
| Validity Sensors VFS491                                                    | 1         | 1.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.43%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.43%   |
| Synaptics UWP WBDI                                                         | 1         | 1.43%   |
| Synaptics  WBDI                                                            | 1         | 1.43%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.43%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.43%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.43%   |
| AuthenTec AES2810                                                          | 1         | 1.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.43%   |
| AuthenTec AES1600                                                          | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 50%     |
| Lenovo      | 4         | 28.57%  |
| Broadcom    | 2         | 14.29%  |
| Upek        | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 50%     |
| Lenovo Integrated Smart Card Reader                                          | 4         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 728       | 75.91%  |
| 1     | 192       | 20.02%  |
| 2     | 33        | 3.44%   |
| 3     | 5         | 0.52%   |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 103       | 39.31%  |
| Fingerprint reader       | 68        | 25.95%  |
| Net/wireless             | 20        | 7.63%   |
| Bluetooth                | 15        | 5.73%   |
| Multimedia controller    | 13        | 4.96%   |
| Communication controller | 11        | 4.2%    |
| Chipcard                 | 11        | 4.2%    |
| Camera                   | 8         | 3.05%   |
| Storage                  | 4         | 1.53%   |
| Sound                    | 3         | 1.15%   |
| Card reader              | 2         | 0.76%   |
| Unassigned class         | 1         | 0.38%   |
| Net/ethernet             | 1         | 0.38%   |
| Modem                    | 1         | 0.38%   |
| Flash memory             | 1         | 0.38%   |


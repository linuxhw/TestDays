Linux in Belarus - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Belarus.

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

Total: 1013

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HONOR         | HYM-WXX                     | [6f5e2be121](https://linux-hardware.org/?probe=6f5e2be121) | Aug 08, 2023 |
| HUAWEI        | KPRC-WX0                    | [f84c568d4b](https://linux-hardware.org/?probe=f84c568d4b) | Aug 07, 2023 |
| HP            | ProBook 450 G5              | [0482630783](https://linux-hardware.org/?probe=0482630783) | Aug 05, 2023 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [a9232da3e4](https://linux-hardware.org/?probe=a9232da3e4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| ASUSTek       | GL503VD                     | [4c3516813b](https://linux-hardware.org/?probe=4c3516813b) | Jul 28, 2023 |
| ASUSTek       | X550CC                      | [792e9db762](https://linux-hardware.org/?probe=792e9db762) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ca354dd42d](https://linux-hardware.org/?probe=ca354dd42d) | Jul 23, 2023 |
| HP            | ProBook 4545s               | [cf43675118](https://linux-hardware.org/?probe=cf43675118) | Jul 20, 2023 |
| Unknown       | Unknown                     | [7e6c1d1018](https://linux-hardware.org/?probe=7e6c1d1018) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| HP            | Pavilion Notebook           | [6623b71de2](https://linux-hardware.org/?probe=6623b71de2) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab43e6b8ef](https://linux-hardware.org/?probe=ab43e6b8ef) | Jul 16, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [6b52cef555](https://linux-hardware.org/?probe=6b52cef555) | Jul 16, 2023 |
| HP            | 255 G8 Notebook PC          | [584f2a2ac4](https://linux-hardware.org/?probe=584f2a2ac4) | Jul 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e9e376fb10](https://linux-hardware.org/?probe=e9e376fb10) | Jul 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [33a8b4ab02](https://linux-hardware.org/?probe=33a8b4ab02) | Jul 08, 2023 |
| Valve         | Jupiter                     | [dfb0bd07f1](https://linux-hardware.org/?probe=dfb0bd07f1) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | [d33df8d1a0](https://linux-hardware.org/?probe=d33df8d1a0) | Jul 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| HP            | Pavilion Notebook           | [a33602b335](https://linux-hardware.org/?probe=a33602b335) | Jun 29, 2023 |
| HP            | EliteBook 840 G1            | [37239831de](https://linux-hardware.org/?probe=37239831de) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| HP            | 255 G1                      | [f09174c096](https://linux-hardware.org/?probe=f09174c096) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e26b3e6d58](https://linux-hardware.org/?probe=e26b3e6d58) | Jun 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [0b6bb0a043](https://linux-hardware.org/?probe=0b6bb0a043) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [50626f77d7](https://linux-hardware.org/?probe=50626f77d7) | Jun 18, 2023 |
| ASUSTek       | X551CAP                     | [9066d9bad2](https://linux-hardware.org/?probe=9066d9bad2) | Jun 17, 2023 |
| Sony          | SVF1521L1RB                 | [b0dfbb64d0](https://linux-hardware.org/?probe=b0dfbb64d0) | Jun 17, 2023 |
| Dell          | Inspiron 15-3573            | [129574e8dc](https://linux-hardware.org/?probe=129574e8dc) | Jun 14, 2023 |
| HP            | 255 G1                      | [a8c4597ccd](https://linux-hardware.org/?probe=a8c4597ccd) | Jun 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c8ca6e8787](https://linux-hardware.org/?probe=c8ca6e8787) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [320e5bee32](https://linux-hardware.org/?probe=320e5bee32) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1e23f3e627](https://linux-hardware.org/?probe=1e23f3e627) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [960ddf4eaf](https://linux-hardware.org/?probe=960ddf4eaf) | May 28, 2023 |
| Toshiba       | Satellite C850-C5K          | [481789fa1e](https://linux-hardware.org/?probe=481789fa1e) | May 28, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5162ff793e](https://linux-hardware.org/?probe=5162ff793e) | May 27, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8962578738](https://linux-hardware.org/?probe=8962578738) | May 26, 2023 |
| HP            | 255 G8 Notebook PC          | [eb644c96f3](https://linux-hardware.org/?probe=eb644c96f3) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [b3eaf738e4](https://linux-hardware.org/?probe=b3eaf738e4) | May 18, 2023 |
| MSI           | GE72 7RE                    | [15a31e188f](https://linux-hardware.org/?probe=15a31e188f) | May 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [9201edcfb8](https://linux-hardware.org/?probe=9201edcfb8) | May 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [32b3c782ff](https://linux-hardware.org/?probe=32b3c782ff) | May 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [fe4b074a5c](https://linux-hardware.org/?probe=fe4b074a5c) | May 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Acer          | Swift SF114-32              | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [699adff825](https://linux-hardware.org/?probe=699adff825) | Apr 24, 2023 |
| Samsung       | R59P/R60P/R61P              | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [94bd5fe556](https://linux-hardware.org/?probe=94bd5fe556) | Apr 21, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [50c44b15eb](https://linux-hardware.org/?probe=50c44b15eb) | Apr 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [9cb44b75f5](https://linux-hardware.org/?probe=9cb44b75f5) | Apr 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9f5fa03bfd](https://linux-hardware.org/?probe=9f5fa03bfd) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | [f87a34e474](https://linux-hardware.org/?probe=f87a34e474) | Apr 19, 2023 |
| Samsung       | NC210/NC110                 | [9cacd6f238](https://linux-hardware.org/?probe=9cacd6f238) | Apr 19, 2023 |
| TECNO         | MEGABOOK T1                 | [733d7d5584](https://linux-hardware.org/?probe=733d7d5584) | Apr 18, 2023 |
| ASUSTek       | X75VCP                      | [a02f8565dd](https://linux-hardware.org/?probe=a02f8565dd) | Apr 14, 2023 |
| ASUSTek       | X75VCP                      | [5ecb1bb650](https://linux-hardware.org/?probe=5ecb1bb650) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U745               | [82bfc450e9](https://linux-hardware.org/?probe=82bfc450e9) | Apr 12, 2023 |
| Dell          | Inspiron 15-3552            | [5c23d1d7f7](https://linux-hardware.org/?probe=5c23d1d7f7) | Apr 08, 2023 |
| HP            | Laptop 17-cp0xxx            | [be2a3d30f2](https://linux-hardware.org/?probe=be2a3d30f2) | Apr 08, 2023 |
| Apple         | MacBookAir4,2               | [6dafdf20a5](https://linux-hardware.org/?probe=6dafdf20a5) | Apr 02, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Toshiba       | Satellite C850-C5K          | [8fc7451def](https://linux-hardware.org/?probe=8fc7451def) | Mar 30, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [51f6d77f50](https://linux-hardware.org/?probe=51f6d77f50) | Mar 30, 2023 |
| Dell          | System XPS L702X            | [2c8aed8334](https://linux-hardware.org/?probe=2c8aed8334) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| HP            | Notebook                    | [f18d14ac70](https://linux-hardware.org/?probe=f18d14ac70) | Mar 28, 2023 |
| HP            | 250 G1                      | [a19b3136b7](https://linux-hardware.org/?probe=a19b3136b7) | Mar 26, 2023 |
| Lenovo        | 3000 G530 4151/200          | [4c0751aa89](https://linux-hardware.org/?probe=4c0751aa89) | Mar 26, 2023 |
| HP            | Pavilion dv7                | [6ae381093b](https://linux-hardware.org/?probe=6ae381093b) | Mar 26, 2023 |
| Getac         | B300-H                      | [28a9b0b0c7](https://linux-hardware.org/?probe=28a9b0b0c7) | Mar 25, 2023 |
| HP            | ProBook 450 G5              | [c4b7067187](https://linux-hardware.org/?probe=c4b7067187) | Mar 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [ea18262536](https://linux-hardware.org/?probe=ea18262536) | Mar 22, 2023 |
| HP            | Pavilion dv6                | [43940eb778](https://linux-hardware.org/?probe=43940eb778) | Mar 20, 2023 |
| HP            | Pavilion dv7                | [d42628a0e9](https://linux-hardware.org/?probe=d42628a0e9) | Mar 19, 2023 |
| HP            | 250 G7 Notebook PC          | [5033dda127](https://linux-hardware.org/?probe=5033dda127) | Mar 19, 2023 |
| ASUSTek       | X555LB                      | [a00be2eabe](https://linux-hardware.org/?probe=a00be2eabe) | Mar 17, 2023 |
| HP            | Pavilion dv6                | [b5746d500d](https://linux-hardware.org/?probe=b5746d500d) | Mar 13, 2023 |
| Sony          | VPCEB3S1R                   | [0e89d9279d](https://linux-hardware.org/?probe=0e89d9279d) | Mar 12, 2023 |
| Sony          | VPCEB3S1R                   | [8541575b10](https://linux-hardware.org/?probe=8541575b10) | Mar 12, 2023 |
| Lenovo        | G50-70 20351                | [249f986099](https://linux-hardware.org/?probe=249f986099) | Mar 09, 2023 |
| HP            | Compaq 610                  | [3f5ffc0582](https://linux-hardware.org/?probe=3f5ffc0582) | Mar 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [48dc89b146](https://linux-hardware.org/?probe=48dc89b146) | Mar 07, 2023 |
| HP            | ProBook 450 G2              | [546d7b3f27](https://linux-hardware.org/?probe=546d7b3f27) | Mar 07, 2023 |
| Acer          | Aspire 5739G                | [efd6fd1985](https://linux-hardware.org/?probe=efd6fd1985) | Mar 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e682158c7f](https://linux-hardware.org/?probe=e682158c7f) | Mar 06, 2023 |
| Dell          | Vostro 3500                 | [268e27cc20](https://linux-hardware.org/?probe=268e27cc20) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| Lenovo        | G550 20023                  | [e8325b5ff1](https://linux-hardware.org/?probe=e8325b5ff1) | Mar 03, 2023 |
| ASUSTek       | UX31A                       | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| Toshiba       | Satellite L300              | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c85bd630f0](https://linux-hardware.org/?probe=c85bd630f0) | Feb 25, 2023 |
| HP            | 250 G8 Notebook PC          | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Samsung       | RV413/RV513                 | [5b524ddbb0](https://linux-hardware.org/?probe=5b524ddbb0) | Feb 23, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [bb2bef71e0](https://linux-hardware.org/?probe=bb2bef71e0) | Feb 23, 2023 |
| Dell          | Inspiron N5110              | [9b00bf7704](https://linux-hardware.org/?probe=9b00bf7704) | Feb 22, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [dc6a6f7872](https://linux-hardware.org/?probe=dc6a6f7872) | Feb 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [788044d53c](https://linux-hardware.org/?probe=788044d53c) | Feb 20, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d8abf7361b](https://linux-hardware.org/?probe=d8abf7361b) | Feb 20, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [faa600d8e5](https://linux-hardware.org/?probe=faa600d8e5) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [dfa8cae135](https://linux-hardware.org/?probe=dfa8cae135) | Feb 17, 2023 |
| ASUSTek       | X540YA                      | [3faff8d320](https://linux-hardware.org/?probe=3faff8d320) | Feb 17, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [44e18a0f72](https://linux-hardware.org/?probe=44e18a0f72) | Feb 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [92a9452070](https://linux-hardware.org/?probe=92a9452070) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| ASUSTek       | X550CL                      | [0da8e9ac4c](https://linux-hardware.org/?probe=0da8e9ac4c) | Feb 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| HP            | Compaq Presario CQ70        | [5644272d9e](https://linux-hardware.org/?probe=5644272d9e) | Feb 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire E5-572G              | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [87b269febc](https://linux-hardware.org/?probe=87b269febc) | Feb 08, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [a1549a7701](https://linux-hardware.org/?probe=a1549a7701) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f3ec6a2ed1](https://linux-hardware.org/?probe=f3ec6a2ed1) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Dell          | Inspiron 3581               | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f94175d8c](https://linux-hardware.org/?probe=6f94175d8c) | Jan 28, 2023 |
| Apple         | MacBookPro8,2               | [add8440e16](https://linux-hardware.org/?probe=add8440e16) | Jan 27, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [f4e06ff0b2](https://linux-hardware.org/?probe=f4e06ff0b2) | Jan 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | [cb2e9f2623](https://linux-hardware.org/?probe=cb2e9f2623) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Inspiron 15-3552            | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [7c116ff037](https://linux-hardware.org/?probe=7c116ff037) | Jan 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [4606ff1dab](https://linux-hardware.org/?probe=4606ff1dab) | Jan 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [fdb726b276](https://linux-hardware.org/?probe=fdb726b276) | Jan 11, 2023 |
| MSI           | Modern 15 A5M               | [18654d5f58](https://linux-hardware.org/?probe=18654d5f58) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [325952460c](https://linux-hardware.org/?probe=325952460c) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [ac63fca6cb](https://linux-hardware.org/?probe=ac63fca6cb) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | [684653e302](https://linux-hardware.org/?probe=684653e302) | Jan 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [d196b92cff](https://linux-hardware.org/?probe=d196b92cff) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [beb602dcf6](https://linux-hardware.org/?probe=beb602dcf6) | Dec 23, 2022 |
| Toshiba       | Satellite C850-C5K          | [a67d24c9f9](https://linux-hardware.org/?probe=a67d24c9f9) | Dec 23, 2022 |
| LTD Delovo... | EVE 14 C414 ES4060EW        | [9f1751d2e5](https://linux-hardware.org/?probe=9f1751d2e5) | Dec 22, 2022 |
| Pegatron      | A17                         | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | G500 20236                  | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b463c25c4d](https://linux-hardware.org/?probe=b463c25c4d) | Dec 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [1c80b48ea0](https://linux-hardware.org/?probe=1c80b48ea0) | Dec 11, 2022 |
| HP            | 550                         | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [1a1f2b375d](https://linux-hardware.org/?probe=1a1f2b375d) | Dec 05, 2022 |
| Dell          | Inspiron 5570               | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| HP            | Pavilion g6                 | [c3f0c49c7c](https://linux-hardware.org/?probe=c3f0c49c7c) | Dec 02, 2022 |
| HP            | Pavilion g6                 | [cb93839085](https://linux-hardware.org/?probe=cb93839085) | Dec 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [2de79b83d5](https://linux-hardware.org/?probe=2de79b83d5) | Nov 28, 2022 |
| ASUSTek       | K70AB                       | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Inspiron 3501               | [1c7b4c3780](https://linux-hardware.org/?probe=1c7b4c3780) | Nov 21, 2022 |
| HASEE Comp... | V1x0PNPx                    | [e75868724e](https://linux-hardware.org/?probe=e75868724e) | Nov 19, 2022 |
| Lenovo        | G580 20150                  | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [b64a32327f](https://linux-hardware.org/?probe=b64a32327f) | Nov 11, 2022 |
| ASUSTek       | UX31A                       | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [423a8f624c](https://linux-hardware.org/?probe=423a8f624c) | Nov 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [09c253d548](https://linux-hardware.org/?probe=09c253d548) | Nov 07, 2022 |
| Chuwi         | GemiBook                    | [9d1fda5ecb](https://linux-hardware.org/?probe=9d1fda5ecb) | Nov 06, 2022 |
| Dell          | Inspiron 7577               | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3cb1f34e2a](https://linux-hardware.org/?probe=3cb1f34e2a) | Nov 04, 2022 |
| ASUSTek       | K501LB                      | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| Unknown       | Unknown                     | [77bdbb310f](https://linux-hardware.org/?probe=77bdbb310f) | Oct 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3f69e984d1](https://linux-hardware.org/?probe=3f69e984d1) | Oct 30, 2022 |
| ASUSTek       | K501LB                      | [25003181f1](https://linux-hardware.org/?probe=25003181f1) | Oct 27, 2022 |
| ASUSTek       | K501LB                      | [2481764903](https://linux-hardware.org/?probe=2481764903) | Oct 27, 2022 |
| HP            | Compaq 610                  | [5adc7e0aba](https://linux-hardware.org/?probe=5adc7e0aba) | Oct 26, 2022 |
| HP            | Compaq 610                  | [9a584886fe](https://linux-hardware.org/?probe=9a584886fe) | Oct 23, 2022 |
| Dell          | Inspiron 7577               | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| Acer          | Aspire E1-531               | [527c4e0728](https://linux-hardware.org/?probe=527c4e0728) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| Acer          | Aspire E1-531               | [834248c556](https://linux-hardware.org/?probe=834248c556) | Oct 16, 2022 |
| ASUSTek       | X751LD                      | [230969c119](https://linux-hardware.org/?probe=230969c119) | Oct 12, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| ASUSTek       | T101MT                      | [d0fc7c3dae](https://linux-hardware.org/?probe=d0fc7c3dae) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4a8d27ad0f](https://linux-hardware.org/?probe=4a8d27ad0f) | Oct 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| HP            | ProBook 450 G2              | [2935c5bedd](https://linux-hardware.org/?probe=2935c5bedd) | Sep 27, 2022 |
| HP            | Pavilion dv4000 (PX306UA... | [372160583e](https://linux-hardware.org/?probe=372160583e) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [a861ca9999](https://linux-hardware.org/?probe=a861ca9999) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Apple         | MacBookPro16,1              | [467d4c60c0](https://linux-hardware.org/?probe=467d4c60c0) | Sep 16, 2022 |
| ASUSTek       | X550MD                      | [69cce160a1](https://linux-hardware.org/?probe=69cce160a1) | Sep 16, 2022 |
| Toshiba       | Satellite C850-C5K          | [51dbca1f4d](https://linux-hardware.org/?probe=51dbca1f4d) | Sep 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Acer          | Aspire E1-571G              | [414795a69b](https://linux-hardware.org/?probe=414795a69b) | Aug 29, 2022 |
| HP            | Compaq 610                  | [538b6ae6f8](https://linux-hardware.org/?probe=538b6ae6f8) | Aug 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| Dell          | XPS 13 9370                 | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Acer          | Aspire 7750ZG               | [e0d514dd08](https://linux-hardware.org/?probe=e0d514dd08) | Aug 21, 2022 |
| Lenovo        | Z710 20250                  | [8c7e567f41](https://linux-hardware.org/?probe=8c7e567f41) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| HP            | Compaq 610                  | [2b90520f8f](https://linux-hardware.org/?probe=2b90520f8f) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f685da542](https://linux-hardware.org/?probe=3f685da542) | Aug 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f41308ccdc](https://linux-hardware.org/?probe=f41308ccdc) | Aug 12, 2022 |
| Sony          | SVF1521L1RW                 | [c5f143f93d](https://linux-hardware.org/?probe=c5f143f93d) | Aug 09, 2022 |
| MSI           | Katana GF76 11UC            | [4b4e4d693e](https://linux-hardware.org/?probe=4b4e4d693e) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| ASUSTek       | X541UV                      | [feb8312a2c](https://linux-hardware.org/?probe=feb8312a2c) | Aug 04, 2022 |
| HONOR         | NBR-WAX9                    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Dell          | Vostro 3500                 | [c8562d4bac](https://linux-hardware.org/?probe=c8562d4bac) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| Dell          | Vostro 3500                 | [4e757278be](https://linux-hardware.org/?probe=4e757278be) | Jul 24, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Fujitsu       | AMILO Pi 3560               | [aed2d10046](https://linux-hardware.org/?probe=aed2d10046) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [c81bc160f7](https://linux-hardware.org/?probe=c81bc160f7) | Jul 13, 2022 |
| Samsung       | 535U3C                      | [80b2b79e75](https://linux-hardware.org/?probe=80b2b79e75) | Jul 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [15a618f993](https://linux-hardware.org/?probe=15a618f993) | Jul 08, 2022 |
| ASUSTek       | K501LB                      | [2ef855cc9c](https://linux-hardware.org/?probe=2ef855cc9c) | Jul 07, 2022 |
| HP            | Compaq 610                  | [62287cff21](https://linux-hardware.org/?probe=62287cff21) | Jul 06, 2022 |
| HONOR         | NBR-WAX9                    | [2fb330049e](https://linux-hardware.org/?probe=2fb330049e) | Jul 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [06d4d79742](https://linux-hardware.org/?probe=06d4d79742) | Jul 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| Prestigio     | Multipad Visconte V         | [fd38a70070](https://linux-hardware.org/?probe=fd38a70070) | Jun 29, 2022 |
| HONOR         | NBR-WAX9                    | [8cb88942e3](https://linux-hardware.org/?probe=8cb88942e3) | Jun 28, 2022 |
| Acer          | Aspire V3-571G              | [e52ad13385](https://linux-hardware.org/?probe=e52ad13385) | Jun 25, 2022 |
| Getac         | B300-H                      | [ff8382e269](https://linux-hardware.org/?probe=ff8382e269) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Getac         | B300-H                      | [d0b0703736](https://linux-hardware.org/?probe=d0b0703736) | Jun 23, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| HP            | Notebook                    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Acer          | Extensa 5220                | [dd0d362582](https://linux-hardware.org/?probe=dd0d362582) | Jun 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [8e7a43f724](https://linux-hardware.org/?probe=8e7a43f724) | Jun 13, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | Notebook                    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| Sony          | SVE1713Y1RB                 | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | [595e4c8656](https://linux-hardware.org/?probe=595e4c8656) | Jun 09, 2022 |
| Acer          | Aspire A315-56              | [0ee020dd5a](https://linux-hardware.org/?probe=0ee020dd5a) | Jun 09, 2022 |
| Acer          | Swift SF314-59              | [e057e3b6d8](https://linux-hardware.org/?probe=e057e3b6d8) | Jun 07, 2022 |
| HP            | Mini 110-4100               | [62932d62d5](https://linux-hardware.org/?probe=62932d62d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Lenovo        | IdeaPad Z580                | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| HP            | Pavilion 17                 | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| ASUSTek       | M51Sr                       | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [edefb39601](https://linux-hardware.org/?probe=edefb39601) | May 08, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7c8dbdcffc](https://linux-hardware.org/?probe=7c8dbdcffc) | May 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| Lenovo        | G710 20252                  | [9390db3498](https://linux-hardware.org/?probe=9390db3498) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | [7fb6e94bab](https://linux-hardware.org/?probe=7fb6e94bab) | Apr 27, 2022 |
| Sony          | SVF1521L1RB                 | [ff5ff260a0](https://linux-hardware.org/?probe=ff5ff260a0) | Apr 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | [18a941a40d](https://linux-hardware.org/?probe=18a941a40d) | Apr 19, 2022 |
| Sony          | SVF1521L1RB                 | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| HP            | Notebook                    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | [ab464ae6a9](https://linux-hardware.org/?probe=ab464ae6a9) | Apr 15, 2022 |
| Acer          | Aspire 5739G                | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [6099079c27](https://linux-hardware.org/?probe=6099079c27) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| Dell          | Inspiron N5110              | [993ad2218a](https://linux-hardware.org/?probe=993ad2218a) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| ASUSTek       | X541NC                      | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| Acer          | Swift SF314-59              | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| HP            | ProBook 455 G1              | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [29b8b7110c](https://linux-hardware.org/?probe=29b8b7110c) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2d741207c5](https://linux-hardware.org/?probe=2d741207c5) | Mar 30, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [803a20d0cb](https://linux-hardware.org/?probe=803a20d0cb) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | [ef7133f14a](https://linux-hardware.org/?probe=ef7133f14a) | Mar 25, 2022 |
| HP            | Pavilion dv3500             | [06883f214a](https://linux-hardware.org/?probe=06883f214a) | Mar 25, 2022 |
| HP            | ProBook 455 G1              | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [db687b8693](https://linux-hardware.org/?probe=db687b8693) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [770f279722](https://linux-hardware.org/?probe=770f279722) | Mar 13, 2022 |
| Dell          | XPS 13 9305                 | [69fd2b147f](https://linux-hardware.org/?probe=69fd2b147f) | Mar 11, 2022 |
| Toshiba       | Satellite C650              | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| HP            | Mini 110-4100               | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | [aebf1eb00c](https://linux-hardware.org/?probe=aebf1eb00c) | Mar 07, 2022 |
| Acer          | Swift SF114-34              | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| HP            | 635                         | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| MSI           | Katana GF76 11UC            | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | Katana GF76 11UC            | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Sony          | VPCF119FX                   | [1e8448b824](https://linux-hardware.org/?probe=1e8448b824) | Feb 15, 2022 |
| ASUSTek       | K50C                        | [01079b722b](https://linux-hardware.org/?probe=01079b722b) | Feb 11, 2022 |
| ASUSTek       | K50C                        | [8bb8c751f8](https://linux-hardware.org/?probe=8bb8c751f8) | Feb 11, 2022 |
| Lenovo        | V580c 20160                 | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| HUAWEI        | HLYL-WXX9                   | [0bcf18e1fc](https://linux-hardware.org/?probe=0bcf18e1fc) | Feb 01, 2022 |
| HP            | Compaq 8710w (GC124EA#AC... | [b21e187792](https://linux-hardware.org/?probe=b21e187792) | Jan 29, 2022 |
| HP            | Presario CQ57               | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| HUAWEI        | HLYL-WXX9                   | [abed2f64a1](https://linux-hardware.org/?probe=abed2f64a1) | Jan 26, 2022 |
| Acer          | Aspire F5-572G              | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e00760f649](https://linux-hardware.org/?probe=e00760f649) | Jan 21, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| ASUSTek       | X550CA                      | [8f9c010abb](https://linux-hardware.org/?probe=8f9c010abb) | Jan 10, 2022 |
| Dell          | G7 7700                     | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Timi          | TM1613                      | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| MSI           | GT75 Titan 8RG              | [77e24243cf](https://linux-hardware.org/?probe=77e24243cf) | Jan 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Lenovo        | V580c 20160                 | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| Lenovo        | ThinkPad E15 20RD003KRT     | [62e3c3073b](https://linux-hardware.org/?probe=62e3c3073b) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [29b9cc77f1](https://linux-hardware.org/?probe=29b9cc77f1) | Dec 21, 2021 |
| ASUSTek       | X540UA                      | [4d399918f0](https://linux-hardware.org/?probe=4d399918f0) | Dec 20, 2021 |
| HONOR         | BMH-WCX9                    | [46395a1450](https://linux-hardware.org/?probe=46395a1450) | Dec 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0642db16f6](https://linux-hardware.org/?probe=0642db16f6) | Dec 19, 2021 |
| MSI           | GL63 9SC                    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK NH532              | [84be255271](https://linux-hardware.org/?probe=84be255271) | Dec 15, 2021 |
| HP            | ProBook 450 G4              | [0573beab82](https://linux-hardware.org/?probe=0573beab82) | Dec 15, 2021 |
| BenQ          | Joybook R56                 | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [610d56a10a](https://linux-hardware.org/?probe=610d56a10a) | Dec 08, 2021 |
| HP            | Pavilion TS 11              | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| LG Electro... | R510                        | [13f4496897](https://linux-hardware.org/?probe=13f4496897) | Nov 28, 2021 |
| ASUSTek       | 1000HE                      | [5923c0d7e3](https://linux-hardware.org/?probe=5923c0d7e3) | Nov 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [c420169ce7](https://linux-hardware.org/?probe=c420169ce7) | Nov 25, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6eca4a1be2](https://linux-hardware.org/?probe=6eca4a1be2) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470p 20J7S06Q0... | [6c92c6ecbb](https://linux-hardware.org/?probe=6c92c6ecbb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [53e26c9677](https://linux-hardware.org/?probe=53e26c9677) | Nov 22, 2021 |
| HP            | EliteBook 850 G6            | [488cdb831c](https://linux-hardware.org/?probe=488cdb831c) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1784f93056](https://linux-hardware.org/?probe=1784f93056) | Nov 18, 2021 |
| HP            | Laptop 15s-eq2xxx           | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| ASUSTek       | UX31A                       | [696ee320dd](https://linux-hardware.org/?probe=696ee320dd) | Nov 11, 2021 |
| Acer          | Aspire 5750G                | [e290db920f](https://linux-hardware.org/?probe=e290db920f) | Nov 08, 2021 |
| HP            | ProBook 455 G1              | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| HP            | Laptop 15s-eq2xxx           | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2ba5ae42bb](https://linux-hardware.org/?probe=2ba5ae42bb) | Oct 31, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [a56c0a6b4d](https://linux-hardware.org/?probe=a56c0a6b4d) | Oct 26, 2021 |
| Samsung       | R508                        | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| HP            | Notebook                    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [4bc3faf49f](https://linux-hardware.org/?probe=4bc3faf49f) | Oct 24, 2021 |
| ASUSTek       | K53BR                       | [af980dc491](https://linux-hardware.org/?probe=af980dc491) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N2000KRT    | [55daad7a3a](https://linux-hardware.org/?probe=55daad7a3a) | Oct 17, 2021 |
| Lenovo        | S10-3                       | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Lenovo        | S10-3                       | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f874da9f03](https://linux-hardware.org/?probe=f874da9f03) | Oct 12, 2021 |
| Acer          | Aspire A515-44G             | [264badf289](https://linux-hardware.org/?probe=264badf289) | Oct 01, 2021 |
| HP            | Pavilion dv4000 (PX306UA... | [fdc2b74a29](https://linux-hardware.org/?probe=fdc2b74a29) | Oct 01, 2021 |
| Lenovo        | ThinkPad T480s 20L8SB9Y0... | [75356ac5ee](https://linux-hardware.org/?probe=75356ac5ee) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e5838666c2](https://linux-hardware.org/?probe=e5838666c2) | Oct 01, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b69288527f](https://linux-hardware.org/?probe=b69288527f) | Oct 01, 2021 |
| HP            | Laptop 15s-eq2xxx           | [49a6459ecf](https://linux-hardware.org/?probe=49a6459ecf) | Sep 23, 2021 |
| HONOR         | HLYL-WXX9                   | [f21200b164](https://linux-hardware.org/?probe=f21200b164) | Sep 23, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9cf1061bcb](https://linux-hardware.org/?probe=9cf1061bcb) | Sep 19, 2021 |
| HP            | Laptop 15s-eq2xxx           | [84678f812f](https://linux-hardware.org/?probe=84678f812f) | Sep 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [a64387b07d](https://linux-hardware.org/?probe=a64387b07d) | Sep 15, 2021 |
| ASUSTek       | K50IJ                       | [01cd639b37](https://linux-hardware.org/?probe=01cd639b37) | Sep 11, 2021 |
| HP            | ProBook 4515s               | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [248b63572e](https://linux-hardware.org/?probe=248b63572e) | Sep 08, 2021 |
| Samsung       | R508                        | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| HP            | Compaq 610                  | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [11fce4275a](https://linux-hardware.org/?probe=11fce4275a) | Sep 01, 2021 |
| ASUSTek       | K53BR                       | [989a6f27be](https://linux-hardware.org/?probe=989a6f27be) | Aug 29, 2021 |
| Acer          | Extensa 2511G               | [d74e3d1835](https://linux-hardware.org/?probe=d74e3d1835) | Aug 22, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6bcc5abfa7](https://linux-hardware.org/?probe=6bcc5abfa7) | Aug 18, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [735e9cba22](https://linux-hardware.org/?probe=735e9cba22) | Aug 18, 2021 |
| Samsung       | R59P/R60P/R61P              | [21914d4123](https://linux-hardware.org/?probe=21914d4123) | Aug 11, 2021 |
| HP            | ProBook 470 G0              | [52a8d13536](https://linux-hardware.org/?probe=52a8d13536) | Aug 08, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| MSI           | GF63 Thin 9SCSR             | [0fac51313a](https://linux-hardware.org/?probe=0fac51313a) | Aug 06, 2021 |
| Lenovo        | Z50-70 20354                | [94d76843e6](https://linux-hardware.org/?probe=94d76843e6) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EQS33800     | [2e1468bf31](https://linux-hardware.org/?probe=2e1468bf31) | Aug 02, 2021 |
| HP            | ProBook 450 G2              | [dbba9b9771](https://linux-hardware.org/?probe=dbba9b9771) | Jul 30, 2021 |
| HP            | ProBook 450 G2              | [6d45e5794a](https://linux-hardware.org/?probe=6d45e5794a) | Jul 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [c90b5a2e7d](https://linux-hardware.org/?probe=c90b5a2e7d) | Jul 28, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| Prestigio     | PSB141C03                   | [60fe58fa1b](https://linux-hardware.org/?probe=60fe58fa1b) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | [3006193ccc](https://linux-hardware.org/?probe=3006193ccc) | Jul 22, 2021 |
| HP            | Laptop 15-bs0xx             | [ab8b0d224b](https://linux-hardware.org/?probe=ab8b0d224b) | Jul 16, 2021 |
| Acer          | Nitro AN515-54              | [30dd6fa596](https://linux-hardware.org/?probe=30dd6fa596) | Jul 14, 2021 |
| Acer          | Nitro AN515-52              | [ce3b5ecb17](https://linux-hardware.org/?probe=ce3b5ecb17) | Jul 13, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [a9b1ac4bdb](https://linux-hardware.org/?probe=a9b1ac4bdb) | Jul 07, 2021 |
| Dell          | XPS 15 9500                 | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Sony          | SVE1512N1RW                 | [9cfa353121](https://linux-hardware.org/?probe=9cfa353121) | Jul 05, 2021 |
| Samsung       | RV415/RV515/E3415           | [09ee8c08c7](https://linux-hardware.org/?probe=09ee8c08c7) | Jul 05, 2021 |
| HP            | EliteBook 840 G2            | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| HP            | Laptop 15s-eq2xxx           | [8dd431f915](https://linux-hardware.org/?probe=8dd431f915) | Jul 03, 2021 |
| Samsung       | RV413/RV513                 | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | [48f732d759](https://linux-hardware.org/?probe=48f732d759) | Jun 23, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Acer          | Aspire E5-572G              | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [ec0c189e56](https://linux-hardware.org/?probe=ec0c189e56) | Jun 15, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [8380ef5fcb](https://linux-hardware.org/?probe=8380ef5fcb) | Jun 11, 2021 |
| Acer          | Aspire A515-51G             | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| HP            | Pavilion 15                 | [8c0f52c64d](https://linux-hardware.org/?probe=8c0f52c64d) | Jun 08, 2021 |
| HP            | Laptop 15-bs0xx             | [5e75af2ba4](https://linux-hardware.org/?probe=5e75af2ba4) | May 31, 2021 |
| Samsung       | RV411/RV511/E3511/S3511     | [8bdfad6e5a](https://linux-hardware.org/?probe=8bdfad6e5a) | May 27, 2021 |
| HP            | Laptop 15-bs0xx             | [8e85b5f3cf](https://linux-hardware.org/?probe=8e85b5f3cf) | May 26, 2021 |
| HP            | Laptop 15-bs0xx             | [8ffe17b548](https://linux-hardware.org/?probe=8ffe17b548) | May 24, 2021 |
| ASUSTek       | X541UJ                      | [22f4d0228f](https://linux-hardware.org/?probe=22f4d0228f) | May 16, 2021 |
| Timi          | TM1703                      | [a8c47ad7f6](https://linux-hardware.org/?probe=a8c47ad7f6) | May 15, 2021 |
| Lenovo        | Z710 20250                  | [f3d7663214](https://linux-hardware.org/?probe=f3d7663214) | May 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [06af60abdc](https://linux-hardware.org/?probe=06af60abdc) | May 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [b71c62e752](https://linux-hardware.org/?probe=b71c62e752) | May 09, 2021 |
| Lenovo        | Z50-70 20354                | [06558373ef](https://linux-hardware.org/?probe=06558373ef) | May 07, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [46872b4b26](https://linux-hardware.org/?probe=46872b4b26) | May 02, 2021 |
| HP            | ProBook 4525s               | [809516ad9a](https://linux-hardware.org/?probe=809516ad9a) | May 01, 2021 |
| Acer          | Aspire A315-21              | [fb5b8d0021](https://linux-hardware.org/?probe=fb5b8d0021) | Apr 29, 2021 |
| Acer          | Aspire A315-21              | [7ec9efef18](https://linux-hardware.org/?probe=7ec9efef18) | Apr 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [3f2270faad](https://linux-hardware.org/?probe=3f2270faad) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [644dd10952](https://linux-hardware.org/?probe=644dd10952) | Apr 22, 2021 |
| HP            | ProBook 450 G7              | [1832412dab](https://linux-hardware.org/?probe=1832412dab) | Apr 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b60d916c33](https://linux-hardware.org/?probe=b60d916c33) | Apr 19, 2021 |
| Lenovo        | G580 20157                  | [1e11286470](https://linux-hardware.org/?probe=1e11286470) | Apr 15, 2021 |
| HP            | ProBook 445 G6              | [520083c016](https://linux-hardware.org/?probe=520083c016) | Apr 14, 2021 |
| ASUSTek       | X541NA                      | [15bd22b48d](https://linux-hardware.org/?probe=15bd22b48d) | Apr 11, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8de936a2ca](https://linux-hardware.org/?probe=8de936a2ca) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ebd6174247](https://linux-hardware.org/?probe=ebd6174247) | Apr 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [0362943e9e](https://linux-hardware.org/?probe=0362943e9e) | Apr 02, 2021 |
| Lenovo        | ThinkPad X230 23252QG       | [a3e8c4ecb4](https://linux-hardware.org/?probe=a3e8c4ecb4) | Mar 31, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [3228126df8](https://linux-hardware.org/?probe=3228126df8) | Mar 29, 2021 |
| Lenovo        | ThinkPad T420 4236GH6       | [102d74838a](https://linux-hardware.org/?probe=102d74838a) | Mar 25, 2021 |
| HP            | ProBook 4525s               | [e4df2fd0b0](https://linux-hardware.org/?probe=e4df2fd0b0) | Mar 24, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [02a403c967](https://linux-hardware.org/?probe=02a403c967) | Mar 24, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | [3157cd3bfe](https://linux-hardware.org/?probe=3157cd3bfe) | Mar 23, 2021 |
| Lenovo        | ThinkPad T61 7661ZM5        | [97df6a4a9a](https://linux-hardware.org/?probe=97df6a4a9a) | Mar 23, 2021 |
| ASUSTek       | UX31A                       | [c6506a0289](https://linux-hardware.org/?probe=c6506a0289) | Mar 21, 2021 |
| Lenovo        | B50-30 20382                | [18d693f712](https://linux-hardware.org/?probe=18d693f712) | Mar 21, 2021 |
| ASUSTek       | N752VX                      | [48cb617015](https://linux-hardware.org/?probe=48cb617015) | Mar 20, 2021 |
| Acer          | Aspire 5551G                | [1002c3efd0](https://linux-hardware.org/?probe=1002c3efd0) | Mar 19, 2021 |
| Acer          | Aspire E5-572G              | [c63de512e5](https://linux-hardware.org/?probe=c63de512e5) | Mar 18, 2021 |
| HP            | 250 G1                      | [7b14b4e7e5](https://linux-hardware.org/?probe=7b14b4e7e5) | Mar 18, 2021 |
| HP            | ProBook 4525s               | [f9830feb98](https://linux-hardware.org/?probe=f9830feb98) | Mar 17, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [d2dde464de](https://linux-hardware.org/?probe=d2dde464de) | Mar 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [12eebe7515](https://linux-hardware.org/?probe=12eebe7515) | Mar 17, 2021 |
| Prestigio     | PSB141C03                   | [82f601055a](https://linux-hardware.org/?probe=82f601055a) | Mar 17, 2021 |
| Acer          | Aspire E5-572G              | [863c6c5d68](https://linux-hardware.org/?probe=863c6c5d68) | Mar 17, 2021 |
| Lenovo        | B50-30 20382                | [51bf91aae7](https://linux-hardware.org/?probe=51bf91aae7) | Mar 14, 2021 |
| HP            | Mini 210-4000               | [9301f9c8ef](https://linux-hardware.org/?probe=9301f9c8ef) | Mar 12, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [83f50b266f](https://linux-hardware.org/?probe=83f50b266f) | Mar 11, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [ed293423f3](https://linux-hardware.org/?probe=ed293423f3) | Mar 11, 2021 |
| HP            | ProBook 4525s               | [912c2f075f](https://linux-hardware.org/?probe=912c2f075f) | Mar 09, 2021 |
| ASUSTek       | X550CC                      | [f63d1b8f0b](https://linux-hardware.org/?probe=f63d1b8f0b) | Mar 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [28a8889148](https://linux-hardware.org/?probe=28a8889148) | Mar 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1df473b11e](https://linux-hardware.org/?probe=1df473b11e) | Mar 03, 2021 |
| Dell          | System XPS L702X            | [1cce147fd2](https://linux-hardware.org/?probe=1cce147fd2) | Feb 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [902d3d474e](https://linux-hardware.org/?probe=902d3d474e) | Feb 25, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [390003cc95](https://linux-hardware.org/?probe=390003cc95) | Feb 24, 2021 |
| ASUSTek       | K50C                        | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD00A... | [0f4f85b4c1](https://linux-hardware.org/?probe=0f4f85b4c1) | Feb 19, 2021 |
| Packard Be... | EasyNote TM86               | [f548aa653a](https://linux-hardware.org/?probe=f548aa653a) | Feb 18, 2021 |
| Acer          | Extensa 5230                | [b128a06266](https://linux-hardware.org/?probe=b128a06266) | Feb 17, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [1a52fb16f9](https://linux-hardware.org/?probe=1a52fb16f9) | Feb 16, 2021 |
| Dell          | Inspiron 5748               | [8bb7ec1035](https://linux-hardware.org/?probe=8bb7ec1035) | Feb 15, 2021 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [c5877ecd52](https://linux-hardware.org/?probe=c5877ecd52) | Feb 14, 2021 |
| ASUSTek       | X540NV                      | [3a64cfa43e](https://linux-hardware.org/?probe=3a64cfa43e) | Feb 13, 2021 |
| HP            | Mini 210-4000               | [966136f01f](https://linux-hardware.org/?probe=966136f01f) | Feb 13, 2021 |
| ASUSTek       | X540NV                      | [2e31ed1ec6](https://linux-hardware.org/?probe=2e31ed1ec6) | Feb 13, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8f8fd2975a](https://linux-hardware.org/?probe=8f8fd2975a) | Feb 13, 2021 |
| Unknown       | Unknown                     | [440af1645f](https://linux-hardware.org/?probe=440af1645f) | Feb 13, 2021 |
| Acer          | Extensa 7630EZ              | [9a0378eb4d](https://linux-hardware.org/?probe=9a0378eb4d) | Feb 11, 2021 |
| Acer          | TravelMate 5760             | [bbd0961627](https://linux-hardware.org/?probe=bbd0961627) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [6487d4bd7c](https://linux-hardware.org/?probe=6487d4bd7c) | Feb 09, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8c35b025b2](https://linux-hardware.org/?probe=8c35b025b2) | Feb 08, 2021 |
| HP            | Laptop 15-dw2xxx            | [cbd3e60242](https://linux-hardware.org/?probe=cbd3e60242) | Feb 07, 2021 |
| HP            | 635                         | [e83d58e706](https://linux-hardware.org/?probe=e83d58e706) | Feb 03, 2021 |
| Acer          | Aspire 5551G                | [811535132b](https://linux-hardware.org/?probe=811535132b) | Feb 02, 2021 |
| Acer          | Aspire A315-21              | [e86c3d781d](https://linux-hardware.org/?probe=e86c3d781d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T410 2537V28       | [126c75190e](https://linux-hardware.org/?probe=126c75190e) | Jan 22, 2021 |
| Lenovo        | G580 20157                  | [e04d0e066e](https://linux-hardware.org/?probe=e04d0e066e) | Jan 22, 2021 |
| HP            | 255 G2                      | [3ebc0a9b9b](https://linux-hardware.org/?probe=3ebc0a9b9b) | Jan 21, 2021 |
| Lenovo        | G50-30 80G0                 | [48644938e9](https://linux-hardware.org/?probe=48644938e9) | Jan 17, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [b3bfbdace0](https://linux-hardware.org/?probe=b3bfbdace0) | Jan 10, 2021 |
| ASUSTek       | N550JK                      | [f12a646f8b](https://linux-hardware.org/?probe=f12a646f8b) | Jan 09, 2021 |
| Acer          | Extensa 2511G               | [ca3628282a](https://linux-hardware.org/?probe=ca3628282a) | Jan 06, 2021 |
| HP            | Mini 5102                   | [76f0b2193f](https://linux-hardware.org/?probe=76f0b2193f) | Jan 06, 2021 |
| HP            | Laptop 15-db1xxx            | [76f271acf1](https://linux-hardware.org/?probe=76f271acf1) | Jan 04, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b005d0780d](https://linux-hardware.org/?probe=b005d0780d) | Jan 04, 2021 |
| Samsung       | SR58P                       | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [f49ba1df9c](https://linux-hardware.org/?probe=f49ba1df9c) | Jan 01, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [997fd6a726](https://linux-hardware.org/?probe=997fd6a726) | Dec 30, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | [8eb79a3a10](https://linux-hardware.org/?probe=8eb79a3a10) | Dec 29, 2020 |
| Lenovo        | G580 20157                  | [f4ae75d77c](https://linux-hardware.org/?probe=f4ae75d77c) | Dec 16, 2020 |
| Dell          | Inspiron 5748               | [091c74353b](https://linux-hardware.org/?probe=091c74353b) | Dec 16, 2020 |
| Lenovo        | B5400 20278                 | [56ea17c80b](https://linux-hardware.org/?probe=56ea17c80b) | Dec 15, 2020 |
| Lenovo        | G580 20157                  | [b987e4cc7c](https://linux-hardware.org/?probe=b987e4cc7c) | Dec 11, 2020 |
| Lenovo        | G580 20157                  | [f6e40ea1a0](https://linux-hardware.org/?probe=f6e40ea1a0) | Dec 11, 2020 |
| Samsung       | R530/R730                   | [eaf1fed190](https://linux-hardware.org/?probe=eaf1fed190) | Dec 11, 2020 |
| Lenovo        | G50-30 80G0                 | [d0d9126db4](https://linux-hardware.org/?probe=d0d9126db4) | Dec 08, 2020 |
| Prestigio     | PSB141C03                   | [4087902d18](https://linux-hardware.org/?probe=4087902d18) | Dec 07, 2020 |
| Lenovo        | G50-30 80G0                 | [a566f76ca4](https://linux-hardware.org/?probe=a566f76ca4) | Dec 07, 2020 |
| Acer          | Aspire E1-532               | [27a4e636f6](https://linux-hardware.org/?probe=27a4e636f6) | Dec 02, 2020 |
| ASUSTek       | Strix GL703GM_GL703GM       | [54886a9cc0](https://linux-hardware.org/?probe=54886a9cc0) | Nov 29, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [91ff5fdd53](https://linux-hardware.org/?probe=91ff5fdd53) | Nov 28, 2020 |
| ASUSTek       | K52N                        | [94f1b7362b](https://linux-hardware.org/?probe=94f1b7362b) | Nov 25, 2020 |
| Acer          | Aspire E1-530               | [e343493113](https://linux-hardware.org/?probe=e343493113) | Nov 25, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | [b265ff82a7](https://linux-hardware.org/?probe=b265ff82a7) | Nov 21, 2020 |
| Lenovo        | ThinkPad E15 20RD0014RT     | [81de71766f](https://linux-hardware.org/?probe=81de71766f) | Nov 21, 2020 |
| Prestigio     | PSB141C02                   | [08aa1ee2ff](https://linux-hardware.org/?probe=08aa1ee2ff) | Nov 20, 2020 |
| ASUSTek       | X541UAK                     | [bada67f585](https://linux-hardware.org/?probe=bada67f585) | Nov 20, 2020 |
| Lenovo        | G50-30 80G0                 | [9687208571](https://linux-hardware.org/?probe=9687208571) | Nov 19, 2020 |
| ASUSTek       | X541UAK                     | [c914110be9](https://linux-hardware.org/?probe=c914110be9) | Nov 19, 2020 |
| Acer          | Aspire E1-532G              | [dd90b2f3e2](https://linux-hardware.org/?probe=dd90b2f3e2) | Nov 18, 2020 |
| Samsung       | R508                        | [937a0199e0](https://linux-hardware.org/?probe=937a0199e0) | Nov 16, 2020 |
| ASUSTek       | K52N                        | [a96cd62a24](https://linux-hardware.org/?probe=a96cd62a24) | Nov 14, 2020 |
| HP            | EliteBook 850 G5            | [225c61e941](https://linux-hardware.org/?probe=225c61e941) | Nov 13, 2020 |
| Dell          | Inspiron 5521               | [1080310f19](https://linux-hardware.org/?probe=1080310f19) | Nov 11, 2020 |
| Intel         | SharkBay Platform           | [21647cb222](https://linux-hardware.org/?probe=21647cb222) | Nov 09, 2020 |
| Unknown       | Unknown                     | [091af6961a](https://linux-hardware.org/?probe=091af6961a) | Nov 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [5da1ec78a0](https://linux-hardware.org/?probe=5da1ec78a0) | Nov 07, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | [412e6eca38](https://linux-hardware.org/?probe=412e6eca38) | Nov 05, 2020 |
| Lenovo        | ThinkPad T61 7663BL3        | [6fb42db6e5](https://linux-hardware.org/?probe=6fb42db6e5) | Nov 05, 2020 |
| Intel         | SharkBay Platform           | [dcd49fdf3b](https://linux-hardware.org/?probe=dcd49fdf3b) | Nov 04, 2020 |
| Samsung       | R508                        | [7915a99545](https://linux-hardware.org/?probe=7915a99545) | Nov 03, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [45666ff7af](https://linux-hardware.org/?probe=45666ff7af) | Nov 01, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [830c1ed47a](https://linux-hardware.org/?probe=830c1ed47a) | Nov 01, 2020 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f5328a95d5](https://linux-hardware.org/?probe=f5328a95d5) | Oct 31, 2020 |
| Dell          | Inspiron 15 5501            | [557aca340e](https://linux-hardware.org/?probe=557aca340e) | Oct 27, 2020 |
| Timi          | TM1701                      | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Dell          | Inspiron 15 5501            | [92fa11d82d](https://linux-hardware.org/?probe=92fa11d82d) | Oct 25, 2020 |
| Dell          | Inspiron 15 5501            | [6a18afe215](https://linux-hardware.org/?probe=6a18afe215) | Oct 25, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b0e3f9ed28](https://linux-hardware.org/?probe=b0e3f9ed28) | Oct 21, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [f21f5a008c](https://linux-hardware.org/?probe=f21f5a008c) | Oct 21, 2020 |
| HP            | 250 G2                      | [164b391add](https://linux-hardware.org/?probe=164b391add) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | [50cb6d53ef](https://linux-hardware.org/?probe=50cb6d53ef) | Oct 18, 2020 |
| Dell          | Inspiron 7577               | [0e1b75fc55](https://linux-hardware.org/?probe=0e1b75fc55) | Oct 18, 2020 |
| Acer          | Unknown                     | [5dc51268a1](https://linux-hardware.org/?probe=5dc51268a1) | Oct 17, 2020 |
| Prestigio     | PSB141C03                   | [eb6b709b25](https://linux-hardware.org/?probe=eb6b709b25) | Oct 12, 2020 |
| Lenovo        | ThinkPad T400 7417CTO       | [41f5d8bbb1](https://linux-hardware.org/?probe=41f5d8bbb1) | Oct 12, 2020 |
| Lenovo        | V145-15AST 81MT             | [479a1ad655](https://linux-hardware.org/?probe=479a1ad655) | Oct 11, 2020 |
| HP            | Laptop 15-bs0xx             | [eefad2dd0f](https://linux-hardware.org/?probe=eefad2dd0f) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [1d6ca8e5fc](https://linux-hardware.org/?probe=1d6ca8e5fc) | Oct 09, 2020 |
| HP            | Laptop 15-bs0xx             | [b0244dd7f4](https://linux-hardware.org/?probe=b0244dd7f4) | Oct 08, 2020 |
| Dell          | G5 5587                     | [7ec299e574](https://linux-hardware.org/?probe=7ec299e574) | Oct 03, 2020 |
| Acer          | Aspire A515-51G             | [4308201e9f](https://linux-hardware.org/?probe=4308201e9f) | Sep 28, 2020 |
| Samsung       | R518                        | [c4db2214cd](https://linux-hardware.org/?probe=c4db2214cd) | Sep 27, 2020 |
| Timi          | TM1709                      | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| HP            | 250 G2                      | [0721c128e6](https://linux-hardware.org/?probe=0721c128e6) | Sep 22, 2020 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [586f647e41](https://linux-hardware.org/?probe=586f647e41) | Sep 13, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [41ed89087e](https://linux-hardware.org/?probe=41ed89087e) | Aug 31, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ed88384ae9](https://linux-hardware.org/?probe=ed88384ae9) | Aug 31, 2020 |
| MSI           | PS42 Modern 8RA             | [ab71a04043](https://linux-hardware.org/?probe=ab71a04043) | Aug 29, 2020 |
| HP            | Laptop 15-bs0xx             | [22adb53a27](https://linux-hardware.org/?probe=22adb53a27) | Aug 29, 2020 |
| Dell          | Precision 7540              | [8e97d27134](https://linux-hardware.org/?probe=8e97d27134) | Aug 27, 2020 |
| ASUSTek       | U36SG                       | [103ce98981](https://linux-hardware.org/?probe=103ce98981) | Aug 27, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [aaae1d3e78](https://linux-hardware.org/?probe=aaae1d3e78) | Aug 24, 2020 |
| Dell          | Vostro 5490                 | [873e3c07c7](https://linux-hardware.org/?probe=873e3c07c7) | Aug 24, 2020 |
| HP            | Laptop 15-bs0xx             | [a7b737f065](https://linux-hardware.org/?probe=a7b737f065) | Aug 23, 2020 |
| HP            | Laptop 15-bs0xx             | [494bb32560](https://linux-hardware.org/?probe=494bb32560) | Aug 23, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [9c05eb6ed3](https://linux-hardware.org/?probe=9c05eb6ed3) | Aug 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [42cfca7021](https://linux-hardware.org/?probe=42cfca7021) | Aug 14, 2020 |
| Acer          | Aspire 4810T                | [5ff79d2a64](https://linux-hardware.org/?probe=5ff79d2a64) | Aug 09, 2020 |
| Acer          | Aspire V3-571G              | [6ca9ef29fc](https://linux-hardware.org/?probe=6ca9ef29fc) | Aug 02, 2020 |
| HP            | 250 G6 Notebook PC          | [9b0eb8f018](https://linux-hardware.org/?probe=9b0eb8f018) | Aug 01, 2020 |
| Timi          | TM1701                      | [71882c9121](https://linux-hardware.org/?probe=71882c9121) | Jul 31, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [d38b29e9f6](https://linux-hardware.org/?probe=d38b29e9f6) | Jul 29, 2020 |
| Timi          | TM1701                      | [024ed71324](https://linux-hardware.org/?probe=024ed71324) | Jul 22, 2020 |
| Acer          | Aspire E1-731               | [e055f89ff6](https://linux-hardware.org/?probe=e055f89ff6) | Jul 15, 2020 |
| HP            | ProBook 450 G5              | [acd59fc735](https://linux-hardware.org/?probe=acd59fc735) | Jul 15, 2020 |
| HP            | ProBook 440 G5              | [744a29218a](https://linux-hardware.org/?probe=744a29218a) | Jul 09, 2020 |
| HP            | ProBook 445 G6              | [e82b679ba1](https://linux-hardware.org/?probe=e82b679ba1) | Jul 05, 2020 |
| eMachines     | eME728                      | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| ASUSTek       | X705UQR                     | [caebcd4a78](https://linux-hardware.org/?probe=caebcd4a78) | Jul 03, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | [a6dcbcadc4](https://linux-hardware.org/?probe=a6dcbcadc4) | Jun 30, 2020 |
| Samsung       | RV411/RV511/E3511/S3511     | [df5777de6d](https://linux-hardware.org/?probe=df5777de6d) | Jun 29, 2020 |
| LG Electro... | R510                        | [51967b227c](https://linux-hardware.org/?probe=51967b227c) | Jun 29, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [566a257192](https://linux-hardware.org/?probe=566a257192) | Jun 07, 2020 |
| Dell          | Inspiron 3521               | [59c6b9d06f](https://linux-hardware.org/?probe=59c6b9d06f) | Jun 06, 2020 |
| ASUSTek       | X540NV                      | [f1a595ed8a](https://linux-hardware.org/?probe=f1a595ed8a) | Jun 05, 2020 |
| ASUSTek       | X541UJ                      | [4116c24ad8](https://linux-hardware.org/?probe=4116c24ad8) | Jun 03, 2020 |
| HP            | ProBook 4740s               | [bac1c80c34](https://linux-hardware.org/?probe=bac1c80c34) | Jun 02, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b73508569c](https://linux-hardware.org/?probe=b73508569c) | May 30, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [178a726d73](https://linux-hardware.org/?probe=178a726d73) | May 28, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [dbfbd4b70e](https://linux-hardware.org/?probe=dbfbd4b70e) | May 28, 2020 |
| ASUSTek       | S551LB                      | [4aed54f228](https://linux-hardware.org/?probe=4aed54f228) | May 28, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire VN7-592G             | [aa51c338b2](https://linux-hardware.org/?probe=aa51c338b2) | May 26, 2020 |
| HP            | Notebook                    | [672d0acfa1](https://linux-hardware.org/?probe=672d0acfa1) | May 26, 2020 |
| HP            | Notebook                    | [1fa50923d3](https://linux-hardware.org/?probe=1fa50923d3) | May 26, 2020 |
| Acer          | AOA150                      | [4879ee6a95](https://linux-hardware.org/?probe=4879ee6a95) | May 24, 2020 |
| Prestigio     | Multipad Visconte V         | [d3f3e2e2b4](https://linux-hardware.org/?probe=d3f3e2e2b4) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e82eb79af2](https://linux-hardware.org/?probe=e82eb79af2) | May 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [06d027143f](https://linux-hardware.org/?probe=06d027143f) | May 11, 2020 |
| HP            | ProBook 450 G6              | [ff446033f4](https://linux-hardware.org/?probe=ff446033f4) | May 07, 2020 |
| HP            | ProBook 450 G6              | [fbdced7593](https://linux-hardware.org/?probe=fbdced7593) | Apr 30, 2020 |
| Timi          | TM1613                      | [5f55af6b8d](https://linux-hardware.org/?probe=5f55af6b8d) | Apr 27, 2020 |
| ASUSTek       | N551JM                      | [cd375242d3](https://linux-hardware.org/?probe=cd375242d3) | Apr 15, 2020 |
| Acer          | Aspire A315-42G             | [e050431a72](https://linux-hardware.org/?probe=e050431a72) | Apr 09, 2020 |
| Acer          | Aspire A315-42G             | [13a642b394](https://linux-hardware.org/?probe=13a642b394) | Apr 09, 2020 |
| HP            | ProBook 4710s               | [56f533f0f5](https://linux-hardware.org/?probe=56f533f0f5) | Apr 07, 2020 |
| HP            | Notebook                    | [d32a1f4247](https://linux-hardware.org/?probe=d32a1f4247) | Mar 30, 2020 |
| Acer          | Aspire 4810T                | [b7d82235f8](https://linux-hardware.org/?probe=b7d82235f8) | Mar 22, 2020 |
| Acer          | TravelMate P259-M           | [596bd79c7a](https://linux-hardware.org/?probe=596bd79c7a) | Mar 22, 2020 |
| Lenovo        | ThinkPad T61 7661WPF        | [ce22405483](https://linux-hardware.org/?probe=ce22405483) | Mar 19, 2020 |
| ASUSTek       | K52N                        | [a1fea085d9](https://linux-hardware.org/?probe=a1fea085d9) | Mar 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0e0fa6f7e5](https://linux-hardware.org/?probe=0e0fa6f7e5) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0c7024795f](https://linux-hardware.org/?probe=0c7024795f) | Mar 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [526830e223](https://linux-hardware.org/?probe=526830e223) | Mar 17, 2020 |
| ASUSTek       | X540NV                      | [e37fc99e67](https://linux-hardware.org/?probe=e37fc99e67) | Mar 11, 2020 |
| Lenovo        | G500 20236                  | [efbd3772bc](https://linux-hardware.org/?probe=efbd3772bc) | Mar 09, 2020 |
| ASUSTek       | X540NV                      | [123e49a129](https://linux-hardware.org/?probe=123e49a129) | Mar 07, 2020 |
| Dell          | Inspiron 3576               | [2938ca5aec](https://linux-hardware.org/?probe=2938ca5aec) | Mar 03, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [7c909cb955](https://linux-hardware.org/?probe=7c909cb955) | Mar 01, 2020 |
| Acer          | Extensa 5220                | [3ac52b68ad](https://linux-hardware.org/?probe=3ac52b68ad) | Mar 01, 2020 |
| Dell          | Inspiron 3576               | [c0fb2f48aa](https://linux-hardware.org/?probe=c0fb2f48aa) | Feb 29, 2020 |
| ASUSTek       | X705UQR                     | [a5cca23283](https://linux-hardware.org/?probe=a5cca23283) | Feb 29, 2020 |
| Packard Be... | DOT S                       | [cd2b5a2715](https://linux-hardware.org/?probe=cd2b5a2715) | Feb 28, 2020 |
| Packard Be... | DOT S                       | [8db7395b33](https://linux-hardware.org/?probe=8db7395b33) | Feb 27, 2020 |
| ASUSTek       | K53SV                       | [9192ccbb93](https://linux-hardware.org/?probe=9192ccbb93) | Feb 26, 2020 |
| Timi          | TM1701                      | [4185035b5f](https://linux-hardware.org/?probe=4185035b5f) | Feb 26, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [619c9af84e](https://linux-hardware.org/?probe=619c9af84e) | Feb 25, 2020 |
| HP            | Pavilion g6                 | [4e0759261c](https://linux-hardware.org/?probe=4e0759261c) | Feb 24, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8e0229807b](https://linux-hardware.org/?probe=8e0229807b) | Feb 24, 2020 |
| Acer          | Aspire V3-571G              | [dda987c8c9](https://linux-hardware.org/?probe=dda987c8c9) | Feb 24, 2020 |
| Acer          | Aspire E1-571G              | [9951bcb215](https://linux-hardware.org/?probe=9951bcb215) | Feb 23, 2020 |
| Packard Be... | DOT S                       | [ef2c3a6924](https://linux-hardware.org/?probe=ef2c3a6924) | Feb 19, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3f3185269f](https://linux-hardware.org/?probe=3f3185269f) | Feb 18, 2020 |
| ASUSTek       | K70AE                       | [1c9b37e0bf](https://linux-hardware.org/?probe=1c9b37e0bf) | Feb 12, 2020 |
| Acer          | Aspire V3-571G              | [8d3edd49c5](https://linux-hardware.org/?probe=8d3edd49c5) | Feb 11, 2020 |
| Dell          | System XPS L702X            | [17383a48fc](https://linux-hardware.org/?probe=17383a48fc) | Feb 06, 2020 |
| Lenovo        | ThinkPad T470 20HD005QRT    | [1864afd83f](https://linux-hardware.org/?probe=1864afd83f) | Feb 03, 2020 |
| ASUSTek       | X705UQR                     | [8b15a6370b](https://linux-hardware.org/?probe=8b15a6370b) | Feb 01, 2020 |
| Acer          | Aspire V5-561G              | [a646ea611f](https://linux-hardware.org/?probe=a646ea611f) | Jan 29, 2020 |
| Samsung       | 305E4Z/305E5Z/305E7Z        | [cd7471d773](https://linux-hardware.org/?probe=cd7471d773) | Jan 25, 2020 |
| Dell          | XPS 15 9570                 | [c97d5c5a5e](https://linux-hardware.org/?probe=c97d5c5a5e) | Jan 24, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [485f1149df](https://linux-hardware.org/?probe=485f1149df) | Jan 20, 2020 |
| ASUSTek       | X705UQR                     | [87c3bdc009](https://linux-hardware.org/?probe=87c3bdc009) | Jan 19, 2020 |
| ASUSTek       | X705UQR                     | [bc34d4d0e9](https://linux-hardware.org/?probe=bc34d4d0e9) | Jan 19, 2020 |
| ASUSTek       | UL30A                       | [f9f8ddf425](https://linux-hardware.org/?probe=f9f8ddf425) | Jan 14, 2020 |
| ASUSTek       | X540SA                      | [22047ce8bb](https://linux-hardware.org/?probe=22047ce8bb) | Jan 11, 2020 |
| HP            | Unknown                     | [7845d03a39](https://linux-hardware.org/?probe=7845d03a39) | Jan 11, 2020 |
| HP            | ProBook 455 G1              | [08dcbaa82a](https://linux-hardware.org/?probe=08dcbaa82a) | Jan 02, 2020 |
| HP            | ProBook 4530s               | [48ca791cd2](https://linux-hardware.org/?probe=48ca791cd2) | Jan 02, 2020 |
| Samsung       | R519/R719                   | [1a0ac991d0](https://linux-hardware.org/?probe=1a0ac991d0) | Jan 01, 2020 |
| ASUSTek       | K53Z                        | [51da8ec92c](https://linux-hardware.org/?probe=51da8ec92c) | Jan 01, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [54845cd095](https://linux-hardware.org/?probe=54845cd095) | Dec 29, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [e96c98384b](https://linux-hardware.org/?probe=e96c98384b) | Dec 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [9f38052441](https://linux-hardware.org/?probe=9f38052441) | Dec 28, 2019 |
| Toshiba       | Satellite L850D-BJS         | [c77563a5fb](https://linux-hardware.org/?probe=c77563a5fb) | Dec 23, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | [57160cc915](https://linux-hardware.org/?probe=57160cc915) | Dec 16, 2019 |
| Samsung       | R508                        | [f2d52e0253](https://linux-hardware.org/?probe=f2d52e0253) | Dec 12, 2019 |
| ASUSTek       | X540NV                      | [e1396088af](https://linux-hardware.org/?probe=e1396088af) | Dec 11, 2019 |
| ASUSTek       | X540NV                      | [0649347201](https://linux-hardware.org/?probe=0649347201) | Dec 11, 2019 |
| Lenovo        | G50-30 80G0                 | [c6838b1dba](https://linux-hardware.org/?probe=c6838b1dba) | Dec 11, 2019 |
| Packard Be... | DOT S                       | [5bd4609615](https://linux-hardware.org/?probe=5bd4609615) | Dec 09, 2019 |
| HP            | Pavilion 17                 | [e5c53c61e8](https://linux-hardware.org/?probe=e5c53c61e8) | Dec 08, 2019 |
| Lenovo        | ThinkPad SL510 2875RS2      | [4b5548d0bb](https://linux-hardware.org/?probe=4b5548d0bb) | Dec 05, 2019 |
| Dell          | G3 3579                     | [c4fe97cca2](https://linux-hardware.org/?probe=c4fe97cca2) | Dec 04, 2019 |
| Dell          | G3 3579                     | [ada421696a](https://linux-hardware.org/?probe=ada421696a) | Dec 04, 2019 |
| HP            | Pavilion 15                 | [03188ddfb3](https://linux-hardware.org/?probe=03188ddfb3) | Dec 03, 2019 |
| Dell          | Inspiron 5559               | [5a4aaf46f2](https://linux-hardware.org/?probe=5a4aaf46f2) | Dec 02, 2019 |
| HP            | ProBook 450 G5              | [9441c13ce5](https://linux-hardware.org/?probe=9441c13ce5) | Dec 02, 2019 |
| MSI           | GP72 7RDX                   | [445ae9719a](https://linux-hardware.org/?probe=445ae9719a) | Dec 02, 2019 |
| Dell          | Latitude E5450              | [9d71909e26](https://linux-hardware.org/?probe=9d71909e26) | Dec 02, 2019 |
| Lenovo        | G50-30 80G0                 | [320dde739d](https://linux-hardware.org/?probe=320dde739d) | Nov 27, 2019 |
| Acer          | Aspire E1-530               | [47bc99ddc7](https://linux-hardware.org/?probe=47bc99ddc7) | Nov 27, 2019 |
| Acer          | Aspire E1-532               | [ecb10a3db1](https://linux-hardware.org/?probe=ecb10a3db1) | Nov 27, 2019 |
| Lenovo        | G50-30 80G0                 | [3baee5b588](https://linux-hardware.org/?probe=3baee5b588) | Nov 26, 2019 |
| Acer          | Aspire E1-530               | [e6b4056c8c](https://linux-hardware.org/?probe=e6b4056c8c) | Nov 26, 2019 |
| Toshiba       | SATEGO X200                 | [087c0e291d](https://linux-hardware.org/?probe=087c0e291d) | Nov 25, 2019 |
| Packard Be... | EasyNote TK36               | [b85f41a113](https://linux-hardware.org/?probe=b85f41a113) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | [5ded5e4dc0](https://linux-hardware.org/?probe=5ded5e4dc0) | Nov 24, 2019 |
| Packard Be... | EasyNote TK36               | [b0e6d88437](https://linux-hardware.org/?probe=b0e6d88437) | Nov 23, 2019 |
| Packard Be... | EasyNote TK36               | [f86cacb590](https://linux-hardware.org/?probe=f86cacb590) | Nov 23, 2019 |
| Lenovo        | S20-30 20421                | [969154a207](https://linux-hardware.org/?probe=969154a207) | Nov 21, 2019 |
| Lenovo        | S20-30 20421                | [d2625b22e1](https://linux-hardware.org/?probe=d2625b22e1) | Nov 19, 2019 |
| HP            | Pavilion 15                 | [ae59f09d06](https://linux-hardware.org/?probe=ae59f09d06) | Nov 19, 2019 |
| Lenovo        | ThinkPad T470 20HD005QRT    | [403acf7be3](https://linux-hardware.org/?probe=403acf7be3) | Nov 16, 2019 |
| ASUSTek       | X541UAK                     | [a765714f02](https://linux-hardware.org/?probe=a765714f02) | Nov 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [292caf76d2](https://linux-hardware.org/?probe=292caf76d2) | Nov 01, 2019 |
| Samsung       | RV408/RV508                 | [e4e8ab57d3](https://linux-hardware.org/?probe=e4e8ab57d3) | Oct 31, 2019 |
| Lenovo        | B50-30 20382                | [c21f8427bb](https://linux-hardware.org/?probe=c21f8427bb) | Oct 31, 2019 |
| BenQ          | JoyBook A53                 | [244ee24b1d](https://linux-hardware.org/?probe=244ee24b1d) | Oct 30, 2019 |
| Dream Mach... | N8xEJEK                     | [7d9991c02f](https://linux-hardware.org/?probe=7d9991c02f) | Oct 30, 2019 |
| MSI           | PS63 Modern 8M              | [3442120f57](https://linux-hardware.org/?probe=3442120f57) | Oct 29, 2019 |
| Samsung       | R528/R728                   | [72819f11a2](https://linux-hardware.org/?probe=72819f11a2) | Oct 26, 2019 |
| ASUSTek       | N550JV                      | [091b2a9dda](https://linux-hardware.org/?probe=091b2a9dda) | Oct 22, 2019 |
| Acer          | Aspire 4810T                | [f177f662c9](https://linux-hardware.org/?probe=f177f662c9) | Oct 21, 2019 |
| HP            | Laptop 15-bw0xx             | [3eade14c1a](https://linux-hardware.org/?probe=3eade14c1a) | Oct 18, 2019 |
| Fujitsu Si... | LIFEBOOK E8410              | [4a653fdd06](https://linux-hardware.org/?probe=4a653fdd06) | Oct 12, 2019 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [d0e6b3a935](https://linux-hardware.org/?probe=d0e6b3a935) | Oct 08, 2019 |
| HP            | Laptop 15-bs0xx             | [5b817a0d34](https://linux-hardware.org/?probe=5b817a0d34) | Oct 06, 2019 |
| ASUSTek       | 1101HA                      | [61837b2a0e](https://linux-hardware.org/?probe=61837b2a0e) | Sep 27, 2019 |
| Dell          | Inspiron 13-5378            | [37c0832ec3](https://linux-hardware.org/?probe=37c0832ec3) | Sep 20, 2019 |
| ASUSTek       | 1101HA                      | [8ad347373c](https://linux-hardware.org/?probe=8ad347373c) | Sep 15, 2019 |
| ASUSTek       | X541UAK                     | [a8ec17e19a](https://linux-hardware.org/?probe=a8ec17e19a) | Sep 13, 2019 |
| Dell          | Vostro 5581                 | [137d404b4f](https://linux-hardware.org/?probe=137d404b4f) | Sep 04, 2019 |
| Samsung       | R528/R728                   | [9a81ee014c](https://linux-hardware.org/?probe=9a81ee014c) | Aug 31, 2019 |
| ASUSTek       | K501UX                      | [5e0c250961](https://linux-hardware.org/?probe=5e0c250961) | Aug 22, 2019 |
| Dell          | Vostro 5581                 | [6d17449b1e](https://linux-hardware.org/?probe=6d17449b1e) | Aug 19, 2019 |
| Dell          | Vostro 5581                 | [e890c77b5d](https://linux-hardware.org/?probe=e890c77b5d) | Aug 18, 2019 |
| Lenovo        | ThinkPad SL510 2875RS2      | [85f5a138a1](https://linux-hardware.org/?probe=85f5a138a1) | Aug 16, 2019 |
| Lenovo        | G50-30 80G0                 | [03e68e8b7c](https://linux-hardware.org/?probe=03e68e8b7c) | Aug 14, 2019 |
| Samsung       | R580/R590                   | [ef8583eaed](https://linux-hardware.org/?probe=ef8583eaed) | Aug 09, 2019 |
| HP            | Pavilion 17                 | [24e7df16f9](https://linux-hardware.org/?probe=24e7df16f9) | Aug 03, 2019 |
| ASUSTek       | 1011PX                      | [5b135fd648](https://linux-hardware.org/?probe=5b135fd648) | Aug 01, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [47bfe0724a](https://linux-hardware.org/?probe=47bfe0724a) | Jul 30, 2019 |
| ASUSTek       | K54HR                       | [5e03bd6730](https://linux-hardware.org/?probe=5e03bd6730) | Jul 29, 2019 |
| Acer          | Extensa 2510G               | [1c77d7a584](https://linux-hardware.org/?probe=1c77d7a584) | Jul 27, 2019 |
| Acer          | Nitro AN515-31              | [c1f4538adb](https://linux-hardware.org/?probe=c1f4538adb) | Jul 24, 2019 |
| Lenovo        | G570 20079                  | [a7618091fb](https://linux-hardware.org/?probe=a7618091fb) | Jul 23, 2019 |
| Acer          | Extensa 2508                | [a1d2e02773](https://linux-hardware.org/?probe=a1d2e02773) | Jul 22, 2019 |
| ASUSTek       | X540SA                      | [9964879fbe](https://linux-hardware.org/?probe=9964879fbe) | Jul 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a385ff1671](https://linux-hardware.org/?probe=a385ff1671) | Jul 20, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1a41f9e428](https://linux-hardware.org/?probe=1a41f9e428) | Jul 20, 2019 |
| MSI           | MS-N014                     | [a6b6d22f92](https://linux-hardware.org/?probe=a6b6d22f92) | Jul 18, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [00eecf27f3](https://linux-hardware.org/?probe=00eecf27f3) | Jul 16, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6b13d225c0](https://linux-hardware.org/?probe=6b13d225c0) | Jul 09, 2019 |
| Acer          | Aspire E1-771               | [4a1964118d](https://linux-hardware.org/?probe=4a1964118d) | Jul 04, 2019 |
| Acer          | Aspire V3-772G              | [6cc64da5c5](https://linux-hardware.org/?probe=6cc64da5c5) | Jun 20, 2019 |
| Lenovo        | B570e HuronRiver Platfor... | [678d443649](https://linux-hardware.org/?probe=678d443649) | Jun 14, 2019 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [f72a609702](https://linux-hardware.org/?probe=f72a609702) | Jun 13, 2019 |
| Lenovo        | B570e HuronRiver Platfor... | [b74e6f3a71](https://linux-hardware.org/?probe=b74e6f3a71) | Jun 08, 2019 |
| HP            | ENVY 17                     | [9f9eeecefa](https://linux-hardware.org/?probe=9f9eeecefa) | Jun 05, 2019 |
| Acer          | Aspire 4810T                | [0b3243adb4](https://linux-hardware.org/?probe=0b3243adb4) | May 29, 2019 |
| Acer          | Aspire 5349                 | [8e79cddbda](https://linux-hardware.org/?probe=8e79cddbda) | May 23, 2019 |
| Lenovo        | IdeaPad Z510 20287          | [8358a6f5f5](https://linux-hardware.org/?probe=8358a6f5f5) | May 22, 2019 |
| ASUSTek       | X551MA                      | [ef445a792b](https://linux-hardware.org/?probe=ef445a792b) | May 20, 2019 |
| ASUSTek       | X551MA                      | [5ad90522ec](https://linux-hardware.org/?probe=5ad90522ec) | May 20, 2019 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ba1f9829de](https://linux-hardware.org/?probe=ba1f9829de) | May 19, 2019 |
| ASUSTek       | X751SA                      | [412366312b](https://linux-hardware.org/?probe=412366312b) | May 18, 2019 |
| Dell          | Inspiron 7577               | [ae6c3a51b8](https://linux-hardware.org/?probe=ae6c3a51b8) | May 17, 2019 |
| ASUSTek       | X751SA                      | [bb1fd1c382](https://linux-hardware.org/?probe=bb1fd1c382) | May 17, 2019 |
| ASUSTek       | X751SA                      | [130b715a25](https://linux-hardware.org/?probe=130b715a25) | May 17, 2019 |
| Samsung       | RV413/RV513                 | [539459e889](https://linux-hardware.org/?probe=539459e889) | May 16, 2019 |
| Samsung       | RV413/RV513                 | [c6e6520b11](https://linux-hardware.org/?probe=c6e6520b11) | May 16, 2019 |
| ASUSTek       | UL30A                       | [6dac8a4d6f](https://linux-hardware.org/?probe=6dac8a4d6f) | May 13, 2019 |
| HP            | ProBook 455 G1              | [185cf26f05](https://linux-hardware.org/?probe=185cf26f05) | May 09, 2019 |
| ASUSTek       | X510UA                      | [f6c30b2027](https://linux-hardware.org/?probe=f6c30b2027) | May 05, 2019 |
| Acer          | Nitro AN515-31              | [7a2df83bd4](https://linux-hardware.org/?probe=7a2df83bd4) | Apr 20, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [67a4e2a8a4](https://linux-hardware.org/?probe=67a4e2a8a4) | Apr 18, 2019 |
| Acer          | Nitro AN515-31              | [7ffaa2afa6](https://linux-hardware.org/?probe=7ffaa2afa6) | Apr 16, 2019 |
| ASUSTek       | UL30A                       | [46271f4c83](https://linux-hardware.org/?probe=46271f4c83) | Apr 07, 2019 |
| ASUSTek       | UX550VD                     | [c440ebc340](https://linux-hardware.org/?probe=c440ebc340) | Apr 04, 2019 |
| ASUSTek       | UL30A                       | [059a9e0d5f](https://linux-hardware.org/?probe=059a9e0d5f) | Apr 02, 2019 |
| HP            | Notebook                    | [b09be0c6da](https://linux-hardware.org/?probe=b09be0c6da) | Mar 31, 2019 |
| Lenovo        | B590 20206                  | [c0039b9d80](https://linux-hardware.org/?probe=c0039b9d80) | Mar 27, 2019 |
| Lenovo        | G50-30 80G0                 | [f801da09f7](https://linux-hardware.org/?probe=f801da09f7) | Mar 26, 2019 |
| Lenovo        | IdeaPad Z565 20066          | [6e6d9742ed](https://linux-hardware.org/?probe=6e6d9742ed) | Mar 23, 2019 |
| ASUSTek       | K50IP                       | [16e798fc6d](https://linux-hardware.org/?probe=16e798fc6d) | Mar 22, 2019 |
| HP            | Laptop 15-bs0xx             | [61650808a4](https://linux-hardware.org/?probe=61650808a4) | Mar 16, 2019 |
| ASUSTek       | X541NA                      | [339f40edee](https://linux-hardware.org/?probe=339f40edee) | Mar 16, 2019 |
| ASUSTek       | X541NA                      | [deef5c1776](https://linux-hardware.org/?probe=deef5c1776) | Mar 16, 2019 |
| Lenovo        | G700 20251                  | [31a2a66abd](https://linux-hardware.org/?probe=31a2a66abd) | Mar 15, 2019 |
| Lenovo        | G570 20079                  | [dddc5b738c](https://linux-hardware.org/?probe=dddc5b738c) | Mar 12, 2019 |
| HP            | 635                         | [c510246cec](https://linux-hardware.org/?probe=c510246cec) | Mar 09, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [bf7d967cac](https://linux-hardware.org/?probe=bf7d967cac) | Mar 05, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [42c1b17429](https://linux-hardware.org/?probe=42c1b17429) | Feb 28, 2019 |
| ASUSTek       | N73JF                       | [ac3cf92791](https://linux-hardware.org/?probe=ac3cf92791) | Feb 24, 2019 |
| ASUSTek       | N73JF                       | [74010f75ff](https://linux-hardware.org/?probe=74010f75ff) | Feb 24, 2019 |
| Acer          | Aspire 3810TZ               | [1af1fd4358](https://linux-hardware.org/?probe=1af1fd4358) | Feb 08, 2019 |
| Dell          | Inspiron 5558               | [74b5e8085f](https://linux-hardware.org/?probe=74b5e8085f) | Feb 06, 2019 |
| HP            | EliteBook 840 G3            | [9246996d88](https://linux-hardware.org/?probe=9246996d88) | Feb 04, 2019 |
| Acer          | Aspire V3-571G              | [5c2493db94](https://linux-hardware.org/?probe=5c2493db94) | Feb 03, 2019 |
| ASUSTek       | E402NA                      | [84151cf35d](https://linux-hardware.org/?probe=84151cf35d) | Jan 30, 2019 |
| Samsung       | R519/R719                   | [c2367f286b](https://linux-hardware.org/?probe=c2367f286b) | Jan 26, 2019 |
| ASUSTek       | X540NV                      | [fd26f0c83a](https://linux-hardware.org/?probe=fd26f0c83a) | Jan 22, 2019 |
| HP            | G62                         | [63c41b239d](https://linux-hardware.org/?probe=63c41b239d) | Jan 21, 2019 |
| HP            | Laptop 15-rb0xx             | [e4399cedcf](https://linux-hardware.org/?probe=e4399cedcf) | Jan 10, 2019 |
| HP            | Laptop 15-rb0xx             | [c4ca5d85f2](https://linux-hardware.org/?probe=c4ca5d85f2) | Jan 10, 2019 |
| ASUSTek       | T101MT                      | [742c2cd59e](https://linux-hardware.org/?probe=742c2cd59e) | Jan 10, 2019 |
| HP            | Compaq Mini 110c-1100       | [f1a0693718](https://linux-hardware.org/?probe=f1a0693718) | Jan 09, 2019 |
| HP            | Notebook                    | [93451d1d63](https://linux-hardware.org/?probe=93451d1d63) | Dec 31, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [441e47c023](https://linux-hardware.org/?probe=441e47c023) | Dec 30, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d942bb34d](https://linux-hardware.org/?probe=5d942bb34d) | Dec 30, 2018 |
| Samsung       | RV408/RV508                 | [f67c14e4d6](https://linux-hardware.org/?probe=f67c14e4d6) | Dec 27, 2018 |
| Samsung       | R508                        | [c9ea0249f2](https://linux-hardware.org/?probe=c9ea0249f2) | Dec 24, 2018 |
| Acer          | AOD257                      | [d6763cd3ef](https://linux-hardware.org/?probe=d6763cd3ef) | Dec 23, 2018 |
| Samsung       | RV413/RV513                 | [d069cd58a8](https://linux-hardware.org/?probe=d069cd58a8) | Dec 20, 2018 |
| Acer          | Extensa 7630EZ              | [ff4bc33ec4](https://linux-hardware.org/?probe=ff4bc33ec4) | Dec 18, 2018 |
| ASUSTek       | M51Sr                       | [c91fc1e6b1](https://linux-hardware.org/?probe=c91fc1e6b1) | Dec 15, 2018 |
| Acer          | TravelMate 5760             | [fd0de5be57](https://linux-hardware.org/?probe=fd0de5be57) | Dec 14, 2018 |
| Acer          | Aspire ES1-523              | [b586596a6a](https://linux-hardware.org/?probe=b586596a6a) | Dec 10, 2018 |
| Lenovo        | Z50-70 20354                | [5d8804f368](https://linux-hardware.org/?probe=5d8804f368) | Dec 07, 2018 |
| Acer          | TravelMate 8481T            | [af2aaf56d9](https://linux-hardware.org/?probe=af2aaf56d9) | Dec 07, 2018 |
| ASUSTek       | N76VJ                       | [2fa5ed1dfc](https://linux-hardware.org/?probe=2fa5ed1dfc) | Nov 30, 2018 |
| Toshiba       | Satellite L300              | [8585fa81bc](https://linux-hardware.org/?probe=8585fa81bc) | Nov 29, 2018 |
| HP            | ProBook 4515s               | [1842a1b183](https://linux-hardware.org/?probe=1842a1b183) | Nov 29, 2018 |
| Lenovo        | B590 20206                  | [020331dd95](https://linux-hardware.org/?probe=020331dd95) | Nov 29, 2018 |
| Lenovo        | B590 20206                  | [9cb3062067](https://linux-hardware.org/?probe=9cb3062067) | Nov 29, 2018 |
| ASUSTek       | X510UNR                     | [8cc859859e](https://linux-hardware.org/?probe=8cc859859e) | Nov 28, 2018 |
| Acer          | Aspire 5750ZG               | [d138e04435](https://linux-hardware.org/?probe=d138e04435) | Nov 27, 2018 |
| Acer          | Aspire 5750ZG               | [516c88099e](https://linux-hardware.org/?probe=516c88099e) | Nov 23, 2018 |
| Lenovo        | B590 20206                  | [0cd011a796](https://linux-hardware.org/?probe=0cd011a796) | Nov 14, 2018 |
| Dell          | Inspiron M5010              | [2457e3698d](https://linux-hardware.org/?probe=2457e3698d) | Nov 05, 2018 |
| Packard Be... | EasyNote TE11HC             | [a196f24690](https://linux-hardware.org/?probe=a196f24690) | Nov 01, 2018 |
| Toshiba       | Satellite A215              | [8bf0975fb2](https://linux-hardware.org/?probe=8bf0975fb2) | Oct 31, 2018 |
| Lenovo        | G700 20251                  | [e8d909b0fa](https://linux-hardware.org/?probe=e8d909b0fa) | Oct 27, 2018 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [fddef6b216](https://linux-hardware.org/?probe=fddef6b216) | Oct 25, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2d1c5d19bf](https://linux-hardware.org/?probe=2d1c5d19bf) | Oct 25, 2018 |
| ASUSTek       | U32VJ                       | [a1d3315657](https://linux-hardware.org/?probe=a1d3315657) | Oct 24, 2018 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0a670684fa](https://linux-hardware.org/?probe=0a670684fa) | Oct 24, 2018 |
| Lenovo        | G700 20251                  | [c556cef805](https://linux-hardware.org/?probe=c556cef805) | Oct 19, 2018 |
| Acer          | Aspire ES1-520              | [7734a8cc4b](https://linux-hardware.org/?probe=7734a8cc4b) | Oct 19, 2018 |
| Toshiba       | Satellite L650              | [3c94da7bb6](https://linux-hardware.org/?probe=3c94da7bb6) | Oct 17, 2018 |
| Samsung       | RV413/RV513                 | [6045dbdc70](https://linux-hardware.org/?probe=6045dbdc70) | Oct 14, 2018 |
| Lenovo        | V580c 20160                 | [9322372044](https://linux-hardware.org/?probe=9322372044) | Oct 05, 2018 |
| ASUSTek       | X55A                        | [5137394ef1](https://linux-hardware.org/?probe=5137394ef1) | Oct 04, 2018 |
| HP            | Pavilion dv6                | [b4469a7aa8](https://linux-hardware.org/?probe=b4469a7aa8) | Oct 02, 2018 |
| ASUSTek       | K42Jr                       | [4f4c1ec561](https://linux-hardware.org/?probe=4f4c1ec561) | Sep 19, 2018 |
| Samsung       | RV413/RV513                 | [074d9a8a6c](https://linux-hardware.org/?probe=074d9a8a6c) | Sep 15, 2018 |
| HP            | ProBook 450 G1              | [a451edb119](https://linux-hardware.org/?probe=a451edb119) | Sep 15, 2018 |
| ASUSTek       | K54L                        | [5db2420e7b](https://linux-hardware.org/?probe=5db2420e7b) | Sep 15, 2018 |
| Samsung       | RV408/RV508                 | [0fcb4ce699](https://linux-hardware.org/?probe=0fcb4ce699) | Sep 06, 2018 |
| Acer          | Extensa 5620                | [59004a5a4d](https://linux-hardware.org/?probe=59004a5a4d) | Aug 28, 2018 |
| HP            | Presario CQ57               | [983b775183](https://linux-hardware.org/?probe=983b775183) | Aug 18, 2018 |
| Acer          | Extensa 5220                | [953f048aa5](https://linux-hardware.org/?probe=953f048aa5) | Aug 12, 2018 |
| Samsung       | N100SP                      | [ef7b7f37ee](https://linux-hardware.org/?probe=ef7b7f37ee) | Aug 07, 2018 |
| Lenovo        | G50-30 80G0                 | [b64c5d0ebc](https://linux-hardware.org/?probe=b64c5d0ebc) | Jul 24, 2018 |
| Acer          | Aspire E1-571G              | [86481cccd4](https://linux-hardware.org/?probe=86481cccd4) | Jul 22, 2018 |
| HP            | ProBook 455 G1              | [ca9f342b1a](https://linux-hardware.org/?probe=ca9f342b1a) | Jul 19, 2018 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [3fb448c842](https://linux-hardware.org/?probe=3fb448c842) | Jul 18, 2018 |
| HP            | Laptop 15-bs0xx             | [069c204d22](https://linux-hardware.org/?probe=069c204d22) | Jul 09, 2018 |
| Lenovo        | G700 20251                  | [8f57f46f49](https://linux-hardware.org/?probe=8f57f46f49) | Jun 26, 2018 |
| HP            | ProBook 4530s               | [993712a06c](https://linux-hardware.org/?probe=993712a06c) | Jun 21, 2018 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [2ce150a93d](https://linux-hardware.org/?probe=2ce150a93d) | Jun 20, 2018 |
| Samsung       | N100SP                      | [b9449f3937](https://linux-hardware.org/?probe=b9449f3937) | Jun 03, 2018 |
| ASUSTek       | X502CA                      | [2867d3e608](https://linux-hardware.org/?probe=2867d3e608) | Jun 03, 2018 |
| ASUSTek       | X502CA                      | [c0ca1e77e7](https://linux-hardware.org/?probe=c0ca1e77e7) | Jun 02, 2018 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [c49afc2dd2](https://linux-hardware.org/?probe=c49afc2dd2) | May 28, 2018 |
| Acer          | Aspire E1-571G              | [d850e72e1e](https://linux-hardware.org/?probe=d850e72e1e) | May 16, 2018 |
| Sony          | VGN-FW235J                  | [9320f505e2](https://linux-hardware.org/?probe=9320f505e2) | May 15, 2018 |
| Lenovo        | G50-30 80G0                 | [3a38db14d4](https://linux-hardware.org/?probe=3a38db14d4) | May 11, 2018 |
| ASUSTek       | K53E                        | [e590bb8d6f](https://linux-hardware.org/?probe=e590bb8d6f) | Apr 23, 2018 |
| Samsung       | 3570R/370R/470R/450R/510... | [d5a992e215](https://linux-hardware.org/?probe=d5a992e215) | Apr 20, 2018 |
| Acer          | Aspire 3810TZ               | [a02d089fef](https://linux-hardware.org/?probe=a02d089fef) | Apr 19, 2018 |
| Lenovo        | G50-80 80E5                 | [fbd53229e1](https://linux-hardware.org/?probe=fbd53229e1) | Apr 17, 2018 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c44fded5bf](https://linux-hardware.org/?probe=c44fded5bf) | Apr 12, 2018 |
| Lenovo        | G50-30 80G0                 | [e0a99c9020](https://linux-hardware.org/?probe=e0a99c9020) | Apr 11, 2018 |
| ASUSTek       | 1005PX                      | [3bd5d73da2](https://linux-hardware.org/?probe=3bd5d73da2) | Apr 09, 2018 |
| Lenovo        | G505 20240                  | [94360ae24c](https://linux-hardware.org/?probe=94360ae24c) | Apr 07, 2018 |
| ASUSTek       | X551MA                      | [a941a24e7c](https://linux-hardware.org/?probe=a941a24e7c) | Mar 29, 2018 |
| HP            | ProBook 4540s               | [c79bd3efcd](https://linux-hardware.org/?probe=c79bd3efcd) | Mar 28, 2018 |
| Acer          | Aspire ES1-523              | [d3f9785c45](https://linux-hardware.org/?probe=d3f9785c45) | Mar 25, 2018 |
| Dell          | Inspiron 1521               | [ceed13b4fc](https://linux-hardware.org/?probe=ceed13b4fc) | Mar 15, 2018 |
| Toshiba       | Satellite L650              | [15735e6616](https://linux-hardware.org/?probe=15735e6616) | Mar 08, 2018 |
| Dell          | Latitude E6410              | [c714bf47fb](https://linux-hardware.org/?probe=c714bf47fb) | Mar 08, 2018 |
| Apple         | MacBookPro9,2               | [93a5831bf0](https://linux-hardware.org/?probe=93a5831bf0) | Mar 07, 2018 |
| Toshiba       | PLCSF                       | [b2185404aa](https://linux-hardware.org/?probe=b2185404aa) | Mar 07, 2018 |
| ASUSTek       | UL30A                       | [921f5d069e](https://linux-hardware.org/?probe=921f5d069e) | Mar 04, 2018 |
| ASUSTek       | UL30A                       | [0baf4ccbe8](https://linux-hardware.org/?probe=0baf4ccbe8) | Mar 04, 2018 |
| ASUSTek       | K50IJ                       | [4ab4ba786a](https://linux-hardware.org/?probe=4ab4ba786a) | Mar 03, 2018 |
| Sony          | VGN-FW235J                  | [8b36bcb7f3](https://linux-hardware.org/?probe=8b36bcb7f3) | Feb 26, 2018 |
| ASUSTek       | X540LJ                      | [1e9c4a36ab](https://linux-hardware.org/?probe=1e9c4a36ab) | Feb 20, 2018 |
| HP            | 655                         | [7d65695404](https://linux-hardware.org/?probe=7d65695404) | Feb 13, 2018 |
| Fujitsu Si... | LIFEBOOK S6410              | [0ce4f9b4f0](https://linux-hardware.org/?probe=0ce4f9b4f0) | Feb 09, 2018 |
| MSI           | CR500                       | [34f7962c46](https://linux-hardware.org/?probe=34f7962c46) | Feb 06, 2018 |
| Acer          | Aspire E1-532G              | [fafd8a85b2](https://linux-hardware.org/?probe=fafd8a85b2) | Feb 01, 2018 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [7fd5e7b200](https://linux-hardware.org/?probe=7fd5e7b200) | Jan 28, 2018 |
| Intel         | Pine Trail - M Revision ... | [65eaa7c7b0](https://linux-hardware.org/?probe=65eaa7c7b0) | Jan 26, 2018 |
| HP            | 625                         | [249a8b5fdd](https://linux-hardware.org/?probe=249a8b5fdd) | Jan 20, 2018 |
| Packard Be... | EasyNote TE11HC             | [213e2f388c](https://linux-hardware.org/?probe=213e2f388c) | Jan 20, 2018 |
| HP            | 655                         | [0b1492a552](https://linux-hardware.org/?probe=0b1492a552) | Jan 19, 2018 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4bd68b7165](https://linux-hardware.org/?probe=4bd68b7165) | Jan 18, 2018 |
| HP            | ProBook 4545s               | [7d82dfba11](https://linux-hardware.org/?probe=7d82dfba11) | Jan 18, 2018 |
| Dell          | Inspiron 5547               | [fab8b9e9b9](https://linux-hardware.org/?probe=fab8b9e9b9) | Jan 18, 2018 |
| Dell          | Inspiron 5547               | [c01a939820](https://linux-hardware.org/?probe=c01a939820) | Jan 17, 2018 |
| Acer          | Aspire V5-123               | [bcd1391d57](https://linux-hardware.org/?probe=bcd1391d57) | Jan 16, 2018 |
| Intel         | Calistoga & ICH7M Chipse... | [f57558ef8e](https://linux-hardware.org/?probe=f57558ef8e) | Jan 15, 2018 |
| Intel         | Calistoga & ICH7M Chipse... | [400fef0f85](https://linux-hardware.org/?probe=400fef0f85) | Jan 14, 2018 |
| Intel         | Calistoga & ICH7M Chipse... | [c8b498a8d0](https://linux-hardware.org/?probe=c8b498a8d0) | Jan 14, 2018 |
| HP            | Pavilion dv6                | [3fbd1376b7](https://linux-hardware.org/?probe=3fbd1376b7) | Jan 09, 2018 |
| Samsung       | RV413/RV513                 | [7ca80b846a](https://linux-hardware.org/?probe=7ca80b846a) | Jan 07, 2018 |
| HP            | Pavilion dv6                | [0810aed827](https://linux-hardware.org/?probe=0810aed827) | Jan 07, 2018 |
| HP            | 655                         | [dde30fdece](https://linux-hardware.org/?probe=dde30fdece) | Jan 06, 2018 |
| HP            | 655                         | [00bccddf88](https://linux-hardware.org/?probe=00bccddf88) | Jan 06, 2018 |
| ASUSTek       | 1015PW                      | [b3bc5400d4](https://linux-hardware.org/?probe=b3bc5400d4) | Jan 06, 2018 |
| HP            | Pavilion dv6                | [f8e6613c03](https://linux-hardware.org/?probe=f8e6613c03) | Jan 06, 2018 |
| Lenovo        | B50-30 20382                | [6804eb0dbd](https://linux-hardware.org/?probe=6804eb0dbd) | Jan 06, 2018 |
| HP            | ProBook 4545s               | [331866b4c7](https://linux-hardware.org/?probe=331866b4c7) | Jan 03, 2018 |
| HP            | ProBook 4545s               | [10c7a2f540](https://linux-hardware.org/?probe=10c7a2f540) | Dec 30, 2017 |
| Dell          | Inspiron 1011               | [c66fdb41dd](https://linux-hardware.org/?probe=c66fdb41dd) | Dec 29, 2017 |
| Dell          | Inspiron 1011               | [4fbadfa275](https://linux-hardware.org/?probe=4fbadfa275) | Dec 29, 2017 |
| Lenovo        | G570 20079                  | [bdd7629c53](https://linux-hardware.org/?probe=bdd7629c53) | Dec 26, 2017 |
| HP            | Presario CQ56               | [55af7d7fe8](https://linux-hardware.org/?probe=55af7d7fe8) | Dec 24, 2017 |
| Samsung       | 730U3E/740U3E               | [7012ff7276](https://linux-hardware.org/?probe=7012ff7276) | Dec 22, 2017 |
| Lenovo        | G505 20240                  | [7d9cdbcb00](https://linux-hardware.org/?probe=7d9cdbcb00) | Dec 16, 2017 |
| Acer          | Aspire E1-731               | [784a423bb4](https://linux-hardware.org/?probe=784a423bb4) | Dec 06, 2017 |
| Acer          | Aspire 5715Z                | [4a8d94b93c](https://linux-hardware.org/?probe=4a8d94b93c) | Dec 03, 2017 |
| Lenovo        | G580 20157                  | [1e8e60ca9b](https://linux-hardware.org/?probe=1e8e60ca9b) | Nov 30, 2017 |
| Acer          | Aspire E1-530               | [4c35840f32](https://linux-hardware.org/?probe=4c35840f32) | Nov 30, 2017 |
| Lenovo        | G580 20157                  | [f1fe4f2dcf](https://linux-hardware.org/?probe=f1fe4f2dcf) | Nov 29, 2017 |
| Lenovo        | G50-30 80G0                 | [46cc147da2](https://linux-hardware.org/?probe=46cc147da2) | Nov 23, 2017 |
| Acer          | Aspire E1-530               | [928cb28dfb](https://linux-hardware.org/?probe=928cb28dfb) | Nov 23, 2017 |
| Lenovo        | ThinkPad SL510 2875RS2      | [bac0b17fd2](https://linux-hardware.org/?probe=bac0b17fd2) | Nov 16, 2017 |
| Lenovo        | G50-30 80G0                 | [d0d8e703c3](https://linux-hardware.org/?probe=d0d8e703c3) | Nov 14, 2017 |
| Dell          | Vostro A860                 | [2af75a3d92](https://linux-hardware.org/?probe=2af75a3d92) | Nov 07, 2017 |
| Acer          | TravelMate 5760             | [9c0d8f5802](https://linux-hardware.org/?probe=9c0d8f5802) | Nov 06, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c7d2faa40e](https://linux-hardware.org/?probe=c7d2faa40e) | Nov 04, 2017 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [a9540b0804](https://linux-hardware.org/?probe=a9540b0804) | Nov 03, 2017 |
| MSI           | U90/U100                    | [2c8b8dc1fb](https://linux-hardware.org/?probe=2c8b8dc1fb) | Oct 30, 2017 |
| Samsung       | R508                        | [cd09147d1a](https://linux-hardware.org/?probe=cd09147d1a) | Oct 26, 2017 |
| HP            | Pavilion g6                 | [ad6ea79e40](https://linux-hardware.org/?probe=ad6ea79e40) | Oct 15, 2017 |
| ASUSTek       | X553MA                      | [566133cd83](https://linux-hardware.org/?probe=566133cd83) | Sep 24, 2017 |
| Acer          | TravelMate 5760             | [6ee2556405](https://linux-hardware.org/?probe=6ee2556405) | Sep 16, 2017 |
| Acer          | Extensa 5220                | [5abac2fefd](https://linux-hardware.org/?probe=5abac2fefd) | Sep 14, 2017 |
| ASUSTek       | X540LJ                      | [f2e803d3b4](https://linux-hardware.org/?probe=f2e803d3b4) | Sep 07, 2017 |
| Dell          | Inspiron M5110              | [47d26c92c9](https://linux-hardware.org/?probe=47d26c92c9) | Sep 01, 2017 |
| HP            | ProBook 455 G1              | [065581e1a2](https://linux-hardware.org/?probe=065581e1a2) | Aug 31, 2017 |
| ASUSTek       | X550CC                      | [9417e4c182](https://linux-hardware.org/?probe=9417e4c182) | Aug 23, 2017 |
| ASUSTek       | A6J                         | [f680730915](https://linux-hardware.org/?probe=f680730915) | Aug 14, 2017 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [eb120c5904](https://linux-hardware.org/?probe=eb120c5904) | Aug 07, 2017 |
| ASUSTek       | X550MJ                      | [62be56c501](https://linux-hardware.org/?probe=62be56c501) | Jul 31, 2017 |
| HP            | ProBook 455 G1              | [bd1f5d775f](https://linux-hardware.org/?probe=bd1f5d775f) | Jul 29, 2017 |
| Lenovo        | B590 20206                  | [06b36668b9](https://linux-hardware.org/?probe=06b36668b9) | Jul 18, 2017 |
| ASUSTek       | N55SL                       | [fe8018c4c4](https://linux-hardware.org/?probe=fe8018c4c4) | Jul 15, 2017 |
| Acer          | TravelMate 5760             | [d04461240c](https://linux-hardware.org/?probe=d04461240c) | Jul 08, 2017 |
| HP            | Presario CQ56               | [de976cca7a](https://linux-hardware.org/?probe=de976cca7a) | Jul 08, 2017 |
| ASUSTek       | A6J                         | [e417c347d8](https://linux-hardware.org/?probe=e417c347d8) | Jul 04, 2017 |
| ASUSTek       | A6J                         | [cd68b9194b](https://linux-hardware.org/?probe=cd68b9194b) | Jul 03, 2017 |
| ASUSTek       | A6J                         | [e591d8bdd0](https://linux-hardware.org/?probe=e591d8bdd0) | Jul 03, 2017 |
| Lenovo        | G50-30 80G0                 | [83327d6299](https://linux-hardware.org/?probe=83327d6299) | Jul 03, 2017 |
| ASUSTek       | A6J                         | [ef5284d65a](https://linux-hardware.org/?probe=ef5284d65a) | Jul 03, 2017 |
| MSI           | CR650                       | [bb97b32449](https://linux-hardware.org/?probe=bb97b32449) | Jul 03, 2017 |
| ASUSTek       | A6J                         | [4cb6f17eb2](https://linux-hardware.org/?probe=4cb6f17eb2) | Jul 01, 2017 |
| ASUSTek       | 1011PX                      | [b4698e905d](https://linux-hardware.org/?probe=b4698e905d) | Jun 29, 2017 |
| Dell          | System XPS L702X            | [791ca50070](https://linux-hardware.org/?probe=791ca50070) | Jun 14, 2017 |
| IBM           | ThinkPad X41 2525FAG        | [671ec7621b](https://linux-hardware.org/?probe=671ec7621b) | Jun 13, 2017 |
| ASUSTek       | N55SL                       | [ae2875f46b](https://linux-hardware.org/?probe=ae2875f46b) | Jun 12, 2017 |
| Lenovo        | G50-30 80G0                 | [58235630a7](https://linux-hardware.org/?probe=58235630a7) | Jun 11, 2017 |
| HP            | Pavilion g6                 | [897e37b204](https://linux-hardware.org/?probe=897e37b204) | Jun 10, 2017 |
| Toshiba       | Satellite L50-A-K3S         | [6c7996782a](https://linux-hardware.org/?probe=6c7996782a) | Jun 01, 2017 |
| IBM           | ThinkPad X41 2525FAG        | [b69e0c7e24](https://linux-hardware.org/?probe=b69e0c7e24) | May 27, 2017 |
| Lenovo        | G500 20236                  | [8fc07a6f38](https://linux-hardware.org/?probe=8fc07a6f38) | May 26, 2017 |
| HP            | ProBook 6570b               | [a5fcc33bca](https://linux-hardware.org/?probe=a5fcc33bca) | May 23, 2017 |
| Acer          | Extensa 5220                | [986f64cc82](https://linux-hardware.org/?probe=986f64cc82) | May 22, 2017 |
| Acer          | Extensa 5220                | [94ac9a45f4](https://linux-hardware.org/?probe=94ac9a45f4) | May 22, 2017 |
| Acer          | Extensa 5230                | [5d9b4a011a](https://linux-hardware.org/?probe=5d9b4a011a) | May 19, 2017 |
| HP            | ProBook 455 G1              | [d986e13cd8](https://linux-hardware.org/?probe=d986e13cd8) | May 17, 2017 |
| Dell          | Inspiron 14-3452            | [f2e5a3b622](https://linux-hardware.org/?probe=f2e5a3b622) | May 12, 2017 |
| Acer          | TravelMate 2490             | [b26e098033](https://linux-hardware.org/?probe=b26e098033) | May 11, 2017 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [050ee437d3](https://linux-hardware.org/?probe=050ee437d3) | May 07, 2017 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [6f7f681b65](https://linux-hardware.org/?probe=6f7f681b65) | Apr 29, 2017 |
| HP            | Pavilion dv7                | [2db47d03ca](https://linux-hardware.org/?probe=2db47d03ca) | Apr 27, 2017 |
| Acer          | Aspire 7552                 | [e54de6ed57](https://linux-hardware.org/?probe=e54de6ed57) | Apr 19, 2017 |
| ASUSTek       | K53U                        | [8250fd2ed0](https://linux-hardware.org/?probe=8250fd2ed0) | Apr 11, 2017 |
| Samsung       | R710                        | [7694ff8186](https://linux-hardware.org/?probe=7694ff8186) | Apr 09, 2017 |
| Acer          | Aspire E1-531               | [abadda8c39](https://linux-hardware.org/?probe=abadda8c39) | Apr 09, 2017 |
| ViewSonic     | ViewBook                    | [510f3cfb16](https://linux-hardware.org/?probe=510f3cfb16) | Apr 09, 2017 |
| Samsung       | R508                        | [0cf5690d55](https://linux-hardware.org/?probe=0cf5690d55) | Mar 26, 2017 |
| Lenovo        | G580 20150                  | [5fc4eab41d](https://linux-hardware.org/?probe=5fc4eab41d) | Mar 26, 2017 |
| HP            | Pavilion g7                 | [2c52ae0e3d](https://linux-hardware.org/?probe=2c52ae0e3d) | Mar 12, 2017 |
| ASUSTek       | X101CH                      | [c29cb19972](https://linux-hardware.org/?probe=c29cb19972) | Mar 12, 2017 |
| HP            | ProBook 4530s               | [b0cd8c5a7b](https://linux-hardware.org/?probe=b0cd8c5a7b) | Mar 05, 2017 |
| Lenovo        | G580 20157                  | [05b88b336c](https://linux-hardware.org/?probe=05b88b336c) | Mar 04, 2017 |
| HP            | Pavilion 15                 | [9371b21011](https://linux-hardware.org/?probe=9371b21011) | Feb 26, 2017 |
| Lenovo        | G570 20079                  | [ba04639760](https://linux-hardware.org/?probe=ba04639760) | Feb 18, 2017 |
| Lenovo        | G570 20079                  | [a399e00c28](https://linux-hardware.org/?probe=a399e00c28) | Feb 16, 2017 |
| Acer          | Aspire E1-531               | [57b6913eb0](https://linux-hardware.org/?probe=57b6913eb0) | Feb 16, 2017 |
| HP            | ProBook 4530s               | [f5e02506e2](https://linux-hardware.org/?probe=f5e02506e2) | Feb 15, 2017 |
| Lenovo        | G580 20150                  | [33ead87e53](https://linux-hardware.org/?probe=33ead87e53) | Feb 14, 2017 |
| Samsung       | 730U3E/740U3E               | [74ba47c62b](https://linux-hardware.org/?probe=74ba47c62b) | Feb 14, 2017 |
| DNS           | W9x0LU                      | [3f2e919f1f](https://linux-hardware.org/?probe=3f2e919f1f) | Feb 11, 2017 |
| Lenovo        | ThinkPad L420 7854RP1       | [f0510e8901](https://linux-hardware.org/?probe=f0510e8901) | Feb 08, 2017 |
| Acer          | Aspire 5551G                | [63ee188b0a](https://linux-hardware.org/?probe=63ee188b0a) | Feb 06, 2017 |
| Acer          | Aspire 4810T                | [e114bc3f93](https://linux-hardware.org/?probe=e114bc3f93) | Feb 06, 2017 |
| HP            | Mini 5102                   | [0d1332f164](https://linux-hardware.org/?probe=0d1332f164) | Feb 03, 2017 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [67f7100c09](https://linux-hardware.org/?probe=67f7100c09) | Jan 31, 2017 |
| ASUSTek       | K52Dr                       | [b34ce135d6](https://linux-hardware.org/?probe=b34ce135d6) | Jan 22, 2017 |
| Samsung       | RF510/RF410/RF710           | [2dd2f77057](https://linux-hardware.org/?probe=2dd2f77057) | Jan 21, 2017 |
| Acer          | TravelMate 5760             | [961b65d4ed](https://linux-hardware.org/?probe=961b65d4ed) | Jan 19, 2017 |
| Dell          | System XPS L702X            | [a1c104a5ee](https://linux-hardware.org/?probe=a1c104a5ee) | Jan 19, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belarus/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 76        | 10.5%   |
| ROSA R11                     | 56        | 7.73%   |
| Ubuntu 20.04                 | 53        | 7.32%   |
| ROSA R8.1                    | 44        | 6.08%   |
| ROSA R9                      | 32        | 4.42%   |
| ROSA R11.1                   | 28        | 3.87%   |
| Ubuntu 18.04                 | 26        | 3.59%   |
| ROSA R8                      | 20        | 2.76%   |
| ROSA 12.2                    | 19        | 2.62%   |
| Ubuntu 22.04                 | 17        | 2.35%   |
| ROSA 12.3                    | 14        | 1.93%   |
| OpenMandriva 4.2             | 12        | 1.66%   |
| Manjaro                      | 11        | 1.52%   |
| Fedora 36                    | 10        | 1.38%   |
| Arch                         | 10        | 1.38%   |
| ROSA 12.4                    | 9         | 1.24%   |
| Debian 11                    | 9         | 1.24%   |
| Arch Rolling                 | 9         | 1.24%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 0.97%   |
| OpenMandriva 4.3             | 7         | 0.97%   |
| Linux Mint 19.3              | 7         | 0.97%   |
| KDE neon 20.04               | 7         | 0.97%   |
| Fedora 35                    | 7         | 0.97%   |
| Linux Mint 21.1              | 6         | 0.83%   |
| Kubuntu 20.04                | 6         | 0.83%   |
| Fedora 38                    | 6         | 0.83%   |
| Fedora 34                    | 6         | 0.83%   |
| Ubuntu 22.10                 | 5         | 0.69%   |
| Manjaro 20.2.1               | 5         | 0.69%   |
| Linux Mint 20.3              | 5         | 0.69%   |
| Linux Mint 20                | 5         | 0.69%   |
| Linux Mint 19                | 5         | 0.69%   |
| Fedora 37                    | 5         | 0.69%   |
| Debian 12                    | 5         | 0.69%   |
| Xubuntu 20.04                | 4         | 0.55%   |
| Ubuntu 23.04                 | 4         | 0.55%   |
| ROSA 12.1                    | 4         | 0.55%   |
| Manjaro 20.0.3               | 4         | 0.55%   |
| LMDE 5                       | 4         | 0.55%   |
| Ubuntu 21.04                 | 3         | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ROSA             | 248       | 38.93%  |
| Ubuntu           | 114       | 17.9%   |
| Linux Mint       | 37        | 5.81%   |
| Endless          | 36        | 5.65%   |
| Fedora           | 33        | 5.18%   |
| Manjaro          | 30        | 4.71%   |
| OpenMandriva     | 24        | 3.77%   |
| Debian           | 18        | 2.83%   |
| Arch             | 18        | 2.83%   |
| Kubuntu          | 12        | 1.88%   |
| KDE neon         | 9         | 1.41%   |
| Xubuntu          | 8         | 1.26%   |
| openSUSE         | 7         | 1.1%    |
| LMDE             | 6         | 0.94%   |
| Gentoo           | 5         | 0.78%   |
| MX               | 3         | 0.47%   |
| Lubuntu          | 3         | 0.47%   |
| Kali             | 3         | 0.47%   |
| Elementary       | 3         | 0.47%   |
| Ubuntu MATE      | 2         | 0.31%   |
| Pop!_OS          | 2         | 0.31%   |
| Clear Linux      | 2         | 0.31%   |
| Zorin            | 1         | 0.16%   |
| Ubuntu Budgie    | 1         | 0.16%   |
| SteamOS          | 1         | 0.16%   |
| Solus            | 1         | 0.16%   |
| Q4OS             | 1         | 0.16%   |
| Peppermint       | 1         | 0.16%   |
| Parrot           | 1         | 0.16%   |
| org.kde.Platform | 1         | 0.16%   |
| Nobara           | 1         | 0.16%   |
| Devuan           | 1         | 0.16%   |
| Deepin           | 1         | 0.16%   |
| CentOS           | 1         | 0.16%   |
| Artix            | 1         | 0.16%   |
| ALT Linux        | 1         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 38        | 4.8%    |
| 4.15.0-desktop-45.1rosa-x86_64      | 24        | 3.03%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 22        | 2.78%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 21        | 2.65%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 20        | 2.53%   |
| 5.10.14-desktop-1omv4002            | 12        | 1.52%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 12        | 1.52%   |
| 5.4.0-42-generic                    | 11        | 1.39%   |
| 5.4.83-generic-2rosa-x86_64         | 9         | 1.14%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 9         | 1.14%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 9         | 1.14%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 8         | 1.01%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 8         | 1.01%   |
| 4.15.0-desktop-45.1rosa-i586        | 8         | 1.01%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 8         | 1.01%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 7         | 0.88%   |
| 4.9.155-nrj-laptop-1rosa-x86_64     | 7         | 0.88%   |
| 5.9.16-1-MANJARO                    | 6         | 0.76%   |
| 5.4.32-generic-2rosa-x86_64         | 6         | 0.76%   |
| 5.16.7-desktop-1omv4003             | 6         | 0.76%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 6         | 0.76%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 6         | 0.76%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 6         | 0.76%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 5         | 0.63%   |
| 5.8.0-14-generic                    | 5         | 0.63%   |
| 5.3.0-28-generic                    | 5         | 0.63%   |
| 5.15.0-56-generic                   | 5         | 0.63%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 5         | 0.63%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 5         | 0.63%   |
| 4.13.0-32-generic                   | 5         | 0.63%   |
| 5.4.0-26-generic                    | 4         | 0.51%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 4         | 0.51%   |
| 5.15.0-43-generic                   | 4         | 0.51%   |
| 5.11.0-35-generic                   | 4         | 0.51%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 4         | 0.51%   |
| 6.1.1-desktop-1omv2290              | 3         | 0.38%   |
| 6.1.0-10-amd64                      | 3         | 0.38%   |
| 5.8.0-50-generic                    | 3         | 0.38%   |
| 5.8.0-43-generic                    | 3         | 0.38%   |
| 5.4.0-58-generic                    | 3         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 79        | 10.26%  |
| 5.4.0    | 55        | 7.14%   |
| 4.9.60   | 44        | 5.71%   |
| 4.9.20   | 30        | 3.9%    |
| 5.15.0   | 27        | 3.51%   |
| 4.9.124  | 25        | 3.25%   |
| 5.10.74  | 21        | 2.73%   |
| 5.8.0    | 20        | 2.6%    |
| 5.11.0   | 20        | 2.6%    |
| 5.0.0    | 17        | 2.21%   |
| 5.3.0    | 16        | 2.08%   |
| 5.10.0   | 16        | 2.08%   |
| 5.13.0   | 15        | 1.95%   |
| 4.9.9    | 14        | 1.82%   |
| 4.1.34   | 14        | 1.82%   |
| 4.9.155  | 13        | 1.69%   |
| 5.19.0   | 12        | 1.56%   |
| 5.10.14  | 12        | 1.56%   |
| 4.1.38   | 12        | 1.56%   |
| 5.4.83   | 11        | 1.43%   |
| 4.9.76   | 10        | 1.3%    |
| 5.15.75  | 8         | 1.04%   |
| 4.18.0   | 8         | 1.04%   |
| 6.1.0    | 7         | 0.91%   |
| 5.9.16   | 7         | 0.91%   |
| 5.4.32   | 7         | 0.91%   |
| 4.9.41   | 7         | 0.91%   |
| 5.16.7   | 6         | 0.78%   |
| 4.13.0   | 6         | 0.78%   |
| 6.2.0    | 5         | 0.65%   |
| 6.1.20   | 5         | 0.65%   |
| 4.19.0   | 5         | 0.65%   |
| 6.1.1    | 4         | 0.52%   |
| 5.15.79  | 4         | 0.52%   |
| 5.14.0   | 4         | 0.52%   |
| 4.9.95   | 4         | 0.52%   |
| 4.9.87   | 4         | 0.52%   |
| 5.10.118 | 3         | 0.39%   |
| 4.8.17   | 3         | 0.39%   |
| 4.1.25   | 3         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 131       | 18.07%  |
| 5.4     | 82        | 11.31%  |
| 4.15    | 79        | 10.9%   |
| 5.10    | 62        | 8.55%   |
| 5.15    | 56        | 7.72%   |
| 4.1     | 29        | 4%      |
| 5.11    | 27        | 3.72%   |
| 5.8     | 24        | 3.31%   |
| 6.1     | 23        | 3.17%   |
| 5.13    | 21        | 2.9%    |
| 5.3     | 19        | 2.62%   |
| 5.19    | 19        | 2.62%   |
| 5.0     | 17        | 2.34%   |
| 6.2     | 16        | 2.21%   |
| 5.9     | 15        | 2.07%   |
| 6.0     | 11        | 1.52%   |
| 5.18    | 10        | 1.38%   |
| 5.16    | 10        | 1.38%   |
| 5.14    | 8         | 1.1%    |
| 4.19    | 8         | 1.1%    |
| 4.18    | 8         | 1.1%    |
| 6.3     | 6         | 0.83%   |
| 5.6     | 6         | 0.83%   |
| 4.13    | 6         | 0.83%   |
| 5.17    | 5         | 0.69%   |
| 4.8     | 5         | 0.69%   |
| 6.4     | 3         | 0.41%   |
| 5.12    | 3         | 0.41%   |
| 4.16    | 3         | 0.41%   |
| 4.14    | 3         | 0.41%   |
| 5.7     | 2         | 0.28%   |
| 5.5     | 2         | 0.28%   |
| 4.17    | 2         | 0.28%   |
| 4.10    | 2         | 0.28%   |
| 5.1     | 1         | 0.14%   |
| 4.4     | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 567       | 91.01%  |
| i686   | 56        | 8.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 177       | 26.58%  |
| KDE4       | 161       | 24.17%  |
| KDE5       | 155       | 23.27%  |
| Unknown    | 52        | 7.81%   |
| XFCE       | 34        | 5.11%   |
| X-Cinnamon | 24        | 3.6%    |
| LXQt       | 20        | 3%      |
| KDE        | 12        | 1.8%    |
| MATE       | 10        | 1.5%    |
| Cinnamon   | 9         | 1.35%   |
| LXDE       | 4         | 0.6%    |
| Pantheon   | 3         | 0.45%   |
| i3         | 2         | 0.3%    |
| sway       | 1         | 0.15%   |
| Deepin     | 1         | 0.15%   |
| Budgie     | 1         | 0.15%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 497       | 78.76%  |
| Wayland | 100       | 15.85%  |
| Unknown | 31        | 4.91%   |
| Tty     | 3         | 0.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 167       | 25.42%  |
| KDM     | 163       | 24.81%  |
| SDDM    | 152       | 23.14%  |
| GDM     | 85        | 12.94%  |
| GDM3    | 36        | 5.48%   |
| LightDM | 35        | 5.33%   |
| TDM     | 17        | 2.59%   |
| SLiM    | 1         | 0.15%   |
| GREETD  | 1         | 0.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 240       | 37.5%   |
| ru_RU       | 233       | 36.41%  |
| en_US       | 133       | 20.78%  |
| be_BY       | 9         | 1.41%   |
| C           | 8         | 1.25%   |
| en_GB       | 7         | 1.09%   |
| ru_RU.UTF_8 | 4         | 0.63%   |
| ru_UA       | 3         | 0.47%   |
| cv_RU       | 2         | 0.31%   |
| ru_BY       | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 334       | 53.02%  |
| EFI  | 296       | 46.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 414       | 63.89%  |
| Unknown | 142       | 21.91%  |
| Btrfs   | 55        | 8.49%   |
| Overlay | 28        | 4.32%   |
| Tmpfs   | 3         | 0.46%   |
| Ext3    | 3         | 0.46%   |
| Xfs     | 2         | 0.31%   |
| F2fs    | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 228       | 35.08%  |
| GPT     | 221       | 34%     |
| MBR     | 201       | 30.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 556       | 87.42%  |
| Yes       | 80        | 12.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 436       | 67.91%  |
| Yes       | 206       | 32.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 128       | 20.92%  |
| Lenovo              | 122       | 19.93%  |
| Hewlett-Packard     | 118       | 19.28%  |
| Acer                | 75        | 12.25%  |
| Dell                | 41        | 6.7%    |
| Samsung Electronics | 36        | 5.88%   |
| MSI                 | 15        | 2.45%   |
| Toshiba             | 10        | 1.63%   |
| Timi                | 9         | 1.47%   |
| Sony                | 7         | 1.14%   |
| HONOR               | 5         | 0.82%   |
| Prestigio           | 4         | 0.65%   |
| Packard Bell        | 4         | 0.65%   |
| HUAWEI              | 4         | 0.65%   |
| Apple               | 4         | 0.65%   |
| Intel               | 3         | 0.49%   |
| Fujitsu Siemens     | 3         | 0.49%   |
| Fujitsu             | 3         | 0.49%   |
| Unknown             | 3         | 0.49%   |
| BenQ                | 2         | 0.33%   |
| ViewSonic           | 1         | 0.16%   |
| Valve               | 1         | 0.16%   |
| TECNO               | 1         | 0.16%   |
| Quanta              | 1         | 0.16%   |
| Pegatron            | 1         | 0.16%   |
| Notebook            | 1         | 0.16%   |
| LTD Delovoy Office  | 1         | 0.16%   |
| LG Electronics      | 1         | 0.16%   |
| IBM                 | 1         | 0.16%   |
| HASEE Computer      | 1         | 0.16%   |
| Getac               | 1         | 0.16%   |
| Gateway             | 1         | 0.16%   |
| eMachines           | 1         | 0.16%   |
| Dream Machines      | 1         | 0.16%   |
| DNS                 | 1         | 0.16%   |
| Chuwi               | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo G50-30 80G0                         | 7         | 1.14%   |
| HP Notebook                                | 6         | 0.98%   |
| Acer Extensa 5220                          | 5         | 0.82%   |
| Unknown                                    | 5         | 0.82%   |
| Timi TM1701                                | 4         | 0.65%   |
| Samsung RV413/RV513                        | 4         | 0.65%   |
| Lenovo IdeaPad 320-15IAP 80XR              | 4         | 0.65%   |
| HP ProBook 455 G1                          | 4         | 0.65%   |
| HP ProBook 450 G5                          | 4         | 0.65%   |
| HP Pavilion g6                             | 4         | 0.65%   |
| HP Laptop 15s-eq2xxx                       | 4         | 0.65%   |
| ASUS X540NV                                | 4         | 0.65%   |
| Acer Aspire E1-571G                        | 4         | 0.65%   |
| Lenovo IdeaPad Z570 HuronRiver Platform    | 3         | 0.49%   |
| Lenovo IdeaPad 100-15IBY 80MJ              | 3         | 0.49%   |
| Lenovo G570 20079                          | 3         | 0.49%   |
| Lenovo G500 20236                          | 3         | 0.49%   |
| Lenovo B590 20206                          | 3         | 0.49%   |
| Lenovo B50-30 20382                        | 3         | 0.49%   |
| HP Pavilion dv6                            | 3         | 0.49%   |
| HP Pavilion 15                             | 3         | 0.49%   |
| HP 635                                     | 3         | 0.49%   |
| Dell Inspiron 7577                         | 3         | 0.49%   |
| ASUS ZenBook UX431DA_UM431DA               | 3         | 0.49%   |
| ASUS X550CC                                | 3         | 0.49%   |
| ASUS X541UAK                               | 3         | 0.49%   |
| Acer Aspire V3-571G                        | 3         | 0.49%   |
| Acer Aspire E1-531                         | 3         | 0.49%   |
| Acer Aspire 4810T                          | 3         | 0.49%   |
| Timi TM1613                                | 2         | 0.33%   |
| Samsung R528/R728                          | 2         | 0.33%   |
| Samsung R508                               | 2         | 0.33%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 2         | 0.33%   |
| Samsung 305E4Z/305E5Z/305E7Z               | 2         | 0.33%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 2         | 0.33%   |
| Prestigio Multipad Visconte V              | 2         | 0.33%   |
| MSI MS-N014                                | 2         | 0.33%   |
| MSI GF63 Thin 9SCSR                        | 2         | 0.33%   |
| Lenovo Z710 20250                          | 2         | 0.33%   |
| Lenovo Z50-70 20354                        | 2         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 49        | 8.01%   |
| Lenovo IdeaPad        | 42        | 6.86%   |
| HP ProBook            | 32        | 5.23%   |
| Lenovo ThinkPad       | 28        | 4.58%   |
| HP Pavilion           | 27        | 4.41%   |
| Dell Inspiron         | 25        | 4.08%   |
| ASUS VivoBook         | 24        | 3.92%   |
| Acer Extensa          | 13        | 2.12%   |
| HP Laptop             | 12        | 1.96%   |
| Toshiba Satellite     | 8         | 1.31%   |
| ASUS ZenBook          | 8         | 1.31%   |
| Lenovo G50-30         | 7         | 1.14%   |
| HP EliteBook          | 7         | 1.14%   |
| HP Notebook           | 6         | 0.98%   |
| Lenovo Legion         | 5         | 0.82%   |
| HP 250                | 5         | 0.82%   |
| Dell Vostro           | 5         | 0.82%   |
| Unknown               | 5         | 0.82%   |
| Timi TM1701           | 4         | 0.65%   |
| Samsung RV413         | 4         | 0.65%   |
| Lenovo G580           | 4         | 0.65%   |
| HP Compaq             | 4         | 0.65%   |
| HP 255                | 4         | 0.65%   |
| Dell XPS              | 4         | 0.65%   |
| ASUS X540NV           | 4         | 0.65%   |
| ASUS ROG              | 4         | 0.65%   |
| ASUS ASUS             | 4         | 0.65%   |
| Acer TravelMate       | 4         | 0.65%   |
| Packard Bell EasyNote | 3         | 0.49%   |
| Lenovo G570           | 3         | 0.49%   |
| Lenovo G500           | 3         | 0.49%   |
| Lenovo B590           | 3         | 0.49%   |
| Lenovo B50-30         | 3         | 0.49%   |
| HP Presario           | 3         | 0.49%   |
| HP Mini               | 3         | 0.49%   |
| HP 635                | 3         | 0.49%   |
| ASUS X550CC           | 3         | 0.49%   |
| ASUS X541UAK          | 3         | 0.49%   |
| Acer Swift            | 3         | 0.49%   |
| Acer Nitro            | 3         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 60        | 9.8%    |
| 2011 | 59        | 9.64%   |
| 2012 | 56        | 9.15%   |
| 2017 | 52        | 8.5%    |
| 2018 | 51        | 8.33%   |
| 2020 | 46        | 7.52%   |
| 2019 | 39        | 6.37%   |
| 2010 | 38        | 6.21%   |
| 2021 | 36        | 5.88%   |
| 2009 | 36        | 5.88%   |
| 2015 | 31        | 5.07%   |
| 2014 | 29        | 4.74%   |
| 2008 | 23        | 3.76%   |
| 2016 | 21        | 3.43%   |
| 2007 | 20        | 3.27%   |
| 2022 | 10        | 1.63%   |
| 2006 | 3         | 0.49%   |
| 2005 | 2         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 612       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 572       | 93.01%  |
| Enabled  | 43        | 6.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 612       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 186       | 29.52%  |
| 3.01-4.0    | 178       | 28.25%  |
| 16.01-24.0  | 73        | 11.59%  |
| 8.01-16.0   | 70        | 11.11%  |
| 1.01-2.0    | 64        | 10.16%  |
| 2.01-3.0    | 23        | 3.65%   |
| 32.01-64.0  | 20        | 3.17%   |
| 0.51-1.0    | 13        | 2.06%   |
| 24.01-32.0  | 2         | 0.32%   |
| 64.01-256.0 | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 237       | 33.66%  |
| 0.51-1.0   | 151       | 21.45%  |
| 2.01-3.0   | 138       | 19.6%   |
| 4.01-8.0   | 84        | 11.93%  |
| 3.01-4.0   | 66        | 9.38%   |
| 8.01-16.0  | 15        | 2.13%   |
| 0.01-0.5   | 11        | 1.56%   |
| 24.01-32.0 | 1         | 0.14%   |
| 16.01-24.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 470       | 74.37%  |
| 2      | 143       | 22.63%  |
| 3      | 16        | 2.53%   |
| 0      | 2         | 0.32%   |
| 4      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 375       | 60.39%  |
| Yes       | 246       | 39.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 504       | 82.22%  |
| No        | 109       | 17.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 607       | 99.18%  |
| No        | 5         | 0.82%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 479       | 76.89%  |
| No        | 144       | 23.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Belarus | 612       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Minsk        | 301       | 44.73%  |
| Vitebsk      | 65        | 9.66%   |
| Gomel        | 56        | 8.32%   |
| Mogilev      | 39        | 5.79%   |
| Brest        | 35        | 5.2%    |
| Hrodna       | 33        | 4.9%    |
| Orsha        | 17        | 2.53%   |
| Babruysk     | 17        | 2.53%   |
| Borisov      | 12        | 1.78%   |
| Polatsk      | 8         | 1.19%   |
| Zhodzina     | 6         | 0.89%   |
| Zhlobin      | 6         | 0.89%   |
| Mazyr        | 6         | 0.89%   |
| Lida         | 6         | 0.89%   |
| Bogushevichi | 4         | 0.59%   |
| Salihorsk    | 3         | 0.45%   |
| Klyetsk      | 3         | 0.45%   |
| Drahichyn    | 3         | 0.45%   |
| Baran'       | 3         | 0.45%   |
| Aleksandrovo | 3         | 0.45%   |
| Smalyavichy  | 2         | 0.3%    |
| Slutsk       | 2         | 0.3%    |
| Pinsk        | 2         | 0.3%    |
| Navapolatsk  | 2         | 0.3%    |
| Maladzyechna | 2         | 0.3%    |
| Loshnitsa    | 2         | 0.3%    |
| Krupki       | 2         | 0.3%    |
| Kolodishchi  | 2         | 0.3%    |
| Fedorovka    | 2         | 0.3%    |
| Borovlyany   | 2         | 0.3%    |
| Baranovichi  | 2         | 0.3%    |
| Zaslawye     | 1         | 0.15%   |
| Vilyeyka     | 1         | 0.15%   |
| Vawkavysk    | 1         | 0.15%   |
| Syanno       | 1         | 0.15%   |
| Snitovo      | 1         | 0.15%   |
| Slonim       | 1         | 0.15%   |
| Shklow       | 1         | 0.15%   |
| Rakov        | 1         | 0.15%   |
| Rahachow     | 1         | 0.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 106       | 149    | 13.91%  |
| Seagate                     | 105       | 140    | 13.78%  |
| Samsung Electronics         | 102       | 130    | 13.39%  |
| Toshiba                     | 77        | 99     | 10.1%   |
| Kingston                    | 50        | 62     | 6.56%   |
| Hitachi                     | 48        | 55     | 6.3%    |
| HGST                        | 46        | 57     | 6.04%   |
| SK hynix                    | 35        | 41     | 4.59%   |
| Intel                       | 23        | 44     | 3.02%   |
| SanDisk                     | 19        | 26     | 2.49%   |
| Unknown                     | 18        | 24     | 2.36%   |
| Crucial                     | 12        | 17     | 1.57%   |
| Fujitsu                     | 10        | 17     | 1.31%   |
| Micron Technology           | 9         | 15     | 1.18%   |
| Patriot                     | 8         | 9      | 1.05%   |
| Gigabyte Technology         | 7         | 9      | 0.92%   |
| A-DATA Technology           | 7         | 8      | 0.92%   |
| KingSpec                    | 6         | 12     | 0.79%   |
| Transcend                   | 5         | 7      | 0.66%   |
| SPCC                        | 5         | 7      | 0.66%   |
| Netac                       | 5         | 6      | 0.66%   |
| KIOXIA                      | 5         | 22     | 0.66%   |
| GOODRAM                     | 4         | 4      | 0.52%   |
| Lenovo                      | 3         | 6      | 0.39%   |
| Apple                       | 3         | 3      | 0.39%   |
| XrayDisk                    | 2         | 2      | 0.26%   |
| TO Exter                    | 2         | 3      | 0.26%   |
| Smartbuy                    | 2         | 2      | 0.26%   |
| Silicon Motion              | 2         | 2      | 0.26%   |
| Phison Electronics          | 2         | 2      | 0.26%   |
| OCZ                         | 2         | 2      | 0.26%   |
| LITEONIT                    | 2         | 2      | 0.26%   |
| Lexar                       | 2         | 2      | 0.26%   |
| Kingston Technology Company | 2         | 2      | 0.26%   |
| KingDian                    | 2         | 4      | 0.26%   |
| JMicron Technology          | 2         | 2      | 0.26%   |
| Zheino                      | 1         | 2      | 0.13%   |
| Union Memory                | 1         | 1      | 0.13%   |
| Team                        | 1         | 1      | 0.13%   |
| SSSTC                       | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB            | 26        | 3.32%   |
| Seagate ST1000LM035-1RK172 1TB      | 19        | 2.42%   |
| Seagate ST500LT012-1DG142 500GB     | 17        | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 12        | 1.53%   |
| HGST HTS545050A7E680 500GB          | 11        | 1.4%    |
| Seagate ST9320325AS 320GB           | 10        | 1.28%   |
| Samsung SSD 860 EVO 250GB           | 9         | 1.15%   |
| Kingston SA400S37120G 120GB SSD     | 9         | 1.15%   |
| WDC WD10JPVX-22JC3T0 1TB            | 8         | 1.02%   |
| Toshiba MQ04ABF100 1TB              | 8         | 1.02%   |
| SK hynix NVMe SSD Drive 512GB       | 8         | 1.02%   |
| Samsung NVMe SSD Drive 256GB        | 8         | 1.02%   |
| HGST HTS721010A9E630 1TB            | 8         | 1.02%   |
| Hitachi HTS545050B9A300 500GB       | 7         | 0.89%   |
| Crucial CT120BX500SSD1 120GB        | 7         | 0.89%   |
| Toshiba MQ01ABD100 1TB              | 6         | 0.77%   |
| Toshiba MQ01ABD075 752GB            | 6         | 0.77%   |
| Toshiba MQ01ABD032 320GB            | 6         | 0.77%   |
| Seagate ST9250315AS 250GB           | 6         | 0.77%   |
| Samsung SSD 860 EVO 500GB           | 6         | 0.77%   |
| Hitachi HTS547575A9E384 752GB       | 6         | 0.77%   |
| HGST HTS541010B7E610 1TB            | 6         | 0.77%   |
| HGST HTS541010A9E680 1TB            | 6         | 0.77%   |
| Seagate ST9500325AS 500GB           | 5         | 0.64%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 0.64%   |
| Intel SSDPEKNW512G8H 512GB          | 5         | 0.64%   |
| Hitachi HTS545032B9A300 320GB       | 5         | 0.64%   |
| Hitachi HTS543232A7A384 320GB       | 5         | 0.64%   |
| SK hynix NVMe SSD Drive 256GB       | 4         | 0.51%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 4         | 0.51%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 0.51%   |
| SanDisk NVMe SSD Drive 256GB        | 4         | 0.51%   |
| Samsung SSD 850 EVO 250GB           | 4         | 0.51%   |
| Samsung NVMe SSD Drive 512GB        | 4         | 0.51%   |
| Samsung MZVLQ512HALU-000H1 512GB    | 4         | 0.51%   |
| Samsung HM500JI 500GB               | 4         | 0.51%   |
| Intel SSDPEKNU512GZ 512GB           | 4         | 0.51%   |
| Hitachi HTS547550A9E384 500GB       | 4         | 0.51%   |
| HGST HTS545050B7E660 500GB          | 4         | 0.51%   |
| HGST HTS545050A7E380 500GB          | 4         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 104       | 139    | 27.08%  |
| WDC                 | 92        | 134    | 23.96%  |
| Toshiba             | 70        | 88     | 18.23%  |
| Hitachi             | 48        | 55     | 12.5%   |
| HGST                | 46        | 57     | 11.98%  |
| Samsung Electronics | 11        | 24     | 2.86%   |
| Fujitsu             | 10        | 17     | 2.6%    |
| JMicron Technology  | 2         | 2      | 0.52%   |
| Apple               | 1         | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 41        | 49     | 21.47%  |
| Kingston            | 34        | 41     | 17.8%   |
| Crucial             | 12        | 17     | 6.28%   |
| SanDisk             | 11        | 18     | 5.76%   |
| SK hynix            | 8         | 10     | 4.19%   |
| Patriot             | 8         | 9      | 4.19%   |
| Gigabyte Technology | 7         | 9      | 3.66%   |
| KingSpec            | 6         | 12     | 3.14%   |
| A-DATA Technology   | 6         | 7      | 3.14%   |
| Transcend           | 5         | 7      | 2.62%   |
| SPCC                | 5         | 7      | 2.62%   |
| WDC                 | 4         | 4      | 2.09%   |
| Netac               | 4         | 5      | 2.09%   |
| GOODRAM             | 4         | 4      | 2.09%   |
| Toshiba             | 3         | 3      | 1.57%   |
| Intel               | 3         | 3      | 1.57%   |
| XrayDisk            | 2         | 2      | 1.05%   |
| TO Exter            | 2         | 3      | 1.05%   |
| Smartbuy            | 2         | 2      | 1.05%   |
| OCZ                 | 2         | 2      | 1.05%   |
| LITEONIT            | 2         | 2      | 1.05%   |
| Lexar               | 2         | 2      | 1.05%   |
| KingDian            | 2         | 4      | 1.05%   |
| Zheino              | 1         | 2      | 0.52%   |
| Union Memory        | 1         | 1      | 0.52%   |
| Team                | 1         | 1      | 0.52%   |
| Seagate             | 1         | 1      | 0.52%   |
| SAGE                | 1         | 1      | 0.52%   |
| PNY                 | 1         | 5      | 0.52%   |
| Plextor             | 1         | 1      | 0.52%   |
| OSCOO               | 1         | 1      | 0.52%   |
| OCZ-VERTEX          | 1         | 1      | 0.52%   |
| Micron Technology   | 1         | 1      | 0.52%   |
| LT                  | 1         | 1      | 0.52%   |
| Corsair             | 1         | 3      | 0.52%   |
| China               | 1         | 2      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |
| AMD                 | 1         | 1      | 0.52%   |
| Unknown             | 1         | 1      | 0.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 373       | 517    | 50.75%  |
| SSD     | 180       | 246    | 24.49%  |
| NVMe    | 159       | 231    | 21.63%  |
| MMC     | 18        | 25     | 2.45%   |
| Unknown | 5         | 5      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 472       | 755    | 71.52%  |
| NVMe | 159       | 230    | 24.09%  |
| MMC  | 18        | 25     | 2.73%   |
| SAS  | 11        | 14     | 1.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 377       | 564    | 72.08%  |
| 0.51-1.0   | 144       | 197    | 27.53%  |
| 1.01-2.0   | 2         | 2      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 191       | 28.17%  |
| 101-250        | 168       | 24.78%  |
| 501-1000       | 83        | 12.24%  |
| 1-20           | 72        | 10.62%  |
| 51-100         | 56        | 8.26%   |
| 21-50          | 50        | 7.37%   |
| 1001-2000      | 36        | 5.31%   |
| Unknown        | 15        | 2.21%   |
| 2001-3000      | 4         | 0.59%   |
| More than 3000 | 3         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 311       | 45.74%  |
| 21-50     | 120       | 17.65%  |
| 51-100    | 79        | 11.62%  |
| 101-250   | 74        | 10.88%  |
| 251-500   | 47        | 6.91%   |
| 501-1000  | 24        | 3.53%   |
| Unknown   | 15        | 2.21%   |
| 1001-2000 | 9         | 1.32%   |
| 0         | 1         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB    | 7         | 9      | 5.43%   |
| Seagate ST9320325AS 320GB          | 6         | 7      | 4.65%   |
| HGST HTS545050A7E680 500GB         | 6         | 7      | 4.65%   |
| Toshiba MQ01ABF050 500GB           | 4         | 5      | 3.1%    |
| Seagate ST9250315AS 250GB          | 4         | 4      | 3.1%    |
| Hitachi HTS545050B9A300 500GB      | 4         | 5      | 3.1%    |
| Toshiba MQ01ABD032 320GB           | 3         | 3      | 2.33%   |
| Seagate ST9500420AS 500GB          | 3         | 3      | 2.33%   |
| Seagate ST9500325AS 500GB          | 3         | 4      | 2.33%   |
| Seagate ST500LT012-9WS142 500GB    | 3         | 3      | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 4      | 2.33%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 2.33%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 2         | 6      | 1.55%   |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 2      | 1.55%   |
| Toshiba MK3259GSXP 320GB           | 2         | 3      | 1.55%   |
| Hitachi HTS722010K9SA00 100GB      | 2         | 2      | 1.55%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 2      | 1.55%   |
| Hitachi HTS545025B9A300 250GB      | 2         | 2      | 1.55%   |
| HGST HTS545050A7E380 500GB         | 2         | 2      | 1.55%   |
| WDC WD5000LPVX-60V0TT0 500GB       | 1         | 2      | 0.78%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 0.78%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 0.78%   |
| WDC WD5000BEVT-75A0RT0 500GB       | 1         | 1      | 0.78%   |
| WDC WD3200BEVT-80A0RT0 320GB       | 1         | 2      | 0.78%   |
| WDC WD3200BEVT-60A23T0 320GB       | 1         | 1      | 0.78%   |
| WDC WD3200BEVT-22A0RT0 320GB       | 1         | 1      | 0.78%   |
| WDC WD3200BEKT-75PVMT1 320GB       | 1         | 1      | 0.78%   |
| WDC WD3200BEKT-60F3T1 320GB        | 1         | 1      | 0.78%   |
| WDC WD2500BEVT-35A23T0 250GB       | 1         | 1      | 0.78%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 0.78%   |
| WDC WD2500BEVT-22A23T0 250GB       | 1         | 1      | 0.78%   |
| WDC WD2500BEVT-00A23T0 250GB       | 1         | 1      | 0.78%   |
| WDC WD2500BEKT-60A25T1 250GB       | 1         | 1      | 0.78%   |
| WDC WD10JPVX-60JC3T0 1TB           | 1         | 1      | 0.78%   |
| WDC WD10JPVT-08A1YT2 1TB           | 1         | 1      | 0.78%   |
| Toshiba MK6476GSX 640GB            | 1         | 1      | 0.78%   |
| Toshiba MK5065GSX 500GB            | 1         | 1      | 0.78%   |
| Toshiba MK5055GSX 500GB            | 1         | 2      | 0.78%   |
| Toshiba MK3275GSX 320GB            | 1         | 2      | 0.78%   |
| Toshiba MK3265GSX 320GB            | 1         | 2      | 0.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 39     | 26.36%  |
| Hitachi             | 28        | 32     | 21.71%  |
| WDC                 | 20        | 26     | 15.5%   |
| Toshiba             | 15        | 20     | 11.63%  |
| HGST                | 11        | 12     | 8.53%   |
| Samsung Electronics | 5         | 12     | 3.88%   |
| Fujitsu             | 4         | 6      | 3.1%    |
| SK hynix            | 2         | 2      | 1.55%   |
| Kingston            | 2         | 2      | 1.55%   |
| SanDisk             | 1         | 1      | 0.78%   |
| PNY                 | 1         | 4      | 0.78%   |
| OCZ                 | 1         | 1      | 0.78%   |
| Micron Technology   | 1         | 1      | 0.78%   |
| LITEONIT            | 1         | 1      | 0.78%   |
| KingSpec            | 1         | 6      | 0.78%   |
| Crucial             | 1         | 1      | 0.78%   |
| Unknown             | 1         | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 39     | 29.57%  |
| Hitachi             | 28        | 32     | 24.35%  |
| WDC                 | 20        | 26     | 17.39%  |
| Toshiba             | 15        | 20     | 13.04%  |
| HGST                | 11        | 12     | 9.57%   |
| Fujitsu             | 4         | 6      | 3.48%   |
| Samsung Electronics | 3         | 10     | 2.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 113       | 145    | 88.98%  |
| SSD  | 13        | 21     | 10.24%  |
| NVMe | 1         | 1      | 0.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-80HXZT3 500GB      | 1         | 1      | 20%     |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 20%     |
| Samsung Electronics HM500JI 500GB | 1         | 1      | 20%     |
| HGST HTS545050B7E660 500GB        | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 346       | 556    | 51.11%  |
| Detected | 200       | 296    | 29.54%  |
| Malfunc  | 126       | 167    | 18.61%  |
| Failed   | 5         | 5      | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 453       | 63.8%   |
| AMD                              | 102       | 14.37%  |
| Samsung Electronics              | 52        | 7.32%   |
| SK hynix                         | 27        | 3.8%    |
| SanDisk                          | 18        | 2.54%   |
| Kingston Technology Company      | 18        | 2.54%   |
| Micron Technology                | 8         | 1.13%   |
| Toshiba America Info Systems     | 6         | 0.85%   |
| KIOXIA                           | 5         | 0.7%    |
| Silicon Integrated Systems [SiS] | 3         | 0.42%   |
| Phison Electronics               | 3         | 0.42%   |
| Lenovo                           | 3         | 0.42%   |
| Silicon Motion                   | 2         | 0.28%   |
| Nvidia                           | 2         | 0.28%   |
| JMicron Technology               | 2         | 0.28%   |
| Solid State Storage Technology   | 1         | 0.14%   |
| Silicon Image                    | 1         | 0.14%   |
| O2 Micro                         | 1         | 0.14%   |
| Netac Technology                 | 1         | 0.14%   |
| Apple                            | 1         | 0.14%   |
| ADATA Technology                 | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 66        | 8.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 62        | 8.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 42        | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 34        | 4.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 33        | 4.27%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 26        | 3.36%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 2.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 22        | 2.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 20        | 2.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 19        | 2.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 19        | 2.46%   |
| Samsung NVMe SSD Controller 980                                                  | 18        | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 18        | 2.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 17        | 2.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 1.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 13        | 1.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 1.55%   |
| Intel SSD 660P Series                                                            | 12        | 1.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 1.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 11        | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 11        | 1.42%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 1.29%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 10        | 1.29%   |
| Intel Comet Lake SATA AHCI Controller                                            | 10        | 1.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 1.29%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 9         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 1.16%   |
| SK hynix BC511 NVMe SSD                                                          | 8         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 8         | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 7         | 0.91%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 6         | 0.78%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 6         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 6         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 6         | 0.78%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 6         | 0.78%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 6         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 6         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 5         | 0.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 5         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 488       | 65.59%  |
| NVMe | 160       | 21.51%  |
| IDE  | 63        | 8.47%   |
| RAID | 33        | 4.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 487       | 79.58%  |
| AMD    | 125       | 20.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 2.27%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 14        | 2.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 1.62%   |
| AMD E-450 APU with Radeon HD Graphics         | 10        | 1.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.46%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.14%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 1.14%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 1.14%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 1.14%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 1.14%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 7         | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.14%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.97%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 6         | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 6         | 0.97%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 6         | 0.97%   |
| AMD A4-4300M APU with Radeon HD Graphics      | 6         | 0.97%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 5         | 0.81%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 0.81%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 5         | 0.81%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.81%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 5         | 0.81%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 5         | 0.81%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.81%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 5         | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.81%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 5         | 0.81%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 4         | 0.65%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 4         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 4         | 0.65%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 0.65%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 4         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 100       | 16.26%  |
| Intel Core i7                        | 81        | 13.17%  |
| Intel Core i3                        | 65        | 10.57%  |
| Intel Celeron                        | 62        | 10.08%  |
| Intel Pentium                        | 45        | 7.32%   |
| Other                                | 35        | 5.69%   |
| AMD Ryzen 5                          | 33        | 5.37%   |
| Intel Core 2 Duo                     | 32        | 5.2%    |
| Intel Atom                           | 28        | 4.55%   |
| AMD E                                | 13        | 2.11%   |
| AMD A4                               | 11        | 1.79%   |
| Intel Pentium Dual-Core              | 10        | 1.63%   |
| AMD A6                               | 9         | 1.46%   |
| AMD Ryzen 7                          | 8         | 1.3%    |
| AMD E1                               | 8         | 1.3%    |
| Intel Pentium Silver                 | 6         | 0.98%   |
| AMD Ryzen 3                          | 6         | 0.98%   |
| Intel Pentium Dual                   | 5         | 0.81%   |
| Intel Genuine                        | 5         | 0.81%   |
| Intel Celeron Dual-Core              | 5         | 0.81%   |
| AMD A10                              | 5         | 0.81%   |
| AMD Turion II                        | 4         | 0.65%   |
| AMD Athlon II                        | 4         | 0.65%   |
| AMD Athlon                           | 4         | 0.65%   |
| AMD A8                               | 4         | 0.65%   |
| Intel Core i9                        | 3         | 0.49%   |
| Intel Core 2 Solo                    | 3         | 0.49%   |
| AMD Phenom II                        | 3         | 0.49%   |
| AMD E2                               | 3         | 0.49%   |
| Intel Pentium M                      | 2         | 0.33%   |
| AMD Turion 64 X2 Mobile              | 2         | 0.33%   |
| AMD Ryzen 9                          | 2         | 0.33%   |
| Intel Core m3                        | 1         | 0.16%   |
| Intel Core Duo                       | 1         | 0.16%   |
| Intel Celeron M                      | 1         | 0.16%   |
| AMD V140                             | 1         | 0.16%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.16%   |
| AMD Turion II Ultra Dual-Core Mobile | 1         | 0.16%   |
| AMD Turion II Dual-Core              | 1         | 0.16%   |
| AMD Ryzen 7 PRO                      | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 340       | 55.19%  |
| 4       | 174       | 28.25%  |
| 1       | 39        | 6.33%   |
| 6       | 35        | 5.68%   |
| 8       | 15        | 2.44%   |
| Unknown | 9         | 1.46%   |
| 12      | 2         | 0.32%   |
| 14      | 1         | 0.16%   |
| 10      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 612       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 368       | 59.55%  |
| 1       | 241       | 39%     |
| Unknown | 9         | 1.46%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 582       | 95.1%   |
| 32-bit         | 15        | 2.45%   |
| Unknown        | 15        | 2.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 84        | 13.25%  |
| 0x206a7    | 52        | 8.2%    |
| 0x306a9    | 43        | 6.78%   |
| 0x1067a    | 29        | 4.57%   |
| 0x806ea    | 24        | 3.79%   |
| 0x806c1    | 22        | 3.47%   |
| 0x30678    | 20        | 3.15%   |
| 0x806ec    | 18        | 2.84%   |
| 0x40651    | 16        | 2.52%   |
| 0x906ea    | 14        | 2.21%   |
| 0x106ca    | 14        | 2.21%   |
| 0x406e3    | 13        | 2.05%   |
| 0x05000119 | 13        | 2.05%   |
| 0x6fd      | 12        | 1.89%   |
| 0x306d4    | 12        | 1.89%   |
| 0x306c3    | 12        | 1.89%   |
| 0x506c9    | 11        | 1.74%   |
| 0x010000c8 | 11        | 1.74%   |
| 0x08108102 | 10        | 1.58%   |
| 0x06001119 | 10        | 1.58%   |
| 0x806e9    | 9         | 1.42%   |
| 0x706a1    | 9         | 1.42%   |
| 0x08608103 | 8         | 1.26%   |
| 0x906e9    | 7         | 1.1%    |
| 0x706e5    | 7         | 1.1%    |
| 0x20652    | 7         | 1.1%    |
| 0x106c2    | 6         | 0.95%   |
| 0x10661    | 6         | 0.95%   |
| 0x0a50000c | 6         | 0.95%   |
| 0x0700010f | 6         | 0.95%   |
| 0x6fb      | 5         | 0.79%   |
| 0x406c4    | 5         | 0.79%   |
| 0x30661    | 5         | 0.79%   |
| 0x20655    | 5         | 0.79%   |
| 0x10676    | 5         | 0.79%   |
| 0x08600106 | 5         | 0.79%   |
| 0x08600104 | 5         | 0.79%   |
| 0x07030105 | 5         | 0.79%   |
| 0x06006705 | 5         | 0.79%   |
| 0x906a3    | 4         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 95        | 15.45%  |
| SandyBridge      | 54        | 8.78%   |
| IvyBridge        | 51        | 8.29%   |
| Penryn           | 40        | 6.5%    |
| Haswell          | 34        | 5.53%   |
| Silvermont       | 33        | 5.37%   |
| Core             | 28        | 4.55%   |
| Bonnell          | 24        | 3.9%    |
| TigerLake        | 23        | 3.74%   |
| Skylake          | 22        | 3.58%   |
| Unknown          | 18        | 2.93%   |
| Bobcat           | 16        | 2.6%    |
| Zen 2            | 15        | 2.44%   |
| K10              | 15        | 2.44%   |
| Zen+             | 14        | 2.28%   |
| Goldmont plus    | 14        | 2.28%   |
| Piledriver       | 13        | 2.11%   |
| Icelake          | 13        | 2.11%   |
| Goldmont         | 13        | 2.11%   |
| Westmere         | 12        | 1.95%   |
| Broadwell        | 12        | 1.95%   |
| Zen 3            | 7         | 1.14%   |
| Excavator        | 7         | 1.14%   |
| Zen              | 6         | 0.98%   |
| Puma             | 6         | 0.98%   |
| Jaguar           | 6         | 0.98%   |
| P6               | 5         | 0.81%   |
| K10 Llano        | 4         | 0.65%   |
| CometLake        | 4         | 0.65%   |
| Alderlake Hybrid | 4         | 0.65%   |
| Nehalem          | 3         | 0.49%   |
| K8 Hammer        | 2         | 0.33%   |
| Tremont          | 1         | 0.16%   |
| K8 & K10 hybrid  | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 439       | 53.6%   |
| Nvidia                           | 195       | 23.81%  |
| AMD                              | 182       | 22.22%  |
| Silicon Integrated Systems [SiS] | 3         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 51        | 5.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 49        | 5.65%   |
| Intel UHD Graphics 620                                                                   | 28        | 3.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 3%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 23        | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 2.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 2.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 1.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 15        | 1.73%   |
| AMD Renoir                                                                               | 15        | 1.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.61%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 14        | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.38%   |
| AMD Lucienne                                                                             | 12        | 1.38%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.27%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 1.15%   |
| Intel HD Graphics 630                                                                    | 10        | 1.15%   |
| Intel HD Graphics 620                                                                    | 10        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.15%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 10        | 1.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.04%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 9         | 1.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 9         | 1.04%   |
| Nvidia GM108M [GeForce MX110]                                                            | 8         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.92%   |
| Intel HD Graphics 500                                                                    | 8         | 0.92%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 8         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                             | 7         | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.81%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 7         | 0.81%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 7         | 0.81%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 7         | 0.81%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 7         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 242       | 39.54%  |
| Intel + Nvidia | 154       | 25.16%  |
| 1 x AMD        | 105       | 17.16%  |
| Intel + AMD    | 42        | 6.86%   |
| 1 x Nvidia     | 30        | 4.9%    |
| 2 x AMD        | 25        | 4.08%   |
| AMD + Nvidia   | 10        | 1.63%   |
| 1 x SiS        | 3         | 0.49%   |
| 2 x Intel      | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 526       | 84.57%  |
| Proprietary | 76        | 12.22%  |
| Unknown     | 20        | 3.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 262       | 41.32%  |
| 1.01-2.0   | 154       | 24.29%  |
| 0.01-0.5   | 126       | 19.87%  |
| 3.01-4.0   | 42        | 6.62%   |
| 0.51-1.0   | 41        | 6.47%   |
| 5.01-6.0   | 6         | 0.95%   |
| 7.01-8.0   | 1         | 0.16%   |
| 2.01-3.0   | 1         | 0.16%   |
| 8.01-16.0  | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 133       | 20.62%  |
| BOE                     | 88        | 13.64%  |
| LG Display              | 85        | 13.18%  |
| Chimei Innolux          | 83        | 12.87%  |
| Samsung Electronics     | 77        | 11.94%  |
| Chi Mei Optoelectronics | 50        | 7.75%   |
| PANDA                   | 15        | 2.33%   |
| Goldstar                | 13        | 2.02%   |
| Dell                    | 13        | 2.02%   |
| LG Philips              | 10        | 1.55%   |
| Lenovo                  | 9         | 1.4%    |
| CPT                     | 9         | 1.4%    |
| HannStar                | 8         | 1.24%   |
| Sharp                   | 6         | 0.93%   |
| Philips                 | 6         | 0.93%   |
| Sony                    | 5         | 0.78%   |
| Hewlett-Packard         | 5         | 0.78%   |
| Apple                   | 5         | 0.78%   |
| Unknown                 | 3         | 0.47%   |
| Iiyama                  | 3         | 0.47%   |
| BenQ                    | 3         | 0.47%   |
| ViewSonic               | 2         | 0.31%   |
| LGD                     | 2         | 0.31%   |
| Valve                   | 1         | 0.16%   |
| Seiko/Epson             | 1         | 0.16%   |
| Quanta Display          | 1         | 0.16%   |
| PCL                     | 1         | 0.16%   |
| MiTAC                   | 1         | 0.16%   |
| Mi                      | 1         | 0.16%   |
| Lenovo Group Limited    | 1         | 0.16%   |
| KDC                     | 1         | 0.16%   |
| ITE                     | 1         | 0.16%   |
| InnoLux Display         | 1         | 0.16%   |
| InfoVision              | 1         | 0.16%   |
| CSO                     | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 14        | 2.16%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 12        | 1.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 10        | 1.54%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 1.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 7         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.93%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.93%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 6         | 0.93%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 6         | 0.93%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 6         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 5         | 0.77%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 5         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 5         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.77%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 5         | 0.77%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.77%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 5         | 0.77%   |
| AU Optronics LCD Monitor AUO47EC 1366x768 344x193mm 15.5-inch            | 5         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.77%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 5         | 0.77%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.62%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 4         | 0.62%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 4         | 0.62%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 4         | 0.62%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 3         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 3         | 0.46%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 3         | 0.46%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 3         | 0.46%   |
| LG Display LCD Monitor LGD03D5 1366x768 345x194mm 15.6-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 3         | 0.46%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 3         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 242       | 38.6%   |
| 1920x1080 (FHD)    | 227       | 36.2%   |
| 1600x900 (HD+)     | 40        | 6.38%   |
| 1280x800 (WXGA)    | 28        | 4.47%   |
| 1024x600           | 20        | 3.19%   |
| 3840x2160 (4K)     | 18        | 2.87%   |
| 1440x900 (WXGA+)   | 12        | 1.91%   |
| 2560x1440 (QHD)    | 7         | 1.12%   |
| 2560x1600          | 4         | 0.64%   |
| 1280x1024 (SXGA)   | 4         | 0.64%   |
| 1920x1200 (WUXGA)  | 3         | 0.48%   |
| 1680x1050 (WSXGA+) | 3         | 0.48%   |
| 3840x2400          | 2         | 0.32%   |
| 2880x1800          | 2         | 0.32%   |
| 2288x1287          | 2         | 0.32%   |
| 1360x768           | 2         | 0.32%   |
| 800x1280           | 1         | 0.16%   |
| 3840x1080          | 1         | 0.16%   |
| 3440x1440          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 2560x1080          | 1         | 0.16%   |
| 2240x1400          | 1         | 0.16%   |
| 2160x1440          | 1         | 0.16%   |
| 2048x1536          | 1         | 0.16%   |
| 1680x945           | 1         | 0.16%   |
| 1024x768 (XGA)     | 1         | 0.16%   |
| Unknown            | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 382       | 59.22%  |
| 17      | 63        | 9.77%   |
| 13      | 47        | 7.29%   |
| 14      | 40        | 6.2%    |
| 10      | 20        | 3.1%    |
| 23      | 14        | 2.17%   |
| 24      | 12        | 1.86%   |
| 21      | 11        | 1.71%   |
| 16      | 9         | 1.4%    |
| Unknown | 8         | 1.24%   |
| 27      | 7         | 1.09%   |
| 11      | 5         | 0.78%   |
| 72      | 3         | 0.47%   |
| 18      | 3         | 0.47%   |
| 12      | 3         | 0.47%   |
| 142     | 2         | 0.31%   |
| 40      | 2         | 0.31%   |
| 34      | 2         | 0.31%   |
| 31      | 2         | 0.31%   |
| 20      | 2         | 0.31%   |
| 54      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 22      | 1         | 0.16%   |
| 19      | 1         | 0.16%   |
| 9       | 1         | 0.16%   |
| 8       | 1         | 0.16%   |
| 7       | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 450       | 70.2%   |
| 351-400        | 69        | 10.76%  |
| 201-300        | 50        | 7.8%    |
| 501-600        | 31        | 4.84%   |
| 401-500        | 16        | 2.5%    |
| Unknown        | 8         | 1.25%   |
| 601-700        | 3         | 0.47%   |
| 1501-2000      | 3         | 0.47%   |
| More than 2000 | 2         | 0.31%   |
| 801-900        | 2         | 0.31%   |
| 701-800        | 2         | 0.31%   |
| 101-200        | 2         | 0.31%   |
| 1001-1500      | 2         | 0.31%   |
| 1-100          | 1         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 531       | 87.77%  |
| 16/10   | 55        | 9.09%   |
| Unknown | 7         | 1.16%   |
| 5/4     | 4         | 0.66%   |
| 4/3     | 2         | 0.33%   |
| 21/9    | 2         | 0.33%   |
| 1.00    | 2         | 0.33%   |
| 3/2     | 1         | 0.17%   |
| 0.67    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 386       | 59.84%  |
| 81-90          | 68        | 10.54%  |
| 121-130        | 45        | 6.98%   |
| 201-250        | 28        | 4.34%   |
| 41-50          | 21        | 3.26%   |
| 71-80          | 19        | 2.95%   |
| 131-140        | 15        | 2.33%   |
| 301-350        | 8         | 1.24%   |
| Unknown        | 8         | 1.24%   |
| More than 1000 | 7         | 1.09%   |
| 251-300        | 7         | 1.09%   |
| 151-200        | 6         | 0.93%   |
| 141-150        | 6         | 0.93%   |
| 51-60          | 5         | 0.78%   |
| 351-500        | 4         | 0.62%   |
| 111-120        | 4         | 0.62%   |
| 61-70          | 3         | 0.47%   |
| 1-40           | 2         | 0.31%   |
| 501-1000       | 2         | 0.31%   |
| 91-100         | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 261       | 40.97%  |
| 121-160       | 214       | 33.59%  |
| 51-100        | 110       | 17.27%  |
| 161-240       | 22        | 3.45%   |
| More than 240 | 12        | 1.88%   |
| 1-50          | 10        | 1.57%   |
| Unknown       | 8         | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 549       | 88.41%  |
| 2     | 54        | 8.7%    |
| 0     | 14        | 2.25%   |
| 3     | 4         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 356       | 35.92%  |
| Qualcomm Atheros                  | 222       | 22.4%   |
| Intel                             | 201       | 20.28%  |
| Broadcom                          | 102       | 10.29%  |
| Marvell Technology Group          | 25        | 2.52%   |
| Ralink                            | 21        | 2.12%   |
| Broadcom Limited                  | 14        | 1.41%   |
| MediaTek                          | 8         | 0.81%   |
| TP-Link                           | 5         | 0.5%    |
| JMicron Technology                | 4         | 0.4%    |
| Huawei Technologies               | 4         | 0.4%    |
| Sierra Wireless                   | 3         | 0.3%    |
| Ralink Technology                 | 3         | 0.3%    |
| Qualcomm                          | 3         | 0.3%    |
| Attansic Technology               | 3         | 0.3%    |
| Hewlett-Packard                   | 2         | 0.2%    |
| Fibocom                           | 2         | 0.2%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.1%    |
| Xiaomi                            | 1         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.1%    |
| Samsung Electronics               | 1         | 0.1%    |
| Philips (or NXP)                  | 1         | 0.1%    |
| Nvidia                            | 1         | 0.1%    |
| Mercucys                          | 1         | 0.1%    |
| Lenovo                            | 1         | 0.1%    |
| Ericsson Business Mobile Networks | 1         | 0.1%    |
| D-Link                            | 1         | 0.1%    |
| ASIX Electronics                  | 1         | 0.1%    |
| Aquantia                          | 1         | 0.1%    |
| Apple                             | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 220       | 19.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 96        | 8.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 4.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 3.64%   |
| Intel Wireless 8265 / 8275                                              | 38        | 3.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 3.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 2.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 2.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.73%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.65%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 1.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.21%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 12        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 11        | 0.95%   |
| Intel Wireless 7265                                                     | 9         | 0.78%   |
| Intel Wireless 7260                                                     | 9         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 8         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 7         | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 7         | 0.61%   |
| Intel WiFi Link 5100                                                    | 7         | 0.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.52%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.52%   |
| Intel Wireless 8260                                                     | 6         | 0.52%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 6         | 0.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 6         | 0.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 5         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 198       | 31.13%  |
| Qualcomm Atheros                  | 192       | 30.19%  |
| Realtek Semiconductor             | 115       | 18.08%  |
| Broadcom                          | 76        | 11.95%  |
| Ralink                            | 21        | 3.3%    |
| MediaTek                          | 8         | 1.26%   |
| Broadcom Limited                  | 8         | 1.26%   |
| TP-Link                           | 3         | 0.47%   |
| Sierra Wireless                   | 3         | 0.47%   |
| Ralink Technology                 | 3         | 0.47%   |
| Qualcomm                          | 2         | 0.31%   |
| Fibocom                           | 2         | 0.31%   |
| Philips (or NXP)                  | 1         | 0.16%   |
| Mercucys                          | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |
| D-Link                            | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 8.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 42        | 6.57%   |
| Intel Wireless 8265 / 8275                                              | 38        | 5.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 5.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 32        | 5.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 26        | 4.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 3.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 3.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 3.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 19        | 2.97%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 2.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 2.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 2.19%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 2.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 2.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 1.88%   |
| Intel Wireless 7265                                                     | 9         | 1.41%   |
| Intel Wireless 7260                                                     | 9         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 7         | 1.1%    |
| Intel WiFi Link 5100                                                    | 7         | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6         | 0.94%   |
| Intel Wireless 8260                                                     | 6         | 0.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 6         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.78%   |
| Intel Centrino Wireless-N 130                                           | 5         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.63%   |
| Intel Wireless 3165                                                     | 4         | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.63%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.63%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 323       | 63.33%  |
| Qualcomm Atheros                 | 61        | 11.96%  |
| Broadcom                         | 38        | 7.45%   |
| Intel                            | 36        | 7.06%   |
| Marvell Technology Group         | 25        | 4.9%    |
| Broadcom Limited                 | 6         | 1.18%   |
| JMicron Technology               | 4         | 0.78%   |
| Attansic Technology              | 3         | 0.59%   |
| TP-Link                          | 2         | 0.39%   |
| Huawei Technologies              | 2         | 0.39%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.2%    |
| Xiaomi                           | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Samsung Electronics              | 1         | 0.2%    |
| Qualcomm                         | 1         | 0.2%    |
| Nvidia                           | 1         | 0.2%    |
| Lenovo                           | 1         | 0.2%    |
| ASIX Electronics                 | 1         | 0.2%    |
| Aquantia                         | 1         | 0.2%    |
| Apple                            | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 220       | 42.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 96        | 18.75%  |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 2.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 11        | 2.15%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 8         | 1.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 1.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 7         | 1.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 1.17%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 1.17%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 6         | 1.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 0.98%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.78%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 0.78%   |
| Intel 82566MM Gigabit Network Connection                                       | 4         | 0.78%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.59%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.59%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 3         | 0.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.59%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 3         | 0.59%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.59%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 0.59%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.39%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.39%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.39%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 2         | 0.39%   |
| Intel WiMAX Connection 2400m                                                   | 2         | 0.39%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.39%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.39%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 607       | 54.54%  |
| Ethernet | 502       | 45.1%   |
| Modem    | 3         | 0.27%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 536       | 81.71%  |
| Ethernet | 120       | 18.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 485       | 79.25%  |
| 1     | 119       | 19.44%  |
| 0     | 6         | 0.98%   |
| 3     | 2         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 602       | 97.57%  |
| Yes  | 15        | 2.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 162       | 33.47%  |
| Realtek Semiconductor           | 76        | 15.7%   |
| Qualcomm Atheros Communications | 62        | 12.81%  |
| IMC Networks                    | 32        | 6.61%   |
| Broadcom                        | 31        | 6.4%    |
| Lite-On Technology              | 27        | 5.58%   |
| Foxconn / Hon Hai               | 24        | 4.96%   |
| Ralink                          | 15        | 3.1%    |
| Foxconn International           | 10        | 2.07%   |
| ASUSTek Computer                | 9         | 1.86%   |
| Toshiba                         | 7         | 1.45%   |
| Hewlett-Packard                 | 7         | 1.45%   |
| Ralink Technology               | 3         | 0.62%   |
| Apple                           | 3         | 0.62%   |
| Taiyo Yuden                     | 2         | 0.41%   |
| Realtek                         | 2         | 0.41%   |
| Qcom                            | 2         | 0.41%   |
| MediaTek                        | 2         | 0.41%   |
| Dell                            | 2         | 0.41%   |
| Cambridge Silicon Radio         | 2         | 0.41%   |
| USI                             | 1         | 0.21%   |
| Micro Star International        | 1         | 0.21%   |
| Chicony Electronics             | 1         | 0.21%   |
| Alps Electric                   | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 69        | 14.23%  |
| Realtek Bluetooth Radio                           | 54        | 11.13%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 34        | 7.01%   |
| Intel AX201 Bluetooth                             | 29        | 5.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 20        | 4.12%   |
| Qualcomm Atheros  Bluetooth Device                | 18        | 3.71%   |
| Ralink RT3290 Bluetooth                           | 15        | 3.09%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 15        | 3.09%   |
| Intel AX200 Bluetooth                             | 14        | 2.89%   |
| Realtek  Bluetooth 4.2 Adapter                    | 12        | 2.47%   |
| Lite-On Bluetooth Device                          | 10        | 2.06%   |
| Foxconn International BCM43142A0 Bluetooth module | 10        | 2.06%   |
| Foxconn / Hon Hai Bluetooth Device                | 10        | 2.06%   |
| IMC Networks Bluetooth Radio                      | 9         | 1.86%   |
| IMC Networks Bluetooth Device                     | 8         | 1.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 8         | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                  | 7         | 1.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 7         | 1.44%   |
| Broadcom BCM2070 Bluetooth Device                 | 7         | 1.44%   |
| Qualcomm Atheros Bluetooth                        | 6         | 1.24%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 1.24%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 6         | 1.24%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 6         | 1.24%   |
| Realtek RTL8723B Bluetooth                        | 5         | 1.03%   |
| Realtek RTL8821A Bluetooth                        | 4         | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 4         | 0.82%   |
| Broadcom BCM2045 Bluetooth                        | 4         | 0.82%   |
| Toshiba RT Bluetooth Radio                        | 3         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 3         | 0.62%   |
| IMC Networks Wireless_Device                      | 3         | 0.62%   |
| IMC Networks Bluetooth USB Host Controller        | 3         | 0.62%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 0.62%   |
| Foxconn / Hon Hai BCM43142A0                      | 3         | 0.62%   |
| Foxconn / Hon Hai BCM20702A0                      | 3         | 0.62%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]  | 3         | 0.62%   |
| ASUS BT-270 Bluetooth Adapter                     | 3         | 0.62%   |
| ASUS BT-253 Bluetooth Adapter                     | 3         | 0.62%   |
| Toshiba Integrated Bluetooth HCI                  | 2         | 0.41%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)           | 2         | 0.41%   |
| Realtek 802.11ac WLAN Adapter                     | 2         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 475       | 67.86%  |
| AMD                              | 141       | 20.14%  |
| Nvidia                           | 59        | 8.43%   |
| Logitech                         | 4         | 0.57%   |
| Silicon Integrated Systems [SiS] | 3         | 0.43%   |
| JMTek                            | 3         | 0.43%   |
| C-Media Electronics              | 3         | 0.43%   |
| Generalplus Technology           | 2         | 0.29%   |
| Conexant Systems                 | 2         | 0.29%   |
| Texas Instruments                | 1         | 0.14%   |
| Tenx Technology                  | 1         | 0.14%   |
| Kingston Technology              | 1         | 0.14%   |
| GYROCOM C&C                      | 1         | 0.14%   |
| GN Netcom                        | 1         | 0.14%   |
| ESS Technology                   | 1         | 0.14%   |
| Creative Labs                    | 1         | 0.14%   |
| Apple                            | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 68        | 7.88%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 55        | 6.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 54        | 6.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 38        | 4.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 4.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 33        | 3.82%   |
| AMD FCH Azalia Controller                                                                         | 32        | 3.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 3.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 27        | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 22        | 2.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 21        | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 20        | 2.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 2.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 1.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 1.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 13        | 1.51%   |
| AMD Wrestler HDMI Audio                                                                           | 13        | 1.51%   |
| AMD Trinity HDMI Audio Controller                                                                 | 13        | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 1.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 1.39%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 1.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 1.39%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 7         | 0.81%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 7         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 0.81%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 6         | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 139       | 25.55%  |
| SK hynix              | 102       | 18.75%  |
| Kingston              | 65        | 11.95%  |
| Unknown               | 61        | 11.21%  |
| Micron Technology     | 53        | 9.74%   |
| Elpida                | 22        | 4.04%   |
| Crucial               | 22        | 4.04%   |
| Ramaxel Technology    | 17        | 3.13%   |
| Nanya Technology      | 14        | 2.57%   |
| A-DATA Technology     | 10        | 1.84%   |
| ASint Technology      | 6         | 1.1%    |
| Transcend             | 5         | 0.92%   |
| Corsair               | 4         | 0.74%   |
| 48spaces              | 4         | 0.74%   |
| Unknown (ABCD)        | 2         | 0.37%   |
| Team                  | 2         | 0.37%   |
| Apacer                | 2         | 0.37%   |
| Wilk                  | 1         | 0.18%   |
| Silicon Power         | 1         | 0.18%   |
| SHARETRONIC           | 1         | 0.18%   |
| Qumo                  | 1         | 0.18%   |
| Qimonda               | 1         | 0.18%   |
| PNY                   | 1         | 0.18%   |
| Patriot               | 1         | 0.18%   |
| Kllisre               | 1         | 0.18%   |
| Kingmax Semiconductor | 1         | 0.18%   |
| Kingmax               | 1         | 0.18%   |
| Goldkey               | 1         | 0.18%   |
| GeIL                  | 1         | 0.18%   |
| G.Skill               | 1         | 0.18%   |
| Unknown               | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 12        | 2.04%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 10        | 1.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 8         | 1.36%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 8         | 1.36%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 8         | 1.36%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                  | 7         | 1.19%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 6         | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 6         | 1.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 6         | 1.02%   |
| Kingston RAM ACR16D3LS1NGG/4G 4096MB SODIMM DDR3 1600MT/s                 | 6         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 5         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 5         | 0.85%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 5         | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s                  | 5         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 5         | 0.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 5         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 4         | 0.68%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 4         | 0.68%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s                    | 4         | 0.68%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 4         | 0.68%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                           | 4         | 0.68%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 4         | 0.68%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s                     | 4         | 0.68%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 4         | 0.68%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s                      | 4         | 0.68%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                      | 4         | 0.68%   |
| Kingston RAM 99U5469-070.A00LF 4GB SODIMM DDR3 1600MT/s                   | 4         | 0.68%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 4         | 0.68%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 3         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                             | 3         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 3         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s                 | 3         | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 0.51%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                            | 3         | 0.51%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                     | 3         | 0.51%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM DDR3 1334MT/s                     | 3         | 0.51%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.51%   |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s                     | 3         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 215       | 47.57%  |
| DDR4    | 138       | 30.53%  |
| DDR2    | 40        | 8.85%   |
| SDRAM   | 25        | 5.53%   |
| LPDDR4  | 15        | 3.32%   |
| Unknown | 9         | 1.99%   |
| DRAM    | 4         | 0.88%   |
| DDR     | 3         | 0.66%   |
| LPDDR3  | 2         | 0.44%   |
| LPDDR5  | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 427       | 95.53%  |
| Row Of Chips | 19        | 4.25%   |
| DIMM         | 1         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 203       | 38.45%  |
| 2048  | 126       | 23.86%  |
| 8192  | 106       | 20.08%  |
| 16384 | 53        | 10.04%  |
| 1024  | 32        | 6.06%   |
| 512   | 5         | 0.95%   |
| 32768 | 3         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 141       | 28.66%  |
| 2667    | 62        | 12.6%   |
| 3200    | 57        | 11.59%  |
| 1334    | 41        | 8.33%   |
| 2400    | 27        | 5.49%   |
| 667     | 27        | 5.49%   |
| 1333    | 26        | 5.28%   |
| Unknown | 18        | 3.66%   |
| 800     | 15        | 3.05%   |
| 4199    | 14        | 2.85%   |
| 1067    | 12        | 2.44%   |
| 3266    | 8         | 1.63%   |
| 2133    | 8         | 1.63%   |
| 2048    | 7         | 1.42%   |
| 1867    | 6         | 1.22%   |
| 4267    | 5         | 1.02%   |
| 533     | 4         | 0.81%   |
| 1066    | 3         | 0.61%   |
| 8400    | 2         | 0.41%   |
| 4266    | 2         | 0.41%   |
| 333     | 2         | 0.41%   |
| 65535   | 1         | 0.2%    |
| 6400    | 1         | 0.2%    |
| 1866    | 1         | 0.2%    |
| 1639    | 1         | 0.2%    |
| 400     | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Seiko Epson         | 1         | 20%     |
| Ricoh               | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L365 Series | 1         | 20%     |
| Samsung SCX-4300 Series | 1         | 20%     |
| Samsung Laser Printer   | 1         | 20%     |
| Ricoh SP 210SU          | 1         | 20%     |
| Canon LBP6020           | 1         | 20%     |

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
| Chicony Electronics                    | 140       | 25.04%  |
| IMC Networks                           | 85        | 15.21%  |
| Quanta                                 | 35        | 6.26%   |
| Bison Electronics                      | 34        | 6.08%   |
| Realtek Semiconductor                  | 32        | 5.72%   |
| Suyin                                  | 31        | 5.55%   |
| Sunplus Innovation Technology          | 28        | 5.01%   |
| Syntek                                 | 23        | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 3.94%   |
| Silicon Motion                         | 21        | 3.76%   |
| Lite-On Technology                     | 19        | 3.4%    |
| Microdia                               | 14        | 2.5%    |
| Z-Star Microelectronics                | 11        | 1.97%   |
| Alcor Micro                            | 10        | 1.79%   |
| Apple                                  | 9         | 1.61%   |
| Acer                                   | 8         | 1.43%   |
| Luxvisions Innotech Limited            | 6         | 1.07%   |
| Logitech                               | 5         | 0.89%   |
| Samsung Electronics                    | 3         | 0.54%   |
| Primax Electronics                     | 3         | 0.54%   |
| Lenovo                                 | 3         | 0.54%   |
| Importek                               | 3         | 0.54%   |
| DigiTech                               | 3         | 0.54%   |
| SunplusIT                              | 2         | 0.36%   |
| Ricoh                                  | 2         | 0.36%   |
| Sonix Technology                       | 1         | 0.18%   |
| Shine-optics                           | 1         | 0.18%   |
| Pixart Imaging                         | 1         | 0.18%   |
| Intel                                  | 1         | 0.18%   |
| Genesys Logic                          | 1         | 0.18%   |
| Arkmicro Technologies                  | 1         | 0.18%   |
| ALi                                    | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                         | 29        | 5.18%   |
| Chicony Integrated Camera                                                  | 16        | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 14        | 2.5%    |
| Chicony USB2.0 VGA UVC WebCam                                              | 12        | 2.14%   |
| Chicony HD WebCam                                                          | 12        | 2.14%   |
| Sunplus HD WebCam                                                          | 11        | 1.96%   |
| Realtek Integrated_Webcam_HD                                               | 11        | 1.96%   |
| Bison Lenovo EasyCamera                                                    | 11        | 1.96%   |
| IMC Networks Integrated Camera                                             | 10        | 1.79%   |
| Chicony Lenovo EasyCamera                                                  | 10        | 1.79%   |
| Bison Lenovo Integrated Webcam                                             | 10        | 1.79%   |
| Syntek Integrated Camera                                                   | 9         | 1.61%   |
| Syntek EasyCamera                                                          | 7         | 1.25%   |
| Microdia Integrated_Webcam_HD                                              | 6         | 1.07%   |
| Chicony USB2.0 HD UVC WebCam                                               | 6         | 1.07%   |
| Chicony EasyCamera                                                         | 6         | 1.07%   |
| Syntek Lenovo EasyCamera                                                   | 5         | 0.89%   |
| Suyin HP TrueVision HD                                                     | 5         | 0.89%   |
| Silicon Motion WebCam SC-0311139N                                          | 5         | 0.89%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.89%   |
| Quanta HP HD Camera                                                        | 5         | 0.89%   |
| Quanta HD Webcam                                                           | 5         | 0.89%   |
| Lite-On Integrated Camera                                                  | 5         | 0.89%   |
| Lite-On HP HD Camera                                                       | 5         | 0.89%   |
| IMC Networks UVC VGA Webcam                                                | 5         | 0.89%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 5         | 0.89%   |
| IMC Networks Integrated Webcam                                             | 5         | 0.89%   |
| Chicony HP HD Camera                                                       | 5         | 0.89%   |
| Alcor Micro USB 2.0 Camera                                                 | 5         | 0.89%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 0.71%   |
| Silicon Motion WebCam SC-03FFL11939N                                       | 4         | 0.71%   |
| Lite-On HP HD Webcam                                                       | 4         | 0.71%   |
| Chicony VGA Webcam                                                         | 4         | 0.71%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 0.71%   |
| Chicony HP Truevision HD                                                   | 4         | 0.71%   |
| Chicony HD WebCam (Acer)                                                   | 4         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 4         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 4         | 0.71%   |
| Bison Integrated Camera                                                    | 4         | 0.71%   |
| Z-Star WebCam SC-03FFL11739P                                               | 3         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 28.57%  |
| Synaptics                  | 14        | 20%     |
| Elan Microelectronics      | 12        | 17.14%  |
| Shenzhen Goodix Technology | 11        | 15.71%  |
| AuthenTec                  | 6         | 8.57%   |
| STMicroelectronics         | 3         | 4.29%   |
| Upek                       | 2         | 2.86%   |
| LighTuning Technology      | 2         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 9         | 12.86%  |
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 8.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 5.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 5.71%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.29%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 4.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.29%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 4.29%   |
| Elan ELAN:ARM-M4                                                           | 3         | 4.29%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.86%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.86%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.86%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.43%   |
| Validity Sensors VFS491                                                    | 1         | 1.43%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.43%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.43%   |
| Synaptics UWP WBDI                                                         | 1         | 1.43%   |
| Synaptics  WBDI                                                            | 1         | 1.43%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.43%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.43%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.43%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.43%   |
| AuthenTec AES2810                                                          | 1         | 1.43%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.43%   |
| AuthenTec AES1600                                                          | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 7         | 50%     |
| Lenovo      | 4         | 28.57%  |
| Broadcom    | 2         | 14.29%  |
| Upek        | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 433       | 69.06%  |
| 1     | 160       | 25.52%  |
| 2     | 27        | 4.31%   |
| 3     | 6         | 0.96%   |
| 4     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 81        | 36.32%  |
| Fingerprint reader       | 68        | 30.49%  |
| Bluetooth                | 17        | 7.62%   |
| Net/wireless             | 14        | 6.28%   |
| Chipcard                 | 11        | 4.93%   |
| Multimedia controller    | 9         | 4.04%   |
| Camera                   | 7         | 3.14%   |
| Communication controller | 6         | 2.69%   |
| Storage                  | 4         | 1.79%   |
| Card reader              | 2         | 0.9%    |
| Sound                    | 1         | 0.45%   |
| Net/ethernet             | 1         | 0.45%   |
| Modem                    | 1         | 0.45%   |
| Flash memory             | 1         | 0.45%   |


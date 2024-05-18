Linux in Iran - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Iran.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Iran/Desktop/README.md) and [notebooks](/Location/Iran/Notebook/README.md).

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

Total: 1067

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 1015                 | Notebook    | [b5f6b13138](https://linux-hardware.org/?probe=b5f6b13138) | May 07, 2024 |
| Dell          | 0215PR A02                  | Desktop     | [ff480889b4](https://linux-hardware.org/?probe=ff480889b4) | May 07, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [3206e427b1](https://linux-hardware.org/?probe=3206e427b1) | May 07, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [3d1643b2c5](https://linux-hardware.org/?probe=3d1643b2c5) | May 06, 2024 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [4a361a3420](https://linux-hardware.org/?probe=4a361a3420) | May 06, 2024 |
| HP            | 83DD                        | Mini pc     | [c20e13567a](https://linux-hardware.org/?probe=c20e13567a) | May 04, 2024 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [dd201d321b](https://linux-hardware.org/?probe=dd201d321b) | May 03, 2024 |
| HP            | ProBook 650 G3              | Notebook    | [e2f71d285f](https://linux-hardware.org/?probe=e2f71d285f) | Apr 28, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [f7d0515f40](https://linux-hardware.org/?probe=f7d0515f40) | Apr 26, 2024 |
| HP            | ZBook 17 G3                 | Notebook    | [05ef86a1b6](https://linux-hardware.org/?probe=05ef86a1b6) | Apr 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [ec99c46757](https://linux-hardware.org/?probe=ec99c46757) | Apr 25, 2024 |
| Dell          | Latitude E6440              | Notebook    | [84566c2460](https://linux-hardware.org/?probe=84566c2460) | Apr 24, 2024 |
| Dell          | Latitude E6440              | Notebook    | [3b5213b70a](https://linux-hardware.org/?probe=3b5213b70a) | Apr 24, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [488c5e3d42](https://linux-hardware.org/?probe=488c5e3d42) | Apr 23, 2024 |
| Dell          | Precision 7720              | Notebook    | [53cebf5b16](https://linux-hardware.org/?probe=53cebf5b16) | Apr 20, 2024 |
| HP            | 339A                        | Desktop     | [8cb48fe045](https://linux-hardware.org/?probe=8cb48fe045) | Apr 19, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [76e18e23c3](https://linux-hardware.org/?probe=76e18e23c3) | Apr 19, 2024 |
| ASUSTek       | H61M-C                      | Desktop     | [a0e36b103b](https://linux-hardware.org/?probe=a0e36b103b) | Apr 10, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [35d9b4afce](https://linux-hardware.org/?probe=35d9b4afce) | Apr 07, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [490787ceee](https://linux-hardware.org/?probe=490787ceee) | Apr 07, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [cf5333f4e5](https://linux-hardware.org/?probe=cf5333f4e5) | Apr 06, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [4eef9d4799](https://linux-hardware.org/?probe=4eef9d4799) | Apr 05, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [1d1175f274](https://linux-hardware.org/?probe=1d1175f274) | Apr 04, 2024 |
| HP            | Pro x2 612 G2               | Tablet      | [78020fe4fb](https://linux-hardware.org/?probe=78020fe4fb) | Apr 04, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [becc45e734](https://linux-hardware.org/?probe=becc45e734) | Apr 04, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [779b1b8228](https://linux-hardware.org/?probe=779b1b8228) | Apr 04, 2024 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [efd659b2da](https://linux-hardware.org/?probe=efd659b2da) | Apr 01, 2024 |
| Dell          | Latitude 5400               | Notebook    | [7c41e018c9](https://linux-hardware.org/?probe=7c41e018c9) | Mar 28, 2024 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [f51533e204](https://linux-hardware.org/?probe=f51533e204) | Mar 25, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [bb3d04acc5](https://linux-hardware.org/?probe=bb3d04acc5) | Mar 23, 2024 |
| MSI           | CR610M                      | Notebook    | [7b139fb61c](https://linux-hardware.org/?probe=7b139fb61c) | Mar 23, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [3cab34a6cb](https://linux-hardware.org/?probe=3cab34a6cb) | Mar 23, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [46380bc9fe](https://linux-hardware.org/?probe=46380bc9fe) | Mar 23, 2024 |
| ASUSTek       | X450LD                      | Notebook    | [a3b7b15fa7](https://linux-hardware.org/?probe=a3b7b15fa7) | Mar 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [8b380f5ddd](https://linux-hardware.org/?probe=8b380f5ddd) | Mar 21, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [60437d07d3](https://linux-hardware.org/?probe=60437d07d3) | Mar 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | Notebook    | [9ef0fec665](https://linux-hardware.org/?probe=9ef0fec665) | Mar 18, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [42a5d23a39](https://linux-hardware.org/?probe=42a5d23a39) | Mar 16, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [43b39cedea](https://linux-hardware.org/?probe=43b39cedea) | Mar 16, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [ea5a34f828](https://linux-hardware.org/?probe=ea5a34f828) | Mar 15, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b9dc85b113](https://linux-hardware.org/?probe=b9dc85b113) | Mar 14, 2024 |
| HP            | 1998                        | Desktop     | [e51bd4abc7](https://linux-hardware.org/?probe=e51bd4abc7) | Mar 14, 2024 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [00c46d511e](https://linux-hardware.org/?probe=00c46d511e) | Mar 06, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [b4a202211e](https://linux-hardware.org/?probe=b4a202211e) | Mar 06, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [b4bc485d5e](https://linux-hardware.org/?probe=b4bc485d5e) | Mar 03, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [f176927a8f](https://linux-hardware.org/?probe=f176927a8f) | Mar 02, 2024 |
| Dell          | System XPS L502X            | Notebook    | [c289512484](https://linux-hardware.org/?probe=c289512484) | Feb 29, 2024 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [6df147d26d](https://linux-hardware.org/?probe=6df147d26d) | Feb 27, 2024 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [4510503539](https://linux-hardware.org/?probe=4510503539) | Feb 27, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [41dbc538ba](https://linux-hardware.org/?probe=41dbc538ba) | Feb 26, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f760d848e](https://linux-hardware.org/?probe=3f760d848e) | Feb 26, 2024 |
| ASUSTek       | N53SN                       | Notebook    | [121581f984](https://linux-hardware.org/?probe=121581f984) | Feb 23, 2024 |
| ASUSTek       | T303UA                      | Tablet      | [503d57f0a5](https://linux-hardware.org/?probe=503d57f0a5) | Feb 20, 2024 |
| Sony          | VGN-SR35G_B                 | Notebook    | [aaa8b6533c](https://linux-hardware.org/?probe=aaa8b6533c) | Feb 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [e477ab47a2](https://linux-hardware.org/?probe=e477ab47a2) | Feb 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [6afbbfd5d0](https://linux-hardware.org/?probe=6afbbfd5d0) | Feb 19, 2024 |
| I-life        | ZEDNOTE                     | Notebook    | [ceefa317d1](https://linux-hardware.org/?probe=ceefa317d1) | Feb 18, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [0c55d1c68f](https://linux-hardware.org/?probe=0c55d1c68f) | Feb 17, 2024 |
| ASUSTek       | X555YI                      | Notebook    | [9fcad9e566](https://linux-hardware.org/?probe=9fcad9e566) | Feb 16, 2024 |
| MSI           | CR610M                      | Notebook    | [cc4ca57086](https://linux-hardware.org/?probe=cc4ca57086) | Feb 13, 2024 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [98dd82d807](https://linux-hardware.org/?probe=98dd82d807) | Feb 12, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [26a59a1a00](https://linux-hardware.org/?probe=26a59a1a00) | Feb 11, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [3e88e5f74b](https://linux-hardware.org/?probe=3e88e5f74b) | Feb 10, 2024 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [255ad6e265](https://linux-hardware.org/?probe=255ad6e265) | Feb 09, 2024 |
| MSI           | MS-7388                     | Desktop     | [e9a8006742](https://linux-hardware.org/?probe=e9a8006742) | Feb 05, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B7402FBA... | Convertible | [f2b4ad5d19](https://linux-hardware.org/?probe=f2b4ad5d19) | Jan 30, 2024 |
| Acer          | Aspire VN7-571G             | Notebook    | [b5f8437f3c](https://linux-hardware.org/?probe=b5f8437f3c) | Jan 28, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [b6507e7469](https://linux-hardware.org/?probe=b6507e7469) | Jan 25, 2024 |
| Rockchip      | RK3288 Asus Tinker          | Soc         | [b21fbd5b1c](https://linux-hardware.org/?probe=b21fbd5b1c) | Jan 22, 2024 |
| HP            | 82B4                        | Desktop     | [0eca4196b3](https://linux-hardware.org/?probe=0eca4196b3) | Jan 21, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [cd1e18703e](https://linux-hardware.org/?probe=cd1e18703e) | Jan 19, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [f07c9d75f0](https://linux-hardware.org/?probe=f07c9d75f0) | Jan 18, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [3437acb566](https://linux-hardware.org/?probe=3437acb566) | Jan 15, 2024 |
| HP            | ProLiant DL380 Gen9         | Server      | [8f3bf0ff17](https://linux-hardware.org/?probe=8f3bf0ff17) | Jan 15, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [c0f0afd78c](https://linux-hardware.org/?probe=c0f0afd78c) | Jan 14, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [e8e49c344d](https://linux-hardware.org/?probe=e8e49c344d) | Jan 14, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [5654e285db](https://linux-hardware.org/?probe=5654e285db) | Jan 10, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [234e6e24b3](https://linux-hardware.org/?probe=234e6e24b3) | Jan 10, 2024 |
| HP            | 17E2                        | Mini pc     | [a2be55ec15](https://linux-hardware.org/?probe=a2be55ec15) | Jan 09, 2024 |
| Lenovo        | ThinkPad X260 20F5A1AC00    | Notebook    | [b14e96fc5f](https://linux-hardware.org/?probe=b14e96fc5f) | Jan 03, 2024 |
| Dell          | Latitude E5470              | Notebook    | [fdc804210f](https://linux-hardware.org/?probe=fdc804210f) | Jan 01, 2024 |
| Dell          | Vostro 2420                 | Notebook    | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8f6b669800](https://linux-hardware.org/?probe=8f6b669800) | Dec 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f73670f10](https://linux-hardware.org/?probe=1f73670f10) | Dec 27, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [359af07cb2](https://linux-hardware.org/?probe=359af07cb2) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | Desktop     | [b4b91802b5](https://linux-hardware.org/?probe=b4b91802b5) | Dec 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [bad7f51319](https://linux-hardware.org/?probe=bad7f51319) | Dec 18, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c3968eb521](https://linux-hardware.org/?probe=c3968eb521) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [b4bcda5523](https://linux-hardware.org/?probe=b4bcda5523) | Dec 15, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fecb896f9f](https://linux-hardware.org/?probe=fecb896f9f) | Dec 14, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [899db988cc](https://linux-hardware.org/?probe=899db988cc) | Dec 12, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [eed0305500](https://linux-hardware.org/?probe=eed0305500) | Dec 10, 2023 |
| MSI           | CR610M                      | Notebook    | [f182f4595a](https://linux-hardware.org/?probe=f182f4595a) | Dec 10, 2023 |
| Unknown       | Apple MacBook Air (13-in... | Notebook    | [15b9622f09](https://linux-hardware.org/?probe=15b9622f09) | Dec 09, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [ae0afe3e73](https://linux-hardware.org/?probe=ae0afe3e73) | Dec 09, 2023 |
| Unknown       | Apple MacBook Air (13-in... | Notebook    | [28887ed4c5](https://linux-hardware.org/?probe=28887ed4c5) | Dec 09, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d0e32e1ab3](https://linux-hardware.org/?probe=d0e32e1ab3) | Dec 08, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d1ad1e6658](https://linux-hardware.org/?probe=d1ad1e6658) | Dec 08, 2023 |
| HP            | 339A                        | Desktop     | [a114886e67](https://linux-hardware.org/?probe=a114886e67) | Dec 07, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [0e087e0b94](https://linux-hardware.org/?probe=0e087e0b94) | Dec 07, 2023 |
| HP            | 3646h                       | Desktop     | [df62144cda](https://linux-hardware.org/?probe=df62144cda) | Dec 05, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [0c680c33ec](https://linux-hardware.org/?probe=0c680c33ec) | Dec 05, 2023 |
| Acer          | Aspire A715-76G             | Notebook    | [11e0ab5e1b](https://linux-hardware.org/?probe=11e0ab5e1b) | Dec 05, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [a82cdb418c](https://linux-hardware.org/?probe=a82cdb418c) | Dec 01, 2023 |
| MSI           | CR610M                      | Notebook    | [35d23c9d26](https://linux-hardware.org/?probe=35d23c9d26) | Nov 30, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [9fa48c41da](https://linux-hardware.org/?probe=9fa48c41da) | Nov 27, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [746bd8c3d5](https://linux-hardware.org/?probe=746bd8c3d5) | Nov 21, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [aa86ed33d3](https://linux-hardware.org/?probe=aa86ed33d3) | Nov 21, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [5f26bd4798](https://linux-hardware.org/?probe=5f26bd4798) | Nov 21, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [ed1bde2ed6](https://linux-hardware.org/?probe=ed1bde2ed6) | Nov 20, 2023 |
| MSI           | CR610M                      | Notebook    | [66ca456fa1](https://linux-hardware.org/?probe=66ca456fa1) | Nov 19, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [4243816d27](https://linux-hardware.org/?probe=4243816d27) | Nov 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [111e6f3234](https://linux-hardware.org/?probe=111e6f3234) | Nov 16, 2023 |
| HP            | Compaq 6910p                | Notebook    | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [0b16b45e10](https://linux-hardware.org/?probe=0b16b45e10) | Nov 14, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [f307d97867](https://linux-hardware.org/?probe=f307d97867) | Nov 13, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [8599ff1b2c](https://linux-hardware.org/?probe=8599ff1b2c) | Nov 13, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [238ea043b4](https://linux-hardware.org/?probe=238ea043b4) | Nov 10, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [0f6145e565](https://linux-hardware.org/?probe=0f6145e565) | Nov 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8cbd7f579](https://linux-hardware.org/?probe=c8cbd7f579) | Nov 09, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [80fb26e63a](https://linux-hardware.org/?probe=80fb26e63a) | Nov 03, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [555d634638](https://linux-hardware.org/?probe=555d634638) | Nov 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [af854a07c5](https://linux-hardware.org/?probe=af854a07c5) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [fadc897ee2](https://linux-hardware.org/?probe=fadc897ee2) | Oct 31, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [0e14e6c7dc](https://linux-hardware.org/?probe=0e14e6c7dc) | Oct 30, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [23fdd2c31d](https://linux-hardware.org/?probe=23fdd2c31d) | Oct 30, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [f3f325941b](https://linux-hardware.org/?probe=f3f325941b) | Oct 25, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [1b88e8b489](https://linux-hardware.org/?probe=1b88e8b489) | Oct 25, 2023 |
| ASUSTek       | N53SN                       | Notebook    | [1cc18d5c46](https://linux-hardware.org/?probe=1cc18d5c46) | Oct 25, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [b003720f21](https://linux-hardware.org/?probe=b003720f21) | Oct 23, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [6a5182fc9c](https://linux-hardware.org/?probe=6a5182fc9c) | Oct 20, 2023 |
| Dell          | Latitude E5470              | Notebook    | [be8c08b665](https://linux-hardware.org/?probe=be8c08b665) | Oct 18, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [fa78f5938c](https://linux-hardware.org/?probe=fa78f5938c) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [7045758f33](https://linux-hardware.org/?probe=7045758f33) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [21d197e617](https://linux-hardware.org/?probe=21d197e617) | Oct 05, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f0b1db1bfd](https://linux-hardware.org/?probe=f0b1db1bfd) | Oct 03, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [394ad8616c](https://linux-hardware.org/?probe=394ad8616c) | Oct 02, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [812367b788](https://linux-hardware.org/?probe=812367b788) | Sep 27, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [8c38084e7e](https://linux-hardware.org/?probe=8c38084e7e) | Sep 27, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [cba55a15ec](https://linux-hardware.org/?probe=cba55a15ec) | Sep 24, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e6bd73a6e1](https://linux-hardware.org/?probe=e6bd73a6e1) | Sep 24, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [169fe58269](https://linux-hardware.org/?probe=169fe58269) | Sep 22, 2023 |
| MSI           | CR610M                      | Notebook    | [5a9d9ba5ae](https://linux-hardware.org/?probe=5a9d9ba5ae) | Sep 22, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [5dae6d6eda](https://linux-hardware.org/?probe=5dae6d6eda) | Sep 21, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [ae062bd5ca](https://linux-hardware.org/?probe=ae062bd5ca) | Sep 21, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [ddf1d6a712](https://linux-hardware.org/?probe=ddf1d6a712) | Sep 20, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [4064a0898f](https://linux-hardware.org/?probe=4064a0898f) | Sep 20, 2023 |
| HP            | 3397                        | Desktop     | [f202c90e23](https://linux-hardware.org/?probe=f202c90e23) | Sep 20, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0602c2deb2](https://linux-hardware.org/?probe=0602c2deb2) | Sep 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [ec5b4aeb84](https://linux-hardware.org/?probe=ec5b4aeb84) | Sep 15, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [db2962124c](https://linux-hardware.org/?probe=db2962124c) | Sep 14, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [cf48b0b959](https://linux-hardware.org/?probe=cf48b0b959) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a68551130a](https://linux-hardware.org/?probe=a68551130a) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3edc89267d](https://linux-hardware.org/?probe=3edc89267d) | Sep 13, 2023 |
| ECS           | A880GM-AD3                  | Desktop     | [828f89ff31](https://linux-hardware.org/?probe=828f89ff31) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [be2af85bb7](https://linux-hardware.org/?probe=be2af85bb7) | Sep 12, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93600fc7c](https://linux-hardware.org/?probe=d93600fc7c) | Sep 11, 2023 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [83ff674ae7](https://linux-hardware.org/?probe=83ff674ae7) | Sep 10, 2023 |
| HP            | 8266                        | Desktop     | [fed6cc89fe](https://linux-hardware.org/?probe=fed6cc89fe) | Sep 09, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [24a7c8a496](https://linux-hardware.org/?probe=24a7c8a496) | Sep 04, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [00a308aa4a](https://linux-hardware.org/?probe=00a308aa4a) | Sep 01, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [10db09006a](https://linux-hardware.org/?probe=10db09006a) | Aug 31, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [2d74d46701](https://linux-hardware.org/?probe=2d74d46701) | Aug 30, 2023 |
| HP            | 83DD                        | Mini pc     | [2955a0b6c5](https://linux-hardware.org/?probe=2955a0b6c5) | Aug 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [641243c308](https://linux-hardware.org/?probe=641243c308) | Aug 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [243b20df85](https://linux-hardware.org/?probe=243b20df85) | Aug 28, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CBA... | Notebook    | [8cbbb0c64a](https://linux-hardware.org/?probe=8cbbb0c64a) | Aug 28, 2023 |
| MSI           | 970A-G46                    | Desktop     | [5b4c3411dc](https://linux-hardware.org/?probe=5b4c3411dc) | Aug 28, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [df71a92503](https://linux-hardware.org/?probe=df71a92503) | Aug 26, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [4f74cc24e0](https://linux-hardware.org/?probe=4f74cc24e0) | Aug 26, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [b9187b37b7](https://linux-hardware.org/?probe=b9187b37b7) | Aug 24, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [7041925c33](https://linux-hardware.org/?probe=7041925c33) | Aug 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c61948c95e](https://linux-hardware.org/?probe=c61948c95e) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [6947635a16](https://linux-hardware.org/?probe=6947635a16) | Aug 18, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dbee57dbed](https://linux-hardware.org/?probe=dbee57dbed) | Aug 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [c24cfbc475](https://linux-hardware.org/?probe=c24cfbc475) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6077ff7606](https://linux-hardware.org/?probe=6077ff7606) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [25f4c96f7b](https://linux-hardware.org/?probe=25f4c96f7b) | Aug 14, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [3048a8eb60](https://linux-hardware.org/?probe=3048a8eb60) | Aug 12, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [2df5a4bd58](https://linux-hardware.org/?probe=2df5a4bd58) | Aug 11, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1bf7b69b0f](https://linux-hardware.org/?probe=1bf7b69b0f) | Aug 11, 2023 |
| Dell          | Latitude E6400              | Notebook    | [f28a234c30](https://linux-hardware.org/?probe=f28a234c30) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [cb8ad3e0fc](https://linux-hardware.org/?probe=cb8ad3e0fc) | Aug 10, 2023 |
| HP            | 8456                        | Desktop     | [fa8ea86591](https://linux-hardware.org/?probe=fa8ea86591) | Aug 08, 2023 |
| Sony          | VGN-FW373D                  | Notebook    | [535f0edf33](https://linux-hardware.org/?probe=535f0edf33) | Aug 04, 2023 |
| Dell          | Latitude E6400              | Notebook    | [9f3cef93ed](https://linux-hardware.org/?probe=9f3cef93ed) | Aug 03, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [79c3c3612b](https://linux-hardware.org/?probe=79c3c3612b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d9db031e65](https://linux-hardware.org/?probe=d9db031e65) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [7ed6a80c20](https://linux-hardware.org/?probe=7ed6a80c20) | Aug 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [96a30f2f21](https://linux-hardware.org/?probe=96a30f2f21) | Jul 27, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [fd2bcebb1d](https://linux-hardware.org/?probe=fd2bcebb1d) | Jul 22, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [daff830182](https://linux-hardware.org/?probe=daff830182) | Jul 21, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [b86a3c24df](https://linux-hardware.org/?probe=b86a3c24df) | Jul 16, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [8a2aeb02b0](https://linux-hardware.org/?probe=8a2aeb02b0) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [adab548264](https://linux-hardware.org/?probe=adab548264) | Jul 13, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [ce2deb4b1d](https://linux-hardware.org/?probe=ce2deb4b1d) | Jul 13, 2023 |
| ASUSTek       | N61Jv                       | Notebook    | [fa3485dbc6](https://linux-hardware.org/?probe=fa3485dbc6) | Jul 13, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [26c6ceb0a6](https://linux-hardware.org/?probe=26c6ceb0a6) | Jul 13, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [779f922cbb](https://linux-hardware.org/?probe=779f922cbb) | Jul 12, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [13ece994a6](https://linux-hardware.org/?probe=13ece994a6) | Jul 09, 2023 |
| Unknown       | CoffeeLake                  | Desktop     | [b3f96a87d5](https://linux-hardware.org/?probe=b3f96a87d5) | Jul 09, 2023 |
| HP            | 18E7                        | Desktop     | [8157fe83c7](https://linux-hardware.org/?probe=8157fe83c7) | Jul 09, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a760e46715](https://linux-hardware.org/?probe=a760e46715) | Jul 08, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1a53ce97b8](https://linux-hardware.org/?probe=1a53ce97b8) | Jul 07, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [465b44efff](https://linux-hardware.org/?probe=465b44efff) | Jul 01, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [826e649d7a](https://linux-hardware.org/?probe=826e649d7a) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [df0ca94515](https://linux-hardware.org/?probe=df0ca94515) | Jun 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [47451d9f30](https://linux-hardware.org/?probe=47451d9f30) | Jun 27, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [d675031e74](https://linux-hardware.org/?probe=d675031e74) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [37e828b0b6](https://linux-hardware.org/?probe=37e828b0b6) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e1678729ff](https://linux-hardware.org/?probe=e1678729ff) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [094d8e8ecf](https://linux-hardware.org/?probe=094d8e8ecf) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a013e4866a](https://linux-hardware.org/?probe=a013e4866a) | Jun 22, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6c766e53cb](https://linux-hardware.org/?probe=6c766e53cb) | Jun 21, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [91e2324734](https://linux-hardware.org/?probe=91e2324734) | Jun 20, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [cd78108f1f](https://linux-hardware.org/?probe=cd78108f1f) | Jun 19, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [eb29f214f3](https://linux-hardware.org/?probe=eb29f214f3) | Jun 17, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [a7728ed657](https://linux-hardware.org/?probe=a7728ed657) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [03c8eed64b](https://linux-hardware.org/?probe=03c8eed64b) | Jun 16, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [9b08f8189d](https://linux-hardware.org/?probe=9b08f8189d) | Jun 15, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [a5cbd2e848](https://linux-hardware.org/?probe=a5cbd2e848) | Jun 14, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9f26d41d53](https://linux-hardware.org/?probe=9f26d41d53) | Jun 14, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [1c33fe3f61](https://linux-hardware.org/?probe=1c33fe3f61) | Jun 12, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [9ac86a512d](https://linux-hardware.org/?probe=9ac86a512d) | Jun 09, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| Sony          | VPCEA45FG                   | Notebook    | [873ca04445](https://linux-hardware.org/?probe=873ca04445) | May 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [c2125f60d2](https://linux-hardware.org/?probe=c2125f60d2) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 80XB     | Convertible | [9e2f0c46ef](https://linux-hardware.org/?probe=9e2f0c46ef) | May 20, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | Notebook    | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [2cbff804d8](https://linux-hardware.org/?probe=2cbff804d8) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [728b1e3209](https://linux-hardware.org/?probe=728b1e3209) | May 03, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [20d436bfa7](https://linux-hardware.org/?probe=20d436bfa7) | May 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a43268d9b](https://linux-hardware.org/?probe=9a43268d9b) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5086f7f4a2](https://linux-hardware.org/?probe=5086f7f4a2) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [dd0a47b6fc](https://linux-hardware.org/?probe=dd0a47b6fc) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [7087295cd7](https://linux-hardware.org/?probe=7087295cd7) | May 01, 2023 |
| ASUSTek       | H110-PLUS                   | Desktop     | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [e37aab534f](https://linux-hardware.org/?probe=e37aab534f) | Apr 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Sony          | VGN-SZ640N                  | Notebook    | [659b01c666](https://linux-hardware.org/?probe=659b01c666) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [f95e411124](https://linux-hardware.org/?probe=f95e411124) | Apr 20, 2023 |
| HP            | ZBook 15                    | Notebook    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| HP            | ZBook 15                    | Notebook    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [110fdee9b2](https://linux-hardware.org/?probe=110fdee9b2) | Apr 10, 2023 |
| Lenovo        | ThinkPad T420 4178A4G       | Notebook    | [206861226d](https://linux-hardware.org/?probe=206861226d) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9e7e969310](https://linux-hardware.org/?probe=9e7e969310) | Apr 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0a028a43f8](https://linux-hardware.org/?probe=0a028a43f8) | Apr 01, 2023 |
| ASUSTek       | X555BP                      | Notebook    | [c7f621e335](https://linux-hardware.org/?probe=c7f621e335) | Apr 01, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [ac6cf948d5](https://linux-hardware.org/?probe=ac6cf948d5) | Mar 27, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [fcd077e70a](https://linux-hardware.org/?probe=fcd077e70a) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e4a88fa14e](https://linux-hardware.org/?probe=e4a88fa14e) | Mar 27, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [30e77255e4](https://linux-hardware.org/?probe=30e77255e4) | Mar 20, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [95ae633abb](https://linux-hardware.org/?probe=95ae633abb) | Mar 19, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [54025a10f5](https://linux-hardware.org/?probe=54025a10f5) | Mar 19, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [5f73fa5db7](https://linux-hardware.org/?probe=5f73fa5db7) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [51ec4d252f](https://linux-hardware.org/?probe=51ec4d252f) | Mar 17, 2023 |
| ASUSTek       | P5P43TD                     | Desktop     | [f2be993036](https://linux-hardware.org/?probe=f2be993036) | Mar 13, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5e4e9bde6f](https://linux-hardware.org/?probe=5e4e9bde6f) | Mar 03, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [7f72d6bba7](https://linux-hardware.org/?probe=7f72d6bba7) | Feb 26, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [d81c35b55b](https://linux-hardware.org/?probe=d81c35b55b) | Feb 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [c6d06c27c7](https://linux-hardware.org/?probe=c6d06c27c7) | Feb 19, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f6276d350a](https://linux-hardware.org/?probe=f6276d350a) | Feb 08, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [1b800ff8c2](https://linux-hardware.org/?probe=1b800ff8c2) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [787543930a](https://linux-hardware.org/?probe=787543930a) | Feb 07, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [a313fa3b83](https://linux-hardware.org/?probe=a313fa3b83) | Feb 02, 2023 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [e64a1e0a5a](https://linux-hardware.org/?probe=e64a1e0a5a) | Jan 31, 2023 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [4427845ac1](https://linux-hardware.org/?probe=4427845ac1) | Jan 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [2b2401b0f0](https://linux-hardware.org/?probe=2b2401b0f0) | Jan 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [b325ae9a48](https://linux-hardware.org/?probe=b325ae9a48) | Jan 11, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [268f34635a](https://linux-hardware.org/?probe=268f34635a) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d70aca4ad6](https://linux-hardware.org/?probe=d70aca4ad6) | Dec 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6d43b6afd](https://linux-hardware.org/?probe=a6d43b6afd) | Dec 22, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [4d24d45918](https://linux-hardware.org/?probe=4d24d45918) | Dec 21, 2022 |
| Acer          | Predator PH315-55           | Notebook    | [01ba4c7b4a](https://linux-hardware.org/?probe=01ba4c7b4a) | Dec 16, 2022 |
| Acer          | Predator PH315-55           | Notebook    | [e2297c201d](https://linux-hardware.org/?probe=e2297c201d) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [1120db45a3](https://linux-hardware.org/?probe=1120db45a3) | Dec 13, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| HP            | 3397                        | Desktop     | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| HPE           | ProLiant DL380 Gen10        | Server      | [4cdcad1148](https://linux-hardware.org/?probe=4cdcad1148) | Nov 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2c8a884430](https://linux-hardware.org/?probe=2c8a884430) | Nov 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [451d2e210d](https://linux-hardware.org/?probe=451d2e210d) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [51809e1ff3](https://linux-hardware.org/?probe=51809e1ff3) | Nov 11, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [db0a79fbd9](https://linux-hardware.org/?probe=db0a79fbd9) | Nov 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [0d4536a010](https://linux-hardware.org/?probe=0d4536a010) | Nov 07, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f22f67754e](https://linux-hardware.org/?probe=f22f67754e) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | Notebook    | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| HP            | G62                         | Notebook    | [a7b5ac8e19](https://linux-hardware.org/?probe=a7b5ac8e19) | Oct 20, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [6459e3fedb](https://linux-hardware.org/?probe=6459e3fedb) | Oct 16, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [5192a80499](https://linux-hardware.org/?probe=5192a80499) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | G62                         | Notebook    | [dbe9a778bb](https://linux-hardware.org/?probe=dbe9a778bb) | Oct 12, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| ASUSTek       | UX490UA                     | Notebook    | [e953c29d50](https://linux-hardware.org/?probe=e953c29d50) | Sep 19, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [d8be5e602a](https://linux-hardware.org/?probe=d8be5e602a) | Sep 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a15d189c98](https://linux-hardware.org/?probe=a15d189c98) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0737d49df2](https://linux-hardware.org/?probe=0737d49df2) | Sep 15, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [968826d76c](https://linux-hardware.org/?probe=968826d76c) | Sep 13, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [8718c2bb09](https://linux-hardware.org/?probe=8718c2bb09) | Sep 12, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [33c08b8aef](https://linux-hardware.org/?probe=33c08b8aef) | Sep 09, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [c803fe67f3](https://linux-hardware.org/?probe=c803fe67f3) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c98348c9a3](https://linux-hardware.org/?probe=c98348c9a3) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [68b6da5fe1](https://linux-hardware.org/?probe=68b6da5fe1) | Sep 04, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [349fc1d85c](https://linux-hardware.org/?probe=349fc1d85c) | Sep 03, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f0d85f4991](https://linux-hardware.org/?probe=f0d85f4991) | Sep 03, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ec5bb450ff](https://linux-hardware.org/?probe=ec5bb450ff) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [93ac400083](https://linux-hardware.org/?probe=93ac400083) | Aug 23, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [8d187f0a28](https://linux-hardware.org/?probe=8d187f0a28) | Aug 22, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fa12e95e32](https://linux-hardware.org/?probe=fa12e95e32) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a36a32eb0e](https://linux-hardware.org/?probe=a36a32eb0e) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [759c9dee6b](https://linux-hardware.org/?probe=759c9dee6b) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [114ada270e](https://linux-hardware.org/?probe=114ada270e) | Aug 08, 2022 |
| ASUSTek       | H110M-C/PS                  | Desktop     | [b633163f9f](https://linux-hardware.org/?probe=b633163f9f) | Aug 06, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Timi          | RedmiBook 14                | Notebook    | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0851479f6b](https://linux-hardware.org/?probe=0851479f6b) | Aug 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [9996781aa7](https://linux-hardware.org/?probe=9996781aa7) | Jul 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [117f3d3969](https://linux-hardware.org/?probe=117f3d3969) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb442470d4](https://linux-hardware.org/?probe=fb442470d4) | Jul 24, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [6f2adb5629](https://linux-hardware.org/?probe=6f2adb5629) | Jul 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bcb07d1cc9](https://linux-hardware.org/?probe=bcb07d1cc9) | Jul 16, 2022 |
| HP            | G62                         | Notebook    | [020a13b927](https://linux-hardware.org/?probe=020a13b927) | Jul 16, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4e8aa38fb4](https://linux-hardware.org/?probe=4e8aa38fb4) | Jul 11, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| ASUSTek       | N43JQ                       | Notebook    | [d73f714472](https://linux-hardware.org/?probe=d73f714472) | Jul 01, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| HP            | 3397                        | Desktop     | [337e956c95](https://linux-hardware.org/?probe=337e956c95) | Jun 22, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [43cf14bdd7](https://linux-hardware.org/?probe=43cf14bdd7) | Jun 22, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2893254eb3](https://linux-hardware.org/?probe=2893254eb3) | Jun 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e64a2a0eeb](https://linux-hardware.org/?probe=e64a2a0eeb) | Jun 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b0e13d9a94](https://linux-hardware.org/?probe=b0e13d9a94) | Jun 05, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [05094a5491](https://linux-hardware.org/?probe=05094a5491) | Jun 05, 2022 |
| Lenovo        | ThinkPad E420 1141E9G       | Notebook    | [48b5588cbd](https://linux-hardware.org/?probe=48b5588cbd) | Jun 01, 2022 |
| ASUSTek       | Maximus II Formula          | Desktop     | [84df720c51](https://linux-hardware.org/?probe=84df720c51) | May 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [27dffb7089](https://linux-hardware.org/?probe=27dffb7089) | May 29, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a4d6e798d](https://linux-hardware.org/?probe=8a4d6e798d) | May 26, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [2771a53784](https://linux-hardware.org/?probe=2771a53784) | May 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [1bce5b14e3](https://linux-hardware.org/?probe=1bce5b14e3) | May 17, 2022 |
| MSI           | 760GM-P33                   | Desktop     | [d37fca6b00](https://linux-hardware.org/?probe=d37fca6b00) | May 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [247fc8ed78](https://linux-hardware.org/?probe=247fc8ed78) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a9646dc78](https://linux-hardware.org/?probe=8a9646dc78) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b6cb96e1d0](https://linux-hardware.org/?probe=b6cb96e1d0) | May 13, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [1d71c877c7](https://linux-hardware.org/?probe=1d71c877c7) | May 13, 2022 |
| Lenovo        | ThinkPad X230 23253QU       | Notebook    | [fde2b81a1c](https://linux-hardware.org/?probe=fde2b81a1c) | May 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| Lenovo        | ThinkPad SL 2743X12         | Notebook    | [ad56efc5ff](https://linux-hardware.org/?probe=ad56efc5ff) | Apr 19, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [020929c7b4](https://linux-hardware.org/?probe=020929c7b4) | Apr 17, 2022 |
| HP            | 3048h                       | Desktop     | [2d19799047](https://linux-hardware.org/?probe=2d19799047) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a7da4b6ee0](https://linux-hardware.org/?probe=a7da4b6ee0) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a0ab75ee00](https://linux-hardware.org/?probe=a0ab75ee00) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36c4b80dbb](https://linux-hardware.org/?probe=36c4b80dbb) | Apr 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000RAD     | Notebook    | [6f4db41ef5](https://linux-hardware.org/?probe=6f4db41ef5) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | Notebook    | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [242cae44a5](https://linux-hardware.org/?probe=242cae44a5) | Apr 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [bfc20224d0](https://linux-hardware.org/?probe=bfc20224d0) | Mar 28, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [6e0eef7b54](https://linux-hardware.org/?probe=6e0eef7b54) | Mar 25, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [08a511ac81](https://linux-hardware.org/?probe=08a511ac81) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [61b36dcd42](https://linux-hardware.org/?probe=61b36dcd42) | Mar 18, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [2eca1925d5](https://linux-hardware.org/?probe=2eca1925d5) | Mar 16, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b10d8b3a00](https://linux-hardware.org/?probe=b10d8b3a00) | Mar 16, 2022 |
| Dell          | Latitude E6530              | Notebook    | [2c3bfeff1d](https://linux-hardware.org/?probe=2c3bfeff1d) | Mar 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [472d23c4f4](https://linux-hardware.org/?probe=472d23c4f4) | Mar 13, 2022 |
| Gigabyte      | G1.Sniper 5                 | Desktop     | [1ee0fc40a2](https://linux-hardware.org/?probe=1ee0fc40a2) | Mar 12, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [0d2de64455](https://linux-hardware.org/?probe=0d2de64455) | Mar 06, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [76da8a616f](https://linux-hardware.org/?probe=76da8a616f) | Mar 05, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [91eafd1ed4](https://linux-hardware.org/?probe=91eafd1ed4) | Mar 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [dad6067f40](https://linux-hardware.org/?probe=dad6067f40) | Mar 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [29926fb03b](https://linux-hardware.org/?probe=29926fb03b) | Mar 03, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [071f146979](https://linux-hardware.org/?probe=071f146979) | Feb 24, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [fa0603a25d](https://linux-hardware.org/?probe=fa0603a25d) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4d49233d4b](https://linux-hardware.org/?probe=4d49233d4b) | Feb 11, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [8294f013e8](https://linux-hardware.org/?probe=8294f013e8) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [93ca64d766](https://linux-hardware.org/?probe=93ca64d766) | Jan 28, 2022 |
| HP            | 8054                        | Desktop     | [332217129d](https://linux-hardware.org/?probe=332217129d) | Jan 26, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [c48fbc97e2](https://linux-hardware.org/?probe=c48fbc97e2) | Jan 22, 2022 |
| ECS           | H61H2-A                     | Desktop     | [90c26876b2](https://linux-hardware.org/?probe=90c26876b2) | Jan 21, 2022 |
| Alienware     | 17 R3                       | Notebook    | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| ECS           | H61H2-A                     | Desktop     | [518e31fcb0](https://linux-hardware.org/?probe=518e31fcb0) | Jan 13, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6875440733](https://linux-hardware.org/?probe=6875440733) | Jan 10, 2022 |
| ASUSTek       | X450LC                      | Notebook    | [8228658808](https://linux-hardware.org/?probe=8228658808) | Jan 09, 2022 |
| ECS           | H61H2-A                     | Desktop     | [47fb5347c0](https://linux-hardware.org/?probe=47fb5347c0) | Jan 06, 2022 |
| ECS           | H61H2-A                     | Desktop     | [fa589d8ed4](https://linux-hardware.org/?probe=fa589d8ed4) | Jan 06, 2022 |
| HP            | 806A                        | Desktop     | [d7519db95a](https://linux-hardware.org/?probe=d7519db95a) | Jan 02, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [ba7acc9c68](https://linux-hardware.org/?probe=ba7acc9c68) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [71a50bcb50](https://linux-hardware.org/?probe=71a50bcb50) | Dec 30, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d8d81e5c50](https://linux-hardware.org/?probe=d8d81e5c50) | Dec 30, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [71135c1724](https://linux-hardware.org/?probe=71135c1724) | Dec 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [9f22de7369](https://linux-hardware.org/?probe=9f22de7369) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [dcbbdb5fc5](https://linux-hardware.org/?probe=dcbbdb5fc5) | Dec 23, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [261f98a324](https://linux-hardware.org/?probe=261f98a324) | Dec 19, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [8e802c50ad](https://linux-hardware.org/?probe=8e802c50ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [7b6f9acbf8](https://linux-hardware.org/?probe=7b6f9acbf8) | Dec 15, 2021 |
| HP            | 3397                        | Desktop     | [83d7b8fe86](https://linux-hardware.org/?probe=83d7b8fe86) | Dec 12, 2021 |
| HP            | 3397                        | Desktop     | [469adb677f](https://linux-hardware.org/?probe=469adb677f) | Dec 12, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [b4a346e899](https://linux-hardware.org/?probe=b4a346e899) | Dec 11, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [2c739999fa](https://linux-hardware.org/?probe=2c739999fa) | Dec 10, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [68820e21d2](https://linux-hardware.org/?probe=68820e21d2) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [c7e180ab84](https://linux-hardware.org/?probe=c7e180ab84) | Dec 08, 2021 |
| Dell          | Latitude E7470              | Notebook    | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [7eed1618fe](https://linux-hardware.org/?probe=7eed1618fe) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [01c7adcf94](https://linux-hardware.org/?probe=01c7adcf94) | Nov 28, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6eff02505f](https://linux-hardware.org/?probe=6eff02505f) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [005b267983](https://linux-hardware.org/?probe=005b267983) | Nov 22, 2021 |
| ASUSTek       | GL702VMK                    | Notebook    | [ff58d2a76e](https://linux-hardware.org/?probe=ff58d2a76e) | Nov 21, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [81a7c19597](https://linux-hardware.org/?probe=81a7c19597) | Nov 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [f119e55cf9](https://linux-hardware.org/?probe=f119e55cf9) | Nov 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Gigabyte      | P41T-D3P                    | Desktop     | [54a25af09a](https://linux-hardware.org/?probe=54a25af09a) | Nov 11, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [20aa404ab6](https://linux-hardware.org/?probe=20aa404ab6) | Nov 10, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [cfafa7735b](https://linux-hardware.org/?probe=cfafa7735b) | Nov 08, 2021 |
| Dell          | Latitude E7240              | Notebook    | [366228fab6](https://linux-hardware.org/?probe=366228fab6) | Nov 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d098305f2a](https://linux-hardware.org/?probe=d098305f2a) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d99bdece1d](https://linux-hardware.org/?probe=d99bdece1d) | Oct 30, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8db63e7a74](https://linux-hardware.org/?probe=8db63e7a74) | Oct 28, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [75b53e8d45](https://linux-hardware.org/?probe=75b53e8d45) | Oct 27, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [19cdc9b391](https://linux-hardware.org/?probe=19cdc9b391) | Oct 26, 2021 |
| Sony          | VPCSA25GX                   | Notebook    | [be4db20b0e](https://linux-hardware.org/?probe=be4db20b0e) | Oct 25, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [6ab1ce41db](https://linux-hardware.org/?probe=6ab1ce41db) | Oct 25, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [6547cded19](https://linux-hardware.org/?probe=6547cded19) | Oct 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [30c1b322ad](https://linux-hardware.org/?probe=30c1b322ad) | Oct 22, 2021 |
| ASUSTek       | U56E                        | Notebook    | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [4e6bceb431](https://linux-hardware.org/?probe=4e6bceb431) | Oct 18, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [783eeaaa01](https://linux-hardware.org/?probe=783eeaaa01) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [cce3e9bd74](https://linux-hardware.org/?probe=cce3e9bd74) | Oct 12, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [398dedabb8](https://linux-hardware.org/?probe=398dedabb8) | Oct 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [23d2e1a73d](https://linux-hardware.org/?probe=23d2e1a73d) | Oct 06, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [cc83275513](https://linux-hardware.org/?probe=cc83275513) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325655d6c5](https://linux-hardware.org/?probe=325655d6c5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6cfb3f0c44](https://linux-hardware.org/?probe=6cfb3f0c44) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASUSTek       | T103HAF                     | Tablet      | [b2d1b00b0a](https://linux-hardware.org/?probe=b2d1b00b0a) | Sep 28, 2021 |
| ASRock        | B85M                        | Desktop     | [566089bd43](https://linux-hardware.org/?probe=566089bd43) | Sep 27, 2021 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [eec5db351d](https://linux-hardware.org/?probe=eec5db351d) | Sep 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e614dfffe](https://linux-hardware.org/?probe=0e614dfffe) | Sep 27, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [3c4378f506](https://linux-hardware.org/?probe=3c4378f506) | Sep 25, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9b27471e86](https://linux-hardware.org/?probe=9b27471e86) | Sep 23, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [2b74c7b1ff](https://linux-hardware.org/?probe=2b74c7b1ff) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [2b132c74b6](https://linux-hardware.org/?probe=2b132c74b6) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [ca2bc77aa5](https://linux-hardware.org/?probe=ca2bc77aa5) | Sep 16, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | Notebook    | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [ec0cd5d69b](https://linux-hardware.org/?probe=ec0cd5d69b) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [7797008e19](https://linux-hardware.org/?probe=7797008e19) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [07d1890920](https://linux-hardware.org/?probe=07d1890920) | Sep 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [a6221df8f8](https://linux-hardware.org/?probe=a6221df8f8) | Sep 10, 2021 |
| ASUSTek       | X540UV                      | Notebook    | [b0a231831a](https://linux-hardware.org/?probe=b0a231831a) | Sep 09, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [d47d63a84f](https://linux-hardware.org/?probe=d47d63a84f) | Sep 07, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [453f65a5e7](https://linux-hardware.org/?probe=453f65a5e7) | Sep 07, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [b915ae27b7](https://linux-hardware.org/?probe=b915ae27b7) | Sep 06, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [62fc103f71](https://linux-hardware.org/?probe=62fc103f71) | Sep 06, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [016672b182](https://linux-hardware.org/?probe=016672b182) | Sep 03, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [b011298d66](https://linux-hardware.org/?probe=b011298d66) | Sep 01, 2021 |
| MSI           | Prestige 14 A10RB           | Notebook    | [2aaa6d05d2](https://linux-hardware.org/?probe=2aaa6d05d2) | Sep 01, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [2044660bb8](https://linux-hardware.org/?probe=2044660bb8) | Aug 30, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0e5100e716](https://linux-hardware.org/?probe=0e5100e716) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0bf997753c](https://linux-hardware.org/?probe=0bf997753c) | Aug 29, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [9f01a4629a](https://linux-hardware.org/?probe=9f01a4629a) | Aug 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [de74046226](https://linux-hardware.org/?probe=de74046226) | Aug 23, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [19a7dfc92a](https://linux-hardware.org/?probe=19a7dfc92a) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [bfe60273f6](https://linux-hardware.org/?probe=bfe60273f6) | Aug 09, 2021 |
| HP            | ZBook 15                    | Notebook    | [1a67896055](https://linux-hardware.org/?probe=1a67896055) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | Notebook    | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [fe27de6bbc](https://linux-hardware.org/?probe=fe27de6bbc) | Aug 07, 2021 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [407501f166](https://linux-hardware.org/?probe=407501f166) | Aug 05, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [1e165352ad](https://linux-hardware.org/?probe=1e165352ad) | Aug 04, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [a5c472e082](https://linux-hardware.org/?probe=a5c472e082) | Aug 01, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [538eb1efa0](https://linux-hardware.org/?probe=538eb1efa0) | Aug 01, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [13e3cf7a5f](https://linux-hardware.org/?probe=13e3cf7a5f) | Jul 29, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [063facd29a](https://linux-hardware.org/?probe=063facd29a) | Jul 28, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [afb9cb6674](https://linux-hardware.org/?probe=afb9cb6674) | Jul 27, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [5d118fd4cc](https://linux-hardware.org/?probe=5d118fd4cc) | Jul 26, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | ProBook 4540s               | Notebook    | [719b37c9ac](https://linux-hardware.org/?probe=719b37c9ac) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [0ae43f5015](https://linux-hardware.org/?probe=0ae43f5015) | Jul 20, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [b26638f586](https://linux-hardware.org/?probe=b26638f586) | Jul 17, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [8a28a4f7f5](https://linux-hardware.org/?probe=8a28a4f7f5) | Jul 17, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [08f5207ee6](https://linux-hardware.org/?probe=08f5207ee6) | Jul 17, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [b3bb7e1295](https://linux-hardware.org/?probe=b3bb7e1295) | Jul 17, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [01b8cc373f](https://linux-hardware.org/?probe=01b8cc373f) | Jul 13, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| HP            | Notebook                    | Notebook    | [3fc4cb2f55](https://linux-hardware.org/?probe=3fc4cb2f55) | Jul 09, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [90a20b185b](https://linux-hardware.org/?probe=90a20b185b) | Jul 03, 2021 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [0301b9707b](https://linux-hardware.org/?probe=0301b9707b) | Jun 29, 2021 |
| Lenovo        | ThinkPad E560 20EV0005AD    | Notebook    | [fab11e73ee](https://linux-hardware.org/?probe=fab11e73ee) | Jun 29, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [6a5d92699d](https://linux-hardware.org/?probe=6a5d92699d) | Jun 23, 2021 |
| Dell          | Latitude D420               | Notebook    | [5f0d609bef](https://linux-hardware.org/?probe=5f0d609bef) | Jun 21, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [7026c20c97](https://linux-hardware.org/?probe=7026c20c97) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [f34a1bbe5a](https://linux-hardware.org/?probe=f34a1bbe5a) | Jun 20, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [1343b5bb5d](https://linux-hardware.org/?probe=1343b5bb5d) | Jun 20, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [5963dd2256](https://linux-hardware.org/?probe=5963dd2256) | Jun 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [4af988fc2f](https://linux-hardware.org/?probe=4af988fc2f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [1fd8a9e8c8](https://linux-hardware.org/?probe=1fd8a9e8c8) | Jun 16, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| ASUSTek       | Z11PG-D24 Series            | Server      | [e4be3f2344](https://linux-hardware.org/?probe=e4be3f2344) | Jun 12, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [28e717743a](https://linux-hardware.org/?probe=28e717743a) | Jun 06, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [35b68a0b4a](https://linux-hardware.org/?probe=35b68a0b4a) | Jun 06, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4b5debd7a6](https://linux-hardware.org/?probe=4b5debd7a6) | Jun 04, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4333473e1e](https://linux-hardware.org/?probe=4333473e1e) | Jun 03, 2021 |
| HP            | ProBook 4520s               | Notebook    | [b0a9a196db](https://linux-hardware.org/?probe=b0a9a196db) | Jun 03, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [b3206cba40](https://linux-hardware.org/?probe=b3206cba40) | Jun 03, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [043730ad50](https://linux-hardware.org/?probe=043730ad50) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [1023832c74](https://linux-hardware.org/?probe=1023832c74) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [2ff6c9500b](https://linux-hardware.org/?probe=2ff6c9500b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [74d1da4b68](https://linux-hardware.org/?probe=74d1da4b68) | May 28, 2021 |
| ASUSTek       | X550MJ                      | Notebook    | [208fc3f30f](https://linux-hardware.org/?probe=208fc3f30f) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [28d19f1a59](https://linux-hardware.org/?probe=28d19f1a59) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [512cc44d82](https://linux-hardware.org/?probe=512cc44d82) | May 21, 2021 |
| ASUSTek       | K53SM                       | Notebook    | [f0199bc53d](https://linux-hardware.org/?probe=f0199bc53d) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [1417eccc8b](https://linux-hardware.org/?probe=1417eccc8b) | May 15, 2021 |
| HP            | EliteBook 725 G2            | Notebook    | [5dddeca3e8](https://linux-hardware.org/?probe=5dddeca3e8) | May 09, 2021 |
| MSI           | PH67A-C43                   | Desktop     | [8e818ce79a](https://linux-hardware.org/?probe=8e818ce79a) | May 05, 2021 |
| Acer          | Aspire V3-574G              | Notebook    | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [2d12301b1c](https://linux-hardware.org/?probe=2d12301b1c) | May 05, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8f0e9df209](https://linux-hardware.org/?probe=8f0e9df209) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [940758b420](https://linux-hardware.org/?probe=940758b420) | Apr 27, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [ced3a1165d](https://linux-hardware.org/?probe=ced3a1165d) | Apr 24, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [eeb73d1c4a](https://linux-hardware.org/?probe=eeb73d1c4a) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [93671f3ecc](https://linux-hardware.org/?probe=93671f3ecc) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [9fbf2707b0](https://linux-hardware.org/?probe=9fbf2707b0) | Apr 19, 2021 |
| ASUSTek       | X555LF                      | Notebook    | [eb9637ae4a](https://linux-hardware.org/?probe=eb9637ae4a) | Apr 19, 2021 |
| Lenovo        | ThinkPad E590 20NB0057AD    | Notebook    | [d06cfc6dee](https://linux-hardware.org/?probe=d06cfc6dee) | Apr 18, 2021 |
| Acer          | AOD260                      | Notebook    | [97f6b98307](https://linux-hardware.org/?probe=97f6b98307) | Apr 16, 2021 |
| Lenovo        | ThinkPad T470p 20J6S08M0... | Notebook    | [84619b1b45](https://linux-hardware.org/?probe=84619b1b45) | Apr 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1dcb2a173e](https://linux-hardware.org/?probe=1dcb2a173e) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [28d13bbb26](https://linux-hardware.org/?probe=28d13bbb26) | Apr 14, 2021 |
| Gigabyte      | M52S-S3P                    | Desktop     | [494ac8b449](https://linux-hardware.org/?probe=494ac8b449) | Apr 11, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [29e4ff83db](https://linux-hardware.org/?probe=29e4ff83db) | Apr 10, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [7713767fa6](https://linux-hardware.org/?probe=7713767fa6) | Apr 10, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [9c00d55213](https://linux-hardware.org/?probe=9c00d55213) | Apr 10, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [5b0c97ade1](https://linux-hardware.org/?probe=5b0c97ade1) | Apr 09, 2021 |
| MSI           | CR610M                      | Notebook    | [e2e00880a3](https://linux-hardware.org/?probe=e2e00880a3) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| ASUSTek       | H61M-C                      | Desktop     | [c39fc169bf](https://linux-hardware.org/?probe=c39fc169bf) | Apr 02, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [c5e7e65164](https://linux-hardware.org/?probe=c5e7e65164) | Apr 01, 2021 |
| HP            | EliteBook 745 G4            | Notebook    | [a5888bbded](https://linux-hardware.org/?probe=a5888bbded) | Apr 01, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [9a4a054203](https://linux-hardware.org/?probe=9a4a054203) | Apr 01, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [9c2661508e](https://linux-hardware.org/?probe=9c2661508e) | Mar 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [bacb9e5030](https://linux-hardware.org/?probe=bacb9e5030) | Mar 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [344eec241a](https://linux-hardware.org/?probe=344eec241a) | Mar 21, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [ca815648fc](https://linux-hardware.org/?probe=ca815648fc) | Mar 17, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [d5d788f2f3](https://linux-hardware.org/?probe=d5d788f2f3) | Mar 15, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [89b0451670](https://linux-hardware.org/?probe=89b0451670) | Mar 14, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [ed8b926f53](https://linux-hardware.org/?probe=ed8b926f53) | Mar 14, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [75ba14ee94](https://linux-hardware.org/?probe=75ba14ee94) | Mar 14, 2021 |
| HP            | 3397                        | Desktop     | [13a7f8c4c2](https://linux-hardware.org/?probe=13a7f8c4c2) | Mar 08, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [be98339598](https://linux-hardware.org/?probe=be98339598) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [eb31b2ffb6](https://linux-hardware.org/?probe=eb31b2ffb6) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [fd19b6b1c8](https://linux-hardware.org/?probe=fd19b6b1c8) | Mar 07, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [502ef11b75](https://linux-hardware.org/?probe=502ef11b75) | Mar 07, 2021 |
| Gigabyte      | GA-M55SLI-S4                | Desktop     | [43d0cb9ac1](https://linux-hardware.org/?probe=43d0cb9ac1) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [b7e39a92a0](https://linux-hardware.org/?probe=b7e39a92a0) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [7ca6ad9361](https://linux-hardware.org/?probe=7ca6ad9361) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [5681b93aaf](https://linux-hardware.org/?probe=5681b93aaf) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [9f858aaf27](https://linux-hardware.org/?probe=9f858aaf27) | Mar 05, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [bae11d222f](https://linux-hardware.org/?probe=bae11d222f) | Mar 04, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [3ae670828a](https://linux-hardware.org/?probe=3ae670828a) | Mar 03, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [fd21e67a3c](https://linux-hardware.org/?probe=fd21e67a3c) | Feb 28, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [429c09a059](https://linux-hardware.org/?probe=429c09a059) | Feb 28, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2ce61d58bf](https://linux-hardware.org/?probe=2ce61d58bf) | Feb 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [dda65f86ac](https://linux-hardware.org/?probe=dda65f86ac) | Feb 24, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e3ff93ab0a](https://linux-hardware.org/?probe=e3ff93ab0a) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [ab787a4172](https://linux-hardware.org/?probe=ab787a4172) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [7ba0b6a17d](https://linux-hardware.org/?probe=7ba0b6a17d) | Feb 21, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [b1b8587cdb](https://linux-hardware.org/?probe=b1b8587cdb) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [d45ed4ad08](https://linux-hardware.org/?probe=d45ed4ad08) | Feb 19, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [b6a8851986](https://linux-hardware.org/?probe=b6a8851986) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [520780b02d](https://linux-hardware.org/?probe=520780b02d) | Feb 18, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [62c9e819cd](https://linux-hardware.org/?probe=62c9e819cd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [8070e672a7](https://linux-hardware.org/?probe=8070e672a7) | Feb 15, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ee986e1fdd](https://linux-hardware.org/?probe=ee986e1fdd) | Feb 11, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b661aa21f1](https://linux-hardware.org/?probe=b661aa21f1) | Feb 09, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [0c9067579c](https://linux-hardware.org/?probe=0c9067579c) | Feb 09, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab4bc22a87](https://linux-hardware.org/?probe=ab4bc22a87) | Feb 06, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [5e9aa1c3de](https://linux-hardware.org/?probe=5e9aa1c3de) | Feb 06, 2021 |
| ASUSTek       | X456URK                     | Notebook    | [6c3b5bdfb1](https://linux-hardware.org/?probe=6c3b5bdfb1) | Feb 05, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [9de86c8038](https://linux-hardware.org/?probe=9de86c8038) | Feb 05, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [d383b4a5e7](https://linux-hardware.org/?probe=d383b4a5e7) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [2bd7b5699d](https://linux-hardware.org/?probe=2bd7b5699d) | Feb 05, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [f1f4fbad09](https://linux-hardware.org/?probe=f1f4fbad09) | Feb 03, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [0df26493a8](https://linux-hardware.org/?probe=0df26493a8) | Feb 03, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [82920966cf](https://linux-hardware.org/?probe=82920966cf) | Feb 01, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d82031935e](https://linux-hardware.org/?probe=d82031935e) | Feb 01, 2021 |
| ASUSTek       | N56JR                       | Notebook    | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [2960ce1b31](https://linux-hardware.org/?probe=2960ce1b31) | Jan 27, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [b97b822412](https://linux-hardware.org/?probe=b97b822412) | Jan 27, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [a0eb5fc713](https://linux-hardware.org/?probe=a0eb5fc713) | Jan 20, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [2fa2f12de6](https://linux-hardware.org/?probe=2fa2f12de6) | Jan 19, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [537d05799c](https://linux-hardware.org/?probe=537d05799c) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [66598d3f69](https://linux-hardware.org/?probe=66598d3f69) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [703dd398d1](https://linux-hardware.org/?probe=703dd398d1) | Jan 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [85c5454ed1](https://linux-hardware.org/?probe=85c5454ed1) | Jan 14, 2021 |
| ASUSTek       | X542UN                      | Notebook    | [44633c4ff2](https://linux-hardware.org/?probe=44633c4ff2) | Jan 13, 2021 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [d8aafdef30](https://linux-hardware.org/?probe=d8aafdef30) | Jan 10, 2021 |
| Sony          | SVF15N12SGB                 | Notebook    | [3ff592b868](https://linux-hardware.org/?probe=3ff592b868) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [4e6cc9fdc4](https://linux-hardware.org/?probe=4e6cc9fdc4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [7243a2df4f](https://linux-hardware.org/?probe=7243a2df4f) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [4d96f1db71](https://linux-hardware.org/?probe=4d96f1db71) | Dec 31, 2020 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [be00a7c4e5](https://linux-hardware.org/?probe=be00a7c4e5) | Dec 28, 2020 |
| Acer          | Aspire 5755G                | Notebook    | [5577ccef28](https://linux-hardware.org/?probe=5577ccef28) | Dec 28, 2020 |
| HP            | ProBook 4540s               | Notebook    | [86bd405fac](https://linux-hardware.org/?probe=86bd405fac) | Dec 27, 2020 |
| HP            | ProBook 4540s               | Notebook    | [7a93e1b05a](https://linux-hardware.org/?probe=7a93e1b05a) | Dec 27, 2020 |
| Dell          | Vostro 1015                 | Notebook    | [9be1d69693](https://linux-hardware.org/?probe=9be1d69693) | Dec 26, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [9582155494](https://linux-hardware.org/?probe=9582155494) | Dec 25, 2020 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [f7f32358db](https://linux-hardware.org/?probe=f7f32358db) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [3071d9e517](https://linux-hardware.org/?probe=3071d9e517) | Dec 23, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [46af0a2d84](https://linux-hardware.org/?probe=46af0a2d84) | Dec 22, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [c659f6a910](https://linux-hardware.org/?probe=c659f6a910) | Dec 21, 2020 |
| HP            | 3397                        | Desktop     | [1b81310dbf](https://linux-hardware.org/?probe=1b81310dbf) | Dec 20, 2020 |
| HP            | 3397                        | Desktop     | [086227e446](https://linux-hardware.org/?probe=086227e446) | Dec 20, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T10... | Notebook    | [d5a85767cd](https://linux-hardware.org/?probe=d5a85767cd) | Dec 18, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [a6bf272580](https://linux-hardware.org/?probe=a6bf272580) | Dec 18, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [fe5ef27982](https://linux-hardware.org/?probe=fe5ef27982) | Dec 17, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [ccdd9fbe6b](https://linux-hardware.org/?probe=ccdd9fbe6b) | Dec 16, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e7e6ad670b](https://linux-hardware.org/?probe=e7e6ad670b) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [03f5d24d56](https://linux-hardware.org/?probe=03f5d24d56) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [886054e929](https://linux-hardware.org/?probe=886054e929) | Dec 15, 2020 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [e39c3e59b5](https://linux-hardware.org/?probe=e39c3e59b5) | Dec 13, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [67aa2554c3](https://linux-hardware.org/?probe=67aa2554c3) | Dec 10, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [90a60a1e78](https://linux-hardware.org/?probe=90a60a1e78) | Dec 06, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [9b4aaf5856](https://linux-hardware.org/?probe=9b4aaf5856) | Dec 06, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [d93fb9ef4a](https://linux-hardware.org/?probe=d93fb9ef4a) | Dec 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [47835d66f6](https://linux-hardware.org/?probe=47835d66f6) | Dec 01, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [9f5052c50b](https://linux-hardware.org/?probe=9f5052c50b) | Nov 30, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [03db05b217](https://linux-hardware.org/?probe=03db05b217) | Nov 30, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [c9c25216a4](https://linux-hardware.org/?probe=c9c25216a4) | Nov 25, 2020 |
| Sony          | VPCEH11FX                   | Notebook    | [d3ff8db043](https://linux-hardware.org/?probe=d3ff8db043) | Nov 22, 2020 |
| HP            | 2AF3                        | Desktop     | [3c07a68022](https://linux-hardware.org/?probe=3c07a68022) | Nov 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8e0bc13a31](https://linux-hardware.org/?probe=8e0bc13a31) | Nov 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [c099ac62d5](https://linux-hardware.org/?probe=c099ac62d5) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [7787345258](https://linux-hardware.org/?probe=7787345258) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [be124397e2](https://linux-hardware.org/?probe=be124397e2) | Nov 13, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3bc3e0823a](https://linux-hardware.org/?probe=3bc3e0823a) | Nov 09, 2020 |
| HP            | ProBook 4540s               | Notebook    | [4864704e84](https://linux-hardware.org/?probe=4864704e84) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [adbb505553](https://linux-hardware.org/?probe=adbb505553) | Nov 08, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [543559dfac](https://linux-hardware.org/?probe=543559dfac) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [c7b7b29a68](https://linux-hardware.org/?probe=c7b7b29a68) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [3b7111b4a2](https://linux-hardware.org/?probe=3b7111b4a2) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [cb3bf5a3df](https://linux-hardware.org/?probe=cb3bf5a3df) | Nov 07, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [6a88e646aa](https://linux-hardware.org/?probe=6a88e646aa) | Nov 07, 2020 |
| ASUSTek       | X550VXK                     | Notebook    | [5f95436c09](https://linux-hardware.org/?probe=5f95436c09) | Nov 06, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [42ef7e253c](https://linux-hardware.org/?probe=42ef7e253c) | Nov 01, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [cba527dd9f](https://linux-hardware.org/?probe=cba527dd9f) | Nov 01, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [75bacf18a7](https://linux-hardware.org/?probe=75bacf18a7) | Oct 31, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f6c5e1d108](https://linux-hardware.org/?probe=f6c5e1d108) | Oct 28, 2020 |
| Foxconn       | A8G-i                       | Desktop     | [b4675cde03](https://linux-hardware.org/?probe=b4675cde03) | Oct 27, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [c3cd0fcf33](https://linux-hardware.org/?probe=c3cd0fcf33) | Oct 24, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [11db584122](https://linux-hardware.org/?probe=11db584122) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [7525ff1dde](https://linux-hardware.org/?probe=7525ff1dde) | Oct 23, 2020 |
| ASUSTek       | N552VW                      | Notebook    | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | Notebook    | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| Lenovo        | B50-80 80EW                 | Notebook    | [c6bf9e5376](https://linux-hardware.org/?probe=c6bf9e5376) | Oct 17, 2020 |
| ASUSTek       | X505BA                      | Notebook    | [6f5c254a9f](https://linux-hardware.org/?probe=6f5c254a9f) | Oct 15, 2020 |
| Intel         | P61-S3                      | Desktop     | [efee9af681](https://linux-hardware.org/?probe=efee9af681) | Oct 13, 2020 |
| Intel         | P61-S3                      | Desktop     | [36f0f58223](https://linux-hardware.org/?probe=36f0f58223) | Oct 12, 2020 |
| Gigabyte      | 8S648FX-RZ                  | Desktop     | [c00289e6ed](https://linux-hardware.org/?probe=c00289e6ed) | Oct 11, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [2763c330eb](https://linux-hardware.org/?probe=2763c330eb) | Oct 09, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [ef1c17dd39](https://linux-hardware.org/?probe=ef1c17dd39) | Oct 08, 2020 |
| ASUSTek       | UX430UA                     | Notebook    | [d6586b9bb8](https://linux-hardware.org/?probe=d6586b9bb8) | Oct 05, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [bbf7ae1125](https://linux-hardware.org/?probe=bbf7ae1125) | Oct 05, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [5996a3b895](https://linux-hardware.org/?probe=5996a3b895) | Sep 29, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [60156a645b](https://linux-hardware.org/?probe=60156a645b) | Sep 29, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [01b67b1979](https://linux-hardware.org/?probe=01b67b1979) | Sep 27, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [616d06a0b0](https://linux-hardware.org/?probe=616d06a0b0) | Sep 26, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [6f184c4bc8](https://linux-hardware.org/?probe=6f184c4bc8) | Sep 26, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [9808a6bb0c](https://linux-hardware.org/?probe=9808a6bb0c) | Sep 25, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ea9c0eca9](https://linux-hardware.org/?probe=5ea9c0eca9) | Sep 24, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [59f1e93325](https://linux-hardware.org/?probe=59f1e93325) | Sep 18, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [a91b502a98](https://linux-hardware.org/?probe=a91b502a98) | Sep 18, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [9456172087](https://linux-hardware.org/?probe=9456172087) | Sep 18, 2020 |
| Gigabyte      | B75M-D3V                    | Desktop     | [32e15ba2b5](https://linux-hardware.org/?probe=32e15ba2b5) | Sep 18, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [36d0455f5f](https://linux-hardware.org/?probe=36d0455f5f) | Sep 15, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7ad450ddd7](https://linux-hardware.org/?probe=7ad450ddd7) | Sep 14, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ed2d21f85](https://linux-hardware.org/?probe=5ed2d21f85) | Sep 05, 2020 |
| ASUSTek       | K52F                        | Notebook    | [1658b8903d](https://linux-hardware.org/?probe=1658b8903d) | Sep 04, 2020 |
| ASUSTek       | K52F                        | Notebook    | [b7a5d27a01](https://linux-hardware.org/?probe=b7a5d27a01) | Sep 04, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [79d7ee2e74](https://linux-hardware.org/?probe=79d7ee2e74) | Sep 04, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [61bc69e87c](https://linux-hardware.org/?probe=61bc69e87c) | Sep 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [c026f89bd8](https://linux-hardware.org/?probe=c026f89bd8) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0ab2905b28](https://linux-hardware.org/?probe=0ab2905b28) | Aug 29, 2020 |
| MSI           | Prestige 14 A10RB           | Notebook    | [b7fff5e5cc](https://linux-hardware.org/?probe=b7fff5e5cc) | Aug 28, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [c172701a56](https://linux-hardware.org/?probe=c172701a56) | Aug 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [af595ebfde](https://linux-hardware.org/?probe=af595ebfde) | Aug 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c03d58914c](https://linux-hardware.org/?probe=c03d58914c) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [55c0c83149](https://linux-hardware.org/?probe=55c0c83149) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [e97f7b8582](https://linux-hardware.org/?probe=e97f7b8582) | Aug 02, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [f7eff6d78e](https://linux-hardware.org/?probe=f7eff6d78e) | Jul 28, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [7b12eabb3e](https://linux-hardware.org/?probe=7b12eabb3e) | Jul 28, 2020 |
| HP            | 3397                        | Desktop     | [e4e6951a4f](https://linux-hardware.org/?probe=e4e6951a4f) | Jul 25, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [2c268bdb51](https://linux-hardware.org/?probe=2c268bdb51) | Jul 24, 2020 |
| Lenovo        | ThinkCentre M58 8910ASU     | Desktop     | [d29d396ad0](https://linux-hardware.org/?probe=d29d396ad0) | Jul 23, 2020 |
| Lenovo        | ThinkPad E490 20N8000JUE    | Notebook    | [66d2ca1186](https://linux-hardware.org/?probe=66d2ca1186) | Jul 22, 2020 |
| ASUSTek       | N53Jq                       | Notebook    | [4d04d4ee3a](https://linux-hardware.org/?probe=4d04d4ee3a) | Jul 19, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [d7789565b7](https://linux-hardware.org/?probe=d7789565b7) | Jul 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [eb9ea3a7af](https://linux-hardware.org/?probe=eb9ea3a7af) | Jul 12, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [e9a3474bde](https://linux-hardware.org/?probe=e9a3474bde) | Jul 09, 2020 |
| HP            | 212B                        | Desktop     | [4a3583e0db](https://linux-hardware.org/?probe=4a3583e0db) | Jul 06, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [de25d26410](https://linux-hardware.org/?probe=de25d26410) | Jul 05, 2020 |
| ECS           | G31T-M                      | Desktop     | [614dcd20e7](https://linux-hardware.org/?probe=614dcd20e7) | Jul 05, 2020 |
| Acer          | Aspire V5-561G              | Notebook    | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [a35de97ee5](https://linux-hardware.org/?probe=a35de97ee5) | Jun 27, 2020 |
| ASUSTek       | H110M-C                     | Desktop     | [5656016c57](https://linux-hardware.org/?probe=5656016c57) | Jun 27, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [304331fe41](https://linux-hardware.org/?probe=304331fe41) | Jun 24, 2020 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [d0f33583b0](https://linux-hardware.org/?probe=d0f33583b0) | Jun 21, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [7554759bac](https://linux-hardware.org/?probe=7554759bac) | Jun 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| ASUSTek       | X580VD                      | Notebook    | [1ad8491ca0](https://linux-hardware.org/?probe=1ad8491ca0) | Jun 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [376ebf1819](https://linux-hardware.org/?probe=376ebf1819) | Jun 14, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [56a1c895ee](https://linux-hardware.org/?probe=56a1c895ee) | Jun 07, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [4a67c5fabb](https://linux-hardware.org/?probe=4a67c5fabb) | Jun 03, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [8fd66dd600](https://linux-hardware.org/?probe=8fd66dd600) | Jun 01, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [fbd9ae49c7](https://linux-hardware.org/?probe=fbd9ae49c7) | Jun 01, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d059aa2096](https://linux-hardware.org/?probe=d059aa2096) | May 29, 2020 |
| Sony          | VGN-SR165E                  | Notebook    | [ee7e382325](https://linux-hardware.org/?probe=ee7e382325) | May 27, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [0ff458cc64](https://linux-hardware.org/?probe=0ff458cc64) | May 23, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [639a8b36be](https://linux-hardware.org/?probe=639a8b36be) | May 23, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [870f5869a0](https://linux-hardware.org/?probe=870f5869a0) | May 22, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [842fbba95c](https://linux-hardware.org/?probe=842fbba95c) | May 22, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [c9967bfff4](https://linux-hardware.org/?probe=c9967bfff4) | May 22, 2020 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [58dbbb5f10](https://linux-hardware.org/?probe=58dbbb5f10) | May 22, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| HP            | 3397                        | Desktop     | [6d3acf04fa](https://linux-hardware.org/?probe=6d3acf04fa) | May 18, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [d919340bf8](https://linux-hardware.org/?probe=d919340bf8) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91908a3d7e](https://linux-hardware.org/?probe=91908a3d7e) | May 15, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [d064b573d0](https://linux-hardware.org/?probe=d064b573d0) | May 14, 2020 |
| ECS           | G41T-M13                    | Desktop     | [7f8c6dbb44](https://linux-hardware.org/?probe=7f8c6dbb44) | May 14, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3448fe759e](https://linux-hardware.org/?probe=3448fe759e) | May 13, 2020 |
| ECS           | G41T-M13                    | Desktop     | [b2c5f54483](https://linux-hardware.org/?probe=b2c5f54483) | May 10, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [d27ef604e7](https://linux-hardware.org/?probe=d27ef604e7) | May 10, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [cc84ca4df1](https://linux-hardware.org/?probe=cc84ca4df1) | May 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [150b4cbfba](https://linux-hardware.org/?probe=150b4cbfba) | May 08, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [efe32a1257](https://linux-hardware.org/?probe=efe32a1257) | May 07, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [3cac051446](https://linux-hardware.org/?probe=3cac051446) | May 07, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [543fb035d1](https://linux-hardware.org/?probe=543fb035d1) | May 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7d8b34f96f](https://linux-hardware.org/?probe=7d8b34f96f) | May 03, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a214d8fa2f](https://linux-hardware.org/?probe=a214d8fa2f) | May 02, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a6f251843f](https://linux-hardware.org/?probe=a6f251843f) | May 01, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96005fbb6f](https://linux-hardware.org/?probe=96005fbb6f) | Apr 28, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [3405972303](https://linux-hardware.org/?probe=3405972303) | Apr 27, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [2950c5ee7f](https://linux-hardware.org/?probe=2950c5ee7f) | Apr 27, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [f82980ac2c](https://linux-hardware.org/?probe=f82980ac2c) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [abfe333fb8](https://linux-hardware.org/?probe=abfe333fb8) | Apr 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [9e8575f75a](https://linux-hardware.org/?probe=9e8575f75a) | Apr 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5ec8b8b3b7](https://linux-hardware.org/?probe=5ec8b8b3b7) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [680bbeabad](https://linux-hardware.org/?probe=680bbeabad) | Apr 24, 2020 |
| HP            | Pavilion g6                 | Notebook    | [66ba3bc59b](https://linux-hardware.org/?probe=66ba3bc59b) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [82f761db09](https://linux-hardware.org/?probe=82f761db09) | Apr 23, 2020 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [409a40b72d](https://linux-hardware.org/?probe=409a40b72d) | Apr 20, 2020 |
| Lenovo        | ThinkPad E480 20KN007XAD    | Notebook    | [8310d15c91](https://linux-hardware.org/?probe=8310d15c91) | Apr 18, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [74699b5097](https://linux-hardware.org/?probe=74699b5097) | Apr 16, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [93a89841fd](https://linux-hardware.org/?probe=93a89841fd) | Apr 12, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [943b36ee80](https://linux-hardware.org/?probe=943b36ee80) | Apr 10, 2020 |
| Sony          | VPCEH11FX                   | Notebook    | [e0ef96682b](https://linux-hardware.org/?probe=e0ef96682b) | Apr 09, 2020 |
| ASUSTek       | G750JH                      | Notebook    | [45a70fa311](https://linux-hardware.org/?probe=45a70fa311) | Apr 08, 2020 |
| ASUSTek       | G750JH                      | Notebook    | [3314aa590e](https://linux-hardware.org/?probe=3314aa590e) | Apr 08, 2020 |
| ASUSTek       | Z97-C                       | Desktop     | [53462bc3ec](https://linux-hardware.org/?probe=53462bc3ec) | Apr 07, 2020 |
| Dell          | Latitude D630               | Notebook    | [98199f8421](https://linux-hardware.org/?probe=98199f8421) | Apr 07, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [839c8344be](https://linux-hardware.org/?probe=839c8344be) | Apr 07, 2020 |
| ASUSTek       | 1015CX                      | Notebook    | [c98f5bcee3](https://linux-hardware.org/?probe=c98f5bcee3) | Apr 05, 2020 |
| ASUSTek       | 1015CX                      | Notebook    | [216b680d21](https://linux-hardware.org/?probe=216b680d21) | Apr 05, 2020 |
| Dell          | Latitude 7350               | Notebook    | [3ecdea8fcc](https://linux-hardware.org/?probe=3ecdea8fcc) | Apr 03, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [0dbe97d54b](https://linux-hardware.org/?probe=0dbe97d54b) | Mar 30, 2020 |
| HP            | 3397                        | Desktop     | [f2d1e62e57](https://linux-hardware.org/?probe=f2d1e62e57) | Mar 29, 2020 |
| HP            | 3646h                       | Desktop     | [63c3bf2b90](https://linux-hardware.org/?probe=63c3bf2b90) | Mar 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ffeee579db](https://linux-hardware.org/?probe=ffeee579db) | Mar 28, 2020 |
| Dell          | Inspiron 3443               | Notebook    | [0a21a54858](https://linux-hardware.org/?probe=0a21a54858) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [aa94d9ab9b](https://linux-hardware.org/?probe=aa94d9ab9b) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [96f26b673c](https://linux-hardware.org/?probe=96f26b673c) | Mar 28, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [21b92f29e5](https://linux-hardware.org/?probe=21b92f29e5) | Mar 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e7effd8e19](https://linux-hardware.org/?probe=e7effd8e19) | Mar 23, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [ec35befc4a](https://linux-hardware.org/?probe=ec35befc4a) | Mar 23, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6f1f96e7fc](https://linux-hardware.org/?probe=6f1f96e7fc) | Mar 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [aa7093b56c](https://linux-hardware.org/?probe=aa7093b56c) | Mar 23, 2020 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [b7d3805ba6](https://linux-hardware.org/?probe=b7d3805ba6) | Mar 23, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [a79912cfdf](https://linux-hardware.org/?probe=a79912cfdf) | Mar 22, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [409951a0dd](https://linux-hardware.org/?probe=409951a0dd) | Mar 20, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| Dell          | Studio 1558                 | Notebook    | [06b0f26f6a](https://linux-hardware.org/?probe=06b0f26f6a) | Mar 12, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| Dell          | Studio 1558                 | Notebook    | [57fddb1856](https://linux-hardware.org/?probe=57fddb1856) | Mar 12, 2020 |
| MSI           | B250M PRO-VH                | Desktop     | [1eb2d76730](https://linux-hardware.org/?probe=1eb2d76730) | Mar 10, 2020 |
| ECS           | 945GCT-M                    | Desktop     | [069450c325](https://linux-hardware.org/?probe=069450c325) | Mar 08, 2020 |
| Gigabyte      | M1689D                      | Desktop     | [9f48604ff2](https://linux-hardware.org/?probe=9f48604ff2) | Mar 07, 2020 |
| Gigabyte      | M1689D                      | Desktop     | [43f9f0167a](https://linux-hardware.org/?probe=43f9f0167a) | Mar 07, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [b224a48803](https://linux-hardware.org/?probe=b224a48803) | Mar 04, 2020 |
| ASUSTek       | N82JQ                       | Notebook    | [b1b698b060](https://linux-hardware.org/?probe=b1b698b060) | Mar 02, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [80b614b253](https://linux-hardware.org/?probe=80b614b253) | Mar 02, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [910ec05246](https://linux-hardware.org/?probe=910ec05246) | Feb 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [ddb0fad848](https://linux-hardware.org/?probe=ddb0fad848) | Feb 29, 2020 |
| Lenovo        | ThinkCentre M58 7360EHU     | Desktop     | [7067a56ae2](https://linux-hardware.org/?probe=7067a56ae2) | Feb 27, 2020 |
| ASUSTek       | UX360UAK                    | Convertible | [e378eda49c](https://linux-hardware.org/?probe=e378eda49c) | Feb 21, 2020 |
| ASUSTek       | UX360UAK                    | Convertible | [8063e9ef93](https://linux-hardware.org/?probe=8063e9ef93) | Feb 21, 2020 |
| Dell          | Vostro 1015                 | Notebook    | [091443df09](https://linux-hardware.org/?probe=091443df09) | Feb 20, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [98cee968eb](https://linux-hardware.org/?probe=98cee968eb) | Feb 18, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [c04cf86240](https://linux-hardware.org/?probe=c04cf86240) | Feb 15, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [00e7d3f0b6](https://linux-hardware.org/?probe=00e7d3f0b6) | Feb 15, 2020 |
| Lenovo        | V580c 20160                 | Notebook    | [7e02c8c738](https://linux-hardware.org/?probe=7e02c8c738) | Feb 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [0061763167](https://linux-hardware.org/?probe=0061763167) | Feb 11, 2020 |
| Sony          | VPCSB19GG                   | Notebook    | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | Notebook    | [dccdce5101](https://linux-hardware.org/?probe=dccdce5101) | Jan 23, 2020 |
| Dell          | Vostro 1510                 | Notebook    | [51fbe1ce5b](https://linux-hardware.org/?probe=51fbe1ce5b) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | Notebook    | [664116ebbf](https://linux-hardware.org/?probe=664116ebbf) | Jan 22, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f77d00b6ce](https://linux-hardware.org/?probe=f77d00b6ce) | Jan 10, 2020 |
| Dell          | Precision M4800             | Notebook    | [cc63357309](https://linux-hardware.org/?probe=cc63357309) | Jan 09, 2020 |
| Lenovo        | ThinkPad X131e 33711T4      | Notebook    | [f06e98b417](https://linux-hardware.org/?probe=f06e98b417) | Jan 08, 2020 |
| HP            | 8054                        | Desktop     | [b9f8081fe1](https://linux-hardware.org/?probe=b9f8081fe1) | Jan 06, 2020 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [9d6c061d8b](https://linux-hardware.org/?probe=9d6c061d8b) | Jan 04, 2020 |
| HP            | ProBook 4540s               | Notebook    | [9ef64f7487](https://linux-hardware.org/?probe=9ef64f7487) | Jan 03, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [63fd9a500f](https://linux-hardware.org/?probe=63fd9a500f) | Dec 27, 2019 |
| Lenovo        | G510 20238                  | Notebook    | [8543221f24](https://linux-hardware.org/?probe=8543221f24) | Dec 27, 2019 |
| HP            | EliteBook 2740p             | Notebook    | [82cb2d5e90](https://linux-hardware.org/?probe=82cb2d5e90) | Dec 26, 2019 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [61d0162de0](https://linux-hardware.org/?probe=61d0162de0) | Dec 21, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| ASUSTek       | X542UN                      | Notebook    | [4b7f71d936](https://linux-hardware.org/?probe=4b7f71d936) | Dec 14, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [f30b5e8075](https://linux-hardware.org/?probe=f30b5e8075) | Dec 09, 2019 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [130e16c2b6](https://linux-hardware.org/?probe=130e16c2b6) | Dec 08, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [a68627d7eb](https://linux-hardware.org/?probe=a68627d7eb) | Nov 28, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [15babe41d0](https://linux-hardware.org/?probe=15babe41d0) | Nov 26, 2019 |
| HP            | 18E7                        | Desktop     | [f728a63212](https://linux-hardware.org/?probe=f728a63212) | Nov 26, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [ed7fb8cbb9](https://linux-hardware.org/?probe=ed7fb8cbb9) | Nov 15, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [5e184acc59](https://linux-hardware.org/?probe=5e184acc59) | Nov 15, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [f13de25d56](https://linux-hardware.org/?probe=f13de25d56) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dda0a53712](https://linux-hardware.org/?probe=dda0a53712) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b86e3d7141](https://linux-hardware.org/?probe=b86e3d7141) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| HP            | Pavilion 15                 | Notebook    | [57540edaa7](https://linux-hardware.org/?probe=57540edaa7) | Nov 12, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [380140eb8d](https://linux-hardware.org/?probe=380140eb8d) | Nov 06, 2019 |
| Dell          | Vostro 1520                 | Notebook    | [247d9e9c2f](https://linux-hardware.org/?probe=247d9e9c2f) | Nov 01, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [89e9d28a32](https://linux-hardware.org/?probe=89e9d28a32) | Nov 01, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [797965c573](https://linux-hardware.org/?probe=797965c573) | Oct 30, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [63dc09b54e](https://linux-hardware.org/?probe=63dc09b54e) | Oct 28, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cf9411c533](https://linux-hardware.org/?probe=cf9411c533) | Oct 28, 2019 |
| Dell          | Vostro 1015                 | Notebook    | [400532e714](https://linux-hardware.org/?probe=400532e714) | Oct 24, 2019 |
| Dell          | Vostro 1015                 | Notebook    | [df8815e747](https://linux-hardware.org/?probe=df8815e747) | Oct 24, 2019 |
| ASUSTek       | N501VW                      | Notebook    | [4d2a1a9add](https://linux-hardware.org/?probe=4d2a1a9add) | Oct 16, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [d1394d6252](https://linux-hardware.org/?probe=d1394d6252) | Oct 11, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c8223df556](https://linux-hardware.org/?probe=c8223df556) | Oct 03, 2019 |
| Dell          | Inspiron N4050              | Notebook    | [153db5ae1b](https://linux-hardware.org/?probe=153db5ae1b) | Oct 01, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a814f0be14](https://linux-hardware.org/?probe=a814f0be14) | Sep 26, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [4c39be72b3](https://linux-hardware.org/?probe=4c39be72b3) | Sep 26, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [fbbabc5836](https://linux-hardware.org/?probe=fbbabc5836) | Sep 23, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [0143228659](https://linux-hardware.org/?probe=0143228659) | Sep 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [6e13970f68](https://linux-hardware.org/?probe=6e13970f68) | Sep 18, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [22d2f0f13e](https://linux-hardware.org/?probe=22d2f0f13e) | Sep 12, 2019 |
| ASUSTek       | X556UQK                     | Notebook    | [cd4ce4d624](https://linux-hardware.org/?probe=cd4ce4d624) | Sep 12, 2019 |
| ASUSTek       | B85-PLUS                    | Desktop     | [2665a9b231](https://linux-hardware.org/?probe=2665a9b231) | Sep 11, 2019 |
| ECS           | 945PT-A2                    | Desktop     | [e73a14a3e7](https://linux-hardware.org/?probe=e73a14a3e7) | Sep 10, 2019 |
| HP            | Pavilion 15                 | Notebook    | [c56817e0e4](https://linux-hardware.org/?probe=c56817e0e4) | Sep 10, 2019 |
| ASUSTek       | M3N78-EH                    | Desktop     | [0ded7435b9](https://linux-hardware.org/?probe=0ded7435b9) | Sep 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [81b3b2667e](https://linux-hardware.org/?probe=81b3b2667e) | Sep 03, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [a4f33fd40a](https://linux-hardware.org/?probe=a4f33fd40a) | Sep 03, 2019 |
| HP            | ProBook 4540s               | Notebook    | [1349a15c0f](https://linux-hardware.org/?probe=1349a15c0f) | Sep 01, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [eaf9b72412](https://linux-hardware.org/?probe=eaf9b72412) | Aug 31, 2019 |
| Lenovo        | ThinkPad E470 20H1002DAD    | Notebook    | [75804928d2](https://linux-hardware.org/?probe=75804928d2) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [579809b8b0](https://linux-hardware.org/?probe=579809b8b0) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [81e015523a](https://linux-hardware.org/?probe=81e015523a) | Aug 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [72437e888c](https://linux-hardware.org/?probe=72437e888c) | Aug 29, 2019 |
| ASUSTek       | X102BA                      | Notebook    | [8365a8b9d6](https://linux-hardware.org/?probe=8365a8b9d6) | Aug 27, 2019 |
| ASUSTek       | X102BA                      | Notebook    | [43b9931c92](https://linux-hardware.org/?probe=43b9931c92) | Aug 26, 2019 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [be649fc45f](https://linux-hardware.org/?probe=be649fc45f) | Aug 25, 2019 |
| MSI           | MS-1454                     | Notebook    | [b03f58cc28](https://linux-hardware.org/?probe=b03f58cc28) | Aug 23, 2019 |
| MSI           | MS-1454                     | Notebook    | [94bfc26599](https://linux-hardware.org/?probe=94bfc26599) | Aug 23, 2019 |
| ASUSTek       | X540UPR                     | Notebook    | [2f40c492db](https://linux-hardware.org/?probe=2f40c492db) | Aug 12, 2019 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [24c83ab728](https://linux-hardware.org/?probe=24c83ab728) | Aug 09, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | Notebook    | [2507713bd4](https://linux-hardware.org/?probe=2507713bd4) | Aug 06, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | Notebook    | [0ad209e005](https://linux-hardware.org/?probe=0ad209e005) | Aug 06, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [541fb4f240](https://linux-hardware.org/?probe=541fb4f240) | Aug 06, 2019 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [d0ac33919a](https://linux-hardware.org/?probe=d0ac33919a) | Aug 05, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [2ab556fd2e](https://linux-hardware.org/?probe=2ab556fd2e) | Aug 03, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [3ff8ae9e18](https://linux-hardware.org/?probe=3ff8ae9e18) | Aug 01, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [9518b70a0d](https://linux-hardware.org/?probe=9518b70a0d) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [9c80796306](https://linux-hardware.org/?probe=9c80796306) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [66cc9aa111](https://linux-hardware.org/?probe=66cc9aa111) | Jul 31, 2019 |
| HP            | Pavilion dv6                | Notebook    | [38f37f78c5](https://linux-hardware.org/?probe=38f37f78c5) | Jul 29, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Iran/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 108       | 14.48%  |
| Ubuntu 18.04       | 84        | 11.26%  |
| Ubuntu 22.04       | 67        | 8.98%   |
| Arch Rolling       | 22        | 2.95%   |
| Arch               | 19        | 2.55%   |
| Ubuntu 19.04       | 16        | 2.14%   |
| Fedora 33          | 14        | 1.88%   |
| Fedora 38          | 13        | 1.74%   |
| ArcoLinux Rolling  | 13        | 1.74%   |
| Debian 11          | 11        | 1.47%   |
| Ubuntu 21.10       | 10        | 1.34%   |
| Ubuntu 20.10       | 10        | 1.34%   |
| Manjaro            | 10        | 1.34%   |
| KDE neon 20.04     | 10        | 1.34%   |
| Xubuntu 18.04      | 9         | 1.21%   |
| Fedora 34          | 9         | 1.21%   |
| Ubuntu 23.10       | 8         | 1.07%   |
| Ubuntu 19.10       | 8         | 1.07%   |
| OpenMandriva 4.2   | 8         | 1.07%   |
| OpenMandriva 23.08 | 7         | 0.94%   |
| Debian 12          | 7         | 0.94%   |
| Xubuntu 22.04      | 6         | 0.8%    |
| Xubuntu 20.04      | 6         | 0.8%    |
| Ubuntu 23.04       | 6         | 0.8%    |
| Ubuntu 21.04       | 6         | 0.8%    |
| OpenMandriva 4.3   | 6         | 0.8%    |
| Linux Mint 20.3    | 6         | 0.8%    |
| Fedora 37          | 6         | 0.8%    |
| Ubuntu 22.10       | 5         | 0.67%   |
| Fedora 35          | 5         | 0.67%   |
| Zorin 16           | 4         | 0.54%   |
| Zorin 15           | 4         | 0.54%   |
| Ubuntu 18.10       | 4         | 0.54%   |
| Pop!_OS 22.04      | 4         | 0.54%   |
| Linux Mint 21.3    | 4         | 0.54%   |
| Linux Mint 21.1    | 4         | 0.54%   |
| Kubuntu 20.04      | 4         | 0.54%   |
| Kali 2021.2        | 4         | 0.54%   |
| Fedora 31          | 4         | 0.54%   |
| Debian             | 4         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu             | 328       | 45.3%   |
| Fedora             | 60        | 8.29%   |
| Arch               | 39        | 5.39%   |
| Manjaro            | 32        | 4.42%   |
| Linux Mint         | 31        | 4.28%   |
| OpenMandriva       | 28        | 3.87%   |
| Debian             | 25        | 3.45%   |
| Xubuntu            | 21        | 2.9%    |
| Kali               | 16        | 2.21%   |
| Endless            | 16        | 2.21%   |
| Kubuntu            | 15        | 2.07%   |
| KDE neon           | 15        | 2.07%   |
| ArcoLinux          | 13        | 1.8%    |
| Zorin              | 12        | 1.66%   |
| Pop!_OS            | 12        | 1.66%   |
| ROSA               | 6         | 0.83%   |
| Lubuntu            | 6         | 0.83%   |
| Ubuntu Unity       | 5         | 0.69%   |
| Ubuntu Budgie      | 4         | 0.55%   |
| openSUSE           | 4         | 0.55%   |
| Elementary         | 4         | 0.55%   |
| Parch              | 3         | 0.41%   |
| Gentoo             | 3         | 0.41%   |
| CentOS             | 3         | 0.41%   |
| Xero               | 2         | 0.28%   |
| Solus              | 2         | 0.28%   |
| Clear Linux        | 2         | 0.28%   |
| Artix              | 2         | 0.28%   |
| Ubuntu MATE        | 1         | 0.14%   |
| Slackware          | 1         | 0.14%   |
| Sabayon            | 1         | 0.14%   |
| Rocky Linux        | 1         | 0.14%   |
| Raspbian           | 1         | 0.14%   |
| PureOS             | 1         | 0.14%   |
| NixOS              | 1         | 0.14%   |
| MX                 | 1         | 0.14%   |
| LMDE               | 1         | 0.14%   |
| Linux Lite         | 1         | 0.14%   |
| GNOME OS           | 1         | 0.14%   |
| Fedora-asahi-remix | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 1.9%    |
| 5.4.0-26-generic         | 9         | 1.14%   |
| 6.5.0-26-generic         | 8         | 1.01%   |
| 5.3.0-46-generic         | 8         | 1.01%   |
| 5.15.0-47-generic        | 8         | 1.01%   |
| 5.10.14-desktop-1omv4002 | 8         | 1.01%   |
| 5.4.0-58-generic         | 7         | 0.89%   |
| 5.4.0-52-generic         | 7         | 0.89%   |
| 5.3.0-40-generic         | 7         | 0.89%   |
| 5.15.0-56-generic        | 7         | 0.89%   |
| 5.11.0-27-generic        | 7         | 0.89%   |
| 6.5.0-9-generic          | 6         | 0.76%   |
| 5.4.0-48-generic         | 6         | 0.76%   |
| 5.16.7-desktop-1omv4003  | 6         | 0.76%   |
| 5.11.0-41-generic        | 6         | 0.76%   |
| 5.0.0-23-generic         | 6         | 0.76%   |
| 6.4.11-desktop-1omv2390  | 5         | 0.63%   |
| 6.2.0-20-generic         | 5         | 0.63%   |
| 5.8.0-63-generic         | 5         | 0.63%   |
| 5.8.0-48-generic         | 5         | 0.63%   |
| 5.15.0-58-generic        | 5         | 0.63%   |
| 5.0.0-37-generic         | 5         | 0.63%   |
| 5.0.0-25-generic         | 5         | 0.63%   |
| 5.0.0-13-generic         | 5         | 0.63%   |
| 4.18.0-15-generic        | 5         | 0.63%   |
| 4.15.0-29-generic        | 5         | 0.63%   |
| 6.5.0-21-generic         | 4         | 0.51%   |
| 6.2.9-300.fc38.x86_64    | 4         | 0.51%   |
| 6.2.0-39-generic         | 4         | 0.51%   |
| 6.2.0-35-generic         | 4         | 0.51%   |
| 5.8.0-50-generic         | 4         | 0.51%   |
| 5.3.0-51-generic         | 4         | 0.51%   |
| 5.19.0-35-generic        | 4         | 0.51%   |
| 5.13.0-30-generic        | 4         | 0.51%   |
| 4.18.0-25-generic        | 4         | 0.51%   |
| 4.18.0-18-generic        | 4         | 0.51%   |
| 6.5.0-28-generic         | 3         | 0.38%   |
| 6.5.0-18-generic         | 3         | 0.38%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.38%   |
| 5.8.0-59-generic         | 3         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 106       | 13.84%  |
| 5.15.0  | 61        | 7.96%   |
| 4.15.0  | 39        | 5.09%   |
| 5.0.0   | 38        | 4.96%   |
| 5.11.0  | 35        | 4.57%   |
| 5.8.0   | 34        | 4.44%   |
| 5.3.0   | 33        | 4.31%   |
| 6.5.0   | 31        | 4.05%   |
| 5.13.0  | 29        | 3.79%   |
| 4.18.0  | 25        | 3.26%   |
| 6.2.0   | 21        | 2.74%   |
| 5.19.0  | 21        | 2.74%   |
| 5.10.0  | 16        | 2.09%   |
| 6.4.11  | 9         | 1.17%   |
| 6.1.0   | 9         | 1.17%   |
| 5.10.14 | 8         | 1.04%   |
| 5.16.7  | 7         | 0.91%   |
| 4.13.0  | 6         | 0.78%   |
| 6.2.9   | 5         | 0.65%   |
| 5.8.18  | 4         | 0.52%   |
| 5.16.15 | 4         | 0.52%   |
| 5.11.11 | 4         | 0.52%   |
| 6.7.4   | 3         | 0.39%   |
| 6.5.9   | 3         | 0.39%   |
| 6.4.12  | 3         | 0.39%   |
| 6.2.6   | 3         | 0.39%   |
| 5.9.16  | 3         | 0.39%   |
| 5.6.0   | 3         | 0.39%   |
| 5.18.0  | 3         | 0.39%   |
| 5.16.0  | 3         | 0.39%   |
| 5.14.16 | 3         | 0.39%   |
| 5.13.19 | 3         | 0.39%   |
| 6.8.9   | 2         | 0.26%   |
| 6.8.7   | 2         | 0.26%   |
| 6.7.0   | 2         | 0.26%   |
| 6.6.4   | 2         | 0.26%   |
| 6.6.10  | 2         | 0.26%   |
| 6.5.4   | 2         | 0.26%   |
| 6.4.8   | 2         | 0.26%   |
| 6.4.3   | 2         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 112       | 14.78%  |
| 5.15    | 75        | 9.89%   |
| 5.8     | 46        | 6.07%   |
| 5.11    | 44        | 5.8%    |
| 5.0     | 41        | 5.41%   |
| 4.15    | 39        | 5.15%   |
| 6.5     | 38        | 5.01%   |
| 5.13    | 38        | 5.01%   |
| 6.2     | 34        | 4.49%   |
| 5.3     | 34        | 4.49%   |
| 5.10    | 34        | 4.49%   |
| 4.18    | 25        | 3.3%    |
| 6.4     | 24        | 3.17%   |
| 5.19    | 23        | 3.03%   |
| 6.1     | 19        | 2.51%   |
| 5.16    | 18        | 2.37%   |
| 6.6     | 14        | 1.85%   |
| 5.14    | 12        | 1.58%   |
| 6.3     | 8         | 1.06%   |
| 5.9     | 8         | 1.06%   |
| 5.18    | 8         | 1.06%   |
| 6.0     | 7         | 0.92%   |
| 5.6     | 7         | 0.92%   |
| 5.12    | 7         | 0.92%   |
| 6.8     | 6         | 0.79%   |
| 6.7     | 6         | 0.79%   |
| 4.13    | 6         | 0.79%   |
| 5.7     | 5         | 0.66%   |
| 4.19    | 5         | 0.66%   |
| 5.17    | 3         | 0.4%    |
| 4.9     | 3         | 0.4%    |
| 5.5     | 2         | 0.26%   |
| 4.14    | 2         | 0.26%   |
| 5.2     | 1         | 0.13%   |
| 4.5     | 1         | 0.13%   |
| 4.20    | 1         | 0.13%   |
| 4.12    | 1         | 0.13%   |
| 3.10    | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 691       | 97.32%  |
| i686    | 15        | 2.11%   |
| aarch64 | 3         | 0.42%   |
| armv7l  | 1         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 400       | 54.72%  |
| Unknown       | 96        | 13.13%  |
| KDE5          | 79        | 10.81%  |
| XFCE          | 59        | 8.07%   |
| X-Cinnamon    | 27        | 3.69%   |
| KDE           | 18        | 2.46%   |
| i3            | 10        | 1.37%   |
| LXQt          | 8         | 1.09%   |
| MATE          | 6         | 0.82%   |
| Budgie        | 6         | 0.82%   |
| Unity         | 5         | 0.68%   |
| Pantheon      | 4         | 0.55%   |
| KDE4          | 2         | 0.27%   |
| Cinnamon      | 2         | 0.27%   |
| bspwm         | 2         | 0.27%   |
| Trinity       | 1         | 0.14%   |
| sway          | 1         | 0.14%   |
| LXDE          | 1         | 0.14%   |
| KDE6          | 1         | 0.14%   |
| GNOME Classic | 1         | 0.14%   |
| enlightenment | 1         | 0.14%   |
| Deepin        | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 496       | 68.04%  |
| Wayland | 155       | 21.26%  |
| Unknown | 70        | 9.6%    |
| Tty     | 8         | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 360       | 49.05%  |
| GDM3    | 108       | 14.71%  |
| GDM     | 100       | 13.62%  |
| SDDM    | 84        | 11.44%  |
| LightDM | 61        | 8.31%   |
| TDM     | 14        | 1.91%   |
| XDM     | 2         | 0.27%   |
| Ly      | 2         | 0.27%   |
| KDM     | 2         | 0.27%   |
| LXDM    | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 569       | 79.14%  |
| Unknown | 91        | 12.66%  |
| en_GB   | 20        | 2.78%   |
| fa_IR   | 13        | 1.81%   |
| C       | 12        | 1.67%   |
| en_CA   | 7         | 0.97%   |
| en_AG   | 2         | 0.28%   |
| ru_RU   | 1         | 0.14%   |
| POSIX   | 1         | 0.14%   |
| ja_JP   | 1         | 0.14%   |
| de_DE   | 1         | 0.14%   |
| az_IR   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 386       | 53.31%  |
| EFI  | 338       | 46.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 562       | 78.16%  |
| Btrfs   | 57        | 7.93%   |
| Overlay | 37        | 5.15%   |
| Tmpfs   | 28        | 3.89%   |
| Unknown | 18        | 2.5%    |
| Xfs     | 8         | 1.11%   |
| Zfs     | 6         | 0.83%   |
| Ext3    | 2         | 0.28%   |
| Ext2    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 396       | 55.08%  |
| GPT     | 265       | 36.86%  |
| MBR     | 58        | 8.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 612       | 84.76%  |
| Yes       | 110       | 15.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 393       | 54.89%  |
| Yes       | 323       | 45.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 240       | 33.8%   |
| Lenovo                  | 135       | 19.01%  |
| Hewlett-Packard         | 105       | 14.79%  |
| Dell                    | 49        | 6.9%    |
| Acer                    | 43        | 6.06%   |
| Gigabyte Technology     | 41        | 5.77%   |
| MSI                     | 24        | 3.38%   |
| Sony                    | 14        | 1.97%   |
| Toshiba                 | 8         | 1.13%   |
| Apple                   | 8         | 1.13%   |
| ECS                     | 7         | 0.99%   |
| Unknown                 | 6         | 0.85%   |
| ASRock                  | 5         | 0.7%    |
| Microsoft               | 3         | 0.42%   |
| Fujitsu                 | 3         | 0.42%   |
| YANYU                   | 2         | 0.28%   |
| Raspberry Pi Foundation | 2         | 0.28%   |
| Biostar                 | 2         | 0.28%   |
| Timi                    | 1         | 0.14%   |
| Supermicro              | 1         | 0.14%   |
| Samsung Electronics     | 1         | 0.14%   |
| Rockchip                | 1         | 0.14%   |
| Razer                   | 1         | 0.14%   |
| Packard Bell            | 1         | 0.14%   |
| LG Electronics          | 1         | 0.14%   |
| Intel                   | 1         | 0.14%   |
| HPE                     | 1         | 0.14%   |
| HIGRADED                | 1         | 0.14%   |
| Foxconn                 | 1         | 0.14%   |
| Alienware               | 1         | 0.14%   |
| 3Logic Group            | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 15        | 2.11%   |
| HP Compaq Elite 8300 SFF                   | 8         | 1.13%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 6         | 0.85%   |
| HP ProBook 4540s                           | 6         | 0.85%   |
| Acer Aspire V3-571G                        | 6         | 0.85%   |
| Unknown                                    | 6         | 0.85%   |
| Lenovo IdeaPad Z510 20287                  | 5         | 0.7%    |
| Lenovo G50-70 20351                        | 5         | 0.7%    |
| Lenovo B570e HuronRiver Platform           | 4         | 0.56%   |
| HP Pavilion g6                             | 4         | 0.56%   |
| HP EliteBook 8470p                         | 4         | 0.56%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR       | 4         | 0.56%   |
| Lenovo Z50-70 20354                        | 3         | 0.42%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK      | 3         | 0.42%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 3         | 0.42%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 3         | 0.42%   |
| Lenovo G50-80 80E5                         | 3         | 0.42%   |
| HP ZBook 17 G3                             | 3         | 0.42%   |
| HP EliteBook 8570p                         | 3         | 0.42%   |
| HP EliteBook 840 G2                        | 3         | 0.42%   |
| Dell Vostro 1015                           | 3         | 0.42%   |
| ASUS X580VD                                | 3         | 0.42%   |
| ASUS VivoBook 15_ASUS Laptop X540MB_X540MB | 3         | 0.42%   |
| ASUS PRIME B250-PLUS                       | 3         | 0.42%   |
| ASUS P5P41T-LE                             | 3         | 0.42%   |
| ASUS K55VD                                 | 3         | 0.42%   |
| ASUS H61M-C                                | 3         | 0.42%   |
| Toshiba PORTEGE X30-D                      | 2         | 0.28%   |
| MSI Prestige 14 A10RB                      | 2         | 0.28%   |
| Microsoft Surface Book 2                   | 2         | 0.28%   |
| Lenovo V330-15IKB 81AX                     | 2         | 0.28%   |
| Lenovo ThinkPad X250 20CM002XUS            | 2         | 0.28%   |
| Lenovo ThinkPad E15 20RD0086UE             | 2         | 0.28%   |
| Lenovo ThinkBook 15-IIL 20SM               | 2         | 0.28%   |
| Lenovo Legion 5 15IMH05H 81Y6              | 2         | 0.28%   |
| Lenovo Legion 5 15ARH05H 82B1              | 2         | 0.28%   |
| Lenovo IdeaPad S540-15IWL GTX 81SW         | 2         | 0.28%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 2         | 0.28%   |
| Lenovo IdeaPad 520-15IKB 81BF              | 2         | 0.28%   |
| Lenovo IdeaPad 5 14ALC05 82LM              | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo IdeaPad    | 50        | 7.04%   |
| Acer Aspire       | 37        | 5.21%   |
| ASUS VivoBook     | 36        | 5.07%   |
| Lenovo ThinkPad   | 33        | 4.65%   |
| HP EliteBook      | 27        | 3.8%    |
| ASUS PRIME        | 26        | 3.66%   |
| HP ProBook        | 18        | 2.54%   |
| Dell Latitude     | 16        | 2.25%   |
| ASUS All          | 15        | 2.11%   |
| Dell Inspiron     | 14        | 1.97%   |
| HP Compaq         | 13        | 1.83%   |
| Dell Vostro       | 11        | 1.55%   |
| ASUS ASUS         | 11        | 1.55%   |
| HP Pavilion       | 10        | 1.41%   |
| ASUS TUF          | 10        | 1.41%   |
| ASUS ROG          | 9         | 1.27%   |
| Lenovo Legion     | 8         | 1.13%   |
| HP ZBook          | 6         | 0.85%   |
| Unknown           | 6         | 0.85%   |
| Toshiba Satellite | 5         | 0.7%    |
| Lenovo G50-70     | 5         | 0.7%    |
| HP EliteDesk      | 5         | 0.7%    |
| Lenovo ThinkBook  | 4         | 0.56%   |
| Lenovo B570e      | 4         | 0.56%   |
| HP ProLiant       | 4         | 0.56%   |
| HP ProDesk        | 4         | 0.56%   |
| ASUS ZenBook      | 4         | 0.56%   |
| Toshiba PORTEGE   | 3         | 0.42%   |
| MSI Modern        | 3         | 0.42%   |
| Microsoft Surface | 3         | 0.42%   |
| Lenovo Z50-70     | 3         | 0.42%   |
| Lenovo G50-80     | 3         | 0.42%   |
| Fujitsu LIFEBOOK  | 3         | 0.42%   |
| Dell Precision    | 3         | 0.42%   |
| ASUS X580VD       | 3         | 0.42%   |
| ASUS P8H61        | 3         | 0.42%   |
| ASUS P5P41T-LE    | 3         | 0.42%   |
| ASUS K55VD        | 3         | 0.42%   |
| ASUS H61M-C       | 3         | 0.42%   |
| Acer TravelMate   | 3         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 74        | 10.42%  |
| 2012    | 70        | 9.86%   |
| 2017    | 55        | 7.75%   |
| 2011    | 53        | 7.46%   |
| 2018    | 48        | 6.76%   |
| 2016    | 47        | 6.62%   |
| 2014    | 45        | 6.34%   |
| 2010    | 44        | 6.2%    |
| 2015    | 43        | 6.06%   |
| 2020    | 42        | 5.92%   |
| 2019    | 42        | 5.92%   |
| 2021    | 40        | 5.63%   |
| 2009    | 33        | 4.65%   |
| 2008    | 22        | 3.1%    |
| 2022    | 20        | 2.82%   |
| 2007    | 11        | 1.55%   |
| 2006    | 8         | 1.13%   |
| 2023    | 6         | 0.85%   |
| Unknown | 4         | 0.56%   |
| 2005    | 2         | 0.28%   |
| 2004    | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 491       | 69.15%  |
| Desktop        | 191       | 26.9%   |
| Tablet         | 8         | 1.13%   |
| Server         | 7         | 0.99%   |
| Convertible    | 5         | 0.7%    |
| System on chip | 3         | 0.42%   |
| Mini pc        | 3         | 0.42%   |
| All in one     | 2         | 0.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 669       | 94.09%  |
| Enabled  | 42        | 5.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 710       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 215       | 30.11%  |
| 8.01-16.0       | 152       | 21.29%  |
| 16.01-24.0      | 137       | 19.19%  |
| 3.01-4.0        | 130       | 18.21%  |
| 32.01-64.0      | 33        | 4.62%   |
| 1.01-2.0        | 21        | 2.94%   |
| 2.01-3.0        | 12        | 1.68%   |
| 64.01-256.0     | 5         | 0.7%    |
| 0.51-1.0        | 4         | 0.56%   |
| 24.01-32.0      | 3         | 0.42%   |
| More than 256.0 | 2         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 251       | 32.81%  |
| 2.01-3.0   | 228       | 29.8%   |
| 3.01-4.0   | 120       | 15.69%  |
| 4.01-8.0   | 95        | 12.42%  |
| 0.51-1.0   | 36        | 4.71%   |
| 8.01-16.0  | 23        | 3.01%   |
| 0.01-0.5   | 9         | 1.18%   |
| 16.01-24.0 | 2         | 0.26%   |
| 24.01-32.0 | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 454       | 62.97%  |
| 2       | 210       | 29.13%  |
| 3       | 38        | 5.27%   |
| 4       | 10        | 1.39%   |
| 5       | 3         | 0.42%   |
| 0       | 3         | 0.42%   |
| 6       | 2         | 0.28%   |
| Unknown | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 403       | 56.21%  |
| Yes       | 314       | 43.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 626       | 88.05%  |
| No        | 85        | 11.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 596       | 83.24%  |
| No        | 120       | 16.76%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 453       | 63.27%  |
| No        | 263       | 36.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Iran    | 710       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 431       | 57.77%  |
| TehrДЃn                      | 46        | 6.17%   |
| Mashhad                        | 28        | 3.75%   |
| Isfahan                        | 27        | 3.62%   |
| Karaj                          | 15        | 2.01%   |
| Shiraz                         | 14        | 1.88%   |
| Tajrish                        | 9         | 1.21%   |
| Tabriz                         | 8         | 1.07%   |
| Qom                            | 8         | 1.07%   |
| Babol                          | 8         | 1.07%   |
| Khorramshahr                   | 7         | 0.94%   |
| Yazd                           | 6         | 0.8%    |
| Sanandij                       | 6         | 0.8%    |
| Rasht                          | 6         | 0.8%    |
| Kerman                         | 5         | 0.67%   |
| Ahvaz                          | 5         | 0.67%   |
| TajrД«sh                     | 3         | 0.4%    |
| Kermanshah                     | 3         | 0.4%    |
| Gorgan                         | 3         | 0.4%    |
| Arak                           | 3         | 0.4%    |
| Zanjan                         | 2         | 0.27%   |
| Shahre Jadide Andisheh         | 2         | 0.27%   |
| Shahr-e Qods                   | 2         | 0.27%   |
| Shahr-e Kord                   | 2         | 0.27%   |
| Sari                           | 2         | 0.27%   |
| Rey                            | 2         | 0.27%   |
| Rehnān                        | 2         | 0.27%   |
| Qazvin                         | 2         | 0.27%   |
| Mīāndoāb                    | 2         | 0.27%   |
| Markaz                         | 2         | 0.27%   |
| Hamadan                        | 2         | 0.27%   |
| Gachsaran                      | 2         | 0.27%   |
| Farsan                         | 2         | 0.27%   |
| DamДЃvand                    | 2         | 0.27%   |
| BorЕ«jerd                    | 2         | 0.27%   |
| Behshahr                       | 2         | 0.27%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.13%   |
| Varamin                        | 1         | 0.13%   |
| Tonekabon                      | 1         | 0.13%   |
| Tīrān                        | 1         | 0.13%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC                          | 187       | 238    | 19.4%   |
| Seagate                      | 162       | 197    | 16.8%   |
| Samsung Electronics          | 117       | 139    | 12.14%  |
| Toshiba                      | 105       | 126    | 10.89%  |
| A-DATA Technology            | 43        | 50     | 4.46%   |
| SanDisk                      | 28        | 33     | 2.9%    |
| Micron Technology            | 26        | 29     | 2.7%    |
| Intel                        | 24        | 24     | 2.49%   |
| Maxtor                       | 23        | 30     | 2.39%   |
| HGST                         | 22        | 26     | 2.28%   |
| Unknown                      | 20        | 21     | 2.07%   |
| Lexar                        | 19        | 24     | 1.97%   |
| Hitachi                      | 18        | 20     | 1.87%   |
| Kingston                     | 16        | 22     | 1.66%   |
| SK hynix                     | 14        | 17     | 1.45%   |
| PNY                          | 8         | 10     | 0.83%   |
| SPCC                         | 7         | 9      | 0.73%   |
| Apacer                       | 7         | 7      | 0.73%   |
| LITEON                       | 6         | 7      | 0.62%   |
| Kingmax                      | 6         | 6      | 0.62%   |
| Gigabyte Technology          | 6         | 7      | 0.62%   |
| Apple                        | 6         | 9      | 0.62%   |
| Silicon Motion               | 5         | 5      | 0.52%   |
| Crucial                      | 5         | 5      | 0.52%   |
| Unknown                      | 5         | 6      | 0.52%   |
| Plextor                      | 4         | 4      | 0.41%   |
| Union Memory (Shenzhen)      | 3         | 3      | 0.31%   |
| Team                         | 3         | 3      | 0.31%   |
| Shenzhen Longsys Electronics | 3         | 5      | 0.31%   |
| MSI                          | 3         | 3      | 0.31%   |
| LITEONIT                     | 3         | 4      | 0.31%   |
| Hewlett-Packard              | 3         | 3      | 0.31%   |
| Biostar                      | 3         | 4      | 0.31%   |
| ValueTech                    | 2         | 3      | 0.21%   |
| Union Memory                 | 2         | 2      | 0.21%   |
| Realtek Semiconductor        | 2         | 3      | 0.21%   |
| OCZ                          | 2         | 2      | 0.21%   |
| MAXIO Technology (Hangzhou)  | 2         | 2      | 0.21%   |
| KODAK                        | 2         | 2      | 0.21%   |
| China                        | 2         | 2      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 41        | 4.08%   |
| Toshiba MQ01ABD100 1TB                            | 20        | 1.99%   |
| Toshiba MQ04ABF100 1TB                            | 18        | 1.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 16        | 1.59%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 15        | 1.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 11        | 1.1%    |
| Seagate ST9500325AS 500GB                         | 11        | 1.1%    |
| WDC WD10SPZX-24Z10 1TB                            | 10        | 1%      |
| WDC WD10SPZX-08Z10 1TB                            | 10        | 1%      |
| Samsung SSD 860 EVO 500GB                         | 10        | 1%      |
| A-DATA SU650 120GB SSD                            | 10        | 1%      |
| WDC WD10JPCX-24UE4T0 1TB                          | 9         | 0.9%    |
| Toshiba MQ01ABF050 500GB                          | 9         | 0.9%    |
| Samsung SSD 860 EVO 250GB                         | 9         | 0.9%    |
| Seagate ST500DM002-1BD142 500GB                   | 8         | 0.8%    |
| Samsung SSD 850 EVO 250GB                         | 8         | 0.8%    |
| Lexar 128GB SSD                                   | 7         | 0.7%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 6         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                   | 6         | 0.6%    |
| Micron 2210_MTFDHBA512QFD 512GB                   | 6         | 0.6%    |
| Maxtor STM3250310AS 250GB                         | 6         | 0.6%    |
| Lexar 256GB SSD                                   | 6         | 0.6%    |
| HGST HTS721010A9E630 1TB                          | 6         | 0.6%    |
| Unknown MMC Card  32GB                            | 5         | 0.5%    |
| Toshiba MQ01ABD075 752GB                          | 5         | 0.5%    |
| Toshiba MQ01ABD050V 500GB                         | 5         | 0.5%    |
| Toshiba MQ01ABD050 500GB                          | 5         | 0.5%    |
| Toshiba DT01ACA050 500GB                          | 5         | 0.5%    |
| Seagate ST9500420AS 500GB                         | 5         | 0.5%    |
| Seagate ST2000LM007-1R8174 2TB                    | 5         | 0.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 5         | 0.5%    |
| A-DATA SU630 240GB SSD                            | 5         | 0.5%    |
| Unknown                                           | 5         | 0.5%    |
| WDC WD10EZRX-00L4HB0 1TB                          | 4         | 0.4%    |
| SK hynix HFM001TD3JX013N 1024GB                   | 4         | 0.4%    |
| Seagate ST3500413AS 500GB                         | 4         | 0.4%    |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 4         | 0.4%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 4         | 0.4%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 4         | 0.4%    |
| Maxtor STM3160215AS 160GB                         | 4         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 162       | 197    | 32.27%  |
| WDC                 | 160       | 200    | 31.87%  |
| Toshiba             | 95        | 112    | 18.92%  |
| Maxtor              | 23        | 30     | 4.58%   |
| HGST                | 22        | 26     | 4.38%   |
| Hitachi             | 18        | 20     | 3.59%   |
| Samsung Electronics | 9         | 13     | 1.79%   |
| Hewlett-Packard     | 3         | 3      | 0.6%    |
| Apple               | 3         | 4      | 0.6%    |
| Unknown             | 2         | 2      | 0.4%    |
| TO Exter            | 1         | 1      | 0.2%    |
| Teleplan            | 1         | 4      | 0.2%    |
| HPE                 | 1         | 1      | 0.2%    |
| Fujitsu             | 1         | 1      | 0.2%    |
| Unknown             | 1         | 2      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 65        | 76     | 21.74%  |
| A-DATA Technology   | 43        | 50     | 14.38%  |
| WDC                 | 30        | 33     | 10.03%  |
| SanDisk             | 17        | 21     | 5.69%   |
| Lexar               | 17        | 20     | 5.69%   |
| Kingston            | 13        | 18     | 4.35%   |
| Micron Technology   | 12        | 12     | 4.01%   |
| SPCC                | 7         | 9      | 2.34%   |
| SK hynix            | 7         | 9      | 2.34%   |
| PNY                 | 7         | 8      | 2.34%   |
| LITEON              | 6         | 7      | 2.01%   |
| Gigabyte Technology | 6         | 7      | 2.01%   |
| Apacer              | 6         | 6      | 2.01%   |
| Toshiba             | 5         | 9      | 1.67%   |
| Intel               | 5         | 5      | 1.67%   |
| Crucial             | 5         | 5      | 1.67%   |
| Plextor             | 4         | 4      | 1.34%   |
| Kingmax             | 4         | 4      | 1.34%   |
| Team                | 3         | 3      | 1%      |
| MSI                 | 3         | 3      | 1%      |
| LITEONIT            | 3         | 4      | 1%      |
| Biostar             | 3         | 4      | 1%      |
| ValueTech           | 2         | 3      | 0.67%   |
| OCZ                 | 2         | 2      | 0.67%   |
| KODAK               | 2         | 2      | 0.67%   |
| China               | 2         | 2      | 0.67%   |
| Apple               | 2         | 2      | 0.67%   |
| X-ENERGY            | 1         | 1      | 0.33%   |
| Western             | 1         | 1      | 0.33%   |
| USB3.0              | 1         | 1      | 0.33%   |
| TwinMOS             | 1         | 1      | 0.33%   |
| Transcend           | 1         | 1      | 0.33%   |
| SSSTC               | 1         | 1      | 0.33%   |
| Pioneer             | 1         | 1      | 0.33%   |
| Patriot             | 1         | 1      | 0.33%   |
| OSCOO               | 1         | 2      | 0.33%   |
| Netac               | 1         | 1      | 0.33%   |
| MAX                 | 1         | 1      | 0.33%   |
| KingSpec            | 1         | 1      | 0.33%   |
| GeIL                | 1         | 1      | 0.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 470       | 616    | 51.14%  |
| SSD     | 284       | 347    | 30.9%   |
| NVMe    | 138       | 165    | 15.02%  |
| MMC     | 15        | 16     | 1.63%   |
| Unknown | 12        | 14     | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 611       | 955    | 77.93%  |
| NVMe | 138       | 165    | 17.6%   |
| SAS  | 20        | 22     | 2.55%   |
| MMC  | 15        | 16     | 1.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 414       | 562    | 56.17%  |
| 0.51-1.0   | 276       | 341    | 37.45%  |
| 1.01-2.0   | 30        | 39     | 4.07%   |
| 3.01-4.0   | 7         | 7      | 0.95%   |
| 2.01-3.0   | 5         | 7      | 0.68%   |
| 4.01-10.0  | 4         | 4      | 0.54%   |
| 10.01-20.0 | 1         | 3      | 0.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 203       | 27.43%  |
| 251-500        | 145       | 19.59%  |
| 501-1000       | 140       | 18.92%  |
| 51-100         | 68        | 9.19%   |
| 1001-2000      | 63        | 8.51%   |
| 21-50          | 42        | 5.68%   |
| 1-20           | 42        | 5.68%   |
| Unknown        | 14        | 1.89%   |
| More than 3000 | 12        | 1.62%   |
| 2001-3000      | 11        | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 279       | 36.86%  |
| 21-50          | 132       | 17.44%  |
| 51-100         | 102       | 13.47%  |
| 101-250        | 91        | 12.02%  |
| 501-1000       | 61        | 8.06%   |
| 251-500        | 59        | 7.79%   |
| Unknown        | 14        | 1.85%   |
| 1001-2000      | 9         | 1.19%   |
| More than 3000 | 6         | 0.79%   |
| 2001-3000      | 4         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB   | 5         | 6      | 6.58%   |
| Toshiba MQ01ABD100 1TB           | 3         | 3      | 3.95%   |
| Toshiba MQ01ABD075 752GB         | 3         | 3      | 3.95%   |
| Seagate ST9500420AS 500GB        | 3         | 3      | 3.95%   |
| Seagate ST9500325AS 500GB        | 3         | 8      | 3.95%   |
| Toshiba MQ01ABF050 500GB         | 2         | 7      | 2.63%   |
| Toshiba MQ01ABD050 500GB         | 2         | 2      | 2.63%   |
| SK hynix SC308 SATA 256GB SSD    | 2         | 2      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB  | 2         | 3      | 2.63%   |
| Seagate ST3500413AS 500GB        | 2         | 2      | 2.63%   |
| HGST HTS541075A9E680 752GB       | 2         | 2      | 2.63%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1         | 1      | 1.32%   |
| WDC WD7500BPVT-80HXZT1 752GB     | 1         | 3      | 1.32%   |
| WDC WD5000LPVX-80V0TT0 500GB     | 1         | 1      | 1.32%   |
| WDC WD5000LPCX-24C6HT0 500GB     | 1         | 1      | 1.32%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1         | 1      | 1.32%   |
| WDC WD5000AAKX-22ERMA0 500GB     | 1         | 2      | 1.32%   |
| WDC WD3200BPVT-75ZEST0 320GB     | 1         | 1      | 1.32%   |
| WDC WD3200AVVS-62L2B0 320GB      | 1         | 1      | 1.32%   |
| WDC WD10SPZX-24Z10 1TB           | 1         | 1      | 1.32%   |
| WDC WD10SPZX-08Z10 1TB           | 1         | 1      | 1.32%   |
| WDC WD10PURZ-85U8XY0 1TB         | 1         | 1      | 1.32%   |
| WDC WD10JPCX-24UE4T0 1TB         | 1         | 1      | 1.32%   |
| WDC WD10EZRX-00A3KB0 1TB         | 1         | 1      | 1.32%   |
| WDC WD10EZEX-00WN4A0 1TB         | 1         | 1      | 1.32%   |
| WDC WD10EARX-00N0YB0 1TB         | 1         | 1      | 1.32%   |
| WDC WD10EARS-00MVWB0 1TB         | 1         | 1      | 1.32%   |
| WDC WD1002FBYS-18A6B0 1TB        | 1         | 1      | 1.32%   |
| Toshiba MQ04ABF100 1TB           | 1         | 1      | 1.32%   |
| Toshiba MK3265GSXN 320GB         | 1         | 1      | 1.32%   |
| Toshiba MK3263GSX 320GB          | 1         | 1      | 1.32%   |
| Toshiba HDWD105 500GB            | 1         | 1      | 1.32%   |
| SSSTC CVB-8D128-HP 128GB SSD     | 1         | 1      | 1.32%   |
| Seagate ST9250315AS 250GB        | 1         | 2      | 1.32%   |
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 1.32%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 1.32%   |
| Seagate ST3500418AS 500GB        | 1         | 1      | 1.32%   |
| Seagate ST3320613AS 320GB        | 1         | 1      | 1.32%   |
| Seagate ST320LT020-9YG142 320GB  | 1         | 1      | 1.32%   |
| Seagate ST1000LM014-SSHD-8GB     | 1         | 1      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 31     | 30.67%  |
| WDC                 | 16        | 20     | 21.33%  |
| Toshiba             | 14        | 19     | 18.67%  |
| Hitachi             | 6         | 7      | 8%      |
| HGST                | 4         | 4      | 5.33%   |
| SK hynix            | 2         | 2      | 2.67%   |
| Samsung Electronics | 2         | 4      | 2.67%   |
| Micron Technology   | 2         | 2      | 2.67%   |
| Maxtor              | 2         | 2      | 2.67%   |
| SSSTC               | 1         | 1      | 1.33%   |
| LITEON              | 1         | 1      | 1.33%   |
| Apple               | 1         | 1      | 1.33%   |
| Unknown             | 1         | 2      | 1.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 31     | 34.33%  |
| WDC                 | 15        | 19     | 22.39%  |
| Toshiba             | 14        | 19     | 20.9%   |
| Hitachi             | 6         | 7      | 8.96%   |
| HGST                | 4         | 4      | 5.97%   |
| Maxtor              | 2         | 2      | 2.99%   |
| Samsung Electronics | 1         | 2      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |
| Unknown             | 1         | 2      | 1.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 64        | 87     | 88.89%  |
| SSD  | 8         | 9      | 11.11%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 453       | 717    | 59.76%  |
| Works    | 233       | 344    | 30.74%  |
| Malfunc  | 71        | 96     | 9.37%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 590       | 72.57%  |
| AMD                              | 63        | 7.75%   |
| Samsung Electronics              | 47        | 5.78%   |
| SanDisk                          | 16        | 1.97%   |
| Micron Technology                | 14        | 1.72%   |
| SK hynix                         | 7         | 0.86%   |
| Nvidia                           | 7         | 0.86%   |
| Union Memory (Shenzhen)          | 6         | 0.74%   |
| Silicon Motion                   | 6         | 0.74%   |
| Shenzhen Longsys Electronics     | 6         | 0.74%   |
| Phison Electronics               | 6         | 0.74%   |
| Marvell Technology Group         | 5         | 0.62%   |
| VIA Technologies                 | 4         | 0.49%   |
| Toshiba America Info Systems     | 4         | 0.49%   |
| Kingston Technology Company      | 4         | 0.49%   |
| Hewlett-Packard                  | 4         | 0.49%   |
| ASMedia Technology               | 4         | 0.49%   |
| Realtek Semiconductor            | 3         | 0.37%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.37%   |
| JMicron Technology               | 3         | 0.37%   |
| Silicon Integrated Systems [SiS] | 2         | 0.25%   |
| KIOXIA                           | 2         | 0.25%   |
| ADATA Technology                 | 2         | 0.25%   |
| ULi Electronics                  | 1         | 0.12%   |
| Solidigm                         | 1         | 0.12%   |
| Micron/Crucial Technology        | 1         | 0.12%   |
| Broadcom / LSI                   | 1         | 0.12%   |
| Adaptec                          | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 62        | 6.71%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 51        | 5.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 46        | 4.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 45        | 4.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 32        | 3.46%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 30        | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 30        | 3.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 27        | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 26        | 2.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23        | 2.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 22        | 2.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 21        | 2.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18        | 1.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 17        | 1.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 16        | 1.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 14        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.19%   |
| Intel SSD 660P Series                                                                   | 10        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10        | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 9         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 9         | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 0.97%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 8         | 0.87%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 0.87%   |
| Intel SATA Controller [RAID mode]                                                       | 8         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8         | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.87%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7         | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 6         | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 0.65%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 6         | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 531       | 63.52%  |
| NVMe | 137       | 16.39%  |
| IDE  | 91        | 10.89%  |
| RAID | 74        | 8.85%   |
| SAS  | 3         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 624       | 87.89%  |
| AMD     | 82        | 11.55%  |
| ARM     | 3         | 0.42%   |
| Unknown | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 21        | 2.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 14        | 1.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 13        | 1.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 12        | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 12        | 1.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 10        | 1.41%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 10        | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 10        | 1.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 9         | 1.27%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 9         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 9         | 1.27%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 8         | 1.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 8         | 1.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 0.99%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7         | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 6         | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 6         | 0.85%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 6         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 0.85%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 6         | 0.85%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 6         | 0.85%   |
| Intel 12th Gen Core i7-12700H               | 6         | 0.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 0.85%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 5         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 5         | 0.7%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 5         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 5         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 5         | 0.7%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5         | 0.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics      | 5         | 0.7%    |
| AMD Ryzen 7 5700U with Radeon Graphics      | 5         | 0.7%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4         | 0.56%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 0.56%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 4         | 0.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 4         | 0.56%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4         | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 0.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 4         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 209       | 29.44%  |
| Intel Core i5           | 188       | 26.48%  |
| Other                   | 53        | 7.46%   |
| Intel Core i3           | 50        | 7.04%   |
| Intel Core 2 Duo        | 36        | 5.07%   |
| Intel Pentium           | 28        | 3.94%   |
| AMD Ryzen 7             | 20        | 2.82%   |
| Intel Celeron           | 14        | 1.97%   |
| AMD Ryzen 5             | 14        | 1.97%   |
| Intel Pentium Dual-Core | 9         | 1.27%   |
| Intel Xeon              | 8         | 1.13%   |
| Intel Atom              | 8         | 1.13%   |
| AMD FX                  | 8         | 1.13%   |
| Intel Core 2 Quad       | 7         | 0.99%   |
| AMD E1                  | 5         | 0.7%    |
| Intel Pentium Dual      | 4         | 0.56%   |
| AMD Ryzen 3             | 4         | 0.56%   |
| Intel Xeon Gold         | 3         | 0.42%   |
| Intel Pentium Silver    | 3         | 0.42%   |
| Intel Genuine           | 3         | 0.42%   |
| AMD PRO A10             | 3         | 0.42%   |
| AMD A4                  | 3         | 0.42%   |
| AMD A10                 | 3         | 0.42%   |
| Intel Pentium 4         | 2         | 0.28%   |
| AMD Ryzen 3 PRO         | 2         | 0.28%   |
| AMD Athlon II X2        | 2         | 0.28%   |
| AMD Athlon 64 X2        | 2         | 0.28%   |
| AMD Athlon 64           | 2         | 0.28%   |
| AMD A6                  | 2         | 0.28%   |
| Intel Pentium D         | 1         | 0.14%   |
| Intel Core M            | 1         | 0.14%   |
| Intel Core i9           | 1         | 0.14%   |
| Intel Core Duo          | 1         | 0.14%   |
| ARM BCM                 | 1         | 0.14%   |
| AMD Ryzen 9             | 1         | 0.14%   |
| AMD PRO A8              | 1         | 0.14%   |
| AMD Phenom II X4        | 1         | 0.14%   |
| AMD Phenom              | 1         | 0.14%   |
| AMD G                   | 1         | 0.14%   |
| AMD E2                  | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 339       | 47.68%  |
| 4      | 253       | 35.58%  |
| 6      | 41        | 5.77%   |
| 8      | 39        | 5.49%   |
| 1      | 12        | 1.69%   |
| 14     | 10        | 1.41%   |
| 12     | 4         | 0.56%   |
| 10     | 4         | 0.56%   |
| 3      | 4         | 0.56%   |
| 24     | 2         | 0.28%   |
| 52     | 1         | 0.14%   |
| 44     | 1         | 0.14%   |
| 28     | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 701       | 98.73%  |
| 2      | 9         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 511       | 71.77%  |
| 1      | 200       | 28.09%  |
| 4      | 1         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 691       | 97.05%  |
| Unknown        | 14        | 1.97%   |
| 32-bit         | 6         | 0.84%   |
| 64-bit         | 1         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 227       | 31.27%  |
| 0x306a9    | 50        | 6.89%   |
| 0x206a7    | 36        | 4.96%   |
| 0x306c3    | 35        | 4.82%   |
| 0x806ea    | 27        | 3.72%   |
| 0x1067a    | 27        | 3.72%   |
| 0x306d4    | 24        | 3.31%   |
| 0x20655    | 23        | 3.17%   |
| 0x806e9    | 18        | 2.48%   |
| 0x906e9    | 16        | 2.2%    |
| 0x506e3    | 16        | 2.2%    |
| 0x806ec    | 15        | 2.07%   |
| 0x906ea    | 14        | 1.93%   |
| 0x40651    | 13        | 1.79%   |
| 0x806c1    | 11        | 1.52%   |
| 0x906a3    | 9         | 1.24%   |
| 0x406e3    | 9         | 1.24%   |
| 0x6fd      | 8         | 1.1%    |
| 0x20652    | 7         | 0.96%   |
| 0xa0652    | 6         | 0.83%   |
| 0x706e5    | 6         | 0.83%   |
| 0x106e5    | 6         | 0.83%   |
| 0x6fb      | 5         | 0.69%   |
| 0x10676    | 5         | 0.69%   |
| 0x906ed    | 4         | 0.55%   |
| 0x706a1    | 4         | 0.55%   |
| 0x0a50000c | 4         | 0.55%   |
| 0x08608103 | 4         | 0.55%   |
| 0x0700010f | 4         | 0.55%   |
| 0x0600611a | 4         | 0.55%   |
| 0x806d1    | 3         | 0.41%   |
| 0x30678    | 3         | 0.41%   |
| 0x106ca    | 3         | 0.41%   |
| 0x08108109 | 3         | 0.41%   |
| 0x06003106 | 3         | 0.41%   |
| 0x010000c8 | 3         | 0.41%   |
| 0xa0653    | 2         | 0.28%   |
| 0x906eb    | 2         | 0.28%   |
| 0x90672    | 2         | 0.28%   |
| 0x6e8      | 2         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 135       | 18.99%  |
| Haswell          | 87        | 12.24%  |
| IvyBridge        | 72        | 10.13%  |
| Skylake          | 49        | 6.89%   |
| SandyBridge      | 49        | 6.89%   |
| Penryn           | 42        | 5.91%   |
| Westmere         | 33        | 4.64%   |
| Broadwell        | 29        | 4.08%   |
| Unknown          | 22        | 3.09%   |
| TigerLake        | 18        | 2.53%   |
| CometLake        | 18        | 2.53%   |
| Alderlake Hybrid | 18        | 2.53%   |
| Core             | 16        | 2.25%   |
| Zen 3            | 10        | 1.41%   |
| Icelake          | 10        | 1.41%   |
| Zen+             | 9         | 1.27%   |
| Excavator        | 9         | 1.27%   |
| Nehalem          | 8         | 1.13%   |
| Goldmont plus    | 8         | 1.13%   |
| Zen 2            | 7         | 0.98%   |
| Silvermont       | 7         | 0.98%   |
| Zen              | 6         | 0.84%   |
| K10              | 6         | 0.84%   |
| Bonnell          | 6         | 0.84%   |
| Steamroller      | 5         | 0.7%    |
| NetBurst         | 5         | 0.7%    |
| Jaguar           | 5         | 0.7%    |
| Puma             | 4         | 0.56%   |
| K8 Hammer        | 4         | 0.56%   |
| P6               | 3         | 0.42%   |
| Bulldozer        | 3         | 0.42%   |
| Bobcat           | 3         | 0.42%   |
| Goldmont         | 2         | 0.28%   |
| Piledriver       | 1         | 0.14%   |
| K10 Llano        | 1         | 0.14%   |
| Gracemont        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 486       | 47.93%  |
| Nvidia                           | 336       | 33.14%  |
| AMD                              | 182       | 17.95%  |
| Matrox Electronics Systems       | 3         | 0.3%    |
| ASPEED Technology                | 3         | 0.3%    |
| VIA Technologies                 | 1         | 0.1%    |
| Trident Microsystems             | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| ATI Technologies                 | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 44        | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 35        | 3.39%   |
| Intel UHD Graphics 620                                                                | 33        | 3.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 28        | 2.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 27        | 2.62%   |
| Intel HD Graphics 620                                                                 | 26        | 2.52%   |
| Intel HD Graphics 5500                                                                | 25        | 2.42%   |
| Intel HD Graphics 530                                                                 | 20        | 1.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 18        | 1.75%   |
| Intel Core Processor Integrated Graphics Controller                                   | 18        | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 17        | 1.65%   |
| Intel HD Graphics 630                                                                 | 17        | 1.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 16        | 1.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 15        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 15        | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 13        | 1.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 13        | 1.26%   |
| Nvidia GP108M [GeForce MX150]                                                         | 12        | 1.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 12        | 1.16%   |
| Nvidia GT218 [GeForce 210]                                                            | 11        | 1.07%   |
| Nvidia GM108M [GeForce MX110]                                                         | 11        | 1.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 11        | 1.07%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 11        | 1.07%   |
| Nvidia GP107M [GeForce MX350]                                                         | 10        | 0.97%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 10        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 10        | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 10        | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 10        | 0.97%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 10        | 0.97%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 9         | 0.87%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 9         | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 9         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 8         | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 8         | 0.78%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 8         | 0.78%   |
| Nvidia GM108M [GeForce 840M]                                                          | 7         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 7         | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 7         | 0.68%   |
| AMD Lucienne                                                                          | 7         | 0.68%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                  | 7         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Intel + Nvidia           | 223       | 31.36%  |
| 1 x Intel                | 192       | 27%     |
| 1 x Nvidia               | 98        | 13.78%  |
| 1 x AMD                  | 90        | 12.66%  |
| Intel + AMD              | 68        | 9.56%   |
| AMD + Nvidia             | 14        | 1.97%   |
| 2 x AMD                  | 12        | 1.69%   |
| Other                    | 4         | 0.56%   |
| 1 x Matrox               | 3         | 0.42%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.14%   |
| 2 x Intel                | 1         | 0.14%   |
| 1 x VIA                  | 1         | 0.14%   |
| 1 x Trident Microsystems | 1         | 0.14%   |
| 1 x SiS                  | 1         | 0.14%   |
| Nvidia + ASPEED          | 1         | 0.14%   |
| 1 x ASPEED               | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 547       | 76.18%  |
| Proprietary | 148       | 20.61%  |
| Unknown     | 23        | 3.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 361       | 49.93%  |
| 1.01-2.0   | 133       | 18.4%   |
| 0.51-1.0   | 75        | 10.37%  |
| 3.01-4.0   | 69        | 9.54%   |
| 0.01-0.5   | 55        | 7.61%   |
| 7.01-8.0   | 13        | 1.8%    |
| 5.01-6.0   | 13        | 1.8%    |
| 8.01-16.0  | 3         | 0.41%   |
| 2.01-3.0   | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 117       | 16.57%  |
| AU Optronics            | 100       | 14.16%  |
| LG Display              | 94        | 13.31%  |
| BOE                     | 83        | 11.76%  |
| Chimei Innolux          | 82        | 11.61%  |
| Goldstar                | 68        | 9.63%   |
| Hewlett-Packard         | 14        | 1.98%   |
| Chi Mei Optoelectronics | 14        | 1.98%   |
| PANDA                   | 11        | 1.56%   |
| Ancor Communications    | 11        | 1.56%   |
| AOC                     | 10        | 1.42%   |
| Apple                   | 9         | 1.27%   |
| BenQ                    | 8         | 1.13%   |
| Lenovo                  | 7         | 0.99%   |
| CHD                     | 7         | 0.99%   |
| Sony                    | 6         | 0.85%   |
| Dell                    | 6         | 0.85%   |
| LG Electronics          | 5         | 0.71%   |
| HannStar                | 5         | 0.71%   |
| Sharp                   | 4         | 0.57%   |
| RTK                     | 4         | 0.57%   |
| Unknown                 | 3         | 0.42%   |
| MSI                     | 3         | 0.42%   |
| LG Philips              | 3         | 0.42%   |
| ASUSTek Computer        | 3         | 0.42%   |
| ViewSonic               | 2         | 0.28%   |
| Unknown (ADA)           | 2         | 0.28%   |
| InnoLux Display         | 2         | 0.28%   |
| InfoVision              | 2         | 0.28%   |
| HUAWEI                  | 2         | 0.28%   |
| Acer                    | 2         | 0.28%   |
| XVision                 | 1         | 0.14%   |
| Xiaomi                  | 1         | 0.14%   |
| TMX                     | 1         | 0.14%   |
| Seiko/Epson             | 1         | 0.14%   |
| SEEYOO                  | 1         | 0.14%   |
| RGT                     | 1         | 0.14%   |
| Quanta Display          | 1         | 0.14%   |
| PAR                     | 1         | 0.14%   |
| Nvidia                  | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 1.67%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 9         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 8         | 1.11%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 1.11%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 7         | 0.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 6         | 0.84%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 5         | 0.7%    |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch         | 5         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.7%    |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 5         | 0.7%    |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                      | 5         | 0.7%    |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch                  | 5         | 0.7%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 5         | 0.7%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 5         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.7%    |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch         | 4         | 0.56%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                   | 4         | 0.56%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.56%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.56%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.56%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 520x290mm 23.4-inch        | 3         | 0.42%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 480x270mm 21.7-inch        | 3         | 0.42%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 3         | 0.42%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 3         | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.42%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.42%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 3         | 0.42%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 3         | 0.42%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 3         | 0.42%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch          | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 300       | 43.6%   |
| 1366x768 (WXGA)    | 207       | 30.09%  |
| 1600x900 (HD+)     | 38        | 5.52%   |
| 1440x900 (WXGA+)   | 26        | 3.78%   |
| 3840x2160 (4K)     | 25        | 3.63%   |
| 1280x800 (WXGA)    | 18        | 2.62%   |
| 1680x1050 (WSXGA+) | 10        | 1.45%   |
| 1280x1024 (SXGA)   | 10        | 1.45%   |
| 2560x1440 (QHD)    | 8         | 1.16%   |
| 1360x768           | 7         | 1.02%   |
| Unknown            | 5         | 0.73%   |
| 1920x1200 (WUXGA)  | 4         | 0.58%   |
| 1024x600           | 4         | 0.58%   |
| 2560x1080          | 3         | 0.44%   |
| 3840x2400          | 2         | 0.29%   |
| 3240x2160          | 2         | 0.29%   |
| 2880x1800          | 2         | 0.29%   |
| 2880x1620          | 2         | 0.29%   |
| 2560x1600          | 2         | 0.29%   |
| 1280x960           | 2         | 0.29%   |
| 5760x2160          | 1         | 0.15%   |
| 3840x1080          | 1         | 0.15%   |
| 3200x2000          | 1         | 0.15%   |
| 3200x1800 (QHD+)   | 1         | 0.15%   |
| 2944x1080          | 1         | 0.15%   |
| 2880x1920          | 1         | 0.15%   |
| 2736x1824          | 1         | 0.15%   |
| 2720x768           | 1         | 0.15%   |
| 1920x1280          | 1         | 0.15%   |
| 1680x945           | 1         | 0.15%   |
| 1280x720 (HD)      | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 319       | 45.25%  |
| 14      | 54        | 7.66%   |
| 21      | 53        | 7.52%   |
| 13      | 53        | 7.52%   |
| 20      | 24        | 3.4%    |
| 23      | 23        | 3.26%   |
| 18      | 23        | 3.26%   |
| Unknown | 23        | 3.26%   |
| 19      | 20        | 2.84%   |
| 24      | 16        | 2.27%   |
| 17      | 16        | 2.27%   |
| 12      | 14        | 1.99%   |
| 27      | 13        | 1.84%   |
| 16      | 9         | 1.28%   |
| 22      | 8         | 1.13%   |
| 11      | 6         | 0.85%   |
| 10      | 5         | 0.71%   |
| 46      | 4         | 0.57%   |
| 31      | 3         | 0.43%   |
| 29      | 3         | 0.43%   |
| 84      | 2         | 0.28%   |
| 72      | 2         | 0.28%   |
| 65      | 2         | 0.28%   |
| 54      | 2         | 0.28%   |
| 32      | 2         | 0.28%   |
| 7       | 2         | 0.28%   |
| 75      | 1         | 0.14%   |
| 50      | 1         | 0.14%   |
| 40      | 1         | 0.14%   |
| 26      | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 417       | 59.57%  |
| 401-500     | 123       | 17.57%  |
| 501-600     | 51        | 7.29%   |
| 201-300     | 39        | 5.57%   |
| Unknown     | 23        | 3.29%   |
| 351-400     | 21        | 3%      |
| 1001-1500   | 9         | 1.29%   |
| 601-700     | 7         | 1%      |
| 1501-2000   | 5         | 0.71%   |
| 701-800     | 2         | 0.29%   |
| 101-200     | 2         | 0.29%   |
| 801-900     | 1         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 563       | 85.3%   |
| 16/10   | 56        | 8.48%   |
| Unknown | 21        | 3.18%   |
| 3/2     | 7         | 1.06%   |
| 5/4     | 6         | 0.91%   |
| 4/3     | 5         | 0.76%   |
| 21/9    | 2         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 319       | 45.38%  |
| 81-90          | 93        | 13.23%  |
| 201-250        | 86        | 12.23%  |
| 151-200        | 54        | 7.68%   |
| 141-150        | 26        | 3.7%    |
| Unknown        | 23        | 3.27%   |
| 301-350        | 15        | 2.13%   |
| 71-80          | 13        | 1.85%   |
| 61-70          | 13        | 1.85%   |
| 121-130        | 12        | 1.71%   |
| More than 1000 | 10        | 1.42%   |
| 51-60          | 6         | 0.85%   |
| 351-500        | 6         | 0.85%   |
| 41-50          | 5         | 0.71%   |
| 501-1000       | 5         | 0.71%   |
| 251-300        | 4         | 0.57%   |
| 131-140        | 4         | 0.57%   |
| 111-120        | 4         | 0.57%   |
| 91-100         | 3         | 0.43%   |
| 1-40           | 2         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 228       | 32.85%  |
| 101-120       | 227       | 32.71%  |
| 51-100        | 168       | 24.21%  |
| Unknown       | 23        | 3.31%   |
| 161-240       | 19        | 2.74%   |
| More than 240 | 18        | 2.59%   |
| 1-50          | 11        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 606       | 84.64%  |
| 2     | 74        | 10.34%  |
| 0     | 34        | 4.75%   |
| 3     | 2         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 412       | 36.11%  |
| Intel                                  | 293       | 25.68%  |
| Qualcomm Atheros                       | 143       | 12.53%  |
| Broadcom                               | 66        | 5.78%   |
| Ralink Technology                      | 28        | 2.45%   |
| Samsung Electronics                    | 22        | 1.93%   |
| Ralink                                 | 21        | 1.84%   |
| MediaTek                               | 21        | 1.84%   |
| Broadcom Limited                       | 19        | 1.67%   |
| Xiaomi                                 | 17        | 1.49%   |
| D-Link                                 | 16        | 1.4%    |
| Marvell Technology Group               | 14        | 1.23%   |
| TP-Link                                | 9         | 0.79%   |
| VIA Technologies                       | 6         | 0.53%   |
| Huawei Technologies                    | 6         | 0.53%   |
| Hewlett-Packard                        | 6         | 0.53%   |
| Nvidia                                 | 5         | 0.44%   |
| D-Link System                          | 5         | 0.44%   |
| Qualcomm Atheros Communications        | 3         | 0.26%   |
| JMicron Technology                     | 3         | 0.26%   |
| HTC (High Tech Computer)               | 3         | 0.26%   |
| Qualcomm                               | 2         | 0.18%   |
| Microsoft                              | 2         | 0.18%   |
| ICS Advent                             | 2         | 0.18%   |
| ASUSTek Computer                       | 2         | 0.18%   |
| ASIX Electronics                       | 2         | 0.18%   |
| ZyDAS                                  | 1         | 0.09%   |
| Tenda                                  | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Smart Link                             | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.09%   |
| Sierra Wireless                        | 1         | 0.09%   |
| LG Electronics                         | 1         | 0.09%   |
| Lenovo                                 | 1         | 0.09%   |
| BUFFALO                                | 1         | 0.09%   |
| Attansic Technology                    | 1         | 0.09%   |
| Aquantia                               | 1         | 0.09%   |
| Apple                                  | 1         | 0.09%   |
| AboCom Systems                         | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 316       | 24.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 3.05%   |
| Intel Wireless 7265                                                    | 26        | 1.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 1.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 24        | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 23        | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 22        | 1.68%   |
| Ralink MT7601U Wireless Adapter                                        | 21        | 1.6%    |
| Intel Wireless 8265 / 8275                                             | 20        | 1.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 18        | 1.37%   |
| Intel Wireless 7260                                                    | 18        | 1.37%   |
| Intel Wireless 8260                                                    | 17        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 16        | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 1.22%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.99%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 13        | 0.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 12        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 12        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                          | 12        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 10        | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 10        | 0.76%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.76%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 10        | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 0.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 0.69%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 8         | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 8         | 0.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 8         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 7         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 7         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7         | 0.53%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 0.53%   |
| Intel Centrino Ultimate-N 6300                                         | 7         | 0.53%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                         | 7         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 237       | 38.66%  |
| Qualcomm Atheros                | 109       | 17.78%  |
| Realtek Semiconductor           | 99        | 16.15%  |
| Broadcom                        | 42        | 6.85%   |
| Ralink Technology               | 28        | 4.57%   |
| Ralink                          | 21        | 3.43%   |
| MediaTek                        | 20        | 3.26%   |
| Broadcom Limited                | 16        | 2.61%   |
| D-Link                          | 15        | 2.45%   |
| TP-Link                         | 8         | 1.31%   |
| Hewlett-Packard                 | 4         | 0.65%   |
| Qualcomm Atheros Communications | 3         | 0.49%   |
| D-Link System                   | 3         | 0.49%   |
| Marvell Technology Group        | 2         | 0.33%   |
| ZyDAS                           | 1         | 0.16%   |
| Xiaomi                          | 1         | 0.16%   |
| Tenda                           | 1         | 0.16%   |
| Sierra Wireless                 | 1         | 0.16%   |
| BUFFALO                         | 1         | 0.16%   |
| AboCom Systems                  | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                            | 26        | 4.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24        | 3.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 23        | 3.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 22        | 3.57%   |
| Ralink MT7601U Wireless Adapter                                | 21        | 3.4%    |
| Intel Wireless 8265 / 8275                                     | 20        | 3.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 18        | 2.92%   |
| Intel Wireless 7260                                            | 18        | 2.92%   |
| Intel Wireless 8260                                            | 17        | 2.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 16        | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 2.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 13        | 2.11%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 2.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 13        | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 2.11%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 12        | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 1.94%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 1.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 10        | 1.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 9         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 7         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                 | 7         | 1.13%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 7         | 1.13%   |
| Ralink RT5370 Wireless Adapter                                 | 6         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 0.97%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 0.97%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 0.97%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 0.81%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 5         | 0.81%   |
| Intel Wireless 3160                                            | 5         | 0.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 0.81%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4         | 0.65%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 4         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 374       | 54.84%  |
| Intel                                  | 121       | 17.74%  |
| Qualcomm Atheros                       | 54        | 7.92%   |
| Broadcom                               | 35        | 5.13%   |
| Samsung Electronics                    | 21        | 3.08%   |
| Xiaomi                                 | 16        | 2.35%   |
| Marvell Technology Group               | 12        | 1.76%   |
| VIA Technologies                       | 6         | 0.88%   |
| Huawei Technologies                    | 6         | 0.88%   |
| Nvidia                                 | 5         | 0.73%   |
| JMicron Technology                     | 3         | 0.44%   |
| HTC (High Tech Computer)               | 3         | 0.44%   |
| Broadcom Limited                       | 3         | 0.44%   |
| Qualcomm                               | 2         | 0.29%   |
| Microsoft                              | 2         | 0.29%   |
| ICS Advent                             | 2         | 0.29%   |
| Hewlett-Packard                        | 2         | 0.29%   |
| D-Link System                          | 2         | 0.29%   |
| ASIX Electronics                       | 2         | 0.29%   |
| TP-Link                                | 1         | 0.15%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.15%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.15%   |
| MediaTek                               | 1         | 0.15%   |
| LG Electronics                         | 1         | 0.15%   |
| Lenovo                                 | 1         | 0.15%   |
| D-Link                                 | 1         | 0.15%   |
| Attansic Technology                    | 1         | 0.15%   |
| ASUSTek Computer                       | 1         | 0.15%   |
| Aquantia                               | 1         | 0.15%   |
| Apple                                  | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 316       | 45.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 40        | 5.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 3.63%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13        | 1.89%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 10        | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 1.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 8         | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 7         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 7         | 1.02%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 0.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 6         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 5         | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 0.73%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 5         | 0.73%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 5         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 0.73%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 5         | 0.73%   |
| Huawei VTR-L09                                                         | 5         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.73%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 4         | 0.58%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.58%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.44%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.44%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 3         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 0.44%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 0.44%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.44%   |
| Intel Ethernet Connection (2) I218-V                                   | 3         | 0.44%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 620       | 50.9%   |
| WiFi     | 594       | 48.77%  |
| Modem    | 2         | 0.16%   |
| Unknown  | 2         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 494       | 71.39%  |
| Ethernet | 197       | 28.47%  |
| Unknown  | 1         | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 444       | 62.54%  |
| 1     | 250       | 35.21%  |
| 0     | 7         | 0.99%   |
| 3     | 5         | 0.7%    |
| 4     | 3         | 0.42%   |
| 8     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 663       | 92.47%  |
| Yes  | 54        | 7.53%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 177       | 38.73%  |
| IMC Networks                    | 62        | 13.57%  |
| Realtek Semiconductor           | 42        | 9.19%   |
| Qualcomm Atheros Communications | 33        | 7.22%   |
| Broadcom                        | 23        | 5.03%   |
| Foxconn / Hon Hai               | 21        | 4.6%    |
| Cambridge Silicon Radio         | 19        | 4.16%   |
| Lite-On Technology              | 17        | 3.72%   |
| Ralink                          | 10        | 2.19%   |
| Dell                            | 10        | 2.19%   |
| ASUSTek Computer                | 10        | 2.19%   |
| Apple                           | 8         | 1.75%   |
| Foxconn International           | 7         | 1.53%   |
| Ralink Technology               | 3         | 0.66%   |
| Hewlett-Packard                 | 3         | 0.66%   |
| Realtek                         | 2         | 0.44%   |
| Marvell Semiconductor           | 2         | 0.44%   |
| Askey Computer                  | 2         | 0.44%   |
| Alps Electric                   | 2         | 0.44%   |
| SiW                             | 1         | 0.22%   |
| Micro Star International        | 1         | 0.22%   |
| MediaTek                        | 1         | 0.22%   |
| Integrated System Solution      | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 57        | 12.47%  |
| Intel Bluetooth Device                                                              | 35        | 7.66%   |
| Intel AX201 Bluetooth                                                               | 34        | 7.44%   |
| Realtek Bluetooth Radio                                                             | 26        | 5.69%   |
| IMC Networks Bluetooth Radio                                                        | 25        | 5.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 22        | 4.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 4.16%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 3.06%   |
| IMC Networks Wireless_Device                                                        | 14        | 3.06%   |
| IMC Networks Bluetooth Device                                                       | 11        | 2.41%   |
| Ralink RT3290 Bluetooth                                                             | 10        | 2.19%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.75%   |
| Realtek RTL8723B Bluetooth                                                          | 7         | 1.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.53%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 1.53%   |
| Intel AX211 Bluetooth                                                               | 7         | 1.53%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 7         | 1.53%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 7         | 1.53%   |
| Intel AX200 Bluetooth                                                               | 6         | 1.31%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.31%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 1.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.09%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.09%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 1.09%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.88%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 0.88%   |
| Broadcom BCM20702A0                                                                 | 4         | 0.88%   |
| Apple Bluetooth Host Controller                                                     | 4         | 0.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.66%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.66%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.66%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 3         | 0.66%   |
| Dell Wireless 360 Bluetooth                                                         | 3         | 0.66%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 0.66%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.66%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.66%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.44%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.44%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 2         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 606       | 65.73%  |
| Nvidia                           | 156       | 16.92%  |
| AMD                              | 126       | 13.67%  |
| C-Media Electronics              | 8         | 0.87%   |
| Generalplus Technology           | 5         | 0.54%   |
| ASUSTek Computer                 | 5         | 0.54%   |
| Silicon Integrated Systems [SiS] | 2         | 0.22%   |
| Focusrite-Novation               | 2         | 0.22%   |
| Creative Labs                    | 2         | 0.22%   |
| BR25                             | 2         | 0.22%   |
| Yamaha                           | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| ULi Electronics                  | 1         | 0.11%   |
| TEAC                             | 1         | 0.11%   |
| Realtek Semiconductor            | 1         | 0.11%   |
| Native Instruments               | 1         | 0.11%   |
| ESS Technology                   | 1         | 0.11%   |
| CMX Systems                      | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 78        | 7.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 65        | 6.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 53        | 4.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 50        | 4.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 38        | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 38        | 3.53%   |
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 3.06%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 30        | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 29        | 2.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 28        | 2.6%    |
| Intel 8 Series HD Audio Controller                                         | 28        | 2.6%    |
| Intel Broadwell-U Audio Controller                                         | 27        | 2.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 26        | 2.41%   |
| Nvidia GF108 High Definition Audio Controller                              | 25        | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 24        | 2.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 1.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 1.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 18        | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 1.58%   |
| Intel CM238 HD Audio Controller                                            | 16        | 1.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 1.39%   |
| AMD FCH Azalia Controller                                                  | 15        | 1.39%   |
| Nvidia High Definition Audio Controller                                    | 14        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                   | 14        | 1.3%    |
| Nvidia Audio device                                                        | 11        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.02%   |
| Intel 200 Series PCH HD Audio                                              | 11        | 1.02%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10        | 0.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 9         | 0.83%   |
| Nvidia GF119 HDMI Audio Controller                                         | 9         | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 9         | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 9         | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 9         | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 8         | 0.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 120       | 28.3%   |
| SK hynix            | 75        | 17.69%  |
| Micron Technology   | 54        | 12.74%  |
| Kingston            | 34        | 8.02%   |
| Crucial             | 33        | 7.78%   |
| Unknown             | 31        | 7.31%   |
| Ramaxel Technology  | 16        | 3.77%   |
| Elpida              | 14        | 3.3%    |
| A-DATA Technology   | 7         | 1.65%   |
| GeIL                | 6         | 1.42%   |
| Corsair             | 6         | 1.42%   |
| Apacer              | 6         | 1.42%   |
| Kingmax             | 4         | 0.94%   |
| G.Skill             | 4         | 0.94%   |
| Nanya Technology    | 3         | 0.71%   |
| Ramos Technology    | 2         | 0.47%   |
| Unknown             | 2         | 0.47%   |
| Unknown (8A02)      | 1         | 0.24%   |
| TwinMOS             | 1         | 0.24%   |
| Transcend           | 1         | 0.24%   |
| Team                | 1         | 0.24%   |
| Silicon Power       | 1         | 0.24%   |
| Neo Forza           | 1         | 0.24%   |
| ASint Technology    | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 8         | 1.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 8         | 1.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 1.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 7         | 1.53%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s        | 7         | 1.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 1.31%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 6         | 1.31%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 6         | 1.31%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 6         | 1.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 5         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 5         | 1.09%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 5         | 1.09%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s           | 5         | 1.09%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 0.87%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 4         | 0.87%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.87%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 4         | 0.87%   |
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s           | 4         | 0.87%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.65%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 3         | 0.65%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 0.65%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 0.65%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 3         | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 3         | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s     | 3         | 0.65%   |
| Samsung RAM K3LKBKB0BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.65%   |
| Ramaxel RAM RMT3170MK58F8F1600 2GB SODIMM DDR3 1600MT/s      | 3         | 0.65%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 3         | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2         | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.44%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s         | 2         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 157       | 45.77%  |
| DDR3    | 136       | 39.65%  |
| DDR2    | 11        | 3.21%   |
| DDR5    | 10        | 2.92%   |
| Unknown | 8         | 2.33%   |
| SDRAM   | 6         | 1.75%   |
| LPDDR5  | 5         | 1.46%   |
| LPDDR3  | 5         | 1.46%   |
| LPDDR4  | 4         | 1.17%   |
| DDR     | 1         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 243       | 71.26%  |
| DIMM         | 78        | 22.87%  |
| Row Of Chips | 17        | 4.99%   |
| Chip         | 2         | 0.59%   |
| RIMM         | 1         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 149       | 37.91%  |
| 4096  | 128       | 32.57%  |
| 16384 | 54        | 13.74%  |
| 2048  | 48        | 12.21%  |
| 1024  | 9         | 2.29%   |
| 32768 | 4         | 1.02%   |
| 65536 | 1         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 93        | 24.41%  |
| 2667    | 63        | 16.54%  |
| 3200    | 49        | 12.86%  |
| 2400    | 31        | 8.14%   |
| 1334    | 25        | 6.56%   |
| 2133    | 21        | 5.51%   |
| 1333    | 21        | 5.51%   |
| 4800    | 10        | 2.62%   |
| Unknown | 9         | 2.36%   |
| 3266    | 8         | 2.1%    |
| 667     | 7         | 1.84%   |
| 6400    | 5         | 1.31%   |
| 4199    | 5         | 1.31%   |
| 1867    | 5         | 1.31%   |
| 800     | 5         | 1.31%   |
| 8400    | 3         | 0.79%   |
| 1067    | 3         | 0.79%   |
| 4266    | 2         | 0.52%   |
| 3000    | 2         | 0.52%   |
| 2666    | 2         | 0.52%   |
| 533     | 2         | 0.52%   |
| 3600    | 1         | 0.26%   |
| 3400    | 1         | 0.26%   |
| 3066    | 1         | 0.26%   |
| 2933    | 1         | 0.26%   |
| 2800    | 1         | 0.26%   |
| 1866    | 1         | 0.26%   |
| 1800    | 1         | 0.26%   |
| 1400    | 1         | 0.26%   |
| 1328    | 1         | 0.26%   |
| 400     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Canon               | 3         | 42.86%  |
| Samsung Electronics | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-1640 Series Laser Printer | 1         | 14.29%  |
| HP LaserJet P1102                    | 1         | 14.29%  |
| HP LaserJet 1018                     | 1         | 14.29%  |
| HP DeskJet 2130 series               | 1         | 14.29%  |
| Canon PIXMA MG5600 Series            | 1         | 14.29%  |
| Canon LBP6300                        | 1         | 14.29%  |
| Canon iR2004/2204 UFRII LT           | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 120            | 1         | 33.33%  |
| Canon CanoScan 4400F               | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 111       | 23.03%  |
| IMC Networks                           | 99        | 20.54%  |
| Realtek Semiconductor                  | 33        | 6.85%   |
| Microdia                               | 32        | 6.64%   |
| Bison Electronics                      | 27        | 5.6%    |
| Syntek                                 | 20        | 4.15%   |
| Sunplus Innovation Technology          | 18        | 3.73%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.73%   |
| Apple                                  | 16        | 3.32%   |
| Acer                                   | 16        | 3.32%   |
| Lite-On Technology                     | 14        | 2.9%    |
| Sonix Technology                       | 12        | 2.49%   |
| Quanta                                 | 12        | 2.49%   |
| Suyin                                  | 9         | 1.87%   |
| Ricoh                                  | 8         | 1.66%   |
| Samsung Electronics                    | 7         | 1.45%   |
| Luxvisions Innotech Limited            | 4         | 0.83%   |
| Alcor Micro                            | 4         | 0.83%   |
| Pixart Imaging                         | 3         | 0.62%   |
| Lenovo                                 | 3         | 0.62%   |
| ALi                                    | 3         | 0.62%   |
| Silicon Motion                         | 2         | 0.41%   |
| Importek                               | 2         | 0.41%   |
| Sunplus Technology                     | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| OmniVision Technologies                | 1         | 0.21%   |
| MacroSilicon                           | 1         | 0.21%   |
| Logitech                               | 1         | 0.21%   |
| LG Electronics                         | 1         | 0.21%   |
| KYE Systems (Mouse Systems)            | 1         | 0.21%   |
| Goertek Electronics                    | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 33        | 6.85%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 25        | 5.19%   |
| IMC Networks Integrated Camera                      | 16        | 3.32%   |
| Chicony Integrated Camera                           | 16        | 3.32%   |
| Chicony USB2.0 HD UVC WebCam                        | 11        | 2.28%   |
| IMC Networks Lenovo EasyCamera                      | 10        | 2.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 10        | 2.07%   |
| Chicony HD WebCam                                   | 9         | 1.87%   |
| Chicony EasyCamera                                  | 9         | 1.87%   |
| Sonix USB2.0 HD UVC WebCam                          | 8         | 1.66%   |
| Microdia Laptop_Integrated_Webcam_HD                | 8         | 1.66%   |
| Lite-On Integrated Camera                           | 8         | 1.66%   |
| Syntek Lenovo EasyCamera                            | 7         | 1.45%   |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 1.45%   |
| Realtek USB Camera                                  | 7         | 1.45%   |
| Chicony HP HD Camera                                | 7         | 1.45%   |
| Acer Lenovo EasyCamera                              | 7         | 1.45%   |
| Syntek Integrated Camera                            | 6         | 1.24%   |
| Syntek EasyCamera                                   | 6         | 1.24%   |
| Sunplus HD WebCam                                   | 6         | 1.24%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 1.24%   |
| Chicony HP HD Webcam                                | 6         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 6         | 1.24%   |
| Bison Lenovo EasyCamera                             | 6         | 1.24%   |
| Acer Integrated Camera                              | 6         | 1.24%   |
| Sunplus Asus Webcam                                 | 5         | 1.04%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 1.04%   |
| Realtek Integrated_Webcam_HD                        | 5         | 1.04%   |
| Microdia USB 2.0 Camera                             | 5         | 1.04%   |
| Lite-On HP HD Camera                                | 5         | 1.04%   |
| Chicony Lenovo EasyCamera                           | 5         | 1.04%   |
| Chicony Integrated HP HD Webcam                     | 5         | 1.04%   |
| Chicony HP HD Webcam [Fixed]                        | 5         | 1.04%   |
| Bison SunplusIT Integrated Camera                   | 5         | 1.04%   |
| Microdia Integrated_Webcam_HD                       | 4         | 0.83%   |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.83%   |
| Bison HD Webcam                                     | 4         | 0.83%   |
| Bison EasyCamera                                    | 4         | 0.83%   |
| Sonix USB2.0 FHD UVC WebCam                         | 3         | 0.62%   |
| Microdia Sonix Integrated Webcam                    | 3         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 51        | 44.74%  |
| Shenzhen Goodix Technology         | 17        | 14.91%  |
| Upek                               | 12        | 10.53%  |
| Elan Microelectronics              | 12        | 10.53%  |
| Synaptics                          | 10        | 8.77%   |
| AuthenTec                          | 5         | 4.39%   |
| LighTuning Technology              | 3         | 2.63%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.75%   |
| Suprema                            | 1         | 0.88%   |
| STMicroelectronics                 | 1         | 0.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 20.18%  |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 11.4%   |
| Validity Sensors VFS491                                                    | 12        | 10.53%  |
| Elan ELAN:Fingerprint                                                      | 12        | 10.53%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 9.65%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 4.39%   |
| Synaptics  WBDI                                                            | 4         | 3.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.75%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.75%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.75%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.75%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.88%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.88%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.88%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.88%   |
| Synaptics UWP WBDI                                                         | 1         | 0.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.88%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                           | 1         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.88%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.88%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.88%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.88%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 9         | 47.37%  |
| Alcor Micro           | 5         | 26.32%  |
| Upek                  | 2         | 10.53%  |
| O2 Micro              | 2         | 10.53%  |
| Gemalto (was Gemplus) | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 26.32%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15.79%  |
| Broadcom 5880                                                                | 3         | 15.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 10.53%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.26%   |
| Broadcom 58200                                                               | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 457       | 62.95%  |
| 1     | 210       | 28.93%  |
| 2     | 46        | 6.34%   |
| 3     | 9         | 1.24%   |
| 4     | 2         | 0.28%   |
| 8     | 1         | 0.14%   |
| 5     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 114       | 34.44%  |
| Graphics card            | 95        | 28.7%   |
| Net/wireless             | 29        | 8.76%   |
| Communication controller | 19        | 5.74%   |
| Bluetooth                | 17        | 5.14%   |
| Chipcard                 | 16        | 4.83%   |
| Camera                   | 10        | 3.02%   |
| Multimedia controller    | 9         | 2.72%   |
| Unassigned class         | 8         | 2.42%   |
| Storage                  | 5         | 1.51%   |
| Sound                    | 3         | 0.91%   |
| Network                  | 2         | 0.6%    |
| Card reader              | 2         | 0.6%    |
| Wireless                 | 1         | 0.3%    |
| Net/ethernet             | 1         | 0.3%    |


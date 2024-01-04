Linux - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/linuxhw/TestDays_VE)

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

Total: 190635

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X515... | [700ae279ed](https://linux-hardware.org/?probe=700ae279ed) | Jan 02, 2024 |
| iQual         | NQ4X                        | [5c66dfd710](https://linux-hardware.org/?probe=5c66dfd710) | Jan 02, 2024 |
| Notebook      | N14xWU                      | [0460984dea](https://linux-hardware.org/?probe=0460984dea) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [8250c46efe](https://linux-hardware.org/?probe=8250c46efe) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [00e99b0067](https://linux-hardware.org/?probe=00e99b0067) | Jan 02, 2024 |
| Lenovo        | V14 G2 ALC 82KC             | [57cd074cfd](https://linux-hardware.org/?probe=57cd074cfd) | Jan 02, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [e15430e53e](https://linux-hardware.org/?probe=e15430e53e) | Jan 02, 2024 |
| Acer          | Aspire 8730                 | [a435ff1bd6](https://linux-hardware.org/?probe=a435ff1bd6) | Jan 02, 2024 |
| Acer          | Aspire 8730                 | [4db4a265b6](https://linux-hardware.org/?probe=4db4a265b6) | Jan 02, 2024 |
| Dell          | Inspiron 5558               | [acc47dae75](https://linux-hardware.org/?probe=acc47dae75) | Jan 02, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [65ddbd761c](https://linux-hardware.org/?probe=65ddbd761c) | Jan 02, 2024 |
| Sony          | SVE1713X1EB                 | [6c3167a5a7](https://linux-hardware.org/?probe=6c3167a5a7) | Jan 02, 2024 |
| ASUSTek       | X75VC                       | [c80297163a](https://linux-hardware.org/?probe=c80297163a) | Jan 02, 2024 |
| Dell          | Inspiron 13-5368            | [811a112c63](https://linux-hardware.org/?probe=811a112c63) | Jan 02, 2024 |
| Dell          | Inspiron 15-3567            | [50d926ec76](https://linux-hardware.org/?probe=50d926ec76) | Jan 02, 2024 |
| Samsung       | 550XCJ/550XCR               | [daf43e4658](https://linux-hardware.org/?probe=daf43e4658) | Jan 02, 2024 |
| MouseCompu... | EGPN711R307                 | [fc34633537](https://linux-hardware.org/?probe=fc34633537) | Jan 02, 2024 |
| Lenovo        | G505 20240                  | [ff10a3ab7d](https://linux-hardware.org/?probe=ff10a3ab7d) | Jan 02, 2024 |
| Lenovo        | G50-70 20351                | [cb1029f101](https://linux-hardware.org/?probe=cb1029f101) | Jan 02, 2024 |
| Notebook      | N13xWU                      | [b88a27e565](https://linux-hardware.org/?probe=b88a27e565) | Jan 02, 2024 |
| Google        | Caroline                    | [8b3ec77c48](https://linux-hardware.org/?probe=8b3ec77c48) | Jan 02, 2024 |
| Acidanther... | MacBookPro16,4              | [3c8c520472](https://linux-hardware.org/?probe=3c8c520472) | Jan 02, 2024 |
| Google        | Blooguard                   | [dc6c0354a9](https://linux-hardware.org/?probe=dc6c0354a9) | Jan 02, 2024 |
| HP            | Pavilion dm4                | [7b2206d3e1](https://linux-hardware.org/?probe=7b2206d3e1) | Jan 02, 2024 |
| HP            | Pavilion dm4                | [97f8b54561](https://linux-hardware.org/?probe=97f8b54561) | Jan 02, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [88bc9fe11f](https://linux-hardware.org/?probe=88bc9fe11f) | Jan 02, 2024 |
| Lenovo        | V15 G3 IAP 82TT             | [2ca86aaf30](https://linux-hardware.org/?probe=2ca86aaf30) | Jan 02, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | [389ae3afc8](https://linux-hardware.org/?probe=389ae3afc8) | Jan 02, 2024 |
| HP            | Laptop 17-cp0xxx            | [a9e2dd2fb6](https://linux-hardware.org/?probe=a9e2dd2fb6) | Jan 02, 2024 |
| HP            | Notebook                    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | [db100cd948](https://linux-hardware.org/?probe=db100cd948) | Jan 02, 2024 |
| System76      | Serval                      | [a0597a9161](https://linux-hardware.org/?probe=a0597a9161) | Jan 02, 2024 |
| HP            | ProBook 450 G5              | [b80a7c9287](https://linux-hardware.org/?probe=b80a7c9287) | Jan 02, 2024 |
| System76      | Serval                      | [c4a91b64e5](https://linux-hardware.org/?probe=c4a91b64e5) | Jan 02, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c106ff91a5](https://linux-hardware.org/?probe=c106ff91a5) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [5570fbf22f](https://linux-hardware.org/?probe=5570fbf22f) | Jan 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [a9ddfb0974](https://linux-hardware.org/?probe=a9ddfb0974) | Jan 02, 2024 |
| MSI           | GS65 Stealth 9SG            | [6f3ddca46b](https://linux-hardware.org/?probe=6f3ddca46b) | Jan 02, 2024 |
| HP            | ProBook 430 G2              | [c56ad1ad48](https://linux-hardware.org/?probe=c56ad1ad48) | Jan 02, 2024 |
| HP            | 15 Notebook PC              | [9eb25ba0bf](https://linux-hardware.org/?probe=9eb25ba0bf) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| Acer          | Nitro AN515-44              | [9ac5286530](https://linux-hardware.org/?probe=9ac5286530) | Jan 02, 2024 |
| HP            | Laptop 15-db0xxx            | [dc302f3b3e](https://linux-hardware.org/?probe=dc302f3b3e) | Jan 02, 2024 |
| Gateway       | MT6707                      | [a2a87f6e95](https://linux-hardware.org/?probe=a2a87f6e95) | Jan 02, 2024 |
| Dell          | XPS 13 9380                 | [d290e010eb](https://linux-hardware.org/?probe=d290e010eb) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | [b732d30db5](https://linux-hardware.org/?probe=b732d30db5) | Jan 02, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [502ebc99c3](https://linux-hardware.org/?probe=502ebc99c3) | Jan 02, 2024 |
| Valve         | Jupiter                     | [e381b764b0](https://linux-hardware.org/?probe=e381b764b0) | Jan 02, 2024 |
| Dell          | G3 3590                     | [ae7267dd5f](https://linux-hardware.org/?probe=ae7267dd5f) | Jan 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [197c876252](https://linux-hardware.org/?probe=197c876252) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [7fbbe32bb5](https://linux-hardware.org/?probe=7fbbe32bb5) | Jan 02, 2024 |
| HP            | ProBook 430 G1              | [7f61fa84aa](https://linux-hardware.org/?probe=7f61fa84aa) | Jan 02, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [fb59929b28](https://linux-hardware.org/?probe=fb59929b28) | Jan 02, 2024 |
| HP            | Laptop 15-dw0xxx            | [43bc3cd4bd](https://linux-hardware.org/?probe=43bc3cd4bd) | Jan 02, 2024 |
| Philco        | 14M2                        | [b5771423fb](https://linux-hardware.org/?probe=b5771423fb) | Jan 02, 2024 |
| Apple         | MacBookPro9,2               | [133a9d6ebc](https://linux-hardware.org/?probe=133a9d6ebc) | Jan 02, 2024 |
| Lenovo        | Legion Y545 81Q6            | [954ab5a643](https://linux-hardware.org/?probe=954ab5a643) | Jan 02, 2024 |
| System76      | Oryx Pro                    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| HP            | Notebook                    | [f6e5af2da0](https://linux-hardware.org/?probe=f6e5af2da0) | Jan 02, 2024 |
| HP            | Pavilion dv3                | [351a45926e](https://linux-hardware.org/?probe=351a45926e) | Jan 02, 2024 |
| HP            | ProBook 440 G5              | [04753e77e0](https://linux-hardware.org/?probe=04753e77e0) | Jan 02, 2024 |
| Acer          | Aspire A515-51G             | [e7b0efb20a](https://linux-hardware.org/?probe=e7b0efb20a) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| HP            | Pavilion 15                 | [277c4aa7d6](https://linux-hardware.org/?probe=277c4aa7d6) | Jan 02, 2024 |
| eMachines     | E725                        | [1c62e8a613](https://linux-hardware.org/?probe=1c62e8a613) | Jan 02, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [8701a130d2](https://linux-hardware.org/?probe=8701a130d2) | Jan 02, 2024 |
| Acer          | Nitro AN515-58              | [b822b77797](https://linux-hardware.org/?probe=b822b77797) | Jan 02, 2024 |
| Sony          | VGN-AR51SU                  | [ad09db7b69](https://linux-hardware.org/?probe=ad09db7b69) | Jan 01, 2024 |
| Valve         | Jupiter                     | [95183ba54e](https://linux-hardware.org/?probe=95183ba54e) | Jan 01, 2024 |
| Sony          | VGN-AR51SU                  | [01e1a67d40](https://linux-hardware.org/?probe=01e1a67d40) | Jan 01, 2024 |
| Medion        | E11202                      | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [83ae2c858c](https://linux-hardware.org/?probe=83ae2c858c) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [689f8869db](https://linux-hardware.org/?probe=689f8869db) | Jan 01, 2024 |
| HP            | ProBook 4540s               | [aaebda14c1](https://linux-hardware.org/?probe=aaebda14c1) | Jan 01, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | [6ea14ec02e](https://linux-hardware.org/?probe=6ea14ec02e) | Jan 01, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [4ec973722a](https://linux-hardware.org/?probe=4ec973722a) | Jan 01, 2024 |
| Chuwi         | HeroBook Pro                | [97c2ff9710](https://linux-hardware.org/?probe=97c2ff9710) | Jan 01, 2024 |
| Dell          | Inspiron 15 3530            | [ee21ee0e37](https://linux-hardware.org/?probe=ee21ee0e37) | Jan 01, 2024 |
| eMachines     | E725                        | [6485437ffb](https://linux-hardware.org/?probe=6485437ffb) | Jan 01, 2024 |
| Unknown       | Apple MacBook Air (13-in... | [834855dcac](https://linux-hardware.org/?probe=834855dcac) | Jan 01, 2024 |
| Fujitsu       | LIFEBOOK E780               | [6606e3d150](https://linux-hardware.org/?probe=6606e3d150) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | [cdb97873fa](https://linux-hardware.org/?probe=cdb97873fa) | Jan 01, 2024 |
| TUXEDO        | N8xxEZ                      | [4eb785f281](https://linux-hardware.org/?probe=4eb785f281) | Jan 01, 2024 |
| System76      | Pangolin                    | [58876a3573](https://linux-hardware.org/?probe=58876a3573) | Jan 01, 2024 |
| Timi          | RedmiBook Pro 14S           | [08718e205b](https://linux-hardware.org/?probe=08718e205b) | Jan 01, 2024 |
| Dell          | Inspiron N5110              | [bf974230c7](https://linux-hardware.org/?probe=bf974230c7) | Jan 01, 2024 |
| HP            | G60                         | [a151a8084c](https://linux-hardware.org/?probe=a151a8084c) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | [f9d4fa4d55](https://linux-hardware.org/?probe=f9d4fa4d55) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [c71368b0eb](https://linux-hardware.org/?probe=c71368b0eb) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d4335b1132](https://linux-hardware.org/?probe=d4335b1132) | Jan 01, 2024 |
| MSI           | N6105                       | [0b934bf922](https://linux-hardware.org/?probe=0b934bf922) | Jan 01, 2024 |
| HP            | Laptop 15-dw0xxx            | [66f6fa63a2](https://linux-hardware.org/?probe=66f6fa63a2) | Jan 01, 2024 |
| Lenovo        | ThinkPad X260 20F5S0KE00    | [08d2a7a982](https://linux-hardware.org/?probe=08d2a7a982) | Jan 01, 2024 |
| Acer          | Aspire A517-52G             | [fb86c6f71c](https://linux-hardware.org/?probe=fb86c6f71c) | Jan 01, 2024 |
| Packard Be... | EasyNote TE11HC             | [8dab3905db](https://linux-hardware.org/?probe=8dab3905db) | Jan 01, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [6826d7c88d](https://linux-hardware.org/?probe=6826d7c88d) | Jan 01, 2024 |
| ASUSTek       | K54HR                       | [c84a5fe9d7](https://linux-hardware.org/?probe=c84a5fe9d7) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [8a14ad7cc9](https://linux-hardware.org/?probe=8a14ad7cc9) | Jan 01, 2024 |
| Google        | Gallop                      | [917756724c](https://linux-hardware.org/?probe=917756724c) | Jan 01, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [a2acc5bb5f](https://linux-hardware.org/?probe=a2acc5bb5f) | Jan 01, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [67ef36b749](https://linux-hardware.org/?probe=67ef36b749) | Jan 01, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [9c0957293d](https://linux-hardware.org/?probe=9c0957293d) | Jan 01, 2024 |
| Apple         | MacBookPro11,2              | [4a37a9b35c](https://linux-hardware.org/?probe=4a37a9b35c) | Jan 01, 2024 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [a679e6f722](https://linux-hardware.org/?probe=a679e6f722) | Jan 01, 2024 |
| Sony          | VJF153                      | [9bf924f424](https://linux-hardware.org/?probe=9bf924f424) | Jan 01, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [5cde8dcd78](https://linux-hardware.org/?probe=5cde8dcd78) | Jan 01, 2024 |
| Dell          | Inspiron 5537               | [d19fc7dff7](https://linux-hardware.org/?probe=d19fc7dff7) | Jan 01, 2024 |
| Dell          | Latitude 5511               | [3b186725e3](https://linux-hardware.org/?probe=3b186725e3) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [20f988146c](https://linux-hardware.org/?probe=20f988146c) | Jan 01, 2024 |
| Acer          | Aspire A315-54K             | [d0fa49f90a](https://linux-hardware.org/?probe=d0fa49f90a) | Jan 01, 2024 |
| ASUSTek       | K54HR                       | [03ce083285](https://linux-hardware.org/?probe=03ce083285) | Jan 01, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [095d9cbf7e](https://linux-hardware.org/?probe=095d9cbf7e) | Jan 01, 2024 |
| eMachines     | E525                        | [a99f0e3394](https://linux-hardware.org/?probe=a99f0e3394) | Jan 01, 2024 |
| Dell          | Inspiron 15-3567            | [54e9b80fb3](https://linux-hardware.org/?probe=54e9b80fb3) | Jan 01, 2024 |
| Lenovo        | ThinkPad T460 20FMS2291P    | [1a86f2a3d4](https://linux-hardware.org/?probe=1a86f2a3d4) | Jan 01, 2024 |
| ASUSTek       | K52Jc                       | [5f0c993270](https://linux-hardware.org/?probe=5f0c993270) | Jan 01, 2024 |
| Dell          | Latitude 7490               | [efab03db5f](https://linux-hardware.org/?probe=efab03db5f) | Jan 01, 2024 |
| Dell          | Inspiron 15-3567            | [c67f642893](https://linux-hardware.org/?probe=c67f642893) | Jan 01, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [494b496889](https://linux-hardware.org/?probe=494b496889) | Jan 01, 2024 |
| MSI           | N6105                       | [24f1343e04](https://linux-hardware.org/?probe=24f1343e04) | Jan 01, 2024 |
| Apple         | MacBookPro7,1               | [9181cf5581](https://linux-hardware.org/?probe=9181cf5581) | Jan 01, 2024 |
| Sony          | VPCEH3P1R                   | [d5a18ec675](https://linux-hardware.org/?probe=d5a18ec675) | Jan 01, 2024 |
| Acer          | One 14 Z8-415               | [b022baea77](https://linux-hardware.org/?probe=b022baea77) | Jan 01, 2024 |
| Acer          | One 14 Z8-415               | [0e2bbf3d20](https://linux-hardware.org/?probe=0e2bbf3d20) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [65fb7df562](https://linux-hardware.org/?probe=65fb7df562) | Jan 01, 2024 |
| HP            | EliteBook 850 G4            | [bd25e4866f](https://linux-hardware.org/?probe=bd25e4866f) | Jan 01, 2024 |
| ASUSTek       | X555LB                      | [6e12fcec56](https://linux-hardware.org/?probe=6e12fcec56) | Jan 01, 2024 |
| Dell          | Latitude 5310               | [87c543db6f](https://linux-hardware.org/?probe=87c543db6f) | Jan 01, 2024 |
| Valve         | Jupiter                     | [c9de553faa](https://linux-hardware.org/?probe=c9de553faa) | Jan 01, 2024 |
| Google        | Caroline                    | [95fb0e423e](https://linux-hardware.org/?probe=95fb0e423e) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [de7126bf06](https://linux-hardware.org/?probe=de7126bf06) | Jan 01, 2024 |
| Dell          | Latitude 5480               | [c1d96bef16](https://linux-hardware.org/?probe=c1d96bef16) | Jan 01, 2024 |
| TUXEDO        | Polaris AMD Gen5            | [aa5447c317](https://linux-hardware.org/?probe=aa5447c317) | Jan 01, 2024 |
| HP            | Pavilion Notebook           | [a7ff16d496](https://linux-hardware.org/?probe=a7ff16d496) | Jan 01, 2024 |
| Lenovo        | Legion Y7000P2020H 82AX     | [59d5eb147b](https://linux-hardware.org/?probe=59d5eb147b) | Jan 01, 2024 |
| Lenovo        | ThinkPad T430 2349SB4       | [06956b900b](https://linux-hardware.org/?probe=06956b900b) | Jan 01, 2024 |
| HP            | EliteBook 820 G1            | [60a0cb2296](https://linux-hardware.org/?probe=60a0cb2296) | Jan 01, 2024 |
| Sony          | VJF153                      | [b3949d3670](https://linux-hardware.org/?probe=b3949d3670) | Jan 01, 2024 |
| Fujitsu       | LIFEBOOK A530               | [044d66edb4](https://linux-hardware.org/?probe=044d66edb4) | Jan 01, 2024 |
| MSI           | P65 Creator 9SE             | [2e5c1a6b06](https://linux-hardware.org/?probe=2e5c1a6b06) | Jan 01, 2024 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [156c23e1d0](https://linux-hardware.org/?probe=156c23e1d0) | Jan 01, 2024 |
| Sony          | SVE1713X1EB                 | [f9081b680a](https://linux-hardware.org/?probe=f9081b680a) | Jan 01, 2024 |
| Packard Be... | EasyNote LJ65               | [52bbda495f](https://linux-hardware.org/?probe=52bbda495f) | Jan 01, 2024 |
| Notebook      | N13xWU                      | [d877ecb7be](https://linux-hardware.org/?probe=d877ecb7be) | Jan 01, 2024 |
| Valve         | Jupiter                     | [b16497fbfc](https://linux-hardware.org/?probe=b16497fbfc) | Jan 01, 2024 |
| Gateway       | M-6307                      | [0936f4a650](https://linux-hardware.org/?probe=0936f4a650) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | [29ab65f09e](https://linux-hardware.org/?probe=29ab65f09e) | Jan 01, 2024 |
| Lenovo        | ThinkPad Twist 33476LU      | [bb88a71510](https://linux-hardware.org/?probe=bb88a71510) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | [3afdb557c8](https://linux-hardware.org/?probe=3afdb557c8) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a70caacf5a](https://linux-hardware.org/?probe=a70caacf5a) | Jan 01, 2024 |
| Dell          | Inspiron 5379               | [c3c47e54db](https://linux-hardware.org/?probe=c3c47e54db) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | [34dd6e3ec3](https://linux-hardware.org/?probe=34dd6e3ec3) | Jan 01, 2024 |
| Apple         | MacBookAir9,1               | [5a511e238e](https://linux-hardware.org/?probe=5a511e238e) | Jan 01, 2024 |
| Toshiba       | Satellite A660              | [4b00ffd071](https://linux-hardware.org/?probe=4b00ffd071) | Jan 01, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [488deac73a](https://linux-hardware.org/?probe=488deac73a) | Jan 01, 2024 |
| Dell          | Latitude E5470              | [fdc804210f](https://linux-hardware.org/?probe=fdc804210f) | Jan 01, 2024 |
| Dell          | Inspiron 3593               | [a2424d3523](https://linux-hardware.org/?probe=a2424d3523) | Jan 01, 2024 |
| Lenovo        | ThinkPad T410 2537BF9       | [5d62cfc80b](https://linux-hardware.org/?probe=5d62cfc80b) | Jan 01, 2024 |
| Lenovo        | ThinkPad T495 20NJ0008US    | [2872198e9f](https://linux-hardware.org/?probe=2872198e9f) | Jan 01, 2024 |
| Dell          | Inspiron 5402               | [388a6a9fc1](https://linux-hardware.org/?probe=388a6a9fc1) | Jan 01, 2024 |
| Dell          | Vostro 3405                 | [78db308528](https://linux-hardware.org/?probe=78db308528) | Jan 01, 2024 |
| HP            | Stream Laptop 14-ax0XX      | [4434600249](https://linux-hardware.org/?probe=4434600249) | Jan 01, 2024 |
| Sony          | VPCSB1V9E                   | [31cb181036](https://linux-hardware.org/?probe=31cb181036) | Jan 01, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [4eb26f2685](https://linux-hardware.org/?probe=4eb26f2685) | Jan 01, 2024 |
| Acer          | Aspire ES1-523              | [e270ce7266](https://linux-hardware.org/?probe=e270ce7266) | Jan 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [6a6513cf92](https://linux-hardware.org/?probe=6a6513cf92) | Jan 01, 2024 |
| ASUSTek       | X75VC                       | [cb47b15eb9](https://linux-hardware.org/?probe=cb47b15eb9) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| HP            | ProBook 640 G1              | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| Valve         | Jupiter                     | [e714aab1f3](https://linux-hardware.org/?probe=e714aab1f3) | Jan 01, 2024 |
| HP            | Laptop 15s-eq2xxx           | [2f1b4ada4b](https://linux-hardware.org/?probe=2f1b4ada4b) | Jan 01, 2024 |
| Acer          | Aspire E1-531               | [6c2a4cd173](https://linux-hardware.org/?probe=6c2a4cd173) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | [22ba5950e3](https://linux-hardware.org/?probe=22ba5950e3) | Jan 01, 2024 |
| Sony          | VGN-NW11S_S                 | [6d47430c42](https://linux-hardware.org/?probe=6d47430c42) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [0120368c3a](https://linux-hardware.org/?probe=0120368c3a) | Jan 01, 2024 |
| Sony          | VGN-NW11S_S                 | [e898dd413e](https://linux-hardware.org/?probe=e898dd413e) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | [dddd9b59bf](https://linux-hardware.org/?probe=dddd9b59bf) | Jan 01, 2024 |
| ASUSTek       | X751LA                      | [089bb5bca9](https://linux-hardware.org/?probe=089bb5bca9) | Jan 01, 2024 |
| ASUSTek       | G75VW                       | [56e330d7bc](https://linux-hardware.org/?probe=56e330d7bc) | Dec 31, 2023 |
| Dell          | Inspiron N5110              | [439d746143](https://linux-hardware.org/?probe=439d746143) | Dec 31, 2023 |
| HP            | Pavilion Gaming Notebook    | [8fdfce9fb8](https://linux-hardware.org/?probe=8fdfce9fb8) | Dec 31, 2023 |
| Medion        | Akoya E6239                 | [757858a876](https://linux-hardware.org/?probe=757858a876) | Dec 31, 2023 |
| Dell          | Latitude 3420               | [775325daa6](https://linux-hardware.org/?probe=775325daa6) | Dec 31, 2023 |
| Acer          | Nitro AN515-55              | [14f7c6a9df](https://linux-hardware.org/?probe=14f7c6a9df) | Dec 31, 2023 |
| Dell          | Latitude E6320              | [1833dcdd43](https://linux-hardware.org/?probe=1833dcdd43) | Dec 31, 2023 |
| Apple         | MacBookAir4,2               | [7ebd4a00e7](https://linux-hardware.org/?probe=7ebd4a00e7) | Dec 31, 2023 |
| Apple         | MacBookAir7,2               | [b25bae6ded](https://linux-hardware.org/?probe=b25bae6ded) | Dec 31, 2023 |
| ASUSTek       | UX550VE                     | [90014cac84](https://linux-hardware.org/?probe=90014cac84) | Dec 31, 2023 |
| HUAWEI        | KLVL-WXX9                   | [28ad8513b4](https://linux-hardware.org/?probe=28ad8513b4) | Dec 31, 2023 |
| Dell          | Latitude E6220              | [11568cda87](https://linux-hardware.org/?probe=11568cda87) | Dec 31, 2023 |
| HP            | Laptop 17-cn0xxx            | [b3568ff9cb](https://linux-hardware.org/?probe=b3568ff9cb) | Dec 31, 2023 |
| Apple         | MacBookPro8,1               | [85665aae4c](https://linux-hardware.org/?probe=85665aae4c) | Dec 31, 2023 |
| ASUSTek       | K54HR                       | [0e5edd355d](https://linux-hardware.org/?probe=0e5edd355d) | Dec 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [c0587a6f3f](https://linux-hardware.org/?probe=c0587a6f3f) | Dec 31, 2023 |
| Google        | Caroline                    | [94a1dd78ec](https://linux-hardware.org/?probe=94a1dd78ec) | Dec 31, 2023 |
| Dell          | Latitude E6500              | [8d7d1376fd](https://linux-hardware.org/?probe=8d7d1376fd) | Dec 31, 2023 |
| Dell          | Latitude 7420               | [a32d08979b](https://linux-hardware.org/?probe=a32d08979b) | Dec 31, 2023 |
| ASUSTek       | K53SC                       | [1f2ddea9fa](https://linux-hardware.org/?probe=1f2ddea9fa) | Dec 31, 2023 |
| Alienware     | M17xR3                      | [ed05d87c74](https://linux-hardware.org/?probe=ed05d87c74) | Dec 31, 2023 |
| HP            | Laptop 17-ca1xxx            | [b569c39f5a](https://linux-hardware.org/?probe=b569c39f5a) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [cd2840bccc](https://linux-hardware.org/?probe=cd2840bccc) | Dec 31, 2023 |
| ASUSTek       | 1001PX                      | [e0e36774e8](https://linux-hardware.org/?probe=e0e36774e8) | Dec 31, 2023 |
| Google        | Caroline                    | [0d1ce09fbd](https://linux-hardware.org/?probe=0d1ce09fbd) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | [5dde4deb12](https://linux-hardware.org/?probe=5dde4deb12) | Dec 31, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ec8f742a7f](https://linux-hardware.org/?probe=ec8f742a7f) | Dec 31, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [bc788ac36f](https://linux-hardware.org/?probe=bc788ac36f) | Dec 31, 2023 |
| Info Quest... | GTN1402 4-64                | [c363bd26ad](https://linux-hardware.org/?probe=c363bd26ad) | Dec 31, 2023 |
| HP            | Laptop 14s-dq1xxx           | [f5f0fa82e5](https://linux-hardware.org/?probe=f5f0fa82e5) | Dec 31, 2023 |
| Dell          | Inspiron 5567               | [c271898460](https://linux-hardware.org/?probe=c271898460) | Dec 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| Dell          | Inspiron 15-3567            | [390160b8e5](https://linux-hardware.org/?probe=390160b8e5) | Dec 31, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | [eeba7c76f2](https://linux-hardware.org/?probe=eeba7c76f2) | Dec 31, 2023 |
| ASUSTek       | VivoBook E14 E402YA_R417... | [47112e4c46](https://linux-hardware.org/?probe=47112e4c46) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| HP            | Pavilion 17                 | [77a7431f73](https://linux-hardware.org/?probe=77a7431f73) | Dec 31, 2023 |
| Acer          | EX5235                      | [c92709aa57](https://linux-hardware.org/?probe=c92709aa57) | Dec 31, 2023 |
| Dell          | Latitude 7420               | [9bee55a186](https://linux-hardware.org/?probe=9bee55a186) | Dec 31, 2023 |
| Google        | Peppy                       | [9b8131eea3](https://linux-hardware.org/?probe=9b8131eea3) | Dec 31, 2023 |
| Acer          | EX5235                      | [4a0cb756ff](https://linux-hardware.org/?probe=4a0cb756ff) | Dec 31, 2023 |
| Dell          | Latitude E6540              | [aa122de07a](https://linux-hardware.org/?probe=aa122de07a) | Dec 31, 2023 |
| Unknown       | Unknown                     | [764c59c56e](https://linux-hardware.org/?probe=764c59c56e) | Dec 31, 2023 |
| Acer          | Aspire SW5-012              | [efc348dbe0](https://linux-hardware.org/?probe=efc348dbe0) | Dec 31, 2023 |
| Irbis         | NB264                       | [b7da9b39c3](https://linux-hardware.org/?probe=b7da9b39c3) | Dec 31, 2023 |
| Dell          | Latitude E4310              | [10397fd191](https://linux-hardware.org/?probe=10397fd191) | Dec 31, 2023 |
| Medion        | M14L-256                    | [0dbbd4db74](https://linux-hardware.org/?probe=0dbbd4db74) | Dec 31, 2023 |
| ASUSTek       | X450CC                      | [0d985ff465](https://linux-hardware.org/?probe=0d985ff465) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [9872ef6241](https://linux-hardware.org/?probe=9872ef6241) | Dec 31, 2023 |
| HP            | ProBook 450 G1              | [a83eb9d306](https://linux-hardware.org/?probe=a83eb9d306) | Dec 31, 2023 |
| Dell          | Latitude 7480               | [527544c2de](https://linux-hardware.org/?probe=527544c2de) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1f44330bcf](https://linux-hardware.org/?probe=1f44330bcf) | Dec 31, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [9f9b454f97](https://linux-hardware.org/?probe=9f9b454f97) | Dec 31, 2023 |
| HP            | 250 G1                      | [da6bcc5b27](https://linux-hardware.org/?probe=da6bcc5b27) | Dec 31, 2023 |
| Apple         | MacBookPro6,2               | [1a25482d3d](https://linux-hardware.org/?probe=1a25482d3d) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [a37bbce8de](https://linux-hardware.org/?probe=a37bbce8de) | Dec 31, 2023 |
| Toshiba       | Satellite Pro C660          | [c3736ea548](https://linux-hardware.org/?probe=c3736ea548) | Dec 31, 2023 |
| Lenovo        | IdeaPad 320-14IAP 80XQ      | [1fedc1bf30](https://linux-hardware.org/?probe=1fedc1bf30) | Dec 31, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [1258df680a](https://linux-hardware.org/?probe=1258df680a) | Dec 31, 2023 |
| HP            | OMEN by Laptop              | [8b1ac4e80c](https://linux-hardware.org/?probe=8b1ac4e80c) | Dec 31, 2023 |
| ASUSTek       | K53U                        | [84ba38c3c5](https://linux-hardware.org/?probe=84ba38c3c5) | Dec 31, 2023 |
| Valve         | Jupiter                     | [ca7a54408f](https://linux-hardware.org/?probe=ca7a54408f) | Dec 31, 2023 |
| Dell          | Latitude 5480               | [3d096bf8e4](https://linux-hardware.org/?probe=3d096bf8e4) | Dec 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [577f6b15de](https://linux-hardware.org/?probe=577f6b15de) | Dec 31, 2023 |
| Dell          | Latitude D630               | [bbae93d767](https://linux-hardware.org/?probe=bbae93d767) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | [92906e6c95](https://linux-hardware.org/?probe=92906e6c95) | Dec 31, 2023 |
| ASUSTek       | X75VC                       | [e2ebd9354f](https://linux-hardware.org/?probe=e2ebd9354f) | Dec 31, 2023 |
| Google        | Delbin                      | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [a4596b8ae1](https://linux-hardware.org/?probe=a4596b8ae1) | Dec 31, 2023 |
| Valve         | Jupiter                     | [5be404c400](https://linux-hardware.org/?probe=5be404c400) | Dec 31, 2023 |
| Dell          | Inspiron 3537               | [7adc50aeab](https://linux-hardware.org/?probe=7adc50aeab) | Dec 31, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [9894c7bf9f](https://linux-hardware.org/?probe=9894c7bf9f) | Dec 31, 2023 |
| Lenovo        | ThinkPad T61 7662CTO        | [d38807fbbe](https://linux-hardware.org/?probe=d38807fbbe) | Dec 31, 2023 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [b66d7c38c1](https://linux-hardware.org/?probe=b66d7c38c1) | Dec 31, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [d694f21feb](https://linux-hardware.org/?probe=d694f21feb) | Dec 31, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [47e1e3c766](https://linux-hardware.org/?probe=47e1e3c766) | Dec 31, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [fc3a637b52](https://linux-hardware.org/?probe=fc3a637b52) | Dec 31, 2023 |
| Acer          | Extensa 5220                | [dd3638713e](https://linux-hardware.org/?probe=dd3638713e) | Dec 31, 2023 |
| Dell          | Latitude 7490               | [455ad2a6f1](https://linux-hardware.org/?probe=455ad2a6f1) | Dec 31, 2023 |
| Lenovo        | ThinkPad T480s 20L8S35G0... | [f2357e961c](https://linux-hardware.org/?probe=f2357e961c) | Dec 31, 2023 |
| Acer          | Aspire A515-43              | [68a2707c3f](https://linux-hardware.org/?probe=68a2707c3f) | Dec 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d975ab384e](https://linux-hardware.org/?probe=d975ab384e) | Dec 31, 2023 |
| Thirdwave     | Prime Series                | [dc3d167b01](https://linux-hardware.org/?probe=dc3d167b01) | Dec 31, 2023 |
| HP            | ProBook 11 G2               | [6cf8228f10](https://linux-hardware.org/?probe=6cf8228f10) | Dec 31, 2023 |
| Toshiba       | Satellite P55-B             | [9a1e5dc1f6](https://linux-hardware.org/?probe=9a1e5dc1f6) | Dec 31, 2023 |
| Dell          | Inspiron 3521               | [7de98bea51](https://linux-hardware.org/?probe=7de98bea51) | Dec 31, 2023 |
| Valve         | Jupiter                     | [e80d5f8a2b](https://linux-hardware.org/?probe=e80d5f8a2b) | Dec 31, 2023 |
| IBM           | ThinkPad T43 1875DMU        | [a33e9f7b0d](https://linux-hardware.org/?probe=a33e9f7b0d) | Dec 31, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | [7b1fe348e4](https://linux-hardware.org/?probe=7b1fe348e4) | Dec 31, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [f160a53f1b](https://linux-hardware.org/?probe=f160a53f1b) | Dec 31, 2023 |
| Apple         | MacBookPro9,2               | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | [70bbf55180](https://linux-hardware.org/?probe=70bbf55180) | Dec 31, 2023 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | [0afd47e9fc](https://linux-hardware.org/?probe=0afd47e9fc) | Dec 31, 2023 |
| Dell          | Latitude E4300              | [528165bb06](https://linux-hardware.org/?probe=528165bb06) | Dec 31, 2023 |
| Acer          | Predator PH16-71            | [deae7730f2](https://linux-hardware.org/?probe=deae7730f2) | Dec 31, 2023 |
| Dell          | Latitude E5430 non-vPro     | [e27c2e0ade](https://linux-hardware.org/?probe=e27c2e0ade) | Dec 31, 2023 |
| NEC Comput... | PC-VK19SGZDF                | [aa9f420488](https://linux-hardware.org/?probe=aa9f420488) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K540... | [70c84eadc0](https://linux-hardware.org/?probe=70c84eadc0) | Dec 31, 2023 |
| Apple         | MacBook6,1                  | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [9c355f1603](https://linux-hardware.org/?probe=9c355f1603) | Dec 31, 2023 |
| Lenovo        | Legion Y545 81Q6            | [a91810bda7](https://linux-hardware.org/?probe=a91810bda7) | Dec 31, 2023 |
| Apple         | MacBookPro10,2              | [275f675ca4](https://linux-hardware.org/?probe=275f675ca4) | Dec 31, 2023 |
| Apple         | MacBookPro8,2               | [34fcef3266](https://linux-hardware.org/?probe=34fcef3266) | Dec 31, 2023 |
| Lenovo        | Y50-70 20378                | [ff5e2959f8](https://linux-hardware.org/?probe=ff5e2959f8) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [7130d1a699](https://linux-hardware.org/?probe=7130d1a699) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | [d04c4d749f](https://linux-hardware.org/?probe=d04c4d749f) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [815e8736a2](https://linux-hardware.org/?probe=815e8736a2) | Dec 31, 2023 |
| Lenovo        | ThinkPad T420 4178AFU       | [8fb51545f7](https://linux-hardware.org/?probe=8fb51545f7) | Dec 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [b5bf7051ef](https://linux-hardware.org/?probe=b5bf7051ef) | Dec 31, 2023 |
| Notebook      | NL5xNU                      | [915031852a](https://linux-hardware.org/?probe=915031852a) | Dec 31, 2023 |
| Lenovo        | ThinkPad T430 2349SVA       | [1a897f9fbd](https://linux-hardware.org/?probe=1a897f9fbd) | Dec 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [49a4d9cad0](https://linux-hardware.org/?probe=49a4d9cad0) | Dec 31, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [942c025f11](https://linux-hardware.org/?probe=942c025f11) | Dec 31, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4582e28453](https://linux-hardware.org/?probe=4582e28453) | Dec 31, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [4dd47839a4](https://linux-hardware.org/?probe=4dd47839a4) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [934f756965](https://linux-hardware.org/?probe=934f756965) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | [71c755966f](https://linux-hardware.org/?probe=71c755966f) | Dec 31, 2023 |
| Valve         | Jupiter                     | [c459051f01](https://linux-hardware.org/?probe=c459051f01) | Dec 31, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [a62110fad4](https://linux-hardware.org/?probe=a62110fad4) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | [b13ec8c4fe](https://linux-hardware.org/?probe=b13ec8c4fe) | Dec 31, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [76869cc8d4](https://linux-hardware.org/?probe=76869cc8d4) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| Dell          | Latitude 5480               | [cf678e4c6d](https://linux-hardware.org/?probe=cf678e4c6d) | Dec 31, 2023 |
| HP            | Laptop 17-cn3xxx            | [3a84122c5a](https://linux-hardware.org/?probe=3a84122c5a) | Dec 30, 2023 |
| Dell          | Latitude E6440              | [f4ba63ff52](https://linux-hardware.org/?probe=f4ba63ff52) | Dec 30, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [eb25c26beb](https://linux-hardware.org/?probe=eb25c26beb) | Dec 30, 2023 |
| Google        | Blorb                       | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| ASUSTek       | PRIME B360M-A               | [42b25d8ac5](https://linux-hardware.org/?probe=42b25d8ac5) | Dec 30, 2023 |
| HP            | Laptop 14s-ef1xxx           | [961d2db618](https://linux-hardware.org/?probe=961d2db618) | Dec 30, 2023 |
| HP            | 250 G6 Notebook PC          | [1a5d669774](https://linux-hardware.org/?probe=1a5d669774) | Dec 30, 2023 |
| Lenovo        | ThinkPad X390 20Q0004VUS    | [4bd6b36cd6](https://linux-hardware.org/?probe=4bd6b36cd6) | Dec 30, 2023 |
| Notebook      | NJx0MU                      | [c7f2d68d77](https://linux-hardware.org/?probe=c7f2d68d77) | Dec 30, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [8b28cb5a8f](https://linux-hardware.org/?probe=8b28cb5a8f) | Dec 30, 2023 |
| Dell          | Inspiron 3505               | [bbcd14000a](https://linux-hardware.org/?probe=bbcd14000a) | Dec 30, 2023 |
| HP            | Pavilion g6                 | [6adc1110b8](https://linux-hardware.org/?probe=6adc1110b8) | Dec 30, 2023 |
| Dell          | Latitude 5540               | [604aab0481](https://linux-hardware.org/?probe=604aab0481) | Dec 30, 2023 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [11892aa026](https://linux-hardware.org/?probe=11892aa026) | Dec 30, 2023 |
| ASUSTek       | PRIME X570-P                | [12b2d456ed](https://linux-hardware.org/?probe=12b2d456ed) | Dec 30, 2023 |
| Packard Be... | EasyNote TS44HR             | [a06265dd1e](https://linux-hardware.org/?probe=a06265dd1e) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | [04acb5230d](https://linux-hardware.org/?probe=04acb5230d) | Dec 30, 2023 |
| ASUSTek       | G74Sx                       | [0933c174aa](https://linux-hardware.org/?probe=0933c174aa) | Dec 30, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [4f95b9d510](https://linux-hardware.org/?probe=4f95b9d510) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [f96a0610cb](https://linux-hardware.org/?probe=f96a0610cb) | Dec 30, 2023 |
| Sony          | VGN-CS21Z_Q                 | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| HP            | ProBook 470 G3              | [22bd0ee412](https://linux-hardware.org/?probe=22bd0ee412) | Dec 30, 2023 |
| Dell          | Precision 3551              | [38a733d0c4](https://linux-hardware.org/?probe=38a733d0c4) | Dec 30, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [0b8c1c9e17](https://linux-hardware.org/?probe=0b8c1c9e17) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2352ac6075](https://linux-hardware.org/?probe=2352ac6075) | Dec 30, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [ca0a0fe5cf](https://linux-hardware.org/?probe=ca0a0fe5cf) | Dec 30, 2023 |
| MSI           | Prestige 15 A10SC           | [e61eb5428f](https://linux-hardware.org/?probe=e61eb5428f) | Dec 30, 2023 |
| Medion        | Akoya E6240T                | [f23e5a29d5](https://linux-hardware.org/?probe=f23e5a29d5) | Dec 30, 2023 |
| Apple         | MacBookAir9,1               | [25fea8aab5](https://linux-hardware.org/?probe=25fea8aab5) | Dec 30, 2023 |
| Intel         | ChiefRiver                  | [6fc4ceeaa6](https://linux-hardware.org/?probe=6fc4ceeaa6) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [5f33ce2d18](https://linux-hardware.org/?probe=5f33ce2d18) | Dec 30, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [136a9fa2b5](https://linux-hardware.org/?probe=136a9fa2b5) | Dec 30, 2023 |
| MSI           | Stealth 16Studio A13VF      | [1fd1d2e727](https://linux-hardware.org/?probe=1fd1d2e727) | Dec 30, 2023 |
| DERE          | Unknown                     | [0c27b482df](https://linux-hardware.org/?probe=0c27b482df) | Dec 30, 2023 |
| Dell          | Latitude E7450              | [dd5f4a17c4](https://linux-hardware.org/?probe=dd5f4a17c4) | Dec 30, 2023 |
| Dell          | Inspiron 7460               | [1085eef155](https://linux-hardware.org/?probe=1085eef155) | Dec 30, 2023 |
| Dell          | Inspiron 5748               | [20017233b9](https://linux-hardware.org/?probe=20017233b9) | Dec 30, 2023 |
| HP            | Pavilion 17                 | [d6e11fbd64](https://linux-hardware.org/?probe=d6e11fbd64) | Dec 30, 2023 |
| Chuwi         | HeroBook Pro                | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| Apple         | MacBookPro11,5              | [4987fb1cb9](https://linux-hardware.org/?probe=4987fb1cb9) | Dec 30, 2023 |
| Microtech     | CoreBook                    | [f82534d32b](https://linux-hardware.org/?probe=f82534d32b) | Dec 30, 2023 |
| Dell          | Inspiron 15-3567            | [5d1ed5c106](https://linux-hardware.org/?probe=5d1ed5c106) | Dec 30, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [aa1bee686a](https://linux-hardware.org/?probe=aa1bee686a) | Dec 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [adf7c97dab](https://linux-hardware.org/?probe=adf7c97dab) | Dec 30, 2023 |
| ASUSTek       | X751LJ                      | [0ebf64067f](https://linux-hardware.org/?probe=0ebf64067f) | Dec 30, 2023 |
| Valve         | Jupiter                     | [2f8ea60a38](https://linux-hardware.org/?probe=2f8ea60a38) | Dec 30, 2023 |
| ASUSTek       | G75VW                       | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| Google        | Barla                       | [585887bc42](https://linux-hardware.org/?probe=585887bc42) | Dec 30, 2023 |
| Dell          | Latitude E5520              | [bdc879aa29](https://linux-hardware.org/?probe=bdc879aa29) | Dec 30, 2023 |
| HP            | ProBook 440 G6              | [14623af544](https://linux-hardware.org/?probe=14623af544) | Dec 30, 2023 |
| Chuwi         | GemiBook                    | [3e5282eb93](https://linux-hardware.org/?probe=3e5282eb93) | Dec 30, 2023 |
| ASUSTek       | K52JB                       | [169f787cff](https://linux-hardware.org/?probe=169f787cff) | Dec 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1372c9e7e6](https://linux-hardware.org/?probe=1372c9e7e6) | Dec 30, 2023 |
| Infinix       | INBOOK X1 NEO               | [71e74b3e03](https://linux-hardware.org/?probe=71e74b3e03) | Dec 30, 2023 |
| HP            | EliteBook 840 G3            | [d3bb35f033](https://linux-hardware.org/?probe=d3bb35f033) | Dec 30, 2023 |
| ASUSTek       | PRIME X570-P                | [596a41673a](https://linux-hardware.org/?probe=596a41673a) | Dec 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [ff8e890649](https://linux-hardware.org/?probe=ff8e890649) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b94c50cb10](https://linux-hardware.org/?probe=b94c50cb10) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f391231013](https://linux-hardware.org/?probe=f391231013) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8f3ab867ea](https://linux-hardware.org/?probe=8f3ab867ea) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [86a499d322](https://linux-hardware.org/?probe=86a499d322) | Dec 30, 2023 |
| HP            | EliteBook 840 G3            | [52ed3f7e82](https://linux-hardware.org/?probe=52ed3f7e82) | Dec 30, 2023 |
| Monster       | ABRA A5 V13.4               | [8cb3a2ee0a](https://linux-hardware.org/?probe=8cb3a2ee0a) | Dec 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [895594b67d](https://linux-hardware.org/?probe=895594b67d) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [460fe0575c](https://linux-hardware.org/?probe=460fe0575c) | Dec 30, 2023 |
| Samsung       | R530/R730/R540              | [c914756956](https://linux-hardware.org/?probe=c914756956) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | [811e5b34cd](https://linux-hardware.org/?probe=811e5b34cd) | Dec 30, 2023 |
| Dell          | Latitude 5480               | [a1bc8df9e4](https://linux-hardware.org/?probe=a1bc8df9e4) | Dec 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| Samsung       | RC530/RC730                 | [866c256904](https://linux-hardware.org/?probe=866c256904) | Dec 30, 2023 |
| Dell          | Latitude E6440              | [8c8ec73113](https://linux-hardware.org/?probe=8c8ec73113) | Dec 30, 2023 |
| HP            | ProBook 6460b               | [45038d4599](https://linux-hardware.org/?probe=45038d4599) | Dec 30, 2023 |
| Dell          | Latitude E5420              | [0bc1fb2eaf](https://linux-hardware.org/?probe=0bc1fb2eaf) | Dec 30, 2023 |
| HP            | ProBook 6450b               | [ce6d3d0e7f](https://linux-hardware.org/?probe=ce6d3d0e7f) | Dec 30, 2023 |
| HP            | ProBook 6450b               | [f2128c8e8a](https://linux-hardware.org/?probe=f2128c8e8a) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4YE0... | [74d75dc18d](https://linux-hardware.org/?probe=74d75dc18d) | Dec 30, 2023 |
| HP            | Pavilion Plus Laptop 14-... | [c6751f4e51](https://linux-hardware.org/?probe=c6751f4e51) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p 20AWS4UD0... | [0305a2f3cf](https://linux-hardware.org/?probe=0305a2f3cf) | Dec 30, 2023 |
| HP            | ProBook 440 G7              | [10d9fd3230](https://linux-hardware.org/?probe=10d9fd3230) | Dec 30, 2023 |
| Acer          | Nitro AN515-58              | [a0039ef79d](https://linux-hardware.org/?probe=a0039ef79d) | Dec 30, 2023 |
| Dell          | Latitude E7440              | [d9fb6a9ead](https://linux-hardware.org/?probe=d9fb6a9ead) | Dec 30, 2023 |
| HP            | Notebook                    | [c5f68d3103](https://linux-hardware.org/?probe=c5f68d3103) | Dec 30, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [f48ada0e7b](https://linux-hardware.org/?probe=f48ada0e7b) | Dec 30, 2023 |
| HUAWEI        | KLVL-WXX9                   | [f8aeb2c6c3](https://linux-hardware.org/?probe=f8aeb2c6c3) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [33556742c3](https://linux-hardware.org/?probe=33556742c3) | Dec 30, 2023 |
| HP            | ENVY m4                     | [6416f24210](https://linux-hardware.org/?probe=6416f24210) | Dec 30, 2023 |
| Unknown       | Unknown                     | [e67f78cf16](https://linux-hardware.org/?probe=e67f78cf16) | Dec 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | [98f6888dcd](https://linux-hardware.org/?probe=98f6888dcd) | Dec 30, 2023 |
| HP            | EliteBook Folio 1040 G3     | [cb51f62169](https://linux-hardware.org/?probe=cb51f62169) | Dec 30, 2023 |
| System76      | Serval WS                   | [3dd4d45859](https://linux-hardware.org/?probe=3dd4d45859) | Dec 30, 2023 |
| Lenovo        | ThinkPad T440p              | [e45829bd8b](https://linux-hardware.org/?probe=e45829bd8b) | Dec 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2490d5b834](https://linux-hardware.org/?probe=2490d5b834) | Dec 30, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [221c773946](https://linux-hardware.org/?probe=221c773946) | Dec 30, 2023 |
| Lenovo        | B590 20206                  | [d3c6913a54](https://linux-hardware.org/?probe=d3c6913a54) | Dec 30, 2023 |
| Medion        | DEFENDER E10                | [2e99d46be8](https://linux-hardware.org/?probe=2e99d46be8) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [2a29a4613c](https://linux-hardware.org/?probe=2a29a4613c) | Dec 30, 2023 |
| Alurin        | ALU-BAR-I511-000-140        | [04ce6d9f2e](https://linux-hardware.org/?probe=04ce6d9f2e) | Dec 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [394c35d74b](https://linux-hardware.org/?probe=394c35d74b) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Positivo      | Harrison                    | [bf31594bef](https://linux-hardware.org/?probe=bf31594bef) | Dec 30, 2023 |
| HP            | Laptop 15-dy2xxx            | [9ee9bc6de8](https://linux-hardware.org/?probe=9ee9bc6de8) | Dec 30, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JNC... | [6410cef098](https://linux-hardware.org/?probe=6410cef098) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [60da2c756f](https://linux-hardware.org/?probe=60da2c756f) | Dec 30, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ebdb840dba](https://linux-hardware.org/?probe=ebdb840dba) | Dec 30, 2023 |
| Acer          | Aspire A517-52              | [0dfed3df52](https://linux-hardware.org/?probe=0dfed3df52) | Dec 30, 2023 |
| Acer          | Aspire F5-573G              | [4744ad0a98](https://linux-hardware.org/?probe=4744ad0a98) | Dec 30, 2023 |
| HP            | Compaq 610                  | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| ASUSTek       | U52F                        | [acf3ac6f23](https://linux-hardware.org/?probe=acf3ac6f23) | Dec 30, 2023 |
| HP            | ENVY m4                     | [f0cd285399](https://linux-hardware.org/?probe=f0cd285399) | Dec 30, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [8fe9261232](https://linux-hardware.org/?probe=8fe9261232) | Dec 30, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | [017090bd57](https://linux-hardware.org/?probe=017090bd57) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f805c2c9fc](https://linux-hardware.org/?probe=f805c2c9fc) | Dec 30, 2023 |
| HP            | Laptop 15-db0xxx            | [bacd120c51](https://linux-hardware.org/?probe=bacd120c51) | Dec 30, 2023 |
| ASUSTek       | N551JW                      | [12339778af](https://linux-hardware.org/?probe=12339778af) | Dec 30, 2023 |
| Lenovo        | ThinkPad T430 2349FC4       | [689d3295aa](https://linux-hardware.org/?probe=689d3295aa) | Dec 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [24ca756f75](https://linux-hardware.org/?probe=24ca756f75) | Dec 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [96662ed691](https://linux-hardware.org/?probe=96662ed691) | Dec 30, 2023 |
| Acer          | Aspire A517-52              | [1c4684011d](https://linux-hardware.org/?probe=1c4684011d) | Dec 30, 2023 |
| Lenovo        | ThinkPad T61 7662CTO        | [9e025b8cde](https://linux-hardware.org/?probe=9e025b8cde) | Dec 30, 2023 |
| Lenovo        | V15-ADA 82C7                | [80604ec459](https://linux-hardware.org/?probe=80604ec459) | Dec 30, 2023 |
| Google        | Reef                        | [362a174638](https://linux-hardware.org/?probe=362a174638) | Dec 30, 2023 |
| Acer          | Aspire A715-75G             | [753b419047](https://linux-hardware.org/?probe=753b419047) | Dec 30, 2023 |
| HP            | Pavilion 15                 | [50b4c1504f](https://linux-hardware.org/?probe=50b4c1504f) | Dec 29, 2023 |
| HP            | Laptop 15-dy2xxx            | [c10327a38f](https://linux-hardware.org/?probe=c10327a38f) | Dec 29, 2023 |
| Monster       | ABRA A5 V13.4               | [274f6e86fc](https://linux-hardware.org/?probe=274f6e86fc) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [61c1444cfc](https://linux-hardware.org/?probe=61c1444cfc) | Dec 29, 2023 |
| Chuwi         | HeroBook Pro                | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [5cfb3467bc](https://linux-hardware.org/?probe=5cfb3467bc) | Dec 29, 2023 |
| Acer          | Aspire A115-31              | [01aeb12545](https://linux-hardware.org/?probe=01aeb12545) | Dec 29, 2023 |
| Valve         | Jupiter                     | [0254493ea3](https://linux-hardware.org/?probe=0254493ea3) | Dec 29, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [76f94ce16a](https://linux-hardware.org/?probe=76f94ce16a) | Dec 29, 2023 |
| Lenovo        | ThinkPad X280 20KF0025US    | [5766ed7c57](https://linux-hardware.org/?probe=5766ed7c57) | Dec 29, 2023 |
| Acer          | Aspire A515-54G             | [35e2f8c10c](https://linux-hardware.org/?probe=35e2f8c10c) | Dec 29, 2023 |
| Dell          | Inspiron 3482               | [bbcb062420](https://linux-hardware.org/?probe=bbcb062420) | Dec 29, 2023 |
| Dell          | Latitude 5580               | [3079edcb81](https://linux-hardware.org/?probe=3079edcb81) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480 20L6SE6900    | [f9e5fe1156](https://linux-hardware.org/?probe=f9e5fe1156) | Dec 29, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [75516d0dbc](https://linux-hardware.org/?probe=75516d0dbc) | Dec 29, 2023 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [a55f917cf6](https://linux-hardware.org/?probe=a55f917cf6) | Dec 29, 2023 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [402a1c70b8](https://linux-hardware.org/?probe=402a1c70b8) | Dec 29, 2023 |
| HP            | EliteBook 8560w             | [c7e5dc5d9b](https://linux-hardware.org/?probe=c7e5dc5d9b) | Dec 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [afd9883450](https://linux-hardware.org/?probe=afd9883450) | Dec 29, 2023 |
| HP            | EliteBook 8560w             | [e3ecbaedf9](https://linux-hardware.org/?probe=e3ecbaedf9) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fa90555a](https://linux-hardware.org/?probe=e0fa90555a) | Dec 29, 2023 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | [13e876e5cf](https://linux-hardware.org/?probe=13e876e5cf) | Dec 29, 2023 |
| LG Electro... | P420-N.AE21G                | [3fdf04ae52](https://linux-hardware.org/?probe=3fdf04ae52) | Dec 29, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [63794eecd3](https://linux-hardware.org/?probe=63794eecd3) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [988bd71a05](https://linux-hardware.org/?probe=988bd71a05) | Dec 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [55340871af](https://linux-hardware.org/?probe=55340871af) | Dec 29, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [01c6121d4c](https://linux-hardware.org/?probe=01c6121d4c) | Dec 29, 2023 |
| Acer          | Aspire A315-24P             | [64dddef2fa](https://linux-hardware.org/?probe=64dddef2fa) | Dec 29, 2023 |
| Dell          | Latitude E7450              | [0d3dc05a2d](https://linux-hardware.org/?probe=0d3dc05a2d) | Dec 29, 2023 |
| HP            | Victus by Gaming Laptop ... | [d82dad2793](https://linux-hardware.org/?probe=d82dad2793) | Dec 29, 2023 |
| Lenovo        | ThinkPad T410 2537BY8       | [0117a0ab48](https://linux-hardware.org/?probe=0117a0ab48) | Dec 29, 2023 |
| HP            | Pavilion dv5                | [f347184b5c](https://linux-hardware.org/?probe=f347184b5c) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [03199adbd4](https://linux-hardware.org/?probe=03199adbd4) | Dec 29, 2023 |
| Dell          | Inspiron 3593               | [dc67ac3e38](https://linux-hardware.org/?probe=dc67ac3e38) | Dec 29, 2023 |
| Apple         | MacBookPro5,2               | [b6269d662d](https://linux-hardware.org/?probe=b6269d662d) | Dec 29, 2023 |
| Lenovo        | G50-80 80E5                 | [0e612ffdf7](https://linux-hardware.org/?probe=0e612ffdf7) | Dec 29, 2023 |
| Dell          | Latitude 5480               | [ddcc69c02c](https://linux-hardware.org/?probe=ddcc69c02c) | Dec 29, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [fe64fba0a5](https://linux-hardware.org/?probe=fe64fba0a5) | Dec 29, 2023 |
| HP            | Laptop 17t-cn200            | [4c241f7e1d](https://linux-hardware.org/?probe=4c241f7e1d) | Dec 29, 2023 |
| ASUSTek       | K72JT                       | [51117cd448](https://linux-hardware.org/?probe=51117cd448) | Dec 29, 2023 |
| Dell          | Precision 5560              | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Razer         | Blade                       | [87f8a27b0a](https://linux-hardware.org/?probe=87f8a27b0a) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [d11d965739](https://linux-hardware.org/?probe=d11d965739) | Dec 29, 2023 |
| Dell          | Latitude E6220              | [c106ee001b](https://linux-hardware.org/?probe=c106ee001b) | Dec 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [55a9c00e34](https://linux-hardware.org/?probe=55a9c00e34) | Dec 29, 2023 |
| Dell          | Vostro 3405                 | [e527034e74](https://linux-hardware.org/?probe=e527034e74) | Dec 29, 2023 |
| Sony          | VGN-CR21S_W                 | [732175d0f6](https://linux-hardware.org/?probe=732175d0f6) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | [c7383a1237](https://linux-hardware.org/?probe=c7383a1237) | Dec 29, 2023 |
| Dell          | Vostro 3405                 | [aee31d728f](https://linux-hardware.org/?probe=aee31d728f) | Dec 29, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [d2c1896794](https://linux-hardware.org/?probe=d2c1896794) | Dec 29, 2023 |
| ASUSTek       | K54HR                       | [ce4e5d4a5b](https://linux-hardware.org/?probe=ce4e5d4a5b) | Dec 29, 2023 |
| Dell          | XPS 15 9560                 | [aabd2af674](https://linux-hardware.org/?probe=aabd2af674) | Dec 29, 2023 |
| HP            | ProBook 650 G1              | [cc8196ebec](https://linux-hardware.org/?probe=cc8196ebec) | Dec 29, 2023 |
| Sony          | VGN-FW21E                   | [52ff803e03](https://linux-hardware.org/?probe=52ff803e03) | Dec 29, 2023 |
| Apple         | MacBookPro14,3              | [83399f5e60](https://linux-hardware.org/?probe=83399f5e60) | Dec 29, 2023 |
| Toshiba       | Satellite C50D-A-138        | [cfb74314e2](https://linux-hardware.org/?probe=cfb74314e2) | Dec 29, 2023 |
| ASUSTek       | K53SV                       | [c285275ef1](https://linux-hardware.org/?probe=c285275ef1) | Dec 29, 2023 |
| Acer          | SF314-71-50E8               | [a2704f17ea](https://linux-hardware.org/?probe=a2704f17ea) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | [50589e94ba](https://linux-hardware.org/?probe=50589e94ba) | Dec 29, 2023 |
| ASUSTek       | K53BE                       | [23efadbf2f](https://linux-hardware.org/?probe=23efadbf2f) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [99561c9ed3](https://linux-hardware.org/?probe=99561c9ed3) | Dec 29, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [13e6674db0](https://linux-hardware.org/?probe=13e6674db0) | Dec 29, 2023 |
| HP            | ProBook 655 G2              | [71ef8433cc](https://linux-hardware.org/?probe=71ef8433cc) | Dec 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | [f37cd9143d](https://linux-hardware.org/?probe=f37cd9143d) | Dec 29, 2023 |
| Dell          | Inspiron 3443               | [0c56a0465b](https://linux-hardware.org/?probe=0c56a0465b) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [791788fbbc](https://linux-hardware.org/?probe=791788fbbc) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9e856c326a](https://linux-hardware.org/?probe=9e856c326a) | Dec 29, 2023 |
| ASUSTek       | K54LY                       | [d2e504447e](https://linux-hardware.org/?probe=d2e504447e) | Dec 29, 2023 |
| Toshiba       | Satellite P70-B             | [2a5acedd16](https://linux-hardware.org/?probe=2a5acedd16) | Dec 29, 2023 |
| Acer          | Aspire A515-44              | [b063fdc8bf](https://linux-hardware.org/?probe=b063fdc8bf) | Dec 29, 2023 |
| HP            | 250 G1                      | [c0c195904c](https://linux-hardware.org/?probe=c0c195904c) | Dec 29, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [53fc03e451](https://linux-hardware.org/?probe=53fc03e451) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3b6d015d5a](https://linux-hardware.org/?probe=3b6d015d5a) | Dec 29, 2023 |
| MSI           | GP75 Leopard 9SE            | [29e0740b9d](https://linux-hardware.org/?probe=29e0740b9d) | Dec 29, 2023 |
| Lenovo        | ThinkPad T450 20BUS2VK00    | [15de64acfb](https://linux-hardware.org/?probe=15de64acfb) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [36856f5ac1](https://linux-hardware.org/?probe=36856f5ac1) | Dec 29, 2023 |
| Acer          | Aspire E5-573G              | [0c4a68d81f](https://linux-hardware.org/?probe=0c4a68d81f) | Dec 29, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [fb4b958ae6](https://linux-hardware.org/?probe=fb4b958ae6) | Dec 29, 2023 |
| Toshiba       | Satellite L655              | [c7e2a4aa7c](https://linux-hardware.org/?probe=c7e2a4aa7c) | Dec 29, 2023 |
| Lenovo        | B560                        | [1f8cf50933](https://linux-hardware.org/?probe=1f8cf50933) | Dec 29, 2023 |
| Lenovo        | Yoga 2 11 20332             | [04bb236111](https://linux-hardware.org/?probe=04bb236111) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [4861953728](https://linux-hardware.org/?probe=4861953728) | Dec 29, 2023 |
| Acer          | Aspire A715-76G             | [e25984fb5e](https://linux-hardware.org/?probe=e25984fb5e) | Dec 29, 2023 |
| Acer          | Aspire E5-573G              | [210403cf9d](https://linux-hardware.org/?probe=210403cf9d) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [650d02f634](https://linux-hardware.org/?probe=650d02f634) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [0a2d1d5688](https://linux-hardware.org/?probe=0a2d1d5688) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | [ab4628dffe](https://linux-hardware.org/?probe=ab4628dffe) | Dec 29, 2023 |
| Dell          | Inspiron 3584               | [818e96295f](https://linux-hardware.org/?probe=818e96295f) | Dec 29, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [3d0513bb6c](https://linux-hardware.org/?probe=3d0513bb6c) | Dec 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [bb3e77da36](https://linux-hardware.org/?probe=bb3e77da36) | Dec 29, 2023 |
| Alienware     | x17 R2                      | [b439c4c2a9](https://linux-hardware.org/?probe=b439c4c2a9) | Dec 29, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [690962312c](https://linux-hardware.org/?probe=690962312c) | Dec 29, 2023 |
| Lenovo        | XiaoXinPro 16 IRH8 83AQ     | [e21e415784](https://linux-hardware.org/?probe=e21e415784) | Dec 29, 2023 |
| Dell          | XPS 13 9380                 | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| Acer          | Aspire SW5-012              | [4efea61fa3](https://linux-hardware.org/?probe=4efea61fa3) | Dec 29, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [a4d9a001ff](https://linux-hardware.org/?probe=a4d9a001ff) | Dec 29, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [751429a259](https://linux-hardware.org/?probe=751429a259) | Dec 29, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [f3af16ad5d](https://linux-hardware.org/?probe=f3af16ad5d) | Dec 29, 2023 |
| HUAWEI        | BOD-WXX9                    | [fdcf9374ad](https://linux-hardware.org/?probe=fdcf9374ad) | Dec 29, 2023 |
| Dell          | Inspiron 7348               | [a55c6eef41](https://linux-hardware.org/?probe=a55c6eef41) | Dec 29, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [8e46844acc](https://linux-hardware.org/?probe=8e46844acc) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| HONOR         | NMH-WDX9                    | [a632604865](https://linux-hardware.org/?probe=a632604865) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4ba914628d](https://linux-hardware.org/?probe=4ba914628d) | Dec 29, 2023 |
| Star Labs     | StarBook                    | [930fb359dd](https://linux-hardware.org/?probe=930fb359dd) | Dec 29, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [bbe4e7af60](https://linux-hardware.org/?probe=bbe4e7af60) | Dec 29, 2023 |
| HP            | Laptop 15-da0xxx            | [03ad95c394](https://linux-hardware.org/?probe=03ad95c394) | Dec 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [42c812d36d](https://linux-hardware.org/?probe=42c812d36d) | Dec 29, 2023 |
| HP            | Laptop 15-da0xxx            | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6c5599855c](https://linux-hardware.org/?probe=6c5599855c) | Dec 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [d5ac5fcf72](https://linux-hardware.org/?probe=d5ac5fcf72) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0060... | [485c94e992](https://linux-hardware.org/?probe=485c94e992) | Dec 29, 2023 |
| Unknown       | M17                         | [3d6789f805](https://linux-hardware.org/?probe=3d6789f805) | Dec 29, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a353b43ac0](https://linux-hardware.org/?probe=a353b43ac0) | Dec 29, 2023 |
| Chuwi         | GemiBook Plus               | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| ASUSTek       | Vivobook Go E1504GAB_E15... | [6fa8529cff](https://linux-hardware.org/?probe=6fa8529cff) | Dec 29, 2023 |
| Timi          | A34R                        | [d72018ec19](https://linux-hardware.org/?probe=d72018ec19) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c0a8fdcf6f](https://linux-hardware.org/?probe=c0a8fdcf6f) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Dell          | Latitude 5424 Rugged        | [1339f0b553](https://linux-hardware.org/?probe=1339f0b553) | Dec 29, 2023 |
| Lenovo        | 3000 N500 42333GS           | [523a81b813](https://linux-hardware.org/?probe=523a81b813) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6a99e4eda2](https://linux-hardware.org/?probe=6a99e4eda2) | Dec 29, 2023 |
| MSI           | MS-168B                     | [cd9dc4eadd](https://linux-hardware.org/?probe=cd9dc4eadd) | Dec 29, 2023 |
| Apple         | MacBookAir4,2               | [9a7ee6f89e](https://linux-hardware.org/?probe=9a7ee6f89e) | Dec 29, 2023 |
| Dell          | Latitude 7300               | [926a273123](https://linux-hardware.org/?probe=926a273123) | Dec 29, 2023 |
| Acer          | Aspire 4736Z                | [ea8dffb40f](https://linux-hardware.org/?probe=ea8dffb40f) | Dec 29, 2023 |
| Dell          | Precision M6400             | [7ea3fcf3ed](https://linux-hardware.org/?probe=7ea3fcf3ed) | Dec 29, 2023 |
| Dell          | Latitude 7300               | [ac9c0099fd](https://linux-hardware.org/?probe=ac9c0099fd) | Dec 29, 2023 |
| HP            | Pavilion dv6                | [9992f9523e](https://linux-hardware.org/?probe=9992f9523e) | Dec 29, 2023 |
| Lenovo        | ThinkPad T450 20BUS05V00    | [3334aeb4e1](https://linux-hardware.org/?probe=3334aeb4e1) | Dec 29, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | [09f37233e4](https://linux-hardware.org/?probe=09f37233e4) | Dec 29, 2023 |
| HUAWEI        | BOD-WXX9                    | [eee070b636](https://linux-hardware.org/?probe=eee070b636) | Dec 29, 2023 |
| Dell          | Inspiron 5759               | [9586fa7d24](https://linux-hardware.org/?probe=9586fa7d24) | Dec 29, 2023 |
| HP            | ZBook 14 G2                 | [0d092c7ece](https://linux-hardware.org/?probe=0d092c7ece) | Dec 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [0be6e9ce52](https://linux-hardware.org/?probe=0be6e9ce52) | Dec 29, 2023 |
| Samsung       | RC530/RC730                 | [db448e5732](https://linux-hardware.org/?probe=db448e5732) | Dec 29, 2023 |
| HP            | Compaq Presario A900        | [e22eed28b4](https://linux-hardware.org/?probe=e22eed28b4) | Dec 29, 2023 |
| Acer          | Aspire F5-571               | [d28fac242c](https://linux-hardware.org/?probe=d28fac242c) | Dec 29, 2023 |
| HP            | ProBook 650 G2              | [1dd3970627](https://linux-hardware.org/?probe=1dd3970627) | Dec 29, 2023 |
| Monster       | TULPAR T5 V23.2             | [9592c22858](https://linux-hardware.org/?probe=9592c22858) | Dec 29, 2023 |
| ASUSTek       | G750JS                      | [1164f5c600](https://linux-hardware.org/?probe=1164f5c600) | Dec 29, 2023 |
| Lenovo        | ThinkPad L590 20Q8S0QB00    | [21c14a621b](https://linux-hardware.org/?probe=21c14a621b) | Dec 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [6de199d009](https://linux-hardware.org/?probe=6de199d009) | Dec 29, 2023 |
| Notebook      | NS5x_NS7xAU                 | [d520b97118](https://linux-hardware.org/?probe=d520b97118) | Dec 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [13ba865757](https://linux-hardware.org/?probe=13ba865757) | Dec 29, 2023 |
| HP            | EliteBook 2570p             | [935d08358c](https://linux-hardware.org/?probe=935d08358c) | Dec 29, 2023 |
| Dell          | Inspiron 5558               | [be6a80140f](https://linux-hardware.org/?probe=be6a80140f) | Dec 29, 2023 |
| Dell          | XPS 13 9370                 | [f2d5cce82a](https://linux-hardware.org/?probe=f2d5cce82a) | Dec 29, 2023 |
| Dell          | Inspiron 3542               | [06e3a35d05](https://linux-hardware.org/?probe=06e3a35d05) | Dec 29, 2023 |
| Lenovo        | Unknown                     | [71b939033d](https://linux-hardware.org/?probe=71b939033d) | Dec 28, 2023 |
| eMachines     | E725                        | [b3be8d374c](https://linux-hardware.org/?probe=b3be8d374c) | Dec 28, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [92c8c4f42c](https://linux-hardware.org/?probe=92c8c4f42c) | Dec 28, 2023 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [be86cafd2e](https://linux-hardware.org/?probe=be86cafd2e) | Dec 28, 2023 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [c2d6079fe7](https://linux-hardware.org/?probe=c2d6079fe7) | Dec 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [990d141701](https://linux-hardware.org/?probe=990d141701) | Dec 28, 2023 |
| Lenovo        | G700 20251                  | [3426bbc85d](https://linux-hardware.org/?probe=3426bbc85d) | Dec 28, 2023 |
| TUXEDO        | Polaris AMD Gen5            | [46ad5a6b29](https://linux-hardware.org/?probe=46ad5a6b29) | Dec 28, 2023 |
| Lenovo        | G700 20251                  | [78b29bb9e8](https://linux-hardware.org/?probe=78b29bb9e8) | Dec 28, 2023 |
| Lenovo        | V145-15AST 81MT             | [fa95062029](https://linux-hardware.org/?probe=fa95062029) | Dec 28, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [fd565ed585](https://linux-hardware.org/?probe=fd565ed585) | Dec 28, 2023 |
| Valve         | Galileo                     | [83bfa965fb](https://linux-hardware.org/?probe=83bfa965fb) | Dec 28, 2023 |
| Lenovo        | ThinkPad T440 20B7A0B7MN    | [e456132635](https://linux-hardware.org/?probe=e456132635) | Dec 28, 2023 |
| HUAWEI        | CREFG-XX                    | [91cc2daf14](https://linux-hardware.org/?probe=91cc2daf14) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [4e1a45dee6](https://linux-hardware.org/?probe=4e1a45dee6) | Dec 28, 2023 |
| Dell          | Vostro 15 5510              | [02df63af48](https://linux-hardware.org/?probe=02df63af48) | Dec 28, 2023 |
| Dell          | Latitude E7450              | [50b3989c19](https://linux-hardware.org/?probe=50b3989c19) | Dec 28, 2023 |
| HP            | OMEN by Laptop              | [71d20fd45b](https://linux-hardware.org/?probe=71d20fd45b) | Dec 28, 2023 |
| Lenovo        | V145-15AST 81MT             | [493e09fce5](https://linux-hardware.org/?probe=493e09fce5) | Dec 28, 2023 |
| Lenovo        | G500 20236                  | [62aa46f354](https://linux-hardware.org/?probe=62aa46f354) | Dec 28, 2023 |
| HP            | EliteBook 840 G4            | [412a23e374](https://linux-hardware.org/?probe=412a23e374) | Dec 28, 2023 |
| Qilive        | QW20141BSP                  | [3f2d1e03c3](https://linux-hardware.org/?probe=3f2d1e03c3) | Dec 28, 2023 |
| ASUSTek       | G73Jh                       | [05dc836501](https://linux-hardware.org/?probe=05dc836501) | Dec 28, 2023 |
| HP            | Pavilion 15                 | [da5644171f](https://linux-hardware.org/?probe=da5644171f) | Dec 28, 2023 |
| MSI           | GS70 2OD                    | [13dab050a1](https://linux-hardware.org/?probe=13dab050a1) | Dec 28, 2023 |
| Lenovo        | ThinkPad T420 4180ED3       | [0c9cecfac4](https://linux-hardware.org/?probe=0c9cecfac4) | Dec 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [a86830ecd2](https://linux-hardware.org/?probe=a86830ecd2) | Dec 28, 2023 |
| MSI           | GS70 2OD                    | [7092678d3b](https://linux-hardware.org/?probe=7092678d3b) | Dec 28, 2023 |
| COIN COMPU... | LUM580                      | [6a8246b500](https://linux-hardware.org/?probe=6a8246b500) | Dec 28, 2023 |
| MACHENIKE     | T58-V                       | [bbcdf32afc](https://linux-hardware.org/?probe=bbcdf32afc) | Dec 28, 2023 |
| Acer          | Nitro AN515-54              | [b310676172](https://linux-hardware.org/?probe=b310676172) | Dec 28, 2023 |
| HP            | 2000                        | [eac2251c15](https://linux-hardware.org/?probe=eac2251c15) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [d6477c7999](https://linux-hardware.org/?probe=d6477c7999) | Dec 28, 2023 |
| HP            | Pavilion Power Laptop 15... | [5bd82e2331](https://linux-hardware.org/?probe=5bd82e2331) | Dec 28, 2023 |
| Unknown       | Unknown                     | [89a77455e5](https://linux-hardware.org/?probe=89a77455e5) | Dec 28, 2023 |
| ASUSTek       | K54HR                       | [dca5908bc4](https://linux-hardware.org/?probe=dca5908bc4) | Dec 28, 2023 |
| HP            | EliteBook Folio 9480m       | [45adbe7c2a](https://linux-hardware.org/?probe=45adbe7c2a) | Dec 28, 2023 |
| Notebook      | NL40_50CU                   | [a91c55ef9f](https://linux-hardware.org/?probe=a91c55ef9f) | Dec 28, 2023 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [e0bfd9face](https://linux-hardware.org/?probe=e0bfd9face) | Dec 28, 2023 |
| Chuwi         | GemiBook                    | [15199d7550](https://linux-hardware.org/?probe=15199d7550) | Dec 28, 2023 |
| Acer          | Aspire E5-553G              | [a21fc70e01](https://linux-hardware.org/?probe=a21fc70e01) | Dec 28, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [2e6989112a](https://linux-hardware.org/?probe=2e6989112a) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [76b6ceb6cf](https://linux-hardware.org/?probe=76b6ceb6cf) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | [b3691ac681](https://linux-hardware.org/?probe=b3691ac681) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [32b6e45042](https://linux-hardware.org/?probe=32b6e45042) | Dec 28, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [324bfb9f22](https://linux-hardware.org/?probe=324bfb9f22) | Dec 28, 2023 |
| BAKED         | P65xRP                      | [4bd66fa9db](https://linux-hardware.org/?probe=4bd66fa9db) | Dec 28, 2023 |
| Dell          | Latitude 7490               | [7eab9f671e](https://linux-hardware.org/?probe=7eab9f671e) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | [16a5247446](https://linux-hardware.org/?probe=16a5247446) | Dec 28, 2023 |
| Lenovo        | ThinkPad L390 20NSS29K00    | [a0860fbefb](https://linux-hardware.org/?probe=a0860fbefb) | Dec 28, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | [ddca4cca74](https://linux-hardware.org/?probe=ddca4cca74) | Dec 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5b2dd63a52](https://linux-hardware.org/?probe=5b2dd63a52) | Dec 28, 2023 |
| Fujitsu       | LIFEBOOK E734               | [2265b1d34f](https://linux-hardware.org/?probe=2265b1d34f) | Dec 28, 2023 |
| HP            | Laptop 15-dw1xxx            | [86c11fc47f](https://linux-hardware.org/?probe=86c11fc47f) | Dec 28, 2023 |
| HP            | EliteBook 830 G5            | [c9ac7b8022](https://linux-hardware.org/?probe=c9ac7b8022) | Dec 28, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [5d86cb3268](https://linux-hardware.org/?probe=5d86cb3268) | Dec 28, 2023 |
| Positivo      | Harrison                    | [e12b67378a](https://linux-hardware.org/?probe=e12b67378a) | Dec 28, 2023 |
| HP            | ZBook 14u G6                | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Medion        | E11202                      | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| LG Electro... | S510-X.CBCKG                | [41f03f323d](https://linux-hardware.org/?probe=41f03f323d) | Dec 28, 2023 |
| HP            | OMEN Laptop 15-ek1xxx       | [16c7cb0337](https://linux-hardware.org/?probe=16c7cb0337) | Dec 28, 2023 |
| LG Electro... | S510-X.CBCKG                | [1348f972c2](https://linux-hardware.org/?probe=1348f972c2) | Dec 28, 2023 |
| HP            | ZBook 15                    | [92d7e45b22](https://linux-hardware.org/?probe=92d7e45b22) | Dec 28, 2023 |
| Unknown       | Unknown                     | [7c86c2f5dc](https://linux-hardware.org/?probe=7c86c2f5dc) | Dec 28, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [08fc99186e](https://linux-hardware.org/?probe=08fc99186e) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | [82f94ea967](https://linux-hardware.org/?probe=82f94ea967) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | [bbce6fb229](https://linux-hardware.org/?probe=bbce6fb229) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | [ecd05eabd6](https://linux-hardware.org/?probe=ecd05eabd6) | Dec 28, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a7878eaed](https://linux-hardware.org/?probe=2a7878eaed) | Dec 28, 2023 |
| HUAWEI        | BOD-WXX9                    | [7d74ad36fd](https://linux-hardware.org/?probe=7d74ad36fd) | Dec 28, 2023 |
| Acer          | Aspire 8730                 | [3110584890](https://linux-hardware.org/?probe=3110584890) | Dec 28, 2023 |
| Medion        | E7220                       | [8a10d2f8d1](https://linux-hardware.org/?probe=8a10d2f8d1) | Dec 28, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [88fe73b44c](https://linux-hardware.org/?probe=88fe73b44c) | Dec 28, 2023 |
| Acer          | Aspire 8730                 | [3a9461e870](https://linux-hardware.org/?probe=3a9461e870) | Dec 28, 2023 |
| Google        | Nami                        | [3d7f7ba09c](https://linux-hardware.org/?probe=3d7f7ba09c) | Dec 28, 2023 |
| Packard Be... | EasyNote TN36               | [2b83138160](https://linux-hardware.org/?probe=2b83138160) | Dec 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [a135119148](https://linux-hardware.org/?probe=a135119148) | Dec 28, 2023 |
| HP            | ENVY Laptop 13-aq1xxx       | [44df1c7cc6](https://linux-hardware.org/?probe=44df1c7cc6) | Dec 28, 2023 |
| Fujitsu       | LIFEBOOK T902               | [050f6ca09e](https://linux-hardware.org/?probe=050f6ca09e) | Dec 28, 2023 |
| Apple         | MacBookPro8,3               | [e47426bf12](https://linux-hardware.org/?probe=e47426bf12) | Dec 28, 2023 |
| HP            | EliteBook 840 G3            | [ce26af0483](https://linux-hardware.org/?probe=ce26af0483) | Dec 28, 2023 |
| Clevo         | NL41MU2                     | [51d90b2126](https://linux-hardware.org/?probe=51d90b2126) | Dec 28, 2023 |
| Apple         | MacBookPro9,2               | [b73abb7ffa](https://linux-hardware.org/?probe=b73abb7ffa) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | [0f8be1187e](https://linux-hardware.org/?probe=0f8be1187e) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS0N200    | [e94a7fb094](https://linux-hardware.org/?probe=e94a7fb094) | Dec 28, 2023 |
| Acer          | Swift SF314-56              | [d230832e06](https://linux-hardware.org/?probe=d230832e06) | Dec 28, 2023 |
| Dell          | Latitude 5510               | [ebe9c1f033](https://linux-hardware.org/?probe=ebe9c1f033) | Dec 28, 2023 |
| Lenovo        | ThinkPad L540 20AV0031FR    | [96e1e4403d](https://linux-hardware.org/?probe=96e1e4403d) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [98b0838eb2](https://linux-hardware.org/?probe=98b0838eb2) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2325V2Y       | [4eb0a16723](https://linux-hardware.org/?probe=4eb0a16723) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cc024fb567](https://linux-hardware.org/?probe=cc024fb567) | Dec 28, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0J60... | [0f46c7112d](https://linux-hardware.org/?probe=0f46c7112d) | Dec 28, 2023 |
| MSI           | GT60 2OC/2OD                | [d0a3fb037a](https://linux-hardware.org/?probe=d0a3fb037a) | Dec 28, 2023 |
| HP            | EliteBook 840 G2            | [6ba5504a6f](https://linux-hardware.org/?probe=6ba5504a6f) | Dec 28, 2023 |
| Lenovo        | ThinkPad L520 5017AD1       | [93cc8d014a](https://linux-hardware.org/?probe=93cc8d014a) | Dec 28, 2023 |
| Google        | Dratini                     | [a81971bf37](https://linux-hardware.org/?probe=a81971bf37) | Dec 28, 2023 |
| ASUSTek       | UL80VT                      | [d9e57db214](https://linux-hardware.org/?probe=d9e57db214) | Dec 28, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [6abb72e809](https://linux-hardware.org/?probe=6abb72e809) | Dec 28, 2023 |
| ASUSTek       | UL80VT                      | [8532e3dcca](https://linux-hardware.org/?probe=8532e3dcca) | Dec 28, 2023 |
| Acer          | Aspire V5-123               | [4220993372](https://linux-hardware.org/?probe=4220993372) | Dec 28, 2023 |
| Gateway       | MX3235m                     | [074b414446](https://linux-hardware.org/?probe=074b414446) | Dec 28, 2023 |
| Google        | Lillipup                    | [e8ac3dc206](https://linux-hardware.org/?probe=e8ac3dc206) | Dec 28, 2023 |
| Gateway       | MX3235m                     | [283075fa43](https://linux-hardware.org/?probe=283075fa43) | Dec 28, 2023 |
| Toshiba       | Satellite A200              | [081782c544](https://linux-hardware.org/?probe=081782c544) | Dec 28, 2023 |
| TrekStor      | Notebook Slim S130          | [9fbe38b102](https://linux-hardware.org/?probe=9fbe38b102) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a5c652bcef](https://linux-hardware.org/?probe=a5c652bcef) | Dec 28, 2023 |
| Apple         | MacBookAir5,2               | [14b41c4c72](https://linux-hardware.org/?probe=14b41c4c72) | Dec 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [02799d9fc9](https://linux-hardware.org/?probe=02799d9fc9) | Dec 28, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [8250429628](https://linux-hardware.org/?probe=8250429628) | Dec 28, 2023 |
| HP            | ProBook 6470b               | [60858223c4](https://linux-hardware.org/?probe=60858223c4) | Dec 28, 2023 |
| Dell          | Inspiron 3593               | [27f6eb03d0](https://linux-hardware.org/?probe=27f6eb03d0) | Dec 28, 2023 |
| Lenovo        | G70-70 80HW                 | [3b6b661f7d](https://linux-hardware.org/?probe=3b6b661f7d) | Dec 28, 2023 |
| ASUSTek       | G750JX                      | [2b867b6af5](https://linux-hardware.org/?probe=2b867b6af5) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [0c55b9f3e3](https://linux-hardware.org/?probe=0c55b9f3e3) | Dec 28, 2023 |
| Acer          | Aspire A315-41              | [1042d42263](https://linux-hardware.org/?probe=1042d42263) | Dec 28, 2023 |
| HP            | EliteBook 820 G3            | [42985f8c13](https://linux-hardware.org/?probe=42985f8c13) | Dec 28, 2023 |
| Dell          | Inspiron 7720               | [965fc7c4a3](https://linux-hardware.org/?probe=965fc7c4a3) | Dec 28, 2023 |
| Acer          | Aspire A315-41              | [d68aa800c6](https://linux-hardware.org/?probe=d68aa800c6) | Dec 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [9c498442e0](https://linux-hardware.org/?probe=9c498442e0) | Dec 28, 2023 |
| GPU Compan... | GWTN141-10                  | [6e74e1b943](https://linux-hardware.org/?probe=6e74e1b943) | Dec 28, 2023 |
| ASUSTek       | X555LB                      | [f29fe264f5](https://linux-hardware.org/?probe=f29fe264f5) | Dec 28, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | [87b76140e0](https://linux-hardware.org/?probe=87b76140e0) | Dec 28, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [424a79de6b](https://linux-hardware.org/?probe=424a79de6b) | Dec 28, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [3a0b2d2a21](https://linux-hardware.org/?probe=3a0b2d2a21) | Dec 28, 2023 |
| Apple         | MacBookPro15,4              | [1d368b7c25](https://linux-hardware.org/?probe=1d368b7c25) | Dec 28, 2023 |
| Razer         | Blade                       | [bd2101718d](https://linux-hardware.org/?probe=bd2101718d) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a1652ba789](https://linux-hardware.org/?probe=a1652ba789) | Dec 28, 2023 |
| HP            | ProBook 455 G1              | [d132700b11](https://linux-hardware.org/?probe=d132700b11) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| HP            | 250 G8 Notebook PC          | [255c0c95bc](https://linux-hardware.org/?probe=255c0c95bc) | Dec 28, 2023 |
| AWOW          | AK41                        | [d081509ed9](https://linux-hardware.org/?probe=d081509ed9) | Dec 28, 2023 |
| Dell          | Latitude 3380               | [4f9660f132](https://linux-hardware.org/?probe=4f9660f132) | Dec 28, 2023 |
| Dell          | Vostro 5470                 | [25e05316e9](https://linux-hardware.org/?probe=25e05316e9) | Dec 28, 2023 |
| HP            | Pavilion dv7                | [4b1ea284d3](https://linux-hardware.org/?probe=4b1ea284d3) | Dec 28, 2023 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [9197fe40a7](https://linux-hardware.org/?probe=9197fe40a7) | Dec 28, 2023 |
| HP            | Notebook                    | [5b3e4ada9c](https://linux-hardware.org/?probe=5b3e4ada9c) | Dec 28, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [da8a8d5994](https://linux-hardware.org/?probe=da8a8d5994) | Dec 28, 2023 |
| ASUSTek       | X750JB                      | [3c2f9bd15e](https://linux-hardware.org/?probe=3c2f9bd15e) | Dec 28, 2023 |
| Dell          | Latitude 3380               | [bb1422b9bd](https://linux-hardware.org/?probe=bb1422b9bd) | Dec 28, 2023 |
| win elemen... | MoreFine S500+              | [6880205d9e](https://linux-hardware.org/?probe=6880205d9e) | Dec 28, 2023 |
| HP            | ProBook 11 G2               | [3ad144c68e](https://linux-hardware.org/?probe=3ad144c68e) | Dec 28, 2023 |
| Acer          | Nitro AN515-51              | [f61d16f126](https://linux-hardware.org/?probe=f61d16f126) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [09d63b8472](https://linux-hardware.org/?probe=09d63b8472) | Dec 28, 2023 |
| Purism        | Librem 14                   | [215d922345](https://linux-hardware.org/?probe=215d922345) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [341b25443b](https://linux-hardware.org/?probe=341b25443b) | Dec 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a5b16ddafb](https://linux-hardware.org/?probe=a5b16ddafb) | Dec 28, 2023 |
| Valve         | Galileo                     | [ae65838bd7](https://linux-hardware.org/?probe=ae65838bd7) | Dec 28, 2023 |
| Dell          | Vostro 2420                 | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| Dell          | Latitude E7470              | [3bbb66a28f](https://linux-hardware.org/?probe=3bbb66a28f) | Dec 28, 2023 |
| HP            | Laptop 17-cp0xxx            | [4118aee355](https://linux-hardware.org/?probe=4118aee355) | Dec 28, 2023 |
| Lenovo        | ThinkPad T560 20FH002GUS    | [76926807cc](https://linux-hardware.org/?probe=76926807cc) | Dec 28, 2023 |
| Acer          | TravelMate P215-52          | [4191cc3d32](https://linux-hardware.org/?probe=4191cc3d32) | Dec 28, 2023 |
| Apple         | MacBookPro8,2               | [a353ad122c](https://linux-hardware.org/?probe=a353ad122c) | Dec 28, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [52a99e896e](https://linux-hardware.org/?probe=52a99e896e) | Dec 28, 2023 |
| Lenovo        | ThinkPad T560 20FH002GUS    | [cf5b823135](https://linux-hardware.org/?probe=cf5b823135) | Dec 28, 2023 |
| ASUSTek       | K73SV                       | [2a36715319](https://linux-hardware.org/?probe=2a36715319) | Dec 28, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [274273301c](https://linux-hardware.org/?probe=274273301c) | Dec 28, 2023 |
| MSI           | GF65 Thin 10SDR             | [18a746317d](https://linux-hardware.org/?probe=18a746317d) | Dec 28, 2023 |
| HUAWEI        | BOD-WXX9                    | [d8e2dd481d](https://linux-hardware.org/?probe=d8e2dd481d) | Dec 28, 2023 |
| Apple         | MacBookPro5,5               | [609aece6c1](https://linux-hardware.org/?probe=609aece6c1) | Dec 28, 2023 |
| Acer          | Aspire E5-573G              | [323f661113](https://linux-hardware.org/?probe=323f661113) | Dec 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [6be155ee0d](https://linux-hardware.org/?probe=6be155ee0d) | Dec 27, 2023 |
| eMachines     | E725                        | [1b90f2bf06](https://linux-hardware.org/?probe=1b90f2bf06) | Dec 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [313a669de8](https://linux-hardware.org/?probe=313a669de8) | Dec 27, 2023 |
| MSI           | Pulse GL66 12UEK            | [4600a758fa](https://linux-hardware.org/?probe=4600a758fa) | Dec 27, 2023 |
| Acer          | Aspire E1-570               | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| Packard Be... | EasyNote MH35               | [2b8b39d335](https://linux-hardware.org/?probe=2b8b39d335) | Dec 27, 2023 |
| HP            | Pavilion dv6                | [39515c70db](https://linux-hardware.org/?probe=39515c70db) | Dec 27, 2023 |
| ASUSTek       | K75VM                       | [4f1fddffba](https://linux-hardware.org/?probe=4f1fddffba) | Dec 27, 2023 |
| Panasonic     | FZ-M1CCA17E3                | [c55632d60a](https://linux-hardware.org/?probe=c55632d60a) | Dec 27, 2023 |
| Samsung       | 550XCJ/550XCR               | [c62c257897](https://linux-hardware.org/?probe=c62c257897) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [1948c445d8](https://linux-hardware.org/?probe=1948c445d8) | Dec 27, 2023 |
| HP            | Compaq 2510p                | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | [3ec4d2a40d](https://linux-hardware.org/?probe=3ec4d2a40d) | Dec 27, 2023 |
| Dell          | G3 3500                     | [87c0216250](https://linux-hardware.org/?probe=87c0216250) | Dec 27, 2023 |
| UNOWHY        | Y13G012S4EI                 | [a3bb952104](https://linux-hardware.org/?probe=a3bb952104) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G614JZ_G614JZ     | [eb40e7ad5c](https://linux-hardware.org/?probe=eb40e7ad5c) | Dec 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [40c72fd8c2](https://linux-hardware.org/?probe=40c72fd8c2) | Dec 27, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [151f072ac9](https://linux-hardware.org/?probe=151f072ac9) | Dec 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [594935ef8c](https://linux-hardware.org/?probe=594935ef8c) | Dec 27, 2023 |
| Apple         | MacBookPro9,2               | [99dfa98b06](https://linux-hardware.org/?probe=99dfa98b06) | Dec 27, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [8ec110334b](https://linux-hardware.org/?probe=8ec110334b) | Dec 27, 2023 |
| Apple         | MacBookAir6,2               | [eaa0ff8b0c](https://linux-hardware.org/?probe=eaa0ff8b0c) | Dec 27, 2023 |
| Apple         | MacBookAir6,2               | [4a28e0da3c](https://linux-hardware.org/?probe=4a28e0da3c) | Dec 27, 2023 |
| Valve         | Jupiter                     | [73a4d3fcfd](https://linux-hardware.org/?probe=73a4d3fcfd) | Dec 27, 2023 |
| Lenovo        | IdeaPad S340-15IML 81NA     | [1594f8077b](https://linux-hardware.org/?probe=1594f8077b) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3fd67d4da9](https://linux-hardware.org/?probe=3fd67d4da9) | Dec 27, 2023 |
| Lenovo        | G50-45 80E3                 | [90e55e787b](https://linux-hardware.org/?probe=90e55e787b) | Dec 27, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [6ce71dea49](https://linux-hardware.org/?probe=6ce71dea49) | Dec 27, 2023 |
| Lenovo        | Mullins-LarneML             | [e545ddc079](https://linux-hardware.org/?probe=e545ddc079) | Dec 27, 2023 |
| HP            | Laptop 14-dk0xxx            | [754b2e0faf](https://linux-hardware.org/?probe=754b2e0faf) | Dec 27, 2023 |
| HP            | Laptop 14-dk0xxx            | [be356bc929](https://linux-hardware.org/?probe=be356bc929) | Dec 27, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | [c16f162169](https://linux-hardware.org/?probe=c16f162169) | Dec 27, 2023 |
| Acer          | Aspire A114-31              | [dfa2a6458d](https://linux-hardware.org/?probe=dfa2a6458d) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [242659bbee](https://linux-hardware.org/?probe=242659bbee) | Dec 27, 2023 |
| HP            | EliteBook 8570w             | [4cd7501dc7](https://linux-hardware.org/?probe=4cd7501dc7) | Dec 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [7b5e390f00](https://linux-hardware.org/?probe=7b5e390f00) | Dec 27, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [eaa68fe0f5](https://linux-hardware.org/?probe=eaa68fe0f5) | Dec 27, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [84bc2c3915](https://linux-hardware.org/?probe=84bc2c3915) | Dec 27, 2023 |
| HP            | Pavilion dv6                | [c29956a752](https://linux-hardware.org/?probe=c29956a752) | Dec 27, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [f745deb3d7](https://linux-hardware.org/?probe=f745deb3d7) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a81c208684](https://linux-hardware.org/?probe=a81c208684) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| Dell          | Latitude 3520               | [b5802159c7](https://linux-hardware.org/?probe=b5802159c7) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c56c8e1bcf](https://linux-hardware.org/?probe=c56c8e1bcf) | Dec 27, 2023 |
| Toshiba       | dynabook Satellite B552/... | [544ae58a40](https://linux-hardware.org/?probe=544ae58a40) | Dec 27, 2023 |
| Dell          | Inspiron 5570               | [84242f4904](https://linux-hardware.org/?probe=84242f4904) | Dec 27, 2023 |
| ASUSTek       | X55U                        | [a29a0b8a23](https://linux-hardware.org/?probe=a29a0b8a23) | Dec 27, 2023 |
| Apple         | MacBookPro11,1              | [344f1c919a](https://linux-hardware.org/?probe=344f1c919a) | Dec 27, 2023 |
| TUXEDO        | Pulse 14 Gen3               | [7873276f27](https://linux-hardware.org/?probe=7873276f27) | Dec 27, 2023 |
| ASUSTek       | X200LA                      | [e7eb756fbf](https://linux-hardware.org/?probe=e7eb756fbf) | Dec 27, 2023 |
| ASUSTek       | X75A                        | [a7b35ca7c8](https://linux-hardware.org/?probe=a7b35ca7c8) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Inter Sale... | NID-11125DE                 | [b3e9e05ed1](https://linux-hardware.org/?probe=b3e9e05ed1) | Dec 27, 2023 |
| Acer          | Nitro AN517-41              | [ab7e890030](https://linux-hardware.org/?probe=ab7e890030) | Dec 27, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | [9d710b8199](https://linux-hardware.org/?probe=9d710b8199) | Dec 27, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [5ef2e29839](https://linux-hardware.org/?probe=5ef2e29839) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [6061821ba9](https://linux-hardware.org/?probe=6061821ba9) | Dec 27, 2023 |
| HUAWEI        | BOD-WXX9                    | [1d2d72f2a2](https://linux-hardware.org/?probe=1d2d72f2a2) | Dec 27, 2023 |
| HP            | 255 G7 Notebook PC          | [8b217c5f35](https://linux-hardware.org/?probe=8b217c5f35) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1fc3f917f2](https://linux-hardware.org/?probe=1fc3f917f2) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [32c3fcc941](https://linux-hardware.org/?probe=32c3fcc941) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | [d39de69e1b](https://linux-hardware.org/?probe=d39de69e1b) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [e36502092e](https://linux-hardware.org/?probe=e36502092e) | Dec 27, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [3d96eb6f36](https://linux-hardware.org/?probe=3d96eb6f36) | Dec 27, 2023 |
| MSI           | Modern 15 B7M               | [2c7f48c9ad](https://linux-hardware.org/?probe=2c7f48c9ad) | Dec 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6d222bdbcb](https://linux-hardware.org/?probe=6d222bdbcb) | Dec 27, 2023 |
| Unknown       | Unknown                     | [0f40cd177e](https://linux-hardware.org/?probe=0f40cd177e) | Dec 27, 2023 |
| Unknown       | Unknown                     | [5965d25e5a](https://linux-hardware.org/?probe=5965d25e5a) | Dec 27, 2023 |
| HP            | Laptop 17-bs0xx             | [07f0d2eb99](https://linux-hardware.org/?probe=07f0d2eb99) | Dec 27, 2023 |
| Dell          | Inspiron 7737               | [b0bde36cc7](https://linux-hardware.org/?probe=b0bde36cc7) | Dec 27, 2023 |
| Dell          | G3 3590                     | [681f15e9c0](https://linux-hardware.org/?probe=681f15e9c0) | Dec 27, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [418992da4d](https://linux-hardware.org/?probe=418992da4d) | Dec 27, 2023 |
| Dell          | Latitude 5420               | [769ba1b68c](https://linux-hardware.org/?probe=769ba1b68c) | Dec 27, 2023 |
| Lenovo        | ThinkPad L530 2475A61       | [990d8dce86](https://linux-hardware.org/?probe=990d8dce86) | Dec 27, 2023 |
| HP            | EliteBook 2540p             | [a23b223ac4](https://linux-hardware.org/?probe=a23b223ac4) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [e623c937a6](https://linux-hardware.org/?probe=e623c937a6) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [f6c6dba166](https://linux-hardware.org/?probe=f6c6dba166) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [705f4fa6fd](https://linux-hardware.org/?probe=705f4fa6fd) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [9435700f28](https://linux-hardware.org/?probe=9435700f28) | Dec 27, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [7378a1bdb4](https://linux-hardware.org/?probe=7378a1bdb4) | Dec 27, 2023 |
| Dell          | Latitude E7440              | [6e44f58de9](https://linux-hardware.org/?probe=6e44f58de9) | Dec 27, 2023 |
| ASUSTek       | GL753VD                     | [73bbd42b1f](https://linux-hardware.org/?probe=73bbd42b1f) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [06264d7b71](https://linux-hardware.org/?probe=06264d7b71) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [09c41915d8](https://linux-hardware.org/?probe=09c41915d8) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [a89881fc3b](https://linux-hardware.org/?probe=a89881fc3b) | Dec 27, 2023 |
| HP            | ProBook 650 G2              | [b18f714a89](https://linux-hardware.org/?probe=b18f714a89) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [2424999ad8](https://linux-hardware.org/?probe=2424999ad8) | Dec 27, 2023 |
| HP            | ProBook 650 G1              | [1126414dff](https://linux-hardware.org/?probe=1126414dff) | Dec 27, 2023 |
| HP            | ProBook 450 G3              | [2ddc54287d](https://linux-hardware.org/?probe=2ddc54287d) | Dec 27, 2023 |
| Dell          | Latitude E6430              | [a5ce676225](https://linux-hardware.org/?probe=a5ce676225) | Dec 27, 2023 |
| Chuwi         | MiniBook X                  | [6249e8f644](https://linux-hardware.org/?probe=6249e8f644) | Dec 27, 2023 |
| Dell          | XPS 15 9570                 | [25466d5d3b](https://linux-hardware.org/?probe=25466d5d3b) | Dec 27, 2023 |
| HP            | Pavilion dv7                | [c84d0249b0](https://linux-hardware.org/?probe=c84d0249b0) | Dec 27, 2023 |
| Lenovo        | IdeaPad S740-15IRH Touch... | [6584c1853d](https://linux-hardware.org/?probe=6584c1853d) | Dec 27, 2023 |
| Dell          | Vostro 3446                 | [ed9d04a3d2](https://linux-hardware.org/?probe=ed9d04a3d2) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| HP            | Pavilion dv7                | [a5fde2f725](https://linux-hardware.org/?probe=a5fde2f725) | Dec 27, 2023 |
| Acer          | Swift SFX14-41G             | [72e733aa23](https://linux-hardware.org/?probe=72e733aa23) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| LG Electro... | 17Z90N-R.AAC8U1             | [b9fd2cf453](https://linux-hardware.org/?probe=b9fd2cf453) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [f7d4fcd885](https://linux-hardware.org/?probe=f7d4fcd885) | Dec 27, 2023 |
| Acer          | Predator PHN16-71           | [865ecc4a8b](https://linux-hardware.org/?probe=865ecc4a8b) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L50007RT    | [17df248bb2](https://linux-hardware.org/?probe=17df248bb2) | Dec 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [cce90b21c6](https://linux-hardware.org/?probe=cce90b21c6) | Dec 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [82dda49ee8](https://linux-hardware.org/?probe=82dda49ee8) | Dec 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [10918ac964](https://linux-hardware.org/?probe=10918ac964) | Dec 27, 2023 |
| Lenovo        | IdeaPad S145-14API 81UV     | [bd8145e3db](https://linux-hardware.org/?probe=bd8145e3db) | Dec 27, 2023 |
| Valve         | Jupiter                     | [bee71f6f73](https://linux-hardware.org/?probe=bee71f6f73) | Dec 27, 2023 |
| HP            | Laptop 14s-dy5xxx           | [de602b4dc6](https://linux-hardware.org/?probe=de602b4dc6) | Dec 27, 2023 |
| Dell          | XPS 17 9720                 | [ff40dc8bad](https://linux-hardware.org/?probe=ff40dc8bad) | Dec 27, 2023 |
| Apple         | MacBookAir9,1               | [13a55dee9a](https://linux-hardware.org/?probe=13a55dee9a) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| Gigabyte      | AERO 15-X9                  | [906642b6ec](https://linux-hardware.org/?probe=906642b6ec) | Dec 27, 2023 |
| Lenovo        | G510 20238                  | [d91e69cc3a](https://linux-hardware.org/?probe=d91e69cc3a) | Dec 27, 2023 |
| Dell          | Inspiron 3583               | [de1dd08f64](https://linux-hardware.org/?probe=de1dd08f64) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4290B52       | [f4ec8bd5f1](https://linux-hardware.org/?probe=f4ec8bd5f1) | Dec 27, 2023 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [7979b3518c](https://linux-hardware.org/?probe=7979b3518c) | Dec 27, 2023 |
| Dell          | Latitude 5420               | [07b64f5dfe](https://linux-hardware.org/?probe=07b64f5dfe) | Dec 27, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [d304e99c16](https://linux-hardware.org/?probe=d304e99c16) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | [c4f9e9de5e](https://linux-hardware.org/?probe=c4f9e9de5e) | Dec 27, 2023 |
| Acer          | TravelMate P256-M           | [c129debcae](https://linux-hardware.org/?probe=c129debcae) | Dec 27, 2023 |
| Unknown       | Unknown                     | [0d550e2115](https://linux-hardware.org/?probe=0d550e2115) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58080b01c8](https://linux-hardware.org/?probe=58080b01c8) | Dec 27, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [df9f1cce5b](https://linux-hardware.org/?probe=df9f1cce5b) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| Dell          | Latitude 5400               | [4c2ddb74c4](https://linux-hardware.org/?probe=4c2ddb74c4) | Dec 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [626b056720](https://linux-hardware.org/?probe=626b056720) | Dec 27, 2023 |
| Dell          | Latitude 5591               | [99b2702a06](https://linux-hardware.org/?probe=99b2702a06) | Dec 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [8af95757fe](https://linux-hardware.org/?probe=8af95757fe) | Dec 27, 2023 |
| Acer          | Aspire 5736Z                | [36f131247e](https://linux-hardware.org/?probe=36f131247e) | Dec 27, 2023 |
| Lenovo        | ThinkPad E480 20KN0065MX    | [14018f1aec](https://linux-hardware.org/?probe=14018f1aec) | Dec 27, 2023 |
| ShangMai      | H                           | [aab28ab3ea](https://linux-hardware.org/?probe=aab28ab3ea) | Dec 27, 2023 |
| Acer          | Aspire E5-571G              | [a143ecb3c3](https://linux-hardware.org/?probe=a143ecb3c3) | Dec 27, 2023 |
| Sony          | SVS13A25PLB                 | [9b32de2519](https://linux-hardware.org/?probe=9b32de2519) | Dec 27, 2023 |
| HP            | ProBook 6570b               | [61f91864e5](https://linux-hardware.org/?probe=61f91864e5) | Dec 27, 2023 |
| Unknown       | Unknown                     | [2bb2a6cd8b](https://linux-hardware.org/?probe=2bb2a6cd8b) | Dec 27, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [925fd30c8a](https://linux-hardware.org/?probe=925fd30c8a) | Dec 27, 2023 |
| Valve         | Jupiter                     | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S24N3J    | [b6b0c2c889](https://linux-hardware.org/?probe=b6b0c2c889) | Dec 27, 2023 |
| Google        | Swanky                      | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Lenovo        | IdeaPad 3-15ITL6 82H8       | [b465280108](https://linux-hardware.org/?probe=b465280108) | Dec 27, 2023 |
| Alienware     | 15 R4                       | [b0bc2ccb53](https://linux-hardware.org/?probe=b0bc2ccb53) | Dec 27, 2023 |
| HUAWEI        | NbDE-WXX9                   | [5f124e4838](https://linux-hardware.org/?probe=5f124e4838) | Dec 27, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [a8871fb21b](https://linux-hardware.org/?probe=a8871fb21b) | Dec 27, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [8017d1c054](https://linux-hardware.org/?probe=8017d1c054) | Dec 27, 2023 |
| Lenovo        | ThinkPad T510 43492RU       | [d3f51b650d](https://linux-hardware.org/?probe=d3f51b650d) | Dec 27, 2023 |
| Valve         | Jupiter                     | [c2f08b6c04](https://linux-hardware.org/?probe=c2f08b6c04) | Dec 26, 2023 |
| Dell          | Precision M4800             | [47508330f1](https://linux-hardware.org/?probe=47508330f1) | Dec 26, 2023 |
| Dell          | Latitude E6530              | [bd56df50f6](https://linux-hardware.org/?probe=bd56df50f6) | Dec 26, 2023 |
| HONOR         | NMH-WCX9                    | [5647df79c0](https://linux-hardware.org/?probe=5647df79c0) | Dec 26, 2023 |
| Lenovo        | IdeaPad 3-15ITL6 82H8       | [67849c584b](https://linux-hardware.org/?probe=67849c584b) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [38b1c283b4](https://linux-hardware.org/?probe=38b1c283b4) | Dec 26, 2023 |
| Hampoo        | L1W6_I1101_C Reserved       | [ad4de7dcab](https://linux-hardware.org/?probe=ad4de7dcab) | Dec 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e832f6b336](https://linux-hardware.org/?probe=e832f6b336) | Dec 26, 2023 |
| Alienware     | m16 R1 AMD                  | [98aaf575cc](https://linux-hardware.org/?probe=98aaf575cc) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d1cd9acaf0](https://linux-hardware.org/?probe=d1cd9acaf0) | Dec 26, 2023 |
| ASUSTek       | K53E                        | [42082143bc](https://linux-hardware.org/?probe=42082143bc) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [3673afc1cd](https://linux-hardware.org/?probe=3673afc1cd) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7a0c2d1a36](https://linux-hardware.org/?probe=7a0c2d1a36) | Dec 26, 2023 |
| GPD           | G1619-04                    | [f77175c08b](https://linux-hardware.org/?probe=f77175c08b) | Dec 26, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [9b570f14f6](https://linux-hardware.org/?probe=9b570f14f6) | Dec 26, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | [b602153aeb](https://linux-hardware.org/?probe=b602153aeb) | Dec 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f2094a7c07](https://linux-hardware.org/?probe=f2094a7c07) | Dec 26, 2023 |
| ASUSTek       | F3Ke                        | [22f515ae42](https://linux-hardware.org/?probe=22f515ae42) | Dec 26, 2023 |
| GITSTAR       | GDC-1461                    | [398e4f42e4](https://linux-hardware.org/?probe=398e4f42e4) | Dec 26, 2023 |
| Acer          | Predator G9-793             | [cd39cff277](https://linux-hardware.org/?probe=cd39cff277) | Dec 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [f91e53f3e0](https://linux-hardware.org/?probe=f91e53f3e0) | Dec 26, 2023 |
| Dell          | Latitude E7450              | [84dc5f09e7](https://linux-hardware.org/?probe=84dc5f09e7) | Dec 26, 2023 |
| Notebook      | NL5xNU                      | [ad5a093909](https://linux-hardware.org/?probe=ad5a093909) | Dec 26, 2023 |
| MSI           | GS40 6QE Phantom            | [2946f9add8](https://linux-hardware.org/?probe=2946f9add8) | Dec 26, 2023 |
| Dell          | Latitude 3420               | [d17deb16ca](https://linux-hardware.org/?probe=d17deb16ca) | Dec 26, 2023 |
| Dell          | Inspiron 15 3515            | [6369debba7](https://linux-hardware.org/?probe=6369debba7) | Dec 26, 2023 |
| Medion        | P6613                       | [1f30069d6d](https://linux-hardware.org/?probe=1f30069d6d) | Dec 26, 2023 |
| ASUSTek       | X550CC                      | [6fa1156580](https://linux-hardware.org/?probe=6fa1156580) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [5a76629311](https://linux-hardware.org/?probe=5a76629311) | Dec 26, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [44db3755d8](https://linux-hardware.org/?probe=44db3755d8) | Dec 26, 2023 |
| HP            | ProBook 6460b               | [4a6a6b9b9d](https://linux-hardware.org/?probe=4a6a6b9b9d) | Dec 26, 2023 |
| ASUSTek       | G750JM                      | [fcda025864](https://linux-hardware.org/?probe=fcda025864) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | [6b4237a1ea](https://linux-hardware.org/?probe=6b4237a1ea) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | [408e19e1f2](https://linux-hardware.org/?probe=408e19e1f2) | Dec 26, 2023 |
| Juana Mans... | SF20GM7                     | [697c873386](https://linux-hardware.org/?probe=697c873386) | Dec 26, 2023 |
| Acer          | Nitro ANV15-51              | [0e1146871b](https://linux-hardware.org/?probe=0e1146871b) | Dec 26, 2023 |
| Dell          | Latitude 5400               | [35adbae547](https://linux-hardware.org/?probe=35adbae547) | Dec 26, 2023 |
| Samsung       | RF511/RF411/RF711           | [743bed087b](https://linux-hardware.org/?probe=743bed087b) | Dec 26, 2023 |
| TUXEDO        | N24_25JU                    | [3c7a5feb48](https://linux-hardware.org/?probe=3c7a5feb48) | Dec 26, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [8b68f422dd](https://linux-hardware.org/?probe=8b68f422dd) | Dec 26, 2023 |
| Lenovo        | ThinkPad T520 4243ED3       | [6fd4832f12](https://linux-hardware.org/?probe=6fd4832f12) | Dec 26, 2023 |
| HUAWEI        | MRGFG-XX                    | [8ac7316911](https://linux-hardware.org/?probe=8ac7316911) | Dec 26, 2023 |
| Kiano         | Elegance 14.2               | [9c32017999](https://linux-hardware.org/?probe=9c32017999) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f58bf5fe4c](https://linux-hardware.org/?probe=f58bf5fe4c) | Dec 26, 2023 |
| HP            | ProBook 450 G3              | [1e952ed878](https://linux-hardware.org/?probe=1e952ed878) | Dec 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | [a49698d49d](https://linux-hardware.org/?probe=a49698d49d) | Dec 26, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [ec9fe6e527](https://linux-hardware.org/?probe=ec9fe6e527) | Dec 26, 2023 |
| HP            | Compaq nx7400 (RH609ES#A... | [6a6b1d3722](https://linux-hardware.org/?probe=6a6b1d3722) | Dec 26, 2023 |
| HP            | ProBook 455 G3              | [9e47611108](https://linux-hardware.org/?probe=9e47611108) | Dec 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a32866554a](https://linux-hardware.org/?probe=a32866554a) | Dec 26, 2023 |
| Apple         | MacBookAir9,1               | [22b65c12f2](https://linux-hardware.org/?probe=22b65c12f2) | Dec 26, 2023 |
| Apple         | MacBookAir6,2               | [67979f3133](https://linux-hardware.org/?probe=67979f3133) | Dec 26, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [97f532d3c8](https://linux-hardware.org/?probe=97f532d3c8) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [971e3fe3eb](https://linux-hardware.org/?probe=971e3fe3eb) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4a481ca830](https://linux-hardware.org/?probe=4a481ca830) | Dec 26, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | [e514863c67](https://linux-hardware.org/?probe=e514863c67) | Dec 26, 2023 |
| Dell          | Vostro 5470                 | [76b6b08744](https://linux-hardware.org/?probe=76b6b08744) | Dec 26, 2023 |
| Dell          | Latitude 3190               | [e0da711bcb](https://linux-hardware.org/?probe=e0da711bcb) | Dec 26, 2023 |
| Dell          | Inspiron 5391               | [a97f2efb6f](https://linux-hardware.org/?probe=a97f2efb6f) | Dec 26, 2023 |
| Dell          | Inspiron 3558               | [d5e9630425](https://linux-hardware.org/?probe=d5e9630425) | Dec 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4fb309a12a](https://linux-hardware.org/?probe=4fb309a12a) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7d873eb94f](https://linux-hardware.org/?probe=7d873eb94f) | Dec 26, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [ed9f6e6354](https://linux-hardware.org/?probe=ed9f6e6354) | Dec 26, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [b35c9836e7](https://linux-hardware.org/?probe=b35c9836e7) | Dec 26, 2023 |
| Chuwi         | MiniBook X                  | [f55a24b036](https://linux-hardware.org/?probe=f55a24b036) | Dec 26, 2023 |
| Acer          | Aspire E1-532               | [c7d5bac798](https://linux-hardware.org/?probe=c7d5bac798) | Dec 26, 2023 |
| Dell          | XPS 13 9370                 | [17304074a6](https://linux-hardware.org/?probe=17304074a6) | Dec 26, 2023 |
| Schenker      | N13xWU                      | [c94ab912c7](https://linux-hardware.org/?probe=c94ab912c7) | Dec 26, 2023 |
| Lenovo        | ThinkPad W530 24474LG       | [180b4817c4](https://linux-hardware.org/?probe=180b4817c4) | Dec 26, 2023 |
| Lenovo        | Unknown                     | [5d5f205d61](https://linux-hardware.org/?probe=5d5f205d61) | Dec 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3db4d71445](https://linux-hardware.org/?probe=3db4d71445) | Dec 26, 2023 |
| Lenovo        | ThinkPad E470 20H1004UIG    | [69efda7672](https://linux-hardware.org/?probe=69efda7672) | Dec 26, 2023 |
| Dell          | XPS 13 9380                 | [541f2d959f](https://linux-hardware.org/?probe=541f2d959f) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [229d71f583](https://linux-hardware.org/?probe=229d71f583) | Dec 26, 2023 |
| Schenker      | N13xWU                      | [b2ff4375a0](https://linux-hardware.org/?probe=b2ff4375a0) | Dec 26, 2023 |
| ASUSTek       | UX31A                       | [bb819f78ef](https://linux-hardware.org/?probe=bb819f78ef) | Dec 26, 2023 |
| Dell          | Precision 7520              | [e4390e22b6](https://linux-hardware.org/?probe=e4390e22b6) | Dec 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8fae3225fd](https://linux-hardware.org/?probe=8fae3225fd) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7fdd8a3f38](https://linux-hardware.org/?probe=7fdd8a3f38) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a1fd8cc737](https://linux-hardware.org/?probe=a1fd8cc737) | Dec 26, 2023 |
| Dell          | Inspiron 3558               | [3015754a4f](https://linux-hardware.org/?probe=3015754a4f) | Dec 26, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [db50c73272](https://linux-hardware.org/?probe=db50c73272) | Dec 26, 2023 |
| Dell          | XPS 15 9530                 | [5902199f52](https://linux-hardware.org/?probe=5902199f52) | Dec 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0W32L    | [55200b6aa5](https://linux-hardware.org/?probe=55200b6aa5) | Dec 26, 2023 |
| HP            | 2000                        | [057698e1aa](https://linux-hardware.org/?probe=057698e1aa) | Dec 26, 2023 |
| Apple         | MacBookPro13,1              | [63344458c9](https://linux-hardware.org/?probe=63344458c9) | Dec 26, 2023 |
| Lenovo        | B51-35 80LH                 | [85a89b00af](https://linux-hardware.org/?probe=85a89b00af) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [b000376310](https://linux-hardware.org/?probe=b000376310) | Dec 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ff3773b480](https://linux-hardware.org/?probe=ff3773b480) | Dec 26, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [3fd8513ee7](https://linux-hardware.org/?probe=3fd8513ee7) | Dec 26, 2023 |
| Lenovo        | ThinkPad E480 20KN003XUS    | [b83c19a718](https://linux-hardware.org/?probe=b83c19a718) | Dec 26, 2023 |
| Dell          | Latitude 5440               | [44e45480d1](https://linux-hardware.org/?probe=44e45480d1) | Dec 26, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c436ff8cab](https://linux-hardware.org/?probe=c436ff8cab) | Dec 26, 2023 |
| Lenovo        | ThinkPad T61 7663DL1        | [b01632df81](https://linux-hardware.org/?probe=b01632df81) | Dec 26, 2023 |
| Apple         | MacBookPro12,1              | [0714d5920a](https://linux-hardware.org/?probe=0714d5920a) | Dec 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [77553a2b0e](https://linux-hardware.org/?probe=77553a2b0e) | Dec 26, 2023 |
| Lenovo        | ThinkPad L470 20J5S0JM00    | [c8f1140dc5](https://linux-hardware.org/?probe=c8f1140dc5) | Dec 26, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [b5b5857360](https://linux-hardware.org/?probe=b5b5857360) | Dec 26, 2023 |
| Dell          | Latitude E6420              | [3a25e340a8](https://linux-hardware.org/?probe=3a25e340a8) | Dec 26, 2023 |
| Dell          | XPS 13 9343                 | [8ba85bdc8c](https://linux-hardware.org/?probe=8ba85bdc8c) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | [c7758c21ce](https://linux-hardware.org/?probe=c7758c21ce) | Dec 26, 2023 |
| Unknown       | Unknown                     | [64873f6716](https://linux-hardware.org/?probe=64873f6716) | Dec 26, 2023 |
| Acer          | Aspire 4750                 | [9f4b6b970d](https://linux-hardware.org/?probe=9f4b6b970d) | Dec 26, 2023 |
| ASUSTek       | X550DP                      | [a456e712b7](https://linux-hardware.org/?probe=a456e712b7) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [ef91ce6df3](https://linux-hardware.org/?probe=ef91ce6df3) | Dec 26, 2023 |
| HP            | Victus by Gaming Laptop ... | [081217d505](https://linux-hardware.org/?probe=081217d505) | Dec 26, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [5f798fd0e0](https://linux-hardware.org/?probe=5f798fd0e0) | Dec 26, 2023 |
| HP            | 15 Notebook PC              | [0b603c74cf](https://linux-hardware.org/?probe=0b603c74cf) | Dec 26, 2023 |
| Lenovo        | ThinkPad T500 20828WG       | [a3edf5e69b](https://linux-hardware.org/?probe=a3edf5e69b) | Dec 26, 2023 |
| Dell          | XPS 15 9530                 | [cf1f0e7284](https://linux-hardware.org/?probe=cf1f0e7284) | Dec 26, 2023 |
| Medion        | E6228                       | [827fcc5d4b](https://linux-hardware.org/?probe=827fcc5d4b) | Dec 26, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 13978     | 10.28%  |
| Ubuntu 22.04      | 7508      | 5.52%   |
| Ubuntu 18.04      | 6971      | 5.13%   |
| Debian 11         | 3418      | 2.51%   |
| Arch Rolling      | 2510      | 1.85%   |
| OpenMandriva 4.2  | 2219      | 1.63%   |
| Pop!_OS 22.04     | 2213      | 1.63%   |
| OpenMandriva 4.3  | 2177      | 1.6%    |
| ROSA R10          | 2145      | 1.58%   |
| Zorin 16          | 2120      | 1.56%   |
| ROSA R11          | 1942      | 1.43%   |
| Linux Mint 20.3   | 1773      | 1.3%    |
| Fedora 38         | 1753      | 1.29%   |
| Arch              | 1744      | 1.28%   |
| ROSA R8           | 1704      | 1.25%   |
| ROSA R6           | 1686      | 1.24%   |
| Manjaro           | 1668      | 1.23%   |
| BlackPanther 18.1 | 1597      | 1.17%   |
| ROSA R7           | 1566      | 1.15%   |
| KDE neon 20.04    | 1561      | 1.15%   |
| Linux Mint 21.1   | 1526      | 1.12%   |
| Linux Mint 20.2   | 1358      | 1%      |
| ROSA R8.1         | 1350      | 0.99%   |
| Linux Mint 19.3   | 1246      | 0.92%   |
| Fedora 36         | 1243      | 0.91%   |
| Fedora 37         | 1240      | 0.91%   |
| Linux Mint 20.1   | 1237      | 0.91%   |
| Debian 12         | 1230      | 0.9%    |
| ROSA R9           | 1218      | 0.9%    |
| ArcoLinux Rolling | 1164      | 0.86%   |
| Ubuntu 19.10      | 1159      | 0.85%   |
| Pop!_OS 20.04     | 1153      | 0.85%   |
| Linux Mint 20     | 1148      | 0.84%   |
| Ubuntu 21.10      | 1124      | 0.83%   |
| ROSA R11.1        | 1104      | 0.81%   |
| Ubuntu 20.10      | 1093      | 0.8%    |
| Linux Mint 21.2   | 1082      | 0.8%    |
| Ubuntu 19.04      | 1037      | 0.76%   |
| Xubuntu 20.04     | 1036      | 0.76%   |
| Zorin 15          | 1016      | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 35066     | 27.72%  |
| ROSA          | 12777     | 10.1%   |
| Linux Mint    | 10709     | 8.46%   |
| Fedora        | 8189      | 6.47%   |
| OpenMandriva  | 7691      | 6.08%   |
| Debian        | 6124      | 4.84%   |
| Pop!_OS       | 5565      | 4.4%    |
| Arch          | 4145      | 3.28%   |
| Manjaro       | 4030      | 3.19%   |
| Zorin         | 3284      | 2.6%    |
| Endless       | 2679      | 2.12%   |
| Kubuntu       | 2456      | 1.94%   |
| Xubuntu       | 2360      | 1.87%   |
| KDE neon      | 2307      | 1.82%   |
| BlackPanther  | 1764      | 1.39%   |
| openSUSE      | 1340      | 1.06%   |
| Kali          | 1330      | 1.05%   |
| ArcoLinux     | 1268      | 1%      |
| SteamOS       | 1205      | 0.95%   |
| Elementary    | 1097      | 0.87%   |
| Lubuntu       | 873       | 0.69%   |
| Gentoo        | 774       | 0.61%   |
| EndeavourOS   | 756       | 0.6%    |
| Ubuntu MATE   | 749       | 0.59%   |
| Ubuntu Unity  | 642       | 0.51%   |
| LMDE          | 573       | 0.45%   |
| Clear Linux   | 466       | 0.37%   |
| MX            | 435       | 0.34%   |
| Ubuntu Budgie | 424       | 0.34%   |
| Parrot        | 387       | 0.31%   |
| Garuda Linux  | 321       | 0.25%   |
| Nobara        | 304       | 0.24%   |
| ALT Linux     | 283       | 0.22%   |
| Xero          | 247       | 0.2%    |
| CentOS        | 221       | 0.17%   |
| Peppermint    | 196       | 0.15%   |
| RHEL          | 160       | 0.13%   |
| NixOS         | 152       | 0.12%   |
| Artix         | 152       | 0.12%   |
| Deepin        | 140       | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 2208      | 1.48%   |
| 5.10.14-desktop-1omv4002           | 2133      | 1.43%   |
| 5.16.7-desktop-1omv4003            | 2041      | 1.37%   |
| 5.15.0-56-generic                  | 1225      | 0.82%   |
| 4.18.16-desktop-1bP                | 1161      | 0.78%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 955       | 0.64%   |
| 5.4.0-58-generic                   | 952       | 0.64%   |
| 6.2.6-desktop-1omv2390             | 928       | 0.62%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 891       | 0.6%    |
| 6.1.1-desktop-1omv2290             | 889       | 0.6%    |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 854       | 0.57%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 848       | 0.57%   |
| 5.15.0-58-generic                  | 846       | 0.57%   |
| 5.4.0-48-generic                   | 826       | 0.55%   |
| 5.15.0-52-generic                  | 823       | 0.55%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 803       | 0.54%   |
| 5.4.0-52-generic                   | 800       | 0.54%   |
| 5.4.0-26-generic                   | 734       | 0.49%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 725       | 0.49%   |
| 5.3.0-28-generic                   | 702       | 0.47%   |
| 5.15.0-46-generic                  | 689       | 0.46%   |
| 5.4.0-29-generic                   | 646       | 0.43%   |
| 5.11.0-27-generic                  | 633       | 0.43%   |
| 5.8.0-14-generic                   | 632       | 0.42%   |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 621       | 0.42%   |
| 5.4.0-40-generic                   | 607       | 0.41%   |
| 5.3.0-40-generic                   | 603       | 0.41%   |
| 5.10.0-8-amd64                     | 602       | 0.4%    |
| 5.15.0-48-generic                  | 595       | 0.4%    |
| 6.2.0-26-generic                   | 592       | 0.4%    |
| 5.3.0-46-generic                   | 588       | 0.4%    |
| 6.4.11-desktop-1omv2390            | 548       | 0.37%   |
| 5.11.0-38-generic                  | 547       | 0.37%   |
| 5.4.0-91-generic                   | 543       | 0.36%   |
| 5.11.0-37-generic                  | 537       | 0.36%   |
| 5.8.0-43-generic                   | 528       | 0.35%   |
| 5.0.0-37-generic                   | 516       | 0.35%   |
| 5.19.0-35-generic                  | 515       | 0.35%   |
| 5.15.0-41-generic                  | 514       | 0.35%   |
| 5.4.0-65-generic                   | 506       | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 18172     | 12.89%  |
| 5.15.0  | 11258     | 7.98%   |
| 4.15.0  | 7245      | 5.14%   |
| 5.11.0  | 5888      | 4.18%   |
| 5.8.0   | 5838      | 4.14%   |
| 5.13.0  | 5564      | 3.95%   |
| 5.3.0   | 4640      | 3.29%   |
| 5.10.0  | 4282      | 3.04%   |
| 5.19.0  | 3989      | 2.83%   |
| 6.2.0   | 3643      | 2.58%   |
| 5.0.0   | 3012      | 2.14%   |
| 4.18.0  | 2181      | 1.55%   |
| 5.10.14 | 2156      | 1.53%   |
| 5.16.7  | 2081      | 1.48%   |
| 6.1.0   | 1867      | 1.32%   |
| 6.2.6   | 1466      | 1.04%   |
| 4.9.20  | 1288      | 0.91%   |
| 3.14.44 | 1284      | 0.91%   |
| 4.9.60  | 1239      | 0.88%   |
| 4.18.16 | 1189      | 0.84%   |
| 4.19.0  | 1068      | 0.76%   |
| 6.1.1   | 1032      | 0.73%   |
| 4.1.25  | 995       | 0.71%   |
| 6.5.0   | 865       | 0.61%   |
| 4.1.15  | 852       | 0.6%    |
| 5.10.74 | 845       | 0.6%    |
| 6.4.11  | 694       | 0.49%   |
| 4.1.34  | 645       | 0.46%   |
| 5.14.0  | 611       | 0.43%   |
| 5.6.14  | 552       | 0.39%   |
| 4.1.38  | 508       | 0.36%   |
| 4.9.124 | 490       | 0.35%   |
| 5.17.5  | 484       | 0.34%   |
| 4.9.9   | 481       | 0.34%   |
| 6.0.0   | 480       | 0.34%   |
| 6.0.12  | 427       | 0.3%    |
| 6.6.2   | 385       | 0.27%   |
| 6.5.5   | 350       | 0.25%   |
| 5.18.0  | 350       | 0.25%   |
| 6.5.6   | 348       | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 19871     | 14.43%  |
| 5.15    | 14440     | 10.49%  |
| 5.10    | 9277      | 6.74%   |
| 4.15    | 7271      | 5.28%   |
| 5.8     | 6994      | 5.08%   |
| 5.11    | 6869      | 4.99%   |
| 6.2     | 6613      | 4.8%    |
| 5.13    | 6457      | 4.69%   |
| 6.1     | 5620      | 4.08%   |
| 5.3     | 5176      | 3.76%   |
| 5.19    | 5125      | 3.72%   |
| 4.9     | 4466      | 3.24%   |
| 5.16    | 3727      | 2.71%   |
| 4.1     | 3569      | 2.59%   |
| 4.18    | 3424      | 2.49%   |
| 5.0     | 3168      | 2.3%    |
| 6.5     | 2725      | 1.98%   |
| 6.0     | 2431      | 1.77%   |
| 6.4     | 2345      | 1.7%    |
| 3.14    | 1740      | 1.26%   |
| 5.14    | 1717      | 1.25%   |
| 5.17    | 1662      | 1.21%   |
| 5.18    | 1571      | 1.14%   |
| 5.6     | 1500      | 1.09%   |
| 6.3     | 1463      | 1.06%   |
| 4.19    | 1367      | 0.99%   |
| 6.6     | 1290      | 0.94%   |
| 5.9     | 1280      | 0.93%   |
| 5.12    | 970       | 0.7%    |
| 5.7     | 849       | 0.62%   |
| 5.5     | 566       | 0.41%   |
| 4.4     | 426       | 0.31%   |
| 4.13    | 258       | 0.19%   |
| 5.1     | 228       | 0.17%   |
| 5.2     | 203       | 0.15%   |
| 3.10    | 159       | 0.12%   |
| 4.16    | 124       | 0.09%   |
| 4.14    | 92        | 0.07%   |
| 4.12    | 89        | 0.06%   |
| 4.10    | 88        | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 116108    | 95.14%  |
| i686    | 5827      | 4.77%   |
| aarch64 | 66        | 0.05%   |
| armv7l  | 28        | 0.02%   |
| ppc     | 4         | 0.003%  |
| Unknown | 4         | 0.003%  |
| i586    | 3         | 0.002%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 51803     | 40.51%  |
| KDE5             | 24168     | 18.9%   |
| Unknown          | 11955     | 9.35%   |
| KDE4             | 8735      | 6.83%   |
| XFCE             | 8651      | 6.76%   |
| X-Cinnamon       | 8029      | 6.28%   |
| MATE             | 3149      | 2.46%   |
| KDE              | 2358      | 1.84%   |
| LXQt             | 1709      | 1.34%   |
| Cinnamon         | 1518      | 1.19%   |
| Pantheon         | 1050      | 0.82%   |
| i3               | 729       | 0.57%   |
| Unity            | 663       | 0.52%   |
| LXDE             | 653       | 0.51%   |
| Budgie           | 646       | 0.51%   |
| GNOME Flashback  | 338       | 0.26%   |
| Deepin           | 286       | 0.22%   |
| sway             | 165       | 0.13%   |
| awesome          | 137       | 0.11%   |
| Hyprland         | 134       | 0.1%    |
| GNOME Classic    | 127       | 0.1%    |
| bspwm            | 91        | 0.07%   |
| DWM              | 77        | 0.06%   |
| openbox          | 75        | 0.06%   |
| lightdm-xsession | 73        | 0.06%   |
| qtile            | 66        | 0.05%   |
| Enlightenment    | 50        | 0.04%   |
| xmonad           | 47        | 0.04%   |
| icewm            | 45        | 0.04%   |
| trinity          | 44        | 0.03%   |
| BunsenLabs       | 27        | 0.02%   |
| LeftWM           | 24        | 0.02%   |
| Endless:GNOME    | 22        | 0.02%   |
| i3-with-shmlog   | 18        | 0.01%   |
| fluxbox          | 18        | 0.01%   |
| fly              | 12        | 0.01%   |
| Herbstluftwm     | 10        | 0.01%   |
| GNUstep          | 10        | 0.01%   |
| chadwm           | 10        | 0.01%   |
| UKUI             | 9         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 94266     | 75.02%  |
| Wayland     | 23199     | 18.46%  |
| Unknown     | 6931      | 5.52%   |
| Tty         | 1255      | 1%      |
| Unspecified | 6         | 0.005%  |
| Web         | 3         | 0.002%  |
| Xcb         | 1         | 0.001%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 54115     | 42.49%  |
| SDDM    | 21267     | 16.7%   |
| GDM     | 14206     | 11.15%  |
| GDM3    | 13606     | 10.68%  |
| LightDM | 11370     | 8.93%   |
| KDM     | 8788      | 6.9%    |
| TDM     | 3373      | 2.65%   |
| XDM     | 203       | 0.16%   |
| SLiM    | 122       | 0.1%    |
| LXDM    | 100       | 0.08%   |
| Ly      | 60        | 0.05%   |
| MDM     | 43        | 0.03%   |
| NODM    | 40        | 0.03%   |
| GREETD  | 36        | 0.03%   |
| LY-DM   | 11        | 0.01%   |
| SLIMSKI | 8         | 0.01%   |
| EMPTTY  | 7         | 0.01%   |
| FLY-DM  | 6         | 0.005%  |
| LDM     | 2         | 0.002%  |
| WDM     | 1         | 0.001%  |
| SU      | 1         | 0.001%  |
| LEMURS  | 1         | 0.001%  |
| CDM     | 1         | 0.001%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 44365     | 35.47%  |
| Unknown | 21937     | 17.54%  |
| de_DE   | 7774      | 6.22%   |
| ru_RU   | 7028      | 5.62%   |
| pt_BR   | 5653      | 4.52%   |
| en_GB   | 5246      | 4.19%   |
| fr_FR   | 4686      | 3.75%   |
| it_IT   | 3151      | 2.52%   |
| es_ES   | 2467      | 1.97%   |
| en_IN   | 2223      | 1.78%   |
| pl_PL   | 1955      | 1.56%   |
| C       | 1868      | 1.49%   |
| en_CA   | 1701      | 1.36%   |
| en_AU   | 1217      | 0.97%   |
| es_MX   | 962       | 0.77%   |
| cs_CZ   | 760       | 0.61%   |
| nl_NL   | 688       | 0.55%   |
| hu_HU   | 627       | 0.5%    |
| es_AR   | 587       | 0.47%   |
| zh_CN   | 553       | 0.44%   |
| tr_TR   | 543       | 0.43%   |
| pt_PT   | 536       | 0.43%   |
| en_ZA   | 458       | 0.37%   |
| de_AT   | 410       | 0.33%   |
| es_CL   | 376       | 0.3%    |
| es_CO   | 360       | 0.29%   |
| sv_SE   | 340       | 0.27%   |
| ru_UA   | 305       | 0.24%   |
| de_CH   | 297       | 0.24%   |
| en_IE   | 268       | 0.21%   |
| fi_FI   | 260       | 0.21%   |
| en_NZ   | 258       | 0.21%   |
| ja_JP   | 243       | 0.19%   |
| ro_RO   | 240       | 0.19%   |
| fr_CA   | 215       | 0.17%   |
| fr_BE   | 208       | 0.17%   |
| el_GR   | 194       | 0.16%   |
| da_DK   | 184       | 0.15%   |
| en_PH   | 175       | 0.14%   |
| nl_BE   | 170       | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 63541     | 50.96%  |
| BIOS | 61156     | 49.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 87387     | 69.4%   |
| Btrfs               | 12158     | 9.66%   |
| Unknown             | 10672     | 8.48%   |
| Overlay             | 9873      | 7.84%   |
| Tmpfs               | 3069      | 2.44%   |
| Xfs                 | 1304      | 1.04%   |
| Zfs                 | 732       | 0.58%   |
| Ext2                | 256       | 0.2%    |
| Ext3                | 173       | 0.14%   |
| F2fs                | 150       | 0.12%   |
| Aufs                | 47        | 0.04%   |
| Rootfs              | 35        | 0.03%   |
| Reiserfs            | 16        | 0.01%   |
| XXXXXXX             | 13        | 0.01%   |
| Jfs                 | 12        | 0.01%   |
| XXXXX               | 5         | 0.004%  |
| XXX4                | 3         | 0.002%  |
| Fuse.fuse-overlayfs | 3         | 0.002%  |
| Bcachefs            | 3         | 0.002%  |
| XXXfs               | 1         | 0.001%  |
| Ufs                 | 1         | 0.001%  |
| SquasXfs            | 1         | 0.001%  |
| OveXlay             | 1         | 0.001%  |
| Ntfs                | 1         | 0.001%  |
| Nfs                 | 1         | 0.001%  |
| ExX4                | 1         | 0.001%  |
| 20G                 | 1         | 0.001%  |
| 12G                 | 1         | 0.001%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 58172     | 46.3%   |
| GPT     | 48041     | 38.24%  |
| MBR     | 19430     | 15.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109531    | 88.24%  |
| Yes       | 14604     | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91160     | 73.42%  |
| Yes       | 33004     | 26.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 24454     | 20.1%   |
| Hewlett-Packard        | 20956     | 17.23%  |
| Dell                   | 18461     | 15.17%  |
| ASUSTek Computer       | 14514     | 11.93%  |
| Acer                   | 11656     | 9.58%   |
| Apple                  | 3541      | 2.91%   |
| Toshiba                | 3506      | 2.88%   |
| Samsung Electronics    | 2978      | 2.45%   |
| MSI                    | 2520      | 2.07%   |
| Sony                   | 1808      | 1.49%   |
| HUAWEI                 | 1324      | 1.09%   |
| Valve                  | 1146      | 0.94%   |
| Google                 | 902       | 0.74%   |
| Fujitsu                | 843       | 0.69%   |
| Notebook               | 761       | 0.63%   |
| Unknown                | 760       | 0.62%   |
| Packard Bell           | 721       | 0.59%   |
| Medion                 | 558       | 0.46%   |
| Positivo               | 555       | 0.46%   |
| Timi                   | 455       | 0.37%   |
| Alienware              | 415       | 0.34%   |
| TUXEDO                 | 400       | 0.33%   |
| Fujitsu Siemens        | 399       | 0.33%   |
| System76               | 374       | 0.31%   |
| eMachines              | 350       | 0.29%   |
| Clevo                  | 340       | 0.28%   |
| LG Electronics         | 290       | 0.24%   |
| Gigabyte Technology    | 252       | 0.21%   |
| Chuwi                  | 234       | 0.19%   |
| Intel                  | 224       | 0.18%   |
| Razer                  | 217       | 0.18%   |
| Panasonic              | 200       | 0.16%   |
| Gateway                | 197       | 0.16%   |
| Framework              | 181       | 0.15%   |
| GPU Company            | 141       | 0.12%   |
| HONOR                  | 126       | 0.1%    |
| Pegatron               | 120       | 0.1%    |
| Schenker               | 117       | 0.1%    |
| PC Specialist          | 111       | 0.09%   |
| Avell High Performance | 93        | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Unknown               | 1367      | 1.12%   |
| Valve Jupiter         | 1120      | 0.92%   |
| HP Notebook           | 816       | 0.67%   |
| HP Pavilion g6        | 553       | 0.45%   |
| HP Pavilion dv6       | 534       | 0.44%   |
| Apple MacBook5,2      | 384       | 0.32%   |
| HP Pavilion 15        | 344       | 0.28%   |
| HP Pavilion dv7       | 337       | 0.28%   |
| HP Pavilion Notebook  | 321       | 0.26%   |
| Apple MacBookPro9,2   | 272       | 0.22%   |
| Dell Latitude E6420   | 269       | 0.22%   |
| Apple MacBookAir7,2   | 251       | 0.21%   |
| HP 15                 | 247       | 0.2%    |
| Dell Latitude E6430   | 246       | 0.2%    |
| Apple MacBookPro8,1   | 243       | 0.2%    |
| Dell Latitude E6410   | 235       | 0.19%   |
| Acer Nitro AN515-54   | 221       | 0.18%   |
| Dell XPS 15 7590      | 214       | 0.18%   |
| Dell XPS 15 9570      | 209       | 0.17%   |
| Dell Latitude E6400   | 205       | 0.17%   |
| Dell Inspiron 15-3567 | 205       | 0.17%   |
| HP Laptop 15-bw0xx    | 202       | 0.17%   |
| HP Pavilion g7        | 201       | 0.17%   |
| HP EliteBook 840 G3   | 199       | 0.16%   |
| Dell Inspiron N5110   | 182       | 0.15%   |
| Dell Inspiron 1545    | 178       | 0.15%   |
| HP Laptop 15-db0xxx   | 175       | 0.14%   |
| HP EliteBook 8460p    | 174       | 0.14%   |
| Dell XPS 15 9500      | 174       | 0.14%   |
| Dell Inspiron 5570    | 171       | 0.14%   |
| HP Laptop 15-bs0xx    | 164       | 0.13%   |
| HP EliteBook 8470p    | 164       | 0.13%   |
| HP Laptop 15-da0xxx   | 162       | 0.13%   |
| Dell XPS 13 9370      | 162       | 0.13%   |
| Dell Inspiron 3542    | 162       | 0.13%   |
| HP Pavilion 17        | 161       | 0.13%   |
| Dell Latitude 7490    | 159       | 0.13%   |
| Dell XPS 13 9360      | 158       | 0.13%   |
| Dell XPS 15 9560      | 156       | 0.13%   |
| Lenovo G50-45 80E3    | 155       | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 11925     | 9.8%    |
| Acer Aspire           | 7883      | 6.48%   |
| Dell Latitude         | 6330      | 5.2%    |
| Dell Inspiron         | 5855      | 4.81%   |
| Lenovo IdeaPad        | 5829      | 4.79%   |
| HP Pavilion           | 4762      | 3.91%   |
| HP EliteBook          | 3296      | 2.71%   |
| Toshiba Satellite     | 2946      | 2.42%   |
| ASUS VivoBook         | 2776      | 2.28%   |
| HP Laptop             | 2765      | 2.27%   |
| HP ProBook            | 2718      | 2.23%   |
| Dell XPS              | 2357      | 1.94%   |
| Dell Precision        | 1378      | 1.13%   |
| Unknown               | 1367      | 1.12%   |
| Dell Vostro           | 1248      | 1.03%   |
| Valve Jupiter         | 1120      | 0.92%   |
| Acer Nitro            | 1033      | 0.85%   |
| Lenovo Legion         | 993       | 0.82%   |
| HP Compaq             | 984       | 0.81%   |
| ASUS ROG              | 907       | 0.75%   |
| HP Notebook           | 819       | 0.67%   |
| Acer Swift            | 759       | 0.62%   |
| ASUS Zenbook          | 721       | 0.59%   |
| Fujitsu LIFEBOOK      | 716       | 0.59%   |
| HP ZBook              | 665       | 0.55%   |
| HP ENVY               | 659       | 0.54%   |
| Packard Bell EasyNote | 635       | 0.52%   |
| ASUS ASUS             | 616       | 0.51%   |
| Lenovo ThinkBook      | 609       | 0.5%    |
| HP 250                | 579       | 0.48%   |
| Acer TravelMate       | 525       | 0.43%   |
| Lenovo Yoga           | 475       | 0.39%   |
| Acer Extensa          | 457       | 0.38%   |
| Apple MacBook5        | 456       | 0.37%   |
| HP OMEN               | 444       | 0.36%   |
| ASUS TUF              | 408       | 0.34%   |
| HP 255                | 384       | 0.32%   |
| Apple MacBookPro8     | 367       | 0.3%    |
| Apple MacBookAir7     | 353       | 0.29%   |
| Apple MacBookPro11    | 340       | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 10515     | 8.64%   |
| 2011    | 10021     | 8.24%   |
| 2012    | 9984      | 8.21%   |
| 2020    | 9750      | 8.01%   |
| 2018    | 9393      | 7.72%   |
| 2021    | 8737      | 7.18%   |
| 2013    | 8458      | 6.95%   |
| 2017    | 7405      | 6.09%   |
| 2010    | 6785      | 5.58%   |
| 2014    | 6764      | 5.56%   |
| 2016    | 6270      | 5.15%   |
| 2015    | 6251      | 5.14%   |
| 2022    | 5054      | 4.15%   |
| 2008    | 5047      | 4.15%   |
| 2009    | 4533      | 3.73%   |
| 2007    | 3196      | 2.63%   |
| 2023    | 1677      | 1.38%   |
| 2006    | 1127      | 0.93%   |
| 2005    | 347       | 0.29%   |
| Unknown | 210       | 0.17%   |
| 2004    | 82        | 0.07%   |
| 2003    | 39        | 0.03%   |
| 2002    | 9         | 0.01%   |
| 1999    | 3         | 0.002%  |
| 2001    | 2         | 0.002%  |
| 2000    | 1         | 0.001%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 121660    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 111073    | 90.44%  |
| Enabled  | 11747     | 9.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 120381    | 98.94%  |
| Yes  | 1286      | 1.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 33976     | 27.4%   |
| 3.01-4.0        | 28414     | 22.92%  |
| 8.01-16.0       | 20830     | 16.8%   |
| 16.01-24.0      | 18736     | 15.11%  |
| 1.01-2.0        | 7382      | 5.95%   |
| 32.01-64.0      | 7150      | 5.77%   |
| 2.01-3.0        | 3379      | 2.73%   |
| 24.01-32.0      | 1342      | 1.08%   |
| 64.01-256.0     | 1242      | 1%      |
| 0.51-1.0        | 1215      | 0.98%   |
| Unknown         | 235       | 0.19%   |
| 0.01-0.5        | 80        | 0.06%   |
| More than 256.0 | 2         | 0.002%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 47837     | 35.11%  |
| 2.01-3.0   | 32531     | 23.88%  |
| 4.01-8.0   | 17715     | 13%     |
| 3.01-4.0   | 16725     | 12.28%  |
| 0.51-1.0   | 14138     | 10.38%  |
| 8.01-16.0  | 4571      | 3.36%   |
| 0.01-0.5   | 1755      | 1.29%   |
| 16.01-24.0 | 475       | 0.35%   |
| Unknown    | 297       | 0.22%   |
| 24.01-32.0 | 150       | 0.11%   |
| 32.01-64.0 | 47        | 0.03%   |
| 0          | 3         | 0.002%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 92139     | 73.87%  |
| 2       | 27903     | 22.37%  |
| 3       | 3146      | 2.52%   |
| 0       | 1020      | 0.82%   |
| 4       | 393       | 0.32%   |
| 5       | 83        | 0.07%   |
| 6       | 26        | 0.02%   |
| 7       | 17        | 0.01%   |
| 8       | 5         | 0.004%  |
| 9       | 2         | 0.002%  |
| Unknown | 2         | 0.002%  |
| 10      | 1         | 0.001%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 75443     | 61.57%  |
| Yes       | 47098     | 38.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99667     | 81.59%  |
| No        | 22494     | 18.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119552    | 98.15%  |
| No        | 2249      | 1.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93135     | 75.52%  |
| No        | 30198     | 24.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 17858     | 14.49%  |
| Russia       | 13065     | 10.6%   |
| Germany      | 11206     | 9.09%   |
| Brazil       | 8112      | 6.58%   |
| France       | 5804      | 4.71%   |
| Italy        | 4734      | 3.84%   |
| UK           | 4216      | 3.42%   |
| Unknown      | 3890      | 3.16%   |
| India        | 3496      | 2.84%   |
| Spain        | 3296      | 2.67%   |
| Poland       | 3229      | 2.62%   |
| Canada       | 2961      | 2.4%    |
| Netherlands  | 2311      | 1.88%   |
| Hungary      | 2294      | 1.86%   |
| Ukraine      | 1840      | 1.49%   |
| Mexico       | 1652      | 1.34%   |
| Australia    | 1546      | 1.25%   |
| Turkey       | 1370      | 1.11%   |
| Czechia      | 1367      | 1.11%   |
| Romania      | 1241      | 1.01%   |
| Sweden       | 1170      | 0.95%   |
| Portugal     | 1112      | 0.9%    |
| Switzerland  | 1093      | 0.89%   |
| Belgium      | 1090      | 0.88%   |
| Austria      | 1077      | 0.87%   |
| Argentina    | 1065      | 0.86%   |
| Indonesia    | 948       | 0.77%   |
| China        | 880       | 0.71%   |
| Finland      | 792       | 0.64%   |
| Greece       | 748       | 0.61%   |
| Colombia     | 732       | 0.59%   |
| Chile        | 671       | 0.54%   |
| Belarus      | 655       | 0.53%   |
| Bulgaria     | 654       | 0.53%   |
| South Africa | 640       | 0.52%   |
| Japan        | 635       | 0.52%   |
| Norway       | 631       | 0.51%   |
| Denmark      | 582       | 0.47%   |
| Slovakia     | 472       | 0.38%   |
| Iran         | 457       | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 3913      | 2.95%   |
| Moscow            | 2985      | 2.25%   |
| St Petersburg     | 1280      | 0.97%   |
| Berlin            | 1090      | 0.82%   |
| Sao Paulo         | 991       | 0.75%   |
| Budapest          | 973       | 0.73%   |
| Paris             | 971       | 0.73%   |
| Warsaw            | 779       | 0.59%   |
| Milan             | 732       | 0.55%   |
| Bangor            | 679       | 0.51%   |
| Vienna            | 669       | 0.5%    |
| Prague            | 583       | 0.44%   |
| Madrid            | 577       | 0.44%   |
| Munich            | 576       | 0.43%   |
| Rome              | 544       | 0.41%   |
| Istanbul          | 519       | 0.39%   |
| Kyiv              | 484       | 0.37%   |
| Hamburg           | 456       | 0.34%   |
| Amsterdam         | 455       | 0.34%   |
| Bengaluru         | 446       | 0.34%   |
| Rio de Janeiro    | 445       | 0.34%   |
| Sydney            | 429       | 0.32%   |
| Krasnodar         | 419       | 0.32%   |
| Novosibirsk       | 414       | 0.31%   |
| Bucharest         | 405       | 0.31%   |
| Barcelona         | 402       | 0.3%    |
| Helsinki          | 398       | 0.3%    |
| Athens            | 396       | 0.3%    |
| Voronezh          | 376       | 0.28%   |
| Melbourne         | 372       | 0.28%   |
| Yekaterinburg     | 367       | 0.28%   |
| Sofia             | 363       | 0.27%   |
| Frankfurt am Main | 362       | 0.27%   |
| Mexico City       | 355       | 0.27%   |
| Pecherskoye       | 337       | 0.25%   |
| Minsk             | 329       | 0.25%   |
| London            | 322       | 0.24%   |
| Toronto           | 305       | 0.23%   |
| Bogotá           | 295       | 0.22%   |
| Montreal          | 291       | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 21715     | 29765  | 14.41%  |
| WDC                         | 18718     | 24115  | 12.42%  |
| Seagate                     | 17445     | 22605  | 11.57%  |
| Toshiba                     | 12642     | 15939  | 8.39%   |
| SanDisk                     | 8732      | 11267  | 5.79%   |
| Unknown                     | 8365      | 11030  | 5.55%   |
| Kingston                    | 7693      | 9713   | 5.1%    |
| SK hynix                    | 5680      | 7104   | 3.77%   |
| Hitachi                     | 5616      | 7030   | 3.73%   |
| Intel                       | 4517      | 6009   | 3%      |
| HGST                        | 4478      | 5849   | 2.97%   |
| Crucial                     | 4150      | 5445   | 2.75%   |
| Micron Technology           | 3515      | 4315   | 2.33%   |
| A-DATA Technology           | 2032      | 2637   | 1.35%   |
| Apple                       | 1676      | 2195   | 1.11%   |
| KIOXIA                      | 1473      | 1840   | 0.98%   |
| Fujitsu                     | 1380      | 1625   | 0.92%   |
| China                       | 1273      | 1608   | 0.84%   |
| LITEON                      | 862       | 1053   | 0.57%   |
| Phison                      | 814       | 987    | 0.54%   |
| SPCC                        | 737       | 961    | 0.49%   |
| Unknown                     | 710       | 812    | 0.47%   |
| Phison Electronics          | 678       | 804    | 0.45%   |
| Transcend                   | 639       | 785    | 0.42%   |
| Silicon Motion              | 611       | 766    | 0.41%   |
| PNY                         | 606       | 767    | 0.4%    |
| Kingston Technology Company | 587       | 683    | 0.39%   |
| Intenso                     | 551       | 704    | 0.37%   |
| LITEONIT                    | 493       | 646    | 0.33%   |
| JMicron Technology          | 478       | 531    | 0.32%   |
| Micron/Crucial Technology   | 461       | 566    | 0.31%   |
| Patriot                     | 437       | 542    | 0.29%   |
| GOODRAM                     | 404       | 504    | 0.27%   |
| OCZ                         | 381       | 471    | 0.25%   |
| KingSpec                    | 348       | 437    | 0.23%   |
| Netac                       | 345       | 428    | 0.23%   |
| ADATA Technology            | 342       | 406    | 0.23%   |
| Apacer                      | 282       | 358    | 0.19%   |
| Team                        | 258       | 316    | 0.17%   |
| Plextor                     | 243       | 321    | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 2339      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1847      | 1.18%   |
| Toshiba MQ01ABD100 1TB                              | 1678      | 1.07%   |
| Kingston SA400S37240G 240GB SSD                     | 1509      | 0.96%   |
| Toshiba MQ01ABF050 500GB                            | 1492      | 0.95%   |
| Seagate ST500LT012-1DG142 500GB                     | 1438      | 0.92%   |
| Unknown MMC Card  32GB                              | 1428      | 0.91%   |
| Toshiba MQ04ABF100 1TB                              | 1281      | 0.82%   |
| Unknown MMC Card  64GB                              | 1105      | 0.71%   |
| Seagate ST9500325AS 500GB                           | 1103      | 0.7%    |
| HGST HTS721010A9E630 1TB                            | 1103      | 0.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 1068      | 0.68%   |
| Samsung NVMe SSD Drive 512GB                        | 861       | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 833       | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                        | 817       | 0.52%   |
| Samsung SSD 860 EVO 500GB                           | 814       | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 807       | 0.52%   |
| HGST HTS545050A7E680 500GB                          | 780       | 0.5%    |
| Kingston SA400S37120G 120GB SSD                     | 774       | 0.49%   |
| Unknown                                             | 710       | 0.45%   |
| HGST HTS541010A9E680 1TB                            | 702       | 0.45%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 663       | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 659       | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 659       | 0.42%   |
| Samsung SSD 850 EVO 250GB                           | 647       | 0.41%   |
| Unknown MMC Card  128GB                             | 643       | 0.41%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 607       | 0.39%   |
| Intel NVMe SSD Drive 512GB                          | 607       | 0.39%   |
| Crucial CT500MX500SSD1 500GB                        | 584       | 0.37%   |
| Samsung SSD 850 EVO 500GB                           | 583       | 0.37%   |
| Seagate ST500LT012-9WS142 500GB                     | 547       | 0.35%   |
| Crucial CT240BX500SSD1 240GB                        | 546       | 0.35%   |
| HGST HTS725050A7E630 500GB                          | 529       | 0.34%   |
| SK hynix NVMe SSD Drive 512GB                       | 517       | 0.33%   |
| Seagate ST9320325AS 320GB                           | 509       | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 509       | 0.33%   |
| SanDisk NVMe SSD Drive 256GB                        | 474       | 0.3%    |
| Unknown MMC Card  16GB                              | 464       | 0.3%    |
| WDC WD5000LPVX-22V0TT0 500GB                        | 451       | 0.29%   |
| Seagate ST1000LM048-2E7172 1TB                      | 443       | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17108     | 22075  | 31.23%  |
| WDC                 | 13776     | 17601  | 25.14%  |
| Toshiba             | 9564      | 11916  | 17.46%  |
| Hitachi             | 5615      | 7029   | 10.25%  |
| HGST                | 4477      | 5848   | 8.17%   |
| Samsung Electronics | 1396      | 1703   | 2.55%   |
| Fujitsu             | 1371      | 1611   | 2.5%    |
| Unknown             | 417       | 535    | 0.76%   |
| Apple               | 179       | 212    | 0.33%   |
| SABRENT             | 169       | 193    | 0.31%   |
| TO Exter            | 90        | 112    | 0.16%   |
| External            | 78        | 104    | 0.14%   |
| ASMT                | 56        | 98     | 0.1%    |
| USB3.0              | 54        | 60     | 0.1%    |
| IBM/Hitachi         | 53        | 61     | 0.1%    |
| Intenso             | 45        | 59     | 0.08%   |
| HGST HTS            | 35        | 46     | 0.06%   |
| StoreJet            | 30        | 31     | 0.05%   |
| SSK                 | 27        | 29     | 0.05%   |
| USB                 | 24        | 26     | 0.04%   |
| JMicron Technology  | 24        | 40     | 0.04%   |
| LaCie               | 20        | 25     | 0.04%   |
| SAGE                | 15        | 20     | 0.03%   |
| KESU                | 12        | 12     | 0.02%   |
| Inateck             | 12        | 12     | 0.02%   |
| MARSHAL             | 11        | 13     | 0.02%   |
| Pioneer             | 9         | 19     | 0.02%   |
| Maxone              | 8         | 8      | 0.01%   |
| Initio              | 8         | 9      | 0.01%   |
| Hewlett-Packard     | 8         | 9      | 0.01%   |
| XrayDisk            | 7         | 10     | 0.01%   |
| Apricorn            | 7         | 10     | 0.01%   |
| Generic-            | 6         | 7      | 0.01%   |
| SILICONMOTION       | 5         | 6      | 0.01%   |
| ACASIS              | 5         | 5      | 0.01%   |
| Unknown             | 5         | 5      | 0.01%   |
| ASMedia             | 4         | 4      | 0.01%   |
| QNAP                | 3         | 7      | 0.01%   |
| IBM                 | 3         | 4      | 0.01%   |
| DAS                 | 3         | 13     | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9614      | 12945  | 20.99%  |
| Kingston            | 6057      | 7638   | 13.22%  |
| SanDisk             | 4676      | 6112   | 10.21%  |
| Crucial             | 3782      | 5006   | 8.26%   |
| WDC                 | 2376      | 3053   | 5.19%   |
| A-DATA Technology   | 1564      | 2050   | 3.41%   |
| Intel               | 1280      | 1635   | 2.79%   |
| China               | 1259      | 1588   | 2.75%   |
| Micron Technology   | 1232      | 1542   | 2.69%   |
| SK hynix            | 1191      | 1490   | 2.6%    |
| Apple               | 1058      | 1233   | 2.31%   |
| Toshiba             | 999       | 1277   | 2.18%   |
| LITEON              | 778       | 956    | 1.7%    |
| SPCC                | 664       | 879    | 1.45%   |
| Transcend           | 596       | 733    | 1.3%    |
| PNY                 | 569       | 723    | 1.24%   |
| LITEONIT            | 493       | 646    | 1.08%   |
| Intenso             | 427       | 544    | 0.93%   |
| Patriot             | 420       | 520    | 0.92%   |
| GOODRAM             | 390       | 490    | 0.85%   |
| OCZ                 | 380       | 470    | 0.83%   |
| KingSpec            | 337       | 423    | 0.74%   |
| Netac               | 301       | 373    | 0.66%   |
| JMicron Technology  | 285       | 313    | 0.62%   |
| Apacer              | 254       | 324    | 0.55%   |
| Plextor             | 234       | 311    | 0.51%   |
| Team                | 220       | 274    | 0.48%   |
| Corsair             | 183       | 226    | 0.4%    |
| Hewlett-Packard     | 174       | 237    | 0.38%   |
| Lexar               | 164       | 199    | 0.36%   |
| Unknown             | 161       | 182    | 0.35%   |
| Gigabyte Technology | 139       | 181    | 0.3%    |
| Seagate             | 122       | 151    | 0.27%   |
| KingDian            | 121       | 165    | 0.26%   |
| Smartbuy            | 111       | 131    | 0.24%   |
| ASMT                | 108       | 128    | 0.24%   |
| FORESEE             | 105       | 127    | 0.23%   |
| Dogfish             | 92        | 118    | 0.2%    |
| BHT                 | 91        | 113    | 0.2%    |
| Teclast             | 79        | 92     | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 52875     | 69656  | 36.87%  |
| SSD     | 42534     | 59003  | 29.66%  |
| NVMe    | 37802     | 52301  | 26.36%  |
| MMC     | 8114      | 10771  | 5.66%   |
| Unknown | 2071      | 2510   | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85189     | 124534 | 62.53%  |
| NVMe | 37772     | 52151  | 27.72%  |
| MMC  | 8114      | 10771  | 5.96%   |
| SAS  | 5165      | 6785   | 3.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64529     | 89023  | 68.53%  |
| 0.51-1.0   | 26122     | 34798  | 27.74%  |
| 1.01-2.0   | 2973      | 4050   | 3.16%   |
| 3.01-4.0   | 247       | 364    | 0.26%   |
| 4.01-10.0  | 241       | 359    | 0.26%   |
| 10.01-20.0 | 28        | 33     | 0.03%   |
| 2.01-3.0   | 18        | 28     | 0.02%   |
| 0          | 3         | 4      | 0.003%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 36529     | 28.01%  |
| 251-500        | 32753     | 25.12%  |
| 501-1000       | 18868     | 14.47%  |
| 1-20           | 11020     | 8.45%   |
| 51-100         | 9402      | 7.21%   |
| 1001-2000      | 7017      | 5.38%   |
| 21-50          | 6247      | 4.79%   |
| Unknown        | 4707      | 3.61%   |
| More than 3000 | 2143      | 1.64%   |
| 2001-3000      | 1704      | 1.31%   |
| 0              | 1         | 0.001%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 56992     | 42.13%  |
| 21-50          | 24431     | 18.06%  |
| 101-250        | 16695     | 12.34%  |
| 51-100         | 15661     | 11.58%  |
| 251-500        | 9129      | 6.75%   |
| 501-1000       | 4910      | 3.63%   |
| Unknown        | 4707      | 3.48%   |
| 1001-2000      | 1802      | 1.33%   |
| More than 3000 | 466       | 0.34%   |
| 2001-3000      | 437       | 0.32%   |
| 0              | 38        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 411       | 531    | 3.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 290       | 359    | 2.32%   |
| Seagate ST500LT012-9WS142 500GB     | 286       | 365    | 2.29%   |
| HGST HTS545050A7E680 500GB          | 247       | 325    | 1.97%   |
| Seagate ST500LT012-1DG142 500GB     | 236       | 285    | 1.89%   |
| Seagate ST9320325AS 320GB           | 214       | 269    | 1.71%   |
| Seagate ST1000LM035-1RK172 1TB      | 183       | 201    | 1.46%   |
| Toshiba MQ01ABD100 1TB              | 180       | 216    | 1.44%   |
| HGST HTS541010A9E680 1TB            | 166       | 209    | 1.33%   |
| Seagate ST9250315AS 250GB           | 146       | 177    | 1.17%   |
| Toshiba MQ01ABF050 500GB            | 142       | 195    | 1.13%   |
| HGST HTS545050A7E380 500GB          | 134       | 185    | 1.07%   |
| HGST HTS721010A9E630 1TB            | 132       | 158    | 1.05%   |
| SanDisk SSD U100 256GB              | 128       | 129    | 1.02%   |
| Hitachi HTS543232A7A384 320GB       | 124       | 148    | 0.99%   |
| HGST HTS725050A7E630 500GB          | 121       | 140    | 0.97%   |
| Hitachi HTS547575A9E384 752GB       | 108       | 136    | 0.86%   |
| Hitachi HTS545050A7E380 500GB       | 108       | 132    | 0.86%   |
| Seagate ST9500420AS 500GB           | 103       | 131    | 0.82%   |
| Seagate ST320LT020-9YG142 320GB     | 102       | 149    | 0.82%   |
| Toshiba MQ01ABD050 500GB            | 98        | 119    | 0.78%   |
| Hitachi HTS547550A9E384 500GB       | 93        | 128    | 0.74%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 90        | 106    | 0.72%   |
| Hitachi HTS545050B9A300 500GB       | 90        | 118    | 0.72%   |
| Hitachi HTS545025B9A300 250GB       | 85        | 106    | 0.68%   |
| Toshiba MQ01ABD075 752GB            | 77        | 91     | 0.62%   |
| Hitachi HTS545032B9A300 320GB       | 77        | 90     | 0.62%   |
| Seagate ST500LM021-1KJ152 500GB     | 75        | 83     | 0.6%    |
| Samsung Electronics HM160HI 160GB   | 72        | 91     | 0.58%   |
| Seagate ST320LT012-9WS14C 320GB     | 69        | 93     | 0.55%   |
| Hitachi HTS541612J9SA00 120GB       | 62        | 76     | 0.5%    |
| Toshiba MK3265GSX 320GB             | 61        | 75     | 0.49%   |
| Seagate ST320LT007-9ZV142 320GB     | 59        | 71     | 0.47%   |
| Hitachi HTS542516K9SA00 160GB       | 57        | 78     | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 56        | 64     | 0.45%   |
| Hitachi HTS723232A7A364 320GB       | 56        | 68     | 0.45%   |
| Hitachi HTS541680J9SA00 80GB        | 56        | 68     | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB            | 55        | 66     | 0.44%   |
| Hitachi HTS542512K9SA00 120GB       | 55        | 68     | 0.44%   |
| Toshiba MQ04ABF100 1TB              | 50        | 53     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3292      | 4064   | 26.44%  |
| Hitachi             | 1744      | 2148   | 14.01%  |
| Toshiba             | 1700      | 2093   | 13.65%  |
| WDC                 | 1698      | 2065   | 13.64%  |
| HGST                | 973       | 1240   | 7.82%   |
| Samsung Electronics | 552       | 682    | 4.43%   |
| SanDisk             | 373       | 410    | 3%      |
| SK hynix            | 277       | 320    | 2.22%   |
| Kingston            | 267       | 315    | 2.14%   |
| Fujitsu             | 250       | 304    | 2.01%   |
| Intel               | 218       | 266    | 1.75%   |
| Crucial             | 172       | 217    | 1.38%   |
| Micron Technology   | 133       | 153    | 1.07%   |
| A-DATA Technology   | 118       | 143    | 0.95%   |
| China               | 66        | 79     | 0.53%   |
| LITEON              | 57        | 66     | 0.46%   |
| LITEONIT            | 39        | 53     | 0.31%   |
| Apple               | 39        | 48     | 0.31%   |
| OCZ                 | 38        | 49     | 0.31%   |
| SPCC                | 30        | 31     | 0.24%   |
| KingSpec            | 29        | 40     | 0.23%   |
| Corsair             | 23        | 25     | 0.18%   |
| IBM/Hitachi         | 19        | 19     | 0.15%   |
| Netac               | 18        | 20     | 0.14%   |
| Transcend           | 16        | 19     | 0.13%   |
| Plextor             | 15        | 17     | 0.12%   |
| SSSTC               | 14        | 16     | 0.11%   |
| Unknown             | 14        | 15     | 0.11%   |
| Intenso             | 10        | 11     | 0.08%   |
| Team                | 8         | 9      | 0.06%   |
| Mushkin             | 8         | 8      | 0.06%   |
| Kingmax             | 8         | 8      | 0.06%   |
| JMicron Technology  | 7         | 7      | 0.06%   |
| ASMT                | 7         | 8      | 0.06%   |
| AMD                 | 7         | 9      | 0.06%   |
| PNY                 | 6         | 12     | 0.05%   |
| Patriot             | 6         | 8      | 0.05%   |
| Lenovo              | 6         | 7      | 0.05%   |
| HGST HTS            | 6         | 8      | 0.05%   |
| Hewlett-Packard     | 6         | 6      | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3291      | 4063   | 33.37%  |
| Hitachi             | 1744      | 2148   | 17.68%  |
| Toshiba             | 1641      | 2019   | 16.64%  |
| WDC                 | 1581      | 1942   | 16.03%  |
| HGST                | 973       | 1240   | 9.87%   |
| Samsung Electronics | 317       | 395    | 3.21%   |
| Fujitsu             | 250       | 304    | 2.53%   |
| IBM/Hitachi         | 19        | 19     | 0.19%   |
| Apple               | 17        | 19     | 0.17%   |
| HGST HTS            | 6         | 8      | 0.06%   |
| MARSHAL             | 5         | 6      | 0.05%   |
| Unknown             | 2         | 2      | 0.02%   |
| ASMT                | 2         | 2      | 0.02%   |
| USB3.0              | 1         | 2      | 0.01%   |
| USB                 | 1         | 1      | 0.01%   |
| SAGE                | 1         | 1      | 0.01%   |
| SABRENT             | 1         | 1      | 0.01%   |
| Magnetic Data       | 1         | 1      | 0.01%   |
| LaCie               | 1         | 1      | 0.01%   |
| JMicron Technology  | 1         | 1      | 0.01%   |
| Initio              | 1         | 2      | 0.01%   |
| Inateck             | 1         | 1      | 0.01%   |
| IBM                 | 1         | 1      | 0.01%   |
| External            | 1         | 1      | 0.01%   |
| CSD                 | 1         | 2      | 0.01%   |
| ASMedia             | 1         | 1      | 0.01%   |
| Apricorn            | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 9718      | 12184  | 79.08%  |
| SSD     | 2248      | 2672   | 18.29%  |
| NVMe    | 319       | 376    | 2.6%    |
| Unknown | 4         | 4      | 0.03%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB     | 8         | 8      | 2.61%   |
| Seagate ST9500325AS 500GB           | 7         | 9      | 2.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 7      | 2.28%   |
| Samsung Electronics HM321HI 320GB   | 7         | 8      | 2.28%   |
| HGST HTS721010A9E630 1TB            | 7         | 8      | 2.28%   |
| Seagate ST9320325AS 320GB           | 6         | 6      | 1.95%   |
| Hitachi HTS545050A7E380 500GB       | 6         | 7      | 1.95%   |
| HGST HTS545050A7E680 500GB          | 6         | 6      | 1.95%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 6      | 1.63%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 5         | 6      | 1.63%   |
| Toshiba MQ01ABD100 1TB              | 5         | 5      | 1.63%   |
| HGST HTS541010A9E680 1TB            | 5         | 5      | 1.63%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 4         | 10     | 1.3%    |
| Toshiba MK6465GSX 640GB             | 4         | 6      | 1.3%    |
| Toshiba MK3265GSX 320GB             | 4         | 4      | 1.3%    |
| Hitachi HTS547550A9E384 500GB       | 4         | 4      | 1.3%    |
| WDC WD7500BPVT-22HXZT1 752GB        | 3         | 4      | 0.98%   |
| WDC WD5000BEVT-22ZAT0 500GB         | 3         | 3      | 0.98%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 3         | 3      | 0.98%   |
| WDC WD2500BEVT-22A23T0 250GB        | 3         | 4      | 0.98%   |
| WDC WD10SPZX-21Z10T0 1TB            | 3         | 3      | 0.98%   |
| Toshiba MQ01ABD050 500GB            | 3         | 3      | 0.98%   |
| Toshiba MK6475GSX 640GB             | 3         | 3      | 0.98%   |
| Toshiba MK5065GSXN 500GB            | 3         | 3      | 0.98%   |
| Toshiba MK3259GSXP 320GB            | 3         | 4      | 0.98%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 3      | 0.98%   |
| Samsung Electronics SSD 980 1TB     | 3         | 3      | 0.98%   |
| Samsung Electronics HM160HI 160GB   | 3         | 3      | 0.98%   |
| Hitachi HTS547575A9E384 752GB       | 3         | 4      | 0.98%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 3      | 0.98%   |
| Crucial CT500P2SSD8 500GB           | 3         | 3      | 0.98%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 2         | 2      | 0.65%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 2         | 2      | 0.65%   |
| WDC WD3200BEVT-11ZCT0 320GB         | 2         | 2      | 0.65%   |
| WDC WD2500LPCX-24C6HT0 250GB        | 2         | 2      | 0.65%   |
| WDC WD2500BEVS-22UST0 250GB         | 2         | 2      | 0.65%   |
| WDC WD1600BEVS-22RST0 160GB         | 2         | 2      | 0.65%   |
| Toshiba MK3275GSX 320GB             | 2         | 2      | 0.65%   |
| Toshiba MK3265GSXN 320GB            | 2         | 2      | 0.65%   |
| Toshiba MK2565GSX 250GB             | 2         | 2      | 0.65%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 82        | 94     | 26.71%  |
| Toshiba                 | 55        | 63     | 17.92%  |
| Seagate                 | 49        | 55     | 15.96%  |
| Samsung Electronics     | 41        | 47     | 13.36%  |
| Hitachi                 | 29        | 32     | 9.45%   |
| HGST                    | 23        | 25     | 7.49%   |
| Intel                   | 5         | 5      | 1.63%   |
| Crucial                 | 4         | 4      | 1.3%    |
| SK hynix                | 3         | 3      | 0.98%   |
| SanDisk                 | 2         | 2      | 0.65%   |
| Fujitsu                 | 2         | 2      | 0.65%   |
| Apple                   | 2         | 3      | 0.65%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.33%   |
| Phison                  | 1         | 1      | 0.33%   |
| Micron Technology       | 1         | 1      | 0.33%   |
| Maxtor                  | 1         | 1      | 0.33%   |
| LITEON                  | 1         | 2      | 0.33%   |
| Kingston                | 1         | 1      | 0.33%   |
| JMicron Technology      | 1         | 1      | 0.33%   |
| Intenso                 | 1         | 1      | 0.33%   |
| Acer                    | 1         | 1      | 0.33%   |
| A-DATA Technology       | 1         | 1      | 0.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 66846     | 105466 | 51.36%  |
| Works    | 50866     | 73185  | 39.08%  |
| Malfunc  | 12137     | 15236  | 9.32%   |
| Failed   | 307       | 346    | 0.24%   |
| Fixed    | 4         | 4      | 0.003%  |
| Limited  | 4         | 4      | 0.003%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 84733     | 60.58%  |
| AMD                                     | 14842     | 10.61%  |
| Samsung Electronics                     | 12004     | 8.58%   |
| SanDisk                                 | 6364      | 4.55%   |
| SK hynix                                | 4356      | 3.11%   |
| Micron Technology                       | 2299      | 1.64%   |
| Kingston Technology Company             | 2198      | 1.57%   |
| Toshiba America Info Systems            | 2187      | 1.56%   |
| Phison Electronics                      | 1651      | 1.18%   |
| KIOXIA                                  | 1515      | 1.08%   |
| Nvidia                                  | 1448      | 1.04%   |
| ADATA Technology                        | 821       | 0.59%   |
| Micron/Crucial Technology               | 800       | 0.57%   |
| Silicon Motion                          | 789       | 0.56%   |
| Silicon Integrated Systems [SiS]        | 443       | 0.32%   |
| Solid State Storage Technology          | 437       | 0.31%   |
| Union Memory (Shenzhen)                 | 435       | 0.31%   |
| Apple                                   | 412       | 0.29%   |
| Realtek Semiconductor                   | 268       | 0.19%   |
| Lite-On Technology                      | 203       | 0.15%   |
| Marvell Technology Group                | 185       | 0.13%   |
| O2 Micro                                | 170       | 0.12%   |
| MAXIO Technology (Hangzhou)             | 166       | 0.12%   |
| Lenovo                                  | 166       | 0.12%   |
| Shenzhen Longsys Electronics            | 148       | 0.11%   |
| JMicron Technology                      | 131       | 0.09%   |
| VIA Technologies                        | 128       | 0.09%   |
| Yangtze Memory Technologies             | 103       | 0.07%   |
| INNOGRIT                                | 88        | 0.06%   |
| Seagate Technology                      | 70        | 0.05%   |
| ASMedia Technology                      | 54        | 0.04%   |
| Biwin Storage Technology                | 49        | 0.04%   |
| Silicon Image                           | 44        | 0.03%   |
| Solidigm                                | 30        | 0.02%   |
| Netac Technology                        | 29        | 0.02%   |
| Transcend                               | 22        | 0.02%   |
| Shenzhen Unionmemory Information System | 19        | 0.01%   |
| Unknown                                 | 13        | 0.01%   |
| ULi Electronics                         | 10        | 0.01%   |
| Shenzhen Shichuangyi Electronics        | 7         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 11822     | 7.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9883      | 6.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 9356      | 6.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 7194      | 4.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6952      | 4.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5264      | 3.48%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4478      | 2.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4409      | 2.92%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3343      | 2.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 3329      | 2.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3299      | 2.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3057      | 2.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3050      | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3045      | 2.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2699      | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2277      | 1.51%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2075      | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1981      | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1870      | 1.24%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1692      | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1650      | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1579      | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1577      | 1.04%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1551      | 1.03%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1509      | 1%      |
| Intel Comet Lake SATA AHCI Controller                                            | 1490      | 0.99%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 1425      | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1389      | 0.92%   |
| Intel SSD 660P Series                                                            | 1286      | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1244      | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1212      | 0.8%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1172      | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1121      | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 1021      | 0.68%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 958       | 0.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 898       | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 860       | 0.57%   |
| Nvidia MCP79 AHCI Controller                                                     | 853       | 0.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 838       | 0.55%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 811       | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 86331     | 59.51%  |
| NVMe | 38017     | 26.21%  |
| RAID | 10722     | 7.39%   |
| IDE  | 9996      | 6.89%   |
| SAS  | 1         | 0.001%  |
| SCSI | 1         | 0.001%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 99384     | 81.68%  |
| AMD          | 22147     | 18.2%   |
| ARM          | 65        | 0.05%   |
| CentaurHauls | 35        | 0.03%   |
| Unknown      | 24        | 0.02%   |
| Phytium      | 6         | 0.005%  |
| Qualcomm     | 4         | 0.003%  |
| PowerBook5,6 | 2         | 0.002%  |
| PowerBook5,4 | 1         | 0.001%  |
| PowerBook3,4 | 1         | 0.001%  |
| GenuineTMx86 | 1         | 0.001%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 1874      | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1647      | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1622      | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1545      | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1387      | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1305      | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1295      | 1.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1256      | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1243      | 1.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1237      | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1229      | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1185      | 0.97%   |
| AMD Custom APU 0405                           | 1146      | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1145      | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1110      | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1058      | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1030      | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1007      | 0.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 996       | 0.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 910       | 0.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 875       | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 860       | 0.71%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 858       | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 854       | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 834       | 0.68%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 791       | 0.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 775       | 0.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 770       | 0.63%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 756       | 0.62%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 737       | 0.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 733       | 0.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 719       | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 694       | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 691       | 0.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 676       | 0.55%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 649       | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 644       | 0.53%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 643       | 0.53%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 633       | 0.52%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 617       | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 28518     | 23.42%  |
| Intel Core i7           | 24325     | 19.97%  |
| Intel Core i3           | 10723     | 8.8%    |
| Other                   | 10382     | 8.52%   |
| Intel Celeron           | 7540      | 6.19%   |
| Intel Core 2 Duo        | 6422      | 5.27%   |
| AMD Ryzen 5             | 4599      | 3.78%   |
| AMD Ryzen 7             | 4016      | 3.3%    |
| Intel Pentium           | 3767      | 3.09%   |
| Intel Atom              | 3259      | 2.68%   |
| AMD A6                  | 1394      | 1.14%   |
| Intel Pentium Dual-Core | 1316      | 1.08%   |
| AMD Ryzen 3             | 980       | 0.8%    |
| AMD A8                  | 957       | 0.79%   |
| AMD A4                  | 936       | 0.77%   |
| AMD E                   | 781       | 0.64%   |
| Intel Pentium Dual      | 776       | 0.64%   |
| AMD A10                 | 772       | 0.63%   |
| Intel Core 2            | 746       | 0.61%   |
| AMD Ryzen 7 PRO         | 740       | 0.61%   |
| AMD Ryzen 9             | 726       | 0.6%    |
| Intel Genuine           | 724       | 0.59%   |
| AMD E1                  | 684       | 0.56%   |
| AMD E2                  | 532       | 0.44%   |
| Intel Pentium Silver    | 469       | 0.39%   |
| Intel Core i9           | 453       | 0.37%   |
| AMD Turion 64 X2 Mobile | 369       | 0.3%    |
| Intel Celeron M         | 341       | 0.28%   |
| Intel Pentium M         | 326       | 0.27%   |
| Intel Celeron Dual-Core | 297       | 0.24%   |
| AMD Ryzen 5 PRO         | 285       | 0.23%   |
| AMD Athlon              | 279       | 0.23%   |
| AMD Athlon II           | 246       | 0.2%    |
| Intel Xeon              | 212       | 0.17%   |
| AMD Phenom II           | 190       | 0.16%   |
| AMD C-60                | 185       | 0.15%   |
| AMD A12                 | 167       | 0.14%   |
| Intel Core m3           | 162       | 0.13%   |
| AMD Athlon X2           | 157       | 0.13%   |
| AMD Athlon 64 X2        | 127       | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 64837     | 53.17%  |
| 4       | 36331     | 29.8%   |
| 6       | 7343      | 6.02%   |
| 8       | 6301      | 5.17%   |
| 1       | 3692      | 3.03%   |
| 14      | 990       | 0.81%   |
| 10      | 806       | 0.66%   |
| 12      | 754       | 0.62%   |
| Unknown | 601       | 0.49%   |
| 16      | 106       | 0.09%   |
| 3       | 76        | 0.06%   |
| 24      | 74        | 0.06%   |
| 5       | 16        | 0.01%   |
| 192     | 2         | 0.002%  |
| 20      | 2         | 0.002%  |
| 128     | 1         | 0.001%  |
| 32      | 1         | 0.001%  |
| 9       | 1         | 0.001%  |
| 7       | 1         | 0.001%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 121564    | 99.89%  |
| Unknown | 93        | 0.08%   |
| 2       | 34        | 0.03%   |
| 4       | 6         | 0.005%  |
| 3       | 2         | 0.002%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 86951     | 71.25%  |
| 1       | 34444     | 28.22%  |
| Unknown | 601       | 0.49%   |
| 4       | 24        | 0.02%   |
| 8       | 18        | 0.01%   |
| 12      | 2         | 0.002%  |
| 16      | 1         | 0.001%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 117965    | 96.61%  |
| Unknown        | 2172      | 1.78%   |
| 32-bit         | 1845      | 1.51%   |
| 64-bit         | 118       | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32890     | 26%     |
| 0x206a7    | 8073      | 6.38%   |
| 0x306a9    | 7391      | 5.84%   |
| 0x1067a    | 4175      | 3.3%    |
| 0x40651    | 3830      | 3.03%   |
| 0x806ea    | 3594      | 2.84%   |
| 0x806ec    | 3571      | 2.82%   |
| 0x406e3    | 3312      | 2.62%   |
| 0x20655    | 3143      | 2.48%   |
| 0x806c1    | 3055      | 2.41%   |
| 0x306d4    | 3053      | 2.41%   |
| 0x806e9    | 2991      | 2.36%   |
| 0x906ea    | 2852      | 2.25%   |
| 0x306c3    | 2584      | 2.04%   |
| 0x6fd      | 2076      | 1.64%   |
| 0x30678    | 1806      | 1.43%   |
| 0x0a50000c | 1439      | 1.14%   |
| 0x08108109 | 1400      | 1.11%   |
| 0x406c4    | 1333      | 1.05%   |
| 0xa0652    | 1314      | 1.04%   |
| 0x906e9    | 1263      | 1%      |
| 0x10676    | 1261      | 1%      |
| 0x706e5    | 1171      | 0.93%   |
| 0x20652    | 1163      | 0.92%   |
| 0x08108102 | 1115      | 0.88%   |
| 0x08600106 | 1052      | 0.83%   |
| 0x506e3    | 1036      | 0.82%   |
| 0x106ca    | 977       | 0.77%   |
| 0x806eb    | 935       | 0.74%   |
| 0x08608103 | 917       | 0.72%   |
| 0x06006705 | 907       | 0.72%   |
| 0x706a1    | 856       | 0.68%   |
| 0x506c9    | 820       | 0.65%   |
| 0x05000119 | 812       | 0.64%   |
| 0x906a3    | 806       | 0.64%   |
| 0x406c3    | 771       | 0.61%   |
| 0x07030105 | 766       | 0.61%   |
| 0x706a8    | 697       | 0.55%   |
| 0x06001119 | 659       | 0.52%   |
| 0x806d1    | 641       | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 21159     | 17.36%  |
| SandyBridge       | 9909      | 8.13%   |
| IvyBridge         | 9359      | 7.68%   |
| Haswell           | 8660      | 7.11%   |
| Penryn            | 6422      | 5.27%   |
| Skylake           | 6019      | 4.94%   |
| Westmere          | 5236      | 4.3%    |
| Unknown           | 5124      | 4.2%    |
| Silvermont        | 4930      | 4.05%   |
| TigerLake         | 4684      | 3.84%   |
| Core              | 4204      | 3.45%   |
| Broadwell         | 4094      | 3.36%   |
| Zen+              | 3062      | 2.51%   |
| Zen 2             | 2791      | 2.29%   |
| Zen 3             | 2478      | 2.03%   |
| Icelake           | 2384      | 1.96%   |
| CometLake         | 2153      | 1.77%   |
| Goldmont plus     | 2106      | 1.73%   |
| Alderlake Hybrid  | 2089      | 1.71%   |
| Excavator         | 2040      | 1.67%   |
| Bonnell           | 1921      | 1.58%   |
| Bobcat            | 1500      | 1.23%   |
| Puma              | 1243      | 1.02%   |
| Goldmont          | 1102      | 0.9%    |
| P6                | 1078      | 0.88%   |
| Piledriver        | 939       | 0.77%   |
| Zen               | 905       | 0.74%   |
| K10               | 820       | 0.67%   |
| K8 Hammer         | 803       | 0.66%   |
| Jaguar            | 725       | 0.59%   |
| K10 Llano         | 614       | 0.5%    |
| Nehalem           | 434       | 0.36%   |
| K8 & K10 hybrid   | 401       | 0.33%   |
| Steamroller       | 192       | 0.16%   |
| Tremont           | 191       | 0.16%   |
| NetBurst          | 67        | 0.05%   |
| Gracemont         | 21        | 0.02%   |
| K6                | 3         | 0.002%  |
| Meteorlake Hybrid | 1         | 0.001%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 89417     | 58.12%  |
| Nvidia                           | 33870     | 22.01%  |
| AMD                              | 30100     | 19.56%  |
| Silicon Integrated Systems [SiS] | 318       | 0.21%   |
| VIA Technologies                 | 111       | 0.07%   |
| Zhaoxin                          | 13        | 0.01%   |
| ATI Technologies                 | 11        | 0.01%   |
| S3 Graphics                      | 7         | 0.005%  |
| Neomagic                         | 5         | 0.003%  |
| ASPEED Technology                | 5         | 0.003%  |
| Silicon Motion                   | 2         | 0.001%  |
| Trident Microsystems             | 1         | 0.001%  |
| Nanjing Ruixinview Technology    | 1         | 0.001%  |
| Matrox Electronics Systems       | 1         | 0.001%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9008      | 5.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8849      | 5.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4916      | 3.08%   |
| Intel UHD Graphics 620                                                                   | 4530      | 2.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4062      | 2.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3978      | 2.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3936      | 2.46%   |
| Intel HD Graphics 620                                                                    | 3786      | 2.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3684      | 2.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3657      | 2.29%   |
| Intel HD Graphics 5500                                                                   | 3277      | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3237      | 2.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3163      | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3159      | 1.98%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2682      | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2542      | 1.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2540      | 1.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2387      | 1.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2134      | 1.34%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 1901      | 1.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1859      | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1859      | 1.16%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1755      | 1.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1733      | 1.08%   |
| Intel HD Graphics 630                                                                    | 1531      | 0.96%   |
| AMD Lucienne                                                                             | 1460      | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1435      | 0.9%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1419      | 0.89%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1334      | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1316      | 0.82%   |
| Intel HD Graphics 530                                                                    | 1261      | 0.79%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 1247      | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1173      | 0.73%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 1120      | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1078      | 0.67%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1073      | 0.67%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1020      | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1001      | 0.63%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 989       | 0.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 988       | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 59511     | 48.74%  |
| Intel + Nvidia                    | 24393     | 19.98%  |
| 1 x AMD                           | 19920     | 16.31%  |
| 1 x Nvidia                        | 6831      | 5.59%   |
| Intel + AMD                       | 5111      | 4.19%   |
| AMD + Nvidia                      | 2596      | 2.13%   |
| 2 x AMD                           | 2517      | 2.06%   |
| 2 x Intel                         | 407       | 0.33%   |
| 1 x SiS                           | 318       | 0.26%   |
| Other                             | 230       | 0.19%   |
| 1 x VIA                           | 111       | 0.09%   |
| 2 x Nvidia                        | 99        | 0.08%   |
| Intel + 2 x Nvidia                | 16        | 0.01%   |
| 1 x Zhaoxin                       | 13        | 0.01%   |
| 1 x S3 Graphics                   | 7         | 0.01%   |
| Intel + AMD + 1 x Nvidia          | 6         | 0.005%  |
| 1 x Neomagic                      | 5         | 0.004%  |
| Nvidia + ASPEED                   | 3         | 0.002%  |
| 2 x Intel + 1 x Nvidia            | 2         | 0.002%  |
| 1 x Silicon Motion                | 2         | 0.002%  |
| 1 x Trident Microsystems          | 1         | 0.001%  |
| Nvidia + Matrox                   | 1         | 0.001%  |
| 1 x Nanjing Ruixinview Technology | 1         | 0.001%  |
| Intel + ASPEED                    | 1         | 0.001%  |
| 1 x ASPEED                        | 1         | 0.001%  |
| AMD + 2 x Nvidia                  | 1         | 0.001%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 104322    | 84.42%  |
| Proprietary | 15669     | 12.68%  |
| Unknown     | 3581      | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 75434     | 60.22%  |
| 0.01-0.5       | 17090     | 13.64%  |
| 1.01-2.0       | 16919     | 13.51%  |
| 0.51-1.0       | 6555      | 5.23%   |
| 3.01-4.0       | 6291      | 5.02%   |
| 5.01-6.0       | 1520      | 1.21%   |
| 7.01-8.0       | 963       | 0.77%   |
| 2.01-3.0       | 323       | 0.26%   |
| 8.01-16.0      | 164       | 0.13%   |
| 16.01-24.0     | 4         | 0.003%  |
| More than 64.0 | 1         | 0.001%  |
| 0              | 1         | 0.001%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25680     | 19.04%  |
| LG Display              | 19521     | 14.48%  |
| BOE                     | 17281     | 12.81%  |
| Chimei Innolux          | 17256     | 12.8%   |
| Samsung Electronics     | 14517     | 10.76%  |
| Chi Mei Optoelectronics | 4013      | 2.98%   |
| Apple                   | 3501      | 2.6%    |
| Dell                    | 3228      | 2.39%   |
| Sharp                   | 3220      | 2.39%   |
| Lenovo                  | 2654      | 1.97%   |
| Goldstar                | 2617      | 1.94%   |
| PANDA                   | 1940      | 1.44%   |
| LG Philips              | 1480      | 1.1%    |
| Hewlett-Packard         | 1460      | 1.08%   |
| InfoVision              | 1279      | 0.95%   |
| Acer                    | 1147      | 0.85%   |
| AOC                     | 957       | 0.71%   |
| Philips                 | 945       | 0.7%    |
| BenQ                    | 922       | 0.68%   |
| Valve                   | 816       | 0.61%   |
| CPT                     | 696       | 0.52%   |
| CSO                     | 681       | 0.5%    |
| HannStar                | 674       | 0.5%    |
| Ancor Communications    | 674       | 0.5%    |
| Sony                    | 581       | 0.43%   |
| Iiyama                  | 472       | 0.35%   |
| ASUSTek Computer        | 386       | 0.29%   |
| ViewSonic               | 378       | 0.28%   |
| Toshiba                 | 301       | 0.22%   |
| Panasonic               | 262       | 0.19%   |
| InnoLux Display         | 260       | 0.19%   |
| TMX                     | 237       | 0.18%   |
| LGD                     | 215       | 0.16%   |
| Eizo                    | 190       | 0.14%   |
| Quanta Display          | 187       | 0.14%   |
| Analogix                | 173       | 0.13%   |
| Unknown                 | 164       | 0.12%   |
| Seiko/Epson             | 151       | 0.11%   |
| Vizio                   | 141       | 0.1%    |
| MSI                     | 134       | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1077      | 0.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1001      | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 963       | 0.71%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 881       | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 879       | 0.64%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 868       | 0.64%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 867       | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 818       | 0.6%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 788       | 0.58%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 665       | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 658       | 0.48%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 530       | 0.39%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 484       | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 482       | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 471       | 0.35%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 452       | 0.33%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 423       | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 414       | 0.3%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 405       | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 380       | 0.28%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 377       | 0.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 366       | 0.27%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 363       | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 355       | 0.26%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 349       | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 342       | 0.25%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 342       | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 341       | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 339       | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 333       | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 330       | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 329       | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 328       | 0.24%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 322       | 0.24%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 315       | 0.23%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 313       | 0.23%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 313       | 0.23%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 308       | 0.23%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 304       | 0.22%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 302       | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48410     | 37.76%  |
| 1366x768 (WXGA)    | 42140     | 32.87%  |
| 1600x900 (HD+)     | 7218      | 5.63%   |
| 1280x800 (WXGA)    | 6338      | 4.94%   |
| 3840x2160 (4K)     | 4264      | 3.33%   |
| 2560x1440 (QHD)    | 2814      | 2.2%    |
| 1440x900 (WXGA+)   | 2513      | 1.96%   |
| 1920x1200 (WUXGA)  | 2423      | 1.89%   |
| 2560x1600          | 1423      | 1.11%   |
| 1024x600           | 1328      | 1.04%   |
| 1680x1050 (WSXGA+) | 1097      | 0.86%   |
| 800x1280           | 965       | 0.75%   |
| 2880x1800          | 867       | 0.68%   |
| 1280x1024 (SXGA)   | 768       | 0.6%    |
| 2560x1080          | 572       | 0.45%   |
| 3440x1440          | 519       | 0.4%    |
| 3840x2400          | 513       | 0.4%    |
| 2160x1440          | 416       | 0.32%   |
| 1360x768           | 411       | 0.32%   |
| 3200x1800 (QHD+)   | 350       | 0.27%   |
| 1024x768 (XGA)     | 297       | 0.23%   |
| Unknown            | 223       | 0.17%   |
| 2256x1504          | 217       | 0.17%   |
| 1920x540           | 196       | 0.15%   |
| 3200x2000          | 130       | 0.1%    |
| 3840x1080          | 128       | 0.1%    |
| 3000x2000          | 123       | 0.1%    |
| 3072x1920          | 121       | 0.09%   |
| 1680x945           | 107       | 0.08%   |
| 3456x2160          | 103       | 0.08%   |
| 2288x1287          | 101       | 0.08%   |
| 1280x720 (HD)      | 86        | 0.07%   |
| 1400x1050          | 81        | 0.06%   |
| 1920x1280          | 79        | 0.06%   |
| 1600x1200          | 79        | 0.06%   |
| 2240x1400          | 76        | 0.06%   |
| 2520x1680          | 67        | 0.05%   |
| 2880x1620          | 55        | 0.04%   |
| 3840x1600          | 52        | 0.04%   |
| 2304x1440          | 39        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 58178     | 43.16%  |
| 13      | 18036     | 13.38%  |
| 14      | 15909     | 11.8%   |
| 17      | 10052     | 7.46%   |
| 24      | 3725      | 2.76%   |
| 27      | 3519      | 2.61%   |
| 12      | 3234      | 2.4%    |
| 23      | 2887      | 2.14%   |
| 11      | 2731      | 2.03%   |
| 21      | 2378      | 1.76%   |
| 16      | 1769      | 1.31%   |
| Unknown | 1501      | 1.11%   |
| 10      | 1496      | 1.11%   |
| 18      | 1156      | 0.86%   |
| 31      | 1110      | 0.82%   |
| 34      | 966       | 0.72%   |
| 7       | 817       | 0.61%   |
| 19      | 798       | 0.59%   |
| 22      | 523       | 0.39%   |
| 20      | 462       | 0.34%   |
| 84      | 368       | 0.27%   |
| 40      | 345       | 0.26%   |
| 72      | 311       | 0.23%   |
| 54      | 284       | 0.21%   |
| 32      | 281       | 0.21%   |
| 25      | 192       | 0.14%   |
| 3       | 174       | 0.13%   |
| 26      | 142       | 0.11%   |
| 8       | 129       | 0.1%    |
| 28      | 112       | 0.08%   |
| 52      | 111       | 0.08%   |
| 48      | 100       | 0.07%   |
| 37      | 90        | 0.07%   |
| 29      | 82        | 0.06%   |
| 46      | 67        | 0.05%   |
| 86      | 65        | 0.05%   |
| 49      | 64        | 0.05%   |
| 65      | 62        | 0.05%   |
| 142     | 56        | 0.04%   |
| 35      | 53        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 83049     | 62.09%  |
| 201-300        | 16234     | 12.14%  |
| 351-400        | 12159     | 9.09%   |
| 501-600        | 9500      | 7.1%    |
| 401-500        | 4854      | 3.63%   |
| 601-700        | 1695      | 1.27%   |
| Unknown        | 1501      | 1.12%   |
| 701-800        | 1322      | 0.99%   |
| 1-100          | 969       | 0.72%   |
| 1001-1500      | 873       | 0.65%   |
| 1501-2000      | 747       | 0.56%   |
| 801-900        | 549       | 0.41%   |
| 101-200        | 141       | 0.11%   |
| 901-1000       | 112       | 0.08%   |
| More than 2000 | 58        | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 99301     | 82.09%  |
| 16/10   | 15447     | 12.77%  |
| 3/2     | 1261      | 1.04%   |
| 21/9    | 1129      | 0.93%   |
| Unknown | 1071      | 0.89%   |
| 0.67    | 789       | 0.65%   |
| 5/4     | 748       | 0.62%   |
| 4/3     | 578       | 0.48%   |
| 6/5     | 216       | 0.18%   |
| 32/9    | 131       | 0.11%   |
| 0.56    | 70        | 0.06%   |
| 1.00    | 60        | 0.05%   |
| 0.62    | 57        | 0.05%   |
| 3.40    | 34        | 0.03%   |
| 3.73    | 16        | 0.01%   |
| 1.96    | 14        | 0.01%   |
| 2.65    | 13        | 0.01%   |
| 3.20    | 10        | 0.01%   |
| 0.89    | 4         | 0.003%  |
| 0.63    | 4         | 0.003%  |
| 2.00    | 3         | 0.002%  |
| 3.33    | 2         | 0.002%  |
| 2.12    | 2         | 0.002%  |
| 0.65    | 2         | 0.002%  |
| 3.88    | 1         | 0.001%  |
| 2.50    | 1         | 0.001%  |
| 2.21    | 1         | 0.001%  |
| 2.01    | 1         | 0.001%  |
| 1.03    | 1         | 0.001%  |
| 0.58    | 1         | 0.001%  |
| 0.00    | 1         | 0.001%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58043     | 43.15%  |
| 81-90          | 27427     | 20.39%  |
| 121-130        | 8329      | 6.19%   |
| 201-250        | 7727      | 5.74%   |
| 71-80          | 6295      | 4.68%   |
| 301-350        | 3628      | 2.7%    |
| 61-70          | 3101      | 2.31%   |
| 51-60          | 2773      | 2.06%   |
| 351-500        | 2523      | 1.88%   |
| 151-200        | 1895      | 1.41%   |
| 131-140        | 1532      | 1.14%   |
| 111-120        | 1506      | 1.12%   |
| Unknown        | 1502      | 1.12%   |
| 41-50          | 1498      | 1.11%   |
| More than 1000 | 1496      | 1.11%   |
| 141-150        | 1390      | 1.03%   |
| 251-300        | 1317      | 0.98%   |
| 1-40           | 1106      | 0.82%   |
| 501-1000       | 829       | 0.62%   |
| 91-100         | 603       | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 48544     | 36.73%  |
| 101-120       | 46484     | 35.17%  |
| 51-100        | 21297     | 16.12%  |
| 161-240       | 9102      | 6.89%   |
| More than 240 | 3746      | 2.83%   |
| Unknown       | 1501      | 1.14%   |
| 1-50          | 1480      | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 102062    | 81.78%  |
| 2     | 17505     | 14.03%  |
| 0     | 3285      | 2.63%   |
| 3     | 1817      | 1.46%   |
| 4     | 123       | 0.1%    |
| 5     | 11        | 0.01%   |
| 6     | 2         | 0.002%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 65067     | 33.11%  |
| Intel                             | 58218     | 29.62%  |
| Qualcomm Atheros                  | 31520     | 16.04%  |
| Broadcom                          | 14297     | 7.28%   |
| Broadcom Limited                  | 3696      | 1.88%   |
| Marvell Technology Group          | 2739      | 1.39%   |
| MediaTek                          | 2730      | 1.39%   |
| Ralink                            | 2141      | 1.09%   |
| ASIX Electronics                  | 1219      | 0.62%   |
| Nvidia                            | 1131      | 0.58%   |
| TP-Link                           | 1109      | 0.56%   |
| Ralink Technology                 | 1043      | 0.53%   |
| Samsung Electronics               | 909       | 0.46%   |
| Huawei Technologies               | 787       | 0.4%    |
| Dell                              | 778       | 0.4%    |
| JMicron Technology                | 677       | 0.34%   |
| Sierra Wireless                   | 657       | 0.33%   |
| Ericsson Business Mobile Networks | 631       | 0.32%   |
| Xiaomi                            | 582       | 0.3%    |
| Lenovo                            | 579       | 0.29%   |
| DisplayLink                       | 560       | 0.28%   |
| Qualcomm                          | 514       | 0.26%   |
| Hewlett-Packard                   | 479       | 0.24%   |
| Silicon Integrated Systems [SiS]  | 370       | 0.19%   |
| Qualcomm Atheros Communications   | 293       | 0.15%   |
| Attansic Technology               | 279       | 0.14%   |
| ASUSTek Computer                  | 226       | 0.12%   |
| NetGear                           | 224       | 0.11%   |
| D-Link                            | 213       | 0.11%   |
| Motorola PCS                      | 165       | 0.08%   |
| Fibocom                           | 158       | 0.08%   |
| OPPO Electronics                  | 151       | 0.08%   |
| Google                            | 147       | 0.07%   |
| Apple                             | 146       | 0.07%   |
| Edimax Technology                 | 128       | 0.07%   |
| ZTE WCDMA Technologies MSM        | 121       | 0.06%   |
| ICS Advent                        | 104       | 0.05%   |
| VIA Technologies                  | 100       | 0.05%   |
| Linksys                           | 90        | 0.05%   |
| D-Link System                     | 89        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 37715     | 16.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 13417     | 5.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5382      | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5061      | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4713      | 2.01%   |
| Intel Wi-Fi 6 AX200                                                     | 4580      | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4572      | 1.95%   |
| Intel Wireless 8265 / 8275                                              | 4361      | 1.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4307      | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 3879      | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3708      | 1.58%   |
| Intel Wireless 7260                                                     | 3496      | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3469      | 1.48%   |
| Intel Wi-Fi 6 AX201                                                     | 3439      | 1.47%   |
| Intel Wireless 7265                                                     | 3413      | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2935      | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2877      | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2623      | 1.12%   |
| Intel Wireless 8260                                                     | 2599      | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2338      | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2253      | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2096      | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1971      | 0.84%   |
| Intel Wireless 3165                                                     | 1879      | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1864      | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1757      | 0.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1650      | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1606      | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1600      | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1520      | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                   | 1447      | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1440      | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1382      | 0.59%   |
| Intel 82577LM Gigabit Network Connection                                | 1346      | 0.57%   |
| Intel Wireless 3160                                                     | 1337      | 0.57%   |
| Intel Ethernet Connection I219-LM                                       | 1224      | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1190      | 0.51%   |
| Intel Ethernet Connection I218-LM                                       | 1185      | 0.51%   |
| Intel Centrino Ultimate-N 6300                                          | 1170      | 0.5%    |
| Intel WiFi Link 5100                                                    | 1168      | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 55609     | 44.18%  |
| Qualcomm Atheros                      | 27134     | 21.56%  |
| Realtek Semiconductor                 | 19593     | 15.56%  |
| Broadcom                              | 10936     | 8.69%   |
| MediaTek                              | 2520      | 2%      |
| Broadcom Limited                      | 2420      | 1.92%   |
| Ralink                                | 2141      | 1.7%    |
| Ralink Technology                     | 1043      | 0.83%   |
| TP-Link                               | 878       | 0.7%    |
| Sierra Wireless                       | 657       | 0.52%   |
| Dell                                  | 577       | 0.46%   |
| Qualcomm                              | 360       | 0.29%   |
| Qualcomm Atheros Communications       | 293       | 0.23%   |
| NetGear                               | 210       | 0.17%   |
| ASUSTek Computer                      | 204       | 0.16%   |
| D-Link                                | 180       | 0.14%   |
| Fibocom                               | 158       | 0.13%   |
| Ericsson Business Mobile Networks     | 130       | 0.1%    |
| Hewlett-Packard                       | 115       | 0.09%   |
| Edimax Technology                     | 106       | 0.08%   |
| D-Link System                         | 89        | 0.07%   |
| Linksys                               | 74        | 0.06%   |
| Belkin Components                     | 64        | 0.05%   |
| Microsoft                             | 49        | 0.04%   |
| Micro Star International              | 25        | 0.02%   |
| AVM                                   | 25        | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 20        | 0.02%   |
| ZyXEL Communications                  | 19        | 0.02%   |
| ZyDAS                                 | 19        | 0.02%   |
| Sitecom Europe                        | 18        | 0.01%   |
| Quectel Wireless Solutions            | 15        | 0.01%   |
| Fujitsu Siemens Computers             | 13        | 0.01%   |
| BUFFALO                               | 13        | 0.01%   |
| Mercucys                              | 11        | 0.01%   |
| Unknown                               | 11        | 0.01%   |
| Xiaomi                                | 10        | 0.01%   |
| Qualcomm Technologies                 | 10        | 0.01%   |
| Qcom                                  | 10        | 0.01%   |
| Marvell Technology Group              | 10        | 0.01%   |
| TRENDnet                              | 9         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5382      | 4.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5061      | 4%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4713      | 3.72%   |
| Intel Wi-Fi 6 AX200                                                     | 4580      | 3.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4572      | 3.61%   |
| Intel Wireless 8265 / 8275                                              | 4361      | 3.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3708      | 2.93%   |
| Intel Wireless 7260                                                     | 3496      | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3469      | 2.74%   |
| Intel Wi-Fi 6 AX201                                                     | 3439      | 2.72%   |
| Intel Wireless 7265                                                     | 3413      | 2.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2935      | 2.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2877      | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2623      | 2.07%   |
| Intel Wireless 8260                                                     | 2599      | 2.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2338      | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2253      | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2096      | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1971      | 1.56%   |
| Intel Wireless 3165                                                     | 1879      | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1864      | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1757      | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1650      | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1606      | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1600      | 1.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1520      | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1382      | 1.09%   |
| Intel Wireless 3160                                                     | 1337      | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1190      | 0.94%   |
| Intel Centrino Ultimate-N 6300                                          | 1170      | 0.92%   |
| Intel WiFi Link 5100                                                    | 1168      | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1067      | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1067      | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1059      | 0.84%   |
| Intel Centrino Advanced-N 6200                                          | 1023      | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 961       | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 950       | 0.75%   |
| Intel Centrino Advanced-N 6235                                          | 947       | 0.75%   |
| Intel Wireless-AC 9260                                                  | 928       | 0.73%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 919       | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 56907     | 54.76%  |
| Intel                                  | 20769     | 19.99%  |
| Qualcomm Atheros                       | 8271      | 7.96%   |
| Broadcom                               | 5290      | 5.09%   |
| Marvell Technology Group               | 2729      | 2.63%   |
| Broadcom Limited                       | 1355      | 1.3%    |
| ASIX Electronics                       | 1219      | 1.17%   |
| Nvidia                                 | 1124      | 1.08%   |
| JMicron Technology                     | 677       | 0.65%   |
| Samsung Electronics                    | 651       | 0.63%   |
| Xiaomi                                 | 571       | 0.55%   |
| Lenovo                                 | 564       | 0.54%   |
| DisplayLink                            | 560       | 0.54%   |
| Huawei Technologies                    | 385       | 0.37%   |
| Silicon Integrated Systems [SiS]       | 359       | 0.35%   |
| Attansic Technology                    | 279       | 0.27%   |
| TP-Link                                | 233       | 0.22%   |
| MediaTek                               | 200       | 0.19%   |
| Qualcomm                               | 152       | 0.15%   |
| OPPO Electronics                       | 151       | 0.15%   |
| Apple                                  | 143       | 0.14%   |
| Google                                 | 142       | 0.14%   |
| Hewlett-Packard                        | 122       | 0.12%   |
| Motorola PCS                           | 118       | 0.11%   |
| ZTE WCDMA Technologies MSM             | 109       | 0.1%    |
| ICS Advent                             | 104       | 0.1%    |
| VIA Technologies                       | 99        | 0.1%    |
| OnePlus Technology (Shenzhen)          | 58        | 0.06%   |
| T & A Mobile Phones                    | 38        | 0.04%   |
| HTC (High Tech Computer)               | 35        | 0.03%   |
| D-Link                                 | 33        | 0.03%   |
| Gemtek                                 | 32        | 0.03%   |
| Spreadtrum Communications              | 31        | 0.03%   |
| LG Electronics                         | 31        | 0.03%   |
| Microchip Technology                   | 30        | 0.03%   |
| Cypress Semiconductor                  | 27        | 0.03%   |
| HMD Global                             | 26        | 0.03%   |
| Edimax Technology                      | 22        | 0.02%   |
| ASUSTek Computer                       | 22        | 0.02%   |
| Sony Ericsson Mobile Communications AB | 21        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37715     | 35.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13417     | 12.79%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4307      | 4.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3879      | 3.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 1447      | 1.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1440      | 1.37%   |
| Intel 82577LM Gigabit Network Connection                          | 1346      | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 1224      | 1.17%   |
| Intel Ethernet Connection I218-LM                                 | 1185      | 1.13%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1050      | 1%      |
| Intel Ethernet Connection I217-LM                                 | 1049      | 1%      |
| ASIX AX88179 Gigabit Ethernet                                     | 1040      | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 1006      | 0.96%   |
| Intel 82567LM Gigabit Network Connection                          | 948       | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 842       | 0.8%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 833       | 0.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 762       | 0.73%   |
| Nvidia MCP79 Ethernet                                             | 759       | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 703       | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 690       | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 683       | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 679       | 0.65%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 646       | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 629       | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 625       | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 615       | 0.59%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 610       | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 584       | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 563       | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 552       | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 547       | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 529       | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 516       | 0.49%   |
| Intel Ethernet Connection I219-V                                  | 498       | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 488       | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 452       | 0.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 438       | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 428       | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 428       | 0.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 427       | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 119534    | 53.94%  |
| Ethernet | 99444     | 44.88%  |
| Modem    | 2397      | 1.08%   |
| Unknown  | 226       | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 99571     | 77.65%  |
| Ethernet | 28610     | 22.31%  |
| Modem    | 27        | 0.02%   |
| Unknown  | 19        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 91341     | 74.94%  |
| 1     | 27785     | 22.8%   |
| 0     | 2023      | 1.66%   |
| 3     | 719       | 0.59%   |
| 4     | 14        | 0.01%   |
| 7     | 2         | 0.002%  |
| 5     | 2         | 0.002%  |
| 13    | 1         | 0.001%  |
| 10    | 1         | 0.001%  |
| 8     | 1         | 0.001%  |
| 6     | 1         | 0.001%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 98401     | 78.81%  |
| Yes     | 22563     | 18.07%  |
| Unknown | 3889      | 3.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41371     | 44.04%  |
| Realtek Semiconductor           | 9677      | 10.3%   |
| Qualcomm Atheros Communications | 9533      | 10.15%  |
| IMC Networks                    | 5989      | 6.38%   |
| Broadcom                        | 5620      | 5.98%   |
| Lite-On Technology              | 4605      | 4.9%    |
| Foxconn / Hon Hai               | 3805      | 4.05%   |
| Apple                           | 3157      | 3.36%   |
| Dell                            | 1786      | 1.9%    |
| Hewlett-Packard                 | 1454      | 1.55%   |
| Cambridge Silicon Radio         | 1227      | 1.31%   |
| Toshiba                         | 1081      | 1.15%   |
| Ralink                          | 1067      | 1.14%   |
| Realtek                         | 711       | 0.76%   |
| ASUSTek Computer                | 685       | 0.73%   |
| Foxconn International           | 492       | 0.52%   |
| Alps Electric                   | 361       | 0.38%   |
| Ralink Technology               | 252       | 0.27%   |
| MediaTek                        | 222       | 0.24%   |
| USI                             | 124       | 0.13%   |
| Askey Computer                  | 121       | 0.13%   |
| Chicony Electronics             | 96        | 0.1%    |
| Taiyo Yuden                     | 82        | 0.09%   |
| Opticis                         | 70        | 0.07%   |
| Qcom                            | 50        | 0.05%   |
| Smart Modular Technologies      | 45        | 0.05%   |
| Micro Star International        | 44        | 0.05%   |
| TP-Link                         | 31        | 0.03%   |
| Fujitsu                         | 31        | 0.03%   |
| Integrated System Solution      | 22        | 0.02%   |
| Edimax Technology               | 22        | 0.02%   |
| Dynex                           | 16        | 0.02%   |
| Belkin Components               | 15        | 0.02%   |
| Unknown                         | 11        | 0.01%   |
| Syntek                          | 10        | 0.01%   |
| SINO WEALTH                     | 7         | 0.01%   |
| Marvell Semiconductor           | 5         | 0.01%   |
| Actions                         | 5         | 0.01%   |
| Sitecom Europe                  | 4         | 0.004%  |
| Logitech                        | 4         | 0.004%  |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16558     | 17.61%  |
| Intel Bluetooth Device                              | 8942      | 9.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6219      | 6.61%   |
| Realtek Bluetooth Radio                             | 5911      | 6.29%   |
| Intel AX200 Bluetooth                               | 4447      | 4.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 4333      | 4.61%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2389      | 2.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1732      | 1.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1568      | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1547      | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1531      | 1.63%   |
| IMC Networks Bluetooth Radio                        | 1511      | 1.61%   |
| Apple Bluetooth Host Controller                     | 1445      | 1.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1258      | 1.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1227      | 1.3%    |
| IMC Networks Bluetooth Device                       | 1221      | 1.3%    |
| IMC Networks 802.11ac WLAN Adapter                  | 1115      | 1.19%   |
| Lite-On Bluetooth Device                            | 1082      | 1.15%   |
| Ralink RT3290 Bluetooth                             | 1067      | 1.13%   |
| IMC Networks Wireless_Device                        | 977       | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 916       | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 916       | 0.97%   |
| Apple Bluetooth USB Host Controller                 | 916       | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 912       | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 907       | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                    | 879       | 0.93%   |
| Intel AX210 Bluetooth                               | 867       | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 830       | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                    | 787       | 0.84%   |
| Realtek Bluetooth Radio                             | 711       | 0.76%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 670       | 0.71%   |
| Dell DW375 Bluetooth Module                         | 616       | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 604       | 0.64%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 556       | 0.59%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 540       | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 525       | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 506       | 0.54%   |
| Foxconn International BCM43142A0 Bluetooth module   | 490       | 0.52%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 467       | 0.5%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 420       | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 96186     | 65.81%  |
| AMD                              | 24995     | 17.1%   |
| Nvidia                           | 16657     | 11.4%   |
| C-Media Electronics              | 953       | 0.65%   |
| Realtek Semiconductor            | 652       | 0.45%   |
| Logitech                         | 630       | 0.43%   |
| Lenovo                           | 586       | 0.4%    |
| GN Netcom                        | 496       | 0.34%   |
| Silicon Integrated Systems [SiS] | 442       | 0.3%    |
| Plantronics                      | 305       | 0.21%   |
| JMTek                            | 292       | 0.2%    |
| Generalplus Technology           | 249       | 0.17%   |
| Texas Instruments                | 248       | 0.17%   |
| Hewlett-Packard                  | 230       | 0.16%   |
| Apple                            | 227       | 0.16%   |
| Kingston Technology              | 184       | 0.13%   |
| Creative Technology              | 165       | 0.11%   |
| VIA Technologies                 | 129       | 0.09%   |
| Razer USA                        | 122       | 0.08%   |
| Focusrite-Novation               | 117       | 0.08%   |
| ASUSTek Computer                 | 108       | 0.07%   |
| SteelSeries ApS                  | 106       | 0.07%   |
| Corsair                          | 102       | 0.07%   |
| Sony                             | 99        | 0.07%   |
| DSEA A/S                         | 78        | 0.05%   |
| Conexant Systems                 | 62        | 0.04%   |
| Dell                             | 59        | 0.04%   |
| Samson Technologies              | 46        | 0.03%   |
| Microsoft                        | 46        | 0.03%   |
| BEHRINGER International          | 46        | 0.03%   |
| No brand                         | 45        | 0.03%   |
| Blue Microphones                 | 45        | 0.03%   |
| RODE Microphones                 | 40        | 0.03%   |
| M-Audio                          | 40        | 0.03%   |
| GYROCOM C&C                      | 39        | 0.03%   |
| Sennheiser Communications        | 38        | 0.03%   |
| Tenx Technology                  | 37        | 0.03%   |
| Samsung Electronics              | 37        | 0.03%   |
| Yamaha                           | 35        | 0.02%   |
| BR23                             | 32        | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 13274     | 7.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11285     | 6.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11251     | 6.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7994      | 4.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5661      | 3.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5540      | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5279      | 2.99%   |
| Intel 8 Series HD Audio Controller                                                                | 4980      | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4960      | 2.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4680      | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4421      | 2.5%    |
| AMD FCH Azalia Controller                                                                         | 4263      | 2.41%   |
| Intel Broadwell-U Audio Controller                                                                | 4091      | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4029      | 2.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3682      | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3671      | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3457      | 1.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3189      | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3078      | 1.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2942      | 1.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2788      | 1.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2597      | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2590      | 1.47%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2132      | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2103      | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2042      | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1996      | 1.13%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1977      | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1956      | 1.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 1948      | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 1788      | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1725      | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1621      | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1561      | 0.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1475      | 0.83%   |
| AMD High Definition Audio Controller                                                              | 1418      | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1337      | 0.76%   |
| AMD Wrestler HDMI Audio                                                                           | 1209      | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1101      | 0.62%   |
| Nvidia Audio device                                                                               | 1100      | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 23285     | 27.57%  |
| SK hynix            | 18728     | 22.17%  |
| Micron Technology   | 9644      | 11.42%  |
| Kingston            | 7341      | 8.69%   |
| Unknown             | 6598      | 7.81%   |
| Crucial             | 3380      | 4%      |
| Elpida              | 2209      | 2.62%   |
| Ramaxel Technology  | 2066      | 2.45%   |
| A-DATA Technology   | 1878      | 2.22%   |
| Nanya Technology    | 1460      | 1.73%   |
| Corsair             | 914       | 1.08%   |
| Unknown (ABCD)      | 773       | 0.92%   |
| Smart               | 644       | 0.76%   |
| G.Skill             | 438       | 0.52%   |
| Unknown             | 434       | 0.51%   |
| Transcend           | 315       | 0.37%   |
| ASint Technology    | 300       | 0.36%   |
| Team                | 272       | 0.32%   |
| Patriot             | 267       | 0.32%   |
| GOODRAM             | 233       | 0.28%   |
| Goldkey             | 196       | 0.23%   |
| Teikon              | 182       | 0.22%   |
| 48spaces            | 182       | 0.22%   |
| AMD                 | 181       | 0.21%   |
| Apacer              | 175       | 0.21%   |
| Qimonda             | 129       | 0.15%   |
| Smart Brazil        | 127       | 0.15%   |
| SHARETRONIC         | 127       | 0.15%   |
| Avant               | 84        | 0.1%    |
| Silicon Power       | 79        | 0.09%   |
| Toshiba             | 77        | 0.09%   |
| PNY                 | 77        | 0.09%   |
| High Bridge         | 71        | 0.08%   |
| Timetec             | 66        | 0.08%   |
| Neo Forza           | 61        | 0.07%   |
| Kllisre             | 57        | 0.07%   |
| CSX                 | 56        | 0.07%   |
| Foxline             | 54        | 0.06%   |
| Kingmax             | 52        | 0.06%   |
| ACPI Digital        | 51        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1028      | 1.14%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 984       | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 958       | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 958       | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 884       | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 855       | 0.95%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 816       | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 807       | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 711       | 0.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 706       | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 689       | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 647       | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 598       | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 595       | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 558       | 0.62%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 533       | 0.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 526       | 0.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 516       | 0.57%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 511       | 0.57%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 498       | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 498       | 0.55%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 481       | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 480       | 0.53%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 480       | 0.53%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 467       | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 458       | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 445       | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 441       | 0.49%   |
| Unknown                                                          | 434       | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 410       | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 410       | 0.45%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 382       | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 378       | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 358       | 0.4%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 354       | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 352       | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 344       | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 342       | 0.38%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 332       | 0.37%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 327       | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 28135     | 39.6%   |
| DDR3    | 27719     | 39.01%  |
| DDR2    | 4890      | 6.88%   |
| LPDDR4  | 3045      | 4.29%   |
| SDRAM   | 2037      | 2.87%   |
| LPDDR3  | 1951      | 2.75%   |
| DDR5    | 1012      | 1.42%   |
| LPDDR5  | 844       | 1.19%   |
| Unknown | 558       | 0.79%   |
| DDR     | 524       | 0.74%   |
| DRAM    | 332       | 0.47%   |
| RAM     | 4         | 0.01%   |
| SRAM    | 1         | 0.001%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 63848     | 90.26%  |
| Row Of Chips    | 5618      | 7.94%   |
| Chip            | 458       | 0.65%   |
| Unknown         | 436       | 0.62%   |
| DIMM            | 375       | 0.53%   |
| Proprietary Car | 5         | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 26198     | 33.05%  |
| 4096    | 24594     | 31.03%  |
| 2048    | 13039     | 16.45%  |
| 16384   | 9017      | 11.38%  |
| 1024    | 3996      | 5.04%   |
| 32768   | 1806      | 2.28%   |
| 512     | 477       | 0.6%    |
| 256     | 74        | 0.09%   |
| Unknown | 16        | 0.02%   |
| 1536    | 11        | 0.01%   |
| 12288   | 6         | 0.01%   |
| 3072    | 6         | 0.01%   |
| 128     | 6         | 0.01%   |
| 6144    | 5         | 0.01%   |
| 64      | 4         | 0.01%   |
| 65536   | 3         | 0.004%  |
| 49152   | 2         | 0.003%  |
| 131072  | 1         | 0.001%  |
| 8072    | 1         | 0.001%  |
| 384     | 1         | 0.001%  |
| 232     | 1         | 0.001%  |
| 8       | 1         | 0.001%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 18373     | 23.72%  |
| 2667    | 12986     | 16.76%  |
| 3200    | 11860     | 15.31%  |
| 1334    | 5306      | 6.85%   |
| 2400    | 4848      | 6.26%   |
| 1333    | 3604      | 4.65%   |
| 2133    | 3148      | 4.06%   |
| 667     | 2635      | 3.4%    |
| Unknown | 2234      | 2.88%   |
| 1067    | 1445      | 1.87%   |
| 800     | 1438      | 1.86%   |
| 4199    | 1084      | 1.4%    |
| 4267    | 1049      | 1.35%   |
| 3266    | 959       | 1.24%   |
| 4800    | 909       | 1.17%   |
| 1867    | 878       | 1.13%   |
| 6400    | 782       | 1.01%   |
| 2048    | 582       | 0.75%   |
| 1066    | 561       | 0.72%   |
| 533     | 540       | 0.7%    |
| 975     | 451       | 0.58%   |
| 8400    | 327       | 0.42%   |
| 4266    | 321       | 0.41%   |
| 3733    | 184       | 0.24%   |
| 333     | 158       | 0.2%    |
| 5600    | 153       | 0.2%    |
| 1866    | 95        | 0.12%   |
| 2933    | 91        | 0.12%   |
| 400     | 88        | 0.11%   |
| 1639    | 85        | 0.11%   |
| 266     | 28        | 0.04%   |
| 5500    | 27        | 0.03%   |
| 3000    | 26        | 0.03%   |
| 1776    | 23        | 0.03%   |
| 7500    | 15        | 0.02%   |
| 7467    | 15        | 0.02%   |
| 2666    | 15        | 0.02%   |
| 1200    | 15        | 0.02%   |
| 666     | 12        | 0.02%   |
| 2267    | 11        | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 465       | 32.89%  |
| Canon                           | 271       | 19.17%  |
| Brother Industries              | 175       | 12.38%  |
| Samsung Electronics             | 173       | 12.23%  |
| Seiko Epson                     | 141       | 9.97%   |
| Xerox                           | 30        | 2.12%   |
| Prolific Technology             | 20        | 1.41%   |
| Panasonic (Matsushita)          | 17        | 1.2%    |
| Pantum                          | 16        | 1.13%   |
| Lexmark International           | 16        | 1.13%   |
| Kyocera                         | 15        | 1.06%   |
| Ricoh                           | 12        | 0.85%   |
| STMicroelectronics              | 11        | 0.78%   |
| Dymo-CoStar                     | 9         | 0.64%   |
| QinHeng Electronics             | 8         | 0.57%   |
| Xiaomi                          | 4         | 0.28%   |
| Oki Data                        | 4         | 0.28%   |
| MIIIW                           | 4         | 0.28%   |
| Dell                            | 4         | 0.28%   |
| Zebra                           | 3         | 0.21%   |
| TSC Auto ID Technology          | 2         | 0.14%   |
| Konica Minolta                  | 2         | 0.14%   |
| BIXOLON                         | 2         | 0.14%   |
| Samsung Info. Systems America   | 1         | 0.07%   |
| Sagem                           | 1         | 0.07%   |
| NXP Semiconductors              | 1         | 0.07%   |
| Minolta                         | 1         | 0.07%   |
| KODAK                           | 1         | 0.07%   |
| iDPRT                           | 1         | 0.07%   |
| ICS Advent                      | 1         | 0.07%   |
| cab Produkttechnik GmbH & Co KG | 1         | 0.07%   |
| Apple                           | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                          | 33        | 2.3%    |
| Samsung M2020 Series                                      | 27        | 1.88%   |
| HP LaserJet 1018                                          | 24        | 1.67%   |
| HP LaserJet P1102                                         | 22        | 1.53%   |
| Canon PIXMA MG2500 Series                                 | 22        | 1.53%   |
| Prolific PL2305 Parallel Port                             | 20        | 1.39%   |
| HP DeskJet 2700 series                                    | 20        | 1.39%   |
| Samsung M2070 Series                                      | 16        | 1.11%   |
| HP DeskJet 2130 series                                    | 15        | 1.04%   |
| HP DeskJet 2600 series                                    | 14        | 0.97%   |
| Canon PIXMA MG3600 Series                                 | 13        | 0.91%   |
| Seiko Epson L3150 Series                                  | 12        | 0.84%   |
| Samsung SCX-4200 series                                   | 12        | 0.84%   |
| Canon LBP6020                                             | 12        | 0.84%   |
| HP LaserJet 3050                                          | 11        | 0.77%   |
| HP DeskJet 2300 series                                    | 11        | 0.77%   |
| HP Deskjet 2050 J510                                      | 11        | 0.77%   |
| Canon LBP2900                                             | 11        | 0.77%   |
| Brother HL-1110 series                                    | 11        | 0.77%   |
| Samsung SCX-3400 Series                                   | 10        | 0.7%    |
| Samsung SCX-3200 Series                                   | 10        | 0.7%    |
| HP ENVY 4520 series                                       | 10        | 0.7%    |
| Seiko Epson L360 Series                                   | 9         | 0.63%   |
| Panasonic (Matsushita) KX-MB1500RU                        | 9         | 0.63%   |
| HP OfficeJet 3830 series                                  | 9         | 0.63%   |
| HP LaserJet Professional P1102w                           | 9         | 0.63%   |
| HP LaserJet P1005                                         | 9         | 0.63%   |
| HP Deskjet 2540 series                                    | 9         | 0.63%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 8         | 0.56%   |
| Seiko Epson Printer                                       | 8         | 0.56%   |
| QinHeng CH340S                                            | 8         | 0.56%   |
| Canon PIXMA MX920 Series                                  | 8         | 0.56%   |
| Brother HL-2030 Laser Printer                             | 8         | 0.56%   |
| Seiko Epson L3110 Series                                  | 7         | 0.49%   |
| Seiko Epson L210 Series                                   | 7         | 0.49%   |
| Samsung ML-1640 Series Laser Printer                      | 7         | 0.49%   |
| Samsung M267x 287x Series                                 | 7         | 0.49%   |
| HP LaserJet 1200                                          | 7         | 0.49%   |
| HP DeskJet 3630 series                                    | 7         | 0.49%   |
| HP Deskjet 1050 J410                                      | 7         | 0.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 130       | 50%     |
| Seiko Epson                                    | 57        | 21.92%  |
| Hewlett-Packard                                | 28        | 10.77%  |
| Mustek Systems                                 | 19        | 7.31%   |
| Ultima Electronics                             | 6         | 2.31%   |
| Acer Peripherals (now BenQ)                    | 4         | 1.54%   |
| Plustek                                        | 3         | 1.15%   |
| KYE Systems (Mouse Systems)                    | 3         | 1.15%   |
| Siemens Information and Communication Products | 2         | 0.77%   |
| Microtek International                         | 2         | 0.77%   |
| AGFA-Gevaert NV                                | 2         | 0.77%   |
| Visioneer                                      | 1         | 0.38%   |
| Papillon Systems                               | 1         | 0.38%   |
| Fujitsu                                        | 1         | 0.38%   |
| Canon Electronics                              | 1         | 0.38%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 24        | 9.2%    |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 17        | 6.51%   |
| Canon CanoScan LiDE 220                                                               | 15        | 5.75%   |
| Canon CanoScan LIDE 25                                                                | 11        | 4.21%   |
| Canon CanoScan LiDE 120                                                               | 10        | 3.83%   |
| Canon CanoScan LiDE 210                                                               | 8         | 3.07%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 7         | 2.68%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 6         | 2.3%    |
| HP ScanJet 2400c                                                                      | 6         | 2.3%    |
| Canon CanoScan LiDE 100                                                               | 6         | 2.3%    |
| Canon CanoScan 4400F                                                                  | 6         | 2.3%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 5         | 1.92%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 1.92%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 5         | 1.92%   |
| Mustek Systems SNAPSCAN e22                                                           | 5         | 1.92%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 5         | 1.92%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 4         | 1.53%   |
| HP Scanjet 200                                                                        | 4         | 1.53%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                      | 3         | 1.15%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 3         | 1.15%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 3         | 1.15%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 3         | 1.15%   |
| Canon CanoScan N650U/N656U                                                            | 3         | 1.15%   |
| Canon CanoScan LiDE 600F                                                              | 3         | 1.15%   |
| Canon CanoScan LiDE 500F                                                              | 3         | 1.15%   |
| Canon CanoScan LiDE 200                                                               | 3         | 1.15%   |
| Canon CanoScan 4200F                                                                  | 3         | 1.15%   |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader       | 2         | 0.77%   |
| Seiko Epson Scanner                                                                   | 2         | 0.77%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 2         | 0.77%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 0.77%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2         | 0.77%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 2         | 0.77%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2         | 0.77%   |
| Plustek OpticSlim 1200 Scanner                                                        | 2         | 0.77%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 2         | 0.77%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 2         | 0.77%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 0.77%   |
| HP ScanJet 5590                                                                       | 2         | 0.77%   |
| HP ScanJet 3770                                                                       | 2         | 0.77%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26171     | 24.57%  |
| IMC Networks                           | 11122     | 10.44%  |
| Microdia                               | 9080      | 8.53%   |
| Realtek Semiconductor                  | 8592      | 8.07%   |
| Bison Electronics                      | 6717      | 6.31%   |
| Sunplus Innovation Technology          | 6023      | 5.66%   |
| Quanta                                 | 5604      | 5.26%   |
| Suyin                                  | 4396      | 4.13%   |
| Cheng Uei Precision Industry (Foxlink) | 4239      | 3.98%   |
| Syntek                                 | 2716      | 2.55%   |
| Apple                                  | 2351      | 2.21%   |
| Acer                                   | 2262      | 2.12%   |
| Lite-On Technology                     | 2248      | 2.11%   |
| Silicon Motion                         | 2199      | 2.06%   |
| Alcor Micro                            | 1561      | 1.47%   |
| Luxvisions Innotech Limited            | 1470      | 1.38%   |
| Logitech                               | 1242      | 1.17%   |
| Ricoh                                  | 1134      | 1.06%   |
| Lenovo                                 | 666       | 0.63%   |
| Samsung Electronics                    | 652       | 0.61%   |
| Sonix Technology                       | 620       | 0.58%   |
| Z-Star Microelectronics                | 539       | 0.51%   |
| ALi                                    | 524       | 0.49%   |
| Importek                               | 477       | 0.45%   |
| Primax Electronics                     | 419       | 0.39%   |
| DigiTech                               | 284       | 0.27%   |
| SunplusIT                              | 259       | 0.24%   |
| OmniVision Technologies                | 212       | 0.2%    |
| icSpring                               | 205       | 0.19%   |
| Microsoft                              | 159       | 0.15%   |
| Sunplus Technology                     | 121       | 0.11%   |
| Intel                                  | 115       | 0.11%   |
| Y Media                                | 108       | 0.1%    |
| GEMBIRD                                | 101       | 0.09%   |
| Generalplus Technology                 | 99        | 0.09%   |
| Genesys Logic                          | 93        | 0.09%   |
| ShineTech                              | 73        | 0.07%   |
| LG Electronics                         | 65        | 0.06%   |
| Shenzhen Kingcome Optoelectronic       | 54        | 0.05%   |
| 8SSC20F27114V1SR0BK1X4S                | 53        | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 4638      | 4.34%   |
| Microdia Integrated_Webcam_HD           | 3802      | 3.56%   |
| Realtek Integrated_Webcam_HD            | 2725      | 2.55%   |
| IMC Networks USB2.0 HD UVC WebCam       | 2624      | 2.45%   |
| IMC Networks Integrated Camera          | 2584      | 2.42%   |
| Chicony HD WebCam                       | 2496      | 2.33%   |
| Sunplus Integrated_Webcam_HD            | 1887      | 1.76%   |
| Bison Integrated Camera                 | 1779      | 1.66%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1691      | 1.58%   |
| Syntek Integrated Camera                | 1297      | 1.21%   |
| Realtek USB camera                      | 1104      | 1.03%   |
| Quanta HD User Facing                   | 1029      | 0.96%   |
| Sunplus HD WebCam                       | 937       | 0.88%   |
| Chicony HP HD Camera                    | 915       | 0.86%   |
| Microdia Integrated Webcam              | 914       | 0.85%   |
| Chicony USB 2.0 Camera                  | 869       | 0.81%   |
| Chicony HP Truevision HD                | 853       | 0.8%    |
| Chicony Lenovo EasyCamera               | 842       | 0.79%   |
| Chicony USB2.0 HD UVC WebCam            | 835       | 0.78%   |
| Lite-On Integrated Camera               | 833       | 0.78%   |
| Bison Lenovo EasyCamera                 | 802       | 0.75%   |
| Chicony HD User Facing                  | 799       | 0.75%   |
| Chicony HP TrueVision HD Camera         | 774       | 0.72%   |
| Chicony USB2.0 VGA UVC WebCam           | 770       | 0.72%   |
| Bison HD Webcam                         | 736       | 0.69%   |
| Quanta HP TrueVision HD Camera          | 713       | 0.67%   |
| Chicony TOSHIBA Web Camera - HD         | 690       | 0.65%   |
| Chicony USB2.0 Camera                   | 689       | 0.64%   |
| Apple iPhone 5/5C/5S/6/SE               | 686       | 0.64%   |
| Apple FaceTime HD Camera                | 664       | 0.62%   |
| Chicony VGA Webcam                      | 661       | 0.62%   |
| Samsung Galaxy series, misc. (MTP mode) | 641       | 0.6%    |
| Chicony EasyCamera                      | 626       | 0.59%   |
| Alcor Micro USB 2.0 Camera              | 597       | 0.56%   |
| Quanta VGA WebCam                       | 596       | 0.56%   |
| Chicony Integrated Camera (1280x720@30) | 589       | 0.55%   |
| Syntek Lenovo EasyCamera                | 588       | 0.55%   |
| Apple Built-in iSight                   | 583       | 0.55%   |
| Bison SunplusIT Integrated Camera       | 582       | 0.54%   |
| Realtek Integrated Webcam               | 571       | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 7142      | 36.06%  |
| Synaptics                          | 4577      | 23.11%  |
| Shenzhen Goodix Technology         | 2730      | 13.78%  |
| AuthenTec                          | 1493      | 7.54%   |
| Upek                               | 1230      | 6.21%   |
| Elan Microelectronics              | 1137      | 5.74%   |
| LighTuning Technology              | 846       | 4.27%   |
| STMicroelectronics                 | 357       | 1.8%    |
| Realtek USB2.0 Finger Print Bridge | 106       | 0.54%   |
| Focal-systems.Corp                 | 88        | 0.44%   |
| Samsung Electronics                | 54        | 0.27%   |
| HOLTEK                             | 27        | 0.14%   |
| DigitalPersona                     | 8         | 0.04%   |
| GDMicroelectronics                 | 4         | 0.02%   |
| Microsoft                          | 3         | 0.02%   |
| Next Biometrics                    | 2         | 0.01%   |
| Dell                               | 2         | 0.01%   |
| Suprema                            | 1         | 0.01%   |
| Futronic Technology                | 1         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 1683      | 8.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1594      | 8.05%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1571      | 7.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1138      | 5.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 845       | 4.27%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 790       | 3.99%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 779       | 3.93%   |
| Elan ELAN:Fingerprint                                                      | 642       | 3.24%   |
| Shenzhen Goodix Fingerprint Reader                                         | 557       | 2.81%   |
| Validity Sensors VFS491                                                    | 510       | 2.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 500       | 2.52%   |
| Validity Sensors Fingerprint scanner                                       | 500       | 2.52%   |
| Shenzhen Goodix FingerPrint                                                | 490       | 2.47%   |
| Validity Sensors Synaptics WBDI                                            | 489       | 2.47%   |
| Elan ELAN:ARM-M4                                                           | 481       | 2.43%   |
| AuthenTec AES2810                                                          | 472       | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 443       | 2.24%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 384       | 1.94%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 355       | 1.79%   |
| STMicroelectronics Fingerprint Reader                                      | 355       | 1.79%   |
| Synaptics Fingerprint reader [HP G6]                                       | 319       | 1.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 318       | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 305       | 1.54%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 297       | 1.5%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 286       | 1.44%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 276       | 1.39%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 265       | 1.34%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 252       | 1.27%   |
| AuthenTec AES1600                                                          | 234       | 1.18%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 223       | 1.13%   |
| AuthenTec Fingerprint Sensor                                               | 211       | 1.07%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 190       | 0.96%   |
| Synaptics  WBDI                                                            | 190       | 0.96%   |
| Synaptics UWP WBDI Device                                                  | 165       | 0.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 155       | 0.78%   |
| LighTuning Fingerprint Reader                                              | 146       | 0.74%   |
| Validity Sensors VFS Fingerprint sensor                                    | 122       | 0.62%   |
| Synaptics WBDI                                                             | 119       | 0.6%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 106       | 0.54%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 102       | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 4128      | 48.71%  |
| Alcor Micro                       | 2305      | 27.2%   |
| O2 Micro                          | 672       | 7.93%   |
| Upek                              | 521       | 6.15%   |
| Lenovo                            | 465       | 5.49%   |
| Gemalto (was Gemplus)             | 84        | 0.99%   |
| SCM Microsystems                  | 50        | 0.59%   |
| Yubico.com                        | 41        | 0.48%   |
| OmniKey                           | 27        | 0.32%   |
| Advanced Card Systems             | 26        | 0.31%   |
| Aladdin Knowledge Systems         | 23        | 0.27%   |
| Realtek Semiconductor             | 21        | 0.25%   |
| Clay Logic                        | 15        | 0.18%   |
| Giesecke & Devrient               | 12        | 0.14%   |
| Cherry                            | 12        | 0.14%   |
| Reiner SCT Kartensysteme          | 7         | 0.08%   |
| Chicony Electronics               | 7         | 0.08%   |
| Bit4id                            | 7         | 0.08%   |
| VASCO Data Security International | 6         | 0.07%   |
| Hewlett-Packard                   | 6         | 0.07%   |
| Watchdata                         | 5         | 0.06%   |
| Aladdin R.D.                      | 5         | 0.06%   |
| Aktiv                             | 5         | 0.06%   |
| Purism, SPC                       | 4         | 0.05%   |
| C3PO                              | 4         | 0.05%   |
| NXP Semiconductors                | 3         | 0.04%   |
| In Focus Systems                  | 3         | 0.04%   |
| Fujitsu Siemens Computers         | 3         | 0.04%   |
| Microchip Technology              | 2         | 0.02%   |
| Athena Smartcard Solutions        | 2         | 0.02%   |
| SpringCard                        | 1         | 0.01%   |
| MagTek                            | 1         | 0.01%   |
| Kobil Systems                     | 1         | 0.01%   |
| Integrated Technology Express     | 1         | 0.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2290      | 27.01%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1524      | 17.97%  |
| Broadcom 5880                                                                | 984       | 11.61%  |
| Broadcom 58200                                                               | 813       | 9.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 773       | 9.12%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 578       | 6.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 521       | 6.14%   |
| Lenovo Integrated Smart Card Reader                                          | 463       | 5.46%   |
| O2 Micro Oz776 SmartCard Reader                                              | 94        | 1.11%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 44        | 0.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 38        | 0.45%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 33        | 0.39%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 30        | 0.35%   |
| Aladdin Knowledge Systems Token JC                                           | 23        | 0.27%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 21        | 0.25%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 21        | 0.25%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 13        | 0.15%   |
| Alcor Micro Watchdata W 1981                                                 | 12        | 0.14%   |
| OmniKey CardMan 4321                                                         | 11        | 0.13%   |
| Clay Logic Nitrokey Pro                                                      | 11        | 0.13%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 10        | 0.12%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 9         | 0.11%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 9         | 0.11%   |
| Advanced Card Systems ACR122U                                                | 9         | 0.11%   |
| Giesecke & Devrient StarSign CUT                                             | 8         | 0.09%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 7         | 0.08%   |
| Bit4id miniLector EVO                                                        | 7         | 0.08%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 6         | 0.07%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 6         | 0.07%   |
| OmniKey CardMan 3021 / 3121                                                  | 6         | 0.07%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 6         | 0.07%   |
| Advanced Card Systems ACR39U                                                 | 6         | 0.07%   |
| Watchdata USB Key                                                            | 5         | 0.06%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 5         | 0.06%   |
| Aladdin R.D. JaCarta                                                         | 5         | 0.06%   |
| Aktiv Rutoken lite                                                           | 5         | 0.06%   |
| VASCO Data Security International DIGIPASS 870                               | 4         | 0.05%   |
| Purism, SPC Librem Key                                                       | 4         | 0.05%   |
| OmniKey CardMan 1021                                                         | 4         | 0.05%   |
| Giesecke & Devrient StarSign CUT S                                           | 4         | 0.05%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 77870     | 62.04%  |
| 1     | 37635     | 29.98%  |
| 2     | 8312      | 6.62%   |
| 3     | 1221      | 0.97%   |
| 4     | 262       | 0.21%   |
| 5     | 108       | 0.09%   |
| 6     | 56        | 0.04%   |
| 7     | 30        | 0.02%   |
| 8     | 17        | 0.01%   |
| 9     | 8         | 0.01%   |
| 10    | 5         | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19574     | 34.04%  |
| Graphics card            | 13083     | 22.75%  |
| Chipcard                 | 7542      | 13.11%  |
| Net/wireless             | 5361      | 9.32%   |
| Multimedia controller    | 3376      | 5.87%   |
| Bluetooth                | 1911      | 3.32%   |
| Camera                   | 1761      | 3.06%   |
| Storage                  | 1164      | 2.02%   |
| Communication controller | 1102      | 1.92%   |
| Sound                    | 587       | 1.02%   |
| Card reader              | 586       | 1.02%   |
| Net/ethernet             | 460       | 0.8%    |
| Modem                    | 306       | 0.53%   |
| Flash memory             | 270       | 0.47%   |
| Network                  | 189       | 0.33%   |
| Firewire controller      | 52        | 0.09%   |
| Dvb card                 | 38        | 0.07%   |
| Storage/ide              | 31        | 0.05%   |
| Unassigned class         | 25        | 0.04%   |
| Storage/nvme             | 23        | 0.04%   |
| Storage/raid             | 16        | 0.03%   |
| Storage/ata              | 16        | 0.03%   |
| Wireless                 | 15        | 0.03%   |
| Tv card                  | 10        | 0.02%   |
| Unclassified device      | 7         | 0.01%   |
| Video                    | 5         | 0.01%   |


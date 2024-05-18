Lubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Lubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Lubuntu/Desktop/README.md) and [notebooks](/Dist/Lubuntu/Notebook/README.md).

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

Total: 2217

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | One S1003                   | Tablet      | [4b36e20081](https://linux-hardware.org/?probe=4b36e20081) | May 09, 2024 |
| Shenzhen B... | XN116B                      | Notebook    | [47dbcecbd7](https://linux-hardware.org/?probe=47dbcecbd7) | May 04, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [93da978d38](https://linux-hardware.org/?probe=93da978d38) | May 04, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [f9fed717ee](https://linux-hardware.org/?probe=f9fed717ee) | May 03, 2024 |
| ASRock        | Wolfdale1333-D667           | Desktop     | [9cfa5ae2c5](https://linux-hardware.org/?probe=9cfa5ae2c5) | May 03, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [e163aa8e32](https://linux-hardware.org/?probe=e163aa8e32) | May 03, 2024 |
| HP            | Pavilion dm1                | Notebook    | [ba07809953](https://linux-hardware.org/?probe=ba07809953) | May 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f163dcd97e](https://linux-hardware.org/?probe=f163dcd97e) | May 02, 2024 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [c327d5c1a6](https://linux-hardware.org/?probe=c327d5c1a6) | May 01, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [2ddfed1c8a](https://linux-hardware.org/?probe=2ddfed1c8a) | May 01, 2024 |
| HP            | 18E9                        | Desktop     | [5b1f8d9d02](https://linux-hardware.org/?probe=5b1f8d9d02) | Apr 29, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a12bc9b719](https://linux-hardware.org/?probe=a12bc9b719) | Apr 28, 2024 |
| ASUSTek       | K45A                        | Notebook    | [7bed7e12ab](https://linux-hardware.org/?probe=7bed7e12ab) | Apr 27, 2024 |
| ASUSTek       | K53BY                       | Notebook    | [6f6c4b9d68](https://linux-hardware.org/?probe=6f6c4b9d68) | Apr 26, 2024 |
| HP            | Compaq 8710w (GT649PA#AB... | Notebook    | [00f1c96012](https://linux-hardware.org/?probe=00f1c96012) | Apr 26, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [e93fe83f01](https://linux-hardware.org/?probe=e93fe83f01) | Apr 24, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [216cd2fc72](https://linux-hardware.org/?probe=216cd2fc72) | Apr 24, 2024 |
| ASUSTek       | X555QG                      | Notebook    | [c905efd379](https://linux-hardware.org/?probe=c905efd379) | Apr 23, 2024 |
| ASUSTek       | X555QG                      | Notebook    | [26b8da2305](https://linux-hardware.org/?probe=26b8da2305) | Apr 23, 2024 |
| ASUSTek       | K42F                        | Notebook    | [f29299723c](https://linux-hardware.org/?probe=f29299723c) | Apr 23, 2024 |
| Lenovo        | B575e 36852BG               | Notebook    | [c2c9ec964e](https://linux-hardware.org/?probe=c2c9ec964e) | Apr 23, 2024 |
| ASUSTek       | K42F                        | Notebook    | [63b454fa02](https://linux-hardware.org/?probe=63b454fa02) | Apr 23, 2024 |
| Lenovo        | B575e 36852BG               | Notebook    | [d168fb33c4](https://linux-hardware.org/?probe=d168fb33c4) | Apr 23, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [8049fc6b37](https://linux-hardware.org/?probe=8049fc6b37) | Apr 23, 2024 |
| Toshiba       | Satellite C850D-11C         | Notebook    | [beccadec71](https://linux-hardware.org/?probe=beccadec71) | Apr 22, 2024 |
| HP            | 8265                        | Desktop     | [17dd357578](https://linux-hardware.org/?probe=17dd357578) | Apr 21, 2024 |
| Fujitsu       | FMVA40B1RJ                  | Notebook    | [b0d3f0b365](https://linux-hardware.org/?probe=b0d3f0b365) | Apr 20, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [bf1e4f8d6a](https://linux-hardware.org/?probe=bf1e4f8d6a) | Apr 20, 2024 |
| HP            | 8184 X4                     | Desktop     | [e110e13968](https://linux-hardware.org/?probe=e110e13968) | Apr 19, 2024 |
| HP            | 3031h                       | Desktop     | [1d9c5e06d3](https://linux-hardware.org/?probe=1d9c5e06d3) | Apr 18, 2024 |
| HP            | EliteBook 6930p             | Notebook    | [263d72f3c6](https://linux-hardware.org/?probe=263d72f3c6) | Apr 17, 2024 |
| Unknown       | Unknown                     | Notebook    | [10d92e98c0](https://linux-hardware.org/?probe=10d92e98c0) | Apr 16, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [c1bd4e2de3](https://linux-hardware.org/?probe=c1bd4e2de3) | Apr 14, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [caf43c2754](https://linux-hardware.org/?probe=caf43c2754) | Apr 14, 2024 |
| HP            | 250 G4 Notebook PC          | Notebook    | [2fcb542c43](https://linux-hardware.org/?probe=2fcb542c43) | Apr 14, 2024 |
| Prestigio     | Smartbook PSB116A           | Desktop     | [cc592e784e](https://linux-hardware.org/?probe=cc592e784e) | Apr 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [94f12b2951](https://linux-hardware.org/?probe=94f12b2951) | Apr 11, 2024 |
| Unknown       | M-140BI3                    | Notebook    | [491b1013ab](https://linux-hardware.org/?probe=491b1013ab) | Apr 11, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8f232e4e6c](https://linux-hardware.org/?probe=8f232e4e6c) | Apr 11, 2024 |
| Biostar       | TA75M+                      | Desktop     | [24de8dbd0b](https://linux-hardware.org/?probe=24de8dbd0b) | Apr 10, 2024 |
| HP            | Pavilion g7                 | Notebook    | [6d84e70e34](https://linux-hardware.org/?probe=6d84e70e34) | Apr 10, 2024 |
| Lenovo        | ThinkPad X201 3680A44       | Notebook    | [db6aadf372](https://linux-hardware.org/?probe=db6aadf372) | Apr 10, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [47ad6cd23e](https://linux-hardware.org/?probe=47ad6cd23e) | Apr 05, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [9b5914816a](https://linux-hardware.org/?probe=9b5914816a) | Apr 05, 2024 |
| Dell          | Latitude E6410              | Notebook    | [7c4144e1df](https://linux-hardware.org/?probe=7c4144e1df) | Apr 05, 2024 |
| ASRock        | H61M-VG3                    | Desktop     | [82fa2b1397](https://linux-hardware.org/?probe=82fa2b1397) | Apr 04, 2024 |
| Acer          | Extensa 5630                | Notebook    | [224d74c060](https://linux-hardware.org/?probe=224d74c060) | Apr 04, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [7a19eed833](https://linux-hardware.org/?probe=7a19eed833) | Apr 03, 2024 |
| Acer          | Aspire XC-780               | Desktop     | [28ef93502a](https://linux-hardware.org/?probe=28ef93502a) | Apr 03, 2024 |
| Acer          | Aspire 3000                 | Notebook    | [1d2fad06c8](https://linux-hardware.org/?probe=1d2fad06c8) | Apr 02, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E20... | Notebook    | [83edc14408](https://linux-hardware.org/?probe=83edc14408) | Mar 30, 2024 |
| AZW           | MINI S                      | Desktop     | [b915778838](https://linux-hardware.org/?probe=b915778838) | Mar 30, 2024 |
| HP            | 250 G4 Notebook PC          | Notebook    | [82ae07c449](https://linux-hardware.org/?probe=82ae07c449) | Mar 29, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [6c9bf73f0c](https://linux-hardware.org/?probe=6c9bf73f0c) | Mar 28, 2024 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [8d88a75722](https://linux-hardware.org/?probe=8d88a75722) | Mar 27, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a47bfb1a29](https://linux-hardware.org/?probe=a47bfb1a29) | Mar 27, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [04ef2627e2](https://linux-hardware.org/?probe=04ef2627e2) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [0ece65fa78](https://linux-hardware.org/?probe=0ece65fa78) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [b909136c03](https://linux-hardware.org/?probe=b909136c03) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [d93ff94b95](https://linux-hardware.org/?probe=d93ff94b95) | Mar 27, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4e434bb17](https://linux-hardware.org/?probe=b4e434bb17) | Mar 27, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [47de08fbc7](https://linux-hardware.org/?probe=47de08fbc7) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [4e7f4f9166](https://linux-hardware.org/?probe=4e7f4f9166) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [4533e58601](https://linux-hardware.org/?probe=4533e58601) | Mar 26, 2024 |
| Acer          | Extensa 2540                | Notebook    | [3e49d36612](https://linux-hardware.org/?probe=3e49d36612) | Mar 26, 2024 |
| Supermicro    | X8DTT-IBX                   | Server      | [d380208ff7](https://linux-hardware.org/?probe=d380208ff7) | Mar 26, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [46b79e7d26](https://linux-hardware.org/?probe=46b79e7d26) | Mar 26, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [b3bbd8f0a3](https://linux-hardware.org/?probe=b3bbd8f0a3) | Mar 23, 2024 |
| HP            | Laptop 14-em0xxx            | Notebook    | [3f937a527b](https://linux-hardware.org/?probe=3f937a527b) | Mar 23, 2024 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [8dfcfff063](https://linux-hardware.org/?probe=8dfcfff063) | Mar 23, 2024 |
| Samsung       | N100                        | Notebook    | [d7a66b3835](https://linux-hardware.org/?probe=d7a66b3835) | Mar 22, 2024 |
| Sony          | VGN-TZ21MN_N                | Notebook    | [1e1a62727b](https://linux-hardware.org/?probe=1e1a62727b) | Mar 19, 2024 |
| ASUSTek       | P5KC                        | Desktop     | [4b54f8d3f2](https://linux-hardware.org/?probe=4b54f8d3f2) | Mar 18, 2024 |
| Unknown       | Unknown                     | Notebook    | [27317f4bcf](https://linux-hardware.org/?probe=27317f4bcf) | Mar 18, 2024 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [5603a5896d](https://linux-hardware.org/?probe=5603a5896d) | Mar 17, 2024 |
| ODM           | Unknown                     | Notebook    | [5a87f7eaeb](https://linux-hardware.org/?probe=5a87f7eaeb) | Mar 17, 2024 |
| Sony          | VPCW216AG                   | Notebook    | [c607fc8a6b](https://linux-hardware.org/?probe=c607fc8a6b) | Mar 16, 2024 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [0dd66d219d](https://linux-hardware.org/?probe=0dd66d219d) | Mar 16, 2024 |
| HP            | Split 13 x2 PC              | Notebook    | [447e4a6951](https://linux-hardware.org/?probe=447e4a6951) | Mar 14, 2024 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [c63473fd10](https://linux-hardware.org/?probe=c63473fd10) | Mar 12, 2024 |
| HP            | Notebook                    | Notebook    | [51a929c53a](https://linux-hardware.org/?probe=51a929c53a) | Mar 08, 2024 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [61e1fc891a](https://linux-hardware.org/?probe=61e1fc891a) | Mar 07, 2024 |
| Sony          | SVF1521NSTB                 | Notebook    | [b9f4d235c9](https://linux-hardware.org/?probe=b9f4d235c9) | Mar 06, 2024 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [00c46d511e](https://linux-hardware.org/?probe=00c46d511e) | Mar 06, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [b4a202211e](https://linux-hardware.org/?probe=b4a202211e) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [025b54a984](https://linux-hardware.org/?probe=025b54a984) | Mar 06, 2024 |
| HP            | Notebook                    | Notebook    | [5f90d8f25b](https://linux-hardware.org/?probe=5f90d8f25b) | Mar 06, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [326d4bbffb](https://linux-hardware.org/?probe=326d4bbffb) | Mar 05, 2024 |
| Fujitsu       | FMVC05005                   | Notebook    | [af1cd1c78b](https://linux-hardware.org/?probe=af1cd1c78b) | Mar 04, 2024 |
| Sony          | VPCEB3C4R                   | Notebook    | [f63a65b29f](https://linux-hardware.org/?probe=f63a65b29f) | Mar 04, 2024 |
| MSI           | MS-168A                     | Notebook    | [1625072479](https://linux-hardware.org/?probe=1625072479) | Mar 02, 2024 |
| MSI           | MS-168A                     | Notebook    | [cae162bcad](https://linux-hardware.org/?probe=cae162bcad) | Mar 02, 2024 |
| HP            | 250 G1                      | Notebook    | [805489bf43](https://linux-hardware.org/?probe=805489bf43) | Feb 26, 2024 |
| Acer          | Aspire X1700                | Desktop     | [20842b7abc](https://linux-hardware.org/?probe=20842b7abc) | Feb 26, 2024 |
| Google        | Lindar                      | Notebook    | [0f6ee4fa1f](https://linux-hardware.org/?probe=0f6ee4fa1f) | Feb 25, 2024 |
| ASRock        | HM55-HT                     | Desktop     | [f6669716da](https://linux-hardware.org/?probe=f6669716da) | Feb 24, 2024 |
| Dell          | Latitude D620               | Notebook    | [2ca5ca0cad](https://linux-hardware.org/?probe=2ca5ca0cad) | Feb 24, 2024 |
| EPoX Compu... | MCP61 Series                | Desktop     | [8028d0a8d1](https://linux-hardware.org/?probe=8028d0a8d1) | Feb 24, 2024 |
| Dell          | Latitude D620               | Notebook    | [78a800debc](https://linux-hardware.org/?probe=78a800debc) | Feb 22, 2024 |
| Dell          | 042P49 A01                  | Desktop     | [3e64e4a44e](https://linux-hardware.org/?probe=3e64e4a44e) | Feb 22, 2024 |
| FOUNDER Co... | M672+968                    | Notebook    | [0dd60ea26f](https://linux-hardware.org/?probe=0dd60ea26f) | Feb 22, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7c9a199867](https://linux-hardware.org/?probe=7c9a199867) | Feb 21, 2024 |
| Sony          | VPCEB3C4R                   | Notebook    | [93a9016bf3](https://linux-hardware.org/?probe=93a9016bf3) | Feb 20, 2024 |
| Dell          | Inspiron 531s               | Desktop     | [0d9877a337](https://linux-hardware.org/?probe=0d9877a337) | Feb 19, 2024 |
| HP            | Presario M2000 (EE629LA#... | Notebook    | [302398d57c](https://linux-hardware.org/?probe=302398d57c) | Feb 18, 2024 |
| HP            | Presario M2000 (EE629LA#... | Notebook    | [c44f12d85d](https://linux-hardware.org/?probe=c44f12d85d) | Feb 18, 2024 |
| HP            | 83DD                        | Mini pc     | [71dc39d477](https://linux-hardware.org/?probe=71dc39d477) | Feb 17, 2024 |
| HP            | 83DD                        | Mini pc     | [8a763f4ef6](https://linux-hardware.org/?probe=8a763f4ef6) | Feb 17, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [edc56f85b9](https://linux-hardware.org/?probe=edc56f85b9) | Feb 17, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d18785d54f](https://linux-hardware.org/?probe=d18785d54f) | Feb 16, 2024 |
| Samsung       | 530XBB                      | Notebook    | [f98c88531f](https://linux-hardware.org/?probe=f98c88531f) | Feb 15, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d21dee5d98](https://linux-hardware.org/?probe=d21dee5d98) | Feb 13, 2024 |
| Digibras      | NH4CU53                     | Notebook    | [1e3d9f1795](https://linux-hardware.org/?probe=1e3d9f1795) | Feb 10, 2024 |
| Dell          | Latitude 3340               | Notebook    | [f1233f10b5](https://linux-hardware.org/?probe=f1233f10b5) | Feb 10, 2024 |
| Google        | Lindar                      | Notebook    | [e3a071ae43](https://linux-hardware.org/?probe=e3a071ae43) | Feb 10, 2024 |
| Dell          | Latitude E5430 vPro         | Notebook    | [9e120d90b8](https://linux-hardware.org/?probe=9e120d90b8) | Feb 09, 2024 |
| ASRock        | H110M Combo-G               | Desktop     | [319e01fd31](https://linux-hardware.org/?probe=319e01fd31) | Feb 09, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | Notebook    | [52d94c62ce](https://linux-hardware.org/?probe=52d94c62ce) | Feb 08, 2024 |
| MSI           | MS-7309                     | Desktop     | [dd1dea1c0e](https://linux-hardware.org/?probe=dd1dea1c0e) | Feb 07, 2024 |
| Fujitsu       | LIFEBOOK U7313              | Notebook    | [f1f1ab12ba](https://linux-hardware.org/?probe=f1f1ab12ba) | Feb 07, 2024 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [f63c9d5f5a](https://linux-hardware.org/?probe=f63c9d5f5a) | Feb 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [5fa467241b](https://linux-hardware.org/?probe=5fa467241b) | Feb 05, 2024 |
| Itautec       | Infoway w7430               | Notebook    | [4928095170](https://linux-hardware.org/?probe=4928095170) | Feb 05, 2024 |
| Acer          | Aspire 5951G                | Notebook    | [e583f21b3a](https://linux-hardware.org/?probe=e583f21b3a) | Feb 05, 2024 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [eb979afe2e](https://linux-hardware.org/?probe=eb979afe2e) | Feb 04, 2024 |
| HP            | Pavilion dv6                | Notebook    | [52c0814c31](https://linux-hardware.org/?probe=52c0814c31) | Feb 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [d477732dfa](https://linux-hardware.org/?probe=d477732dfa) | Feb 03, 2024 |
| ODM           | Unknown                     | Notebook    | [0ad5efc9ef](https://linux-hardware.org/?probe=0ad5efc9ef) | Feb 03, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [e7f247621c](https://linux-hardware.org/?probe=e7f247621c) | Feb 02, 2024 |
| Lenovo        | G405 20239                  | Notebook    | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [793c3d3b4c](https://linux-hardware.org/?probe=793c3d3b4c) | Jan 31, 2024 |
| Lenovo        | G575 20081                  | Notebook    | [162e1f81cf](https://linux-hardware.org/?probe=162e1f81cf) | Jan 31, 2024 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [a72292c97b](https://linux-hardware.org/?probe=a72292c97b) | Jan 31, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [dcd752673f](https://linux-hardware.org/?probe=dcd752673f) | Jan 29, 2024 |
| Acer          | Aspire ES1-520              | Notebook    | [633516e35a](https://linux-hardware.org/?probe=633516e35a) | Jan 25, 2024 |
| Lenovo        | ThinkPad T60p 20078JU       | Notebook    | [6c83cf1141](https://linux-hardware.org/?probe=6c83cf1141) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ODM           | Unknown                     | Notebook    | [2d8310fe96](https://linux-hardware.org/?probe=2d8310fe96) | Jan 24, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [f181c086e3](https://linux-hardware.org/?probe=f181c086e3) | Jan 23, 2024 |
| Dell          | 0DF42J A00                  | Desktop     | [5a172ff7ec](https://linux-hardware.org/?probe=5a172ff7ec) | Jan 22, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [c0eb7c0861](https://linux-hardware.org/?probe=c0eb7c0861) | Jan 21, 2024 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [9b6eb3d320](https://linux-hardware.org/?probe=9b6eb3d320) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | Desktop     | [5d46b8d1b3](https://linux-hardware.org/?probe=5d46b8d1b3) | Jan 19, 2024 |
| Dell          | 018D1Y A00                  | Desktop     | [cf089739df](https://linux-hardware.org/?probe=cf089739df) | Jan 19, 2024 |
| ZOTAC         | NM10                        | Desktop     | [e185a9b292](https://linux-hardware.org/?probe=e185a9b292) | Jan 18, 2024 |
| Intel         | H61                         | Desktop     | [1d639194e4](https://linux-hardware.org/?probe=1d639194e4) | Jan 17, 2024 |
| HP            | 3397                        | Desktop     | [a46224b9bc](https://linux-hardware.org/?probe=a46224b9bc) | Jan 17, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [817daf41f7](https://linux-hardware.org/?probe=817daf41f7) | Jan 16, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [87ad2c7889](https://linux-hardware.org/?probe=87ad2c7889) | Jan 16, 2024 |
| Lenovo        | ThinkPad SL 2746F2G         | Notebook    | [47b2e38ff4](https://linux-hardware.org/?probe=47b2e38ff4) | Jan 16, 2024 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [907bccb062](https://linux-hardware.org/?probe=907bccb062) | Jan 16, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [45399ef111](https://linux-hardware.org/?probe=45399ef111) | Jan 15, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [d6239c4393](https://linux-hardware.org/?probe=d6239c4393) | Jan 15, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [dce09bb097](https://linux-hardware.org/?probe=dce09bb097) | Jan 14, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [c0f0afd78c](https://linux-hardware.org/?probe=c0f0afd78c) | Jan 14, 2024 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [82175efff8](https://linux-hardware.org/?probe=82175efff8) | Jan 14, 2024 |
| Foxconn       | 2AA9h                       | Desktop     | [40459d91a4](https://linux-hardware.org/?probe=40459d91a4) | Jan 11, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [681ea2eb1a](https://linux-hardware.org/?probe=681ea2eb1a) | Jan 10, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [2894cc00dc](https://linux-hardware.org/?probe=2894cc00dc) | Jan 10, 2024 |
| iRU           | 15TLI                       | Notebook    | [4d83aee906](https://linux-hardware.org/?probe=4d83aee906) | Jan 10, 2024 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [5654e285db](https://linux-hardware.org/?probe=5654e285db) | Jan 10, 2024 |
| iRU           | 15TLI                       | Notebook    | [d318923a72](https://linux-hardware.org/?probe=d318923a72) | Jan 09, 2024 |
| Supermicro    | X12DPi-N6                   | Server      | [fe3ca134e4](https://linux-hardware.org/?probe=fe3ca134e4) | Jan 09, 2024 |
| Supermicro    | X12DPi-N6                   | Server      | [ba90dbeba2](https://linux-hardware.org/?probe=ba90dbeba2) | Jan 09, 2024 |
| ASUSTek       | K53U                        | Notebook    | [df631caaa2](https://linux-hardware.org/?probe=df631caaa2) | Jan 09, 2024 |
| Lenovo        | ThinkPad T430 23477C7       | Notebook    | [db1c43a6a6](https://linux-hardware.org/?probe=db1c43a6a6) | Jan 09, 2024 |
| HP            | 240 G6 Notebook PC          | Notebook    | [52fa49b647](https://linux-hardware.org/?probe=52fa49b647) | Jan 08, 2024 |
| HP            | Notebook                    | Notebook    | [79932769a2](https://linux-hardware.org/?probe=79932769a2) | Jan 08, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [3a14a938f8](https://linux-hardware.org/?probe=3a14a938f8) | Jan 08, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [186230d9c6](https://linux-hardware.org/?probe=186230d9c6) | Jan 08, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [9aa6d7d7c0](https://linux-hardware.org/?probe=9aa6d7d7c0) | Jan 07, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f8471bbcf4](https://linux-hardware.org/?probe=f8471bbcf4) | Jan 04, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3290e9841e](https://linux-hardware.org/?probe=3290e9841e) | Jan 04, 2024 |
| Dell          | 0CRH6C A00                  | Desktop     | [6c4bafe7b1](https://linux-hardware.org/?probe=6c4bafe7b1) | Jan 04, 2024 |
| Lenovo        | 3102 SDK0J40700 WIN 3258... | Desktop     | [afda94711c](https://linux-hardware.org/?probe=afda94711c) | Jan 04, 2024 |
| Google        | Electro                     | Notebook    | [74ed1caffe](https://linux-hardware.org/?probe=74ed1caffe) | Jan 04, 2024 |
| Packard Be... | EasyNote LM85               | Notebook    | [e756bb57ba](https://linux-hardware.org/?probe=e756bb57ba) | Jan 03, 2024 |
| Acer          | Aspire ES1-520              | Notebook    | [922ef3d7e1](https://linux-hardware.org/?probe=922ef3d7e1) | Jan 03, 2024 |
| Koloe         | X58                         | Desktop     | [2a3e4788ed](https://linux-hardware.org/?probe=2a3e4788ed) | Jan 03, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [481cbbf231](https://linux-hardware.org/?probe=481cbbf231) | Jan 03, 2024 |
| HP            | Notebook                    | Notebook    | [3db48f7d59](https://linux-hardware.org/?probe=3db48f7d59) | Jan 02, 2024 |
| Apple         | MacBookAir4,2               | Notebook    | [7ebd4a00e7](https://linux-hardware.org/?probe=7ebd4a00e7) | Dec 31, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [ba4ad2bc18](https://linux-hardware.org/?probe=ba4ad2bc18) | Dec 31, 2023 |
| HP            | ProBook 470 G3              | Notebook    | [22bd0ee412](https://linux-hardware.org/?probe=22bd0ee412) | Dec 30, 2023 |
| Dell          | 0PU052                      | Desktop     | [7da56e0b33](https://linux-hardware.org/?probe=7da56e0b33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | Notebook    | [af69ec2d33](https://linux-hardware.org/?probe=af69ec2d33) | Dec 29, 2023 |
| Lenovo        | ThinkPad W540 20BG001KFR    | Notebook    | [143c6b4161](https://linux-hardware.org/?probe=143c6b4161) | Dec 29, 2023 |
| Chuwi         | GemiBook Plus               | Notebook    | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| EPoX Compu... | MCP61 Series                | Desktop     | [730493cca3](https://linux-hardware.org/?probe=730493cca3) | Dec 29, 2023 |
| Qilive        | QW20141BSP                  | Notebook    | [3f2d1e03c3](https://linux-hardware.org/?probe=3f2d1e03c3) | Dec 28, 2023 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [8f6b669800](https://linux-hardware.org/?probe=8f6b669800) | Dec 27, 2023 |
| Google        | Swanky                      | Notebook    | [12fd273db1](https://linux-hardware.org/?probe=12fd273db1) | Dec 27, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [54ca5c9e74](https://linux-hardware.org/?probe=54ca5c9e74) | Dec 25, 2023 |
| Google        | Madoo                       | Notebook    | [14e757fdb4](https://linux-hardware.org/?probe=14e757fdb4) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [0b4e0e5e2b](https://linux-hardware.org/?probe=0b4e0e5e2b) | Dec 24, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ba98d8db9](https://linux-hardware.org/?probe=3ba98d8db9) | Dec 24, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [538aa9126b](https://linux-hardware.org/?probe=538aa9126b) | Dec 23, 2023 |
| ATARI         | VCS 800 Black Walnut        | Notebook    | [34456982d3](https://linux-hardware.org/?probe=34456982d3) | Dec 23, 2023 |
| Google        | Treeya                      | Notebook    | [b6541ef594](https://linux-hardware.org/?probe=b6541ef594) | Dec 19, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [9e7c59246d](https://linux-hardware.org/?probe=9e7c59246d) | Dec 19, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [6528f813b7](https://linux-hardware.org/?probe=6528f813b7) | Dec 17, 2023 |
| Google        | Candy                       | Notebook    | [be56752bfd](https://linux-hardware.org/?probe=be56752bfd) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [65d7452931](https://linux-hardware.org/?probe=65d7452931) | Dec 17, 2023 |
| PELADN        | HA-3                        | Desktop     | [cd40102512](https://linux-hardware.org/?probe=cd40102512) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [acdb6ef8aa](https://linux-hardware.org/?probe=acdb6ef8aa) | Dec 17, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [a3015ca40c](https://linux-hardware.org/?probe=a3015ca40c) | Dec 14, 2023 |
| HP            | ZBook 17                    | Notebook    | [d1269ca08c](https://linux-hardware.org/?probe=d1269ca08c) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Lenovo        | 3111 SDK0J40700 WIN 3258... | Mini pc     | [52be4d3e15](https://linux-hardware.org/?probe=52be4d3e15) | Dec 12, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [e126cdbf4b](https://linux-hardware.org/?probe=e126cdbf4b) | Dec 10, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [213b775f8b](https://linux-hardware.org/?probe=213b775f8b) | Dec 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [d4c43fe4f4](https://linux-hardware.org/?probe=d4c43fe4f4) | Dec 08, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [5ebbbca196](https://linux-hardware.org/?probe=5ebbbca196) | Dec 04, 2023 |
| Dell          | 0PU052                      | Desktop     | [4a653cc26a](https://linux-hardware.org/?probe=4a653cc26a) | Dec 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d25f6b4dd3](https://linux-hardware.org/?probe=d25f6b4dd3) | Dec 02, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [5a628a7b0f](https://linux-hardware.org/?probe=5a628a7b0f) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3b82362902](https://linux-hardware.org/?probe=3b82362902) | Nov 29, 2023 |
| SGIN          | M15                         | Notebook    | [c7fb994367](https://linux-hardware.org/?probe=c7fb994367) | Nov 28, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a03b74a3d3](https://linux-hardware.org/?probe=a03b74a3d3) | Nov 28, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [dedc54db8f](https://linux-hardware.org/?probe=dedc54db8f) | Nov 27, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [370ddc00c4](https://linux-hardware.org/?probe=370ddc00c4) | Nov 24, 2023 |
| Chuwi         | X312B                       | Notebook    | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| eMachines     | EL1358                      | Desktop     | [f22b0b98c3](https://linux-hardware.org/?probe=f22b0b98c3) | Nov 23, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1e58f5a4f9](https://linux-hardware.org/?probe=1e58f5a4f9) | Nov 21, 2023 |
| MSI           | Raider GE76 12UE            | Notebook    | [bad07cc00d](https://linux-hardware.org/?probe=bad07cc00d) | Nov 20, 2023 |
| Packard Be... | ENLE11BZ                    | Notebook    | [905ad855b3](https://linux-hardware.org/?probe=905ad855b3) | Nov 19, 2023 |
| ASUSTek       | X201E                       | Notebook    | [3532136698](https://linux-hardware.org/?probe=3532136698) | Nov 18, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d297e1365c](https://linux-hardware.org/?probe=d297e1365c) | Nov 16, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [dde4f98b29](https://linux-hardware.org/?probe=dde4f98b29) | Nov 16, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [b7dda3ece0](https://linux-hardware.org/?probe=b7dda3ece0) | Nov 14, 2023 |
| Acer          | Extensa 5620                | Notebook    | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| MSI           | MS-7309                     | Desktop     | [c6ca259cae](https://linux-hardware.org/?probe=c6ca259cae) | Nov 13, 2023 |
| Intel         | STK2MV64CC H89290-502       | Desktop     | [041670b7d8](https://linux-hardware.org/?probe=041670b7d8) | Nov 13, 2023 |
| ASUSTek       | T100TAS                     | Notebook    | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [988c1c2454](https://linux-hardware.org/?probe=988c1c2454) | Nov 12, 2023 |
| HP            | 255 G1                      | Notebook    | [9aa30be183](https://linux-hardware.org/?probe=9aa30be183) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fa680be8d9](https://linux-hardware.org/?probe=fa680be8d9) | Nov 10, 2023 |
| ASUSTek       | X550ZE                      | Notebook    | [31d4fc8694](https://linux-hardware.org/?probe=31d4fc8694) | Nov 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [94bc809d57](https://linux-hardware.org/?probe=94bc809d57) | Nov 05, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| PCChips       | P49G                        | Desktop     | [6b1de00356](https://linux-hardware.org/?probe=6b1de00356) | Nov 02, 2023 |
| ZOTAC         | NM10                        | Desktop     | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [d63ccd5259](https://linux-hardware.org/?probe=d63ccd5259) | Oct 30, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [4f0b8be2f6](https://linux-hardware.org/?probe=4f0b8be2f6) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [48785f697c](https://linux-hardware.org/?probe=48785f697c) | Oct 29, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [3fa8a23f12](https://linux-hardware.org/?probe=3fa8a23f12) | Oct 29, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c86a40c419](https://linux-hardware.org/?probe=c86a40c419) | Oct 28, 2023 |
| Intel         | H61                         | Desktop     | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Acer          | Veriton N4660G              | Desktop     | [712511f568](https://linux-hardware.org/?probe=712511f568) | Oct 27, 2023 |
| Acer          | Aspire 9300                 | Notebook    | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5a23f97862](https://linux-hardware.org/?probe=5a23f97862) | Oct 23, 2023 |
| Dixonsxp      | Unknown                     | Notebook    | [da9f723fd0](https://linux-hardware.org/?probe=da9f723fd0) | Oct 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [8c9d16e737](https://linux-hardware.org/?probe=8c9d16e737) | Oct 22, 2023 |
| ZOTAC         | NM10                        | Desktop     | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [5ddf61741f](https://linux-hardware.org/?probe=5ddf61741f) | Oct 20, 2023 |
| HP            | 8265                        | Desktop     | [f1bdedb075](https://linux-hardware.org/?probe=f1bdedb075) | Oct 20, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [8ff07b1c79](https://linux-hardware.org/?probe=8ff07b1c79) | Oct 19, 2023 |
| Positivo      | AT300b                      | Notebook    | [a39989b55b](https://linux-hardware.org/?probe=a39989b55b) | Oct 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60b3dbfa2](https://linux-hardware.org/?probe=c60b3dbfa2) | Oct 17, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20D900... | Notebook    | [9d142e587e](https://linux-hardware.org/?probe=9d142e587e) | Oct 17, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [99490448ae](https://linux-hardware.org/?probe=99490448ae) | Oct 16, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [431b672bf5](https://linux-hardware.org/?probe=431b672bf5) | Oct 16, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [1f161ae269](https://linux-hardware.org/?probe=1f161ae269) | Oct 16, 2023 |
| Google        | Careena                     | Notebook    | [8359c8c3e8](https://linux-hardware.org/?probe=8359c8c3e8) | Oct 15, 2023 |
| Google        | Careena                     | Notebook    | [4292c49150](https://linux-hardware.org/?probe=4292c49150) | Oct 15, 2023 |
| HP            | Notebook                    | Notebook    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Thomson       | NEO14-4W64                  | Notebook    | [f68e52a8a1](https://linux-hardware.org/?probe=f68e52a8a1) | Oct 12, 2023 |
| BLANK         | Intel powered classmate ... | Notebook    | [78cc4b7937](https://linux-hardware.org/?probe=78cc4b7937) | Oct 11, 2023 |
| BLANK         | Intel powered classmate ... | Notebook    | [bc4093e3c7](https://linux-hardware.org/?probe=bc4093e3c7) | Oct 11, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [2bb1495e06](https://linux-hardware.org/?probe=2bb1495e06) | Oct 08, 2023 |
| Google        | Sasuke                      | Notebook    | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [f8ad7736e2](https://linux-hardware.org/?probe=f8ad7736e2) | Oct 07, 2023 |
| Insyde        | Braswell                    | Notebook    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bf8761b854](https://linux-hardware.org/?probe=bf8761b854) | Oct 06, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [f88a18cfef](https://linux-hardware.org/?probe=f88a18cfef) | Oct 06, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| Getac         | X500G3                      | Notebook    | [919772eed0](https://linux-hardware.org/?probe=919772eed0) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | Notebook    | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [d14bc5c139](https://linux-hardware.org/?probe=d14bc5c139) | Sep 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [f4326ad956](https://linux-hardware.org/?probe=f4326ad956) | Sep 26, 2023 |
| ASUSTek       | E1600WKA                    | All in one  | [43c8a9b758](https://linux-hardware.org/?probe=43c8a9b758) | Sep 26, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [3ff273b73c](https://linux-hardware.org/?probe=3ff273b73c) | Sep 26, 2023 |
| Intel         | H61                         | Desktop     | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| ASUSTek       | X451MA                      | Notebook    | [ed779c5de4](https://linux-hardware.org/?probe=ed779c5de4) | Sep 20, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [7b1aae3e2b](https://linux-hardware.org/?probe=7b1aae3e2b) | Sep 20, 2023 |
| Mini PC       | Cherry Trail CR             | Notebook    | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [47d423039b](https://linux-hardware.org/?probe=47d423039b) | Sep 19, 2023 |
| Dell          | Precision 3570              | Notebook    | [fd3441ff1d](https://linux-hardware.org/?probe=fd3441ff1d) | Sep 18, 2023 |
| Google        | Blooglet                    | Notebook    | [79ce749655](https://linux-hardware.org/?probe=79ce749655) | Sep 17, 2023 |
| Intel         | D945GCZ AAD32112-503        | Desktop     | [806f698174](https://linux-hardware.org/?probe=806f698174) | Sep 14, 2023 |
| HP            | 15                          | Notebook    | [03e1207549](https://linux-hardware.org/?probe=03e1207549) | Sep 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [04666fa9b7](https://linux-hardware.org/?probe=04666fa9b7) | Sep 11, 2023 |
| HP            | 2000                        | Notebook    | [48790bd831](https://linux-hardware.org/?probe=48790bd831) | Sep 09, 2023 |
| HP            | 2000                        | Notebook    | [ce9ba2b7c4](https://linux-hardware.org/?probe=ce9ba2b7c4) | Sep 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| eMachines     | eM350                       | Notebook    | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [69fec63660](https://linux-hardware.org/?probe=69fec63660) | Sep 04, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [ea00f871b9](https://linux-hardware.org/?probe=ea00f871b9) | Sep 04, 2023 |
| HP            | 255 G2                      | Notebook    | [27b48aa011](https://linux-hardware.org/?probe=27b48aa011) | Sep 02, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [8ba55e98ec](https://linux-hardware.org/?probe=8ba55e98ec) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d169572a6b](https://linux-hardware.org/?probe=d169572a6b) | Aug 31, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [ddcb97361b](https://linux-hardware.org/?probe=ddcb97361b) | Aug 30, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [cab1480dc6](https://linux-hardware.org/?probe=cab1480dc6) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2bd35d44f1](https://linux-hardware.org/?probe=2bd35d44f1) | Aug 29, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [f37ab96772](https://linux-hardware.org/?probe=f37ab96772) | Aug 28, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [7abf0d31d8](https://linux-hardware.org/?probe=7abf0d31d8) | Aug 28, 2023 |
| Toshiba       | Satellite P770              | Notebook    | [8618c83c93](https://linux-hardware.org/?probe=8618c83c93) | Aug 26, 2023 |
| Google        | Robo                        | Notebook    | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| Acer          | Predator G3610              | Desktop     | [04153b05c7](https://linux-hardware.org/?probe=04153b05c7) | Aug 22, 2023 |
| Compal        | PBL20                       | Notebook    | [ae09076b4e](https://linux-hardware.org/?probe=ae09076b4e) | Aug 22, 2023 |
| HP            | Notebook                    | Notebook    | [11d2993965](https://linux-hardware.org/?probe=11d2993965) | Aug 20, 2023 |
| Google        | Madoo                       | Notebook    | [8eea1017dc](https://linux-hardware.org/?probe=8eea1017dc) | Aug 20, 2023 |
| HP            | Notebook                    | Notebook    | [f6e4865586](https://linux-hardware.org/?probe=f6e4865586) | Aug 19, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [3dfc4104a4](https://linux-hardware.org/?probe=3dfc4104a4) | Aug 18, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [62ecbe2f01](https://linux-hardware.org/?probe=62ecbe2f01) | Aug 18, 2023 |
| Inventec      | DQ Class A02                | Desktop     | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Lenovo        | ThinkPad T430 2349TFK       | Notebook    | [390899a281](https://linux-hardware.org/?probe=390899a281) | Aug 17, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dd8d164747](https://linux-hardware.org/?probe=dd8d164747) | Aug 17, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [374096baa6](https://linux-hardware.org/?probe=374096baa6) | Aug 15, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | Desktop     | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Apple         | Mac-F223BEC8                | Desktop     | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| HP            | Pavilion g7                 | Notebook    | [43351d6476](https://linux-hardware.org/?probe=43351d6476) | Aug 12, 2023 |
| Positivo      | C4128B-1                    | Convertible | [ef67e885dc](https://linux-hardware.org/?probe=ef67e885dc) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Toshiba       | Satellite L875D             | Notebook    | [de1a418102](https://linux-hardware.org/?probe=de1a418102) | Aug 08, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [20532065b5](https://linux-hardware.org/?probe=20532065b5) | Aug 04, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8f6ada13fa](https://linux-hardware.org/?probe=8f6ada13fa) | Aug 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [257fe62454](https://linux-hardware.org/?probe=257fe62454) | Aug 02, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [00d2ac7698](https://linux-hardware.org/?probe=00d2ac7698) | Aug 01, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Unknown       | SCHNEIDER                   | Desktop     | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
| Dell          | Inspiron 1520               | Notebook    | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Lenovo        | ThinkPad T61 7659WCN        | Notebook    | [f447bc27b2](https://linux-hardware.org/?probe=f447bc27b2) | Jul 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4fe4e8b639](https://linux-hardware.org/?probe=4fe4e8b639) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [742d3b24c8](https://linux-hardware.org/?probe=742d3b24c8) | Jul 24, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | Notebook    | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [54c338bb01](https://linux-hardware.org/?probe=54c338bb01) | Jul 22, 2023 |
| Dell          | Inspiron 5576               | Notebook    | [6654328e2c](https://linux-hardware.org/?probe=6654328e2c) | Jul 22, 2023 |
| HP            | 2187 A01                    | Desktop     | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| HP            | 3646h                       | Desktop     | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [b503fa1044](https://linux-hardware.org/?probe=b503fa1044) | Jul 21, 2023 |
| Dell          | Latitude 5290               | Notebook    | [66860827b9](https://linux-hardware.org/?probe=66860827b9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [cd8a01d7ab](https://linux-hardware.org/?probe=cd8a01d7ab) | Jul 19, 2023 |
| Fujitsu       | FMVNC4BC4                   | Notebook    | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E1-771               | Notebook    | [9d53aeea5a](https://linux-hardware.org/?probe=9d53aeea5a) | Jul 19, 2023 |
| HP            | 255 G2                      | Notebook    | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [07809870aa](https://linux-hardware.org/?probe=07809870aa) | Jul 19, 2023 |
| LG Electro... | 15Z90N-U.ARS5U1             | Notebook    | [54b03a096b](https://linux-hardware.org/?probe=54b03a096b) | Jul 19, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [493d7a5ab7](https://linux-hardware.org/?probe=493d7a5ab7) | Jul 12, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [6535e7c6d1](https://linux-hardware.org/?probe=6535e7c6d1) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [8337bfbb61](https://linux-hardware.org/?probe=8337bfbb61) | Jul 08, 2023 |
| Acer          | Swift SFE16-42              | Notebook    | [c8b8a7d737](https://linux-hardware.org/?probe=c8b8a7d737) | Jul 07, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [632958a27e](https://linux-hardware.org/?probe=632958a27e) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| Unknown       | Unknown                     | Other       | [f49e789b52](https://linux-hardware.org/?probe=f49e789b52) | Jul 04, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | Notebook    | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| Google        | Pyro                        | Notebook    | [9632e7a77b](https://linux-hardware.org/?probe=9632e7a77b) | Jul 02, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| eMachines     | eME443                      | Notebook    | [0d6808da66](https://linux-hardware.org/?probe=0d6808da66) | Jun 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [afe6ac4f32](https://linux-hardware.org/?probe=afe6ac4f32) | Jun 27, 2023 |
| Intel         | NUC11ATBC4 M53051-400       | Mini pc     | [7c6c7cff66](https://linux-hardware.org/?probe=7c6c7cff66) | Jun 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [e094f469bc](https://linux-hardware.org/?probe=e094f469bc) | Jun 25, 2023 |
| Sony          | VPCEB37FD                   | Notebook    | [e8d24fe375](https://linux-hardware.org/?probe=e8d24fe375) | Jun 25, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| Pencents      | U50 Standard                | Mini pc     | [96db8365b1](https://linux-hardware.org/?probe=96db8365b1) | Jun 20, 2023 |
| TrekStor      | SurfTab wintron 7.0 ST70... | Notebook    | [b61b22c866](https://linux-hardware.org/?probe=b61b22c866) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | Notebook    | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e4c0eeb007](https://linux-hardware.org/?probe=e4c0eeb007) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [af1a5cda08](https://linux-hardware.org/?probe=af1a5cda08) | Jun 16, 2023 |
| Dell          | Precision 3570              | Notebook    | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | 21B4 A01                    | Desktop     | [16b576ebea](https://linux-hardware.org/?probe=16b576ebea) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| HP            | 3646h                       | Desktop     | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | Notebook    | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| HP            | 3646h                       | Desktop     | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 240 G3                      | Notebook    | [475e3e63ef](https://linux-hardware.org/?probe=475e3e63ef) | Jun 05, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [b6411e69f3](https://linux-hardware.org/?probe=b6411e69f3) | Jun 04, 2023 |
| HP            | 3397                        | Desktop     | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [1375d36b0f](https://linux-hardware.org/?probe=1375d36b0f) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [88c6b12404](https://linux-hardware.org/?probe=88c6b12404) | May 27, 2023 |
| Shanghai Z... | ZEB20 TBD                   | Mini pc     | [84953a504d](https://linux-hardware.org/?probe=84953a504d) | May 26, 2023 |
| Dell          | Latitude E6430              | Notebook    | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbab0f6dd8](https://linux-hardware.org/?probe=cbab0f6dd8) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [ca431e5e80](https://linux-hardware.org/?probe=ca431e5e80) | May 24, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [20c80a45a8](https://linux-hardware.org/?probe=20c80a45a8) | May 22, 2023 |
| Foxconn       | G41MXE-V                    | Desktop     | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [bd6409ee58](https://linux-hardware.org/?probe=bd6409ee58) | May 19, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2d944abb09](https://linux-hardware.org/?probe=2d944abb09) | May 19, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [ce80a21736](https://linux-hardware.org/?probe=ce80a21736) | May 19, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | Desktop     | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| Lenovo        | ThinkPad T400 276522G       | Notebook    | [dc8b38dd37](https://linux-hardware.org/?probe=dc8b38dd37) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [1167f27914](https://linux-hardware.org/?probe=1167f27914) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0145d107e8](https://linux-hardware.org/?probe=0145d107e8) | May 15, 2023 |
| Intel         | W7650                       | Notebook    | [a672f7199c](https://linux-hardware.org/?probe=a672f7199c) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| Toshiba       | Satellite Radius P55W-B     | Notebook    | [e2ed5e2135](https://linux-hardware.org/?probe=e2ed5e2135) | May 11, 2023 |
| Acer          | EQ45M                       | Desktop     | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| libre-comp... | roc-rk3328-cc               | Soc         | [9709c9cf35](https://linux-hardware.org/?probe=9709c9cf35) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0b08b7a631](https://linux-hardware.org/?probe=0b08b7a631) | May 09, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a08e2235cd](https://linux-hardware.org/?probe=a08e2235cd) | May 09, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| HP            | Notebook                    | Notebook    | [70ee3adf89](https://linux-hardware.org/?probe=70ee3adf89) | May 08, 2023 |
| Samsung       | 530XBB                      | Notebook    | [4d039b72a7](https://linux-hardware.org/?probe=4d039b72a7) | May 08, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [8b7b41fde9](https://linux-hardware.org/?probe=8b7b41fde9) | May 07, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [f830561f82](https://linux-hardware.org/?probe=f830561f82) | May 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [cacf6a8831](https://linux-hardware.org/?probe=cacf6a8831) | May 07, 2023 |
| HP            | x2 210                      | Notebook    | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3daf4fbc68](https://linux-hardware.org/?probe=3daf4fbc68) | May 07, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e6309dff56](https://linux-hardware.org/?probe=e6309dff56) | May 05, 2023 |
| Google        | Glimmer                     | Notebook    | [c9ccc1f6c9](https://linux-hardware.org/?probe=c9ccc1f6c9) | May 02, 2023 |
| Google        | Glimmer                     | Notebook    | [f4558038dd](https://linux-hardware.org/?probe=f4558038dd) | May 02, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| Sony          | SVF1521C6EW                 | Notebook    | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [6976f884e6](https://linux-hardware.org/?probe=6976f884e6) | Apr 29, 2023 |
| HP            | Laptop 15-bs2xx             | Notebook    | [ad768363bc](https://linux-hardware.org/?probe=ad768363bc) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Google        | Chell                       | Notebook    | [1d1b263f21](https://linux-hardware.org/?probe=1d1b263f21) | Apr 27, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [e9237f0d53](https://linux-hardware.org/?probe=e9237f0d53) | Apr 27, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [4db8688749](https://linux-hardware.org/?probe=4db8688749) | Apr 25, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | Desktop     | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| Dell          | Latitude 5290               | Notebook    | [54f92464ba](https://linux-hardware.org/?probe=54f92464ba) | Apr 23, 2023 |
| HP            | G42                         | Notebook    | [dd87e935d0](https://linux-hardware.org/?probe=dd87e935d0) | Apr 20, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [f79af9bad0](https://linux-hardware.org/?probe=f79af9bad0) | Apr 20, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [2d8d4a8124](https://linux-hardware.org/?probe=2d8d4a8124) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [70a0b986fa](https://linux-hardware.org/?probe=70a0b986fa) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [e233174fb3](https://linux-hardware.org/?probe=e233174fb3) | Apr 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [db0d2a4c4e](https://linux-hardware.org/?probe=db0d2a4c4e) | Apr 14, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Intel         | W7650                       | Notebook    | [3e4c54a5f0](https://linux-hardware.org/?probe=3e4c54a5f0) | Apr 11, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| Toshiba       | Satellite P70-A             | Notebook    | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [f982fd86f7](https://linux-hardware.org/?probe=f982fd86f7) | Apr 05, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b16afcac8b](https://linux-hardware.org/?probe=b16afcac8b) | Apr 03, 2023 |
| ASRock        | G31M-S                      | Desktop     | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [0e18c3546c](https://linux-hardware.org/?probe=0e18c3546c) | Apr 01, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| ASRock        | G31M-S                      | Desktop     | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| ASRock        | G31M-S                      | Desktop     | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | Desktop     | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [35eaaaac45](https://linux-hardware.org/?probe=35eaaaac45) | Mar 26, 2023 |
| Packard Be... | EasyNote SB65               | Notebook    | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [872e7f18c5](https://linux-hardware.org/?probe=872e7f18c5) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| Samsung       | 530XBB                      | Notebook    | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [104f6a754e](https://linux-hardware.org/?probe=104f6a754e) | Mar 22, 2023 |
| HP            | 89DC 0100                   | All in one  | [d8afbb81f9](https://linux-hardware.org/?probe=d8afbb81f9) | Mar 21, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | Precision M3800             | Notebook    | [1d20598cc5](https://linux-hardware.org/?probe=1d20598cc5) | Mar 17, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Dell          | Latitude 5290               | Notebook    | [2b4d5d7866](https://linux-hardware.org/?probe=2b4d5d7866) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c1cca300c](https://linux-hardware.org/?probe=2c1cca300c) | Mar 13, 2023 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [b12ff30d25](https://linux-hardware.org/?probe=b12ff30d25) | Mar 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [4167bec602](https://linux-hardware.org/?probe=4167bec602) | Mar 09, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [256a8abb58](https://linux-hardware.org/?probe=256a8abb58) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [dbe64de6bd](https://linux-hardware.org/?probe=dbe64de6bd) | Mar 06, 2023 |
| ASUSTek       | A7N8X-E                     | Desktop     | [d0847fb118](https://linux-hardware.org/?probe=d0847fb118) | Mar 06, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f4e7268671](https://linux-hardware.org/?probe=f4e7268671) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [4d2a27cffa](https://linux-hardware.org/?probe=4d2a27cffa) | Mar 05, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| Dell          | Latitude E6230              | Notebook    | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b492e1c092](https://linux-hardware.org/?probe=b492e1c092) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| DEXP          | Aquilon C15                 | Notebook    | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | Desktop     | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Google        | Celes                       | Notebook    | [1952ca99b7](https://linux-hardware.org/?probe=1952ca99b7) | Mar 01, 2023 |
| Google        | Celes                       | Notebook    | [097300a7d3](https://linux-hardware.org/?probe=097300a7d3) | Mar 01, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [6741a47327](https://linux-hardware.org/?probe=6741a47327) | Mar 01, 2023 |
| Acer          | Aspire Z5101                | All in one  | [ec55f791bb](https://linux-hardware.org/?probe=ec55f791bb) | Feb 28, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Getac         | V200-X                      | Notebook    | [f3a5da3eae](https://linux-hardware.org/?probe=f3a5da3eae) | Feb 27, 2023 |
| Acer          | Aspire Z5101                | All in one  | [3dd821cc61](https://linux-hardware.org/?probe=3dd821cc61) | Feb 27, 2023 |
| HP            | Pavilion 17                 | Notebook    | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [26548764cd](https://linux-hardware.org/?probe=26548764cd) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [be9468c864](https://linux-hardware.org/?probe=be9468c864) | Feb 26, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | Notebook    | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4b440b2084](https://linux-hardware.org/?probe=4b440b2084) | Feb 22, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [6f9ef751cd](https://linux-hardware.org/?probe=6f9ef751cd) | Feb 20, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [1c2d1949fd](https://linux-hardware.org/?probe=1c2d1949fd) | Feb 19, 2023 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [edfa765236](https://linux-hardware.org/?probe=edfa765236) | Feb 19, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [d65b4290e6](https://linux-hardware.org/?probe=d65b4290e6) | Feb 19, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [41a31b6bd1](https://linux-hardware.org/?probe=41a31b6bd1) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2420c1fb57](https://linux-hardware.org/?probe=2420c1fb57) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fbe66f89a](https://linux-hardware.org/?probe=9fbe66f89a) | Feb 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | Notebook    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Getac         | V200-X                      | Notebook    | [754a4bd022](https://linux-hardware.org/?probe=754a4bd022) | Feb 17, 2023 |
| Getac         | V200-X                      | Notebook    | [6794c7246f](https://linux-hardware.org/?probe=6794c7246f) | Feb 17, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [39dfda526c](https://linux-hardware.org/?probe=39dfda526c) | Feb 17, 2023 |
| MSI           | MS-7267                     | Desktop     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [72b29b5f80](https://linux-hardware.org/?probe=72b29b5f80) | Feb 16, 2023 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [1fbc4cea88](https://linux-hardware.org/?probe=1fbc4cea88) | Feb 16, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [fbe0863656](https://linux-hardware.org/?probe=fbe0863656) | Feb 15, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| ECS           | G41T-M7                     | Desktop     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | Notebook    | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [360789275e](https://linux-hardware.org/?probe=360789275e) | Feb 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [49d1ea8b3e](https://linux-hardware.org/?probe=49d1ea8b3e) | Feb 11, 2023 |
| Dell          | 0FPP7F A00                  | Desktop     | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Insyde        | CherryTrail                 | Notebook    | [db3d49fa06](https://linux-hardware.org/?probe=db3d49fa06) | Feb 08, 2023 |
| Gigabyte      | H61MA-D2V                   | Desktop     | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Toshiba       | Satellite C55D-A            | Notebook    | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| Acer          | TravelMate P253             | Notebook    | [b2cad8970a](https://linux-hardware.org/?probe=b2cad8970a) | Feb 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| Acer          | AO756                       | Notebook    | [630b2b9b5b](https://linux-hardware.org/?probe=630b2b9b5b) | Feb 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [88be1adb45](https://linux-hardware.org/?probe=88be1adb45) | Feb 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | Notebook    | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 4291H82       | Notebook    | [f9781882f8](https://linux-hardware.org/?probe=f9781882f8) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [850fc5b742](https://linux-hardware.org/?probe=850fc5b742) | Jan 25, 2023 |
| MSI           | MS-7032                     | Desktop     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [d529b5d578](https://linux-hardware.org/?probe=d529b5d578) | Jan 24, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [4eb3c2afb3](https://linux-hardware.org/?probe=4eb3c2afb3) | Jan 23, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [118cda5e06](https://linux-hardware.org/?probe=118cda5e06) | Jan 23, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f1e995c40b](https://linux-hardware.org/?probe=f1e995c40b) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [16708a6471](https://linux-hardware.org/?probe=16708a6471) | Jan 20, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [194f5676bd](https://linux-hardware.org/?probe=194f5676bd) | Jan 20, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [4c7cc6f614](https://linux-hardware.org/?probe=4c7cc6f614) | Jan 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8c57e1afda](https://linux-hardware.org/?probe=8c57e1afda) | Jan 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c0055f8de2](https://linux-hardware.org/?probe=c0055f8de2) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [11964c6701](https://linux-hardware.org/?probe=11964c6701) | Jan 16, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | Desktop     | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [87c00cc849](https://linux-hardware.org/?probe=87c00cc849) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | Desktop     | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| Fujitsu Si... | AMILO Si 2636               | Notebook    | [4a918c5503](https://linux-hardware.org/?probe=4a918c5503) | Jan 11, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [2549187c34](https://linux-hardware.org/?probe=2549187c34) | Jan 10, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [e9050d81df](https://linux-hardware.org/?probe=e9050d81df) | Jan 09, 2023 |
| Acer          | Aspire One 721              | Notebook    | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [da62202546](https://linux-hardware.org/?probe=da62202546) | Jan 08, 2023 |
| ASUSTek       | W5Fe                        | Notebook    | [d56398aefd](https://linux-hardware.org/?probe=d56398aefd) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Google        | Candy                       | Notebook    | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [6ef8fba020](https://linux-hardware.org/?probe=6ef8fba020) | Jan 06, 2023 |
| ASUSTek       | F50SV                       | Notebook    | [ae6f64f5df](https://linux-hardware.org/?probe=ae6f64f5df) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| ASUSTek       | F8SG                        | Notebook    | [d70636ce7e](https://linux-hardware.org/?probe=d70636ce7e) | Jan 05, 2023 |
| Dell          | Dimension 4500S             | Desktop     | [5b907b07e4](https://linux-hardware.org/?probe=5b907b07e4) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [4036321fcf](https://linux-hardware.org/?probe=4036321fcf) | Jan 05, 2023 |
| Google        | Celes                       | Notebook    | [70525bfcb2](https://linux-hardware.org/?probe=70525bfcb2) | Jan 05, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [bd9e90dca3](https://linux-hardware.org/?probe=bd9e90dca3) | Jan 04, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [73a67d66af](https://linux-hardware.org/?probe=73a67d66af) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| Acer          | Aspire SW3-013              | Notebook    | [44016de6db](https://linux-hardware.org/?probe=44016de6db) | Jan 01, 2023 |
| HP            | 21B4 A01                    | Desktop     | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| Google        | Candy                       | Notebook    | [86bb9a73fc](https://linux-hardware.org/?probe=86bb9a73fc) | Dec 31, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [23985812a9](https://linux-hardware.org/?probe=23985812a9) | Dec 30, 2022 |
| Dell          | 05KX61 A00                  | Server      | [9f365307f3](https://linux-hardware.org/?probe=9f365307f3) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Google        | Edgar                       | Notebook    | [738a0d9324](https://linux-hardware.org/?probe=738a0d9324) | Dec 30, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [41a9d09ec8](https://linux-hardware.org/?probe=41a9d09ec8) | Dec 29, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [a9c1fc9fbd](https://linux-hardware.org/?probe=a9c1fc9fbd) | Dec 28, 2022 |
| Apple         | Mac-F2268CC8                | All in one  | [fd1cdfc132](https://linux-hardware.org/?probe=fd1cdfc132) | Dec 28, 2022 |
| Acer          | Aspire SW3-013              | Notebook    | [04286c0e93](https://linux-hardware.org/?probe=04286c0e93) | Dec 27, 2022 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [252a51f201](https://linux-hardware.org/?probe=252a51f201) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [cd547b04a1](https://linux-hardware.org/?probe=cd547b04a1) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1505706e04](https://linux-hardware.org/?probe=1505706e04) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | Desktop     | [1c996d8122](https://linux-hardware.org/?probe=1c996d8122) | Dec 25, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [f33ebabb99](https://linux-hardware.org/?probe=f33ebabb99) | Dec 24, 2022 |
| HP            | Stream 8 Tablet             | Tablet      | [752a0b9007](https://linux-hardware.org/?probe=752a0b9007) | Dec 23, 2022 |
| Positivo      | C14CR21                     | Notebook    | [be49c26bb4](https://linux-hardware.org/?probe=be49c26bb4) | Dec 21, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | Notebook    | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [e171eea812](https://linux-hardware.org/?probe=e171eea812) | Dec 21, 2022 |
| Google        | Coral                       | Notebook    | [8e2407d4b2](https://linux-hardware.org/?probe=8e2407d4b2) | Dec 19, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | Notebook    | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | 2000                        | Notebook    | [bcbeb17a60](https://linux-hardware.org/?probe=bcbeb17a60) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [9ddb08e4ae](https://linux-hardware.org/?probe=9ddb08e4ae) | Dec 13, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [becb2e6bbc](https://linux-hardware.org/?probe=becb2e6bbc) | Dec 12, 2022 |
| SGIN          | laptop                      | Notebook    | [8f650d00dd](https://linux-hardware.org/?probe=8f650d00dd) | Dec 11, 2022 |
| ASUSTek       | K50C                        | Notebook    | [6cf2037e0f](https://linux-hardware.org/?probe=6cf2037e0f) | Dec 11, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [492071e526](https://linux-hardware.org/?probe=492071e526) | Dec 09, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [bcf1460e47](https://linux-hardware.org/?probe=bcf1460e47) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [bdbc74a754](https://linux-hardware.org/?probe=bdbc74a754) | Dec 07, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [193053a6ef](https://linux-hardware.org/?probe=193053a6ef) | Dec 05, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| ASUSTek       | ET1610PT                    | Desktop     | [d8b1840336](https://linux-hardware.org/?probe=d8b1840336) | Dec 03, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [179ce76921](https://linux-hardware.org/?probe=179ce76921) | Dec 02, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [f91b4cdb61](https://linux-hardware.org/?probe=f91b4cdb61) | Nov 29, 2022 |
| HP            | 620                         | Notebook    | [5baeeace34](https://linux-hardware.org/?probe=5baeeace34) | Nov 28, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [03a1a706d1](https://linux-hardware.org/?probe=03a1a706d1) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [63487a2957](https://linux-hardware.org/?probe=63487a2957) | Nov 28, 2022 |
| ASUSTek       | K70IO                       | Notebook    | [4eabf9a0d4](https://linux-hardware.org/?probe=4eabf9a0d4) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [0b632b7ae8](https://linux-hardware.org/?probe=0b632b7ae8) | Nov 27, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [ba7b5c7748](https://linux-hardware.org/?probe=ba7b5c7748) | Nov 26, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [2d8e324570](https://linux-hardware.org/?probe=2d8e324570) | Nov 26, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [f8e0414c84](https://linux-hardware.org/?probe=f8e0414c84) | Nov 26, 2022 |
| Intel         | BTC-T37                     | Desktop     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [f40545f0d5](https://linux-hardware.org/?probe=f40545f0d5) | Nov 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9b9cd79752](https://linux-hardware.org/?probe=9b9cd79752) | Nov 23, 2022 |
| HP            | 620                         | Notebook    | [a09882989c](https://linux-hardware.org/?probe=a09882989c) | Nov 23, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [e1c126c1f2](https://linux-hardware.org/?probe=e1c126c1f2) | Nov 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [242d685287](https://linux-hardware.org/?probe=242d685287) | Nov 22, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [a9d392c0c3](https://linux-hardware.org/?probe=a9d392c0c3) | Nov 22, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [cc9c76c85c](https://linux-hardware.org/?probe=cc9c76c85c) | Nov 21, 2022 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2574454ebe](https://linux-hardware.org/?probe=2574454ebe) | Nov 21, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | Desktop     | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [63e70c5e46](https://linux-hardware.org/?probe=63e70c5e46) | Nov 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [3b7077c5ab](https://linux-hardware.org/?probe=3b7077c5ab) | Nov 19, 2022 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [9eb6a535ac](https://linux-hardware.org/?probe=9eb6a535ac) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [33ced86304](https://linux-hardware.org/?probe=33ced86304) | Nov 19, 2022 |
| HP            | 3048h                       | Desktop     | [e5fdb1f67a](https://linux-hardware.org/?probe=e5fdb1f67a) | Nov 19, 2022 |
| ASUSTek       | K55A                        | Notebook    | [d09b309d4d](https://linux-hardware.org/?probe=d09b309d4d) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [4825e06bd4](https://linux-hardware.org/?probe=4825e06bd4) | Nov 19, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [57bcd4363a](https://linux-hardware.org/?probe=57bcd4363a) | Nov 19, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [3d49b98878](https://linux-hardware.org/?probe=3d49b98878) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [f528238460](https://linux-hardware.org/?probe=f528238460) | Nov 16, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [97ccc55f03](https://linux-hardware.org/?probe=97ccc55f03) | Nov 16, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ed6f93342d](https://linux-hardware.org/?probe=ed6f93342d) | Nov 15, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [a7f77757c7](https://linux-hardware.org/?probe=a7f77757c7) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [759ee850cc](https://linux-hardware.org/?probe=759ee850cc) | Nov 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [f506c5c2fa](https://linux-hardware.org/?probe=f506c5c2fa) | Nov 13, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8a149b06a1](https://linux-hardware.org/?probe=8a149b06a1) | Nov 12, 2022 |
| Acer          | AOD255E                     | Notebook    | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | Notebook    | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [70940de14e](https://linux-hardware.org/?probe=70940de14e) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [19205fc20b](https://linux-hardware.org/?probe=19205fc20b) | Nov 04, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [29617200dd](https://linux-hardware.org/?probe=29617200dd) | Nov 03, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [24f27140f8](https://linux-hardware.org/?probe=24f27140f8) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a922f68180](https://linux-hardware.org/?probe=a922f68180) | Nov 03, 2022 |
| Lenovo        | NOK                         | Desktop     | [8c9f8ff505](https://linux-hardware.org/?probe=8c9f8ff505) | Nov 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [027cfb43c4](https://linux-hardware.org/?probe=027cfb43c4) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [113930496e](https://linux-hardware.org/?probe=113930496e) | Oct 31, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2934bab108](https://linux-hardware.org/?probe=2934bab108) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [4ba79bc73e](https://linux-hardware.org/?probe=4ba79bc73e) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Intel         | D33217GKE G76540-203        | Desktop     | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4b4c00b0a9](https://linux-hardware.org/?probe=4b4c00b0a9) | Oct 28, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [9c7127a256](https://linux-hardware.org/?probe=9c7127a256) | Oct 27, 2022 |
| Acer          | Extensa 2509                | Notebook    | [a27b3d38a9](https://linux-hardware.org/?probe=a27b3d38a9) | Oct 27, 2022 |
| Google        | Apel                        | Notebook    | [f3bf9850dd](https://linux-hardware.org/?probe=f3bf9850dd) | Oct 26, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| Acer          | Aspire one                  | Notebook    | [fced25613a](https://linux-hardware.org/?probe=fced25613a) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| HP            | 431 Notebook                | Notebook    | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [784360100d](https://linux-hardware.org/?probe=784360100d) | Oct 14, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [15ba599a80](https://linux-hardware.org/?probe=15ba599a80) | Oct 14, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | ThinkPad SL510 2847CXG      | Notebook    | [5680d8a827](https://linux-hardware.org/?probe=5680d8a827) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| AOpen         | D1007 0BBA                  | Desktop     | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | Desktop     | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [b4a8655f31](https://linux-hardware.org/?probe=b4a8655f31) | Oct 08, 2022 |
| Toshiba       | Satellite C655D             | Notebook    | [80ec8503c0](https://linux-hardware.org/?probe=80ec8503c0) | Oct 05, 2022 |
| Lenovo        | ThinkPad T410 2537CS0       | Notebook    | [c6a45619c4](https://linux-hardware.org/?probe=c6a45619c4) | Oct 03, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [1ad22cf7a8](https://linux-hardware.org/?probe=1ad22cf7a8) | Sep 28, 2022 |
| Dell          | 0PU052                      | Desktop     | [2890a8407e](https://linux-hardware.org/?probe=2890a8407e) | Sep 28, 2022 |
| Lenovo        | ThinkPad E550 20DF00CUFR    | Notebook    | [7b5e707097](https://linux-hardware.org/?probe=7b5e707097) | Sep 27, 2022 |
| Dell          | 0R849J A00                  | Desktop     | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [4005a32539](https://linux-hardware.org/?probe=4005a32539) | Sep 26, 2022 |
| ASUSTek       | UX360CAK                    | Convertible | [015df11bc4](https://linux-hardware.org/?probe=015df11bc4) | Sep 25, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [cf8128637b](https://linux-hardware.org/?probe=cf8128637b) | Sep 24, 2022 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e63b24acc3](https://linux-hardware.org/?probe=e63b24acc3) | Sep 24, 2022 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3468d8c911](https://linux-hardware.org/?probe=3468d8c911) | Sep 24, 2022 |
| Dell          | 0PU052                      | Desktop     | [6ca93366df](https://linux-hardware.org/?probe=6ca93366df) | Sep 23, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1dbeac403e](https://linux-hardware.org/?probe=1dbeac403e) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| ASUSTek       | X451CA                      | Notebook    | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c45724d6d3](https://linux-hardware.org/?probe=c45724d6d3) | Sep 20, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [2f9ab4273a](https://linux-hardware.org/?probe=2f9ab4273a) | Sep 20, 2022 |
| Gateway       | NE46R                       | Notebook    | [61ee26263b](https://linux-hardware.org/?probe=61ee26263b) | Sep 20, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [29241bb609](https://linux-hardware.org/?probe=29241bb609) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [93cb353340](https://linux-hardware.org/?probe=93cb353340) | Sep 14, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [763b0fced4](https://linux-hardware.org/?probe=763b0fced4) | Sep 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [8b85e41d17](https://linux-hardware.org/?probe=8b85e41d17) | Sep 14, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Star Labs     | Lite                        | Notebook    | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| Dell          | XPS L322X                   | Notebook    | [bd4b0713a8](https://linux-hardware.org/?probe=bd4b0713a8) | Sep 04, 2022 |
| Acer          | AOA150                      | Notebook    | [3146707963](https://linux-hardware.org/?probe=3146707963) | Sep 02, 2022 |
| Dell          | 0J584C A00                  | Desktop     | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [3c18cd9208](https://linux-hardware.org/?probe=3c18cd9208) | Aug 25, 2022 |
| Standard      | AHV                         | Notebook    | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [7035af5c32](https://linux-hardware.org/?probe=7035af5c32) | Aug 23, 2022 |
| ASRock        | A520M-HVS                   | Desktop     | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [df6dff3fa3](https://linux-hardware.org/?probe=df6dff3fa3) | Aug 19, 2022 |
| Prestigio     | PSB141C01BFH                | Notebook    | [37e5052027](https://linux-hardware.org/?probe=37e5052027) | Aug 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB Touch ... | Notebook    | [0d774697cc](https://linux-hardware.org/?probe=0d774697cc) | Aug 11, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| Intel         | W7650                       | Notebook    | [1c8a9fd64b](https://linux-hardware.org/?probe=1c8a9fd64b) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| OEM           | Unknown                     | Notebook    | [d95f8f1502](https://linux-hardware.org/?probe=d95f8f1502) | Aug 09, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [11beb61f79](https://linux-hardware.org/?probe=11beb61f79) | Aug 09, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [98c601bb55](https://linux-hardware.org/?probe=98c601bb55) | Aug 08, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [01e4feaac6](https://linux-hardware.org/?probe=01e4feaac6) | Aug 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [7a3c91b14a](https://linux-hardware.org/?probe=7a3c91b14a) | Aug 07, 2022 |
| HP            | 8768 A                      | Desktop     | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [c857595b97](https://linux-hardware.org/?probe=c857595b97) | Aug 05, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | Desktop     | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | Desktop     | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [49ba856687](https://linux-hardware.org/?probe=49ba856687) | Aug 03, 2022 |
| Dell          | Precision 3510              | Notebook    | [2d74356174](https://linux-hardware.org/?probe=2d74356174) | Aug 03, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [84efbc858e](https://linux-hardware.org/?probe=84efbc858e) | Aug 02, 2022 |
| Dell          | Precision 3510              | Notebook    | [d2e79b01bb](https://linux-hardware.org/?probe=d2e79b01bb) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [6a4bc65f84](https://linux-hardware.org/?probe=6a4bc65f84) | Jul 31, 2022 |
| Google        | Celes                       | Notebook    | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| Dell          | XPS M1330                   | Notebook    | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Toshiba       | NB250                       | Notebook    | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | Presario CQ56               | Notebook    | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | Desktop     | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0X8582                      | Desktop     | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | Desktop     | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | 900                         | Notebook    | [ae42d40b7a](https://linux-hardware.org/?probe=ae42d40b7a) | Jul 25, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Sony          | VPCEB15FM                   | Notebook    | [340ef685ef](https://linux-hardware.org/?probe=340ef685ef) | Jul 24, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| Dell          | 0X8582                      | Desktop     | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | Desktop     | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| HP            | 245 G2                      | Notebook    | [03a8791b0c](https://linux-hardware.org/?probe=03a8791b0c) | Jul 18, 2022 |
| Samsung       | N130                        | Notebook    | [4874e0173d](https://linux-hardware.org/?probe=4874e0173d) | Jul 17, 2022 |
| HP            | 245 G2                      | Notebook    | [f37ddc5aed](https://linux-hardware.org/?probe=f37ddc5aed) | Jul 17, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [27a46d46dd](https://linux-hardware.org/?probe=27a46d46dd) | Jul 16, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [21b83125d8](https://linux-hardware.org/?probe=21b83125d8) | Jul 14, 2022 |
| Standard      | AHV                         | Notebook    | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [08b1b304ae](https://linux-hardware.org/?probe=08b1b304ae) | Jul 11, 2022 |
| Foxconn       | 2ACA                        | Desktop     | [92681ef1e5](https://linux-hardware.org/?probe=92681ef1e5) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| HP            | 1495                        | Desktop     | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [dd80f74e85](https://linux-hardware.org/?probe=dd80f74e85) | Jul 05, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [69e4341e99](https://linux-hardware.org/?probe=69e4341e99) | Jul 05, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| HP            | 1495                        | Desktop     | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [92c11e77c4](https://linux-hardware.org/?probe=92c11e77c4) | Jul 03, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [de35c60b5f](https://linux-hardware.org/?probe=de35c60b5f) | Jul 01, 2022 |
| MSI           | VR630                       | Notebook    | [097cd732b3](https://linux-hardware.org/?probe=097cd732b3) | Jun 27, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a27f696a28](https://linux-hardware.org/?probe=a27f696a28) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [f6f825d83a](https://linux-hardware.org/?probe=f6f825d83a) | Jun 22, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| HP            | Notebook                    | Notebook    | [76d300309e](https://linux-hardware.org/?probe=76d300309e) | Jun 21, 2022 |
| Gateway       | Sonic-C                     | Notebook    | [6bec9c80ea](https://linux-hardware.org/?probe=6bec9c80ea) | Jun 21, 2022 |
| Gigabyte      | GA-MA69G-S3H                | Desktop     | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| Dell          | Latitude XT                 | Notebook    | [c07eac8a84](https://linux-hardware.org/?probe=c07eac8a84) | Jun 17, 2022 |
| Dell          | Studio 1537                 | Notebook    | [12a651ebd2](https://linux-hardware.org/?probe=12a651ebd2) | Jun 16, 2022 |
| ASUSTek       | M4N78-AM                    | Desktop     | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [14ed78a258](https://linux-hardware.org/?probe=14ed78a258) | Jun 11, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| HP            | Notebook                    | Notebook    | [5c18b71eb1](https://linux-hardware.org/?probe=5c18b71eb1) | Jun 10, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [1a41b08f4f](https://linux-hardware.org/?probe=1a41b08f4f) | Jun 10, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3c1a5025f1](https://linux-hardware.org/?probe=3c1a5025f1) | Jun 09, 2022 |
| Sony          | VGN-SZ71WN_C                | Notebook    | [aece18b520](https://linux-hardware.org/?probe=aece18b520) | Jun 06, 2022 |
| MSI           | MS-AA1511                   | All in one  | [80c9ccb7c7](https://linux-hardware.org/?probe=80c9ccb7c7) | Jun 06, 2022 |
| ASUSTek       | PRIME X370-A                | Desktop     | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| Intel         | W7650                       | Notebook    | [fd4abd788b](https://linux-hardware.org/?probe=fd4abd788b) | Jun 06, 2022 |
| ASUSTek       | 1000H                       | Notebook    | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d191629954](https://linux-hardware.org/?probe=d191629954) | Jun 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [816c29b1df](https://linux-hardware.org/?probe=816c29b1df) | Jun 04, 2022 |
| HP            | G62                         | Notebook    | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| HP            | 3397                        | Desktop     | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7c389588bb](https://linux-hardware.org/?probe=7c389588bb) | Jun 02, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [8fe291470d](https://linux-hardware.org/?probe=8fe291470d) | Jun 02, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a1c25fad70](https://linux-hardware.org/?probe=a1c25fad70) | Jun 01, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63ccee44b1](https://linux-hardware.org/?probe=63ccee44b1) | May 28, 2022 |
| HP            | Berknip                     | Notebook    | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [c77f0f6328](https://linux-hardware.org/?probe=c77f0f6328) | May 27, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3972cb6508](https://linux-hardware.org/?probe=3972cb6508) | May 25, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [37af5b0ba4](https://linux-hardware.org/?probe=37af5b0ba4) | May 24, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [0d13155508](https://linux-hardware.org/?probe=0d13155508) | May 23, 2022 |
| Dell          | System Inspiron 17 7000 ... | Notebook    | [5f646f4e8c](https://linux-hardware.org/?probe=5f646f4e8c) | May 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | Desktop     | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| ASUSTek       | X402CA                      | Notebook    | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [f52f5b7be2](https://linux-hardware.org/?probe=f52f5b7be2) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [6528155c00](https://linux-hardware.org/?probe=6528155c00) | May 19, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [53219da3f5](https://linux-hardware.org/?probe=53219da3f5) | May 19, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| Lenovo        | NOK                         | Desktop     | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [7807aa5ed4](https://linux-hardware.org/?probe=7807aa5ed4) | May 16, 2022 |
| Google        | Terra                       | Notebook    | [35088c1c05](https://linux-hardware.org/?probe=35088c1c05) | May 16, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Dell          | 0CRH6C A00                  | Desktop     | [fe2648c1f7](https://linux-hardware.org/?probe=fe2648c1f7) | May 14, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [68ee4b094a](https://linux-hardware.org/?probe=68ee4b094a) | May 13, 2022 |
| Pegatron      | VIOLET6                     | Desktop     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [5774e3f483](https://linux-hardware.org/?probe=5774e3f483) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [f3bd3e55aa](https://linux-hardware.org/?probe=f3bd3e55aa) | May 12, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [3a09364bb2](https://linux-hardware.org/?probe=3a09364bb2) | May 12, 2022 |
| Toshiba       | Satellite P20               | Notebook    | [923779da79](https://linux-hardware.org/?probe=923779da79) | May 11, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Positivo      | AT300b                      | Notebook    | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| ASUSTek       | Rampage III GENE            | Desktop     | [798c1f07f6](https://linux-hardware.org/?probe=798c1f07f6) | May 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [f151955e44](https://linux-hardware.org/?probe=f151955e44) | May 10, 2022 |
| Google        | Relm                        | Notebook    | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| ASUSTek       | 900                         | Notebook    | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Intel         | W7650                       | Notebook    | [bd5d159229](https://linux-hardware.org/?probe=bd5d159229) | May 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | Notebook    | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [fd19fe90e5](https://linux-hardware.org/?probe=fd19fe90e5) | May 05, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [4682643304](https://linux-hardware.org/?probe=4682643304) | May 05, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [dc913baa2b](https://linux-hardware.org/?probe=dc913baa2b) | May 04, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| Samsung       | RV415/RV515                 | Notebook    | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [dbad5c417d](https://linux-hardware.org/?probe=dbad5c417d) | May 04, 2022 |
| ASUSTek       | 900                         | Notebook    | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Intel         | DQ57TM AAE70931-403         | Desktop     | [dd1df3c77d](https://linux-hardware.org/?probe=dd1df3c77d) | May 02, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| Google        | Bobba360                    | Notebook    | [e90fbcc91d](https://linux-hardware.org/?probe=e90fbcc91d) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| YASHI         | MYBOOK 360                  | Notebook    | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | Pavilion g4                 | Notebook    | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Lubuntu 20.04    | 465       | 29.26%  |
| Lubuntu 22.04    | 452       | 28.45%  |
| Lubuntu 18.04    | 221       | 13.91%  |
| Lubuntu 21.10    | 80        | 5.03%   |
| Lubuntu 19.10    | 62        | 3.9%    |
| Lubuntu 21.04    | 53        | 3.34%   |
| Lubuntu 23.10    | 48        | 3.02%   |
| Lubuntu 20.10    | 48        | 3.02%   |
| Lubuntu 22.10    | 44        | 2.77%   |
| Lubuntu 23.04    | 38        | 2.39%   |
| Lubuntu 16.04    | 31        | 1.95%   |
| Lubuntu 19.04    | 14        | 0.88%   |
| Lubuntu 18.10    | 13        | 0.82%   |
| Lubuntu 24.04    | 9         | 0.57%   |
| Lubuntu          | 3         | 0.19%   |
| Lubuntu 16.10    | 2         | 0.13%   |
| Lubuntu 20.04.1  | 1         | 0.06%   |
| Lubuntu 18.04.05 | 1         | 0.06%   |
| Lubuntu 17.10    | 1         | 0.06%   |
| Lubuntu 17.04    | 1         | 0.06%   |
| Lubuntu 13.04    | 1         | 0.06%   |
| Lubuntu 12.04    | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Lubuntu | 1539      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 39        | 2.24%   |
| 5.15.0-43-generic | 36        | 2.07%   |
| 5.4.0-52-generic  | 24        | 1.38%   |
| 5.15.0-56-generic | 21        | 1.21%   |
| 6.5.0-14-generic  | 19        | 1.09%   |
| 5.13.0-19-generic | 19        | 1.09%   |
| 5.15.0-25-generic | 17        | 0.98%   |
| 5.19.0-32-generic | 16        | 0.92%   |
| 5.15.0-60-generic | 16        | 0.92%   |
| 5.13.0-40-generic | 16        | 0.92%   |
| 5.13.0-28-generic | 16        | 0.92%   |
| 5.15.0-46-generic | 15        | 0.86%   |
| 5.4.0-48-generic  | 14        | 0.81%   |
| 5.4.0-47-generic  | 14        | 0.81%   |
| 5.3.0-46-generic  | 14        | 0.81%   |
| 5.15.0-41-generic | 14        | 0.81%   |
| 6.2.0-26-generic  | 13        | 0.75%   |
| 5.15.0-47-generic | 13        | 0.75%   |
| 5.13.0-30-generic | 13        | 0.75%   |
| 5.11.0-27-generic | 13        | 0.75%   |
| 5.11.0-16-generic | 13        | 0.75%   |
| 6.2.0-39-generic  | 12        | 0.69%   |
| 5.4.0-54-generic  | 12        | 0.69%   |
| 5.4.0-26-generic  | 12        | 0.69%   |
| 5.19.0-41-generic | 12        | 0.69%   |
| 5.19.0-35-generic | 12        | 0.69%   |
| 5.15.0-58-generic | 12        | 0.69%   |
| 6.5.0-15-generic  | 11        | 0.63%   |
| 6.2.0-34-generic  | 11        | 0.63%   |
| 5.8.0-50-generic  | 11        | 0.63%   |
| 5.4.0-73-generic  | 11        | 0.63%   |
| 5.4.0-40-generic  | 11        | 0.63%   |
| 5.15.0-91-generic | 11        | 0.63%   |
| 5.15.0-53-generic | 11        | 0.63%   |
| 5.15.0-52-generic | 11        | 0.63%   |
| 5.15.0-30-generic | 11        | 0.63%   |
| 5.13.0-35-generic | 11        | 0.63%   |
| 6.5.0-9-generic   | 10        | 0.58%   |
| 5.4.0-29-generic  | 10        | 0.58%   |
| 5.3.0-18-generic  | 10        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 334       | 20.69%  |
| 5.15.0  | 302       | 18.71%  |
| 4.15.0  | 147       | 9.11%   |
| 5.13.0  | 119       | 7.37%   |
| 5.19.0  | 112       | 6.94%   |
| 6.5.0   | 106       | 6.57%   |
| 5.11.0  | 102       | 6.32%   |
| 5.8.0   | 99        | 6.13%   |
| 6.2.0   | 95        | 5.89%   |
| 5.3.0   | 86        | 5.33%   |
| 5.0.0   | 22        | 1.36%   |
| 4.18.0  | 13        | 0.81%   |
| 6.8.0   | 8         | 0.5%    |
| 4.4.0   | 8         | 0.5%    |
| 6.1.0   | 3         | 0.19%   |
| 6.6.0   | 2         | 0.12%   |
| 5.6.0   | 2         | 0.12%   |
| 5.4.30  | 2         | 0.12%   |
| 5.14.0  | 2         | 0.12%   |
| 4.9.253 | 2         | 0.12%   |
| 4.8.0   | 2         | 0.12%   |
| 4.13.0  | 2         | 0.12%   |
| 4.10.0  | 2         | 0.12%   |
| 6.7.8   | 1         | 0.06%   |
| 6.7.6   | 1         | 0.06%   |
| 6.7.0   | 1         | 0.06%   |
| 6.6.6   | 1         | 0.06%   |
| 6.5.1   | 1         | 0.06%   |
| 6.4.12  | 1         | 0.06%   |
| 6.3.3   | 1         | 0.06%   |
| 6.2.8   | 1         | 0.06%   |
| 6.2.6   | 1         | 0.06%   |
| 6.1.6   | 1         | 0.06%   |
| 6.1.46  | 1         | 0.06%   |
| 6.1.3   | 1         | 0.06%   |
| 6.1.26  | 1         | 0.06%   |
| 6.1.12  | 1         | 0.06%   |
| 6.0.9   | 1         | 0.06%   |
| 6.0.8   | 1         | 0.06%   |
| 6.0.14  | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 336       | 20.82%  |
| 5.15    | 303       | 18.77%  |
| 4.15    | 148       | 9.17%   |
| 5.13    | 119       | 7.37%   |
| 5.19    | 114       | 7.06%   |
| 6.5     | 107       | 6.63%   |
| 5.11    | 102       | 6.32%   |
| 5.8     | 99        | 6.13%   |
| 6.2     | 97        | 6.01%   |
| 5.3     | 87        | 5.39%   |
| 5.0     | 22        | 1.36%   |
| 4.18    | 13        | 0.81%   |
| 6.8     | 8         | 0.5%    |
| 6.1     | 8         | 0.5%    |
| 4.4     | 8         | 0.5%    |
| 6.0     | 6         | 0.37%   |
| 6.7     | 3         | 0.19%   |
| 6.6     | 3         | 0.19%   |
| 5.6     | 3         | 0.19%   |
| 4.9     | 3         | 0.19%   |
| 4.13    | 3         | 0.19%   |
| 5.7     | 2         | 0.12%   |
| 5.16    | 2         | 0.12%   |
| 5.14    | 2         | 0.12%   |
| 5.10    | 2         | 0.12%   |
| 4.8     | 2         | 0.12%   |
| 4.10    | 2         | 0.12%   |
| 6.4     | 1         | 0.06%   |
| 6.3     | 1         | 0.06%   |
| 5.9     | 1         | 0.06%   |
| 5.5     | 1         | 0.06%   |
| 5.18    | 1         | 0.06%   |
| 5.12    | 1         | 0.06%   |
| 4.20    | 1         | 0.06%   |
| 4.14    | 1         | 0.06%   |
| 3.13    | 1         | 0.06%   |
| 3.1     | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1393      | 90.51%  |
| i686    | 132       | 8.58%   |
| aarch64 | 11        | 0.71%   |
| armv7l  | 2         | 0.13%   |
| ppc64   | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| LXQt            | 1223      | 79.06%  |
| LXDE            | 250       | 16.16%  |
| Unknown         | 22        | 1.42%   |
| GNOME           | 19        | 1.23%   |
| Openbox         | 7         | 0.45%   |
| X-Cinnamon      | 5         | 0.32%   |
| KDE5            | 4         | 0.26%   |
| Lubuntu         | 3         | 0.19%   |
| Cinnamon        | 3         | 0.19%   |
| XFCE            | 2         | 0.13%   |
| i3              | 2         | 0.13%   |
| GNOME Flashback | 2         | 0.13%   |
| Budgie          | 2         | 0.13%   |
| ratflow         | 1         | 0.06%   |
| MATE            | 1         | 0.06%   |
| KDE             | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1487      | 96.12%  |
| Tty         | 47        | 3.04%   |
| Wayland     | 10        | 0.65%   |
| Unknown     | 2         | 0.13%   |
| Unspecified | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 866       | 55.41%  |
| Unknown | 413       | 26.42%  |
| LightDM | 152       | 9.72%   |
| TDM     | 68        | 4.35%   |
| GDM     | 38        | 2.43%   |
| GDM3    | 19        | 1.22%   |
| XDM     | 3         | 0.19%   |
| LXDM    | 3         | 0.19%   |
| SLiM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 450       | 29.07%  |
| fr_FR   | 150       | 9.69%   |
| pt_BR   | 102       | 6.59%   |
| it_IT   | 96        | 6.2%    |
| en_GB   | 91        | 5.88%   |
| de_DE   | 90        | 5.81%   |
| C       | 82        | 5.3%    |
| ru_RU   | 50        | 3.23%   |
| pl_PL   | 35        | 2.26%   |
| es_ES   | 35        | 2.26%   |
| en_CA   | 32        | 2.07%   |
| Unknown | 31        | 2%      |
| en_AU   | 27        | 1.74%   |
| es_AR   | 24        | 1.55%   |
| es_MX   | 17        | 1.1%    |
| tr_TR   | 15        | 0.97%   |
| cs_CZ   | 15        | 0.97%   |
| hu_HU   | 13        | 0.84%   |
| en_IN   | 12        | 0.78%   |
| en_AG   | 11        | 0.71%   |
| nl_NL   | 10        | 0.65%   |
| ja_JP   | 10        | 0.65%   |
| fi_FI   | 9         | 0.58%   |
| es_CR   | 8         | 0.52%   |
| es_CL   | 8         | 0.52%   |
| es_CO   | 7         | 0.45%   |
| nl_BE   | 6         | 0.39%   |
| el_GR   | 6         | 0.39%   |
| zh_TW   | 5         | 0.32%   |
| fr_BE   | 5         | 0.32%   |
| es_PE   | 5         | 0.32%   |
| en_IE   | 5         | 0.32%   |
| fr_CA   | 4         | 0.26%   |
| es_VE   | 4         | 0.26%   |
| es_UY   | 4         | 0.26%   |
| es_EC   | 4         | 0.26%   |
| en_ZA   | 4         | 0.26%   |
| en_SG   | 4         | 0.26%   |
| en_PH   | 4         | 0.26%   |
| en_NZ   | 4         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 986       | 63.41%  |
| EFI  | 569       | 36.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1338      | 85.93%  |
| Tmpfs   | 100       | 6.42%   |
| Overlay | 77        | 4.95%   |
| Btrfs   | 17        | 1.09%   |
| Xfs     | 7         | 0.45%   |
| Aufs    | 5         | 0.32%   |
| Unknown | 5         | 0.32%   |
| Ext3    | 3         | 0.19%   |
| Ext2    | 2         | 0.13%   |
| Zfs     | 1         | 0.06%   |
| XXX4    | 1         | 0.06%   |
| F2fs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 596       | 38.28%  |
| Unknown | 548       | 35.2%   |
| MBR     | 413       | 26.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1371      | 88.11%  |
| Yes       | 185       | 11.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1126      | 72.65%  |
| Yes       | 424       | 27.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 254       | 16.5%   |
| ASUSTek Computer        | 193       | 12.54%  |
| Lenovo                  | 156       | 10.14%  |
| Dell                    | 152       | 9.88%   |
| Acer                    | 112       | 7.28%   |
| MSI                     | 59        | 3.83%   |
| Gigabyte Technology     | 55        | 3.57%   |
| Toshiba                 | 50        | 3.25%   |
| ASRock                  | 46        | 2.99%   |
| Apple                   | 34        | 2.21%   |
| Intel                   | 32        | 2.08%   |
| Samsung Electronics     | 31        | 2.01%   |
| Google                  | 31        | 2.01%   |
| Unknown                 | 31        | 2.01%   |
| Sony                    | 24        | 1.56%   |
| Positivo                | 19        | 1.23%   |
| Fujitsu                 | 18        | 1.17%   |
| Packard Bell            | 12        | 0.78%   |
| AMI                     | 12        | 0.78%   |
| Pegatron                | 11        | 0.71%   |
| Fujitsu Siemens         | 11        | 0.71%   |
| Mediacom                | 9         | 0.58%   |
| Foxconn                 | 9         | 0.58%   |
| Raspberry Pi Foundation | 7         | 0.45%   |
| Supermicro              | 6         | 0.39%   |
| Notebook                | 6         | 0.39%   |
| Biostar                 | 6         | 0.39%   |
| AAEON                   | 6         | 0.39%   |
| Microsoft               | 5         | 0.32%   |
| IBM                     | 5         | 0.32%   |
| Gateway                 | 5         | 0.32%   |
| eMachines               | 5         | 0.32%   |
| Chuwi                   | 5         | 0.32%   |
| HUAWEI                  | 4         | 0.26%   |
| Alienware               | 4         | 0.26%   |
| TrekStor                | 3         | 0.19%   |
| Thomson                 | 3         | 0.19%   |
| Panasonic               | 3         | 0.19%   |
| OEM                     | 3         | 0.19%   |
| Nvidia                  | 3         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 42        | 2.73%   |
| HP Notebook                           | 13        | 0.84%   |
| HP Pavilion dv6                       | 6         | 0.39%   |
| HP Pavilion 15                        | 6         | 0.39%   |
| Apple MacBookPro8,1                   | 6         | 0.39%   |
| AAEON MF-001                          | 6         | 0.39%   |
| HP Pavilion g6                        | 5         | 0.32%   |
| Apple iMac7,1                         | 5         | 0.32%   |
| Supermicro X8DTT-IBX                  | 4         | 0.26%   |
| MSI MS-7C37                           | 4         | 0.26%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 4         | 0.26%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS   | 4         | 0.26%   |
| HP t620 Quad Core TC                  | 4         | 0.26%   |
| Dell OptiPlex 790                     | 4         | 0.26%   |
| Dell OptiPlex 7010                    | 4         | 0.26%   |
| Dell Latitude D630                    | 4         | 0.26%   |
| Dell Inspiron N5010                   | 4         | 0.26%   |
| Nvidia Tegra                          | 3         | 0.19%   |
| MSI MS-7309                           | 3         | 0.19%   |
| Mediacom WinPad 11,6 FullHD- WPU11    | 3         | 0.19%   |
| Lenovo IdeaPad 320-15AST 80XV         | 3         | 0.19%   |
| Lenovo IdeaPad 100-15IBD 80QQ         | 3         | 0.19%   |
| Lenovo G50-30 80G0                    | 3         | 0.19%   |
| HP ProBook 440 G7                     | 3         | 0.19%   |
| HP Pavilion g7                        | 3         | 0.19%   |
| HP Laptop 15-da0xxx                   | 3         | 0.19%   |
| HP 2000                               | 3         | 0.19%   |
| Google Candy                          | 3         | 0.19%   |
| Dell OptiPlex 755                     | 3         | 0.19%   |
| Dell Latitude E6410                   | 3         | 0.19%   |
| Dell Inspiron 15-3567                 | 3         | 0.19%   |
| ASUS V-P8H67E                         | 3         | 0.19%   |
| ASUS All Series                       | 3         | 0.19%   |
| ASUS 1000H                            | 3         | 0.19%   |
| ASRock FM2A85X Extreme6               | 3         | 0.19%   |
| Apple MacBook4,1                      | 3         | 0.19%   |
| Acer Aspire 5742G                     | 3         | 0.19%   |
| Acer Aspire 5735                      | 3         | 0.19%   |
| YASHI MYBOOK 360                      | 2         | 0.13%   |
| Toshiba Satellite L40                 | 2         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 81        | 5.26%   |
| Lenovo ThinkPad       | 50        | 3.25%   |
| Lenovo IdeaPad        | 49        | 3.18%   |
| Dell Inspiron         | 48        | 3.12%   |
| Toshiba Satellite     | 45        | 2.92%   |
| HP Pavilion           | 45        | 2.92%   |
| Unknown               | 42        | 2.73%   |
| HP Compaq             | 41        | 2.66%   |
| Dell Latitude         | 35        | 2.27%   |
| HP ProBook            | 30        | 1.95%   |
| HP EliteBook          | 23        | 1.49%   |
| Dell OptiPlex         | 23        | 1.49%   |
| HP Laptop             | 20        | 1.3%    |
| Lenovo ThinkCentre    | 15        | 0.97%   |
| HP Notebook           | 13        | 0.84%   |
| ASUS VivoBook         | 13        | 0.84%   |
| Dell XPS              | 10        | 0.65%   |
| Dell Vostro           | 10        | 0.65%   |
| Packard Bell EasyNote | 9         | 0.58%   |
| Fujitsu Siemens AMILO | 8         | 0.52%   |
| Fujitsu LIFEBOOK      | 8         | 0.52%   |
| Dell Precision        | 8         | 0.52%   |
| ASUS PRIME            | 8         | 0.52%   |
| Acer Extensa          | 8         | 0.52%   |
| RPi Raspberry         | 7         | 0.45%   |
| HP t620               | 6         | 0.39%   |
| HP Stream             | 6         | 0.39%   |
| HP Presario           | 6         | 0.39%   |
| ASUS ROG              | 6         | 0.39%   |
| Apple MacBookPro8     | 6         | 0.39%   |
| AAEON MF-001          | 6         | 0.39%   |
| Microsoft Surface     | 5         | 0.32%   |
| HP Spectre            | 5         | 0.32%   |
| HP 250                | 5         | 0.32%   |
| Dell Studio           | 5         | 0.32%   |
| ASUS M5A97            | 5         | 0.32%   |
| Apple iMac7           | 5         | 0.32%   |
| Acer Swift            | 5         | 0.32%   |
| Supermicro X8DTT-IBX  | 4         | 0.26%   |
| MSI MS-7C37           | 4         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 135       | 8.77%   |
| 2012    | 128       | 8.32%   |
| 2010    | 117       | 7.6%    |
| 2008    | 114       | 7.41%   |
| 2013    | 104       | 6.76%   |
| 2007    | 99        | 6.43%   |
| 2009    | 91        | 5.91%   |
| 2014    | 84        | 5.46%   |
| 2017    | 80        | 5.2%    |
| 2019    | 79        | 5.13%   |
| 2016    | 75        | 4.87%   |
| 2020    | 73        | 4.74%   |
| 2015    | 72        | 4.68%   |
| 2021    | 66        | 4.29%   |
| 2018    | 59        | 3.83%   |
| 2006    | 53        | 3.44%   |
| 2022    | 43        | 2.79%   |
| 2023    | 20        | 1.3%    |
| 2005    | 20        | 1.3%    |
| Unknown | 14        | 0.91%   |
| 2004    | 6         | 0.39%   |
| 2002    | 3         | 0.19%   |
| 2001    | 2         | 0.13%   |
| 2003    | 1         | 0.06%   |
| 2000    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 956       | 62.12%  |
| Desktop        | 486       | 31.58%  |
| Mini pc        | 23        | 1.49%   |
| Convertible    | 18        | 1.17%   |
| All in one     | 16        | 1.04%   |
| Tablet         | 14        | 0.91%   |
| Server         | 13        | 0.84%   |
| System on chip | 12        | 0.78%   |
| Other          | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1457      | 94.3%   |
| Enabled  | 88        | 5.7%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1505      | 97.73%  |
| Yes  | 35        | 2.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 473       | 30.3%   |
| 4.01-8.0        | 334       | 21.4%   |
| 1.01-2.0        | 246       | 15.76%  |
| 8.01-16.0       | 170       | 10.89%  |
| 16.01-24.0      | 132       | 8.46%   |
| 2.01-3.0        | 69        | 4.42%   |
| 32.01-64.0      | 56        | 3.59%   |
| 0.51-1.0        | 47        | 3.01%   |
| 24.01-32.0      | 12        | 0.77%   |
| 64.01-256.0     | 11        | 0.7%    |
| 0.01-0.5        | 8         | 0.51%   |
| More than 256.0 | 3         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 703       | 42.76%  |
| 0.51-1.0   | 391       | 23.78%  |
| 2.01-3.0   | 269       | 16.36%  |
| 4.01-8.0   | 103       | 6.27%   |
| 3.01-4.0   | 80        | 4.87%   |
| 0.01-0.5   | 75        | 4.56%   |
| 8.01-16.0  | 17        | 1.03%   |
| 16.01-24.0 | 3         | 0.18%   |
| Unknown    | 2         | 0.12%   |
| 32.01-64.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1060      | 68.21%  |
| 2      | 345       | 22.2%   |
| 3      | 55        | 3.54%   |
| 4      | 31        | 1.99%   |
| 0      | 29        | 1.87%   |
| 5      | 19        | 1.22%   |
| 6      | 5         | 0.32%   |
| 7      | 3         | 0.19%   |
| 8      | 2         | 0.13%   |
| 17     | 1         | 0.06%   |
| 14     | 1         | 0.06%   |
| 13     | 1         | 0.06%   |
| 12     | 1         | 0.06%   |
| 10     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 815       | 52.65%  |
| Yes       | 733       | 47.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1318      | 85.47%  |
| No        | 224       | 14.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1170      | 75.83%  |
| No        | 373       | 24.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 815       | 52.34%  |
| Yes       | 742       | 47.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 244       | 15.81%  |
| France       | 154       | 9.98%   |
| Brazil       | 125       | 8.1%    |
| Germany      | 121       | 7.84%   |
| Italy        | 119       | 7.71%   |
| Russia       | 76        | 4.93%   |
| UK           | 66        | 4.28%   |
| Poland       | 45        | 2.92%   |
| Canada       | 44        | 2.85%   |
| Spain        | 38        | 2.46%   |
| Netherlands  | 29        | 1.88%   |
| Argentina    | 28        | 1.81%   |
| Australia    | 25        | 1.62%   |
| Czechia      | 22        | 1.43%   |
| Finland      | 21        | 1.36%   |
| Turkey       | 20        | 1.3%    |
| Indonesia    | 20        | 1.3%    |
| Mexico       | 19        | 1.23%   |
| Hungary      | 19        | 1.23%   |
| Belgium      | 19        | 1.23%   |
| Switzerland  | 15        | 0.97%   |
| India        | 15        | 0.97%   |
| Ukraine      | 12        | 0.78%   |
| Colombia     | 11        | 0.71%   |
| Sweden       | 10        | 0.65%   |
| Japan        | 10        | 0.65%   |
| Chile        | 10        | 0.65%   |
| Malaysia     | 9         | 0.58%   |
| Greece       | 9         | 0.58%   |
| Costa Rica   | 9         | 0.58%   |
| Ireland      | 8         | 0.52%   |
| South Africa | 7         | 0.45%   |
| Slovakia     | 7         | 0.45%   |
| Romania      | 7         | 0.45%   |
| Bulgaria     | 7         | 0.45%   |
| Portugal     | 6         | 0.39%   |
| Peru         | 6         | 0.39%   |
| Lithuania    | 6         | 0.39%   |
| Iran         | 6         | 0.39%   |
| Ecuador      | 6         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 23        | 1.42%   |
| Milan             | 17        | 1.05%   |
| Rome              | 16        | 0.99%   |
| Moscow            | 13        | 0.8%    |
| Melbourne         | 12        | 0.74%   |
| Helsinki          | 11        | 0.68%   |
| Sao Paulo         | 9         | 0.56%   |
| Warsaw            | 8         | 0.49%   |
| Prague            | 8         | 0.49%   |
| St Petersburg     | 7         | 0.43%   |
| Oshawa            | 7         | 0.43%   |
| New York          | 7         | 0.43%   |
| Lyon              | 7         | 0.43%   |
| Istanbul          | 7         | 0.43%   |
| Heredia           | 7         | 0.43%   |
| Bengaluru         | 7         | 0.43%   |
| Zurich            | 6         | 0.37%   |
| Rio de Janeiro    | 6         | 0.37%   |
| Munich            | 6         | 0.37%   |
| Kyiv              | 6         | 0.37%   |
| Kuala Lumpur      | 6         | 0.37%   |
| Houston           | 6         | 0.37%   |
| Budapest          | 6         | 0.37%   |
| Brasília         | 6         | 0.37%   |
| Bogotá           | 6         | 0.37%   |
| Athens            | 6         | 0.37%   |
| Wellington        | 5         | 0.31%   |
| Tehran            | 5         | 0.31%   |
| Stuttgart         | 5         | 0.31%   |
| Porto Alegre      | 5         | 0.31%   |
| Mexico City       | 5         | 0.31%   |
| Madrid            | 5         | 0.31%   |
| Frankfurt am Main | 5         | 0.31%   |
| Bruhl             | 5         | 0.31%   |
| Berlin            | 5         | 0.31%   |
| Yekaterinburg     | 4         | 0.25%   |
| Winnipeg          | 4         | 0.25%   |
| Uberlândia       | 4         | 0.25%   |
| Tampere           | 4         | 0.25%   |
| Sydney            | 4         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 314       | 416    | 16.14%  |
| WDC                 | 312       | 420    | 16.03%  |
| Samsung Electronics | 197       | 287    | 10.12%  |
| Unknown             | 166       | 223    | 8.53%   |
| Toshiba             | 130       | 150    | 6.68%   |
| Hitachi             | 118       | 147    | 6.06%   |
| Kingston            | 100       | 118    | 5.14%   |
| SanDisk             | 63        | 70     | 3.24%   |
| Crucial             | 60        | 77     | 3.08%   |
| HGST                | 36        | 42     | 1.85%   |
| Intel               | 28        | 39     | 1.44%   |
| Fujitsu             | 26        | 28     | 1.34%   |
| Micron Technology   | 23        | 24     | 1.18%   |
| SK hynix            | 22        | 22     | 1.13%   |
| A-DATA Technology   | 22        | 24     | 1.13%   |
| Unknown             | 21        | 22     | 1.08%   |
| Maxtor              | 19        | 21     | 0.98%   |
| China               | 19        | 22     | 0.98%   |
| Apacer              | 15        | 15     | 0.77%   |
| Patriot             | 11        | 11     | 0.57%   |
| PNY                 | 10        | 11     | 0.51%   |
| Transcend           | 8         | 10     | 0.41%   |
| SPCC                | 8         | 11     | 0.41%   |
| Silicon Motion      | 8         | 9      | 0.41%   |
| OCZ                 | 8         | 9      | 0.41%   |
| KIOXIA              | 8         | 8      | 0.41%   |
| Apple               | 8         | 15     | 0.41%   |
| LITEONIT            | 7         | 7      | 0.36%   |
| Intenso             | 7         | 7      | 0.36%   |
| Lexar               | 6         | 8      | 0.31%   |
| GOODRAM             | 6         | 6      | 0.31%   |
| Team                | 5         | 5      | 0.26%   |
| LITEON              | 5         | 6      | 0.26%   |
| LDLC                | 5         | 7      | 0.26%   |
| JMicron Technology  | 5         | 5      | 0.26%   |
| Hewlett-Packard     | 5         | 11     | 0.26%   |
| Corsair             | 5         | 5      | 0.26%   |
| Plextor             | 4         | 6      | 0.21%   |
| Phison              | 4         | 8      | 0.21%   |
| NGFF                | 4         | 4      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 34        | 1.61%   |
| Kingston SA400S37240G 240GB SSD     | 28        | 1.33%   |
| Unknown MMC Card  64GB              | 25        | 1.19%   |
| Unknown                             | 21        | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 16        | 0.76%   |
| Seagate ST9500325AS 500GB           | 14        | 0.66%   |
| Seagate ST500LT012-1DG142 500GB     | 14        | 0.66%   |
| Toshiba MQ01ABD100 1TB              | 13        | 0.62%   |
| Seagate ST500DM002-1BD142 500GB     | 13        | 0.62%   |
| Samsung SSD 850 EVO 250GB           | 12        | 0.57%   |
| Kingston SA400S37480G 480GB SSD     | 12        | 0.57%   |
| Unknown SD/MMC/MS PRO 128GB         | 11        | 0.52%   |
| Unknown MMC Card  16GB              | 11        | 0.52%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 11        | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB      | 11        | 0.52%   |
| Kingston SA400S37120G 120GB SSD     | 11        | 0.52%   |
| Crucial CT240BX500SSD1 240GB        | 10        | 0.47%   |
| Unknown NCard  32GB                 | 9         | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 8         | 0.38%   |
| Unknown DA4064  64GB                | 8         | 0.38%   |
| Toshiba MQ01ABD050 500GB            | 8         | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB      | 8         | 0.38%   |
| Seagate ST1000DM010-2EP102 1TB      | 8         | 0.38%   |
| SanDisk DF4032  32GB                | 8         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 7         | 0.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 7         | 0.33%   |
| Seagate ST3500418AS 500GB           | 7         | 0.33%   |
| Seagate Expansion 2TB               | 7         | 0.33%   |
| HGST HTS545050A7E380 500GB          | 7         | 0.33%   |
| Seagate ST9320325AS 320GB           | 6         | 0.28%   |
| Seagate ST9250315AS 250GB           | 6         | 0.28%   |
| Samsung SSD 850 EVO 500GB           | 6         | 0.28%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 0.28%   |
| Crucial CT1000MX500SSD1 1TB         | 6         | 0.28%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 0.24%   |
| WDC WD10EZEX-08WN4A0 1TB            | 5         | 0.24%   |
| Unknown MMC Card  128GB             | 5         | 0.24%   |
| Unknown M52516  16GB                | 5         | 0.24%   |
| Toshiba MQ04ABF100 1TB              | 5         | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 311       | 412    | 31.35%  |
| WDC                 | 274       | 366    | 27.62%  |
| Hitachi             | 118       | 147    | 11.9%   |
| Toshiba             | 111       | 126    | 11.19%  |
| Samsung Electronics | 59        | 86     | 5.95%   |
| HGST                | 36        | 42     | 3.63%   |
| Fujitsu             | 26        | 28     | 2.62%   |
| Maxtor              | 18        | 20     | 1.81%   |
| Unknown             | 11        | 13     | 1.11%   |
| TO Exter            | 3         | 3      | 0.3%    |
| JMicron Technology  | 3         | 3      | 0.3%    |
| IBM/Hitachi         | 3         | 4      | 0.3%    |
| Hewlett-Packard     | 3         | 4      | 0.3%    |
| Apple               | 3         | 3      | 0.3%    |
| WD MediaMax         | 2         | 3      | 0.2%    |
| USB                 | 2         | 2      | 0.2%    |
| STEC                | 2         | 3      | 0.2%    |
| XrayDisk            | 1         | 1      | 0.1%    |
| RSH-319             | 1         | 1      | 0.1%    |
| LaCie               | 1         | 1      | 0.1%    |
| External            | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| ASMT                | 1         | 2      | 0.1%    |
| Apricorn            | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 94        | 129    | 16.29%  |
| Kingston            | 85        | 101    | 14.73%  |
| Crucial             | 52        | 69     | 9.01%   |
| SanDisk             | 41        | 48     | 7.11%   |
| WDC                 | 30        | 36     | 5.2%    |
| Intel               | 22        | 32     | 3.81%   |
| A-DATA Technology   | 19        | 21     | 3.29%   |
| China               | 17        | 19     | 2.95%   |
| Apacer              | 15        | 15     | 2.6%    |
| Toshiba             | 12        | 14     | 2.08%   |
| PNY                 | 10        | 11     | 1.73%   |
| Patriot             | 10        | 10     | 1.73%   |
| Micron Technology   | 10        | 10     | 1.73%   |
| Transcend           | 8         | 10     | 1.39%   |
| OCZ                 | 8         | 9      | 1.39%   |
| LITEONIT            | 7         | 7      | 1.21%   |
| SPCC                | 6         | 7      | 1.04%   |
| Lexar               | 6         | 8      | 1.04%   |
| Intenso             | 6         | 6      | 1.04%   |
| GOODRAM             | 6         | 6      | 1.04%   |
| Team                | 5         | 5      | 0.87%   |
| LITEON              | 5         | 6      | 0.87%   |
| Corsair             | 5         | 5      | 0.87%   |
| Plextor             | 4         | 6      | 0.69%   |
| NGFF                | 4         | 4      | 0.69%   |
| KingSpec            | 4         | 6      | 0.69%   |
| Apple               | 4         | 10     | 0.69%   |
| SK hynix            | 3         | 3      | 0.52%   |
| LDLC                | 3         | 3      | 0.52%   |
| Dogfish             | 3         | 3      | 0.52%   |
| XrayDisk            | 2         | 2      | 0.35%   |
| Unknown             | 2         | 2      | 0.35%   |
| Teclast             | 2         | 2      | 0.35%   |
| ORTIAL              | 2         | 2      | 0.35%   |
| Netac               | 2         | 2      | 0.35%   |
| Mushkin             | 2         | 2      | 0.35%   |
| Londisk             | 2         | 2      | 0.35%   |
| KingDian            | 2         | 2      | 0.35%   |
| Hewlett-Packard     | 2         | 7      | 0.35%   |
| Gigabyte Technology | 2         | 2      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 866       | 1273   | 48.52%  |
| SSD     | 542       | 707    | 30.36%  |
| MMC     | 186       | 245    | 10.42%  |
| NVMe    | 170       | 223    | 9.52%   |
| Unknown | 21        | 30     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1245      | 1923   | 74.82%  |
| MMC  | 186       | 245    | 11.18%  |
| NVMe | 169       | 222    | 10.16%  |
| SAS  | 64        | 88     | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1035      | 1398   | 72.18%  |
| 0.51-1.0   | 277       | 394    | 19.32%  |
| 1.01-2.0   | 73        | 104    | 5.09%   |
| 3.01-4.0   | 26        | 53     | 1.81%   |
| 2.01-3.0   | 13        | 17     | 0.91%   |
| 4.01-10.0  | 10        | 14     | 0.7%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 483       | 30.74%  |
| 251-500        | 352       | 22.41%  |
| 51-100         | 165       | 10.5%   |
| 501-1000       | 151       | 9.61%   |
| 1-20           | 129       | 8.21%   |
| 21-50          | 126       | 8.02%   |
| 1001-2000      | 74        | 4.71%   |
| More than 3000 | 50        | 3.18%   |
| 2001-3000      | 32        | 2.04%   |
| Unknown        | 9         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 811       | 50.22%  |
| 21-50          | 302       | 18.7%   |
| 101-250        | 164       | 10.15%  |
| 51-100         | 131       | 8.11%   |
| 251-500        | 70        | 4.33%   |
| 501-1000       | 59        | 3.65%   |
| 1001-2000      | 34        | 2.11%   |
| More than 3000 | 25        | 1.55%   |
| 2001-3000      | 10        | 0.62%   |
| Unknown        | 9         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 9      | 3.85%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 1.92%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 1.92%   |
| Hitachi HTS545032B9A300 320GB      | 4         | 4      | 1.92%   |
| Apacer 16GB SATA Flash Drive SSD   | 4         | 4      | 1.92%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 1.44%   |
| Seagate ST1000DM003-9YN162 1TB     | 3         | 3      | 1.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 2         | 2      | 0.96%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 2         | 2      | 0.96%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 3      | 0.96%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 0.96%   |
| Toshiba DT01ACA050 500GB           | 2         | 2      | 0.96%   |
| Seagate ST9500420AS 500GB          | 2         | 2      | 0.96%   |
| Seagate ST9250315AS 250GB          | 2         | 2      | 0.96%   |
| Seagate ST500LM021-1KJ152 500GB    | 2         | 2      | 0.96%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 3      | 0.96%   |
| Samsung Electronics HD502IJ 500GB  | 2         | 2      | 0.96%   |
| Hitachi HTS542512K9SA00 120GB      | 2         | 2      | 0.96%   |
| HGST HTS545050A7E380 500GB         | 2         | 2      | 0.96%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.48%   |
| WDC WD800BEVS-60RST0 80GB          | 1         | 1      | 0.48%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1         | 2      | 0.48%   |
| WDC WD5000LUCT-62C26Y0 500GB       | 1         | 1      | 0.48%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 1      | 0.48%   |
| WDC WD5000BPVT-75HXZT1 500GB       | 1         | 1      | 0.48%   |
| WDC WD5000AAKX-003CA0 500GB        | 1         | 1      | 0.48%   |
| WDC WD5000AAKX-001CA0 500GB        | 1         | 1      | 0.48%   |
| WDC WD400EB-00CPF0 40GB            | 1         | 1      | 0.48%   |
| WDC WD400BB-75CAA0 40GB            | 1         | 1      | 0.48%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.48%   |
| WDC WD3200BPVT-75ZEST0 320GB       | 1         | 1      | 0.48%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 0.48%   |
| WDC WD3200BEVT-75A23T0 320GB       | 1         | 1      | 0.48%   |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.48%   |
| WDC WD3200AAJS-00L7A0 320GB        | 1         | 1      | 0.48%   |
| WDC WD3200AACS-00M6B0 320GB        | 1         | 1      | 0.48%   |
| WDC WD2500HHTZ-04N21V0 250GB       | 1         | 1      | 0.48%   |
| WDC WD2500BEVT-80A23T0 250GB       | 1         | 2      | 0.48%   |
| WDC WD2500AAJS-75M0A0 250GB        | 1         | 1      | 0.48%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1         | 1      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 67     | 27.72%  |
| WDC                 | 41        | 48     | 20.3%   |
| Hitachi             | 25        | 27     | 12.38%  |
| Toshiba             | 14        | 14     | 6.93%   |
| Samsung Electronics | 7         | 15     | 3.47%   |
| HGST                | 7         | 7      | 3.47%   |
| Maxtor              | 5         | 5      | 2.48%   |
| Kingston            | 5         | 5      | 2.48%   |
| Intel               | 5         | 6      | 2.48%   |
| Crucial             | 5         | 5      | 2.48%   |
| Fujitsu             | 4         | 4      | 1.98%   |
| Apacer              | 4         | 4      | 1.98%   |
| SK hynix            | 3         | 3      | 1.49%   |
| OCZ                 | 2         | 3      | 0.99%   |
| LITEON              | 2         | 2      | 0.99%   |
| KingSpec            | 2         | 4      | 0.99%   |
| Apple               | 2         | 2      | 0.99%   |
| A-DATA Technology   | 2         | 2      | 0.99%   |
| Transcend           | 1         | 1      | 0.5%    |
| TCSUNBOW            | 1         | 1      | 0.5%    |
| Silicon Motion      | 1         | 1      | 0.5%    |
| SanDisk             | 1         | 1      | 0.5%    |
| Plextor             | 1         | 1      | 0.5%    |
| ORTIAL              | 1         | 1      | 0.5%    |
| NGFF                | 1         | 1      | 0.5%    |
| Mushkin             | 1         | 1      | 0.5%    |
| Micron Technology   | 1         | 1      | 0.5%    |
| LDLC                | 1         | 1      | 0.5%    |
| Kingmax             | 1         | 1      | 0.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 67     | 35.9%   |
| WDC                 | 38        | 45     | 24.36%  |
| Hitachi             | 25        | 27     | 16.03%  |
| Toshiba             | 14        | 14     | 8.97%   |
| HGST                | 7         | 7      | 4.49%   |
| Samsung Electronics | 6         | 14     | 3.85%   |
| Maxtor              | 5         | 5      | 3.21%   |
| Fujitsu             | 4         | 4      | 2.56%   |
| Apple               | 1         | 1      | 0.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 149       | 184    | 76.41%  |
| SSD  | 43        | 47     | 22.05%  |
| NVMe | 3         | 3      | 1.54%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-75V0TT0 500GB      | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-40RYA0 320GB       | 1         | 1      | 7.14%   |
| WDC WD2500BEVT-75A23T0 250GB      | 1         | 2      | 7.14%   |
| WDC WD1200BEVS-22UST0 120GB       | 1         | 1      | 7.14%   |
| WDC WD10SPZX-22Z10T0 1TB          | 1         | 1      | 7.14%   |
| Toshiba HDWD110 1TB               | 1         | 1      | 7.14%   |
| Seagate ST9320325AS 320GB         | 1         | 1      | 7.14%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 980 1TB   | 1         | 1      | 7.14%   |
| Samsung Electronics SSD 850 250GB | 1         | 1      | 7.14%   |
| Samsung Electronics HM320JI 320GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD080HJ 80GB  | 1         | 1      | 7.14%   |
| Intel SSDSA1M160G2HP 160GB        | 1         | 1      | 7.14%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 6      | 35.71%  |
| Samsung Electronics | 4         | 4      | 28.57%  |
| Seagate             | 2         | 2      | 14.29%  |
| Toshiba             | 1         | 1      | 7.14%   |
| Intel               | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 833       | 1323   | 50.73%  |
| Works    | 603       | 906    | 36.72%  |
| Malfunc  | 192       | 234    | 11.69%  |
| Failed   | 14        | 15     | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 992       | 61.58%  |
| AMD                              | 270       | 16.76%  |
| Nvidia                           | 72        | 4.47%   |
| Samsung Electronics              | 50        | 3.1%    |
| SanDisk                          | 23        | 1.43%   |
| JMicron Technology               | 23        | 1.43%   |
| ASMedia Technology               | 18        | 1.12%   |
| Kingston Technology Company      | 17        | 1.06%   |
| Micron Technology                | 15        | 0.93%   |
| VIA Technologies                 | 14        | 0.87%   |
| SK hynix                         | 13        | 0.81%   |
| Silicon Integrated Systems [SiS] | 13        | 0.81%   |
| Marvell Technology Group         | 13        | 0.81%   |
| Silicon Motion                   | 12        | 0.74%   |
| Micron/Crucial Technology        | 10        | 0.62%   |
| KIOXIA                           | 8         | 0.5%    |
| Toshiba America Info Systems     | 7         | 0.43%   |
| Silicon Image                    | 7         | 0.43%   |
| Phison Electronics               | 6         | 0.37%   |
| LSI Logic / Symbios Logic        | 5         | 0.31%   |
| Union Memory (Shenzhen)          | 3         | 0.19%   |
| Broadcom / LSI                   | 3         | 0.19%   |
| ADATA Technology                 | 3         | 0.19%   |
| ULi Electronics                  | 2         | 0.12%   |
| Solid State Storage Technology   | 2         | 0.12%   |
| Shenzhen Longsys Electronics     | 2         | 0.12%   |
| Zhaoxin                          | 1         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.06%   |
| Seagate Technology               | 1         | 0.06%   |
| Hosin Global Electronics         | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Broadcom                         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 161       | 8.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 83        | 4.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 64        | 3.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 53        | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 53        | 2.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 51        | 2.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 50        | 2.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 50        | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 50        | 2.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 49        | 2.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 42        | 2.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 39        | 1.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 38        | 1.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 37        | 1.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 34        | 1.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 33        | 1.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 30        | 1.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 25        | 1.26%   |
| Nvidia MCP61 SATA Controller                                                            | 25        | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 25        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 23        | 1.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 21        | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 21        | 1.06%   |
| Nvidia MCP61 IDE                                                                        | 20        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 18        | 0.91%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17        | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 17        | 0.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 16        | 0.81%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 16        | 0.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 15        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 15        | 0.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 14        | 0.71%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 14        | 0.71%   |
| AMD 400 Series Chipset SATA Controller                                                  | 14        | 0.71%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 13        | 0.66%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 13        | 0.66%   |
| Intel SATA Controller [RAID mode]                                                       | 13        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1029      | 60.57%  |
| IDE  | 417       | 24.54%  |
| NVMe | 167       | 9.83%   |
| RAID | 81        | 4.77%   |
| SCSI | 3         | 0.18%   |
| SAS  | 2         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1177      | 76.48%  |
| AMD          | 347       | 22.55%  |
| ARM          | 12        | 0.78%   |
| PowerMac7,2  | 1         | 0.06%   |
| CentaurHauls | 1         | 0.06%   |
| Unknown      | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 30        | 1.95%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 17        | 1.1%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz           | 17        | 1.1%    |
| Intel Celeron CPU N2840 @ 2.16GHz           | 14        | 0.91%   |
| Intel Atom CPU N270 @ 1.60GHz               | 14        | 0.91%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 12        | 0.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 12        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 11        | 0.71%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 11        | 0.71%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 11        | 0.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 11        | 0.71%   |
| ARM Processor                               | 11        | 0.71%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 10        | 0.65%   |
| Intel Atom CPU Z3735F @ 1.33GHz             | 10        | 0.65%   |
| Intel Atom CPU N450 @ 1.66GHz               | 10        | 0.65%   |
| AMD E-450 APU with Radeon HD Graphics       | 10        | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 9         | 0.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 9         | 0.58%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 9         | 0.58%   |
| Intel Atom CPU N455 @ 1.66GHz               | 9         | 0.58%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 8         | 0.52%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 8         | 0.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 0.52%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 7         | 0.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 0.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 7         | 0.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 7         | 0.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7         | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 0.45%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 0.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 7         | 0.45%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz        | 7         | 0.45%   |
| AMD E-300 APU with Radeon HD Graphics       | 7         | 0.45%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 6         | 0.39%   |
| Intel Pentium 4 CPU 2.80GHz                 | 6         | 0.39%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6         | 0.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 6         | 0.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 6         | 0.39%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 6         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 223       | 14.49%  |
| Intel Celeron           | 180       | 11.7%   |
| Intel Atom              | 133       | 8.64%   |
| Intel Core i7           | 128       | 8.32%   |
| Intel Core i3           | 112       | 7.28%   |
| Intel Core 2 Duo        | 109       | 7.08%   |
| Other                   | 54        | 3.51%   |
| Intel Pentium           | 45        | 2.92%   |
| Intel Pentium Dual-Core | 36        | 2.34%   |
| Intel Pentium Dual      | 36        | 2.34%   |
| AMD Ryzen 7             | 33        | 2.14%   |
| AMD Ryzen 5             | 32        | 2.08%   |
| Intel Xeon              | 28        | 1.82%   |
| AMD Athlon 64 X2        | 27        | 1.75%   |
| Intel Core 2            | 23        | 1.49%   |
| AMD E                   | 23        | 1.49%   |
| AMD A6                  | 20        | 1.3%    |
| AMD E1                  | 19        | 1.23%   |
| AMD A4                  | 18        | 1.17%   |
| Intel Pentium 4         | 17        | 1.1%    |
| Intel Genuine           | 15        | 0.97%   |
| Intel Core 2 Quad       | 14        | 0.91%   |
| AMD FX                  | 13        | 0.84%   |
| AMD A8                  | 13        | 0.84%   |
| AMD A10                 | 13        | 0.84%   |
| AMD Athlon II X2        | 12        | 0.78%   |
| AMD E2                  | 10        | 0.65%   |
| AMD Athlon 64           | 8         | 0.52%   |
| Intel Pentium Silver    | 7         | 0.45%   |
| Intel Celeron Dual-Core | 7         | 0.45%   |
| AMD Ryzen 3             | 7         | 0.45%   |
| AMD GX                  | 7         | 0.45%   |
| AMD Athlon              | 7         | 0.45%   |
| Intel Pentium D         | 6         | 0.39%   |
| Intel Celeron M         | 6         | 0.39%   |
| AMD Phenom II X4        | 6         | 0.39%   |
| AMD Mobile Sempron      | 6         | 0.39%   |
| Intel Pentium M         | 5         | 0.32%   |
| AMD Turion 64 X2 Mobile | 5         | 0.32%   |
| AMD C-50                | 5         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 891       | 57.89%  |
| 4       | 404       | 26.25%  |
| 1       | 124       | 8.06%   |
| 8       | 47        | 3.05%   |
| 6       | 42        | 2.73%   |
| 3       | 8         | 0.52%   |
| 10      | 7         | 0.45%   |
| 12      | 5         | 0.32%   |
| Unknown | 4         | 0.26%   |
| 16      | 2         | 0.13%   |
| 64      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 32      | 1         | 0.06%   |
| 20      | 1         | 0.06%   |
| 14      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1519      | 98.7%   |
| 2       | 15        | 0.97%   |
| Unknown | 4         | 0.26%   |
| 4       | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 878       | 57.05%  |
| 2       | 656       | 42.63%  |
| Unknown | 4         | 0.26%   |
| 8       | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1468      | 95.39%  |
| 32-bit         | 61        | 3.96%   |
| Unknown        | 9         | 0.58%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 491       | 31.31%  |
| 0x206a7    | 79        | 5.04%   |
| 0x306a9    | 66        | 4.21%   |
| 0x1067a    | 65        | 4.15%   |
| 0x6fd      | 54        | 3.44%   |
| 0x406c4    | 36        | 2.3%    |
| 0x20655    | 33        | 2.1%    |
| 0x30678    | 31        | 1.98%   |
| 0x05000119 | 31        | 1.98%   |
| 0x306c3    | 30        | 1.91%   |
| 0x40651    | 29        | 1.85%   |
| 0x106ca    | 28        | 1.79%   |
| 0x406c3    | 23        | 1.47%   |
| 0x406e3    | 21        | 1.34%   |
| 0x6fb      | 18        | 1.15%   |
| 0x106c2    | 18        | 1.15%   |
| 0x806ec    | 17        | 1.08%   |
| 0x706a8    | 17        | 1.08%   |
| 0x10676    | 17        | 1.08%   |
| 0x0700010f | 17        | 1.08%   |
| 0x706a1    | 16        | 1.02%   |
| 0x806e9    | 13        | 0.83%   |
| 0x6f6      | 13        | 0.83%   |
| 0x20652    | 13        | 0.83%   |
| 0x06006705 | 13        | 0.83%   |
| 0x806ea    | 12        | 0.77%   |
| 0x506c9    | 12        | 0.77%   |
| 0x06001119 | 12        | 0.77%   |
| 0x010000c8 | 12        | 0.77%   |
| 0x906ea    | 10        | 0.64%   |
| 0x6e8      | 10        | 0.64%   |
| 0x306d4    | 10        | 0.64%   |
| 0x05000029 | 10        | 0.64%   |
| 0x806c1    | 9         | 0.57%   |
| 0x6d8      | 9         | 0.57%   |
| 0x06000852 | 9         | 0.57%   |
| 0x706e5    | 8         | 0.51%   |
| 0x10661    | 8         | 0.51%   |
| 0x0a50000c | 8         | 0.51%   |
| 0x06006704 | 8         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 140       | 9.1%    |
| Core             | 127       | 8.25%   |
| Penryn           | 118       | 7.67%   |
| SandyBridge      | 110       | 7.15%   |
| IvyBridge        | 103       | 6.69%   |
| KabyLake         | 86        | 5.59%   |
| Haswell          | 86        | 5.59%   |
| Westmere         | 74        | 4.81%   |
| Bonnell          | 62        | 4.03%   |
| K8 Hammer        | 53        | 3.44%   |
| Goldmont plus    | 50        | 3.25%   |
| Bobcat           | 48        | 3.12%   |
| Skylake          | 47        | 3.05%   |
| K10              | 37        | 2.4%    |
| Excavator        | 37        | 2.4%    |
| NetBurst         | 28        | 1.82%   |
| Unknown          | 28        | 1.82%   |
| Piledriver       | 27        | 1.75%   |
| P6               | 26        | 1.69%   |
| Goldmont         | 25        | 1.62%   |
| Zen 3            | 23        | 1.49%   |
| Jaguar           | 23        | 1.49%   |
| Zen 2            | 22        | 1.43%   |
| Zen+             | 21        | 1.36%   |
| TigerLake        | 17        | 1.1%    |
| Broadwell        | 17        | 1.1%    |
| IceLake          | 15        | 0.97%   |
| Nehalem          | 14        | 0.91%   |
| Zen              | 13        | 0.84%   |
| Puma             | 13        | 0.84%   |
| CometLake        | 10        | 0.65%   |
| Tremont          | 9         | 0.58%   |
| Alderlake Hybrid | 8         | 0.52%   |
| Steamroller      | 6         | 0.39%   |
| K8 & K10 hybrid  | 6         | 0.39%   |
| K10 Llano        | 5         | 0.32%   |
| Gracemont        | 3         | 0.19%   |
| K6               | 1         | 0.06%   |
| Bulldozer        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 925       | 55.39%  |
| AMD                              | 399       | 23.89%  |
| Nvidia                           | 314       | 18.8%   |
| Matrox Electronics Systems       | 12        | 0.72%   |
| Silicon Integrated Systems [SiS] | 11        | 0.66%   |
| VIA Technologies                 | 6         | 0.36%   |
| Zhaoxin                          | 1         | 0.06%   |
| S3 Graphics                      | 1         | 0.06%   |
| ASPEED Technology                | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 89        | 4.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 82        | 4.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 67        | 3.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 58        | 3.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 50        | 2.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 50        | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 49        | 2.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 2.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 44        | 2.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 2.13%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 31        | 1.73%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 30        | 1.68%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 28        | 1.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.34%   |
| Intel HD Graphics 500                                                                    | 24        | 1.34%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 1.12%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 17        | 0.95%   |
| Intel HD Graphics 620                                                                    | 17        | 0.95%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 15        | 0.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 0.78%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 14        | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 0.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 0.78%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.73%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 0.73%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 13        | 0.73%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 0.67%   |
| Intel UHD Graphics 620                                                                   | 12        | 0.67%   |
| Intel HD Graphics 5500                                                                   | 12        | 0.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 0.67%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12        | 0.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 12        | 0.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 12        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 11        | 0.62%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 11        | 0.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 0.62%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 11        | 0.62%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 0.62%   |
| Intel JasperLake [UHD Graphics]                                                          | 10        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 789       | 51.07%  |
| 1 x AMD            | 319       | 20.65%  |
| 1 x Nvidia         | 220       | 14.24%  |
| Intel + Nvidia     | 78        | 5.05%   |
| Intel + AMD        | 39        | 2.52%   |
| 2 x AMD            | 30        | 1.94%   |
| Other              | 20        | 1.29%   |
| 1 x SiS            | 11        | 0.71%   |
| 1 x Matrox         | 11        | 0.71%   |
| AMD + Nvidia       | 10        | 0.65%   |
| 1 x VIA            | 6         | 0.39%   |
| 2 x Intel          | 4         | 0.26%   |
| 2 x Nvidia         | 2         | 0.13%   |
| 1 x Zhaoxin        | 1         | 0.06%   |
| 1 x S3 Graphics    | 1         | 0.06%   |
| Nvidia + Matrox    | 1         | 0.06%   |
| Intel + 2 x Nvidia | 1         | 0.06%   |
| Intel + 2 x AMD    | 1         | 0.06%   |
| 1 x ASPEED         | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1357      | 87.77%  |
| Proprietary | 119       | 7.7%    |
| Unknown     | 70        | 4.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 944       | 60.59%  |
| 0.01-0.5   | 323       | 20.73%  |
| 1.01-2.0   | 115       | 7.38%   |
| 0.51-1.0   | 102       | 6.55%   |
| 3.01-4.0   | 36        | 2.31%   |
| 7.01-8.0   | 15        | 0.96%   |
| 5.01-6.0   | 9         | 0.58%   |
| 2.01-3.0   | 7         | 0.45%   |
| 8.01-16.0  | 7         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 215       | 14.37%  |
| AU Optronics            | 193       | 12.9%   |
| LG Display              | 143       | 9.56%   |
| BOE                     | 120       | 8.02%   |
| Chimei Innolux          | 110       | 7.35%   |
| Dell                    | 72        | 4.81%   |
| Acer                    | 49        | 3.28%   |
| Goldstar                | 48        | 3.21%   |
| Chi Mei Optoelectronics | 42        | 2.81%   |
| Hewlett-Packard         | 39        | 2.61%   |
| Lenovo                  | 32        | 2.14%   |
| Apple                   | 32        | 2.14%   |
| Philips                 | 31        | 2.07%   |
| LG Philips              | 29        | 1.94%   |
| HannStar                | 24        | 1.6%    |
| AOC                     | 24        | 1.6%    |
| BenQ                    | 20        | 1.34%   |
| Ancor Communications    | 18        | 1.2%    |
| InfoVision              | 16        | 1.07%   |
| Iiyama                  | 15        | 1%      |
| CPT                     | 14        | 0.94%   |
| Sharp                   | 13        | 0.87%   |
| Vizio                   | 10        | 0.67%   |
| Unknown                 | 10        | 0.67%   |
| Sony                    | 10        | 0.67%   |
| PANDA                   | 9         | 0.6%    |
| NEC Computers           | 9         | 0.6%    |
| Toshiba                 | 7         | 0.47%   |
| Sceptre Tech            | 6         | 0.4%    |
| LG Electronics          | 6         | 0.4%    |
| ASUSTek Computer        | 6         | 0.4%    |
| Fujitsu Siemens         | 5         | 0.33%   |
| Eizo                    | 5         | 0.33%   |
| ViewSonic               | 4         | 0.27%   |
| MSI                     | 4         | 0.27%   |
| InnoLux Display         | 4         | 0.27%   |
| Unknown (ADA)           | 3         | 0.2%    |
| RTK                     | 3         | 0.2%    |
| Positivo                | 3         | 0.2%    |
| Plain Tree Systems      | 3         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 10        | 0.66%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.66%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 9         | 0.59%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch              | 8         | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.53%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 7         | 0.46%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.4%    |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 5         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch            | 5         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 4         | 0.26%   |
| BOE LCD Monitor BOE0771 1366x768 256x144mm 11.6-inch                     | 4         | 0.26%   |
| BOE LCD Monitor BOE075A 1366x768 309x173mm 13.9-inch                     | 4         | 0.26%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.26%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.26%   |
| BOE LCD Monitor BOE0635 1920x1080 309x173mm 13.9-inch                    | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 4         | 0.26%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.26%   |
| Acer H213H ACR0087 1920x1080 531x299mm 24.0-inch                         | 4         | 0.26%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 3         | 0.2%    |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch            | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 471       | 31.93%  |
| 1920x1080 (FHD)    | 405       | 27.46%  |
| 1280x800 (WXGA)    | 118       | 8%      |
| 1280x1024 (SXGA)   | 78        | 5.29%   |
| 1600x900 (HD+)     | 72        | 4.88%   |
| 1680x1050 (WSXGA+) | 53        | 3.59%   |
| 1440x900 (WXGA+)   | 45        | 3.05%   |
| 3840x2160 (4K)     | 41        | 2.78%   |
| 1024x600           | 33        | 2.24%   |
| 2560x1440 (QHD)    | 32        | 2.17%   |
| 1920x1200 (WUXGA)  | 27        | 1.83%   |
| 1024x768 (XGA)     | 16        | 1.08%   |
| 1360x768           | 15        | 1.02%   |
| Unknown            | 9         | 0.61%   |
| 2288x1287          | 6         | 0.41%   |
| 3840x2400          | 4         | 0.27%   |
| 2560x1600          | 4         | 0.27%   |
| 2160x1440          | 4         | 0.27%   |
| 1280x720 (HD)      | 4         | 0.27%   |
| 3440x1440          | 3         | 0.2%    |
| 3200x1800 (QHD+)   | 3         | 0.2%    |
| 2560x1080          | 3         | 0.2%    |
| 1920x540           | 3         | 0.2%    |
| 1280x768           | 3         | 0.2%    |
| 3600x1200          | 2         | 0.14%   |
| 3200x1080          | 2         | 0.14%   |
| 2880x1800          | 2         | 0.14%   |
| 2736x1824          | 2         | 0.14%   |
| 2048x1536          | 2         | 0.14%   |
| 1600x1200          | 2         | 0.14%   |
| 800x600            | 1         | 0.07%   |
| 5760x2160          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3120x2080          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2160x1200          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |
| 1528x1222          | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |
| 1360x765           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 419       | 28.12%  |
| 14      | 146       | 9.8%    |
| 13      | 142       | 9.53%   |
| 17      | 98        | 6.58%   |
| 24      | 71        | 4.77%   |
| 11      | 69        | 4.63%   |
| 19      | 65        | 4.36%   |
| 23      | 60        | 4.03%   |
| 27      | 52        | 3.49%   |
| 21      | 52        | 3.49%   |
| Unknown | 51        | 3.42%   |
| 10      | 36        | 2.42%   |
| 18      | 34        | 2.28%   |
| 22      | 33        | 2.21%   |
| 12      | 32        | 2.15%   |
| 20      | 31        | 2.08%   |
| 31      | 12        | 0.81%   |
| 72      | 10        | 0.67%   |
| 84      | 9         | 0.6%    |
| 40      | 5         | 0.34%   |
| 47      | 4         | 0.27%   |
| 34      | 4         | 0.27%   |
| 26      | 4         | 0.27%   |
| 8       | 4         | 0.27%   |
| 142     | 3         | 0.2%    |
| 65      | 3         | 0.2%    |
| 32      | 3         | 0.2%    |
| 9       | 3         | 0.2%    |
| 7       | 3         | 0.2%    |
| 54      | 2         | 0.13%   |
| 52      | 2         | 0.13%   |
| 49      | 2         | 0.13%   |
| 48      | 2         | 0.13%   |
| 43      | 2         | 0.13%   |
| 42      | 2         | 0.13%   |
| 39      | 2         | 0.13%   |
| 38      | 2         | 0.13%   |
| 29      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 25      | 2         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 657       | 44.39%  |
| 201-300        | 206       | 13.92%  |
| 501-600        | 184       | 12.43%  |
| 401-500        | 170       | 11.49%  |
| 351-400        | 119       | 8.04%   |
| Unknown        | 51        | 3.45%   |
| 601-700        | 20        | 1.35%   |
| 1501-2000      | 19        | 1.28%   |
| 1001-1500      | 18        | 1.22%   |
| 801-900        | 10        | 0.68%   |
| 101-200        | 9         | 0.61%   |
| 701-800        | 8         | 0.54%   |
| 901-1000       | 6         | 0.41%   |
| More than 2000 | 3         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1003      | 71.19%  |
| 16/10   | 239       | 16.96%  |
| 5/4     | 75        | 5.32%   |
| Unknown | 40        | 2.84%   |
| 4/3     | 29        | 2.06%   |
| 3/2     | 13        | 0.92%   |
| 21/9    | 5         | 0.35%   |
| 1.00    | 3         | 0.21%   |
| 6/5     | 2         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 414       | 27.88%  |
| 81-90          | 240       | 16.16%  |
| 201-250        | 177       | 11.92%  |
| 151-200        | 115       | 7.74%   |
| 51-60          | 69        | 4.65%   |
| 141-150        | 60        | 4.04%   |
| 301-350        | 54        | 3.64%   |
| Unknown        | 51        | 3.43%   |
| 71-80          | 48        | 3.23%   |
| 121-130        | 48        | 3.23%   |
| 41-50          | 39        | 2.63%   |
| More than 1000 | 35        | 2.36%   |
| 251-300        | 30        | 2.02%   |
| 61-70          | 28        | 1.89%   |
| 501-1000       | 22        | 1.48%   |
| 351-500        | 21        | 1.41%   |
| 131-140        | 15        | 1.01%   |
| 1-40           | 8         | 0.54%   |
| 91-100         | 6         | 0.4%    |
| 111-120        | 5         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 518       | 35.43%  |
| 51-100        | 502       | 34.34%  |
| 121-160       | 289       | 19.77%  |
| Unknown       | 51        | 3.49%   |
| 161-240       | 49        | 3.35%   |
| 1-50          | 38        | 2.6%    |
| More than 240 | 15        | 1.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1363      | 87.48%  |
| 2     | 135       | 8.66%   |
| 0     | 51        | 3.27%   |
| 3     | 8         | 0.51%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 821       | 34.69%  |
| Intel                            | 521       | 22.01%  |
| Qualcomm Atheros                 | 335       | 14.15%  |
| Broadcom                         | 176       | 7.44%   |
| Nvidia                           | 61        | 2.58%   |
| Marvell Technology Group         | 59        | 2.49%   |
| Ralink Technology                | 57        | 2.41%   |
| Broadcom Limited                 | 42        | 1.77%   |
| Ralink                           | 40        | 1.69%   |
| TP-Link                          | 27        | 1.14%   |
| Samsung Electronics              | 20        | 0.84%   |
| ASIX Electronics                 | 15        | 0.63%   |
| MediaTek                         | 14        | 0.59%   |
| Xiaomi                           | 11        | 0.46%   |
| VIA Technologies                 | 11        | 0.46%   |
| Attansic Technology              | 11        | 0.46%   |
| Silicon Integrated Systems [SiS] | 9         | 0.38%   |
| NetGear                          | 9         | 0.38%   |
| Huawei Technologies              | 9         | 0.38%   |
| Qualcomm Atheros Communications  | 8         | 0.34%   |
| JMicron Technology               | 8         | 0.34%   |
| D-Link                           | 7         | 0.3%    |
| Belkin Components                | 7         | 0.3%    |
| AMD                              | 5         | 0.21%   |
| Mellanox Technologies            | 4         | 0.17%   |
| ICS Advent                       | 4         | 0.17%   |
| Dell                             | 4         | 0.17%   |
| D-Link System                    | 4         | 0.17%   |
| ASUSTek Computer                 | 4         | 0.17%   |
| OPPO Electronics                 | 3         | 0.13%   |
| Micro Star International         | 3         | 0.13%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| 3Com                             | 3         | 0.13%   |
| ULi Electronics                  | 2         | 0.08%   |
| Seeed Technology                 | 2         | 0.08%   |
| Qualcomm                         | 2         | 0.08%   |
| Motorola PCS                     | 2         | 0.08%   |
| Linksys                          | 2         | 0.08%   |
| Intersil                         | 2         | 0.08%   |
| FIBOCOM                          | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 469       | 17.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 164       | 6.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 64        | 2.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 49        | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 42        | 1.55%   |
| Intel Wireless 7260                                                     | 39        | 1.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 38        | 1.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 37        | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 37        | 1.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 1.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 1.07%   |
| Intel Wireless 7265                                                     | 27        | 0.99%   |
| Intel Wireless 3165                                                     | 26        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 25        | 0.92%   |
| Ralink MT7601U Wireless Adapter                                         | 25        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 22        | 0.81%   |
| Nvidia MCP61 Ethernet                                                   | 22        | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 18        | 0.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                | 18        | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 17        | 0.63%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 0.55%   |
| Intel Wireless 8265 / 8275                                              | 15        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 14        | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 14        | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 14        | 0.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 0.52%   |
| Intel Ethernet Connection I217-LM                                       | 14        | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 13        | 0.48%   |
| Realtek 802.11ac NIC                                                    | 13        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 13        | 0.48%   |
| Intel Wireless 8260                                                     | 13        | 0.48%   |
| Intel Wireless 3160                                                     | 12        | 0.44%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 12        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 387       | 31.36%  |
| Qualcomm Atheros                      | 277       | 22.45%  |
| Realtek Semiconductor                 | 239       | 19.37%  |
| Broadcom                              | 113       | 9.16%   |
| Ralink Technology                     | 57        | 4.62%   |
| Ralink                                | 40        | 3.24%   |
| TP-Link                               | 25        | 2.03%   |
| Broadcom Limited                      | 24        | 1.94%   |
| MediaTek                              | 12        | 0.97%   |
| Qualcomm Atheros Communications       | 8         | 0.65%   |
| NetGear                               | 8         | 0.65%   |
| Belkin Components                     | 7         | 0.57%   |
| D-Link                                | 6         | 0.49%   |
| Marvell Technology Group              | 5         | 0.41%   |
| ASUSTek Computer                      | 4         | 0.32%   |
| Micro Star International              | 3         | 0.24%   |
| Linksys                               | 2         | 0.16%   |
| FIBOCOM                               | 2         | 0.16%   |
| Edimax Technology                     | 2         | 0.16%   |
| Dell                                  | 2         | 0.16%   |
| D-Link System                         | 2         | 0.16%   |
| ZyXEL Communications                  | 1         | 0.08%   |
| Tenda                                 | 1         | 0.08%   |
| Sitecom Europe                        | 1         | 0.08%   |
| Sierra Wireless                       | 1         | 0.08%   |
| Samsung Electronics                   | 1         | 0.08%   |
| Microsoft                             | 1         | 0.08%   |
| Logitec                               | 1         | 0.08%   |
| IMC Networks                          | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 64        | 5.15%   |
| Intel Wireless 7260                                                     | 39        | 3.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 3.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 38        | 3.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 37        | 2.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 37        | 2.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 37        | 2.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 2.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 29        | 2.33%   |
| Intel Wireless 7265                                                     | 27        | 2.17%   |
| Intel Wireless 3165                                                     | 26        | 2.09%   |
| Ralink MT7601U Wireless Adapter                                         | 25        | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 22        | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 18        | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 18        | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 1.45%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 17        | 1.37%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 15        | 1.21%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 1.21%   |
| Intel Wireless 8265 / 8275                                              | 15        | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 14        | 1.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 1.13%   |
| Realtek 802.11ac NIC                                                    | 13        | 1.05%   |
| Intel Wireless 8260                                                     | 13        | 1.05%   |
| Intel Wireless 3160                                                     | 12        | 0.97%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 12        | 0.97%   |
| Realtek 802.11n WLAN Adapter                                            | 11        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.88%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 11        | 0.88%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 10        | 0.8%    |
| Ralink RT5370 Wireless Adapter                                          | 10        | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 10        | 0.8%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 0.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 9         | 0.72%   |
| Intel Centrino Ultimate-N 6300                                          | 9         | 0.72%   |
| Intel Centrino Advanced-N 6200                                          | 9         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 9         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 721       | 50.85%  |
| Intel                            | 243       | 17.14%  |
| Qualcomm Atheros                 | 103       | 7.26%   |
| Broadcom                         | 83        | 5.85%   |
| Nvidia                           | 61        | 4.3%    |
| Marvell Technology Group         | 54        | 3.81%   |
| Samsung Electronics              | 19        | 1.34%   |
| Broadcom Limited                 | 18        | 1.27%   |
| ASIX Electronics                 | 15        | 1.06%   |
| Xiaomi                           | 11        | 0.78%   |
| VIA Technologies                 | 11        | 0.78%   |
| Attansic Technology              | 11        | 0.78%   |
| Silicon Integrated Systems [SiS] | 9         | 0.63%   |
| JMicron Technology               | 8         | 0.56%   |
| Huawei Technologies              | 7         | 0.49%   |
| ICS Advent                       | 4         | 0.28%   |
| OPPO Electronics                 | 3         | 0.21%   |
| 3Com                             | 3         | 0.21%   |
| ULi Electronics                  | 2         | 0.14%   |
| TP-Link                          | 2         | 0.14%   |
| Qualcomm                         | 2         | 0.14%   |
| Motorola PCS                     | 2         | 0.14%   |
| MediaTek                         | 2         | 0.14%   |
| D-Link System                    | 2         | 0.14%   |
| Accton Technology                | 2         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.07%   |
| Yulong                           | 1         | 0.07%   |
| Trident Microsystems             | 1         | 0.07%   |
| T & A Mobile Phones              | 1         | 0.07%   |
| Spreadtrum Communications        | 1         | 0.07%   |
| Research In Motion               | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.07%   |
| NetGear                          | 1         | 0.07%   |
| Microchip Technology             | 1         | 0.07%   |
| LG Electronics                   | 1         | 0.07%   |
| Lab126                           | 1         | 0.07%   |
| Intersil                         | 1         | 0.07%   |
| Insyde Software                  | 1         | 0.07%   |
| Hewlett-Packard                  | 1         | 0.07%   |
| Hangzhou Silan Microelectronics  | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 469       | 32.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 164       | 11.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 49        | 3.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 42        | 2.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 25        | 1.74%   |
| Nvidia MCP61 Ethernet                                                  | 22        | 1.53%   |
| Intel 82577LM Gigabit Network Connection                               | 18        | 1.26%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 14        | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 14        | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 14        | 0.98%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 13        | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13        | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 11        | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 11        | 0.77%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 11        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 10        | 0.7%    |
| Intel Ethernet Connection I218-LM                                      | 10        | 0.7%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 10        | 0.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 10        | 0.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                           | 9         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 9         | 0.63%   |
| Intel 82579V Gigabit Network Connection                                | 9         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 9         | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 8         | 0.56%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                               | 8         | 0.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 8         | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 7         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 7         | 0.49%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 7         | 0.49%   |
| Intel Ethernet Controller I225-V                                       | 7         | 0.49%   |
| Intel Ethernet Connection I217-V                                       | 7         | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 7         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 6         | 0.42%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 6         | 0.42%   |
| Nvidia MCP51 Ethernet Controller                                       | 6         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1315      | 52.1%   |
| WiFi     | 1172      | 46.43%  |
| Modem    | 32        | 1.27%   |
| Unknown  | 5         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 908       | 58.77%  |
| Ethernet | 637       | 41.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 844       | 54.81%  |
| 1     | 573       | 37.21%  |
| 0     | 91        | 5.91%   |
| 3     | 27        | 1.75%   |
| 4     | 4         | 0.26%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1242      | 79.72%  |
| Yes  | 316       | 20.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 253       | 33.69%  |
| Realtek Semiconductor           | 83        | 11.05%  |
| Qualcomm Atheros Communications | 70        | 9.32%   |
| Broadcom                        | 56        | 7.46%   |
| Cambridge Silicon Radio         | 48        | 6.39%   |
| Lite-On Technology              | 33        | 4.39%   |
| Apple                           | 32        | 4.26%   |
| IMC Networks                    | 29        | 3.86%   |
| Foxconn / Hon Hai               | 27        | 3.6%    |
| Hewlett-Packard                 | 22        | 2.93%   |
| Dell                            | 21        | 2.8%    |
| Ralink                          | 15        | 2%      |
| Toshiba                         | 12        | 1.6%    |
| ASUSTek Computer                | 11        | 1.46%   |
| Alps Electric                   | 10        | 1.33%   |
| Marvell Semiconductor           | 5         | 0.67%   |
| MediaTek                        | 4         | 0.53%   |
| TP-Link                         | 3         | 0.4%    |
| Ralink Technology               | 2         | 0.27%   |
| Qcom                            | 2         | 0.27%   |
| Micro Star International        | 2         | 0.27%   |
| Logitech                        | 2         | 0.27%   |
| Askey Computer                  | 2         | 0.27%   |
| Syntek                          | 1         | 0.13%   |
| Smart Modular Technologies      | 1         | 0.13%   |
| Integrated System Solution      | 1         | 0.13%   |
| HTC (High Tech Computer)        | 1         | 0.13%   |
| Fujitsu                         | 1         | 0.13%   |
| Dynex                           | 1         | 0.13%   |
| Chicony Electronics             | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 108       | 14.32%  |
| Realtek Bluetooth Radio                                                             | 49        | 6.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 48        | 6.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 37        | 4.91%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 32        | 4.24%   |
| Intel Bluetooth Device                                                              | 27        | 3.58%   |
| Intel AX201 Bluetooth                                                               | 26        | 3.45%   |
| Intel AX200 Bluetooth                                                               | 16        | 2.12%   |
| Ralink RT3290 Bluetooth                                                             | 15        | 1.99%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 1.99%   |
| Apple Bluetooth Host Controller                                                     | 15        | 1.99%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 1.72%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 12        | 1.59%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 12        | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 11        | 1.46%   |
| Apple Bluetooth HCI                                                                 | 11        | 1.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 1.33%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 10        | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 9         | 1.19%   |
| Realtek RTL8723B Bluetooth                                                          | 8         | 1.06%   |
| Realtek 802.11ac WLAN Adapter                                                       | 8         | 1.06%   |
| IMC Networks Bluetooth Device                                                       | 8         | 1.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 0.93%   |
| Intel AX210 Bluetooth                                                               | 7         | 0.93%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 0.93%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 7         | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.8%    |
| Dell Wireless 365 Bluetooth                                                         | 6         | 0.8%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 6         | 0.8%    |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.66%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 0.66%   |
| IMC Networks Bluetooth module                                                       | 5         | 0.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 5         | 0.66%   |
| Intel AX211 Bluetooth                                                               | 4         | 0.53%   |
| Broadcom HP Portable Bumble Bee                                                     | 4         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 4         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1036      | 58.8%   |
| AMD                                          | 359       | 20.37%  |
| Nvidia                                       | 234       | 13.28%  |
| C-Media Electronics                          | 25        | 1.42%   |
| VIA Technologies                             | 14        | 0.79%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.68%   |
| Creative Labs                                | 10        | 0.57%   |
| Logitech                                     | 8         | 0.45%   |
| Texas Instruments                            | 6         | 0.34%   |
| GN Netcom                                    | 6         | 0.34%   |
| ASUSTek Computer                             | 6         | 0.34%   |
| XMOS                                         | 4         | 0.23%   |
| Plantronics                                  | 4         | 0.23%   |
| Razer USA                                    | 3         | 0.17%   |
| Generalplus Technology                       | 3         | 0.17%   |
| Creative Technology                          | 3         | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.11%   |
| ULi Electronics                              | 2         | 0.11%   |
| Realtek Semiconductor                        | 2         | 0.11%   |
| JMTek                                        | 2         | 0.11%   |
| Focusrite-Novation                           | 2         | 0.11%   |
| Zhaoxin                                      | 1         | 0.06%   |
| Sony                                         | 1         | 0.06%   |
| Setek Elektronik                             | 1         | 0.06%   |
| QinHeng Electronics                          | 1         | 0.06%   |
| Nordic Semiconductor ASA                     | 1         | 0.06%   |
| MosArt Semiconductor                         | 1         | 0.06%   |
| Microsoft                                    | 1         | 0.06%   |
| Micro Star International                     | 1         | 0.06%   |
| KORG                                         | 1         | 0.06%   |
| Hewlett-Packard                              | 1         | 0.06%   |
| Guillemot                                    | 1         | 0.06%   |
| ESI                                          | 1         | 0.06%   |
| Ensoniq                                      | 1         | 0.06%   |
| Elitegroup Computer Systems (ECS)            | 1         | 0.06%   |
| Elgato Systems                               | 1         | 0.06%   |
| EGO SYStems                                  | 1         | 0.06%   |
| Dell                                         | 1         | 0.06%   |
| Cirrus Logic                                 | 1         | 0.06%   |
| Asahi Kasei Microsystems                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 119       | 5.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 113       | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 89        | 4.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 78        | 3.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 77        | 3.7%    |
| AMD FCH Azalia Controller                                                                         | 76        | 3.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 71        | 3.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 70        | 3.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 64        | 3.08%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 58        | 2.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 50        | 2.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 45        | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 41        | 1.97%   |
| Intel 8 Series HD Audio Controller                                                                | 40        | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 39        | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 39        | 1.88%   |
| AMD Wrestler HDMI Audio                                                                           | 38        | 1.83%   |
| Nvidia High Definition Audio Controller                                                           | 36        | 1.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 33        | 1.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 32        | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 31        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 29        | 1.39%   |
| AMD High Definition Audio Controller                                                              | 28        | 1.35%   |
| Nvidia MCP61 High Definition Audio                                                                | 25        | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 25        | 1.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 17        | 0.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 17        | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 17        | 0.82%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 0.77%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 0.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 0.72%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 13        | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 13        | 0.63%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 13        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 230       | 20.46%  |
| Unknown                      | 212       | 18.86%  |
| SK hynix                     | 190       | 16.9%   |
| Kingston                     | 88        | 7.83%   |
| Micron Technology            | 87        | 7.74%   |
| Crucial                      | 42        | 3.74%   |
| Unknown (ABCD)               | 34        | 3.02%   |
| Corsair                      | 32        | 2.85%   |
| Nanya Technology             | 26        | 2.31%   |
| A-DATA Technology            | 26        | 2.31%   |
| G.Skill                      | 24        | 2.14%   |
| Elpida                       | 21        | 1.87%   |
| Unknown                      | 13        | 1.16%   |
| Ramaxel Technology           | 12        | 1.07%   |
| Smart                        | 11        | 0.98%   |
| Teikon                       | 6         | 0.53%   |
| Patriot                      | 6         | 0.53%   |
| Transcend                    | 5         | 0.44%   |
| Team                         | 5         | 0.44%   |
| PNY                          | 4         | 0.36%   |
| Qimonda                      | 3         | 0.27%   |
| ASint Technology             | 3         | 0.27%   |
| Apacer                       | 3         | 0.27%   |
| Unifosa                      | 2         | 0.18%   |
| Toshiba                      | 2         | 0.18%   |
| Timetec                      | 2         | 0.18%   |
| PUSKILL                      | 2         | 0.18%   |
| High Bridge                  | 2         | 0.18%   |
| GOODRAM                      | 2         | 0.18%   |
| fef5                         | 2         | 0.18%   |
| Avant                        | 2         | 0.18%   |
| Wilk                         | 1         | 0.09%   |
| Unknown (AB)                 | 1         | 0.09%   |
| Unknown (0xD306)             | 1         | 0.09%   |
| Unknown (0x4000000000000000) | 1         | 0.09%   |
| Unknown (07FB)               | 1         | 0.09%   |
| TakeMS                       | 1         | 0.09%   |
| Smart Brazil                 | 1         | 0.09%   |
| Silicon Power                | 1         | 0.09%   |
| Sesame                       | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.15%   |
| Unknown                                                          | 13        | 1.07%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 12        | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 11        | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 11        | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.82%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 10        | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.82%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 9         | 0.74%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 9         | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.66%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 7         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.58%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 6         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 6         | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DRAM                            | 6         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.41%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                    | 5         | 0.41%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 5         | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.41%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 5         | 0.41%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 5         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 4         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 4         | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 4         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 4         | 0.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 4         | 0.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 4         | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.33%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 4         | 0.33%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 4         | 0.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.33%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.33%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 433       | 43.87%  |
| DDR4    | 232       | 23.51%  |
| DDR2    | 119       | 12.06%  |
| LPDDR4  | 58        | 5.88%   |
| SDRAM   | 51        | 5.17%   |
| Unknown | 34        | 3.44%   |
| DDR     | 19        | 1.93%   |
| LPDDR3  | 16        | 1.62%   |
| DRAM    | 12        | 1.22%   |
| LPDDR5  | 9         | 0.91%   |
| DDR5    | 4         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 631       | 65.05%  |
| DIMM         | 289       | 29.79%  |
| Row Of Chips | 41        | 4.23%   |
| Unknown      | 8         | 0.82%   |
| Chip         | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 332       | 30.18%  |
| 2048  | 281       | 25.55%  |
| 8192  | 267       | 24.27%  |
| 1024  | 106       | 9.64%   |
| 16384 | 68        | 6.18%   |
| 512   | 21        | 1.91%   |
| 32768 | 14        | 1.27%   |
| 256   | 6         | 0.55%   |
| 3072  | 2         | 0.18%   |
| 128   | 2         | 0.18%   |
| 65536 | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 261       | 24.58%  |
| 1333    | 86        | 8.1%    |
| 3200    | 83        | 7.82%   |
| 2400    | 80        | 7.53%   |
| 2667    | 66        | 6.21%   |
| Unknown | 62        | 5.84%   |
| 667     | 58        | 5.46%   |
| 1334    | 52        | 4.9%    |
| 800     | 42        | 3.95%   |
| 2133    | 35        | 3.3%    |
| 1066    | 31        | 2.92%   |
| 1067    | 25        | 2.35%   |
| 533     | 24        | 2.26%   |
| 1867    | 17        | 1.6%    |
| 2048    | 16        | 1.51%   |
| 1866    | 14        | 1.32%   |
| 3266    | 11        | 1.04%   |
| 400     | 10        | 0.94%   |
| 4267    | 9         | 0.85%   |
| 6400    | 8         | 0.75%   |
| 3600    | 6         | 0.56%   |
| 3400    | 5         | 0.47%   |
| 975     | 5         | 0.47%   |
| 333     | 5         | 0.47%   |
| 4800    | 4         | 0.38%   |
| 4199    | 4         | 0.38%   |
| 3066    | 4         | 0.38%   |
| 49926   | 3         | 0.28%   |
| 3866    | 3         | 0.28%   |
| 266     | 3         | 0.28%   |
| 4266    | 2         | 0.19%   |
| 3933    | 2         | 0.19%   |
| 3733    | 2         | 0.19%   |
| 3000    | 2         | 0.19%   |
| 2933    | 2         | 0.19%   |
| 2733    | 2         | 0.19%   |
| 2666    | 2         | 0.19%   |
| 1800    | 2         | 0.19%   |
| 1639    | 2         | 0.19%   |
| 41632   | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 29.03%  |
| Brother Industries    | 7         | 22.58%  |
| Samsung Electronics   | 6         | 19.35%  |
| Canon                 | 4         | 12.9%   |
| Lexmark International | 2         | 6.45%   |
| STMicroelectronics    | 1         | 3.23%   |
| Seiko Epson           | 1         | 3.23%   |
| Dymo-CoStar           | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SCX-4200 series                 | 2         | 6.45%   |
| Brother DCP-7055W                       | 2         | 6.45%   |
| STMicroelectronics USB Printing Support | 1         | 3.23%   |
| Seiko Epson TM-T20X                     | 1         | 3.23%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 3.23%   |
| Samsung SCX-3400 Series                 | 1         | 3.23%   |
| Samsung ML-1640 Series Laser Printer    | 1         | 3.23%   |
| Samsung M2020 Series                    | 1         | 3.23%   |
| Lexmark International Z33 Printer       | 1         | 3.23%   |
| Lexmark International MS617dn           | 1         | 3.23%   |
| HP PSC 1500 series                      | 1         | 3.23%   |
| HP OfficeJet 4650 series                | 1         | 3.23%   |
| HP LaserJet P2015 series                | 1         | 3.23%   |
| HP LaserJet P1102                       | 1         | 3.23%   |
| HP LaserJet 1200                        | 1         | 3.23%   |
| HP DeskJet D2460                        | 1         | 3.23%   |
| HP DeskJet 3630 series                  | 1         | 3.23%   |
| HP Deskjet 3520 series                  | 1         | 3.23%   |
| HP Deskjet 1050 J410                    | 1         | 3.23%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo  | 1         | 3.23%   |
| Canon TS5100 series                     | 1         | 3.23%   |
| Canon PIXMA MP250                       | 1         | 3.23%   |
| Canon MF3110                            | 1         | 3.23%   |
| Canon LiDE 300                          | 1         | 3.23%   |
| Brother PTUSB Printing                  | 1         | 3.23%   |
| Brother PT-2450DX                       | 1         | 3.23%   |
| Brother Printer                         | 1         | 3.23%   |
| Brother HL-L2380DW                      | 1         | 3.23%   |
| Brother HL-2230 series                  | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 42.86%  |
| Canon           | 3         | 42.86%  |
| Seiko Epson     | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 14.29%  |
| HP scanjet 8270                                               | 1         | 14.29%  |
| HP ScanJet 2400c                                              | 1         | 14.29%  |
| HP HP4470C                                                    | 1         | 14.29%  |
| Canon CanoScan LiDE 500F                                      | 1         | 14.29%  |
| Canon CanoScan LiDE 220                                       | 1         | 14.29%  |
| Canon CanoScan LiDE 200                                       | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 220       | 25.55%  |
| Realtek Semiconductor                  | 73        | 8.48%   |
| Microdia                               | 59        | 6.85%   |
| IMC Networks                           | 58        | 6.74%   |
| Suyin                                  | 39        | 4.53%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 4.07%   |
| Sunplus Innovation Technology          | 34        | 3.95%   |
| Quanta                                 | 33        | 3.83%   |
| Bison Electronics                      | 33        | 3.83%   |
| Apple                                  | 33        | 3.83%   |
| Alcor Micro                            | 31        | 3.6%    |
| Silicon Motion                         | 25        | 2.9%    |
| Syntek                                 | 19        | 2.21%   |
| Lite-On Technology                     | 18        | 2.09%   |
| Logitech                               | 16        | 1.86%   |
| Acer                                   | 12        | 1.39%   |
| Ricoh                                  | 11        | 1.28%   |
| Lenovo                                 | 11        | 1.28%   |
| Luxvisions Innotech Limited            | 9         | 1.05%   |
| ALi                                    | 8         | 0.93%   |
| Microsoft                              | 7         | 0.81%   |
| GEMBIRD                                | 7         | 0.81%   |
| Z-Star Microelectronics                | 6         | 0.7%    |
| icSpring                               | 6         | 0.7%    |
| Importek                               | 5         | 0.58%   |
| Generalplus Technology                 | 5         | 0.58%   |
| Samsung Electronics                    | 4         | 0.46%   |
| Genesys Logic                          | 4         | 0.46%   |
| Y Media                                | 2         | 0.23%   |
| USB Camera CS                          | 2         | 0.23%   |
| SunplusIT                              | 2         | 0.23%   |
| Sunplus IT                             | 2         | 0.23%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.23%   |
| OmniVision Technologies                | 2         | 0.23%   |
| LG Electronics                         | 2         | 0.23%   |
| KYE Systems (Mouse Systems)            | 2         | 0.23%   |
| ARC International                      | 2         | 0.23%   |
| WCM_USB                                | 1         | 0.12%   |
| WaveRider Communications               | 1         | 0.12%   |
| Toshiba                                | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 20        | 2.31%   |
| Alcor Micro USB 2.0 PC cam                              | 16        | 1.85%   |
| Realtek Integrated_Webcam_HD                            | 15        | 1.73%   |
| Chicony HD WebCam                                       | 14        | 1.61%   |
| Realtek USB Camera                                      | 12        | 1.38%   |
| Chicony HP Truevision HD                                | 12        | 1.38%   |
| Chicony USB 2.0 Camera                                  | 11        | 1.27%   |
| Chicony EasyCamera                                      | 11        | 1.27%   |
| Sunplus HD WebCam                                       | 10        | 1.15%   |
| Apple Built-in iSight                                   | 10        | 1.15%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 9         | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                         | 9         | 1.04%   |
| Chicony HP TrueVision HD Camera                         | 9         | 1.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 9         | 1.04%   |
| Chicony HP Webcam                                       | 8         | 0.92%   |
| Chicony HP HD Webcam                                    | 8         | 0.92%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 8         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 8         | 0.92%   |
| Bison Integrated Camera                                 | 8         | 0.92%   |
| Microdia Integrated_Webcam_HD                           | 7         | 0.81%   |
| Microdia 1.3 MPixel Integrated Webcam                   | 7         | 0.81%   |
| IMC Networks USB 2.0 UVC VGA WebCam                     | 7         | 0.81%   |
| Chicony VGA Webcam                                      | 7         | 0.81%   |
| Apple FaceTime HD Camera                                | 7         | 0.81%   |
| Lite-On HP HD Camera                                    | 6         | 0.69%   |
| IMC Networks UVC VGA Webcam                             | 6         | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 6         | 0.69%   |
| icSpring camera                                         | 6         | 0.69%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]       | 6         | 0.69%   |
| Bison Lenovo EasyCamera                                 | 6         | 0.69%   |
| Suyin Acer CrystalEye Webcam                            | 5         | 0.58%   |
| Silicon Motion WebCam SC-0311139N                       | 5         | 0.58%   |
| Realtek Integrated Webcam HD                            | 5         | 0.58%   |
| Quanta HP HD Camera                                     | 5         | 0.58%   |
| Microdia Sonix USB 2.0 Camera                           | 5         | 0.58%   |
| Microdia Integrated Webcam                              | 5         | 0.58%   |
| Lenovo Integrated Webcam [R5U877]                       | 5         | 0.58%   |
| IMC Networks Integrated Webcam                          | 5         | 0.58%   |
| IMC Networks Integrated Camera                          | 5         | 0.58%   |
| Chicony Lenovo EasyCamera                               | 5         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 40        | 40%     |
| AuthenTec                  | 17        | 17%     |
| Upek                       | 12        | 12%     |
| Synaptics                  | 8         | 8%      |
| STMicroelectronics         | 8         | 8%      |
| Shenzhen Goodix Technology | 7         | 7%      |
| Samsung Electronics        | 3         | 3%      |
| LighTuning Technology      | 3         | 3%      |
| Elan Microelectronics      | 2         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 11        | 11%     |
| Validity Sensors VFS495 Fingerprint Reader                | 10        | 10%     |
| STMicroelectronics Fingerprint Reader                     | 8         | 8%      |
| AuthenTec AES2810                                         | 6         | 6%      |
| Validity Sensors VFS471 Fingerprint Reader                | 5         | 5%      |
| AuthenTec AES2501 Fingerprint Sensor                      | 5         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader               | 4         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor              | 4         | 4%      |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 4%      |
| Validity Sensors VFS491                                   | 3         | 3%      |
| Validity Sensors VFS451 Fingerprint Reader                | 3         | 3%      |
| AuthenTec AES1600                                         | 3         | 3%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 2         | 2%      |
| Validity Sensors VFS300 Fingerprint Reader                | 2         | 2%      |
| Validity Sensors Fingerprint scanner                      | 2         | 2%      |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 2%      |
| Shenzhen Goodix FingerPrint                               | 2         | 2%      |
| Samsung Fingerprint Device                                | 2         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 2%      |
| Elan ELAN:Fingerprint                                     | 2         | 2%      |
| AuthenTec AES1660 Fingerprint Sensor                      | 2         | 2%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 1%      |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1%      |
| Validity Sensors VFS101 Fingerprint Reader                | 1         | 1%      |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 1%      |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 1%      |
| Upek TCS5B Fingerprint sensor                             | 1         | 1%      |
| Synaptics WBDI                                            | 1         | 1%      |
| Synaptics UWP WBDI                                        | 1         | 1%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 1%      |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 1%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1%      |
| Shenzhen Goodix Fingerprint Reader                        | 1         | 1%      |
| Samsung Fingerprint Sensor Device - 730B                  | 1         | 1%      |
| LighTuning Fingerprint Reader                             | 1         | 1%      |
| AuthenTec Fingerprint Sensor                              | 1         | 1%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 30.23%  |
| Alcor Micro           | 13        | 30.23%  |
| O2 Micro              | 9         | 20.93%  |
| Lenovo                | 2         | 4.65%   |
| CHERRY                | 2         | 4.65%   |
| Upek                  | 1         | 2.33%   |
| Realtek Semiconductor | 1         | 2.33%   |
| OmniKey               | 1         | 2.33%   |
| Gemalto (was Gemplus) | 1         | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 12        | 27.91%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 13.95%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 13.95%  |
| Broadcom 5880                                                                | 5         | 11.63%  |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 6.98%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.65%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 4.65%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.33%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 2.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.33%   |
| Broadcom 58200                                                               | 1         | 2.33%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1174      | 75.69%  |
| 1     | 307       | 19.79%  |
| 2     | 59        | 3.8%    |
| 3     | 8         | 0.52%   |
| 4     | 2         | 0.13%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 119       | 26.62%  |
| Fingerprint reader       | 99        | 22.15%  |
| Net/wireless             | 58        | 12.98%  |
| Chipcard                 | 38        | 8.5%    |
| Bluetooth                | 24        | 5.37%   |
| Communication controller | 16        | 3.58%   |
| Camera                   | 16        | 3.58%   |
| Multimedia controller    | 15        | 3.36%   |
| Sound                    | 11        | 2.46%   |
| Net/ethernet             | 10        | 2.24%   |
| Modem                    | 10        | 2.24%   |
| Storage                  | 9         | 2.01%   |
| Unassigned class         | 6         | 1.34%   |
| Flash memory             | 5         | 1.12%   |
| Dvb card                 | 5         | 1.12%   |
| Network                  | 3         | 0.67%   |
| Card reader              | 2         | 0.45%   |
| Storage/raid             | 1         | 0.22%   |


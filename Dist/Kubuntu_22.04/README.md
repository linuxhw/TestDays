Kubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_22.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 1369

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | Notebook    | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [85cc9860f3](https://linux-hardware.org/?probe=85cc9860f3) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9028ba6c0f](https://linux-hardware.org/?probe=9028ba6c0f) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | XPS 9315                    | Notebook    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | Notebook    | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | Desktop     | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| HP            | 212B                        | Desktop     | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| HP            | 18E7                        | Desktop     | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | Notebook    | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | Desktop     | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| System76      | Galago Pro                  | Notebook    | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Supermicro    | C7H61                       | Desktop     | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HP            | Presario CQ62               | Notebook    | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Dell          | Latitude 5289               | Convertible | [eeb009e8f5](https://linux-hardware.org/?probe=eeb009e8f5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | Notebook    | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | Notebook    | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [35b286ba6b](https://linux-hardware.org/?probe=35b286ba6b) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [44eaa3f5c1](https://linux-hardware.org/?probe=44eaa3f5c1) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | Notebook    | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| Dell          | Latitude 7530               | Notebook    | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | Notebook    | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | 00V16R A00                  | All in one  | [cb94924faa](https://linux-hardware.org/?probe=cb94924faa) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| Supermicro    | C7H61                       | Desktop     | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | Desktop     | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| Dell          | 0RW199                      | Desktop     | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | Notebook    | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [7cce222ce2](https://linux-hardware.org/?probe=7cce222ce2) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | Notebook    | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8ba82ca424](https://linux-hardware.org/?probe=8ba82ca424) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [46e8dbcdc8](https://linux-hardware.org/?probe=46e8dbcdc8) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [fac3426827](https://linux-hardware.org/?probe=fac3426827) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| HP            | ProBook 6470b               | Notebook    | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| HP            | 86F0 11000                  | All in one  | [2fab63e976](https://linux-hardware.org/?probe=2fab63e976) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| ONN           | 100002435                   | Tablet      | [35d8a4ce58](https://linux-hardware.org/?probe=35d8a4ce58) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Google        | Lillipup                    | Notebook    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Dell          | Precision 7730              | Notebook    | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | Notebook    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | Notebook    | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| HP            | ProBook 6470b               | Notebook    | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3951ddfe72](https://linux-hardware.org/?probe=3951ddfe72) | Jan 23, 2023 |
| MSI           | MS-AEC21                    | All in one  | [e541cd3043](https://linux-hardware.org/?probe=e541cd3043) | Jan 23, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d2b797f3de](https://linux-hardware.org/?probe=d2b797f3de) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bfaffed5d2](https://linux-hardware.org/?probe=bfaffed5d2) | Jan 21, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a9d66d6af6](https://linux-hardware.org/?probe=a9d66d6af6) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0bc976587f](https://linux-hardware.org/?probe=0bc976587f) | Jan 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | Desktop     | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [6286dbdb0b](https://linux-hardware.org/?probe=6286dbdb0b) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | Notebook    | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| HP            | ProBook 6570b               | Notebook    | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [774322328a](https://linux-hardware.org/?probe=774322328a) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d94fa63122](https://linux-hardware.org/?probe=d94fa63122) | Jan 08, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [391d13c7ba](https://linux-hardware.org/?probe=391d13c7ba) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | Desktop     | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | Notebook    | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a5b2453630](https://linux-hardware.org/?probe=a5b2453630) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| Dell          | 0PTTT9 A00                  | Desktop     | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | Notebook    | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | 8399                        | Desktop     | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| HP            | Beats 15                    | Notebook    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Acer          | Aspire A517-53              | Notebook    | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | Notebook    | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| SGIN          | laptop                      | Notebook    | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| HP            | Sona                        | Notebook    | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | Notebook    | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [3d563943d4](https://linux-hardware.org/?probe=3d563943d4) | Dec 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Dell          | Precision 5540              | Notebook    | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1cbc80c6fb](https://linux-hardware.org/?probe=1cbc80c6fb) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | NOK                         | Desktop     | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8745419f51](https://linux-hardware.org/?probe=8745419f51) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [55e56516e5](https://linux-hardware.org/?probe=55e56516e5) | Dec 06, 2022 |
| HP            | Beats 15                    | Notebook    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HP            | EliteBook x360 1040 G5      | Convertible | [02c80899f7](https://linux-hardware.org/?probe=02c80899f7) | Dec 05, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [5b17c3205f](https://linux-hardware.org/?probe=5b17c3205f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | Notebook    | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| Haier         | A1420EM                     | Notebook    | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fc681f2f42](https://linux-hardware.org/?probe=fc681f2f42) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [e3c2051d8f](https://linux-hardware.org/?probe=e3c2051d8f) | Nov 26, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [d876db7f78](https://linux-hardware.org/?probe=d876db7f78) | Nov 22, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | Notebook    | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | Desktop     | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [12fe5843d1](https://linux-hardware.org/?probe=12fe5843d1) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| Samsung       | 950QED                      | Convertible | [c68fd01b4c](https://linux-hardware.org/?probe=c68fd01b4c) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | Notebook    | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | Notebook    | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | Notebook    | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [16b7880c43](https://linux-hardware.org/?probe=16b7880c43) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [317efeba98](https://linux-hardware.org/?probe=317efeba98) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| HP            | 844C                        | Desktop     | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | Notebook    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Gigabyte      | MX33-BS0-00 00010001        | Server      | [abfee9c5f7](https://linux-hardware.org/?probe=abfee9c5f7) | Oct 18, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [b106ebaef6](https://linux-hardware.org/?probe=b106ebaef6) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| Dell          | Precision 3570              | Notebook    | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [159150cc56](https://linux-hardware.org/?probe=159150cc56) | Oct 17, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| JWIPC         | A320I S1                    | Desktop     | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | Notebook    | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | Notebook    | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [eb5e8725ae](https://linux-hardware.org/?probe=eb5e8725ae) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [b9f2861719](https://linux-hardware.org/?probe=b9f2861719) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| AZW           | SER                         | Mini pc     | [9e9ee5be74](https://linux-hardware.org/?probe=9e9ee5be74) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [2a27e3cb58](https://linux-hardware.org/?probe=2a27e3cb58) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [f52114ac39](https://linux-hardware.org/?probe=f52114ac39) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Google        | Blooglet                    | Notebook    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version              | Computers | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 67        | 6.1%    |
| 5.15.0-52-generic    | 66        | 6.01%   |
| 5.15.0-48-generic    | 41        | 3.73%   |
| 5.15.0-58-generic    | 40        | 3.64%   |
| 5.15.0-43-generic    | 37        | 3.37%   |
| 5.15.0-47-generic    | 36        | 3.28%   |
| 5.15.0-53-generic    | 33        | 3%      |
| 5.15.0-46-generic    | 33        | 3%      |
| 5.15.0-60-generic    | 32        | 2.91%   |
| 5.15.0-41-generic    | 29        | 2.64%   |
| 5.19.0-35-generic    | 28        | 2.55%   |
| 5.15.0-25-generic    | 27        | 2.46%   |
| 5.15.0-40-generic    | 26        | 2.37%   |
| 5.15.0-67-generic    | 25        | 2.27%   |
| 6.2.0-26-generic     | 24        | 2.18%   |
| 5.19.0-46-generic    | 24        | 2.18%   |
| 5.15.0-27-generic    | 24        | 2.18%   |
| 5.19.0-38-generic    | 22        | 2%      |
| 5.15.0-50-generic    | 22        | 2%      |
| 5.19.0-41-generic    | 19        | 1.73%   |
| 5.19.0-32-generic    | 19        | 1.73%   |
| 5.15.0-33-generic    | 18        | 1.64%   |
| 5.15.0-78-generic    | 15        | 1.36%   |
| 5.15.0-71-generic    | 15        | 1.36%   |
| 5.15.0-69-generic    | 15        | 1.36%   |
| 5.19.0-42-generic    | 14        | 1.27%   |
| 5.15.0-57-generic    | 14        | 1.27%   |
| 5.19.0-43-generic    | 12        | 1.09%   |
| 5.15.0-73-generic    | 12        | 1.09%   |
| 5.15.0-72-generic    | 12        | 1.09%   |
| 5.15.0-75-generic    | 11        | 1%      |
| 5.15.0-37-generic    | 10        | 0.91%   |
| 5.15.0-30-generic    | 10        | 0.91%   |
| 5.15.0-76-generic    | 9         | 0.82%   |
| 5.15.0-39-generic    | 9         | 0.82%   |
| 5.19.0-50-generic    | 8         | 0.73%   |
| 5.15.0-43-lowlatency | 8         | 0.73%   |
| 5.19.0-40-generic    | 7         | 0.64%   |
| 5.15.0-82-generic    | 7         | 0.64%   |
| 5.15.0-48-lowlatency | 7         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 741       | 72.08%  |
| 5.19.0  | 166       | 16.15%  |
| 6.2.0   | 34        | 3.31%   |
| 5.17.0  | 16        | 1.56%   |
| 6.0.0   | 6         | 0.58%   |
| 5.13.0  | 6         | 0.58%   |
| 6.1.0   | 5         | 0.49%   |
| 6.4.10  | 2         | 0.19%   |
| 6.3.6   | 2         | 0.19%   |
| 6.2.2   | 2         | 0.19%   |
| 6.1.5   | 2         | 0.19%   |
| 6.0.7   | 2         | 0.19%   |
| 6.0.1   | 2         | 0.19%   |
| 5.19.5  | 2         | 0.19%   |
| 5.18.4  | 2         | 0.19%   |
| 5.18.10 | 2         | 0.19%   |
| 6.4.8   | 1         | 0.1%    |
| 6.4.0   | 1         | 0.1%    |
| 6.3.9   | 1         | 0.1%    |
| 6.3.8   | 1         | 0.1%    |
| 6.3.4   | 1         | 0.1%    |
| 6.3.1   | 1         | 0.1%    |
| 6.3.0   | 1         | 0.1%    |
| 6.2.8   | 1         | 0.1%    |
| 6.1.9   | 1         | 0.1%    |
| 6.1.12  | 1         | 0.1%    |
| 6.1.1   | 1         | 0.1%    |
| 6.0.9   | 1         | 0.1%    |
| 6.0.8   | 1         | 0.1%    |
| 6.0.6   | 1         | 0.1%    |
| 5.4.0   | 1         | 0.1%    |
| 5.19.2  | 1         | 0.1%    |
| 5.19.12 | 1         | 0.1%    |
| 5.19.11 | 1         | 0.1%    |
| 5.18.6  | 1         | 0.1%    |
| 5.18.19 | 1         | 0.1%    |
| 5.18.15 | 1         | 0.1%    |
| 5.18.12 | 1         | 0.1%    |
| 5.17.6  | 1         | 0.1%    |
| 5.17.5  | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 743       | 72.42%  |
| 5.19    | 171       | 16.67%  |
| 6.2     | 37        | 3.61%   |
| 5.17    | 21        | 2.05%   |
| 6.0     | 12        | 1.17%   |
| 6.1     | 10        | 0.97%   |
| 5.18    | 8         | 0.78%   |
| 6.3     | 7         | 0.68%   |
| 5.13    | 6         | 0.58%   |
| 6.4     | 4         | 0.39%   |
| 5.16    | 3         | 0.29%   |
| 5.4     | 1         | 0.1%    |
| 5.14    | 1         | 0.1%    |
| 5.11    | 1         | 0.1%    |
| 5.10    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 998       | 99.8%   |
| riscv64 | 1         | 0.1%    |
| aarch64 | 1         | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 985       | 98.3%   |
| GNOME      | 6         | 0.6%    |
| KDE        | 4         | 0.4%    |
| XFCE       | 1         | 0.1%    |
| X-Cinnamon | 1         | 0.1%    |
| MATE       | 1         | 0.1%    |
| i3         | 1         | 0.1%    |
| GNUstep    | 1         | 0.1%    |
| Cinnamon   | 1         | 0.1%    |
| Budgie     | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 957       | 95.32%  |
| Wayland | 30        | 2.99%   |
| Tty     | 16        | 1.59%   |
| Web     | 1         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 738       | 73.36%  |
| Unknown | 190       | 18.89%  |
| GDM3    | 50        | 4.97%   |
| LightDM | 25        | 2.49%   |
| SLiM    | 1         | 0.1%    |
| LXDM    | 1         | 0.1%    |
| GDM     | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang                 | Computers | Percent |
|----------------------|-----------|---------|
| en_US                | 486       | 48.41%  |
| de_DE                | 83        | 8.27%   |
| it_IT                | 51        | 5.08%   |
| ru_RU                | 48        | 4.78%   |
| fr_FR                | 48        | 4.78%   |
| en_GB                | 46        | 4.58%   |
| pt_BR                | 24        | 2.39%   |
| es_ES                | 22        | 2.19%   |
| en_AU                | 22        | 2.19%   |
| pl_PL                | 20        | 1.99%   |
| en_IN                | 19        | 1.89%   |
| en_CA                | 14        | 1.39%   |
| cs_CZ                | 8         | 0.8%    |
| es_AR                | 7         | 0.7%    |
| en_ZA                | 7         | 0.7%    |
| C                    | 7         | 0.7%    |
| hu_HU                | 6         | 0.6%    |
| en_PH                | 6         | 0.6%    |
| en_NZ                | 6         | 0.6%    |
| zh_CN                | 5         | 0.5%    |
| tr_TR                | 5         | 0.5%    |
| en_SG                | 5         | 0.5%    |
| nl_NL                | 4         | 0.4%    |
| fi_FI                | 4         | 0.4%    |
| es_CO                | 3         | 0.3%    |
| el_GR                | 3         | 0.3%    |
| de_CH                | 3         | 0.3%    |
| Default              | 3         | 0.3%    |
| sl_SI                | 2         | 0.2%    |
| pt_PT                | 2         | 0.2%    |
| nl_BE                | 2         | 0.2%    |
| fr_CH                | 2         | 0.2%    |
| fr_BE                | 2         | 0.2%    |
| es_VE                | 2         | 0.2%    |
| es_MX                | 2         | 0.2%    |
| es_CL                | 2         | 0.2%    |
| en_DE                | 2         | 0.2%    |
| de_AT                | 2         | 0.2%    |
| da_DK                | 2         | 0.2%    |
| الافتراضيّ | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 544       | 54.02%  |
| BIOS | 463       | 45.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 879       | 87.03%  |
| Tmpfs   | 43        | 4.26%   |
| Btrfs   | 41        | 4.06%   |
| Overlay | 36        | 3.56%   |
| Xfs     | 7         | 0.69%   |
| Zfs     | 2         | 0.2%    |
| Ext3    | 1         | 0.1%    |
| Ext2    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 674       | 66.8%   |
| Unknown | 263       | 26.07%  |
| MBR     | 72        | 7.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 903       | 89.76%  |
| Yes       | 103       | 10.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 622       | 62.01%  |
| Yes       | 381       | 37.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 169       | 16.9%   |
| ASUSTek Computer    | 159       | 15.9%   |
| Hewlett-Packard     | 131       | 13.1%   |
| Dell                | 126       | 12.6%   |
| Gigabyte Technology | 74        | 7.4%    |
| MSI                 | 73        | 7.3%    |
| Acer                | 48        | 4.8%    |
| ASRock              | 33        | 3.3%    |
| Apple               | 20        | 2%      |
| HUAWEI              | 15        | 1.5%    |
| Samsung Electronics | 12        | 1.2%    |
| Intel               | 8         | 0.8%    |
| Fujitsu             | 8         | 0.8%    |
| Toshiba             | 6         | 0.6%    |
| Supermicro          | 6         | 0.6%    |
| Google              | 6         | 0.6%    |
| Alienware           | 6         | 0.6%    |
| Notebook            | 5         | 0.5%    |
| AZW                 | 5         | 0.5%    |
| Unknown             | 5         | 0.5%    |
| TUXEDO              | 4         | 0.4%    |
| Timi                | 4         | 0.4%    |
| Sony                | 4         | 0.4%    |
| Microsoft           | 4         | 0.4%    |
| Biostar             | 4         | 0.4%    |
| System76            | 3         | 0.3%    |
| Framework           | 3         | 0.3%    |
| Shuttle             | 2         | 0.2%    |
| Schenker            | 2         | 0.2%    |
| Razer               | 2         | 0.2%    |
| Positivo            | 2         | 0.2%    |
| Panasonic           | 2         | 0.2%    |
| Medion              | 2         | 0.2%    |
| LG Electronics      | 2         | 0.2%    |
| HONOR               | 2         | 0.2%    |
| Haier               | 2         | 0.2%    |
| GPU Company         | 2         | 0.2%    |
| Carbon Systems      | 2         | 0.2%    |
| ZOTAC               | 1         | 0.1%    |
| VALE                | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 14        | 1.4%    |
| Unknown                                | 9         | 0.9%    |
| HUAWEI HVY-WXX9                        | 5         | 0.5%    |
| ASUS ROG STRIX B550-F GAMING           | 5         | 0.5%    |
| MSI MS-7B79                            | 4         | 0.4%    |
| HP 255 G8 Notebook PC                  | 4         | 0.4%    |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 3         | 0.3%    |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 3         | 0.3%    |
| HP ProBook 6470b                       | 3         | 0.3%    |
| HP ProBook 440 G8 Notebook PC          | 3         | 0.3%    |
| HP Pavilion g6                         | 3         | 0.3%    |
| HP OMEN Laptop 15-en0xxx               | 3         | 0.3%    |
| HP Laptop 15-ef2xxx                    | 3         | 0.3%    |
| HP EliteBook 845 G7 Notebook PC        | 3         | 0.3%    |
| Gigabyte B450M DS3H                    | 3         | 0.3%    |
| Framework Laptop (12th Gen Intel Core) | 3         | 0.3%    |
| Dell XPS 15 9560                       | 3         | 0.3%    |
| Dell OptiPlex 7010                     | 3         | 0.3%    |
| Dell Latitude 5420                     | 3         | 0.3%    |
| Dell Latitude 3420                     | 3         | 0.3%    |
| Acer Aspire A515-45                    | 3         | 0.3%    |
| Timi TM1701                            | 2         | 0.2%    |
| Supermicro SKAGIT09                    | 2         | 0.2%    |
| MSI MS-7C95                            | 2         | 0.2%    |
| MSI MS-7C56                            | 2         | 0.2%    |
| MSI MS-7B86                            | 2         | 0.2%    |
| MSI MS-7B84                            | 2         | 0.2%    |
| MSI MS-7A40                            | 2         | 0.2%    |
| MSI Modern 15 A5M                      | 2         | 0.2%    |
| Lenovo Z50-75 80EC                     | 2         | 0.2%    |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.2%    |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 2         | 0.2%    |
| Lenovo IdeaPad 3 15ADA05 81W1          | 2         | 0.2%    |
| HUAWEI CREM-WXX9                       | 2         | 0.2%    |
| HP ZBook 15 G6                         | 2         | 0.2%    |
| HP x2 Detachable 10-p0XX               | 2         | 0.2%    |
| HP ProBook 6570b                       | 2         | 0.2%    |
| HP Pavilion Laptop 15-eh1xxx           | 2         | 0.2%    |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 2         | 0.2%    |
| HP Pavilion dv6                        | 2         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 70        | 7%      |
| Lenovo IdeaPad     | 36        | 3.6%    |
| Dell Latitude      | 35        | 3.5%    |
| Acer Aspire        | 27        | 2.7%    |
| Dell Inspiron      | 26        | 2.6%    |
| ASUS ROG           | 24        | 2.4%    |
| HP Pavilion        | 20        | 2%      |
| HP ProBook         | 19        | 1.9%    |
| Dell XPS           | 19        | 1.9%    |
| ASUS PRIME         | 19        | 1.9%    |
| HP EliteBook       | 16        | 1.6%    |
| Dell Precision     | 15        | 1.5%    |
| HP Laptop          | 14        | 1.4%    |
| Dell OptiPlex      | 14        | 1.4%    |
| ASUS VivoBook      | 14        | 1.4%    |
| ASUS All           | 14        | 1.4%    |
| Lenovo ThinkCentre | 13        | 1.3%    |
| ASUS TUF           | 13        | 1.3%    |
| Lenovo Legion      | 10        | 1%      |
| Lenovo Yoga        | 9         | 0.9%    |
| Unknown            | 9         | 0.9%    |
| Lenovo ThinkBook   | 8         | 0.8%    |
| HP ENVY            | 8         | 0.8%    |
| Acer Nitro         | 8         | 0.8%    |
| Dell Vostro        | 7         | 0.7%    |
| Gigabyte X570      | 6         | 0.6%    |
| ASUS ASUS          | 6         | 0.6%    |
| Toshiba Satellite  | 5         | 0.5%    |
| HUAWEI HVY-WXX9    | 5         | 0.5%    |
| HP ZBook           | 5         | 0.5%    |
| HP OMEN            | 5         | 0.5%    |
| HP 255             | 5         | 0.5%    |
| MSI MS-7B79        | 4         | 0.4%    |
| Microsoft Surface  | 4         | 0.4%    |
| Lenovo IdeaCentre  | 4         | 0.4%    |
| HP Spectre         | 4         | 0.4%    |
| HP ProDesk         | 4         | 0.4%    |
| Gigabyte B450      | 4         | 0.4%    |
| Fujitsu LIFEBOOK   | 4         | 0.4%    |
| Fujitsu ESPRIMO    | 4         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 168       | 16.8%   |
| 2020    | 136       | 13.6%   |
| 2019    | 89        | 8.9%    |
| 2022    | 86        | 8.6%    |
| 2018    | 85        | 8.5%    |
| 2012    | 69        | 6.9%    |
| 2017    | 58        | 5.8%    |
| 2014    | 58        | 5.8%    |
| 2013    | 51        | 5.1%    |
| 2016    | 49        | 4.9%    |
| 2015    | 41        | 4.1%    |
| 2011    | 39        | 3.9%    |
| 2010    | 25        | 2.5%    |
| 2008    | 13        | 1.3%    |
| 2023    | 12        | 1.2%    |
| 2009    | 11        | 1.1%    |
| 2007    | 9         | 0.9%    |
| Unknown | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 562       | 56.2%   |
| Desktop        | 358       | 35.8%   |
| Convertible    | 37        | 3.7%    |
| Mini pc        | 17        | 1.7%    |
| All in one     | 12        | 1.2%    |
| Tablet         | 8         | 0.8%    |
| Server         | 4         | 0.4%    |
| Stick pc       | 1         | 0.1%    |
| System on chip | 1         | 0.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 900       | 89.64%  |
| Enabled  | 104       | 10.36%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 992       | 99.2%   |
| Yes  | 8         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 276       | 27.38%  |
| 4.01-8.0        | 211       | 20.93%  |
| 8.01-16.0       | 181       | 17.96%  |
| 32.01-64.0      | 161       | 15.97%  |
| 3.01-4.0        | 83        | 8.23%   |
| 64.01-256.0     | 55        | 5.46%   |
| 24.01-32.0      | 29        | 2.88%   |
| 1.01-2.0        | 6         | 0.6%    |
| 2.01-3.0        | 4         | 0.4%    |
| More than 256.0 | 2         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 271       | 25.66%  |
| 4.01-8.0   | 263       | 24.91%  |
| 3.01-4.0   | 213       | 20.17%  |
| 1.01-2.0   | 207       | 19.6%   |
| 8.01-16.0  | 73        | 6.91%   |
| 16.01-24.0 | 14        | 1.33%   |
| 0.51-1.0   | 7         | 0.66%   |
| 32.01-64.0 | 3         | 0.28%   |
| 24.01-32.0 | 3         | 0.28%   |
| 0.01-0.5   | 2         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 534       | 52.87%  |
| 2      | 285       | 28.22%  |
| 3      | 95        | 9.41%   |
| 4      | 42        | 4.16%   |
| 5      | 24        | 2.38%   |
| 6      | 14        | 1.39%   |
| 7      | 9         | 0.89%   |
| 9      | 2         | 0.2%    |
| 8      | 2         | 0.2%    |
| 0      | 2         | 0.2%    |
| 11     | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 738       | 73.58%  |
| Yes       | 265       | 26.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 816       | 81.52%  |
| No        | 185       | 18.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 821       | 81.94%  |
| No        | 181       | 18.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 715       | 70.93%  |
| No        | 293       | 29.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 220       | 21.96%  |
| Germany      | 108       | 10.78%  |
| Italy        | 68        | 6.79%   |
| France       | 61        | 6.09%   |
| Russia       | 57        | 5.69%   |
| UK           | 43        | 4.29%   |
| Brazil       | 36        | 3.59%   |
| Poland       | 32        | 3.19%   |
| Spain        | 28        | 2.79%   |
| Canada       | 21        | 2.1%    |
| India        | 20        | 2%      |
| Australia    | 20        | 2%      |
| Netherlands  | 19        | 1.9%    |
| Switzerland  | 15        | 1.5%    |
| Czechia      | 13        | 1.3%    |
| Hungary      | 11        | 1.1%    |
| Argentina    | 11        | 1.1%    |
| Finland      | 10        | 1%      |
| Turkey       | 9         | 0.9%    |
| Slovenia     | 9         | 0.9%    |
| Indonesia    | 9         | 0.9%    |
| Portugal     | 8         | 0.8%    |
| Mexico       | 8         | 0.8%    |
| Bulgaria     | 8         | 0.8%    |
| Belgium      | 8         | 0.8%    |
| Sweden       | 7         | 0.7%    |
| South Africa | 7         | 0.7%    |
| Philippines  | 7         | 0.7%    |
| New Zealand  | 7         | 0.7%    |
| Thailand     | 6         | 0.6%    |
| Serbia       | 6         | 0.6%    |
| Greece       | 6         | 0.6%    |
| China        | 6         | 0.6%    |
| Singapore    | 5         | 0.5%    |
| Denmark      | 5         | 0.5%    |
| Austria      | 5         | 0.5%    |
| Romania      | 4         | 0.4%    |
| Norway       | 4         | 0.4%    |
| Estonia      | 4         | 0.4%    |
| Colombia     | 4         | 0.4%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 19        | 1.83%   |
| Milan             | 15        | 1.45%   |
| Berlin            | 14        | 1.35%   |
| Paris             | 9         | 0.87%   |
| Warsaw            | 7         | 0.67%   |
| Prague            | 7         | 0.67%   |
| Munich            | 7         | 0.67%   |
| Montreal          | 7         | 0.67%   |
| Castro Valley     | 7         | 0.67%   |
| St Petersburg     | 6         | 0.58%   |
| Sao Paulo         | 6         | 0.58%   |
| Madrid            | 6         | 0.58%   |
| Hamburg           | 6         | 0.58%   |
| Bengaluru         | 6         | 0.58%   |
| Amsterdam         | 6         | 0.58%   |
| Wroclaw           | 5         | 0.48%   |
| Vladivostok       | 5         | 0.48%   |
| Sydney            | 5         | 0.48%   |
| Singapore         | 5         | 0.48%   |
| Rio de Janeiro    | 5         | 0.48%   |
| New York          | 5         | 0.48%   |
| London            | 5         | 0.48%   |
| Houston           | 5         | 0.48%   |
| Dallas            | 5         | 0.48%   |
| Belgrade          | 5         | 0.48%   |
| Auckland          | 5         | 0.48%   |
| Zurich            | 4         | 0.39%   |
| Washington        | 4         | 0.39%   |
| Vienna            | 4         | 0.39%   |
| Turin             | 4         | 0.39%   |
| Melbourne         | 4         | 0.39%   |
| Krakow            | 4         | 0.39%   |
| Johannesburg      | 4         | 0.39%   |
| Jakarta           | 4         | 0.39%   |
| Jacksonville      | 4         | 0.39%   |
| Frankfurt am Main | 4         | 0.39%   |
| Cologne           | 4         | 0.39%   |
| Budapest          | 4         | 0.39%   |
| Vilnius           | 3         | 0.29%   |
| Varna             | 3         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 263       | 401    | 16.76%  |
| WDC                         | 208       | 287    | 13.26%  |
| Seagate                     | 170       | 280    | 10.83%  |
| Kingston                    | 103       | 120    | 6.56%   |
| Sandisk                     | 97        | 126    | 6.18%   |
| Toshiba                     | 89        | 115    | 5.67%   |
| Crucial                     | 57        | 66     | 3.63%   |
| Unknown                     | 52        | 68     | 3.31%   |
| SK hynix                    | 49        | 58     | 3.12%   |
| Intel                       | 43        | 52     | 2.74%   |
| Hitachi                     | 37        | 45     | 2.36%   |
| Micron Technology           | 36        | 39     | 2.29%   |
| A-DATA Technology           | 26        | 28     | 1.66%   |
| KIOXIA                      | 24        | 26     | 1.53%   |
| HGST                        | 23        | 28     | 1.47%   |
| China                       | 20        | 24     | 1.27%   |
| Phison                      | 15        | 15     | 0.96%   |
| PNY                         | 13        | 21     | 0.83%   |
| Patriot                     | 13        | 16     | 0.83%   |
| Apple                       | 13        | 14     | 0.83%   |
| SPCC                        | 12        | 12     | 0.76%   |
| Phison Electronics          | 11        | 11     | 0.7%    |
| Unknown                     | 9         | 9      | 0.57%   |
| Silicon Motion              | 8         | 8      | 0.51%   |
| Micron/Crucial Technology   | 8         | 11     | 0.51%   |
| Kingston Technology Company | 7         | 8      | 0.45%   |
| Maxtor                      | 6         | 7      | 0.38%   |
| LITEON                      | 6         | 6      | 0.38%   |
| SSSTC                       | 5         | 5      | 0.32%   |
| Realtek Semiconductor       | 5         | 5      | 0.32%   |
| OCZ                         | 5         | 5      | 0.32%   |
| Lexar                       | 5         | 5      | 0.32%   |
| JMicron Technology          | 5         | 5      | 0.32%   |
| Intenso                     | 5         | 8      | 0.32%   |
| Verbatim                    | 4         | 4      | 0.25%   |
| Team                        | 4         | 4      | 0.25%   |
| SABRENT                     | 4         | 6      | 0.25%   |
| Netac                       | 4         | 4      | 0.25%   |
| GOODRAM                     | 4         | 4      | 0.25%   |
| Emtec                       | 4         | 4      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 19        | 1.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 16        | 0.92%   |
| Kingston SA400S37480G 480GB SSD                       | 16        | 0.92%   |
| Samsung SSD 860 EVO 500GB                             | 14        | 0.8%    |
| Samsung SSD 850 EVO 500GB                             | 12        | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB                        | 9         | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB                        | 9         | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB                          | 9         | 0.52%   |
| Samsung SSD 850 EVO 250GB                             | 9         | 0.52%   |
| Unknown                                               | 9         | 0.52%   |
| Unknown MMC Card  64GB                                | 8         | 0.46%   |
| Toshiba MQ01ABD100 1TB                                | 8         | 0.46%   |
| Toshiba DT01ACA100 1TB                                | 8         | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB                        | 8         | 0.46%   |
| Seagate Expansion 2TB                                 | 8         | 0.46%   |
| SanDisk NVMe SSD Drive 1TB                            | 8         | 0.46%   |
| Samsung SSD 980 PRO 1TB                               | 8         | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 8         | 0.46%   |
| Crucial CT240BX500SSD1 240GB                          | 8         | 0.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 7         | 0.4%    |
| Samsung SSD 860 EVO 1TB                               | 7         | 0.4%    |
| Kingston SA2000M81000G 1TB                            | 7         | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 6         | 0.34%   |
| Unknown MMC Card  32GB                                | 6         | 0.34%   |
| Unknown MMC Card  128GB                               | 6         | 0.34%   |
| Toshiba MQ04ABF100 1TB                                | 6         | 0.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 6         | 0.34%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 6         | 0.34%   |
| SanDisk NVMe SSD Drive 500GB                          | 6         | 0.34%   |
| Samsung SSD 980 1TB                                   | 6         | 0.34%   |
| Samsung SSD 970 EVO Plus 2TB                          | 6         | 0.34%   |
| Samsung SSD 970 EVO Plus 250GB                        | 6         | 0.34%   |
| Samsung SSD 870 EVO 1TB                               | 6         | 0.34%   |
| Samsung SSD 860 QVO 1TB                               | 6         | 0.34%   |
| Crucial CT500MX500SSD1 500GB                          | 6         | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                           | 6         | 0.34%   |
| Crucial CT1000BX500SSD1 1TB                           | 6         | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 5         | 0.29%   |
| Toshiba HDWD110 1TB                                   | 5         | 0.29%   |
| Seagate ST3500418AS 500GB                             | 5         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 162       | 264    | 34.91%  |
| WDC                 | 142       | 189    | 30.6%   |
| Toshiba             | 56        | 71     | 12.07%  |
| Hitachi             | 37        | 45     | 7.97%   |
| HGST                | 23        | 28     | 4.96%   |
| Samsung Electronics | 18        | 26     | 3.88%   |
| Maxtor              | 5         | 6      | 1.08%   |
| SABRENT             | 4         | 6      | 0.86%   |
| Apple               | 4         | 4      | 0.86%   |
| Unknown             | 3         | 3      | 0.65%   |
| USB3.0              | 2         | 2      | 0.43%   |
| SAGE                | 1         | 1      | 0.22%   |
| KESU                | 1         | 1      | 0.22%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| IET                 | 1         | 1      | 0.22%   |
| HPE                 | 1         | 6      | 0.22%   |
| HGST HTS            | 1         | 1      | 0.22%   |
| External            | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 130       | 193    | 24.81%  |
| Kingston            | 68        | 77     | 12.98%  |
| SanDisk             | 48        | 57     | 9.16%   |
| Crucial             | 45        | 52     | 8.59%   |
| WDC                 | 31        | 47     | 5.92%   |
| A-DATA Technology   | 21        | 22     | 4.01%   |
| China               | 19        | 23     | 3.63%   |
| Patriot             | 13        | 16     | 2.48%   |
| PNY                 | 11        | 19     | 2.1%    |
| Intel               | 11        | 15     | 2.1%    |
| SPCC                | 9         | 9      | 1.72%   |
| Micron Technology   | 9         | 9      | 1.72%   |
| Toshiba             | 7         | 10     | 1.34%   |
| LITEON              | 6         | 6      | 1.15%   |
| OCZ                 | 5         | 5      | 0.95%   |
| Apple               | 5         | 5      | 0.95%   |
| Verbatim            | 4         | 4      | 0.76%   |
| Lexar               | 4         | 4      | 0.76%   |
| Intenso             | 4         | 5      | 0.76%   |
| GOODRAM             | 4         | 4      | 0.76%   |
| Team                | 3         | 3      | 0.57%   |
| SK hynix            | 3         | 3      | 0.57%   |
| Plextor             | 3         | 3      | 0.57%   |
| Mushkin             | 3         | 4      | 0.57%   |
| LITEONIT            | 3         | 3      | 0.57%   |
| Hewlett-Packard     | 3         | 3      | 0.57%   |
| Emtec               | 3         | 3      | 0.57%   |
| Transcend           | 2         | 2      | 0.38%   |
| Smart               | 2         | 2      | 0.38%   |
| Netac               | 2         | 2      | 0.38%   |
| KODAK               | 2         | 2      | 0.38%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.38%   |
| JMicron Technology  | 2         | 2      | 0.38%   |
| Apacer              | 2         | 2      | 0.38%   |
| ADATA SU            | 2         | 2      | 0.38%   |
| Unknown             | 2         | 2      | 0.38%   |
| VISIPRO             | 1         | 2      | 0.19%   |
| ValueTech           | 1         | 1      | 0.19%   |
| tecmiyo             | 1         | 3      | 0.19%   |
| T-FORCE             | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 503       | 662    | 35.88%  |
| SSD     | 446       | 658    | 31.81%  |
| HDD     | 378       | 657    | 26.96%  |
| MMC     | 51        | 61     | 3.64%   |
| Unknown | 24        | 34     | 1.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 619       | 1246   | 50%     |
| NVMe | 503       | 660    | 40.63%  |
| SAS  | 65        | 105    | 5.25%   |
| MMC  | 51        | 61     | 4.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 436       | 681    | 49.71%  |
| 0.51-1.0   | 252       | 347    | 28.73%  |
| 1.01-2.0   | 99        | 140    | 11.29%  |
| 3.01-4.0   | 45        | 82     | 5.13%   |
| 4.01-10.0  | 28        | 40     | 3.19%   |
| 2.01-3.0   | 13        | 17     | 1.48%   |
| 10.01-20.0 | 4         | 8      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 244       | 23.85%  |
| 101-250        | 216       | 21.11%  |
| 501-1000       | 191       | 18.67%  |
| 1001-2000      | 136       | 13.29%  |
| More than 3000 | 88        | 8.6%    |
| 2001-3000      | 63        | 6.16%   |
| 51-100         | 37        | 3.62%   |
| 1-20           | 34        | 3.32%   |
| 21-50          | 11        | 1.08%   |
| Unknown        | 3         | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 203       | 19.61%  |
| 101-250        | 201       | 19.42%  |
| 51-100         | 140       | 13.53%  |
| 251-500        | 135       | 13.04%  |
| 21-50          | 128       | 12.37%  |
| 501-1000       | 103       | 9.95%   |
| 1001-2000      | 63        | 6.09%   |
| More than 3000 | 41        | 3.96%   |
| 2001-3000      | 18        | 1.74%   |
| Unknown        | 3         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ04ABF100 1TB               | 2         | 2      | 1.98%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 1.98%   |
| SK hynix BC711 HFM256GD3JX013N 256GB | 2         | 2      | 1.98%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 2      | 1.98%   |
| Seagate ST3500418AS 500GB            | 2         | 2      | 1.98%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 2      | 1.98%   |
| SanDisk SSD PLUS 240GB               | 2         | 2      | 1.98%   |
| Samsung Electronics SSD 870 EVO 1TB  | 2         | 2      | 1.98%   |
| Kingston SUV400S37240G 240GB SSD     | 2         | 2      | 1.98%   |
| Hitachi HDS721010CLA630 1TB          | 2         | 2      | 1.98%   |
| HGST HTS721010A9E630 1TB             | 2         | 2      | 1.98%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 0.99%   |
| WDC WD7502ABYS-02A6B0 752GB          | 1         | 1      | 0.99%   |
| WDC WD5000AZRX-00A3KB0 500GB         | 1         | 1      | 0.99%   |
| WDC WD5000AVVS-63M8B0 500GB          | 1         | 1      | 0.99%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 0.99%   |
| WDC WD30EZRX-00MMMB0 3TB             | 1         | 1      | 0.99%   |
| WDC WD20EFRX-68EUZN0 2TB             | 1         | 2      | 0.99%   |
| WDC WD20EADS-14R6B0 2TB              | 1         | 1      | 0.99%   |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1      | 0.99%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 1      | 0.99%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1      | 0.99%   |
| WDC WD10EURX-73C57Y0 1TB             | 1         | 1      | 0.99%   |
| WDC WD10EARS-00MVWB0 1TB             | 1         | 1      | 0.99%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 1      | 0.99%   |
| WDC WD10EACS-65D6B0 1TB              | 1         | 1      | 0.99%   |
| VISIPRO SSD 256GB                    | 1         | 2      | 0.99%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 1         | 1      | 0.99%   |
| Toshiba MQ01ABF032 320GB             | 1         | 1      | 0.99%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 0.99%   |
| tecmiyo SATA SSD 128GB               | 1         | 3      | 0.99%   |
| T-FORCE SSD 512GB                    | 1         | 1      | 0.99%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 0.99%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 0.99%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1      | 0.99%   |
| Seagate ST4000VN008-2DR166 4TB       | 1         | 2      | 0.99%   |
| Seagate ST3500630AS 500GB            | 1         | 1      | 0.99%   |
| Seagate ST3250310AS 250GB            | 1         | 1      | 0.99%   |
| Seagate ST320LT020-9YG142 320GB      | 1         | 1      | 0.99%   |
| Seagate ST3160827AS 160GB            | 1         | 1      | 0.99%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 24     | 20.41%  |
| WDC                 | 14        | 16     | 14.29%  |
| Samsung Electronics | 10        | 15     | 10.2%   |
| Hitachi             | 10        | 10     | 10.2%   |
| Crucial             | 6         | 6      | 6.12%   |
| Toshiba             | 5         | 5      | 5.1%    |
| SK hynix            | 4         | 4      | 4.08%   |
| SanDisk             | 4         | 4      | 4.08%   |
| HGST                | 4         | 4      | 4.08%   |
| Kingston            | 3         | 3      | 3.06%   |
| Micron Technology   | 2         | 2      | 2.04%   |
| Maxtor              | 2         | 2      | 2.04%   |
| Intel               | 2         | 5      | 2.04%   |
| A-DATA Technology   | 2         | 2      | 2.04%   |
| VISIPRO             | 1         | 2      | 1.02%   |
| tecmiyo             | 1         | 3      | 1.02%   |
| T-FORCE             | 1         | 1      | 1.02%   |
| R580                | 1         | 1      | 1.02%   |
| Phison Electronics  | 1         | 1      | 1.02%   |
| OCZ                 | 1         | 1      | 1.02%   |
| LITEONIT            | 1         | 1      | 1.02%   |
| LITEON              | 1         | 1      | 1.02%   |
| Intenso             | 1         | 1      | 1.02%   |
| BAITITON            | 1         | 1      | 1.02%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 24     | 35.71%  |
| WDC                 | 13        | 15     | 23.21%  |
| Hitachi             | 10        | 10     | 17.86%  |
| Toshiba             | 4         | 4      | 7.14%   |
| HGST                | 4         | 4      | 7.14%   |
| Samsung Electronics | 3         | 8      | 5.36%   |
| Maxtor              | 2         | 2      | 3.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 67     | 56.38%  |
| SSD  | 33        | 40     | 35.11%  |
| NVMe | 8         | 8      | 8.51%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 562       | 1003   | 49.73%  |
| Detected | 475       | 952    | 42.04%  |
| Malfunc  | 92        | 115    | 8.14%   |
| Failed   | 1         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 600       | 43.07%  |
| AMD                            | 214       | 15.36%  |
| Samsung Electronics            | 140       | 10.05%  |
| SanDisk                        | 97        | 6.96%   |
| SK hynix                       | 46        | 3.3%    |
| Kingston Technology Company    | 44        | 3.16%   |
| Phison Electronics             | 33        | 2.37%   |
| Toshiba America Info Systems   | 28        | 2.01%   |
| Micron Technology              | 27        | 1.94%   |
| ASMedia Technology             | 26        | 1.87%   |
| KIOXIA                         | 23        | 1.65%   |
| Micron/Crucial Technology      | 21        | 1.51%   |
| Silicon Motion                 | 11        | 0.79%   |
| Realtek Semiconductor          | 10        | 0.72%   |
| JMicron Technology             | 9         | 0.65%   |
| Marvell Technology Group       | 8         | 0.57%   |
| Solid State Storage Technology | 7         | 0.5%    |
| ADATA Technology               | 7         | 0.5%    |
| LSI Logic / Symbios Logic      | 6         | 0.43%   |
| Union Memory (Shenzhen)        | 5         | 0.36%   |
| Seagate Technology             | 5         | 0.36%   |
| Nvidia                         | 4         | 0.29%   |
| Apple                          | 4         | 0.29%   |
| Silicon Image                  | 2         | 0.14%   |
| Netac Technology               | 2         | 0.14%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.14%   |
| Broadcom / LSI                 | 2         | 0.14%   |
| Zhaoxin                        | 1         | 0.07%   |
| Yangtze Memory Technologies    | 1         | 0.07%   |
| VIA Technologies               | 1         | 0.07%   |
| Shenzhen Longsys Electronics   | 1         | 0.07%   |
| OCZ Technology Group           | 1         | 0.07%   |
| O2 Micro                       | 1         | 0.07%   |
| Lenovo                         | 1         | 0.07%   |
| INNOGRIT                       | 1         | 0.07%   |
| Hewlett-Packard                | 1         | 0.07%   |
| Unknown                        | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 154       | 9.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 64        | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 61        | 3.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 49        | 3.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 49        | 3.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 46        | 2.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 36        | 2.29%   |
| AMD 400 Series Chipset SATA Controller                                         | 34        | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 32        | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 31        | 1.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 25        | 1.59%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 24        | 1.53%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 23        | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 23        | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 22        | 1.4%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 21        | 1.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21        | 1.34%   |
| Intel Tiger Lake-LP SATA Controller                                            | 19        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 18        | 1.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 18        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 18        | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 17        | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 15        | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 0.96%   |
| Intel SATA Controller [RAID mode]                                              | 14        | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 0.89%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 14        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 14        | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 13        | 0.83%   |
| Intel SSD 660P Series                                                          | 13        | 0.83%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 12        | 0.76%   |
| Phison E12 NVMe Controller                                                     | 12        | 0.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 12        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 0.76%   |
| Kingston Company A2000 NVMe SSD                                                | 10        | 0.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 0.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 0.64%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 10        | 0.64%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 9         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 700       | 50.61%  |
| NVMe | 499       | 36.08%  |
| RAID | 117       | 8.46%   |
| IDE  | 60        | 4.34%   |
| SAS  | 5         | 0.36%   |
| SCSI | 2         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 709       | 70.9%   |
| AMD           | 288       | 28.8%   |
| sifive,u74-mc | 1         | 0.1%    |
| CentaurHauls  | 1         | 0.1%    |
| ARM           | 1         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 21        | 2.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 20        | 2%      |
| Intel Core i7-9750H CPU @ 2.60GHz       | 17        | 1.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics  | 17        | 1.7%    |
| Intel 12th Gen Core i7-12700H           | 13        | 1.3%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 13        | 1.3%    |
| AMD Ryzen 5 5500U with Radeon Graphics  | 13        | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 12        | 1.2%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 1.2%    |
| Intel Celeron N4020 CPU @ 1.10GHz       | 10        | 1%      |
| Intel Core i7-3770 CPU @ 3.40GHz        | 9         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 9         | 0.9%    |
| AMD Ryzen 5 5600X 6-Core Processor      | 9         | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 8         | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 8         | 0.8%    |
| Intel 12th Gen Core i7-1260P            | 8         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 7         | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 0.7%    |
| Intel 12th Gen Core i7-1255U            | 7         | 0.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 7         | 0.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics  | 7         | 0.7%    |
| Intel Core i7-4790K CPU @ 4.00GHz       | 6         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 6         | 0.6%    |
| Intel Core i5-10400F CPU @ 2.90GHz      | 6         | 0.6%    |
| AMD Ryzen 7 3700X 8-Core Processor      | 6         | 0.6%    |
| AMD Ryzen 5 3600 6-Core Processor       | 6         | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 5         | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz        | 5         | 0.5%    |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 5         | 0.5%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 5         | 0.5%    |
| Intel Core i5-9600K CPU @ 3.70GHz       | 5         | 0.5%    |
| Intel Core i5-7300U CPU @ 2.60GHz       | 5         | 0.5%    |
| Intel Core i5-4590 CPU @ 3.30GHz        | 5         | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 5         | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 0.5%    |
| Intel Core i5-10300H CPU @ 2.50GHz      | 5         | 0.5%    |
| Intel Celeron N4000 CPU @ 1.10GHz       | 5         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 207       | 20.7%   |
| Intel Core i5           | 185       | 18.5%   |
| Other                   | 151       | 15.1%   |
| AMD Ryzen 7             | 81        | 8.1%    |
| AMD Ryzen 5             | 81        | 8.1%    |
| Intel Core i3           | 46        | 4.6%    |
| Intel Celeron           | 36        | 3.6%    |
| AMD Ryzen 9             | 28        | 2.8%    |
| Intel Xeon              | 22        | 2.2%    |
| Intel Pentium           | 19        | 1.9%    |
| Intel Core 2 Duo        | 16        | 1.6%    |
| AMD Ryzen 3             | 16        | 1.6%    |
| AMD FX                  | 13        | 1.3%    |
| AMD Ryzen 7 PRO         | 12        | 1.2%    |
| Intel Core i9           | 11        | 1.1%    |
| AMD A6                  | 9         | 0.9%    |
| Intel Pentium Silver    | 7         | 0.7%    |
| AMD A8                  | 6         | 0.6%    |
| AMD Ryzen 5 PRO         | 5         | 0.5%    |
| AMD A10                 | 5         | 0.5%    |
| Intel Core 2 Quad       | 4         | 0.4%    |
| Intel Atom              | 3         | 0.3%    |
| AMD Ryzen Threadripper  | 3         | 0.3%    |
| AMD Phenom II X4        | 3         | 0.3%    |
| AMD Athlon 64 X2        | 3         | 0.3%    |
| AMD Athlon              | 3         | 0.3%    |
| Intel Pentium Gold      | 2         | 0.2%    |
| Intel Core m3           | 2         | 0.2%    |
| AMD PRO A10             | 2         | 0.2%    |
| AMD Phenom II X2        | 2         | 0.2%    |
| AMD Opteron             | 2         | 0.2%    |
| AMD E                   | 2         | 0.2%    |
| AMD Athlon II           | 2         | 0.2%    |
| AMD A4                  | 2         | 0.2%    |
| Intel Core M            | 1         | 0.1%    |
| Intel Core 2            | 1         | 0.1%    |
| Intel Celeron Dual-Core | 1         | 0.1%    |
| AMD Sempron             | 1         | 0.1%    |
| AMD Phenom II X6        | 1         | 0.1%    |
| AMD Phenom              | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 361       | 36.1%   |
| 2       | 266       | 26.6%   |
| 6       | 148       | 14.8%   |
| 8       | 127       | 12.7%   |
| 12      | 29        | 2.9%    |
| 14      | 20        | 2%      |
| 16      | 17        | 1.7%    |
| 10      | 17        | 1.7%    |
| 1       | 5         | 0.5%    |
| 24      | 4         | 0.4%    |
| 3       | 2         | 0.2%    |
| Unknown | 2         | 0.2%    |
| 36      | 1         | 0.1%    |
| 5       | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 993       | 99.3%   |
| 2       | 5         | 0.5%    |
| Unknown | 2         | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 797       | 79.38%  |
| 1       | 205       | 20.42%  |
| Unknown | 2         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 999       | 99.9%   |
| Unknown        | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 408       | 40.12%  |
| 0x806c1    | 37        | 3.64%   |
| 0x306a9    | 34        | 3.34%   |
| 0x0a50000c | 32        | 3.15%   |
| 0x906a3    | 31        | 3.05%   |
| 0x306c3    | 29        | 2.85%   |
| 0x806ea    | 27        | 2.65%   |
| 0x906ea    | 22        | 2.16%   |
| 0x806ec    | 17        | 1.67%   |
| 0x08608103 | 17        | 1.67%   |
| 0x206a7    | 16        | 1.57%   |
| 0x08600106 | 16        | 1.57%   |
| 0x906e9    | 14        | 1.38%   |
| 0x506e3    | 14        | 1.38%   |
| 0x806e9    | 13        | 1.28%   |
| 0x08701021 | 13        | 1.28%   |
| 0x406e3    | 11        | 1.08%   |
| 0x906ed    | 9         | 0.88%   |
| 0x1067a    | 9         | 0.88%   |
| 0x906a4    | 8         | 0.79%   |
| 0x706a8    | 8         | 0.79%   |
| 0x08608102 | 8         | 0.79%   |
| 0x0800820d | 8         | 0.79%   |
| 0xa0653    | 7         | 0.69%   |
| 0xa0652    | 7         | 0.69%   |
| 0x806c2    | 7         | 0.69%   |
| 0x706a1    | 7         | 0.69%   |
| 0x0a50000d | 7         | 0.69%   |
| 0x08108109 | 7         | 0.69%   |
| 0x90672    | 6         | 0.59%   |
| 0x806d1    | 6         | 0.59%   |
| 0x706e5    | 6         | 0.59%   |
| 0x40651    | 6         | 0.59%   |
| 0xa0655    | 5         | 0.49%   |
| 0x406f1    | 5         | 0.49%   |
| 0x40661    | 5         | 0.49%   |
| 0x0a201205 | 5         | 0.49%   |
| 0x06006705 | 5         | 0.49%   |
| 0x010000c8 | 5         | 0.49%   |
| 0x506c9    | 4         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 165       | 16.47%  |
| Haswell          | 87        | 8.68%   |
| Zen 3            | 80        | 7.98%   |
| IvyBridge        | 79        | 7.88%   |
| Unknown          | 71        | 7.09%   |
| TigerLake        | 65        | 6.49%   |
| Alderlake Hybrid | 50        | 4.99%   |
| Zen 2            | 49        | 4.89%   |
| Skylake          | 42        | 4.19%   |
| SandyBridge      | 39        | 3.89%   |
| Zen+             | 38        | 3.79%   |
| CometLake        | 30        | 2.99%   |
| Goldmont plus    | 27        | 2.69%   |
| IceLake          | 22        | 2.2%    |
| Zen              | 20        | 2%      |
| Piledriver       | 17        | 1.7%    |
| Broadwell        | 17        | 1.7%    |
| Penryn           | 16        | 1.6%    |
| Westmere         | 13        | 1.3%    |
| Excavator        | 13        | 1.3%    |
| K10              | 12        | 1.2%    |
| Silvermont       | 10        | 1%      |
| Nehalem          | 9         | 0.9%    |
| Core             | 8         | 0.8%    |
| Goldmont         | 6         | 0.6%    |
| K10 Llano        | 4         | 0.4%    |
| Steamroller      | 3         | 0.3%    |
| Puma             | 3         | 0.3%    |
| K8 Hammer        | 3         | 0.3%    |
| Bobcat           | 2         | 0.2%    |
| K8 & K10 hybrid  | 1         | 0.1%    |
| Bulldozer        | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 551       | 44.91%  |
| Nvidia                     | 366       | 29.83%  |
| AMD                        | 301       | 24.53%  |
| Matrox Electronics Systems | 5         | 0.41%   |
| ASPEED Technology          | 3         | 0.24%   |
| Zhaoxin                    | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 57        | 4.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 47        | 3.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 41        | 3.29%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 31        | 2.48%   |
| AMD Lucienne                                                                          | 29        | 2.32%   |
| Intel UHD Graphics 620                                                                | 28        | 2.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 28        | 2.24%   |
| Intel HD Graphics 620                                                                 | 27        | 2.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 27        | 2.16%   |
| AMD Renoir                                                                            | 27        | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 22        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 21        | 1.68%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 21        | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 20        | 1.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 19        | 1.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 16        | 1.28%   |
| Intel HD Graphics 630                                                                 | 16        | 1.28%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 16        | 1.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 15        | 1.2%    |
| Intel HD Graphics 530                                                                 | 13        | 1.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 11        | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 11        | 0.88%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 11        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 10        | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                        | 10        | 0.8%    |
| AMD Rembrandt [Radeon 680M]                                                           | 10        | 0.8%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 9         | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 9         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 9         | 0.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 9         | 0.72%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                | 9         | 0.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 9         | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 8         | 0.64%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 8         | 0.64%   |
| Intel HD Graphics 5500                                                                | 8         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 8         | 0.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 8         | 0.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                            | 8         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 7         | 0.56%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 7         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 357       | 35.63%  |
| 1 x AMD                  | 225       | 22.46%  |
| 1 x Nvidia               | 191       | 19.06%  |
| Intel + Nvidia           | 139       | 13.87%  |
| AMD + Nvidia             | 30        | 2.99%   |
| Intel + AMD              | 29        | 2.89%   |
| 2 x AMD                  | 13        | 1.3%    |
| Other                    | 4         | 0.4%    |
| 2 x Nvidia               | 4         | 0.4%    |
| Nvidia + ASPEED          | 2         | 0.2%    |
| 1 x Matrox               | 2         | 0.2%    |
| AMD + Matrox             | 2         | 0.2%    |
| 1 x Zhaoxin              | 1         | 0.1%    |
| Nvidia + Matrox          | 1         | 0.1%    |
| Intel + AMD + 1 x Nvidia | 1         | 0.1%    |
| 1 x ASPEED               | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 716       | 71.24%  |
| Proprietary | 263       | 26.17%  |
| Unknown     | 26        | 2.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 636       | 62.78%  |
| 0.01-0.5   | 92        | 9.08%   |
| 1.01-2.0   | 87        | 8.59%   |
| 3.01-4.0   | 54        | 5.33%   |
| 0.51-1.0   | 49        | 4.84%   |
| 7.01-8.0   | 45        | 4.44%   |
| 5.01-6.0   | 29        | 2.86%   |
| 8.01-16.0  | 15        | 1.48%   |
| 16.01-24.0 | 4         | 0.39%   |
| 4.01-5.0   | 1         | 0.1%    |
| 2.01-3.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 151       | 12.75%  |
| BOE                     | 125       | 10.56%  |
| AU Optronics            | 119       | 10.05%  |
| Chimei Innolux          | 108       | 9.12%   |
| LG Display              | 93        | 7.85%   |
| Dell                    | 75        | 6.33%   |
| Goldstar                | 72        | 6.08%   |
| Hewlett-Packard         | 54        | 4.56%   |
| Acer                    | 35        | 2.96%   |
| Philips                 | 34        | 2.87%   |
| BenQ                    | 29        | 2.45%   |
| Sharp                   | 25        | 2.11%   |
| AOC                     | 24        | 2.03%   |
| Ancor Communications    | 20        | 1.69%   |
| Iiyama                  | 18        | 1.52%   |
| ASUSTek Computer        | 16        | 1.35%   |
| InfoVision              | 15        | 1.27%   |
| Apple                   | 15        | 1.27%   |
| Lenovo                  | 12        | 1.01%   |
| CSO                     | 11        | 0.93%   |
| Sony                    | 10        | 0.84%   |
| Chi Mei Optoelectronics | 8         | 0.68%   |
| ViewSonic               | 7         | 0.59%   |
| NEC Computers           | 5         | 0.42%   |
| Vizio                   | 4         | 0.34%   |
| Sceptre Tech            | 4         | 0.34%   |
| PANDA                   | 4         | 0.34%   |
| Eizo                    | 4         | 0.34%   |
| RTK                     | 3         | 0.25%   |
| Panasonic               | 3         | 0.25%   |
| MSI                     | 3         | 0.25%   |
| LG Electronics          | 3         | 0.25%   |
| Idek Iiyama             | 3         | 0.25%   |
| HKC                     | 3         | 0.25%   |
| Gigabyte Technology     | 3         | 0.25%   |
| Fujitsu Siemens         | 3         | 0.25%   |
| CHD                     | 3         | 0.25%   |
| Xiaomi                  | 2         | 0.17%   |
| Vestel Elektronik       | 2         | 0.17%   |
| Unknown                 | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 5         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 5         | 0.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 5         | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 5         | 0.41%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5         | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 5         | 0.41%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 5         | 0.41%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.33%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 4         | 0.33%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 0.33%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.25%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 3         | 0.25%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 3         | 0.25%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch           | 3         | 0.25%   |
| Iiyama PLE2207WS IVM5609 1680x1050 474x296mm 22.0-inch                | 3         | 0.25%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch             | 3         | 0.25%   |
| Goldstar 2D HD LG TV GSM59CA 1366x768 510x290mm 23.1-inch             | 3         | 0.25%   |
| Dell 2408WFP DELA02B 1920x1200 519x320mm 24.0-inch                    | 3         | 0.25%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                 | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 3         | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 0.25%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                 | 3         | 0.25%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.25%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                 | 3         | 0.25%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO559C 1920x1080 309x174mm 14.0-inch        | 3         | 0.25%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch        | 3         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 554       | 50.55%  |
| 1366x768 (WXGA)    | 138       | 12.59%  |
| 3840x2160 (4K)     | 84        | 7.66%   |
| 2560x1440 (QHD)    | 57        | 5.2%    |
| 1920x1200 (WUXGA)  | 52        | 4.74%   |
| 1680x1050 (WSXGA+) | 32        | 2.92%   |
| 1600x900 (HD+)     | 28        | 2.55%   |
| 3440x1440          | 18        | 1.64%   |
| 1280x1024 (SXGA)   | 18        | 1.64%   |
| 2560x1600          | 17        | 1.55%   |
| 2880x1800          | 15        | 1.37%   |
| 2560x1080          | 12        | 1.09%   |
| 1440x900 (WXGA+)   | 9         | 0.82%   |
| 3840x1080          | 5         | 0.46%   |
| 1360x768           | 5         | 0.46%   |
| 1280x800 (WXGA)    | 5         | 0.46%   |
| Unknown            | 5         | 0.46%   |
| 2240x1400          | 4         | 0.36%   |
| 2160x1440          | 4         | 0.36%   |
| 2256x1504          | 3         | 0.27%   |
| 1024x768 (XGA)     | 3         | 0.27%   |
| 3840x2400          | 2         | 0.18%   |
| 3072x1920          | 2         | 0.18%   |
| 2736x1824          | 2         | 0.18%   |
| 2520x1680          | 2         | 0.18%   |
| 1920x540           | 2         | 0.18%   |
| 1600x1200          | 2         | 0.18%   |
| 1280x720 (HD)      | 2         | 0.18%   |
| 6160x1440          | 1         | 0.09%   |
| 5760x2160          | 1         | 0.09%   |
| 5760x1080          | 1         | 0.09%   |
| 480x1920           | 1         | 0.09%   |
| 4800x1080          | 1         | 0.09%   |
| 3840x1600          | 1         | 0.09%   |
| 3840x1200          | 1         | 0.09%   |
| 3600x1200          | 1         | 0.09%   |
| 3000x2000          | 1         | 0.09%   |
| 2496x1664          | 1         | 0.09%   |
| 2288x1287          | 1         | 0.09%   |
| 2160x1350          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 276       | 23.43%  |
| 24      | 113       | 9.59%   |
| 14      | 108       | 9.17%   |
| 27      | 97        | 8.23%   |
| 13      | 93        | 7.89%   |
| 23      | 87        | 7.39%   |
| 21      | 72        | 6.11%   |
| 17      | 57        | 4.84%   |
| 31      | 33        | 2.8%    |
| 16      | 29        | 2.46%   |
| 34      | 28        | 2.38%   |
| Unknown | 23        | 1.95%   |
| 22      | 19        | 1.61%   |
| 19      | 17        | 1.44%   |
| 12      | 12        | 1.02%   |
| 18      | 11        | 0.93%   |
| 32      | 10        | 0.85%   |
| 11      | 10        | 0.85%   |
| 72      | 9         | 0.76%   |
| 20      | 9         | 0.76%   |
| 54      | 8         | 0.68%   |
| 40      | 6         | 0.51%   |
| 25      | 6         | 0.51%   |
| 84      | 5         | 0.42%   |
| 46      | 5         | 0.42%   |
| 65      | 4         | 0.34%   |
| 49      | 3         | 0.25%   |
| 36      | 3         | 0.25%   |
| 28      | 3         | 0.25%   |
| 10      | 3         | 0.25%   |
| 69      | 2         | 0.17%   |
| 60      | 2         | 0.17%   |
| 48      | 2         | 0.17%   |
| 42      | 2         | 0.17%   |
| 26      | 2         | 0.17%   |
| 142     | 1         | 0.08%   |
| 78      | 1         | 0.08%   |
| 63      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |
| 43      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 441       | 38.35%  |
| 501-600        | 262       | 22.78%  |
| 401-500        | 120       | 10.43%  |
| 201-300        | 78        | 6.78%   |
| 351-400        | 77        | 6.7%    |
| 601-700        | 52        | 4.52%   |
| 701-800        | 41        | 3.57%   |
| 1001-1500      | 26        | 2.26%   |
| Unknown        | 23        | 2%      |
| 1501-2000      | 17        | 1.48%   |
| 801-900        | 9         | 0.78%   |
| 901-1000       | 3         | 0.26%   |
| More than 2000 | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 788       | 77.41%  |
| 16/10   | 139       | 13.65%  |
| 21/9    | 31        | 3.05%   |
| Unknown | 18        | 1.77%   |
| 3/2     | 17        | 1.67%   |
| 5/4     | 15        | 1.47%   |
| 4/3     | 4         | 0.39%   |
| 32/9    | 4         | 0.39%   |
| 1.00    | 1         | 0.1%    |
| 0.25    | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 283       | 24.5%   |
| 201-250        | 220       | 19.05%  |
| 81-90          | 161       | 13.94%  |
| 301-350        | 99        | 8.57%   |
| 351-500        | 72        | 6.23%   |
| 121-130        | 49        | 4.24%   |
| 151-200        | 45        | 3.9%    |
| 71-80          | 42        | 3.64%   |
| 251-300        | 39        | 3.38%   |
| More than 1000 | 35        | 3.03%   |
| 501-1000       | 23        | 1.99%   |
| Unknown        | 23        | 1.99%   |
| 111-120        | 21        | 1.82%   |
| 141-150        | 16        | 1.39%   |
| 61-70          | 10        | 0.87%   |
| 51-60          | 10        | 0.87%   |
| 41-50          | 3         | 0.26%   |
| 131-140        | 2         | 0.17%   |
| 91-100         | 2         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 354       | 31.78%  |
| 51-100        | 338       | 30.34%  |
| 101-120       | 224       | 20.11%  |
| 161-240       | 107       | 9.61%   |
| 1-50          | 38        | 3.41%   |
| More than 240 | 30        | 2.69%   |
| Unknown       | 23        | 2.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 734       | 72.53%  |
| 2     | 213       | 21.05%  |
| 3     | 30        | 2.96%   |
| 0     | 28        | 2.77%   |
| 4     | 7         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 555       | 36.16%  |
| Intel                             | 539       | 35.11%  |
| Qualcomm Atheros                  | 131       | 8.53%   |
| Broadcom                          | 65        | 4.23%   |
| MediaTek                          | 57        | 3.71%   |
| TP-Link                           | 19        | 1.24%   |
| Ralink Technology                 | 19        | 1.24%   |
| ASIX Electronics                  | 14        | 0.91%   |
| Samsung Electronics               | 11        | 0.72%   |
| Aquantia                          | 10        | 0.65%   |
| Ralink                            | 9         | 0.59%   |
| Lenovo                            | 8         | 0.52%   |
| Broadcom Limited                  | 8         | 0.52%   |
| Sierra Wireless                   | 7         | 0.46%   |
| Huawei Technologies               | 7         | 0.46%   |
| Marvell Technology Group          | 6         | 0.39%   |
| Xiaomi                            | 4         | 0.26%   |
| Qualcomm                          | 4         | 0.26%   |
| Nvidia                            | 4         | 0.26%   |
| Qualcomm Atheros Communications   | 3         | 0.2%    |
| NetGear                           | 3         | 0.2%    |
| Edimax Technology                 | 3         | 0.2%    |
| DisplayLink                       | 3         | 0.2%    |
| D-Link                            | 3         | 0.2%    |
| Belkin Components                 | 3         | 0.2%    |
| ASUSTek Computer                  | 3         | 0.2%    |
| Wilocity                          | 2         | 0.13%   |
| VIA Technologies                  | 2         | 0.13%   |
| JMicron Technology                | 2         | 0.13%   |
| Hewlett-Packard                   | 2         | 0.13%   |
| Google                            | 2         | 0.13%   |
| Ericsson Business Mobile Networks | 2         | 0.13%   |
| Dell                              | 2         | 0.13%   |
| D-Link System                     | 2         | 0.13%   |
| Apple                             | 2         | 0.13%   |
| ZyXEL Communications              | 1         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Solarflare Communications         | 1         | 0.07%   |
| Shenzhen Goodix Technology        | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 354       | 19.57%  |
| Intel Wi-Fi 6 AX200                                               | 60        | 3.32%   |
| Intel Wi-Fi 6 AX201                                               | 47        | 2.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 45        | 2.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 42        | 2.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 40        | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 1.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 1.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.71%   |
| Intel Wireless 8265 / 8275                                        | 28        | 1.55%   |
| Intel I211 Gigabit Network Connection                             | 26        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 23        | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 22        | 1.22%   |
| Intel Wireless 7260                                               | 22        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19        | 1.05%   |
| Intel Wireless 7265                                               | 19        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 1%      |
| Intel Wireless 8260                                               | 16        | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 16        | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 15        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.72%   |
| Intel Ethernet Connection (2) I219-V                              | 13        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.72%   |
| Realtek 802.11ac NIC                                              | 12        | 0.66%   |
| Intel Wireless 3165                                               | 12        | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.66%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 10        | 0.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 0.55%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 0.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 409       | 46.96%  |
| Realtek Semiconductor             | 167       | 19.17%  |
| Qualcomm Atheros                  | 99        | 11.37%  |
| MediaTek                          | 56        | 6.43%   |
| Broadcom                          | 46        | 5.28%   |
| Ralink Technology                 | 19        | 2.18%   |
| TP-Link                           | 15        | 1.72%   |
| Ralink                            | 9         | 1.03%   |
| Sierra Wireless                   | 7         | 0.8%    |
| Broadcom Limited                  | 6         | 0.69%   |
| Qualcomm                          | 4         | 0.46%   |
| Qualcomm Atheros Communications   | 3         | 0.34%   |
| NetGear                           | 3         | 0.34%   |
| Edimax Technology                 | 3         | 0.34%   |
| D-Link                            | 3         | 0.34%   |
| Belkin Components                 | 3         | 0.34%   |
| ASUSTek Computer                  | 3         | 0.34%   |
| Wilocity                          | 2         | 0.23%   |
| Marvell Technology Group          | 2         | 0.23%   |
| Ericsson Business Mobile Networks | 2         | 0.23%   |
| Dell                              | 2         | 0.23%   |
| D-Link System                     | 2         | 0.23%   |
| ZyXEL Communications              | 1         | 0.11%   |
| Microsoft                         | 1         | 0.11%   |
| Mercucys                          | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| LG Electronics                    | 1         | 0.11%   |
| Fibocom                           | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 60        | 6.79%   |
| Intel Wi-Fi 6 AX201                                            | 47        | 5.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 42        | 4.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 40        | 4.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 32        | 3.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 3.51%   |
| Intel Wireless 8265 / 8275                                     | 28        | 3.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 23        | 2.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 22        | 2.49%   |
| Intel Wireless 7260                                            | 22        | 2.49%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 19        | 2.15%   |
| Intel Wireless 7265                                            | 19        | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 19        | 2.15%   |
| Intel Wireless 8260                                            | 16        | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 16        | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 15        | 1.7%    |
| Realtek 802.11ac NIC                                           | 12        | 1.36%   |
| Intel Wireless 3165                                            | 12        | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 12        | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 1.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.13%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 9         | 1.02%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 9         | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8         | 0.9%    |
| Realtek 802.11n WLAN Adapter                                   | 8         | 0.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 0.9%    |
| Intel Wireless-AC 9260                                         | 7         | 0.79%   |
| Intel Centrino Advanced-N 6235                                 | 7         | 0.79%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                 | 6         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                | 6         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 6         | 0.68%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 6         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 473       | 53.27%  |
| Intel                      | 268       | 30.18%  |
| Qualcomm Atheros           | 36        | 4.05%   |
| Broadcom                   | 27        | 3.04%   |
| ASIX Electronics           | 14        | 1.58%   |
| Samsung Electronics        | 11        | 1.24%   |
| Aquantia                   | 10        | 1.13%   |
| Lenovo                     | 8         | 0.9%    |
| Huawei Technologies        | 7         | 0.79%   |
| Xiaomi                     | 4         | 0.45%   |
| TP-Link                    | 4         | 0.45%   |
| Nvidia                     | 4         | 0.45%   |
| Marvell Technology Group   | 4         | 0.45%   |
| DisplayLink                | 3         | 0.34%   |
| VIA Technologies           | 2         | 0.23%   |
| JMicron Technology         | 2         | 0.23%   |
| Google                     | 2         | 0.23%   |
| Broadcom Limited           | 2         | 0.23%   |
| Apple                      | 2         | 0.23%   |
| ZTE WCDMA Technologies MSM | 1         | 0.11%   |
| Solarflare Communications  | 1         | 0.11%   |
| MediaTek                   | 1         | 0.11%   |
| ICS Advent                 | 1         | 0.11%   |
| IBM                        | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 354       | 38.73%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 45        | 4.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 3.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 3.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34        | 3.72%   |
| Intel I211 Gigabit Network Connection                             | 26        | 2.84%   |
| Intel Ethernet Controller I225-V                                  | 23        | 2.52%   |
| Intel Ethernet Connection I217-LM                                 | 18        | 1.97%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 1.42%   |
| Intel Ethernet Connection (2) I219-V                              | 13        | 1.42%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 1.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.31%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 1.31%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 1.09%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.88%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.77%   |
| Intel I210 Gigabit Network Connection                             | 7         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.77%   |
| Intel Ethernet Connection (10) I219-V                             | 7         | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.77%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7         | 0.77%   |
| Intel Ethernet Connection (16) I219-LM                            | 6         | 0.66%   |
| Intel Ethernet Connection (14) I219-V                             | 6         | 0.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.55%   |
| Huawei MLA-L11                                                    | 5         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.44%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.44%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.44%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 4         | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 821       | 49.91%  |
| Ethernet | 814       | 49.48%  |
| Modem    | 7         | 0.43%   |
| Unknown  | 3         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 636       | 60.51%  |
| Ethernet | 415       | 39.49%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 528       | 52.8%   |
| 1     | 419       | 41.9%   |
| 3     | 25        | 2.5%    |
| 0     | 21        | 2.1%    |
| 4     | 5         | 0.5%    |
| 6     | 2         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 711       | 70.54%  |
| Yes  | 297       | 29.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 361       | 49.45%  |
| Realtek Semiconductor           | 87        | 11.92%  |
| Cambridge Silicon Radio         | 47        | 6.44%   |
| Qualcomm Atheros Communications | 45        | 6.16%   |
| IMC Networks                    | 34        | 4.66%   |
| Foxconn / Hon Hai               | 29        | 3.97%   |
| Broadcom                        | 28        | 3.84%   |
| Lite-On Technology              | 21        | 2.88%   |
| ASUSTek Computer                | 16        | 2.19%   |
| Apple                           | 15        | 2.05%   |
| MediaTek                        | 8         | 1.1%    |
| Realtek                         | 6         | 0.82%   |
| Dell                            | 6         | 0.82%   |
| TP-Link                         | 5         | 0.68%   |
| Toshiba                         | 4         | 0.55%   |
| Edimax Technology               | 4         | 0.55%   |
| Ralink                          | 2         | 0.27%   |
| Marvell Semiconductor           | 2         | 0.27%   |
| Hewlett-Packard                 | 2         | 0.27%   |
| USI                             | 1         | 0.14%   |
| SINO WEALTH                     | 1         | 0.14%   |
| Foxconn International           | 1         | 0.14%   |
| Dynex                           | 1         | 0.14%   |
| D-Link                          | 1         | 0.14%   |
| Conwise Technology              | 1         | 0.14%   |
| Chicony Electronics             | 1         | 0.14%   |
| Alps Electric                   | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 95        | 13%     |
| Intel AX201 Bluetooth                                                               | 83        | 11.35%  |
| Realtek Bluetooth Radio                                                             | 69        | 9.44%   |
| Intel AX200 Bluetooth                                                               | 58        | 7.93%   |
| Intel Bluetooth Device                                                              | 49        | 6.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 47        | 6.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 47        | 6.43%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 23        | 3.15%   |
| IMC Networks Wireless_Device                                                        | 16        | 2.19%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 15        | 2.05%   |
| Intel AX210 Bluetooth                                                               | 14        | 1.92%   |
| Lite-On Wireless_Device                                                             | 13        | 1.78%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 12        | 1.64%   |
| Apple Bluetooth Host Controller                                                     | 11        | 1.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 10        | 1.37%   |
| IMC Networks Bluetooth Radio                                                        | 10        | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 1.09%   |
| MediaTek Wireless_Device                                                            | 8         | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 8         | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 0.96%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 7         | 0.96%   |
| Broadcom HP Portable SoftSailing                                                    | 6         | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.82%   |
| TP-Link UB5A Adapter                                                                | 5         | 0.68%   |
| Realtek 802.11ac WLAN Adapter                                                       | 5         | 0.68%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.68%   |
| ASUS ASUS USB-BT500                                                                 | 5         | 0.68%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth                                         | 4         | 0.55%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.41%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.27%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 2         | 0.27%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 0.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.27%   |
| Edimax Bluetooth Adapter                                                            | 2         | 0.27%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.27%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.27%   |
| ASUS Qualcomm Bluetooth 4.1                                                         | 2         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 690       | 46.06%  |
| AMD                       | 339       | 22.63%  |
| Nvidia                    | 279       | 18.62%  |
| C-Media Electronics       | 29        | 1.94%   |
| GN Netcom                 | 13        | 0.87%   |
| JMTek                     | 11        | 0.73%   |
| Lenovo                    | 9         | 0.6%    |
| Texas Instruments         | 6         | 0.4%    |
| Razer USA                 | 6         | 0.4%    |
| Logitech                  | 6         | 0.4%    |
| Hewlett-Packard           | 6         | 0.4%    |
| Creative Labs             | 6         | 0.4%    |
| Realtek Semiconductor     | 5         | 0.33%   |
| Generalplus Technology    | 5         | 0.33%   |
| Focusrite-Novation        | 5         | 0.33%   |
| VIA Technologies          | 4         | 0.27%   |
| Micro Star International  | 4         | 0.27%   |
| Kingston Technology       | 4         | 0.27%   |
| Corsair                   | 4         | 0.27%   |
| Blue Microphones          | 4         | 0.27%   |
| Tenx Technology           | 3         | 0.2%    |
| KORG                      | 3         | 0.2%    |
| Apple                     | 3         | 0.2%    |
| ZOOM                      | 2         | 0.13%   |
| TerraTec Electronic       | 2         | 0.13%   |
| SteelSeries ApS           | 2         | 0.13%   |
| M-Audio                   | 2         | 0.13%   |
| HECATE G2 GAMING HEADSET  | 2         | 0.13%   |
| ASUSTek Computer          | 2         | 0.13%   |
| Arturia                   | 2         | 0.13%   |
| AKAI Professional M.I.    | 2         | 0.13%   |
| Zhaoxin                   | 1         | 0.07%   |
| Yamaha                    | 1         | 0.07%   |
| Veho                      | 1         | 0.07%   |
| Unknown                   | 1         | 0.07%   |
| Sony                      | 1         | 0.07%   |
| Silicon Motion            | 1         | 0.07%   |
| Sennheiser Communications | 1         | 0.07%   |
| Samson Technologies       | 1         | 0.07%   |
| Roland                    | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 148       | 8.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 98        | 5.51%   |
| Intel Sunrise Point-LP HD Audio                                            | 79        | 4.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 71        | 3.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 65        | 3.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 56        | 3.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 47        | 2.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 46        | 2.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 46        | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 43        | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 37        | 2.08%   |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 1.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 27        | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 26        | 1.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 1.41%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 24        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 23        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 22        | 1.24%   |
| Intel 200 Series PCH HD Audio                                              | 20        | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 19        | 1.07%   |
| Nvidia TU106 High Definition Audio Controller                              | 18        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 18        | 1.01%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 18        | 1.01%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 17        | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 0.96%   |
| AMD FCH Azalia Controller                                                  | 17        | 0.96%   |
| Nvidia GA104 High Definition Audio Controller                              | 16        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 0.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 16        | 0.9%    |
| Nvidia GA106 High Definition Audio Controller                              | 15        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15        | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                         | 14        | 0.79%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 13        | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 12        | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 12        | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 12        | 0.67%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 12        | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 12        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 187       | 23.61%  |
| SK hynix            | 119       | 15.03%  |
| Kingston            | 96        | 12.12%  |
| Micron Technology   | 85        | 10.73%  |
| Crucial             | 69        | 8.71%   |
| Corsair             | 45        | 5.68%   |
| Unknown             | 37        | 4.67%   |
| G.Skill             | 29        | 3.66%   |
| Unknown (ABCD)      | 16        | 2.02%   |
| A-DATA Technology   | 15        | 1.89%   |
| Ramaxel Technology  | 10        | 1.26%   |
| Unknown             | 9         | 1.14%   |
| Team                | 8         | 1.01%   |
| Elpida              | 7         | 0.88%   |
| Patriot             | 6         | 0.76%   |
| Nanya Technology    | 6         | 0.76%   |
| Smart               | 4         | 0.51%   |
| Silicon Power       | 4         | 0.51%   |
| AMD                 | 4         | 0.51%   |
| Wilk                | 3         | 0.38%   |
| Transcend           | 3         | 0.38%   |
| PNY                 | 3         | 0.38%   |
| Teikon              | 2         | 0.25%   |
| GOODRAM             | 2         | 0.25%   |
| Atermiter           | 2         | 0.25%   |
| Unknown (8A02)      | 1         | 0.13%   |
| Unifosa             | 1         | 0.13%   |
| Super Talent        | 1         | 0.13%   |
| Shenzhen Zhongteng  | 1         | 0.13%   |
| Shenzhen WODPOSIT   | 1         | 0.13%   |
| SHARETRONIC         | 1         | 0.13%   |
| Qumo                | 1         | 0.13%   |
| Qimonda             | 1         | 0.13%   |
| Neo Forza           | 1         | 0.13%   |
| Lexar               | 1         | 0.13%   |
| Kingmax             | 1         | 0.13%   |
| Imation             | 1         | 0.13%   |
| Hewlett-Packard     | 1         | 0.13%   |
| Goldkey             | 1         | 0.13%   |
| Gold Key            | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 13        | 1.56%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 1.08%   |
| Unknown                                                          | 9         | 1.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.72%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.72%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 0.6%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.48%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 4         | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.48%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.48%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.48%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.48%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.48%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.48%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.48%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 3         | 0.36%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 3         | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 3         | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.36%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 3         | 0.36%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.36%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.36%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.36%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.36%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 402       | 60%     |
| DDR3    | 151       | 22.54%  |
| LPDDR4  | 42        | 6.27%   |
| DDR5    | 25        | 3.73%   |
| LPDDR5  | 12        | 1.79%   |
| DDR2    | 10        | 1.49%   |
| Unknown | 10        | 1.49%   |
| SDRAM   | 8         | 1.19%   |
| LPDDR3  | 8         | 1.19%   |
| DDR     | 2         | 0.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 391       | 57.67%  |
| DIMM         | 212       | 31.27%  |
| Row Of Chips | 66        | 9.73%   |
| Chip         | 5         | 0.74%   |
| Unknown      | 3         | 0.44%   |
| RIMM         | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 334       | 45.88%  |
| 16384 | 154       | 21.15%  |
| 4096  | 151       | 20.74%  |
| 2048  | 44        | 6.04%   |
| 32768 | 40        | 5.49%   |
| 1024  | 5         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 186       | 25.87%  |
| 1600    | 105       | 14.6%   |
| 2667    | 97        | 13.49%  |
| 2400    | 66        | 9.18%   |
| 1333    | 39        | 5.42%   |
| 3600    | 26        | 3.62%   |
| 2133    | 24        | 3.34%   |
| 4800    | 19        | 2.64%   |
| 4267    | 18        | 2.5%    |
| 1867    | 13        | 1.81%   |
| 6400    | 11        | 1.53%   |
| 1334    | 9         | 1.25%   |
| 2666    | 8         | 1.11%   |
| 3800    | 7         | 0.97%   |
| 3000    | 7         | 0.97%   |
| 3266    | 6         | 0.83%   |
| 2933    | 5         | 0.7%    |
| 1066    | 5         | 0.7%    |
| 667     | 5         | 0.7%    |
| 4266    | 4         | 0.56%   |
| 3066    | 4         | 0.56%   |
| 2800    | 4         | 0.56%   |
| 3666    | 3         | 0.42%   |
| 3333    | 3         | 0.42%   |
| 1866    | 3         | 0.42%   |
| 800     | 3         | 0.42%   |
| 400     | 3         | 0.42%   |
| Unknown | 3         | 0.42%   |
| 8400    | 2         | 0.28%   |
| 6000    | 2         | 0.28%   |
| 3866    | 2         | 0.28%   |
| 2048    | 2         | 0.28%   |
| 1648    | 2         | 0.28%   |
| 52217   | 1         | 0.14%   |
| 7500    | 1         | 0.14%   |
| 5808    | 1         | 0.14%   |
| 5800    | 1         | 0.14%   |
| 5600    | 1         | 0.14%   |
| 5200    | 1         | 0.14%   |
| 4199    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 33.33%  |
| Seiko Epson         | 6         | 20%     |
| Brother Industries  | 4         | 13.33%  |
| Canon               | 3         | 10%     |
| Samsung Electronics | 2         | 6.67%   |
| Xerox               | 1         | 3.33%   |
| Prolific Technology | 1         | 3.33%   |
| Kyocera             | 1         | 3.33%   |
| Dymo-CoStar         | 1         | 3.33%   |
| Datamax-O'Neil      | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson L360 Series               | 2         | 6.67%   |
| Seiko Epson L3110 Series              | 2         | 6.67%   |
| Samsung M2070 Series                  | 2         | 6.67%   |
| Brother MFC-J460DW                    | 2         | 6.67%   |
| Xerox Phaser 3140 and 3155            | 1         | 3.33%   |
| Seiko Epson XP-3100 Series            | 1         | 3.33%   |
| Seiko Epson ET-2700 Series            | 1         | 3.33%   |
| Prolific PL2305 Parallel Port         | 1         | 3.33%   |
| Kyocera Mita FS-820                   | 1         | 3.33%   |
| HP OfficeJet 5500 series              | 1         | 3.33%   |
| HP LaserJet Professional P 1102w      | 1         | 3.33%   |
| HP LaserJet P2015 series              | 1         | 3.33%   |
| HP LaserJet 1022                      | 1         | 3.33%   |
| HP LaserJet 1012                      | 1         | 3.33%   |
| HP ENVY 4500 series                   | 1         | 3.33%   |
| HP DeskJet D2300                      | 1         | 3.33%   |
| HP DeskJet 3700 series                | 1         | 3.33%   |
| HP DeskJet 3630 series                | 1         | 3.33%   |
| HP ColorLaserJet M253-M254            | 1         | 3.33%   |
| Dymo-CoStar LabelWriter 450           | 1         | 3.33%   |
| Datamax-O'Neil Datamax E-4304         | 1         | 3.33%   |
| Canon PIXMA MX470 Series              | 1         | 3.33%   |
| Canon LaserShot LBP-1120 Printer      | 1         | 3.33%   |
| Canon iP2600 series                   | 1         | 3.33%   |
| Brother PT-P700 P-touch Label Printer | 1         | 3.33%   |
| Brother HL-2230 series                | 1         | 3.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 5         | 71.43%  |
| Seiko Epson    | 1         | 14.29%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2         | 28.57%  |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 14.29%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1         | 14.29%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 14.29%  |
| Canon CanoScan LiDE 220                     | 1         | 14.29%  |
| Canon CanoScan LiDE 210                     | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 120       | 17.75%  |
| Microdia                               | 71        | 10.5%   |
| IMC Networks                           | 68        | 10.06%  |
| Logitech                               | 56        | 8.28%   |
| Quanta                                 | 49        | 7.25%   |
| Bison Electronics                      | 49        | 7.25%   |
| Realtek Semiconductor                  | 44        | 6.51%   |
| Sunplus Innovation Technology          | 31        | 4.59%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 3.85%   |
| Syntek                                 | 16        | 2.37%   |
| Luxvisions Innotech Limited            | 16        | 2.37%   |
| Acer                                   | 13        | 1.92%   |
| Lite-On Technology                     | 11        | 1.63%   |
| Apple                                  | 10        | 1.48%   |
| Silicon Motion                         | 8         | 1.18%   |
| Samsung Electronics                    | 8         | 1.18%   |
| Generalplus Technology                 | 6         | 0.89%   |
| Microsoft                              | 5         | 0.74%   |
| Alcor Micro                            | 5         | 0.74%   |
| Y Media                                | 4         | 0.59%   |
| SunplusIT                              | 4         | 0.59%   |
| Sonix Technology                       | 4         | 0.59%   |
| icSpring                               | 4         | 0.59%   |
| Z-Star Microelectronics                | 3         | 0.44%   |
| Suyin                                  | 3         | 0.44%   |
| KYE Systems (Mouse Systems)            | 3         | 0.44%   |
| GEMBIRD                                | 3         | 0.44%   |
| ARC International                      | 3         | 0.44%   |
| Unknown                                | 2         | 0.3%    |
| LG Electronics                         | 2         | 0.3%    |
| Lenovo                                 | 2         | 0.3%    |
| Jieli Technology                       | 2         | 0.3%    |
| Fifine K420                            | 2         | 0.3%    |
| Xiaomi                                 | 1         | 0.15%   |
| USB Camera CS                          | 1         | 0.15%   |
| STEREOLABS                             | 1         | 0.15%   |
| SN0002                                 | 1         | 0.15%   |
| ShineTech                              | 1         | 0.15%   |
| Ricoh                                  | 1         | 0.15%   |
| Razer USA                              | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 35        | 5.16%   |
| Microdia Integrated_Webcam_HD                                   | 34        | 5.01%   |
| IMC Networks Integrated Camera                                  | 24        | 3.54%   |
| Bison Integrated Camera                                         | 23        | 3.39%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 19        | 2.8%    |
| Logitech HD Pro Webcam C920                                     | 17        | 2.51%   |
| Realtek Integrated_Webcam_HD                                    | 14        | 2.06%   |
| Chicony HD WebCam                                               | 12        | 1.77%   |
| Sunplus Integrated_Webcam_HD                                    | 11        | 1.62%   |
| Quanta HP TrueVision HD Camera                                  | 11        | 1.62%   |
| Syntek Integrated Camera                                        | 10        | 1.47%   |
| Logitech Webcam C270                                            | 10        | 1.47%   |
| Chicony HP HD Camera                                            | 10        | 1.47%   |
| Chicony HD User Facing                                          | 10        | 1.47%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 8         | 1.18%   |
| Quanta HD User Facing                                           | 8         | 1.18%   |
| Microdia Integrated_Webcam_FHD                                  | 7         | 1.03%   |
| Bison HD Webcam                                                 | 7         | 1.03%   |
| Microdia Webcam Vitade AF                                       | 6         | 0.88%   |
| Logitech C922 Pro Stream Webcam                                 | 6         | 0.88%   |
| IMC Networks HD Camera                                          | 6         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)                         | 6         | 0.88%   |
| Chicony HP Wide Vision HD Camera                                | 6         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.88%   |
| Quanta HP Wide Vision HD Camera                                 | 5         | 0.74%   |
| Luxvisions Innotech Limited Integrated Camera                   | 5         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 5         | 0.74%   |
| Apple FaceTime HD Camera (Built-in)                             | 5         | 0.74%   |
| Y Media USB Camera                                              | 4         | 0.59%   |
| Syntek Lenovo EasyCamera                                        | 4         | 0.59%   |
| Realtek USB Camera                                              | 4         | 0.59%   |
| Realtek Integrated Webcam                                       | 4         | 0.59%   |
| Quanta HP HD Camera                                             | 4         | 0.59%   |
| Quanta HD Webcam                                                | 4         | 0.59%   |
| Quanta ACER HD User Facing                                      | 4         | 0.59%   |
| Microdia GC02M2                                                 | 4         | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 4         | 0.59%   |
| Lite-On Integrated Camera                                       | 4         | 0.59%   |
| icSpring camera                                                 | 4         | 0.59%   |
| Chicony USB2.0 Camera                                           | 4         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 42        | 31.82%  |
| Shenzhen Goodix Technology         | 34        | 25.76%  |
| Validity Sensors                   | 33        | 25%     |
| Elan Microelectronics              | 10        | 7.58%   |
| AuthenTec                          | 4         | 3.03%   |
| Upek                               | 3         | 2.27%   |
| LighTuning Technology              | 3         | 2.27%   |
| STMicroelectronics                 | 1         | 0.76%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.76%   |
| Focal-systems.Corp                 | 1         | 0.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 25        | 18.94%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 6.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 5.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 5.3%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 4.55%   |
| Elan ELAN:ARM-M4                                                           | 6         | 4.55%   |
| Synaptics WBDI                                                             | 5         | 3.79%   |
| Synaptics UWP WBDI                                                         | 5         | 3.79%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 3.03%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.03%   |
| Validity Sensors VFS491                                                    | 3         | 2.27%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.27%   |
| Synaptics UWP WBDI Device                                                  | 3         | 2.27%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.27%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.52%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.52%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 1.52%   |
| Synaptics  WBDI                                                            | 2         | 1.52%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.52%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.76%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.76%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.76%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.76%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.76%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.76%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.76%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.76%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.76%   |
| AuthenTec AES2810                                                          | 1         | 0.76%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 38.18%  |
| Alcor Micro           | 20        | 36.36%  |
| Upek                  | 4         | 7.27%   |
| OmniKey               | 2         | 3.64%   |
| BIT4ID                | 2         | 3.64%   |
| SCM Microsystems      | 1         | 1.82%   |
| O2 Micro              | 1         | 1.82%   |
| Lenovo                | 1         | 1.82%   |
| Gemalto (was Gemplus) | 1         | 1.82%   |
| Clay Logic            | 1         | 1.82%   |
| Advanced Card Systems | 1         | 1.82%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 36.36%  |
| Broadcom 58200                                                               | 8         | 14.55%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 9.09%   |
| Broadcom 5880                                                                | 5         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 7.27%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.45%   |
| BIT4ID miniLector EVO                                                        | 2         | 3.64%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 1.82%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.82%   |
| OmniKey CardMan 1021                                                         | 1         | 1.82%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.82%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 1.82%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.82%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.82%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.82%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 694       | 67.97%  |
| 1     | 261       | 25.56%  |
| 2     | 57        | 5.58%   |
| 3     | 7         | 0.69%   |
| 9     | 1         | 0.1%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 131       | 33.76%  |
| Graphics card            | 59        | 15.21%  |
| Chipcard                 | 48        | 12.37%  |
| Net/wireless             | 45        | 11.6%   |
| Camera                   | 27        | 6.96%   |
| Multimedia controller    | 20        | 5.15%   |
| Unassigned class         | 14        | 3.61%   |
| Bluetooth                | 12        | 3.09%   |
| Sound                    | 8         | 2.06%   |
| Communication controller | 8         | 2.06%   |
| Storage                  | 4         | 1.03%   |
| Network                  | 3         | 0.77%   |
| Net/ethernet             | 3         | 0.77%   |
| Card reader              | 3         | 0.77%   |
| Modem                    | 2         | 0.52%   |
| Dvb card                 | 1         | 0.26%   |


Debian 12 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 12.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_12/Desktop/README.md) and [notebooks](/Dist/Debian_12/Notebook/README.md).

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

Total: 805

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0HC3G4 A00                  | Mini pc     | [c111f0f4be](https://linux-hardware.org/?probe=c111f0f4be) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | Notebook    | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [b2d81d6e67](https://linux-hardware.org/?probe=b2d81d6e67) | Jun 30, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [befac7b8de](https://linux-hardware.org/?probe=befac7b8de) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [2b5e40efaa](https://linux-hardware.org/?probe=2b5e40efaa) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | Notebook    | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [9fc143ab80](https://linux-hardware.org/?probe=9fc143ab80) | Jun 30, 2023 |
| Dell          | G3 3590                     | Notebook    | [5c7312fed9](https://linux-hardware.org/?probe=5c7312fed9) | Jun 30, 2023 |
| ASRock        | G31M-GS                     | Desktop     | [3bd67e0f9f](https://linux-hardware.org/?probe=3bd67e0f9f) | Jun 30, 2023 |
| Lenovo        | ThinkPad L512 44444NG       | Notebook    | [300a79aa88](https://linux-hardware.org/?probe=300a79aa88) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Dell          | Inspiron 7373               | Convertible | [e7edaad244](https://linux-hardware.org/?probe=e7edaad244) | Jun 30, 2023 |
| ASUSTek       | K52F                        | Notebook    | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [a3de72d73c](https://linux-hardware.org/?probe=a3de72d73c) | Jun 29, 2023 |
| Dell          | 0PU052                      | Desktop     | [b4fde65c68](https://linux-hardware.org/?probe=b4fde65c68) | Jun 29, 2023 |
| Lenovo        | ThinkPad T440p 2000CT0      | Notebook    | [10c852dc38](https://linux-hardware.org/?probe=10c852dc38) | Jun 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [25a1aaf938](https://linux-hardware.org/?probe=25a1aaf938) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | Notebook    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [a996f391dc](https://linux-hardware.org/?probe=a996f391dc) | Jun 29, 2023 |
| Dell          | Latitude 3500               | Notebook    | [e1831984f8](https://linux-hardware.org/?probe=e1831984f8) | Jun 28, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d6823d5ec7](https://linux-hardware.org/?probe=d6823d5ec7) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| HP            | Pavilion dv6                | Notebook    | [7fe9e439c0](https://linux-hardware.org/?probe=7fe9e439c0) | Jun 28, 2023 |
| Aquarius      | NS585                       | Notebook    | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [04d1ab025a](https://linux-hardware.org/?probe=04d1ab025a) | Jun 28, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | Notebook    | [56eef68e89](https://linux-hardware.org/?probe=56eef68e89) | Jun 28, 2023 |
| OEM           | Unknown                     | Desktop     | [0448bbee67](https://linux-hardware.org/?probe=0448bbee67) | Jun 28, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [1c07c9f0b8](https://linux-hardware.org/?probe=1c07c9f0b8) | Jun 28, 2023 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [fff4bc4f46](https://linux-hardware.org/?probe=fff4bc4f46) | Jun 28, 2023 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [bc9d733b89](https://linux-hardware.org/?probe=bc9d733b89) | Jun 27, 2023 |
| Dell          | 0H1TR9 A00                  | All in one  | [b4be8eaa80](https://linux-hardware.org/?probe=b4be8eaa80) | Jun 27, 2023 |
| Lenovo        | 1048 SDK0K17763 WIN 1801... | Desktop     | [d903758323](https://linux-hardware.org/?probe=d903758323) | Jun 27, 2023 |
| Supermicro    | X9DRT                       | Server      | [807e745cb1](https://linux-hardware.org/?probe=807e745cb1) | Jun 27, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [765d0708eb](https://linux-hardware.org/?probe=765d0708eb) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| Dell          | 0PU052                      | Desktop     | [34eaa7185d](https://linux-hardware.org/?probe=34eaa7185d) | Jun 26, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [7b60ea1445](https://linux-hardware.org/?probe=7b60ea1445) | Jun 26, 2023 |
| Gigabyte      | H310MD2P-CF                 | Desktop     | [1ad319cfc7](https://linux-hardware.org/?probe=1ad319cfc7) | Jun 26, 2023 |
| HP            | EliteBook 835 13 inch G1... | Notebook    | [e43818af40](https://linux-hardware.org/?probe=e43818af40) | Jun 26, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [87962635d3](https://linux-hardware.org/?probe=87962635d3) | Jun 26, 2023 |
| LG Electro... | 17Z90R-G.AD79F              | Notebook    | [0d641b84fe](https://linux-hardware.org/?probe=0d641b84fe) | Jun 26, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [0ee45fd3e8](https://linux-hardware.org/?probe=0ee45fd3e8) | Jun 26, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [b8a3042b9d](https://linux-hardware.org/?probe=b8a3042b9d) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| Aquarius      | NS585                       | Notebook    | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [f5c0a2fd49](https://linux-hardware.org/?probe=f5c0a2fd49) | Jun 26, 2023 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [0dc147bd7c](https://linux-hardware.org/?probe=0dc147bd7c) | Jun 26, 2023 |
| Leader        | SC8-PRO                     | Stick pc    | [ad54f075f6](https://linux-hardware.org/?probe=ad54f075f6) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 34766TT       | Notebook    | [06ad7b4a25](https://linux-hardware.org/?probe=06ad7b4a25) | Jun 26, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [dfc817892b](https://linux-hardware.org/?probe=dfc817892b) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [ed89cd0d05](https://linux-hardware.org/?probe=ed89cd0d05) | Jun 26, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [62665eec25](https://linux-hardware.org/?probe=62665eec25) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0a233c34b3](https://linux-hardware.org/?probe=0a233c34b3) | Jun 26, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [3ccdaf3c82](https://linux-hardware.org/?probe=3ccdaf3c82) | Jun 26, 2023 |
| ASUSTek       | E403SA                      | Notebook    | [bdc47269c3](https://linux-hardware.org/?probe=bdc47269c3) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| JINGSHA       | Unknown                     | Desktop     | [2ae6ac9599](https://linux-hardware.org/?probe=2ae6ac9599) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| Biostar       | X370GTN                     | Desktop     | [80b2b1d180](https://linux-hardware.org/?probe=80b2b1d180) | Jun 25, 2023 |
| Intel         | H55                         | Desktop     | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Dell          | Latitude E6430              | Notebook    | [be9b6c75da](https://linux-hardware.org/?probe=be9b6c75da) | Jun 25, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a87db20468](https://linux-hardware.org/?probe=a87db20468) | Jun 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [a7df01b153](https://linux-hardware.org/?probe=a7df01b153) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | Notebook    | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| HP            | 872E                        | Mini pc     | [d59093e79e](https://linux-hardware.org/?probe=d59093e79e) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [46a7aaf9f1](https://linux-hardware.org/?probe=46a7aaf9f1) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| Irbis         | NB131                       | Convertible | [9898b376fe](https://linux-hardware.org/?probe=9898b376fe) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | Notebook    | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [46d748a0a1](https://linux-hardware.org/?probe=46d748a0a1) | Jun 23, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [9ed9153958](https://linux-hardware.org/?probe=9ed9153958) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [51b5eb0fa2](https://linux-hardware.org/?probe=51b5eb0fa2) | Jun 23, 2023 |
| Dell          | 0HC3G4 A00                  | Mini pc     | [23723983da](https://linux-hardware.org/?probe=23723983da) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [655b20a34b](https://linux-hardware.org/?probe=655b20a34b) | Jun 23, 2023 |
| Lenovo        | ThinkPad X230 2325SRQ       | Notebook    | [fd42553eea](https://linux-hardware.org/?probe=fd42553eea) | Jun 22, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| ASUSTek       | X45U                        | Notebook    | [63a491a160](https://linux-hardware.org/?probe=63a491a160) | Jun 22, 2023 |
| Acer          | Aspire X1700                | Desktop     | [aac17ef2f2](https://linux-hardware.org/?probe=aac17ef2f2) | Jun 22, 2023 |
| AMI           | Intel                       | Desktop     | [1a4a632d56](https://linux-hardware.org/?probe=1a4a632d56) | Jun 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [abbb1b897d](https://linux-hardware.org/?probe=abbb1b897d) | Jun 22, 2023 |
| ASRock        | NUC-TGL                     | Desktop     | [6dcb1eb43d](https://linux-hardware.org/?probe=6dcb1eb43d) | Jun 22, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b8e19a16f9](https://linux-hardware.org/?probe=b8e19a16f9) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e32510f57](https://linux-hardware.org/?probe=2e32510f57) | Jun 21, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [9841bf505c](https://linux-hardware.org/?probe=9841bf505c) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [9f3829c99f](https://linux-hardware.org/?probe=9f3829c99f) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [379e3473e2](https://linux-hardware.org/?probe=379e3473e2) | Jun 21, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8a2a9fd293](https://linux-hardware.org/?probe=8a2a9fd293) | Jun 21, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d661316023](https://linux-hardware.org/?probe=d661316023) | Jun 21, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [b652abc634](https://linux-hardware.org/?probe=b652abc634) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [abe5412cf6](https://linux-hardware.org/?probe=abe5412cf6) | Jun 21, 2023 |
| HP            | 1588h                       | Desktop     | [f08e230cd3](https://linux-hardware.org/?probe=f08e230cd3) | Jun 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [197d2f4c7c](https://linux-hardware.org/?probe=197d2f4c7c) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8a61f834dd](https://linux-hardware.org/?probe=8a61f834dd) | Jun 21, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [10d1aeda8b](https://linux-hardware.org/?probe=10d1aeda8b) | Jun 21, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [0aa3b8d433](https://linux-hardware.org/?probe=0aa3b8d433) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [c7e1912b55](https://linux-hardware.org/?probe=c7e1912b55) | Jun 20, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [53f708517b](https://linux-hardware.org/?probe=53f708517b) | Jun 20, 2023 |
| Google        | Stout                       | Notebook    | [cb67ad655e](https://linux-hardware.org/?probe=cb67ad655e) | Jun 20, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [bf19dd1c4b](https://linux-hardware.org/?probe=bf19dd1c4b) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1742a525de](https://linux-hardware.org/?probe=1742a525de) | Jun 20, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [cfc9cd338e](https://linux-hardware.org/?probe=cfc9cd338e) | Jun 20, 2023 |
| Dell          | 0RW203                      | Desktop     | [6872d8e6c5](https://linux-hardware.org/?probe=6872d8e6c5) | Jun 20, 2023 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [9b75bc9f7e](https://linux-hardware.org/?probe=9b75bc9f7e) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [c3f77cf346](https://linux-hardware.org/?probe=c3f77cf346) | Jun 20, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [4c2f50a608](https://linux-hardware.org/?probe=4c2f50a608) | Jun 19, 2023 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [fe617b45f8](https://linux-hardware.org/?probe=fe617b45f8) | Jun 19, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [c40116d0de](https://linux-hardware.org/?probe=c40116d0de) | Jun 19, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [b0f066ab7e](https://linux-hardware.org/?probe=b0f066ab7e) | Jun 18, 2023 |
| Dell          | Latitude E7450              | Notebook    | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| Intel         | H81                         | Desktop     | [5cda43eb30](https://linux-hardware.org/?probe=5cda43eb30) | Jun 18, 2023 |
| Xunlong       | Orange Pi Lite              | Soc         | [f7e41df8d6](https://linux-hardware.org/?probe=f7e41df8d6) | Jun 18, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [e7fdb650cd](https://linux-hardware.org/?probe=e7fdb650cd) | Jun 18, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e4c418382a](https://linux-hardware.org/?probe=e4c418382a) | Jun 17, 2023 |
| HP            | 2B38                        | Desktop     | [b84e03e083](https://linux-hardware.org/?probe=b84e03e083) | Jun 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [26b4c05332](https://linux-hardware.org/?probe=26b4c05332) | Jun 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S10T0... | Notebook    | [a3dd392c51](https://linux-hardware.org/?probe=a3dd392c51) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [c60ca4bcc4](https://linux-hardware.org/?probe=c60ca4bcc4) | Jun 17, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f8aca3e72](https://linux-hardware.org/?probe=0f8aca3e72) | Jun 17, 2023 |
| Unknown       | Unknown                     | Soc         | [92f385e306](https://linux-hardware.org/?probe=92f385e306) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| ASUSTek       | P5K Premium                 | Desktop     | [dddb2b8bdf](https://linux-hardware.org/?probe=dddb2b8bdf) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [444f324394](https://linux-hardware.org/?probe=444f324394) | Jun 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [6767dd6968](https://linux-hardware.org/?probe=6767dd6968) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | Notebook    | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| Dell          | 0XM089 A00                  | Server      | [c52b7c8444](https://linux-hardware.org/?probe=c52b7c8444) | Jun 16, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [ec1b8c4ef4](https://linux-hardware.org/?probe=ec1b8c4ef4) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [f1294224ee](https://linux-hardware.org/?probe=f1294224ee) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [9b8a05d0f9](https://linux-hardware.org/?probe=9b8a05d0f9) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | Notebook    | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2db615249d](https://linux-hardware.org/?probe=2db615249d) | Jun 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [138e2807af](https://linux-hardware.org/?probe=138e2807af) | Jun 15, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [5d8061c350](https://linux-hardware.org/?probe=5d8061c350) | Jun 15, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [f7e4f16796](https://linux-hardware.org/?probe=f7e4f16796) | Jun 15, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [91787f8dfb](https://linux-hardware.org/?probe=91787f8dfb) | Jun 15, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [5ec4b74af2](https://linux-hardware.org/?probe=5ec4b74af2) | Jun 15, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [a708d51992](https://linux-hardware.org/?probe=a708d51992) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| HP            | 2820h                       | Desktop     | [77b54a0343](https://linux-hardware.org/?probe=77b54a0343) | Jun 14, 2023 |
| HP            | 2820h                       | Desktop     | [40e65d7a30](https://linux-hardware.org/?probe=40e65d7a30) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [294cbcd9cd](https://linux-hardware.org/?probe=294cbcd9cd) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [11fa244fa5](https://linux-hardware.org/?probe=11fa244fa5) | Jun 14, 2023 |
| Intel         | DG41TY AAE47335-203         | Desktop     | [4f1d844d48](https://linux-hardware.org/?probe=4f1d844d48) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [3117d89b20](https://linux-hardware.org/?probe=3117d89b20) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [3feaf0bd19](https://linux-hardware.org/?probe=3feaf0bd19) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [5fc5be3367](https://linux-hardware.org/?probe=5fc5be3367) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [aba284328c](https://linux-hardware.org/?probe=aba284328c) | Jun 14, 2023 |
| Dell          | XPS M1530                   | Notebook    | [252d777fa0](https://linux-hardware.org/?probe=252d777fa0) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [b899120507](https://linux-hardware.org/?probe=b899120507) | Jun 14, 2023 |
| Acer          | TravelMate 5742Z            | Notebook    | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [051cebacd1](https://linux-hardware.org/?probe=051cebacd1) | Jun 14, 2023 |
| Dell          | Latitude 7480               | Notebook    | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [18a5adccb6](https://linux-hardware.org/?probe=18a5adccb6) | Jun 14, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [221a4431e2](https://linux-hardware.org/?probe=221a4431e2) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [85abf9e475](https://linux-hardware.org/?probe=85abf9e475) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [40df819ebb](https://linux-hardware.org/?probe=40df819ebb) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [9ed186ba56](https://linux-hardware.org/?probe=9ed186ba56) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f444f44a49](https://linux-hardware.org/?probe=f444f44a49) | Jun 13, 2023 |
| Samsung       | 750XED                      | Notebook    | [8997330d6a](https://linux-hardware.org/?probe=8997330d6a) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [2a4d82175c](https://linux-hardware.org/?probe=2a4d82175c) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [1df32db310](https://linux-hardware.org/?probe=1df32db310) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [9949220d98](https://linux-hardware.org/?probe=9949220d98) | Jun 13, 2023 |
| Lenovo        | ThinkCentre M55p 8808D8U    | Desktop     | [d801927769](https://linux-hardware.org/?probe=d801927769) | Jun 13, 2023 |
| Shuttle       | FM10 V10                    | Desktop     | [f1396e2cce](https://linux-hardware.org/?probe=f1396e2cce) | Jun 13, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [d85ad203ff](https://linux-hardware.org/?probe=d85ad203ff) | Jun 13, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [06c6c417c9](https://linux-hardware.org/?probe=06c6c417c9) | Jun 13, 2023 |
| ECS           | G31T-M9                     | Desktop     | [ba2a738c96](https://linux-hardware.org/?probe=ba2a738c96) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | Notebook    | [4c34707bef](https://linux-hardware.org/?probe=4c34707bef) | Jun 13, 2023 |
| Sony          | SVE11116FGW                 | Notebook    | [a048cbcdeb](https://linux-hardware.org/?probe=a048cbcdeb) | Jun 13, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [86ab821b84](https://linux-hardware.org/?probe=86ab821b84) | Jun 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f578df0eb9](https://linux-hardware.org/?probe=f578df0eb9) | Jun 13, 2023 |
| Intel         | JSL MRD                     | Desktop     | [8943f697bc](https://linux-hardware.org/?probe=8943f697bc) | Jun 13, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [a515b0dbf7](https://linux-hardware.org/?probe=a515b0dbf7) | Jun 12, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [20b91b813f](https://linux-hardware.org/?probe=20b91b813f) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [dad1ea59a4](https://linux-hardware.org/?probe=dad1ea59a4) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [7a4183e095](https://linux-hardware.org/?probe=7a4183e095) | Jun 12, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [a810b267ef](https://linux-hardware.org/?probe=a810b267ef) | Jun 12, 2023 |
| NEC Comput... | VERSA P91 series            | Notebook    | [2051db7014](https://linux-hardware.org/?probe=2051db7014) | Jun 12, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [9ac2f1ed7e](https://linux-hardware.org/?probe=9ac2f1ed7e) | Jun 12, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [f39a1874f7](https://linux-hardware.org/?probe=f39a1874f7) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f30be06897](https://linux-hardware.org/?probe=f30be06897) | Jun 11, 2023 |
| Dell          | Inspiron 5481               | Convertible | [ff9d9d8929](https://linux-hardware.org/?probe=ff9d9d8929) | Jun 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [756a317dd6](https://linux-hardware.org/?probe=756a317dd6) | Jun 11, 2023 |
| Lenovo        | G565 4385                   | Notebook    | [2fd61f3fc5](https://linux-hardware.org/?probe=2fd61f3fc5) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0aeb6a400a](https://linux-hardware.org/?probe=0aeb6a400a) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | Notebook    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| ASUSTek       | P7H55D-M PRO                | Desktop     | [6049b3d69d](https://linux-hardware.org/?probe=6049b3d69d) | Jun 10, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [88955e82f2](https://linux-hardware.org/?probe=88955e82f2) | Jun 10, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b3e01203b0](https://linux-hardware.org/?probe=b3e01203b0) | Jun 10, 2023 |
| Dell          | Latitude 5480               | Notebook    | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| ECS           | G31T-M9                     | Desktop     | [d8ca98b733](https://linux-hardware.org/?probe=d8ca98b733) | Jun 09, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [fb883c82bc](https://linux-hardware.org/?probe=fb883c82bc) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b2c39972c2](https://linux-hardware.org/?probe=b2c39972c2) | Jun 09, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [e54b5ce7da](https://linux-hardware.org/?probe=e54b5ce7da) | Jun 09, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [576a624a1b](https://linux-hardware.org/?probe=576a624a1b) | Jun 09, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [f1100ce875](https://linux-hardware.org/?probe=f1100ce875) | Jun 08, 2023 |
| ASUSTek       | M4A78T-E                    | Desktop     | [fa22309a62](https://linux-hardware.org/?probe=fa22309a62) | Jun 08, 2023 |
| HP            | G62                         | Notebook    | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [4797a4c2f9](https://linux-hardware.org/?probe=4797a4c2f9) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [53833409d1](https://linux-hardware.org/?probe=53833409d1) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [ef71a1641b](https://linux-hardware.org/?probe=ef71a1641b) | Jun 08, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [b2c6247a0e](https://linux-hardware.org/?probe=b2c6247a0e) | Jun 07, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2ff7b71aed](https://linux-hardware.org/?probe=2ff7b71aed) | Jun 06, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [10ecbb2117](https://linux-hardware.org/?probe=10ecbb2117) | Jun 06, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [626a677331](https://linux-hardware.org/?probe=626a677331) | Jun 06, 2023 |
| ECS           | G31T-M9                     | Desktop     | [8bb444bdd6](https://linux-hardware.org/?probe=8bb444bdd6) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [2ec944c5d0](https://linux-hardware.org/?probe=2ec944c5d0) | Jun 05, 2023 |
| Aquarius      | NS585                       | Notebook    | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| Fujitsu       | FMVNA4NE-                   | Notebook    | [b1c1176a5b](https://linux-hardware.org/?probe=b1c1176a5b) | Jun 05, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8896a460d4](https://linux-hardware.org/?probe=8896a460d4) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [d392dff6bb](https://linux-hardware.org/?probe=d392dff6bb) | Jun 05, 2023 |
| ECS           | G31T-M9                     | Desktop     | [630360ab38](https://linux-hardware.org/?probe=630360ab38) | Jun 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [991c5472ac](https://linux-hardware.org/?probe=991c5472ac) | Jun 05, 2023 |
| Unknown       | Unknown                     | Soc         | [9cb76f0184](https://linux-hardware.org/?probe=9cb76f0184) | Jun 04, 2023 |
| Unknown       | Unknown                     | Soc         | [7e2052896c](https://linux-hardware.org/?probe=7e2052896c) | Jun 04, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| Acer          | Aspire A115-31              | Notebook    | [338f025bce](https://linux-hardware.org/?probe=338f025bce) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [5387bcbf7d](https://linux-hardware.org/?probe=5387bcbf7d) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [881df8f45c](https://linux-hardware.org/?probe=881df8f45c) | Jun 03, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0dd3be3300](https://linux-hardware.org/?probe=0dd3be3300) | Jun 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [8933e1b0ad](https://linux-hardware.org/?probe=8933e1b0ad) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [2f7bb21988](https://linux-hardware.org/?probe=2f7bb21988) | Jun 02, 2023 |
| HC Technol... | HCAR357-NR                  | Desktop     | [58f698b10a](https://linux-hardware.org/?probe=58f698b10a) | Jun 02, 2023 |
| MSI           | G31TM-P21                   | Desktop     | [964377db0b](https://linux-hardware.org/?probe=964377db0b) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [853bd25ca5](https://linux-hardware.org/?probe=853bd25ca5) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3a9fb692f1](https://linux-hardware.org/?probe=3a9fb692f1) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [9b549fe65a](https://linux-hardware.org/?probe=9b549fe65a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [db685837d0](https://linux-hardware.org/?probe=db685837d0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [968b38e0b9](https://linux-hardware.org/?probe=968b38e0b9) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [c9a04d8da0](https://linux-hardware.org/?probe=c9a04d8da0) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [238931757a](https://linux-hardware.org/?probe=238931757a) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e190e991a6](https://linux-hardware.org/?probe=e190e991a6) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0816e77499](https://linux-hardware.org/?probe=0816e77499) | Jun 02, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [ff143ac918](https://linux-hardware.org/?probe=ff143ac918) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | Notebook    | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [07e5342fb8](https://linux-hardware.org/?probe=07e5342fb8) | Jun 02, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [f3b666f725](https://linux-hardware.org/?probe=f3b666f725) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1cf7ec0aa5](https://linux-hardware.org/?probe=1cf7ec0aa5) | Jun 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [7f9d81bd57](https://linux-hardware.org/?probe=7f9d81bd57) | Jun 01, 2023 |
| Aquarius      | NS585                       | Notebook    | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| Aquarius      | NS585                       | Notebook    | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| Unknown       | Unknown                     | Notebook    | [412c6d4af8](https://linux-hardware.org/?probe=412c6d4af8) | May 31, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| ECS           | G31T-M9                     | Desktop     | [f227323587](https://linux-hardware.org/?probe=f227323587) | May 31, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [f2c67ed13d](https://linux-hardware.org/?probe=f2c67ed13d) | May 31, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [c56271ea6a](https://linux-hardware.org/?probe=c56271ea6a) | May 30, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a0ffb7fd40](https://linux-hardware.org/?probe=a0ffb7fd40) | May 30, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [446d026ac1](https://linux-hardware.org/?probe=446d026ac1) | May 30, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [66de62e958](https://linux-hardware.org/?probe=66de62e958) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [80c2e03e4e](https://linux-hardware.org/?probe=80c2e03e4e) | May 29, 2023 |
| ECS           | G31T-M9                     | Desktop     | [8f4cd5b132](https://linux-hardware.org/?probe=8f4cd5b132) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ffe8469edc](https://linux-hardware.org/?probe=ffe8469edc) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e9f274ad89](https://linux-hardware.org/?probe=e9f274ad89) | May 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [62a5559050](https://linux-hardware.org/?probe=62a5559050) | May 29, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [a9c147d701](https://linux-hardware.org/?probe=a9c147d701) | May 29, 2023 |
| ASRock        | J4105-ITX                   | Desktop     | [570bc894da](https://linux-hardware.org/?probe=570bc894da) | May 29, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9e0fc265de](https://linux-hardware.org/?probe=9e0fc265de) | May 29, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Unknown       | Unknown                     | Soc         | [0f85a652ad](https://linux-hardware.org/?probe=0f85a652ad) | May 28, 2023 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [5d4d7c7ef4](https://linux-hardware.org/?probe=5d4d7c7ef4) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [447ea38d26](https://linux-hardware.org/?probe=447ea38d26) | May 27, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [57dcd55314](https://linux-hardware.org/?probe=57dcd55314) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [bcdfc5a2bf](https://linux-hardware.org/?probe=bcdfc5a2bf) | May 27, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [68cb8bdf49](https://linux-hardware.org/?probe=68cb8bdf49) | May 27, 2023 |
| Aquarius      | NS585                       | Notebook    | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [6b8c135c5d](https://linux-hardware.org/?probe=6b8c135c5d) | May 27, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4862d28e3f](https://linux-hardware.org/?probe=4862d28e3f) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [92836191e9](https://linux-hardware.org/?probe=92836191e9) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [0d449702e3](https://linux-hardware.org/?probe=0d449702e3) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [a5fbe0c1ba](https://linux-hardware.org/?probe=a5fbe0c1ba) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [f9fd99a8b7](https://linux-hardware.org/?probe=f9fd99a8b7) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6c87853f8c](https://linux-hardware.org/?probe=6c87853f8c) | May 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9b93292db9](https://linux-hardware.org/?probe=9b93292db9) | May 26, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [138348e6eb](https://linux-hardware.org/?probe=138348e6eb) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [388eed2f8e](https://linux-hardware.org/?probe=388eed2f8e) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [1bc02afebc](https://linux-hardware.org/?probe=1bc02afebc) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [485617123a](https://linux-hardware.org/?probe=485617123a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [d1933e40f4](https://linux-hardware.org/?probe=d1933e40f4) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [db84f366d0](https://linux-hardware.org/?probe=db84f366d0) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4d7f19ec5b](https://linux-hardware.org/?probe=4d7f19ec5b) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [adb7acad13](https://linux-hardware.org/?probe=adb7acad13) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [897503110a](https://linux-hardware.org/?probe=897503110a) | May 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7ddbfedd32](https://linux-hardware.org/?probe=7ddbfedd32) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [96202d100a](https://linux-hardware.org/?probe=96202d100a) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [faa830a26c](https://linux-hardware.org/?probe=faa830a26c) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [03d0e0d8d7](https://linux-hardware.org/?probe=03d0e0d8d7) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f76e433d68](https://linux-hardware.org/?probe=f76e433d68) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [610a5f2bb3](https://linux-hardware.org/?probe=610a5f2bb3) | May 26, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f10a5bd0f9](https://linux-hardware.org/?probe=f10a5bd0f9) | May 26, 2023 |
| Dell          | Latitude 3520               | Notebook    | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| eMachines     | E725                        | Notebook    | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [7a40f97a17](https://linux-hardware.org/?probe=7a40f97a17) | May 26, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [66ff968642](https://linux-hardware.org/?probe=66ff968642) | May 25, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [387793dfb2](https://linux-hardware.org/?probe=387793dfb2) | May 25, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [142c9c4384](https://linux-hardware.org/?probe=142c9c4384) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [7b4b86c1ea](https://linux-hardware.org/?probe=7b4b86c1ea) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [15c2f741bf](https://linux-hardware.org/?probe=15c2f741bf) | May 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [45ac56e70c](https://linux-hardware.org/?probe=45ac56e70c) | May 25, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ac28804681](https://linux-hardware.org/?probe=ac28804681) | May 25, 2023 |
| ASUSTek       | E35M1-M                     | Desktop     | [c62d813dd9](https://linux-hardware.org/?probe=c62d813dd9) | May 24, 2023 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [3898315bde](https://linux-hardware.org/?probe=3898315bde) | May 24, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [e147bb9d5e](https://linux-hardware.org/?probe=e147bb9d5e) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [17f5577d63](https://linux-hardware.org/?probe=17f5577d63) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [d06b734926](https://linux-hardware.org/?probe=d06b734926) | May 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3ee24557f7](https://linux-hardware.org/?probe=3ee24557f7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| ASRock        | H270 Performance            | Desktop     | [b3f7fdc329](https://linux-hardware.org/?probe=b3f7fdc329) | May 23, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [d784b0822d](https://linux-hardware.org/?probe=d784b0822d) | May 22, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [91aa0c376a](https://linux-hardware.org/?probe=91aa0c376a) | May 22, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [98f94bccb6](https://linux-hardware.org/?probe=98f94bccb6) | May 22, 2023 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [71fc64d684](https://linux-hardware.org/?probe=71fc64d684) | May 22, 2023 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [b2ed9436de](https://linux-hardware.org/?probe=b2ed9436de) | May 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d4460792c6](https://linux-hardware.org/?probe=d4460792c6) | May 21, 2023 |
| Lenovo        | ThinkPad T410s 2904FAG      | Notebook    | [742f2c09c5](https://linux-hardware.org/?probe=742f2c09c5) | May 21, 2023 |
| Terrans Fo... | AMD                         | Notebook    | [8087d42d0e](https://linux-hardware.org/?probe=8087d42d0e) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Unknown       | Unknown                     | Soc         | [d40c7d6729](https://linux-hardware.org/?probe=d40c7d6729) | May 21, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [979f49012c](https://linux-hardware.org/?probe=979f49012c) | May 21, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [f28727e594](https://linux-hardware.org/?probe=f28727e594) | May 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a4528c4521](https://linux-hardware.org/?probe=a4528c4521) | May 20, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Acer          | Aspire 5739G                | Notebook    | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [919ed7f9e1](https://linux-hardware.org/?probe=919ed7f9e1) | May 20, 2023 |
| HP            | 1905                        | Desktop     | [1ce2caa771](https://linux-hardware.org/?probe=1ce2caa771) | May 19, 2023 |
| HP            | 1905                        | Desktop     | [de8cea1b10](https://linux-hardware.org/?probe=de8cea1b10) | May 19, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [51827f5ae5](https://linux-hardware.org/?probe=51827f5ae5) | May 19, 2023 |
| HP            | Elite x2 1013 G3            | Tablet      | [0da06960ac](https://linux-hardware.org/?probe=0da06960ac) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0f034f50a0](https://linux-hardware.org/?probe=0f034f50a0) | May 19, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [cdb86f0326](https://linux-hardware.org/?probe=cdb86f0326) | May 19, 2023 |
| Acer          | Aspire 5253                 | Notebook    | [fa328bbd9c](https://linux-hardware.org/?probe=fa328bbd9c) | May 19, 2023 |
| ASRock        | X299 Taichi XE              | Desktop     | [deae8ee190](https://linux-hardware.org/?probe=deae8ee190) | May 19, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [8c80042f1e](https://linux-hardware.org/?probe=8c80042f1e) | May 19, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [d1e00e62c4](https://linux-hardware.org/?probe=d1e00e62c4) | May 19, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [d4c89434ae](https://linux-hardware.org/?probe=d4c89434ae) | May 18, 2023 |
| Toshiba       | Satellite C855-22N          | Notebook    | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [94bf603662](https://linux-hardware.org/?probe=94bf603662) | May 18, 2023 |
| Aquarius      | NS585                       | Notebook    | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [5e003a073d](https://linux-hardware.org/?probe=5e003a073d) | May 18, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [058907d9d3](https://linux-hardware.org/?probe=058907d9d3) | May 18, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [dce4e8be7c](https://linux-hardware.org/?probe=dce4e8be7c) | May 17, 2023 |
| Acer          | TravelMate X514-51          | Notebook    | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [a65ace49b0](https://linux-hardware.org/?probe=a65ace49b0) | May 17, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [bd8552e2d6](https://linux-hardware.org/?probe=bd8552e2d6) | May 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [b9410e67b1](https://linux-hardware.org/?probe=b9410e67b1) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | Notebook    | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [0fd753db6d](https://linux-hardware.org/?probe=0fd753db6d) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9505c6130c](https://linux-hardware.org/?probe=9505c6130c) | May 16, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [4ea868b4d1](https://linux-hardware.org/?probe=4ea868b4d1) | May 15, 2023 |
| Gigabyte      | B760 AORUS ELITE AX         | Desktop     | [b1ab3ebdd4](https://linux-hardware.org/?probe=b1ab3ebdd4) | May 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c12ae2e393](https://linux-hardware.org/?probe=c12ae2e393) | May 15, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [36cb64f82a](https://linux-hardware.org/?probe=36cb64f82a) | May 15, 2023 |
| Unknown       | Unknown                     | Soc         | [8fa49f6af8](https://linux-hardware.org/?probe=8fa49f6af8) | May 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [878a94a7c7](https://linux-hardware.org/?probe=878a94a7c7) | May 13, 2023 |
| Gigabyte      | Z690 AERO G                 | Desktop     | [a199ff9b72](https://linux-hardware.org/?probe=a199ff9b72) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [a25f9e8d93](https://linux-hardware.org/?probe=a25f9e8d93) | May 13, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [d2ba323017](https://linux-hardware.org/?probe=d2ba323017) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a2a47b4c35](https://linux-hardware.org/?probe=a2a47b4c35) | May 12, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [de18c72638](https://linux-hardware.org/?probe=de18c72638) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2a1dfd0d0c](https://linux-hardware.org/?probe=2a1dfd0d0c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [5ab21854e6](https://linux-hardware.org/?probe=5ab21854e6) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [c5c05f7e4c](https://linux-hardware.org/?probe=c5c05f7e4c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | Notebook    | [d90b0e6626](https://linux-hardware.org/?probe=d90b0e6626) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | Notebook    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [d835755922](https://linux-hardware.org/?probe=d835755922) | May 12, 2023 |
| HP            | ProBook 6470b               | Notebook    | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [ba177fa007](https://linux-hardware.org/?probe=ba177fa007) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [bdcd2a3f9c](https://linux-hardware.org/?probe=bdcd2a3f9c) | May 12, 2023 |
| HP            | 829A                        | Mini pc     | [e51b2da826](https://linux-hardware.org/?probe=e51b2da826) | May 12, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [92a39a22a2](https://linux-hardware.org/?probe=92a39a22a2) | May 12, 2023 |
| Dell          | XPS 9315                    | Notebook    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [72aed73d34](https://linux-hardware.org/?probe=72aed73d34) | May 11, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [8ed39df8c1](https://linux-hardware.org/?probe=8ed39df8c1) | May 10, 2023 |
| Dell          | Precision 5520              | Notebook    | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [0625860f59](https://linux-hardware.org/?probe=0625860f59) | May 10, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [0f4b4bd536](https://linux-hardware.org/?probe=0f4b4bd536) | May 10, 2023 |
| ECS           | G31T-M9                     | Desktop     | [25fd5432f0](https://linux-hardware.org/?probe=25fd5432f0) | May 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [c3902a3649](https://linux-hardware.org/?probe=c3902a3649) | May 10, 2023 |
| Supermicro    | X9DRW                       | Server      | [a36aa5e1ee](https://linux-hardware.org/?probe=a36aa5e1ee) | May 10, 2023 |
| Supermicro    | X8DTU                       | Server      | [c3f047a095](https://linux-hardware.org/?probe=c3f047a095) | May 10, 2023 |
| Supermicro    | X8DTU                       | Server      | [5898cc1b65](https://linux-hardware.org/?probe=5898cc1b65) | May 10, 2023 |
| ASRock        | H470M-HVS                   | Desktop     | [e61f99e96e](https://linux-hardware.org/?probe=e61f99e96e) | May 10, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [b904defc14](https://linux-hardware.org/?probe=b904defc14) | May 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [9b21cbbca0](https://linux-hardware.org/?probe=9b21cbbca0) | May 09, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [c4c4a1fe74](https://linux-hardware.org/?probe=c4c4a1fe74) | May 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [1f874eaf6d](https://linux-hardware.org/?probe=1f874eaf6d) | May 08, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [401db07b93](https://linux-hardware.org/?probe=401db07b93) | May 08, 2023 |
| ASRock        | B760 Pro RS/D4              | Desktop     | [cf7cf903c0](https://linux-hardware.org/?probe=cf7cf903c0) | May 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [36334e327a](https://linux-hardware.org/?probe=36334e327a) | May 08, 2023 |
| HP            | 1589                        | Desktop     | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | 829A                        | Mini pc     | [eba2b6ce4e](https://linux-hardware.org/?probe=eba2b6ce4e) | May 06, 2023 |
| GPD           | G1618-04                    | All in one  | [1ac75759ce](https://linux-hardware.org/?probe=1ac75759ce) | May 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e0357a19f3](https://linux-hardware.org/?probe=e0357a19f3) | May 05, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [d016282342](https://linux-hardware.org/?probe=d016282342) | May 05, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [27a1a2533b](https://linux-hardware.org/?probe=27a1a2533b) | May 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [be7c8943ce](https://linux-hardware.org/?probe=be7c8943ce) | May 05, 2023 |
| Unknown       | Unknown                     | Soc         | [043c078caf](https://linux-hardware.org/?probe=043c078caf) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| Avell High... | A40 LIV                     | Notebook    | [5745ae021d](https://linux-hardware.org/?probe=5745ae021d) | May 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4ecbee26b1](https://linux-hardware.org/?probe=4ecbee26b1) | May 04, 2023 |
| Aquarius      | NS585                       | Notebook    | [817d9a6b62](https://linux-hardware.org/?probe=817d9a6b62) | May 04, 2023 |
| Aquarius      | NS585                       | Notebook    | [c629501448](https://linux-hardware.org/?probe=c629501448) | May 03, 2023 |
| Lenovo        | ThinkPad T495 20NK000XBR    | Notebook    | [c7ca4b1477](https://linux-hardware.org/?probe=c7ca4b1477) | May 03, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [0d7dd6a0c1](https://linux-hardware.org/?probe=0d7dd6a0c1) | May 03, 2023 |
| MSI           | Unknown                     | Notebook    | [917d7a7fc9](https://linux-hardware.org/?probe=917d7a7fc9) | May 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| Aquarius      | NS585                       | Notebook    | [e6922e974c](https://linux-hardware.org/?probe=e6922e974c) | May 02, 2023 |
| Lenovo        | SDK0J40705 WIN 342504154... | Desktop     | [60d40b601b](https://linux-hardware.org/?probe=60d40b601b) | May 02, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [5195c623c0](https://linux-hardware.org/?probe=5195c623c0) | May 02, 2023 |
| Toshiba       | Satellite X200              | Notebook    | [e1674b1234](https://linux-hardware.org/?probe=e1674b1234) | May 02, 2023 |
| Google        | Homestar (rev4+)            | Soc         | [9184b7f306](https://linux-hardware.org/?probe=9184b7f306) | May 02, 2023 |
| Sony          | VPCF13WFX                   | Notebook    | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | Notebook    | [fe1b421c9d](https://linux-hardware.org/?probe=fe1b421c9d) | May 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b2adc0ae5](https://linux-hardware.org/?probe=1b2adc0ae5) | May 01, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d85b7a2592](https://linux-hardware.org/?probe=d85b7a2592) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [0a9a85f5f0](https://linux-hardware.org/?probe=0a9a85f5f0) | Apr 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [83b10185e8](https://linux-hardware.org/?probe=83b10185e8) | Apr 29, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [88d774df0d](https://linux-hardware.org/?probe=88d774df0d) | Apr 29, 2023 |
| Aquarius      | NS585                       | Notebook    | [b23696ca41](https://linux-hardware.org/?probe=b23696ca41) | Apr 28, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [dcfa7042da](https://linux-hardware.org/?probe=dcfa7042da) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [5f5809c40f](https://linux-hardware.org/?probe=5f5809c40f) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [d395c6168d](https://linux-hardware.org/?probe=d395c6168d) | Apr 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [2093399e21](https://linux-hardware.org/?probe=2093399e21) | Apr 27, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [2dcf65cf8e](https://linux-hardware.org/?probe=2dcf65cf8e) | Apr 26, 2023 |
| HP            | 8309                        | Desktop     | [cde28bd710](https://linux-hardware.org/?probe=cde28bd710) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | Notebook    | [0234325d36](https://linux-hardware.org/?probe=0234325d36) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [fa21ed6900](https://linux-hardware.org/?probe=fa21ed6900) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [a0983c89d8](https://linux-hardware.org/?probe=a0983c89d8) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [5d9edb6ed4](https://linux-hardware.org/?probe=5d9edb6ed4) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [972d7f6e4a](https://linux-hardware.org/?probe=972d7f6e4a) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [c89bbd8bc0](https://linux-hardware.org/?probe=c89bbd8bc0) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [a6e5a5f3d1](https://linux-hardware.org/?probe=a6e5a5f3d1) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [b6dac5b058](https://linux-hardware.org/?probe=b6dac5b058) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [1563889dac](https://linux-hardware.org/?probe=1563889dac) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [9bdbad2ab7](https://linux-hardware.org/?probe=9bdbad2ab7) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [e30d7dde7b](https://linux-hardware.org/?probe=e30d7dde7b) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [68527a900f](https://linux-hardware.org/?probe=68527a900f) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [ce99b27fb4](https://linux-hardware.org/?probe=ce99b27fb4) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [fc377acae2](https://linux-hardware.org/?probe=fc377acae2) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [ed32f24d6e](https://linux-hardware.org/?probe=ed32f24d6e) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [ea60267a5b](https://linux-hardware.org/?probe=ea60267a5b) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [f71897bf76](https://linux-hardware.org/?probe=f71897bf76) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [7aa4561ca5](https://linux-hardware.org/?probe=7aa4561ca5) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [385ce8cd93](https://linux-hardware.org/?probe=385ce8cd93) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [3fc8926a1a](https://linux-hardware.org/?probe=3fc8926a1a) | Apr 25, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9e6ce2eb71](https://linux-hardware.org/?probe=9e6ce2eb71) | Apr 25, 2023 |
| Aquarius      | NS585                       | Notebook    | [58306d0266](https://linux-hardware.org/?probe=58306d0266) | Apr 25, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [1cd850e8af](https://linux-hardware.org/?probe=1cd850e8af) | Apr 25, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [c5f2fa1c5a](https://linux-hardware.org/?probe=c5f2fa1c5a) | Apr 25, 2023 |
| HP            | ProBook 4520s               | Notebook    | [b680525b61](https://linux-hardware.org/?probe=b680525b61) | Apr 24, 2023 |
| HP            | ProBook 4520s               | Notebook    | [e4ce7aed55](https://linux-hardware.org/?probe=e4ce7aed55) | Apr 24, 2023 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [f3d90b0d4a](https://linux-hardware.org/?probe=f3d90b0d4a) | Apr 23, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [67dc214198](https://linux-hardware.org/?probe=67dc214198) | Apr 23, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [90f041e2a1](https://linux-hardware.org/?probe=90f041e2a1) | Apr 23, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [6d06ef4fa1](https://linux-hardware.org/?probe=6d06ef4fa1) | Apr 23, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Dell          | G15 5520                    | Notebook    | [238c8f53aa](https://linux-hardware.org/?probe=238c8f53aa) | Apr 22, 2023 |
| sunxi         | FriendlyArm NanoPi M1       | Soc         | [3e4c8bce3b](https://linux-hardware.org/?probe=3e4c8bce3b) | Apr 22, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [9c3e15de68](https://linux-hardware.org/?probe=9c3e15de68) | Apr 22, 2023 |
| Dell          | Inspiron 7591 2n1           | Convertible | [9896e8b804](https://linux-hardware.org/?probe=9896e8b804) | Apr 22, 2023 |
| Dell          | Latitude E6330              | Notebook    | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| ASUSTek       | P5N-D                       | Desktop     | [c1af2b9a2c](https://linux-hardware.org/?probe=c1af2b9a2c) | Apr 22, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [8a1e6b7f32](https://linux-hardware.org/?probe=8a1e6b7f32) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [036616c992](https://linux-hardware.org/?probe=036616c992) | Apr 21, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [cb40e046d8](https://linux-hardware.org/?probe=cb40e046d8) | Apr 21, 2023 |
| Toshiba       | Satellite X200              | Notebook    | [15035835d0](https://linux-hardware.org/?probe=15035835d0) | Apr 20, 2023 |
| HP            | Notebook                    | Notebook    | [7174065ed3](https://linux-hardware.org/?probe=7174065ed3) | Apr 20, 2023 |
| Aquarius      | NS585                       | Notebook    | [753222f54f](https://linux-hardware.org/?probe=753222f54f) | Apr 20, 2023 |
| Aquarius      | NS585                       | Notebook    | [be0bc2be01](https://linux-hardware.org/?probe=be0bc2be01) | Apr 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [6090be709d](https://linux-hardware.org/?probe=6090be709d) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | Desktop     | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| Aquarius      | NS585                       | Notebook    | [f7f0464c39](https://linux-hardware.org/?probe=f7f0464c39) | Apr 20, 2023 |
| Aquarius      | NS585                       | Notebook    | [8393642230](https://linux-hardware.org/?probe=8393642230) | Apr 20, 2023 |
| Aquarius      | NS585                       | Notebook    | [a5b9a09e63](https://linux-hardware.org/?probe=a5b9a09e63) | Apr 20, 2023 |
| Unknown       | Unknown                     | Soc         | [909f002719](https://linux-hardware.org/?probe=909f002719) | Apr 20, 2023 |
| Medion        | P17605                      | Notebook    | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| Unknown       | Unknown                     | Soc         | [f07d0fd264](https://linux-hardware.org/?probe=f07d0fd264) | Apr 19, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [e1da556a0b](https://linux-hardware.org/?probe=e1da556a0b) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d669bcc680](https://linux-hardware.org/?probe=d669bcc680) | Apr 19, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [d04a1b7f36](https://linux-hardware.org/?probe=d04a1b7f36) | Apr 19, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [8538987e5c](https://linux-hardware.org/?probe=8538987e5c) | Apr 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [704da241f5](https://linux-hardware.org/?probe=704da241f5) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [e492c87b46](https://linux-hardware.org/?probe=e492c87b46) | Apr 18, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [b15f47258b](https://linux-hardware.org/?probe=b15f47258b) | Apr 18, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [52272d52d3](https://linux-hardware.org/?probe=52272d52d3) | Apr 18, 2023 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [7f0be1868e](https://linux-hardware.org/?probe=7f0be1868e) | Apr 18, 2023 |
| Dell          | 0D4VY1 A00                  | All in one  | [ddbd926522](https://linux-hardware.org/?probe=ddbd926522) | Apr 18, 2023 |
| Dell          | 0R4CNN A02                  | Server      | [237a3cd682](https://linux-hardware.org/?probe=237a3cd682) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| ASUSTek       | G551JW                      | Notebook    | [65f6143e36](https://linux-hardware.org/?probe=65f6143e36) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | Notebook    | [180ef53338](https://linux-hardware.org/?probe=180ef53338) | Apr 18, 2023 |
| Lenovo        | ThinkPad L540 20AUA39QJP    | Notebook    | [fd3b20c292](https://linux-hardware.org/?probe=fd3b20c292) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | Notebook    | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| IBM           | ThinkPad R51 1836Q4U        | Notebook    | [ebec8b53eb](https://linux-hardware.org/?probe=ebec8b53eb) | Apr 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c4d3eabb55](https://linux-hardware.org/?probe=c4d3eabb55) | Apr 17, 2023 |
| Acer          | Swift SF314-41              | Notebook    | [8c42a0aba8](https://linux-hardware.org/?probe=8c42a0aba8) | Apr 16, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [838519057f](https://linux-hardware.org/?probe=838519057f) | Apr 16, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [31557d5e8c](https://linux-hardware.org/?probe=31557d5e8c) | Apr 15, 2023 |
| Unknown       | Unknown                     | Soc         | [018daf402b](https://linux-hardware.org/?probe=018daf402b) | Apr 15, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [3e96076874](https://linux-hardware.org/?probe=3e96076874) | Apr 15, 2023 |
| Acer          | WG43M                       | Desktop     | [a3a49836f9](https://linux-hardware.org/?probe=a3a49836f9) | Apr 15, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | Desktop     | [0ec41c7bd8](https://linux-hardware.org/?probe=0ec41c7bd8) | Apr 14, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [58ec498e8f](https://linux-hardware.org/?probe=58ec498e8f) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [15de4db91b](https://linux-hardware.org/?probe=15de4db91b) | Apr 14, 2023 |
| Dell          | G15 5510                    | Notebook    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| Intel         | Alder Lake-H PCH E1.0G      | Desktop     | [9cf22928fb](https://linux-hardware.org/?probe=9cf22928fb) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [60f7db51fa](https://linux-hardware.org/?probe=60f7db51fa) | Apr 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e9708d65e9](https://linux-hardware.org/?probe=e9708d65e9) | Apr 13, 2023 |
| Dell          | Latitude 5490               | Notebook    | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e0b6eda111](https://linux-hardware.org/?probe=e0b6eda111) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| Aquarius      | NS585                       | Notebook    | [6f4b987640](https://linux-hardware.org/?probe=6f4b987640) | Apr 11, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [8ee190d352](https://linux-hardware.org/?probe=8ee190d352) | Apr 11, 2023 |
| Dell          | Latitude 3320               | Notebook    | [b7c2bb88b3](https://linux-hardware.org/?probe=b7c2bb88b3) | Apr 10, 2023 |
| Dell          | Latitude 3320               | Notebook    | [436e7b8903](https://linux-hardware.org/?probe=436e7b8903) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d24ce5fa44](https://linux-hardware.org/?probe=d24ce5fa44) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | Notebook    | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [8d4288ca33](https://linux-hardware.org/?probe=8d4288ca33) | Apr 09, 2023 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [63945c445c](https://linux-hardware.org/?probe=63945c445c) | Apr 08, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [89966b216e](https://linux-hardware.org/?probe=89966b216e) | Apr 07, 2023 |
| QTQD          | Unknown                     | Desktop     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [a8939164e7](https://linux-hardware.org/?probe=a8939164e7) | Apr 06, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [a639dfd228](https://linux-hardware.org/?probe=a639dfd228) | Apr 06, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [55ea8a957b](https://linux-hardware.org/?probe=55ea8a957b) | Apr 06, 2023 |
| eMachines     | eME728                      | Notebook    | [aff08e7f2d](https://linux-hardware.org/?probe=aff08e7f2d) | Apr 05, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [eadee78860](https://linux-hardware.org/?probe=eadee78860) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | Notebook    | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| System76      | Lemur Pro                   | Notebook    | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| ASUSTek       | VM42                        | Desktop     | [84f848ea21](https://linux-hardware.org/?probe=84f848ea21) | Apr 05, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f4013d94e](https://linux-hardware.org/?probe=6f4013d94e) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [5f9965b18e](https://linux-hardware.org/?probe=5f9965b18e) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [6fb463806f](https://linux-hardware.org/?probe=6fb463806f) | Apr 04, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [0401a50bac](https://linux-hardware.org/?probe=0401a50bac) | Apr 04, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5a83d4ef1e](https://linux-hardware.org/?probe=5a83d4ef1e) | Apr 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [739f49ff7e](https://linux-hardware.org/?probe=739f49ff7e) | Apr 04, 2023 |
| Framework     | Laptop                      | Notebook    | [5bb187865d](https://linux-hardware.org/?probe=5bb187865d) | Apr 04, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [dbbe4bbbc5](https://linux-hardware.org/?probe=dbbe4bbbc5) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1b35a0e9f7](https://linux-hardware.org/?probe=1b35a0e9f7) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [70ed012fb4](https://linux-hardware.org/?probe=70ed012fb4) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [734efd13d3](https://linux-hardware.org/?probe=734efd13d3) | Apr 03, 2023 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [48f07855d1](https://linux-hardware.org/?probe=48f07855d1) | Apr 02, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [cd6a05149d](https://linux-hardware.org/?probe=cd6a05149d) | Apr 02, 2023 |
| Schenker      | XMG CORE (REN/M20)          | Notebook    | [50e9dee7b1](https://linux-hardware.org/?probe=50e9dee7b1) | Apr 01, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [3c509a7075](https://linux-hardware.org/?probe=3c509a7075) | Apr 01, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [0ceb5a3b7c](https://linux-hardware.org/?probe=0ceb5a3b7c) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6fd833b58c](https://linux-hardware.org/?probe=6fd833b58c) | Apr 01, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [35e4f876ca](https://linux-hardware.org/?probe=35e4f876ca) | Mar 31, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fca09d31a2](https://linux-hardware.org/?probe=fca09d31a2) | Mar 31, 2023 |
| ASRock        | B760M Pro RS/D4             | Desktop     | [6a63402e9c](https://linux-hardware.org/?probe=6a63402e9c) | Mar 31, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [3806b33cae](https://linux-hardware.org/?probe=3806b33cae) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [f310910b0e](https://linux-hardware.org/?probe=f310910b0e) | Mar 30, 2023 |
| Fujitsu Si... | D2764-A1 S26361-D2764-A1    | Desktop     | [08af010307](https://linux-hardware.org/?probe=08af010307) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [244ffc8736](https://linux-hardware.org/?probe=244ffc8736) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [82118905ba](https://linux-hardware.org/?probe=82118905ba) | Mar 30, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6cc34607d1](https://linux-hardware.org/?probe=6cc34607d1) | Mar 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| THUNDEROBO... | 911 Plus                    | Notebook    | [6617ad47b7](https://linux-hardware.org/?probe=6617ad47b7) | Mar 28, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [4fe0ddab4b](https://linux-hardware.org/?probe=4fe0ddab4b) | Mar 28, 2023 |
| Google        | Swanky                      | Notebook    | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [5969fea8f0](https://linux-hardware.org/?probe=5969fea8f0) | Mar 28, 2023 |
| Gigabyte      | H97M-HD3                    | Desktop     | [1b531d5ada](https://linux-hardware.org/?probe=1b531d5ada) | Mar 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | Notebook    | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| GPD           | P3 MAX                      | Notebook    | [b3627909f1](https://linux-hardware.org/?probe=b3627909f1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [c1e74d51ee](https://linux-hardware.org/?probe=c1e74d51ee) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| HP            | 895D                        | Desktop     | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| Dell          | Precision 5570              | Notebook    | [454590a1a8](https://linux-hardware.org/?probe=454590a1a8) | Mar 26, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a05e768cca](https://linux-hardware.org/?probe=a05e768cca) | Mar 25, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9b9a21b7da](https://linux-hardware.org/?probe=9b9a21b7da) | Mar 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [cea1787057](https://linux-hardware.org/?probe=cea1787057) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [728f83932f](https://linux-hardware.org/?probe=728f83932f) | Mar 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [58f8d5849a](https://linux-hardware.org/?probe=58f8d5849a) | Mar 24, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e6ecf47eda](https://linux-hardware.org/?probe=e6ecf47eda) | Mar 24, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [4b563f19dd](https://linux-hardware.org/?probe=4b563f19dd) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5a94081c24](https://linux-hardware.org/?probe=5a94081c24) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | Notebook    | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6b3cdb2b1a](https://linux-hardware.org/?probe=6b3cdb2b1a) | Mar 23, 2023 |
| ECS           | G31T-M9                     | Desktop     | [e314bf5403](https://linux-hardware.org/?probe=e314bf5403) | Mar 23, 2023 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [26ca87e272](https://linux-hardware.org/?probe=26ca87e272) | Mar 23, 2023 |
| Acer          | Aspire VN7-791              | Notebook    | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [1f5d2a057c](https://linux-hardware.org/?probe=1f5d2a057c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | Notebook    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [468588ab96](https://linux-hardware.org/?probe=468588ab96) | Mar 21, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6b25c70b9f](https://linux-hardware.org/?probe=6b25c70b9f) | Mar 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c5c907b643](https://linux-hardware.org/?probe=c5c907b643) | Mar 21, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [b9bf22cc53](https://linux-hardware.org/?probe=b9bf22cc53) | Mar 20, 2023 |
| Dell          | G3 3590                     | Notebook    | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| Intel         | STK2M3W64CC H89289-506      | Desktop     | [5386cc221b](https://linux-hardware.org/?probe=5386cc221b) | Mar 19, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [d1a16fdb17](https://linux-hardware.org/?probe=d1a16fdb17) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [08572d5e7c](https://linux-hardware.org/?probe=08572d5e7c) | Mar 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [82914cf856](https://linux-hardware.org/?probe=82914cf856) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [262faf6d70](https://linux-hardware.org/?probe=262faf6d70) | Mar 18, 2023 |
| Aquarius      | NS585                       | Notebook    | [cd1e92458f](https://linux-hardware.org/?probe=cd1e92458f) | Mar 17, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [89660a09c2](https://linux-hardware.org/?probe=89660a09c2) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [66f4a76724](https://linux-hardware.org/?probe=66f4a76724) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [b50b834744](https://linux-hardware.org/?probe=b50b834744) | Mar 16, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [f3ee556fb5](https://linux-hardware.org/?probe=f3ee556fb5) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [372deb4bed](https://linux-hardware.org/?probe=372deb4bed) | Mar 16, 2023 |
| ASUSTek       | M4A88T-M                    | Desktop     | [d8e1601e65](https://linux-hardware.org/?probe=d8e1601e65) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b843a727ce](https://linux-hardware.org/?probe=b843a727ce) | Mar 15, 2023 |
| HP            | 8715                        | Mini pc     | [7f9acb1f3e](https://linux-hardware.org/?probe=7f9acb1f3e) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [0eb13c3117](https://linux-hardware.org/?probe=0eb13c3117) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [6e24f7a3c1](https://linux-hardware.org/?probe=6e24f7a3c1) | Mar 15, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [15d4cdae49](https://linux-hardware.org/?probe=15d4cdae49) | Mar 14, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [7a992ff109](https://linux-hardware.org/?probe=7a992ff109) | Mar 14, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [ef02f8156e](https://linux-hardware.org/?probe=ef02f8156e) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [cc878090ee](https://linux-hardware.org/?probe=cc878090ee) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [088b681bdd](https://linux-hardware.org/?probe=088b681bdd) | Mar 13, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [55a73e2e07](https://linux-hardware.org/?probe=55a73e2e07) | Mar 12, 2023 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [daf687f0a1](https://linux-hardware.org/?probe=daf687f0a1) | Mar 12, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| HP            | 8076 MVB,A                  | Desktop     | [20150077f5](https://linux-hardware.org/?probe=20150077f5) | Mar 11, 2023 |
| Dell          | Latitude 3320               | Notebook    | [2a58a07005](https://linux-hardware.org/?probe=2a58a07005) | Mar 11, 2023 |
| Dell          | Latitude 3320               | Notebook    | [d17364c0ef](https://linux-hardware.org/?probe=d17364c0ef) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c528b16696](https://linux-hardware.org/?probe=c528b16696) | Mar 10, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [dd67a26e98](https://linux-hardware.org/?probe=dd67a26e98) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cfacdb386a](https://linux-hardware.org/?probe=cfacdb386a) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5bc1f5d6d8](https://linux-hardware.org/?probe=5bc1f5d6d8) | Mar 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| Dell          | Precision 3560              | Notebook    | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [32d1af5dee](https://linux-hardware.org/?probe=32d1af5dee) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [92f8093adb](https://linux-hardware.org/?probe=92f8093adb) | Mar 07, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [eb5b9b8cb9](https://linux-hardware.org/?probe=eb5b9b8cb9) | Mar 06, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | Notebook    | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c4def038d9](https://linux-hardware.org/?probe=c4def038d9) | Mar 04, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1bef11c91d](https://linux-hardware.org/?probe=1bef11c91d) | Mar 04, 2023 |
| HP            | 82B4                        | Desktop     | [47d445cfa6](https://linux-hardware.org/?probe=47d445cfa6) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | Notebook    | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ae03ade800](https://linux-hardware.org/?probe=ae03ade800) | Mar 04, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Unknown       | Unknown                     | Soc         | [59b899bee2](https://linux-hardware.org/?probe=59b899bee2) | Mar 02, 2023 |
| Unknown       | Unknown                     | Soc         | [71faa2a8b1](https://linux-hardware.org/?probe=71faa2a8b1) | Mar 02, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [e055e73b69](https://linux-hardware.org/?probe=e055e73b69) | Mar 02, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [672684e416](https://linux-hardware.org/?probe=672684e416) | Feb 28, 2023 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [edf2240a74](https://linux-hardware.org/?probe=edf2240a74) | Feb 28, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [3a670fbd63](https://linux-hardware.org/?probe=3a670fbd63) | Feb 27, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| Dell          | G3 3590                     | Notebook    | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [23a808c1e1](https://linux-hardware.org/?probe=23a808c1e1) | Feb 24, 2023 |
| Unknown       | Unknown                     | Soc         | [44fdfeedf2](https://linux-hardware.org/?probe=44fdfeedf2) | Feb 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4009d82fc8](https://linux-hardware.org/?probe=4009d82fc8) | Feb 22, 2023 |
| Dell          | Latitude 7530               | Notebook    | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | Notebook    | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJA0... | Convertible | [aba497a637](https://linux-hardware.org/?probe=aba497a637) | Feb 21, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Dell          | 0T065F A01                  | Desktop     | [c8b1f8651a](https://linux-hardware.org/?probe=c8b1f8651a) | Feb 19, 2023 |
| Gigabyte      | X299 UD4 Pro-CF             | Desktop     | [d442995b00](https://linux-hardware.org/?probe=d442995b00) | Feb 19, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [22fdba9212](https://linux-hardware.org/?probe=22fdba9212) | Feb 19, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [22b75dc114](https://linux-hardware.org/?probe=22b75dc114) | Feb 18, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [288e753767](https://linux-hardware.org/?probe=288e753767) | Feb 17, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [cfdcc68921](https://linux-hardware.org/?probe=cfdcc68921) | Feb 16, 2023 |
| MSI           | Z270 TOMAHAWK ARCTIC        | Desktop     | [7bb3c6268f](https://linux-hardware.org/?probe=7bb3c6268f) | Feb 16, 2023 |
| Dell          | Precision 5570              | Notebook    | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [940563622b](https://linux-hardware.org/?probe=940563622b) | Feb 16, 2023 |
| Dell          | Precision 5570              | Notebook    | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [5ebd73227b](https://linux-hardware.org/?probe=5ebd73227b) | Feb 14, 2023 |
| HP            | 3648h                       | Desktop     | [18eb122bc9](https://linux-hardware.org/?probe=18eb122bc9) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [34ad4bac16](https://linux-hardware.org/?probe=34ad4bac16) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [c49317ce12](https://linux-hardware.org/?probe=c49317ce12) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [b1d1f36f51](https://linux-hardware.org/?probe=b1d1f36f51) | Feb 13, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [517a5a9e81](https://linux-hardware.org/?probe=517a5a9e81) | Feb 13, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [124d65cd04](https://linux-hardware.org/?probe=124d65cd04) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [c0d18ab501](https://linux-hardware.org/?probe=c0d18ab501) | Feb 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [7b6a31ec69](https://linux-hardware.org/?probe=7b6a31ec69) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [65e66dbf71](https://linux-hardware.org/?probe=65e66dbf71) | Feb 10, 2023 |
| ASUSTek       | M4N78                       | Desktop     | [34ddf02a41](https://linux-hardware.org/?probe=34ddf02a41) | Feb 10, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | Notebook    | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | Notebook    | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [bbaa8165e4](https://linux-hardware.org/?probe=bbaa8165e4) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | Notebook    | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [4b19274da1](https://linux-hardware.org/?probe=4b19274da1) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [bc5b9a2c5d](https://linux-hardware.org/?probe=bc5b9a2c5d) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [55402fea35](https://linux-hardware.org/?probe=55402fea35) | Feb 05, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7b81bb188c](https://linux-hardware.org/?probe=7b81bb188c) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_12/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.1.0-9-amd64           | 218       | 34.38%  |
| 6.1.0-4-amd64           | 128       | 20.19%  |
| 6.1.0-7-amd64           | 90        | 14.2%   |
| 6.1.0-6-amd64           | 45        | 7.1%    |
| 6.1.0-3-amd64           | 36        | 5.68%   |
| 6.1.0-5-amd64           | 32        | 5.05%   |
| 6.1.0-8-amd64           | 15        | 2.37%   |
| 6.0.0-6-amd64           | 6         | 0.95%   |
| 6.0.0-2-amd64           | 4         | 0.63%   |
| 6.1.0-7-rt-amd64        | 3         | 0.47%   |
| 5.15.0-starfive         | 3         | 0.47%   |
| 6.2.16-3-pve            | 2         | 0.32%   |
| 6.2.16-2-pve            | 2         | 0.32%   |
| 6.1.0-9-686-pae         | 2         | 0.32%   |
| 6.1.0-2-amd64           | 2         | 0.32%   |
| 6.0.0-4-amd64           | 2         | 0.32%   |
| 6.0.0-0.deb11.6-amd64   | 2         | 0.32%   |
| 5.15.94-starfive2       | 2         | 0.32%   |
| 6.3.9-1-liquorix-amd64  | 1         | 0.16%   |
| 6.3.8-1-liquorix-amd64  | 1         | 0.16%   |
| 6.3.5-x64v3-xanmod1     | 1         | 0.16%   |
| 6.3.3-tkg-cfs           | 1         | 0.16%   |
| 6.3.0-7-amd64           | 1         | 0.16%   |
| 6.3.0-0-amd64           | 1         | 0.16%   |
| 6.2.8-x64v3-xanmod1     | 1         | 0.16%   |
| 6.2.8                   | 1         | 0.16%   |
| 6.2.11-3-liquorix-amd64 | 1         | 0.16%   |
| 6.2.11                  | 1         | 0.16%   |
| 6.1.9-x64v3-xanmod1     | 1         | 0.16%   |
| 6.1.27-mab64            | 1         | 0.16%   |
| 6.1.26-sunxi            | 1         | 0.16%   |
| 6.1.25-sunxi            | 1         | 0.16%   |
| 6.1.13-x64v1-xanmod1    | 1         | 0.16%   |
| 6.1.11-stb-cbq          | 1         | 0.16%   |
| 6.1.0-9-rt-amd64        | 1         | 0.16%   |
| 6.1.0-9-armmp           | 1         | 0.16%   |
| 6.1.0-7-686             | 1         | 0.16%   |
| 6.1.0-6-rt-amd64        | 1         | 0.16%   |
| 6.1.0-6-powerpc64       | 1         | 0.16%   |
| 6.1.0-0-amd64           | 1         | 0.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.0    | 558       | 90.73%  |
| 6.0.0    | 15        | 2.44%   |
| 5.10.0   | 6         | 0.98%   |
| 6.2.16   | 4         | 0.65%   |
| 5.15.0   | 4         | 0.65%   |
| 6.3.0    | 2         | 0.33%   |
| 6.2.8    | 2         | 0.33%   |
| 6.2.11   | 2         | 0.33%   |
| 5.15.94  | 2         | 0.33%   |
| 6.3.9    | 1         | 0.16%   |
| 6.3.8    | 1         | 0.16%   |
| 6.3.5    | 1         | 0.16%   |
| 6.3.3    | 1         | 0.16%   |
| 6.1.9    | 1         | 0.16%   |
| 6.1.27   | 1         | 0.16%   |
| 6.1.26   | 1         | 0.16%   |
| 6.1.25   | 1         | 0.16%   |
| 6.1.13   | 1         | 0.16%   |
| 6.1.11   | 1         | 0.16%   |
| 6.1      | 1         | 0.16%   |
| 5.19.0   | 1         | 0.16%   |
| 5.16.0   | 1         | 0.16%   |
| 5.15.95  | 1         | 0.16%   |
| 5.15.90  | 1         | 0.16%   |
| 5.15.108 | 1         | 0.16%   |
| 5.10.136 | 1         | 0.16%   |
| 5.10.113 | 1         | 0.16%   |
| 4.14.180 | 1         | 0.16%   |
| 4.1.42   | 1         | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 564       | 91.86%  |
| 6.0     | 15        | 2.44%   |
| 6.2     | 8         | 1.3%    |
| 5.15    | 8         | 1.3%    |
| 5.10    | 8         | 1.3%    |
| 6.3     | 6         | 0.98%   |
| 6       | 1         | 0.16%   |
| 5.19    | 1         | 0.16%   |
| 5.16    | 1         | 0.16%   |
| 4.14    | 1         | 0.16%   |
| 4.1     | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 594       | 97.22%  |
| riscv64 | 5         | 0.82%   |
| i686    | 4         | 0.65%   |
| aarch64 | 4         | 0.65%   |
| armv7l  | 3         | 0.49%   |
| ppc64   | 1         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 186       | 30.24%  |
| GNOME            | 177       | 28.78%  |
| KDE5             | 111       | 18.05%  |
| XFCE             | 52        | 8.46%   |
| X-Cinnamon       | 29        | 4.72%   |
| MATE             | 22        | 3.58%   |
| LXDE             | 8         | 1.3%    |
| i3               | 8         | 1.3%    |
| LXQt             | 5         | 0.81%   |
| GNOME Flashback  | 4         | 0.65%   |
| GNUstep          | 2         | 0.33%   |
| Enlightenment    | 2         | 0.33%   |
| xmonad           | 1         | 0.16%   |
| sway             | 1         | 0.16%   |
| Pantheon         | 1         | 0.16%   |
| openbox          | 1         | 0.16%   |
| lightdm-xsession | 1         | 0.16%   |
| GNOME Classic    | 1         | 0.16%   |
| Cinnamon         | 1         | 0.16%   |
| Budgie           | 1         | 0.16%   |
| awesome          | 1         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 240       | 39.02%  |
| Wayland | 177       | 28.78%  |
| Unknown | 161       | 26.18%  |
| Tty     | 37        | 6.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 273       | 44.25%  |
| GDM3    | 152       | 24.64%  |
| LightDM | 93        | 15.07%  |
| SDDM    | 89        | 14.42%  |
| LXDM    | 3         | 0.49%   |
| XDM     | 2         | 0.32%   |
| SLiM    | 2         | 0.32%   |
| GREETD  | 2         | 0.32%   |
| Ly      | 1         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 174       | 28.43%  |
| ru_RU   | 149       | 24.35%  |
| de_DE   | 59        | 9.64%   |
| fr_FR   | 35        | 5.72%   |
| en_GB   | 29        | 4.74%   |
| Unknown | 29        | 4.74%   |
| sv_SE   | 15        | 2.45%   |
| pt_BR   | 12        | 1.96%   |
| es_ES   | 11        | 1.8%    |
| zh_CN   | 9         | 1.47%   |
| it_IT   | 9         | 1.47%   |
| en_CA   | 9         | 1.47%   |
| pl_PL   | 6         | 0.98%   |
| en_IN   | 5         | 0.82%   |
| en_AU   | 5         | 0.82%   |
| C       | 5         | 0.82%   |
| de_AT   | 4         | 0.65%   |
| fr_BE   | 3         | 0.49%   |
| en_NZ   | 3         | 0.49%   |
| tr_TR   | 2         | 0.33%   |
| nl_NL   | 2         | 0.33%   |
| es_CL   | 2         | 0.33%   |
| es_AR   | 2         | 0.33%   |
| en_ZA   | 2         | 0.33%   |
| en_IL   | 2         | 0.33%   |
| en_IE   | 2         | 0.33%   |
| en_DK   | 2         | 0.33%   |
| ca_ES   | 2         | 0.33%   |
| be_BY   | 2         | 0.33%   |
| zh_TW   | 1         | 0.16%   |
| uk_UA   | 1         | 0.16%   |
| pt_PT   | 1         | 0.16%   |
| oc_FR   | 1         | 0.16%   |
| nl_BE   | 1         | 0.16%   |
| ko_KR   | 1         | 0.16%   |
| ja_JP   | 1         | 0.16%   |
| id_ID   | 1         | 0.16%   |
| hu_HU   | 1         | 0.16%   |
| hr_HR   | 1         | 0.16%   |
| fi_FI   | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 335       | 54.83%  |
| BIOS | 276       | 45.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 401       | 65.63%  |
| Overlay | 160       | 26.19%  |
| Btrfs   | 30        | 4.91%   |
| Xfs     | 8         | 1.31%   |
| Tmpfs   | 5         | 0.82%   |
| Zfs     | 3         | 0.49%   |
| Ext2    | 2         | 0.33%   |
| F2fs    | 1         | 0.16%   |
| Ext3    | 1         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 369       | 60.29%  |
| MBR     | 153       | 25%     |
| Unknown | 90        | 14.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 533       | 86.81%  |
| Yes       | 81        | 13.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 359       | 58.66%  |
| Yes       | 253       | 41.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 127       | 20.79%  |
| Lenovo                         | 105       | 17.18%  |
| Hewlett-Packard                | 62        | 10.15%  |
| Dell                           | 55        | 9%      |
| Gigabyte Technology            | 49        | 8.02%   |
| Aquarius                       | 29        | 4.75%   |
| Acer                           | 23        | 3.76%   |
| MSI                            | 22        | 3.6%    |
| ASRock                         | 20        | 3.27%   |
| Apple                          | 15        | 2.45%   |
| Intel                          | 11        | 1.8%    |
| Unknown                        | 10        | 1.64%   |
| HUAWEI                         | 6         | 0.98%   |
| Toshiba                        | 4         | 0.65%   |
| ECS                            | 4         | 0.65%   |
| Supermicro                     | 3         | 0.49%   |
| Sony                           | 3         | 0.49%   |
| Samsung Electronics            | 3         | 0.49%   |
| Microsoft                      | 3         | 0.49%   |
| HONOR                          | 3         | 0.49%   |
| Google                         | 3         | 0.49%   |
| eMachines                      | 3         | 0.49%   |
| Techvision                     | 2         | 0.33%   |
| Schenker                       | 2         | 0.33%   |
| LG Electronics                 | 2         | 0.33%   |
| GPD                            | 2         | 0.33%   |
| Fujitsu                        | 2         | 0.33%   |
| Foxconn                        | 2         | 0.33%   |
| Biostar                        | 2         | 0.33%   |
| Avell High Performance         | 2         | 0.33%   |
| AMI                            | 2         | 0.33%   |
| Xunlong                        | 1         | 0.16%   |
| TUXEDO                         | 1         | 0.16%   |
| THUNDEROBOT                    | 1         | 0.16%   |
| Terrans Force                  | 1         | 0.16%   |
| Tactus                         | 1         | 0.16%   |
| System76                       | 1         | 0.16%   |
| sunxi                          | 1         | 0.16%   |
| Shuttle                        | 1         | 0.16%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                            | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Aquarius NS585                                  | 29        | 4.75%   |
| ASUS All Series                                 | 20        | 3.27%   |
| Unknown                                         | 14        | 2.29%   |
| Lenovo ThinkCentre M55p 8808D8U                 | 12        | 1.96%   |
| ASUS PRIME B450M-K                              | 10        | 1.64%   |
| Gigabyte H81M-S2V                               | 8         | 1.31%   |
| Apple MacBookAir7,2                             | 5         | 0.82%   |
| Lenovo ThinkPad L14 Gen 2 20X1004CMX            | 4         | 0.65%   |
| ECS G31T-M9                                     | 4         | 0.65%   |
| Dell Precision 5570                             | 4         | 0.65%   |
| ASUS S20 K29                                    | 4         | 0.65%   |
| MSI MS-7996                                     | 3         | 0.49%   |
| HP EliteBook 840 G5                             | 3         | 0.49%   |
| HP Elite x360 830 13 inch G9 2-in-1 Notebook PC | 3         | 0.49%   |
| Gigabyte M56S-S3                                | 3         | 0.49%   |
| ASUS ROG STRIX X570-E GAMING                    | 3         | 0.49%   |
| ASUS PRIME B450M-A                              | 3         | 0.49%   |
| Techvision TVI7309X                             | 2         | 0.33%   |
| MSI MS-7C37                                     | 2         | 0.33%   |
| Microsoft Surface Go                            | 2         | 0.33%   |
| Lenovo ThinkPad L13 Gen 2 20VJS6RY00            | 2         | 0.33%   |
| HUAWEI BOHK-WAX9X                               | 2         | 0.33%   |
| HONOR NMH-WCX9                                  | 2         | 0.33%   |
| HP ProBook 640 G1                               | 2         | 0.33%   |
| HP ProBook 440 14 inch G9 Notebook PC           | 2         | 0.33%   |
| HP OMEN by Laptop                               | 2         | 0.33%   |
| HP EliteBook 845 G8 Notebook PC                 | 2         | 0.33%   |
| HP 255 G8 Notebook PC                           | 2         | 0.33%   |
| Gigabyte M68MT-S2                               | 2         | 0.33%   |
| Gigabyte H61M-DS2 REV 1.2                       | 2         | 0.33%   |
| Gigabyte B550M DS3H                             | 2         | 0.33%   |
| Gigabyte B450M H                                | 2         | 0.33%   |
| Gigabyte B450 AORUS ELITE                       | 2         | 0.33%   |
| Dell XPS 15 9570                                | 2         | 0.33%   |
| Dell Latitude 7480                              | 2         | 0.33%   |
| Dell Latitude 3320                              | 2         | 0.33%   |
| Dell G3 3590                                    | 2         | 0.33%   |
| ASUS Zenbook UX535QE_UM535QE                    | 2         | 0.33%   |
| ASUS VivoBook_ASUSLaptop M3401QA_M3401QA        | 2         | 0.33%   |
| ASUS TUF Gaming B550M-PLUS                      | 2         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 60        | 9.82%   |
| ASUS PRIME         | 29        | 4.75%   |
| Aquarius NS585     | 29        | 4.75%   |
| ASUS All           | 20        | 3.27%   |
| Lenovo ThinkCentre | 19        | 3.11%   |
| Dell Latitude      | 16        | 2.62%   |
| Unknown            | 14        | 2.29%   |
| Acer Aspire        | 13        | 2.13%   |
| HP EliteBook       | 11        | 1.8%    |
| ASUS ROG           | 11        | 1.8%    |
| Lenovo IdeaPad     | 10        | 1.64%   |
| Dell XPS           | 10        | 1.64%   |
| Dell Inspiron      | 10        | 1.64%   |
| ASUS VivoBook      | 10        | 1.64%   |
| Gigabyte H81M-S2V  | 8         | 1.31%   |
| HP ProBook         | 7         | 1.15%   |
| Dell Precision     | 7         | 1.15%   |
| ASUS Zenbook       | 6         | 0.98%   |
| ASUS TUF           | 6         | 0.98%   |
| Apple MacBookAir7  | 6         | 0.98%   |
| Toshiba Satellite  | 4         | 0.65%   |
| Lenovo Yoga        | 4         | 0.65%   |
| HP ProDesk         | 4         | 0.65%   |
| HP Pavilion        | 4         | 0.65%   |
| HP OMEN            | 4         | 0.65%   |
| HP Elite           | 4         | 0.65%   |
| ECS G31T-M9        | 4         | 0.65%   |
| ASUS S20           | 4         | 0.65%   |
| Acer Nitro         | 4         | 0.65%   |
| MSI Prestige       | 3         | 0.49%   |
| MSI MS-7996        | 3         | 0.49%   |
| Microsoft Surface  | 3         | 0.49%   |
| HP Laptop          | 3         | 0.49%   |
| HP ENVY            | 3         | 0.49%   |
| HP Compaq          | 3         | 0.49%   |
| Gigabyte M56S-S3   | 3         | 0.49%   |
| Gigabyte B550M     | 3         | 0.49%   |
| Gigabyte B450M     | 3         | 0.49%   |
| Gigabyte B450      | 3         | 0.49%   |
| Dell Vostro        | 3         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 77        | 12.6%   |
| 2022    | 73        | 11.95%  |
| 2021    | 61        | 9.98%   |
| 2020    | 60        | 9.82%   |
| 2018    | 52        | 8.51%   |
| 2012    | 37        | 6.06%   |
| 2014    | 31        | 5.07%   |
| 2017    | 27        | 4.42%   |
| 2009    | 27        | 4.42%   |
| 2007    | 25        | 4.09%   |
| 2013    | 21        | 3.44%   |
| 2010    | 20        | 3.27%   |
| 2015    | 19        | 3.11%   |
| 2008    | 18        | 2.95%   |
| 2016    | 17        | 2.78%   |
| 2023    | 16        | 2.62%   |
| 2011    | 15        | 2.45%   |
| Unknown | 13        | 2.13%   |
| 2006    | 1         | 0.16%   |
| 2005    | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 300       | 49.1%   |
| Desktop        | 250       | 40.92%  |
| Convertible    | 20        | 3.27%   |
| Mini pc        | 13        | 2.13%   |
| System on chip | 11        | 1.8%    |
| Tablet         | 5         | 0.82%   |
| All in one     | 5         | 0.82%   |
| Server         | 5         | 0.82%   |
| Phone          | 1         | 0.16%   |
| Stick pc       | 1         | 0.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 554       | 90.38%  |
| Enabled  | 59        | 9.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 608       | 99.51%  |
| Yes  | 3         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 156       | 25.45%  |
| 8.01-16.0       | 108       | 17.62%  |
| 16.01-24.0      | 94        | 15.33%  |
| 32.01-64.0      | 90        | 14.68%  |
| 3.01-4.0        | 90        | 14.68%  |
| 64.01-256.0     | 25        | 4.08%   |
| 1.01-2.0        | 23        | 3.75%   |
| 2.01-3.0        | 11        | 1.79%   |
| 24.01-32.0      | 6         | 0.98%   |
| 0.51-1.0        | 6         | 0.98%   |
| More than 256.0 | 2         | 0.33%   |
| 0.01-0.5        | 1         | 0.16%   |
| Unknown         | 1         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.51-1.0    | 139       | 22.13%  |
| 4.01-8.0    | 129       | 20.54%  |
| 1.01-2.0    | 119       | 18.95%  |
| 2.01-3.0    | 111       | 17.68%  |
| 3.01-4.0    | 62        | 9.87%   |
| 8.01-16.0   | 34        | 5.41%   |
| 0.01-0.5    | 22        | 3.5%    |
| 16.01-24.0  | 7         | 1.11%   |
| 32.01-64.0  | 2         | 0.32%   |
| 24.01-32.0  | 1         | 0.16%   |
| 64.01-256.0 | 1         | 0.16%   |
| Unknown     | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 426       | 69.38%  |
| 2      | 109       | 17.75%  |
| 3      | 41        | 6.68%   |
| 4      | 15        | 2.44%   |
| 5      | 9         | 1.47%   |
| 6      | 8         | 1.3%    |
| 8      | 2         | 0.33%   |
| 29     | 1         | 0.16%   |
| 10     | 1         | 0.16%   |
| 7      | 1         | 0.16%   |
| 0      | 1         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 473       | 77.29%  |
| Yes       | 139       | 22.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 508       | 83.01%  |
| No        | 104       | 16.99%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 425       | 69.22%  |
| No        | 189       | 30.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 369       | 60.29%  |
| No        | 243       | 39.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 152       | 24.72%  |
| USA         | 81        | 13.17%  |
| Germany     | 76        | 12.36%  |
| France      | 38        | 6.18%   |
| Sweden      | 25        | 4.07%   |
| Brazil      | 23        | 3.74%   |
| UK          | 19        | 3.09%   |
| Spain       | 17        | 2.76%   |
| Poland      | 14        | 2.28%   |
| Italy       | 14        | 2.28%   |
| Canada      | 12        | 1.95%   |
| China       | 9         | 1.46%   |
| Netherlands | 8         | 1.3%    |
| Australia   | 8         | 1.3%    |
| Austria     | 7         | 1.14%   |
| Switzerland | 6         | 0.98%   |
| Czechia     | 6         | 0.98%   |
| Belgium     | 6         | 0.98%   |
| Mexico      | 5         | 0.81%   |
| India       | 5         | 0.81%   |
| Norway      | 4         | 0.65%   |
| New Zealand | 4         | 0.65%   |
| Israel      | 4         | 0.65%   |
| Finland     | 4         | 0.65%   |
| Argentina   | 4         | 0.65%   |
| Ukraine     | 3         | 0.49%   |
| Turkey      | 3         | 0.49%   |
| Slovakia    | 3         | 0.49%   |
| Singapore   | 3         | 0.49%   |
| Japan       | 3         | 0.49%   |
| Hungary     | 3         | 0.49%   |
| Denmark     | 3         | 0.49%   |
| Belarus     | 3         | 0.49%   |
| Romania     | 2         | 0.33%   |
| Morocco     | 2         | 0.33%   |
| Madagascar  | 2         | 0.33%   |
| Latvia      | 2         | 0.33%   |
| Ireland     | 2         | 0.33%   |
| Indonesia   | 2         | 0.33%   |
| Georgia     | 2         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 124       | 19.97%  |
| Bangor            | 26        | 4.19%   |
| Saltsjoe-Boo      | 16        | 2.58%   |
| Moscow            | 14        | 2.25%   |
| Paris             | 9         | 1.45%   |
| Toronto           | 6         | 0.97%   |
| Berlin            | 6         | 0.97%   |
| Vienna            | 5         | 0.81%   |
| Frankfurt am Main | 5         | 0.81%   |
| Marseille         | 4         | 0.64%   |
| Manchester        | 4         | 0.64%   |
| Madrid            | 4         | 0.64%   |
| Zurich            | 3         | 0.48%   |
| Wroclaw           | 3         | 0.48%   |
| Stockholm         | 3         | 0.48%   |
| St Petersburg     | 3         | 0.48%   |
| Singapore         | 3         | 0.48%   |
| Seattle           | 3         | 0.48%   |
| Prague            | 3         | 0.48%   |
| Nuremberg         | 3         | 0.48%   |
| Munich            | 3         | 0.48%   |
| London            | 3         | 0.48%   |
| Hofheim am Taunus | 3         | 0.48%   |
| Hamburg           | 3         | 0.48%   |
| Gladbeck          | 3         | 0.48%   |
| Beijing           | 3         | 0.48%   |
| Barcelona         | 3         | 0.48%   |
| Amsterdam         | 3         | 0.48%   |
| Wellington        | 2         | 0.32%   |
| Tiranges          | 2         | 0.32%   |
| Tbilisi           | 2         | 0.32%   |
| Sydney            | 2         | 0.32%   |
| Strasbourg        | 2         | 0.32%   |
| Seville           | 2         | 0.32%   |
| San Jose          | 2         | 0.32%   |
| San Francisco     | 2         | 0.32%   |
| Samara            | 2         | 0.32%   |
| Rozhanovce        | 2         | 0.32%   |
| Richmond          | 2         | 0.32%   |
| Płock            | 2         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 143       | 188    | 17%     |
| WDC                         | 138       | 187    | 16.41%  |
| Seagate                     | 86        | 129    | 10.23%  |
| Crucial                     | 48        | 59     | 5.71%   |
| Toshiba                     | 46        | 54     | 5.47%   |
| SanDisk                     | 43        | 51     | 5.11%   |
| A-DATA Technology           | 38        | 50     | 4.52%   |
| Kingston                    | 34        | 38     | 4.04%   |
| Unknown                     | 31        | 41     | 3.69%   |
| Hitachi                     | 23        | 27     | 2.73%   |
| SK hynix                    | 20        | 23     | 2.38%   |
| Micron Technology           | 17        | 17     | 2.02%   |
| Intel                       | 15        | 15     | 1.78%   |
| KIOXIA                      | 9         | 10     | 1.07%   |
| HGST                        | 9         | 10     | 1.07%   |
| Apple                       | 9         | 9      | 1.07%   |
| Kingston Technology Company | 7         | 8      | 0.83%   |
| China                       | 7         | 7      | 0.83%   |
| SPCC                        | 6         | 7      | 0.71%   |
| Transcend                   | 5         | 5      | 0.59%   |
| Netac                       | 5         | 5      | 0.59%   |
| Intenso                     | 5         | 5      | 0.59%   |
| SSSTC                       | 4         | 4      | 0.48%   |
| Silicon Motion              | 4         | 6      | 0.48%   |
| LITEON                      | 4         | 4      | 0.48%   |
| JMicron Technology          | 4         | 4      | 0.48%   |
| TO Exter                    | 3         | 4      | 0.36%   |
| SABRENT                     | 3         | 3      | 0.36%   |
| Plextor                     | 3         | 3      | 0.36%   |
| Phison                      | 3         | 3      | 0.36%   |
| OCZ                         | 3         | 3      | 0.36%   |
| KIOXIA-EXCERIA              | 3         | 3      | 0.36%   |
| Hewlett-Packard             | 3         | 5      | 0.36%   |
| GOODRAM                     | 3         | 3      | 0.36%   |
| Unknown                     | 3         | 3      | 0.36%   |
| XPG                         | 2         | 4      | 0.24%   |
| PNY                         | 2         | 3      | 0.24%   |
| Phison Electronics          | 2         | 3      | 0.24%   |
| Lexar                       | 2         | 2      | 0.24%   |
| Fujitsu                     | 2         | 2      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| A-DATA SU800 512GB SSD                              | 29        | 3.15%   |
| Crucial CT480BX500SSD1 480GB                        | 17        | 1.85%   |
| WDC WD5000AAKX-60U6AA0 500GB                        | 15        | 1.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 13        | 1.41%   |
| Samsung SSD 980 PRO 1TB                             | 10        | 1.09%   |
| Seagate ST1000DM003-1ER162 1TB                      | 9         | 0.98%   |
| Crucial CT500MX500SSD1 500GB                        | 8         | 0.87%   |
| Kingston SA400S37480G 480GB SSD                     | 7         | 0.76%   |
| Hitachi HDS728080PLA380 40Y9028LEN 80GB             | 7         | 0.76%   |
| Samsung SSD 980 1TB                                 | 6         | 0.65%   |
| Samsung SSD 970 EVO Plus 1TB                        | 6         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 6         | 0.65%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.65%   |
| Toshiba XG6 NVMe SSD Controller 2TB                 | 5         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB                      | 5         | 0.54%   |
| Samsung PM9A1 NVMe 1024GB                           | 5         | 0.54%   |
| Samsung MZVLB512HBJQ-000L7 512GB                    | 5         | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                         | 5         | 0.54%   |
| Apple SSD SM0128G 121GB                             | 5         | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 4         | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4         | 0.43%   |
| Unknown SD32G  32GB                                 | 4         | 0.43%   |
| Seagate ST4000DM004-2CV104 4TB                      | 4         | 0.43%   |
| Seagate ST3250410AS 250GB                           | 4         | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                          | 4         | 0.43%   |
| Samsung SSD 980 500GB                               | 4         | 0.43%   |
| Samsung SSD 860 EVO 250GB                           | 4         | 0.43%   |
| Samsung SSD 850 EVO 500GB                           | 4         | 0.43%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 0.43%   |
| HGST HTS721010A9E630 1TB                            | 4         | 0.43%   |
| WDC WD800JD-08MSA1 80GB                             | 3         | 0.33%   |
| WDC WD5000LPLX-00ZNTT0 500GB                        | 3         | 0.33%   |
| WDC WD2500AAKS-00VSA0 250GB                         | 3         | 0.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 3         | 0.33%   |
| Unknown SD/MMC/MS PRO 250GB                         | 3         | 0.33%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.33%   |
| Toshiba DT01ACA100 1TB                              | 3         | 0.33%   |
| Toshiba DT01ACA050 500GB                            | 3         | 0.33%   |
| TO Exter nal USB 3.0 1TB                            | 3         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 96        | 126    | 38.55%  |
| Seagate             | 81        | 123    | 32.53%  |
| Toshiba             | 30        | 37     | 12.05%  |
| Hitachi             | 23        | 27     | 9.24%   |
| HGST                | 9         | 10     | 3.61%   |
| Unknown             | 3         | 3      | 1.2%    |
| Fujitsu             | 2         | 2      | 0.8%    |
| USB                 | 1         | 1      | 0.4%    |
| Samsung Electronics | 1         | 1      | 0.4%    |
| Maxtor              | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 2      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 58     | 17.23%  |
| Crucial             | 39        | 44     | 14.61%  |
| A-DATA Technology   | 31        | 43     | 11.61%  |
| Kingston            | 23        | 26     | 8.61%   |
| SanDisk             | 20        | 25     | 7.49%   |
| WDC                 | 19        | 28     | 7.12%   |
| China               | 7         | 7      | 2.62%   |
| Intel               | 6         | 6      | 2.25%   |
| Apple               | 6         | 6      | 2.25%   |
| SPCC                | 5         | 5      | 1.87%   |
| Intenso             | 5         | 5      | 1.87%   |
| Toshiba             | 4         | 5      | 1.5%    |
| Netac               | 4         | 4      | 1.5%    |
| Transcend           | 3         | 3      | 1.12%   |
| TO Exter            | 3         | 4      | 1.12%   |
| SK hynix            | 3         | 3      | 1.12%   |
| Plextor             | 3         | 3      | 1.12%   |
| OCZ                 | 3         | 3      | 1.12%   |
| LITEON              | 3         | 3      | 1.12%   |
| GOODRAM             | 3         | 3      | 1.12%   |
| Seagate             | 2         | 2      | 0.75%   |
| PNY                 | 2         | 3      | 0.75%   |
| Micron Technology   | 2         | 2      | 0.75%   |
| AMD                 | 2         | 2      | 0.75%   |
| Wellcomm            | 1         | 1      | 0.37%   |
| TrekStor            | 1         | 1      | 0.37%   |
| SSD                 | 1         | 1      | 0.37%   |
| S3+                 | 1         | 1      | 0.37%   |
| Pioneer             | 1         | 1      | 0.37%   |
| Patriot             | 1         | 1      | 0.37%   |
| Origin              | 1         | 1      | 0.37%   |
| OCZ-VERTEX3         | 1         | 1      | 0.37%   |
| NT-1TB              | 1         | 1      | 0.37%   |
| MSI                 | 1         | 1      | 0.37%   |
| MicroFrom           | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| KOWIN               | 1         | 1      | 0.37%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.37%   |
| INNOVATION IT       | 1         | 1      | 0.37%   |
| Innodisk            | 1         | 1      | 0.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 276       | 357    | 35.75%  |
| SSD     | 238       | 316    | 30.83%  |
| HDD     | 220       | 334    | 28.5%   |
| MMC     | 33        | 43     | 4.27%   |
| Unknown | 5         | 5      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 390       | 603    | 53.87%  |
| NVMe | 271       | 349    | 37.43%  |
| MMC  | 33        | 43     | 4.56%   |
| SAS  | 30        | 60     | 4.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 281       | 353    | 57.46%  |
| 0.51-1.0   | 131       | 172    | 26.79%  |
| 1.01-2.0   | 34        | 49     | 6.95%   |
| 3.01-4.0   | 21        | 45     | 4.29%   |
| 4.01-10.0  | 11        | 16     | 2.25%   |
| 2.01-3.0   | 9         | 9      | 1.84%   |
| 10.01-20.0 | 2         | 6      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 151       | 24.43%  |
| 251-500        | 117       | 18.93%  |
| 101-250        | 110       | 17.8%   |
| 501-1000       | 78        | 12.62%  |
| 1001-2000      | 49        | 7.93%   |
| More than 3000 | 37        | 5.99%   |
| 1-20           | 26        | 4.21%   |
| 51-100         | 20        | 3.24%   |
| 21-50          | 19        | 3.07%   |
| 2001-3000      | 11        | 1.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 165       | 26.61%  |
| Unknown        | 151       | 24.35%  |
| 101-250        | 83        | 13.39%  |
| 21-50          | 61        | 9.84%   |
| 51-100         | 53        | 8.55%   |
| 501-1000       | 38        | 6.13%   |
| 251-500        | 33        | 5.32%   |
| 1001-2000      | 20        | 3.23%   |
| More than 3000 | 12        | 1.94%   |
| 2001-3000      | 4         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB         | 12        | 12     | 14.12%  |
| Seagate ST3250410AS 250GB            | 3         | 3      | 3.53%   |
| WDC WD3200AAJS-00L7A0 320GB          | 2         | 2      | 2.35%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 2.35%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 2.35%   |
| Hitachi HDS721050CLA362 500GB        | 2         | 3      | 2.35%   |
| ZHITAI TiPlus5000 512GB              | 1         | 1      | 1.18%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 1         | 2      | 1.18%   |
| WDC WD800AAJS-60WAA0 80GB            | 1         | 1      | 1.18%   |
| WDC WD5000LPVT-08G33T1 500GB         | 1         | 1      | 1.18%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 3      | 1.18%   |
| WDC WD400BD-60LRA0 40GB              | 1         | 1      | 1.18%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 1      | 1.18%   |
| WDC WD2500AAKS-00VSA0 250GB          | 1         | 2      | 1.18%   |
| WDC WD2500AAJS-00B4A0 250GB          | 1         | 1      | 1.18%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 1      | 1.18%   |
| WDC WD1600YS-18SHB2 160GB            | 1         | 1      | 1.18%   |
| WDC WD1600AAJS-00B4A0 160GB          | 1         | 1      | 1.18%   |
| WDC WD10JPVX-08JC3T5 1TB             | 1         | 1      | 1.18%   |
| WDC WD10EZEX-00WN4A0 1TB             | 1         | 1      | 1.18%   |
| WDC WD10EARS-00MVWB0 1TB             | 1         | 1      | 1.18%   |
| WDC WD10EALX-009BA0 1TB              | 1         | 1      | 1.18%   |
| WDC WD10EADS-00L5B1 1TB              | 1         | 1      | 1.18%   |
| WDC WD1000DHTZ-04N21V0 1TB           | 1         | 1      | 1.18%   |
| WDC WD Blue SA510 2.5 1000GB SSD     | 1         | 1      | 1.18%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.18%   |
| Toshiba MK3263GSX 320GB              | 1         | 1      | 1.18%   |
| Toshiba MK3259GSXP 320GB             | 1         | 1      | 1.18%   |
| Toshiba DT01ACA200 2TB               | 1         | 1      | 1.18%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 1         | 1      | 1.18%   |
| ShiJi 1TB                            | 1         | 2      | 1.18%   |
| Seagate ST9250414ASG 250GB           | 1         | 1      | 1.18%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 1.18%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 1      | 1.18%   |
| Seagate ST5000LM000-2AN170 5TB       | 1         | 2      | 1.18%   |
| Seagate ST4000LM016-1N2170 4TB       | 1         | 1      | 1.18%   |
| Seagate ST3808110AS 41N3267 LEN 80GB | 1         | 1      | 1.18%   |
| Seagate ST3250824AS 250GB            | 1         | 1      | 1.18%   |
| Seagate ST3160815AS 160GB            | 1         | 1      | 1.18%   |
| Seagate ST3160215AS 160GB            | 1         | 1      | 1.18%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 36     | 37.35%  |
| Seagate             | 18        | 20     | 21.69%  |
| Hitachi             | 7         | 8      | 8.43%   |
| Toshiba             | 4         | 4      | 4.82%   |
| SK hynix            | 3         | 3      | 3.61%   |
| Samsung Electronics | 3         | 3      | 3.61%   |
| SanDisk             | 2         | 2      | 2.41%   |
| Kingston            | 2         | 2      | 2.41%   |
| Intel               | 2         | 2      | 2.41%   |
| HGST                | 2         | 2      | 2.41%   |
| ZHITAI              | 1         | 1      | 1.2%    |
| ShiJi               | 1         | 2      | 1.2%    |
| Mushkin             | 1         | 1      | 1.2%    |
| Micron Technology   | 1         | 1      | 1.2%    |
| Maxtor              | 1         | 1      | 1.2%    |
| LITEON              | 1         | 1      | 1.2%    |
| JMicron Technology  | 1         | 1      | 1.2%    |
| China               | 1         | 1      | 1.2%    |
| A-DATA Technology   | 1         | 1      | 1.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 33     | 46.77%  |
| Seagate             | 18        | 20     | 29.03%  |
| Hitachi             | 7         | 8      | 11.29%  |
| Toshiba             | 4         | 4      | 6.45%   |
| HGST                | 2         | 2      | 3.23%   |
| Samsung Electronics | 1         | 1      | 1.61%   |
| Maxtor              | 1         | 1      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 57        | 69     | 73.08%  |
| SSD  | 12        | 13     | 15.38%  |
| NVMe | 9         | 10     | 11.54%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 447       | 692    | 65.83%  |
| Detected | 155       | 271    | 22.83%  |
| Malfunc  | 77        | 92     | 11.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 344       | 43%     |
| AMD                            | 122       | 15.25%  |
| Samsung Electronics            | 106       | 13.25%  |
| SanDisk                        | 47        | 5.88%   |
| Kingston Technology Company    | 18        | 2.25%   |
| SK hynix                       | 16        | 2%      |
| Micron Technology              | 15        | 1.88%   |
| ASMedia Technology             | 15        | 1.88%   |
| Toshiba America Info Systems   | 13        | 1.63%   |
| Nvidia                         | 12        | 1.5%    |
| Micron/Crucial Technology      | 12        | 1.5%    |
| ADATA Technology               | 11        | 1.38%   |
| Phison Electronics             | 9         | 1.13%   |
| KIOXIA                         | 9         | 1.13%   |
| JMicron Technology             | 8         | 1%      |
| Silicon Motion                 | 7         | 0.88%   |
| Solid State Storage Technology | 4         | 0.5%    |
| Marvell Technology Group       | 3         | 0.38%   |
| Yangtze Memory Technologies    | 2         | 0.25%   |
| VIA Technologies               | 2         | 0.25%   |
| Transcend                      | 2         | 0.25%   |
| Silicon Image                  | 2         | 0.25%   |
| Seagate Technology             | 2         | 0.25%   |
| LSI Logic / Symbios Logic      | 2         | 0.25%   |
| Biwin Storage Technology       | 2         | 0.25%   |
| Apple                          | 2         | 0.25%   |
| Adaptec                        | 2         | 0.25%   |
| Union Memory (Shenzhen)        | 1         | 0.13%   |
| Shenzhen Longsys Electronics   | 1         | 0.13%   |
| Realtek Semiconductor          | 1         | 0.13%   |
| Netac Technology               | 1         | 0.13%   |
| Lite-On Technology             | 1         | 0.13%   |
| Jiangsu Huacun Elec.           | 1         | 0.13%   |
| INNOGRIT                       | 1         | 0.13%   |
| IBM                            | 1         | 0.13%   |
| Hewlett-Packard                | 1         | 0.13%   |
| Broadcom / LSI                 | 1         | 0.13%   |
| Artop Electronic               | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 87        | 9.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 41        | 4.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 38        | 4.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 35        | 3.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 32        | 3.45%   |
| AMD 400 Series Chipset SATA Controller                                         | 28        | 3.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 20        | 2.16%   |
| Samsung NVMe SSD Controller 980                                                | 19        | 2.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 19        | 2.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 18        | 1.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 1.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 15        | 1.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 15        | 1.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 14        | 1.51%   |
| AMD 500 Series Chipset SATA Controller                                         | 14        | 1.51%   |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 1.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 1.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 1.19%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 10        | 1.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 10        | 1.08%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 0.97%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 0.97%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 9         | 0.97%   |
| Intel 82Q963/Q965 PT IDER Controller                                           | 9         | 0.97%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 6 port SATA Controller [AHCI mode]           | 8         | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 0.75%   |
| SanDisk Non-Volatile memory controller                                         | 7         | 0.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 0.75%   |
| Kingston Company Company Non-Volatile memory controller                        | 7         | 0.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 0.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 0.75%   |
| Intel 700 Series Chipset Family SATA AHCI Controller                           | 7         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 0.65%   |
| Micron NVMe Storage Controller                                                 | 6         | 0.65%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 6         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 414       | 51.49%  |
| NVMe | 268       | 33.33%  |
| IDE  | 78        | 9.7%    |
| RAID | 39        | 4.85%   |
| SAS  | 4         | 0.5%    |
| SCSI | 1         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 437       | 71.52%  |
| AMD               | 160       | 26.19%  |
| ARM               | 6         | 0.98%   |
| sifive,u74-mc     | 4         | 0.65%   |
| Qualcomm          | 1         | 0.16%   |
| CHRP IBM,8233-E8B | 1         | 0.16%   |
| CentaurHauls      | 1         | 0.16%   |
| Unknown           | 1         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-9100 CPU @ 3.60GHz              | 29        | 4.74%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 18        | 2.94%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 15        | 2.45%   |
| Intel Core 2 CPU 6400 @ 2.13GHz               | 12        | 1.96%   |
| AMD Ryzen 5 3350G with Radeon Vega Graphics   | 10        | 1.63%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 8         | 1.31%   |
| Intel 12th Gen Core i5-1235U                  | 8         | 1.31%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.31%   |
| Intel 12th Gen Core i7-12700H                 | 7         | 1.14%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 6         | 0.98%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 0.98%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 0.98%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 5         | 0.82%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 5         | 0.82%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 5         | 0.82%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 5         | 0.82%   |
| sifive,u74-mc rv64imafdc                      | 4         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.65%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.65%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.65%   |
| Intel 12th Gen Core i7-1260P                  | 4         | 0.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.65%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 4         | 0.65%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.65%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 4         | 0.65%   |
| AMD E-350 Processor                           | 4         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.49%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.49%   |
| Intel Celeron N5105 @ 2.00GHz                 | 3         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 110       | 17.97%  |
| Intel Core i5           | 93        | 15.2%   |
| Intel Core i7           | 64        | 10.46%  |
| Intel Core i3           | 54        | 8.82%   |
| AMD Ryzen 5             | 49        | 8.01%   |
| AMD Ryzen 7             | 39        | 6.37%   |
| Intel Pentium           | 34        | 5.56%   |
| Intel Core 2 Duo        | 21        | 3.43%   |
| Intel Celeron           | 21        | 3.43%   |
| AMD Ryzen 9             | 16        | 2.61%   |
| Intel Core 2            | 15        | 2.45%   |
| Intel Xeon              | 11        | 1.8%    |
| Intel Pentium Dual-Core | 11        | 1.8%    |
| AMD Ryzen 5 PRO         | 9         | 1.47%   |
| AMD Ryzen 3             | 5         | 0.82%   |
| AMD FX                  | 5         | 0.82%   |
| AMD E                   | 4         | 0.65%   |
| AMD Athlon 64 X2        | 4         | 0.65%   |
| Intel Pentium Silver    | 3         | 0.49%   |
| Intel Core 2 Quad       | 3         | 0.49%   |
| Intel Atom              | 3         | 0.49%   |
| AMD Ryzen 7 PRO         | 3         | 0.49%   |
| AMD A6                  | 3         | 0.49%   |
| Intel Pentium Gold      | 2         | 0.33%   |
| Intel Core i9           | 2         | 0.33%   |
| ARM Allwinner           | 2         | 0.33%   |
| AMD GX                  | 2         | 0.33%   |
| AMD Athlon II X3        | 2         | 0.33%   |
| AMD Athlon II           | 2         | 0.33%   |
| Intel Pentium M         | 1         | 0.16%   |
| Intel Pentium D         | 1         | 0.16%   |
| Intel Pentium 4         | 1         | 0.16%   |
| Intel Core m3           | 1         | 0.16%   |
| ARM BCM                 | 1         | 0.16%   |
| AMD Ryzen Threadripper  | 1         | 0.16%   |
| AMD Ryzen 3 PRO         | 1         | 0.16%   |
| AMD Phenom II X6        | 1         | 0.16%   |
| AMD Phenom II X4        | 1         | 0.16%   |
| AMD Phenom II X3        | 1         | 0.16%   |
| AMD Phenom              | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 206       | 33.72%  |
| 4       | 202       | 33.06%  |
| 6       | 61        | 9.98%   |
| 8       | 55        | 9%      |
| 12      | 22        | 3.6%    |
| 10      | 17        | 2.78%   |
| 16      | 12        | 1.96%   |
| 14      | 12        | 1.96%   |
| 1       | 9         | 1.47%   |
| Unknown | 7         | 1.15%   |
| 3       | 4         | 0.65%   |
| 24      | 3         | 0.49%   |
| 22      | 1         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 598       | 97.87%  |
| Unknown | 7         | 1.15%   |
| 2       | 6         | 0.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 403       | 65.74%  |
| 1       | 202       | 32.95%  |
| Unknown | 7         | 1.14%   |
| 4       | 1         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 601       | 98.36%  |
| Unknown        | 8         | 1.31%   |
| 32-bit         | 2         | 0.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 21.82%  |
| 0x306c3    | 40        | 6.51%   |
| 0x806c1    | 31        | 5.05%   |
| 0x906eb    | 30        | 4.89%   |
| 0x1067a    | 25        | 4.07%   |
| 0x08108109 | 20        | 3.26%   |
| 0x906a3    | 19        | 3.09%   |
| 0x906a4    | 15        | 2.44%   |
| 0x306a9    | 13        | 2.12%   |
| 0x806ea    | 12        | 1.95%   |
| 0x806e9    | 12        | 1.95%   |
| 0x6f2      | 12        | 1.95%   |
| 0x206a7    | 12        | 1.95%   |
| 0x0a50000d | 11        | 1.79%   |
| 0x906ea    | 10        | 1.63%   |
| 0x0a50000c | 10        | 1.63%   |
| 0x306d4    | 9         | 1.47%   |
| 0x906e9    | 8         | 1.3%    |
| 0x806ec    | 8         | 1.3%    |
| 0x506e3    | 8         | 1.3%    |
| 0x08600106 | 8         | 1.3%    |
| 0x90672    | 7         | 1.14%   |
| 0x40651    | 7         | 1.14%   |
| 0x0a20120a | 7         | 1.14%   |
| 0x08608103 | 7         | 1.14%   |
| 0x406e3    | 6         | 0.98%   |
| 0x20655    | 6         | 0.98%   |
| 0x706a8    | 5         | 0.81%   |
| 0x10676    | 5         | 0.81%   |
| 0x0a404102 | 5         | 0.81%   |
| 0xb0671    | 4         | 0.65%   |
| 0x906c0    | 4         | 0.65%   |
| 0x0a601203 | 4         | 0.65%   |
| 0x0a201016 | 4         | 0.65%   |
| 0x08701021 | 4         | 0.65%   |
| 0x0800820d | 4         | 0.65%   |
| 0xa0655    | 3         | 0.49%   |
| 0xa0653    | 3         | 0.49%   |
| 0x6fd      | 3         | 0.49%   |
| 0x20652    | 3         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 106       | 17.32%  |
| Haswell          | 56        | 9.15%   |
| Alderlake Hybrid | 47        | 7.68%   |
| Zen 3            | 45        | 7.35%   |
| Unknown          | 44        | 7.19%   |
| TigerLake        | 40        | 6.54%   |
| Penryn           | 36        | 5.88%   |
| Zen+             | 30        | 4.9%    |
| IvyBridge        | 23        | 3.76%   |
| Zen 2            | 22        | 3.59%   |
| Skylake          | 21        | 3.43%   |
| Core             | 20        | 3.27%   |
| SandyBridge      | 16        | 2.61%   |
| Westmere         | 13        | 2.12%   |
| Broadwell        | 12        | 1.96%   |
| K10              | 10        | 1.63%   |
| CometLake        | 9         | 1.47%   |
| Zen              | 8         | 1.31%   |
| Silvermont       | 7         | 1.14%   |
| Goldmont plus    | 7         | 1.14%   |
| Piledriver       | 6         | 0.98%   |
| Bobcat           | 6         | 0.98%   |
| Tremont          | 4         | 0.65%   |
| K8 Hammer        | 4         | 0.65%   |
| IceLake          | 4         | 0.65%   |
| Excavator        | 4         | 0.65%   |
| Nehalem          | 3         | 0.49%   |
| Jaguar           | 3         | 0.49%   |
| NetBurst         | 2         | 0.33%   |
| Steamroller      | 1         | 0.16%   |
| P6               | 1         | 0.16%   |
| Goldmont         | 1         | 0.16%   |
| Bonnell          | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 358       | 51.96%  |
| AMD                        | 164       | 23.8%   |
| Nvidia                     | 159       | 23.08%  |
| Matrox Electronics Systems | 6         | 0.87%   |
| Zhaoxin                    | 1         | 0.15%   |
| ASPEED Technology          | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 37        | 5.28%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 36        | 5.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 26        | 3.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21        | 3%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 21        | 3%      |
| Intel Alder Lake-P Integrated Graphics Controller                           | 19        | 2.71%   |
| Nvidia GF108 [GeForce GT 730]                                               | 17        | 2.43%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 17        | 2.43%   |
| Intel UHD Graphics 620                                                      | 15        | 2.14%   |
| Intel 82Q963/Q965 Integrated Graphics Controller                            | 13        | 1.85%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 12        | 1.71%   |
| Intel HD Graphics 620                                                       | 11        | 1.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 11        | 1.57%   |
| AMD Renoir                                                                  | 11        | 1.57%   |
| Intel HD Graphics 630                                                       | 10        | 1.43%   |
| AMD Lucienne                                                                | 10        | 1.43%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 9         | 1.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 8         | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 8         | 1.14%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 8         | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 1.14%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8         | 1.14%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8         | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                         | 7         | 1%      |
| Intel HD Graphics 6000                                                      | 6         | 0.86%   |
| AMD Rembrandt [Radeon 680M]                                                 | 6         | 0.86%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 6         | 0.86%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6         | 0.86%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 5         | 0.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 0.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 5         | 0.71%   |
| Intel JasperLake [UHD Graphics]                                             | 5         | 0.71%   |
| Intel HD Graphics 530                                                       | 5         | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 5         | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 5         | 0.71%   |
| AMD Barcelo                                                                 | 5         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 0.57%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 4         | 0.57%   |
| Intel AlderLake-S GT1                                                       | 4         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 281       | 45.84%  |
| 1 x AMD        | 130       | 21.21%  |
| 1 x Nvidia     | 83        | 13.54%  |
| Intel + Nvidia | 60        | 9.79%   |
| AMD + Nvidia   | 15        | 2.45%   |
| Other          | 12        | 1.96%   |
| Intel + AMD    | 10        | 1.63%   |
| 2 x AMD        | 8         | 1.31%   |
| 1 x Matrox     | 6         | 0.98%   |
| 2 x Intel      | 5         | 0.82%   |
| 1 x Zhaoxin    | 1         | 0.16%   |
| 1 x ASPEED     | 1         | 0.16%   |
| AMD + Matrox   | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 405       | 66.18%  |
| Unknown     | 148       | 24.18%  |
| Proprietary | 59        | 9.64%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 449       | 73.25%  |
| 0.01-0.5   | 40        | 6.53%   |
| 1.01-2.0   | 31        | 5.06%   |
| 7.01-8.0   | 27        | 4.4%    |
| 3.01-4.0   | 26        | 4.24%   |
| 0.51-1.0   | 22        | 3.59%   |
| 5.01-6.0   | 6         | 0.98%   |
| 8.01-16.0  | 6         | 0.98%   |
| 2.01-3.0   | 3         | 0.49%   |
| 16.01-24.0 | 2         | 0.33%   |
| 4.01-5.0   | 1         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 12.87%  |
| Samsung Electronics     | 53        | 9.89%   |
| BOE                     | 49        | 9.14%   |
| Chimei Innolux          | 42        | 7.84%   |
| Dell                    | 38        | 7.09%   |
| LG Display              | 31        | 5.78%   |
| Goldstar                | 21        | 3.92%   |
| Hewlett-Packard         | 20        | 3.73%   |
| BenQ                    | 20        | 3.73%   |
| Ancor Communications    | 20        | 3.73%   |
| Sharp                   | 15        | 2.8%    |
| Acer                    | 15        | 2.8%    |
| Apple                   | 13        | 2.43%   |
| Philips                 | 12        | 2.24%   |
| AOC                     | 11        | 2.05%   |
| PANDA                   | 9         | 1.68%   |
| Lenovo                  | 9         | 1.68%   |
| InfoVision              | 6         | 1.12%   |
| Iiyama                  | 6         | 1.12%   |
| Sony                    | 5         | 0.93%   |
| ViewSonic               | 4         | 0.75%   |
| ASUSTek Computer        | 4         | 0.75%   |
| Unknown                 | 4         | 0.75%   |
| Sceptre Tech            | 3         | 0.56%   |
| Mi                      | 3         | 0.56%   |
| LG Philips              | 3         | 0.56%   |
| LG Electronics          | 3         | 0.56%   |
| CSO                     | 3         | 0.56%   |
| Chi Mei Optoelectronics | 3         | 0.56%   |
| Vizio                   | 2         | 0.37%   |
| Toshiba                 | 2         | 0.37%   |
| Panasonic               | 2         | 0.37%   |
| MSI                     | 2         | 0.37%   |
| HKC                     | 2         | 0.37%   |
| Eizo                    | 2         | 0.37%   |
| Compal                  | 2         | 0.37%   |
| YSD                     | 1         | 0.19%   |
| Unknown                 | 1         | 0.19%   |
| TCL                     | 1         | 0.19%   |
| RTK                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications ASUS VS229 ACI22D3 1920x1080 475x267mm 21.5-inch | 13        | 2.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 1.64%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 0.73%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 4         | 0.73%   |
| Unknown                                                               | 4         | 0.73%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 3         | 0.55%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 3         | 0.55%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 3         | 0.55%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN13C6 1920x1200 286x178mm 13.3-inch      | 3         | 0.55%   |
| BenQ PD2700U BNQ802E 3840x2160 597x336mm 27.0-inch                    | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.55%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 3         | 0.55%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 2         | 0.36%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 2         | 0.36%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.36%   |
| Samsung Electronics S22D300 SAM0B3E 1920x1080 477x268mm 21.5-inch     | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDC415A 3200x1800 293x165mm 13.2-inch | 2         | 0.36%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 2         | 0.36%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.36%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.36%   |
| LG Electronics LCD Monitor LG FULL HD                                 | 2         | 0.36%   |
| LG Display LCD Monitor LGD06EA 2560x1600 366x229mm 17.0-inch          | 2         | 0.36%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.36%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.36%   |
| LG Display LCD Monitor LGD03F1 1600x900 309x174mm 14.0-inch           | 2         | 0.36%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch               | 2         | 0.36%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 2         | 0.36%   |
| InfoVision LCD Monitor IVO854A 1920x1200 286x179mm 13.3-inch          | 2         | 0.36%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch            | 2         | 0.36%   |
| Hewlett-Packard 23xi HWP3032 1920x1080 509x286mm 23.0-inch            | 2         | 0.36%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 0.36%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2         | 0.36%   |
| Dell G3223Q DEL428C 3840x2160 708x399mm 32.0-inch                     | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 2         | 0.36%   |
| BOE LCD Monitor BOE092E 1920x1080 310x173mm 14.0-inch                 | 2         | 0.36%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                 | 2         | 0.36%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 2         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 246       | 47.67%  |
| 1366x768 (WXGA)    | 57        | 11.05%  |
| 3840x2160 (4K)     | 39        | 7.56%   |
| 2560x1440 (QHD)    | 25        | 4.84%   |
| 1920x1200 (WUXGA)  | 23        | 4.46%   |
| 1600x900 (HD+)     | 19        | 3.68%   |
| 1440x900 (WXGA+)   | 12        | 2.33%   |
| Unknown            | 11        | 2.13%   |
| 1280x1024 (SXGA)   | 10        | 1.94%   |
| 3440x1440          | 7         | 1.36%   |
| 2560x1600          | 7         | 1.36%   |
| 1280x800 (WXGA)    | 7         | 1.36%   |
| 3840x2400          | 6         | 1.16%   |
| 1680x1050 (WSXGA+) | 6         | 1.16%   |
| 2880x1800          | 4         | 0.78%   |
| 3840x1600          | 3         | 0.58%   |
| 3000x2000          | 3         | 0.58%   |
| 2560x1080          | 3         | 0.58%   |
| 3840x1200          | 2         | 0.39%   |
| 1920x540           | 2         | 0.39%   |
| 1800x1200          | 2         | 0.39%   |
| 7680x2160          | 1         | 0.19%   |
| 7280x2160          | 1         | 0.19%   |
| 6400x2160          | 1         | 0.19%   |
| 6400x1440          | 1         | 0.19%   |
| 5760x2160          | 1         | 0.19%   |
| 4480x1440          | 1         | 0.19%   |
| 3840x1100          | 1         | 0.19%   |
| 3840x1080          | 1         | 0.19%   |
| 3456x2160          | 1         | 0.19%   |
| 3286x1080          | 1         | 0.19%   |
| 3200x1800 (QHD+)   | 1         | 0.19%   |
| 3072x1920          | 1         | 0.19%   |
| 2966x900           | 1         | 0.19%   |
| 2880x1620          | 1         | 0.19%   |
| 2800x1752          | 1         | 0.19%   |
| 2288x1287          | 1         | 0.19%   |
| 2256x1504          | 1         | 0.19%   |
| 2240x1400          | 1         | 0.19%   |
| 2160x1440          | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 111       | 21.02%  |
| 13      | 86        | 16.29%  |
| 14      | 51        | 9.66%   |
| 24      | 46        | 8.71%   |
| 27      | 42        | 7.95%   |
| 21      | 37        | 7.01%   |
| 23      | 26        | 4.92%   |
| Unknown | 24        | 4.55%   |
| 17      | 15        | 2.84%   |
| 31      | 12        | 2.27%   |
| 34      | 10        | 1.89%   |
| 20      | 7         | 1.33%   |
| 18      | 7         | 1.33%   |
| 11      | 7         | 1.33%   |
| 19      | 6         | 1.14%   |
| 12      | 6         | 1.14%   |
| 22      | 4         | 0.76%   |
| 16      | 4         | 0.76%   |
| 32      | 3         | 0.57%   |
| 26      | 3         | 0.57%   |
| 10      | 3         | 0.57%   |
| 72      | 2         | 0.38%   |
| 40      | 2         | 0.38%   |
| 37      | 2         | 0.38%   |
| 142     | 1         | 0.19%   |
| 85      | 1         | 0.19%   |
| 84      | 1         | 0.19%   |
| 75      | 1         | 0.19%   |
| 66      | 1         | 0.19%   |
| 54      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 49      | 1         | 0.19%   |
| 48      | 1         | 0.19%   |
| 43      | 1         | 0.19%   |
| 39      | 1         | 0.19%   |
| 28      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 199       | 38.34%  |
| 501-600        | 105       | 20.23%  |
| 201-300        | 69        | 13.29%  |
| 401-500        | 57        | 10.98%  |
| Unknown        | 24        | 4.62%   |
| 601-700        | 18        | 3.47%   |
| 351-400        | 18        | 3.47%   |
| 701-800        | 13        | 2.5%    |
| 801-900        | 5         | 0.96%   |
| 1501-2000      | 5         | 0.96%   |
| 1001-1500      | 4         | 0.77%   |
| More than 2000 | 1         | 0.19%   |
| 901-1000       | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 347       | 73.05%  |
| 16/10   | 71        | 14.95%  |
| Unknown | 22        | 4.63%   |
| 21/9    | 12        | 2.53%   |
| 5/4     | 9         | 1.89%   |
| 3/2     | 7         | 1.47%   |
| 4/3     | 3         | 0.63%   |
| 32/9    | 1         | 0.21%   |
| 3.40    | 1         | 0.21%   |
| 1.00    | 1         | 0.21%   |
| 0.45    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 109       | 20.64%  |
| 81-90          | 95        | 17.99%  |
| 201-250        | 86        | 16.29%  |
| 301-350        | 44        | 8.33%   |
| 71-80          | 40        | 7.58%   |
| 351-500        | 26        | 4.92%   |
| Unknown        | 24        | 4.55%   |
| 251-300        | 21        | 3.98%   |
| 151-200        | 21        | 3.98%   |
| More than 1000 | 11        | 2.08%   |
| 141-150        | 10        | 1.89%   |
| 121-130        | 9         | 1.7%    |
| 51-60          | 8         | 1.52%   |
| 111-120        | 7         | 1.33%   |
| 61-70          | 6         | 1.14%   |
| 501-1000       | 6         | 1.14%   |
| 41-50          | 3         | 0.57%   |
| 131-140        | 2         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 170       | 33.27%  |
| 51-100        | 128       | 25.05%  |
| 101-120       | 103       | 20.16%  |
| 161-240       | 56        | 10.96%  |
| Unknown       | 24        | 4.7%    |
| More than 240 | 21        | 4.11%   |
| 1-50          | 9         | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 369       | 59.81%  |
| 0     | 153       | 24.8%   |
| 2     | 84        | 13.61%  |
| 3     | 11        | 1.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 340       | 38.42%  |
| Intel                             | 312       | 35.25%  |
| Qualcomm Atheros                  | 62        | 7.01%   |
| Broadcom                          | 35        | 3.95%   |
| MediaTek                          | 21        | 2.37%   |
| ASIX Electronics                  | 13        | 1.47%   |
| Nvidia                            | 12        | 1.36%   |
| Broadcom Limited                  | 11        | 1.24%   |
| Marvell Technology Group          | 8         | 0.9%    |
| TP-Link                           | 7         | 0.79%   |
| Qualcomm                          | 6         | 0.68%   |
| Xiaomi                            | 5         | 0.56%   |
| Aquantia                          | 4         | 0.45%   |
| Ralink Technology                 | 3         | 0.34%   |
| NetGear                           | 3         | 0.34%   |
| D-Link                            | 3         | 0.34%   |
| ASUSTek Computer                  | 3         | 0.34%   |
| Sierra Wireless                   | 2         | 0.23%   |
| Ralink                            | 2         | 0.23%   |
| Microsoft                         | 2         | 0.23%   |
| Mellanox Technologies             | 2         | 0.23%   |
| Google                            | 2         | 0.23%   |
| Ericsson Business Mobile Networks | 2         | 0.23%   |
| 3Com                              | 2         | 0.23%   |
| Wacom                             | 1         | 0.11%   |
| U-Blox                            | 1         | 0.11%   |
| SysKonnect                        | 1         | 0.11%   |
| Spreadtrum Communications         | 1         | 0.11%   |
| Solarflare Communications         | 1         | 0.11%   |
| Raspberry Pi                      | 1         | 0.11%   |
| Qualcomm Atheros Communications   | 1         | 0.11%   |
| OPPO Electronics                  | 1         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.11%   |
| Microchip Technology              | 1         | 0.11%   |
| MCS                               | 1         | 0.11%   |
| Linksys                           | 1         | 0.11%   |
| Lenovo                            | 1         | 0.11%   |
| JMicron Technology                | 1         | 0.11%   |
| IBM                               | 1         | 0.11%   |
| Fujitsu                           | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 230       | 22.18%  |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 33        | 3.18%   |
| Intel Wi-Fi 6 AX200                                               | 32        | 3.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 31        | 2.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 26        | 2.51%   |
| Intel Wi-Fi 6 AX201                                               | 26        | 2.51%   |
| Intel Wireless 8265 / 8275                                        | 25        | 2.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 24        | 2.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 1.93%   |
| Intel I211 Gigabit Network Connection                             | 17        | 1.64%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 14        | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.16%   |
| Intel 82566DM Gigabit Network Connection                          | 12        | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 1.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 1.06%   |
| Intel Wireless 7260                                               | 11        | 1.06%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 10        | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10        | 0.96%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.87%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 8         | 0.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 0.68%   |
| Intel Wireless 7265                                               | 7         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 7         | 0.68%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.68%   |
| Intel Wireless-AC 9260                                            | 6         | 0.58%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.58%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 6         | 0.58%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 5         | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 0.48%   |
| Intel Wireless 8260                                               | 5         | 0.48%   |
| Intel Ethernet Connection (16) I219-V                             | 5         | 0.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.48%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 5         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 243       | 54.48%  |
| Realtek Semiconductor           | 67        | 15.02%  |
| Qualcomm Atheros                | 51        | 11.43%  |
| Broadcom                        | 23        | 5.16%   |
| MediaTek                        | 19        | 4.26%   |
| Broadcom Limited                | 10        | 2.24%   |
| TP-Link                         | 6         | 1.35%   |
| Qualcomm                        | 5         | 1.12%   |
| Ralink Technology               | 3         | 0.67%   |
| NetGear                         | 3         | 0.67%   |
| D-Link                          | 3         | 0.67%   |
| ASUSTek Computer                | 3         | 0.67%   |
| Sierra Wireless                 | 2         | 0.45%   |
| Ralink                          | 2         | 0.45%   |
| Wacom                           | 1         | 0.22%   |
| Qualcomm Atheros Communications | 1         | 0.22%   |
| Microsoft                       | 1         | 0.22%   |
| Marvell Technology Group        | 1         | 0.22%   |
| Linksys                         | 1         | 0.22%   |
| Edimax Technology               | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                               | 33        | 7.33%   |
| Intel Wi-Fi 6 AX200                                            | 32        | 7.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 31        | 6.89%   |
| Intel Wi-Fi 6 AX201                                            | 26        | 5.78%   |
| Intel Wireless 8265 / 8275                                     | 25        | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 2.44%   |
| Intel Wireless 7260                                            | 11        | 2.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 10        | 2.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 10        | 2.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 2%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 8         | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 7         | 1.56%   |
| Intel Wireless 7265                                            | 7         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.56%   |
| Intel Wireless-AC 9260                                         | 6         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 1.33%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 6         | 1.33%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 5         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1.11%   |
| Intel Wireless 8260                                            | 5         | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 1.11%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 5         | 1.11%   |
| Intel 700 Series Chipset Family Wi-Fi                          | 5         | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.89%   |
| Realtek 802.11ac NIC                                           | 4         | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 0.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 0.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 0.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.67%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 3         | 0.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 316       | 55.93%  |
| Intel                     | 154       | 27.26%  |
| Qualcomm Atheros          | 17        | 3.01%   |
| Broadcom                  | 14        | 2.48%   |
| ASIX Electronics          | 13        | 2.3%    |
| Nvidia                    | 12        | 2.12%   |
| Marvell Technology Group  | 7         | 1.24%   |
| Xiaomi                    | 5         | 0.88%   |
| Aquantia                  | 4         | 0.71%   |
| MediaTek                  | 2         | 0.35%   |
| Google                    | 2         | 0.35%   |
| 3Com                      | 2         | 0.35%   |
| TP-Link                   | 1         | 0.18%   |
| SysKonnect                | 1         | 0.18%   |
| Spreadtrum Communications | 1         | 0.18%   |
| Solarflare Communications | 1         | 0.18%   |
| Qualcomm                  | 1         | 0.18%   |
| OPPO Electronics          | 1         | 0.18%   |
| Microsoft                 | 1         | 0.18%   |
| Microchip Technology      | 1         | 0.18%   |
| Mellanox Technologies     | 1         | 0.18%   |
| Lenovo                    | 1         | 0.18%   |
| JMicron Technology        | 1         | 0.18%   |
| IBM                       | 1         | 0.18%   |
| Emulex                    | 1         | 0.18%   |
| DisplayLink               | 1         | 0.18%   |
| D-Link System             | 1         | 0.18%   |
| Broadcom Limited          | 1         | 0.18%   |
| Apple                     | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 230       | 39.93%  |
| Realtek RTL8125 2.5GbE Controller                                   | 26        | 4.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 24        | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 20        | 3.47%   |
| Intel I211 Gigabit Network Connection                               | 17        | 2.95%   |
| Realtek RTL8152 Fast Ethernet Adapter                               | 16        | 2.78%   |
| Intel Ethernet Controller I225-V                                    | 14        | 2.43%   |
| Intel Ethernet Connection (4) I219-LM                               | 12        | 2.08%   |
| Intel 82566DM Gigabit Network Connection                            | 12        | 2.08%   |
| ASIX AX88179 Gigabit Ethernet                                       | 12        | 2.08%   |
| Intel Ethernet Connection (13) I219-V                               | 10        | 1.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 10        | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                | 7         | 1.22%   |
| Intel Ethernet Connection I217-LM                                   | 6         | 1.04%   |
| Intel Ethernet Connection (16) I219-V                               | 5         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 4         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                            | 4         | 0.69%   |
| Nvidia MCP61 Ethernet                                               | 4         | 0.69%   |
| Intel Ethernet Connection I217-V                                    | 4         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                | 4         | 0.69%   |
| Intel 82579V Gigabit Network Connection                             | 4         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                    | 3         | 0.52%   |
| Nvidia MCP65 Ethernet                                               | 3         | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller             | 3         | 0.52%   |
| Intel I350 Gigabit Network Connection                               | 3         | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                               | 3         | 0.52%   |
| Intel Ethernet Connection (13) I219-LM                              | 3         | 0.52%   |
| Intel Ethernet Connection (11) I219-LM                              | 3         | 0.52%   |
| Aquantia AQC113CS NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter               | 2         | 0.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                       | 2         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                               | 2         | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet      | 2         | 0.35%   |
| Nvidia MCP79 Ethernet                                               | 2         | 0.35%   |
| MediaTek Armor X10 Pro                                              | 2         | 0.35%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller             | 2         | 0.35%   |
| Intel Ethernet Connection I219-V                                    | 2         | 0.35%   |
| Intel Ethernet Connection I219-LM                                   | 2         | 0.35%   |
| Intel Ethernet Connection I218-V                                    | 2         | 0.35%   |
| Intel Ethernet Connection I218-LM                                   | 2         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 508       | 53.93%  |
| WiFi     | 424       | 45.01%  |
| Modem    | 7         | 0.74%   |
| Unknown  | 3         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 352       | 56.05%  |
| WiFi     | 276       | 43.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 285       | 46.57%  |
| 1     | 284       | 46.41%  |
| 3     | 17        | 2.78%   |
| 0     | 17        | 2.78%   |
| 4     | 7         | 1.14%   |
| 9     | 1         | 0.16%   |
| 6     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 455       | 74.1%   |
| Yes  | 159       | 25.9%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 221       | 58.93%  |
| Realtek Semiconductor           | 39        | 10.4%   |
| Qualcomm Atheros Communications | 18        | 4.8%    |
| Foxconn / Hon Hai               | 16        | 4.27%   |
| Apple                           | 15        | 4%      |
| Cambridge Silicon Radio         | 12        | 3.2%    |
| Lite-On Technology              | 9         | 2.4%    |
| IMC Networks                    | 9         | 2.4%    |
| Broadcom                        | 8         | 2.13%   |
| ASUSTek Computer                | 7         | 1.87%   |
| Realtek                         | 4         | 1.07%   |
| Dell                            | 3         | 0.8%    |
| TP-Link                         | 2         | 0.53%   |
| Toshiba                         | 2         | 0.53%   |
| MediaTek                        | 2         | 0.53%   |
| Hewlett-Packard                 | 2         | 0.53%   |
| Ralink Technology               | 1         | 0.27%   |
| Micro Star International        | 1         | 0.27%   |
| Marvell Semiconductor           | 1         | 0.27%   |
| Integrated System Solution      | 1         | 0.27%   |
| Foxconn International           | 1         | 0.27%   |
| Edimax Technology               | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 50        | 13.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 48        | 12.8%   |
| Intel AX201 Bluetooth                               | 39        | 10.4%   |
| Realtek Bluetooth Radio                             | 35        | 9.33%   |
| Intel Bluetooth Device                              | 31        | 8.27%   |
| Intel AX200 Bluetooth                               | 31        | 8.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 3.2%    |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 2.93%   |
| Intel AX210 Bluetooth                               | 9         | 2.4%    |
| Apple Bluetooth USB Host Controller                 | 8         | 2.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 1.87%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.07%   |
| Realtek Bluetooth Radio                             | 4         | 1.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.07%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.07%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.07%   |
| Apple Bluetooth Host Controller                     | 4         | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.8%    |
| Lite-On Wireless_Device                             | 3         | 0.8%    |
| Lite-On Bluetooth Device                            | 3         | 0.8%    |
| IMC Networks Wireless_Device                        | 3         | 0.8%    |
| Dell BCM20702A0 Bluetooth Module                    | 3         | 0.8%    |
| ASUS ASUS USB-BT500                                 | 3         | 0.8%    |
| TP-Link UB500 Adapter                               | 2         | 0.53%   |
| MediaTek Wireless_Device                            | 2         | 0.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.53%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.53%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.53%   |
| Apple Bluetooth HCI                                 | 2         | 0.53%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.27%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.27%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.27%   |
| Micro Star International Bluetooth EDR Device       | 1         | 0.27%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.27%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.27%   |
| Integrated System Solution Bluetooth Device         | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 420       | 52.5%   |
| AMD                          | 170       | 21.25%  |
| Nvidia                       | 116       | 14.5%   |
| C-Media Electronics          | 17        | 2.13%   |
| Logitech                     | 12        | 1.5%    |
| ASUSTek Computer             | 6         | 0.75%   |
| Realtek Semiconductor        | 5         | 0.63%   |
| Creative Labs                | 5         | 0.63%   |
| Kingston Technology          | 4         | 0.5%    |
| GN Netcom                    | 4         | 0.5%    |
| SteelSeries ApS              | 3         | 0.38%   |
| Plantronics                  | 3         | 0.38%   |
| Lenovo                       | 3         | 0.38%   |
| Hewlett-Packard              | 3         | 0.38%   |
| Generalplus Technology       | 3         | 0.38%   |
| Blue Microphones             | 3         | 0.38%   |
| Micro Star International     | 2         | 0.25%   |
| Audient                      | 2         | 0.25%   |
| Zhaoxin                      | 1         | 0.13%   |
| Yamaha                       | 1         | 0.13%   |
| VIA Technologies             | 1         | 0.13%   |
| USB MICROPHONE               | 1         | 0.13%   |
| Texas Instruments            | 1         | 0.13%   |
| Samson Technologies          | 1         | 0.13%   |
| OPPO Electronics             | 1         | 0.13%   |
| Microsoft                    | 1         | 0.13%   |
| JMTek                        | 1         | 0.13%   |
| Giga-Byte Technology         | 1         | 0.13%   |
| Focusrite-Novation           | 1         | 0.13%   |
| Dell                         | 1         | 0.13%   |
| D&M Holdings (Denon/Marantz) | 1         | 0.13%   |
| Creative Technology          | 1         | 0.13%   |
| Corsair                      | 1         | 0.13%   |
| Cambridge Silicon Radio      | 1         | 0.13%   |
| Beyerdynamic                 | 1         | 0.13%   |
| Asahi Kasei Microsystems     | 1         | 0.13%   |
| Apple                        | 1         | 0.13%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 87        | 8.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 4.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 41        | 4.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 41        | 4.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 40        | 4.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 3.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 36        | 3.67%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 35        | 3.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 27        | 2.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 22        | 2.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 2.14%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 19        | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19        | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 17        | 1.73%   |
| Intel 200 Series PCH HD Audio                                              | 17        | 1.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14        | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 1.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 11        | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 1.12%   |
| Intel Broadwell-U Audio Controller                                         | 11        | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 1.12%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 0.92%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9         | 0.92%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                              | 8         | 0.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 0.82%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 8         | 0.82%   |
| AMD FCH Azalia Controller                                                  | 8         | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8         | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 8         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.71%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1           | 7         | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.61%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 112       | 19.68%  |
| SK hynix                                | 92        | 16.17%  |
| Kingston                                | 79        | 13.88%  |
| Crucial                                 | 68        | 11.95%  |
| Unknown                                 | 62        | 10.9%   |
| Micron Technology                       | 47        | 8.26%   |
| Corsair                                 | 19        | 3.34%   |
| G.Skill                                 | 16        | 2.81%   |
| A-DATA Technology                       | 14        | 2.46%   |
| Micro Memory Bank                       | 8         | 1.41%   |
| Elpida                                  | 7         | 1.23%   |
| Patriot                                 | 6         | 1.05%   |
| Ramaxel Technology                      | 5         | 0.88%   |
| Unknown                                 | 5         | 0.88%   |
| Unknown (ABCD)                          | 4         | 0.7%    |
| Nanya Technology                        | 3         | 0.53%   |
| Transcend                               | 2         | 0.35%   |
| Team                                    | 2         | 0.35%   |
| Silicon Power Computer & Communications | 2         | 0.35%   |
| ASint Technology                        | 2         | 0.35%   |
| V-Color                                 | 1         | 0.18%   |
| Unknown (768A)                          | 1         | 0.18%   |
| Unknown (0x7FFF)                        | 1         | 0.18%   |
| Unknown (0x0E9D)                        | 1         | 0.18%   |
| Toshiba                                 | 1         | 0.18%   |
| Smart                                   | 1         | 0.18%   |
| PKI                                     | 1         | 0.18%   |
| Patriot Memory (PDP Systems)            | 1         | 0.18%   |
| Neo Forza                               | 1         | 0.18%   |
| KLEVV                                   | 1         | 0.18%   |
| Hikvision                               | 1         | 0.18%   |
| A Force                                 | 1         | 0.18%   |
| <Invalid>                               | 1         | 0.18%   |
| 48spaces                                | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s                          | 29        | 4.75%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s                            | 15        | 2.46%   |
| Samsung RAM M378A1K43DB2-CTD 8GB DIMM DDR4 4333MT/s                              | 10        | 1.64%   |
| Micro Memory Bank RAM FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF 2GB DIMM DDR2 667MT/s | 8         | 1.31%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                            | 7         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                           | 6         | 0.98%   |
| Patriot RAM PSD38G13332 8GB DIMM DDR3 1333MT/s                                   | 6         | 0.98%   |
| Unknown RAM Module 2GB DIMM SDRAM                                                | 5         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                            | 5         | 0.82%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s                            | 5         | 0.82%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                             | 5         | 0.82%   |
| Unknown                                                                          | 5         | 0.82%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                             | 4         | 0.66%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                             | 4         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s                 | 4         | 0.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                            | 4         | 0.66%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                            | 4         | 0.66%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s                            | 4         | 0.66%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                              | 3         | 0.49%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                                     | 3         | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                           | 3         | 0.49%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s                           | 3         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s                           | 3         | 0.49%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                           | 3         | 0.49%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                                      | 3         | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s                      | 3         | 0.49%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3266MT/s                              | 3         | 0.49%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                            | 3         | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                             | 3         | 0.49%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s                            | 3         | 0.49%   |
| Crucial RAM 524D313238363441413636372E384648FFFF 1GB DIMM DDR2 667MT/s           | 3         | 0.49%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s                         | 3         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3                                               | 2         | 0.33%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                              | 2         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                                         | 2         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                                      | 2         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3                                               | 2         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                       | 2         | 0.33%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                                            | 2         | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                         | 2         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 252       | 48.93%  |
| DDR3    | 113       | 21.94%  |
| DDR2    | 32        | 6.21%   |
| DDR5    | 28        | 5.44%   |
| LPDDR4  | 24        | 4.66%   |
| Unknown | 22        | 4.27%   |
| SDRAM   | 15        | 2.91%   |
| LPDDR3  | 13        | 2.52%   |
| LPDDR5  | 10        | 1.94%   |
| DDR     | 6         | 1.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 252       | 48.93%  |
| DIMM         | 209       | 40.58%  |
| Row Of Chips | 48        | 9.32%   |
| Chip         | 2         | 0.39%   |
| Unknown      | 2         | 0.39%   |
| RIMM         | 1         | 0.19%   |
| FB-DIMM      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 223       | 40.33%  |
| 4096  | 110       | 19.89%  |
| 2048  | 80        | 14.47%  |
| 16384 | 77        | 13.92%  |
| 32768 | 31        | 5.61%   |
| 1024  | 24        | 4.34%   |
| 512   | 6         | 1.08%   |
| 256   | 1         | 0.18%   |
| 64    | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 91        | 17.07%  |
| 2667    | 79        | 14.82%  |
| 1600    | 68        | 12.76%  |
| 2400    | 30        | 5.63%   |
| 667     | 24        | 4.5%    |
| 1333    | 21        | 3.94%   |
| 4800    | 20        | 3.75%   |
| 2133    | 20        | 3.75%   |
| 3600    | 18        | 3.38%   |
| 1866    | 17        | 3.19%   |
| Unknown | 17        | 3.19%   |
| 4267    | 16        | 3%      |
| 800     | 15        | 2.81%   |
| 6400    | 11        | 2.06%   |
| 4333    | 10        | 1.88%   |
| 1066    | 9         | 1.69%   |
| 1867    | 8         | 1.5%    |
| 1067    | 6         | 1.13%   |
| 3266    | 4         | 0.75%   |
| 2666    | 4         | 0.75%   |
| 1334    | 4         | 0.75%   |
| 6000    | 3         | 0.56%   |
| 5200    | 3         | 0.56%   |
| 3933    | 3         | 0.56%   |
| 3400    | 3         | 0.56%   |
| 8400    | 2         | 0.38%   |
| 4266    | 2         | 0.38%   |
| 3733    | 2         | 0.38%   |
| 3534    | 2         | 0.38%   |
| 2866    | 2         | 0.38%   |
| 2048    | 2         | 0.38%   |
| 1639    | 2         | 0.38%   |
| 5600    | 1         | 0.19%   |
| 5354    | 1         | 0.19%   |
| 4199    | 1         | 0.19%   |
| 3800    | 1         | 0.19%   |
| 3500    | 1         | 0.19%   |
| 3100    | 1         | 0.19%   |
| 3000    | 1         | 0.19%   |
| 2933    | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 4         | 28.57%  |
| Canon               | 3         | 21.43%  |
| Hewlett-Packard     | 2         | 14.29%  |
| Zebra               | 1         | 7.14%   |
| Seiko Epson         | 1         | 7.14%   |
| Samsung Electronics | 1         | 7.14%   |
| Pantum              | 1         | 7.14%   |
| Dymo-CoStar         | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Zebra Printer                    | 1         | 7.14%   |
| Seiko Epson L6290 Series         | 1         | 7.14%   |
| Samsung M2020 Series             | 1         | 7.14%   |
| Pantum P2500W series             | 1         | 7.14%   |
| HP LaserJet P2035                | 1         | 7.14%   |
| HP ENVY 5540 series              | 1         | 7.14%   |
| Dymo-CoStar DYMO LabelWriter DUO | 1         | 7.14%   |
| Canon PIXMA iP4300 Printer       | 1         | 7.14%   |
| Canon MF4010 series              | 1         | 7.14%   |
| Canon MF3010                     | 1         | 7.14%   |
| Brother MFC-L2710DW series       | 1         | 7.14%   |
| Brother HL-3040CN series         | 1         | 7.14%   |
| Brother HL-1110 series           | 1         | 7.14%   |
| Brother DCP-7030                 | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Seiko Epson     | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 25%     |
| HP ScanJet 82x0C                            | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 25%     |
| Canon CanoScan LiDE 210                     | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 70        | 21.02%  |
| IMC Networks                           | 38        | 11.41%  |
| Acer                                   | 36        | 10.81%  |
| Realtek Semiconductor                  | 22        | 6.61%   |
| Microdia                               | 22        | 6.61%   |
| Logitech                               | 20        | 6.01%   |
| Bison Electronics                      | 17        | 5.11%   |
| Quanta                                 | 16        | 4.8%    |
| Sunplus Innovation Technology          | 12        | 3.6%    |
| Syntek                                 | 9         | 2.7%    |
| Lite-On Technology                     | 9         | 2.7%    |
| Luxvisions Innotech Limited            | 8         | 2.4%    |
| Microsoft                              | 7         | 2.1%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.1%    |
| Apple                                  | 7         | 2.1%    |
| Generalplus Technology                 | 5         | 1.5%    |
| Suyin                                  | 4         | 1.2%    |
| Lenovo                                 | 4         | 1.2%    |
| USB Camera                             | 2         | 0.6%    |
| SunplusIT                              | 2         | 0.6%    |
| Sonix Technology                       | 2         | 0.6%    |
| Silicon Motion                         | 2         | 0.6%    |
| Alcor Micro                            | 2         | 0.6%    |
| ValueHD                                | 1         | 0.3%    |
| Samsung Electronics                    | 1         | 0.3%    |
| Ricoh                                  | 1         | 0.3%    |
| OmniVision Technologies                | 1         | 0.3%    |
| Magic Control Technology               | 1         | 0.3%    |
| Jieli Technology                       | 1         | 0.3%    |
| GEMBIRD                                | 1         | 0.3%    |
| EVGA                                   | 1         | 0.3%    |
| Denron                                 | 1         | 0.3%    |
| ALi                                    | 1         | 0.3%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Acer BisonCam, NB Pro                               | 28        | 8.26%   |
| Chicony Integrated Camera                           | 17        | 5.01%   |
| Microdia Integrated_Webcam_HD                       | 16        | 4.72%   |
| Realtek Integrated_Webcam_HD                        | 12        | 3.54%   |
| IMC Networks Integrated Camera                      | 11        | 3.24%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 10        | 2.95%   |
| Syntek Integrated Camera                            | 8         | 2.36%   |
| Chicony HD Webcam                                   | 8         | 2.36%   |
| Sunplus Integrated_Webcam_HD                        | 7         | 2.06%   |
| Logitech HD Pro Webcam C920                         | 6         | 1.77%   |
| Logitech Webcam C270                                | 5         | 1.47%   |
| Lite-On Integrated Camera                           | 5         | 1.47%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.47%   |
| Chicony HP HD Camera                                | 5         | 1.47%   |
| Chicony HD User Facing                              | 5         | 1.47%   |
| Bison Integrated Camera                             | 5         | 1.47%   |
| Generalplus GENERAL WEBCAM                          | 4         | 1.18%   |
| Chicony USB2.0 Camera                               | 4         | 1.18%   |
| Acer Integrated Camera                              | 4         | 1.18%   |
| Quanta ov9734_techfront_camera                      | 3         | 0.88%   |
| Quanta HP HD Camera                                 | 3         | 0.88%   |
| Quanta HD User Facing                               | 3         | 0.88%   |
| Luxvisions Innotech Limited HP 5MP Camera           | 3         | 0.88%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 0.88%   |
| Chicony USB 2.0 Camera                              | 3         | 0.88%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.88%   |
| Chicony HP Webcam                                   | 3         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 3         | 0.88%   |
| Bison Integrated RGB Camera                         | 3         | 0.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 3         | 0.88%   |
| USB Camera USB Camera                               | 2         | 0.59%   |
| Sunplus HP Wide Vision HD                           | 2         | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                          | 2         | 0.59%   |
| Realtek USB Camera                                  | 2         | 0.59%   |
| Realtek Integrated Webcam                           | 2         | 0.59%   |
| Quanta VGA WebCam                                   | 2         | 0.59%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.59%   |
| Microsoft LifeCam HD-3000                           | 2         | 0.59%   |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 0.59%   |
| Logitech C920 PRO HD Webcam                         | 2         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 28        | 40.58%  |
| Validity Sensors                   | 19        | 27.54%  |
| Shenzhen Goodix Technology         | 9         | 13.04%  |
| Upek                               | 3         | 4.35%   |
| STMicroelectronics                 | 3         | 4.35%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.9%    |
| LighTuning Technology              | 2         | 2.9%    |
| Focal-systems.Corp                 | 1         | 1.45%   |
| Elan Microelectronics              | 1         | 1.45%   |
| AuthenTec                          | 1         | 1.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 15.94%  |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 11.59%  |
| Validity Sensors Synaptics WBDI                                            | 5         | 7.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 5.8%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 5.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 5.8%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 5.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4.35%   |
| Synaptics UWP WBDI Device                                                  | 3         | 4.35%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.9%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 2.9%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.45%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.45%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.45%   |
| Synaptics UWP WBDI                                                         | 1         | 1.45%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.45%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.45%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.45%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 1.45%   |
| Unknown                                                                    | 1         | 1.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 15        | 46.88%  |
| Broadcom              | 9         | 28.13%  |
| Lenovo                | 3         | 9.38%   |
| Realtek Semiconductor | 2         | 6.25%   |
| Yubico.com            | 1         | 3.13%   |
| Upek                  | 1         | 3.13%   |
| SCM Microsystems      | 1         | 3.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 43.75%  |
| Broadcom 58200                                                               | 4         | 12.5%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 9.38%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 9.38%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 6.25%   |
| Broadcom 5880                                                                | 2         | 6.25%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 3.13%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.13%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 3.13%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 319       | 51.7%   |
| 1     | 246       | 39.87%  |
| 2     | 47        | 7.62%   |
| 3     | 4         | 0.65%   |
| 5     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 157       | 48.91%  |
| Fingerprint reader       | 68        | 21.18%  |
| Chipcard                 | 25        | 7.79%   |
| Multimedia controller    | 22        | 6.85%   |
| Net/wireless             | 19        | 5.92%   |
| Camera                   | 15        | 4.67%   |
| Bluetooth                | 4         | 1.25%   |
| Unassigned class         | 3         | 0.93%   |
| Communication controller | 3         | 0.93%   |
| Wireless                 | 2         | 0.62%   |
| Storage                  | 1         | 0.31%   |
| Sound                    | 1         | 0.31%   |
| Net/ethernet             | 1         | 0.31%   |


Linux in Belgium - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Belgium.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Belgium/Desktop/README.md) and [notebooks](/Location/Belgium/Notebook/README.md).

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

Total: 2970

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [bb5a34d03f](https://linux-hardware.org/?probe=bb5a34d03f) | Oct 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [951a03d2ad](https://linux-hardware.org/?probe=951a03d2ad) | Sep 30, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [7f47d1f656](https://linux-hardware.org/?probe=7f47d1f656) | Sep 30, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [a343a1c573](https://linux-hardware.org/?probe=a343a1c573) | Sep 30, 2023 |
| Getac         | T800G2                      | Tablet      | [ede8155598](https://linux-hardware.org/?probe=ede8155598) | Sep 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5d157102ea](https://linux-hardware.org/?probe=5d157102ea) | Sep 29, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [16dabb2f6e](https://linux-hardware.org/?probe=16dabb2f6e) | Sep 29, 2023 |
| Packard Be... | EasyNote TK36               | Notebook    | [1e8f79c726](https://linux-hardware.org/?probe=1e8f79c726) | Sep 29, 2023 |
| Alienware     | x14                         | Notebook    | [048d5f6f2a](https://linux-hardware.org/?probe=048d5f6f2a) | Sep 28, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [0f2958c5a1](https://linux-hardware.org/?probe=0f2958c5a1) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [64dcffc72f](https://linux-hardware.org/?probe=64dcffc72f) | Sep 26, 2023 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [d621ecd81f](https://linux-hardware.org/?probe=d621ecd81f) | Sep 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [a58111d9ae](https://linux-hardware.org/?probe=a58111d9ae) | Sep 25, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [0c17f26ed8](https://linux-hardware.org/?probe=0c17f26ed8) | Sep 25, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [7c0b883934](https://linux-hardware.org/?probe=7c0b883934) | Sep 24, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [450edd6547](https://linux-hardware.org/?probe=450edd6547) | Sep 24, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b96887841e](https://linux-hardware.org/?probe=b96887841e) | Sep 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [c545236a4c](https://linux-hardware.org/?probe=c545236a4c) | Sep 22, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [535d4769c8](https://linux-hardware.org/?probe=535d4769c8) | Sep 22, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [0314ce541e](https://linux-hardware.org/?probe=0314ce541e) | Sep 22, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [6f6fbfc86f](https://linux-hardware.org/?probe=6f6fbfc86f) | Sep 20, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [ff02c716c1](https://linux-hardware.org/?probe=ff02c716c1) | Sep 19, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [3d4f35cc26](https://linux-hardware.org/?probe=3d4f35cc26) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [b21eddb040](https://linux-hardware.org/?probe=b21eddb040) | Sep 19, 2023 |
| HP            | 82A2                        | Desktop     | [cc179a17a8](https://linux-hardware.org/?probe=cc179a17a8) | Sep 18, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0NF0... | Notebook    | [54aa39a845](https://linux-hardware.org/?probe=54aa39a845) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [3faff3c0aa](https://linux-hardware.org/?probe=3faff3c0aa) | Sep 18, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [502aab1a11](https://linux-hardware.org/?probe=502aab1a11) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [47e95a92cc](https://linux-hardware.org/?probe=47e95a92cc) | Sep 17, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ac1361d323](https://linux-hardware.org/?probe=ac1361d323) | Sep 17, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [5fe7196179](https://linux-hardware.org/?probe=5fe7196179) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [93356dbebb](https://linux-hardware.org/?probe=93356dbebb) | Sep 17, 2023 |
| HP            | 1905                        | Desktop     | [688c5ddf16](https://linux-hardware.org/?probe=688c5ddf16) | Sep 17, 2023 |
| HP            | 1905                        | Desktop     | [562179ca0e](https://linux-hardware.org/?probe=562179ca0e) | Sep 17, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [81a1d404e3](https://linux-hardware.org/?probe=81a1d404e3) | Sep 15, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [37d6d12772](https://linux-hardware.org/?probe=37d6d12772) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [e1ac878fa3](https://linux-hardware.org/?probe=e1ac878fa3) | Sep 15, 2023 |
| Dell          | Latitude 5501               | Notebook    | [1608104990](https://linux-hardware.org/?probe=1608104990) | Sep 14, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7d22cd1af1](https://linux-hardware.org/?probe=7d22cd1af1) | Sep 11, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [c78162f5fd](https://linux-hardware.org/?probe=c78162f5fd) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [45261be082](https://linux-hardware.org/?probe=45261be082) | Sep 10, 2023 |
| HP            | 620                         | Notebook    | [6fd1497e1a](https://linux-hardware.org/?probe=6fd1497e1a) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [4dfd50fada](https://linux-hardware.org/?probe=4dfd50fada) | Sep 10, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b65fb1e357](https://linux-hardware.org/?probe=b65fb1e357) | Sep 09, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [7c51242294](https://linux-hardware.org/?probe=7c51242294) | Sep 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e48cab52a7](https://linux-hardware.org/?probe=e48cab52a7) | Sep 05, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [3747ee0c29](https://linux-hardware.org/?probe=3747ee0c29) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [7d3f9fa0e5](https://linux-hardware.org/?probe=7d3f9fa0e5) | Sep 04, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [0b3868c6bc](https://linux-hardware.org/?probe=0b3868c6bc) | Sep 04, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [58ff81abf2](https://linux-hardware.org/?probe=58ff81abf2) | Sep 03, 2023 |
| HP            | 843B                        | Desktop     | [d0cef21578](https://linux-hardware.org/?probe=d0cef21578) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [93b9808859](https://linux-hardware.org/?probe=93b9808859) | Sep 03, 2023 |
| Acer          | TravelMate 8372             | Notebook    | [709e81e4a0](https://linux-hardware.org/?probe=709e81e4a0) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [b9765f73b1](https://linux-hardware.org/?probe=b9765f73b1) | Sep 02, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [d7fcde026e](https://linux-hardware.org/?probe=d7fcde026e) | Sep 02, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [e7a06bde4e](https://linux-hardware.org/?probe=e7a06bde4e) | Sep 01, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [24743bf01d](https://linux-hardware.org/?probe=24743bf01d) | Sep 01, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [905ee212e5](https://linux-hardware.org/?probe=905ee212e5) | Sep 01, 2023 |
| Acer          | TravelMate 5760G            | Notebook    | [1a0a1749fc](https://linux-hardware.org/?probe=1a0a1749fc) | Sep 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [4cb96ee770](https://linux-hardware.org/?probe=4cb96ee770) | Sep 01, 2023 |
| Maxtang       | BYT30                       | Desktop     | [6f7fa1fde6](https://linux-hardware.org/?probe=6f7fa1fde6) | Aug 31, 2023 |
| ASUSTek       | X75VC                       | Notebook    | [4a2115b7ae](https://linux-hardware.org/?probe=4a2115b7ae) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6cd62bfac4](https://linux-hardware.org/?probe=6cd62bfac4) | Aug 31, 2023 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [189647b3df](https://linux-hardware.org/?probe=189647b3df) | Aug 31, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [abfe7c3f74](https://linux-hardware.org/?probe=abfe7c3f74) | Aug 30, 2023 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [193a50f761](https://linux-hardware.org/?probe=193a50f761) | Aug 30, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [92492caa13](https://linux-hardware.org/?probe=92492caa13) | Aug 29, 2023 |
| Acer          | Aspire 7560                 | Notebook    | [4cb158cafc](https://linux-hardware.org/?probe=4cb158cafc) | Aug 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [844b4e4dc2](https://linux-hardware.org/?probe=844b4e4dc2) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5fddb9cc18](https://linux-hardware.org/?probe=5fddb9cc18) | Aug 28, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [1afaed6ffa](https://linux-hardware.org/?probe=1afaed6ffa) | Aug 28, 2023 |
| HP            | 1905                        | Desktop     | [c1758c3a05](https://linux-hardware.org/?probe=c1758c3a05) | Aug 26, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [69824bbd6d](https://linux-hardware.org/?probe=69824bbd6d) | Aug 26, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [499c14b0f7](https://linux-hardware.org/?probe=499c14b0f7) | Aug 26, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [ac61c512ef](https://linux-hardware.org/?probe=ac61c512ef) | Aug 25, 2023 |
| Dell          | Studio 1735                 | Notebook    | [5932ab2004](https://linux-hardware.org/?probe=5932ab2004) | Aug 25, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [43686cdaa0](https://linux-hardware.org/?probe=43686cdaa0) | Aug 25, 2023 |
| Unknown       | HX90                        | Desktop     | [305cd9a7ed](https://linux-hardware.org/?probe=305cd9a7ed) | Aug 25, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [d366a928cc](https://linux-hardware.org/?probe=d366a928cc) | Aug 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [5057058532](https://linux-hardware.org/?probe=5057058532) | Aug 23, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [659ac11761](https://linux-hardware.org/?probe=659ac11761) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [05c761f480](https://linux-hardware.org/?probe=05c761f480) | Aug 22, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [1824f3c712](https://linux-hardware.org/?probe=1824f3c712) | Aug 19, 2023 |
| Dell          | 0CT017                      | Desktop     | [3bb33d455c](https://linux-hardware.org/?probe=3bb33d455c) | Aug 18, 2023 |
| Dell          | 0200DY A00                  | Desktop     | [9b94c2313c](https://linux-hardware.org/?probe=9b94c2313c) | Aug 18, 2023 |
| Dell          | 0CT017                      | Desktop     | [5f628eeffa](https://linux-hardware.org/?probe=5f628eeffa) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d0d3c76bb8](https://linux-hardware.org/?probe=d0d3c76bb8) | Aug 17, 2023 |
| ASUSTek       | M3A76-CM                    | Desktop     | [031a6edf78](https://linux-hardware.org/?probe=031a6edf78) | Aug 16, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [927eacb30f](https://linux-hardware.org/?probe=927eacb30f) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [4c4e9222ce](https://linux-hardware.org/?probe=4c4e9222ce) | Aug 16, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [aaec4c4fe1](https://linux-hardware.org/?probe=aaec4c4fe1) | Aug 16, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [166b18583b](https://linux-hardware.org/?probe=166b18583b) | Aug 15, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [488c1edd8d](https://linux-hardware.org/?probe=488c1edd8d) | Aug 13, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [6e7a8f72dd](https://linux-hardware.org/?probe=6e7a8f72dd) | Aug 10, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [d45603bb4e](https://linux-hardware.org/?probe=d45603bb4e) | Aug 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5e64d2b59e](https://linux-hardware.org/?probe=5e64d2b59e) | Aug 06, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [584974f252](https://linux-hardware.org/?probe=584974f252) | Aug 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5a0ec66589](https://linux-hardware.org/?probe=5a0ec66589) | Aug 05, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [db2732f0e8](https://linux-hardware.org/?probe=db2732f0e8) | Aug 04, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [38f7c8653b](https://linux-hardware.org/?probe=38f7c8653b) | Aug 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [deeafc23f9](https://linux-hardware.org/?probe=deeafc23f9) | Aug 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8da287a76b](https://linux-hardware.org/?probe=8da287a76b) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [9b314ec48b](https://linux-hardware.org/?probe=9b314ec48b) | Aug 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [1fa056944b](https://linux-hardware.org/?probe=1fa056944b) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [4c04d9d11e](https://linux-hardware.org/?probe=4c04d9d11e) | Aug 01, 2023 |
| HP            | 620                         | Notebook    | [eafc7ac5c3](https://linux-hardware.org/?probe=eafc7ac5c3) | Aug 01, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [c74f4bde19](https://linux-hardware.org/?probe=c74f4bde19) | Aug 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [6eb487950f](https://linux-hardware.org/?probe=6eb487950f) | Aug 01, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [93d193bdbc](https://linux-hardware.org/?probe=93d193bdbc) | Aug 01, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [1fe93c22b0](https://linux-hardware.org/?probe=1fe93c22b0) | Jul 31, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [4e2e9f1f7f](https://linux-hardware.org/?probe=4e2e9f1f7f) | Jul 31, 2023 |
| Dell          | 0M863N A00                  | Desktop     | [3c403d83cc](https://linux-hardware.org/?probe=3c403d83cc) | Jul 30, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [42bf6e1e48](https://linux-hardware.org/?probe=42bf6e1e48) | Jul 30, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | Notebook    | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| HP            | 530                         | Notebook    | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [edbd410baa](https://linux-hardware.org/?probe=edbd410baa) | Jul 30, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [d54ad601d0](https://linux-hardware.org/?probe=d54ad601d0) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Unknown       | HX90                        | Desktop     | [ba2a06600a](https://linux-hardware.org/?probe=ba2a06600a) | Jul 25, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [64595670db](https://linux-hardware.org/?probe=64595670db) | Jul 25, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [73f6f39c67](https://linux-hardware.org/?probe=73f6f39c67) | Jul 25, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [ab11ab8316](https://linux-hardware.org/?probe=ab11ab8316) | Jul 25, 2023 |
| Unknown       | HX90                        | Desktop     | [25aeb91b82](https://linux-hardware.org/?probe=25aeb91b82) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [77ee44a9fe](https://linux-hardware.org/?probe=77ee44a9fe) | Jul 23, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [6a0b0513cd](https://linux-hardware.org/?probe=6a0b0513cd) | Jul 22, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [dec408556d](https://linux-hardware.org/?probe=dec408556d) | Jul 21, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [59cf8541b4](https://linux-hardware.org/?probe=59cf8541b4) | Jul 20, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [ceda2054b7](https://linux-hardware.org/?probe=ceda2054b7) | Jul 19, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [c3ec46f79e](https://linux-hardware.org/?probe=c3ec46f79e) | Jul 19, 2023 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [2986780209](https://linux-hardware.org/?probe=2986780209) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [97c2950df7](https://linux-hardware.org/?probe=97c2950df7) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7843df6b43](https://linux-hardware.org/?probe=7843df6b43) | Jul 19, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [140d426127](https://linux-hardware.org/?probe=140d426127) | Jul 18, 2023 |
| ASUSTek       | NARRA2                      | Desktop     | [4d18b60338](https://linux-hardware.org/?probe=4d18b60338) | Jul 18, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e790be3f6e](https://linux-hardware.org/?probe=e790be3f6e) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [295bc58365](https://linux-hardware.org/?probe=295bc58365) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [782127b6f6](https://linux-hardware.org/?probe=782127b6f6) | Jul 17, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d589d40102](https://linux-hardware.org/?probe=d589d40102) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7e0ff09c1f](https://linux-hardware.org/?probe=7e0ff09c1f) | Jul 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b189eebd1c](https://linux-hardware.org/?probe=b189eebd1c) | Jul 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [0d54b47098](https://linux-hardware.org/?probe=0d54b47098) | Jul 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [8f40997f5f](https://linux-hardware.org/?probe=8f40997f5f) | Jul 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [7d19e6a8f5](https://linux-hardware.org/?probe=7d19e6a8f5) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [6d96bf0f5b](https://linux-hardware.org/?probe=6d96bf0f5b) | Jul 09, 2023 |
| HP            | 620                         | Notebook    | [5f88c564fd](https://linux-hardware.org/?probe=5f88c564fd) | Jul 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| Dell          | Latitude 3380               | Notebook    | [b4403e7b15](https://linux-hardware.org/?probe=b4403e7b15) | Jul 07, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [f32ffc678f](https://linux-hardware.org/?probe=f32ffc678f) | Jul 07, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [3ad05bcf55](https://linux-hardware.org/?probe=3ad05bcf55) | Jul 06, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [84b5d3ce3c](https://linux-hardware.org/?probe=84b5d3ce3c) | Jul 06, 2023 |
| Dell          | Precision 7520              | Notebook    | [1bffd04c84](https://linux-hardware.org/?probe=1bffd04c84) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [5b1b409a2f](https://linux-hardware.org/?probe=5b1b409a2f) | Jul 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [06ac15dcca](https://linux-hardware.org/?probe=06ac15dcca) | Jul 04, 2023 |
| Dell          | Precision 5560              | Notebook    | [5f8f3c917f](https://linux-hardware.org/?probe=5f8f3c917f) | Jul 04, 2023 |
| HP            | 21F5 0A                     | Desktop     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [075cc6eb8a](https://linux-hardware.org/?probe=075cc6eb8a) | Jul 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b4560fc1c1](https://linux-hardware.org/?probe=b4560fc1c1) | Jul 02, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [d04862302e](https://linux-hardware.org/?probe=d04862302e) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [6df0ae15e1](https://linux-hardware.org/?probe=6df0ae15e1) | Jul 01, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d3fb700ff1](https://linux-hardware.org/?probe=d3fb700ff1) | Jul 01, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [d4a008aefb](https://linux-hardware.org/?probe=d4a008aefb) | Jun 30, 2023 |
| Dell          | Latitude 5440               | Notebook    | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| VALE          | Notebook Slim S132          | Notebook    | [3e381e10f7](https://linux-hardware.org/?probe=3e381e10f7) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [39f7adb927](https://linux-hardware.org/?probe=39f7adb927) | Jun 30, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [b8327a4d00](https://linux-hardware.org/?probe=b8327a4d00) | Jun 30, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1f5a11092b](https://linux-hardware.org/?probe=1f5a11092b) | Jun 28, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [b7ac1c1ba6](https://linux-hardware.org/?probe=b7ac1c1ba6) | Jun 24, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [bf6de06fb9](https://linux-hardware.org/?probe=bf6de06fb9) | Jun 23, 2023 |
| Hardkernel    | ODROID-H3                   | Desktop     | [7f87bb5b32](https://linux-hardware.org/?probe=7f87bb5b32) | Jun 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac0a9c170f](https://linux-hardware.org/?probe=ac0a9c170f) | Jun 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [666f5d0ce5](https://linux-hardware.org/?probe=666f5d0ce5) | Jun 22, 2023 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [88cdeeac94](https://linux-hardware.org/?probe=88cdeeac94) | Jun 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [3574f89b15](https://linux-hardware.org/?probe=3574f89b15) | Jun 21, 2023 |
| Acer          | Aspire F5-771G              | Notebook    | [034d235f5c](https://linux-hardware.org/?probe=034d235f5c) | Jun 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [e65deab189](https://linux-hardware.org/?probe=e65deab189) | Jun 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b3e34f06a4](https://linux-hardware.org/?probe=b3e34f06a4) | Jun 19, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [601d7611be](https://linux-hardware.org/?probe=601d7611be) | Jun 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [aafa9250df](https://linux-hardware.org/?probe=aafa9250df) | Jun 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [192105166b](https://linux-hardware.org/?probe=192105166b) | Jun 14, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [e2df546273](https://linux-hardware.org/?probe=e2df546273) | Jun 13, 2023 |
| Medion        | Z370H4-EM                   | Desktop     | [bcfcd0b59d](https://linux-hardware.org/?probe=bcfcd0b59d) | Jun 13, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [50c975ae08](https://linux-hardware.org/?probe=50c975ae08) | Jun 13, 2023 |
| Emdoor        | AG958                       | Notebook    | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [ea61fdd09a](https://linux-hardware.org/?probe=ea61fdd09a) | Jun 11, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [7d5fc6a209](https://linux-hardware.org/?probe=7d5fc6a209) | Jun 11, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [43c70efbe7](https://linux-hardware.org/?probe=43c70efbe7) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [9a66179aaf](https://linux-hardware.org/?probe=9a66179aaf) | Jun 04, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| Dell          | Latitude 5510               | Notebook    | [78bd1ae0e0](https://linux-hardware.org/?probe=78bd1ae0e0) | May 31, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [3718997542](https://linux-hardware.org/?probe=3718997542) | May 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [8ec80f5e43](https://linux-hardware.org/?probe=8ec80f5e43) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [1aa973f6bc](https://linux-hardware.org/?probe=1aa973f6bc) | May 28, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [fd8a08639d](https://linux-hardware.org/?probe=fd8a08639d) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [5a4cf4d2e3](https://linux-hardware.org/?probe=5a4cf4d2e3) | May 23, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [a7794f4f9e](https://linux-hardware.org/?probe=a7794f4f9e) | May 21, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| HP            | Elite x2 1013 G3            | Tablet      | [0da06960ac](https://linux-hardware.org/?probe=0da06960ac) | May 19, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| Valve         | Jupiter                     | Notebook    | [0de060a93f](https://linux-hardware.org/?probe=0de060a93f) | May 18, 2023 |
| HP            | 0A54h                       | Desktop     | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [254f42a469](https://linux-hardware.org/?probe=254f42a469) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [05379205f4](https://linux-hardware.org/?probe=05379205f4) | May 18, 2023 |
| HP            | 620                         | Notebook    | [6b688ce696](https://linux-hardware.org/?probe=6b688ce696) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [874dcebbaa](https://linux-hardware.org/?probe=874dcebbaa) | May 17, 2023 |
| Dell          | 0M3F6C A01                  | Desktop     | [d0fc9b65d0](https://linux-hardware.org/?probe=d0fc9b65d0) | May 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [af16278f1e](https://linux-hardware.org/?probe=af16278f1e) | May 17, 2023 |
| Emdoor        | AG958                       | Notebook    | [7ff5858830](https://linux-hardware.org/?probe=7ff5858830) | May 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f97e4e7fc1](https://linux-hardware.org/?probe=f97e4e7fc1) | May 15, 2023 |
| Medion        | Akoya P6660 MD99790         | Notebook    | [20ecc9b5dc](https://linux-hardware.org/?probe=20ecc9b5dc) | May 15, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [8e0efa6d0a](https://linux-hardware.org/?probe=8e0efa6d0a) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [ced38114fc](https://linux-hardware.org/?probe=ced38114fc) | May 14, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [4bde221d90](https://linux-hardware.org/?probe=4bde221d90) | May 13, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [0a23198016](https://linux-hardware.org/?probe=0a23198016) | May 13, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [c0841ef7e1](https://linux-hardware.org/?probe=c0841ef7e1) | May 12, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [ed18615cb3](https://linux-hardware.org/?probe=ed18615cb3) | May 11, 2023 |
| Medion        | E2292                       | Convertible | [116727a473](https://linux-hardware.org/?probe=116727a473) | May 11, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [5384ed47e6](https://linux-hardware.org/?probe=5384ed47e6) | May 10, 2023 |
| FriendlyEl... | NanoPi NEO3                 | Soc         | [c182a0679c](https://linux-hardware.org/?probe=c182a0679c) | May 10, 2023 |
| ASUSTek       | UX410UAK                    | Notebook    | [d68a2bc7c0](https://linux-hardware.org/?probe=d68a2bc7c0) | May 10, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9ce4debe84](https://linux-hardware.org/?probe=9ce4debe84) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [434f1425a4](https://linux-hardware.org/?probe=434f1425a4) | May 09, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [9a4e4763d4](https://linux-hardware.org/?probe=9a4e4763d4) | May 09, 2023 |
| MSI           | Katana 17 B12UCXK           | Notebook    | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [e7ffe2585f](https://linux-hardware.org/?probe=e7ffe2585f) | May 09, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [29d129229b](https://linux-hardware.org/?probe=29d129229b) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Dell          | Latitude 7390               | Notebook    | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [f41852fa6e](https://linux-hardware.org/?probe=f41852fa6e) | May 07, 2023 |
| MSI           | CR61 3M                     | Notebook    | [7b5d49d859](https://linux-hardware.org/?probe=7b5d49d859) | May 07, 2023 |
| MSI           | GS70 2PC Stealth            | Notebook    | [370f9304b6](https://linux-hardware.org/?probe=370f9304b6) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [9d5ca00c7c](https://linux-hardware.org/?probe=9d5ca00c7c) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [6bea90b569](https://linux-hardware.org/?probe=6bea90b569) | May 07, 2023 |
| Intel         | DP43TF AAE34878-403         | Desktop     | [6353d110f5](https://linux-hardware.org/?probe=6353d110f5) | May 07, 2023 |
| Intel         | DP43TF AAE34878-404         | Desktop     | [db0ab14831](https://linux-hardware.org/?probe=db0ab14831) | May 07, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [1eddb3203a](https://linux-hardware.org/?probe=1eddb3203a) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [2e02937097](https://linux-hardware.org/?probe=2e02937097) | May 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [051da44921](https://linux-hardware.org/?probe=051da44921) | May 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6a54ace5f8](https://linux-hardware.org/?probe=6a54ace5f8) | May 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [68c7b6891b](https://linux-hardware.org/?probe=68c7b6891b) | May 06, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [c490e68d59](https://linux-hardware.org/?probe=c490e68d59) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [29636a9923](https://linux-hardware.org/?probe=29636a9923) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [7bb2ae638b](https://linux-hardware.org/?probe=7bb2ae638b) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [bd0458e8a9](https://linux-hardware.org/?probe=bd0458e8a9) | May 01, 2023 |
| Medion        | P6630                       | Notebook    | [93abad41dd](https://linux-hardware.org/?probe=93abad41dd) | Apr 30, 2023 |
| Dell          | Latitude 5521               | Notebook    | [1629b4efc4](https://linux-hardware.org/?probe=1629b4efc4) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [fa805f77f7](https://linux-hardware.org/?probe=fa805f77f7) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S56G00    | Notebook    | [8da21e9a17](https://linux-hardware.org/?probe=8da21e9a17) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f8aee85cd4](https://linux-hardware.org/?probe=f8aee85cd4) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d138bfdf52](https://linux-hardware.org/?probe=d138bfdf52) | Apr 28, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [f4d7a6ed92](https://linux-hardware.org/?probe=f4d7a6ed92) | Apr 28, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [15b900cf50](https://linux-hardware.org/?probe=15b900cf50) | Apr 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [d5b1ec921a](https://linux-hardware.org/?probe=d5b1ec921a) | Apr 27, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [de581801e8](https://linux-hardware.org/?probe=de581801e8) | Apr 27, 2023 |
| Dell          | Latitude E6440              | Notebook    | [d55c77598b](https://linux-hardware.org/?probe=d55c77598b) | Apr 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [cb64c7f963](https://linux-hardware.org/?probe=cb64c7f963) | Apr 25, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [9ca5902786](https://linux-hardware.org/?probe=9ca5902786) | Apr 25, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | Notebook    | [2e542c241d](https://linux-hardware.org/?probe=2e542c241d) | Apr 25, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [d7e9027e6a](https://linux-hardware.org/?probe=d7e9027e6a) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| Dell          | Latitude E6330              | Notebook    | [b532a9756c](https://linux-hardware.org/?probe=b532a9756c) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d342e4d24c](https://linux-hardware.org/?probe=d342e4d24c) | Apr 22, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| Toshiba       | Satellite Pro NB10-A-125    | Notebook    | [3a77f344af](https://linux-hardware.org/?probe=3a77f344af) | Apr 20, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [841c2f241b](https://linux-hardware.org/?probe=841c2f241b) | Apr 19, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [e3ebb38e6b](https://linux-hardware.org/?probe=e3ebb38e6b) | Apr 19, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [5b77cc21f4](https://linux-hardware.org/?probe=5b77cc21f4) | Apr 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [efdcb6b99e](https://linux-hardware.org/?probe=efdcb6b99e) | Apr 18, 2023 |
| Dell          | 0J4NFV A01                  | Desktop     | [a6b3ac3ff2](https://linux-hardware.org/?probe=a6b3ac3ff2) | Apr 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [38aeb226af](https://linux-hardware.org/?probe=38aeb226af) | Apr 17, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [1a55ffc593](https://linux-hardware.org/?probe=1a55ffc593) | Apr 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f3345aced](https://linux-hardware.org/?probe=4f3345aced) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [7230f64c9b](https://linux-hardware.org/?probe=7230f64c9b) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [a7f312ea0a](https://linux-hardware.org/?probe=a7f312ea0a) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [f1afe43806](https://linux-hardware.org/?probe=f1afe43806) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6ac02f43f2](https://linux-hardware.org/?probe=6ac02f43f2) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| HP            | 0A5Ch                       | Desktop     | [636d94a346](https://linux-hardware.org/?probe=636d94a346) | Apr 15, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [b87471108a](https://linux-hardware.org/?probe=b87471108a) | Apr 14, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [43d0d0a55e](https://linux-hardware.org/?probe=43d0d0a55e) | Apr 14, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS29J05    | Notebook    | [60c50f0a10](https://linux-hardware.org/?probe=60c50f0a10) | Apr 13, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [f44505b54b](https://linux-hardware.org/?probe=f44505b54b) | Apr 12, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| Sony          | SVE1713A1EW                 | Notebook    | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| MSI           | B150M BAZOOKA               | Desktop     | [ce60e4a299](https://linux-hardware.org/?probe=ce60e4a299) | Apr 08, 2023 |
| Gigabyte      | B660 DS3H DDR4              | Desktop     | [269e742eb7](https://linux-hardware.org/?probe=269e742eb7) | Apr 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b220308aa1](https://linux-hardware.org/?probe=b220308aa1) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [00fef3bb7b](https://linux-hardware.org/?probe=00fef3bb7b) | Apr 06, 2023 |
| HP            | 620                         | Notebook    | [ad46cdbb0d](https://linux-hardware.org/?probe=ad46cdbb0d) | Apr 06, 2023 |
| Lenovo        | ThinkPad Edge E135 33596... | Notebook    | [d9d2e73619](https://linux-hardware.org/?probe=d9d2e73619) | Apr 05, 2023 |
| Medion        | BTDD-EAIO                   | All in one  | [2bbf3378ef](https://linux-hardware.org/?probe=2bbf3378ef) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [8eb8bb5119](https://linux-hardware.org/?probe=8eb8bb5119) | Apr 03, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [95a98c59b1](https://linux-hardware.org/?probe=95a98c59b1) | Apr 03, 2023 |
| Clevo         | P170HMx                     | Notebook    | [c963b350fc](https://linux-hardware.org/?probe=c963b350fc) | Apr 03, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [0aefaba90e](https://linux-hardware.org/?probe=0aefaba90e) | Apr 03, 2023 |
| HP            | 8430 1000                   | All in one  | [380754e2f6](https://linux-hardware.org/?probe=380754e2f6) | Apr 02, 2023 |
| HP            | 3397                        | Desktop     | [04943f0d5f](https://linux-hardware.org/?probe=04943f0d5f) | Apr 02, 2023 |
| AZW           | Speed S                     | Notebook    | [52292a4968](https://linux-hardware.org/?probe=52292a4968) | Apr 02, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [12319c9ee3](https://linux-hardware.org/?probe=12319c9ee3) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [98cd4ea3a6](https://linux-hardware.org/?probe=98cd4ea3a6) | Apr 01, 2023 |
| HP            | Pavilion g7                 | Notebook    | [7820d2ca67](https://linux-hardware.org/?probe=7820d2ca67) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | Notebook    | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [0ff3ab318e](https://linux-hardware.org/?probe=0ff3ab318e) | Mar 31, 2023 |
| HP            | Compaq 6730b (GB987ET#UU... | Notebook    | [6c6ceb9bc3](https://linux-hardware.org/?probe=6c6ceb9bc3) | Mar 31, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [01492665ee](https://linux-hardware.org/?probe=01492665ee) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0b4fae8189](https://linux-hardware.org/?probe=0b4fae8189) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [13acfd725a](https://linux-hardware.org/?probe=13acfd725a) | Mar 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [cf66e81623](https://linux-hardware.org/?probe=cf66e81623) | Mar 31, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c73c5374a4](https://linux-hardware.org/?probe=c73c5374a4) | Mar 30, 2023 |
| Medion        | P8614                       | Notebook    | [a66fe7042e](https://linux-hardware.org/?probe=a66fe7042e) | Mar 29, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7e04c0e7cd](https://linux-hardware.org/?probe=7e04c0e7cd) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [0ab4054ab9](https://linux-hardware.org/?probe=0ab4054ab9) | Mar 26, 2023 |
| MSI           | GT70                        | Notebook    | [8b00b28b12](https://linux-hardware.org/?probe=8b00b28b12) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [fe5c568f41](https://linux-hardware.org/?probe=fe5c568f41) | Mar 26, 2023 |
| Medion        | P7624                       | Notebook    | [778f5948f1](https://linux-hardware.org/?probe=778f5948f1) | Mar 26, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eeeac5db0f](https://linux-hardware.org/?probe=eeeac5db0f) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [311e49c553](https://linux-hardware.org/?probe=311e49c553) | Mar 23, 2023 |
| Alienware     | m17 R3                      | Notebook    | [6c62c223ed](https://linux-hardware.org/?probe=6c62c223ed) | Mar 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [7622701d31](https://linux-hardware.org/?probe=7622701d31) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [846f31de3e](https://linux-hardware.org/?probe=846f31de3e) | Mar 21, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [de9712600d](https://linux-hardware.org/?probe=de9712600d) | Mar 20, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Acer          | Aspire XC-705               | Desktop     | [2ef61db0a6](https://linux-hardware.org/?probe=2ef61db0a6) | Mar 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [837ed83646](https://linux-hardware.org/?probe=837ed83646) | Mar 18, 2023 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5a70cf923e](https://linux-hardware.org/?probe=5a70cf923e) | Mar 18, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [1825764856](https://linux-hardware.org/?probe=1825764856) | Mar 17, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| Intel         | NUC8i7HVB J68196-602        | Mini pc     | [68b65fda4c](https://linux-hardware.org/?probe=68b65fda4c) | Mar 15, 2023 |
| Lenovo        | Yoga 330-11IGM 81A6         | Convertible | [13a4e703dc](https://linux-hardware.org/?probe=13a4e703dc) | Mar 14, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [cde6fff1ad](https://linux-hardware.org/?probe=cde6fff1ad) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Lenovo        | ThinkPad W510 4389AP5       | Notebook    | [2c01c1fd0e](https://linux-hardware.org/?probe=2c01c1fd0e) | Mar 11, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [dfbb481b02](https://linux-hardware.org/?probe=dfbb481b02) | Mar 11, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a63cd6d4aa](https://linux-hardware.org/?probe=a63cd6d4aa) | Mar 09, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [0dc84b30aa](https://linux-hardware.org/?probe=0dc84b30aa) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [72eed5b458](https://linux-hardware.org/?probe=72eed5b458) | Mar 08, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [1563e26ae3](https://linux-hardware.org/?probe=1563e26ae3) | Mar 07, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [44b690055c](https://linux-hardware.org/?probe=44b690055c) | Mar 07, 2023 |
| MSI           | GT60 2OC/2OD                | Notebook    | [d595ae284e](https://linux-hardware.org/?probe=d595ae284e) | Mar 07, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8f08518290](https://linux-hardware.org/?probe=8f08518290) | Mar 06, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [819f8b1cad](https://linux-hardware.org/?probe=819f8b1cad) | Mar 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [e560390e4f](https://linux-hardware.org/?probe=e560390e4f) | Mar 05, 2023 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [c3e39b21f9](https://linux-hardware.org/?probe=c3e39b21f9) | Mar 05, 2023 |
| Acer          | Aspire 6530G                | Notebook    | [a4077c8432](https://linux-hardware.org/?probe=a4077c8432) | Mar 05, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c2f98c3014](https://linux-hardware.org/?probe=c2f98c3014) | Mar 05, 2023 |
| Toshiba       | Satellite C855-112          | Notebook    | [8635f2eecd](https://linux-hardware.org/?probe=8635f2eecd) | Mar 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [d850dacb6a](https://linux-hardware.org/?probe=d850dacb6a) | Mar 04, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [ac3640b913](https://linux-hardware.org/?probe=ac3640b913) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| HP            | 620                         | Notebook    | [421e31de43](https://linux-hardware.org/?probe=421e31de43) | Mar 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a877190b1c](https://linux-hardware.org/?probe=a877190b1c) | Mar 02, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [639a660b02](https://linux-hardware.org/?probe=639a660b02) | Mar 02, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f441cc82e4](https://linux-hardware.org/?probe=f441cc82e4) | Mar 01, 2023 |
| ASUSTek       | F70SL                       | Notebook    | [5870cf8326](https://linux-hardware.org/?probe=5870cf8326) | Mar 01, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b1d7964fc7](https://linux-hardware.org/?probe=b1d7964fc7) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [9ba7cfbdeb](https://linux-hardware.org/?probe=9ba7cfbdeb) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [0710c7be6e](https://linux-hardware.org/?probe=0710c7be6e) | Feb 28, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [057c307bf5](https://linux-hardware.org/?probe=057c307bf5) | Feb 28, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [4acd4aa811](https://linux-hardware.org/?probe=4acd4aa811) | Feb 27, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [068ad292bd](https://linux-hardware.org/?probe=068ad292bd) | Feb 27, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [41330b2783](https://linux-hardware.org/?probe=41330b2783) | Feb 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [de7aec7f12](https://linux-hardware.org/?probe=de7aec7f12) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [e257e205bf](https://linux-hardware.org/?probe=e257e205bf) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [950130a7b4](https://linux-hardware.org/?probe=950130a7b4) | Feb 23, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [c2117fed20](https://linux-hardware.org/?probe=c2117fed20) | Feb 22, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [abfe4c823a](https://linux-hardware.org/?probe=abfe4c823a) | Feb 21, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [30f09c71a1](https://linux-hardware.org/?probe=30f09c71a1) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | Notebook    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7e5789e02b](https://linux-hardware.org/?probe=7e5789e02b) | Feb 21, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJA0... | Convertible | [aba497a637](https://linux-hardware.org/?probe=aba497a637) | Feb 21, 2023 |
| HP            | 1850                        | Desktop     | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [da5050e2f8](https://linux-hardware.org/?probe=da5050e2f8) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | Notebook    | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [9eca2efc88](https://linux-hardware.org/?probe=9eca2efc88) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | Notebook    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [831d4806fb](https://linux-hardware.org/?probe=831d4806fb) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Notebook    | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [caeb6bc93f](https://linux-hardware.org/?probe=caeb6bc93f) | Feb 17, 2023 |
| MSI           | Z170A TOMAHAWK              | Desktop     | [4a92de7e43](https://linux-hardware.org/?probe=4a92de7e43) | Feb 17, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [2b25f214e9](https://linux-hardware.org/?probe=2b25f214e9) | Feb 15, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [5bf8aa635c](https://linux-hardware.org/?probe=5bf8aa635c) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [e718a6af67](https://linux-hardware.org/?probe=e718a6af67) | Feb 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [01319ac289](https://linux-hardware.org/?probe=01319ac289) | Feb 13, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [2a14385869](https://linux-hardware.org/?probe=2a14385869) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [c0d18ab501](https://linux-hardware.org/?probe=c0d18ab501) | Feb 12, 2023 |
| Packard Be... | DOT S                       | Notebook    | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [9c458e5a66](https://linux-hardware.org/?probe=9c458e5a66) | Feb 11, 2023 |
| Acer          | Aspire V5-122               | Notebook    | [99fd12250b](https://linux-hardware.org/?probe=99fd12250b) | Feb 10, 2023 |
| Teclast       | F15S                        | Notebook    | [951ded8432](https://linux-hardware.org/?probe=951ded8432) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [26fb33ec6c](https://linux-hardware.org/?probe=26fb33ec6c) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [997020aeb0](https://linux-hardware.org/?probe=997020aeb0) | Feb 08, 2023 |
| Medion        | Cattle24 1M                 | Desktop     | [c90f2404df](https://linux-hardware.org/?probe=c90f2404df) | Feb 08, 2023 |
| Dell          | 06JWJY A01                  | Desktop     | [ee53c6f627](https://linux-hardware.org/?probe=ee53c6f627) | Feb 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [870ba1caa7](https://linux-hardware.org/?probe=870ba1caa7) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Medion        | P6624                       | Notebook    | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | GL703VD                     | Notebook    | [62e1e79469](https://linux-hardware.org/?probe=62e1e79469) | Feb 03, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [a630801a13](https://linux-hardware.org/?probe=a630801a13) | Feb 03, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [72bdb7165c](https://linux-hardware.org/?probe=72bdb7165c) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2261a77abb](https://linux-hardware.org/?probe=2261a77abb) | Feb 01, 2023 |
| Google        | Pantheon                    | Notebook    | [12e0b96dd1](https://linux-hardware.org/?probe=12e0b96dd1) | Feb 01, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [8641149603](https://linux-hardware.org/?probe=8641149603) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f6be582448](https://linux-hardware.org/?probe=f6be582448) | Jan 30, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [358b908129](https://linux-hardware.org/?probe=358b908129) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [f5311b2134](https://linux-hardware.org/?probe=f5311b2134) | Jan 28, 2023 |
| HP            | 89E9 0100                   | All in one  | [4afdd5b9fc](https://linux-hardware.org/?probe=4afdd5b9fc) | Jan 28, 2023 |
| Acer          | Peppy                       | Notebook    | [9a16262be8](https://linux-hardware.org/?probe=9a16262be8) | Jan 27, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [77a6b88d58](https://linux-hardware.org/?probe=77a6b88d58) | Jan 27, 2023 |
| Intel         | DG965SS AAD41678-306        | Desktop     | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| MSI           | Z270 GAMING M5              | Desktop     | [218f278cab](https://linux-hardware.org/?probe=218f278cab) | Jan 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [85ad9c7e62](https://linux-hardware.org/?probe=85ad9c7e62) | Jan 25, 2023 |
| Dell          | Latitude E6410              | Notebook    | [03463d0a58](https://linux-hardware.org/?probe=03463d0a58) | Jan 25, 2023 |
| HP            | 304Ah                       | Desktop     | [a41a25807f](https://linux-hardware.org/?probe=a41a25807f) | Jan 25, 2023 |
| ASUSTek       | P8H61-I R2.0                | Desktop     | [37c4aa5f03](https://linux-hardware.org/?probe=37c4aa5f03) | Jan 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [19bb445ee4](https://linux-hardware.org/?probe=19bb445ee4) | Jan 22, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [6228476153](https://linux-hardware.org/?probe=6228476153) | Jan 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [c228c064b7](https://linux-hardware.org/?probe=c228c064b7) | Jan 20, 2023 |
| Medion        | P6624                       | Notebook    | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| HP            | 843B                        | Desktop     | [2af17234ba](https://linux-hardware.org/?probe=2af17234ba) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [9476823c0b](https://linux-hardware.org/?probe=9476823c0b) | Jan 19, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| MSI           | Katana GF76 11UC            | Notebook    | [8c0b32cf24](https://linux-hardware.org/?probe=8c0b32cf24) | Jan 18, 2023 |
| Acer          | Swift SF314-54G             | Notebook    | [c666c8f973](https://linux-hardware.org/?probe=c666c8f973) | Jan 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f3b27e21a7](https://linux-hardware.org/?probe=f3b27e21a7) | Jan 16, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [c06c7eedaf](https://linux-hardware.org/?probe=c06c7eedaf) | Jan 16, 2023 |
| Medion        | MS-7501                     | Desktop     | [abd269d539](https://linux-hardware.org/?probe=abd269d539) | Jan 15, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9fe6c51640](https://linux-hardware.org/?probe=9fe6c51640) | Jan 15, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [e3b9b73877](https://linux-hardware.org/?probe=e3b9b73877) | Jan 14, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [406649acdf](https://linux-hardware.org/?probe=406649acdf) | Jan 14, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [5047da7461](https://linux-hardware.org/?probe=5047da7461) | Jan 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f59adc6dcd](https://linux-hardware.org/?probe=f59adc6dcd) | Jan 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [bbecf2579c](https://linux-hardware.org/?probe=bbecf2579c) | Jan 13, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| HP            | 3397                        | Desktop     | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [10c4bcf564](https://linux-hardware.org/?probe=10c4bcf564) | Jan 12, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60c16871ac](https://linux-hardware.org/?probe=60c16871ac) | Jan 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8193577e0b](https://linux-hardware.org/?probe=8193577e0b) | Jan 11, 2023 |
| HP            | Pavilion dv6000 (RY604EA... | Notebook    | [a8ec5eb86a](https://linux-hardware.org/?probe=a8ec5eb86a) | Jan 11, 2023 |
| Acer          | Aspire 7560                 | Notebook    | [58cd9d7ad2](https://linux-hardware.org/?probe=58cd9d7ad2) | Jan 09, 2023 |
| Dell          | XPS L521X                   | Notebook    | [2930493243](https://linux-hardware.org/?probe=2930493243) | Jan 09, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [e6cb9446f5](https://linux-hardware.org/?probe=e6cb9446f5) | Jan 09, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [8ec4c19bf3](https://linux-hardware.org/?probe=8ec4c19bf3) | Jan 09, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [0f1543c21d](https://linux-hardware.org/?probe=0f1543c21d) | Jan 09, 2023 |
| Notebook      | P7xxDM3(-G)                 | Notebook    | [7cafa98138](https://linux-hardware.org/?probe=7cafa98138) | Jan 08, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d1eaa576e7](https://linux-hardware.org/?probe=d1eaa576e7) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [4673ec60ea](https://linux-hardware.org/?probe=4673ec60ea) | Jan 07, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [cbd020e86f](https://linux-hardware.org/?probe=cbd020e86f) | Jan 07, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [bb893b2d93](https://linux-hardware.org/?probe=bb893b2d93) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [89eccb038f](https://linux-hardware.org/?probe=89eccb038f) | Jan 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0232b39536](https://linux-hardware.org/?probe=0232b39536) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [458cb8c4de](https://linux-hardware.org/?probe=458cb8c4de) | Jan 06, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a84d0d7b42](https://linux-hardware.org/?probe=a84d0d7b42) | Jan 06, 2023 |
| Medion        | S4214                       | Notebook    | [58131e715e](https://linux-hardware.org/?probe=58131e715e) | Jan 06, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9f029a8cdb](https://linux-hardware.org/?probe=9f029a8cdb) | Jan 06, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [b1911d1ae5](https://linux-hardware.org/?probe=b1911d1ae5) | Jan 01, 2023 |
| Dell          | System XPS L702X            | Notebook    | [7030c340cc](https://linux-hardware.org/?probe=7030c340cc) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L6S29E0A    | Notebook    | [82168627b7](https://linux-hardware.org/?probe=82168627b7) | Dec 31, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b0f7933824](https://linux-hardware.org/?probe=b0f7933824) | Dec 29, 2022 |
| HP            | Notebook                    | Notebook    | [91bc85bf6e](https://linux-hardware.org/?probe=91bc85bf6e) | Dec 29, 2022 |
| Acer          | Aspire M3920                | Desktop     | [49cb4f51a8](https://linux-hardware.org/?probe=49cb4f51a8) | Dec 28, 2022 |
| Dell          | Latitude 5580               | Notebook    | [7c006e8c6d](https://linux-hardware.org/?probe=7c006e8c6d) | Dec 28, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [bf50da5153](https://linux-hardware.org/?probe=bf50da5153) | Dec 28, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| Notebook      | N7x0WU                      | Notebook    | [9eee40dd50](https://linux-hardware.org/?probe=9eee40dd50) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [34532e7f7d](https://linux-hardware.org/?probe=34532e7f7d) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| HP            | 0AACh                       | Desktop     | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | Stream x360 Convertible ... | Convertible | [e01713ca07](https://linux-hardware.org/?probe=e01713ca07) | Dec 24, 2022 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [355d32cbac](https://linux-hardware.org/?probe=355d32cbac) | Dec 24, 2022 |
| HP            | 0AACh                       | Desktop     | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | Notebook    | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d407c538c4](https://linux-hardware.org/?probe=d407c538c4) | Dec 24, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [5105f25e5e](https://linux-hardware.org/?probe=5105f25e5e) | Dec 23, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [59d46f37db](https://linux-hardware.org/?probe=59d46f37db) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a2d763d722](https://linux-hardware.org/?probe=a2d763d722) | Dec 21, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [60683b36c2](https://linux-hardware.org/?probe=60683b36c2) | Dec 20, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [d854f4c5ad](https://linux-hardware.org/?probe=d854f4c5ad) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Dell          | 0D6H9T A03                  | Desktop     | [835cdeea5e](https://linux-hardware.org/?probe=835cdeea5e) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [6c56016ed0](https://linux-hardware.org/?probe=6c56016ed0) | Dec 19, 2022 |
| Packard Be... | EasyNote TR85               | Notebook    | [abd93a5cca](https://linux-hardware.org/?probe=abd93a5cca) | Dec 19, 2022 |
| HP            | ProBook 6570b               | Notebook    | [4deb8fc518](https://linux-hardware.org/?probe=4deb8fc518) | Dec 19, 2022 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [3684f593d4](https://linux-hardware.org/?probe=3684f593d4) | Dec 18, 2022 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [15f724ada5](https://linux-hardware.org/?probe=15f724ada5) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Medion        | WIM2210                     | Notebook    | [d1a64f7b3b](https://linux-hardware.org/?probe=d1a64f7b3b) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3db1266e41](https://linux-hardware.org/?probe=3db1266e41) | Dec 17, 2022 |
| Lenovo        | B70-80 80MR                 | Notebook    | [c17bee3b4a](https://linux-hardware.org/?probe=c17bee3b4a) | Dec 17, 2022 |
| Lenovo        | ThinkPad T570 20H9S04C00    | Notebook    | [f3093ba13c](https://linux-hardware.org/?probe=f3093ba13c) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [4e9bbbaa1f](https://linux-hardware.org/?probe=4e9bbbaa1f) | Dec 16, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1398958777](https://linux-hardware.org/?probe=1398958777) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e008a86cd5](https://linux-hardware.org/?probe=e008a86cd5) | Dec 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [45efd7615d](https://linux-hardware.org/?probe=45efd7615d) | Dec 12, 2022 |
| Lenovo        | ThinkPad T430 2349L26       | Notebook    | [9d0bcbdc75](https://linux-hardware.org/?probe=9d0bcbdc75) | Dec 11, 2022 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5749b67534](https://linux-hardware.org/?probe=5749b67534) | Dec 10, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [d1b6c31805](https://linux-hardware.org/?probe=d1b6c31805) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| Lenovo        | ThinkPad T520 4243CJ2       | Notebook    | [93e5e0ca9b](https://linux-hardware.org/?probe=93e5e0ca9b) | Dec 08, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [7ba193202d](https://linux-hardware.org/?probe=7ba193202d) | Dec 08, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [5e5a1fd920](https://linux-hardware.org/?probe=5e5a1fd920) | Dec 07, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e2e47d2d43](https://linux-hardware.org/?probe=e2e47d2d43) | Dec 06, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [185bfcb7fa](https://linux-hardware.org/?probe=185bfcb7fa) | Dec 04, 2022 |
| HP            | Pavilion Laptop             | Notebook    | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | Notebook    | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HP            | ProBook 6550b               | Notebook    | [564bf050f2](https://linux-hardware.org/?probe=564bf050f2) | Dec 02, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [cccf492c06](https://linux-hardware.org/?probe=cccf492c06) | Dec 01, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4c7e1d5bc4](https://linux-hardware.org/?probe=4c7e1d5bc4) | Dec 01, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [bb49870780](https://linux-hardware.org/?probe=bb49870780) | Nov 28, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| Dell          | G3 3779                     | Notebook    | [1cf1d8aa20](https://linux-hardware.org/?probe=1cf1d8aa20) | Nov 26, 2022 |
| Dell          | G3 3779                     | Notebook    | [4bc02c1721](https://linux-hardware.org/?probe=4bc02c1721) | Nov 26, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| Acer          | NC-ES1-512-C3AH             | Notebook    | [0670f9ed15](https://linux-hardware.org/?probe=0670f9ed15) | Nov 25, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [62e12083b5](https://linux-hardware.org/?probe=62e12083b5) | Nov 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [495d972ae3](https://linux-hardware.org/?probe=495d972ae3) | Nov 23, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [66383ce902](https://linux-hardware.org/?probe=66383ce902) | Nov 22, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [0354f9cb0e](https://linux-hardware.org/?probe=0354f9cb0e) | Nov 21, 2022 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [c6b206401a](https://linux-hardware.org/?probe=c6b206401a) | Nov 21, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [d7ee80553a](https://linux-hardware.org/?probe=d7ee80553a) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [f55a45b87f](https://linux-hardware.org/?probe=f55a45b87f) | Nov 20, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [e3d6c78ed4](https://linux-hardware.org/?probe=e3d6c78ed4) | Nov 20, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [dfd1c98a18](https://linux-hardware.org/?probe=dfd1c98a18) | Nov 20, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [a7ca712256](https://linux-hardware.org/?probe=a7ca712256) | Nov 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [571dc553f9](https://linux-hardware.org/?probe=571dc553f9) | Nov 19, 2022 |
| Intel         | NUC11DBBi7 M17027-403       | Mini pc     | [d0d37dd251](https://linux-hardware.org/?probe=d0d37dd251) | Nov 17, 2022 |
| Dell          | Latitude 5530               | Notebook    | [35a6ba0a9f](https://linux-hardware.org/?probe=35a6ba0a9f) | Nov 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [7c8d905b3d](https://linux-hardware.org/?probe=7c8d905b3d) | Nov 17, 2022 |
| Dell          | Precision 7560              | Notebook    | [0ee8814502](https://linux-hardware.org/?probe=0ee8814502) | Nov 16, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [5d11a28230](https://linux-hardware.org/?probe=5d11a28230) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9876aa0fd](https://linux-hardware.org/?probe=c9876aa0fd) | Nov 16, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [f56f2c6a53](https://linux-hardware.org/?probe=f56f2c6a53) | Nov 14, 2022 |
| ASRock        | B660M-HDV                   | Desktop     | [eeaa5c82ea](https://linux-hardware.org/?probe=eeaa5c82ea) | Nov 13, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ef06fcef1](https://linux-hardware.org/?probe=9ef06fcef1) | Nov 13, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [94e5dec391](https://linux-hardware.org/?probe=94e5dec391) | Nov 12, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [022a97b52e](https://linux-hardware.org/?probe=022a97b52e) | Nov 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [3f11ca7016](https://linux-hardware.org/?probe=3f11ca7016) | Nov 11, 2022 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [929685d936](https://linux-hardware.org/?probe=929685d936) | Nov 11, 2022 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [07bae444fc](https://linux-hardware.org/?probe=07bae444fc) | Nov 11, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [331a1db69d](https://linux-hardware.org/?probe=331a1db69d) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [d703e1c63c](https://linux-hardware.org/?probe=d703e1c63c) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| Acer          | Aspire 1825PTZ              | Notebook    | [c2dc801a81](https://linux-hardware.org/?probe=c2dc801a81) | Nov 09, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a41a51330d](https://linux-hardware.org/?probe=a41a51330d) | Nov 08, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [9fda4c3798](https://linux-hardware.org/?probe=9fda4c3798) | Nov 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e9389bc87e](https://linux-hardware.org/?probe=e9389bc87e) | Nov 08, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [25756ad3c1](https://linux-hardware.org/?probe=25756ad3c1) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [5505ec9b09](https://linux-hardware.org/?probe=5505ec9b09) | Nov 06, 2022 |
| HP            | Pavilion 17                 | Notebook    | [958de69d5b](https://linux-hardware.org/?probe=958de69d5b) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [4e35f6b15e](https://linux-hardware.org/?probe=4e35f6b15e) | Nov 05, 2022 |
| ASUSTek       | K56CM                       | Notebook    | [c93289dc28](https://linux-hardware.org/?probe=c93289dc28) | Nov 05, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [681d0b959b](https://linux-hardware.org/?probe=681d0b959b) | Nov 05, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [3e390c5fb3](https://linux-hardware.org/?probe=3e390c5fb3) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [0f4bdc1677](https://linux-hardware.org/?probe=0f4bdc1677) | Nov 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [3e8fbc43d7](https://linux-hardware.org/?probe=3e8fbc43d7) | Nov 04, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [ff19454b61](https://linux-hardware.org/?probe=ff19454b61) | Nov 04, 2022 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [e7254fb467](https://linux-hardware.org/?probe=e7254fb467) | Nov 04, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [2069a0e7fc](https://linux-hardware.org/?probe=2069a0e7fc) | Nov 02, 2022 |
| Dell          | Latitude 5580               | Notebook    | [92545fb976](https://linux-hardware.org/?probe=92545fb976) | Nov 02, 2022 |
| Dell          | Precision 7550              | Notebook    | [2065f4ab5f](https://linux-hardware.org/?probe=2065f4ab5f) | Nov 02, 2022 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [95e2a1e7d9](https://linux-hardware.org/?probe=95e2a1e7d9) | Nov 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [63bf11c696](https://linux-hardware.org/?probe=63bf11c696) | Nov 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [034414a73e](https://linux-hardware.org/?probe=034414a73e) | Nov 01, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6f635f46c6](https://linux-hardware.org/?probe=6f635f46c6) | Nov 01, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [0424e08b3d](https://linux-hardware.org/?probe=0424e08b3d) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f497e98b58](https://linux-hardware.org/?probe=f497e98b58) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [cfe35367bf](https://linux-hardware.org/?probe=cfe35367bf) | Oct 30, 2022 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [81ccab7297](https://linux-hardware.org/?probe=81ccab7297) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [4eff9900f2](https://linux-hardware.org/?probe=4eff9900f2) | Oct 28, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [6cfd4bdb14](https://linux-hardware.org/?probe=6cfd4bdb14) | Oct 28, 2022 |
| PC Special... | Recoil II                   | Notebook    | [9ec5a6ef20](https://linux-hardware.org/?probe=9ec5a6ef20) | Oct 27, 2022 |
| PC Special... | Recoil II                   | Notebook    | [38ec5a7708](https://linux-hardware.org/?probe=38ec5a7708) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [18dad8d151](https://linux-hardware.org/?probe=18dad8d151) | Oct 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [76fa0d836f](https://linux-hardware.org/?probe=76fa0d836f) | Oct 25, 2022 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | Desktop     | [0d21d658ee](https://linux-hardware.org/?probe=0d21d658ee) | Oct 24, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [0e12d15b78](https://linux-hardware.org/?probe=0e12d15b78) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8b0377a420](https://linux-hardware.org/?probe=8b0377a420) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [f82a2d8d8e](https://linux-hardware.org/?probe=f82a2d8d8e) | Oct 23, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [25295c680c](https://linux-hardware.org/?probe=25295c680c) | Oct 23, 2022 |
| ASUSTek       | P9X79 WS                    | Desktop     | [86f91e4898](https://linux-hardware.org/?probe=86f91e4898) | Oct 23, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a7bffc7d13](https://linux-hardware.org/?probe=a7bffc7d13) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [e34cb7ea31](https://linux-hardware.org/?probe=e34cb7ea31) | Oct 20, 2022 |
| Lenovo        | ThinkPad E590 20NB002BMB    | Notebook    | [4b272ef951](https://linux-hardware.org/?probe=4b272ef951) | Oct 20, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [f5d5e3fb86](https://linux-hardware.org/?probe=f5d5e3fb86) | Oct 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [aa8a459961](https://linux-hardware.org/?probe=aa8a459961) | Oct 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [d51ba4a008](https://linux-hardware.org/?probe=d51ba4a008) | Oct 18, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [70d12e710f](https://linux-hardware.org/?probe=70d12e710f) | Oct 18, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [9d471dbf37](https://linux-hardware.org/?probe=9d471dbf37) | Oct 18, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [f6c1e8e061](https://linux-hardware.org/?probe=f6c1e8e061) | Oct 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [901d7614e5](https://linux-hardware.org/?probe=901d7614e5) | Oct 17, 2022 |
| Shuttle       | FS81                        | Desktop     | [61c0ca02f3](https://linux-hardware.org/?probe=61c0ca02f3) | Oct 16, 2022 |
| ASUSTek       | GD30CI                      | Desktop     | [e002a9ef5c](https://linux-hardware.org/?probe=e002a9ef5c) | Oct 16, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [fda3302752](https://linux-hardware.org/?probe=fda3302752) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c22c1df016](https://linux-hardware.org/?probe=c22c1df016) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [870d58dd75](https://linux-hardware.org/?probe=870d58dd75) | Oct 15, 2022 |
| Dell          | 0M863N A00                  | Desktop     | [27e1ded122](https://linux-hardware.org/?probe=27e1ded122) | Oct 15, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [73f8df6ec6](https://linux-hardware.org/?probe=73f8df6ec6) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0bc0bf85be](https://linux-hardware.org/?probe=0bc0bf85be) | Oct 14, 2022 |
| Dell          | Latitude E6330              | Notebook    | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Dell          | Precision M3800             | Notebook    | [96ea6a1a31](https://linux-hardware.org/?probe=96ea6a1a31) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| Dell          | Latitude 5530               | Notebook    | [9453558076](https://linux-hardware.org/?probe=9453558076) | Oct 12, 2022 |
| ASUSTek       | X756UVK                     | Notebook    | [8d2e9a5e1e](https://linux-hardware.org/?probe=8d2e9a5e1e) | Oct 12, 2022 |
| HP            | 82A5                        | Mini pc     | [5a8ea35493](https://linux-hardware.org/?probe=5a8ea35493) | Oct 11, 2022 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | Notebook    | [2209173803](https://linux-hardware.org/?probe=2209173803) | Oct 10, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | Notebook    | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b26ceb2206](https://linux-hardware.org/?probe=b26ceb2206) | Oct 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [bc86477fff](https://linux-hardware.org/?probe=bc86477fff) | Oct 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [24d18c0f7f](https://linux-hardware.org/?probe=24d18c0f7f) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1798b09b89](https://linux-hardware.org/?probe=1798b09b89) | Oct 08, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [b1ff49ff0f](https://linux-hardware.org/?probe=b1ff49ff0f) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [8b0ed3f04c](https://linux-hardware.org/?probe=8b0ed3f04c) | Oct 06, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [b419239d57](https://linux-hardware.org/?probe=b419239d57) | Oct 06, 2022 |
| Gigabyte      | Spring Peak                 | Notebook    | [45794008e2](https://linux-hardware.org/?probe=45794008e2) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [03dc83a686](https://linux-hardware.org/?probe=03dc83a686) | Oct 05, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [bce5ab0354](https://linux-hardware.org/?probe=bce5ab0354) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Notebook      | W330SU2                     | Notebook    | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| Dell          | Latitude 5530               | Notebook    | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [02c5cd53e9](https://linux-hardware.org/?probe=02c5cd53e9) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d658b9dcbe](https://linux-hardware.org/?probe=d658b9dcbe) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [56e5d25094](https://linux-hardware.org/?probe=56e5d25094) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| Razer         | Blade                       | Notebook    | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [757d465447](https://linux-hardware.org/?probe=757d465447) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8ee663c695](https://linux-hardware.org/?probe=8ee663c695) | Sep 26, 2022 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [d09f4c4501](https://linux-hardware.org/?probe=d09f4c4501) | Sep 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [36a7fc8903](https://linux-hardware.org/?probe=36a7fc8903) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [3d7933270a](https://linux-hardware.org/?probe=3d7933270a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [1e6b1b068a](https://linux-hardware.org/?probe=1e6b1b068a) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [a978086f1b](https://linux-hardware.org/?probe=a978086f1b) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Lenovo        | B570e 476025G               | Notebook    | [ab67a90ba7](https://linux-hardware.org/?probe=ab67a90ba7) | Sep 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [153aed4d7c](https://linux-hardware.org/?probe=153aed4d7c) | Sep 19, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [e728637650](https://linux-hardware.org/?probe=e728637650) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [de718ac983](https://linux-hardware.org/?probe=de718ac983) | Sep 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [3da12828c0](https://linux-hardware.org/?probe=3da12828c0) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [798bb8eda6](https://linux-hardware.org/?probe=798bb8eda6) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [90871c217b](https://linux-hardware.org/?probe=90871c217b) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| Dell          | Precision 7720              | Notebook    | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [b8e79c9c77](https://linux-hardware.org/?probe=b8e79c9c77) | Sep 16, 2022 |
| Acer          | Aspire XC-705               | Desktop     | [2600793890](https://linux-hardware.org/?probe=2600793890) | Sep 15, 2022 |
| Medion        | MS-7857                     | Desktop     | [98a978898c](https://linux-hardware.org/?probe=98a978898c) | Sep 14, 2022 |
| Medion        | MS-7857                     | Desktop     | [54237e3276](https://linux-hardware.org/?probe=54237e3276) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [916aa5cc5d](https://linux-hardware.org/?probe=916aa5cc5d) | Sep 14, 2022 |
| Acer          | Aspire 7551                 | Notebook    | [3f97043d7a](https://linux-hardware.org/?probe=3f97043d7a) | Sep 14, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [ddac4b0175](https://linux-hardware.org/?probe=ddac4b0175) | Sep 13, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [18400c7a0d](https://linux-hardware.org/?probe=18400c7a0d) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [864a5abac7](https://linux-hardware.org/?probe=864a5abac7) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | Notebook    | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| Sony          | SVE1712L1EW                 | Notebook    | [6a797dc1cf](https://linux-hardware.org/?probe=6a797dc1cf) | Sep 12, 2022 |
| Hampoo        | Cherry Trail CR Hampoo_r... | Notebook    | [8d76919c1a](https://linux-hardware.org/?probe=8d76919c1a) | Sep 11, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c7eb1fd4ca](https://linux-hardware.org/?probe=c7eb1fd4ca) | Sep 11, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Sony          | SVE14A2V1EW                 | Notebook    | [5123cfd3cd](https://linux-hardware.org/?probe=5123cfd3cd) | Sep 09, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [857e841fb7](https://linux-hardware.org/?probe=857e841fb7) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [603514ef84](https://linux-hardware.org/?probe=603514ef84) | Sep 09, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [cf774b3e03](https://linux-hardware.org/?probe=cf774b3e03) | Sep 02, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [32e71c2905](https://linux-hardware.org/?probe=32e71c2905) | Sep 01, 2022 |
| Notebook      | NL40_50CU                   | Notebook    | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1f8274de5a](https://linux-hardware.org/?probe=1f8274de5a) | Aug 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [567bf4b44a](https://linux-hardware.org/?probe=567bf4b44a) | Aug 31, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [14f4c7e248](https://linux-hardware.org/?probe=14f4c7e248) | Aug 29, 2022 |
| Lenovo        | ThinkPad P1 20MDS0FC00      | Notebook    | [dcdde00f17](https://linux-hardware.org/?probe=dcdde00f17) | Aug 29, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | Notebook    | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| Dell          | Latitude 5511               | Notebook    | [22c835a93a](https://linux-hardware.org/?probe=22c835a93a) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [413cc5a3c3](https://linux-hardware.org/?probe=413cc5a3c3) | Aug 24, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fdc1bb0c75](https://linux-hardware.org/?probe=fdc1bb0c75) | Aug 23, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [fca17b512f](https://linux-hardware.org/?probe=fca17b512f) | Aug 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b3fcba32bd](https://linux-hardware.org/?probe=b3fcba32bd) | Aug 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| Dell          | Vostro 3360                 | Notebook    | [0964195fe5](https://linux-hardware.org/?probe=0964195fe5) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [47b1480e61](https://linux-hardware.org/?probe=47b1480e61) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1fb1214f6](https://linux-hardware.org/?probe=d1fb1214f6) | Aug 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fc1a1cd41f](https://linux-hardware.org/?probe=fc1a1cd41f) | Aug 20, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7dbac78a87](https://linux-hardware.org/?probe=7dbac78a87) | Aug 20, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [abbb1d7360](https://linux-hardware.org/?probe=abbb1d7360) | Aug 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c3e335499f](https://linux-hardware.org/?probe=c3e335499f) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| MSI           | MS-AE611 100                | All in one  | [336e0dfd12](https://linux-hardware.org/?probe=336e0dfd12) | Aug 18, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 872B                        | Desktop     | [466f4962fe](https://linux-hardware.org/?probe=466f4962fe) | Aug 17, 2022 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [bd808084a5](https://linux-hardware.org/?probe=bd808084a5) | Aug 16, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [07e825ed5b](https://linux-hardware.org/?probe=07e825ed5b) | Aug 16, 2022 |
| HP            | 2AB6                        | Desktop     | [bf0c915ea8](https://linux-hardware.org/?probe=bf0c915ea8) | Aug 15, 2022 |
| HP            | 2AB6                        | Desktop     | [2fe34984da](https://linux-hardware.org/?probe=2fe34984da) | Aug 15, 2022 |
| HP            | 1825                        | Desktop     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [97f14bc24c](https://linux-hardware.org/?probe=97f14bc24c) | Aug 14, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [d7735b3387](https://linux-hardware.org/?probe=d7735b3387) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ba9961565a](https://linux-hardware.org/?probe=ba9961565a) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [fe91d8cdd3](https://linux-hardware.org/?probe=fe91d8cdd3) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | Notebook    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| MSI           | MS-AE611 100                | All in one  | [94bcb206d3](https://linux-hardware.org/?probe=94bcb206d3) | Aug 10, 2022 |
| Dell          | Latitude D630               | Notebook    | [5f682c6798](https://linux-hardware.org/?probe=5f682c6798) | Aug 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aee6d50427](https://linux-hardware.org/?probe=aee6d50427) | Aug 05, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [882cec3541](https://linux-hardware.org/?probe=882cec3541) | Aug 02, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f6f97a58c4](https://linux-hardware.org/?probe=f6f97a58c4) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Dell          | Latitude 5520               | Notebook    | [0406990128](https://linux-hardware.org/?probe=0406990128) | Aug 01, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b59f87dd02](https://linux-hardware.org/?probe=b59f87dd02) | Aug 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [9e219bd7c2](https://linux-hardware.org/?probe=9e219bd7c2) | Jul 29, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [e6f2cdc55e](https://linux-hardware.org/?probe=e6f2cdc55e) | Jul 29, 2022 |
| Dell          | Latitude 5590               | Notebook    | [ab7d6b9f02](https://linux-hardware.org/?probe=ab7d6b9f02) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [c4a4fed104](https://linux-hardware.org/?probe=c4a4fed104) | Jul 28, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [356556d83a](https://linux-hardware.org/?probe=356556d83a) | Jul 28, 2022 |
| Dell          | Latitude D630               | Notebook    | [a14838d1ef](https://linux-hardware.org/?probe=a14838d1ef) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [bf64b6cf98](https://linux-hardware.org/?probe=bf64b6cf98) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | Desktop     | [d8b47ea062](https://linux-hardware.org/?probe=d8b47ea062) | Jul 27, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c2f56b2458](https://linux-hardware.org/?probe=c2f56b2458) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [910067609e](https://linux-hardware.org/?probe=910067609e) | Jul 27, 2022 |
| Toshiba       | Satellite C870D-116         | Notebook    | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b2e54629e5](https://linux-hardware.org/?probe=b2e54629e5) | Jul 25, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [a190a7d890](https://linux-hardware.org/?probe=a190a7d890) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [7ac84940b8](https://linux-hardware.org/?probe=7ac84940b8) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | Notebook    | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | Desktop     | [d13d96da02](https://linux-hardware.org/?probe=d13d96da02) | Jul 23, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [f8ce34248a](https://linux-hardware.org/?probe=f8ce34248a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E580 20KSS0GK01    | Notebook    | [b2d902cbc6](https://linux-hardware.org/?probe=b2d902cbc6) | Jul 21, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [f7f43ba6ed](https://linux-hardware.org/?probe=f7f43ba6ed) | Jul 18, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [bffac60888](https://linux-hardware.org/?probe=bffac60888) | Jul 16, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [d52eabbac8](https://linux-hardware.org/?probe=d52eabbac8) | Jul 16, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [471b64a407](https://linux-hardware.org/?probe=471b64a407) | Jul 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [5b07f65ff5](https://linux-hardware.org/?probe=5b07f65ff5) | Jul 16, 2022 |
| Sony          | SVE1513H1EW                 | Notebook    | [6e4d66c2ee](https://linux-hardware.org/?probe=6e4d66c2ee) | Jul 15, 2022 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [cb6916e513](https://linux-hardware.org/?probe=cb6916e513) | Jul 15, 2022 |
| Medion        | MS-7797                     | Desktop     | [caf13d5392](https://linux-hardware.org/?probe=caf13d5392) | Jul 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [b85cc7c80c](https://linux-hardware.org/?probe=b85cc7c80c) | Jul 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Acer          | Aspire M3920                | Desktop     | [9b12bf66ac](https://linux-hardware.org/?probe=9b12bf66ac) | Jul 11, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b40a6c6b15](https://linux-hardware.org/?probe=b40a6c6b15) | Jul 09, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| HP            | 2820h                       | Desktop     | [bfc5afa2c8](https://linux-hardware.org/?probe=bfc5afa2c8) | Jul 07, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [b08ab62885](https://linux-hardware.org/?probe=b08ab62885) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e7c2f09e51](https://linux-hardware.org/?probe=e7c2f09e51) | Jul 05, 2022 |
| NEC Comput... | NEC Versa M370              | Notebook    | [d4dbd6878c](https://linux-hardware.org/?probe=d4dbd6878c) | Jul 04, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [238f7bf18c](https://linux-hardware.org/?probe=238f7bf18c) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | Pavilion dm1                | Notebook    | [927f5b38e0](https://linux-hardware.org/?probe=927f5b38e0) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | Notebook    | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [90a56ffa69](https://linux-hardware.org/?probe=90a56ffa69) | Jun 27, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Google        | Bobba360                    | Notebook    | [6fcae5202a](https://linux-hardware.org/?probe=6fcae5202a) | Jun 26, 2022 |
| Dell          | Latitude E6330              | Notebook    | [969981b8cb](https://linux-hardware.org/?probe=969981b8cb) | Jun 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9421b03b9e](https://linux-hardware.org/?probe=9421b03b9e) | Jun 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c2e6e05eea](https://linux-hardware.org/?probe=c2e6e05eea) | Jun 25, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| MSI           | IONA                        | Desktop     | [9f4e8871a7](https://linux-hardware.org/?probe=9f4e8871a7) | Jun 24, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [34e3aad338](https://linux-hardware.org/?probe=34e3aad338) | Jun 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9f67f6836e](https://linux-hardware.org/?probe=9f67f6836e) | Jun 23, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [32a4f6d3e0](https://linux-hardware.org/?probe=32a4f6d3e0) | Jun 23, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [f3ceed4c58](https://linux-hardware.org/?probe=f3ceed4c58) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [17e0b3e4c0](https://linux-hardware.org/?probe=17e0b3e4c0) | Jun 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [6d1dcb879d](https://linux-hardware.org/?probe=6d1dcb879d) | Jun 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [6647ddd346](https://linux-hardware.org/?probe=6647ddd346) | Jun 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [812caba8bf](https://linux-hardware.org/?probe=812caba8bf) | Jun 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c1efcc5411](https://linux-hardware.org/?probe=c1efcc5411) | Jun 16, 2022 |
| Unknown       | MediaTek krane sku176       | Soc         | [c992270582](https://linux-hardware.org/?probe=c992270582) | Jun 15, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [5ef81d4b82](https://linux-hardware.org/?probe=5ef81d4b82) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [4b6c230717](https://linux-hardware.org/?probe=4b6c230717) | Jun 12, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3ddbde438b](https://linux-hardware.org/?probe=3ddbde438b) | Jun 12, 2022 |
| MSI           | H55M-E33                    | Desktop     | [1fa7005827](https://linux-hardware.org/?probe=1fa7005827) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Dell          | 0XCR8D A03                  | Desktop     | [7b5fb1809b](https://linux-hardware.org/?probe=7b5fb1809b) | Jun 09, 2022 |
| HP            | Compaq 8710w                | Notebook    | [666f2ebcf0](https://linux-hardware.org/?probe=666f2ebcf0) | Jun 08, 2022 |
| Dell          | 0HX555                      | Desktop     | [41ae8a1dd5](https://linux-hardware.org/?probe=41ae8a1dd5) | Jun 08, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [bfd4aab236](https://linux-hardware.org/?probe=bfd4aab236) | Jun 04, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [68a1616b4a](https://linux-hardware.org/?probe=68a1616b4a) | Jun 03, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [54fb76191c](https://linux-hardware.org/?probe=54fb76191c) | Jun 03, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [ea56369709](https://linux-hardware.org/?probe=ea56369709) | Jun 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [909d9cb8d5](https://linux-hardware.org/?probe=909d9cb8d5) | Jun 03, 2022 |
| Samsung       | 750XED                      | Notebook    | [1a900ee340](https://linux-hardware.org/?probe=1a900ee340) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | G11CD-K                     | Desktop     | [6550f85808](https://linux-hardware.org/?probe=6550f85808) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [70313d6ed4](https://linux-hardware.org/?probe=70313d6ed4) | May 31, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [820a9fb182](https://linux-hardware.org/?probe=820a9fb182) | May 30, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [475315dc10](https://linux-hardware.org/?probe=475315dc10) | May 28, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6e5dd6f76f](https://linux-hardware.org/?probe=6e5dd6f76f) | May 25, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [6e1f063199](https://linux-hardware.org/?probe=6e1f063199) | May 24, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fdc743e9e1](https://linux-hardware.org/?probe=fdc743e9e1) | May 23, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Medion        | P6624                       | Notebook    | [ed8bd28269](https://linux-hardware.org/?probe=ed8bd28269) | May 21, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1ca28a2fb](https://linux-hardware.org/?probe=d1ca28a2fb) | May 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [a0597ba198](https://linux-hardware.org/?probe=a0597ba198) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9d14cc23ca](https://linux-hardware.org/?probe=9d14cc23ca) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [56d6c8d749](https://linux-hardware.org/?probe=56d6c8d749) | May 19, 2022 |
| HP            | 82A2                        | Desktop     | [6e0efeba1d](https://linux-hardware.org/?probe=6e0efeba1d) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [2886b99972](https://linux-hardware.org/?probe=2886b99972) | May 17, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [74cb2084ef](https://linux-hardware.org/?probe=74cb2084ef) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [0f8829e460](https://linux-hardware.org/?probe=0f8829e460) | May 15, 2022 |
| Lenovo        | ThinkPad T450s 20BWS4X50... | Notebook    | [0fb588c686](https://linux-hardware.org/?probe=0fb588c686) | May 15, 2022 |
| ASUSTek       | Mac-F60DEB81FF30ACF6 Mac... | Notebook    | [83b27998e5](https://linux-hardware.org/?probe=83b27998e5) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [3f84f4220e](https://linux-hardware.org/?probe=3f84f4220e) | May 14, 2022 |
| Sony          | VPCEH1M0E                   | Notebook    | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9722abbde0](https://linux-hardware.org/?probe=9722abbde0) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f20d2bc2b](https://linux-hardware.org/?probe=3f20d2bc2b) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| Acer          | Aspire M3985                | Desktop     | [e650ae1a26](https://linux-hardware.org/?probe=e650ae1a26) | May 11, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [a6f5c6215d](https://linux-hardware.org/?probe=a6f5c6215d) | May 11, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [4f87a5b748](https://linux-hardware.org/?probe=4f87a5b748) | May 10, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [eaa10a050b](https://linux-hardware.org/?probe=eaa10a050b) | May 10, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [0066686d1d](https://linux-hardware.org/?probe=0066686d1d) | May 10, 2022 |
| Dell          | 0KV3RP A00                  | Desktop     | [6ef8c2f171](https://linux-hardware.org/?probe=6ef8c2f171) | May 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Belgium/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 302       | 14.5%   |
| Ubuntu 18.04                 | 141       | 6.77%   |
| Ubuntu 22.04                 | 117       | 5.62%   |
| Debian 11                    | 51        | 2.45%   |
| Zorin 16                     | 48        | 2.3%    |
| ArcoLinux Rolling            | 47        | 2.26%   |
| OpenMandriva 4.2             | 45        | 2.16%   |
| OpenMandriva 4.3             | 39        | 1.87%   |
| Fedora 36                    | 33        | 1.58%   |
| Ubuntu 20.10                 | 31        | 1.49%   |
| Linux Mint 20.3              | 29        | 1.39%   |
| Linux Mint 20.1              | 29        | 1.39%   |
| Ubuntu 19.10                 | 27        | 1.3%    |
| Manjaro                      | 27        | 1.3%    |
| Linux Mint 19.3              | 26        | 1.25%   |
| Fedora 35                    | 26        | 1.25%   |
| Arch                         | 26        | 1.25%   |
| Xubuntu 20.04                | 25        | 1.2%    |
| Arch Rolling                 | 25        | 1.2%    |
| Linux Mint 20.2              | 23        | 1.1%    |
| openSUSE Tumbleweed-XXXXXXXX | 22        | 1.06%   |
| Fedora 38                    | 22        | 1.06%   |
| Pop!_OS 22.04                | 21        | 1.01%   |
| Fedora 34                    | 21        | 1.01%   |
| Ubuntu 19.04                 | 20        | 0.96%   |
| Pop!_OS 20.04                | 20        | 0.96%   |
| Linux Mint 21                | 20        | 0.96%   |
| Linux Mint 20                | 19        | 0.91%   |
| OpenMandriva 23.01           | 18        | 0.86%   |
| Fedora 37                    | 18        | 0.86%   |
| Ubuntu 21.10                 | 17        | 0.82%   |
| Ubuntu 21.04                 | 17        | 0.82%   |
| OpenMandriva 23.03           | 17        | 0.82%   |
| Pop!_OS 21.04                | 16        | 0.77%   |
| KDE neon 20.04               | 16        | 0.77%   |
| Fedora 33                    | 16        | 0.77%   |
| Linux Mint 21.1              | 15        | 0.72%   |
| Fedora 32                    | 15        | 0.72%   |
| Debian 10                    | 15        | 0.72%   |
| EndeavourOS Rolling          | 14        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 684       | 35.51%  |
| Linux Mint    | 179       | 9.29%   |
| OpenMandriva  | 137       | 7.11%   |
| Fedora        | 129       | 6.7%    |
| Debian        | 97        | 5.04%   |
| Pop!_OS       | 66        | 3.43%   |
| Manjaro       | 63        | 3.27%   |
| Zorin         | 60        | 3.12%   |
| Xubuntu       | 53        | 2.75%   |
| Arch          | 49        | 2.54%   |
| ArcoLinux     | 48        | 2.49%   |
| Kubuntu       | 39        | 2.02%   |
| openSUSE      | 32        | 1.66%   |
| ROSA          | 30        | 1.56%   |
| KDE neon      | 25        | 1.3%    |
| Elementary    | 21        | 1.09%   |
| Ubuntu Unity  | 18        | 0.93%   |
| Lubuntu       | 18        | 0.93%   |
| Ubuntu MATE   | 16        | 0.83%   |
| Gentoo        | 16        | 0.83%   |
| EndeavourOS   | 16        | 0.83%   |
| CentOS        | 12        | 0.62%   |
| Kali          | 11        | 0.57%   |
| Endless       | 11        | 0.57%   |
| LMDE          | 8         | 0.42%   |
| BlackPanther  | 8         | 0.42%   |
| SteamOS       | 7         | 0.36%   |
| Garuda Linux  | 7         | 0.36%   |
| Ubuntu Budgie | 6         | 0.31%   |
| MX            | 6         | 0.31%   |
| Clear Linux   | 6         | 0.31%   |
| Ubuntu Studio | 4         | 0.21%   |
| Nobara        | 4         | 0.21%   |
| NixOS         | 3         | 0.16%   |
| LinuxFX       | 3         | 0.16%   |
| Rocky Linux   | 2         | 0.1%    |
| Raspbian      | 2         | 0.1%    |
| Peppermint    | 2         | 0.1%    |
| Parrot        | 2         | 0.1%    |
| Feren OS      | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 44        | 1.84%   |
| 5.16.7-desktop-1omv4003  | 37        | 1.54%   |
| 5.4.0-42-generic         | 29        | 1.21%   |
| 5.15.0-56-generic        | 23        | 0.96%   |
| 5.4.0-58-generic         | 22        | 0.92%   |
| 5.4.0-48-generic         | 21        | 0.88%   |
| 5.3.0-42-generic         | 20        | 0.83%   |
| 5.15.0-46-generic        | 18        | 0.75%   |
| 6.2.6-desktop-1omv2390   | 17        | 0.71%   |
| 5.15.0-58-generic        | 17        | 0.71%   |
| 5.15.0-52-generic        | 17        | 0.71%   |
| 6.1.1-desktop-1omv2290   | 15        | 0.63%   |
| 5.8.0-48-generic         | 15        | 0.63%   |
| 5.8.0-43-generic         | 15        | 0.63%   |
| 5.4.0-65-generic         | 15        | 0.63%   |
| 5.15.0-48-generic        | 15        | 0.63%   |
| 5.4.0-66-generic         | 14        | 0.58%   |
| 5.4.0-29-generic         | 14        | 0.58%   |
| 5.3.0-46-generic         | 14        | 0.58%   |
| 5.11.0-38-generic        | 14        | 0.58%   |
| 5.4.0-74-generic         | 13        | 0.54%   |
| 5.4.0-52-generic         | 13        | 0.54%   |
| 5.4.0-40-generic         | 13        | 0.54%   |
| 5.4.0-37-generic         | 12        | 0.5%    |
| 5.4.0-26-generic         | 12        | 0.5%    |
| 5.19.0-35-generic        | 12        | 0.5%    |
| 5.15.0-53-generic        | 12        | 0.5%    |
| 5.15.0-47-generic        | 12        | 0.5%    |
| 5.15.0-41-generic        | 12        | 0.5%    |
| 5.13.0-28-generic        | 12        | 0.5%    |
| 5.10.0-21-amd64          | 12        | 0.5%    |
| 6.2.0-26-generic         | 11        | 0.46%   |
| 5.4.0-91-generic         | 11        | 0.46%   |
| 5.11.0-43-generic        | 11        | 0.46%   |
| 5.11.0-41-generic        | 11        | 0.46%   |
| 5.8.0-53-generic         | 10        | 0.42%   |
| 5.4.0-54-generic         | 10        | 0.42%   |
| 5.13.0-39-generic        | 10        | 0.42%   |
| 5.4.0-56-generic         | 9         | 0.38%   |
| 5.3.0-40-generic         | 9         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 353       | 15.78%  |
| 5.15.0  | 211       | 9.43%   |
| 5.8.0   | 118       | 5.27%   |
| 5.11.0  | 107       | 4.78%   |
| 4.15.0  | 107       | 4.78%   |
| 5.13.0  | 87        | 3.89%   |
| 5.3.0   | 83        | 3.71%   |
| 5.10.0  | 64        | 2.86%   |
| 5.19.0  | 63        | 2.82%   |
| 5.0.0   | 51        | 2.28%   |
| 5.10.14 | 44        | 1.97%   |
| 5.16.7  | 37        | 1.65%   |
| 4.18.0  | 37        | 1.65%   |
| 6.2.0   | 36        | 1.61%   |
| 6.2.6   | 21        | 0.94%   |
| 6.1.0   | 16        | 0.72%   |
| 4.19.0  | 16        | 0.72%   |
| 6.1.1   | 15        | 0.67%   |
| 6.0.0   | 10        | 0.45%   |
| 4.18.16 | 10        | 0.45%   |
| 6.0.12  | 9         | 0.4%    |
| 5.17.5  | 9         | 0.4%    |
| 4.9.20  | 9         | 0.4%    |
| 6.2.11  | 8         | 0.36%   |
| 5.14.10 | 8         | 0.36%   |
| 6.5.0   | 7         | 0.31%   |
| 6.4.11  | 7         | 0.31%   |
| 6.1.12  | 7         | 0.31%   |
| 5.18.12 | 7         | 0.31%   |
| 5.9.11  | 6         | 0.27%   |
| 5.8.5   | 6         | 0.27%   |
| 5.17.0  | 6         | 0.27%   |
| 5.16.0  | 6         | 0.27%   |
| 5.13.12 | 6         | 0.27%   |
| 4.9.60  | 6         | 0.27%   |
| 4.4.0   | 6         | 0.27%   |
| 3.10.0  | 6         | 0.27%   |
| 6.3.9   | 5         | 0.22%   |
| 6.3.8   | 5         | 0.22%   |
| 6.3.1   | 5         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 382       | 17.52%  |
| 5.15    | 266       | 12.2%   |
| 5.10    | 142       | 6.51%   |
| 5.8     | 140       | 6.42%   |
| 5.11    | 134       | 6.15%   |
| 4.15    | 107       | 4.91%   |
| 5.13    | 106       | 4.86%   |
| 5.3     | 92        | 4.22%   |
| 6.2     | 90        | 4.13%   |
| 5.19    | 87        | 3.99%   |
| 5.16    | 74        | 3.39%   |
| 5.0     | 57        | 2.61%   |
| 6.1     | 52        | 2.39%   |
| 6.0     | 49        | 2.25%   |
| 4.18    | 48        | 2.2%    |
| 5.17    | 39        | 1.79%   |
| 5.18    | 33        | 1.51%   |
| 6.4     | 29        | 1.33%   |
| 5.14    | 28        | 1.28%   |
| 6.3     | 27        | 1.24%   |
| 5.9     | 26        | 1.19%   |
| 4.9     | 26        | 1.19%   |
| 5.12    | 24        | 1.1%    |
| 4.19    | 23        | 1.06%   |
| 5.6     | 22        | 1.01%   |
| 6.5     | 15        | 0.69%   |
| 5.5     | 13        | 0.6%    |
| 5.7     | 12        | 0.55%   |
| 4.4     | 6         | 0.28%   |
| 3.10    | 6         | 0.28%   |
| 4.13    | 5         | 0.23%   |
| 5.2     | 4         | 0.18%   |
| 5.1     | 4         | 0.18%   |
| 4.12    | 3         | 0.14%   |
| 5.15.96 | 2         | 0.09%   |
| 4.17    | 2         | 0.09%   |
| 4.1     | 2         | 0.09%   |
| 4.2     | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 2.6     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1776      | 96.84%  |
| i686    | 41        | 2.24%   |
| aarch64 | 14        | 0.76%   |
| armv7l  | 2         | 0.11%   |
| armv6l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 847       | 42.93%  |
| KDE5             | 306       | 15.51%  |
| Unknown          | 244       | 12.37%  |
| XFCE             | 164       | 8.31%   |
| X-Cinnamon       | 133       | 6.74%   |
| MATE             | 55        | 2.79%   |
| KDE              | 37        | 1.88%   |
| LXQt             | 29        | 1.47%   |
| Cinnamon         | 23        | 1.17%   |
| i3               | 21        | 1.06%   |
| Pantheon         | 20        | 1.01%   |
| Unity            | 18        | 0.91%   |
| KDE4             | 14        | 0.71%   |
| Budgie           | 11        | 0.56%   |
| sway             | 6         | 0.3%    |
| Hyprland         | 6         | 0.3%    |
| LXDE             | 5         | 0.25%   |
| GNOME Flashback  | 5         | 0.25%   |
| LeftWM           | 4         | 0.2%    |
| Deepin           | 4         | 0.2%    |
| lightdm-xsession | 3         | 0.15%   |
| awesome          | 3         | 0.15%   |
| Trinity          | 2         | 0.1%    |
| Openbox          | 2         | 0.1%    |
| ICEWM            | 2         | 0.1%    |
| chadwm           | 2         | 0.1%    |
| bspwm            | 2         | 0.1%    |
| xmonad           | 1         | 0.05%   |
| spectrwm         | 1         | 0.05%   |
| qtile            | 1         | 0.05%   |
| GNOME Classic    | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1430      | 74.91%  |
| Wayland | 312       | 16.34%  |
| Unknown | 137       | 7.18%   |
| Tty     | 30        | 1.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 898       | 46.31%  |
| SDDM    | 306       | 15.78%  |
| GDM     | 248       | 12.79%  |
| GDM3    | 228       | 11.76%  |
| LightDM | 173       | 8.92%   |
| TDM     | 68        | 3.51%   |
| KDM     | 13        | 0.67%   |
| XDM     | 4         | 0.21%   |
| SLiM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 616       | 32.23%  |
| fr_BE      | 349       | 18.26%  |
| nl_BE      | 310       | 16.22%  |
| Unknown    | 225       | 11.77%  |
| fr_FR      | 106       | 5.55%   |
| en_GB      | 95        | 4.97%   |
| nl_NL      | 86        | 4.5%    |
| C          | 32        | 1.67%   |
| de_DE      | 14        | 0.73%   |
| de_BE      | 10        | 0.52%   |
| pl_PL      | 9         | 0.47%   |
| en_IE      | 9         | 0.47%   |
| ru_RU      | 6         | 0.31%   |
| es_ES      | 5         | 0.26%   |
| ro_RO      | 3         | 0.16%   |
| pt_PT      | 3         | 0.16%   |
| POSIX      | 3         | 0.16%   |
| it_IT      | 3         | 0.16%   |
| C.UTF8     | 3         | 0.16%   |
| en_US.UTF8 | 2         | 0.1%    |
| en_CA      | 2         | 0.1%    |
| en_BE      | 2         | 0.1%    |
| tt_RU      | 1         | 0.05%   |
| tr_TR      | 1         | 0.05%   |
| pt_BR      | 1         | 0.05%   |
| nl_BE.UTF8 | 1         | 0.05%   |
| nl_AW      | 1         | 0.05%   |
| li_BE      | 1         | 0.05%   |
| ku_TR      | 1         | 0.05%   |
| it_CH      | 1         | 0.05%   |
| hu_HU      | 1         | 0.05%   |
| fr_LU      | 1         | 0.05%   |
| fr_FR.UTF8 | 1         | 0.05%   |
| fr_CH      | 1         | 0.05%   |
| en_ZA      | 1         | 0.05%   |
| en_NZ      | 1         | 0.05%   |
| en_IN      | 1         | 0.05%   |
| en_DK      | 1         | 0.05%   |
| en_BW      | 1         | 0.05%   |
| bg_BG      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 950       | 50.42%  |
| BIOS | 934       | 49.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1430      | 75.14%  |
| Btrfs    | 183       | 9.62%   |
| Overlay  | 144       | 7.57%   |
| Unknown  | 64        | 3.36%   |
| Tmpfs    | 34        | 1.79%   |
| Xfs      | 27        | 1.42%   |
| Zfs      | 10        | 0.53%   |
| Ext2     | 8         | 0.42%   |
| Reiserfs | 1         | 0.05%   |
| F2fs     | 1         | 0.05%   |
| Ext3     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 945       | 50%     |
| GPT     | 739       | 39.1%   |
| MBR     | 206       | 10.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1540      | 81.87%  |
| Yes       | 341       | 18.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1304      | 69.73%  |
| Yes       | 566       | 30.27%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 291       | 15.88%  |
| Hewlett-Packard         | 283       | 15.45%  |
| Lenovo                  | 242       | 13.21%  |
| Dell                    | 240       | 13.1%   |
| MSI                     | 130       | 7.1%    |
| Acer                    | 106       | 5.79%   |
| Gigabyte Technology     | 98        | 5.35%   |
| Medion                  | 60        | 3.28%   |
| ASRock                  | 48        | 2.62%   |
| Apple                   | 43        | 2.35%   |
| Intel                   | 34        | 1.86%   |
| Toshiba                 | 33        | 1.8%    |
| Sony                    | 26        | 1.42%   |
| Packard Bell            | 24        | 1.31%   |
| Notebook                | 22        | 1.2%    |
| Fujitsu                 | 14        | 0.76%   |
| Unknown                 | 14        | 0.76%   |
| Raspberry Pi Foundation | 12        | 0.66%   |
| TUXEDO                  | 10        | 0.55%   |
| Valve                   | 8         | 0.44%   |
| Samsung Electronics     | 8         | 0.44%   |
| Foxconn                 | 6         | 0.33%   |
| Supermicro              | 5         | 0.27%   |
| Fujitsu Siemens         | 5         | 0.27%   |
| Alienware               | 5         | 0.27%   |
| PC Specialist           | 4         | 0.22%   |
| Pegatron                | 3         | 0.16%   |
| Microsoft               | 3         | 0.16%   |
| HUAWEI                  | 3         | 0.16%   |
| Google                  | 3         | 0.16%   |
| Clevo                   | 3         | 0.16%   |
| BESSTAR Tech            | 3         | 0.16%   |
| AZW                     | 3         | 0.16%   |
| AMI                     | 3         | 0.16%   |
| Teclast                 | 2         | 0.11%   |
| Shuttle                 | 2         | 0.11%   |
| Razer                   | 2         | 0.11%   |
| Panasonic               | 2         | 0.11%   |
| Nvidia                  | 2         | 0.11%   |
| YJKC                    | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 26        | 1.42%   |
| Unknown                          | 18        | 0.98%   |
| Valve Jupiter                    | 8         | 0.44%   |
| HP Pavilion g7                   | 7         | 0.38%   |
| HP Pavilion Notebook             | 6         | 0.33%   |
| ASRock B450M Pro4                | 6         | 0.33%   |
| MSI MS-7C37                      | 5         | 0.27%   |
| MSI MS-7B86                      | 5         | 0.27%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5 | 5         | 0.27%   |
| HP ProBook 6570b                 | 5         | 0.27%   |
| HP ProBook 650 G1                | 5         | 0.27%   |
| HP Pavilion dv7                  | 5         | 0.27%   |
| HP EliteBook 850 G8 Notebook PC  | 5         | 0.27%   |
| Dell XPS 13 7390                 | 5         | 0.27%   |
| Dell OptiPlex 780                | 5         | 0.27%   |
| Dell Latitude 5530               | 5         | 0.27%   |
| Toshiba Satellite C660           | 4         | 0.22%   |
| RPi Raspberry Pi                 | 4         | 0.22%   |
| MSI MS-7C91                      | 4         | 0.22%   |
| MSI MS-7A38                      | 4         | 0.22%   |
| HP Pavilion Laptop 15-eh1xxx     | 4         | 0.22%   |
| HP Pavilion Laptop 15-cw0xxx     | 4         | 0.22%   |
| HP Pavilion dv6                  | 4         | 0.22%   |
| HP Pavilion 17                   | 4         | 0.22%   |
| HP Laptop 15-db0xxx              | 4         | 0.22%   |
| HP Compaq Elite 8300 SFF         | 4         | 0.22%   |
| Gigabyte X570 AORUS MASTER       | 4         | 0.22%   |
| Gigabyte Spring Peak             | 4         | 0.22%   |
| Gigabyte GB-BRR7H-4800           | 4         | 0.22%   |
| Gigabyte B550I AORUS PRO AX      | 4         | 0.22%   |
| Dell XPS 13 9370                 | 4         | 0.22%   |
| Dell OptiPlex 3010               | 4         | 0.22%   |
| Dell Latitude 5520               | 4         | 0.22%   |
| ASUS UNLOCK INSTALL              | 4         | 0.22%   |
| ASUS ROG STRIX X570-E GAMING     | 4         | 0.22%   |
| ASUS PRIME X570-PRO              | 4         | 0.22%   |
| MSI MS-7A34                      | 3         | 0.16%   |
| MSI MS-7850                      | 3         | 0.16%   |
| Medion MS-7728                   | 3         | 0.16%   |
| Lenovo Yoga 530-14IKB 81EK       | 3         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 122       | 6.66%   |
| Dell Latitude         | 88        | 4.8%    |
| Acer Aspire           | 80        | 4.37%   |
| HP Pavilion           | 60        | 3.28%   |
| HP EliteBook          | 59        | 3.22%   |
| HP ProBook            | 41        | 2.24%   |
| Lenovo IdeaPad        | 38        | 2.07%   |
| Dell XPS              | 38        | 2.07%   |
| HP Compaq             | 36        | 1.97%   |
| Dell OptiPlex         | 35        | 1.91%   |
| ASUS PRIME            | 35        | 1.91%   |
| Toshiba Satellite     | 29        | 1.58%   |
| ASUS ROG              | 27        | 1.47%   |
| Dell Precision        | 26        | 1.42%   |
| ASUS All              | 26        | 1.42%   |
| Dell Inspiron         | 25        | 1.36%   |
| HP Laptop             | 19        | 1.04%   |
| Lenovo Yoga           | 18        | 0.98%   |
| ASUS TUF              | 18        | 0.98%   |
| Unknown               | 18        | 0.98%   |
| Packard Bell EasyNote | 14        | 0.76%   |
| Medion Akoya          | 14        | 0.76%   |
| Lenovo Legion         | 14        | 0.76%   |
| RPi Raspberry         | 12        | 0.66%   |
| ASUS VivoBook         | 12        | 0.66%   |
| Lenovo ThinkCentre    | 11        | 0.6%    |
| Dell Vostro           | 11        | 0.6%    |
| HP ZBook              | 10        | 0.55%   |
| HP ENVY               | 10        | 0.55%   |
| Gigabyte X570         | 9         | 0.49%   |
| Valve Jupiter         | 8         | 0.44%   |
| Acer Nitro            | 8         | 0.44%   |
| HP ProDesk            | 7         | 0.38%   |
| Fujitsu ESPRIMO       | 7         | 0.38%   |
| Lenovo ThinkBook      | 6         | 0.33%   |
| Lenovo IdeaCentre     | 6         | 0.33%   |
| Dell Studio           | 6         | 0.33%   |
| ASRock B450M          | 6         | 0.33%   |
| MSI MS-7C37           | 5         | 0.27%   |
| MSI MS-7B86           | 5         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 177       | 9.66%   |
| 2018    | 177       | 9.66%   |
| 2019    | 163       | 8.9%    |
| 2012    | 143       | 7.81%   |
| 2013    | 133       | 7.26%   |
| 2011    | 131       | 7.15%   |
| 2014    | 113       | 6.17%   |
| 2017    | 110       | 6%      |
| 2021    | 98        | 5.35%   |
| 2016    | 85        | 4.64%   |
| 2015    | 84        | 4.59%   |
| 2010    | 83        | 4.53%   |
| 2008    | 83        | 4.53%   |
| 2009    | 72        | 3.93%   |
| 2022    | 64        | 3.49%   |
| 2007    | 54        | 2.95%   |
| 2006    | 26        | 1.42%   |
| Unknown | 19        | 1.04%   |
| 2023    | 11        | 0.6%    |
| 2005    | 4         | 0.22%   |
| 2004    | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1031      | 56.28%  |
| Desktop        | 660       | 36.03%  |
| Convertible    | 53        | 2.89%   |
| Mini pc        | 25        | 1.36%   |
| All in one     | 21        | 1.15%   |
| System on chip | 17        | 0.93%   |
| Server         | 13        | 0.71%   |
| Tablet         | 12        | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1689      | 91.1%   |
| Enabled  | 165       | 8.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1828      | 99.78%  |
| Yes  | 4         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 409       | 21.78%  |
| 16.01-24.0      | 405       | 21.57%  |
| 8.01-16.0       | 348       | 18.53%  |
| 3.01-4.0        | 322       | 17.15%  |
| 32.01-64.0      | 191       | 10.17%  |
| 1.01-2.0        | 60        | 3.19%   |
| 64.01-256.0     | 58        | 3.09%   |
| 24.01-32.0      | 35        | 1.86%   |
| 2.01-3.0        | 26        | 1.38%   |
| 0.51-1.0        | 17        | 0.91%   |
| More than 256.0 | 4         | 0.21%   |
| 0.01-0.5        | 3         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 701       | 33.46%  |
| 2.01-3.0    | 523       | 24.96%  |
| 4.01-8.0    | 307       | 14.65%  |
| 3.01-4.0    | 273       | 13.03%  |
| 0.51-1.0    | 136       | 6.49%   |
| 8.01-16.0   | 103       | 4.92%   |
| 0.01-0.5    | 33        | 1.58%   |
| 16.01-24.0  | 10        | 0.48%   |
| 24.01-32.0  | 7         | 0.33%   |
| 64.01-256.0 | 1         | 0.05%   |
| Unknown     | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1085      | 56.96%  |
| 2       | 484       | 25.41%  |
| 3       | 149       | 7.82%   |
| 4       | 88        | 4.62%   |
| 5       | 45        | 2.36%   |
| 6       | 23        | 1.21%   |
| 0       | 16        | 0.84%   |
| 9       | 4         | 0.21%   |
| 8       | 4         | 0.21%   |
| 7       | 4         | 0.21%   |
| 16      | 1         | 0.05%   |
| 10      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1050      | 56.85%  |
| Yes       | 797       | 43.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1644      | 89.25%  |
| No        | 198       | 10.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1394      | 75.6%   |
| No        | 450       | 24.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1092      | 58.58%  |
| No        | 772       | 41.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Belgium | 1832      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Brussels       | 250       | 12.24%  |
| Antwerp        | 126       | 6.17%   |
| Ghent          | 82        | 4.01%   |
| Liège         | 60        | 2.94%   |
| Ixelles-Elsene | 45        | 2.2%    |
| Mechelen       | 33        | 1.62%   |
| Leuven         | 27        | 1.32%   |
| Bruges         | 22        | 1.08%   |
| Turnhout       | 21        | 1.03%   |
| Schaarbeek     | 18        | 0.88%   |
| Hasselt        | 17        | 0.83%   |
| Anderlecht     | 17        | 0.83%   |
| Uccle          | 16        | 0.78%   |
| Namur          | 16        | 0.78%   |
| Mons           | 16        | 0.78%   |
| Aalst          | 16        | 0.78%   |
| La Louvière   | 14        | 0.69%   |
| Mortsel        | 13        | 0.64%   |
| Lier           | 13        | 0.64%   |
| Etterbeek      | 13        | 0.64%   |
| Jette          | 12        | 0.59%   |
| Wilrijk        | 11        | 0.54%   |
| Sint-Niklaas   | 11        | 0.54%   |
| Seraing        | 11        | 0.54%   |
| Roeselare      | 11        | 0.54%   |
| Kontich        | 11        | 0.54%   |
| Gavere         | 11        | 0.54%   |
| Duffel         | 11        | 0.54%   |
| Deurne         | 11        | 0.54%   |
| Charleroi      | 11        | 0.54%   |
| Boom           | 11        | 0.54%   |
| Tournai        | 10        | 0.49%   |
| Sint-Truiden   | 10        | 0.49%   |
| Kanne          | 10        | 0.49%   |
| Bilzen         | 10        | 0.49%   |
| Waregem        | 9         | 0.44%   |
| Vilvoorde      | 9         | 0.44%   |
| Langdorp       | 9         | 0.44%   |
| Harelbeke      | 9         | 0.44%   |
| Hamme          | 9         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 560       | 1017   | 20.71%  |
| WDC                         | 403       | 679    | 14.9%   |
| Seagate                     | 392       | 669    | 14.5%   |
| Toshiba                     | 174       | 237    | 6.43%   |
| Kingston                    | 146       | 225    | 5.4%    |
| SanDisk                     | 122       | 159    | 4.51%   |
| Unknown                     | 103       | 141    | 3.81%   |
| Crucial                     | 101       | 142    | 3.74%   |
| Hitachi                     | 83        | 113    | 3.07%   |
| SK hynix                    | 79        | 99     | 2.92%   |
| Intel                       | 74        | 89     | 2.74%   |
| Micron Technology           | 49        | 55     | 1.81%   |
| HGST                        | 45        | 65     | 1.66%   |
| Apple                       | 23        | 29     | 0.85%   |
| Phison                      | 19        | 22     | 0.7%    |
| LITEON                      | 19        | 26     | 0.7%    |
| KIOXIA                      | 19        | 21     | 0.7%    |
| Intenso                     | 18        | 26     | 0.67%   |
| Maxtor                      | 16        | 19     | 0.59%   |
| Corsair                     | 16        | 17     | 0.59%   |
| Micron/Crucial Technology   | 15        | 22     | 0.55%   |
| Fujitsu                     | 14        | 20     | 0.52%   |
| China                       | 14        | 17     | 0.52%   |
| A-DATA Technology           | 14        | 19     | 0.52%   |
| OCZ                         | 13        | 16     | 0.48%   |
| PNY                         | 10        | 11     | 0.37%   |
| Phison Electronics          | 9         | 11     | 0.33%   |
| LaCie                       | 9         | 12     | 0.33%   |
| Silicon Motion              | 8         | 11     | 0.3%    |
| LITEONIT                    | 8         | 11     | 0.3%    |
| Kingston Technology Company | 8         | 8      | 0.3%    |
| Transcend                   | 7         | 12     | 0.26%   |
| LDLC                        | 6         | 7      | 0.22%   |
| GOODRAM                     | 6         | 10     | 0.22%   |
| ASMT                        | 6         | 6      | 0.22%   |
| KingSpec                    | 5         | 5      | 0.18%   |
| Union Memory                | 4         | 8      | 0.15%   |
| SSSTC                       | 4         | 4      | 0.15%   |
| KingFast                    | 4         | 4      | 0.15%   |
| JMicron Technology          | 4         | 6      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 34        | 1.11%   |
| Samsung SSD 850 EVO 250GB                           | 27        | 0.88%   |
| Samsung NVMe SSD Drive 1TB                          | 27        | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 25        | 0.81%   |
| Samsung SSD 850 EVO 500GB                           | 24        | 0.78%   |
| Samsung NVMe SSD Drive 512GB                        | 23        | 0.75%   |
| Kingston SV300S37A120G 120GB SSD                    | 23        | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 22        | 0.72%   |
| Samsung SSD 860 EVO 250GB                           | 21        | 0.68%   |
| Samsung SSD 860 EVO 1TB                             | 21        | 0.68%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.68%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.65%   |
| Toshiba DT01ACA100 1TB                              | 17        | 0.55%   |
| Samsung SSD 870 EVO 1TB                             | 17        | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                      | 16        | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 16        | 0.52%   |
| Seagate Expansion 1TB                               | 15        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 0.49%   |
| Samsung SSD 840 EVO 250GB                           | 15        | 0.49%   |
| Kingston SA400S37240G 240GB SSD                     | 15        | 0.49%   |
| Intel NVMe SSD Drive 512GB                          | 15        | 0.49%   |
| Toshiba MQ01ABD100 1TB                              | 14        | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.46%   |
| Unknown MMC Card  64GB                              | 13        | 0.42%   |
| Unknown MMC Card  32GB                              | 13        | 0.42%   |
| SK hynix NVMe SSD Drive 512GB                       | 13        | 0.42%   |
| Seagate ST9500325AS 500GB                           | 13        | 0.42%   |
| Seagate ST2000DM001-1CH164 2TB                      | 13        | 0.42%   |
| Samsung SSD 870 QVO 1TB                             | 13        | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 13        | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB                      | 12        | 0.39%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.39%   |
| Crucial CT500MX500SSD1 500GB                        | 12        | 0.39%   |
| Crucial CT480BX500SSD1 480GB                        | 12        | 0.39%   |
| Unknown SD/MMC/MS PRO 128GB                         | 11        | 0.36%   |
| Unknown MMC Card  128GB                             | 11        | 0.36%   |
| Seagate ST3500418AS 500GB                           | 11        | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                        | 11        | 0.36%   |
| Samsung SSD 860 QVO 1TB                             | 11        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 381       | 652    | 35.61%  |
| WDC                 | 332       | 571    | 31.03%  |
| Toshiba             | 127       | 167    | 11.87%  |
| Hitachi             | 83        | 113    | 7.76%   |
| HGST                | 45        | 65     | 4.21%   |
| Samsung Electronics | 39        | 64     | 3.64%   |
| Maxtor              | 16        | 19     | 1.5%    |
| Fujitsu             | 14        | 19     | 1.31%   |
| Unknown             | 11        | 20     | 1.03%   |
| Apple               | 6         | 6      | 0.56%   |
| LaCie               | 2         | 2      | 0.19%   |
| Intenso             | 2         | 5      | 0.19%   |
| Hewlett-Packard     | 2         | 4      | 0.19%   |
| WD MediaMax         | 1         | 1      | 0.09%   |
| SINTECHI            | 1         | 1      | 0.09%   |
| SABRENT             | 1         | 1      | 0.09%   |
| Magnetic Data       | 1         | 1      | 0.09%   |
| Lenovo              | 1         | 2      | 0.09%   |
| KESU                | 1         | 3      | 0.09%   |
| IET                 | 1         | 3      | 0.09%   |
| ExcelStor           | 1         | 1      | 0.09%   |
| Dell                | 1         | 1      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 315       | 558    | 35.43%  |
| Kingston            | 115       | 180    | 12.94%  |
| Crucial             | 87        | 124    | 9.79%   |
| SanDisk             | 68        | 92     | 7.65%   |
| WDC                 | 48        | 57     | 5.4%    |
| SK hynix            | 22        | 34     | 2.47%   |
| Intel               | 22        | 25     | 2.47%   |
| Toshiba             | 21        | 27     | 2.36%   |
| Micron Technology   | 19        | 22     | 2.14%   |
| LITEON              | 16        | 23     | 1.8%    |
| Intenso             | 15        | 19     | 1.69%   |
| China               | 14        | 17     | 1.57%   |
| OCZ                 | 13        | 16     | 1.46%   |
| Apple               | 11        | 15     | 1.24%   |
| Corsair             | 9         | 10     | 1.01%   |
| PNY                 | 8         | 9      | 0.9%    |
| LITEONIT            | 8         | 11     | 0.9%    |
| A-DATA Technology   | 8         | 12     | 0.9%    |
| Transcend           | 6         | 11     | 0.67%   |
| GOODRAM             | 6         | 10     | 0.67%   |
| ASMT                | 6         | 6      | 0.67%   |
| KingSpec            | 4         | 4      | 0.45%   |
| Phison              | 3         | 3      | 0.34%   |
| Emtec               | 3         | 3      | 0.34%   |
| Zheino              | 2         | 2      | 0.22%   |
| SPCC                | 2         | 3      | 0.22%   |
| Seagate             | 2         | 2      | 0.22%   |
| Plextor             | 2         | 2      | 0.22%   |
| KingFast            | 2         | 2      | 0.22%   |
| JMicron Technology  | 2         | 3      | 0.22%   |
| FORESEE             | 2         | 2      | 0.22%   |
| Unknown             | 2         | 2      | 0.22%   |
| WDC WDS             | 1         | 1      | 0.11%   |
| Verbatim            | 1         | 1      | 0.11%   |
| Vaseky              | 1         | 1      | 0.11%   |
| TO Exter            | 1         | 1      | 0.11%   |
| tigo                | 1         | 1      | 0.11%   |
| Teclast             | 1         | 1      | 0.11%   |
| Reeinno             | 1         | 3      | 0.11%   |
| Patriot             | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 891       | 1722   | 36.62%  |
| SSD     | 785       | 1338   | 32.26%  |
| NVMe    | 634       | 953    | 26.06%  |
| MMC     | 83        | 100    | 3.41%   |
| Unknown | 40        | 61     | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1330      | 2894   | 61.29%  |
| NVMe | 634       | 953    | 29.22%  |
| SAS  | 123       | 227    | 5.67%   |
| MMC  | 83        | 100    | 3.82%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1026      | 1725   | 56.84%  |
| 0.51-1.0   | 486       | 823    | 26.93%  |
| 1.01-2.0   | 159       | 276    | 8.81%   |
| 3.01-4.0   | 64        | 115    | 3.55%   |
| 4.01-10.0  | 35        | 60     | 1.94%   |
| 2.01-3.0   | 30        | 47     | 1.66%   |
| 10.01-20.0 | 5         | 14     | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 508       | 25.51%  |
| 251-500        | 450       | 22.6%   |
| 501-1000       | 272       | 13.66%  |
| 1001-2000      | 181       | 9.09%   |
| 1-20           | 125       | 6.28%   |
| 51-100         | 119       | 5.98%   |
| More than 3000 | 118       | 5.93%   |
| 2001-3000      | 78        | 3.92%   |
| Unknown        | 78        | 3.92%   |
| 21-50          | 62        | 3.11%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 742       | 35.79%  |
| 21-50          | 311       | 15%     |
| 101-250        | 279       | 13.46%  |
| 51-100         | 205       | 9.89%   |
| 251-500        | 168       | 8.1%    |
| 501-1000       | 130       | 6.27%   |
| 1001-2000      | 92        | 4.44%   |
| Unknown        | 78        | 3.76%   |
| More than 3000 | 34        | 1.64%   |
| 2001-3000      | 34        | 1.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 6         | 26     | 3.59%   |
| Seagate ST9500325AS 500GB                      | 4         | 4      | 2.4%    |
| Seagate ST3500418AS 500GB                      | 4         | 11     | 2.4%    |
| WDC WD10EZEX-21M2NA0 1TB                       | 2         | 2      | 1.2%    |
| Toshiba MQ01ABD075 752GB                       | 2         | 2      | 1.2%    |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 1.2%    |
| Seagate ST4000DM000-1F2168 4TB                 | 2         | 4      | 1.2%    |
| Seagate ST320LT007-9ZV142 320GB                | 2         | 8      | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 7      | 1.2%    |
| Samsung Electronics SSD 970 EVO 1TB            | 2         | 4      | 1.2%    |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.2%    |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 1.2%    |
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 1.2%    |
| Hitachi HTS545050A7E380 500GB                  | 2         | 4      | 1.2%    |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 1.2%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                 | 1         | 1      | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB                   | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-75U6AA0 500GB                   | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-753CA1 500GB                    | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-07U6AA0 500GB                   | 1         | 1      | 0.6%    |
| WDC WD5000AAKS-22A7B0 500GB                    | 1         | 1      | 0.6%    |
| WDC WD5000AADS-00S9B0 500GB                    | 1         | 1      | 0.6%    |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-55JJ5T0 320GB                   | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-22ZEST0 320GB                   | 1         | 1      | 0.6%    |
| WDC WD3200BEVT-60A23T0 320GB                   | 1         | 1      | 0.6%    |
| WDC WD3200BEKT-75PVMT1 320GB                   | 1         | 6      | 0.6%    |
| WDC WD3200BEKT-60PVMT0 320GB                   | 1         | 1      | 0.6%    |
| WDC WD1600JS-60MHB5 160GB                      | 1         | 1      | 0.6%    |
| WDC WD10SPCX-60HWST0 1TB                       | 1         | 1      | 0.6%    |
| WDC WD10EZRX-00L4HB0 1TB                       | 1         | 1      | 0.6%    |
| WDC WD10EZRX-00A8LB0 1TB                       | 1         | 1      | 0.6%    |
| WDC WD10EARS-22Y5B1 1TB                        | 1         | 1      | 0.6%    |
| WDC WD10EARS-00Y5B1 1TB                        | 1         | 2      | 0.6%    |
| WDC WD10EALX-009BA0 1TB                        | 1         | 1      | 0.6%    |
| WDC WD10EALS-00Z8A0 1TB                        | 1         | 1      | 0.6%    |
| WDC WD10EADS-00P8B0 1TB                        | 1         | 1      | 0.6%    |
| WDC WD10EADS-00M2B0 1TB                        | 1         | 1      | 0.6%    |
| WDC WD Green M.2 2280 480GB                    | 1         | 1      | 0.6%    |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 94     | 27.85%  |
| WDC                 | 23        | 32     | 14.56%  |
| Hitachi             | 15        | 18     | 9.49%   |
| Samsung Electronics | 14        | 19     | 8.86%   |
| Toshiba             | 11        | 11     | 6.96%   |
| Intel               | 8         | 8      | 5.06%   |
| Crucial             | 7         | 8      | 4.43%   |
| SK hynix            | 6         | 10     | 3.8%    |
| SanDisk             | 5         | 5      | 3.16%   |
| Kingston            | 5         | 10     | 3.16%   |
| HGST                | 5         | 5      | 3.16%   |
| Maxtor              | 4         | 4      | 2.53%   |
| Fujitsu             | 4         | 8      | 2.53%   |
| Micron Technology   | 3         | 3      | 1.9%    |
| SPCC                | 1         | 1      | 0.63%   |
| OCZ                 | 1         | 1      | 0.63%   |
| KingFast            | 1         | 1      | 0.63%   |
| A-DATA Technology   | 1         | 1      | 0.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 94     | 40.37%  |
| WDC                 | 21        | 30     | 19.27%  |
| Hitachi             | 15        | 18     | 13.76%  |
| Toshiba             | 10        | 10     | 9.17%   |
| Samsung Electronics | 6         | 8      | 5.5%    |
| HGST                | 5         | 5      | 4.59%   |
| Maxtor              | 4         | 4      | 3.67%   |
| Fujitsu             | 4         | 8      | 3.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 106       | 177    | 68.83%  |
| SSD  | 41        | 52     | 26.62%  |
| NVMe | 7         | 10     | 4.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200BUCT-63TWBY0 320GB                 | 1         | 1      | 25%     |
| Samsung Electronics MZVLW128HEGR-000L2 128GB | 1         | 2      | 25%     |
| Hitachi HDS721010DLE630 1TB                  | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 2      | 25%     |
| Hitachi             | 1         | 1      | 25%     |
| HGST                | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1088      | 2477   | 54.65%  |
| Works    | 749       | 1453   | 37.62%  |
| Malfunc  | 150       | 239    | 7.53%   |
| Failed   | 4         | 5      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1248      | 53.31%  |
| AMD                              | 307       | 13.11%  |
| Samsung Electronics              | 267       | 11.41%  |
| SanDisk                          | 82        | 3.5%    |
| SK hynix                         | 55        | 2.35%   |
| Kingston Technology Company      | 39        | 1.67%   |
| ASMedia Technology               | 34        | 1.45%   |
| Phison Electronics               | 32        | 1.37%   |
| Marvell Technology Group         | 32        | 1.37%   |
| JMicron Technology               | 32        | 1.37%   |
| Micron/Crucial Technology        | 30        | 1.28%   |
| Micron Technology                | 30        | 1.28%   |
| Toshiba America Info Systems     | 28        | 1.2%    |
| Nvidia                           | 23        | 0.98%   |
| KIOXIA                           | 19        | 0.81%   |
| Union Memory (Shenzhen)          | 9         | 0.38%   |
| ADATA Technology                 | 9         | 0.38%   |
| Silicon Motion                   | 8         | 0.34%   |
| Solid State Storage Technology   | 7         | 0.3%    |
| Silicon Image                    | 5         | 0.21%   |
| Seagate Technology               | 5         | 0.21%   |
| Broadcom / LSI                   | 5         | 0.21%   |
| Apple                            | 5         | 0.21%   |
| LSI Logic / Symbios Logic        | 4         | 0.17%   |
| Lite-On Technology               | 4         | 0.17%   |
| VIA Technologies                 | 3         | 0.13%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| Transcend                        | 2         | 0.09%   |
| Silicon Integrated Systems [SiS] | 2         | 0.09%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.09%   |
| Adaptec                          | 2         | 0.09%   |
| Realtek Semiconductor            | 1         | 0.04%   |
| PMC-Sierra                       | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| HighPoint Technologies           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Areca Technology                 | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 212       | 7.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 155       | 5.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 96        | 3.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 84        | 3.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 83        | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 72        | 2.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 63        | 2.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 50        | 1.84%   |
| AMD 400 Series Chipset SATA Controller                                         | 50        | 1.84%   |
| Samsung NVMe SSD Controller 980                                                | 45        | 1.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 43        | 1.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 42        | 1.55%   |
| Intel SATA Controller [RAID mode]                                              | 40        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 39        | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 38        | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 38        | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 35        | 1.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 33        | 1.22%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 32        | 1.18%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 32        | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 32        | 1.18%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 30        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 30        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 28        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 28        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 28        | 1.03%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 27        | 1%      |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 26        | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 19        | 0.7%    |
| Intel SSD 660P Series                                                          | 19        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 19        | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                             | 18        | 0.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 17        | 0.63%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 16        | 0.59%   |
| Intel Tiger Lake-LP SATA Controller                                            | 16        | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 16        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1314      | 55.23%  |
| NVMe | 638       | 26.82%  |
| IDE  | 237       | 9.96%   |
| RAID | 175       | 7.36%   |
| SAS  | 13        | 0.55%   |
| SCSI | 2         | 0.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 1422      | 77.62%  |
| AMD     | 393       | 21.45%  |
| ARM     | 15        | 0.82%   |
| Unknown | 2         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 28        | 1.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 25        | 1.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 22        | 1.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 1.14%   |
| AMD Ryzen 5 3600 6-Core Processor       | 20        | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 19        | 1.04%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 17        | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 17        | 0.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 16        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 15        | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 15        | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 14        | 0.76%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 12        | 0.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 12        | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 12        | 0.65%   |
| ARM Processor                           | 12        | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 12        | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 0.6%    |
| Intel Core i7-8665U CPU @ 1.90GHz       | 11        | 0.6%    |
| Intel Core i7-10510U CPU @ 1.80GHz      | 11        | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 11        | 0.6%    |
| AMD Ryzen 7 3700X 8-Core Processor      | 11        | 0.6%    |
| Intel Core i7-8700 CPU @ 3.20GHz        | 10        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 10        | 0.54%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 10        | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 10        | 0.54%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 10        | 0.54%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 10        | 0.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 10        | 0.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 10        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 9         | 0.49%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 9         | 0.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 0.49%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 9         | 0.49%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 9         | 0.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 9         | 0.49%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 9         | 0.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 9         | 0.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 8         | 0.44%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 8         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 425       | 23.19%  |
| Intel Core i5           | 406       | 22.15%  |
| Other                   | 140       | 7.64%   |
| Intel Core i3           | 128       | 6.98%   |
| AMD Ryzen 5             | 99        | 5.4%    |
| Intel Core 2 Duo        | 93        | 5.07%   |
| AMD Ryzen 7             | 79        | 4.31%   |
| Intel Celeron           | 50        | 2.73%   |
| AMD Ryzen 9             | 44        | 2.4%    |
| Intel Xeon              | 34        | 1.85%   |
| Intel Pentium           | 31        | 1.69%   |
| Intel Atom              | 24        | 1.31%   |
| Intel Pentium Dual-Core | 23        | 1.25%   |
| Intel Core 2            | 21        | 1.15%   |
| Intel Core 2 Quad       | 19        | 1.04%   |
| AMD Ryzen 7 PRO         | 13        | 0.71%   |
| Intel Core i9           | 12        | 0.65%   |
| AMD Ryzen 5 PRO         | 12        | 0.65%   |
| AMD E1                  | 12        | 0.65%   |
| AMD Ryzen 3             | 10        | 0.55%   |
| AMD E                   | 10        | 0.55%   |
| AMD A8                  | 10        | 0.55%   |
| AMD A4                  | 10        | 0.55%   |
| AMD FX                  | 9         | 0.49%   |
| AMD A6                  | 9         | 0.49%   |
| Intel Pentium Dual      | 8         | 0.44%   |
| Intel Genuine           | 8         | 0.44%   |
| AMD A10                 | 8         | 0.44%   |
| Intel Pentium Silver    | 7         | 0.38%   |
| AMD Phenom II X4        | 7         | 0.38%   |
| Intel Pentium 4         | 5         | 0.27%   |
| AMD Phenom              | 5         | 0.27%   |
| AMD Athlon II X2        | 5         | 0.27%   |
| AMD Ryzen Threadripper  | 4         | 0.22%   |
| AMD Athlon 64 X2        | 4         | 0.22%   |
| Intel Xeon Silver       | 3         | 0.16%   |
| Intel Celeron M         | 3         | 0.16%   |
| ARM BCM                 | 3         | 0.16%   |
| AMD Turion 64 X2 Mobile | 3         | 0.16%   |
| AMD Phenom II X6        | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 692       | 37.71%  |
| 2       | 684       | 37.28%  |
| 6       | 185       | 10.08%  |
| 8       | 137       | 7.47%   |
| 12      | 51        | 2.78%   |
| 1       | 29        | 1.58%   |
| 10      | 19        | 1.04%   |
| 16      | 12        | 0.65%   |
| Unknown | 7         | 0.38%   |
| 14      | 6         | 0.33%   |
| 3       | 6         | 0.33%   |
| 64      | 2         | 0.11%   |
| 32      | 2         | 0.11%   |
| 128     | 1         | 0.05%   |
| 24      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1811      | 98.85%  |
| 2       | 17        | 0.93%   |
| Unknown | 3         | 0.16%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1260      | 68.66%  |
| 1       | 568       | 30.95%  |
| Unknown | 7         | 0.38%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1786      | 97.12%  |
| Unknown        | 39        | 2.12%   |
| 32-bit         | 13        | 0.71%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 488       | 25.35%  |
| 0x306a9    | 114       | 5.92%   |
| 0x206a7    | 106       | 5.51%   |
| 0x306c3    | 97        | 5.04%   |
| 0x1067a    | 63        | 3.27%   |
| 0x906e9    | 49        | 2.55%   |
| 0x906ea    | 46        | 2.39%   |
| 0x806ea    | 46        | 2.39%   |
| 0x806ec    | 43        | 2.23%   |
| 0x40651    | 37        | 1.92%   |
| 0x506e3    | 36        | 1.87%   |
| 0x806c1    | 35        | 1.82%   |
| 0x20655    | 33        | 1.71%   |
| 0x806e9    | 32        | 1.66%   |
| 0x306d4    | 30        | 1.56%   |
| 0x406e3    | 29        | 1.51%   |
| 0x08701021 | 28        | 1.45%   |
| 0x6fd      | 27        | 1.4%    |
| 0x10676    | 22        | 1.14%   |
| 0xa0652    | 19        | 0.99%   |
| 0x0a50000c | 19        | 0.99%   |
| 0x08600106 | 18        | 0.94%   |
| 0x30678    | 15        | 0.78%   |
| 0x106e5    | 15        | 0.78%   |
| 0x08701013 | 15        | 0.78%   |
| 0x6f6      | 14        | 0.73%   |
| 0x08608103 | 14        | 0.73%   |
| 0x806eb    | 13        | 0.68%   |
| 0x6fb      | 13        | 0.68%   |
| 0x08108109 | 13        | 0.68%   |
| 0x20652    | 12        | 0.62%   |
| 0x206d7    | 11        | 0.57%   |
| 0x08600103 | 11        | 0.57%   |
| 0x0a201009 | 10        | 0.52%   |
| 0x0800820d | 10        | 0.52%   |
| 0x05000119 | 10        | 0.52%   |
| 0x010000c8 | 10        | 0.52%   |
| 0x0810100b | 9         | 0.47%   |
| 0x07030105 | 9         | 0.47%   |
| 0x06001119 | 9         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 311       | 16.96%  |
| Haswell          | 178       | 9.71%   |
| SandyBridge      | 144       | 7.85%   |
| IvyBridge        | 142       | 7.74%   |
| Zen 2            | 104       | 5.67%   |
| Penryn           | 102       | 5.56%   |
| Skylake          | 86        | 4.69%   |
| Unknown          | 76        | 4.14%   |
| Core             | 75        | 4.09%   |
| Zen 3            | 58        | 3.16%   |
| Westmere         | 57        | 3.11%   |
| TigerLake        | 53        | 2.89%   |
| CometLake        | 43        | 2.34%   |
| Zen+             | 42        | 2.29%   |
| Silvermont       | 42        | 2.29%   |
| Broadwell        | 41        | 2.24%   |
| Alderlake Hybrid | 32        | 1.74%   |
| Zen              | 29        | 1.58%   |
| K10              | 28        | 1.53%   |
| Nehalem          | 27        | 1.47%   |
| IceLake          | 22        | 1.2%    |
| Piledriver       | 19        | 1.04%   |
| Bobcat           | 17        | 0.93%   |
| Goldmont plus    | 15        | 0.82%   |
| Excavator        | 15        | 0.82%   |
| Puma             | 13        | 0.71%   |
| Jaguar           | 11        | 0.6%    |
| K8 Hammer        | 10        | 0.55%   |
| Bonnell          | 10        | 0.55%   |
| P6               | 8         | 0.44%   |
| NetBurst         | 8         | 0.44%   |
| Goldmont         | 5         | 0.27%   |
| Tremont          | 3         | 0.16%   |
| K8 & K10 hybrid  | 3         | 0.16%   |
| Steamroller      | 2         | 0.11%   |
| K10 Llano        | 2         | 0.11%   |
| Gracemont        | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1029      | 47.57%  |
| Nvidia                           | 666       | 30.79%  |
| AMD                              | 454       | 20.99%  |
| Matrox Electronics Systems       | 9         | 0.42%   |
| ASPEED Technology                | 3         | 0.14%   |
| VIA Technologies                 | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 89        | 4%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 88        | 3.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 51        | 2.29%   |
| Intel UHD Graphics 620                                                                   | 51        | 2.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 51        | 2.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 2.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 37        | 1.66%   |
| AMD Renoir                                                                               | 37        | 1.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 35        | 1.57%   |
| Intel HD Graphics 630                                                                    | 34        | 1.53%   |
| Intel HD Graphics 620                                                                    | 33        | 1.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 31        | 1.39%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 31        | 1.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 1.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.17%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 25        | 1.12%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 0.99%   |
| Intel HD Graphics 530                                                                    | 21        | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 0.94%   |
| AMD Lucienne                                                                             | 20        | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 19        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 19        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.72%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 15        | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 14        | 0.63%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 14        | 0.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 14        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.58%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 12        | 0.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 11        | 0.49%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 11        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 717       | 38.71%  |
| 1 x Nvidia         | 398       | 21.49%  |
| 1 x AMD            | 359       | 19.38%  |
| Intel + Nvidia     | 238       | 12.85%  |
| Intel + AMD        | 53        | 2.86%   |
| AMD + Nvidia       | 26        | 1.4%    |
| Other              | 21        | 1.13%   |
| 2 x AMD            | 18        | 0.97%   |
| 1 x Matrox         | 9         | 0.49%   |
| 2 x Intel          | 4         | 0.22%   |
| 2 x Nvidia         | 3         | 0.16%   |
| 1 x ASPEED         | 2         | 0.11%   |
| 1 x VIA            | 1         | 0.05%   |
| 1 x SiS            | 1         | 0.05%   |
| Nvidia + ASPEED    | 1         | 0.05%   |
| Intel + 2 x Nvidia | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1442      | 76.87%  |
| Proprietary | 345       | 18.39%  |
| Unknown     | 89        | 4.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1014      | 53.34%  |
| 1.01-2.0   | 232       | 12.2%   |
| 0.01-0.5   | 222       | 11.68%  |
| 0.51-1.0   | 153       | 8.05%   |
| 3.01-4.0   | 105       | 5.52%   |
| 7.01-8.0   | 89        | 4.68%   |
| 5.01-6.0   | 42        | 2.21%   |
| 8.01-16.0  | 26        | 1.37%   |
| 2.01-3.0   | 13        | 0.68%   |
| 16.01-24.0 | 5         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 287       | 14.36%  |
| AU Optronics            | 283       | 14.16%  |
| LG Display              | 194       | 9.7%    |
| Chimei Innolux          | 138       | 6.9%    |
| BOE                     | 125       | 6.25%   |
| Dell                    | 112       | 5.6%    |
| Iiyama                  | 83        | 4.15%   |
| Goldstar                | 77        | 3.85%   |
| Philips                 | 65        | 3.25%   |
| Hewlett-Packard         | 64        | 3.2%    |
| AOC                     | 47        | 2.35%   |
| BenQ                    | 46        | 2.3%    |
| Sharp                   | 41        | 2.05%   |
| Acer                    | 39        | 1.95%   |
| Apple                   | 35        | 1.75%   |
| Medion                  | 34        | 1.7%    |
| Lenovo                  | 34        | 1.7%    |
| Chi Mei Optoelectronics | 32        | 1.6%    |
| Ancor Communications    | 27        | 1.35%   |
| Sony                    | 16        | 0.8%    |
| Unknown                 | 13        | 0.65%   |
| Fujitsu Siemens         | 12        | 0.6%    |
| InfoVision              | 11        | 0.55%   |
| ASUSTek Computer        | 11        | 0.55%   |
| PANDA                   | 9         | 0.45%   |
| LG Philips              | 9         | 0.45%   |
| Eizo                    | 9         | 0.45%   |
| Vestel Elektronik       | 8         | 0.4%    |
| CSO                     | 8         | 0.4%    |
| Valve                   | 7         | 0.35%   |
| Idek Iiyama             | 7         | 0.35%   |
| Panasonic               | 6         | 0.3%    |
| LG Electronics          | 6         | 0.3%    |
| Arnos Instruments       | 6         | 0.3%    |
| ViewSonic               | 5         | 0.25%   |
| Seiko/Epson             | 5         | 0.25%   |
| Packard Bell            | 5         | 0.25%   |
| NEC Computers           | 5         | 0.25%   |
| MSI                     | 5         | 0.25%   |
| Toshiba                 | 4         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 17        | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 14        | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 11        | 0.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 10        | 0.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 9         | 0.43%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 9         | 0.43%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 9         | 0.43%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch        | 8         | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 8         | 0.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 7         | 0.33%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 7         | 0.33%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 7         | 0.33%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 6         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch         | 6         | 0.29%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 6         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 6         | 0.29%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 6         | 0.29%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.29%   |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                     | 6         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 6         | 0.29%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                            | 6         | 0.29%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 5         | 0.24%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch         | 5         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 5         | 0.24%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                     | 5         | 0.24%   |
| Dell U2515H DELD070 2560x1440 553x311mm 25.0-inch                         | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch          | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch          | 5         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO149E 1600x900 380x210mm 17.1-inch             | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 5         | 0.24%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 4         | 0.19%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 4         | 0.19%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch       | 4         | 0.19%   |
| Samsung Electronics S24R65x SAM1022 1920x1080 527x296mm 23.8-inch         | 4         | 0.19%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch         | 4         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 4         | 0.19%   |
| Medion MD 20430 MED36A2 1920x1080 521x293mm 23.5-inch                     | 4         | 0.19%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 4         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 845       | 44.13%  |
| 1366x768 (WXGA)    | 230       | 12.01%  |
| 3840x2160 (4K)     | 138       | 7.21%   |
| 1600x900 (HD+)     | 127       | 6.63%   |
| 2560x1440 (QHD)    | 112       | 5.85%   |
| 1680x1050 (WSXGA+) | 72        | 3.76%   |
| 1280x1024 (SXGA)   | 60        | 3.13%   |
| 1440x900 (WXGA+)   | 53        | 2.77%   |
| 1920x1200 (WUXGA)  | 48        | 2.51%   |
| 1280x800 (WXGA)    | 37        | 1.93%   |
| Unknown            | 26        | 1.36%   |
| 3440x1440          | 23        | 1.2%    |
| 3840x1080          | 18        | 0.94%   |
| 2560x1600          | 12        | 0.63%   |
| 2560x1080          | 11        | 0.57%   |
| 1360x768           | 10        | 0.52%   |
| 3840x2400          | 9         | 0.47%   |
| 1600x1200          | 8         | 0.42%   |
| 800x1280           | 7         | 0.37%   |
| 2880x1800          | 7         | 0.37%   |
| 1024x600           | 7         | 0.37%   |
| 3200x1800 (QHD+)   | 6         | 0.31%   |
| 1680x945           | 5         | 0.26%   |
| 1024x768 (XGA)     | 5         | 0.26%   |
| 5760x1080          | 3         | 0.16%   |
| 2736x1824          | 3         | 0.16%   |
| 3840x1600          | 2         | 0.1%    |
| 2960x1050          | 2         | 0.1%    |
| 2256x1504          | 2         | 0.1%    |
| 2048x1152          | 2         | 0.1%    |
| 1920x540           | 2         | 0.1%    |
| 1920x1280          | 2         | 0.1%    |
| 1280x960           | 2         | 0.1%    |
| 7680x2160          | 1         | 0.05%   |
| 6320x1800          | 1         | 0.05%   |
| 5120x1440          | 1         | 0.05%   |
| 4480x1080          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3520x1080          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 487       | 24.2%   |
| 17      | 183       | 9.1%    |
| 27      | 175       | 8.7%    |
| 13      | 156       | 7.75%   |
| 24      | 155       | 7.7%    |
| 23      | 136       | 6.76%   |
| 14      | 114       | 5.67%   |
| Unknown | 111       | 5.52%   |
| 21      | 101       | 5.02%   |
| 19      | 54        | 2.68%   |
| 22      | 39        | 1.94%   |
| 31      | 35        | 1.74%   |
| 34      | 31        | 1.54%   |
| 18      | 29        | 1.44%   |
| 20      | 28        | 1.39%   |
| 12      | 26        | 1.29%   |
| 11      | 18        | 0.89%   |
| 25      | 15        | 0.75%   |
| 16      | 13        | 0.65%   |
| 72      | 12        | 0.6%    |
| 10      | 12        | 0.6%    |
| 84      | 11        | 0.55%   |
| 54      | 8         | 0.4%    |
| 40      | 8         | 0.4%    |
| 32      | 8         | 0.4%    |
| 7       | 6         | 0.3%    |
| 49      | 5         | 0.25%   |
| 29      | 4         | 0.2%    |
| 65      | 3         | 0.15%   |
| 33      | 3         | 0.15%   |
| 52      | 2         | 0.1%    |
| 48      | 2         | 0.1%    |
| 46      | 2         | 0.1%    |
| 43      | 2         | 0.1%    |
| 42      | 2         | 0.1%    |
| 39      | 2         | 0.1%    |
| 37      | 2         | 0.1%    |
| 26      | 2         | 0.1%    |
| 3       | 2         | 0.1%    |
| 142     | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 669       | 33.65%  |
| 501-600        | 429       | 21.58%  |
| 351-400        | 225       | 11.32%  |
| 401-500        | 208       | 10.46%  |
| 201-300        | 154       | 7.75%   |
| Unknown        | 111       | 5.58%   |
| 601-700        | 76        | 3.82%   |
| 701-800        | 42        | 2.11%   |
| 1001-1500      | 26        | 1.31%   |
| 1501-2000      | 23        | 1.16%   |
| 801-900        | 13        | 0.65%   |
| 1-100          | 7         | 0.35%   |
| 901-1000       | 4         | 0.2%    |
| More than 2000 | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1329      | 74%     |
| 16/10   | 238       | 13.25%  |
| Unknown | 91        | 5.07%   |
| 5/4     | 55        | 3.06%   |
| 21/9    | 34        | 1.89%   |
| 4/3     | 16        | 0.89%   |
| 3/2     | 12        | 0.67%   |
| 6/5     | 6         | 0.33%   |
| 0.67    | 6         | 0.33%   |
| 32/9    | 5         | 0.28%   |
| 1.00    | 2         | 0.11%   |
| 3.73    | 1         | 0.06%   |
| 0.56    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 485       | 24.38%  |
| 201-250        | 338       | 16.99%  |
| 81-90          | 181       | 9.1%    |
| 301-350        | 178       | 8.95%   |
| 121-130        | 143       | 7.19%   |
| 151-200        | 121       | 6.08%   |
| Unknown        | 111       | 5.58%   |
| 71-80          | 90        | 4.52%   |
| 351-500        | 82        | 4.12%   |
| 251-300        | 64        | 3.22%   |
| More than 1000 | 42        | 2.11%   |
| 141-150        | 31        | 1.56%   |
| 131-140        | 26        | 1.31%   |
| 61-70          | 24        | 1.21%   |
| 501-1000       | 23        | 1.16%   |
| 51-60          | 18        | 0.9%    |
| 41-50          | 12        | 0.6%    |
| 111-120        | 11        | 0.55%   |
| 1-40           | 7         | 0.35%   |
| 91-100         | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 618       | 31.87%  |
| 121-160       | 533       | 27.49%  |
| 101-120       | 468       | 24.14%  |
| 161-240       | 125       | 6.45%   |
| Unknown       | 111       | 5.72%   |
| More than 240 | 52        | 2.68%   |
| 1-50          | 32        | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1459      | 77.28%  |
| 2     | 296       | 15.68%  |
| 0     | 97        | 5.14%   |
| 3     | 35        | 1.85%   |
| 4     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 978       | 35.47%  |
| Realtek Semiconductor             | 945       | 34.28%  |
| Qualcomm Atheros                  | 298       | 10.81%  |
| Broadcom                          | 150       | 5.44%   |
| Broadcom Limited                  | 34        | 1.23%   |
| TP-Link                           | 32        | 1.16%   |
| Marvell Technology Group          | 31        | 1.12%   |
| MediaTek                          | 28        | 1.02%   |
| Ralink                            | 25        | 0.91%   |
| Nvidia                            | 22        | 0.8%    |
| D-Link System                     | 17        | 0.62%   |
| Ralink Technology                 | 16        | 0.58%   |
| ASIX Electronics                  | 16        | 0.58%   |
| Lenovo                            | 10        | 0.36%   |
| Dell                              | 10        | 0.36%   |
| DisplayLink                       | 9         | 0.33%   |
| Sierra Wireless                   | 8         | 0.29%   |
| IMC Networks                      | 8         | 0.29%   |
| Microsoft                         | 7         | 0.25%   |
| Ericsson Business Mobile Networks | 7         | 0.25%   |
| D-Link                            | 7         | 0.25%   |
| ASUSTek Computer                  | 7         | 0.25%   |
| Microchip Technology              | 5         | 0.18%   |
| Linksys                           | 5         | 0.18%   |
| JMicron Technology                | 5         | 0.18%   |
| Sitecom Europe                    | 4         | 0.15%   |
| Samsung Electronics               | 4         | 0.15%   |
| Qualcomm Atheros Communications   | 4         | 0.15%   |
| Hewlett-Packard                   | 4         | 0.15%   |
| Fibocom                           | 4         | 0.15%   |
| Aquantia                          | 4         | 0.15%   |
| Qualcomm                          | 3         | 0.11%   |
| Arduino SA                        | 3         | 0.11%   |
| Xiaomi                            | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.07%   |
| OPPO Electronics                  | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| MosChip Semiconductor             | 2         | 0.07%   |
| Huawei Technologies               | 2         | 0.07%   |
| Google                            | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 646       | 19.59%  |
| Intel Wi-Fi 6 AX200                                               | 119       | 3.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 82        | 2.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 81        | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 1.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 57        | 1.73%   |
| Intel Wireless 7260                                               | 52        | 1.58%   |
| Intel I211 Gigabit Network Connection                             | 50        | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 47        | 1.43%   |
| Intel Wireless 8265 / 8275                                        | 47        | 1.43%   |
| Intel Wi-Fi 6 AX201                                               | 40        | 1.21%   |
| Intel Wireless 7265                                               | 38        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 36        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 34        | 1.03%   |
| Intel Wireless 8260                                               | 34        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 33        | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 31        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 30        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 30        | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 30        | 0.91%   |
| Intel Ethernet Connection (2) I219-V                              | 28        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 27        | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25        | 0.76%   |
| Intel Wireless-AC 9260                                            | 25        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 25        | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 22        | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 21        | 0.64%   |
| Intel Ethernet Controller I225-V                                  | 20        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 0.58%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.58%   |
| Intel Centrino Wireless-N 2230                                    | 19        | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 17        | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.52%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 746       | 51.03%  |
| Qualcomm Atheros                      | 234       | 16.01%  |
| Realtek Semiconductor                 | 190       | 13%     |
| Broadcom                              | 97        | 6.63%   |
| Ralink                                | 25        | 1.71%   |
| MediaTek                              | 24        | 1.64%   |
| TP-Link                               | 22        | 1.5%    |
| Broadcom Limited                      | 18        | 1.23%   |
| Ralink Technology                     | 16        | 1.09%   |
| D-Link System                         | 14        | 0.96%   |
| Sierra Wireless                       | 8         | 0.55%   |
| IMC Networks                          | 8         | 0.55%   |
| D-Link                                | 7         | 0.48%   |
| ASUSTek Computer                      | 7         | 0.48%   |
| Microsoft                             | 6         | 0.41%   |
| Linksys                               | 5         | 0.34%   |
| Sitecom Europe                        | 4         | 0.27%   |
| Qualcomm Atheros Communications       | 4         | 0.27%   |
| Fibocom                               | 4         | 0.27%   |
| Dell                                  | 4         | 0.27%   |
| Qualcomm                              | 3         | 0.21%   |
| Marvell Technology Group              | 2         | 0.14%   |
| Edimax Technology                     | 2         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.14%   |
| Z-Com                                 | 1         | 0.07%   |
| Texas Instruments                     | 1         | 0.07%   |
| Tenda                                 | 1         | 0.07%   |
| Panasonic (Matsushita)                | 1         | 0.07%   |
| NetGear                               | 1         | 0.07%   |
| Hewlett-Packard                       | 1         | 0.07%   |
| Guillemot                             | 1         | 0.07%   |
| Gemtek                                | 1         | 0.07%   |
| Belkin Components                     | 1         | 0.07%   |
| AVM                                   | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 119       | 8.09%   |
| Intel Wireless 7260                                            | 52        | 3.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 47        | 3.2%    |
| Intel Wireless 8265 / 8275                                     | 47        | 3.2%    |
| Intel Wi-Fi 6 AX201                                            | 40        | 2.72%   |
| Intel Wireless 7265                                            | 38        | 2.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 36        | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 34        | 2.31%   |
| Intel Wireless 8260                                            | 34        | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 33        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 31        | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 30        | 2.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 30        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 30        | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 27        | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 1.84%   |
| Intel Wireless-AC 9260                                         | 25        | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 22        | 1.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 21        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.29%   |
| Intel Centrino Wireless-N 2230                                 | 19        | 1.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 17        | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 16        | 1.09%   |
| Intel WiFi Link 5100                                           | 15        | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 15        | 1.02%   |
| Intel Centrino Advanced-N 6235                                 | 15        | 1.02%   |
| Intel Centrino Advanced-N 6200                                 | 15        | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14        | 0.95%   |
| Intel Wireless 3165                                            | 14        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 13        | 0.88%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 0.88%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 12        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 0.82%   |
| Intel Wireless 3160                                            | 11        | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.75%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 11        | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 10        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 869       | 49.8%   |
| Intel                                  | 527       | 30.2%   |
| Qualcomm Atheros                       | 114       | 6.53%   |
| Broadcom                               | 71        | 4.07%   |
| Marvell Technology Group               | 29        | 1.66%   |
| Nvidia                                 | 22        | 1.26%   |
| Broadcom Limited                       | 16        | 0.92%   |
| ASIX Electronics                       | 16        | 0.92%   |
| Lenovo                                 | 10        | 0.57%   |
| TP-Link                                | 9         | 0.52%   |
| DisplayLink                            | 9         | 0.52%   |
| JMicron Technology                     | 5         | 0.29%   |
| Samsung Electronics                    | 4         | 0.23%   |
| Microchip Technology                   | 4         | 0.23%   |
| MediaTek                               | 4         | 0.23%   |
| Aquantia                               | 4         | 0.23%   |
| Hewlett-Packard                        | 3         | 0.17%   |
| D-Link System                          | 3         | 0.17%   |
| Xiaomi                                 | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.11%   |
| OPPO Electronics                       | 2         | 0.11%   |
| Motorola PCS                           | 2         | 0.11%   |
| MosChip Semiconductor                  | 2         | 0.11%   |
| Google                                 | 2         | 0.11%   |
| Attansic Technology                    | 2         | 0.11%   |
| Apple                                  | 2         | 0.11%   |
| ADMtek                                 | 2         | 0.11%   |
| VIA Technologies                       | 1         | 0.06%   |
| Tehuti Networks                        | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OpenMoko                               | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| Microsoft                              | 1         | 0.06%   |
| IBM                                    | 1         | 0.06%   |
| Huawei Technologies                    | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 646       | 36.05%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 82        | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 81        | 4.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 3.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 57        | 3.18%   |
| Intel I211 Gigabit Network Connection                             | 50        | 2.79%   |
| Intel Ethernet Connection (2) I219-V                              | 28        | 1.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25        | 1.4%    |
| Intel 82579V Gigabit Network Connection                           | 25        | 1.4%    |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.23%   |
| Intel Ethernet Controller I225-V                                  | 20        | 1.12%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 19        | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 19        | 1.06%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.95%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.89%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.73%   |
| Intel Ethernet Connection (6) I219-LM                             | 11        | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 10        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.56%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 9         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 9         | 0.5%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.45%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 8         | 0.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 8         | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 7         | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1638      | 53.41%  |
| WiFi     | 1395      | 45.48%  |
| Modem    | 30        | 0.98%   |
| Unknown  | 4         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1024      | 52.73%  |
| Ethernet | 918       | 47.27%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1050      | 56.97%  |
| 1     | 694       | 37.66%  |
| 3     | 52        | 2.82%   |
| 0     | 35        | 1.9%    |
| 4     | 6         | 0.33%   |
| 5     | 3         | 0.16%   |
| 6     | 2         | 0.11%   |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1309      | 68.68%  |
| Yes  | 597       | 31.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 577       | 51.94%  |
| Realtek Semiconductor           | 91        | 8.19%   |
| Qualcomm Atheros Communications | 60        | 5.4%    |
| Broadcom                        | 53        | 4.77%   |
| Cambridge Silicon Radio         | 50        | 4.5%    |
| IMC Networks                    | 46        | 4.14%   |
| Foxconn / Hon Hai               | 39        | 3.51%   |
| Apple                           | 37        | 3.33%   |
| ASUSTek Computer                | 29        | 2.61%   |
| Lite-On Technology              | 27        | 2.43%   |
| Dell                            | 25        | 2.25%   |
| Hewlett-Packard                 | 24        | 2.16%   |
| Toshiba                         | 12        | 1.08%   |
| Belkin Components               | 8         | 0.72%   |
| MediaTek                        | 6         | 0.54%   |
| Ralink                          | 5         | 0.45%   |
| Alps Electric                   | 5         | 0.45%   |
| Foxconn International           | 4         | 0.36%   |
| Ralink Technology               | 3         | 0.27%   |
| TP-Link                         | 2         | 0.18%   |
| Marvell Semiconductor           | 2         | 0.18%   |
| Realtek                         | 1         | 0.09%   |
| Qcom                            | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| Logitech                        | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| HTC (High Tech Computer)        | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 193       | 17.32%  |
| Intel AX200 Bluetooth                               | 117       | 10.5%   |
| Intel AX201 Bluetooth                               | 95        | 8.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 74        | 6.64%   |
| Realtek Bluetooth Radio                             | 52        | 4.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 50        | 4.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 2.6%    |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 2.24%   |
| Intel Bluetooth Device                              | 19        | 1.71%   |
| IMC Networks Bluetooth Radio                        | 19        | 1.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 1.44%   |
| Apple Bluetooth Host Controller                     | 16        | 1.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1.26%   |
| IMC Networks Bluetooth Device                       | 14        | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 1.08%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 12        | 1.08%   |
| Intel AX210 Bluetooth                               | 11        | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.9%    |
| Dell DW375 Bluetooth Module                         | 10        | 0.9%    |
| Broadcom HP Portable SoftSailing                    | 10        | 0.9%    |
| Apple Bluetooth USB Host Controller                 | 10        | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.81%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 9         | 0.81%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.63%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.63%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.63%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 6         | 0.54%   |
| Lite-On Bluetooth Device                            | 6         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 0.54%   |
| Toshiba Bluetooth Device                            | 5         | 0.45%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.45%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.45%   |
| MediaTek Wireless_Device                            | 5         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1367      | 51.84%  |
| Nvidia                               | 498       | 18.89%  |
| AMD                                  | 480       | 18.2%   |
| C-Media Electronics                  | 44        | 1.67%   |
| Logitech                             | 21        | 0.8%    |
| Kingston Technology                  | 16        | 0.61%   |
| Creative Labs                        | 16        | 0.61%   |
| Realtek Semiconductor                | 13        | 0.49%   |
| Corsair                              | 12        | 0.46%   |
| GN Netcom                            | 11        | 0.42%   |
| Plantronics                          | 10        | 0.38%   |
| Hewlett-Packard                      | 10        | 0.38%   |
| Focusrite-Novation                   | 9         | 0.34%   |
| JMTek                                | 7         | 0.27%   |
| ASUSTek Computer                     | 7         | 0.27%   |
| Texas Instruments                    | 6         | 0.23%   |
| RODE Microphones                     | 6         | 0.23%   |
| Razer USA                            | 6         | 0.23%   |
| VIA Technologies                     | 5         | 0.19%   |
| Micro Star International             | 5         | 0.19%   |
| Generalplus Technology               | 5         | 0.19%   |
| Audio-Technica                       | 5         | 0.19%   |
| SteelSeries ApS                      | 4         | 0.15%   |
| Sennheiser Communications            | 4         | 0.15%   |
| Roland                               | 4         | 0.15%   |
| Blue Microphones                     | 4         | 0.15%   |
| Astro Gaming                         | 4         | 0.15%   |
| Lenovo                               | 3         | 0.11%   |
| Dell                                 | 3         | 0.11%   |
| Trust                                | 2         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.08%   |
| Sony                                 | 2         | 0.08%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.08%   |
| OPPO Electronics                     | 2         | 0.08%   |
| M-Audio                              | 2         | 0.08%   |
| Harman International                 | 2         | 0.08%   |
| GYROCOM C&C                          | 2         | 0.08%   |
| FIFINE Microphones                   | 2         | 0.08%   |
| Creative Technology                  | 2         | 0.08%   |
| BEHRINGER International              | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 139       | 4.52%   |
| AMD Family 17h/19h HD Audio Controller                                     | 138       | 4.49%   |
| Intel Sunrise Point-LP HD Audio                                            | 134       | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 126       | 4.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 94        | 3.06%   |
| AMD Starship/Matisse HD Audio Controller                                   | 89        | 2.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 79        | 2.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 73        | 2.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 71        | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 69        | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                 | 61        | 1.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 55        | 1.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 53        | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 1.56%   |
| Intel 8 Series HD Audio Controller                                         | 48        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 48        | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 46        | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 44        | 1.43%   |
| AMD FCH Azalia Controller                                                  | 43        | 1.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 42        | 1.37%   |
| Intel 200 Series PCH HD Audio                                              | 42        | 1.37%   |
| Intel Broadwell-U Audio Controller                                         | 37        | 1.2%    |
| Intel Comet Lake PCH cAVS                                                  | 35        | 1.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 34        | 1.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 34        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 32        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 32        | 1.04%   |
| Nvidia GK107 HDMI Audio Controller                                         | 31        | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 31        | 1.01%   |
| Nvidia High Definition Audio Controller                                    | 30        | 0.98%   |
| Nvidia GF108 High Definition Audio Controller                              | 30        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 29        | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                   | 29        | 0.94%   |
| Nvidia TU106 High Definition Audio Controller                              | 27        | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 27        | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 27        | 0.88%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 25        | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 269       | 23.47%  |
| SK hynix            | 212       | 18.5%   |
| Kingston            | 141       | 12.3%   |
| Corsair             | 117       | 10.21%  |
| Micron Technology   | 108       | 9.42%   |
| Unknown             | 84        | 7.33%   |
| Crucial             | 63        | 5.5%    |
| G.Skill             | 38        | 3.32%   |
| Elpida              | 23        | 2.01%   |
| Ramaxel Technology  | 19        | 1.66%   |
| Nanya Technology    | 19        | 1.66%   |
| A-DATA Technology   | 11        | 0.96%   |
| Unknown (ABCD)      | 7         | 0.61%   |
| Unknown             | 6         | 0.52%   |
| Unifosa             | 5         | 0.44%   |
| Transcend           | 4         | 0.35%   |
| Timetec             | 2         | 0.17%   |
| Team                | 2         | 0.17%   |
| Patriot             | 2         | 0.17%   |
| GOODRAM             | 2         | 0.17%   |
| Unknown (0x8551)    | 1         | 0.09%   |
| Unknown (09D5)      | 1         | 0.09%   |
| TRS STAR            | 1         | 0.09%   |
| TakeMS              | 1         | 0.09%   |
| Qimonda             | 1         | 0.09%   |
| PNY                 | 1         | 0.09%   |
| OCZ                 | 1         | 0.09%   |
| J&A Information     | 1         | 0.09%   |
| GeIL                | 1         | 0.09%   |
| Corsair SerNum0     | 1         | 0.09%   |
| Aeneon              | 1         | 0.09%   |
| A-DA                | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.13%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.73%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 0.73%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 9         | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.65%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 8         | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 7         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.57%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.57%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.57%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 7         | 0.57%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 7         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.49%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.49%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 6         | 0.49%   |
| Unknown                                                          | 6         | 0.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 5         | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 5         | 0.4%    |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 5         | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.4%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.4%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.4%    |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 5         | 0.4%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.4%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 5         | 0.4%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 4         | 0.32%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 4         | 0.32%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.32%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 490       | 47.76%  |
| DDR3    | 343       | 33.43%  |
| DDR2    | 59        | 5.75%   |
| SDRAM   | 39        | 3.8%    |
| LPDDR3  | 28        | 2.73%   |
| LPDDR4  | 25        | 2.44%   |
| Unknown | 19        | 1.85%   |
| DDR5    | 11        | 1.07%   |
| LPDDR5  | 8         | 0.78%   |
| DDR     | 4         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 595       | 59.09%  |
| DIMM         | 338       | 33.57%  |
| Row Of Chips | 65        | 6.45%   |
| Chip         | 5         | 0.5%    |
| FB-DIMM      | 2         | 0.2%    |
| RIMM         | 1         | 0.1%    |
| Unknown      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 417       | 38.22%  |
| 4096  | 286       | 26.21%  |
| 16384 | 185       | 16.96%  |
| 2048  | 127       | 11.64%  |
| 32768 | 35        | 3.21%   |
| 1024  | 34        | 3.12%   |
| 512   | 6         | 0.55%   |
| 8     | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 226       | 20.42%  |
| 3200    | 182       | 16.44%  |
| 2667    | 146       | 13.19%  |
| 2400    | 81        | 7.32%   |
| 1333    | 70        | 6.32%   |
| 2133    | 61        | 5.51%   |
| 1334    | 35        | 3.16%   |
| 667     | 32        | 2.89%   |
| 3600    | 27        | 2.44%   |
| 800     | 24        | 2.17%   |
| 1867    | 17        | 1.54%   |
| Unknown | 15        | 1.36%   |
| 1067    | 14        | 1.26%   |
| 1800    | 13        | 1.17%   |
| 4267    | 11        | 0.99%   |
| 2048    | 11        | 0.99%   |
| 3400    | 10        | 0.9%    |
| 3533    | 9         | 0.81%   |
| 2666    | 9         | 0.81%   |
| 4800    | 8         | 0.72%   |
| 3866    | 8         | 0.72%   |
| 3266    | 8         | 0.72%   |
| 6400    | 7         | 0.63%   |
| 3000    | 7         | 0.63%   |
| 3534    | 6         | 0.54%   |
| 1066    | 5         | 0.45%   |
| 975     | 5         | 0.45%   |
| 4199    | 4         | 0.36%   |
| 3666    | 4         | 0.36%   |
| 533     | 4         | 0.36%   |
| 8400    | 3         | 0.27%   |
| 3800    | 3         | 0.27%   |
| 3733    | 3         | 0.27%   |
| 3100    | 3         | 0.27%   |
| 2933    | 3         | 0.27%   |
| 1866    | 3         | 0.27%   |
| 1639    | 3         | 0.27%   |
| 1331    | 3         | 0.27%   |
| 5200    | 2         | 0.18%   |
| 2800    | 2         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 40.35%  |
| Brother Industries  | 12        | 21.05%  |
| Canon               | 8         | 14.04%  |
| Seiko Epson         | 6         | 10.53%  |
| Samsung Electronics | 3         | 5.26%   |
| Kyocera             | 2         | 3.51%   |
| Ricoh               | 1         | 1.75%   |
| Prolific Technology | 1         | 1.75%   |
| Dymo-CoStar         | 1         | 1.75%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                                 | 2         | 3.45%   |
| Samsung ML-1660 Series                                     | 2         | 3.45%   |
| HP ENVY 4500 series                                        | 2         | 3.45%   |
| HP DeskJet 3630 series                                     | 2         | 3.45%   |
| Seiko Epson XP-2200 Series                                 | 1         | 1.72%   |
| Seiko Epson WF-3010 Series                                 | 1         | 1.72%   |
| Seiko Epson ET-8550 Series                                 | 1         | 1.72%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.72%   |
| Samsung SCX-472x Series                                    | 1         | 1.72%   |
| Ricoh SP C250SF                                            | 1         | 1.72%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.72%   |
| Kyocera TASKalfa 250ci                                     | 1         | 1.72%   |
| Kyocera FS-C5150DN                                         | 1         | 1.72%   |
| HP OfficeJet Pro 6960                                      | 1         | 1.72%   |
| HP OfficeJet Pro 69                                        | 1         | 1.72%   |
| HP LaserJet Professional P 1102w                           | 1         | 1.72%   |
| HP LaserJet Pro M148f-M149f                                | 1         | 1.72%   |
| HP LaserJet P4015                                          | 1         | 1.72%   |
| HP LaserJet CM1415fn                                       | 1         | 1.72%   |
| HP LaserJet 3015                                           | 1         | 1.72%   |
| HP LaserJet 1020                                           | 1         | 1.72%   |
| HP LaserJet 1015                                           | 1         | 1.72%   |
| HP EWS UPD                                                 | 1         | 1.72%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.72%   |
| HP ENVY 5540 series                                        | 1         | 1.72%   |
| HP ENVY 4520 series                                        | 1         | 1.72%   |
| HP Deskjet F4500 series                                    | 1         | 1.72%   |
| HP DeskJet F300 series                                     | 1         | 1.72%   |
| HP DeskJet 5650c                                           | 1         | 1.72%   |
| HP DeskJet 5150c                                           | 1         | 1.72%   |
| HP DeskJet 3700 series                                     | 1         | 1.72%   |
| HP DeskJet 2600 series                                     | 1         | 1.72%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.72%   |
| Canon TS6300 series                                        | 1         | 1.72%   |
| Canon TS5300 series                                        | 1         | 1.72%   |
| Canon TS5100 series                                        | 1         | 1.72%   |
| Canon PIXMA MX920 Series                                   | 1         | 1.72%   |
| Canon PIXMA MP240                                          | 1         | 1.72%   |
| Canon MG5700 series                                        | 1         | 1.72%   |
| Canon iP4900 series                                        | 1         | 1.72%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 6         | 37.5%   |
| Seiko Epson     | 5         | 31.25%  |
| Canon           | 4         | 25%     |
| AGFA-Gevaert NV | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]        | 1         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]             | 1         | 6.25%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 6.25%   |
| Seiko Epson GT-F700 [Perfection V350]                   | 1         | 6.25%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 6.25%   |
| HP ScanJet G4010                                        | 1         | 6.25%   |
| HP scanjet 8270                                         | 1         | 6.25%   |
| HP ScanJet 4370                                         | 1         | 6.25%   |
| HP ScanJet 3800c                                        | 1         | 6.25%   |
| HP ScanJet 3670                                         | 1         | 6.25%   |
| HP ScanJet 3400cse                                      | 1         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 6.25%   |
| Canon CanoScan LiDE 210                                 | 1         | 6.25%   |
| Canon CanoScan LiDE 110                                 | 1         | 6.25%   |
| Canon CanoScan 3200F                                    | 1         | 6.25%   |
| AGFA-Gevaert NV Snapscan e40                            | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 256       | 22.54%  |
| Microdia                               | 115       | 10.12%  |
| Realtek Semiconductor                  | 88        | 7.75%   |
| Logitech                               | 81        | 7.13%   |
| IMC Networks                           | 78        | 6.87%   |
| Bison Electronics                      | 54        | 4.75%   |
| Sunplus Innovation Technology          | 51        | 4.49%   |
| Quanta                                 | 44        | 3.87%   |
| Suyin                                  | 42        | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 38        | 3.35%   |
| Lite-On Technology                     | 37        | 3.26%   |
| Apple                                  | 37        | 3.26%   |
| Syntek                                 | 34        | 2.99%   |
| Acer                                   | 30        | 2.64%   |
| Alcor Micro                            | 17        | 1.5%    |
| Luxvisions Innotech Limited            | 15        | 1.32%   |
| Ricoh                                  | 14        | 1.23%   |
| Samsung Electronics                    | 9         | 0.79%   |
| Silicon Motion                         | 6         | 0.53%   |
| Generalplus Technology                 | 6         | 0.53%   |
| Lenovo                                 | 5         | 0.44%   |
| Jieli Technology                       | 5         | 0.44%   |
| ALi                                    | 5         | 0.44%   |
| Primax Electronics                     | 4         | 0.35%   |
| Microsoft                              | 4         | 0.35%   |
| Importek                               | 4         | 0.35%   |
| Creative Technology                    | 4         | 0.35%   |
| Z-Star Microelectronics                | 3         | 0.26%   |
| WaveRider Communications               | 3         | 0.26%   |
| Trust                                  | 3         | 0.26%   |
| Sonix Technology                       | 3         | 0.26%   |
| Sunplus Technology                     | 2         | 0.18%   |
| STEREOLABS                             | 2         | 0.18%   |
| Pixart Imaging                         | 2         | 0.18%   |
| OPPO Electronics                       | 2         | 0.18%   |
| KYE Systems (Mouse Systems)            | 2         | 0.18%   |
| Hewlett-Packard                        | 2         | 0.18%   |
| GEMBIRD                                | 2         | 0.18%   |
| Dell                                   | 2         | 0.18%   |
| webcamvendor                           | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD             | 40        | 3.5%    |
| Chicony integrated camera                | 38        | 3.32%   |
| Microdia Integrated_Webcam_HD            | 34        | 2.97%   |
| IMC Networks Integrated Camera           | 32        | 2.8%    |
| Syntek Integrated Camera                 | 23        | 2.01%   |
| Bison Integrated Camera                  | 21        | 1.84%   |
| Chicony HD WebCam                        | 19        | 1.66%   |
| Microdia Integrated Webcam               | 16        | 1.4%    |
| Quanta HP HD Camera                      | 15        | 1.31%   |
| IMC Networks USB2.0 HD UVC WebCam        | 15        | 1.31%   |
| Chicony USB2.0 Camera                    | 15        | 1.31%   |
| Logitech HD Webcam C525                  | 13        | 1.14%   |
| Logitech HD Pro Webcam C920              | 13        | 1.14%   |
| Lite-On Integrated Camera                | 12        | 1.05%   |
| Chicony HP HD Webcam                     | 12        | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 12        | 1.05%   |
| Sunplus HD WebCam                        | 11        | 0.96%   |
| Lite-On HP HD Camera                     | 11        | 0.96%   |
| Chicony HP Wide Vision HD Camera         | 11        | 0.96%   |
| Chicony HP HD Camera                     | 11        | 0.96%   |
| Apple Built-in iSight                    | 11        | 0.96%   |
| Sunplus Integrated_Webcam_HD             | 10        | 0.87%   |
| Samsung Galaxy series, misc. (MTP mode)  | 9         | 0.79%   |
| Microdia USB 2.0 Camera                  | 9         | 0.79%   |
| Logitech Webcam C270                     | 9         | 0.79%   |
| Chicony USB2.0 HD UVC WebCam             | 9         | 0.79%   |
| Chicony EasyCamera                       | 9         | 0.79%   |
| Apple FaceTime HD Camera (Built-in)      | 9         | 0.79%   |
| Acer BisonCam,NB Pro                     | 9         | 0.79%   |
| Microdia Camera                          | 8         | 0.7%    |
| Chicony USB 2.0 Camera                   | 8         | 0.7%    |
| Chicony Integrated Camera (1280x720@30)  | 8         | 0.7%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 7         | 0.61%   |
| Realtek USB Camera                       | 7         | 0.61%   |
| Microdia Laptop_Integrated_Webcam_2M     | 7         | 0.61%   |
| Logitech C922 Pro Stream Webcam          | 7         | 0.61%   |
| Chicony Integrated HP HD Webcam          | 7         | 0.61%   |
| Chicony HP TrueVision HD Camera          | 7         | 0.61%   |
| Bison HD Webcam                          | 7         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam             | 6         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 91        | 37.76%  |
| Validity Sensors                   | 79        | 32.78%  |
| Shenzhen Goodix Technology         | 25        | 10.37%  |
| AuthenTec                          | 15        | 6.22%   |
| LighTuning Technology              | 10        | 4.15%   |
| Upek                               | 8         | 3.32%   |
| STMicroelectronics                 | 7         | 2.9%    |
| Elan Microelectronics              | 4         | 1.66%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.41%   |
| DigitalPersona                     | 1         | 0.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 26        | 10.79%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 10.79%  |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 4.98%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 3.32%   |
| Synaptics WBDI                                                             | 8         | 3.32%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 3.32%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 3.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 3.32%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 2.9%    |
| Synaptics  WBDI                                                            | 7         | 2.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.9%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 2.9%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 2.49%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 2.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.49%   |
| Synaptics UWP WBDI                                                         | 6         | 2.49%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 2.49%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 2.49%   |
| Validity Sensors VFS491                                                    | 5         | 2.07%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.07%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 2.07%   |
| AuthenTec AES2810                                                          | 5         | 2.07%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.66%   |
| Synaptics WBDI Device                                                      | 4         | 1.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.24%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.24%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.24%   |
| Elan ELAN:ARM-M4                                                           | 3         | 1.24%   |
| AuthenTec AES1600                                                          | 3         | 1.24%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.83%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.83%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.83%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.41%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.41%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.41%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.41%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 66        | 33.17%  |
| Alcor Micro                       | 55        | 27.64%  |
| VASCO Data Security International | 21        | 10.55%  |
| Realtek Semiconductor             | 16        | 8.04%   |
| O2 Micro                          | 13        | 6.53%   |
| Lenovo                            | 11        | 5.53%   |
| Advanced Card Systems             | 5         | 2.51%   |
| OmniKey                           | 3         | 1.51%   |
| Upek                              | 2         | 1.01%   |
| Yubico.com                        | 1         | 0.5%    |
| SCM Microsystems                  | 1         | 0.5%    |
| Integrated Technology Express     | 1         | 0.5%    |
| Gemalto (was Gemplus)             | 1         | 0.5%    |
| Feitian Technologies              | 1         | 0.5%    |
| Clay Logic                        | 1         | 0.5%    |
| Cherry                            | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 53        | 26.63%  |
| Broadcom 58200                                                               | 26        | 13.07%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 9.05%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 16        | 8.04%   |
| Broadcom 5880                                                                | 14        | 7.04%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 12        | 6.03%   |
| Lenovo Integrated Smart Card Reader                                          | 11        | 5.53%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 5.03%   |
| VASCO Data Security International DIGIPASS 870                               | 9         | 4.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 4.02%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 2.01%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.51%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 1.01%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.01%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.01%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.5%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.5%    |
| OmniKey CardMan 4321                                                         | 1         | 0.5%    |
| Integrated Technology Express SmartCard Reader                               | 1         | 0.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.5%    |
| Feitian Technologies SCR301                                                  | 1         | 0.5%    |
| Clay Logic Nitrokey Start                                                    | 1         | 0.5%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.5%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1231      | 64.69%  |
| 1     | 536       | 28.17%  |
| 2     | 106       | 5.57%   |
| 3     | 20        | 1.05%   |
| 4     | 6         | 0.32%   |
| 6     | 2         | 0.11%   |
| 8     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 236       | 29.57%  |
| Graphics card            | 162       | 20.3%   |
| Chipcard                 | 139       | 17.42%  |
| Net/wireless             | 67        | 8.4%    |
| Multimedia controller    | 44        | 5.51%   |
| Communication controller | 27        | 3.38%   |
| Camera                   | 22        | 2.76%   |
| Unassigned class         | 18        | 2.26%   |
| Card reader              | 17        | 2.13%   |
| Bluetooth                | 17        | 2.13%   |
| Sound                    | 12        | 1.5%    |
| Storage                  | 11        | 1.38%   |
| Net/ethernet             | 10        | 1.25%   |
| Network                  | 5         | 0.63%   |
| Flash memory             | 4         | 0.5%    |
| Modem                    | 3         | 0.38%   |
| Dvb card                 | 2         | 0.25%   |
| Storage/raid             | 1         | 0.13%   |
| Storage/ide              | 1         | 0.13%   |


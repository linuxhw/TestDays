OpenMandriva 23.08 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 23.08.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_23.08/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_23.08/Notebook/README.md).

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

Total: 1554

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 339A                        | Desktop     | [e8e666af64](https://linux-hardware.org/?probe=e8e666af64) | Feb 02, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [c7753ffa8e](https://linux-hardware.org/?probe=c7753ffa8e) | Feb 02, 2024 |
| Dell          | Latitude 7390               | Notebook    | [2386e8641f](https://linux-hardware.org/?probe=2386e8641f) | Feb 02, 2024 |
| Dell          | Inspiron 3442               | Notebook    | [ca29fa6852](https://linux-hardware.org/?probe=ca29fa6852) | Feb 02, 2024 |
| Dell          | Latitude 7400               | Notebook    | [ad51cec5ea](https://linux-hardware.org/?probe=ad51cec5ea) | Feb 02, 2024 |
| HP            | 18E7                        | Desktop     | [84caef4dde](https://linux-hardware.org/?probe=84caef4dde) | Feb 02, 2024 |
| PC Special... | GK5CQ7Z                     | Notebook    | [d7632585fc](https://linux-hardware.org/?probe=d7632585fc) | Feb 02, 2024 |
| Toshiba       | Satellite L50D-B            | Notebook    | [49e28cce05](https://linux-hardware.org/?probe=49e28cce05) | Feb 02, 2024 |
| Dell          | 0WMJ54 A00                  | Desktop     | [d6c3c89e3d](https://linux-hardware.org/?probe=d6c3c89e3d) | Feb 02, 2024 |
| Dell          | 0215PR A05                  | Desktop     | [05183a71ef](https://linux-hardware.org/?probe=05183a71ef) | Feb 01, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [c83dcb11ca](https://linux-hardware.org/?probe=c83dcb11ca) | Jan 31, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [bf9814808f](https://linux-hardware.org/?probe=bf9814808f) | Jan 31, 2024 |
| Unknown       | X133                        | Notebook    | [a2fcc244e8](https://linux-hardware.org/?probe=a2fcc244e8) | Jan 31, 2024 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [f37bfd54e7](https://linux-hardware.org/?probe=f37bfd54e7) | Jan 31, 2024 |
| HP            | 8B3C A                      | Desktop     | [12ec418267](https://linux-hardware.org/?probe=12ec418267) | Jan 31, 2024 |
| Evolute       | B14HM21                     | Notebook    | [c5a911ad90](https://linux-hardware.org/?probe=c5a911ad90) | Jan 31, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [9126475882](https://linux-hardware.org/?probe=9126475882) | Jan 31, 2024 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [2a526e4632](https://linux-hardware.org/?probe=2a526e4632) | Jan 30, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [3418c8d84c](https://linux-hardware.org/?probe=3418c8d84c) | Jan 30, 2024 |
| MSI           | Bravo 15 B5DD               | Notebook    | [a989f7aa10](https://linux-hardware.org/?probe=a989f7aa10) | Jan 30, 2024 |
| HP            | Pavilion dv7                | Notebook    | [7899a3498e](https://linux-hardware.org/?probe=7899a3498e) | Jan 30, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [fd6be31d9d](https://linux-hardware.org/?probe=fd6be31d9d) | Jan 30, 2024 |
| LG Electro... | E500-SP13G                  | Notebook    | [24499c2111](https://linux-hardware.org/?probe=24499c2111) | Jan 30, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [9e4c4acd0d](https://linux-hardware.org/?probe=9e4c4acd0d) | Jan 30, 2024 |
| Sony          | VPCF12A4E                   | Notebook    | [66fb5f96a0](https://linux-hardware.org/?probe=66fb5f96a0) | Jan 30, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [9cbabba588](https://linux-hardware.org/?probe=9cbabba588) | Jan 29, 2024 |
| AZW           | MINI S 10                   | Desktop     | [d707319ed7](https://linux-hardware.org/?probe=d707319ed7) | Jan 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c9d5d0fa7b](https://linux-hardware.org/?probe=c9d5d0fa7b) | Jan 29, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fbf917dbe4](https://linux-hardware.org/?probe=fbf917dbe4) | Jan 29, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [12cf7dfeeb](https://linux-hardware.org/?probe=12cf7dfeeb) | Jan 29, 2024 |
| Compaq        | Presario CQ-21              | Notebook    | [b947b6f2b8](https://linux-hardware.org/?probe=b947b6f2b8) | Jan 29, 2024 |
| Dell          | 0J3C2F A00                  | Desktop     | [95ae5646c8](https://linux-hardware.org/?probe=95ae5646c8) | Jan 29, 2024 |
| HP            | 3396                        | Desktop     | [b59e0b4023](https://linux-hardware.org/?probe=b59e0b4023) | Jan 29, 2024 |
| Positivo      | SF37405                     | Notebook    | [5955478d22](https://linux-hardware.org/?probe=5955478d22) | Jan 28, 2024 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [d3aaef580d](https://linux-hardware.org/?probe=d3aaef580d) | Jan 28, 2024 |
| ASRock        | B760M-HDV/M.2 D4            | Desktop     | [56ef6ba880](https://linux-hardware.org/?probe=56ef6ba880) | Jan 28, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [9cee6b0a5b](https://linux-hardware.org/?probe=9cee6b0a5b) | Jan 27, 2024 |
| ASRock        | H470 Phantom Gaming 4       | Desktop     | [dc402c3f43](https://linux-hardware.org/?probe=dc402c3f43) | Jan 27, 2024 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [4490f8e838](https://linux-hardware.org/?probe=4490f8e838) | Jan 27, 2024 |
| Medion        | E3223                       | Convertible | [86ea690f80](https://linux-hardware.org/?probe=86ea690f80) | Jan 26, 2024 |
| HP            | 82F2 A01                    | Desktop     | [437bec28fa](https://linux-hardware.org/?probe=437bec28fa) | Jan 26, 2024 |
| Lenovo        | Aptio CRB NOK               | Mini pc     | [97a08f730e](https://linux-hardware.org/?probe=97a08f730e) | Jan 25, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [347b980bdf](https://linux-hardware.org/?probe=347b980bdf) | Jan 25, 2024 |
| Acer          | Aspire 5820TG               | Notebook    | [d36d7405c8](https://linux-hardware.org/?probe=d36d7405c8) | Jan 25, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ff7fd4d2cd](https://linux-hardware.org/?probe=ff7fd4d2cd) | Jan 24, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5c2e73a06a](https://linux-hardware.org/?probe=5c2e73a06a) | Jan 23, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [91f61c4366](https://linux-hardware.org/?probe=91f61c4366) | Jan 23, 2024 |
| Intel         | Unknown                     | Desktop     | [8427ffd0dc](https://linux-hardware.org/?probe=8427ffd0dc) | Jan 23, 2024 |
| Positivo      | Mobile                      | Notebook    | [d1ca90b4f5](https://linux-hardware.org/?probe=d1ca90b4f5) | Jan 23, 2024 |
| Dell          | Latitude E5540              | Notebook    | [2e1716a6aa](https://linux-hardware.org/?probe=2e1716a6aa) | Jan 22, 2024 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [97f9705158](https://linux-hardware.org/?probe=97f9705158) | Jan 22, 2024 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [efa155f365](https://linux-hardware.org/?probe=efa155f365) | Jan 22, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [87f5dfadc9](https://linux-hardware.org/?probe=87f5dfadc9) | Jan 22, 2024 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [fe5025efdd](https://linux-hardware.org/?probe=fe5025efdd) | Jan 21, 2024 |
| HP            | 18E5                        | Desktop     | [69ba380344](https://linux-hardware.org/?probe=69ba380344) | Jan 21, 2024 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [8621eed350](https://linux-hardware.org/?probe=8621eed350) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [ec963a72d8](https://linux-hardware.org/?probe=ec963a72d8) | Jan 21, 2024 |
| Samsung       | X420/X520                   | Notebook    | [9dae8bd2c2](https://linux-hardware.org/?probe=9dae8bd2c2) | Jan 21, 2024 |
| HP            | EliteBook 8770w             | Notebook    | [6b53fccf5d](https://linux-hardware.org/?probe=6b53fccf5d) | Jan 21, 2024 |
| Casper        | NIRVANA NOTEBOOK            | Desktop     | [af055c48ff](https://linux-hardware.org/?probe=af055c48ff) | Jan 21, 2024 |
| Intel         | DZ77GA-70K AAG39009-500     | Desktop     | [cba7125977](https://linux-hardware.org/?probe=cba7125977) | Jan 20, 2024 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [e8a23ca7a0](https://linux-hardware.org/?probe=e8a23ca7a0) | Jan 20, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [366d017089](https://linux-hardware.org/?probe=366d017089) | Jan 20, 2024 |
| HP            | ProBook 430 G3              | Notebook    | [ed36d7cd8f](https://linux-hardware.org/?probe=ed36d7cd8f) | Jan 20, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [58be81f7c1](https://linux-hardware.org/?probe=58be81f7c1) | Jan 20, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [39cd221e89](https://linux-hardware.org/?probe=39cd221e89) | Jan 20, 2024 |
| HP            | Presario CQ43               | Notebook    | [ad1175a3a8](https://linux-hardware.org/?probe=ad1175a3a8) | Jan 20, 2024 |
| HP            | 8055                        | Desktop     | [5e6a445b12](https://linux-hardware.org/?probe=5e6a445b12) | Jan 19, 2024 |
| Dell          | Latitude E6420              | Notebook    | [b0d535026a](https://linux-hardware.org/?probe=b0d535026a) | Jan 19, 2024 |
| Google        | Garg                        | Notebook    | [2c85d92017](https://linux-hardware.org/?probe=2c85d92017) | Jan 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4d77bb448](https://linux-hardware.org/?probe=e4d77bb448) | Jan 19, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD           | Desktop     | [8d2bc7b076](https://linux-hardware.org/?probe=8d2bc7b076) | Jan 18, 2024 |
| Biostar       | A770E                       | Desktop     | [a149b3aeb6](https://linux-hardware.org/?probe=a149b3aeb6) | Jan 17, 2024 |
| Acer          | Aspire E1-531G              | Notebook    | [2c64046f89](https://linux-hardware.org/?probe=2c64046f89) | Jan 17, 2024 |
| Dell          | 0MHWCY A00                  | All in one  | [021cf9cd7c](https://linux-hardware.org/?probe=021cf9cd7c) | Jan 17, 2024 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [f414f21db4](https://linux-hardware.org/?probe=f414f21db4) | Jan 16, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [c1f78ee398](https://linux-hardware.org/?probe=c1f78ee398) | Jan 16, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [8bbf7916f3](https://linux-hardware.org/?probe=8bbf7916f3) | Jan 15, 2024 |
| Microsoft     | Surface Pro 7               | Tablet      | [bc6a402c24](https://linux-hardware.org/?probe=bc6a402c24) | Jan 14, 2024 |
| Dell          | Latitude E4310              | Notebook    | [a11f178faf](https://linux-hardware.org/?probe=a11f178faf) | Jan 14, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [4f2655db6f](https://linux-hardware.org/?probe=4f2655db6f) | Jan 14, 2024 |
| Lenovo        | G780 20138                  | Notebook    | [de9b5d4fe7](https://linux-hardware.org/?probe=de9b5d4fe7) | Jan 14, 2024 |
| Positivo      | POS-EINM10CB POSITIVO       | Desktop     | [ed11587f82](https://linux-hardware.org/?probe=ed11587f82) | Jan 14, 2024 |
| Lenovo        | ThinkPad P15v Gen 1 20TR... | Notebook    | [3382b10d32](https://linux-hardware.org/?probe=3382b10d32) | Jan 14, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [33b3e5d03d](https://linux-hardware.org/?probe=33b3e5d03d) | Jan 14, 2024 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [b62ae21449](https://linux-hardware.org/?probe=b62ae21449) | Jan 13, 2024 |
| Samsung       | 300E5M/300E5L               | Notebook    | [23fdab96e1](https://linux-hardware.org/?probe=23fdab96e1) | Jan 13, 2024 |
| Gigabyte      | H510M H V2                  | Desktop     | [1340d91b43](https://linux-hardware.org/?probe=1340d91b43) | Jan 13, 2024 |
| ASUSTek       | X756UXK                     | Notebook    | [16c3f8c205](https://linux-hardware.org/?probe=16c3f8c205) | Jan 13, 2024 |
| Dell          | 0W2F8G A01                  | Desktop     | [959d868bbf](https://linux-hardware.org/?probe=959d868bbf) | Jan 13, 2024 |
| Gigabyte      | H97M-Gaming 3               | Desktop     | [6230f1ef11](https://linux-hardware.org/?probe=6230f1ef11) | Jan 12, 2024 |
| Lenovo        | ThinkPad L570 20J9S0KG00    | Notebook    | [6d03ee96b8](https://linux-hardware.org/?probe=6d03ee96b8) | Jan 12, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [50ca06fa28](https://linux-hardware.org/?probe=50ca06fa28) | Jan 11, 2024 |
| Dell          | 04TP5V A00                  | Mini pc     | [0f58e0a990](https://linux-hardware.org/?probe=0f58e0a990) | Jan 11, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [272249651d](https://linux-hardware.org/?probe=272249651d) | Jan 11, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [bf8ac62321](https://linux-hardware.org/?probe=bf8ac62321) | Jan 11, 2024 |
| Dell          | Inspiron 11-3168            | Notebook    | [f7763a1298](https://linux-hardware.org/?probe=f7763a1298) | Jan 10, 2024 |
| Intel         | H81                         | Desktop     | [1a1c6de235](https://linux-hardware.org/?probe=1a1c6de235) | Jan 10, 2024 |
| ASRock        | Q1900B-ITX                  | Desktop     | [610dfd5b71](https://linux-hardware.org/?probe=610dfd5b71) | Jan 10, 2024 |
| Lenovo        | ThinkPad T480 20L6S6KF00    | Notebook    | [5e3205ab0e](https://linux-hardware.org/?probe=5e3205ab0e) | Jan 10, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d30a326b47](https://linux-hardware.org/?probe=d30a326b47) | Jan 10, 2024 |
| GPU Compan... | GWNR71517                   | Notebook    | [11b2e02998](https://linux-hardware.org/?probe=11b2e02998) | Jan 10, 2024 |
| Dell          | Inspiron 15 3515            | Notebook    | [1ca72e6562](https://linux-hardware.org/?probe=1ca72e6562) | Jan 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [6921991670](https://linux-hardware.org/?probe=6921991670) | Jan 09, 2024 |
| MSI           | 970A-G43                    | Desktop     | [00e0cf9c8d](https://linux-hardware.org/?probe=00e0cf9c8d) | Jan 09, 2024 |
| Razer         | Book 13 - RZ09-0357         | Notebook    | [91bd06ba56](https://linux-hardware.org/?probe=91bd06ba56) | Jan 09, 2024 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b0ac8e8208](https://linux-hardware.org/?probe=b0ac8e8208) | Jan 09, 2024 |
| OEM           | B75 Ver:1.41                | Desktop     | [5466b2e4af](https://linux-hardware.org/?probe=5466b2e4af) | Jan 08, 2024 |
| Lenovo        | ThinkCentre M72e 0896A2G    | Desktop     | [b77ad754ae](https://linux-hardware.org/?probe=b77ad754ae) | Jan 08, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [6ffbab86cc](https://linux-hardware.org/?probe=6ffbab86cc) | Jan 07, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [6fcf0891d9](https://linux-hardware.org/?probe=6fcf0891d9) | Jan 07, 2024 |
| Lenovo        | ThinkPad T60 1951YCQ        | Notebook    | [b449df298d](https://linux-hardware.org/?probe=b449df298d) | Jan 07, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7e23c64c2c](https://linux-hardware.org/?probe=7e23c64c2c) | Jan 06, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [9e7374b8ef](https://linux-hardware.org/?probe=9e7374b8ef) | Jan 06, 2024 |
| Gigabyte      | MZBSWAP-00                  | Desktop     | [eb3700b576](https://linux-hardware.org/?probe=eb3700b576) | Jan 06, 2024 |
| HP            | Compaq 6730s                | Notebook    | [1ad2b54c9d](https://linux-hardware.org/?probe=1ad2b54c9d) | Jan 05, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [59d6a69f30](https://linux-hardware.org/?probe=59d6a69f30) | Jan 05, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [d8ed7241cb](https://linux-hardware.org/?probe=d8ed7241cb) | Jan 05, 2024 |
| Intel         | JSL MRD                     | Desktop     | [8b1f990d75](https://linux-hardware.org/?probe=8b1f990d75) | Jan 05, 2024 |
| Acer          | Veriton M2630G V:1.0        | Desktop     | [40d6bf6d97](https://linux-hardware.org/?probe=40d6bf6d97) | Jan 05, 2024 |
| Dell          | Latitude 7390               | Notebook    | [1e8c287eaa](https://linux-hardware.org/?probe=1e8c287eaa) | Jan 04, 2024 |
| Lenovo        | IdeaPad S540-15IWL 81NE     | Notebook    | [65ef79e8a1](https://linux-hardware.org/?probe=65ef79e8a1) | Jan 04, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [2e71050736](https://linux-hardware.org/?probe=2e71050736) | Jan 04, 2024 |
| PIPO          | W10                         | Tablet      | [7ef241e885](https://linux-hardware.org/?probe=7ef241e885) | Jan 04, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3557687358](https://linux-hardware.org/?probe=3557687358) | Jan 04, 2024 |
| ASUSTek       | M5A78L-M LX3 PLUS           | Desktop     | [d53af9a54d](https://linux-hardware.org/?probe=d53af9a54d) | Jan 03, 2024 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [442c8e3a83](https://linux-hardware.org/?probe=442c8e3a83) | Jan 03, 2024 |
| ASUSTek       | Maximus V GENE              | Desktop     | [e62026b868](https://linux-hardware.org/?probe=e62026b868) | Jan 02, 2024 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [553bcade60](https://linux-hardware.org/?probe=553bcade60) | Jan 01, 2024 |
| Toshiba       | Satellite Pro C660          | Notebook    | [c3736ea548](https://linux-hardware.org/?probe=c3736ea548) | Dec 31, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [a4596b8ae1](https://linux-hardware.org/?probe=a4596b8ae1) | Dec 31, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6adc1110b8](https://linux-hardware.org/?probe=6adc1110b8) | Dec 30, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [2ecb9b3019](https://linux-hardware.org/?probe=2ecb9b3019) | Dec 30, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [0a6df1d55f](https://linux-hardware.org/?probe=0a6df1d55f) | Dec 28, 2023 |
| Intel         | H61                         | Desktop     | [baec7a3074](https://linux-hardware.org/?probe=baec7a3074) | Dec 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [a86830ecd2](https://linux-hardware.org/?probe=a86830ecd2) | Dec 28, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [d230832e06](https://linux-hardware.org/?probe=d230832e06) | Dec 28, 2023 |
| MSI           | MS-B9311                    | Desktop     | [424154cf65](https://linux-hardware.org/?probe=424154cf65) | Dec 28, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [282f8845af](https://linux-hardware.org/?probe=282f8845af) | Dec 27, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [9c32017999](https://linux-hardware.org/?probe=9c32017999) | Dec 26, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | Notebook    | [a49698d49d](https://linux-hardware.org/?probe=a49698d49d) | Dec 26, 2023 |
| Acer          | Predator Orion PO5-620      | Desktop     | [2d7731ff10](https://linux-hardware.org/?probe=2d7731ff10) | Dec 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [6233bad3b5](https://linux-hardware.org/?probe=6233bad3b5) | Dec 25, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [88415099d0](https://linux-hardware.org/?probe=88415099d0) | Dec 25, 2023 |
| HP            | 82F1                        | Desktop     | [86959f8199](https://linux-hardware.org/?probe=86959f8199) | Dec 24, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [a109a64bdd](https://linux-hardware.org/?probe=a109a64bdd) | Dec 24, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [a95c11e27b](https://linux-hardware.org/?probe=a95c11e27b) | Dec 23, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a84743b247](https://linux-hardware.org/?probe=a84743b247) | Dec 23, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [996611fcab](https://linux-hardware.org/?probe=996611fcab) | Dec 23, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [3625c673e4](https://linux-hardware.org/?probe=3625c673e4) | Dec 23, 2023 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [83e47fa893](https://linux-hardware.org/?probe=83e47fa893) | Dec 23, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [45b0f5ae9a](https://linux-hardware.org/?probe=45b0f5ae9a) | Dec 23, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [3441aa81e6](https://linux-hardware.org/?probe=3441aa81e6) | Dec 23, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f189893dcb](https://linux-hardware.org/?probe=f189893dcb) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | Desktop     | [739d4b0840](https://linux-hardware.org/?probe=739d4b0840) | Dec 23, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6406b552c4](https://linux-hardware.org/?probe=6406b552c4) | Dec 23, 2023 |
| Dell          | Studio 1737                 | Notebook    | [a157d70ea2](https://linux-hardware.org/?probe=a157d70ea2) | Dec 22, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [367c28d17a](https://linux-hardware.org/?probe=367c28d17a) | Dec 22, 2023 |
| Dell          | 0X7841                      | Desktop     | [3757ec7f5f](https://linux-hardware.org/?probe=3757ec7f5f) | Dec 22, 2023 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [d15476594e](https://linux-hardware.org/?probe=d15476594e) | Dec 22, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [be8f1bf021](https://linux-hardware.org/?probe=be8f1bf021) | Dec 22, 2023 |
| Acer          | One 14 Z2-493               | Notebook    | [11215309a3](https://linux-hardware.org/?probe=11215309a3) | Dec 22, 2023 |
| Dell          | Latitude E6400              | Notebook    | [6e6d4fec11](https://linux-hardware.org/?probe=6e6d4fec11) | Dec 21, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [030e411799](https://linux-hardware.org/?probe=030e411799) | Dec 21, 2023 |
| HP            | 2B28                        | Desktop     | [a3c79770af](https://linux-hardware.org/?probe=a3c79770af) | Dec 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [2675cca8c2](https://linux-hardware.org/?probe=2675cca8c2) | Dec 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [664d34d04d](https://linux-hardware.org/?probe=664d34d04d) | Dec 20, 2023 |
| Lenovo        | ThinkPad T420 4236DA4       | Notebook    | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [95bd5100ac](https://linux-hardware.org/?probe=95bd5100ac) | Dec 20, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [403d617fdd](https://linux-hardware.org/?probe=403d617fdd) | Dec 19, 2023 |
| Lenovo        | ThinkPad T590 20N5S44300    | Notebook    | [5a90e712d1](https://linux-hardware.org/?probe=5a90e712d1) | Dec 19, 2023 |
| Gigabyte      | Z77X-UP5 TH-CF              | Desktop     | [ee9b8f604a](https://linux-hardware.org/?probe=ee9b8f604a) | Dec 19, 2023 |
| Fujitsu       | FMVNF70W                    | Notebook    | [cbeca4d4e8](https://linux-hardware.org/?probe=cbeca4d4e8) | Dec 19, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [6046941a0a](https://linux-hardware.org/?probe=6046941a0a) | Dec 18, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [ffff088d9c](https://linux-hardware.org/?probe=ffff088d9c) | Dec 18, 2023 |
| Samsung       | RV409/RV509/RV709           | Notebook    | [7f55b490b8](https://linux-hardware.org/?probe=7f55b490b8) | Dec 18, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [907abd30c7](https://linux-hardware.org/?probe=907abd30c7) | Dec 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5c8981cf69](https://linux-hardware.org/?probe=5c8981cf69) | Dec 17, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [3907c9bfa3](https://linux-hardware.org/?probe=3907c9bfa3) | Dec 16, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [1e7fb2b8d8](https://linux-hardware.org/?probe=1e7fb2b8d8) | Dec 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [49e930f611](https://linux-hardware.org/?probe=49e930f611) | Dec 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [41fd53bbff](https://linux-hardware.org/?probe=41fd53bbff) | Dec 16, 2023 |
| HP            | 3647h                       | Desktop     | [4feaf76045](https://linux-hardware.org/?probe=4feaf76045) | Dec 16, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [72b7f2d771](https://linux-hardware.org/?probe=72b7f2d771) | Dec 16, 2023 |
| Toshiba       | T20                         | Notebook    | [5bb395790c](https://linux-hardware.org/?probe=5bb395790c) | Dec 16, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [2d4a3c6859](https://linux-hardware.org/?probe=2d4a3c6859) | Dec 16, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [485f360521](https://linux-hardware.org/?probe=485f360521) | Dec 15, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [a2e31b8b20](https://linux-hardware.org/?probe=a2e31b8b20) | Dec 15, 2023 |
| Teclast       | X6 plus                     | Tablet      | [ea768f654f](https://linux-hardware.org/?probe=ea768f654f) | Dec 15, 2023 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [39094226f9](https://linux-hardware.org/?probe=39094226f9) | Dec 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [8939c99ccb](https://linux-hardware.org/?probe=8939c99ccb) | Dec 15, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [22910f80b0](https://linux-hardware.org/?probe=22910f80b0) | Dec 14, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [1c7f9648af](https://linux-hardware.org/?probe=1c7f9648af) | Dec 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [51e42890da](https://linux-hardware.org/?probe=51e42890da) | Dec 14, 2023 |
| HP            | 1495                        | Desktop     | [bd97989dd8](https://linux-hardware.org/?probe=bd97989dd8) | Dec 14, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [b701b34038](https://linux-hardware.org/?probe=b701b34038) | Dec 14, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [313b058c8c](https://linux-hardware.org/?probe=313b058c8c) | Dec 14, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [7e8dd058b9](https://linux-hardware.org/?probe=7e8dd058b9) | Dec 14, 2023 |
| Acer          | Aspire A315-22              | Notebook    | [e1deaf47e9](https://linux-hardware.org/?probe=e1deaf47e9) | Dec 14, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [fe7ad66674](https://linux-hardware.org/?probe=fe7ad66674) | Dec 13, 2023 |
| Intel         | powered classmate PC        | Tablet      | [834af9a8e7](https://linux-hardware.org/?probe=834af9a8e7) | Dec 13, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [945274527c](https://linux-hardware.org/?probe=945274527c) | Dec 13, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [18a9f48bee](https://linux-hardware.org/?probe=18a9f48bee) | Dec 13, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [cdde8c0b3f](https://linux-hardware.org/?probe=cdde8c0b3f) | Dec 13, 2023 |
| ASUSTek       | K50AF                       | Notebook    | [00e0b6dc86](https://linux-hardware.org/?probe=00e0b6dc86) | Dec 13, 2023 |
| HP            | 18E5                        | Desktop     | [8195da7520](https://linux-hardware.org/?probe=8195da7520) | Dec 13, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [cc4a45597c](https://linux-hardware.org/?probe=cc4a45597c) | Dec 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6407db19a5](https://linux-hardware.org/?probe=6407db19a5) | Dec 13, 2023 |
| Positivo      | POS-PIH81DL                 | Desktop     | [55cf834e17](https://linux-hardware.org/?probe=55cf834e17) | Dec 13, 2023 |
| HP            | 8169                        | Desktop     | [e0549dcc03](https://linux-hardware.org/?probe=e0549dcc03) | Dec 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8151ecbeef](https://linux-hardware.org/?probe=8151ecbeef) | Dec 12, 2023 |
| MSI           | A88XM GAMING                | Desktop     | [1f17749a2e](https://linux-hardware.org/?probe=1f17749a2e) | Dec 12, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [0e87f04695](https://linux-hardware.org/?probe=0e87f04695) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [4cffef33b7](https://linux-hardware.org/?probe=4cffef33b7) | Dec 12, 2023 |
| Sony          | SVE1713A1EW                 | Notebook    | [64b473222e](https://linux-hardware.org/?probe=64b473222e) | Dec 12, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [56e614b2fe](https://linux-hardware.org/?probe=56e614b2fe) | Dec 12, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [8396e4fdc5](https://linux-hardware.org/?probe=8396e4fdc5) | Dec 12, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [27cbfe44c9](https://linux-hardware.org/?probe=27cbfe44c9) | Dec 12, 2023 |
| Dell          | 0TNDVR A00                  | Desktop     | [4a4ab03bc7](https://linux-hardware.org/?probe=4a4ab03bc7) | Dec 11, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [ee8ea2b093](https://linux-hardware.org/?probe=ee8ea2b093) | Dec 11, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [1b4243a8d7](https://linux-hardware.org/?probe=1b4243a8d7) | Dec 11, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [03c91234ae](https://linux-hardware.org/?probe=03c91234ae) | Dec 11, 2023 |
| MouseCompu... | H116K                       | Notebook    | [0d2d3680f0](https://linux-hardware.org/?probe=0d2d3680f0) | Dec 11, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [06651b08d9](https://linux-hardware.org/?probe=06651b08d9) | Dec 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [b9fbad0653](https://linux-hardware.org/?probe=b9fbad0653) | Dec 11, 2023 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [baec95bb2f](https://linux-hardware.org/?probe=baec95bb2f) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [be5332c927](https://linux-hardware.org/?probe=be5332c927) | Dec 11, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [96ea36be06](https://linux-hardware.org/?probe=96ea36be06) | Dec 10, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [bedb502b74](https://linux-hardware.org/?probe=bedb502b74) | Dec 10, 2023 |
| Gigabyte      | H310M DS2 x.x               | Desktop     | [6150f23143](https://linux-hardware.org/?probe=6150f23143) | Dec 10, 2023 |
| Gigabyte      | P67A-UD3P-B3                | Desktop     | [e96b9306cb](https://linux-hardware.org/?probe=e96b9306cb) | Dec 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9ae1729415](https://linux-hardware.org/?probe=9ae1729415) | Dec 10, 2023 |
| HP            | 2B29                        | Desktop     | [6fb328f58e](https://linux-hardware.org/?probe=6fb328f58e) | Dec 10, 2023 |
| HP            | 3047h                       | Desktop     | [b4e9ee347f](https://linux-hardware.org/?probe=b4e9ee347f) | Dec 10, 2023 |
| Intel         | NUC10i5FNB K61361-305       | Mini pc     | [87b9071f4a](https://linux-hardware.org/?probe=87b9071f4a) | Dec 10, 2023 |
| ASUSTek       | PRIME Z270M-PLUS            | Desktop     | [5c1ffcfbe3](https://linux-hardware.org/?probe=5c1ffcfbe3) | Dec 09, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [c576c4fbae](https://linux-hardware.org/?probe=c576c4fbae) | Dec 09, 2023 |
| MSI           | Modern 15 B12M              | Notebook    | [da95a095fa](https://linux-hardware.org/?probe=da95a095fa) | Dec 08, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [a4eb4e410e](https://linux-hardware.org/?probe=a4eb4e410e) | Dec 08, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [b1c2f80587](https://linux-hardware.org/?probe=b1c2f80587) | Dec 07, 2023 |
| Biostar       | A520MH                      | Desktop     | [de9fc0f8f2](https://linux-hardware.org/?probe=de9fc0f8f2) | Dec 07, 2023 |
| Fujitsu       | D2863 S26361-D2863-A10 W... | Server      | [b5b2a93ff1](https://linux-hardware.org/?probe=b5b2a93ff1) | Dec 07, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [52c0a2e6fa](https://linux-hardware.org/?probe=52c0a2e6fa) | Dec 07, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [986d7f4d8f](https://linux-hardware.org/?probe=986d7f4d8f) | Dec 07, 2023 |
| HP            | 21B4 A01                    | Desktop     | [a8f5a67f32](https://linux-hardware.org/?probe=a8f5a67f32) | Dec 07, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [2a4412d268](https://linux-hardware.org/?probe=2a4412d268) | Dec 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1f2c85d176](https://linux-hardware.org/?probe=1f2c85d176) | Dec 06, 2023 |
| Dell          | Latitude 7350               | Notebook    | [3fb5b65dba](https://linux-hardware.org/?probe=3fb5b65dba) | Dec 06, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [f15eca360f](https://linux-hardware.org/?probe=f15eca360f) | Dec 06, 2023 |
| Samsung       | R580/R590                   | Notebook    | [89f285aacc](https://linux-hardware.org/?probe=89f285aacc) | Dec 05, 2023 |
| Dell          | 0V0D45 A01                  | All in one  | [95f0db9f7b](https://linux-hardware.org/?probe=95f0db9f7b) | Dec 05, 2023 |
| HP            | ProBook 4540s               | Notebook    | [99c14e0650](https://linux-hardware.org/?probe=99c14e0650) | Dec 05, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [a2e7a10bdf](https://linux-hardware.org/?probe=a2e7a10bdf) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ac0fd4af39](https://linux-hardware.org/?probe=ac0fd4af39) | Dec 05, 2023 |
| ASUSTek       | K53U                        | Notebook    | [b76cef4836](https://linux-hardware.org/?probe=b76cef4836) | Dec 05, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4d14243cb9](https://linux-hardware.org/?probe=4d14243cb9) | Dec 05, 2023 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [3cdd72e242](https://linux-hardware.org/?probe=3cdd72e242) | Dec 05, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9478c73013](https://linux-hardware.org/?probe=9478c73013) | Dec 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [667c6d4e98](https://linux-hardware.org/?probe=667c6d4e98) | Dec 05, 2023 |
| Dell          | Inspiron 16 7635 2-in-1     | Convertible | [0fe6da9d8c](https://linux-hardware.org/?probe=0fe6da9d8c) | Dec 05, 2023 |
| Dell          | 02N3WF A03                  | Desktop     | [2974cc160f](https://linux-hardware.org/?probe=2974cc160f) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | Notebook    | [03866b12cd](https://linux-hardware.org/?probe=03866b12cd) | Dec 04, 2023 |
| HP            | Compaq 6730b (NA373UC#AB... | Notebook    | [7e0d2ebaaf](https://linux-hardware.org/?probe=7e0d2ebaaf) | Dec 04, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [bd98f1df4c](https://linux-hardware.org/?probe=bd98f1df4c) | Dec 04, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [ff40966f37](https://linux-hardware.org/?probe=ff40966f37) | Dec 04, 2023 |
| Acer          | Veriton S6620G v1.0         | Desktop     | [34095bbfed](https://linux-hardware.org/?probe=34095bbfed) | Dec 04, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [0f629c5ee8](https://linux-hardware.org/?probe=0f629c5ee8) | Dec 04, 2023 |
| Samsung       | 550XDA                      | Notebook    | [b5bfe47576](https://linux-hardware.org/?probe=b5bfe47576) | Dec 04, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [73fa5936a1](https://linux-hardware.org/?probe=73fa5936a1) | Dec 04, 2023 |
| HP            | 1998                        | Desktop     | [50a48ad374](https://linux-hardware.org/?probe=50a48ad374) | Dec 04, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [219f784b96](https://linux-hardware.org/?probe=219f784b96) | Dec 04, 2023 |
| HP            | ProBook 450 G0              | Notebook    | [80f6017066](https://linux-hardware.org/?probe=80f6017066) | Dec 04, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [49eeb946c5](https://linux-hardware.org/?probe=49eeb946c5) | Dec 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [f013a81cbb](https://linux-hardware.org/?probe=f013a81cbb) | Dec 03, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [5726a3acac](https://linux-hardware.org/?probe=5726a3acac) | Dec 03, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [c3d34dfe3a](https://linux-hardware.org/?probe=c3d34dfe3a) | Dec 03, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [b877f8ccda](https://linux-hardware.org/?probe=b877f8ccda) | Dec 03, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [d27ace68bb](https://linux-hardware.org/?probe=d27ace68bb) | Dec 03, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [793b594721](https://linux-hardware.org/?probe=793b594721) | Dec 03, 2023 |
| HP            | 3397                        | Desktop     | [b6c4db2738](https://linux-hardware.org/?probe=b6c4db2738) | Dec 03, 2023 |
| HP            | 8169                        | Desktop     | [6bdddabb7f](https://linux-hardware.org/?probe=6bdddabb7f) | Dec 03, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [0d59473ae1](https://linux-hardware.org/?probe=0d59473ae1) | Dec 02, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [d6118da294](https://linux-hardware.org/?probe=d6118da294) | Dec 02, 2023 |
| Intel         | X99                         | Desktop     | [e96bed5f38](https://linux-hardware.org/?probe=e96bed5f38) | Dec 02, 2023 |
| MSI           | B85M-E43 DASH               | Desktop     | [b9caa2d56f](https://linux-hardware.org/?probe=b9caa2d56f) | Dec 02, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [8f5c7fb36e](https://linux-hardware.org/?probe=8f5c7fb36e) | Dec 02, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [9a4c0266e8](https://linux-hardware.org/?probe=9a4c0266e8) | Dec 02, 2023 |
| Sony          | VJS153C11N                  | Notebook    | [eb8f061cb3](https://linux-hardware.org/?probe=eb8f061cb3) | Dec 02, 2023 |
| Sony          | VPCS13S9E                   | Notebook    | [0cd7cfa9de](https://linux-hardware.org/?probe=0cd7cfa9de) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f195d4731](https://linux-hardware.org/?probe=5f195d4731) | Dec 02, 2023 |
| Clevo         | W251ESQ/W270ESQ             | Notebook    | [8572803f38](https://linux-hardware.org/?probe=8572803f38) | Dec 01, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [ddb5b7cd64](https://linux-hardware.org/?probe=ddb5b7cd64) | Dec 01, 2023 |
| HP            | 8459                        | Desktop     | [b7a22ecb3f](https://linux-hardware.org/?probe=b7a22ecb3f) | Dec 01, 2023 |
| HP            | 240 G7                      | Notebook    | [ad50ca6a6e](https://linux-hardware.org/?probe=ad50ca6a6e) | Dec 01, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [6b97c68c9f](https://linux-hardware.org/?probe=6b97c68c9f) | Dec 01, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [8646f4d21b](https://linux-hardware.org/?probe=8646f4d21b) | Dec 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ed158c0464](https://linux-hardware.org/?probe=ed158c0464) | Dec 01, 2023 |
| Google        | Fleex                       | Notebook    | [4baac33893](https://linux-hardware.org/?probe=4baac33893) | Dec 01, 2023 |
| Samsung       | R530/R730                   | Notebook    | [cdda254219](https://linux-hardware.org/?probe=cdda254219) | Dec 01, 2023 |
| Lenovo        | ThinkPad T430 2349AK2       | Notebook    | [53a55a0da2](https://linux-hardware.org/?probe=53a55a0da2) | Dec 01, 2023 |
| Multilaser    | PC31X                       | Notebook    | [1f63edb2f9](https://linux-hardware.org/?probe=1f63edb2f9) | Dec 01, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [436f0406e4](https://linux-hardware.org/?probe=436f0406e4) | Dec 01, 2023 |
| Gigabyte      | B250-D3A-CF                 | Desktop     | [5d3de45ec6](https://linux-hardware.org/?probe=5d3de45ec6) | Dec 01, 2023 |
| Intel         | X99H                        | Desktop     | [147f088343](https://linux-hardware.org/?probe=147f088343) | Dec 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [8524905e3f](https://linux-hardware.org/?probe=8524905e3f) | Nov 30, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [915505c787](https://linux-hardware.org/?probe=915505c787) | Nov 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [cc54ea37ef](https://linux-hardware.org/?probe=cc54ea37ef) | Nov 30, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | Desktop     | [3630fd2945](https://linux-hardware.org/?probe=3630fd2945) | Nov 30, 2023 |
| AZW           | U59                         | Desktop     | [eccee157da](https://linux-hardware.org/?probe=eccee157da) | Nov 30, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b23f24b006](https://linux-hardware.org/?probe=b23f24b006) | Nov 30, 2023 |
| HP            | 1495                        | Desktop     | [9dcb53a8c2](https://linux-hardware.org/?probe=9dcb53a8c2) | Nov 30, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6a3776da6b](https://linux-hardware.org/?probe=6a3776da6b) | Nov 29, 2023 |
| Teclast       | F15S                        | Notebook    | [34392dd87e](https://linux-hardware.org/?probe=34392dd87e) | Nov 29, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1537766927](https://linux-hardware.org/?probe=1537766927) | Nov 29, 2023 |
| Lenovo        | ThinkPad W530 244723G       | Notebook    | [30e3d22482](https://linux-hardware.org/?probe=30e3d22482) | Nov 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1b2c06817f](https://linux-hardware.org/?probe=1b2c06817f) | Nov 29, 2023 |
| Unknown       | Intel BayTrail Series R1... | Desktop     | [6ab4075642](https://linux-hardware.org/?probe=6ab4075642) | Nov 29, 2023 |
| HP            | 8053                        | Desktop     | [6d6877e008](https://linux-hardware.org/?probe=6d6877e008) | Nov 29, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [8ed2e1621c](https://linux-hardware.org/?probe=8ed2e1621c) | Nov 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [d87ba8d291](https://linux-hardware.org/?probe=d87ba8d291) | Nov 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fc4e66ac12](https://linux-hardware.org/?probe=fc4e66ac12) | Nov 29, 2023 |
| ASUSTek       | GL703VM                     | Notebook    | [262f681abe](https://linux-hardware.org/?probe=262f681abe) | Nov 29, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [96af3871d2](https://linux-hardware.org/?probe=96af3871d2) | Nov 29, 2023 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [4948ddc4be](https://linux-hardware.org/?probe=4948ddc4be) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [a7b0f7fe30](https://linux-hardware.org/?probe=a7b0f7fe30) | Nov 28, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | Desktop     | [a06c08c462](https://linux-hardware.org/?probe=a06c08c462) | Nov 28, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7c53518c08](https://linux-hardware.org/?probe=7c53518c08) | Nov 28, 2023 |
| Gigabyte      | H310M DS2                   | Desktop     | [14a8656c8b](https://linux-hardware.org/?probe=14a8656c8b) | Nov 28, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [beba27b952](https://linux-hardware.org/?probe=beba27b952) | Nov 28, 2023 |
| HP            | 1497                        | Desktop     | [6cd2fea9bd](https://linux-hardware.org/?probe=6cd2fea9bd) | Nov 28, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [fe332ae4ef](https://linux-hardware.org/?probe=fe332ae4ef) | Nov 28, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [9e6c582721](https://linux-hardware.org/?probe=9e6c582721) | Nov 28, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [83375f1b7a](https://linux-hardware.org/?probe=83375f1b7a) | Nov 28, 2023 |
| Gigabyte      | G31-S3G                     | Desktop     | [895a8554b4](https://linux-hardware.org/?probe=895a8554b4) | Nov 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c1777b379](https://linux-hardware.org/?probe=8c1777b379) | Nov 28, 2023 |
| MSI           | GE60 0NC\0ND                | Notebook    | [f1285ee8a7](https://linux-hardware.org/?probe=f1285ee8a7) | Nov 28, 2023 |
| ASUSTek       | PN41-S1                     | Mini pc     | [d254031e43](https://linux-hardware.org/?probe=d254031e43) | Nov 28, 2023 |
| HP            | 18E5                        | Desktop     | [a9c04bd2c7](https://linux-hardware.org/?probe=a9c04bd2c7) | Nov 28, 2023 |
| Biostar       | H310MHP                     | Desktop     | [58282ae6c7](https://linux-hardware.org/?probe=58282ae6c7) | Nov 28, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [8c82a1d8c3](https://linux-hardware.org/?probe=8c82a1d8c3) | Nov 28, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [160556d559](https://linux-hardware.org/?probe=160556d559) | Nov 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7c4bb8dad1](https://linux-hardware.org/?probe=7c4bb8dad1) | Nov 28, 2023 |
| Samsung       | RV411/RV511/E3511/S3511     | Notebook    | [36ecf595ab](https://linux-hardware.org/?probe=36ecf595ab) | Nov 27, 2023 |
| Acer          | Aspire 5740                 | Notebook    | [bad53e91fc](https://linux-hardware.org/?probe=bad53e91fc) | Nov 27, 2023 |
| HP            | Pavilion g7                 | Notebook    | [10f5b71d45](https://linux-hardware.org/?probe=10f5b71d45) | Nov 27, 2023 |
| Dynabook      | Satellite Pro C50-H-11G     | Notebook    | [438812dbd7](https://linux-hardware.org/?probe=438812dbd7) | Nov 27, 2023 |
| Dell          | Precision 7670              | Notebook    | [450a8674d6](https://linux-hardware.org/?probe=450a8674d6) | Nov 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [d36366cac6](https://linux-hardware.org/?probe=d36366cac6) | Nov 27, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [fc4a8c9532](https://linux-hardware.org/?probe=fc4a8c9532) | Nov 27, 2023 |
| Lenovo        | ThinkCentre M58p 6137A1G    | Desktop     | [fafec0e338](https://linux-hardware.org/?probe=fafec0e338) | Nov 27, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [e8867e4bb9](https://linux-hardware.org/?probe=e8867e4bb9) | Nov 27, 2023 |
| Dell          | Latitude 13                 | Notebook    | [bf50df43fa](https://linux-hardware.org/?probe=bf50df43fa) | Nov 27, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [0ff86eddc6](https://linux-hardware.org/?probe=0ff86eddc6) | Nov 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [1276cc7c88](https://linux-hardware.org/?probe=1276cc7c88) | Nov 27, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [8c0078f865](https://linux-hardware.org/?probe=8c0078f865) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8885a17766](https://linux-hardware.org/?probe=8885a17766) | Nov 27, 2023 |
| Intel         | H61                         | Desktop     | [97a16fcd1b](https://linux-hardware.org/?probe=97a16fcd1b) | Nov 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS0RK00    | Notebook    | [96642d7e8e](https://linux-hardware.org/?probe=96642d7e8e) | Nov 27, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [7563ed582c](https://linux-hardware.org/?probe=7563ed582c) | Nov 27, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [ebdc85d7a5](https://linux-hardware.org/?probe=ebdc85d7a5) | Nov 27, 2023 |
| Dell          | 0CU409                      | Desktop     | [328adb4fd0](https://linux-hardware.org/?probe=328adb4fd0) | Nov 27, 2023 |
| Intel         | X99H                        | Desktop     | [2cbd1213a8](https://linux-hardware.org/?probe=2cbd1213a8) | Nov 27, 2023 |
| HP            | 83EE                        | Desktop     | [4a9e67adc6](https://linux-hardware.org/?probe=4a9e67adc6) | Nov 27, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [c3618a788c](https://linux-hardware.org/?probe=c3618a788c) | Nov 27, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [dda972d27c](https://linux-hardware.org/?probe=dda972d27c) | Nov 26, 2023 |
| Dell          | 07KY25 A01                  | Desktop     | [98134987bb](https://linux-hardware.org/?probe=98134987bb) | Nov 26, 2023 |
| Packard Be... | EasyNote LJ75               | Notebook    | [ec3c8ef712](https://linux-hardware.org/?probe=ec3c8ef712) | Nov 26, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [8c0edc3315](https://linux-hardware.org/?probe=8c0edc3315) | Nov 26, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [c314753a7c](https://linux-hardware.org/?probe=c314753a7c) | Nov 26, 2023 |
| HP            | 630                         | Notebook    | [cd7a4c040d](https://linux-hardware.org/?probe=cd7a4c040d) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fdb42ffac6](https://linux-hardware.org/?probe=fdb42ffac6) | Nov 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [25aa31e65e](https://linux-hardware.org/?probe=25aa31e65e) | Nov 26, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [da3ac19523](https://linux-hardware.org/?probe=da3ac19523) | Nov 26, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [21bc20e802](https://linux-hardware.org/?probe=21bc20e802) | Nov 26, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [c9d2305459](https://linux-hardware.org/?probe=c9d2305459) | Nov 26, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [cceb19120f](https://linux-hardware.org/?probe=cceb19120f) | Nov 26, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ab6a5cd935](https://linux-hardware.org/?probe=ab6a5cd935) | Nov 26, 2023 |
| MSI           | MS-B1711                    | Desktop     | [963341bb09](https://linux-hardware.org/?probe=963341bb09) | Nov 26, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [8139afea1a](https://linux-hardware.org/?probe=8139afea1a) | Nov 26, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [d9c6907311](https://linux-hardware.org/?probe=d9c6907311) | Nov 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [43e183bc2b](https://linux-hardware.org/?probe=43e183bc2b) | Nov 26, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [420c85d7b3](https://linux-hardware.org/?probe=420c85d7b3) | Nov 26, 2023 |
| ASRock        | 970A-G                      | Desktop     | [aabcb223d0](https://linux-hardware.org/?probe=aabcb223d0) | Nov 26, 2023 |
| Dell          | Latitude 12 Rugged Table... | Notebook    | [012c390a1c](https://linux-hardware.org/?probe=012c390a1c) | Nov 26, 2023 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [2d09c86fa7](https://linux-hardware.org/?probe=2d09c86fa7) | Nov 26, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [2009f6493b](https://linux-hardware.org/?probe=2009f6493b) | Nov 26, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0f5aa8a55b](https://linux-hardware.org/?probe=0f5aa8a55b) | Nov 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [454b211624](https://linux-hardware.org/?probe=454b211624) | Nov 25, 2023 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [f285125351](https://linux-hardware.org/?probe=f285125351) | Nov 25, 2023 |
| Lenovo        | ThinkPad T420 4236Q23       | Notebook    | [3bfbdef979](https://linux-hardware.org/?probe=3bfbdef979) | Nov 25, 2023 |
| Dell          | Latitude E5540              | Notebook    | [29c4fc6485](https://linux-hardware.org/?probe=29c4fc6485) | Nov 25, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Notebook    | [534d53e480](https://linux-hardware.org/?probe=534d53e480) | Nov 25, 2023 |
| Minix         | H61M-USB3 V1.2              | Desktop     | [2024379183](https://linux-hardware.org/?probe=2024379183) | Nov 25, 2023 |
| Dell          | 0K83V0 A00                  | Desktop     | [0ffd410841](https://linux-hardware.org/?probe=0ffd410841) | Nov 25, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [26cfb9b66d](https://linux-hardware.org/?probe=26cfb9b66d) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [4e8b656513](https://linux-hardware.org/?probe=4e8b656513) | Nov 24, 2023 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [a56a424940](https://linux-hardware.org/?probe=a56a424940) | Nov 24, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [39919b75ba](https://linux-hardware.org/?probe=39919b75ba) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7478563980](https://linux-hardware.org/?probe=7478563980) | Nov 23, 2023 |
| HUAWEI        | KLVF-XX                     | Notebook    | [279b1557ed](https://linux-hardware.org/?probe=279b1557ed) | Nov 23, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e257380edc](https://linux-hardware.org/?probe=e257380edc) | Nov 23, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [4b2a2cc667](https://linux-hardware.org/?probe=4b2a2cc667) | Nov 23, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [a67ae23c5a](https://linux-hardware.org/?probe=a67ae23c5a) | Nov 23, 2023 |
| Medion        | E14412                      | Notebook    | [3ba8cc6090](https://linux-hardware.org/?probe=3ba8cc6090) | Nov 22, 2023 |
| Lenovo        | G70-80 80FF                 | Notebook    | [c3acaa0cd4](https://linux-hardware.org/?probe=c3acaa0cd4) | Nov 22, 2023 |
| Lenovo        | ThinkPad T420 4180KHU       | Notebook    | [cb4a42ed82](https://linux-hardware.org/?probe=cb4a42ed82) | Nov 22, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [eff4442629](https://linux-hardware.org/?probe=eff4442629) | Nov 22, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [af6326319c](https://linux-hardware.org/?probe=af6326319c) | Nov 21, 2023 |
| Lenovo        | ThinkPad T550 20CJS02E00    | Notebook    | [00e8b77882](https://linux-hardware.org/?probe=00e8b77882) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [28af744237](https://linux-hardware.org/?probe=28af744237) | Nov 21, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [078c28606a](https://linux-hardware.org/?probe=078c28606a) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [442654cab6](https://linux-hardware.org/?probe=442654cab6) | Nov 21, 2023 |
| Dell          | Latitude E6230              | Notebook    | [467d45ff38](https://linux-hardware.org/?probe=467d45ff38) | Nov 20, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5be7c208c3](https://linux-hardware.org/?probe=5be7c208c3) | Nov 20, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [29293282c2](https://linux-hardware.org/?probe=29293282c2) | Nov 20, 2023 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [ae2a0fceac](https://linux-hardware.org/?probe=ae2a0fceac) | Nov 20, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [6ed1f31ed3](https://linux-hardware.org/?probe=6ed1f31ed3) | Nov 20, 2023 |
| HP            | 89B5 A                      | Desktop     | [4c228a49ce](https://linux-hardware.org/?probe=4c228a49ce) | Nov 20, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [f2462919d4](https://linux-hardware.org/?probe=f2462919d4) | Nov 19, 2023 |
| ASRock        | B660M-STX                   | Desktop     | [883a70813a](https://linux-hardware.org/?probe=883a70813a) | Nov 19, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [4243816d27](https://linux-hardware.org/?probe=4243816d27) | Nov 19, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [82c49fc608](https://linux-hardware.org/?probe=82c49fc608) | Nov 19, 2023 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [be4bd9aeaf](https://linux-hardware.org/?probe=be4bd9aeaf) | Nov 18, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [94ad738290](https://linux-hardware.org/?probe=94ad738290) | Nov 18, 2023 |
| HP            | Compaq 6510b (GR680ET)      | Notebook    | [4d849ef131](https://linux-hardware.org/?probe=4d849ef131) | Nov 18, 2023 |
| HP            | 8055                        | Desktop     | [1125d976fc](https://linux-hardware.org/?probe=1125d976fc) | Nov 18, 2023 |
| Lenovo        | Unknown                     | Notebook    | [616a6584a4](https://linux-hardware.org/?probe=616a6584a4) | Nov 18, 2023 |
| AMI           | Intel                       | Notebook    | [d590688338](https://linux-hardware.org/?probe=d590688338) | Nov 18, 2023 |
| Dell          | Latitude 3189               | Notebook    | [915f8dc0af](https://linux-hardware.org/?probe=915f8dc0af) | Nov 18, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [a933d36c63](https://linux-hardware.org/?probe=a933d36c63) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ff84b6e035](https://linux-hardware.org/?probe=ff84b6e035) | Nov 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [029e25867a](https://linux-hardware.org/?probe=029e25867a) | Nov 17, 2023 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [8fa21e29e3](https://linux-hardware.org/?probe=8fa21e29e3) | Nov 17, 2023 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | Notebook    | [47427f60c0](https://linux-hardware.org/?probe=47427f60c0) | Nov 16, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [63ba7cf0b1](https://linux-hardware.org/?probe=63ba7cf0b1) | Nov 16, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [e8f9a52206](https://linux-hardware.org/?probe=e8f9a52206) | Nov 16, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [96c7dc6aa1](https://linux-hardware.org/?probe=96c7dc6aa1) | Nov 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [5b960b8464](https://linux-hardware.org/?probe=5b960b8464) | Nov 16, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [e2eb5cacb7](https://linux-hardware.org/?probe=e2eb5cacb7) | Nov 15, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [160e8325ba](https://linux-hardware.org/?probe=160e8325ba) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [d4c7bc8dc8](https://linux-hardware.org/?probe=d4c7bc8dc8) | Nov 15, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [f4a73d26e0](https://linux-hardware.org/?probe=f4a73d26e0) | Nov 15, 2023 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [08053c4143](https://linux-hardware.org/?probe=08053c4143) | Nov 15, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [25b9244c80](https://linux-hardware.org/?probe=25b9244c80) | Nov 15, 2023 |
| LG Electro... | 14Z90RS-K.AAW7U1            | Notebook    | [2921cb3437](https://linux-hardware.org/?probe=2921cb3437) | Nov 14, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [556cb2f633](https://linux-hardware.org/?probe=556cb2f633) | Nov 14, 2023 |
| MSI           | Z97-G43                     | Desktop     | [ea16582cb2](https://linux-hardware.org/?probe=ea16582cb2) | Nov 14, 2023 |
| MSI           | A88X-G45 GAMING             | Desktop     | [5ab91132ea](https://linux-hardware.org/?probe=5ab91132ea) | Nov 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8e95b24f18](https://linux-hardware.org/?probe=8e95b24f18) | Nov 13, 2023 |
| HP            | 09F0h                       | Desktop     | [1c1ab6c56f](https://linux-hardware.org/?probe=1c1ab6c56f) | Nov 12, 2023 |
| Dell          | Latitude E7440              | Notebook    | [407afcc9d2](https://linux-hardware.org/?probe=407afcc9d2) | Nov 12, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [4a14d46e6b](https://linux-hardware.org/?probe=4a14d46e6b) | Nov 12, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [cccbd25b73](https://linux-hardware.org/?probe=cccbd25b73) | Nov 12, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [fcc17bd8a1](https://linux-hardware.org/?probe=fcc17bd8a1) | Nov 12, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [689f2bca5b](https://linux-hardware.org/?probe=689f2bca5b) | Nov 11, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [532b575898](https://linux-hardware.org/?probe=532b575898) | Nov 11, 2023 |
| HP            | 1850                        | Desktop     | [117ab7ea0d](https://linux-hardware.org/?probe=117ab7ea0d) | Nov 11, 2023 |
| Philco        | 14H                         | Notebook    | [01ddcfeb9e](https://linux-hardware.org/?probe=01ddcfeb9e) | Nov 11, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9c852b1f0b](https://linux-hardware.org/?probe=9c852b1f0b) | Nov 11, 2023 |
| Minix         | NEO Z83-4 V1.5              | Desktop     | [3623dfcb88](https://linux-hardware.org/?probe=3623dfcb88) | Nov 10, 2023 |
| MSI           | MS-AC111 100                | All in one  | [bccec4f06c](https://linux-hardware.org/?probe=bccec4f06c) | Nov 10, 2023 |
| ALLDOCUBE     | i1405C                      | Notebook    | [8f63b8af98](https://linux-hardware.org/?probe=8f63b8af98) | Nov 10, 2023 |
| Intel         | DG35EC AAE29266-210         | Desktop     | [fe0e055f82](https://linux-hardware.org/?probe=fe0e055f82) | Nov 10, 2023 |
| Unknown       | Unknown                     | Notebook    | [820a8f3b76](https://linux-hardware.org/?probe=820a8f3b76) | Nov 10, 2023 |
| Lenovo        | ThinkCentre M90z M91Z       | All in one  | [510092ea51](https://linux-hardware.org/?probe=510092ea51) | Nov 10, 2023 |
| HP            | 339A                        | Desktop     | [7be77c764f](https://linux-hardware.org/?probe=7be77c764f) | Nov 09, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [9f16fd11b7](https://linux-hardware.org/?probe=9f16fd11b7) | Nov 09, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [10f68961cf](https://linux-hardware.org/?probe=10f68961cf) | Nov 08, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [c301ae970c](https://linux-hardware.org/?probe=c301ae970c) | Nov 08, 2023 |
| Dell          | 082WXT A01                  | Desktop     | [41e56ed8e4](https://linux-hardware.org/?probe=41e56ed8e4) | Nov 08, 2023 |
| HP            | 339A                        | Desktop     | [cdcbe8d47d](https://linux-hardware.org/?probe=cdcbe8d47d) | Nov 07, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0f5ee4c730](https://linux-hardware.org/?probe=0f5ee4c730) | Nov 07, 2023 |
| HP            | Notebook                    | Notebook    | [e18c5aca5b](https://linux-hardware.org/?probe=e18c5aca5b) | Nov 07, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [fc483856a6](https://linux-hardware.org/?probe=fc483856a6) | Nov 07, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [3de6cf8221](https://linux-hardware.org/?probe=3de6cf8221) | Nov 07, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [4b43ed314b](https://linux-hardware.org/?probe=4b43ed314b) | Nov 06, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [c376116add](https://linux-hardware.org/?probe=c376116add) | Nov 06, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [216faa6f5d](https://linux-hardware.org/?probe=216faa6f5d) | Nov 06, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [37d32a1fd5](https://linux-hardware.org/?probe=37d32a1fd5) | Nov 06, 2023 |
| Dell          | Latitude E6410              | Notebook    | [b6ac4a50b7](https://linux-hardware.org/?probe=b6ac4a50b7) | Nov 06, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [105d51f329](https://linux-hardware.org/?probe=105d51f329) | Nov 05, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4601ae11d9](https://linux-hardware.org/?probe=4601ae11d9) | Nov 05, 2023 |
| HP            | 802F                        | Desktop     | [8fe557cc85](https://linux-hardware.org/?probe=8fe557cc85) | Nov 05, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2710dfedf4](https://linux-hardware.org/?probe=2710dfedf4) | Nov 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [f070e73453](https://linux-hardware.org/?probe=f070e73453) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | Notebook    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Acer          | Aspire M1920                | Desktop     | [f6ffcb0c41](https://linux-hardware.org/?probe=f6ffcb0c41) | Nov 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [399dda92eb](https://linux-hardware.org/?probe=399dda92eb) | Nov 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | Notebook    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| Gigabyte      | GA-870A-USB3L               | Desktop     | [d2412dfd7c](https://linux-hardware.org/?probe=d2412dfd7c) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [c74051abb7](https://linux-hardware.org/?probe=c74051abb7) | Nov 04, 2023 |
| MSI           | MS-1759                     | Notebook    | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Dell          | Latitude E7450              | Notebook    | [e7effc42ed](https://linux-hardware.org/?probe=e7effc42ed) | Nov 04, 2023 |
| Dell          | Latitude E5450              | Notebook    | [1f23c5fd7c](https://linux-hardware.org/?probe=1f23c5fd7c) | Nov 04, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [03303fa6ed](https://linux-hardware.org/?probe=03303fa6ed) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | Notebook    | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| Dell          | Latitude 3420               | Notebook    | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [d27cd12013](https://linux-hardware.org/?probe=d27cd12013) | Nov 03, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6c0dc28b9f](https://linux-hardware.org/?probe=6c0dc28b9f) | Nov 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [6844fc4fcf](https://linux-hardware.org/?probe=6844fc4fcf) | Nov 03, 2023 |
| HP            | ProBook 6450b               | Notebook    | [a63f28d2be](https://linux-hardware.org/?probe=a63f28d2be) | Nov 02, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [da5c3ffb7e](https://linux-hardware.org/?probe=da5c3ffb7e) | Nov 02, 2023 |
| Intel         | powered classmate PC        | Notebook    | [122f9662f5](https://linux-hardware.org/?probe=122f9662f5) | Nov 02, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [0f5f162498](https://linux-hardware.org/?probe=0f5f162498) | Nov 02, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [87ec116ea6](https://linux-hardware.org/?probe=87ec116ea6) | Nov 01, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [a09d649781](https://linux-hardware.org/?probe=a09d649781) | Nov 01, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [e27c813285](https://linux-hardware.org/?probe=e27c813285) | Oct 31, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [c0626d553b](https://linux-hardware.org/?probe=c0626d553b) | Oct 30, 2023 |
| Intel         | B75                         | Desktop     | [a46db29108](https://linux-hardware.org/?probe=a46db29108) | Oct 29, 2023 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [ac060a5eb6](https://linux-hardware.org/?probe=ac060a5eb6) | Oct 29, 2023 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [3cc0feaa4e](https://linux-hardware.org/?probe=3cc0feaa4e) | Oct 29, 2023 |
| Acer          | AOD270                      | Notebook    | [83c4a5920f](https://linux-hardware.org/?probe=83c4a5920f) | Oct 29, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [09d76f025a](https://linux-hardware.org/?probe=09d76f025a) | Oct 29, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [0c4d99e9dc](https://linux-hardware.org/?probe=0c4d99e9dc) | Oct 29, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [31d6b19c8d](https://linux-hardware.org/?probe=31d6b19c8d) | Oct 29, 2023 |
| Koloe         | X58                         | Desktop     | [91fbabe04c](https://linux-hardware.org/?probe=91fbabe04c) | Oct 29, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [39d06d7acf](https://linux-hardware.org/?probe=39d06d7acf) | Oct 28, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [7545369484](https://linux-hardware.org/?probe=7545369484) | Oct 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ecc6e8d906](https://linux-hardware.org/?probe=ecc6e8d906) | Oct 28, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [21beb00969](https://linux-hardware.org/?probe=21beb00969) | Oct 28, 2023 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [10bcfab3cb](https://linux-hardware.org/?probe=10bcfab3cb) | Oct 28, 2023 |
| ASUSTek       | X101                        | Notebook    | [dab1a6368d](https://linux-hardware.org/?probe=dab1a6368d) | Oct 27, 2023 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [5eaa7922e7](https://linux-hardware.org/?probe=5eaa7922e7) | Oct 27, 2023 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [80b6c027b0](https://linux-hardware.org/?probe=80b6c027b0) | Oct 27, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [9d662bd187](https://linux-hardware.org/?probe=9d662bd187) | Oct 27, 2023 |
| Dell          | Precision M6800             | Notebook    | [e8fd7cce51](https://linux-hardware.org/?probe=e8fd7cce51) | Oct 27, 2023 |
| Toshiba       | dynabook T350/56ARK         | Notebook    | [802dacc8cc](https://linux-hardware.org/?probe=802dacc8cc) | Oct 27, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [3a2901251b](https://linux-hardware.org/?probe=3a2901251b) | Oct 27, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [0a0a08dd5f](https://linux-hardware.org/?probe=0a0a08dd5f) | Oct 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [00e978bda2](https://linux-hardware.org/?probe=00e978bda2) | Oct 26, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [d3dacafdc2](https://linux-hardware.org/?probe=d3dacafdc2) | Oct 26, 2023 |
| HP            | 650                         | Notebook    | [0625bd022d](https://linux-hardware.org/?probe=0625bd022d) | Oct 26, 2023 |
| Dell          | 03NJH0 A01                  | Desktop     | [dbb152a219](https://linux-hardware.org/?probe=dbb152a219) | Oct 26, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [b62701c032](https://linux-hardware.org/?probe=b62701c032) | Oct 25, 2023 |
| Toshiba       | Satellite C670D-126         | Notebook    | [b117860daf](https://linux-hardware.org/?probe=b117860daf) | Oct 25, 2023 |
| NEC Comput... | PC-VJ22LFWZHSRF             | Notebook    | [b229c83a28](https://linux-hardware.org/?probe=b229c83a28) | Oct 25, 2023 |
| Lenovo        | ThinkCentre M90 5485W2L     | Desktop     | [0fcc4fe794](https://linux-hardware.org/?probe=0fcc4fe794) | Oct 24, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [50cab103c8](https://linux-hardware.org/?probe=50cab103c8) | Oct 24, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [b61468f9c5](https://linux-hardware.org/?probe=b61468f9c5) | Oct 24, 2023 |
| LG Electro... | 17ZT90P-G.AX33U1            | Notebook    | [0d53262cff](https://linux-hardware.org/?probe=0d53262cff) | Oct 23, 2023 |
| Lenovo        | 30C7 SDK0J40709 WIN 3259... | Desktop     | [71fd7dde1d](https://linux-hardware.org/?probe=71fd7dde1d) | Oct 23, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [35e54833e8](https://linux-hardware.org/?probe=35e54833e8) | Oct 23, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [6a62fa5cb6](https://linux-hardware.org/?probe=6a62fa5cb6) | Oct 23, 2023 |
| HP            | 3397                        | Desktop     | [3f8e8810c1](https://linux-hardware.org/?probe=3f8e8810c1) | Oct 23, 2023 |
| Toshiba       | Satellite P55W-C            | Notebook    | [60911595dc](https://linux-hardware.org/?probe=60911595dc) | Oct 23, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [d21c4ec9dd](https://linux-hardware.org/?probe=d21c4ec9dd) | Oct 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [3e46064143](https://linux-hardware.org/?probe=3e46064143) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| ASUSTek       | X550LA                      | Notebook    | [10e4a414fd](https://linux-hardware.org/?probe=10e4a414fd) | Oct 22, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [ad7ca8e192](https://linux-hardware.org/?probe=ad7ca8e192) | Oct 21, 2023 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [859edb18bd](https://linux-hardware.org/?probe=859edb18bd) | Oct 21, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [ff0d8bbab4](https://linux-hardware.org/?probe=ff0d8bbab4) | Oct 21, 2023 |
| HP            | TouchSmart tm2              | Notebook    | [a79b82edd3](https://linux-hardware.org/?probe=a79b82edd3) | Oct 21, 2023 |
| Compaq        | 434                         | Notebook    | [094bba21f8](https://linux-hardware.org/?probe=094bba21f8) | Oct 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [314c39b6d1](https://linux-hardware.org/?probe=314c39b6d1) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [1ff62f5fd7](https://linux-hardware.org/?probe=1ff62f5fd7) | Oct 21, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [b5bf9b7639](https://linux-hardware.org/?probe=b5bf9b7639) | Oct 21, 2023 |
| Samsung       | R530/R730/P590              | Notebook    | [6a774fbae7](https://linux-hardware.org/?probe=6a774fbae7) | Oct 21, 2023 |
| Lenovo        | ThinkPad X201 3680V5T       | Notebook    | [b30e261022](https://linux-hardware.org/?probe=b30e261022) | Oct 20, 2023 |
| MSI           | G41TM-P31                   | Desktop     | [3ed69770a6](https://linux-hardware.org/?probe=3ed69770a6) | Oct 20, 2023 |
| Lenovo        | ThinkPad L540 20AUA044FR    | Notebook    | [70d42f0667](https://linux-hardware.org/?probe=70d42f0667) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | Notebook    | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [71bfa98c37](https://linux-hardware.org/?probe=71bfa98c37) | Oct 20, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [34ffce7f83](https://linux-hardware.org/?probe=34ffce7f83) | Oct 20, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [2593407253](https://linux-hardware.org/?probe=2593407253) | Oct 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3fd9b0b53f](https://linux-hardware.org/?probe=3fd9b0b53f) | Oct 20, 2023 |
| Toshiba       | Satellite P50t-B-118        | Notebook    | [5237c0866e](https://linux-hardware.org/?probe=5237c0866e) | Oct 19, 2023 |
| Acer          | AOD270                      | Notebook    | [b8c4966af7](https://linux-hardware.org/?probe=b8c4966af7) | Oct 19, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [aa95d1c178](https://linux-hardware.org/?probe=aa95d1c178) | Oct 19, 2023 |
| HP            | TouchSmart tm2              | Notebook    | [f72f6a43b5](https://linux-hardware.org/?probe=f72f6a43b5) | Oct 19, 2023 |
| Intel         | DH55HC AAE70933-505         | Desktop     | [f1bc373847](https://linux-hardware.org/?probe=f1bc373847) | Oct 19, 2023 |
| ASUSTek       | X542UR                      | Notebook    | [72390695fd](https://linux-hardware.org/?probe=72390695fd) | Oct 19, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [a0c126c4ce](https://linux-hardware.org/?probe=a0c126c4ce) | Oct 19, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [0994d6d9a2](https://linux-hardware.org/?probe=0994d6d9a2) | Oct 18, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [04e9833b48](https://linux-hardware.org/?probe=04e9833b48) | Oct 18, 2023 |
| Dell          | Latitude E6320              | Notebook    | [91e5128fd5](https://linux-hardware.org/?probe=91e5128fd5) | Oct 18, 2023 |
| Chuwi         | M01ALWR310-ADA90B           | Mini pc     | [4dbcbacf46](https://linux-hardware.org/?probe=4dbcbacf46) | Oct 18, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Notebook    | [7e446027c0](https://linux-hardware.org/?probe=7e446027c0) | Oct 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [7b5cf8abfc](https://linux-hardware.org/?probe=7b5cf8abfc) | Oct 17, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [f3bd5c6632](https://linux-hardware.org/?probe=f3bd5c6632) | Oct 17, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [cf920dcf20](https://linux-hardware.org/?probe=cf920dcf20) | Oct 17, 2023 |
| Acer          | Veriton X2660G              | Desktop     | [d122988e18](https://linux-hardware.org/?probe=d122988e18) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9f9777f778](https://linux-hardware.org/?probe=9f9777f778) | Oct 17, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [9258f94300](https://linux-hardware.org/?probe=9258f94300) | Oct 17, 2023 |
| HP            | Folio 13 - 2000             | Notebook    | [c541a1603c](https://linux-hardware.org/?probe=c541a1603c) | Oct 17, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [3d62b547f3](https://linux-hardware.org/?probe=3d62b547f3) | Oct 16, 2023 |
| HP            | 630                         | Notebook    | [db6efff83b](https://linux-hardware.org/?probe=db6efff83b) | Oct 16, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [8522bfdadd](https://linux-hardware.org/?probe=8522bfdadd) | Oct 16, 2023 |
| MSI           | Z97A GAMING 7               | Desktop     | [8af7152ba5](https://linux-hardware.org/?probe=8af7152ba5) | Oct 16, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [b1a36d42aa](https://linux-hardware.org/?probe=b1a36d42aa) | Oct 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0c6b7d2953](https://linux-hardware.org/?probe=0c6b7d2953) | Oct 16, 2023 |
| Sony          | VPCEF2S1E                   | Notebook    | [e4be1dd0e0](https://linux-hardware.org/?probe=e4be1dd0e0) | Oct 16, 2023 |
| Gigabyte      | GA-E350N-USB3               | Desktop     | [62f5ab12ea](https://linux-hardware.org/?probe=62f5ab12ea) | Oct 15, 2023 |
| Gigabyte      | GA-78LMT-S2 R2              | Desktop     | [038f59eb24](https://linux-hardware.org/?probe=038f59eb24) | Oct 15, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [64738e1724](https://linux-hardware.org/?probe=64738e1724) | Oct 15, 2023 |
| Intel         | D945GTP AAC97837-309        | Other       | [49d064bc5d](https://linux-hardware.org/?probe=49d064bc5d) | Oct 15, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [579dc4dabc](https://linux-hardware.org/?probe=579dc4dabc) | Oct 15, 2023 |
| PCWare        | IPMH61R1                    | Desktop     | [145dc39d14](https://linux-hardware.org/?probe=145dc39d14) | Oct 14, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [ed4ca29c66](https://linux-hardware.org/?probe=ed4ca29c66) | Oct 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [babe25d4ce](https://linux-hardware.org/?probe=babe25d4ce) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 64757D7       | Notebook    | [b374e214af](https://linux-hardware.org/?probe=b374e214af) | Oct 13, 2023 |
| HP            | 1495                        | Desktop     | [e524318d58](https://linux-hardware.org/?probe=e524318d58) | Oct 13, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f5e57e4558](https://linux-hardware.org/?probe=f5e57e4558) | Oct 13, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [04b09d7164](https://linux-hardware.org/?probe=04b09d7164) | Oct 12, 2023 |
| HP            | 14                          | Notebook    | [e207fce0d4](https://linux-hardware.org/?probe=e207fce0d4) | Oct 12, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [29bb46e198](https://linux-hardware.org/?probe=29bb46e198) | Oct 12, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [cfcd99cc4f](https://linux-hardware.org/?probe=cfcd99cc4f) | Oct 10, 2023 |
| Dell          | Latitude E6440              | Notebook    | [7471faa299](https://linux-hardware.org/?probe=7471faa299) | Oct 10, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Medion        | E11201                      | Notebook    | [25afe8c1be](https://linux-hardware.org/?probe=25afe8c1be) | Oct 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | Desktop     | [3e075f72d8](https://linux-hardware.org/?probe=3e075f72d8) | Oct 09, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [a3401cc125](https://linux-hardware.org/?probe=a3401cc125) | Oct 09, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [c237b78f41](https://linux-hardware.org/?probe=c237b78f41) | Oct 08, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [fa47449843](https://linux-hardware.org/?probe=fa47449843) | Oct 08, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [c6da0d1963](https://linux-hardware.org/?probe=c6da0d1963) | Oct 08, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [ac5943ef0c](https://linux-hardware.org/?probe=ac5943ef0c) | Oct 08, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3EJ0... | Notebook    | [f39067b962](https://linux-hardware.org/?probe=f39067b962) | Oct 07, 2023 |
| Fujitsu       | D2619 S26361-D2619-N15 W... | Server      | [f7382028bb](https://linux-hardware.org/?probe=f7382028bb) | Oct 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [0bf2deeb16](https://linux-hardware.org/?probe=0bf2deeb16) | Oct 07, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [30d2522c95](https://linux-hardware.org/?probe=30d2522c95) | Oct 07, 2023 |
| Intel         | H61                         | Desktop     | [a37805d0d3](https://linux-hardware.org/?probe=a37805d0d3) | Oct 07, 2023 |
| ASRock        | N68C-GS FX                  | Desktop     | [cfafd2008d](https://linux-hardware.org/?probe=cfafd2008d) | Oct 07, 2023 |
| MSI           | 09AC                        | Desktop     | [f70ac0139f](https://linux-hardware.org/?probe=f70ac0139f) | Oct 07, 2023 |
| AZW           | Green G4 10                 | Desktop     | [d8fb758dec](https://linux-hardware.org/?probe=d8fb758dec) | Oct 07, 2023 |
| MACHINIST     | E5-MR9A PRO V1.2            | Desktop     | [668d09e797](https://linux-hardware.org/?probe=668d09e797) | Oct 07, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [205a84adc9](https://linux-hardware.org/?probe=205a84adc9) | Oct 07, 2023 |
| Lenovo        | ThinkCentre xxx 7090A17     | Desktop     | [669bc2a016](https://linux-hardware.org/?probe=669bc2a016) | Oct 06, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| Thomson       | WWN15I5-8BK1T               | Notebook    | [10ca155743](https://linux-hardware.org/?probe=10ca155743) | Oct 06, 2023 |
| HP            | Laptop 15s-fq3xxx           | Notebook    | [3cbdc1eb94](https://linux-hardware.org/?probe=3cbdc1eb94) | Oct 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [bc448fbb82](https://linux-hardware.org/?probe=bc448fbb82) | Oct 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [6e8b2e49f0](https://linux-hardware.org/?probe=6e8b2e49f0) | Oct 05, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [1729f3bfbe](https://linux-hardware.org/?probe=1729f3bfbe) | Oct 05, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [0ef9b0be54](https://linux-hardware.org/?probe=0ef9b0be54) | Oct 05, 2023 |
| Lenovo        | B50-80 80LT                 | Notebook    | [74b54d0f3f](https://linux-hardware.org/?probe=74b54d0f3f) | Oct 05, 2023 |
| HP            | 3397                        | Desktop     | [e77e1b6391](https://linux-hardware.org/?probe=e77e1b6391) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a72a2ee89e](https://linux-hardware.org/?probe=a72a2ee89e) | Oct 04, 2023 |
| HP            | 1825                        | Desktop     | [d326bc59ff](https://linux-hardware.org/?probe=d326bc59ff) | Oct 04, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [51ec04551f](https://linux-hardware.org/?probe=51ec04551f) | Oct 04, 2023 |
| Lenovo        | NOK                         | Desktop     | [dd6bffed79](https://linux-hardware.org/?probe=dd6bffed79) | Oct 04, 2023 |
| Dell          | Latitude E6410              | Notebook    | [0b58de80dd](https://linux-hardware.org/?probe=0b58de80dd) | Oct 04, 2023 |
| HP            | 3646h                       | Desktop     | [f39e9c8741](https://linux-hardware.org/?probe=f39e9c8741) | Oct 04, 2023 |
| Intel         | JSL MRD                     | Desktop     | [5a4bfcaba3](https://linux-hardware.org/?probe=5a4bfcaba3) | Oct 03, 2023 |
| MSI           | CR620                       | Notebook    | [be490381a9](https://linux-hardware.org/?probe=be490381a9) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3657d65cec](https://linux-hardware.org/?probe=3657d65cec) | Oct 03, 2023 |
| Intel         | DG41RQ AAE54511-202         | Desktop     | [5d2ec27525](https://linux-hardware.org/?probe=5d2ec27525) | Oct 03, 2023 |
| Dell          | 0Y3R3K A03                  | Desktop     | [0675277f70](https://linux-hardware.org/?probe=0675277f70) | Oct 03, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [fe83d524fb](https://linux-hardware.org/?probe=fe83d524fb) | Oct 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [25d2225829](https://linux-hardware.org/?probe=25d2225829) | Oct 02, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [fcef55efdf](https://linux-hardware.org/?probe=fcef55efdf) | Oct 01, 2023 |
| Toshiba       | Satellite L775              | Notebook    | [c659fe6fba](https://linux-hardware.org/?probe=c659fe6fba) | Oct 01, 2023 |
| AZW           | MINI S 10                   | Desktop     | [13e3a733fd](https://linux-hardware.org/?probe=13e3a733fd) | Oct 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [def4633785](https://linux-hardware.org/?probe=def4633785) | Oct 01, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [0166816d1b](https://linux-hardware.org/?probe=0166816d1b) | Oct 01, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [b8aadf6823](https://linux-hardware.org/?probe=b8aadf6823) | Sep 30, 2023 |
| ASUSTek       | P5B-E Plus                  | Desktop     | [78c413cac5](https://linux-hardware.org/?probe=78c413cac5) | Sep 30, 2023 |
| Acer          | Aspire 5560                 | Notebook    | [252d19e4f5](https://linux-hardware.org/?probe=252d19e4f5) | Sep 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [e065b9c701](https://linux-hardware.org/?probe=e065b9c701) | Sep 30, 2023 |
| Toshiba       | Satellite C845D             | Notebook    | [92651c9e51](https://linux-hardware.org/?probe=92651c9e51) | Sep 30, 2023 |
| Lenovo        | 300s-15ARR 81FB             | Notebook    | [4f7e627fd2](https://linux-hardware.org/?probe=4f7e627fd2) | Sep 30, 2023 |
| SKIKK         | Sindri 14                   | Notebook    | [9766c80aa9](https://linux-hardware.org/?probe=9766c80aa9) | Sep 29, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [d0fea1d86b](https://linux-hardware.org/?probe=d0fea1d86b) | Sep 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [b7faf1054b](https://linux-hardware.org/?probe=b7faf1054b) | Sep 29, 2023 |
| Intel         | H110D4-P1                   | Desktop     | [ccedaaab02](https://linux-hardware.org/?probe=ccedaaab02) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [902918fb1d](https://linux-hardware.org/?probe=902918fb1d) | Sep 29, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [e9d026d0df](https://linux-hardware.org/?probe=e9d026d0df) | Sep 29, 2023 |
| Lenovo        | H410                        | Desktop     | [f49a6ce32f](https://linux-hardware.org/?probe=f49a6ce32f) | Sep 28, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [2a5937c5e5](https://linux-hardware.org/?probe=2a5937c5e5) | Sep 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [a1ef1eb6e6](https://linux-hardware.org/?probe=a1ef1eb6e6) | Sep 28, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [85548f2790](https://linux-hardware.org/?probe=85548f2790) | Sep 28, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [9c4b30a15c](https://linux-hardware.org/?probe=9c4b30a15c) | Sep 27, 2023 |
| ASUSTek       | D700MD                      | Desktop     | [91740e63b9](https://linux-hardware.org/?probe=91740e63b9) | Sep 27, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [ee4b3f2b76](https://linux-hardware.org/?probe=ee4b3f2b76) | Sep 26, 2023 |
| LG Electro... | 13U70Q-G.AA75B              | Notebook    | [f38b79055b](https://linux-hardware.org/?probe=f38b79055b) | Sep 26, 2023 |
| Samsung       | R519/R719                   | Notebook    | [15ae7c9603](https://linux-hardware.org/?probe=15ae7c9603) | Sep 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0RN1S    | Notebook    | [598d621f0d](https://linux-hardware.org/?probe=598d621f0d) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [897f671915](https://linux-hardware.org/?probe=897f671915) | Sep 25, 2023 |
| Toshiba       | dynabook Satellite B350/... | Notebook    | [2b241af774](https://linux-hardware.org/?probe=2b241af774) | Sep 25, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [a2f6814940](https://linux-hardware.org/?probe=a2f6814940) | Sep 25, 2023 |
| Pegatron      | EVANS                       | Desktop     | [b9347254b0](https://linux-hardware.org/?probe=b9347254b0) | Sep 25, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [1939307392](https://linux-hardware.org/?probe=1939307392) | Sep 25, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [6d6d719f30](https://linux-hardware.org/?probe=6d6d719f30) | Sep 25, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [5cfbe2e7e0](https://linux-hardware.org/?probe=5cfbe2e7e0) | Sep 24, 2023 |
| Biostar       | B550MH                      | Desktop     | [4ef9bbad17](https://linux-hardware.org/?probe=4ef9bbad17) | Sep 24, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [e998b320d8](https://linux-hardware.org/?probe=e998b320d8) | Sep 24, 2023 |
| Gigabyte      | X299 AORUS Gaming-CF        | Desktop     | [4c6071b20c](https://linux-hardware.org/?probe=4c6071b20c) | Sep 24, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [c0e3bef058](https://linux-hardware.org/?probe=c0e3bef058) | Sep 24, 2023 |
| ASUSTek       | Z97-C                       | Desktop     | [e4c1f075b9](https://linux-hardware.org/?probe=e4c1f075b9) | Sep 23, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [c2cb8052f9](https://linux-hardware.org/?probe=c2cb8052f9) | Sep 23, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [46a99bb50a](https://linux-hardware.org/?probe=46a99bb50a) | Sep 23, 2023 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [92e5dde8b3](https://linux-hardware.org/?probe=92e5dde8b3) | Sep 23, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [c86094eac8](https://linux-hardware.org/?probe=c86094eac8) | Sep 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [13a9f1d65a](https://linux-hardware.org/?probe=13a9f1d65a) | Sep 23, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [7e03b87e4b](https://linux-hardware.org/?probe=7e03b87e4b) | Sep 23, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [be4a46768b](https://linux-hardware.org/?probe=be4a46768b) | Sep 23, 2023 |
| Shuttle       | XS36V                       | Desktop     | [dbcb5658e4](https://linux-hardware.org/?probe=dbcb5658e4) | Sep 23, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9ea546d36c](https://linux-hardware.org/?probe=9ea546d36c) | Sep 22, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [2676f29c41](https://linux-hardware.org/?probe=2676f29c41) | Sep 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [f5b912e122](https://linux-hardware.org/?probe=f5b912e122) | Sep 22, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ce0f2babca](https://linux-hardware.org/?probe=ce0f2babca) | Sep 22, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [57c3bb43f5](https://linux-hardware.org/?probe=57c3bb43f5) | Sep 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c5833405a5](https://linux-hardware.org/?probe=c5833405a5) | Sep 22, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| Lenovo        | ThinkPad X220 4286BB2       | Notebook    | [a3b217a707](https://linux-hardware.org/?probe=a3b217a707) | Sep 21, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [2e2072e3ca](https://linux-hardware.org/?probe=2e2072e3ca) | Sep 21, 2023 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | Desktop     | [d3c9063140](https://linux-hardware.org/?probe=d3c9063140) | Sep 21, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [61ae2b85c5](https://linux-hardware.org/?probe=61ae2b85c5) | Sep 21, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [182384fdaa](https://linux-hardware.org/?probe=182384fdaa) | Sep 20, 2023 |
| MSI           | Indio                       | Desktop     | [330a2c9640](https://linux-hardware.org/?probe=330a2c9640) | Sep 20, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [8eacbd2f7a](https://linux-hardware.org/?probe=8eacbd2f7a) | Sep 19, 2023 |
| Biostar       | B550GTQ                     | Desktop     | [5478c7bc91](https://linux-hardware.org/?probe=5478c7bc91) | Sep 19, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [32f2e74fe3](https://linux-hardware.org/?probe=32f2e74fe3) | Sep 19, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [6f4fafb23f](https://linux-hardware.org/?probe=6f4fafb23f) | Sep 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f40bb3790e](https://linux-hardware.org/?probe=f40bb3790e) | Sep 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [0a5f29963e](https://linux-hardware.org/?probe=0a5f29963e) | Sep 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7b51f6f455](https://linux-hardware.org/?probe=7b51f6f455) | Sep 18, 2023 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [ab79a26993](https://linux-hardware.org/?probe=ab79a26993) | Sep 18, 2023 |
| HP            | Notebook                    | Notebook    | [0c80a5c83f](https://linux-hardware.org/?probe=0c80a5c83f) | Sep 18, 2023 |
| MSI           | Modern 14 C11M              | Notebook    | [4c6156df05](https://linux-hardware.org/?probe=4c6156df05) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cad09f007e](https://linux-hardware.org/?probe=cad09f007e) | Sep 18, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9c94944d56](https://linux-hardware.org/?probe=9c94944d56) | Sep 18, 2023 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [232bd09926](https://linux-hardware.org/?probe=232bd09926) | Sep 17, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [beaa4e5554](https://linux-hardware.org/?probe=beaa4e5554) | Sep 17, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | Notebook    | [20d35c7482](https://linux-hardware.org/?probe=20d35c7482) | Sep 17, 2023 |
| Notebook      | NP5x_6x_7x_SNx              | Notebook    | [83be57b9aa](https://linux-hardware.org/?probe=83be57b9aa) | Sep 17, 2023 |
| Dell          | System XPS L502X            | Notebook    | [d3154f94d7](https://linux-hardware.org/?probe=d3154f94d7) | Sep 17, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [cd0090bea7](https://linux-hardware.org/?probe=cd0090bea7) | Sep 16, 2023 |
| Intel         | DX79SI AAG28808-602         | Desktop     | [2ccc7fc308](https://linux-hardware.org/?probe=2ccc7fc308) | Sep 16, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [513b6982f2](https://linux-hardware.org/?probe=513b6982f2) | Sep 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bef465f035](https://linux-hardware.org/?probe=bef465f035) | Sep 16, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [e28e555058](https://linux-hardware.org/?probe=e28e555058) | Sep 16, 2023 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [cb32849dcc](https://linux-hardware.org/?probe=cb32849dcc) | Sep 16, 2023 |
| HP            | 339A                        | Desktop     | [5808e19d94](https://linux-hardware.org/?probe=5808e19d94) | Sep 15, 2023 |
| Gigabyte      | P35-DS3                     | Desktop     | [7cf209e4c1](https://linux-hardware.org/?probe=7cf209e4c1) | Sep 15, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [dd369f3c60](https://linux-hardware.org/?probe=dd369f3c60) | Sep 15, 2023 |
| Dell          | 073MMW A03                  | Desktop     | [b0fc15849b](https://linux-hardware.org/?probe=b0fc15849b) | Sep 15, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [9b3fc9218b](https://linux-hardware.org/?probe=9b3fc9218b) | Sep 14, 2023 |
| Intel         | H81                         | Desktop     | [34f1a336e3](https://linux-hardware.org/?probe=34f1a336e3) | Sep 14, 2023 |
| Gigabyte      | Z97X-SOC-CF                 | Desktop     | [9c86fc8235](https://linux-hardware.org/?probe=9c86fc8235) | Sep 14, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [3959de124c](https://linux-hardware.org/?probe=3959de124c) | Sep 14, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [33b3749fc5](https://linux-hardware.org/?probe=33b3749fc5) | Sep 14, 2023 |
| ASUSTek       | NAGAMI2                     | Desktop     | [c0e4ce344f](https://linux-hardware.org/?probe=c0e4ce344f) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| MSI           | B85M-E45                    | Desktop     | [d454b67226](https://linux-hardware.org/?probe=d454b67226) | Sep 13, 2023 |
| HP            | Notebook                    | Notebook    | [1f0357e569](https://linux-hardware.org/?probe=1f0357e569) | Sep 13, 2023 |
| Packard Be... | MCP73                       | Desktop     | [b47efcac04](https://linux-hardware.org/?probe=b47efcac04) | Sep 13, 2023 |
| HP            | 339A                        | Desktop     | [1b8a467d98](https://linux-hardware.org/?probe=1b8a467d98) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [1b8a46fc57](https://linux-hardware.org/?probe=1b8a46fc57) | Sep 13, 2023 |
| HP            | 829A                        | Mini pc     | [204c5a2a04](https://linux-hardware.org/?probe=204c5a2a04) | Sep 13, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [3b15d88a26](https://linux-hardware.org/?probe=3b15d88a26) | Sep 13, 2023 |
| MSI           | A88XM GAMING                | Desktop     | [0b0a88f781](https://linux-hardware.org/?probe=0b0a88f781) | Sep 13, 2023 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [caef8df1be](https://linux-hardware.org/?probe=caef8df1be) | Sep 12, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [2b7e16f244](https://linux-hardware.org/?probe=2b7e16f244) | Sep 12, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [49cc8ea6d2](https://linux-hardware.org/?probe=49cc8ea6d2) | Sep 12, 2023 |
| MSI           | B450M PRO-VDH               | Desktop     | [c06182cc86](https://linux-hardware.org/?probe=c06182cc86) | Sep 12, 2023 |
| Intel         | H61                         | Desktop     | [fec08a2214](https://linux-hardware.org/?probe=fec08a2214) | Sep 12, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [c687b18168](https://linux-hardware.org/?probe=c687b18168) | Sep 12, 2023 |
| Dell          | Latitude E4200              | Notebook    | [ab13ebe930](https://linux-hardware.org/?probe=ab13ebe930) | Sep 12, 2023 |
| Dell          | 0G254H A00                  | Desktop     | [b41d69b7e2](https://linux-hardware.org/?probe=b41d69b7e2) | Sep 12, 2023 |
| HP            | 82A1                        | Desktop     | [8a68160c22](https://linux-hardware.org/?probe=8a68160c22) | Sep 12, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [a7fca90eab](https://linux-hardware.org/?probe=a7fca90eab) | Sep 12, 2023 |
| Dell          | 0G3HR7 A00                  | Desktop     | [ae2dfec1af](https://linux-hardware.org/?probe=ae2dfec1af) | Sep 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c32a84014](https://linux-hardware.org/?probe=7c32a84014) | Sep 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [ecdef7173c](https://linux-hardware.org/?probe=ecdef7173c) | Sep 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [b360f71c3d](https://linux-hardware.org/?probe=b360f71c3d) | Sep 11, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [9c4e42b171](https://linux-hardware.org/?probe=9c4e42b171) | Sep 11, 2023 |
| HP            | 304Ah                       | Desktop     | [fe71b825fd](https://linux-hardware.org/?probe=fe71b825fd) | Sep 11, 2023 |
| Intel         | H81 V2.3                    | Desktop     | [0673e1f5ed](https://linux-hardware.org/?probe=0673e1f5ed) | Sep 11, 2023 |
| LIVEFAN       | Unknown                     | Notebook    | [102a13c2c5](https://linux-hardware.org/?probe=102a13c2c5) | Sep 11, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d4474d69](https://linux-hardware.org/?probe=d7d4474d69) | Sep 11, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7813372525](https://linux-hardware.org/?probe=7813372525) | Sep 11, 2023 |
| Dell          | 088DT1 A00                  | Desktop     | [08eff7732c](https://linux-hardware.org/?probe=08eff7732c) | Sep 11, 2023 |
| Philco        | DTC-A55                     | Desktop     | [30cdd25bb0](https://linux-hardware.org/?probe=30cdd25bb0) | Sep 11, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [962fd46c5c](https://linux-hardware.org/?probe=962fd46c5c) | Sep 11, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [2c892b26d1](https://linux-hardware.org/?probe=2c892b26d1) | Sep 11, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [9f1aed2560](https://linux-hardware.org/?probe=9f1aed2560) | Sep 10, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [4f0a6ec78c](https://linux-hardware.org/?probe=4f0a6ec78c) | Sep 10, 2023 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [83ff674ae7](https://linux-hardware.org/?probe=83ff674ae7) | Sep 10, 2023 |
| Daten Tecn... | DA75PRO                     | Desktop     | [343cbab6e9](https://linux-hardware.org/?probe=343cbab6e9) | Sep 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [923e3060e8](https://linux-hardware.org/?probe=923e3060e8) | Sep 10, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [c5be1f9523](https://linux-hardware.org/?probe=c5be1f9523) | Sep 10, 2023 |
| Dell          | Inspiron 11-3162            | Notebook    | [600d8479fe](https://linux-hardware.org/?probe=600d8479fe) | Sep 10, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [91b6565880](https://linux-hardware.org/?probe=91b6565880) | Sep 09, 2023 |
| HP            | 8266                        | Desktop     | [fed6cc89fe](https://linux-hardware.org/?probe=fed6cc89fe) | Sep 09, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [f7eae2e7c4](https://linux-hardware.org/?probe=f7eae2e7c4) | Sep 09, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [1a943fda98](https://linux-hardware.org/?probe=1a943fda98) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [8723b09478](https://linux-hardware.org/?probe=8723b09478) | Sep 09, 2023 |
| ASUSTek       | P10S-C Series               | Desktop     | [67829cd702](https://linux-hardware.org/?probe=67829cd702) | Sep 09, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c320e0c618](https://linux-hardware.org/?probe=c320e0c618) | Sep 09, 2023 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [dc4bc20437](https://linux-hardware.org/?probe=dc4bc20437) | Sep 09, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [75c6651a69](https://linux-hardware.org/?probe=75c6651a69) | Sep 09, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [b16e6f8c25](https://linux-hardware.org/?probe=b16e6f8c25) | Sep 08, 2023 |
| Chuwi         | UBook XPro                  | Convertible | [a4724d44e8](https://linux-hardware.org/?probe=a4724d44e8) | Sep 08, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [e64c5d24b0](https://linux-hardware.org/?probe=e64c5d24b0) | Sep 08, 2023 |
| Dell          | 0J37VM A01                  | Desktop     | [cfd16871a7](https://linux-hardware.org/?probe=cfd16871a7) | Sep 08, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [d98be8d71c](https://linux-hardware.org/?probe=d98be8d71c) | Sep 08, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c06ee9858a](https://linux-hardware.org/?probe=c06ee9858a) | Sep 08, 2023 |
| Intel         | H81                         | Desktop     | [52fa5b7a15](https://linux-hardware.org/?probe=52fa5b7a15) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ecef237a9c](https://linux-hardware.org/?probe=ecef237a9c) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7a0e6bd16c](https://linux-hardware.org/?probe=7a0e6bd16c) | Sep 07, 2023 |
| Medion        | H110H4-CM2                  | Desktop     | [184f133a7d](https://linux-hardware.org/?probe=184f133a7d) | Sep 07, 2023 |
| ASRock        | H310CM-HDV                  | Desktop     | [7aa11cd98f](https://linux-hardware.org/?probe=7aa11cd98f) | Sep 07, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bdd695dc3](https://linux-hardware.org/?probe=7bdd695dc3) | Sep 07, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [8274cbca33](https://linux-hardware.org/?probe=8274cbca33) | Sep 07, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [78ecb1b882](https://linux-hardware.org/?probe=78ecb1b882) | Sep 07, 2023 |
| Gigabyte      | H610M S2 V2 DDR4            | Desktop     | [7323821425](https://linux-hardware.org/?probe=7323821425) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1bc029ed5e](https://linux-hardware.org/?probe=1bc029ed5e) | Sep 07, 2023 |
| Dell          | Latitude 5480               | Notebook    | [166d57f310](https://linux-hardware.org/?probe=166d57f310) | Sep 07, 2023 |
| Google        | Blooguard                   | Notebook    | [c9dec98f0f](https://linux-hardware.org/?probe=c9dec98f0f) | Sep 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5254176a5a](https://linux-hardware.org/?probe=5254176a5a) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [498958a11d](https://linux-hardware.org/?probe=498958a11d) | Sep 07, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [96d3b5db5c](https://linux-hardware.org/?probe=96d3b5db5c) | Sep 07, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [f98e7f20ca](https://linux-hardware.org/?probe=f98e7f20ca) | Sep 06, 2023 |
| Clevo         | M1100M                      | Notebook    | [399b796d9f](https://linux-hardware.org/?probe=399b796d9f) | Sep 06, 2023 |
| Acer          | Swift SF314-51              | Notebook    | [7e7c32364d](https://linux-hardware.org/?probe=7e7c32364d) | Sep 06, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [507d1bd39c](https://linux-hardware.org/?probe=507d1bd39c) | Sep 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [a738df6114](https://linux-hardware.org/?probe=a738df6114) | Sep 06, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [774ca51623](https://linux-hardware.org/?probe=774ca51623) | Sep 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [03e260aff4](https://linux-hardware.org/?probe=03e260aff4) | Sep 06, 2023 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [9e650e7107](https://linux-hardware.org/?probe=9e650e7107) | Sep 06, 2023 |
| Lenovo        | IdeaCentre K330B            | Desktop     | [a53977eb83](https://linux-hardware.org/?probe=a53977eb83) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | Desktop     | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [3f1c2a5cfa](https://linux-hardware.org/?probe=3f1c2a5cfa) | Sep 06, 2023 |
| Dell          | 0RN4PJ A01                  | Server      | [342dfcbde0](https://linux-hardware.org/?probe=342dfcbde0) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [4e04252ac1](https://linux-hardware.org/?probe=4e04252ac1) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | Notebook    | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| Dell          | 0CU409                      | Desktop     | [f5ae8200cf](https://linux-hardware.org/?probe=f5ae8200cf) | Sep 06, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [783815f79f](https://linux-hardware.org/?probe=783815f79f) | Sep 06, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [10bb2b77f8](https://linux-hardware.org/?probe=10bb2b77f8) | Sep 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [07f51e668b](https://linux-hardware.org/?probe=07f51e668b) | Sep 06, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [afba6fc1eb](https://linux-hardware.org/?probe=afba6fc1eb) | Sep 06, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [dd18138503](https://linux-hardware.org/?probe=dd18138503) | Sep 06, 2023 |
| Purism        | Librem 15 v3                | Notebook    | [d3a66abc8b](https://linux-hardware.org/?probe=d3a66abc8b) | Sep 05, 2023 |
| HP            | 0B54h D                     | Desktop     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS3L502    | Notebook    | [cb8de94658](https://linux-hardware.org/?probe=cb8de94658) | Sep 05, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [ed90b83cc0](https://linux-hardware.org/?probe=ed90b83cc0) | Sep 05, 2023 |
| MSI           | H270 GAMING M3              | Desktop     | [1c93682de6](https://linux-hardware.org/?probe=1c93682de6) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Intel         | H61                         | Desktop     | [d749d1595f](https://linux-hardware.org/?probe=d749d1595f) | Sep 05, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [344c861540](https://linux-hardware.org/?probe=344c861540) | Sep 05, 2023 |
| Acer          | Aspire V3-572P              | Notebook    | [1b021435e8](https://linux-hardware.org/?probe=1b021435e8) | Sep 05, 2023 |
| Dell          | Inspiron 3482               | Notebook    | [078746577b](https://linux-hardware.org/?probe=078746577b) | Sep 05, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [97ac9f9de8](https://linux-hardware.org/?probe=97ac9f9de8) | Sep 05, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [97e43e20d7](https://linux-hardware.org/?probe=97e43e20d7) | Sep 05, 2023 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [a66c2d8e50](https://linux-hardware.org/?probe=a66c2d8e50) | Sep 05, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [25b4eff820](https://linux-hardware.org/?probe=25b4eff820) | Sep 05, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [0b87bf5b4b](https://linux-hardware.org/?probe=0b87bf5b4b) | Sep 05, 2023 |
| ASRock        | E35LM1                      | Desktop     | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [59b9a21678](https://linux-hardware.org/?probe=59b9a21678) | Sep 04, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [46627e6392](https://linux-hardware.org/?probe=46627e6392) | Sep 04, 2023 |
| ASUSTek       | P5P43TD/USB3                | Desktop     | [619032e1d0](https://linux-hardware.org/?probe=619032e1d0) | Sep 04, 2023 |
| Dell          | 0J8G6F A03                  | Desktop     | [490dd7a710](https://linux-hardware.org/?probe=490dd7a710) | Sep 04, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [2380eeae30](https://linux-hardware.org/?probe=2380eeae30) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| Dell          | Vostro 5590                 | Notebook    | [24ee101fee](https://linux-hardware.org/?probe=24ee101fee) | Sep 04, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [7c39e7227e](https://linux-hardware.org/?probe=7c39e7227e) | Sep 04, 2023 |
| HUAWEI        | MateBook HZ-W09             | Tablet      | [1e12adec6b](https://linux-hardware.org/?probe=1e12adec6b) | Sep 04, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d8efe50ca5](https://linux-hardware.org/?probe=d8efe50ca5) | Sep 04, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [7c149b5f95](https://linux-hardware.org/?probe=7c149b5f95) | Sep 04, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | Desktop     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [b3e23f1718](https://linux-hardware.org/?probe=b3e23f1718) | Sep 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [46aeab1365](https://linux-hardware.org/?probe=46aeab1365) | Sep 04, 2023 |
| OEM           | Intel H81                   | Desktop     | [649a092684](https://linux-hardware.org/?probe=649a092684) | Sep 04, 2023 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [c3059a2ebc](https://linux-hardware.org/?probe=c3059a2ebc) | Sep 04, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [2ba34b459a](https://linux-hardware.org/?probe=2ba34b459a) | Sep 04, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [85cc15f8ea](https://linux-hardware.org/?probe=85cc15f8ea) | Sep 04, 2023 |
| Gigabyte      | GB-BKi3A-7100               | Notebook    | [40c832efb9](https://linux-hardware.org/?probe=40c832efb9) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [02160fded0](https://linux-hardware.org/?probe=02160fded0) | Sep 04, 2023 |
| ASUSTek       | X75A1                       | Notebook    | [d8be6d6952](https://linux-hardware.org/?probe=d8be6d6952) | Sep 04, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [9918661e50](https://linux-hardware.org/?probe=9918661e50) | Sep 04, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| HP            | 829E                        | Mini pc     | [205ab47a36](https://linux-hardware.org/?probe=205ab47a36) | Sep 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ee6914ebdf](https://linux-hardware.org/?probe=ee6914ebdf) | Sep 04, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [08a80ee482](https://linux-hardware.org/?probe=08a80ee482) | Sep 04, 2023 |
| ASUSTek       | N56JN                       | Notebook    | [eb9458de08](https://linux-hardware.org/?probe=eb9458de08) | Sep 04, 2023 |
| Sony          | VPCEB27FX                   | Notebook    | [268d3a14a7](https://linux-hardware.org/?probe=268d3a14a7) | Sep 04, 2023 |
| HP            | 247 G8 Notebook PC          | Notebook    | [74a7d9e304](https://linux-hardware.org/?probe=74a7d9e304) | Sep 04, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [362e60bccc](https://linux-hardware.org/?probe=362e60bccc) | Sep 04, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [acf39c0e3f](https://linux-hardware.org/?probe=acf39c0e3f) | Sep 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [1cc4b106a4](https://linux-hardware.org/?probe=1cc4b106a4) | Sep 04, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [49d36f6acc](https://linux-hardware.org/?probe=49d36f6acc) | Sep 04, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [8e29b0ae51](https://linux-hardware.org/?probe=8e29b0ae51) | Sep 04, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f235f2e7ef](https://linux-hardware.org/?probe=f235f2e7ef) | Sep 04, 2023 |
| Lenovo        | ThinkPad T400 64758S4       | Notebook    | [efcb0a82e1](https://linux-hardware.org/?probe=efcb0a82e1) | Sep 04, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [82f3e710d9](https://linux-hardware.org/?probe=82f3e710d9) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| VIT           | P2400                       | Notebook    | [d8ea46cf44](https://linux-hardware.org/?probe=d8ea46cf44) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [518f9f381b](https://linux-hardware.org/?probe=518f9f381b) | Sep 04, 2023 |
| MSI           | B360M MORTAR ILYA MUROME... | Desktop     | [0899e4058a](https://linux-hardware.org/?probe=0899e4058a) | Sep 04, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [0faa734044](https://linux-hardware.org/?probe=0faa734044) | Sep 04, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [1b89968327](https://linux-hardware.org/?probe=1b89968327) | Sep 03, 2023 |
| Intel         | NUC8i7HNB J68197-603        | Mini pc     | [cfa756b2c1](https://linux-hardware.org/?probe=cfa756b2c1) | Sep 03, 2023 |
| ALLDOCUBE     | i1402A                      | Notebook    | [d5d2c60681](https://linux-hardware.org/?probe=d5d2c60681) | Sep 03, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [f92734bf2b](https://linux-hardware.org/?probe=f92734bf2b) | Sep 03, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [3ba5173eb2](https://linux-hardware.org/?probe=3ba5173eb2) | Sep 03, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [188a672b4d](https://linux-hardware.org/?probe=188a672b4d) | Sep 03, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [6ce264a945](https://linux-hardware.org/?probe=6ce264a945) | Sep 03, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [58ff81abf2](https://linux-hardware.org/?probe=58ff81abf2) | Sep 03, 2023 |
| Intel         | H61                         | Desktop     | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| MSI           | GF63 Thin 9SC               | Notebook    | [510641439b](https://linux-hardware.org/?probe=510641439b) | Sep 03, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [70172e3461](https://linux-hardware.org/?probe=70172e3461) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [5656c8fd0b](https://linux-hardware.org/?probe=5656c8fd0b) | Sep 03, 2023 |
| ASUSTek       | STRIKER II EXTREME          | Desktop     | [eafb53342a](https://linux-hardware.org/?probe=eafb53342a) | Sep 03, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T410 25188PG       | Notebook    | [603479bd64](https://linux-hardware.org/?probe=603479bd64) | Sep 03, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Desktop     | [3ad034200f](https://linux-hardware.org/?probe=3ad034200f) | Sep 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [b44e37eec5](https://linux-hardware.org/?probe=b44e37eec5) | Sep 03, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [3e995d059e](https://linux-hardware.org/?probe=3e995d059e) | Sep 03, 2023 |
| HP            | ENVY m6                     | Notebook    | [0a810c8663](https://linux-hardware.org/?probe=0a810c8663) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [5ed468ca65](https://linux-hardware.org/?probe=5ed468ca65) | Sep 03, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f02e3011d3](https://linux-hardware.org/?probe=f02e3011d3) | Sep 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [d669a79662](https://linux-hardware.org/?probe=d669a79662) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [e0b3a3a55b](https://linux-hardware.org/?probe=e0b3a3a55b) | Sep 03, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [2a900ea3bd](https://linux-hardware.org/?probe=2a900ea3bd) | Sep 03, 2023 |
| ASRock        | A320D4-P1                   | Desktop     | [244c92966f](https://linux-hardware.org/?probe=244c92966f) | Sep 03, 2023 |
| NEC Comput... | MS-7451MA                   | Desktop     | [963dde730a](https://linux-hardware.org/?probe=963dde730a) | Sep 03, 2023 |
| HP            | 828A                        | Desktop     | [13126d5ce1](https://linux-hardware.org/?probe=13126d5ce1) | Sep 03, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [92b5ca6639](https://linux-hardware.org/?probe=92b5ca6639) | Sep 03, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [976846f5c4](https://linux-hardware.org/?probe=976846f5c4) | Sep 03, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b49fa94760](https://linux-hardware.org/?probe=b49fa94760) | Sep 03, 2023 |
| Pegatron      | IPMSB-GS                    | Desktop     | [35b8f645a7](https://linux-hardware.org/?probe=35b8f645a7) | Sep 03, 2023 |
| Google        | Lick                        | Notebook    | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [45e892a632](https://linux-hardware.org/?probe=45e892a632) | Sep 03, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [9e80502e5d](https://linux-hardware.org/?probe=9e80502e5d) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [d68ec21cac](https://linux-hardware.org/?probe=d68ec21cac) | Sep 03, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4cb41c4eb3](https://linux-hardware.org/?probe=4cb41c4eb3) | Sep 03, 2023 |
| Acer          | Aspire E5-471G              | Notebook    | [b1332205f3](https://linux-hardware.org/?probe=b1332205f3) | Sep 03, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [2c90811519](https://linux-hardware.org/?probe=2c90811519) | Sep 03, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [96dbf56986](https://linux-hardware.org/?probe=96dbf56986) | Sep 03, 2023 |
| Intel         | H81                         | Desktop     | [98f445e831](https://linux-hardware.org/?probe=98f445e831) | Sep 03, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [9c71da2165](https://linux-hardware.org/?probe=9c71da2165) | Sep 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b53be4cf36](https://linux-hardware.org/?probe=b53be4cf36) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | Notebook    | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1458b372fd](https://linux-hardware.org/?probe=1458b372fd) | Sep 03, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [78f4fd9711](https://linux-hardware.org/?probe=78f4fd9711) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| ASUSTek       | M2N                         | Desktop     | [1df62dde56](https://linux-hardware.org/?probe=1df62dde56) | Sep 03, 2023 |
| Gigabyte      | F2A88X-UP4                  | Desktop     | [37bfab5442](https://linux-hardware.org/?probe=37bfab5442) | Sep 02, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [a76e69489c](https://linux-hardware.org/?probe=a76e69489c) | Sep 02, 2023 |
| Alienware     | m15 R3                      | Notebook    | [c2e00a5341](https://linux-hardware.org/?probe=c2e00a5341) | Sep 02, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | Notebook    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [3e11cfff1b](https://linux-hardware.org/?probe=3e11cfff1b) | Sep 02, 2023 |
| Lenovo        | ThinkPad A485 20MVS16C00    | Notebook    | [4d39e78f8f](https://linux-hardware.org/?probe=4d39e78f8f) | Sep 02, 2023 |
| Intel         | DQ77KB AAG40294-401         | Desktop     | [656df7cddd](https://linux-hardware.org/?probe=656df7cddd) | Sep 02, 2023 |
| HP            | 3646h                       | Desktop     | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4fa68712c5](https://linux-hardware.org/?probe=4fa68712c5) | Sep 02, 2023 |
| Multilaser    | UM125                       | Mini pc     | [a43bdb65de](https://linux-hardware.org/?probe=a43bdb65de) | Sep 02, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [adacf1a54a](https://linux-hardware.org/?probe=adacf1a54a) | Sep 02, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [289dd0308b](https://linux-hardware.org/?probe=289dd0308b) | Sep 02, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b161a13302](https://linux-hardware.org/?probe=b161a13302) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [c5db2939ee](https://linux-hardware.org/?probe=c5db2939ee) | Sep 02, 2023 |
| Lenovo        | ThinkPad T460s 20F9003CU... | Notebook    | [8c94711a27](https://linux-hardware.org/?probe=8c94711a27) | Sep 02, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [6a4908587f](https://linux-hardware.org/?probe=6a4908587f) | Sep 02, 2023 |
| HP            | 1497                        | Desktop     | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| UMAX          | 13Wr                        | Notebook    | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [53cd38e0c5](https://linux-hardware.org/?probe=53cd38e0c5) | Sep 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [d25c5d75c1](https://linux-hardware.org/?probe=d25c5d75c1) | Sep 02, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Acer          | TravelMate 8372             | Notebook    | [709e81e4a0](https://linux-hardware.org/?probe=709e81e4a0) | Sep 02, 2023 |
| Microtech     | ebookPro                    | Notebook    | [ce14e0ffeb](https://linux-hardware.org/?probe=ce14e0ffeb) | Sep 02, 2023 |
| Lenovo        | ThinkPad T540p 20BFCTO      | Notebook    | [6c4bd340bc](https://linux-hardware.org/?probe=6c4bd340bc) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [02c6b100f0](https://linux-hardware.org/?probe=02c6b100f0) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e7b6359ed9](https://linux-hardware.org/?probe=e7b6359ed9) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5590e2e8d6](https://linux-hardware.org/?probe=5590e2e8d6) | Sep 02, 2023 |
| MSI           | H81M-P33                    | Desktop     | [266b226035](https://linux-hardware.org/?probe=266b226035) | Sep 02, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [c03e79d6e1](https://linux-hardware.org/?probe=c03e79d6e1) | Sep 02, 2023 |
| MSI           | MS-1688                     | Notebook    | [30cd2d6e9a](https://linux-hardware.org/?probe=30cd2d6e9a) | Sep 02, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [0cd9e98276](https://linux-hardware.org/?probe=0cd9e98276) | Sep 02, 2023 |
| MSI           | GP70 2OD                    | Notebook    | [4bc109f9a0](https://linux-hardware.org/?probe=4bc109f9a0) | Sep 02, 2023 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [674da4ba95](https://linux-hardware.org/?probe=674da4ba95) | Sep 02, 2023 |
| Acer          | Aspire TC-875 V:1.0         | Desktop     | [a25ba0bd0c](https://linux-hardware.org/?probe=a25ba0bd0c) | Sep 02, 2023 |
| ASRock        | H570 Steel Legend           | Desktop     | [192d8ebfa3](https://linux-hardware.org/?probe=192d8ebfa3) | Sep 02, 2023 |
| HP            | 1000                        | Notebook    | [aedfad957a](https://linux-hardware.org/?probe=aedfad957a) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX505DU_TUF50... | Notebook    | [dd49edce58](https://linux-hardware.org/?probe=dd49edce58) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c972b65ed6](https://linux-hardware.org/?probe=c972b65ed6) | Sep 02, 2023 |
| Dell          | Latitude 2120               | Notebook    | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Medion        | B460H6-EM                   | Desktop     | [ec8f0bbb13](https://linux-hardware.org/?probe=ec8f0bbb13) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [f3655da9eb](https://linux-hardware.org/?probe=f3655da9eb) | Sep 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [ba40b3b859](https://linux-hardware.org/?probe=ba40b3b859) | Sep 01, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [60c351e038](https://linux-hardware.org/?probe=60c351e038) | Sep 01, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [741ffec692](https://linux-hardware.org/?probe=741ffec692) | Sep 01, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_23.08/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 6.4.11-desktop-1omv2390      | 1209      | 78.4%   |
| 6.4.8-desktop-2omv2390       | 303       | 19.65%  |
| 6.5.0-desktop-1omv2390       | 19        | 1.23%   |
| 6.6.2-desktop-1omv2390       | 4         | 0.26%   |
| 6.5.1-desktop-1omv2390       | 2         | 0.13%   |
| 6.3.5-desktop-3omv2390       | 2         | 0.13%   |
| 6.6.0-desktop-1omv2390       | 1         | 0.06%   |
| 6.5.0-desktop-0.rc7.1omv2390 | 1         | 0.06%   |
| 6.5.0-desktop-0.rc4.1omv2390 | 1         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.11  | 1209      | 78.4%   |
| 6.4.8   | 303       | 19.65%  |
| 6.5.0   | 21        | 1.36%   |
| 6.6.2   | 4         | 0.26%   |
| 6.5.1   | 2         | 0.13%   |
| 6.3.5   | 2         | 0.13%   |
| 6.6.0   | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4     | 1512      | 98.05%  |
| 6.5     | 23        | 1.49%   |
| 6.6     | 5         | 0.32%   |
| 6.3     | 2         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1542      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 1268      | 82.23%  |
| GNOME    | 142       | 9.21%   |
| LXQt     | 125       | 8.11%   |
| Budgie   | 3         | 0.19%   |
| Cinnamon | 2         | 0.13%   |
| Unknown  | 2         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1486      | 96.37%  |
| X11     | 55        | 3.57%   |
| Unknown | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1399      | 90.73%  |
| GDM     | 142       | 9.21%   |
| Unknown | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 737       | 47.8%   |
| de_DE      | 114       | 7.39%   |
| fr_FR      | 98        | 6.36%   |
| pt_BR      | 95        | 6.16%   |
| ru_RU      | 79        | 5.12%   |
| en_GB      | 66        | 4.28%   |
| pl_PL      | 57        | 3.7%    |
| it_IT      | 46        | 2.98%   |
| es_ES      | 36        | 2.33%   |
| es_MX      | 20        | 1.3%    |
| en_CA      | 19        | 1.23%   |
| cs_CZ      | 15        | 0.97%   |
| hu_HU      | 12        | 0.78%   |
| es_VE      | 11        | 0.71%   |
| en_IN      | 11        | 0.71%   |
| en_AU      | 11        | 0.71%   |
| es_AR      | 10        | 0.65%   |
| tr_TR      | 9         | 0.58%   |
| es_CO      | 9         | 0.58%   |
| nl_BE      | 8         | 0.52%   |
| pt_PT      | 7         | 0.45%   |
| fr_BE      | 7         | 0.45%   |
| es_CL      | 7         | 0.45%   |
| de_AT      | 6         | 0.39%   |
| fr_CA      | 4         | 0.26%   |
| en_IE      | 4         | 0.26%   |
| ro_RO      | 3         | 0.19%   |
| nl_NL      | 3         | 0.19%   |
| fr_CH      | 3         | 0.19%   |
| en_ZA      | 3         | 0.19%   |
| en_DK      | 3         | 0.19%   |
| de_CH      | 3         | 0.19%   |
| ja_JP      | 2         | 0.13%   |
| en_SG      | 2         | 0.13%   |
| de_LU      | 2         | 0.13%   |
| ca_ES      | 2         | 0.13%   |
| ar_DZ      | 2         | 0.13%   |
| UTF-8      | 1         | 0.06%   |
| uk_UA      | 1         | 0.06%   |
| ru_RU-UTF8 | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 932       | 60.44%  |
| BIOS | 610       | 39.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 782       | 50.71%  |
| Ext4     | 658       | 42.67%  |
| Btrfs    | 74        | 4.8%    |
| Xfs      | 8         | 0.52%   |
| F2fs     | 7         | 0.45%   |
| Reiserfs | 4         | 0.26%   |
| Jfs      | 3         | 0.19%   |
| Ext3     | 3         | 0.19%   |
| Ext2     | 3         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1198      | 77.69%  |
| MBR     | 343       | 22.24%  |
| Unknown | 1         | 0.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 790       | 51.23%  |
| Yes       | 752       | 48.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 873       | 56.61%  |
| Yes       | 669       | 43.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 229       | 14.85%  |
| Lenovo                               | 213       | 13.81%  |
| Hewlett-Packard                      | 210       | 13.62%  |
| Dell                                 | 160       | 10.38%  |
| Gigabyte Technology                  | 118       | 7.65%   |
| MSI                                  | 96        | 6.23%   |
| Acer                                 | 92        | 5.97%   |
| Intel                                | 59        | 3.83%   |
| ASRock                               | 54        | 3.5%    |
| Toshiba                              | 26        | 1.69%   |
| Samsung Electronics                  | 24        | 1.56%   |
| Fujitsu                              | 24        | 1.56%   |
| Apple                                | 20        | 1.3%    |
| Foxconn                              | 13        | 0.84%   |
| Medion                               | 12        | 0.78%   |
| AZW                                  | 11        | 0.71%   |
| Positivo                             | 10        | 0.65%   |
| Unknown                              | 10        | 0.65%   |
| Sony                                 | 9         | 0.58%   |
| Pegatron                             | 7         | 0.45%   |
| LG Electronics                       | 7         | 0.45%   |
| HUAWEI                               | 7         | 0.45%   |
| Chuwi                                | 7         | 0.45%   |
| Biostar                              | 7         | 0.45%   |
| Shenzhen Meigao Electronic Equipment | 6         | 0.39%   |
| Packard Bell                         | 6         | 0.39%   |
| ECS                                  | 5         | 0.32%   |
| Microsoft                            | 4         | 0.26%   |
| Google                               | 4         | 0.26%   |
| UMAX                                 | 3         | 0.19%   |
| Panasonic                            | 3         | 0.19%   |
| OEM                                  | 3         | 0.19%   |
| GPU Company                          | 3         | 0.19%   |
| Clevo                                | 3         | 0.19%   |
| ALLDOCUBE                            | 3         | 0.19%   |
| Thomson                              | 2         | 0.13%   |
| Teclast                              | 2         | 0.13%   |
| System76                             | 2         | 0.13%   |
| Shuttle                              | 2         | 0.13%   |
| Red Hat                              | 2         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 14        | 0.91%   |
| ASUS All Series                         | 10        | 0.65%   |
| Intel H61                               | 8         | 0.52%   |
| HP Pavilion g6                          | 7         | 0.45%   |
| Intel H81                               | 6         | 0.39%   |
| MSI MS-7C51                             | 5         | 0.32%   |
| Lenovo ThinkPad L13 Gen 3 21BAS0X700    | 5         | 0.32%   |
| Gigabyte B75M-D3H                       | 5         | 0.32%   |
| Dell OptiPlex 9020                      | 5         | 0.32%   |
| Dell OptiPlex 7010                      | 5         | 0.32%   |
| MSI MS-7C91                             | 4         | 0.26%   |
| Intel X99                               | 4         | 0.26%   |
| HP Laptop 15s-eq2xxx                    | 4         | 0.26%   |
| HP Compaq Pro 6300 SFF                  | 4         | 0.26%   |
| Dell Inspiron 3542                      | 4         | 0.26%   |
| ASUS K50AF                              | 4         | 0.26%   |
| Samsung 300E5M/300E5L                   | 3         | 0.19%   |
| Positivo Mobile                         | 3         | 0.19%   |
| MSI MS-7B89                             | 3         | 0.19%   |
| MSI MS-7B86                             | 3         | 0.19%   |
| MSI MS-7817                             | 3         | 0.19%   |
| Lenovo V15-IGL 82C3                     | 3         | 0.19%   |
| Lenovo IdeaPad Z570 HuronRiver Platform | 3         | 0.19%   |
| Lenovo IdeaPad 3 15ALC6 82MF            | 3         | 0.19%   |
| Intel Jasper Lake Client Platform       | 3         | 0.19%   |
| HP Z400 Workstation                     | 3         | 0.19%   |
| HP Notebook                             | 3         | 0.19%   |
| HP ElitePad 1000 G2                     | 3         | 0.19%   |
| HP EliteDesk 800 G1 USDT                | 3         | 0.19%   |
| HP EliteBook 840 G3                     | 3         | 0.19%   |
| HP Compaq Elite 8300 SFF                | 3         | 0.19%   |
| Gigabyte X570 AORUS ELITE               | 3         | 0.19%   |
| Gigabyte X299 AORUS Gaming              | 3         | 0.19%   |
| Gigabyte B85M-D3H                       | 3         | 0.19%   |
| Gigabyte A320M-H                        | 3         | 0.19%   |
| Dell OptiPlex 3010                      | 3         | 0.19%   |
| Dell Latitude E6410                     | 3         | 0.19%   |
| Dell Latitude E6400                     | 3         | 0.19%   |
| Dell Latitude 7480                      | 3         | 0.19%   |
| Dell Latitude 7390                      | 3         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 72        | 4.67%   |
| Acer Aspire           | 62        | 4.02%   |
| Dell Latitude         | 49        | 3.18%   |
| Lenovo IdeaPad        | 47        | 3.05%   |
| Dell Inspiron         | 45        | 2.92%   |
| ASUS PRIME            | 34        | 2.2%    |
| Dell OptiPlex         | 32        | 2.08%   |
| HP Compaq             | 31        | 2.01%   |
| HP Pavilion           | 28        | 1.82%   |
| HP Laptop             | 28        | 1.82%   |
| Lenovo ThinkCentre    | 27        | 1.75%   |
| ASUS VivoBook         | 26        | 1.69%   |
| HP EliteBook          | 22        | 1.43%   |
| HP ProBook            | 20        | 1.3%    |
| Toshiba Satellite     | 19        | 1.23%   |
| ASUS TUF              | 15        | 0.97%   |
| Unknown               | 14        | 0.91%   |
| HP EliteDesk          | 13        | 0.84%   |
| Fujitsu ESPRIMO       | 13        | 0.84%   |
| Lenovo Yoga           | 10        | 0.65%   |
| Dell Vostro           | 10        | 0.65%   |
| ASUS All              | 10        | 0.65%   |
| HP ProDesk            | 9         | 0.58%   |
| Dell Precision        | 9         | 0.58%   |
| ASUS M5A78L-M         | 9         | 0.58%   |
| Intel H61             | 8         | 0.52%   |
| Intel H81             | 7         | 0.45%   |
| HP Slim               | 7         | 0.45%   |
| ASUS ROG              | 7         | 0.45%   |
| Acer Veriton          | 6         | 0.39%   |
| Packard Bell EasyNote | 5         | 0.32%   |
| MSI MS-7C51           | 5         | 0.32%   |
| Lenovo IdeaCentre     | 5         | 0.32%   |
| HP ENVY               | 5         | 0.32%   |
| Gigabyte X570         | 5         | 0.32%   |
| Gigabyte B75M-D3H     | 5         | 0.32%   |
| Gigabyte B550         | 5         | 0.32%   |
| Dell XPS              | 5         | 0.32%   |
| Acer TravelMate       | 5         | 0.32%   |
| Acer Nitro            | 5         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 153       | 9.92%   |
| 2011    | 130       | 8.43%   |
| 2021    | 120       | 7.78%   |
| 2018    | 114       | 7.39%   |
| 2014    | 114       | 7.39%   |
| 2020    | 110       | 7.13%   |
| 2013    | 102       | 6.61%   |
| 2010    | 98        | 6.36%   |
| 2019    | 97        | 6.29%   |
| 2017    | 94        | 6.1%    |
| 2022    | 91        | 5.9%    |
| 2016    | 77        | 4.99%   |
| 2015    | 56        | 3.63%   |
| 2009    | 55        | 3.57%   |
| 2023    | 46        | 2.98%   |
| 2008    | 38        | 2.46%   |
| 2007    | 31        | 2.01%   |
| 2006    | 12        | 0.78%   |
| 2005    | 3         | 0.19%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 731       | 47.41%  |
| Desktop     | 721       | 46.76%  |
| Mini pc     | 35        | 2.27%   |
| Convertible | 22        | 1.43%   |
| All in one  | 19        | 1.23%   |
| Tablet      | 10        | 0.65%   |
| Server      | 3         | 0.19%   |
| Other       | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1542      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1536      | 99.61%  |
| Yes  | 6         | 0.39%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 471       | 30.54%  |
| 3.01-4.0    | 290       | 18.81%  |
| 16.01-24.0  | 287       | 18.61%  |
| 8.01-16.0   | 254       | 16.47%  |
| 32.01-64.0  | 112       | 7.26%   |
| 1.01-2.0    | 44        | 2.85%   |
| 64.01-256.0 | 31        | 2.01%   |
| 2.01-3.0    | 27        | 1.75%   |
| 24.01-32.0  | 22        | 1.43%   |
| 0.51-1.0    | 4         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 976       | 63.25%  |
| 2.01-3.0  | 352       | 22.81%  |
| 0.51-1.0  | 125       | 8.1%    |
| 3.01-4.0  | 61        | 3.95%   |
| 4.01-8.0  | 16        | 1.04%   |
| 0.01-0.5  | 12        | 0.78%   |
| 8.01-16.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 881       | 57.13%  |
| 2      | 403       | 26.13%  |
| 3      | 129       | 8.37%   |
| 4      | 53        | 3.44%   |
| 5      | 27        | 1.75%   |
| 0      | 22        | 1.43%   |
| 6      | 18        | 1.17%   |
| 8      | 3         | 0.19%   |
| 10     | 2         | 0.13%   |
| 7      | 2         | 0.13%   |
| 11     | 1         | 0.06%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 881       | 57.13%  |
| Yes       | 661       | 42.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1368      | 88.72%  |
| No        | 174       | 11.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1083      | 70.23%  |
| No        | 459       | 29.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 842       | 54.6%   |
| No        | 700       | 45.4%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 183       | 11.87%  |
| Germany      | 173       | 11.22%  |
| Brazil       | 143       | 9.27%   |
| France       | 107       | 6.94%   |
| Russia       | 99        | 6.42%   |
| Poland       | 81        | 5.25%   |
| Italy        | 69        | 4.47%   |
| UK           | 65        | 4.22%   |
| Spain        | 54        | 3.5%    |
| Canada       | 42        | 2.72%   |
| Australia    | 31        | 2.01%   |
| Mexico       | 27        | 1.75%   |
| India        | 27        | 1.75%   |
| Netherlands  | 22        | 1.43%   |
| Hungary      | 21        | 1.36%   |
| Japan        | 20        | 1.3%    |
| Czechia      | 20        | 1.3%    |
| Belgium      | 19        | 1.23%   |
| Turkey       | 18        | 1.17%   |
| Colombia     | 17        | 1.1%    |
| Indonesia    | 15        | 0.97%   |
| Argentina    | 14        | 0.91%   |
| Thailand     | 13        | 0.84%   |
| Romania      | 13        | 0.84%   |
| Greece       | 13        | 0.84%   |
| Venezuela    | 11        | 0.71%   |
| Portugal     | 10        | 0.65%   |
| Bulgaria     | 10        | 0.65%   |
| Sweden       | 9         | 0.58%   |
| China        | 9         | 0.58%   |
| Austria      | 9         | 0.58%   |
| Switzerland  | 8         | 0.52%   |
| Slovakia     | 8         | 0.52%   |
| Malaysia     | 8         | 0.52%   |
| Chile        | 8         | 0.52%   |
| Ukraine      | 7         | 0.45%   |
| South Africa | 7         | 0.45%   |
| Finland      | 7         | 0.45%   |
| Serbia       | 6         | 0.39%   |
| Norway       | 5         | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Warsaw         | 20        | 1.3%    |
| Berlin         | 16        | 1.04%   |
| Moscow         | 15        | 0.97%   |
| Melbourne      | 12        | 0.78%   |
| Sydney         | 11        | 0.71%   |
| Rio de Janeiro | 11        | 0.71%   |
| Milan          | 10        | 0.65%   |
| Paris          | 9         | 0.58%   |
| Krakow         | 9         | 0.58%   |
| Sao Paulo      | 8         | 0.52%   |
| Istanbul       | 8         | 0.52%   |
| Athens         | 8         | 0.52%   |
| Stuttgart      | 7         | 0.45%   |
| St Petersburg  | 7         | 0.45%   |
| San Cristóbal | 7         | 0.45%   |
| Rome           | 7         | 0.45%   |
| Madrid         | 7         | 0.45%   |
| Vienna         | 6         | 0.39%   |
| Prague         | 6         | 0.39%   |
| Munich         | 6         | 0.39%   |
| Curitiba       | 6         | 0.39%   |
| Wroclaw        | 5         | 0.32%   |
| Vancouver      | 5         | 0.32%   |
| Novosibirsk    | 5         | 0.32%   |
| Hamburg        | 5         | 0.32%   |
| Braunschweig   | 5         | 0.32%   |
| Brasília      | 5         | 0.32%   |
| Yekaterinburg  | 4         | 0.26%   |
| Sofia          | 4         | 0.26%   |
| Porto Alegre   | 4         | 0.26%   |
| Perth          | 4         | 0.26%   |
| Perm           | 4         | 0.26%   |
| Liège         | 4         | 0.26%   |
| Glasgow        | 4         | 0.26%   |
| Genoa          | 4         | 0.26%   |
| Delhi          | 4         | 0.26%   |
| Cologne        | 4         | 0.26%   |
| Chelyabinsk    | 4         | 0.26%   |
| Budapest       | 4         | 0.26%   |
| Bogotá        | 4         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 341       | 408    | 14.86%  |
| Samsung Electronics         | 282       | 334    | 12.29%  |
| Seagate                     | 263       | 305    | 11.46%  |
| Toshiba                     | 150       | 164    | 6.54%   |
| Kingston                    | 143       | 153    | 6.23%   |
| Crucial                     | 99        | 115    | 4.32%   |
| SanDisk                     | 95        | 100    | 4.14%   |
| Unknown                     | 73        | 97     | 3.18%   |
| Hitachi                     | 69        | 69     | 3.01%   |
| China                       | 49        | 53     | 2.14%   |
| A-DATA Technology           | 49        | 51     | 2.14%   |
| SK hynix                    | 41        | 42     | 1.79%   |
| Intel                       | 39        | 40     | 1.7%    |
| SPCC                        | 31        | 33     | 1.35%   |
| Micron Technology           | 31        | 31     | 1.35%   |
| HGST                        | 28        | 28     | 1.22%   |
| Unknown                     | 28        | 30     | 1.22%   |
| Intenso                     | 25        | 27     | 1.09%   |
| GOODRAM                     | 21        | 25     | 0.92%   |
| Patriot                     | 19        | 19     | 0.83%   |
| Maxtor                      | 18        | 19     | 0.78%   |
| PNY                         | 16        | 17     | 0.7%    |
| Silicon Motion              | 14        | 15     | 0.61%   |
| Netac                       | 14        | 15     | 0.61%   |
| Lexar                       | 14        | 17     | 0.61%   |
| JMicron Technology          | 14        | 14     | 0.61%   |
| Apple                       | 14        | 14     | 0.61%   |
| Kingston Technology Company | 13        | 13     | 0.57%   |
| Phison                      | 12        | 13     | 0.52%   |
| KIOXIA                      | 12        | 12     | 0.52%   |
| Team                        | 11        | 11     | 0.48%   |
| SSSTC                       | 10        | 10     | 0.44%   |
| Fanxiang                    | 10        | 10     | 0.44%   |
| Apacer                      | 10        | 10     | 0.44%   |
| LITEON                      | 9         | 9      | 0.39%   |
| KingSpec                    | 9         | 10     | 0.39%   |
| Transcend                   | 8         | 8      | 0.35%   |
| Hewlett-Packard             | 8         | 8      | 0.35%   |
| OCZ                         | 7         | 7      | 0.31%   |
| Verbatim                    | 6         | 6      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 30        | 1.2%    |
| Unknown                            | 28        | 1.12%   |
| Seagate ST500DM002-1BD142 500GB    | 22        | 0.88%   |
| Kingston SA400S37480G 480GB SSD    | 22        | 0.88%   |
| Crucial CT500MX500SSD1 500GB       | 18        | 0.72%   |
| Seagate ST1000DM010-2EP102 1TB     | 17        | 0.68%   |
| Seagate ST500LT012-1DG142 500GB    | 15        | 0.6%    |
| SanDisk NVMe SSD Drive 1TB         | 15        | 0.6%    |
| Toshiba MQ04ABF100 1TB             | 14        | 0.56%   |
| Samsung SSD 860 EVO 500GB          | 14        | 0.56%   |
| Toshiba MQ01ABD100 1TB             | 13        | 0.52%   |
| Samsung SSD 850 EVO 250GB          | 13        | 0.52%   |
| Crucial CT240BX500SSD1 240GB       | 13        | 0.52%   |
| Unknown SD/MMC/MS PRO 256GB        | 12        | 0.48%   |
| Toshiba DT01ACA100 1TB             | 12        | 0.48%   |
| Samsung SSD 870 EVO 500GB          | 12        | 0.48%   |
| Toshiba MQ01ABF050 500GB           | 11        | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB     | 11        | 0.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 0.44%   |
| Kingston SA400S37120G 120GB SSD    | 11        | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB           | 9         | 0.36%   |
| Toshiba DT01ACA050 500GB           | 9         | 0.36%   |
| Crucial CT1000BX500SSD1 1TB        | 9         | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 8         | 0.32%   |
| Unknown SD/MMC 2GB                 | 8         | 0.32%   |
| Unknown M.S./M.S.Pro/HG 16GB       | 8         | 0.32%   |
| Unknown Compact Flash 977MB        | 8         | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB     | 8         | 0.32%   |
| Seagate Expansion 1TB              | 8         | 0.32%   |
| SanDisk SSD PLUS 240GB             | 8         | 0.32%   |
| Samsung SSD 970 EVO Plus 500GB     | 8         | 0.32%   |
| Samsung SSD 860 EVO 250GB          | 8         | 0.32%   |
| Samsung SSD 850 EVO 500GB          | 8         | 0.32%   |
| Samsung HD322HJ 320GB              | 8         | 0.32%   |
| Kingston SV300S37A120G 120GB SSD   | 8         | 0.32%   |
| JMicron Generic 8GB                | 8         | 0.32%   |
| WDC WD10SPZX-24Z10 1TB             | 7         | 0.28%   |
| Seagate ST3500418AS 500GB          | 7         | 0.28%   |
| Seagate ST1000DM003-1SB102 1TB     | 7         | 0.28%   |
| Seagate ST1000DM003-1ER162 1TB     | 7         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 273       | 319    | 30.99%  |
| Seagate             | 259       | 301    | 29.4%   |
| Toshiba             | 131       | 143    | 14.87%  |
| Hitachi             | 69        | 69     | 7.83%   |
| Samsung Electronics | 54        | 57     | 6.13%   |
| HGST                | 28        | 28     | 3.18%   |
| Maxtor              | 17        | 18     | 1.93%   |
| Unknown             | 13        | 13     | 1.48%   |
| JMicron Technology  | 9         | 9      | 1.02%   |
| Apple               | 7         | 7      | 0.79%   |
| Fujitsu             | 4         | 5      | 0.45%   |
| ExcelStor           | 3         | 3      | 0.34%   |
| TO Exter            | 2         | 2      | 0.23%   |
| Min Yi U            | 2         | 2      | 0.23%   |
| Inateck             | 2         | 2      | 0.23%   |
| External            | 2         | 2      | 0.23%   |
| WD MediaMax         | 1         | 1      | 0.11%   |
| SSK                 | 1         | 1      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| IB-AC703            | 1         | 1      | 0.11%   |
| DAS                 | 1         | 4      | 0.11%   |
| Unknown             | 1         | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 138       | 154    | 15.45%  |
| Kingston            | 108       | 114    | 12.09%  |
| Crucial             | 76        | 79     | 8.51%   |
| SanDisk             | 59        | 62     | 6.61%   |
| China               | 49        | 53     | 5.49%   |
| WDC                 | 43        | 48     | 4.82%   |
| A-DATA Technology   | 35        | 36     | 3.92%   |
| SPCC                | 27        | 27     | 3.02%   |
| Intenso             | 24        | 26     | 2.69%   |
| GOODRAM             | 21        | 25     | 2.35%   |
| Patriot             | 18        | 18     | 2.02%   |
| PNY                 | 16        | 17     | 1.79%   |
| Micron Technology   | 16        | 16     | 1.79%   |
| Intel               | 15        | 15     | 1.68%   |
| SK hynix            | 13        | 14     | 1.46%   |
| Toshiba             | 11        | 12     | 1.23%   |
| Netac               | 10        | 11     | 1.12%   |
| KingSpec            | 9         | 10     | 1.01%   |
| Transcend           | 8         | 8      | 0.9%    |
| Team                | 8         | 8      | 0.9%    |
| LITEON              | 8         | 8      | 0.9%    |
| Unknown             | 8         | 8      | 0.9%    |
| OCZ                 | 7         | 7      | 0.78%   |
| Lexar               | 7         | 8      | 0.78%   |
| Verbatim            | 6         | 6      | 0.67%   |
| Hewlett-Packard     | 6         | 6      | 0.67%   |
| Fanxiang            | 6         | 6      | 0.67%   |
| Apple               | 6         | 6      | 0.67%   |
| Apacer              | 6         | 6      | 0.67%   |
| LITEONIT            | 5         | 5      | 0.56%   |
| WALRAM              | 4         | 4      | 0.45%   |
| USB3.0              | 4         | 4      | 0.45%   |
| T-FORCE             | 4         | 4      | 0.45%   |
| KingFast            | 4         | 4      | 0.45%   |
| INNOVATION IT       | 4         | 4      | 0.45%   |
| HS-SSD-C100         | 4         | 4      | 0.45%   |
| Vaseky              | 3         | 3      | 0.34%   |
| Seagate             | 3         | 3      | 0.34%   |
| Emtec               | 3         | 3      | 0.34%   |
| AirDisk             | 3         | 3      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 764       | 944    | 37.84%  |
| HDD     | 741       | 990    | 36.7%   |
| NVMe    | 421       | 502    | 20.85%  |
| MMC     | 64        | 74     | 3.17%   |
| Unknown | 29        | 47     | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1236      | 1835   | 67.14%  |
| NVMe | 420       | 497    | 22.81%  |
| SAS  | 121       | 151    | 6.57%   |
| MMC  | 64        | 74     | 3.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 952       | 1226   | 61.74%  |
| 0.51-1.0   | 444       | 524    | 28.79%  |
| 1.01-2.0   | 88        | 104    | 5.71%   |
| 3.01-4.0   | 22        | 30     | 1.43%   |
| 2.01-3.0   | 21        | 25     | 1.36%   |
| 4.01-10.0  | 11        | 18     | 0.71%   |
| 10.01-20.0 | 4         | 7      | 0.26%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 575       | 37.27%  |
| 101-250        | 315       | 20.41%  |
| 251-500        | 202       | 13.09%  |
| 501-1000       | 120       | 7.78%   |
| 51-100         | 102       | 6.61%   |
| Unknown        | 75        | 4.86%   |
| 21-50          | 68        | 4.41%   |
| 1001-2000      | 50        | 3.24%   |
| 2001-3000      | 20        | 1.3%    |
| More than 3000 | 16        | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1243      | 80.61%  |
| 21-50          | 82        | 5.32%   |
| Unknown        | 75        | 4.86%   |
| 51-100         | 43        | 2.79%   |
| 101-250        | 42        | 2.72%   |
| 251-500        | 21        | 1.36%   |
| 501-1000       | 19        | 1.23%   |
| 1001-2000      | 9         | 0.58%   |
| More than 3000 | 6         | 0.39%   |
| 2001-3000      | 2         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB      | 10        | 10     | 2.43%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 6      | 1.46%   |
| Seagate ST3500418AS 500GB            | 5         | 5      | 1.21%   |
| Toshiba MQ01ABD100 1TB               | 4         | 4      | 0.97%   |
| Toshiba MK3259GSXP 320GB             | 4         | 4      | 0.97%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 5      | 0.97%   |
| Samsung Electronics HD322HJ 320GB    | 4         | 4      | 0.97%   |
| Hitachi HTS543225L9A300 250GB        | 4         | 4      | 0.97%   |
| Toshiba DT01ACA050 500GB             | 3         | 3      | 0.73%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 3         | 3      | 0.73%   |
| Seagate ST9500325AS 500GB            | 3         | 3      | 0.73%   |
| Seagate ST320LT012-9WS14C 320GB      | 3         | 3      | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 3      | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 3      | 0.73%   |
| Samsung Electronics HD502HJ 500GB    | 3         | 3      | 0.73%   |
| Samsung Electronics HD103UJ 1TB      | 3         | 3      | 0.73%   |
| Maxtor STM380815AS 80GB              | 3         | 3      | 0.73%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 3      | 0.73%   |
| HGST HTS721010A9E630 1TB             | 3         | 3      | 0.73%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 0.49%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 2         | 2      | 0.49%   |
| WDC WD5000LPVX-60V0TT0 500GB         | 2         | 2      | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 2      | 0.49%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 2      | 0.49%   |
| WDC WD5000BPVT-00HXZT3 500GB         | 2         | 2      | 0.49%   |
| WDC WD5000AVCS-632DY1 500GB          | 2         | 2      | 0.49%   |
| WDC WD5000AAKX-75U6AA0 500GB         | 2         | 2      | 0.49%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2         | 2      | 0.49%   |
| WDC WD3200AAJS-56M0A0 320GB          | 2         | 2      | 0.49%   |
| WDC WD3200AAJS-56B4A0 320GB          | 2         | 2      | 0.49%   |
| WDC WD3200AAJS-00L7A0 320GB          | 2         | 2      | 0.49%   |
| WDC WD10EZEX-60M2NA0 1TB             | 2         | 2      | 0.49%   |
| WDC WD10EARS-00Y5B1 1TB              | 2         | 2      | 0.49%   |
| Toshiba MQ04ABF100 1TB               | 2         | 2      | 0.49%   |
| Toshiba MQ01ABF050 500GB             | 2         | 2      | 0.49%   |
| Toshiba MK6475GSX 640GB              | 2         | 2      | 0.49%   |
| Toshiba DT01ACA100 1TB               | 2         | 2      | 0.49%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 0.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 93     | 22.17%  |
| WDC                 | 87        | 92     | 21.43%  |
| Hitachi             | 47        | 47     | 11.58%  |
| Toshiba             | 42        | 43     | 10.34%  |
| Samsung Electronics | 35        | 36     | 8.62%   |
| SK hynix            | 12        | 12     | 2.96%   |
| Maxtor              | 12        | 12     | 2.96%   |
| SanDisk             | 10        | 10     | 2.46%   |
| Kingston            | 8         | 8      | 1.97%   |
| HGST                | 8         | 8      | 1.97%   |
| A-DATA Technology   | 8         | 8      | 1.97%   |
| China               | 6         | 6      | 1.48%   |
| Micron Technology   | 5         | 5      | 1.23%   |
| SPCC                | 4         | 4      | 0.99%   |
| Netac               | 3         | 3      | 0.74%   |
| LITEONIT            | 3         | 3      | 0.74%   |
| Intel               | 3         | 3      | 0.74%   |
| Intenso             | 2         | 2      | 0.49%   |
| ExcelStor           | 2         | 2      | 0.49%   |
| Crucial             | 2         | 2      | 0.49%   |
| XPG                 | 1         | 1      | 0.25%   |
| Wibtek              | 1         | 1      | 0.25%   |
| SSSTC               | 1         | 1      | 0.25%   |
| SandForce           | 1         | 1      | 0.25%   |
| Reeinno             | 1         | 1      | 0.25%   |
| PNY                 | 1         | 1      | 0.25%   |
| Plextor             | 1         | 1      | 0.25%   |
| OCZ-AGIL            | 1         | 1      | 0.25%   |
| KingDian            | 1         | 1      | 0.25%   |
| JMicron Technology  | 1         | 1      | 0.25%   |
| INNOVATION IT       | 1         | 1      | 0.25%   |
| Fujitsu             | 1         | 1      | 0.25%   |
| EX276687RUS         | 1         | 1      | 0.25%   |
| C300-CTF            | 1         | 1      | 0.25%   |
| C-S12               | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |
| ACOS                | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 93     | 28.66%  |
| WDC                 | 79        | 83     | 25.16%  |
| Hitachi             | 47        | 47     | 14.97%  |
| Toshiba             | 42        | 43     | 13.38%  |
| Samsung Electronics | 31        | 32     | 9.87%   |
| Maxtor              | 12        | 12     | 3.82%   |
| HGST                | 8         | 8      | 2.55%   |
| ExcelStor           | 2         | 2      | 0.64%   |
| JMicron Technology  | 1         | 1      | 0.32%   |
| Fujitsu             | 1         | 1      | 0.32%   |
| Apple               | 1         | 1      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 285       | 323    | 76%     |
| SSD  | 80        | 83     | 21.33%  |
| NVMe | 10        | 10     | 2.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-22JJ5T0 320GB   | 1         | 1      | 10%     |
| WDC WD10EZEX-00BN5A0 1TB       | 1         | 1      | 10%     |
| Toshiba MQ01ABD050 500GB       | 1         | 1      | 10%     |
| Toshiba MK2575GSX 250GB        | 1         | 1      | 10%     |
| Toshiba MK1234GSX 120GB        | 1         | 1      | 10%     |
| Seagate ST3320613AS 320GB      | 1         | 1      | 10%     |
| Seagate ST3250318AS 250GB      | 1         | 1      | 10%     |
| Seagate ST31000528AS 1TB       | 1         | 1      | 10%     |
| Intel SSDSCKKF256H6 SATA 256GB | 1         | 1      | 10%     |
| Hitachi HTS545032B9A300 320GB  | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 30%     |
| Seagate | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Intel   | 1         | 1      | 10%     |
| Hitachi | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1240      | 1886   | 68.62%  |
| Malfunc  | 366       | 416    | 20.25%  |
| Detected | 191       | 245    | 10.57%  |
| Failed   | 10        | 10     | 0.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1096      | 56.76%  |
| AMD                              | 301       | 15.59%  |
| Samsung Electronics              | 115       | 5.96%   |
| SanDisk                          | 69        | 3.57%   |
| Kingston Technology Company      | 49        | 2.54%   |
| Phison Electronics               | 30        | 1.55%   |
| SK hynix                         | 26        | 1.35%   |
| Silicon Motion                   | 25        | 1.29%   |
| Micron/Crucial Technology        | 25        | 1.29%   |
| Nvidia                           | 22        | 1.14%   |
| ASMedia Technology               | 22        | 1.14%   |
| JMicron Technology               | 21        | 1.09%   |
| Micron Technology                | 18        | 0.93%   |
| Marvell Technology Group         | 17        | 0.88%   |
| MAXIO Technology (Hangzhou)      | 16        | 0.83%   |
| KIOXIA                           | 15        | 0.78%   |
| ADATA Technology                 | 12        | 0.62%   |
| Solid State Storage Technology   | 9         | 0.47%   |
| Realtek Semiconductor            | 8         | 0.41%   |
| Toshiba America Info Systems     | 6         | 0.31%   |
| Shenzhen Longsys Electronics     | 6         | 0.31%   |
| VIA Technologies                 | 4         | 0.21%   |
| Union Memory (Shenzhen)          | 3         | 0.16%   |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |
| Netac Technology                 | 2         | 0.1%    |
| LSI Logic / Symbios Logic        | 2         | 0.1%    |
| INNOGRIT                         | 2         | 0.1%    |
| Broadcom / LSI                   | 2         | 0.1%    |
| Seagate Technology               | 1         | 0.05%   |
| Nextorage                        | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 180       | 8.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 89        | 3.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 69        | 3.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 68        | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 57        | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 56        | 2.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 50        | 2.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 50        | 2.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 43        | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 42        | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 42        | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 39        | 1.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 36        | 1.62%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 34        | 1.53%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 34        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 34        | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 33        | 1.48%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 32        | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 31        | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                                  | 29        | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 27        | 1.21%   |
| AMD FCH SATA Controller D                                                               | 26        | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 25        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 24        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21        | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21        | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 20        | 0.9%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 20        | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 20        | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 20        | 0.9%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 20        | 0.9%    |
| Intel SATA Controller [RAID mode]                                                       | 19        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 19        | 0.85%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 18        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 18        | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 17        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 16        | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 15        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1188      | 61.14%  |
| NVMe | 421       | 21.67%  |
| IDE  | 231       | 11.89%  |
| RAID | 98        | 5.04%   |
| SAS  | 5         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1177      | 76.33%  |
| AMD    | 365       | 23.67%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-3470 CPU @ 3.20GHz        | 18        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 12        | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 12        | 0.78%   |
| Intel Core i5-10400 CPU @ 2.90GHz       | 12        | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 12        | 0.78%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 12        | 0.78%   |
| AMD Ryzen 5 3600 6-Core Processor       | 12        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 11        | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 10        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 10        | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.65%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 10        | 0.65%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 10        | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 9         | 0.58%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 9         | 0.58%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 9         | 0.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 9         | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 8         | 0.52%   |
| Intel Core i3-2100 CPU @ 3.10GHz        | 8         | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 8         | 0.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 8         | 0.52%   |
| AMD FX-8350 Eight-Core Processor        | 8         | 0.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 7         | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 7         | 0.45%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 7         | 0.45%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 7         | 0.45%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 7         | 0.45%   |
| Intel Core i5-3570 CPU @ 3.40GHz        | 7         | 0.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 7         | 0.45%   |
| Intel Core i5 CPU M 430 @ 2.27GHz       | 7         | 0.45%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 7         | 0.45%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 7         | 0.45%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 7         | 0.45%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 7         | 0.45%   |
| Intel Celeron N4000 CPU @ 1.10GHz       | 7         | 0.45%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 7         | 0.45%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 7         | 0.45%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 7         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 379       | 24.58%  |
| Intel Core i7           | 185       | 12%     |
| Intel Core i3           | 168       | 10.89%  |
| Intel Celeron           | 113       | 7.33%   |
| Other                   | 95        | 6.16%   |
| AMD Ryzen 5             | 90        | 5.84%   |
| AMD Ryzen 7             | 58        | 3.76%   |
| Intel Pentium           | 55        | 3.57%   |
| Intel Core 2 Duo        | 51        | 3.31%   |
| AMD Ryzen 3             | 33        | 2.14%   |
| Intel Pentium Dual-Core | 27        | 1.75%   |
| AMD FX                  | 26        | 1.69%   |
| Intel Xeon              | 25        | 1.62%   |
| Intel Atom              | 22        | 1.43%   |
| AMD Ryzen 9             | 18        | 1.17%   |
| Intel Core 2 Quad       | 17        | 1.1%    |
| AMD A6                  | 15        | 0.97%   |
| AMD A8                  | 13        | 0.84%   |
| AMD A4                  | 13        | 0.84%   |
| AMD Athlon II X2        | 10        | 0.65%   |
| Intel Pentium Silver    | 9         | 0.58%   |
| AMD Ryzen 5 PRO         | 9         | 0.58%   |
| AMD A10                 | 8         | 0.52%   |
| Intel Pentium Dual      | 7         | 0.45%   |
| Intel Core 2            | 7         | 0.45%   |
| AMD Phenom II X4        | 7         | 0.45%   |
| AMD Athlon 64 X2        | 7         | 0.45%   |
| AMD Athlon              | 7         | 0.45%   |
| Intel Genuine           | 6         | 0.39%   |
| AMD E                   | 6         | 0.39%   |
| Intel Pentium Gold      | 5         | 0.32%   |
| AMD Athlon II Dual-Core | 4         | 0.26%   |
| Intel Pentium D         | 3         | 0.19%   |
| Intel Core M            | 3         | 0.19%   |
| AMD Sempron             | 3         | 0.19%   |
| AMD Ryzen 7 PRO         | 3         | 0.19%   |
| AMD PRO A10             | 3         | 0.19%   |
| Intel Pentium 4         | 2         | 0.13%   |
| Intel Core m3           | 2         | 0.13%   |
| Intel Core i9           | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 697       | 45.2%   |
| 4      | 539       | 34.95%  |
| 6      | 134       | 8.69%   |
| 8      | 77        | 4.99%   |
| 1      | 35        | 2.27%   |
| 12     | 24        | 1.56%   |
| 14     | 10        | 0.65%   |
| 10     | 10        | 0.65%   |
| 3      | 9         | 0.58%   |
| 16     | 4         | 0.26%   |
| 36     | 1         | 0.06%   |
| 24     | 1         | 0.06%   |
| 5      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1537      | 99.68%  |
| 2      | 3         | 0.19%   |
| 16     | 1         | 0.06%   |
| 14     | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 939       | 60.89%  |
| 1      | 599       | 38.85%  |
| 4      | 2         | 0.13%   |
| 12     | 1         | 0.06%   |
| 8      | 1         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1542      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1196      | 77.56%  |
| 0x08108109 | 33        | 2.14%   |
| 0x0a50000d | 26        | 1.69%   |
| 0x08701030 | 16        | 1.04%   |
| 0x08608103 | 15        | 0.97%   |
| 0x010000c8 | 15        | 0.97%   |
| 0x0a20120a | 14        | 0.91%   |
| 0x0a50000c | 12        | 0.78%   |
| 0x06000822 | 11        | 0.71%   |
| 0x08701021 | 10        | 0.65%   |
| 0x0800820d | 10        | 0.65%   |
| 0x06006705 | 10        | 0.65%   |
| 0x0600611a | 10        | 0.65%   |
| 0x06001119 | 10        | 0.65%   |
| 0x0a404102 | 9         | 0.58%   |
| 0x0810100b | 9         | 0.58%   |
| 0x08600106 | 8         | 0.52%   |
| 0x06003106 | 8         | 0.52%   |
| 0x06000817 | 7         | 0.45%   |
| 0x0600081c | 6         | 0.39%   |
| 0x08108102 | 5         | 0.32%   |
| 0x08101016 | 5         | 0.32%   |
| 0x08001138 | 5         | 0.32%   |
| 0x05000028 | 5         | 0.32%   |
| 0x0a201025 | 4         | 0.26%   |
| 0x08608104 | 4         | 0.26%   |
| 0x08200103 | 4         | 0.26%   |
| 0x08101007 | 4         | 0.26%   |
| 0x03000027 | 4         | 0.26%   |
| 0x010000b6 | 4         | 0.26%   |
| 0x08a00006 | 3         | 0.19%   |
| 0x08600109 | 3         | 0.19%   |
| 0x06001116 | 3         | 0.19%   |
| 0x05000101 | 3         | 0.19%   |
| 0x03000014 | 3         | 0.19%   |
| 0x0a601206 | 2         | 0.13%   |
| 0x0a601203 | 2         | 0.13%   |
| 0x08608102 | 2         | 0.13%   |
| 0x08600104 | 2         | 0.13%   |
| 0x0800820b | 2         | 0.13%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 163       | 10.57%  |
| Haswell          | 162       | 10.51%  |
| SandyBridge      | 131       | 8.5%    |
| IvyBridge        | 131       | 8.5%    |
| Penryn           | 82        | 5.32%   |
| Skylake          | 78        | 5.06%   |
| Westmere         | 64        | 4.15%   |
| Zen 3            | 61        | 3.96%   |
| Zen+             | 53        | 3.44%   |
| Silvermont       | 45        | 2.92%   |
| Alderlake Hybrid | 43        | 2.79%   |
| Unknown          | 42        | 2.72%   |
| Zen 2            | 41        | 2.66%   |
| CometLake        | 40        | 2.59%   |
| Piledriver       | 38        | 2.46%   |
| Core             | 38        | 2.46%   |
| Goldmont plus    | 36        | 2.33%   |
| Zen              | 29        | 1.88%   |
| K10              | 29        | 1.88%   |
| Broadwell        | 29        | 1.88%   |
| Icelake          | 28        | 1.82%   |
| TigerLake        | 26        | 1.69%   |
| Excavator        | 21        | 1.36%   |
| Nehalem          | 18        | 1.17%   |
| Goldmont         | 16        | 1.04%   |
| Tremont          | 15        | 0.97%   |
| Bonnell          | 15        | 0.97%   |
| K8 Hammer        | 13        | 0.84%   |
| Steamroller      | 11        | 0.71%   |
| Bobcat           | 10        | 0.65%   |
| K10 Llano        | 9         | 0.58%   |
| Gracemont        | 9         | 0.58%   |
| Puma             | 5         | 0.32%   |
| NetBurst         | 5         | 0.32%   |
| Jaguar           | 3         | 0.19%   |
| K8 & K10 hybrid  | 2         | 0.13%   |
| Bulldozer        | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 912       | 53.18%  |
| AMD                              | 408       | 23.79%  |
| Nvidia                           | 386       | 22.51%  |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Red Hat                          | 2         | 0.12%   |
| Matrox Electronics Systems       | 2         | 0.12%   |
| ATI Technologies                 | 2         | 0.12%   |
| ASPEED Technology                | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 105       | 5.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 59        | 3.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 49        | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 40        | 2.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 39        | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 39        | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 34        | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 31        | 1.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 29        | 1.66%   |
| Intel HD Graphics 620                                                                    | 28        | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26        | 1.48%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 1.37%   |
| Intel UHD Graphics 620                                                                   | 23        | 1.31%   |
| Intel HD Graphics 530                                                                    | 23        | 1.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 22        | 1.26%   |
| Intel HD Graphics 5500                                                                   | 21        | 1.2%    |
| AMD Lucienne                                                                             | 21        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 20        | 1.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.08%   |
| Intel HD Graphics 630                                                                    | 18        | 1.03%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 1.03%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16        | 0.91%   |
| Intel JasperLake [UHD Graphics]                                                          | 16        | 0.91%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 16        | 0.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 15        | 0.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15        | 0.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 0.8%    |
| Intel HD Graphics 500                                                                    | 14        | 0.8%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13        | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 13        | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 0.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 0.74%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 13        | 0.74%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 13        | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.68%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 12        | 0.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 701       | 45.46%  |
| 1 x AMD                | 347       | 22.5%   |
| 1 x Nvidia             | 243       | 15.76%  |
| Intel + Nvidia         | 124       | 8.04%   |
| 2 x Intel              | 52        | 3.37%   |
| Intel + AMD            | 33        | 2.14%   |
| 2 x AMD                | 18        | 1.17%   |
| AMD + Nvidia           | 12        | 0.78%   |
| 2 x Nvidia             | 3         | 0.19%   |
| 2 x Intel + 1 x Nvidia | 2         | 0.13%   |
| 1 x SiS                | 2         | 0.13%   |
| 1 x Red Hat            | 2         | 0.13%   |
| 1 x Matrox             | 2         | 0.13%   |
| Nvidia + ASPEED        | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1496      | 97.02%  |
| Unknown     | 34        | 2.2%    |
| Proprietary | 12        | 0.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 790       | 51.23%  |
| 1.01-2.0   | 214       | 13.88%  |
| 0.01-0.5   | 175       | 11.35%  |
| 0.51-1.0   | 145       | 9.4%    |
| 3.01-4.0   | 97        | 6.29%   |
| 7.01-8.0   | 57        | 3.7%    |
| 5.01-6.0   | 24        | 1.56%   |
| 8.01-16.0  | 21        | 1.36%   |
| 2.01-3.0   | 15        | 0.97%   |
| 4.01-5.0   | 2         | 0.13%   |
| 16.01-24.0 | 2         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 213       | 13.59%  |
| AU Optronics            | 169       | 10.78%  |
| BOE                     | 145       | 9.25%   |
| LG Display              | 125       | 7.98%   |
| Chimei Innolux          | 105       | 6.7%    |
| Goldstar                | 93        | 5.93%   |
| Dell                    | 78        | 4.98%   |
| Acer                    | 64        | 4.08%   |
| Hewlett-Packard         | 63        | 4.02%   |
| Philips                 | 43        | 2.74%   |
| AOC                     | 37        | 2.36%   |
| BenQ                    | 35        | 2.23%   |
| Ancor Communications    | 29        | 1.85%   |
| Chi Mei Optoelectronics | 28        | 1.79%   |
| ViewSonic               | 25        | 1.6%    |
| Lenovo                  | 19        | 1.21%   |
| Iiyama                  | 19        | 1.21%   |
| Apple                   | 16        | 1.02%   |
| Sharp                   | 15        | 0.96%   |
| PANDA                   | 15        | 0.96%   |
| Sony                    | 14        | 0.89%   |
| InfoVision              | 14        | 0.89%   |
| ASUSTek Computer        | 14        | 0.89%   |
| NEC Computers           | 13        | 0.83%   |
| MSI                     | 11        | 0.7%    |
| Fujitsu Siemens         | 10        | 0.64%   |
| Panasonic               | 9         | 0.57%   |
| Eizo                    | 9         | 0.57%   |
| RTK                     | 7         | 0.45%   |
| Unknown                 | 6         | 0.38%   |
| Hitachi                 | 6         | 0.38%   |
| HannStar                | 6         | 0.38%   |
| Sceptre Tech            | 5         | 0.32%   |
| Medion                  | 5         | 0.32%   |
| LG Philips              | 5         | 0.32%   |
| HKC                     | 5         | 0.32%   |
| ___                     | 3         | 0.19%   |
| Unknown (XXX)           | 3         | 0.19%   |
| Toshiba                 | 3         | 0.19%   |
| STA                     | 3         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 6         | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.38%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 5         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.32%   |
| BOE LCD Monitor BOE0A84 1920x1200 286x179mm 13.3-inch                    | 5         | 0.32%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 5         | 0.32%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.32%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 4         | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.25%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.25%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 4         | 0.25%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 4         | 0.25%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch              | 4         | 0.25%   |
| Dell P2311H DEL4066 1920x1080 509x286mm 23.0-inch                        | 4         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 4         | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch            | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 4         | 0.25%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 4         | 0.25%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                         | 4         | 0.25%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch    | 4         | 0.25%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch            | 3         | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.19%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 3         | 0.19%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch                  | 3         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 683       | 44.26%  |
| 1366x768 (WXGA)    | 359       | 23.27%  |
| 3840x2160 (4K)     | 73        | 4.73%   |
| 1600x900 (HD+)     | 67        | 4.34%   |
| 2560x1440 (QHD)    | 50        | 3.24%   |
| 1280x1024 (SXGA)   | 46        | 2.98%   |
| 1920x1200 (WUXGA)  | 44        | 2.85%   |
| 1680x1050 (WSXGA+) | 44        | 2.85%   |
| 1440x900 (WXGA+)   | 43        | 2.79%   |
| 1280x800 (WXGA)    | 24        | 1.56%   |
| 3440x1440          | 11        | 0.71%   |
| 1360x768           | 11        | 0.71%   |
| 2560x1080          | 9         | 0.58%   |
| 2560x1600          | 8         | 0.52%   |
| 1600x1200          | 8         | 0.52%   |
| 1920x540           | 7         | 0.45%   |
| 1024x768 (XGA)     | 7         | 0.45%   |
| 2880x1800          | 6         | 0.39%   |
| 2288x1287          | 6         | 0.39%   |
| 2160x1440          | 6         | 0.39%   |
| 1280x720 (HD)      | 5         | 0.32%   |
| 1024x600           | 5         | 0.32%   |
| 3840x2400          | 3         | 0.19%   |
| 3200x1800 (QHD+)   | 3         | 0.19%   |
| 2736x1824          | 2         | 0.13%   |
| 2256x1504          | 2         | 0.13%   |
| 2048x1152          | 2         | 0.13%   |
| 1152x864           | 2         | 0.13%   |
| 3840x1600          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 2880x1920          | 1         | 0.06%   |
| 2880x1620          | 1         | 0.06%   |
| 2520x1680          | 1         | 0.06%   |
| 1920x1280          | 1         | 0.06%   |
| Unknown            | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 367       | 23.41%  |
| 23      | 127       | 8.1%    |
| 21      | 120       | 7.65%   |
| 24      | 115       | 7.33%   |
| 13      | 115       | 7.33%   |
| 14      | 107       | 6.82%   |
| 17      | 98        | 6.25%   |
| 27      | 95        | 6.06%   |
| 31      | 50        | 3.19%   |
| 19      | 46        | 2.93%   |
| 18      | 41        | 2.61%   |
| 22      | 34        | 2.17%   |
| 20      | 34        | 2.17%   |
| 12      | 31        | 1.98%   |
| 11      | 22        | 1.4%    |
| Unknown | 21        | 1.34%   |
| 84      | 16        | 1.02%   |
| 16      | 16        | 1.02%   |
| 34      | 14        | 0.89%   |
| 10      | 14        | 0.89%   |
| 72      | 13        | 0.83%   |
| 32      | 9         | 0.57%   |
| 54      | 7         | 0.45%   |
| 40      | 7         | 0.45%   |
| 28      | 6         | 0.38%   |
| 26      | 5         | 0.32%   |
| 25      | 5         | 0.32%   |
| 142     | 4         | 0.26%   |
| 39      | 4         | 0.26%   |
| 52      | 3         | 0.19%   |
| 46      | 3         | 0.19%   |
| 37      | 3         | 0.19%   |
| 48      | 2         | 0.13%   |
| 43      | 2         | 0.13%   |
| 33      | 2         | 0.13%   |
| 85      | 1         | 0.06%   |
| 74      | 1         | 0.06%   |
| 69      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 63      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 561       | 36.01%  |
| 501-600        | 333       | 21.37%  |
| 401-500        | 252       | 16.17%  |
| 201-300        | 122       | 7.83%   |
| 351-400        | 109       | 7%      |
| 601-700        | 62        | 3.98%   |
| 1501-2000      | 32        | 2.05%   |
| 701-800        | 25        | 1.6%    |
| Unknown        | 21        | 1.35%   |
| 1001-1500      | 19        | 1.22%   |
| 801-900        | 15        | 0.96%   |
| More than 2000 | 4         | 0.26%   |
| 901-1000       | 3         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1208      | 80.16%  |
| 16/10   | 183       | 12.14%  |
| 5/4     | 48        | 3.19%   |
| 4/3     | 19        | 1.26%   |
| 21/9    | 19        | 1.26%   |
| 3/2     | 18        | 1.19%   |
| Unknown | 7         | 0.46%   |
| 1.00    | 4         | 0.27%   |
| 32/9    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 365       | 23.37%  |
| 201-250        | 310       | 19.85%  |
| 81-90          | 172       | 11.01%  |
| 151-200        | 124       | 7.94%   |
| 301-350        | 100       | 6.4%    |
| 351-500        | 77        | 4.93%   |
| 121-130        | 64        | 4.1%    |
| 141-150        | 57        | 3.65%   |
| 251-300        | 54        | 3.46%   |
| 71-80          | 53        | 3.39%   |
| More than 1000 | 52        | 3.33%   |
| 61-70          | 25        | 1.6%    |
| 51-60          | 23        | 1.47%   |
| 501-1000       | 21        | 1.34%   |
| Unknown        | 21        | 1.34%   |
| 111-120        | 14        | 0.9%    |
| 41-50          | 13        | 0.83%   |
| 131-140        | 11        | 0.7%    |
| 91-100         | 6         | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 613       | 40.01%  |
| 101-120       | 459       | 29.96%  |
| 121-160       | 317       | 20.69%  |
| 161-240       | 70        | 4.57%   |
| 1-50          | 36        | 2.35%   |
| Unknown       | 21        | 1.37%   |
| More than 240 | 16        | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1381      | 89.56%  |
| 2     | 107       | 6.94%   |
| 0     | 46        | 2.98%   |
| 3     | 8         | 0.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 909       | 40.42%  |
| Intel                             | 655       | 29.12%  |
| Qualcomm Atheros                  | 267       | 11.87%  |
| Broadcom                          | 102       | 4.54%   |
| MediaTek                          | 37        | 1.65%   |
| TP-Link                           | 31        | 1.38%   |
| Ralink Technology                 | 28        | 1.24%   |
| Broadcom Limited                  | 23        | 1.02%   |
| Nvidia                            | 19        | 0.84%   |
| Ralink                            | 18        | 0.8%    |
| Marvell Technology Group          | 16        | 0.71%   |
| Qualcomm Atheros Communications   | 14        | 0.62%   |
| ASIX Electronics                  | 14        | 0.62%   |
| D-Link                            | 11        | 0.49%   |
| Dell                              | 9         | 0.4%    |
| Huawei Technologies               | 8         | 0.36%   |
| Samsung Electronics               | 7         | 0.31%   |
| Sierra Wireless                   | 6         | 0.27%   |
| NetGear                           | 6         | 0.27%   |
| JMicron Technology                | 6         | 0.27%   |
| OPPO Electronics                  | 5         | 0.22%   |
| Ericsson Business Mobile Networks | 5         | 0.22%   |
| ASUSTek Computer                  | 4         | 0.18%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.13%   |
| Qualcomm                          | 3         | 0.13%   |
| Microchip Technology              | 3         | 0.13%   |
| DisplayLink                       | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.09%   |
| Motorola PCS                      | 2         | 0.09%   |
| Mercucys                          | 2         | 0.09%   |
| Lenovo                            | 2         | 0.09%   |
| ICS Advent                        | 2         | 0.09%   |
| Hewlett-Packard                   | 2         | 0.09%   |
| D-Link System                     | 2         | 0.09%   |
| BUFFALO                           | 2         | 0.09%   |
| Belkin Components                 | 2         | 0.09%   |
| AVM                               | 2         | 0.09%   |
| Xiaomi                            | 1         | 0.04%   |
| VIA Technologies                  | 1         | 0.04%   |
| U-Blox                            | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 624       | 23.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 121       | 4.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 77        | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 57        | 2.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 43        | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 41        | 1.57%   |
| Intel Wireless 8265 / 8275                                             | 41        | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                      | 35        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 34        | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 34        | 1.3%    |
| Intel Wireless 7265                                                    | 32        | 1.23%   |
| Intel Ethernet Connection I217-LM                                      | 32        | 1.23%   |
| Intel Wi-Fi 6 AX200                                                    | 31        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.11%   |
| Intel Wireless 7260                                                    | 26        | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 25        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 21        | 0.81%   |
| Intel Wireless 8260                                                    | 21        | 0.81%   |
| Intel Wi-Fi 6 AX201                                                    | 21        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 21        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 21        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 20        | 0.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 20        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                        | 19        | 0.73%   |
| Intel Ethernet Connection (4) I219-LM                                  | 19        | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 17        | 0.65%   |
| Intel Wireless 3165                                                    | 17        | 0.65%   |
| Intel Ethernet Controller I225-V                                       | 17        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 17        | 0.65%   |
| Intel 82579V Gigabit Network Connection                                | 17        | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 15        | 0.58%   |
| Intel Wireless 3160                                                    | 14        | 0.54%   |
| Intel Ethernet Connection I217-V                                       | 14        | 0.54%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 13        | 0.5%    |
| Intel Ethernet Connection I219-LM                                      | 13        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                  | 13        | 0.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 13        | 0.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 12        | 0.46%   |
| Realtek 802.11ac NIC                                                   | 12        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 456       | 40.46%  |
| Realtek Semiconductor           | 230       | 20.41%  |
| Qualcomm Atheros                | 200       | 17.75%  |
| Broadcom                        | 57        | 5.06%   |
| MediaTek                        | 36        | 3.19%   |
| TP-Link                         | 28        | 2.48%   |
| Ralink Technology               | 28        | 2.48%   |
| Ralink                          | 18        | 1.6%    |
| Qualcomm Atheros Communications | 14        | 1.24%   |
| Broadcom Limited                | 12        | 1.06%   |
| D-Link                          | 11        | 0.98%   |
| Sierra Wireless                 | 6         | 0.53%   |
| NetGear                         | 6         | 0.53%   |
| ASUSTek Computer                | 4         | 0.35%   |
| Dell                            | 3         | 0.27%   |
| Mercucys                        | 2         | 0.18%   |
| D-Link System                   | 2         | 0.18%   |
| BUFFALO                         | 2         | 0.18%   |
| Belkin Components               | 2         | 0.18%   |
| AVM                             | 2         | 0.18%   |
| Tenda                           | 1         | 0.09%   |
| Qualcomm                        | 1         | 0.09%   |
| Microsoft                       | 1         | 0.09%   |
| Marvell Technology Group        | 1         | 0.09%   |
| Fujitsu Siemens Computers       | 1         | 0.09%   |
| Fibocom                         | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |
| CyberTAN Technology             | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 57        | 5.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 43        | 3.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 41        | 3.63%   |
| Intel Wireless 8265 / 8275                                     | 41        | 3.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 34        | 3.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 34        | 3.01%   |
| Intel Wireless 7265                                            | 32        | 2.83%   |
| Intel Wi-Fi 6 AX200                                            | 31        | 2.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 29        | 2.57%   |
| Intel Wireless 7260                                            | 26        | 2.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 2.21%   |
| Intel Wireless 8260                                            | 21        | 1.86%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 1.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 21        | 1.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 20        | 1.77%   |
| Ralink MT7601U Wireless Adapter                                | 19        | 1.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 17        | 1.51%   |
| Intel Wireless 3165                                            | 17        | 1.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 1.33%   |
| Intel Wireless 3160                                            | 14        | 1.24%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 13        | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 13        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 12        | 1.06%   |
| Realtek 802.11ac NIC                                           | 12        | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 12        | 1.06%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 11        | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                | 10        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 10        | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9         | 0.8%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 9         | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 9         | 0.8%    |
| Intel Centrino Advanced-N 6200                                 | 9         | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 8         | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8         | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 807       | 56.71%  |
| Intel                             | 357       | 25.09%  |
| Qualcomm Atheros                  | 91        | 6.39%   |
| Broadcom                          | 58        | 4.08%   |
| Nvidia                            | 19        | 1.34%   |
| Marvell Technology Group          | 15        | 1.05%   |
| ASIX Electronics                  | 14        | 0.98%   |
| Broadcom Limited                  | 11        | 0.77%   |
| Samsung Electronics               | 6         | 0.42%   |
| JMicron Technology                | 6         | 0.42%   |
| Huawei Technologies               | 6         | 0.42%   |
| OPPO Electronics                  | 5         | 0.35%   |
| TP-Link                           | 3         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.21%   |
| Microchip Technology              | 3         | 0.21%   |
| DisplayLink                       | 3         | 0.21%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.14%   |
| Qualcomm                          | 2         | 0.14%   |
| Lenovo                            | 2         | 0.14%   |
| ICS Advent                        | 2         | 0.14%   |
| Xiaomi                            | 1         | 0.07%   |
| VIA Technologies                  | 1         | 0.07%   |
| Sundance Technology Inc / IC Plus | 1         | 0.07%   |
| MediaTek                          | 1         | 0.07%   |
| LG Electronics                    | 1         | 0.07%   |
| Attansic Technology               | 1         | 0.07%   |
| Apple                             | 1         | 0.07%   |
| 3Com                              | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 624       | 42.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 121       | 8.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 77        | 5.29%   |
| Realtek RTL8125 2.5GbE Controller                                      | 35        | 2.41%   |
| Intel Ethernet Connection I217-LM                                      | 32        | 2.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 21        | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 20        | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                                  | 19        | 1.31%   |
| Intel Ethernet Controller I225-V                                       | 17        | 1.17%   |
| Intel Ethernet Connection (2) I219-V                                   | 17        | 1.17%   |
| Intel 82579V Gigabit Network Connection                                | 17        | 1.17%   |
| Intel Ethernet Connection I217-V                                       | 14        | 0.96%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                                  | 13        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 11        | 0.76%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.76%   |
| Intel 82577LM Gigabit Network Connection                               | 11        | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                          | 11        | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 9         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                               | 9         | 0.62%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 9         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 8         | 0.55%   |
| Nvidia MCP61 Ethernet                                                  | 8         | 0.55%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 0.55%   |
| Intel Ethernet Connection (7) I219-V                                   | 8         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 0.55%   |
| Intel 82574L Gigabit Network Connection                                | 8         | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 8         | 0.55%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 0.55%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 8         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.48%   |
| Intel 82578DM Gigabit Network Connection                               | 7         | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 7         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 6         | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 6         | 0.41%   |
| Intel I210 Gigabit Network Connection                                  | 6         | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                                  | 6         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 5         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1368      | 55.3%   |
| WiFi     | 1084      | 43.82%  |
| Modem    | 19        | 0.77%   |
| Unknown  | 3         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 796       | 52.37%  |
| WiFi     | 724       | 47.63%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 770       | 49.94%  |
| 1     | 726       | 47.08%  |
| 3     | 23        | 1.49%   |
| 0     | 21        | 1.36%   |
| 4     | 2         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 985       | 63.88%  |
| Yes  | 557       | 36.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 362       | 42.69%  |
| Realtek Semiconductor           | 115       | 13.56%  |
| Qualcomm Atheros Communications | 76        | 8.96%   |
| Cambridge Silicon Radio         | 60        | 7.08%   |
| Foxconn / Hon Hai               | 39        | 4.6%    |
| Broadcom                        | 37        | 4.36%   |
| IMC Networks                    | 34        | 4.01%   |
| Lite-On Technology              | 31        | 3.66%   |
| Apple                           | 19        | 2.24%   |
| Dell                            | 12        | 1.42%   |
| MediaTek                        | 11        | 1.3%    |
| Hewlett-Packard                 | 9         | 1.06%   |
| Toshiba                         | 8         | 0.94%   |
| TP-Link                         | 7         | 0.83%   |
| ASUSTek Computer                | 7         | 0.83%   |
| Ralink                          | 5         | 0.59%   |
| Unknown                         | 4         | 0.47%   |
| USI                             | 2         | 0.24%   |
| Integrated System Solution      | 2         | 0.24%   |
| Realtek                         | 1         | 0.12%   |
| Micro Star International        | 1         | 0.12%   |
| Marvell Semiconductor           | 1         | 0.12%   |
| Fujitsu                         | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Dynex                           | 1         | 0.12%   |
| Alps Electric                   | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 146       | 17.22%  |
| Realtek Bluetooth Radio                                                             | 80        | 9.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 60        | 7.08%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 54        | 6.37%   |
| Intel AX201 Bluetooth                                                               | 46        | 5.42%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 36        | 4.25%   |
| Intel AX200 Bluetooth                                                               | 30        | 3.54%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 29        | 3.42%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 21        | 2.48%   |
| Intel Bluetooth Device                                                              | 19        | 2.24%   |
| Intel AX210 Bluetooth                                                               | 18        | 2.12%   |
| IMC Networks Bluetooth Radio                                                        | 18        | 2.12%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 1.77%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 15        | 1.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 13        | 1.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 12        | 1.42%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 11        | 1.3%    |
| MediaTek Wireless_Device                                                            | 10        | 1.18%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 10        | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.06%   |
| Lite-On Bluetooth Device                                                            | 9         | 1.06%   |
| Apple Bluetooth Host Controller                                                     | 9         | 1.06%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 8         | 0.94%   |
| TP-Link UB500 Adapter                                                               | 7         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 7         | 0.83%   |
| IMC Networks Bluetooth Device                                                       | 7         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.71%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 6         | 0.71%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.71%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 0.71%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 0.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.59%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.59%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.47%   |
| Lite-On Wireless_Device                                                             | 4         | 0.47%   |
| IMC Networks Wireless_Device                                                        | 4         | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 0.47%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1150      | 56.71%  |
| AMD                                          | 434       | 21.4%   |
| Nvidia                                       | 307       | 15.14%  |
| C-Media Electronics                          | 32        | 1.58%   |
| Creative Labs                                | 11        | 0.54%   |
| Texas Instruments                            | 7         | 0.35%   |
| Realtek Semiconductor                        | 5         | 0.25%   |
| Generalplus Technology                       | 5         | 0.25%   |
| JMTek                                        | 4         | 0.2%    |
| GN Netcom                                    | 4         | 0.2%    |
| Creative Technology                          | 4         | 0.2%    |
| ASUSTek Computer                             | 4         | 0.2%    |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.15%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.15%   |
| M-Audio                                      | 3         | 0.15%   |
| TerraTec Electronic                          | 2         | 0.1%    |
| SAVITECH                                     | 2         | 0.1%    |
| Razer USA                                    | 2         | 0.1%    |
| Logitech                                     | 2         | 0.1%    |
| Lenovo                                       | 2         | 0.1%    |
| KTMicro                                      | 2         | 0.1%    |
| Kingston Technology                          | 2         | 0.1%    |
| GYROCOM C&C                                  | 2         | 0.1%    |
| Focusrite-Novation                           | 2         | 0.1%    |
| FiiO Electronics Technology                  | 2         | 0.1%    |
| BR23                                         | 2         | 0.1%    |
| ATI Technologies                             | 2         | 0.1%    |
| Xilinx                                       | 1         | 0.05%   |
| VIA Technologies                             | 1         | 0.05%   |
| Valve Software                               | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.05%   |
| Tenx Technology                              | 1         | 0.05%   |
| somic                                        | 1         | 0.05%   |
| Samson Technologies                          | 1         | 0.05%   |
| PreSonus Audio Electronics                   | 1         | 0.05%   |
| ONN                                          | 1         | 0.05%   |
| Nordic Semiconductor ASA                     | 1         | 0.05%   |
| Native Instruments                           | 1         | 0.05%   |
| MosArt Semiconductor                         | 1         | 0.05%   |
| Microsoft                                    | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 148       | 6.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 128       | 5.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 127       | 5.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 103       | 4.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 93        | 3.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 71        | 2.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 71        | 2.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 71        | 2.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 64        | 2.61%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 56        | 2.28%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 54        | 2.2%    |
| AMD Starship/Matisse HD Audio Controller                                   | 46        | 1.88%   |
| AMD FCH Azalia Controller                                                  | 43        | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 40        | 1.63%   |
| Intel 8 Series HD Audio Controller                                         | 40        | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 38        | 1.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 36        | 1.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 36        | 1.47%   |
| Intel 200 Series PCH HD Audio                                              | 36        | 1.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 35        | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                              | 32        | 1.3%    |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 1.18%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29        | 1.18%   |
| Nvidia High Definition Audio Controller                                    | 27        | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 27        | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 27        | 1.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 26        | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 26        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 23        | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21        | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 21        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 18        | 0.73%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 17        | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 17        | 0.69%   |
| Intel Jasper Lake HD Audio                                                 | 16        | 0.65%   |
| Intel Comet Lake PCH-LP cAVS                                               | 16        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 16        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 353       | 19.05%  |
| SK hynix                     | 261       | 14.09%  |
| Kingston                     | 230       | 12.41%  |
| Unknown                      | 200       | 10.79%  |
| Micron Technology            | 179       | 9.66%   |
| Crucial                      | 96        | 5.18%   |
| Corsair                      | 74        | 3.99%   |
| G.Skill                      | 54        | 2.91%   |
| A-DATA Technology            | 39        | 2.1%    |
| Ramaxel Technology           | 35        | 1.89%   |
| Unknown                      | 31        | 1.67%   |
| Smart                        | 30        | 1.62%   |
| Elpida                       | 30        | 1.62%   |
| Nanya Technology             | 26        | 1.4%    |
| Patriot                      | 19        | 1.03%   |
| Unknown (ABCD)               | 18        | 0.97%   |
| Team                         | 13        | 0.7%    |
| GOODRAM                      | 12        | 0.65%   |
| Apacer                       | 12        | 0.65%   |
| AMD                          | 11        | 0.59%   |
| Transcend                    | 10        | 0.54%   |
| Kllisre                      | 5         | 0.27%   |
| Atermiter                    | 5         | 0.27%   |
| ASint Technology             | 5         | 0.27%   |
| Unknown (0x0E9D)             | 4         | 0.22%   |
| Teikon                       | 4         | 0.22%   |
| High Bridge                  | 4         | 0.22%   |
| 4ea5                         | 4         | 0.22%   |
| 48spaces                     | 4         | 0.22%   |
| V-GeN                        | 3         | 0.16%   |
| Smart Brazil                 | 3         | 0.16%   |
| Silicon Power                | 3         | 0.16%   |
| PNY                          | 3         | 0.16%   |
| Patriot Memory (PDP Systems) | 3         | 0.16%   |
| Avant                        | 3         | 0.16%   |
| Wodposit                     | 2         | 0.11%   |
| Unknown (0x7FFF)             | 2         | 0.11%   |
| Thermaltake                  | 2         | 0.11%   |
| Red Hat                      | 2         | 0.11%   |
| Neo Forza                    | 2         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 31        | 1.54%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 17        | 0.84%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 17        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 15        | 0.74%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 13        | 0.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 13        | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 13        | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 13        | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 11        | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 11        | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 10        | 0.5%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                 | 10        | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 10        | 0.5%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                            | 9         | 0.45%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 9         | 0.45%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 0.45%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s            | 9         | 0.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 9         | 0.45%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                           | 8         | 0.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 8         | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 8         | 0.4%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 8         | 0.4%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 7         | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 7         | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                 | 7         | 0.35%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                            | 7         | 0.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 7         | 0.35%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 7         | 0.35%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 6         | 0.3%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                | 6         | 0.3%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 6         | 0.3%    |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 6         | 0.3%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 6         | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 6         | 0.3%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 6         | 0.3%    |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s                 | 6         | 0.3%    |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 6         | 0.3%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 6         | 0.3%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 6         | 0.3%    |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s               | 6         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 648       | 41.62%  |
| DDR4    | 601       | 38.6%   |
| DDR2    | 76        | 4.88%   |
| Unknown | 61        | 3.92%   |
| SDRAM   | 58        | 3.73%   |
| LPDDR4  | 48        | 3.08%   |
| DDR5    | 19        | 1.22%   |
| LPDDR5  | 16        | 1.03%   |
| LPDDR3  | 11        | 0.71%   |
| DDR     | 10        | 0.64%   |
| DRAM    | 7         | 0.45%   |
| RAM     | 2         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 808       | 52.33%  |
| DIMM            | 661       | 42.81%  |
| Row Of Chips    | 63        | 4.08%   |
| Unknown         | 8         | 0.52%   |
| Chip            | 2         | 0.13%   |
| RIMM            | 1         | 0.06%   |
| Proprietary Car | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 606       | 34.93%  |
| 4096  | 572       | 32.97%  |
| 2048  | 286       | 16.48%  |
| 16384 | 163       | 9.39%   |
| 1024  | 59        | 3.4%    |
| 32768 | 41        | 2.36%   |
| 512   | 5         | 0.29%   |
| 65536 | 1         | 0.06%   |
| 15616 | 1         | 0.06%   |
| 12333 | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 416       | 23.94%  |
| 3200    | 201       | 11.57%  |
| 2667    | 187       | 10.76%  |
| 1333    | 152       | 8.75%   |
| 2400    | 121       | 6.96%   |
| 1334    | 85        | 4.89%   |
| 2133    | 68        | 3.91%   |
| 667     | 49        | 2.82%   |
| 800     | 45        | 2.59%   |
| Unknown | 35        | 2.01%   |
| 3600    | 34        | 1.96%   |
| 1867    | 27        | 1.55%   |
| 1067    | 25        | 1.44%   |
| 1066    | 19        | 1.09%   |
| 4800    | 15        | 0.86%   |
| 3733    | 15        | 0.86%   |
| 2666    | 15        | 0.86%   |
| 6400    | 14        | 0.81%   |
| 3266    | 14        | 0.81%   |
| 1866    | 13        | 0.75%   |
| 1800    | 13        | 0.75%   |
| 400     | 12        | 0.69%   |
| 4267    | 11        | 0.63%   |
| 2933    | 11        | 0.63%   |
| 533     | 10        | 0.58%   |
| 4199    | 9         | 0.52%   |
| 3800    | 9         | 0.52%   |
| 2048    | 7         | 0.4%    |
| 975     | 7         | 0.4%    |
| 3466    | 6         | 0.35%   |
| 3400    | 6         | 0.35%   |
| 3000    | 6         | 0.35%   |
| 1648    | 6         | 0.35%   |
| 333     | 6         | 0.35%   |
| 4266    | 5         | 0.29%   |
| 3866    | 5         | 0.29%   |
| 2132    | 4         | 0.23%   |
| 2000    | 4         | 0.23%   |
| 8400    | 3         | 0.17%   |
| 4000    | 3         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 19        | 38.78%  |
| Canon                 | 8         | 16.33%  |
| Brother Industries    | 8         | 16.33%  |
| Samsung Electronics   | 5         | 10.2%   |
| Seiko Epson           | 4         | 8.16%   |
| Prolific Technology   | 2         | 4.08%   |
| Oki Data              | 1         | 2.04%   |
| Lexmark International | 1         | 2.04%   |
| Apple                 | 1         | 2.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP DeskJet 4100 series               | 3         | 6%      |
| HP DeskJet 2600 series               | 3         | 6%      |
| Prolific PL2305 Parallel Port        | 2         | 4%      |
| Brother HL-L2350DW series            | 2         | 4%      |
| Seiko Epson L3210 Series             | 1         | 2%      |
| Seiko Epson L3150 Series             | 1         | 2%      |
| Seiko Epson L120 Series              | 1         | 2%      |
| Seiko Epson ET-4850 Series           | 1         | 2%      |
| Samsung SCX-6x55X Series             | 1         | 2%      |
| Samsung ML-1865                      | 1         | 2%      |
| Samsung ML-1640 Series Laser Printer | 1         | 2%      |
| Samsung M2020 Series                 | 1         | 2%      |
| Samsung Composite Device             | 1         | 2%      |
| Oki Data MC363 Multifunction Printer | 1         | 2%      |
| Lexmark International MS510dn        | 1         | 2%      |
| HP OfficeJet Pro 6960                | 1         | 2%      |
| HP Officejet J4500 series            | 1         | 2%      |
| HP OfficeJet 8010 series             | 1         | 2%      |
| HP OfficeJet 3830 series             | 1         | 2%      |
| HP LaserJet 1020                     | 1         | 2%      |
| HP LaserJet 1015                     | 1         | 2%      |
| HP HP LaserJet M14-M17               | 1         | 2%      |
| HP DeskJet Plus 6400 series          | 1         | 2%      |
| HP DeskJet 6940 series               | 1         | 2%      |
| HP DeskJet 4530 series               | 1         | 2%      |
| HP DeskJet 3700 series               | 1         | 2%      |
| HP DeskJet 3630 series               | 1         | 2%      |
| HP DeskJet 2700 series               | 1         | 2%      |
| HP Color LaserJet CP1215             | 1         | 2%      |
| Canon PIXMA MG3600 Series            | 1         | 2%      |
| Canon MF4010 series                  | 1         | 2%      |
| Canon MF110/910 Series               | 1         | 2%      |
| Canon LiDE 400                       | 1         | 2%      |
| Canon LBP2900                        | 1         | 2%      |
| Canon G4010 series                   | 1         | 2%      |
| Canon G3010 series                   | 1         | 2%      |
| Canon G2020 series                   | 1         | 2%      |
| Brother QL-600 Label Printer         | 1         | 2%      |
| Brother MFC-L6900DW series           | 1         | 2%      |
| Brother MFC-L2690DW                  | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 66.67%  |
| Hewlett-Packard | 2         | 22.22%  |
| Seiko Epson     | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 11.11%  |
| HP Scanjet G2710                                  | 1         | 11.11%  |
| HP ScanJet 2400c                                  | 1         | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20                | 1         | 11.11%  |
| Canon CanoScan N650U/N656U                        | 1         | 11.11%  |
| Canon CanoScan LIDE 25                            | 1         | 11.11%  |
| Canon CanoScan LiDE 220                           | 1         | 11.11%  |
| Canon CanoScan LiDE 110                           | 1         | 11.11%  |
| Canon CanoScan 1220U                              | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 169       | 22.01%  |
| Microdia                               | 74        | 9.64%   |
| IMC Networks                           | 66        | 8.59%   |
| Realtek Semiconductor                  | 51        | 6.64%   |
| Bison Electronics                      | 51        | 6.64%   |
| Quanta                                 | 38        | 4.95%   |
| Sunplus Innovation Technology          | 31        | 4.04%   |
| Logitech                               | 29        | 3.78%   |
| Cheng Uei Precision Industry (Foxlink) | 24        | 3.13%   |
| Acer                                   | 24        | 3.13%   |
| Suyin                                  | 23        | 2.99%   |
| Syntek                                 | 22        | 2.86%   |
| Luxvisions Innotech Limited            | 14        | 1.82%   |
| Apple                                  | 14        | 1.82%   |
| Silicon Motion                         | 13        | 1.69%   |
| Alcor Micro                            | 12        | 1.56%   |
| Z-Star Microelectronics                | 9         | 1.17%   |
| Lite-On Technology                     | 8         | 1.04%   |
| Microsoft                              | 7         | 0.91%   |
| Lenovo                                 | 7         | 0.91%   |
| ALi                                    | 7         | 0.91%   |
| Importek                               | 6         | 0.78%   |
| Unknown                                | 4         | 0.52%   |
| SunplusIT                              | 4         | 0.52%   |
| Sonix Technology                       | 4         | 0.52%   |
| Ricoh                                  | 4         | 0.52%   |
| USB Camera                             | 3         | 0.39%   |
| Tripath Technology                     | 3         | 0.39%   |
| Hewlett-Packard                        | 3         | 0.39%   |
| DigiTech                               | 3         | 0.39%   |
| Y Media                                | 2         | 0.26%   |
| OYT Tech                               | 2         | 0.26%   |
| kingcome                               | 2         | 0.26%   |
| Genesys Logic                          | 2         | 0.26%   |
| Generalplus Technology                 | 2         | 0.26%   |
| GEMBIRD                                | 2         | 0.26%   |
| Creative Technology                    | 2         | 0.26%   |
| Arkmicro Technologies                  | 2         | 0.26%   |
| ARC International                      | 2         | 0.26%   |
| webcamvendor                           | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 30        | 3.88%   |
| Microdia Integrated_Webcam_HD                                  | 17        | 2.2%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 17        | 2.2%    |
| Syntek Integrated Camera                                       | 16        | 2.07%   |
| Realtek Integrated_Webcam_HD                                   | 15        | 1.94%   |
| Chicony HD WebCam                                              | 15        | 1.94%   |
| Bison Integrated Camera                                        | 14        | 1.81%   |
| IMC Networks Integrated Camera                                 | 12        | 1.55%   |
| Acer Integrated Camera                                         | 11        | 1.42%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 10        | 1.29%   |
| Chicony HP TrueVision HD Camera                                | 10        | 1.29%   |
| Sunplus Integrated_Webcam_HD                                   | 9         | 1.16%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 9         | 1.16%   |
| Quanta HD User Facing                                          | 8         | 1.03%   |
| Microdia USB 2.0 Camera                                        | 8         | 1.03%   |
| Logitech Webcam C270                                           | 8         | 1.03%   |
| Bison Lenovo EasyCamera                                        | 8         | 1.03%   |
| Realtek USB Camera                                             | 7         | 0.91%   |
| Chicony USB2.0 HD UVC WebCam                                   | 7         | 0.91%   |
| Chicony HP HD Webcam                                           | 7         | 0.91%   |
| ALi Gateway Webcam                                             | 7         | 0.91%   |
| Silicon Motion Web Camera                                      | 6         | 0.78%   |
| Microdia Integrated Webcam                                     | 6         | 0.78%   |
| Chicony USB 2.0 Camera                                         | 6         | 0.78%   |
| Chicony HP HD Camera                                           | 6         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 6         | 0.78%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 6         | 0.78%   |
| Bison Lenovo Integrated Webcam                                 | 6         | 0.78%   |
| Bison HD Webcam                                                | 6         | 0.78%   |
| Bison BisonCam, NB Pro                                         | 6         | 0.78%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 5         | 0.65%   |
| Quanta VGA WebCam                                              | 5         | 0.65%   |
| Quanta HP Webcam                                               | 5         | 0.65%   |
| Microdia Webcam Vitade AF                                      | 5         | 0.65%   |
| Microdia Lenovo EasyCamera                                     | 5         | 0.65%   |
| Microdia HP Integrated Webcam                                  | 5         | 0.65%   |
| IMC Networks Integrated Webcam                                 | 5         | 0.65%   |
| Chicony VGA WebCam                                             | 5         | 0.65%   |
| Chicony EasyCamera                                             | 5         | 0.65%   |
| Apple FaceTime HD Camera (Built-in)                            | 5         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 46        | 42.59%  |
| Synaptics                          | 17        | 15.74%  |
| Upek                               | 12        | 11.11%  |
| AuthenTec                          | 10        | 9.26%   |
| Shenzhen Goodix Technology         | 7         | 6.48%   |
| LighTuning Technology              | 7         | 6.48%   |
| Elan Microelectronics              | 5         | 4.63%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.85%   |
| Focal-systems.Corp                 | 2         | 1.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 9.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 9.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 5.56%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 4.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.63%   |
| AuthenTec AES2810                                                          | 5         | 4.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.7%    |
| Validity Sensors VFS491                                                    | 4         | 3.7%    |
| Synaptics WBDI                                                             | 4         | 3.7%    |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.78%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.78%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.78%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 2.78%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.78%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.78%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 2.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.85%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 1.85%   |
| Synaptics  WBDI                                                            | 2         | 1.85%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.85%   |
| LighTuning Fingerprint Sensor                                              | 2         | 1.85%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 2         | 1.85%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.93%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.93%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.93%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.93%   |
| Synaptics Fingerprint scanner                                              | 1         | 0.93%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.93%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 26        | 52%     |
| Alcor Micro           | 7         | 14%     |
| O2 Micro              | 4         | 8%      |
| Upek                  | 3         | 6%      |
| SCM Microsystems      | 2         | 4%      |
| Lenovo                | 2         | 4%      |
| Gemalto (was Gemplus) | 2         | 4%      |
| OmniKey               | 1         | 2%      |
| Chicony Electronics   | 1         | 2%      |
| Cherry                | 1         | 2%      |
| Advanced Card Systems | 1         | 2%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 28%     |
| Broadcom 5880                                                                | 9         | 18%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 14%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 8%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6%      |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 4%      |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 2%      |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 2%      |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 2%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2%      |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 2%      |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 2%      |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 2%      |
| Broadcom 58200                                                               | 1         | 2%      |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1272      | 82.49%  |
| 1     | 230       | 14.92%  |
| 2     | 35        | 2.27%   |
| 3     | 5         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 108       | 35.88%  |
| Graphics card            | 78        | 25.91%  |
| Chipcard                 | 47        | 15.61%  |
| Net/wireless             | 16        | 5.32%   |
| Multimedia controller    | 16        | 5.32%   |
| Communication controller | 9         | 2.99%   |
| Unassigned class         | 8         | 2.66%   |
| Storage                  | 8         | 2.66%   |
| Bluetooth                | 7         | 2.33%   |
| Card reader              | 2         | 0.66%   |
| Storage/raid             | 1         | 0.33%   |
| Network                  | 1         | 0.33%   |


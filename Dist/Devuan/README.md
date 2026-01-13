Devuan - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Devuan.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Devuan/Desktop/README.md) and [notebooks](/Dist/Devuan/Notebook/README.md).

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

Total: 382

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga Slim 7 15ILL9 83HM     | Notebook    | [0e189c5b46](https://linux-hardware.org/?probe=0e189c5b46) | Dec 14, 2025 |
| HP            | 304Ah                       | Desktop     | [71dfdb19f6](https://linux-hardware.org/?probe=71dfdb19f6) | Dec 11, 2025 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ed4340cd1a](https://linux-hardware.org/?probe=ed4340cd1a) | Dec 05, 2025 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [9431b767be](https://linux-hardware.org/?probe=9431b767be) | Dec 03, 2025 |
| Gigabyte      | B85M-D3H                    | Desktop     | [31b2a1f884](https://linux-hardware.org/?probe=31b2a1f884) | Nov 23, 2025 |
| OrangePi      | Zero2 W                     | Soc         | [5e8ef52768](https://linux-hardware.org/?probe=5e8ef52768) | Nov 22, 2025 |
| Dell          | 0D4MD1 A00                  | Desktop     | [b691fc2880](https://linux-hardware.org/?probe=b691fc2880) | Nov 19, 2025 |
| IBM           | ThinkPad X40 23718EU        | Notebook    | [b7760d34a4](https://linux-hardware.org/?probe=b7760d34a4) | Oct 24, 2025 |
| ASUSTek       | Pro WS W790-ACE             | Desktop     | [2e0f05a7d9](https://linux-hardware.org/?probe=2e0f05a7d9) | Oct 23, 2025 |
| Dell          | Latitude 7275               | Notebook    | [7f37b4132b](https://linux-hardware.org/?probe=7f37b4132b) | Oct 21, 2025 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [ac0f8b3712](https://linux-hardware.org/?probe=ac0f8b3712) | Oct 20, 2025 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [c2ec807464](https://linux-hardware.org/?probe=c2ec807464) | Oct 20, 2025 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0899ddb6b6](https://linux-hardware.org/?probe=0899ddb6b6) | Oct 16, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [b31b577b75](https://linux-hardware.org/?probe=b31b577b75) | Oct 13, 2025 |
| MSI           | X570-A PRO                  | Desktop     | [d68db2f7ee](https://linux-hardware.org/?probe=d68db2f7ee) | Oct 06, 2025 |
| Lenovo        | ThinkServer TS440           | Desktop     | [173f941c64](https://linux-hardware.org/?probe=173f941c64) | Sep 30, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [5eea17a71a](https://linux-hardware.org/?probe=5eea17a71a) | Sep 30, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [32b0946cac](https://linux-hardware.org/?probe=32b0946cac) | Sep 25, 2025 |
| Intel         | H81U                        | Notebook    | [3453a83029](https://linux-hardware.org/?probe=3453a83029) | Sep 17, 2025 |
| Lenovo        | G710 20252                  | Notebook    | [4d96941694](https://linux-hardware.org/?probe=4d96941694) | Sep 09, 2025 |
| AZW           | Gemini T34-M                | Desktop     | [65e7e08bef](https://linux-hardware.org/?probe=65e7e08bef) | Sep 06, 2025 |
| AZW           | Gemini T34-M                | Desktop     | [3a5389f512](https://linux-hardware.org/?probe=3a5389f512) | Sep 06, 2025 |
| Unknown       | X99-D8                      | Desktop     | [42431a020f](https://linux-hardware.org/?probe=42431a020f) | Sep 04, 2025 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [0327b16100](https://linux-hardware.org/?probe=0327b16100) | Sep 01, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [059fb4f7bb](https://linux-hardware.org/?probe=059fb4f7bb) | Aug 31, 2025 |
| Dell          | MXC051                      | Notebook    | [1aa114333f](https://linux-hardware.org/?probe=1aa114333f) | Aug 31, 2025 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e8330e8df4](https://linux-hardware.org/?probe=e8330e8df4) | Aug 26, 2025 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [da9ad1e52b](https://linux-hardware.org/?probe=da9ad1e52b) | Aug 26, 2025 |
| Lenovo        | ThinkServer TS440           | Desktop     | [4030534b99](https://linux-hardware.org/?probe=4030534b99) | Aug 23, 2025 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [60fc6d703e](https://linux-hardware.org/?probe=60fc6d703e) | Aug 16, 2025 |
| VIT           | M2420                       | Notebook    | [8b9406ab14](https://linux-hardware.org/?probe=8b9406ab14) | Aug 15, 2025 |
| Gigabyte      | G1.Guerrilla                | Desktop     | [1d70f31076](https://linux-hardware.org/?probe=1d70f31076) | Aug 05, 2025 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [7c7ef95c5c](https://linux-hardware.org/?probe=7c7ef95c5c) | Aug 04, 2025 |
| AZW           | U59                         | Desktop     | [675db42ec7](https://linux-hardware.org/?probe=675db42ec7) | Aug 01, 2025 |
| MSI           | X570-A PRO                  | Desktop     | [b15e25dd23](https://linux-hardware.org/?probe=b15e25dd23) | Jul 30, 2025 |
| Lenovo        | ThinkServer TS440           | Desktop     | [3dd29d877f](https://linux-hardware.org/?probe=3dd29d877f) | Jul 28, 2025 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [9619058707](https://linux-hardware.org/?probe=9619058707) | Jul 15, 2025 |
| Acer          | Aspire A515-54              | Notebook    | [26cea0bfd2](https://linux-hardware.org/?probe=26cea0bfd2) | Jul 10, 2025 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [8491558d46](https://linux-hardware.org/?probe=8491558d46) | Jul 03, 2025 |
| Gigabyte      | B760 GAMING X AX            | Desktop     | [31d6778bbe](https://linux-hardware.org/?probe=31d6778bbe) | Jul 03, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [04f2a9918d](https://linux-hardware.org/?probe=04f2a9918d) | Jul 02, 2025 |
| ASUSTek       | X555LA                      | Notebook    | [132f009cef](https://linux-hardware.org/?probe=132f009cef) | Jun 25, 2025 |
| HP            | Pavilion dv2700             | Notebook    | [54c8c3e9ce](https://linux-hardware.org/?probe=54c8c3e9ce) | Jun 22, 2025 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [1374490476](https://linux-hardware.org/?probe=1374490476) | Jun 19, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7ce7e3285a](https://linux-hardware.org/?probe=7ce7e3285a) | Jun 08, 2025 |
| MSI           | Modern 15 A5M               | Notebook    | [9ce8e5a8ff](https://linux-hardware.org/?probe=9ce8e5a8ff) | May 18, 2025 |
| AVERATEC      | E1200                       | Notebook    | [472c4b84ed](https://linux-hardware.org/?probe=472c4b84ed) | May 16, 2025 |
| ASUSTek       | K50IE                       | Notebook    | [9f21e8de10](https://linux-hardware.org/?probe=9f21e8de10) | May 08, 2025 |
| Lenovo        | IdeaPad Y550 20017          | Notebook    | [ab679a51db](https://linux-hardware.org/?probe=ab679a51db) | Apr 16, 2025 |
| MSI           | X570-A PRO                  | Desktop     | [157c4afbb8](https://linux-hardware.org/?probe=157c4afbb8) | Apr 15, 2025 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [87b2260338](https://linux-hardware.org/?probe=87b2260338) | Mar 19, 2025 |
| ASUSTek       | K50IE                       | Notebook    | [fe847bba58](https://linux-hardware.org/?probe=fe847bba58) | Mar 19, 2025 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [28fb11d47d](https://linux-hardware.org/?probe=28fb11d47d) | Mar 17, 2025 |
| HP            | 829A                        | Mini pc     | [a4345f505f](https://linux-hardware.org/?probe=a4345f505f) | Mar 14, 2025 |
| ASUSTek       | X555LJ                      | Notebook    | [281c68dcbc](https://linux-hardware.org/?probe=281c68dcbc) | Mar 11, 2025 |
| ASRock        | X370 Gaming K4              | Desktop     | [b843db386a](https://linux-hardware.org/?probe=b843db386a) | Feb 19, 2025 |
| Unknown       | Unknown                     | Desktop     | [0ae66b83f4](https://linux-hardware.org/?probe=0ae66b83f4) | Feb 17, 2025 |
| Lenovo        | ThinkServer TS440           | Desktop     | [d28f900a93](https://linux-hardware.org/?probe=d28f900a93) | Feb 01, 2025 |
| Gigabyte      | A520I AC                    | Desktop     | [316bf86d32](https://linux-hardware.org/?probe=316bf86d32) | Jan 29, 2025 |
| Biostar       | A960G+                      | Desktop     | [4c8bbea6fa](https://linux-hardware.org/?probe=4c8bbea6fa) | Jan 21, 2025 |
| Lenovo        | ThinkPad X200 7459D12       | Notebook    | [75784aa0ab](https://linux-hardware.org/?probe=75784aa0ab) | Jan 20, 2025 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [47eefaf43e](https://linux-hardware.org/?probe=47eefaf43e) | Jan 13, 2025 |
| ASUSTek       | P5VD2-MX SE                 | Desktop     | [79f2dc1f44](https://linux-hardware.org/?probe=79f2dc1f44) | Jan 04, 2025 |
| Purism        | Librem 14                   | Notebook    | [5f54d4d304](https://linux-hardware.org/?probe=5f54d4d304) | Jan 01, 2025 |
| Medion        | MS-7800                     | Desktop     | [4d798c6151](https://linux-hardware.org/?probe=4d798c6151) | Dec 28, 2024 |
| Lenovo        | IdeaPad Y460                | Notebook    | [3c6931e293](https://linux-hardware.org/?probe=3c6931e293) | Dec 27, 2024 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [3dd5eb18d7](https://linux-hardware.org/?probe=3dd5eb18d7) | Dec 04, 2024 |
| ASUSTek       | K50IE                       | Notebook    | [6b1d699417](https://linux-hardware.org/?probe=6b1d699417) | Nov 30, 2024 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [37e2be7204](https://linux-hardware.org/?probe=37e2be7204) | Nov 29, 2024 |
| ASUSTek       | K50IE                       | Notebook    | [2b124f3ff4](https://linux-hardware.org/?probe=2b124f3ff4) | Nov 28, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [47689d663d](https://linux-hardware.org/?probe=47689d663d) | Nov 26, 2024 |
| Lenovo        | ThinkServer TS440           | Desktop     | [32d727d9ed](https://linux-hardware.org/?probe=32d727d9ed) | Nov 23, 2024 |
| Dell          | Latitude E5500              | Notebook    | [872edd1a02](https://linux-hardware.org/?probe=872edd1a02) | Nov 15, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [324609e537](https://linux-hardware.org/?probe=324609e537) | Nov 13, 2024 |
| Acer          | Aspire E5-576               | Notebook    | [a8438fb58b](https://linux-hardware.org/?probe=a8438fb58b) | Nov 13, 2024 |
| Lenovo        | ThinkPad X200 7459D12       | Notebook    | [a34523d690](https://linux-hardware.org/?probe=a34523d690) | Nov 05, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [e0f9145a94](https://linux-hardware.org/?probe=e0f9145a94) | Oct 29, 2024 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [3f2770b9fe](https://linux-hardware.org/?probe=3f2770b9fe) | Oct 25, 2024 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [08d5336ac6](https://linux-hardware.org/?probe=08d5336ac6) | Oct 23, 2024 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f32872a46b](https://linux-hardware.org/?probe=f32872a46b) | Oct 22, 2024 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [d657be30d1](https://linux-hardware.org/?probe=d657be30d1) | Oct 22, 2024 |
| MSI           | 970A-G46                    | Desktop     | [7f5bf49bca](https://linux-hardware.org/?probe=7f5bf49bca) | Oct 08, 2024 |
| Packard Be... | IMEDIA S1300                | Desktop     | [169f7ca9c5](https://linux-hardware.org/?probe=169f7ca9c5) | Oct 07, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [48012a37a7](https://linux-hardware.org/?probe=48012a37a7) | Oct 06, 2024 |
| Lenovo        | ThinkServer TS440           | Desktop     | [f632484903](https://linux-hardware.org/?probe=f632484903) | Sep 24, 2024 |
| Lenovo        | ThinkServer TS440           | Desktop     | [d6f3c76298](https://linux-hardware.org/?probe=d6f3c76298) | Sep 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6a8043a39f](https://linux-hardware.org/?probe=6a8043a39f) | Sep 21, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [17fd2f1a0d](https://linux-hardware.org/?probe=17fd2f1a0d) | Sep 21, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [467e17fa7f](https://linux-hardware.org/?probe=467e17fa7f) | Sep 15, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [c481ebf3ab](https://linux-hardware.org/?probe=c481ebf3ab) | Sep 03, 2024 |
| Lenovo        | LOQ 15AHP9 83DX             | Notebook    | [b59950cf4a](https://linux-hardware.org/?probe=b59950cf4a) | Sep 03, 2024 |
| Nitrokey      | NitroPC                     | Desktop     | [9483c755b2](https://linux-hardware.org/?probe=9483c755b2) | Aug 30, 2024 |
| Lenovo        | ThinkPad X230 23253A2       | Notebook    | [3fee175541](https://linux-hardware.org/?probe=3fee175541) | Aug 27, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [5d24c43a0f](https://linux-hardware.org/?probe=5d24c43a0f) | Aug 23, 2024 |
| Dell          | Latitude E6430              | Notebook    | [bdf4eb5fc6](https://linux-hardware.org/?probe=bdf4eb5fc6) | Jul 29, 2024 |
| Framework     | Laptop                      | Notebook    | [8436ce2126](https://linux-hardware.org/?probe=8436ce2126) | Jul 22, 2024 |
| ASUSTek       | M4A78LT-M-LE                | Desktop     | [f4985cfd49](https://linux-hardware.org/?probe=f4985cfd49) | Jul 21, 2024 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [545544cd2e](https://linux-hardware.org/?probe=545544cd2e) | Jul 18, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [2afec4b13a](https://linux-hardware.org/?probe=2afec4b13a) | Jul 17, 2024 |
| Nitrokey      | NitroPC                     | Desktop     | [b6feebdb98](https://linux-hardware.org/?probe=b6feebdb98) | Jul 15, 2024 |
| ASUSTek       | TUF Gaming FX505GD          | Notebook    | [e269bf0952](https://linux-hardware.org/?probe=e269bf0952) | Jul 14, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [df123831be](https://linux-hardware.org/?probe=df123831be) | Jul 13, 2024 |
| Lenovo        | ThinkPad X230 4290EM6       | Notebook    | [ec3109a514](https://linux-hardware.org/?probe=ec3109a514) | Jul 13, 2024 |
| ASRock        | H310CM-HG4                  | Desktop     | [a7472ec4d0](https://linux-hardware.org/?probe=a7472ec4d0) | Jul 12, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [59b443dc2a](https://linux-hardware.org/?probe=59b443dc2a) | Jul 12, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [b8bdcd66a2](https://linux-hardware.org/?probe=b8bdcd66a2) | Jul 07, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [e482f45dc4](https://linux-hardware.org/?probe=e482f45dc4) | Jul 06, 2024 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [6dc0514739](https://linux-hardware.org/?probe=6dc0514739) | Jul 05, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [48d2c2f4d4](https://linux-hardware.org/?probe=48d2c2f4d4) | Jun 30, 2024 |
| Acer          | Aspire 5742Z                | Notebook    | [47307ae042](https://linux-hardware.org/?probe=47307ae042) | Jun 23, 2024 |
| Positivo      | POS-PIB150DT                | Desktop     | [0605d568ff](https://linux-hardware.org/?probe=0605d568ff) | Jun 18, 2024 |
| ASUSTek       | EB1037                      | Desktop     | [b138f78a44](https://linux-hardware.org/?probe=b138f78a44) | Jun 16, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [8b81f887cb](https://linux-hardware.org/?probe=8b81f887cb) | Jun 15, 2024 |
| Intel         | NUC5CPYB H61145-410         | Mini pc     | [fcf83a3e56](https://linux-hardware.org/?probe=fcf83a3e56) | Jun 07, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [71ef9c5bc6](https://linux-hardware.org/?probe=71ef9c5bc6) | Jun 07, 2024 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [f2859ff34a](https://linux-hardware.org/?probe=f2859ff34a) | Jun 07, 2024 |
| Shenzhen M... | ANSVK                       | Desktop     | [9d7782cbb6](https://linux-hardware.org/?probe=9d7782cbb6) | May 22, 2024 |
| Shenzhen M... | ANSVK                       | Desktop     | [70f87ebe01](https://linux-hardware.org/?probe=70f87ebe01) | May 22, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [090323c57b](https://linux-hardware.org/?probe=090323c57b) | May 20, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [f637fbeb5a](https://linux-hardware.org/?probe=f637fbeb5a) | May 11, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [536f8ed319](https://linux-hardware.org/?probe=536f8ed319) | May 09, 2024 |
| System76      | Galago Pro                  | Notebook    | [06d9cca0d2](https://linux-hardware.org/?probe=06d9cca0d2) | Apr 27, 2024 |
| ASUSTek       | 1000H                       | Notebook    | [0463a4d88b](https://linux-hardware.org/?probe=0463a4d88b) | Apr 26, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [08ca3d5ea0](https://linux-hardware.org/?probe=08ca3d5ea0) | Apr 19, 2024 |
| Dell          | Studio 1558                 | Notebook    | [73fb46028c](https://linux-hardware.org/?probe=73fb46028c) | Apr 12, 2024 |
| Samsung       | DP515A2G-K02FR SAMSUNG_S... | All in one  | [b029695fa9](https://linux-hardware.org/?probe=b029695fa9) | Apr 06, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [fec7c15063](https://linux-hardware.org/?probe=fec7c15063) | Apr 03, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [7756c3e23b](https://linux-hardware.org/?probe=7756c3e23b) | Apr 01, 2024 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [63429edd54](https://linux-hardware.org/?probe=63429edd54) | Apr 01, 2024 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [f886e7b907](https://linux-hardware.org/?probe=f886e7b907) | Mar 21, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [0348bd12f8](https://linux-hardware.org/?probe=0348bd12f8) | Mar 15, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [fbd2947969](https://linux-hardware.org/?probe=fbd2947969) | Mar 13, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [3b35cebff6](https://linux-hardware.org/?probe=3b35cebff6) | Mar 12, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [63a3f8ce29](https://linux-hardware.org/?probe=63a3f8ce29) | Mar 11, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [aa06991c8c](https://linux-hardware.org/?probe=aa06991c8c) | Mar 11, 2024 |
| Gigabyte      | B360M HD3                   | Desktop     | [724f7885d0](https://linux-hardware.org/?probe=724f7885d0) | Mar 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2270faaf14](https://linux-hardware.org/?probe=2270faaf14) | Mar 07, 2024 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [7fb7bfaacd](https://linux-hardware.org/?probe=7fb7bfaacd) | Mar 05, 2024 |
| ASUSTek       | K55VJ                       | Notebook    | [88ee2dbed6](https://linux-hardware.org/?probe=88ee2dbed6) | Mar 03, 2024 |
| Gigabyte      | B760 GAMING X AX            | Desktop     | [bdd341c11c](https://linux-hardware.org/?probe=bdd341c11c) | Mar 02, 2024 |
| MACHENIKE     | T90-V                       | Notebook    | [01cb379c2e](https://linux-hardware.org/?probe=01cb379c2e) | Feb 24, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [3b4a6f9360](https://linux-hardware.org/?probe=3b4a6f9360) | Feb 19, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [5b29c953c3](https://linux-hardware.org/?probe=5b29c953c3) | Feb 17, 2024 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [72820ef395](https://linux-hardware.org/?probe=72820ef395) | Feb 15, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [7f6b3c0f92](https://linux-hardware.org/?probe=7f6b3c0f92) | Feb 13, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [348dffed6d](https://linux-hardware.org/?probe=348dffed6d) | Feb 09, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [6cac3b71e0](https://linux-hardware.org/?probe=6cac3b71e0) | Feb 01, 2024 |
| Dell          | OptiPlex 780                | Desktop     | [3c444c1e27](https://linux-hardware.org/?probe=3c444c1e27) | Jan 24, 2024 |
| ASUSTek       | Z170-P                      | Desktop     | [fc85634fb3](https://linux-hardware.org/?probe=fc85634fb3) | Jan 10, 2024 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | Notebook    | [b66d7c38c1](https://linux-hardware.org/?probe=b66d7c38c1) | Dec 31, 2023 |
| Dell          | 03GCPM A01                  | Server      | [7c11f33356](https://linux-hardware.org/?probe=7c11f33356) | Dec 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [ce4bc6f455](https://linux-hardware.org/?probe=ce4bc6f455) | Dec 21, 2023 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [3834ee3d70](https://linux-hardware.org/?probe=3834ee3d70) | Dec 15, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f170615f49](https://linux-hardware.org/?probe=f170615f49) | Dec 14, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [7af6ecc981](https://linux-hardware.org/?probe=7af6ecc981) | Dec 12, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c23aa9b02a](https://linux-hardware.org/?probe=c23aa9b02a) | Dec 10, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [c72f209121](https://linux-hardware.org/?probe=c72f209121) | Dec 05, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8b68261a59](https://linux-hardware.org/?probe=8b68261a59) | Nov 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [2961332bce](https://linux-hardware.org/?probe=2961332bce) | Nov 26, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1080... | Notebook    | [37c32a9af7](https://linux-hardware.org/?probe=37c32a9af7) | Nov 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [01866950a6](https://linux-hardware.org/?probe=01866950a6) | Nov 25, 2023 |
| HP            | G62                         | Notebook    | [9d6424c4cc](https://linux-hardware.org/?probe=9d6424c4cc) | Nov 24, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [8e8de2388b](https://linux-hardware.org/?probe=8e8de2388b) | Nov 21, 2023 |
| HP            | Presario C700               | Notebook    | [c8a9963f71](https://linux-hardware.org/?probe=c8a9963f71) | Nov 19, 2023 |
| HP            | Unknown                     | Notebook    | [3827b1fa19](https://linux-hardware.org/?probe=3827b1fa19) | Nov 16, 2023 |
| HP            | Unknown                     | Notebook    | [ef19087623](https://linux-hardware.org/?probe=ef19087623) | Nov 16, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [547a248361](https://linux-hardware.org/?probe=547a248361) | Nov 03, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [21e7b53022](https://linux-hardware.org/?probe=21e7b53022) | Nov 02, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EC00    | Notebook    | [820620d5c4](https://linux-hardware.org/?probe=820620d5c4) | Nov 01, 2023 |
| Intel         | X99                         | Desktop     | [8f60418655](https://linux-hardware.org/?probe=8f60418655) | Oct 30, 2023 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [a54528c1ef](https://linux-hardware.org/?probe=a54528c1ef) | Oct 29, 2023 |
| Samsung       | N150P                       | Notebook    | [83f77d7896](https://linux-hardware.org/?probe=83f77d7896) | Oct 23, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [baacbfa91a](https://linux-hardware.org/?probe=baacbfa91a) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [cf522294f8](https://linux-hardware.org/?probe=cf522294f8) | Oct 18, 2023 |
| TUXEDO        | XP1610                      | Notebook    | [31be190f30](https://linux-hardware.org/?probe=31be190f30) | Oct 13, 2023 |
| Dell          | XPS M1530                   | Notebook    | [b24e393bbb](https://linux-hardware.org/?probe=b24e393bbb) | Sep 23, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [56cd0e05e8](https://linux-hardware.org/?probe=56cd0e05e8) | Sep 22, 2023 |
| PC Special... | P7xxTM1                     | Notebook    | [2bdbc2f2e7](https://linux-hardware.org/?probe=2bdbc2f2e7) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [f23bb97453](https://linux-hardware.org/?probe=f23bb97453) | Sep 11, 2023 |
| Sony          | VGN-FZ140E                  | Notebook    | [361226919e](https://linux-hardware.org/?probe=361226919e) | Sep 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [61906f4e91](https://linux-hardware.org/?probe=61906f4e91) | Sep 07, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [89a0e93fd5](https://linux-hardware.org/?probe=89a0e93fd5) | Sep 05, 2023 |
| Intel         | powered classmate PC        | Notebook    | [f852524db2](https://linux-hardware.org/?probe=f852524db2) | Sep 01, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [44e328b3a0](https://linux-hardware.org/?probe=44e328b3a0) | Aug 24, 2023 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | Notebook    | [c299d4ad92](https://linux-hardware.org/?probe=c299d4ad92) | Aug 15, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| Dell          | 0GX297                      | Desktop     | [0fa81b620e](https://linux-hardware.org/?probe=0fa81b620e) | Aug 14, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [bed2e58bf4](https://linux-hardware.org/?probe=bed2e58bf4) | Aug 14, 2023 |
| ASUSTek       | T200TA                      | Notebook    | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [3e63b3dec0](https://linux-hardware.org/?probe=3e63b3dec0) | Aug 09, 2023 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [a036ddad16](https://linux-hardware.org/?probe=a036ddad16) | Aug 09, 2023 |
| Supermicro    | X10SRG-F                    | Desktop     | [3bdaa7bfef](https://linux-hardware.org/?probe=3bdaa7bfef) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [67febbf0c0](https://linux-hardware.org/?probe=67febbf0c0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [606780c010](https://linux-hardware.org/?probe=606780c010) | Jul 24, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c298263c6c](https://linux-hardware.org/?probe=c298263c6c) | Jul 22, 2023 |
| Dell          | Latitude E5500              | Notebook    | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Nokia         | N900                        | Notebook    | [7728c85b90](https://linux-hardware.org/?probe=7728c85b90) | Jul 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [d072001450](https://linux-hardware.org/?probe=d072001450) | Jul 04, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [8b04801d40](https://linux-hardware.org/?probe=8b04801d40) | Jun 27, 2023 |
| Lenovo        | ThinkPad T410 2537DA3       | Notebook    | [067b7f26a2](https://linux-hardware.org/?probe=067b7f26a2) | Jun 25, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [82c9c200bc](https://linux-hardware.org/?probe=82c9c200bc) | Jun 20, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [7a3f7dcd73](https://linux-hardware.org/?probe=7a3f7dcd73) | Jun 17, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [54f07f7d96](https://linux-hardware.org/?probe=54f07f7d96) | May 12, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | Desktop     | [36022cb1ac](https://linux-hardware.org/?probe=36022cb1ac) | May 11, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [d07874c829](https://linux-hardware.org/?probe=d07874c829) | Apr 24, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| HP            | 212A                        | Desktop     | [178f3b9c05](https://linux-hardware.org/?probe=178f3b9c05) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [96e067f5c8](https://linux-hardware.org/?probe=96e067f5c8) | Apr 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [549f922cf6](https://linux-hardware.org/?probe=549f922cf6) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [a9aa9ab39f](https://linux-hardware.org/?probe=a9aa9ab39f) | Apr 13, 2023 |
| Lenovo        | 3138 SDK0J40697 WIN 3305... | Desktop     | [491da3c2c2](https://linux-hardware.org/?probe=491da3c2c2) | Apr 10, 2023 |
| Google        | Cyan                        | Notebook    | [f32e15dfef](https://linux-hardware.org/?probe=f32e15dfef) | Apr 09, 2023 |
| MSI           | PH67A-C43                   | Desktop     | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [ec45a753a5](https://linux-hardware.org/?probe=ec45a753a5) | Apr 02, 2023 |
| Dell          | G5 5505                     | Notebook    | [2552b456b6](https://linux-hardware.org/?probe=2552b456b6) | Mar 29, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [a33a768662](https://linux-hardware.org/?probe=a33a768662) | Mar 29, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [98ba3a9ce6](https://linux-hardware.org/?probe=98ba3a9ce6) | Mar 25, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [f22446cb1d](https://linux-hardware.org/?probe=f22446cb1d) | Mar 16, 2023 |
| Google        | Bluebird                    | Notebook    | [2d18088551](https://linux-hardware.org/?probe=2d18088551) | Mar 15, 2023 |
| Dell          | Latitude E6230              | Notebook    | [49a9844be8](https://linux-hardware.org/?probe=49a9844be8) | Mar 15, 2023 |
| AMI           | Intel                       | Desktop     | [c2c28fa7e4](https://linux-hardware.org/?probe=c2c28fa7e4) | Mar 15, 2023 |
| Dell          | Latitude E6440              | Notebook    | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [83dcd35e5f](https://linux-hardware.org/?probe=83dcd35e5f) | Mar 12, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [60cd9db1c5](https://linux-hardware.org/?probe=60cd9db1c5) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| MSI           | A320M PRO-E                 | Desktop     | [3e441c86f1](https://linux-hardware.org/?probe=3e441c86f1) | Feb 20, 2023 |
| HP            | 829A                        | Mini pc     | [8791cd83c7](https://linux-hardware.org/?probe=8791cd83c7) | Feb 19, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| MSI           | H67MS-E43                   | Desktop     | [47a6655b3b](https://linux-hardware.org/?probe=47a6655b3b) | Feb 07, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [63ea9a161f](https://linux-hardware.org/?probe=63ea9a161f) | Jan 31, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | Notebook    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [360a177e77](https://linux-hardware.org/?probe=360a177e77) | Jan 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [f4349052b8](https://linux-hardware.org/?probe=f4349052b8) | Jan 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [1f72002986](https://linux-hardware.org/?probe=1f72002986) | Dec 29, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1d9edd6c97](https://linux-hardware.org/?probe=1d9edd6c97) | Dec 25, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [beeeff23a5](https://linux-hardware.org/?probe=beeeff23a5) | Dec 25, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ed3886b135](https://linux-hardware.org/?probe=ed3886b135) | Dec 02, 2022 |
| Dell          | Latitude E6530              | Notebook    | [e40986d2fb](https://linux-hardware.org/?probe=e40986d2fb) | Nov 22, 2022 |
| Dell          | Latitude E6530              | Notebook    | [14debbe3e5](https://linux-hardware.org/?probe=14debbe3e5) | Nov 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [be4f638bc7](https://linux-hardware.org/?probe=be4f638bc7) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [de8b7d8220](https://linux-hardware.org/?probe=de8b7d8220) | Nov 19, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [7254534946](https://linux-hardware.org/?probe=7254534946) | Oct 20, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [270cf10219](https://linux-hardware.org/?probe=270cf10219) | Sep 25, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [bf397424f3](https://linux-hardware.org/?probe=bf397424f3) | Sep 18, 2022 |
| HP            | 1825                        | Desktop     | [bceae72004](https://linux-hardware.org/?probe=bceae72004) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [defafd4f0b](https://linux-hardware.org/?probe=defafd4f0b) | Aug 10, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [389bef188c](https://linux-hardware.org/?probe=389bef188c) | Aug 10, 2022 |
| MSI           | X99S MPOWER                 | Desktop     | [a3c1523b6b](https://linux-hardware.org/?probe=a3c1523b6b) | Jul 27, 2022 |
| Sony          | VPCEE23FX                   | Notebook    | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Dell          | Latitude 7280               | Notebook    | [75ce6d31bc](https://linux-hardware.org/?probe=75ce6d31bc) | Jul 14, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [045554b70c](https://linux-hardware.org/?probe=045554b70c) | Jul 08, 2022 |
| Dell          | 054KM3 A01                  | Desktop     | [407b210bfe](https://linux-hardware.org/?probe=407b210bfe) | Jul 05, 2022 |
| HP            | 18E7                        | Desktop     | [2fd690b3b4](https://linux-hardware.org/?probe=2fd690b3b4) | Jun 22, 2022 |
| Lenovo        | ThinkPad T430 2349I46       | Notebook    | [3a7df4ea17](https://linux-hardware.org/?probe=3a7df4ea17) | Jun 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [a698baa5f6](https://linux-hardware.org/?probe=a698baa5f6) | Jun 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [001634b95b](https://linux-hardware.org/?probe=001634b95b) | Jun 17, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [5da801634f](https://linux-hardware.org/?probe=5da801634f) | Jun 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [2d4c950e2f](https://linux-hardware.org/?probe=2d4c950e2f) | May 25, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [73139cdb17](https://linux-hardware.org/?probe=73139cdb17) | May 25, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [bce1bba9ff](https://linux-hardware.org/?probe=bce1bba9ff) | Apr 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| HP            | Notebook                    | Notebook    | [966668f0c0](https://linux-hardware.org/?probe=966668f0c0) | Apr 17, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [fe4bb32aa1](https://linux-hardware.org/?probe=fe4bb32aa1) | Apr 14, 2022 |
| Dell          | 014GRG A00                  | Desktop     | [1783efe96b](https://linux-hardware.org/?probe=1783efe96b) | Apr 14, 2022 |
| Lenovo        | ThinkPad T470s 20HGS00P0... | Notebook    | [2c9878c68b](https://linux-hardware.org/?probe=2c9878c68b) | Apr 13, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [1aa66a62c4](https://linux-hardware.org/?probe=1aa66a62c4) | Mar 26, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| HP            | 1825                        | Desktop     | [a7ce5b6b11](https://linux-hardware.org/?probe=a7ce5b6b11) | Mar 03, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [a3aed9d375](https://linux-hardware.org/?probe=a3aed9d375) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [f92ae76fed](https://linux-hardware.org/?probe=f92ae76fed) | Feb 24, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [7ab68e0043](https://linux-hardware.org/?probe=7ab68e0043) | Feb 17, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2a65b8a5f](https://linux-hardware.org/?probe=f2a65b8a5f) | Feb 14, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [824dbdd8ad](https://linux-hardware.org/?probe=824dbdd8ad) | Jan 22, 2022 |
| Online Lab... | SR 42                       | Desktop     | [e3037eb087](https://linux-hardware.org/?probe=e3037eb087) | Jan 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9e14e04f7f](https://linux-hardware.org/?probe=9e14e04f7f) | Jan 22, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [562262b9eb](https://linux-hardware.org/?probe=562262b9eb) | Jan 22, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [8e7267692b](https://linux-hardware.org/?probe=8e7267692b) | Jan 21, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [9fbdf4dfc2](https://linux-hardware.org/?probe=9fbdf4dfc2) | Jan 17, 2022 |
| Lenovo        | ThinkPad T420 4180AG3       | Notebook    | [2c3cd27ad2](https://linux-hardware.org/?probe=2c3cd27ad2) | Jan 16, 2022 |
| Notebook      | W230ST                      | Notebook    | [3dacf0aea8](https://linux-hardware.org/?probe=3dacf0aea8) | Jan 15, 2022 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [202ccac61c](https://linux-hardware.org/?probe=202ccac61c) | Dec 30, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [1c15b6b3c7](https://linux-hardware.org/?probe=1c15b6b3c7) | Dec 26, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [899cb98778](https://linux-hardware.org/?probe=899cb98778) | Dec 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [d43a6a6bb8](https://linux-hardware.org/?probe=d43a6a6bb8) | Nov 29, 2021 |
| HP            | 1495                        | Desktop     | [28835849f0](https://linux-hardware.org/?probe=28835849f0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [55689e67b3](https://linux-hardware.org/?probe=55689e67b3) | Oct 27, 2021 |
| Lenovo        | ThinkPad X230 2325DE0       | Notebook    | [991007e92a](https://linux-hardware.org/?probe=991007e92a) | Oct 13, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7f1b3371a9](https://linux-hardware.org/?probe=7f1b3371a9) | Oct 03, 2021 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [5a7e6805d3](https://linux-hardware.org/?probe=5a7e6805d3) | Oct 02, 2021 |
| MSI           | B360M PRO-VD                | Desktop     | [06e625d98f](https://linux-hardware.org/?probe=06e625d98f) | Oct 02, 2021 |
| Toshiba       | Satellite M40X              | Notebook    | [61fea93e97](https://linux-hardware.org/?probe=61fea93e97) | Oct 01, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [ae41600fd9](https://linux-hardware.org/?probe=ae41600fd9) | Sep 24, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [04747e3df4](https://linux-hardware.org/?probe=04747e3df4) | Sep 19, 2021 |
| IBM           | ThinkPad T41p 2373GHG       | Notebook    | [134b90f474](https://linux-hardware.org/?probe=134b90f474) | Sep 18, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ffd8fa11af](https://linux-hardware.org/?probe=ffd8fa11af) | Sep 16, 2021 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d65f9a48fd](https://linux-hardware.org/?probe=d65f9a48fd) | Sep 04, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [04256a6e0a](https://linux-hardware.org/?probe=04256a6e0a) | Aug 25, 2021 |
| Lenovo        | ThinkPad X200 74585FU       | Notebook    | [dffbcc492c](https://linux-hardware.org/?probe=dffbcc492c) | Aug 25, 2021 |
| ASUSTek       | K52F                        | Notebook    | [643e3cc4b3](https://linux-hardware.org/?probe=643e3cc4b3) | Aug 13, 2021 |
| MSI           | MS-1688                     | Notebook    | [0ae772d66b](https://linux-hardware.org/?probe=0ae772d66b) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 429053G       | Notebook    | [5f553465bf](https://linux-hardware.org/?probe=5f553465bf) | Jul 29, 2021 |
| Acer          | Extensa 215-51K             | Notebook    | [1c49c2f4d0](https://linux-hardware.org/?probe=1c49c2f4d0) | Jul 26, 2021 |
| Lenovo        | ThinkPad X250 20CLS7WY04    | Notebook    | [fc77801294](https://linux-hardware.org/?probe=fc77801294) | Jun 07, 2021 |
| HP            | 1825                        | Desktop     | [ff75be1ea3](https://linux-hardware.org/?probe=ff75be1ea3) | Jun 06, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [aef4e323e2](https://linux-hardware.org/?probe=aef4e323e2) | Jun 06, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [8702580cb4](https://linux-hardware.org/?probe=8702580cb4) | May 26, 2021 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [05f1d12390](https://linux-hardware.org/?probe=05f1d12390) | May 26, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [2ffdc89c2a](https://linux-hardware.org/?probe=2ffdc89c2a) | Apr 28, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [50f8ddb45c](https://linux-hardware.org/?probe=50f8ddb45c) | Apr 28, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [6fa86f9d25](https://linux-hardware.org/?probe=6fa86f9d25) | Apr 27, 2021 |
| Google        | Panther                     | Desktop     | [666794d603](https://linux-hardware.org/?probe=666794d603) | Apr 26, 2021 |
| ASUSTek       | K55VJ                       | Notebook    | [aef1b6c71f](https://linux-hardware.org/?probe=aef1b6c71f) | Apr 17, 2021 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [630bbb748a](https://linux-hardware.org/?probe=630bbb748a) | Apr 17, 2021 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [f103eefd66](https://linux-hardware.org/?probe=f103eefd66) | Apr 17, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [e802fc9ff5](https://linux-hardware.org/?probe=e802fc9ff5) | Apr 17, 2021 |
| HP            | ProBook 6475b               | Notebook    | [74b0fa77b5](https://linux-hardware.org/?probe=74b0fa77b5) | Apr 14, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e4b76f9137](https://linux-hardware.org/?probe=e4b76f9137) | Apr 10, 2021 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [15691fbc42](https://linux-hardware.org/?probe=15691fbc42) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Xi 1546               | Notebook    | [22a53eeb74](https://linux-hardware.org/?probe=22a53eeb74) | Apr 03, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [ee6bb68e8c](https://linux-hardware.org/?probe=ee6bb68e8c) | Mar 29, 2021 |
| ASUSTek       | A8R-MVP                     | Desktop     | [6daa2a372c](https://linux-hardware.org/?probe=6daa2a372c) | Mar 27, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [b8f4c7c2cb](https://linux-hardware.org/?probe=b8f4c7c2cb) | Mar 22, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eeebc66137](https://linux-hardware.org/?probe=eeebc66137) | Mar 17, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fdf4e6d366](https://linux-hardware.org/?probe=fdf4e6d366) | Mar 17, 2021 |
| ASRock        | K8A780LM                    | Desktop     | [d95a56d80f](https://linux-hardware.org/?probe=d95a56d80f) | Mar 15, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [0f5f41e1ca](https://linux-hardware.org/?probe=0f5f41e1ca) | Mar 08, 2021 |
| ASRock        | H81M-ITX                    | Desktop     | [8599b883d6](https://linux-hardware.org/?probe=8599b883d6) | Mar 08, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [248565d49c](https://linux-hardware.org/?probe=248565d49c) | Feb 20, 2021 |
| Intel         | D815EEA AAA45884-401        | Desktop     | [3acc2f0b1e](https://linux-hardware.org/?probe=3acc2f0b1e) | Feb 20, 2021 |
| Gigabyte      | GA-G41M-ES2L                | Desktop     | [592c995804](https://linux-hardware.org/?probe=592c995804) | Jan 30, 2021 |
| Acer          | F672CR R01-A4               | Desktop     | [8d41694165](https://linux-hardware.org/?probe=8d41694165) | Jan 25, 2021 |
| Teclast       | F6 Plus                     | Notebook    | [26ac25681a](https://linux-hardware.org/?probe=26ac25681a) | Jan 08, 2021 |
| Lenovo        | ThinkStation E20 4220CTO    | Desktop     | [f963a2e7f9](https://linux-hardware.org/?probe=f963a2e7f9) | Jan 06, 2021 |
| Dell          | 0GXM1W A04                  | Desktop     | [989f983b51](https://linux-hardware.org/?probe=989f983b51) | Dec 28, 2020 |
| Lenovo        | ThinkStation E20 4220CTO    | Desktop     | [aac28ba905](https://linux-hardware.org/?probe=aac28ba905) | Dec 19, 2020 |
| Dell          | Precision 7530              | Notebook    | [8e0ee186a3](https://linux-hardware.org/?probe=8e0ee186a3) | Dec 04, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [b708be8d9e](https://linux-hardware.org/?probe=b708be8d9e) | Nov 10, 2020 |
| Lenovo        | ThinkPad X60 1707YF8        | Notebook    | [bcdd451de1](https://linux-hardware.org/?probe=bcdd451de1) | Oct 31, 2020 |
| Intel         | HURONRIVER                  | Desktop     | [49bdd1a99d](https://linux-hardware.org/?probe=49bdd1a99d) | Oct 29, 2020 |
| ASUSTek       | Maximus V GENE              | Desktop     | [253b5aba98](https://linux-hardware.org/?probe=253b5aba98) | Oct 29, 2020 |
| Nokia         | N900                        | Notebook    | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [cd136e059e](https://linux-hardware.org/?probe=cd136e059e) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 23247S0       | Notebook    | [f313b0bf1b](https://linux-hardware.org/?probe=f313b0bf1b) | Oct 01, 2020 |
| Dell          | Precision 7530              | Notebook    | [e6c6dd2734](https://linux-hardware.org/?probe=e6c6dd2734) | Sep 26, 2020 |
| Dell          | Precision 7530              | Notebook    | [81e9306141](https://linux-hardware.org/?probe=81e9306141) | Sep 26, 2020 |
| HP            | 1791                        | Desktop     | [f41fcdc019](https://linux-hardware.org/?probe=f41fcdc019) | Sep 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3d241c321f](https://linux-hardware.org/?probe=3d241c321f) | Sep 20, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [32b487459e](https://linux-hardware.org/?probe=32b487459e) | Sep 16, 2020 |
| ASUSTek       | K52F                        | Notebook    | [cef5147eeb](https://linux-hardware.org/?probe=cef5147eeb) | Aug 30, 2020 |
| Acer          | Aspire 5732Z                | Notebook    | [c4cb936b69](https://linux-hardware.org/?probe=c4cb936b69) | Aug 30, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [6251a9111f](https://linux-hardware.org/?probe=6251a9111f) | Aug 30, 2020 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [0c85729a27](https://linux-hardware.org/?probe=0c85729a27) | Aug 30, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| HP            | 1791                        | Desktop     | [5a21e91155](https://linux-hardware.org/?probe=5a21e91155) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ff5143e508](https://linux-hardware.org/?probe=ff5143e508) | Aug 02, 2020 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [358be6b820](https://linux-hardware.org/?probe=358be6b820) | Jul 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [51e3108708](https://linux-hardware.org/?probe=51e3108708) | Jun 28, 2020 |
| Dell          | Latitude 5501               | Notebook    | [94ec8d2a1d](https://linux-hardware.org/?probe=94ec8d2a1d) | Jun 28, 2020 |
| Lenovo        | IdeaPad Z370                | Notebook    | [76c985ed75](https://linux-hardware.org/?probe=76c985ed75) | Jun 27, 2020 |
| Dell          | Latitude E7250              | Notebook    | [c2ca61e7bf](https://linux-hardware.org/?probe=c2ca61e7bf) | Jun 23, 2020 |
| ASUSTek       | P5PE-VM                     | Desktop     | [298c1239dd](https://linux-hardware.org/?probe=298c1239dd) | May 20, 2020 |
| MSI           | B350 PC MATE                | Desktop     | [ff3852f02d](https://linux-hardware.org/?probe=ff3852f02d) | Mar 23, 2020 |
| Dell          | Inspiron 1564               | Notebook    | [b80e556643](https://linux-hardware.org/?probe=b80e556643) | Feb 02, 2020 |
| MTC           | Montara-GML                 | Notebook    | [227bf1ba1d](https://linux-hardware.org/?probe=227bf1ba1d) | Dec 07, 2019 |
| ASRock        | G31M-VS2                    | Desktop     | [b64547f948](https://linux-hardware.org/?probe=b64547f948) | Dec 06, 2019 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [338994bd66](https://linux-hardware.org/?probe=338994bd66) | Dec 02, 2019 |
| ASUSTek       | P5PE-VM                     | Desktop     | [6a89046dfb](https://linux-hardware.org/?probe=6a89046dfb) | Dec 02, 2019 |
| Microsoft     | Surface Pro 4               | Tablet      | [59ca47d9e7](https://linux-hardware.org/?probe=59ca47d9e7) | Apr 12, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Devuan 5                | 123       | 40.2%   |
| Devuan 4                | 86        | 28.1%   |
| Devuan 3                | 31        | 10.13%  |
| Devuan 6                | 30        | 9.8%    |
| Devuan Testing/unstable | 15        | 4.9%    |
| Devuan                  | 9         | 2.94%   |
| Devuan 2.1              | 7         | 2.29%   |
| Devuan 9                | 1         | 0.33%   |
| Devuan 7                | 1         | 0.33%   |
| Devuan 3.0              | 1         | 0.33%   |
| Devuan 2.0              | 1         | 0.33%   |
| Devuan 1.0.0            | 1         | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Devuan | 288       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version               | Computers | Percent |
|-----------------------|-----------|---------|
| 5.10.0-21-amd64       | 13        | 3.88%   |
| 6.1.0-10-amd64        | 12        | 3.58%   |
| 6.1.0-13-amd64        | 11        | 3.28%   |
| 5.10.0-9-amd64        | 10        | 2.99%   |
| 5.10.0-23-amd64       | 8         | 2.39%   |
| 6.1.0-18-amd64        | 7         | 2.09%   |
| 5.10.0-8-amd64        | 7         | 2.09%   |
| 6.1.0-28-amd64        | 6         | 1.79%   |
| 5.10.0-16-amd64       | 6         | 1.79%   |
| 4.19.0-9-amd64        | 6         | 1.79%   |
| 4.19.0-14-amd64       | 6         | 1.79%   |
| 6.6.15-amd64          | 5         | 1.49%   |
| 6.1.0-38-amd64        | 5         | 1.49%   |
| 6.1.0-26-amd64        | 5         | 1.49%   |
| 6.1.0-21-amd64        | 5         | 1.49%   |
| 6.1.0-17-amd64        | 5         | 1.49%   |
| 6.1.0-11-amd64        | 5         | 1.49%   |
| 5.10.0-19-amd64       | 5         | 1.49%   |
| 4.19.0-16-amd64       | 5         | 1.49%   |
| 5.10.0-18-amd64       | 4         | 1.19%   |
| 5.10.0-13-amd64       | 4         | 1.19%   |
| 5.10.0-11-amd64       | 4         | 1.19%   |
| 5.10.0-10-amd64       | 4         | 1.19%   |
| 6.12.48+deb13-amd64   | 3         | 0.9%    |
| 6.12.38+deb13-amd64   | 3         | 0.9%    |
| 6.1.0-9-amd64         | 3         | 0.9%    |
| 6.1.0-6-amd64         | 3         | 0.9%    |
| 6.1.0-22-amd64        | 3         | 0.9%    |
| 6.1.0-12-amd64        | 3         | 0.9%    |
| 5.7.0-2-amd64         | 3         | 0.9%    |
| 5.10.0-25-amd64       | 3         | 0.9%    |
| 5.10.0-20-amd64       | 3         | 0.9%    |
| 4.19.0-12-amd64       | 3         | 0.9%    |
| 4.19.0-10-amd64       | 3         | 0.9%    |
| 6.9.7-amd64           | 2         | 0.6%    |
| 6.5.0-0.deb12.4-amd64 | 2         | 0.6%    |
| 6.5.0-0.deb12.1-amd64 | 2         | 0.6%    |
| 6.12.30-amd64         | 2         | 0.6%    |
| 6.10.6-amd64          | 2         | 0.6%    |
| 6.10.11+bpo-amd64     | 2         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 98        | 30.91%  |
| 5.10.0  | 85        | 26.81%  |
| 4.19.0  | 29        | 9.15%   |
| 4.9.0   | 10        | 3.15%   |
| 5.7.0   | 6         | 1.89%   |
| 6.6.15  | 5         | 1.58%   |
| 6.5.0   | 4         | 1.26%   |
| 6.0.0   | 4         | 1.26%   |
| 5.18.0  | 4         | 1.26%   |
| 6.12.48 | 3         | 0.95%   |
| 6.12.38 | 3         | 0.95%   |
| 5.15.0  | 3         | 0.95%   |
| 6.9.7   | 2         | 0.63%   |
| 6.3.0   | 2         | 0.63%   |
| 6.12.30 | 2         | 0.63%   |
| 6.12.0  | 2         | 0.63%   |
| 6.10.6  | 2         | 0.63%   |
| 6.10.11 | 2         | 0.63%   |
| 5.9.0   | 2         | 0.63%   |
| 5.8.0   | 2         | 0.63%   |
| 5.14.0  | 2         | 0.63%   |
| 6.9.0   | 1         | 0.32%   |
| 6.7.5   | 1         | 0.32%   |
| 6.6.13  | 1         | 0.32%   |
| 6.4.0   | 1         | 0.32%   |
| 6.2.12  | 1         | 0.32%   |
| 6.17.8  | 1         | 0.32%   |
| 6.17.2  | 1         | 0.32%   |
| 6.17.0  | 1         | 0.32%   |
| 6.16.8  | 1         | 0.32%   |
| 6.16.1  | 1         | 0.32%   |
| 6.16.0  | 1         | 0.32%   |
| 6.13.0  | 1         | 0.32%   |
| 6.12.6  | 1         | 0.32%   |
| 6.12.57 | 1         | 0.32%   |
| 6.12.43 | 1         | 0.32%   |
| 6.12.33 | 1         | 0.32%   |
| 6.12.32 | 1         | 0.32%   |
| 6.12.25 | 1         | 0.32%   |
| 6.12.22 | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 104       | 33.23%  |
| 5.10    | 86        | 27.48%  |
| 4.19    | 30        | 9.58%   |
| 6.12    | 16        | 5.11%   |
| 4.9     | 10        | 3.19%   |
| 5.7     | 7         | 2.24%   |
| 6.6     | 6         | 1.92%   |
| 6.10    | 6         | 1.92%   |
| 5.18    | 6         | 1.92%   |
| 6.5     | 4         | 1.28%   |
| 6.0     | 4         | 1.28%   |
| 5.15    | 4         | 1.28%   |
| 6.9     | 3         | 0.96%   |
| 6.17    | 3         | 0.96%   |
| 6.3     | 2         | 0.64%   |
| 6.16    | 2         | 0.64%   |
| 6.11    | 2         | 0.64%   |
| 5.9     | 2         | 0.64%   |
| 5.8     | 2         | 0.64%   |
| 5.14    | 2         | 0.64%   |
| 6.7     | 1         | 0.32%   |
| 6.4     | 1         | 0.32%   |
| 6.2     | 1         | 0.32%   |
| 6.13    | 1         | 0.32%   |
| 5.6     | 1         | 0.32%   |
| 5.19    | 1         | 0.32%   |
| 5.16    | 1         | 0.32%   |
| 5.11    | 1         | 0.32%   |
| 5.1     | 1         | 0.32%   |
| 5.0     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.18    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 271       | 93.77%  |
| i686    | 14        | 4.84%   |
| armv7l  | 3         | 1.04%   |
| aarch64 | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 136       | 45.48%  |
| Unknown         | 38        | 12.71%  |
| KDE5            | 35        | 11.71%  |
| MATE            | 30        | 10.03%  |
| i3              | 12        | 4.01%   |
| LXDE            | 10        | 3.34%   |
| LXQt            | 7         | 2.34%   |
| GNOME           | 6         | 2.01%   |
| Cinnamon        | 6         | 2.01%   |
| X-Cinnamon      | 5         | 1.67%   |
| awesome         | 3         | 1%      |
| Trinity         | 2         | 0.67%   |
| Openbox         | 2         | 0.67%   |
| KDE6            | 2         | 0.67%   |
| Enlightenment   | 2         | 0.67%   |
| sway            | 1         | 0.33%   |
| GNOME Flashback | 1         | 0.33%   |
| Budgie          | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 250       | 84.46%  |
| Tty         | 25        | 8.45%   |
| Wayland     | 10        | 3.38%   |
| Unknown     | 10        | 3.38%   |
| Unspecified | 1         | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 99        | 33.67%  |
| Unknown | 79        | 26.87%  |
| LightDM | 75        | 25.51%  |
| SDDM    | 20        | 6.8%    |
| GDM3    | 6         | 2.04%   |
| XDM     | 5         | 1.7%    |
| NODM    | 5         | 1.7%    |
| TDM     | 2         | 0.68%   |
| LXDM    | 2         | 0.68%   |
| Ly      | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 112       | 37.97%  |
| en_GB       | 34        | 11.53%  |
| fr_FR       | 20        | 6.78%   |
| ru_RU       | 19        | 6.44%   |
| es_ES       | 14        | 4.75%   |
| Unknown     | 13        | 4.41%   |
| C           | 12        | 4.07%   |
| pt_BR       | 11        | 3.73%   |
| de_DE       | 9         | 3.05%   |
| it_IT       | 8         | 2.71%   |
| de_AT       | 5         | 1.69%   |
| pl_PL       | 4         | 1.36%   |
| fr_BE       | 4         | 1.36%   |
| en_AU       | 4         | 1.36%   |
| sk_SK       | 3         | 1.02%   |
| hu_HU       | 3         | 1.02%   |
| en_NZ       | 3         | 1.02%   |
| es_MX       | 2         | 0.68%   |
| en_ZA       | 2         | 0.68%   |
| en_DK       | 2         | 0.68%   |
| ru_UA       | 1         | 0.34%   |
| ru_RU.utf-8 | 1         | 0.34%   |
| ko_KR       | 1         | 0.34%   |
| fr_CA       | 1         | 0.34%   |
| es_SV       | 1         | 0.34%   |
| es_CL       | 1         | 0.34%   |
| es_AR       | 1         | 0.34%   |
| en_US.utf-8 | 1         | 0.34%   |
| en_SG       | 1         | 0.34%   |
| en_CA       | 1         | 0.34%   |
| de_CH       | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 150       | 51.72%  |
| EFI  | 140       | 48.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 244       | 84.43%  |
| Btrfs   | 14        | 4.84%   |
| Unknown | 9         | 3.11%   |
| Xfs     | 8         | 2.77%   |
| Overlay | 8         | 2.77%   |
| Ext3    | 2         | 0.69%   |
| Ext2    | 2         | 0.69%   |
| Zfs     | 1         | 0.35%   |
| OveXlay | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 158       | 53.74%  |
| MBR     | 90        | 30.61%  |
| Unknown | 46        | 15.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 236       | 80.55%  |
| Yes       | 57        | 19.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 227       | 78.28%  |
| Yes       | 63        | 21.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 55        | 19.1%   |
| Dell                                 | 36        | 12.5%   |
| ASUSTek Computer                     | 36        | 12.5%   |
| Hewlett-Packard                      | 25        | 8.68%   |
| Gigabyte Technology                  | 25        | 8.68%   |
| MSI                                  | 16        | 5.56%   |
| Acer                                 | 12        | 4.17%   |
| Intel                                | 7         | 2.43%   |
| ASRock                               | 7         | 2.43%   |
| Toshiba                              | 4         | 1.39%   |
| Samsung Electronics                  | 4         | 1.39%   |
| Fujitsu                              | 4         | 1.39%   |
| Apple                                | 4         | 1.39%   |
| Google                               | 3         | 1.04%   |
| Fujitsu Siemens                      | 3         | 1.04%   |
| AMI                                  | 3         | 1.04%   |
| Unknown                              | 3         | 1.04%   |
| Sony                                 | 2         | 0.69%   |
| Notebook                             | 2         | 0.69%   |
| Nokia                                | 2         | 0.69%   |
| Nitrokey                             | 2         | 0.69%   |
| IBM                                  | 2         | 0.69%   |
| Foxconn                              | 2         | 0.69%   |
| VIT                                  | 1         | 0.35%   |
| TUXEDO                               | 1         | 0.35%   |
| Teclast                              | 1         | 0.35%   |
| System76                             | 1         | 0.35%   |
| Supermicro                           | 1         | 0.35%   |
| Sun Microsystems                     | 1         | 0.35%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.35%   |
| Raspberry Pi Foundation              | 1         | 0.35%   |
| Purism                               | 1         | 0.35%   |
| Positivo                             | 1         | 0.35%   |
| PC Specialist                        | 1         | 0.35%   |
| Packard Bell                         | 1         | 0.35%   |
| OrangePi                             | 1         | 0.35%   |
| Online Labs                          | 1         | 0.35%   |
| MTC                                  | 1         | 0.35%   |
| Microsoft                            | 1         | 0.35%   |
| Medion                               | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                                                     | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                                  | 4         | 1.39%   |
| Lenovo 70AQ000JGE ThinkServer TS440                                                      | 3         | 1.04%   |
| Dell Latitude E6430                                                                      | 3         | 1.04%   |
| Nokia N900                                                                               | 2         | 0.69%   |
| Nitrokey NitroPC                                                                         | 2         | 0.69%   |
| MSI MS-7693                                                                              | 2         | 0.69%   |
| HP EliteDesk 800 G3 DM 35W                                                               | 2         | 0.69%   |
| Gigabyte Z390 GAMING SLI                                                                 | 2         | 0.69%   |
| Gigabyte B550 AORUS ELITE AX V2                                                          | 2         | 0.69%   |
| Dell OptiPlex 7050                                                                       | 2         | 0.69%   |
| ASUS X555LJ                                                                              | 2         | 0.69%   |
| ASUS TUF B450-PRO GAMING                                                                 | 2         | 0.69%   |
| AMI Aptio CRB                                                                            | 2         | 0.69%   |
| VIT M2420                                                                                | 1         | 0.35%   |
| TUXEDO XP1610                                                                            | 1         | 0.35%   |
| Toshiba Satellite Pro A50-C                                                              | 1         | 0.35%   |
| Toshiba Satellite M40X                                                                   | 1         | 0.35%   |
| Toshiba Satellite L655                                                                   | 1         | 0.35%   |
| Toshiba Satellite L300                                                                   | 1         | 0.35%   |
| Teclast F6 Plus                                                                          | 1         | 0.35%   |
| System76 Galago Pro                                                                      | 1         | 0.35%   |
| Supermicro SYS-1018GR-T                                                                  | 1         | 0.35%   |
| Sun Microsystems Ultra 24                                                                | 1         | 0.35%   |
| Sony VPCEE23FX                                                                           | 1         | 0.35%   |
| Sony VGN-FZ140E                                                                          | 1         | 0.35%   |
| Shenzhen Meigao Electronic Equipment Mercury Series                                      | 1         | 0.35%   |
| Samsung N150P                                                                            | 1         | 0.35%   |
| Samsung DP505/DM515                                                                      | 1         | 0.35%   |
| Samsung 550XDA                                                                           | 1         | 0.35%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.35%   |
| RPi Raspberry Pi 2 Model B Rev 1.1                                                       | 1         | 0.35%   |
| Purism Librem 14                                                                         | 1         | 0.35%   |
| Positivo Positivo Master D610                                                            | 1         | 0.35%   |
| PC Specialist P7xxTM1                                                                    | 1         | 0.35%   |
| Packard Bell IMEDIA S1300                                                                | 1         | 0.35%   |
| OrangePi Zero2 W                                                                         | 1         | 0.35%   |
| Online Labs SR                                                                           | 1         | 0.35%   |
| Notebook W230ST                                                                          | 1         | 0.35%   |
| Notebook NV4XMB,ME,MZ                                                                    | 1         | 0.35%   |
| MTC Montara-GML                                                                          | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 31        | 10.76%  |
| Dell Latitude           | 14        | 4.86%   |
| Acer Aspire             | 10        | 3.47%   |
| Lenovo IdeaPad          | 8         | 2.78%   |
| Dell OptiPlex           | 7         | 2.43%   |
| ASUS PRIME              | 6         | 2.08%   |
| Toshiba Satellite       | 4         | 1.39%   |
| Dell Inspiron           | 4         | 1.39%   |
| Unknown                 | 4         | 1.39%   |
| Lenovo Yoga             | 3         | 1.04%   |
| Lenovo ThinkStation     | 3         | 1.04%   |
| Lenovo 70AQ000JGE       | 3         | 1.04%   |
| HP ProBook              | 3         | 1.04%   |
| HP Pavilion             | 3         | 1.04%   |
| HP Laptop               | 3         | 1.04%   |
| HP EliteDesk            | 3         | 1.04%   |
| Gigabyte B550           | 3         | 1.04%   |
| Dell XPS                | 3         | 1.04%   |
| ASUS TUF                | 3         | 1.04%   |
| ASUS ROG                | 3         | 1.04%   |
| Nokia N900              | 2         | 0.69%   |
| Nitrokey NitroPC        | 2         | 0.69%   |
| MSI MS-7693             | 2         | 0.69%   |
| Lenovo LOQ              | 2         | 0.69%   |
| IBM ThinkPad            | 2         | 0.69%   |
| HP Compaq               | 2         | 0.69%   |
| Gigabyte Z390           | 2         | 0.69%   |
| Fujitsu Siemens AMILO   | 2         | 0.69%   |
| Fujitsu ESPRIMO         | 2         | 0.69%   |
| Dell Precision          | 2         | 0.69%   |
| Dell PowerEdge          | 2         | 0.69%   |
| ASUS X555LJ             | 2         | 0.69%   |
| AMI Aptio               | 2         | 0.69%   |
| VIT M2420               | 1         | 0.35%   |
| TUXEDO XP1610           | 1         | 0.35%   |
| Teclast F6              | 1         | 0.35%   |
| System76 Galago         | 1         | 0.35%   |
| Supermicro SYS-1018GR-T | 1         | 0.35%   |
| Sun Microsystems Ultra  | 1         | 0.35%   |
| Sony VPCEE23FX          | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 33        | 11.46%  |
| 2019    | 27        | 9.38%   |
| 2013    | 21        | 7.29%   |
| 2012    | 20        | 6.94%   |
| 2014    | 18        | 6.25%   |
| 2010    | 17        | 5.9%    |
| 2020    | 16        | 5.56%   |
| 2008    | 16        | 5.56%   |
| 2021    | 15        | 5.21%   |
| 2017    | 14        | 4.86%   |
| 2016    | 14        | 4.86%   |
| 2022    | 12        | 4.17%   |
| 2011    | 12        | 4.17%   |
| 2009    | 12        | 4.17%   |
| 2015    | 8         | 2.78%   |
| 2023    | 7         | 2.43%   |
| 2007    | 7         | 2.43%   |
| 2006    | 5         | 1.74%   |
| 2024    | 4         | 1.39%   |
| 2005    | 4         | 1.39%   |
| Unknown | 4         | 1.39%   |
| 2025    | 1         | 0.35%   |
| 2000    | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 149       | 51.74%  |
| Desktop        | 116       | 40.28%  |
| Mini pc        | 9         | 3.13%   |
| Convertible    | 5         | 1.74%   |
| Tablet         | 3         | 1.04%   |
| System on chip | 2         | 0.69%   |
| All in one     | 2         | 0.69%   |
| Server         | 2         | 0.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 286       | 98.62%  |
| Enabled  | 4         | 1.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 276       | 95.83%  |
| Yes  | 12        | 4.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 62        | 21.38%  |
| 4.01-8.0        | 56        | 19.31%  |
| 8.01-16.0       | 52        | 17.93%  |
| 3.01-4.0        | 39        | 13.45%  |
| 32.01-64.0      | 31        | 10.69%  |
| 1.01-2.0        | 18        | 6.21%   |
| 64.01-256.0     | 13        | 4.48%   |
| 2.01-3.0        | 7         | 2.41%   |
| 24.01-32.0      | 4         | 1.38%   |
| 0.01-0.5        | 4         | 1.38%   |
| More than 256.0 | 2         | 0.69%   |
| 0.51-1.0        | 2         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 101       | 31.46%  |
| 4.01-8.0   | 53        | 16.51%  |
| 2.01-3.0   | 53        | 16.51%  |
| 0.51-1.0   | 40        | 12.46%  |
| 3.01-4.0   | 29        | 9.03%   |
| 8.01-16.0  | 23        | 7.17%   |
| 0.01-0.5   | 15        | 4.67%   |
| 16.01-24.0 | 5         | 1.56%   |
| 32.01-64.0 | 1         | 0.31%   |
| 24.01-32.0 | 1         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 175       | 60.14%  |
| 2      | 58        | 19.93%  |
| 3      | 27        | 9.28%   |
| 4      | 10        | 3.44%   |
| 5      | 7         | 2.41%   |
| 6      | 5         | 1.72%   |
| 9      | 3         | 1.03%   |
| 7      | 3         | 1.03%   |
| 0      | 2         | 0.69%   |
| 8      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 192       | 66.44%  |
| Yes       | 97        | 33.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 264       | 91.35%  |
| No        | 25        | 8.65%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 62.76%  |
| No        | 108       | 37.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 53.08%  |
| Yes       | 137       | 46.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 35        | 12.07%  |
| Russia          | 27        | 9.31%   |
| France          | 27        | 9.31%   |
| Germany         | 22        | 7.59%   |
| Brazil          | 18        | 6.21%   |
| Spain           | 16        | 5.52%   |
| Poland          | 11        | 3.79%   |
| Italy           | 10        | 3.45%   |
| Ukraine         | 9         | 3.1%    |
| UK              | 9         | 3.1%    |
| Hungary         | 9         | 3.1%    |
| Netherlands     | 7         | 2.41%   |
| Slovakia        | 6         | 2.07%   |
| Finland         | 6         | 2.07%   |
| Austria         | 6         | 2.07%   |
| Portugal        | 4         | 1.38%   |
| Mexico          | 4         | 1.38%   |
| Grenada         | 4         | 1.38%   |
| Georgia         | 4         | 1.38%   |
| Canada          | 4         | 1.38%   |
| Australia       | 4         | 1.38%   |
| Argentina       | 4         | 1.38%   |
| Switzerland     | 3         | 1.03%   |
| New Zealand     | 3         | 1.03%   |
| Belgium         | 3         | 1.03%   |
| South Africa    | 2         | 0.69%   |
| Norway          | 2         | 0.69%   |
| Japan           | 2         | 0.69%   |
| Israel          | 2         | 0.69%   |
| Indonesia       | 2         | 0.69%   |
| Iceland         | 2         | 0.69%   |
| Greece          | 2         | 0.69%   |
| China           | 2         | 0.69%   |
| Bulgaria        | 2         | 0.69%   |
| Belarus         | 2         | 0.69%   |
| Vietnam         | 1         | 0.34%   |
| Tunisia         | 1         | 0.34%   |
| The Netherlands | 1         | 0.34%   |
| South Korea     | 1         | 0.34%   |
| Singapore       | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Wroclaw             | 6         | 2.02%   |
| Issy-les-Moulineaux | 5         | 1.68%   |
| Bratislava          | 5         | 1.68%   |
| Bagnolet            | 5         | 1.68%   |
| Tbilisi             | 4         | 1.35%   |
| Sao Paulo           | 4         | 1.35%   |
| Saint George's      | 4         | 1.35%   |
| Paris               | 4         | 1.35%   |
| Munich              | 4         | 1.35%   |
| Moscow              | 4         | 1.35%   |
| Budapest            | 4         | 1.35%   |
| Amsterdam           | 4         | 1.35%   |
| Vienna              | 3         | 1.01%   |
| Rio de Janeiro      | 3         | 1.01%   |
| Molsheim            | 3         | 1.01%   |
| Madrid              | 3         | 1.01%   |
| Volzhskiy           | 2         | 0.67%   |
| Valencia            | 2         | 0.67%   |
| Toronto             | 2         | 0.67%   |
| Thessaloniki        | 2         | 0.67%   |
| Tel Aviv            | 2         | 0.67%   |
| Szombathely         | 2         | 0.67%   |
| Sydney              | 2         | 0.67%   |
| St Petersburg       | 2         | 0.67%   |
| Sofia               | 2         | 0.67%   |
| Sacramento          | 2         | 0.67%   |
| Roubaix             | 2         | 0.67%   |
| Reykjavik           | 2         | 0.67%   |
| Palmyra             | 2         | 0.67%   |
| Oslo                | 2         | 0.67%   |
| Nadudvar            | 2         | 0.67%   |
| Milan               | 2         | 0.67%   |
| Lisbon              | 2         | 0.67%   |
| Kyiv                | 2         | 0.67%   |
| Krasnodar           | 2         | 0.67%   |
| Jyväskylä         | 2         | 0.67%   |
| Joensuu             | 2         | 0.67%   |
| Ft. Washington      | 2         | 0.67%   |
| Buenos Aires        | 2         | 0.67%   |
| Auckland            | 2         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 68        | 120    | 16.11%  |
| Seagate             | 52        | 97     | 12.32%  |
| Samsung Electronics | 51        | 85     | 12.09%  |
| Kingston            | 32        | 51     | 7.58%   |
| Toshiba             | 19        | 19     | 4.5%    |
| Unknown             | 18        | 23     | 4.27%   |
| Crucial             | 18        | 24     | 4.27%   |
| SanDisk             | 17        | 19     | 4.03%   |
| Intel               | 17        | 24     | 4.03%   |
| Hitachi             | 11        | 11     | 2.61%   |
| SK hynix            | 7         | 7      | 1.66%   |
| HGST                | 7         | 7      | 1.66%   |
| PNY                 | 6         | 7      | 1.42%   |
| Micron Technology   | 6         | 7      | 1.42%   |
| China               | 6         | 6      | 1.42%   |
| Patriot             | 5         | 5      | 1.18%   |
| A-DATA Technology   | 5         | 5      | 1.18%   |
| Fujitsu             | 4         | 4      | 0.95%   |
| Team                | 3         | 3      | 0.71%   |
| Netac               | 3         | 3      | 0.71%   |
| LITEON              | 3         | 6      | 0.71%   |
| Lexar               | 3         | 3      | 0.71%   |
| Intenso             | 3         | 3      | 0.71%   |
| IBM-D050            | 3         | 12     | 0.71%   |
| Dogfish             | 3         | 3      | 0.71%   |
| Transcend           | 2         | 3      | 0.47%   |
| SABRENT             | 2         | 3      | 0.47%   |
| Phison Electronics  | 2         | 2      | 0.47%   |
| Maxtor              | 2         | 2      | 0.47%   |
| LITEONIT            | 2         | 2      | 0.47%   |
| Lenovo              | 2         | 2      | 0.47%   |
| IBM/Hitachi         | 2         | 2      | 0.47%   |
| Hewlett-Packard     | 2         | 3      | 0.47%   |
| Emtec               | 2         | 2      | 0.47%   |
| Corsair             | 2         | 2      | 0.47%   |
| Wicgtyp             | 1         | 1      | 0.24%   |
| WD MediaMax         | 1         | 3      | 0.24%   |
| Verbatim            | 1         | 1      | 0.24%   |
| Union Memory        | 1         | 2      | 0.24%   |
| UMIS                | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| Kingston SA400S37480G 480GB SSD | 7         | 1.49%   |
| Kingston SA400S37240G 240GB SSD | 7         | 1.49%   |
| Unknown MMC Card  32GB          | 5         | 1.06%   |
| Toshiba MQ04ABF100 1TB          | 5         | 1.06%   |
| Kingston SA400S37120G 120GB SSD | 5         | 1.06%   |
| Samsung SSD 870 EVO 1TB         | 4         | 0.85%   |
| Samsung SSD 860 EVO 250GB       | 4         | 0.85%   |
| PNY CS900 240GB SSD             | 4         | 0.85%   |
| Kingston SA2000M8250G 250GB     | 4         | 0.85%   |
| WDC WDS500G2B0A-00SM50 500GB    | 3         | 0.64%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3         | 0.64%   |
| WDC WD10EZEX-00BBHA0 1TB        | 3         | 0.64%   |
| Unknown MMC Card  128GB         | 3         | 0.64%   |
| Seagate ST4000NM0023 4TB        | 3         | 0.64%   |
| Samsung SSD 980 PRO 1TB         | 3         | 0.64%   |
| Samsung SSD 980 1TB             | 3         | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB  | 3         | 0.64%   |
| Samsung SSD 860 EVO 500GB       | 3         | 0.64%   |
| Samsung SSD 860 EVO 1TB         | 3         | 0.64%   |
| Samsung SSD 850 EVO 500GB       | 3         | 0.64%   |
| Samsung SSD 850 EVO 250GB       | 3         | 0.64%   |
| Intel SSDSC2KB240GZ 240GB       | 3         | 0.64%   |
| Intel SSDPEKKF256G8L 256GB      | 3         | 0.64%   |
| IBM-D050 ST4000NM0023 4TB       | 3         | 0.64%   |
| HGST HTS545050A7E680 500GB      | 3         | 0.64%   |
| Crucial CT1000MX500SSD1 1TB     | 3         | 0.64%   |
| WDC WD5000BPVT-24HXZT3 500GB    | 2         | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB        | 2         | 0.43%   |
| WDC WD20EFRX-68EUZN0 2TB        | 2         | 0.43%   |
| WDC WD10EARX-00N0YB0 1TB        | 2         | 0.43%   |
| WDC WD10EADS-22M2B0 1TB         | 2         | 0.43%   |
| Seagate ST9250410AS 250GB       | 2         | 0.43%   |
| Seagate ST500LT012-1DG142 500GB | 2         | 0.43%   |
| Seagate ST500LM021-1KJ152 500GB | 2         | 0.43%   |
| Seagate ST3500418AS 500GB       | 2         | 0.43%   |
| Seagate ST2000DX002-2DV164 2TB  | 2         | 0.43%   |
| Seagate ST2000DM008-2UB102 2TB  | 2         | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB  | 2         | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB  | 2         | 0.43%   |
| Seagate ST1000DM010-2EP102 1TB  | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 56        | 104    | 35.9%   |
| Seagate             | 51        | 96     | 32.69%  |
| Toshiba             | 14        | 14     | 8.97%   |
| Hitachi             | 11        | 11     | 7.05%   |
| HGST                | 7         | 7      | 4.49%   |
| Fujitsu             | 4         | 4      | 2.56%   |
| Samsung Electronics | 3         | 6      | 1.92%   |
| IBM-D050            | 3         | 12     | 1.92%   |
| Maxtor              | 2         | 2      | 1.28%   |
| IBM/Hitachi         | 2         | 2      | 1.28%   |
| Unknown             | 1         | 1      | 0.64%   |
| HPE                 | 1         | 2      | 0.64%   |
| Hewlett-Packard     | 1         | 2      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 38     | 19.48%  |
| Kingston            | 23        | 35     | 14.94%  |
| SanDisk             | 8         | 8      | 5.19%   |
| Intel               | 8         | 14     | 5.19%   |
| Crucial             | 8         | 12     | 5.19%   |
| WDC                 | 7         | 8      | 4.55%   |
| PNY                 | 6         | 7      | 3.9%    |
| China               | 6         | 6      | 3.9%    |
| Patriot             | 5         | 5      | 3.25%   |
| Micron Technology   | 4         | 4      | 2.6%    |
| Team                | 3         | 3      | 1.95%   |
| SK hynix            | 3         | 3      | 1.95%   |
| Netac               | 3         | 3      | 1.95%   |
| Dogfish             | 3         | 3      | 1.95%   |
| A-DATA Technology   | 3         | 3      | 1.95%   |
| Transcend           | 2         | 3      | 1.3%    |
| SABRENT             | 2         | 3      | 1.3%    |
| LITEONIT            | 2         | 2      | 1.3%    |
| LITEON              | 2         | 5      | 1.3%    |
| Intenso             | 2         | 2      | 1.3%    |
| Emtec               | 2         | 2      | 1.3%    |
| Wicgtyp             | 1         | 1      | 0.65%   |
| Verbatim            | 1         | 1      | 0.65%   |
| Union Memory        | 1         | 2      | 0.65%   |
| Toshiba             | 1         | 1      | 0.65%   |
| Teclast             | 1         | 1      | 0.65%   |
| Supermicro          | 1         | 1      | 0.65%   |
| SomnAmbulist        | 1         | 1      | 0.65%   |
| Smart               | 1         | 1      | 0.65%   |
| Plextor             | 1         | 1      | 0.65%   |
| Mushkin             | 1         | 1      | 0.65%   |
| Lexar               | 1         | 1      | 0.65%   |
| Kston               | 1         | 1      | 0.65%   |
| KingDian            | 1         | 1      | 0.65%   |
| HXY                 | 1         | 1      | 0.65%   |
| HUSKY               | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 1      | 0.65%   |
| GOODRAM             | 1         | 1      | 0.65%   |
| faspeed             | 1         | 1      | 0.65%   |
| Corsair             | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 138       | 192    | 36.22%  |
| HDD     | 131       | 263    | 34.38%  |
| NVMe    | 91        | 130    | 23.88%  |
| MMC     | 16        | 20     | 4.2%    |
| Unknown | 5         | 8      | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 215       | 446    | 64.18%  |
| NVMe | 91        | 128    | 27.16%  |
| MMC  | 16        | 20     | 4.78%   |
| SAS  | 13        | 19     | 3.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 165       | 236    | 59.35%  |
| 0.51-1.0   | 63        | 98     | 22.66%  |
| 1.01-2.0   | 26        | 49     | 9.35%   |
| 3.01-4.0   | 16        | 56     | 5.76%   |
| 2.01-3.0   | 4         | 9      | 1.44%   |
| 4.01-10.0  | 4         | 7      | 1.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 65        | 21.74%  |
| 101-250        | 60        | 20.07%  |
| 501-1000       | 50        | 16.72%  |
| 51-100         | 28        | 9.36%   |
| More than 3000 | 26        | 8.7%    |
| 1001-2000      | 23        | 7.69%   |
| 21-50          | 18        | 6.02%   |
| 1-20           | 11        | 3.68%   |
| Unknown        | 10        | 3.34%   |
| 2001-3000      | 8         | 2.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 95        | 31.25%  |
| 101-250        | 48        | 15.79%  |
| 21-50          | 39        | 12.83%  |
| 251-500        | 31        | 10.2%   |
| 51-100         | 31        | 10.2%   |
| 1001-2000      | 16        | 5.26%   |
| 501-1000       | 15        | 4.93%   |
| More than 3000 | 13        | 4.28%   |
| Unknown        | 10        | 3.29%   |
| 2001-3000      | 6         | 1.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB            | 3         | 3      | 5.56%   |
| WDC WD5000BPVT-24HXZT3 500GB          | 2         | 2      | 3.7%    |
| Seagate ST500LM021-1KJ152 500GB       | 2         | 2      | 3.7%    |
| Hitachi HDS721616PLA380 160GB         | 2         | 2      | 3.7%    |
| China SSD 256GB                       | 2         | 2      | 3.7%    |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 1.85%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 1      | 1.85%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 1.85%   |
| WDC WD5000AAKS-08V0A0 500GB           | 1         | 2      | 1.85%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 1.85%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 2      | 1.85%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 3      | 1.85%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 1.85%   |
| WDC WD1502FAEX-007BA0 1TB             | 1         | 1      | 1.85%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 1.85%   |
| WDC WD10EARX-00N0YB0 1TB              | 1         | 1      | 1.85%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 1.85%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 1.85%   |
| Toshiba MQ02ABF100 1TB                | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.85%   |
| SomnAmbulist SSD 120GB                | 1         | 1      | 1.85%   |
| SK hynix SH920 mSATA 128GB SSD        | 1         | 1      | 1.85%   |
| Seagate ST9200420ASG 200GB            | 1         | 1      | 1.85%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 1.85%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.85%   |
| Seagate ST320LT020-9YG142 320GB       | 1         | 1      | 1.85%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.85%   |
| Seagate ST1000LM014-SSHD-8GB          | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 1.85%   |
| Samsung Electronics SP2504C 250GB     | 1         | 1      | 1.85%   |
| Samsung Electronics HD160JJ 160GB     | 1         | 1      | 1.85%   |
| Maxtor 6E040L0 41GB                   | 1         | 1      | 1.85%   |
| Kingston SMS200S3120G 120GB SSD       | 1         | 1      | 1.85%   |
| Kingston SA400S37240G 240GB SSD       | 1         | 1      | 1.85%   |
| Kingston SA400S37120G 120GB SSD       | 1         | 1      | 1.85%   |
| Intel SSDSC2KF256H6 SATA 256GB        | 1         | 1      | 1.85%   |
| Intel SSDSC2BF120A5 120GB             | 1         | 3      | 1.85%   |
| IBM/Hitachi IC25N060ATMR04-0 64GB     | 1         | 1      | 1.85%   |
| HPE MB4000GEFNA 4TB                   | 1         | 2      | 1.85%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 17     | 23.08%  |
| Seagate             | 8         | 8      | 15.38%  |
| Hitachi             | 6         | 6      | 11.54%  |
| Toshiba             | 4         | 4      | 7.69%   |
| HGST                | 4         | 4      | 7.69%   |
| Kingston            | 3         | 3      | 5.77%   |
| China               | 3         | 3      | 5.77%   |
| Samsung Electronics | 2         | 3      | 3.85%   |
| Intel               | 2         | 4      | 3.85%   |
| Fujitsu             | 2         | 2      | 3.85%   |
| SomnAmbulist        | 1         | 1      | 1.92%   |
| SK hynix            | 1         | 1      | 1.92%   |
| Maxtor              | 1         | 1      | 1.92%   |
| IBM/Hitachi         | 1         | 1      | 1.92%   |
| HPE                 | 1         | 2      | 1.92%   |
| Hewlett-Packard     | 1         | 2      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 17     | 30%     |
| Seagate             | 8         | 8      | 20%     |
| Hitachi             | 6         | 6      | 15%     |
| HGST                | 4         | 4      | 10%     |
| Toshiba             | 3         | 3      | 7.5%    |
| Fujitsu             | 2         | 2      | 5%      |
| Samsung Electronics | 1         | 2      | 2.5%    |
| Maxtor              | 1         | 1      | 2.5%    |
| IBM/Hitachi         | 1         | 1      | 2.5%    |
| HPE                 | 1         | 2      | 2.5%    |
| Hewlett-Packard     | 1         | 2      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 48     | 76.92%  |
| SSD  | 11        | 13     | 21.15%  |
| NVMe | 1         | 1      | 1.92%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 201       | 421    | 61.66%  |
| Detected | 75        | 130    | 23.01%  |
| Malfunc  | 50        | 62     | 15.34%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 192       | 53.93%  |
| AMD                              | 48        | 13.48%  |
| Samsung Electronics              | 24        | 6.74%   |
| Sandisk                          | 15        | 4.21%   |
| Kingston Technology Company      | 11        | 3.09%   |
| Micron/Crucial Technology        | 10        | 2.81%   |
| Marvell Technology Group         | 5         | 1.4%    |
| Toshiba America Info Systems     | 4         | 1.12%   |
| SK hynix                         | 4         | 1.12%   |
| Nvidia                           | 4         | 1.12%   |
| LSI Logic / Symbios Logic        | 4         | 1.12%   |
| VIA Technologies                 | 3         | 0.84%   |
| Silicon Motion                   | 3         | 0.84%   |
| Phison Electronics               | 3         | 0.84%   |
| Micron Technology                | 3         | 0.84%   |
| ADATA Technology                 | 3         | 0.84%   |
| Lenovo                           | 2         | 0.56%   |
| Broadcom / LSI                   | 2         | 0.56%   |
| ASMedia Technology               | 2         | 0.56%   |
| Union Memory (Shenzhen)          | 1         | 0.28%   |
| Solidigm                         | 1         | 0.28%   |
| Solid State Storage Technology   | 1         | 0.28%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |
| Shenzhen Longsys Electronics     | 1         | 0.28%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.28%   |
| Lite-On Technology               | 1         | 0.28%   |
| KIOXIA                           | 1         | 0.28%   |
| Integrated Technology Express    | 1         | 0.28%   |
| INNOGRIT                         | 1         | 0.28%   |
| HighPoint Technologies           | 1         | 0.28%   |
| Chelsio Communications           | 1         | 0.28%   |
| Biwin Storage Technology         | 1         | 0.28%   |
| Adaptec                          | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 6.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 3.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 2.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 2.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 9         | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 2.17%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 8         | 1.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 1.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 1.93%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 7         | 1.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 7         | 1.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 1.45%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 6         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.45%   |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 1.2%    |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                     | 5         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 1.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.2%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 5         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.96%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 0.96%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                        | 4         | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 0.96%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 4         | 0.96%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 0.96%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 0.96%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                         | 4         | 0.96%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                    | 3         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 196       | 54.75%  |
| NVMe | 91        | 25.42%  |
| IDE  | 50        | 13.97%  |
| RAID | 19        | 5.31%   |
| SCSI | 2         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 224       | 77.78%  |
| AMD    | 60        | 20.83%  |
| ARM    | 4         | 1.39%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 2.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.38%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.38%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz           | 3         | 1.04%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 3         | 1.04%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.04%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 3         | 1.04%   |
| AMD FX-8300 Eight-Core Processor              | 3         | 1.04%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.69%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.69%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 2         | 0.69%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 2         | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.69%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2         | 0.69%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.69%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 0.69%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz         | 2         | 0.69%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 2         | 0.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.69%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2         | 0.69%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.69%   |
| Intel 12th Gen Core i5-12500H                 | 2         | 0.69%   |
| ARM Nokia RX-51 board Processor               | 2         | 0.69%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 2         | 0.69%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 2         | 0.69%   |
| AMD Ryzen 5 5600 6-Core Processor             | 2         | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.69%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.69%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.69%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 0.69%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 0.69%   |
| Intel Xeon w5-2465X                           | 1         | 0.35%   |
| Intel Xeon CPU X3460 @ 2.80GHz                | 1         | 0.35%   |
| Intel Xeon CPU X3430 @ 2.40GHz                | 1         | 0.35%   |
| Intel Xeon CPU E5-2696 v3 @ 2.30GHz           | 1         | 0.35%   |
| Intel Xeon CPU E5-2683 v4 @ 2.10GHz           | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 52        | 17.99%  |
| Intel Core i7           | 46        | 15.92%  |
| Intel Core i3           | 22        | 7.61%   |
| Other                   | 21        | 7.27%   |
| Intel Celeron           | 20        | 6.92%   |
| AMD Ryzen 5             | 18        | 6.23%   |
| Intel Xeon              | 14        | 4.84%   |
| AMD Ryzen 7             | 12        | 4.15%   |
| Intel Core 2 Duo        | 11        | 3.81%   |
| Intel Atom              | 7         | 2.42%   |
| Intel Pentium Dual-Core | 6         | 2.08%   |
| Intel Pentium M         | 5         | 1.73%   |
| Intel Pentium           | 5         | 1.73%   |
| AMD FX                  | 4         | 1.38%   |
| AMD A10                 | 4         | 1.38%   |
| Intel Pentium Dual      | 3         | 1.04%   |
| Intel Core i9           | 3         | 1.04%   |
| Intel Core 2 Quad       | 3         | 1.04%   |
| Intel Core 2            | 3         | 1.04%   |
| Intel Celeron M         | 2         | 0.69%   |
| AMD Ryzen 3             | 2         | 0.69%   |
| AMD Athlon II           | 2         | 0.69%   |
| AMD A6                  | 2         | 0.69%   |
| Intel Pentium Silver    | 1         | 0.35%   |
| Intel Pentium Gold      | 1         | 0.35%   |
| Intel Pentium D         | 1         | 0.35%   |
| Intel Pentium 4         | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core m5           | 1         | 0.35%   |
| Intel Core              | 1         | 0.35%   |
| ARM BCM                 | 1         | 0.35%   |
| AMD Turion 64 X2        | 1         | 0.35%   |
| AMD Sempron             | 1         | 0.35%   |
| AMD Ryzen Threadripper  | 1         | 0.35%   |
| AMD Ryzen 9             | 1         | 0.35%   |
| AMD Ryzen 7 PRO         | 1         | 0.35%   |
| AMD Ryzen 5 PRO         | 1         | 0.35%   |
| AMD Phenom II X4        | 1         | 0.35%   |
| AMD GX                  | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 109       | 37.85%  |
| 4       | 88        | 30.56%  |
| 6       | 36        | 12.5%   |
| 8       | 20        | 6.94%   |
| 1       | 20        | 6.94%   |
| 10      | 5         | 1.74%   |
| 12      | 4         | 1.39%   |
| 16      | 2         | 0.69%   |
| 36      | 1         | 0.35%   |
| 24      | 1         | 0.35%   |
| 14      | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 285       | 98.96%  |
| 2       | 2         | 0.69%   |
| Unknown | 1         | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 166       | 57.44%  |
| 1       | 122       | 42.21%  |
| Unknown | 1         | 0.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 274       | 95.14%  |
| 32-bit         | 9         | 3.13%   |
| Unknown        | 5         | 1.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 107       | 35.79%  |
| 0x306a9    | 13        | 4.35%   |
| 0x306c3    | 12        | 4.01%   |
| 0x906ea    | 10        | 3.34%   |
| 0x1067a    | 10        | 3.34%   |
| 0x206a7    | 9         | 3.01%   |
| 0x806ec    | 8         | 2.68%   |
| 0x406e3    | 8         | 2.68%   |
| 0x40651    | 7         | 2.34%   |
| 0x20655    | 6         | 2.01%   |
| 0x506e3    | 5         | 1.67%   |
| 0x806ea    | 4         | 1.34%   |
| 0x806c1    | 4         | 1.34%   |
| 0x6fd      | 4         | 1.34%   |
| 0x406c4    | 4         | 1.34%   |
| 0x30678    | 4         | 1.34%   |
| 0x706a1    | 3         | 1%      |
| 0x6d8      | 3         | 1%      |
| 0x306d4    | 3         | 1%      |
| 0x08701021 | 3         | 1%      |
| 0x0800820d | 3         | 1%      |
| 0xa0653    | 2         | 0.67%   |
| 0x906ed    | 2         | 0.67%   |
| 0x906e9    | 2         | 0.67%   |
| 0x906a3    | 2         | 0.67%   |
| 0x706a8    | 2         | 0.67%   |
| 0x6f6      | 2         | 0.67%   |
| 0x695      | 2         | 0.67%   |
| 0x20652    | 2         | 0.67%   |
| 0x106e5    | 2         | 0.67%   |
| 0x10676    | 2         | 0.67%   |
| 0x0a20120a | 2         | 0.67%   |
| 0x08608103 | 2         | 0.67%   |
| 0x0810100b | 2         | 0.67%   |
| 0x08001138 | 2         | 0.67%   |
| 0xf49      | 1         | 0.33%   |
| 0xb06e0    | 1         | 0.33%   |
| 0xb06a3    | 1         | 0.33%   |
| 0xb0671    | 1         | 0.33%   |
| 0xa0655    | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 14.48%  |
| Haswell          | 30        | 10.34%  |
| Penryn           | 17        | 5.86%   |
| IvyBridge        | 17        | 5.86%   |
| Skylake          | 15        | 5.17%   |
| Unknown          | 15        | 5.17%   |
| Westmere         | 12        | 4.14%   |
| Silvermont       | 12        | 4.14%   |
| Core             | 12        | 4.14%   |
| SandyBridge      | 11        | 3.79%   |
| Zen              | 9         | 3.1%    |
| Zen 3            | 8         | 2.76%   |
| Zen 2            | 8         | 2.76%   |
| Piledriver       | 8         | 2.76%   |
| P6               | 8         | 2.76%   |
| Alderlake Hybrid | 8         | 2.76%   |
| Zen+             | 6         | 2.07%   |
| TigerLake        | 6         | 2.07%   |
| CometLake        | 6         | 2.07%   |
| Broadwell        | 6         | 2.07%   |
| Goldmont plus    | 5         | 1.72%   |
| Nehalem          | 4         | 1.38%   |
| K10              | 4         | 1.38%   |
| Excavator        | 3         | 1.03%   |
| Bonnell          | 3         | 1.03%   |
| NetBurst         | 2         | 0.69%   |
| K8 Hammer        | 2         | 0.69%   |
| Jaguar           | 2         | 0.69%   |
| Gracemont        | 2         | 0.69%   |
| Bobcat           | 2         | 0.69%   |
| Tremont          | 1         | 0.34%   |
| Sapphire Rapids  | 1         | 0.34%   |
| Puma             | 1         | 0.34%   |
| K10 Llano        | 1         | 0.34%   |
| Goldmont         | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 172       | 54.6%   |
| AMD                              | 70        | 22.22%  |
| Nvidia                           | 68        | 21.59%  |
| VIA Technologies                 | 2         | 0.63%   |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |
| Matrox Electronics Systems       | 1         | 0.32%   |
| ASPEED Technology                | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 3.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.73%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.12%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 6         | 1.82%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.52%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 5         | 1.52%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.52%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.21%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 4         | 1.21%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 1.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.21%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 4         | 1.21%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.21%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 4         | 1.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.21%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.91%   |
| Intel Xeon E3-1200 v3 Processor Integrated Graphics Controller                           | 3         | 0.91%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 0.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 0.91%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 3         | 0.91%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 3         | 0.91%   |
| AMD Lucienne                                                                             | 3         | 0.91%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.61%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 132       | 45.67%  |
| 1 x AMD        | 56        | 19.38%  |
| 1 x Nvidia     | 42        | 14.53%  |
| Intel + Nvidia | 25        | 8.65%   |
| Other          | 8         | 2.77%   |
| 2 x AMD        | 8         | 2.77%   |
| 2 x Intel      | 7         | 2.42%   |
| Intel + AMD    | 5         | 1.73%   |
| 1 x VIA        | 2         | 0.69%   |
| 1 x SiS        | 1         | 0.35%   |
| 1 x Matrox     | 1         | 0.35%   |
| 1 x ASPEED     | 1         | 0.35%   |
| AMD + Nvidia   | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 236       | 81.38%  |
| Proprietary | 32        | 11.03%  |
| Unknown     | 22        | 7.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 195       | 66.1%   |
| 0.01-0.5   | 25        | 8.47%   |
| 0.51-1.0   | 19        | 6.44%   |
| 7.01-8.0   | 16        | 5.42%   |
| 1.01-2.0   | 14        | 4.75%   |
| 3.01-4.0   | 12        | 4.07%   |
| 5.01-6.0   | 8         | 2.71%   |
| 2.01-3.0   | 3         | 1.02%   |
| 8.01-16.0  | 3         | 1.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 41        | 13.49%  |
| BOE                     | 28        | 9.21%   |
| AU Optronics            | 27        | 8.88%   |
| LG Display              | 25        | 8.22%   |
| Chimei Innolux          | 19        | 6.25%   |
| Dell                    | 16        | 5.26%   |
| Goldstar                | 15        | 4.93%   |
| Hewlett-Packard         | 13        | 4.28%   |
| Philips                 | 12        | 3.95%   |
| Lenovo                  | 12        | 3.95%   |
| Acer                    | 12        | 3.95%   |
| Ancor Communications    | 9         | 2.96%   |
| Iiyama                  | 6         | 1.97%   |
| AOC                     | 6         | 1.97%   |
| Unknown                 | 5         | 1.64%   |
| PANDA                   | 5         | 1.64%   |
| Chi Mei Optoelectronics | 5         | 1.64%   |
| BenQ                    | 4         | 1.32%   |
| Sharp                   | 3         | 0.99%   |
| Apple                   | 3         | 0.99%   |
| Toshiba                 | 2         | 0.66%   |
| Sony                    | 2         | 0.66%   |
| MStar                   | 2         | 0.66%   |
| MiTAC                   | 2         | 0.66%   |
| InnoLux Display         | 2         | 0.66%   |
| CHI                     | 2         | 0.66%   |
| ___                     | 1         | 0.33%   |
| ZLX                     | 1         | 0.33%   |
| ViewSonic               | 1         | 0.33%   |
| TMA                     | 1         | 0.33%   |
| STD                     | 1         | 0.33%   |
| Sceptre Tech            | 1         | 0.33%   |
| PCT                     | 1         | 0.33%   |
| Packard Bell            | 1         | 0.33%   |
| MSI                     | 1         | 0.33%   |
| Lenovo Group Limited    | 1         | 0.33%   |
| InfoVision              | 1         | 0.33%   |
| HJW                     | 1         | 0.33%   |
| Hisense                 | 1         | 0.33%   |
| HannStar                | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.96%   |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch     | 3         | 0.96%   |
| Samsung Electronics S24D340 SAM0BBB 1920x1080 531x299mm 24.0-inch     | 3         | 0.96%   |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch  | 2         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 2         | 0.64%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch               | 2         | 0.64%   |
| Philips 17S PHL0877 1280x1024 337x270mm 17.0-inch                     | 2         | 0.64%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 2         | 0.64%   |
| MiTAC MTC26T42 MTC0B01 1280x720 708x398mm 32.0-inch                   | 2         | 0.64%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.64%   |
| Lenovo LCD Monitor LEN4010 1280x800 261x163mm 12.1-inch               | 2         | 0.64%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch      | 2         | 0.64%   |
| Hewlett-Packard 22m HPN3575 1920x1080 476x268mm 21.5-inch             | 2         | 0.64%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.64%   |
| Dell P2717H DEL40F7 1920x1080 598x336mm 27.0-inch                     | 2         | 0.64%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                 | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.64%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.64%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 2         | 0.64%   |
| Acer AL1707 A ACRAD46 1280x1024 338x270mm 17.0-inch                   | 2         | 0.64%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.32%   |
| ZLX Dummy display ZLX0301 1920x1080 480x270mm 21.7-inch               | 1         | 0.32%   |
| ViewSonic VA2261 Series VSC0F30 1920x1080 477x268mm 21.5-inch         | 1         | 0.32%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.32%   |
| Unknown LCD Monitor hp L1702 1280x1024                                | 1         | 0.32%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                     | 1         | 0.32%   |
| Toshiba TV TSB010D 1920x1080 529x299mm 23.9-inch                      | 1         | 0.32%   |
| TMA LCD Monitor TMA2036 2880x1800 330x206mm 15.3-inch                 | 1         | 0.32%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 0.32%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                         | 1         | 0.32%   |
| Sony SDM-HS95 SNY2700 1280x1024 380x300mm 19.1-inch                   | 1         | 0.32%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP144F 1920x1080 276x156mm 12.5-inch               | 1         | 0.32%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.32%   |
| Sceptre Tech Sceptre F22 SPT08E3 1920x1080 475x267mm 21.5-inch        | 1         | 0.32%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch     | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                      | 1         | 0.32%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch  | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 125       | 42.96%  |
| 1366x768 (WXGA)    | 61        | 20.96%  |
| 3840x2160 (4K)     | 13        | 4.47%   |
| 1280x1024 (SXGA)   | 12        | 4.12%   |
| 2560x1440 (QHD)    | 11        | 3.78%   |
| 1920x1200 (WUXGA)  | 11        | 3.78%   |
| 1600x900 (HD+)     | 9         | 3.09%   |
| 1440x900 (WXGA+)   | 9         | 3.09%   |
| 1680x1050 (WSXGA+) | 6         | 2.06%   |
| 1280x800 (WXGA)    | 6         | 2.06%   |
| Unknown            | 4         | 1.37%   |
| 2288x1287          | 3         | 1.03%   |
| 5760x1080          | 2         | 0.69%   |
| 3440x1440          | 2         | 0.69%   |
| 1920x540           | 2         | 0.69%   |
| 1600x1200          | 2         | 0.69%   |
| 1360x768           | 2         | 0.69%   |
| 1024x600           | 2         | 0.69%   |
| 4480x1440          | 1         | 0.34%   |
| 3200x1800 (QHD+)   | 1         | 0.34%   |
| 3000x2000          | 1         | 0.34%   |
| 2880x1800          | 1         | 0.34%   |
| 2736x1824          | 1         | 0.34%   |
| 2256x1504          | 1         | 0.34%   |
| 2160x1440          | 1         | 0.34%   |
| 2048x1152          | 1         | 0.34%   |
| 1024x768 (XGA)     | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 65        | 21.59%  |
| 24      | 32        | 10.63%  |
| 14      | 25        | 8.31%   |
| 21      | 23        | 7.64%   |
| 27      | 19        | 6.31%   |
| 13      | 19        | 6.31%   |
| 12      | 16        | 5.32%   |
| Unknown | 13        | 4.32%   |
| 23      | 12        | 3.99%   |
| 17      | 11        | 3.65%   |
| 19      | 9         | 2.99%   |
| 31      | 8         | 2.66%   |
| 18      | 8         | 2.66%   |
| 11      | 6         | 1.99%   |
| 22      | 5         | 1.66%   |
| 52      | 4         | 1.33%   |
| 32      | 4         | 1.33%   |
| 142     | 3         | 1%      |
| 54      | 3         | 1%      |
| 72      | 2         | 0.66%   |
| 34      | 2         | 0.66%   |
| 25      | 2         | 0.66%   |
| 16      | 2         | 0.66%   |
| 10      | 2         | 0.66%   |
| 84      | 1         | 0.33%   |
| 46      | 1         | 0.33%   |
| 40      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 26      | 1         | 0.33%   |
| 20      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 104       | 35.74%  |
| 501-600        | 61        | 20.96%  |
| 401-500        | 37        | 12.71%  |
| 201-300        | 34        | 11.68%  |
| Unknown        | 13        | 4.47%   |
| 351-400        | 12        | 4.12%   |
| 601-700        | 8         | 2.75%   |
| 1001-1500      | 8         | 2.75%   |
| 701-800        | 6         | 2.06%   |
| More than 2000 | 3         | 1.03%   |
| 1501-2000      | 3         | 1.03%   |
| 801-900        | 2         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 203       | 75.19%  |
| 16/10   | 33        | 12.22%  |
| Unknown | 10        | 3.7%    |
| 5/4     | 8         | 2.96%   |
| 4/3     | 4         | 1.48%   |
| 3/2     | 4         | 1.48%   |
| 6/5     | 3         | 1.11%   |
| 1.00    | 3         | 1.11%   |
| 21/9    | 2         | 0.74%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 21.21%  |
| 201-250        | 57        | 19.19%  |
| 81-90          | 35        | 11.78%  |
| 301-350        | 19        | 6.4%    |
| 61-70          | 16        | 5.39%   |
| 151-200        | 15        | 5.05%   |
| 351-500        | 14        | 4.71%   |
| More than 1000 | 13        | 4.38%   |
| Unknown        | 13        | 4.38%   |
| 141-150        | 12        | 4.04%   |
| 251-300        | 11        | 3.7%    |
| 71-80          | 9         | 3.03%   |
| 51-60          | 6         | 2.02%   |
| 111-120        | 4         | 1.35%   |
| 121-130        | 3         | 1.01%   |
| 501-1000       | 3         | 1.01%   |
| 41-50          | 2         | 0.67%   |
| 131-140        | 2         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 100       | 34.6%   |
| 101-120       | 73        | 25.26%  |
| 121-160       | 67        | 23.18%  |
| 161-240       | 19        | 6.57%   |
| 1-50          | 13        | 4.5%    |
| Unknown       | 13        | 4.5%    |
| More than 240 | 4         | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 232       | 77.08%  |
| 2     | 43        | 14.29%  |
| 0     | 17        | 5.65%   |
| 3     | 9         | 2.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 147       | 33.72%  |
| Intel                            | 132       | 30.28%  |
| Qualcomm Atheros                 | 51        | 11.7%   |
| Broadcom                         | 18        | 4.13%   |
| MediaTek                         | 12        | 2.75%   |
| Marvell Technology Group         | 8         | 1.83%   |
| Ralink Technology                | 7         | 1.61%   |
| Broadcom Limited                 | 7         | 1.61%   |
| TP-Link                          | 5         | 1.15%   |
| Samsung Electronics              | 4         | 0.92%   |
| NetGear                          | 4         | 0.92%   |
| VIA Technologies                 | 3         | 0.69%   |
| Sierra Wireless                  | 3         | 0.69%   |
| Nvidia                           | 3         | 0.69%   |
| ICS Advent                       | 3         | 0.69%   |
| Espressif                        | 3         | 0.69%   |
| ASIX Electronics                 | 3         | 0.69%   |
| Ralink                           | 2         | 0.46%   |
| JMicron Technology               | 2         | 0.46%   |
| D-Link System                    | 2         | 0.46%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.23%   |
| Xiaomi                           | 1         | 0.23%   |
| STMicroelectronics               | 1         | 0.23%   |
| Solarflare Communications        | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Shenzhen Goodix Technology       | 1         | 0.23%   |
| Seiko Epson                      | 1         | 0.23%   |
| Qualcomm                         | 1         | 0.23%   |
| Motorola PCS                     | 1         | 0.23%   |
| Microchip Technology             | 1         | 0.23%   |
| Huawei Technologies              | 1         | 0.23%   |
| Hewlett-Packard                  | 1         | 0.23%   |
| Edimax Technology                | 1         | 0.23%   |
| DisplayLink                      | 1         | 0.23%   |
| Dell                             | 1         | 0.23%   |
| Chelsio Communications           | 1         | 0.23%   |
| Aquantia                         | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 111       | 21.64%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 3.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 2.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 10        | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 1.56%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 1.36%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.17%   |
| Intel Wireless 8265 / 8275                                             | 6         | 1.17%   |
| Intel Wireless 8260                                                    | 6         | 1.17%   |
| Intel Wireless 7260                                                    | 6         | 1.17%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.97%   |
| Intel Wireless 7265                                                    | 5         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.78%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.78%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 4         | 0.78%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 4         | 0.78%   |
| Intel Ethernet Controller I225-V                                       | 4         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.78%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller      | 4         | 0.78%   |
| Sierra Wireless EM7455                                                 | 3         | 0.58%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 3         | 0.58%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection               | 3         | 0.58%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.58%   |
| Intel Centrino Advanced-N 6200                                         | 3         | 0.58%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 74        | 38.14%  |
| Qualcomm Atheros         | 43        | 22.16%  |
| Realtek Semiconductor    | 28        | 14.43%  |
| MediaTek                 | 11        | 5.67%   |
| Broadcom                 | 9         | 4.64%   |
| Ralink Technology        | 7         | 3.61%   |
| Broadcom Limited         | 6         | 3.09%   |
| NetGear                  | 4         | 2.06%   |
| TP-Link                  | 3         | 1.55%   |
| Sierra Wireless          | 3         | 1.55%   |
| Ralink                   | 2         | 1.03%   |
| Marvell Technology Group | 1         | 0.52%   |
| Hewlett-Packard          | 1         | 0.52%   |
| Edimax Technology        | 1         | 0.52%   |
| Dell                     | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 10        | 5.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.61%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.09%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.09%   |
| Intel Wireless 8260                                                     | 6         | 3.09%   |
| Intel Wireless 7260                                                     | 6         | 3.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2.58%   |
| Intel Wireless 7265                                                     | 5         | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 2.06%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 4         | 2.06%   |
| Sierra Wireless EM7455                                                  | 3         | 1.55%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 1.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.55%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 3         | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.55%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.55%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 3         | 1.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.03%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.03%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 2         | 1.03%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.03%   |
| NetGear WNA3100M(v1) Wireless-N 300 [Realtek RTL8192CU]                 | 2         | 1.03%   |
| NetGear WG111v3 54 Mbps Wireless [realtek RTL8187B]                     | 2         | 1.03%   |
| Intel Wireless 3165                                                     | 2         | 1.03%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 1.03%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 138       | 47.1%   |
| Intel                            | 92        | 31.4%   |
| Qualcomm Atheros                 | 11        | 3.75%   |
| Broadcom                         | 10        | 3.41%   |
| Marvell Technology Group         | 7         | 2.39%   |
| Samsung Electronics              | 4         | 1.37%   |
| VIA Technologies                 | 3         | 1.02%   |
| Nvidia                           | 3         | 1.02%   |
| ICS Advent                       | 3         | 1.02%   |
| ASIX Electronics                 | 3         | 1.02%   |
| TP-Link                          | 2         | 0.68%   |
| JMicron Technology               | 2         | 0.68%   |
| D-Link System                    | 2         | 0.68%   |
| Xiaomi                           | 1         | 0.34%   |
| Solarflare Communications        | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Seiko Epson                      | 1         | 0.34%   |
| Qualcomm                         | 1         | 0.34%   |
| Motorola PCS                     | 1         | 0.34%   |
| Microchip Technology             | 1         | 0.34%   |
| MediaTek                         | 1         | 0.34%   |
| Huawei Technologies              | 1         | 0.34%   |
| DisplayLink                      | 1         | 0.34%   |
| Chelsio Communications           | 1         | 0.34%   |
| Broadcom Limited                 | 1         | 0.34%   |
| Aquantia                         | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 111       | 36.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 5.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 15        | 4.87%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.95%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 1.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.62%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 1.3%    |
| Intel Ethernet Controller I225-V                                       | 4         | 1.3%    |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 1.3%    |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.97%   |
| ICS Advent 10/100M LAN                                                 | 3         | 0.97%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 2         | 0.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.65%   |
| Intel I350 Gigabit Network Connection                                  | 2         | 0.65%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.65%   |
| Intel Ethernet Controller I226-V                                       | 2         | 0.65%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.65%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.65%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.65%   |
| Intel 82578DM Gigabit Network Connection                               | 2         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.32%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 1         | 0.32%   |
| Solarflare SFC9020 10G Ethernet Controller                             | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.32%   |
| Seiko Epson ELPAP02 Ethernet unit                                      | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 264       | 57.77%  |
| WiFi     | 182       | 39.82%  |
| Modem    | 11        | 2.41%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 161       | 55.14%  |
| WiFi     | 130       | 44.52%  |
| Modem    | 1         | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 157       | 54.14%  |
| 1     | 110       | 37.93%  |
| 0     | 11        | 3.79%   |
| 3     | 8         | 2.76%   |
| 4     | 2         | 0.69%   |
| 7     | 1         | 0.34%   |
| 5     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 235       | 81.6%   |
| Yes  | 53        | 18.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 36.88%  |
| Qualcomm Atheros Communications | 15        | 10.64%  |
| Realtek Semiconductor           | 12        | 8.51%   |
| IMC Networks                    | 9         | 6.38%   |
| Broadcom                        | 9         | 6.38%   |
| Cambridge Silicon Radio         | 7         | 4.96%   |
| Lite-On Technology              | 6         | 4.26%   |
| MediaTek                        | 5         | 3.55%   |
| Dell                            | 5         | 3.55%   |
| ASUSTek Computer                | 5         | 3.55%   |
| Foxconn / Hon Hai               | 4         | 2.84%   |
| Foxconn International           | 3         | 2.13%   |
| Apple                           | 3         | 2.13%   |
| TP-Link                         | 1         | 0.71%   |
| Realtek                         | 1         | 0.71%   |
| Ralink                          | 1         | 0.71%   |
| Marvell Semiconductor           | 1         | 0.71%   |
| Hewlett-Packard                 | 1         | 0.71%   |
| Fujitsu                         | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 23        | 16.31%  |
| Realtek Bluetooth Radio                             | 12        | 8.51%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 7.8%    |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 7.09%   |
| Intel AX200 Bluetooth                               | 7         | 4.96%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 4.96%   |
| MediaTek Wireless_Device                            | 5         | 3.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 3.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 2.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2.13%   |
| Intel Bluetooth Device                              | 3         | 2.13%   |
| IMC Networks Wireless_Device                        | 3         | 2.13%   |
| IMC Networks Bluetooth Device                       | 3         | 2.13%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 2.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.42%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.42%   |
| Intel AX201 Bluetooth                               | 2         | 1.42%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 1.42%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.42%   |
| ASUS ASUS USB-BT500                                 | 2         | 1.42%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.42%   |
| TP-Link TP-T@- UB500 Adapter                        | 1         | 0.71%   |
| Realtek Bluetooth Radio                             | 1         | 0.71%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.71%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.71%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.71%   |
| Lite-On Bluetooth Device                            | 1         | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.71%   |
| Intel AX210 Bluetooth                               | 1         | 0.71%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.71%   |
| IMC Networks BCM20702A0                             | 1         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.71%   |
| Fujitsu Bluetooth Device                            | 1         | 0.71%   |
| Foxconn / Hon Hai BT                                | 1         | 0.71%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 208       | 54.45%  |
| AMD                                          | 71        | 18.59%  |
| Nvidia                                       | 54        | 14.14%  |
| Creative Labs                                | 7         | 1.83%   |
| C-Media Electronics                          | 6         | 1.57%   |
| Texas Instruments                            | 3         | 0.79%   |
| Plantronics                                  | 3         | 0.79%   |
| VIA Technologies                             | 2         | 0.52%   |
| Logitech                                     | 2         | 0.52%   |
| KTMicro                                      | 2         | 0.52%   |
| Generalplus Technology                       | 2         | 0.52%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.26%   |
| Walmart                                      | 1         | 0.26%   |
| TEAC                                         | 1         | 0.26%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.26%   |
| Samsung Electronics                          | 1         | 0.26%   |
| Realtek Semiconductor                        | 1         | 0.26%   |
| Nordic Semiconductor ASA                     | 1         | 0.26%   |
| Medeli Electronics                           | 1         | 0.26%   |
| M-Audio                                      | 1         | 0.26%   |
| KORG                                         | 1         | 0.26%   |
| JMTek                                        | 1         | 0.26%   |
| GYROCOM C&C                                  | 1         | 0.26%   |
| GN Netcom                                    | 1         | 0.26%   |
| Giga-Byte Technology                         | 1         | 0.26%   |
| Focusrite-Novation                           | 1         | 0.26%   |
| FIFINE Microphones                           | 1         | 0.26%   |
| Elite Silicon                                | 1         | 0.26%   |
| DSEA A/S                                     | 1         | 0.26%   |
| Cirrus Logic                                 | 1         | 0.26%   |
| Blue Microphones                             | 1         | 0.26%   |
| Avance Logic                                 | 1         | 0.26%   |
| ASUSTek Computer                             | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 20        | 4.36%   |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 3.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 3.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 14        | 3.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 2.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 2.18%   |
| Intel 200 Series PCH HD Audio                                              | 10        | 2.18%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 1.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 1.96%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 9         | 1.96%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 1.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.53%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 7         | 1.53%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 1.53%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.31%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.31%   |
| Nvidia High Definition Audio Controller                                    | 5         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.09%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 5         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 1.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 1.09%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 0.87%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 0.87%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller          | 4         | 0.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.87%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 0.87%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 58        | 20.71%  |
| Kingston                     | 43        | 15.36%  |
| SK hynix                     | 37        | 13.21%  |
| Unknown                      | 35        | 12.5%   |
| Corsair                      | 21        | 7.5%    |
| Micron Technology            | 20        | 7.14%   |
| Crucial                      | 13        | 4.64%   |
| G.Skill                      | 9         | 3.21%   |
| A-DATA Technology            | 8         | 2.86%   |
| Nanya Technology             | 5         | 1.79%   |
| Unknown                      | 5         | 1.79%   |
| Unknown (ABCD)               | 3         | 1.07%   |
| Ramaxel Technology           | 3         | 1.07%   |
| Transcend                    | 2         | 0.71%   |
| Unknown (F785)               | 1         | 0.36%   |
| Unknown (130B)               | 1         | 0.36%   |
| Unknown (0x0E9D)             | 1         | 0.36%   |
| Team                         | 1         | 0.36%   |
| Smart                        | 1         | 0.36%   |
| Silicon Power                | 1         | 0.36%   |
| PUSKILL                      | 1         | 0.36%   |
| Patriot Memory (PDP Systems) | 1         | 0.36%   |
| Patriot                      | 1         | 0.36%   |
| GOODRAM                      | 1         | 0.36%   |
| Goldkey                      | 1         | 0.36%   |
| Elpida                       | 1         | 0.36%   |
| Avant                        | 1         | 0.36%   |
| Apacer                       | 1         | 0.36%   |
| AMD                          | 1         | 0.36%   |
| A Force                      | 1         | 0.36%   |
| 4ea5                         | 1         | 0.36%   |
| 48spaces                     | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown                                                        | 5         | 1.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 1.3%    |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s           | 3         | 0.97%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 3         | 0.97%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 0.97%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 0.97%   |
| Kingston RAM 9965432-089.A00LF 4GB DIMM DDR3 1600MT/s          | 3         | 0.97%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s         | 3         | 0.97%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 3         | 0.97%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 2         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR                           | 2         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 2         | 0.65%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 2         | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s          | 2         | 0.65%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.65%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s          | 2         | 0.65%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s  | 2         | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s            | 2         | 0.65%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s          | 2         | 0.65%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s           | 2         | 0.65%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s      | 2         | 0.65%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s        | 2         | 0.65%   |
| Corsair RAM CMK32GX4M4A2666C16 8GB DIMM DDR4 3000MT/s          | 2         | 0.65%   |
| Unknown RAM SM3S320SD0488CABC 8192MB SODIMM DDR3 1600MT/s      | 1         | 0.32%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.32%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8192MB DIMM DDR3 800MT/s                    | 1         | 0.32%   |
| Unknown RAM Module 64MB DIMM DRAM 100MT/s                      | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 102       | 42.15%  |
| DDR3    | 86        | 35.54%  |
| SDRAM   | 11        | 4.55%   |
| DDR2    | 9         | 3.72%   |
| DDR     | 7         | 2.89%   |
| LPDDR3  | 6         | 2.48%   |
| DDR5    | 6         | 2.48%   |
| LPDDR5  | 5         | 2.07%   |
| LPDDR4  | 4         | 1.65%   |
| Unknown | 4         | 1.65%   |
| DRAM    | 2         | 0.83%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 136       | 57.63%  |
| DIMM         | 89        | 37.71%  |
| Row Of Chips | 9         | 3.81%   |
| Chip         | 1         | 0.42%   |
| Unknown      | 1         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 92        | 34.2%   |
| 4096  | 65        | 24.16%  |
| 16384 | 47        | 17.47%  |
| 2048  | 32        | 11.9%   |
| 1024  | 13        | 4.83%   |
| 32768 | 12        | 4.46%   |
| 512   | 3         | 1.12%   |
| 65536 | 1         | 0.37%   |
| 12288 | 1         | 0.37%   |
| 256   | 1         | 0.37%   |
| 128   | 1         | 0.37%   |
| 64    | 1         | 0.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 60        | 22.9%   |
| 3200    | 30        | 11.45%  |
| 2667    | 30        | 11.45%  |
| 2400    | 17        | 6.49%   |
| 2133    | 12        | 4.58%   |
| 3600    | 11        | 4.2%    |
| 1333    | 11        | 4.2%    |
| Unknown | 11        | 4.2%    |
| 667     | 8         | 3.05%   |
| 800     | 6         | 2.29%   |
| 1067    | 5         | 1.91%   |
| 6400    | 4         | 1.53%   |
| 4800    | 4         | 1.53%   |
| 4199    | 4         | 1.53%   |
| 3800    | 4         | 1.53%   |
| 1334    | 4         | 1.53%   |
| 3266    | 3         | 1.15%   |
| 3000    | 3         | 1.15%   |
| 2933    | 3         | 1.15%   |
| 1867    | 3         | 1.15%   |
| 1800    | 3         | 1.15%   |
| 1066    | 3         | 1.15%   |
| 8400    | 2         | 0.76%   |
| 5600    | 2         | 0.76%   |
| 2666    | 2         | 0.76%   |
| 1866    | 2         | 0.76%   |
| 533     | 2         | 0.76%   |
| 400     | 2         | 0.76%   |
| 6800    | 1         | 0.38%   |
| 4000    | 1         | 0.38%   |
| 3466    | 1         | 0.38%   |
| 3400    | 1         | 0.38%   |
| 3333    | 1         | 0.38%   |
| 3066    | 1         | 0.38%   |
| 2448    | 1         | 0.38%   |
| 1632    | 1         | 0.38%   |
| 1200    | 1         | 0.38%   |
| 975     | 1         | 0.38%   |
| 100     | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 4         | 33.33%  |
| QinHeng Electronics    | 2         | 16.67%  |
| Brother Industries     | 2         | 16.67%  |
| Samsung Electronics    | 1         | 8.33%   |
| Prolific Technology    | 1         | 8.33%   |
| Custom Engineering SPA | 1         | 8.33%   |
| Canon                  | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                           | Computers | Percent |
|---------------------------------|-----------|---------|
| QinHeng CH340S                  | 2         | 16.67%  |
| Samsung SCX-4600 Series         | 1         | 8.33%   |
| Prolific PL2305 Parallel Port   | 1         | 8.33%   |
| HP ENVY 5000 series             | 1         | 8.33%   |
| HP DeskJet F4200 series         | 1         | 8.33%   |
| HP Deskjet 1510                 | 1         | 8.33%   |
| HP Deskjet 1050 J410            | 1         | 8.33%   |
| Custom Engineering SPA KUBE USB | 1         | 8.33%   |
| Canon G1010 series              | 1         | 8.33%   |
| Brother MFC-J460DW              | 1         | 8.33%   |
| Brother HL-L2375DW series       | 1         | 8.33%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 27.86%  |
| Bison Electronics                      | 13        | 9.29%   |
| Microdia                               | 10        | 7.14%   |
| Logitech                               | 9         | 6.43%   |
| Realtek Semiconductor                  | 7         | 5%      |
| Sunplus Innovation Technology          | 6         | 4.29%   |
| Quanta                                 | 6         | 4.29%   |
| IMC Networks                           | 6         | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.57%   |
| Suyin                                  | 4         | 2.86%   |
| Luxvisions Innotech Limited            | 4         | 2.86%   |
| Silicon Motion                         | 3         | 2.14%   |
| Lite-On Technology                     | 3         | 2.14%   |
| Acer                                   | 3         | 2.14%   |
| Z-Star Microelectronics                | 2         | 1.43%   |
| Syntek                                 | 2         | 1.43%   |
| KYE Systems (Mouse Systems)            | 2         | 1.43%   |
| Cubeternet                             | 2         | 1.43%   |
| Softkinetic                            | 1         | 0.71%   |
| ShineTech                              | 1         | 0.71%   |
| Samsung Electronics                    | 1         | 0.71%   |
| OmniVision Technologies                | 1         | 0.71%   |
| Mustek Systems                         | 1         | 0.71%   |
| Microsoft                              | 1         | 0.71%   |
| MacroSilicon                           | 1         | 0.71%   |
| LG Electronics                         | 1         | 0.71%   |
| Lenovo                                 | 1         | 0.71%   |
| kingcome                               | 1         | 0.71%   |
| Hauppauge                              | 1         | 0.71%   |
| Genesys Logic                          | 1         | 0.71%   |
| GEMBIRD                                | 1         | 0.71%   |
| Apple                                  | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 12        | 8.57%   |
| Chicony HD Webcam                                           | 4         | 2.86%   |
| Logitech Webcam C270                                        | 3         | 2.14%   |
| IMC Networks Integrated Camera                              | 3         | 2.14%   |
| Bison Integrated RGB Camera                                 | 3         | 2.14%   |
| Bison BisonCam,NB Pro                                       | 3         | 2.14%   |
| Syntek Integrated Camera                                    | 2         | 1.43%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.43%   |
| Microdia Integrated Webcam                                  | 2         | 1.43%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 1.43%   |
| Logitech HD Pro Webcam C920                                 | 2         | 1.43%   |
| Cubeternet GL-UPC822 UVC WebCam                             | 2         | 1.43%   |
| Chicony HP TrueVision HD Camera                             | 2         | 1.43%   |
| Chicony EasyCamera                                          | 2         | 1.43%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.43%   |
| Z-Star Webcam                                               | 1         | 0.71%   |
| Z-Star A4 TECH USB2.0 PC Camera E                           | 1         | 0.71%   |
| Suyin Lenovo EasyCamera Integrated Webcam                   | 1         | 0.71%   |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.71%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.71%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.71%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.71%   |
| Sunplus Integrated Camera                                   | 1         | 0.71%   |
| Sunplus Dell Integrated Webcam                              | 1         | 0.71%   |
| Sunplus Asus Webcam                                         | 1         | 0.71%   |
| Sunplus 720p HD Camera                                      | 1         | 0.71%   |
| Softkinetic DepthSense 325                                  | 1         | 0.71%   |
| Silicon Motion WebCam SC-10IRR13340N                        | 1         | 0.71%   |
| Silicon Motion Lenovo EasyCamera                            | 1         | 0.71%   |
| Silicon Motion HP Webcam-101                                | 1         | 0.71%   |
| ShineTech USB2.0 HD UVC WebCam                              | 1         | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.71%   |
| Realtek USB Camera                                          | 1         | 0.71%   |
| Realtek Lenovo EasyCamera                                   | 1         | 0.71%   |
| Realtek Laptop Camera                                       | 1         | 0.71%   |
| Realtek Integrated Webcam_HD                                | 1         | 0.71%   |
| Realtek HD 720P Webcam                                      | 1         | 0.71%   |
| Quanta USB webcam                                           | 1         | 0.71%   |
| Quanta Sony Visual Communication Camera                     | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 47.06%  |
| Validity Sensors           | 3         | 17.65%  |
| STMicroelectronics         | 2         | 11.76%  |
| Shenzhen Goodix Technology | 2         | 11.76%  |
| Upek                       | 1         | 5.88%   |
| AuthenTec                  | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 3         | 17.65%  |
| Validity Sensors Synaptics WBDI                        | 2         | 11.76%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 11.76%  |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 11.76%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.88%   |
| Synaptics WBDI Device                                  | 1         | 5.88%   |
| Synaptics UWP WBDI                                     | 1         | 5.88%   |
| Synaptics TouchPad                                     | 1         | 5.88%   |
| Synaptics Fingerprint scanner                          | 1         | 5.88%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 5.88%   |
| AuthenTec AES2810                                      | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 47.83%  |
| Alcor Micro | 8         | 34.78%  |
| Upek        | 3         | 13.04%  |
| Lenovo      | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 34.78%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 17.39%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 17.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 13.04%  |
| Broadcom 5880                                                                | 2         | 8.7%    |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.35%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 205       | 69.73%  |
| 1     | 63        | 21.43%  |
| 2     | 20        | 6.8%    |
| 3     | 4         | 1.36%   |
| 5     | 1         | 0.34%   |
| 4     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 29        | 26.85%  |
| Chipcard                 | 18        | 16.67%  |
| Fingerprint reader       | 17        | 15.74%  |
| Net/wireless             | 10        | 9.26%   |
| Communication controller | 8         | 7.41%   |
| Unassigned class         | 6         | 5.56%   |
| Multimedia controller    | 5         | 4.63%   |
| Camera                   | 5         | 4.63%   |
| Bluetooth                | 3         | 2.78%   |
| Net/ethernet             | 2         | 1.85%   |
| Storage/raid             | 1         | 0.93%   |
| Storage                  | 1         | 0.93%   |
| Sound                    | 1         | 0.93%   |
| Firewire controller      | 1         | 0.93%   |
| Card reader              | 1         | 0.93%   |


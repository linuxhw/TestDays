Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 18024

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | Notebook    | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [3f218796ae](https://linux-hardware.org/?probe=3f218796ae) | Apr 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2175527bda](https://linux-hardware.org/?probe=2175527bda) | Apr 01, 2023 |
| Itautec       | Infoway w7535               | Notebook    | [48a539f108](https://linux-hardware.org/?probe=48a539f108) | Apr 01, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [ee536703f8](https://linux-hardware.org/?probe=ee536703f8) | Apr 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [816e9cb6f6](https://linux-hardware.org/?probe=816e9cb6f6) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [93ef0bb287](https://linux-hardware.org/?probe=93ef0bb287) | Apr 01, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [67b91e463a](https://linux-hardware.org/?probe=67b91e463a) | Mar 31, 2023 |
| Acer          | Aspire A315-54K             | Notebook    | [d325177071](https://linux-hardware.org/?probe=d325177071) | Mar 31, 2023 |
| Positivo      | S14CT01                     | Notebook    | [a47919fcc4](https://linux-hardware.org/?probe=a47919fcc4) | Mar 31, 2023 |
| Quanta        | QL3 TBD                     | Notebook    | [21673aecac](https://linux-hardware.org/?probe=21673aecac) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | A58M-A/BR                   | Desktop     | [90724dc86e](https://linux-hardware.org/?probe=90724dc86e) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| Dell          | Vostro V131                 | Notebook    | [53538c2ae9](https://linux-hardware.org/?probe=53538c2ae9) | Mar 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7597a96654](https://linux-hardware.org/?probe=7597a96654) | Mar 31, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [fe5578a96e](https://linux-hardware.org/?probe=fe5578a96e) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [1fa3e0934f](https://linux-hardware.org/?probe=1fa3e0934f) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [ebd6135034](https://linux-hardware.org/?probe=ebd6135034) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [88864f0e2d](https://linux-hardware.org/?probe=88864f0e2d) | Mar 31, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [e110fbb7d6](https://linux-hardware.org/?probe=e110fbb7d6) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3aac57dfbd](https://linux-hardware.org/?probe=3aac57dfbd) | Mar 30, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Positivo      | S14SL01                     | Notebook    | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| Acer          | Prespa M                    | Notebook    | [a6541a27d9](https://linux-hardware.org/?probe=a6541a27d9) | Mar 30, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [27b9c84cbe](https://linux-hardware.org/?probe=27b9c84cbe) | Mar 30, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [5418efd855](https://linux-hardware.org/?probe=5418efd855) | Mar 30, 2023 |
| Lenovo        | Yoga 510-14ISK 80UK         | Notebook    | [722c1e9d68](https://linux-hardware.org/?probe=722c1e9d68) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| Dell          | Latitude 3490               | Notebook    | [16d4f0954b](https://linux-hardware.org/?probe=16d4f0954b) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [83cb13ffb4](https://linux-hardware.org/?probe=83cb13ffb4) | Mar 30, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [1b8dc51444](https://linux-hardware.org/?probe=1b8dc51444) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [1fe20bdfcb](https://linux-hardware.org/?probe=1fe20bdfcb) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [7b53b4da78](https://linux-hardware.org/?probe=7b53b4da78) | Mar 29, 2023 |
| Positivo      | Q232A                       | Notebook    | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6023df2b8b](https://linux-hardware.org/?probe=6023df2b8b) | Mar 29, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [a46eb24b2a](https://linux-hardware.org/?probe=a46eb24b2a) | Mar 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| ASUSTek       | X751LJ                      | Notebook    | [cf5d71e2b3](https://linux-hardware.org/?probe=cf5d71e2b3) | Mar 29, 2023 |
| Samsung       | 370E4K                      | Notebook    | [68e9294ac9](https://linux-hardware.org/?probe=68e9294ac9) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [2bf528dfb1](https://linux-hardware.org/?probe=2bf528dfb1) | Mar 29, 2023 |
| Daten Tecn... | DQ77PRO                     | Desktop     | [86885bfc03](https://linux-hardware.org/?probe=86885bfc03) | Mar 29, 2023 |
| Intel         | B75                         | Desktop     | [2bddb84c2e](https://linux-hardware.org/?probe=2bddb84c2e) | Mar 29, 2023 |
| HOUTER        | IPMH61R1                    | Desktop     | [bcabc2573c](https://linux-hardware.org/?probe=bcabc2573c) | Mar 29, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [9d48f53259](https://linux-hardware.org/?probe=9d48f53259) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | Notebook    | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [8258074853](https://linux-hardware.org/?probe=8258074853) | Mar 28, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [7f2e65257c](https://linux-hardware.org/?probe=7f2e65257c) | Mar 28, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [9ee954843e](https://linux-hardware.org/?probe=9ee954843e) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [7ec74ffcfa](https://linux-hardware.org/?probe=7ec74ffcfa) | Mar 28, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [b1ef6303a6](https://linux-hardware.org/?probe=b1ef6303a6) | Mar 28, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [7e5cb33850](https://linux-hardware.org/?probe=7e5cb33850) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Dell          | G3 3579                     | Notebook    | [55b5db4326](https://linux-hardware.org/?probe=55b5db4326) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [9c9e155f84](https://linux-hardware.org/?probe=9c9e155f84) | Mar 28, 2023 |
| Intel         | H61                         | Desktop     | [56437a0e05](https://linux-hardware.org/?probe=56437a0e05) | Mar 28, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6b4122e888](https://linux-hardware.org/?probe=6b4122e888) | Mar 28, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [727f980b20](https://linux-hardware.org/?probe=727f980b20) | Mar 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| Dell          | Inspiron 5448               | Notebook    | [b800b24cbd](https://linux-hardware.org/?probe=b800b24cbd) | Mar 27, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [46fbf61289](https://linux-hardware.org/?probe=46fbf61289) | Mar 27, 2023 |
| Dell          | G15 5515                    | Notebook    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | Desktop     | [ec1f547743](https://linux-hardware.org/?probe=ec1f547743) | Mar 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [f312d049e0](https://linux-hardware.org/?probe=f312d049e0) | Mar 27, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [33bccb2234](https://linux-hardware.org/?probe=33bccb2234) | Mar 27, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [2fbd1f3f64](https://linux-hardware.org/?probe=2fbd1f3f64) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Positivo      | Smash2                      | Notebook    | [b61791c478](https://linux-hardware.org/?probe=b61791c478) | Mar 26, 2023 |
| MSI           | CR620                       | Notebook    | [2fce81cc28](https://linux-hardware.org/?probe=2fce81cc28) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5c3f0186de](https://linux-hardware.org/?probe=5c3f0186de) | Mar 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f0d9554e41](https://linux-hardware.org/?probe=f0d9554e41) | Mar 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [db70257507](https://linux-hardware.org/?probe=db70257507) | Mar 26, 2023 |
| Sony          | SVF14215CXB                 | Notebook    | [624af23eb4](https://linux-hardware.org/?probe=624af23eb4) | Mar 26, 2023 |
| BESSTAR Te... | F6BFC                       | Desktop     | [881c531ee5](https://linux-hardware.org/?probe=881c531ee5) | Mar 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [2163c72a12](https://linux-hardware.org/?probe=2163c72a12) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [a999580cf7](https://linux-hardware.org/?probe=a999580cf7) | Mar 25, 2023 |
| Samsung       | 550XDA                      | Notebook    | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| AZW           | MINI S                      | Desktop     | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2df4a612b4](https://linux-hardware.org/?probe=2df4a612b4) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| Acer          | Aspire 4740                 | Notebook    | [c4e47e53dc](https://linux-hardware.org/?probe=c4e47e53dc) | Mar 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [27ff485a92](https://linux-hardware.org/?probe=27ff485a92) | Mar 25, 2023 |
| Acer          | Aspire ES1-411              | Notebook    | [1a4caa9a83](https://linux-hardware.org/?probe=1a4caa9a83) | Mar 24, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [f2a2593a06](https://linux-hardware.org/?probe=f2a2593a06) | Mar 24, 2023 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [0bcd7ee5e8](https://linux-hardware.org/?probe=0bcd7ee5e8) | Mar 24, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [51a085fb56](https://linux-hardware.org/?probe=51a085fb56) | Mar 24, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [391a73b307](https://linux-hardware.org/?probe=391a73b307) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [cce19de050](https://linux-hardware.org/?probe=cce19de050) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [56942672e1](https://linux-hardware.org/?probe=56942672e1) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a9ffd21a7f](https://linux-hardware.org/?probe=a9ffd21a7f) | Mar 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [4e2b8b9de9](https://linux-hardware.org/?probe=4e2b8b9de9) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| PCWare        | IPMH310G                    | Desktop     | [3cc2e91e56](https://linux-hardware.org/?probe=3cc2e91e56) | Mar 24, 2023 |
| Itautec       | ST 4265                     | Desktop     | [4671d7c30e](https://linux-hardware.org/?probe=4671d7c30e) | Mar 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9e55d83acd](https://linux-hardware.org/?probe=9e55d83acd) | Mar 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [50931f533e](https://linux-hardware.org/?probe=50931f533e) | Mar 23, 2023 |
| Samsung       | 530XBB                      | Notebook    | [2bb5946ee7](https://linux-hardware.org/?probe=2bb5946ee7) | Mar 23, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2536217d87](https://linux-hardware.org/?probe=2536217d87) | Mar 23, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [cd3e7fa4e5](https://linux-hardware.org/?probe=cd3e7fa4e5) | Mar 23, 2023 |
| Intel         | DH87RL AAG74240-401         | Desktop     | [3465e562e8](https://linux-hardware.org/?probe=3465e562e8) | Mar 23, 2023 |
| Avell High... | B.ON                        | Notebook    | [0fe36e1e74](https://linux-hardware.org/?probe=0fe36e1e74) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [7d303a08d4](https://linux-hardware.org/?probe=7d303a08d4) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| Lenovo        | ThinkPad L450 20DSA25V01    | Notebook    | [68b1ae2c5d](https://linux-hardware.org/?probe=68b1ae2c5d) | Mar 23, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [204b7c3324](https://linux-hardware.org/?probe=204b7c3324) | Mar 23, 2023 |
| Lenovo        | 500w Gen 3 82J3             | Convertible | [26ca87e272](https://linux-hardware.org/?probe=26ca87e272) | Mar 23, 2023 |
| Digiboard     | NM70-TI                     | Desktop     | [d654b9738a](https://linux-hardware.org/?probe=d654b9738a) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [64c4a47e0e](https://linux-hardware.org/?probe=64c4a47e0e) | Mar 23, 2023 |
| Multilaser    | UB820                       | All in one  | [9d056bd8e0](https://linux-hardware.org/?probe=9d056bd8e0) | Mar 23, 2023 |
| HPE           | ProLiant MicroServer Gen... | Server      | [01d2615c22](https://linux-hardware.org/?probe=01d2615c22) | Mar 23, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [299072c37e](https://linux-hardware.org/?probe=299072c37e) | Mar 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [fca39bd9eb](https://linux-hardware.org/?probe=fca39bd9eb) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [47b661fcb3](https://linux-hardware.org/?probe=47b661fcb3) | Mar 22, 2023 |
| Samsung       | 550XDA                      | Notebook    | [b145c438d7](https://linux-hardware.org/?probe=b145c438d7) | Mar 22, 2023 |
| Gigabyte      | H110M-S2H DDR3-CF           | Desktop     | [f848ecf9cf](https://linux-hardware.org/?probe=f848ecf9cf) | Mar 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [568fac441d](https://linux-hardware.org/?probe=568fac441d) | Mar 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [e07e3320b1](https://linux-hardware.org/?probe=e07e3320b1) | Mar 22, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [ebe6cc115e](https://linux-hardware.org/?probe=ebe6cc115e) | Mar 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [20adc36857](https://linux-hardware.org/?probe=20adc36857) | Mar 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2e6307252f](https://linux-hardware.org/?probe=2e6307252f) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | Notebook    | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [982f47fec3](https://linux-hardware.org/?probe=982f47fec3) | Mar 22, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [1e299101d8](https://linux-hardware.org/?probe=1e299101d8) | Mar 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1165b3734c](https://linux-hardware.org/?probe=1165b3734c) | Mar 21, 2023 |
| Avell High... | A62 LIV                     | Notebook    | [14dab05208](https://linux-hardware.org/?probe=14dab05208) | Mar 21, 2023 |
| Toshiba       | Satellite A305              | Notebook    | [ed7bc92488](https://linux-hardware.org/?probe=ed7bc92488) | Mar 21, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [ee892df403](https://linux-hardware.org/?probe=ee892df403) | Mar 21, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b6b5eb415f](https://linux-hardware.org/?probe=b6b5eb415f) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [330f307e06](https://linux-hardware.org/?probe=330f307e06) | Mar 21, 2023 |
| CCE           | NM70-I                      | Desktop     | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [217e9242da](https://linux-hardware.org/?probe=217e9242da) | Mar 20, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [b011027d1a](https://linux-hardware.org/?probe=b011027d1a) | Mar 20, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [2060b57720](https://linux-hardware.org/?probe=2060b57720) | Mar 20, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [b15061e252](https://linux-hardware.org/?probe=b15061e252) | Mar 20, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4483bfa54d](https://linux-hardware.org/?probe=4483bfa54d) | Mar 20, 2023 |
| Win elemen... | M600                        | Desktop     | [eb40c2a7fc](https://linux-hardware.org/?probe=eb40c2a7fc) | Mar 20, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [ef87ac1a64](https://linux-hardware.org/?probe=ef87ac1a64) | Mar 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [32d80303b6](https://linux-hardware.org/?probe=32d80303b6) | Mar 20, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddb34b9c1f](https://linux-hardware.org/?probe=ddb34b9c1f) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Avell High... | B.ON                        | Notebook    | [b215c2fd75](https://linux-hardware.org/?probe=b215c2fd75) | Mar 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1292539ef0](https://linux-hardware.org/?probe=1292539ef0) | Mar 19, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [22bd6400f6](https://linux-hardware.org/?probe=22bd6400f6) | Mar 19, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [f587cfd0f1](https://linux-hardware.org/?probe=f587cfd0f1) | Mar 19, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [964d71f3f2](https://linux-hardware.org/?probe=964d71f3f2) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cd8f53a887](https://linux-hardware.org/?probe=cd8f53a887) | Mar 19, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [6e6c326058](https://linux-hardware.org/?probe=6e6c326058) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [99e92fa4df](https://linux-hardware.org/?probe=99e92fa4df) | Mar 18, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [fb9df7f581](https://linux-hardware.org/?probe=fb9df7f581) | Mar 18, 2023 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [1a93d601d7](https://linux-hardware.org/?probe=1a93d601d7) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [176b7d75bf](https://linux-hardware.org/?probe=176b7d75bf) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [49b005770d](https://linux-hardware.org/?probe=49b005770d) | Mar 18, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [00b550c606](https://linux-hardware.org/?probe=00b550c606) | Mar 18, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [6af556d727](https://linux-hardware.org/?probe=6af556d727) | Mar 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [8c8a87616c](https://linux-hardware.org/?probe=8c8a87616c) | Mar 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [45a412e241](https://linux-hardware.org/?probe=45a412e241) | Mar 18, 2023 |
| Positivo      | C14CU51                     | Notebook    | [02fe8f2e3b](https://linux-hardware.org/?probe=02fe8f2e3b) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [252cd1ff88](https://linux-hardware.org/?probe=252cd1ff88) | Mar 18, 2023 |
| Intel         | H61                         | Desktop     | [10b44e8f3e](https://linux-hardware.org/?probe=10b44e8f3e) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| ASUSTek       | K84C                        | Notebook    | [1c6b73b907](https://linux-hardware.org/?probe=1c6b73b907) | Mar 18, 2023 |
| Samsung       | 550XDA                      | Notebook    | [210e5d9e14](https://linux-hardware.org/?probe=210e5d9e14) | Mar 17, 2023 |
| Acer          | Aspire V7-482PG             | Notebook    | [9ba6bdc643](https://linux-hardware.org/?probe=9ba6bdc643) | Mar 17, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [16b1b61892](https://linux-hardware.org/?probe=16b1b61892) | Mar 17, 2023 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [19a69ab150](https://linux-hardware.org/?probe=19a69ab150) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [fc0e66fc8a](https://linux-hardware.org/?probe=fc0e66fc8a) | Mar 17, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [452349c032](https://linux-hardware.org/?probe=452349c032) | Mar 17, 2023 |
| HP            | 871A                        | Mini pc     | [b4b1c552ad](https://linux-hardware.org/?probe=b4b1c552ad) | Mar 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [35505ab2bf](https://linux-hardware.org/?probe=35505ab2bf) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [353d82cd61](https://linux-hardware.org/?probe=353d82cd61) | Mar 17, 2023 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [bf5b0c4406](https://linux-hardware.org/?probe=bf5b0c4406) | Mar 17, 2023 |
| Positivo      | N1250                       | Notebook    | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [dd12b2101e](https://linux-hardware.org/?probe=dd12b2101e) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [2215bc867b](https://linux-hardware.org/?probe=2215bc867b) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| Intel         | X99                         | Desktop     | [e7d23adc36](https://linux-hardware.org/?probe=e7d23adc36) | Mar 17, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [1cedff3f90](https://linux-hardware.org/?probe=1cedff3f90) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [0d1834afd1](https://linux-hardware.org/?probe=0d1834afd1) | Mar 16, 2023 |
| HP            | 8266                        | Desktop     | [90ee08c208](https://linux-hardware.org/?probe=90ee08c208) | Mar 16, 2023 |
| Avell High... | STORM TWO                   | Notebook    | [e6b20084b5](https://linux-hardware.org/?probe=e6b20084b5) | Mar 16, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [63676e7012](https://linux-hardware.org/?probe=63676e7012) | Mar 16, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [1e1b3b6542](https://linux-hardware.org/?probe=1e1b3b6542) | Mar 16, 2023 |
| LG Electro... | 15Z980-G.BH72P1             | Notebook    | [0bba01d850](https://linux-hardware.org/?probe=0bba01d850) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [f4374c5a2b](https://linux-hardware.org/?probe=f4374c5a2b) | Mar 15, 2023 |
| HP            | 8299                        | Desktop     | [d76d2b1088](https://linux-hardware.org/?probe=d76d2b1088) | Mar 15, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [3028035868](https://linux-hardware.org/?probe=3028035868) | Mar 15, 2023 |
| PCWare        | IPX4105G Pro                | Desktop     | [f685771047](https://linux-hardware.org/?probe=f685771047) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [1451ae2f05](https://linux-hardware.org/?probe=1451ae2f05) | Mar 15, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [6e1d22df26](https://linux-hardware.org/?probe=6e1d22df26) | Mar 15, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [26971576bb](https://linux-hardware.org/?probe=26971576bb) | Mar 14, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [7649d9be35](https://linux-hardware.org/?probe=7649d9be35) | Mar 14, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [800c597040](https://linux-hardware.org/?probe=800c597040) | Mar 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| Motorola      | Moto G4 Play (harpia)       | Soc         | [2d1a7ffdd5](https://linux-hardware.org/?probe=2d1a7ffdd5) | Mar 14, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [bb1dca9ea3](https://linux-hardware.org/?probe=bb1dca9ea3) | Mar 14, 2023 |
| Positivo      | Q464B                       | Notebook    | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [bbb4128793](https://linux-hardware.org/?probe=bbb4128793) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| ASUSTek       | PRIME B350M-K               | Desktop     | [ae6352dc35](https://linux-hardware.org/?probe=ae6352dc35) | Mar 13, 2023 |
| Biostar       | A320MH                      | Desktop     | [6fbd813bc2](https://linux-hardware.org/?probe=6fbd813bc2) | Mar 13, 2023 |
| Google        | Celes                       | Notebook    | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [7ffbc62c94](https://linux-hardware.org/?probe=7ffbc62c94) | Mar 13, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [4c6424525e](https://linux-hardware.org/?probe=4c6424525e) | Mar 13, 2023 |
| Dell          | Inspiron 13 5320            | Notebook    | [efbe50cd5c](https://linux-hardware.org/?probe=efbe50cd5c) | Mar 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [c6b7f1ec98](https://linux-hardware.org/?probe=c6b7f1ec98) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0a83a62b1c](https://linux-hardware.org/?probe=0a83a62b1c) | Mar 13, 2023 |
| HP            | Pavilion dm1                | Notebook    | [9ed7d80abb](https://linux-hardware.org/?probe=9ed7d80abb) | Mar 13, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [8567b21f41](https://linux-hardware.org/?probe=8567b21f41) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [89e2967e3c](https://linux-hardware.org/?probe=89e2967e3c) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [1ece615e2d](https://linux-hardware.org/?probe=1ece615e2d) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | Notebook    | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Samsung       | 730QED                      | Convertible | [2479585a5b](https://linux-hardware.org/?probe=2479585a5b) | Mar 12, 2023 |
| Dell          | Vostro 14-5480              | Notebook    | [3ea64e75d4](https://linux-hardware.org/?probe=3ea64e75d4) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [bd0af3660b](https://linux-hardware.org/?probe=bd0af3660b) | Mar 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2e839dd9f0](https://linux-hardware.org/?probe=2e839dd9f0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | Desktop     | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [75e9243247](https://linux-hardware.org/?probe=75e9243247) | Mar 12, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c42ead0ecf](https://linux-hardware.org/?probe=c42ead0ecf) | Mar 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [d2b4cffe84](https://linux-hardware.org/?probe=d2b4cffe84) | Mar 11, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [3e9c39ec40](https://linux-hardware.org/?probe=3e9c39ec40) | Mar 11, 2023 |
| Positivo      | Q464B                       | Notebook    | [513b08857c](https://linux-hardware.org/?probe=513b08857c) | Mar 11, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [757a62eff0](https://linux-hardware.org/?probe=757a62eff0) | Mar 11, 2023 |
| Dell          | System XPS L502X            | Notebook    | [b3f35673e6](https://linux-hardware.org/?probe=b3f35673e6) | Mar 11, 2023 |
| Intel         | H61                         | Desktop     | [0a38ec61cc](https://linux-hardware.org/?probe=0a38ec61cc) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [d5426d5f1e](https://linux-hardware.org/?probe=d5426d5f1e) | Mar 11, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ac565d5d7d](https://linux-hardware.org/?probe=ac565d5d7d) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [729d9395f0](https://linux-hardware.org/?probe=729d9395f0) | Mar 11, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [fd3c999c22](https://linux-hardware.org/?probe=fd3c999c22) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [92e7dacbc6](https://linux-hardware.org/?probe=92e7dacbc6) | Mar 11, 2023 |
| Positivo      | C14CU51                     | Notebook    | [0cc5053d97](https://linux-hardware.org/?probe=0cc5053d97) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [15dd4409fc](https://linux-hardware.org/?probe=15dd4409fc) | Mar 11, 2023 |
| Intel         | X99H                        | Desktop     | [a89ad204c8](https://linux-hardware.org/?probe=a89ad204c8) | Mar 11, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [9e6843fe2e](https://linux-hardware.org/?probe=9e6843fe2e) | Mar 10, 2023 |
| Dell          | Latitude E6420              | Notebook    | [514c8548aa](https://linux-hardware.org/?probe=514c8548aa) | Mar 10, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [0842fc186b](https://linux-hardware.org/?probe=0842fc186b) | Mar 10, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [0d8d93d401](https://linux-hardware.org/?probe=0d8d93d401) | Mar 10, 2023 |
| Lenovo        | NOK                         | Desktop     | [2e90ce2e87](https://linux-hardware.org/?probe=2e90ce2e87) | Mar 10, 2023 |
| Dell          | 0G2DM9 A02                  | Desktop     | [e6d8fa1563](https://linux-hardware.org/?probe=e6d8fa1563) | Mar 10, 2023 |
| Dell          | Inspiron 5420               | Notebook    | [77d13c9c12](https://linux-hardware.org/?probe=77d13c9c12) | Mar 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5a1af5afcf](https://linux-hardware.org/?probe=5a1af5afcf) | Mar 10, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [b8dffd9bd3](https://linux-hardware.org/?probe=b8dffd9bd3) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [d524e6c586](https://linux-hardware.org/?probe=d524e6c586) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6ae7081970](https://linux-hardware.org/?probe=6ae7081970) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [2d75f5ea8b](https://linux-hardware.org/?probe=2d75f5ea8b) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | Desktop     | [8b2c5b902c](https://linux-hardware.org/?probe=8b2c5b902c) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Colorful T... | BATTLE-AX B660M-HD DELUX... | Desktop     | [3a0c1c2237](https://linux-hardware.org/?probe=3a0c1c2237) | Mar 10, 2023 |
| Xunlong       | Orange Pi PC Plus           | Soc         | [ad41e0e370](https://linux-hardware.org/?probe=ad41e0e370) | Mar 09, 2023 |
| HP            | 1905                        | Desktop     | [dc86818199](https://linux-hardware.org/?probe=dc86818199) | Mar 09, 2023 |
| Dell          | 0TW904                      | Desktop     | [19f37f2901](https://linux-hardware.org/?probe=19f37f2901) | Mar 09, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [12d1ccac8d](https://linux-hardware.org/?probe=12d1ccac8d) | Mar 09, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [a5677d37dc](https://linux-hardware.org/?probe=a5677d37dc) | Mar 09, 2023 |
| Multilaser    | PC130                       | Notebook    | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e7429f9be3](https://linux-hardware.org/?probe=e7429f9be3) | Mar 09, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [a05bd1ffa7](https://linux-hardware.org/?probe=a05bd1ffa7) | Mar 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [97698bd9a9](https://linux-hardware.org/?probe=97698bd9a9) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7c99e05792](https://linux-hardware.org/?probe=7c99e05792) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [daf758d941](https://linux-hardware.org/?probe=daf758d941) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [8a643c9a04](https://linux-hardware.org/?probe=8a643c9a04) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| Dell          | 0TW904                      | Desktop     | [20e3b7cc23](https://linux-hardware.org/?probe=20e3b7cc23) | Mar 08, 2023 |
| Intel         | B75 V124                    | Desktop     | [777cb32ba1](https://linux-hardware.org/?probe=777cb32ba1) | Mar 08, 2023 |
| Samsung       | 550XDA                      | Notebook    | [65093a6cf5](https://linux-hardware.org/?probe=65093a6cf5) | Mar 08, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [8900b65d0b](https://linux-hardware.org/?probe=8900b65d0b) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d7ac4c2edb](https://linux-hardware.org/?probe=d7ac4c2edb) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [d6618b65cf](https://linux-hardware.org/?probe=d6618b65cf) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [1ef5bb11d6](https://linux-hardware.org/?probe=1ef5bb11d6) | Mar 08, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [30d171ddbc](https://linux-hardware.org/?probe=30d171ddbc) | Mar 08, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [0bad20c48c](https://linux-hardware.org/?probe=0bad20c48c) | Mar 08, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [1edca5142c](https://linux-hardware.org/?probe=1edca5142c) | Mar 07, 2023 |
| Lenovo        | ThinkPad T460 20FMS49100    | Notebook    | [285589b568](https://linux-hardware.org/?probe=285589b568) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | ThinkPad T430 234424P       | Notebook    | [f9d41f9054](https://linux-hardware.org/?probe=f9d41f9054) | Mar 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ca3d88758](https://linux-hardware.org/?probe=4ca3d88758) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [242bd44f0c](https://linux-hardware.org/?probe=242bd44f0c) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cb7ac03a2a](https://linux-hardware.org/?probe=cb7ac03a2a) | Mar 07, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [cb9468fb01](https://linux-hardware.org/?probe=cb9468fb01) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| LG Electro... | A530-U.BE54P1               | Notebook    | [c0260c82db](https://linux-hardware.org/?probe=c0260c82db) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [955e69578c](https://linux-hardware.org/?probe=955e69578c) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [22273fa42e](https://linux-hardware.org/?probe=22273fa42e) | Mar 06, 2023 |
| Lenovo        | ThinkCentre M91P 4518NR1    | Desktop     | [dfea3b8d9f](https://linux-hardware.org/?probe=dfea3b8d9f) | Mar 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [349f7731c8](https://linux-hardware.org/?probe=349f7731c8) | Mar 06, 2023 |
| Samsung       | 550XDA                      | Notebook    | [f73f29bd0b](https://linux-hardware.org/?probe=f73f29bd0b) | Mar 06, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [ff8a1d6dc3](https://linux-hardware.org/?probe=ff8a1d6dc3) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7fb36218d9](https://linux-hardware.org/?probe=7fb36218d9) | Mar 06, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e67eb9d235](https://linux-hardware.org/?probe=e67eb9d235) | Mar 06, 2023 |
| Dell          | G15 5520                    | Notebook    | [0322e7d38c](https://linux-hardware.org/?probe=0322e7d38c) | Mar 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [4a0130d910](https://linux-hardware.org/?probe=4a0130d910) | Mar 06, 2023 |
| Samsung       | 730QED                      | Convertible | [227d50ccd3](https://linux-hardware.org/?probe=227d50ccd3) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [2e4f2069e8](https://linux-hardware.org/?probe=2e4f2069e8) | Mar 06, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [9bfa331a22](https://linux-hardware.org/?probe=9bfa331a22) | Mar 06, 2023 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [c9e67a9174](https://linux-hardware.org/?probe=c9e67a9174) | Mar 06, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [a6c7741454](https://linux-hardware.org/?probe=a6c7741454) | Mar 06, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [ca2ad0edee](https://linux-hardware.org/?probe=ca2ad0edee) | Mar 05, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [a544ef69d8](https://linux-hardware.org/?probe=a544ef69d8) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96738d19ab](https://linux-hardware.org/?probe=96738d19ab) | Mar 05, 2023 |
| Acer          | Aspire A515-54              | Notebook    | [6c190c594b](https://linux-hardware.org/?probe=6c190c594b) | Mar 05, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [973f97d171](https://linux-hardware.org/?probe=973f97d171) | Mar 05, 2023 |
| Samsung       | 730QED                      | Convertible | [e97442a97b](https://linux-hardware.org/?probe=e97442a97b) | Mar 05, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [79d3147035](https://linux-hardware.org/?probe=79d3147035) | Mar 05, 2023 |
| Lenovo        | G50-80 80R0                 | Notebook    | [6d4a93e1d8](https://linux-hardware.org/?probe=6d4a93e1d8) | Mar 05, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [38bf7fda89](https://linux-hardware.org/?probe=38bf7fda89) | Mar 05, 2023 |
| Lenovo        | G50-80 80R0                 | Notebook    | [5e640d57d8](https://linux-hardware.org/?probe=5e640d57d8) | Mar 05, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [7950f8f750](https://linux-hardware.org/?probe=7950f8f750) | Mar 05, 2023 |
| Google        | Lillipup                    | Notebook    | [6c7cf4cd9e](https://linux-hardware.org/?probe=6c7cf4cd9e) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [a21f4171f1](https://linux-hardware.org/?probe=a21f4171f1) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [7e9b335ee0](https://linux-hardware.org/?probe=7e9b335ee0) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [48cf9d748f](https://linux-hardware.org/?probe=48cf9d748f) | Mar 05, 2023 |
| Acer          | Spin SP315-51               | Convertible | [d61c6e3f41](https://linux-hardware.org/?probe=d61c6e3f41) | Mar 04, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| PCWare        | APM-A320G                   | Desktop     | [2bc24b8935](https://linux-hardware.org/?probe=2bc24b8935) | Mar 04, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [62309a2dac](https://linux-hardware.org/?probe=62309a2dac) | Mar 04, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [a067a3c4a6](https://linux-hardware.org/?probe=a067a3c4a6) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [b61241e05e](https://linux-hardware.org/?probe=b61241e05e) | Mar 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [05dc2f9352](https://linux-hardware.org/?probe=05dc2f9352) | Mar 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [10c4eda3a2](https://linux-hardware.org/?probe=10c4eda3a2) | Mar 04, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [871c72708d](https://linux-hardware.org/?probe=871c72708d) | Mar 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05934ca860](https://linux-hardware.org/?probe=05934ca860) | Mar 04, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [463de722cd](https://linux-hardware.org/?probe=463de722cd) | Mar 04, 2023 |
| Dell          | G15 5520                    | Notebook    | [1e3dcc41d3](https://linux-hardware.org/?probe=1e3dcc41d3) | Mar 04, 2023 |
| Lenovo        | ThinkPad T430 234424P       | Notebook    | [54a25c6e4b](https://linux-hardware.org/?probe=54a25c6e4b) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [b7d678deee](https://linux-hardware.org/?probe=b7d678deee) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [d7b1fc0c9d](https://linux-hardware.org/?probe=d7b1fc0c9d) | Mar 04, 2023 |
| OEM           | Unknown                     | Desktop     | [d0f1ae246c](https://linux-hardware.org/?probe=d0f1ae246c) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | Desktop     | [6396907447](https://linux-hardware.org/?probe=6396907447) | Mar 03, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [d16e7dcded](https://linux-hardware.org/?probe=d16e7dcded) | Mar 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [be909f0882](https://linux-hardware.org/?probe=be909f0882) | Mar 03, 2023 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [4f279ee581](https://linux-hardware.org/?probe=4f279ee581) | Mar 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [845ed95f72](https://linux-hardware.org/?probe=845ed95f72) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [d1e6cecff5](https://linux-hardware.org/?probe=d1e6cecff5) | Mar 03, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5043ee2124](https://linux-hardware.org/?probe=5043ee2124) | Mar 03, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [1139097eb7](https://linux-hardware.org/?probe=1139097eb7) | Mar 03, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [f4292f5622](https://linux-hardware.org/?probe=f4292f5622) | Mar 03, 2023 |
| HP            | Compaq Presario CQ42        | Notebook    | [f8cfeeb2d9](https://linux-hardware.org/?probe=f8cfeeb2d9) | Mar 03, 2023 |
| Intel         | W7650                       | Notebook    | [30bde4c2d8](https://linux-hardware.org/?probe=30bde4c2d8) | Mar 03, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| Dell          | Latitude 3490               | Notebook    | [e23ef8765b](https://linux-hardware.org/?probe=e23ef8765b) | Mar 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [534da84bd1](https://linux-hardware.org/?probe=534da84bd1) | Mar 02, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [1427d9ce74](https://linux-hardware.org/?probe=1427d9ce74) | Mar 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [4a0bc37c58](https://linux-hardware.org/?probe=4a0bc37c58) | Mar 02, 2023 |
| DIEBOLD       | H55H-CM                     | Desktop     | [fadb939dd7](https://linux-hardware.org/?probe=fadb939dd7) | Mar 02, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [eebbe0447e](https://linux-hardware.org/?probe=eebbe0447e) | Mar 02, 2023 |
| ASRock        | 970A-G                      | Desktop     | [4a8ff8612a](https://linux-hardware.org/?probe=4a8ff8612a) | Mar 02, 2023 |
| Positivo      | POS-PIH55BO POSITIVO        | Desktop     | [ab9ad1a310](https://linux-hardware.org/?probe=ab9ad1a310) | Mar 02, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [3a56892391](https://linux-hardware.org/?probe=3a56892391) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| Supermicro    | X8DAH                       | Server      | [71610ce997](https://linux-hardware.org/?probe=71610ce997) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [1b3d15d8f6](https://linux-hardware.org/?probe=1b3d15d8f6) | Mar 01, 2023 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [0485a3d508](https://linux-hardware.org/?probe=0485a3d508) | Mar 01, 2023 |
| Sony          | VPCEH10EB                   | Notebook    | [9c8bb09559](https://linux-hardware.org/?probe=9c8bb09559) | Mar 01, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [7ec6d4d881](https://linux-hardware.org/?probe=7ec6d4d881) | Mar 01, 2023 |
| Positivo      | S14CT01                     | Notebook    | [312e70e158](https://linux-hardware.org/?probe=312e70e158) | Mar 01, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [44e24e77eb](https://linux-hardware.org/?probe=44e24e77eb) | Mar 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a91c417b74](https://linux-hardware.org/?probe=a91c417b74) | Mar 01, 2023 |
| HP            | Compaq Presario CQ42        | Notebook    | [5118aed3c9](https://linux-hardware.org/?probe=5118aed3c9) | Mar 01, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [be4fb3d705](https://linux-hardware.org/?probe=be4fb3d705) | Mar 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [884979d592](https://linux-hardware.org/?probe=884979d592) | Mar 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | Notebook    | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [05ad6c694b](https://linux-hardware.org/?probe=05ad6c694b) | Mar 01, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [5721cbc403](https://linux-hardware.org/?probe=5721cbc403) | Feb 28, 2023 |
| Philco        | 10D                         | Notebook    | [dd709d35db](https://linux-hardware.org/?probe=dd709d35db) | Feb 28, 2023 |
| Samsung       | 370E4K                      | Notebook    | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3948048a11](https://linux-hardware.org/?probe=3948048a11) | Feb 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [915fc4d913](https://linux-hardware.org/?probe=915fc4d913) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [77ff8fd545](https://linux-hardware.org/?probe=77ff8fd545) | Feb 28, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [47ed7baef0](https://linux-hardware.org/?probe=47ed7baef0) | Feb 28, 2023 |
| Dell          | G15 5510                    | Notebook    | [2c8f883abe](https://linux-hardware.org/?probe=2c8f883abe) | Feb 28, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [ee8e20d95e](https://linux-hardware.org/?probe=ee8e20d95e) | Feb 27, 2023 |
| PCWare        | IPMH61R2                    | Desktop     | [52a17bf9c1](https://linux-hardware.org/?probe=52a17bf9c1) | Feb 27, 2023 |
| Samsung       | 370E4K                      | Notebook    | [d66bcd2bc8](https://linux-hardware.org/?probe=d66bcd2bc8) | Feb 27, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [264f8cb6db](https://linux-hardware.org/?probe=264f8cb6db) | Feb 27, 2023 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [509c2a6e57](https://linux-hardware.org/?probe=509c2a6e57) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [04c721038a](https://linux-hardware.org/?probe=04c721038a) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| HP            | 430                         | Notebook    | [f90c967f06](https://linux-hardware.org/?probe=f90c967f06) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [86fac430ca](https://linux-hardware.org/?probe=86fac430ca) | Feb 26, 2023 |
| Samsung       | 370E4K                      | Notebook    | [7b769eb33e](https://linux-hardware.org/?probe=7b769eb33e) | Feb 26, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [31f6d9e11d](https://linux-hardware.org/?probe=31f6d9e11d) | Feb 26, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [47eff629e0](https://linux-hardware.org/?probe=47eff629e0) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| FIC           | PTM33 PCB                   | Desktop     | [b70b076cda](https://linux-hardware.org/?probe=b70b076cda) | Feb 26, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [2168c2bb5c](https://linux-hardware.org/?probe=2168c2bb5c) | Feb 26, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [066cc238c4](https://linux-hardware.org/?probe=066cc238c4) | Feb 26, 2023 |
| Dell          | G15 5520                    | Notebook    | [d68c28ea8d](https://linux-hardware.org/?probe=d68c28ea8d) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [0a5dfbb9e6](https://linux-hardware.org/?probe=0a5dfbb9e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [75e601b927](https://linux-hardware.org/?probe=75e601b927) | Feb 26, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [5911354b82](https://linux-hardware.org/?probe=5911354b82) | Feb 26, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [d205de771a](https://linux-hardware.org/?probe=d205de771a) | Feb 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [336a7cad31](https://linux-hardware.org/?probe=336a7cad31) | Feb 25, 2023 |
| Dell          | G7 7588                     | Notebook    | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [faee032e6c](https://linux-hardware.org/?probe=faee032e6c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [af95b24466](https://linux-hardware.org/?probe=af95b24466) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [37bcb5eb45](https://linux-hardware.org/?probe=37bcb5eb45) | Feb 25, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [d9f49e98fd](https://linux-hardware.org/?probe=d9f49e98fd) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5c3d39f884](https://linux-hardware.org/?probe=5c3d39f884) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [30afdb56c5](https://linux-hardware.org/?probe=30afdb56c5) | Feb 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [bfa5623f15](https://linux-hardware.org/?probe=bfa5623f15) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| HP            | 2AA2                        | Desktop     | [b9411eadb7](https://linux-hardware.org/?probe=b9411eadb7) | Feb 25, 2023 |
| ASUSTek       | Z450LA                      | Notebook    | [304be04748](https://linux-hardware.org/?probe=304be04748) | Feb 25, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [dff66700c0](https://linux-hardware.org/?probe=dff66700c0) | Feb 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [15b5511875](https://linux-hardware.org/?probe=15b5511875) | Feb 25, 2023 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [3f931a7600](https://linux-hardware.org/?probe=3f931a7600) | Feb 25, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [23c0509d46](https://linux-hardware.org/?probe=23c0509d46) | Feb 25, 2023 |
| Sony          | VPCCW13FB                   | Notebook    | [1772a3987b](https://linux-hardware.org/?probe=1772a3987b) | Feb 25, 2023 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [eb1e211b0f](https://linux-hardware.org/?probe=eb1e211b0f) | Feb 25, 2023 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [6d03ea4905](https://linux-hardware.org/?probe=6d03ea4905) | Feb 24, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [9cbbaaf012](https://linux-hardware.org/?probe=9cbbaaf012) | Feb 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [d3354bd88c](https://linux-hardware.org/?probe=d3354bd88c) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| PCWare        | IPMH61R2                    | Desktop     | [eda674b9a5](https://linux-hardware.org/?probe=eda674b9a5) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [5c7e454884](https://linux-hardware.org/?probe=5c7e454884) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6dd01c6a20](https://linux-hardware.org/?probe=6dd01c6a20) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1b5b668cea](https://linux-hardware.org/?probe=1b5b668cea) | Feb 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e3f8cf325d](https://linux-hardware.org/?probe=e3f8cf325d) | Feb 24, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [2a8b727725](https://linux-hardware.org/?probe=2a8b727725) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c0af9c8bdb](https://linux-hardware.org/?probe=c0af9c8bdb) | Feb 24, 2023 |
| Positivo      | N1103                       | Notebook    | [b89c4551aa](https://linux-hardware.org/?probe=b89c4551aa) | Feb 24, 2023 |
| Positivo      | Q464C-O                     | Notebook    | [cda1faecb1](https://linux-hardware.org/?probe=cda1faecb1) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [1bf7d82ab3](https://linux-hardware.org/?probe=1bf7d82ab3) | Feb 23, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [5f091de01b](https://linux-hardware.org/?probe=5f091de01b) | Feb 23, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [de05d0d3f6](https://linux-hardware.org/?probe=de05d0d3f6) | Feb 23, 2023 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [e60b570c27](https://linux-hardware.org/?probe=e60b570c27) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [5b4def0870](https://linux-hardware.org/?probe=5b4def0870) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| Dell          | Latitude 3420               | Notebook    | [86fd73d1e3](https://linux-hardware.org/?probe=86fd73d1e3) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d74903e764](https://linux-hardware.org/?probe=d74903e764) | Feb 23, 2023 |
| Intel         | H61                         | Desktop     | [5e26cd7b85](https://linux-hardware.org/?probe=5e26cd7b85) | Feb 23, 2023 |
| System76      | Gazelle                     | Notebook    | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [05f7c375b7](https://linux-hardware.org/?probe=05f7c375b7) | Feb 23, 2023 |
| Positivo      | POS-PQ45AU POSITIVO         | Desktop     | [8ed6dacaa7](https://linux-hardware.org/?probe=8ed6dacaa7) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [fd084cb513](https://linux-hardware.org/?probe=fd084cb513) | Feb 23, 2023 |
| Intel         | H61                         | Desktop     | [de757dd659](https://linux-hardware.org/?probe=de757dd659) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe9944c457](https://linux-hardware.org/?probe=fe9944c457) | Feb 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e23562af05](https://linux-hardware.org/?probe=e23562af05) | Feb 23, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [789bcfe82f](https://linux-hardware.org/?probe=789bcfe82f) | Feb 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b82d73c832](https://linux-hardware.org/?probe=b82d73c832) | Feb 22, 2023 |
| Positivo      | Q464C                       | Notebook    | [1b08f16a08](https://linux-hardware.org/?probe=1b08f16a08) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | Notebook    | [5b173518b5](https://linux-hardware.org/?probe=5b173518b5) | Feb 22, 2023 |
| Sony          | SVE15125CBW                 | Notebook    | [107bd5b235](https://linux-hardware.org/?probe=107bd5b235) | Feb 22, 2023 |
| PCWare        | IPMH61R2                    | Desktop     | [f02c3d5895](https://linux-hardware.org/?probe=f02c3d5895) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c99d1595ec](https://linux-hardware.org/?probe=c99d1595ec) | Feb 22, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [974ae4135b](https://linux-hardware.org/?probe=974ae4135b) | Feb 22, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [71aa647a28](https://linux-hardware.org/?probe=71aa647a28) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [d16dd6d1f3](https://linux-hardware.org/?probe=d16dd6d1f3) | Feb 22, 2023 |
| Positivo      | S14SL01                     | Notebook    | [914a9e691e](https://linux-hardware.org/?probe=914a9e691e) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [ad766a4190](https://linux-hardware.org/?probe=ad766a4190) | Feb 22, 2023 |
| Positivo      | Q232A                       | Notebook    | [71c020b7e4](https://linux-hardware.org/?probe=71c020b7e4) | Feb 22, 2023 |
| Positivo      | S14CT01                     | Notebook    | [af73fc0481](https://linux-hardware.org/?probe=af73fc0481) | Feb 22, 2023 |
| Samsung       | 767XCL                      | Notebook    | [3fb09fb626](https://linux-hardware.org/?probe=3fb09fb626) | Feb 22, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [ff88bcbafc](https://linux-hardware.org/?probe=ff88bcbafc) | Feb 22, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [aa39c9a471](https://linux-hardware.org/?probe=aa39c9a471) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [818012d7ef](https://linux-hardware.org/?probe=818012d7ef) | Feb 21, 2023 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [d1c356a1c7](https://linux-hardware.org/?probe=d1c356a1c7) | Feb 21, 2023 |
| INET          | Z12B                        | Mini pc     | [0baa359181](https://linux-hardware.org/?probe=0baa359181) | Feb 21, 2023 |
| INET          | Z12B                        | Mini pc     | [cc6d503d94](https://linux-hardware.org/?probe=cc6d503d94) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [ae2e7a22a0](https://linux-hardware.org/?probe=ae2e7a22a0) | Feb 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [08eab2bac4](https://linux-hardware.org/?probe=08eab2bac4) | Feb 21, 2023 |
| Avell High... | 1513                        | Notebook    | [0b46cb6de1](https://linux-hardware.org/?probe=0b46cb6de1) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [caccb434d2](https://linux-hardware.org/?probe=caccb434d2) | Feb 21, 2023 |
| Compaq        | 430                         | Notebook    | [4bd84653a5](https://linux-hardware.org/?probe=4bd84653a5) | Feb 21, 2023 |
| HP            | 1000                        | Notebook    | [91faf9460d](https://linux-hardware.org/?probe=91faf9460d) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| ASRock        | AM1B-MH                     | Desktop     | [d67d348d90](https://linux-hardware.org/?probe=d67d348d90) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Win elemen... | M600                        | Desktop     | [76c26f5ebb](https://linux-hardware.org/?probe=76c26f5ebb) | Feb 20, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [e7e12370af](https://linux-hardware.org/?probe=e7e12370af) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [cccf0ea7f3](https://linux-hardware.org/?probe=cccf0ea7f3) | Feb 20, 2023 |
| AMD           | A78FX VER                   | Desktop     | [36eb566c26](https://linux-hardware.org/?probe=36eb566c26) | Feb 20, 2023 |
| Intel         | H55                         | Desktop     | [6102979c67](https://linux-hardware.org/?probe=6102979c67) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [8c8ae38704](https://linux-hardware.org/?probe=8c8ae38704) | Feb 19, 2023 |
| Dell          | 04YP6J A03                  | Desktop     | [696cc9b57a](https://linux-hardware.org/?probe=696cc9b57a) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [7432db815e](https://linux-hardware.org/?probe=7432db815e) | Feb 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [aaee9da394](https://linux-hardware.org/?probe=aaee9da394) | Feb 19, 2023 |
| HP            | Compaq Presario CQ42        | Notebook    | [001f2f1a86](https://linux-hardware.org/?probe=001f2f1a86) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [ca537a9b24](https://linux-hardware.org/?probe=ca537a9b24) | Feb 19, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [d5dbc5770a](https://linux-hardware.org/?probe=d5dbc5770a) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Multilaser    | PC130                       | Notebook    | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [e06b3509f1](https://linux-hardware.org/?probe=e06b3509f1) | Feb 19, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [6be03ad579](https://linux-hardware.org/?probe=6be03ad579) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [34681494ec](https://linux-hardware.org/?probe=34681494ec) | Feb 18, 2023 |
| Avell High... | B.ON                        | Notebook    | [d7f2dafd5e](https://linux-hardware.org/?probe=d7f2dafd5e) | Feb 18, 2023 |
| Acer          | Spin SP315-51               | Convertible | [7a3814b168](https://linux-hardware.org/?probe=7a3814b168) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| Login Info... | LOG-H61H2-M2                | Desktop     | [889231ad64](https://linux-hardware.org/?probe=889231ad64) | Feb 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a782ccbba9](https://linux-hardware.org/?probe=a782ccbba9) | Feb 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [beff031939](https://linux-hardware.org/?probe=beff031939) | Feb 18, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [a2cdf7d471](https://linux-hardware.org/?probe=a2cdf7d471) | Feb 18, 2023 |
| Intel         | H61                         | Desktop     | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [f3c66a583b](https://linux-hardware.org/?probe=f3c66a583b) | Feb 17, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [daf6a78f6f](https://linux-hardware.org/?probe=daf6a78f6f) | Feb 17, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [de9c98193e](https://linux-hardware.org/?probe=de9c98193e) | Feb 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9d88e03390](https://linux-hardware.org/?probe=9d88e03390) | Feb 17, 2023 |
| Samsung       | 550XDA                      | Notebook    | [d7f1482689](https://linux-hardware.org/?probe=d7f1482689) | Feb 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [423c7bb57a](https://linux-hardware.org/?probe=423c7bb57a) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Intel         | B75                         | All in one  | [5d2d67dec2](https://linux-hardware.org/?probe=5d2d67dec2) | Feb 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [502adcba49](https://linux-hardware.org/?probe=502adcba49) | Feb 17, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [f69ff4a8c8](https://linux-hardware.org/?probe=f69ff4a8c8) | Feb 16, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [9200702bb7](https://linux-hardware.org/?probe=9200702bb7) | Feb 16, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [7b5fe965fd](https://linux-hardware.org/?probe=7b5fe965fd) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ebca46331e](https://linux-hardware.org/?probe=ebca46331e) | Feb 16, 2023 |
| DIEBOLD       | H55H-CM                     | Desktop     | [fdfc5c5e92](https://linux-hardware.org/?probe=fdfc5c5e92) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f3d6e20575](https://linux-hardware.org/?probe=f3d6e20575) | Feb 16, 2023 |
| Dell          | Inspiron 13-5378            | Notebook    | [cf5749e5be](https://linux-hardware.org/?probe=cf5749e5be) | Feb 16, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c14428167e](https://linux-hardware.org/?probe=c14428167e) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Positivo      | CHT14B                      | Notebook    | [49eff89b98](https://linux-hardware.org/?probe=49eff89b98) | Feb 16, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [b66ca441a7](https://linux-hardware.org/?probe=b66ca441a7) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [701fdae932](https://linux-hardware.org/?probe=701fdae932) | Feb 16, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [37674ee96e](https://linux-hardware.org/?probe=37674ee96e) | Feb 16, 2023 |
| Lenovo        | ThinkPad L470 20J4CTO1WW    | Notebook    | [7d55f655bb](https://linux-hardware.org/?probe=7d55f655bb) | Feb 15, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [4e0f0e0310](https://linux-hardware.org/?probe=4e0f0e0310) | Feb 15, 2023 |
| Itautec       | ST 4265                     | Desktop     | [84023fa8ac](https://linux-hardware.org/?probe=84023fa8ac) | Feb 15, 2023 |
| HP            | 8434 11                     | Desktop     | [2f4023e5f3](https://linux-hardware.org/?probe=2f4023e5f3) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [e42ed53dcf](https://linux-hardware.org/?probe=e42ed53dcf) | Feb 15, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [35fcd679e5](https://linux-hardware.org/?probe=35fcd679e5) | Feb 15, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [8385999199](https://linux-hardware.org/?probe=8385999199) | Feb 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1ca19c3d1d](https://linux-hardware.org/?probe=1ca19c3d1d) | Feb 14, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [7ec9e518c4](https://linux-hardware.org/?probe=7ec9e518c4) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | Notebook    | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Acer          | Predator G3-572             | Notebook    | [410a9aae8c](https://linux-hardware.org/?probe=410a9aae8c) | Feb 14, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [a401dfe086](https://linux-hardware.org/?probe=a401dfe086) | Feb 14, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [3569214674](https://linux-hardware.org/?probe=3569214674) | Feb 14, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [5fefbd2419](https://linux-hardware.org/?probe=5fefbd2419) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [0b0a816ecc](https://linux-hardware.org/?probe=0b0a816ecc) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [4785d6d596](https://linux-hardware.org/?probe=4785d6d596) | Feb 14, 2023 |
| Lenovo        | 312A NOK                    | Desktop     | [60794bd7c3](https://linux-hardware.org/?probe=60794bd7c3) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [03f90da8d3](https://linux-hardware.org/?probe=03f90da8d3) | Feb 14, 2023 |
| Lenovo        | G50-80 80R0                 | Notebook    | [86422b9261](https://linux-hardware.org/?probe=86422b9261) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| DIEBOLD       | NM70-I                      | Desktop     | [ed4d687c32](https://linux-hardware.org/?probe=ed4d687c32) | Feb 14, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [805931ad5f](https://linux-hardware.org/?probe=805931ad5f) | Feb 14, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [39564bbf72](https://linux-hardware.org/?probe=39564bbf72) | Feb 13, 2023 |
| Positivo      | CHT14B                      | Notebook    | [859e8a3c17](https://linux-hardware.org/?probe=859e8a3c17) | Feb 13, 2023 |
| Positivo      | CHT14B                      | Notebook    | [2d5b910ed3](https://linux-hardware.org/?probe=2d5b910ed3) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | Notebook    | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | Desktop     | [56411004d4](https://linux-hardware.org/?probe=56411004d4) | Feb 13, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [e4b1d6656b](https://linux-hardware.org/?probe=e4b1d6656b) | Feb 13, 2023 |
| Samsung       | 550XDA                      | Notebook    | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| Intel         | H61                         | Desktop     | [f220565e36](https://linux-hardware.org/?probe=f220565e36) | Feb 12, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [75f2859a68](https://linux-hardware.org/?probe=75f2859a68) | Feb 12, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [ec0e0c6dc2](https://linux-hardware.org/?probe=ec0e0c6dc2) | Feb 12, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [9fa2cd7dfb](https://linux-hardware.org/?probe=9fa2cd7dfb) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [df52d514c9](https://linux-hardware.org/?probe=df52d514c9) | Feb 12, 2023 |
| Intel         | H61                         | Desktop     | [800d3a961c](https://linux-hardware.org/?probe=800d3a961c) | Feb 12, 2023 |
| Intel         | H61                         | Desktop     | [7a6e4d8211](https://linux-hardware.org/?probe=7a6e4d8211) | Feb 12, 2023 |
| ASUSTek       | M5A88-M                     | Desktop     | [f1b285512e](https://linux-hardware.org/?probe=f1b285512e) | Feb 12, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [d2fec952ae](https://linux-hardware.org/?probe=d2fec952ae) | Feb 12, 2023 |
| Colorful T... | CVN B450M GAMING V14        | Desktop     | [fdedcd0d4a](https://linux-hardware.org/?probe=fdedcd0d4a) | Feb 11, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [1623076357](https://linux-hardware.org/?probe=1623076357) | Feb 11, 2023 |
| Compaq        | Presario CQ-14              | Desktop     | [515b629bbc](https://linux-hardware.org/?probe=515b629bbc) | Feb 11, 2023 |
| Samsung       | 767XCL                      | Notebook    | [8a62be0577](https://linux-hardware.org/?probe=8a62be0577) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [e32070b494](https://linux-hardware.org/?probe=e32070b494) | Feb 11, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [5b2605691d](https://linux-hardware.org/?probe=5b2605691d) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [31d099a8db](https://linux-hardware.org/?probe=31d099a8db) | Feb 11, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [594e3be773](https://linux-hardware.org/?probe=594e3be773) | Feb 11, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [2dca851444](https://linux-hardware.org/?probe=2dca851444) | Feb 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [f56c83d6dd](https://linux-hardware.org/?probe=f56c83d6dd) | Feb 11, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d85a564e73](https://linux-hardware.org/?probe=d85a564e73) | Feb 11, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | Desktop     | [abfd3f65af](https://linux-hardware.org/?probe=abfd3f65af) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | Notebook    | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [ca5ff923cc](https://linux-hardware.org/?probe=ca5ff923cc) | Feb 10, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [e3ad5a0e88](https://linux-hardware.org/?probe=e3ad5a0e88) | Feb 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [956a602343](https://linux-hardware.org/?probe=956a602343) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Gigabyte      | GA-A75-UD4H                 | Desktop     | [eb4302c6dd](https://linux-hardware.org/?probe=eb4302c6dd) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [52125d1623](https://linux-hardware.org/?probe=52125d1623) | Feb 10, 2023 |
| Samsung       | 550XDA                      | Notebook    | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| Lenovo        | Unknown                     | Desktop     | [253bcab6fa](https://linux-hardware.org/?probe=253bcab6fa) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [0f111bd12b](https://linux-hardware.org/?probe=0f111bd12b) | Feb 09, 2023 |
| ASRock        | B450M Pro4-F                | Desktop     | [35bd9cf04c](https://linux-hardware.org/?probe=35bd9cf04c) | Feb 09, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [2c17efbcd7](https://linux-hardware.org/?probe=2c17efbcd7) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3b71a70207](https://linux-hardware.org/?probe=3b71a70207) | Feb 09, 2023 |
| Positivo      | Smash2                      | Notebook    | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [c5c9fb9b41](https://linux-hardware.org/?probe=c5c9fb9b41) | Feb 09, 2023 |
| Acer          | Aspire A315-53G             | Notebook    | [e2a551b06b](https://linux-hardware.org/?probe=e2a551b06b) | Feb 09, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [452c65c04b](https://linux-hardware.org/?probe=452c65c04b) | Feb 09, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [5e1eb34232](https://linux-hardware.org/?probe=5e1eb34232) | Feb 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [fe84bf2bc9](https://linux-hardware.org/?probe=fe84bf2bc9) | Feb 09, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [43968e7a27](https://linux-hardware.org/?probe=43968e7a27) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [74f2ac0aeb](https://linux-hardware.org/?probe=74f2ac0aeb) | Feb 08, 2023 |
| Lenovo        | 3164 NOK                    | Desktop     | [750d30cb48](https://linux-hardware.org/?probe=750d30cb48) | Feb 08, 2023 |
| Dell          | 0TW904                      | Desktop     | [01c887764a](https://linux-hardware.org/?probe=01c887764a) | Feb 08, 2023 |
| Dell          | G15 5515                    | Notebook    | [3b0208199f](https://linux-hardware.org/?probe=3b0208199f) | Feb 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [acbbbca6e7](https://linux-hardware.org/?probe=acbbbca6e7) | Feb 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3245fc2fec](https://linux-hardware.org/?probe=3245fc2fec) | Feb 08, 2023 |
| Intel         | H61                         | Desktop     | [81e14fd083](https://linux-hardware.org/?probe=81e14fd083) | Feb 08, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [8fb3a20b27](https://linux-hardware.org/?probe=8fb3a20b27) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [127269499d](https://linux-hardware.org/?probe=127269499d) | Feb 07, 2023 |
| Dell          | 0TW904                      | Desktop     | [f88778be48](https://linux-hardware.org/?probe=f88778be48) | Feb 07, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | Notebook    | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7e020b928e](https://linux-hardware.org/?probe=7e020b928e) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0a94d67455](https://linux-hardware.org/?probe=0a94d67455) | Feb 07, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [83380dcad6](https://linux-hardware.org/?probe=83380dcad6) | Feb 07, 2023 |
| Lenovo        | 3102 NOK                    | Desktop     | [2a34c65a5d](https://linux-hardware.org/?probe=2a34c65a5d) | Feb 06, 2023 |
| Lenovo        | 3102 NOK                    | Desktop     | [0b35653efd](https://linux-hardware.org/?probe=0b35653efd) | Feb 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a2378e95f6](https://linux-hardware.org/?probe=a2378e95f6) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [cfdb3767fb](https://linux-hardware.org/?probe=cfdb3767fb) | Feb 06, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [986d240b5d](https://linux-hardware.org/?probe=986d240b5d) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [f0aa46956b](https://linux-hardware.org/?probe=f0aa46956b) | Feb 06, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0e0bd23571](https://linux-hardware.org/?probe=0e0bd23571) | Feb 05, 2023 |
| Quanta        | TWS                         | Notebook    | [275ccf1b58](https://linux-hardware.org/?probe=275ccf1b58) | Feb 05, 2023 |
| Dell          | G15 5510                    | Notebook    | [41bbdf84c2](https://linux-hardware.org/?probe=41bbdf84c2) | Feb 05, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [5c63c52fd4](https://linux-hardware.org/?probe=5c63c52fd4) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [02d439f664](https://linux-hardware.org/?probe=02d439f664) | Feb 05, 2023 |
| LG Electro... | R590-U.BE57P1               | Desktop     | [7de316c06f](https://linux-hardware.org/?probe=7de316c06f) | Feb 05, 2023 |
| ASRock        | H61M-HP4                    | Desktop     | [826a81ae2e](https://linux-hardware.org/?probe=826a81ae2e) | Feb 05, 2023 |
| OEM           | Intel H81                   | Desktop     | [806280459d](https://linux-hardware.org/?probe=806280459d) | Feb 05, 2023 |
| Lenovo        | G400s VILG1                 | Notebook    | [426348e103](https://linux-hardware.org/?probe=426348e103) | Feb 05, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [f2423d1d75](https://linux-hardware.org/?probe=f2423d1d75) | Feb 05, 2023 |
| Dell          | G15 5515                    | Notebook    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| Evolute       | SFX-65                      | Notebook    | [7b37b32f92](https://linux-hardware.org/?probe=7b37b32f92) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [7cd8292c5f](https://linux-hardware.org/?probe=7cd8292c5f) | Feb 04, 2023 |
| Lenovo        | ThinkCentre M57p 6073AG7    | Desktop     | [01a8e618f5](https://linux-hardware.org/?probe=01a8e618f5) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7659183894](https://linux-hardware.org/?probe=7659183894) | Feb 04, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [de29ca3277](https://linux-hardware.org/?probe=de29ca3277) | Feb 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0185beaec6](https://linux-hardware.org/?probe=0185beaec6) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [701a355d37](https://linux-hardware.org/?probe=701a355d37) | Feb 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| ECS           | A780GM-A                    | Desktop     | [2cb7086ff1](https://linux-hardware.org/?probe=2cb7086ff1) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | Notebook    | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| ECS           | A780GM-A                    | Desktop     | [6f6599f880](https://linux-hardware.org/?probe=6f6599f880) | Feb 04, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [06af577a0c](https://linux-hardware.org/?probe=06af577a0c) | Feb 04, 2023 |
| Dell          | Precision M4600             | Notebook    | [a0d6749416](https://linux-hardware.org/?probe=a0d6749416) | Feb 04, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [6f3ba6b805](https://linux-hardware.org/?probe=6f3ba6b805) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | Notebook    | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| HP            | 3048h                       | Desktop     | [03b28af2be](https://linux-hardware.org/?probe=03b28af2be) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [5c7d71b636](https://linux-hardware.org/?probe=5c7d71b636) | Feb 03, 2023 |
| Intel         | H61                         | Desktop     | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [f99e3aa76d](https://linux-hardware.org/?probe=f99e3aa76d) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| Dell          | 0TW904                      | Desktop     | [83d5b82840](https://linux-hardware.org/?probe=83d5b82840) | Feb 03, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [656df2cea9](https://linux-hardware.org/?probe=656df2cea9) | Feb 03, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3e5a2f20cc](https://linux-hardware.org/?probe=3e5a2f20cc) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [a99bd855d2](https://linux-hardware.org/?probe=a99bd855d2) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [b82450078c](https://linux-hardware.org/?probe=b82450078c) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2aa4452578](https://linux-hardware.org/?probe=2aa4452578) | Feb 02, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [17a4a2e5fd](https://linux-hardware.org/?probe=17a4a2e5fd) | Feb 02, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [92d639c0f4](https://linux-hardware.org/?probe=92d639c0f4) | Feb 02, 2023 |
| Dell          | Latitude 7480               | Notebook    | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de08972b9](https://linux-hardware.org/?probe=2de08972b9) | Feb 02, 2023 |
| Positivo      | Mobile                      | Notebook    | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [516e83f7e6](https://linux-hardware.org/?probe=516e83f7e6) | Feb 02, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [721bc8fb78](https://linux-hardware.org/?probe=721bc8fb78) | Feb 02, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [1d26f2fcbc](https://linux-hardware.org/?probe=1d26f2fcbc) | Feb 02, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [895cb06490](https://linux-hardware.org/?probe=895cb06490) | Feb 02, 2023 |
| Insyde        | Braswell                    | Notebook    | [928b461a5b](https://linux-hardware.org/?probe=928b461a5b) | Feb 02, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [e296e8530f](https://linux-hardware.org/?probe=e296e8530f) | Feb 02, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [9a5e6fd61e](https://linux-hardware.org/?probe=9a5e6fd61e) | Feb 02, 2023 |
| Philco        | 14I                         | Notebook    | [8f9833285e](https://linux-hardware.org/?probe=8f9833285e) | Feb 01, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [7d271a8235](https://linux-hardware.org/?probe=7d271a8235) | Feb 01, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [c4e6e989f5](https://linux-hardware.org/?probe=c4e6e989f5) | Feb 01, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [b2dd8d93c7](https://linux-hardware.org/?probe=b2dd8d93c7) | Feb 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [6aa10285fe](https://linux-hardware.org/?probe=6aa10285fe) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [fa4104f438](https://linux-hardware.org/?probe=fa4104f438) | Feb 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [ec80fcb8a5](https://linux-hardware.org/?probe=ec80fcb8a5) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [9aee0a798c](https://linux-hardware.org/?probe=9aee0a798c) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | Desktop     | [20868d90a7](https://linux-hardware.org/?probe=20868d90a7) | Feb 01, 2023 |
| PCWare        | IPX525R2-D3                 | Desktop     | [d67831dc82](https://linux-hardware.org/?probe=d67831dc82) | Feb 01, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [aa3b7e2dc8](https://linux-hardware.org/?probe=aa3b7e2dc8) | Feb 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f2b211ff3a](https://linux-hardware.org/?probe=f2b211ff3a) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f6f4bc8c7](https://linux-hardware.org/?probe=2f6f4bc8c7) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [9b73123be3](https://linux-hardware.org/?probe=9b73123be3) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| AZW           | U59                         | Desktop     | [74f028454a](https://linux-hardware.org/?probe=74f028454a) | Feb 01, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| AMD           | Inagua CRB                  | Desktop     | [3f497311dd](https://linux-hardware.org/?probe=3f497311dd) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Dell          | 06HR05 A00                  | Desktop     | [b80c55d90d](https://linux-hardware.org/?probe=b80c55d90d) | Jan 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d8d386cb1d](https://linux-hardware.org/?probe=d8d386cb1d) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [bb5d758714](https://linux-hardware.org/?probe=bb5d758714) | Jan 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d8f44aeb4c](https://linux-hardware.org/?probe=d8f44aeb4c) | Jan 31, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [e5dc585024](https://linux-hardware.org/?probe=e5dc585024) | Jan 31, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [75fad3daf3](https://linux-hardware.org/?probe=75fad3daf3) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [95fe94d9f4](https://linux-hardware.org/?probe=95fe94d9f4) | Jan 30, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [88db10e257](https://linux-hardware.org/?probe=88db10e257) | Jan 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [79e7fde988](https://linux-hardware.org/?probe=79e7fde988) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | Notebook    | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Avell High... | B.ON                        | Notebook    | [721fbbdeb2](https://linux-hardware.org/?probe=721fbbdeb2) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [1c62beb905](https://linux-hardware.org/?probe=1c62beb905) | Jan 29, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [ca82a3e5a7](https://linux-hardware.org/?probe=ca82a3e5a7) | Jan 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [51245400df](https://linux-hardware.org/?probe=51245400df) | Jan 29, 2023 |
| Intel         | H61                         | Desktop     | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [0e6a170715](https://linux-hardware.org/?probe=0e6a170715) | Jan 29, 2023 |
| Intel         | H61                         | Desktop     | [0ce404915f](https://linux-hardware.org/?probe=0ce404915f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [351106d7e5](https://linux-hardware.org/?probe=351106d7e5) | Jan 29, 2023 |
| Positivo      | Q464C-O                     | Notebook    | [e61f2d0622](https://linux-hardware.org/?probe=e61f2d0622) | Jan 29, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [da753d74a1](https://linux-hardware.org/?probe=da753d74a1) | Jan 29, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [fead488cf1](https://linux-hardware.org/?probe=fead488cf1) | Jan 29, 2023 |
| ASUSTek       | PRIME Z690-A                | Desktop     | [8dee7ae6ec](https://linux-hardware.org/?probe=8dee7ae6ec) | Jan 28, 2023 |
| Dell          | G15 5520                    | Notebook    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [ca72045652](https://linux-hardware.org/?probe=ca72045652) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [de8739d9d5](https://linux-hardware.org/?probe=de8739d9d5) | Jan 28, 2023 |
| ASUSTek       | A58M-A/BR                   | Desktop     | [2e6e55e6ea](https://linux-hardware.org/?probe=2e6e55e6ea) | Jan 28, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [41ff395299](https://linux-hardware.org/?probe=41ff395299) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f1f5def619](https://linux-hardware.org/?probe=f1f5def619) | Jan 28, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [fd9d67e4b8](https://linux-hardware.org/?probe=fd9d67e4b8) | Jan 27, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3ee2e6ab56](https://linux-hardware.org/?probe=3ee2e6ab56) | Jan 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [c74ea31148](https://linux-hardware.org/?probe=c74ea31148) | Jan 27, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8965805130](https://linux-hardware.org/?probe=8965805130) | Jan 27, 2023 |
| HP            | Compaq 6530b                | Notebook    | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [5a32be51f4](https://linux-hardware.org/?probe=5a32be51f4) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | Notebook    | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [93be3d62c4](https://linux-hardware.org/?probe=93be3d62c4) | Jan 27, 2023 |
| Compaq        | 430                         | Notebook    | [069fa715b9](https://linux-hardware.org/?probe=069fa715b9) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [b4d0bbaf56](https://linux-hardware.org/?probe=b4d0bbaf56) | Jan 27, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [d155136857](https://linux-hardware.org/?probe=d155136857) | Jan 27, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [05dac90dec](https://linux-hardware.org/?probe=05dac90dec) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [0697311f5f](https://linux-hardware.org/?probe=0697311f5f) | Jan 27, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [5a333d4e71](https://linux-hardware.org/?probe=5a333d4e71) | Jan 26, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [90de00d686](https://linux-hardware.org/?probe=90de00d686) | Jan 26, 2023 |
| Dell          | G3 3500                     | Notebook    | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| HP            | 225E                        | Desktop     | [bace147a01](https://linux-hardware.org/?probe=bace147a01) | Jan 26, 2023 |
| HP            | 8299                        | Desktop     | [d73eaeeb81](https://linux-hardware.org/?probe=d73eaeeb81) | Jan 26, 2023 |
| HP            | 8299                        | Desktop     | [47b5f3fdef](https://linux-hardware.org/?probe=47b5f3fdef) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| Dell          | Vostro 3458                 | Notebook    | [3beffe6710](https://linux-hardware.org/?probe=3beffe6710) | Jan 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d632bd0c9f](https://linux-hardware.org/?probe=d632bd0c9f) | Jan 26, 2023 |
| ASUSTek       | Z550SA                      | Notebook    | [f5ac147c1e](https://linux-hardware.org/?probe=f5ac147c1e) | Jan 26, 2023 |
| Multilaser    | PC150                       | Notebook    | [1c4ace00d1](https://linux-hardware.org/?probe=1c4ace00d1) | Jan 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f69047309d](https://linux-hardware.org/?probe=f69047309d) | Jan 26, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b392e71ce5](https://linux-hardware.org/?probe=b392e71ce5) | Jan 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6eafb4ceab](https://linux-hardware.org/?probe=6eafb4ceab) | Jan 25, 2023 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [b8045702e2](https://linux-hardware.org/?probe=b8045702e2) | Jan 25, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [5e044ca68b](https://linux-hardware.org/?probe=5e044ca68b) | Jan 25, 2023 |
| HP            | G60                         | Notebook    | [8fe616c588](https://linux-hardware.org/?probe=8fe616c588) | Jan 25, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [a123c38d76](https://linux-hardware.org/?probe=a123c38d76) | Jan 25, 2023 |
| MSI           | 2A9C                        | Desktop     | [cea7204c4b](https://linux-hardware.org/?probe=cea7204c4b) | Jan 25, 2023 |
| HP            | Folio 13                    | Notebook    | [214197bef4](https://linux-hardware.org/?probe=214197bef4) | Jan 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8780aceeec](https://linux-hardware.org/?probe=8780aceeec) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [3e59c1f38b](https://linux-hardware.org/?probe=3e59c1f38b) | Jan 25, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [2fbe64570f](https://linux-hardware.org/?probe=2fbe64570f) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [7de7df58a3](https://linux-hardware.org/?probe=7de7df58a3) | Jan 24, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [fce5f618d8](https://linux-hardware.org/?probe=fce5f618d8) | Jan 24, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [02491de92f](https://linux-hardware.org/?probe=02491de92f) | Jan 24, 2023 |
| Compaq        | 420                         | Notebook    | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [fe1a2d7fc6](https://linux-hardware.org/?probe=fe1a2d7fc6) | Jan 24, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [418e5a2787](https://linux-hardware.org/?probe=418e5a2787) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Insyde        | Braswell                    | Notebook    | [6abab0adc1](https://linux-hardware.org/?probe=6abab0adc1) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| ASUSTek       | K46CB                       | Notebook    | [62aa75f57a](https://linux-hardware.org/?probe=62aa75f57a) | Jan 23, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [30967bc549](https://linux-hardware.org/?probe=30967bc549) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [4a97e29245](https://linux-hardware.org/?probe=4a97e29245) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [54ebd7c5f8](https://linux-hardware.org/?probe=54ebd7c5f8) | Jan 23, 2023 |
| Dell          | Latitude 3420               | Notebook    | [d2a8b9657a](https://linux-hardware.org/?probe=d2a8b9657a) | Jan 23, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [6395ea422c](https://linux-hardware.org/?probe=6395ea422c) | Jan 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [08f11b861b](https://linux-hardware.org/?probe=08f11b861b) | Jan 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f0c7e0be](https://linux-hardware.org/?probe=e7f0c7e0be) | Jan 23, 2023 |
| Alienware     | m15 R7                      | Notebook    | [e57302bf60](https://linux-hardware.org/?probe=e57302bf60) | Jan 23, 2023 |
| HP            | 540                         | Notebook    | [a4a7b26f42](https://linux-hardware.org/?probe=a4a7b26f42) | Jan 23, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [885f180987](https://linux-hardware.org/?probe=885f180987) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Unknown       | G41T-M7                     | Desktop     | [026810c423](https://linux-hardware.org/?probe=026810c423) | Jan 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7d4406c9bc](https://linux-hardware.org/?probe=7d4406c9bc) | Jan 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| Biostar       | A320MH                      | Desktop     | [4c75d6c079](https://linux-hardware.org/?probe=4c75d6c079) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [14a5fa99db](https://linux-hardware.org/?probe=14a5fa99db) | Jan 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7afed6351](https://linux-hardware.org/?probe=e7afed6351) | Jan 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [569626e023](https://linux-hardware.org/?probe=569626e023) | Jan 22, 2023 |
| Dell          | G3 3500                     | Notebook    | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [43aaf27a04](https://linux-hardware.org/?probe=43aaf27a04) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | Notebook    | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [697fbcd8d1](https://linux-hardware.org/?probe=697fbcd8d1) | Jan 22, 2023 |
| Dell          | G3 3500                     | Notebook    | [e81b4d5e46](https://linux-hardware.org/?probe=e81b4d5e46) | Jan 22, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [b066912bf8](https://linux-hardware.org/?probe=b066912bf8) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [e5fff0ebe0](https://linux-hardware.org/?probe=e5fff0ebe0) | Jan 21, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [42e0ba4db2](https://linux-hardware.org/?probe=42e0ba4db2) | Jan 21, 2023 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [8a3035382a](https://linux-hardware.org/?probe=8a3035382a) | Jan 21, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [6ddc2793d7](https://linux-hardware.org/?probe=6ddc2793d7) | Jan 21, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [ae4c9eaa9c](https://linux-hardware.org/?probe=ae4c9eaa9c) | Jan 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ed9d60d9b7](https://linux-hardware.org/?probe=ed9d60d9b7) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| Philco        | OEM                         | Notebook    | [a39f50ccfd](https://linux-hardware.org/?probe=a39f50ccfd) | Jan 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f94d5172](https://linux-hardware.org/?probe=e7f94d5172) | Jan 21, 2023 |
| Lenovo        | 3148 SDK0L22692 WIN 3792... | Desktop     | [f66c33020e](https://linux-hardware.org/?probe=f66c33020e) | Jan 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [edee5aee7a](https://linux-hardware.org/?probe=edee5aee7a) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [fa251ca13c](https://linux-hardware.org/?probe=fa251ca13c) | Jan 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [965d1fa09f](https://linux-hardware.org/?probe=965d1fa09f) | Jan 20, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [a37e873516](https://linux-hardware.org/?probe=a37e873516) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | Desktop     | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [138a9b3b0c](https://linux-hardware.org/?probe=138a9b3b0c) | Jan 20, 2023 |
| Intel         | B75                         | Desktop     | [40da372747](https://linux-hardware.org/?probe=40da372747) | Jan 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6364be5249](https://linux-hardware.org/?probe=6364be5249) | Jan 20, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [46e35da681](https://linux-hardware.org/?probe=46e35da681) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [2d420c3acb](https://linux-hardware.org/?probe=2d420c3acb) | Jan 20, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [c158cd6095](https://linux-hardware.org/?probe=c158cd6095) | Jan 20, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [97987f88e7](https://linux-hardware.org/?probe=97987f88e7) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [4f815d5b4f](https://linux-hardware.org/?probe=4f815d5b4f) | Jan 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7ab1c1990](https://linux-hardware.org/?probe=c7ab1c1990) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [33a3aac223](https://linux-hardware.org/?probe=33a3aac223) | Jan 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3447d19b00](https://linux-hardware.org/?probe=3447d19b00) | Jan 20, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1320f35331](https://linux-hardware.org/?probe=1320f35331) | Jan 20, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9d5faff505](https://linux-hardware.org/?probe=9d5faff505) | Jan 20, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [cc9e6f8862](https://linux-hardware.org/?probe=cc9e6f8862) | Jan 19, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [c2f25e54e6](https://linux-hardware.org/?probe=c2f25e54e6) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [440ff298e7](https://linux-hardware.org/?probe=440ff298e7) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [d4480b6267](https://linux-hardware.org/?probe=d4480b6267) | Jan 19, 2023 |
| Intel         | H110                        | Desktop     | [532f2a340e](https://linux-hardware.org/?probe=532f2a340e) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [41138327da](https://linux-hardware.org/?probe=41138327da) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [183de4d0f6](https://linux-hardware.org/?probe=183de4d0f6) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62aa341472](https://linux-hardware.org/?probe=62aa341472) | Jan 19, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [c2ed0fe829](https://linux-hardware.org/?probe=c2ed0fe829) | Jan 19, 2023 |
| Digitron      | G31T-M7                     | Desktop     | [ee9978ae25](https://linux-hardware.org/?probe=ee9978ae25) | Jan 19, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [58bed7db63](https://linux-hardware.org/?probe=58bed7db63) | Jan 19, 2023 |
| Compal        | Unknown                     | Notebook    | [81abfdb7d5](https://linux-hardware.org/?probe=81abfdb7d5) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Compal        | Unknown                     | Notebook    | [14cc4178d9](https://linux-hardware.org/?probe=14cc4178d9) | Jan 18, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [fd498f882b](https://linux-hardware.org/?probe=fd498f882b) | Jan 18, 2023 |
| Intel         | H61                         | Desktop     | [be9b2384b0](https://linux-hardware.org/?probe=be9b2384b0) | Jan 18, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [80022afba6](https://linux-hardware.org/?probe=80022afba6) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3f0d644eaf](https://linux-hardware.org/?probe=3f0d644eaf) | Jan 18, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [1aac8c57f8](https://linux-hardware.org/?probe=1aac8c57f8) | Jan 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [84479cfc00](https://linux-hardware.org/?probe=84479cfc00) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [22d07dfddf](https://linux-hardware.org/?probe=22d07dfddf) | Jan 18, 2023 |
| Toshiba       | STI 014293                  | Desktop     | [8e47b89089](https://linux-hardware.org/?probe=8e47b89089) | Jan 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98f8255c15](https://linux-hardware.org/?probe=98f8255c15) | Jan 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [009adbd75c](https://linux-hardware.org/?probe=009adbd75c) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [032ac1d52e](https://linux-hardware.org/?probe=032ac1d52e) | Jan 18, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [1a8a1eea59](https://linux-hardware.org/?probe=1a8a1eea59) | Jan 17, 2023 |
| Login Info... | LOG-H110M-G3                | Desktop     | [74defcfa62](https://linux-hardware.org/?probe=74defcfa62) | Jan 17, 2023 |
| AZW           | SER V01                     | Mini pc     | [6048d12291](https://linux-hardware.org/?probe=6048d12291) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [0b7d83316f](https://linux-hardware.org/?probe=0b7d83316f) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [c2dd87db86](https://linux-hardware.org/?probe=c2dd87db86) | Jan 17, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [cd9cdce064](https://linux-hardware.org/?probe=cd9cdce064) | Jan 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1511      | 11.79%  |
| Ubuntu 18.04       | 1032      | 8.05%   |
| Ubuntu 22.04       | 417       | 3.25%   |
| OpenMandriva 4.2   | 337       | 2.63%   |
| Pop!_OS 20.04      | 318       | 2.48%   |
| Linux Mint 20      | 314       | 2.45%   |
| Linux Mint 19.3    | 284       | 2.22%   |
| OpenMandriva 4.3   | 282       | 2.2%    |
| Linux Mint 19.1    | 235       | 1.83%   |
| Ubuntu 19.04       | 218       | 1.7%    |
| KDE neon 20.04     | 213       | 1.66%   |
| Linux Mint 20.3    | 211       | 1.65%   |
| Linux Mint 20.1    | 207       | 1.62%   |
| Manjaro            | 190       | 1.48%   |
| Arch               | 189       | 1.48%   |
| Zorin 16           | 184       | 1.44%   |
| Linux Mint 20.2    | 182       | 1.42%   |
| Pop!_OS 22.04      | 177       | 1.38%   |
| Ubuntu 19.10       | 173       | 1.35%   |
| Debian 11          | 166       | 1.3%    |
| Debian 10          | 155       | 1.21%   |
| Zorin 15           | 149       | 1.16%   |
| Arch Rolling       | 136       | 1.06%   |
| Pop!_OS 21.04      | 127       | 0.99%   |
| Pop!_OS 20.10      | 127       | 0.99%   |
| OpenMandriva 23.01 | 121       | 0.94%   |
| Fedora 34          | 120       | 0.94%   |
| Fedora 36          | 117       | 0.91%   |
| Xubuntu 20.04      | 115       | 0.9%    |
| Fedora 37          | 111       | 0.87%   |
| Fedora 32          | 111       | 0.87%   |
| Pop!_OS 21.10      | 110       | 0.86%   |
| Fedora 35          | 110       | 0.86%   |
| Fedora 33          | 105       | 0.82%   |
| Linux Mint 19.2    | 103       | 0.8%    |
| Kubuntu 20.04      | 101       | 0.79%   |
| Linux Mint 21      | 100       | 0.78%   |
| Ubuntu MATE 20.04  | 99        | 0.77%   |
| Ubuntu 20.10       | 99        | 0.77%   |
| Ubuntu 18.10       | 83        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3664      | 29.97%  |
| Linux Mint    | 1674      | 13.69%  |
| Endless       | 1032      | 8.44%   |
| Pop!_OS       | 825       | 6.75%   |
| OpenMandriva  | 800       | 6.54%   |
| Fedora        | 703       | 5.75%   |
| Debian        | 422       | 3.45%   |
| Manjaro       | 368       | 3.01%   |
| Zorin         | 342       | 2.8%    |
| Arch          | 312       | 2.55%   |
| KDE neon      | 263       | 2.15%   |
| Xubuntu       | 225       | 1.84%   |
| Kubuntu       | 209       | 1.71%   |
| Ubuntu MATE   | 135       | 1.1%    |
| ROSA          | 126       | 1.03%   |
| openSUSE      | 113       | 0.92%   |
| Lubuntu       | 104       | 0.85%   |
| Elementary    | 94        | 0.77%   |
| Ubuntu Unity  | 85        | 0.7%    |
| LMDE          | 64        | 0.52%   |
| Kali          | 58        | 0.47%   |
| Deepin        | 46        | 0.38%   |
| ArcoLinux     | 44        | 0.36%   |
| Ubuntu Budgie | 41        | 0.34%   |
| LinuxFX       | 40        | 0.33%   |
| Clear Linux   | 35        | 0.29%   |
| CentOS        | 30        | 0.25%   |
| BlackPanther  | 30        | 0.25%   |
| BigLinux      | 30        | 0.25%   |
| EndeavourOS   | 22        | 0.18%   |
| Gentoo        | 18        | 0.15%   |
| Parrot        | 16        | 0.13%   |
| Peppermint    | 14        | 0.11%   |
| MX            | 14        | 0.11%   |
| Garuda Linux  | 14        | 0.11%   |
| UbuntuDDE     | 12        | 0.1%    |
| Nobara        | 12        | 0.1%    |
| Linux Lite    | 12        | 0.1%    |
| Solus         | 11        | 0.09%   |
| Reborn OS     | 11        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 710       | 5.14%   |
| 5.10.14-desktop-1omv4002 | 326       | 2.36%   |
| 5.8.0-14-generic         | 314       | 2.28%   |
| 5.16.7-desktop-1omv4003  | 267       | 1.93%   |
| 4.15.0-46-generic        | 156       | 1.13%   |
| 5.3.0-28-generic         | 146       | 1.06%   |
| 5.4.0-48-generic         | 138       | 1%      |
| 5.4.0-19-generic         | 138       | 1%      |
| 5.4.0-7634-generic       | 123       | 0.89%   |
| 6.1.1-desktop-1omv2290   | 112       | 0.81%   |
| 5.4.0-40-generic         | 111       | 0.8%    |
| 5.11.0-35-generic        | 110       | 0.8%    |
| 5.4.0-58-generic         | 109       | 0.79%   |
| 5.4.0-26-generic         | 105       | 0.76%   |
| 5.4.0-52-generic         | 101       | 0.73%   |
| 5.15.0-56-generic        | 99        | 0.72%   |
| 4.18.0-15-generic        | 97        | 0.7%    |
| 5.4.0-47-generic         | 96        | 0.7%    |
| 5.3.0-40-generic         | 89        | 0.64%   |
| 5.11.0-7620-generic      | 78        | 0.57%   |
| 5.0.0-32-generic         | 78        | 0.57%   |
| 5.3.0-46-generic         | 77        | 0.56%   |
| 5.0.0-37-generic         | 72        | 0.52%   |
| 4.15.0-20-generic        | 72        | 0.52%   |
| 5.4.0-70-generic         | 71        | 0.51%   |
| 5.4.0-72-generic         | 68        | 0.49%   |
| 5.15.0-52-generic        | 66        | 0.48%   |
| 5.15.0-46-generic        | 66        | 0.48%   |
| 5.4.0-91-generic         | 65        | 0.47%   |
| 5.4.0-80-generic         | 63        | 0.46%   |
| 5.3.0-23-generic         | 63        | 0.46%   |
| 5.4.0-29-generic         | 62        | 0.45%   |
| 4.18.0-16-generic        | 62        | 0.45%   |
| 5.4.0-65-generic         | 61        | 0.44%   |
| 5.4.0-37-generic         | 61        | 0.44%   |
| 5.4.0-39-generic         | 60        | 0.43%   |
| 5.0.0-25-generic         | 60        | 0.43%   |
| 5.4.0-74-generic         | 59        | 0.43%   |
| 5.8.0-7630-generic       | 58        | 0.42%   |
| 5.3.0-19-generic         | 58        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 3024      | 23.14%  |
| 4.15.0  | 942       | 7.21%   |
| 5.8.0   | 898       | 6.87%   |
| 5.3.0   | 799       | 6.11%   |
| 5.15.0  | 760       | 5.82%   |
| 5.11.0  | 703       | 5.38%   |
| 5.0.0   | 563       | 4.31%   |
| 5.13.0  | 462       | 3.54%   |
| 4.18.0  | 416       | 3.18%   |
| 5.10.14 | 328       | 2.51%   |
| 5.16.7  | 267       | 2.04%   |
| 5.10.0  | 219       | 1.68%   |
| 4.19.0  | 184       | 1.41%   |
| 5.19.0  | 182       | 1.39%   |
| 6.1.1   | 122       | 0.93%   |
| 5.17.5  | 59        | 0.45%   |
| 5.7.9   | 47        | 0.36%   |
| 6.0.12  | 46        | 0.35%   |
| 4.4.0   | 46        | 0.35%   |
| 5.16.11 | 40        | 0.31%   |
| 5.14.0  | 40        | 0.31%   |
| 4.9.0   | 40        | 0.31%   |
| 5.15.5  | 31        | 0.24%   |
| 5.7.0   | 30        | 0.23%   |
| 5.15.15 | 30        | 0.23%   |
| 6.2.6   | 28        | 0.21%   |
| 5.9.16  | 28        | 0.21%   |
| 5.6.19  | 27        | 0.21%   |
| 4.9.60  | 27        | 0.21%   |
| 5.3.18  | 25        | 0.19%   |
| 5.11.12 | 25        | 0.19%   |
| 4.18.16 | 25        | 0.19%   |
| 6.0.0   | 24        | 0.18%   |
| 5.13.19 | 24        | 0.18%   |
| 5.18.12 | 23        | 0.18%   |
| 5.7.10  | 22        | 0.17%   |
| 5.16.13 | 22        | 0.17%   |
| 6.0.6   | 21        | 0.16%   |
| 5.16.15 | 21        | 0.16%   |
| 5.18.10 | 20        | 0.15%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3149      | 24.4%   |
| 5.15    | 1031      | 7.99%   |
| 5.8     | 1011      | 7.83%   |
| 4.15    | 942       | 7.3%    |
| 5.3     | 870       | 6.74%   |
| 5.11    | 800       | 6.2%    |
| 5.10    | 738       | 5.72%   |
| 5.0     | 605       | 4.69%   |
| 5.13    | 554       | 4.29%   |
| 5.16    | 452       | 3.5%    |
| 4.18    | 449       | 3.48%   |
| 5.19    | 280       | 2.17%   |
| 6.1     | 244       | 1.89%   |
| 4.19    | 220       | 1.7%    |
| 6.0     | 192       | 1.49%   |
| 5.7     | 172       | 1.33%   |
| 5.17    | 156       | 1.21%   |
| 5.18    | 137       | 1.06%   |
| 5.14    | 132       | 1.02%   |
| 5.6     | 126       | 0.98%   |
| 5.12    | 113       | 0.88%   |
| 5.9     | 110       | 0.85%   |
| 4.9     | 106       | 0.82%   |
| 6.2     | 71        | 0.55%   |
| 4.4     | 52        | 0.4%    |
| 5.5     | 50        | 0.39%   |
| 5.1     | 39        | 0.3%    |
| 5.2     | 29        | 0.22%   |
| 3.10    | 15        | 0.12%   |
| 4.13    | 13        | 0.1%    |
| 4.1     | 12        | 0.09%   |
| 4.20    | 10        | 0.08%   |
| 4.10    | 8         | 0.06%   |
| 4.12    | 6         | 0.05%   |
| 4.14    | 5         | 0.04%   |
| 4.8     | 3         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 11363     | 97.17%  |
| i686    | 300       | 2.57%   |
| aarch64 | 19        | 0.16%   |
| armv7l  | 12        | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 5595      | 45.76%  |
| Unknown                  | 1812      | 14.82%  |
| KDE5                     | 1524      | 12.46%  |
| X-Cinnamon               | 995       | 8.14%   |
| XFCE                     | 810       | 6.62%   |
| MATE                     | 351       | 2.87%   |
| KDE                      | 311       | 2.54%   |
| Cinnamon                 | 221       | 1.81%   |
| LXQt                     | 102       | 0.83%   |
| Unity                    | 88        | 0.72%   |
| Pantheon                 | 82        | 0.67%   |
| KDE4                     | 66        | 0.54%   |
| Deepin                   | 59        | 0.48%   |
| Budgie                   | 59        | 0.48%   |
| LXDE                     | 52        | 0.43%   |
| i3                       | 32        | 0.26%   |
| GNOME Flashback          | 16        | 0.13%   |
| GNOME Classic            | 13        | 0.11%   |
| awesome                  | 10        | 0.08%   |
| sway                     | 6         | 0.05%   |
| Enlightenment            | 5         | 0.04%   |
| Openbox                  | 4         | 0.03%   |
| bspwm                    | 3         | 0.02%   |
| qtile                    | 2         | 0.02%   |
| Hyprland                 | 2         | 0.02%   |
| xmonad                   | 1         | 0.01%   |
| Trinity                  | 1         | 0.01%   |
| jwm                      | 1         | 0.01%   |
| icewm                    | 1         | 0.01%   |
| GNUstep                  | 1         | 0.01%   |
| GNOME:Phosh              | 1         | 0.01%   |
| 03WindowMaker            | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 9787      | 81.65%  |
| Wayland | 1228      | 10.24%  |
| Unknown | 889       | 7.42%   |
| Tty     | 81        | 0.68%   |
| Web     | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7577      | 62.6%   |
| SDDM    | 1336      | 11.04%  |
| GDM     | 1220      | 10.08%  |
| GDM3    | 735       | 6.07%   |
| LightDM | 611       | 5.05%   |
| TDM     | 538       | 4.44%   |
| KDM     | 66        | 0.55%   |
| XDM     | 9         | 0.07%   |
| SLiM    | 5         | 0.04%   |
| LXDM    | 3         | 0.02%   |
| MDM     | 2         | 0.02%   |
| SLIMSKI | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 7863      | 65.74%  |
| en_US       | 2075      | 17.35%  |
| Unknown     | 1698      | 14.2%   |
| C           | 171       | 1.43%   |
| en_GB       | 47        | 0.39%   |
| pt_PT       | 44        | 0.37%   |
| es_ES       | 18        | 0.15%   |
| en_CA       | 8         | 0.07%   |
| fr_FR       | 6         | 0.05%   |
| de_DE       | 5         | 0.04%   |
| POSIX       | 3         | 0.03%   |
| pt_BRutf8   | 2         | 0.02%   |
| ja_JP       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| en_AG       | 2         | 0.02%   |
| C.UTF8      | 2         | 0.02%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_CL       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| en_DK       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 6793      | 56.73%  |
| EFI  | 5181      | 43.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 9274      | 77.44%  |
| Overlay | 956       | 7.98%   |
| Btrfs   | 828       | 6.91%   |
| Unknown | 705       | 5.89%   |
| Xfs     | 87        | 0.73%   |
| Zfs     | 45        | 0.38%   |
| Tmpfs   | 24        | 0.2%    |
| Ext3    | 21        | 0.18%   |
| Ext2    | 18        | 0.15%   |
| F2fs    | 14        | 0.12%   |
| Aufs    | 4         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 7937      | 66.21%  |
| GPT     | 2721      | 22.7%   |
| MBR     | 1329      | 11.09%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10485     | 88.34%  |
| Yes       | 1384      | 11.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8798      | 74.01%  |
| Yes       | 3090      | 25.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 1889      | 16.16%  |
| ASUSTek Computer        | 1558      | 13.33%  |
| Acer                    | 1383      | 11.83%  |
| Lenovo                  | 994       | 8.51%   |
| Gigabyte Technology     | 764       | 6.54%   |
| Positivo                | 673       | 5.76%   |
| Hewlett-Packard         | 626       | 5.36%   |
| Samsung Electronics     | 602       | 5.15%   |
| Intel                   | 422       | 3.61%   |
| ASRock                  | 383       | 3.28%   |
| Unknown                 | 219       | 1.87%   |
| MSI                     | 206       | 1.76%   |
| Sony                    | 153       | 1.31%   |
| LG Electronics          | 124       | 1.06%   |
| Apple                   | 120       | 1.03%   |
| PCWare                  | 109       | 0.93%   |
| Itautec                 | 109       | 0.93%   |
| Semp Toshiba            | 105       | 0.9%    |
| Biostar                 | 85        | 0.73%   |
| Avell High Performance  | 77        | 0.66%   |
| Pegatron                | 70        | 0.6%    |
| Digibras                | 69        | 0.59%   |
| ECS                     | 61        | 0.52%   |
| Philco                  | 49        | 0.42%   |
| OEM                     | 49        | 0.42%   |
| Multilaser              | 49        | 0.42%   |
| Compaq                  | 40        | 0.34%   |
| Positivo Bahia - VAIO   | 36        | 0.31%   |
| Toshiba                 | 35        | 0.3%    |
| Megaware                | 30        | 0.26%   |
| Huanan                  | 30        | 0.26%   |
| Foxconn                 | 27        | 0.23%   |
| Notebook                | 25        | 0.21%   |
| Clevo                   | 23        | 0.2%    |
| Login Informatica       | 21        | 0.18%   |
| Gateway                 | 21        | 0.18%   |
| Compal                  | 19        | 0.16%   |
| Raspberry Pi Foundation | 17        | 0.15%   |
| Google                  | 17        | 0.15%   |
| Supermicro              | 16        | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 277       | 2.37%   |
| ASUS All Series                             | 143       | 1.22%   |
| Acer Nitro AN515-54                         | 136       | 1.16%   |
| Positivo Mobile                             | 120       | 1.03%   |
| Acer Nitro AN515-44                         | 82        | 0.7%    |
| Intel H61                                   | 78        | 0.67%   |
| Acer Aspire A315-53                         | 68        | 0.58%   |
| Samsung 340XAA/350XAA/550XAA                | 67        | 0.57%   |
| Dell Inspiron 5566                          | 63        | 0.54%   |
| Lenovo IdeaPad S145-15API 81V7              | 60        | 0.51%   |
| ASUS PRIME B450M-GAMING/BR                  | 60        | 0.51%   |
| Dell Inspiron 3583                          | 58        | 0.5%    |
| Lenovo IdeaPad 330-15IKB 81FE               | 54        | 0.46%   |
| Acer Aspire A315-34                         | 54        | 0.46%   |
| Dell Inspiron 15-3567                       | 53        | 0.45%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 51        | 0.44%   |
| Acer Nitro AN517-51                         | 51        | 0.44%   |
| ASRock A320M-HD                             | 50        | 0.43%   |
| Acer Aspire A515-51                         | 50        | 0.43%   |
| ASUS PRIME A320M-K/BR                       | 49        | 0.42%   |
| ASUS M5A78L-M LX/BR                         | 47        | 0.4%    |
| Acer Nitro AN515-43                         | 45        | 0.39%   |
| Intel H55                                   | 44        | 0.38%   |
| Semp Toshiba STI                            | 43        | 0.37%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 43        | 0.37%   |
| Samsung 300E5M/300E5L                       | 41        | 0.35%   |
| HP G42                                      | 40        | 0.34%   |
| Dell Inspiron 3442                          | 39        | 0.33%   |
| Positivo S14CT01                            | 38        | 0.33%   |
| Gigabyte H61M-S1                            | 38        | 0.33%   |
| Dell Inspiron N4050                         | 38        | 0.33%   |
| Dell Inspiron 3421                          | 38        | 0.33%   |
| Samsung 550XDA                              | 37        | 0.32%   |
| Itautec Infoway                             | 37        | 0.32%   |
| Acer Nitro AN515-52                         | 36        | 0.31%   |
| Gigabyte A320M-S2H                          | 35        | 0.3%    |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 33        | 0.28%   |
| Gigabyte B75M-D3H                           | 33        | 0.28%   |
| Digibras NH4CU03                            | 33        | 0.28%   |
| Dell Inspiron 7520                          | 33        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 1081      | 9.25%   |
| Acer Aspire        | 895       | 7.66%   |
| Lenovo IdeaPad     | 485       | 4.15%   |
| Acer Nitro         | 388       | 3.32%   |
| Unknown            | 277       | 2.37%   |
| Dell Vostro        | 235       | 2.01%   |
| ASUS PRIME         | 226       | 1.93%   |
| Lenovo ThinkPad    | 198       | 1.69%   |
| HP Pavilion        | 190       | 1.63%   |
| Dell Latitude      | 171       | 1.46%   |
| Dell OptiPlex      | 153       | 1.31%   |
| ASUS All           | 143       | 1.22%   |
| Positivo Mobile    | 120       | 1.03%   |
| ASUS M5A78L-M      | 117       | 1%      |
| ASUS VivoBook      | 115       | 0.98%   |
| Itautec Infoway    | 103       | 0.88%   |
| ASUS TUF           | 103       | 0.88%   |
| HP Compaq          | 98        | 0.84%   |
| ASUS P8H61-M       | 82        | 0.7%    |
| Intel H61          | 81        | 0.69%   |
| Samsung 340XAA     | 67        | 0.57%   |
| Lenovo ThinkCentre | 61        | 0.52%   |
| Dell G3            | 54        | 0.46%   |
| Dell XPS           | 53        | 0.45%   |
| ASUS ROG           | 51        | 0.44%   |
| ASRock A320M-HD    | 51        | 0.44%   |
| Semp Toshiba STI   | 50        | 0.43%   |
| HP ProBook         | 48        | 0.41%   |
| Samsung RV411      | 46        | 0.39%   |
| Intel H55          | 44        | 0.38%   |
| Samsung 300E5M     | 41        | 0.35%   |
| HP G42             | 40        | 0.34%   |
| Positivo S14CT01   | 38        | 0.33%   |
| Gigabyte H61M-S1   | 38        | 0.33%   |
| Dell System        | 38        | 0.33%   |
| Samsung 550XDA     | 37        | 0.32%   |
| HP EliteBook       | 35        | 0.3%    |
| Gigabyte A320M-S2H | 35        | 0.3%    |
| ASRock B450M       | 35        | 0.3%    |
| Acer Predator      | 34        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1227      | 10.5%   |
| 2012    | 1188      | 10.17%  |
| 2011    | 1116      | 9.55%   |
| 2018    | 1087      | 9.3%    |
| 2017    | 937       | 8.02%   |
| 2013    | 904       | 7.74%   |
| 2010    | 751       | 6.43%   |
| 2016    | 729       | 6.24%   |
| 2014    | 694       | 5.94%   |
| 2020    | 625       | 5.35%   |
| 2009    | 508       | 4.35%   |
| 2008    | 491       | 4.2%    |
| 2015    | 453       | 3.88%   |
| 2021    | 426       | 3.65%   |
| 2007    | 286       | 2.45%   |
| 2006    | 95        | 0.81%   |
| 2022    | 81        | 0.69%   |
| Unknown | 52        | 0.44%   |
| 2005    | 26        | 0.22%   |
| 2004    | 9         | 0.08%   |
| 2023    | 1         | 0.01%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6971      | 59.65%  |
| Desktop        | 4411      | 37.74%  |
| All in one     | 97        | 0.83%   |
| Convertible    | 79        | 0.68%   |
| Mini pc        | 44        | 0.38%   |
| Server         | 35        | 0.3%    |
| System on chip | 28        | 0.24%   |
| Tablet         | 20        | 0.17%   |
| Phone          | 1         | 0.01%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 10565     | 89.78%  |
| Enabled  | 1203      | 10.22%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11667     | 99.83%  |
| Yes  | 20        | 0.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3218      | 27.05%  |
| 3.01-4.0        | 3140      | 26.4%   |
| 8.01-16.0       | 2073      | 17.43%  |
| 16.01-24.0      | 1798      | 15.12%  |
| 1.01-2.0        | 792       | 6.66%   |
| 32.01-64.0      | 360       | 3.03%   |
| 2.01-3.0        | 263       | 2.21%   |
| 24.01-32.0      | 102       | 0.86%   |
| 64.01-256.0     | 79        | 0.66%   |
| 0.51-1.0        | 60        | 0.5%    |
| More than 256.0 | 6         | 0.05%   |
| 0.01-0.5        | 2         | 0.02%   |
| Unknown         | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 4838      | 37.49%  |
| 2.01-3.0    | 3487      | 27.02%  |
| 3.01-4.0    | 1628      | 12.61%  |
| 4.01-8.0    | 1529      | 11.85%  |
| 0.51-1.0    | 967       | 7.49%   |
| 8.01-16.0   | 294       | 2.28%   |
| 0.01-0.5    | 120       | 0.93%   |
| 16.01-24.0  | 26        | 0.2%    |
| 32.01-64.0  | 5         | 0.04%   |
| 24.01-32.0  | 5         | 0.04%   |
| Unknown     | 5         | 0.04%   |
| 64.01-256.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7468      | 62.26%  |
| 2       | 3271      | 27.27%  |
| 3       | 704       | 5.87%   |
| 4       | 274       | 2.28%   |
| 0       | 119       | 0.99%   |
| 5       | 83        | 0.69%   |
| 6       | 50        | 0.42%   |
| 7       | 10        | 0.08%   |
| 8       | 7         | 0.06%   |
| 9       | 5         | 0.04%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 7292      | 61.91%  |
| Yes       | 4487      | 38.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10728     | 91.65%  |
| No        | 977       | 8.35%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8569      | 72.82%  |
| No        | 3199      | 27.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5920      | 50.17%  |
| No        | 5881      | 49.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 11687     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 1522      | 12.43%  |
| Rio de Janeiro        | 704       | 5.75%   |
| Brasília             | 375       | 3.06%   |
| Belo Horizonte        | 340       | 2.78%   |
| Curitiba              | 333       | 2.72%   |
| Porto Alegre          | 269       | 2.2%    |
| Fortaleza             | 257       | 2.1%    |
| Campinas              | 183       | 1.49%   |
| Salvador              | 180       | 1.47%   |
| Recife                | 159       | 1.3%    |
| Goiânia              | 139       | 1.13%   |
| Florianópolis        | 133       | 1.09%   |
| Santo André          | 130       | 1.06%   |
| Natal                 | 107       | 0.87%   |
| Manaus                | 99        | 0.81%   |
| Niterói              | 95        | 0.78%   |
| Osasco                | 93        | 0.76%   |
| Sao José dos Campos  | 92        | 0.75%   |
| Guarulhos             | 92        | 0.75%   |
| Campo Grande          | 87        | 0.71%   |
| Sao Luís             | 82        | 0.67%   |
| Maringá              | 80        | 0.65%   |
| Sorocaba              | 79        | 0.65%   |
| Belém                | 77        | 0.63%   |
| Joinville             | 73        | 0.6%    |
| Joao Pessoa           | 72        | 0.59%   |
| Londrina              | 71        | 0.58%   |
| Teresina              | 70        | 0.57%   |
| Uberlândia           | 64        | 0.52%   |
| Ribeirao Preto        | 63        | 0.51%   |
| Juiz de Fora          | 63        | 0.51%   |
| Maceió               | 61        | 0.5%    |
| Aracaju               | 59        | 0.48%   |
| Serra                 | 56        | 0.46%   |
| Sao Jose              | 55        | 0.45%   |
| Cuiabá               | 55        | 0.45%   |
| Sao Bernardo do Campo | 53        | 0.43%   |
| Vitória              | 52        | 0.42%   |
| Duque de Caxias       | 52        | 0.42%   |
| Sao Carlos            | 50        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3331      | 4266   | 20.63%  |
| Seagate                        | 3152      | 4422   | 19.52%  |
| Kingston                       | 1629      | 2104   | 10.09%  |
| Samsung Electronics            | 1608      | 2223   | 9.96%   |
| Toshiba                        | 938       | 1094   | 5.81%   |
| SanDisk                        | 839       | 1127   | 5.2%    |
| Unknown                        | 497       | 678    | 3.08%   |
| A-DATA Technology              | 446       | 566    | 2.76%   |
| Hitachi                        | 377       | 464    | 2.34%   |
| China                          | 349       | 411    | 2.16%   |
| Intel                          | 304       | 372    | 1.88%   |
| Crucial                        | 289       | 377    | 1.79%   |
| Silicon Motion                 | 163       | 210    | 1.01%   |
| ADATA Technology               | 162       | 193    | 1%      |
| HGST                           | 136       | 161    | 0.84%   |
| SK hynix                       | 130       | 176    | 0.81%   |
| LITEON                         | 123       | 144    | 0.76%   |
| Maxtor                         | 120       | 140    | 0.74%   |
| KingSpec                       | 102       | 117    | 0.63%   |
| Lexar                          | 91        | 105    | 0.56%   |
| Realtek Semiconductor          | 73        | 90     | 0.45%   |
| Phison                         | 67        | 89     | 0.41%   |
| JMicron Technology             | 62        | 71     | 0.38%   |
| Corsair                        | 62        | 74     | 0.38%   |
| XPG                            | 58        | 71     | 0.36%   |
| Netac                          | 55        | 69     | 0.34%   |
| Fujitsu                        | 54        | 62     | 0.33%   |
| PNY                            | 45        | 54     | 0.28%   |
| Hewlett-Packard                | 42        | 50     | 0.26%   |
| Patriot                        | 41        | 56     | 0.25%   |
| SSSTC                          | 39        | 40     | 0.24%   |
| Apple                          | 38        | 55     | 0.24%   |
| Gigabyte Technology            | 35        | 47     | 0.22%   |
| XrayDisk                       | 34        | 42     | 0.21%   |
| Solid State Storage Technology | 32        | 43     | 0.2%    |
| Unknown                        | 32        | 33     | 0.2%    |
| KIOXIA                         | 31        | 36     | 0.19%   |
| Solid State Storage            | 29        | 32     | 0.18%   |
| KingDian                       | 27        | 34     | 0.17%   |
| Smart                          | 26        | 30     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 558       | 3.24%   |
| WDC WD10SPZX-21Z10T0 1TB            | 479       | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 306       | 1.78%   |
| Kingston SA400S37120G 120GB SSD     | 295       | 1.71%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 285       | 1.65%   |
| Kingston SA400S37480G 480GB SSD     | 278       | 1.61%   |
| Seagate ST500DM002-1BD142 500GB     | 248       | 1.44%   |
| Seagate ST1000DM010-2EP102 1TB      | 208       | 1.21%   |
| Toshiba MQ01ABD100 1TB              | 152       | 0.88%   |
| Kingston SV300S37A120G 120GB SSD    | 142       | 0.82%   |
| Unknown MMC Card  32GB              | 139       | 0.81%   |
| SanDisk SSD PLUS 240GB              | 137       | 0.8%    |
| WDC WD10SPZX-24Z10 1TB              | 136       | 0.79%   |
| Samsung HD322HJ 320GB               | 119       | 0.69%   |
| Seagate Expansion+ 2TB              | 118       | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 116       | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB            | 109       | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 105       | 0.61%   |
| Intel NVMe SSD Drive 512GB          | 103       | 0.6%    |
| Samsung HD161HJ 160GB               | 101       | 0.59%   |
| SanDisk SSD PLUS 120GB              | 100       | 0.58%   |
| Samsung HM321HI 320GB               | 100       | 0.58%   |
| Samsung HD502HJ 500GB               | 100       | 0.58%   |
| Seagate ST1000DM003-1ER162 1TB      | 96        | 0.56%   |
| Samsung HD502HI 500GB               | 96        | 0.56%   |
| Crucial CT240BX500SSD1 240GB        | 96        | 0.56%   |
| Seagate ST9500325AS 500GB           | 89        | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB      | 89        | 0.52%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 88        | 0.51%   |
| WDC WD10SPZX-75Z10T2 1TB            | 81        | 0.47%   |
| Toshiba MQ01ABF050 500GB            | 80        | 0.46%   |
| SanDisk SDSSDA240G 240GB            | 79        | 0.46%   |
| WDC WD5000AAKX-003CA0 500GB         | 77        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 77        | 0.45%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 72        | 0.42%   |
| Seagate ST3500418AS 500GB           | 71        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB        | 71        | 0.41%   |
| Intel SSDPEKKW256G7 256GB           | 71        | 0.41%   |
| WDC WD10EARS-00Y5B1 1TB             | 69        | 0.4%    |
| ADATA NVMe SSD Drive 256GB          | 69        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3137      | 4390   | 35.29%  |
| WDC                 | 2972      | 3715   | 33.44%  |
| Samsung Electronics | 1102      | 1444   | 12.4%   |
| Toshiba             | 890       | 1037   | 10.01%  |
| Hitachi             | 377       | 464    | 4.24%   |
| HGST                | 136       | 161    | 1.53%   |
| Maxtor              | 111       | 130    | 1.25%   |
| Fujitsu             | 53        | 60     | 0.6%    |
| Unknown             | 33        | 37     | 0.37%   |
| Apple               | 17        | 28     | 0.19%   |
| Hewlett-Packard     | 16        | 18     | 0.18%   |
| ExcelStor           | 10        | 11     | 0.11%   |
| SAGE                | 5         | 9      | 0.06%   |
| JMicron Technology  | 5         | 6      | 0.06%   |
| HPE                 | 4         | 4      | 0.05%   |
| ASMT                | 4         | 4      | 0.05%   |
| USB3.0              | 3         | 3      | 0.03%   |
| SABRENT             | 1         | 1      | 0.01%   |
| Phison              | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1569      | 2011   | 32.44%  |
| SanDisk             | 627       | 868    | 12.97%  |
| WDC                 | 360       | 448    | 7.44%   |
| China               | 348       | 410    | 7.2%    |
| Samsung Electronics | 330       | 505    | 6.82%   |
| Crucial             | 275       | 359    | 5.69%   |
| A-DATA Technology   | 264       | 322    | 5.46%   |
| LITEON              | 109       | 129    | 2.25%   |
| KingSpec            | 100       | 115    | 2.07%   |
| Lexar               | 88        | 102    | 1.82%   |
| JMicron Technology  | 50        | 58     | 1.03%   |
| Corsair             | 50        | 59     | 1.03%   |
| Intel               | 49        | 61     | 1.01%   |
| PNY                 | 43        | 52     | 0.89%   |
| Netac               | 42        | 53     | 0.87%   |
| Patriot             | 39        | 53     | 0.81%   |
| Gigabyte Technology | 28        | 39     | 0.58%   |
| Smart               | 26        | 30     | 0.54%   |
| KingDian            | 26        | 33     | 0.54%   |
| Unknown             | 22        | 24     | 0.45%   |
| SK hynix            | 20        | 24     | 0.41%   |
| Apple               | 20        | 24     | 0.41%   |
| Hewlett-Packard     | 19        | 23     | 0.39%   |
| XrayDisk            | 18        | 20     | 0.37%   |
| Toshiba             | 18        | 21     | 0.37%   |
| Seagate             | 17        | 20     | 0.35%   |
| Unknown             | 17        | 18     | 0.35%   |
| OCZ                 | 15        | 16     | 0.31%   |
| BHT                 | 14        | 18     | 0.29%   |
| LITEONIT            | 13        | 19     | 0.27%   |
| Micron Technology   | 10        | 12     | 0.21%   |
| Maxtor              | 9         | 10     | 0.19%   |
| Team                | 8         | 20     | 0.17%   |
| walram              | 7         | 7      | 0.14%   |
| RZX                 | 7         | 13     | 0.14%   |
| Plextor             | 7         | 8      | 0.14%   |
| HUSKY               | 7         | 8      | 0.14%   |
| HS-SSD-C100         | 7         | 7      | 0.14%   |
| Win Memory          | 6         | 7      | 0.12%   |
| S3+                 | 6         | 6      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7894      | 11538  | 53.84%  |
| SSD     | 4363      | 6210   | 29.76%  |
| NVMe    | 1889      | 2541   | 12.88%  |
| MMC     | 381       | 545    | 2.6%    |
| Unknown | 135       | 178    | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 10267     | 17436  | 79.59%  |
| NVMe | 1887      | 2538   | 14.63%  |
| MMC  | 381       | 545    | 2.95%   |
| SAS  | 365       | 493    | 2.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 7798      | 11678  | 63.51%  |
| 0.51-1.0   | 3704      | 4890   | 30.17%  |
| 1.01-2.0   | 580       | 828    | 4.72%   |
| 3.01-4.0   | 76        | 173    | 0.62%   |
| 2.01-3.0   | 67        | 98     | 0.55%   |
| 4.01-10.0  | 49        | 74     | 0.4%    |
| 10.01-20.0 | 4         | 6      | 0.03%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3447      | 27.89%  |
| 251-500        | 3005      | 24.31%  |
| 501-1000       | 2030      | 16.42%  |
| 1-20           | 954       | 7.72%   |
| 1001-2000      | 883       | 7.14%   |
| 51-100         | 785       | 6.35%   |
| 21-50          | 571       | 4.62%   |
| 2001-3000      | 244       | 1.97%   |
| Unknown        | 225       | 1.82%   |
| More than 3000 | 216       | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4893      | 38.29%  |
| 21-50          | 2724      | 21.32%  |
| 101-250        | 1587      | 12.42%  |
| 51-100         | 1547      | 12.11%  |
| 251-500        | 852       | 6.67%   |
| 501-1000       | 577       | 4.52%   |
| 1001-2000      | 252       | 1.97%   |
| Unknown        | 225       | 1.76%   |
| 2001-3000      | 65        | 0.51%   |
| More than 3000 | 56        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 45        | 48     | 3.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 42        | 45     | 3.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 29        | 31     | 2.32%   |
| Seagate ST9500325AS 500GB           | 25        | 27     | 2%      |
| WDC WD5000AAKX-003CA0 500GB         | 24        | 24     | 1.92%   |
| Samsung Electronics HD322HJ 320GB   | 22        | 29     | 1.76%   |
| Samsung Electronics HD161HJ 160GB   | 19        | 20     | 1.52%   |
| Samsung Electronics HD502HI 500GB   | 17        | 20     | 1.36%   |
| Samsung Electronics HD502HJ 500GB   | 14        | 14     | 1.12%   |
| Toshiba MQ01ABD100 1TB              | 13        | 13     | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB      | 13        | 13     | 1.04%   |
| WDC WD10EARS-00Y5B1 1TB             | 12        | 15     | 0.96%   |
| Kingston SV300S37A120G 120GB SSD    | 12        | 13     | 0.96%   |
| Toshiba MQ01ABD050 500GB            | 11        | 11     | 0.88%   |
| Seagate ST9320325AS 320GB           | 11        | 11     | 0.88%   |
| Seagate ST500LT012-9WS142 500GB     | 11        | 13     | 0.88%   |
| Seagate ST3500418AS 500GB           | 11        | 16     | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB      | 10        | 13     | 0.8%    |
| Maxtor STM3160215AS 160GB           | 10        | 11     | 0.8%    |
| WDC WD3200AAJS-00L7A0 320GB         | 9         | 9      | 0.72%   |
| Seagate ST3320418AS 320GB           | 9         | 13     | 0.72%   |
| Samsung Electronics HD250HJ 250GB   | 9         | 10     | 0.72%   |
| Samsung Electronics HD080HJ 80GB    | 9         | 11     | 0.72%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 10     | 0.72%   |
| Samsung Electronics HM321HI 320GB   | 8         | 8      | 0.64%   |
| Samsung Electronics HD103SJ 1TB     | 8         | 10     | 0.64%   |
| Kingston SA400S37240G 240GB SSD     | 8         | 8      | 0.64%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 12     | 0.64%   |
| Toshiba MQ02ABD100H 1TB             | 7         | 10     | 0.56%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 0.56%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 8      | 0.56%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 7         | 8      | 0.56%   |
| Seagate ST31000524AS 1TB            | 7         | 7      | 0.56%   |
| Seagate ST2000DM001-1CH164 2TB      | 7         | 9      | 0.56%   |
| Seagate ST1500DL003-9VT16L 1TB      | 7         | 8      | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 9      | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 6         | 7      | 0.48%   |
| WDC WD5000AAKX-083CA1 500GB         | 6         | 6      | 0.48%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 6         | 7      | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB            | 6         | 8      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 403       | 480    | 33.72%  |
| WDC                 | 264       | 302    | 22.09%  |
| Samsung Electronics | 179       | 223    | 14.98%  |
| Toshiba             | 100       | 108    | 8.37%   |
| Hitachi             | 63        | 67     | 5.27%   |
| Kingston            | 46        | 54     | 3.85%   |
| Maxtor              | 21        | 23     | 1.76%   |
| SanDisk             | 19        | 19     | 1.59%   |
| China               | 18        | 20     | 1.51%   |
| A-DATA Technology   | 11        | 11     | 0.92%   |
| HGST                | 9         | 9      | 0.75%   |
| Intel               | 6         | 6      | 0.5%    |
| XPG                 | 5         | 5      | 0.42%   |
| Fujitsu             | 5         | 6      | 0.42%   |
| PNY                 | 4         | 6      | 0.33%   |
| Crucial             | 4         | 4      | 0.33%   |
| OCZ                 | 3         | 3      | 0.25%   |
| KingSpec            | 3         | 3      | 0.25%   |
| Apple               | 3         | 3      | 0.25%   |
| XrayDisk            | 2         | 2      | 0.17%   |
| WALRAM              | 2         | 2      | 0.17%   |
| LITEON              | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 2      | 0.17%   |
| Corsair             | 2         | 2      | 0.17%   |
| Unknown             | 2         | 2      | 0.17%   |
| SSSTC               | 1         | 1      | 0.08%   |
| SK hynix            | 1         | 1      | 0.08%   |
| ShiJi               | 1         | 1      | 0.08%   |
| QIANGHE             | 1         | 1      | 0.08%   |
| Plextor             | 1         | 1      | 0.08%   |
| OCZ-VERTEX3         | 1         | 1      | 0.08%   |
| Netac               | 1         | 1      | 0.08%   |
| Mushkin             | 1         | 1      | 0.08%   |
| Micron Technology   | 1         | 1      | 0.08%   |
| LITEONIT            | 1         | 2      | 0.08%   |
| Kross Elegance      | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| Initio              | 1         | 1      | 0.08%   |
| FEASSO              | 1         | 2      | 0.08%   |
| ExcelStor           | 1         | 2      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 403       | 480    | 39.16%  |
| WDC                 | 250       | 287    | 24.3%   |
| Samsung Electronics | 173       | 217    | 16.81%  |
| Toshiba             | 99        | 107    | 9.62%   |
| Hitachi             | 63        | 67     | 6.12%   |
| Maxtor              | 21        | 23     | 2.04%   |
| HGST                | 9         | 9      | 0.87%   |
| Fujitsu             | 5         | 6      | 0.49%   |
| Hewlett-Packard     | 2         | 2      | 0.19%   |
| Apple               | 2         | 2      | 0.19%   |
| FEASSO              | 1         | 2      | 0.1%    |
| ExcelStor           | 1         | 2      | 0.1%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 942       | 1204   | 85.09%  |
| SSD  | 143       | 158    | 12.92%  |
| NVMe | 22        | 22     | 1.99%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 3         | 3      | 11.11%  |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 7.41%   |
| Samsung Electronics HD502HJ 500GB                | 2         | 4      | 7.41%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1         | 1      | 3.7%    |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 3.7%    |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 3.7%    |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 3.7%    |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 3.7%    |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 3.7%    |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 3.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 3.7%    |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 3.7%    |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 3.7%    |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 3.7%    |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 3.7%    |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 3.7%    |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 3.7%    |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 3.7%    |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 3.7%    |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 3.7%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 37.04%  |
| Seagate             | 8         | 8      | 29.63%  |
| WDC                 | 4         | 4      | 14.81%  |
| Toshiba             | 3         | 3      | 11.11%  |
| Maxtor              | 1         | 1      | 3.7%    |
| Hitachi             | 1         | 1      | 3.7%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 8319      | 14740  | 66.86%  |
| Works    | 3024      | 4858   | 24.3%   |
| Malfunc  | 1071      | 1384   | 8.61%   |
| Failed   | 27        | 29     | 0.22%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8912      | 67.21%  |
| AMD                              | 1889      | 14.25%  |
| ADATA Technology                 | 374       | 2.82%   |
| SanDisk                          | 268       | 2.02%   |
| Nvidia                           | 257       | 1.94%   |
| Samsung Electronics              | 222       | 1.67%   |
| Silicon Motion                   | 187       | 1.41%   |
| Solid State Storage Technology   | 113       | 0.85%   |
| Realtek Semiconductor            | 107       | 0.81%   |
| SK hynix                         | 103       | 0.78%   |
| Silicon Integrated Systems [SiS] | 102       | 0.77%   |
| Phison Electronics               | 100       | 0.75%   |
| Marvell Technology Group         | 83        | 0.63%   |
| Kingston Technology Company      | 81        | 0.61%   |
| JMicron Technology               | 81        | 0.61%   |
| VIA Technologies                 | 73        | 0.55%   |
| ASMedia Technology               | 69        | 0.52%   |
| Micron/Crucial Technology        | 37        | 0.28%   |
| KIOXIA                           | 30        | 0.23%   |
| Lite-On Technology               | 26        | 0.2%    |
| Toshiba America Info Systems     | 24        | 0.18%   |
| LSI Logic / Symbios Logic        | 21        | 0.16%   |
| MAXIO Technology (Hangzhou)      | 15        | 0.11%   |
| Micron Technology                | 12        | 0.09%   |
| Broadcom / LSI                   | 12        | 0.09%   |
| Union Memory (Shenzhen)          | 8         | 0.06%   |
| Silicon Image                    | 6         | 0.05%   |
| Netac Technology                 | 6         | 0.05%   |
| Beijing Starblaze Technology     | 6         | 0.05%   |
| Shenzhen Longsys Electronics     | 5         | 0.04%   |
| Seagate Technology               | 5         | 0.04%   |
| OCZ Technology Group             | 4         | 0.03%   |
| Adaptec                          | 4         | 0.03%   |
| Hewlett-Packard                  | 3         | 0.02%   |
| Apple                            | 3         | 0.02%   |
| Lenovo                           | 2         | 0.02%   |
| INNOGRIT                         | 2         | 0.02%   |
| Dell                             | 2         | 0.02%   |
| ULi Electronics                  | 1         | 0.01%   |
| TenaFe                           | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1155      | 7.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 986       | 6.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 836       | 5.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 628       | 3.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 581       | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 477       | 2.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 451       | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 404       | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 383       | 2.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 381       | 2.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 319       | 1.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 315       | 1.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 308       | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 294       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 246       | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 244       | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 244       | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 240       | 1.48%   |
| AMD FCH SATA Controller D                                                               | 222       | 1.37%   |
| AMD 400 Series Chipset SATA Controller                                                  | 218       | 1.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 212       | 1.31%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 206       | 1.27%   |
| Nvidia MCP61 SATA Controller                                                            | 179       | 1.1%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 170       | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 169       | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 164       | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 156       | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 149       | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 147       | 0.91%   |
| Nvidia MCP61 IDE                                                                        | 146       | 0.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 146       | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 143       | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 138       | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 137       | 0.84%   |
| ADATA Non-Volatile memory controller                                                    | 135       | 0.83%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 128       | 0.79%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                             | 128       | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 127       | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 127       | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 127       | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8852      | 63.51%  |
| IDE  | 2344      | 16.82%  |
| NVMe | 1900      | 13.63%  |
| RAID | 822       | 5.9%    |
| SCSI | 14        | 0.1%    |
| SAS  | 7         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 9500      | 81.29%  |
| AMD          | 2151      | 18.41%  |
| ARM          | 29        | 0.25%   |
| CentaurHauls | 5         | 0.04%   |
| Qualcomm     | 1         | 0.01%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 256       | 2.19%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 161       | 1.37%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 146       | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 143       | 1.22%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 135       | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 129       | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 128       | 1.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 120       | 1.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 120       | 1.02%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 120       | 1.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 111       | 0.95%   |
| AMD FX-6300 Six-Core Processor                | 94        | 0.8%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 93        | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 90        | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 90        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 89        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 89        | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 88        | 0.75%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 86        | 0.73%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 84        | 0.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 83        | 0.71%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 83        | 0.71%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 82        | 0.7%    |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 82        | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 78        | 0.67%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 78        | 0.67%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 76        | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 75        | 0.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 73        | 0.62%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 73        | 0.62%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 67        | 0.57%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 66        | 0.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 65        | 0.55%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 65        | 0.55%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 64        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 62        | 0.53%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 62        | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 61        | 0.52%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 61        | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 59        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2850      | 24.34%  |
| Intel Core i7           | 1856      | 15.85%  |
| Intel Core i3           | 1634      | 13.95%  |
| Intel Celeron           | 800       | 6.83%   |
| AMD Ryzen 5             | 527       | 4.5%    |
| Intel Core 2 Duo        | 515       | 4.4%    |
| Intel Pentium Dual-Core | 314       | 2.68%   |
| AMD Ryzen 7             | 313       | 2.67%   |
| Other                   | 311       | 2.66%   |
| Intel Atom              | 300       | 2.56%   |
| Intel Pentium           | 278       | 2.37%   |
| AMD FX                  | 258       | 2.2%    |
| Intel Xeon              | 224       | 1.91%   |
| Intel Pentium Dual      | 145       | 1.24%   |
| AMD Ryzen 3             | 103       | 0.88%   |
| Intel Core 2 Quad       | 97        | 0.83%   |
| AMD Phenom II X4        | 78        | 0.67%   |
| AMD Athlon II X2        | 73        | 0.62%   |
| AMD A4                  | 63        | 0.54%   |
| AMD A10                 | 58        | 0.5%    |
| AMD E                   | 57        | 0.49%   |
| Intel Core 2            | 53        | 0.45%   |
| AMD Athlon 64 X2        | 49        | 0.42%   |
| AMD A8                  | 49        | 0.42%   |
| AMD A6                  | 49        | 0.42%   |
| AMD Athlon              | 42        | 0.36%   |
| Intel Genuine           | 41        | 0.35%   |
| AMD C-60                | 41        | 0.35%   |
| AMD Ryzen 9             | 39        | 0.33%   |
| AMD E1                  | 34        | 0.29%   |
| AMD Sempron             | 31        | 0.26%   |
| Intel Pentium 4         | 29        | 0.25%   |
| AMD Phenom II X6        | 27        | 0.23%   |
| AMD C-70                | 26        | 0.22%   |
| Intel Pentium Gold      | 23        | 0.2%    |
| Intel Core i9           | 22        | 0.19%   |
| AMD Athlon II X4        | 18        | 0.15%   |
| AMD Phenom II X2        | 17        | 0.15%   |
| AMD C-50                | 17        | 0.15%   |
| Intel Celeron Dual-Core | 16        | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6271      | 53.55%  |
| 4       | 3683      | 31.45%  |
| 6       | 776       | 6.63%   |
| 8       | 373       | 3.19%   |
| 1       | 332       | 2.84%   |
| 3       | 138       | 1.18%   |
| 12      | 55        | 0.47%   |
| 10      | 23        | 0.2%    |
| 16      | 18        | 0.15%   |
| Unknown | 16        | 0.14%   |
| 14      | 11        | 0.09%   |
| 20      | 6         | 0.05%   |
| 24      | 4         | 0.03%   |
| 5       | 2         | 0.02%   |
| 32      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11644     | 99.62%  |
| 2       | 40        | 0.34%   |
| Unknown | 3         | 0.03%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7561      | 64.63%  |
| 1       | 4120      | 35.22%  |
| Unknown | 16        | 0.14%   |
| 8       | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11100     | 94.44%  |
| Unknown        | 544       | 4.63%   |
| 32-bit         | 62        | 0.53%   |
| 64-bit         | 48        | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2323      | 19.19%  |
| 0x306a9    | 995       | 8.22%   |
| 0x206a7    | 974       | 8.05%   |
| 0x1067a    | 637       | 5.26%   |
| 0x906ea    | 409       | 3.38%   |
| 0x806e9    | 409       | 3.38%   |
| 0x306c3    | 366       | 3.02%   |
| 0x20655    | 365       | 3.02%   |
| 0x40651    | 340       | 2.81%   |
| 0x806ec    | 324       | 2.68%   |
| 0x306d4    | 281       | 2.32%   |
| 0x406e3    | 277       | 2.29%   |
| 0x806ea    | 250       | 2.07%   |
| 0x6fd      | 246       | 2.03%   |
| 0x906e9    | 215       | 1.78%   |
| 0x406c4    | 178       | 1.47%   |
| 0x806c1    | 174       | 1.44%   |
| 0x08108109 | 152       | 1.26%   |
| 0x06000852 | 152       | 1.26%   |
| 0x010000c8 | 130       | 1.07%   |
| 0x30678    | 128       | 1.06%   |
| 0x20652    | 94        | 0.78%   |
| 0x05000119 | 94        | 0.78%   |
| 0x906ed    | 87        | 0.72%   |
| 0x08600103 | 84        | 0.69%   |
| 0x0800820d | 81        | 0.67%   |
| 0x10676    | 80        | 0.66%   |
| 0x08108102 | 79        | 0.65%   |
| 0x706e5    | 76        | 0.63%   |
| 0x506e3    | 75        | 0.62%   |
| 0x706a1    | 74        | 0.61%   |
| 0x08701021 | 74        | 0.61%   |
| 0x6fb      | 65        | 0.54%   |
| 0x106ca    | 61        | 0.5%    |
| 0x706a8    | 58        | 0.48%   |
| 0x406c3    | 58        | 0.48%   |
| 0x806eb    | 56        | 0.46%   |
| 0x08701013 | 54        | 0.45%   |
| 0x0600611a | 53        | 0.44%   |
| 0x306f2    | 52        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2143      | 18.32%  |
| IvyBridge        | 1217      | 10.4%   |
| SandyBridge      | 1170      | 10%     |
| Haswell          | 899       | 7.69%   |
| Penryn           | 830       | 7.1%    |
| Westmere         | 553       | 4.73%   |
| Core             | 465       | 3.98%   |
| Silvermont       | 453       | 3.87%   |
| Skylake          | 430       | 3.68%   |
| Zen+             | 399       | 3.41%   |
| Broadwell        | 337       | 2.88%   |
| K10              | 298       | 2.55%   |
| Piledriver       | 280       | 2.39%   |
| Zen 2            | 263       | 2.25%   |
| Zen              | 223       | 1.91%   |
| TigerLake        | 218       | 1.86%   |
| Bobcat           | 166       | 1.42%   |
| Goldmont plus    | 151       | 1.29%   |
| CometLake        | 145       | 1.24%   |
| Bonnell          | 124       | 1.06%   |
| Unknown          | 123       | 1.05%   |
| IceLake          | 117       | 1%      |
| K8 Hammer        | 106       | 0.91%   |
| Zen 3            | 98        | 0.84%   |
| Excavator        | 80        | 0.68%   |
| Nehalem          | 74        | 0.63%   |
| NetBurst         | 50        | 0.43%   |
| Goldmont         | 48        | 0.41%   |
| K10 Llano        | 46        | 0.39%   |
| Steamroller      | 42        | 0.36%   |
| Bulldozer        | 41        | 0.35%   |
| Jaguar           | 39        | 0.33%   |
| P6               | 26        | 0.22%   |
| Alderlake Hybrid | 19        | 0.16%   |
| K8 & K10 hybrid  | 11        | 0.09%   |
| Puma             | 7         | 0.06%   |
| Tremont          | 5         | 0.04%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7903      | 56.53%  |
| Nvidia                           | 3434      | 24.56%  |
| AMD                              | 2449      | 17.52%  |
| Silicon Integrated Systems [SiS] | 99        | 0.71%   |
| VIA Technologies                 | 55        | 0.39%   |
| Matrox Electronics Systems       | 24        | 0.17%   |
| ASPEED Technology                | 7         | 0.05%   |
| Silicon Motion                   | 4         | 0.03%   |
| ATI Technologies                 | 4         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 975       | 6.81%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 727       | 5.08%   |
| Intel HD Graphics 620                                                                    | 505       | 3.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 476       | 3.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 397       | 2.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 373       | 2.61%   |
| Intel HD Graphics 5500                                                                   | 306       | 2.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 288       | 2.01%   |
| Intel UHD Graphics 620                                                                   | 287       | 2.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 286       | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 281       | 1.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 273       | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 265       | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 253       | 1.77%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 239       | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 186       | 1.3%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 180       | 1.26%   |
| Intel HD Graphics 630                                                                    | 172       | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 172       | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 168       | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 165       | 1.15%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 159       | 1.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 159       | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 151       | 1.05%   |
| Nvidia GT218 [GeForce 210]                                                               | 143       | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 143       | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 132       | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 132       | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 103       | 0.72%   |
| AMD Renoir                                                                               | 103       | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 97        | 0.68%   |
| Nvidia TU117M                                                                            | 96        | 0.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 96        | 0.67%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 96        | 0.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 93        | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 90        | 0.63%   |
| Nvidia GM108M [GeForce MX110]                                                            | 88        | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 87        | 0.61%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 84        | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 84        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 5817      | 49.45%  |
| 1 x AMD                 | 1777      | 15.11%  |
| 1 x Nvidia              | 1646      | 13.99%  |
| Intel + Nvidia          | 1593      | 13.54%  |
| Intel + AMD             | 406       | 3.45%   |
| AMD + Nvidia            | 165       | 1.4%    |
| 2 x AMD                 | 108       | 0.92%   |
| 1 x SiS                 | 99        | 0.84%   |
| 1 x VIA                 | 54        | 0.46%   |
| Other                   | 33        | 0.28%   |
| 1 x Matrox              | 23        | 0.2%    |
| 2 x Nvidia              | 15        | 0.13%   |
| 2 x Intel               | 13        | 0.11%   |
| 1 x ASPEED              | 6         | 0.05%   |
| Intel + Silicon Motion  | 2         | 0.02%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + Matrox            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 9370      | 79.23%  |
| Proprietary | 1994      | 16.86%  |
| Unknown     | 463       | 3.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 7234      | 60.4%   |
| 1.01-2.0   | 1706      | 14.24%  |
| 0.01-0.5   | 1036      | 8.65%   |
| 0.51-1.0   | 791       | 6.6%    |
| 3.01-4.0   | 750       | 6.26%   |
| 7.01-8.0   | 191       | 1.59%   |
| 5.01-6.0   | 183       | 1.53%   |
| 2.01-3.0   | 60        | 0.5%    |
| 8.01-16.0  | 22        | 0.18%   |
| 4.01-5.0   | 2         | 0.02%   |
| 16.01-24.0 | 2         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1822      | 14.54%  |
| Goldstar                | 1620      | 12.92%  |
| BOE                     | 1499      | 11.96%  |
| AU Optronics            | 1468      | 11.71%  |
| Chimei Innolux          | 1175      | 9.37%   |
| LG Display              | 1116      | 8.9%    |
| AOC                     | 827       | 6.6%    |
| Dell                    | 515       | 4.11%   |
| Philips                 | 334       | 2.66%   |
| Acer                    | 196       | 1.56%   |
| Chi Mei Optoelectronics | 158       | 1.26%   |
| LG Electronics          | 152       | 1.21%   |
| Hewlett-Packard         | 123       | 0.98%   |
| InfoVision              | 122       | 0.97%   |
| PANDA                   | 112       | 0.89%   |
| Lenovo                  | 104       | 0.83%   |
| Apple                   | 104       | 0.83%   |
| Sony                    | 84        | 0.67%   |
| BenQ                    | 65        | 0.52%   |
| Unknown                 | 62        | 0.49%   |
| HannStar                | 48        | 0.38%   |
| CPT                     | 48        | 0.38%   |
| RTK                     | 47        | 0.37%   |
| Positivo                | 42        | 0.34%   |
| LG Philips              | 36        | 0.29%   |
| Panasonic               | 34        | 0.27%   |
| InnoLux Display         | 31        | 0.25%   |
| SLD                     | 28        | 0.22%   |
| ASUSTek Computer        | 28        | 0.22%   |
| Ancor Communications    | 25        | 0.2%    |
| Sharp                   | 24        | 0.19%   |
| GDH                     | 21        | 0.17%   |
| NCS                     | 20        | 0.16%   |
| Toshiba                 | 19        | 0.15%   |
| MTD                     | 18        | 0.14%   |
| HB@                     | 17        | 0.14%   |
| STA                     | 16        | 0.13%   |
| SKY                     | 15        | 0.12%   |
| AGO                     | 15        | 0.12%   |
| VIE                     | 14        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 167       | 1.3%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 119       | 0.92%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 118       | 0.92%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 111       | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 104       | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 101       | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 99        | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 97        | 0.75%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 96        | 0.74%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 78        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 77        | 0.6%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 74        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 72        | 0.56%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 70        | 0.54%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 67        | 0.52%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 67        | 0.52%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 66        | 0.51%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 63        | 0.49%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 62        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 61        | 0.47%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 60        | 0.47%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 58        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 57        | 0.44%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 56        | 0.43%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 56        | 0.43%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.42%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch          | 54        | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 53        | 0.41%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 53        | 0.41%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 51        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 51        | 0.4%    |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 46        | 0.36%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 45        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 44        | 0.34%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 44        | 0.34%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 44        | 0.34%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 44        | 0.34%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 41        | 0.32%   |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 41        | 0.32%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 41        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 4954      | 40.57%  |
| 1920x1080 (FHD)    | 3795      | 31.08%  |
| 1600x900 (HD+)     | 512       | 4.19%   |
| 1440x900 (WXGA+)   | 396       | 3.24%   |
| 2560x1080          | 388       | 3.18%   |
| 1360x768           | 341       | 2.79%   |
| 1280x1024 (SXGA)   | 336       | 2.75%   |
| 1280x800 (WXGA)    | 304       | 2.49%   |
| 3840x2160 (4K)     | 271       | 2.22%   |
| 1680x1050 (WSXGA+) | 189       | 1.55%   |
| 1024x768 (XGA)     | 118       | 0.97%   |
| 2560x1440 (QHD)    | 107       | 0.88%   |
| Unknown            | 104       | 0.85%   |
| 1920x1200 (WUXGA)  | 64        | 0.52%   |
| 1280x720 (HD)      | 48        | 0.39%   |
| 1024x600           | 41        | 0.34%   |
| 1920x540           | 36        | 0.29%   |
| 3840x1080          | 29        | 0.24%   |
| 2288x1287          | 22        | 0.18%   |
| 3440x1440          | 17        | 0.14%   |
| 2560x1600          | 12        | 0.1%    |
| 1152x864           | 9         | 0.07%   |
| 4480x1080          | 6         | 0.05%   |
| 1600x1200          | 6         | 0.05%   |
| 5760x1080          | 5         | 0.04%   |
| 3360x1080          | 5         | 0.04%   |
| 3286x1080          | 5         | 0.04%   |
| 3200x1080          | 5         | 0.04%   |
| 1280x960           | 5         | 0.04%   |
| 800x1280           | 4         | 0.03%   |
| 3840x2400          | 4         | 0.03%   |
| 2880x1800          | 4         | 0.03%   |
| 2736x1824          | 4         | 0.03%   |
| 3520x1080          | 3         | 0.02%   |
| 3200x1800 (QHD+)   | 3         | 0.02%   |
| 2732x768           | 3         | 0.02%   |
| 6400x1080          | 2         | 0.02%   |
| 3600x1080          | 2         | 0.02%   |
| 3360x1050          | 2         | 0.02%   |
| 2800x900           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3676      | 29.2%   |
| 14      | 1518      | 12.06%  |
| 13      | 1352      | 10.74%  |
| 18      | 839       | 6.67%   |
| 21      | 779       | 6.19%   |
| 23      | 736       | 5.85%   |
| 17      | 520       | 4.13%   |
| Unknown | 504       | 4%      |
| 24      | 363       | 2.88%   |
| 34      | 337       | 2.68%   |
| 20      | 309       | 2.45%   |
| 19      | 294       | 2.34%   |
| 27      | 280       | 2.22%   |
| 31      | 138       | 1.1%    |
| 22      | 119       | 0.95%   |
| 11      | 117       | 0.93%   |
| 12      | 79        | 0.63%   |
| 40      | 69        | 0.55%   |
| 72      | 63        | 0.5%    |
| 32      | 57        | 0.45%   |
| 28      | 55        | 0.44%   |
| 84      | 47        | 0.37%   |
| 10      | 47        | 0.37%   |
| 54      | 46        | 0.37%   |
| 16      | 40        | 0.32%   |
| 52      | 34        | 0.27%   |
| 26      | 34        | 0.27%   |
| 46      | 29        | 0.23%   |
| 47      | 16        | 0.13%   |
| 37      | 12        | 0.1%    |
| 142     | 11        | 0.09%   |
| 48      | 10        | 0.08%   |
| 25      | 7         | 0.06%   |
| 58      | 6         | 0.05%   |
| 65      | 5         | 0.04%   |
| 39      | 5         | 0.04%   |
| 43      | 4         | 0.03%   |
| 41      | 4         | 0.03%   |
| 7       | 4         | 0.03%   |
| 50      | 3         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 6451      | 52.02%  |
| 401-500        | 2216      | 17.87%  |
| 501-600        | 1323      | 10.67%  |
| Unknown        | 504       | 4.06%   |
| 201-300        | 465       | 3.75%   |
| 351-400        | 441       | 3.56%   |
| 701-800        | 395       | 3.18%   |
| 601-700        | 226       | 1.82%   |
| 1001-1500      | 156       | 1.26%   |
| 1501-2000      | 111       | 0.9%    |
| 801-900        | 89        | 0.72%   |
| More than 2000 | 11        | 0.09%   |
| 901-1000       | 10        | 0.08%   |
| 1-100          | 4         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 9054      | 79.74%  |
| 16/10   | 914       | 8.05%   |
| Unknown | 427       | 3.76%   |
| 21/9    | 374       | 3.29%   |
| 5/4     | 330       | 2.91%   |
| 4/3     | 176       | 1.55%   |
| 3/2     | 54        | 0.48%   |
| 1.00    | 13        | 0.11%   |
| 32/9    | 4         | 0.04%   |
| 0.67    | 4         | 0.04%   |
| 6/5     | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3634      | 29.03%  |
| 81-90          | 2695      | 21.53%  |
| 201-250        | 1693      | 13.52%  |
| 141-150        | 1027      | 8.2%    |
| 151-200        | 861       | 6.88%   |
| 351-500        | 548       | 4.38%   |
| Unknown        | 504       | 4.03%   |
| 301-350        | 289       | 2.31%   |
| More than 1000 | 231       | 1.85%   |
| 71-80          | 179       | 1.43%   |
| 501-1000       | 148       | 1.18%   |
| 251-300        | 143       | 1.14%   |
| 121-130        | 142       | 1.13%   |
| 131-140        | 118       | 0.94%   |
| 51-60          | 117       | 0.93%   |
| 91-100         | 52        | 0.42%   |
| 41-50          | 47        | 0.38%   |
| 61-70          | 44        | 0.35%   |
| 111-120        | 43        | 0.34%   |
| 1-40           | 4         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 5142      | 42.25%  |
| 51-100        | 4012      | 32.97%  |
| 121-160       | 1988      | 16.34%  |
| Unknown       | 505       | 4.15%   |
| 1-50          | 338       | 2.78%   |
| 161-240       | 160       | 1.31%   |
| More than 240 | 25        | 0.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 9505      | 79.59%  |
| 2     | 1861      | 15.58%  |
| 0     | 480       | 4.02%   |
| 3     | 90        | 0.75%   |
| 4     | 6         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 8329      | 44.86%  |
| Qualcomm Atheros                  | 3662      | 19.72%  |
| Intel                             | 3130      | 16.86%  |
| Broadcom                          | 851       | 4.58%   |
| Ralink Technology                 | 416       | 2.24%   |
| Marvell Technology Group          | 233       | 1.25%   |
| Nvidia                            | 215       | 1.16%   |
| JMicron Technology                | 214       | 1.15%   |
| Ralink                            | 211       | 1.14%   |
| Broadcom Limited                  | 186       | 1%      |
| TP-Link                           | 179       | 0.96%   |
| Qualcomm Atheros Communications   | 131       | 0.71%   |
| Samsung Electronics               | 111       | 0.6%    |
| Silicon Integrated Systems [SiS]  | 100       | 0.54%   |
| D-Link                            | 73        | 0.39%   |
| VIA Technologies                  | 70        | 0.38%   |
| Xiaomi                            | 49        | 0.26%   |
| Motorola PCS                      | 48        | 0.26%   |
| Microsoft                         | 43        | 0.23%   |
| D-Link System                     | 39        | 0.21%   |
| MediaTek                          | 38        | 0.2%    |
| ASIX Electronics                  | 34        | 0.18%   |
| ICS Advent                        | 18        | 0.1%    |
| Motorola                          | 14        | 0.08%   |
| DisplayLink                       | 11        | 0.06%   |
| Huawei Technologies               | 10        | 0.05%   |
| Edimax Technology                 | 8         | 0.04%   |
| Qualcomm                          | 7         | 0.04%   |
| LG Electronics                    | 7         | 0.04%   |
| Dell                              | 7         | 0.04%   |
| ASUSTek Computer                  | 7         | 0.04%   |
| Microchip Technology              | 6         | 0.03%   |
| Mercucys                          | 6         | 0.03%   |
| Lenovo                            | 5         | 0.03%   |
| Arduino SA                        | 5         | 0.03%   |
| 3Com                              | 5         | 0.03%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |
| Ericsson Business Mobile Networks | 4         | 0.02%   |
| Attansic Technology               | 4         | 0.02%   |
| AMD                               | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5467      | 26.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1806      | 8.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 851       | 4.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 754       | 3.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 652       | 3.21%   |
| Intel Wi-Fi 6 AX200                                               | 372       | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 328       | 1.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 316       | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 307       | 1.51%   |
| Ralink MT7601U Wireless Adapter                                   | 234       | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 213       | 1.05%   |
| Intel Wi-Fi 6 AX201                                               | 201       | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 178       | 0.88%   |
| Intel Wireless 7265                                               | 172       | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 165       | 0.81%   |
| Nvidia MCP61 Ethernet                                             | 159       | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 153       | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 149       | 0.73%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 140       | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 118       | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 117       | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                   | 116       | 0.57%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 113       | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 112       | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 106       | 0.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 104       | 0.51%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 103       | 0.51%   |
| Intel Wireless 7260                                               | 103       | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 99        | 0.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 98        | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 96        | 0.47%   |
| Intel Wireless 3165                                               | 95        | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.46%   |
| Intel Ethernet Connection (2) I219-V                              | 90        | 0.44%   |
| Ralink RT5370 Wireless Adapter                                    | 85        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 84        | 0.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 83        | 0.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81        | 0.4%    |
| Intel Ethernet Connection (7) I219-V                              | 81        | 0.4%    |
| Intel Wireless 3160                                               | 79        | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3211      | 36.01%  |
| Intel                                 | 2407      | 26.99%  |
| Realtek Semiconductor                 | 1525      | 17.1%   |
| Broadcom                              | 524       | 5.88%   |
| Ralink Technology                     | 416       | 4.66%   |
| Ralink                                | 211       | 2.37%   |
| TP-Link                               | 165       | 1.85%   |
| Qualcomm Atheros Communications       | 131       | 1.47%   |
| Broadcom Limited                      | 103       | 1.15%   |
| D-Link                                | 73        | 0.82%   |
| Microsoft                             | 43        | 0.48%   |
| MediaTek                              | 30        | 0.34%   |
| D-Link System                         | 26        | 0.29%   |
| Edimax Technology                     | 8         | 0.09%   |
| Marvell Technology Group              | 7         | 0.08%   |
| Mercucys                              | 6         | 0.07%   |
| Dell                                  | 4         | 0.04%   |
| NetGear                               | 3         | 0.03%   |
| Micro Star International              | 3         | 0.03%   |
| Encore Electronics                    | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| Linksys                               | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 851       | 9.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 754       | 8.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 652       | 7.26%   |
| Intel Wi-Fi 6 AX200                                                     | 372       | 4.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 328       | 3.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 316       | 3.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 307       | 3.42%   |
| Ralink MT7601U Wireless Adapter                                         | 234       | 2.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 213       | 2.37%   |
| Intel Wi-Fi 6 AX201                                                     | 201       | 2.24%   |
| Intel Wireless 7265                                                     | 172       | 1.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 165       | 1.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 140       | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 118       | 1.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 117       | 1.3%    |
| Qualcomm Atheros AR9271 802.11n                                         | 116       | 1.29%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 113       | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 106       | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 104       | 1.16%   |
| Intel Wireless 7260                                                     | 103       | 1.15%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 99        | 1.1%    |
| Intel Wireless 3165                                                     | 95        | 1.06%   |
| Ralink RT5370 Wireless Adapter                                          | 85        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 83        | 0.92%   |
| Intel Wireless 3160                                                     | 79        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 78        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 78        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 78        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 71        | 0.79%   |
| Realtek 802.11ac NIC                                                    | 70        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 68        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 67        | 0.75%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 65        | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 65        | 0.72%   |
| Intel Centrino Advanced-N 6235                                          | 65        | 0.72%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 64        | 0.71%   |
| Intel Wireless 8265 / 8275                                              | 61        | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 58        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 0.61%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 52        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 7648      | 68.85%  |
| Intel                             | 1079      | 9.71%   |
| Qualcomm Atheros                  | 698       | 6.28%   |
| Broadcom                          | 404       | 3.64%   |
| Marvell Technology Group          | 226       | 2.03%   |
| Nvidia                            | 214       | 1.93%   |
| JMicron Technology                | 214       | 1.93%   |
| Samsung Electronics               | 110       | 0.99%   |
| Silicon Integrated Systems [SiS]  | 100       | 0.9%    |
| Broadcom Limited                  | 89        | 0.8%    |
| VIA Technologies                  | 69        | 0.62%   |
| Xiaomi                            | 49        | 0.44%   |
| Motorola PCS                      | 37        | 0.33%   |
| ASIX Electronics                  | 34        | 0.31%   |
| ICS Advent                        | 18        | 0.16%   |
| TP-Link                           | 14        | 0.13%   |
| D-Link System                     | 13        | 0.12%   |
| DisplayLink                       | 11        | 0.1%    |
| MediaTek                          | 7         | 0.06%   |
| Qualcomm                          | 6         | 0.05%   |
| Microchip Technology              | 5         | 0.05%   |
| LG Electronics                    | 5         | 0.05%   |
| Lenovo                            | 5         | 0.05%   |
| Huawei Technologies               | 5         | 0.05%   |
| ASUSTek Computer                  | 5         | 0.05%   |
| 3Com                              | 5         | 0.05%   |
| Sundance Technology Inc / IC Plus | 4         | 0.04%   |
| Attansic Technology               | 4         | 0.04%   |
| OPPO Electronics                  | 3         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.03%   |
| Apple                             | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| Dell                              | 2         | 0.02%   |
| Aquantia                          | 2         | 0.02%   |
| Accton Technology                 | 2         | 0.02%   |
| Standard Microsystems             | 1         | 0.01%   |
| SK hynix                          | 1         | 0.01%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5467      | 48.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1806      | 16.06%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 178       | 1.58%   |
| Nvidia MCP61 Ethernet                                             | 159       | 1.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 153       | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 149       | 1.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 112       | 1%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 103       | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 98        | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 96        | 0.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 93        | 0.83%   |
| Intel Ethernet Connection (2) I219-V                              | 90        | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 84        | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81        | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 81        | 0.72%   |
| Intel I211 Gigabit Network Connection                             | 79        | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 76        | 0.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 76        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 74        | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 71        | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 69        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 65        | 0.58%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 61        | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 56        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 52        | 0.46%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 48        | 0.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 48        | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 45        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 40        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 39        | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 38        | 0.34%   |
| Motorola PCS moto g pure                                          | 37        | 0.33%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 37        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 36        | 0.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 36        | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 34        | 0.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.28%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 30        | 0.27%   |
| Intel Ethernet Connection (2) I218-V                              | 29        | 0.26%   |
| Intel Ethernet Connection I217-V                                  | 28        | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10716     | 55.34%  |
| WiFi     | 8565      | 44.23%  |
| Modem    | 58        | 0.3%    |
| Unknown  | 24        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 7040      | 58.1%   |
| Ethernet | 5074      | 41.88%  |
| Unknown  | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6787      | 57.86%  |
| 1     | 4488      | 38.26%  |
| 0     | 357       | 3.04%   |
| 3     | 76        | 0.65%   |
| 4     | 17        | 0.14%   |
| 10    | 3         | 0.03%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9299      | 77.56%  |
| Yes  | 2690      | 22.44%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2053      | 34.45%  |
| Qualcomm Atheros Communications | 1550      | 26.01%  |
| Lite-On Technology              | 652       | 10.94%  |
| Cambridge Silicon Radio         | 498       | 8.36%   |
| Realtek Semiconductor           | 234       | 3.93%   |
| Broadcom                        | 226       | 3.79%   |
| IMC Networks                    | 133       | 2.23%   |
| Apple                           | 123       | 2.06%   |
| Foxconn / Hon Hai               | 122       | 2.05%   |
| Dell                            | 78        | 1.31%   |
| Hewlett-Packard                 | 54        | 0.91%   |
| Ralink                          | 48        | 0.81%   |
| Smart Modular Technologies      | 43        | 0.72%   |
| Qcom                            | 27        | 0.45%   |
| ASUSTek Computer                | 22        | 0.37%   |
| Ralink Technology               | 16        | 0.27%   |
| Alps Electric                   | 13        | 0.22%   |
| MediaTek                        | 12        | 0.2%    |
| Foxconn International           | 12        | 0.2%    |
| Integrated System Solution      | 8         | 0.13%   |
| Askey Computer                  | 8         | 0.13%   |
| Micro Star International        | 5         | 0.08%   |
| Toshiba                         | 4         | 0.07%   |
| Opticis                         | 3         | 0.05%   |
| Conwise Technology              | 3         | 0.05%   |
| Unknown                         | 3         | 0.05%   |
| SINO WEALTH                     | 2         | 0.03%   |
| Marvell Semiconductor           | 2         | 0.03%   |
| Actions                         | 2         | 0.03%   |
| Syntek                          | 1         | 0.02%   |
| Realtek                         | 1         | 0.02%   |
| Motorola PCS                    | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 880       | 14.76%  |
| Intel Bluetooth wireless interface                                                  | 678       | 11.37%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 524       | 8.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 498       | 8.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 372       | 6.24%   |
| Intel AX200 Bluetooth                                                               | 360       | 6.04%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 241       | 4.04%   |
| Intel AX201 Bluetooth                                                               | 197       | 3.3%    |
| Realtek Bluetooth Radio                                                             | 172       | 2.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 150       | 2.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 137       | 2.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 124       | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 92        | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 91        | 1.53%   |
| Lite-On Bluetooth Device                                                            | 89        | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 76        | 1.27%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 63        | 1.06%   |
| IMC Networks Bluetooth Radio                                                        | 62        | 1.04%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 59        | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 58        | 0.97%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 57        | 0.96%   |
| Apple Bluetooth Host Controller                                                     | 52        | 0.87%   |
| Ralink RT3290 Bluetooth                                                             | 48        | 0.81%   |
| Smart Modular Bluetooth Device                                                      | 43        | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 38        | 0.64%   |
| Dell Wireless 365 Bluetooth                                                         | 34        | 0.57%   |
| IMC Networks Bluetooth Device                                                       | 32        | 0.54%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 32        | 0.54%   |
| Apple Bluetooth USB Host Controller                                                 | 31        | 0.52%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 30        | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 28        | 0.47%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.4%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 24        | 0.4%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 22        | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 20        | 0.34%   |
| Intel AX210 Bluetooth                                                               | 20        | 0.34%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 19        | 0.32%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 17        | 0.29%   |
| Dell DW375 Bluetooth Module                                                         | 17        | 0.29%   |
| Apple Bluetooth HCI                                                                 | 17        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 9053      | 60.53%  |
| AMD                                             | 2397      | 16.03%  |
| Nvidia                                          | 2312      | 15.46%  |
| C-Media Electronics                             | 246       | 1.64%   |
| Generalplus Technology                          | 120       | 0.8%    |
| Silicon Integrated Systems [SiS]                | 101       | 0.68%   |
| Logitech                                        | 84        | 0.56%   |
| VIA Technologies                                | 75        | 0.5%    |
| JMTek                                           | 67        | 0.45%   |
| Kingston Technology                             | 51        | 0.34%   |
| Texas Instruments                               | 41        | 0.27%   |
| Creative Labs                                   | 37        | 0.25%   |
| Corsair                                         | 29        | 0.19%   |
| Microsoft                                       | 24        | 0.16%   |
| Plantronics                                     | 19        | 0.13%   |
| Licensed by Sony Computer Entertainment America | 16        | 0.11%   |
| GN Netcom                                       | 16        | 0.11%   |
| Tenx Technology                                 | 15        | 0.1%    |
| Razer USA                                       | 15        | 0.1%    |
| BEHRINGER International                         | 14        | 0.09%   |
| Sony                                            | 12        | 0.08%   |
| Realtek Semiconductor                           | 11        | 0.07%   |
| Dell                                            | 9         | 0.06%   |
| M-Audio                                         | 8         | 0.05%   |
| Goldvish                                        | 8         | 0.05%   |
| Focusrite-Novation                              | 8         | 0.05%   |
| SteelSeries ApS                                 | 7         | 0.05%   |
| Samson Technologies                             | 7         | 0.05%   |
| JBL                                             | 7         | 0.05%   |
| BY EDIFIER                                      | 7         | 0.05%   |
| Samsung Electronics                             | 6         | 0.04%   |
| Philips (or NXP)                                | 6         | 0.04%   |
| Fry's Electronics                               | 6         | 0.04%   |
| Creative Technology                             | 6         | 0.04%   |
| Elite Silicon                                   | 5         | 0.03%   |
| Cirrus Logic                                    | 5         | 0.03%   |
| Turtle Beach                                    | 4         | 0.03%   |
| Tdlasunnic                                      | 4         | 0.03%   |
| Meizu                                           | 4         | 0.03%   |
| Lenovo                                          | 4         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1187      | 6.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1148      | 6.61%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1130      | 6.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 684       | 3.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 611       | 3.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 585       | 3.37%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 542       | 3.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 522       | 3%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 411       | 2.36%   |
| Intel 8 Series HD Audio Controller                                                                | 398       | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 394       | 2.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 360       | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 360       | 2.07%   |
| Intel Broadwell-U Audio Controller                                                                | 325       | 1.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 324       | 1.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 319       | 1.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 305       | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 286       | 1.65%   |
| AMD FCH Azalia Controller                                                                         | 257       | 1.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 256       | 1.47%   |
| Nvidia High Definition Audio Controller                                                           | 234       | 1.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 217       | 1.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 214       | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 202       | 1.16%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 202       | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 196       | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 182       | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 178       | 1.02%   |
| Nvidia MCP61 High Definition Audio                                                                | 173       | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 169       | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 161       | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 151       | 0.87%   |
| AMD Wrestler HDMI Audio                                                                           | 148       | 0.85%   |
| Intel 200 Series PCH HD Audio                                                                     | 140       | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 140       | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 139       | 0.8%    |
| Generalplus Technology USB Audio Device                                                           | 120       | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 117       | 0.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 115       | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 110       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 881       | 17.73%  |
| Kingston            | 796       | 16.02%  |
| Smart               | 674       | 13.57%  |
| Samsung Electronics | 461       | 9.28%   |
| SK hynix            | 333       | 6.7%    |
| A-DATA Technology   | 292       | 5.88%   |
| Corsair             | 230       | 4.63%   |
| Teikon              | 174       | 3.5%    |
| Crucial             | 169       | 3.4%    |
| Micron Technology   | 163       | 3.28%   |
| Smart Brazil        | 106       | 2.13%   |
| High Bridge         | 62        | 1.25%   |
| Unknown             | 53        | 1.07%   |
| Elpida              | 51        | 1.03%   |
| Team                | 49        | 0.99%   |
| Multilaser          | 43        | 0.87%   |
| G.Skill             | 37        | 0.74%   |
| Unknown (ABCD)      | 33        | 0.66%   |
| Apacer              | 28        | 0.56%   |
| Patriot             | 27        | 0.54%   |
| Nanya Technology    | 21        | 0.42%   |
| Kllisre             | 17        | 0.34%   |
| Atermiter           | 17        | 0.34%   |
| Avant               | 14        | 0.28%   |
| Ramaxel Technology  | 13        | 0.26%   |
| PUSKILL             | 12        | 0.24%   |
| HT Micron           | 11        | 0.22%   |
| Smart Modular       | 10        | 0.2%    |
| RZX                 | 10        | 0.2%    |
| Kreton              | 10        | 0.2%    |
| HBS                 | 9         | 0.18%   |
| CSX                 | 9         | 0.18%   |
| GeIL                | 8         | 0.16%   |
| Kingmax             | 7         | 0.14%   |
| Unknown (82B5)      | 6         | 0.12%   |
| Positivo            | 6         | 0.12%   |
| Carry               | 6         | 0.12%   |
| Hewlett-Packard     | 5         | 0.1%    |
| GLOWAY              | 5         | 0.1%    |
| Asgard              | 5         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 77        | 1.41%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 54        | 0.99%   |
| Unknown                                                          | 53        | 0.97%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s            | 50        | 0.92%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 46        | 0.84%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 44        | 0.81%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 41        | 0.75%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 41        | 0.75%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 38        | 0.7%    |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 36        | 0.66%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 35        | 0.64%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 33        | 0.61%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 32        | 0.59%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 32        | 0.59%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 32        | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 31        | 0.57%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 31        | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 30        | 0.55%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 30        | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 29        | 0.53%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 27        | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 26        | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.44%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 23        | 0.42%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 22        | 0.4%    |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 21        | 0.39%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 20        | 0.37%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 20        | 0.37%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.37%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 20        | 0.37%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 19        | 0.35%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 19        | 0.35%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 18        | 0.33%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 18        | 0.33%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 18        | 0.33%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.33%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 17        | 0.31%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s              | 17        | 0.31%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s                     | 17        | 0.31%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 16        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 1822      | 43.25%  |
| DDR4         | 1529      | 36.29%  |
| DDR2         | 286       | 6.79%   |
| Unknown      | 195       | 4.63%   |
| SDRAM        | 185       | 4.39%   |
| LPDDR4       | 82        | 1.95%   |
| DDR          | 44        | 1.04%   |
| LPDDR3       | 31        | 0.74%   |
| DRAM         | 19        | 0.45%   |
| DDR5         | 13        | 0.31%   |
| LPDDR5       | 5         | 0.12%   |
| RAM          | 1         | 0.02%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2293      | 54.84%  |
| DIMM         | 1766      | 42.24%  |
| Row Of Chips | 102       | 2.44%   |
| Unknown      | 11        | 0.26%   |
| RIMM         | 4         | 0.1%    |
| FB-DIMM      | 3         | 0.07%   |
| Chip         | 2         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1764      | 37.04%  |
| 8192  | 1359      | 28.54%  |
| 2048  | 969       | 20.35%  |
| 16384 | 408       | 8.57%   |
| 1024  | 159       | 3.34%   |
| 32768 | 83        | 1.74%   |
| 512   | 16        | 0.34%   |
| 256   | 2         | 0.04%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1039      | 22.08%  |
| 1333    | 605       | 12.86%  |
| 2667    | 591       | 12.56%  |
| 2400    | 443       | 9.42%   |
| Unknown | 246       | 5.23%   |
| 3200    | 234       | 4.97%   |
| 1334    | 233       | 4.95%   |
| 800     | 157       | 3.34%   |
| 2133    | 149       | 3.17%   |
| 667     | 142       | 3.02%   |
| 1066    | 72        | 1.53%   |
| 3400    | 69        | 1.47%   |
| 3000    | 62        | 1.32%   |
| 1067    | 62        | 1.32%   |
| 3600    | 57        | 1.21%   |
| 1867    | 52        | 1.11%   |
| 4199    | 40        | 0.85%   |
| 3466    | 36        | 0.77%   |
| 533     | 36        | 0.77%   |
| 4267    | 33        | 0.7%    |
| 1866    | 33        | 0.7%    |
| 2800    | 29        | 0.62%   |
| 3733    | 21        | 0.45%   |
| 2933    | 21        | 0.45%   |
| 975     | 21        | 0.45%   |
| 2048    | 20        | 0.43%   |
| 400     | 20        | 0.43%   |
| 2666    | 19        | 0.4%    |
| 3151    | 17        | 0.36%   |
| 333     | 15        | 0.32%   |
| 3266    | 14        | 0.3%    |
| 3800    | 13        | 0.28%   |
| 4800    | 11        | 0.23%   |
| 3334    | 9         | 0.19%   |
| 8400    | 6         | 0.13%   |
| 3333    | 6         | 0.13%   |
| 6400    | 5         | 0.11%   |
| 1200    | 5         | 0.11%   |
| 41632   | 4         | 0.09%   |
| 5354    | 3         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 113       | 44.66%  |
| Seiko Epson           | 69        | 27.27%  |
| Samsung Electronics   | 22        | 8.7%    |
| Canon                 | 19        | 7.51%   |
| Brother Industries    | 17        | 6.72%   |
| Lexmark International | 3         | 1.19%   |
| QinHeng Electronics   | 2         | 0.79%   |
| Apple                 | 2         | 0.79%   |
| Xerox                 | 1         | 0.4%    |
| Ricoh                 | 1         | 0.4%    |
| Prolific Technology   | 1         | 0.4%    |
| Oki Data              | 1         | 0.4%    |
| MIIIW                 | 1         | 0.4%    |
| ARGOX                 | 1         | 0.4%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 13        | 5.12%   |
| Seiko Epson L396 Series                      | 11        | 4.33%   |
| Seiko Epson L355 Series                      | 9         | 3.54%   |
| HP Ink Tank Wireless 410 series              | 9         | 3.54%   |
| HP DeskJet 2130 series                       | 9         | 3.54%   |
| Seiko Epson L365 Series                      | 7         | 2.76%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.76%   |
| HP DeskJet 2700 series                       | 7         | 2.76%   |
| HP Deskjet 2540 series                       | 7         | 2.76%   |
| HP LaserJet 1020                             | 6         | 2.36%   |
| Canon G3010 series                           | 6         | 2.36%   |
| Samsung SCX-4200 series                      | 5         | 1.97%   |
| HP LaserJet Professional P1102w              | 5         | 1.97%   |
| HP DeskJet F4100 Printer series              | 5         | 1.97%   |
| Samsung M2070 Series                         | 4         | 1.57%   |
| Samsung M2020 Series                         | 4         | 1.57%   |
| HP LaserJet P1005                            | 4         | 1.57%   |
| HP DeskJet F4200 series                      | 4         | 1.57%   |
| HP DeskJet 3630 series                       | 4         | 1.57%   |
| HP DeskJet 2600 series                       | 4         | 1.57%   |
| HP Deskjet 2050 J510                         | 4         | 1.57%   |
| Seiko Epson L220 Series                      | 3         | 1.18%   |
| Seiko Epson L210 Series                      | 3         | 1.18%   |
| HP LaserJet 1018                             | 3         | 1.18%   |
| HP Deskjet F4400 series                      | 3         | 1.18%   |
| Brother HL-1200 series                       | 3         | 1.18%   |
| Seiko Epson XP-243 245 247 Series            | 2         | 0.79%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 2         | 0.79%   |
| Seiko Epson L375 Series                      | 2         | 0.79%   |
| Seiko Epson L3110 Series                     | 2         | 0.79%   |
| Seiko Epson ET-3750 Series                   | 2         | 0.79%   |
| Seiko Epson ET-2700 Series                   | 2         | 0.79%   |
| Samsung SCX-3200 Series                      | 2         | 0.79%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.79%   |
| QinHeng CH340S                               | 2         | 0.79%   |
| HP Printing Support                          | 2         | 0.79%   |
| HP DeskJet D1360                             | 2         | 0.79%   |
| HP Deskjet 4620 series                       | 2         | 0.79%   |
| HP DeskJet 2300 series                       | 2         | 0.79%   |
| HP DeskJet 1110 series                       | 2         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 45%     |
| Hewlett-Packard | 8         | 40%     |
| Seiko Epson     | 2         | 10%     |
| Mustek Systems  | 1         | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 25%     |
| Canon CanoScan LIDE 25                                  | 4         | 20%     |
| Canon CanoScan LiDE 110                                 | 2         | 10%     |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5%      |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 5%      |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 5%      |
| HP ScanJet G4050                                        | 1         | 5%      |
| HP ScanJet 3800c                                        | 1         | 5%      |
| HP Scanjet 200                                          | 1         | 5%      |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5%      |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5%      |
| Canon CanoScan LiDE 210                                 | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1407      | 19.43%  |
| Microdia                               | 814       | 11.24%  |
| Realtek Semiconductor                  | 664       | 9.17%   |
| Quanta                                 | 597       | 8.24%   |
| Silicon Motion                         | 542       | 7.48%   |
| Sunplus Innovation Technology          | 507       | 7%      |
| Acer                                   | 417       | 5.76%   |
| IMC Networks                           | 303       | 4.18%   |
| Suyin                                  | 276       | 3.81%   |
| Logitech                               | 267       | 3.69%   |
| Syntek                                 | 207       | 2.86%   |
| Alcor Micro                            | 146       | 2.02%   |
| Apple                                  | 114       | 1.57%   |
| Samsung Electronics                    | 89        | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) | 82        | 1.13%   |
| Generalplus Technology                 | 63        | 0.87%   |
| Z-Star Microelectronics                | 62        | 0.86%   |
| Microsoft                              | 53        | 0.73%   |
| Ricoh                                  | 49        | 0.68%   |
| Bison Electronics                      | 49        | 0.68%   |
| ALi                                    | 43        | 0.59%   |
| Sonix Technology                       | 32        | 0.44%   |
| Aveo Technology                        | 28        | 0.39%   |
| Lite-On Technology                     | 24        | 0.33%   |
| GEMBIRD                                | 24        | 0.33%   |
| OmniVision Technologies                | 22        | 0.3%    |
| Importek                               | 22        | 0.3%    |
| Unknown                                | 21        | 0.29%   |
| Pixart Imaging                         | 20        | 0.28%   |
| Jieli Technology                       | 20        | 0.28%   |
| SunplusIT                              | 18        | 0.25%   |
| LG Electronics                         | 18        | 0.25%   |
| Cubeternet                             | 17        | 0.23%   |
| Lenovo                                 | 16        | 0.22%   |
| USB Camera                             | 15        | 0.21%   |
| Y Media                                | 13        | 0.18%   |
| Shenzhen Kingcome Optoelectronic       | 10        | 0.14%   |
| Intel                                  | 10        | 0.14%   |
| Genesys Logic                          | 10        | 0.14%   |
| Sunplus Technology                     | 9         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD              | 303       | 4.18%   |
| Microdia Integrated_Webcam_HD             | 302       | 4.16%   |
| Quanta HD User Facing                     | 255       | 3.51%   |
| Chicony HD WebCam                         | 250       | 3.45%   |
| Chicony HD User Facing                    | 209       | 2.88%   |
| Sunplus Integrated_Webcam_HD              | 196       | 2.7%    |
| Silicon Motion Web Camera                 | 196       | 2.7%    |
| Quanta VGA WebCam                         | 192       | 2.65%   |
| Chicony Integrated Camera                 | 147       | 2.03%   |
| Chicony VGA WebCam                        | 137       | 1.89%   |
| Syntek Integrated Camera                  | 116       | 1.6%    |
| Realtek Integrated Webcam                 | 104       | 1.43%   |
| Sunplus HD WebCam                         | 103       | 1.42%   |
| Logitech Webcam C270                      | 101       | 1.39%   |
| Chicony USB 2.0 Camera                    | 94        | 1.3%    |
| Alcor Micro USB 2.0 Camera                | 91        | 1.25%   |
| Samsung Galaxy A5 (MTP)                   | 88        | 1.21%   |
| Quanta HD Webcam                          | 86        | 1.19%   |
| Microdia Laptop_Integrated_Webcam_HD      | 83        | 1.14%   |
| Acer BisonCam, NB Pro                     | 73        | 1.01%   |
| Acer EasyCamera                           | 66        | 0.91%   |
| Acer Lenovo EasyCamera                    | 64        | 0.88%   |
| Microdia Dell Laptop Integrated Webcam HD | 55        | 0.76%   |
| Logitech HD Pro Webcam C920               | 55        | 0.76%   |
| IMC Networks Integrated Camera            | 53        | 0.73%   |
| Silicon Motion WebCam SC-10HDD12636N      | 50        | 0.69%   |
| Microdia Integrated Webcam HD             | 49        | 0.68%   |
| Generalplus GENERAL WEBCAM                | 48        | 0.66%   |
| Realtek USB Camera                        | 47        | 0.65%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 45        | 0.62%   |
| Acer VGA WebCam                           | 44        | 0.61%   |
| Chicony EasyCamera                        | 42        | 0.58%   |
| Silicon Motion WebCam SCB-1100N           | 41        | 0.57%   |
| Realtek HD WebCam                         | 41        | 0.57%   |
| Silicon Motion WebCam SC-13HDL11939N      | 39        | 0.54%   |
| Acer HD Webcam                            | 39        | 0.54%   |
| Syntek EasyCamera                         | 38        | 0.52%   |
| Suyin Integrated_Webcam_HD                | 38        | 0.52%   |
| Silicon Motion WebCam SC-0311139N         | 38        | 0.52%   |
| IMC Networks USB2.0 HD UVC WebCam         | 38        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 283       | 47.64%  |
| Synaptics                  | 69        | 11.62%  |
| Shenzhen Goodix Technology | 63        | 10.61%  |
| AuthenTec                  | 58        | 9.76%   |
| Upek                       | 54        | 9.09%   |
| LighTuning Technology      | 30        | 5.05%   |
| Samsung Electronics        | 17        | 2.86%   |
| Elan Microelectronics      | 8         | 1.35%   |
| STMicroelectronics         | 4         | 0.67%   |
| Futronic Technology        | 2         | 0.34%   |
| Focal-systems.Corp         | 2         | 0.34%   |
| Dell                       | 2         | 0.34%   |
| Next Biometrics            | 1         | 0.17%   |
| DigitalPersona             | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 109       | 18.35%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 46        | 7.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 42        | 7.07%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 4.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 4.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 25        | 4.21%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 24        | 4.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 3.87%   |
| Validity Sensors Fingerprint scanner                                       | 21        | 3.54%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 18        | 3.03%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 3.03%   |
| Samsung Fingerprint Device                                                 | 17        | 2.86%   |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 2.69%   |
| Synaptics  WBDI                                                            | 15        | 2.53%   |
| AuthenTec AES2810                                                          | 14        | 2.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 2.36%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 2.02%   |
| Validity Sensors VFS491                                                    | 11        | 1.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 1.85%   |
| AuthenTec Fingerprint Sensor                                               | 10        | 1.68%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 8         | 1.35%   |
| Elan ELAN:Fingerprint                                                      | 8         | 1.35%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.18%   |
| Upek TCS5B Fingerprint sensor                                              | 7         | 1.18%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.18%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.01%   |
| Synaptics WBDI                                                             | 5         | 0.84%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.84%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 0.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.51%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.34%   |
| Futronic FS81 Fingerprint Scanner Module                                   | 2         | 0.34%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.34%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 2         | 0.34%   |
| AuthenTec AES1600                                                          | 2         | 0.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 81        | 43.55%  |
| Alcor Micro                       | 27        | 14.52%  |
| Gemalto (was Gemplus)             | 15        | 8.06%   |
| Lenovo                            | 13        | 6.99%   |
| Giesecke & Devrient               | 11        | 5.91%   |
| Upek                              | 10        | 5.38%   |
| Watchdata                         | 7         | 3.76%   |
| Aladdin Knowledge Systems         | 6         | 3.23%   |
| SCM Microsystems                  | 4         | 2.15%   |
| OmniKey                           | 3         | 1.61%   |
| O2 Micro                          | 3         | 1.61%   |
| Chicony Electronics               | 3         | 1.61%   |
| VASCO Data Security International | 1         | 0.54%   |
| Realtek Semiconductor             | 1         | 0.54%   |
| Advanced Card Systems             | 1         | 0.54%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 14.52%  |
| Broadcom 58200                                                               | 22        | 11.83%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 11.29%  |
| Broadcom 5880                                                                | 20        | 10.75%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 18        | 9.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 14        | 7.53%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 6.99%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 5.38%   |
| Watchdata USB Key                                                            | 7         | 3.76%   |
| Giesecke & Devrient StarSign CUT                                             | 6         | 3.23%   |
| Aladdin Knowledge Systems Token JC                                           | 6         | 3.23%   |
| Giesecke & Devrient StarSign CUT S                                           | 5         | 2.69%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.61%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 1.08%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.08%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.08%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.08%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.54%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.54%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.54%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.54%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.54%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.54%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 9406      | 79.12%  |
| 1     | 2157      | 18.14%  |
| 2     | 265       | 2.23%   |
| 3     | 34        | 0.29%   |
| 4     | 17        | 0.14%   |
| 7     | 4         | 0.03%   |
| 5     | 3         | 0.03%   |
| 8     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 900       | 32.26%  |
| Fingerprint reader       | 590       | 21.15%  |
| Net/wireless             | 358       | 12.83%  |
| Multimedia controller    | 244       | 8.75%   |
| Chipcard                 | 157       | 5.63%   |
| Communication controller | 104       | 3.73%   |
| Bluetooth                | 86        | 3.08%   |
| Camera                   | 73        | 2.62%   |
| Sound                    | 59        | 2.11%   |
| Unassigned class         | 53        | 1.9%    |
| Storage                  | 42        | 1.51%   |
| Net/ethernet             | 34        | 1.22%   |
| Modem                    | 24        | 0.86%   |
| Flash memory             | 21        | 0.75%   |
| Card reader              | 14        | 0.5%    |
| Network                  | 9         | 0.32%   |
| Storage/ide              | 7         | 0.25%   |
| Firewire controller      | 5         | 0.18%   |
| Storage/raid             | 4         | 0.14%   |
| Storage/nvme             | 2         | 0.07%   |
| Wireless                 | 1         | 0.04%   |
| Video                    | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |


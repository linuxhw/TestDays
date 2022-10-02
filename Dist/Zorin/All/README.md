Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 5572

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | V570 1066EDG                | Notebook    | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | Desktop     | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Dell          | Inspiron 1200               | Notebook    | [becf544fa6](https://linux-hardware.org/?probe=becf544fa6) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [1a331f2583](https://linux-hardware.org/?probe=1a331f2583) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | Notebook    | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | 8055                        | Desktop     | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| Dell          | Inspiron 1200               | Notebook    | [32dd972d77](https://linux-hardware.org/?probe=32dd972d77) | Sep 29, 2022 |
| HP            | 843C                        | Desktop     | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | Notebook    | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Apple         | Mac-F4208EC8 PVT            | Mini pc     | [62d808a3e5](https://linux-hardware.org/?probe=62d808a3e5) | Sep 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3052bded51](https://linux-hardware.org/?probe=3052bded51) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | Desktop     | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c9e87b7962](https://linux-hardware.org/?probe=c9e87b7962) | Sep 26, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fa3be9d376](https://linux-hardware.org/?probe=fa3be9d376) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Gateway       | FMCP7AM                     | Desktop     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | Notebook    | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [ade183eadc](https://linux-hardware.org/?probe=ade183eadc) | Sep 24, 2022 |
| HP            | 18E7                        | Desktop     | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fab0eac5a6](https://linux-hardware.org/?probe=fab0eac5a6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [9ccc1b86a7](https://linux-hardware.org/?probe=9ccc1b86a7) | Sep 23, 2022 |
| ASRock        | B85M Pro4                   | Desktop     | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| HP            | 8055                        | Desktop     | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [00e679e86c](https://linux-hardware.org/?probe=00e679e86c) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [318436c7ab](https://linux-hardware.org/?probe=318436c7ab) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [a2fb3b0ed7](https://linux-hardware.org/?probe=a2fb3b0ed7) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [4421e54d32](https://linux-hardware.org/?probe=4421e54d32) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Alienware     | 18                          | Notebook    | [91d0153265](https://linux-hardware.org/?probe=91d0153265) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| MSI           | MS-7260                     | Desktop     | [52d2fa8c71](https://linux-hardware.org/?probe=52d2fa8c71) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Dell          | Latitude D610               | Notebook    | [47e0f0fa27](https://linux-hardware.org/?probe=47e0f0fa27) | Sep 19, 2022 |
| Dell          | Latitude D610               | Notebook    | [35f0ea4fc8](https://linux-hardware.org/?probe=35f0ea4fc8) | Sep 19, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [493f68c9d6](https://linux-hardware.org/?probe=493f68c9d6) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Lenovo        | ThinkPad 11e 20DAS09U00     | Notebook    | [81bd748796](https://linux-hardware.org/?probe=81bd748796) | Sep 19, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Dell          | Latitude E6540              | Notebook    | [7bf393c147](https://linux-hardware.org/?probe=7bf393c147) | Sep 19, 2022 |
| Alienware     | 18                          | Notebook    | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | Notebook    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| Dell          | Latitude D610               | Notebook    | [f383e5d7ae](https://linux-hardware.org/?probe=f383e5d7ae) | Sep 18, 2022 |
| HP            | 0AA8h                       | Desktop     | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| HP            | 0AA8h                       | Desktop     | [5e6f953759](https://linux-hardware.org/?probe=5e6f953759) | Sep 18, 2022 |
| Ematic        | EWT118                      | Notebook    | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
| Dell          | Latitude D610               | Notebook    | [df13ed7396](https://linux-hardware.org/?probe=df13ed7396) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | Desktop     | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [5620510083](https://linux-hardware.org/?probe=5620510083) | Sep 16, 2022 |
| Dell          | Latitude E4300              | Notebook    | [b3c04d8a81](https://linux-hardware.org/?probe=b3c04d8a81) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [258c624b3b](https://linux-hardware.org/?probe=258c624b3b) | Sep 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [3ff6899749](https://linux-hardware.org/?probe=3ff6899749) | Sep 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [437d152a42](https://linux-hardware.org/?probe=437d152a42) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [199f191441](https://linux-hardware.org/?probe=199f191441) | Sep 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3c13816886](https://linux-hardware.org/?probe=3c13816886) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [25c2b764a6](https://linux-hardware.org/?probe=25c2b764a6) | Sep 12, 2022 |
| HP            | 0AA8h                       | Desktop     | [fc09b092c1](https://linux-hardware.org/?probe=fc09b092c1) | Sep 11, 2022 |
| HP            | Stream Notebook PC 14       | Notebook    | [4618d27b09](https://linux-hardware.org/?probe=4618d27b09) | Sep 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| Gigabyte      | P64V7                       | Notebook    | [b9d2c998be](https://linux-hardware.org/?probe=b9d2c998be) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| HP            | Pavilion dv6000 (RP986EA... | Notebook    | [f20de20683](https://linux-hardware.org/?probe=f20de20683) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [4c6d525103](https://linux-hardware.org/?probe=4c6d525103) | Sep 11, 2022 |
| ECS           | Iris8                       | Desktop     | [dcfb9e172d](https://linux-hardware.org/?probe=dcfb9e172d) | Sep 11, 2022 |
| HP            | 0A54h                       | Desktop     | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e6bf2b7f3f](https://linux-hardware.org/?probe=e6bf2b7f3f) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | Desktop     | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| MSI           | 2AE0                        | Desktop     | [df247fd9d0](https://linux-hardware.org/?probe=df247fd9d0) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| ECS           | Iris8                       | Desktop     | [29bc0560b4](https://linux-hardware.org/?probe=29bc0560b4) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| HP            | 0AA8h                       | Desktop     | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [678759289b](https://linux-hardware.org/?probe=678759289b) | Sep 09, 2022 |
| Acer          | Aspire C22-820              | All in one  | [7b21589632](https://linux-hardware.org/?probe=7b21589632) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | Notebook    | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | Notebook    | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| HP            | 15                          | Notebook    | [c02361a2ff](https://linux-hardware.org/?probe=c02361a2ff) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | Desktop     | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [5ed29a7629](https://linux-hardware.org/?probe=5ed29a7629) | Sep 05, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [88c4e0664a](https://linux-hardware.org/?probe=88c4e0664a) | Sep 05, 2022 |
| HP            | G62                         | Notebook    | [a3f84f3bf8](https://linux-hardware.org/?probe=a3f84f3bf8) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [eec792ef79](https://linux-hardware.org/?probe=eec792ef79) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [0751d35153](https://linux-hardware.org/?probe=0751d35153) | Sep 04, 2022 |
| ASRock        | B550M/ac                    | Desktop     | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | Desktop     | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [079d33f9b2](https://linux-hardware.org/?probe=079d33f9b2) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [c74752a0d2](https://linux-hardware.org/?probe=c74752a0d2) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [8b36704183](https://linux-hardware.org/?probe=8b36704183) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [1bfbfd28f4](https://linux-hardware.org/?probe=1bfbfd28f4) | Sep 02, 2022 |
| MSI           | MS-B9201                    | Desktop     | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | Desktop     | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [2eb780855d](https://linux-hardware.org/?probe=2eb780855d) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [a5e4d22ccd](https://linux-hardware.org/?probe=a5e4d22ccd) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | Desktop     | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [8e2cd928f3](https://linux-hardware.org/?probe=8e2cd928f3) | Aug 31, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [836644c18b](https://linux-hardware.org/?probe=836644c18b) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | Desktop     | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | Desktop     | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| HP            | ProBook 6470b               | Notebook    | [2cbe458c94](https://linux-hardware.org/?probe=2cbe458c94) | Aug 30, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [436d2b29aa](https://linux-hardware.org/?probe=436d2b29aa) | Aug 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a96a893eac](https://linux-hardware.org/?probe=a96a893eac) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| Ematic        | EWT118                      | Notebook    | [3fa43d450e](https://linux-hardware.org/?probe=3fa43d450e) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | Notebook    | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [be30fd63a0](https://linux-hardware.org/?probe=be30fd63a0) | Aug 29, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [135f83007e](https://linux-hardware.org/?probe=135f83007e) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0d92d186f](https://linux-hardware.org/?probe=b0d92d186f) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | Notebook    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| HP            | 339A                        | Desktop     | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [148c6dd35a](https://linux-hardware.org/?probe=148c6dd35a) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [be59676867](https://linux-hardware.org/?probe=be59676867) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | Desktop     | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [04aec7a28a](https://linux-hardware.org/?probe=04aec7a28a) | Aug 28, 2022 |
| Google        | Butterfly                   | Notebook    | [df8fafaf3b](https://linux-hardware.org/?probe=df8fafaf3b) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| GHIA          | 2 en 1                      | Tablet      | [5ed07e6854](https://linux-hardware.org/?probe=5ed07e6854) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [5b80fb349f](https://linux-hardware.org/?probe=5b80fb349f) | Aug 26, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7c9f388153](https://linux-hardware.org/?probe=7c9f388153) | Aug 26, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [c6fc39489e](https://linux-hardware.org/?probe=c6fc39489e) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [5d03f69f35](https://linux-hardware.org/?probe=5d03f69f35) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | Desktop     | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [73de62c6c7](https://linux-hardware.org/?probe=73de62c6c7) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| MSI           | 2AE0                        | Desktop     | [beb918fbc9](https://linux-hardware.org/?probe=beb918fbc9) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| HP            | 2AF7                        | Desktop     | [29826a67d9](https://linux-hardware.org/?probe=29826a67d9) | Aug 22, 2022 |
| HP            | 2AF7                        | Desktop     | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | Desktop     | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [e7f6559a38](https://linux-hardware.org/?probe=e7f6559a38) | Aug 21, 2022 |
| Dell          | 0C27VV A03                  | Desktop     | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [a8bf4ad2a0](https://linux-hardware.org/?probe=a8bf4ad2a0) | Aug 21, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Alienware     | 15 R3                       | Notebook    | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Positivo      | C14CU51                     | Notebook    | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | Notebook    | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| GPU Compan... | GWTN156-11                  | Notebook    | [c22aa4377d](https://linux-hardware.org/?probe=c22aa4377d) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| MSI           | MS-AE611 100                | All in one  | [336e0dfd12](https://linux-hardware.org/?probe=336e0dfd12) | Aug 18, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [ffb9dcb065](https://linux-hardware.org/?probe=ffb9dcb065) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [a37b0b7e18](https://linux-hardware.org/?probe=a37b0b7e18) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | 14                          | Notebook    | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| ASUSTek       | K54C                        | Notebook    | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1074f0ba0d](https://linux-hardware.org/?probe=1074f0ba0d) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | Desktop     | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| MSI           | MS-AE611 100                | All in one  | [702827bd22](https://linux-hardware.org/?probe=702827bd22) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | Desktop     | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [7267931d03](https://linux-hardware.org/?probe=7267931d03) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b3e408ce95](https://linux-hardware.org/?probe=b3e408ce95) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [1fe351cfab](https://linux-hardware.org/?probe=1fe351cfab) | Aug 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [ddeddb54bf](https://linux-hardware.org/?probe=ddeddb54bf) | Aug 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b19949df5a](https://linux-hardware.org/?probe=b19949df5a) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| HP            | Pavilion 15                 | Notebook    | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |
| Google        | Kasumi                      | Notebook    | [0d1ce61572](https://linux-hardware.org/?probe=0d1ce61572) | Aug 11, 2022 |
| Google        | Kasumi                      | Notebook    | [47ebd6bcac](https://linux-hardware.org/?probe=47ebd6bcac) | Aug 11, 2022 |
| Dell          | Latitude D630               | Notebook    | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4e54f20c67](https://linux-hardware.org/?probe=4e54f20c67) | Aug 10, 2022 |
| IP3 Tech      | AB1                         | Mini pc     | [1db65c598c](https://linux-hardware.org/?probe=1db65c598c) | Aug 10, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [889eb9531f](https://linux-hardware.org/?probe=889eb9531f) | Aug 10, 2022 |
| MSI           | MS-AE611 100                | All in one  | [94bcb206d3](https://linux-hardware.org/?probe=94bcb206d3) | Aug 10, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [af03bf80b5](https://linux-hardware.org/?probe=af03bf80b5) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [a40ad10b4c](https://linux-hardware.org/?probe=a40ad10b4c) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [9071c341a9](https://linux-hardware.org/?probe=9071c341a9) | Aug 10, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [bee60f5725](https://linux-hardware.org/?probe=bee60f5725) | Aug 09, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [7005dd1f5f](https://linux-hardware.org/?probe=7005dd1f5f) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [4c372a442f](https://linux-hardware.org/?probe=4c372a442f) | Aug 09, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| HP            | 1589                        | Desktop     | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0e2f35ef5e](https://linux-hardware.org/?probe=0e2f35ef5e) | Aug 08, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [69430d4693](https://linux-hardware.org/?probe=69430d4693) | Aug 08, 2022 |
| HP            | 18E7                        | Desktop     | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | Desktop     | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [a90c14a429](https://linux-hardware.org/?probe=a90c14a429) | Aug 07, 2022 |
| AMI           | Unknown                     | Notebook    | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| MSI           | CR620                       | Notebook    | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| MP            | MS-7848                     | Desktop     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | Desktop     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | Desktop     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| Ematic        | EWT118                      | Notebook    | [a5362d970a](https://linux-hardware.org/?probe=a5362d970a) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | Notebook    | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Medion        | E7419 MD60990               | Notebook    | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| ASUSTek       | PN51-E1                     | Mini pc     | [d345f9ab52](https://linux-hardware.org/?probe=d345f9ab52) | Aug 04, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2fd7410925](https://linux-hardware.org/?probe=2fd7410925) | Aug 04, 2022 |
| Acer          | Peppy                       | Notebook    | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [db66e72de8](https://linux-hardware.org/?probe=db66e72de8) | Aug 04, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [6e5ce364b3](https://linux-hardware.org/?probe=6e5ce364b3) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [87bf7fcb48](https://linux-hardware.org/?probe=87bf7fcb48) | Aug 03, 2022 |
| LORD ELECT... | GM965 Series                | Desktop     | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | Desktop     | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d1ca5eafe5](https://linux-hardware.org/?probe=d1ca5eafe5) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| HP            | Notebook                    | Notebook    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| MSI           | Boston                      | Desktop     | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| Toshiba       | Satellite P205              | Notebook    | [8ed745a2dc](https://linux-hardware.org/?probe=8ed745a2dc) | Aug 03, 2022 |
| Acer          | Spin SP513-55N              | Convertible | [295df2a1d7](https://linux-hardware.org/?probe=295df2a1d7) | Aug 03, 2022 |
| Dell          | G15 5510                    | Notebook    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | ThinkPad T420 4236VTQ       | Notebook    | [1ea6046182](https://linux-hardware.org/?probe=1ea6046182) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [b4bee86632](https://linux-hardware.org/?probe=b4bee86632) | Aug 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cc8b9aa8f6](https://linux-hardware.org/?probe=cc8b9aa8f6) | Aug 01, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [405a75cb1d](https://linux-hardware.org/?probe=405a75cb1d) | Aug 01, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7c68dbe47e](https://linux-hardware.org/?probe=7c68dbe47e) | Aug 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6532751d00](https://linux-hardware.org/?probe=6532751d00) | Aug 01, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [a954bc2f31](https://linux-hardware.org/?probe=a954bc2f31) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| HP            | 82F2                        | Desktop     | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| HP            | Compaq 6730s                | Notebook    | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| HP            | 550                         | Notebook    | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [15508d1eff](https://linux-hardware.org/?probe=15508d1eff) | Jul 30, 2022 |
| Dell          | Latitude E7450              | Notebook    | [894a489a03](https://linux-hardware.org/?probe=894a489a03) | Jul 30, 2022 |
| Dell          | Latitude E7450              | Notebook    | [268b4ca289](https://linux-hardware.org/?probe=268b4ca289) | Jul 30, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f50872e350](https://linux-hardware.org/?probe=f50872e350) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [55e1536ab6](https://linux-hardware.org/?probe=55e1536ab6) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [ceb521429a](https://linux-hardware.org/?probe=ceb521429a) | Jul 29, 2022 |
| Packard Be... | H57M01                      | Desktop     | [4789405230](https://linux-hardware.org/?probe=4789405230) | Jul 29, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [6d95a05ee7](https://linux-hardware.org/?probe=6d95a05ee7) | Jul 28, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| Dell          | Latitude E7450              | Notebook    | [4a277d4cee](https://linux-hardware.org/?probe=4a277d4cee) | Jul 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f9b0fe48d6](https://linux-hardware.org/?probe=f9b0fe48d6) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [e33f8c0a93](https://linux-hardware.org/?probe=e33f8c0a93) | Jul 26, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [a059cf305d](https://linux-hardware.org/?probe=a059cf305d) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [99c0ca0d0b](https://linux-hardware.org/?probe=99c0ca0d0b) | Jul 25, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [e39f15a1b5](https://linux-hardware.org/?probe=e39f15a1b5) | Jul 25, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [96d6480781](https://linux-hardware.org/?probe=96d6480781) | Jul 25, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [c8e578f98f](https://linux-hardware.org/?probe=c8e578f98f) | Jul 24, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [48e39039fc](https://linux-hardware.org/?probe=48e39039fc) | Jul 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [ff4dba6b3e](https://linux-hardware.org/?probe=ff4dba6b3e) | Jul 24, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [d06c0db3ce](https://linux-hardware.org/?probe=d06c0db3ce) | Jul 24, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [aa952e11aa](https://linux-hardware.org/?probe=aa952e11aa) | Jul 24, 2022 |
| HP            | Unknown                     | Notebook    | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| HP            | Stream Notebook             | Notebook    | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [177a181771](https://linux-hardware.org/?probe=177a181771) | Jul 23, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [722f3df811](https://linux-hardware.org/?probe=722f3df811) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [f5d81fb635](https://linux-hardware.org/?probe=f5d81fb635) | Jul 23, 2022 |
| Dell          | 0FDY5C A00                  | Desktop     | [83cf5f7085](https://linux-hardware.org/?probe=83cf5f7085) | Jul 23, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1512e3bf4d](https://linux-hardware.org/?probe=1512e3bf4d) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [f1af5f5e45](https://linux-hardware.org/?probe=f1af5f5e45) | Jul 22, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| Gigabyte      | M68M-S2P                    | Desktop     | [7d4ba4168a](https://linux-hardware.org/?probe=7d4ba4168a) | Jul 22, 2022 |
| HP            | ProBook 4540s               | Notebook    | [a2d1e2fd68](https://linux-hardware.org/?probe=a2d1e2fd68) | Jul 22, 2022 |
| HP            | Compaq 420                  | Notebook    | [913795a620](https://linux-hardware.org/?probe=913795a620) | Jul 21, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [84f435a6d0](https://linux-hardware.org/?probe=84f435a6d0) | Jul 21, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [711546ab63](https://linux-hardware.org/?probe=711546ab63) | Jul 21, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [cb0f9c95d2](https://linux-hardware.org/?probe=cb0f9c95d2) | Jul 20, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [e332607406](https://linux-hardware.org/?probe=e332607406) | Jul 19, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [89af63cf6f](https://linux-hardware.org/?probe=89af63cf6f) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Google        | Butterfly                   | Notebook    | [ed6aa75ba5](https://linux-hardware.org/?probe=ed6aa75ba5) | Jul 19, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [82966b0f63](https://linux-hardware.org/?probe=82966b0f63) | Jul 18, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4a5f294565](https://linux-hardware.org/?probe=4a5f294565) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | Notebook    | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [c6888145e7](https://linux-hardware.org/?probe=c6888145e7) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ac616e6f37](https://linux-hardware.org/?probe=ac616e6f37) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| Dell          | MXG061                      | Notebook    | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Acer          | NC-A315-41G-R88F            | Notebook    | [8ffe1077fd](https://linux-hardware.org/?probe=8ffe1077fd) | Jul 17, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [08446807d6](https://linux-hardware.org/?probe=08446807d6) | Jul 17, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [75a19b4509](https://linux-hardware.org/?probe=75a19b4509) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| HP            | ENVY 17                     | Notebook    | [bc1e8b41a5](https://linux-hardware.org/?probe=bc1e8b41a5) | Jul 17, 2022 |
| MSI           | CR620                       | Notebook    | [68a2718dd2](https://linux-hardware.org/?probe=68a2718dd2) | Jul 17, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c47ecbd03f](https://linux-hardware.org/?probe=c47ecbd03f) | Jul 16, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [0cf64c41f0](https://linux-hardware.org/?probe=0cf64c41f0) | Jul 16, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [84cd652e24](https://linux-hardware.org/?probe=84cd652e24) | Jul 16, 2022 |
| ASUSTek       | X751MA                      | Notebook    | [e8c8c0d6ec](https://linux-hardware.org/?probe=e8c8c0d6ec) | Jul 16, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [e5fed36e22](https://linux-hardware.org/?probe=e5fed36e22) | Jul 15, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [26ed071525](https://linux-hardware.org/?probe=26ed071525) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [56bd2a162b](https://linux-hardware.org/?probe=56bd2a162b) | Jul 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ccc3bc2a39](https://linux-hardware.org/?probe=ccc3bc2a39) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | Notebook    | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [f244f6157b](https://linux-hardware.org/?probe=f244f6157b) | Jul 15, 2022 |
| AMI           | Unknown                     | Notebook    | [2d15648f33](https://linux-hardware.org/?probe=2d15648f33) | Jul 14, 2022 |
| Alienware     | x15 R1                      | Notebook    | [95ee5b34a7](https://linux-hardware.org/?probe=95ee5b34a7) | Jul 14, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| HP            | Unknown                     | Notebook    | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [66efd060ca](https://linux-hardware.org/?probe=66efd060ca) | Jul 14, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [a0dd163643](https://linux-hardware.org/?probe=a0dd163643) | Jul 14, 2022 |
| Unknown       | Intel X79                   | Desktop     | [b0bb64b9ea](https://linux-hardware.org/?probe=b0bb64b9ea) | Jul 13, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [09e66aef7e](https://linux-hardware.org/?probe=09e66aef7e) | Jul 13, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [27ab632ec8](https://linux-hardware.org/?probe=27ab632ec8) | Jul 13, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [5056c4f640](https://linux-hardware.org/?probe=5056c4f640) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | Notebook    | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| Star Labs     | StarBook                    | Notebook    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [2d990d7afe](https://linux-hardware.org/?probe=2d990d7afe) | Jul 12, 2022 |
| HP            | 3398                        | Desktop     | [1b964004d9](https://linux-hardware.org/?probe=1b964004d9) | Jul 12, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e974774285](https://linux-hardware.org/?probe=e974774285) | Jul 12, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| ASUSTek       | V-P8H61E                    | Desktop     | [f8e5b72d1c](https://linux-hardware.org/?probe=f8e5b72d1c) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [42b248f049](https://linux-hardware.org/?probe=42b248f049) | Jul 11, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [d234e8543d](https://linux-hardware.org/?probe=d234e8543d) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [bc5945b570](https://linux-hardware.org/?probe=bc5945b570) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [f25593cec7](https://linux-hardware.org/?probe=f25593cec7) | Jul 11, 2022 |
| Lenovo        | ThinkCentre M91 7516AD1     | Desktop     | [19660ae71a](https://linux-hardware.org/?probe=19660ae71a) | Jul 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6d6b4c9d06](https://linux-hardware.org/?probe=6d6b4c9d06) | Jul 11, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [845bdfd72c](https://linux-hardware.org/?probe=845bdfd72c) | Jul 11, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [0d90a39160](https://linux-hardware.org/?probe=0d90a39160) | Jul 10, 2022 |
| MSI           | Creator 15 A10SET           | Notebook    | [d90f2aec1b](https://linux-hardware.org/?probe=d90f2aec1b) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [36252f70d6](https://linux-hardware.org/?probe=36252f70d6) | Jul 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [e3197762a9](https://linux-hardware.org/?probe=e3197762a9) | Jul 10, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8a02619147](https://linux-hardware.org/?probe=8a02619147) | Jul 10, 2022 |
| eMachines     | E720 V1.06                  | Notebook    | [ec23637bd5](https://linux-hardware.org/?probe=ec23637bd5) | Jul 09, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| Pegatron      | Benicia                     | Desktop     | [2360476ad3](https://linux-hardware.org/?probe=2360476ad3) | Jul 09, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [42335e5c5c](https://linux-hardware.org/?probe=42335e5c5c) | Jul 09, 2022 |
| HP            | Pavilion 15                 | Notebook    | [1fbb699502](https://linux-hardware.org/?probe=1fbb699502) | Jul 09, 2022 |
| Dell          | Latitude 5400               | Notebook    | [46ce7cf7fe](https://linux-hardware.org/?probe=46ce7cf7fe) | Jul 09, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c74f3711f3](https://linux-hardware.org/?probe=c74f3711f3) | Jul 09, 2022 |
| Fujitsu Si... | AMILO L Series              | Notebook    | [410cd1aeec](https://linux-hardware.org/?probe=410cd1aeec) | Jul 08, 2022 |
| Sony          | VGN-Z31XN_B                 | Notebook    | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Lenovo        | ThinkPad T400 2768GB4       | Notebook    | [498bb4a509](https://linux-hardware.org/?probe=498bb4a509) | Jul 08, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [37aff6bb24](https://linux-hardware.org/?probe=37aff6bb24) | Jul 08, 2022 |
| HP            | 18E4                        | Desktop     | [bf615fe0ae](https://linux-hardware.org/?probe=bf615fe0ae) | Jul 08, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [b7ed1ecdf2](https://linux-hardware.org/?probe=b7ed1ecdf2) | Jul 08, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [159ebeaa5e](https://linux-hardware.org/?probe=159ebeaa5e) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [f11f4826ba](https://linux-hardware.org/?probe=f11f4826ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [50e02d8554](https://linux-hardware.org/?probe=50e02d8554) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | Notebook    | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [9118f548bb](https://linux-hardware.org/?probe=9118f548bb) | Jul 08, 2022 |
| ASUSTek       | K70IC                       | Notebook    | [baa2ddeb5a](https://linux-hardware.org/?probe=baa2ddeb5a) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| Acer          | Spin SP513-55N              | Convertible | [bd077334f0](https://linux-hardware.org/?probe=bd077334f0) | Jul 07, 2022 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [830b5c1c8d](https://linux-hardware.org/?probe=830b5c1c8d) | Jul 07, 2022 |
| HP            | Mini 110-3100               | Notebook    | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Samsung       | 550XDA                      | Notebook    | [74bcded10f](https://linux-hardware.org/?probe=74bcded10f) | Jul 06, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [0dcb64ed5f](https://linux-hardware.org/?probe=0dcb64ed5f) | Jul 06, 2022 |
| Acer          | E91M                        | Desktop     | [4e55aacdd7](https://linux-hardware.org/?probe=4e55aacdd7) | Jul 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [167fe0c2d1](https://linux-hardware.org/?probe=167fe0c2d1) | Jul 06, 2022 |
| MSI           | Boston                      | Desktop     | [3dfcd01115](https://linux-hardware.org/?probe=3dfcd01115) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [59923a9781](https://linux-hardware.org/?probe=59923a9781) | Jul 06, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | Notebook    | [17607e5f03](https://linux-hardware.org/?probe=17607e5f03) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [b8e2b7b6bd](https://linux-hardware.org/?probe=b8e2b7b6bd) | Jul 05, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [dc12f11117](https://linux-hardware.org/?probe=dc12f11117) | Jul 05, 2022 |
| Biostar       | P4M90-M7A Ver:1.0           | Desktop     | [0567d5e337](https://linux-hardware.org/?probe=0567d5e337) | Jul 05, 2022 |
| HP            | ProBook 6475b               | Notebook    | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| Packard Be... | H17HV                       | Notebook    | [8b05e7f955](https://linux-hardware.org/?probe=8b05e7f955) | Jul 04, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| Deffad        | Unknown                     | Notebook    | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e20dba9308](https://linux-hardware.org/?probe=e20dba9308) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [b847a4a45d](https://linux-hardware.org/?probe=b847a4a45d) | Jul 03, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [0aa196cd0c](https://linux-hardware.org/?probe=0aa196cd0c) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [c186124284](https://linux-hardware.org/?probe=c186124284) | Jul 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301RA_GV3... | Convertible | [fce4d4547c](https://linux-hardware.org/?probe=fce4d4547c) | Jul 03, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [eb23a7916c](https://linux-hardware.org/?probe=eb23a7916c) | Jul 03, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| HP            | 8350                        | Desktop     | [39a8a75ebe](https://linux-hardware.org/?probe=39a8a75ebe) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [31a8bd72d6](https://linux-hardware.org/?probe=31a8bd72d6) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [83a3a5794d](https://linux-hardware.org/?probe=83a3a5794d) | Jul 02, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [7b7c8244af](https://linux-hardware.org/?probe=7b7c8244af) | Jul 02, 2022 |
| Gigabyte      | EP45-DS3                    | Desktop     | [bc316ca4cb](https://linux-hardware.org/?probe=bc316ca4cb) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | Notebook    | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire C22-820              | All in one  | [0bb41ffb71](https://linux-hardware.org/?probe=0bb41ffb71) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX392FN_UX392FN     | Notebook    | [b4699ba106](https://linux-hardware.org/?probe=b4699ba106) | Jun 30, 2022 |
| Dell          | 0HJ054                      | Desktop     | [bb9d7a3a58](https://linux-hardware.org/?probe=bb9d7a3a58) | Jun 30, 2022 |
| MSI           | CR620                       | Notebook    | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| Dell          | Latitude 7389               | Convertible | [6cc0f640ed](https://linux-hardware.org/?probe=6cc0f640ed) | Jun 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Dell          | Inspiron 3531               | Notebook    | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [8cf2281f01](https://linux-hardware.org/?probe=8cf2281f01) | Jun 27, 2022 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [9923c241d9](https://linux-hardware.org/?probe=9923c241d9) | Jun 27, 2022 |
| Dell          | 0U880P A00                  | Desktop     | [e14832f09c](https://linux-hardware.org/?probe=e14832f09c) | Jun 26, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6262e08c1f](https://linux-hardware.org/?probe=6262e08c1f) | Jun 26, 2022 |
| Pegatron      | IPPSB-DB                    | Desktop     | [a63cdffc5b](https://linux-hardware.org/?probe=a63cdffc5b) | Jun 26, 2022 |
| Acer          | Aspire A515-55G             | Notebook    | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [3dc935ecb1](https://linux-hardware.org/?probe=3dc935ecb1) | Jun 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c78b132d02](https://linux-hardware.org/?probe=c78b132d02) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [b232a434fd](https://linux-hardware.org/?probe=b232a434fd) | Jun 26, 2022 |
| Google        | Candy                       | Notebook    | [8888e44843](https://linux-hardware.org/?probe=8888e44843) | Jun 25, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [0297d9c8c1](https://linux-hardware.org/?probe=0297d9c8c1) | Jun 25, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [fbde5d214f](https://linux-hardware.org/?probe=fbde5d214f) | Jun 24, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [26cd390b15](https://linux-hardware.org/?probe=26cd390b15) | Jun 24, 2022 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [05449d9e5c](https://linux-hardware.org/?probe=05449d9e5c) | Jun 24, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [8f8ce01734](https://linux-hardware.org/?probe=8f8ce01734) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | Notebook    | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dede0c6694](https://linux-hardware.org/?probe=dede0c6694) | Jun 23, 2022 |
| MSI           | A75A-G35                    | Desktop     | [9e3dd8051c](https://linux-hardware.org/?probe=9e3dd8051c) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a24305d670](https://linux-hardware.org/?probe=a24305d670) | Jun 23, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [b21a0caebf](https://linux-hardware.org/?probe=b21a0caebf) | Jun 22, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ebacc3616d](https://linux-hardware.org/?probe=ebacc3616d) | Jun 22, 2022 |
| Dell          | Latitude E6400              | Notebook    | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ecea2bb4ad](https://linux-hardware.org/?probe=ecea2bb4ad) | Jun 22, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [6b549dfe09](https://linux-hardware.org/?probe=6b549dfe09) | Jun 22, 2022 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [d3feec9910](https://linux-hardware.org/?probe=d3feec9910) | Jun 21, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [3bd256be91](https://linux-hardware.org/?probe=3bd256be91) | Jun 21, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [4014366c8a](https://linux-hardware.org/?probe=4014366c8a) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [cb159502de](https://linux-hardware.org/?probe=cb159502de) | Jun 21, 2022 |
| Dell          | Latitude E6540              | Notebook    | [c0f2801648](https://linux-hardware.org/?probe=c0f2801648) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Dell          | Latitude E6540              | Notebook    | [7d19e0b30e](https://linux-hardware.org/?probe=7d19e0b30e) | Jun 20, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [421b2e1975](https://linux-hardware.org/?probe=421b2e1975) | Jun 20, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| AWOW          | NY41                        | Mini pc     | [f420b36754](https://linux-hardware.org/?probe=f420b36754) | Jun 19, 2022 |
| AWOW          | NY41                        | Mini pc     | [e8f74093f9](https://linux-hardware.org/?probe=e8f74093f9) | Jun 19, 2022 |
| Global Dis... | W11651                      | Notebook    | [a28b308f7f](https://linux-hardware.org/?probe=a28b308f7f) | Jun 19, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [82be38e941](https://linux-hardware.org/?probe=82be38e941) | Jun 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [99eb49831a](https://linux-hardware.org/?probe=99eb49831a) | Jun 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a20ee1d5b6](https://linux-hardware.org/?probe=a20ee1d5b6) | Jun 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [85a022001e](https://linux-hardware.org/?probe=85a022001e) | Jun 16, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [14500170b0](https://linux-hardware.org/?probe=14500170b0) | Jun 16, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [a07f3b6954](https://linux-hardware.org/?probe=a07f3b6954) | Jun 16, 2022 |
| Dell          | Inspiron 7500 2n1 Black     | Convertible | [d08495e5aa](https://linux-hardware.org/?probe=d08495e5aa) | Jun 16, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8932d07801](https://linux-hardware.org/?probe=8932d07801) | Jun 16, 2022 |
| Dell          | 0X501H A02                  | Desktop     | [b9cb2a1e48](https://linux-hardware.org/?probe=b9cb2a1e48) | Jun 15, 2022 |
| Dell          | Precision M4700             | Notebook    | [3d10ec3c17](https://linux-hardware.org/?probe=3d10ec3c17) | Jun 15, 2022 |
| Acer          | Aspire M3970                | Desktop     | [b966120966](https://linux-hardware.org/?probe=b966120966) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | Notebook    | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dell          | XPS 12 9Q23                 | Notebook    | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [e849fd55ad](https://linux-hardware.org/?probe=e849fd55ad) | Jun 14, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [aa63e13a60](https://linux-hardware.org/?probe=aa63e13a60) | Jun 13, 2022 |
| Positivo      | Q464C                       | Notebook    | [1cb4cb4da1](https://linux-hardware.org/?probe=1cb4cb4da1) | Jun 13, 2022 |
| Lenovo        | 3717 SDK0J40709 WIN 3259... | Desktop     | [ba6786bbe8](https://linux-hardware.org/?probe=ba6786bbe8) | Jun 13, 2022 |
| Positivo      | Q464C                       | Notebook    | [a772cd7eae](https://linux-hardware.org/?probe=a772cd7eae) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [9baa7ce30e](https://linux-hardware.org/?probe=9baa7ce30e) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | Notebook    | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [4e227cff8b](https://linux-hardware.org/?probe=4e227cff8b) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2a772cecf4](https://linux-hardware.org/?probe=2a772cecf4) | Jun 12, 2022 |
| Foxconn       | Irvine HP P/N               | Desktop     | [551f18d133](https://linux-hardware.org/?probe=551f18d133) | Jun 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [14b9e721b7](https://linux-hardware.org/?probe=14b9e721b7) | Jun 11, 2022 |
| HP            | Pavilion 17                 | Notebook    | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Positivo      | C4500D                      | Notebook    | [70dc4735fa](https://linux-hardware.org/?probe=70dc4735fa) | Jun 11, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [dcaa9a66f4](https://linux-hardware.org/?probe=dcaa9a66f4) | Jun 10, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [828f110a40](https://linux-hardware.org/?probe=828f110a40) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [4b56f8a972](https://linux-hardware.org/?probe=4b56f8a972) | Jun 08, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [8b2e214403](https://linux-hardware.org/?probe=8b2e214403) | Jun 08, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [431ccbf84a](https://linux-hardware.org/?probe=431ccbf84a) | Jun 08, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9719a84d3e](https://linux-hardware.org/?probe=9719a84d3e) | Jun 08, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [9651975542](https://linux-hardware.org/?probe=9651975542) | Jun 07, 2022 |
| Dell          | Inspiron 11-3168            | Notebook    | [b43b02cdeb](https://linux-hardware.org/?probe=b43b02cdeb) | Jun 07, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [39cfb21bae](https://linux-hardware.org/?probe=39cfb21bae) | Jun 07, 2022 |
| Lenovo        | ThinkPad T540p 20BF0038G... | Notebook    | [e7d830048d](https://linux-hardware.org/?probe=e7d830048d) | Jun 06, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [902546cb45](https://linux-hardware.org/?probe=902546cb45) | Jun 06, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [94d4930070](https://linux-hardware.org/?probe=94d4930070) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | Desktop     | [e993e32a56](https://linux-hardware.org/?probe=e993e32a56) | Jun 06, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [96ed2caf25](https://linux-hardware.org/?probe=96ed2caf25) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [4af3ead1a7](https://linux-hardware.org/?probe=4af3ead1a7) | Jun 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [0ebbfb5b74](https://linux-hardware.org/?probe=0ebbfb5b74) | Jun 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [654b62a3bb](https://linux-hardware.org/?probe=654b62a3bb) | Jun 05, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [07808a7cbf](https://linux-hardware.org/?probe=07808a7cbf) | Jun 05, 2022 |
| Acer          | Aspire C22-820              | All in one  | [32cb850c67](https://linux-hardware.org/?probe=32cb850c67) | Jun 05, 2022 |
| HP            | 8350                        | Desktop     | [63a9e40af6](https://linux-hardware.org/?probe=63a9e40af6) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [480a4c12b1](https://linux-hardware.org/?probe=480a4c12b1) | Jun 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Acer          | Aspire C22-820              | All in one  | [682fb84b70](https://linux-hardware.org/?probe=682fb84b70) | Jun 04, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [d5648a1a95](https://linux-hardware.org/?probe=d5648a1a95) | Jun 04, 2022 |
| MSI           | B85M-G43                    | Desktop     | [097b308b60](https://linux-hardware.org/?probe=097b308b60) | Jun 04, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [94c2c3411a](https://linux-hardware.org/?probe=94c2c3411a) | Jun 04, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [d88547de78](https://linux-hardware.org/?probe=d88547de78) | Jun 04, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9404638832](https://linux-hardware.org/?probe=9404638832) | Jun 03, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| BESSTAR Te... | TL50                        | Desktop     | [0455aba8a3](https://linux-hardware.org/?probe=0455aba8a3) | Jun 03, 2022 |
| HP            | 3029h                       | Desktop     | [d536fb8e36](https://linux-hardware.org/?probe=d536fb8e36) | Jun 03, 2022 |
| Ematic        | EWT935DK                    | Notebook    | [13c5b6c48c](https://linux-hardware.org/?probe=13c5b6c48c) | Jun 03, 2022 |
| Medion        | WIM2180                     | Notebook    | [0548ef61b7](https://linux-hardware.org/?probe=0548ef61b7) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Medion        | WIM2180                     | Notebook    | [b645a2fa42](https://linux-hardware.org/?probe=b645a2fa42) | Jun 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [61b90c102c](https://linux-hardware.org/?probe=61b90c102c) | Jun 03, 2022 |
| ASUSTek       | P5E-VM DO                   | Desktop     | [935c03cd63](https://linux-hardware.org/?probe=935c03cd63) | Jun 03, 2022 |
| ASUSTek       | T102HA                      | Tablet      | [ec87718c8c](https://linux-hardware.org/?probe=ec87718c8c) | Jun 02, 2022 |
| Lenovo        | G780 2182                   | Notebook    | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [71e59838a5](https://linux-hardware.org/?probe=71e59838a5) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [702f836250](https://linux-hardware.org/?probe=702f836250) | Jun 02, 2022 |
| Biostar       | A78MD                       | Desktop     | [206b04b6d8](https://linux-hardware.org/?probe=206b04b6d8) | Jun 02, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [5eff529610](https://linux-hardware.org/?probe=5eff529610) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [5c9f7b1ab9](https://linux-hardware.org/?probe=5c9f7b1ab9) | Jun 02, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [0e1e2765fc](https://linux-hardware.org/?probe=0e1e2765fc) | Jun 01, 2022 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [8b67a50c5e](https://linux-hardware.org/?probe=8b67a50c5e) | Jun 01, 2022 |
| Biostar       | A78MD                       | Desktop     | [49ea0bd0e4](https://linux-hardware.org/?probe=49ea0bd0e4) | Jun 01, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [01a41f9d99](https://linux-hardware.org/?probe=01a41f9d99) | Jun 01, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [7c1c1fa1ce](https://linux-hardware.org/?probe=7c1c1fa1ce) | Jun 01, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [12cfa4cdb2](https://linux-hardware.org/?probe=12cfa4cdb2) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [951bd2ea8d](https://linux-hardware.org/?probe=951bd2ea8d) | May 31, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | Desktop     | [7bfeaeb75b](https://linux-hardware.org/?probe=7bfeaeb75b) | May 31, 2022 |
| Positivo      | POS-PIG41BAG                | Desktop     | [3ca7484fcf](https://linux-hardware.org/?probe=3ca7484fcf) | May 31, 2022 |
| ASUSTek       | X450LD                      | Notebook    | [b77a4297da](https://linux-hardware.org/?probe=b77a4297da) | May 31, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [20b5815ca3](https://linux-hardware.org/?probe=20b5815ca3) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d078b8d5dd](https://linux-hardware.org/?probe=d078b8d5dd) | May 30, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [1dbf357f4f](https://linux-hardware.org/?probe=1dbf357f4f) | May 30, 2022 |
| Dell          | Latitude E6510              | Notebook    | [4fe104ba1c](https://linux-hardware.org/?probe=4fe104ba1c) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [dbf473f0a0](https://linux-hardware.org/?probe=dbf473f0a0) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [574439c3c6](https://linux-hardware.org/?probe=574439c3c6) | May 30, 2022 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [5874582cbc](https://linux-hardware.org/?probe=5874582cbc) | May 29, 2022 |
| Intel         | NUC5i3RYB H41000-507        | Mini pc     | [8435958f2a](https://linux-hardware.org/?probe=8435958f2a) | May 29, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | Notebook    | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| MSI           | Z97 XPOWER AC               | Desktop     | [dd5c7a981a](https://linux-hardware.org/?probe=dd5c7a981a) | May 29, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [2c3ba3123f](https://linux-hardware.org/?probe=2c3ba3123f) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [ba2d55d308](https://linux-hardware.org/?probe=ba2d55d308) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [fac9e55ae9](https://linux-hardware.org/?probe=fac9e55ae9) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [fa0b4c98df](https://linux-hardware.org/?probe=fa0b4c98df) | May 29, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [9ebd09a280](https://linux-hardware.org/?probe=9ebd09a280) | May 29, 2022 |
| Dell          | Latitude 3410               | Notebook    | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [3b95da87e9](https://linux-hardware.org/?probe=3b95da87e9) | May 28, 2022 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [7d47123b6c](https://linux-hardware.org/?probe=7d47123b6c) | May 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3302c5de16](https://linux-hardware.org/?probe=3302c5de16) | May 27, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [4e77d22694](https://linux-hardware.org/?probe=4e77d22694) | May 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9011cf0a9b](https://linux-hardware.org/?probe=9011cf0a9b) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [1137f80fcd](https://linux-hardware.org/?probe=1137f80fcd) | May 27, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [57dbc86807](https://linux-hardware.org/?probe=57dbc86807) | May 27, 2022 |
| Dell          | Inspiron 5423               | Notebook    | [bd9cd24b2d](https://linux-hardware.org/?probe=bd9cd24b2d) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0d0af584d5](https://linux-hardware.org/?probe=0d0af584d5) | May 26, 2022 |
| Acer          | Aspire E3-112M              | Notebook    | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [ba19793a38](https://linux-hardware.org/?probe=ba19793a38) | May 26, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | Notebook    | [7a7ef6ced7](https://linux-hardware.org/?probe=7a7ef6ced7) | May 26, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [5df43d2ecd](https://linux-hardware.org/?probe=5df43d2ecd) | May 26, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [19d760099e](https://linux-hardware.org/?probe=19d760099e) | May 25, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | Notebook    | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [3334efe1e7](https://linux-hardware.org/?probe=3334efe1e7) | May 25, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [42ebc7f075](https://linux-hardware.org/?probe=42ebc7f075) | May 25, 2022 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [24c058da74](https://linux-hardware.org/?probe=24c058da74) | May 25, 2022 |
| HP            | EliteBook 8760w             | Notebook    | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [dd317d92a3](https://linux-hardware.org/?probe=dd317d92a3) | May 25, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [18427eddde](https://linux-hardware.org/?probe=18427eddde) | May 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [293f5586bd](https://linux-hardware.org/?probe=293f5586bd) | May 25, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [a6e55f9bd8](https://linux-hardware.org/?probe=a6e55f9bd8) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [a439693491](https://linux-hardware.org/?probe=a439693491) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | Notebook    | [cca71eec7f](https://linux-hardware.org/?probe=cca71eec7f) | May 24, 2022 |
| Dell          | Venue 8 Pro 5830            | Notebook    | [c07937f5ea](https://linux-hardware.org/?probe=c07937f5ea) | May 24, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [783e306676](https://linux-hardware.org/?probe=783e306676) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| Dell          | Latitude D520               | Notebook    | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Lenovo        | ThinkPad X301 277418G       | Notebook    | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| Toshiba       | Satellite L75D-A            | Notebook    | [0a4b6bedbf](https://linux-hardware.org/?probe=0a4b6bedbf) | May 24, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [4249d49f41](https://linux-hardware.org/?probe=4249d49f41) | May 22, 2022 |
| Toshiba       | Satellite L10W-C            | Notebook    | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [dffc3ea80a](https://linux-hardware.org/?probe=dffc3ea80a) | May 21, 2022 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [084bacdad3](https://linux-hardware.org/?probe=084bacdad3) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| ASUSTek       | K43U                        | Notebook    | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| Positivo      | CHT14B                      | Notebook    | [435bbd3b75](https://linux-hardware.org/?probe=435bbd3b75) | May 20, 2022 |
| Samsung       | 930QDB                      | Convertible | [ecaa182549](https://linux-hardware.org/?probe=ecaa182549) | May 20, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [3a9789ed8a](https://linux-hardware.org/?probe=3a9789ed8a) | May 20, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e2a3654000](https://linux-hardware.org/?probe=e2a3654000) | May 20, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [4ae1475168](https://linux-hardware.org/?probe=4ae1475168) | May 20, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | Notebook    | [8e5e8ea1ba](https://linux-hardware.org/?probe=8e5e8ea1ba) | May 20, 2022 |
| Medion        | Akoya S6214T                | Notebook    | [b0a0df98e0](https://linux-hardware.org/?probe=b0a0df98e0) | May 20, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1d5fec86a8](https://linux-hardware.org/?probe=1d5fec86a8) | May 20, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [b6b5e0738c](https://linux-hardware.org/?probe=b6b5e0738c) | May 19, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Acer          | TravelMate 5320             | Notebook    | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| ASUSTek       | K43U                        | Notebook    | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| MSI           | B85M-G43                    | Desktop     | [ef33bf347c](https://linux-hardware.org/?probe=ef33bf347c) | May 18, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [dd1193f7ab](https://linux-hardware.org/?probe=dd1193f7ab) | May 18, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| HP            | Pavilion g4                 | Notebook    | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [16404d222a](https://linux-hardware.org/?probe=16404d222a) | May 18, 2022 |
| Gateway       | NV55C                       | Notebook    | [82fcde80bb](https://linux-hardware.org/?probe=82fcde80bb) | May 18, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [2b889fc85b](https://linux-hardware.org/?probe=2b889fc85b) | May 17, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [d8b886317a](https://linux-hardware.org/?probe=d8b886317a) | May 17, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [1df44e40e2](https://linux-hardware.org/?probe=1df44e40e2) | May 17, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [aa8b5a4aec](https://linux-hardware.org/?probe=aa8b5a4aec) | May 17, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [7ab57b617f](https://linux-hardware.org/?probe=7ab57b617f) | May 17, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [4b277b05bb](https://linux-hardware.org/?probe=4b277b05bb) | May 17, 2022 |
| HP            | 2ADE                        | Desktop     | [77c2ea750b](https://linux-hardware.org/?probe=77c2ea750b) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | Notebook    | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [aea8e14bff](https://linux-hardware.org/?probe=aea8e14bff) | May 17, 2022 |
| ASUSTek       | ROG Strix G713IM_G713IM     | Notebook    | [eb1da20105](https://linux-hardware.org/?probe=eb1da20105) | May 17, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [fba6de28d9](https://linux-hardware.org/?probe=fba6de28d9) | May 16, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ebbd363703](https://linux-hardware.org/?probe=ebbd363703) | May 16, 2022 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [4555cff448](https://linux-hardware.org/?probe=4555cff448) | May 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7fcd8503ab](https://linux-hardware.org/?probe=7fcd8503ab) | May 16, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [bb968f8b83](https://linux-hardware.org/?probe=bb968f8b83) | May 16, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b95339f19d](https://linux-hardware.org/?probe=b95339f19d) | May 15, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| ASRock        | A88M-G                      | Desktop     | [81d094b2ec](https://linux-hardware.org/?probe=81d094b2ec) | May 15, 2022 |
| ASRock        | A88M-G                      | Desktop     | [8883591354](https://linux-hardware.org/?probe=8883591354) | May 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0d9d6b919b](https://linux-hardware.org/?probe=0d9d6b919b) | May 15, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c9da66f0e8](https://linux-hardware.org/?probe=c9da66f0e8) | May 15, 2022 |
| Thomson       | NEO14SBK                    | Notebook    | [2ae5fbd212](https://linux-hardware.org/?probe=2ae5fbd212) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [08ba1e652c](https://linux-hardware.org/?probe=08ba1e652c) | May 14, 2022 |
| Intel         | S5520HC E26045-457          | Server      | [ce6fe2a9cd](https://linux-hardware.org/?probe=ce6fe2a9cd) | May 14, 2022 |
| HP            | Pavilion 17                 | Notebook    | [a3f1fe480c](https://linux-hardware.org/?probe=a3f1fe480c) | May 14, 2022 |
| MSI           | MS-7260                     | Desktop     | [835ab9042d](https://linux-hardware.org/?probe=835ab9042d) | May 13, 2022 |
| ASUSTek       | N80Vb                       | Notebook    | [74cb7e076b](https://linux-hardware.org/?probe=74cb7e076b) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Alienware     | 17                          | Notebook    | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| Lenovo        | ThinkPad T61 7661V72        | Notebook    | [3d40fb11e8](https://linux-hardware.org/?probe=3d40fb11e8) | May 13, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [602289ad13](https://linux-hardware.org/?probe=602289ad13) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [048951833f](https://linux-hardware.org/?probe=048951833f) | May 13, 2022 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [f45bf21321](https://linux-hardware.org/?probe=f45bf21321) | May 12, 2022 |
| Dell          | 0F2A30 A00                  | All in one  | [ae5664a81f](https://linux-hardware.org/?probe=ae5664a81f) | May 12, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3824ac02d2](https://linux-hardware.org/?probe=3824ac02d2) | May 12, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | Desktop     | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| Acer          | Aspire X3990                | Desktop     | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [8f62053ddd](https://linux-hardware.org/?probe=8f62053ddd) | May 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [422c7a9209](https://linux-hardware.org/?probe=422c7a9209) | May 11, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [018c90008f](https://linux-hardware.org/?probe=018c90008f) | May 11, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [b1d977cd69](https://linux-hardware.org/?probe=b1d977cd69) | May 11, 2022 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [b558000bcc](https://linux-hardware.org/?probe=b558000bcc) | May 10, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [e041ed14b2](https://linux-hardware.org/?probe=e041ed14b2) | May 10, 2022 |
| Dell          | 0DR845                      | Desktop     | [ab501b0efe](https://linux-hardware.org/?probe=ab501b0efe) | May 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [838a99f17a](https://linux-hardware.org/?probe=838a99f17a) | May 10, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [5590d9a0f3](https://linux-hardware.org/?probe=5590d9a0f3) | May 10, 2022 |
| Foxconn       | LIMA                        | Desktop     | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [81cd3de099](https://linux-hardware.org/?probe=81cd3de099) | May 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [a5deca63d5](https://linux-hardware.org/?probe=a5deca63d5) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [1606b44e03](https://linux-hardware.org/?probe=1606b44e03) | May 09, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [42f2a531b5](https://linux-hardware.org/?probe=42f2a531b5) | May 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [637a04a2d1](https://linux-hardware.org/?probe=637a04a2d1) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [485a4916ed](https://linux-hardware.org/?probe=485a4916ed) | May 09, 2022 |
| ASRock        | H87M                        | Desktop     | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [bf028580b1](https://linux-hardware.org/?probe=bf028580b1) | May 09, 2022 |
| HP            | Pavilion dv7                | Notebook    | [709b7bc3e0](https://linux-hardware.org/?probe=709b7bc3e0) | May 09, 2022 |
| Gateway       | SX2185                      | Desktop     | [ddb64bc283](https://linux-hardware.org/?probe=ddb64bc283) | May 09, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [be0cecd40a](https://linux-hardware.org/?probe=be0cecd40a) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9a00d24f58](https://linux-hardware.org/?probe=9a00d24f58) | May 09, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [3f3089216f](https://linux-hardware.org/?probe=3f3089216f) | May 09, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [0ed6635d41](https://linux-hardware.org/?probe=0ed6635d41) | May 09, 2022 |
| ASUSTek       | U43F                        | Notebook    | [ad1a88d120](https://linux-hardware.org/?probe=ad1a88d120) | May 08, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [6b8870d38c](https://linux-hardware.org/?probe=6b8870d38c) | May 08, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [a0751c16d5](https://linux-hardware.org/?probe=a0751c16d5) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | Notebook    | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [5c2fec5833](https://linux-hardware.org/?probe=5c2fec5833) | May 08, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [c401229392](https://linux-hardware.org/?probe=c401229392) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [bed44df427](https://linux-hardware.org/?probe=bed44df427) | May 07, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [4c6f4d04bb](https://linux-hardware.org/?probe=4c6f4d04bb) | May 07, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [44f45ca8ea](https://linux-hardware.org/?probe=44f45ca8ea) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [f5c19a4d13](https://linux-hardware.org/?probe=f5c19a4d13) | May 07, 2022 |
| Toshiba       | TECRA A50-E                 | Notebook    | [29935ac4c6](https://linux-hardware.org/?probe=29935ac4c6) | May 06, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [458bf998ee](https://linux-hardware.org/?probe=458bf998ee) | May 06, 2022 |
| Intel         | H55                         | Desktop     | [138637d12c](https://linux-hardware.org/?probe=138637d12c) | May 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | Notebook    | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| Gigabyte      | G41M-Combo                  | Desktop     | [9940073216](https://linux-hardware.org/?probe=9940073216) | May 05, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [3c83210e52](https://linux-hardware.org/?probe=3c83210e52) | May 05, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [fd9ed9a035](https://linux-hardware.org/?probe=fd9ed9a035) | May 05, 2022 |
| HP            | 1906                        | Desktop     | [6f7f0536a9](https://linux-hardware.org/?probe=6f7f0536a9) | May 05, 2022 |
| Google        | Candy                       | Notebook    | [d461281743](https://linux-hardware.org/?probe=d461281743) | May 04, 2022 |
| HP            | Notebook                    | Notebook    | [05f1b18534](https://linux-hardware.org/?probe=05f1b18534) | May 04, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [31eaff1b28](https://linux-hardware.org/?probe=31eaff1b28) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8aadfc9dc1](https://linux-hardware.org/?probe=8aadfc9dc1) | May 04, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [4398a5b70f](https://linux-hardware.org/?probe=4398a5b70f) | May 04, 2022 |
| MSI           | B85M-G43                    | Desktop     | [f5deeb2d19](https://linux-hardware.org/?probe=f5deeb2d19) | May 04, 2022 |
| Google        | Candy                       | Notebook    | [2c41b3e736](https://linux-hardware.org/?probe=2c41b3e736) | May 04, 2022 |
| ASUSTek       | E200HA                      | Notebook    | [399a40cb14](https://linux-hardware.org/?probe=399a40cb14) | May 03, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [17aad0bb78](https://linux-hardware.org/?probe=17aad0bb78) | May 03, 2022 |
| HP            | 1906                        | Desktop     | [60ce09d82e](https://linux-hardware.org/?probe=60ce09d82e) | May 03, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [b224821361](https://linux-hardware.org/?probe=b224821361) | May 03, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [637890bd75](https://linux-hardware.org/?probe=637890bd75) | May 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [7587fe8761](https://linux-hardware.org/?probe=7587fe8761) | May 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bf79099573](https://linux-hardware.org/?probe=bf79099573) | May 03, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [4e21e1d28e](https://linux-hardware.org/?probe=4e21e1d28e) | May 02, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [0698d33be4](https://linux-hardware.org/?probe=0698d33be4) | May 02, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [5340c940c2](https://linux-hardware.org/?probe=5340c940c2) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [ce61ffd777](https://linux-hardware.org/?probe=ce61ffd777) | May 02, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [7f9e8dd9f6](https://linux-hardware.org/?probe=7f9e8dd9f6) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [63fc1199bc](https://linux-hardware.org/?probe=63fc1199bc) | May 01, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [c8e857524b](https://linux-hardware.org/?probe=c8e857524b) | May 01, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [317736e849](https://linux-hardware.org/?probe=317736e849) | May 01, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [51b0e7e57f](https://linux-hardware.org/?probe=51b0e7e57f) | May 01, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Acer          | Aspire 5741                 | Notebook    | [f82c315ff4](https://linux-hardware.org/?probe=f82c315ff4) | May 01, 2022 |
| Dell          | 0M017G A01                  | Desktop     | [653212f53c](https://linux-hardware.org/?probe=653212f53c) | May 01, 2022 |
| Acer          | V5-171                      | Notebook    | [a07ba20ff0](https://linux-hardware.org/?probe=a07ba20ff0) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| HP            | 1791                        | Desktop     | [877270ede6](https://linux-hardware.org/?probe=877270ede6) | Apr 30, 2022 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| Intel         | DCP847SKE G80890-105        | Desktop     | [45dc47c8aa](https://linux-hardware.org/?probe=45dc47c8aa) | Apr 30, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [89323fb22d](https://linux-hardware.org/?probe=89323fb22d) | Apr 30, 2022 |
| Acer          | V5-171                      | Notebook    | [8500a1c376](https://linux-hardware.org/?probe=8500a1c376) | Apr 30, 2022 |
| Foxconn       | 2A92                        | Desktop     | [298326d530](https://linux-hardware.org/?probe=298326d530) | Apr 30, 2022 |
| Foxconn       | 2A92                        | Desktop     | [a710d4a58f](https://linux-hardware.org/?probe=a710d4a58f) | Apr 30, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [af8b52acd3](https://linux-hardware.org/?probe=af8b52acd3) | Apr 29, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [c864c65ec1](https://linux-hardware.org/?probe=c864c65ec1) | Apr 29, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | Notebook    | [c4021bd208](https://linux-hardware.org/?probe=c4021bd208) | Apr 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [6a8bdd387c](https://linux-hardware.org/?probe=6a8bdd387c) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | ThinkCentre M91p 7052A9G    | Desktop     | [277754d8c1](https://linux-hardware.org/?probe=277754d8c1) | Apr 29, 2022 |
| Lenovo        | ThinkPad L412 440332U       | Notebook    | [6616ce20ee](https://linux-hardware.org/?probe=6616ce20ee) | Apr 28, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [814f90b822](https://linux-hardware.org/?probe=814f90b822) | Apr 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Razer         | Blade                       | Notebook    | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| HP            | 15                          | Notebook    | [63e5782bc3](https://linux-hardware.org/?probe=63e5782bc3) | Apr 27, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [97a2717eb9](https://linux-hardware.org/?probe=97a2717eb9) | Apr 27, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [68fdd1e81a](https://linux-hardware.org/?probe=68fdd1e81a) | Apr 27, 2022 |
| ASUSTek       | Hematite                    | Desktop     | [a6eec927f0](https://linux-hardware.org/?probe=a6eec927f0) | Apr 26, 2022 |
| MSI           | MS-6701                     | Desktop     | [8853d92523](https://linux-hardware.org/?probe=8853d92523) | Apr 26, 2022 |
| MSI           | MS-6701                     | Desktop     | [0bde2af604](https://linux-hardware.org/?probe=0bde2af604) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [ebfb06702f](https://linux-hardware.org/?probe=ebfb06702f) | Apr 25, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [47a349b8db](https://linux-hardware.org/?probe=47a349b8db) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [982005a931](https://linux-hardware.org/?probe=982005a931) | Apr 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [148f1cc5e8](https://linux-hardware.org/?probe=148f1cc5e8) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [a282e15540](https://linux-hardware.org/?probe=a282e15540) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [f940bea00c](https://linux-hardware.org/?probe=f940bea00c) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [b1594df62f](https://linux-hardware.org/?probe=b1594df62f) | Apr 25, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [392c7e4d0d](https://linux-hardware.org/?probe=392c7e4d0d) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [e1731ce27f](https://linux-hardware.org/?probe=e1731ce27f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [a681022e30](https://linux-hardware.org/?probe=a681022e30) | Apr 25, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [127dd69ddf](https://linux-hardware.org/?probe=127dd69ddf) | Apr 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 1978      | 52.77%  |
| Zorin 15 | 1575      | 42.02%  |
| Zorin 12 | 195       | 5.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 3736      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-38-generic | 176       | 4.2%    |
| 5.11.0-27-generic | 154       | 3.67%   |
| 5.15.0-46-generic | 146       | 3.48%   |
| 5.11.0-40-generic | 124       | 2.96%   |
| 5.13.0-39-generic | 120       | 2.86%   |
| 5.13.0-30-generic | 113       | 2.69%   |
| 5.3.0-40-generic  | 110       | 2.62%   |
| 5.11.0-41-generic | 107       | 2.55%   |
| 5.11.0-37-generic | 107       | 2.55%   |
| 5.11.0-43-generic | 101       | 2.41%   |
| 5.4.0-42-generic  | 98        | 2.34%   |
| 5.11.0-34-generic | 94        | 2.24%   |
| 5.13.0-40-generic | 90        | 2.15%   |
| 5.0.0-37-generic  | 79        | 1.88%   |
| 5.13.0-44-generic | 77        | 1.84%   |
| 5.13.0-35-generic | 75        | 1.79%   |
| 5.15.0-41-generic | 74        | 1.76%   |
| 5.3.0-46-generic  | 73        | 1.74%   |
| 5.13.0-28-generic | 71        | 1.69%   |
| 5.3.0-51-generic  | 65        | 1.55%   |
| 5.4.0-47-generic  | 60        | 1.43%   |
| 5.13.0-52-generic | 59        | 1.41%   |
| 5.13.0-27-generic | 59        | 1.41%   |
| 5.3.0-53-generic  | 54        | 1.29%   |
| 5.13.0-41-generic | 54        | 1.29%   |
| 5.4.0-58-generic  | 53        | 1.26%   |
| 5.3.0-42-generic  | 52        | 1.24%   |
| 5.4.0-48-generic  | 48        | 1.14%   |
| 5.15.0-48-generic | 48        | 1.14%   |
| 5.4.0-65-generic  | 46        | 1.1%    |
| 5.4.0-72-generic  | 45        | 1.07%   |
| 5.4.0-45-generic  | 45        | 1.07%   |
| 5.13.0-51-generic | 42        | 1%      |
| 5.4.0-80-generic  | 41        | 0.98%   |
| 5.11.0-36-generic | 39        | 0.93%   |
| 5.3.0-62-generic  | 38        | 0.91%   |
| 5.15.0-43-generic | 37        | 0.88%   |
| 5.3.0-28-generic  | 36        | 0.86%   |
| 5.11.0-46-generic | 36        | 0.86%   |
| 5.11.0-44-generic | 35        | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 944       | 24.24%  |
| 5.4.0   | 897       | 23.03%  |
| 5.13.0  | 750       | 19.26%  |
| 5.3.0   | 487       | 12.5%   |
| 5.15.0  | 295       | 7.57%   |
| 4.15.0  | 188       | 4.83%   |
| 5.0.0   | 153       | 3.93%   |
| 4.18.0  | 75        | 1.93%   |
| 5.8.0   | 53        | 1.36%   |
| 5.14.0  | 6         | 0.15%   |
| 4.4.0   | 6         | 0.15%   |
| 5.7.1   | 3         | 0.08%   |
| 5.7.0   | 2         | 0.05%   |
| 5.6.0   | 2         | 0.05%   |
| 5.17.5  | 2         | 0.05%   |
| 5.17.1  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.10.0  | 2         | 0.05%   |
| 4.13.0  | 2         | 0.05%   |
| 5.9.12  | 1         | 0.03%   |
| 5.9.0   | 1         | 0.03%   |
| 5.8.5   | 1         | 0.03%   |
| 5.7.17  | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.4.1   | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.6  | 1         | 0.03%   |
| 5.19.2  | 1         | 0.03%   |
| 5.19.12 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.19.0  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.18.15 | 1         | 0.03%   |
| 5.17.9  | 1         | 0.03%   |
| 5.16.5  | 1         | 0.03%   |
| 5.16.14 | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.15.13 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 944       | 24.24%  |
| 5.4     | 899       | 23.08%  |
| 5.13    | 751       | 19.28%  |
| 5.3     | 487       | 12.5%   |
| 5.15    | 298       | 7.65%   |
| 4.15    | 188       | 4.83%   |
| 5.0     | 153       | 3.93%   |
| 4.18    | 75        | 1.93%   |
| 5.8     | 54        | 1.39%   |
| 5.7     | 6         | 0.15%   |
| 5.19    | 6         | 0.15%   |
| 5.14    | 6         | 0.15%   |
| 4.4     | 6         | 0.15%   |
| 5.17    | 5         | 0.13%   |
| 5.16    | 5         | 0.13%   |
| 5.10    | 4         | 0.1%    |
| 5.9     | 2         | 0.05%   |
| 5.6     | 2         | 0.05%   |
| 5.18    | 2         | 0.05%   |
| 4.13    | 2         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3382      | 90.45%  |
| i686   | 357       | 9.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 2685      | 70.92%  |
| XFCE       | 789       | 20.84%  |
| Unknown    | 292       | 7.71%   |
| X-Cinnamon | 7         | 0.18%   |
| KDE        | 4         | 0.11%   |
| Unity      | 3         | 0.08%   |
| KDE5       | 2         | 0.05%   |
| Cinnamon   | 2         | 0.05%   |
| MATE       | 1         | 0.03%   |
| Budgie     | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3538      | 93.85%  |
| Unknown | 180       | 4.77%   |
| Wayland | 51        | 1.35%   |
| Tty     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3152      | 83.17%  |
| GDM3    | 255       | 6.73%   |
| GDM     | 213       | 5.62%   |
| LightDM | 157       | 4.14%   |
| TDM     | 11        | 0.29%   |
| SDDM    | 2         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1338      | 35.53%  |
| de_DE   | 289       | 7.67%   |
| pt_BR   | 253       | 6.72%   |
| Unknown | 230       | 6.11%   |
| en_GB   | 229       | 6.08%   |
| it_IT   | 116       | 3.08%   |
| en_CA   | 104       | 2.76%   |
| en_IN   | 103       | 2.73%   |
| es_ES   | 96        | 2.55%   |
| fr_FR   | 94        | 2.5%    |
| pl_PL   | 83        | 2.2%    |
| en_AU   | 66        | 1.75%   |
| nl_NL   | 61        | 1.62%   |
| es_MX   | 57        | 1.51%   |
| ru_RU   | 49        | 1.3%    |
| pt_PT   | 43        | 1.14%   |
| es_AR   | 43        | 1.14%   |
| cs_CZ   | 37        | 0.98%   |
| en_ZA   | 35        | 0.93%   |
| C       | 27        | 0.72%   |
| tr_TR   | 25        | 0.66%   |
| es_CL   | 25        | 0.66%   |
| sv_SE   | 22        | 0.58%   |
| fr_CA   | 21        | 0.56%   |
| hu_HU   | 20        | 0.53%   |
| en_NZ   | 19        | 0.5%    |
| es_CO   | 18        | 0.48%   |
| de_AT   | 16        | 0.42%   |
| ja_JP   | 14        | 0.37%   |
| fr_BE   | 13        | 0.35%   |
| el_GR   | 13        | 0.35%   |
| nl_BE   | 12        | 0.32%   |
| da_DK   | 12        | 0.32%   |
| es_PE   | 11        | 0.29%   |
| en_PH   | 10        | 0.27%   |
| de_CH   | 10        | 0.27%   |
| ru_UA   | 9         | 0.24%   |
| nb_NO   | 9         | 0.24%   |
| fi_FI   | 9         | 0.24%   |
| bg_BG   | 9         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2151      | 56.97%  |
| EFI  | 1625      | 43.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3520      | 93.97%  |
| Overlay  | 80        | 2.14%   |
| Zfs      | 39        | 1.04%   |
| Btrfs    | 33        | 0.88%   |
| Ext2     | 31        | 0.83%   |
| Unknown  | 27        | 0.72%   |
| Ext3     | 9         | 0.24%   |
| Xfs      | 6         | 0.16%   |
| Reiserfs | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3479      | 92.9%   |
| GPT     | 205       | 5.47%   |
| MBR     | 61        | 1.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3523      | 93.67%  |
| Yes       | 238       | 6.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3007      | 79.8%   |
| Yes       | 761       | 20.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 658       | 17.61%  |
| ASUSTek Computer    | 552       | 14.78%  |
| Dell                | 492       | 13.17%  |
| Lenovo              | 406       | 10.87%  |
| Acer                | 215       | 5.75%   |
| Gigabyte Technology | 210       | 5.62%   |
| MSI                 | 143       | 3.83%   |
| Toshiba             | 133       | 3.56%   |
| ASRock              | 113       | 3.02%   |
| Apple               | 95        | 2.54%   |
| Intel               | 61        | 1.63%   |
| Samsung Electronics | 53        | 1.42%   |
| Unknown             | 44        | 1.18%   |
| Sony                | 38        | 1.02%   |
| Fujitsu             | 31        | 0.83%   |
| Pegatron            | 26        | 0.7%    |
| Packard Bell        | 24        | 0.64%   |
| Positivo            | 23        | 0.62%   |
| Foxconn             | 20        | 0.54%   |
| Medion              | 19        | 0.51%   |
| Biostar             | 19        | 0.51%   |
| Fujitsu Siemens     | 17        | 0.46%   |
| ECS                 | 17        | 0.46%   |
| Google              | 15        | 0.4%    |
| Microsoft           | 14        | 0.37%   |
| HUAWEI              | 13        | 0.35%   |
| AMI                 | 13        | 0.35%   |
| Alienware           | 12        | 0.32%   |
| Gateway             | 11        | 0.29%   |
| Notebook            | 10        | 0.27%   |
| eMachines           | 9         | 0.24%   |
| Panasonic           | 7         | 0.19%   |
| NEC Computers       | 7         | 0.19%   |
| Shuttle             | 6         | 0.16%   |
| Insyde              | 6         | 0.16%   |
| IBM                 | 6         | 0.16%   |
| Semp Toshiba        | 5         | 0.13%   |
| Quanta              | 5         | 0.13%   |
| Multilaser          | 5         | 0.13%   |
| LG Electronics      | 5         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 73        | 1.95%   |
| ASUS All Series            | 30        | 0.8%    |
| HP Notebook                | 23        | 0.62%   |
| HP Pavilion Notebook       | 12        | 0.32%   |
| HP 15                      | 11        | 0.29%   |
| Dell OptiPlex 7010         | 11        | 0.29%   |
| HP Pavilion dv6            | 10        | 0.27%   |
| HP Pavilion dv7            | 9         | 0.24%   |
| Dell OptiPlex 790          | 9         | 0.24%   |
| Toshiba Satellite C660     | 8         | 0.21%   |
| HP Pavilion 15             | 8         | 0.21%   |
| HP Laptop 15-bw0xx         | 8         | 0.21%   |
| Dell OptiPlex 780          | 8         | 0.21%   |
| Dell Latitude D630         | 8         | 0.21%   |
| Dell Inspiron 1545         | 8         | 0.21%   |
| MSI MS-7C02                | 7         | 0.19%   |
| HP Pavilion g6             | 7         | 0.19%   |
| Gigabyte A320M-S2H         | 7         | 0.19%   |
| Dell OptiPlex 990          | 7         | 0.19%   |
| Dell OptiPlex 755          | 7         | 0.19%   |
| Dell Latitude E6400        | 7         | 0.19%   |
| Dell Inspiron 15-3567      | 7         | 0.19%   |
| ASUS M5A78L-M/USB3         | 7         | 0.19%   |
| HP Pavilion dv6700         | 6         | 0.16%   |
| HP Pavilion 17             | 6         | 0.16%   |
| HP EliteBook 840 G1        | 6         | 0.16%   |
| Gigabyte B450 AORUS M      | 6         | 0.16%   |
| Gigabyte 970A-DS3P         | 6         | 0.16%   |
| Dell Latitude E6410        | 6         | 0.16%   |
| Dell Inspiron 1525         | 6         | 0.16%   |
| ASUS M5A97 R2.0            | 6         | 0.16%   |
| Apple MacBookPro8,1        | 6         | 0.16%   |
| Toshiba Satellite A100     | 5         | 0.13%   |
| MSI MS-7817                | 5         | 0.13%   |
| Lenovo MIIX 320-10ICR 80XF | 5         | 0.13%   |
| HP ProDesk 600 G1 SFF      | 5         | 0.13%   |
| HP ProBook 640 G1          | 5         | 0.13%   |
| HP Pavilion g7             | 5         | 0.13%   |
| HP Pavilion dv5            | 5         | 0.13%   |
| HP EliteBook 8460p         | 5         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Inspiron          | 154       | 4.12%   |
| HP Pavilion            | 143       | 3.83%   |
| Acer Aspire            | 142       | 3.8%    |
| Lenovo ThinkPad        | 126       | 3.37%   |
| Dell Latitude          | 125       | 3.35%   |
| Toshiba Satellite      | 112       | 3%      |
| Lenovo IdeaPad         | 98        | 2.62%   |
| HP Compaq              | 88        | 2.36%   |
| Dell OptiPlex          | 86        | 2.3%    |
| Unknown                | 73        | 1.95%   |
| HP EliteBook           | 65        | 1.74%   |
| HP ProBook             | 56        | 1.5%    |
| HP Laptop              | 45        | 1.2%    |
| Lenovo ThinkCentre     | 39        | 1.04%   |
| ASUS ROG               | 37        | 0.99%   |
| ASUS PRIME             | 37        | 0.99%   |
| Dell Vostro            | 31        | 0.83%   |
| ASUS All               | 30        | 0.8%    |
| ASUS VivoBook          | 29        | 0.78%   |
| HP ENVY                | 28        | 0.75%   |
| Dell Precision         | 27        | 0.72%   |
| ASUS TUF               | 27        | 0.72%   |
| Dell XPS               | 25        | 0.67%   |
| HP Notebook            | 23        | 0.62%   |
| Lenovo Yoga            | 20        | 0.54%   |
| Packard Bell EasyNote  | 19        | 0.51%   |
| HP Stream              | 16        | 0.43%   |
| Microsoft Surface      | 14        | 0.37%   |
| HP EliteDesk           | 13        | 0.35%   |
| HP 255                 | 13        | 0.35%   |
| Fujitsu ESPRIMO        | 13        | 0.35%   |
| ASUS ZenBook           | 13        | 0.35%   |
| HP Presario            | 12        | 0.32%   |
| HP 15                  | 12        | 0.32%   |
| Gigabyte B450          | 12        | 0.32%   |
| ASUS M5A78L-M          | 12        | 0.32%   |
| HP OMEN                | 11        | 0.29%   |
| Gigabyte GA-78LMT-USB3 | 11        | 0.29%   |
| ASUS M5A97             | 11        | 0.29%   |
| Fujitsu LIFEBOOK       | 10        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 339       | 9.07%   |
| 2012    | 305       | 8.16%   |
| 2013    | 304       | 8.14%   |
| 2010    | 273       | 7.31%   |
| 2018    | 267       | 7.15%   |
| 2008    | 253       | 6.77%   |
| 2014    | 240       | 6.42%   |
| 2019    | 226       | 6.05%   |
| 2009    | 220       | 5.89%   |
| 2017    | 209       | 5.59%   |
| 2007    | 202       | 5.41%   |
| 2020    | 189       | 5.06%   |
| 2016    | 177       | 4.74%   |
| 2015    | 175       | 4.68%   |
| 2021    | 172       | 4.6%    |
| 2006    | 90        | 2.41%   |
| 2005    | 56        | 1.5%    |
| 2022    | 13        | 0.35%   |
| 2004    | 11        | 0.29%   |
| 2003    | 8         | 0.21%   |
| Unknown | 6         | 0.16%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2165      | 57.95%  |
| Desktop     | 1337      | 35.79%  |
| Convertible | 71        | 1.9%    |
| All in one  | 66        | 1.77%   |
| Mini pc     | 45        | 1.2%    |
| Tablet      | 43        | 1.15%   |
| Server      | 9         | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3416      | 90.97%  |
| Enabled  | 339       | 9.03%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3717      | 99.49%  |
| Yes  | 19        | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 986       | 26.15%  |
| 4.01-8.0    | 842       | 22.33%  |
| 8.01-16.0   | 583       | 15.46%  |
| 16.01-24.0  | 474       | 12.57%  |
| 1.01-2.0    | 396       | 10.5%   |
| 32.01-64.0  | 200       | 5.3%    |
| 2.01-3.0    | 134       | 3.55%   |
| 0.51-1.0    | 88        | 2.33%   |
| 64.01-256.0 | 43        | 1.14%   |
| 24.01-32.0  | 25        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1767      | 44.11%  |
| 2.01-3.0   | 1056      | 26.36%  |
| 3.01-4.0   | 420       | 10.48%  |
| 0.51-1.0   | 355       | 8.86%   |
| 4.01-8.0   | 312       | 7.79%   |
| 8.01-16.0  | 46        | 1.15%   |
| 0.01-0.5   | 41        | 1.02%   |
| 16.01-24.0 | 6         | 0.15%   |
| 24.01-32.0 | 3         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2507      | 65.8%   |
| 2       | 886       | 23.25%  |
| 3       | 221       | 5.8%    |
| 4       | 87        | 2.28%   |
| 5       | 42        | 1.1%    |
| 6       | 24        | 0.63%   |
| 0       | 21        | 0.55%   |
| 7       | 10        | 0.26%   |
| 8       | 8         | 0.21%   |
| 30      | 1         | 0.03%   |
| 11      | 1         | 0.03%   |
| 10      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1931      | 51.44%  |
| No        | 1823      | 48.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3282      | 87.71%  |
| No        | 460       | 12.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2942      | 78.52%  |
| No        | 805       | 21.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1919      | 50.92%  |
| No        | 1850      | 49.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 863       | 23.02%  |
| Germany      | 335       | 8.94%   |
| Brazil       | 288       | 7.68%   |
| UK           | 228       | 6.08%   |
| Canada       | 145       | 3.87%   |
| Italy        | 129       | 3.44%   |
| India        | 110       | 2.93%   |
| Spain        | 106       | 2.83%   |
| Netherlands  | 101       | 2.69%   |
| France       | 97        | 2.59%   |
| Poland       | 84        | 2.24%   |
| Australia    | 77        | 2.05%   |
| Mexico       | 73        | 1.95%   |
| Argentina    | 55        | 1.47%   |
| Portugal     | 48        | 1.28%   |
| Russia       | 45        | 1.2%    |
| South Africa | 44        | 1.17%   |
| Czechia      | 44        | 1.17%   |
| Sweden       | 41        | 1.09%   |
| Belgium      | 40        | 1.07%   |
| Romania      | 37        | 0.99%   |
| Indonesia    | 35        | 0.93%   |
| Greece       | 33        | 0.88%   |
| Switzerland  | 32        | 0.85%   |
| Austria      | 32        | 0.85%   |
| Turkey       | 31        | 0.83%   |
| Chile        | 29        | 0.77%   |
| Norway       | 27        | 0.72%   |
| Colombia     | 27        | 0.72%   |
| Hungary      | 26        | 0.69%   |
| Denmark      | 26        | 0.69%   |
| New Zealand  | 25        | 0.67%   |
| Serbia       | 24        | 0.64%   |
| Japan        | 24        | 0.64%   |
| Ukraine      | 19        | 0.51%   |
| Bulgaria     | 19        | 0.51%   |
| Philippines  | 16        | 0.43%   |
| Egypt        | 15        | 0.4%    |
| Israel       | 14        | 0.37%   |
| Finland      | 13        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 35        | 0.9%    |
| Berlin         | 29        | 0.75%   |
| Athens         | 26        | 0.67%   |
| Sydney         | 24        | 0.62%   |
| Munich         | 22        | 0.57%   |
| Vienna         | 20        | 0.52%   |
| Rio de Janeiro | 19        | 0.49%   |
| Rome           | 17        | 0.44%   |
| Madrid         | 16        | 0.41%   |
| Dallas         | 16        | 0.41%   |
| Perth          | 15        | 0.39%   |
| Montreal       | 15        | 0.39%   |
| Milan          | 15        | 0.39%   |
| Johannesburg   | 15        | 0.39%   |
| Auckland       | 15        | 0.39%   |
| Toronto        | 14        | 0.36%   |
| Buenos Aires   | 14        | 0.36%   |
| Bogotá        | 14        | 0.36%   |
| Warsaw         | 13        | 0.34%   |
| New York       | 13        | 0.34%   |
| Belgrade       | 13        | 0.34%   |
| Zurich         | 12        | 0.31%   |
| Prague         | 12        | 0.31%   |
| Mexico City    | 12        | 0.31%   |
| London         | 12        | 0.31%   |
| Istanbul       | 12        | 0.31%   |
| Denver         | 12        | 0.31%   |
| Nairobi        | 11        | 0.28%   |
| Moscow         | 11        | 0.28%   |
| Jakarta        | 11        | 0.28%   |
| Hamburg        | 11        | 0.28%   |
| Bucharest      | 11        | 0.28%   |
| Bengaluru      | 11        | 0.28%   |
| Tel Aviv       | 10        | 0.26%   |
| Stockholm      | 10        | 0.26%   |
| Seattle        | 10        | 0.26%   |
| Houston        | 10        | 0.26%   |
| Glasgow        | 10        | 0.26%   |
| Cape Town      | 10        | 0.26%   |
| Cairo          | 10        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 866       | 1171   | 17.28%  |
| WDC                       | 770       | 999    | 15.37%  |
| Samsung Electronics       | 594       | 849    | 11.85%  |
| Toshiba                   | 413       | 480    | 8.24%   |
| Unknown                   | 278       | 392    | 5.55%   |
| Kingston                  | 266       | 329    | 5.31%   |
| SanDisk                   | 261       | 305    | 5.21%   |
| Hitachi                   | 259       | 318    | 5.17%   |
| Crucial                   | 156       | 189    | 3.11%   |
| Intel                     | 90        | 113    | 1.8%    |
| HGST                      | 88        | 109    | 1.76%   |
| SK hynix                  | 66        | 81     | 1.32%   |
| A-DATA Technology         | 59        | 67     | 1.18%   |
| China                     | 48        | 53     | 0.96%   |
| Micron Technology         | 46        | 54     | 0.92%   |
| Phison                    | 42        | 54     | 0.84%   |
| Apple                     | 40        | 43     | 0.8%    |
| Maxtor                    | 38        | 52     | 0.76%   |
| Fujitsu                   | 38        | 40     | 0.76%   |
| PNY                       | 36        | 44     | 0.72%   |
| Intenso                   | 34        | 37     | 0.68%   |
| OCZ                       | 25        | 28     | 0.5%    |
| SPCC                      | 23        | 27     | 0.46%   |
| Silicon Motion            | 21        | 29     | 0.42%   |
| Patriot                   | 20        | 30     | 0.4%    |
| Transcend                 | 19        | 40     | 0.38%   |
| LITEON                    | 19        | 24     | 0.38%   |
| JMicron Technology        | 18        | 23     | 0.36%   |
| Micron/Crucial Technology | 16        | 17     | 0.32%   |
| SABRENT                   | 15        | 16     | 0.3%    |
| KIOXIA                    | 15        | 15     | 0.3%    |
| Team                      | 14        | 17     | 0.28%   |
| Hewlett-Packard           | 14        | 18     | 0.28%   |
| GOODRAM                   | 14        | 15     | 0.28%   |
| Netac                     | 13        | 14     | 0.26%   |
| LITEONIT                  | 13        | 15     | 0.26%   |
| Lexar                     | 11        | 11     | 0.22%   |
| Gigabyte Technology       | 10        | 18     | 0.2%    |
| Corsair                   | 10        | 11     | 0.2%    |
| Unknown                   | 10        | 10     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 96        | 1.76%   |
| Unknown MMC Card  64GB              | 72        | 1.32%   |
| Kingston SA400S37240G 240GB SSD     | 63        | 1.16%   |
| Seagate ST500DM002-1BD142 500GB     | 43        | 0.79%   |
| Toshiba MQ01ABF050 500GB            | 42        | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB      | 39        | 0.72%   |
| Kingston SA400S37480G 480GB SSD     | 39        | 0.72%   |
| Crucial CT240BX500SSD1 240GB        | 39        | 0.72%   |
| Samsung SSD 860 EVO 500GB           | 37        | 0.68%   |
| Kingston SA400S37120G 120GB SSD     | 36        | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 34        | 0.62%   |
| Samsung NVMe SSD Drive 256GB        | 34        | 0.62%   |
| Samsung NVMe SSD Drive 512GB        | 33        | 0.61%   |
| Unknown MMC Card  128GB             | 32        | 0.59%   |
| Toshiba MQ01ABD100 1TB              | 32        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB      | 30        | 0.55%   |
| Samsung NVMe SSD Drive 500GB        | 30        | 0.55%   |
| Toshiba MQ04ABF100 1TB              | 29        | 0.53%   |
| Samsung NVMe SSD Drive 1TB          | 29        | 0.53%   |
| Samsung SSD 850 EVO 250GB           | 28        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB     | 27        | 0.5%    |
| Samsung SSD 850 EVO 500GB           | 27        | 0.5%    |
| Seagate ST3500418AS 500GB           | 26        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD    | 26        | 0.48%   |
| Seagate ST9500325AS 500GB           | 25        | 0.46%   |
| Unknown SD/MMC/MS PRO 2GB           | 24        | 0.44%   |
| Crucial CT500MX500SSD1 500GB        | 24        | 0.44%   |
| Seagate Expansion 1TB               | 23        | 0.42%   |
| SanDisk NVMe SSD Drive 256GB        | 22        | 0.4%    |
| Toshiba DT01ACA100 1TB              | 21        | 0.39%   |
| Samsung SSD 860 EVO 250GB           | 21        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB            | 20        | 0.37%   |
| Unknown MMC Card  16GB              | 20        | 0.37%   |
| Intel NVMe SSD Drive 512GB          | 20        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB      | 19        | 0.35%   |
| SanDisk NVMe SSD Drive 512GB        | 19        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 18        | 0.33%   |
| Seagate ST1000DM003-1ER162 1TB      | 18        | 0.33%   |
| Hitachi HTS545032B9A300 320GB       | 18        | 0.33%   |
| SanDisk NVMe SSD Drive 1TB          | 17        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 855       | 1144   | 34.08%  |
| WDC                 | 700       | 894    | 27.9%   |
| Toshiba             | 350       | 410    | 13.95%  |
| Hitachi             | 259       | 318    | 10.32%  |
| Samsung Electronics | 119       | 149    | 4.74%   |
| HGST                | 88        | 109    | 3.51%   |
| Fujitsu             | 38        | 40     | 1.51%   |
| Maxtor              | 36        | 50     | 1.43%   |
| Unknown             | 24        | 30     | 0.96%   |
| Apple               | 20        | 22     | 0.8%    |
| USB3.0              | 4         | 5      | 0.16%   |
| IBM/Hitachi         | 4         | 5      | 0.16%   |
| Hewlett-Packard     | 3         | 6      | 0.12%   |
| SABRENT             | 2         | 2      | 0.08%   |
| Intenso             | 2         | 2      | 0.08%   |
| Quantum             | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| JMicron Technology  | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 2      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 315       | 435    | 19.95%  |
| Kingston            | 228       | 281    | 14.44%  |
| SanDisk             | 162       | 193    | 10.26%  |
| Crucial             | 153       | 184    | 9.69%   |
| WDC                 | 71        | 87     | 4.5%    |
| A-DATA Technology   | 54        | 62     | 3.42%   |
| Intel               | 47        | 55     | 2.98%   |
| China               | 47        | 52     | 2.98%   |
| PNY                 | 36        | 44     | 2.28%   |
| Toshiba             | 34        | 37     | 2.15%   |
| SK hynix            | 29        | 33     | 1.84%   |
| Micron Technology   | 28        | 33     | 1.77%   |
| Intenso             | 25        | 28     | 1.58%   |
| OCZ                 | 23        | 26     | 1.46%   |
| SPCC                | 21        | 25     | 1.33%   |
| Patriot             | 20        | 30     | 1.27%   |
| Transcend           | 19        | 40     | 1.2%    |
| LITEON              | 19        | 24     | 1.2%    |
| Apple               | 17        | 17     | 1.08%   |
| Team                | 14        | 17     | 0.89%   |
| Netac               | 13        | 14     | 0.82%   |
| LITEONIT            | 13        | 15     | 0.82%   |
| Goodram             | 13        | 14     | 0.82%   |
| Lexar               | 10        | 10     | 0.63%   |
| Hewlett-Packard     | 10        | 11     | 0.63%   |
| Leven               | 9         | 10     | 0.57%   |
| Gigabyte Technology | 9         | 16     | 0.57%   |
| KingSpec            | 8         | 10     | 0.51%   |
| Corsair             | 7         | 8      | 0.44%   |
| ASMT                | 7         | 7      | 0.44%   |
| Plextor             | 6         | 7      | 0.38%   |
| OWC                 | 6         | 6      | 0.38%   |
| Apacer              | 6         | 6      | 0.38%   |
| Verbatim            | 4         | 4      | 0.25%   |
| TCSUNBOW            | 4         | 4      | 0.25%   |
| Super Talent        | 4         | 5      | 0.25%   |
| Seagate             | 4         | 5      | 0.25%   |
| Pioneer             | 4         | 4      | 0.25%   |
| Mushkin             | 4         | 4      | 0.25%   |
| FORESEE             | 4         | 4      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2199      | 3192   | 48.12%  |
| SSD     | 1424      | 1957   | 31.16%  |
| NVMe    | 594       | 791    | 13%     |
| MMC     | 258       | 355    | 5.65%   |
| Unknown | 95        | 124    | 2.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3182      | 5032   | 75.67%  |
| NVMe | 576       | 761    | 13.7%   |
| MMC  | 258       | 355    | 6.14%   |
| SAS  | 189       | 271    | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2517      | 3464   | 67.66%  |
| 0.51-1.0   | 892       | 1208   | 23.98%  |
| 1.01-2.0   | 197       | 283    | 5.3%    |
| 3.01-4.0   | 46        | 82     | 1.24%   |
| 4.01-10.0  | 38        | 54     | 1.02%   |
| 2.01-3.0   | 28        | 56     | 0.75%   |
| 10.01-20.0 | 2         | 2      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1259      | 32.72%  |
| 251-500        | 925       | 24.04%  |
| 501-1000       | 494       | 12.84%  |
| 51-100         | 414       | 10.76%  |
| 21-50          | 236       | 6.13%   |
| 1001-2000      | 183       | 4.76%   |
| 1-20           | 121       | 3.14%   |
| More than 3000 | 116       | 3.01%   |
| 2001-3000      | 66        | 1.72%   |
| Unknown        | 34        | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1999      | 50.2%   |
| 21-50          | 856       | 21.5%   |
| 51-100         | 385       | 9.67%   |
| 101-250        | 300       | 7.53%   |
| 251-500        | 187       | 4.7%    |
| 501-1000       | 95        | 2.39%   |
| 1001-2000      | 58        | 1.46%   |
| More than 3000 | 51        | 1.28%   |
| Unknown        | 34        | 0.85%   |
| 2001-3000      | 17        | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB              | 2         | 2      | 3.28%   |
| Seagate ST9500420AS 500GB            | 2         | 2      | 3.28%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 3.28%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 1      | 1.64%   |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 1.64%   |
| WDC WD3200BPVT-55ZEST0 320GB         | 1         | 1      | 1.64%   |
| WDC WD3200AAKS-22B3A0 320GB          | 1         | 1      | 1.64%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 1      | 1.64%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 1      | 1.64%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 1      | 1.64%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 1.64%   |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 1      | 1.64%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 2      | 1.64%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 1      | 1.64%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 1.64%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.64%   |
| Toshiba MK8046GSX 80GB               | 1         | 1      | 1.64%   |
| Toshiba MK5061GSY 500GB              | 1         | 1      | 1.64%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 1.64%   |
| Toshiba MK2046GSX 200GB              | 1         | 1      | 1.64%   |
| Toshiba MG03ACA200 2TB               | 1         | 1      | 1.64%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.64%   |
| Silicon Motion Inland NVMe SSD 256GB | 1         | 1      | 1.64%   |
| Seagate ST9320325AS 320GB            | 1         | 1      | 1.64%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.64%   |
| Seagate ST9200420ASG 200GB           | 1         | 1      | 1.64%   |
| Seagate ST9160314AS 160GB            | 1         | 1      | 1.64%   |
| Seagate ST9120822AS 120GB            | 1         | 1      | 1.64%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 1.64%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 1      | 1.64%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1      | 1.64%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 1      | 1.64%   |
| Seagate ST3500514NS 500GB            | 1         | 1      | 1.64%   |
| Seagate ST3500413AS 500GB            | 1         | 1      | 1.64%   |
| Seagate ST3320620AS 320GB            | 1         | 1      | 1.64%   |
| Seagate ST3250318AS 250GB            | 1         | 1      | 1.64%   |
| Seagate ST320LT012-1DG14C 320GB      | 1         | 1      | 1.64%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1      | 1.64%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1      | 1.64%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 25     | 40%     |
| WDC                 | 11        | 12     | 18.33%  |
| Toshiba             | 10        | 10     | 16.67%  |
| Kingston            | 2         | 2      | 3.33%   |
| Hitachi             | 2         | 2      | 3.33%   |
| HGST                | 2         | 2      | 3.33%   |
| SK hynix            | 1         | 1      | 1.67%   |
| Silicon Motion      | 1         | 1      | 1.67%   |
| Samsung Electronics | 1         | 1      | 1.67%   |
| OCZ                 | 1         | 1      | 1.67%   |
| Micron Technology   | 1         | 1      | 1.67%   |
| LITEON              | 1         | 1      | 1.67%   |
| Intel               | 1         | 1      | 1.67%   |
| Hewlett-Packard     | 1         | 1      | 1.67%   |
| A-DATA Technology   | 1         | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 24        | 25     | 48.98%  |
| WDC     | 11        | 12     | 22.45%  |
| Toshiba | 10        | 10     | 20.41%  |
| Hitachi | 2         | 2      | 4.08%   |
| HGST    | 2         | 2      | 4.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 51     | 81.36%  |
| SSD  | 8         | 8      | 13.56%  |
| NVMe | 3         | 3      | 5.08%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3476      | 5982   | 91.91%  |
| Works    | 246       | 374    | 6.5%    |
| Malfunc  | 59        | 62     | 1.56%   |
| Failed   | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2605      | 61.74%  |
| AMD                              | 682       | 16.16%  |
| Samsung Electronics              | 208       | 4.93%   |
| Nvidia                           | 119       | 2.82%   |
| SanDisk                          | 98        | 2.32%   |
| ASMedia Technology               | 52        | 1.23%   |
| JMicron Technology               | 51        | 1.21%   |
| Phison Electronics               | 46        | 1.09%   |
| Kingston Technology Company      | 42        | 1%      |
| Marvell Technology Group         | 35        | 0.83%   |
| VIA Technologies                 | 34        | 0.81%   |
| SK hynix                         | 34        | 0.81%   |
| Silicon Integrated Systems [SiS] | 31        | 0.73%   |
| Toshiba America Info Systems     | 29        | 0.69%   |
| Silicon Motion                   | 23        | 0.55%   |
| Micron/Crucial Technology        | 19        | 0.45%   |
| Micron Technology                | 19        | 0.45%   |
| KIOXIA                           | 17        | 0.4%    |
| Silicon Image                    | 14        | 0.33%   |
| ADATA Technology                 | 12        | 0.28%   |
| Realtek Semiconductor            | 9         | 0.21%   |
| Broadcom / LSI                   | 6         | 0.14%   |
| Lite-On Technology               | 5         | 0.12%   |
| Seagate Technology               | 4         | 0.09%   |
| LSI Logic / Symbios Logic        | 4         | 0.09%   |
| Union Memory (Shenzhen)          | 3         | 0.07%   |
| Apple                            | 3         | 0.07%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| Solid State Storage Technology   | 2         | 0.05%   |
| OCZ Technology Group             | 2         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.05%   |
| Adaptec                          | 2         | 0.05%   |
| Promise Technology               | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 414       | 8.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 186       | 3.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 167       | 3.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 166       | 3.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 152       | 2.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 146       | 2.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 132       | 2.57%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 126       | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 126       | 2.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 106       | 2.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 103       | 2%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 100       | 1.95%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 100       | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 95        | 1.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 94        | 1.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 89        | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 77        | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 71        | 1.38%   |
| Intel SATA Controller [RAID mode]                                                       | 66        | 1.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 66        | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 60        | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 53        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 51        | 0.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 50        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 49        | 0.95%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 48        | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 47        | 0.91%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 41        | 0.8%    |
| Nvidia MCP61 SATA Controller                                                            | 40        | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 40        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 38        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 38        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 37        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 37        | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 35        | 0.68%   |
| Samsung NVMe SSD Controller 980                                                         | 34        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 34        | 0.66%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 34        | 0.66%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 30        | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 28        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2631      | 59.26%  |
| IDE  | 929       | 20.92%  |
| NVMe | 579       | 13.04%  |
| RAID | 289       | 6.51%   |
| SAS  | 7         | 0.16%   |
| SCSI | 5         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2921      | 78.19%  |
| AMD          | 814       | 21.79%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 56        | 1.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 33        | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 26        | 0.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 25        | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 24        | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 23        | 0.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.56%   |
| AMD Ryzen 5 3600 6-Core Processor             | 21        | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 0.51%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.48%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.48%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.48%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.45%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 17        | 0.45%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 17        | 0.45%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 17        | 0.45%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 17        | 0.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 0.43%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 0.43%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 15        | 0.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 15        | 0.4%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 15        | 0.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 0.4%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 15        | 0.4%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 15        | 0.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.4%    |
| Intel Pentium 4 CPU 3.00GHz                   | 14        | 0.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.37%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 14        | 0.37%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 14        | 0.37%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 14        | 0.37%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 14        | 0.37%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 13        | 0.35%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 0.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 722       | 19.29%  |
| Intel Core i7           | 464       | 12.4%   |
| Intel Core i3           | 351       | 9.38%   |
| Intel Core 2 Duo        | 284       | 7.59%   |
| Intel Celeron           | 235       | 6.28%   |
| Intel Atom              | 175       | 4.68%   |
| AMD Ryzen 5             | 132       | 3.53%   |
| Intel Pentium           | 120       | 3.21%   |
| Other                   | 98        | 2.62%   |
| AMD Ryzen 7             | 85        | 2.27%   |
| Intel Pentium Dual-Core | 71        | 1.9%    |
| Intel Xeon              | 67        | 1.79%   |
| Intel Pentium Dual      | 62        | 1.66%   |
| AMD A6                  | 61        | 1.63%   |
| AMD FX                  | 60        | 1.6%    |
| Intel Core 2 Quad       | 55        | 1.47%   |
| AMD A4                  | 43        | 1.15%   |
| Intel Genuine           | 41        | 1.1%    |
| Intel Core 2            | 39        | 1.04%   |
| AMD Ryzen 3             | 38        | 1.02%   |
| Intel Pentium 4         | 36        | 0.96%   |
| AMD Athlon 64 X2        | 35        | 0.94%   |
| AMD A8                  | 33        | 0.88%   |
| AMD A10                 | 32        | 0.86%   |
| AMD Athlon II X2        | 25        | 0.67%   |
| AMD Ryzen 9             | 24        | 0.64%   |
| Intel Celeron M         | 23        | 0.61%   |
| Intel Pentium M         | 22        | 0.59%   |
| AMD E1                  | 22        | 0.59%   |
| AMD E                   | 20        | 0.53%   |
| AMD Phenom II X4        | 18        | 0.48%   |
| AMD Athlon              | 17        | 0.45%   |
| AMD Sempron             | 16        | 0.43%   |
| AMD Turion 64 X2 Mobile | 13        | 0.35%   |
| AMD Athlon II X4        | 12        | 0.32%   |
| Intel Core i9           | 11        | 0.29%   |
| Intel Pentium Silver    | 10        | 0.27%   |
| Intel Pentium D         | 9         | 0.24%   |
| AMD Phenom II X6        | 9         | 0.24%   |
| Intel Pentium Gold      | 8         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1966      | 52.52%  |
| 4      | 1137      | 30.38%  |
| 1      | 250       | 6.68%   |
| 6      | 192       | 5.13%   |
| 8      | 128       | 3.42%   |
| 3      | 29        | 0.77%   |
| 12     | 18        | 0.48%   |
| 16     | 11        | 0.29%   |
| 10     | 8         | 0.21%   |
| 20     | 2         | 0.05%   |
| 40     | 1         | 0.03%   |
| 14     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3720      | 99.57%  |
| 2      | 16        | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1940      | 51.93%  |
| 1      | 1796      | 48.07%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3597      | 96.25%  |
| 32-bit         | 137       | 3.67%   |
| Unknown        | 3         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 351       | 9.25%   |
| 0x206a7    | 320       | 8.44%   |
| 0x306a9    | 246       | 6.49%   |
| 0x1067a    | 245       | 6.46%   |
| 0x306c3    | 195       | 5.14%   |
| 0x6fd      | 119       | 3.14%   |
| 0x40651    | 110       | 2.9%    |
| 0x20655    | 89        | 2.35%   |
| 0x406c4    | 77        | 2.03%   |
| 0x406e3    | 75        | 1.98%   |
| 0x806e9    | 73        | 1.92%   |
| 0x306d4    | 69        | 1.82%   |
| 0x30678    | 66        | 1.74%   |
| 0x806ea    | 60        | 1.58%   |
| 0x506e3    | 59        | 1.56%   |
| 0x10676    | 58        | 1.53%   |
| 0x906ea    | 53        | 1.4%    |
| 0x806c1    | 52        | 1.37%   |
| 0x6fb      | 51        | 1.34%   |
| 0x806ec    | 50        | 1.32%   |
| 0x906e9    | 46        | 1.21%   |
| 0x06001119 | 45        | 1.19%   |
| 0x06000852 | 44        | 1.16%   |
| 0x010000c8 | 42        | 1.11%   |
| 0x20652    | 38        | 1%      |
| 0x406c3    | 36        | 0.95%   |
| 0x08701021 | 36        | 0.95%   |
| 0x506c9    | 35        | 0.92%   |
| 0x106ca    | 35        | 0.92%   |
| 0x08108109 | 35        | 0.92%   |
| 0x6f6      | 32        | 0.84%   |
| 0x0700010f | 31        | 0.82%   |
| 0x6e8      | 30        | 0.79%   |
| 0x06006705 | 30        | 0.79%   |
| 0x6d8      | 28        | 0.74%   |
| 0x106c2    | 25        | 0.66%   |
| 0x706e5    | 24        | 0.63%   |
| 0x706a8    | 24        | 0.63%   |
| 0x08108102 | 24        | 0.63%   |
| 0x07030105 | 24        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 354       | 9.47%   |
| SandyBridge      | 339       | 9.07%   |
| Haswell          | 333       | 8.91%   |
| Penryn           | 322       | 8.61%   |
| IvyBridge        | 264       | 7.06%   |
| Core             | 258       | 6.9%    |
| Silvermont       | 213       | 5.7%    |
| Skylake          | 144       | 3.85%   |
| Westmere         | 143       | 3.83%   |
| K10              | 98        | 2.62%   |
| Piledriver       | 94        | 2.51%   |
| Zen+             | 92        | 2.46%   |
| Zen 2            | 89        | 2.38%   |
| K8 Hammer        | 88        | 2.35%   |
| P6               | 79        | 2.11%   |
| Broadwell        | 71        | 1.9%    |
| Bonnell          | 71        | 1.9%    |
| TigerLake        | 59        | 1.58%   |
| Excavator        | 56        | 1.5%    |
| NetBurst         | 53        | 1.42%   |
| Zen 3            | 50        | 1.34%   |
| Zen              | 48        | 1.28%   |
| CometLake        | 46        | 1.23%   |
| Goldmont plus    | 44        | 1.18%   |
| Icelake          | 41        | 1.1%    |
| Puma             | 39        | 1.04%   |
| Jaguar           | 37        | 0.99%   |
| Goldmont         | 37        | 0.99%   |
| Bobcat           | 37        | 0.99%   |
| Nehalem          | 35        | 0.94%   |
| Unknown          | 22        | 0.59%   |
| K10 Llano        | 21        | 0.56%   |
| Steamroller      | 18        | 0.48%   |
| K8 & K10 hybrid  | 15        | 0.4%    |
| Bulldozer        | 14        | 0.37%   |
| Alderlake Hybrid | 7         | 0.19%   |
| Tremont          | 4         | 0.11%   |
| K6               | 3         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2197      | 52.35%  |
| Nvidia                           | 1002      | 23.87%  |
| AMD                              | 948       | 22.59%  |
| Silicon Integrated Systems [SiS] | 25        | 0.6%    |
| VIA Technologies                 | 16        | 0.38%   |
| Matrox Electronics Systems       | 5         | 0.12%   |
| ASPEED Technology                | 2         | 0.05%   |
| Trident Microsystems             | 1         | 0.02%   |
| Silicon Motion                   | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 257       | 5.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 166       | 3.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 124       | 2.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 114       | 2.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 110       | 2.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 103       | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 88        | 1.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 72        | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 69        | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 69        | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 69        | 1.56%   |
| Intel HD Graphics 620                                                                    | 69        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 68        | 1.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 59        | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 58        | 1.31%   |
| Intel UHD Graphics 620                                                                   | 56        | 1.27%   |
| Intel HD Graphics 5500                                                                   | 51        | 1.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 50        | 1.13%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 47        | 1.07%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 47        | 1.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 44        | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                           | 43        | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 43        | 0.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 37        | 0.84%   |
| Intel HD Graphics 630                                                                    | 36        | 0.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 36        | 0.82%   |
| AMD Renoir                                                                               | 35        | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33        | 0.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 0.75%   |
| Intel HD Graphics 530                                                                    | 32        | 0.73%   |
| Intel HD Graphics 500                                                                    | 30        | 0.68%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 26        | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 24        | 0.54%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 24        | 0.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 0.54%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 24        | 0.54%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 23        | 0.52%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 23        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1782      | 47.52%  |
| 1 x AMD                  | 761       | 20.29%  |
| 1 x Nvidia               | 685       | 18.27%  |
| Intel + Nvidia           | 276       | 7.36%   |
| Intel + AMD              | 99        | 2.64%   |
| 2 x AMD                  | 58        | 1.55%   |
| AMD + Nvidia             | 28        | 0.75%   |
| 1 x SiS                  | 25        | 0.67%   |
| 1 x VIA                  | 16        | 0.43%   |
| 2 x Nvidia               | 7         | 0.19%   |
| 1 x Matrox               | 5         | 0.13%   |
| Other                    | 3         | 0.08%   |
| 2 x Intel                | 1         | 0.03%   |
| 1 x Trident Microsystems | 1         | 0.03%   |
| Nvidia + Silicon Motion  | 1         | 0.03%   |
| Nvidia + ASPEED          | 1         | 0.03%   |
| 1 x ASPEED               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3021      | 80.35%  |
| Proprietary | 544       | 14.47%  |
| Unknown     | 195       | 5.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2121      | 55.89%  |
| 0.01-0.5   | 603       | 15.89%  |
| 1.01-2.0   | 403       | 10.62%  |
| 0.51-1.0   | 335       | 8.83%   |
| 3.01-4.0   | 158       | 4.16%   |
| 7.01-8.0   | 87        | 2.29%   |
| 5.01-6.0   | 45        | 1.19%   |
| 8.01-16.0  | 23        | 0.61%   |
| 2.01-3.0   | 15        | 0.4%    |
| 16.01-24.0 | 4         | 0.11%   |
| 4.01-5.0   | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 543       | 14.79%  |
| AU Optronics            | 440       | 11.99%  |
| LG Display              | 341       | 9.29%   |
| Chimei Innolux          | 279       | 7.6%    |
| BOE                     | 236       | 6.43%   |
| Dell                    | 181       | 4.93%   |
| Goldstar                | 168       | 4.58%   |
| Hewlett-Packard         | 133       | 3.62%   |
| Acer                    | 102       | 2.78%   |
| Chi Mei Optoelectronics | 91        | 2.48%   |
| Apple                   | 81        | 2.21%   |
| AOC                     | 79        | 2.15%   |
| Philips                 | 75        | 2.04%   |
| LG Philips              | 62        | 1.69%   |
| Ancor Communications    | 60        | 1.63%   |
| BenQ                    | 59        | 1.61%   |
| Lenovo                  | 56        | 1.53%   |
| Sharp                   | 41        | 1.12%   |
| LG Electronics          | 35        | 0.95%   |
| InfoVision              | 34        | 0.93%   |
| ViewSonic               | 32        | 0.87%   |
| Unknown                 | 27        | 0.74%   |
| Sony                    | 26        | 0.71%   |
| Toshiba                 | 23        | 0.63%   |
| PANDA                   | 23        | 0.63%   |
| HannStar                | 23        | 0.63%   |
| Vizio                   | 22        | 0.6%    |
| Iiyama                  | 18        | 0.49%   |
| CPT                     | 17        | 0.46%   |
| Unknown                 | 16        | 0.44%   |
| Sceptre Tech            | 14        | 0.38%   |
| ASUSTek Computer        | 14        | 0.38%   |
| NEC Computers           | 13        | 0.35%   |
| Eizo                    | 12        | 0.33%   |
| Quanta Display          | 11        | 0.3%    |
| Fujitsu Siemens         | 11        | 0.3%    |
| Panasonic               | 10        | 0.27%   |
| LGD                     | 10        | 0.27%   |
| Gateway                 | 10        | 0.27%   |
| HPN                     | 9         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 25        | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.56%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.48%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 16        | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.42%   |
| Unknown                                                                  | 16        | 0.42%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 12        | 0.32%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 11        | 0.29%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch     | 10        | 0.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.27%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 10        | 0.27%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 9         | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 9         | 0.24%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.24%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 8         | 0.21%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 8         | 0.21%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 8         | 0.21%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 8         | 0.21%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 8         | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 7         | 0.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 7         | 0.19%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                         | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 7         | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 7         | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 7         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1169      | 32.45%  |
| 1366x768 (WXGA)    | 1003      | 27.85%  |
| 1600x900 (HD+)     | 216       | 6%      |
| 1280x800 (WXGA)    | 188       | 5.22%   |
| 3840x2160 (4K)     | 142       | 3.94%   |
| 1280x1024 (SXGA)   | 127       | 3.53%   |
| 1440x900 (WXGA+)   | 119       | 3.3%    |
| 1680x1050 (WSXGA+) | 107       | 2.97%   |
| 2560x1440 (QHD)    | 65        | 1.8%    |
| Unknown            | 63        | 1.75%   |
| 1920x1200 (WUXGA)  | 57        | 1.58%   |
| 1360x768           | 53        | 1.47%   |
| 1024x600           | 45        | 1.25%   |
| 3840x1080          | 23        | 0.64%   |
| 1024x768 (XGA)     | 22        | 0.61%   |
| 3440x1440          | 21        | 0.58%   |
| 2560x1080          | 19        | 0.53%   |
| 2560x1600          | 17        | 0.47%   |
| 1920x540           | 14        | 0.39%   |
| 2736x1824          | 9         | 0.25%   |
| 3200x1800 (QHD+)   | 7         | 0.19%   |
| 2256x1504          | 7         | 0.19%   |
| 1280x768           | 7         | 0.19%   |
| 5760x1080          | 6         | 0.17%   |
| 2160x1440          | 6         | 0.17%   |
| 3840x2400          | 5         | 0.14%   |
| 2880x1800          | 5         | 0.14%   |
| 1280x720 (HD)      | 5         | 0.14%   |
| 5760x2160          | 4         | 0.11%   |
| 4480x1440          | 4         | 0.11%   |
| 3600x1080          | 4         | 0.11%   |
| 1680x945           | 4         | 0.11%   |
| 1600x1200          | 4         | 0.11%   |
| 3840x1600          | 3         | 0.08%   |
| 2048x1152          | 3         | 0.08%   |
| 1400x1050          | 3         | 0.08%   |
| 1024x576           | 3         | 0.08%   |
| 6400x1440          | 2         | 0.06%   |
| 5440x1080          | 2         | 0.06%   |
| 3840x1200          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1014      | 27.82%  |
| Unknown | 335       | 9.19%   |
| 13      | 301       | 8.26%   |
| 14      | 270       | 7.41%   |
| 17      | 252       | 6.91%   |
| 27      | 158       | 4.33%   |
| 24      | 157       | 4.31%   |
| 23      | 152       | 4.17%   |
| 21      | 149       | 4.09%   |
| 19      | 112       | 3.07%   |
| 18      | 101       | 2.77%   |
| 11      | 80        | 2.19%   |
| 20      | 79        | 2.17%   |
| 12      | 66        | 1.81%   |
| 31      | 64        | 1.76%   |
| 22      | 63        | 1.73%   |
| 10      | 54        | 1.48%   |
| 34      | 35        | 0.96%   |
| 54      | 19        | 0.52%   |
| 84      | 18        | 0.49%   |
| 72      | 18        | 0.49%   |
| 40      | 17        | 0.47%   |
| 26      | 16        | 0.44%   |
| 32      | 15        | 0.41%   |
| 16      | 10        | 0.27%   |
| 52      | 8         | 0.22%   |
| 25      | 8         | 0.22%   |
| 74      | 5         | 0.14%   |
| 65      | 5         | 0.14%   |
| 49      | 5         | 0.14%   |
| 42      | 5         | 0.14%   |
| 29      | 5         | 0.14%   |
| 37      | 4         | 0.11%   |
| 36      | 4         | 0.11%   |
| 33      | 4         | 0.11%   |
| 8       | 4         | 0.11%   |
| 48      | 3         | 0.08%   |
| 46      | 3         | 0.08%   |
| 41      | 3         | 0.08%   |
| 28      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1467      | 40.7%   |
| 501-600     | 446       | 12.38%  |
| 401-500     | 443       | 12.29%  |
| 201-300     | 342       | 9.49%   |
| Unknown     | 335       | 9.3%    |
| 351-400     | 289       | 8.02%   |
| 601-700     | 87        | 2.41%   |
| 701-800     | 58        | 1.61%   |
| 1001-1500   | 53        | 1.47%   |
| 1501-2000   | 43        | 1.19%   |
| 801-900     | 25        | 0.69%   |
| 901-1000    | 12        | 0.33%   |
| 101-200     | 4         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2397      | 70.38%  |
| 16/10   | 475       | 13.95%  |
| Unknown | 298       | 8.75%   |
| 5/4     | 114       | 3.35%   |
| 21/9    | 39        | 1.15%   |
| 4/3     | 36        | 1.06%   |
| 3/2     | 31        | 0.91%   |
| 32/9    | 8         | 0.23%   |
| 6/5     | 5         | 0.15%   |
| 3.73    | 2         | 0.06%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1014      | 27.99%  |
| 81-90          | 461       | 12.72%  |
| 201-250        | 406       | 11.21%  |
| Unknown        | 335       | 9.25%   |
| 151-200        | 258       | 7.12%   |
| 301-350        | 161       | 4.44%   |
| 141-150        | 144       | 3.97%   |
| 121-130        | 135       | 3.73%   |
| 351-500        | 128       | 3.53%   |
| 71-80          | 108       | 2.98%   |
| More than 1000 | 87        | 2.4%    |
| 51-60          | 81        | 2.24%   |
| 251-300        | 70        | 1.93%   |
| 61-70          | 59        | 1.63%   |
| 131-140        | 56        | 1.55%   |
| 41-50          | 53        | 1.46%   |
| 501-1000       | 47        | 1.3%    |
| 91-100         | 9         | 0.25%   |
| 111-120        | 7         | 0.19%   |
| 1-40           | 4         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1172      | 33.14%  |
| 51-100        | 1138      | 32.17%  |
| 121-160       | 642       | 18.15%  |
| Unknown       | 335       | 9.47%   |
| 161-240       | 117       | 3.31%   |
| 1-50          | 96        | 2.71%   |
| More than 240 | 37        | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3176      | 83.8%   |
| 2     | 381       | 10.05%  |
| 0     | 198       | 5.22%   |
| 3     | 33        | 0.87%   |
| 4     | 2         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1974      | 33.76%  |
| Intel                             | 1443      | 24.68%  |
| Qualcomm Atheros                  | 797       | 13.63%  |
| Broadcom                          | 480       | 8.21%   |
| Broadcom Limited                  | 151       | 2.58%   |
| Marvell Technology Group          | 110       | 1.88%   |
| Ralink Technology                 | 103       | 1.76%   |
| Nvidia                            | 103       | 1.76%   |
| Ralink                            | 84        | 1.44%   |
| TP-Link                           | 64        | 1.09%   |
| Samsung Electronics               | 37        | 0.63%   |
| MediaTek                          | 30        | 0.51%   |
| Silicon Integrated Systems [SiS]  | 29        | 0.5%    |
| VIA Technologies                  | 27        | 0.46%   |
| ASIX Electronics                  | 26        | 0.44%   |
| Xiaomi                            | 25        | 0.43%   |
| NetGear                           | 23        | 0.39%   |
| D-Link                            | 23        | 0.39%   |
| D-Link System                     | 21        | 0.36%   |
| JMicron Technology                | 20        | 0.34%   |
| Qualcomm Atheros Communications   | 19        | 0.32%   |
| Huawei Technologies               | 18        | 0.31%   |
| DisplayLink                       | 17        | 0.29%   |
| Dell                              | 17        | 0.29%   |
| Edimax Technology                 | 16        | 0.27%   |
| ASUSTek Computer                  | 13        | 0.22%   |
| Sierra Wireless                   | 11        | 0.19%   |
| Microsoft                         | 11        | 0.19%   |
| Motorola PCS                      | 10        | 0.17%   |
| Hewlett-Packard                   | 10        | 0.17%   |
| OPPO Electronics                  | 9         | 0.15%   |
| Ericsson Business Mobile Networks | 8         | 0.14%   |
| Belkin Components                 | 7         | 0.12%   |
| AMD                               | 7         | 0.12%   |
| Qualcomm                          | 6         | 0.1%    |
| Linksys                           | 6         | 0.1%    |
| T & A Mobile Phones               | 5         | 0.09%   |
| Attansic Technology               | 5         | 0.09%   |
| Aquantia                          | 5         | 0.09%   |
| Sitecom Europe                    | 4         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1184      | 17.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 387       | 5.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 166       | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 130       | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 113       | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 104       | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 96        | 1.41%   |
| Intel Wireless 7260                                                     | 87        | 1.28%   |
| Intel Wi-Fi 6 AX200                                                     | 83        | 1.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 73        | 1.07%   |
| Realtek 802.11ac NIC                                                    | 73        | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 67        | 0.98%   |
| Intel Wireless 7265                                                     | 63        | 0.92%   |
| Intel Ethernet Connection I217-LM                                       | 61        | 0.9%    |
| Intel Wireless 8265 / 8275                                              | 60        | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 59        | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 58        | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 58        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 58        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 56        | 0.82%   |
| Intel Wireless 3165                                                     | 55        | 0.81%   |
| Intel I211 Gigabit Network Connection                                   | 50        | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 48        | 0.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 48        | 0.7%    |
| Ralink MT7601U Wireless Adapter                                         | 48        | 0.7%    |
| Intel Wireless 8260                                                     | 47        | 0.69%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 45        | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                       | 43        | 0.63%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 41        | 0.6%    |
| Intel Wi-Fi 6 AX201                                                     | 39        | 0.57%   |
| Nvidia MCP61 Ethernet                                                   | 38        | 0.56%   |
| Intel WiFi Link 5100                                                    | 38        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 35        | 0.51%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 31        | 0.46%   |
| Intel Ethernet Connection (2) I219-V                                    | 31        | 0.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 0.46%   |
| Intel Ethernet Connection I218-LM                                       | 27        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1043      | 32.82%  |
| Qualcomm Atheros                      | 634       | 19.95%  |
| Realtek Semiconductor                 | 594       | 18.69%  |
| Broadcom                              | 336       | 10.57%  |
| Ralink Technology                     | 103       | 3.24%   |
| Broadcom Limited                      | 98        | 3.08%   |
| Ralink                                | 84        | 2.64%   |
| TP-Link                               | 57        | 1.79%   |
| D-Link                                | 23        | 0.72%   |
| NetGear                               | 22        | 0.69%   |
| MediaTek                              | 22        | 0.69%   |
| Qualcomm Atheros Communications       | 19        | 0.6%    |
| D-Link System                         | 18        | 0.57%   |
| Edimax Technology                     | 16        | 0.5%    |
| Marvell Technology Group              | 13        | 0.41%   |
| ASUSTek Computer                      | 12        | 0.38%   |
| Sierra Wireless                       | 11        | 0.35%   |
| Microsoft                             | 10        | 0.31%   |
| Dell                                  | 8         | 0.25%   |
| Belkin Components                     | 7         | 0.22%   |
| Linksys                               | 6         | 0.19%   |
| Sitecom Europe                        | 4         | 0.13%   |
| Micro Star International              | 4         | 0.13%   |
| Gemtek                                | 4         | 0.13%   |
| ZyDAS                                 | 3         | 0.09%   |
| Hewlett-Packard                       | 3         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.09%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| Xiaomi                                | 2         | 0.06%   |
| TRENDnet                              | 2         | 0.06%   |
| Senao                                 | 2         | 0.06%   |
| IMC Networks                          | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Lite-On Technology                    | 1         | 0.03%   |
| Fibocom                               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 130       | 4.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 113       | 3.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 104       | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 96        | 3%      |
| Intel Wireless 7260                                                     | 87        | 2.72%   |
| Intel Wi-Fi 6 AX200                                                     | 83        | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 73        | 2.28%   |
| Realtek 802.11ac NIC                                                    | 73        | 2.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 67        | 2.09%   |
| Intel Wireless 7265                                                     | 63        | 1.97%   |
| Intel Wireless 8265 / 8275                                              | 60        | 1.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 59        | 1.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 58        | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 58        | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 56        | 1.75%   |
| Intel Wireless 3165                                                     | 55        | 1.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 48        | 1.5%    |
| Ralink MT7601U Wireless Adapter                                         | 48        | 1.5%    |
| Intel Wireless 8260                                                     | 47        | 1.47%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 45        | 1.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 41        | 1.28%   |
| Intel Wi-Fi 6 AX201                                                     | 39        | 1.22%   |
| Intel WiFi Link 5100                                                    | 38        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 1.09%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 31        | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 31        | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 27        | 0.84%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 26        | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 25        | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 25        | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 25        | 0.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 25        | 0.78%   |
| Intel Wireless 3160                                                     | 24        | 0.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 24        | 0.75%   |
| Intel Centrino Wireless-N 2230                                          | 23        | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 22        | 0.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 22        | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 21        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1736      | 50.07%  |
| Intel                                  | 765       | 22.07%  |
| Qualcomm Atheros                       | 238       | 6.86%   |
| Broadcom                               | 202       | 5.83%   |
| Nvidia                                 | 103       | 2.97%   |
| Marvell Technology Group               | 97        | 2.8%    |
| Broadcom Limited                       | 59        | 1.7%    |
| Samsung Electronics                    | 36        | 1.04%   |
| Silicon Integrated Systems [SiS]       | 28        | 0.81%   |
| VIA Technologies                       | 27        | 0.78%   |
| ASIX Electronics                       | 26        | 0.75%   |
| Xiaomi                                 | 23        | 0.66%   |
| JMicron Technology                     | 20        | 0.58%   |
| DisplayLink                            | 17        | 0.49%   |
| Huawei Technologies                    | 14        | 0.4%    |
| OPPO Electronics                       | 9         | 0.26%   |
| MediaTek                               | 8         | 0.23%   |
| TP-Link                                | 7         | 0.2%    |
| Motorola PCS                           | 7         | 0.2%    |
| Qualcomm                               | 5         | 0.14%   |
| Attansic Technology                    | 5         | 0.14%   |
| Aquantia                               | 5         | 0.14%   |
| Hewlett-Packard                        | 3         | 0.09%   |
| Davicom Semiconductor                  | 3         | 0.09%   |
| D-Link System                          | 3         | 0.09%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.06%   |
| Google                                 | 2         | 0.06%   |
| Apple                                  | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.03%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Sun Microsystems                       | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Research In Motion                     | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| Novatel Wireless                       | 1         | 0.03%   |
| NetGear                                | 1         | 0.03%   |
| Motorola BCS                           | 1         | 0.03%   |
| Lenovo                                 | 1         | 0.03%   |
| ICS Advent                             | 1         | 0.03%   |
| HMD Global                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1184      | 33.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 387       | 11.02%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 166       | 4.73%   |
| Intel Ethernet Connection I217-LM                                 | 61        | 1.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 58        | 1.65%   |
| Intel I211 Gigabit Network Connection                             | 50        | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 48        | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 43        | 1.22%   |
| Nvidia MCP61 Ethernet                                             | 38        | 1.08%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 35        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 31        | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 27        | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 27        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 26        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 24        | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 23        | 0.65%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 22        | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 22        | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 21        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 20        | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 19        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 19        | 0.54%   |
| Intel 82566MM Gigabit Network Connection                          | 19        | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 18        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 17        | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 17        | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 17        | 0.48%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 17        | 0.48%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 17        | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3278      | 51.88%  |
| WiFi     | 2943      | 46.57%  |
| Modem    | 85        | 1.35%   |
| Unknown  | 13        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2312      | 59.65%  |
| Ethernet | 1560      | 40.25%  |
| Modem    | 2         | 0.05%   |
| Unknown  | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2173      | 58.04%  |
| 1     | 1400      | 37.39%  |
| 0     | 113       | 3.02%   |
| 3     | 53        | 1.42%   |
| 5     | 3         | 0.08%   |
| 7     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3028      | 80.19%  |
| Yes  | 748       | 19.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 670       | 34.54%  |
| Realtek Semiconductor           | 221       | 11.39%  |
| Qualcomm Atheros Communications | 208       | 10.72%  |
| Broadcom                        | 150       | 7.73%   |
| Cambridge Silicon Radio         | 113       | 5.82%   |
| Apple                           | 91        | 4.69%   |
| IMC Networks                    | 87        | 4.48%   |
| Lite-On Technology              | 64        | 3.3%    |
| Dell                            | 56        | 2.89%   |
| Hewlett-Packard                 | 53        | 2.73%   |
| Foxconn / Hon Hai               | 49        | 2.53%   |
| ASUSTek Computer                | 32        | 1.65%   |
| Toshiba                         | 31        | 1.6%    |
| Ralink                          | 19        | 0.98%   |
| Realtek                         | 11        | 0.57%   |
| Alps Electric                   | 11        | 0.57%   |
| Marvell Semiconductor           | 10        | 0.52%   |
| Foxconn International           | 10        | 0.52%   |
| Dynex                           | 8         | 0.41%   |
| Integrated System Solution      | 6         | 0.31%   |
| Askey Computer                  | 6         | 0.31%   |
| MediaTek                        | 5         | 0.26%   |
| Taiyo Yuden                     | 4         | 0.21%   |
| Ralink Technology               | 4         | 0.21%   |
| Micro Star International        | 4         | 0.21%   |
| TP-Link                         | 3         | 0.15%   |
| Chicony Electronics             | 3         | 0.15%   |
| Belkin Components               | 3         | 0.15%   |
| Sitecom Europe                  | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| National Semiconductor          | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 320       | 16.49%  |
| Realtek Bluetooth Radio                             | 144       | 7.42%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 113       | 5.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 91        | 4.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 78        | 4.02%   |
| Intel AX201 Bluetooth                               | 75        | 3.86%   |
| Intel AX200 Bluetooth                               | 72        | 3.71%   |
| Realtek  Bluetooth 4.2 Adapter                      | 64        | 3.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 2.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 1.8%    |
| IMC Networks Bluetooth Device                       | 35        | 1.8%    |
| Apple Bluetooth Host Controller                     | 32        | 1.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 29        | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.39%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 25        | 1.29%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 1.29%   |
| IMC Networks Bluetooth Radio                        | 25        | 1.29%   |
| Apple Bluetooth USB Host Controller                 | 25        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                    | 24        | 1.24%   |
| Intel AX210 Bluetooth                               | 22        | 1.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 21        | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 1.08%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 20        | 1.03%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.98%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 18        | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 0.88%   |
| Apple Bluetooth HCI                                 | 16        | 0.82%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.77%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 14        | 0.72%   |
| Lite-On Bluetooth Device                            | 13        | 0.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.67%   |
| Dell DW375 Bluetooth Module                         | 13        | 0.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 13        | 0.67%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.62%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.62%   |
| Realtek Bluetooth Radio                             | 11        | 0.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 0.57%   |
| Foxconn International BCM43142A0 Bluetooth module   | 10        | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2712      | 56.94%  |
| AMD                                  | 953       | 20.01%  |
| Nvidia                               | 743       | 15.6%   |
| C-Media Electronics                  | 63        | 1.32%   |
| Silicon Integrated Systems [SiS]     | 31        | 0.65%   |
| VIA Technologies                     | 30        | 0.63%   |
| Creative Labs                        | 27        | 0.57%   |
| Logitech                             | 19        | 0.4%    |
| Texas Instruments                    | 15        | 0.31%   |
| JMTek                                | 13        | 0.27%   |
| GN Netcom                            | 11        | 0.23%   |
| Generalplus Technology               | 11        | 0.23%   |
| Kingston Technology                  | 9         | 0.19%   |
| Realtek Semiconductor                | 8         | 0.17%   |
| Tenx Technology                      | 7         | 0.15%   |
| Razer USA                            | 7         | 0.15%   |
| Plantronics                          | 7         | 0.15%   |
| Creative Technology                  | 7         | 0.15%   |
| SteelSeries ApS                      | 6         | 0.13%   |
| ASUSTek Computer                     | 6         | 0.13%   |
| Corsair                              | 4         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.06%   |
| Sennheiser Communications            | 3         | 0.06%   |
| Samsung Electronics                  | 3         | 0.06%   |
| Focusrite-Novation                   | 3         | 0.06%   |
| Yamaha                               | 2         | 0.04%   |
| Turtle Beach                         | 2         | 0.04%   |
| Numark                               | 2         | 0.04%   |
| Micronas                             | 2         | 0.04%   |
| Micro Star International             | 2         | 0.04%   |
| Klipsch Audio                        | 2         | 0.04%   |
| Ensoniq                              | 2         | 0.04%   |
| DigiTech                             | 2         | 0.04%   |
| AKAI Professional M.I.               | 2         | 0.04%   |
| ZOOM                                 | 1         | 0.02%   |
| XMOS                                 | 1         | 0.02%   |
| Valve Software                       | 1         | 0.02%   |
| Syntek                               | 1         | 0.02%   |
| Swissonic                            | 1         | 0.02%   |
| Sony                                 | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 313       | 5.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 276       | 4.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 256       | 4.56%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 226       | 4.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 190       | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 187       | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 184       | 3.28%   |
| AMD FCH Azalia Controller                                                                         | 171       | 3.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 157       | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 153       | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 136       | 2.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 121       | 2.16%   |
| Intel 8 Series HD Audio Controller                                                                | 116       | 2.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 112       | 2%      |
| AMD Starship/Matisse HD Audio Controller                                                          | 83        | 1.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 83        | 1.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 81        | 1.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 78        | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 78        | 1.39%   |
| Intel Broadwell-U Audio Controller                                                                | 69        | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 68        | 1.21%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 65        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 63        | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 61        | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 61        | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 59        | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 55        | 0.98%   |
| Nvidia High Definition Audio Controller                                                           | 51        | 0.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 49        | 0.87%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 47        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 46        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 46        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 44        | 0.78%   |
| AMD High Definition Audio Controller                                                              | 43        | 0.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 42        | 0.75%   |
| Nvidia MCP61 High Definition Audio                                                                | 39        | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 39        | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 37        | 0.66%   |
| AMD Trinity HDMI Audio Controller                                                                 | 37        | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 36        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 159       | 21.12%  |
| SK hynix            | 147       | 19.52%  |
| Unknown             | 105       | 13.94%  |
| Micron Technology   | 71        | 9.43%   |
| Kingston            | 68        | 9.03%   |
| Crucial             | 33        | 4.38%   |
| Corsair             | 24        | 3.19%   |
| G.Skill             | 22        | 2.92%   |
| Nanya Technology    | 17        | 2.26%   |
| Elpida              | 15        | 1.99%   |
| Unknown (ABCD)      | 14        | 1.86%   |
| Ramaxel Technology  | 13        | 1.73%   |
| A-DATA Technology   | 12        | 1.59%   |
| Team                | 6         | 0.8%    |
| Qimonda             | 6         | 0.8%    |
| Patriot             | 5         | 0.66%   |
| Smart               | 4         | 0.53%   |
| Transcend           | 2         | 0.27%   |
| Timetec             | 2         | 0.27%   |
| High Bridge         | 2         | 0.27%   |
| Unknown             | 2         | 0.27%   |
| Walton Chaintech    | 1         | 0.13%   |
| Unknown (08B5)      | 1         | 0.13%   |
| Unifosa             | 1         | 0.13%   |
| Toshiba             | 1         | 0.13%   |
| Teikon              | 1         | 0.13%   |
| Strontium           | 1         | 0.13%   |
| Smart Brazil        | 1         | 0.13%   |
| SHARETRONIC         | 1         | 0.13%   |
| Ramos Technology    | 1         | 0.13%   |
| PUSKILL             | 1         | 0.13%   |
| PNY                 | 1         | 0.13%   |
| Netlist             | 1         | 0.13%   |
| Nayna               | 1         | 0.13%   |
| Kingmax             | 1         | 0.13%   |
| HBS                 | 1         | 0.13%   |
| GSkill              | 1         | 0.13%   |
| Goldkey             | 1         | 0.13%   |
| F7852C80            | 1         | 0.13%   |
| Essencore           | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 12        | 1.49%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 7         | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.87%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 6         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.75%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.75%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.62%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 0.5%    |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.5%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.5%    |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 3         | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 3         | 0.37%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1066MT/s                  | 3         | 0.37%   |
| SK hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s          | 3         | 0.37%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.37%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.37%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 3         | 0.37%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 3         | 0.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.37%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.37%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s          | 3         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 254       | 39.14%  |
| DDR4    | 204       | 31.43%  |
| DDR2    | 77        | 11.86%  |
| SDRAM   | 32        | 4.93%   |
| LPDDR4  | 28        | 4.31%   |
| Unknown | 26        | 4.01%   |
| LPDDR3  | 14        | 2.16%   |
| DDR     | 8         | 1.23%   |
| DRAM    | 6         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 399       | 62.83%  |
| DIMM         | 191       | 30.08%  |
| Row Of Chips | 41        | 6.46%   |
| Chip         | 2         | 0.31%   |
| FB-DIMM      | 1         | 0.16%   |
| Unknown      | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 246       | 33.98%  |
| 8192  | 195       | 26.93%  |
| 2048  | 151       | 20.86%  |
| 1024  | 64        | 8.84%   |
| 16384 | 46        | 6.35%   |
| 512   | 12        | 1.66%   |
| 32768 | 8         | 1.1%    |
| 256   | 2         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 160       | 22.63%  |
| 2667    | 75        | 10.61%  |
| 3200    | 62        | 8.77%   |
| 1333    | 58        | 8.2%    |
| 667     | 39        | 5.52%   |
| 2400    | 37        | 5.23%   |
| Unknown | 34        | 4.81%   |
| 1334    | 30        | 4.24%   |
| 2133    | 28        | 3.96%   |
| 800     | 24        | 3.39%   |
| 1066    | 18        | 2.55%   |
| 3600    | 15        | 2.12%   |
| 3266    | 12        | 1.7%    |
| 533     | 11        | 1.56%   |
| 1867    | 10        | 1.41%   |
| 4267    | 9         | 1.27%   |
| 4199    | 9         | 1.27%   |
| 975     | 9         | 1.27%   |
| 2048    | 8         | 1.13%   |
| 3466    | 6         | 0.85%   |
| 1866    | 6         | 0.85%   |
| 400     | 6         | 0.85%   |
| 3000    | 4         | 0.57%   |
| 1800    | 4         | 0.57%   |
| 333     | 4         | 0.57%   |
| 8400    | 3         | 0.42%   |
| 1067    | 3         | 0.42%   |
| 3333    | 2         | 0.28%   |
| 2933    | 2         | 0.28%   |
| 2800    | 2         | 0.28%   |
| 2666    | 2         | 0.28%   |
| 1639    | 2         | 0.28%   |
| 49926   | 1         | 0.14%   |
| 4400    | 1         | 0.14%   |
| 4266    | 1         | 0.14%   |
| 4000    | 1         | 0.14%   |
| 3800    | 1         | 0.14%   |
| 3733    | 1         | 0.14%   |
| 3666    | 1         | 0.14%   |
| 3400    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 31        | 30.1%   |
| Canon                 | 24        | 23.3%   |
| Brother Industries    | 16        | 15.53%  |
| Samsung Electronics   | 13        | 12.62%  |
| Seiko Epson           | 11        | 10.68%  |
| STMicroelectronics    | 2         | 1.94%   |
| Zebra                 | 1         | 0.97%   |
| Toshiba TEC           | 1         | 0.97%   |
| Ricoh                 | 1         | 0.97%   |
| QinHeng Electronics   | 1         | 0.97%   |
| Pantum                | 1         | 0.97%   |
| Lexmark International | 1         | 0.97%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon TS3100 series                                       | 4         | 3.88%   |
| Seiko Epson L3110 Series                                  | 3         | 2.91%   |
| Canon PIXMA MG2500 Series                                 | 3         | 2.91%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.94%   |
| Samsung SCX-3400 Series                                   | 2         | 1.94%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.94%   |
| Samsung CLX-3300 Series                                   | 2         | 1.94%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.94%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.94%   |
| HP ENVY 5000 series                                       | 2         | 1.94%   |
| HP ENVY 4520 series                                       | 2         | 1.94%   |
| HP DeskJet 2700 series                                    | 2         | 1.94%   |
| HP DeskJet 1110 series                                    | 2         | 1.94%   |
| Canon PIXMA MX340                                         | 2         | 1.94%   |
| Canon MF4010 series                                       | 2         | 1.94%   |
| Brother HL-2130 series                                    | 2         | 1.94%   |
| Zebra ZP 450 Printer                                      | 1         | 0.97%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.97%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.97%   |
| Seiko Epson XP-202 203 206 Series                         | 1         | 0.97%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.97%   |
| Seiko Epson Printer                                       | 1         | 0.97%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.97%   |
| Seiko Epson L222 Series                                   | 1         | 0.97%   |
| Seiko Epson L120 Series                                   | 1         | 0.97%   |
| Seiko Epson ET-2820 Series                                | 1         | 0.97%   |
| Samsung SCX-483x 5x3x Series                              | 1         | 0.97%   |
| Samsung SCX-4200 series                                   | 1         | 0.97%   |
| Samsung ML-2950 Series                                    | 1         | 0.97%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 0.97%   |
| Samsung M2070 Series                                      | 1         | 0.97%   |
| Samsung M2020 Series                                      | 1         | 0.97%   |
| Samsung C460 Series                                       | 1         | 0.97%   |
| Ricoh SP C250SF                                           | 1         | 0.97%   |
| QinHeng CH340S                                            | 1         | 0.97%   |
| Pantum P2500W series                                      | 1         | 0.97%   |
| Lexmark International 2400 series                         | 1         | 0.97%   |
| HP Smart Tank 510 series                                  | 1         | 0.97%   |
| HP OfficeJet Pro 9010 series                              | 1         | 0.97%   |
| HP OfficeJet 4650 series                                  | 1         | 0.97%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 71.43%  |
| Seiko Epson     | 2         | 14.29%  |
| Hewlett-Packard | 2         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 14.29%  |
| Canon CanoScan LIDE 25                      | 2         | 14.29%  |
| Canon CanoScan LiDE 100                     | 2         | 14.29%  |
| HP ScanJet 2400c                            | 1         | 7.14%   |
| HP PSC 1200                                 | 1         | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 7.14%   |
| Canon CanoScan LiDE 90                      | 1         | 7.14%   |
| Canon CanoScan LiDE 60                      | 1         | 7.14%   |
| Canon CanoScan LiDE 110                     | 1         | 7.14%   |
| Canon CanoScan D660U                        | 1         | 7.14%   |
| Canon CanoScan 8800F                        | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 493       | 24.14%  |
| Microdia                               | 181       | 8.86%   |
| Realtek Semiconductor                  | 159       | 7.79%   |
| IMC Networks                           | 144       | 7.05%   |
| Acer                                   | 120       | 5.88%   |
| Sunplus Innovation Technology          | 104       | 5.09%   |
| Suyin                                  | 97        | 4.75%   |
| Cheng Uei Precision Industry (Foxlink) | 91        | 4.46%   |
| Apple                                  | 85        | 4.16%   |
| Quanta                                 | 68        | 3.33%   |
| Logitech                               | 62        | 3.04%   |
| Silicon Motion                         | 43        | 2.11%   |
| Syntek                                 | 42        | 2.06%   |
| Lite-On Technology                     | 36        | 1.76%   |
| Alcor Micro                            | 36        | 1.76%   |
| Ricoh                                  | 30        | 1.47%   |
| Samsung Electronics                    | 23        | 1.13%   |
| Microsoft                              | 19        | 0.93%   |
| Importek                               | 17        | 0.83%   |
| Luxvisions Innotech Limited            | 15        | 0.73%   |
| ALi                                    | 15        | 0.73%   |
| Primax Electronics                     | 13        | 0.64%   |
| Z-Star Microelectronics                | 12        | 0.59%   |
| GEMBIRD                                | 10        | 0.49%   |
| Generalplus Technology                 | 9         | 0.44%   |
| OmniVision Technologies                | 8         | 0.39%   |
| Lenovo                                 | 8         | 0.39%   |
| ARC International                      | 8         | 0.39%   |
| Sonix Technology                       | 7         | 0.34%   |
| Genesys Logic                          | 7         | 0.34%   |
| Unknown                                | 6         | 0.29%   |
| Sunplus Technology                     | 5         | 0.24%   |
| icSpring                               | 5         | 0.24%   |
| Cubeternet                             | 5         | 0.24%   |
| Jieli Technology                       | 4         | 0.2%    |
| Huawei Technologies                    | 4         | 0.2%    |
| SunplusIT                              | 3         | 0.15%   |
| Pixart Imaging                         | 3         | 0.15%   |
| LG Electronics                         | 3         | 0.15%   |
| Creative Technology                    | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 52        | 2.54%   |
| Microdia Integrated_Webcam_HD                    | 34        | 1.66%   |
| Realtek Integrated_Webcam_HD                     | 33        | 1.61%   |
| IMC Networks USB2.0 HD UVC WebCam                | 33        | 1.61%   |
| Chicony HD WebCam                                | 29        | 1.41%   |
| Chicony HP Truevision HD                         | 28        | 1.37%   |
| Microdia Integrated Webcam                       | 27        | 1.32%   |
| Chicony USB 2.0 Camera                           | 26        | 1.27%   |
| Acer Integrated Camera                           | 26        | 1.27%   |
| Apple FaceTime HD Camera (Built-in)              | 25        | 1.22%   |
| Apple iPhone5/5C/5S/6                            | 24        | 1.17%   |
| Acer Lenovo EasyCamera                           | 24        | 1.17%   |
| Samsung Galaxy A5 (MTP)                          | 23        | 1.12%   |
| Chicony TOSHIBA Web Camera - HD                  | 23        | 1.12%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 22        | 1.07%   |
| Realtek USB Camera                               | 21        | 1.02%   |
| Chicony HP TrueVision HD Camera                  | 21        | 1.02%   |
| Sunplus Integrated_Webcam_HD                     | 19        | 0.93%   |
| Logitech Webcam C270                             | 18        | 0.88%   |
| Chicony EasyCamera                               | 18        | 0.88%   |
| Apple Built-in iSight                            | 18        | 0.88%   |
| IMC Networks Integrated Camera                   | 17        | 0.83%   |
| Chicony Lenovo EasyCamera                        | 17        | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 17        | 0.83%   |
| Syntek Integrated Camera                         | 16        | 0.78%   |
| Realtek Integrated Webcam                        | 16        | 0.78%   |
| Chicony HP HD Webcam                             | 16        | 0.78%   |
| Alcor Micro SHUNCCM2MP                           | 16        | 0.78%   |
| Sunplus HD WebCam                                | 15        | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.73%   |
| Suyin HP Truevision HD                           | 14        | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 14        | 0.68%   |
| Quanta HP Webcam                                 | 14        | 0.68%   |
| Microdia Sonix USB 2.0 Camera                    | 14        | 0.68%   |
| Chicony CNF9055 Toshiba Webcam                   | 14        | 0.68%   |
| Quanta HP TrueVision HD Camera                   | 13        | 0.63%   |
| Chicony VGA WebCam                               | 13        | 0.63%   |
| Chicony USB2.0 HD UVC WebCam                     | 13        | 0.63%   |
| Chicony HP Webcam                                | 13        | 0.63%   |
| ALi Gateway Webcam                               | 13        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 147       | 44.14%  |
| AuthenTec                  | 52        | 15.62%  |
| Synaptics                  | 31        | 9.31%   |
| Shenzhen Goodix Technology | 29        | 8.71%   |
| Upek                       | 28        | 8.41%   |
| Elan Microelectronics      | 18        | 5.41%   |
| STMicroelectronics         | 17        | 5.11%   |
| LighTuning Technology      | 8         | 2.4%    |
| Samsung Electronics        | 2         | 0.6%    |
| Focal-systems.Corp         | 1         | 0.3%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 9.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 27        | 8.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 5.71%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 5.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 4.8%    |
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 4.8%    |
| AuthenTec AES2810                                                          | 16        | 4.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 4.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 4.5%    |
| Validity Sensors Fingerprint scanner                                       | 13        | 3.9%    |
| Unknown                                                                    | 12        | 3.6%    |
| Validity Sensors VFS491                                                    | 11        | 3.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 3%      |
| Elan ELAN:Fingerprint                                                      | 10        | 3%      |
| AuthenTec AES1600                                                          | 9         | 2.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.4%    |
| Elan ELAN:ARM-M4                                                           | 8         | 2.4%    |
| Synaptics  WBDI                                                            | 7         | 2.1%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 1.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.5%    |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.2%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.2%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1.2%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.9%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 0.9%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 0.9%    |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.9%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.9%    |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.6%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.6%    |
| LighTuning Fingerprint Reader                                              | 2         | 0.6%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.6%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.3%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.3%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 71        | 50%     |
| Alcor Micro                       | 23        | 16.2%   |
| O2 Micro                          | 20        | 14.08%  |
| Lenovo                            | 8         | 5.63%   |
| Upek                              | 7         | 4.93%   |
| Realtek Semiconductor             | 3         | 2.11%   |
| Yubico.com                        | 2         | 1.41%   |
| SCM Microsystems                  | 2         | 1.41%   |
| VASCO Data Security International | 1         | 0.7%    |
| Reiner SCT Kartensysteme          | 1         | 0.7%    |
| OmniKey                           | 1         | 0.7%    |
| Kobil Systems                     | 1         | 0.7%    |
| Fujitsu Siemens Computers         | 1         | 0.7%    |
| Advanced Card Systems             | 1         | 0.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 23.94%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 15.49%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 13.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 11.27%  |
| Broadcom 5880                                                                | 14        | 9.86%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 5.63%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.93%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.82%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.11%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.41%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.41%   |
| Broadcom 58200                                                               | 2         | 1.41%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.7%    |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.7%    |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.7%    |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.7%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.7%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.7%    |
| Advanced Card Systems ACR39U                                                 | 1         | 0.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2665      | 70.35%  |
| 1     | 921       | 24.31%  |
| 2     | 183       | 4.83%   |
| 3     | 16        | 0.42%   |
| 4     | 2         | 0.05%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 328       | 25.19%  |
| Graphics card            | 311       | 23.89%  |
| Net/wireless             | 230       | 17.67%  |
| Chipcard                 | 132       | 10.14%  |
| Multimedia controller    | 95        | 7.3%    |
| Modem                    | 37        | 2.84%   |
| Communication controller | 37        | 2.84%   |
| Storage                  | 34        | 2.61%   |
| Bluetooth                | 25        | 1.92%   |
| Sound                    | 16        | 1.23%   |
| Camera                   | 13        | 1%      |
| Unassigned class         | 10        | 0.77%   |
| Flash memory             | 10        | 0.77%   |
| Net/ethernet             | 6         | 0.46%   |
| Card reader              | 4         | 0.31%   |
| Storage/ide              | 3         | 0.23%   |
| Network                  | 3         | 0.23%   |
| Storage/raid             | 2         | 0.15%   |
| Storage/nvme             | 2         | 0.15%   |
| Dvb card                 | 2         | 0.15%   |
| Unclassified device      | 1         | 0.08%   |
| Storage/ata              | 1         | 0.08%   |


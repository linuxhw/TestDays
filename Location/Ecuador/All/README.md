Linux in Ecuador - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ecuador/Desktop/README.md) and [notebooks](/Location/Ecuador/Notebook/README.md).

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

Total: 613

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B550M-HDV                   | Desktop     | [580197f54a](https://linux-hardware.org/?probe=580197f54a) | Dec 31, 2025 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [f6e4512df5](https://linux-hardware.org/?probe=f6e4512df5) | Dec 30, 2025 |
| HP            | Pavilion g4                 | Notebook    | [c1a1b34ecc](https://linux-hardware.org/?probe=c1a1b34ecc) | Dec 25, 2025 |
| Notebook      | NH5xAx                      | Notebook    | [4f6c01dbca](https://linux-hardware.org/?probe=4f6c01dbca) | Dec 16, 2025 |
| ASUSTek       | G73Jw                       | Notebook    | [fc5996b06a](https://linux-hardware.org/?probe=fc5996b06a) | Dec 13, 2025 |
| ASUSTek       | G73Jw                       | Notebook    | [e85f6e2840](https://linux-hardware.org/?probe=e85f6e2840) | Dec 13, 2025 |
| Google        | Robo                        | Notebook    | [18939a9871](https://linux-hardware.org/?probe=18939a9871) | Dec 10, 2025 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [f881baea49](https://linux-hardware.org/?probe=f881baea49) | Dec 10, 2025 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [9afae0ee95](https://linux-hardware.org/?probe=9afae0ee95) | Dec 06, 2025 |
| HP            | Pavilion g4                 | Notebook    | [df34fc3443](https://linux-hardware.org/?probe=df34fc3443) | Dec 06, 2025 |
| HP            | Pavilion 14                 | Notebook    | [ad9bffe3b3](https://linux-hardware.org/?probe=ad9bffe3b3) | Nov 28, 2025 |
| MSI           | Thin 15 B13UC               | Notebook    | [6776dfcf29](https://linux-hardware.org/?probe=6776dfcf29) | Nov 26, 2025 |
| Gigabyte      | B75M-D3H                    | Desktop     | [ebf87f29b8](https://linux-hardware.org/?probe=ebf87f29b8) | Nov 19, 2025 |
| MSI           | Stealth GS77 12UE           | Notebook    | [34c2f9b0a8](https://linux-hardware.org/?probe=34c2f9b0a8) | Nov 17, 2025 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [df8020df97](https://linux-hardware.org/?probe=df8020df97) | Nov 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [9c74bf8f67](https://linux-hardware.org/?probe=9c74bf8f67) | Nov 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [dd03deae7a](https://linux-hardware.org/?probe=dd03deae7a) | Nov 09, 2025 |
| Unknown       | Intel X79                   | Desktop     | [595ba96f97](https://linux-hardware.org/?probe=595ba96f97) | Oct 30, 2025 |
| Acer          | Predator PH315-51           | Notebook    | [29baa91dd5](https://linux-hardware.org/?probe=29baa91dd5) | Oct 26, 2025 |
| Unknown       | Unknown                     | Notebook    | [65635ebccb](https://linux-hardware.org/?probe=65635ebccb) | Oct 25, 2025 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [e4dd68c427](https://linux-hardware.org/?probe=e4dd68c427) | Oct 19, 2025 |
| Toshiba       | Satellite L50-B             | Notebook    | [e15338ac63](https://linux-hardware.org/?probe=e15338ac63) | Oct 16, 2025 |
| ASRock        | B450 Steel Legend           | Desktop     | [5caa64c2a3](https://linux-hardware.org/?probe=5caa64c2a3) | Oct 14, 2025 |
| HP            | 18E7                        | Desktop     | [fa4df28929](https://linux-hardware.org/?probe=fa4df28929) | Oct 12, 2025 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [29c498aaab](https://linux-hardware.org/?probe=29c498aaab) | Oct 11, 2025 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [844e31335b](https://linux-hardware.org/?probe=844e31335b) | Oct 11, 2025 |
| Google        | Setzer                      | Notebook    | [59d6153e0f](https://linux-hardware.org/?probe=59d6153e0f) | Oct 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [d19b7e2930](https://linux-hardware.org/?probe=d19b7e2930) | Oct 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [76d8cd8e4d](https://linux-hardware.org/?probe=76d8cd8e4d) | Oct 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [15deadc7ba](https://linux-hardware.org/?probe=15deadc7ba) | Oct 03, 2025 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [4fc627f17d](https://linux-hardware.org/?probe=4fc627f17d) | Sep 23, 2025 |
| Dell          | 06X1TJ A00                  | Desktop     | [90fd996649](https://linux-hardware.org/?probe=90fd996649) | Sep 22, 2025 |
| Dell          | Unidentified System         | Notebook    | [30626f4bfe](https://linux-hardware.org/?probe=30626f4bfe) | Sep 21, 2025 |
| MSI           | B250M BAZOOKA               | Desktop     | [7539217654](https://linux-hardware.org/?probe=7539217654) | Sep 11, 2025 |
| Dell          | Inspiron 5547               | Notebook    | [090c9ddad9](https://linux-hardware.org/?probe=090c9ddad9) | Sep 09, 2025 |
| Unknown       | Unknown                     | Notebook    | [b8528a3d1d](https://linux-hardware.org/?probe=b8528a3d1d) | Sep 06, 2025 |
| Dell          | 06X1TJ A00                  | Desktop     | [f5c85043a4](https://linux-hardware.org/?probe=f5c85043a4) | Aug 29, 2025 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d7c635558a](https://linux-hardware.org/?probe=d7c635558a) | Aug 26, 2025 |
| Lenovo        | ThinkPad P16 Gen 2 21FA0... | Notebook    | [f607ea28bc](https://linux-hardware.org/?probe=f607ea28bc) | Aug 24, 2025 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a1a0884b8b](https://linux-hardware.org/?probe=a1a0884b8b) | Aug 09, 2025 |
| ASUSTek       | GL502VS                     | Notebook    | [0cfd13b331](https://linux-hardware.org/?probe=0cfd13b331) | Aug 04, 2025 |
| HP            | Compaq Presario CQ40        | Notebook    | [a8f55661e6](https://linux-hardware.org/?probe=a8f55661e6) | Aug 04, 2025 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [f85b5a4fe2](https://linux-hardware.org/?probe=f85b5a4fe2) | Jul 31, 2025 |
| Gigabyte      | A520M DS3H V2               | Desktop     | [b7960ef963](https://linux-hardware.org/?probe=b7960ef963) | Jul 28, 2025 |
| Intel         | X99                         | Desktop     | [3e8cec12fd](https://linux-hardware.org/?probe=3e8cec12fd) | Jul 20, 2025 |
| ASRock        | B450M Pro4-F                | Desktop     | [58fa834d77](https://linux-hardware.org/?probe=58fa834d77) | Jul 14, 2025 |
| HP            | Stream Notebook PC 13       | Notebook    | [a26dcc7e8b](https://linux-hardware.org/?probe=a26dcc7e8b) | Jul 05, 2025 |
| Dell          | 06X1TJ A00                  | Desktop     | [b8fe9f0ff2](https://linux-hardware.org/?probe=b8fe9f0ff2) | Jun 30, 2025 |
| System76      | Pangolin                    | Notebook    | [7aadbc0b69](https://linux-hardware.org/?probe=7aadbc0b69) | Jun 30, 2025 |
| HP            | ProBook 450 G3              | Notebook    | [a1839d8ce8](https://linux-hardware.org/?probe=a1839d8ce8) | Jun 29, 2025 |
| Dell          | Latitude 5500               | Notebook    | [7fe46a5914](https://linux-hardware.org/?probe=7fe46a5914) | Jun 23, 2025 |
| Dell          | Latitude 5500               | Notebook    | [801b8856dc](https://linux-hardware.org/?probe=801b8856dc) | Jun 19, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [8370a3f2fa](https://linux-hardware.org/?probe=8370a3f2fa) | Jun 17, 2025 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [6f0c47f77c](https://linux-hardware.org/?probe=6f0c47f77c) | Jun 15, 2025 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [ad11de04f2](https://linux-hardware.org/?probe=ad11de04f2) | Jun 15, 2025 |
| Sony          | VPCEG25FL                   | Notebook    | [d110c6abee](https://linux-hardware.org/?probe=d110c6abee) | Jun 14, 2025 |
| Lenovo        | ThinkPad X220 42872WS       | Notebook    | [735deb0809](https://linux-hardware.org/?probe=735deb0809) | Jun 03, 2025 |
| Dell          | Inspiron 15 3525            | Notebook    | [0b27f4ec6e](https://linux-hardware.org/?probe=0b27f4ec6e) | Jun 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [3b9eb0d1f8](https://linux-hardware.org/?probe=3b9eb0d1f8) | May 28, 2025 |
| Dell          | Inspiron 5547               | Notebook    | [97208d54f8](https://linux-hardware.org/?probe=97208d54f8) | May 27, 2025 |
| Dell          | 0F3KHR A00                  | Desktop     | [926bd6bbd7](https://linux-hardware.org/?probe=926bd6bbd7) | May 26, 2025 |
| ASRock        | A520M-HVS                   | Desktop     | [eeb2a8eba9](https://linux-hardware.org/?probe=eeb2a8eba9) | May 26, 2025 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c2b6c378a0](https://linux-hardware.org/?probe=c2b6c378a0) | May 17, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [130b97292b](https://linux-hardware.org/?probe=130b97292b) | May 15, 2025 |
| Dell          | 06X1TJ A00                  | Desktop     | [5c2f0139d5](https://linux-hardware.org/?probe=5c2f0139d5) | May 11, 2025 |
| ASUSTek       | E202SA                      | Notebook    | [425064df68](https://linux-hardware.org/?probe=425064df68) | May 09, 2025 |
| HP            | Compaq 6730s                | Notebook    | [96bd92d6f0](https://linux-hardware.org/?probe=96bd92d6f0) | May 06, 2025 |
| Dell          | Inspiron 5547               | Notebook    | [9b2ef80964](https://linux-hardware.org/?probe=9b2ef80964) | May 05, 2025 |
| Dell          | Inspiron 14-3467            | Notebook    | [bf2355ffc1](https://linux-hardware.org/?probe=bf2355ffc1) | May 05, 2025 |
| Dell          | Inspiron 14-3467            | Notebook    | [070c57d0ef](https://linux-hardware.org/?probe=070c57d0ef) | Apr 30, 2025 |
| GPU Compan... | GWTN141-10                  | Notebook    | [4a3702a1da](https://linux-hardware.org/?probe=4a3702a1da) | Apr 25, 2025 |
| HP            | ENVY m6 Notebook            | Notebook    | [e1e9dc0d89](https://linux-hardware.org/?probe=e1e9dc0d89) | Apr 21, 2025 |
| HP            | 2B1B                        | Desktop     | [5384700322](https://linux-hardware.org/?probe=5384700322) | Apr 20, 2025 |
| Dell          | Inspiron 3185               | Notebook    | [1f523e5dc3](https://linux-hardware.org/?probe=1f523e5dc3) | Apr 19, 2025 |
| HP            | 1000                        | Notebook    | [525b9bb521](https://linux-hardware.org/?probe=525b9bb521) | Apr 18, 2025 |
| Dell          | Inspiron 3501               | Notebook    | [7b341170e4](https://linux-hardware.org/?probe=7b341170e4) | Apr 16, 2025 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [9196e30cb7](https://linux-hardware.org/?probe=9196e30cb7) | Apr 12, 2025 |
| ASRock        | B450M Pro4-F                | Desktop     | [fe54220ead](https://linux-hardware.org/?probe=fe54220ead) | Apr 11, 2025 |
| HP            | 3397                        | Desktop     | [1f2fe94d4a](https://linux-hardware.org/?probe=1f2fe94d4a) | Apr 02, 2025 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [33acc6f19a](https://linux-hardware.org/?probe=33acc6f19a) | Mar 24, 2025 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [5deefdc949](https://linux-hardware.org/?probe=5deefdc949) | Mar 24, 2025 |
| ASUSTek       | FX503VD                     | Notebook    | [ee6ef151ae](https://linux-hardware.org/?probe=ee6ef151ae) | Mar 23, 2025 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | Notebook    | [d28a6d121b](https://linux-hardware.org/?probe=d28a6d121b) | Mar 21, 2025 |
| HP            | Pavilion dv5                | Notebook    | [743b1c6a08](https://linux-hardware.org/?probe=743b1c6a08) | Mar 16, 2025 |
| Dell          | Inspiron 15 5510            | Notebook    | [6ea0e9c2eb](https://linux-hardware.org/?probe=6ea0e9c2eb) | Mar 12, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c769caad0e](https://linux-hardware.org/?probe=c769caad0e) | Mar 12, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2f49c786af](https://linux-hardware.org/?probe=2f49c786af) | Mar 12, 2025 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [1d61cb08e5](https://linux-hardware.org/?probe=1d61cb08e5) | Mar 05, 2025 |
| Lenovo        | ThinkPad T450 20BUS2RN09    | Notebook    | [f09c87a871](https://linux-hardware.org/?probe=f09c87a871) | Mar 03, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [667e4486a6](https://linux-hardware.org/?probe=667e4486a6) | Feb 26, 2025 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [5fab8982a9](https://linux-hardware.org/?probe=5fab8982a9) | Feb 21, 2025 |
| Biostar       | H61MLB                      | Desktop     | [cca3895d08](https://linux-hardware.org/?probe=cca3895d08) | Feb 09, 2025 |
| Acer          | Aspire A315-44P             | Notebook    | [1978b4be35](https://linux-hardware.org/?probe=1978b4be35) | Feb 08, 2025 |
| ASRock        | B460M Pro4                  | Desktop     | [3740934825](https://linux-hardware.org/?probe=3740934825) | Feb 07, 2025 |
| Foxconn       | H55MXV Series               | Desktop     | [7c25d7d98d](https://linux-hardware.org/?probe=7c25d7d98d) | Feb 05, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [902eebca03](https://linux-hardware.org/?probe=902eebca03) | Feb 05, 2025 |
| HP            | ProBook 4440s               | Notebook    | [d9e21d83a4](https://linux-hardware.org/?probe=d9e21d83a4) | Jan 30, 2025 |
| HP            | 843B                        | Desktop     | [56c4841a76](https://linux-hardware.org/?probe=56c4841a76) | Jan 29, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [ecbc053b77](https://linux-hardware.org/?probe=ecbc053b77) | Jan 25, 2025 |
| HP            | ProBook 440 G7              | Notebook    | [91b1fe70a1](https://linux-hardware.org/?probe=91b1fe70a1) | Jan 23, 2025 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0U... | Notebook    | [c9c83d8b45](https://linux-hardware.org/?probe=c9c83d8b45) | Jan 20, 2025 |
| ASUSTek       | X455LJ                      | Notebook    | [1b26882393](https://linux-hardware.org/?probe=1b26882393) | Jan 20, 2025 |
| Lenovo        | ThinkPad T480 20L6S3RVUS    | Notebook    | [7f87f4d08f](https://linux-hardware.org/?probe=7f87f4d08f) | Jan 20, 2025 |
| HP            | Notebook                    | Notebook    | [6f33e3c4b9](https://linux-hardware.org/?probe=6f33e3c4b9) | Jan 19, 2025 |
| Lenovo        | Yoga 7 2-in-1 14IML9 83D... | Convertible | [8b7dbbd8e9](https://linux-hardware.org/?probe=8b7dbbd8e9) | Jan 18, 2025 |
| ASUSTek       | X455LJ                      | Notebook    | [dae3d540f6](https://linux-hardware.org/?probe=dae3d540f6) | Dec 18, 2024 |
| ASUSTek       | E202SA                      | Notebook    | [b4fe788f4e](https://linux-hardware.org/?probe=b4fe788f4e) | Dec 17, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [204aaa19ef](https://linux-hardware.org/?probe=204aaa19ef) | Dec 13, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [c70be6f167](https://linux-hardware.org/?probe=c70be6f167) | Dec 04, 2024 |
| Dell          | Latitude E6440              | Notebook    | [2c75de8400](https://linux-hardware.org/?probe=2c75de8400) | Dec 01, 2024 |
| ASUSTek       | E202SA                      | Notebook    | [18a63b065d](https://linux-hardware.org/?probe=18a63b065d) | Nov 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2264ba28f3](https://linux-hardware.org/?probe=2264ba28f3) | Oct 24, 2024 |
| Dell          | Latitude E6420              | Notebook    | [007ca74afb](https://linux-hardware.org/?probe=007ca74afb) | Oct 21, 2024 |
| Dell          | Latitude E6420              | Notebook    | [a6a2d8c1fe](https://linux-hardware.org/?probe=a6a2d8c1fe) | Oct 20, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5820bd151b](https://linux-hardware.org/?probe=5820bd151b) | Oct 17, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [479b6dd12a](https://linux-hardware.org/?probe=479b6dd12a) | Oct 16, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [9b61bff954](https://linux-hardware.org/?probe=9b61bff954) | Oct 16, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [47f24a1302](https://linux-hardware.org/?probe=47f24a1302) | Oct 13, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0b81ce4446](https://linux-hardware.org/?probe=0b81ce4446) | Oct 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [90af0212ea](https://linux-hardware.org/?probe=90af0212ea) | Sep 27, 2024 |
| Dell          | 0F3KHR A00                  | Desktop     | [0293193b5e](https://linux-hardware.org/?probe=0293193b5e) | Sep 26, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3be9ed3045](https://linux-hardware.org/?probe=3be9ed3045) | Sep 15, 2024 |
| Dell          | Inspiron 3458               | Notebook    | [79c31f85e1](https://linux-hardware.org/?probe=79c31f85e1) | Sep 13, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b00cab52d1](https://linux-hardware.org/?probe=b00cab52d1) | Sep 05, 2024 |
| Dell          | 0VV4V0 A00                  | All in one  | [078a22f745](https://linux-hardware.org/?probe=078a22f745) | Sep 03, 2024 |
| HP            | Pavilion g4                 | Notebook    | [c9131e779e](https://linux-hardware.org/?probe=c9131e779e) | Aug 24, 2024 |
| Unknown       | Unknown                     | Notebook    | [bbbbf2ec13](https://linux-hardware.org/?probe=bbbbf2ec13) | Aug 13, 2024 |
| Acer          | Swift SFE16-43              | Notebook    | [083b0cac5f](https://linux-hardware.org/?probe=083b0cac5f) | Aug 12, 2024 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [cf835ce8d2](https://linux-hardware.org/?probe=cf835ce8d2) | Aug 11, 2024 |
| HP            | Notebook                    | Notebook    | [1a796d1daf](https://linux-hardware.org/?probe=1a796d1daf) | Aug 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [32d11d630e](https://linux-hardware.org/?probe=32d11d630e) | Aug 01, 2024 |
| Biostar       | H61MLB                      | Desktop     | [10f695fe18](https://linux-hardware.org/?probe=10f695fe18) | Jul 31, 2024 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [f50ff2bcfb](https://linux-hardware.org/?probe=f50ff2bcfb) | Jul 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [5cd2fdb7f3](https://linux-hardware.org/?probe=5cd2fdb7f3) | Jul 23, 2024 |
| ASRock        | B650M PG Riptide            | Desktop     | [2672901369](https://linux-hardware.org/?probe=2672901369) | Jul 22, 2024 |
| HP            | Pavilion g4                 | Notebook    | [922cae179f](https://linux-hardware.org/?probe=922cae179f) | Jul 13, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [c802131da8](https://linux-hardware.org/?probe=c802131da8) | Jul 07, 2024 |
| ASUSTek       | TP410UAR                    | Convertible | [fb5a78c205](https://linux-hardware.org/?probe=fb5a78c205) | Jul 05, 2024 |
| Dell          | Vostro 5502                 | Notebook    | [02acef5e70](https://linux-hardware.org/?probe=02acef5e70) | Jul 04, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [92ca1f097e](https://linux-hardware.org/?probe=92ca1f097e) | Jun 30, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [d139897a73](https://linux-hardware.org/?probe=d139897a73) | Jun 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [6fb2ca786a](https://linux-hardware.org/?probe=6fb2ca786a) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [f5baa7dc23](https://linux-hardware.org/?probe=f5baa7dc23) | Jun 19, 2024 |
| Toshiba       | Satellite P855              | Notebook    | [e3c736f4b8](https://linux-hardware.org/?probe=e3c736f4b8) | Jun 18, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [5d77f14b5f](https://linux-hardware.org/?probe=5d77f14b5f) | Jun 18, 2024 |
| Toshiba       | Satellite P855              | Notebook    | [71b541e230](https://linux-hardware.org/?probe=71b541e230) | Jun 16, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [4852045434](https://linux-hardware.org/?probe=4852045434) | Jun 08, 2024 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [e33f8a4718](https://linux-hardware.org/?probe=e33f8a4718) | Jun 01, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d447330673](https://linux-hardware.org/?probe=d447330673) | Jun 01, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [ca35abddb1](https://linux-hardware.org/?probe=ca35abddb1) | May 30, 2024 |
| Lenovo        | V330-14ISK 81AY             | Notebook    | [fd2bdae039](https://linux-hardware.org/?probe=fd2bdae039) | May 24, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0U... | Notebook    | [630273772a](https://linux-hardware.org/?probe=630273772a) | May 19, 2024 |
| Acer          | Aspire V5-471P              | Notebook    | [00d54a6432](https://linux-hardware.org/?probe=00d54a6432) | May 13, 2024 |
| Acer          | Aspire V5-471P              | Notebook    | [d9b4f36303](https://linux-hardware.org/?probe=d9b4f36303) | May 13, 2024 |
| HP            | 8299                        | Desktop     | [6024274be6](https://linux-hardware.org/?probe=6024274be6) | May 06, 2024 |
| ECS           | H61H2-TI                    | All in one  | [6a421efdca](https://linux-hardware.org/?probe=6a421efdca) | May 01, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [a823e9adf2](https://linux-hardware.org/?probe=a823e9adf2) | Apr 26, 2024 |
| Pegatron      | 2AA1h                       | Desktop     | [52b3bc466c](https://linux-hardware.org/?probe=52b3bc466c) | Apr 25, 2024 |
| HP            | 1000                        | Notebook    | [dee2aa2dd9](https://linux-hardware.org/?probe=dee2aa2dd9) | Apr 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [d4f3102f5c](https://linux-hardware.org/?probe=d4f3102f5c) | Apr 25, 2024 |
| MSI           | Stealth GS77 12UE           | Notebook    | [47ff584537](https://linux-hardware.org/?probe=47ff584537) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [39dff10b12](https://linux-hardware.org/?probe=39dff10b12) | Apr 08, 2024 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [cdfa410878](https://linux-hardware.org/?probe=cdfa410878) | Apr 05, 2024 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [9e4b6c171a](https://linux-hardware.org/?probe=9e4b6c171a) | Apr 04, 2024 |
| Intel         | H55                         | Desktop     | [361d690313](https://linux-hardware.org/?probe=361d690313) | Mar 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a95e92f1f5](https://linux-hardware.org/?probe=a95e92f1f5) | Mar 16, 2024 |
| Dell          | G15 5515                    | Notebook    | [527be515b4](https://linux-hardware.org/?probe=527be515b4) | Mar 12, 2024 |
| Toshiba       | Satellite P855              | Notebook    | [cb7eb1810c](https://linux-hardware.org/?probe=cb7eb1810c) | Feb 26, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [68bbab3ac1](https://linux-hardware.org/?probe=68bbab3ac1) | Feb 19, 2024 |
| Google        | Blooglet                    | Notebook    | [66b986a87d](https://linux-hardware.org/?probe=66b986a87d) | Feb 19, 2024 |
| HP            | 245 G8                      | Notebook    | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Google        | Blooglet                    | Notebook    | [34a54def3d](https://linux-hardware.org/?probe=34a54def3d) | Feb 13, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [f4f20111f0](https://linux-hardware.org/?probe=f4f20111f0) | Feb 12, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [f9989aa45a](https://linux-hardware.org/?probe=f9989aa45a) | Feb 09, 2024 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [21be6e4ab5](https://linux-hardware.org/?probe=21be6e4ab5) | Feb 07, 2024 |
| ASUSTek       | H110M-D                     | Desktop     | [7f2b907eb8](https://linux-hardware.org/?probe=7f2b907eb8) | Jan 25, 2024 |
| Dell          | Latitude D630               | Notebook    | [bf9ce8c208](https://linux-hardware.org/?probe=bf9ce8c208) | Jan 21, 2024 |
| Dell          | Latitude D630               | Notebook    | [b2a68014db](https://linux-hardware.org/?probe=b2a68014db) | Jan 21, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [c6ba3badcb](https://linux-hardware.org/?probe=c6ba3badcb) | Jan 18, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [342f21a2ff](https://linux-hardware.org/?probe=342f21a2ff) | Jan 18, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [3a14a938f8](https://linux-hardware.org/?probe=3a14a938f8) | Jan 08, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [186230d9c6](https://linux-hardware.org/?probe=186230d9c6) | Jan 08, 2024 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [f8466df8c5](https://linux-hardware.org/?probe=f8466df8c5) | Dec 26, 2023 |
| HP            | 1000                        | Notebook    | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [cc934b68d9](https://linux-hardware.org/?probe=cc934b68d9) | Nov 22, 2023 |
| HP            | Unknown                     | Notebook    | [d065dfae65](https://linux-hardware.org/?probe=d065dfae65) | Nov 19, 2023 |
| HP            | Unknown                     | Notebook    | [539958ff9d](https://linux-hardware.org/?probe=539958ff9d) | Nov 19, 2023 |
| MSI           | PRO H610M-G DDR4            | Notebook    | [5955e4e776](https://linux-hardware.org/?probe=5955e4e776) | Nov 15, 2023 |
| MSI           | PRO H610M-G DDR4            | Notebook    | [f41807e01e](https://linux-hardware.org/?probe=f41807e01e) | Nov 14, 2023 |
| Toshiba       | Satellite S55-B             | Notebook    | [bcc2e19a3a](https://linux-hardware.org/?probe=bcc2e19a3a) | Nov 12, 2023 |
| HP            | 245 G8                      | Notebook    | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | Notebook    | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | 245 G8                      | Notebook    | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Razer         | Blade Stealth               | Notebook    | [0ebbfdba6a](https://linux-hardware.org/?probe=0ebbfdba6a) | Oct 26, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [21a31e5298](https://linux-hardware.org/?probe=21a31e5298) | Oct 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [46e4f7a743](https://linux-hardware.org/?probe=46e4f7a743) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Alienware     | m15                         | Notebook    | [9ac9acc336](https://linux-hardware.org/?probe=9ac9acc336) | Oct 12, 2023 |
| Alienware     | m15                         | Notebook    | [8b4a8c8fc9](https://linux-hardware.org/?probe=8b4a8c8fc9) | Oct 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [7b78b2ea5b](https://linux-hardware.org/?probe=7b78b2ea5b) | Oct 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9b1cc15d8a](https://linux-hardware.org/?probe=9b1cc15d8a) | Sep 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e2c6027a51](https://linux-hardware.org/?probe=e2c6027a51) | Sep 30, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [8c1d3fc469](https://linux-hardware.org/?probe=8c1d3fc469) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [c38ca27643](https://linux-hardware.org/?probe=c38ca27643) | Sep 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [f4582a5754](https://linux-hardware.org/?probe=f4582a5754) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5fac0d7732](https://linux-hardware.org/?probe=5fac0d7732) | Sep 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [09c45a1e2d](https://linux-hardware.org/?probe=09c45a1e2d) | Sep 17, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | Notebook    | [eb0aa53dc9](https://linux-hardware.org/?probe=eb0aa53dc9) | Sep 08, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | Notebook    | [ecc10a1197](https://linux-hardware.org/?probe=ecc10a1197) | Sep 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [9dd40cd022](https://linux-hardware.org/?probe=9dd40cd022) | Sep 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a1caab6466](https://linux-hardware.org/?probe=a1caab6466) | Aug 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [5c8f4ac5c0](https://linux-hardware.org/?probe=5c8f4ac5c0) | Aug 16, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | Desktop     | [5df6fee2f9](https://linux-hardware.org/?probe=5df6fee2f9) | Aug 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5bd12768fa](https://linux-hardware.org/?probe=5bd12768fa) | Aug 09, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [5bd6d0c2d8](https://linux-hardware.org/?probe=5bd6d0c2d8) | Jul 20, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [d80699b846](https://linux-hardware.org/?probe=d80699b846) | Jul 13, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [602c50a904](https://linux-hardware.org/?probe=602c50a904) | Jul 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Biostar       | H61MGV3                     | Desktop     | [109f8064f6](https://linux-hardware.org/?probe=109f8064f6) | Jun 21, 2023 |
| Intel         | DG35EC AAE29266-209         | Desktop     | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | Desktop     | [3e5a0aac78](https://linux-hardware.org/?probe=3e5a0aac78) | Jun 19, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Dell          | Inspiron 3493               | Notebook    | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f661806559](https://linux-hardware.org/?probe=f661806559) | Jun 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [a57949da97](https://linux-hardware.org/?probe=a57949da97) | Jun 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e365621d30](https://linux-hardware.org/?probe=e365621d30) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | Notebook    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| Acer          | Extensa 5220                | Notebook    | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [1f232288d7](https://linux-hardware.org/?probe=1f232288d7) | May 07, 2023 |
| Sony          | VPCEG23EL                   | Notebook    | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [76674fb178](https://linux-hardware.org/?probe=76674fb178) | Apr 26, 2023 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [5cb6709055](https://linux-hardware.org/?probe=5cb6709055) | Apr 20, 2023 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d7d0bcde76](https://linux-hardware.org/?probe=d7d0bcde76) | Apr 15, 2023 |
| Biostar       | H81MHV3L                    | Desktop     | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| HP            | Notebook                    | Notebook    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| HP            | 245 G6                      | Notebook    | [c6a1e2951c](https://linux-hardware.org/?probe=c6a1e2951c) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [078e440a68](https://linux-hardware.org/?probe=078e440a68) | Mar 31, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [1812fe9a19](https://linux-hardware.org/?probe=1812fe9a19) | Mar 26, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [a302d93972](https://linux-hardware.org/?probe=a302d93972) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9e45f992a1](https://linux-hardware.org/?probe=9e45f992a1) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [34fd631d2b](https://linux-hardware.org/?probe=34fd631d2b) | Mar 22, 2023 |
| Samsung       | R519/R719                   | Notebook    | [9e1cdf3582](https://linux-hardware.org/?probe=9e1cdf3582) | Mar 17, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Dell          | 014GRG A01                  | Desktop     | [2e7b556001](https://linux-hardware.org/?probe=2e7b556001) | Mar 05, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [0cf17a3787](https://linux-hardware.org/?probe=0cf17a3787) | Feb 27, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5bf68a313d](https://linux-hardware.org/?probe=5bf68a313d) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [72d2220b42](https://linux-hardware.org/?probe=72d2220b42) | Feb 07, 2023 |
| Google        | Setzer                      | Notebook    | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [85dbbce597](https://linux-hardware.org/?probe=85dbbce597) | Jan 27, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [b4d38fb35a](https://linux-hardware.org/?probe=b4d38fb35a) | Jan 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| Gateway       | NV55C                       | Notebook    | [b8ae4adfdc](https://linux-hardware.org/?probe=b8ae4adfdc) | Jan 12, 2023 |
| Lenovo        | 300e 2nd Gen 81M9           | Convertible | [d36b6385d2](https://linux-hardware.org/?probe=d36b6385d2) | Jan 11, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [d7abd06e34](https://linux-hardware.org/?probe=d7abd06e34) | Jan 08, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [aa67834a96](https://linux-hardware.org/?probe=aa67834a96) | Jan 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [93adad7445](https://linux-hardware.org/?probe=93adad7445) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf4ba78c7d](https://linux-hardware.org/?probe=cf4ba78c7d) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | Notebook    | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [296edfbde5](https://linux-hardware.org/?probe=296edfbde5) | Dec 22, 2022 |
| Dynabook      | PORTEGE X40-J               | Notebook    | [3f1fc426b0](https://linux-hardware.org/?probe=3f1fc426b0) | Dec 05, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Gateway       | NV510P                      | Notebook    | [13fe5a5e78](https://linux-hardware.org/?probe=13fe5a5e78) | Oct 16, 2022 |
| Gateway       | NV510P                      | Notebook    | [7cb93d25ac](https://linux-hardware.org/?probe=7cb93d25ac) | Oct 16, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [71a25274d7](https://linux-hardware.org/?probe=71a25274d7) | Oct 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [ea7b836323](https://linux-hardware.org/?probe=ea7b836323) | Oct 08, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [6b528465e2](https://linux-hardware.org/?probe=6b528465e2) | Sep 20, 2022 |
| HP            | 8768 A                      | Desktop     | [dd63bfb225](https://linux-hardware.org/?probe=dd63bfb225) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fbe2b37462](https://linux-hardware.org/?probe=fbe2b37462) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | Notebook                    | Notebook    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [eaab7f2460](https://linux-hardware.org/?probe=eaab7f2460) | Aug 09, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [6e9be54f47](https://linux-hardware.org/?probe=6e9be54f47) | Jul 09, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Google        | Delbin                      | Notebook    | [26becdfc83](https://linux-hardware.org/?probe=26becdfc83) | Jun 26, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c434320a62](https://linux-hardware.org/?probe=c434320a62) | Jun 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [70d24e4237](https://linux-hardware.org/?probe=70d24e4237) | Jun 02, 2022 |
| ASUSTek       | UX360CA                     | Notebook    | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| Alienware     | 15 R3                       | Notebook    | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Sony          | SVE14113ELW                 | Notebook    | [647c09a7be](https://linux-hardware.org/?probe=647c09a7be) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [ec5867b2f7](https://linux-hardware.org/?probe=ec5867b2f7) | May 17, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [9b06242456](https://linux-hardware.org/?probe=9b06242456) | May 17, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [e559318a8b](https://linux-hardware.org/?probe=e559318a8b) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C                      | Desktop     | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [e049bbd414](https://linux-hardware.org/?probe=e049bbd414) | Apr 26, 2022 |
| Biostar       | G41D3C                      | Desktop     | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| HP            | Unknown                     | Notebook    | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| HP            | Unknown                     | Notebook    | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| Google        | Panther                     | Desktop     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | Desktop     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| Sony          | VPCEG30EL                   | Notebook    | [c19f1a4739](https://linux-hardware.org/?probe=c19f1a4739) | Mar 26, 2022 |
| Sony          | SVE14A25CLB                 | Notebook    | [2e6afba454](https://linux-hardware.org/?probe=2e6afba454) | Mar 25, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Dell          | Inspiron 7547               | Notebook    | [af0de64399](https://linux-hardware.org/?probe=af0de64399) | Mar 22, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [faae36d70e](https://linux-hardware.org/?probe=faae36d70e) | Mar 17, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4d5aa250a1](https://linux-hardware.org/?probe=4d5aa250a1) | Mar 17, 2022 |
| TrekStor      | Primebook C13               | Convertible | [2c908202fc](https://linux-hardware.org/?probe=2c908202fc) | Mar 17, 2022 |
| Toshiba       | Satellite C55D-A            | Notebook    | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [bd4f7daadb](https://linux-hardware.org/?probe=bd4f7daadb) | Mar 10, 2022 |
| Compal        | PBL2021                     | Notebook    | [4e367db737](https://linux-hardware.org/?probe=4e367db737) | Feb 28, 2022 |
| Intel         | H81                         | Desktop     | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | Desktop     | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Dell          | G5 5587                     | Notebook    | [5f51492976](https://linux-hardware.org/?probe=5f51492976) | Jan 29, 2022 |
| Dell          | Latitude 7280               | Notebook    | [fdf5a41dcc](https://linux-hardware.org/?probe=fdf5a41dcc) | Jan 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [b4c6f2fe35](https://linux-hardware.org/?probe=b4c6f2fe35) | Jan 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d8fc419747](https://linux-hardware.org/?probe=d8fc419747) | Jan 18, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ddd3544bcf](https://linux-hardware.org/?probe=ddd3544bcf) | Jan 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fbd40dba79](https://linux-hardware.org/?probe=fbd40dba79) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f2ba12e1f](https://linux-hardware.org/?probe=9f2ba12e1f) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [82281b42b0](https://linux-hardware.org/?probe=82281b42b0) | Dec 29, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [ef48db912e](https://linux-hardware.org/?probe=ef48db912e) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Google        | Treeya                      | Notebook    | [a0ab206cd8](https://linux-hardware.org/?probe=a0ab206cd8) | Nov 09, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [d6ed71bc78](https://linux-hardware.org/?probe=d6ed71bc78) | Nov 02, 2021 |
| HP            | G42                         | Notebook    | [5ee39658a8](https://linux-hardware.org/?probe=5ee39658a8) | Oct 28, 2021 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d31c8b483c](https://linux-hardware.org/?probe=d31c8b483c) | Oct 28, 2021 |
| HP            | G42                         | Notebook    | [a8181c9c9b](https://linux-hardware.org/?probe=a8181c9c9b) | Oct 24, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [177f79d880](https://linux-hardware.org/?probe=177f79d880) | Oct 18, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [2297765c40](https://linux-hardware.org/?probe=2297765c40) | Oct 14, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [6257ee6ddd](https://linux-hardware.org/?probe=6257ee6ddd) | Oct 07, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [5972d02719](https://linux-hardware.org/?probe=5972d02719) | Oct 07, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [2307619c77](https://linux-hardware.org/?probe=2307619c77) | Sep 27, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [d4cd8cbc7e](https://linux-hardware.org/?probe=d4cd8cbc7e) | Sep 27, 2021 |
| Foxconn       | H61MXL-K                    | Desktop     | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [449fdc2d2d](https://linux-hardware.org/?probe=449fdc2d2d) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Toshiba       | Satellite S55-B             | Notebook    | [c4ec7d25a7](https://linux-hardware.org/?probe=c4ec7d25a7) | Aug 21, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [008647318c](https://linux-hardware.org/?probe=008647318c) | Aug 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [5de2d0ae61](https://linux-hardware.org/?probe=5de2d0ae61) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| Acer          | TravelMate X3410-M          | Notebook    | [18b5757039](https://linux-hardware.org/?probe=18b5757039) | Jul 29, 2021 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [a071db12c9](https://linux-hardware.org/?probe=a071db12c9) | Jul 12, 2021 |
| Google        | Banjo                       | Notebook    | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Google        | Grunt                       | Notebook    | [2bb0921a94](https://linux-hardware.org/?probe=2bb0921a94) | Jul 01, 2021 |
| Google        | Grunt                       | Notebook    | [4ea5c8f438](https://linux-hardware.org/?probe=4ea5c8f438) | Jul 01, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| Google        | Kip                         | Notebook    | [7634152b76](https://linux-hardware.org/?probe=7634152b76) | Jun 21, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [a5fc625cf2](https://linux-hardware.org/?probe=a5fc625cf2) | Jun 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| HP            | 1000                        | Notebook    | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | 1000                        | Notebook    | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| Acer          | Aspire V5-121               | Notebook    | [cc73e2b026](https://linux-hardware.org/?probe=cc73e2b026) | May 13, 2021 |
| HP            | 1000                        | Notebook    | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| Lenovo        | ThinkPad E15 20REA00000     | Notebook    | [1ac42dd429](https://linux-hardware.org/?probe=1ac42dd429) | May 09, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| ASRock        | B550M-HDV                   | Desktop     | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Dell          | G5 5587                     | Notebook    | [c88e053304](https://linux-hardware.org/?probe=c88e053304) | Apr 07, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [0ba2e43e56](https://linux-hardware.org/?probe=0ba2e43e56) | Mar 24, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [7b12363b97](https://linux-hardware.org/?probe=7b12363b97) | Mar 04, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Dell          | Inspiron 7375               | Notebook    | [eea996c7d4](https://linux-hardware.org/?probe=eea996c7d4) | Feb 26, 2021 |
| Shuttle       | SFM27 V20                   | Desktop     | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [35cc521571](https://linux-hardware.org/?probe=35cc521571) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [2162db2610](https://linux-hardware.org/?probe=2162db2610) | Feb 03, 2021 |
| Sony          | VPCCW1S1E                   | Notebook    | [f57d56b50e](https://linux-hardware.org/?probe=f57d56b50e) | Jan 31, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f4e1001265](https://linux-hardware.org/?probe=f4e1001265) | Jan 23, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [063b008ad5](https://linux-hardware.org/?probe=063b008ad5) | Jan 15, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [473e0472d5](https://linux-hardware.org/?probe=473e0472d5) | Jan 12, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [5a7277af8b](https://linux-hardware.org/?probe=5a7277af8b) | Jan 08, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [bbbf68f88b](https://linux-hardware.org/?probe=bbbf68f88b) | Jan 08, 2021 |
| Google        | Parrot                      | Notebook    | [a3a6c2f819](https://linux-hardware.org/?probe=a3a6c2f819) | Jan 04, 2021 |
| Google        | Parrot                      | Notebook    | [55b807260c](https://linux-hardware.org/?probe=55b807260c) | Jan 04, 2021 |
| HP            | Pavilion 14                 | Notebook    | [91b047b61a](https://linux-hardware.org/?probe=91b047b61a) | Dec 31, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3f61162824](https://linux-hardware.org/?probe=3f61162824) | Dec 07, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [e5dab19c0f](https://linux-hardware.org/?probe=e5dab19c0f) | Dec 05, 2020 |
| Intel         | DP55KG AAE47218-404         | Desktop     | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| HP            | ProBook 4440s               | Notebook    | [b4747f87a1](https://linux-hardware.org/?probe=b4747f87a1) | Nov 24, 2020 |
| Dell          | Inspiron 1750               | Notebook    | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [364a814fd0](https://linux-hardware.org/?probe=364a814fd0) | Nov 19, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [b0fbbd8176](https://linux-hardware.org/?probe=b0fbbd8176) | Nov 19, 2020 |
| HP            | 3115m                       | Notebook    | [1ae9651614](https://linux-hardware.org/?probe=1ae9651614) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [106453a877](https://linux-hardware.org/?probe=106453a877) | Oct 23, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [fea6f132fa](https://linux-hardware.org/?probe=fea6f132fa) | Oct 23, 2020 |
| Toshiba       | PORTEGE M805                | Notebook    | [cacfe4abd9](https://linux-hardware.org/?probe=cacfe4abd9) | Oct 22, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [146545f430](https://linux-hardware.org/?probe=146545f430) | Oct 17, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [61e809ea3a](https://linux-hardware.org/?probe=61e809ea3a) | Oct 12, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6353946b7e](https://linux-hardware.org/?probe=6353946b7e) | Oct 12, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [03631f1005](https://linux-hardware.org/?probe=03631f1005) | Oct 08, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [78e7085775](https://linux-hardware.org/?probe=78e7085775) | Oct 08, 2020 |
| MSI           | B75A-G43                    | Desktop     | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43                    | Desktop     | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Toshiba       | Satellite C45-A             | Notebook    | [2774da64f6](https://linux-hardware.org/?probe=2774da64f6) | Sep 18, 2020 |
| HP            | Pavilion 15                 | Notebook    | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP            | Mini 210-1100               | Notebook    | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| HP            | 1497                        | Desktop     | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [40aeea62f1](https://linux-hardware.org/?probe=40aeea62f1) | Sep 13, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [489cee4d9a](https://linux-hardware.org/?probe=489cee4d9a) | Sep 12, 2020 |
| Toshiba       | Satellite P775              | Notebook    | [d71ccb1065](https://linux-hardware.org/?probe=d71ccb1065) | Sep 10, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [8626b52852](https://linux-hardware.org/?probe=8626b52852) | Sep 08, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [c3f5f6d566](https://linux-hardware.org/?probe=c3f5f6d566) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4e0f1689a3](https://linux-hardware.org/?probe=4e0f1689a3) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [8eb7cfa128](https://linux-hardware.org/?probe=8eb7cfa128) | Sep 05, 2020 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1b11abd994](https://linux-hardware.org/?probe=1b11abd994) | Sep 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [21f0c0015c](https://linux-hardware.org/?probe=21f0c0015c) | Aug 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [29f01daf9e](https://linux-hardware.org/?probe=29f01daf9e) | Aug 26, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [e39ccc961c](https://linux-hardware.org/?probe=e39ccc961c) | Aug 20, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Convertible | [1f4ef5bb49](https://linux-hardware.org/?probe=1f4ef5bb49) | Aug 19, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [dd8aa75b79](https://linux-hardware.org/?probe=dd8aa75b79) | Aug 16, 2020 |
| ASUSTek       | X502CA                      | Notebook    | [7876d4c48d](https://linux-hardware.org/?probe=7876d4c48d) | Aug 14, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9bcbc98b0f](https://linux-hardware.org/?probe=9bcbc98b0f) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [c32745014a](https://linux-hardware.org/?probe=c32745014a) | Jul 22, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a70d38c48c](https://linux-hardware.org/?probe=a70d38c48c) | Jul 20, 2020 |
| Acer          | AO722                       | Notebook    | [90943ce018](https://linux-hardware.org/?probe=90943ce018) | Jul 10, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [e4318a8dea](https://linux-hardware.org/?probe=e4318a8dea) | Jul 04, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [ba6d8528e9](https://linux-hardware.org/?probe=ba6d8528e9) | Jul 04, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | Notebook                    | Notebook    | [b646ab05a7](https://linux-hardware.org/?probe=b646ab05a7) | Jun 30, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [853f76e35e](https://linux-hardware.org/?probe=853f76e35e) | Jun 23, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b8b588701d](https://linux-hardware.org/?probe=b8b588701d) | Jun 22, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [87e6d2f056](https://linux-hardware.org/?probe=87e6d2f056) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [7332f612bc](https://linux-hardware.org/?probe=7332f612bc) | May 30, 2020 |
| HP            | ProBook 4440s               | Notebook    | [5442b989be](https://linux-hardware.org/?probe=5442b989be) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [15c3385fcd](https://linux-hardware.org/?probe=15c3385fcd) | May 30, 2020 |
| Biostar       | H81MLV3                     | Desktop     | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [84339f57da](https://linux-hardware.org/?probe=84339f57da) | May 09, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Apple         | MacBookPro13,3              | Notebook    | [81946cb76f](https://linux-hardware.org/?probe=81946cb76f) | Apr 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [df8a7bcad8](https://linux-hardware.org/?probe=df8a7bcad8) | Mar 26, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| HP            | 15                          | Notebook    | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP            | 15                          | Notebook    | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Acer          | AO722                       | Notebook    | [08d71a347b](https://linux-hardware.org/?probe=08d71a347b) | Feb 29, 2020 |
| Acer          | AO722                       | Notebook    | [291cea2763](https://linux-hardware.org/?probe=291cea2763) | Feb 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [5ae0871de5](https://linux-hardware.org/?probe=5ae0871de5) | Feb 23, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [cfc85f91d5](https://linux-hardware.org/?probe=cfc85f91d5) | Feb 22, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [ab03f678e6](https://linux-hardware.org/?probe=ab03f678e6) | Feb 22, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b37b6efdf7](https://linux-hardware.org/?probe=b37b6efdf7) | Feb 18, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [f8c6ef3229](https://linux-hardware.org/?probe=f8c6ef3229) | Feb 17, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0893b14338](https://linux-hardware.org/?probe=0893b14338) | Feb 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d2b7a56172](https://linux-hardware.org/?probe=d2b7a56172) | Jan 14, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [30baa09d89](https://linux-hardware.org/?probe=30baa09d89) | Jan 14, 2020 |
| Acer          | Aspire ES1-131              | Notebook    | [fcb74db0f2](https://linux-hardware.org/?probe=fcb74db0f2) | Jan 14, 2020 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Dell          | System XPS L502X            | Notebook    | [d43cf2a533](https://linux-hardware.org/?probe=d43cf2a533) | Sep 12, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a4264e7371](https://linux-hardware.org/?probe=a4264e7371) | Sep 12, 2019 |
| HP            | 18E7                        | Desktop     | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| Toshiba       | Satellite E45t-B            | Notebook    | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Toshiba       | Satellite P55W-C            | Notebook    | [cc12571867](https://linux-hardware.org/?probe=cc12571867) | Jul 27, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [76dbbe880b](https://linux-hardware.org/?probe=76dbbe880b) | Jul 10, 2019 |
| HP            | Pavilion 14                 | Notebook    | [6dde2ab979](https://linux-hardware.org/?probe=6dde2ab979) | Jun 08, 2019 |
| Apple         | MacBook1,1                  | Notebook    | [57ca5e1449](https://linux-hardware.org/?probe=57ca5e1449) | Jun 02, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a4d0b9a0cc](https://linux-hardware.org/?probe=a4d0b9a0cc) | May 27, 2019 |
| Dell          | 0CRH6C A02                  | Desktop     | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6abf9ea94e](https://linux-hardware.org/?probe=6abf9ea94e) | Apr 17, 2019 |
| HP            | ENVY Notebook               | Notebook    | [4d812e744e](https://linux-hardware.org/?probe=4d812e744e) | Apr 17, 2019 |
| Cartimex      | H61H2-MV                    | Desktop     | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ecuador/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 41        | 8.95%   |
| Ubuntu 22.04                 | 23        | 5.02%   |
| Ubuntu 18.04                 | 22        | 4.8%    |
| Ubuntu 24.04                 | 16        | 3.49%   |
| Zorin 17                     | 15        | 3.28%   |
| Debian 12                    | 12        | 2.62%   |
| Debian 11                    | 12        | 2.62%   |
| OpenMandriva 4.3             | 9         | 1.97%   |
| Arch Rolling                 | 9         | 1.97%   |
| Linux Mint 20.3              | 8         | 1.75%   |
| Fedora 38                    | 8         | 1.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 1.53%   |
| Linux Mint 21.1              | 7         | 1.53%   |
| Zorin 16                     | 6         | 1.31%   |
| OpenMandriva 24.12           | 6         | 1.31%   |
| KDE neon 20.04               | 6         | 1.31%   |
| Pop!_OS 22.04                | 5         | 1.09%   |
| OpenMandriva 5.0             | 5         | 1.09%   |
| Linux Mint 19.3              | 5         | 1.09%   |
| Fedora 36                    | 5         | 1.09%   |
| Fedora 34                    | 5         | 1.09%   |
| Zorin 15                     | 4         | 0.87%   |
| Ubuntu 23.10                 | 4         | 0.87%   |
| Pop!_OS 21.10                | 4         | 0.87%   |
| Pop!_OS 21.04                | 4         | 0.87%   |
| OpenMandriva 4.2             | 4         | 0.87%   |
| OpenMandriva 25.90           | 4         | 0.87%   |
| OpenMandriva 23.03           | 4         | 0.87%   |
| LMDE 4                       | 4         | 0.87%   |
| Fedora 41                    | 4         | 0.87%   |
| Fedora 37                    | 4         | 0.87%   |
| Fedora 33                    | 4         | 0.87%   |
| EndeavourOS Rolling          | 4         | 0.87%   |
| ArcoLinux Rolling            | 4         | 0.87%   |
| Zorin 18                     | 3         | 0.66%   |
| Ubuntu 22.10                 | 3         | 0.66%   |
| Ubuntu 21.10                 | 3         | 0.66%   |
| Pop!_OS 20.04                | 3         | 0.66%   |
| OpenMandriva 6.0             | 3         | 0.66%   |
| OpenMandriva 23.01           | 3         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 118       | 26.76%  |
| OpenMandriva  | 44        | 9.98%   |
| Linux Mint    | 41        | 9.3%    |
| Fedora        | 41        | 9.3%    |
| Debian        | 29        | 6.58%   |
| Zorin         | 28        | 6.35%   |
| Pop!_OS       | 17        | 3.85%   |
| Arch          | 12        | 2.72%   |
| Manjaro       | 9         | 2.04%   |
| KDE neon      | 9         | 2.04%   |
| openSUSE      | 8         | 1.81%   |
| LMDE          | 8         | 1.81%   |
| Lubuntu       | 7         | 1.59%   |
| Elementary    | 7         | 1.59%   |
| Xubuntu       | 6         | 1.36%   |
| Kali          | 5         | 1.13%   |
| Kubuntu       | 4         | 0.91%   |
| EndeavourOS   | 4         | 0.91%   |
| ArcoLinux     | 4         | 0.91%   |
| Ubuntu MATE   | 3         | 0.68%   |
| Garuda Linux  | 3         | 0.68%   |
| CentOS        | 3         | 0.68%   |
| CachyOS       | 3         | 0.68%   |
| Bazzite       | 3         | 0.68%   |
| Void Linux    | 2         | 0.45%   |
| Ubuntu Budgie | 2         | 0.45%   |
| SteamOS       | 2         | 0.45%   |
| Nobara        | 2         | 0.45%   |
| Endless       | 2         | 0.45%   |
| Clear Linux   | 2         | 0.45%   |
| BlackPanther  | 2         | 0.45%   |
| XeroG         | 1         | 0.23%   |
| Xero          | 1         | 0.23%   |
| ROSA          | 1         | 0.23%   |
| RHEL          | 1         | 0.23%   |
| Peppermint    | 1         | 0.23%   |
| Parrot        | 1         | 0.23%   |
| MX            | 1         | 0.23%   |
| Linux Lite    | 1         | 0.23%   |
| Deepin        | 1         | 0.23%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 8         | 1.64%   |
| 6.14.2-desktop-3omv2590  | 7         | 1.44%   |
| 5.4.0-54-generic         | 6         | 1.23%   |
| 6.8.0-57-generic         | 5         | 1.03%   |
| 6.6.2-desktop-1omv2390   | 5         | 1.03%   |
| 6.12.1-desktop-1omv2490  | 5         | 1.03%   |
| 5.4.0-42-generic         | 5         | 1.03%   |
| 5.15.0-56-generic        | 5         | 1.03%   |
| 5.13.0-35-generic        | 5         | 1.03%   |
| 6.8.0-31-generic         | 4         | 0.82%   |
| 6.5.0-35-generic         | 4         | 0.82%   |
| 5.4.0-45-generic         | 4         | 0.82%   |
| 5.15.0-33-generic        | 4         | 0.82%   |
| 5.10.14-desktop-1omv4002 | 4         | 0.82%   |
| 6.9.3-76060903-generic   | 3         | 0.62%   |
| 6.8.0-59-generic         | 3         | 0.62%   |
| 6.5.0-41-generic         | 3         | 0.62%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.62%   |
| 6.14.0-36-generic        | 3         | 0.62%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.62%   |
| 6.1.0-13-amd64           | 3         | 0.62%   |
| 5.8.0-41-generic         | 3         | 0.62%   |
| 5.4.0-7634-generic       | 3         | 0.62%   |
| 5.4.0-58-generic         | 3         | 0.62%   |
| 5.4.0-56-generic         | 3         | 0.62%   |
| 5.4.0-48-generic         | 3         | 0.62%   |
| 5.4.0-37-generic         | 3         | 0.62%   |
| 5.4.0-26-generic         | 3         | 0.62%   |
| 5.16.11-76051611-generic | 3         | 0.62%   |
| 5.13.0-7614-generic      | 3         | 0.62%   |
| 5.0.0-37-generic         | 3         | 0.62%   |
| 5.0.0-23-generic         | 3         | 0.62%   |
| 6.8.0-60-generic         | 2         | 0.41%   |
| 6.8.0-47-generic         | 2         | 0.41%   |
| 6.5.0-26-generic         | 2         | 0.41%   |
| 6.5.0-14-generic         | 2         | 0.41%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.41%   |
| 6.2.15-300.fc38.x86_64   | 2         | 0.41%   |
| 6.2.0-33-generic         | 2         | 0.41%   |
| 6.17.0-3-cachyos         | 2         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 57        | 12.23%  |
| 5.15.0  | 34        | 7.3%    |
| 6.8.0   | 25        | 5.36%   |
| 6.5.0   | 21        | 4.51%   |
| 5.13.0  | 19        | 4.08%   |
| 4.15.0  | 18        | 3.86%   |
| 6.1.0   | 15        | 3.22%   |
| 5.8.0   | 12        | 2.58%   |
| 6.14.0  | 11        | 2.36%   |
| 5.10.0  | 10        | 2.15%   |
| 6.14.2  | 9         | 1.93%   |
| 5.16.7  | 9         | 1.93%   |
| 5.11.0  | 9         | 1.93%   |
| 5.0.0   | 9         | 1.93%   |
| 5.19.0  | 7         | 1.5%    |
| 6.11.0  | 6         | 1.29%   |
| 5.3.0   | 6         | 1.29%   |
| 6.6.2   | 5         | 1.07%   |
| 6.2.0   | 5         | 1.07%   |
| 6.12.9  | 5         | 1.07%   |
| 6.12.1  | 5         | 1.07%   |
| 5.10.14 | 4         | 0.86%   |
| 6.9.3   | 3         | 0.64%   |
| 6.2.6   | 3         | 0.64%   |
| 6.17.0  | 3         | 0.64%   |
| 6.1.1   | 3         | 0.64%   |
| 5.17.5  | 3         | 0.64%   |
| 5.16.11 | 3         | 0.64%   |
| 4.19.0  | 3         | 0.64%   |
| 4.18.0  | 3         | 0.64%   |
| 3.10.0  | 3         | 0.64%   |
| 6.8.5   | 2         | 0.43%   |
| 6.7.5   | 2         | 0.43%   |
| 6.5.9   | 2         | 0.43%   |
| 6.4.3   | 2         | 0.43%   |
| 6.4.10  | 2         | 0.43%   |
| 6.3.5   | 2         | 0.43%   |
| 6.2.9   | 2         | 0.43%   |
| 6.2.2   | 2         | 0.43%   |
| 6.2.15  | 2         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 13.1%   |
| 5.15    | 41        | 8.95%   |
| 6.8     | 28        | 6.11%   |
| 6.5     | 26        | 5.68%   |
| 6.14    | 22        | 4.8%    |
| 5.10    | 21        | 4.59%   |
| 6.1     | 20        | 4.37%   |
| 5.13    | 20        | 4.37%   |
| 4.15    | 18        | 3.93%   |
| 6.12    | 17        | 3.71%   |
| 5.16    | 17        | 3.71%   |
| 6.2     | 16        | 3.49%   |
| 5.8     | 14        | 3.06%   |
| 5.19    | 12        | 2.62%   |
| 5.11    | 12        | 2.62%   |
| 6.17    | 10        | 2.18%   |
| 6.11    | 10        | 2.18%   |
| 5.0     | 10        | 2.18%   |
| 5.3     | 8         | 1.75%   |
| 6.6     | 7         | 1.53%   |
| 6.4     | 7         | 1.53%   |
| 6.10    | 7         | 1.53%   |
| 5.17    | 6         | 1.31%   |
| 4.18    | 5         | 1.09%   |
| 6.16    | 4         | 0.87%   |
| 6.0     | 4         | 0.87%   |
| 5.18    | 4         | 0.87%   |
| 6.9     | 3         | 0.66%   |
| 6.7     | 3         | 0.66%   |
| 6.15    | 3         | 0.66%   |
| 6.13    | 3         | 0.66%   |
| 5.7     | 3         | 0.66%   |
| 5.14    | 3         | 0.66%   |
| 4.19    | 3         | 0.66%   |
| 3.10    | 3         | 0.66%   |
| 6.3     | 2         | 0.44%   |
| 5.5     | 2         | 0.44%   |
| 5.12    | 2         | 0.44%   |
| 5.9     | 1         | 0.22%   |
| 4.9     | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 395       | 96.81%  |
| i686    | 12        | 2.94%   |
| aarch64 | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 191       | 43.81%  |
| KDE5       | 62        | 14.22%  |
| X-Cinnamon | 38        | 8.72%   |
| Unknown    | 35        | 8.03%   |
| XFCE       | 32        | 7.34%   |
| KDE6       | 29        | 6.65%   |
| MATE       | 11        | 2.52%   |
| Pantheon   | 7         | 1.61%   |
| LXDE       | 7         | 1.61%   |
| LXQt       | 6         | 1.38%   |
| KDE        | 6         | 1.38%   |
| qtile      | 2         | 0.46%   |
| Deepin     | 2         | 0.46%   |
| Budgie     | 2         | 0.46%   |
| jwm        | 1         | 0.23%   |
| ICEWM      | 1         | 0.23%   |
| Hyprland   | 1         | 0.23%   |
| Cutefish   | 1         | 0.23%   |
| COSMIC     | 1         | 0.23%   |
| Cinnamon   | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 290       | 67.6%   |
| Wayland | 122       | 28.44%  |
| Unknown | 15        | 3.5%    |
| Tty     | 2         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 204       | 46.79%  |
| SDDM    | 79        | 18.12%  |
| GDM3    | 66        | 15.14%  |
| LightDM | 41        | 9.4%    |
| GDM     | 41        | 9.4%    |
| TDM     | 5         | 1.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_EC   | 192       | 45.39%  |
| en_US   | 116       | 27.42%  |
| es_ES   | 46        | 10.87%  |
| Unknown | 21        | 4.96%   |
| es_MX   | 15        | 3.55%   |
| es_CO   | 7         | 1.65%   |
| C       | 6         | 1.42%   |
| de_DE   | 4         | 0.95%   |
| es_US   | 3         | 0.71%   |
| es_PE   | 3         | 0.71%   |
| ru_RU   | 2         | 0.47%   |
| fr_FR   | 2         | 0.47%   |
| es_AR   | 2         | 0.47%   |
| en_GB   | 2         | 0.47%   |
| es_CU   | 1         | 0.24%   |
| en_AG   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 217       | 51.06%  |
| BIOS | 208       | 48.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 288       | 67.92%  |
| Btrfs   | 57        | 13.44%  |
| Overlay | 40        | 9.43%   |
| Tmpfs   | 22        | 5.19%   |
| Xfs     | 9         | 2.12%   |
| Unknown | 4         | 0.94%   |
| Zfs     | 3         | 0.71%   |
| Ext2    | 1         | 0.24%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 207       | 49.05%  |
| GPT     | 178       | 42.18%  |
| MBR     | 37        | 8.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 356       | 85.17%  |
| Yes       | 62        | 14.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 284       | 67.78%  |
| Yes       | 135       | 32.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 76        | 18.63%  |
| ASUSTek Computer      | 64        | 15.69%  |
| Lenovo                | 50        | 12.25%  |
| Dell                  | 50        | 12.25%  |
| Gigabyte Technology   | 20        | 4.9%    |
| Toshiba               | 16        | 3.92%   |
| Acer                  | 15        | 3.68%   |
| Intel                 | 13        | 3.19%   |
| Apple                 | 12        | 2.94%   |
| ASRock                | 11        | 2.7%    |
| Google                | 10        | 2.45%   |
| Biostar               | 10        | 2.45%   |
| MSI                   | 9         | 2.21%   |
| Unknown               | 9         | 2.21%   |
| Sony                  | 7         | 1.72%   |
| Samsung Electronics   | 4         | 0.98%   |
| Foxconn               | 4         | 0.98%   |
| Gateway               | 3         | 0.74%   |
| Valve                 | 2         | 0.49%   |
| Razer                 | 2         | 0.49%   |
| Pegatron              | 2         | 0.49%   |
| ECS                   | 2         | 0.49%   |
| Alienware             | 2         | 0.49%   |
| XTRATECH COMPUTERS SA | 1         | 0.25%   |
| TrekStor              | 1         | 0.25%   |
| TPV-INVENTA           | 1         | 0.25%   |
| Timi                  | 1         | 0.25%   |
| System76              | 1         | 0.25%   |
| Shuttle               | 1         | 0.25%   |
| Notebook              | 1         | 0.25%   |
| HUAWEI                | 1         | 0.25%   |
| GPU Company           | 1         | 0.25%   |
| Fujitsu               | 1         | 0.25%   |
| Dynabook              | 1         | 0.25%   |
| Compal                | 1         | 0.25%   |
| Chuwi                 | 1         | 0.25%   |
| Cartimex              | 1         | 0.25%   |
| AMI                   | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 11        | 2.7%    |
| HP Notebook                              | 5         | 1.23%   |
| HP Pavilion g4                           | 4         | 0.98%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 4         | 0.98%   |
| ASUS All Series                          | 4         | 0.98%   |
| HP ProBook 4440s                         | 3         | 0.74%   |
| HP Pavilion Laptop 15-cw1xxx             | 3         | 0.74%   |
| Dell OptiPlex 9020                       | 3         | 0.74%   |
| ASUS PRIME A320M-A                       | 3         | 0.74%   |
| ASUS E202SA                              | 3         | 0.74%   |
| Apple MacBookPro9,2                      | 3         | 0.74%   |
| Apple MacBookPro12,1                     | 3         | 0.74%   |
| Valve Jupiter                            | 2         | 0.49%   |
| Toshiba Satellite S55-B                  | 2         | 0.49%   |
| Toshiba Satellite C55-B                  | 2         | 0.49%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 2         | 0.49%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 0.49%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 2         | 0.49%   |
| HP ProDesk 600 G1 SFF                    | 2         | 0.49%   |
| HP Pavilion Laptop 15-cw0xxx             | 2         | 0.49%   |
| HP Pavilion 14                           | 2         | 0.49%   |
| HP Laptop 15-da0xxx                      | 2         | 0.49%   |
| HP 1000                                  | 2         | 0.49%   |
| Gigabyte H81M-H                          | 2         | 0.49%   |
| Dell Vostro 3480                         | 2         | 0.49%   |
| Dell Latitude E6420                      | 2         | 0.49%   |
| Dell Inspiron N4050                      | 2         | 0.49%   |
| Dell Inspiron 5570                       | 2         | 0.49%   |
| Dell Inspiron 3442                       | 2         | 0.49%   |
| Dell Inspiron 15 7000 Gaming             | 2         | 0.49%   |
| Dell Inspiron 1420                       | 2         | 0.49%   |
| Dell Inspiron 14-3467                    | 2         | 0.49%   |
| Dell G5 5587                             | 2         | 0.49%   |
| Biostar H61MGV3                          | 2         | 0.49%   |
| Biostar G31-M7 TE                        | 2         | 0.49%   |
| ASUS PRIME H410M-E                       | 2         | 0.49%   |
| ASUS PRIME A320M-K                       | 2         | 0.49%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 2         | 0.49%   |
| ASRock B550M-HDV                         | 2         | 0.49%   |
| XTRATECH COMPUTERS SA MN-1022X           | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 27        | 6.62%   |
| Lenovo IdeaPad     | 21        | 5.15%   |
| HP Pavilion        | 20        | 4.9%    |
| Toshiba Satellite  | 15        | 3.68%   |
| ASUS PRIME         | 15        | 3.68%   |
| ASUS VivoBook      | 14        | 3.43%   |
| Lenovo ThinkPad    | 13        | 3.19%   |
| Unknown            | 11        | 2.7%    |
| HP Laptop          | 10        | 2.45%   |
| Dell Latitude      | 9         | 2.21%   |
| Acer Aspire        | 9         | 2.21%   |
| HP ProBook         | 6         | 1.47%   |
| HP ENVY            | 6         | 1.47%   |
| HP Notebook        | 5         | 1.23%   |
| HP Compaq          | 4         | 0.98%   |
| Dell OptiPlex      | 4         | 0.98%   |
| ASUS TUF           | 4         | 0.98%   |
| ASUS All           | 4         | 0.98%   |
| Lenovo Yoga        | 3         | 0.74%   |
| HP EliteBook       | 3         | 0.74%   |
| Dell Vostro        | 3         | 0.74%   |
| ASUS E202SA        | 3         | 0.74%   |
| Apple MacBookPro9  | 3         | 0.74%   |
| Apple MacBookPro12 | 3         | 0.74%   |
| Valve Jupiter      | 2         | 0.49%   |
| Razer Blade        | 2         | 0.49%   |
| MSI Stealth        | 2         | 0.49%   |
| Lenovo ThinkBook   | 2         | 0.49%   |
| Intel DH61BF       | 2         | 0.49%   |
| HP ProDesk         | 2         | 0.49%   |
| HP OMEN            | 2         | 0.49%   |
| HP 245             | 2         | 0.49%   |
| HP 15              | 2         | 0.49%   |
| HP 1000            | 2         | 0.49%   |
| Gigabyte H81M-H    | 2         | 0.49%   |
| Gigabyte H410M     | 2         | 0.49%   |
| Dell G5            | 2         | 0.49%   |
| Biostar H61MGV3    | 2         | 0.49%   |
| Biostar G31-M7     | 2         | 0.49%   |
| ASUS ROG           | 2         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 38        | 9.31%   |
| 2019    | 38        | 9.31%   |
| 2012    | 38        | 9.31%   |
| 2018    | 36        | 8.82%   |
| 2017    | 31        | 7.6%    |
| 2013    | 31        | 7.6%    |
| 2021    | 30        | 7.35%   |
| 2014    | 26        | 6.37%   |
| 2011    | 24        | 5.88%   |
| 2015    | 20        | 4.9%    |
| 2016    | 17        | 4.17%   |
| 2022    | 15        | 3.68%   |
| 2010    | 12        | 2.94%   |
| 2009    | 11        | 2.7%    |
| 2007    | 11        | 2.7%    |
| 2023    | 8         | 1.96%   |
| 2008    | 8         | 1.96%   |
| 2024    | 7         | 1.72%   |
| 2006    | 3         | 0.74%   |
| 2025    | 2         | 0.49%   |
| 2005    | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 271       | 66.42%  |
| Desktop        | 116       | 28.43%  |
| Convertible    | 15        | 3.68%   |
| Mini pc        | 2         | 0.49%   |
| All in one     | 2         | 0.49%   |
| System on chip | 1         | 0.25%   |
| Tablet         | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 385       | 93.45%  |
| Enabled  | 27        | 6.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 398       | 97.55%  |
| Yes  | 10        | 2.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 115       | 27.45%  |
| 8.01-16.0   | 86        | 20.53%  |
| 3.01-4.0    | 72        | 17.18%  |
| 16.01-24.0  | 69        | 16.47%  |
| 32.01-64.0  | 33        | 7.88%   |
| 1.01-2.0    | 21        | 5.01%   |
| 24.01-32.0  | 10        | 2.39%   |
| 2.01-3.0    | 6         | 1.43%   |
| 64.01-256.0 | 6         | 1.43%   |
| 0.51-1.0    | 1         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 127       | 27.73%  |
| 2.01-3.0   | 122       | 26.64%  |
| 4.01-8.0   | 84        | 18.34%  |
| 3.01-4.0   | 82        | 17.9%   |
| 8.01-16.0  | 22        | 4.8%    |
| 0.51-1.0   | 13        | 2.84%   |
| 0.01-0.5   | 5         | 1.09%   |
| 16.01-24.0 | 2         | 0.44%   |
| 24.01-32.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 274       | 65.55%  |
| 2      | 108       | 25.84%  |
| 3      | 24        | 5.74%   |
| 4      | 8         | 1.91%   |
| 5      | 2         | 0.48%   |
| 6      | 1         | 0.24%   |
| 0      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 278       | 67.48%  |
| Yes       | 134       | 32.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 332       | 81.37%  |
| No        | 76        | 18.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 334       | 81.27%  |
| No        | 77        | 18.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 272       | 66.34%  |
| No        | 138       | 33.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ecuador | 408       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 176       | 41.81%  |
| Guayaquil                      | 114       | 27.08%  |
| Cuenca                         | 33        | 7.84%   |
| Loja                           | 13        | 3.09%   |
| Manta                          | 9         | 2.14%   |
| Portoviejo                     | 8         | 1.9%    |
| Ambato                         | 8         | 1.9%    |
| Riobamba                       | 5         | 1.19%   |
| Machala                        | 5         | 1.19%   |
| Santo Domingo de los Colorados | 4         | 0.95%   |
| Hacienda Ibarra                | 4         | 0.95%   |
| Puyo                           | 3         | 0.71%   |
| Latacunga                      | 3         | 0.71%   |
| Sucúa                         | 2         | 0.48%   |
| Otavalo                        | 2         | 0.48%   |
| Ibarra                         | 2         | 0.48%   |
| Cotacachi                      | 2         | 0.48%   |
| Ayacucho                       | 2         | 0.48%   |
| Vinces                         | 1         | 0.24%   |
| Uyumbicho                      | 1         | 0.24%   |
| Samborondon                    | 1         | 0.24%   |
| Salinas                        | 1         | 0.24%   |
| Quevedo                        | 1         | 0.24%   |
| Provincia del Chimborazo       | 1         | 0.24%   |
| Nueva Loja                     | 1         | 0.24%   |
| Montecristi                    | 1         | 0.24%   |
| Las Pinas                      | 1         | 0.24%   |
| La Troncal                     | 1         | 0.24%   |
| La Providencia                 | 1         | 0.24%   |
| La Mana                        | 1         | 0.24%   |
| La Concordia Numero Uno        | 1         | 0.24%   |
| Huaquillas                     | 1         | 0.24%   |
| Hacienda Santo Domingo         | 1         | 0.24%   |
| Hacienda San Sebastian         | 1         | 0.24%   |
| Hacienda La Libertad           | 1         | 0.24%   |
| Guanujo                        | 1         | 0.24%   |
| Guamani                        | 1         | 0.24%   |
| Febres Cordero                 | 1         | 0.24%   |
| Esmeraldas                     | 1         | 0.24%   |
| Cumbaya                        | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 103       | 144    | 18.46%  |
| Seagate                     | 68        | 99     | 12.19%  |
| Toshiba                     | 64        | 79     | 11.47%  |
| Kingston                    | 55        | 83     | 9.86%   |
| Samsung Electronics         | 43        | 52     | 7.71%   |
| Hitachi                     | 21        | 25     | 3.76%   |
| A-DATA Technology           | 21        | 30     | 3.76%   |
| Unknown                     | 20        | 31     | 3.58%   |
| SK hynix                    | 15        | 17     | 2.69%   |
| SanDisk                     | 15        | 22     | 2.69%   |
| Intel                       | 11        | 19     | 1.97%   |
| HGST                        | 10        | 13     | 1.79%   |
| Hewlett-Packard             | 10        | 11     | 1.79%   |
| Kingston Technology Company | 9         | 12     | 1.61%   |
| Micron Technology           | 8         | 9      | 1.43%   |
| JMicron Technology          | 8         | 8      | 1.43%   |
| Apple                       | 7         | 10     | 1.25%   |
| KIOXIA                      | 5         | 6      | 0.9%    |
| Gigabyte Technology         | 5         | 5      | 0.9%    |
| Crucial                     | 5         | 6      | 0.9%    |
| Phison Electronics          | 4         | 4      | 0.72%   |
| PNY                         | 3         | 3      | 0.54%   |
| MAXIO Technology (Hangzhou) | 3         | 3      | 0.54%   |
| Fujitsu                     | 3         | 3      | 0.54%   |
| SPCC                        | 2         | 2      | 0.36%   |
| Phison                      | 2         | 2      | 0.36%   |
| Patriot                     | 2         | 2      | 0.36%   |
| HS-SSD-WAVE(S)              | 2         | 2      | 0.36%   |
| Golden                      | 2         | 2      | 0.36%   |
| Unknown                     | 2         | 2      | 0.36%   |
| USB3.0                      | 1         | 1      | 0.18%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.18%   |
| Union Memory                | 1         | 1      | 0.18%   |
| UMIS                        | 1         | 1      | 0.18%   |
| TXRUI                       | 1         | 1      | 0.18%   |
| Team                        | 1         | 1      | 0.18%   |
| SOLIDIGM                    | 1         | 1      | 0.18%   |
| SABRENT                     | 1         | 1      | 0.18%   |
| Realtek Semiconductor       | 1         | 1      | 0.18%   |
| Rayson                      | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 19        | 3.17%   |
| Seagate ST1000LM035-1RK172 1TB                    | 10        | 1.67%   |
| Kingston SA400S37480G 480GB SSD                   | 9         | 1.5%    |
| Toshiba MQ04ABF100 1TB                            | 8         | 1.33%   |
| Seagate ST500DM002-1BD142 500GB                   | 8         | 1.33%   |
| Kingston SA400S37960G 960GB SSD                   | 8         | 1.33%   |
| Toshiba MQ01ABF050 500GB                          | 7         | 1.17%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                  | 6         | 1%      |
| WDC WD10EZEX-08WN4A0 1TB                          | 6         | 1%      |
| Toshiba DT01ACA100 1TB                            | 6         | 1%      |
| A-DATA SU650 120GB SSD                            | 6         | 1%      |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 5         | 0.83%   |
| Unknown MMC Card  32GB                            | 5         | 0.83%   |
| JMicron Tech 250GB                                | 5         | 0.83%   |
| HP SSD S700 500GB                                 | 5         | 0.83%   |
| WDC WD20EZRZ-00Z5HB0 2TB                          | 4         | 0.67%   |
| WDC WD10SPZX-24Z10 1TB                            | 4         | 0.67%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 4         | 0.67%   |
| Unknown MMC Card  64GB                            | 4         | 0.67%   |
| Unknown MMC Card  16GB                            | 4         | 0.67%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 0.67%   |
| Toshiba DT01ACA200 2TB                            | 4         | 0.67%   |
| Seagate ST31000524AS 1TB                          | 4         | 0.67%   |
| Seagate ST2000LM007-1R8174 2TB                    | 4         | 0.67%   |
| SanDisk NVMe SSD Drive 1TB                        | 4         | 0.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 0.67%   |
| Kingston Company SNV2S2000G 2TB                   | 4         | 0.67%   |
| Kingston SNVS500G 500GB                           | 4         | 0.67%   |
| WDC WD6400BEVT-22A0RT0 640GB                      | 3         | 0.5%    |
| WDC WD10SPZX-24Z10T0 1TB                          | 3         | 0.5%    |
| Unknown MMC Card  128GB                           | 3         | 0.5%    |
| Toshiba MQ01ABD075 752GB                          | 3         | 0.5%    |
| Seagate ST9500420AS 500GB                         | 3         | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                    | 3         | 0.5%    |
| Samsung HD502HJ 500GB                             | 3         | 0.5%    |
| Micron 3400_MTFDKBA1T0TFH 1024GB                  | 3         | 0.5%    |
| Kingston SV300S37A60G 64GB SSD                    | 3         | 0.5%    |
| Kingston SNV2S500G 500GB                          | 3         | 0.5%    |
| JMicron Generic 320GB                             | 3         | 0.5%    |
| Hitachi HTS547550A9E384 500GB                     | 3         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 74        | 107    | 28.79%  |
| Seagate             | 68        | 99     | 26.46%  |
| Toshiba             | 58        | 71     | 22.57%  |
| Hitachi             | 21        | 25     | 8.17%   |
| Samsung Electronics | 14        | 16     | 5.45%   |
| HGST                | 10        | 13     | 3.89%   |
| JMicron Technology  | 3         | 3      | 1.17%   |
| Fujitsu             | 3         | 3      | 1.17%   |
| Unknown             | 2         | 4      | 0.78%   |
| USB3.0              | 1         | 1      | 0.39%   |
| Maxtor              | 1         | 1      | 0.39%   |
| HPE                 | 1         | 1      | 0.39%   |
| Apple               | 1         | 1      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 44        | 58     | 28.76%  |
| WDC                 | 26        | 30     | 16.99%  |
| A-DATA Technology   | 18        | 26     | 11.76%  |
| Hewlett-Packard     | 9         | 10     | 5.88%   |
| Samsung Electronics | 8         | 12     | 5.23%   |
| SanDisk             | 5         | 5      | 3.27%   |
| Apple               | 5         | 8      | 3.27%   |
| Toshiba             | 4         | 6      | 2.61%   |
| Gigabyte Technology | 4         | 4      | 2.61%   |
| Crucial             | 4         | 4      | 2.61%   |
| PNY                 | 3         | 3      | 1.96%   |
| SPCC                | 2         | 2      | 1.31%   |
| SK hynix            | 2         | 2      | 1.31%   |
| Patriot             | 2         | 2      | 1.31%   |
| Intel               | 2         | 2      | 1.31%   |
| Golden              | 2         | 2      | 1.31%   |
| Team                | 1         | 1      | 0.65%   |
| SABRENT             | 1         | 1      | 0.65%   |
| Rayson              | 1         | 1      | 0.65%   |
| OWC                 | 1         | 1      | 0.65%   |
| Netac               | 1         | 1      | 0.65%   |
| Micron Technology   | 1         | 1      | 0.65%   |
| Micro Center        | 1         | 1      | 0.65%   |
| LITEON              | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| KINGPAN             | 1         | 1      | 0.65%   |
| HS-SSD-E100N        | 1         | 1      | 0.65%   |
| HS-SSD-E100         | 1         | 1      | 0.65%   |
| ANKEJE              | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 230       | 345    | 44.75%  |
| SSD     | 136       | 189    | 26.46%  |
| NVMe    | 119       | 163    | 23.15%  |
| MMC     | 18        | 28     | 3.5%    |
| Unknown | 11        | 12     | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 314       | 520    | 66.95%  |
| NVMe | 119       | 163    | 25.37%  |
| SAS  | 18        | 26     | 3.84%   |
| MMC  | 18        | 28     | 3.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 209       | 302    | 55.59%  |
| 0.51-1.0   | 133       | 186    | 35.37%  |
| 1.01-2.0   | 27        | 35     | 7.18%   |
| 3.01-4.0   | 4         | 7      | 1.06%   |
| 2.01-3.0   | 2         | 3      | 0.53%   |
| 4.01-10.0  | 1         | 1      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 108       | 24.66%  |
| 101-250        | 98        | 22.37%  |
| 501-1000       | 71        | 16.21%  |
| 1001-2000      | 48        | 10.96%  |
| 1-20           | 33        | 7.53%   |
| 51-100         | 26        | 5.94%   |
| More than 3000 | 19        | 4.34%   |
| 21-50          | 19        | 4.34%   |
| Unknown        | 12        | 2.74%   |
| 2001-3000      | 4         | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 154       | 34%     |
| 21-50          | 88        | 19.43%  |
| 101-250        | 62        | 13.69%  |
| 51-100         | 49        | 10.82%  |
| 251-500        | 42        | 9.27%   |
| 501-1000       | 24        | 5.3%    |
| 1001-2000      | 12        | 2.65%   |
| Unknown        | 12        | 2.65%   |
| More than 3000 | 5         | 1.1%    |
| 2001-3000      | 4         | 0.88%   |
| 0              | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB            | 3         | 3      | 5.66%   |
| Seagate ST500DM002-1BD142 500GB         | 3         | 4      | 5.66%   |
| Hitachi HTS547550A9E384 500GB           | 3         | 3      | 5.66%   |
| Hitachi HDS721050CLA660 500GB           | 3         | 4      | 5.66%   |
| WDC WD10EZEX-00BN5A0 1TB                | 2         | 2      | 3.77%   |
| Toshiba MQ01ABF050 500GB                | 2         | 4      | 3.77%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 3.77%   |
| WDC WD5000LPVT-00G33T0 500GB            | 1         | 1      | 1.89%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 2      | 1.89%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 1         | 1      | 1.89%   |
| WDC WD3200AAKS-00L9A0 320GB             | 1         | 1      | 1.89%   |
| WDC WD1200BEVS-22UST0 120GB             | 1         | 1      | 1.89%   |
| WDC WD10SPCX-22HWST0 1TB                | 1         | 2      | 1.89%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 1         | 1      | 1.89%   |
| WDC WD10EZEX-00WN4A0 1TB                | 1         | 1      | 1.89%   |
| Toshiba MQ01ABD100M 1TB                 | 1         | 1      | 1.89%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1      | 1.89%   |
| Toshiba MK7559GSXP 752GB                | 1         | 1      | 1.89%   |
| Toshiba MK3265GSXN 320GB                | 1         | 1      | 1.89%   |
| Toshiba MK3259GSXP 320GB                | 1         | 1      | 1.89%   |
| Toshiba MK2561GSYN 250GB                | 1         | 2      | 1.89%   |
| Toshiba DT01ACA300 3TB                  | 1         | 2      | 1.89%   |
| Seagate ST9750420AS 752GB               | 1         | 1      | 1.89%   |
| Seagate ST3750330AS 752GB               | 1         | 1      | 1.89%   |
| Seagate ST3500630AS 500GB               | 1         | 1      | 1.89%   |
| Seagate ST31000524AS 1TB                | 1         | 1      | 1.89%   |
| Seagate ST31000333AS 1TB                | 1         | 2      | 1.89%   |
| Seagate ST2000DL003-9VT166 2TB          | 1         | 1      | 1.89%   |
| Seagate ST1000LX015-1U7172 1TB          | 1         | 3      | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1      | 1.89%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 2      | 1.89%   |
| Samsung Electronics HD501LJ 500GB       | 1         | 1      | 1.89%   |
| Samsung Electronics HD322HJ 320GB       | 1         | 1      | 1.89%   |
| Samsung Electronics HD161GJ 160GB       | 1         | 1      | 1.89%   |
| Samsung Electronics HD103UJ 1TB         | 1         | 1      | 1.89%   |
| Kingston SNS4151S316GD 16GB SSD         | 1         | 1      | 1.89%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 1.89%   |
| HPE MB0500EAMZD 500GB                   | 1         | 1      | 1.89%   |
| Hitachi HTS543232L9SA00 320GB           | 1         | 1      | 1.89%   |
| HGST HTS545050A7E380 500GB              | 1         | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 23.08%  |
| Seagate             | 12        | 17     | 23.08%  |
| Toshiba             | 11        | 15     | 21.15%  |
| Hitachi             | 7         | 8      | 13.46%  |
| Samsung Electronics | 4         | 4      | 7.69%   |
| Kingston            | 2         | 2      | 3.85%   |
| Fujitsu             | 2         | 2      | 3.85%   |
| HPE                 | 1         | 1      | 1.92%   |
| HGST                | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 24%     |
| Seagate             | 12        | 17     | 24%     |
| Toshiba             | 11        | 15     | 22%     |
| Hitachi             | 7         | 8      | 14%     |
| Samsung Electronics | 4         | 4      | 8%      |
| Fujitsu             | 2         | 2      | 4%      |
| HPE                 | 1         | 1      | 2%      |
| HGST                | 1         | 1      | 2%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 63     | 95.56%  |
| SSD  | 2         | 2      | 4.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK6476GSX 640GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 250       | 447    | 56.05%  |
| Works    | 150       | 224    | 33.63%  |
| Malfunc  | 45        | 65     | 10.09%  |
| Failed   | 1         | 1      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 277       | 56.07%  |
| AMD                          | 79        | 15.99%  |
| Samsung Electronics          | 26        | 5.26%   |
| Kingston Technology Company  | 24        | 4.86%   |
| SanDisk                      | 17        | 3.44%   |
| SK hynix                     | 13        | 2.63%   |
| Phison Electronics           | 9         | 1.82%   |
| Micron Technology            | 7         | 1.42%   |
| Marvell Technology Group     | 5         | 1.01%   |
| KIOXIA                       | 5         | 1.01%   |
| ADATA Technology             | 4         | 0.81%   |
| Union Memory (Shenzhen)      | 3         | 0.61%   |
| Nvidia                       | 3         | 0.61%   |
| MAXIO Technology (Hangzhou)  | 3         | 0.61%   |
| JMicron Technology           | 3         | 0.61%   |
| ASMedia Technology           | 3         | 0.61%   |
| VIA Technologies             | 2         | 0.4%    |
| Toshiba America Info Systems | 2         | 0.4%    |
| Micron/Crucial Technology    | 2         | 0.4%    |
| Solidigm                     | 1         | 0.2%    |
| Silicon Motion               | 1         | 0.2%    |
| Realtek Semiconductor        | 1         | 0.2%    |
| Lite-On Technology           | 1         | 0.2%    |
| INNOGRIT                     | 1         | 0.2%    |
| Broadcom / LSI               | 1         | 0.2%    |
| Apple                        | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 59        | 10.71%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 26        | 4.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 24        | 4.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21        | 3.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 19        | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 14        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 2.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 1.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 9         | 1.63%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 9         | 1.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.45%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 7         | 1.27%   |
| Intel RST Volume Management Device Controller                                           | 7         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 7         | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7         | 1.27%   |
| AMD 500 Series Chipset SATA Controller                                                  | 7         | 1.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.27%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 6         | 1.09%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 1.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 1.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.09%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 5         | 0.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 0.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 0.91%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 5         | 0.91%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 4         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 0.73%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 4         | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 0.73%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4         | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 291       | 57.97%  |
| NVMe | 119       | 23.71%  |
| RAID | 49        | 9.76%   |
| IDE  | 43        | 8.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 311       | 76.23%  |
| AMD    | 96        | 23.53%  |
| ARM    | 1         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 2.7%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 2.21%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 1.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 1.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.47%   |
| AMD Ryzen 5 3600 6-Core Processor             | 5         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.98%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 4         | 0.98%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 4         | 0.98%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.98%   |
| Intel 13th Gen Core i9-13900H                 | 4         | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 0.98%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.74%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.74%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.74%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.74%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.74%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 3         | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.74%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.74%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.74%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.74%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.74%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.74%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 0.74%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 3         | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.74%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.74%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.74%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 84        | 20.59%  |
| Intel Core i5           | 81        | 19.85%  |
| Other                   | 38        | 9.31%   |
| Intel Core i3           | 33        | 8.09%   |
| Intel Celeron           | 29        | 7.11%   |
| AMD Ryzen 5             | 29        | 7.11%   |
| AMD Ryzen 7             | 22        | 5.39%   |
| Intel Core 2 Duo        | 16        | 3.92%   |
| Intel Pentium           | 10        | 2.45%   |
| Intel Atom              | 7         | 1.72%   |
| AMD Ryzen 3             | 5         | 1.23%   |
| Intel Xeon              | 4         | 0.98%   |
| AMD E2                  | 4         | 0.98%   |
| AMD E1                  | 4         | 0.98%   |
| Intel Pentium Dual-Core | 3         | 0.74%   |
| Intel Genuine           | 3         | 0.74%   |
| AMD A8                  | 3         | 0.74%   |
| AMD A6                  | 3         | 0.74%   |
| AMD A12                 | 3         | 0.74%   |
| Intel Pentium Silver    | 2         | 0.49%   |
| Intel Core 2 Quad       | 2         | 0.49%   |
| AMD Ryzen 9             | 2         | 0.49%   |
| AMD FX                  | 2         | 0.49%   |
| AMD E                   | 2         | 0.49%   |
| AMD Athlon II X2        | 2         | 0.49%   |
| AMD A4                  | 2         | 0.49%   |
| Intel Pentium M         | 1         | 0.25%   |
| Intel Core m3           | 1         | 0.25%   |
| Intel Core i9           | 1         | 0.25%   |
| Intel Core              | 1         | 0.25%   |
| Intel Celeron M         | 1         | 0.25%   |
| AMD Ryzen 7 PRO         | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Phenom II X6        | 1         | 0.25%   |
| AMD Phenom II X2        | 1         | 0.25%   |
| AMD C-70                | 1         | 0.25%   |
| AMD C-60                | 1         | 0.25%   |
| AMD Athlon II Neo       | 1         | 0.25%   |
| AMD A10                 | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 178       | 43.52%  |
| 4      | 143       | 34.96%  |
| 6      | 35        | 8.56%   |
| 8      | 27        | 6.6%    |
| 1      | 9         | 2.2%    |
| 14     | 8         | 1.96%   |
| 12     | 4         | 0.98%   |
| 10     | 3         | 0.73%   |
| 24     | 2         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 407       | 99.75%  |
| 2      | 1         | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 274       | 66.99%  |
| 1      | 135       | 33.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 402       | 98.53%  |
| 32-bit         | 3         | 0.74%   |
| Unknown        | 2         | 0.49%   |
| 64-bit         | 1         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 191       | 44.84%  |
| 0x306a9    | 19        | 4.46%   |
| 0x206a7    | 16        | 3.76%   |
| 0x806ea    | 15        | 3.52%   |
| 0x306c3    | 15        | 3.52%   |
| 0x306d4    | 10        | 2.35%   |
| 0x1067a    | 9         | 2.11%   |
| 0x6fd      | 8         | 1.88%   |
| 0x40651    | 8         | 1.88%   |
| 0x08108109 | 7         | 1.64%   |
| 0xa0653    | 5         | 1.17%   |
| 0x806c1    | 5         | 1.17%   |
| 0x06006705 | 5         | 1.17%   |
| 0x906ed    | 4         | 0.94%   |
| 0x906ea    | 4         | 0.94%   |
| 0x806ec    | 4         | 0.94%   |
| 0x706e5    | 4         | 0.94%   |
| 0x406e3    | 4         | 0.94%   |
| 0x0810100b | 4         | 0.94%   |
| 0x05000119 | 4         | 0.94%   |
| 0x806eb    | 3         | 0.7%    |
| 0x806e9    | 3         | 0.7%    |
| 0x706a1    | 3         | 0.7%    |
| 0x406c4    | 3         | 0.7%    |
| 0x30678    | 3         | 0.7%    |
| 0x20655    | 3         | 0.7%    |
| 0x106ca    | 3         | 0.7%    |
| 0x08600104 | 3         | 0.7%    |
| 0x06006704 | 3         | 0.7%    |
| 0x0600611a | 3         | 0.7%    |
| 0x010000c8 | 3         | 0.7%    |
| 0x706a8    | 2         | 0.47%   |
| 0x6e8      | 2         | 0.47%   |
| 0x506e3    | 2         | 0.47%   |
| 0x106e5    | 2         | 0.47%   |
| 0x0a201005 | 2         | 0.47%   |
| 0x08701021 | 2         | 0.47%   |
| 0x08608104 | 2         | 0.47%   |
| 0x08108102 | 2         | 0.47%   |
| 0x0700010f | 2         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 59        | 14.39%  |
| Haswell           | 41        | 10%     |
| IvyBridge         | 35        | 8.54%   |
| SandyBridge       | 23        | 5.61%   |
| Unknown           | 22        | 5.37%   |
| Skylake           | 17        | 4.15%   |
| Zen+              | 16        | 3.9%    |
| Zen 2             | 16        | 3.9%    |
| TigerLake         | 14        | 3.41%   |
| Excavator         | 14        | 3.41%   |
| Core              | 14        | 3.41%   |
| Broadwell         | 14        | 3.41%   |
| Zen 3             | 12        | 2.93%   |
| Silvermont        | 12        | 2.93%   |
| Penryn            | 12        | 2.93%   |
| CometLake         | 12        | 2.93%   |
| Alderlake Hybrid  | 11        | 2.68%   |
| Goldmont plus     | 9         | 2.2%    |
| IceLake           | 8         | 1.95%   |
| Zen               | 7         | 1.71%   |
| Westmere          | 7         | 1.71%   |
| Bobcat            | 7         | 1.71%   |
| K10               | 5         | 1.22%   |
| Bonnell           | 5         | 1.22%   |
| Nehalem           | 4         | 0.98%   |
| P6                | 3         | 0.73%   |
| Goldmont          | 3         | 0.73%   |
| Puma              | 2         | 0.49%   |
| Jaguar            | 2         | 0.49%   |
| Steamroller       | 1         | 0.24%   |
| Piledriver        | 1         | 0.24%   |
| Meteorlake Hybrid | 1         | 0.24%   |
| K10 Llano         | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 272       | 58.12%  |
| AMD              | 111       | 23.72%  |
| Nvidia           | 84        | 17.95%  |
| VIA Technologies | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 4.36%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 20        | 4.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 3.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 3.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 3.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 3.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 2.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 2.28%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 10        | 2.07%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.66%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 8         | 1.66%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 1.45%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 7         | 1.45%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 7         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.45%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.45%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 6         | 1.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.24%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.24%   |
| AMD Lucienne                                                                             | 6         | 1.24%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 1.04%   |
| Nvidia GT218 [GeForce 210]                                                               | 4         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.83%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 4         | 0.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.83%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 0.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.62%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.62%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 216       | 52.43%  |
| 1 x AMD                  | 89        | 21.6%   |
| 1 x Nvidia               | 41        | 9.95%   |
| Intel + Nvidia           | 37        | 8.98%   |
| Intel + AMD              | 14        | 3.4%    |
| AMD + Nvidia             | 6         | 1.46%   |
| 2 x Intel                | 3         | 0.73%   |
| Other                    | 2         | 0.49%   |
| 2 x AMD                  | 2         | 0.49%   |
| 1 x VIA                  | 1         | 0.24%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 349       | 84.3%   |
| Proprietary | 46        | 11.11%  |
| Unknown     | 19        | 4.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 287       | 67.69%  |
| 0.01-0.5   | 44        | 10.38%  |
| 1.01-2.0   | 43        | 10.14%  |
| 3.01-4.0   | 16        | 3.77%   |
| 0.51-1.0   | 16        | 3.77%   |
| 7.01-8.0   | 7         | 1.65%   |
| 5.01-6.0   | 5         | 1.18%   |
| 8.01-16.0  | 5         | 1.18%   |
| 2.01-3.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 57        | 12.75%  |
| Chimei Innolux          | 55        | 12.3%   |
| AU Optronics            | 54        | 12.08%  |
| BOE                     | 53        | 11.86%  |
| Samsung Electronics     | 45        | 10.07%  |
| LG Display              | 44        | 9.84%   |
| AOC                     | 17        | 3.8%    |
| Hewlett-Packard         | 12        | 2.68%   |
| Apple                   | 12        | 2.68%   |
| BenQ                    | 11        | 2.46%   |
| Dell                    | 9         | 2.01%   |
| Chi Mei Optoelectronics | 9         | 2.01%   |
| Acer                    | 5         | 1.12%   |
| PANDA                   | 4         | 0.89%   |
| LG Electronics          | 4         | 0.89%   |
| Lenovo                  | 4         | 0.89%   |
| ASUSTek Computer        | 4         | 0.89%   |
| Unknown (XXX)           | 3         | 0.67%   |
| Sony                    | 3         | 0.67%   |
| LG Philips              | 3         | 0.67%   |
| InfoVision              | 3         | 0.67%   |
| Valve                   | 2         | 0.45%   |
| Sharp                   | 2         | 0.45%   |
| Philips                 | 2         | 0.45%   |
| MSI                     | 2         | 0.45%   |
| KTC                     | 2         | 0.45%   |
| InnoLux Display         | 2         | 0.45%   |
| Gigabyte Technology     | 2         | 0.45%   |
| DMT                     | 2         | 0.45%   |
| ViewSonic               | 1         | 0.22%   |
| Unknown (CEA)           | 1         | 0.22%   |
| Toshiba                 | 1         | 0.22%   |
| TES                     | 1         | 0.22%   |
| TCL                     | 1         | 0.22%   |
| SKY                     | 1         | 0.22%   |
| RTK                     | 1         | 0.22%   |
| NEC Computers           | 1         | 0.22%   |
| MStar                   | 1         | 0.22%   |
| JDZ                     | 1         | 0.22%   |
| Huion                   | 1         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 14        | 3.06%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 5         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 5         | 1.09%   |
| AOC LCD Monitor AOC2070 1600x900 430x240mm 19.4-inch                 | 5         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch     | 4         | 0.87%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 4         | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 3         | 0.66%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 0.66%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 3         | 0.66%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                 | 3         | 0.66%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 3         | 0.66%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                  | 3         | 0.66%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 0.66%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 0.66%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3         | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.66%   |
| Apple Color LCD APPA029 2560x1600 286x179mm 13.3-inch                | 3         | 0.66%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.44%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 2         | 0.44%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 304x228mm 15.0-inch  | 2         | 0.44%   |
| Samsung Electronics SyncMaster SAM01A1 1024x768 304x228mm 15.0-inch  | 2         | 0.44%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 2         | 0.44%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.44%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2         | 0.44%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 2         | 0.44%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2         | 0.44%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.44%   |
| LG Display LCD Monitor LGD02B2 1366x768 310x174mm 14.0-inch          | 2         | 0.44%   |
| Lenovo LCD Monitor LEN9051 1920x1080 344x194mm 15.5-inch             | 2         | 0.44%   |
| Goldstar LG HD PLUS GSM5AC7 1600x900 440x250mm 19.9-inch             | 2         | 0.44%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 2         | 0.44%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 2         | 0.44%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 2         | 0.44%   |
| DMT CHHWJT* DMT0030 1440x900 708x398mm 32.0-inch                     | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 2         | 0.44%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 2         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 166       | 38.07%  |
| 1920x1080 (FHD)    | 139       | 31.88%  |
| 1600x900 (HD+)     | 23        | 5.28%   |
| 1280x800 (WXGA)    | 15        | 3.44%   |
| 3840x2160 (4K)     | 12        | 2.75%   |
| 1920x1200 (WUXGA)  | 11        | 2.52%   |
| 1440x900 (WXGA+)   | 10        | 2.29%   |
| 1360x768           | 10        | 2.29%   |
| 1024x768 (XGA)     | 9         | 2.06%   |
| 2560x1600          | 8         | 1.83%   |
| 2560x1440 (QHD)    | 8         | 1.83%   |
| 1280x1024 (SXGA)   | 5         | 1.15%   |
| 1680x1050 (WSXGA+) | 4         | 0.92%   |
| 1024x600           | 3         | 0.69%   |
| 800x1280           | 2         | 0.46%   |
| Unknown            | 2         | 0.46%   |
| 4093x4093          | 1         | 0.23%   |
| 3840x2400          | 1         | 0.23%   |
| 3520x1080          | 1         | 0.23%   |
| 3440x1440          | 1         | 0.23%   |
| 3200x2000          | 1         | 0.23%   |
| 2880x1800          | 1         | 0.23%   |
| 2646x1024          | 1         | 0.23%   |
| 2256x1504          | 1         | 0.23%   |
| 1600x1200          | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 140       | 31.04%  |
| 13      | 52        | 11.53%  |
| 14      | 50        | 11.09%  |
| 18      | 48        | 10.64%  |
| 19      | 25        | 5.54%   |
| 23      | 18        | 3.99%   |
| 21      | 18        | 3.99%   |
| 11      | 15        | 3.33%   |
| 17      | 11        | 2.44%   |
| 24      | 9         | 2%      |
| 12      | 9         | 2%      |
| Unknown | 9         | 2%      |
| 16      | 8         | 1.77%   |
| 27      | 7         | 1.55%   |
| 31      | 5         | 1.11%   |
| 32      | 4         | 0.89%   |
| 20      | 4         | 0.89%   |
| 54      | 3         | 0.67%   |
| 10      | 3         | 0.67%   |
| 52      | 2         | 0.44%   |
| 39      | 2         | 0.44%   |
| 22      | 2         | 0.44%   |
| 7       | 2         | 0.44%   |
| 85      | 1         | 0.22%   |
| 72      | 1         | 0.22%   |
| 63      | 1         | 0.22%   |
| 40      | 1         | 0.22%   |
| 34      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 226       | 51.48%  |
| 401-500     | 86        | 19.59%  |
| 201-300     | 47        | 10.71%  |
| 501-600     | 32        | 7.29%   |
| 351-400     | 15        | 3.42%   |
| Unknown     | 9         | 2.05%   |
| 601-700     | 6         | 1.37%   |
| 1001-1500   | 6         | 1.37%   |
| 701-800     | 5         | 1.14%   |
| 801-900     | 3         | 0.68%   |
| 1501-2000   | 2         | 0.46%   |
| 1-100       | 2         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 326       | 81.5%   |
| 16/10   | 45        | 11.25%  |
| 4/3     | 11        | 2.75%   |
| Unknown | 9         | 2.25%   |
| 5/4     | 5         | 1.25%   |
| 0.67    | 2         | 0.5%    |
| 3/2     | 1         | 0.25%   |
| 21/9    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 138       | 30.73%  |
| 81-90          | 90        | 20.04%  |
| 141-150        | 49        | 10.91%  |
| 151-200        | 37        | 8.24%   |
| 201-250        | 33        | 7.35%   |
| 51-60          | 15        | 3.34%   |
| 71-80          | 13        | 2.9%    |
| 351-500        | 10        | 2.23%   |
| 111-120        | 9         | 2%      |
| Unknown        | 9         | 2%      |
| More than 1000 | 8         | 1.78%   |
| 61-70          | 8         | 1.78%   |
| 301-350        | 7         | 1.56%   |
| 121-130        | 7         | 1.56%   |
| 251-300        | 5         | 1.11%   |
| 41-50          | 3         | 0.67%   |
| 501-1000       | 3         | 0.67%   |
| 1-40           | 2         | 0.45%   |
| 131-140        | 2         | 0.45%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 144       | 33.18%  |
| 51-100        | 128       | 29.49%  |
| 121-160       | 119       | 27.42%  |
| 161-240       | 22        | 5.07%   |
| 1-50          | 9         | 2.07%   |
| Unknown       | 9         | 2.07%   |
| More than 240 | 3         | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 337       | 81.01%  |
| 2     | 64        | 15.38%  |
| 0     | 10        | 2.4%    |
| 3     | 5         | 1.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 261       | 42.23%  |
| Intel                           | 143       | 23.14%  |
| Qualcomm Atheros                | 81        | 13.11%  |
| Broadcom                        | 41        | 6.63%   |
| TP-Link                         | 20        | 3.24%   |
| MediaTek                        | 15        | 2.43%   |
| Ralink                          | 9         | 1.46%   |
| Ralink Technology               | 8         | 1.29%   |
| Broadcom Limited                | 6         | 0.97%   |
| Samsung Electronics             | 5         | 0.81%   |
| Marvell Technology Group        | 5         | 0.81%   |
| Xiaomi                          | 4         | 0.65%   |
| ASIX Electronics                | 4         | 0.65%   |
| Qualcomm Atheros Communications | 3         | 0.49%   |
| Nvidia                          | 2         | 0.32%   |
| D-Link System                   | 2         | 0.32%   |
| VIA Technologies                | 1         | 0.16%   |
| TRENDnet                        | 1         | 0.16%   |
| Shenzhen Goodix Technology      | 1         | 0.16%   |
| Qualcomm                        | 1         | 0.16%   |
| OPPO Electronics                | 1         | 0.16%   |
| NetGear                         | 1         | 0.16%   |
| Hewlett-Packard                 | 1         | 0.16%   |
| DisplayLink                     | 1         | 0.16%   |
| Arduino SA                      | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 157       | 22.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 55        | 7.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 20        | 2.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 18        | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 1.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 11        | 1.55%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 1.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 10        | 1.41%   |
| Intel Wireless 8265 / 8275                                             | 9         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 9         | 1.27%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 8         | 1.13%   |
| Intel Wireless 3160                                                    | 8         | 1.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 1.13%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 7         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 0.98%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                          | 7         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 0.84%   |
| Intel Wireless 7265                                                    | 6         | 0.84%   |
| Intel Wireless 7260                                                    | 6         | 0.84%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 5         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.7%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 5         | 0.7%    |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 5         | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 5         | 0.7%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                        | 4         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.56%   |
| Intel Wireless 8260                                                    | 4         | 0.56%   |
| Intel Wireless 3165                                                    | 4         | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 0.56%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.56%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 4         | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 114       | 32.39%  |
| Realtek Semiconductor           | 76        | 21.59%  |
| Qualcomm Atheros                | 68        | 19.32%  |
| Broadcom                        | 34        | 9.66%   |
| TP-Link                         | 19        | 5.4%    |
| MediaTek                        | 15        | 4.26%   |
| Ralink                          | 9         | 2.56%   |
| Ralink Technology               | 8         | 2.27%   |
| Broadcom Limited                | 4         | 1.14%   |
| Qualcomm Atheros Communications | 3         | 0.85%   |
| TRENDnet                        | 1         | 0.28%   |
| NetGear                         | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 20        | 5.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 5.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 14        | 3.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 3.11%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 3.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 2.82%   |
| Intel Wireless 8265 / 8275                                              | 9         | 2.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 8         | 2.26%   |
| Intel Wireless 3160                                                     | 8         | 2.26%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 7         | 1.98%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.69%   |
| Intel Wireless 7265                                                     | 6         | 1.69%   |
| Intel Wireless 7260                                                     | 6         | 1.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 5         | 1.41%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 5         | 1.41%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 1.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.13%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.13%   |
| Intel Wireless 8260                                                     | 4         | 1.13%   |
| Intel Wireless 3165                                                     | 4         | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.13%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 1.13%   |
| TP-Link 802.11ac WLAN Adapter                                           | 3         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 3         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.85%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 232       | 67.05%  |
| Intel                    | 50        | 14.45%  |
| Qualcomm Atheros         | 21        | 6.07%   |
| Broadcom                 | 15        | 4.34%   |
| Marvell Technology Group | 5         | 1.45%   |
| Xiaomi                   | 4         | 1.16%   |
| Samsung Electronics      | 4         | 1.16%   |
| ASIX Electronics         | 4         | 1.16%   |
| Nvidia                   | 2         | 0.58%   |
| D-Link System            | 2         | 0.58%   |
| Broadcom Limited         | 2         | 0.58%   |
| VIA Technologies         | 1         | 0.29%   |
| TP-Link                  | 1         | 0.29%   |
| Qualcomm                 | 1         | 0.29%   |
| OPPO Electronics         | 1         | 0.29%   |
| DisplayLink              | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 157       | 44.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 55        | 15.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 1.99%   |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 1.99%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 1.14%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.14%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 0.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.57%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 0.57%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.57%   |
| Intel WiMAX Connection 2400m                                           | 2         | 0.57%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.57%   |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.57%   |
| Intel Ethernet Connection (17) I219-V                                  | 2         | 0.57%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2         | 0.57%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.57%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.28%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.28%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.28%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 0.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.28%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 334       | 49.78%  |
| Ethernet | 332       | 49.48%  |
| Modem    | 5         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 59.06%  |
| Ethernet | 174       | 40.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 222       | 54.28%  |
| 1     | 180       | 44.01%  |
| 0     | 5         | 1.22%   |
| 3     | 2         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 333       | 79.47%  |
| Yes  | 86        | 20.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 93        | 34.07%  |
| Realtek Semiconductor           | 40        | 14.65%  |
| Qualcomm Atheros Communications | 34        | 12.45%  |
| IMC Networks                    | 17        | 6.23%   |
| Cambridge Silicon Radio         | 16        | 5.86%   |
| Broadcom                        | 16        | 5.86%   |
| Lite-On Technology              | 12        | 4.4%    |
| Apple                           | 11        | 4.03%   |
| Foxconn / Hon Hai               | 10        | 3.66%   |
| Toshiba                         | 3         | 1.1%    |
| Ralink                          | 3         | 1.1%    |
| MediaTek                        | 3         | 1.1%    |
| Hewlett-Packard                 | 3         | 1.1%    |
| TP-Link                         | 2         | 0.73%   |
| Ralink Technology               | 2         | 0.73%   |
| Dell                            | 2         | 0.73%   |
| ASUSTek Computer                | 2         | 0.73%   |
| Realtek                         | 1         | 0.37%   |
| Foxconn International           | 1         | 0.37%   |
| D-Link System                   | 1         | 0.37%   |
| Alps Electric                   | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 13.92%  |
| Qualcomm Atheros  Bluetooth Device                  | 23        | 8.42%   |
| Intel AX201 Bluetooth                               | 20        | 7.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 6.59%   |
| Realtek Bluetooth Radio                             | 17        | 6.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 16        | 5.86%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 4.4%    |
| IMC Networks Bluetooth Radio                        | 9         | 3.3%    |
| Intel Bluetooth Device                              | 7         | 2.56%   |
| Intel AX200 Bluetooth                               | 7         | 2.56%   |
| IMC Networks Wireless_Device                        | 6         | 2.2%    |
| Apple Bluetooth Host Controller                     | 6         | 2.2%    |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.83%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.47%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.47%   |
| Lite-On Wireless_Device                             | 4         | 1.47%   |
| Lite-On Bluetooth Device                            | 4         | 1.47%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.47%   |
| Toshiba Bluetooth Device                            | 3         | 1.1%    |
| Ralink RT3290 Bluetooth                             | 3         | 1.1%    |
| MediaTek Wireless_Device                            | 3         | 1.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.1%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.1%    |
| TP-Link TP-T@- UB500 Adapter                        | 2         | 0.73%   |
| Lite-On Bluetooth Radio                             | 2         | 0.73%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.73%   |
| Intel AX210 Bluetooth                               | 2         | 0.73%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.73%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.73%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.73%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.73%   |
| Broadcom HP Portable Valentine                      | 2         | 0.73%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.73%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.73%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.37%   |
| Realtek Bluetooth Radio                             | 1         | 0.37%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.37%   |
| Ralink CSR BS8510                                   | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 307       | 61.52%  |
| AMD                 | 108       | 21.64%  |
| Nvidia              | 63        | 12.63%  |
| Focusrite-Novation  | 3         | 0.6%    |
| Texas Instruments   | 2         | 0.4%    |
| Sony                | 2         | 0.4%    |
| Kingston Technology | 2         | 0.4%    |
| C-Media Electronics | 2         | 0.4%    |
| VIA Technologies    | 1         | 0.2%    |
| SteelSeries ApS     | 1         | 0.2%    |
| Samson Technologies | 1         | 0.2%    |
| M-Audio             | 1         | 0.2%    |
| Logitech            | 1         | 0.2%    |
| GN Netcom           | 1         | 0.2%    |
| Creative Labs       | 1         | 0.2%    |
| Corsair             | 1         | 0.2%    |
| Audient             | 1         | 0.2%    |
| Apple               | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 49        | 7.79%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 36        | 5.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 30        | 4.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 24        | 3.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 23        | 3.66%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 20        | 3.18%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 3.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 2.54%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 2.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 2.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 2.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 2.07%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 2.07%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 1.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 1.91%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.43%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.43%   |
| AMD High Definition Audio Controller                                                              | 9         | 1.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 8         | 1.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 1.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 7         | 1.11%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 7         | 1.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 7         | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 0.95%   |
| AMD Radeon High Definition Audio Controller                                                       | 6         | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.79%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 5         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 73        | 26.45%  |
| Kingston            | 44        | 15.94%  |
| SK hynix            | 41        | 14.86%  |
| Micron Technology   | 29        | 10.51%  |
| Unknown             | 19        | 6.88%   |
| A-DATA Technology   | 17        | 6.16%   |
| Corsair             | 13        | 4.71%   |
| Crucial             | 8         | 2.9%    |
| Ramaxel Technology  | 7         | 2.54%   |
| Nanya Technology    | 4         | 1.45%   |
| Avant               | 4         | 1.45%   |
| Unknown (ABCD)      | 2         | 0.72%   |
| Team                | 2         | 0.72%   |
| Hewlett-Packard     | 2         | 0.72%   |
| Elpida              | 2         | 0.72%   |
| Unknown             | 2         | 0.72%   |
| PNY                 | 1         | 0.36%   |
| Hikvision           | 1         | 0.36%   |
| GOODRAM             | 1         | 0.36%   |
| Gold Key            | 1         | 0.36%   |
| G.Skill             | 1         | 0.36%   |
| fef5                | 1         | 0.36%   |
| 8054000080CE        | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 3.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 4         | 1.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.01%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.01%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.01%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.01%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.01%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.01%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 3         | 1.01%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.01%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.01%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 2         | 0.68%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.68%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.68%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Kingston RAM SNY1333D3S9ELC/4G 4GB SODIMM DDR3 1334MT/s          | 2         | 0.68%   |
| Kingston RAM KHX3000C16D4/16GX 16GB DIMM DDR4 3000MT/s           | 2         | 0.68%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 0.68%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.68%   |
| Kingston RAM 9905744-077.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 0.68%   |
| Unknown                                                          | 2         | 0.68%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.34%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.34%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.34%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.34%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.34%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 119       | 52.65%  |
| DDR3    | 67        | 29.65%  |
| DDR2    | 9         | 3.98%   |
| LPDDR4  | 8         | 3.54%   |
| SDRAM   | 6         | 2.65%   |
| Unknown | 6         | 2.65%   |
| DDR5    | 5         | 2.21%   |
| LPDDR3  | 3         | 1.33%   |
| LPDDR5  | 2         | 0.88%   |
| DDR     | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 148       | 65.78%  |
| DIMM         | 58        | 25.78%  |
| Row Of Chips | 14        | 6.22%   |
| Unknown      | 3         | 1.33%   |
| Chip         | 2         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 86        | 33.86%  |
| 4096  | 86        | 33.86%  |
| 16384 | 40        | 15.75%  |
| 2048  | 22        | 8.66%   |
| 32768 | 11        | 4.33%   |
| 1024  | 9         | 3.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 52        | 20.16%  |
| 2667    | 50        | 19.38%  |
| 3200    | 42        | 16.28%  |
| 2400    | 16        | 6.2%    |
| 1333    | 16        | 6.2%    |
| 2133    | 12        | 4.65%   |
| 3266    | 9         | 3.49%   |
| Unknown | 6         | 2.33%   |
| 3600    | 5         | 1.94%   |
| 1334    | 5         | 1.94%   |
| 8400    | 4         | 1.55%   |
| 667     | 4         | 1.55%   |
| 3733    | 3         | 1.16%   |
| 1867    | 3         | 1.16%   |
| 800     | 3         | 1.16%   |
| 5600    | 2         | 0.78%   |
| 4199    | 2         | 0.78%   |
| 3466    | 2         | 0.78%   |
| 3400    | 2         | 0.78%   |
| 3000    | 2         | 0.78%   |
| 1866    | 2         | 0.78%   |
| 7467    | 1         | 0.39%   |
| 6400    | 1         | 0.39%   |
| 6000    | 1         | 0.39%   |
| 5200    | 1         | 0.39%   |
| 4800    | 1         | 0.39%   |
| 4333    | 1         | 0.39%   |
| 4267    | 1         | 0.39%   |
| 3933    | 1         | 0.39%   |
| 2666    | 1         | 0.39%   |
| 2048    | 1         | 0.39%   |
| 1776    | 1         | 0.39%   |
| 1067    | 1         | 0.39%   |
| 1066    | 1         | 0.39%   |
| 975     | 1         | 0.39%   |
| 933     | 1         | 0.39%   |
| 533     | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 3         | 37.5%   |
| Hewlett-Packard     | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |
| Prolific Technology | 1         | 12.5%   |
| Brother Industries  | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson XP-3100 Series         | 1         | 12.5%   |
| Seiko Epson L380 Series            | 1         | 12.5%   |
| Seiko Epson L3110 Series           | 1         | 12.5%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 12.5%   |
| Prolific PL2305 Parallel Port      | 1         | 12.5%   |
| HP Ink Tank Wireless 410 series    | 1         | 12.5%   |
| HP Deskjet 2050 J510               | 1         | 12.5%   |
| Brother DCP-T500W                  | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 70        | 23.73%  |
| IMC Networks                           | 33        | 11.19%  |
| Realtek Semiconductor                  | 23        | 7.8%    |
| Microdia                               | 23        | 7.8%    |
| Quanta                                 | 18        | 6.1%    |
| Cheng Uei Precision Industry (Foxlink) | 14        | 4.75%   |
| Sunplus Innovation Technology          | 13        | 4.41%   |
| Suyin                                  | 12        | 4.07%   |
| Bison Electronics                      | 10        | 3.39%   |
| Syntek                                 | 8         | 2.71%   |
| Luxvisions Innotech Limited            | 7         | 2.37%   |
| Lite-On Technology                     | 6         | 2.03%   |
| Apple                                  | 6         | 2.03%   |
| Logitech                               | 5         | 1.69%   |
| Generalplus Technology                 | 4         | 1.36%   |
| Alcor Micro                            | 4         | 1.36%   |
| Silicon Motion                         | 3         | 1.02%   |
| Ricoh                                  | 3         | 1.02%   |
| KYE Systems (Mouse Systems)            | 3         | 1.02%   |
| Sonix Technology                       | 2         | 0.68%   |
| ShineTech                              | 2         | 0.68%   |
| Pixart Imaging                         | 2         | 0.68%   |
| OmniVision Technologies                | 2         | 0.68%   |
| Microsoft                              | 2         | 0.68%   |
| Jieli Technology                       | 2         | 0.68%   |
| Importek                               | 2         | 0.68%   |
| icSpring                               | 2         | 0.68%   |
| Z-Star Microelectronics                | 1         | 0.34%   |
| Unknown                                | 1         | 0.34%   |
| Trust                                  | 1         | 0.34%   |
| Shine-optics                           | 1         | 0.34%   |
| Samsung Electronics                    | 1         | 0.34%   |
| Novatek Microelectronics               | 1         | 0.34%   |
| MacroSilicon                           | 1         | 0.34%   |
| Lenovo                                 | 1         | 0.34%   |
| Genesys Logic                          | 1         | 0.34%   |
| GEMBIRD                                | 1         | 0.34%   |
| Foxconn / Hon Hai                      | 1         | 0.34%   |
| eMeet                                  | 1         | 0.34%   |
| Arkmicro Technologies                  | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 12        | 4.07%   |
| Chicony Integrated Camera                                                  | 12        | 4.07%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 3.05%   |
| Realtek Integrated_Webcam_HD                                               | 8         | 2.71%   |
| IMC Networks Integrated Camera                                             | 8         | 2.71%   |
| Chicony HP Truevision HD                                                   | 6         | 2.03%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 5         | 1.69%   |
| Chicony TOSHIBA Web Camera - HD                                            | 5         | 1.69%   |
| Realtek Integrated Webcam                                                  | 4         | 1.36%   |
| Quanta HD Webcam                                                           | 4         | 1.36%   |
| Logitech Webcam C270                                                       | 4         | 1.36%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.36%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 4         | 1.36%   |
| Syntek Integrated Camera                                                   | 3         | 1.02%   |
| Suyin Integrated_Webcam_HD                                                 | 3         | 1.02%   |
| Suyin HP Truevision HD                                                     | 3         | 1.02%   |
| Suyin HD WebCam                                                            | 3         | 1.02%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.02%   |
| Quanta HP Wide Vision HD Camera                                            | 3         | 1.02%   |
| Quanta HP Webcam                                                           | 3         | 1.02%   |
| Microdia USB 2.0 Camera                                                    | 3         | 1.02%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 3         | 1.02%   |
| IMC Networks VGA UVC WebCam                                                | 3         | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.02%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 3         | 1.02%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.02%   |
| Chicony HD User Facing                                                     | 3         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.02%   |
| Bison Integrated Camera                                                    | 3         | 1.02%   |
| Apple FaceTime HD Camera                                                   | 3         | 1.02%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.68%   |
| Syntek EasyCamera                                                          | 2         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 2         | 0.68%   |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.68%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 2         | 0.68%   |
| ShineTech USB2.0 HD UVC WebCam                                             | 2         | 0.68%   |
| Realtek HP Truevision HD                                                   | 2         | 0.68%   |
| Realtek HP "Truevision HD" laptop camera                                   | 2         | 0.68%   |
| Realtek HD WebCam                                                          | 2         | 0.68%   |
| Quanta HP Webcam-50                                                        | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 24.14%  |
| Validity Sensors           | 6         | 20.69%  |
| Shenzhen Goodix Technology | 4         | 13.79%  |
| Elan Microelectronics      | 4         | 13.79%  |
| AuthenTec                  | 4         | 13.79%  |
| Upek                       | 2         | 6.9%    |
| STMicroelectronics         | 1         | 3.45%   |
| LighTuning Technology      | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 4         | 13.79%  |
| AuthenTec AES1600                                      | 3         | 10.34%  |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 6.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 6.9%    |
| Synaptics  WBDI                                        | 2         | 6.9%    |
| Elan ELAN:Fingerprint                                  | 2         | 6.9%    |
| Elan ELAN:ARM-M4                                       | 2         | 6.9%    |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.45%   |
| Validity Sensors VFS491                                | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.45%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.45%   |
| Synaptics WBDI                                         | 1         | 3.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 3.45%   |
| Synaptics Fingerprint scanner                          | 1         | 3.45%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 3.45%   |
| LighTuning Fingerprint Sensor                          | 1         | 3.45%   |
| AuthenTec AES2810                                      | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 44.44%  |
| O2 Micro    | 3         | 33.33%  |
| Upek        | 1         | 11.11%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 305       | 73.32%  |
| 1     | 96        | 23.08%  |
| 2     | 13        | 3.13%   |
| 5     | 1         | 0.24%   |
| 3     | 1         | 0.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 29        | 22.48%  |
| Fingerprint reader       | 29        | 22.48%  |
| Net/wireless             | 27        | 20.93%  |
| Multimedia controller    | 14        | 10.85%  |
| Chipcard                 | 8         | 6.2%    |
| Bluetooth                | 5         | 3.88%   |
| Sound                    | 4         | 3.1%    |
| Communication controller | 4         | 3.1%    |
| Camera                   | 4         | 3.1%    |
| Storage                  | 3         | 2.33%   |
| Network                  | 1         | 0.78%   |
| Net/ethernet             | 1         | 0.78%   |


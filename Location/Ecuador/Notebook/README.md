Linux in Ecuador - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 406

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Gaming Laptop      | [f6e4512df5](https://linux-hardware.org/?probe=f6e4512df5) | Dec 30, 2025 |
| HP            | Pavilion g4                 | [c1a1b34ecc](https://linux-hardware.org/?probe=c1a1b34ecc) | Dec 25, 2025 |
| Notebook      | NH5xAx                      | [4f6c01dbca](https://linux-hardware.org/?probe=4f6c01dbca) | Dec 16, 2025 |
| ASUSTek       | G73Jw                       | [fc5996b06a](https://linux-hardware.org/?probe=fc5996b06a) | Dec 13, 2025 |
| ASUSTek       | G73Jw                       | [e85f6e2840](https://linux-hardware.org/?probe=e85f6e2840) | Dec 13, 2025 |
| Google        | Robo                        | [18939a9871](https://linux-hardware.org/?probe=18939a9871) | Dec 10, 2025 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [f881baea49](https://linux-hardware.org/?probe=f881baea49) | Dec 10, 2025 |
| HP            | Pavilion g4                 | [df34fc3443](https://linux-hardware.org/?probe=df34fc3443) | Dec 06, 2025 |
| HP            | Pavilion 14                 | [ad9bffe3b3](https://linux-hardware.org/?probe=ad9bffe3b3) | Nov 28, 2025 |
| MSI           | Thin 15 B13UC               | [6776dfcf29](https://linux-hardware.org/?probe=6776dfcf29) | Nov 26, 2025 |
| MSI           | Stealth GS77 12UE           | [34c2f9b0a8](https://linux-hardware.org/?probe=34c2f9b0a8) | Nov 17, 2025 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [df8020df97](https://linux-hardware.org/?probe=df8020df97) | Nov 11, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9c74bf8f67](https://linux-hardware.org/?probe=9c74bf8f67) | Nov 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [dd03deae7a](https://linux-hardware.org/?probe=dd03deae7a) | Nov 09, 2025 |
| Acer          | Predator PH315-51           | [29baa91dd5](https://linux-hardware.org/?probe=29baa91dd5) | Oct 26, 2025 |
| Unknown       | Unknown                     | [65635ebccb](https://linux-hardware.org/?probe=65635ebccb) | Oct 25, 2025 |
| Toshiba       | Satellite L50-B             | [e15338ac63](https://linux-hardware.org/?probe=e15338ac63) | Oct 16, 2025 |
| HP            | Laptop 14-cf3xxx            | [29c498aaab](https://linux-hardware.org/?probe=29c498aaab) | Oct 11, 2025 |
| HP            | Laptop 14-cf3xxx            | [844e31335b](https://linux-hardware.org/?probe=844e31335b) | Oct 11, 2025 |
| Google        | Setzer                      | [59d6153e0f](https://linux-hardware.org/?probe=59d6153e0f) | Oct 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [d19b7e2930](https://linux-hardware.org/?probe=d19b7e2930) | Oct 03, 2025 |
| Dell          | Inspiron 15 7000 Gaming     | [4fc627f17d](https://linux-hardware.org/?probe=4fc627f17d) | Sep 23, 2025 |
| Dell          | Unidentified System         | [30626f4bfe](https://linux-hardware.org/?probe=30626f4bfe) | Sep 21, 2025 |
| Dell          | Inspiron 5547               | [090c9ddad9](https://linux-hardware.org/?probe=090c9ddad9) | Sep 09, 2025 |
| Unknown       | Unknown                     | [b8528a3d1d](https://linux-hardware.org/?probe=b8528a3d1d) | Sep 06, 2025 |
| Lenovo        | ThinkPad P16 Gen 2 21FA0... | [f607ea28bc](https://linux-hardware.org/?probe=f607ea28bc) | Aug 24, 2025 |
| ASUSTek       | GL502VS                     | [0cfd13b331](https://linux-hardware.org/?probe=0cfd13b331) | Aug 04, 2025 |
| HP            | Compaq Presario CQ40        | [a8f55661e6](https://linux-hardware.org/?probe=a8f55661e6) | Aug 04, 2025 |
| Lenovo        | V15 G3 ABA 82TV             | [f85b5a4fe2](https://linux-hardware.org/?probe=f85b5a4fe2) | Jul 31, 2025 |
| HP            | Stream Notebook PC 13       | [a26dcc7e8b](https://linux-hardware.org/?probe=a26dcc7e8b) | Jul 05, 2025 |
| System76      | Pangolin                    | [7aadbc0b69](https://linux-hardware.org/?probe=7aadbc0b69) | Jun 30, 2025 |
| HP            | ProBook 450 G3              | [a1839d8ce8](https://linux-hardware.org/?probe=a1839d8ce8) | Jun 29, 2025 |
| Dell          | Latitude 5500               | [7fe46a5914](https://linux-hardware.org/?probe=7fe46a5914) | Jun 23, 2025 |
| Dell          | Latitude 5500               | [801b8856dc](https://linux-hardware.org/?probe=801b8856dc) | Jun 19, 2025 |
| Apple         | MacBookPro11,1              | [8370a3f2fa](https://linux-hardware.org/?probe=8370a3f2fa) | Jun 17, 2025 |
| Sony          | VPCEG25FL                   | [d110c6abee](https://linux-hardware.org/?probe=d110c6abee) | Jun 14, 2025 |
| Lenovo        | ThinkPad X220 42872WS       | [735deb0809](https://linux-hardware.org/?probe=735deb0809) | Jun 03, 2025 |
| Dell          | Inspiron 15 3525            | [0b27f4ec6e](https://linux-hardware.org/?probe=0b27f4ec6e) | Jun 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [3b9eb0d1f8](https://linux-hardware.org/?probe=3b9eb0d1f8) | May 28, 2025 |
| Dell          | Inspiron 5547               | [97208d54f8](https://linux-hardware.org/?probe=97208d54f8) | May 27, 2025 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c2b6c378a0](https://linux-hardware.org/?probe=c2b6c378a0) | May 17, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [130b97292b](https://linux-hardware.org/?probe=130b97292b) | May 15, 2025 |
| ASUSTek       | E202SA                      | [425064df68](https://linux-hardware.org/?probe=425064df68) | May 09, 2025 |
| HP            | Compaq 6730s                | [96bd92d6f0](https://linux-hardware.org/?probe=96bd92d6f0) | May 06, 2025 |
| Dell          | Inspiron 5547               | [9b2ef80964](https://linux-hardware.org/?probe=9b2ef80964) | May 05, 2025 |
| Dell          | Inspiron 14-3467            | [bf2355ffc1](https://linux-hardware.org/?probe=bf2355ffc1) | May 05, 2025 |
| Dell          | Inspiron 14-3467            | [070c57d0ef](https://linux-hardware.org/?probe=070c57d0ef) | Apr 30, 2025 |
| GPU Compan... | GWTN141-10                  | [4a3702a1da](https://linux-hardware.org/?probe=4a3702a1da) | Apr 25, 2025 |
| HP            | ENVY m6 Notebook            | [e1e9dc0d89](https://linux-hardware.org/?probe=e1e9dc0d89) | Apr 21, 2025 |
| Dell          | Inspiron 3185               | [1f523e5dc3](https://linux-hardware.org/?probe=1f523e5dc3) | Apr 19, 2025 |
| HP            | 1000                        | [525b9bb521](https://linux-hardware.org/?probe=525b9bb521) | Apr 18, 2025 |
| Dell          | Inspiron 3501               | [7b341170e4](https://linux-hardware.org/?probe=7b341170e4) | Apr 16, 2025 |
| ASUSTek       | FX503VD                     | [ee6ef151ae](https://linux-hardware.org/?probe=ee6ef151ae) | Mar 23, 2025 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [d28a6d121b](https://linux-hardware.org/?probe=d28a6d121b) | Mar 21, 2025 |
| HP            | Pavilion dv5                | [743b1c6a08](https://linux-hardware.org/?probe=743b1c6a08) | Mar 16, 2025 |
| Dell          | Inspiron 15 5510            | [6ea0e9c2eb](https://linux-hardware.org/?probe=6ea0e9c2eb) | Mar 12, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c769caad0e](https://linux-hardware.org/?probe=c769caad0e) | Mar 12, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2f49c786af](https://linux-hardware.org/?probe=2f49c786af) | Mar 12, 2025 |
| Lenovo        | ThinkPad T450 20BUS2RN09    | [f09c87a871](https://linux-hardware.org/?probe=f09c87a871) | Mar 03, 2025 |
| HP            | Laptop 14-ck0xxx            | [5fab8982a9](https://linux-hardware.org/?probe=5fab8982a9) | Feb 21, 2025 |
| Acer          | Aspire A315-44P             | [1978b4be35](https://linux-hardware.org/?probe=1978b4be35) | Feb 08, 2025 |
| Apple         | MacBookPro12,1              | [902eebca03](https://linux-hardware.org/?probe=902eebca03) | Feb 05, 2025 |
| HP            | ProBook 4440s               | [d9e21d83a4](https://linux-hardware.org/?probe=d9e21d83a4) | Jan 30, 2025 |
| Apple         | MacBookPro12,1              | [ecbc053b77](https://linux-hardware.org/?probe=ecbc053b77) | Jan 25, 2025 |
| HP            | ProBook 440 G7              | [91b1fe70a1](https://linux-hardware.org/?probe=91b1fe70a1) | Jan 23, 2025 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0U... | [c9c83d8b45](https://linux-hardware.org/?probe=c9c83d8b45) | Jan 20, 2025 |
| ASUSTek       | X455LJ                      | [1b26882393](https://linux-hardware.org/?probe=1b26882393) | Jan 20, 2025 |
| Lenovo        | ThinkPad T480 20L6S3RVUS    | [7f87f4d08f](https://linux-hardware.org/?probe=7f87f4d08f) | Jan 20, 2025 |
| HP            | Notebook                    | [6f33e3c4b9](https://linux-hardware.org/?probe=6f33e3c4b9) | Jan 19, 2025 |
| ASUSTek       | X455LJ                      | [dae3d540f6](https://linux-hardware.org/?probe=dae3d540f6) | Dec 18, 2024 |
| ASUSTek       | E202SA                      | [b4fe788f4e](https://linux-hardware.org/?probe=b4fe788f4e) | Dec 17, 2024 |
| Lenovo        | Y50-70 20378                | [c70be6f167](https://linux-hardware.org/?probe=c70be6f167) | Dec 04, 2024 |
| Dell          | Latitude E6440              | [2c75de8400](https://linux-hardware.org/?probe=2c75de8400) | Dec 01, 2024 |
| ASUSTek       | E202SA                      | [18a63b065d](https://linux-hardware.org/?probe=18a63b065d) | Nov 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2264ba28f3](https://linux-hardware.org/?probe=2264ba28f3) | Oct 24, 2024 |
| Dell          | Latitude E6420              | [007ca74afb](https://linux-hardware.org/?probe=007ca74afb) | Oct 21, 2024 |
| Dell          | Latitude E6420              | [a6a2d8c1fe](https://linux-hardware.org/?probe=a6a2d8c1fe) | Oct 20, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5820bd151b](https://linux-hardware.org/?probe=5820bd151b) | Oct 17, 2024 |
| Apple         | MacBookPro12,1              | [479b6dd12a](https://linux-hardware.org/?probe=479b6dd12a) | Oct 16, 2024 |
| Apple         | MacBookPro12,1              | [9b61bff954](https://linux-hardware.org/?probe=9b61bff954) | Oct 16, 2024 |
| HP            | Victus by Gaming Laptop ... | [0b81ce4446](https://linux-hardware.org/?probe=0b81ce4446) | Oct 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [90af0212ea](https://linux-hardware.org/?probe=90af0212ea) | Sep 27, 2024 |
| Dell          | Inspiron 3458               | [79c31f85e1](https://linux-hardware.org/?probe=79c31f85e1) | Sep 13, 2024 |
| HP            | Pavilion g4                 | [c9131e779e](https://linux-hardware.org/?probe=c9131e779e) | Aug 24, 2024 |
| Unknown       | Unknown                     | [bbbbf2ec13](https://linux-hardware.org/?probe=bbbbf2ec13) | Aug 13, 2024 |
| Acer          | Swift SFE16-43              | [083b0cac5f](https://linux-hardware.org/?probe=083b0cac5f) | Aug 12, 2024 |
| HP            | Laptop 15-gw0xxx            | [cf835ce8d2](https://linux-hardware.org/?probe=cf835ce8d2) | Aug 11, 2024 |
| HP            | Notebook                    | [1a796d1daf](https://linux-hardware.org/?probe=1a796d1daf) | Aug 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [32d11d630e](https://linux-hardware.org/?probe=32d11d630e) | Aug 01, 2024 |
| HP            | Laptop 15-gw0xxx            | [f50ff2bcfb](https://linux-hardware.org/?probe=f50ff2bcfb) | Jul 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [5cd2fdb7f3](https://linux-hardware.org/?probe=5cd2fdb7f3) | Jul 23, 2024 |
| HP            | Pavilion g4                 | [922cae179f](https://linux-hardware.org/?probe=922cae179f) | Jul 13, 2024 |
| Apple         | MacBookPro9,2               | [c802131da8](https://linux-hardware.org/?probe=c802131da8) | Jul 07, 2024 |
| Dell          | Vostro 5502                 | [02acef5e70](https://linux-hardware.org/?probe=02acef5e70) | Jul 04, 2024 |
| Acer          | Aspire A315-44P             | [d139897a73](https://linux-hardware.org/?probe=d139897a73) | Jun 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [6fb2ca786a](https://linux-hardware.org/?probe=6fb2ca786a) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [f5baa7dc23](https://linux-hardware.org/?probe=f5baa7dc23) | Jun 19, 2024 |
| Toshiba       | Satellite P855              | [e3c736f4b8](https://linux-hardware.org/?probe=e3c736f4b8) | Jun 18, 2024 |
| Dell          | Inspiron N4050              | [5d77f14b5f](https://linux-hardware.org/?probe=5d77f14b5f) | Jun 18, 2024 |
| Toshiba       | Satellite P855              | [71b541e230](https://linux-hardware.org/?probe=71b541e230) | Jun 16, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | [d447330673](https://linux-hardware.org/?probe=d447330673) | Jun 01, 2024 |
| Lenovo        | V330-14ISK 81AY             | [fd2bdae039](https://linux-hardware.org/?probe=fd2bdae039) | May 24, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0U... | [630273772a](https://linux-hardware.org/?probe=630273772a) | May 19, 2024 |
| Acer          | Aspire V5-471P              | [00d54a6432](https://linux-hardware.org/?probe=00d54a6432) | May 13, 2024 |
| Acer          | Aspire V5-471P              | [d9b4f36303](https://linux-hardware.org/?probe=d9b4f36303) | May 13, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [a823e9adf2](https://linux-hardware.org/?probe=a823e9adf2) | Apr 26, 2024 |
| HP            | 1000                        | [dee2aa2dd9](https://linux-hardware.org/?probe=dee2aa2dd9) | Apr 25, 2024 |
| Apple         | MacBookPro9,2               | [d4f3102f5c](https://linux-hardware.org/?probe=d4f3102f5c) | Apr 25, 2024 |
| MSI           | Stealth GS77 12UE           | [47ff584537](https://linux-hardware.org/?probe=47ff584537) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | [39dff10b12](https://linux-hardware.org/?probe=39dff10b12) | Apr 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a95e92f1f5](https://linux-hardware.org/?probe=a95e92f1f5) | Mar 16, 2024 |
| Dell          | G15 5515                    | [527be515b4](https://linux-hardware.org/?probe=527be515b4) | Mar 12, 2024 |
| Toshiba       | Satellite P855              | [cb7eb1810c](https://linux-hardware.org/?probe=cb7eb1810c) | Feb 26, 2024 |
| HP            | OMEN by Laptop              | [68bbab3ac1](https://linux-hardware.org/?probe=68bbab3ac1) | Feb 19, 2024 |
| Google        | Blooglet                    | [66b986a87d](https://linux-hardware.org/?probe=66b986a87d) | Feb 19, 2024 |
| HP            | 245 G8                      | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Google        | Blooglet                    | [34a54def3d](https://linux-hardware.org/?probe=34a54def3d) | Feb 13, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | [f4f20111f0](https://linux-hardware.org/?probe=f4f20111f0) | Feb 12, 2024 |
| Toshiba       | Satellite C55-B             | [f9989aa45a](https://linux-hardware.org/?probe=f9989aa45a) | Feb 09, 2024 |
| Dell          | Latitude D630               | [bf9ce8c208](https://linux-hardware.org/?probe=bf9ce8c208) | Jan 21, 2024 |
| Dell          | Latitude D630               | [b2a68014db](https://linux-hardware.org/?probe=b2a68014db) | Jan 21, 2024 |
| Acer          | Aspire A715-51G             | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | [3a14a938f8](https://linux-hardware.org/?probe=3a14a938f8) | Jan 08, 2024 |
| HP            | 1000                        | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| HP            | Laptop 15-dw1xxx            | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [cc934b68d9](https://linux-hardware.org/?probe=cc934b68d9) | Nov 22, 2023 |
| HP            | Unknown                     | [d065dfae65](https://linux-hardware.org/?probe=d065dfae65) | Nov 19, 2023 |
| HP            | Unknown                     | [539958ff9d](https://linux-hardware.org/?probe=539958ff9d) | Nov 19, 2023 |
| MSI           | PRO H610M-G DDR4            | [5955e4e776](https://linux-hardware.org/?probe=5955e4e776) | Nov 15, 2023 |
| MSI           | PRO H610M-G DDR4            | [f41807e01e](https://linux-hardware.org/?probe=f41807e01e) | Nov 14, 2023 |
| Toshiba       | Satellite S55-B             | [bcc2e19a3a](https://linux-hardware.org/?probe=bcc2e19a3a) | Nov 12, 2023 |
| HP            | 245 G8                      | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | 245 G8                      | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| Razer         | Blade Stealth               | [0ebbfdba6a](https://linux-hardware.org/?probe=0ebbfdba6a) | Oct 26, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [21a31e5298](https://linux-hardware.org/?probe=21a31e5298) | Oct 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | [46e4f7a743](https://linux-hardware.org/?probe=46e4f7a743) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Alienware     | m15                         | [9ac9acc336](https://linux-hardware.org/?probe=9ac9acc336) | Oct 12, 2023 |
| Alienware     | m15                         | [8b4a8c8fc9](https://linux-hardware.org/?probe=8b4a8c8fc9) | Oct 12, 2023 |
| Apple         | MacBookPro12,1              | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Toshiba       | Satellite A205              | [7b78b2ea5b](https://linux-hardware.org/?probe=7b78b2ea5b) | Oct 06, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | [8c1d3fc469](https://linux-hardware.org/?probe=8c1d3fc469) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | [c38ca27643](https://linux-hardware.org/?probe=c38ca27643) | Sep 29, 2023 |
| Valve         | Jupiter                     | [f4582a5754](https://linux-hardware.org/?probe=f4582a5754) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [5fac0d7732](https://linux-hardware.org/?probe=5fac0d7732) | Sep 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | [09c45a1e2d](https://linux-hardware.org/?probe=09c45a1e2d) | Sep 17, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | [eb0aa53dc9](https://linux-hardware.org/?probe=eb0aa53dc9) | Sep 08, 2023 |
| Toshiba       | Satellite A205              | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | [ecc10a1197](https://linux-hardware.org/?probe=ecc10a1197) | Sep 04, 2023 |
| Toshiba       | Satellite L50-B             | [9dd40cd022](https://linux-hardware.org/?probe=9dd40cd022) | Sep 03, 2023 |
| HP            | Laptop 14-cm0xxx            | [a1caab6466](https://linux-hardware.org/?probe=a1caab6466) | Aug 27, 2023 |
| Apple         | MacBookPro9,2               | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| Apple         | MacBookPro5,5               | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5bd12768fa](https://linux-hardware.org/?probe=5bd12768fa) | Aug 09, 2023 |
| Dell          | Vostro 3480                 | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Toshiba       | Satellite A135              | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| Toshiba       | Satellite A135              | [5bd6d0c2d8](https://linux-hardware.org/?probe=5bd6d0c2d8) | Jul 20, 2023 |
| HP            | ENVY m6 Notebook            | [602c50a904](https://linux-hardware.org/?probe=602c50a904) | Jul 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Dell          | Inspiron 3493               | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| Acer          | Aspire A515-45              | [f661806559](https://linux-hardware.org/?probe=f661806559) | Jun 02, 2023 |
| Acer          | Aspire A515-45              | [a57949da97](https://linux-hardware.org/?probe=a57949da97) | Jun 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| Acer          | Extensa 5220                | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Sony          | VPCEG23EL                   | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [5cb6709055](https://linux-hardware.org/?probe=5cb6709055) | Apr 20, 2023 |
| HP            | Notebook                    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| HP            | 245 G6                      | [c6a1e2951c](https://linux-hardware.org/?probe=c6a1e2951c) | Apr 05, 2023 |
| Valve         | Jupiter                     | [078e440a68](https://linux-hardware.org/?probe=078e440a68) | Mar 31, 2023 |
| Acer          | Aspire A515-43              | [1812fe9a19](https://linux-hardware.org/?probe=1812fe9a19) | Mar 26, 2023 |
| Acer          | Aspire A515-43              | [a302d93972](https://linux-hardware.org/?probe=a302d93972) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [9e45f992a1](https://linux-hardware.org/?probe=9e45f992a1) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [34fd631d2b](https://linux-hardware.org/?probe=34fd631d2b) | Mar 22, 2023 |
| Samsung       | R519/R719                   | [9e1cdf3582](https://linux-hardware.org/?probe=9e1cdf3582) | Mar 17, 2023 |
| HP            | Laptop 14-cf3xxx            | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Dell          | Latitude E6420              | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| Dell          | Inspiron 14-3467            | [5bf68a313d](https://linux-hardware.org/?probe=5bf68a313d) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | [72d2220b42](https://linux-hardware.org/?probe=72d2220b42) | Feb 07, 2023 |
| Google        | Setzer                      | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [85dbbce597](https://linux-hardware.org/?probe=85dbbce597) | Jan 27, 2023 |
| Alienware     | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | [b4d38fb35a](https://linux-hardware.org/?probe=b4d38fb35a) | Jan 18, 2023 |
| Gateway       | NV55C                       | [b8ae4adfdc](https://linux-hardware.org/?probe=b8ae4adfdc) | Jan 12, 2023 |
| Apple         | MacBookPro16,2              | [d7abd06e34](https://linux-hardware.org/?probe=d7abd06e34) | Jan 08, 2023 |
| Apple         | MacBookPro16,2              | [aa67834a96](https://linux-hardware.org/?probe=aa67834a96) | Jan 08, 2023 |
| HP            | ENVY 15                     | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf4ba78c7d](https://linux-hardware.org/?probe=cf4ba78c7d) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Dynabook      | PORTEGE X40-J               | [3f1fc426b0](https://linux-hardware.org/?probe=3f1fc426b0) | Dec 05, 2022 |
| HP            | Laptop 14-cf3xxx            | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| HP            | Laptop 15-da0xxx            | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | Laptop 15-dy2xxx            | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Gateway       | NV510P                      | [13fe5a5e78](https://linux-hardware.org/?probe=13fe5a5e78) | Oct 16, 2022 |
| Gateway       | NV510P                      | [7cb93d25ac](https://linux-hardware.org/?probe=7cb93d25ac) | Oct 16, 2022 |
| HP            | Laptop 14-cf3xxx            | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| HP            | Laptop 15-da0xxx            | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| HP            | Laptop 14-cf3xxx            | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| HP            | Notebook                    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Dell          | Inspiron 7472               | [eaab7f2460](https://linux-hardware.org/?probe=eaab7f2460) | Aug 09, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| Dell          | Latitude E6420              | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| HP            | Laptop 14-cf3xxx            | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| MSI           | GF63 Thin 9SC               | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| MSI           | GF63 Thin 9SC               | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| HP            | Laptop 14-cf3xxx            | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| Dell          | Latitude 5520               | [6e9be54f47](https://linux-hardware.org/?probe=6e9be54f47) | Jul 09, 2022 |
| Apple         | MacBookPro12,1              | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Google        | Delbin                      | [26becdfc83](https://linux-hardware.org/?probe=26becdfc83) | Jun 26, 2022 |
| ASUSTek       | X555QG                      | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| Fujitsu       | LIFEBOOK E752               | [c434320a62](https://linux-hardware.org/?probe=c434320a62) | Jun 19, 2022 |
| ASUSTek       | X411UN                      | [70d24e4237](https://linux-hardware.org/?probe=70d24e4237) | Jun 02, 2022 |
| ASUSTek       | UX360CA                     | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| Alienware     | 15 R3                       | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| HP            | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Chuwi         | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Sony          | SVE14113ELW                 | [647c09a7be](https://linux-hardware.org/?probe=647c09a7be) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| Lenovo        | G580 20150                  | [ec5867b2f7](https://linux-hardware.org/?probe=ec5867b2f7) | May 17, 2022 |
| Lenovo        | G580 20150                  | [9b06242456](https://linux-hardware.org/?probe=9b06242456) | May 17, 2022 |
| Toshiba       | Satellite L45-B             | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite L50-B             | [e559318a8b](https://linux-hardware.org/?probe=e559318a8b) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| HP            | Laptop 14-cf3xxx            | [e049bbd414](https://linux-hardware.org/?probe=e049bbd414) | Apr 26, 2022 |
| HP            | Unknown                     | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| HP            | Unknown                     | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| HP            | Pavilion dv6                | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| Lenovo        | V15-IIL 82C5                | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| Sony          | VPCEG30EL                   | [c19f1a4739](https://linux-hardware.org/?probe=c19f1a4739) | Mar 26, 2022 |
| Sony          | SVE14A25CLB                 | [2e6afba454](https://linux-hardware.org/?probe=2e6afba454) | Mar 25, 2022 |
| Apple         | MacBookPro12,1              | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Dell          | Inspiron 7547               | [af0de64399](https://linux-hardware.org/?probe=af0de64399) | Mar 22, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Razer         | Blade Stealth               | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| HP            | Laptop 14-cf3xxx            | [faae36d70e](https://linux-hardware.org/?probe=faae36d70e) | Mar 17, 2022 |
| HP            | Laptop 14-cf3xxx            | [4d5aa250a1](https://linux-hardware.org/?probe=4d5aa250a1) | Mar 17, 2022 |
| Toshiba       | Satellite C55D-A            | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| HP            | 15 Notebook PC              | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| HP            | EliteBook Folio 9470m       | [bd4f7daadb](https://linux-hardware.org/?probe=bd4f7daadb) | Mar 10, 2022 |
| Compal        | PBL2021                     | [4e367db737](https://linux-hardware.org/?probe=4e367db737) | Feb 28, 2022 |
| Dell          | G5 5587                     | [5f51492976](https://linux-hardware.org/?probe=5f51492976) | Jan 29, 2022 |
| Dell          | Latitude 7280               | [fdf5a41dcc](https://linux-hardware.org/?probe=fdf5a41dcc) | Jan 25, 2022 |
| Dell          | Latitude 7280               | [b4c6f2fe35](https://linux-hardware.org/?probe=b4c6f2fe35) | Jan 25, 2022 |
| Dell          | Inspiron 3442               | [d8fc419747](https://linux-hardware.org/?probe=d8fc419747) | Jan 18, 2022 |
| Acer          | Aspire A515-56              | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Acer          | Aspire A515-56              | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [ef48db912e](https://linux-hardware.org/?probe=ef48db912e) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| ASUSTek       | G750JX                      | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| Google        | Treeya                      | [a0ab206cd8](https://linux-hardware.org/?probe=a0ab206cd8) | Nov 09, 2021 |
| Dell          | Inspiron MP061              | [d6ed71bc78](https://linux-hardware.org/?probe=d6ed71bc78) | Nov 02, 2021 |
| HP            | G42                         | [5ee39658a8](https://linux-hardware.org/?probe=5ee39658a8) | Oct 28, 2021 |
| Timi          | RedmiBook 14-APCS           | [d31c8b483c](https://linux-hardware.org/?probe=d31c8b483c) | Oct 28, 2021 |
| HP            | G42                         | [a8181c9c9b](https://linux-hardware.org/?probe=a8181c9c9b) | Oct 24, 2021 |
| Fujitsu       | LIFEBOOK E752               | [177f79d880](https://linux-hardware.org/?probe=177f79d880) | Oct 18, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| Dell          | Inspiron 3593               | [2297765c40](https://linux-hardware.org/?probe=2297765c40) | Oct 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| HP            | 240 G6 Notebook PC          | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| Unknown       | Unknown                     | [449fdc2d2d](https://linux-hardware.org/?probe=449fdc2d2d) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| Toshiba       | Satellite S55-B             | [c4ec7d25a7](https://linux-hardware.org/?probe=c4ec7d25a7) | Aug 21, 2021 |
| HP            | Pavilion g4                 | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| Unknown       | Unknown                     | [008647318c](https://linux-hardware.org/?probe=008647318c) | Aug 09, 2021 |
| Unknown       | Unknown                     | [5de2d0ae61](https://linux-hardware.org/?probe=5de2d0ae61) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| Acer          | TravelMate X3410-M          | [18b5757039](https://linux-hardware.org/?probe=18b5757039) | Jul 29, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK E752               | [a071db12c9](https://linux-hardware.org/?probe=a071db12c9) | Jul 12, 2021 |
| Google        | Banjo                       | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| Google        | Grunt                       | [2bb0921a94](https://linux-hardware.org/?probe=2bb0921a94) | Jul 01, 2021 |
| Google        | Grunt                       | [4ea5c8f438](https://linux-hardware.org/?probe=4ea5c8f438) | Jul 01, 2021 |
| Google        | Kip                         | [7634152b76](https://linux-hardware.org/?probe=7634152b76) | Jun 21, 2021 |
| Acer          | TravelMate B117-M           | [a5fc625cf2](https://linux-hardware.org/?probe=a5fc625cf2) | Jun 04, 2021 |
| MSI           | GF63 Thin 9SC               | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| HP            | 1000                        | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | 1000                        | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| Acer          | Aspire V5-121               | [cc73e2b026](https://linux-hardware.org/?probe=cc73e2b026) | May 13, 2021 |
| HP            | 1000                        | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| Lenovo        | ThinkPad E15 20REA00000     | [1ac42dd429](https://linux-hardware.org/?probe=1ac42dd429) | May 09, 2021 |
| MSI           | GF63 Thin 9SC               | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Samsung       | 550XCJ/550XCR               | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| Dell          | Inspiron 3442               | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Dell          | G5 5587                     | [c88e053304](https://linux-hardware.org/?probe=c88e053304) | Apr 07, 2021 |
| Dell          | Inspiron 3558               | [0ba2e43e56](https://linux-hardware.org/?probe=0ba2e43e56) | Mar 24, 2021 |
| HP            | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Dell          | Inspiron 1420               | [7b12363b97](https://linux-hardware.org/?probe=7b12363b97) | Mar 04, 2021 |
| Dell          | Inspiron 7375               | [eea996c7d4](https://linux-hardware.org/?probe=eea996c7d4) | Feb 26, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Dell          | Vostro 3480                 | [2162db2610](https://linux-hardware.org/?probe=2162db2610) | Feb 03, 2021 |
| Sony          | VPCCW1S1E                   | [f57d56b50e](https://linux-hardware.org/?probe=f57d56b50e) | Jan 31, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [f4e1001265](https://linux-hardware.org/?probe=f4e1001265) | Jan 23, 2021 |
| HP            | Laptop 14-cf3xxx            | [063b008ad5](https://linux-hardware.org/?probe=063b008ad5) | Jan 15, 2021 |
| HP            | Laptop 14-cf3xxx            | [473e0472d5](https://linux-hardware.org/?probe=473e0472d5) | Jan 12, 2021 |
| HP            | EliteBook 2730p             | [5a7277af8b](https://linux-hardware.org/?probe=5a7277af8b) | Jan 08, 2021 |
| HP            | EliteBook 2730p             | [bbbf68f88b](https://linux-hardware.org/?probe=bbbf68f88b) | Jan 08, 2021 |
| Google        | Parrot                      | [a3a6c2f819](https://linux-hardware.org/?probe=a3a6c2f819) | Jan 04, 2021 |
| Google        | Parrot                      | [55b807260c](https://linux-hardware.org/?probe=55b807260c) | Jan 04, 2021 |
| HP            | Pavilion 14                 | [91b047b61a](https://linux-hardware.org/?probe=91b047b61a) | Dec 31, 2020 |
| Gateway       | NE56R                       | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| HP            | Laptop 14-cf3xxx            | [3f61162824](https://linux-hardware.org/?probe=3f61162824) | Dec 07, 2020 |
| Dell          | Inspiron 1420               | [e5dab19c0f](https://linux-hardware.org/?probe=e5dab19c0f) | Dec 05, 2020 |
| HP            | ProBook 4440s               | [b4747f87a1](https://linux-hardware.org/?probe=b4747f87a1) | Nov 24, 2020 |
| Dell          | Inspiron 1750               | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| Dell          | Latitude D430               | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Fujitsu       | LIFEBOOK E752               | [364a814fd0](https://linux-hardware.org/?probe=364a814fd0) | Nov 19, 2020 |
| Fujitsu       | LIFEBOOK E752               | [b0fbbd8176](https://linux-hardware.org/?probe=b0fbbd8176) | Nov 19, 2020 |
| HP            | 3115m                       | [1ae9651614](https://linux-hardware.org/?probe=1ae9651614) | Nov 17, 2020 |
| Gateway       | NE56R                       | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| ASUSTek       | X510UAR                     | [106453a877](https://linux-hardware.org/?probe=106453a877) | Oct 23, 2020 |
| ASUSTek       | X510UAR                     | [fea6f132fa](https://linux-hardware.org/?probe=fea6f132fa) | Oct 23, 2020 |
| Toshiba       | PORTEGE M805                | [cacfe4abd9](https://linux-hardware.org/?probe=cacfe4abd9) | Oct 22, 2020 |
| Toshiba       | Satellite C55-B             | [146545f430](https://linux-hardware.org/?probe=146545f430) | Oct 17, 2020 |
| Toshiba       | Satellite C55-B             | [61e809ea3a](https://linux-hardware.org/?probe=61e809ea3a) | Oct 12, 2020 |
| Toshiba       | Satellite C55-B             | [6353946b7e](https://linux-hardware.org/?probe=6353946b7e) | Oct 12, 2020 |
| Dell          | Inspiron 1420               | [03631f1005](https://linux-hardware.org/?probe=03631f1005) | Oct 08, 2020 |
| Dell          | Inspiron 1420               | [78e7085775](https://linux-hardware.org/?probe=78e7085775) | Oct 08, 2020 |
| Sony          | VGN-CR120E                  | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Sony          | VGN-CR120E                  | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| Toshiba       | Satellite C45-A             | [2774da64f6](https://linux-hardware.org/?probe=2774da64f6) | Sep 18, 2020 |
| HP            | Pavilion 15                 | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP            | Mini 210-1100               | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP            | Pavilion 15                 | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| HP            | Laptop 14-cf3xxx            | [489cee4d9a](https://linux-hardware.org/?probe=489cee4d9a) | Sep 12, 2020 |
| Toshiba       | Satellite P775              | [d71ccb1065](https://linux-hardware.org/?probe=d71ccb1065) | Sep 10, 2020 |
| HP            | Pavilion dv2500             | [8626b52852](https://linux-hardware.org/?probe=8626b52852) | Sep 08, 2020 |
| Samsung       | 530U4E/540U4E               | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | [c3f5f6d566](https://linux-hardware.org/?probe=c3f5f6d566) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | [4e0f1689a3](https://linux-hardware.org/?probe=4e0f1689a3) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | [8eb7cfa128](https://linux-hardware.org/?probe=8eb7cfa128) | Sep 05, 2020 |
| HP            | Laptop 14-df0xxx            | [1b11abd994](https://linux-hardware.org/?probe=1b11abd994) | Sep 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [21f0c0015c](https://linux-hardware.org/?probe=21f0c0015c) | Aug 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [29f01daf9e](https://linux-hardware.org/?probe=29f01daf9e) | Aug 26, 2020 |
| Dell          | Inspiron N4050              | [e39ccc961c](https://linux-hardware.org/?probe=e39ccc961c) | Aug 20, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [dd8aa75b79](https://linux-hardware.org/?probe=dd8aa75b79) | Aug 16, 2020 |
| ASUSTek       | X502CA                      | [7876d4c48d](https://linux-hardware.org/?probe=7876d4c48d) | Aug 14, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [9bcbc98b0f](https://linux-hardware.org/?probe=9bcbc98b0f) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [c32745014a](https://linux-hardware.org/?probe=c32745014a) | Jul 22, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [a70d38c48c](https://linux-hardware.org/?probe=a70d38c48c) | Jul 20, 2020 |
| Acer          | AO722                       | [90943ce018](https://linux-hardware.org/?probe=90943ce018) | Jul 10, 2020 |
| Dell          | Inspiron 7375               | [e4318a8dea](https://linux-hardware.org/?probe=e4318a8dea) | Jul 04, 2020 |
| Dell          | Inspiron 7375               | [ba6d8528e9](https://linux-hardware.org/?probe=ba6d8528e9) | Jul 04, 2020 |
| HP            | Notebook                    | [b646ab05a7](https://linux-hardware.org/?probe=b646ab05a7) | Jun 30, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [b8b588701d](https://linux-hardware.org/?probe=b8b588701d) | Jun 22, 2020 |
| Lenovo        | 3000 V200 076433G           | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| HP            | ProBook 4440s               | [5442b989be](https://linux-hardware.org/?probe=5442b989be) | May 30, 2020 |
| Dell          | Inspiron 5570               | [84339f57da](https://linux-hardware.org/?probe=84339f57da) | May 09, 2020 |
| Apple         | MacBookPro13,3              | [81946cb76f](https://linux-hardware.org/?probe=81946cb76f) | Apr 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [df8a7bcad8](https://linux-hardware.org/?probe=df8a7bcad8) | Mar 26, 2020 |
| Lenovo        | G710 20252                  | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| HP            | 15                          | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP            | 15                          | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Acer          | AO722                       | [08d71a347b](https://linux-hardware.org/?probe=08d71a347b) | Feb 29, 2020 |
| Acer          | AO722                       | [291cea2763](https://linux-hardware.org/?probe=291cea2763) | Feb 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek       | UX303LA                     | [5ae0871de5](https://linux-hardware.org/?probe=5ae0871de5) | Feb 23, 2020 |
| ASUSTek       | UX303LA                     | [cfc85f91d5](https://linux-hardware.org/?probe=cfc85f91d5) | Feb 22, 2020 |
| ASUSTek       | UX303LA                     | [ab03f678e6](https://linux-hardware.org/?probe=ab03f678e6) | Feb 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d2b7a56172](https://linux-hardware.org/?probe=d2b7a56172) | Jan 14, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [30baa09d89](https://linux-hardware.org/?probe=30baa09d89) | Jan 14, 2020 |
| Acer          | Aspire ES1-131              | [fcb74db0f2](https://linux-hardware.org/?probe=fcb74db0f2) | Jan 14, 2020 |
| HP            | Laptop 14-bs0xx             | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Dell          | System XPS L502X            | [d43cf2a533](https://linux-hardware.org/?probe=d43cf2a533) | Sep 12, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | [a4264e7371](https://linux-hardware.org/?probe=a4264e7371) | Sep 12, 2019 |
| Toshiba       | Satellite E45t-B            | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| Toshiba       | Satellite P55W-C            | [cc12571867](https://linux-hardware.org/?probe=cc12571867) | Jul 27, 2019 |
| HP            | Laptop 15-da0xxx            | [76dbbe880b](https://linux-hardware.org/?probe=76dbbe880b) | Jul 10, 2019 |
| HP            | Pavilion 14                 | [6dde2ab979](https://linux-hardware.org/?probe=6dde2ab979) | Jun 08, 2019 |
| Apple         | MacBook1,1                  | [57ca5e1449](https://linux-hardware.org/?probe=57ca5e1449) | Jun 02, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | [a4d0b9a0cc](https://linux-hardware.org/?probe=a4d0b9a0cc) | May 27, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | [6abf9ea94e](https://linux-hardware.org/?probe=6abf9ea94e) | Apr 17, 2019 |
| HP            | ENVY Notebook               | [4d812e744e](https://linux-hardware.org/?probe=4d812e744e) | Apr 17, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 23        | 7.57%   |
| Ubuntu 22.04                 | 12        | 3.95%   |
| Zorin 17                     | 11        | 3.62%   |
| Ubuntu 18.04                 | 11        | 3.62%   |
| Ubuntu 24.04                 | 10        | 3.29%   |
| Debian 11                    | 9         | 2.96%   |
| Linux Mint 20.3              | 7         | 2.3%    |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.97%   |
| KDE neon 20.04               | 6         | 1.97%   |
| Fedora 38                    | 6         | 1.97%   |
| Pop!_OS 22.04                | 5         | 1.64%   |
| OpenMandriva 4.3             | 5         | 1.64%   |
| Linux Mint 21.1              | 5         | 1.64%   |
| Linux Mint 19.3              | 5         | 1.64%   |
| Debian 12                    | 5         | 1.64%   |
| Zorin 16                     | 4         | 1.32%   |
| Zorin 15                     | 4         | 1.32%   |
| Ubuntu 23.10                 | 4         | 1.32%   |
| OpenMandriva 24.12           | 4         | 1.32%   |
| Fedora 41                    | 4         | 1.32%   |
| Arch Rolling                 | 4         | 1.32%   |
| Zorin 18                     | 3         | 0.99%   |
| Pop!_OS 21.10                | 3         | 0.99%   |
| OpenMandriva 5.0             | 3         | 0.99%   |
| OpenMandriva 25.90           | 3         | 0.99%   |
| OpenMandriva 23.03           | 3         | 0.99%   |
| LMDE 5                       | 3         | 0.99%   |
| LMDE 4                       | 3         | 0.99%   |
| Linux Mint 21.2              | 3         | 0.99%   |
| Garuda Linux Soaring         | 3         | 0.99%   |
| Fedora 40                    | 3         | 0.99%   |
| Fedora 37                    | 3         | 0.99%   |
| Fedora 34                    | 3         | 0.99%   |
| Fedora 33                    | 3         | 0.99%   |
| EndeavourOS Rolling          | 3         | 0.99%   |
| ArcoLinux Rolling            | 3         | 0.99%   |
| Xubuntu 22.10                | 2         | 0.66%   |
| Xubuntu 20.04                | 2         | 0.66%   |
| Ubuntu 22.10                 | 2         | 0.66%   |
| Ubuntu 21.10                 | 2         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 69        | 23.63%  |
| Fedora        | 30        | 10.27%  |
| Linux Mint    | 29        | 9.93%   |
| OpenMandriva  | 25        | 8.56%   |
| Zorin         | 22        | 7.53%   |
| Debian        | 17        | 5.82%   |
| Pop!_OS       | 13        | 4.45%   |
| KDE neon      | 8         | 2.74%   |
| openSUSE      | 6         | 2.05%   |
| LMDE          | 6         | 2.05%   |
| Elementary    | 6         | 2.05%   |
| Xubuntu       | 5         | 1.71%   |
| Manjaro       | 5         | 1.71%   |
| Lubuntu       | 5         | 1.71%   |
| Arch          | 5         | 1.71%   |
| Ubuntu MATE   | 3         | 1.03%   |
| Kubuntu       | 3         | 1.03%   |
| Garuda Linux  | 3         | 1.03%   |
| EndeavourOS   | 3         | 1.03%   |
| ArcoLinux     | 3         | 1.03%   |
| Void Linux    | 2         | 0.68%   |
| Ubuntu Budgie | 2         | 0.68%   |
| SteamOS       | 2         | 0.68%   |
| Kali          | 2         | 0.68%   |
| Endless       | 2         | 0.68%   |
| BlackPanther  | 2         | 0.68%   |
| Bazzite       | 2         | 0.68%   |
| XeroG         | 1         | 0.34%   |
| Xero          | 1         | 0.34%   |
| ROSA          | 1         | 0.34%   |
| RHEL          | 1         | 0.34%   |
| Parrot        | 1         | 0.34%   |
| Nobara        | 1         | 0.34%   |
| MX            | 1         | 0.34%   |
| Linux Lite    | 1         | 0.34%   |
| Deepin        | 1         | 0.34%   |
| CachyOS       | 1         | 0.34%   |
| BuildRoot     | 1         | 0.34%   |
| Anduinos      | 1         | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-54-generic         | 4         | 1.24%   |
| 5.4.0-42-generic         | 4         | 1.24%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.24%   |
| 5.15.0-33-generic        | 4         | 1.24%   |
| 5.13.0-35-generic        | 4         | 1.24%   |
| 6.9.3-76060903-generic   | 3         | 0.93%   |
| 6.8.0-57-generic         | 3         | 0.93%   |
| 6.8.0-31-generic         | 3         | 0.93%   |
| 6.6.2-desktop-1omv2390   | 3         | 0.93%   |
| 6.5.0-41-generic         | 3         | 0.93%   |
| 6.5.0-35-generic         | 3         | 0.93%   |
| 6.14.0-36-generic        | 3         | 0.93%   |
| 6.12.1-desktop-1omv2490  | 3         | 0.93%   |
| 5.4.0-58-generic         | 3         | 0.93%   |
| 5.4.0-56-generic         | 3         | 0.93%   |
| 5.4.0-48-generic         | 3         | 0.93%   |
| 5.4.0-45-generic         | 3         | 0.93%   |
| 5.4.0-26-generic         | 3         | 0.93%   |
| 5.16.11-76051611-generic | 3         | 0.93%   |
| 5.15.0-56-generic        | 3         | 0.93%   |
| 6.8.0-60-generic         | 2         | 0.62%   |
| 6.8.0-59-generic         | 2         | 0.62%   |
| 6.8.0-47-generic         | 2         | 0.62%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.62%   |
| 6.14.2-desktop-3omv2590  | 2         | 0.62%   |
| 6.12.9-desktop-1omv2490  | 2         | 0.62%   |
| 6.11.0-26-generic        | 2         | 0.62%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.62%   |
| 6.1.0-13-amd64           | 2         | 0.62%   |
| 5.8.0-43-generic         | 2         | 0.62%   |
| 5.8.0-41-generic         | 2         | 0.62%   |
| 5.8.0-14-generic         | 2         | 0.62%   |
| 5.4.0-77-generic         | 2         | 0.62%   |
| 5.4.0-7634-generic       | 2         | 0.62%   |
| 5.4.0-110-generic        | 2         | 0.62%   |
| 5.3.0-62-generic         | 2         | 0.62%   |
| 5.15.59-xanmod1          | 2         | 0.62%   |
| 5.15.0-58-generic        | 2         | 0.62%   |
| 5.15.0-27-generic        | 2         | 0.62%   |
| 5.13.0-7614-generic      | 2         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 42        | 13.5%   |
| 5.15.0  | 23        | 7.4%    |
| 6.5.0   | 17        | 5.47%   |
| 6.8.0   | 15        | 4.82%   |
| 5.13.0  | 15        | 4.82%   |
| 6.14.0  | 9         | 2.89%   |
| 6.1.0   | 8         | 2.57%   |
| 4.15.0  | 8         | 2.57%   |
| 5.8.0   | 7         | 2.25%   |
| 5.10.0  | 7         | 2.25%   |
| 5.0.0   | 7         | 2.25%   |
| 6.11.0  | 5         | 1.61%   |
| 5.11.0  | 5         | 1.61%   |
| 6.2.0   | 4         | 1.29%   |
| 6.14.2  | 4         | 1.29%   |
| 5.3.0   | 4         | 1.29%   |
| 5.19.0  | 4         | 1.29%   |
| 5.16.7  | 4         | 1.29%   |
| 6.9.3   | 3         | 0.96%   |
| 6.6.2   | 3         | 0.96%   |
| 6.12.9  | 3         | 0.96%   |
| 6.12.1  | 3         | 0.96%   |
| 5.16.11 | 3         | 0.96%   |
| 6.8.5   | 2         | 0.64%   |
| 6.7.5   | 2         | 0.64%   |
| 6.5.9   | 2         | 0.64%   |
| 6.4.3   | 2         | 0.64%   |
| 6.4.10  | 2         | 0.64%   |
| 6.3.5   | 2         | 0.64%   |
| 6.2.6   | 2         | 0.64%   |
| 6.2.2   | 2         | 0.64%   |
| 6.17.0  | 2         | 0.64%   |
| 6.12.48 | 2         | 0.64%   |
| 6.11.10 | 2         | 0.64%   |
| 6.1.1   | 2         | 0.64%   |
| 5.17.5  | 2         | 0.64%   |
| 5.15.59 | 2         | 0.64%   |
| 4.18.16 | 2         | 0.64%   |
| 4.18.0  | 2         | 0.64%   |
| 6.7.9   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 14.75%  |
| 5.15    | 27        | 8.85%   |
| 6.5     | 22        | 7.21%   |
| 6.8     | 17        | 5.57%   |
| 6.14    | 15        | 4.92%   |
| 5.13    | 15        | 4.92%   |
| 6.1     | 12        | 3.93%   |
| 5.10    | 12        | 3.93%   |
| 6.2     | 11        | 3.61%   |
| 6.12    | 11        | 3.61%   |
| 5.16    | 10        | 3.28%   |
| 6.11    | 9         | 2.95%   |
| 5.8     | 8         | 2.62%   |
| 4.15    | 8         | 2.62%   |
| 6.4     | 7         | 2.3%    |
| 5.11    | 7         | 2.3%    |
| 5.0     | 7         | 2.3%    |
| 6.17    | 6         | 1.97%   |
| 5.19    | 6         | 1.97%   |
| 5.3     | 5         | 1.64%   |
| 6.10    | 4         | 1.31%   |
| 4.18    | 4         | 1.31%   |
| 6.9     | 3         | 0.98%   |
| 6.7     | 3         | 0.98%   |
| 6.6     | 3         | 0.98%   |
| 6.16    | 3         | 0.98%   |
| 6.13    | 3         | 0.98%   |
| 6.0     | 3         | 0.98%   |
| 5.18    | 3         | 0.98%   |
| 5.14    | 3         | 0.98%   |
| 6.3     | 2         | 0.66%   |
| 5.7     | 2         | 0.66%   |
| 5.5     | 2         | 0.66%   |
| 5.17    | 2         | 0.66%   |
| 5.12    | 2         | 0.66%   |
| 5.9     | 1         | 0.33%   |
| 4.9     | 1         | 0.33%   |
| 4.19    | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 261       | 96.31%  |
| i686   | 10        | 3.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 127       | 44.1%   |
| KDE5       | 39        | 13.54%  |
| X-Cinnamon | 27        | 9.38%   |
| Unknown    | 22        | 7.64%   |
| XFCE       | 21        | 7.29%   |
| KDE6       | 15        | 5.21%   |
| MATE       | 8         | 2.78%   |
| Pantheon   | 6         | 2.08%   |
| LXQt       | 5         | 1.74%   |
| KDE        | 5         | 1.74%   |
| LXDE       | 4         | 1.39%   |
| Budgie     | 2         | 0.69%   |
| qtile      | 1         | 0.35%   |
| jwm        | 1         | 0.35%   |
| ICEWM      | 1         | 0.35%   |
| Deepin     | 1         | 0.35%   |
| Cutefish   | 1         | 0.35%   |
| COSMIC     | 1         | 0.35%   |
| Cinnamon   | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 192       | 67.37%  |
| Wayland | 79        | 27.72%  |
| Unknown | 13        | 4.56%   |
| Tty     | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 141       | 48.29%  |
| SDDM    | 49        | 16.78%  |
| GDM3    | 41        | 14.04%  |
| LightDM | 30        | 10.27%  |
| GDM     | 28        | 9.59%   |
| TDM     | 3         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_EC   | 127       | 45.2%   |
| en_US   | 70        | 24.91%  |
| es_ES   | 34        | 12.1%   |
| Unknown | 15        | 5.34%   |
| es_MX   | 11        | 3.91%   |
| es_CO   | 6         | 2.14%   |
| de_DE   | 4         | 1.42%   |
| es_US   | 3         | 1.07%   |
| C       | 3         | 1.07%   |
| es_PE   | 2         | 0.71%   |
| es_AR   | 2         | 0.71%   |
| ru_RU   | 1         | 0.36%   |
| fr_FR   | 1         | 0.36%   |
| es_CU   | 1         | 0.36%   |
| en_GB   | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 151       | 53.17%  |
| BIOS | 133       | 46.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 193       | 68.2%   |
| Btrfs   | 42        | 14.84%  |
| Overlay | 24        | 8.48%   |
| Tmpfs   | 15        | 5.3%    |
| Xfs     | 4         | 1.41%   |
| Zfs     | 3         | 1.06%   |
| Ext2    | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 139       | 49.47%  |
| GPT     | 126       | 44.84%  |
| MBR     | 16        | 5.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 234       | 84.48%  |
| Yes       | 43        | 15.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 194       | 69.53%  |
| Yes       | 85        | 30.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 61        | 22.51%  |
| Lenovo              | 44        | 16.24%  |
| Dell                | 44        | 16.24%  |
| ASUSTek Computer    | 31        | 11.44%  |
| Toshiba             | 16        | 5.9%    |
| Acer                | 14        | 5.17%   |
| Apple               | 12        | 4.43%   |
| Google              | 9         | 3.32%   |
| Sony                | 7         | 2.58%   |
| Unknown             | 6         | 2.21%   |
| MSI                 | 5         | 1.85%   |
| Samsung Electronics | 4         | 1.48%   |
| Gateway             | 3         | 1.11%   |
| Valve               | 2         | 0.74%   |
| Razer               | 2         | 0.74%   |
| Alienware           | 2         | 0.74%   |
| Timi                | 1         | 0.37%   |
| System76            | 1         | 0.37%   |
| Notebook            | 1         | 0.37%   |
| HUAWEI              | 1         | 0.37%   |
| GPU Company         | 1         | 0.37%   |
| Fujitsu             | 1         | 0.37%   |
| Dynabook            | 1         | 0.37%   |
| Compal              | 1         | 0.37%   |
| Chuwi               | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 2.95%   |
| HP Notebook                              | 5         | 1.85%   |
| HP Pavilion g4                           | 4         | 1.48%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 4         | 1.48%   |
| HP ProBook 4440s                         | 3         | 1.11%   |
| HP Pavilion Laptop 15-cw1xxx             | 3         | 1.11%   |
| ASUS E202SA                              | 3         | 1.11%   |
| Apple MacBookPro9,2                      | 3         | 1.11%   |
| Apple MacBookPro12,1                     | 3         | 1.11%   |
| Valve Jupiter                            | 2         | 0.74%   |
| Toshiba Satellite S55-B                  | 2         | 0.74%   |
| Toshiba Satellite C55-B                  | 2         | 0.74%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 2         | 0.74%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 0.74%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 2         | 0.74%   |
| HP Pavilion Laptop 15-cw0xxx             | 2         | 0.74%   |
| HP Pavilion 14                           | 2         | 0.74%   |
| HP Laptop 15-da0xxx                      | 2         | 0.74%   |
| HP 1000                                  | 2         | 0.74%   |
| Dell Vostro 3480                         | 2         | 0.74%   |
| Dell Latitude E6420                      | 2         | 0.74%   |
| Dell Inspiron N4050                      | 2         | 0.74%   |
| Dell Inspiron 5570                       | 2         | 0.74%   |
| Dell Inspiron 3442                       | 2         | 0.74%   |
| Dell Inspiron 15 7000 Gaming             | 2         | 0.74%   |
| Dell Inspiron 1420                       | 2         | 0.74%   |
| Dell Inspiron 14-3467                    | 2         | 0.74%   |
| Dell G5 5587                             | 2         | 0.74%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 2         | 0.74%   |
| Toshiba Satellite S55-A                  | 1         | 0.37%   |
| Toshiba Satellite P855                   | 1         | 0.37%   |
| Toshiba Satellite P775                   | 1         | 0.37%   |
| Toshiba Satellite P55W-C                 | 1         | 0.37%   |
| Toshiba Satellite L50-B                  | 1         | 0.37%   |
| Toshiba Satellite L45-B                  | 1         | 0.37%   |
| Toshiba Satellite E45t-B                 | 1         | 0.37%   |
| Toshiba Satellite C55D-A                 | 1         | 0.37%   |
| Toshiba Satellite C45-A                  | 1         | 0.37%   |
| Toshiba Satellite A205                   | 1         | 0.37%   |
| Toshiba Satellite A135                   | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 26        | 9.59%   |
| Lenovo IdeaPad     | 21        | 7.75%   |
| HP Pavilion        | 17        | 6.27%   |
| Toshiba Satellite  | 15        | 5.54%   |
| ASUS VivoBook      | 14        | 5.17%   |
| Lenovo ThinkPad    | 12        | 4.43%   |
| HP Laptop          | 10        | 3.69%   |
| Dell Latitude      | 9         | 3.32%   |
| Acer Aspire        | 8         | 2.95%   |
| Unknown            | 8         | 2.95%   |
| HP ProBook         | 6         | 2.21%   |
| HP Notebook        | 5         | 1.85%   |
| HP ENVY            | 3         | 1.11%   |
| Dell Vostro        | 3         | 1.11%   |
| ASUS E202SA        | 3         | 1.11%   |
| Apple MacBookPro9  | 3         | 1.11%   |
| Apple MacBookPro12 | 3         | 1.11%   |
| Valve Jupiter      | 2         | 0.74%   |
| Razer Blade        | 2         | 0.74%   |
| MSI Stealth        | 2         | 0.74%   |
| Lenovo ThinkBook   | 2         | 0.74%   |
| HP OMEN            | 2         | 0.74%   |
| HP EliteBook       | 2         | 0.74%   |
| HP Compaq          | 2         | 0.74%   |
| HP 245             | 2         | 0.74%   |
| HP 15              | 2         | 0.74%   |
| HP 1000            | 2         | 0.74%   |
| Dell G5            | 2         | 0.74%   |
| ASUS ASUS          | 2         | 0.74%   |
| Acer TravelMate    | 2         | 0.74%   |
| Toshiba PORTEGE    | 1         | 0.37%   |
| Timi RedmiBook     | 1         | 0.37%   |
| System76 Pangolin  | 1         | 0.37%   |
| Sony VPCEG30EL     | 1         | 0.37%   |
| Sony VPCEG25FL     | 1         | 0.37%   |
| Sony VPCEG23EL     | 1         | 0.37%   |
| Sony VPCCW1S1E     | 1         | 0.37%   |
| Sony VGN-CR120E    | 1         | 0.37%   |
| Sony SVE14A25CLB   | 1         | 0.37%   |
| Sony SVE14113ELW   | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 28        | 10.33%  |
| 2018 | 27        | 9.96%   |
| 2019 | 24        | 8.86%   |
| 2020 | 23        | 8.49%   |
| 2017 | 22        | 8.12%   |
| 2021 | 20        | 7.38%   |
| 2014 | 16        | 5.9%    |
| 2013 | 16        | 5.9%    |
| 2011 | 16        | 5.9%    |
| 2015 | 15        | 5.54%   |
| 2016 | 11        | 4.06%   |
| 2022 | 10        | 3.69%   |
| 2007 | 9         | 3.32%   |
| 2023 | 7         | 2.58%   |
| 2010 | 7         | 2.58%   |
| 2024 | 5         | 1.85%   |
| 2009 | 5         | 1.85%   |
| 2008 | 4         | 1.48%   |
| 2006 | 3         | 1.11%   |
| 2025 | 2         | 0.74%   |
| 2005 | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 271       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 252       | 92.31%  |
| Enabled  | 21        | 7.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 262       | 96.68%  |
| Yes  | 9         | 3.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 83        | 29.86%  |
| 8.01-16.0   | 52        | 18.71%  |
| 3.01-4.0    | 51        | 18.35%  |
| 16.01-24.0  | 44        | 15.83%  |
| 32.01-64.0  | 23        | 8.27%   |
| 1.01-2.0    | 15        | 5.4%    |
| 2.01-3.0    | 5         | 1.8%    |
| 24.01-32.0  | 2         | 0.72%   |
| 64.01-256.0 | 2         | 0.72%   |
| 0.51-1.0    | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 83        | 27.85%  |
| 1.01-2.0   | 83        | 27.85%  |
| 4.01-8.0   | 55        | 18.46%  |
| 3.01-4.0   | 49        | 16.44%  |
| 8.01-16.0  | 16        | 5.37%   |
| 0.51-1.0   | 7         | 2.35%   |
| 0.01-0.5   | 3         | 1.01%   |
| 24.01-32.0 | 1         | 0.34%   |
| 16.01-24.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 197       | 71.12%  |
| 2      | 75        | 27.08%  |
| 3      | 4         | 1.44%   |
| 0      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 191       | 70.22%  |
| Yes       | 81        | 29.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 77.12%  |
| No        | 62        | 22.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 99.26%  |
| No        | 2         | 0.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 82.42%  |
| No        | 48        | 17.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ecuador | 271       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 117       | 41.64%  |
| Guayaquil                      | 72        | 25.62%  |
| Cuenca                         | 27        | 9.61%   |
| Loja                           | 11        | 3.91%   |
| Manta                          | 6         | 2.14%   |
| Ambato                         | 6         | 2.14%   |
| Portoviejo                     | 5         | 1.78%   |
| Machala                        | 4         | 1.42%   |
| Puyo                           | 3         | 1.07%   |
| Hacienda Ibarra                | 3         | 1.07%   |
| Sucúa                         | 2         | 0.71%   |
| Santo Domingo de los Colorados | 2         | 0.71%   |
| Riobamba                       | 2         | 0.71%   |
| Ayacucho                       | 2         | 0.71%   |
| Uyumbicho                      | 1         | 0.36%   |
| Samborondon                    | 1         | 0.36%   |
| Salinas                        | 1         | 0.36%   |
| Provincia del Chimborazo       | 1         | 0.36%   |
| Otavalo                        | 1         | 0.36%   |
| Nueva Loja                     | 1         | 0.36%   |
| Montecristi                    | 1         | 0.36%   |
| Latacunga                      | 1         | 0.36%   |
| La Troncal                     | 1         | 0.36%   |
| La Providencia                 | 1         | 0.36%   |
| La Mana                        | 1         | 0.36%   |
| La Concordia Numero Uno        | 1         | 0.36%   |
| Ibarra                         | 1         | 0.36%   |
| Huaquillas                     | 1         | 0.36%   |
| Hacienda San Sebastian         | 1         | 0.36%   |
| Guamani                        | 1         | 0.36%   |
| Febres Cordero                 | 1         | 0.36%   |
| Cayambe                        | 1         | 0.36%   |
| Babahoyo                       | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 57        | 71     | 16.67%  |
| Toshiba                     | 45        | 51     | 13.16%  |
| Seagate                     | 34        | 51     | 9.94%   |
| Kingston                    | 27        | 32     | 7.89%   |
| Samsung Electronics         | 24        | 28     | 7.02%   |
| Unknown                     | 14        | 21     | 4.09%   |
| A-DATA Technology           | 14        | 18     | 4.09%   |
| Hitachi                     | 13        | 16     | 3.8%    |
| SK hynix                    | 12        | 14     | 3.51%   |
| SanDisk                     | 12        | 19     | 3.51%   |
| Micron Technology           | 8         | 9      | 2.34%   |
| HGST                        | 8         | 11     | 2.34%   |
| JMicron Technology          | 7         | 7      | 2.05%   |
| Apple                       | 7         | 10     | 2.05%   |
| Intel                       | 6         | 10     | 1.75%   |
| Hewlett-Packard             | 6         | 7      | 1.75%   |
| Kingston Technology Company | 5         | 6      | 1.46%   |
| Crucial                     | 5         | 6      | 1.46%   |
| KIOXIA                      | 4         | 4      | 1.17%   |
| Gigabyte Technology         | 3         | 3      | 0.88%   |
| Phison Electronics          | 2         | 2      | 0.58%   |
| Phison                      | 2         | 2      | 0.58%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.58%   |
| Fujitsu                     | 2         | 2      | 0.58%   |
| USB3.0                      | 1         | 1      | 0.29%   |
| Union Memory                | 1         | 1      | 0.29%   |
| UMIS                        | 1         | 1      | 0.29%   |
| Team                        | 1         | 1      | 0.29%   |
| SOLIDIGM                    | 1         | 1      | 0.29%   |
| SABRENT                     | 1         | 1      | 0.29%   |
| Realtek Semiconductor       | 1         | 1      | 0.29%   |
| PNY                         | 1         | 1      | 0.29%   |
| Patriot                     | 1         | 1      | 0.29%   |
| OWC                         | 1         | 1      | 0.29%   |
| Netac                       | 1         | 1      | 0.29%   |
| Micron/Crucial Technology   | 1         | 1      | 0.29%   |
| LITEON                      | 1         | 1      | 0.29%   |
| Lite-On                     | 1         | 1      | 0.29%   |
| LaCie                       | 1         | 1      | 0.29%   |
| KingSpec                    | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 10        | 2.82%   |
| Toshiba MQ04ABF100 1TB                            | 7         | 1.97%   |
| Toshiba MQ01ABF050 500GB                          | 7         | 1.97%   |
| Kingston SA400S37240G 240GB SSD                   | 7         | 1.97%   |
| Kingston SA400S37960G 960GB SSD                   | 5         | 1.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 4         | 1.13%   |
| WDC WD10SPZX-24Z10 1TB                            | 4         | 1.13%   |
| Unknown MMC Card  32GB                            | 4         | 1.13%   |
| Unknown MMC Card  16GB                            | 4         | 1.13%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.13%   |
| Seagate ST2000LM007-1R8174 2TB                    | 4         | 1.13%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 4         | 1.13%   |
| Kingston SA400S37480G 480GB SSD                   | 4         | 1.13%   |
| JMicron Tech 250GB                                | 4         | 1.13%   |
| WDC WD6400BEVT-22A0RT0 640GB                      | 3         | 0.85%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 3         | 0.85%   |
| Toshiba MQ01ABD075 752GB                          | 3         | 0.85%   |
| SanDisk NVMe SSD Drive 1TB                        | 3         | 0.85%   |
| Micron 3400_MTFDKBA1T0TFH 1024GB                  | 3         | 0.85%   |
| JMicron Generic 320GB                             | 3         | 0.85%   |
| Hitachi HTS547550A9E384 500GB                     | 3         | 0.85%   |
| HP SSD S700 500GB                                 | 3         | 0.85%   |
| Gigabyte GP-GSTFS31480GNTD 480GB                  | 3         | 0.85%   |
| A-DATA SU650 120GB SSD                            | 3         | 0.85%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                  | 2         | 0.56%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.56%   |
| WDC WD1600BEVT-22ZCT0 160GB                       | 2         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 2         | 0.56%   |
| WDC WD10SPZX-22Z10T1 1TB                          | 2         | 0.56%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 2         | 0.56%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.56%   |
| Unknown SD/MMC/MS PRO 2GB                         | 2         | 0.56%   |
| Unknown MMC Card  64GB                            | 2         | 0.56%   |
| Toshiba MQ01ABD100M 1TB                           | 2         | 0.56%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD           | 2         | 0.56%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB            | 2         | 0.56%   |
| Seagate ST9500420AS 500GB                         | 2         | 0.56%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.56%   |
| Seagate ST500LT012-9WS142 500GB                   | 2         | 0.56%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 41        | 46     | 28.87%  |
| WDC                 | 36        | 47     | 25.35%  |
| Seagate             | 34        | 51     | 23.94%  |
| Hitachi             | 13        | 16     | 9.15%   |
| HGST                | 8         | 11     | 5.63%   |
| JMicron Technology  | 3         | 3      | 2.11%   |
| Unknown             | 2         | 4      | 1.41%   |
| Fujitsu             | 2         | 2      | 1.41%   |
| USB3.0              | 1         | 1      | 0.7%    |
| Samsung Electronics | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 20        | 21     | 21.74%  |
| WDC                 | 16        | 18     | 17.39%  |
| A-DATA Technology   | 12        | 16     | 13.04%  |
| Samsung Electronics | 6         | 7      | 6.52%   |
| SanDisk             | 5         | 5      | 5.43%   |
| Hewlett-Packard     | 5         | 6      | 5.43%   |
| Apple               | 5         | 8      | 5.43%   |
| Crucial             | 4         | 4      | 4.35%   |
| Gigabyte Technology | 3         | 3      | 3.26%   |
| Toshiba             | 2         | 3      | 2.17%   |
| SK hynix            | 2         | 2      | 2.17%   |
| Team                | 1         | 1      | 1.09%   |
| SABRENT             | 1         | 1      | 1.09%   |
| PNY                 | 1         | 1      | 1.09%   |
| Patriot             | 1         | 1      | 1.09%   |
| OWC                 | 1         | 1      | 1.09%   |
| Netac               | 1         | 1      | 1.09%   |
| Micron Technology   | 1         | 1      | 1.09%   |
| LITEON              | 1         | 1      | 1.09%   |
| KingSpec            | 1         | 1      | 1.09%   |
| KINGPAN             | 1         | 1      | 1.09%   |
| HS-SSD-E100N        | 1         | 1      | 1.09%   |
| Golden              | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 138       | 183    | 42.2%   |
| NVMe    | 86        | 112    | 26.3%   |
| SSD     | 83        | 105    | 25.38%  |
| MMC     | 13        | 18     | 3.98%   |
| Unknown | 7         | 7      | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 198       | 271    | 63.06%  |
| NVMe | 86        | 112    | 27.39%  |
| SAS  | 17        | 24     | 5.41%   |
| MMC  | 13        | 18     | 4.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 130       | 161    | 58.04%  |
| 0.51-1.0   | 84        | 117    | 37.5%   |
| 1.01-2.0   | 9         | 9      | 4.02%   |
| 3.01-4.0   | 1         | 1      | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 74        | 25.61%  |
| 101-250        | 68        | 23.53%  |
| 501-1000       | 42        | 14.53%  |
| 1001-2000      | 34        | 11.76%  |
| 1-20           | 19        | 6.57%   |
| 51-100         | 18        | 6.23%   |
| 21-50          | 16        | 5.54%   |
| Unknown        | 9         | 3.11%   |
| More than 3000 | 8         | 2.77%   |
| 2001-3000      | 1         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 101       | 34.01%  |
| 21-50     | 59        | 19.87%  |
| 101-250   | 45        | 15.15%  |
| 51-100    | 31        | 10.44%  |
| 251-500   | 27        | 9.09%   |
| 501-1000  | 16        | 5.39%   |
| Unknown   | 9         | 3.03%   |
| 1001-2000 | 5         | 1.68%   |
| 2001-3000 | 3         | 1.01%   |
| 0         | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB            | 3         | 3      | 12%     |
| Hitachi HTS547550A9E384 500GB           | 3         | 3      | 12%     |
| Toshiba MQ01ABF050 500GB                | 2         | 4      | 8%      |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 8%      |
| WDC WD5000LPVT-00G33T0 500GB            | 1         | 1      | 4%      |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 2      | 4%      |
| WDC WD10SPCX-22HWST0 1TB                | 1         | 2      | 4%      |
| Toshiba MQ01ABD100M 1TB                 | 1         | 1      | 4%      |
| Toshiba MQ01ABD075 752GB                | 1         | 1      | 4%      |
| Toshiba MK3265GSXN 320GB                | 1         | 1      | 4%      |
| Toshiba MK3259GSXP 320GB                | 1         | 1      | 4%      |
| Toshiba MK2561GSYN 250GB                | 1         | 2      | 4%      |
| Seagate ST9750420AS 752GB               | 1         | 1      | 4%      |
| Seagate ST1000LX015-1U7172 1TB          | 1         | 3      | 4%      |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1      | 4%      |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 4%      |
| Hitachi HTS543232L9SA00 320GB           | 1         | 1      | 4%      |
| HGST HTS545050A7E380 500GB              | 1         | 1      | 4%      |
| Fujitsu MHY2250BH 250GB                 | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 9         | 12     | 36%     |
| WDC      | 6         | 8      | 24%     |
| Hitachi  | 4         | 4      | 16%     |
| Seagate  | 3         | 5      | 12%     |
| Kingston | 1         | 1      | 4%      |
| HGST     | 1         | 1      | 4%      |
| Fujitsu  | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 9         | 12     | 37.5%   |
| WDC     | 6         | 8      | 25%     |
| Hitachi | 4         | 4      | 16.67%  |
| Seagate | 3         | 5      | 12.5%   |
| HGST    | 1         | 1      | 4.17%   |
| Fujitsu | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 31     | 96%     |
| SSD  | 1         | 1      | 4%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK6476GSX 640GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 168       | 258    | 57.73%  |
| Works    | 97        | 134    | 33.33%  |
| Malfunc  | 25        | 32     | 8.59%   |
| Failed   | 1         | 1      | 0.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 184       | 57.14%  |
| AMD                          | 48        | 14.91%  |
| Samsung Electronics          | 22        | 6.83%   |
| SanDisk                      | 13        | 4.04%   |
| Kingston Technology Company  | 12        | 3.73%   |
| SK hynix                     | 10        | 3.11%   |
| Micron Technology            | 7         | 2.17%   |
| Phison Electronics           | 4         | 1.24%   |
| KIOXIA                       | 4         | 1.24%   |
| ADATA Technology             | 3         | 0.93%   |
| Union Memory (Shenzhen)      | 2         | 0.62%   |
| Toshiba America Info Systems | 2         | 0.62%   |
| Micron/Crucial Technology    | 2         | 0.62%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.62%   |
| Solidigm                     | 1         | 0.31%   |
| Silicon Motion               | 1         | 0.31%   |
| Realtek Semiconductor        | 1         | 0.31%   |
| Nvidia                       | 1         | 0.31%   |
| Marvell Technology Group     | 1         | 0.31%   |
| Lite-On Technology           | 1         | 0.31%   |
| Apple                        | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 46        | 13.53%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 23        | 6.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 6.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 5.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 3.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 3.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 2.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 7         | 2.06%   |
| Intel RST Volume Management Device Controller                                    | 7         | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.06%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 1.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.76%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 5         | 1.47%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.47%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                             | 4         | 1.18%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 1.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.88%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 3         | 0.88%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 3         | 0.88%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 0.88%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 3         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 0.88%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.59%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 2         | 0.59%   |
| Phison PS5021-E21 PCIe4 NVMe Controller (DRAM-less)                              | 2         | 0.59%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 2         | 0.59%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.59%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                       | 2         | 0.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 192       | 58.18%  |
| NVMe | 86        | 26.06%  |
| RAID | 35        | 10.61%  |
| IDE  | 17        | 5.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 209       | 77.12%  |
| AMD    | 62        | 22.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.32%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 2.95%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 2.21%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 2.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 2.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.48%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 1.48%   |
| Intel 13th Gen Core i9-13900H                 | 4         | 1.48%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.11%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 1.11%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 1.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.11%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.11%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 3         | 1.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.11%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.11%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.11%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 1.11%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.11%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.11%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.11%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.11%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.11%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 3         | 1.11%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 3         | 1.11%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.74%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.74%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.74%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.74%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.74%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 60        | 22.14%  |
| Intel Core i5           | 49        | 18.08%  |
| Other                   | 32        | 11.81%  |
| Intel Core i3           | 23        | 8.49%   |
| Intel Celeron           | 23        | 8.49%   |
| AMD Ryzen 7             | 16        | 5.9%    |
| AMD Ryzen 5             | 13        | 4.8%    |
| Intel Core 2 Duo        | 12        | 4.43%   |
| AMD Ryzen 3             | 4         | 1.48%   |
| AMD E2                  | 4         | 1.48%   |
| Intel Genuine           | 3         | 1.11%   |
| Intel Atom              | 3         | 1.11%   |
| AMD A6                  | 3         | 1.11%   |
| AMD A12                 | 3         | 1.11%   |
| Intel Pentium Silver    | 2         | 0.74%   |
| Intel Pentium Dual-Core | 2         | 0.74%   |
| Intel Pentium           | 2         | 0.74%   |
| AMD E1                  | 2         | 0.74%   |
| AMD E                   | 2         | 0.74%   |
| AMD A8                  | 2         | 0.74%   |
| AMD A4                  | 2         | 0.74%   |
| Intel Pentium M         | 1         | 0.37%   |
| Intel Core m3           | 1         | 0.37%   |
| Intel Celeron M         | 1         | 0.37%   |
| AMD Ryzen 9             | 1         | 0.37%   |
| AMD Ryzen 7 PRO         | 1         | 0.37%   |
| AMD FX                  | 1         | 0.37%   |
| AMD C-70                | 1         | 0.37%   |
| AMD C-60                | 1         | 0.37%   |
| AMD A10                 | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 144       | 52.94%  |
| 4      | 78        | 28.68%  |
| 8      | 18        | 6.62%   |
| 6      | 12        | 4.41%   |
| 1      | 9         | 3.31%   |
| 14     | 6         | 2.21%   |
| 12     | 2         | 0.74%   |
| 10     | 2         | 0.74%   |
| 24     | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 271       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 200       | 73.53%  |
| 1      | 72        | 26.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 267       | 98.52%  |
| 32-bit         | 3         | 1.11%   |
| Unknown        | 1         | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 45.23%  |
| 0x806ea    | 12        | 4.24%   |
| 0x306a9    | 11        | 3.89%   |
| 0x206a7    | 11        | 3.89%   |
| 0x306d4    | 10        | 3.53%   |
| 0x6fd      | 7         | 2.47%   |
| 0x40651    | 7         | 2.47%   |
| 0x08108109 | 7         | 2.47%   |
| 0x806c1    | 5         | 1.77%   |
| 0x06006705 | 5         | 1.77%   |
| 0x706e5    | 4         | 1.41%   |
| 0x306c3    | 4         | 1.41%   |
| 0x1067a    | 4         | 1.41%   |
| 0x05000119 | 4         | 1.41%   |
| 0x906ea    | 3         | 1.06%   |
| 0x806ec    | 3         | 1.06%   |
| 0x806eb    | 3         | 1.06%   |
| 0x806e9    | 3         | 1.06%   |
| 0x406e3    | 3         | 1.06%   |
| 0x06006704 | 3         | 1.06%   |
| 0x0600611a | 3         | 1.06%   |
| 0x906ed    | 2         | 0.71%   |
| 0x706a1    | 2         | 0.71%   |
| 0x6e8      | 2         | 0.71%   |
| 0x406c4    | 2         | 0.71%   |
| 0x30678    | 2         | 0.71%   |
| 0x20655    | 2         | 0.71%   |
| 0x106ca    | 2         | 0.71%   |
| 0x08608104 | 2         | 0.71%   |
| 0x08600104 | 2         | 0.71%   |
| 0x08108102 | 2         | 0.71%   |
| 0x0810100b | 2         | 0.71%   |
| 0xa0660    | 1         | 0.35%   |
| 0xa0652    | 1         | 0.35%   |
| 0x906a3    | 1         | 0.35%   |
| 0x706a8    | 1         | 0.35%   |
| 0x6fa      | 1         | 0.35%   |
| 0x6d8      | 1         | 0.35%   |
| 0x506e3    | 1         | 0.35%   |
| 0x506c9    | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 44        | 16.18%  |
| Haswell          | 21        | 7.72%   |
| IvyBridge        | 19        | 6.99%   |
| SandyBridge      | 18        | 6.62%   |
| Unknown          | 17        | 6.25%   |
| Excavator        | 14        | 5.15%   |
| Zen+             | 13        | 4.78%   |
| TigerLake        | 13        | 4.78%   |
| Core             | 13        | 4.78%   |
| Broadwell        | 13        | 4.78%   |
| Skylake          | 10        | 3.68%   |
| Silvermont       | 10        | 3.68%   |
| Alderlake Hybrid | 8         | 2.94%   |
| Zen 2            | 7         | 2.57%   |
| Goldmont plus    | 7         | 2.57%   |
| IceLake          | 6         | 2.21%   |
| Bobcat           | 6         | 2.21%   |
| Penryn           | 5         | 1.84%   |
| Zen 3            | 4         | 1.47%   |
| Zen              | 4         | 1.47%   |
| Westmere         | 4         | 1.47%   |
| P6               | 3         | 1.1%    |
| CometLake        | 3         | 1.1%    |
| Bonnell          | 3         | 1.1%    |
| Puma             | 2         | 0.74%   |
| Goldmont         | 2         | 0.74%   |
| Nehalem          | 1         | 0.37%   |
| K10 Llano        | 1         | 0.37%   |
| Jaguar           | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 198       | 61.68%  |
| AMD    | 74        | 23.05%  |
| Nvidia | 49        | 15.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 5.71%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 17        | 5.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 5.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 4.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 4.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.6%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 10        | 3%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.4%    |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 7         | 2.1%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.8%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 6         | 1.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.8%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 6         | 1.8%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 5         | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.5%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 1.5%    |
| AMD Lucienne                                                                             | 5         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.2%    |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 4         | 1.2%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.2%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.9%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.9%    |
| Intel Broadwell-U GT3 [Iris Graphics 6100]                                               | 3         | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.9%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.6%    |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.6%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 152       | 55.88%  |
| 1 x AMD        | 56        | 20.59%  |
| Intel + Nvidia | 32        | 11.76%  |
| 1 x Nvidia     | 11        | 4.04%   |
| Intel + AMD    | 11        | 4.04%   |
| AMD + Nvidia   | 6         | 2.21%   |
| 2 x Intel      | 2         | 0.74%   |
| Other          | 1         | 0.37%   |
| 2 x AMD        | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 240       | 87.91%  |
| Proprietary | 24        | 8.79%   |
| Unknown     | 9         | 3.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 195       | 70.14%  |
| 0.01-0.5   | 34        | 12.23%  |
| 1.01-2.0   | 24        | 8.63%   |
| 3.01-4.0   | 13        | 4.68%   |
| 0.51-1.0   | 7         | 2.52%   |
| 7.01-8.0   | 2         | 0.72%   |
| 5.01-6.0   | 2         | 0.72%   |
| 2.01-3.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 53        | 16.88%  |
| AU Optronics            | 50        | 15.92%  |
| BOE                     | 48        | 15.29%  |
| LG Display              | 41        | 13.06%  |
| Samsung Electronics     | 28        | 8.92%   |
| Goldstar                | 18        | 5.73%   |
| Apple                   | 12        | 3.82%   |
| Chi Mei Optoelectronics | 9         | 2.87%   |
| AOC                     | 7         | 2.23%   |
| PANDA                   | 4         | 1.27%   |
| Lenovo                  | 4         | 1.27%   |
| ASUSTek Computer        | 4         | 1.27%   |
| LG Philips              | 3         | 0.96%   |
| InfoVision              | 3         | 0.96%   |
| Dell                    | 3         | 0.96%   |
| Valve                   | 2         | 0.64%   |
| Sony                    | 2         | 0.64%   |
| Sharp                   | 2         | 0.64%   |
| InnoLux Display         | 2         | 0.64%   |
| Hewlett-Packard         | 2         | 0.64%   |
| Acer                    | 2         | 0.64%   |
| ViewSonic               | 1         | 0.32%   |
| Unknown (XXX)           | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| TCL                     | 1         | 0.32%   |
| SKY                     | 1         | 0.32%   |
| MSI                     | 1         | 0.32%   |
| JDZ                     | 1         | 0.32%   |
| Huion                   | 1         | 0.32%   |
| HKC                     | 1         | 0.32%   |
| HannStar                | 1         | 0.32%   |
| Gigabyte Technology     | 1         | 0.32%   |
| CSOT                    | 1         | 0.32%   |
| CSO                     | 1         | 0.32%   |
| CPT                     | 1         | 0.32%   |
| BenQ                    | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 6         | 1.9%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 5         | 1.59%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch     | 4         | 1.27%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 4         | 1.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.27%   |
| AOC LCD Monitor AOC2070 1600x900 430x240mm 19.4-inch                 | 4         | 1.27%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 3         | 0.95%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 0.95%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 3         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 0.95%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 0.95%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.95%   |
| Apple Color LCD APPA029 2560x1600 286x179mm 13.3-inch                | 3         | 0.95%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 2         | 0.63%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD02B2 1366x768 310x174mm 14.0-inch          | 2         | 0.63%   |
| Lenovo LCD Monitor LEN9051 1920x1080 344x194mm 15.5-inch             | 2         | 0.63%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                  | 2         | 0.63%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 309x173mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x174mm 14.0-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 2         | 0.63%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 2         | 0.63%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO3191 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 133       | 44.19%  |
| 1920x1080 (FHD)    | 95        | 31.56%  |
| 1280x800 (WXGA)    | 15        | 4.98%   |
| 1600x900 (HD+)     | 14        | 4.65%   |
| 1920x1200 (WUXGA)  | 10        | 3.32%   |
| 2560x1600          | 8         | 2.66%   |
| 3840x2160 (4K)     | 5         | 1.66%   |
| 2560x1440 (QHD)    | 4         | 1.33%   |
| 1024x600           | 3         | 1%      |
| 800x1280           | 2         | 0.66%   |
| 1680x1050 (WSXGA+) | 2         | 0.66%   |
| 1440x900 (WXGA+)   | 2         | 0.66%   |
| 1024x768 (XGA)     | 2         | 0.66%   |
| 3840x2400          | 1         | 0.33%   |
| 3440x1440          | 1         | 0.33%   |
| 3200x2000          | 1         | 0.33%   |
| 2880x1800          | 1         | 0.33%   |
| 1360x768           | 1         | 0.33%   |
| 1280x1024 (SXGA)   | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 127       | 40.45%  |
| 13     | 49        | 15.61%  |
| 14     | 43        | 13.69%  |
| 11     | 14        | 4.46%   |
| 18     | 13        | 4.14%   |
| 19     | 10        | 3.18%   |
| 17     | 9         | 2.87%   |
| 16     | 8         | 2.55%   |
| 12     | 8         | 2.55%   |
| 21     | 7         | 2.23%   |
| 27     | 5         | 1.59%   |
| 31     | 4         | 1.27%   |
| 23     | 4         | 1.27%   |
| 10     | 3         | 0.96%   |
| 54     | 2         | 0.64%   |
| 22     | 2         | 0.64%   |
| 7      | 2         | 0.64%   |
| 72     | 1         | 0.32%   |
| 40     | 1         | 0.32%   |
| 34     | 1         | 0.32%   |
| 24     | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 206       | 66.67%  |
| 201-300     | 43        | 13.92%  |
| 401-500     | 28        | 9.06%   |
| 351-400     | 11        | 3.56%   |
| 501-600     | 9         | 2.91%   |
| 601-700     | 5         | 1.62%   |
| 1001-1500   | 2         | 0.65%   |
| 1-100       | 2         | 0.65%   |
| 801-900     | 1         | 0.32%   |
| 701-800     | 1         | 0.32%   |
| 1501-2000   | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 233       | 84.73%  |
| 16/10 | 35        | 12.73%  |
| 4/3   | 2         | 0.73%   |
| 0.67  | 2         | 0.73%   |
| 5/4   | 1         | 0.36%   |
| 3/2   | 1         | 0.36%   |
| 21/9  | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 126       | 40.26%  |
| 81-90          | 82        | 26.2%   |
| 51-60          | 14        | 4.47%   |
| 141-150        | 14        | 4.47%   |
| 151-200        | 12        | 3.83%   |
| 201-250        | 11        | 3.51%   |
| 71-80          | 10        | 3.19%   |
| 61-70          | 8         | 2.56%   |
| 111-120        | 8         | 2.56%   |
| 121-130        | 7         | 2.24%   |
| 351-500        | 5         | 1.6%    |
| 301-350        | 5         | 1.6%    |
| More than 1000 | 3         | 0.96%   |
| 41-50          | 3         | 0.96%   |
| 1-40           | 2         | 0.64%   |
| 131-140        | 1         | 0.32%   |
| 501-1000       | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 130       | 42.48%  |
| 121-160       | 109       | 35.62%  |
| 51-100        | 44        | 14.38%  |
| 161-240       | 17        | 5.56%   |
| 1-50          | 4         | 1.31%   |
| More than 240 | 2         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 224       | 81.16%  |
| 2     | 45        | 16.3%   |
| 0     | 4         | 1.45%   |
| 3     | 3         | 1.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 172       | 39.36%  |
| Intel                           | 97        | 22.2%   |
| Qualcomm Atheros                | 70        | 16.02%  |
| Broadcom                        | 37        | 8.47%   |
| MediaTek                        | 14        | 3.2%    |
| TP-Link                         | 11        | 2.52%   |
| Ralink                          | 6         | 1.37%   |
| Broadcom Limited                | 6         | 1.37%   |
| Marvell Technology Group        | 5         | 1.14%   |
| Samsung Electronics             | 4         | 0.92%   |
| ASIX Electronics                | 4         | 0.92%   |
| Xiaomi                          | 2         | 0.46%   |
| Shenzhen Goodix Technology      | 1         | 0.23%   |
| Ralink Technology               | 1         | 0.23%   |
| Qualcomm Atheros Communications | 1         | 0.23%   |
| Qualcomm                        | 1         | 0.23%   |
| OPPO Electronics                | 1         | 0.23%   |
| Nvidia                          | 1         | 0.23%   |
| NetGear                         | 1         | 0.23%   |
| Hewlett-Packard                 | 1         | 0.23%   |
| DisplayLink                     | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 90        | 17.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 48        | 9.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 3.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 3.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 2.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 1.96%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 8         | 1.57%   |
| Intel Wireless 8265 / 8275                                              | 8         | 1.57%   |
| Intel Wireless 3160                                                     | 8         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.18%   |
| Intel Wireless 7265                                                     | 6         | 1.18%   |
| Intel Wireless 7260                                                     | 6         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 0.98%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 5         | 0.98%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.98%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 4         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 4         | 0.78%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.78%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.59%   |
| Intel Wireless 8260                                                     | 3         | 0.59%   |
| Intel Wireless 3165                                                     | 3         | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 32.98%  |
| Qualcomm Atheros                | 63        | 22.11%  |
| Realtek Semiconductor           | 59        | 20.7%   |
| Broadcom                        | 32        | 11.23%  |
| MediaTek                        | 14        | 4.91%   |
| TP-Link                         | 10        | 3.51%   |
| Ralink                          | 6         | 2.11%   |
| Broadcom Limited                | 4         | 1.4%    |
| Ralink Technology               | 1         | 0.35%   |
| Qualcomm Atheros Communications | 1         | 0.35%   |
| NetGear                         | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 6.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 18        | 6.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 4.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 10        | 3.48%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 3.14%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 8         | 2.79%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.79%   |
| Intel Wireless 3160                                                     | 8         | 2.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 2.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.09%   |
| Intel Wireless 7265                                                     | 6         | 2.09%   |
| Intel Wireless 7260                                                     | 6         | 2.09%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.74%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 5         | 1.74%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 1.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 4         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.39%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.05%   |
| Intel Wireless 8260                                                     | 3         | 1.05%   |
| Intel Wireless 3165                                                     | 3         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.05%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.05%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.05%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.7%    |
| TP-Link 802.11ac WLAN Adapter                                           | 2         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.7%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 149       | 68.66%  |
| Intel                    | 19        | 8.76%   |
| Qualcomm Atheros         | 15        | 6.91%   |
| Broadcom                 | 13        | 5.99%   |
| Marvell Technology Group | 5         | 2.3%    |
| ASIX Electronics         | 4         | 1.84%   |
| Samsung Electronics      | 3         | 1.38%   |
| Xiaomi                   | 2         | 0.92%   |
| Broadcom Limited         | 2         | 0.92%   |
| TP-Link                  | 1         | 0.46%   |
| Qualcomm                 | 1         | 0.46%   |
| OPPO Electronics         | 1         | 0.46%   |
| Nvidia                   | 1         | 0.46%   |
| DisplayLink              | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 90        | 41.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 21.92%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 2.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 1.83%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.37%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.91%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.91%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.91%   |
| Intel WiMAX Connection 2400m                                           | 2         | 0.91%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.91%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.46%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.46%   |
| OPPO Ace 3V                                                            | 1         | 0.46%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.46%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.46%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.46%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.46%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.46%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 1         | 0.46%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.46%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.46%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 269       | 55.81%  |
| Ethernet | 209       | 43.36%  |
| Modem    | 4         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 212       | 73.36%  |
| Ethernet | 77        | 26.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 191       | 70.48%  |
| 1     | 77        | 28.41%  |
| 0     | 3         | 1.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 217       | 78.91%  |
| Yes  | 58        | 21.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 32.3%   |
| Realtek Semiconductor           | 35        | 15.49%  |
| Qualcomm Atheros Communications | 34        | 15.04%  |
| IMC Networks                    | 16        | 7.08%   |
| Broadcom                        | 14        | 6.19%   |
| Lite-On Technology              | 12        | 5.31%   |
| Apple                           | 10        | 4.42%   |
| Foxconn / Hon Hai               | 9         | 3.98%   |
| Cambridge Silicon Radio         | 4         | 1.77%   |
| Toshiba                         | 3         | 1.33%   |
| Ralink                          | 3         | 1.33%   |
| Hewlett-Packard                 | 3         | 1.33%   |
| Ralink Technology               | 2         | 0.88%   |
| MediaTek                        | 2         | 0.88%   |
| Dell                            | 2         | 0.88%   |
| Realtek                         | 1         | 0.44%   |
| Foxconn International           | 1         | 0.44%   |
| ASUSTek Computer                | 1         | 0.44%   |
| Alps Electric                   | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 35        | 15.49%  |
| Qualcomm Atheros  Bluetooth Device                  | 23        | 10.18%  |
| Realtek Bluetooth Radio                             | 16        | 7.08%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 6.64%   |
| Intel AX201 Bluetooth                               | 15        | 6.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 3.98%   |
| IMC Networks Bluetooth Radio                        | 9         | 3.98%   |
| IMC Networks Wireless_Device                        | 6         | 2.65%   |
| Apple Bluetooth Host Controller                     | 5         | 2.21%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.77%   |
| Lite-On Wireless_Device                             | 4         | 1.77%   |
| Lite-On Bluetooth Device                            | 4         | 1.77%   |
| Intel Bluetooth Device                              | 4         | 1.77%   |
| Intel AX200 Bluetooth                               | 4         | 1.77%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.77%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.77%   |
| Toshiba Bluetooth Device                            | 3         | 1.33%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.33%   |
| MediaTek Wireless_Device                            | 2         | 0.88%   |
| Lite-On Bluetooth Radio                             | 2         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.88%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.88%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.88%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.88%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.88%   |
| Broadcom HP Portable Valentine                      | 2         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.88%   |
| Realtek Bluetooth Radio                             | 1         | 0.44%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.44%   |
| Ralink CSR BS8510                                   | 1         | 0.44%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 208       | 67.1%   |
| AMD                 | 63        | 20.32%  |
| Nvidia              | 32        | 10.32%  |
| Texas Instruments   | 1         | 0.32%   |
| Sony                | 1         | 0.32%   |
| GN Netcom           | 1         | 0.32%   |
| Focusrite-Novation  | 1         | 0.32%   |
| C-Media Electronics | 1         | 0.32%   |
| Audient             | 1         | 0.32%   |
| Apple               | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 35        | 8.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 31        | 7.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 5.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 17        | 4.25%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 3.75%   |
| Intel 8 Series HD Audio Controller                                                                | 15        | 3.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 3.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 3.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 3.25%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 3.25%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 13        | 3.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 3%      |
| AMD High Definition Audio Controller                                                              | 9         | 2.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2%      |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 2%      |
| AMD FCH Azalia Controller                                                                         | 8         | 2%      |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 7         | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.75%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.5%    |
| AMD Wrestler HDMI Audio                                                                           | 6         | 1.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.25%   |
| AMD Radeon High Definition Audio Controller                                                       | 5         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1%      |
| Nvidia GA107 High Definition Audio Controller                                                     | 4         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1%      |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 31.98%  |
| SK hynix            | 40        | 20.3%   |
| Micron Technology   | 24        | 12.18%  |
| Kingston            | 23        | 11.68%  |
| A-DATA Technology   | 10        | 5.08%   |
| Unknown             | 7         | 3.55%   |
| Ramaxel Technology  | 7         | 3.55%   |
| Crucial             | 5         | 2.54%   |
| Nanya Technology    | 4         | 2.03%   |
| Unknown (ABCD)      | 2         | 1.02%   |
| Elpida              | 2         | 1.02%   |
| Avant               | 2         | 1.02%   |
| Team                | 1         | 0.51%   |
| Hikvision           | 1         | 0.51%   |
| Hewlett-Packard     | 1         | 0.51%   |
| GOODRAM             | 1         | 0.51%   |
| fef5                | 1         | 0.51%   |
| Corsair             | 1         | 0.51%   |
| 8054000080CE        | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 3.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 4         | 1.92%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.44%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 1.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 3         | 1.44%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.96%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.96%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.96%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.96%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 2         | 0.96%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.96%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.96%   |
| Kingston RAM SNY1333D3S9ELC/4G 4GB SODIMM DDR3 1334MT/s          | 2         | 0.96%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 0.96%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 2         | 0.96%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.96%   |
| Kingston RAM 9905744-077.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 0.96%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                         | 1         | 0.48%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 84        | 54.55%  |
| DDR3    | 45        | 29.22%  |
| LPDDR4  | 7         | 4.55%   |
| DDR2    | 5         | 3.25%   |
| SDRAM   | 3         | 1.95%   |
| LPDDR3  | 3         | 1.95%   |
| DDR5    | 3         | 1.95%   |
| Unknown | 2         | 1.3%    |
| LPDDR5  | 1         | 0.65%   |
| DDR     | 1         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 137       | 88.96%  |
| Row Of Chips | 13        | 8.44%   |
| Unknown      | 3         | 1.95%   |
| Chip         | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 63        | 36%     |
| 4096  | 63        | 36%     |
| 16384 | 24        | 13.71%  |
| 2048  | 11        | 6.29%   |
| 32768 | 7         | 4%      |
| 1024  | 7         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 42        | 23.73%  |
| 1600    | 41        | 23.16%  |
| 3200    | 34        | 19.21%  |
| 2400    | 14        | 7.91%   |
| 3266    | 7         | 3.95%   |
| 2133    | 5         | 2.82%   |
| 1334    | 5         | 2.82%   |
| 8400    | 4         | 2.26%   |
| 1867    | 3         | 1.69%   |
| 5600    | 2         | 1.13%   |
| 4199    | 2         | 1.13%   |
| 800     | 2         | 1.13%   |
| 667     | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |
| 6400    | 1         | 0.56%   |
| 4800    | 1         | 0.56%   |
| 4267    | 1         | 0.56%   |
| 3733    | 1         | 0.56%   |
| 2048    | 1         | 0.56%   |
| 1776    | 1         | 0.56%   |
| 1333    | 1         | 0.56%   |
| 1067    | 1         | 0.56%   |
| 1066    | 1         | 0.56%   |
| 975     | 1         | 0.56%   |
| 933     | 1         | 0.56%   |
| 533     | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 2         | 40%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Seiko Epson L380 Series         | 1         | 20%     |
| Seiko Epson L3110 Series        | 1         | 20%     |
| Prolific PL2305 Parallel Port   | 1         | 20%     |
| HP Ink Tank Wireless 410 series | 1         | 20%     |
| Brother DCP-T500W               | 1         | 20%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 66        | 26.72%  |
| IMC Networks                           | 27        | 10.93%  |
| Realtek Semiconductor                  | 22        | 8.91%   |
| Microdia                               | 18        | 7.29%   |
| Quanta                                 | 17        | 6.88%   |
| Suyin                                  | 12        | 4.86%   |
| Sunplus Innovation Technology          | 12        | 4.86%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 4.86%   |
| Bison Electronics                      | 10        | 4.05%   |
| Syntek                                 | 7         | 2.83%   |
| Lite-On Technology                     | 6         | 2.43%   |
| Apple                                  | 6         | 2.43%   |
| Luxvisions Innotech Limited            | 5         | 2.02%   |
| Silicon Motion                         | 3         | 1.21%   |
| Ricoh                                  | 3         | 1.21%   |
| Alcor Micro                            | 3         | 1.21%   |
| Sonix Technology                       | 2         | 0.81%   |
| ShineTech                              | 2         | 0.81%   |
| OmniVision Technologies                | 2         | 0.81%   |
| Importek                               | 2         | 0.81%   |
| icSpring                               | 2         | 0.81%   |
| Z-Star Microelectronics                | 1         | 0.4%    |
| Trust                                  | 1         | 0.4%    |
| Shine-optics                           | 1         | 0.4%    |
| Samsung Electronics                    | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| Generalplus Technology                 | 1         | 0.4%    |
| Foxconn / Hon Hai                      | 1         | 0.4%    |
| ALi                                    | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 12        | 4.86%   |
| Chicony Integrated Camera                                                  | 12        | 4.86%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 3.64%   |
| Realtek Integrated_Webcam_HD                                               | 8         | 3.24%   |
| Chicony HP Truevision HD                                                   | 6         | 2.43%   |
| IMC Networks Integrated Camera                                             | 5         | 2.02%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 5         | 2.02%   |
| Chicony TOSHIBA Web Camera - HD                                            | 5         | 2.02%   |
| Realtek Integrated Webcam                                                  | 4         | 1.62%   |
| Quanta HD Webcam                                                           | 4         | 1.62%   |
| Chicony HP TrueVision HD Camera                                            | 4         | 1.62%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                    | 4         | 1.62%   |
| Suyin Integrated_Webcam_HD                                                 | 3         | 1.21%   |
| Suyin HP Truevision HD                                                     | 3         | 1.21%   |
| Suyin HD WebCam                                                            | 3         | 1.21%   |
| Sunplus Integrated_Webcam_HD                                               | 3         | 1.21%   |
| Quanta HP Webcam                                                           | 3         | 1.21%   |
| Microdia USB 2.0 Camera                                                    | 3         | 1.21%   |
| IMC Networks VGA UVC WebCam                                                | 3         | 1.21%   |
| IMC Networks TOSHIBA Web Camera - HD                                       | 3         | 1.21%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.21%   |
| Chicony HD User Facing                                                     | 3         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.21%   |
| Bison Integrated Camera                                                    | 3         | 1.21%   |
| Apple FaceTime HD Camera                                                   | 3         | 1.21%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.81%   |
| Syntek Integrated Camera                                                   | 2         | 0.81%   |
| Syntek EasyCamera                                                          | 2         | 0.81%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 2         | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 2         | 0.81%   |
| ShineTech USB2.0 HD UVC WebCam                                             | 2         | 0.81%   |
| Realtek HP Truevision HD                                                   | 2         | 0.81%   |
| Realtek HP "Truevision HD" laptop camera                                   | 2         | 0.81%   |
| Quanta HP Wide Vision HD Camera                                            | 2         | 0.81%   |
| Quanta HP Webcam-50                                                        | 2         | 0.81%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.81%   |
| OmniVision OV2640 Webcam                                                   | 2         | 0.81%   |
| Luxvisions Innotech Limited Integrated RGB Camera                          | 2         | 0.81%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 2         | 0.81%   |
| Lite-On TOSHIBA Web Camera - HD                                            | 2         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 22.73%  |
| Shenzhen Goodix Technology | 4         | 18.18%  |
| Synaptics                  | 3         | 13.64%  |
| Elan Microelectronics      | 3         | 13.64%  |
| AuthenTec                  | 3         | 13.64%  |
| Upek                       | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 4         | 18.18%  |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 9.09%   |
| Elan ELAN:Fingerprint                                  | 2         | 9.09%   |
| AuthenTec AES1600                                      | 2         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors VFS491                                | 1         | 4.55%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.55%   |
| LighTuning Fingerprint Sensor                          | 1         | 4.55%   |
| Elan ELAN:ARM-M4                                       | 1         | 4.55%   |
| AuthenTec AES2810                                      | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 4         | 50%     |
| O2 Micro | 3         | 37.5%   |
| Upek     | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 12.5%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 190       | 68.84%  |
| 1     | 75        | 27.17%  |
| 2     | 9         | 3.26%   |
| 5     | 1         | 0.36%   |
| 3     | 1         | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 22        | 22%     |
| Net/wireless             | 21        | 21%     |
| Graphics card            | 19        | 19%     |
| Multimedia controller    | 12        | 12%     |
| Chipcard                 | 7         | 7%      |
| Bluetooth                | 5         | 5%      |
| Camera                   | 4         | 4%      |
| Storage                  | 3         | 3%      |
| Sound                    | 3         | 3%      |
| Communication controller | 2         | 2%      |
| Network                  | 1         | 1%      |
| Net/ethernet             | 1         | 1%      |


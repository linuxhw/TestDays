Linux in Egypt - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Egypt.

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

Total: 483

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5570               | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [32c2f39f3a](https://linux-hardware.org/?probe=32c2f39f3a) | Aug 06, 2023 |
| Dell          | Inspiron 3558               | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Toshiba       | Satellite C855D             | [4835e837bd](https://linux-hardware.org/?probe=4835e837bd) | Aug 03, 2023 |
| HP            | ProBook 6475b               | [c3cfc235fe](https://linux-hardware.org/?probe=c3cfc235fe) | Aug 01, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [ad721ddbad](https://linux-hardware.org/?probe=ad721ddbad) | Jul 31, 2023 |
| Dell          | Vostro 15 3515              | [08990a8da3](https://linux-hardware.org/?probe=08990a8da3) | Jul 28, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| Dell          | Inspiron N4050              | [42ddc0425b](https://linux-hardware.org/?probe=42ddc0425b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [0093aba5fd](https://linux-hardware.org/?probe=0093aba5fd) | Jul 16, 2023 |
| HP            | Unknown                     | [e36ee407e4](https://linux-hardware.org/?probe=e36ee407e4) | Jul 12, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [5d4cb4e73a](https://linux-hardware.org/?probe=5d4cb4e73a) | Jul 03, 2023 |
| HP            | Laptop 15-dw3xxx            | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | [587f8b6b83](https://linux-hardware.org/?probe=587f8b6b83) | Jul 01, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [7d8f0212e9](https://linux-hardware.org/?probe=7d8f0212e9) | Jun 24, 2023 |
| HP            | EliteBook 8540w             | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d4da1625e2](https://linux-hardware.org/?probe=d4da1625e2) | Jun 12, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ac48eeb92c](https://linux-hardware.org/?probe=ac48eeb92c) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | [ade15528d8](https://linux-hardware.org/?probe=ade15528d8) | Jun 10, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| Dell          | Vostro 15 3515              | [8a69d6c123](https://linux-hardware.org/?probe=8a69d6c123) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [ecfe7565f4](https://linux-hardware.org/?probe=ecfe7565f4) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [2fadb86df4](https://linux-hardware.org/?probe=2fadb86df4) | May 27, 2023 |
| HP            | EliteBook 8440p             | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dedcc1bb3f](https://linux-hardware.org/?probe=dedcc1bb3f) | May 22, 2023 |
| Dell          | Inspiron N4050              | [ec1357e74e](https://linux-hardware.org/?probe=ec1357e74e) | May 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7ab850285a](https://linux-hardware.org/?probe=7ab850285a) | May 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [3ff6a3dac0](https://linux-hardware.org/?probe=3ff6a3dac0) | May 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [483415e8cb](https://linux-hardware.org/?probe=483415e8cb) | May 05, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3ab78594e3](https://linux-hardware.org/?probe=3ab78594e3) | May 02, 2023 |
| HP            | Unknown                     | [475eb33956](https://linux-hardware.org/?probe=475eb33956) | May 01, 2023 |
| Lenovo        | ThinkPad X220 429044U       | [1bf66ba9be](https://linux-hardware.org/?probe=1bf66ba9be) | Apr 26, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [43aae4850b](https://linux-hardware.org/?probe=43aae4850b) | Apr 23, 2023 |
| HP            | Notebook                    | [36788985ec](https://linux-hardware.org/?probe=36788985ec) | Apr 20, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b1c04430cc](https://linux-hardware.org/?probe=b1c04430cc) | Apr 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b2873d15a0](https://linux-hardware.org/?probe=b2873d15a0) | Apr 19, 2023 |
| HP            | Notebook                    | [072fc2bf12](https://linux-hardware.org/?probe=072fc2bf12) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6fae9a24fb](https://linux-hardware.org/?probe=6fae9a24fb) | Apr 19, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c33ef2ceeb](https://linux-hardware.org/?probe=c33ef2ceeb) | Apr 11, 2023 |
| HP            | Laptop 15-bs0xx             | [c73108de7b](https://linux-hardware.org/?probe=c73108de7b) | Apr 06, 2023 |
| Dell          | Latitude 7350               | [9bdfad0684](https://linux-hardware.org/?probe=9bdfad0684) | Apr 06, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | [9de89fee19](https://linux-hardware.org/?probe=9de89fee19) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | [7b4a51d5e3](https://linux-hardware.org/?probe=7b4a51d5e3) | Mar 29, 2023 |
| Dell          | Latitude 7350               | [de44a7d43c](https://linux-hardware.org/?probe=de44a7d43c) | Mar 28, 2023 |
| HP            | Compaq 610                  | [dc9383200e](https://linux-hardware.org/?probe=dc9383200e) | Mar 28, 2023 |
| Dell          | Latitude 7350               | [8ef24a8281](https://linux-hardware.org/?probe=8ef24a8281) | Mar 28, 2023 |
| Dell          | Latitude E6430              | [912e5e8577](https://linux-hardware.org/?probe=912e5e8577) | Mar 26, 2023 |
| Dell          | Latitude E6430              | [237dabb566](https://linux-hardware.org/?probe=237dabb566) | Mar 26, 2023 |
| HP            | 250 G4                      | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| Lenovo        | S20-30 20421                | [3c1dd3564d](https://linux-hardware.org/?probe=3c1dd3564d) | Mar 19, 2023 |
| Dell          | G5 5500                     | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Dell          | G3 3579                     | [e548fa074e](https://linux-hardware.org/?probe=e548fa074e) | Mar 14, 2023 |
| Dell          | Inspiron N4050              | [3b1827fe4f](https://linux-hardware.org/?probe=3b1827fe4f) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Dell          | Latitude 5420               | [948cbeda59](https://linux-hardware.org/?probe=948cbeda59) | Feb 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Dell          | G3 3579                     | [4721b18608](https://linux-hardware.org/?probe=4721b18608) | Feb 09, 2023 |
| HP            | Compaq Presario CQ61        | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | [bc685693a6](https://linux-hardware.org/?probe=bc685693a6) | Jan 30, 2023 |
| Dell          | Inspiron 3580               | [e049beb54a](https://linux-hardware.org/?probe=e049beb54a) | Jan 28, 2023 |
| Lenovo        | Z51-70 80K6                 | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Dell          | G15 5511                    | [cea8996d31](https://linux-hardware.org/?probe=cea8996d31) | Jan 23, 2023 |
| Dell          | Latitude 5580               | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| Acer          | Nitro AN515-55              | [58db914ce7](https://linux-hardware.org/?probe=58db914ce7) | Jan 14, 2023 |
| Acer          | Nitro AN515-55              | [85969e813b](https://linux-hardware.org/?probe=85969e813b) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| Dell          | Inspiron N4050              | [9464593531](https://linux-hardware.org/?probe=9464593531) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [eab4c8b296](https://linux-hardware.org/?probe=eab4c8b296) | Jan 06, 2023 |
| Lenovo        | Z51-70 80K6                 | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| HP            | Laptop 15-bs0xx             | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| Dell          | Latitude E7470              | [2894205731](https://linux-hardware.org/?probe=2894205731) | Dec 19, 2022 |
| Dell          | Latitude 5580               | [c8b402d4df](https://linux-hardware.org/?probe=c8b402d4df) | Dec 18, 2022 |
| Dell          | Latitude 5580               | [b45e1798cc](https://linux-hardware.org/?probe=b45e1798cc) | Dec 18, 2022 |
| HP            | 15                          | [95f40991cc](https://linux-hardware.org/?probe=95f40991cc) | Dec 18, 2022 |
| HP            | EliteBook 840 G5            | [2c57417bdf](https://linux-hardware.org/?probe=2c57417bdf) | Dec 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| Lenovo        | Z50-70 20354                | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| HP            | Laptop 15s-eq2xxx           | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | EliteBook 745 G3            | [6c7a9e7fe5](https://linux-hardware.org/?probe=6c7a9e7fe5) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| HP            | EliteBook 820 G4            | [d4ed3112e5](https://linux-hardware.org/?probe=d4ed3112e5) | Nov 21, 2022 |
| HP            | EliteBook 820 G4            | [c565a2d0fc](https://linux-hardware.org/?probe=c565a2d0fc) | Nov 21, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Dell          | Inspiron 3593               | [f5c9f5e8e1](https://linux-hardware.org/?probe=f5c9f5e8e1) | Nov 19, 2022 |
| Lenovo        | IdeaPad Z470                | [bc0980a6df](https://linux-hardware.org/?probe=bc0980a6df) | Nov 16, 2022 |
| Hampoo        | Cherry Trail CR             | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| Dell          | Latitude D630               | [ef49631a3c](https://linux-hardware.org/?probe=ef49631a3c) | Nov 12, 2022 |
| Samsung       | 275E4E/275E5E               | [0eba8cf68e](https://linux-hardware.org/?probe=0eba8cf68e) | Nov 09, 2022 |
| Dell          | Precision 5520              | [a96e7097e1](https://linux-hardware.org/?probe=a96e7097e1) | Nov 03, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | [8575548418](https://linux-hardware.org/?probe=8575548418) | Oct 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [38c23f070a](https://linux-hardware.org/?probe=38c23f070a) | Oct 27, 2022 |
| Dell          | Latitude E7270              | [7c249e55c8](https://linux-hardware.org/?probe=7c249e55c8) | Oct 27, 2022 |
| HP            | Notebook                    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | Notebook                    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Dell          | G15 5510                    | [1286ecf9dd](https://linux-hardware.org/?probe=1286ecf9dd) | Oct 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a360479032](https://linux-hardware.org/?probe=a360479032) | Oct 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [72e2c65863](https://linux-hardware.org/?probe=72e2c65863) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Sony          | VPCEH3LFX                   | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| HP            | ENVY m6                     | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| HP            | Notebook                    | [a30c1af9a5](https://linux-hardware.org/?probe=a30c1af9a5) | Sep 30, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [113f7431d5](https://linux-hardware.org/?probe=113f7431d5) | Sep 28, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [cf8fefa8b5](https://linux-hardware.org/?probe=cf8fefa8b5) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | [d0f2ed977a](https://linux-hardware.org/?probe=d0f2ed977a) | Sep 28, 2022 |
| Dell          | Inspiron N5110              | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [3f9e2bb677](https://linux-hardware.org/?probe=3f9e2bb677) | Sep 23, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [10103bf87f](https://linux-hardware.org/?probe=10103bf87f) | Sep 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [56bff32d34](https://linux-hardware.org/?probe=56bff32d34) | Sep 21, 2022 |
| Dell          | Latitude 3540               | [7e56d744b7](https://linux-hardware.org/?probe=7e56d744b7) | Sep 21, 2022 |
| Dell          | Latitude 3540               | [0216f52b36](https://linux-hardware.org/?probe=0216f52b36) | Sep 21, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | [fef4bc54eb](https://linux-hardware.org/?probe=fef4bc54eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | [db6bdb0dbd](https://linux-hardware.org/?probe=db6bdb0dbd) | Sep 20, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [e91328a3c2](https://linux-hardware.org/?probe=e91328a3c2) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Samsung       | Lumpy                       | [9c1fd4f253](https://linux-hardware.org/?probe=9c1fd4f253) | Sep 18, 2022 |
| Samsung       | Lumpy                       | [1ea9c40a42](https://linux-hardware.org/?probe=1ea9c40a42) | Sep 15, 2022 |
| ASUSTek       | X555LD                      | [12d6e02796](https://linux-hardware.org/?probe=12d6e02796) | Sep 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0356a8d7a1](https://linux-hardware.org/?probe=0356a8d7a1) | Sep 05, 2022 |
| HP            | Pavilion 15                 | [ed8a48954e](https://linux-hardware.org/?probe=ed8a48954e) | Sep 04, 2022 |
| Dell          | G15 5510                    | [fbcdd4d274](https://linux-hardware.org/?probe=fbcdd4d274) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [93980a32fc](https://linux-hardware.org/?probe=93980a32fc) | Sep 02, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| HP            | EliteBook 8560w             | [0ea43b9010](https://linux-hardware.org/?probe=0ea43b9010) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77a2156c5a](https://linux-hardware.org/?probe=77a2156c5a) | Aug 21, 2022 |
| HP            | ProBook 655 G1              | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [c62eb0135b](https://linux-hardware.org/?probe=c62eb0135b) | Aug 15, 2022 |
| HP            | EliteBook 8560w             | [86b3f33331](https://linux-hardware.org/?probe=86b3f33331) | Aug 14, 2022 |
| HP            | EliteBook 8560w             | [4ea7538e24](https://linux-hardware.org/?probe=4ea7538e24) | Aug 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e97781a7cc](https://linux-hardware.org/?probe=e97781a7cc) | Aug 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [abe7afa30f](https://linux-hardware.org/?probe=abe7afa30f) | Aug 09, 2022 |
| Lenovo        | V15-ADA 82C7                | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Toshiba       | NB250                       | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | G62                         | [dd114592c4](https://linux-hardware.org/?probe=dd114592c4) | Jul 27, 2022 |
| MSI           | MS-14Y1                     | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [5510f2d904](https://linux-hardware.org/?probe=5510f2d904) | Jul 18, 2022 |
| Panasonic     | FZG1-3                      | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1f42376321](https://linux-hardware.org/?probe=1f42376321) | Jul 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [977cf239f9](https://linux-hardware.org/?probe=977cf239f9) | Jul 08, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b1d77e2a01](https://linux-hardware.org/?probe=b1d77e2a01) | Jul 05, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [8e2249c595](https://linux-hardware.org/?probe=8e2249c595) | Jul 05, 2022 |
| HP            | EliteBook 840 G4            | [342facf96e](https://linux-hardware.org/?probe=342facf96e) | Jul 04, 2022 |
| HP            | Pavilion 15                 | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| HP            | Pavilion 15                 | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | ProBook 645 G1              | [1157ee7e3a](https://linux-hardware.org/?probe=1157ee7e3a) | Jun 21, 2022 |
| ASUSTek       | X555LJ                      | [ee2a9b3c87](https://linux-hardware.org/?probe=ee2a9b3c87) | Jun 20, 2022 |
| Dell          | G5 5587                     | [9f2ca6b48b](https://linux-hardware.org/?probe=9f2ca6b48b) | Jun 18, 2022 |
| Lenovo        | B40-80 80F6                 | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| ASUSTek       | X553MA                      | [1794b92b61](https://linux-hardware.org/?probe=1794b92b61) | Jun 12, 2022 |
| Dell          | Latitude E6410              | [184348232a](https://linux-hardware.org/?probe=184348232a) | Jun 11, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [4058369652](https://linux-hardware.org/?probe=4058369652) | May 21, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bd33528d52](https://linux-hardware.org/?probe=bd33528d52) | May 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | Pavilion 15                 | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Dell          | Inspiron N4050              | [6d8f615203](https://linux-hardware.org/?probe=6d8f615203) | Apr 30, 2022 |
| Dell          | Inspiron N5110              | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| HP            | Pavilion 15                 | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Fujitsu       | FMVA06004                   | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Dell          | Latitude 3440               | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| HP            | Laptop 15-bs0xx             | [a1636896d9](https://linux-hardware.org/?probe=a1636896d9) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | [03481a94b3](https://linux-hardware.org/?probe=03481a94b3) | Apr 22, 2022 |
| HP            | 15                          | [3253e0fc56](https://linux-hardware.org/?probe=3253e0fc56) | Apr 21, 2022 |
| Sony          | SVT1121B2EW                 | [dd43f45353](https://linux-hardware.org/?probe=dd43f45353) | Apr 21, 2022 |
| Dell          | Inspiron 7577               | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| Alienware     | 17                          | [b9b420077c](https://linux-hardware.org/?probe=b9b420077c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [fecdd237a4](https://linux-hardware.org/?probe=fecdd237a4) | Apr 11, 2022 |
| Lenovo        | Flex 2-14 20404             | [4368114931](https://linux-hardware.org/?probe=4368114931) | Apr 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f93e8f46c2](https://linux-hardware.org/?probe=f93e8f46c2) | Apr 01, 2022 |
| HP            | Laptop 15-bs0xx             | [bd875807ce](https://linux-hardware.org/?probe=bd875807ce) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | [96f9ba743f](https://linux-hardware.org/?probe=96f9ba743f) | Mar 25, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [55a2911462](https://linux-hardware.org/?probe=55a2911462) | Mar 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Notebook                    | [4cc8a23994](https://linux-hardware.org/?probe=4cc8a23994) | Mar 22, 2022 |
| HP            | Notebook                    | [cb2c910f05](https://linux-hardware.org/?probe=cb2c910f05) | Mar 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [99dc5cde41](https://linux-hardware.org/?probe=99dc5cde41) | Mar 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d74cd69ff9](https://linux-hardware.org/?probe=d74cd69ff9) | Mar 20, 2022 |
| HP            | Pavilion 15                 | [0f3cb22c3d](https://linux-hardware.org/?probe=0f3cb22c3d) | Mar 20, 2022 |
| HP            | G62                         | [5a5a9ce935](https://linux-hardware.org/?probe=5a5a9ce935) | Mar 20, 2022 |
| HP            | ENVY dv6                    | [39ff0aa86d](https://linux-hardware.org/?probe=39ff0aa86d) | Mar 17, 2022 |
| Dell          | Latitude 3410               | [d21a10beb4](https://linux-hardware.org/?probe=d21a10beb4) | Mar 10, 2022 |
| Acer          | Aspire ES1-331              | [cbba045d50](https://linux-hardware.org/?probe=cbba045d50) | Mar 05, 2022 |
| HP            | Pavilion Notebook           | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| Dell          | Venue 10 Pro 5056           | [faf162367f](https://linux-hardware.org/?probe=faf162367f) | Feb 25, 2022 |
| HP            | Laptop 15-db0xxx            | [732784f9ec](https://linux-hardware.org/?probe=732784f9ec) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [2c3ac58820](https://linux-hardware.org/?probe=2c3ac58820) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| HP            | ENVY dv6                    | [6d07aead9f](https://linux-hardware.org/?probe=6d07aead9f) | Feb 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| Dell          | G3 3500                     | [0010596573](https://linux-hardware.org/?probe=0010596573) | Feb 10, 2022 |
| Dell          | Latitude E6540              | [9129341c42](https://linux-hardware.org/?probe=9129341c42) | Jan 24, 2022 |
| HP            | ProBook 445 G7              | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| Sony          | SVF15328CXB                 | [d55d8f394d](https://linux-hardware.org/?probe=d55d8f394d) | Jan 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dfbb7c034f](https://linux-hardware.org/?probe=dfbb7c034f) | Jan 20, 2022 |
| HP            | 250 G7 Notebook PC          | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| Dell          | Inspiron N5010              | [4edc707b67](https://linux-hardware.org/?probe=4edc707b67) | Jan 14, 2022 |
| HP            | EliteBook 8440p             | [b70942532f](https://linux-hardware.org/?probe=b70942532f) | Jan 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| HP            | EliteBook 8440p             | [bda1b240c9](https://linux-hardware.org/?probe=bda1b240c9) | Dec 28, 2021 |
| Dell          | G15 5510                    | [1209f0844f](https://linux-hardware.org/?probe=1209f0844f) | Dec 20, 2021 |
| Dell          | G15 5510                    | [e5039b3b7d](https://linux-hardware.org/?probe=e5039b3b7d) | Dec 18, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [f8dc028352](https://linux-hardware.org/?probe=f8dc028352) | Dec 08, 2021 |
| HP            | Compaq CQ58                 | [dd578dae69](https://linux-hardware.org/?probe=dd578dae69) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | [d15350584d](https://linux-hardware.org/?probe=d15350584d) | Dec 05, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [d6acd43784](https://linux-hardware.org/?probe=d6acd43784) | Nov 25, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [e820cb3456](https://linux-hardware.org/?probe=e820cb3456) | Nov 25, 2021 |
| HP            | ProBook 470 G3              | [49f973804a](https://linux-hardware.org/?probe=49f973804a) | Nov 13, 2021 |
| Dell          | Latitude 5420               | [973018da2b](https://linux-hardware.org/?probe=973018da2b) | Nov 08, 2021 |
| Dell          | Inspiron 3537               | [eacb69d71e](https://linux-hardware.org/?probe=eacb69d71e) | Nov 05, 2021 |
| Lenovo        | ThinkPad E14 20RAS0CM00     | [a35aaaeb6d](https://linux-hardware.org/?probe=a35aaaeb6d) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | [e8781db5ab](https://linux-hardware.org/?probe=e8781db5ab) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | [e1978d5164](https://linux-hardware.org/?probe=e1978d5164) | Oct 31, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [08d287d2e2](https://linux-hardware.org/?probe=08d287d2e2) | Oct 30, 2021 |
| HP            | ProBook 6460b               | [317c62df4b](https://linux-hardware.org/?probe=317c62df4b) | Oct 23, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [2db5d6dc7c](https://linux-hardware.org/?probe=2db5d6dc7c) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [1faf3f28e5](https://linux-hardware.org/?probe=1faf3f28e5) | Oct 20, 2021 |
| Dell          | Inspiron 3521               | [831fff897a](https://linux-hardware.org/?probe=831fff897a) | Oct 15, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d69772c626](https://linux-hardware.org/?probe=d69772c626) | Oct 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0086ED     | [2db7f4be45](https://linux-hardware.org/?probe=2db7f4be45) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e8ae6d00a2](https://linux-hardware.org/?probe=e8ae6d00a2) | Oct 12, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| HP            | ProBook 645 G1              | [102902cf2b](https://linux-hardware.org/?probe=102902cf2b) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [51d51a675d](https://linux-hardware.org/?probe=51d51a675d) | Oct 10, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [f8d957d29f](https://linux-hardware.org/?probe=f8d957d29f) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c5495590b](https://linux-hardware.org/?probe=6c5495590b) | Oct 08, 2021 |
| Hampoo        | Cherry Trail CR             | [b95391e679](https://linux-hardware.org/?probe=b95391e679) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | [61c4dc2ac2](https://linux-hardware.org/?probe=61c4dc2ac2) | Oct 03, 2021 |
| ASUSTek       | N501JW                      | [0e37d3409d](https://linux-hardware.org/?probe=0e37d3409d) | Oct 01, 2021 |
| Dell          | Inspiron 5584               | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| HP            | Compaq 2510p                | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Packard Be... | EasyNote LX                 | [125ad979fe](https://linux-hardware.org/?probe=125ad979fe) | Aug 06, 2021 |
| Dell          | G3 3579                     | [4f7539c771](https://linux-hardware.org/?probe=4f7539c771) | Jul 30, 2021 |
| Dell          | Inspiron 1564               | [08fc5f3b99](https://linux-hardware.org/?probe=08fc5f3b99) | Jul 27, 2021 |
| Dell          | Inspiron 5570               | [b07887acc1](https://linux-hardware.org/?probe=b07887acc1) | Jul 18, 2021 |
| Lenovo        | G510 20238                  | [428dcd6503](https://linux-hardware.org/?probe=428dcd6503) | Jul 07, 2021 |
| Dell          | G3 3579                     | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| ASUSTek       | X200MA                      | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| Dell          | Inspiron 1545               | [8c7ef2bc15](https://linux-hardware.org/?probe=8c7ef2bc15) | Jun 20, 2021 |
| Dell          | Inspiron 1545               | [4c397b8b70](https://linux-hardware.org/?probe=4c397b8b70) | Jun 20, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [e57c2fb16d](https://linux-hardware.org/?probe=e57c2fb16d) | May 30, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [976e39384a](https://linux-hardware.org/?probe=976e39384a) | May 30, 2021 |
| HP            | ProBook 645 G1              | [a92458c2db](https://linux-hardware.org/?probe=a92458c2db) | May 26, 2021 |
| Fujitsu       | LIFEBOOK S752               | [6ae217a5a8](https://linux-hardware.org/?probe=6ae217a5a8) | May 21, 2021 |
| Dell          | G5 5587                     | [fae808ae7d](https://linux-hardware.org/?probe=fae808ae7d) | May 02, 2021 |
| HP            | Notebook                    | [872a5f9112](https://linux-hardware.org/?probe=872a5f9112) | Apr 18, 2021 |
| Hampoo        | Cherry Trail CR             | [101c47c9a2](https://linux-hardware.org/?probe=101c47c9a2) | Apr 17, 2021 |
| Fujitsu Si... | AMILO Li1705                | [3200f41cf0](https://linux-hardware.org/?probe=3200f41cf0) | Apr 13, 2021 |
| HP            | 15                          | [27bcfc6f15](https://linux-hardware.org/?probe=27bcfc6f15) | Apr 10, 2021 |
| HP            | 15                          | [aebfb75282](https://linux-hardware.org/?probe=aebfb75282) | Apr 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [820db16b30](https://linux-hardware.org/?probe=820db16b30) | Apr 08, 2021 |
| Dell          | Inspiron 3580               | [fcb5ccbc6c](https://linux-hardware.org/?probe=fcb5ccbc6c) | Apr 08, 2021 |
| Dell          | Inspiron 7577               | [a3ecba2a79](https://linux-hardware.org/?probe=a3ecba2a79) | Apr 06, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [bb1ef328b0](https://linux-hardware.org/?probe=bb1ef328b0) | Mar 30, 2021 |
| HP            | Unknown                     | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| HP            | Pavilion dv6                | [ecb76b364b](https://linux-hardware.org/?probe=ecb76b364b) | Mar 20, 2021 |
| Lenovo        | ThinkPad X250 20CM003WMS    | [9dbe8f6250](https://linux-hardware.org/?probe=9dbe8f6250) | Mar 12, 2021 |
| TECNO         | WinPad 10A                  | [e96bf0a4fa](https://linux-hardware.org/?probe=e96bf0a4fa) | Mar 08, 2021 |
| Lenovo        | AILZx                       | [b0c93e5b27](https://linux-hardware.org/?probe=b0c93e5b27) | Mar 07, 2021 |
| Lenovo        | AILZx                       | [d06410a1dd](https://linux-hardware.org/?probe=d06410a1dd) | Mar 04, 2021 |
| Lenovo        | AILZx                       | [cf1bc93ffd](https://linux-hardware.org/?probe=cf1bc93ffd) | Mar 04, 2021 |
| Lenovo        | G50-80 80E5                 | [5ba97fc0d2](https://linux-hardware.org/?probe=5ba97fc0d2) | Mar 03, 2021 |
| HP            | EliteBook 8470p             | [586d9baf41](https://linux-hardware.org/?probe=586d9baf41) | Feb 25, 2021 |
| HP            | EliteBook 8470p             | [f22c5da52d](https://linux-hardware.org/?probe=f22c5da52d) | Feb 25, 2021 |
| Dell          | Inspiron 5570               | [4fd5f831b6](https://linux-hardware.org/?probe=4fd5f831b6) | Feb 22, 2021 |
| Dell          | Latitude XT3                | [2335b761fb](https://linux-hardware.org/?probe=2335b761fb) | Feb 16, 2021 |
| HP            | 250 G3                      | [67cb272c8e](https://linux-hardware.org/?probe=67cb272c8e) | Feb 14, 2021 |
| Dell          | Latitude XT3                | [94f5a1f396](https://linux-hardware.org/?probe=94f5a1f396) | Feb 13, 2021 |
| HP            | Laptop 15-da1xxx            | [6472781079](https://linux-hardware.org/?probe=6472781079) | Feb 09, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [fdfa43b360](https://linux-hardware.org/?probe=fdfa43b360) | Feb 01, 2021 |
| HP            | ProBook 450 G7              | [7e3a962336](https://linux-hardware.org/?probe=7e3a962336) | Jan 31, 2021 |
| Lenovo        | G50-80 80E5                 | [9072c5e554](https://linux-hardware.org/?probe=9072c5e554) | Jan 29, 2021 |
| HP            | Pavilion dv6                | [55752483ef](https://linux-hardware.org/?probe=55752483ef) | Jan 25, 2021 |
| Lenovo        | ThinkPad T580 20LAS09100    | [92d071729f](https://linux-hardware.org/?probe=92d071729f) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | [e596928019](https://linux-hardware.org/?probe=e596928019) | Jan 22, 2021 |
| HP            | Laptop 15-da1xxx            | [8b2119a584](https://linux-hardware.org/?probe=8b2119a584) | Jan 22, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdfeee2839](https://linux-hardware.org/?probe=bdfeee2839) | Jan 21, 2021 |
| Dell          | G3 3590                     | [27fb9a0695](https://linux-hardware.org/?probe=27fb9a0695) | Jan 12, 2021 |
| HP            | Pavilion dv6                | [dbf279a62e](https://linux-hardware.org/?probe=dbf279a62e) | Jan 07, 2021 |
| HP            | Pavilion dv6                | [f14ce7c7c0](https://linux-hardware.org/?probe=f14ce7c7c0) | Jan 07, 2021 |
| Dell          | Inspiron 5520               | [a8f7f002a3](https://linux-hardware.org/?probe=a8f7f002a3) | Jan 06, 2021 |
| Dell          | Inspiron 7577               | [09ee69f73b](https://linux-hardware.org/?probe=09ee69f73b) | Jan 05, 2021 |
| HP            | ZBook 15 G2                 | [062d9c02f6](https://linux-hardware.org/?probe=062d9c02f6) | Jan 03, 2021 |
| HP            | Pavilion dv6                | [d18c93f636](https://linux-hardware.org/?probe=d18c93f636) | Dec 31, 2020 |
| HP            | Pavilion dv6                | [0a288440a6](https://linux-hardware.org/?probe=0a288440a6) | Dec 31, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [1262d56db8](https://linux-hardware.org/?probe=1262d56db8) | Dec 30, 2020 |
| Dell          | Latitude E6400              | [9f5ac2d658](https://linux-hardware.org/?probe=9f5ac2d658) | Dec 30, 2020 |
| Toshiba       | Satellite C660              | [054d224782](https://linux-hardware.org/?probe=054d224782) | Dec 25, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Apple         | MacBookPro5,3               | [29542ce3fc](https://linux-hardware.org/?probe=29542ce3fc) | Dec 23, 2020 |
| Lenovo        | ThinkPad E15 20RD001HAD     | [4f6e684aa1](https://linux-hardware.org/?probe=4f6e684aa1) | Dec 22, 2020 |
| HP            | Pavilion g6                 | [172d4abbd7](https://linux-hardware.org/?probe=172d4abbd7) | Dec 19, 2020 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [9d4e1e6361](https://linux-hardware.org/?probe=9d4e1e6361) | Dec 17, 2020 |
| HP            | ProBook 4540s               | [a35b479f53](https://linux-hardware.org/?probe=a35b479f53) | Dec 09, 2020 |
| HP            | ZBook 15                    | [f7f246578a](https://linux-hardware.org/?probe=f7f246578a) | Dec 07, 2020 |
| ASUSTek       | X455LD                      | [9e5d7995ce](https://linux-hardware.org/?probe=9e5d7995ce) | Dec 03, 2020 |
| Lenovo        | ThinkPad T580 20LAS09100    | [d5a8abcbc5](https://linux-hardware.org/?probe=d5a8abcbc5) | Dec 01, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c9204a3c7d](https://linux-hardware.org/?probe=c9204a3c7d) | Nov 22, 2020 |
| Fujitsu       | LIFEBOOK S752               | [db7eb29112](https://linux-hardware.org/?probe=db7eb29112) | Nov 22, 2020 |
| I-Life Dig... | ZED AIR 2                   | [74f5e7c221](https://linux-hardware.org/?probe=74f5e7c221) | Nov 20, 2020 |
| I-Life Dig... | ZED AIR 2                   | [04802ac1cb](https://linux-hardware.org/?probe=04802ac1cb) | Nov 20, 2020 |
| HP            | ZBook 15                    | [9adafc3a81](https://linux-hardware.org/?probe=9adafc3a81) | Nov 19, 2020 |
| Dell          | Inspiron 7577               | [c09f7df61e](https://linux-hardware.org/?probe=c09f7df61e) | Nov 18, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [630b92e4d0](https://linux-hardware.org/?probe=630b92e4d0) | Nov 18, 2020 |
| HP            | EliteBook 2570p             | [3d005c24b6](https://linux-hardware.org/?probe=3d005c24b6) | Nov 17, 2020 |
| HP            | ProBook 450 G7              | [907aebb56a](https://linux-hardware.org/?probe=907aebb56a) | Nov 16, 2020 |
| HP            | EliteBook 745 G3            | [ec87278338](https://linux-hardware.org/?probe=ec87278338) | Nov 14, 2020 |
| HP            | EliteBook 850 G1            | [0b7205d523](https://linux-hardware.org/?probe=0b7205d523) | Nov 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [cee12c5d76](https://linux-hardware.org/?probe=cee12c5d76) | Nov 09, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5aff9926a](https://linux-hardware.org/?probe=b5aff9926a) | Nov 09, 2020 |
| HP            | Pavilion g6                 | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | Pavilion g6                 | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Dell          | Latitude 3590               | [6a285d94b7](https://linux-hardware.org/?probe=6a285d94b7) | Nov 02, 2020 |
| Dell          | Latitude E5570              | [ba5361df9e](https://linux-hardware.org/?probe=ba5361df9e) | Oct 29, 2020 |
| Dell          | G5 5587                     | [14789ef506](https://linux-hardware.org/?probe=14789ef506) | Oct 27, 2020 |
| Dell          | G5 5587                     | [414f6ca570](https://linux-hardware.org/?probe=414f6ca570) | Oct 27, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [3810f22dfc](https://linux-hardware.org/?probe=3810f22dfc) | Oct 23, 2020 |
| Dell          | Inspiron 5570               | [b7c7ae8b8b](https://linux-hardware.org/?probe=b7c7ae8b8b) | Oct 17, 2020 |
| HP            | Laptop 15-da1xxx            | [8e58300f1c](https://linux-hardware.org/?probe=8e58300f1c) | Oct 17, 2020 |
| HP            | ProBook 450 G7              | [e6c4e6ff27](https://linux-hardware.org/?probe=e6c4e6ff27) | Oct 15, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [59bbdc5626](https://linux-hardware.org/?probe=59bbdc5626) | Oct 14, 2020 |
| HP            | ProBook 450 G7              | [1722d6f45f](https://linux-hardware.org/?probe=1722d6f45f) | Oct 13, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [9a361154cb](https://linux-hardware.org/?probe=9a361154cb) | Oct 11, 2020 |
| HP            | EliteBook 840 G1            | [8d775d0fba](https://linux-hardware.org/?probe=8d775d0fba) | Oct 07, 2020 |
| HP            | EliteBook 840 G1            | [0f22425e10](https://linux-hardware.org/?probe=0f22425e10) | Oct 07, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [68e8da08fa](https://linux-hardware.org/?probe=68e8da08fa) | Oct 06, 2020 |
| HP            | ProBook 645 G1              | [6a95a69346](https://linux-hardware.org/?probe=6a95a69346) | Oct 04, 2020 |
| HP            | ProBook 645 G1              | [fc81852ffb](https://linux-hardware.org/?probe=fc81852ffb) | Oct 04, 2020 |
| ASUSTek       | G53SW                       | [cb9eb22047](https://linux-hardware.org/?probe=cb9eb22047) | Oct 02, 2020 |
| HP            | Laptop 15-da1xxx            | [6e17f92f25](https://linux-hardware.org/?probe=6e17f92f25) | Sep 30, 2020 |
| HP            | Laptop 15-da1xxx            | [839f278908](https://linux-hardware.org/?probe=839f278908) | Sep 30, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [e22e757c8c](https://linux-hardware.org/?probe=e22e757c8c) | Sep 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [105d229822](https://linux-hardware.org/?probe=105d229822) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4d46200fc3](https://linux-hardware.org/?probe=4d46200fc3) | Sep 17, 2020 |
| ASUSTek       | X580VN                      | [cdd3998e5d](https://linux-hardware.org/?probe=cdd3998e5d) | Sep 12, 2020 |
| ASUSTek       | X580VN                      | [02de9a38ac](https://linux-hardware.org/?probe=02de9a38ac) | Sep 12, 2020 |
| HP            | ProBook 645 G1              | [0a888dfc64](https://linux-hardware.org/?probe=0a888dfc64) | Sep 12, 2020 |
| HP            | ZBook 15 G2                 | [29083832b1](https://linux-hardware.org/?probe=29083832b1) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| Dell          | Inspiron 3543               | [82f88ee681](https://linux-hardware.org/?probe=82f88ee681) | Aug 09, 2020 |
| Dell          | G5 5587                     | [ff9bde0012](https://linux-hardware.org/?probe=ff9bde0012) | Aug 06, 2020 |
| Dell          | G5 5587                     | [0f1718b1a5](https://linux-hardware.org/?probe=0f1718b1a5) | Aug 03, 2020 |
| HP            | EliteBook 745 G3            | [0107343e87](https://linux-hardware.org/?probe=0107343e87) | Aug 02, 2020 |
| Dell          | Latitude 7400               | [bb45d9a55f](https://linux-hardware.org/?probe=bb45d9a55f) | Jul 31, 2020 |
| Dell          | Inspiron 7577               | [3ed23397a7](https://linux-hardware.org/?probe=3ed23397a7) | Jul 30, 2020 |
| HP            | ZBook 15 G3                 | [5bd1b54d12](https://linux-hardware.org/?probe=5bd1b54d12) | Jul 28, 2020 |
| Dell          | Inspiron 3593               | [51ed8b0103](https://linux-hardware.org/?probe=51ed8b0103) | Jul 28, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | [f599cd92cd](https://linux-hardware.org/?probe=f599cd92cd) | Jul 27, 2020 |
| HP            | ZBook 15 G3                 | [81dd1b462b](https://linux-hardware.org/?probe=81dd1b462b) | Jul 26, 2020 |
| Lenovo        | ThinkPad E580 20KS0008AD    | [5e0f6c1dce](https://linux-hardware.org/?probe=5e0f6c1dce) | Jul 26, 2020 |
| Lenovo        | ThinkPad E420 1141D7G       | [f24dee8f72](https://linux-hardware.org/?probe=f24dee8f72) | Jul 24, 2020 |
| HP            | EliteBook 850 G5            | [56cf19c251](https://linux-hardware.org/?probe=56cf19c251) | Jul 18, 2020 |
| Dell          | Inspiron 5570               | [3d66bcb580](https://linux-hardware.org/?probe=3d66bcb580) | Jul 15, 2020 |
| HP            | EliteBook 840 G2            | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Dell          | Inspiron 1525               | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| Lenovo        | G555 0873                   | [6a79c9f57b](https://linux-hardware.org/?probe=6a79c9f57b) | Jun 26, 2020 |
| Dell          | Inspiron 5559               | [3b7aa38697](https://linux-hardware.org/?probe=3b7aa38697) | Jun 24, 2020 |
| Dell          | Inspiron 5559               | [bf6cda0ab3](https://linux-hardware.org/?probe=bf6cda0ab3) | Jun 24, 2020 |
| Lenovo        | Y50-70 20378                | [f9ef75ee84](https://linux-hardware.org/?probe=f9ef75ee84) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | [bd3ec8d031](https://linux-hardware.org/?probe=bd3ec8d031) | Jun 23, 2020 |
| Dell          | Inspiron 5559               | [bb181efab0](https://linux-hardware.org/?probe=bb181efab0) | Jun 22, 2020 |
| Dell          | Inspiron 5559               | [5cad704188](https://linux-hardware.org/?probe=5cad704188) | Jun 22, 2020 |
| Lenovo        | ThinkPad E480 20KN0082AD    | [f8743f8e7c](https://linux-hardware.org/?probe=f8743f8e7c) | Jun 03, 2020 |
| Acer          | Aspire 5253                 | [7951613e3c](https://linux-hardware.org/?probe=7951613e3c) | Jun 02, 2020 |
| Lenovo        | Z50-70 20354                | [474b3dc645](https://linux-hardware.org/?probe=474b3dc645) | Jun 01, 2020 |
| HP            | G60                         | [36393e3df7](https://linux-hardware.org/?probe=36393e3df7) | May 30, 2020 |
| Dell          | Latitude E5570              | [52fe4fa81d](https://linux-hardware.org/?probe=52fe4fa81d) | May 27, 2020 |
| Packard Be... | EasyNote TJ75               | [3e4f50b818](https://linux-hardware.org/?probe=3e4f50b818) | May 18, 2020 |
| Lenovo        | G555 0873                   | [80cd03a651](https://linux-hardware.org/?probe=80cd03a651) | May 17, 2020 |
| Lenovo        | G555 0873                   | [0c8aa224f6](https://linux-hardware.org/?probe=0c8aa224f6) | May 17, 2020 |
| Lenovo        | G50-70 20351                | [49f0886269](https://linux-hardware.org/?probe=49f0886269) | May 15, 2020 |
| Lenovo        | G50-70 20351                | [261ecd7cd3](https://linux-hardware.org/?probe=261ecd7cd3) | May 15, 2020 |
| HP            | Pavilion g4                 | [d72a853f70](https://linux-hardware.org/?probe=d72a853f70) | May 15, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [567c197788](https://linux-hardware.org/?probe=567c197788) | May 14, 2020 |
| HP            | ProBook 450 G1              | [d2f086da96](https://linux-hardware.org/?probe=d2f086da96) | May 13, 2020 |
| Dell          | G3 3579                     | [1391477c00](https://linux-hardware.org/?probe=1391477c00) | May 11, 2020 |
| Dell          | G3 3779                     | [8adf43a503](https://linux-hardware.org/?probe=8adf43a503) | May 05, 2020 |
| Dell          | Inspiron 3521               | [bdb886a73d](https://linux-hardware.org/?probe=bdb886a73d) | May 05, 2020 |
| HP            | Pavilion g4                 | [8dec145194](https://linux-hardware.org/?probe=8dec145194) | May 05, 2020 |
| Toshiba       | Satellite L850-A894         | [4cff22692a](https://linux-hardware.org/?probe=4cff22692a) | Apr 26, 2020 |
| Toshiba       | Satellite L850-A894         | [c6bd4ae874](https://linux-hardware.org/?probe=c6bd4ae874) | Apr 26, 2020 |
| Dell          | Inspiron 5583               | [73ad84a03c](https://linux-hardware.org/?probe=73ad84a03c) | Apr 22, 2020 |
| Dell          | G5 5587                     | [56485e9db4](https://linux-hardware.org/?probe=56485e9db4) | Apr 22, 2020 |
| Toshiba       | Satellite A300              | [cb33489db5](https://linux-hardware.org/?probe=cb33489db5) | Apr 18, 2020 |
| Toshiba       | Satellite A300              | [e39b380b81](https://linux-hardware.org/?probe=e39b380b81) | Apr 18, 2020 |
| Dell          | Inspiron 3543               | [165bdbdf8b](https://linux-hardware.org/?probe=165bdbdf8b) | Apr 09, 2020 |
| Acer          | Aspire E5-475G              | [a8a037650e](https://linux-hardware.org/?probe=a8a037650e) | Apr 05, 2020 |
| Toshiba       | Satellite C850D-B810        | [bfa7a5b4b3](https://linux-hardware.org/?probe=bfa7a5b4b3) | Apr 04, 2020 |
| Toshiba       | Satellite C850D-B810        | [d911f2bb34](https://linux-hardware.org/?probe=d911f2bb34) | Apr 04, 2020 |
| HP            | Pavilion dv6                | [5a16417e7b](https://linux-hardware.org/?probe=5a16417e7b) | Apr 04, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c6657af4bd](https://linux-hardware.org/?probe=c6657af4bd) | Mar 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [2645325565](https://linux-hardware.org/?probe=2645325565) | Mar 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [b90d909930](https://linux-hardware.org/?probe=b90d909930) | Mar 28, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [3aa7a0e126](https://linux-hardware.org/?probe=3aa7a0e126) | Mar 27, 2020 |
| HP            | Pavilion dv7                | [6f801c5209](https://linux-hardware.org/?probe=6f801c5209) | Mar 20, 2020 |
| Dell          | Inspiron 3593               | [f7f247e8c5](https://linux-hardware.org/?probe=f7f247e8c5) | Mar 19, 2020 |
| Lenovo        | ThinkPad SL410 0616A44      | [2c3f83610d](https://linux-hardware.org/?probe=2c3f83610d) | Mar 04, 2020 |
| Lenovo        | Y50-70 20378                | [d4389ea7a1](https://linux-hardware.org/?probe=d4389ea7a1) | Feb 23, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| Dell          | Inspiron N4050              | [9808803a9a](https://linux-hardware.org/?probe=9808803a9a) | Feb 07, 2020 |
| Dell          | Inspiron N4050              | [bd16699d67](https://linux-hardware.org/?probe=bd16699d67) | Feb 07, 2020 |
| Dell          | Inspiron 5570               | [101d794bd2](https://linux-hardware.org/?probe=101d794bd2) | Jan 30, 2020 |
| Dell          | Inspiron N5110              | [975cffd2a7](https://linux-hardware.org/?probe=975cffd2a7) | Jan 17, 2020 |
| Dell          | Inspiron N5110              | [d08a0ed65d](https://linux-hardware.org/?probe=d08a0ed65d) | Jan 16, 2020 |
| Lenovo        | ThinkPad E590 20NB0002AD    | [0fc61e3795](https://linux-hardware.org/?probe=0fc61e3795) | Jan 13, 2020 |
| HP            | EliteBook 745 G4            | [99937a33e7](https://linux-hardware.org/?probe=99937a33e7) | Jan 05, 2020 |
| ASUSTek       | X540UA                      | [714b86d8a5](https://linux-hardware.org/?probe=714b86d8a5) | Dec 31, 2019 |
| Dell          | Inspiron 5570               | [92a06ce5da](https://linux-hardware.org/?probe=92a06ce5da) | Dec 31, 2019 |
| HP            | Pavilion dv7                | [9091bfdcb2](https://linux-hardware.org/?probe=9091bfdcb2) | Dec 13, 2019 |
| Dell          | Inspiron 15-3567            | [ddc251a8e0](https://linux-hardware.org/?probe=ddc251a8e0) | Dec 07, 2019 |
| Dell          | Inspiron 3542               | [38da710325](https://linux-hardware.org/?probe=38da710325) | Dec 01, 2019 |
| Lenovo        | IdeaPad Z510 20287          | [19294a1943](https://linux-hardware.org/?probe=19294a1943) | Nov 29, 2019 |
| Dell          | Inspiron 15-3567            | [ba36a0ae04](https://linux-hardware.org/?probe=ba36a0ae04) | Nov 27, 2019 |
| Dell          | Inspiron 15-3567            | [a93aff23bf](https://linux-hardware.org/?probe=a93aff23bf) | Nov 24, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8f75febf6c](https://linux-hardware.org/?probe=8f75febf6c) | Nov 23, 2019 |
| HP            | Pavilion dv7                | [0261873b10](https://linux-hardware.org/?probe=0261873b10) | Nov 22, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [3054eabefb](https://linux-hardware.org/?probe=3054eabefb) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [62081db5d0](https://linux-hardware.org/?probe=62081db5d0) | Nov 20, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [6ed324d188](https://linux-hardware.org/?probe=6ed324d188) | Nov 20, 2019 |
| HP            | Pavilion dv7                | [ab5fc8d0ac](https://linux-hardware.org/?probe=ab5fc8d0ac) | Nov 15, 2019 |
| Dell          | Inspiron 3543               | [5d228450e9](https://linux-hardware.org/?probe=5d228450e9) | Nov 11, 2019 |
| HP            | Pavilion dv7                | [41305d675a](https://linux-hardware.org/?probe=41305d675a) | Nov 09, 2019 |
| HP            | Pavilion dv7                | [6031485dd2](https://linux-hardware.org/?probe=6031485dd2) | Nov 08, 2019 |
| Lenovo        | ThinkPad T420 4178CXG       | [70105ff0ab](https://linux-hardware.org/?probe=70105ff0ab) | Nov 03, 2019 |
| Lenovo        | ThinkPad L460 20FVS0ER00    | [713a72e731](https://linux-hardware.org/?probe=713a72e731) | Oct 31, 2019 |
| HP            | ProBook 450 G4              | [e11bd3882e](https://linux-hardware.org/?probe=e11bd3882e) | Oct 22, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [677874b570](https://linux-hardware.org/?probe=677874b570) | Oct 18, 2019 |
| HP            | ProBook 450 G2              | [d8532c559a](https://linux-hardware.org/?probe=d8532c559a) | Sep 18, 2019 |
| Dell          | Inspiron N5010              | [fb490db7bf](https://linux-hardware.org/?probe=fb490db7bf) | Sep 09, 2019 |
| Dell          | Inspiron N5010              | [993460ba08](https://linux-hardware.org/?probe=993460ba08) | Sep 09, 2019 |
| MSI           | GL62 7QF                    | [4d0dbc5874](https://linux-hardware.org/?probe=4d0dbc5874) | Aug 30, 2019 |
| MSI           | GL62 7QF                    | [e508053ff2](https://linux-hardware.org/?probe=e508053ff2) | Aug 29, 2019 |
| Dell          | G3 3579                     | [ddcae43a95](https://linux-hardware.org/?probe=ddcae43a95) | Aug 24, 2019 |
| Dell          | Latitude E6440              | [c9fc484b61](https://linux-hardware.org/?probe=c9fc484b61) | Aug 20, 2019 |
| Dell          | Latitude E6440              | [f153be7930](https://linux-hardware.org/?probe=f153be7930) | Aug 20, 2019 |
| HP            | Pavilion dv7                | [d2006e7a87](https://linux-hardware.org/?probe=d2006e7a87) | Jul 27, 2019 |
| Toshiba       | Satellite C850-B341         | [acd80fad4b](https://linux-hardware.org/?probe=acd80fad4b) | Jul 20, 2019 |
| Acer          | Aspire A315-21              | [ea1580c609](https://linux-hardware.org/?probe=ea1580c609) | Jul 01, 2019 |
| Dell          | Inspiron 5559               | [4cbf20a7cf](https://linux-hardware.org/?probe=4cbf20a7cf) | Jun 18, 2019 |
| Lenovo        | ThinkPad T410 2522N18       | [9ab11256e2](https://linux-hardware.org/?probe=9ab11256e2) | Jun 16, 2019 |
| Acer          | Aspire E5-576G              | [119e4e5705](https://linux-hardware.org/?probe=119e4e5705) | Jun 06, 2019 |
| Lenovo        | Yoga 300-11IBY 80M0         | [0d944086c2](https://linux-hardware.org/?probe=0d944086c2) | Jun 04, 2019 |
| HP            | Laptop 15-bs1xx             | [47b56cee05](https://linux-hardware.org/?probe=47b56cee05) | May 25, 2019 |
| HP            | EliteBook 840 G1            | [fb72c7a17e](https://linux-hardware.org/?probe=fb72c7a17e) | May 22, 2019 |
| HP            | EliteBook 840 G1            | [8cc7613eb4](https://linux-hardware.org/?probe=8cc7613eb4) | May 22, 2019 |
| Dell          | Inspiron 3576               | [e86a5c4340](https://linux-hardware.org/?probe=e86a5c4340) | Apr 12, 2019 |
| HP            | ProBook 450 G2              | [ed27c8b4b2](https://linux-hardware.org/?probe=ed27c8b4b2) | Feb 23, 2019 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d1e0440b23](https://linux-hardware.org/?probe=d1e0440b23) | Jan 30, 2019 |
| Dell          | Inspiron 7520               | [4362c41db3](https://linux-hardware.org/?probe=4362c41db3) | Nov 17, 2018 |
| Dell          | Inspiron 7520               | [461541bb3a](https://linux-hardware.org/?probe=461541bb3a) | Nov 17, 2018 |
| Dell          | Latitude E5470              | [f54e62ab63](https://linux-hardware.org/?probe=f54e62ab63) | Nov 11, 2018 |
| Dell          | Latitude E5470              | [496335b114](https://linux-hardware.org/?probe=496335b114) | Nov 10, 2018 |
| Dell          | Latitude E5470              | [3c869c46e5](https://linux-hardware.org/?probe=3c869c46e5) | Nov 08, 2018 |
| Toshiba       | Satellite L50-A661          | [fad34d33ee](https://linux-hardware.org/?probe=fad34d33ee) | Apr 22, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 59        | 17.05%  |
| Ubuntu 18.04       | 34        | 9.83%   |
| Ubuntu 22.04       | 31        | 8.96%   |
| Zorin 16           | 9         | 2.6%    |
| Ubuntu 19.10       | 9         | 2.6%    |
| OpenMandriva 4.3   | 8         | 2.31%   |
| Zorin 15           | 7         | 2.02%   |
| Ubuntu 20.10       | 7         | 2.02%   |
| ArcoLinux Rolling  | 7         | 2.02%   |
| Pop!_OS 22.04      | 6         | 1.73%   |
| Fedora 38          | 6         | 1.73%   |
| Fedora 36          | 6         | 1.73%   |
| Ubuntu 22.10       | 5         | 1.45%   |
| Pop!_OS 20.10      | 5         | 1.45%   |
| Ubuntu 21.10       | 4         | 1.16%   |
| Linux Mint 20.3    | 4         | 1.16%   |
| Linux Mint 19.3    | 4         | 1.16%   |
| Fedora 34          | 4         | 1.16%   |
| Arch               | 4         | 1.16%   |
| Ubuntu 23.04       | 3         | 0.87%   |
| Ubuntu 21.04       | 3         | 0.87%   |
| Pop!_OS 20.04      | 3         | 0.87%   |
| OpenMandriva 23.03 | 3         | 0.87%   |
| Manjaro            | 3         | 0.87%   |
| Linux Mint 21      | 3         | 0.87%   |
| Linux Mint 20.1    | 3         | 0.87%   |
| Linux Mint 19      | 3         | 0.87%   |
| Kubuntu 20.04      | 3         | 0.87%   |
| KDE neon 20.04     | 3         | 0.87%   |
| Fedora 37          | 3         | 0.87%   |
| Fedora 35          | 3         | 0.87%   |
| Fedora 33          | 3         | 0.87%   |
| Arch Rolling       | 3         | 0.87%   |
| Xero Rolling       | 2         | 0.58%   |
| Ubuntu Unity 16.04 | 2         | 0.58%   |
| Ubuntu 19.04       | 2         | 0.58%   |
| Ubuntu 18.10       | 2         | 0.58%   |
| Pop!_OS 21.04      | 2         | 0.58%   |
| OpenMandriva 4.2   | 2         | 0.58%   |
| Nobara 36          | 2         | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 157       | 46.87%  |
| Fedora        | 28        | 8.36%   |
| Linux Mint    | 21        | 6.27%   |
| Zorin         | 16        | 4.78%   |
| OpenMandriva  | 16        | 4.78%   |
| Pop!_OS       | 15        | 4.48%   |
| Manjaro       | 10        | 2.99%   |
| Kali          | 9         | 2.69%   |
| Endless       | 8         | 2.39%   |
| ArcoLinux     | 7         | 2.09%   |
| Arch          | 7         | 2.09%   |
| Debian        | 5         | 1.49%   |
| Kubuntu       | 4         | 1.19%   |
| KDE neon      | 4         | 1.19%   |
| ROSA          | 3         | 0.9%    |
| Xero          | 2         | 0.6%    |
| Ubuntu Unity  | 2         | 0.6%    |
| Parrot        | 2         | 0.6%    |
| Nobara        | 2         | 0.6%    |
| MX            | 2         | 0.6%    |
| Lubuntu       | 2         | 0.6%    |
| Clear Linux   | 2         | 0.6%    |
| ALT Linux     | 2         | 0.6%    |
| Xubuntu       | 1         | 0.3%    |
| Ubuntu Budgie | 1         | 0.3%    |
| RHEL          | 1         | 0.3%    |
| LMDE          | 1         | 0.3%    |
| EndeavourOS   | 1         | 0.3%    |
| Elementary    | 1         | 0.3%    |
| CentOS        | 1         | 0.3%    |
| BlackPanther  | 1         | 0.3%    |
| Alpine        | 1         | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.4.0-42-generic        | 13        | 3.52%   |
| 5.16.7-desktop-1omv4003 | 7         | 1.9%    |
| 5.4.0-58-generic        | 6         | 1.63%   |
| 5.15.0-47-generic       | 5         | 1.36%   |
| 6.2.6-desktop-1omv2390  | 4         | 1.08%   |
| 5.8.0-7630-generic      | 4         | 1.08%   |
| 5.8.0-48-generic        | 4         | 1.08%   |
| 5.4.0-48-generic        | 4         | 1.08%   |
| 5.4.0-29-generic        | 4         | 1.08%   |
| 5.19.0-76051900-generic | 4         | 1.08%   |
| 5.19.0-38-generic       | 4         | 1.08%   |
| 5.0.0-32-generic        | 4         | 1.08%   |
| 5.8.0-43-generic        | 3         | 0.81%   |
| 5.8.0-41-generic        | 3         | 0.81%   |
| 5.4.0-56-generic        | 3         | 0.81%   |
| 5.3.0-51-generic        | 3         | 0.81%   |
| 5.3.0-18-generic        | 3         | 0.81%   |
| 5.19.0-41-generic       | 3         | 0.81%   |
| 5.15.0-56-generic       | 3         | 0.81%   |
| 5.15.0-52-generic       | 3         | 0.81%   |
| 5.15.0-50-generic       | 3         | 0.81%   |
| 5.15.0-48-generic       | 3         | 0.81%   |
| 5.15.0-40-generic       | 3         | 0.81%   |
| 5.13.0-30-generic       | 3         | 0.81%   |
| 5.11.0-38-generic       | 3         | 0.81%   |
| 5.11.0-37-generic       | 3         | 0.81%   |
| 5.11.0-35-generic       | 3         | 0.81%   |
| 6.0.10-201.fc36.x86_64  | 2         | 0.54%   |
| 5.4.0-80-generic        | 2         | 0.54%   |
| 5.4.0-59-generic        | 2         | 0.54%   |
| 5.4.0-54-generic        | 2         | 0.54%   |
| 5.4.0-53-generic        | 2         | 0.54%   |
| 5.4.0-52-generic        | 2         | 0.54%   |
| 5.4.0-40-generic        | 2         | 0.54%   |
| 5.4.0-100-generic       | 2         | 0.54%   |
| 5.3.0-46-generic        | 2         | 0.54%   |
| 5.3.0-45-generic        | 2         | 0.54%   |
| 5.3.0-42-generic        | 2         | 0.54%   |
| 5.3.0-26-generic        | 2         | 0.54%   |
| 5.3.0-23-generic        | 2         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 58        | 16.48%  |
| 5.15.0  | 38        | 10.8%   |
| 5.3.0   | 24        | 6.82%   |
| 5.8.0   | 23        | 6.53%   |
| 5.19.0  | 19        | 5.4%    |
| 4.15.0  | 19        | 5.4%    |
| 5.13.0  | 14        | 3.98%   |
| 5.0.0   | 14        | 3.98%   |
| 5.11.0  | 13        | 3.69%   |
| 5.10.0  | 8         | 2.27%   |
| 4.18.0  | 8         | 2.27%   |
| 5.16.7  | 7         | 1.99%   |
| 6.2.6   | 5         | 1.42%   |
| 6.0.0   | 3         | 0.85%   |
| 5.17.5  | 3         | 0.85%   |
| 6.2.11  | 2         | 0.57%   |
| 6.2.0   | 2         | 0.57%   |
| 6.0.10  | 2         | 0.57%   |
| 5.18.17 | 2         | 0.57%   |
| 5.18.0  | 2         | 0.57%   |
| 5.17.1  | 2         | 0.57%   |
| 5.16.0  | 2         | 0.57%   |
| 5.14.0  | 2         | 0.57%   |
| 5.10.19 | 2         | 0.57%   |
| 5.10.14 | 2         | 0.57%   |
| 4.19.0  | 2         | 0.57%   |
| 6.4.8   | 1         | 0.28%   |
| 6.4.6   | 1         | 0.28%   |
| 6.4.3   | 1         | 0.28%   |
| 6.3.6   | 1         | 0.28%   |
| 6.3.5   | 1         | 0.28%   |
| 6.3.4   | 1         | 0.28%   |
| 6.3.12  | 1         | 0.28%   |
| 6.3.0   | 1         | 0.28%   |
| 6.2.9   | 1         | 0.28%   |
| 6.2.8   | 1         | 0.28%   |
| 6.2.16  | 1         | 0.28%   |
| 6.2.14  | 1         | 0.28%   |
| 6.1.5   | 1         | 0.28%   |
| 6.1.4   | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 63        | 18.21%  |
| 5.15    | 44        | 12.72%  |
| 5.8     | 26        | 7.51%   |
| 5.3     | 26        | 7.51%   |
| 5.19    | 22        | 6.36%   |
| 4.15    | 19        | 5.49%   |
| 5.10    | 18        | 5.2%    |
| 5.13    | 15        | 4.34%   |
| 5.11    | 15        | 4.34%   |
| 5.16    | 14        | 4.05%   |
| 5.0     | 14        | 4.05%   |
| 6.2     | 13        | 3.76%   |
| 4.18    | 9         | 2.6%    |
| 6.0     | 8         | 2.31%   |
| 5.17    | 7         | 2.02%   |
| 5.18    | 6         | 1.73%   |
| 6.3     | 5         | 1.45%   |
| 6.1     | 4         | 1.16%   |
| 6.4     | 3         | 0.87%   |
| 5.14    | 3         | 0.87%   |
| 5.12    | 3         | 0.87%   |
| 5.6     | 2         | 0.58%   |
| 4.19    | 2         | 0.58%   |
| 5.9     | 1         | 0.29%   |
| 5.7     | 1         | 0.29%   |
| 5.5     | 1         | 0.29%   |
| 4.9     | 1         | 0.29%   |
| 4.16    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 318       | 98.76%  |
| i686   | 4         | 1.24%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 202       | 60.48%  |
| Unknown       | 36        | 10.78%  |
| KDE5          | 35        | 10.48%  |
| XFCE          | 26        | 7.78%   |
| X-Cinnamon    | 18        | 5.39%   |
| MATE          | 4         | 1.2%    |
| Unity         | 2         | 0.6%    |
| KDE4          | 2         | 0.6%    |
| Cinnamon      | 2         | 0.6%    |
| qtile         | 1         | 0.3%    |
| LXQt          | 1         | 0.3%    |
| LXDE          | 1         | 0.3%    |
| KDE           | 1         | 0.3%    |
| i3            | 1         | 0.3%    |
| Enlightenment | 1         | 0.3%    |
| Budgie        | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 246       | 73.87%  |
| Wayland | 61        | 18.32%  |
| Unknown | 22        | 6.61%   |
| Tty     | 4         | 1.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 183       | 55.62%  |
| GDM3    | 46        | 13.98%  |
| GDM     | 41        | 12.46%  |
| SDDM    | 32        | 9.73%   |
| LightDM | 18        | 5.47%   |
| TDM     | 6         | 1.82%   |
| KDM     | 2         | 0.61%   |
| LY-DM   | 1         | 0.3%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 269       | 82.01%  |
| Unknown | 31        | 9.45%   |
| en_GB   | 18        | 5.49%   |
| ar_EG   | 4         | 1.22%   |
| C       | 3         | 0.91%   |
| ru_RU   | 2         | 0.61%   |
| de_DE   | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 177       | 53.96%  |
| EFI  | 151       | 46.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 263       | 80.67%  |
| Btrfs   | 24        | 7.36%   |
| Overlay | 15        | 4.6%    |
| Unknown | 11        | 3.37%   |
| Tmpfs   | 6         | 1.84%   |
| Xfs     | 4         | 1.23%   |
| Ext3    | 2         | 0.61%   |
| Ext2    | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 198       | 61.11%  |
| GPT     | 100       | 30.86%  |
| MBR     | 26        | 8.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 287       | 87.5%   |
| Yes       | 41        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 182       | 55.66%  |
| Yes       | 145       | 44.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 94        | 29.19%  |
| Dell                        | 86        | 26.71%  |
| Lenovo                      | 79        | 24.53%  |
| ASUSTek Computer            | 22        | 6.83%   |
| Toshiba                     | 8         | 2.48%   |
| Acer                        | 6         | 1.86%   |
| MSI                         | 4         | 1.24%   |
| Sony                        | 3         | 0.93%   |
| Samsung Electronics         | 3         | 0.93%   |
| Hampoo                      | 3         | 0.93%   |
| Packard Bell                | 2         | 0.62%   |
| Fujitsu Siemens             | 2         | 0.62%   |
| Fujitsu                     | 2         | 0.62%   |
| Apple                       | 2         | 0.62%   |
| TECNO                       | 1         | 0.31%   |
| Razer                       | 1         | 0.31%   |
| Panasonic                   | 1         | 0.31%   |
| I-Life Digital Technologies | 1         | 0.31%   |
| HUAWEI                      | 1         | 0.31%   |
| Alienware                   | 1         | 0.31%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Lenovo IdeaPad 520-15IKB 81BF         | 7         | 2.17%   |
| Dell Inspiron 5570                    | 6         | 1.86%   |
| HP Notebook                           | 5         | 1.55%   |
| Dell G3 3579                          | 5         | 1.55%   |
| Lenovo IdeaPad 330-15AST 81D6         | 4         | 1.24%   |
| HP ProBook 450 G7                     | 4         | 1.24%   |
| Dell Inspiron 7577                    | 4         | 1.24%   |
| Dell G5 5587                          | 4         | 1.24%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 3         | 0.93%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 3         | 0.93%   |
| HP ProBook 645 G1                     | 3         | 0.93%   |
| HP Pavilion dv6                       | 3         | 0.93%   |
| HP Pavilion 15                        | 3         | 0.93%   |
| HP Laptop 15-da1xxx                   | 3         | 0.93%   |
| HP Laptop 15-bs0xx                    | 3         | 0.93%   |
| HP EliteBook 745 G3                   | 3         | 0.93%   |
| HP 15                                 | 3         | 0.93%   |
| Hampoo Cherry Trail CR                | 3         | 0.93%   |
| Dell Inspiron N5110                   | 3         | 0.93%   |
| Dell Inspiron 3593                    | 3         | 0.93%   |
| Dell Inspiron 3521                    | 3         | 0.93%   |
| Dell G15 5510                         | 3         | 0.93%   |
| Unknown                               | 3         | 0.93%   |
| Lenovo Z50-70 20354                   | 2         | 0.62%   |
| Lenovo Y50-70 20378                   | 2         | 0.62%   |
| Lenovo Legion 5 15IMH05H 81Y6         | 2         | 0.62%   |
| Lenovo IdeaPad 310-15IKB 80TV         | 2         | 0.62%   |
| Lenovo G555 0873                      | 2         | 0.62%   |
| HP ZBook 15 G2                        | 2         | 0.62%   |
| HP ProBook 450 G2                     | 2         | 0.62%   |
| HP Pavilion g6                        | 2         | 0.62%   |
| HP Pavilion g4                        | 2         | 0.62%   |
| HP Pavilion dv7                       | 2         | 0.62%   |
| HP EliteBook 8440p                    | 2         | 0.62%   |
| HP EliteBook 840 G1                   | 2         | 0.62%   |
| Dell Vostro 15 3515                   | 2         | 0.62%   |
| Dell Latitude E5570                   | 2         | 0.62%   |
| Dell Latitude 5580                    | 2         | 0.62%   |
| Dell Latitude 5420                    | 2         | 0.62%   |
| Dell Inspiron N5010                   | 2         | 0.62%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 43        | 13.35%  |
| Lenovo IdeaPad        | 34        | 10.56%  |
| Dell Latitude         | 22        | 6.83%   |
| HP EliteBook          | 21        | 6.52%   |
| HP ProBook            | 19        | 5.9%    |
| Lenovo ThinkPad       | 17        | 5.28%   |
| HP Pavilion           | 15        | 4.66%   |
| HP Laptop             | 10        | 3.11%   |
| Dell G3               | 8         | 2.48%   |
| ASUS VivoBook         | 8         | 2.48%   |
| Toshiba Satellite     | 7         | 2.17%   |
| Lenovo Legion         | 6         | 1.86%   |
| HP Notebook           | 5         | 1.55%   |
| Dell G5               | 5         | 1.55%   |
| Acer Aspire           | 5         | 1.55%   |
| HP ZBook              | 4         | 1.24%   |
| HP Compaq             | 4         | 1.24%   |
| Dell G15              | 4         | 1.24%   |
| Lenovo Yoga           | 3         | 0.93%   |
| HP 250                | 3         | 0.93%   |
| HP 15                 | 3         | 0.93%   |
| Hampoo Cherry         | 3         | 0.93%   |
| Unknown               | 3         | 0.93%   |
| Packard Bell EasyNote | 2         | 0.62%   |
| Lenovo Z50-70         | 2         | 0.62%   |
| Lenovo Y50-70         | 2         | 0.62%   |
| Lenovo G555           | 2         | 0.62%   |
| HP ENVY               | 2         | 0.62%   |
| Dell Vostro           | 2         | 0.62%   |
| ASUS ROG              | 2         | 0.62%   |
| ASUS ASUS             | 2         | 0.62%   |
| Toshiba NB250         | 1         | 0.31%   |
| TECNO WinPad          | 1         | 0.31%   |
| Sony VPCEH3LFX        | 1         | 0.31%   |
| Sony SVT1121B2EW      | 1         | 0.31%   |
| Sony SVF15328CXB      | 1         | 0.31%   |
| Samsung Lumpy         | 1         | 0.31%   |
| Samsung 300E5EV       | 1         | 0.31%   |
| Samsung 275E4E        | 1         | 0.31%   |
| Razer Blade           | 1         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 43        | 13.35%  |
| 2017 | 37        | 11.49%  |
| 2014 | 27        | 8.39%   |
| 2019 | 26        | 8.07%   |
| 2016 | 25        | 7.76%   |
| 2015 | 25        | 7.76%   |
| 2013 | 25        | 7.76%   |
| 2011 | 20        | 6.21%   |
| 2020 | 19        | 5.9%    |
| 2012 | 19        | 5.9%    |
| 2010 | 15        | 4.66%   |
| 2021 | 14        | 4.35%   |
| 2008 | 12        | 3.73%   |
| 2009 | 7         | 2.17%   |
| 2022 | 4         | 1.24%   |
| 2007 | 3         | 0.93%   |
| 2023 | 1         | 0.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 322       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 303       | 94.1%   |
| Enabled  | 19        | 5.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 321       | 99.69%  |
| Yes  | 1         | 0.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 102       | 31.58%  |
| 16.01-24.0  | 73        | 22.6%   |
| 3.01-4.0    | 65        | 20.12%  |
| 8.01-16.0   | 46        | 14.24%  |
| 1.01-2.0    | 15        | 4.64%   |
| 2.01-3.0    | 8         | 2.48%   |
| 32.01-64.0  | 6         | 1.86%   |
| 24.01-32.0  | 6         | 1.86%   |
| 64.01-256.0 | 1         | 0.31%   |
| 0.51-1.0    | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 116       | 32.86%  |
| 1.01-2.0   | 111       | 31.44%  |
| 3.01-4.0   | 58        | 16.43%  |
| 4.01-8.0   | 53        | 15.01%  |
| 0.51-1.0   | 8         | 2.27%   |
| 8.01-16.0  | 4         | 1.13%   |
| 16.01-24.0 | 2         | 0.57%   |
| 0.01-0.5   | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 201       | 60.73%  |
| 2      | 121       | 36.56%  |
| 3      | 8         | 2.42%   |
| 4      | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 187       | 57.72%  |
| Yes       | 137       | 42.28%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 288       | 89.44%  |
| No        | 34        | 10.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 318       | 98.76%  |
| No        | 4         | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 82.52%  |
| No        | 57        | 17.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Egypt   | 322       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Cairo            | 191       | 54.73%  |
| Alexandria       | 36        | 10.32%  |
| Giza             | 28        | 8.02%   |
| Al Mansurah      | 11        | 3.15%   |
| Tanta            | 9         | 2.58%   |
| Hurghada         | 4         | 1.15%   |
| Awsim            | 4         | 1.15%   |
| Assiut           | 4         | 1.15%   |
| Zagazig          | 3         | 0.86%   |
| Ismailia         | 3         | 0.86%   |
| Helwan           | 3         | 0.86%   |
| Damanhur         | 3         | 0.86%   |
| Aswan            | 3         | 0.86%   |
| Suez             | 2         | 0.57%   |
| Sohag            | 2         | 0.57%   |
| New Cairo        | 2         | 0.57%   |
| Minya            | 2         | 0.57%   |
| Madinat as Sadat | 2         | 0.57%   |
| Edfu             | 2         | 0.57%   |
| Damietta         | 2         | 0.57%   |
| Bani Suwayf      | 2         | 0.57%   |
| Banha            | 2         | 0.57%   |
| Al Fayyum        | 2         | 0.57%   |
| Zefta            | 1         | 0.29%   |
| Tukh             | 1         | 0.29%   |
| Talkha           | 1         | 0.29%   |
| Smouha           | 1         | 0.29%   |
| Shirbin          | 1         | 0.29%   |
| Sharqia          | 1         | 0.29%   |
| Port Said        | 1         | 0.29%   |
| Monufia          | 1         | 0.29%   |
| Mit Salsil       | 1         | 0.29%   |
| Mashtul as Suq   | 1         | 0.29%   |
| Madinat an Nasr  | 1         | 0.29%   |
| Luxor            | 1         | 0.29%   |
| Kirdasah         | 1         | 0.29%   |
| Kafr Shukr       | 1         | 0.29%   |
| Heliopolis       | 1         | 0.29%   |
| Fuwwah           | 1         | 0.29%   |
| Fāraskūr       | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 88        | 103    | 20.23%  |
| WDC                            | 73        | 92     | 16.78%  |
| Toshiba                        | 63        | 80     | 14.48%  |
| Samsung Electronics            | 37        | 49     | 8.51%   |
| Kingston                       | 22        | 25     | 5.06%   |
| Unknown                        | 19        | 24     | 4.37%   |
| Crucial                        | 16        | 18     | 3.68%   |
| Hitachi                        | 15        | 19     | 3.45%   |
| SK hynix                       | 12        | 13     | 2.76%   |
| Micron Technology              | 12        | 14     | 2.76%   |
| SanDisk                        | 11        | 12     | 2.53%   |
| HGST                           | 11        | 11     | 2.53%   |
| HS-SSD-C100                    | 8         | 11     | 1.84%   |
| Intel                          | 6         | 6      | 1.38%   |
| TwinMOS                        | 3         | 5      | 0.69%   |
| Micron/Crucial Technology      | 3         | 3      | 0.69%   |
| LITEONIT                       | 3         | 4      | 0.69%   |
| LITEON                         | 3         | 5      | 0.69%   |
| KIOXIA                         | 3         | 4      | 0.69%   |
| Transcend                      | 2         | 2      | 0.46%   |
| Kingston Technology Company    | 2         | 2      | 0.46%   |
| KingSpec                       | 2         | 2      | 0.46%   |
| HS-SSD-E100                    | 2         | 2      | 0.46%   |
| China                          | 2         | 2      | 0.46%   |
| Apple                          | 2         | 2      | 0.46%   |
| A-DATA Technology              | 2         | 2      | 0.46%   |
| Value                          | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.23%   |
| UMIS                           | 1         | 1      | 0.23%   |
| Team                           | 1         | 1      | 0.23%   |
| Solid State Storage Technology | 1         | 1      | 0.23%   |
| Silicon Motion                 | 1         | 1      | 0.23%   |
| Phison Electronics             | 1         | 1      | 0.23%   |
| Phison                         | 1         | 1      | 0.23%   |
| Maxtor                         | 1         | 1      | 0.23%   |
| Lexar                          | 1         | 1      | 0.23%   |
| JMicron Technology             | 1         | 1      | 0.23%   |
| HUAWEI                         | 1         | 1      | 0.23%   |
| ADATA Technology               | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 41        | 9.23%   |
| Toshiba MQ04ABF100 1TB                              | 13        | 2.93%   |
| Toshiba MQ01ABD100 1TB                              | 12        | 2.7%    |
| Seagate ST2000LM007-1R8174 2TB                      | 10        | 2.25%   |
| Kingston SA400S37240G 240GB SSD                     | 7         | 1.58%   |
| Seagate ST500LT012-1DG142 500GB                     | 6         | 1.35%   |
| Samsung NVMe SSD Drive 256GB                        | 6         | 1.35%   |
| Kingston SA400S37480G 480GB SSD                     | 6         | 1.35%   |
| WDC WD10SPZX-24Z10 1TB                              | 5         | 1.13%   |
| Crucial CT480BX500SSD1 480GB                        | 5         | 1.13%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 4         | 0.9%    |
| WDC WD10JPVX-60JC3T1 1TB                            | 4         | 0.9%    |
| WDC WD10JPCX-24UE4T0 1TB                            | 4         | 0.9%    |
| Unknown MMC Card  64GB                              | 4         | 0.9%    |
| Unknown MMC Card  32GB                              | 4         | 0.9%    |
| Toshiba MQ01ABF050 500GB                            | 4         | 0.9%    |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 4         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 4         | 0.9%    |
| Hitachi HTS547575A9E384 752GB                       | 4         | 0.9%    |
| HGST HTS545050A7E680 500GB                          | 4         | 0.9%    |
| WDC WD10SPZX-75Z10T1 1TB                            | 3         | 0.68%   |
| Unknown SD/MMC/MS PRO 128GB                         | 3         | 0.68%   |
| Toshiba MQ01ACF032 320GB                            | 3         | 0.68%   |
| Toshiba MK3276GSX 320GB                             | 3         | 0.68%   |
| Toshiba MK3275GSX 320GB                             | 3         | 0.68%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 3         | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 3         | 0.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.68%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                 | 3         | 0.68%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 0.68%   |
| HS-SSD-C100 SSD 240G                                | 3         | 0.68%   |
| HS-SSD-C100 120G                                    | 3         | 0.68%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 0.68%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2         | 0.45%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 2         | 0.45%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 2         | 0.45%   |
| WDC WD3200BPVT-75JJ5T0 320GB                        | 2         | 0.45%   |
| WDC WD1600BEVT-24A23T0 160GB                        | 2         | 0.45%   |
| WDC WD10SPZX-75Z10T3 1TB                            | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 88        | 103    | 36.82%  |
| WDC                 | 64        | 83     | 26.78%  |
| Toshiba             | 55        | 69     | 23.01%  |
| Hitachi             | 15        | 19     | 6.28%   |
| HGST                | 11        | 11     | 4.6%    |
| Unknown             | 3         | 3      | 1.26%   |
| Samsung Electronics | 1         | 2      | 0.42%   |
| JMicron Technology  | 1         | 1      | 0.42%   |
| Apple               | 1         | 1      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 19        | 22     | 18.27%  |
| Samsung Electronics | 16        | 18     | 15.38%  |
| Crucial             | 14        | 16     | 13.46%  |
| SanDisk             | 8         | 9      | 7.69%   |
| Micron Technology   | 6         | 6      | 5.77%   |
| WDC                 | 5         | 5      | 4.81%   |
| Toshiba             | 4         | 6      | 3.85%   |
| SK hynix            | 4         | 4      | 3.85%   |
| Intel               | 4         | 4      | 3.85%   |
| TwinMOS             | 3         | 5      | 2.88%   |
| LITEONIT            | 3         | 4      | 2.88%   |
| LITEON              | 3         | 5      | 2.88%   |
| HS-SSD-C100         | 3         | 4      | 2.88%   |
| Transcend           | 2         | 2      | 1.92%   |
| KingSpec            | 2         | 2      | 1.92%   |
| China               | 2         | 2      | 1.92%   |
| Value               | 1         | 1      | 0.96%   |
| Team                | 1         | 1      | 0.96%   |
| Maxtor              | 1         | 1      | 0.96%   |
| Lexar               | 1         | 1      | 0.96%   |
| Apple               | 1         | 1      | 0.96%   |
| A-DATA Technology   | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 231       | 292    | 54.61%  |
| SSD     | 99        | 120    | 23.4%   |
| NVMe    | 69        | 84     | 16.31%  |
| MMC     | 14        | 18     | 3.31%   |
| Unknown | 10        | 11     | 2.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 281       | 416    | 75.95%  |
| NVMe | 69        | 84     | 18.65%  |
| MMC  | 14        | 18     | 3.78%   |
| SAS  | 6         | 7      | 1.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 170       | 222    | 52.31%  |
| 0.51-1.0   | 139       | 174    | 42.77%  |
| 1.01-2.0   | 15        | 15     | 4.62%   |
| 3.01-4.0   | 1         | 1      | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 97        | 28.78%  |
| 251-500        | 74        | 21.96%  |
| 501-1000       | 50        | 14.84%  |
| 51-100         | 41        | 12.17%  |
| 1001-2000      | 29        | 8.61%   |
| 21-50          | 21        | 6.23%   |
| 1-20           | 17        | 5.04%   |
| Unknown        | 4         | 1.19%   |
| More than 3000 | 3         | 0.89%   |
| 2001-3000      | 1         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 125       | 35.82%  |
| 21-50          | 80        | 22.92%  |
| 101-250        | 53        | 15.19%  |
| 51-100         | 43        | 12.32%  |
| 501-1000       | 19        | 5.44%   |
| 251-500        | 18        | 5.16%   |
| 1001-2000      | 4         | 1.15%   |
| Unknown        | 4         | 1.15%   |
| 2001-3000      | 2         | 0.57%   |
| More than 3000 | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 4      | 9.68%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 3.23%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 1      | 3.23%   |
| WDC WD5000BPVT-24HXZT3 500GB                        | 1         | 1      | 3.23%   |
| WDC WD3200BUDT-63DPZY0 320GB                        | 1         | 1      | 3.23%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 2      | 3.23%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 1      | 3.23%   |
| TwinMOS SSD 128GB                                   | 1         | 1      | 3.23%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 1      | 3.23%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 3.23%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 3.23%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 3.23%   |
| Seagate ST95005620AS 500GB                          | 1         | 2      | 3.23%   |
| Seagate ST9320328CS 320GB                           | 1         | 2      | 3.23%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 3.23%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 3.23%   |
| Seagate ST2000LM015-2E81 2TB                        | 1         | 1      | 3.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 3.23%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 3.23%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 1      | 3.23%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 3.23%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 3.23%   |
| Hitachi HTS723225L9A360 250GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS545032B9SA02 320GB                       | 1         | 1      | 3.23%   |
| Hitachi HTS543225L9A300 250GB                       | 1         | 1      | 3.23%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 3.23%   |
| Apple HDD HTS547550A9E384 500GB                     | 1         | 1      | 3.23%   |
| A-DATA Technology IM2P33F3 NVMe 256GB               | 1         | 1      | 3.23%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 12     | 29.03%  |
| WDC                 | 6         | 7      | 19.35%  |
| Hitachi             | 4         | 4      | 12.9%   |
| Toshiba             | 3         | 3      | 9.68%   |
| Micron Technology   | 2         | 2      | 6.45%   |
| TwinMOS             | 1         | 1      | 3.23%   |
| SK hynix            | 1         | 1      | 3.23%   |
| Samsung Electronics | 1         | 1      | 3.23%   |
| Intel               | 1         | 1      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |
| Apple               | 1         | 1      | 3.23%   |
| A-DATA Technology   | 1         | 1      | 3.23%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 12     | 39.13%  |
| WDC     | 6         | 7      | 26.09%  |
| Hitachi | 4         | 4      | 17.39%  |
| Toshiba | 2         | 2      | 8.7%    |
| HGST    | 1         | 1      | 4.35%   |
| Apple   | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 27     | 74.19%  |
| SSD  | 7         | 7      | 22.58%  |
| NVMe | 1         | 1      | 3.23%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 217       | 354    | 64.39%  |
| Works    | 89        | 136    | 26.41%  |
| Malfunc  | 31        | 35     | 9.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 261       | 70.16%  |
| AMD                            | 36        | 9.68%   |
| Samsung Electronics            | 24        | 6.45%   |
| SK hynix                       | 8         | 2.15%   |
| SanDisk                        | 7         | 1.88%   |
| Toshiba America Info Systems   | 6         | 1.61%   |
| Micron Technology              | 6         | 1.61%   |
| Micron/Crucial Technology      | 5         | 1.34%   |
| Kingston Technology Company    | 5         | 1.34%   |
| KIOXIA                         | 3         | 0.81%   |
| Union Memory (Shenzhen)        | 2         | 0.54%   |
| Phison Electronics             | 2         | 0.54%   |
| ADATA Technology               | 2         | 0.54%   |
| VIA Technologies               | 1         | 0.27%   |
| Solid State Storage Technology | 1         | 0.27%   |
| Silicon Motion                 | 1         | 0.27%   |
| Shenzhen Longsys Electronics   | 1         | 0.27%   |
| Nvidia                         | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 46        | 11.89%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 31        | 8.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 22        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 21        | 5.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 5.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 19        | 4.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 18        | 4.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 17        | 4.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 15        | 3.88%   |
| Intel Comet Lake SATA AHCI Controller                                            | 9         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 2.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 2.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 2.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.81%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 1.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 1.55%   |
| Samsung NVMe SSD Controller 980                                                  | 5         | 1.29%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 5         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.29%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.29%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 4         | 1.03%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 1.03%   |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.03%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 0.78%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 3         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 0.78%   |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.52%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.52%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile       | 2         | 0.52%   |
| AMD FCH SATA Controller [IDE mode]                                               | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 268       | 70.71%  |
| NVMe | 71        | 18.73%  |
| RAID | 25        | 6.6%    |
| IDE  | 15        | 3.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 282       | 87.58%  |
| AMD    | 40        | 12.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz            | 16        | 4.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 12        | 3.73%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz           | 8         | 2.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 7         | 2.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 7         | 2.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz            | 6         | 1.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz            | 6         | 1.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 5         | 1.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 5         | 1.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz           | 5         | 1.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 5         | 1.55%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 4         | 1.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 4         | 1.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 4         | 1.24%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 4         | 1.24%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 4         | 1.24%   |
| Intel Core i5-2430M CPU @ 2.40GHz            | 4         | 1.24%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 4         | 1.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 4         | 1.24%   |
| Intel Core i7-5500U CPU @ 2.40GHz            | 3         | 0.93%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz           | 3         | 0.93%   |
| Intel Core i7-2630QM CPU @ 2.00GHz           | 3         | 0.93%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 3         | 0.93%   |
| Intel Core i5-7300U CPU @ 2.60GHz            | 3         | 0.93%   |
| Intel Core i5-5300U CPU @ 2.30GHz            | 3         | 0.93%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 3         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 3         | 0.93%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 3         | 0.93%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 3         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 0.93%   |
| Intel Core i3-5005U CPU @ 2.00GHz            | 3         | 0.93%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 3         | 0.93%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 3         | 0.93%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 3         | 0.93%   |
| AMD PRO A10-8700B R6, 10 Compute Cores 4C+6G | 3         | 0.93%   |
| AMD E2-9000 RADEON R2, 4 COMPUTE CORES 2C+2G | 3         | 0.93%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G | 3         | 0.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz           | 2         | 0.62%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 0.62%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz           | 2         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 112       | 34.78%  |
| Intel Core i5           | 87        | 27.02%  |
| Intel Core i3           | 31        | 9.63%   |
| Other                   | 16        | 4.97%   |
| Intel Core 2 Duo        | 12        | 3.73%   |
| Intel Celeron           | 10        | 3.11%   |
| Intel Atom              | 6         | 1.86%   |
| AMD Ryzen 7             | 6         | 1.86%   |
| AMD E2                  | 6         | 1.86%   |
| AMD A6                  | 5         | 1.55%   |
| Intel Pentium           | 4         | 1.24%   |
| AMD PRO A10             | 4         | 1.24%   |
| AMD Ryzen 5             | 3         | 0.93%   |
| AMD A8                  | 3         | 0.93%   |
| AMD A4                  | 3         | 0.93%   |
| Intel Pentium Dual-Core | 2         | 0.62%   |
| AMD E1                  | 2         | 0.62%   |
| AMD Athlon II Dual-Core | 2         | 0.62%   |
| Intel Genuine           | 1         | 0.31%   |
| Intel Core M            | 1         | 0.31%   |
| Intel Core i9           | 1         | 0.31%   |
| Intel Celeron Dual-Core | 1         | 0.31%   |
| AMD Ryzen 9             | 1         | 0.31%   |
| AMD Ryzen 7 PRO         | 1         | 0.31%   |
| AMD E                   | 1         | 0.31%   |
| AMD A10                 | 1         | 0.31%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 180       | 55.9%   |
| 4      | 100       | 31.06%  |
| 6      | 27        | 8.39%   |
| 8      | 8         | 2.48%   |
| 1      | 4         | 1.24%   |
| 24     | 1         | 0.31%   |
| 12     | 1         | 0.31%   |
| 10     | 1         | 0.31%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 322       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 263       | 81.68%  |
| 1      | 59        | 18.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 315       | 97.52%  |
| Unknown        | 7         | 2.17%   |
| 32-bit         | 1         | 0.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 27.33%  |
| 0x206a7    | 21        | 6.31%   |
| 0x806ea    | 17        | 5.11%   |
| 0x40651    | 17        | 5.11%   |
| 0x306d4    | 15        | 4.5%    |
| 0x306a9    | 15        | 4.5%    |
| 0x806e9    | 14        | 4.2%    |
| 0x306c3    | 14        | 4.2%    |
| 0x906ea    | 13        | 3.9%    |
| 0x806ec    | 11        | 3.3%    |
| 0x406e3    | 9         | 2.7%    |
| 0x906e9    | 8         | 2.4%    |
| 0xa0652    | 6         | 1.8%    |
| 0x1067a    | 6         | 1.8%    |
| 0x806c1    | 5         | 1.5%    |
| 0x6fd      | 5         | 1.5%    |
| 0x30678    | 5         | 1.5%    |
| 0x20655    | 5         | 1.5%    |
| 0x706e5    | 4         | 1.2%    |
| 0x406c3    | 4         | 1.2%    |
| 0x06006705 | 4         | 1.2%    |
| 0x06006704 | 4         | 1.2%    |
| 0x806eb    | 3         | 0.9%    |
| 0x20652    | 3         | 0.9%    |
| 0x0600111f | 3         | 0.9%    |
| 0x506e3    | 2         | 0.6%    |
| 0x106e5    | 2         | 0.6%    |
| 0x10676    | 2         | 0.6%    |
| 0x0a50000c | 2         | 0.6%    |
| 0x0600611a | 2         | 0.6%    |
| 0x06001119 | 2         | 0.6%    |
| 0x906a4    | 1         | 0.3%    |
| 0x906a3    | 1         | 0.3%    |
| 0x806d1    | 1         | 0.3%    |
| 0x706a1    | 1         | 0.3%    |
| 0x6e8      | 1         | 0.3%    |
| 0x506c9    | 1         | 0.3%    |
| 0x106ca    | 1         | 0.3%    |
| 0x08608103 | 1         | 0.3%    |
| 0x08600106 | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 89        | 27.64%  |
| Haswell          | 36        | 11.18%  |
| SandyBridge      | 25        | 7.76%   |
| IvyBridge        | 20        | 6.21%   |
| Broadwell        | 19        | 5.9%    |
| Skylake          | 18        | 5.59%   |
| Westmere         | 13        | 4.04%   |
| Excavator        | 13        | 4.04%   |
| Silvermont       | 11        | 3.42%   |
| CometLake        | 11        | 3.42%   |
| TigerLake        | 9         | 2.8%    |
| Penryn           | 8         | 2.48%   |
| Core             | 7         | 2.17%   |
| Piledriver       | 6         | 1.86%   |
| IceLake          | 6         | 1.86%   |
| Bobcat           | 4         | 1.24%   |
| Zen+             | 3         | 0.93%   |
| Zen 2            | 3         | 0.93%   |
| Unknown          | 3         | 0.93%   |
| Zen 3            | 2         | 0.62%   |
| Zen              | 2         | 0.62%   |
| Puma             | 2         | 0.62%   |
| Nehalem          | 2         | 0.62%   |
| K10              | 2         | 0.62%   |
| Goldmont plus    | 2         | 0.62%   |
| Alderlake Hybrid | 2         | 0.62%   |
| Steamroller      | 1         | 0.31%   |
| P6               | 1         | 0.31%   |
| Goldmont         | 1         | 0.31%   |
| Bonnell          | 1         | 0.31%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 259       | 54.76%  |
| Nvidia           | 114       | 24.1%   |
| AMD              | 99        | 20.93%  |
| VIA Technologies | 1         | 0.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 24        | 5.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 4.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 3.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 3.76%   |
| Intel HD Graphics 620                                                                    | 16        | 3.34%   |
| Intel HD Graphics 5500                                                                   | 16        | 3.34%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 3.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 3.13%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 14        | 2.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2.51%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 2.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2.09%   |
| Intel HD Graphics 630                                                                    | 10        | 2.09%   |
| Nvidia GM108M [GeForce MX130]                                                            | 9         | 1.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 1.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 1.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 1.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 1.46%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.46%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.25%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.04%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 5         | 1.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.84%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 4         | 0.84%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 0.84%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.63%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.63%   |
| Nvidia GP108M [GeForce MX230]                                                            | 3         | 0.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.63%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 117       | 36%     |
| Intel + Nvidia | 95        | 29.23%  |
| Intel + AMD    | 50        | 15.38%  |
| 1 x AMD        | 42        | 12.92%  |
| 1 x Nvidia     | 13        | 4%      |
| AMD + Nvidia   | 5         | 1.54%   |
| 2 x AMD        | 2         | 0.62%   |
| 1 x VIA        | 1         | 0.31%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 262       | 79.64%  |
| Proprietary | 58        | 17.63%  |
| Unknown     | 9         | 2.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 191       | 57.7%   |
| 1.01-2.0   | 50        | 15.11%  |
| 3.01-4.0   | 40        | 12.08%  |
| 0.01-0.5   | 22        | 6.65%   |
| 0.51-1.0   | 21        | 6.34%   |
| 5.01-6.0   | 5         | 1.51%   |
| 7.01-8.0   | 1         | 0.3%    |
| 8.01-16.0  | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 67        | 20.12%  |
| LG Display              | 60        | 18.02%  |
| AU Optronics            | 55        | 16.52%  |
| Chimei Innolux          | 51        | 15.32%  |
| Samsung Electronics     | 39        | 11.71%  |
| Chi Mei Optoelectronics | 14        | 4.2%    |
| Dell                    | 8         | 2.4%    |
| Lenovo                  | 7         | 2.1%    |
| Sharp                   | 5         | 1.5%    |
| InfoVision              | 5         | 1.5%    |
| PANDA                   | 4         | 1.2%    |
| Unknown                 | 2         | 0.6%    |
| Philips                 | 2         | 0.6%    |
| Apple                   | 2         | 0.6%    |
| Toshiba                 | 1         | 0.3%    |
| TMX                     | 1         | 0.3%    |
| Panasonic               | 1         | 0.3%    |
| NCS                     | 1         | 0.3%    |
| LG Philips              | 1         | 0.3%    |
| KDC                     | 1         | 0.3%    |
| InnoLux Display         | 1         | 0.3%    |
| Hewlett-Packard         | 1         | 0.3%    |
| Goldstar                | 1         | 0.3%    |
| CSO                     | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |
| ASUSTek Computer        | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 2.4%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 7         | 2.1%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 6         | 1.8%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 1.5%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 5         | 1.5%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 4         | 1.2%    |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                  | 4         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 4         | 1.2%    |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 1.2%    |
| BOE LCD Monitor BOE07B0 1920x1080 344x194mm 15.5-inch                    | 4         | 1.2%    |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 4         | 1.2%    |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch     | 3         | 0.9%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 3         | 0.9%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.9%    |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 3         | 0.9%    |
| BOE LCD Monitor BOE06C6 1920x1080 344x194mm 15.5-inch                    | 3         | 0.9%    |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                    | 3         | 0.9%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.9%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.9%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.6%    |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch    | 2         | 0.6%    |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.6%    |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch                  | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch         | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 344x194mm 15.5-inch         | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A4 1366x768 344x194mm 15.5-inch | 2         | 0.6%    |
| BOE LCD Monitor BOE0826 1920x1080 344x193mm 15.5-inch                    | 2         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 155       | 47.55%  |
| 1920x1080 (FHD)    | 132       | 40.49%  |
| 1600x900 (HD+)     | 9         | 2.76%   |
| 1280x800 (WXGA)    | 8         | 2.45%   |
| 3840x2160 (4K)     | 5         | 1.53%   |
| 1440x900 (WXGA+)   | 5         | 1.53%   |
| 1680x1050 (WSXGA+) | 4         | 1.23%   |
| 2560x1440 (QHD)    | 3         | 0.92%   |
| 3200x1800 (QHD+)   | 1         | 0.31%   |
| 2560x1600          | 1         | 0.31%   |
| 2288x1287          | 1         | 0.31%   |
| 1920x1200 (WUXGA)  | 1         | 0.31%   |
| 1024x600           | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 220       | 66.07%  |
| 14      | 44        | 13.21%  |
| 13      | 20        | 6.01%   |
| 12      | 11        | 3.3%    |
| 17      | 7         | 2.1%    |
| 24      | 5         | 1.5%    |
| 22      | 4         | 1.2%    |
| 23      | 3         | 0.9%    |
| 18      | 3         | 0.9%    |
| 27      | 2         | 0.6%    |
| 21      | 2         | 0.6%    |
| 19      | 2         | 0.6%    |
| 11      | 2         | 0.6%    |
| Unknown | 2         | 0.6%    |
| 142     | 1         | 0.3%    |
| 58      | 1         | 0.3%    |
| 42      | 1         | 0.3%    |
| 40      | 1         | 0.3%    |
| 16      | 1         | 0.3%    |
| 10      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 278       | 83.99%  |
| 201-300        | 20        | 6.04%   |
| 501-600        | 10        | 3.02%   |
| 401-500        | 10        | 3.02%   |
| 351-400        | 7         | 2.11%   |
| Unknown        | 2         | 0.6%    |
| More than 2000 | 1         | 0.3%    |
| 801-900        | 1         | 0.3%    |
| 1001-1500      | 1         | 0.3%    |
| 901-1000       | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 295       | 93.35%  |
| 16/10   | 17        | 5.38%   |
| Unknown | 2         | 0.63%   |
| 4/3     | 1         | 0.32%   |
| 1.00    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 217       | 65.17%  |
| 81-90          | 58        | 17.42%  |
| 201-250        | 13        | 3.9%    |
| 61-70          | 10        | 3%      |
| 71-80          | 6         | 1.8%    |
| 121-130        | 6         | 1.8%    |
| 91-100         | 4         | 1.2%    |
| 151-200        | 3         | 0.9%    |
| More than 1000 | 2         | 0.6%    |
| 51-60          | 2         | 0.6%    |
| 301-350        | 2         | 0.6%    |
| 141-150        | 2         | 0.6%    |
| 501-1000       | 2         | 0.6%    |
| Unknown        | 2         | 0.6%    |
| 41-50          | 1         | 0.3%    |
| 251-300        | 1         | 0.3%    |
| 131-140        | 1         | 0.3%    |
| 111-120        | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 147       | 44.68%  |
| 121-160       | 133       | 40.43%  |
| 51-100        | 34        | 10.33%  |
| 161-240       | 8         | 2.43%   |
| More than 240 | 3         | 0.91%   |
| 1-50          | 2         | 0.61%   |
| Unknown       | 2         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 294       | 89.91%  |
| 2     | 25        | 7.65%   |
| 0     | 7         | 2.14%   |
| 3     | 1         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 227       | 41.65%  |
| Intel                             | 149       | 27.34%  |
| Qualcomm Atheros                  | 84        | 15.41%  |
| Broadcom                          | 37        | 6.79%   |
| Broadcom Limited                  | 8         | 1.47%   |
| Ralink Technology                 | 6         | 1.1%    |
| Ralink                            | 6         | 1.1%    |
| MediaTek                          | 5         | 0.92%   |
| Marvell Technology Group          | 4         | 0.73%   |
| Huawei Technologies               | 4         | 0.73%   |
| TP-Link                           | 3         | 0.55%   |
| Samsung Electronics               | 3         | 0.55%   |
| VIA Technologies                  | 1         | 0.18%   |
| Sierra Wireless                   | 1         | 0.18%   |
| Nvidia                            | 1         | 0.18%   |
| Hewlett-Packard                   | 1         | 0.18%   |
| Ericsson Business Mobile Networks | 1         | 0.18%   |
| Dell                              | 1         | 0.18%   |
| D-Link                            | 1         | 0.18%   |
| Belkin Components                 | 1         | 0.18%   |
| ASIX Electronics                  | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133       | 20.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 81        | 12.76%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 33        | 5.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 2.2%    |
| Intel Wireless 8265 / 8275                                        | 14        | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14        | 2.2%    |
| Broadcom BCM43142 802.11b/g/n                                     | 14        | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 2.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 11        | 1.73%   |
| Intel Wireless 7265                                               | 10        | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 1.57%   |
| Intel Wireless 8260                                               | 9         | 1.42%   |
| Intel Wireless 7260                                               | 9         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.42%   |
| Intel Wireless 3160                                               | 8         | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 8         | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 1.1%    |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 5         | 0.79%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.79%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 5         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.63%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 3         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.47%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.47%   |
| Intel Wireless 3165                                               | 3         | 0.47%   |
| Intel PRODUCT_MODEM                                               | 3         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 142       | 42.39%  |
| Qualcomm Atheros                  | 76        | 22.69%  |
| Realtek Semiconductor             | 54        | 16.12%  |
| Broadcom                          | 33        | 9.85%   |
| Broadcom Limited                  | 7         | 2.09%   |
| Ralink Technology                 | 6         | 1.79%   |
| Ralink                            | 6         | 1.79%   |
| MediaTek                          | 4         | 1.19%   |
| TP-Link                           | 2         | 0.6%    |
| Sierra Wireless                   | 1         | 0.3%    |
| Ericsson Business Mobile Networks | 1         | 0.3%    |
| Dell                              | 1         | 0.3%    |
| D-Link                            | 1         | 0.3%    |
| Belkin Components                 | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 33        | 9.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 4.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 4.15%   |
| Intel Wireless 8265 / 8275                                     | 14        | 4.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 4.15%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 4.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 3.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 3.26%   |
| Intel Wireless 7265                                            | 10        | 2.97%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 2.97%   |
| Intel Wireless 8260                                            | 9         | 2.67%   |
| Intel Wireless 7260                                            | 9         | 2.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 2.67%   |
| Intel Wireless 3160                                            | 8         | 2.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 2.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 1.48%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 1.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.19%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.19%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.19%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.89%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.89%   |
| Intel Wireless 3165                                            | 3         | 0.89%   |
| Intel PRODUCT_MODEM                                            | 3         | 0.89%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 0.89%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 0.89%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 0.89%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 3         | 0.89%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.59%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.59%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.59%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 215       | 73.88%  |
| Intel                    | 46        | 15.81%  |
| Qualcomm Atheros         | 13        | 4.47%   |
| Broadcom                 | 5         | 1.72%   |
| Marvell Technology Group | 4         | 1.37%   |
| Huawei Technologies      | 2         | 0.69%   |
| VIA Technologies         | 1         | 0.34%   |
| TP-Link                  | 1         | 0.34%   |
| Nvidia                   | 1         | 0.34%   |
| MediaTek                 | 1         | 0.34%   |
| Broadcom Limited         | 1         | 0.34%   |
| ASIX Electronics         | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 133       | 45.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 81        | 27.74%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.74%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 2.05%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.71%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.37%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.37%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.03%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 3         | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.68%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.68%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.68%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.68%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.34%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.34%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.34%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.34%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.34%   |
| MediaTek Titan pocket                                             | 1         | 0.34%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.34%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.34%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.34%   |
| Huawei WLZ-AN00                                                   | 1         | 0.34%   |
| Huawei E353/E3131                                                 | 1         | 0.34%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.34%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.34%   |
| Broadcom Limited NetXtreme BCM5762 Gigabit Ethernet PCIe          | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 318       | 52.05%  |
| Ethernet | 287       | 46.97%  |
| Modem    | 6         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 273       | 83.23%  |
| Ethernet | 55        | 16.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 280       | 86.96%  |
| 1     | 35        | 10.87%  |
| 0     | 5         | 1.55%   |
| 3     | 2         | 0.62%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 322       | 99.69%  |
| Yes  | 1         | 0.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 40.96%  |
| Qualcomm Atheros Communications | 50        | 18.45%  |
| Realtek Semiconductor           | 37        | 13.65%  |
| Broadcom                        | 23        | 8.49%   |
| IMC Networks                    | 8         | 2.95%   |
| Hewlett-Packard                 | 7         | 2.58%   |
| Foxconn / Hon Hai               | 7         | 2.58%   |
| Lite-On Technology              | 6         | 2.21%   |
| Toshiba                         | 5         | 1.85%   |
| Ralink                          | 4         | 1.48%   |
| Dell                            | 3         | 1.11%   |
| Cambridge Silicon Radio         | 3         | 1.11%   |
| Foxconn International           | 2         | 0.74%   |
| Apple                           | 2         | 0.74%   |
| Taiyo Yuden                     | 1         | 0.37%   |
| MediaTek                        | 1         | 0.37%   |
| Edimax Technology               | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 56        | 20.66%  |
| Qualcomm Atheros  Bluetooth Device                  | 35        | 12.92%  |
| Realtek Bluetooth Radio                             | 25        | 9.23%   |
| Intel AX201 Bluetooth                               | 22        | 8.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 6.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 2.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 5         | 1.85%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 5         | 1.85%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.48%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.48%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.48%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.48%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 1.48%   |
| Realtek RTL8821A Bluetooth                          | 3         | 1.11%   |
| Realtek RTL8723B Bluetooth                          | 3         | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.11%   |
| Lite-On Bluetooth Device                            | 3         | 1.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.11%   |
| Dell Wireless 365 Bluetooth                         | 3         | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.11%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.11%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.11%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.74%   |
| Intel Bluetooth Device                              | 2         | 0.74%   |
| Intel AX200 Bluetooth                               | 2         | 0.74%   |
| IMC Networks Wireless_Device                        | 2         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.74%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.74%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.74%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.37%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.37%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.37%   |
| Toshiba Bluetooth Device                            | 1         | 0.37%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 274       | 72.3%   |
| Nvidia            | 54        | 14.25%  |
| AMD               | 48        | 12.66%  |
| VIA Technologies  | 1         | 0.26%   |
| Texas Instruments | 1         | 0.26%   |
| Logitech          | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 56        | 12.07%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 23        | 4.96%   |
| Intel 8 Series HD Audio Controller                                         | 22        | 4.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22        | 4.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 4.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 4.09%   |
| Intel Broadwell-U Audio Controller                                         | 19        | 4.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 3.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15        | 3.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 3.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 13        | 2.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 12        | 2.59%   |
| AMD FCH Azalia Controller                                                  | 12        | 2.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 2.37%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 2.37%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 2.16%   |
| Intel CM238 HD Audio Controller                                            | 10        | 2.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 2.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 9         | 1.94%   |
| AMD High Definition Audio Controller                                       | 9         | 1.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 1.51%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 1.51%   |
| AMD Trinity HDMI Audio Controller                                          | 6         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.08%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.65%   |
| Nvidia Audio device                                                        | 3         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 0.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 0.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 0.65%   |
| Nvidia GT216 HDMI Audio Controller                                         | 2         | 0.43%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 59        | 31.89%  |
| Samsung Electronics | 54        | 29.19%  |
| Micron Technology   | 24        | 12.97%  |
| Crucial             | 12        | 6.49%   |
| Ramaxel Technology  | 11        | 5.95%   |
| Kingston            | 8         | 4.32%   |
| Unknown             | 4         | 2.16%   |
| Nanya Technology    | 3         | 1.62%   |
| Elpida              | 3         | 1.62%   |
| Team                | 2         | 1.08%   |
| Unknown             | 2         | 1.08%   |
| Unknown (ABCD)      | 1         | 0.54%   |
| G.Skill             | 1         | 0.54%   |
| Axiom               | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 7         | 3.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 5         | 2.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.57%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 1.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 3         | 1.57%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 3         | 1.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 3         | 1.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 3         | 1.57%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s    | 3         | 1.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 3         | 1.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 3         | 1.57%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s    | 3         | 1.57%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s | 2         | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 1.05%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 2         | 1.05%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s | 2         | 1.05%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 2         | 1.05%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s          | 2         | 1.05%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s  | 2         | 1.05%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.05%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 1.05%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s    | 2         | 1.05%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 1.05%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 1.05%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.05%   |
| Ramaxel RAM RMSA3260NA78HAF-2400 8GB SODIMM DDR4 2400MT/s | 2         | 1.05%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 2         | 1.05%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s     | 2         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.05%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s     | 2         | 1.05%   |
| Unknown                                                   | 2         | 1.05%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 1         | 0.52%   |
| Unknown RAM Module 8GB SODIMM DDR3                        | 1         | 0.52%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s               | 1         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s            | 1         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 85        | 57.05%  |
| DDR3   | 55        | 36.91%  |
| SDRAM  | 3         | 2.01%   |
| LPDDR4 | 3         | 2.01%   |
| LPDDR5 | 1         | 0.67%   |
| DDR2   | 1         | 0.67%   |
| DDR    | 1         | 0.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 139       | 95.86%  |
| Row Of Chips | 4         | 2.76%   |
| DIMM         | 1         | 0.69%   |
| Chip         | 1         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 60        | 35.93%  |
| 4096  | 53        | 31.74%  |
| 16384 | 35        | 20.96%  |
| 2048  | 17        | 10.18%  |
| 1024  | 1         | 0.6%    |
| 512   | 1         | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 51        | 31.48%  |
| 1600    | 43        | 26.54%  |
| 3200    | 21        | 12.96%  |
| 1334    | 12        | 7.41%   |
| 2400    | 11        | 6.79%   |
| 2133    | 7         | 4.32%   |
| 1333    | 4         | 2.47%   |
| 8400    | 2         | 1.23%   |
| 4199    | 2         | 1.23%   |
| 3266    | 2         | 1.23%   |
| 1866    | 2         | 1.23%   |
| 6400    | 1         | 0.62%   |
| 2048    | 1         | 0.62%   |
| 800     | 1         | 0.62%   |
| 667     | 1         | 0.62%   |
| Unknown | 1         | 0.62%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1018 | 1         | 50%     |
| HP Deskjet 1510  | 1         | 50%     |

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
| Chicony Electronics                    | 70        | 23.97%  |
| Microdia                               | 38        | 13.01%  |
| Realtek Semiconductor                  | 32        | 10.96%  |
| IMC Networks                           | 28        | 9.59%   |
| Cheng Uei Precision Industry (Foxlink) | 26        | 8.9%    |
| Sunplus Innovation Technology          | 22        | 7.53%   |
| Bison Electronics                      | 17        | 5.82%   |
| Lite-On Technology                     | 10        | 3.42%   |
| Quanta                                 | 8         | 2.74%   |
| Acer                                   | 8         | 2.74%   |
| Suyin                                  | 7         | 2.4%    |
| Silicon Motion                         | 7         | 2.4%    |
| Syntek                                 | 6         | 2.05%   |
| Apple                                  | 4         | 1.37%   |
| Luxvisions Innotech Limited            | 2         | 0.68%   |
| Lenovo                                 | 2         | 0.68%   |
| Sonix Technology                       | 1         | 0.34%   |
| OmniVision Technologies                | 1         | 0.34%   |
| MacroSilicon                           | 1         | 0.34%   |
| Intel                                  | 1         | 0.34%   |
| ALi                                    | 1         | 0.34%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 21        | 7.17%   |
| Realtek Integrated_Webcam_HD                                               | 15        | 5.12%   |
| Chicony EasyCamera                                                         | 12        | 4.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 2.73%   |
| IMC Networks Integrated Camera                                             | 8         | 2.73%   |
| Sunplus Integrated_Webcam_HD                                               | 7         | 2.39%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 7         | 2.39%   |
| Chicony Integrated Camera                                                  | 6         | 2.05%   |
| Chicony HP HD Camera                                                       | 6         | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 6         | 2.05%   |
| Bison Lenovo EasyCamera                                                    | 5         | 1.71%   |
| Syntek Integrated Camera                                                   | 4         | 1.37%   |
| Realtek Integrated Webcam HD                                               | 4         | 1.37%   |
| Realtek Integrated Webcam                                                  | 4         | 1.37%   |
| Realtek EasyCamera                                                         | 4         | 1.37%   |
| Microdia Dell Laptop Integrated Webcam HD                                  | 4         | 1.37%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 4         | 1.37%   |
| Chicony HP Truevision HD camera                                            | 4         | 1.37%   |
| Chicony HP HD Webcam                                                       | 4         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 4         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 4         | 1.37%   |
| Bison HP TrueVision HD Webcam                                              | 4         | 1.37%   |
| Sunplus Dell HD Webcam                                                     | 3         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 3         | 1.02%   |
| Lite-On Integrated Camera                                                  | 3         | 1.02%   |
| Lite-On HP HD Webcam                                                       | 3         | 1.02%   |
| Lite-On HP HD Camera                                                       | 3         | 1.02%   |
| IMC Networks Lenovo EasyCamera                                             | 3         | 1.02%   |
| IMC Networks EasyCamera                                                    | 3         | 1.02%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 1.02%   |
| Chicony USB 2.0 Camera                                                     | 3         | 1.02%   |
| Chicony HP TrueVision HD                                                   | 3         | 1.02%   |
| Bison EasyCamera                                                           | 3         | 1.02%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 3         | 1.02%   |
| Acer Lenovo EasyCamera                                                     | 3         | 1.02%   |
| Suyin HP Truevision HD                                                     | 2         | 0.68%   |
| Sunplus HP Universal Camera                                                | 2         | 0.68%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 0.68%   |
| Sunplus Dell E5570 integrated webcam                                       | 2         | 0.68%   |
| Silicon Motion WebCam SC-03M12736N                                         | 2         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 55.56%  |
| Synaptics                  | 11        | 20.37%  |
| Shenzhen Goodix Technology | 6         | 11.11%  |
| Upek                       | 5         | 9.26%   |
| AuthenTec                  | 2         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 25.93%  |
| Validity Sensors Fingerprint scanner                                       | 6         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 7.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 7.41%   |
| Synaptics  WBDI                                                            | 4         | 7.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 7.41%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 7.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 5.56%   |
| Validity Sensors VFS491                                                    | 2         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.7%    |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 3.7%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 1.85%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.85%   |
| AuthenTec AES2810                                                          | 1         | 1.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 1.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 66.67%  |
| Alcor Micro | 3         | 16.67%  |
| O2 Micro    | 2         | 11.11%  |
| Lenovo      | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 5         | 27.78%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.11%  |
| Broadcom 58200                                                               | 2         | 11.11%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 203       | 61.14%  |
| 1     | 106       | 31.93%  |
| 2     | 22        | 6.63%   |
| 4     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 36.05%  |
| Graphics card            | 38        | 25.85%  |
| Chipcard                 | 18        | 12.24%  |
| Net/wireless             | 17        | 11.56%  |
| Bluetooth                | 6         | 4.08%   |
| Multimedia controller    | 5         | 3.4%    |
| Sound                    | 3         | 2.04%   |
| Net/ethernet             | 2         | 1.36%   |
| Storage/ide              | 1         | 0.68%   |
| Storage                  | 1         | 0.68%   |
| Communication controller | 1         | 0.68%   |
| Card reader              | 1         | 0.68%   |
| Camera                   | 1         | 0.68%   |


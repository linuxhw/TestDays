Solus - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Solus.

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

Total: 157

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 5738                 | [c065f8efda](https://linux-hardware.org/?probe=c065f8efda) | Mar 31, 2024 |
| Packard Be... | EasyNote MH36               | [db4c360048](https://linux-hardware.org/?probe=db4c360048) | Mar 30, 2024 |
| Dell          | Latitude E5470              | [844e9a99df](https://linux-hardware.org/?probe=844e9a99df) | Mar 24, 2024 |
| Dell          | Latitude E5470              | [a268f7138b](https://linux-hardware.org/?probe=a268f7138b) | Mar 24, 2024 |
| Lenovo        | ThinkPad T410 253725G       | [33a07105de](https://linux-hardware.org/?probe=33a07105de) | Mar 24, 2024 |
| Apple         | MacBookPro12,1              | [c3230ba277](https://linux-hardware.org/?probe=c3230ba277) | Mar 03, 2024 |
| HUAWEI        | BOD-WXX9                    | [d8e2dd481d](https://linux-hardware.org/?probe=d8e2dd481d) | Dec 28, 2023 |
| Google        | Kip                         | [344f7b3eda](https://linux-hardware.org/?probe=344f7b3eda) | Sep 21, 2023 |
| Dell          | Latitude E6400              | [d3bc465020](https://linux-hardware.org/?probe=d3bc465020) | Aug 23, 2023 |
| Dell          | Latitude E6400              | [a1b816015e](https://linux-hardware.org/?probe=a1b816015e) | Aug 23, 2023 |
| Packard Be... | EasyNote TE11HC             | [f69a3b4363](https://linux-hardware.org/?probe=f69a3b4363) | Aug 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [af4abf9f1d](https://linux-hardware.org/?probe=af4abf9f1d) | Aug 16, 2023 |
| Acer          | Nitro AN515-45              | [fda8d0a543](https://linux-hardware.org/?probe=fda8d0a543) | Aug 02, 2023 |
| Valve         | Jupiter                     | [b7af0e09ea](https://linux-hardware.org/?probe=b7af0e09ea) | Jul 12, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [33a8b4ab02](https://linux-hardware.org/?probe=33a8b4ab02) | Jul 08, 2023 |
| Sony          | VPCF236FM                   | [21a805fe1d](https://linux-hardware.org/?probe=21a805fe1d) | Jul 08, 2023 |
| ASUSTek       | UX430UAR                    | [6a51948293](https://linux-hardware.org/?probe=6a51948293) | Jul 03, 2023 |
| Dell          | Latitude 3420               | [730bdb05fe](https://linux-hardware.org/?probe=730bdb05fe) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d7e8503e88](https://linux-hardware.org/?probe=d7e8503e88) | Jun 23, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [299733170c](https://linux-hardware.org/?probe=299733170c) | Apr 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [db0f4c6df3](https://linux-hardware.org/?probe=db0f4c6df3) | Mar 16, 2023 |
| Dell          | Inspiron 7460               | [141874b125](https://linux-hardware.org/?probe=141874b125) | Jan 08, 2023 |
| Samsung       | R430/P430/R480              | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Toshiba       | Satellite L855              | [932d8fec2d](https://linux-hardware.org/?probe=932d8fec2d) | Dec 12, 2022 |
| MSI           | Modern 14 B5M               | [2bd9abfe2c](https://linux-hardware.org/?probe=2bd9abfe2c) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [12b14f3cbc](https://linux-hardware.org/?probe=12b14f3cbc) | Nov 06, 2022 |
| Quanta        | TWS                         | [a800f54191](https://linux-hardware.org/?probe=a800f54191) | Nov 06, 2022 |
| Toshiba       | Satellite L855              | [1065197a6e](https://linux-hardware.org/?probe=1065197a6e) | Sep 15, 2022 |
| Dell          | Latitude E5470              | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [76083d81dc](https://linux-hardware.org/?probe=76083d81dc) | Jul 30, 2022 |
| Acer          | Aspire A315-54              | [9e0bbc26f4](https://linux-hardware.org/?probe=9e0bbc26f4) | Jul 22, 2022 |
| AZW           | SEi                         | [7556cabcae](https://linux-hardware.org/?probe=7556cabcae) | Jul 07, 2022 |
| GPU Compan... | GWTC116-2                   | [d0c0f4f120](https://linux-hardware.org/?probe=d0c0f4f120) | Jul 06, 2022 |
| GPU Compan... | GWTC116-2                   | [9d0dd21c70](https://linux-hardware.org/?probe=9d0dd21c70) | Jul 06, 2022 |
| HP            | ProBook 450 G5              | [c4880f9bab](https://linux-hardware.org/?probe=c4880f9bab) | Jun 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5330a5aa11](https://linux-hardware.org/?probe=5330a5aa11) | Jun 02, 2022 |
| HP            | ProBook 450 G5              | [7f8acf64cd](https://linux-hardware.org/?probe=7f8acf64cd) | May 31, 2022 |
| HP            | ProBook 450 G5              | [2fbbe84744](https://linux-hardware.org/?probe=2fbbe84744) | May 31, 2022 |
| Google        | Edgar                       | [fef9eeb5db](https://linux-hardware.org/?probe=fef9eeb5db) | May 02, 2022 |
| Lenovo        | Z50-70 20354                | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Dell          | XPS 13 9380                 | [efc6123d49](https://linux-hardware.org/?probe=efc6123d49) | Mar 06, 2022 |
| Google        | Delbin                      | [fbf8763bd4](https://linux-hardware.org/?probe=fbf8763bd4) | Feb 05, 2022 |
| Acer          | Aspire A315-54              | [5eb9b9e574](https://linux-hardware.org/?probe=5eb9b9e574) | Jan 22, 2022 |
| Acer          | Swift SF114-34              | [15431686d8](https://linux-hardware.org/?probe=15431686d8) | Jan 06, 2022 |
| Toshiba       | TECRA R840                  | [753c7caef6](https://linux-hardware.org/?probe=753c7caef6) | Dec 27, 2021 |
| Sony          | VPCYB15AB                   | [780ef18db3](https://linux-hardware.org/?probe=780ef18db3) | Dec 13, 2021 |
| Dell          | Latitude 5580               | [a10f022f63](https://linux-hardware.org/?probe=a10f022f63) | Nov 26, 2021 |
| Framework     | Laptop                      | [7995a7a4de](https://linux-hardware.org/?probe=7995a7a4de) | Nov 18, 2021 |
| Dell          | Latitude E6220              | [09a75055c9](https://linux-hardware.org/?probe=09a75055c9) | Nov 12, 2021 |
| Framework     | Laptop                      | [72a07a2e81](https://linux-hardware.org/?probe=72a07a2e81) | Nov 11, 2021 |
| AZW           | SEi                         | [0e29003348](https://linux-hardware.org/?probe=0e29003348) | Oct 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c7f1620c1c](https://linux-hardware.org/?probe=c7f1620c1c) | Oct 05, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [f19ad7cba2](https://linux-hardware.org/?probe=f19ad7cba2) | Sep 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [1cca1c6ce5](https://linux-hardware.org/?probe=1cca1c6ce5) | Sep 13, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [888bf75e20](https://linux-hardware.org/?probe=888bf75e20) | Sep 13, 2021 |
| Acer          | Nitro AN515-45              | [5bad88330d](https://linux-hardware.org/?probe=5bad88330d) | Sep 01, 2021 |
| Dell          | Inspiron 1525               | [3f3cd9c9e2](https://linux-hardware.org/?probe=3f3cd9c9e2) | Aug 25, 2021 |
| Dell          | Inspiron 1525               | [de3cb038ef](https://linux-hardware.org/?probe=de3cb038ef) | Aug 25, 2021 |
| Acer          | Nitro AN515-45              | [d98d816e7f](https://linux-hardware.org/?probe=d98d816e7f) | Aug 18, 2021 |
| Acer          | Nitro AN515-45              | [5320b136ea](https://linux-hardware.org/?probe=5320b136ea) | Aug 12, 2021 |
| Dell          | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| HP            | ProBook 650 G2              | [15257858f3](https://linux-hardware.org/?probe=15257858f3) | Aug 07, 2021 |
| Dell          | Inspiron 15-3573            | [52916532a3](https://linux-hardware.org/?probe=52916532a3) | Aug 06, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [75ec31cefd](https://linux-hardware.org/?probe=75ec31cefd) | Jul 16, 2021 |
| Dell          | Vostro 15-3568              | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| ASUSTek       | N53SV                       | [53fef6a61a](https://linux-hardware.org/?probe=53fef6a61a) | Jul 08, 2021 |
| Dell          | Inspiron 3537               | [6fc3976633](https://linux-hardware.org/?probe=6fc3976633) | Jun 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [0e1e07507e](https://linux-hardware.org/?probe=0e1e07507e) | Jun 15, 2021 |
| HP            | ProBook 650 G1              | [120d5f24fe](https://linux-hardware.org/?probe=120d5f24fe) | Jun 07, 2021 |
| Howard Com... | W350                        | [3e55c8284e](https://linux-hardware.org/?probe=3e55c8284e) | May 28, 2021 |
| Acer          | Aspire E5-575G              | [ce04df7bae](https://linux-hardware.org/?probe=ce04df7bae) | May 23, 2021 |
| Gigabyte      | AORUS 17G KB                | [fd9385ff3c](https://linux-hardware.org/?probe=fd9385ff3c) | Apr 29, 2021 |
| Packard Be... | EasyNote TS11HR             | [5c51b7f289](https://linux-hardware.org/?probe=5c51b7f289) | Apr 25, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| HP            | Pavilion dv7                | [e8b5a1786b](https://linux-hardware.org/?probe=e8b5a1786b) | Apr 08, 2021 |
| HP            | ProBook 650 G1              | [e25f4adb0b](https://linux-hardware.org/?probe=e25f4adb0b) | Mar 31, 2021 |
| HP            | ProBook 650 G1              | [4ba1bb5165](https://linux-hardware.org/?probe=4ba1bb5165) | Mar 29, 2021 |
| Toshiba       | Satellite L855              | [e507a57307](https://linux-hardware.org/?probe=e507a57307) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f1c277189f](https://linux-hardware.org/?probe=f1c277189f) | Feb 16, 2021 |
| Acer          | Aspire 5735                 | [d8b7b99dd0](https://linux-hardware.org/?probe=d8b7b99dd0) | Feb 16, 2021 |
| Toshiba       | Satellite L855              | [7a2993f67a](https://linux-hardware.org/?probe=7a2993f67a) | Feb 03, 2021 |
| Lenovo        | ThinkPad T410 2522Y1L       | [3c4543a94f](https://linux-hardware.org/?probe=3c4543a94f) | Jan 26, 2021 |
| Dell          | XPS 13 9360                 | [56d39c0f21](https://linux-hardware.org/?probe=56d39c0f21) | Jan 02, 2021 |
| Toshiba       | Satellite L855              | [0173204c7f](https://linux-hardware.org/?probe=0173204c7f) | Dec 23, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [26447067ee](https://linux-hardware.org/?probe=26447067ee) | Dec 20, 2020 |
| Acer          | Aspire A315-21              | [5f78418b58](https://linux-hardware.org/?probe=5f78418b58) | Dec 19, 2020 |
| HP            | EliteBook 840 G3            | [708eaf5602](https://linux-hardware.org/?probe=708eaf5602) | Dec 14, 2020 |
| Toshiba       | Satellite L855              | [3d3a517e96](https://linux-hardware.org/?probe=3d3a517e96) | Dec 11, 2020 |
| Sony          | VPCEB1S1E                   | [ebcb16e616](https://linux-hardware.org/?probe=ebcb16e616) | Nov 27, 2020 |
| Panasonic     | CF-C2CCEZXCM                | [cba289e868](https://linux-hardware.org/?probe=cba289e868) | Nov 22, 2020 |
| Acer          | Aspire E1-532P              | [4a2a5fd18c](https://linux-hardware.org/?probe=4a2a5fd18c) | Nov 01, 2020 |
| Timi          | TM1701                      | [36446e6594](https://linux-hardware.org/?probe=36446e6594) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | [b21d4ca9d0](https://linux-hardware.org/?probe=b21d4ca9d0) | Oct 26, 2020 |
| Apple         | MacBook5,2                  | [eb1b0d459f](https://linux-hardware.org/?probe=eb1b0d459f) | Oct 25, 2020 |
| Toshiba       | PORTEGE Z20T-B              | [9d789eba3c](https://linux-hardware.org/?probe=9d789eba3c) | Oct 12, 2020 |
| Toshiba       | Satellite P50-A             | [884731a198](https://linux-hardware.org/?probe=884731a198) | Sep 28, 2020 |
| HP            | ProBook 450 G5              | [d04bae5c49](https://linux-hardware.org/?probe=d04bae5c49) | Sep 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C5A... | [2f729ef2af](https://linux-hardware.org/?probe=2f729ef2af) | Sep 11, 2020 |
| Lenovo        | ThinkPad T440p 20AN009CU... | [bcc44c581c](https://linux-hardware.org/?probe=bcc44c581c) | Sep 09, 2020 |
| Dell          | Inspiron 5577               | [b46a79f93e](https://linux-hardware.org/?probe=b46a79f93e) | Sep 03, 2020 |
| Acer          | Aspire ES1-111M             | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [793085b89a](https://linux-hardware.org/?probe=793085b89a) | Aug 15, 2020 |
| HP            | ProBook 440 G4              | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| Avell High... | Avell G1750 MUV / C65 MU... | [cf035fee07](https://linux-hardware.org/?probe=cf035fee07) | Jul 24, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2fdc7ceb31](https://linux-hardware.org/?probe=2fdc7ceb31) | Jul 03, 2020 |
| HP            | Presario C700               | [6b50a4fad1](https://linux-hardware.org/?probe=6b50a4fad1) | Jun 26, 2020 |
| ASUSTek       | K45A                        | [57c5b7b4bd](https://linux-hardware.org/?probe=57c5b7b4bd) | Jun 08, 2020 |
| Acer          | Predator PH315-52           | [b5e7780315](https://linux-hardware.org/?probe=b5e7780315) | Jun 04, 2020 |
| Lenovo        | Z51-70 80K6                 | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [cb0fe570e2](https://linux-hardware.org/?probe=cb0fe570e2) | May 22, 2020 |
| Dell          | Latitude 7390               | [49112c8937](https://linux-hardware.org/?probe=49112c8937) | May 20, 2020 |
| HP            | ProBook 6470b               | [59db0f436f](https://linux-hardware.org/?probe=59db0f436f) | May 13, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [e98c6a162c](https://linux-hardware.org/?probe=e98c6a162c) | May 03, 2020 |
| Toshiba       | Satellite L655              | [32a9d86996](https://linux-hardware.org/?probe=32a9d86996) | May 02, 2020 |
| Acer          | Aspire E1-532P              | [b401e8b701](https://linux-hardware.org/?probe=b401e8b701) | Apr 30, 2020 |
| HP            | Pavilion dv6                | [6939cb8715](https://linux-hardware.org/?probe=6939cb8715) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | [328b82f240](https://linux-hardware.org/?probe=328b82f240) | Apr 11, 2020 |
| HP            | Pavilion dv6                | [0c6dc861d6](https://linux-hardware.org/?probe=0c6dc861d6) | Apr 06, 2020 |
| HP            | Pavilion dv6                | [3d9d707ea7](https://linux-hardware.org/?probe=3d9d707ea7) | Mar 30, 2020 |
| Chuwi         | LapBook SE                  | [f7cfd1b163](https://linux-hardware.org/?probe=f7cfd1b163) | Mar 26, 2020 |
| Acer          | Swift SF314-56              | [3826e4d14c](https://linux-hardware.org/?probe=3826e4d14c) | Mar 24, 2020 |
| Google        | Kip                         | [4f62ee34a3](https://linux-hardware.org/?probe=4f62ee34a3) | Mar 22, 2020 |
| Dell          | Vostro 3446                 | [c42d273e36](https://linux-hardware.org/?probe=c42d273e36) | Mar 12, 2020 |
| HP            | ProBook 450 G5              | [0c527b2640](https://linux-hardware.org/?probe=0c527b2640) | Mar 08, 2020 |
| Acer          | Aspire VN7-792G             | [3924df2c92](https://linux-hardware.org/?probe=3924df2c92) | Feb 28, 2020 |
| Apple         | MacBookPro10,2              | [1281c8c30d](https://linux-hardware.org/?probe=1281c8c30d) | Feb 26, 2020 |
| Lenovo        | ThinkPad T480 20L5S08L00    | [3c23e0d823](https://linux-hardware.org/?probe=3c23e0d823) | Feb 20, 2020 |
| Lenovo        | ThinkPad W530 243852U       | [eb8bd4a219](https://linux-hardware.org/?probe=eb8bd4a219) | Jan 20, 2020 |
| ASUSTek       | X556UQK                     | [5070b3831b](https://linux-hardware.org/?probe=5070b3831b) | Dec 29, 2019 |
| Lenovo        | ThinkPad X301 4057WHQ       | [badcab7790](https://linux-hardware.org/?probe=badcab7790) | Dec 22, 2019 |
| Dell          | Inspiron N5040              | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| Howard Com... | W350                        | [7434be9250](https://linux-hardware.org/?probe=7434be9250) | Dec 10, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Acer          | Aspire E5-575G              | [99d56262c0](https://linux-hardware.org/?probe=99d56262c0) | Dec 03, 2019 |
| HP            | Pavilion 17                 | [09c3d61b20](https://linux-hardware.org/?probe=09c3d61b20) | Nov 18, 2019 |
| HP            | Stream Laptop 14-cb1XX      | [372f025649](https://linux-hardware.org/?probe=372f025649) | Nov 18, 2019 |
| HP            | 255 G1                      | [0a0d476781](https://linux-hardware.org/?probe=0a0d476781) | Nov 06, 2019 |
| HP            | 255 G1                      | [2aa8aaffc1](https://linux-hardware.org/?probe=2aa8aaffc1) | Nov 04, 2019 |
| Acer          | Swift SF315-52              | [c5950fe2b2](https://linux-hardware.org/?probe=c5950fe2b2) | Oct 20, 2019 |
| Toshiba       | Unknown                     | [64c90921de](https://linux-hardware.org/?probe=64c90921de) | Oct 18, 2019 |
| Dell          | Latitude 7490               | [2381ee7707](https://linux-hardware.org/?probe=2381ee7707) | Oct 14, 2019 |
| HP            | ENVY dv7                    | [1f13304239](https://linux-hardware.org/?probe=1f13304239) | Oct 06, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | [4e34d8767a](https://linux-hardware.org/?probe=4e34d8767a) | Aug 03, 2019 |
| Dell          | XPS 15 9560                 | [65f14ca77f](https://linux-hardware.org/?probe=65f14ca77f) | Jun 11, 2019 |
| HP            | EliteBook 8770w             | [fdba82a5b5](https://linux-hardware.org/?probe=fdba82a5b5) | Apr 01, 2019 |
| Acer          | Aspire V3-571G              | [0ffa9711e1](https://linux-hardware.org/?probe=0ffa9711e1) | Jan 07, 2019 |
| Acer          | Aspire V3-571G              | [46de1b2636](https://linux-hardware.org/?probe=46de1b2636) | Jan 07, 2019 |
| Acer          | Aspire E1-532P              | [26e0937896](https://linux-hardware.org/?probe=26e0937896) | Nov 01, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Solus 4.1    | 39        | 33.33%  |
| Solus 4.3    | 33        | 28.21%  |
| Solus 4.0    | 17        | 14.53%  |
| Solus 4.2    | 13        | 11.11%  |
| Solus 4.4    | 8         | 6.84%   |
| Solus 4.5    | 6         | 5.13%   |
| Solus 3.9999 | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Solus | 113       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 9         | 7.44%   |
| 5.13.1-187.current  | 6         | 4.96%   |
| 5.6.4-152.current   | 5         | 4.13%   |
| 5.6.19-159.current  | 5         | 4.13%   |
| 5.6.13-153.current  | 4         | 3.31%   |
| 5.5.7-150.current   | 4         | 3.31%   |
| 5.15.50-216.current | 4         | 3.31%   |
| 6.6.21-280.current  | 3         | 2.48%   |
| 6.3.8-240.current   | 3         | 2.48%   |
| 5.3.7-132.current   | 3         | 2.48%   |
| 5.2.20-130.current  | 3         | 2.48%   |
| 5.15.32-213.current | 3         | 2.48%   |
| 5.14.21-210.current | 3         | 2.48%   |
| 5.11.22-180.current | 3         | 2.48%   |
| 6.1.5-229.current   | 2         | 1.65%   |
| 6.0.11-225.current  | 2         | 1.65%   |
| 5.6.18-156.current  | 2         | 1.65%   |
| 5.5.4-148.current   | 2         | 1.65%   |
| 5.5.11-151.current  | 2         | 1.65%   |
| 5.4.12-144.current  | 2         | 1.65%   |
| 5.3.15-138.current  | 2         | 1.65%   |
| 5.3.10-134.current  | 2         | 1.65%   |
| 5.2.2-122.current   | 2         | 1.65%   |
| 5.15.77-219.current | 2         | 1.65%   |
| 5.14.16-205.current | 2         | 1.65%   |
| 5.13.6-190.current  | 2         | 1.65%   |
| 5.13.12-193.current | 2         | 1.65%   |
| 5.12.10-182.current | 2         | 1.65%   |
| 5.11.9-176.current  | 2         | 1.65%   |
| 5.11.12-177.current | 2         | 1.65%   |
| 5.10.12-171.current | 2         | 1.65%   |
| 6.6.9-269.current   | 1         | 0.83%   |
| 6.6.8-268.current   | 1         | 0.83%   |
| 6.6.22-281.current  | 1         | 0.83%   |
| 6.4.15-254.current  | 1         | 0.83%   |
| 6.3.12-244.current  | 1         | 0.83%   |
| 6.3.12-241.current  | 1         | 0.83%   |
| 6.1.2-228.current   | 1         | 0.83%   |
| 5.6.18-155.current  | 1         | 0.83%   |
| 5.5.3-147.current   | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6.19  | 14        | 11.57%  |
| 5.13.1  | 6         | 4.96%   |
| 5.6.4   | 5         | 4.13%   |
| 5.6.13  | 4         | 3.31%   |
| 5.5.7   | 4         | 3.31%   |
| 5.15.50 | 4         | 3.31%   |
| 6.6.21  | 3         | 2.48%   |
| 6.3.8   | 3         | 2.48%   |
| 5.6.18  | 3         | 2.48%   |
| 5.4.12  | 3         | 2.48%   |
| 5.3.7   | 3         | 2.48%   |
| 5.2.20  | 3         | 2.48%   |
| 5.15.32 | 3         | 2.48%   |
| 5.14.21 | 3         | 2.48%   |
| 5.14.16 | 3         | 2.48%   |
| 5.11.22 | 3         | 2.48%   |
| 6.3.12  | 2         | 1.65%   |
| 6.1.5   | 2         | 1.65%   |
| 6.0.11  | 2         | 1.65%   |
| 5.5.4   | 2         | 1.65%   |
| 5.5.11  | 2         | 1.65%   |
| 5.3.15  | 2         | 1.65%   |
| 5.3.10  | 2         | 1.65%   |
| 5.2.2   | 2         | 1.65%   |
| 5.15.77 | 2         | 1.65%   |
| 5.13.6  | 2         | 1.65%   |
| 5.13.12 | 2         | 1.65%   |
| 5.12.10 | 2         | 1.65%   |
| 5.11.9  | 2         | 1.65%   |
| 5.11.12 | 2         | 1.65%   |
| 5.10.12 | 2         | 1.65%   |
| 6.6.9   | 1         | 0.83%   |
| 6.6.8   | 1         | 0.83%   |
| 6.6.22  | 1         | 0.83%   |
| 6.4.15  | 1         | 0.83%   |
| 6.1.2   | 1         | 0.83%   |
| 5.5.3   | 1         | 0.83%   |
| 5.4.1   | 1         | 0.83%   |
| 5.2.13  | 1         | 0.83%   |
| 5.15.61 | 1         | 0.83%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6     | 26        | 21.67%  |
| 5.15    | 13        | 10.83%  |
| 5.13    | 12        | 10%     |
| 5.5     | 9         | 7.5%    |
| 5.14    | 9         | 7.5%    |
| 5.3     | 7         | 5.83%   |
| 6.6     | 6         | 5%      |
| 5.2     | 6         | 5%      |
| 5.11    | 6         | 5%      |
| 6.3     | 5         | 4.17%   |
| 5.10    | 5         | 4.17%   |
| 5.4     | 4         | 3.33%   |
| 6.1     | 3         | 2.5%    |
| 6.0     | 2         | 1.67%   |
| 5.12    | 2         | 1.67%   |
| 6.4     | 1         | 0.83%   |
| 5.0     | 1         | 0.83%   |
| 4.20    | 1         | 0.83%   |
| 4.18    | 1         | 0.83%   |
| 4.14    | 1         | 0.83%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 113       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 58        | 49.57%  |
| Unknown | 23        | 19.66%  |
| MATE    | 11        | 9.4%    |
| KDE     | 10        | 8.55%   |
| GNOME   | 8         | 6.84%   |
| KDE5    | 7         | 5.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 111       | 98.23%  |
| Wayland | 2         | 1.77%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 68.7%   |
| LightDM | 15        | 13.04%  |
| TDM     | 12        | 10.43%  |
| SDDM    | 5         | 4.35%   |
| GDM     | 4         | 3.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 63        | 55.26%  |
| Unknown | 10        | 8.77%   |
| en_GB   | 6         | 5.26%   |
| de_DE   | 5         | 4.39%   |
| it_IT   | 4         | 3.51%   |
| pt_BR   | 3         | 2.63%   |
| pl_PL   | 3         | 2.63%   |
| fr_FR   | 3         | 2.63%   |
| es_ES   | 3         | 2.63%   |
| en_AU   | 3         | 2.63%   |
| tr_TR   | 2         | 1.75%   |
| en_NZ   | 2         | 1.75%   |
| uk_UA   | 1         | 0.88%   |
| ru_RU   | 1         | 0.88%   |
| fi_FI   | 1         | 0.88%   |
| es_CL   | 1         | 0.88%   |
| en_IN   | 1         | 0.88%   |
| en_CA   | 1         | 0.88%   |
| de_AT   | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 71        | 61.74%  |
| BIOS | 44        | 38.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 99        | 86.84%  |
| Unknown | 8         | 7.02%   |
| Tmpfs   | 4         | 3.51%   |
| Overlay | 3         | 2.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 68        | 59.13%  |
| GPT     | 37        | 32.17%  |
| MBR     | 10        | 8.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 103       | 91.15%  |
| Yes       | 10        | 8.85%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 84.07%  |
| Yes       | 18        | 15.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Dell                   | 20        | 17.7%   |
| Lenovo                 | 19        | 16.81%  |
| Hewlett-Packard        | 16        | 14.16%  |
| Acer                   | 16        | 14.16%  |
| ASUSTek Computer       | 8         | 7.08%   |
| Toshiba                | 6         | 5.31%   |
| Google                 | 4         | 3.54%   |
| Sony                   | 3         | 2.65%   |
| Samsung Electronics    | 3         | 2.65%   |
| Packard Bell           | 3         | 2.65%   |
| Apple                  | 3         | 2.65%   |
| Valve                  | 1         | 0.88%   |
| Timi                   | 1         | 0.88%   |
| Panasonic              | 1         | 0.88%   |
| MSI                    | 1         | 0.88%   |
| HUAWEI                 | 1         | 0.88%   |
| Howard Computers       | 1         | 0.88%   |
| GPU Company            | 1         | 0.88%   |
| Gigabyte Technology    | 1         | 0.88%   |
| Framework              | 1         | 0.88%   |
| Chuwi                  | 1         | 0.88%   |
| AZW                    | 1         | 0.88%   |
| Avell High Performance | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G5                                     | 2         | 1.77%   |
| Google Kip                                            | 2         | 1.77%   |
| Dell Latitude E5470                                   | 2         | 1.77%   |
| Acer Nitro AN515-45                                   | 2         | 1.77%   |
| Acer Aspire E5-575G                                   | 2         | 1.77%   |
| Valve Jupiter                                         | 1         | 0.88%   |
| Toshiba TECRA R840                                    | 1         | 0.88%   |
| Toshiba Satellite P50-A                               | 1         | 0.88%   |
| Toshiba Satellite L855                                | 1         | 0.88%   |
| Toshiba Satellite L655                                | 1         | 0.88%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 0.88%   |
| Timi TM1701                                           | 1         | 0.88%   |
| Sony VPCYB15AB                                        | 1         | 0.88%   |
| Sony VPCF236FM                                        | 1         | 0.88%   |
| Sony VPCEB1S1E                                        | 1         | 0.88%   |
| Samsung R430/P430/R480                                | 1         | 0.88%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.88%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 0.88%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 0.88%   |
| Packard Bell EasyNote TS11HR                          | 1         | 0.88%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.88%   |
| Packard Bell EasyNote MH36                            | 1         | 0.88%   |
| MSI Modern 14 B5M                                     | 1         | 0.88%   |
| Lenovo Z51-70 80K6                                    | 1         | 0.88%   |
| Lenovo Z50-70 20354                                   | 1         | 0.88%   |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 0.88%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 0.88%   |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 0.88%   |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 0.88%   |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 0.88%   |
| Lenovo ThinkPad T410 253725G                          | 1         | 0.88%   |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 0.88%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 0.88%   |
| Lenovo ThinkPad T14 Gen 1 20S00013FR                  | 1         | 0.88%   |
| Lenovo ThinkPad Edge E440 20C5A03300                  | 1         | 0.88%   |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 0.88%   |
| Lenovo IdeaPad S340-15API 81NC                        | 1         | 0.88%   |
| Lenovo IdeaPad 530S-14ARR 81H1                        | 1         | 0.88%   |
| Lenovo IdeaPad 5 15ALC05 82LN                         | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 11        | 9.73%   |
| Acer Aspire            | 10        | 8.85%   |
| Dell Latitude          | 8         | 7.08%   |
| Dell Inspiron          | 6         | 5.31%   |
| Lenovo IdeaPad         | 5         | 4.42%   |
| HP ProBook             | 5         | 4.42%   |
| HP Pavilion            | 4         | 3.54%   |
| Dell XPS               | 4         | 3.54%   |
| Toshiba Satellite      | 3         | 2.65%   |
| Packard Bell EasyNote  | 3         | 2.65%   |
| Acer Swift             | 3         | 2.65%   |
| HP EliteBook           | 2         | 1.77%   |
| Google Kip             | 2         | 1.77%   |
| Dell Vostro            | 2         | 1.77%   |
| ASUS VivoBook          | 2         | 1.77%   |
| Acer Nitro             | 2         | 1.77%   |
| Valve Jupiter          | 1         | 0.88%   |
| Toshiba TECRA          | 1         | 0.88%   |
| Toshiba PORTEGE        | 1         | 0.88%   |
| Timi TM1701            | 1         | 0.88%   |
| Sony VPCYB15AB         | 1         | 0.88%   |
| Sony VPCF236FM         | 1         | 0.88%   |
| Sony VPCEB1S1E         | 1         | 0.88%   |
| Samsung R430           | 1         | 0.88%   |
| Samsung 300E5EV        | 1         | 0.88%   |
| Samsung 270E5K         | 1         | 0.88%   |
| Panasonic CF-C2CCEZXCM | 1         | 0.88%   |
| MSI Modern             | 1         | 0.88%   |
| Lenovo Z51-70          | 1         | 0.88%   |
| Lenovo Z50-70          | 1         | 0.88%   |
| Lenovo Legion          | 1         | 0.88%   |
| HUAWEI BOD-WXX9        | 1         | 0.88%   |
| Howard Computers W350  | 1         | 0.88%   |
| HP Stream              | 1         | 0.88%   |
| HP Presario            | 1         | 0.88%   |
| HP OMEN                | 1         | 0.88%   |
| HP ENVY                | 1         | 0.88%   |
| HP 255                 | 1         | 0.88%   |
| GPU Company GWTC116-2  | 1         | 0.88%   |
| Google Edgar           | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 12        | 10.62%  |
| 2016 | 12        | 10.62%  |
| 2021 | 11        | 9.73%   |
| 2017 | 10        | 8.85%   |
| 2012 | 10        | 8.85%   |
| 2019 | 9         | 7.96%   |
| 2014 | 7         | 6.19%   |
| 2020 | 6         | 5.31%   |
| 2013 | 6         | 5.31%   |
| 2011 | 6         | 5.31%   |
| 2008 | 6         | 5.31%   |
| 2015 | 5         | 4.42%   |
| 2010 | 5         | 4.42%   |
| 2009 | 5         | 4.42%   |
| 2023 | 1         | 0.88%   |
| 2022 | 1         | 0.88%   |
| 2007 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 113       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 110       | 97.35%  |
| Enabled  | 3         | 2.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 96.46%  |
| Yes  | 4         | 3.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 30        | 26.32%  |
| 8.01-16.0   | 27        | 23.68%  |
| 4.01-8.0    | 23        | 20.18%  |
| 16.01-24.0  | 20        | 17.54%  |
| 32.01-64.0  | 7         | 6.14%   |
| 1.01-2.0    | 3         | 2.63%   |
| 2.01-3.0    | 2         | 1.75%   |
| 24.01-32.0  | 1         | 0.88%   |
| 64.01-256.0 | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 42        | 35.29%  |
| 2.01-3.0  | 37        | 31.09%  |
| 4.01-8.0  | 15        | 12.61%  |
| 3.01-4.0  | 14        | 11.76%  |
| 0.51-1.0  | 9         | 7.56%   |
| 8.01-16.0 | 2         | 1.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 75.22%  |
| 2      | 27        | 23.89%  |
| 3      | 1         | 0.88%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 61.95%  |
| Yes       | 43        | 38.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 79.65%  |
| No        | 23        | 20.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 79.65%  |
| No        | 23        | 20.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 23        | 20.35%  |
| India              | 8         | 7.08%   |
| Netherlands        | 7         | 6.19%   |
| Brazil             | 7         | 6.19%   |
| Poland             | 4         | 3.54%   |
| Germany            | 4         | 3.54%   |
| UK                 | 3         | 2.65%   |
| Spain              | 3         | 2.65%   |
| Russia             | 3         | 2.65%   |
| Italy              | 3         | 2.65%   |
| France             | 3         | 2.65%   |
| Chile              | 3         | 2.65%   |
| Australia          | 3         | 2.65%   |
| Ukraine            | 2         | 1.77%   |
| Turkey             | 2         | 1.77%   |
| Norway             | 2         | 1.77%   |
| New Zealand        | 2         | 1.77%   |
| Mexico             | 2         | 1.77%   |
| Indonesia          | 2         | 1.77%   |
| Guatemala          | 2         | 1.77%   |
| Finland            | 2         | 1.77%   |
| China              | 2         | 1.77%   |
| Austria            | 2         | 1.77%   |
| Vietnam            | 1         | 0.88%   |
| Venezuela          | 1         | 0.88%   |
| Switzerland        | 1         | 0.88%   |
| Sweden             | 1         | 0.88%   |
| Saudi Arabia       | 1         | 0.88%   |
| Oman               | 1         | 0.88%   |
| Nepal              | 1         | 0.88%   |
| Latvia             | 1         | 0.88%   |
| Japan              | 1         | 0.88%   |
| Iran               | 1         | 0.88%   |
| Hungary            | 1         | 0.88%   |
| Greece             | 1         | 0.88%   |
| Dominican Republic | 1         | 0.88%   |
| Czechia            | 1         | 0.88%   |
| Canada             | 1         | 0.88%   |
| Belgium            | 1         | 0.88%   |
| Belarus            | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| The Hague                 | 3         | 2.52%   |
| Melbourne                 | 3         | 2.52%   |
| Vienna                    | 2         | 1.68%   |
| San Francisco del Rincón | 2         | 1.68%   |
| Oslo                      | 2         | 1.68%   |
| Hrubieszów               | 2         | 1.68%   |
| Guatemala City            | 2         | 1.68%   |
| Columbus                  | 2         | 1.68%   |
| Beijing                   | 2         | 1.68%   |
| Auckland                  | 2         | 1.68%   |
| Amsterdam                 | 2         | 1.68%   |
| Zhytomyr                  | 1         | 0.84%   |
| Yverdon-les-Bains         | 1         | 0.84%   |
| Wendell                   | 1         | 0.84%   |
| Vineland                  | 1         | 0.84%   |
| Vasco da Gama             | 1         | 0.84%   |
| Uberlândia               | 1         | 0.84%   |
| Toronto                   | 1         | 0.84%   |
| Tirana                    | 1         | 0.84%   |
| Terranuova Bracciolini    | 1         | 0.84%   |
| Teresopolis               | 1         | 0.84%   |
| Tehran                    | 1         | 0.84%   |
| Stroudsburg               | 1         | 0.84%   |
| Stare Babice              | 1         | 0.84%   |
| St Petersburg             | 1         | 0.84%   |
| Severna Park              | 1         | 0.84%   |
| Semarang                  | 1         | 0.84%   |
| Santo Domingo Este        | 1         | 0.84%   |
| Santiago                  | 1         | 0.84%   |
| San Justo                 | 1         | 0.84%   |
| San Francisco             | 1         | 0.84%   |
| Saint-Just-Saint-Rambert  | 1         | 0.84%   |
| Saint Paul                | 1         | 0.84%   |
| Riyadh                    | 1         | 0.84%   |
| Riga                      | 1         | 0.84%   |
| Red Oak                   | 1         | 0.84%   |
| Quilicura                 | 1         | 0.84%   |
| Portland                  | 1         | 0.84%   |
| Port Orange               | 1         | 0.84%   |
| Pomeroy                   | 1         | 0.84%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 18        | 19     | 12.77%  |
| Toshiba                   | 16        | 19     | 11.35%  |
| Samsung Electronics       | 15        | 16     | 10.64%  |
| Seagate                   | 12        | 15     | 8.51%   |
| SanDisk                   | 11        | 13     | 7.8%    |
| SK hynix                  | 10        | 10     | 7.09%   |
| Kingston                  | 9         | 9      | 6.38%   |
| Unknown                   | 8         | 8      | 5.67%   |
| Intel                     | 7         | 9      | 4.96%   |
| Micron Technology         | 5         | 6      | 3.55%   |
| Hitachi                   | 3         | 3      | 2.13%   |
| Crucial                   | 3         | 4      | 2.13%   |
| Silicon Motion            | 2         | 2      | 1.42%   |
| HGST                      | 2         | 2      | 1.42%   |
| Gigabyte Technology       | 2         | 2      | 1.42%   |
| Apple                     | 2         | 2      | 1.42%   |
| A-DATA Technology         | 2         | 2      | 1.42%   |
| Transcend                 | 1         | 1      | 0.71%   |
| SABRENT                   | 1         | 1      | 0.71%   |
| PNY                       | 1         | 1      | 0.71%   |
| Phison Electronics        | 1         | 1      | 0.71%   |
| Phison                    | 1         | 1      | 0.71%   |
| Patriot                   | 1         | 1      | 0.71%   |
| O2 Micro                  | 1         | 1      | 0.71%   |
| Micron/Crucial Technology | 1         | 1      | 0.71%   |
| Lenovo                    | 1         | 1      | 0.71%   |
| KIOXIA                    | 1         | 1      | 0.71%   |
| KingFast                  | 1         | 1      | 0.71%   |
| FORESEE                   | 1         | 1      | 0.71%   |
| Advantech                 | 1         | 1      | 0.71%   |
| AAPL                      | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 5         | 3.47%   |
| Unknown MMC Card  32GB                  | 3         | 2.08%   |
| SK hynix NVMe SSD Drive 128GB           | 3         | 2.08%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 2.08%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 2.08%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 2         | 1.39%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 1.39%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.39%   |
| Unknown MMC Card  128GB                 | 2         | 1.39%   |
| SK hynix SC311 SATA 256GB SSD           | 2         | 1.39%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.39%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.69%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.69%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.69%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 0.69%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 0.69%   |
| WDC WD2500LPVX-22V0TT0 250GB            | 1         | 0.69%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.69%   |
| WDC WD2500BEVT-00A23T0 250GB            | 1         | 0.69%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.69%   |
| WDC WD10JPVX-08JC3T5 1TB                | 1         | 0.69%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.69%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB    | 1         | 0.69%   |
| Unknown USB DISK 3.2 1TB                | 1         | 0.69%   |
| Unknown MMC Card  64GB                  | 1         | 0.69%   |
| Unknown AJNB4R  16GB                    | 1         | 0.69%   |
| Transcend TS240GSSD220S 240GB           | 1         | 0.69%   |
| Toshiba THNSNJ256GVNU 256GB SSD         | 1         | 0.69%   |
| Toshiba THNS128GG4BNAA 128GB SSD        | 1         | 0.69%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.69%   |
| Toshiba NVMe SSD Drive 256GB            | 1         | 0.69%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.69%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.69%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.69%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.69%   |
| Toshiba MK7559GSXP 752GB                | 1         | 0.69%   |
| Toshiba MK5055GSX 500GB                 | 1         | 0.69%   |
| Toshiba KXG60ZNV512G NVMe 512GB         | 1         | 0.69%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB | 1         | 0.69%   |
| SK hynix NVMe SSD Drive 500GB           | 1         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 15     | 32.56%  |
| Seagate | 12        | 15     | 27.91%  |
| Toshiba | 10        | 13     | 23.26%  |
| Hitachi | 3         | 3      | 6.98%   |
| HGST    | 2         | 2      | 4.65%   |
| SABRENT | 1         | 1      | 2.33%   |
| AAPL    | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 20%     |
| Kingston            | 6         | 6      | 13.33%  |
| SanDisk             | 4         | 4      | 8.89%   |
| Micron Technology   | 4         | 5      | 8.89%   |
| SK hynix            | 3         | 3      | 6.67%   |
| Intel               | 3         | 4      | 6.67%   |
| Crucial             | 3         | 4      | 6.67%   |
| WDC                 | 2         | 2      | 4.44%   |
| Toshiba             | 2         | 2      | 4.44%   |
| Gigabyte Technology | 2         | 2      | 4.44%   |
| Apple               | 2         | 2      | 4.44%   |
| Transcend           | 1         | 1      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| Patriot             | 1         | 1      | 2.22%   |
| FORESEE             | 1         | 1      | 2.22%   |
| Advantech           | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 42        | 48     | 31.58%  |
| HDD     | 42        | 50     | 31.58%  |
| NVMe    | 39        | 47     | 29.32%  |
| MMC     | 8         | 8      | 6.02%   |
| Unknown | 2         | 2      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 95     | 58.73%  |
| NVMe | 39        | 47     | 30.95%  |
| MMC  | 8         | 8      | 6.35%   |
| SAS  | 5         | 5      | 3.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 55        | 67     | 67.07%  |
| 0.51-1.0   | 25        | 29     | 30.49%  |
| 1.01-2.0   | 2         | 2      | 2.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 48        | 42.11%  |
| 251-500    | 26        | 22.81%  |
| 501-1000   | 15        | 13.16%  |
| 1001-2000  | 7         | 6.14%   |
| 21-50      | 5         | 4.39%   |
| 51-100     | 5         | 4.39%   |
| Unknown    | 5         | 4.39%   |
| 1-20       | 2         | 1.75%   |
| 2001-3000  | 1         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 45        | 37.82%  |
| 21-50     | 25        | 21.01%  |
| 51-100    | 15        | 12.61%  |
| 101-250   | 13        | 10.92%  |
| 251-500   | 11        | 9.24%   |
| Unknown   | 5         | 4.2%    |
| 1001-2000 | 3         | 2.52%   |
| 501-1000  | 2         | 1.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB                    | 1         | 1      | 16.67%  |
| Toshiba MK7559GSXP 752GB                       | 1         | 1      | 16.67%  |
| Seagate ST9320325AS 320GB                      | 1         | 2      | 16.67%  |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB   | 1         | 1      | 16.67%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 16.67%  |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 16.67%  |
| Toshiba             | 1         | 1      | 16.67%  |
| Seagate             | 1         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Micron Technology   | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 2      | 25%     |
| Hitachi | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 5      | 66.67%  |
| NVMe | 1         | 1      | 16.67%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Detected | 77        | 106    | 64.71%  |
| Works    | 36        | 42     | 30.25%  |
| Malfunc  | 6         | 7      | 5.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 80        | 60.15%  |
| AMD                          | 12        | 9.02%   |
| SK hynix                     | 7         | 5.26%   |
| SanDisk                      | 7         | 5.26%   |
| Samsung Electronics          | 7         | 5.26%   |
| Toshiba America Info Systems | 5         | 3.76%   |
| Kingston Technology Company  | 3         | 2.26%   |
| Silicon Motion               | 2         | 1.5%    |
| Phison Electronics           | 2         | 1.5%    |
| ADATA Technology             | 2         | 1.5%    |
| O2 Micro                     | 1         | 0.75%   |
| Nvidia                       | 1         | 0.75%   |
| Micron/Crucial Technology    | 1         | 0.75%   |
| Micron Technology            | 1         | 0.75%   |
| Lenovo                       | 1         | 0.75%   |
| JMicron Technology           | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 14        | 10.22%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 8.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 6.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 5.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 4.38%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 4.38%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 3.65%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 2.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.19%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.19%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.46%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 1.46%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 2         | 1.46%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 1.46%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 1.46%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 2         | 1.46%   |
| Intel SSD 600P Series                                                          | 2         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.46%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.73%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.73%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.73%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.73%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.73%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 1         | 0.73%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 1         | 0.73%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.73%   |
| O2 Micro FORESEE E2M2 NVMe SSD                                                 | 1         | 0.73%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 84        | 64.12%  |
| NVMe | 38        | 29.01%  |
| RAID | 5         | 3.82%   |
| IDE  | 4         | 3.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 97        | 85.84%  |
| AMD    | 16        | 14.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 5.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 4.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 2.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.65%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 2.65%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 1.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.77%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 1.77%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 1.77%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 1.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.77%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 1.77%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 1.77%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.77%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 1.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.77%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.77%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.88%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.88%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.88%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.88%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 0.88%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 0.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.88%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.88%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.88%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.88%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.88%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.88%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.88%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 32.74%  |
| Intel Core i7           | 25        | 22.12%  |
| Intel Celeron           | 9         | 7.96%   |
| Other                   | 7         | 6.19%   |
| Intel Core i3           | 6         | 5.31%   |
| AMD Ryzen 7             | 6         | 5.31%   |
| AMD Ryzen 5             | 6         | 5.31%   |
| Intel Core 2 Duo        | 5         | 4.42%   |
| Intel Pentium Dual-Core | 3         | 2.65%   |
| Intel Pentium           | 3         | 2.65%   |
| Intel Pentium Silver    | 1         | 0.88%   |
| Intel Pentium Dual      | 1         | 0.88%   |
| Intel Core M            | 1         | 0.88%   |
| Intel Atom              | 1         | 0.88%   |
| AMD E1                  | 1         | 0.88%   |
| AMD E                   | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 55.75%  |
| 4      | 39        | 34.51%  |
| 6      | 7         | 6.19%   |
| 8      | 3         | 2.65%   |
| 1      | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 86        | 76.11%  |
| 1      | 27        | 23.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 95.61%  |
| Unknown        | 5         | 4.39%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 13.91%  |
| 0x806ea    | 9         | 7.83%   |
| 0x306a9    | 8         | 6.96%   |
| 0x806e9    | 7         | 6.09%   |
| 0x206a7    | 7         | 6.09%   |
| 0x40651    | 5         | 4.35%   |
| 0x806ec    | 4         | 3.48%   |
| 0x806c1    | 4         | 3.48%   |
| 0x306c3    | 4         | 3.48%   |
| 0x20655    | 4         | 3.48%   |
| 0x1067a    | 4         | 3.48%   |
| 0x906ea    | 3         | 2.61%   |
| 0x906e9    | 3         | 2.61%   |
| 0x706a1    | 3         | 2.61%   |
| 0x406e3    | 3         | 2.61%   |
| 0x306d4    | 3         | 2.61%   |
| 0x0a50000c | 3         | 2.61%   |
| 0x08108102 | 3         | 2.61%   |
| 0x6fd      | 2         | 1.74%   |
| 0x506e3    | 2         | 1.74%   |
| 0x30678    | 2         | 1.74%   |
| 0x0810100b | 2         | 1.74%   |
| 0xa0652    | 1         | 0.87%   |
| 0x906c0    | 1         | 0.87%   |
| 0x806eb    | 1         | 0.87%   |
| 0x706a8    | 1         | 0.87%   |
| 0x20652    | 1         | 0.87%   |
| 0x10676    | 1         | 0.87%   |
| 0x10661    | 1         | 0.87%   |
| 0x08900201 | 1         | 0.87%   |
| 0x08608103 | 1         | 0.87%   |
| 0x08600106 | 1         | 0.87%   |
| 0x08108109 | 1         | 0.87%   |
| 0x06006704 | 1         | 0.87%   |
| 0x05000119 | 1         | 0.87%   |
| 0x05000029 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 25.66%  |
| Haswell       | 10        | 8.85%   |
| SandyBridge   | 9         | 7.96%   |
| IvyBridge     | 8         | 7.08%   |
| Penryn        | 7         | 6.19%   |
| Westmere      | 6         | 5.31%   |
| Skylake       | 6         | 5.31%   |
| TigerLake     | 5         | 4.42%   |
| Zen+          | 4         | 3.54%   |
| Silvermont    | 4         | 3.54%   |
| Goldmont plus | 4         | 3.54%   |
| Broadwell     | 4         | 3.54%   |
| Zen 3         | 3         | 2.65%   |
| Core          | 3         | 2.65%   |
| Unknown       | 3         | 2.65%   |
| Zen           | 2         | 1.77%   |
| Bobcat        | 2         | 1.77%   |
| Zen 2         | 1         | 0.88%   |
| Tremont       | 1         | 0.88%   |
| Excavator     | 1         | 0.88%   |
| CometLake     | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 60.27%  |
| Nvidia | 32        | 21.92%  |
| AMD    | 26        | 17.81%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 9         | 6.08%   |
| Intel HD Graphics 620                                                     | 8         | 5.41%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 4.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 4.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 4         | 2.7%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 2.7%    |
| Intel Core Processor Integrated Graphics Controller                       | 4         | 2.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.7%    |
| Nvidia GM108M [GeForce 940MX]                                             | 3         | 2.03%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 3         | 2.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 3         | 2.03%   |
| Intel HD Graphics 630                                                     | 3         | 2.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.35%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.35%   |
| Nvidia GM108M [GeForce 930MX]                                             | 2         | 1.35%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.35%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 2         | 1.35%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.35%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.35%   |
| Intel HD Graphics 5500                                                    | 2         | 1.35%   |
| Intel HD Graphics 530                                                     | 2         | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.35%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                  | 2         | 1.35%   |
| AMD Lucienne                                                              | 2         | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.68%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 60        | 53.1%   |
| Intel + Nvidia | 24        | 21.24%  |
| 1 x AMD        | 17        | 15.04%  |
| AMD + Nvidia   | 5         | 4.42%   |
| Intel + AMD    | 4         | 3.54%   |
| 1 x Nvidia     | 3         | 2.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 94        | 83.19%  |
| Proprietary | 19        | 16.81%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 55.75%  |
| 1.01-2.0   | 17        | 15.04%  |
| 0.01-0.5   | 12        | 10.62%  |
| 0.51-1.0   | 11        | 9.73%   |
| 3.01-4.0   | 7         | 6.19%   |
| 5.01-6.0   | 3         | 2.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 21.48%  |
| BOE                     | 18        | 13.33%  |
| LG Display              | 16        | 11.85%  |
| Samsung Electronics     | 15        | 11.11%  |
| Chimei Innolux          | 15        | 11.11%  |
| Lenovo                  | 6         | 4.44%   |
| Goldstar                | 4         | 2.96%   |
| Sharp                   | 3         | 2.22%   |
| Dell                    | 3         | 2.22%   |
| Chi Mei Optoelectronics | 3         | 2.22%   |
| Apple                   | 3         | 2.22%   |
| AOC                     | 3         | 2.22%   |
| PANDA                   | 2         | 1.48%   |
| BenQ                    | 2         | 1.48%   |
| Ancor Communications    | 2         | 1.48%   |
| ___                     | 1         | 0.74%   |
| Valve                   | 1         | 0.74%   |
| Unknown                 | 1         | 0.74%   |
| Toshiba                 | 1         | 0.74%   |
| Sony                    | 1         | 0.74%   |
| Philips                 | 1         | 0.74%   |
| LG Philips              | 1         | 0.74%   |
| GKK                     | 1         | 0.74%   |
| CSO                     | 1         | 0.74%   |
| CPT                     | 1         | 0.74%   |
| Acer                    | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 2         | 1.47%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 2         | 1.47%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                 | 2         | 1.47%   |
| BOE LCD Monitor BOE0638 1920x1080 309x173mm 13.9-inch                 | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.47%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.74%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.74%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.74%   |
| Toshiba Internal LCD TOS5091 1366x768 309x174mm 14.0-inch             | 1         | 0.74%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.74%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.74%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch  | 1         | 0.74%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4250 1920x1080 276x156mm 12.5-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.74%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.74%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch     | 1         | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.74%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                 | 1         | 0.74%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.74%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.74%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 1         | 0.74%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.74%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 59        | 46.83%  |
| 1366x768 (WXGA)    | 36        | 28.57%  |
| 1600x900 (HD+)     | 7         | 5.56%   |
| 1440x900 (WXGA+)   | 5         | 3.97%   |
| 1280x800 (WXGA)    | 4         | 3.17%   |
| 3840x2160 (4K)     | 3         | 2.38%   |
| 2560x1440 (QHD)    | 3         | 2.38%   |
| 2560x1600          | 2         | 1.59%   |
| 800x1280           | 1         | 0.79%   |
| 3840x1080          | 1         | 0.79%   |
| 2560x1080          | 1         | 0.79%   |
| 2256x1504          | 1         | 0.79%   |
| 1920x1200 (WUXGA)  | 1         | 0.79%   |
| 1680x1050 (WSXGA+) | 1         | 0.79%   |
| 1360x768           | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 58        | 43.28%  |
| 13      | 25        | 18.66%  |
| 14      | 16        | 11.94%  |
| 17      | 7         | 5.22%   |
| 24      | 5         | 3.73%   |
| 23      | 4         | 2.99%   |
| 21      | 4         | 2.99%   |
| 27      | 2         | 1.49%   |
| 12      | 2         | 1.49%   |
| 11      | 2         | 1.49%   |
| 72      | 1         | 0.75%   |
| 49      | 1         | 0.75%   |
| 40      | 1         | 0.75%   |
| 34      | 1         | 0.75%   |
| 31      | 1         | 0.75%   |
| 18      | 1         | 0.75%   |
| 16      | 1         | 0.75%   |
| 7       | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 64.66%  |
| 201-300     | 14        | 10.53%  |
| 501-600     | 10        | 7.52%   |
| 351-400     | 10        | 7.52%   |
| 401-500     | 6         | 4.51%   |
| 801-900     | 1         | 0.75%   |
| 701-800     | 1         | 0.75%   |
| 601-700     | 1         | 0.75%   |
| 1501-2000   | 1         | 0.75%   |
| 1001-1500   | 1         | 0.75%   |
| 1-100       | 1         | 0.75%   |
| Unknown     | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 101       | 86.32%  |
| 16/10 | 11        | 9.4%    |
| 3/2   | 2         | 1.71%   |
| 32/9  | 1         | 0.85%   |
| 21/9  | 1         | 0.85%   |
| 0.67  | 1         | 0.85%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 57        | 42.54%  |
| 81-90          | 34        | 25.37%  |
| 201-250        | 10        | 7.46%   |
| 71-80          | 7         | 5.22%   |
| 121-130        | 7         | 5.22%   |
| 61-70          | 2         | 1.49%   |
| 51-60          | 2         | 1.49%   |
| 351-500        | 2         | 1.49%   |
| 301-350        | 2         | 1.49%   |
| 251-300        | 2         | 1.49%   |
| 501-1000       | 2         | 1.49%   |
| More than 1000 | 1         | 0.75%   |
| 1-40           | 1         | 0.75%   |
| 151-200        | 1         | 0.75%   |
| 141-150        | 1         | 0.75%   |
| 111-120        | 1         | 0.75%   |
| 91-100         | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 43.08%  |
| 101-120       | 37        | 28.46%  |
| 51-100        | 22        | 16.92%  |
| 161-240       | 10        | 7.69%   |
| More than 240 | 3         | 2.31%   |
| 1-50          | 1         | 0.77%   |
| Unknown       | 1         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 93        | 81.58%  |
| 2     | 19        | 16.67%  |
| 3     | 2         | 1.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 59        | 32.42%  |
| Realtek Semiconductor         | 52        | 28.57%  |
| Qualcomm Atheros              | 31        | 17.03%  |
| Broadcom                      | 12        | 6.59%   |
| MediaTek                      | 4         | 2.2%    |
| Marvell Technology Group      | 4         | 2.2%    |
| Ralink                        | 3         | 1.65%   |
| Dell                          | 2         | 1.1%    |
| Xiaomi                        | 1         | 0.55%   |
| TP-Link                       | 1         | 0.55%   |
| T & A Mobile Phones           | 1         | 0.55%   |
| Sierra Wireless               | 1         | 0.55%   |
| Samsung Electronics           | 1         | 0.55%   |
| Ralink Technology             | 1         | 0.55%   |
| Qualcomm                      | 1         | 0.55%   |
| OnePlus Technology (Shenzhen) | 1         | 0.55%   |
| Nvidia                        | 1         | 0.55%   |
| Lenovo                        | 1         | 0.55%   |
| LeEco                         | 1         | 0.55%   |
| Jolla Oy                      | 1         | 0.55%   |
| Hewlett-Packard               | 1         | 0.55%   |
| Broadcom Limited              | 1         | 0.55%   |
| ASIX Electronics              | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 15.35%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 4.19%   |
| Intel Wireless 8265 / 8275                                             | 9         | 4.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 7         | 3.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 2.79%   |
| Intel Wireless 7260                                                    | 6         | 2.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 2.33%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 1.86%   |
| Intel Wireless 8260                                                    | 4         | 1.86%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 1.4%    |
| Realtek Killer E2600 GbE Controller                                    | 3         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.4%    |
| Intel Wireless 7265                                                    | 3         | 1.4%    |
| Intel Wireless 3165                                                    | 3         | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 2         | 0.93%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                              | 2         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 2         | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.93%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2         | 0.93%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.93%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                          | 2         | 0.93%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 2         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 2         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 0.93%   |
| Broadcom BCM4311 802.11b/g WLAN                                        | 2         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.47%   |
| T & A Mobile Phones TCL 20E                                            | 1         | 0.47%   |
| Sierra Wireless EM7305                                                 | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 49.15%  |
| Qualcomm Atheros      | 28        | 23.73%  |
| Realtek Semiconductor | 12        | 10.17%  |
| Broadcom              | 8         | 6.78%   |
| MediaTek              | 4         | 3.39%   |
| Ralink                | 3         | 2.54%   |
| Sierra Wireless       | 1         | 0.85%   |
| Ralink Technology     | 1         | 0.85%   |
| Hewlett-Packard       | 1         | 0.85%   |
| Dell                  | 1         | 0.85%   |
| Broadcom Limited      | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 7.56%   |
| Intel Wireless 8265 / 8275                                     | 9         | 7.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 5.04%   |
| Intel Wireless 7260                                            | 6         | 5.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 4.2%    |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 3.36%   |
| Intel Wireless 8260                                            | 4         | 3.36%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 2.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 2.52%   |
| Intel Wireless 7265                                            | 3         | 2.52%   |
| Intel Wireless 3165                                            | 3         | 2.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.68%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 2         | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.68%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 2         | 1.68%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 1.68%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.68%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.68%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.68%   |
| Sierra Wireless EM7305                                         | 1         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.84%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.84%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.84%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.84%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.84%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 0.84%   |
| Intel Wireless 3160                                            | 1         | 0.84%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 0.84%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.84%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 45        | 47.87%  |
| Intel                    | 25        | 26.6%   |
| Qualcomm Atheros         | 5         | 5.32%   |
| Broadcom                 | 5         | 5.32%   |
| Marvell Technology Group | 4         | 4.26%   |
| Xiaomi                   | 1         | 1.06%   |
| TP-Link                  | 1         | 1.06%   |
| T & A Mobile Phones      | 1         | 1.06%   |
| Samsung Electronics      | 1         | 1.06%   |
| Qualcomm                 | 1         | 1.06%   |
| Nvidia                   | 1         | 1.06%   |
| Lenovo                   | 1         | 1.06%   |
| LeEco                    | 1         | 1.06%   |
| Jolla Oy                 | 1         | 1.06%   |
| ASIX Electronics         | 1         | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 33        | 35.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 7.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 7.45%   |
| Realtek Killer E2600 GbE Controller                                            | 3         | 3.19%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 2.13%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 2.13%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 2.13%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 2.13%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 2.13%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 1.06%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.06%   |
| T & A Mobile Phones TCL 20E                                                    | 1         | 1.06%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.06%   |
| Qualcomm SAMSUNG_Android                                                       | 1         | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.06%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.06%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.06%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.06%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.06%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.06%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 1.06%   |
| Lenovo Thinkpad LAN                                                            | 1         | 1.06%   |
| LeEco Android                                                                  | 1         | 1.06%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 1.06%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.06%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.06%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.06%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.06%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.06%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.06%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.06%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.06%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 1.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 1.06%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 55.12%  |
| Ethernet | 90        | 43.9%   |
| Modem    | 1         | 0.49%   |
| Unknown  | 1         | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 97        | 85.09%  |
| Ethernet | 17        | 14.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 84        | 74.34%  |
| 1     | 28        | 24.78%  |
| 0     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 101       | 88.6%   |
| Yes  | 13        | 11.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 50%     |
| Qualcomm Atheros Communications | 10        | 11.11%  |
| Lite-On Technology              | 10        | 11.11%  |
| IMC Networks                    | 5         | 5.56%   |
| Realtek Semiconductor           | 4         | 4.44%   |
| Broadcom                        | 4         | 4.44%   |
| Apple                           | 3         | 3.33%   |
| Foxconn / Hon Hai               | 2         | 2.22%   |
| Dell                            | 2         | 2.22%   |
| Toshiba                         | 1         | 1.11%   |
| Ralink                          | 1         | 1.11%   |
| MediaTek                        | 1         | 1.11%   |
| Hewlett-Packard                 | 1         | 1.11%   |
| Cambridge Silicon Radio         | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 14.44%  |
| Intel Bluetooth Device                                                              | 12        | 13.33%  |
| Intel AX201 Bluetooth                                                               | 6         | 6.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 5.56%   |
| Intel AX200 Bluetooth                                                               | 5         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 3.33%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 3.33%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 2.22%   |
| Lite-On Wireless_Device                                                             | 2         | 2.22%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 2.22%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.22%   |
| Apple Bluetooth Host Controller                                                     | 2         | 2.22%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 1.11%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.11%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.11%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.11%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.11%   |
| MediaTek Wireless_Device                                                            | 1         | 1.11%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.11%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.11%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.11%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.11%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.11%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.11%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 1.11%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.11%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 1.11%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.11%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.11%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 96        | 69.57%  |
| AMD                 | 22        | 15.94%  |
| Nvidia              | 15        | 10.87%  |
| Conexant Systems    | 2         | 1.45%   |
| Samsung Electronics | 1         | 0.72%   |
| GYROCOM C&C         | 1         | 0.72%   |
| ASUSTek Computer    | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 12.88%  |
| AMD Family 17h/19h HD Audio Controller                                     | 12        | 7.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 6.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 4.29%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 4.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 3.68%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 3.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 3.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 2.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 2.45%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.45%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.84%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.84%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 1.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.23%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.23%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 1.23%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.23%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 1.23%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.61%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.61%   |
| Nvidia Audio device                                                        | 1         | 0.61%   |
| Intel Jasper Lake HD Audio                                                 | 1         | 0.61%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 28.57%  |
| SK hynix            | 11        | 17.46%  |
| Crucial             | 6         | 9.52%   |
| A-DATA Technology   | 6         | 9.52%   |
| Kingston            | 5         | 7.94%   |
| Micron Technology   | 4         | 6.35%   |
| Unknown             | 3         | 4.76%   |
| Nanya Technology    | 3         | 4.76%   |
| Ramaxel Technology  | 2         | 3.17%   |
| Elpida              | 2         | 3.17%   |
| Team                | 1         | 1.59%   |
| G.Skill             | 1         | 1.59%   |
| ChangXin Memory     | 1         | 1.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 3.13%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 3.13%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.56%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.56%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s         | 1         | 1.56%   |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 1.56%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.56%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.56%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.56%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.56%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.56%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.56%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.56%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM 1600MT/s                 | 1         | 1.56%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.56%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.56%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.56%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.56%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.56%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.56%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.56%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.56%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.56%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.56%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 1.56%   |
| Ramaxel RAM RMT3170EB68E9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.56%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 1.56%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.56%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2                    | 1         | 1.56%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.56%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 51.92%  |
| DDR3   | 15        | 28.85%  |
| LPDDR3 | 4         | 7.69%   |
| LPDDR4 | 2         | 3.85%   |
| DDR2   | 2         | 3.85%   |
| SDRAM  | 1         | 1.92%   |
| DDR    | 1         | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 46        | 92%     |
| Row Of Chips | 4         | 8%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 21        | 38.89%  |
| 4096  | 13        | 24.07%  |
| 16384 | 9         | 16.67%  |
| 2048  | 6         | 11.11%  |
| 32768 | 3         | 5.56%   |
| 1024  | 2         | 3.7%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 11        | 19.64%  |
| 1600    | 11        | 19.64%  |
| 3200    | 9         | 16.07%  |
| 2400    | 6         | 10.71%  |
| 2133    | 5         | 8.93%   |
| Unknown | 3         | 5.36%   |
| 1334    | 2         | 3.57%   |
| 4267    | 1         | 1.79%   |
| 3733    | 1         | 1.79%   |
| 3266    | 1         | 1.79%   |
| 2048    | 1         | 1.79%   |
| 1867    | 1         | 1.79%   |
| 1333    | 1         | 1.79%   |
| 1067    | 1         | 1.79%   |
| 800     | 1         | 1.79%   |
| 667     | 1         | 1.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother MFC-9330CDW | 1         | 100%    |

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
| Chicony Electronics                    | 24        | 23.3%   |
| Realtek Semiconductor                  | 13        | 12.62%  |
| IMC Networks                           | 12        | 11.65%  |
| Microdia                               | 10        | 9.71%   |
| Quanta                                 | 7         | 6.8%    |
| Sunplus Innovation Technology          | 5         | 4.85%   |
| Suyin                                  | 4         | 3.88%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.88%   |
| Bison Electronics                      | 4         | 3.88%   |
| Logitech                               | 3         | 2.91%   |
| Lite-On Technology                     | 3         | 2.91%   |
| Syntek                                 | 2         | 1.94%   |
| Lenovo                                 | 2         | 1.94%   |
| Importek                               | 2         | 1.94%   |
| Z-Star Microelectronics                | 1         | 0.97%   |
| Unknown                                | 1         | 0.97%   |
| Silicon Motion                         | 1         | 0.97%   |
| Ricoh                                  | 1         | 0.97%   |
| Microsoft                              | 1         | 0.97%   |
| Intel                                  | 1         | 0.97%   |
| Apple                                  | 1         | 0.97%   |
| Acer                                   | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                     | 7         | 6.73%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 5         | 4.81%   |
| Microdia Integrated_Webcam_HD                                         | 4         | 3.85%   |
| Chicony Integrated Camera                                             | 4         | 3.85%   |
| Sunplus Integrated_Webcam_HD                                          | 3         | 2.88%   |
| Realtek HD WebCam                                                     | 3         | 2.88%   |
| IMC Networks Integrated Camera                                        | 3         | 2.88%   |
| Suyin HP TrueVision HD Integrated Webcam                              | 2         | 1.92%   |
| Realtek Integrated_Webcam_HD                                          | 2         | 1.92%   |
| Realtek Integrated Webcam_HD                                          | 2         | 1.92%   |
| Quanta HP TrueVision HD Webcam                                        | 2         | 1.92%   |
| Quanta HD User Facing                                                 | 2         | 1.92%   |
| Microdia USB 2.0 Camera                                               | 2         | 1.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 2         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                   | 2         | 1.92%   |
| Z-Star Webcam                                                         | 1         | 0.96%   |
| Unknown ATIV VGA CAMERA                                               | 1         | 0.96%   |
| Syntek USB2.0 Camera                                                  | 1         | 0.96%   |
| Syntek Integrated Camera                                              | 1         | 0.96%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                              | 1         | 0.96%   |
| Suyin 1.3M HD WebCam                                                  | 1         | 0.96%   |
| Sunplus Laptop_Integrated_Webcam_HD                                   | 1         | 0.96%   |
| Sunplus Laptop Integrated WebCam HD                                   | 1         | 0.96%   |
| Silicon Motion WebCam SC-10HDD12636N                                  | 1         | 0.96%   |
| Ricoh USB2.0 Camera                                                   | 1         | 0.96%   |
| Realtek USB2.0 HD UVC WebCam                                          | 1         | 0.96%   |
| Realtek Laptop Camera                                                 | 1         | 0.96%   |
| Realtek Integrated Webcam HD                                          | 1         | 0.96%   |
| Realtek Integrated Webcam                                             | 1         | 0.96%   |
| Realtek Integrated Camera                                             | 1         | 0.96%   |
| Realtek Dell_Monitor_IR_Webcam                                        | 1         | 0.96%   |
| Quanta VGA WebCam                                                     | 1         | 0.96%   |
| Quanta USB2.0 HD UVC WebCam                                           | 1         | 0.96%   |
| Quanta HP Wide Vision HD Camera                                       | 1         | 0.96%   |
| Microsoft LifeCam Studio                                              | 1         | 0.96%   |
| Microdia Webcam                                                       | 1         | 0.96%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 0.96%   |
| Microdia Integrated Webcam HD                                         | 1         | 0.96%   |
| Microdia Dell Laptop Integrated Webcam HD                             | 1         | 0.96%   |
| Logitech Webcam C310                                                  | 1         | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 44%     |
| Synaptics                  | 3         | 12%     |
| Elan Microelectronics      | 3         | 12%     |
| Upek                       | 2         | 8%      |
| Shenzhen Goodix Technology | 2         | 8%      |
| LighTuning Technology      | 2         | 8%      |
| AuthenTec                  | 2         | 8%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 16%     |
| Elan ELAN:Fingerprint                                  | 3         | 12%     |
| Validity Sensors Fingerprint scanner                   | 2         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 8%      |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 8%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 8%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4%      |
| Validity Sensors VFS491                                | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4%      |
| Upek TCS5B Fingerprint sensor                          | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4%      |
| AuthenTec Fingerprint Sensor                           | 1         | 4%      |
| AuthenTec AES2810                                      | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 30%     |
| Alcor Micro | 3         | 30%     |
| Upek        | 2         | 20%     |
| O2 Micro    | 1         | 10%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 30%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 20%     |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 10%     |
| Lenovo Integrated Smart Card Reader                        | 1         | 10%     |
| Broadcom 5880                                              | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 70        | 61.95%  |
| 1     | 30        | 26.55%  |
| 2     | 13        | 11.5%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 25        | 43.1%   |
| Net/wireless          | 10        | 17.24%  |
| Chipcard              | 9         | 15.52%  |
| Multimedia controller | 5         | 8.62%   |
| Graphics card         | 4         | 6.9%    |
| Unassigned class      | 1         | 1.72%   |
| Storage               | 1         | 1.72%   |
| Net/ethernet          | 1         | 1.72%   |
| Camera                | 1         | 1.72%   |
| Bluetooth             | 1         | 1.72%   |


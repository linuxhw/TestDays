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

Total: 135

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Solus 4.1    | 39        | 39.39%  |
| Solus 4.3    | 29        | 29.29%  |
| Solus 4.0    | 17        | 17.17%  |
| Solus 4.2    | 13        | 13.13%  |
| Solus 3.9999 | 1         | 1.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Solus | 95        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 9         | 8.74%   |
| 5.6.4-152.current   | 5         | 4.85%   |
| 5.6.19-159.current  | 5         | 4.85%   |
| 5.6.13-153.current  | 4         | 3.88%   |
| 5.5.7-150.current   | 4         | 3.88%   |
| 5.15.50-216.current | 4         | 3.88%   |
| 5.13.1-187.current  | 4         | 3.88%   |
| 5.3.7-132.current   | 3         | 2.91%   |
| 5.2.20-130.current  | 3         | 2.91%   |
| 5.15.32-213.current | 3         | 2.91%   |
| 5.14.21-210.current | 3         | 2.91%   |
| 5.11.22-180.current | 3         | 2.91%   |
| 6.0.11-225.current  | 2         | 1.94%   |
| 5.6.18-156.current  | 2         | 1.94%   |
| 5.5.4-148.current   | 2         | 1.94%   |
| 5.5.11-151.current  | 2         | 1.94%   |
| 5.4.12-144.current  | 2         | 1.94%   |
| 5.3.15-138.current  | 2         | 1.94%   |
| 5.3.10-134.current  | 2         | 1.94%   |
| 5.2.2-122.current   | 2         | 1.94%   |
| 5.15.77-219.current | 2         | 1.94%   |
| 5.14.16-205.current | 2         | 1.94%   |
| 5.13.6-190.current  | 2         | 1.94%   |
| 5.13.12-193.current | 2         | 1.94%   |
| 5.12.10-182.current | 2         | 1.94%   |
| 5.11.9-176.current  | 2         | 1.94%   |
| 5.11.12-177.current | 2         | 1.94%   |
| 5.10.12-171.current | 2         | 1.94%   |
| 5.6.18-155.current  | 1         | 0.97%   |
| 5.5.3-147.current   | 1         | 0.97%   |
| 5.4.12-143.current  | 1         | 0.97%   |
| 5.4.1-137.current   | 1         | 0.97%   |
| 5.2.13-126.current  | 1         | 0.97%   |
| 5.15.61-217.current | 1         | 0.97%   |
| 5.15.37-214.current | 1         | 0.97%   |
| 5.15.26-211.current | 1         | 0.97%   |
| 5.14.7-198.current  | 1         | 0.97%   |
| 5.14.16-204.current | 1         | 0.97%   |
| 5.14.15-203.current | 1         | 0.97%   |
| 5.14.12-201.current | 1         | 0.97%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6.19  | 14        | 13.59%  |
| 5.6.4   | 5         | 4.85%   |
| 5.6.13  | 4         | 3.88%   |
| 5.5.7   | 4         | 3.88%   |
| 5.15.50 | 4         | 3.88%   |
| 5.13.1  | 4         | 3.88%   |
| 5.6.18  | 3         | 2.91%   |
| 5.4.12  | 3         | 2.91%   |
| 5.3.7   | 3         | 2.91%   |
| 5.2.20  | 3         | 2.91%   |
| 5.15.32 | 3         | 2.91%   |
| 5.14.21 | 3         | 2.91%   |
| 5.14.16 | 3         | 2.91%   |
| 5.11.22 | 3         | 2.91%   |
| 6.0.11  | 2         | 1.94%   |
| 5.5.4   | 2         | 1.94%   |
| 5.5.11  | 2         | 1.94%   |
| 5.3.15  | 2         | 1.94%   |
| 5.3.10  | 2         | 1.94%   |
| 5.2.2   | 2         | 1.94%   |
| 5.15.77 | 2         | 1.94%   |
| 5.13.6  | 2         | 1.94%   |
| 5.13.12 | 2         | 1.94%   |
| 5.12.10 | 2         | 1.94%   |
| 5.11.9  | 2         | 1.94%   |
| 5.11.12 | 2         | 1.94%   |
| 5.10.12 | 2         | 1.94%   |
| 5.5.3   | 1         | 0.97%   |
| 5.4.1   | 1         | 0.97%   |
| 5.2.13  | 1         | 0.97%   |
| 5.15.61 | 1         | 0.97%   |
| 5.15.37 | 1         | 0.97%   |
| 5.15.26 | 1         | 0.97%   |
| 5.14.7  | 1         | 0.97%   |
| 5.14.15 | 1         | 0.97%   |
| 5.14.12 | 1         | 0.97%   |
| 5.13.15 | 1         | 0.97%   |
| 5.13.0  | 1         | 0.97%   |
| 5.10.7  | 1         | 0.97%   |
| 5.10.2  | 1         | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6     | 26        | 25.49%  |
| 5.15    | 12        | 11.76%  |
| 5.13    | 10        | 9.8%    |
| 5.5     | 9         | 8.82%   |
| 5.14    | 9         | 8.82%   |
| 5.3     | 7         | 6.86%   |
| 5.2     | 6         | 5.88%   |
| 5.11    | 6         | 5.88%   |
| 5.10    | 5         | 4.9%    |
| 5.4     | 4         | 3.92%   |
| 6.0     | 2         | 1.96%   |
| 5.12    | 2         | 1.96%   |
| 5.0     | 1         | 0.98%   |
| 4.20    | 1         | 0.98%   |
| 4.18    | 1         | 0.98%   |
| 4.14    | 1         | 0.98%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 95        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 49        | 49.49%  |
| Unknown | 23        | 23.23%  |
| MATE    | 10        | 10.1%   |
| KDE     | 9         | 9.09%   |
| GNOME   | 5         | 5.05%   |
| KDE5    | 3         | 3.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 95        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 73.2%   |
| TDM     | 12        | 12.37%  |
| LightDM | 9         | 9.28%   |
| SDDM    | 4         | 4.12%   |
| GDM     | 1         | 1.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 51        | 53.13%  |
| Unknown | 10        | 10.42%  |
| en_GB   | 6         | 6.25%   |
| pt_BR   | 3         | 3.13%   |
| fr_FR   | 3         | 3.13%   |
| es_ES   | 3         | 3.13%   |
| en_AU   | 3         | 3.13%   |
| de_DE   | 3         | 3.13%   |
| tr_TR   | 2         | 2.08%   |
| pl_PL   | 2         | 2.08%   |
| it_IT   | 2         | 2.08%   |
| en_NZ   | 2         | 2.08%   |
| uk_UA   | 1         | 1.04%   |
| ru_RU   | 1         | 1.04%   |
| es_CL   | 1         | 1.04%   |
| en_IN   | 1         | 1.04%   |
| en_CA   | 1         | 1.04%   |
| de_AT   | 1         | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 60        | 61.86%  |
| BIOS | 37        | 38.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 88        | 91.67%  |
| Unknown | 7         | 7.29%   |
| Overlay | 1         | 1.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 62        | 63.92%  |
| GPT     | 28        | 28.87%  |
| MBR     | 7         | 7.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 88        | 92.63%  |
| Yes       | 7         | 7.37%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 82.11%  |
| Yes       | 17        | 17.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 16        | 16.84%  |
| Hewlett-Packard        | 16        | 16.84%  |
| Dell                   | 16        | 16.84%  |
| Acer                   | 14        | 14.74%  |
| Toshiba                | 6         | 6.32%   |
| ASUSTek Computer       | 6         | 6.32%   |
| Samsung Electronics    | 3         | 3.16%   |
| Google                 | 3         | 3.16%   |
| Sony                   | 2         | 2.11%   |
| Apple                  | 2         | 2.11%   |
| Timi                   | 1         | 1.05%   |
| Panasonic              | 1         | 1.05%   |
| Packard Bell           | 1         | 1.05%   |
| MSI                    | 1         | 1.05%   |
| Howard Computers       | 1         | 1.05%   |
| GPU Company            | 1         | 1.05%   |
| Gigabyte Technology    | 1         | 1.05%   |
| Framework              | 1         | 1.05%   |
| Chuwi                  | 1         | 1.05%   |
| AZW                    | 1         | 1.05%   |
| Avell High Performance | 1         | 1.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G5                                     | 2         | 2.11%   |
| Acer Aspire E5-575G                                   | 2         | 2.11%   |
| Toshiba TECRA R840                                    | 1         | 1.05%   |
| Toshiba Satellite P50-A                               | 1         | 1.05%   |
| Toshiba Satellite L855                                | 1         | 1.05%   |
| Toshiba Satellite L655                                | 1         | 1.05%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 1.05%   |
| Timi TM1701                                           | 1         | 1.05%   |
| Sony VPCYB15AB                                        | 1         | 1.05%   |
| Sony VPCEB1S1E                                        | 1         | 1.05%   |
| Samsung R430/P430/R480                                | 1         | 1.05%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 1.05%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 1.05%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 1.05%   |
| Packard Bell EasyNote TS11HR                          | 1         | 1.05%   |
| MSI Modern 14 B5M                                     | 1         | 1.05%   |
| Lenovo Z51-70 80K6                                    | 1         | 1.05%   |
| Lenovo Z50-70 20354                                   | 1         | 1.05%   |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 1.05%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 1.05%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 1.05%   |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 1.05%   |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 1.05%   |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 1.05%   |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 1.05%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 1.05%   |
| Lenovo ThinkPad Edge E440 20C5A03300                  | 1         | 1.05%   |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 1.05%   |
| Lenovo IdeaPad S340-15API 81NC                        | 1         | 1.05%   |
| Lenovo IdeaPad 5 15ALC05 82LN                         | 1         | 1.05%   |
| Lenovo IdeaPad 330S-15IKB 81F5                        | 1         | 1.05%   |
| Lenovo IdeaPad 320-15ISK 80XH                         | 1         | 1.05%   |
| Howard Computers W350                                 | 1         | 1.05%   |
| HP Stream Laptop 14-cb1XX                             | 1         | 1.05%   |
| HP ProBook 650 G1                                     | 1         | 1.05%   |
| HP ProBook 6470b                                      | 1         | 1.05%   |
| HP ProBook 440 G4                                     | 1         | 1.05%   |
| HP Presario C700                                      | 1         | 1.05%   |
| HP Pavilion Laptop 15-cw0xxx                          | 1         | 1.05%   |
| HP Pavilion dv7                                       | 1         | 1.05%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 9         | 9.47%   |
| Acer Aspire            | 9         | 9.47%   |
| HP ProBook             | 5         | 5.26%   |
| Dell Latitude          | 5         | 5.26%   |
| Dell Inspiron          | 5         | 5.26%   |
| Lenovo IdeaPad         | 4         | 4.21%   |
| HP Pavilion            | 4         | 4.21%   |
| Dell XPS               | 4         | 4.21%   |
| Toshiba Satellite      | 3         | 3.16%   |
| Acer Swift             | 3         | 3.16%   |
| HP EliteBook           | 2         | 2.11%   |
| Dell Vostro            | 2         | 2.11%   |
| Toshiba TECRA          | 1         | 1.05%   |
| Toshiba PORTEGE        | 1         | 1.05%   |
| Timi TM1701            | 1         | 1.05%   |
| Sony VPCYB15AB         | 1         | 1.05%   |
| Sony VPCEB1S1E         | 1         | 1.05%   |
| Samsung R430           | 1         | 1.05%   |
| Samsung 300E5EV        | 1         | 1.05%   |
| Samsung 270E5K         | 1         | 1.05%   |
| Panasonic CF-C2CCEZXCM | 1         | 1.05%   |
| Packard Bell EasyNote  | 1         | 1.05%   |
| MSI Modern             | 1         | 1.05%   |
| Lenovo Z51-70          | 1         | 1.05%   |
| Lenovo Z50-70          | 1         | 1.05%   |
| Lenovo Legion          | 1         | 1.05%   |
| Howard Computers W350  | 1         | 1.05%   |
| HP Stream              | 1         | 1.05%   |
| HP Presario            | 1         | 1.05%   |
| HP OMEN                | 1         | 1.05%   |
| HP ENVY                | 1         | 1.05%   |
| HP 255                 | 1         | 1.05%   |
| GPU Company GWTC116-2  | 1         | 1.05%   |
| Google Kip             | 1         | 1.05%   |
| Google Edgar           | 1         | 1.05%   |
| Google Delbin          | 1         | 1.05%   |
| Gigabyte AORUS         | 1         | 1.05%   |
| Framework Laptop       | 1         | 1.05%   |
| Chuwi LapBook          | 1         | 1.05%   |
| AZW SEi                | 1         | 1.05%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 12        | 12.63%  |
| 2018 | 11        | 11.58%  |
| 2019 | 9         | 9.47%   |
| 2012 | 9         | 9.47%   |
| 2017 | 8         | 8.42%   |
| 2021 | 7         | 7.37%   |
| 2014 | 7         | 7.37%   |
| 2013 | 6         | 6.32%   |
| 2020 | 5         | 5.26%   |
| 2011 | 5         | 5.26%   |
| 2010 | 5         | 5.26%   |
| 2008 | 4         | 4.21%   |
| 2015 | 3         | 3.16%   |
| 2009 | 3         | 3.16%   |
| 2007 | 1         | 1.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 95        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 95        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 96.84%  |
| Yes  | 3         | 3.16%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 24        | 25%     |
| 8.01-16.0   | 23        | 23.96%  |
| 4.01-8.0    | 19        | 19.79%  |
| 16.01-24.0  | 18        | 18.75%  |
| 32.01-64.0  | 6         | 6.25%   |
| 1.01-2.0    | 3         | 3.13%   |
| 2.01-3.0    | 2         | 2.08%   |
| 64.01-256.0 | 1         | 1.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 38        | 37.62%  |
| 2.01-3.0  | 29        | 28.71%  |
| 4.01-8.0  | 14        | 13.86%  |
| 3.01-4.0  | 11        | 10.89%  |
| 0.51-1.0  | 8         | 7.92%   |
| 8.01-16.0 | 1         | 0.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 70        | 73.68%  |
| 2      | 24        | 25.26%  |
| 3      | 1         | 1.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 60%     |
| Yes       | 38        | 40%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 81.05%  |
| No        | 18        | 18.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 81.05%  |
| No        | 18        | 18.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 19        | 20%     |
| India              | 8         | 8.42%   |
| Brazil             | 6         | 6.32%   |
| Netherlands        | 5         | 5.26%   |
| UK                 | 3         | 3.16%   |
| Spain              | 3         | 3.16%   |
| Poland             | 3         | 3.16%   |
| France             | 3         | 3.16%   |
| Australia          | 3         | 3.16%   |
| Ukraine            | 2         | 2.11%   |
| Turkey             | 2         | 2.11%   |
| Russia             | 2         | 2.11%   |
| Norway             | 2         | 2.11%   |
| New Zealand        | 2         | 2.11%   |
| Indonesia          | 2         | 2.11%   |
| Guatemala          | 2         | 2.11%   |
| Germany            | 2         | 2.11%   |
| Chile              | 2         | 2.11%   |
| Vietnam            | 1         | 1.05%   |
| Venezuela          | 1         | 1.05%   |
| Switzerland        | 1         | 1.05%   |
| Sweden             | 1         | 1.05%   |
| Saudi Arabia       | 1         | 1.05%   |
| Oman               | 1         | 1.05%   |
| Nepal              | 1         | 1.05%   |
| Mexico             | 1         | 1.05%   |
| Latvia             | 1         | 1.05%   |
| Japan              | 1         | 1.05%   |
| Italy              | 1         | 1.05%   |
| Iran               | 1         | 1.05%   |
| Hungary            | 1         | 1.05%   |
| Greece             | 1         | 1.05%   |
| Finland            | 1         | 1.05%   |
| Dominican Republic | 1         | 1.05%   |
| Czechia            | 1         | 1.05%   |
| China              | 1         | 1.05%   |
| Canada             | 1         | 1.05%   |
| Belgium            | 1         | 1.05%   |
| Belarus            | 1         | 1.05%   |
| Austria            | 1         | 1.05%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Melbourne                 | 3         | 2.97%   |
| Oslo                      | 2         | 1.98%   |
| Guatemala City            | 2         | 1.98%   |
| Columbus                  | 2         | 1.98%   |
| Auckland                  | 2         | 1.98%   |
| Amsterdam                 | 2         | 1.98%   |
| Zhytomyr                  | 1         | 0.99%   |
| Yverdon-les-Bains         | 1         | 0.99%   |
| Wendell                   | 1         | 0.99%   |
| Vineland                  | 1         | 0.99%   |
| Vienna                    | 1         | 0.99%   |
| Vasco da Gama             | 1         | 0.99%   |
| Toronto                   | 1         | 0.99%   |
| Tirana                    | 1         | 0.99%   |
| The Hague                 | 1         | 0.99%   |
| Terranuova Bracciolini    | 1         | 0.99%   |
| Teresopolis               | 1         | 0.99%   |
| Tehran                    | 1         | 0.99%   |
| Stroudsburg               | 1         | 0.99%   |
| Stare Babice              | 1         | 0.99%   |
| St Petersburg             | 1         | 0.99%   |
| Severna Park              | 1         | 0.99%   |
| Semarang                  | 1         | 0.99%   |
| Santo Domingo Este        | 1         | 0.99%   |
| Santiago                  | 1         | 0.99%   |
| San Justo                 | 1         | 0.99%   |
| San Francisco del Rincón | 1         | 0.99%   |
| San Francisco             | 1         | 0.99%   |
| Saint-Just-Saint-Rambert  | 1         | 0.99%   |
| Riyadh                    | 1         | 0.99%   |
| Riga                      | 1         | 0.99%   |
| Red Oak                   | 1         | 0.99%   |
| Quilicura                 | 1         | 0.99%   |
| Portland                  | 1         | 0.99%   |
| Port Orange               | 1         | 0.99%   |
| Pomeroy                   | 1         | 0.99%   |
| Pessac                    | 1         | 0.99%   |
| Paracuellos de Jarama     | 1         | 0.99%   |
| New York                  | 1         | 0.99%   |
| Muscat                    | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 14.88%  |
| Toshiba             | 15        | 18     | 12.4%   |
| Samsung Electronics | 15        | 16     | 12.4%   |
| Seagate             | 11        | 14     | 9.09%   |
| SanDisk             | 9         | 11     | 7.44%   |
| Kingston            | 8         | 8      | 6.61%   |
| SK hynix            | 7         | 7      | 5.79%   |
| Unknown             | 6         | 6      | 4.96%   |
| Intel               | 6         | 8      | 4.96%   |
| Micron Technology   | 5         | 6      | 4.13%   |
| Crucial             | 3         | 4      | 2.48%   |
| Silicon Motion      | 2         | 2      | 1.65%   |
| Hitachi             | 2         | 2      | 1.65%   |
| Transcend           | 1         | 1      | 0.83%   |
| SABRENT             | 1         | 1      | 0.83%   |
| PNY                 | 1         | 1      | 0.83%   |
| Phison              | 1         | 1      | 0.83%   |
| Lenovo              | 1         | 1      | 0.83%   |
| KIOXIA              | 1         | 1      | 0.83%   |
| KingFast            | 1         | 1      | 0.83%   |
| HGST                | 1         | 1      | 0.83%   |
| Gigabyte Technology | 1         | 1      | 0.83%   |
| FORESEE             | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| Advantech           | 1         | 1      | 0.83%   |
| AAPL                | 1         | 1      | 0.83%   |
| A-DATA Technology   | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 5         | 4.03%   |
| SK hynix NVMe SSD Drive 128GB           | 3         | 2.42%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 2.42%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 2.42%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 2         | 1.61%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 1.61%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.61%   |
| Unknown MMC Card  32GB                  | 2         | 1.61%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.61%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.81%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.81%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.81%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 0.81%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 0.81%   |
| WDC WD2500LPVX-22V0TT0 250GB            | 1         | 0.81%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.81%   |
| WDC WD2500BEVT-00A23T0 250GB            | 1         | 0.81%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.81%   |
| WDC WD10JPVX-08JC3T5 1TB                | 1         | 0.81%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.81%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB    | 1         | 0.81%   |
| Unknown USB DISK 3.2 1TB                | 1         | 0.81%   |
| Unknown MMC Card  64GB                  | 1         | 0.81%   |
| Unknown MMC Card  128GB                 | 1         | 0.81%   |
| Unknown AJNB4R  16GB                    | 1         | 0.81%   |
| Transcend TS240GSSD220S 240GB           | 1         | 0.81%   |
| Toshiba THNSNJ256GVNU 256GB SSD         | 1         | 0.81%   |
| Toshiba THNS128GG4BNAA 128GB SSD        | 1         | 0.81%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.81%   |
| Toshiba NVMe SSD Drive 256GB            | 1         | 0.81%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.81%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.81%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.81%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.81%   |
| Toshiba MK5055GSX 500GB                 | 1         | 0.81%   |
| Toshiba KXG60ZNV512G NVMe 512GB         | 1         | 0.81%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB | 1         | 0.81%   |
| SK hynix NVMe SSD Drive 500GB           | 1         | 0.81%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 0.81%   |
| SK hynix HFM512GDJTNG-8310A 512GB       | 1         | 0.81%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 15     | 36.84%  |
| Seagate | 11        | 14     | 28.95%  |
| Toshiba | 9         | 12     | 23.68%  |
| Hitachi | 2         | 2      | 5.26%   |
| HGST    | 1         | 1      | 2.63%   |
| AAPL    | 1         | 1      | 2.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 23.68%  |
| Kingston            | 5         | 5      | 13.16%  |
| SanDisk             | 4         | 4      | 10.53%  |
| Micron Technology   | 4         | 5      | 10.53%  |
| Intel               | 3         | 4      | 7.89%   |
| Crucial             | 3         | 4      | 7.89%   |
| WDC                 | 2         | 2      | 5.26%   |
| Toshiba             | 2         | 2      | 5.26%   |
| Transcend           | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| Gigabyte Technology | 1         | 1      | 2.63%   |
| FORESEE             | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |
| Advantech           | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 37        | 45     | 32.74%  |
| SSD     | 36        | 41     | 31.86%  |
| NVMe    | 32        | 41     | 28.32%  |
| MMC     | 6         | 6      | 5.31%   |
| Unknown | 2         | 2      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 64        | 84     | 59.81%  |
| NVMe | 32        | 40     | 29.91%  |
| MMC  | 6         | 6      | 5.61%   |
| SAS  | 5         | 5      | 4.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 46        | 57     | 64.79%  |
| 0.51-1.0   | 23        | 27     | 32.39%  |
| 1.01-2.0   | 2         | 2      | 2.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 43        | 44.79%  |
| 251-500    | 21        | 21.88%  |
| 501-1000   | 13        | 13.54%  |
| 1001-2000  | 7         | 7.29%   |
| 21-50      | 4         | 4.17%   |
| 51-100     | 3         | 3.13%   |
| 1-20       | 2         | 2.08%   |
| Unknown    | 2         | 2.08%   |
| 2001-3000  | 1         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 40        | 39.6%   |
| 21-50     | 19        | 18.81%  |
| 51-100    | 13        | 12.87%  |
| 101-250   | 12        | 11.88%  |
| 251-500   | 10        | 9.9%    |
| 1001-2000 | 3         | 2.97%   |
| 501-1000  | 2         | 1.98%   |
| Unknown   | 2         | 1.98%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB                    | 1         | 1      | 20%     |
| Seagate ST9320325AS 320GB                      | 1         | 2      | 20%     |
| Samsung Electronics MZVLB512HAJQ-000L7 512GB   | 1         | 1      | 20%     |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 20%     |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 20%     |
| Seagate             | 1         | 2      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Micron Technology   | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 2      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 4      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 67        | 94     | 66.34%  |
| Works    | 29        | 35     | 28.71%  |
| Malfunc  | 5         | 6      | 4.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 69        | 61.06%  |
| AMD                          | 10        | 8.85%   |
| SK hynix                     | 7         | 6.19%   |
| Samsung Electronics          | 6         | 5.31%   |
| Toshiba America Info Systems | 5         | 4.42%   |
| SanDisk                      | 5         | 4.42%   |
| Kingston Technology Company  | 3         | 2.65%   |
| Silicon Motion               | 2         | 1.77%   |
| Phison Electronics           | 1         | 0.88%   |
| Nvidia                       | 1         | 0.88%   |
| Micron Technology            | 1         | 0.88%   |
| Lenovo                       | 1         | 0.88%   |
| JMicron Technology           | 1         | 0.88%   |
| ADATA Technology             | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 10.26%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 7.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 6.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 5.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 5.13%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 3.42%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 3.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.56%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.71%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 1.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.71%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 1.71%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 1.71%   |
| Intel SSD 600P Series                                                          | 2         | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.71%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.85%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.85%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.85%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.85%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.85%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.85%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.85%   |
| Micron Non-Volatile memory controller                                          | 1         | 0.85%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 0.85%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.85%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.85%   |
| Intel SSD 660P Series                                                          | 1         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 74        | 66.67%  |
| NVMe | 31        | 27.93%  |
| RAID | 3         | 2.7%    |
| IDE  | 3         | 2.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 83        | 87.37%  |
| AMD    | 12        | 12.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 6.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 4.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 3.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 3.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 3.16%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.11%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 2.11%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 2.11%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 2.11%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.11%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 2.11%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.11%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.11%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.05%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.05%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 1.05%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.05%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 1.05%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 1.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.05%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.05%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.05%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.05%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.05%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.05%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 1.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.05%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 1.05%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.05%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.05%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.05%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 1.05%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 34.74%  |
| Intel Core i7           | 22        | 23.16%  |
| Intel Celeron           | 8         | 8.42%   |
| Intel Core i3           | 6         | 6.32%   |
| AMD Ryzen 7             | 5         | 5.26%   |
| Other                   | 4         | 4.21%   |
| Intel Core 2 Duo        | 4         | 4.21%   |
| AMD Ryzen 5             | 4         | 4.21%   |
| Intel Pentium           | 2         | 2.11%   |
| Intel Pentium Silver    | 1         | 1.05%   |
| Intel Pentium Dual-Core | 1         | 1.05%   |
| Intel Pentium Dual      | 1         | 1.05%   |
| Intel Core M            | 1         | 1.05%   |
| Intel Atom              | 1         | 1.05%   |
| AMD E1                  | 1         | 1.05%   |
| AMD E                   | 1         | 1.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 54        | 56.84%  |
| 4      | 32        | 33.68%  |
| 6      | 5         | 5.26%   |
| 8      | 3         | 3.16%   |
| 1      | 1         | 1.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 95        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 73        | 76.84%  |
| 1      | 22        | 23.16%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 91        | 94.79%  |
| Unknown        | 5         | 5.21%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ea    | 9         | 9.28%   |
| 0x306a9    | 8         | 8.25%   |
| 0x206a7    | 7         | 7.22%   |
| 0x806e9    | 6         | 6.19%   |
| Unknown    | 6         | 6.19%   |
| 0x40651    | 5         | 5.15%   |
| 0x306c3    | 4         | 4.12%   |
| 0x20655    | 4         | 4.12%   |
| 0x906ea    | 3         | 3.09%   |
| 0x906e9    | 3         | 3.09%   |
| 0x806ec    | 3         | 3.09%   |
| 0x806c1    | 3         | 3.09%   |
| 0x706a1    | 3         | 3.09%   |
| 0x406e3    | 3         | 3.09%   |
| 0x306d4    | 3         | 3.09%   |
| 0x1067a    | 3         | 3.09%   |
| 0x08108102 | 3         | 3.09%   |
| 0x6fd      | 2         | 2.06%   |
| 0x506e3    | 2         | 2.06%   |
| 0x30678    | 2         | 2.06%   |
| 0xa0652    | 1         | 1.03%   |
| 0x906c0    | 1         | 1.03%   |
| 0x806eb    | 1         | 1.03%   |
| 0x706a8    | 1         | 1.03%   |
| 0x20652    | 1         | 1.03%   |
| 0x10676    | 1         | 1.03%   |
| 0x10661    | 1         | 1.03%   |
| 0x0a50000c | 1         | 1.03%   |
| 0x08608103 | 1         | 1.03%   |
| 0x08600106 | 1         | 1.03%   |
| 0x08108109 | 1         | 1.03%   |
| 0x0810100b | 1         | 1.03%   |
| 0x06006704 | 1         | 1.03%   |
| 0x05000119 | 1         | 1.03%   |
| 0x05000029 | 1         | 1.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 27.37%  |
| Haswell       | 10        | 10.53%  |
| IvyBridge     | 8         | 8.42%   |
| SandyBridge   | 7         | 7.37%   |
| Westmere      | 5         | 5.26%   |
| Skylake       | 5         | 5.26%   |
| Zen+          | 4         | 4.21%   |
| Penryn        | 4         | 4.21%   |
| Goldmont plus | 4         | 4.21%   |
| TigerLake     | 3         | 3.16%   |
| Silvermont    | 3         | 3.16%   |
| Core          | 3         | 3.16%   |
| Broadwell     | 3         | 3.16%   |
| Bobcat        | 2         | 2.11%   |
| Unknown       | 2         | 2.11%   |
| Zen 3         | 1         | 1.05%   |
| Zen 2         | 1         | 1.05%   |
| Zen           | 1         | 1.05%   |
| Tremont       | 1         | 1.05%   |
| Excavator     | 1         | 1.05%   |
| CometLake     | 1         | 1.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 77        | 61.11%  |
| Nvidia | 28        | 22.22%  |
| AMD    | 21        | 16.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 8         | 6.25%   |
| Intel HD Graphics 620                                                     | 7         | 5.47%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 5.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6         | 4.69%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 3.13%   |
| Nvidia GM108M [GeForce 940MX]                                             | 3         | 2.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 2.34%   |
| Intel HD Graphics 630                                                     | 3         | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 2.34%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.34%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.56%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 1.56%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.56%   |
| Nvidia GM108M [GeForce 930MX]                                             | 2         | 1.56%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.56%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 2         | 1.56%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 2         | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.56%   |
| Intel HD Graphics 5500                                                    | 2         | 1.56%   |
| Intel HD Graphics 530                                                     | 2         | 1.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.56%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                  | 2         | 1.56%   |
| AMD Lucienne                                                              | 2         | 1.56%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.78%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.78%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.78%   |
| Nvidia GK208M [GeForce GT 730M]                                           | 1         | 0.78%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.78%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 51.58%  |
| Intel + Nvidia | 24        | 25.26%  |
| 1 x AMD        | 14        | 14.74%  |
| Intel + AMD    | 4         | 4.21%   |
| AMD + Nvidia   | 3         | 3.16%   |
| 1 x Nvidia     | 1         | 1.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 77        | 81.05%  |
| Proprietary | 18        | 18.95%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 54.74%  |
| 1.01-2.0   | 17        | 17.89%  |
| 0.51-1.0   | 10        | 10.53%  |
| 0.01-0.5   | 7         | 7.37%   |
| 3.01-4.0   | 6         | 6.32%   |
| 5.01-6.0   | 3         | 3.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 24.78%  |
| LG Display              | 14        | 12.39%  |
| BOE                     | 14        | 12.39%  |
| Chimei Innolux          | 13        | 11.5%   |
| Samsung Electronics     | 12        | 10.62%  |
| Lenovo                  | 4         | 3.54%   |
| Goldstar                | 4         | 3.54%   |
| Sharp                   | 3         | 2.65%   |
| PANDA                   | 2         | 1.77%   |
| Chi Mei Optoelectronics | 2         | 1.77%   |
| BenQ                    | 2         | 1.77%   |
| Apple                   | 2         | 1.77%   |
| AOC                     | 2         | 1.77%   |
| Ancor Communications    | 2         | 1.77%   |
| ___                     | 1         | 0.88%   |
| Unknown                 | 1         | 0.88%   |
| Toshiba                 | 1         | 0.88%   |
| Sony                    | 1         | 0.88%   |
| Philips                 | 1         | 0.88%   |
| GKK                     | 1         | 0.88%   |
| Dell                    | 1         | 0.88%   |
| CSO                     | 1         | 0.88%   |
| Acer                    | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.75%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.88%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.88%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch             | 1         | 0.88%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.88%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.88%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch  | 1         | 0.88%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch   | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4250 1920x1080 276x156mm 12.5-inch | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.88%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.88%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch     | 1         | 0.88%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                 | 1         | 0.88%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.88%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.88%   |
| LG Display LCD Monitor LGD0404 1366x768 277x156mm 12.5-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0383 1600x900 380x210mm 17.1-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch           | 1         | 0.88%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 45.19%  |
| 1366x768 (WXGA)    | 34        | 32.69%  |
| 1600x900 (HD+)     | 7         | 6.73%   |
| 3840x2160 (4K)     | 3         | 2.88%   |
| 1440x900 (WXGA+)   | 3         | 2.88%   |
| 1280x800 (WXGA)    | 3         | 2.88%   |
| 2560x1600          | 1         | 0.96%   |
| 2560x1440 (QHD)    | 1         | 0.96%   |
| 2560x1080          | 1         | 0.96%   |
| 2256x1504          | 1         | 0.96%   |
| 1920x1200 (WUXGA)  | 1         | 0.96%   |
| 1680x1050 (WSXGA+) | 1         | 0.96%   |
| 1360x768           | 1         | 0.96%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 52        | 46.43%  |
| 13      | 20        | 17.86%  |
| 14      | 11        | 9.82%   |
| 17      | 7         | 6.25%   |
| 24      | 4         | 3.57%   |
| 21      | 4         | 3.57%   |
| 23      | 3         | 2.68%   |
| 27      | 2         | 1.79%   |
| 12      | 2         | 1.79%   |
| 11      | 2         | 1.79%   |
| 72      | 1         | 0.89%   |
| 40      | 1         | 0.89%   |
| 34      | 1         | 0.89%   |
| 18      | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 63.96%  |
| 201-300     | 13        | 11.71%  |
| 351-400     | 9         | 8.11%   |
| 501-600     | 8         | 7.21%   |
| 401-500     | 6         | 5.41%   |
| 801-900     | 1         | 0.9%    |
| 701-800     | 1         | 0.9%    |
| 1501-2000   | 1         | 0.9%    |
| Unknown     | 1         | 0.9%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 87        | 89.69%  |
| 16/10 | 7         | 7.22%   |
| 3/2   | 2         | 2.06%   |
| 21/9  | 1         | 1.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 45.54%  |
| 81-90          | 24        | 21.43%  |
| 201-250        | 9         | 8.04%   |
| 71-80          | 7         | 6.25%   |
| 121-130        | 7         | 6.25%   |
| 61-70          | 2         | 1.79%   |
| 51-60          | 2         | 1.79%   |
| 301-350        | 2         | 1.79%   |
| More than 1000 | 1         | 0.89%   |
| 351-500        | 1         | 0.89%   |
| 251-300        | 1         | 0.89%   |
| 151-200        | 1         | 0.89%   |
| 141-150        | 1         | 0.89%   |
| 501-1000       | 1         | 0.89%   |
| 91-100         | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 43        | 39.81%  |
| 101-120       | 36        | 33.33%  |
| 51-100        | 16        | 14.81%  |
| 161-240       | 8         | 7.41%   |
| More than 240 | 3         | 2.78%   |
| 1-50          | 1         | 0.93%   |
| Unknown       | 1         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 79        | 82.29%  |
| 2     | 15        | 15.63%  |
| 3     | 2         | 2.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 49        | 31.61%  |
| Realtek Semiconductor         | 45        | 29.03%  |
| Qualcomm Atheros              | 29        | 18.71%  |
| Broadcom                      | 9         | 5.81%   |
| Marvell Technology Group      | 4         | 2.58%   |
| Ralink                        | 2         | 1.29%   |
| MediaTek                      | 2         | 1.29%   |
| Dell                          | 2         | 1.29%   |
| TP-Link                       | 1         | 0.65%   |
| T & A Mobile Phones           | 1         | 0.65%   |
| Sierra Wireless               | 1         | 0.65%   |
| Samsung Electronics           | 1         | 0.65%   |
| Ralink Technology             | 1         | 0.65%   |
| Qualcomm                      | 1         | 0.65%   |
| OnePlus Technology (Shenzhen) | 1         | 0.65%   |
| Nvidia                        | 1         | 0.65%   |
| Lenovo                        | 1         | 0.65%   |
| Jolla Oy                      | 1         | 0.65%   |
| Hewlett-Packard               | 1         | 0.65%   |
| ASIX Electronics              | 1         | 0.65%   |
| Android                       | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 16.3%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 4.35%   |
| Intel Wireless 8265 / 8275                                        | 8         | 4.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.72%   |
| Intel Wireless 7260                                               | 5         | 2.72%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.63%   |
| Intel Wireless 8260                                               | 3         | 1.63%   |
| Intel Wireless 7265                                               | 3         | 1.63%   |
| Intel Wireless 3165                                               | 3         | 1.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.09%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.09%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.09%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 1.09%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.54%   |
| T & A Mobile Phones A509DL                                        | 1         | 0.54%   |
| Sierra Wireless EM7305                                            | 1         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.54%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.54%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.54%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.54%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 49%     |
| Qualcomm Atheros      | 26        | 26%     |
| Realtek Semiconductor | 10        | 10%     |
| Broadcom              | 7         | 7%      |
| Ralink                | 2         | 2%      |
| MediaTek              | 2         | 2%      |
| Sierra Wireless       | 1         | 1%      |
| Ralink Technology     | 1         | 1%      |
| Hewlett-Packard       | 1         | 1%      |
| Dell                  | 1         | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 8%      |
| Intel Wireless 8265 / 8275                                     | 8         | 8%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 6%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 5%      |
| Intel Wireless 7260                                            | 5         | 5%      |
| Intel Wi-Fi 6 AX200                                            | 5         | 5%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 4%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 3%      |
| Intel Wireless 8260                                            | 3         | 3%      |
| Intel Wireless 7265                                            | 3         | 3%      |
| Intel Wireless 3165                                            | 3         | 3%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 2%      |
| Intel Wi-Fi 6 AX201                                            | 2         | 2%      |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2%      |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2%      |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 2%      |
| Sierra Wireless EM7305                                         | 1         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1%      |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1%      |
| Realtek RTL8187 Wireless Adapter                               | 1         | 1%      |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1%      |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1%      |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1%      |
| Intel Wireless 3160                                            | 1         | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 1%      |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 1%      |
| Intel Ultimate N WiFi Link 5300                                | 1         | 1%      |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1%      |
| Intel Centrino Wireless-N 2230                                 | 1         | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 40        | 49.38%  |
| Intel                    | 21        | 25.93%  |
| Qualcomm Atheros         | 5         | 6.17%   |
| Marvell Technology Group | 4         | 4.94%   |
| Broadcom                 | 3         | 3.7%    |
| TP-Link                  | 1         | 1.23%   |
| Samsung Electronics      | 1         | 1.23%   |
| Qualcomm                 | 1         | 1.23%   |
| Nvidia                   | 1         | 1.23%   |
| Lenovo                   | 1         | 1.23%   |
| Jolla Oy                 | 1         | 1.23%   |
| ASIX Electronics         | 1         | 1.23%   |
| Android                  | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 30        | 37.04%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 8.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 7.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 2.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 2.47%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 2.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.23%   |
| Qualcomm Nokia 5.4                                                             | 1         | 1.23%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.23%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.23%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.23%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 1.23%   |
| Lenovo Thinkpad LAN                                                            | 1         | 1.23%   |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 1.23%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.23%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.23%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.23%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.23%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.23%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.23%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.23%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.23%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.23%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.23%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.23%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.23%   |
| Android Android                                                                | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 54.29%  |
| Ethernet | 77        | 44%     |
| Unknown  | 2         | 1.14%   |
| Modem    | 1         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 86.46%  |
| Ethernet | 13        | 13.54%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 73        | 76.84%  |
| 1     | 21        | 22.11%  |
| 0     | 1         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 87        | 90.63%  |
| Yes  | 9         | 9.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 38        | 49.35%  |
| Qualcomm Atheros Communications | 9         | 11.69%  |
| Lite-On Technology              | 9         | 11.69%  |
| Realtek Semiconductor           | 4         | 5.19%   |
| Broadcom                        | 4         | 5.19%   |
| IMC Networks                    | 3         | 3.9%    |
| Foxconn / Hon Hai               | 2         | 2.6%    |
| Apple                           | 2         | 2.6%    |
| Toshiba                         | 1         | 1.3%    |
| Ralink                          | 1         | 1.3%    |
| MediaTek                        | 1         | 1.3%    |
| Hewlett-Packard                 | 1         | 1.3%    |
| Dell                            | 1         | 1.3%    |
| Cambridge Silicon Radio         | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 28.57%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 6.49%   |
| Intel AX200 Bluetooth                                                               | 5         | 6.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 3.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 3.9%    |
| Intel AX201 Bluetooth                                                               | 3         | 3.9%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.6%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 2.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 2.6%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 2.6%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.6%    |
| Toshiba RT Bluetooth Radio                                                          | 1         | 1.3%    |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.3%    |
| Realtek Bluetooth Radio                                                             | 1         | 1.3%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.3%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.3%    |
| MediaTek Wireless_Device                                                            | 1         | 1.3%    |
| Lite-On Wireless_Device                                                             | 1         | 1.3%    |
| Lite-On Bluetooth Device                                                            | 1         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.3%    |
| Intel AX210 Bluetooth                                                               | 1         | 1.3%    |
| IMC Networks Bluetooth Device                                                       | 1         | 1.3%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.3%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.3%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.3%    |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.3%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.3%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.3%    |
| Apple Bluetooth Host Controller                                                     | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 82        | 71.3%   |
| AMD                 | 17        | 14.78%  |
| Nvidia              | 13        | 11.3%   |
| Samsung Electronics | 1         | 0.87%   |
| GYROCOM C&C         | 1         | 0.87%   |
| Conexant Systems    | 1         | 0.87%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 13.14%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6.57%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 6.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 4.38%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 4.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.19%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.19%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.46%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.46%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.46%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.46%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.46%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.73%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.73%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.73%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.73%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.73%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.73%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.73%   |
| GYROCOM C&C Fiio E10                                                                              | 1         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 30.77%  |
| SK hynix            | 9         | 17.31%  |
| A-DATA Technology   | 5         | 9.62%   |
| Kingston            | 4         | 7.69%   |
| Crucial             | 4         | 7.69%   |
| Nanya Technology    | 3         | 5.77%   |
| Micron Technology   | 3         | 5.77%   |
| Unknown             | 2         | 3.85%   |
| Ramaxel Technology  | 2         | 3.85%   |
| Elpida              | 2         | 3.85%   |
| Team                | 1         | 1.92%   |
| G.Skill             | 1         | 1.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 3.85%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 3.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.92%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.92%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 1.92%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.92%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.92%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.92%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.92%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.92%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.92%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.92%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.92%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.92%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.92%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 1.92%   |
| Ramaxel RAM RMT3170EB68E9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.92%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 1.92%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.92%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 1.92%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.92%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.92%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s            | 1         | 1.92%   |
| Kingston RAM 99U5663-003.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 1.92%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.92%   |
| Kingston RAM 9905624-044.A00G 8192MB SODIMM DDR4 2400MT/s        | 1         | 1.92%   |
| G.Skill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s           | 1         | 1.92%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s                    | 1         | 1.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 47.62%  |
| DDR3   | 13        | 30.95%  |
| LPDDR3 | 4         | 9.52%   |
| DDR2   | 2         | 4.76%   |
| SDRAM  | 1         | 2.38%   |
| LPDDR4 | 1         | 2.38%   |
| DDR    | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 92.68%  |
| Row Of Chips | 3         | 7.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 16        | 38.1%   |
| 4096  | 11        | 26.19%  |
| 16384 | 6         | 14.29%  |
| 2048  | 6         | 14.29%  |
| 32768 | 2         | 4.76%   |
| 1024  | 1         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 21.74%  |
| 2667    | 8         | 17.39%  |
| 2133    | 6         | 13.04%  |
| 3200    | 5         | 10.87%  |
| 2400    | 5         | 10.87%  |
| 1334    | 2         | 4.35%   |
| Unknown | 2         | 4.35%   |
| 4267    | 1         | 2.17%   |
| 3266    | 1         | 2.17%   |
| 2048    | 1         | 2.17%   |
| 1867    | 1         | 2.17%   |
| 1333    | 1         | 2.17%   |
| 1067    | 1         | 2.17%   |
| 800     | 1         | 2.17%   |
| 667     | 1         | 2.17%   |

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
| Chicony Electronics                    | 20        | 22.99%  |
| Realtek Semiconductor                  | 10        | 11.49%  |
| Microdia                               | 9         | 10.34%  |
| IMC Networks                           | 8         | 9.2%    |
| Quanta                                 | 6         | 6.9%    |
| Sunplus Innovation Technology          | 5         | 5.75%   |
| Acer                                   | 5         | 5.75%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.6%    |
| Suyin                                  | 3         | 3.45%   |
| Logitech                               | 3         | 3.45%   |
| Lite-On Technology                     | 3         | 3.45%   |
| Syntek                                 | 2         | 2.3%    |
| Lenovo                                 | 2         | 2.3%    |
| Importek                               | 2         | 2.3%    |
| Z-Star Microelectronics                | 1         | 1.15%   |
| Unknown                                | 1         | 1.15%   |
| Silicon Motion                         | 1         | 1.15%   |
| Intel                                  | 1         | 1.15%   |
| Apple                                  | 1         | 1.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                     | 6         | 6.82%   |
| Microdia Integrated_Webcam_HD                                         | 4         | 4.55%   |
| Sunplus Integrated_Webcam_HD                                          | 3         | 3.41%   |
| Realtek HD WebCam                                                     | 3         | 3.41%   |
| IMC Networks USB2.0 HD UVC WebCam                                     | 3         | 3.41%   |
| Chicony Integrated Camera                                             | 3         | 3.41%   |
| Suyin HP TrueVision HD Integrated Webcam                              | 2         | 2.27%   |
| Realtek Integrated Webcam_HD                                          | 2         | 2.27%   |
| Quanta HD User Facing                                                 | 2         | 2.27%   |
| Microdia USB 2.0 Camera                                               | 2         | 2.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 2         | 2.27%   |
| IMC Networks Integrated Camera                                        | 2         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                         | 2         | 2.27%   |
| Z-Star Webcam                                                         | 1         | 1.14%   |
| Unknown ATIV VGA CAMERA                                               | 1         | 1.14%   |
| Syntek USB2.0 Camera                                                  | 1         | 1.14%   |
| Syntek Integrated Camera                                              | 1         | 1.14%   |
| Suyin 1.3M HD WebCam                                                  | 1         | 1.14%   |
| Sunplus Laptop_Integrated_Webcam_HD                                   | 1         | 1.14%   |
| Sunplus Laptop Integrated WebCam HD                                   | 1         | 1.14%   |
| Silicon Motion WebCam SC-10HDD12636N                                  | 1         | 1.14%   |
| Realtek USB2.0 HD UVC WebCam                                          | 1         | 1.14%   |
| Realtek Laptop Camera                                                 | 1         | 1.14%   |
| Realtek Integrated_Webcam_HD                                          | 1         | 1.14%   |
| Realtek Integrated Webcam                                             | 1         | 1.14%   |
| Realtek Integrated Camera                                             | 1         | 1.14%   |
| Quanta VGA WebCam                                                     | 1         | 1.14%   |
| Quanta USB2.0 HD UVC WebCam                                           | 1         | 1.14%   |
| Quanta HP Wide Vision HD Camera                                       | 1         | 1.14%   |
| Quanta HP TrueVision HD Webcam                                        | 1         | 1.14%   |
| Microdia Webcam                                                       | 1         | 1.14%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.14%   |
| Microdia Dell Laptop Integrated Webcam HD                             | 1         | 1.14%   |
| Logitech Webcam C310                                                  | 1         | 1.14%   |
| Logitech Webcam C270                                                  | 1         | 1.14%   |
| Logitech HD Pro Webcam C920                                           | 1         | 1.14%   |
| Lite-On Integrated Camera                                             | 1         | 1.14%   |
| Lite-On HP HD Webcam                                                  | 1         | 1.14%   |
| Lite-On HP HD Camera                                                  | 1         | 1.14%   |
| Lenovo UVC Camera                                                     | 1         | 1.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 50%     |
| Upek                       | 2         | 9.09%   |
| Synaptics                  | 2         | 9.09%   |
| LighTuning Technology      | 2         | 9.09%   |
| Elan Microelectronics      | 2         | 9.09%   |
| AuthenTec                  | 2         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 18.18%  |
| Validity Sensors Fingerprint scanner                   | 2         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 9.09%   |
| Elan ELAN:Fingerprint                                  | 2         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.55%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.55%   |
| Validity Sensors VFS491                                | 1         | 4.55%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.55%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.55%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.55%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 4.55%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.55%   |
| AuthenTec AES2810                                      | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Upek        | 2         | 25%     |
| Broadcom    | 2         | 25%     |
| Alcor Micro | 2         | 25%     |
| O2 Micro    | 1         | 12.5%   |
| Lenovo      | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 12.5%   |
| Broadcom 5880                                              | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 59        | 62.11%  |
| 1     | 25        | 26.32%  |
| 2     | 11        | 11.58%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 22        | 44.9%   |
| Net/wireless          | 8         | 16.33%  |
| Chipcard              | 7         | 14.29%  |
| Multimedia controller | 4         | 8.16%   |
| Graphics card         | 3         | 6.12%   |
| Unassigned class      | 1         | 2.04%   |
| Storage               | 1         | 2.04%   |
| Net/ethernet          | 1         | 2.04%   |
| Camera                | 1         | 2.04%   |
| Bluetooth             | 1         | 2.04%   |


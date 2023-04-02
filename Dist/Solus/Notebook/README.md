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

Total: 137

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Solus 4.1    | 39        | 38.61%  |
| Solus 4.3    | 31        | 30.69%  |
| Solus 4.0    | 17        | 16.83%  |
| Solus 4.2    | 13        | 12.87%  |
| Solus 3.9999 | 1         | 0.99%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Solus | 97        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.6.19-158.current  | 9         | 8.57%   |
| 5.6.4-152.current   | 5         | 4.76%   |
| 5.6.19-159.current  | 5         | 4.76%   |
| 5.6.13-153.current  | 4         | 3.81%   |
| 5.5.7-150.current   | 4         | 3.81%   |
| 5.15.50-216.current | 4         | 3.81%   |
| 5.13.1-187.current  | 4         | 3.81%   |
| 5.3.7-132.current   | 3         | 2.86%   |
| 5.2.20-130.current  | 3         | 2.86%   |
| 5.15.32-213.current | 3         | 2.86%   |
| 5.14.21-210.current | 3         | 2.86%   |
| 5.11.22-180.current | 3         | 2.86%   |
| 6.0.11-225.current  | 2         | 1.9%    |
| 5.6.18-156.current  | 2         | 1.9%    |
| 5.5.4-148.current   | 2         | 1.9%    |
| 5.5.11-151.current  | 2         | 1.9%    |
| 5.4.12-144.current  | 2         | 1.9%    |
| 5.3.15-138.current  | 2         | 1.9%    |
| 5.3.10-134.current  | 2         | 1.9%    |
| 5.2.2-122.current   | 2         | 1.9%    |
| 5.15.77-219.current | 2         | 1.9%    |
| 5.14.16-205.current | 2         | 1.9%    |
| 5.13.6-190.current  | 2         | 1.9%    |
| 5.13.12-193.current | 2         | 1.9%    |
| 5.12.10-182.current | 2         | 1.9%    |
| 5.11.9-176.current  | 2         | 1.9%    |
| 5.11.12-177.current | 2         | 1.9%    |
| 5.10.12-171.current | 2         | 1.9%    |
| 6.1.5-229.current   | 1         | 0.95%   |
| 6.1.2-228.current   | 1         | 0.95%   |
| 5.6.18-155.current  | 1         | 0.95%   |
| 5.5.3-147.current   | 1         | 0.95%   |
| 5.4.12-143.current  | 1         | 0.95%   |
| 5.4.1-137.current   | 1         | 0.95%   |
| 5.2.13-126.current  | 1         | 0.95%   |
| 5.15.61-217.current | 1         | 0.95%   |
| 5.15.37-214.current | 1         | 0.95%   |
| 5.15.26-211.current | 1         | 0.95%   |
| 5.14.7-198.current  | 1         | 0.95%   |
| 5.14.16-204.current | 1         | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6.19  | 14        | 13.33%  |
| 5.6.4   | 5         | 4.76%   |
| 5.6.13  | 4         | 3.81%   |
| 5.5.7   | 4         | 3.81%   |
| 5.15.50 | 4         | 3.81%   |
| 5.13.1  | 4         | 3.81%   |
| 5.6.18  | 3         | 2.86%   |
| 5.4.12  | 3         | 2.86%   |
| 5.3.7   | 3         | 2.86%   |
| 5.2.20  | 3         | 2.86%   |
| 5.15.32 | 3         | 2.86%   |
| 5.14.21 | 3         | 2.86%   |
| 5.14.16 | 3         | 2.86%   |
| 5.11.22 | 3         | 2.86%   |
| 6.0.11  | 2         | 1.9%    |
| 5.5.4   | 2         | 1.9%    |
| 5.5.11  | 2         | 1.9%    |
| 5.3.15  | 2         | 1.9%    |
| 5.3.10  | 2         | 1.9%    |
| 5.2.2   | 2         | 1.9%    |
| 5.15.77 | 2         | 1.9%    |
| 5.13.6  | 2         | 1.9%    |
| 5.13.12 | 2         | 1.9%    |
| 5.12.10 | 2         | 1.9%    |
| 5.11.9  | 2         | 1.9%    |
| 5.11.12 | 2         | 1.9%    |
| 5.10.12 | 2         | 1.9%    |
| 6.1.5   | 1         | 0.95%   |
| 6.1.2   | 1         | 0.95%   |
| 5.5.3   | 1         | 0.95%   |
| 5.4.1   | 1         | 0.95%   |
| 5.2.13  | 1         | 0.95%   |
| 5.15.61 | 1         | 0.95%   |
| 5.15.37 | 1         | 0.95%   |
| 5.15.26 | 1         | 0.95%   |
| 5.14.7  | 1         | 0.95%   |
| 5.14.15 | 1         | 0.95%   |
| 5.14.12 | 1         | 0.95%   |
| 5.13.15 | 1         | 0.95%   |
| 5.13.0  | 1         | 0.95%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.6     | 26        | 25%     |
| 5.15    | 12        | 11.54%  |
| 5.13    | 10        | 9.62%   |
| 5.5     | 9         | 8.65%   |
| 5.14    | 9         | 8.65%   |
| 5.3     | 7         | 6.73%   |
| 5.2     | 6         | 5.77%   |
| 5.11    | 6         | 5.77%   |
| 5.10    | 5         | 4.81%   |
| 5.4     | 4         | 3.85%   |
| 6.1     | 2         | 1.92%   |
| 6.0     | 2         | 1.92%   |
| 5.12    | 2         | 1.92%   |
| 5.0     | 1         | 0.96%   |
| 4.20    | 1         | 0.96%   |
| 4.18    | 1         | 0.96%   |
| 4.14    | 1         | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 97        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Budgie  | 50        | 49.5%   |
| Unknown | 23        | 22.77%  |
| MATE    | 10        | 9.9%    |
| KDE     | 10        | 9.9%    |
| GNOME   | 5         | 4.95%   |
| KDE5    | 3         | 2.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 97        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 73        | 73.74%  |
| TDM     | 12        | 12.12%  |
| LightDM | 9         | 9.09%   |
| SDDM    | 4         | 4.04%   |
| GDM     | 1         | 1.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 52        | 53.06%  |
| Unknown | 10        | 10.2%   |
| en_GB   | 6         | 6.12%   |
| de_DE   | 4         | 4.08%   |
| pt_BR   | 3         | 3.06%   |
| fr_FR   | 3         | 3.06%   |
| es_ES   | 3         | 3.06%   |
| en_AU   | 3         | 3.06%   |
| tr_TR   | 2         | 2.04%   |
| pl_PL   | 2         | 2.04%   |
| it_IT   | 2         | 2.04%   |
| en_NZ   | 2         | 2.04%   |
| uk_UA   | 1         | 1.02%   |
| ru_RU   | 1         | 1.02%   |
| es_CL   | 1         | 1.02%   |
| en_IN   | 1         | 1.02%   |
| en_CA   | 1         | 1.02%   |
| de_AT   | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 61.62%  |
| BIOS | 38        | 38.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 90        | 91.84%  |
| Unknown | 7         | 7.14%   |
| Overlay | 1         | 1.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 62        | 62.63%  |
| GPT     | 30        | 30.3%   |
| MBR     | 7         | 7.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 92.78%  |
| Yes       | 7         | 7.22%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 82.47%  |
| Yes       | 17        | 17.53%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 17        | 17.53%  |
| Dell                   | 17        | 17.53%  |
| Hewlett-Packard        | 16        | 16.49%  |
| Acer                   | 14        | 14.43%  |
| Toshiba                | 6         | 6.19%   |
| ASUSTek Computer       | 6         | 6.19%   |
| Samsung Electronics    | 3         | 3.09%   |
| Google                 | 3         | 3.09%   |
| Sony                   | 2         | 2.06%   |
| Apple                  | 2         | 2.06%   |
| Timi                   | 1         | 1.03%   |
| Panasonic              | 1         | 1.03%   |
| Packard Bell           | 1         | 1.03%   |
| MSI                    | 1         | 1.03%   |
| Howard Computers       | 1         | 1.03%   |
| GPU Company            | 1         | 1.03%   |
| Gigabyte Technology    | 1         | 1.03%   |
| Framework              | 1         | 1.03%   |
| Chuwi                  | 1         | 1.03%   |
| AZW                    | 1         | 1.03%   |
| Avell High Performance | 1         | 1.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G5                                     | 2         | 2.06%   |
| Acer Aspire E5-575G                                   | 2         | 2.06%   |
| Toshiba TECRA R840                                    | 1         | 1.03%   |
| Toshiba Satellite P50-A                               | 1         | 1.03%   |
| Toshiba Satellite L855                                | 1         | 1.03%   |
| Toshiba Satellite L655                                | 1         | 1.03%   |
| Toshiba PORTEGE Z20T-B                                | 1         | 1.03%   |
| Timi TM1701                                           | 1         | 1.03%   |
| Sony VPCYB15AB                                        | 1         | 1.03%   |
| Sony VPCEB1S1E                                        | 1         | 1.03%   |
| Samsung R430/P430/R480                                | 1         | 1.03%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 1.03%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 1         | 1.03%   |
| Panasonic CF-C2CCEZXCM                                | 1         | 1.03%   |
| Packard Bell EasyNote TS11HR                          | 1         | 1.03%   |
| MSI Modern 14 B5M                                     | 1         | 1.03%   |
| Lenovo Z51-70 80K6                                    | 1         | 1.03%   |
| Lenovo Z50-70 20354                                   | 1         | 1.03%   |
| Lenovo ThinkPad X301 4057WHQ                          | 1         | 1.03%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS1DN00              | 1         | 1.03%   |
| Lenovo ThinkPad W530 243852U                          | 1         | 1.03%   |
| Lenovo ThinkPad T480 20L5S08L00                       | 1         | 1.03%   |
| Lenovo ThinkPad T440p 20AN009CUS                      | 1         | 1.03%   |
| Lenovo ThinkPad T430 2349CV2                          | 1         | 1.03%   |
| Lenovo ThinkPad T410 2522Y1L                          | 1         | 1.03%   |
| Lenovo ThinkPad T15 Gen 2i 20W4CTO1WW                 | 1         | 1.03%   |
| Lenovo ThinkPad T14 Gen 1 20S00013FR                  | 1         | 1.03%   |
| Lenovo ThinkPad Edge E440 20C5A03300                  | 1         | 1.03%   |
| Lenovo Legion Y530-15ICH 81FV                         | 1         | 1.03%   |
| Lenovo IdeaPad S340-15API 81NC                        | 1         | 1.03%   |
| Lenovo IdeaPad 5 15ALC05 82LN                         | 1         | 1.03%   |
| Lenovo IdeaPad 330S-15IKB 81F5                        | 1         | 1.03%   |
| Lenovo IdeaPad 320-15ISK 80XH                         | 1         | 1.03%   |
| Howard Computers W350                                 | 1         | 1.03%   |
| HP Stream Laptop 14-cb1XX                             | 1         | 1.03%   |
| HP ProBook 650 G1                                     | 1         | 1.03%   |
| HP ProBook 6470b                                      | 1         | 1.03%   |
| HP ProBook 440 G4                                     | 1         | 1.03%   |
| HP Presario C700                                      | 1         | 1.03%   |
| HP Pavilion Laptop 15-cw0xxx                          | 1         | 1.03%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 10.31%  |
| Acer Aspire            | 9         | 9.28%   |
| Dell Inspiron          | 6         | 6.19%   |
| HP ProBook             | 5         | 5.15%   |
| Dell Latitude          | 5         | 5.15%   |
| Lenovo IdeaPad         | 4         | 4.12%   |
| HP Pavilion            | 4         | 4.12%   |
| Dell XPS               | 4         | 4.12%   |
| Toshiba Satellite      | 3         | 3.09%   |
| Acer Swift             | 3         | 3.09%   |
| HP EliteBook           | 2         | 2.06%   |
| Dell Vostro            | 2         | 2.06%   |
| Toshiba TECRA          | 1         | 1.03%   |
| Toshiba PORTEGE        | 1         | 1.03%   |
| Timi TM1701            | 1         | 1.03%   |
| Sony VPCYB15AB         | 1         | 1.03%   |
| Sony VPCEB1S1E         | 1         | 1.03%   |
| Samsung R430           | 1         | 1.03%   |
| Samsung 300E5EV        | 1         | 1.03%   |
| Samsung 270E5K         | 1         | 1.03%   |
| Panasonic CF-C2CCEZXCM | 1         | 1.03%   |
| Packard Bell EasyNote  | 1         | 1.03%   |
| MSI Modern             | 1         | 1.03%   |
| Lenovo Z51-70          | 1         | 1.03%   |
| Lenovo Z50-70          | 1         | 1.03%   |
| Lenovo Legion          | 1         | 1.03%   |
| Howard Computers W350  | 1         | 1.03%   |
| HP Stream              | 1         | 1.03%   |
| HP Presario            | 1         | 1.03%   |
| HP OMEN                | 1         | 1.03%   |
| HP ENVY                | 1         | 1.03%   |
| HP 255                 | 1         | 1.03%   |
| GPU Company GWTC116-2  | 1         | 1.03%   |
| Google Kip             | 1         | 1.03%   |
| Google Edgar           | 1         | 1.03%   |
| Google Delbin          | 1         | 1.03%   |
| Gigabyte AORUS         | 1         | 1.03%   |
| Framework Laptop       | 1         | 1.03%   |
| Chuwi LapBook          | 1         | 1.03%   |
| AZW SEi                | 1         | 1.03%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 12        | 12.37%  |
| 2018 | 11        | 11.34%  |
| 2019 | 9         | 9.28%   |
| 2017 | 9         | 9.28%   |
| 2012 | 9         | 9.28%   |
| 2021 | 7         | 7.22%   |
| 2014 | 7         | 7.22%   |
| 2020 | 6         | 6.19%   |
| 2013 | 6         | 6.19%   |
| 2011 | 5         | 5.15%   |
| 2010 | 5         | 5.15%   |
| 2008 | 4         | 4.12%   |
| 2015 | 3         | 3.09%   |
| 2009 | 3         | 3.09%   |
| 2007 | 1         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 97        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 97        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 94        | 96.91%  |
| Yes  | 3         | 3.09%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 24        | 24.49%  |
| 8.01-16.0   | 23        | 23.47%  |
| 4.01-8.0    | 19        | 19.39%  |
| 16.01-24.0  | 19        | 19.39%  |
| 32.01-64.0  | 7         | 7.14%   |
| 1.01-2.0    | 3         | 3.06%   |
| 2.01-3.0    | 2         | 2.04%   |
| 64.01-256.0 | 1         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 38        | 36.89%  |
| 2.01-3.0  | 30        | 29.13%  |
| 4.01-8.0  | 14        | 13.59%  |
| 3.01-4.0  | 11        | 10.68%  |
| 0.51-1.0  | 8         | 7.77%   |
| 8.01-16.0 | 2         | 1.94%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 74.23%  |
| 2      | 24        | 24.74%  |
| 3      | 1         | 1.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 59        | 60.82%  |
| Yes       | 38        | 39.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 81.44%  |
| No        | 18        | 18.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 100%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 81.44%  |
| No        | 18        | 18.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 20        | 20.62%  |
| India              | 8         | 8.25%   |
| Brazil             | 6         | 6.19%   |
| Netherlands        | 5         | 5.15%   |
| UK                 | 3         | 3.09%   |
| Spain              | 3         | 3.09%   |
| Poland             | 3         | 3.09%   |
| Germany            | 3         | 3.09%   |
| France             | 3         | 3.09%   |
| Australia          | 3         | 3.09%   |
| Ukraine            | 2         | 2.06%   |
| Turkey             | 2         | 2.06%   |
| Russia             | 2         | 2.06%   |
| Norway             | 2         | 2.06%   |
| New Zealand        | 2         | 2.06%   |
| Indonesia          | 2         | 2.06%   |
| Guatemala          | 2         | 2.06%   |
| Chile              | 2         | 2.06%   |
| Vietnam            | 1         | 1.03%   |
| Venezuela          | 1         | 1.03%   |
| Switzerland        | 1         | 1.03%   |
| Sweden             | 1         | 1.03%   |
| Saudi Arabia       | 1         | 1.03%   |
| Oman               | 1         | 1.03%   |
| Nepal              | 1         | 1.03%   |
| Mexico             | 1         | 1.03%   |
| Latvia             | 1         | 1.03%   |
| Japan              | 1         | 1.03%   |
| Italy              | 1         | 1.03%   |
| Iran               | 1         | 1.03%   |
| Hungary            | 1         | 1.03%   |
| Greece             | 1         | 1.03%   |
| Finland            | 1         | 1.03%   |
| Dominican Republic | 1         | 1.03%   |
| Czechia            | 1         | 1.03%   |
| China              | 1         | 1.03%   |
| Canada             | 1         | 1.03%   |
| Belgium            | 1         | 1.03%   |
| Belarus            | 1         | 1.03%   |
| Austria            | 1         | 1.03%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Melbourne                 | 3         | 2.91%   |
| Oslo                      | 2         | 1.94%   |
| Guatemala City            | 2         | 1.94%   |
| Columbus                  | 2         | 1.94%   |
| Auckland                  | 2         | 1.94%   |
| Amsterdam                 | 2         | 1.94%   |
| Zhytomyr                  | 1         | 0.97%   |
| Yverdon-les-Bains         | 1         | 0.97%   |
| Wendell                   | 1         | 0.97%   |
| Vineland                  | 1         | 0.97%   |
| Vienna                    | 1         | 0.97%   |
| Vasco da Gama             | 1         | 0.97%   |
| Toronto                   | 1         | 0.97%   |
| Tirana                    | 1         | 0.97%   |
| The Hague                 | 1         | 0.97%   |
| Terranuova Bracciolini    | 1         | 0.97%   |
| Teresopolis               | 1         | 0.97%   |
| Tehran                    | 1         | 0.97%   |
| Stroudsburg               | 1         | 0.97%   |
| Stare Babice              | 1         | 0.97%   |
| St Petersburg             | 1         | 0.97%   |
| Severna Park              | 1         | 0.97%   |
| Semarang                  | 1         | 0.97%   |
| Santo Domingo Este        | 1         | 0.97%   |
| Santiago                  | 1         | 0.97%   |
| San Justo                 | 1         | 0.97%   |
| San Francisco del Rincón | 1         | 0.97%   |
| San Francisco             | 1         | 0.97%   |
| Saint-Just-Saint-Rambert  | 1         | 0.97%   |
| Riyadh                    | 1         | 0.97%   |
| Riga                      | 1         | 0.97%   |
| Red Oak                   | 1         | 0.97%   |
| Quilicura                 | 1         | 0.97%   |
| Portland                  | 1         | 0.97%   |
| Port Orange               | 1         | 0.97%   |
| Pomeroy                   | 1         | 0.97%   |
| Pessac                    | 1         | 0.97%   |
| Paracuellos de Jarama     | 1         | 0.97%   |
| New York                  | 1         | 0.97%   |
| Muscat                    | 1         | 0.97%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 19     | 14.63%  |
| Toshiba             | 15        | 18     | 12.2%   |
| Samsung Electronics | 15        | 16     | 12.2%   |
| Seagate             | 11        | 14     | 8.94%   |
| SanDisk             | 10        | 12     | 8.13%   |
| SK hynix            | 8         | 8      | 6.5%    |
| Kingston            | 8         | 8      | 6.5%    |
| Unknown             | 6         | 6      | 4.88%   |
| Intel               | 6         | 8      | 4.88%   |
| Micron Technology   | 5         | 6      | 4.07%   |
| Crucial             | 3         | 4      | 2.44%   |
| Silicon Motion      | 2         | 2      | 1.63%   |
| Hitachi             | 2         | 2      | 1.63%   |
| Transcend           | 1         | 1      | 0.81%   |
| SABRENT             | 1         | 1      | 0.81%   |
| PNY                 | 1         | 1      | 0.81%   |
| Phison              | 1         | 1      | 0.81%   |
| Lenovo              | 1         | 1      | 0.81%   |
| KIOXIA              | 1         | 1      | 0.81%   |
| KingFast            | 1         | 1      | 0.81%   |
| HGST                | 1         | 1      | 0.81%   |
| Gigabyte Technology | 1         | 1      | 0.81%   |
| FORESEE             | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |
| Advantech           | 1         | 1      | 0.81%   |
| AAPL                | 1         | 1      | 0.81%   |
| A-DATA Technology   | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 5         | 3.97%   |
| SK hynix NVMe SSD Drive 128GB           | 3         | 2.38%   |
| SanDisk NVMe SSD Drive 256GB            | 3         | 2.38%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 2.38%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 2         | 1.59%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 1.59%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.59%   |
| Unknown MMC Card  32GB                  | 2         | 1.59%   |
| Samsung SSD 860 EVO 250GB               | 2         | 1.59%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.79%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.79%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.79%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 0.79%   |
| WDC WD3200BEVT-75ZCT2 320GB             | 1         | 0.79%   |
| WDC WD2500LPVX-22V0TT0 250GB            | 1         | 0.79%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.79%   |
| WDC WD2500BEVT-00A23T0 250GB            | 1         | 0.79%   |
| WDC WD10SPZX-24Z10T0 1TB                | 1         | 0.79%   |
| WDC WD10JPVX-08JC3T5 1TB                | 1         | 0.79%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.79%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB    | 1         | 0.79%   |
| Unknown USB DISK 3.2 250GB              | 1         | 0.79%   |
| Unknown MMC Card  64GB                  | 1         | 0.79%   |
| Unknown MMC Card  128GB                 | 1         | 0.79%   |
| Unknown AJNB4R  16GB                    | 1         | 0.79%   |
| Transcend TS240GSSD220S 240GB           | 1         | 0.79%   |
| Toshiba THNSNJ256GVNU 256GB SSD         | 1         | 0.79%   |
| Toshiba THNS128GG4BNAA 128GB SSD        | 1         | 0.79%   |
| Toshiba NVMe SSD Drive 512GB            | 1         | 0.79%   |
| Toshiba NVMe SSD Drive 256GB            | 1         | 0.79%   |
| Toshiba NVMe SSD Drive 1024GB           | 1         | 0.79%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.79%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.79%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.79%   |
| Toshiba MK5055GSX 500GB                 | 1         | 0.79%   |
| Toshiba KXG60ZNV512G NVMe 512GB         | 1         | 0.79%   |
| SK hynix SC311 SATA 256GB SSD           | 1         | 0.79%   |
| SK hynix PC401 HFS256GD9TNG-62A0A 256GB | 1         | 0.79%   |
| SK hynix NVMe SSD Drive 500GB           | 1         | 0.79%   |
| SK hynix NVMe SSD Drive 256GB           | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 14        | 15     | 35.9%   |
| Seagate | 11        | 14     | 28.21%  |
| Toshiba | 9         | 12     | 23.08%  |
| Hitachi | 2         | 2      | 5.13%   |
| SABRENT | 1         | 1      | 2.56%   |
| HGST    | 1         | 1      | 2.56%   |
| AAPL    | 1         | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 9      | 23.08%  |
| Kingston            | 5         | 5      | 12.82%  |
| SanDisk             | 4         | 4      | 10.26%  |
| Micron Technology   | 4         | 5      | 10.26%  |
| Intel               | 3         | 4      | 7.69%   |
| Crucial             | 3         | 4      | 7.69%   |
| WDC                 | 2         | 2      | 5.13%   |
| Toshiba             | 2         | 2      | 5.13%   |
| Transcend           | 1         | 1      | 2.56%   |
| SK hynix            | 1         | 1      | 2.56%   |
| PNY                 | 1         | 1      | 2.56%   |
| Gigabyte Technology | 1         | 1      | 2.56%   |
| FORESEE             | 1         | 1      | 2.56%   |
| Apple               | 1         | 1      | 2.56%   |
| Advantech           | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 38        | 46     | 32.76%  |
| SSD     | 37        | 42     | 31.9%   |
| NVMe    | 33        | 41     | 28.45%  |
| MMC     | 6         | 6      | 5.17%   |
| Unknown | 2         | 2      | 1.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 65        | 85     | 59.63%  |
| NVMe | 33        | 41     | 30.28%  |
| MMC  | 6         | 6      | 5.5%    |
| SAS  | 5         | 5      | 4.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 59     | 65.28%  |
| 0.51-1.0   | 23        | 27     | 31.94%  |
| 1.01-2.0   | 2         | 2      | 2.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 44        | 44.9%   |
| 251-500    | 21        | 21.43%  |
| 501-1000   | 14        | 14.29%  |
| 1001-2000  | 7         | 7.14%   |
| 21-50      | 4         | 4.08%   |
| 51-100     | 3         | 3.06%   |
| 1-20       | 2         | 2.04%   |
| Unknown    | 2         | 2.04%   |
| 2001-3000  | 1         | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 40        | 38.83%  |
| 21-50     | 19        | 18.45%  |
| 51-100    | 14        | 13.59%  |
| 101-250   | 12        | 11.65%  |
| 251-500   | 11        | 10.68%  |
| 1001-2000 | 3         | 2.91%   |
| 501-1000  | 2         | 1.94%   |
| Unknown   | 2         | 1.94%   |

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
| Detected | 67        | 94     | 65.05%  |
| Works    | 31        | 37     | 30.1%   |
| Malfunc  | 5         | 6      | 4.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 70        | 60.87%  |
| AMD                          | 10        | 8.7%    |
| SK hynix                     | 7         | 6.09%   |
| SanDisk                      | 6         | 5.22%   |
| Samsung Electronics          | 6         | 5.22%   |
| Toshiba America Info Systems | 5         | 4.35%   |
| Kingston Technology Company  | 3         | 2.61%   |
| Silicon Motion               | 2         | 1.74%   |
| Phison Electronics           | 1         | 0.87%   |
| Nvidia                       | 1         | 0.87%   |
| Micron Technology            | 1         | 0.87%   |
| Lenovo                       | 1         | 0.87%   |
| JMicron Technology           | 1         | 0.87%   |
| ADATA Technology             | 1         | 0.87%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 10.92%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 7.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 6.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 5.04%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 3.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 3.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 3.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 2.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.52%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 2.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 2.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.68%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 2         | 1.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 1.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.68%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 1.68%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 1.68%   |
| Intel SSD 600P Series                                                          | 2         | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.68%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.84%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.84%   |
| SK hynix PC300 NVMe Solid State Drive 256GB                                    | 1         | 0.84%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 1         | 0.84%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.84%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.84%   |
| Samsung NVMe SSD Controller 980                                                | 1         | 0.84%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.84%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.84%   |
| Micron NVMe Storage Controller                                                 | 1         | 0.84%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.84%   |
| JMicron JMB360 AHCI Controller                                                 | 1         | 0.84%   |
| Intel SSD 660P Series                                                          | 1         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 74        | 65.49%  |
| NVMe | 32        | 28.32%  |
| RAID | 4         | 3.54%   |
| IDE  | 3         | 2.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 87.63%  |
| AMD    | 12        | 12.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 6.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 4.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 3.09%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 3.09%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 3.09%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 2.06%   |
| Intel Core i7-4600M CPU @ 2.90GHz             | 2         | 2.06%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 2.06%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 2.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.06%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 2.06%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 2         | 2.06%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 2.06%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.06%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 2.06%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 1.03%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 1.03%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 1.03%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.03%   |
| Intel Pentium 3556U @ 1.70GHz                 | 1         | 1.03%   |
| Intel Core M-5Y51 CPU @ 1.10GHz               | 1         | 1.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.03%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 1.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 1.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.03%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.03%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.03%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 1.03%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1.03%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.03%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.03%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 1         | 1.03%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1         | 1.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.03%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.03%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.03%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 34.02%  |
| Intel Core i7           | 24        | 24.74%  |
| Intel Celeron           | 8         | 8.25%   |
| Intel Core i3           | 6         | 6.19%   |
| AMD Ryzen 7             | 5         | 5.15%   |
| Other                   | 4         | 4.12%   |
| Intel Core 2 Duo        | 4         | 4.12%   |
| AMD Ryzen 5             | 4         | 4.12%   |
| Intel Pentium           | 2         | 2.06%   |
| Intel Pentium Silver    | 1         | 1.03%   |
| Intel Pentium Dual-Core | 1         | 1.03%   |
| Intel Pentium Dual      | 1         | 1.03%   |
| Intel Core M            | 1         | 1.03%   |
| Intel Atom              | 1         | 1.03%   |
| AMD E1                  | 1         | 1.03%   |
| AMD E                   | 1         | 1.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 55        | 56.7%   |
| 4      | 33        | 34.02%  |
| 6      | 5         | 5.15%   |
| 8      | 3         | 3.09%   |
| 1      | 1         | 1.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 97        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 75        | 77.32%  |
| 1      | 22        | 22.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 93        | 94.9%   |
| Unknown        | 5         | 5.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ea    | 9         | 9.09%   |
| 0x306a9    | 8         | 8.08%   |
| 0x806e9    | 7         | 7.07%   |
| 0x206a7    | 7         | 7.07%   |
| Unknown    | 6         | 6.06%   |
| 0x40651    | 5         | 5.05%   |
| 0x806ec    | 4         | 4.04%   |
| 0x306c3    | 4         | 4.04%   |
| 0x20655    | 4         | 4.04%   |
| 0x906ea    | 3         | 3.03%   |
| 0x906e9    | 3         | 3.03%   |
| 0x806c1    | 3         | 3.03%   |
| 0x706a1    | 3         | 3.03%   |
| 0x406e3    | 3         | 3.03%   |
| 0x306d4    | 3         | 3.03%   |
| 0x1067a    | 3         | 3.03%   |
| 0x08108102 | 3         | 3.03%   |
| 0x6fd      | 2         | 2.02%   |
| 0x506e3    | 2         | 2.02%   |
| 0x30678    | 2         | 2.02%   |
| 0xa0652    | 1         | 1.01%   |
| 0x906c0    | 1         | 1.01%   |
| 0x806eb    | 1         | 1.01%   |
| 0x706a8    | 1         | 1.01%   |
| 0x20652    | 1         | 1.01%   |
| 0x10676    | 1         | 1.01%   |
| 0x10661    | 1         | 1.01%   |
| 0x0a50000c | 1         | 1.01%   |
| 0x08608103 | 1         | 1.01%   |
| 0x08600106 | 1         | 1.01%   |
| 0x08108109 | 1         | 1.01%   |
| 0x0810100b | 1         | 1.01%   |
| 0x06006704 | 1         | 1.01%   |
| 0x05000119 | 1         | 1.01%   |
| 0x05000029 | 1         | 1.01%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 28.87%  |
| Haswell       | 10        | 10.31%  |
| IvyBridge     | 8         | 8.25%   |
| SandyBridge   | 7         | 7.22%   |
| Westmere      | 5         | 5.15%   |
| Skylake       | 5         | 5.15%   |
| Zen+          | 4         | 4.12%   |
| Penryn        | 4         | 4.12%   |
| Goldmont plus | 4         | 4.12%   |
| TigerLake     | 3         | 3.09%   |
| Silvermont    | 3         | 3.09%   |
| Core          | 3         | 3.09%   |
| Broadwell     | 3         | 3.09%   |
| Bobcat        | 2         | 2.06%   |
| Unknown       | 2         | 2.06%   |
| Zen 3         | 1         | 1.03%   |
| Zen 2         | 1         | 1.03%   |
| Zen           | 1         | 1.03%   |
| Tremont       | 1         | 1.03%   |
| Excavator     | 1         | 1.03%   |
| CometLake     | 1         | 1.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 79        | 61.72%  |
| Nvidia | 28        | 21.88%  |
| AMD    | 21        | 16.41%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                    | 8         | 6.15%   |
| Intel HD Graphics 620                                                     | 8         | 6.15%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 5.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.62%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6         | 4.62%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 3.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 3.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 3.08%   |
| Nvidia GM108M [GeForce 940MX]                                             | 3         | 2.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 2.31%   |
| Intel HD Graphics 630                                                     | 3         | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 2.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.31%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 2         | 1.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 1.54%   |
| Nvidia GM108M [GeForce 930MX]                                             | 2         | 1.54%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.54%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 2         | 1.54%   |
| Nvidia GF108M [GeForce GT 540M]                                           | 2         | 1.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.54%   |
| Intel HD Graphics 5500                                                    | 2         | 1.54%   |
| Intel HD Graphics 530                                                     | 2         | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.54%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                  | 2         | 1.54%   |
| AMD Lucienne                                                              | 2         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.77%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.77%   |
| Nvidia GK208M [GeForce GT 730M]                                           | 1         | 0.77%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.77%   |
| Nvidia GK107GLM [Quadro K1000M]                                           | 1         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 52.58%  |
| Intel + Nvidia | 24        | 24.74%  |
| 1 x AMD        | 14        | 14.43%  |
| Intel + AMD    | 4         | 4.12%   |
| AMD + Nvidia   | 3         | 3.09%   |
| 1 x Nvidia     | 1         | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 79        | 81.44%  |
| Proprietary | 18        | 18.56%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 55.67%  |
| 1.01-2.0   | 17        | 17.53%  |
| 0.51-1.0   | 10        | 10.31%  |
| 0.01-0.5   | 7         | 7.22%   |
| 3.01-4.0   | 6         | 6.19%   |
| 5.01-6.0   | 3         | 3.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 24.14%  |
| LG Display              | 16        | 13.79%  |
| BOE                     | 14        | 12.07%  |
| Chimei Innolux          | 13        | 11.21%  |
| Samsung Electronics     | 12        | 10.34%  |
| Lenovo                  | 4         | 3.45%   |
| Goldstar                | 4         | 3.45%   |
| Sharp                   | 3         | 2.59%   |
| PANDA                   | 2         | 1.72%   |
| Dell                    | 2         | 1.72%   |
| Chi Mei Optoelectronics | 2         | 1.72%   |
| BenQ                    | 2         | 1.72%   |
| Apple                   | 2         | 1.72%   |
| AOC                     | 2         | 1.72%   |
| Ancor Communications    | 2         | 1.72%   |
| ___                     | 1         | 0.86%   |
| Unknown                 | 1         | 0.86%   |
| Toshiba                 | 1         | 0.86%   |
| Sony                    | 1         | 0.86%   |
| Philips                 | 1         | 0.86%   |
| GKK                     | 1         | 0.86%   |
| CSO                     | 1         | 0.86%   |
| Acer                    | 1         | 0.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch      | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 1.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.71%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.85%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.85%   |
| Toshiba Internal LCD TOS5091 1366x768 344x193mm 15.5-inch             | 1         | 0.85%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.85%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.85%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.85%   |
| Samsung Electronics SyncMaster SAM0375 1680x1050 494x320mm 23.2-inch  | 1         | 0.85%   |
| Samsung Electronics SMS24A650 SAM082A 1920x1080 531x299mm 24.0-inch   | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC4545 1280x800 331x207mm 15.4-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3641 1366x768 353x198mm 15.9-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC4250 1920x1080 276x156mm 12.5-inch | 1         | 0.85%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.85%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.85%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch     | 1         | 0.85%   |
| Philips 273PLPH PHL08A8 1920x1080 598x336mm 27.0-inch                 | 1         | 0.85%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.85%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.85%   |
| LG Display LCD Monitor LGD06FB 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0570 1920x1080 344x194mm 15.5-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.85%   |
| LG Display LCD Monitor LGD0404 1366x768 277x156mm 12.5-inch           | 1         | 0.85%   |
| LG Display LCD Monitor LGD0383 1600x900 382x215mm 17.3-inch           | 1         | 0.85%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 45.79%  |
| 1366x768 (WXGA)    | 34        | 31.78%  |
| 1600x900 (HD+)     | 7         | 6.54%   |
| 3840x2160 (4K)     | 3         | 2.8%    |
| 1440x900 (WXGA+)   | 3         | 2.8%    |
| 1280x800 (WXGA)    | 3         | 2.8%    |
| 3840x1080          | 1         | 0.93%   |
| 2560x1600          | 1         | 0.93%   |
| 2560x1440 (QHD)    | 1         | 0.93%   |
| 2560x1080          | 1         | 0.93%   |
| 2256x1504          | 1         | 0.93%   |
| 1920x1200 (WUXGA)  | 1         | 0.93%   |
| 1680x1050 (WSXGA+) | 1         | 0.93%   |
| 1360x768           | 1         | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 52        | 45.22%  |
| 13      | 20        | 17.39%  |
| 14      | 13        | 11.3%   |
| 17      | 7         | 6.09%   |
| 24      | 4         | 3.48%   |
| 21      | 4         | 3.48%   |
| 23      | 3         | 2.61%   |
| 27      | 2         | 1.74%   |
| 12      | 2         | 1.74%   |
| 11      | 2         | 1.74%   |
| 72      | 1         | 0.87%   |
| 49      | 1         | 0.87%   |
| 40      | 1         | 0.87%   |
| 34      | 1         | 0.87%   |
| 18      | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 73        | 64.04%  |
| 201-300     | 13        | 11.4%   |
| 351-400     | 9         | 7.89%   |
| 501-600     | 8         | 7.02%   |
| 401-500     | 6         | 5.26%   |
| 801-900     | 1         | 0.88%   |
| 701-800     | 1         | 0.88%   |
| 1501-2000   | 1         | 0.88%   |
| 1001-1500   | 1         | 0.88%   |
| Unknown     | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 89        | 89%     |
| 16/10 | 7         | 7%      |
| 3/2   | 2         | 2%      |
| 32/9  | 1         | 1%      |
| 21/9  | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 51        | 44.35%  |
| 81-90          | 26        | 22.61%  |
| 201-250        | 9         | 7.83%   |
| 71-80          | 7         | 6.09%   |
| 121-130        | 7         | 6.09%   |
| 61-70          | 2         | 1.74%   |
| 51-60          | 2         | 1.74%   |
| 301-350        | 2         | 1.74%   |
| 501-1000       | 2         | 1.74%   |
| More than 1000 | 1         | 0.87%   |
| 351-500        | 1         | 0.87%   |
| 251-300        | 1         | 0.87%   |
| 151-200        | 1         | 0.87%   |
| 141-150        | 1         | 0.87%   |
| 91-100         | 1         | 0.87%   |
| Unknown        | 1         | 0.87%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 45        | 40.54%  |
| 101-120       | 36        | 32.43%  |
| 51-100        | 17        | 15.32%  |
| 161-240       | 8         | 7.21%   |
| More than 240 | 3         | 2.7%    |
| 1-50          | 1         | 0.9%    |
| Unknown       | 1         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 80        | 81.63%  |
| 2     | 16        | 16.33%  |
| 3     | 2         | 2.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 51        | 32.28%  |
| Realtek Semiconductor         | 46        | 29.11%  |
| Qualcomm Atheros              | 29        | 18.35%  |
| Broadcom                      | 9         | 5.7%    |
| Marvell Technology Group      | 4         | 2.53%   |
| Ralink                        | 2         | 1.27%   |
| MediaTek                      | 2         | 1.27%   |
| Dell                          | 2         | 1.27%   |
| TP-Link                       | 1         | 0.63%   |
| T & A Mobile Phones           | 1         | 0.63%   |
| Sierra Wireless               | 1         | 0.63%   |
| Samsung Electronics           | 1         | 0.63%   |
| Ralink Technology             | 1         | 0.63%   |
| Qualcomm                      | 1         | 0.63%   |
| OnePlus Technology (Shenzhen) | 1         | 0.63%   |
| Nvidia                        | 1         | 0.63%   |
| Lenovo                        | 1         | 0.63%   |
| Jolla Oy                      | 1         | 0.63%   |
| Hewlett-Packard               | 1         | 0.63%   |
| ASIX Electronics              | 1         | 0.63%   |
| Android                       | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 16.49%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 4.26%   |
| Intel Wireless 8265 / 8275                                        | 8         | 4.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 3.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 2.66%   |
| Intel Wireless 7260                                               | 5         | 2.66%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 2.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 1.6%    |
| Intel Wireless 8260                                               | 3         | 1.6%    |
| Intel Wireless 7265                                               | 3         | 1.6%    |
| Intel Wireless 3165                                               | 3         | 1.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.06%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.06%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.06%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                     | 2         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.06%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.06%   |
| Broadcom BCM4311 802.11b/g WLAN                                   | 2         | 1.06%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.53%   |
| T & A Mobile Phones Unisoc Phone                                  | 1         | 0.53%   |
| Sierra Wireless EM7305                                            | 1         | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.53%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.53%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.53%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 50%     |
| Qualcomm Atheros      | 26        | 25.49%  |
| Realtek Semiconductor | 10        | 9.8%    |
| Broadcom              | 7         | 6.86%   |
| Ralink                | 2         | 1.96%   |
| MediaTek              | 2         | 1.96%   |
| Sierra Wireless       | 1         | 0.98%   |
| Ralink Technology     | 1         | 0.98%   |
| Hewlett-Packard       | 1         | 0.98%   |
| Dell                  | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 7.84%   |
| Intel Wireless 8265 / 8275                                     | 8         | 7.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 5.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 4.9%    |
| Intel Wireless 7260                                            | 5         | 4.9%    |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 3.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 2.94%   |
| Intel Wireless 8260                                            | 3         | 2.94%   |
| Intel Wireless 7265                                            | 3         | 2.94%   |
| Intel Wireless 3165                                            | 3         | 2.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.96%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.96%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 1.96%   |
| Sierra Wireless EM7305                                         | 1         | 0.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.98%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.98%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.98%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.98%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.98%   |
| Intel Wireless 3160                                            | 1         | 0.98%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 1         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.98%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 41        | 49.4%   |
| Intel                    | 22        | 26.51%  |
| Qualcomm Atheros         | 5         | 6.02%   |
| Marvell Technology Group | 4         | 4.82%   |
| Broadcom                 | 3         | 3.61%   |
| TP-Link                  | 1         | 1.2%    |
| Samsung Electronics      | 1         | 1.2%    |
| Qualcomm                 | 1         | 1.2%    |
| Nvidia                   | 1         | 1.2%    |
| Lenovo                   | 1         | 1.2%    |
| Jolla Oy                 | 1         | 1.2%    |
| ASIX Electronics         | 1         | 1.2%    |
| Android                  | 1         | 1.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 31        | 37.35%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 8.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 6         | 7.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 2.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 2.41%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 2.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 2.41%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 1.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 1.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.2%    |
| Qualcomm QM215-QRD _SN:E72764DE                                                | 1         | 1.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 1.2%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.2%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 1.2%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 1.2%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 1.2%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.2%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 1         | 1.2%    |
| Lenovo Thinkpad LAN                                                            | 1         | 1.2%    |
| Jolla Oy Jolla Phone Developer                                                 | 1         | 1.2%    |
| Intel Ethernet Connection I219-V                                               | 1         | 1.2%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.2%    |
| Intel Ethernet Connection I218-LM                                              | 1         | 1.2%    |
| Intel Ethernet Connection I217-V                                               | 1         | 1.2%    |
| Intel Ethernet Connection I217-LM                                              | 1         | 1.2%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 1.2%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.2%    |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.2%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 1.2%    |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 1.2%    |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.2%    |
| Android Android                                                                | 1         | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 97        | 54.19%  |
| Ethernet | 79        | 44.13%  |
| Unknown  | 2         | 1.12%   |
| Modem    | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 86.73%  |
| Ethernet | 13        | 13.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 75        | 77.32%  |
| 1     | 21        | 21.65%  |
| 0     | 1         | 1.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 89        | 90.82%  |
| Yes  | 9         | 9.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 50.63%  |
| Qualcomm Atheros Communications | 9         | 11.39%  |
| Lite-On Technology              | 9         | 11.39%  |
| Realtek Semiconductor           | 4         | 5.06%   |
| Broadcom                        | 4         | 5.06%   |
| IMC Networks                    | 3         | 3.8%    |
| Foxconn / Hon Hai               | 2         | 2.53%   |
| Apple                           | 2         | 2.53%   |
| Toshiba                         | 1         | 1.27%   |
| Ralink                          | 1         | 1.27%   |
| MediaTek                        | 1         | 1.27%   |
| Hewlett-Packard                 | 1         | 1.27%   |
| Dell                            | 1         | 1.27%   |
| Cambridge Silicon Radio         | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 22        | 27.85%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 6.33%   |
| Intel AX200 Bluetooth                                                               | 5         | 6.33%   |
| Intel AX201 Bluetooth                                                               | 4         | 5.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 3.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 3.8%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 2.53%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 2.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 2.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 2.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 2.53%   |
| Intel AX210 Bluetooth                                                               | 2         | 2.53%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.53%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 1.27%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.27%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 1.27%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.27%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 1.27%   |
| MediaTek Wireless_Device                                                            | 1         | 1.27%   |
| Lite-On Wireless_Device                                                             | 1         | 1.27%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.27%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.27%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 1.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.27%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.27%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 1.27%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.27%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.27%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 84        | 71.79%  |
| AMD                 | 17        | 14.53%  |
| Nvidia              | 13        | 11.11%  |
| Samsung Electronics | 1         | 0.85%   |
| GYROCOM C&C         | 1         | 0.85%   |
| Conexant Systems    | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 13.67%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 6.47%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 6.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 4.32%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 4.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.88%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 2.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 2.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.16%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 2.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.16%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.16%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 2.16%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 1.44%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 1.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.44%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.44%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.44%   |
| Samsung Electronics USBC Headset                                                                  | 1         | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.72%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.72%   |
| GYROCOM C&C Fiio E10                                                                              | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 17        | 30.91%  |
| SK hynix            | 9         | 16.36%  |
| Crucial             | 5         | 9.09%   |
| A-DATA Technology   | 5         | 9.09%   |
| Micron Technology   | 4         | 7.27%   |
| Kingston            | 4         | 7.27%   |
| Nanya Technology    | 3         | 5.45%   |
| Unknown             | 2         | 3.64%   |
| Ramaxel Technology  | 2         | 3.64%   |
| Elpida              | 2         | 3.64%   |
| Team                | 1         | 1.82%   |
| G.Skill             | 1         | 1.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 3.57%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 3.57%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 1.79%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.79%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 1.79%   |
| SK hynix RAM Module 2048MB SODIMM DDR2 800MT/s                   | 1         | 1.79%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.79%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.79%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.79%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 1.79%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                 | 1         | 1.79%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.79%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.79%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 1.79%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 1         | 1.79%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.79%   |
| Samsung RAM K4E8E324EB-EGCF 2GB SODIMM LPDDR3 1867MT/s           | 1         | 1.79%   |
| Ramaxel RAM RMT3170EB68E9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| Ramaxel RAM RMT1970ED48E8F1066 2GB SODIMM DDR3 1067MT/s          | 1         | 1.79%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.79%   |
| Micron RAM 8HTF12864HDY-667E1 1GB SODIMM DDR2 667MT/s            | 1         | 1.79%   |
| Micron RAM 8ATF1G64HZ-2G3H1 8GB SODIMM DDR4 2400MT/s             | 1         | 1.79%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.79%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Kingston RAM ACR26D4S9S8ME-8 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Kingston RAM 99U5663-003.A00G 16GB SODIMM DDR4 2400MT/s          | 1         | 1.79%   |
| Kingston RAM 99U5428-063.A00LF 8GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 50%     |
| DDR3   | 13        | 29.55%  |
| LPDDR3 | 4         | 9.09%   |
| DDR2   | 2         | 4.55%   |
| SDRAM  | 1         | 2.27%   |
| LPDDR4 | 1         | 2.27%   |
| DDR    | 1         | 2.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 93.02%  |
| Row Of Chips | 3         | 6.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 17        | 37.78%  |
| 4096  | 11        | 24.44%  |
| 16384 | 7         | 15.56%  |
| 2048  | 6         | 13.33%  |
| 32768 | 3         | 6.67%   |
| 1024  | 1         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 10        | 20.41%  |
| 2667    | 9         | 18.37%  |
| 3200    | 6         | 12.24%  |
| 2400    | 6         | 12.24%  |
| 2133    | 6         | 12.24%  |
| 1334    | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| 4267    | 1         | 2.04%   |
| 3266    | 1         | 2.04%   |
| 2048    | 1         | 2.04%   |
| 1867    | 1         | 2.04%   |
| 1333    | 1         | 2.04%   |
| 1067    | 1         | 2.04%   |
| 800     | 1         | 2.04%   |
| 667     | 1         | 2.04%   |

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
| Chicony Electronics                    | 21        | 23.33%  |
| Realtek Semiconductor                  | 11        | 12.22%  |
| Microdia                               | 9         | 10%     |
| IMC Networks                           | 8         | 8.89%   |
| Quanta                                 | 6         | 6.67%   |
| Sunplus Innovation Technology          | 5         | 5.56%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.44%   |
| Acer                                   | 4         | 4.44%   |
| Suyin                                  | 3         | 3.33%   |
| Logitech                               | 3         | 3.33%   |
| Lite-On Technology                     | 3         | 3.33%   |
| Syntek                                 | 2         | 2.22%   |
| Lenovo                                 | 2         | 2.22%   |
| Importek                               | 2         | 2.22%   |
| Z-Star Microelectronics                | 1         | 1.11%   |
| Unknown                                | 1         | 1.11%   |
| Silicon Motion                         | 1         | 1.11%   |
| Microsoft                              | 1         | 1.11%   |
| Intel                                  | 1         | 1.11%   |
| Bison Electronics                      | 1         | 1.11%   |
| Apple                                  | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                                     | 6         | 6.59%   |
| Chicony Integrated Camera                                             | 4         | 4.4%    |
| Sunplus Integrated_Webcam_HD                                          | 3         | 3.3%    |
| Realtek HD WebCam                                                     | 3         | 3.3%    |
| Microdia Integrated_Webcam_HD                                         | 3         | 3.3%    |
| IMC Networks USB2.0 HD UVC WebCam                                     | 3         | 3.3%    |
| Suyin HP TrueVision HD Integrated Webcam                              | 2         | 2.2%    |
| Realtek Integrated Webcam_HD                                          | 2         | 2.2%    |
| Quanta HD User Facing                                                 | 2         | 2.2%    |
| Microdia USB 2.0 Camera                                               | 2         | 2.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                                    | 2         | 2.2%    |
| IMC Networks Integrated Camera                                        | 2         | 2.2%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                         | 2         | 2.2%    |
| Z-Star Webcam                                                         | 1         | 1.1%    |
| Unknown ATIV VGA CAMERA                                               | 1         | 1.1%    |
| Syntek USB2.0 Camera                                                  | 1         | 1.1%    |
| Syntek Integrated Camera                                              | 1         | 1.1%    |
| Suyin 1.3M HD WebCam                                                  | 1         | 1.1%    |
| Sunplus Laptop_Integrated_Webcam_HD                                   | 1         | 1.1%    |
| Sunplus Laptop Integrated WebCam HD                                   | 1         | 1.1%    |
| Silicon Motion WebCam SC-10HDD12636N                                  | 1         | 1.1%    |
| Realtek Laptop Camera                                                 | 1         | 1.1%    |
| Realtek Integrated_Webcam_HD                                          | 1         | 1.1%    |
| Realtek Integrated Webcam HD                                          | 1         | 1.1%    |
| Realtek Integrated Webcam                                             | 1         | 1.1%    |
| Realtek Integrated Camera                                             | 1         | 1.1%    |
| Realtek HP Truevision HD                                              | 1         | 1.1%    |
| Quanta VGA WebCam                                                     | 1         | 1.1%    |
| Quanta USB2.0 HD UVC WebCam                                           | 1         | 1.1%    |
| Quanta HP Wide Vision HD Camera                                       | 1         | 1.1%    |
| Quanta HP TrueVision HD Webcam                                        | 1         | 1.1%    |
| Microsoft LifeCam Studio                                              | 1         | 1.1%    |
| Microdia Webcam                                                       | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M | 1         | 1.1%    |
| Microdia Integrated Webcam HD                                         | 1         | 1.1%    |
| Microdia Dell Laptop Integrated Webcam HD                             | 1         | 1.1%    |
| Logitech Webcam C310                                                  | 1         | 1.1%    |
| Logitech Webcam C270                                                  | 1         | 1.1%    |
| Logitech HD Pro Webcam C920                                           | 1         | 1.1%    |
| Lite-On Integrated Camera                                             | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 47.83%  |
| Synaptics                  | 3         | 13.04%  |
| Upek                       | 2         | 8.7%    |
| LighTuning Technology      | 2         | 8.7%    |
| Elan Microelectronics      | 2         | 8.7%    |
| AuthenTec                  | 2         | 8.7%    |
| Shenzhen Goodix Technology | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 17.39%  |
| Validity Sensors Fingerprint scanner                   | 2         | 8.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 8.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 8.7%    |
| Elan ELAN:Fingerprint                                  | 2         | 8.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.35%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.35%   |
| Validity Sensors VFS491                                | 1         | 4.35%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.35%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.35%   |
| Upek TCS5B Fingerprint sensor                          | 1         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 4.35%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 4.35%   |
| AuthenTec Fingerprint Sensor                           | 1         | 4.35%   |
| AuthenTec AES2810                                      | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 33.33%  |
| Upek        | 2         | 22.22%  |
| Broadcom    | 2         | 22.22%  |
| O2 Micro    | 1         | 11.11%  |
| Lenovo      | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 3         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 22.22%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 11.11%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 11.11%  |
| Broadcom 5880                                              | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 59        | 60.82%  |
| 1     | 25        | 25.77%  |
| 2     | 13        | 13.4%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 23        | 43.4%   |
| Net/wireless          | 8         | 15.09%  |
| Chipcard              | 8         | 15.09%  |
| Graphics card         | 5         | 9.43%   |
| Multimedia controller | 4         | 7.55%   |
| Unassigned class      | 1         | 1.89%   |
| Storage               | 1         | 1.89%   |
| Net/ethernet          | 1         | 1.89%   |
| Camera                | 1         | 1.89%   |
| Bluetooth             | 1         | 1.89%   |


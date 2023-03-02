Linux in Argentina - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Argentina.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Argentina/Desktop/README.md) and [notebooks](/Location/Argentina/Notebook/README.md).

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

Total: 2403

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [aefca0b663](https://linux-hardware.org/?probe=aefca0b663) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [12ccf2fe8b](https://linux-hardware.org/?probe=12ccf2fe8b) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [c7bb2ebe8b](https://linux-hardware.org/?probe=c7bb2ebe8b) | Feb 24, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [916f372721](https://linux-hardware.org/?probe=916f372721) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [6e82a5c5d6](https://linux-hardware.org/?probe=6e82a5c5d6) | Feb 24, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f7d34fdd3a](https://linux-hardware.org/?probe=f7d34fdd3a) | Feb 24, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a37b20471b](https://linux-hardware.org/?probe=a37b20471b) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a5f65720f5](https://linux-hardware.org/?probe=a5f65720f5) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [cfcf2ff473](https://linux-hardware.org/?probe=cfcf2ff473) | Feb 21, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6e97a3ff67](https://linux-hardware.org/?probe=6e97a3ff67) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| Dell          | Inspiron 3502               | Notebook    | [224f4edab7](https://linux-hardware.org/?probe=224f4edab7) | Feb 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [008d5e19e1](https://linux-hardware.org/?probe=008d5e19e1) | Feb 20, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b4b87d47fb](https://linux-hardware.org/?probe=b4b87d47fb) | Feb 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [38a92c4ace](https://linux-hardware.org/?probe=38a92c4ace) | Feb 15, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [ba53e8885b](https://linux-hardware.org/?probe=ba53e8885b) | Feb 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| BANGHO        | GM-15Z11 GF1650 i5          | Notebook    | [6cdb04950c](https://linux-hardware.org/?probe=6cdb04950c) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f8de6e450a](https://linux-hardware.org/?probe=f8de6e450a) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [0243fe3621](https://linux-hardware.org/?probe=0243fe3621) | Feb 07, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [eca9b95b61](https://linux-hardware.org/?probe=eca9b95b61) | Feb 07, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a1f33b7267](https://linux-hardware.org/?probe=a1f33b7267) | Feb 06, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [5ae73f08c5](https://linux-hardware.org/?probe=5ae73f08c5) | Feb 06, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [32f4028033](https://linux-hardware.org/?probe=32f4028033) | Feb 05, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [93ee4435a2](https://linux-hardware.org/?probe=93ee4435a2) | Feb 03, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [86667a843f](https://linux-hardware.org/?probe=86667a843f) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [03540bd8e5](https://linux-hardware.org/?probe=03540bd8e5) | Feb 02, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a6584159ac](https://linux-hardware.org/?probe=a6584159ac) | Feb 02, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| ECS           | A55F-M4                     | Desktop     | [08af507321](https://linux-hardware.org/?probe=08af507321) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [f6d37d568c](https://linux-hardware.org/?probe=f6d37d568c) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [9fab32d6a5](https://linux-hardware.org/?probe=9fab32d6a5) | Feb 01, 2023 |
| Samsung       | SQ35S                       | Notebook    | [7ad1c8a94b](https://linux-hardware.org/?probe=7ad1c8a94b) | Feb 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [298b411767](https://linux-hardware.org/?probe=298b411767) | Jan 31, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5abc8dccdb](https://linux-hardware.org/?probe=5abc8dccdb) | Jan 31, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [5122097b1e](https://linux-hardware.org/?probe=5122097b1e) | Jan 29, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d25a13d2c4](https://linux-hardware.org/?probe=d25a13d2c4) | Jan 28, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b2c04ca4b9](https://linux-hardware.org/?probe=b2c04ca4b9) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [055d033d99](https://linux-hardware.org/?probe=055d033d99) | Jan 24, 2023 |
| Sony          | VPCEA30EL                   | Notebook    | [7de250ffe6](https://linux-hardware.org/?probe=7de250ffe6) | Jan 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| ECS           | A55F-M4                     | Desktop     | [db65e68855](https://linux-hardware.org/?probe=db65e68855) | Jan 23, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [458bb94702](https://linux-hardware.org/?probe=458bb94702) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| BANGHO        | MOV                         | Notebook    | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [212fa962a2](https://linux-hardware.org/?probe=212fa962a2) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [ca60f249a9](https://linux-hardware.org/?probe=ca60f249a9) | Jan 13, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [08638b9441](https://linux-hardware.org/?probe=08638b9441) | Jan 13, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [8243f25120](https://linux-hardware.org/?probe=8243f25120) | Jan 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [86a6601ce5](https://linux-hardware.org/?probe=86a6601ce5) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [46679246b9](https://linux-hardware.org/?probe=46679246b9) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8c480c028a](https://linux-hardware.org/?probe=8c480c028a) | Jan 10, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [ff6c949737](https://linux-hardware.org/?probe=ff6c949737) | Jan 09, 2023 |
| Dell          | Latitude 3490               | Notebook    | [7cf81f6b69](https://linux-hardware.org/?probe=7cf81f6b69) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4334ec8d00](https://linux-hardware.org/?probe=4334ec8d00) | Jan 08, 2023 |
| ASUSTek       | M2N68-AM SE                 | Desktop     | [52a0fe59db](https://linux-hardware.org/?probe=52a0fe59db) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| HP            | 240 G8                      | Notebook    | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [290ccc3261](https://linux-hardware.org/?probe=290ccc3261) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [95db7fffba](https://linux-hardware.org/?probe=95db7fffba) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [aa23d3d6f0](https://linux-hardware.org/?probe=aa23d3d6f0) | Jan 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4473dafda](https://linux-hardware.org/?probe=a4473dafda) | Jan 03, 2023 |
| Positivo      | Z100                        | Notebook    | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [c6c0626dd1](https://linux-hardware.org/?probe=c6c0626dd1) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| Acer          | AO756                       | Notebook    | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [8cbb4aa960](https://linux-hardware.org/?probe=8cbb4aa960) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [d6e7a07be2](https://linux-hardware.org/?probe=d6e7a07be2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| Exo           | Smart Serie M               | Notebook    | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [5004189ba4](https://linux-hardware.org/?probe=5004189ba4) | Dec 26, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [ff69d47b58](https://linux-hardware.org/?probe=ff69d47b58) | Dec 24, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [696403dae4](https://linux-hardware.org/?probe=696403dae4) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7de172c3b1](https://linux-hardware.org/?probe=7de172c3b1) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [1f8d567742](https://linux-hardware.org/?probe=1f8d567742) | Dec 20, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [97aa100931](https://linux-hardware.org/?probe=97aa100931) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [33bbc3a179](https://linux-hardware.org/?probe=33bbc3a179) | Dec 18, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| Dell          | Latitude 5520               | Notebook    | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| Exo           | Smart Serie M               | Notebook    | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [9866855d37](https://linux-hardware.org/?probe=9866855d37) | Dec 13, 2022 |
| Clevo         | M740TU/M760TU               | Notebook    | [5f1a4b58fb](https://linux-hardware.org/?probe=5f1a4b58fb) | Dec 13, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| MSI           | A55M-E33                    | Desktop     | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| Dell          | G15 5515                    | Notebook    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| HP            | Notebook                    | Notebook    | [37eead7e86](https://linux-hardware.org/?probe=37eead7e86) | Dec 07, 2022 |
| BANGHO        | BES T5                      | Notebook    | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7d42818fc5](https://linux-hardware.org/?probe=7d42818fc5) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | Desktop     | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [81eca2f60e](https://linux-hardware.org/?probe=81eca2f60e) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [5841aa11f1](https://linux-hardware.org/?probe=5841aa11f1) | Nov 30, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3f545fe7c9](https://linux-hardware.org/?probe=3f545fe7c9) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Foxconn       | A74ML-K                     | Desktop     | [438e3ff761](https://linux-hardware.org/?probe=438e3ff761) | Nov 27, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | Notebook    | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [036dcac9fa](https://linux-hardware.org/?probe=036dcac9fa) | Nov 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [fdafa2db2a](https://linux-hardware.org/?probe=fdafa2db2a) | Nov 22, 2022 |
| HP            | Notebook                    | Notebook    | [ab824250b9](https://linux-hardware.org/?probe=ab824250b9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [498c078586](https://linux-hardware.org/?probe=498c078586) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [abda5b4aaf](https://linux-hardware.org/?probe=abda5b4aaf) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7ffd8149f4](https://linux-hardware.org/?probe=7ffd8149f4) | Nov 21, 2022 |
| Dell          | Latitude E6510              | Notebook    | [c8b9fa9d0a](https://linux-hardware.org/?probe=c8b9fa9d0a) | Nov 20, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [d22a7fff30](https://linux-hardware.org/?probe=d22a7fff30) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| Exo           | Smart XS1                   | Notebook    | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [3964f95a8c](https://linux-hardware.org/?probe=3964f95a8c) | Nov 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [ef34a2a126](https://linux-hardware.org/?probe=ef34a2a126) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [d82617ae65](https://linux-hardware.org/?probe=d82617ae65) | Nov 15, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [83e4ef99fb](https://linux-hardware.org/?probe=83e4ef99fb) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| ASUSTek       | UX410UAK                    | Notebook    | [6653b6c4a5](https://linux-hardware.org/?probe=6653b6c4a5) | Nov 13, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [842f768168](https://linux-hardware.org/?probe=842f768168) | Nov 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Lenovo        | ThinkPad W541 20EGS0V700    | Notebook    | [d03ec65abc](https://linux-hardware.org/?probe=d03ec65abc) | Nov 08, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d71ebfae8b](https://linux-hardware.org/?probe=d71ebfae8b) | Nov 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | Notebook    | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [f427764e2c](https://linux-hardware.org/?probe=f427764e2c) | Nov 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [deac1b706f](https://linux-hardware.org/?probe=deac1b706f) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [9cf3beb13f](https://linux-hardware.org/?probe=9cf3beb13f) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [36b3303b35](https://linux-hardware.org/?probe=36b3303b35) | Oct 30, 2022 |
| ASUSTek       | TUF H370-PRO GAMING WIFI    | Desktop     | [48cbfa7a78](https://linux-hardware.org/?probe=48cbfa7a78) | Oct 28, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97ee92b9d1](https://linux-hardware.org/?probe=97ee92b9d1) | Oct 28, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [3eeb2624bf](https://linux-hardware.org/?probe=3eeb2624bf) | Oct 27, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bc5db124b](https://linux-hardware.org/?probe=1bc5db124b) | Oct 27, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [9c19f9e755](https://linux-hardware.org/?probe=9c19f9e755) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [eca0e58bd8](https://linux-hardware.org/?probe=eca0e58bd8) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [c6cfa3f96d](https://linux-hardware.org/?probe=c6cfa3f96d) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [e0dce17c1f](https://linux-hardware.org/?probe=e0dce17c1f) | Oct 25, 2022 |
| ASRock        | N68-S                       | Desktop     | [f1f502f834](https://linux-hardware.org/?probe=f1f502f834) | Oct 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [0c60239460](https://linux-hardware.org/?probe=0c60239460) | Oct 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3749438ef1](https://linux-hardware.org/?probe=3749438ef1) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [25db15ea87](https://linux-hardware.org/?probe=25db15ea87) | Oct 24, 2022 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [8f793706c2](https://linux-hardware.org/?probe=8f793706c2) | Oct 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [4a17b0a89d](https://linux-hardware.org/?probe=4a17b0a89d) | Oct 22, 2022 |
| Intel         | Montevina CRB               | Notebook    | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [c8a0b8e94f](https://linux-hardware.org/?probe=c8a0b8e94f) | Oct 20, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [d565cdf4a5](https://linux-hardware.org/?probe=d565cdf4a5) | Oct 19, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [3b8ac4e243](https://linux-hardware.org/?probe=3b8ac4e243) | Oct 19, 2022 |
| Positivo      | AT300i                      | Notebook    | [02190f570b](https://linux-hardware.org/?probe=02190f570b) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1be458024b](https://linux-hardware.org/?probe=1be458024b) | Oct 15, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [85f4236c50](https://linux-hardware.org/?probe=85f4236c50) | Oct 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| BANGHO        | B801 IP-M23.62.06           | All in one  | [5a66a855a8](https://linux-hardware.org/?probe=5a66a855a8) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [6a810d253c](https://linux-hardware.org/?probe=6a810d253c) | Oct 13, 2022 |
| Dell          | Latitude 7420               | Convertible | [dade6a2b21](https://linux-hardware.org/?probe=dade6a2b21) | Oct 13, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7dcd7050ae](https://linux-hardware.org/?probe=7dcd7050ae) | Oct 10, 2022 |
| Positivo      | AT300i                      | Notebook    | [62b9d61028](https://linux-hardware.org/?probe=62b9d61028) | Oct 09, 2022 |
| Positivo      | AT300i                      | Notebook    | [8bbd312832](https://linux-hardware.org/?probe=8bbd312832) | Oct 09, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [6ea2c2d73b](https://linux-hardware.org/?probe=6ea2c2d73b) | Oct 08, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [7f78dda318](https://linux-hardware.org/?probe=7f78dda318) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [0cb27058b8](https://linux-hardware.org/?probe=0cb27058b8) | Oct 07, 2022 |
| ASUSTek       | X505BP                      | Notebook    | [3ebba89d5e](https://linux-hardware.org/?probe=3ebba89d5e) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [11ed7b9f37](https://linux-hardware.org/?probe=11ed7b9f37) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [51a7f36a69](https://linux-hardware.org/?probe=51a7f36a69) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Biostar       | H55 HD                      | Desktop     | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [d5a4d2ae41](https://linux-hardware.org/?probe=d5a4d2ae41) | Sep 28, 2022 |
| Positivo      | SW6H                        | Notebook    | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| System76      | Lemur Pro                   | Notebook    | [35340e6221](https://linux-hardware.org/?probe=35340e6221) | Sep 26, 2022 |
| NSX           | Celeron 14                  | Notebook    | [b8fdb14beb](https://linux-hardware.org/?probe=b8fdb14beb) | Sep 25, 2022 |
| NSX           | Celeron 14                  | Notebook    | [1d358a2828](https://linux-hardware.org/?probe=1d358a2828) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [f038a5908f](https://linux-hardware.org/?probe=f038a5908f) | Sep 23, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| BANGHO        | BES G1529                   | Notebook    | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [e4e09c23e5](https://linux-hardware.org/?probe=e4e09c23e5) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b3350b3f69](https://linux-hardware.org/?probe=b3350b3f69) | Sep 17, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Exo           | Smart XL4                   | Notebook    | [96f159b86f](https://linux-hardware.org/?probe=96f159b86f) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | Desktop     | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| HP            | Pavilion 17                 | Notebook    | [5d9be9b086](https://linux-hardware.org/?probe=5d9be9b086) | Sep 13, 2022 |
| Dell          | Precision 5550              | Notebook    | [82eebd67fd](https://linux-hardware.org/?probe=82eebd67fd) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [105dae5731](https://linux-hardware.org/?probe=105dae5731) | Sep 11, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [c9b78bb640](https://linux-hardware.org/?probe=c9b78bb640) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [7d108d27ee](https://linux-hardware.org/?probe=7d108d27ee) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [86af6e4676](https://linux-hardware.org/?probe=86af6e4676) | Sep 08, 2022 |
| HP            | 245 G6                      | Notebook    | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [35ead5350d](https://linux-hardware.org/?probe=35ead5350d) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fc5e3d8261](https://linux-hardware.org/?probe=fc5e3d8261) | Sep 05, 2022 |
| Intel         | powered classmate PC        | Notebook    | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [115b09b849](https://linux-hardware.org/?probe=115b09b849) | Aug 30, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | Notebook    | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| Exo           | Smart Serie L               | Notebook    | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [9fe64d4a60](https://linux-hardware.org/?probe=9fe64d4a60) | Aug 27, 2022 |
| HP            | Notebook                    | Notebook    | [2d11bc2975](https://linux-hardware.org/?probe=2d11bc2975) | Aug 26, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Standard      | AHV                         | Notebook    | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [c3ddddae2c](https://linux-hardware.org/?probe=c3ddddae2c) | Aug 24, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6c0183592b](https://linux-hardware.org/?probe=6c0183592b) | Aug 23, 2022 |
| Sony          | VGN-NR210FH                 | Notebook    | [8c007bfa55](https://linux-hardware.org/?probe=8c007bfa55) | Aug 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [d4a7a111a7](https://linux-hardware.org/?probe=d4a7a111a7) | Aug 21, 2022 |
| Novatech      | C141WP-I5HS                 | Notebook    | [767c02caeb](https://linux-hardware.org/?probe=767c02caeb) | Aug 20, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97aa39b2ca](https://linux-hardware.org/?probe=97aa39b2ca) | Aug 19, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | Notebook    | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| HP            | Notebook                    | Notebook    | [784ad31f68](https://linux-hardware.org/?probe=784ad31f68) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| PCBOX         | Kant                        | Notebook    | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2a4c496cce](https://linux-hardware.org/?probe=2a4c496cce) | Aug 15, 2022 |
| ASRock        | H55M                        | Desktop     | [8d0bd0d2d2](https://linux-hardware.org/?probe=8d0bd0d2d2) | Aug 15, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [c001e6e62b](https://linux-hardware.org/?probe=c001e6e62b) | Aug 12, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [6b5082a45c](https://linux-hardware.org/?probe=6b5082a45c) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d77caddb55](https://linux-hardware.org/?probe=d77caddb55) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| HP            | Pavilion 17                 | Notebook    | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [a6f68827fb](https://linux-hardware.org/?probe=a6f68827fb) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | Notebook    | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [18d8a04343](https://linux-hardware.org/?probe=18d8a04343) | Aug 08, 2022 |
| Toshiba       | Satellite Pro L300D         | Notebook    | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| MSI           | CR620                       | Notebook    | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| Intel         | 945GCT-M                    | Desktop     | [0481d5180e](https://linux-hardware.org/?probe=0481d5180e) | Aug 06, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [ab52d0fc52](https://linux-hardware.org/?probe=ab52d0fc52) | Aug 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [0b4eaa2b43](https://linux-hardware.org/?probe=0b4eaa2b43) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [beaaaa6f6e](https://linux-hardware.org/?probe=beaaaa6f6e) | Aug 03, 2022 |
| LG Electro... | R480-L.B211P1               | Notebook    | [307f422c53](https://linux-hardware.org/?probe=307f422c53) | Aug 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [a484fb9cc8](https://linux-hardware.org/?probe=a484fb9cc8) | Aug 02, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Toshiba       | Satellite-C845              | Notebook    | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [047d3c88ad](https://linux-hardware.org/?probe=047d3c88ad) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [14bbcb7e47](https://linux-hardware.org/?probe=14bbcb7e47) | Jul 30, 2022 |
| ASRock        | Z97 Pro4                    | Desktop     | [0db03812df](https://linux-hardware.org/?probe=0db03812df) | Jul 29, 2022 |
| MSI           | Z370 GAMING M5              | Desktop     | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [eb92148078](https://linux-hardware.org/?probe=eb92148078) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | Notebook    | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [a2c2f04e29](https://linux-hardware.org/?probe=a2c2f04e29) | Jul 26, 2022 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [88b45b1956](https://linux-hardware.org/?probe=88b45b1956) | Jul 26, 2022 |
| ASUSTek       | X550ZA                      | Notebook    | [00126a3052](https://linux-hardware.org/?probe=00126a3052) | Jul 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7ffde486ac](https://linux-hardware.org/?probe=7ffde486ac) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f84af529bb](https://linux-hardware.org/?probe=f84af529bb) | Jul 24, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [73a12fbe59](https://linux-hardware.org/?probe=73a12fbe59) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [6f5d960fdc](https://linux-hardware.org/?probe=6f5d960fdc) | Jul 21, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [2543aa4d88](https://linux-hardware.org/?probe=2543aa4d88) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Dell          | 0DR845                      | Desktop     | [cf4bcf9de8](https://linux-hardware.org/?probe=cf4bcf9de8) | Jul 19, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48d9b9f502](https://linux-hardware.org/?probe=48d9b9f502) | Jul 18, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [70c17c522d](https://linux-hardware.org/?probe=70c17c522d) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5089cb3d81](https://linux-hardware.org/?probe=5089cb3d81) | Jul 17, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| NSX           | SB142G                      | Notebook    | [12329702b6](https://linux-hardware.org/?probe=12329702b6) | Jul 15, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [0c08648c4d](https://linux-hardware.org/?probe=0c08648c4d) | Jul 15, 2022 |
| ASRock        | A55M-VS                     | Desktop     | [844ac53526](https://linux-hardware.org/?probe=844ac53526) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | Desktop     | [3b8f491017](https://linux-hardware.org/?probe=3b8f491017) | Jul 14, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| Standard      | AHV                         | Notebook    | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Lenovo        | ThinkPad L470 20J5S01L00    | Notebook    | [401e13e2a6](https://linux-hardware.org/?probe=401e13e2a6) | Jul 12, 2022 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [46d0d5dccc](https://linux-hardware.org/?probe=46d0d5dccc) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [4f064a8dbc](https://linux-hardware.org/?probe=4f064a8dbc) | Jul 10, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3aee4d5b24](https://linux-hardware.org/?probe=3aee4d5b24) | Jul 09, 2022 |
| ECS           | H110M4-C23                  | Desktop     | [4a4af6d2e9](https://linux-hardware.org/?probe=4a4af6d2e9) | Jul 08, 2022 |
| Dell          | Latitude 3520               | Notebook    | [8439c98834](https://linux-hardware.org/?probe=8439c98834) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [5b90bd12c7](https://linux-hardware.org/?probe=5b90bd12c7) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [9c2136e4eb](https://linux-hardware.org/?probe=9c2136e4eb) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [244b168c32](https://linux-hardware.org/?probe=244b168c32) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [147320c75c](https://linux-hardware.org/?probe=147320c75c) | Jul 04, 2022 |
| NSX           | SB142G                      | Notebook    | [58158ab261](https://linux-hardware.org/?probe=58158ab261) | Jul 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [2a161e0d10](https://linux-hardware.org/?probe=2a161e0d10) | Jul 04, 2022 |
| Novatech      | C141WP-I5HS                 | Notebook    | [c487164618](https://linux-hardware.org/?probe=c487164618) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ad993981af](https://linux-hardware.org/?probe=ad993981af) | Jul 02, 2022 |
| Intel         | DX58SO AAE29331-703         | Desktop     | [3b22974574](https://linux-hardware.org/?probe=3b22974574) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8d9a85c7f3](https://linux-hardware.org/?probe=8d9a85c7f3) | Jun 30, 2022 |
| MSI           | CR620                       | Notebook    | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ddfd26738](https://linux-hardware.org/?probe=8ddfd26738) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | Notebook    | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Dell          | Latitude 3410               | Notebook    | [050678128c](https://linux-hardware.org/?probe=050678128c) | Jun 29, 2022 |
| Dell          | Latitude 3590               | Notebook    | [b5d4509068](https://linux-hardware.org/?probe=b5d4509068) | Jun 29, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [ff60a3cb61](https://linux-hardware.org/?probe=ff60a3cb61) | Jun 28, 2022 |
| HP            | ProBook 455 G4              | Notebook    | [f54297787f](https://linux-hardware.org/?probe=f54297787f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ec155fca3f](https://linux-hardware.org/?probe=ec155fca3f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [016ee6ec73](https://linux-hardware.org/?probe=016ee6ec73) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [af267c59cd](https://linux-hardware.org/?probe=af267c59cd) | Jun 28, 2022 |
| HP            | 8054                        | Desktop     | [82dd44f05f](https://linux-hardware.org/?probe=82dd44f05f) | Jun 26, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [90c166f77b](https://linux-hardware.org/?probe=90c166f77b) | Jun 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [21d2b9f0fb](https://linux-hardware.org/?probe=21d2b9f0fb) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 3646h                       | Desktop     | [d27deccf27](https://linux-hardware.org/?probe=d27deccf27) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| HP            | 255 G3                      | Notebook    | [def96ad707](https://linux-hardware.org/?probe=def96ad707) | Jun 21, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [465ffdd126](https://linux-hardware.org/?probe=465ffdd126) | Jun 21, 2022 |
| Dell          | Latitude 3590               | Notebook    | [fdfd4be1e2](https://linux-hardware.org/?probe=fdfd4be1e2) | Jun 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
| ASUSTek       | UX410UAK                    | Notebook    | [0d2e384ebf](https://linux-hardware.org/?probe=0d2e384ebf) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [4e35a154b5](https://linux-hardware.org/?probe=4e35a154b5) | Jun 18, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a56ff0b014](https://linux-hardware.org/?probe=a56ff0b014) | Jun 18, 2022 |
| ASRock        | G41M-GS                     | Desktop     | [9167934132](https://linux-hardware.org/?probe=9167934132) | Jun 18, 2022 |
| HP            | 0A60h                       | Desktop     | [cb42238223](https://linux-hardware.org/?probe=cb42238223) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9481bad179](https://linux-hardware.org/?probe=9481bad179) | Jun 17, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [41495c085a](https://linux-hardware.org/?probe=41495c085a) | Jun 16, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [4e33fa1a1d](https://linux-hardware.org/?probe=4e33fa1a1d) | Jun 15, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [71f9801165](https://linux-hardware.org/?probe=71f9801165) | Jun 15, 2022 |
| MSI           | 3664h                       | Desktop     | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [9916ed24a9](https://linux-hardware.org/?probe=9916ed24a9) | Jun 15, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [a3f29fd594](https://linux-hardware.org/?probe=a3f29fd594) | Jun 14, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [c8b26ae553](https://linux-hardware.org/?probe=c8b26ae553) | Jun 13, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [cae8181e7d](https://linux-hardware.org/?probe=cae8181e7d) | Jun 11, 2022 |
| Gadnic        | NOT00A1                     | Notebook    | [d63fbf4c2e](https://linux-hardware.org/?probe=d63fbf4c2e) | Jun 10, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [9ae6cc8594](https://linux-hardware.org/?probe=9ae6cc8594) | Jun 07, 2022 |
| ASRock        | H55M                        | Desktop     | [058eceb951](https://linux-hardware.org/?probe=058eceb951) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [ea589a3279](https://linux-hardware.org/?probe=ea589a3279) | Jun 07, 2022 |
| ASRock        | Z97M Anniversary            | Desktop     | [1855124dd3](https://linux-hardware.org/?probe=1855124dd3) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [09d190612b](https://linux-hardware.org/?probe=09d190612b) | Jun 06, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b3a7546aa9](https://linux-hardware.org/?probe=b3a7546aa9) | Jun 06, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [6c408a6fd7](https://linux-hardware.org/?probe=6c408a6fd7) | Jun 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [321300f927](https://linux-hardware.org/?probe=321300f927) | Jun 01, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [94a496851b](https://linux-hardware.org/?probe=94a496851b) | Jun 01, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [ec364402d8](https://linux-hardware.org/?probe=ec364402d8) | May 31, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Positivo      | ONE700                      | All in one  | [0675afbbfb](https://linux-hardware.org/?probe=0675afbbfb) | May 29, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [30be732591](https://linux-hardware.org/?probe=30be732591) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | Notebook    | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [8546d9cf10](https://linux-hardware.org/?probe=8546d9cf10) | May 27, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [bb0591d5c8](https://linux-hardware.org/?probe=bb0591d5c8) | May 26, 2022 |
| Juana Mans... | SF20GM7                     | Notebook    | [2078b0ab3f](https://linux-hardware.org/?probe=2078b0ab3f) | May 26, 2022 |
| American M... | K7S41GX                     | Desktop     | [b311270c22](https://linux-hardware.org/?probe=b311270c22) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | Desktop     | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [36e5918bc8](https://linux-hardware.org/?probe=36e5918bc8) | May 25, 2022 |
| Positivo      | AT510                       | Notebook    | [2845c5ebd6](https://linux-hardware.org/?probe=2845c5ebd6) | May 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [e59616f367](https://linux-hardware.org/?probe=e59616f367) | May 23, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [2cd1f7fd5e](https://linux-hardware.org/?probe=2cd1f7fd5e) | May 23, 2022 |
| Toshiba       | Unknown                     | Notebook    | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6d384d3502](https://linux-hardware.org/?probe=6d384d3502) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa4b76df10](https://linux-hardware.org/?probe=aa4b76df10) | May 21, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [830532746e](https://linux-hardware.org/?probe=830532746e) | May 20, 2022 |
| Dell          | Inspiron 3502               | Notebook    | [0d26fe46da](https://linux-hardware.org/?probe=0d26fe46da) | May 19, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [27289062cb](https://linux-hardware.org/?probe=27289062cb) | May 19, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | Desktop     | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [66a07f5e71](https://linux-hardware.org/?probe=66a07f5e71) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [3856a337bb](https://linux-hardware.org/?probe=3856a337bb) | May 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [2b8318661b](https://linux-hardware.org/?probe=2b8318661b) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [09c8ff393f](https://linux-hardware.org/?probe=09c8ff393f) | May 16, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [5af3adc742](https://linux-hardware.org/?probe=5af3adc742) | May 13, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [40d9831b29](https://linux-hardware.org/?probe=40d9831b29) | May 12, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [d3088d7665](https://linux-hardware.org/?probe=d3088d7665) | May 11, 2022 |
| Positivo      | AT300b                      | Notebook    | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [ba9835cb43](https://linux-hardware.org/?probe=ba9835cb43) | May 10, 2022 |
| Dell          | Latitude E6430              | Notebook    | [a188e200b3](https://linux-hardware.org/?probe=a188e200b3) | May 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Foxconn       | LIMA                        | Desktop     | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ed1e3083d6](https://linux-hardware.org/?probe=ed1e3083d6) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f84e562503](https://linux-hardware.org/?probe=f84e562503) | May 06, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [76e6cc98aa](https://linux-hardware.org/?probe=76e6cc98aa) | May 05, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3be0a0d66d](https://linux-hardware.org/?probe=3be0a0d66d) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [f3791f34b1](https://linux-hardware.org/?probe=f3791f34b1) | May 02, 2022 |
| Intel         | powered classmate PC        | Tablet      | [61790801c2](https://linux-hardware.org/?probe=61790801c2) | May 01, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [dc1b877e42](https://linux-hardware.org/?probe=dc1b877e42) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| NSX           | SB1402                      | Notebook    | [c9d79a4fe5](https://linux-hardware.org/?probe=c9d79a4fe5) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d3872db37e](https://linux-hardware.org/?probe=d3872db37e) | Apr 29, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [2cfdf9b28a](https://linux-hardware.org/?probe=2cfdf9b28a) | Apr 29, 2022 |
| Dell          | Latitude 5411               | Notebook    | [34c470e595](https://linux-hardware.org/?probe=34c470e595) | Apr 28, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [d7757bf097](https://linux-hardware.org/?probe=d7757bf097) | Apr 27, 2022 |
| NOBLEX        | N14WD21                     | Notebook    | [a8a7a4e1d5](https://linux-hardware.org/?probe=a8a7a4e1d5) | Apr 27, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [00728feb75](https://linux-hardware.org/?probe=00728feb75) | Apr 26, 2022 |
| Lenovo        | ThinkPad E470 20H1A01YAC    | Notebook    | [cd8726de3c](https://linux-hardware.org/?probe=cd8726de3c) | Apr 26, 2022 |
| Dell          | Studio 1558                 | Notebook    | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | Notebook                    | Notebook    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [fb612cbcd5](https://linux-hardware.org/?probe=fb612cbcd5) | Apr 24, 2022 |
| ASUSTek       | X556UB                      | Notebook    | [a9d2922649](https://linux-hardware.org/?probe=a9d2922649) | Apr 23, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [86f45617ad](https://linux-hardware.org/?probe=86f45617ad) | Apr 22, 2022 |
| ASUSTek       | K53E                        | Notebook    | [14e628cbba](https://linux-hardware.org/?probe=14e628cbba) | Apr 22, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [d66e41c50e](https://linux-hardware.org/?probe=d66e41c50e) | Apr 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [c021555957](https://linux-hardware.org/?probe=c021555957) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c00611352d](https://linux-hardware.org/?probe=c00611352d) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f28318e17b](https://linux-hardware.org/?probe=f28318e17b) | Apr 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2d0ac286da](https://linux-hardware.org/?probe=2d0ac286da) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| Dell          | Latitude 3520               | Notebook    | [8003f0258a](https://linux-hardware.org/?probe=8003f0258a) | Apr 14, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [a5a366f7e7](https://linux-hardware.org/?probe=a5a366f7e7) | Apr 13, 2022 |
| MSI           | H81M-E33                    | Desktop     | [460099f77f](https://linux-hardware.org/?probe=460099f77f) | Apr 13, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [9bcf0f1e4f](https://linux-hardware.org/?probe=9bcf0f1e4f) | Apr 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [52e0e2e934](https://linux-hardware.org/?probe=52e0e2e934) | Apr 12, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [d93ab23121](https://linux-hardware.org/?probe=d93ab23121) | Apr 10, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [de3e230ca3](https://linux-hardware.org/?probe=de3e230ca3) | Apr 10, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [cfa5407b7f](https://linux-hardware.org/?probe=cfa5407b7f) | Apr 10, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [48e5060f20](https://linux-hardware.org/?probe=48e5060f20) | Apr 10, 2022 |
| Unknown       | P4M800CE-8237               | Desktop     | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [a19db5a006](https://linux-hardware.org/?probe=a19db5a006) | Apr 05, 2022 |
| Advantec      | CX23500W                    | Notebook    | [a3152e0a0f](https://linux-hardware.org/?probe=a3152e0a0f) | Apr 02, 2022 |
| Advantec      | CX23500W                    | Notebook    | [feb5c20169](https://linux-hardware.org/?probe=feb5c20169) | Apr 02, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Exo           | Smart XQ5c                  | Notebook    | [5653a02bd3](https://linux-hardware.org/?probe=5653a02bd3) | Mar 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [14bd2cc137](https://linux-hardware.org/?probe=14bd2cc137) | Mar 31, 2022 |
| Dell          | Latitude 3410               | Notebook    | [fd37f4137d](https://linux-hardware.org/?probe=fd37f4137d) | Mar 30, 2022 |
| MSI           | MS-7388                     | Desktop     | [d5eabb8266](https://linux-hardware.org/?probe=d5eabb8266) | Mar 30, 2022 |
| Kanji         | Tamura MAX DUO              | Convertible | [1434c90e55](https://linux-hardware.org/?probe=1434c90e55) | Mar 30, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | Notebook    | [38700103d3](https://linux-hardware.org/?probe=38700103d3) | Mar 29, 2022 |
| Toshiba       | PORTEGE R935                | Notebook    | [b209a8e000](https://linux-hardware.org/?probe=b209a8e000) | Mar 28, 2022 |
| HP            | 81BB                        | All in one  | [cb07426c3e](https://linux-hardware.org/?probe=cb07426c3e) | Mar 28, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [dfc5a02c31](https://linux-hardware.org/?probe=dfc5a02c31) | Mar 28, 2022 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [f8c03d6697](https://linux-hardware.org/?probe=f8c03d6697) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [dd1e7b6c4d](https://linux-hardware.org/?probe=dd1e7b6c4d) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| HP            | 81BB                        | All in one  | [d3fec7d8f4](https://linux-hardware.org/?probe=d3fec7d8f4) | Mar 28, 2022 |
| Positivo      | Z100                        | Notebook    | [5577927db3](https://linux-hardware.org/?probe=5577927db3) | Mar 27, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [87a81b14f0](https://linux-hardware.org/?probe=87a81b14f0) | Mar 25, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b5ee1f293e](https://linux-hardware.org/?probe=b5ee1f293e) | Mar 25, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d809ca0f7a](https://linux-hardware.org/?probe=d809ca0f7a) | Mar 25, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [2e006b534b](https://linux-hardware.org/?probe=2e006b534b) | Mar 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [984b59ccb9](https://linux-hardware.org/?probe=984b59ccb9) | Mar 24, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [90ce7b8310](https://linux-hardware.org/?probe=90ce7b8310) | Mar 24, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [d3623fd756](https://linux-hardware.org/?probe=d3623fd756) | Mar 24, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [1057b723a8](https://linux-hardware.org/?probe=1057b723a8) | Mar 24, 2022 |
| BGH e-Nova    | Unknown                     | Notebook    | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| HP            | 8054                        | Desktop     | [38288fadf8](https://linux-hardware.org/?probe=38288fadf8) | Mar 21, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [c845b9c738](https://linux-hardware.org/?probe=c845b9c738) | Mar 21, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [0008f2b843](https://linux-hardware.org/?probe=0008f2b843) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [34d7600473](https://linux-hardware.org/?probe=34d7600473) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [bd7accdfd5](https://linux-hardware.org/?probe=bd7accdfd5) | Mar 20, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [116074683a](https://linux-hardware.org/?probe=116074683a) | Mar 19, 2022 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [2e70de8c8d](https://linux-hardware.org/?probe=2e70de8c8d) | Mar 19, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [74bdda89c3](https://linux-hardware.org/?probe=74bdda89c3) | Mar 18, 2022 |
| NSX           | SB142G                      | Notebook    | [0a13591ca3](https://linux-hardware.org/?probe=0a13591ca3) | Mar 18, 2022 |
| ASUSTek       | X505BP                      | Notebook    | [3dc5b19d13](https://linux-hardware.org/?probe=3dc5b19d13) | Mar 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b2ec039a2e](https://linux-hardware.org/?probe=b2ec039a2e) | Mar 17, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [39b60a2ef4](https://linux-hardware.org/?probe=39b60a2ef4) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [25c0bbffe2](https://linux-hardware.org/?probe=25c0bbffe2) | Mar 15, 2022 |
| Lenovo        | Edge 15 80H1                | Notebook    | [bd2b981053](https://linux-hardware.org/?probe=bd2b981053) | Mar 14, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7e32829960](https://linux-hardware.org/?probe=7e32829960) | Mar 13, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [c31b5d363f](https://linux-hardware.org/?probe=c31b5d363f) | Mar 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [5aa4d54781](https://linux-hardware.org/?probe=5aa4d54781) | Mar 09, 2022 |
| NOBLEX        | N14WD21                     | Notebook    | [c166ec8175](https://linux-hardware.org/?probe=c166ec8175) | Mar 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7708a6ffb9](https://linux-hardware.org/?probe=7708a6ffb9) | Mar 07, 2022 |
| ASRock        | G41M-S3                     | Desktop     | [a5d8ab9493](https://linux-hardware.org/?probe=a5d8ab9493) | Mar 07, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | Notebook    | [3a01549416](https://linux-hardware.org/?probe=3a01549416) | Mar 06, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | Notebook    | [48d2d5d234](https://linux-hardware.org/?probe=48d2d5d234) | Mar 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [52a16c13b1](https://linux-hardware.org/?probe=52a16c13b1) | Mar 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [eca1413f3f](https://linux-hardware.org/?probe=eca1413f3f) | Mar 04, 2022 |
| Nvidia        | Tegra                       | Soc         | [904f2d4f21](https://linux-hardware.org/?probe=904f2d4f21) | Feb 28, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e79a48e141](https://linux-hardware.org/?probe=e79a48e141) | Feb 27, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [65eae3fe4c](https://linux-hardware.org/?probe=65eae3fe4c) | Feb 25, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [bf565614ca](https://linux-hardware.org/?probe=bf565614ca) | Feb 24, 2022 |
| ASRock        | G31M-S                      | Desktop     | [1ecf0fe3af](https://linux-hardware.org/?probe=1ecf0fe3af) | Feb 24, 2022 |
| Lenovo        | ChiefRiver                  | All in one  | [019a150df4](https://linux-hardware.org/?probe=019a150df4) | Feb 23, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | Notebook    | [6d10cb57e1](https://linux-hardware.org/?probe=6d10cb57e1) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [747899db53](https://linux-hardware.org/?probe=747899db53) | Feb 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [2a57fc9391](https://linux-hardware.org/?probe=2a57fc9391) | Feb 20, 2022 |
| ASUSTek       | X55C                        | Notebook    | [ae05784a4a](https://linux-hardware.org/?probe=ae05784a4a) | Feb 19, 2022 |
| Samsung       | SQ35S                       | Notebook    | [7f4f9ad483](https://linux-hardware.org/?probe=7f4f9ad483) | Feb 18, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [d9f8a4991e](https://linux-hardware.org/?probe=d9f8a4991e) | Feb 18, 2022 |
| Advantec      | C15B                        | Desktop     | [708b68ac89](https://linux-hardware.org/?probe=708b68ac89) | Feb 17, 2022 |
| ASUSTek       | PRIME Z270M-PLUS            | Desktop     | [0faabbb741](https://linux-hardware.org/?probe=0faabbb741) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| ASUSTek       | X540UA                      | Notebook    | [681b4aca6f](https://linux-hardware.org/?probe=681b4aca6f) | Feb 16, 2022 |
| Radio Vict... | B34 SLIM                    | Notebook    | [8a100feae7](https://linux-hardware.org/?probe=8a100feae7) | Feb 16, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [0937e1da6a](https://linux-hardware.org/?probe=0937e1da6a) | Feb 14, 2022 |
| Dell          | 0RF705                      | Desktop     | [4369e75c27](https://linux-hardware.org/?probe=4369e75c27) | Feb 14, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [581ebd9976](https://linux-hardware.org/?probe=581ebd9976) | Feb 13, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [fc4efd1eff](https://linux-hardware.org/?probe=fc4efd1eff) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| ASRock        | H55M                        | Desktop     | [85a293bc45](https://linux-hardware.org/?probe=85a293bc45) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [196bd41500](https://linux-hardware.org/?probe=196bd41500) | Feb 12, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [e189ec36c5](https://linux-hardware.org/?probe=e189ec36c5) | Feb 12, 2022 |
| MSI           | GP72 6QE                    | Notebook    | [d4a2d3bb85](https://linux-hardware.org/?probe=d4a2d3bb85) | Feb 12, 2022 |
| MSI           | GP72 6QE                    | Notebook    | [9409e22a95](https://linux-hardware.org/?probe=9409e22a95) | Feb 12, 2022 |
| ASRock        | G31M-S                      | Desktop     | [0e52738a23](https://linux-hardware.org/?probe=0e52738a23) | Feb 11, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [b04de36c04](https://linux-hardware.org/?probe=b04de36c04) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [0f65488b54](https://linux-hardware.org/?probe=0f65488b54) | Feb 11, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [da554d50b7](https://linux-hardware.org/?probe=da554d50b7) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [fc6c97721c](https://linux-hardware.org/?probe=fc6c97721c) | Feb 09, 2022 |
| Sony          | VJFE52A0711H                | Notebook    | [0a29c49c46](https://linux-hardware.org/?probe=0a29c49c46) | Feb 09, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [5beef7a5b1](https://linux-hardware.org/?probe=5beef7a5b1) | Feb 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [c71db9d118](https://linux-hardware.org/?probe=c71db9d118) | Feb 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [61aae88463](https://linux-hardware.org/?probe=61aae88463) | Feb 08, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [c4cba809c4](https://linux-hardware.org/?probe=c4cba809c4) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [dbfba11836](https://linux-hardware.org/?probe=dbfba11836) | Feb 08, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [b6df9d3243](https://linux-hardware.org/?probe=b6df9d3243) | Feb 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [c6783b6b8b](https://linux-hardware.org/?probe=c6783b6b8b) | Feb 07, 2022 |
| HP            | 0A60h                       | Desktop     | [8c9b5ec56f](https://linux-hardware.org/?probe=8c9b5ec56f) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | Desktop     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c1fe9c81a0](https://linux-hardware.org/?probe=c1fe9c81a0) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f92b5e4b44](https://linux-hardware.org/?probe=f92b5e4b44) | Feb 06, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [0e2c677ddc](https://linux-hardware.org/?probe=0e2c677ddc) | Feb 03, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [fa4a95f3a5](https://linux-hardware.org/?probe=fa4a95f3a5) | Feb 03, 2022 |
| ASUSTek       | Maximus V GENE              | Desktop     | [749946734b](https://linux-hardware.org/?probe=749946734b) | Feb 03, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [23987146db](https://linux-hardware.org/?probe=23987146db) | Feb 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [a5298ee805](https://linux-hardware.org/?probe=a5298ee805) | Feb 02, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c7af52d518](https://linux-hardware.org/?probe=c7af52d518) | Feb 02, 2022 |
| Gigabyte      | A320M-HD2-CF                | Desktop     | [6ad345c1a5](https://linux-hardware.org/?probe=6ad345c1a5) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Dell          | 0NX183 A01                  | Desktop     | [54e546f9ae](https://linux-hardware.org/?probe=54e546f9ae) | Jan 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [690eba21e0](https://linux-hardware.org/?probe=690eba21e0) | Jan 30, 2022 |
| Unknown       | P4M800CE-8237               | Desktop     | [ff8ade4a5a](https://linux-hardware.org/?probe=ff8ade4a5a) | Jan 28, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [350f00e69f](https://linux-hardware.org/?probe=350f00e69f) | Jan 27, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [343ab23f97](https://linux-hardware.org/?probe=343ab23f97) | Jan 27, 2022 |
| Lenovo        | G40-80 80E4                 | Notebook    | [4c27ace709](https://linux-hardware.org/?probe=4c27ace709) | Jan 26, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [62e942ea94](https://linux-hardware.org/?probe=62e942ea94) | Jan 26, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [f8afc9746e](https://linux-hardware.org/?probe=f8afc9746e) | Jan 24, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [72a04dc661](https://linux-hardware.org/?probe=72a04dc661) | Jan 22, 2022 |
| Standard      | MB50II                      | Notebook    | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [0f956f27ad](https://linux-hardware.org/?probe=0f956f27ad) | Jan 20, 2022 |
| Gadnic        | NOT00A1                     | Notebook    | [f1c6b56aa2](https://linux-hardware.org/?probe=f1c6b56aa2) | Jan 18, 2022 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [a6302c118b](https://linux-hardware.org/?probe=a6302c118b) | Jan 17, 2022 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [8a0c194baa](https://linux-hardware.org/?probe=8a0c194baa) | Jan 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [0e5d4dfabf](https://linux-hardware.org/?probe=0e5d4dfabf) | Jan 13, 2022 |
| MSI           | MS-7309                     | Desktop     | [b980404ce1](https://linux-hardware.org/?probe=b980404ce1) | Jan 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [b5437027b1](https://linux-hardware.org/?probe=b5437027b1) | Jan 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2b44f3e733](https://linux-hardware.org/?probe=2b44f3e733) | Jan 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [137736d936](https://linux-hardware.org/?probe=137736d936) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [7d5ceb70bb](https://linux-hardware.org/?probe=7d5ceb70bb) | Jan 10, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [6b1eb1745e](https://linux-hardware.org/?probe=6b1eb1745e) | Jan 10, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [50adc5f773](https://linux-hardware.org/?probe=50adc5f773) | Jan 08, 2022 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [1f828632ed](https://linux-hardware.org/?probe=1f828632ed) | Jan 07, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [35c962a07f](https://linux-hardware.org/?probe=35c962a07f) | Jan 02, 2022 |
| VS Company    | MCP61M                      | Desktop     | [8009a6fbdf](https://linux-hardware.org/?probe=8009a6fbdf) | Jan 02, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b6b0572310](https://linux-hardware.org/?probe=b6b0572310) | Jan 02, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [dfa1412d12](https://linux-hardware.org/?probe=dfa1412d12) | Jan 01, 2022 |
| HP            | 0A60h                       | Desktop     | [2812050060](https://linux-hardware.org/?probe=2812050060) | Jan 01, 2022 |
| Dell          | Latitude E5540              | Notebook    | [1a112d75bc](https://linux-hardware.org/?probe=1a112d75bc) | Jan 01, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [4754d83d04](https://linux-hardware.org/?probe=4754d83d04) | Jan 01, 2022 |
| Exo           | HR14                        | Notebook    | [3a16049e36](https://linux-hardware.org/?probe=3a16049e36) | Dec 31, 2021 |
| Exo           | HR14                        | Notebook    | [8c3bf46eb1](https://linux-hardware.org/?probe=8c3bf46eb1) | Dec 31, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [c05333a0bc](https://linux-hardware.org/?probe=c05333a0bc) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | G40-80 80E4                 | Notebook    | [993fe7cef6](https://linux-hardware.org/?probe=993fe7cef6) | Dec 30, 2021 |
| HP            | 15                          | Notebook    | [e0d79905e2](https://linux-hardware.org/?probe=e0d79905e2) | Dec 29, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [d860437585](https://linux-hardware.org/?probe=d860437585) | Dec 28, 2021 |
| Intel         | DG965WH AAD41692-305        | Desktop     | [970dba93b8](https://linux-hardware.org/?probe=970dba93b8) | Dec 28, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [8c9f72d757](https://linux-hardware.org/?probe=8c9f72d757) | Dec 27, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d02d1bb775](https://linux-hardware.org/?probe=d02d1bb775) | Dec 27, 2021 |
| System76      | Lemur Pro                   | Notebook    | [6dbfd95ccb](https://linux-hardware.org/?probe=6dbfd95ccb) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d2e019564f](https://linux-hardware.org/?probe=d2e019564f) | Dec 26, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| Dell          | Inspiron 7791 2n1           | Convertible | [b5887ff3fd](https://linux-hardware.org/?probe=b5887ff3fd) | Dec 25, 2021 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [da08b0d873](https://linux-hardware.org/?probe=da08b0d873) | Dec 22, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [64492ac63b](https://linux-hardware.org/?probe=64492ac63b) | Dec 22, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [8df64a7f80](https://linux-hardware.org/?probe=8df64a7f80) | Dec 21, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [ce7e7de4b4](https://linux-hardware.org/?probe=ce7e7de4b4) | Dec 20, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [aaab97a820](https://linux-hardware.org/?probe=aaab97a820) | Dec 19, 2021 |
| Dell          | 0RF705                      | Desktop     | [b28693bf2b](https://linux-hardware.org/?probe=b28693bf2b) | Dec 19, 2021 |
| System76      | Lemur Pro                   | Notebook    | [aebe0acb39](https://linux-hardware.org/?probe=aebe0acb39) | Dec 18, 2021 |
| Compaq        | Presario 21                 | Notebook    | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [915303d28d](https://linux-hardware.org/?probe=915303d28d) | Dec 16, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [15d1b4bba5](https://linux-hardware.org/?probe=15d1b4bba5) | Dec 16, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [99dbb19723](https://linux-hardware.org/?probe=99dbb19723) | Dec 15, 2021 |
| HONOR         | HLYL-WXX9                   | Notebook    | [0b6a9394b4](https://linux-hardware.org/?probe=0b6a9394b4) | Dec 15, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [bc401cc9a6](https://linux-hardware.org/?probe=bc401cc9a6) | Dec 14, 2021 |
| Lenovo        | ThinkPad X230 23252CG       | Notebook    | [e2ed9e27c3](https://linux-hardware.org/?probe=e2ed9e27c3) | Dec 14, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [e66c15a464](https://linux-hardware.org/?probe=e66c15a464) | Dec 13, 2021 |
| Gigabyte      | H510M H                     | Desktop     | [53588115a6](https://linux-hardware.org/?probe=53588115a6) | Dec 13, 2021 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [903dfc6f62](https://linux-hardware.org/?probe=903dfc6f62) | Dec 13, 2021 |
| ASUSTek       | X541UAK                     | Notebook    | [9c83d97134](https://linux-hardware.org/?probe=9c83d97134) | Dec 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [6df961216e](https://linux-hardware.org/?probe=6df961216e) | Dec 12, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [60cdd8ce45](https://linux-hardware.org/?probe=60cdd8ce45) | Dec 11, 2021 |
| Quanta        | 2AC5                        | Desktop     | [0e0fcca430](https://linux-hardware.org/?probe=0e0fcca430) | Dec 10, 2021 |
| Quanta        | 2AC5                        | Desktop     | [d0c9fba2a4](https://linux-hardware.org/?probe=d0c9fba2a4) | Dec 10, 2021 |
| Toshiba       | TE5                         | Notebook    | [fb39721f00](https://linux-hardware.org/?probe=fb39721f00) | Dec 10, 2021 |
| ASRock        | QC6000M                     | Desktop     | [3475206cb1](https://linux-hardware.org/?probe=3475206cb1) | Dec 10, 2021 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [44fb1a2d77](https://linux-hardware.org/?probe=44fb1a2d77) | Dec 09, 2021 |
| Gigabyte      | H410M H                     | Desktop     | [a1b80c28f2](https://linux-hardware.org/?probe=a1b80c28f2) | Dec 09, 2021 |
| System76      | Lemur Pro                   | Notebook    | [6e54a15cf2](https://linux-hardware.org/?probe=6e54a15cf2) | Dec 08, 2021 |
| Exo           | C14C                        | Notebook    | [2e0765b245](https://linux-hardware.org/?probe=2e0765b245) | Dec 08, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [b041919f38](https://linux-hardware.org/?probe=b041919f38) | Dec 08, 2021 |
| Exo           | C14C                        | Notebook    | [1d4221ab9e](https://linux-hardware.org/?probe=1d4221ab9e) | Dec 06, 2021 |
| Positivo      | AT300b                      | Notebook    | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [adf5a1b645](https://linux-hardware.org/?probe=adf5a1b645) | Dec 04, 2021 |
| Acer          | Aspire 5251                 | Notebook    | [30ef0eefda](https://linux-hardware.org/?probe=30ef0eefda) | Dec 04, 2021 |
| Intel         | powered classmate PC        | Tablet      | [09bfb979b0](https://linux-hardware.org/?probe=09bfb979b0) | Dec 03, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [4c79974ae8](https://linux-hardware.org/?probe=4c79974ae8) | Dec 03, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3f21e28b42](https://linux-hardware.org/?probe=3f21e28b42) | Dec 03, 2021 |
| Biostar       | NF61V-M2                    | Desktop     | [0d21d633c9](https://linux-hardware.org/?probe=0d21d633c9) | Dec 02, 2021 |
| BANGHO        | CLOUD                       | Notebook    | [214c91e455](https://linux-hardware.org/?probe=214c91e455) | Dec 01, 2021 |
| BANGHO        | MOV                         | Notebook    | [3e5867cd6a](https://linux-hardware.org/?probe=3e5867cd6a) | Dec 01, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [30820af902](https://linux-hardware.org/?probe=30820af902) | Nov 29, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [4215fcadd9](https://linux-hardware.org/?probe=4215fcadd9) | Nov 25, 2021 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [dbf2659c98](https://linux-hardware.org/?probe=dbf2659c98) | Nov 23, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [6e2d7fbaed](https://linux-hardware.org/?probe=6e2d7fbaed) | Nov 22, 2021 |
| BANGHO        | Suma 1025                   | Tablet      | [4168edf1bf](https://linux-hardware.org/?probe=4168edf1bf) | Nov 22, 2021 |
| Exo           | Smart Serie M               | Notebook    | [cbf705cf51](https://linux-hardware.org/?probe=cbf705cf51) | Nov 22, 2021 |
| ASUSTek       | G551JW                      | Notebook    | [5f018a92ee](https://linux-hardware.org/?probe=5f018a92ee) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | Desktop     | [be9ba487cd](https://linux-hardware.org/?probe=be9ba487cd) | Nov 21, 2021 |
| Intel         | DP35DP AAD81073-205         | Desktop     | [d8c73031f1](https://linux-hardware.org/?probe=d8c73031f1) | Nov 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [8eeef70a27](https://linux-hardware.org/?probe=8eeef70a27) | Nov 19, 2021 |
| ASRock        | B450M Pro4-F R2.0           | Desktop     | [8dc5c4b2c1](https://linux-hardware.org/?probe=8dc5c4b2c1) | Nov 19, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5502066af1](https://linux-hardware.org/?probe=5502066af1) | Nov 18, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a8e3d44c9e](https://linux-hardware.org/?probe=a8e3d44c9e) | Nov 15, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [58809fa055](https://linux-hardware.org/?probe=58809fa055) | Nov 14, 2021 |
| ASRock        | 880GMH/USB3                 | Desktop     | [25aeb2bbf9](https://linux-hardware.org/?probe=25aeb2bbf9) | Nov 14, 2021 |
| ASRock        | 880GMH/USB3                 | Desktop     | [05ce0a8880](https://linux-hardware.org/?probe=05ce0a8880) | Nov 14, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| Acer          | Aspire ES1-572              | Notebook    | [871bd7121a](https://linux-hardware.org/?probe=871bd7121a) | Nov 11, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [c282ff2172](https://linux-hardware.org/?probe=c282ff2172) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [eb66540889](https://linux-hardware.org/?probe=eb66540889) | Nov 10, 2021 |
| Kanji         | Tamura MAX DUO              | Convertible | [0cff4ea4dd](https://linux-hardware.org/?probe=0cff4ea4dd) | Nov 09, 2021 |
| ASRock        | A55M-VS                     | Desktop     | [3e40db1efb](https://linux-hardware.org/?probe=3e40db1efb) | Nov 09, 2021 |
| Lenovo        | 14w 81MQ00AHAR              | Notebook    | [17785cda04](https://linux-hardware.org/?probe=17785cda04) | Nov 09, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [77b62d6178](https://linux-hardware.org/?probe=77b62d6178) | Nov 09, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [fbc9822ad6](https://linux-hardware.org/?probe=fbc9822ad6) | Nov 09, 2021 |
| MSI           | 990XA-GD55                  | Desktop     | [461ac78561](https://linux-hardware.org/?probe=461ac78561) | Nov 08, 2021 |
| MSI           | MS-7369                     | Desktop     | [670cc450d8](https://linux-hardware.org/?probe=670cc450d8) | Nov 08, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c4fd612984](https://linux-hardware.org/?probe=c4fd612984) | Nov 07, 2021 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e21897758d](https://linux-hardware.org/?probe=e21897758d) | Nov 07, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [384fb31833](https://linux-hardware.org/?probe=384fb31833) | Nov 06, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7b21a0bc71](https://linux-hardware.org/?probe=7b21a0bc71) | Nov 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [03961f687b](https://linux-hardware.org/?probe=03961f687b) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | Notebook    | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| BANGHO        | MOV                         | Notebook    | [9c2b56129e](https://linux-hardware.org/?probe=9c2b56129e) | Nov 06, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [1a749d9336](https://linux-hardware.org/?probe=1a749d9336) | Nov 05, 2021 |
| Lenovo        | G40-80 80E4                 | Notebook    | [57b9418a9c](https://linux-hardware.org/?probe=57b9418a9c) | Nov 05, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [1f65cc3bef](https://linux-hardware.org/?probe=1f65cc3bef) | Nov 05, 2021 |
| HP            | 15                          | Notebook    | [0719e191d4](https://linux-hardware.org/?probe=0719e191d4) | Nov 04, 2021 |
| HP            | 630                         | Notebook    | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [f9fbde199a](https://linux-hardware.org/?probe=f9fbde199a) | Nov 02, 2021 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [a84ed9f4fc](https://linux-hardware.org/?probe=a84ed9f4fc) | Nov 02, 2021 |
| Lenovo        | G40-80 80E4                 | Notebook    | [f89ddc0ebd](https://linux-hardware.org/?probe=f89ddc0ebd) | Nov 02, 2021 |
| Intel         | HURONRIVER                  | Notebook    | [5ded89b4a5](https://linux-hardware.org/?probe=5ded89b4a5) | Nov 02, 2021 |
| MSI           | 760GM-P34                   | Desktop     | [1161af8368](https://linux-hardware.org/?probe=1161af8368) | Oct 31, 2021 |
| ASUSTek       | Q524UQK                     | Convertible | [84ceeeacf1](https://linux-hardware.org/?probe=84ceeeacf1) | Oct 27, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | Notebook    | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| HP            | Pavilion dv4                | Notebook    | [f0ae431e2c](https://linux-hardware.org/?probe=f0ae431e2c) | Oct 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c739ed76e3](https://linux-hardware.org/?probe=c739ed76e3) | Oct 26, 2021 |
| Unknown       | K8M800-8237                 | Desktop     | [91468b399e](https://linux-hardware.org/?probe=91468b399e) | Oct 25, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [7877fc09ba](https://linux-hardware.org/?probe=7877fc09ba) | Oct 22, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7a2305704](https://linux-hardware.org/?probe=c7a2305704) | Oct 21, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [8d1ec3a3b6](https://linux-hardware.org/?probe=8d1ec3a3b6) | Oct 21, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [3115478a9b](https://linux-hardware.org/?probe=3115478a9b) | Oct 20, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [f092832b93](https://linux-hardware.org/?probe=f092832b93) | Oct 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [0290c2ca6d](https://linux-hardware.org/?probe=0290c2ca6d) | Oct 19, 2021 |
| Toshiba       | Satellite A505              | Notebook    | [a955d2e293](https://linux-hardware.org/?probe=a955d2e293) | Oct 18, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f31078afd8](https://linux-hardware.org/?probe=f31078afd8) | Oct 18, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [34fc60e37e](https://linux-hardware.org/?probe=34fc60e37e) | Oct 16, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | Notebook    | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| HP            | Mini 110-3000               | Notebook    | [ee2ce4e3b9](https://linux-hardware.org/?probe=ee2ce4e3b9) | Oct 14, 2021 |
| NOBLEX        | E11IS2                      | Notebook    | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a0c897a604](https://linux-hardware.org/?probe=a0c897a604) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [000ac750e0](https://linux-hardware.org/?probe=000ac750e0) | Oct 13, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [a65d72b574](https://linux-hardware.org/?probe=a65d72b574) | Oct 13, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| ASRock        | 960GC-GS FX                 | Desktop     | [437c7ad805](https://linux-hardware.org/?probe=437c7ad805) | Oct 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| MSI           | B150M PRO-VDH               | Desktop     | [da329b10c9](https://linux-hardware.org/?probe=da329b10c9) | Oct 08, 2021 |
| MSI           | B150M PRO-VDH               | Desktop     | [13f8e82e6a](https://linux-hardware.org/?probe=13f8e82e6a) | Oct 08, 2021 |
| MSI           | B550M PRO-VDH               | Desktop     | [b806a146d2](https://linux-hardware.org/?probe=b806a146d2) | Oct 08, 2021 |
| Dell          | Latitude 5480               | Notebook    | [3ed90a1781](https://linux-hardware.org/?probe=3ed90a1781) | Oct 07, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [8163e064d3](https://linux-hardware.org/?probe=8163e064d3) | Oct 07, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [1939167a1c](https://linux-hardware.org/?probe=1939167a1c) | Oct 06, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [c111f21064](https://linux-hardware.org/?probe=c111f21064) | Oct 05, 2021 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [4d45d7e8b5](https://linux-hardware.org/?probe=4d45d7e8b5) | Oct 05, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| Dell          | G3 3779                     | Notebook    | [0257eadb71](https://linux-hardware.org/?probe=0257eadb71) | Oct 04, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bea39ba8be](https://linux-hardware.org/?probe=bea39ba8be) | Oct 03, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [00c624b592](https://linux-hardware.org/?probe=00c624b592) | Oct 03, 2021 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [09b4e39973](https://linux-hardware.org/?probe=09b4e39973) | Oct 03, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [f1b660b91c](https://linux-hardware.org/?probe=f1b660b91c) | Oct 02, 2021 |
| Acer          | Aspire E5-432               | Notebook    | [2d6ea0cb46](https://linux-hardware.org/?probe=2d6ea0cb46) | Oct 02, 2021 |
| Lenovo        | ThinkPad E495 20NES0RR00    | Notebook    | [016f532a15](https://linux-hardware.org/?probe=016f532a15) | Oct 02, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [cd2412d37e](https://linux-hardware.org/?probe=cd2412d37e) | Oct 01, 2021 |
| Intel         | D425KT AAE93083-401         | Mini pc     | [9dc27fc5be](https://linux-hardware.org/?probe=9dc27fc5be) | Oct 01, 2021 |
| ASUSTek       | K53E                        | Notebook    | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| Exo           | SmartPro Q6                 | Notebook    | [5986a21d65](https://linux-hardware.org/?probe=5986a21d65) | Sep 30, 2021 |
| Lenovo        | ThinkPad T470 20HES57W00    | Notebook    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ff712cfd11](https://linux-hardware.org/?probe=ff712cfd11) | Sep 28, 2021 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [781b63209d](https://linux-hardware.org/?probe=781b63209d) | Sep 28, 2021 |
| Acer          | Aspire 2930Z                | Notebook    | [95cf81718f](https://linux-hardware.org/?probe=95cf81718f) | Sep 28, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [f936e50be4](https://linux-hardware.org/?probe=f936e50be4) | Sep 26, 2021 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [c499580572](https://linux-hardware.org/?probe=c499580572) | Sep 26, 2021 |
| Biostar       | P4M89-M7B Ver:1.0           | Desktop     | [e540393e87](https://linux-hardware.org/?probe=e540393e87) | Sep 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [445b864b6e](https://linux-hardware.org/?probe=445b864b6e) | Sep 25, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [c4a94c7628](https://linux-hardware.org/?probe=c4a94c7628) | Sep 23, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f93c2362ff](https://linux-hardware.org/?probe=f93c2362ff) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Acer          | Aspire 2930Z                | Notebook    | [837506804e](https://linux-hardware.org/?probe=837506804e) | Sep 20, 2021 |
| Acer          | Aspire 2930Z                | Notebook    | [720324554e](https://linux-hardware.org/?probe=720324554e) | Sep 20, 2021 |
| Acer          | Aspire 2930Z                | Notebook    | [85e19ff9ba](https://linux-hardware.org/?probe=85e19ff9ba) | Sep 20, 2021 |
| MSI           | MS-7253                     | Desktop     | [4be11be3f6](https://linux-hardware.org/?probe=4be11be3f6) | Sep 19, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [8daebb1450](https://linux-hardware.org/?probe=8daebb1450) | Sep 19, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Unknown       | P4M800CE-8237               | Desktop     | [f7a252e496](https://linux-hardware.org/?probe=f7a252e496) | Sep 18, 2021 |
| Unknown       | P4M800CE-8237               | Desktop     | [13e024d15e](https://linux-hardware.org/?probe=13e024d15e) | Sep 18, 2021 |
| HP            | 0A64h                       | Desktop     | [edcb77e9a1](https://linux-hardware.org/?probe=edcb77e9a1) | Sep 15, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | Notebook    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| Lenovo        | G480 20150                  | Notebook    | [d7d8be3a08](https://linux-hardware.org/?probe=d7d8be3a08) | Sep 15, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | Notebook    | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | Notebook    | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [6d95dbecb4](https://linux-hardware.org/?probe=6d95dbecb4) | Sep 13, 2021 |
| Positivo      | SW6H                        | Notebook    | [2653f4ff4b](https://linux-hardware.org/?probe=2653f4ff4b) | Sep 12, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [1fc1622a64](https://linux-hardware.org/?probe=1fc1622a64) | Sep 12, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [c9a8c369e7](https://linux-hardware.org/?probe=c9a8c369e7) | Sep 10, 2021 |
| IBM           | ThinkPad T41 23737JY        | Notebook    | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [361beeda3d](https://linux-hardware.org/?probe=361beeda3d) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | Notebook    | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Intel         | Pine Trail - M Revision ... | Notebook    | [147f6959ad](https://linux-hardware.org/?probe=147f6959ad) | Sep 08, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [014c8bb745](https://linux-hardware.org/?probe=014c8bb745) | Sep 07, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2f680da4b8](https://linux-hardware.org/?probe=2f680da4b8) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [409ed1f8a4](https://linux-hardware.org/?probe=409ed1f8a4) | Sep 06, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [e7b06b1276](https://linux-hardware.org/?probe=e7b06b1276) | Sep 06, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [df2dd7daca](https://linux-hardware.org/?probe=df2dd7daca) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [d1773b3e3d](https://linux-hardware.org/?probe=d1773b3e3d) | Sep 06, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d2cc7f4ca](https://linux-hardware.org/?probe=5d2cc7f4ca) | Sep 06, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [b1147fa740](https://linux-hardware.org/?probe=b1147fa740) | Sep 05, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [e33cd98e47](https://linux-hardware.org/?probe=e33cd98e47) | Sep 05, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [7122e4bd16](https://linux-hardware.org/?probe=7122e4bd16) | Sep 04, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [16ef0eab27](https://linux-hardware.org/?probe=16ef0eab27) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 20RD002RUS     | Notebook    | [2140460960](https://linux-hardware.org/?probe=2140460960) | Sep 03, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e9da9320c](https://linux-hardware.org/?probe=0e9da9320c) | Sep 03, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [99767a5ca2](https://linux-hardware.org/?probe=99767a5ca2) | Sep 02, 2021 |
| Lenovo        | G470 20078                  | Notebook    | [b480871bf8](https://linux-hardware.org/?probe=b480871bf8) | Sep 02, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [caa58a3463](https://linux-hardware.org/?probe=caa58a3463) | Sep 01, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [e8b8cb1cf7](https://linux-hardware.org/?probe=e8b8cb1cf7) | Sep 01, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [038868057d](https://linux-hardware.org/?probe=038868057d) | Aug 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [d2ce2247c6](https://linux-hardware.org/?probe=d2ce2247c6) | Aug 30, 2021 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [91f168dd88](https://linux-hardware.org/?probe=91f168dd88) | Aug 29, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [78eb1f5b7f](https://linux-hardware.org/?probe=78eb1f5b7f) | Aug 29, 2021 |
| BANGHO        | MAX G0101                   | Notebook    | [88ac236a11](https://linux-hardware.org/?probe=88ac236a11) | Aug 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6545        | Notebook    | [f597bdfe1a](https://linux-hardware.org/?probe=f597bdfe1a) | Aug 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [97afdfd346](https://linux-hardware.org/?probe=97afdfd346) | Aug 29, 2021 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [f6b7e268fe](https://linux-hardware.org/?probe=f6b7e268fe) | Aug 28, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [7f53bb7787](https://linux-hardware.org/?probe=7f53bb7787) | Aug 28, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [50477e1758](https://linux-hardware.org/?probe=50477e1758) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [d51c8093ec](https://linux-hardware.org/?probe=d51c8093ec) | Aug 27, 2021 |
| Gigabyte      | A520M H                     | Desktop     | [4b126be26e](https://linux-hardware.org/?probe=4b126be26e) | Aug 26, 2021 |
| BANGHO        | MOV                         | Notebook    | [9bacff92e1](https://linux-hardware.org/?probe=9bacff92e1) | Aug 25, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [2882cf9963](https://linux-hardware.org/?probe=2882cf9963) | Aug 25, 2021 |
| ASUSTek       | AM1M-A                      | Desktop     | [17f2638893](https://linux-hardware.org/?probe=17f2638893) | Aug 24, 2021 |
| Positivo      | Unknown                     | Notebook    | [28bac734c5](https://linux-hardware.org/?probe=28bac734c5) | Aug 24, 2021 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [f3f58765e6](https://linux-hardware.org/?probe=f3f58765e6) | Aug 24, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [c10c8ceffe](https://linux-hardware.org/?probe=c10c8ceffe) | Aug 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [be114a1393](https://linux-hardware.org/?probe=be114a1393) | Aug 23, 2021 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [4118ea79d0](https://linux-hardware.org/?probe=4118ea79d0) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [4a647bfabc](https://linux-hardware.org/?probe=4a647bfabc) | Aug 23, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [8f16ee8e8c](https://linux-hardware.org/?probe=8f16ee8e8c) | Aug 21, 2021 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7f83e1b3c8](https://linux-hardware.org/?probe=7f83e1b3c8) | Aug 21, 2021 |
| Dell          | Latitude 7400               | Notebook    | [61fd9efe24](https://linux-hardware.org/?probe=61fd9efe24) | Aug 21, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [768bf35df4](https://linux-hardware.org/?probe=768bf35df4) | Aug 20, 2021 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [6d7fb6d592](https://linux-hardware.org/?probe=6d7fb6d592) | Aug 19, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [c83e0428a8](https://linux-hardware.org/?probe=c83e0428a8) | Aug 17, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [6e32aa4ffd](https://linux-hardware.org/?probe=6e32aa4ffd) | Aug 17, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [54369d3959](https://linux-hardware.org/?probe=54369d3959) | Aug 16, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ea9196699a](https://linux-hardware.org/?probe=ea9196699a) | Aug 16, 2021 |
| Intel         | powered classmate PC        | Tablet      | [978012ace1](https://linux-hardware.org/?probe=978012ace1) | Aug 15, 2021 |
| Intel         | powered classmate PC        | Tablet      | [0ef2caca24](https://linux-hardware.org/?probe=0ef2caca24) | Aug 15, 2021 |
| ASRock        | M3A785GMH/128M              | Desktop     | [4ace1ea1ac](https://linux-hardware.org/?probe=4ace1ea1ac) | Aug 15, 2021 |
| BANGHO        | Suma 1025                   | Tablet      | [50eebaa5c8](https://linux-hardware.org/?probe=50eebaa5c8) | Aug 14, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [c2c86f701d](https://linux-hardware.org/?probe=c2c86f701d) | Aug 13, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [f8af262ae5](https://linux-hardware.org/?probe=f8af262ae5) | Aug 13, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [b42acf7c50](https://linux-hardware.org/?probe=b42acf7c50) | Aug 12, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [d62c66d9bd](https://linux-hardware.org/?probe=d62c66d9bd) | Aug 12, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [668328ae19](https://linux-hardware.org/?probe=668328ae19) | Aug 12, 2021 |
| Lenovo        | G40-80 80E4                 | Notebook    | [acd155c49f](https://linux-hardware.org/?probe=acd155c49f) | Aug 11, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [4c28c43c28](https://linux-hardware.org/?probe=4c28c43c28) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [8beee2f359](https://linux-hardware.org/?probe=8beee2f359) | Aug 10, 2021 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [d2e35c6ccb](https://linux-hardware.org/?probe=d2e35c6ccb) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [88dcb8813a](https://linux-hardware.org/?probe=88dcb8813a) | Aug 10, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [07fad2e81c](https://linux-hardware.org/?probe=07fad2e81c) | Aug 10, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | Notebook    | [c3b36c30d8](https://linux-hardware.org/?probe=c3b36c30d8) | Aug 09, 2021 |
| Exo           | Ready J7W                   | Desktop     | [df3a9167c8](https://linux-hardware.org/?probe=df3a9167c8) | Aug 09, 2021 |
| Exo           | Ready J7W                   | Desktop     | [c18b993ce6](https://linux-hardware.org/?probe=c18b993ce6) | Aug 09, 2021 |
| ASUSTek       | M4A78LT-M LX                | Desktop     | [bdd403e11c](https://linux-hardware.org/?probe=bdd403e11c) | Aug 09, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [53bb9bce29](https://linux-hardware.org/?probe=53bb9bce29) | Aug 08, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [a54ce42dd4](https://linux-hardware.org/?probe=a54ce42dd4) | Aug 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [76ee9bfbac](https://linux-hardware.org/?probe=76ee9bfbac) | Aug 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8f1124f1fd](https://linux-hardware.org/?probe=8f1124f1fd) | Aug 06, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a4ba68cc4e](https://linux-hardware.org/?probe=a4ba68cc4e) | Aug 06, 2021 |
| Gigabyte      | 970A-D3                     | Desktop     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| Lenovo        | IdeaPad U310                | Notebook    | [f57c372664](https://linux-hardware.org/?probe=f57c372664) | Aug 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Argentina/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 241       | 13.98%  |
| Ubuntu 18.04                 | 174       | 10.09%  |
| Ubuntu 22.04                 | 71        | 4.12%   |
| OpenMandriva 4.2             | 56        | 3.25%   |
| OpenMandriva 4.3             | 53        | 3.07%   |
| Debian 11                    | 49        | 2.84%   |
| Zorin 15                     | 36        | 2.09%   |
| Linux Mint 20.2              | 31        | 1.8%    |
| Manjaro                      | 27        | 1.57%   |
| Linux Mint 20.3              | 26        | 1.51%   |
| Linux Mint 20.1              | 26        | 1.51%   |
| Linux Mint 20                | 26        | 1.51%   |
| KDE neon 20.04               | 25        | 1.45%   |
| Arch Rolling                 | 25        | 1.45%   |
| Xubuntu 20.04                | 24        | 1.39%   |
| Fedora 36                    | 24        | 1.39%   |
| Zorin 16                     | 23        | 1.33%   |
| Linux Mint 19.3              | 23        | 1.33%   |
| BlackPanther 18.1            | 23        | 1.33%   |
| Ubuntu 19.04                 | 21        | 1.22%   |
| Arch                         | 20        | 1.16%   |
| ArcoLinux Rolling            | 19        | 1.1%    |
| Xubuntu 18.04                | 18        | 1.04%   |
| Fedora 33                    | 18        | 1.04%   |
| Pop!_OS 22.04                | 17        | 0.99%   |
| Ubuntu 19.10                 | 16        | 0.93%   |
| Pop!_OS 21.04                | 16        | 0.93%   |
| Kubuntu 20.04                | 16        | 0.93%   |
| Ubuntu MATE 20.04            | 15        | 0.87%   |
| Ubuntu 21.10                 | 14        | 0.81%   |
| Ubuntu 21.04                 | 14        | 0.81%   |
| Fedora 34                    | 14        | 0.81%   |
| Fedora 32                    | 14        | 0.81%   |
| Debian 10                    | 14        | 0.81%   |
| Ubuntu 18.10                 | 13        | 0.75%   |
| Pop!_OS 20.04                | 13        | 0.75%   |
| Ubuntu 20.10                 | 12        | 0.7%    |
| Pop!_OS 20.10                | 10        | 0.58%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 0.58%   |
| Nobara 36                    | 10        | 0.58%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 572       | 34.62%  |
| Linux Mint    | 152       | 9.2%    |
| OpenMandriva  | 124       | 7.51%   |
| Fedora        | 90        | 5.45%   |
| Debian        | 75        | 4.54%   |
| Zorin         | 61        | 3.69%   |
| Pop!_OS       | 60        | 3.63%   |
| Xubuntu       | 54        | 3.27%   |
| Manjaro       | 48        | 2.91%   |
| Arch          | 43        | 2.6%    |
| Endless       | 38        | 2.3%    |
| Kubuntu       | 33        | 2%      |
| KDE neon      | 30        | 1.82%   |
| BlackPanther  | 23        | 1.39%   |
| ROSA          | 22        | 1.33%   |
| Elementary    | 22        | 1.33%   |
| Ubuntu MATE   | 20        | 1.21%   |
| ArcoLinux     | 20        | 1.21%   |
| Lubuntu       | 17        | 1.03%   |
| Ubuntu Budgie | 12        | 0.73%   |
| Ubuntu Unity  | 11        | 0.67%   |
| openSUSE      | 11        | 0.67%   |
| Nobara        | 11        | 0.67%   |
| Clear Linux   | 11        | 0.67%   |
| LMDE          | 9         | 0.54%   |
| EndeavourOS   | 9         | 0.54%   |
| Gentoo        | 6         | 0.36%   |
| UbuntuDDE     | 5         | 0.3%    |
| Peppermint    | 5         | 0.3%    |
| Kali          | 5         | 0.3%    |
| LinuxFX       | 4         | 0.24%   |
| Solus         | 3         | 0.18%   |
| RHEL          | 3         | 0.18%   |
| Huayra        | 3         | 0.18%   |
| Deepin        | 3         | 0.18%   |
| Void Linux    | 2         | 0.12%   |
| Sparky        | 2         | 0.12%   |
| Rocky Linux   | 2         | 0.12%   |
| Reborn OS     | 2         | 0.12%   |
| Parrot        | 2         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 54        | 2.89%   |
| 5.16.7-desktop-1omv4003  | 52        | 2.78%   |
| 5.4.0-42-generic         | 44        | 2.35%   |
| 5.4.0-26-generic         | 25        | 1.34%   |
| 4.18.16-desktop-1bP      | 22        | 1.18%   |
| 5.4.0-52-generic         | 20        | 1.07%   |
| 5.4.0-48-generic         | 20        | 1.07%   |
| 5.3.0-40-generic         | 17        | 0.91%   |
| 5.15.0-41-generic        | 15        | 0.8%    |
| 5.4.0-91-generic         | 14        | 0.75%   |
| 5.4.0-40-generic         | 14        | 0.75%   |
| 5.4.0-37-generic         | 14        | 0.75%   |
| 5.3.0-28-generic         | 14        | 0.75%   |
| 5.15.0-52-generic        | 14        | 0.75%   |
| 5.4.0-74-generic         | 13        | 0.7%    |
| 5.3.0-46-generic         | 13        | 0.7%    |
| 5.8.0-53-generic         | 12        | 0.64%   |
| 5.4.0-72-generic         | 12        | 0.64%   |
| 5.4.0-58-generic         | 12        | 0.64%   |
| 5.4.0-29-generic         | 12        | 0.64%   |
| 5.3.0-53-generic         | 12        | 0.64%   |
| 5.11.0-27-generic        | 12        | 0.64%   |
| 5.4.0-80-generic         | 11        | 0.59%   |
| 5.4.0-47-generic         | 11        | 0.59%   |
| 5.4.0-19-generic         | 11        | 0.59%   |
| 5.15.0-48-generic        | 11        | 0.59%   |
| 5.15.0-46-generic        | 11        | 0.59%   |
| 5.13.0-28-generic        | 11        | 0.59%   |
| 5.8.0-43-generic         | 10        | 0.54%   |
| 5.4.0-45-generic         | 10        | 0.54%   |
| 5.11.0-37-generic        | 10        | 0.54%   |
| 4.18.0-15-generic        | 10        | 0.54%   |
| 5.8.0-7630-generic       | 9         | 0.48%   |
| 5.8.0-59-generic         | 9         | 0.48%   |
| 5.4.0-65-generic         | 9         | 0.48%   |
| 5.4.0-31-generic         | 9         | 0.48%   |
| 5.15.0-56-generic        | 9         | 0.48%   |
| 5.10.0-9-amd64           | 9         | 0.48%   |
| 4.18.0-17-generic        | 9         | 0.48%   |
| 6.1.1-desktop-1omv2290   | 8         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 371       | 21.14%  |
| 5.15.0  | 126       | 7.18%   |
| 4.15.0  | 119       | 6.78%   |
| 5.8.0   | 96        | 5.47%   |
| 5.3.0   | 96        | 5.47%   |
| 5.11.0  | 77        | 4.39%   |
| 5.13.0  | 72        | 4.1%    |
| 5.10.14 | 55        | 3.13%   |
| 5.0.0   | 55        | 3.13%   |
| 5.10.0  | 54        | 3.08%   |
| 5.16.7  | 52        | 2.96%   |
| 4.18.0  | 51        | 2.91%   |
| 4.19.0  | 27        | 1.54%   |
| 4.18.16 | 23        | 1.31%   |
| 5.19.0  | 18        | 1.03%   |
| 6.1.1   | 10        | 0.57%   |
| 5.14.0  | 10        | 0.57%   |
| 5.17.5  | 8         | 0.46%   |
| 5.15.5  | 7         | 0.4%    |
| 5.11.12 | 7         | 0.4%    |
| 4.4.0   | 7         | 0.4%    |
| 6.0.8   | 6         | 0.34%   |
| 5.18.0  | 6         | 0.34%   |
| 5.13.13 | 6         | 0.34%   |
| 6.0.9   | 5         | 0.28%   |
| 5.18.5  | 5         | 0.28%   |
| 5.18.16 | 5         | 0.28%   |
| 5.12.4  | 5         | 0.28%   |
| 4.9.20  | 5         | 0.28%   |
| 6.0.15  | 4         | 0.23%   |
| 6.0.12  | 4         | 0.23%   |
| 6.0.10  | 4         | 0.23%   |
| 5.9.16  | 4         | 0.23%   |
| 5.9.10  | 4         | 0.23%   |
| 5.8.6   | 4         | 0.23%   |
| 5.8.16  | 4         | 0.23%   |
| 5.18.12 | 4         | 0.23%   |
| 5.16.19 | 4         | 0.23%   |
| 5.16.16 | 4         | 0.23%   |
| 5.15.8  | 4         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 386       | 22.33%  |
| 5.15    | 165       | 9.54%   |
| 5.10    | 135       | 7.81%   |
| 5.8     | 119       | 6.88%   |
| 4.15    | 119       | 6.88%   |
| 5.3     | 98        | 5.67%   |
| 5.11    | 98        | 5.67%   |
| 5.13    | 93        | 5.38%   |
| 4.18    | 76        | 4.4%    |
| 5.16    | 74        | 4.28%   |
| 5.0     | 59        | 3.41%   |
| 5.19    | 42        | 2.43%   |
| 5.18    | 37        | 2.14%   |
| 6.0     | 31        | 1.79%   |
| 4.19    | 30        | 1.74%   |
| 5.17    | 24        | 1.39%   |
| 6.1     | 22        | 1.27%   |
| 5.14    | 19        | 1.1%    |
| 5.9     | 18        | 1.04%   |
| 4.9     | 17        | 0.98%   |
| 5.6     | 16        | 0.93%   |
| 5.7     | 12        | 0.69%   |
| 5.12    | 12        | 0.69%   |
| 4.4     | 7         | 0.4%    |
| 5.5     | 6         | 0.35%   |
| 4.1     | 3         | 0.17%   |
| 4.20    | 2         | 0.12%   |
| 4.13    | 2         | 0.12%   |
| 3.10    | 2         | 0.12%   |
| 5.2     | 1         | 0.06%   |
| 5.1     | 1         | 0.06%   |
| 4.17    | 1         | 0.06%   |
| 4.10    | 1         | 0.06%   |
| 3.16    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1512      | 94.38%  |
| i686    | 87        | 5.43%   |
| aarch64 | 2         | 0.12%   |
| armv7l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 680       | 40.99%  |
| KDE5             | 259       | 15.61%  |
| Unknown          | 200       | 12.06%  |
| XFCE             | 157       | 9.46%   |
| X-Cinnamon       | 102       | 6.15%   |
| MATE             | 71        | 4.28%   |
| KDE              | 41        | 2.47%   |
| Pantheon         | 19        | 1.15%   |
| LXQt             | 18        | 1.08%   |
| Cinnamon         | 16        | 0.96%   |
| LXDE             | 14        | 0.84%   |
| KDE4             | 14        | 0.84%   |
| Budgie           | 13        | 0.78%   |
| Unity            | 11        | 0.66%   |
| i3               | 11        | 0.66%   |
| Deepin           | 8         | 0.48%   |
| qtile            | 3         | 0.18%   |
| GNOME Flashback  | 3         | 0.18%   |
| xmonad           | 2         | 0.12%   |
| lightdm-xsession | 2         | 0.12%   |
| i3-with-shmlog   | 2         | 0.12%   |
| DWM              | 2         | 0.12%   |
| Cutefish         | 2         | 0.12%   |
| bspwm            | 2         | 0.12%   |
| UKUI             | 1         | 0.06%   |
| trinity          | 1         | 0.06%   |
| sway             | 1         | 0.06%   |
| openbox          | 1         | 0.06%   |
| icewm            | 1         | 0.06%   |
| Enlightenment    | 1         | 0.06%   |
| awesome          | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1318      | 80.71%  |
| Wayland | 188       | 11.51%  |
| Unknown | 110       | 6.74%   |
| Tty     | 17        | 1.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 930       | 56.33%  |
| SDDM    | 244       | 14.78%  |
| GDM     | 156       | 9.45%   |
| LightDM | 131       | 7.93%   |
| GDM3    | 118       | 7.15%   |
| TDM     | 49        | 2.97%   |
| KDM     | 14        | 0.85%   |
| SLiM    | 3         | 0.18%   |
| LXDM    | 3         | 0.18%   |
| XDM     | 2         | 0.12%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| es_AR       | 885       | 54.06%  |
| en_US       | 366       | 22.36%  |
| Unknown     | 206       | 12.58%  |
| es_ES       | 94        | 5.74%   |
| es_MX       | 28        | 1.71%   |
| C           | 25        | 1.53%   |
| en_GB       | 11        | 0.67%   |
| pt_BR       | 4         | 0.24%   |
| POSIX       | 2         | 0.12%   |
| it_IT       | 2         | 0.12%   |
| es_UY       | 2         | 0.12%   |
| es_US       | 2         | 0.12%   |
| es_CL       | 2         | 0.12%   |
| ru_RU       | 1         | 0.06%   |
| fr_FR       | 1         | 0.06%   |
| es_AR.UtF-8 | 1         | 0.06%   |
| en_UTF-8    | 1         | 0.06%   |
| en_US.UTF8  | 1         | 0.06%   |
| en_CA       | 1         | 0.06%   |
| en_AG       | 1         | 0.06%   |
| C.UTF8      | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 956       | 58.44%  |
| EFI  | 680       | 41.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1293      | 79.28%  |
| Overlay | 153       | 9.38%   |
| Btrfs   | 96        | 5.89%   |
| Unknown | 52        | 3.19%   |
| Xfs     | 18        | 1.1%    |
| Zfs     | 6         | 0.37%   |
| Ext2    | 5         | 0.31%   |
| Tmpfs   | 3         | 0.18%   |
| Ext3    | 3         | 0.18%   |
| F2fs    | 1         | 0.06%   |
| Aufs    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 986       | 60.49%  |
| GPT     | 451       | 27.67%  |
| MBR     | 193       | 11.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1383      | 85.11%  |
| Yes       | 242       | 14.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1101      | 67.67%  |
| Yes       | 526       | 32.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 302       | 18.85%  |
| Lenovo                  | 213       | 13.3%   |
| Gigabyte Technology     | 201       | 12.55%  |
| Hewlett-Packard         | 139       | 8.68%   |
| Dell                    | 122       | 7.62%   |
| MSI                     | 101       | 6.3%    |
| ASRock                  | 86        | 5.37%   |
| Intel                   | 46        | 2.87%   |
| BANGHO                  | 44        | 2.75%   |
| Acer                    | 44        | 2.75%   |
| Toshiba                 | 30        | 1.87%   |
| Exo                     | 29        | 1.81%   |
| Samsung Electronics     | 25        | 1.56%   |
| Positivo                | 23        | 1.44%   |
| Sony                    | 17        | 1.06%   |
| ECS                     | 17        | 1.06%   |
| Apple                   | 14        | 0.87%   |
| Biostar                 | 11        | 0.69%   |
| Unknown                 | 11        | 0.69%   |
| Compal                  | 8         | 0.5%    |
| Clevo                   | 7         | 0.44%   |
| AMI                     | 7         | 0.44%   |
| Foxconn                 | 6         | 0.37%   |
| Standard                | 5         | 0.31%   |
| Quanta                  | 5         | 0.31%   |
| NOBLEX                  | 5         | 0.31%   |
| Coradir                 | 5         | 0.31%   |
| Advantec                | 5         | 0.31%   |
| System76                | 4         | 0.25%   |
| NSX                     | 4         | 0.25%   |
| HUAWEI                  | 4         | 0.25%   |
| Kanji                   | 3         | 0.19%   |
| A-DATA Technology       | 3         | 0.19%   |
| Raspberry Pi Foundation | 2         | 0.12%   |
| Radio Victoria Fueguina | 2         | 0.12%   |
| Pegatron                | 2         | 0.12%   |
| PCChips                 | 2         | 0.12%   |
| PCBOX                   | 2         | 0.12%   |
| Packard Bell            | 2         | 0.12%   |
| Novatech                | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 24        | 1.5%    |
| MSI MS-7721                            | 22        | 1.37%   |
| ASUS All Series                        | 16        | 1%      |
| Gigabyte F2A68HM-H                     | 12        | 0.75%   |
| ASUS PRIME A320M-K                     | 12        | 0.75%   |
| Lenovo V330-15IKB 81AX                 | 9         | 0.56%   |
| BANGHO MOV                             | 9         | 0.56%   |
| Gigabyte H81M-H                        | 8         | 0.5%    |
| Gigabyte A320M-S2H                     | 8         | 0.5%    |
| ASUS PRIME B450M-A                     | 8         | 0.5%    |
| ASUS P5KPL-AM SE                       | 8         | 0.5%    |
| Lenovo ThinkPad L15 Gen 2 20X4S27200   | 7         | 0.44%   |
| HP Notebook                            | 7         | 0.44%   |
| HP Laptop 15-bs0xx                     | 7         | 0.44%   |
| Gigabyte H61M-S1                       | 7         | 0.44%   |
| BANGHO Suma 1025                       | 7         | 0.44%   |
| MSI MS-7C52                            | 6         | 0.37%   |
| MSI MS-7A15                            | 6         | 0.37%   |
| Lenovo G470 20078                      | 6         | 0.37%   |
| Intel powered classmate PC             | 6         | 0.37%   |
| Gigabyte M68MT-S2                      | 6         | 0.37%   |
| Gigabyte H110M-H                       | 6         | 0.37%   |
| BANGHO MAX G0101                       | 6         | 0.37%   |
| ASUS ROG STRIX B550-F GAMING           | 6         | 0.37%   |
| HP Pavilion dv6                        | 5         | 0.31%   |
| Gigabyte F2A55M-HD2                    | 5         | 0.31%   |
| Gigabyte A320M-S2H V2                  | 5         | 0.31%   |
| Gigabyte A320M-H                       | 5         | 0.31%   |
| Exo CloudbookE15                       | 5         | 0.31%   |
| ECS H81H3-M4                           | 5         | 0.31%   |
| Dell Inspiron 1525                     | 5         | 0.31%   |
| Coradir Coradir/ES10IS5                | 5         | 0.31%   |
| BANGHO W240HU/W250HUQ                  | 5         | 0.31%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA | 5         | 0.31%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR   | 5         | 0.31%   |
| MSI MS-7309                            | 4         | 0.25%   |
| Lenovo ThinkPad T430 2349DS5           | 4         | 0.25%   |
| Lenovo IdeaPad 320-15ABR 80XS          | 4         | 0.25%   |
| Intel DN2820FYB H24582-205             | 4         | 0.25%   |
| HP Pavilion Notebook                   | 4         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 75        | 4.68%   |
| Dell Inspiron      | 63        | 3.93%   |
| ASUS PRIME         | 47        | 2.93%   |
| Lenovo IdeaPad     | 43        | 2.68%   |
| HP Pavilion        | 39        | 2.43%   |
| Dell Latitude      | 37        | 2.31%   |
| Acer Aspire        | 37        | 2.31%   |
| ASUS VivoBook      | 28        | 1.75%   |
| Unknown            | 24        | 1.5%    |
| MSI MS-7721        | 22        | 1.37%   |
| HP Laptop          | 20        | 1.25%   |
| Toshiba Satellite  | 18        | 1.12%   |
| ASUS All           | 16        | 1%      |
| HP Compaq          | 14        | 0.87%   |
| ASUS ROG           | 14        | 0.87%   |
| Gigabyte A320M-S2H | 13        | 0.81%   |
| Gigabyte F2A68HM-H | 12        | 0.75%   |
| Lenovo ThinkBook   | 10        | 0.62%   |
| HP 250             | 10        | 0.62%   |
| Exo Smart          | 10        | 0.62%   |
| BANGHO MAX         | 10        | 0.62%   |
| Lenovo V330-15IKB  | 9         | 0.56%   |
| HP EliteBook       | 9         | 0.56%   |
| BANGHO MOV         | 9         | 0.56%   |
| ASUS M5A78L-M      | 9         | 0.56%   |
| Lenovo ThinkCentre | 8         | 0.5%    |
| Gigabyte H81M-H    | 8         | 0.5%    |
| Gigabyte B450      | 8         | 0.5%    |
| BANGHO Suma        | 8         | 0.5%    |
| ASUS P5KPL-AM      | 8         | 0.5%    |
| HP Notebook        | 7         | 0.44%   |
| Gigabyte H61M-S1   | 7         | 0.44%   |
| Dell OptiPlex      | 7         | 0.44%   |
| ASUS TUF           | 7         | 0.44%   |
| Samsung 300E4A     | 6         | 0.37%   |
| MSI MS-7C52        | 6         | 0.37%   |
| MSI MS-7A15        | 6         | 0.37%   |
| Lenovo G470        | 6         | 0.37%   |
| Intel powered      | 6         | 0.37%   |
| HP ProBook         | 6         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 149       | 9.3%    |
| 2012    | 147       | 9.18%   |
| 2018    | 127       | 7.93%   |
| 2011    | 118       | 7.37%   |
| 2020    | 116       | 7.24%   |
| 2015    | 110       | 6.87%   |
| 2019    | 107       | 6.68%   |
| 2014    | 104       | 6.49%   |
| 2013    | 103       | 6.43%   |
| 2010    | 100       | 6.24%   |
| 2021    | 91        | 5.68%   |
| 2016    | 83        | 5.18%   |
| 2008    | 76        | 4.74%   |
| 2009    | 64        | 4%      |
| 2007    | 52        | 3.25%   |
| 2006    | 34        | 2.12%   |
| Unknown | 9         | 0.56%   |
| 2022    | 4         | 0.25%   |
| 2004    | 4         | 0.25%   |
| 2005    | 3         | 0.19%   |
| 2001    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 858       | 53.56%  |
| Desktop        | 684       | 42.7%   |
| Convertible    | 21        | 1.31%   |
| Tablet         | 15        | 0.94%   |
| Mini pc        | 12        | 0.75%   |
| All in one     | 8         | 0.5%    |
| System on chip | 3         | 0.19%   |
| Server         | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1511      | 93.79%  |
| Enabled  | 100       | 6.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1600      | 99.88%  |
| Yes  | 2         | 0.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 403       | 24.88%  |
| 4.01-8.0    | 381       | 23.52%  |
| 8.01-16.0   | 304       | 18.77%  |
| 16.01-24.0  | 216       | 13.33%  |
| 1.01-2.0    | 144       | 8.89%   |
| 32.01-64.0  | 78        | 4.81%   |
| 2.01-3.0    | 40        | 2.47%   |
| 0.51-1.0    | 25        | 1.54%   |
| 24.01-32.0  | 17        | 1.05%   |
| 64.01-256.0 | 11        | 0.68%   |
| 0.01-0.5    | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 656       | 37.61%  |
| 2.01-3.0   | 409       | 23.45%  |
| 4.01-8.0   | 209       | 11.98%  |
| 3.01-4.0   | 198       | 11.35%  |
| 0.51-1.0   | 175       | 10.03%  |
| 8.01-16.0  | 63        | 3.61%   |
| 0.01-0.5   | 26        | 1.49%   |
| 16.01-24.0 | 8         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1031      | 62.79%  |
| 2      | 410       | 24.97%  |
| 3      | 125       | 7.61%   |
| 4      | 48        | 2.92%   |
| 5      | 12        | 0.73%   |
| 0      | 10        | 0.61%   |
| 6      | 3         | 0.18%   |
| 7      | 2         | 0.12%   |
| 20     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1011      | 62.6%   |
| Yes       | 604       | 37.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1436      | 89.58%  |
| No        | 167       | 10.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1183      | 73.11%  |
| No        | 435       | 26.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 877       | 54.3%   |
| Yes       | 738       | 45.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Argentina | 1602      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Buenos Aires                | 389       | 23.2%   |
| Córdoba                    | 108       | 6.44%   |
| Rosario                     | 72        | 4.29%   |
| La Plata                    | 44        | 2.62%   |
| Mar del Plata               | 43        | 2.56%   |
| Lanus                       | 22        | 1.31%   |
| Corrientes                  | 22        | 1.31%   |
| Avellaneda                  | 21        | 1.25%   |
| San Miguel de Tucumán      | 19        | 1.13%   |
| Mendoza                     | 19        | 1.13%   |
| Lomas de Zamora             | 18        | 1.07%   |
| Santa Fe                    | 15        | 0.89%   |
| Ramos Mejia                 | 15        | 0.89%   |
| Florencio Varela            | 15        | 0.89%   |
| Resistencia                 | 14        | 0.83%   |
| Quilmes                     | 14        | 0.83%   |
| Olivos                      | 14        | 0.83%   |
| Bahía Blanca               | 14        | 0.83%   |
| Villa Ballester             | 13        | 0.78%   |
| Tandil                      | 13        | 0.78%   |
| Paraná                     | 13        | 0.78%   |
| Salta                       | 12        | 0.72%   |
| Ituzaingo                   | 12        | 0.72%   |
| Posadas                     | 11        | 0.66%   |
| Neuquén                    | 11        | 0.66%   |
| Viedma                      | 10        | 0.6%    |
| San Telmo                   | 10        | 0.6%    |
| San Juan                    | 10        | 0.6%    |
| Caseros                     | 10        | 0.6%    |
| Villa Nueva                 | 9         | 0.54%   |
| San Nicolás de los Arroyos | 9         | 0.54%   |
| San Martín de los Andes    | 9         | 0.54%   |
| Bariloche                   | 9         | 0.54%   |
| Yerba Buena                 | 8         | 0.48%   |
| Pilar                       | 8         | 0.48%   |
| Godoy Cruz                  | 8         | 0.48%   |
| Tigre                       | 7         | 0.42%   |
| San Luis                    | 7         | 0.42%   |
| San Isidro                  | 7         | 0.42%   |
| San Francisco               | 7         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 608       | 913    | 27.93%  |
| Seagate                   | 300       | 371    | 13.78%  |
| Kingston                  | 288       | 363    | 13.23%  |
| Samsung Electronics       | 188       | 262    | 8.64%   |
| Toshiba                   | 185       | 230    | 8.5%    |
| Hitachi                   | 78        | 87     | 3.58%   |
| Unknown                   | 59        | 76     | 2.71%   |
| SanDisk                   | 57        | 80     | 2.62%   |
| HGST                      | 47        | 51     | 2.16%   |
| A-DATA Technology         | 44        | 49     | 2.02%   |
| SK hynix                  | 36        | 39     | 1.65%   |
| Gigabyte Technology       | 33        | 49     | 1.52%   |
| Crucial                   | 30        | 47     | 1.38%   |
| Intel                     | 20        | 39     | 0.92%   |
| Hewlett-Packard           | 16        | 22     | 0.73%   |
| Micron Technology         | 14        | 17     | 0.64%   |
| Maxtor                    | 14        | 15     | 0.64%   |
| Corsair                   | 12        | 12     | 0.55%   |
| China                     | 10        | 11     | 0.46%   |
| Realtek Semiconductor     | 9         | 11     | 0.41%   |
| PNY                       | 9         | 18     | 0.41%   |
| XPG                       | 8         | 8      | 0.37%   |
| KIOXIA                    | 8         | 8      | 0.37%   |
| Patriot                   | 6         | 8      | 0.28%   |
| Colorful                  | 6         | 7      | 0.28%   |
| Silicon Motion            | 5         | 6      | 0.23%   |
| Phison                    | 5         | 6      | 0.23%   |
| ADATA Technology          | 5         | 6      | 0.23%   |
| Lexar                     | 4         | 5      | 0.18%   |
| HS-SSD-C100               | 4         | 5      | 0.18%   |
| Unknown                   | 4         | 4      | 0.18%   |
| Union Memory              | 3         | 3      | 0.14%   |
| OCZ                       | 3         | 3      | 0.14%   |
| Netac                     | 3         | 5      | 0.14%   |
| Neo                       | 3         | 3      | 0.14%   |
| Micron/Crucial Technology | 3         | 5      | 0.14%   |
| Hikvision                 | 3         | 3      | 0.14%   |
| Fujitsu                   | 3         | 3      | 0.14%   |
| FORESEE                   | 3         | 3      | 0.14%   |
| Apple                     | 3         | 3      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 91        | 3.79%   |
| Kingston SA400S37480G 480GB SSD      | 53        | 2.21%   |
| Seagate ST1000LM035-1RK172 1TB       | 41        | 1.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 34        | 1.42%   |
| WDC WD10EZEX-08WN4A0 1TB             | 33        | 1.38%   |
| Toshiba MQ01ABF050 500GB             | 28        | 1.17%   |
| Kingston SA400S37120G 120GB SSD      | 28        | 1.17%   |
| Toshiba MQ01ABD100 1TB               | 27        | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 26        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB      | 21        | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB       | 21        | 0.88%   |
| Kingston SV300S37A120G 120GB SSD     | 20        | 0.83%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 19        | 0.79%   |
| WDC WD5000AAKX-001CA0 500GB          | 19        | 0.79%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 17        | 0.71%   |
| WDC WD10EZEX-00BN5A0 1TB             | 17        | 0.71%   |
| Unknown MMC Card  32GB               | 17        | 0.71%   |
| Kingston SV300S37A240G 240GB SSD     | 15        | 0.63%   |
| Kingston SUV400S37240G 240GB SSD     | 14        | 0.58%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 13        | 0.54%   |
| Toshiba MQ04ABF100 1TB               | 13        | 0.54%   |
| Toshiba DT01ACA100 1TB               | 13        | 0.54%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 12        | 0.5%    |
| WDC WD1600AABS-00PRA0 160GB          | 12        | 0.5%    |
| Toshiba MQ01ABD032 320GB             | 12        | 0.5%    |
| Seagate ST500LM030-2E717D 500GB      | 12        | 0.5%    |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 12        | 0.5%    |
| A-DATA SU630 240GB SSD               | 12        | 0.5%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 11        | 0.46%   |
| Toshiba DT01ACA050 500GB             | 11        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB      | 11        | 0.46%   |
| Kingston SA400S37960G 960GB SSD      | 11        | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 10        | 0.42%   |
| WDC WD10EZEX-21WN4A0 1TB             | 10        | 0.42%   |
| WDC WD10JPVX-60JC3T1 1TB             | 9         | 0.38%   |
| WDC WD10EZEX-00WN4A0 1TB             | 9         | 0.38%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 9         | 0.38%   |
| Samsung HD502HJ 500GB                | 9         | 0.38%   |
| Samsung HD322HJ 320GB                | 9         | 0.38%   |
| HGST HTS721010A9E630 1TB             | 9         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 514       | 740    | 42.03%  |
| Seagate             | 295       | 364    | 24.12%  |
| Toshiba             | 168       | 209    | 13.74%  |
| Samsung Electronics | 98        | 134    | 8.01%   |
| Hitachi             | 78        | 87     | 6.38%   |
| HGST                | 47        | 51     | 3.84%   |
| Maxtor              | 11        | 11     | 0.9%    |
| Unknown             | 4         | 4      | 0.33%   |
| Fujitsu             | 3         | 3      | 0.25%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Quantum             | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |
| ASMT                | 1         | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 263       | 333    | 40.59%  |
| WDC                 | 104       | 129    | 16.05%  |
| Samsung Electronics | 39        | 61     | 6.02%   |
| A-DATA Technology   | 38        | 41     | 5.86%   |
| SanDisk             | 33        | 41     | 5.09%   |
| Gigabyte Technology | 29        | 45     | 4.48%   |
| Crucial             | 29        | 46     | 4.48%   |
| PNY                 | 9         | 18     | 1.39%   |
| Hewlett-Packard     | 9         | 12     | 1.39%   |
| Corsair             | 9         | 9      | 1.39%   |
| SK hynix            | 8         | 9      | 1.23%   |
| Intel               | 6         | 7      | 0.93%   |
| Colorful            | 6         | 7      | 0.93%   |
| China               | 6         | 6      | 0.93%   |
| Toshiba             | 5         | 5      | 0.77%   |
| Patriot             | 5         | 7      | 0.77%   |
| Micron Technology   | 4         | 6      | 0.62%   |
| Lexar               | 4         | 5      | 0.62%   |
| Seagate             | 3         | 5      | 0.46%   |
| OCZ                 | 3         | 3      | 0.46%   |
| Netac               | 3         | 5      | 0.46%   |
| Maxtor              | 3         | 4      | 0.46%   |
| FORESEE             | 3         | 3      | 0.46%   |
| Team                | 2         | 2      | 0.31%   |
| SPCC                | 2         | 2      | 0.31%   |
| LITEONIT            | 2         | 2      | 0.31%   |
| Kimtigo             | 2         | 2      | 0.31%   |
| HS-SSD-C100         | 2         | 3      | 0.31%   |
| Hikvision           | 2         | 2      | 0.31%   |
| Apple               | 2         | 2      | 0.31%   |
| Unknown             | 2         | 2      | 0.31%   |
| XrayDisk            | 1         | 1      | 0.15%   |
| WDC WDS2            | 1         | 1      | 0.15%   |
| Transcend           | 1         | 1      | 0.15%   |
| tecmiyo             | 1         | 3      | 0.15%   |
| Super Talent        | 1         | 1      | 0.15%   |
| SMI                 | 1         | 1      | 0.15%   |
| NGFF                | 1         | 2      | 0.15%   |
| Neo                 | 1         | 1      | 0.15%   |
| LITEON              | 1         | 1      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1068      | 1609   | 53.29%  |
| SSD     | 610       | 849    | 30.44%  |
| NVMe    | 252       | 360    | 12.57%  |
| MMC     | 56        | 74     | 2.79%   |
| Unknown | 18        | 17     | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1397      | 2446   | 80.8%   |
| NVMe | 252       | 360    | 14.57%  |
| MMC  | 56        | 74     | 3.24%   |
| SAS  | 24        | 29     | 1.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1075      | 1613   | 64.26%  |
| 0.51-1.0   | 484       | 685    | 28.93%  |
| 1.01-2.0   | 79        | 112    | 4.72%   |
| 3.01-4.0   | 13        | 22     | 0.78%   |
| 2.01-3.0   | 11        | 12     | 0.66%   |
| 4.01-10.0  | 11        | 14     | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 493       | 29.1%   |
| 251-500        | 397       | 23.44%  |
| 501-1000       | 258       | 15.23%  |
| 1001-2000      | 132       | 7.79%   |
| 1-20           | 120       | 7.08%   |
| 51-100         | 106       | 6.26%   |
| 21-50          | 81        | 4.78%   |
| Unknown        | 40        | 2.36%   |
| 2001-3000      | 39        | 2.3%    |
| More than 3000 | 28        | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 713       | 40.88%  |
| 21-50          | 288       | 16.51%  |
| 101-250        | 229       | 13.13%  |
| 51-100         | 202       | 11.58%  |
| 251-500        | 131       | 7.51%   |
| 501-1000       | 83        | 4.76%   |
| 1001-2000      | 41        | 2.35%   |
| Unknown        | 40        | 2.29%   |
| 2001-3000      | 9         | 0.52%   |
| More than 3000 | 8         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB        | 7         | 9      | 3.72%   |
| Seagate ST1000LM035-1RK172 1TB     | 6         | 6      | 3.19%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4         | 4      | 2.13%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 3         | 3      | 1.6%    |
| WDC WD5000BPVT-22HXZT3 500GB       | 3         | 3      | 1.6%    |
| WDC WD5000AAKX-00ERMA0 500GB       | 3         | 3      | 1.6%    |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 3      | 1.6%    |
| WDC WD10EARS-00Y5B1 1TB            | 3         | 3      | 1.6%    |
| Toshiba MQ01ABF050 500GB           | 3         | 3      | 1.6%    |
| Toshiba MQ01ABD100 1TB             | 3         | 6      | 1.6%    |
| Toshiba MK1665GSX 160GB            | 3         | 3      | 1.6%    |
| Seagate ST500DM002-1BD142 500GB    | 3         | 3      | 1.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.6%    |
| Kingston SA400S37240G 240GB SSD    | 3         | 3      | 1.6%    |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.6%    |
| WDC WD5000AAKX-08ERMA0 500GB       | 2         | 2      | 1.06%   |
| WDC WD3200AAKS-00L9A0 320GB        | 2         | 2      | 1.06%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 2         | 2      | 1.06%   |
| Seagate ST9500325AS 500GB          | 2         | 2      | 1.06%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 4      | 1.06%   |
| Seagate ST500LM030-2E717D 500GB    | 2         | 2      | 1.06%   |
| Seagate ST1500DL003-9VT16L 1TB     | 2         | 2      | 1.06%   |
| Seagate ST1000DM003-9YN162 1TB     | 2         | 2      | 1.06%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 2      | 1.06%   |
| Samsung Electronics SP0411N 40GB   | 2         | 3      | 1.06%   |
| Samsung Electronics HN-M101MBB 1TB | 2         | 2      | 1.06%   |
| Samsung Electronics HD322HJ 320GB  | 2         | 2      | 1.06%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 2      | 1.06%   |
| Kingston SUV400S37240G 240GB SSD   | 2         | 2      | 1.06%   |
| HGST HTS721010A9E630 1TB           | 2         | 3      | 1.06%   |
| HGST HTS541075A9E680 752GB         | 2         | 2      | 1.06%   |
| XPG SPECTRIX S40G 4TB              | 1         | 1      | 0.53%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 4      | 0.53%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 1      | 0.53%   |
| WDC WD800JD-00MSA1 80GB            | 1         | 1      | 0.53%   |
| WDC WD800BD-22MRA1 80GB            | 1         | 1      | 0.53%   |
| WDC WD800BB-75JHC0 80GB            | 1         | 1      | 0.53%   |
| WDC WD800BB-00JHC0 80GB            | 1         | 1      | 0.53%   |
| WDC WD6400AAKS-65Z7B0 640GB        | 1         | 1      | 0.53%   |
| WDC WD5003ABYX-01WERA0 500GB       | 1         | 1      | 0.53%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 68        | 85     | 38.42%  |
| Seagate             | 39        | 42     | 22.03%  |
| Toshiba             | 20        | 23     | 11.3%   |
| Samsung Electronics | 15        | 17     | 8.47%   |
| HGST                | 10        | 11     | 5.65%   |
| Hitachi             | 9         | 9      | 5.08%   |
| Kingston            | 8         | 8      | 4.52%   |
| Maxtor              | 2         | 2      | 1.13%   |
| A-DATA Technology   | 2         | 2      | 1.13%   |
| XPG                 | 1         | 1      | 0.56%   |
| tecmiyo             | 1         | 3      | 0.56%   |
| SMI                 | 1         | 1      | 0.56%   |
| Quantum             | 1         | 1      | 0.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 63        | 77     | 40.13%  |
| Seagate             | 39        | 42     | 24.84%  |
| Toshiba             | 20        | 23     | 12.74%  |
| Samsung Electronics | 13        | 15     | 8.28%   |
| HGST                | 10        | 11     | 6.37%   |
| Hitachi             | 9         | 9      | 5.73%   |
| Maxtor              | 2         | 2      | 1.27%   |
| Quantum             | 1         | 1      | 0.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 148       | 180    | 88.1%   |
| SSD  | 19        | 24     | 11.31%  |
| NVMe | 1         | 1      | 0.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB       | 2         | 2      | 28.57%  |
| WDC WD1600BEVT-80A23T0 160GB      | 1         | 1      | 14.29%  |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 14.29%  |
| Toshiba MK1665GSX 160GB           | 1         | 1      | 14.29%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 14.29%  |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Toshiba             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1028      | 1829   | 60.19%  |
| Works    | 508       | 868    | 29.74%  |
| Malfunc  | 165       | 205    | 9.66%   |
| Failed   | 7         | 7      | 0.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1015      | 56.67%  |
| AMD                              | 369       | 20.6%   |
| Nvidia                           | 73        | 4.08%   |
| Samsung Electronics              | 56        | 3.13%   |
| SanDisk                          | 51        | 2.85%   |
| Kingston Technology Company      | 29        | 1.62%   |
| SK hynix                         | 28        | 1.56%   |
| VIA Technologies                 | 27        | 1.51%   |
| Realtek Semiconductor            | 17        | 0.95%   |
| Silicon Integrated Systems [SiS] | 15        | 0.84%   |
| Phison Electronics               | 14        | 0.78%   |
| Toshiba America Info Systems     | 12        | 0.67%   |
| JMicron Technology               | 12        | 0.67%   |
| Silicon Motion                   | 11        | 0.61%   |
| KIOXIA                           | 11        | 0.61%   |
| ASMedia Technology               | 10        | 0.56%   |
| Micron Technology                | 9         | 0.5%    |
| ADATA Technology                 | 8         | 0.45%   |
| Marvell Technology Group         | 7         | 0.39%   |
| Union Memory (Shenzhen)          | 4         | 0.22%   |
| Micron/Crucial Technology        | 4         | 0.22%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.11%   |
| Silicon Image                    | 1         | 0.06%   |
| Promise Technology               | 1         | 0.06%   |
| Lite-On Technology               | 1         | 0.06%   |
| Broadcom / LSI                   | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 237       | 10.68%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 115       | 5.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 89        | 4.01%   |
| Nvidia MCP61 SATA Controller                                                            | 62        | 2.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 61        | 2.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 59        | 2.66%   |
| Nvidia MCP61 IDE                                                                        | 54        | 2.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 53        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 50        | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 48        | 2.16%   |
| AMD FCH SATA Controller D                                                               | 46        | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 45        | 2.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 43        | 1.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 40        | 1.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 35        | 1.58%   |
| AMD 400 Series Chipset SATA Controller                                                  | 32        | 1.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29        | 1.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 29        | 1.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 29        | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 28        | 1.26%   |
| AMD FCH IDE Controller                                                                  | 27        | 1.22%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 26        | 1.17%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 25        | 1.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 25        | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 24        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 23        | 1.04%   |
| Samsung NVMe SSD Controller 980                                                         | 21        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 21        | 0.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 20        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 19        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 19        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 18        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 17        | 0.77%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 16        | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 16        | 0.72%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 15        | 0.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 15        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1168      | 62.69%  |
| IDE  | 366       | 19.65%  |
| NVMe | 254       | 13.63%  |
| RAID | 74        | 3.97%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1124      | 70.12%  |
| AMD    | 476       | 29.69%  |
| ARM    | 3         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 24        | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 1.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 16        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 15        | 0.94%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 15        | 0.94%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 15        | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.87%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 14        | 0.87%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 14        | 0.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.75%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 11        | 0.69%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 10        | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 0.62%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 10        | 0.62%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 10        | 0.62%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 10        | 0.62%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 10        | 0.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.56%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 9         | 0.56%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 9         | 0.56%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 9         | 0.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 0.56%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.56%   |
| AMD Athlon II X2 250 Processor                | 9         | 0.56%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 9         | 0.56%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 8         | 0.5%    |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 8         | 0.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.5%    |
| Intel Atom CPU N455 @ 1.66GHz                 | 8         | 0.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 8         | 0.5%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.5%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 8         | 0.5%    |
| AMD A4-4000 APU with Radeon HD Graphics       | 8         | 0.5%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 7         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 319       | 19.9%   |
| Intel Core i7           | 207       | 12.91%  |
| Intel Core i3           | 156       | 9.73%   |
| Intel Celeron           | 122       | 7.61%   |
| AMD Ryzen 5             | 84        | 5.24%   |
| Other                   | 63        | 3.93%   |
| Intel Atom              | 55        | 3.43%   |
| Intel Pentium           | 49        | 3.06%   |
| AMD Ryzen 7             | 48        | 2.99%   |
| Intel Core 2 Duo        | 43        | 2.68%   |
| Intel Pentium Dual-Core | 38        | 2.37%   |
| AMD A8                  | 36        | 2.25%   |
| AMD A6                  | 32        | 2%      |
| AMD FX                  | 30        | 1.87%   |
| Intel Pentium Dual      | 25        | 1.56%   |
| AMD Ryzen 3             | 25        | 1.56%   |
| AMD Athlon II X2        | 22        | 1.37%   |
| AMD A4                  | 22        | 1.37%   |
| AMD Athlon 64 X2        | 21        | 1.31%   |
| AMD A10                 | 21        | 1.31%   |
| AMD Sempron             | 17        | 1.06%   |
| AMD Athlon              | 15        | 0.94%   |
| AMD Phenom II X4        | 14        | 0.87%   |
| Intel Core 2            | 11        | 0.69%   |
| AMD Ryzen 9             | 11        | 0.69%   |
| Intel Pentium D         | 9         | 0.56%   |
| Intel Pentium 4         | 9         | 0.56%   |
| Intel Genuine           | 9         | 0.56%   |
| AMD Phenom II X6        | 8         | 0.5%    |
| AMD Athlon II X4        | 7         | 0.44%   |
| AMD A12                 | 6         | 0.37%   |
| Intel Core 2 Quad       | 5         | 0.31%   |
| AMD E1                  | 5         | 0.31%   |
| AMD Athlon II X3        | 5         | 0.31%   |
| AMD Athlon II           | 5         | 0.31%   |
| Intel Xeon              | 4         | 0.25%   |
| AMD Phenom              | 4         | 0.25%   |
| Intel Pentium Gold      | 3         | 0.19%   |
| Intel Core i9           | 3         | 0.19%   |
| AMD Ryzen 7 PRO         | 3         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 814       | 50.78%  |
| 4       | 483       | 30.13%  |
| 1       | 109       | 6.8%    |
| 6       | 99        | 6.18%   |
| 8       | 67        | 4.18%   |
| 3       | 17        | 1.06%   |
| 12      | 5         | 0.31%   |
| 16      | 4         | 0.25%   |
| Unknown | 3         | 0.19%   |
| 10      | 2         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1599      | 99.81%  |
| 2       | 2         | 0.12%   |
| Unknown | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 943       | 58.79%  |
| 1       | 658       | 41.02%  |
| Unknown | 3         | 0.19%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1550      | 96.45%  |
| Unknown        | 31        | 1.93%   |
| 32-bit         | 19        | 1.18%   |
| 64-bit         | 7         | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 315       | 18.99%  |
| 0x306a9    | 97        | 5.85%   |
| 0x206a7    | 94        | 5.67%   |
| 0x306c3    | 63        | 3.8%    |
| 0x1067a    | 59        | 3.56%   |
| 0x806e9    | 46        | 2.77%   |
| 0x806ec    | 41        | 2.47%   |
| 0x6fd      | 36        | 2.17%   |
| 0x08108109 | 33        | 1.99%   |
| 0x906e9    | 32        | 1.93%   |
| 0x406e3    | 32        | 1.93%   |
| 0x010000c8 | 32        | 1.93%   |
| 0x806c1    | 30        | 1.81%   |
| 0x806ea    | 29        | 1.75%   |
| 0x306d4    | 29        | 1.75%   |
| 0x30678    | 29        | 1.75%   |
| 0x906ea    | 27        | 1.63%   |
| 0x06001119 | 25        | 1.51%   |
| 0x506e3    | 24        | 1.45%   |
| 0x20655    | 23        | 1.39%   |
| 0x40651    | 22        | 1.33%   |
| 0x406c4    | 21        | 1.27%   |
| 0x06003106 | 20        | 1.21%   |
| 0x706e5    | 19        | 1.15%   |
| 0x106ca    | 18        | 1.08%   |
| 0x706a1    | 15        | 0.9%    |
| 0x506c9    | 15        | 0.9%    |
| 0x08701021 | 15        | 0.9%    |
| 0x0a50000c | 14        | 0.84%   |
| 0x0800820d | 13        | 0.78%   |
| 0x0600611a | 13        | 0.78%   |
| 0x06006118 | 13        | 0.78%   |
| 0x06000852 | 13        | 0.78%   |
| 0x30661    | 11        | 0.66%   |
| 0x20652    | 11        | 0.66%   |
| 0x10676    | 11        | 0.66%   |
| 0x08101016 | 11        | 0.66%   |
| 0x06006705 | 11        | 0.66%   |
| 0x0600063e | 10        | 0.6%    |
| 0x406c3    | 9         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 227       | 14.16%  |
| IvyBridge        | 112       | 6.99%   |
| SandyBridge      | 108       | 6.74%   |
| Haswell          | 100       | 6.24%   |
| K10              | 85        | 5.3%    |
| Penryn           | 80        | 4.99%   |
| Silvermont       | 77        | 4.8%    |
| Skylake          | 70        | 4.37%   |
| Zen+             | 62        | 3.87%   |
| Core             | 60        | 3.74%   |
| Piledriver       | 50        | 3.12%   |
| Excavator        | 44        | 2.74%   |
| Zen 2            | 40        | 2.5%    |
| TigerLake        | 39        | 2.43%   |
| Westmere         | 37        | 2.31%   |
| Zen 3            | 34        | 2.12%   |
| Zen              | 34        | 2.12%   |
| K8 Hammer        | 34        | 2.12%   |
| Bonnell          | 34        | 2.12%   |
| Broadwell        | 31        | 1.93%   |
| Steamroller      | 30        | 1.87%   |
| Icelake          | 29        | 1.81%   |
| Goldmont plus    | 28        | 1.75%   |
| CometLake        | 27        | 1.68%   |
| NetBurst         | 21        | 1.31%   |
| Unknown          | 19        | 1.19%   |
| Goldmont         | 17        | 1.06%   |
| K10 Llano        | 13        | 0.81%   |
| P6               | 11        | 0.69%   |
| Bulldozer        | 11        | 0.69%   |
| Jaguar           | 10        | 0.62%   |
| Nehalem          | 8         | 0.5%    |
| Bobcat           | 8         | 0.5%    |
| Puma             | 7         | 0.44%   |
| K8 & K10 hybrid  | 2         | 0.12%   |
| K6               | 2         | 0.12%   |
| Alderlake Hybrid | 2         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 954       | 54.08%  |
| AMD                              | 447       | 25.34%  |
| Nvidia                           | 338       | 19.16%  |
| Silicon Integrated Systems [SiS] | 12        | 0.68%   |
| VIA Technologies                 | 11        | 0.62%   |
| ATI Technologies                 | 2         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 97        | 5.32%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 3.95%   |
| Intel HD Graphics 620                                                                    | 56        | 3.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 43        | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 42        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 2.25%   |
| Intel UHD Graphics 620                                                                   | 36        | 1.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 1.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 34        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 32        | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 32        | 1.75%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 1.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 1.37%   |
| Intel HD Graphics 630                                                                    | 25        | 1.37%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 25        | 1.37%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 1.37%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 24        | 1.32%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 20        | 1.1%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 20        | 1.1%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 1.04%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 19        | 1.04%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 19        | 1.04%   |
| Intel HD Graphics 500                                                                    | 17        | 0.93%   |
| AMD Renoir                                                                               | 17        | 0.93%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 0.93%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 17        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 16        | 0.88%   |
| Intel HD Graphics 530                                                                    | 16        | 0.88%   |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 15        | 0.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 0.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 15        | 0.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 0.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 0.82%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 14        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 813       | 50.56%  |
| 1 x AMD        | 376       | 23.38%  |
| 1 x Nvidia     | 217       | 13.5%   |
| Intel + Nvidia | 98        | 6.09%   |
| Intel + AMD    | 37        | 2.3%    |
| 2 x AMD        | 20        | 1.24%   |
| AMD + Nvidia   | 19        | 1.18%   |
| 1 x SiS        | 12        | 0.75%   |
| 1 x VIA        | 11        | 0.68%   |
| Other          | 3         | 0.19%   |
| 2 x Nvidia     | 2         | 0.12%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1376      | 85.31%  |
| Proprietary | 151       | 9.36%   |
| Unknown     | 86        | 5.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 952       | 57.94%  |
| 0.01-0.5   | 218       | 13.27%  |
| 1.01-2.0   | 190       | 11.56%  |
| 0.51-1.0   | 132       | 8.03%   |
| 3.01-4.0   | 91        | 5.54%   |
| 7.01-8.0   | 30        | 1.83%   |
| 5.01-6.0   | 17        | 1.03%   |
| 2.01-3.0   | 7         | 0.43%   |
| 8.01-16.0  | 6         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 418       | 24.79%  |
| Goldstar                | 195       | 11.57%  |
| AU Optronics            | 179       | 10.62%  |
| Chimei Innolux          | 149       | 8.84%   |
| BOE                     | 138       | 8.19%   |
| LG Display              | 117       | 6.94%   |
| InfoVision              | 40        | 2.37%   |
| Dell                    | 33        | 1.96%   |
| ViewSonic               | 30        | 1.78%   |
| BenQ                    | 25        | 1.48%   |
| Philips                 | 23        | 1.36%   |
| Hitachi                 | 20        | 1.19%   |
| Lenovo                  | 19        | 1.13%   |
| SKY                     | 18        | 1.07%   |
| LG Electronics          | 18        | 1.07%   |
| Chi Mei Optoelectronics | 18        | 1.07%   |
| Hewlett-Packard         | 17        | 1.01%   |
| Apple                   | 14        | 0.83%   |
| PANDA                   | 12        | 0.71%   |
| LG Philips              | 11        | 0.65%   |
| AOC                     | 11        | 0.65%   |
| Unknown                 | 10        | 0.59%   |
| InnoLux Display         | 10        | 0.59%   |
| SAC                     | 9         | 0.53%   |
| HannStar                | 9         | 0.53%   |
| STA                     | 7         | 0.42%   |
| Sony                    | 7         | 0.42%   |
| Sharp                   | 7         | 0.42%   |
| CPT                     | 7         | 0.42%   |
| ASUSTek Computer        | 7         | 0.42%   |
| HKC                     | 6         | 0.36%   |
| Acer                    | 6         | 0.36%   |
| MStar                   | 5         | 0.3%    |
| UTV                     | 4         | 0.24%   |
| KDC                     | 4         | 0.24%   |
| GDH                     | 4         | 0.24%   |
| CDR                     | 4         | 0.24%   |
| Unknown (XXX)           | 3         | 0.18%   |
| SANYO                   | 3         | 0.18%   |
| RTK                     | 3         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 20        | 1.15%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 18        | 1.04%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 17        | 0.98%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 17        | 0.98%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 15        | 0.86%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 14        | 0.81%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 14        | 0.81%   |
| Hitachi HDMI HEC0088 1920x540                                        | 12        | 0.69%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 12        | 0.69%   |
| SKY SKYWORTH SKY0001 1920x1080 885x498mm 40.0-inch                   | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 11        | 0.63%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 10        | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch | 10        | 0.58%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 9         | 0.52%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 9         | 0.52%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 9         | 0.52%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 9         | 0.52%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 9         | 0.52%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 8         | 0.46%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 8         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 8         | 0.46%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 8         | 0.46%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 8         | 0.46%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 7         | 0.4%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 7         | 0.4%    |
| Goldstar E2340 GSM57C7 1920x1080 510x290mm 23.1-inch                 | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 7         | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 7         | 0.4%    |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch    | 6         | 0.35%   |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 6         | 0.35%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 6         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 6         | 0.35%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 6         | 0.35%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 6         | 0.35%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 6         | 0.35%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 6         | 0.35%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080                     | 5         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 585       | 35.82%  |
| 1366x768 (WXGA)    | 570       | 34.91%  |
| 3840x2160 (4K)     | 56        | 3.43%   |
| 1280x1024 (SXGA)   | 56        | 3.43%   |
| 1600x900 (HD+)     | 50        | 3.06%   |
| 1280x800 (WXGA)    | 46        | 2.82%   |
| 1680x1050 (WSXGA+) | 44        | 2.69%   |
| 1440x900 (WXGA+)   | 44        | 2.69%   |
| 1360x768           | 43        | 2.63%   |
| 1920x1200 (WUXGA)  | 23        | 1.41%   |
| 1920x540           | 17        | 1.04%   |
| 2560x1440 (QHD)    | 11        | 0.67%   |
| 1024x600           | 11        | 0.67%   |
| Unknown            | 10        | 0.61%   |
| 2560x1080          | 8         | 0.49%   |
| 1280x720 (HD)      | 7         | 0.43%   |
| 1024x768 (XGA)     | 6         | 0.37%   |
| 3200x1800 (QHD+)   | 5         | 0.31%   |
| 1152x864           | 4         | 0.24%   |
| 3840x2400          | 3         | 0.18%   |
| 3840x1080          | 3         | 0.18%   |
| 2560x1600          | 3         | 0.18%   |
| 2288x1287          | 3         | 0.18%   |
| 3456x2160          | 2         | 0.12%   |
| 3440x1440          | 2         | 0.12%   |
| 2160x1440          | 2         | 0.12%   |
| 2048x1152          | 2         | 0.12%   |
| 1280x960           | 2         | 0.12%   |
| 4093x4093          | 1         | 0.06%   |
| 3840x1100          | 1         | 0.06%   |
| 3286x1080          | 1         | 0.06%   |
| 3280x1080          | 1         | 0.06%   |
| 3046x1050          | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2880x1800          | 1         | 0.06%   |
| 2736x1824          | 1         | 0.06%   |
| 2646x1024          | 1         | 0.06%   |
| 2560x2880          | 1         | 0.06%   |
| 2048x1536          | 1         | 0.06%   |
| 1792x1344          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 453       | 26.51%  |
| 14      | 173       | 10.12%  |
| 13      | 158       | 9.25%   |
| 23      | 143       | 8.37%   |
| 21      | 138       | 8.07%   |
| 18      | 107       | 6.26%   |
| 17      | 58        | 3.39%   |
| Unknown | 57        | 3.34%   |
| 24      | 50        | 2.93%   |
| 19      | 48        | 2.81%   |
| 20      | 41        | 2.4%    |
| 27      | 39        | 2.28%   |
| 40      | 34        | 1.99%   |
| 10      | 26        | 1.52%   |
| 22      | 20        | 1.17%   |
| 31      | 16        | 0.94%   |
| 16      | 16        | 0.94%   |
| 12      | 16        | 0.94%   |
| 84      | 15        | 0.88%   |
| 48      | 15        | 0.88%   |
| 52      | 14        | 0.82%   |
| 11      | 14        | 0.82%   |
| 46      | 11        | 0.64%   |
| 32      | 9         | 0.53%   |
| 34      | 8         | 0.47%   |
| 54      | 6         | 0.35%   |
| 142     | 3         | 0.18%   |
| 39      | 3         | 0.18%   |
| 26      | 3         | 0.18%   |
| 72      | 2         | 0.12%   |
| 55      | 2         | 0.12%   |
| 47      | 2         | 0.12%   |
| 25      | 2         | 0.12%   |
| 64      | 1         | 0.06%   |
| 58      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |
| 41      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 30      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 759       | 45.04%  |
| 401-500        | 339       | 20.12%  |
| 501-600        | 219       | 13%     |
| 201-300        | 96        | 5.7%    |
| 351-400        | 62        | 3.68%   |
| Unknown        | 57        | 3.38%   |
| 1001-1500      | 52        | 3.09%   |
| 801-900        | 38        | 2.26%   |
| 601-700        | 23        | 1.36%   |
| 701-800        | 17        | 1.01%   |
| 1501-2000      | 17        | 1.01%   |
| More than 2000 | 3         | 0.18%   |
| 901-1000       | 3         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1222      | 79.97%  |
| 16/10   | 145       | 9.49%   |
| Unknown | 49        | 3.21%   |
| 5/4     | 39        | 2.55%   |
| 4/3     | 36        | 2.36%   |
| 1.96    | 12        | 0.79%   |
| 3/2     | 9         | 0.59%   |
| 21/9    | 9         | 0.59%   |
| 1.00    | 3         | 0.2%    |
| 32/9    | 2         | 0.13%   |
| 3.40    | 1         | 0.07%   |
| 0.89    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 435       | 25.72%  |
| 201-250        | 309       | 18.27%  |
| 81-90          | 301       | 17.8%   |
| 141-150        | 130       | 7.69%   |
| 151-200        | 115       | 6.8%    |
| 501-1000       | 66        | 3.9%    |
| Unknown        | 57        | 3.37%   |
| More than 1000 | 45        | 2.66%   |
| 301-350        | 41        | 2.42%   |
| 351-500        | 34        | 2.01%   |
| 71-80          | 32        | 1.89%   |
| 121-130        | 30        | 1.77%   |
| 41-50          | 26        | 1.54%   |
| 111-120        | 26        | 1.54%   |
| 51-60          | 15        | 0.89%   |
| 61-70          | 11        | 0.65%   |
| 251-300        | 9         | 0.53%   |
| 131-140        | 5         | 0.3%    |
| 91-100         | 4         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 655       | 39.46%  |
| 51-100        | 563       | 33.92%  |
| 121-160       | 258       | 15.54%  |
| 1-50          | 83        | 5%      |
| Unknown       | 57        | 3.43%   |
| 161-240       | 29        | 1.75%   |
| More than 240 | 15        | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1323      | 80.67%  |
| 2     | 237       | 14.45%  |
| 0     | 70        | 4.27%   |
| 3     | 10        | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1059      | 44.61%  |
| Intel                                 | 484       | 20.39%  |
| Qualcomm Atheros                      | 300       | 12.64%  |
| Broadcom                              | 78        | 3.29%   |
| TP-Link                               | 64        | 2.7%    |
| Nvidia                                | 63        | 2.65%   |
| Ralink Technology                     | 40        | 1.68%   |
| Marvell Technology Group              | 30        | 1.26%   |
| Broadcom Limited                      | 30        | 1.26%   |
| Qualcomm Atheros Communications       | 28        | 1.18%   |
| Ralink                                | 22        | 0.93%   |
| JMicron Technology                    | 22        | 0.93%   |
| VIA Technologies                      | 19        | 0.8%    |
| Samsung Electronics                   | 19        | 0.8%    |
| Silicon Integrated Systems [SiS]      | 15        | 0.63%   |
| MediaTek                              | 13        | 0.55%   |
| Motorola PCS                          | 12        | 0.51%   |
| Microsoft                             | 9         | 0.38%   |
| ASIX Electronics                      | 6         | 0.25%   |
| NetGear                               | 4         | 0.17%   |
| D-Link System                         | 4         | 0.17%   |
| Ericsson Business Mobile Networks     | 3         | 0.13%   |
| DisplayLink                           | 3         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.13%   |
| 3Com                                  | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.08%   |
| Xiaomi                                | 2         | 0.08%   |
| T & A Mobile Phones                   | 2         | 0.08%   |
| Sundance Technology Inc / IC Plus     | 2         | 0.08%   |
| Standard Microsystems                 | 2         | 0.08%   |
| Ovislink                              | 2         | 0.08%   |
| Linksys                               | 2         | 0.08%   |
| ICS Advent                            | 2         | 0.08%   |
| Encore Electronics                    | 2         | 0.08%   |
| Davicom Semiconductor                 | 2         | 0.08%   |
| D-Link                                | 2         | 0.08%   |
| Arduino SA                            | 2         | 0.08%   |
| ZyDAS                                 | 1         | 0.04%   |
| Unknown                               | 1         | 0.04%   |
| Spreadtrum Communications             | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 723       | 25.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 164       | 5.86%   |
| Nvidia MCP61 Ethernet                                             | 56        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 55        | 1.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 45        | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 41        | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 40        | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 39        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 38        | 1.36%   |
| Intel Wireless 3160                                               | 31        | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 30        | 1.07%   |
| Intel Wi-Fi 6 AX200                                               | 30        | 1.07%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 29        | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 27        | 0.96%   |
| Qualcomm Atheros AR9271 802.11n                                   | 26        | 0.93%   |
| Intel Wireless 3165                                               | 25        | 0.89%   |
| Intel Wi-Fi 6 AX201                                               | 25        | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 24        | 0.86%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 23        | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.82%   |
| Ralink MT7601U Wireless Adapter                                   | 22        | 0.79%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 21        | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 0.75%   |
| Intel Wireless 8265 / 8275                                        | 21        | 0.75%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 20        | 0.71%   |
| Intel Wireless 7260                                               | 19        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 19        | 0.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 18        | 0.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 18        | 0.64%   |
| Intel I211 Gigabit Network Connection                             | 17        | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 16        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 16        | 0.57%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15        | 0.54%   |
| Intel Wireless 7265                                               | 15        | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 15        | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 380       | 30.69%  |
| Realtek Semiconductor                 | 339       | 27.38%  |
| Qualcomm Atheros                      | 248       | 20.03%  |
| Broadcom                              | 65        | 5.25%   |
| TP-Link                               | 55        | 4.44%   |
| Ralink Technology                     | 40        | 3.23%   |
| Qualcomm Atheros Communications       | 28        | 2.26%   |
| Ralink                                | 22        | 1.78%   |
| Broadcom Limited                      | 18        | 1.45%   |
| Microsoft                             | 8         | 0.65%   |
| MediaTek                              | 7         | 0.57%   |
| NetGear                               | 4         | 0.32%   |
| D-Link System                         | 4         | 0.32%   |
| Marvell Technology Group              | 3         | 0.24%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.24%   |
| Ovislink                              | 2         | 0.16%   |
| Linksys                               | 2         | 0.16%   |
| Encore Electronics                    | 2         | 0.16%   |
| D-Link                                | 2         | 0.16%   |
| ZyDAS                                 | 1         | 0.08%   |
| Sierra Wireless                       | 1         | 0.08%   |
| Samsung Electronics                   | 1         | 0.08%   |
| Ericsson Business Mobile Networks     | 1         | 0.08%   |
| Dell                                  | 1         | 0.08%   |
| Cisco Aironet Wireless Communications | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 55        | 4.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 45        | 3.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 3.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 39        | 3.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 38        | 3.04%   |
| Intel Wireless 3160                                                     | 31        | 2.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 30        | 2.4%    |
| Intel Wi-Fi 6 AX200                                                     | 30        | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 29        | 2.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 27        | 2.16%   |
| Qualcomm Atheros AR9271 802.11n                                         | 26        | 2.08%   |
| Intel Wireless 3165                                                     | 25        | 2%      |
| Intel Wi-Fi 6 AX201                                                     | 25        | 2%      |
| Realtek RTL8723DE Wireless Network Adapter                              | 23        | 1.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 1.84%   |
| Ralink MT7601U Wireless Adapter                                         | 22        | 1.76%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 21        | 1.68%   |
| Intel Wireless 8265 / 8275                                              | 21        | 1.68%   |
| Intel Wireless 7260                                                     | 19        | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 19        | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 18        | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 16        | 1.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 16        | 1.28%   |
| Intel Wireless 7265                                                     | 15        | 1.2%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 15        | 1.2%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 14        | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 14        | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 13        | 1.04%   |
| Intel Wireless 8260                                                     | 13        | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 1.04%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 12        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 0.96%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 11        | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 11        | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 11        | 0.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 10        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 944       | 62.02%  |
| Intel                             | 211       | 13.86%  |
| Qualcomm Atheros                  | 110       | 7.23%   |
| Nvidia                            | 63        | 4.14%   |
| Marvell Technology Group          | 27        | 1.77%   |
| JMicron Technology                | 22        | 1.45%   |
| Broadcom                          | 21        | 1.38%   |
| VIA Technologies                  | 19        | 1.25%   |
| Samsung Electronics               | 18        | 1.18%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.99%   |
| Broadcom Limited                  | 12        | 0.79%   |
| TP-Link                           | 10        | 0.66%   |
| Motorola PCS                      | 10        | 0.66%   |
| MediaTek                          | 6         | 0.39%   |
| ASIX Electronics                  | 6         | 0.39%   |
| DisplayLink                       | 3         | 0.2%    |
| 3Com                              | 3         | 0.2%    |
| Xiaomi                            | 2         | 0.13%   |
| T & A Mobile Phones               | 2         | 0.13%   |
| Sundance Technology Inc / IC Plus | 2         | 0.13%   |
| Standard Microsystems             | 2         | 0.13%   |
| ICS Advent                        | 2         | 0.13%   |
| Davicom Semiconductor             | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.07%   |
| Spreadtrum Communications         | 1         | 0.07%   |
| Microsoft                         | 1         | 0.07%   |
| Macronix [MXIC]                   | 1         | 0.07%   |
| LG Electronics                    | 1         | 0.07%   |
| Lenovo                            | 1         | 0.07%   |
| Huawei Technologies               | 1         | 0.07%   |
| Digitech Systems                  | 1         | 0.07%   |
| Aquantia                          | 1         | 0.07%   |
| 3DSP                              | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 723       | 47.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 164       | 10.68%  |
| Nvidia MCP61 Ethernet                                             | 56        | 3.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 1.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 24        | 1.56%   |
| Intel Ethernet Connection (2) I219-V                              | 22        | 1.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 1.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 20        | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 19        | 1.24%   |
| Intel I211 Gigabit Network Connection                             | 17        | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 1.04%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15        | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.85%   |
| Intel Ethernet Controller I225-V                                  | 13        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.85%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 12        | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 0.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 0.72%   |
| Motorola PCS moto g(8) plus                                       | 10        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.65%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.59%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 6         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.39%   |
| Intel PRO/100 VE Network Connection                               | 6         | 0.39%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.39%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 0.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.33%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 5         | 0.33%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 5         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1435      | 54.5%   |
| WiFi     | 1182      | 44.89%  |
| Modem    | 13        | 0.49%   |
| Unknown  | 3         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 971       | 59.35%  |
| Ethernet | 664       | 40.59%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 851       | 52.89%  |
| 1     | 692       | 43.01%  |
| 0     | 43        | 2.67%   |
| 3     | 21        | 1.31%   |
| 32    | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1431      | 88.17%  |
| Yes  | 192       | 11.83%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 301       | 40.57%  |
| Realtek Semiconductor           | 138       | 18.6%   |
| Qualcomm Atheros Communications | 61        | 8.22%   |
| Cambridge Silicon Radio         | 44        | 5.93%   |
| IMC Networks                    | 38        | 5.12%   |
| Broadcom                        | 37        | 4.99%   |
| Lite-On Technology              | 32        | 4.31%   |
| Foxconn / Hon Hai               | 19        | 2.56%   |
| Dell                            | 13        | 1.75%   |
| Apple                           | 13        | 1.75%   |
| Toshiba                         | 9         | 1.21%   |
| Ralink                          | 7         | 0.94%   |
| ASUSTek Computer                | 7         | 0.94%   |
| TP-Link                         | 3         | 0.4%    |
| Integrated System Solution      | 3         | 0.4%    |
| Hewlett-Packard                 | 3         | 0.4%    |
| USI                             | 2         | 0.27%   |
| Qcom                            | 2         | 0.27%   |
| Marvell Semiconductor           | 2         | 0.27%   |
| Syntek                          | 1         | 0.13%   |
| Roper                           | 1         | 0.13%   |
| Realtek                         | 1         | 0.13%   |
| Logitech                        | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |
| Edimax Technology               | 1         | 0.13%   |
| Conwise Technology              | 1         | 0.13%   |
| Alps Electric                   | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 128       | 17.25%  |
| Realtek Bluetooth Radio                                                             | 76        | 10.24%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 49        | 6.6%    |
| Intel AX201 Bluetooth                                                               | 45        | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 44        | 5.93%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 39        | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 31        | 4.18%   |
| Intel AX200 Bluetooth                                                               | 31        | 4.18%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 18        | 2.43%   |
| Realtek RTL8723B Bluetooth                                                          | 17        | 2.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 15        | 2.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 13        | 1.75%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 1.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.48%   |
| Lite-On Bluetooth Device                                                            | 11        | 1.48%   |
| IMC Networks Bluetooth Device                                                       | 10        | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 8         | 1.08%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.08%   |
| Ralink RT3290 Bluetooth                                                             | 7         | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 0.94%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 7         | 0.94%   |
| Toshiba Bluetooth USB Host Controller                                               | 6         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 0.81%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 6         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.81%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 0.81%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 0.81%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 5         | 0.67%   |
| IMC Networks Wireless_Device                                                        | 5         | 0.67%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 0.67%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.54%   |
| Intel AX210 Bluetooth                                                               | 4         | 0.54%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.54%   |
| Apple Bluetooth HCI                                                                 | 4         | 0.54%   |
| TP-Link TPuLink UB500 Adapter                                                       | 3         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.4%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.4%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 3         | 0.4%    |
| Broadcom Bluetooth 2.1 Device                                                       | 3         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1069      | 53.75%  |
| AMD                                             | 470       | 23.63%  |
| Nvidia                                          | 255       | 12.82%  |
| Logitech                                        | 33        | 1.66%   |
| C-Media Electronics                             | 29        | 1.46%   |
| VIA Technologies                                | 17        | 0.85%   |
| Silicon Integrated Systems [SiS]                | 15        | 0.75%   |
| Kingston Technology                             | 13        | 0.65%   |
| Generalplus Technology                          | 7         | 0.35%   |
| Creative Labs                                   | 7         | 0.35%   |
| Plantronics                                     | 6         | 0.3%    |
| Focusrite-Novation                              | 6         | 0.3%    |
| Texas Instruments                               | 5         | 0.25%   |
| M-Audio                                         | 4         | 0.2%    |
| GN Netcom                                       | 4         | 0.2%    |
| Samson Technologies                             | 3         | 0.15%   |
| Fry's Electronics                               | 3         | 0.15%   |
| ESI Audiotechnik                                | 3         | 0.15%   |
| Elite Silicon                                   | 3         | 0.15%   |
| ASUSTek Computer                                | 3         | 0.15%   |
| Astro Gaming                                    | 3         | 0.15%   |
| Realtek Semiconductor                           | 2         | 0.1%    |
| Razer USA                                       | 2         | 0.1%    |
| Microsoft                                       | 2         | 0.1%    |
| Licensed by Sony Computer Entertainment America | 2         | 0.1%    |
| Ensoniq                                         | 2         | 0.1%    |
| Creative Technology                             | 2         | 0.1%    |
| BEHRINGER International                         | 2         | 0.1%    |
| ATI Technologies                                | 2         | 0.1%    |
| Yamaha                                          | 1         | 0.05%   |
| TEAC                                            | 1         | 0.05%   |
| Pro-Ject                                        | 1         | 0.05%   |
| Micro Star International                        | 1         | 0.05%   |
| Lenovo                                          | 1         | 0.05%   |
| JMTek                                           | 1         | 0.05%   |
| Holtek Semiconductor                            | 1         | 0.05%   |
| Hewlett-Packard                                 | 1         | 0.05%   |
| Dell                                            | 1         | 0.05%   |
| Corsair                                         | 1         | 0.05%   |
| Cirrus Logic                                    | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 135       | 5.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 123       | 5.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 114       | 4.7%    |
| AMD FCH Azalia Controller                                                  | 101       | 4.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 100       | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 95        | 3.92%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 78        | 3.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 68        | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 61        | 2.52%   |
| Nvidia MCP61 High Definition Audio                                         | 59        | 2.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 49        | 2.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48        | 1.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 44        | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 41        | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 40        | 1.65%   |
| AMD Kabini HDMI/DP Audio                                                   | 40        | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 39        | 1.61%   |
| AMD Starship/Matisse HD Audio Controller                                   | 37        | 1.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 37        | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 37        | 1.53%   |
| Intel Broadwell-U Audio Controller                                         | 31        | 1.28%   |
| Intel 200 Series PCH HD Audio                                              | 29        | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 28        | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 28        | 1.15%   |
| AMD Trinity HDMI Audio Controller                                          | 28        | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 28        | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 27        | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 1.11%   |
| Intel 8 Series HD Audio Controller                                         | 27        | 1.11%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 27        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 26        | 1.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 26        | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 25        | 1.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 25        | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 24        | 0.99%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 24        | 0.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 0.95%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 21        | 0.87%   |
| Nvidia High Definition Audio Controller                                    | 20        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 20        | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Kingston                                         | 225       | 23.81%  |
| Samsung Electronics                              | 166       | 17.57%  |
| SK hynix                                         | 116       | 12.28%  |
| Unknown                                          | 114       | 12.06%  |
| Micron Technology                                | 49        | 5.19%   |
| Crucial                                          | 48        | 5.08%   |
| A-DATA Technology                                | 34        | 3.6%    |
| Corsair                                          | 32        | 3.39%   |
| Magnum Tech                                      | 13        | 1.38%   |
| Nanya Technology                                 | 12        | 1.27%   |
| Unknown (ABCD)                                   | 11        | 1.16%   |
| Novatech                                         | 10        | 1.06%   |
| G.Skill                                          | 10        | 1.06%   |
| Goldkey                                          | 9         | 0.95%   |
| Elpida                                           | 9         | 0.95%   |
| Avant                                            | 8         | 0.85%   |
| Patriot                                          | 7         | 0.74%   |
| Ramaxel Technology                               | 6         | 0.63%   |
| Unknown                                          | 6         | 0.63%   |
| Super Talent                                     | 5         | 0.53%   |
| Memox                                            | 5         | 0.53%   |
| Hewlett-Packard                                  | 5         | 0.53%   |
| Transcend                                        | 4         | 0.42%   |
| Team                                             | 4         | 0.42%   |
| Saikano                                          | 4         | 0.42%   |
| Neo Forza                                        | 3         | 0.32%   |
| CSX                                              | 3         | 0.32%   |
| 48spaces                                         | 3         | 0.32%   |
| Teikon                                           | 2         | 0.21%   |
| Ramos Technology                                 | 2         | 0.21%   |
| PNY                                              | 2         | 0.21%   |
| Apacer                                           | 2         | 0.21%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.11%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.11%   |
| Unknown (07D5)                                   | 1         | 0.11%   |
| Thermaltake                                      | 1         | 0.11%   |
| Qimonda                                          | 1         | 0.11%   |
| OLOY                                             | 1         | 0.11%   |
| Mushkin                                          | 1         | 0.11%   |
| Kreton                                           | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 1.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 12        | 1.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.17%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 12        | 1.17%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 11        | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.08%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.88%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 9         | 0.88%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 9         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.78%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 8         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.68%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.59%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 6         | 0.59%   |
| Unknown                                                          | 6         | 0.59%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 5         | 0.49%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.49%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 0.49%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s         | 5         | 0.49%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 4         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 4         | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.39%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                      | 4         | 0.39%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s            | 4         | 0.39%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s              | 4         | 0.39%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 1866MT/s                | 4         | 0.39%   |
| Kingston RAM KHX1600C10D3/ 4GB DIMM DDR3 1600MT/s                | 4         | 0.39%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 4         | 0.39%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.39%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s           | 4         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 338       | 42.78%  |
| DDR3    | 303       | 38.35%  |
| DDR2    | 45        | 5.7%    |
| Unknown | 38        | 4.81%   |
| LPDDR4  | 23        | 2.91%   |
| SDRAM   | 20        | 2.53%   |
| LPDDR3  | 10        | 1.27%   |
| DDR     | 8         | 1.01%   |
| DRAM    | 4         | 0.51%   |
| DDR5    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 441       | 55.75%  |
| DIMM         | 312       | 39.44%  |
| Row Of Chips | 35        | 4.42%   |
| Chip         | 2         | 0.25%   |
| Unknown      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 341       | 38.19%  |
| 4096  | 278       | 31.13%  |
| 2048  | 136       | 15.23%  |
| 16384 | 87        | 9.74%   |
| 1024  | 33        | 3.7%    |
| 32768 | 13        | 1.46%   |
| 512   | 4         | 0.45%   |
| 6144  | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 186       | 20.64%  |
| 2667    | 135       | 14.98%  |
| 3200    | 105       | 11.65%  |
| 1333    | 97        | 10.77%  |
| 2400    | 75        | 8.32%   |
| 2133    | 42        | 4.66%   |
| Unknown | 31        | 3.44%   |
| 1334    | 30        | 3.33%   |
| 667     | 24        | 2.66%   |
| 3266    | 16        | 1.78%   |
| 3600    | 13        | 1.44%   |
| 800     | 13        | 1.44%   |
| 3400    | 12        | 1.33%   |
| 2666    | 11        | 1.22%   |
| 533     | 11        | 1.22%   |
| 1066    | 10        | 1.11%   |
| 3466    | 9         | 1%      |
| 1866    | 9         | 1%      |
| 1067    | 8         | 0.89%   |
| 3000    | 7         | 0.78%   |
| 333     | 7         | 0.78%   |
| 4199    | 5         | 0.55%   |
| 2933    | 5         | 0.55%   |
| 1867    | 5         | 0.55%   |
| 400     | 5         | 0.55%   |
| 4267    | 4         | 0.44%   |
| 975     | 4         | 0.44%   |
| 2048    | 3         | 0.33%   |
| 3151    | 2         | 0.22%   |
| 3007    | 2         | 0.22%   |
| 2800    | 2         | 0.22%   |
| 8400    | 1         | 0.11%   |
| 4800    | 1         | 0.11%   |
| 4266    | 1         | 0.11%   |
| 3866    | 1         | 0.11%   |
| 3733    | 1         | 0.11%   |
| 3533    | 1         | 0.11%   |
| 3500    | 1         | 0.11%   |
| 3334    | 1         | 0.11%   |
| 3100    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 24        | 46.15%  |
| Brother Industries  | 16        | 30.77%  |
| Seiko Epson         | 4         | 7.69%   |
| Samsung Electronics | 3         | 5.77%   |
| Ricoh               | 1         | 1.92%   |
| QinHeng Electronics | 1         | 1.92%   |
| Pantum              | 1         | 1.92%   |
| NXP Semiconductors  | 1         | 1.92%   |
| Graphtec America    | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Brother HL-1200 series                        | 4         | 7.69%   |
| Brother HL-1110 series                        | 4         | 7.69%   |
| HP LaserJet Professional P1102w               | 3         | 5.77%   |
| HP LaserJet Professional P 1102w              | 3         | 5.77%   |
| Brother HL-1210W series                       | 3         | 5.77%   |
| Samsung M2020 Series                          | 2         | 3.85%   |
| HP LaserJet P1006                             | 2         | 3.85%   |
| HP LaserJet P1005                             | 2         | 3.85%   |
| HP Ink Tank 110 series                        | 2         | 3.85%   |
| Brother HL-2130 series                        | 2         | 3.85%   |
| Seiko Epson XP-243 245 247 Series             | 1         | 1.92%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.92%   |
| Seiko Epson L355 Series                       | 1         | 1.92%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.92%   |
| Samsung Xerox Phaser 3117 Laser Printer       | 1         | 1.92%   |
| Ricoh Printing Support                        | 1         | 1.92%   |
| QinHeng CH340S                                | 1         | 1.92%   |
| Pantum P2500W series                          | 1         | 1.92%   |
| NXP Semiconductors Printer-80                 | 1         | 1.92%   |
| HP PSC 1400                                   | 1         | 1.92%   |
| HP Laserjet P1505                             | 1         | 1.92%   |
| HP LaserJet 3050                              | 1         | 1.92%   |
| HP LaserJet 1020                              | 1         | 1.92%   |
| HP Ink Tank Wireless 410 series               | 1         | 1.92%   |
| HP DeskJet F4100 Printer series               | 1         | 1.92%   |
| HP DeskJet F300 series                        | 1         | 1.92%   |
| HP DeskJet 3630 series                        | 1         | 1.92%   |
| HP Deskjet 3050 J610 series                   | 1         | 1.92%   |
| HP DeskJet 2620 All-in-One Printer            | 1         | 1.92%   |
| HP Deskjet 2050 J510                          | 1         | 1.92%   |
| HP Color LaserJet Pro M478f-9f                | 1         | 1.92%   |
| Graphtec America Graphtec Printer             | 1         | 1.92%   |
| Brother DCP-7055 scanner/printer              | 1         | 1.92%   |
| Brother DCP-1610NW                            | 1         | 1.92%   |
| Brother DCP-1600                              | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 202       | 21.49%  |
| Acer                                   | 89        | 9.47%   |
| IMC Networks                           | 83        | 8.83%   |
| Realtek Semiconductor                  | 75        | 7.98%   |
| Microdia                               | 69        | 7.34%   |
| Logitech                               | 38        | 4.04%   |
| Sunplus Innovation Technology          | 37        | 3.94%   |
| Syntek                                 | 34        | 3.62%   |
| Alcor Micro                            | 32        | 3.4%    |
| Cheng Uei Precision Industry (Foxlink) | 29        | 3.09%   |
| Suyin                                  | 28        | 2.98%   |
| Silicon Motion                         | 27        | 2.87%   |
| Quanta                                 | 27        | 2.87%   |
| Samsung Electronics                    | 17        | 1.81%   |
| Apple                                  | 17        | 1.81%   |
| Z-Star Microelectronics                | 14        | 1.49%   |
| Lite-On Technology                     | 12        | 1.28%   |
| Luxvisions Innotech Limited            | 11        | 1.17%   |
| KYE Systems (Mouse Systems)            | 11        | 1.17%   |
| Ricoh                                  | 10        | 1.06%   |
| Generalplus Technology                 | 9         | 0.96%   |
| Microsoft                              | 7         | 0.74%   |
| OmniVision Technologies                | 6         | 0.64%   |
| Jieli Technology                       | 6         | 0.64%   |
| icSpring                               | 4         | 0.43%   |
| GEMBIRD                                | 4         | 0.43%   |
| ALi                                    | 4         | 0.43%   |
| SunplusIT                              | 3         | 0.32%   |
| Sonix Technology                       | 3         | 0.32%   |
| MacroSilicon                           | 3         | 0.32%   |
| Lenovo                                 | 3         | 0.32%   |
| Cubeternet                             | 3         | 0.32%   |
| Razer USA                              | 2         | 0.21%   |
| Pixart Imaging                         | 2         | 0.21%   |
| Intel                                  | 2         | 0.21%   |
| Importek                               | 2         | 0.21%   |
| Genesys Logic                          | 2         | 0.21%   |
| Aveo Technology                        | 2         | 0.21%   |
| ARC International                      | 2         | 0.21%   |
| Y Media                                | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 Camera                                         | 33        | 3.49%   |
| Acer Integrated Camera                                         | 31        | 3.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 29        | 3.07%   |
| Microdia Integrated_Webcam_HD                                  | 22        | 2.33%   |
| Realtek Integrated_Webcam_HD                                   | 21        | 2.22%   |
| IMC Networks Integrated Camera                                 | 21        | 2.22%   |
| Alcor Micro USB Camera                                         | 20        | 2.11%   |
| Chicony Integrated Camera                                      | 18        | 1.9%    |
| Samsung Galaxy A5 (MTP)                                        | 16        | 1.69%   |
| Chicony USB2.0 Camera                                          | 14        | 1.48%   |
| Chicony Lenovo EasyCamera                                      | 14        | 1.48%   |
| Logitech Webcam C270                                           | 13        | 1.37%   |
| Syntek Integrated Camera                                       | 12        | 1.27%   |
| Chicony HD Webcam                                              | 12        | 1.27%   |
| Sunplus Integrated_Webcam_HD                                   | 11        | 1.16%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 1.06%   |
| Chicony TOSHIBA Web Camera - HD                                | 10        | 1.06%   |
| Realtek USB Camera                                             | 9         | 0.95%   |
| Luxvisions Innotech Limited Integrated Camera                  | 9         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 9         | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 9         | 0.95%   |
| Acer Lenovo EasyCamera                                         | 9         | 0.95%   |
| Acer HD Webcam                                                 | 9         | 0.95%   |
| Acer BisonCam, NB Pro                                          | 9         | 0.95%   |
| Logitech C922 Pro Stream Webcam                                | 8         | 0.85%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 8         | 0.85%   |
| Acer SunplusIT Integrated Camera                               | 8         | 0.85%   |
| Microdia Webcam Vitade AF                                      | 7         | 0.74%   |
| Chicony Integrated Camera (1280x720@30)                        | 7         | 0.74%   |
| Chicony HP Wide Vision HD Camera                               | 7         | 0.74%   |
| Alcor Micro USB 2.0 PC Camera                                  | 7         | 0.74%   |
| Acer USB Camera                                                | 7         | 0.74%   |
| Z-Star Webcam                                                  | 6         | 0.63%   |
| Syntek EasyCamera                                              | 6         | 0.63%   |
| Sunplus Asus Webcam                                            | 6         | 0.63%   |
| Silicon Motion WebCam SC-0311139N                              | 6         | 0.63%   |
| Jieli USB PHY 2.0                                              | 6         | 0.63%   |
| Generalplus GENERAL WEBCAM                                     | 6         | 0.63%   |
| Chicony USB2.0 HD UVC WebCam                                   | 6         | 0.63%   |
| Chicony HP Webcam                                              | 6         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 41        | 36.28%  |
| Validity Sensors           | 30        | 26.55%  |
| Shenzhen Goodix Technology | 22        | 19.47%  |
| Elan Microelectronics      | 6         | 5.31%   |
| AuthenTec                  | 6         | 5.31%   |
| Upek                       | 4         | 3.54%   |
| LighTuning Technology      | 2         | 1.77%   |
| STMicroelectronics         | 1         | 0.88%   |
| Focal-systems.Corp         | 1         | 0.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 15.93%  |
| Shenzhen Goodix  FingerPrint Device                                        | 15        | 13.27%  |
| Synaptics  WBDI                                                            | 12        | 10.62%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 6.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 5.31%   |
| Unknown                                                                    | 6         | 5.31%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.54%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.54%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.54%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.54%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.65%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.77%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.77%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.77%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.77%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 1.77%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.77%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.77%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.88%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.88%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.88%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.88%   |
| AuthenTec AES2810                                                          | 1         | 0.88%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 60.61%  |
| Upek        | 9         | 27.27%  |
| Lenovo      | 2         | 6.06%   |
| O2 Micro    | 1         | 3.03%   |
| Alcor Micro | 1         | 3.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 27.27%  |
| Broadcom 58200                                                               | 7         | 21.21%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 18.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 12.12%  |
| Broadcom 5880                                                                | 3         | 9.09%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.03%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1237      | 75.84%  |
| 1     | 342       | 20.97%  |
| 2     | 44        | 2.7%    |
| 3     | 5         | 0.31%   |
| 8     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 132       | 29.53%  |
| Fingerprint reader       | 112       | 25.06%  |
| Net/wireless             | 74        | 16.55%  |
| Chipcard                 | 31        | 6.94%   |
| Camera                   | 20        | 4.47%   |
| Multimedia controller    | 14        | 3.13%   |
| Bluetooth                | 14        | 3.13%   |
| Communication controller | 13        | 2.91%   |
| Sound                    | 9         | 2.01%   |
| Net/ethernet             | 9         | 2.01%   |
| Modem                    | 5         | 1.12%   |
| Network                  | 4         | 0.89%   |
| Unassigned class         | 2         | 0.45%   |
| Flash memory             | 2         | 0.45%   |
| Firewire controller      | 2         | 0.45%   |
| Card reader              | 2         | 0.45%   |
| Storage/ide              | 1         | 0.22%   |
| Dvb card                 | 1         | 0.22%   |


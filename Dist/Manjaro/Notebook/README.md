Manjaro - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Manjaro.

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

Total: 5474

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| ASUSTek       | UX530UQ                     | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| WOOKING       | X16                         | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| Google        | Chell                       | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| Acer          | Aspire A314-36M             | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| Dell          | Latitude 5530               | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| HONOR         | HYM-WXX                     | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| Dell          | Latitude 3340               | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| Dell          | XPS 15 9530                 | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b34bb8b33a](https://linux-hardware.org/?probe=b34bb8b33a) | Jun 02, 2023 |
| MSI           | U200                        | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [d25f4736b7](https://linux-hardware.org/?probe=d25f4736b7) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Acer          | Aspire 3830TG               | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| Dell          | Precision 3550              | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP            | Pavilion dv4                | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Acer          | Aspire A315-59              | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| HP            | Laptop 15-ef2xxx            | [2139621391](https://linux-hardware.org/?probe=2139621391) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Dell          | Vostro 1015                 | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| Apple         | MacBookPro8,1               | [d8aa236e2d](https://linux-hardware.org/?probe=d8aa236e2d) | May 28, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| Unknown       | Unknown                     | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| Dell          | Vostro 1015                 | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| HP            | EliteBook 2570p             | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Getac         | V110G3                      | [4a80145aac](https://linux-hardware.org/?probe=4a80145aac) | May 21, 2023 |
| HP            | Laptop 17-cn2xxx            | [953734fc80](https://linux-hardware.org/?probe=953734fc80) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| Getac         | V110G3                      | [1b04290d0e](https://linux-hardware.org/?probe=1b04290d0e) | May 19, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Dell          | Inspiron 15-7568            | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Acer          | Swift SFA16-41              | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [0770462dab](https://linux-hardware.org/?probe=0770462dab) | May 15, 2023 |
| Dell          | Inspiron 3542               | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| HP            | Laptop 15-ef2xxx            | [f732fbd488](https://linux-hardware.org/?probe=f732fbd488) | May 14, 2023 |
| Dell          | XPS 15 9570                 | [59214a0e61](https://linux-hardware.org/?probe=59214a0e61) | May 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Dell          | Vostro 5471                 | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| HP            | Pavilion dv6                | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| Schenker      | VISION (E22)                | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| MSI           | GT70 2PC                    | [c98c889dbf](https://linux-hardware.org/?probe=c98c889dbf) | May 11, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Dell          | Precision 7520              | [184802dbab](https://linux-hardware.org/?probe=184802dbab) | May 11, 2023 |
| Itautec       | Infoway w7440               | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Dell          | Latitude E6440              | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57a74239f8](https://linux-hardware.org/?probe=57a74239f8) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [962ca6e507](https://linux-hardware.org/?probe=962ca6e507) | May 10, 2023 |
| Acer          | TravelMate P653-M           | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [69f4dd51d9](https://linux-hardware.org/?probe=69f4dd51d9) | May 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Dell          | XPS 15 9520                 | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Toshiba       | Satellite L855              | [5e78ff90cc](https://linux-hardware.org/?probe=5e78ff90cc) | May 08, 2023 |
| TUXEDO        | N24_25BU                    | [9cd4e499ae](https://linux-hardware.org/?probe=9cd4e499ae) | May 07, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Dell          | Inspiron 5585               | [f838e48bd3](https://linux-hardware.org/?probe=f838e48bd3) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| HP            | EliteBook 840 G6            | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| Gigabyte      | G5 MD                       | [7ad914a8a9](https://linux-hardware.org/?probe=7ad914a8a9) | May 06, 2023 |
| Acer          | Nitro AN517-54              | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [9b843f40a1](https://linux-hardware.org/?probe=9b843f40a1) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| HP            | Laptop 15-dy1xxx            | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| Dell          | XPS 15 9510                 | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | Compaq Presario C700        | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Acer          | Swift SF114-32              | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Acer          | Nitro AN517-54              | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| MECHREVO      | WUJIE16 Pro                 | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| HP            | ProBook 450 G7              | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Sony          | VPCSB2A7R                   | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| HP            | ENVY Notebook               | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Emdoor        | AG958                       | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Medion        | E4251                       | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Google        | Fleex                       | [19603bb256](https://linux-hardware.org/?probe=19603bb256) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [6e1df0f6ee](https://linux-hardware.org/?probe=6e1df0f6ee) | Apr 21, 2023 |
| Emdoor        | AG958                       | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [87538ce2ba](https://linux-hardware.org/?probe=87538ce2ba) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| HP            | Laptop 15-dw3xxx            | [648c4c3622](https://linux-hardware.org/?probe=648c4c3622) | Apr 20, 2023 |
| HP            | ProBook 4540s               | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Dell          | Precision 3550              | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| HONOR         | HYM-WXX                     | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| HP            | 250 G7 Notebook PC          | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| Dell          | Precision 3571              | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| Dell          | Latitude 5500               | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| Positivo      | C14CR01                     | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| AZW           | GT-R                        | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| HP            | ProBook 640 G1              | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Unknown       | Unknown                     | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Unknown       | Unknown                     | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Apple         | MacBookPro7,1               | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| Acer          | Aspire A515-57              | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| Dell          | Precision 5520              | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| Sony          | VPCSB2A7R                   | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| MACHENIKE     | T58-V                       | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Fujitsu       | LIFEBOOK E746               | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Acer          | Nitro AN515-46              | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [770d8a9253](https://linux-hardware.org/?probe=770d8a9253) | Apr 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [8c29713fe9](https://linux-hardware.org/?probe=8c29713fe9) | Apr 05, 2023 |
| LG Electro... | Kabylake Platform           | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Toshiba       | QOSMIO F750                 | [695bc9e499](https://linux-hardware.org/?probe=695bc9e499) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| Timi          | RedmiBook 16                | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| Star Labs     | StarBook                    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| Dell          | XPS 13 9380                 | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| Dell          | Precision M6400             | [293957e2c0](https://linux-hardware.org/?probe=293957e2c0) | Mar 30, 2023 |
| HP            | OMEN by Laptop              | [c6e4da00ac](https://linux-hardware.org/?probe=c6e4da00ac) | Mar 30, 2023 |
| Framework     | Laptop                      | [ef17714efa](https://linux-hardware.org/?probe=ef17714efa) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HP            | Notebook                    | [ea7c0e1a2c](https://linux-hardware.org/?probe=ea7c0e1a2c) | Mar 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c393e49ce3](https://linux-hardware.org/?probe=c393e49ce3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e7608e5c20](https://linux-hardware.org/?probe=e7608e5c20) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Toshiba       | QOSMIO F750                 | [b52a3268f6](https://linux-hardware.org/?probe=b52a3268f6) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Dell          | G15 5515                    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| MSI           | GT70 2PE                    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [13e0523db8](https://linux-hardware.org/?probe=13e0523db8) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| Dell          | Vostro 15-3568              | [bc2447e1e5](https://linux-hardware.org/?probe=bc2447e1e5) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [f027c9ca09](https://linux-hardware.org/?probe=f027c9ca09) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | [e6ee9fc566](https://linux-hardware.org/?probe=e6ee9fc566) | Mar 25, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [5377aa4b23](https://linux-hardware.org/?probe=5377aa4b23) | Mar 24, 2023 |
| realme        | CloudProXXXX                | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Dell          | XPS 9315                    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [88d49f423d](https://linux-hardware.org/?probe=88d49f423d) | Mar 22, 2023 |
| Dell          | XPS 15 9500                 | [893f51c005](https://linux-hardware.org/?probe=893f51c005) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| ASUSTek       | TP500LB                     | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Dell          | XPS 15 9520                 | [b6ffb56057](https://linux-hardware.org/?probe=b6ffb56057) | Mar 20, 2023 |
| Acer          | Aspire E5-573G              | [e1c4772d0d](https://linux-hardware.org/?probe=e1c4772d0d) | Mar 19, 2023 |
| Acer          | Aspire E5-573G              | [68cf28bafe](https://linux-hardware.org/?probe=68cf28bafe) | Mar 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S64C00    | [d91384b02c](https://linux-hardware.org/?probe=d91384b02c) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| HP            | 245 G8                      | [5b1606146f](https://linux-hardware.org/?probe=5b1606146f) | Mar 19, 2023 |
| Sony          | SVZ1311C5E                  | [e433359eb9](https://linux-hardware.org/?probe=e433359eb9) | Mar 18, 2023 |
| Dell          | Latitude E5470              | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | [dd58f68013](https://linux-hardware.org/?probe=dd58f68013) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| Sony          | SVF1521Q1EW                 | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| Sony          | VPCEB4L1E                   | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| Dell          | G5 5587                     | [4ff3c98faf](https://linux-hardware.org/?probe=4ff3c98faf) | Mar 14, 2023 |
| Dell          | XPS 15 7590                 | [5997bff822](https://linux-hardware.org/?probe=5997bff822) | Mar 14, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4f32e23c4](https://linux-hardware.org/?probe=b4f32e23c4) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [3dc28679cc](https://linux-hardware.org/?probe=3dc28679cc) | Mar 14, 2023 |
| Positivo      | Q464B                       | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| HP            | Pavilion dv7                | [b0834fe20e](https://linux-hardware.org/?probe=b0834fe20e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| Apple         | MacBookPro14,1              | [999c455869](https://linux-hardware.org/?probe=999c455869) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| GPD           | G1621-02                    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Medion        | E4251                       | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | [593c3e084d](https://linux-hardware.org/?probe=593c3e084d) | Mar 12, 2023 |
| HP            | Laptop 15-dw3xxx            | [cc73320a47](https://linux-hardware.org/?probe=cc73320a47) | Mar 12, 2023 |
| HP            | Laptop 15-dy1xxx            | [ac6452184d](https://linux-hardware.org/?probe=ac6452184d) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | [5dfc4ceb2a](https://linux-hardware.org/?probe=5dfc4ceb2a) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| Unknown       | Unknown                     | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| Medion        | Akoya E6412T                | [d8941697fd](https://linux-hardware.org/?probe=d8941697fd) | Mar 09, 2023 |
| Dell          | Latitude 5590               | [d7d667d45f](https://linux-hardware.org/?probe=d7d667d45f) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [141222a198](https://linux-hardware.org/?probe=141222a198) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | [2f2541bbf1](https://linux-hardware.org/?probe=2f2541bbf1) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Infinix       | INBOOK X2 GEN11             | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Dell          | Latitude 5330               | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [d62df340f9](https://linux-hardware.org/?probe=d62df340f9) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Unknown       | Unknown                     | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| Google        | Delbin                      | [3817b0d62d](https://linux-hardware.org/?probe=3817b0d62d) | Mar 05, 2023 |
| Dell          | XPS 15 9500                 | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| HP            | Pavilion 15                 | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [645b47cfa2](https://linux-hardware.org/?probe=645b47cfa2) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Dell          | Latitude 5421               | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Dell          | Vostro 3500                 | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| HP            | ZBook 17 G2                 | [408bb96959](https://linux-hardware.org/?probe=408bb96959) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [aef7584b8c](https://linux-hardware.org/?probe=aef7584b8c) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | [b2ae4d0b42](https://linux-hardware.org/?probe=b2ae4d0b42) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude E5470              | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| HP            | EliteBook 8470p             | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [55c6dbae70](https://linux-hardware.org/?probe=55c6dbae70) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| Dell          | Latitude 7410               | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| MSI           | GF63 Thin 9RCX              | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f98cec9924](https://linux-hardware.org/?probe=f98cec9924) | Feb 22, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [8be573974d](https://linux-hardware.org/?probe=8be573974d) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| Apple         | MacBookAir7,2               | [97b147476a](https://linux-hardware.org/?probe=97b147476a) | Feb 20, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [d8afec7717](https://linux-hardware.org/?probe=d8afec7717) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | [a3f369f79b](https://linux-hardware.org/?probe=a3f369f79b) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [f8e02626c5](https://linux-hardware.org/?probe=f8e02626c5) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| HP            | Notebook                    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| Dell          | G3 3590                     | [a8a3df007f](https://linux-hardware.org/?probe=a8a3df007f) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| Acer          | Aspire A515-51              | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [5e35f0aecc](https://linux-hardware.org/?probe=5e35f0aecc) | Feb 17, 2023 |
| Jumper        | EZbook                      | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| Jumper        | EZbook                      | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e5e721aaf2](https://linux-hardware.org/?probe=e5e721aaf2) | Feb 16, 2023 |
| Google        | Robo360                     | [744490a82c](https://linux-hardware.org/?probe=744490a82c) | Feb 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Google        | Robo360                     | [573d036948](https://linux-hardware.org/?probe=573d036948) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Dell          | XPS 9320                    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Acer          | TravelMate P215-52          | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| Dell          | Latitude 7490               | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| Dell          | Precision 3571              | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7711c96063](https://linux-hardware.org/?probe=7711c96063) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| ASUSTek       | X550CC                      | [769e8c51f0](https://linux-hardware.org/?probe=769e8c51f0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fb8b46669e](https://linux-hardware.org/?probe=fb8b46669e) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [0a3aa89ac9](https://linux-hardware.org/?probe=0a3aa89ac9) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [69cd397ac6](https://linux-hardware.org/?probe=69cd397ac6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Dell          | Inspiron 13 5310            | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| MSI           | GE60 2QE                    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Dell          | Precision 3571              | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f5dbc828f3](https://linux-hardware.org/?probe=f5dbc828f3) | Feb 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [5c86b33fdd](https://linux-hardware.org/?probe=5c86b33fdd) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [7a2dd12cd8](https://linux-hardware.org/?probe=7a2dd12cd8) | Feb 08, 2023 |
| HP            | 15 Notebook PC              | [df487953da](https://linux-hardware.org/?probe=df487953da) | Feb 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [a8aa5d2d58](https://linux-hardware.org/?probe=a8aa5d2d58) | Feb 07, 2023 |
| HUAWEI        | BOM-WXX9                    | [ad723064e1](https://linux-hardware.org/?probe=ad723064e1) | Feb 06, 2023 |
| ASUSTek       | X550VXK                     | [e7a0aa4ff9](https://linux-hardware.org/?probe=e7a0aa4ff9) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f3cc45d12e](https://linux-hardware.org/?probe=f3cc45d12e) | Feb 05, 2023 |
| Timi          | A34S                        | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| Timi          | A34S                        | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [139605fcc1](https://linux-hardware.org/?probe=139605fcc1) | Feb 03, 2023 |
| Dell          | XPS 15 7590                 | [81f824a063](https://linux-hardware.org/?probe=81f824a063) | Feb 03, 2023 |
| Unknown       | Unknown                     | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Acer          | Predator PH315-55           | [9f90c06d52](https://linux-hardware.org/?probe=9f90c06d52) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| GPD           | G1619-04                    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| Dell          | Vostro 5481                 | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [3a2665872a](https://linux-hardware.org/?probe=3a2665872a) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| Dell          | Latitude 7430               | [44d6dd63ce](https://linux-hardware.org/?probe=44d6dd63ce) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Acer          | Aspire A315-56              | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| HP            | Compaq 6530b                | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [1ae85a6add](https://linux-hardware.org/?probe=1ae85a6add) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | [7f9b52e91c](https://linux-hardware.org/?probe=7f9b52e91c) | Jan 27, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Lenovo        | ThinkPad T490 20N20048GE    | [54915be6bc](https://linux-hardware.org/?probe=54915be6bc) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| realme        | CloudProXXXX                | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [bf22d53528](https://linux-hardware.org/?probe=bf22d53528) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Dell          | XPS 9320                    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| realme        | CloudProXXXX                | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| System76      | Darter UltraThin            | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| Medion        | E4251                       | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| Toshiba       | Satellite C50-C             | [3512195f65](https://linux-hardware.org/?probe=3512195f65) | Jan 21, 2023 |
| Dell          | G7 7700                     | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| Acer          | Swift SF314-57              | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| Dell          | Latitude E5440              | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | [96e072d33f](https://linux-hardware.org/?probe=96e072d33f) | Jan 18, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Acer          | Predator PH315-52           | [4df4c5ecc8](https://linux-hardware.org/?probe=4df4c5ecc8) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| Dell          | Inspiron 5585               | [b92481ca4e](https://linux-hardware.org/?probe=b92481ca4e) | Jan 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [6c8a25d916](https://linux-hardware.org/?probe=6c8a25d916) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| MSI           | Prestige 15 A11SCX          | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| HP            | ProBook 655 G1              | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| LG Electro... | 17Z90N-R.AAS9U1             | [9d6736bccd](https://linux-hardware.org/?probe=9d6736bccd) | Jan 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [4a0fec8aef](https://linux-hardware.org/?probe=4a0fec8aef) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [73533cda86](https://linux-hardware.org/?probe=73533cda86) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [ff2c48315e](https://linux-hardware.org/?probe=ff2c48315e) | Jan 13, 2023 |
| realme        | CloudProXXXX                | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| HP            | Pavilion 15                 | [1dc150e9db](https://linux-hardware.org/?probe=1dc150e9db) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [9f06213ef6](https://linux-hardware.org/?probe=9f06213ef6) | Jan 12, 2023 |
| HP            | ProBook 6560b               | [5b71b83435](https://linux-hardware.org/?probe=5b71b83435) | Jan 12, 2023 |
| Notebook      | L14xMU                      | [48b282b529](https://linux-hardware.org/?probe=48b282b529) | Jan 12, 2023 |
| Apple         | MacBookPro11,3              | [ede9b6da76](https://linux-hardware.org/?probe=ede9b6da76) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [5be6eaa40c](https://linux-hardware.org/?probe=5be6eaa40c) | Jan 11, 2023 |
| HONOR         | NMH-WCX9                    | [a67f1ee7b0](https://linux-hardware.org/?probe=a67f1ee7b0) | Jan 11, 2023 |
| Dell          | Precision 7710              | [fada5459cb](https://linux-hardware.org/?probe=fada5459cb) | Jan 11, 2023 |
| HP            | ProBook 655 G1              | [f61b79535e](https://linux-hardware.org/?probe=f61b79535e) | Jan 10, 2023 |
| ASUSTek       | UX31A                       | [c618ab31a8](https://linux-hardware.org/?probe=c618ab31a8) | Jan 10, 2023 |
| HP            | Pavilion dv6                | [8f65765701](https://linux-hardware.org/?probe=8f65765701) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [45e96fb346](https://linux-hardware.org/?probe=45e96fb346) | Jan 09, 2023 |
| Dell          | Precision 7710              | [0e64a34c3e](https://linux-hardware.org/?probe=0e64a34c3e) | Jan 09, 2023 |
| ASUSTek       | UX31A                       | [2eaea530ea](https://linux-hardware.org/?probe=2eaea530ea) | Jan 09, 2023 |
| HP            | ProBook 655 G1              | [91948448b6](https://linux-hardware.org/?probe=91948448b6) | Jan 09, 2023 |
| MSI           | GS63 Stealth 8RE            | [8682a08d74](https://linux-hardware.org/?probe=8682a08d74) | Jan 09, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [5feb203761](https://linux-hardware.org/?probe=5feb203761) | Jan 08, 2023 |
| ASUSTek       | UX31A                       | [da175172b3](https://linux-hardware.org/?probe=da175172b3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [1570ad8d8b](https://linux-hardware.org/?probe=1570ad8d8b) | Jan 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6ab7f1996a](https://linux-hardware.org/?probe=6ab7f1996a) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a0809aa](https://linux-hardware.org/?probe=dc2a0809aa) | Jan 07, 2023 |
| IPASON        | MaxBook P1X                 | [b7d1ce416f](https://linux-hardware.org/?probe=b7d1ce416f) | Jan 07, 2023 |
| Sony          | SVS1512U1RW                 | [c5de402a7c](https://linux-hardware.org/?probe=c5de402a7c) | Jan 06, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Samsung       | R530/R730                   | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c298dd423d](https://linux-hardware.org/?probe=c298dd423d) | Jan 05, 2023 |
| Medion        | E4251 MD61435               | [7f3f24b812](https://linux-hardware.org/?probe=7f3f24b812) | Jan 05, 2023 |
| ASUSTek       | X501A1                      | [f88e88d88d](https://linux-hardware.org/?probe=f88e88d88d) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| HP            | Laptop 14-dk0xxx            | [47654afbbc](https://linux-hardware.org/?probe=47654afbbc) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ac3df6f289](https://linux-hardware.org/?probe=ac3df6f289) | Jan 03, 2023 |
| HP            | EliteBook 840 G5            | [f7bf32067f](https://linux-hardware.org/?probe=f7bf32067f) | Jan 03, 2023 |
| Dell          | Inspiron 7577               | [437194cbc0](https://linux-hardware.org/?probe=437194cbc0) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [c8d9352d43](https://linux-hardware.org/?probe=c8d9352d43) | Jan 03, 2023 |
| ASUSTek       | UX31A                       | [ddadb5f34d](https://linux-hardware.org/?probe=ddadb5f34d) | Jan 03, 2023 |
| Dell          | Latitude 7410               | [3dadd543f1](https://linux-hardware.org/?probe=3dadd543f1) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Dell          | XPS 15 9570                 | [c5d2fc381a](https://linux-hardware.org/?probe=c5d2fc381a) | Jan 02, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7ff55c14b4](https://linux-hardware.org/?probe=7ff55c14b4) | Jan 02, 2023 |
| HP            | ZBook 15 G5                 | [04364cac9a](https://linux-hardware.org/?probe=04364cac9a) | Jan 02, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fbf89f7693](https://linux-hardware.org/?probe=fbf89f7693) | Jan 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| Lenovo        | ThinkPad L440 20ASEB3       | [a22f1e75b3](https://linux-hardware.org/?probe=a22f1e75b3) | Jan 01, 2023 |
| Unknown       | Unknown                     | [10496680a5](https://linux-hardware.org/?probe=10496680a5) | Dec 31, 2022 |
| Dell          | XPS 9320                    | [c98fd80f29](https://linux-hardware.org/?probe=c98fd80f29) | Dec 31, 2022 |
| ASUSTek       | X550VXK                     | [b8cd38522a](https://linux-hardware.org/?probe=b8cd38522a) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [ac397dc318](https://linux-hardware.org/?probe=ac397dc318) | Dec 31, 2022 |
| HP            | EliteBook 845 14 inch G9... | [5b5e58e433](https://linux-hardware.org/?probe=5b5e58e433) | Dec 31, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [c2a949b725](https://linux-hardware.org/?probe=c2a949b725) | Dec 31, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [5043868e71](https://linux-hardware.org/?probe=5043868e71) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [614187020c](https://linux-hardware.org/?probe=614187020c) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [11d4e1f9a1](https://linux-hardware.org/?probe=11d4e1f9a1) | Dec 29, 2022 |
| HP            | Pavilion Sleekbook 14 PC    | [b60b954dc4](https://linux-hardware.org/?probe=b60b954dc4) | Dec 29, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [bc9e41ea0d](https://linux-hardware.org/?probe=bc9e41ea0d) | Dec 29, 2022 |
| GPU Compan... | GWNR71517                   | [65f3d3dd65](https://linux-hardware.org/?probe=65f3d3dd65) | Dec 29, 2022 |
| Apple         | MacBookAir6,2               | [af9ab4ba4d](https://linux-hardware.org/?probe=af9ab4ba4d) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f5cbe897b8](https://linux-hardware.org/?probe=f5cbe897b8) | Dec 29, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [41f77d037b](https://linux-hardware.org/?probe=41f77d037b) | Dec 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [b62b4d2134](https://linux-hardware.org/?probe=b62b4d2134) | Dec 27, 2022 |
| Dell          | XPS 9320                    | [7a2537eba2](https://linux-hardware.org/?probe=7a2537eba2) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [eb5e0b8201](https://linux-hardware.org/?probe=eb5e0b8201) | Dec 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4ea69511df](https://linux-hardware.org/?probe=4ea69511df) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c8b85cb0cd](https://linux-hardware.org/?probe=c8b85cb0cd) | Dec 26, 2022 |
| Dell          | Inspiron N5010              | [69ac8a9522](https://linux-hardware.org/?probe=69ac8a9522) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [06027a53fb](https://linux-hardware.org/?probe=06027a53fb) | Dec 26, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [649291f277](https://linux-hardware.org/?probe=649291f277) | Dec 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [8d2d8be057](https://linux-hardware.org/?probe=8d2d8be057) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Dell          | XPS 9320                    | [f55956cac2](https://linux-hardware.org/?probe=f55956cac2) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [81fcc00d18](https://linux-hardware.org/?probe=81fcc00d18) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [880f8d51d3](https://linux-hardware.org/?probe=880f8d51d3) | Dec 24, 2022 |
| HP            | ProBook 6470b               | [315e362044](https://linux-hardware.org/?probe=315e362044) | Dec 24, 2022 |
| Medion        | E4251 MD61435               | [0ef8f76193](https://linux-hardware.org/?probe=0ef8f76193) | Dec 23, 2022 |
| HP            | Laptop 15-bs0xx             | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| HUAWEI        | KPR-WX9                     | [e2b01c4a0f](https://linux-hardware.org/?probe=e2b01c4a0f) | Dec 23, 2022 |
| Acer          | Aspire A515-52G             | [586dd36eed](https://linux-hardware.org/?probe=586dd36eed) | Dec 23, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [e2e9b14a43](https://linux-hardware.org/?probe=e2e9b14a43) | Dec 23, 2022 |
| Dell          | Precision M6600             | [00840d085c](https://linux-hardware.org/?probe=00840d085c) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Dell          | XPS 9320                    | [7bb7ba7202](https://linux-hardware.org/?probe=7bb7ba7202) | Dec 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| MSI           | Katana GF66 11UE            | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| HUAWEI        | VLT-WX0                     | [6f2d542a6e](https://linux-hardware.org/?probe=6f2d542a6e) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [ee344993aa](https://linux-hardware.org/?probe=ee344993aa) | Dec 22, 2022 |
| ASUSTek       | K45VM                       | [cc9fb3fd05](https://linux-hardware.org/?probe=cc9fb3fd05) | Dec 22, 2022 |
| Lenovo        | ThinkPad T540p 20BFS0MQ0... | [94e5bdb2cb](https://linux-hardware.org/?probe=94e5bdb2cb) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [482001243a](https://linux-hardware.org/?probe=482001243a) | Dec 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [95a82bb7e0](https://linux-hardware.org/?probe=95a82bb7e0) | Dec 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [214d584e36](https://linux-hardware.org/?probe=214d584e36) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [c4f6f99d36](https://linux-hardware.org/?probe=c4f6f99d36) | Dec 21, 2022 |
| HP            | ENVY Laptop 16-h0xxx        | [4e38f93dd3](https://linux-hardware.org/?probe=4e38f93dd3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [bdb2887598](https://linux-hardware.org/?probe=bdb2887598) | Dec 20, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [90d1d153a4](https://linux-hardware.org/?probe=90d1d153a4) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [93eff781da](https://linux-hardware.org/?probe=93eff781da) | Dec 20, 2022 |
| Acer          | Aspire A715-51G             | [0b7352a343](https://linux-hardware.org/?probe=0b7352a343) | Dec 20, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [654a04cdc4](https://linux-hardware.org/?probe=654a04cdc4) | Dec 20, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [ebf2594631](https://linux-hardware.org/?probe=ebf2594631) | Dec 19, 2022 |
| K.A.Techno... | TM1                         | [88e36a5d00](https://linux-hardware.org/?probe=88e36a5d00) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Dell          | XPS 13 9350                 | [d414748117](https://linux-hardware.org/?probe=d414748117) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c45ca502c5](https://linux-hardware.org/?probe=c45ca502c5) | Dec 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [2d6dff8209](https://linux-hardware.org/?probe=2d6dff8209) | Dec 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0d67c53553](https://linux-hardware.org/?probe=0d67c53553) | Dec 18, 2022 |
| HP            | 2000                        | [6273a792ae](https://linux-hardware.org/?probe=6273a792ae) | Dec 18, 2022 |
| Acer          | Aspire A515-46              | [fab35bfa42](https://linux-hardware.org/?probe=fab35bfa42) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [86fbbf1bc2](https://linux-hardware.org/?probe=86fbbf1bc2) | Dec 17, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| Alienware     | 15                          | [6da8e1748a](https://linux-hardware.org/?probe=6da8e1748a) | Dec 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8f50c0d881](https://linux-hardware.org/?probe=8f50c0d881) | Dec 15, 2022 |
| Dell          | Vostro 7590                 | [c758af3223](https://linux-hardware.org/?probe=c758af3223) | Dec 15, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | [ca39e55353](https://linux-hardware.org/?probe=ca39e55353) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Dell          | Inspiron 5370               | [dd8f3feae5](https://linux-hardware.org/?probe=dd8f3feae5) | Dec 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9495189605](https://linux-hardware.org/?probe=9495189605) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [3878d884cb](https://linux-hardware.org/?probe=3878d884cb) | Dec 15, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [98f6e27cac](https://linux-hardware.org/?probe=98f6e27cac) | Dec 14, 2022 |
| Toshiba       | Satellite Pro L300          | [6db5b50a6b](https://linux-hardware.org/?probe=6db5b50a6b) | Dec 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [db7a82e46c](https://linux-hardware.org/?probe=db7a82e46c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| K.A.Techno... | TM1                         | [a27835f164](https://linux-hardware.org/?probe=a27835f164) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| Acer          | Aspire ES1-111M             | [0d527c1b1d](https://linux-hardware.org/?probe=0d527c1b1d) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Acer          | Nitro AN517-41              | [468d665801](https://linux-hardware.org/?probe=468d665801) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [559c3f32f8](https://linux-hardware.org/?probe=559c3f32f8) | Dec 12, 2022 |
| HP            | OMEN by Gaming Laptop 16... | [eb0d410f64](https://linux-hardware.org/?probe=eb0d410f64) | Dec 12, 2022 |
| Apple         | MacBookPro11,2              | [6048cffe66](https://linux-hardware.org/?probe=6048cffe66) | Dec 12, 2022 |
| Unknown       | X133                        | [694e264bcf](https://linux-hardware.org/?probe=694e264bcf) | Dec 12, 2022 |
| MSI           | Prestige 14 A11SC           | [7fa118f812](https://linux-hardware.org/?probe=7fa118f812) | Dec 11, 2022 |
| Medion        | E4251                       | [f7303bf4c9](https://linux-hardware.org/?probe=f7303bf4c9) | Dec 11, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| Acer          | Aspire E5-571G              | [5ddea1e0e0](https://linux-hardware.org/?probe=5ddea1e0e0) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| HUAWEI        | CREM-WXX9                   | [1b6dee1e4a](https://linux-hardware.org/?probe=1b6dee1e4a) | Dec 10, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [61b2bab886](https://linux-hardware.org/?probe=61b2bab886) | Dec 10, 2022 |
| Medion        | E4251                       | [a16b01515b](https://linux-hardware.org/?probe=a16b01515b) | Dec 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [173f4b722f](https://linux-hardware.org/?probe=173f4b722f) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [fdda7ba30e](https://linux-hardware.org/?probe=fdda7ba30e) | Dec 10, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [16232a46ed](https://linux-hardware.org/?probe=16232a46ed) | Dec 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5S... | [7772d8b9f8](https://linux-hardware.org/?probe=7772d8b9f8) | Dec 10, 2022 |
| GPU Compan... | GWNR71517                   | [148040d1fd](https://linux-hardware.org/?probe=148040d1fd) | Dec 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [9d240437ee](https://linux-hardware.org/?probe=9d240437ee) | Dec 08, 2022 |
| IPASON        | MaxBook P1X                 | [c699081c87](https://linux-hardware.org/?probe=c699081c87) | Dec 08, 2022 |
| BESSTAR Te... | U820                        | [ea466e46b1](https://linux-hardware.org/?probe=ea466e46b1) | Dec 07, 2022 |
| HP            | 245 G8                      | [2fbc616550](https://linux-hardware.org/?probe=2fbc616550) | Dec 07, 2022 |
| Clevo         | P150HMx                     | [f1500b1665](https://linux-hardware.org/?probe=f1500b1665) | Dec 06, 2022 |
| Dell          | Inspiron N5110              | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Dell          | G15 5515                    | [63fed6d448](https://linux-hardware.org/?probe=63fed6d448) | Dec 06, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [3e1e88ac7a](https://linux-hardware.org/?probe=3e1e88ac7a) | Dec 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2KM0... | [792c537a38](https://linux-hardware.org/?probe=792c537a38) | Dec 06, 2022 |
| HP            | ProBook 440 G5              | [7f9c0a0974](https://linux-hardware.org/?probe=7f9c0a0974) | Dec 06, 2022 |
| Dell          | G5 5505                     | [c36399d764](https://linux-hardware.org/?probe=c36399d764) | Dec 06, 2022 |
| Medion        | E4251                       | [a515c5c071](https://linux-hardware.org/?probe=a515c5c071) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [05f6a48b4a](https://linux-hardware.org/?probe=05f6a48b4a) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [8a91af8c9d](https://linux-hardware.org/?probe=8a91af8c9d) | Dec 05, 2022 |
| Toshiba       | Satellite C650D             | [694d2c9099](https://linux-hardware.org/?probe=694d2c9099) | Dec 05, 2022 |
| Medion        | E4251 MD61435               | [481a9c958a](https://linux-hardware.org/?probe=481a9c958a) | Dec 04, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [3ee55cc441](https://linux-hardware.org/?probe=3ee55cc441) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| HP            | ProBook 440 G5              | [a8e17ad39c](https://linux-hardware.org/?probe=a8e17ad39c) | Dec 04, 2022 |
| MECHREVO      | X3 Series GK7CP6R           | [7990b26bbf](https://linux-hardware.org/?probe=7990b26bbf) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [05ae64c1b8](https://linux-hardware.org/?probe=05ae64c1b8) | Dec 04, 2022 |
| Acer          | Aspire 4736Z                | [ae6745045a](https://linux-hardware.org/?probe=ae6745045a) | Dec 04, 2022 |
| HP            | ZBook 15 G4                 | [9950cb061d](https://linux-hardware.org/?probe=9950cb061d) | Dec 03, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [2cf560b162](https://linux-hardware.org/?probe=2cf560b162) | Dec 03, 2022 |
| Medion        | E4251 MD61435               | [c3f4fd226e](https://linux-hardware.org/?probe=c3f4fd226e) | Dec 03, 2022 |
| Medion        | E4251                       | [3167cbece1](https://linux-hardware.org/?probe=3167cbece1) | Dec 03, 2022 |
| HP            | Pavilion Laptop             | [2e2f1d44c1](https://linux-hardware.org/?probe=2e2f1d44c1) | Dec 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Valve         | Jupiter                     | [1fdf6ffce7](https://linux-hardware.org/?probe=1fdf6ffce7) | Dec 01, 2022 |
| Dell          | Precision 5540              | [030dbd45f0](https://linux-hardware.org/?probe=030dbd45f0) | Dec 01, 2022 |
| Acer          | TravelMate P614-51T-G2      | [952e89e25d](https://linux-hardware.org/?probe=952e89e25d) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [9bd70d2025](https://linux-hardware.org/?probe=9bd70d2025) | Nov 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [bd0ca3e793](https://linux-hardware.org/?probe=bd0ca3e793) | Nov 30, 2022 |
| Toshiba       | TECRA S11                   | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [f5f86becf7](https://linux-hardware.org/?probe=f5f86becf7) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Dell          | Precision 7520              | [2c0cb92f23](https://linux-hardware.org/?probe=2c0cb92f23) | Nov 29, 2022 |
| HP            | ProBook 440 G5              | [45097ff070](https://linux-hardware.org/?probe=45097ff070) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| Lenovo        | ThinkPad T460s 20FAS16J0... | [142a1e8a94](https://linux-hardware.org/?probe=142a1e8a94) | Nov 29, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e0bdd2fbd2](https://linux-hardware.org/?probe=e0bdd2fbd2) | Nov 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [69a6535286](https://linux-hardware.org/?probe=69a6535286) | Nov 28, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| HP            | Laptop 15-dy2xxx            | [a1c088bc35](https://linux-hardware.org/?probe=a1c088bc35) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | [0dcd2bdc50](https://linux-hardware.org/?probe=0dcd2bdc50) | Nov 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [620cab185f](https://linux-hardware.org/?probe=620cab185f) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| HUAWEI        | KLVL-WXXW                   | [7e65f428cc](https://linux-hardware.org/?probe=7e65f428cc) | Nov 27, 2022 |
| MSI           | GL62 7QF                    | [abd74be332](https://linux-hardware.org/?probe=abd74be332) | Nov 27, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| ASUSTek       | X555YI                      | [2626d57c13](https://linux-hardware.org/?probe=2626d57c13) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| Alienware     | 15                          | [3423725ae2](https://linux-hardware.org/?probe=3423725ae2) | Nov 24, 2022 |
| MSI           | GP63 Leopard 8RE            | [f8bb75758e](https://linux-hardware.org/?probe=f8bb75758e) | Nov 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [c799c028af](https://linux-hardware.org/?probe=c799c028af) | Nov 23, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [96205eb8d4](https://linux-hardware.org/?probe=96205eb8d4) | Nov 22, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [97571585cd](https://linux-hardware.org/?probe=97571585cd) | Nov 22, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [e9ba2ff234](https://linux-hardware.org/?probe=e9ba2ff234) | Nov 22, 2022 |
| ASUSTek       | PRIME Z690-P                | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [bdf1794487](https://linux-hardware.org/?probe=bdf1794487) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [7e8b56ff73](https://linux-hardware.org/?probe=7e8b56ff73) | Nov 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [54d3eed278](https://linux-hardware.org/?probe=54d3eed278) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [60c1698203](https://linux-hardware.org/?probe=60c1698203) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6722142846](https://linux-hardware.org/?probe=6722142846) | Nov 20, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Fujitsu       | LIFEBOOK E756               | [144470ec16](https://linux-hardware.org/?probe=144470ec16) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| Lenovo        | ThinkPad T430 2349KQ3       | [aacdefc31b](https://linux-hardware.org/?probe=aacdefc31b) | Nov 17, 2022 |
| Timi          | Xiaomi Book Pro 16 2022     | [08db92bff6](https://linux-hardware.org/?probe=08db92bff6) | Nov 17, 2022 |
| HP            | Compaq 15                   | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [922ce95539](https://linux-hardware.org/?probe=922ce95539) | Nov 16, 2022 |
| Google        | Boten                       | [105e91dd04](https://linux-hardware.org/?probe=105e91dd04) | Nov 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [3e46bbaa1b](https://linux-hardware.org/?probe=3e46bbaa1b) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [cf97226a28](https://linux-hardware.org/?probe=cf97226a28) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [612006bada](https://linux-hardware.org/?probe=612006bada) | Nov 15, 2022 |
| Dell          | Latitude E6220              | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| HP            | ProBook 450 G7              | [2e122b28c4](https://linux-hardware.org/?probe=2e122b28c4) | Nov 15, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dcffe478fe](https://linux-hardware.org/?probe=dcffe478fe) | Nov 14, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [e6ef3b56eb](https://linux-hardware.org/?probe=e6ef3b56eb) | Nov 14, 2022 |
| Lenovo        | ThinkPad T450s 20BW000DH... | [b9913c760a](https://linux-hardware.org/?probe=b9913c760a) | Nov 14, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [41dbab85c0](https://linux-hardware.org/?probe=41dbab85c0) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b3473a1862](https://linux-hardware.org/?probe=b3473a1862) | Nov 13, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ca85c59fad](https://linux-hardware.org/?probe=ca85c59fad) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Dell          | G15 5510                    | [641a09f9cc](https://linux-hardware.org/?probe=641a09f9cc) | Nov 13, 2022 |
| Lenovo        | G500 20236                  | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [7827dd0f86](https://linux-hardware.org/?probe=7827dd0f86) | Nov 11, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [64d896b971](https://linux-hardware.org/?probe=64d896b971) | Nov 11, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [c3612a66aa](https://linux-hardware.org/?probe=c3612a66aa) | Nov 10, 2022 |
| HP            | EliteBook 840 14 inch G9... | [950c263b8a](https://linux-hardware.org/?probe=950c263b8a) | Nov 10, 2022 |
| Dell          | Latitude E6330              | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Acer          | Aspire V5-123               | [7e9ca0bb77](https://linux-hardware.org/?probe=7e9ca0bb77) | Nov 09, 2022 |
| HP            | ENVY 15                     | [716fe10a4a](https://linux-hardware.org/?probe=716fe10a4a) | Nov 09, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| Lenovo        | V15-IIL 82C5                | [7f372be9dc](https://linux-hardware.org/?probe=7f372be9dc) | Nov 07, 2022 |
| Dell          | Inspiron 5379               | [f18d0b8b8a](https://linux-hardware.org/?probe=f18d0b8b8a) | Nov 06, 2022 |
| Dell          | Inspiron 5379               | [141de7e9a7](https://linux-hardware.org/?probe=141de7e9a7) | Nov 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [3d53b3616f](https://linux-hardware.org/?probe=3d53b3616f) | Nov 06, 2022 |
| HP            | ProBook 455 G7              | [4432a70f95](https://linux-hardware.org/?probe=4432a70f95) | Nov 06, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | [e5abd4f928](https://linux-hardware.org/?probe=e5abd4f928) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Dell          | Inspiron 5502               | [204c296466](https://linux-hardware.org/?probe=204c296466) | Nov 04, 2022 |
| ASUSTek       | X553MA                      | [d70f962654](https://linux-hardware.org/?probe=d70f962654) | Nov 04, 2022 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [ca5335acd5](https://linux-hardware.org/?probe=ca5335acd5) | Nov 03, 2022 |
| Dell          | Latitude 7280               | [ec1ac4ec28](https://linux-hardware.org/?probe=ec1ac4ec28) | Nov 03, 2022 |
| Acer          | Swift SF314-57              | [8ab3b70362](https://linux-hardware.org/?probe=8ab3b70362) | Nov 03, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [2b5c165e30](https://linux-hardware.org/?probe=2b5c165e30) | Nov 02, 2022 |
| Dell          | XPS 13 9305                 | [4ffebc50a0](https://linux-hardware.org/?probe=4ffebc50a0) | Nov 02, 2022 |
| Dell          | Precision 7530              | [b1b5f7678c](https://linux-hardware.org/?probe=b1b5f7678c) | Nov 01, 2022 |
| Apple         | MacBookAir6,2               | [053e74af53](https://linux-hardware.org/?probe=053e74af53) | Nov 01, 2022 |
| Acer          | Aspire A515-46              | [ef6bcab217](https://linux-hardware.org/?probe=ef6bcab217) | Nov 01, 2022 |
| Lenovo        | ThinkPad L460 20FVS1Y500    | [5fc669ddbe](https://linux-hardware.org/?probe=5fc669ddbe) | Nov 01, 2022 |
| SANTECH       | NL5xRU                      | [63e1b4298d](https://linux-hardware.org/?probe=63e1b4298d) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [6a28e2929d](https://linux-hardware.org/?probe=6a28e2929d) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440p 20AW005BG... | [b25134edde](https://linux-hardware.org/?probe=b25134edde) | Oct 31, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5355a5547a](https://linux-hardware.org/?probe=5355a5547a) | Oct 31, 2022 |
| Alienware     | 15 R3                       | [4659975000](https://linux-hardware.org/?probe=4659975000) | Oct 31, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [0e06dcc642](https://linux-hardware.org/?probe=0e06dcc642) | Oct 31, 2022 |
| ASUSTek       | X510UNR                     | [41a0a441d3](https://linux-hardware.org/?probe=41a0a441d3) | Oct 30, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [c49a76df2a](https://linux-hardware.org/?probe=c49a76df2a) | Oct 30, 2022 |
| ASUSTek       | X550JX                      | [56e2dbb09b](https://linux-hardware.org/?probe=56e2dbb09b) | Oct 30, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [eb22113dae](https://linux-hardware.org/?probe=eb22113dae) | Oct 29, 2022 |
| HP            | InsydeH2O EFI BIOS          | [d157bdbc2b](https://linux-hardware.org/?probe=d157bdbc2b) | Oct 29, 2022 |
| ASUSTek       | X541UV                      | [cef88d9d62](https://linux-hardware.org/?probe=cef88d9d62) | Oct 29, 2022 |
| Acer          | Aspire 4745Z                | [baf4fe6e63](https://linux-hardware.org/?probe=baf4fe6e63) | Oct 29, 2022 |
| Chuwi         | LapBook Pro                 | [d362ed14bf](https://linux-hardware.org/?probe=d362ed14bf) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [806e4d754d](https://linux-hardware.org/?probe=806e4d754d) | Oct 28, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [d6ccf0a2d8](https://linux-hardware.org/?probe=d6ccf0a2d8) | Oct 28, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [d5c2f29c22](https://linux-hardware.org/?probe=d5c2f29c22) | Oct 28, 2022 |
| MSI           | GP66 Leopard 11UG           | [aec6edc8a0](https://linux-hardware.org/?probe=aec6edc8a0) | Oct 28, 2022 |
| Dell          | Inspiron 11 - 3147          | [58d46fb47f](https://linux-hardware.org/?probe=58d46fb47f) | Oct 28, 2022 |
| Acer          | Aspire E5-573G              | [f575803f23](https://linux-hardware.org/?probe=f575803f23) | Oct 28, 2022 |
| Lenovo        | G470 20078                  | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| HP            | ProBook 450 G5              | [664bf1184f](https://linux-hardware.org/?probe=664bf1184f) | Oct 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| HUAWEI        | BOM-WXX9                    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [b9c616b406](https://linux-hardware.org/?probe=b9c616b406) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [16b3338525](https://linux-hardware.org/?probe=16b3338525) | Oct 27, 2022 |
| HP            | ProBook 445 G7              | [d9f63cbff8](https://linux-hardware.org/?probe=d9f63cbff8) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [ffa2d93859](https://linux-hardware.org/?probe=ffa2d93859) | Oct 26, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [642cfbc2d7](https://linux-hardware.org/?probe=642cfbc2d7) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [1ded224c69](https://linux-hardware.org/?probe=1ded224c69) | Oct 26, 2022 |
| Acer          | Swift SFX14-41G             | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [bb90eb1ad1](https://linux-hardware.org/?probe=bb90eb1ad1) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b2bb88f27f](https://linux-hardware.org/?probe=b2bb88f27f) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [e5d5599bc7](https://linux-hardware.org/?probe=e5d5599bc7) | Oct 25, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [9cc8a69671](https://linux-hardware.org/?probe=9cc8a69671) | Oct 25, 2022 |
| HP            | Spectre Laptop 13-af0xx     | [7e6d814d87](https://linux-hardware.org/?probe=7e6d814d87) | Oct 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [15ced71b20](https://linux-hardware.org/?probe=15ced71b20) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [8994af98ff](https://linux-hardware.org/?probe=8994af98ff) | Oct 24, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fc7326f81b](https://linux-hardware.org/?probe=fc7326f81b) | Oct 24, 2022 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [37028111aa](https://linux-hardware.org/?probe=37028111aa) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [bc30c6555a](https://linux-hardware.org/?probe=bc30c6555a) | Oct 24, 2022 |
| HONOR         | BBR-WAX9                    | [667d235a8f](https://linux-hardware.org/?probe=667d235a8f) | Oct 24, 2022 |
| MSI           | Pulse GL76 12UEK            | [bb06dc4756](https://linux-hardware.org/?probe=bb06dc4756) | Oct 24, 2022 |
| Tactus        | GeoBook_240                 | [5331bf15bd](https://linux-hardware.org/?probe=5331bf15bd) | Oct 23, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| HP            | ZBook 17 G6                 | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7cafd024ea](https://linux-hardware.org/?probe=7cafd024ea) | Oct 22, 2022 |
| Global Dis... | W11651                      | [9cf1e2df07](https://linux-hardware.org/?probe=9cf1e2df07) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [9f16b5a7e2](https://linux-hardware.org/?probe=9f16b5a7e2) | Oct 22, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [025f4fa8ab](https://linux-hardware.org/?probe=025f4fa8ab) | Oct 22, 2022 |
| Lenovo        | Legion 5 82B5               | [3d67f01531](https://linux-hardware.org/?probe=3d67f01531) | Oct 22, 2022 |
| HP            | ProBook 6550b               | [cc300bedc8](https://linux-hardware.org/?probe=cc300bedc8) | Oct 21, 2022 |
| MSI           | Katana GF76 11UG            | [ab90111e61](https://linux-hardware.org/?probe=ab90111e61) | Oct 21, 2022 |
| Dell          | Latitude E6400              | [d899ab2ef4](https://linux-hardware.org/?probe=d899ab2ef4) | Oct 21, 2022 |
| Medion        | S15449                      | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| HP            | ProBook 6550b               | [176fc347d2](https://linux-hardware.org/?probe=176fc347d2) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [30bf540299](https://linux-hardware.org/?probe=30bf540299) | Oct 19, 2022 |
| MSI           | Modern 15 A11MU             | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [56089b3625](https://linux-hardware.org/?probe=56089b3625) | Oct 19, 2022 |
| Acer          | Aspire 4750                 | [e07159c158](https://linux-hardware.org/?probe=e07159c158) | Oct 19, 2022 |
| Dell          | Latitude E6220              | [66badd4e9a](https://linux-hardware.org/?probe=66badd4e9a) | Oct 18, 2022 |
| Acer          | Aspire 4750                 | [0910d29ded](https://linux-hardware.org/?probe=0910d29ded) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [469118097a](https://linux-hardware.org/?probe=469118097a) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Acer          | Aspire V3-771               | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Dell          | Inspiron 7520               | [732f4ea8fe](https://linux-hardware.org/?probe=732f4ea8fe) | Oct 17, 2022 |
| HP            | ENVY 15                     | [17681478e1](https://linux-hardware.org/?probe=17681478e1) | Oct 17, 2022 |
| Dell          | Inspiron 3542               | [55f7f983c4](https://linux-hardware.org/?probe=55f7f983c4) | Oct 17, 2022 |
| Lenovo        | Y50-70 20378                | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| MSI           | Katana GF76 11UG            | [460ceb1307](https://linux-hardware.org/?probe=460ceb1307) | Oct 16, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e515cd0e66](https://linux-hardware.org/?probe=e515cd0e66) | Oct 15, 2022 |
| HP            | ProBook 455 G7              | [bb58a322f3](https://linux-hardware.org/?probe=bb58a322f3) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [89b3dc8edd](https://linux-hardware.org/?probe=89b3dc8edd) | Oct 14, 2022 |
| Acer          | Aspire E5-553G              | [fcf93f53f4](https://linux-hardware.org/?probe=fcf93f53f4) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [705931711b](https://linux-hardware.org/?probe=705931711b) | Oct 13, 2022 |
| Dell          | Latitude E7250              | [f397f81353](https://linux-hardware.org/?probe=f397f81353) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5074f8e471](https://linux-hardware.org/?probe=5074f8e471) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [318b3ef82b](https://linux-hardware.org/?probe=318b3ef82b) | Oct 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [cbc3888844](https://linux-hardware.org/?probe=cbc3888844) | Oct 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fb97ad01eb](https://linux-hardware.org/?probe=fb97ad01eb) | Oct 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [17feafd680](https://linux-hardware.org/?probe=17feafd680) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [1bbc611d89](https://linux-hardware.org/?probe=1bbc611d89) | Oct 12, 2022 |
| AVITA         | NS14A6                      | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| AVITA         | NS14A6                      | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| HUAWEI        | HVY-WXX9                    | [10ab944320](https://linux-hardware.org/?probe=10ab944320) | Oct 11, 2022 |
| HP            | Pavilion g6                 | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Lenovo        | Z50-75 80EC                 | [3837291e33](https://linux-hardware.org/?probe=3837291e33) | Oct 10, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [cc663da2bc](https://linux-hardware.org/?probe=cc663da2bc) | Oct 10, 2022 |
| Dell          | Inspiron 7520               | [05e8d3583c](https://linux-hardware.org/?probe=05e8d3583c) | Oct 10, 2022 |
| Acer          | Aspire 5750                 | [f335fc684d](https://linux-hardware.org/?probe=f335fc684d) | Oct 09, 2022 |
| Apple         | MacBookPro10,2              | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| Dell          | Precision 5560              | [001c5b0c94](https://linux-hardware.org/?probe=001c5b0c94) | Oct 09, 2022 |
| Dell          | Latitude 5310               | [f694e6b10e](https://linux-hardware.org/?probe=f694e6b10e) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Acer          | Extensa 215-32              | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [49802b54cd](https://linux-hardware.org/?probe=49802b54cd) | Oct 08, 2022 |
| Acer          | Extensa 215-32              | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [4afa1df235](https://linux-hardware.org/?probe=4afa1df235) | Oct 08, 2022 |
| ASUSTek       | X550CL                      | [d0584d3672](https://linux-hardware.org/?probe=d0584d3672) | Oct 08, 2022 |
| HP            | Pavilion dv6                | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2e020fe882](https://linux-hardware.org/?probe=2e020fe882) | Oct 07, 2022 |
| Toshiba       | Satellite P755              | [9b8147c1f7](https://linux-hardware.org/?probe=9b8147c1f7) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| Toshiba       | Encore                      | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| CyberPower... | FANG Pro                    | [e8734135b0](https://linux-hardware.org/?probe=e8734135b0) | Oct 05, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [4ba2e11c73](https://linux-hardware.org/?probe=4ba2e11c73) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [ca89628082](https://linux-hardware.org/?probe=ca89628082) | Oct 03, 2022 |
| GPD           | G1621-02                    | [1f88eb2bec](https://linux-hardware.org/?probe=1f88eb2bec) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [9c3f9bb60e](https://linux-hardware.org/?probe=9c3f9bb60e) | Oct 03, 2022 |
| MSI           | Katana GF76 11UG            | [d433417836](https://linux-hardware.org/?probe=d433417836) | Oct 03, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [0d67980efe](https://linux-hardware.org/?probe=0d67980efe) | Oct 03, 2022 |
| Acer          | Aspire F5-573G              | [a9f0d894af](https://linux-hardware.org/?probe=a9f0d894af) | Oct 03, 2022 |
| Dell          | XPS 13 9310                 | [f58849d2c7](https://linux-hardware.org/?probe=f58849d2c7) | Oct 03, 2022 |
| HP            | Laptop 14-dk0xxx            | [4283f9a4bd](https://linux-hardware.org/?probe=4283f9a4bd) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | [831cd8e80f](https://linux-hardware.org/?probe=831cd8e80f) | Oct 02, 2022 |
| HP            | ProBook 6470b               | [10438199c4](https://linux-hardware.org/?probe=10438199c4) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | 250 G3                      | [753ef53a5a](https://linux-hardware.org/?probe=753ef53a5a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [012add7349](https://linux-hardware.org/?probe=012add7349) | Oct 01, 2022 |
| Sony          | SVF15N17CXB                 | [5082dde27d](https://linux-hardware.org/?probe=5082dde27d) | Oct 01, 2022 |
| Irbis         | NB121                       | [a2eb8c8af1](https://linux-hardware.org/?probe=a2eb8c8af1) | Sep 30, 2022 |
| HP            | EliteBook 850 G1            | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Irbis         | NB121                       | [90a0ae1cf9](https://linux-hardware.org/?probe=90a0ae1cf9) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [3ad60e2d21](https://linux-hardware.org/?probe=3ad60e2d21) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [5a8032ee05](https://linux-hardware.org/?probe=5a8032ee05) | Sep 30, 2022 |
| Intel Clie... | LAPQC71A                    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| HP            | Notebook                    | [e172f83238](https://linux-hardware.org/?probe=e172f83238) | Sep 30, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [4e9248b1eb](https://linux-hardware.org/?probe=4e9248b1eb) | Sep 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [353324cbfd](https://linux-hardware.org/?probe=353324cbfd) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a1bee52021](https://linux-hardware.org/?probe=a1bee52021) | Sep 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [dfea1c9f70](https://linux-hardware.org/?probe=dfea1c9f70) | Sep 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [25d3fc37f5](https://linux-hardware.org/?probe=25d3fc37f5) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [f5ddf4a2b4](https://linux-hardware.org/?probe=f5ddf4a2b4) | Sep 29, 2022 |
| HP            | ProBook 430 G6              | [5c133ac35b](https://linux-hardware.org/?probe=5c133ac35b) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [72d80e02c9](https://linux-hardware.org/?probe=72d80e02c9) | Sep 29, 2022 |
| HUAWEI        | KLVD-WXX9                   | [47b22afda2](https://linux-hardware.org/?probe=47b22afda2) | Sep 29, 2022 |
| Toshiba       | Satellite C650D             | [0fce536c7d](https://linux-hardware.org/?probe=0fce536c7d) | Sep 28, 2022 |
| HP            | Laptop 14-dq1xxx            | [9b3a3858bc](https://linux-hardware.org/?probe=9b3a3858bc) | Sep 28, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [9a1e3a98ab](https://linux-hardware.org/?probe=9a1e3a98ab) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ebfbdd37b8](https://linux-hardware.org/?probe=ebfbdd37b8) | Sep 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [09d154c2f2](https://linux-hardware.org/?probe=09d154c2f2) | Sep 27, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [e27e7bfd76](https://linux-hardware.org/?probe=e27e7bfd76) | Sep 27, 2022 |
| Dell          | Latitude E7440              | [d211ff97c6](https://linux-hardware.org/?probe=d211ff97c6) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Dell          | Latitude E6400              | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Lenovo        | ThinkPad T460p 20FW000EG... | [60138ee2f9](https://linux-hardware.org/?probe=60138ee2f9) | Sep 26, 2022 |
| Timi          | RedmiBook Pro 15S           | [533cc3b3ae](https://linux-hardware.org/?probe=533cc3b3ae) | Sep 26, 2022 |
| ASUSTek       | N45SF                       | [7461bd2562](https://linux-hardware.org/?probe=7461bd2562) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [0d1b8fe301](https://linux-hardware.org/?probe=0d1b8fe301) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | [ccba8f6c1a](https://linux-hardware.org/?probe=ccba8f6c1a) | Sep 24, 2022 |
| ASUSTek       | X556UF                      | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| Acer          | Swift SF314-71              | [321edce78d](https://linux-hardware.org/?probe=321edce78d) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E531 68852... | [5e91cc6f07](https://linux-hardware.org/?probe=5e91cc6f07) | Sep 21, 2022 |
| Unknown       | Unknown                     | [af65739ccc](https://linux-hardware.org/?probe=af65739ccc) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | Laptop                      | [0cbc7e4f5a](https://linux-hardware.org/?probe=0cbc7e4f5a) | Sep 21, 2022 |
| HP            | ENVY 15                     | [388547d18c](https://linux-hardware.org/?probe=388547d18c) | Sep 21, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [6ffce551a0](https://linux-hardware.org/?probe=6ffce551a0) | Sep 21, 2022 |
| HP            | ProBook 4520s               | [af4a575c52](https://linux-hardware.org/?probe=af4a575c52) | Sep 20, 2022 |
| Apple         | MacBookAir7,2               | [f9f1973349](https://linux-hardware.org/?probe=f9f1973349) | Sep 20, 2022 |
| Gateway       | NV57H                       | [8fb75d738c](https://linux-hardware.org/?probe=8fb75d738c) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [75cc4fa084](https://linux-hardware.org/?probe=75cc4fa084) | Sep 19, 2022 |
| Acer          | Nitro AN515-42              | [97e2956728](https://linux-hardware.org/?probe=97e2956728) | Sep 19, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [1cbec0f70e](https://linux-hardware.org/?probe=1cbec0f70e) | Sep 19, 2022 |
| Lenovo        | B580 20144                  | [093692b5ab](https://linux-hardware.org/?probe=093692b5ab) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ACH6 82QJ        | [e2c5e4775c](https://linux-hardware.org/?probe=e2c5e4775c) | Sep 19, 2022 |
| Apple         | MacBookPro15,1              | [b0e746792f](https://linux-hardware.org/?probe=b0e746792f) | Sep 19, 2022 |
| Sony          | VPCF236FM                   | [397f485cfc](https://linux-hardware.org/?probe=397f485cfc) | Sep 19, 2022 |
| Dell          | Precision M4800             | [73d00fe344](https://linux-hardware.org/?probe=73d00fe344) | Sep 19, 2022 |
| ASUSTek       | G752VT                      | [bbd1eb7810](https://linux-hardware.org/?probe=bbd1eb7810) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [13b23fabb7](https://linux-hardware.org/?probe=13b23fabb7) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [59369fa3fb](https://linux-hardware.org/?probe=59369fa3fb) | Sep 17, 2022 |
| Dell          | Inspiron MP061              | [f045e1f138](https://linux-hardware.org/?probe=f045e1f138) | Sep 17, 2022 |
| AXDIA Inte... | WINPAD V10                  | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [31c810e744](https://linux-hardware.org/?probe=31c810e744) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [8e62e03e0b](https://linux-hardware.org/?probe=8e62e03e0b) | Sep 15, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [00bcfb51bd](https://linux-hardware.org/?probe=00bcfb51bd) | Sep 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [45309244c3](https://linux-hardware.org/?probe=45309244c3) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| ASUSTek       | X550VXK                     | [df5d5b4f0d](https://linux-hardware.org/?probe=df5d5b4f0d) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c9df1f2514](https://linux-hardware.org/?probe=c9df1f2514) | Sep 13, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [b62bd233c2](https://linux-hardware.org/?probe=b62bd233c2) | Sep 13, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | [dee9d6b81f](https://linux-hardware.org/?probe=dee9d6b81f) | Sep 13, 2022 |
| ASUSTek       | X541UJ                      | [9745e99a08](https://linux-hardware.org/?probe=9745e99a08) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [82b9d1247e](https://linux-hardware.org/?probe=82b9d1247e) | Sep 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Manjaro        | 1488      | 37.32%  |
| Manjaro 22.0.0 | 188       | 4.72%   |
| Manjaro 20.2.1 | 163       | 4.09%   |
| Manjaro 20.1   | 142       | 3.56%   |
| Manjaro 20.2   | 140       | 3.51%   |
| Manjaro 20.0.3 | 125       | 3.14%   |
| Manjaro 21.2.6 | 113       | 2.83%   |
| Manjaro 21.1.0 | 89        | 2.23%   |
| Manjaro 18.1.5 | 83        | 2.08%   |
| Manjaro 21.2.0 | 72        | 1.81%   |
| Manjaro 21.0.7 | 70        | 1.76%   |
| Manjaro 21.2.5 | 65        | 1.63%   |
| Manjaro 21.1.6 | 63        | 1.58%   |
| Manjaro 19.0.2 | 55        | 1.38%   |
| Manjaro 20.0   | 52        | 1.3%    |
| Manjaro 21.2.1 | 48        | 1.2%    |
| Manjaro 18.0.4 | 47        | 1.18%   |
| Manjaro 21.0   | 46        | 1.15%   |
| Manjaro 21.0.5 | 44        | 1.1%    |
| Manjaro 22.1.0 | 41        | 1.03%   |
| Manjaro 20.1.1 | 41        | 1.03%   |
| Manjaro 20.1.2 | 40        | 1%      |
| Manjaro 22.0.4 | 37        | 0.93%   |
| Manjaro 21.2.3 | 37        | 0.93%   |
| Manjaro 20.0.1 | 36        | 0.9%    |
| Manjaro 21.3.7 | 34        | 0.85%   |
| Manjaro 21.2.2 | 31        | 0.78%   |
| Manjaro 21.0.4 | 31        | 0.78%   |
| Manjaro 21.3.6 | 29        | 0.73%   |
| Manjaro 21.2.4 | 29        | 0.73%   |
| Manjaro 21.1.2 | 25        | 0.63%   |
| Manjaro 21.1.4 | 24        | 0.6%    |
| Manjaro 22.0.5 | 23        | 0.58%   |
| Manjaro 21.0.1 | 20        | 0.5%    |
| Manjaro 18.1.4 | 20        | 0.5%    |
| Manjaro 21.3.1 | 19        | 0.48%   |
| Manjaro 21.3.0 | 19        | 0.48%   |
| Manjaro 21.1.3 | 19        | 0.48%   |
| Manjaro 21.1.1 | 19        | 0.48%   |
| Manjaro 22.1.1 | 18        | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Manjaro | 3653      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 161       | 3.75%   |
| 5.13.19-2-MANJARO | 95        | 2.21%   |
| 5.9.11-3-MANJARO  | 73        | 1.7%    |
| 5.8.11-1-MANJARO  | 69        | 1.61%   |
| 5.8.6-1-MANJARO   | 68        | 1.58%   |
| 5.15.32-1-MANJARO | 63        | 1.47%   |
| 5.15.28-1-MANJARO | 61        | 1.42%   |
| 5.10.42-1-MANJARO | 57        | 1.33%   |
| 5.8.18-1-MANJARO  | 55        | 1.28%   |
| 5.15.12-1-MANJARO | 52        | 1.21%   |
| 6.1.1-1-MANJARO   | 51        | 1.19%   |
| 6.1.12-1-MANJARO  | 49        | 1.14%   |
| 5.8.16-2-MANJARO  | 41        | 0.96%   |
| 5.15.65-1-MANJARO | 40        | 0.93%   |
| 5.10.2-2-MANJARO  | 40        | 0.93%   |
| 5.6.16-1-MANJARO  | 39        | 0.91%   |
| 5.15.60-1-MANJARO | 39        | 0.91%   |
| 5.10.7-3-MANJARO  | 38        | 0.89%   |
| 5.12.9-1-MANJARO  | 36        | 0.84%   |
| 5.6.19-2-MANJARO  | 33        | 0.77%   |
| 5.15.74-3-MANJARO | 31        | 0.72%   |
| 5.15.7-1-MANJARO  | 31        | 0.72%   |
| 5.7.9-1-MANJARO   | 30        | 0.7%    |
| 5.6.15-1-MANJARO  | 30        | 0.7%    |
| 5.15.81-1-MANJARO | 30        | 0.7%    |
| 5.15.78-1-MANJARO | 30        | 0.7%    |
| 5.15.41-1-MANJARO | 30        | 0.7%    |
| 5.10.36-2-MANJARO | 30        | 0.7%    |
| 5.7.17-2-MANJARO  | 29        | 0.68%   |
| 5.7.0-3-MANJARO   | 29        | 0.68%   |
| 5.8.3-2-MANJARO   | 28        | 0.65%   |
| 5.15.25-1-MANJARO | 28        | 0.65%   |
| 5.14.10-1-MANJARO | 28        | 0.65%   |
| 5.10.34-1-MANJARO | 27        | 0.63%   |
| 5.16.14-1-MANJARO | 25        | 0.58%   |
| 5.15.85-1-MANJARO | 25        | 0.58%   |
| 5.10.70-1-MANJARO | 25        | 0.58%   |
| 5.10.53-1-MANJARO | 25        | 0.58%   |
| 5.9.3-1-MANJARO   | 23        | 0.54%   |
| 5.17.1-3-MANJARO  | 23        | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.16  | 161       | 3.75%   |
| 5.13.19 | 96        | 2.24%   |
| 5.9.11  | 77        | 1.79%   |
| 5.8.11  | 69        | 1.61%   |
| 5.8.6   | 68        | 1.58%   |
| 5.15.32 | 64        | 1.49%   |
| 5.15.28 | 61        | 1.42%   |
| 5.10.42 | 57        | 1.33%   |
| 5.8.18  | 55        | 1.28%   |
| 5.15.12 | 52        | 1.21%   |
| 6.1.1   | 51        | 1.19%   |
| 6.1.12  | 49        | 1.14%   |
| 5.8.16  | 42        | 0.98%   |
| 5.15.65 | 40        | 0.93%   |
| 5.10.2  | 40        | 0.93%   |
| 5.6.16  | 39        | 0.91%   |
| 5.15.60 | 39        | 0.91%   |
| 5.10.7  | 39        | 0.91%   |
| 5.7.0   | 36        | 0.84%   |
| 5.12.9  | 36        | 0.84%   |
| 5.6.19  | 35        | 0.82%   |
| 5.9.1   | 33        | 0.77%   |
| 5.15.74 | 32        | 0.75%   |
| 5.15.7  | 32        | 0.75%   |
| 5.7.9   | 30        | 0.7%    |
| 5.6.15  | 30        | 0.7%    |
| 5.17.1  | 30        | 0.7%    |
| 5.15.81 | 30        | 0.7%    |
| 5.15.78 | 30        | 0.7%    |
| 5.15.41 | 30        | 0.7%    |
| 5.10.36 | 30        | 0.7%    |
| 5.7.17  | 29        | 0.68%   |
| 5.8.3   | 28        | 0.65%   |
| 5.15.25 | 28        | 0.65%   |
| 5.14.10 | 28        | 0.65%   |
| 5.10.34 | 27        | 0.63%   |
| 5.19.0  | 26        | 0.61%   |
| 5.16.14 | 25        | 0.58%   |
| 5.15.85 | 25        | 0.58%   |
| 5.10.70 | 25        | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 710       | 17.57%  |
| 5.10    | 504       | 12.47%  |
| 5.4     | 357       | 8.83%   |
| 5.9     | 322       | 7.97%   |
| 5.8     | 291       | 7.2%    |
| 6.1     | 274       | 6.78%   |
| 5.13    | 204       | 5.05%   |
| 5.6     | 199       | 4.92%   |
| 5.7     | 137       | 3.39%   |
| 4.19    | 121       | 2.99%   |
| 5.16    | 99        | 2.45%   |
| 5.12    | 94        | 2.33%   |
| 6.0     | 81        | 2%      |
| 5.11    | 81        | 2%      |
| 5.14    | 77        | 1.9%    |
| 5.19    | 74        | 1.83%   |
| 5.17    | 70        | 1.73%   |
| 5.18    | 69        | 1.71%   |
| 5.3     | 64        | 1.58%   |
| 5.5     | 62        | 1.53%   |
| 6.2     | 41        | 1.01%   |
| 4.14    | 25        | 0.62%   |
| 5.2     | 23        | 0.57%   |
| 5.0     | 17        | 0.42%   |
| 6.3     | 13        | 0.32%   |
| 5.1     | 13        | 0.32%   |
| 4.20    | 9         | 0.22%   |
| 4.18    | 7         | 0.17%   |
| 4.9     | 2         | 0.05%   |
| 6.4     | 1         | 0.02%   |
| 4.16    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3651      | 99.95%  |
| i686   | 2         | 0.05%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| KDE5                 | 1338      | 35.6%   |
| XFCE                 | 818       | 21.77%  |
| GNOME                | 808       | 21.5%   |
| KDE                  | 276       | 7.34%   |
| Unknown              | 197       | 5.24%   |
| X-Cinnamon           | 83        | 2.21%   |
| i3                   | 80        | 2.13%   |
| MATE                 | 37        | 0.98%   |
| Cinnamon             | 30        | 0.8%    |
| Deepin               | 25        | 0.67%   |
| Budgie               | 14        | 0.37%   |
| Awesome              | 11        | 0.29%   |
| sway                 | 8         | 0.21%   |
| LXQt                 | 7         | 0.19%   |
| LXDE                 | 6         | 0.16%   |
| i3-with-shmlog       | 3         | 0.08%   |
| leftwm               | 2         | 0.05%   |
| GNOME Flashback      | 2         | 0.05%   |
| DWM                  | 2         | 0.05%   |
| Bspwm                | 2         | 0.05%   |
| Yaru:ubuntu:GNOME    | 1         | 0.03%   |
| xinitrc              | 1         | 0.03%   |
| Unity                | 1         | 0.03%   |
| swayLANG=en_CA.UTF-8 | 1         | 0.03%   |
| qtile                | 1         | 0.03%   |
| Hyprland             | 1         | 0.03%   |
| herbstluftwm         | 1         | 0.03%   |
| GNOME Classic        | 1         | 0.03%   |
| Enlightenment        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3074      | 82.97%  |
| Wayland | 506       | 13.66%  |
| Unknown | 92        | 2.48%   |
| Tty     | 33        | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1476      | 39.48%  |
| SDDM    | 956       | 25.57%  |
| LightDM | 662       | 17.71%  |
| GDM     | 508       | 13.59%  |
| TDM     | 123       | 3.29%   |
| LXDM    | 5         | 0.13%   |
| GREETD  | 4         | 0.11%   |
| Ly      | 2         | 0.05%   |
| XDM     | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |
| CDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1581      | 42.78%  |
| de_DE   | 263       | 7.12%   |
| ru_RU   | 255       | 6.9%    |
| en_GB   | 244       | 6.6%    |
| Unknown | 244       | 6.6%    |
| pt_BR   | 154       | 4.17%   |
| fr_FR   | 98        | 2.65%   |
| it_IT   | 79        | 2.14%   |
| es_ES   | 70        | 1.89%   |
| pl_PL   | 66        | 1.79%   |
| en_CA   | 61        | 1.65%   |
| en_IN   | 56        | 1.52%   |
| es_MX   | 41        | 1.11%   |
| en_AU   | 39        | 1.06%   |
| zh_CN   | 33        | 0.89%   |
| de_AT   | 22        | 0.6%    |
| ru_UA   | 20        | 0.54%   |
| C       | 18        | 0.49%   |
| nl_NL   | 17        | 0.46%   |
| es_AR   | 16        | 0.43%   |
| en_IE   | 15        | 0.41%   |
| tr_TR   | 14        | 0.38%   |
| pt_PT   | 14        | 0.38%   |
| es_CL   | 14        | 0.38%   |
| en_DK   | 13        | 0.35%   |
| cs_CZ   | 13        | 0.35%   |
| uk_UA   | 11        | 0.3%    |
| sv_SE   | 11        | 0.3%    |
| es_CO   | 11        | 0.3%    |
| hu_HU   | 10        | 0.27%   |
| fi_FI   | 10        | 0.27%   |
| en_ZA   | 10        | 0.27%   |
| en_NZ   | 9         | 0.24%   |
| de_CH   | 9         | 0.24%   |
| nl_BE   | 8         | 0.22%   |
| el_GR   | 8         | 0.22%   |
| zh_TW   | 7         | 0.19%   |
| en_PH   | 7         | 0.19%   |
| en_DE   | 7         | 0.19%   |
| en_SG   | 6         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1905      | 51.36%  |
| EFI  | 1804      | 48.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3087      | 83.84%  |
| Btrfs    | 347       | 9.42%   |
| Overlay  | 86        | 2.34%   |
| Unknown  | 82        | 2.23%   |
| Xfs      | 36        | 0.98%   |
| Tmpfs    | 24        | 0.65%   |
| F2fs     | 11        | 0.3%    |
| Reiserfs | 3         | 0.08%   |
| Ext3     | 3         | 0.08%   |
| Ext2     | 2         | 0.05%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1808      | 48.62%  |
| Unknown | 1601      | 43.05%  |
| MBR     | 310       | 8.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3324      | 89.94%  |
| Yes       | 372       | 10.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2625      | 70.77%  |
| Yes       | 1084      | 29.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 913       | 24.99%  |
| Hewlett-Packard      | 625       | 17.11%  |
| Dell                 | 549       | 15.03%  |
| ASUSTek Computer     | 446       | 12.21%  |
| Acer                 | 294       | 8.05%   |
| MSI                  | 107       | 2.93%   |
| Apple                | 91        | 2.49%   |
| Toshiba              | 63        | 1.72%   |
| HUAWEI               | 62        | 1.7%    |
| Samsung Electronics  | 59        | 1.62%   |
| Timi                 | 38        | 1.04%   |
| Sony                 | 32        | 0.88%   |
| Notebook             | 29        | 0.79%   |
| Fujitsu              | 28        | 0.77%   |
| Google               | 26        | 0.71%   |
| Unknown              | 21        | 0.57%   |
| TUXEDO               | 18        | 0.49%   |
| Razer                | 15        | 0.41%   |
| Alienware            | 13        | 0.36%   |
| Schenker             | 12        | 0.33%   |
| LG Electronics       | 10        | 0.27%   |
| HONOR                | 10        | 0.27%   |
| Packard Bell         | 9         | 0.25%   |
| Gigabyte Technology  | 9         | 0.25%   |
| System76             | 8         | 0.22%   |
| Positivo             | 8         | 0.22%   |
| Medion               | 8         | 0.22%   |
| Panasonic            | 7         | 0.19%   |
| Clevo                | 7         | 0.19%   |
| Chuwi                | 7         | 0.19%   |
| Monster              | 6         | 0.16%   |
| Multilaser           | 5         | 0.14%   |
| GPD                  | 5         | 0.14%   |
| Framework            | 5         | 0.14%   |
| Star Labs            | 4         | 0.11%   |
| PC Specialist        | 4         | 0.11%   |
| MECHREVO             | 4         | 0.11%   |
| Intel Client Systems | 4         | 0.11%   |
| TrekStor             | 3         | 0.08%   |
| Gateway              | 3         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 31        | 0.85%   |
| HP Notebook                          | 22        | 0.6%    |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 14        | 0.38%   |
| Lenovo Legion 5 15ARH05 82B5         | 13        | 0.36%   |
| Dell XPS 15 9500                     | 13        | 0.36%   |
| Dell XPS 13 9310                     | 13        | 0.36%   |
| HP Pavilion Notebook                 | 12        | 0.33%   |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 11        | 0.3%    |
| HP Pavilion dv7                      | 10        | 0.27%   |
| HP Laptop 15-bs0xx                   | 10        | 0.27%   |
| Dell Inspiron 3542                   | 10        | 0.27%   |
| HP Pavilion g6                       | 9         | 0.25%   |
| HP Pavilion dv6                      | 9         | 0.25%   |
| HP Pavilion 15                       | 9         | 0.25%   |
| Dell XPS 15 9570                     | 9         | 0.25%   |
| Dell XPS 15 9560                     | 9         | 0.25%   |
| Dell XPS 15 7590                     | 9         | 0.25%   |
| Dell XPS 13 7390                     | 9         | 0.25%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY | 8         | 0.22%   |
| HP OMEN by Laptop                    | 8         | 0.22%   |
| HP 15                                | 8         | 0.22%   |
| Dell Latitude E6430                  | 8         | 0.22%   |
| Dell Inspiron N5110                  | 8         | 0.22%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 8         | 0.22%   |
| Apple MacBookPro9,2                  | 8         | 0.22%   |
| Timi TM1701                          | 7         | 0.19%   |
| Lenovo Z50-70 20354                  | 7         | 0.19%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 7         | 0.19%   |
| Lenovo Y520-15IKBN 80WK              | 7         | 0.19%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 7         | 0.19%   |
| HUAWEI NBLK-WAX9X                    | 7         | 0.19%   |
| HP Laptop 15s-eq2xxx                 | 7         | 0.19%   |
| HP 250 G7 Notebook PC                | 7         | 0.19%   |
| Dell G3 3590                         | 7         | 0.19%   |
| Apple MacBookPro15,1                 | 7         | 0.19%   |
| Apple MacBookAir7,2                  | 7         | 0.19%   |
| Acer Swift SF314-42                  | 7         | 0.19%   |
| Lenovo ThinkBook 15-IIL 20SM         | 6         | 0.16%   |
| Lenovo Legion 5 15ARH05H 82B1        | 6         | 0.16%   |
| Lenovo Legion 5 15ACH6H 82JU         | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 425       | 11.63%  |
| Lenovo IdeaPad        | 247       | 6.76%   |
| Acer Aspire           | 188       | 5.15%   |
| Dell Inspiron         | 174       | 4.76%   |
| HP Pavilion           | 145       | 3.97%   |
| Dell Latitude         | 142       | 3.89%   |
| Dell XPS              | 106       | 2.9%    |
| HP Laptop             | 101       | 2.76%   |
| HP ProBook            | 94        | 2.57%   |
| HP EliteBook          | 90        | 2.46%   |
| ASUS VivoBook         | 75        | 2.05%   |
| Lenovo Legion         | 67        | 1.83%   |
| Toshiba Satellite     | 56        | 1.53%   |
| ASUS ROG              | 56        | 1.53%   |
| Dell Precision        | 46        | 1.26%   |
| Dell Vostro           | 39        | 1.07%   |
| Acer Swift            | 38        | 1.04%   |
| ASUS ZenBook          | 33        | 0.9%    |
| ASUS TUF              | 32        | 0.88%   |
| Unknown               | 31        | 0.85%   |
| Acer Nitro            | 29        | 0.79%   |
| HP OMEN               | 27        | 0.74%   |
| Lenovo ThinkBook      | 26        | 0.71%   |
| HP ENVY               | 26        | 0.71%   |
| ASUS ASUS             | 25        | 0.68%   |
| Fujitsu LIFEBOOK      | 24        | 0.66%   |
| HP Notebook           | 22        | 0.6%    |
| Lenovo Yoga           | 20        | 0.55%   |
| HP ZBook              | 20        | 0.55%   |
| HP 250                | 19        | 0.52%   |
| Timi RedmiBook        | 16        | 0.44%   |
| HP Compaq             | 15        | 0.41%   |
| Dell G3               | 15        | 0.41%   |
| Razer Blade           | 14        | 0.38%   |
| Apple MacBookPro11    | 14        | 0.38%   |
| Acer TravelMate       | 14        | 0.38%   |
| HP 15                 | 13        | 0.36%   |
| Acer Predator         | 12        | 0.33%   |
| HP 255                | 11        | 0.3%    |
| Packard Bell EasyNote | 9         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 492       | 13.47%  |
| 2020    | 477       | 13.06%  |
| 2018    | 379       | 10.38%  |
| 2021    | 344       | 9.42%   |
| 2017    | 291       | 7.97%   |
| 2012    | 266       | 7.28%   |
| 2015    | 213       | 5.83%   |
| 2014    | 207       | 5.67%   |
| 2013    | 207       | 5.67%   |
| 2016    | 196       | 5.37%   |
| 2011    | 195       | 5.34%   |
| 2010    | 111       | 3.04%   |
| 2022    | 101       | 2.76%   |
| 2008    | 72        | 1.97%   |
| 2009    | 54        | 1.48%   |
| 2007    | 27        | 0.74%   |
| 2023    | 9         | 0.25%   |
| 2006    | 8         | 0.22%   |
| Unknown | 3         | 0.08%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3653      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3651      | 99.89%  |
| Enabled  | 4         | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3609      | 98.8%   |
| Yes  | 44        | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1115      | 30.19%  |
| 16.01-24.0  | 791       | 21.42%  |
| 8.01-16.0   | 767       | 20.77%  |
| 3.01-4.0    | 524       | 14.19%  |
| 32.01-64.0  | 291       | 7.88%   |
| 1.01-2.0    | 68        | 1.84%   |
| 24.01-32.0  | 65        | 1.76%   |
| 64.01-256.0 | 43        | 1.16%   |
| 2.01-3.0    | 28        | 0.76%   |
| 0.51-1.0    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1123      | 27.82%  |
| 1.01-2.0   | 1013      | 25.1%   |
| 4.01-8.0   | 804       | 19.92%  |
| 3.01-4.0   | 700       | 17.34%  |
| 8.01-16.0  | 230       | 5.7%    |
| 0.51-1.0   | 135       | 3.34%   |
| 16.01-24.0 | 16        | 0.4%    |
| 24.01-32.0 | 7         | 0.17%   |
| 0.01-0.5   | 7         | 0.17%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2520      | 67.69%  |
| 2      | 1036      | 27.83%  |
| 3      | 132       | 3.55%   |
| 0      | 19        | 0.51%   |
| 4      | 13        | 0.35%   |
| 7      | 2         | 0.05%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2734      | 74.46%  |
| Yes       | 938       | 25.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2803      | 76.46%  |
| No        | 863       | 23.54%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3611      | 98.74%  |
| No        | 46        | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3006      | 81.71%  |
| No        | 673       | 18.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 536       | 14.57%  |
| Germany     | 397       | 10.79%  |
| Russia      | 336       | 9.13%   |
| Brazil      | 225       | 6.12%   |
| France      | 140       | 3.81%   |
| UK          | 125       | 3.4%    |
| Italy       | 124       | 3.37%   |
| Poland      | 111       | 3.02%   |
| Spain       | 98        | 2.66%   |
| India       | 98        | 2.66%   |
| Canada      | 98        | 2.66%   |
| Netherlands | 93        | 2.53%   |
| Ukraine     | 88        | 2.39%   |
| Mexico      | 64        | 1.74%   |
| China       | 53        | 1.44%   |
| Austria     | 51        | 1.39%   |
| Turkey      | 46        | 1.25%   |
| Australia   | 45        | 1.22%   |
| Sweden      | 40        | 1.09%   |
| Indonesia   | 37        | 1.01%   |
| Romania     | 35        | 0.95%   |
| Belgium     | 34        | 0.92%   |
| Switzerland | 33        | 0.9%    |
| Portugal    | 33        | 0.9%    |
| Czechia     | 33        | 0.9%    |
| Belarus     | 29        | 0.79%   |
| Hungary     | 28        | 0.76%   |
| Finland     | 27        | 0.73%   |
| Bulgaria    | 25        | 0.68%   |
| Norway      | 24        | 0.65%   |
| Greece      | 24        | 0.65%   |
| Argentina   | 24        | 0.65%   |
| Colombia    | 22        | 0.6%    |
| Taiwan      | 21        | 0.57%   |
| Denmark     | 21        | 0.57%   |
| Chile       | 19        | 0.52%   |
| Iran        | 18        | 0.49%   |
| Bangladesh  | 18        | 0.49%   |
| Croatia     | 16        | 0.43%   |
| Japan       | 15        | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 78        | 2.01%   |
| St Petersburg     | 49        | 1.26%   |
| Vienna            | 36        | 0.93%   |
| Paris             | 33        | 0.85%   |
| Berlin            | 31        | 0.8%    |
| Sao Paulo         | 27        | 0.7%    |
| Kyiv              | 25        | 0.64%   |
| Amsterdam         | 25        | 0.64%   |
| Warsaw            | 21        | 0.54%   |
| Milan             | 20        | 0.52%   |
| Munich            | 19        | 0.49%   |
| Frankfurt am Main | 18        | 0.46%   |
| Bengaluru         | 18        | 0.46%   |
| Toronto           | 17        | 0.44%   |
| Minsk             | 17        | 0.44%   |
| Istanbul          | 17        | 0.44%   |
| Prague            | 16        | 0.41%   |
| Novosibirsk       | 16        | 0.41%   |
| Helsinki          | 16        | 0.41%   |
| London            | 15        | 0.39%   |
| Rome              | 14        | 0.36%   |
| Mexico City       | 14        | 0.36%   |
| Madrid            | 14        | 0.36%   |
| Hamburg           | 14        | 0.36%   |
| Budapest          | 13        | 0.34%   |
| Bucharest         | 13        | 0.34%   |
| Barcelona         | 13        | 0.34%   |
| Melbourne         | 12        | 0.31%   |
| Dhaka             | 12        | 0.31%   |
| Zagreb            | 11        | 0.28%   |
| Yekaterinburg     | 11        | 0.28%   |
| The Hague         | 11        | 0.28%   |
| Sofia             | 11        | 0.28%   |
| Krasnodar         | 11        | 0.28%   |
| Cologne           | 11        | 0.28%   |
| Athens            | 11        | 0.28%   |
| Sydney            | 10        | 0.26%   |
| Stockholm         | 10        | 0.26%   |
| Seattle           | 10        | 0.26%   |
| San Jose          | 10        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 844       | 1118   | 17.56%  |
| WDC                            | 517       | 625    | 10.76%  |
| Seagate                        | 475       | 613    | 9.88%   |
| Toshiba                        | 363       | 423    | 7.55%   |
| SanDisk                        | 322       | 408    | 6.7%    |
| Kingston                       | 260       | 303    | 5.41%   |
| SK hynix                       | 248       | 303    | 5.16%   |
| Unknown                        | 241       | 295    | 5.01%   |
| Crucial                        | 167       | 207    | 3.47%   |
| Intel                          | 165       | 206    | 3.43%   |
| HGST                           | 142       | 170    | 2.95%   |
| Micron Technology              | 131       | 165    | 2.73%   |
| Hitachi                        | 89        | 104    | 1.85%   |
| KIOXIA                         | 63        | 73     | 1.31%   |
| A-DATA Technology              | 59        | 70     | 1.23%   |
| Apple                          | 57        | 69     | 1.19%   |
| Phison                         | 44        | 65     | 0.92%   |
| China                          | 39        | 42     | 0.81%   |
| Transcend                      | 31        | 37     | 0.64%   |
| Micron/Crucial Technology      | 26        | 33     | 0.54%   |
| LITEONIT                       | 26        | 32     | 0.54%   |
| GOODRAM                        | 26        | 45     | 0.54%   |
| Silicon Motion                 | 24        | 28     | 0.5%    |
| Phison Electronics             | 24        | 24     | 0.5%    |
| LITEON                         | 24        | 27     | 0.5%    |
| JMicron Technology             | 18        | 19     | 0.37%   |
| Plextor                        | 14        | 22     | 0.29%   |
| SPCC                           | 13        | 15     | 0.27%   |
| Kingston Technology Company    | 13        | 13     | 0.27%   |
| Union Memory (Shenzhen)        | 12        | 12     | 0.25%   |
| Patriot                        | 12        | 12     | 0.25%   |
| Intenso                        | 12        | 13     | 0.25%   |
| Solid State Storage Technology | 11        | 18     | 0.23%   |
| ADATA Technology               | 11        | 13     | 0.23%   |
| Fujitsu                        | 10        | 10     | 0.21%   |
| Unknown                        | 10        | 13     | 0.21%   |
| XPG                            | 9         | 15     | 0.19%   |
| Hewlett-Packard                | 9         | 13     | 0.19%   |
| PNY                            | 8         | 12     | 0.17%   |
| Netac                          | 8         | 14     | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 92        | 1.83%   |
| Samsung NVMe SSD Drive 512GB                        | 65        | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 58        | 1.16%   |
| HGST HTS721010A9E630 1TB                            | 52        | 1.04%   |
| Toshiba MQ04ABF100 1TB                              | 51        | 1.02%   |
| Toshiba MQ01ABD100 1TB                              | 51        | 1.02%   |
| SK hynix NVMe SSD Drive 512GB                       | 46        | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 43        | 0.86%   |
| SanDisk NVMe SSD Drive 512GB                        | 43        | 0.86%   |
| Samsung NVMe SSD Drive 256GB                        | 43        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                     | 40        | 0.8%    |
| Toshiba MQ01ABF050 500GB                            | 37        | 0.74%   |
| Unknown MMC Card  32GB                              | 34        | 0.68%   |
| Unknown MMC Card  64GB                              | 31        | 0.62%   |
| Intel NVMe SSD Drive 512GB                          | 30        | 0.6%    |
| Samsung NVMe SSD Drive 1TB                          | 29        | 0.58%   |
| Unknown SD/MMC/MS PRO 64GB                          | 28        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                        | 27        | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                        | 26        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                     | 25        | 0.5%    |
| Seagate ST1000LM049-2GH172 1TB                      | 24        | 0.48%   |
| Kingston SA400S37120G 120GB SSD                     | 24        | 0.48%   |
| HGST HTS545050A7E680 500GB                          | 24        | 0.48%   |
| Samsung SSD 860 EVO 500GB                           | 23        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 23        | 0.46%   |
| Samsung NVMe SSD Drive 1024GB                       | 23        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                     | 23        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                         | 23        | 0.46%   |
| SK hynix NVMe SSD Drive 256GB                       | 22        | 0.44%   |
| Seagate Expansion 1TB                               | 22        | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 22        | 0.44%   |
| Seagate ST9500325AS 500GB                           | 20        | 0.4%    |
| WDC WD10SPZX-21Z10T0 1TB                            | 19        | 0.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 19        | 0.38%   |
| SanDisk NVMe SSD Drive 1TB                          | 19        | 0.38%   |
| Micron NVMe SSD Drive 512GB                         | 19        | 0.38%   |
| Kingston NVMe SSD Drive 512GB                       | 19        | 0.38%   |
| WDC WD10SPZX-24Z10 1TB                              | 18        | 0.36%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 18        | 0.36%   |
| Unknown MMC Card  128GB                             | 18        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 462       | 591    | 34.53%  |
| WDC                 | 336       | 398    | 25.11%  |
| Toshiba             | 230       | 265    | 17.19%  |
| HGST                | 142       | 170    | 10.61%  |
| Hitachi             | 89        | 104    | 6.65%   |
| Unknown             | 30        | 33     | 2.24%   |
| Samsung Electronics | 15        | 17     | 1.12%   |
| Fujitsu             | 10        | 10     | 0.75%   |
| Apple               | 5         | 6      | 0.37%   |
| USB3.0              | 2         | 2      | 0.15%   |
| SSK                 | 2         | 3      | 0.15%   |
| Intenso             | 2         | 2      | 0.15%   |
| QNAP                | 1         | 1      | 0.07%   |
| Pioneer             | 1         | 3      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| MARSHAL             | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Inateck             | 1         | 1      | 0.07%   |
| Hewlett-Packard     | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |
| ASMT                | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 3      | 0.07%   |
| Apricorn            | 1         | 1      | 0.07%   |
| ACASIS              | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 343       | 429    | 23.05%  |
| Kingston            | 188       | 213    | 12.63%  |
| Crucial             | 154       | 194    | 10.35%  |
| SanDisk             | 130       | 170    | 8.74%   |
| WDC                 | 87        | 105    | 5.85%   |
| Micron Technology   | 52        | 67     | 3.49%   |
| SK hynix            | 44        | 53     | 2.96%   |
| A-DATA Technology   | 44        | 50     | 2.96%   |
| China               | 39        | 42     | 2.62%   |
| Apple               | 38        | 43     | 2.55%   |
| Intel               | 37        | 43     | 2.49%   |
| Toshiba             | 31        | 35     | 2.08%   |
| Transcend           | 29        | 34     | 1.95%   |
| LITEONIT            | 26        | 32     | 1.75%   |
| GOODRAM             | 25        | 44     | 1.68%   |
| LITEON              | 21        | 24     | 1.41%   |
| Plextor             | 13        | 21     | 0.87%   |
| Patriot             | 11        | 11     | 0.74%   |
| Intenso             | 10        | 11     | 0.67%   |
| SPCC                | 8         | 9      | 0.54%   |
| Netac               | 8         | 14     | 0.54%   |
| JMicron Technology  | 8         | 8      | 0.54%   |
| PNY                 | 7         | 11     | 0.47%   |
| OCZ                 | 7         | 8      | 0.47%   |
| KingSpec            | 7         | 7      | 0.47%   |
| Seagate             | 6         | 10     | 0.4%    |
| Hewlett-Packard     | 5         | 8      | 0.34%   |
| Corsair             | 5         | 5      | 0.34%   |
| Unknown             | 5         | 8      | 0.34%   |
| TO Exter            | 4         | 5      | 0.27%   |
| SABRENT             | 4         | 4      | 0.27%   |
| Lexar               | 4         | 4      | 0.27%   |
| FORESEE             | 4         | 4      | 0.27%   |
| Apacer              | 4         | 4      | 0.27%   |
| TwinMOS             | 3         | 5      | 0.2%    |
| Team                | 3         | 4      | 0.2%    |
| Mushkin             | 3         | 4      | 0.2%    |
| Vaseky              | 2         | 2      | 0.13%   |
| Unknown             | 2         | 3      | 0.13%   |
| OWC                 | 2         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1607      | 2197   | 35.36%  |
| SSD     | 1387      | 1833   | 30.52%  |
| HDD     | 1287      | 1618   | 28.32%  |
| MMC     | 199       | 247    | 4.38%   |
| Unknown | 65        | 74     | 1.43%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2289      | 3291   | 53.44%  |
| NVMe | 1607      | 2187   | 37.52%  |
| MMC  | 199       | 247    | 4.65%   |
| SAS  | 188       | 244    | 4.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1627      | 2173   | 61.68%  |
| 0.51-1.0   | 905       | 1132   | 34.31%  |
| 1.01-2.0   | 77        | 98     | 2.92%   |
| 3.01-4.0   | 14        | 31     | 0.53%   |
| 4.01-10.0  | 9         | 11     | 0.34%   |
| 10.01-20.0 | 4         | 4      | 0.15%   |
| 2.01-3.0   | 2         | 2      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1007      | 26.58%  |
| 251-500        | 984       | 25.97%  |
| 501-1000       | 598       | 15.78%  |
| 1001-2000      | 307       | 8.1%    |
| Unknown        | 276       | 7.28%   |
| 51-100         | 241       | 6.36%   |
| 1-20           | 135       | 3.56%   |
| 21-50          | 114       | 3.01%   |
| More than 3000 | 67        | 1.77%   |
| 2001-3000      | 60        | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 919       | 23.22%  |
| 21-50          | 747       | 18.87%  |
| 101-250        | 665       | 16.8%   |
| 51-100         | 596       | 15.06%  |
| 251-500        | 413       | 10.43%  |
| Unknown        | 276       | 6.97%   |
| 501-1000       | 231       | 5.84%   |
| 1001-2000      | 76        | 1.92%   |
| More than 3000 | 16        | 0.4%    |
| 2001-3000      | 16        | 0.4%    |
| 0              | 3         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 10        | 11     | 4.69%   |
| HGST HTS545050A7E680 500GB                          | 9         | 9      | 4.23%   |
| HGST HTS721010A9E630 1TB                            | 8         | 8      | 3.76%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 2.82%   |
| HGST HTS545050A7E380 500GB                          | 6         | 6      | 2.82%   |
| Seagate ST500LT012-9WS142 500GB                     | 5         | 22     | 2.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 5      | 2.35%   |
| Seagate ST9320325AS 320GB                           | 4         | 5      | 1.88%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 1.88%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 1.41%   |
| Toshiba MQ01ABD050 500GB                            | 3         | 3      | 1.41%   |
| Seagate ST9500325AS 500GB                           | 3         | 4      | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 1.41%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 3         | 3      | 1.41%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 1.41%   |
| Hitachi HTS723232A7A364 320GB                       | 3         | 3      | 1.41%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 3      | 1.41%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 3      | 0.94%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 2         | 2      | 0.94%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.94%   |
| Seagate ST9750420AS 752GB                           | 2         | 2      | 0.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 2      | 0.94%   |
| Seagate ST1000LX015-1U7172 1TB                      | 2         | 5      | 0.94%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 2      | 0.94%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.94%   |
| HGST HTS541010A9E680 1TB                            | 2         | 2      | 0.94%   |
| Crucial CT525MX300SSD1 528GB                        | 2         | 2      | 0.94%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 1      | 0.47%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 0.47%   |
| WDC WD800BEVS-22RST0 80GB                           | 1         | 1      | 0.47%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 0.47%   |
| WDC WD5000LPVX-08V0TT5 500GB                        | 1         | 1      | 0.47%   |
| WDC WD5000LPLX-00ZNTT0 500GB                        | 1         | 1      | 0.47%   |
| WDC WD5000LPCX-22VHAT0 500GB                        | 1         | 1      | 0.47%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 1         | 1      | 0.47%   |
| WDC WD5000BPVT-60HXZT3 500GB                        | 1         | 1      | 0.47%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 1      | 0.47%   |
| WDC WD5000BEVT-75A0RT0 500GB                        | 1         | 1      | 0.47%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 1      | 0.47%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 1         | 1      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 82     | 25.47%  |
| HGST                | 32        | 32     | 15.09%  |
| WDC                 | 25        | 28     | 11.79%  |
| Toshiba             | 23        | 27     | 10.85%  |
| Hitachi             | 19        | 20     | 8.96%   |
| Samsung Electronics | 10        | 11     | 4.72%   |
| Crucial             | 8         | 11     | 3.77%   |
| SK hynix            | 6         | 10     | 2.83%   |
| SanDisk             | 6         | 6      | 2.83%   |
| Intel               | 5         | 6      | 2.36%   |
| Micron Technology   | 4         | 6      | 1.89%   |
| LITEON              | 3         | 3      | 1.42%   |
| Kingston            | 3         | 3      | 1.42%   |
| A-DATA Technology   | 3         | 4      | 1.42%   |
| TwinMOS             | 1         | 1      | 0.47%   |
| Realtek             | 1         | 1      | 0.47%   |
| MARSHAL             | 1         | 1      | 0.47%   |
| LITEONIT            | 1         | 1      | 0.47%   |
| KingSpec            | 1         | 1      | 0.47%   |
| IM3D                | 1         | 1      | 0.47%   |
| Faspeed             | 1         | 1      | 0.47%   |
| Corsair             | 1         | 1      | 0.47%   |
| ASMT                | 1         | 1      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |
| Unknown             | 1         | 1      | 0.47%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 82     | 36.24%  |
| HGST                | 32        | 32     | 21.48%  |
| WDC                 | 23        | 26     | 15.44%  |
| Toshiba             | 19        | 23     | 12.75%  |
| Hitachi             | 19        | 20     | 12.75%  |
| Samsung Electronics | 1         | 1      | 0.67%   |
| MARSHAL             | 1         | 1      | 0.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 148       | 185    | 70.48%  |
| SSD  | 54        | 66     | 25.71%  |
| NVMe | 8         | 9      | 3.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 33.33%  |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 33.33%  |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 66.67%  |
| Samsung Electronics | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2293      | 3581   | 58.26%  |
| Works    | 1434      | 2125   | 36.43%  |
| Malfunc  | 206       | 260    | 5.23%   |
| Failed   | 3         | 3      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2381      | 52.1%   |
| Samsung Electronics              | 546       | 11.95%  |
| AMD                              | 529       | 11.58%  |
| SanDisk                          | 280       | 6.13%   |
| SK hynix                         | 202       | 4.42%   |
| Toshiba America Info Systems     | 97        | 2.12%   |
| Kingston Technology Company      | 84        | 1.84%   |
| Micron Technology                | 78        | 1.71%   |
| Phison Electronics               | 73        | 1.6%    |
| KIOXIA                           | 71        | 1.55%   |
| Micron/Crucial Technology        | 38        | 0.83%   |
| ADATA Technology                 | 29        | 0.63%   |
| Silicon Motion                   | 26        | 0.57%   |
| Union Memory (Shenzhen)          | 25        | 0.55%   |
| Solid State Storage Technology   | 19        | 0.42%   |
| Nvidia                           | 19        | 0.42%   |
| Apple                            | 13        | 0.28%   |
| Realtek Semiconductor            | 10        | 0.22%   |
| Lite-On Technology               | 10        | 0.22%   |
| Shenzhen Longsys Electronics     | 8         | 0.18%   |
| Marvell Technology Group         | 6         | 0.13%   |
| Seagate Technology               | 4         | 0.09%   |
| Lenovo                           | 4         | 0.09%   |
| Biwin Storage Technology         | 4         | 0.09%   |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| JMicron Technology               | 3         | 0.07%   |
| Transcend                        | 2         | 0.04%   |
| ASMedia Technology               | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 490       | 10.29%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 327       | 6.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 295       | 6.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 254       | 5.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 219       | 4.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 163       | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 162       | 3.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 145       | 3.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 129       | 2.71%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 120       | 2.52%   |
| Samsung NVMe SSD Controller 980                                                | 112       | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 112       | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 91        | 1.91%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 85        | 1.78%   |
| Micron NVMe Storage Controller                                                 | 77        | 1.62%   |
| Intel SSD 660P Series                                                          | 68        | 1.43%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 64        | 1.34%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 61        | 1.28%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 61        | 1.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 60        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 57        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 52        | 1.09%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 50        | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 49        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 48        | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                          | 47        | 0.99%   |
| SK hynix BC511                                                                 | 45        | 0.94%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 40        | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 40        | 0.84%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 40        | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 38        | 0.8%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 36        | 0.76%   |
| SK hynix Non-Volatile memory controller                                        | 33        | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 33        | 0.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 32        | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 31        | 0.65%   |
| Phison E12 NVMe Controller                                                     | 30        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 29        | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 27        | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                        | 26        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2557      | 55.77%  |
| NVMe | 1612      | 35.16%  |
| RAID | 314       | 6.85%   |
| IDE  | 102       | 2.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2831      | 77.5%   |
| AMD    | 822       | 22.5%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 80        | 2.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 68        | 1.86%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 68        | 1.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 66        | 1.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 66        | 1.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 66        | 1.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 65        | 1.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 63        | 1.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 52        | 1.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 51        | 1.39%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 50        | 1.37%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 47        | 1.28%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 1.2%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 43        | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 42        | 1.15%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 41        | 1.12%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 40        | 1.09%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 36        | 0.98%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 0.93%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 33        | 0.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 33        | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 32        | 0.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 32        | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 30        | 0.82%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 29        | 0.79%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 0.77%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 28        | 0.77%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 27        | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 27        | 0.74%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 27        | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.68%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 25        | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 22        | 0.6%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 22        | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 21        | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 960       | 26.24%  |
| Intel Core i7                  | 956       | 26.13%  |
| Other                          | 261       | 7.14%   |
| AMD Ryzen 7                    | 256       | 7%      |
| AMD Ryzen 5                    | 244       | 6.67%   |
| Intel Core i3                  | 243       | 6.64%   |
| Intel Celeron                  | 137       | 3.75%   |
| Intel Core 2 Duo               | 92        | 2.52%   |
| Intel Pentium                  | 79        | 2.16%   |
| AMD Ryzen 3                    | 52        | 1.42%   |
| AMD Ryzen 9                    | 34        | 0.93%   |
| AMD Ryzen 7 PRO                | 33        | 0.9%    |
| AMD A6                         | 27        | 0.74%   |
| AMD A10                        | 25        | 0.68%   |
| Intel Core i9                  | 24        | 0.66%   |
| Intel Atom                     | 24        | 0.66%   |
| AMD A8                         | 22        | 0.6%    |
| Intel Pentium Dual-Core        | 19        | 0.52%   |
| AMD A4                         | 19        | 0.52%   |
| Intel Pentium Silver           | 18        | 0.49%   |
| AMD E1                         | 18        | 0.49%   |
| AMD E                          | 17        | 0.46%   |
| Intel Core 2                   | 11        | 0.3%    |
| AMD E2                         | 9         | 0.25%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.19%   |
| AMD Athlon                     | 7         | 0.19%   |
| Intel Core m3                  | 6         | 0.16%   |
| AMD Ryzen 5 PRO                | 6         | 0.16%   |
| AMD A12                        | 5         | 0.14%   |
| Intel Xeon                     | 4         | 0.11%   |
| Intel Genuine                  | 4         | 0.11%   |
| AMD FX                         | 4         | 0.11%   |
| Intel Core m7                  | 3         | 0.08%   |
| Intel Core m5                  | 3         | 0.08%   |
| AMD Athlon X2                  | 3         | 0.08%   |
| Intel Core M                   | 2         | 0.05%   |
| Intel Core 2 Quad              | 2         | 0.05%   |
| Intel Celeron Dual-Core        | 2         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.05%   |
| AMD Turion II                  | 2         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1548      | 42.35%  |
| 4       | 1348      | 36.88%  |
| 6       | 358       | 9.79%   |
| 8       | 326       | 8.92%   |
| 14      | 26        | 0.71%   |
| 12      | 17        | 0.47%   |
| 1       | 17        | 0.47%   |
| 10      | 8         | 0.22%   |
| 16      | 3         | 0.08%   |
| 3       | 3         | 0.08%   |
| Unknown | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3653      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3014      | 82.46%  |
| 1       | 640       | 17.51%  |
| Unknown | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3590      | 98.22%  |
| Unknown        | 65        | 1.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1823      | 48.29%  |
| 0x306a9    | 144       | 3.81%   |
| 0x906ea    | 118       | 3.13%   |
| 0x806ea    | 116       | 3.07%   |
| 0x806ec    | 105       | 2.78%   |
| 0x806c1    | 92        | 2.44%   |
| 0x206a7    | 80        | 2.12%   |
| 0x806e9    | 79        | 2.09%   |
| 0x406e3    | 73        | 1.93%   |
| 0x40651    | 71        | 1.88%   |
| 0x08108102 | 64        | 1.7%    |
| 0x306c3    | 59        | 1.56%   |
| 0x0a50000c | 57        | 1.51%   |
| 0x306d4    | 56        | 1.48%   |
| 0x08600106 | 54        | 1.43%   |
| 0x906e9    | 53        | 1.4%    |
| 0xa0652    | 47        | 1.25%   |
| 0x08108109 | 45        | 1.19%   |
| 0x08600103 | 43        | 1.14%   |
| 0x806eb    | 42        | 1.11%   |
| 0x706e5    | 39        | 1.03%   |
| 0x08600104 | 38        | 1.01%   |
| 0x1067a    | 31        | 0.82%   |
| 0x08608103 | 31        | 0.82%   |
| 0x20655    | 29        | 0.77%   |
| 0x506e3    | 28        | 0.74%   |
| 0x906a3    | 21        | 0.56%   |
| 0x30678    | 17        | 0.45%   |
| 0x806d1    | 16        | 0.42%   |
| 0x0810100b | 16        | 0.42%   |
| 0x406c4    | 15        | 0.4%    |
| 0x06006705 | 15        | 0.4%    |
| 0x706a1    | 14        | 0.37%   |
| 0x506c9    | 14        | 0.37%   |
| 0x906ed    | 11        | 0.29%   |
| 0x08600102 | 11        | 0.29%   |
| 0x0600611a | 11        | 0.29%   |
| 0x0a50000b | 10        | 0.26%   |
| 0x0a404102 | 10        | 0.26%   |
| 0x06001119 | 10        | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 898       | 24.56%  |
| Haswell          | 291       | 7.96%   |
| IvyBridge        | 266       | 7.28%   |
| Zen 2            | 213       | 5.83%   |
| Skylake          | 207       | 5.66%   |
| SandyBridge      | 205       | 5.61%   |
| Zen+             | 173       | 4.73%   |
| TigerLake        | 159       | 4.35%   |
| Broadwell        | 144       | 3.94%   |
| Unknown          | 135       | 3.69%   |
| Zen 3            | 124       | 3.39%   |
| Penryn           | 95        | 2.6%    |
| Westmere         | 93        | 2.54%   |
| CometLake        | 92        | 2.52%   |
| Silvermont       | 85        | 2.32%   |
| IceLake          | 84        | 2.3%    |
| Excavator        | 58        | 1.59%   |
| Goldmont plus    | 53        | 1.45%   |
| Zen              | 39        | 1.07%   |
| Core             | 37        | 1.01%   |
| Goldmont         | 30        | 0.82%   |
| Alderlake Hybrid | 29        | 0.79%   |
| Bobcat           | 27        | 0.74%   |
| Piledriver       | 24        | 0.66%   |
| Puma             | 23        | 0.63%   |
| Jaguar           | 20        | 0.55%   |
| Nehalem          | 11        | 0.3%    |
| K8 Hammer        | 9         | 0.25%   |
| K10 Llano        | 9         | 0.25%   |
| K10              | 7         | 0.19%   |
| Steamroller      | 5         | 0.14%   |
| K8 & K10 hybrid  | 5         | 0.14%   |
| Bonnell          | 5         | 0.14%   |
| Tremont          | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2634      | 53.77%  |
| Nvidia | 1286      | 26.25%  |
| AMD    | 979       | 19.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 252       | 5.04%   |
| AMD Renoir                                                                               | 203       | 4.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 199       | 3.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 180       | 3.6%    |
| Intel UHD Graphics 620                                                                   | 176       | 3.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 175       | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 159       | 3.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 151       | 3.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 140       | 2.8%    |
| Intel HD Graphics 620                                                                    | 129       | 2.58%   |
| Intel HD Graphics 5500                                                                   | 123       | 2.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 115       | 2.3%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 2.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 104       | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 93        | 1.86%   |
| Intel HD Graphics 630                                                                    | 88        | 1.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 70        | 1.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 70        | 1.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 69        | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 67        | 1.34%   |
| AMD Lucienne                                                                             | 64        | 1.28%   |
| Intel HD Graphics 530                                                                    | 62        | 1.24%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 58        | 1.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 53        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 0.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 45        | 0.9%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 45        | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 43        | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 42        | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 40        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 0.78%   |
| Nvidia TU117M                                                                            | 38        | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 38        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 0.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 38        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 36        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 36        | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 35        | 0.7%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 35        | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 35        | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1547      | 42.24%  |
| Intel + Nvidia     | 961       | 26.24%  |
| 1 x AMD            | 635       | 17.34%  |
| 1 x Nvidia         | 165       | 4.51%   |
| AMD + Nvidia       | 155       | 4.23%   |
| Intel + AMD        | 119       | 3.25%   |
| 2 x AMD            | 72        | 1.97%   |
| 2 x Nvidia         | 3         | 0.08%   |
| Other              | 2         | 0.05%   |
| 2 x Intel          | 2         | 0.05%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2950      | 79.88%  |
| Proprietary | 742       | 20.09%  |
| Unknown     | 1         | 0.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2828      | 76.25%  |
| 0.01-0.5   | 298       | 8.03%   |
| 1.01-2.0   | 241       | 6.5%    |
| 0.51-1.0   | 117       | 3.15%   |
| 3.01-4.0   | 115       | 3.1%    |
| 5.01-6.0   | 57        | 1.54%   |
| 7.01-8.0   | 32        | 0.86%   |
| 2.01-3.0   | 11        | 0.3%    |
| 8.01-16.0  | 9         | 0.24%   |
| 16.01-24.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 732       | 17.01%  |
| LG Display              | 660       | 15.33%  |
| Chimei Innolux          | 641       | 14.89%  |
| BOE                     | 633       | 14.71%  |
| Samsung Electronics     | 341       | 7.92%   |
| Sharp                   | 138       | 3.21%   |
| Dell                    | 118       | 2.74%   |
| Goldstar                | 105       | 2.44%   |
| PANDA                   | 95        | 2.21%   |
| Apple                   | 92        | 2.14%   |
| Chi Mei Optoelectronics | 80        | 1.86%   |
| Lenovo                  | 68        | 1.58%   |
| Hewlett-Packard         | 48        | 1.12%   |
| Philips                 | 40        | 0.93%   |
| Acer                    | 39        | 0.91%   |
| Ancor Communications    | 37        | 0.86%   |
| BenQ                    | 35        | 0.81%   |
| AOC                     | 35        | 0.81%   |
| InfoVision              | 28        | 0.65%   |
| CSO                     | 26        | 0.6%    |
| ViewSonic               | 23        | 0.53%   |
| TMX                     | 19        | 0.44%   |
| LGD                     | 17        | 0.39%   |
| Iiyama                  | 17        | 0.39%   |
| ASUSTek Computer        | 17        | 0.39%   |
| LG Philips              | 16        | 0.37%   |
| Sony                    | 14        | 0.33%   |
| Panasonic               | 11        | 0.26%   |
| CPT                     | 10        | 0.23%   |
| Toshiba                 | 9         | 0.21%   |
| Unknown                 | 8         | 0.19%   |
| NEC Computers           | 7         | 0.16%   |
| Unknown                 | 6         | 0.14%   |
| Insignia                | 6         | 0.14%   |
| HannStar                | 6         | 0.14%   |
| LG Electronics          | 5         | 0.12%   |
| JDI                     | 5         | 0.12%   |
| Sceptre Tech            | 4         | 0.09%   |
| MSI                     | 4         | 0.09%   |
| Mi                      | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 43        | 0.99%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 41        | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 40        | 0.92%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 33        | 0.76%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.48%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 20        | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 20        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 16        | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.37%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.34%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 14        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.32%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 14        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.3%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.28%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 12        | 0.28%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 11        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 11        | 0.25%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 11        | 0.25%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 11        | 0.25%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 11        | 0.25%   |
| AU Optronics LCD Monitor 1920x1080                                       | 11        | 0.25%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 10        | 0.23%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 10        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2007      | 49.9%   |
| 1366x768 (WXGA)    | 986       | 24.52%  |
| 3840x2160 (4K)     | 171       | 4.25%   |
| 1600x900 (HD+)     | 141       | 3.51%   |
| 2560x1440 (QHD)    | 118       | 2.93%   |
| 1280x800 (WXGA)    | 86        | 2.14%   |
| 1920x1200 (WUXGA)  | 69        | 1.72%   |
| 1440x900 (WXGA+)   | 56        | 1.39%   |
| 2560x1600          | 51        | 1.27%   |
| 2880x1800          | 38        | 0.94%   |
| 1680x1050 (WSXGA+) | 35        | 0.87%   |
| 2560x1080          | 27        | 0.67%   |
| 3840x2400          | 23        | 0.57%   |
| Unknown            | 22        | 0.55%   |
| 2160x1440          | 19        | 0.47%   |
| 1280x1024 (SXGA)   | 19        | 0.47%   |
| 3440x1440          | 18        | 0.45%   |
| 1360x768           | 16        | 0.4%    |
| 3200x1800 (QHD+)   | 13        | 0.32%   |
| 3840x1080          | 12        | 0.3%    |
| 3456x2160          | 10        | 0.25%   |
| 3200x2000          | 9         | 0.22%   |
| 2256x1504          | 7         | 0.17%   |
| 3840x1600          | 6         | 0.15%   |
| 1920x540           | 6         | 0.15%   |
| 3000x2000          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 3286x1080          | 4         | 0.1%    |
| 2520x1680          | 4         | 0.1%    |
| 2240x1400          | 4         | 0.1%    |
| 2880x1920          | 3         | 0.07%   |
| 1600x1200          | 3         | 0.07%   |
| 1024x600           | 3         | 0.07%   |
| 3840x1200          | 2         | 0.05%   |
| 3840x1100          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2560x1700          | 2         | 0.05%   |
| 800x1280           | 1         | 0.02%   |
| 7680x1080          | 1         | 0.02%   |
| 720x1280           | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1843      | 43.06%  |
| 13      | 621       | 14.51%  |
| 14      | 535       | 12.5%   |
| 17      | 264       | 6.17%   |
| 27      | 148       | 3.46%   |
| 24      | 137       | 3.2%    |
| 23      | 114       | 2.66%   |
| 12      | 89        | 2.08%   |
| 21      | 88        | 2.06%   |
| Unknown | 78        | 1.82%   |
| 11      | 52        | 1.21%   |
| 16      | 50        | 1.17%   |
| 31      | 47        | 1.1%    |
| 34      | 38        | 0.89%   |
| 18      | 22        | 0.51%   |
| 22      | 19        | 0.44%   |
| 19      | 19        | 0.44%   |
| 84      | 12        | 0.28%   |
| 20      | 12        | 0.28%   |
| 40      | 11        | 0.26%   |
| 32      | 9         | 0.21%   |
| 26      | 8         | 0.19%   |
| 72      | 7         | 0.16%   |
| 37      | 7         | 0.16%   |
| 54      | 6         | 0.14%   |
| 25      | 5         | 0.12%   |
| 52      | 4         | 0.09%   |
| 28      | 4         | 0.09%   |
| 10      | 4         | 0.09%   |
| 74      | 3         | 0.07%   |
| 49      | 3         | 0.07%   |
| 48      | 3         | 0.07%   |
| 42      | 2         | 0.05%   |
| 35      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 8       | 2         | 0.05%   |
| 86      | 1         | 0.02%   |
| 75      | 1         | 0.02%   |
| 65      | 1         | 0.02%   |
| 60      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2717      | 63.99%  |
| 201-300     | 422       | 9.94%   |
| 501-600     | 372       | 8.76%   |
| 351-400     | 315       | 7.42%   |
| 401-500     | 151       | 3.56%   |
| Unknown     | 78        | 1.84%   |
| 601-700     | 71        | 1.67%   |
| 701-800     | 50        | 1.18%   |
| 1501-2000   | 24        | 0.57%   |
| 801-900     | 21        | 0.49%   |
| 1001-1500   | 19        | 0.45%   |
| 901-1000    | 3         | 0.07%   |
| 101-200     | 2         | 0.05%   |
| 1-100       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3174      | 84.41%  |
| 16/10   | 382       | 10.16%  |
| Unknown | 64        | 1.7%    |
| 3/2     | 52        | 1.38%   |
| 21/9    | 48        | 1.28%   |
| 5/4     | 15        | 0.4%    |
| 4/3     | 11        | 0.29%   |
| 32/9    | 7         | 0.19%   |
| 3.40    | 2         | 0.05%   |
| 0.62    | 2         | 0.05%   |
| 6/5     | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1838      | 43.06%  |
| 81-90          | 941       | 22.05%  |
| 201-250        | 297       | 6.96%   |
| 121-130        | 223       | 5.22%   |
| 71-80          | 214       | 5.01%   |
| 301-350        | 153       | 3.58%   |
| 351-500        | 102       | 2.39%   |
| 61-70          | 84        | 1.97%   |
| Unknown        | 78        | 1.83%   |
| 51-60          | 54        | 1.27%   |
| 151-200        | 52        | 1.22%   |
| 111-120        | 45        | 1.05%   |
| More than 1000 | 40        | 0.94%   |
| 251-300        | 40        | 0.94%   |
| 131-140        | 34        | 0.8%    |
| 141-150        | 27        | 0.63%   |
| 501-1000       | 24        | 0.56%   |
| 91-100         | 15        | 0.35%   |
| 41-50          | 4         | 0.09%   |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1912      | 45.56%  |
| 101-120       | 1083      | 25.8%   |
| 51-100        | 599       | 14.27%  |
| 161-240       | 326       | 7.77%   |
| More than 240 | 160       | 3.81%   |
| Unknown       | 78        | 1.86%   |
| 1-50          | 39        | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2976      | 79.87%  |
| 2     | 661       | 17.74%  |
| 3     | 65        | 1.74%   |
| 0     | 17        | 0.46%   |
| 4     | 7         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2038      | 35.57%  |
| Realtek Semiconductor             | 2020      | 35.25%  |
| Qualcomm Atheros                  | 765       | 13.35%  |
| Broadcom                          | 275       | 4.8%    |
| MediaTek                          | 84        | 1.47%   |
| Broadcom Limited                  | 74        | 1.29%   |
| Ralink                            | 44        | 0.77%   |
| TP-Link                           | 35        | 0.61%   |
| Ralink Technology                 | 34        | 0.59%   |
| ASIX Electronics                  | 31        | 0.54%   |
| Sierra Wireless                   | 29        | 0.51%   |
| Marvell Technology Group          | 26        | 0.45%   |
| Xiaomi                            | 24        | 0.42%   |
| Lenovo                            | 23        | 0.4%    |
| Dell                              | 22        | 0.38%   |
| DisplayLink                       | 19        | 0.33%   |
| Hewlett-Packard                   | 16        | 0.28%   |
| Qualcomm                          | 15        | 0.26%   |
| Huawei Technologies               | 15        | 0.26%   |
| JMicron Technology                | 14        | 0.24%   |
| Samsung Electronics               | 12        | 0.21%   |
| Ericsson Business Mobile Networks | 11        | 0.19%   |
| Nvidia                            | 9         | 0.16%   |
| ASUSTek Computer                  | 9         | 0.16%   |
| Fibocom                           | 8         | 0.14%   |
| Qualcomm Atheros Communications   | 7         | 0.12%   |
| Linksys                           | 7         | 0.12%   |
| NetGear                           | 6         | 0.1%    |
| D-Link                            | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 5         | 0.09%   |
| Google                            | 5         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 4         | 0.07%   |
| Edimax Technology                 | 4         | 0.07%   |
| Apple                             | 4         | 0.07%   |
| Quectel Wireless Solutions        | 3         | 0.05%   |
| ZyXEL Communications              | 2         | 0.03%   |
| Spreadtrum Communications         | 2         | 0.03%   |
| OPPO Electronics                  | 2         | 0.03%   |
| Motorola PCS                      | 2         | 0.03%   |
| Microsoft                         | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1296      | 18.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 316       | 4.63%   |
| Intel Wi-Fi 6 AX200                                               | 285       | 4.17%   |
| Intel Wireless 8265 / 8275                                        | 183       | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 172       | 2.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 152       | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 147       | 2.15%   |
| Intel Wireless 7260                                               | 130       | 1.9%    |
| Intel Wireless 7265                                               | 128       | 1.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 123       | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 121       | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 121       | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 116       | 1.7%    |
| Intel Wi-Fi 6 AX201                                               | 116       | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 106       | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 94        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 90        | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 85        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 84        | 1.23%   |
| Intel Wireless 8260                                               | 83        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 78        | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 72        | 1.05%   |
| Intel Wireless 3165                                               | 66        | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 64        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 58        | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 49        | 0.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 46        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 43        | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 43        | 0.63%   |
| Intel Wireless 3160                                               | 41        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 41        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 41        | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 41        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 40        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 39        | 0.57%   |
| Intel Wireless-AC 9260                                            | 38        | 0.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 38        | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 37        | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 37        | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 35        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1982      | 52.08%  |
| Qualcomm Atheros                      | 642       | 16.87%  |
| Realtek Semiconductor                 | 611       | 16.05%  |
| Broadcom                              | 213       | 5.6%    |
| MediaTek                              | 77        | 2.02%   |
| Broadcom Limited                      | 57        | 1.5%    |
| Ralink                                | 44        | 1.16%   |
| Ralink Technology                     | 34        | 0.89%   |
| Sierra Wireless                       | 29        | 0.76%   |
| TP-Link                               | 28        | 0.74%   |
| Dell                                  | 16        | 0.42%   |
| Qualcomm                              | 9         | 0.24%   |
| Fibocom                               | 8         | 0.21%   |
| Qualcomm Atheros Communications       | 7         | 0.18%   |
| Linksys                               | 7         | 0.18%   |
| ASUSTek Computer                      | 7         | 0.18%   |
| NetGear                               | 6         | 0.16%   |
| D-Link                                | 6         | 0.16%   |
| Hewlett-Packard                       | 5         | 0.13%   |
| Edimax Technology                     | 4         | 0.11%   |
| Quectel Wireless Solutions            | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.05%   |
| Microsoft                             | 2         | 0.05%   |
| ZyDAS                                 | 1         | 0.03%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| D-Link System                         | 1         | 0.03%   |
| Belkin Components                     | 1         | 0.03%   |
| Apple                                 | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 285       | 7.43%   |
| Intel Wireless 8265 / 8275                                     | 183       | 4.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 172       | 4.49%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 147       | 3.83%   |
| Intel Wireless 7260                                            | 130       | 3.39%   |
| Intel Wireless 7265                                            | 128       | 3.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 121       | 3.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 121       | 3.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 116       | 3.03%   |
| Intel Wi-Fi 6 AX201                                            | 116       | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 106       | 2.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 94        | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 90        | 2.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 85        | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 84        | 2.19%   |
| Intel Wireless 8260                                            | 83        | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 78        | 2.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 72        | 1.88%   |
| Intel Wireless 3165                                            | 66        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 64        | 1.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 58        | 1.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 49        | 1.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 46        | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 43        | 1.12%   |
| Intel Wireless 3160                                            | 41        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 41        | 1.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 41        | 1.07%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 40        | 1.04%   |
| Intel Wireless-AC 9260                                         | 38        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 38        | 0.99%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 37        | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                  | 37        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 34        | 0.89%   |
| Intel Centrino Wireless-N 2230                                 | 34        | 0.89%   |
| Intel Centrino Advanced-N 6235                                 | 33        | 0.86%   |
| Intel Centrino Ultimate-N 6300                                 | 27        | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                     | 24        | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 23        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 22        | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 22        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1794      | 61.63%  |
| Intel                                  | 593       | 20.37%  |
| Qualcomm Atheros                       | 191       | 6.56%   |
| Broadcom                               | 98        | 3.37%   |
| ASIX Electronics                       | 31        | 1.06%   |
| Marvell Technology Group               | 26        | 0.89%   |
| Xiaomi                                 | 23        | 0.79%   |
| Lenovo                                 | 23        | 0.79%   |
| Broadcom Limited                       | 20        | 0.69%   |
| DisplayLink                            | 19        | 0.65%   |
| JMicron Technology                     | 14        | 0.48%   |
| Nvidia                                 | 9         | 0.31%   |
| TP-Link                                | 7         | 0.24%   |
| Samsung Electronics                    | 7         | 0.24%   |
| MediaTek                               | 7         | 0.24%   |
| Huawei Technologies                    | 7         | 0.24%   |
| Qualcomm                               | 6         | 0.21%   |
| Google                                 | 5         | 0.17%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.14%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.14%   |
| Hewlett-Packard                        | 3         | 0.1%    |
| Apple                                  | 3         | 0.1%    |
| Spreadtrum Communications              | 2         | 0.07%   |
| OPPO Electronics                       | 2         | 0.07%   |
| Motorola PCS                           | 2         | 0.07%   |
| ICS Advent                             | 2         | 0.07%   |
| Attansic Technology                    | 2         | 0.07%   |
| ASUSTek Computer                       | 2         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| HTC (High Tech Computer)               | 1         | 0.03%   |
| Foxconn / Hon Hai                      | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1296      | 43.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 316       | 10.71%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 152       | 5.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 123       | 4.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 43        | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 41        | 1.39%   |
| Intel Ethernet Connection (4) I219-V                              | 39        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 35        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 34        | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 34        | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 28        | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 24        | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 0.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 0.68%   |
| Intel Ethernet Connection (7) I219-LM                             | 20        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 19        | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 18        | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 18        | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 17        | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 14        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 14        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13        | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.44%   |
| Intel Ethernet Connection I217-V                                  | 12        | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 11        | 0.37%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.34%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.34%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.34%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3611      | 56%     |
| Ethernet | 2795      | 43.35%  |
| Modem    | 40        | 0.62%   |
| Unknown  | 2         | 0.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3132      | 81.31%  |
| Ethernet | 720       | 18.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2536      | 69.35%  |
| 1     | 1052      | 28.77%  |
| 0     | 38        | 1.04%   |
| 3     | 31        | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3114      | 83.87%  |
| Yes  | 599       | 16.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1624      | 53.56%  |
| Realtek Semiconductor           | 355       | 11.71%  |
| Qualcomm Atheros Communications | 301       | 9.93%   |
| IMC Networks                    | 158       | 5.21%   |
| Lite-On Technology              | 134       | 4.42%   |
| Broadcom                        | 99        | 3.27%   |
| Foxconn / Hon Hai               | 79        | 2.61%   |
| Apple                           | 75        | 2.47%   |
| Realtek                         | 39        | 1.29%   |
| Cambridge Silicon Radio         | 34        | 1.12%   |
| Dell                            | 24        | 0.79%   |
| Ralink                          | 23        | 0.76%   |
| Hewlett-Packard                 | 19        | 0.63%   |
| Toshiba                         | 14        | 0.46%   |
| Foxconn International           | 9         | 0.3%    |
| ASUSTek Computer                | 8         | 0.26%   |
| Opticis                         | 7         | 0.23%   |
| Ralink Technology               | 6         | 0.2%    |
| Alps Electric                   | 5         | 0.16%   |
| MediaTek                        | 4         | 0.13%   |
| Askey Computer                  | 4         | 0.13%   |
| TP-Link                         | 2         | 0.07%   |
| Fujitsu                         | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| USI                             | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Dynex                           | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 586       | 19.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 280       | 9.23%   |
| Intel AX200 Bluetooth                               | 275       | 9.06%   |
| Intel AX201 Bluetooth                               | 261       | 8.6%    |
| Realtek Bluetooth Radio                             | 218       | 7.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 148       | 4.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 92        | 3.03%   |
| IMC Networks Bluetooth Radio                        | 64        | 2.11%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 1.98%   |
| Intel Bluetooth Device                              | 50        | 1.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 47        | 1.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1.45%   |
| Intel AX210 Bluetooth                               | 44        | 1.45%   |
| Apple Bluetooth Host Controller                     | 41        | 1.35%   |
| Realtek Bluetooth Radio                             | 39        | 1.29%   |
| Lite-On Bluetooth Device                            | 38        | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 1.25%   |
| IMC Networks Bluetooth Device                       | 37        | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 35        | 1.15%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 1.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 34        | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                  | 30        | 0.99%   |
| IMC Networks Wireless_Device                        | 29        | 0.96%   |
| Apple Bluetooth USB Host Controller                 | 28        | 0.92%   |
| Ralink RT3290 Bluetooth                             | 23        | 0.76%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 21        | 0.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 15        | 0.49%   |
| Realtek RTL8821A Bluetooth                          | 15        | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.43%   |
| Lite-On Wireless_Device                             | 13        | 0.43%   |
| Broadcom HP Portable SoftSailing                    | 13        | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.4%    |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.36%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 10        | 0.33%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 10        | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 9         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2786      | 61.98%  |
| AMD                                  | 884       | 19.67%  |
| Nvidia                               | 528       | 11.75%  |
| C-Media Electronics                  | 36        | 0.8%    |
| Realtek Semiconductor                | 26        | 0.58%   |
| Logitech                             | 23        | 0.51%   |
| Lenovo                               | 22        | 0.49%   |
| GN Netcom                            | 17        | 0.38%   |
| Kingston Technology                  | 13        | 0.29%   |
| JMTek                                | 13        | 0.29%   |
| Plantronics                          | 10        | 0.22%   |
| Texas Instruments                    | 9         | 0.2%    |
| SteelSeries ApS                      | 9         | 0.2%    |
| Generalplus Technology               | 9         | 0.2%    |
| Apple                                | 8         | 0.18%   |
| Focusrite-Novation                   | 7         | 0.16%   |
| Samson Technologies                  | 5         | 0.11%   |
| Razer USA                            | 5         | 0.11%   |
| Hewlett-Packard                      | 5         | 0.11%   |
| GYROCOM C&C                          | 5         | 0.11%   |
| Creative Technology                  | 4         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.07%   |
| RODE Microphones                     | 3         | 0.07%   |
| Huawei Technologies                  | 3         | 0.07%   |
| DSEA A/S                             | 3         | 0.07%   |
| Corsair                              | 3         | 0.07%   |
| Sony                                 | 2         | 0.04%   |
| Sennheiser Communications            | 2         | 0.04%   |
| Samsung Electronics                  | 2         | 0.04%   |
| DCMT Technology                      | 2         | 0.04%   |
| Cambridge Silicon Radio              | 2         | 0.04%   |
| Blue Microphones                     | 2         | 0.04%   |
| ASUSTek Computer                     | 2         | 0.04%   |
| Astro Gaming                         | 2         | 0.04%   |
| Alesis                               | 2         | 0.04%   |
| Yealink Network Technology           | 1         | 0.02%   |
| Yamaha                               | 1         | 0.02%   |
| VIA Technologies                     | 1         | 0.02%   |
| Turtle Beach                         | 1         | 0.02%   |
| Trust                                | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 618       | 11.02%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 458       | 8.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 311       | 5.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 299       | 5.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 214       | 3.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 190       | 3.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 172       | 3.07%   |
| Intel 8 Series HD Audio Controller                                                                | 161       | 2.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 160       | 2.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 159       | 2.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 156       | 2.78%   |
| Intel Broadwell-U Audio Controller                                                                | 144       | 2.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 143       | 2.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 129       | 2.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 108       | 1.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 104       | 1.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 99        | 1.77%   |
| Intel CM238 HD Audio Controller                                                                   | 98        | 1.75%   |
| AMD FCH Azalia Controller                                                                         | 91        | 1.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 80        | 1.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 74        | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 71        | 1.27%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 69        | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 68        | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                                          | 68        | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 57        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 55        | 0.98%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 53        | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 48        | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 47        | 0.84%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 42        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 41        | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 35        | 0.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 35        | 0.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 33        | 0.59%   |
| AMD High Definition Audio Controller                                                              | 33        | 0.59%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 32        | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 32        | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 30        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 867       | 31.71%  |
| SK hynix            | 580       | 21.21%  |
| Micron Technology   | 380       | 13.9%   |
| Kingston            | 248       | 9.07%   |
| Crucial             | 131       | 4.79%   |
| Unknown             | 101       | 3.69%   |
| A-DATA Technology   | 64        | 2.34%   |
| Ramaxel Technology  | 63        | 2.3%    |
| Elpida              | 46        | 1.68%   |
| Corsair             | 36        | 1.32%   |
| Nanya Technology    | 31        | 1.13%   |
| G.Skill             | 24        | 0.88%   |
| Smart               | 17        | 0.62%   |
| Transcend           | 16        | 0.59%   |
| GOODRAM             | 16        | 0.59%   |
| Unknown (ABCD)      | 15        | 0.55%   |
| Patriot             | 12        | 0.44%   |
| Unknown             | 10        | 0.37%   |
| Team                | 9         | 0.33%   |
| Apacer              | 7         | 0.26%   |
| ASint Technology    | 6         | 0.22%   |
| AMD                 | 5         | 0.18%   |
| Teikon              | 4         | 0.15%   |
| Goldkey             | 4         | 0.15%   |
| Smart Brazil        | 3         | 0.11%   |
| Silicon Power       | 3         | 0.11%   |
| SHARETRONIC         | 3         | 0.11%   |
| Avant               | 3         | 0.11%   |
| Atermiter           | 3         | 0.11%   |
| Timetec             | 2         | 0.07%   |
| Qumo                | 2         | 0.07%   |
| Qimonda             | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| V-Color             | 1         | 0.04%   |
| Unknown (768A)      | 1         | 0.04%   |
| Unknown (0x8AF1)    | 1         | 0.04%   |
| Unknown (0x0B6B)    | 1         | 0.04%   |
| Unknown (0x02BA)    | 1         | 0.04%   |
| Unknown (08B5)      | 1         | 0.04%   |
| Unknown (08AE)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 57        | 1.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 53        | 1.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 1.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 1.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 37        | 1.29%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 34        | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 33        | 1.15%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 29        | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 28        | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 26        | 0.9%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 26        | 0.9%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 26        | 0.9%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.87%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 25        | 0.87%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.83%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.8%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 19        | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.66%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.63%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 13        | 0.45%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 13        | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 13        | 0.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.45%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 13        | 0.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 13        | 0.45%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 12        | 0.42%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 12        | 0.42%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 11        | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1264      | 55.58%  |
| DDR3    | 683       | 30.04%  |
| LPDDR4  | 116       | 5.1%    |
| LPDDR3  | 101       | 4.44%   |
| SDRAM   | 34        | 1.5%    |
| DDR2    | 32        | 1.41%   |
| DDR5    | 26        | 1.14%   |
| LPDDR5  | 10        | 0.44%   |
| Unknown | 4         | 0.18%   |
| DRAM    | 2         | 0.09%   |
| DDR     | 2         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1977      | 86.63%  |
| Row Of Chips | 271       | 11.88%  |
| Chip         | 18        | 0.79%   |
| Unknown      | 10        | 0.44%   |
| DIMM         | 6         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1085      | 43.61%  |
| 4096  | 769       | 30.91%  |
| 16384 | 354       | 14.23%  |
| 2048  | 190       | 7.64%   |
| 32768 | 62        | 2.49%   |
| 1024  | 27        | 1.09%   |
| 512   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 626       | 25.19%  |
| 1600    | 527       | 21.21%  |
| 3200    | 472       | 18.99%  |
| 2400    | 209       | 8.41%   |
| 2133    | 153       | 6.16%   |
| 1334    | 93        | 3.74%   |
| 1333    | 58        | 2.33%   |
| 3266    | 53        | 2.13%   |
| 4267    | 48        | 1.93%   |
| 1867    | 33        | 1.33%   |
| 4800    | 26        | 1.05%   |
| 1067    | 26        | 1.05%   |
| 4199    | 25        | 1.01%   |
| Unknown | 22        | 0.89%   |
| 667     | 20        | 0.8%    |
| 4266    | 18        | 0.72%   |
| 800     | 11        | 0.44%   |
| 6400    | 9         | 0.36%   |
| 975     | 9         | 0.36%   |
| 3733    | 7         | 0.28%   |
| 2048    | 7         | 0.28%   |
| 1066    | 7         | 0.28%   |
| 8400    | 6         | 0.24%   |
| 2933    | 3         | 0.12%   |
| 1866    | 3         | 0.12%   |
| 3000    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 333     | 2         | 0.08%   |
| 65535   | 1         | 0.04%   |
| 5200    | 1         | 0.04%   |
| 3600    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 2134    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 666     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 27.59%  |
| Seiko Epson         | 7         | 24.14%  |
| Canon               | 4         | 13.79%  |
| Brother Industries  | 4         | 13.79%  |
| Samsung Electronics | 2         | 6.9%    |
| Xiaomi              | 1         | 3.45%   |
| Sagem               | 1         | 3.45%   |
| Kyocera             | 1         | 3.45%   |
| Dymo-CoStar         | 1         | 3.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| HP ENVY 4520 series                                    | 2         | 6.9%    |
| Brother HL-L2300D series                               | 2         | 6.9%    |
| Xiaomi MiMouse 2                                       | 1         | 3.45%   |
| Seiko Epson Printer                                    | 1         | 3.45%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 3.45%   |
| Seiko Epson L4260 Series                               | 1         | 3.45%   |
| Seiko Epson L365 Series                                | 1         | 3.45%   |
| Seiko Epson L355 Series                                | 1         | 3.45%   |
| Seiko Epson ET-2810 Series                             | 1         | 3.45%   |
| Seiko Epson ET-2710 Series                             | 1         | 3.45%   |
| Samsung ML-1865                                        | 1         | 3.45%   |
| Samsung CLX-3180 Series                                | 1         | 3.45%   |
| Sagem Laser Pro LL                                     | 1         | 3.45%   |
| Kyocera FS-1030D printer                               | 1         | 3.45%   |
| HP Officejet 4500 G510g-m                              | 1         | 3.45%   |
| HP LaserJet P1102                                      | 1         | 3.45%   |
| HP Ink Tank Wireless 410 series                        | 1         | 3.45%   |
| HP Ink Tank 310 series                                 | 1         | 3.45%   |
| HP DeskJet 2700 series                                 | 1         | 3.45%   |
| HP DeskJet 1110 series                                 | 1         | 3.45%   |
| Dymo-CoStar DYMO LabelWriter 450 Twin Turbo            | 1         | 3.45%   |
| Canon TS300 series                                     | 1         | 3.45%   |
| Canon TR4500 series                                    | 1         | 3.45%   |
| Canon PIXMA MG3600 Series                              | 1         | 3.45%   |
| Canon G4010 series                                     | 1         | 3.45%   |
| Brother QL-500 label printer                           | 1         | 3.45%   |
| Brother MFC-L2710DW series                             | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 7         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20     | 2         | 28.57%  |
| Canon CanoScan LiDE 220                | 2         | 28.57%  |
| Canon CanoScan LiDE 500F               | 1         | 14.29%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 14.29%  |
| Canon CanoScan LiDE 110                | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 793       | 23.74%  |
| IMC Networks                           | 467       | 13.98%  |
| Realtek Semiconductor                  | 280       | 8.38%   |
| Microdia                               | 268       | 8.02%   |
| Quanta                                 | 201       | 6.02%   |
| Sunplus Innovation Technology          | 172       | 5.15%   |
| Bison Electronics                      | 148       | 4.43%   |
| Acer                                   | 148       | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 129       | 3.86%   |
| Lite-On Technology                     | 102       | 3.05%   |
| Syntek                                 | 100       | 2.99%   |
| Suyin                                  | 88        | 2.63%   |
| Apple                                  | 61        | 1.83%   |
| Silicon Motion                         | 54        | 1.62%   |
| Logitech                               | 46        | 1.38%   |
| Luxvisions Innotech Limited            | 45        | 1.35%   |
| Alcor Micro                            | 38        | 1.14%   |
| Samsung Electronics                    | 22        | 0.66%   |
| Ricoh                                  | 20        | 0.6%    |
| Lenovo                                 | 14        | 0.42%   |
| Sonix Technology                       | 13        | 0.39%   |
| Microsoft                              | 11        | 0.33%   |
| Importek                               | 11        | 0.33%   |
| Primax Electronics                     | 10        | 0.3%    |
| DigiTech                               | 7         | 0.21%   |
| ALi                                    | 6         | 0.18%   |
| SunplusIT                              | 5         | 0.15%   |
| Intel                                  | 5         | 0.15%   |
| icSpring                               | 5         | 0.15%   |
| Denron                                 | 5         | 0.15%   |
| Z-Star Microelectronics                | 4         | 0.12%   |
| OmniVision Technologies                | 4         | 0.12%   |
| Genesys Logic                          | 4         | 0.12%   |
| GEMBIRD                                | 4         | 0.12%   |
| Y Media                                | 3         | 0.09%   |
| MacroSilicon                           | 3         | 0.09%   |
| Creative Technology                    | 3         | 0.09%   |
| ARC International                      | 3         | 0.09%   |
| webcam                                 | 2         | 0.06%   |
| USB Camera CS                          | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 206       | 6.15%   |
| IMC Networks Integrated Camera                      | 148       | 4.42%   |
| Microdia Integrated_Webcam_HD                       | 138       | 4.12%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 117       | 3.49%   |
| Realtek Integrated_Webcam_HD                        | 101       | 3.01%   |
| Chicony HD WebCam                                   | 85        | 2.54%   |
| Syntek Integrated Camera                            | 65        | 1.94%   |
| Sunplus Integrated_Webcam_HD                        | 57        | 1.7%    |
| Bison Integrated Camera                             | 51        | 1.52%   |
| Acer Integrated Camera                              | 46        | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 43        | 1.28%   |
| Lite-On Integrated Camera                           | 38        | 1.13%   |
| Quanta HP TrueVision HD Camera                      | 35        | 1.04%   |
| Acer HD Webcam                                      | 33        | 0.98%   |
| Quanta HD User Facing                               | 30        | 0.89%   |
| Chicony USB2.0 Camera                               | 29        | 0.87%   |
| Lite-On HP HD Camera                                | 28        | 0.84%   |
| Chicony HP HD Camera                                | 27        | 0.81%   |
| Chicony HD User Facing                              | 25        | 0.75%   |
| Bison SunplusIT Integrated Camera                   | 25        | 0.75%   |
| Microdia Integrated Webcam                          | 24        | 0.72%   |
| Chicony USB2.0 HD UVC WebCam                        | 24        | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)             | 22        | 0.66%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 22        | 0.66%   |
| IMC Networks HD Camera                              | 22        | 0.66%   |
| Chicony Lenovo EasyCamera                           | 22        | 0.66%   |
| Chicony HP Truevision HD                            | 22        | 0.66%   |
| Realtek USB Camera                                  | 21        | 0.63%   |
| Chicony HP TrueVision HD Camera                     | 21        | 0.63%   |
| Chicony EasyCamera                                  | 21        | 0.63%   |
| Syntek Lenovo EasyCamera                            | 20        | 0.6%    |
| Sunplus HD WebCam                                   | 20        | 0.6%    |
| IMC Networks HP TrueVision HD Camera                | 20        | 0.6%    |
| Quanta HD Webcam                                    | 19        | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD                | 19        | 0.57%   |
| Chicony Integrated Camera (1280x720@30)             | 19        | 0.57%   |
| Chicony HP Wide Vision HD Camera                    | 19        | 0.57%   |
| Realtek HD WebCam                                   | 18        | 0.54%   |
| Quanta VGA WebCam                                   | 18        | 0.54%   |
| Quanta HP Wide Vision HD Camera                     | 18        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 239       | 31.7%   |
| Synaptics                          | 200       | 26.53%  |
| Shenzhen Goodix Technology         | 158       | 20.95%  |
| Elan Microelectronics              | 56        | 7.43%   |
| LighTuning Technology              | 35        | 4.64%   |
| Upek                               | 27        | 3.58%   |
| AuthenTec                          | 21        | 2.79%   |
| STMicroelectronics                 | 7         | 0.93%   |
| Focal-systems.Corp                 | 4         | 0.53%   |
| Samsung Electronics                | 3         | 0.4%    |
| DigitalPersona                     | 2         | 0.27%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.13%   |
| HOLTEK                             | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 86        | 11.41%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 64        | 8.49%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 50        | 6.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 43        | 5.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 36        | 4.77%   |
| Elan ELAN:Fingerprint                                                      | 36        | 4.77%   |
| Shenzhen Goodix FingerPrint                                                | 29        | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 27        | 3.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.18%   |
| Validity Sensors Synaptics WBDI                                            | 23        | 3.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 3.05%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 21        | 2.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.52%   |
| Elan ELAN:ARM-M4                                                           | 19        | 2.52%   |
| Validity Sensors VFS491                                                    | 16        | 2.12%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 16        | 2.12%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.99%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.86%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 14        | 1.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.59%   |
| Synaptics UWP WBDI                                                         | 10        | 1.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.19%   |
| Synaptics WBDI                                                             | 9         | 1.19%   |
| Synaptics  WBDI                                                            | 9         | 1.19%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.19%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.93%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.93%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 0.8%    |
| Synaptics UWP WBDI Device                                                  | 6         | 0.8%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.66%   |
| Synaptics WBDI Device                                                      | 5         | 0.66%   |
| AuthenTec AES2810                                                          | 5         | 0.66%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.53%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.53%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 0.53%   |
| Unknown                                                                    | 4         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 91        | 37.3%   |
| Alcor Micro               | 86        | 35.25%  |
| Upek                      | 16        | 6.56%   |
| O2 Micro                  | 16        | 6.56%   |
| Lenovo                    | 16        | 6.56%   |
| Yubico.com                | 8         | 3.28%   |
| Gemalto (was Gemplus)     | 4         | 1.64%   |
| Reiner SCT Kartensysteme  | 1         | 0.41%   |
| OmniKey                   | 1         | 0.41%   |
| Hewlett-Packard           | 1         | 0.41%   |
| Clay Logic                | 1         | 0.41%   |
| C3PO                      | 1         | 0.41%   |
| Aladdin Knowledge Systems | 1         | 0.41%   |
| Advanced Card Systems     | 1         | 0.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 86        | 35.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 14.34%  |
| Broadcom 5880                                                                | 26        | 10.66%  |
| Broadcom 58200                                                               | 18        | 7.38%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 6.56%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 6.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 6.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 4.92%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.87%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.41%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.41%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.41%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.41%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.41%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.41%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.41%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.41%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2216      | 59.39%  |
| 1     | 1204      | 32.27%  |
| 2     | 285       | 7.64%   |
| 3     | 23        | 0.62%   |
| 4     | 3         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 739       | 41.19%  |
| Graphics card            | 346       | 19.29%  |
| Chipcard                 | 220       | 12.26%  |
| Multimedia controller    | 149       | 8.31%   |
| Net/wireless             | 136       | 7.58%   |
| Camera                   | 57        | 3.18%   |
| Net/ethernet             | 48        | 2.68%   |
| Bluetooth                | 36        | 2.01%   |
| Storage                  | 20        | 1.11%   |
| Card reader              | 15        | 0.84%   |
| Sound                    | 9         | 0.5%    |
| Communication controller | 7         | 0.39%   |
| Modem                    | 4         | 0.22%   |
| Network                  | 3         | 0.17%   |
| Dvb card                 | 3         | 0.17%   |
| Storage/nvme             | 2         | 0.11%   |


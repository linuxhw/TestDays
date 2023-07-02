Linux in Denmark - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

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

Total: 750

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c9cbb8f947](https://linux-hardware.org/?probe=c9cbb8f947) | Jun 27, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [46e3ea33a3](https://linux-hardware.org/?probe=46e3ea33a3) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| HP            | OMEN by Laptop              | [07d9cc6d71](https://linux-hardware.org/?probe=07d9cc6d71) | Jun 26, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [5298e132fc](https://linux-hardware.org/?probe=5298e132fc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L480 20LS002YMX    | [9c9702483c](https://linux-hardware.org/?probe=9c9702483c) | Jun 22, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [fc06bc7209](https://linux-hardware.org/?probe=fc06bc7209) | Jun 20, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [5bd2521f5c](https://linux-hardware.org/?probe=5bd2521f5c) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| Dell          | Inspiron 15-7568            | [4d0efefd7c](https://linux-hardware.org/?probe=4d0efefd7c) | Jun 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [2aaa4324d0](https://linux-hardware.org/?probe=2aaa4324d0) | Jun 12, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [a62438daef](https://linux-hardware.org/?probe=a62438daef) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470 20HDS14L00    | [fab548c31e](https://linux-hardware.org/?probe=fab548c31e) | Jun 10, 2023 |
| Acer          | Aspire E5-553               | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| Razer         | Blade 15 Advanced Model ... | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | 1225B                       | [769a6736f1](https://linux-hardware.org/?probe=769a6736f1) | May 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [742ae62ba6](https://linux-hardware.org/?probe=742ae62ba6) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| Dell          | Inspiron 15-7568            | [227930e25d](https://linux-hardware.org/?probe=227930e25d) | May 29, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [4147fc8cb7](https://linux-hardware.org/?probe=4147fc8cb7) | May 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1UB1H    | [d9295f37bc](https://linux-hardware.org/?probe=d9295f37bc) | May 27, 2023 |
| Acer          | Aspire E5-553               | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [97687a73c3](https://linux-hardware.org/?probe=97687a73c3) | May 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0037MD     | [f1a58d3a7f](https://linux-hardware.org/?probe=f1a58d3a7f) | May 11, 2023 |
| Acer          | Aspire 5810T                | [d21ea25d7a](https://linux-hardware.org/?probe=d21ea25d7a) | May 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS0AP00    | [f628b12917](https://linux-hardware.org/?probe=f628b12917) | May 10, 2023 |
| Acer          | Aspire 5810T                | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| HP            | ProBook 6570b               | [d240b443c4](https://linux-hardware.org/?probe=d240b443c4) | May 06, 2023 |
| Acer          | Aspire 5810T                | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Acer          | Aspire E5-553               | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOD-WXX9                    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| Lenovo        | ThinkPad T520 4243W4L       | [bcdd9e5f74](https://linux-hardware.org/?probe=bcdd9e5f74) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [0ec2388253](https://linux-hardware.org/?probe=0ec2388253) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [a196246f09](https://linux-hardware.org/?probe=a196246f09) | Apr 17, 2023 |
| Lenovo        | ThinkPad W541 20EGS03800    | [4be9d98954](https://linux-hardware.org/?probe=4be9d98954) | Apr 11, 2023 |
| eMachines     | E725                        | [758d0c86b2](https://linux-hardware.org/?probe=758d0c86b2) | Apr 06, 2023 |
| Acer          | Aspire E5-771               | [2ef87c5f77](https://linux-hardware.org/?probe=2ef87c5f77) | Apr 06, 2023 |
| Acer          | Swift SF314-59              | [d12cbc4044](https://linux-hardware.org/?probe=d12cbc4044) | Apr 06, 2023 |
| HUAWEI        | BOD-WXX9                    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| Dell          | Latitude 7480               | [f1ca485181](https://linux-hardware.org/?probe=f1ca485181) | Apr 02, 2023 |
| Lenovo        | G505 20240                  | [d873632b2b](https://linux-hardware.org/?probe=d873632b2b) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420 4236W1K       | [e093aace6e](https://linux-hardware.org/?probe=e093aace6e) | Mar 27, 2023 |
| Lenovo        | ThinkPad L530 24812SG       | [163d4e376e](https://linux-hardware.org/?probe=163d4e376e) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Acer          | Aspire E5-553               | [3d591cd190](https://linux-hardware.org/?probe=3d591cd190) | Mar 21, 2023 |
| Acer          | Extensa 7620                | [59bb9967c2](https://linux-hardware.org/?probe=59bb9967c2) | Mar 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [ccfa4fb30e](https://linux-hardware.org/?probe=ccfa4fb30e) | Mar 17, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [4012d2fb1f](https://linux-hardware.org/?probe=4012d2fb1f) | Mar 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | [f2f8796262](https://linux-hardware.org/?probe=f2f8796262) | Mar 16, 2023 |
| Lenovo        | ThinkPad P52s 20LBS0AF00    | [fe02ac3290](https://linux-hardware.org/?probe=fe02ac3290) | Mar 15, 2023 |
| Samsung       | NP770                       | [ab2677e28e](https://linux-hardware.org/?probe=ab2677e28e) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| HP            | OMEN by Laptop              | [a3a369de93](https://linux-hardware.org/?probe=a3a369de93) | Mar 08, 2023 |
| Apple         | MacBookPro9,2               | [8995f4a3b0](https://linux-hardware.org/?probe=8995f4a3b0) | Mar 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | [38623506fd](https://linux-hardware.org/?probe=38623506fd) | Mar 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [05e7af9004](https://linux-hardware.org/?probe=05e7af9004) | Mar 02, 2023 |
| HP            | Pavilion dv7                | [3d8c3db030](https://linux-hardware.org/?probe=3d8c3db030) | Feb 26, 2023 |
| HP            | EliteBook 840 G6            | [ea6777bf2d](https://linux-hardware.org/?probe=ea6777bf2d) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7380033a44](https://linux-hardware.org/?probe=7380033a44) | Feb 22, 2023 |
| HP            | Pavilion dv7                | [5fd9a2f9c5](https://linux-hardware.org/?probe=5fd9a2f9c5) | Feb 17, 2023 |
| HP            | Notebook                    | [682935bcda](https://linux-hardware.org/?probe=682935bcda) | Feb 16, 2023 |
| HP            | Notebook                    | [1ea98ae976](https://linux-hardware.org/?probe=1ea98ae976) | Feb 16, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aa3655a17e](https://linux-hardware.org/?probe=aa3655a17e) | Feb 15, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [36f57d56f8](https://linux-hardware.org/?probe=36f57d56f8) | Feb 15, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a55211363f](https://linux-hardware.org/?probe=a55211363f) | Feb 09, 2023 |
| HP            | Notebook                    | [eb0699bb89](https://linux-hardware.org/?probe=eb0699bb89) | Feb 07, 2023 |
| HP            | Pavilion g7                 | [e64e08ebd4](https://linux-hardware.org/?probe=e64e08ebd4) | Feb 05, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | [5a7e90c12d](https://linux-hardware.org/?probe=5a7e90c12d) | Feb 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ab57658c86](https://linux-hardware.org/?probe=ab57658c86) | Jan 31, 2023 |
| Lenovo        | ThinkPad L380 20M5S09Y00    | [2326ffc032](https://linux-hardware.org/?probe=2326ffc032) | Jan 31, 2023 |
| HP            | Laptop 14-bp0xx             | [68d8a60823](https://linux-hardware.org/?probe=68d8a60823) | Jan 27, 2023 |
| Standard      | Unknown                     | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | ProBook 650 G1              | [f9882955cb](https://linux-hardware.org/?probe=f9882955cb) | Jan 24, 2023 |
| Lenovo        | ThinkPad W541 20EF0020MD    | [fca73ad2a9](https://linux-hardware.org/?probe=fca73ad2a9) | Jan 24, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [96a5ca6b92](https://linux-hardware.org/?probe=96a5ca6b92) | Jan 23, 2023 |
| System76      | Darter UltraThin            | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Lenovo        | ThinkPad X230 2325AS7       | [71a521018d](https://linux-hardware.org/?probe=71a521018d) | Jan 19, 2023 |
| ASUSTek       | S301LA                      | [c45b4758ed](https://linux-hardware.org/?probe=c45b4758ed) | Jan 18, 2023 |
| Lenovo        | G505 20240                  | [ef2fdd351c](https://linux-hardware.org/?probe=ef2fdd351c) | Jan 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [138f888e23](https://linux-hardware.org/?probe=138f888e23) | Jan 15, 2023 |
| Acer          | Aspire 5810T                | [a39184ad9b](https://linux-hardware.org/?probe=a39184ad9b) | Jan 13, 2023 |
| Acer          | Aspire 5810T                | [ccc420a65a](https://linux-hardware.org/?probe=ccc420a65a) | Jan 13, 2023 |
| Acer          | Aspire A515-56              | [2f95543d62](https://linux-hardware.org/?probe=2f95543d62) | Jan 11, 2023 |
| Acer          | Aspire E5-553               | [e68c76cbee](https://linux-hardware.org/?probe=e68c76cbee) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| HP            | EliteBook 845 14 inch G9... | [26826e3c23](https://linux-hardware.org/?probe=26826e3c23) | Jan 04, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [bc17e3a0f4](https://linux-hardware.org/?probe=bc17e3a0f4) | Jan 04, 2023 |
| Medion        | P7621                       | [6ce2ef1abc](https://linux-hardware.org/?probe=6ce2ef1abc) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Apple         | MacBookPro10,2              | [a01c19a34d](https://linux-hardware.org/?probe=a01c19a34d) | Dec 29, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | X75A1                       | [5a5ee8db71](https://linux-hardware.org/?probe=5a5ee8db71) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| Valve         | Jupiter                     | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| MSI           | GP65 Leopard 9SE            | [7b980fbd8f](https://linux-hardware.org/?probe=7b980fbd8f) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| Medion        | P7621                       | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [be36edb132](https://linux-hardware.org/?probe=be36edb132) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [491b8d0b8f](https://linux-hardware.org/?probe=491b8d0b8f) | Dec 11, 2022 |
| Lenovo        | ThinkPad Z61m 94503HG       | [4131ed9268](https://linux-hardware.org/?probe=4131ed9268) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Dell          | XPS 13 9370                 | [e5291ae74e](https://linux-hardware.org/?probe=e5291ae74e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Acer          | Aspire E5-575G              | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Standard      | Unknown                     | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Inspiron 15 3520            | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [dee6d2a740](https://linux-hardware.org/?probe=dee6d2a740) | Nov 23, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| Acer          | Aspire 5810T                | [2c671f2494](https://linux-hardware.org/?probe=2c671f2494) | Nov 18, 2022 |
| Timi          | TM1607                      | [a93d1611bb](https://linux-hardware.org/?probe=a93d1611bb) | Nov 18, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [7352c1f1ed](https://linux-hardware.org/?probe=7352c1f1ed) | Nov 17, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Acer          | Aspire E5-553               | [4c031f5f3b](https://linux-hardware.org/?probe=4c031f5f3b) | Nov 15, 2022 |
| Apple         | MacBookPro5,5               | [a35952fc68](https://linux-hardware.org/?probe=a35952fc68) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| MSI           | GV62 8RC                    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a62bf9ed3b](https://linux-hardware.org/?probe=a62bf9ed3b) | Nov 08, 2022 |
| HP            | Notebook                    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS3CF0... | [2c52a84e7c](https://linux-hardware.org/?probe=2c52a84e7c) | Nov 06, 2022 |
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Acer          | Aspire E5-551               | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Acer          | Aspire E5-553               | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Valve         | Jupiter                     | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| HP            | ProBook 6550b               | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | B50-50 80S2                 | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Acer          | Aspire M3-581TG             | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| Dell          | Latitude 7490               | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Notebook      | PB50_70DFx,DDx              | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| HP            | EliteBook 2560p             | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| HP            | ProBook 6450b               | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| SLIMBOOK      | PROX14-10                   | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| Dell          | Precision 5750              | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Acer          | Aspire V5-573G              | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| Lenovo        | E31-80 80MX                 | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| HP            | Pavilion Notebook           | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Apple         | MacBookPro11,5              | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| Medion        | P7612                       | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| Medion        | P7612                       | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Apple         | MacBookAir7,2               | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Quanta        | MW1/HW1                     | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Toshiba       | Satellite P850              | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| DukaPC        | Notebook                    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| Razer         | Blade Stealth               | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Apple         | MacBookPro14,1              | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| HP            | ZBook 15                    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Lenovo        | V130-15IKB 81HN             | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | XPS 15 9510                 | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| GPD           | P2 MAX                      | [78f79b2790](https://linux-hardware.org/?probe=78f79b2790) | Jul 31, 2021 |
| ASUSTek       | GL702VM                     | [bb9d228646](https://linux-hardware.org/?probe=bb9d228646) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a02dac8dff](https://linux-hardware.org/?probe=a02dac8dff) | Jul 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [e52365f866](https://linux-hardware.org/?probe=e52365f866) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [7a03dbd869](https://linux-hardware.org/?probe=7a03dbd869) | Jul 17, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [ce58f3f770](https://linux-hardware.org/?probe=ce58f3f770) | Jul 16, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a56195f1f1](https://linux-hardware.org/?probe=a56195f1f1) | Jul 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [440841d04a](https://linux-hardware.org/?probe=440841d04a) | Jul 12, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [3b106f1da0](https://linux-hardware.org/?probe=3b106f1da0) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [f8872c9e84](https://linux-hardware.org/?probe=f8872c9e84) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| DukaPC        | Notebook                    | [6d87054512](https://linux-hardware.org/?probe=6d87054512) | Jul 02, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Timi          | TM1703                      | [bd3756811d](https://linux-hardware.org/?probe=bd3756811d) | Jun 26, 2021 |
| DukaPC        | Notebook                    | [c29d208cdf](https://linux-hardware.org/?probe=c29d208cdf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T420 4236Y19       | [48927432b4](https://linux-hardware.org/?probe=48927432b4) | Jun 20, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0Y70... | [5e57af6782](https://linux-hardware.org/?probe=5e57af6782) | Jun 11, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| HP            | Compaq Presario CQ71        | [d4deb2b08d](https://linux-hardware.org/?probe=d4deb2b08d) | Jun 01, 2021 |
| Dell          | Latitude E6520              | [d1d0976880](https://linux-hardware.org/?probe=d1d0976880) | May 31, 2021 |
| Lenovo        | ThinkPad T400 647358G       | [b4f44d7932](https://linux-hardware.org/?probe=b4f44d7932) | May 29, 2021 |
| Toshiba       | Satellite C660              | [58d3740c30](https://linux-hardware.org/?probe=58d3740c30) | May 28, 2021 |
| Acer          | Aspire E5-553               | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| LAMINA        | T-1012B NORD                | [71e70e946a](https://linux-hardware.org/?probe=71e70e946a) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | [9dc2932064](https://linux-hardware.org/?probe=9dc2932064) | May 24, 2021 |
| ASUSTek       | X553SA                      | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire E5-511               | [9edec55620](https://linux-hardware.org/?probe=9edec55620) | May 23, 2021 |
| Acer          | Aspire E5-511               | [e20c93a2c1](https://linux-hardware.org/?probe=e20c93a2c1) | May 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a9e4c7793b](https://linux-hardware.org/?probe=a9e4c7793b) | May 18, 2021 |
| eMachines     | E725                        | [329f8f580e](https://linux-hardware.org/?probe=329f8f580e) | May 14, 2021 |
| ASUSTek       | K95VM                       | [58d4ed3c2b](https://linux-hardware.org/?probe=58d4ed3c2b) | May 10, 2021 |
| HP            | 15                          | [a13c097d59](https://linux-hardware.org/?probe=a13c097d59) | May 09, 2021 |
| HP            | 15                          | [c3cdcdab60](https://linux-hardware.org/?probe=c3cdcdab60) | May 09, 2021 |
| Alienware     | 17 R2                       | [a8470edc65](https://linux-hardware.org/?probe=a8470edc65) | May 06, 2021 |
| ASUSTek       | G74Sx                       | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| Lenovo        | ThinkPad T520 4243PC2       | [915d41f361](https://linux-hardware.org/?probe=915d41f361) | Apr 29, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [e2f8b2beda](https://linux-hardware.org/?probe=e2f8b2beda) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [684f1471b1](https://linux-hardware.org/?probe=684f1471b1) | Apr 23, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| Lenovo        | ThinkPad T520 42434YG       | [8e0b4ee3a1](https://linux-hardware.org/?probe=8e0b4ee3a1) | Apr 17, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [49e1959064](https://linux-hardware.org/?probe=49e1959064) | Apr 16, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [b2853266e8](https://linux-hardware.org/?probe=b2853266e8) | Apr 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [4b127c0ba4](https://linux-hardware.org/?probe=4b127c0ba4) | Apr 11, 2021 |
| HP            | Laptop 15-da1xxx            | [a844e710cc](https://linux-hardware.org/?probe=a844e710cc) | Apr 09, 2021 |
| Lenovo        | ThinkPad T60 20076RG        | [aa3ea77acf](https://linux-hardware.org/?probe=aa3ea77acf) | Apr 08, 2021 |
| HP            | G72                         | [2ab4eb5fcd](https://linux-hardware.org/?probe=2ab4eb5fcd) | Apr 05, 2021 |
| ASUSTek       | K95VM                       | [81a01884d2](https://linux-hardware.org/?probe=81a01884d2) | Mar 24, 2021 |
| Lenovo        | ThinkPad W520 4284Y54       | [8d564e495b](https://linux-hardware.org/?probe=8d564e495b) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire E5-553               | [0c21dc1b96](https://linux-hardware.org/?probe=0c21dc1b96) | Mar 19, 2021 |
| HP            | Pavilion dm1                | [438cf03315](https://linux-hardware.org/?probe=438cf03315) | Mar 18, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [7e7a4bc992](https://linux-hardware.org/?probe=7e7a4bc992) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [1b8a078a19](https://linux-hardware.org/?probe=1b8a078a19) | Mar 16, 2021 |
| HP            | EliteBook 830 G5            | [248eb896a0](https://linux-hardware.org/?probe=248eb896a0) | Mar 15, 2021 |
| HP            | Compaq Presario CQ60        | [e4613a6f75](https://linux-hardware.org/?probe=e4613a6f75) | Mar 15, 2021 |
| Dell          | Latitude E5250              | [22067e0909](https://linux-hardware.org/?probe=22067e0909) | Mar 13, 2021 |
| Dell          | Latitude E5250              | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| HP            | Pavilion dv9700             | [f55ec4dd18](https://linux-hardware.org/?probe=f55ec4dd18) | Mar 11, 2021 |
| Dell          | XPS 13 9370                 | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| Dell          | Latitude E5250              | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Acer          | Aspire E5-575G              | [18240d24d8](https://linux-hardware.org/?probe=18240d24d8) | Mar 06, 2021 |
| Toshiba       | Satellite L350D             | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| Acer          | Aspire E5-553               | [74e6da0017](https://linux-hardware.org/?probe=74e6da0017) | Feb 27, 2021 |
| HP            | 630                         | [6803747e34](https://linux-hardware.org/?probe=6803747e34) | Feb 22, 2021 |
| HP            | 630                         | [8b04fe81aa](https://linux-hardware.org/?probe=8b04fe81aa) | Feb 22, 2021 |
| Lenovo        | ThinkPad T61 7661W1D        | [6db91fdd34](https://linux-hardware.org/?probe=6db91fdd34) | Feb 17, 2021 |
| Lenovo        | 3000 G530 444622G           | [3ef99e25df](https://linux-hardware.org/?probe=3ef99e25df) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMA2AE00    | [2730f6215a](https://linux-hardware.org/?probe=2730f6215a) | Feb 12, 2021 |
| Dell          | XPS 13 9360                 | [564f71d6f3](https://linux-hardware.org/?probe=564f71d6f3) | Feb 10, 2021 |
| Acer          | Aspire E5-553               | [ab7532985d](https://linux-hardware.org/?probe=ab7532985d) | Feb 05, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [ed806c00b2](https://linux-hardware.org/?probe=ed806c00b2) | Feb 04, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| HP            | EliteBook 840 G5            | [19ef5f3adb](https://linux-hardware.org/?probe=19ef5f3adb) | Jan 29, 2021 |
| Dell          | Latitude E7440              | [ee2c17a895](https://linux-hardware.org/?probe=ee2c17a895) | Jan 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [964b7c1b1f](https://linux-hardware.org/?probe=964b7c1b1f) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [82da77953a](https://linux-hardware.org/?probe=82da77953a) | Jan 19, 2021 |
| Dell          | Latitude 5500               | [d7e06bd87b](https://linux-hardware.org/?probe=d7e06bd87b) | Jan 18, 2021 |
| Dell          | Latitude 5500               | [f40a2d50bc](https://linux-hardware.org/?probe=f40a2d50bc) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| Dell          | XPS 13 9300                 | [229b46a693](https://linux-hardware.org/?probe=229b46a693) | Jan 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [fa963386d8](https://linux-hardware.org/?probe=fa963386d8) | Jan 07, 2021 |
| Toshiba       | Satellite L40               | [bd26bbbe43](https://linux-hardware.org/?probe=bd26bbbe43) | Jan 06, 2021 |
| Lenovo        | G570 4334                   | [c643363b80](https://linux-hardware.org/?probe=c643363b80) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2ed1a3283e](https://linux-hardware.org/?probe=2ed1a3283e) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c0c38c5aee](https://linux-hardware.org/?probe=c0c38c5aee) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [65fe7eb049](https://linux-hardware.org/?probe=65fe7eb049) | Dec 30, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [f514e54057](https://linux-hardware.org/?probe=f514e54057) | Dec 28, 2020 |
| ASUSTek       | PU401LAC                    | [c5bf49eabf](https://linux-hardware.org/?probe=c5bf49eabf) | Dec 26, 2020 |
| HP            | EliteBook 850 G5            | [ce2a32dd24](https://linux-hardware.org/?probe=ce2a32dd24) | Dec 22, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3e419467e2](https://linux-hardware.org/?probe=3e419467e2) | Dec 22, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [87c08ecbb6](https://linux-hardware.org/?probe=87c08ecbb6) | Dec 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [52e86fd2a9](https://linux-hardware.org/?probe=52e86fd2a9) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [14a84d3948](https://linux-hardware.org/?probe=14a84d3948) | Dec 20, 2020 |
| Lenovo        | ThinkPad T520 4243W54       | [15862aca5c](https://linux-hardware.org/?probe=15862aca5c) | Dec 20, 2020 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [01b87f6602](https://linux-hardware.org/?probe=01b87f6602) | Dec 18, 2020 |
| Lenovo        | Unknown                     | [92b19a0db9](https://linux-hardware.org/?probe=92b19a0db9) | Dec 18, 2020 |
| Dell          | Latitude E7270              | [bac2c2820f](https://linux-hardware.org/?probe=bac2c2820f) | Dec 17, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [5dfa78d268](https://linux-hardware.org/?probe=5dfa78d268) | Dec 15, 2020 |
| HP            | ProBook 650 G5              | [56c46edc3f](https://linux-hardware.org/?probe=56c46edc3f) | Dec 13, 2020 |
| HP            | ProBook 650 G5              | [a035f76fcb](https://linux-hardware.org/?probe=a035f76fcb) | Dec 12, 2020 |
| Acer          | Extensa 2519                | [17bdd3b68f](https://linux-hardware.org/?probe=17bdd3b68f) | Dec 10, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [e9f3972862](https://linux-hardware.org/?probe=e9f3972862) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [f98c566bb6](https://linux-hardware.org/?probe=f98c566bb6) | Dec 03, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [ff051ee214](https://linux-hardware.org/?probe=ff051ee214) | Dec 01, 2020 |
| Dell          | Latitude E6540              | [5a0fbaa262](https://linux-hardware.org/?probe=5a0fbaa262) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8b31225bd7](https://linux-hardware.org/?probe=8b31225bd7) | Nov 27, 2020 |
| Apple         | MacBookPro7,1               | [ad6bb1f253](https://linux-hardware.org/?probe=ad6bb1f253) | Nov 24, 2020 |
| Lenovo        | ThinkPad P52 20M9001MMD     | [72ba2ae6cb](https://linux-hardware.org/?probe=72ba2ae6cb) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | System XPS L321X            | [3fb9a4373c](https://linux-hardware.org/?probe=3fb9a4373c) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [ee5da1d9b0](https://linux-hardware.org/?probe=ee5da1d9b0) | Nov 10, 2020 |
| Lenovo        | ThinkPad X301 2776LEG       | [2c4aa61663](https://linux-hardware.org/?probe=2c4aa61663) | Nov 09, 2020 |
| Dell          | XPS 13 9370                 | [b75b281fee](https://linux-hardware.org/?probe=b75b281fee) | Nov 08, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de9ea1422c](https://linux-hardware.org/?probe=de9ea1422c) | Nov 08, 2020 |
| HP            | Pavilion Notebook           | [1698bf3366](https://linux-hardware.org/?probe=1698bf3366) | Nov 07, 2020 |
| HP            | EliteBook 820 G3            | [e34831e959](https://linux-hardware.org/?probe=e34831e959) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [bb40872a6b](https://linux-hardware.org/?probe=bb40872a6b) | Nov 05, 2020 |
| HP            | ProBook 4720s               | [acb46376ad](https://linux-hardware.org/?probe=acb46376ad) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [d65f8070e0](https://linux-hardware.org/?probe=d65f8070e0) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | XPS 15 9560                 | [5e06a37540](https://linux-hardware.org/?probe=5e06a37540) | Nov 01, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1213098826](https://linux-hardware.org/?probe=1213098826) | Oct 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [de02478ef0](https://linux-hardware.org/?probe=de02478ef0) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Razer         | Blade                       | [7aef75c2c6](https://linux-hardware.org/?probe=7aef75c2c6) | Oct 28, 2020 |
| Dell          | Vostro 3558                 | [eda9a94c60](https://linux-hardware.org/?probe=eda9a94c60) | Oct 28, 2020 |
| Acer          | Nitro AN515-53              | [08235cd1ad](https://linux-hardware.org/?probe=08235cd1ad) | Oct 25, 2020 |
| Acer          | Nitro AN515-53              | [80a32fe04b](https://linux-hardware.org/?probe=80a32fe04b) | Oct 24, 2020 |
| Dell          | Vostro 3558                 | [e22529c904](https://linux-hardware.org/?probe=e22529c904) | Oct 23, 2020 |
| Apple         | MacBookPro5,5               | [b7c6f0c157](https://linux-hardware.org/?probe=b7c6f0c157) | Oct 22, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [cbd374b1d9](https://linux-hardware.org/?probe=cbd374b1d9) | Oct 22, 2020 |
| Toshiba       | Satellite L40               | [3d02e46571](https://linux-hardware.org/?probe=3d02e46571) | Oct 22, 2020 |
| HP            | EliteBook 850 G5            | [1a2d14ded4](https://linux-hardware.org/?probe=1a2d14ded4) | Oct 20, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| Toshiba       | Satellite P50-A-11J         | [720f19d566](https://linux-hardware.org/?probe=720f19d566) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [20453e8620](https://linux-hardware.org/?probe=20453e8620) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [eee8f03871](https://linux-hardware.org/?probe=eee8f03871) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [4ffeac234f](https://linux-hardware.org/?probe=4ffeac234f) | Oct 09, 2020 |
| Acer          | Nitro AN515-53              | [fe2889ef02](https://linux-hardware.org/?probe=fe2889ef02) | Oct 08, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| Acer          | Aspire 7551                 | [0524a7f258](https://linux-hardware.org/?probe=0524a7f258) | Oct 04, 2020 |
| Acer          | Aspire VN7-792G             | [908eea39dd](https://linux-hardware.org/?probe=908eea39dd) | Oct 04, 2020 |
| Acer          | Nitro AN515-53              | [a1d00d9bc3](https://linux-hardware.org/?probe=a1d00d9bc3) | Oct 03, 2020 |
| Acer          | Nitro AN515-53              | [be2aafbbae](https://linux-hardware.org/?probe=be2aafbbae) | Oct 03, 2020 |
| HP            | ProBook 650 G2              | [f04b6dbdc5](https://linux-hardware.org/?probe=f04b6dbdc5) | Oct 02, 2020 |
| HP            | ProBook 650 G2              | [7b826236e8](https://linux-hardware.org/?probe=7b826236e8) | Oct 02, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [9a69eca48e](https://linux-hardware.org/?probe=9a69eca48e) | Oct 01, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [3b51f51354](https://linux-hardware.org/?probe=3b51f51354) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [a3846db026](https://linux-hardware.org/?probe=a3846db026) | Sep 26, 2020 |
| Lenovo        | G710 20252                  | [6d3ef693db](https://linux-hardware.org/?probe=6d3ef693db) | Sep 23, 2020 |
| HP            | Pavilion Sleekbook 15       | [d5217dd737](https://linux-hardware.org/?probe=d5217dd737) | Sep 20, 2020 |
| Google        | Liara                       | [e6434b38e5](https://linux-hardware.org/?probe=e6434b38e5) | Sep 16, 2020 |
| HP            | 620                         | [3cd40bde20](https://linux-hardware.org/?probe=3cd40bde20) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [1f2fba4e2e](https://linux-hardware.org/?probe=1f2fba4e2e) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [46f7d12d9e](https://linux-hardware.org/?probe=46f7d12d9e) | Sep 11, 2020 |
| HP            | EliteBook 850 G5            | [826772015a](https://linux-hardware.org/?probe=826772015a) | Sep 09, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Apple         | MacBookPro10,1              | [3d676f563d](https://linux-hardware.org/?probe=3d676f563d) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325W3J       | [b076277c46](https://linux-hardware.org/?probe=b076277c46) | Sep 05, 2020 |
| Lenovo        | ThinkPad X240 20AMS39B00    | [b2f7ace5e9](https://linux-hardware.org/?probe=b2f7ace5e9) | Sep 05, 2020 |
| Notebook      | W35xSTQ_370ST               | [69960189a7](https://linux-hardware.org/?probe=69960189a7) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [392b8d8877](https://linux-hardware.org/?probe=392b8d8877) | Sep 04, 2020 |
| Lenovo        | V110-15IAP 80TG             | [74a552046a](https://linux-hardware.org/?probe=74a552046a) | Sep 02, 2020 |
| Toshiba       | Satellite L755D             | [e3aa57d80d](https://linux-hardware.org/?probe=e3aa57d80d) | Aug 30, 2020 |
| HP            | 620                         | [2abb876aa3](https://linux-hardware.org/?probe=2abb876aa3) | Aug 27, 2020 |
| Purism        | Librem 13 v2                | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| HP            | Pavilion dm1                | [39154c83b0](https://linux-hardware.org/?probe=39154c83b0) | Aug 27, 2020 |
| Acer          | NC-SF314-51-56Y4            | [0627a672e7](https://linux-hardware.org/?probe=0627a672e7) | Aug 27, 2020 |
| Lenovo        | Unknown                     | [74313d4eb1](https://linux-hardware.org/?probe=74313d4eb1) | Aug 24, 2020 |
| Lenovo        | ThinkPad P50s 20FLS02200    | [68d5ec0716](https://linux-hardware.org/?probe=68d5ec0716) | Aug 24, 2020 |
| HP            | ProBook 650 G2              | [4a91b4b21f](https://linux-hardware.org/?probe=4a91b4b21f) | Aug 18, 2020 |
| Razer         | Blade                       | [b8e7f44d4a](https://linux-hardware.org/?probe=b8e7f44d4a) | Aug 17, 2020 |
| HP            | EliteBook 820 G3            | [0d1ad99429](https://linux-hardware.org/?probe=0d1ad99429) | Aug 13, 2020 |
| Toshiba       | Satellite L40               | [33ec17e21b](https://linux-hardware.org/?probe=33ec17e21b) | Aug 13, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [8e3eee2d07](https://linux-hardware.org/?probe=8e3eee2d07) | Aug 06, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [6b9f38754c](https://linux-hardware.org/?probe=6b9f38754c) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [72a1412fb1](https://linux-hardware.org/?probe=72a1412fb1) | Aug 04, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [133bc3dd52](https://linux-hardware.org/?probe=133bc3dd52) | Aug 04, 2020 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [6d4445f122](https://linux-hardware.org/?probe=6d4445f122) | Aug 02, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [c535bd5654](https://linux-hardware.org/?probe=c535bd5654) | Jul 29, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [fa42e14984](https://linux-hardware.org/?probe=fa42e14984) | Jul 28, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [e748a3510c](https://linux-hardware.org/?probe=e748a3510c) | Jul 27, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [3122f02f2c](https://linux-hardware.org/?probe=3122f02f2c) | Jul 23, 2020 |
| Packard Be... | EasyNote LJ73               | [b7cb387fea](https://linux-hardware.org/?probe=b7cb387fea) | Jul 21, 2020 |
| Dell          | Latitude E6420              | [e9238dcfff](https://linux-hardware.org/?probe=e9238dcfff) | Jul 19, 2020 |
| Dell          | Latitude E6420              | [231cadfc4a](https://linux-hardware.org/?probe=231cadfc4a) | Jul 19, 2020 |
| Toshiba       | Satellite L755D             | [a0cdb2f0bf](https://linux-hardware.org/?probe=a0cdb2f0bf) | Jul 12, 2020 |
| Toshiba       | Satellite L755D             | [f4ab460d93](https://linux-hardware.org/?probe=f4ab460d93) | Jul 12, 2020 |
| Dell          | Latitude 7480               | [c265940ec9](https://linux-hardware.org/?probe=c265940ec9) | Jul 11, 2020 |
| Apple         | MacBookPro6,1               | [432c9e6acf](https://linux-hardware.org/?probe=432c9e6acf) | Jul 05, 2020 |
| Apple         | MacBookPro14,1              | [b1b965bcfa](https://linux-hardware.org/?probe=b1b965bcfa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [26dfef89d5](https://linux-hardware.org/?probe=26dfef89d5) | Jun 30, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [3f43b86780](https://linux-hardware.org/?probe=3f43b86780) | Jun 29, 2020 |
| Fujitsu       | LIFEBOOK U938               | [445cfe436d](https://linux-hardware.org/?probe=445cfe436d) | Jun 28, 2020 |
| ASUSTek       | K56CB                       | [bbdd76a080](https://linux-hardware.org/?probe=bbdd76a080) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK U938               | [6fab40c5c2](https://linux-hardware.org/?probe=6fab40c5c2) | Jun 20, 2020 |
| Acer          | Mantasta                    | [fae9194978](https://linux-hardware.org/?probe=fae9194978) | Jun 19, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [12d9fce39b](https://linux-hardware.org/?probe=12d9fce39b) | Jun 18, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [8307e528e0](https://linux-hardware.org/?probe=8307e528e0) | Jun 17, 2020 |
| HP            | Pavilion 15                 | [6d0c4b8b4f](https://linux-hardware.org/?probe=6d0c4b8b4f) | Jun 16, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [c9de665933](https://linux-hardware.org/?probe=c9de665933) | Jun 14, 2020 |
| Dell          | Latitude 7480               | [f1120b6914](https://linux-hardware.org/?probe=f1120b6914) | Jun 14, 2020 |
| Dell          | XPS 15 9560                 | [68f8b211cb](https://linux-hardware.org/?probe=68f8b211cb) | Jun 13, 2020 |
| Dell          | XPS 15 9560                 | [5e9c9bd030](https://linux-hardware.org/?probe=5e9c9bd030) | Jun 13, 2020 |
| Razer         | Blade                       | [5ed51b12b4](https://linux-hardware.org/?probe=5ed51b12b4) | Jun 12, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [6e1571661e](https://linux-hardware.org/?probe=6e1571661e) | Jun 12, 2020 |
| Lenovo        | ThinkPad W520 4284Y19       | [ac2ade7339](https://linux-hardware.org/?probe=ac2ade7339) | Jun 07, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| Dell          | XPS 15 7590                 | [386ef00203](https://linux-hardware.org/?probe=386ef00203) | May 25, 2020 |
| Dell          | XPS 15 7590                 | [544670327d](https://linux-hardware.org/?probe=544670327d) | May 21, 2020 |
| Acer          | TravelMate 6592             | [9bb4619272](https://linux-hardware.org/?probe=9bb4619272) | May 17, 2020 |
| Acer          | TravelMate 6592             | [e4e54de319](https://linux-hardware.org/?probe=e4e54de319) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [788a18932c](https://linux-hardware.org/?probe=788a18932c) | May 16, 2020 |
| Acer          | Swift SF514-52T             | [93ede38f81](https://linux-hardware.org/?probe=93ede38f81) | May 16, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b47983a36a](https://linux-hardware.org/?probe=b47983a36a) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5fbd9385df](https://linux-hardware.org/?probe=5fbd9385df) | May 13, 2020 |
| Lenovo        | ThinkPad T410 2522WPH       | [236d1e64eb](https://linux-hardware.org/?probe=236d1e64eb) | May 10, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a54bb2200a](https://linux-hardware.org/?probe=a54bb2200a) | May 06, 2020 |
| HP            | 255 G7 Notebook PC          | [0a904bfe70](https://linux-hardware.org/?probe=0a904bfe70) | May 05, 2020 |
| TUXEDO        | Unknown                     | [3f23947dd8](https://linux-hardware.org/?probe=3f23947dd8) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [b85ac004b3](https://linux-hardware.org/?probe=b85ac004b3) | May 04, 2020 |
| Lenovo        | ThinkPad T480s 20L8S5U50... | [d295ec1834](https://linux-hardware.org/?probe=d295ec1834) | May 03, 2020 |
| Dell          | Latitude E7450              | [0f14ff60e1](https://linux-hardware.org/?probe=0f14ff60e1) | May 02, 2020 |
| HP            | EliteBook 840 G1            | [9c6700839f](https://linux-hardware.org/?probe=9c6700839f) | May 01, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| Acer          | Aspire A715-72G             | [db52ab416a](https://linux-hardware.org/?probe=db52ab416a) | Apr 29, 2020 |
| HP            | EliteBook 840 G1            | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [2ea2bebae7](https://linux-hardware.org/?probe=2ea2bebae7) | Apr 25, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [47ae6712b9](https://linux-hardware.org/?probe=47ae6712b9) | Apr 25, 2020 |
| HP            | Unknown                     | [7da32c9344](https://linux-hardware.org/?probe=7da32c9344) | Apr 21, 2020 |
| Dell          | Latitude E5510              | [a70ec059cf](https://linux-hardware.org/?probe=a70ec059cf) | Apr 13, 2020 |
| HP            | Pavilion dv9700             | [6096eebeb4](https://linux-hardware.org/?probe=6096eebeb4) | Apr 11, 2020 |
| Apple         | MacBookPro5,5               | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Lenovo        | B50-10 80QR                 | [587fb80750](https://linux-hardware.org/?probe=587fb80750) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [bfb0ade0c7](https://linux-hardware.org/?probe=bfb0ade0c7) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [26154d1d2c](https://linux-hardware.org/?probe=26154d1d2c) | Apr 01, 2020 |
| ASUSTek       | N76VB                       | [a771ac7748](https://linux-hardware.org/?probe=a771ac7748) | Mar 24, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | Pavilion dv7                | [64000a6ec8](https://linux-hardware.org/?probe=64000a6ec8) | Mar 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [69559fb5ce](https://linux-hardware.org/?probe=69559fb5ce) | Mar 18, 2020 |
| Toshiba       | Satellite C670D-10C         | [bdcd7e9b36](https://linux-hardware.org/?probe=bdcd7e9b36) | Mar 17, 2020 |
| Toshiba       | Satellite C670D-10C         | [ab2ea68be0](https://linux-hardware.org/?probe=ab2ea68be0) | Mar 17, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| HP            | ProBook 4720s               | [a32d5c092c](https://linux-hardware.org/?probe=a32d5c092c) | Mar 15, 2020 |
| Toshiba       | Satellite L40               | [467c320928](https://linux-hardware.org/?probe=467c320928) | Mar 11, 2020 |
| Lenovo        | ThinkPad Edge E530 3259C... | [7e0acb9bed](https://linux-hardware.org/?probe=7e0acb9bed) | Mar 06, 2020 |
| HP            | ProBook 4720s               | [823553cfbd](https://linux-hardware.org/?probe=823553cfbd) | Mar 03, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [de25ec2891](https://linux-hardware.org/?probe=de25ec2891) | Feb 28, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [b333f7015a](https://linux-hardware.org/?probe=b333f7015a) | Feb 28, 2020 |
| HP            | ZBook 14u G5                | [03871e6b83](https://linux-hardware.org/?probe=03871e6b83) | Feb 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [0937d2a588](https://linux-hardware.org/?probe=0937d2a588) | Feb 20, 2020 |
| Dell          | Inspiron 3542               | [5e00c1766c](https://linux-hardware.org/?probe=5e00c1766c) | Feb 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [7f8aef2f6b](https://linux-hardware.org/?probe=7f8aef2f6b) | Feb 19, 2020 |
| MSI           | MS-1738                     | [0cbf139f1d](https://linux-hardware.org/?probe=0cbf139f1d) | Feb 11, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [7773f702ab](https://linux-hardware.org/?probe=7773f702ab) | Feb 10, 2020 |
| ASUSTek       | UX331UA                     | [62bdf0c233](https://linux-hardware.org/?probe=62bdf0c233) | Feb 10, 2020 |
| HP            | EliteBook 850 G5            | [fc9101307a](https://linux-hardware.org/?probe=fc9101307a) | Feb 07, 2020 |
| Dell          | Precision 7530              | [bb59dc45d2](https://linux-hardware.org/?probe=bb59dc45d2) | Feb 06, 2020 |
| MSI           | MS-1738                     | [1f7c3ccb75](https://linux-hardware.org/?probe=1f7c3ccb75) | Jan 29, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [1435e47012](https://linux-hardware.org/?probe=1435e47012) | Jan 27, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [44ad91d4da](https://linux-hardware.org/?probe=44ad91d4da) | Jan 24, 2020 |
| Dell          | Latitude 5590               | [206a367d42](https://linux-hardware.org/?probe=206a367d42) | Jan 24, 2020 |
| HP            | EliteBook 850 G5            | [bcc6422548](https://linux-hardware.org/?probe=bcc6422548) | Jan 18, 2020 |
| Samsung       | N150/N210/N220              | [91718b856a](https://linux-hardware.org/?probe=91718b856a) | Jan 16, 2020 |
| HP            | EliteBook 840 G6            | [79936056dd](https://linux-hardware.org/?probe=79936056dd) | Jan 16, 2020 |
| HP            | Laptop 15-bw0xx             | [2aff706ca4](https://linux-hardware.org/?probe=2aff706ca4) | Jan 15, 2020 |
| Lenovo        | ThinkPad T430s 2356W1L      | [42b6186198](https://linux-hardware.org/?probe=42b6186198) | Jan 13, 2020 |
| HP            | ProBook 4710s               | [d6124de12a](https://linux-hardware.org/?probe=d6124de12a) | Jan 01, 2020 |
| HP            | ProBook 4710s               | [7eb0b2437d](https://linux-hardware.org/?probe=7eb0b2437d) | Jan 01, 2020 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [14015a6cde](https://linux-hardware.org/?probe=14015a6cde) | Dec 24, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [c7b13e4ba2](https://linux-hardware.org/?probe=c7b13e4ba2) | Dec 23, 2019 |
| Dell          | Inspiron 1545               | [adaa5b6d54](https://linux-hardware.org/?probe=adaa5b6d54) | Dec 10, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [7ab81dbd28](https://linux-hardware.org/?probe=7ab81dbd28) | Nov 30, 2019 |
| HP            | Pavilion dv6                | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Lenovo        | ThinkPad S5-S540 20B3005... | [e84f3912be](https://linux-hardware.org/?probe=e84f3912be) | Nov 10, 2019 |
| eMachines     | E725                        | [599a7f6c54](https://linux-hardware.org/?probe=599a7f6c54) | Nov 03, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [9607f525a8](https://linux-hardware.org/?probe=9607f525a8) | Oct 29, 2019 |
| Apple         | MacBookPro9,2               | [99702307ab](https://linux-hardware.org/?probe=99702307ab) | Oct 21, 2019 |
| HP            | OMEN by Laptop              | [90ef6677b7](https://linux-hardware.org/?probe=90ef6677b7) | Oct 15, 2019 |
| Dell          | XPS 15 9570                 | [6cdbd762c1](https://linux-hardware.org/?probe=6cdbd762c1) | Oct 13, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [acd2d7dfad](https://linux-hardware.org/?probe=acd2d7dfad) | Oct 12, 2019 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [98855b1409](https://linux-hardware.org/?probe=98855b1409) | Oct 09, 2019 |
| Lenovo        | ThinkPad E480 20KN001NMX    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Dell          | Latitude 7480               | [b6627cc113](https://linux-hardware.org/?probe=b6627cc113) | Oct 08, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [14671c29e5](https://linux-hardware.org/?probe=14671c29e5) | Oct 07, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [402c3e5e59](https://linux-hardware.org/?probe=402c3e5e59) | Oct 05, 2019 |
| Acer          | Aspire ES1-311              | [d9d6c865ef](https://linux-hardware.org/?probe=d9d6c865ef) | Sep 26, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [98ed6c18c5](https://linux-hardware.org/?probe=98ed6c18c5) | Sep 21, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [fd17c2893e](https://linux-hardware.org/?probe=fd17c2893e) | Sep 19, 2019 |
| HP            | EliteBook 850 G5            | [b355ce68ad](https://linux-hardware.org/?probe=b355ce68ad) | Sep 15, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [01545dc8fb](https://linux-hardware.org/?probe=01545dc8fb) | Sep 11, 2019 |
| HP            | EliteBook 850 G5            | [f0c27f436e](https://linux-hardware.org/?probe=f0c27f436e) | Sep 10, 2019 |
| HP            | Pavilion dv2                | [b9b30ae45c](https://linux-hardware.org/?probe=b9b30ae45c) | Sep 10, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [121e1a0f7a](https://linux-hardware.org/?probe=121e1a0f7a) | Aug 27, 2019 |
| Samsung       | 940X3G/930X3G               | [73a88e2c94](https://linux-hardware.org/?probe=73a88e2c94) | Aug 23, 2019 |
| Dell          | XPS 15 9570                 | [85fc7259b6](https://linux-hardware.org/?probe=85fc7259b6) | Aug 15, 2019 |
| Fujitsu       | LIFEBOOK U772               | [0f7c7fe35a](https://linux-hardware.org/?probe=0f7c7fe35a) | Aug 15, 2019 |
| HP            | Pavilion x2 Detachable      | [923cbd5735](https://linux-hardware.org/?probe=923cbd5735) | Aug 06, 2019 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [0aaee3cc4f](https://linux-hardware.org/?probe=0aaee3cc4f) | Aug 02, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [61e8e08336](https://linux-hardware.org/?probe=61e8e08336) | Jul 31, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [41e069ab47](https://linux-hardware.org/?probe=41e069ab47) | Jul 31, 2019 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [3e47232411](https://linux-hardware.org/?probe=3e47232411) | Jul 26, 2019 |
| Dell          | Latitude E7470              | [90e9f8dfad](https://linux-hardware.org/?probe=90e9f8dfad) | Jul 26, 2019 |
| Lenovo        | ThinkPad S430 33642NG       | [7c0cd24986](https://linux-hardware.org/?probe=7c0cd24986) | Jul 25, 2019 |
| HP            | Pavilion dv9700             | [bfebe8555b](https://linux-hardware.org/?probe=bfebe8555b) | Jul 25, 2019 |
| HP            | Compaq CQ58                 | [0c02dfd17b](https://linux-hardware.org/?probe=0c02dfd17b) | Jul 21, 2019 |
| HP            | Compaq nx7400 (RU429ET#A... | [37b1d8aa7d](https://linux-hardware.org/?probe=37b1d8aa7d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [f3d7e4e13d](https://linux-hardware.org/?probe=f3d7e4e13d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [a75a2e9dae](https://linux-hardware.org/?probe=a75a2e9dae) | Jul 19, 2019 |
| HP            | Pavilion dv7                | [dda054b15d](https://linux-hardware.org/?probe=dda054b15d) | Jul 15, 2019 |
| ASUSTek       | 900                         | [db34e96f60](https://linux-hardware.org/?probe=db34e96f60) | Jul 06, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [5bc72880ea](https://linux-hardware.org/?probe=5bc72880ea) | Jun 15, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [25522cad27](https://linux-hardware.org/?probe=25522cad27) | Jun 13, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [4ed2a6de0d](https://linux-hardware.org/?probe=4ed2a6de0d) | Jun 08, 2019 |
| Acer          | Nitro AN515-42              | [5d176e185c](https://linux-hardware.org/?probe=5d176e185c) | Jun 06, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [945dd2aedf](https://linux-hardware.org/?probe=945dd2aedf) | Jun 04, 2019 |
| ASUSTek       | X55SV                       | [4137ac8f54](https://linux-hardware.org/?probe=4137ac8f54) | May 31, 2019 |
| HP            | EliteBook 8440p             | [e1a6c35a36](https://linux-hardware.org/?probe=e1a6c35a36) | May 27, 2019 |
| HP            | EliteBook 8440p             | [cfcb01f30c](https://linux-hardware.org/?probe=cfcb01f30c) | May 27, 2019 |
| HP            | EliteBook 8760w             | [13780fae80](https://linux-hardware.org/?probe=13780fae80) | May 25, 2019 |
| HP            | EliteBook 8760w             | [93d7fd3de9](https://linux-hardware.org/?probe=93d7fd3de9) | May 25, 2019 |
| ASUSTek       | UX331UA                     | [5b86d530bf](https://linux-hardware.org/?probe=5b86d530bf) | May 07, 2019 |
| MSI           | GV62 8RE                    | [4c00b9e457](https://linux-hardware.org/?probe=4c00b9e457) | May 05, 2019 |
| Lenovo        | Unknown                     | [fd7bf6fb44](https://linux-hardware.org/?probe=fd7bf6fb44) | May 04, 2019 |
| Lenovo        | Unknown                     | [abcb8328f0](https://linux-hardware.org/?probe=abcb8328f0) | May 03, 2019 |
| ASUSTek       | UX331UA                     | [4e74668f09](https://linux-hardware.org/?probe=4e74668f09) | Apr 30, 2019 |
| AMI           | Cherry Trail CR             | [c2adff61c1](https://linux-hardware.org/?probe=c2adff61c1) | Apr 16, 2019 |
| ASUSTek       | X550JX                      | [961517bceb](https://linux-hardware.org/?probe=961517bceb) | Apr 08, 2019 |
| Acer          | TravelMate 5720             | [3c724ba732](https://linux-hardware.org/?probe=3c724ba732) | Apr 03, 2019 |
| Acer          | TravelMate 5720             | [19a257005b](https://linux-hardware.org/?probe=19a257005b) | Apr 02, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [16f12d3bc8](https://linux-hardware.org/?probe=16f12d3bc8) | Apr 01, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [28142e5518](https://linux-hardware.org/?probe=28142e5518) | Apr 01, 2019 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e8fd67417e](https://linux-hardware.org/?probe=e8fd67417e) | Mar 29, 2019 |
| ASUSTek       | S551LN                      | [2c007f8b6c](https://linux-hardware.org/?probe=2c007f8b6c) | Mar 23, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [6f637899c4](https://linux-hardware.org/?probe=6f637899c4) | Mar 12, 2019 |
| HP            | Laptop 14-ck0xxx            | [620383c937](https://linux-hardware.org/?probe=620383c937) | Mar 07, 2019 |
| Acer          | Aspire 7220                 | [918907fa0a](https://linux-hardware.org/?probe=918907fa0a) | Mar 06, 2019 |
| ASUSTek       | N750JK                      | [29d535d30f](https://linux-hardware.org/?probe=29d535d30f) | Feb 15, 2019 |
| ASUSTek       | N750JK                      | [0a21e6bf0f](https://linux-hardware.org/?probe=0a21e6bf0f) | Feb 13, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [f5cf28dd23](https://linux-hardware.org/?probe=f5cf28dd23) | Jan 25, 2019 |
| ASUSTek       | N750JK                      | [e706aadaf7](https://linux-hardware.org/?probe=e706aadaf7) | Jan 16, 2019 |
| ASUSTek       | N750JK                      | [8e8a651043](https://linux-hardware.org/?probe=8e8a651043) | Jan 12, 2019 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [d87952f0b8](https://linux-hardware.org/?probe=d87952f0b8) | Dec 20, 2018 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [7f746478de](https://linux-hardware.org/?probe=7f746478de) | Dec 20, 2018 |
| Lenovo        | ThinkPad T530 24295XG       | [65d4845db2](https://linux-hardware.org/?probe=65d4845db2) | Dec 10, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [904c160172](https://linux-hardware.org/?probe=904c160172) | Nov 25, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [e71b0059ee](https://linux-hardware.org/?probe=e71b0059ee) | Nov 25, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [dc38e86871](https://linux-hardware.org/?probe=dc38e86871) | Jun 29, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [f521f460e8](https://linux-hardware.org/?probe=f521f460e8) | Jun 29, 2018 |
| Acer          | Aspire ES1-111M             | [782a0a4926](https://linux-hardware.org/?probe=782a0a4926) | Mar 25, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 90        | 15.96%  |
| Ubuntu 18.04                 | 48        | 8.51%   |
| Ubuntu 22.04                 | 34        | 6.03%   |
| Ubuntu 21.10                 | 15        | 2.66%   |
| OpenMandriva 4.2             | 12        | 2.13%   |
| Fedora 34                    | 12        | 2.13%   |
| Arch Rolling                 | 11        | 1.95%   |
| Arch                         | 11        | 1.95%   |
| Pop!_OS 22.04                | 10        | 1.77%   |
| Debian 11                    | 10        | 1.77%   |
| Manjaro                      | 9         | 1.6%    |
| Ubuntu 19.04                 | 8         | 1.42%   |
| Pop!_OS 20.04                | 8         | 1.42%   |
| OpenMandriva 23.03           | 8         | 1.42%   |
| Fedora 36                    | 8         | 1.42%   |
| Zorin 15                     | 7         | 1.24%   |
| Pop!_OS 21.04                | 7         | 1.24%   |
| Linux Mint 20.3              | 7         | 1.24%   |
| Linux Mint 20.2              | 7         | 1.24%   |
| KDE neon 20.04               | 7         | 1.24%   |
| Fedora 32                    | 7         | 1.24%   |
| Debian 10                    | 7         | 1.24%   |
| Ubuntu 22.10                 | 6         | 1.06%   |
| Ubuntu 20.10                 | 6         | 1.06%   |
| Pop!_OS 21.10                | 6         | 1.06%   |
| OpenMandriva 4.3             | 6         | 1.06%   |
| Linux Mint 21                | 6         | 1.06%   |
| Linux Mint 20.1              | 6         | 1.06%   |
| Fedora 38                    | 6         | 1.06%   |
| Fedora 37                    | 6         | 1.06%   |
| Fedora 33                    | 6         | 1.06%   |
| Xubuntu 20.04                | 5         | 0.89%   |
| Ubuntu 19.10                 | 5         | 0.89%   |
| Ubuntu 18.10                 | 5         | 0.89%   |
| Linux Mint 20                | 5         | 0.89%   |
| Fedora 35                    | 5         | 0.89%   |
| Zorin 16                     | 4         | 0.71%   |
| Ubuntu 21.04                 | 4         | 0.71%   |
| Pop!_OS 20.10                | 4         | 0.71%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 204       | 39.08%  |
| Fedora       | 47        | 9%      |
| Linux Mint   | 41        | 7.85%   |
| Pop!_OS      | 34        | 6.51%   |
| OpenMandriva | 28        | 5.36%   |
| Manjaro      | 21        | 4.02%   |
| Arch         | 21        | 4.02%   |
| Debian       | 19        | 3.64%   |
| Zorin        | 13        | 2.49%   |
| Kubuntu      | 13        | 2.49%   |
| Xubuntu      | 10        | 1.92%   |
| KDE neon     | 10        | 1.92%   |
| Ubuntu Unity | 5         | 0.96%   |
| ROSA         | 5         | 0.96%   |
| Elementary   | 5         | 0.96%   |
| Void Linux   | 4         | 0.77%   |
| openSUSE     | 4         | 0.77%   |
| EndeavourOS  | 4         | 0.77%   |
| ArcoLinux    | 4         | 0.77%   |
| Ubuntu MATE  | 3         | 0.57%   |
| Parrot       | 3         | 0.57%   |
| LMDE         | 3         | 0.57%   |
| Garuda Linux | 3         | 0.57%   |
| Clear Linux  | 3         | 0.57%   |
| SteamOS      | 2         | 0.38%   |
| Kali         | 2         | 0.38%   |
| Endless      | 2         | 0.38%   |
| Xero         | 1         | 0.19%   |
| TUXEDO OS    | 1         | 0.19%   |
| NixOS        | 1         | 0.19%   |
| Lubuntu      | 1         | 0.19%   |
| LinuxFX      | 1         | 0.19%   |
| Gentoo       | 1         | 0.19%   |
| GalliumOS    | 1         | 0.19%   |
| BlackPanther | 1         | 0.19%   |
| antiX        | 1         | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 14        | 2.27%   |
| 5.10.14-desktop-1omv4002 | 12        | 1.94%   |
| 6.2.6-desktop-1omv2390   | 8         | 1.3%    |
| 5.16.7-desktop-1omv4003  | 7         | 1.13%   |
| 5.15.0-56-generic        | 7         | 1.13%   |
| 5.4.0-52-generic         | 6         | 0.97%   |
| 5.4.0-48-generic         | 6         | 0.97%   |
| 5.4.0-26-generic         | 6         | 0.97%   |
| 5.4.0-7634-generic       | 5         | 0.81%   |
| 5.4.0-47-generic         | 5         | 0.81%   |
| 5.19.0-35-generic        | 5         | 0.81%   |
| 5.15.0-53-generic        | 5         | 0.81%   |
| 5.15.0-52-generic        | 5         | 0.81%   |
| 5.11.0-40-generic        | 5         | 0.81%   |
| 5.4.0-58-generic         | 4         | 0.65%   |
| 5.4.0-40-generic         | 4         | 0.65%   |
| 5.3.0-40-generic         | 4         | 0.65%   |
| 5.19.0-76051900-generic  | 4         | 0.65%   |
| 5.15.0-46-generic        | 4         | 0.65%   |
| 5.15.0-43-generic        | 4         | 0.65%   |
| 5.11.0-41-generic        | 4         | 0.65%   |
| 5.11.0-27-generic        | 4         | 0.65%   |
| 5.0.0-23-generic         | 4         | 0.65%   |
| 4.15.0-55-generic        | 4         | 0.65%   |
| 6.2.6-76060206-generic   | 3         | 0.49%   |
| 5.8.15-301.fc33.x86_64   | 3         | 0.49%   |
| 5.8.0-59-generic         | 3         | 0.49%   |
| 5.8.0-50-generic         | 3         | 0.49%   |
| 5.8.0-45-generic         | 3         | 0.49%   |
| 5.8.0-29-generic         | 3         | 0.49%   |
| 5.4.0-96-generic         | 3         | 0.49%   |
| 5.4.0-91-generic         | 3         | 0.49%   |
| 5.4.0-81-generic         | 3         | 0.49%   |
| 5.4.0-77-generic         | 3         | 0.49%   |
| 5.4.0-62-generic         | 3         | 0.49%   |
| 5.4.0-54-generic         | 3         | 0.49%   |
| 5.4.0-29-generic         | 3         | 0.49%   |
| 5.3.0-28-generic         | 3         | 0.49%   |
| 5.19.0-38-generic        | 3         | 0.49%   |
| 5.15.0-71-generic        | 3         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 93        | 16.06%  |
| 5.15.0  | 49        | 8.46%   |
| 5.11.0  | 36        | 6.22%   |
| 4.15.0  | 35        | 6.04%   |
| 5.8.0   | 28        | 4.84%   |
| 5.13.0  | 27        | 4.66%   |
| 5.19.0  | 24        | 4.15%   |
| 5.3.0   | 18        | 3.11%   |
| 5.0.0   | 17        | 2.94%   |
| 6.2.6   | 13        | 2.25%   |
| 4.18.0  | 13        | 2.25%   |
| 5.10.14 | 12        | 2.07%   |
| 5.10.0  | 12        | 2.07%   |
| 5.16.7  | 7         | 1.21%   |
| 4.19.0  | 7         | 1.21%   |
| 6.1.1   | 4         | 0.69%   |
| 5.7.15  | 4         | 0.69%   |
| 6.0.10  | 3         | 0.52%   |
| 5.9.0   | 3         | 0.52%   |
| 5.8.15  | 3         | 0.52%   |
| 5.4.18  | 3         | 0.52%   |
| 5.19.13 | 3         | 0.52%   |
| 5.16.0  | 3         | 0.52%   |
| 5.14.0  | 3         | 0.52%   |
| 5.13.12 | 3         | 0.52%   |
| 6.3.8   | 2         | 0.35%   |
| 6.2.14  | 2         | 0.35%   |
| 6.2.0   | 2         | 0.35%   |
| 6.1.0   | 2         | 0.35%   |
| 6.0.6   | 2         | 0.35%   |
| 6.0.0   | 2         | 0.35%   |
| 5.9.16  | 2         | 0.35%   |
| 5.9.14  | 2         | 0.35%   |
| 5.8.16  | 2         | 0.35%   |
| 5.8.11  | 2         | 0.35%   |
| 5.6.7   | 2         | 0.35%   |
| 5.4.8   | 2         | 0.35%   |
| 5.18.11 | 2         | 0.35%   |
| 5.17.5  | 2         | 0.35%   |
| 5.16.18 | 2         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 102       | 17.83%  |
| 5.15    | 69        | 12.06%  |
| 5.11    | 40        | 6.99%   |
| 5.8     | 39        | 6.82%   |
| 5.19    | 35        | 6.12%   |
| 4.15    | 35        | 6.12%   |
| 5.13    | 32        | 5.59%   |
| 5.10    | 30        | 5.24%   |
| 5.16    | 20        | 3.5%    |
| 6.2     | 19        | 3.32%   |
| 5.3     | 18        | 3.15%   |
| 5.0     | 18        | 3.15%   |
| 4.18    | 14        | 2.45%   |
| 6.1     | 13        | 2.27%   |
| 5.14    | 12        | 2.1%    |
| 6.0     | 11        | 1.92%   |
| 5.9     | 9         | 1.57%   |
| 4.19    | 8         | 1.4%    |
| 5.18    | 7         | 1.22%   |
| 5.7     | 6         | 1.05%   |
| 5.6     | 6         | 1.05%   |
| 5.17    | 6         | 1.05%   |
| 5.12    | 5         | 0.87%   |
| 6.3     | 4         | 0.7%    |
| 5.1     | 3         | 0.52%   |
| 4.9     | 2         | 0.35%   |
| 4.4     | 2         | 0.35%   |
| 4.14    | 2         | 0.35%   |
| 5.2     | 1         | 0.17%   |
| 4.16    | 1         | 0.17%   |
| 4.13    | 1         | 0.17%   |
| 4.10    | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 484       | 96.22%  |
| i686   | 19        | 3.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 262       | 49.62%  |
| KDE5            | 81        | 15.34%  |
| Unknown         | 71        | 13.45%  |
| X-Cinnamon      | 32        | 6.06%   |
| XFCE            | 31        | 5.87%   |
| KDE             | 13        | 2.46%   |
| MATE            | 12        | 2.27%   |
| Unity           | 5         | 0.95%   |
| i3              | 5         | 0.95%   |
| Pantheon        | 4         | 0.76%   |
| LXQt            | 3         | 0.57%   |
| GNOME Flashback | 2         | 0.38%   |
| Cinnamon        | 2         | 0.38%   |
| sway            | 1         | 0.19%   |
| qtile-default   | 1         | 0.19%   |
| LeftWM          | 1         | 0.19%   |
| icewm           | 1         | 0.19%   |
| awesome         | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 378       | 72%     |
| Wayland | 105       | 20%     |
| Unknown | 37        | 7.05%   |
| Tty     | 5         | 0.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 283       | 54.42%  |
| GDM     | 69        | 13.27%  |
| GDM3    | 66        | 12.69%  |
| SDDM    | 59        | 11.35%  |
| LightDM | 29        | 5.58%   |
| TDM     | 12        | 2.31%   |
| Ly      | 1         | 0.19%   |
| GREETD  | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 180       | 34.55%  |
| da_DK   | 151       | 28.98%  |
| en_DK   | 68        | 13.05%  |
| Unknown | 64        | 12.28%  |
| en_GB   | 30        | 5.76%   |
| de_DE   | 10        | 1.92%   |
| C       | 6         | 1.15%   |
| pl_PL   | 2         | 0.38%   |
| en_AG   | 2         | 0.38%   |
| zh_TW   | 1         | 0.19%   |
| pt_BR   | 1         | 0.19%   |
| nl_NL   | 1         | 0.19%   |
| it_IT   | 1         | 0.19%   |
| is_IS   | 1         | 0.19%   |
| fr_FR   | 1         | 0.19%   |
| en_CA   | 1         | 0.19%   |
| de_CH   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 263       | 51.27%  |
| BIOS | 250       | 48.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 394       | 76.36%  |
| Btrfs   | 63        | 12.21%  |
| Overlay | 26        | 5.04%   |
| Unknown | 20        | 3.88%   |
| Zfs     | 5         | 0.97%   |
| Tmpfs   | 5         | 0.97%   |
| Ext2    | 3         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 303       | 58.61%  |
| GPT     | 170       | 32.88%  |
| MBR     | 44        | 8.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 453       | 88.82%  |
| Yes       | 57        | 11.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 400       | 78.43%  |
| Yes       | 110       | 21.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 192       | 38.25%  |
| Hewlett-Packard     | 87        | 17.33%  |
| ASUSTek Computer    | 46        | 9.16%   |
| Dell                | 44        | 8.76%   |
| Acer                | 37        | 7.37%   |
| Apple               | 16        | 3.19%   |
| Toshiba             | 10        | 1.99%   |
| Notebook            | 9         | 1.79%   |
| MSI                 | 9         | 1.79%   |
| HUAWEI              | 5         | 1%      |
| Samsung Electronics | 4         | 0.8%    |
| Google              | 4         | 0.8%    |
| Razer               | 3         | 0.6%    |
| Medion              | 3         | 0.6%    |
| Valve               | 2         | 0.4%    |
| TUXEDO              | 2         | 0.4%    |
| Timi                | 2         | 0.4%    |
| Quanta              | 2         | 0.4%    |
| Packard Bell        | 2         | 0.4%    |
| GPD                 | 2         | 0.4%    |
| Fujitsu             | 2         | 0.4%    |
| eMachines           | 2         | 0.4%    |
| AMI                 | 2         | 0.4%    |
| Unknown             | 2         | 0.4%    |
| System76            | 1         | 0.2%    |
| Standard            | 1         | 0.2%    |
| SLIMBOOK            | 1         | 0.2%    |
| Purism              | 1         | 0.2%    |
| LG Electronics      | 1         | 0.2%    |
| LAMINA              | 1         | 0.2%    |
| Komplett            | 1         | 0.2%    |
| IBM                 | 1         | 0.2%    |
| Fujitsu Siemens     | 1         | 0.2%    |
| Framework           | 1         | 0.2%    |
| DukaPC              | 1         | 0.2%    |
| Dixonsxp            | 1         | 0.2%    |
| Alienware           | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 9         | 1.79%   |
| HP Pavilion dv7                       | 5         | 1%      |
| Dell XPS 15 9570                      | 4         | 0.8%    |
| HP OMEN by Laptop                     | 3         | 0.6%    |
| HP Notebook                           | 3         | 0.6%    |
| HP EliteBook 820 G3                   | 3         | 0.6%    |
| Dell XPS 13 9370                      | 3         | 0.6%    |
| Dell Latitude 7480                    | 3         | 0.6%    |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK | 3         | 0.6%    |
| Apple MacBookPro9,2                   | 3         | 0.6%    |
| Apple MacBookPro5,5                   | 3         | 0.6%    |
| Valve Jupiter                         | 2         | 0.4%    |
| Toshiba Satellite L40                 | 2         | 0.4%    |
| Quanta MW1/HW1                        | 2         | 0.4%    |
| Notebook W54_55SU1,SUW                | 2         | 0.4%    |
| Lenovo ThinkPad T530 24295L4          | 2         | 0.4%    |
| Lenovo ThinkBook 15 G2 ARE 20VG       | 2         | 0.4%    |
| Lenovo Legion 5 15ACH6H 82JU          | 2         | 0.4%    |
| Lenovo IdeaPad S130-14IGM 81J2        | 2         | 0.4%    |
| Lenovo IdeaPad 310-15IKB 80TV         | 2         | 0.4%    |
| Lenovo G505 20240                     | 2         | 0.4%    |
| Lenovo E31-80 80MX                    | 2         | 0.4%    |
| HP ProBook 650 G1                     | 2         | 0.4%    |
| HP Pavilion Notebook                  | 2         | 0.4%    |
| HP Pavilion g7                        | 2         | 0.4%    |
| HP Pavilion 15                        | 2         | 0.4%    |
| HP Laptop 15s-eq2xxx                  | 2         | 0.4%    |
| HP Laptop 15-bw0xx                    | 2         | 0.4%    |
| HP EliteBook 845 G7 Notebook PC       | 2         | 0.4%    |
| HP EliteBook 840 G6                   | 2         | 0.4%    |
| HP EliteBook 840 G1                   | 2         | 0.4%    |
| HP Compaq Presario CQ71               | 2         | 0.4%    |
| eMachines E725                        | 2         | 0.4%    |
| Dell XPS 15 9560                      | 2         | 0.4%    |
| Dell Latitude E7440                   | 2         | 0.4%    |
| Apple MacBookPro7,1                   | 2         | 0.4%    |
| Apple MacBookPro14,1                  | 2         | 0.4%    |
| Acer Aspire E5-575G                   | 2         | 0.4%    |
| TUXEDO Pulse 15 Gen1                  | 1         | 0.2%    |
| Toshiba Satellite U300                | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 139       | 27.69%  |
| Acer Aspire           | 25        | 4.98%   |
| HP EliteBook          | 23        | 4.58%   |
| HP Pavilion           | 20        | 3.98%   |
| Dell Latitude         | 19        | 3.78%   |
| Lenovo IdeaPad        | 17        | 3.39%   |
| Dell XPS              | 13        | 2.59%   |
| HP ProBook            | 11        | 2.19%   |
| Toshiba Satellite     | 10        | 1.99%   |
| ASUS ROG              | 10        | 1.99%   |
| HP Laptop             | 9         | 1.79%   |
| Unknown               | 9         | 1.79%   |
| Dell Inspiron         | 7         | 1.39%   |
| ASUS ZenBook          | 7         | 1.39%   |
| HP Compaq             | 6         | 1.2%    |
| Lenovo ThinkBook      | 5         | 1%      |
| Lenovo Legion         | 5         | 1%      |
| ASUS VivoBook         | 5         | 1%      |
| HP OMEN               | 4         | 0.8%    |
| Acer Swift            | 4         | 0.8%    |
| Razer Blade           | 3         | 0.6%    |
| Lenovo Yoga           | 3         | 0.6%    |
| HP ZBook              | 3         | 0.6%    |
| HP Notebook           | 3         | 0.6%    |
| Dell Precision        | 3         | 0.6%    |
| Apple MacBookPro9     | 3         | 0.6%    |
| Apple MacBookPro5     | 3         | 0.6%    |
| Valve Jupiter         | 2         | 0.4%    |
| Quanta MW1            | 2         | 0.4%    |
| Packard Bell EasyNote | 2         | 0.4%    |
| Notebook W54          | 2         | 0.4%    |
| MSI GV62              | 2         | 0.4%    |
| Lenovo G505           | 2         | 0.4%    |
| Lenovo E31-80         | 2         | 0.4%    |
| Lenovo 3000           | 2         | 0.4%    |
| Fujitsu LIFEBOOK      | 2         | 0.4%    |
| eMachines E725        | 2         | 0.4%    |
| ASUS TUF              | 2         | 0.4%    |
| ASUS ASUS             | 2         | 0.4%    |
| Apple MacBookPro7     | 2         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 45        | 8.96%   |
| 2018    | 45        | 8.96%   |
| 2013    | 41        | 8.17%   |
| 2020    | 40        | 7.97%   |
| 2017    | 40        | 7.97%   |
| 2021    | 38        | 7.57%   |
| 2015    | 38        | 7.57%   |
| 2012    | 36        | 7.17%   |
| 2011    | 34        | 6.77%   |
| 2016    | 32        | 6.37%   |
| 2014    | 23        | 4.58%   |
| 2009    | 21        | 4.18%   |
| 2010    | 20        | 3.98%   |
| 2022    | 14        | 2.79%   |
| 2008    | 14        | 2.79%   |
| 2007    | 14        | 2.79%   |
| 2006    | 5         | 1%      |
| 2003    | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 502       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 443       | 87.55%  |
| Enabled  | 63        | 12.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 497       | 99%     |
| Yes  | 5         | 1%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 153       | 29.82%  |
| 8.01-16.0   | 102       | 19.88%  |
| 16.01-24.0  | 91        | 17.74%  |
| 3.01-4.0    | 80        | 15.59%  |
| 32.01-64.0  | 43        | 8.38%   |
| 1.01-2.0    | 15        | 2.92%   |
| 2.01-3.0    | 10        | 1.95%   |
| 24.01-32.0  | 9         | 1.75%   |
| 64.01-256.0 | 8         | 1.56%   |
| 0.51-1.0    | 1         | 0.19%   |
| 0.01-0.5    | 1         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 177       | 31.66%  |
| 2.01-3.0   | 154       | 27.55%  |
| 4.01-8.0   | 98        | 17.53%  |
| 3.01-4.0   | 82        | 14.67%  |
| 0.51-1.0   | 25        | 4.47%   |
| 8.01-16.0  | 15        | 2.68%   |
| 0.01-0.5   | 5         | 0.89%   |
| 16.01-24.0 | 2         | 0.36%   |
| 32.01-64.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 401       | 78.47%  |
| 2      | 95        | 18.59%  |
| 3      | 11        | 2.15%   |
| 0      | 3         | 0.59%   |
| 4      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 345       | 68.05%  |
| Yes       | 162       | 31.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 428       | 84.75%  |
| No        | 77        | 15.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 496       | 98.8%   |
| No        | 6         | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 423       | 82.46%  |
| No        | 90        | 17.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Denmark | 502       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Copenhagen            | 114       | 21.35%  |
| Frederiksberg         | 35        | 6.55%   |
| Odense                | 34        | 6.37%   |
| Aarhus                | 19        | 3.56%   |
| Bronshoj              | 15        | 2.81%   |
| Aalborg               | 13        | 2.43%   |
| Silkeborg             | 11        | 2.06%   |
| Slagelse              | 10        | 1.87%   |
| Holstebro             | 9         | 1.69%   |
| Valby                 | 8         | 1.5%    |
| Norresundby           | 8         | 1.5%    |
| Kongens Lyngby        | 8         | 1.5%    |
| Glostrup Municipality | 8         | 1.5%    |
| Esbjerg               | 8         | 1.5%    |
| Gentofte Municipality | 7         | 1.31%   |
| Aabenraa              | 7         | 1.31%   |
| Skanderborg           | 6         | 1.12%   |
| Roskilde              | 6         | 1.12%   |
| Naestved              | 6         | 1.12%   |
| Horsens               | 6         | 1.12%   |
| Taastrup              | 5         | 0.94%   |
| Nyborg                | 5         | 0.94%   |
| Kastrup               | 5         | 0.94%   |
| Hvidovre              | 5         | 0.94%   |
| Herlev                | 5         | 0.94%   |
| Elsinore              | 5         | 0.94%   |
| Vanlose               | 4         | 0.75%   |
| Thisted               | 4         | 0.75%   |
| Skive                 | 4         | 0.75%   |
| Sindal                | 4         | 0.75%   |
| Risskov               | 4         | 0.75%   |
| Hojbjerg              | 4         | 0.75%   |
| Vejle                 | 3         | 0.56%   |
| Vaerlose              | 3         | 0.56%   |
| Svendborg             | 3         | 0.56%   |
| Rønne                | 3         | 0.56%   |
| Kolding               | 3         | 0.56%   |
| Holte                 | 3         | 0.56%   |
| Hadsund               | 3         | 0.56%   |
| Brønderslev          | 3         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 150       | 206    | 25.42%  |
| WDC                         | 63        | 81     | 10.68%  |
| Seagate                     | 46        | 54     | 7.8%    |
| Toshiba                     | 42        | 61     | 7.12%   |
| Kingston                    | 40        | 52     | 6.78%   |
| SK hynix                    | 37        | 51     | 6.27%   |
| Sandisk                     | 27        | 34     | 4.58%   |
| Unknown                     | 25        | 31     | 4.24%   |
| Hitachi                     | 24        | 30     | 4.07%   |
| Intel                       | 22        | 25     | 3.73%   |
| Micron Technology           | 18        | 22     | 3.05%   |
| HGST                        | 15        | 20     | 2.54%   |
| LITEON                      | 10        | 22     | 1.69%   |
| PNY                         | 8         | 8      | 1.36%   |
| Intenso                     | 8         | 10     | 1.36%   |
| Apple                       | 7         | 9      | 1.19%   |
| Crucial                     | 6         | 6      | 1.02%   |
| LITEONIT                    | 4         | 5      | 0.68%   |
| Lenovo                      | 4         | 5      | 0.68%   |
| A-DATA Technology           | 4         | 4      | 0.68%   |
| OCZ                         | 3         | 3      | 0.51%   |
| KIOXIA                      | 3         | 4      | 0.51%   |
| USB3.0                      | 2         | 2      | 0.34%   |
| Silicon Motion              | 2         | 2      | 0.34%   |
| Phison Electronics          | 2         | 2      | 0.34%   |
| Fujitsu                     | 2         | 3      | 0.34%   |
| China                       | 2         | 2      | 0.34%   |
| XPG                         | 1         | 1      | 0.17%   |
| UMIS                        | 1         | 1      | 0.17%   |
| Transcend                   | 1         | 1      | 0.17%   |
| Solid State Storage         | 1         | 1      | 0.17%   |
| Phison                      | 1         | 2      | 0.17%   |
| Micron/Crucial Technology   | 1         | 1      | 0.17%   |
| Kingston Technology Company | 1         | 1      | 0.17%   |
| KingFast                    | 1         | 1      | 0.17%   |
| Kingchuxing                 | 1         | 1      | 0.17%   |
| Hewlett-Packard             | 1         | 1      | 0.17%   |
| Dogfish                     | 1         | 1      | 0.17%   |
| ASUS-PHISON                 | 1         | 1      | 0.17%   |
| Apricorn                    | 1         | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 10        | 1.61%   |
| Samsung NVMe SSD Drive 256GB                        | 10        | 1.61%   |
| Samsung SSD 850 EVO 500GB                           | 9         | 1.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 1.13%   |
| Toshiba NVMe SSD Drive 512GB                        | 6         | 0.97%   |
| Samsung NVMe SSD Drive 512GB                        | 6         | 0.97%   |
| Kingston SA400S37480G 480GB SSD                     | 6         | 0.97%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 0.97%   |
| Unknown MMC Card  32GB                              | 5         | 0.81%   |
| SK hynix NVMe SSD Drive 512GB                       | 5         | 0.81%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 0.81%   |
| Samsung NVMe SSD Drive 1024GB                       | 5         | 0.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 5         | 0.81%   |
| HGST HTS721010A9E630 1TB                            | 5         | 0.81%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 4         | 0.65%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 4         | 0.65%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 4         | 0.65%   |
| Seagate ST2000LM015-2E8174 2TB                      | 4         | 0.65%   |
| Samsung MZVLB512HAJQ-000L7 512GB                    | 4         | 0.65%   |
| PNY CS900 120GB SSD                                 | 4         | 0.65%   |
| WDC WD2500BEVT-60ZCT1 250GB                         | 3         | 0.48%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 0.48%   |
| Unknown MMC Card  64GB                              | 3         | 0.48%   |
| Toshiba XG6 NVMe SSD Controller 2TB                 | 3         | 0.48%   |
| Toshiba THNSFJ256GCSU 256GB SSD                     | 3         | 0.48%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB              | 3         | 0.48%   |
| SK hynix NVMe SSD Drive 256GB                       | 3         | 0.48%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 0.48%   |
| Seagate ST1000LM048-2E7172 1TB                      | 3         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.48%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.48%   |
| Samsung SSD 840 EVO 250GB                           | 3         | 0.48%   |
| Samsung MZVLB1T0HBLR-000L7 1TB                      | 3         | 0.48%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.48%   |
| Kingston SV300S37A240G 240GB SSD                    | 3         | 0.48%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 0.48%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 0.48%   |
| Intel NVMe SSD Drive 512GB                          | 3         | 0.48%   |
| HGST HTS545050A7E380 500GB                          | 3         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 45        | 53     | 32.37%  |
| WDC      | 35        | 47     | 25.18%  |
| Hitachi  | 24        | 30     | 17.27%  |
| HGST     | 15        | 20     | 10.79%  |
| Toshiba  | 14        | 15     | 10.07%  |
| USB3.0   | 2         | 2      | 1.44%   |
| Fujitsu  | 2         | 3      | 1.44%   |
| Apricorn | 1         | 2      | 0.72%   |
| Apple    | 1         | 2      | 0.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 80        | 103    | 35.71%  |
| Kingston            | 34        | 45     | 15.18%  |
| SanDisk             | 14        | 17     | 6.25%   |
| WDC                 | 12        | 15     | 5.36%   |
| Toshiba             | 12        | 14     | 5.36%   |
| LITEON              | 9         | 21     | 4.02%   |
| SK hynix            | 8         | 10     | 3.57%   |
| PNY                 | 8         | 8      | 3.57%   |
| Micron Technology   | 7         | 8      | 3.13%   |
| Intel               | 7         | 8      | 3.13%   |
| Intenso             | 6         | 8      | 2.68%   |
| Crucial             | 5         | 5      | 2.23%   |
| Apple               | 5         | 5      | 2.23%   |
| LITEONIT            | 4         | 5      | 1.79%   |
| A-DATA Technology   | 4         | 4      | 1.79%   |
| OCZ                 | 3         | 3      | 1.34%   |
| China               | 2         | 2      | 0.89%   |
| KingFast            | 1         | 1      | 0.45%   |
| Kingchuxing         | 1         | 1      | 0.45%   |
| Dogfish             | 1         | 1      | 0.45%   |
| ASUS-PHISON         | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 215       | 285    | 37.99%  |
| NVMe    | 190       | 276    | 33.57%  |
| HDD     | 131       | 174    | 23.14%  |
| MMC     | 26        | 32     | 4.59%   |
| Unknown | 4         | 4      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 318       | 449    | 58.14%  |
| NVMe | 190       | 276    | 34.73%  |
| MMC  | 26        | 32     | 4.75%   |
| SAS  | 13        | 14     | 2.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 251       | 347    | 72.75%  |
| 0.51-1.0   | 77        | 91     | 22.32%  |
| 1.01-2.0   | 14        | 18     | 4.06%   |
| 4.01-10.0  | 3         | 3      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 168       | 31.4%   |
| 251-500        | 119       | 22.24%  |
| 501-1000       | 77        | 14.39%  |
| 1-20           | 39        | 7.29%   |
| 51-100         | 35        | 6.54%   |
| 1001-2000      | 29        | 5.42%   |
| Unknown        | 28        | 5.23%   |
| 21-50          | 18        | 3.36%   |
| More than 3000 | 11        | 2.06%   |
| 2001-3000      | 11        | 2.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 225       | 40.98%  |
| 21-50          | 91        | 16.58%  |
| 101-250        | 66        | 12.02%  |
| 51-100         | 60        | 10.93%  |
| 251-500        | 43        | 7.83%   |
| Unknown        | 28        | 5.1%    |
| 501-1000       | 23        | 4.19%   |
| 1001-2000      | 8         | 1.46%   |
| 2001-3000      | 3         | 0.55%   |
| More than 3000 | 2         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 10%     |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 10%     |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 5%      |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 5%      |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 5%      |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 5%      |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 5%      |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 5%      |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 1         | 1      | 5%      |
| Seagate ST9500420AS 500GB             | 1         | 1      | 5%      |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 5%      |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 5%      |
| Micron Technology 1100 SATA 512GB SSD | 1         | 1      | 5%      |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 5%      |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 5%      |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 5%      |
| Apple HDD HTS547550A9E384 500GB       | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 30%     |
| HGST              | 4         | 4      | 20%     |
| WDC               | 3         | 3      | 15%     |
| Toshiba           | 3         | 3      | 15%     |
| SK hynix          | 1         | 1      | 5%      |
| Micron Technology | 1         | 1      | 5%      |
| Kingston          | 1         | 1      | 5%      |
| Apple             | 1         | 1      | 5%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 42.86%  |
| HGST    | 4         | 4      | 28.57%  |
| WDC     | 2         | 2      | 14.29%  |
| Toshiba | 1         | 1      | 7.14%   |
| Apple   | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 70%     |
| SSD  | 5         | 5      | 25%     |
| NVMe | 1         | 1      | 5%      |

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
| Detected | 341       | 532    | 64.22%  |
| Works    | 170       | 219    | 32.02%  |
| Malfunc  | 20        | 20     | 3.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 319       | 56.16%  |
| Samsung Electronics              | 78        | 13.73%  |
| AMD                              | 48        | 8.45%   |
| SK hynix                         | 28        | 4.93%   |
| SanDisk                          | 28        | 4.93%   |
| Toshiba America Info Systems     | 17        | 2.99%   |
| Micron Technology                | 12        | 2.11%   |
| Nvidia                           | 8         | 1.41%   |
| Kingston Technology Company      | 6         | 1.06%   |
| Silicon Motion                   | 5         | 0.88%   |
| Lenovo                           | 4         | 0.7%    |
| Phison Electronics               | 3         | 0.53%   |
| KIOXIA                           | 2         | 0.35%   |
| ADATA Technology                 | 2         | 0.35%   |
| Union Memory (Shenzhen)          | 1         | 0.18%   |
| Solid State Storage Technology   | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Micron/Crucial Technology        | 1         | 0.18%   |
| Lite-On Technology               | 1         | 0.18%   |
| JMicron Technology               | 1         | 0.18%   |
| ASMedia Technology               | 1         | 0.18%   |
| Apple                            | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 47        | 7.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 42        | 6.86%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 39        | 6.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 33        | 5.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 31        | 5.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 28        | 4.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20        | 3.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 3.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 18        | 2.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 18        | 2.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 14        | 2.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 1.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 12        | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 11        | 1.8%    |
| Samsung NVMe SSD Controller 980                                                | 10        | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 10        | 1.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 10        | 1.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 1.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 8         | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.14%   |
| SanDisk PC SN530 NVMe SSD                                                      | 6         | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 0.98%   |
| Micron NVMe Storage Controller                                                 | 6         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 0.98%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 5         | 0.82%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 5         | 0.82%   |
| Intel SSD 660P Series                                                          | 5         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 0.82%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 4         | 0.65%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 4         | 0.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 0.65%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 0.65%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 4         | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 4         | 0.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 4         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 4         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 328       | 56.26%  |
| NVMe | 191       | 32.76%  |
| IDE  | 37        | 6.35%   |
| RAID | 27        | 4.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 408       | 81.27%  |
| AMD    | 94        | 18.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 14        | 2.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 10        | 1.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 10        | 1.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 10        | 1.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 8         | 1.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 8         | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 8         | 1.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 7         | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 7         | 1.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 1.39%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 6         | 1.2%    |
| Intel Core i7-6600U CPU @ 2.60GHz           | 6         | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 6         | 1.2%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 6         | 1.2%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 6         | 1.2%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 6         | 1.2%    |
| Intel Core i7-8665U CPU @ 1.90GHz           | 5         | 1%      |
| Intel Core i7-8650U CPU @ 1.90GHz           | 5         | 1%      |
| Intel Core i5-6300U CPU @ 2.40GHz           | 5         | 1%      |
| AMD Ryzen 7 5700U with Radeon Graphics      | 5         | 1%      |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 4         | 0.8%    |
| Intel Core i7-7600U CPU @ 2.80GHz           | 4         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 4         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 4         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 0.8%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 4         | 0.8%    |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 4         | 0.8%    |
| Intel Core i7-10875H CPU @ 2.30GHz          | 4         | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 0.8%    |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 0.8%    |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 4         | 0.8%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 4         | 0.8%    |
| AMD Ryzen 9 5900HS with Radeon Graphics     | 4         | 0.8%    |
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 0.8%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 3         | 0.6%    |
| Intel Core i7-4600U CPU @ 2.10GHz           | 3         | 0.6%    |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 3         | 0.6%    |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 145       | 28.88%  |
| Intel Core i7                  | 142       | 28.29%  |
| Other                          | 24        | 4.78%   |
| Intel Core 2 Duo               | 23        | 4.58%   |
| AMD Ryzen 7                    | 20        | 3.98%   |
| Intel Core i3                  | 18        | 3.59%   |
| Intel Celeron                  | 17        | 3.39%   |
| AMD Ryzen 5                    | 14        | 2.79%   |
| AMD Ryzen 7 PRO                | 10        | 1.99%   |
| Intel Pentium                  | 9         | 1.79%   |
| AMD Ryzen 9                    | 8         | 1.59%   |
| Intel Pentium Dual-Core        | 7         | 1.39%   |
| Intel Atom                     | 6         | 1.2%    |
| Intel Core i9                  | 5         | 1%      |
| AMD A6                         | 5         | 1%      |
| AMD Ryzen 5 PRO                | 4         | 0.8%    |
| AMD E1                         | 4         | 0.8%    |
| AMD A8                         | 4         | 0.8%    |
| Intel Pentium M                | 3         | 0.6%    |
| AMD Ryzen 3                    | 3         | 0.6%    |
| AMD E                          | 3         | 0.6%    |
| Intel Pentium Silver           | 2         | 0.4%    |
| Intel Pentium Dual             | 2         | 0.4%    |
| Intel Genuine                  | 2         | 0.4%    |
| Intel Core m3                  | 2         | 0.4%    |
| Intel Core 2                   | 2         | 0.4%    |
| AMD Turion 64 X2 Mobile        | 2         | 0.4%    |
| AMD Athlon                     | 2         | 0.4%    |
| AMD A4                         | 2         | 0.4%    |
| AMD A10                        | 2         | 0.4%    |
| Intel Core m7                  | 1         | 0.2%    |
| Intel Celeron M                | 1         | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.2%    |
| AMD FX                         | 1         | 0.2%    |
| AMD E2                         | 1         | 0.2%    |
| AMD Athlon X2                  | 1         | 0.2%    |
| AMD Athlon Neo                 | 1         | 0.2%    |
| AMD Athlon II Neo              | 1         | 0.2%    |
| AMD Athlon II Dual-Core        | 1         | 0.2%    |
| AMD Athlon II                  | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 251       | 50%     |
| 4      | 156       | 31.08%  |
| 8      | 44        | 8.76%   |
| 6      | 34        | 6.77%   |
| 1      | 14        | 2.79%   |
| 12     | 2         | 0.4%    |
| 14     | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 502       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 388       | 77.29%  |
| 1      | 113       | 22.51%  |
| 4      | 1         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 486       | 96.43%  |
| Unknown        | 13        | 2.58%   |
| 32-bit         | 5         | 0.99%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 25.29%  |
| 0x40651    | 27        | 5.17%   |
| 0x306a9    | 26        | 4.98%   |
| 0x206a7    | 26        | 4.98%   |
| 0x406e3    | 23        | 4.41%   |
| 0x1067a    | 19        | 3.64%   |
| 0x806ea    | 18        | 3.45%   |
| 0x806e9    | 18        | 3.45%   |
| 0x306c3    | 17        | 3.26%   |
| 0x906ea    | 16        | 3.07%   |
| 0x806ec    | 15        | 2.87%   |
| 0x20655    | 12        | 2.3%    |
| 0x806c1    | 11        | 2.11%   |
| 0x0a50000c | 10        | 1.92%   |
| 0x906e9    | 9         | 1.72%   |
| 0x08600106 | 8         | 1.53%   |
| 0x906ed    | 6         | 1.15%   |
| 0x806eb    | 6         | 1.15%   |
| 0x20652    | 6         | 1.15%   |
| 0x08600104 | 6         | 1.15%   |
| 0x706e5    | 5         | 0.96%   |
| 0x506e3    | 5         | 0.96%   |
| 0x08608103 | 5         | 0.96%   |
| 0x08108102 | 5         | 0.96%   |
| 0x07030105 | 5         | 0.96%   |
| 0x6fd      | 4         | 0.77%   |
| 0x406c3    | 4         | 0.77%   |
| 0x306d4    | 4         | 0.77%   |
| 0x30678    | 4         | 0.77%   |
| 0x10676    | 4         | 0.77%   |
| 0x0a404102 | 4         | 0.77%   |
| 0x0810100b | 4         | 0.77%   |
| 0xa0652    | 3         | 0.57%   |
| 0x706a1    | 3         | 0.57%   |
| 0x6d8      | 3         | 0.57%   |
| 0x406c4    | 3         | 0.57%   |
| 0x906a3    | 2         | 0.38%   |
| 0x6fb      | 2         | 0.38%   |
| 0x6fa      | 2         | 0.38%   |
| 0x6f6      | 2         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 115       | 22.91%  |
| Haswell          | 53        | 10.56%  |
| Skylake          | 40        | 7.97%   |
| SandyBridge      | 36        | 7.17%   |
| IvyBridge        | 34        | 6.77%   |
| Penryn           | 26        | 5.18%   |
| Westmere         | 19        | 3.78%   |
| Zen 2            | 17        | 3.39%   |
| Unknown          | 17        | 3.39%   |
| Zen 3            | 16        | 3.19%   |
| TigerLake        | 15        | 2.99%   |
| Silvermont       | 13        | 2.59%   |
| Core             | 13        | 2.59%   |
| Broadwell        | 11        | 2.19%   |
| Zen+             | 10        | 1.99%   |
| CometLake        | 7         | 1.39%   |
| Puma             | 6         | 1.2%    |
| IceLake          | 6         | 1.2%    |
| Excavator        | 6         | 1.2%    |
| P6               | 5         | 1%      |
| Bobcat           | 5         | 1%      |
| Zen              | 4         | 0.8%    |
| Goldmont plus    | 4         | 0.8%    |
| K8 Hammer        | 3         | 0.6%    |
| K8 & K10 hybrid  | 3         | 0.6%    |
| K10              | 3         | 0.6%    |
| Alderlake Hybrid | 3         | 0.6%    |
| Steamroller      | 2         | 0.4%    |
| Nehalem          | 2         | 0.4%    |
| Jaguar           | 2         | 0.4%    |
| Goldmont         | 2         | 0.4%    |
| Bonnell          | 2         | 0.4%    |
| Piledriver       | 1         | 0.2%    |
| K10 Llano        | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 361       | 57.21%  |
| Nvidia                           | 150       | 23.77%  |
| AMD                              | 119       | 18.86%  |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 5.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 32        | 4.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 31        | 4.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 4.62%   |
| Intel UHD Graphics 620                                                                   | 26        | 4%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 3.69%   |
| Intel HD Graphics 620                                                                    | 21        | 3.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 18        | 2.77%   |
| AMD Renoir                                                                               | 17        | 2.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 2.46%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 2.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 2%      |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.54%   |
| Intel HD Graphics 630                                                                    | 9         | 1.38%   |
| Intel HD Graphics 5500                                                                   | 9         | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 1.23%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 1.08%   |
| AMD Lucienne                                                                             | 7         | 1.08%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.92%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 0.92%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.77%   |
| Intel HD Graphics 530                                                                    | 5         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.62%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 4         | 0.62%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 4         | 0.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.62%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.62%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 4         | 0.62%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 244       | 48.41%  |
| Intel + Nvidia | 98        | 19.44%  |
| 1 x AMD        | 78        | 15.48%  |
| 1 x Nvidia     | 38        | 7.54%   |
| Intel + AMD    | 17        | 3.37%   |
| AMD + Nvidia   | 13        | 2.58%   |
| 2 x AMD        | 12        | 2.38%   |
| Other          | 2         | 0.4%    |
| 2 x Intel      | 1         | 0.2%    |
| 1 x SiS        | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 420       | 82.84%  |
| Proprietary | 75        | 14.79%  |
| Unknown     | 12        | 2.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 314       | 61.45%  |
| 0.01-0.5   | 69        | 13.5%   |
| 1.01-2.0   | 60        | 11.74%  |
| 3.01-4.0   | 26        | 5.09%   |
| 0.51-1.0   | 26        | 5.09%   |
| 5.01-6.0   | 9         | 1.76%   |
| 7.01-8.0   | 5         | 0.98%   |
| 2.01-3.0   | 2         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 124       | 21.34%  |
| LG Display              | 90        | 15.49%  |
| Chimei Innolux          | 66        | 11.36%  |
| BOE                     | 61        | 10.5%   |
| Samsung Electronics     | 52        | 8.95%   |
| Lenovo                  | 35        | 6.02%   |
| Sharp                   | 18        | 3.1%    |
| Dell                    | 18        | 3.1%    |
| Apple                   | 16        | 2.75%   |
| Chi Mei Optoelectronics | 11        | 1.89%   |
| Philips                 | 9         | 1.55%   |
| PANDA                   | 8         | 1.38%   |
| Hewlett-Packard         | 7         | 1.2%    |
| AOC                     | 7         | 1.2%    |
| InfoVision              | 5         | 0.86%   |
| Goldstar                | 5         | 0.86%   |
| ASUSTek Computer        | 4         | 0.69%   |
| Sony                    | 3         | 0.52%   |
| Panasonic               | 3         | 0.52%   |
| LG Philips              | 3         | 0.52%   |
| BenQ                    | 3         | 0.52%   |
| TMX                     | 2         | 0.34%   |
| Seiko/Epson             | 2         | 0.34%   |
| Packard Bell            | 2         | 0.34%   |
| LGD                     | 2         | 0.34%   |
| CSO                     | 2         | 0.34%   |
| CPT                     | 2         | 0.34%   |
| Acer                    | 2         | 0.34%   |
| ViewSonic               | 1         | 0.17%   |
| Vestel Elektronik       | 1         | 0.17%   |
| Valve                   | 1         | 0.17%   |
| Toshiba                 | 1         | 0.17%   |
| Tianma XM               | 1         | 0.17%   |
| RTK                     | 1         | 0.17%   |
| PVT                     | 1         | 0.17%   |
| MSI                     | 1         | 0.17%   |
| Lenovo Group Limited    | 1         | 0.17%   |
| JDI                     | 1         | 0.17%   |
| IBM                     | 1         | 0.17%   |
| HKC                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 8         | 1.34%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 6         | 1.01%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.84%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 5         | 0.84%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 4         | 0.67%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 3         | 0.5%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.5%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 3         | 0.5%    |
| Lenovo LCD Monitor LEN4011 1280x800 260x170mm 12.2-inch                  | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch         | 3         | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.5%    |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                    | 3         | 0.5%    |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                    | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x173mm 13.9-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO12ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.5%    |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 3         | 0.5%    |
| TMX TL140BDXP02-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 2         | 0.34%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.34%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.34%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch     | 2         | 0.34%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.34%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 250       | 45.45%  |
| 1366x768 (WXGA)    | 100       | 18.18%  |
| 1600x900 (HD+)     | 46        | 8.36%   |
| 3840x2160 (4K)     | 39        | 7.09%   |
| 2560x1440 (QHD)    | 27        | 4.91%   |
| 1280x800 (WXGA)    | 20        | 3.64%   |
| 1920x1200 (WUXGA)  | 10        | 1.82%   |
| 1680x1050 (WSXGA+) | 9         | 1.64%   |
| 1440x900 (WXGA+)   | 9         | 1.64%   |
| 2560x1600          | 7         | 1.27%   |
| 2880x1800          | 6         | 1.09%   |
| 3440x1440          | 4         | 0.73%   |
| 1400x1050          | 3         | 0.55%   |
| 800x1280           | 2         | 0.36%   |
| 3840x2400          | 2         | 0.36%   |
| 3200x1800 (QHD+)   | 2         | 0.36%   |
| 3000x2000          | 2         | 0.36%   |
| 1280x1024 (SXGA)   | 2         | 0.36%   |
| 1024x600           | 2         | 0.36%   |
| 3840x1600          | 1         | 0.18%   |
| 3840x1100          | 1         | 0.18%   |
| 3840x1080          | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 2160x1440          | 1         | 0.18%   |
| 1920x540           | 1         | 0.18%   |
| 1360x768           | 1         | 0.18%   |
| Unknown            | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 215       | 36.75%  |
| 14      | 92        | 15.73%  |
| 13      | 84        | 14.36%  |
| 17      | 46        | 7.86%   |
| 12      | 26        | 4.44%   |
| 27      | 25        | 4.27%   |
| 24      | 20        | 3.42%   |
| 23      | 12        | 2.05%   |
| Unknown | 11        | 1.88%   |
| 31      | 10        | 1.71%   |
| 84      | 5         | 0.85%   |
| 22      | 5         | 0.85%   |
| 11      | 5         | 0.85%   |
| 34      | 4         | 0.68%   |
| 21      | 3         | 0.51%   |
| 18      | 3         | 0.51%   |
| 10      | 3         | 0.51%   |
| 72      | 2         | 0.34%   |
| 25      | 2         | 0.34%   |
| 19      | 2         | 0.34%   |
| 16      | 2         | 0.34%   |
| 74      | 1         | 0.17%   |
| 65      | 1         | 0.17%   |
| 57      | 1         | 0.17%   |
| 37      | 1         | 0.17%   |
| 32      | 1         | 0.17%   |
| 29      | 1         | 0.17%   |
| 7       | 1         | 0.17%   |
| 3       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 341       | 59%     |
| 201-300     | 77        | 13.32%  |
| 351-400     | 54        | 9.34%   |
| 501-600     | 50        | 8.65%   |
| 601-700     | 16        | 2.77%   |
| 401-500     | 11        | 1.9%    |
| Unknown     | 11        | 1.9%    |
| 1501-2000   | 8         | 1.38%   |
| 701-800     | 5         | 0.87%   |
| 1001-1500   | 2         | 0.35%   |
| 1-100       | 2         | 0.35%   |
| 801-900     | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 419       | 81.2%   |
| 16/10   | 67        | 12.98%  |
| Unknown | 9         | 1.74%   |
| 3/2     | 8         | 1.55%   |
| 21/9    | 5         | 0.97%   |
| 4/3     | 3         | 0.58%   |
| 5/4     | 2         | 0.39%   |
| 6/5     | 1         | 0.19%   |
| 3.40    | 1         | 0.19%   |
| 0.67    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 213       | 36.72%  |
| 81-90          | 144       | 24.83%  |
| 121-130        | 35        | 6.03%   |
| 71-80          | 33        | 5.69%   |
| 201-250        | 28        | 4.83%   |
| 301-350        | 25        | 4.31%   |
| 61-70          | 23        | 3.97%   |
| 351-500        | 14        | 2.41%   |
| 251-300        | 11        | 1.9%    |
| Unknown        | 11        | 1.9%    |
| More than 1000 | 10        | 1.72%   |
| 131-140        | 10        | 1.72%   |
| 51-60          | 6         | 1.03%   |
| 141-150        | 4         | 0.69%   |
| 41-50          | 3         | 0.52%   |
| 111-120        | 3         | 0.52%   |
| 1-40           | 2         | 0.34%   |
| 151-200        | 2         | 0.34%   |
| 91-100         | 2         | 0.34%   |
| 501-1000       | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 268       | 47.1%   |
| 101-120       | 137       | 24.08%  |
| 51-100        | 72        | 12.65%  |
| 161-240       | 47        | 8.26%   |
| More than 240 | 29        | 5.1%    |
| Unknown       | 11        | 1.93%   |
| 1-50          | 5         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 414       | 80.08%  |
| 2     | 78        | 15.09%  |
| 3     | 14        | 2.71%   |
| 0     | 9         | 1.74%   |
| 4     | 2         | 0.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 319       | 40.85%  |
| Realtek Semiconductor             | 213       | 27.27%  |
| Qualcomm Atheros                  | 89        | 11.4%   |
| Broadcom                          | 44        | 5.63%   |
| Lenovo                            | 15        | 1.92%   |
| MediaTek                          | 13        | 1.66%   |
| Sierra Wireless                   | 12        | 1.54%   |
| Broadcom Limited                  | 11        | 1.41%   |
| Ericsson Business Mobile Networks | 10        | 1.28%   |
| Ralink                            | 7         | 0.9%    |
| Nvidia                            | 6         | 0.77%   |
| Marvell Technology Group          | 5         | 0.64%   |
| DisplayLink                       | 4         | 0.51%   |
| Dell                              | 4         | 0.51%   |
| Ralink Technology                 | 3         | 0.38%   |
| Qualcomm                          | 3         | 0.38%   |
| ASIX Electronics                  | 3         | 0.38%   |
| Xiaomi                            | 2         | 0.26%   |
| TP-Link                           | 2         | 0.26%   |
| Samsung Electronics               | 2         | 0.26%   |
| NetGear                           | 2         | 0.26%   |
| ZyXEL Communications              | 1         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.13%   |
| Philips (or NXP)                  | 1         | 0.13%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.13%   |
| Linksys                           | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| Huawei Technologies               | 1         | 0.13%   |
| Hewlett-Packard                   | 1         | 0.13%   |
| Google                            | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| D-Link System                     | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139       | 13.93%  |
| Intel Wireless 8265 / 8275                                        | 36        | 3.61%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 3.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34        | 3.41%   |
| Intel Wi-Fi 6 AX200                                               | 33        | 3.31%   |
| Intel Wireless 7260                                               | 32        | 3.21%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 28        | 2.81%   |
| Intel Wireless 8260                                               | 21        | 2.1%    |
| Intel Wireless 7265                                               | 20        | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 1.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 1.4%    |
| Intel Ethernet Connection I218-LM                                 | 14        | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 12        | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 1.1%    |
| Intel Centrino Ultimate-N 6300                                    | 11        | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 1%      |
| Intel Wi-Fi 6 AX201                                               | 10        | 1%      |
| Intel Ethernet Connection I219-LM                                 | 10        | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 10        | 1%      |
| Intel 82577LM Gigabit Network Connection                          | 10        | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 10        | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 9         | 0.9%    |
| Intel Centrino Wireless-N 2230                                    | 9         | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 0.8%    |
| Intel Ethernet Connection I219-V                                  | 8         | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.7%    |
| Sierra Wireless EM7455                                            | 6         | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 0.6%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 6         | 0.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 0.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.6%    |
| Sierra Wireless EM7345 4G LTE                                     | 5         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 311       | 59.35%  |
| Qualcomm Atheros      | 71        | 13.55%  |
| Realtek Semiconductor | 54        | 10.31%  |
| Broadcom              | 32        | 6.11%   |
| MediaTek              | 13        | 2.48%   |
| Sierra Wireless       | 12        | 2.29%   |
| Ralink                | 7         | 1.34%   |
| Broadcom Limited      | 7         | 1.34%   |
| Ralink Technology     | 3         | 0.57%   |
| Dell                  | 3         | 0.57%   |
| TP-Link               | 2         | 0.38%   |
| Qualcomm              | 2         | 0.38%   |
| NetGear               | 2         | 0.38%   |
| ZyXEL Communications  | 1         | 0.19%   |
| Philips (or NXP)      | 1         | 0.19%   |
| Fibocom               | 1         | 0.19%   |
| D-Link System         | 1         | 0.19%   |
| ASUSTek Computer      | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 36        | 6.87%   |
| Intel Wi-Fi 6 AX200                                                     | 33        | 6.3%    |
| Intel Wireless 7260                                                     | 32        | 6.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 28        | 5.34%   |
| Intel Wireless 8260                                                     | 21        | 4.01%   |
| Intel Wireless 7265                                                     | 20        | 3.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 19        | 3.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 2.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 2.1%    |
| Intel Centrino Ultimate-N 6300                                          | 11        | 2.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 10        | 1.91%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.72%   |
| Intel Centrino Wireless-N 2230                                          | 9         | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 1.53%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 7         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.34%   |
| Sierra Wireless EM7455                                                  | 6         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.15%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.15%   |
| Sierra Wireless EM7345 4G LTE                                           | 5         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.95%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.95%   |
| Intel Wireless 3165                                                     | 5         | 0.95%   |
| Intel Wireless 3160                                                     | 5         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.95%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 0.95%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 196       | 43.08%  |
| Intel                            | 167       | 36.7%   |
| Qualcomm Atheros                 | 27        | 5.93%   |
| Broadcom                         | 19        | 4.18%   |
| Lenovo                           | 15        | 3.3%    |
| Nvidia                           | 6         | 1.32%   |
| Marvell Technology Group         | 5         | 1.1%    |
| DisplayLink                      | 4         | 0.88%   |
| Broadcom Limited                 | 4         | 0.88%   |
| ASIX Electronics                 | 3         | 0.66%   |
| Xiaomi                           | 2         | 0.44%   |
| Samsung Electronics              | 2         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Qualcomm                         | 1         | 0.22%   |
| Linksys                          | 1         | 0.22%   |
| ICS Advent                       | 1         | 0.22%   |
| Google                           | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 139       | 30.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 34        | 7.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 34        | 7.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 4.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 3.92%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 3.05%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 2.18%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 2.18%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 2.18%   |
| Intel Ethernet Connection I219-V                                  | 8         | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 1.09%   |
| Intel Ethernet Connection (7) I219-V                              | 5         | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.09%   |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.87%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 0.87%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 4         | 0.87%   |
| Lenovo ThinkPad Lan                                               | 4         | 0.87%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.87%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.87%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.87%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 4         | 0.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.65%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.65%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.44%   |
| Realtek PCIe GbE Family Controller                                | 2         | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 496       | 52.82%  |
| Ethernet | 428       | 45.58%  |
| Modem    | 14        | 1.49%   |
| Unknown  | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 421       | 77.96%  |
| Ethernet | 119       | 22.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 393       | 77.98%  |
| 1     | 101       | 20.04%  |
| 3     | 6         | 1.19%   |
| 0     | 4         | 0.79%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 481       | 95.44%  |
| Yes  | 23        | 4.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 233       | 54.57%  |
| Broadcom                        | 43        | 10.07%  |
| Realtek Semiconductor           | 32        | 7.49%   |
| Qualcomm Atheros Communications | 23        | 5.39%   |
| Lite-On Technology              | 18        | 4.22%   |
| IMC Networks                    | 17        | 3.98%   |
| Foxconn / Hon Hai               | 16        | 3.75%   |
| Apple                           | 14        | 3.28%   |
| Hewlett-Packard                 | 9         | 2.11%   |
| Cambridge Silicon Radio         | 4         | 0.94%   |
| Dell                            | 3         | 0.7%    |
| Realtek                         | 2         | 0.47%   |
| Ralink Technology               | 2         | 0.47%   |
| Ralink                          | 2         | 0.47%   |
| ASUSTek Computer                | 2         | 0.47%   |
| USI                             | 1         | 0.23%   |
| Toshiba                         | 1         | 0.23%   |
| Taiyo Yuden                     | 1         | 0.23%   |
| MediaTek                        | 1         | 0.23%   |
| Foxconn International           | 1         | 0.23%   |
| D-Link System                   | 1         | 0.23%   |
| Chicony Electronics             | 1         | 0.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 122       | 28.57%  |
| Intel AX200 Bluetooth                               | 32        | 7.49%   |
| Intel AX201 Bluetooth                               | 28        | 6.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 5.39%   |
| Broadcom BCM2045B (BDC-2.1)                         | 20        | 4.68%   |
| Realtek Bluetooth Radio                             | 18        | 4.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 2.81%   |
| Apple Bluetooth Host Controller                     | 10        | 2.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 2.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 1.87%   |
| IMC Networks Wireless_Device                        | 8         | 1.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.87%   |
| Intel AX210 Bluetooth                               | 7         | 1.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 1.41%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.41%   |
| Lite-On Bluetooth Device                            | 4         | 0.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 0.94%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 0.94%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 3         | 0.7%    |
| Realtek RTL8723B Bluetooth                          | 3         | 0.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.7%    |
| Dell DW375 Bluetooth Module                         | 3         | 0.7%    |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.7%    |
| Realtek RTL8821A Bluetooth                          | 2         | 0.47%   |
| Realtek Bluetooth Radio                             | 2         | 0.47%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.47%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.47%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.47%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.47%   |
| USI Bluetooth Device                                | 1         | 0.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 395       | 62.11%  |
| AMD                              | 99        | 15.57%  |
| Nvidia                           | 90        | 14.15%  |
| Lenovo                           | 13        | 2.04%   |
| GN Netcom                        | 7         | 1.1%    |
| Hewlett-Packard                  | 4         | 0.63%   |
| Plantronics                      | 3         | 0.47%   |
| Logitech                         | 3         | 0.47%   |
| Realtek Semiconductor            | 2         | 0.31%   |
| Razer USA                        | 2         | 0.31%   |
| Kingston Technology              | 2         | 0.31%   |
| XMOS                             | 1         | 0.16%   |
| VIA Technologies                 | 1         | 0.16%   |
| Trust                            | 1         | 0.16%   |
| Texas Instruments                | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Sennheiser Communications        | 1         | 0.16%   |
| Samson Technologies              | 1         | 0.16%   |
| RODE Microphones                 | 1         | 0.16%   |
| OPPO Electronics                 | 1         | 0.16%   |
| NAD Electronics                  | 1         | 0.16%   |
| DSEA A/S                         | 1         | 0.16%   |
| Creative Technology              | 1         | 0.16%   |
| C-Media Electronics              | 1         | 0.16%   |
| Blue Microphones                 | 1         | 0.16%   |
| Antelope Audio                   | 1         | 0.16%   |
| Afatech                          | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 85        | 10.87%  |
| AMD Family 17h/19h HD Audio Controller                                     | 60        | 7.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 38        | 4.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37        | 4.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 32        | 4.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 30        | 3.84%   |
| Intel 8 Series HD Audio Controller                                         | 30        | 3.84%   |
| Intel Cannon Lake PCH cAVS                                                 | 28        | 3.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24        | 3.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 2.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 20        | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18        | 2.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 2.05%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 1.92%   |
| AMD FCH Azalia Controller                                                  | 14        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 13        | 1.66%   |
| Intel CM238 HD Audio Controller                                            | 11        | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 1.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 10        | 1.28%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 1.28%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.02%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.02%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8         | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 7         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 0.9%    |
| Intel Comet Lake PCH cAVS                                                  | 7         | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 0.77%   |
| Nvidia GT216 HDMI Audio Controller                                         | 5         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.64%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 0.64%   |
| Nvidia TU104 HD Audio Controller                                           | 4         | 0.51%   |
| Nvidia High Definition Audio Controller                                    | 4         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 90        | 32.03%  |
| SK hynix            | 66        | 23.49%  |
| Micron Technology   | 39        | 13.88%  |
| Kingston            | 31        | 11.03%  |
| Unknown             | 16        | 5.69%   |
| Crucial             | 11        | 3.91%   |
| Elpida              | 6         | 2.14%   |
| Ramaxel Technology  | 3         | 1.07%   |
| Nanya Technology    | 3         | 1.07%   |
| Corsair             | 3         | 1.07%   |
| A-DATA Technology   | 3         | 1.07%   |
| G.Skill             | 2         | 0.71%   |
| Transcend           | 1         | 0.36%   |
| SHARETRONIC         | 1         | 0.36%   |
| Neo Forza           | 1         | 0.36%   |
| ff                  | 1         | 0.36%   |
| fef5                | 1         | 0.36%   |
| Avant               | 1         | 0.36%   |
| Apacer              | 1         | 0.36%   |
| 4ea5                | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 2.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 2.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.68%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 1.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.35%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 1.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 1.35%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 1.01%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 3         | 1.01%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 1.01%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.01%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.01%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.01%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.01%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.67%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.67%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.67%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.67%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.67%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.67%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.67%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.67%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.67%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.67%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.67%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.67%   |
| Samsung RAM M471A2K43BB1-CPB 16384MB SODIMM DDR4 2133MT/s        | 2         | 0.67%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.67%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.67%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.67%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 114       | 47.7%   |
| DDR3    | 78        | 32.64%  |
| LPDDR3  | 18        | 7.53%   |
| LPDDR4  | 12        | 5.02%   |
| DDR2    | 9         | 3.77%   |
| DDR5    | 2         | 0.84%   |
| Unknown | 2         | 0.84%   |
| SDRAM   | 1         | 0.42%   |
| LPDDR5  | 1         | 0.42%   |
| DRAM    | 1         | 0.42%   |
| DDR     | 1         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 208       | 86.31%  |
| Row Of Chips | 24        | 9.96%   |
| Chip         | 4         | 1.66%   |
| Unknown      | 4         | 1.66%   |
| DIMM         | 1         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 116       | 45.31%  |
| 4096  | 61        | 23.83%  |
| 16384 | 42        | 16.41%  |
| 2048  | 23        | 8.98%   |
| 32768 | 9         | 3.52%   |
| 1024  | 3         | 1.17%   |
| 512   | 2         | 0.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 60        | 23.62%  |
| 2667    | 53        | 20.87%  |
| 3200    | 42        | 16.54%  |
| 2133    | 23        | 9.06%   |
| 2400    | 14        | 5.51%   |
| 1334    | 11        | 4.33%   |
| 1867    | 8         | 3.15%   |
| 1333    | 8         | 3.15%   |
| 667     | 7         | 2.76%   |
| 4267    | 5         | 1.97%   |
| 1067    | 5         | 1.97%   |
| 4266    | 4         | 1.57%   |
| Unknown | 4         | 1.57%   |
| 4800    | 2         | 0.79%   |
| 3266    | 2         | 0.79%   |
| 2933    | 2         | 0.79%   |
| 800     | 2         | 0.79%   |
| 8400    | 1         | 0.39%   |
| 4199    | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 40%     |
| Canon              | 2         | 40%     |
| Brother Industries | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP Officejet Pro 6230    | 1         | 20%     |
| HP DeskJet 3700 series   | 1         | 20%     |
| Canon PIXMA MX370 Series | 1         | 20%     |
| Canon PIXMA MP280        | 1         | 20%     |
| Brother HL-1210W series  | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 136       | 30.43%  |
| IMC Networks                           | 46        | 10.29%  |
| Bison Electronics                      | 38        | 8.5%    |
| Realtek Semiconductor                  | 32        | 7.16%   |
| Acer                                   | 23        | 5.15%   |
| Quanta                                 | 19        | 4.25%   |
| Microdia                               | 19        | 4.25%   |
| Lite-On Technology                     | 17        | 3.8%    |
| Suyin                                  | 16        | 3.58%   |
| Sunplus Innovation Technology          | 16        | 3.58%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 3.36%   |
| Syntek                                 | 14        | 3.13%   |
| Apple                                  | 12        | 2.68%   |
| Logitech                               | 11        | 2.46%   |
| Lenovo                                 | 7         | 1.57%   |
| Luxvisions Innotech Limited            | 6         | 1.34%   |
| Silicon Motion                         | 5         | 1.12%   |
| Samsung Electronics                    | 3         | 0.67%   |
| Primax Electronics                     | 3         | 0.67%   |
| Alcor Micro                            | 2         | 0.45%   |
| Z-Star Microelectronics                | 1         | 0.22%   |
| Sonix Technology                       | 1         | 0.22%   |
| Ricoh                                  | 1         | 0.22%   |
| MacroSilicon                           | 1         | 0.22%   |
| Genesys Logic                          | 1         | 0.22%   |
| GEMBIRD                                | 1         | 0.22%   |
| ALi                                    | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 43        | 9.58%   |
| IMC Networks Integrated Camera           | 18        | 4.01%   |
| Chicony HD WebCam                        | 15        | 3.34%   |
| Realtek Integrated_Webcam_HD             | 13        | 2.9%    |
| IMC Networks USB2.0 HD UVC WebCam        | 13        | 2.9%    |
| Lite-On Integrated Camera                | 10        | 2.23%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 10        | 2.23%   |
| Acer Integrated Camera                   | 10        | 2.23%   |
| Microdia Integrated_Webcam_HD            | 9         | 2%      |
| Bison SunplusIT Integrated Camera        | 8         | 1.78%   |
| Syntek Lenovo EasyCamera                 | 7         | 1.56%   |
| Chicony HP HD Camera                     | 6         | 1.34%   |
| Apple Built-in iSight                    | 6         | 1.34%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 1.11%   |
| Luxvisions Innotech Limited HP HD Camera | 5         | 1.11%   |
| Chicony Integrated Camera (1280x720@30)  | 5         | 1.11%   |
| Bison ThinkPad P50 Integrated Camera     | 5         | 1.11%   |
| Acer Lenovo EasyCamera                   | 5         | 1.11%   |
| Syntek Integrated Camera                 | 4         | 0.89%   |
| Quanta USB2.0 HD UVC WebCam              | 4         | 0.89%   |
| Quanta HP Webcam                         | 4         | 0.89%   |
| Lenovo Integrated Webcam                 | 4         | 0.89%   |
| Chicony USB 2.0 Camera                   | 4         | 0.89%   |
| Chicony Integrated Camera [ThinkPad]     | 4         | 0.89%   |
| Chicony HP Truevision HD                 | 4         | 0.89%   |
| Bison ThinkPad Integrated Camera         | 4         | 0.89%   |
| Bison SunplusIT INC. Integrated Camera   | 4         | 0.89%   |
| Bison Integrated Camera                  | 4         | 0.89%   |
| Acer HD Webcam                           | 4         | 0.89%   |
| Sunplus Laptop Integrated WebCam HD      | 3         | 0.67%   |
| Sunplus Integrated_Webcam_HD             | 3         | 0.67%   |
| Samsung Galaxy A5 (MTP)                  | 3         | 0.67%   |
| Realtek Integrated Webcam HD             | 3         | 0.67%   |
| Quanta HD Webcam                         | 3         | 0.67%   |
| Microdia Integrated Webcam               | 3         | 0.67%   |
| Lite-On HP HD Webcam                     | 3         | 0.67%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 3         | 0.67%   |
| IMC Networks USB Camera                  | 3         | 0.67%   |
| Chicony USB2.0 Camera                    | 3         | 0.67%   |
| Chicony Lenovo EasyCamera                | 3         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 54        | 37.76%  |
| Synaptics                  | 44        | 30.77%  |
| Upek                       | 17        | 11.89%  |
| Shenzhen Goodix Technology | 12        | 8.39%   |
| AuthenTec                  | 9         | 6.29%   |
| Elan Microelectronics      | 4         | 2.8%    |
| STMicroelectronics         | 2         | 1.4%    |
| LighTuning Technology      | 1         | 0.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 18.88%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 11.89%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 11.89%  |
| Validity Sensors Synaptics WBDI                                            | 9         | 6.29%   |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 6.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 3.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.5%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.8%    |
| AuthenTec AES2810                                                          | 4         | 2.8%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 2.8%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.1%    |
| Validity Sensors VFS491                                                    | 2         | 1.4%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.4%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.4%    |
| Synaptics UWP WBDI Device                                                  | 2         | 1.4%    |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.4%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.4%    |
| Elan ELAN:Fingerprint                                                      | 2         | 1.4%    |
| Elan ELAN:ARM-M4                                                           | 2         | 1.4%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.7%    |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.7%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.7%    |
| Synaptics UWP WBDI                                                         | 1         | 0.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.7%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.7%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 44        | 63.77%  |
| Broadcom    | 16        | 23.19%  |
| Upek        | 6         | 8.7%    |
| Lenovo      | 3         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 63.77%  |
| Broadcom 5880                                                                | 8         | 11.59%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 8.7%    |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 7.25%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.9%    |
| Broadcom 58200                                                               | 1         | 1.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 268       | 52.04%  |
| 1     | 182       | 35.34%  |
| 2     | 53        | 10.29%  |
| 3     | 7         | 1.36%   |
| 4     | 3         | 0.58%   |
| 10    | 1         | 0.19%   |
| 6     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 141       | 43.65%  |
| Chipcard                 | 64        | 19.81%  |
| Graphics card            | 44        | 13.62%  |
| Net/wireless             | 18        | 5.57%   |
| Multimedia controller    | 18        | 5.57%   |
| Card reader              | 10        | 3.1%    |
| Camera                   | 7         | 2.17%   |
| Communication controller | 5         | 1.55%   |
| Bluetooth                | 5         | 1.55%   |
| Storage                  | 4         | 1.24%   |
| Net/ethernet             | 4         | 1.24%   |
| Sound                    | 2         | 0.62%   |
| Modem                    | 1         | 0.31%   |


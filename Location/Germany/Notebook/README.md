Linux in Germany - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

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

Total: 15564

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 15-3568              | [b422d7c8cc](https://linux-hardware.org/?probe=b422d7c8cc) | Aug 12, 2023 |
| Dell          | XPS 15 9560                 | [756901f27f](https://linux-hardware.org/?probe=756901f27f) | Aug 12, 2023 |
| Valve         | Jupiter                     | [61e105aa9d](https://linux-hardware.org/?probe=61e105aa9d) | Aug 12, 2023 |
| Dell          | Latitude E7270              | [63fd1b0d6b](https://linux-hardware.org/?probe=63fd1b0d6b) | Aug 12, 2023 |
| Acer          | Extensa 215-55              | [aea9ada5e8](https://linux-hardware.org/?probe=aea9ada5e8) | Aug 11, 2023 |
| Toshiba       | Satellite T110              | [ecb4e047b3](https://linux-hardware.org/?probe=ecb4e047b3) | Aug 11, 2023 |
| Acer          | Aspire E5-721               | [f4abfc94d4](https://linux-hardware.org/?probe=f4abfc94d4) | Aug 11, 2023 |
| Acer          | Extensa 215-55              | [036866525c](https://linux-hardware.org/?probe=036866525c) | Aug 11, 2023 |
| Toshiba       | Satellite T110              | [8180105119](https://linux-hardware.org/?probe=8180105119) | Aug 11, 2023 |
| Medion        | P651x series                | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| HP            | Laptop 17-cp1xxx            | [ac523f4e3b](https://linux-hardware.org/?probe=ac523f4e3b) | Aug 11, 2023 |
| HP            | EliteBook 8470p             | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| Fujitsu       | LIFEBOOK S762               | [1ced8ae4d0](https://linux-hardware.org/?probe=1ced8ae4d0) | Aug 11, 2023 |
| Fujitsu       | LIFEBOOK S762               | [cb0b5cbd5d](https://linux-hardware.org/?probe=cb0b5cbd5d) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY            | [eacd0cc54d](https://linux-hardware.org/?probe=eacd0cc54d) | Aug 11, 2023 |
| Acer          | Aspire E1-731               | [b75a766ee9](https://linux-hardware.org/?probe=b75a766ee9) | Aug 10, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [eee160a070](https://linux-hardware.org/?probe=eee160a070) | Aug 10, 2023 |
| HP            | ProBook 430 G2              | [426901227d](https://linux-hardware.org/?probe=426901227d) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | [0b8fc947af](https://linux-hardware.org/?probe=0b8fc947af) | Aug 10, 2023 |
| Fujitsu       | LIFEBOOK A530               | [05e64e3a0a](https://linux-hardware.org/?probe=05e64e3a0a) | Aug 10, 2023 |
| Lenovo        | ThinkPad P51 20HH0015IX     | [77c11473b2](https://linux-hardware.org/?probe=77c11473b2) | Aug 10, 2023 |
| Acer          | Aspire E5-721               | [6743c7ca9d](https://linux-hardware.org/?probe=6743c7ca9d) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | [69123aa283](https://linux-hardware.org/?probe=69123aa283) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | [9c28979b9d](https://linux-hardware.org/?probe=9c28979b9d) | Aug 10, 2023 |
| HUAWEI        | BOM-WXX9                    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | [3986ff4298](https://linux-hardware.org/?probe=3986ff4298) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [2f7f77225a](https://linux-hardware.org/?probe=2f7f77225a) | Aug 09, 2023 |
| HP            | EliteBook 840 G2            | [90291816a0](https://linux-hardware.org/?probe=90291816a0) | Aug 09, 2023 |
| HP            | OMEN by Laptop              | [fdbe025351](https://linux-hardware.org/?probe=fdbe025351) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Acer          | Aspire A317-33              | [6dd8126a05](https://linux-hardware.org/?probe=6dd8126a05) | Aug 09, 2023 |
| HP            | Laptop 15s-eq3xxx           | [284cfb0f6d](https://linux-hardware.org/?probe=284cfb0f6d) | Aug 08, 2023 |
| Lenovo        | ThinkPad T440 20B7S4NV07    | [af7992a11e](https://linux-hardware.org/?probe=af7992a11e) | Aug 08, 2023 |
| HP            | OMEN by Laptop              | [b15a5e767a](https://linux-hardware.org/?probe=b15a5e767a) | Aug 08, 2023 |
| Acer          | Aspire E5-721               | [82a8a2346a](https://linux-hardware.org/?probe=82a8a2346a) | Aug 08, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [4f4c3a2b96](https://linux-hardware.org/?probe=4f4c3a2b96) | Aug 08, 2023 |
| Acer          | Aspire 8930                 | [1a39769fb2](https://linux-hardware.org/?probe=1a39769fb2) | Aug 08, 2023 |
| HP            | 255 G5                      | [b38a912e23](https://linux-hardware.org/?probe=b38a912e23) | Aug 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5aa44fc15a](https://linux-hardware.org/?probe=5aa44fc15a) | Aug 08, 2023 |
| Acer          | Aspire 4820TG               | [49a63e5cc4](https://linux-hardware.org/?probe=49a63e5cc4) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Toshiba       | Satellite C50-A510          | [335af4e25a](https://linux-hardware.org/?probe=335af4e25a) | Aug 08, 2023 |
| HP            | Pavilion 17                 | [4833cfdbd8](https://linux-hardware.org/?probe=4833cfdbd8) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Dell          | Inspiron 3505               | [e07624ae41](https://linux-hardware.org/?probe=e07624ae41) | Aug 07, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| Insyde        | BayTrail                    | [df18553ec6](https://linux-hardware.org/?probe=df18553ec6) | Aug 07, 2023 |
| HP            | Elite x2 1012 G1            | [fea0f58ed5](https://linux-hardware.org/?probe=fea0f58ed5) | Aug 07, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | [22624fbda5](https://linux-hardware.org/?probe=22624fbda5) | Aug 07, 2023 |
| Acer          | Aspire V3-771               | [ebdbffb7da](https://linux-hardware.org/?probe=ebdbffb7da) | Aug 07, 2023 |
| HP            | EliteBook 8470p             | [62d3a8d08d](https://linux-hardware.org/?probe=62d3a8d08d) | Aug 07, 2023 |
| ASUSTek       | X540SA                      | [db952b584b](https://linux-hardware.org/?probe=db952b584b) | Aug 07, 2023 |
| ASUSTek       | N552VX                      | [1c616233ca](https://linux-hardware.org/?probe=1c616233ca) | Aug 07, 2023 |
| ASUSTek       | N76VM                       | [083980d0fb](https://linux-hardware.org/?probe=083980d0fb) | Aug 07, 2023 |
| HP            | Laptop 17-ak0xx             | [67749cdc51](https://linux-hardware.org/?probe=67749cdc51) | Aug 07, 2023 |
| Fujitsu       | LIFEBOOK A359               | [60a09f6ca3](https://linux-hardware.org/?probe=60a09f6ca3) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Timi          | TM1607                      | [c545853106](https://linux-hardware.org/?probe=c545853106) | Aug 07, 2023 |
| Clevo         | W150HRM                     | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| HP            | EliteBook 8570p             | [99635bf61d](https://linux-hardware.org/?probe=99635bf61d) | Aug 06, 2023 |
| HP            | EliteBook 8540p             | [4709894444](https://linux-hardware.org/?probe=4709894444) | Aug 06, 2023 |
| Dell          | XPS 15 7590                 | [6a53759849](https://linux-hardware.org/?probe=6a53759849) | Aug 06, 2023 |
| Packard Be... | EasyNote LS11HR             | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| Dell          | Latitude E5520              | [132e7834f7](https://linux-hardware.org/?probe=132e7834f7) | Aug 06, 2023 |
| ASUSTek       | N76VM                       | [80d45ff242](https://linux-hardware.org/?probe=80d45ff242) | Aug 06, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [27d1d39b58](https://linux-hardware.org/?probe=27d1d39b58) | Aug 06, 2023 |
| ASUSTek       | K54L                        | [3ce0c0b7b2](https://linux-hardware.org/?probe=3ce0c0b7b2) | Aug 06, 2023 |
| ASUSTek       | K54L                        | [b28f27325f](https://linux-hardware.org/?probe=b28f27325f) | Aug 06, 2023 |
| HP            | Laptop 15-db0xxx            | [51442067d5](https://linux-hardware.org/?probe=51442067d5) | Aug 06, 2023 |
| Dell          | Latitude E5570              | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| Chuwi         | GemiBook Pro                | [2726702c6a](https://linux-hardware.org/?probe=2726702c6a) | Aug 06, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | [89119ae1fc](https://linux-hardware.org/?probe=89119ae1fc) | Aug 06, 2023 |
| Dell          | Inspiron MM061              | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| Lenovo        | ThinkPad X201 Tablet 298... | [7132bbeb85](https://linux-hardware.org/?probe=7132bbeb85) | Aug 06, 2023 |
| Valve         | Jupiter                     | [efbeafcf8f](https://linux-hardware.org/?probe=efbeafcf8f) | Aug 05, 2023 |
| Valve         | Jupiter                     | [eadfa77bef](https://linux-hardware.org/?probe=eadfa77bef) | Aug 05, 2023 |
| ASUSTek       | K73SV                       | [c908f2bfdd](https://linux-hardware.org/?probe=c908f2bfdd) | Aug 05, 2023 |
| ASUSTek       | S301LA                      | [cc5477fc6b](https://linux-hardware.org/?probe=cc5477fc6b) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| Dell          | Latitude 7490               | [73efa45f4f](https://linux-hardware.org/?probe=73efa45f4f) | Aug 05, 2023 |
| Dell          | Latitude 7490               | [ce0e015b6e](https://linux-hardware.org/?probe=ce0e015b6e) | Aug 05, 2023 |
| Shuttle       | DS47D                       | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| Apple         | MacBookPro5,5               | [ccbf514dc7](https://linux-hardware.org/?probe=ccbf514dc7) | Aug 04, 2023 |
| HP            | Laptop 15s-eq1xxx           | [e6e6cc7b2e](https://linux-hardware.org/?probe=e6e6cc7b2e) | Aug 04, 2023 |
| Acer          | Swift SF514-52T             | [6b6773eeef](https://linux-hardware.org/?probe=6b6773eeef) | Aug 04, 2023 |
| Dell          | Latitude E6330              | [c4b0f9dfd2](https://linux-hardware.org/?probe=c4b0f9dfd2) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7bc7a7e01c](https://linux-hardware.org/?probe=7bc7a7e01c) | Aug 04, 2023 |
| Dell          | Latitude E6330              | [3c74e4818b](https://linux-hardware.org/?probe=3c74e4818b) | Aug 04, 2023 |
| Lenovo        | ThinkPad T420 4236MBG       | [aaaa17358f](https://linux-hardware.org/?probe=aaaa17358f) | Aug 04, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [5e28b5b07a](https://linux-hardware.org/?probe=5e28b5b07a) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b8fa3962ed](https://linux-hardware.org/?probe=b8fa3962ed) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5799f1a89c](https://linux-hardware.org/?probe=5799f1a89c) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [058011da0f](https://linux-hardware.org/?probe=058011da0f) | Aug 04, 2023 |
| Acer          | Swift SF114-34              | [2af2b0aecb](https://linux-hardware.org/?probe=2af2b0aecb) | Aug 04, 2023 |
| ASUSTek       | N501JW                      | [e7d254dbe5](https://linux-hardware.org/?probe=e7d254dbe5) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Acer          | Extensa 5630                | [8b3c2a89a1](https://linux-hardware.org/?probe=8b3c2a89a1) | Aug 04, 2023 |
| Acer          | Extensa 5630                | [ba6669a5e7](https://linux-hardware.org/?probe=ba6669a5e7) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Medion        | Erazer X7841 MD99556        | [c9f4247fc1](https://linux-hardware.org/?probe=c9f4247fc1) | Aug 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3ES0A    | [1038e99486](https://linux-hardware.org/?probe=1038e99486) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| Acer          | Aspire V5-572P              | [1d27d25f8d](https://linux-hardware.org/?probe=1d27d25f8d) | Aug 03, 2023 |
| HP            | Notebook                    | [499fc30d3a](https://linux-hardware.org/?probe=499fc30d3a) | Aug 03, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [620397fdc9](https://linux-hardware.org/?probe=620397fdc9) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [882d963e19](https://linux-hardware.org/?probe=882d963e19) | Aug 03, 2023 |
| Lenovo        | G500 20236                  | [88a569c8ee](https://linux-hardware.org/?probe=88a569c8ee) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [38d0bcf5d1](https://linux-hardware.org/?probe=38d0bcf5d1) | Aug 03, 2023 |
| Acer          | Aspire VN7-793G             | [c7e996a3c2](https://linux-hardware.org/?probe=c7e996a3c2) | Aug 03, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [a3401e5a4b](https://linux-hardware.org/?probe=a3401e5a4b) | Aug 03, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | [6e8234ed89](https://linux-hardware.org/?probe=6e8234ed89) | Aug 03, 2023 |
| Dell          | Latitude 5420               | [491cea9604](https://linux-hardware.org/?probe=491cea9604) | Aug 03, 2023 |
| Packard Be... | EasyNote LS11HR             | [6e79cf1bf0](https://linux-hardware.org/?probe=6e79cf1bf0) | Aug 03, 2023 |
| Dell          | Latitude E6320              | [9b42be4945](https://linux-hardware.org/?probe=9b42be4945) | Aug 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [433a85501a](https://linux-hardware.org/?probe=433a85501a) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [101e2e7e7e](https://linux-hardware.org/?probe=101e2e7e7e) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [16cafd9d32](https://linux-hardware.org/?probe=16cafd9d32) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [cf7cad0e02](https://linux-hardware.org/?probe=cf7cad0e02) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | [6ffb3ac7e7](https://linux-hardware.org/?probe=6ffb3ac7e7) | Aug 02, 2023 |
| Medion        | X681X                       | [8209a37737](https://linux-hardware.org/?probe=8209a37737) | Aug 02, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | [0f5b976e39](https://linux-hardware.org/?probe=0f5b976e39) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Precision M4500             | [b425204301](https://linux-hardware.org/?probe=b425204301) | Aug 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [502969280a](https://linux-hardware.org/?probe=502969280a) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [57bac048da](https://linux-hardware.org/?probe=57bac048da) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | [479ca68bae](https://linux-hardware.org/?probe=479ca68bae) | Aug 02, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [8fb651def8](https://linux-hardware.org/?probe=8fb651def8) | Aug 02, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| Acer          | Aspire ES1-521              | [127d7abd32](https://linux-hardware.org/?probe=127d7abd32) | Aug 01, 2023 |
| Acer          | Aspire A517-52              | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Dell          | Precision 7550              | [ab0d21bb4e](https://linux-hardware.org/?probe=ab0d21bb4e) | Aug 01, 2023 |
| Lenovo        | ThinkPad X250 20CM001PGE    | [9c5503cd84](https://linux-hardware.org/?probe=9c5503cd84) | Aug 01, 2023 |
| Acer          | Aspire ES1-311              | [6f59479d87](https://linux-hardware.org/?probe=6f59479d87) | Aug 01, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | [e6d6527380](https://linux-hardware.org/?probe=e6d6527380) | Aug 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [bc84705e8f](https://linux-hardware.org/?probe=bc84705e8f) | Aug 01, 2023 |
| Medion        | E5214                       | [98cb0db418](https://linux-hardware.org/?probe=98cb0db418) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Dell          | Latitude E6220              | [5b4b97df21](https://linux-hardware.org/?probe=5b4b97df21) | Aug 01, 2023 |
| Dell          | Latitude 7640               | [ddb87f6cdb](https://linux-hardware.org/?probe=ddb87f6cdb) | Jul 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| TUXEDO        | N7x0WU                      | [05c525a9a7](https://linux-hardware.org/?probe=05c525a9a7) | Jul 31, 2023 |
| HP            | 255 G8 Notebook PC          | [b42946849e](https://linux-hardware.org/?probe=b42946849e) | Jul 31, 2023 |
| HP            | Laptop 17-bs0xx             | [49dac3f2d9](https://linux-hardware.org/?probe=49dac3f2d9) | Jul 31, 2023 |
| Dell          | Precision 3571              | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| HP            | Pavilion 17                 | [38fe3ae501](https://linux-hardware.org/?probe=38fe3ae501) | Jul 31, 2023 |
| HP            | Laptop 17-bs0xx             | [aca7e14a0e](https://linux-hardware.org/?probe=aca7e14a0e) | Jul 31, 2023 |
| HP            | ProBook 4720s               | [f1e4220c67](https://linux-hardware.org/?probe=f1e4220c67) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| Medion        | Erazer X7841 MD99556        | [7b9d9dfa25](https://linux-hardware.org/?probe=7b9d9dfa25) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| HP            | Laptop 17-cp0xxx            | [e8b1218a57](https://linux-hardware.org/?probe=e8b1218a57) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS20D00     | [4ef8aa09c6](https://linux-hardware.org/?probe=4ef8aa09c6) | Jul 31, 2023 |
| Acer          | Aspire 5741G                | [3c56ffebcb](https://linux-hardware.org/?probe=3c56ffebcb) | Jul 30, 2023 |
| Apple         | MacBookPro5,5               | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [1fe8eab1c6](https://linux-hardware.org/?probe=1fe8eab1c6) | Jul 30, 2023 |
| Dell          | Latitude 5421               | [3872b1f799](https://linux-hardware.org/?probe=3872b1f799) | Jul 30, 2023 |
| HP            | Pavilion 15                 | [7dcc58cdf2](https://linux-hardware.org/?probe=7dcc58cdf2) | Jul 30, 2023 |
| Medion        | E5214                       | [d1c634ee07](https://linux-hardware.org/?probe=d1c634ee07) | Jul 30, 2023 |
| Dell          | Latitude E6510              | [f8ebba29c6](https://linux-hardware.org/?probe=f8ebba29c6) | Jul 30, 2023 |
| Lenovo        | ThinkPad T440p 20AN009FG... | [f2cc6379cc](https://linux-hardware.org/?probe=f2cc6379cc) | Jul 30, 2023 |
| Apple         | MacBookPro9,1               | [3b030b25ac](https://linux-hardware.org/?probe=3b030b25ac) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| Dell          | Latitude E5520              | [09aa4e35c4](https://linux-hardware.org/?probe=09aa4e35c4) | Jul 30, 2023 |
| Acer          | Aspire A315-42              | [3d1aebd069](https://linux-hardware.org/?probe=3d1aebd069) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| Dell          | Inspiron 16 7610            | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Acer          | Aspire A517-52              | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| Dell          | Latitude 7380               | [ec068abcb3](https://linux-hardware.org/?probe=ec068abcb3) | Jul 29, 2023 |
| Panasonic     | CF-20-1                     | [0b59968d03](https://linux-hardware.org/?probe=0b59968d03) | Jul 29, 2023 |
| Dell          | Latitude 7380               | [a5ea12f136](https://linux-hardware.org/?probe=a5ea12f136) | Jul 29, 2023 |
| Dell          | Latitude E6230              | [462496c6db](https://linux-hardware.org/?probe=462496c6db) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [32ad81bc5d](https://linux-hardware.org/?probe=32ad81bc5d) | Jul 29, 2023 |
| Wortmann      | 1220624_1470150             | [b68bd8a80c](https://linux-hardware.org/?probe=b68bd8a80c) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | [02d2d041f8](https://linux-hardware.org/?probe=02d2d041f8) | Jul 29, 2023 |
| HP            | EliteBook 2540p             | [cb13e61bae](https://linux-hardware.org/?probe=cb13e61bae) | Jul 28, 2023 |
| HP            | EliteBook 820 G2            | [39b9a37ad6](https://linux-hardware.org/?probe=39b9a37ad6) | Jul 28, 2023 |
| Acer          | Aspire A515-52G             | [2ba77ece3b](https://linux-hardware.org/?probe=2ba77ece3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b9b1a625ee](https://linux-hardware.org/?probe=b9b1a625ee) | Jul 28, 2023 |
| HP            | EliteBook 2540p             | [cedff6ca6f](https://linux-hardware.org/?probe=cedff6ca6f) | Jul 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [8fee6296fe](https://linux-hardware.org/?probe=8fee6296fe) | Jul 28, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0180... | [cde4989301](https://linux-hardware.org/?probe=cde4989301) | Jul 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [1c3edafdf4](https://linux-hardware.org/?probe=1c3edafdf4) | Jul 28, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | [4439f26a90](https://linux-hardware.org/?probe=4439f26a90) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [a467ce5440](https://linux-hardware.org/?probe=a467ce5440) | Jul 28, 2023 |
| Acer          | Aspire V3-771               | [4abc91d2fb](https://linux-hardware.org/?probe=4abc91d2fb) | Jul 28, 2023 |
| Lenovo        | ThinkPad L570 20JRS06XGE    | [cae3db2f8d](https://linux-hardware.org/?probe=cae3db2f8d) | Jul 28, 2023 |
| Apple         | MacBookAir7,2               | [3e7b8ae52e](https://linux-hardware.org/?probe=3e7b8ae52e) | Jul 28, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [79acef5aba](https://linux-hardware.org/?probe=79acef5aba) | Jul 28, 2023 |
| TUXEDO        | Unknown                     | [9c46ee9f93](https://linux-hardware.org/?probe=9c46ee9f93) | Jul 28, 2023 |
| HP            | Laptop 17-cp1xxx            | [29a0a48515](https://linux-hardware.org/?probe=29a0a48515) | Jul 28, 2023 |
| Acer          | Aspire E5-573G              | [f07b71e1d6](https://linux-hardware.org/?probe=f07b71e1d6) | Jul 28, 2023 |
| HP            | Pavilion 17                 | [eb4d13c329](https://linux-hardware.org/?probe=eb4d13c329) | Jul 28, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [49b28d270b](https://linux-hardware.org/?probe=49b28d270b) | Jul 27, 2023 |
| Apple         | MacBookPro5,2               | [2c6617e2f9](https://linux-hardware.org/?probe=2c6617e2f9) | Jul 27, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [8424587178](https://linux-hardware.org/?probe=8424587178) | Jul 27, 2023 |
| Apple         | MacBookAir5,1               | [da2904da80](https://linux-hardware.org/?probe=da2904da80) | Jul 27, 2023 |
| Dell          | XPS 15 9570                 | [af7b522b57](https://linux-hardware.org/?probe=af7b522b57) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [dc632de3b5](https://linux-hardware.org/?probe=dc632de3b5) | Jul 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9970afb7db](https://linux-hardware.org/?probe=9970afb7db) | Jul 27, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e97688a8c1](https://linux-hardware.org/?probe=e97688a8c1) | Jul 27, 2023 |
| Fujitsu       | LIFEBOOK U748               | [23d71a87d0](https://linux-hardware.org/?probe=23d71a87d0) | Jul 26, 2023 |
| HP            | Laptop 17-cp0xxx            | [79ea58e0d1](https://linux-hardware.org/?probe=79ea58e0d1) | Jul 26, 2023 |
| Chuwi         | GemiBook Pro                | [d626a17105](https://linux-hardware.org/?probe=d626a17105) | Jul 26, 2023 |
| Chuwi         | GemiBook Pro                | [01f9930ae2](https://linux-hardware.org/?probe=01f9930ae2) | Jul 26, 2023 |
| Dell          | Latitude E5430 non-vPro     | [b5b201f80a](https://linux-hardware.org/?probe=b5b201f80a) | Jul 26, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [784b86f367](https://linux-hardware.org/?probe=784b86f367) | Jul 25, 2023 |
| HP            | ProBook 640 G2              | [ae244aab21](https://linux-hardware.org/?probe=ae244aab21) | Jul 25, 2023 |
| Apple         | MacBookPro5,5               | [9cf2abf318](https://linux-hardware.org/?probe=9cf2abf318) | Jul 25, 2023 |
| Acer          | Aspire A515-45              | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| MSI           | GL75 Leopard 10SFR          | [8b976f0d08](https://linux-hardware.org/?probe=8b976f0d08) | Jul 25, 2023 |
| Acer          | Aspire E5-774G              | [1568ba2843](https://linux-hardware.org/?probe=1568ba2843) | Jul 25, 2023 |
| ECT           | ONE GAMING Laptop Carry ... | [335aad489c](https://linux-hardware.org/?probe=335aad489c) | Jul 25, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [9acc2dda36](https://linux-hardware.org/?probe=9acc2dda36) | Jul 25, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [1cf27b8466](https://linux-hardware.org/?probe=1cf27b8466) | Jul 25, 2023 |
| Dell          | XPS 15 9520                 | [54377b2911](https://linux-hardware.org/?probe=54377b2911) | Jul 25, 2023 |
| Lenovo        | B590 62743QG                | [d8bd2493ec](https://linux-hardware.org/?probe=d8bd2493ec) | Jul 25, 2023 |
| MSI           | WF66 11UJ                   | [305e24e26d](https://linux-hardware.org/?probe=305e24e26d) | Jul 25, 2023 |
| ASUSTek       | X751SA                      | [27185d9ec1](https://linux-hardware.org/?probe=27185d9ec1) | Jul 25, 2023 |
| Apple         | MacBookPro5,1               | [b5771a9e3f](https://linux-hardware.org/?probe=b5771a9e3f) | Jul 25, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7910b0c067](https://linux-hardware.org/?probe=7910b0c067) | Jul 25, 2023 |
| HUAWEI        | HLYL-WXX9                   | [7da659326d](https://linux-hardware.org/?probe=7da659326d) | Jul 24, 2023 |
| Acer          | Aspire E1-571               | [24b5ed47e3](https://linux-hardware.org/?probe=24b5ed47e3) | Jul 24, 2023 |
| Dell          | Latitude E6230              | [6f832e0bb3](https://linux-hardware.org/?probe=6f832e0bb3) | Jul 24, 2023 |
| Lenovo        | ThinkPad X200 7458C23       | [3f09abaa12](https://linux-hardware.org/?probe=3f09abaa12) | Jul 24, 2023 |
| Medion        | E14303                      | [c6ef5b69b3](https://linux-hardware.org/?probe=c6ef5b69b3) | Jul 24, 2023 |
| HP            | EliteBook 840 G2            | [598e9ca129](https://linux-hardware.org/?probe=598e9ca129) | Jul 24, 2023 |
| Fujitsu       | CELSIUS H700                | [8a23e1d76a](https://linux-hardware.org/?probe=8a23e1d76a) | Jul 24, 2023 |
| Acer          | Aspire V5-572P              | [2033b22202](https://linux-hardware.org/?probe=2033b22202) | Jul 24, 2023 |
| Acer          | Aspire V5-572P              | [47b219049e](https://linux-hardware.org/?probe=47b219049e) | Jul 24, 2023 |
| Fujitsu       | LIFEBOOK A530               | [8c0fa80a0e](https://linux-hardware.org/?probe=8c0fa80a0e) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [f9bd193456](https://linux-hardware.org/?probe=f9bd193456) | Jul 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3bd5c9d59c](https://linux-hardware.org/?probe=3bd5c9d59c) | Jul 23, 2023 |
| ASUSTek       | H170M-PLUS                  | [f17fd3bbe1](https://linux-hardware.org/?probe=f17fd3bbe1) | Jul 23, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [4a5ded3dcc](https://linux-hardware.org/?probe=4a5ded3dcc) | Jul 23, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [4824895fac](https://linux-hardware.org/?probe=4824895fac) | Jul 23, 2023 |
| ASUSTek       | X555LAB                     | [0e40daefd2](https://linux-hardware.org/?probe=0e40daefd2) | Jul 23, 2023 |
| Dell          | Latitude E7270              | [9d14027d6c](https://linux-hardware.org/?probe=9d14027d6c) | Jul 23, 2023 |
| Acer          | Aspire V3-772               | [06eca9873d](https://linux-hardware.org/?probe=06eca9873d) | Jul 23, 2023 |
| HP            | G62                         | [003a68db8b](https://linux-hardware.org/?probe=003a68db8b) | Jul 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [c741f10f18](https://linux-hardware.org/?probe=c741f10f18) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | [1bf0a25c8e](https://linux-hardware.org/?probe=1bf0a25c8e) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | [f7fb9875de](https://linux-hardware.org/?probe=f7fb9875de) | Jul 22, 2023 |
| HP            | Laptop 17-by3xxx            | [b5fe1f6fca](https://linux-hardware.org/?probe=b5fe1f6fca) | Jul 22, 2023 |
| Acer          | Aspire V3-372               | [7223651dee](https://linux-hardware.org/?probe=7223651dee) | Jul 22, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [c95c0b0730](https://linux-hardware.org/?probe=c95c0b0730) | Jul 22, 2023 |
| Acer          | Aspire VN7-571G             | [9cb2aaa7da](https://linux-hardware.org/?probe=9cb2aaa7da) | Jul 22, 2023 |
| Medion        | E6224                       | [c33b8a1fb1](https://linux-hardware.org/?probe=c33b8a1fb1) | Jul 22, 2023 |
| Acer          | Aspire VN7-571G             | [d517bf7f3b](https://linux-hardware.org/?probe=d517bf7f3b) | Jul 21, 2023 |
| HP            | ProBook 470 G2              | [b7fc9c0c1a](https://linux-hardware.org/?probe=b7fc9c0c1a) | Jul 21, 2023 |
| Acer          | Aspire V5-551               | [8a13138f82](https://linux-hardware.org/?probe=8a13138f82) | Jul 21, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [2af4d18efd](https://linux-hardware.org/?probe=2af4d18efd) | Jul 21, 2023 |
| HP            | ZBook 15 G2                 | [1c164d4bc9](https://linux-hardware.org/?probe=1c164d4bc9) | Jul 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49b784f5e2](https://linux-hardware.org/?probe=49b784f5e2) | Jul 21, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | [65dfd39fb4](https://linux-hardware.org/?probe=65dfd39fb4) | Jul 21, 2023 |
| Lenovo        | IdeaPadFlex 14D 20333       | [f7fcf9f782](https://linux-hardware.org/?probe=f7fcf9f782) | Jul 21, 2023 |
| Toshiba       | TECRA A50-A                 | [e96ff00334](https://linux-hardware.org/?probe=e96ff00334) | Jul 21, 2023 |
| Apple         | MacBookPro11,4              | [cce59a7f72](https://linux-hardware.org/?probe=cce59a7f72) | Jul 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1400CDA... | [61837fa4da](https://linux-hardware.org/?probe=61837fa4da) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| Lenovo        | G50-80 80E5                 | [0f212dfabe](https://linux-hardware.org/?probe=0f212dfabe) | Jul 21, 2023 |
| Fujitsu       | LIFEBOOK E556               | [d02422eb33](https://linux-hardware.org/?probe=d02422eb33) | Jul 20, 2023 |
| Acer          | Aspire E5-573G              | [b9e9f5f7fa](https://linux-hardware.org/?probe=b9e9f5f7fa) | Jul 20, 2023 |
| ASUSTek       | GL702VM                     | [f2a5e69f00](https://linux-hardware.org/?probe=f2a5e69f00) | Jul 20, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [820630ba9e](https://linux-hardware.org/?probe=820630ba9e) | Jul 20, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [6bc352838a](https://linux-hardware.org/?probe=6bc352838a) | Jul 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9a2d353d76](https://linux-hardware.org/?probe=9a2d353d76) | Jul 20, 2023 |
| HP            | Elite x2 1012 G1            | [78f66f7c03](https://linux-hardware.org/?probe=78f66f7c03) | Jul 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [58882ecdfe](https://linux-hardware.org/?probe=58882ecdfe) | Jul 20, 2023 |
| ASUSTek       | N501VW                      | [08cd5a81b2](https://linux-hardware.org/?probe=08cd5a81b2) | Jul 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [fc26baabc9](https://linux-hardware.org/?probe=fc26baabc9) | Jul 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [524d69b498](https://linux-hardware.org/?probe=524d69b498) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [7733ed8a40](https://linux-hardware.org/?probe=7733ed8a40) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [4bba49b11c](https://linux-hardware.org/?probe=4bba49b11c) | Jul 19, 2023 |
| Fujitsu       | LIFEBOOK A512               | [adc2f71c13](https://linux-hardware.org/?probe=adc2f71c13) | Jul 19, 2023 |
| HP            | Compaq 6510b (KE135ET#AB... | [5f123a3842](https://linux-hardware.org/?probe=5f123a3842) | Jul 19, 2023 |
| Schenker      | XMG NEO (CML/E20)           | [9f99e57705](https://linux-hardware.org/?probe=9f99e57705) | Jul 19, 2023 |
| HP            | 255 G2                      | [eaf9befa3a](https://linux-hardware.org/?probe=eaf9befa3a) | Jul 19, 2023 |
| Lenovo        | ThinkPad X390 20Q1S0HE00    | [9f95f31702](https://linux-hardware.org/?probe=9f95f31702) | Jul 19, 2023 |
| Fujitsu       | LIFEBOOK A544               | [5643f29431](https://linux-hardware.org/?probe=5643f29431) | Jul 19, 2023 |
| Dell          | Latitude 5511               | [9dcb3c30b2](https://linux-hardware.org/?probe=9dcb3c30b2) | Jul 19, 2023 |
| Dell          | Latitude 7440               | [508d0e46e7](https://linux-hardware.org/?probe=508d0e46e7) | Jul 19, 2023 |
| Lenovo        | ThinkPad T410 2537AT1       | [7d94a6effc](https://linux-hardware.org/?probe=7d94a6effc) | Jul 19, 2023 |
| Valve         | Jupiter                     | [6ddba888cf](https://linux-hardware.org/?probe=6ddba888cf) | Jul 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [360ee7202f](https://linux-hardware.org/?probe=360ee7202f) | Jul 18, 2023 |
| Lenovo        | ThinkPad T520 42435UG       | [f789cd31fa](https://linux-hardware.org/?probe=f789cd31fa) | Jul 18, 2023 |
| Fujitsu       | LIFEBOOK A557               | [96f08b7598](https://linux-hardware.org/?probe=96f08b7598) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [96585144ab](https://linux-hardware.org/?probe=96585144ab) | Jul 18, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | [1b210ca778](https://linux-hardware.org/?probe=1b210ca778) | Jul 18, 2023 |
| Lenovo        | ThinkPad T420 4236C92       | [a7b56f640a](https://linux-hardware.org/?probe=a7b56f640a) | Jul 18, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [b5e1bfb09d](https://linux-hardware.org/?probe=b5e1bfb09d) | Jul 17, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [bc8992d98a](https://linux-hardware.org/?probe=bc8992d98a) | Jul 17, 2023 |
| Apple         | MacBookPro11,2              | [6bebb2e751](https://linux-hardware.org/?probe=6bebb2e751) | Jul 17, 2023 |
| Apple         | MacBookPro8,1               | [7dd13cea49](https://linux-hardware.org/?probe=7dd13cea49) | Jul 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | [b53aa427b9](https://linux-hardware.org/?probe=b53aa427b9) | Jul 17, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [0bbd5c68bb](https://linux-hardware.org/?probe=0bbd5c68bb) | Jul 17, 2023 |
| Dell          | Inspiron 7400               | [793ffb4349](https://linux-hardware.org/?probe=793ffb4349) | Jul 17, 2023 |
| Dell          | Inspiron 7400               | [5bfc86eb6b](https://linux-hardware.org/?probe=5bfc86eb6b) | Jul 17, 2023 |
| Toshiba       | Satellite L755              | [5bb24e4fff](https://linux-hardware.org/?probe=5bb24e4fff) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [5be1306636](https://linux-hardware.org/?probe=5be1306636) | Jul 17, 2023 |
| Dell          | XPS 15 9500                 | [2b81f8a707](https://linux-hardware.org/?probe=2b81f8a707) | Jul 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [afb16ac821](https://linux-hardware.org/?probe=afb16ac821) | Jul 17, 2023 |
| HP            | Pavilion 15                 | [86870a7a20](https://linux-hardware.org/?probe=86870a7a20) | Jul 17, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [52d550e878](https://linux-hardware.org/?probe=52d550e878) | Jul 17, 2023 |
| Medion        | E6224                       | [4ffae87044](https://linux-hardware.org/?probe=4ffae87044) | Jul 17, 2023 |
| ASUSTek       | X555LAB                     | [85fcb1e2f0](https://linux-hardware.org/?probe=85fcb1e2f0) | Jul 16, 2023 |
| ASUSTek       | X75A1                       | [745ef2a79f](https://linux-hardware.org/?probe=745ef2a79f) | Jul 16, 2023 |
| HP            | EliteBook 8440p             | [bf92089000](https://linux-hardware.org/?probe=bf92089000) | Jul 16, 2023 |
| ASUSTek       | N76VM                       | [b00f20954a](https://linux-hardware.org/?probe=b00f20954a) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1625385cef](https://linux-hardware.org/?probe=1625385cef) | Jul 16, 2023 |
| MSI           | GX60 3CC                    | [99566dd038](https://linux-hardware.org/?probe=99566dd038) | Jul 16, 2023 |
| Acer          | Aspire V3-771               | [75d9ed2095](https://linux-hardware.org/?probe=75d9ed2095) | Jul 15, 2023 |
| Dell          | Latitude 7290               | [4675215b5f](https://linux-hardware.org/?probe=4675215b5f) | Jul 15, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [cabc9a2940](https://linux-hardware.org/?probe=cabc9a2940) | Jul 15, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | [437209972c](https://linux-hardware.org/?probe=437209972c) | Jul 15, 2023 |
| Acer          | Aspire A315-51              | [938e7cd384](https://linux-hardware.org/?probe=938e7cd384) | Jul 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [c76e3df311](https://linux-hardware.org/?probe=c76e3df311) | Jul 14, 2023 |
| Apple         | MacBookPro6,2               | [990cd83468](https://linux-hardware.org/?probe=990cd83468) | Jul 14, 2023 |
| Lenovo        | G50-70 20351                | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| HP            | ProBook 640 G2              | [e5efd1b971](https://linux-hardware.org/?probe=e5efd1b971) | Jul 14, 2023 |
| Dell          | Latitude E6230              | [1577fae8ee](https://linux-hardware.org/?probe=1577fae8ee) | Jul 14, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [26fda3b894](https://linux-hardware.org/?probe=26fda3b894) | Jul 14, 2023 |
| HP            | Pavilion HDX9000            | [34940122a6](https://linux-hardware.org/?probe=34940122a6) | Jul 14, 2023 |
| Medion        | Akoya E6418 MD99620         | [7416e91f77](https://linux-hardware.org/?probe=7416e91f77) | Jul 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | [2213337296](https://linux-hardware.org/?probe=2213337296) | Jul 14, 2023 |
| HP            | Laptop 17-bs1xx             | [26a95caa91](https://linux-hardware.org/?probe=26a95caa91) | Jul 14, 2023 |
| Packard Be... | EasyNote LM85               | [3efd87a0d8](https://linux-hardware.org/?probe=3efd87a0d8) | Jul 14, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | [698c4a8958](https://linux-hardware.org/?probe=698c4a8958) | Jul 14, 2023 |
| Acer          | Swift SF314-71              | [95a7d172c2](https://linux-hardware.org/?probe=95a7d172c2) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | [d2d9d84e27](https://linux-hardware.org/?probe=d2d9d84e27) | Jul 13, 2023 |
| Acer          | Swift SF314-71              | [876eb35009](https://linux-hardware.org/?probe=876eb35009) | Jul 13, 2023 |
| Acer          | Aspire E5-774G              | [7f06f99146](https://linux-hardware.org/?probe=7f06f99146) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | [46d98ecf9a](https://linux-hardware.org/?probe=46d98ecf9a) | Jul 13, 2023 |
| HP            | Laptop 15-db0xxx            | [301dbaa508](https://linux-hardware.org/?probe=301dbaa508) | Jul 13, 2023 |
| Acer          | Aspire 4820TG               | [a93793ae9c](https://linux-hardware.org/?probe=a93793ae9c) | Jul 13, 2023 |
| Fujitsu       | LIFEBOOK A530               | [da70565d12](https://linux-hardware.org/?probe=da70565d12) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | [d605371dc3](https://linux-hardware.org/?probe=d605371dc3) | Jul 13, 2023 |
| Acer          | Nitro AN515-45              | [2e11b53615](https://linux-hardware.org/?probe=2e11b53615) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [2015dd83cb](https://linux-hardware.org/?probe=2015dd83cb) | Jul 12, 2023 |
| HP            | EliteBook 745 G2            | [8f732d599e](https://linux-hardware.org/?probe=8f732d599e) | Jul 12, 2023 |
| Lenovo        | G550 2958                   | [3be8a7bcff](https://linux-hardware.org/?probe=3be8a7bcff) | Jul 12, 2023 |
| HP            | Elite x2 1012 G1            | [09f6949e95](https://linux-hardware.org/?probe=09f6949e95) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [e594307388](https://linux-hardware.org/?probe=e594307388) | Jul 12, 2023 |
| Lenovo        | ThinkPad T560 20FHA03TGE    | [1dbf924d0e](https://linux-hardware.org/?probe=1dbf924d0e) | Jul 12, 2023 |
| MSI           | SUMMIT E13FlipEvo A12MT     | [90faae34f3](https://linux-hardware.org/?probe=90faae34f3) | Jul 12, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e2792f841d](https://linux-hardware.org/?probe=e2792f841d) | Jul 12, 2023 |
| Lenovo        | G550 2958                   | [be3dc3329e](https://linux-hardware.org/?probe=be3dc3329e) | Jul 12, 2023 |
| ASUSTek       | P53E                        | [e8081090a3](https://linux-hardware.org/?probe=e8081090a3) | Jul 12, 2023 |
| VALE          | Notebook Classic C140       | [90f5732595](https://linux-hardware.org/?probe=90f5732595) | Jul 11, 2023 |
| Dell          | Inspiron 13-5368            | [3048699131](https://linux-hardware.org/?probe=3048699131) | Jul 11, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [6e7ff15b27](https://linux-hardware.org/?probe=6e7ff15b27) | Jul 11, 2023 |
| HP            | G62                         | [c202be1723](https://linux-hardware.org/?probe=c202be1723) | Jul 11, 2023 |
| Fujitsu       | LIFEBOOK E780               | [ab432dcb0e](https://linux-hardware.org/?probe=ab432dcb0e) | Jul 11, 2023 |
| Thomson       | GEN15C8SL256                | [5820f59f33](https://linux-hardware.org/?probe=5820f59f33) | Jul 11, 2023 |
| Acer          | Aspire V3-771               | [057560f5ad](https://linux-hardware.org/?probe=057560f5ad) | Jul 11, 2023 |
| Lenovo        | ThinkPad T430 23501B3       | [8f1d64206e](https://linux-hardware.org/?probe=8f1d64206e) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [11eed5426e](https://linux-hardware.org/?probe=11eed5426e) | Jul 11, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [f09d4ec214](https://linux-hardware.org/?probe=f09d4ec214) | Jul 11, 2023 |
| Lenovo        | IdeaPad Slim 3 14AMN8 82... | [47c4706927](https://linux-hardware.org/?probe=47c4706927) | Jul 10, 2023 |
| Thomson       | GEN15C8SL256                | [e6959db4b4](https://linux-hardware.org/?probe=e6959db4b4) | Jul 10, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [f273c7ffee](https://linux-hardware.org/?probe=f273c7ffee) | Jul 10, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [a5d9143c99](https://linux-hardware.org/?probe=a5d9143c99) | Jul 10, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [33c3fbd9ff](https://linux-hardware.org/?probe=33c3fbd9ff) | Jul 10, 2023 |
| Toshiba       | Satellite C850-1MN          | [dc54b6905e](https://linux-hardware.org/?probe=dc54b6905e) | Jul 10, 2023 |
| Medion        | Akoya P2214T                | [341fc04e6c](https://linux-hardware.org/?probe=341fc04e6c) | Jul 10, 2023 |
| Lenovo        | B560 43308UG                | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Lenovo        | ThinkPad T520 42435JG       | [1e41ad8e38](https://linux-hardware.org/?probe=1e41ad8e38) | Jul 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | [e853f79dd4](https://linux-hardware.org/?probe=e853f79dd4) | Jul 09, 2023 |
| Dell          | Latitude E6230              | [dd453671f3](https://linux-hardware.org/?probe=dd453671f3) | Jul 09, 2023 |
| Fujitsu Si... | AMILO Pa 1510               | [b51a760728](https://linux-hardware.org/?probe=b51a760728) | Jul 09, 2023 |
| HP            | Pavilion g7                 | [5e2cf6a804](https://linux-hardware.org/?probe=5e2cf6a804) | Jul 09, 2023 |
| Samsung       | R780                        | [20ca919523](https://linux-hardware.org/?probe=20ca919523) | Jul 09, 2023 |
| Samsung       | R780                        | [c5fb0ee6aa](https://linux-hardware.org/?probe=c5fb0ee6aa) | Jul 09, 2023 |
| Fujitsu       | LIFEBOOK S752               | [a2bd9b682d](https://linux-hardware.org/?probe=a2bd9b682d) | Jul 08, 2023 |
| Lenovo        | ThinkPad X240 20AMS3S919    | [63e13bb1f2](https://linux-hardware.org/?probe=63e13bb1f2) | Jul 08, 2023 |
| Apple         | MacBookPro11,1              | [eb31d015ff](https://linux-hardware.org/?probe=eb31d015ff) | Jul 08, 2023 |
| Lenovo        | ThinkPad A275 20KCS08C0K    | [9857dab3ab](https://linux-hardware.org/?probe=9857dab3ab) | Jul 08, 2023 |
| Acer          | Swift SF515-51T             | [9a9c9af000](https://linux-hardware.org/?probe=9a9c9af000) | Jul 08, 2023 |
| Fujitsu       | LIFEBOOK S938               | [8d2f776940](https://linux-hardware.org/?probe=8d2f776940) | Jul 08, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | [cd45163d47](https://linux-hardware.org/?probe=cd45163d47) | Jul 08, 2023 |
| Dell          | Vostro 15 3535              | [8b67e5b282](https://linux-hardware.org/?probe=8b67e5b282) | Jul 08, 2023 |
| Acer          | AS VN7-571G                 | [7e0ceb9818](https://linux-hardware.org/?probe=7e0ceb9818) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [96d1578908](https://linux-hardware.org/?probe=96d1578908) | Jul 07, 2023 |
| Schenker      | VIA 15 Pro                  | [bec6fac79a](https://linux-hardware.org/?probe=bec6fac79a) | Jul 07, 2023 |
| Apple         | MacBookPro11,4              | [4ea2a95674](https://linux-hardware.org/?probe=4ea2a95674) | Jul 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS17228     | [cb869cfeab](https://linux-hardware.org/?probe=cb869cfeab) | Jul 07, 2023 |
| Fujitsu       | LIFEBOOK U758               | [eaa8bbf9da](https://linux-hardware.org/?probe=eaa8bbf9da) | Jul 07, 2023 |
| Lenovo        | ThinkPad X260 20F5S0V500    | [760a6712db](https://linux-hardware.org/?probe=760a6712db) | Jul 07, 2023 |
| Medion        | Akoya P2214T                | [e2c31b421a](https://linux-hardware.org/?probe=e2c31b421a) | Jul 07, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [25bf789962](https://linux-hardware.org/?probe=25bf789962) | Jul 07, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a9e9fe8243](https://linux-hardware.org/?probe=a9e9fe8243) | Jul 07, 2023 |
| MSI           | GP70 2QF                    | [5d6c0e9b23](https://linux-hardware.org/?probe=5d6c0e9b23) | Jul 06, 2023 |
| ASUSTek       | X75VC                       | [636145e5c0](https://linux-hardware.org/?probe=636145e5c0) | Jul 06, 2023 |
| Dell          | Latitude 7430               | [743d41d534](https://linux-hardware.org/?probe=743d41d534) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | [12a6839453](https://linux-hardware.org/?probe=12a6839453) | Jul 06, 2023 |
| TUXEDO        | Book XUX7 Gen13             | [e480e61359](https://linux-hardware.org/?probe=e480e61359) | Jul 06, 2023 |
| HP            | EliteBook 840 G3            | [5af1e951c9](https://linux-hardware.org/?probe=5af1e951c9) | Jul 06, 2023 |
| HP            | Laptop 17-bs1xx             | [ec66938fb1](https://linux-hardware.org/?probe=ec66938fb1) | Jul 06, 2023 |
| Dell          | Latitude E7270              | [406e4a918b](https://linux-hardware.org/?probe=406e4a918b) | Jul 06, 2023 |
| Valve         | Jupiter                     | [1256447c33](https://linux-hardware.org/?probe=1256447c33) | Jul 06, 2023 |
| Sony          | VPCEA1AGG                   | [edbc1fff31](https://linux-hardware.org/?probe=edbc1fff31) | Jul 05, 2023 |
| HP            | EliteBook 755 G5            | [356eae0e07](https://linux-hardware.org/?probe=356eae0e07) | Jul 05, 2023 |
| Lenovo        | G50-70 20351                | [26145eba2e](https://linux-hardware.org/?probe=26145eba2e) | Jul 05, 2023 |
| HP            | 250 G7 Notebook PC          | [a3d75416d1](https://linux-hardware.org/?probe=a3d75416d1) | Jul 05, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| Sony          | SVF1521B4E                  | [31ca39bf23](https://linux-hardware.org/?probe=31ca39bf23) | Jul 05, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [8e16561151](https://linux-hardware.org/?probe=8e16561151) | Jul 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [5e18a2d43c](https://linux-hardware.org/?probe=5e18a2d43c) | Jul 05, 2023 |
| HP            | Laptop 15-da0xxx            | [f634e3942a](https://linux-hardware.org/?probe=f634e3942a) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | [40b7950cb2](https://linux-hardware.org/?probe=40b7950cb2) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | [73435e5646](https://linux-hardware.org/?probe=73435e5646) | Jul 05, 2023 |
| Packard Be... | IPOWER                      | [3c116708b4](https://linux-hardware.org/?probe=3c116708b4) | Jul 05, 2023 |
| Valve         | Jupiter                     | [3ae34472ca](https://linux-hardware.org/?probe=3ae34472ca) | Jul 04, 2023 |
| Acer          | Aspire 4820TG               | [69e40b4481](https://linux-hardware.org/?probe=69e40b4481) | Jul 04, 2023 |
| Dell          | Precision M4800             | [6b8b9d5bd0](https://linux-hardware.org/?probe=6b8b9d5bd0) | Jul 04, 2023 |
| ASUSTek       | N76VM                       | [4ea34c4ac0](https://linux-hardware.org/?probe=4ea34c4ac0) | Jul 04, 2023 |
| HP            | EliteBook 840 G6            | [d072001450](https://linux-hardware.org/?probe=d072001450) | Jul 04, 2023 |
| Medion        | E15301                      | [0682c086cb](https://linux-hardware.org/?probe=0682c086cb) | Jul 04, 2023 |
| HP            | EliteBook 6930p             | [b7328dc212](https://linux-hardware.org/?probe=b7328dc212) | Jul 04, 2023 |
| MSI           | GP70 2QF                    | [a8ffe05f9f](https://linux-hardware.org/?probe=a8ffe05f9f) | Jul 03, 2023 |
| ASUSTek       | 1015PN                      | [7482ea5fc2](https://linux-hardware.org/?probe=7482ea5fc2) | Jul 03, 2023 |
| Dell          | G5 5590                     | [c956c1fd2e](https://linux-hardware.org/?probe=c956c1fd2e) | Jul 03, 2023 |
| HP            | Laptop 15s-eq2xxx           | [25d3329df1](https://linux-hardware.org/?probe=25d3329df1) | Jul 03, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [67c131f536](https://linux-hardware.org/?probe=67c131f536) | Jul 03, 2023 |
| Lenovo        | ThinkPad T590 20N4002VGE    | [1e805e975e](https://linux-hardware.org/?probe=1e805e975e) | Jul 03, 2023 |
| Gigabyte      | G5 GE                       | [c8f96f1825](https://linux-hardware.org/?probe=c8f96f1825) | Jul 03, 2023 |
| HUAWEI        | HVY-WXX9                    | [2585d66bd1](https://linux-hardware.org/?probe=2585d66bd1) | Jul 03, 2023 |
| Medion        | E15301                      | [2531465ecd](https://linux-hardware.org/?probe=2531465ecd) | Jul 03, 2023 |
| Dell          | Latitude 7530               | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [cc0464c9a4](https://linux-hardware.org/?probe=cc0464c9a4) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [6686fca24b](https://linux-hardware.org/?probe=6686fca24b) | Jul 03, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [ccb318cd32](https://linux-hardware.org/?probe=ccb318cd32) | Jul 03, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [8fc6ae0352](https://linux-hardware.org/?probe=8fc6ae0352) | Jul 03, 2023 |
| Sony          | SVF1521B4E                  | [ad4f5c5d91](https://linux-hardware.org/?probe=ad4f5c5d91) | Jul 03, 2023 |
| Unknown       | Unknown                     | [849c84499e](https://linux-hardware.org/?probe=849c84499e) | Jul 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [e8ff92b585](https://linux-hardware.org/?probe=e8ff92b585) | Jul 03, 2023 |
| HP            | EliteBook 840 G3            | [ed37dd6278](https://linux-hardware.org/?probe=ed37dd6278) | Jul 03, 2023 |
| Sony          | VPCEA1AGG                   | [de28a65daa](https://linux-hardware.org/?probe=de28a65daa) | Jul 02, 2023 |
| Fujitsu Si... | LIFEBOOK E8420              | [c997fd76cf](https://linux-hardware.org/?probe=c997fd76cf) | Jul 02, 2023 |
| Lenovo        | ThinkPad T520 4243B65       | [07584ce70c](https://linux-hardware.org/?probe=07584ce70c) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| Apple         | MacBookPro8,2               | [e9440ca77a](https://linux-hardware.org/?probe=e9440ca77a) | Jul 02, 2023 |
| Lenovo        | G50-70 20351                | [033ce7c13d](https://linux-hardware.org/?probe=033ce7c13d) | Jul 02, 2023 |
| Fujitsu       | LIFEBOOK A544               | [1d192a08b6](https://linux-hardware.org/?probe=1d192a08b6) | Jul 02, 2023 |
| Acer          | Aspire ES1-571              | [08bf46431e](https://linux-hardware.org/?probe=08bf46431e) | Jul 02, 2023 |
| Lenovo        | ThinkPad T410 2537PW4       | [10079a3e26](https://linux-hardware.org/?probe=10079a3e26) | Jul 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | [2eb6c4356c](https://linux-hardware.org/?probe=2eb6c4356c) | Jul 02, 2023 |
| ASUSTek       | F5SR                        | [8a96310d69](https://linux-hardware.org/?probe=8a96310d69) | Jul 02, 2023 |
| Lenovo        | ThinkPad T530 2429AA9       | [708fe309bc](https://linux-hardware.org/?probe=708fe309bc) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [d69c578d83](https://linux-hardware.org/?probe=d69c578d83) | Jul 02, 2023 |
| MSI           | GP70 2QF                    | [993cc6ebac](https://linux-hardware.org/?probe=993cc6ebac) | Jul 02, 2023 |
| Lex BayTra... | 2I380D                      | [2e20df184f](https://linux-hardware.org/?probe=2e20df184f) | Jul 02, 2023 |
| HP            | Compaq 6910p                | [d72eacd7ea](https://linux-hardware.org/?probe=d72eacd7ea) | Jul 02, 2023 |
| Lenovo        | G550 2958                   | [d895cb5a47](https://linux-hardware.org/?probe=d895cb5a47) | Jul 02, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [3d599df965](https://linux-hardware.org/?probe=3d599df965) | Jul 02, 2023 |
| Lenovo        | G550 2958                   | [e408b71b8c](https://linux-hardware.org/?probe=e408b71b8c) | Jul 01, 2023 |
| HP            | EliteBook 840 G4            | [e8c59c8c25](https://linux-hardware.org/?probe=e8c59c8c25) | Jul 01, 2023 |
| Acer          | Predator PT515-51           | [fc639c945e](https://linux-hardware.org/?probe=fc639c945e) | Jul 01, 2023 |
| Dell          | Latitude E6410              | [675794fe6e](https://linux-hardware.org/?probe=675794fe6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [a1a9486fc8](https://linux-hardware.org/?probe=a1a9486fc8) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| ASUSTek       | X510UQR                     | [2c5f862c42](https://linux-hardware.org/?probe=2c5f862c42) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Apple         | MacBookPro11,1              | [998267633e](https://linux-hardware.org/?probe=998267633e) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [f182eda3d3](https://linux-hardware.org/?probe=f182eda3d3) | Jul 01, 2023 |
| HP            | OMEN by Laptop              | [3702fd669f](https://linux-hardware.org/?probe=3702fd669f) | Jul 01, 2023 |
| HP            | OMEN by Laptop              | [10dc1c07c8](https://linux-hardware.org/?probe=10dc1c07c8) | Jul 01, 2023 |
| HUAWEI        | HKD-WXX                     | [18b69ee7ff](https://linux-hardware.org/?probe=18b69ee7ff) | Jul 01, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [2ba1cce30e](https://linux-hardware.org/?probe=2ba1cce30e) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [a559729258](https://linux-hardware.org/?probe=a559729258) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E780               | [12c5cd0309](https://linux-hardware.org/?probe=12c5cd0309) | Jul 01, 2023 |
| Valve         | Jupiter                     | [86984d2e19](https://linux-hardware.org/?probe=86984d2e19) | Jun 30, 2023 |
| Fujitsu       | LIFEBOOK P771               | [9d6575a3aa](https://linux-hardware.org/?probe=9d6575a3aa) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| HP            | EliteBook 850 G1            | [a5f3a5ad14](https://linux-hardware.org/?probe=a5f3a5ad14) | Jun 30, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [b15b3b6025](https://linux-hardware.org/?probe=b15b3b6025) | Jun 30, 2023 |
| ASUSTek       | N76VM                       | [df79346cd4](https://linux-hardware.org/?probe=df79346cd4) | Jun 30, 2023 |
| HP            | Laptop 17-cp2xxx            | [2012cd2c37](https://linux-hardware.org/?probe=2012cd2c37) | Jun 30, 2023 |
| Acer          | Aspire A315-56              | [3a814856ae](https://linux-hardware.org/?probe=3a814856ae) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [31db4fffd0](https://linux-hardware.org/?probe=31db4fffd0) | Jun 30, 2023 |
| HP            | EliteBook 8760w             | [470630eb65](https://linux-hardware.org/?probe=470630eb65) | Jun 30, 2023 |
| ASUSTek       | N76VM                       | [d770e894db](https://linux-hardware.org/?probe=d770e894db) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Valve         | Jupiter                     | [d8a4613446](https://linux-hardware.org/?probe=d8a4613446) | Jun 29, 2023 |
| Intel         | Whiskey Platform            | [1caca06d89](https://linux-hardware.org/?probe=1caca06d89) | Jun 29, 2023 |
| Medion        | Akoya P7818                 | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| Sony          | VGN-FE41M                   | [3bc894dc99](https://linux-hardware.org/?probe=3bc894dc99) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [a24ee9a903](https://linux-hardware.org/?probe=a24ee9a903) | Jun 29, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| HP            | EliteBook 840 G3            | [979c4b20fc](https://linux-hardware.org/?probe=979c4b20fc) | Jun 29, 2023 |
| HP            | Notebook                    | [a178cbf707](https://linux-hardware.org/?probe=a178cbf707) | Jun 29, 2023 |
| Acer          | Aspire A517-52              | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S68T00    | [a50310948a](https://linux-hardware.org/?probe=a50310948a) | Jun 29, 2023 |
| Acer          | Aspire 5830TG               | [8c001b69bb](https://linux-hardware.org/?probe=8c001b69bb) | Jun 29, 2023 |
| HP            | Laptop 17-cp2xxx            | [f1a1aa76e2](https://linux-hardware.org/?probe=f1a1aa76e2) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| Acer          | Aspire V5-572P              | [1a28142960](https://linux-hardware.org/?probe=1a28142960) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [5819c72f02](https://linux-hardware.org/?probe=5819c72f02) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | [892229f999](https://linux-hardware.org/?probe=892229f999) | Jun 28, 2023 |
| HP            | Laptop 15-db0xxx            | [6d470794e9](https://linux-hardware.org/?probe=6d470794e9) | Jun 28, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ed4a581e3e](https://linux-hardware.org/?probe=ed4a581e3e) | Jun 28, 2023 |
| ASUSTek       | F5SR                        | [3722cfa5fb](https://linux-hardware.org/?probe=3722cfa5fb) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | [cd65c92d12](https://linux-hardware.org/?probe=cd65c92d12) | Jun 27, 2023 |
| Acer          | Aspire E5-573               | [e3b1cdc71c](https://linux-hardware.org/?probe=e3b1cdc71c) | Jun 27, 2023 |
| TUXEDO        | P64_HJ,HK1                  | [4c542d50e7](https://linux-hardware.org/?probe=4c542d50e7) | Jun 27, 2023 |
| Acer          | Aspire 5738                 | [09d8109c56](https://linux-hardware.org/?probe=09d8109c56) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| Acer          | Aspire E5-573G              | [fc532e9492](https://linux-hardware.org/?probe=fc532e9492) | Jun 27, 2023 |
| Dell          | Latitude E6230              | [b52e22e663](https://linux-hardware.org/?probe=b52e22e663) | Jun 27, 2023 |
| Valve         | Jupiter                     | [563dc53040](https://linux-hardware.org/?probe=563dc53040) | Jun 27, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [d3e14b3015](https://linux-hardware.org/?probe=d3e14b3015) | Jun 26, 2023 |
| Dell          | Precision 5570              | [dbf68aa669](https://linux-hardware.org/?probe=dbf68aa669) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T1J    | [91955c07a6](https://linux-hardware.org/?probe=91955c07a6) | Jun 26, 2023 |
| ASUSTek       | F5SR                        | [059a0b2611](https://linux-hardware.org/?probe=059a0b2611) | Jun 26, 2023 |
| HP            | EliteBook 8560w             | [dc55ec08b3](https://linux-hardware.org/?probe=dc55ec08b3) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [44f08646c1](https://linux-hardware.org/?probe=44f08646c1) | Jun 26, 2023 |
| Unknown       | Unknown                     | [736f2d7bb5](https://linux-hardware.org/?probe=736f2d7bb5) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| Fujitsu       | LIFEBOOK S751               | [94fe70521f](https://linux-hardware.org/?probe=94fe70521f) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [de0797cd44](https://linux-hardware.org/?probe=de0797cd44) | Jun 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [8b0180f4d4](https://linux-hardware.org/?probe=8b0180f4d4) | Jun 25, 2023 |
| Acer          | Swift SFX16-52G             | [28c4b7b2f3](https://linux-hardware.org/?probe=28c4b7b2f3) | Jun 25, 2023 |
| Acer          | Swift SFX16-52G             | [ac98f81b2a](https://linux-hardware.org/?probe=ac98f81b2a) | Jun 25, 2023 |
| ASUSTek       | N501VW                      | [7513f535f9](https://linux-hardware.org/?probe=7513f535f9) | Jun 25, 2023 |
| ASUSTek       | X75VC                       | [9fd44ac61e](https://linux-hardware.org/?probe=9fd44ac61e) | Jun 25, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e172f7e955](https://linux-hardware.org/?probe=e172f7e955) | Jun 25, 2023 |
| ASUSTek       | K54C                        | [38e6ce020c](https://linux-hardware.org/?probe=38e6ce020c) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| Unknown       | Unknown                     | [72c377827d](https://linux-hardware.org/?probe=72c377827d) | Jun 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [df9521a37d](https://linux-hardware.org/?probe=df9521a37d) | Jun 24, 2023 |
| ASUSTek       | X750LN                      | [739ab83805](https://linux-hardware.org/?probe=739ab83805) | Jun 24, 2023 |
| HP            | Pavilion Notebook           | [e80fd49ba9](https://linux-hardware.org/?probe=e80fd49ba9) | Jun 24, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [71f17d4d74](https://linux-hardware.org/?probe=71f17d4d74) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [8a22a7fba4](https://linux-hardware.org/?probe=8a22a7fba4) | Jun 24, 2023 |
| Dell          | Inspiron 5767               | [9e3bf66b84](https://linux-hardware.org/?probe=9e3bf66b84) | Jun 24, 2023 |
| Dell          | Latitude E6500              | [2b1720ad90](https://linux-hardware.org/?probe=2b1720ad90) | Jun 24, 2023 |
| MSI           | GS63 7RD                    | [310191e110](https://linux-hardware.org/?probe=310191e110) | Jun 24, 2023 |
| ASUSTek       | K53TK                       | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| Lenovo        | V145-15AST 81MT             | [1fe939429c](https://linux-hardware.org/?probe=1fe939429c) | Jun 24, 2023 |
| Valve         | Jupiter                     | [ba0343b607](https://linux-hardware.org/?probe=ba0343b607) | Jun 24, 2023 |
| Dell          | XPS 15 9570                 | [2c09eb930c](https://linux-hardware.org/?probe=2c09eb930c) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | [f51aeb6252](https://linux-hardware.org/?probe=f51aeb6252) | Jun 23, 2023 |
| Gigabyte      | AORUS 15P YD                | [1e2fb31885](https://linux-hardware.org/?probe=1e2fb31885) | Jun 23, 2023 |
| ASUSTek       | X555LAB                     | [7b227bbaed](https://linux-hardware.org/?probe=7b227bbaed) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | [46e9b730a1](https://linux-hardware.org/?probe=46e9b730a1) | Jun 23, 2023 |
| Medion        | P6624                       | [49bd227ded](https://linux-hardware.org/?probe=49bd227ded) | Jun 23, 2023 |
| MSI           | S12T 3M/S12 3M              | [f135825cec](https://linux-hardware.org/?probe=f135825cec) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [3cdf59359c](https://linux-hardware.org/?probe=3cdf59359c) | Jun 23, 2023 |
| HP            | Pavilion Notebook           | [cc0361248f](https://linux-hardware.org/?probe=cc0361248f) | Jun 23, 2023 |
| Acer          | Swift SFX14-51G             | [c8f3981a52](https://linux-hardware.org/?probe=c8f3981a52) | Jun 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | [2faa400326](https://linux-hardware.org/?probe=2faa400326) | Jun 23, 2023 |
| TUXEDO        | Unknown                     | [71a75069f7](https://linux-hardware.org/?probe=71a75069f7) | Jun 23, 2023 |
| Dell          | Latitude E6510              | [a85838194d](https://linux-hardware.org/?probe=a85838194d) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [efad2eddea](https://linux-hardware.org/?probe=efad2eddea) | Jun 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [70b047f976](https://linux-hardware.org/?probe=70b047f976) | Jun 22, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [9d234065ed](https://linux-hardware.org/?probe=9d234065ed) | Jun 22, 2023 |
| Dell          | XPS 17 9710                 | [892620ac83](https://linux-hardware.org/?probe=892620ac83) | Jun 22, 2023 |
| Sony          | SVE1712C1EW                 | [12f0ee026f](https://linux-hardware.org/?probe=12f0ee026f) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4ae6c879aa](https://linux-hardware.org/?probe=4ae6c879aa) | Jun 22, 2023 |
| Acer          | Swift SFE16-42              | [9afa4fb174](https://linux-hardware.org/?probe=9afa4fb174) | Jun 22, 2023 |
| Framework     | Laptop                      | [eb51a9a662](https://linux-hardware.org/?probe=eb51a9a662) | Jun 22, 2023 |
| HP            | EliteBook 820 G3            | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| Acer          | Aspire V5-552G              | [adeea10c6c](https://linux-hardware.org/?probe=adeea10c6c) | Jun 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [8158959dbd](https://linux-hardware.org/?probe=8158959dbd) | Jun 22, 2023 |
| HP            | EliteBook 8540p             | [c72d0ef702](https://linux-hardware.org/?probe=c72d0ef702) | Jun 22, 2023 |
| Lenovo        | ThinkPad L380 20M5000UGE    | [06db720b62](https://linux-hardware.org/?probe=06db720b62) | Jun 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [888133764a](https://linux-hardware.org/?probe=888133764a) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [522dfb5977](https://linux-hardware.org/?probe=522dfb5977) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [601921c51d](https://linux-hardware.org/?probe=601921c51d) | Jun 21, 2023 |
| ASUSTek       | G752VM                      | [b518236bd7](https://linux-hardware.org/?probe=b518236bd7) | Jun 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo        | ThinkPad T510 4349WHC       | [9134464b7a](https://linux-hardware.org/?probe=9134464b7a) | Jun 21, 2023 |
| Acer          | Extensa 2519                | [36f37b33d5](https://linux-hardware.org/?probe=36f37b33d5) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [510604914c](https://linux-hardware.org/?probe=510604914c) | Jun 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [ab169bfbfd](https://linux-hardware.org/?probe=ab169bfbfd) | Jun 21, 2023 |
| HONOR         | HLYL-WXX9                   | [498f41554b](https://linux-hardware.org/?probe=498f41554b) | Jun 21, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [76fbd356a0](https://linux-hardware.org/?probe=76fbd356a0) | Jun 21, 2023 |
| Apple         | MacBookPro6,2               | [3beb323b62](https://linux-hardware.org/?probe=3beb323b62) | Jun 21, 2023 |
| Packard Be... | EasyNote TE11HC             | [6bbc56b36c](https://linux-hardware.org/?probe=6bbc56b36c) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [293b8783a3](https://linux-hardware.org/?probe=293b8783a3) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [2f452cfce0](https://linux-hardware.org/?probe=2f452cfce0) | Jun 20, 2023 |
| Apple         | MacBookPro5,5               | [16c4045c3b](https://linux-hardware.org/?probe=16c4045c3b) | Jun 20, 2023 |
| HUAWEI        | CREM-WXX9                   | [55182e9371](https://linux-hardware.org/?probe=55182e9371) | Jun 20, 2023 |
| TUXEDO        | P95xER                      | [f2f6ddaf27](https://linux-hardware.org/?probe=f2f6ddaf27) | Jun 20, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [3be3d70197](https://linux-hardware.org/?probe=3be3d70197) | Jun 20, 2023 |
| HP            | 255 G7 Notebook PC          | [3db68832fd](https://linux-hardware.org/?probe=3db68832fd) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| MSI           | GT70 2OC/2OD                | [d8d81f0614](https://linux-hardware.org/?probe=d8d81f0614) | Jun 20, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [dd152b03bc](https://linux-hardware.org/?probe=dd152b03bc) | Jun 20, 2023 |
| TUXEDO        | P65xRP                      | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Valve         | Jupiter                     | [f4e47bb83e](https://linux-hardware.org/?probe=f4e47bb83e) | Jun 20, 2023 |
| HP            | EliteBook 840 G6            | [82c9c200bc](https://linux-hardware.org/?probe=82c9c200bc) | Jun 20, 2023 |
| HP            | Pavilion dv6                | [09d49049bf](https://linux-hardware.org/?probe=09d49049bf) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [91f85b5bb5](https://linux-hardware.org/?probe=91f85b5bb5) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [93f576698e](https://linux-hardware.org/?probe=93f576698e) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [a0862de551](https://linux-hardware.org/?probe=a0862de551) | Jun 19, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [3cfd8a448c](https://linux-hardware.org/?probe=3cfd8a448c) | Jun 19, 2023 |
| HP            | Pavilion Laptop 13-an0xx... | [0f68ace67c](https://linux-hardware.org/?probe=0f68ace67c) | Jun 19, 2023 |
| Lenovo        | ThinkPad T450s 20BWS11H0... | [596055aa43](https://linux-hardware.org/?probe=596055aa43) | Jun 19, 2023 |
| HP            | Laptop 15-db0xxx            | [c67d08fe43](https://linux-hardware.org/?probe=c67d08fe43) | Jun 19, 2023 |
| HP            | Laptop 14s-fq0xxx           | [6ff28ccac1](https://linux-hardware.org/?probe=6ff28ccac1) | Jun 19, 2023 |
| Acer          | Aspire 7739                 | [eda7fb180a](https://linux-hardware.org/?probe=eda7fb180a) | Jun 19, 2023 |
| MSI           | GL72M 7REX                  | [6d50ff945d](https://linux-hardware.org/?probe=6d50ff945d) | Jun 19, 2023 |
| HP            | ProBook 650 G3              | [009fdf15c4](https://linux-hardware.org/?probe=009fdf15c4) | Jun 19, 2023 |
| Packard Be... | EasyNote TE11HC             | [33785e2493](https://linux-hardware.org/?probe=33785e2493) | Jun 18, 2023 |
| Acer          | Aspire 7739                 | [34854e20dd](https://linux-hardware.org/?probe=34854e20dd) | Jun 18, 2023 |
| MSI           | MS-16Y1                     | [167889509f](https://linux-hardware.org/?probe=167889509f) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | [ce3c5bc056](https://linux-hardware.org/?probe=ce3c5bc056) | Jun 18, 2023 |
| ASUSTek       | X555LJ                      | [a4bea0f3e3](https://linux-hardware.org/?probe=a4bea0f3e3) | Jun 18, 2023 |
| ASUSTek       | X555LA                      | [a57885e16c](https://linux-hardware.org/?probe=a57885e16c) | Jun 18, 2023 |
| HP            | Notebook                    | [e53b70bcac](https://linux-hardware.org/?probe=e53b70bcac) | Jun 18, 2023 |
| ASUSTek       | X556UQK                     | [fb675907ec](https://linux-hardware.org/?probe=fb675907ec) | Jun 18, 2023 |
| Dell          | Precision M4800             | [9f86d737f2](https://linux-hardware.org/?probe=9f86d737f2) | Jun 18, 2023 |
| HP            | Compaq Presario CQ71        | [d5025e2864](https://linux-hardware.org/?probe=d5025e2864) | Jun 18, 2023 |
| HP            | EliteBook 840 G5            | [7c7742bf5a](https://linux-hardware.org/?probe=7c7742bf5a) | Jun 18, 2023 |
| VALE          | Notebook Classic C140       | [afa3a9de5e](https://linux-hardware.org/?probe=afa3a9de5e) | Jun 18, 2023 |
| Sony          | SVF1421L1EW                 | [5d377cbe13](https://linux-hardware.org/?probe=5d377cbe13) | Jun 17, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [2bfd69673e](https://linux-hardware.org/?probe=2bfd69673e) | Jun 17, 2023 |
| Sony          | SVF1421L1EW                 | [e4dc7d363e](https://linux-hardware.org/?probe=e4dc7d363e) | Jun 17, 2023 |
| HP            | Notebook                    | [f01887f9d6](https://linux-hardware.org/?probe=f01887f9d6) | Jun 17, 2023 |
| HP            | 250 G4                      | [f25c49812b](https://linux-hardware.org/?probe=f25c49812b) | Jun 17, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [9206f6c141](https://linux-hardware.org/?probe=9206f6c141) | Jun 17, 2023 |
| HP            | EliteBook 8440p             | [4b1b2457a4](https://linux-hardware.org/?probe=4b1b2457a4) | Jun 17, 2023 |
| Medion        | S15449                      | [9ee17b411b](https://linux-hardware.org/?probe=9ee17b411b) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop      | [2d5c5b2c80](https://linux-hardware.org/?probe=2d5c5b2c80) | Jun 17, 2023 |
| Lenovo        | ThinkPad Edge E535 3260F... | [3fd273f672](https://linux-hardware.org/?probe=3fd273f672) | Jun 17, 2023 |
| Medion        | E6214                       | [5547ea042f](https://linux-hardware.org/?probe=5547ea042f) | Jun 17, 2023 |
| Medion        | E6214                       | [98ddb6700a](https://linux-hardware.org/?probe=98ddb6700a) | Jun 17, 2023 |
| Dell          | Inspiron 3593               | [46ad2c78f7](https://linux-hardware.org/?probe=46ad2c78f7) | Jun 17, 2023 |
| Toshiba       | Satellite L775D-107         | [7959d73eb9](https://linux-hardware.org/?probe=7959d73eb9) | Jun 17, 2023 |
| ASUSTek       | K73BR                       | [9f4d2564bf](https://linux-hardware.org/?probe=9f4d2564bf) | Jun 16, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [45d3e053e3](https://linux-hardware.org/?probe=45d3e053e3) | Jun 16, 2023 |
| Lenovo        | ThinkPad P51 20HJS1SF00     | [664ae7a0f2](https://linux-hardware.org/?probe=664ae7a0f2) | Jun 16, 2023 |
| Samsung       | 750XDA                      | [e04dd13d49](https://linux-hardware.org/?probe=e04dd13d49) | Jun 16, 2023 |
| Dell          | Latitude D620               | [8dc25931d7](https://linux-hardware.org/?probe=8dc25931d7) | Jun 16, 2023 |
| Dell          | Latitude D620               | [819f346812](https://linux-hardware.org/?probe=819f346812) | Jun 16, 2023 |
| HONOR         | BMH-WCX9                    | [da0a4b3bf0](https://linux-hardware.org/?probe=da0a4b3bf0) | Jun 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ea2e8604af](https://linux-hardware.org/?probe=ea2e8604af) | Jun 16, 2023 |
| Dell          | Precision 3570              | [6f6debf1a4](https://linux-hardware.org/?probe=6f6debf1a4) | Jun 15, 2023 |
| MSI           | GL72M 7REX                  | [1f1699301f](https://linux-hardware.org/?probe=1f1699301f) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | [32eb9f5dea](https://linux-hardware.org/?probe=32eb9f5dea) | Jun 15, 2023 |
| Acer          | Swift SF114-34              | [9f9ffda2e3](https://linux-hardware.org/?probe=9f9ffda2e3) | Jun 15, 2023 |
| Acer          | TravelMate 8172             | [569fde2487](https://linux-hardware.org/?probe=569fde2487) | Jun 15, 2023 |
| ASUSTek       | K70AC                       | [b9dc7d0b00](https://linux-hardware.org/?probe=b9dc7d0b00) | Jun 15, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Dell          | Latitude E7450              | [05ebaf45ae](https://linux-hardware.org/?probe=05ebaf45ae) | Jun 15, 2023 |
| Medion        | E6214                       | [71b2e69534](https://linux-hardware.org/?probe=71b2e69534) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | [ff98efdef7](https://linux-hardware.org/?probe=ff98efdef7) | Jun 15, 2023 |
| HP            | EliteBook 1040 G4           | [01724286d9](https://linux-hardware.org/?probe=01724286d9) | Jun 15, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5b85dc34c6](https://linux-hardware.org/?probe=5b85dc34c6) | Jun 15, 2023 |
| Dell          | Precision M4500             | [5daca408ec](https://linux-hardware.org/?probe=5daca408ec) | Jun 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [65298dde46](https://linux-hardware.org/?probe=65298dde46) | Jun 14, 2023 |
| HP            | ENVY 17                     | [269ca0c6e9](https://linux-hardware.org/?probe=269ca0c6e9) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | [8f84dca464](https://linux-hardware.org/?probe=8f84dca464) | Jun 14, 2023 |
| Dell          | Latitude 7430               | [6cf1c68c1d](https://linux-hardware.org/?probe=6cf1c68c1d) | Jun 14, 2023 |
| HP            | Pavilion 17                 | [bf5d126cc8](https://linux-hardware.org/?probe=bf5d126cc8) | Jun 14, 2023 |
| ASUSTek       | X555LA                      | [782fa74afe](https://linux-hardware.org/?probe=782fa74afe) | Jun 14, 2023 |
| Dell          | XPS 9320                    | [a6567a0c58](https://linux-hardware.org/?probe=a6567a0c58) | Jun 13, 2023 |
| Fujitsu       | LIFEBOOK E780               | [b8631b65c4](https://linux-hardware.org/?probe=b8631b65c4) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | [1626648a8b](https://linux-hardware.org/?probe=1626648a8b) | Jun 13, 2023 |
| LincPlus      | LINNCPLUS P1                | [878dc2b05f](https://linux-hardware.org/?probe=878dc2b05f) | Jun 13, 2023 |
| Medion        | E7424 MD60150               | [c8d6acdb6f](https://linux-hardware.org/?probe=c8d6acdb6f) | Jun 13, 2023 |
| Medion        | Akoya P6656 MD99615         | [f6956c6b6c](https://linux-hardware.org/?probe=f6956c6b6c) | Jun 13, 2023 |
| Medion        | E7424 MD60150               | [9f4ec54afd](https://linux-hardware.org/?probe=9f4ec54afd) | Jun 13, 2023 |
| HP            | Laptop 15s-eq2xxx           | [20c6793733](https://linux-hardware.org/?probe=20c6793733) | Jun 13, 2023 |
| Schenker      | VIA 15 Pro                  | [311a7e116c](https://linux-hardware.org/?probe=311a7e116c) | Jun 13, 2023 |
| HP            | Pavilion 17                 | [54eb1dbd1c](https://linux-hardware.org/?probe=54eb1dbd1c) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3f3cbfd7fe](https://linux-hardware.org/?probe=3f3cbfd7fe) | Jun 12, 2023 |
| Acer          | Aspire F5-573G              | [c85f08223b](https://linux-hardware.org/?probe=c85f08223b) | Jun 12, 2023 |
| TUXEDO        | Unknown                     | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [4df7edf5e2](https://linux-hardware.org/?probe=4df7edf5e2) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | [a4c87fb2bc](https://linux-hardware.org/?probe=a4c87fb2bc) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a6d7a1885](https://linux-hardware.org/?probe=7a6d7a1885) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | [2069778d1f](https://linux-hardware.org/?probe=2069778d1f) | Jun 12, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [f3dae81611](https://linux-hardware.org/?probe=f3dae81611) | Jun 12, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [f19d062310](https://linux-hardware.org/?probe=f19d062310) | Jun 12, 2023 |
| Dell          | Latitude 7430               | [6a01453dfa](https://linux-hardware.org/?probe=6a01453dfa) | Jun 12, 2023 |
| Hampoo        | Cherry Trail CR V200        | [d2ee0bc234](https://linux-hardware.org/?probe=d2ee0bc234) | Jun 12, 2023 |
| Dell          | Latitude E6510              | [f3e9e3bbf1](https://linux-hardware.org/?probe=f3e9e3bbf1) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9a4af7d5c3](https://linux-hardware.org/?probe=9a4af7d5c3) | Jun 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [d2c4574d58](https://linux-hardware.org/?probe=d2c4574d58) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | [352eaf6ce7](https://linux-hardware.org/?probe=352eaf6ce7) | Jun 11, 2023 |
| Acer          | Aspire A317-33              | [f62e645bd3](https://linux-hardware.org/?probe=f62e645bd3) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | [673ab1f0a9](https://linux-hardware.org/?probe=673ab1f0a9) | Jun 11, 2023 |
| Valve         | Jupiter                     | [fc47f86c91](https://linux-hardware.org/?probe=fc47f86c91) | Jun 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| HP            | EliteBook 1040 G4           | [98aa06475b](https://linux-hardware.org/?probe=98aa06475b) | Jun 10, 2023 |
| Apple         | MacBookPro11,3              | [b7dfbae839](https://linux-hardware.org/?probe=b7dfbae839) | Jun 10, 2023 |
| Dell          | Latitude E6510              | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| HP            | Laptop 17-by3xxx            | [421ff52b0b](https://linux-hardware.org/?probe=421ff52b0b) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f7a2bd2ca8](https://linux-hardware.org/?probe=f7a2bd2ca8) | Jun 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [65a47406b0](https://linux-hardware.org/?probe=65a47406b0) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [b2f7d876c7](https://linux-hardware.org/?probe=b2f7d876c7) | Jun 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| HP            | ZBook 15 G2                 | [68c941fe5d](https://linux-hardware.org/?probe=68c941fe5d) | Jun 10, 2023 |
| HP            | EliteBook 840 G2            | [770045a9fc](https://linux-hardware.org/?probe=770045a9fc) | Jun 10, 2023 |
| HP            | ZBook 15 G2                 | [2851b41659](https://linux-hardware.org/?probe=2851b41659) | Jun 09, 2023 |
| HP            | Laptop 17-bs0xx             | [c93d52343c](https://linux-hardware.org/?probe=c93d52343c) | Jun 09, 2023 |
| Google        | Akali 360                   | [1f7d5f8bc5](https://linux-hardware.org/?probe=1f7d5f8bc5) | Jun 09, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [849dbace60](https://linux-hardware.org/?probe=849dbace60) | Jun 09, 2023 |
| Dell          | Latitude E7470              | [c5457da74f](https://linux-hardware.org/?probe=c5457da74f) | Jun 09, 2023 |
| Dell          | Precision M4600             | [a79a783515](https://linux-hardware.org/?probe=a79a783515) | Jun 09, 2023 |
| Acer          | TravelMate P215-53          | [9536bf547a](https://linux-hardware.org/?probe=9536bf547a) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E754               | [4d09f42447](https://linux-hardware.org/?probe=4d09f42447) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [ab35c95b72](https://linux-hardware.org/?probe=ab35c95b72) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [531e3f124d](https://linux-hardware.org/?probe=531e3f124d) | Jun 09, 2023 |
| HP            | EliteBook Folio 9470m       | [5739bbf07f](https://linux-hardware.org/?probe=5739bbf07f) | Jun 08, 2023 |
| HP            | EliteBook Folio 9470m       | [74dd8ef72a](https://linux-hardware.org/?probe=74dd8ef72a) | Jun 08, 2023 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [4c8d8758b7](https://linux-hardware.org/?probe=4c8d8758b7) | Jun 08, 2023 |
| Lenovo        | ThinkPad X280 20KES5SE22    | [c25a510191](https://linux-hardware.org/?probe=c25a510191) | Jun 08, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | [e6cb646bd4](https://linux-hardware.org/?probe=e6cb646bd4) | Jun 08, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [0aea375d78](https://linux-hardware.org/?probe=0aea375d78) | Jun 08, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3f04b950e8](https://linux-hardware.org/?probe=3f04b950e8) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7543a0bbc1](https://linux-hardware.org/?probe=7543a0bbc1) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444C... | [4e5e1d4052](https://linux-hardware.org/?probe=4e5e1d4052) | Jun 08, 2023 |
| HP            | Pavilion dv7                | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [06608c68d7](https://linux-hardware.org/?probe=06608c68d7) | Jun 07, 2023 |
| Apple         | MacBookPro11,1              | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [490ae0bc1c](https://linux-hardware.org/?probe=490ae0bc1c) | Jun 07, 2023 |
| ASUSTek       | X200MA                      | [7c0552ad30](https://linux-hardware.org/?probe=7c0552ad30) | Jun 06, 2023 |
| Dell          | Precision 5510              | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| Acer          | Aspire V5-572P              | [cdb5005799](https://linux-hardware.org/?probe=cdb5005799) | Jun 06, 2023 |
| Acer          | Aspire V5-572P              | [49745927a0](https://linux-hardware.org/?probe=49745927a0) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| Acer          | Aspire A517-53              | [a039ca0054](https://linux-hardware.org/?probe=a039ca0054) | Jun 05, 2023 |
| TUXEDO        | N8xEJEK                     | [28ca72e1e1](https://linux-hardware.org/?probe=28ca72e1e1) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X250 20CLS02K00    | [fc306205a7](https://linux-hardware.org/?probe=fc306205a7) | Jun 05, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | [55abece90c](https://linux-hardware.org/?probe=55abece90c) | Jun 05, 2023 |
| Acer          | Aspire ES1-571              | [ed19db3614](https://linux-hardware.org/?probe=ed19db3614) | Jun 05, 2023 |
| HP            | Notebook                    | [1605419ae0](https://linux-hardware.org/?probe=1605419ae0) | Jun 05, 2023 |
| HP            | Laptop 17-cp0xxx            | [b142b6de06](https://linux-hardware.org/?probe=b142b6de06) | Jun 05, 2023 |
| Dell          | Latitude E6510              | [49743c8db7](https://linux-hardware.org/?probe=49743c8db7) | Jun 04, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5540              | [d2bde0e098](https://linux-hardware.org/?probe=d2bde0e098) | Jun 04, 2023 |
| Dell          | Latitude E5540              | [f9483c219e](https://linux-hardware.org/?probe=f9483c219e) | Jun 04, 2023 |
| Dell          | Latitude E6510              | [51c45b0aa7](https://linux-hardware.org/?probe=51c45b0aa7) | Jun 04, 2023 |
| Acer          | Aspire 3820                 | [edbf91844a](https://linux-hardware.org/?probe=edbf91844a) | Jun 04, 2023 |
| Sony          | VPCEH2H4E                   | [793e883d0c](https://linux-hardware.org/?probe=793e883d0c) | Jun 04, 2023 |
| HP            | EliteBook 840 G3            | [7c35e9a268](https://linux-hardware.org/?probe=7c35e9a268) | Jun 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | [4d9e4fb129](https://linux-hardware.org/?probe=4d9e4fb129) | Jun 04, 2023 |
| Dell          | Latitude E5440              | [02b3462a2c](https://linux-hardware.org/?probe=02b3462a2c) | Jun 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| Acer          | Swift SF316-51              | [4ba1405836](https://linux-hardware.org/?probe=4ba1405836) | Jun 04, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [2eeb67613f](https://linux-hardware.org/?probe=2eeb67613f) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [0935f74d34](https://linux-hardware.org/?probe=0935f74d34) | Jun 04, 2023 |
| Clevo         | M670SRU                     | [e163d57d56](https://linux-hardware.org/?probe=e163d57d56) | Jun 04, 2023 |
| MSI           | U200                        | [01900b8117](https://linux-hardware.org/?probe=01900b8117) | Jun 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [7179829c20](https://linux-hardware.org/?probe=7179829c20) | Jun 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [038871f5be](https://linux-hardware.org/?probe=038871f5be) | Jun 04, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c16266c1c9](https://linux-hardware.org/?probe=c16266c1c9) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| Acer          | Aspire 5738                 | [138d22e03e](https://linux-hardware.org/?probe=138d22e03e) | Jun 04, 2023 |
| Toshiba       | TECRA Z40-C                 | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [a10a42a44d](https://linux-hardware.org/?probe=a10a42a44d) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [e58b2a1237](https://linux-hardware.org/?probe=e58b2a1237) | Jun 04, 2023 |
| Pegatron      | Spring Peak                 | [ce54d0192d](https://linux-hardware.org/?probe=ce54d0192d) | Jun 04, 2023 |
| ASUSTek       | K52Je                       | [0190eef08c](https://linux-hardware.org/?probe=0190eef08c) | Jun 03, 2023 |
| Gigabyte      | G5 GE                       | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| ASUSTek       | X540SA                      | [e9e8995d2e](https://linux-hardware.org/?probe=e9e8995d2e) | Jun 03, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| Chuwi         | GemiBook Pro                | [772d1f8765](https://linux-hardware.org/?probe=772d1f8765) | Jun 03, 2023 |
| Acer          | Aspire V3-372               | [1200863830](https://linux-hardware.org/?probe=1200863830) | Jun 03, 2023 |
| ASUSTek       | K52Je                       | [c6f78ba2aa](https://linux-hardware.org/?probe=c6f78ba2aa) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [41e5c1790c](https://linux-hardware.org/?probe=41e5c1790c) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [d583c74274](https://linux-hardware.org/?probe=d583c74274) | Jun 03, 2023 |
| Acer          | Aspire AV15-51              | [7ed9ba7165](https://linux-hardware.org/?probe=7ed9ba7165) | Jun 03, 2023 |
| Toshiba       | Satellite L50-C             | [7b1b547b11](https://linux-hardware.org/?probe=7b1b547b11) | Jun 03, 2023 |
| Acer          | Aspire 7745G                | [135ce50995](https://linux-hardware.org/?probe=135ce50995) | Jun 03, 2023 |
| Dell          | G15 5520                    | [b77b760dfe](https://linux-hardware.org/?probe=b77b760dfe) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Notebook                    | [9b12c54cf2](https://linux-hardware.org/?probe=9b12c54cf2) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | [160d4525c6](https://linux-hardware.org/?probe=160d4525c6) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2a67b74a26](https://linux-hardware.org/?probe=2a67b74a26) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [9bf36ef4a5](https://linux-hardware.org/?probe=9bf36ef4a5) | Jun 02, 2023 |
| MSI           | U200                        | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | [f576f54ff2](https://linux-hardware.org/?probe=f576f54ff2) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | [e94cab5008](https://linux-hardware.org/?probe=e94cab5008) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1aea71b6c0](https://linux-hardware.org/?probe=1aea71b6c0) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1bdb74a8ba](https://linux-hardware.org/?probe=1bdb74a8ba) | Jun 02, 2023 |
| HP            | G62                         | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Dell          | Latitude 5540               | [98ec8ec8bf](https://linux-hardware.org/?probe=98ec8ec8bf) | Jun 01, 2023 |
| Acer          | Predator PH517-51           | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [97b54068b7](https://linux-hardware.org/?probe=97b54068b7) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| Dell          | Vostro 7590                 | [d9bfa42b63](https://linux-hardware.org/?probe=d9bfa42b63) | Jun 01, 2023 |
| Packard Be... | EasyNote TK11BZ             | [b1cbe3b6a6](https://linux-hardware.org/?probe=b1cbe3b6a6) | Jun 01, 2023 |
| HP            | ProBook 6450b               | [d3d4e45f9d](https://linux-hardware.org/?probe=d3d4e45f9d) | Jun 01, 2023 |
| ASUSTek       | K53SK                       | [9b376cdd45](https://linux-hardware.org/?probe=9b376cdd45) | Jun 01, 2023 |
| Apple         | MacBook4,1                  | [996b318420](https://linux-hardware.org/?probe=996b318420) | Jun 01, 2023 |
| Dell          | Latitude E6400              | [efe855c429](https://linux-hardware.org/?probe=efe855c429) | May 31, 2023 |
| Dell          | Latitude E6400              | [c56e8318db](https://linux-hardware.org/?probe=c56e8318db) | May 31, 2023 |
| ASUSTek       | K53SK                       | [39c63c5bd1](https://linux-hardware.org/?probe=39c63c5bd1) | May 31, 2023 |
| Lenovo        | V17 G3 IAP 82U1             | [1be071e25d](https://linux-hardware.org/?probe=1be071e25d) | May 31, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [2bb50cdcc7](https://linux-hardware.org/?probe=2bb50cdcc7) | May 31, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Fujitsu       | LIFEBOOK E780               | [8459f7cfee](https://linux-hardware.org/?probe=8459f7cfee) | May 31, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| Dell          | Precision 3550              | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [0ead50ad49](https://linux-hardware.org/?probe=0ead50ad49) | May 31, 2023 |
| ASUSTek       | K53SK                       | [bfd926c8da](https://linux-hardware.org/?probe=bfd926c8da) | May 30, 2023 |
| VALE          | Notebook Classic C140       | [cdc6168586](https://linux-hardware.org/?probe=cdc6168586) | May 30, 2023 |
| Acer          | Aspire 5749                 | [3bca2af88d](https://linux-hardware.org/?probe=3bca2af88d) | May 30, 2023 |
| Acer          | Predator PH517-51           | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [048a3a0f30](https://linux-hardware.org/?probe=048a3a0f30) | May 29, 2023 |
| Fujitsu       | LIFEBOOK E780               | [aac95cf765](https://linux-hardware.org/?probe=aac95cf765) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9fce8d1e40](https://linux-hardware.org/?probe=9fce8d1e40) | May 29, 2023 |
| Acer          | Aspire A315-51              | [d6f1c2bdbd](https://linux-hardware.org/?probe=d6f1c2bdbd) | May 29, 2023 |
| Acer          | Aspire ES1-571              | [6f75ba50c1](https://linux-hardware.org/?probe=6f75ba50c1) | May 29, 2023 |
| Apple         | MacBookPro14,1              | [a5785cf3c3](https://linux-hardware.org/?probe=a5785cf3c3) | May 29, 2023 |
| Samsung       | 600B4B/600B5B               | [feba5017b3](https://linux-hardware.org/?probe=feba5017b3) | May 29, 2023 |
| Dell          | XPS 13 9310                 | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| HP            | EliteBook 735 G6            | [18b33e6fc7](https://linux-hardware.org/?probe=18b33e6fc7) | May 29, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Fujitsu       | CELSIUS H720                | [d7d19435c2](https://linux-hardware.org/?probe=d7d19435c2) | May 29, 2023 |
| Acer          | Nitro AN515-52              | [b90162f812](https://linux-hardware.org/?probe=b90162f812) | May 29, 2023 |
| HP            | Laptop 17-cp0xxx            | [5ac36928a5](https://linux-hardware.org/?probe=5ac36928a5) | May 28, 2023 |
| ALLDOCUBE     | i1405C                      | [7e4475ef13](https://linux-hardware.org/?probe=7e4475ef13) | May 28, 2023 |
| Acer          | Swift SF114-34              | [ec48f7a207](https://linux-hardware.org/?probe=ec48f7a207) | May 28, 2023 |
| Dell          | Inspiron 7559               | [af1bb009ca](https://linux-hardware.org/?probe=af1bb009ca) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d5a3141562](https://linux-hardware.org/?probe=d5a3141562) | May 28, 2023 |
| Lenovo        | V130-15IKB 81HN             | [e50700f8be](https://linux-hardware.org/?probe=e50700f8be) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Acer          | Aspire ES1-571              | [a3da42e0e9](https://linux-hardware.org/?probe=a3da42e0e9) | May 28, 2023 |
| TUXEDO        | Unknown                     | [21be23e012](https://linux-hardware.org/?probe=21be23e012) | May 28, 2023 |
| Apple         | MacBookAir7,2               | [f75fb35204](https://linux-hardware.org/?probe=f75fb35204) | May 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [618a907425](https://linux-hardware.org/?probe=618a907425) | May 27, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [ef1ea73723](https://linux-hardware.org/?probe=ef1ea73723) | May 27, 2023 |
| Acer          | TravelMate 5735Z            | [9eea76e3ee](https://linux-hardware.org/?probe=9eea76e3ee) | May 27, 2023 |
| Lenovo        | G50-70 20351                | [ee0a9f666c](https://linux-hardware.org/?probe=ee0a9f666c) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | EliteBook 840 G2            | [519e04a228](https://linux-hardware.org/?probe=519e04a228) | May 27, 2023 |
| Acer          | Aspire ES1-571              | [029ea88e3b](https://linux-hardware.org/?probe=029ea88e3b) | May 27, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [9984b363d1](https://linux-hardware.org/?probe=9984b363d1) | May 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [737d3fe7fb](https://linux-hardware.org/?probe=737d3fe7fb) | May 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [d5d9543a5a](https://linux-hardware.org/?probe=d5d9543a5a) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [16ee98f9cc](https://linux-hardware.org/?probe=16ee98f9cc) | May 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [39cf075935](https://linux-hardware.org/?probe=39cf075935) | May 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90058G... | [71a2e90192](https://linux-hardware.org/?probe=71a2e90192) | May 26, 2023 |
| ASUSTek       | K53SV                       | [357c1fd091](https://linux-hardware.org/?probe=357c1fd091) | May 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [852932c13b](https://linux-hardware.org/?probe=852932c13b) | May 26, 2023 |
| ASUSTek       | K52Je                       | [3b40aeae90](https://linux-hardware.org/?probe=3b40aeae90) | May 26, 2023 |
| Dell          | Latitude E6330              | [e7477af1a5](https://linux-hardware.org/?probe=e7477af1a5) | May 26, 2023 |
| Dell          | Precision 5530              | [702b4d7914](https://linux-hardware.org/?probe=702b4d7914) | May 26, 2023 |
| Dell          | Latitude E6510              | [9edaeb2ffa](https://linux-hardware.org/?probe=9edaeb2ffa) | May 25, 2023 |
| HP            | 250 G7 Notebook PC          | [2f0f83bda2](https://linux-hardware.org/?probe=2f0f83bda2) | May 25, 2023 |
| ASUSTek       | X705UVR                     | [bedbf77e16](https://linux-hardware.org/?probe=bedbf77e16) | May 25, 2023 |
| Sony          | SVF1521B4E                  | [d6eaf68ef4](https://linux-hardware.org/?probe=d6eaf68ef4) | May 25, 2023 |
| Sony          | SVF1521B4E                  | [03c5deb4cc](https://linux-hardware.org/?probe=03c5deb4cc) | May 25, 2023 |
| Acer          | Aspire V3-371               | [f9200e891b](https://linux-hardware.org/?probe=f9200e891b) | May 25, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | [48ad025649](https://linux-hardware.org/?probe=48ad025649) | May 25, 2023 |
| Google        | Akali 360                   | [2a4bbc5d81](https://linux-hardware.org/?probe=2a4bbc5d81) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| Dell          | Latitude E6430              | [37dab72e8c](https://linux-hardware.org/?probe=37dab72e8c) | May 25, 2023 |
| Lenovo        | ThinkPad T440p 20AW0045M... | [355e03f684](https://linux-hardware.org/?probe=355e03f684) | May 25, 2023 |
| Fujitsu       | LIFEBOOK E752               | [0c7493d8d3](https://linux-hardware.org/?probe=0c7493d8d3) | May 24, 2023 |
| Lenovo        | IdeaPad Y560                | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | 255 G7 Notebook PC          | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Lenovo        | G50-70 20351                | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| Apple         | MacBookPro6,2               | [6858db4f73](https://linux-hardware.org/?probe=6858db4f73) | May 24, 2023 |
| Dell          | Precision 5570              | [f014c35d45](https://linux-hardware.org/?probe=f014c35d45) | May 24, 2023 |
| Lenovo        | ThinkPad T410 2537AT1       | [babbb757c6](https://linux-hardware.org/?probe=babbb757c6) | May 24, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [520e3d90a6](https://linux-hardware.org/?probe=520e3d90a6) | May 24, 2023 |
| ASUSTek       | K73BR                       | [2b59c4c84c](https://linux-hardware.org/?probe=2b59c4c84c) | May 24, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [306ecade71](https://linux-hardware.org/?probe=306ecade71) | May 24, 2023 |
| Valve         | Jupiter                     | [fd4190f3d7](https://linux-hardware.org/?probe=fd4190f3d7) | May 24, 2023 |
| PC Special... | NH5x_7xDPx                  | [4d4ce3a2bc](https://linux-hardware.org/?probe=4d4ce3a2bc) | May 23, 2023 |
| Dell          | Inspiron 3593               | [715800f05d](https://linux-hardware.org/?probe=715800f05d) | May 23, 2023 |
| Toshiba       | Satellite C660D             | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| Dell          | Latitude E6510              | [731befae67](https://linux-hardware.org/?probe=731befae67) | May 23, 2023 |
| Lenovo        | ThinkPad E460 20ETCTO1WW    | [cd2c3fbd45](https://linux-hardware.org/?probe=cd2c3fbd45) | May 23, 2023 |
| ASUSTek       | X751MA                      | [674b64f381](https://linux-hardware.org/?probe=674b64f381) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e1c91c725](https://linux-hardware.org/?probe=6e1c91c725) | May 23, 2023 |
| Matsushita... | CF-W7BWAYZL3                | [a00f38be95](https://linux-hardware.org/?probe=a00f38be95) | May 23, 2023 |
| Lenovo        | ThinkPad W500 40626NG       | [9466f83af8](https://linux-hardware.org/?probe=9466f83af8) | May 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| Dell          | Latitude 7490               | [f689b559e8](https://linux-hardware.org/?probe=f689b559e8) | May 22, 2023 |
| Acer          | Aspire V3-371               | [c6276aaa0c](https://linux-hardware.org/?probe=c6276aaa0c) | May 22, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [03e6dd8808](https://linux-hardware.org/?probe=03e6dd8808) | May 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f25279745a](https://linux-hardware.org/?probe=f25279745a) | May 22, 2023 |
| Apple         | MacBookPro8,1               | [5b78800649](https://linux-hardware.org/?probe=5b78800649) | May 22, 2023 |
| Acer          | Aspire A315-43              | [926421c6be](https://linux-hardware.org/?probe=926421c6be) | May 22, 2023 |
| Apple         | MacBookPro8,1               | [a78ee7457a](https://linux-hardware.org/?probe=a78ee7457a) | May 22, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [7cba5b3595](https://linux-hardware.org/?probe=7cba5b3595) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| Framework     | Laptop                      | [7715f5f056](https://linux-hardware.org/?probe=7715f5f056) | May 22, 2023 |
| Lenovo        | ThinkPad X230 2325AC2       | [bc1633cf27](https://linux-hardware.org/?probe=bc1633cf27) | May 22, 2023 |
| HP            | Laptop 17-cp0xxx            | [0148c19bc7](https://linux-hardware.org/?probe=0148c19bc7) | May 22, 2023 |
| Acer          | TM8573T                     | [64df92ebbe](https://linux-hardware.org/?probe=64df92ebbe) | May 22, 2023 |
| HP            | Laptop 15s-eq2xxx           | [cccb529fd3](https://linux-hardware.org/?probe=cccb529fd3) | May 21, 2023 |
| Acer          | TM8573T                     | [2ea1f44eb8](https://linux-hardware.org/?probe=2ea1f44eb8) | May 21, 2023 |
| Apple         | MacBookPro14,2              | [d29f7a36f9](https://linux-hardware.org/?probe=d29f7a36f9) | May 21, 2023 |
| Acer          | Aspire A515-52G             | [a80648e2a4](https://linux-hardware.org/?probe=a80648e2a4) | May 21, 2023 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | [03afaf2468](https://linux-hardware.org/?probe=03afaf2468) | May 21, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0W90... | [0b3265b088](https://linux-hardware.org/?probe=0b3265b088) | May 21, 2023 |
| Fujitsu       | LIFEBOOK S752               | [906ba8b65c](https://linux-hardware.org/?probe=906ba8b65c) | May 21, 2023 |
| Acer          | Aspire V5-572P              | [99f4730d26](https://linux-hardware.org/?probe=99f4730d26) | May 21, 2023 |
| Sony          | SVF1521B4E                  | [89c04d3b34](https://linux-hardware.org/?probe=89c04d3b34) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| Dell          | G3 3500                     | [cbe9c2f010](https://linux-hardware.org/?probe=cbe9c2f010) | May 21, 2023 |
| Lenovo        | Y50-70 20378                | [2aff70d7c9](https://linux-hardware.org/?probe=2aff70d7c9) | May 21, 2023 |
| Acer          | E1-510                      | [709c32e016](https://linux-hardware.org/?probe=709c32e016) | May 21, 2023 |
| Acer          | E1-510                      | [c18f4ac56b](https://linux-hardware.org/?probe=c18f4ac56b) | May 21, 2023 |
| Acer          | Aspire V5-572P              | [456d6c8887](https://linux-hardware.org/?probe=456d6c8887) | May 21, 2023 |
| MICROBYTE     | ezbook                      | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [157b535164](https://linux-hardware.org/?probe=157b535164) | May 20, 2023 |
| Acer          | Aspire S3                   | [b6841c9aeb](https://linux-hardware.org/?probe=b6841c9aeb) | May 20, 2023 |
| Acer          | Aspire 5739G                | [23a84a79ed](https://linux-hardware.org/?probe=23a84a79ed) | May 20, 2023 |
| Acer          | Aspire S3                   | [3fafb0df5d](https://linux-hardware.org/?probe=3fafb0df5d) | May 20, 2023 |
| Dell          | Latitude 5285               | [0db3cfd34e](https://linux-hardware.org/?probe=0db3cfd34e) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| Dell          | Latitude E6510              | [342b8d094e](https://linux-hardware.org/?probe=342b8d094e) | May 20, 2023 |
| HP            | Pavilion dv6                | [17ac43247a](https://linux-hardware.org/?probe=17ac43247a) | May 20, 2023 |
| Acer          | Aspire 5739G                | [2ae6c83437](https://linux-hardware.org/?probe=2ae6c83437) | May 20, 2023 |
| Dell          | Latitude E6510              | [4d606396f8](https://linux-hardware.org/?probe=4d606396f8) | May 20, 2023 |
| Packard Be... | EasyNote MH36               | [a77cfa4947](https://linux-hardware.org/?probe=a77cfa4947) | May 20, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | [87e70e9606](https://linux-hardware.org/?probe=87e70e9606) | May 19, 2023 |
| HP            | Notebook                    | [3664846c35](https://linux-hardware.org/?probe=3664846c35) | May 19, 2023 |
| Lenovo        | ThinkPad T61 6463B45        | [a2445821f3](https://linux-hardware.org/?probe=a2445821f3) | May 19, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [c0e3ea54c0](https://linux-hardware.org/?probe=c0e3ea54c0) | May 19, 2023 |
| Dell          | Latitude E5430 non-vPro     | [6d6cdfc735](https://linux-hardware.org/?probe=6d6cdfc735) | May 19, 2023 |
| Apple         | MacBookPro11,3              | [3de00073ba](https://linux-hardware.org/?probe=3de00073ba) | May 19, 2023 |
| Dell          | Latitude 5411               | [8929285bca](https://linux-hardware.org/?probe=8929285bca) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [749d31d44a](https://linux-hardware.org/?probe=749d31d44a) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [85da505294](https://linux-hardware.org/?probe=85da505294) | May 19, 2023 |
| HP            | 15                          | [a22d3981e2](https://linux-hardware.org/?probe=a22d3981e2) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| HP            | Pavilion dv6                | [4fb1281981](https://linux-hardware.org/?probe=4fb1281981) | May 18, 2023 |
| Lenovo        | ThinkPad X200s 7470WUB      | [e5ad235f60](https://linux-hardware.org/?probe=e5ad235f60) | May 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Dell          | Latitude E6500              | [27213adbe8](https://linux-hardware.org/?probe=27213adbe8) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [6141537b7b](https://linux-hardware.org/?probe=6141537b7b) | May 18, 2023 |
| HP            | Laptop 14s-dq0xxx           | [6173aa2164](https://linux-hardware.org/?probe=6173aa2164) | May 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [25e9a17dd0](https://linux-hardware.org/?probe=25e9a17dd0) | May 18, 2023 |
| Dell          | XPS 13 9305                 | [3eb1bee421](https://linux-hardware.org/?probe=3eb1bee421) | May 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [eb15dc415d](https://linux-hardware.org/?probe=eb15dc415d) | May 18, 2023 |
| HUAWEI        | HVY-WXX9                    | [b30078ae71](https://linux-hardware.org/?probe=b30078ae71) | May 18, 2023 |
| HP            | 630                         | [bd7bdf5942](https://linux-hardware.org/?probe=bd7bdf5942) | May 18, 2023 |
| Sony          | VPCEB4Z1E                   | [d1cca131ad](https://linux-hardware.org/?probe=d1cca131ad) | May 18, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d3bfab996e](https://linux-hardware.org/?probe=d3bfab996e) | May 18, 2023 |
| Dell          | Latitude E7240              | [208261238e](https://linux-hardware.org/?probe=208261238e) | May 18, 2023 |
| Dell          | Latitude E7240              | [faf148036f](https://linux-hardware.org/?probe=faf148036f) | May 18, 2023 |
| Medion        | E6232                       | [a447a0aba0](https://linux-hardware.org/?probe=a447a0aba0) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [a23a2d1c6c](https://linux-hardware.org/?probe=a23a2d1c6c) | May 18, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [aa625a94a0](https://linux-hardware.org/?probe=aa625a94a0) | May 18, 2023 |
| Valve         | Jupiter                     | [c16624e321](https://linux-hardware.org/?probe=c16624e321) | May 17, 2023 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | [66f184855c](https://linux-hardware.org/?probe=66f184855c) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [4aadc89f41](https://linux-hardware.org/?probe=4aadc89f41) | May 17, 2023 |
| HP            | Laptop 14s-dq0xxx           | [0a08d453f7](https://linux-hardware.org/?probe=0a08d453f7) | May 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | [ad17e04f3b](https://linux-hardware.org/?probe=ad17e04f3b) | May 17, 2023 |
| Dell          | Latitude E7270              | [c3b39e55f4](https://linux-hardware.org/?probe=c3b39e55f4) | May 17, 2023 |
| Apple         | MacBookPro12,1              | [8aef05613d](https://linux-hardware.org/?probe=8aef05613d) | May 17, 2023 |
| Dell          | Latitude 7430               | [eb576d7c2a](https://linux-hardware.org/?probe=eb576d7c2a) | May 17, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [f31be9149e](https://linux-hardware.org/?probe=f31be9149e) | May 17, 2023 |
| Dell          | XPS 13 7390                 | [51ff9a820a](https://linux-hardware.org/?probe=51ff9a820a) | May 16, 2023 |
| Dell          | XPS 13 7390                 | [e98b404c17](https://linux-hardware.org/?probe=e98b404c17) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | [1d5a340968](https://linux-hardware.org/?probe=1d5a340968) | May 16, 2023 |
| Dell          | Latitude 7430               | [d137c2d73b](https://linux-hardware.org/?probe=d137c2d73b) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c62b63f5bf](https://linux-hardware.org/?probe=c62b63f5bf) | May 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [24cb48f7d7](https://linux-hardware.org/?probe=24cb48f7d7) | May 16, 2023 |
| Acer          | Swift SFA16-41              | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [58b895e713](https://linux-hardware.org/?probe=58b895e713) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | [040fb99c20](https://linux-hardware.org/?probe=040fb99c20) | May 15, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [19feb08b89](https://linux-hardware.org/?probe=19feb08b89) | May 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 1408      | 12.75%  |
| Ubuntu 18.04                 | 645       | 5.84%   |
| Ubuntu 22.04                 | 571       | 5.17%   |
| Linux Mint 20.3              | 307       | 2.78%   |
| Linux Mint 20.2              | 303       | 2.74%   |
| Debian 11                    | 285       | 2.58%   |
| OpenMandriva 4.2             | 255       | 2.31%   |
| Linux Mint 21.1              | 252       | 2.28%   |
| OpenMandriva 4.3             | 244       | 2.21%   |
| Linux Mint 20.1              | 201       | 1.82%   |
| Manjaro                      | 182       | 1.65%   |
| Zorin 16                     | 177       | 1.6%    |
| Linux Mint 20                | 176       | 1.59%   |
| Arch Rolling                 | 174       | 1.58%   |
| Ubuntu 21.10                 | 162       | 1.47%   |
| Ubuntu 20.10                 | 160       | 1.45%   |
| Linux Mint 19.3              | 158       | 1.43%   |
| Arch                         | 146       | 1.32%   |
| Xubuntu 20.04                | 139       | 1.26%   |
| KDE neon 20.04               | 118       | 1.07%   |
| Ubuntu 22.10                 | 114       | 1.03%   |
| Linux Mint 21                | 114       | 1.03%   |
| Ubuntu 19.10                 | 112       | 1.01%   |
| Pop!_OS 22.04                | 109       | 0.99%   |
| Ubuntu 19.04                 | 102       | 0.92%   |
| Ubuntu 21.04                 | 99        | 0.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 98        | 0.89%   |
| Fedora 37                    | 92        | 0.83%   |
| OpenMandriva 23.03           | 90        | 0.81%   |
| OpenMandriva 23.01           | 86        | 0.78%   |
| Fedora 38                    | 86        | 0.78%   |
| Fedora 36                    | 86        | 0.78%   |
| BlackPanther 18.1            | 84        | 0.76%   |
| ArcoLinux Rolling            | 80        | 0.72%   |
| Debian 10                    | 78        | 0.71%   |
| Fedora 33                    | 72        | 0.65%   |
| Pop!_OS 20.10                | 67        | 0.61%   |
| Kubuntu 20.04                | 66        | 0.6%    |
| Zorin 15                     | 65        | 0.59%   |
| Xubuntu 18.04                | 65        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 3308      | 31.89%  |
| Linux Mint    | 1553      | 14.97%  |
| OpenMandriva  | 719       | 6.93%   |
| Debian        | 513       | 4.95%   |
| Fedora        | 492       | 4.74%   |
| Manjaro       | 418       | 4.03%   |
| Arch          | 315       | 3.04%   |
| Pop!_OS       | 312       | 3.01%   |
| Xubuntu       | 292       | 2.82%   |
| Zorin         | 254       | 2.45%   |
| Kubuntu       | 238       | 2.29%   |
| ROSA          | 187       | 1.8%    |
| openSUSE      | 180       | 1.74%   |
| KDE neon      | 164       | 1.58%   |
| Endless       | 105       | 1.01%   |
| Elementary    | 105       | 1.01%   |
| BlackPanther  | 93        | 0.9%    |
| SteamOS       | 89        | 0.86%   |
| ArcoLinux     | 88        | 0.85%   |
| Gentoo        | 86        | 0.83%   |
| Ubuntu MATE   | 85        | 0.82%   |
| Kali          | 72        | 0.69%   |
| LMDE          | 66        | 0.64%   |
| Ubuntu Budgie | 65        | 0.63%   |
| Lubuntu       | 58        | 0.56%   |
| Ubuntu Unity  | 53        | 0.51%   |
| EndeavourOS   | 47        | 0.45%   |
| MX            | 42        | 0.4%    |
| TUXEDO OS     | 32        | 0.31%   |
| Garuda Linux  | 26        | 0.25%   |
| Clear Linux   | 25        | 0.24%   |
| Parrot        | 19        | 0.18%   |
| Peppermint    | 18        | 0.17%   |
| CentOS        | 18        | 0.17%   |
| Xero          | 15        | 0.14%   |
| Nobara        | 14        | 0.13%   |
| LinuxFX       | 12        | 0.12%   |
| Void Linux    | 11        | 0.11%   |
| Deepin        | 11        | 0.11%   |
| Devuan        | 10        | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 245       | 1.99%   |
| 5.16.7-desktop-1omv4003  | 226       | 1.84%   |
| 5.4.0-42-generic         | 157       | 1.28%   |
| 5.15.0-56-generic        | 152       | 1.23%   |
| 5.4.0-58-generic         | 120       | 0.97%   |
| 5.15.0-58-generic        | 110       | 0.89%   |
| 5.4.0-91-generic         | 105       | 0.85%   |
| 5.4.0-48-generic         | 93        | 0.76%   |
| 5.4.0-52-generic         | 90        | 0.73%   |
| 6.2.6-desktop-1omv2390   | 87        | 0.71%   |
| 6.1.1-desktop-1omv2290   | 80        | 0.65%   |
| 5.15.0-52-generic        | 79        | 0.64%   |
| 5.15.0-46-generic        | 79        | 0.64%   |
| 5.15.0-60-generic        | 73        | 0.59%   |
| 5.8.0-43-generic         | 67        | 0.54%   |
| 5.4.0-26-generic         | 64        | 0.52%   |
| 5.19.0-35-generic        | 64        | 0.52%   |
| 5.15.0-48-generic        | 64        | 0.52%   |
| 5.13.0-39-generic        | 61        | 0.5%    |
| 5.13.0-28-generic        | 60        | 0.49%   |
| 5.11.0-38-generic        | 60        | 0.49%   |
| 5.4.0-56-generic         | 59        | 0.48%   |
| 5.4.0-74-generic         | 58        | 0.47%   |
| 5.4.0-72-generic         | 58        | 0.47%   |
| 5.4.0-65-generic         | 58        | 0.47%   |
| 5.11.0-27-generic        | 58        | 0.47%   |
| 5.15.0-53-generic        | 57        | 0.46%   |
| 5.11.0-37-generic        | 57        | 0.46%   |
| 4.18.16-desktop-1bP      | 57        | 0.46%   |
| 5.4.0-54-generic         | 56        | 0.45%   |
| 5.11.0-40-generic        | 56        | 0.45%   |
| 5.4.0-33-generic         | 55        | 0.45%   |
| 5.4.0-29-generic         | 55        | 0.45%   |
| 5.15.0-47-generic        | 55        | 0.45%   |
| 5.15.0-67-generic        | 54        | 0.44%   |
| 5.4.0-40-generic         | 53        | 0.43%   |
| 5.3.0-40-generic         | 52        | 0.42%   |
| 5.4.0-47-generic         | 51        | 0.41%   |
| 5.3.0-28-generic         | 51        | 0.41%   |
| 5.4.0-90-generic         | 50        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 2099      | 18.47%  |
| 5.15.0  | 1152      | 10.13%  |
| 4.15.0  | 603       | 5.3%    |
| 5.8.0   | 598       | 5.26%   |
| 5.13.0  | 598       | 5.26%   |
| 5.11.0  | 584       | 5.14%   |
| 5.19.0  | 429       | 3.77%   |
| 5.3.0   | 388       | 3.41%   |
| 5.10.0  | 373       | 3.28%   |
| 5.0.0   | 250       | 2.2%    |
| 5.10.14 | 247       | 2.17%   |
| 5.16.7  | 229       | 2.01%   |
| 4.18.0  | 209       | 1.84%   |
| 6.2.6   | 119       | 1.05%   |
| 6.2.0   | 113       | 0.99%   |
| 6.1.0   | 100       | 0.88%   |
| 4.19.0  | 94        | 0.83%   |
| 6.1.1   | 92        | 0.81%   |
| 4.18.16 | 61        | 0.54%   |
| 6.0.0   | 52        | 0.46%   |
| 5.14.0  | 47        | 0.41%   |
| 4.9.20  | 36        | 0.32%   |
| 5.3.18  | 33        | 0.29%   |
| 5.18.0  | 33        | 0.29%   |
| 4.9.60  | 31        | 0.27%   |
| 5.17.5  | 30        | 0.26%   |
| 5.6.0   | 28        | 0.25%   |
| 4.4.0   | 28        | 0.25%   |
| 5.9.16  | 27        | 0.24%   |
| 5.6.14  | 27        | 0.24%   |
| 5.16.0  | 27        | 0.24%   |
| 5.14.21 | 25        | 0.22%   |
| 5.8.16  | 24        | 0.21%   |
| 6.0.12  | 23        | 0.2%    |
| 5.17.0  | 23        | 0.2%    |
| 6.3.8   | 22        | 0.19%   |
| 6.3.1   | 21        | 0.18%   |
| 6.2.11  | 21        | 0.18%   |
| 6.1.12  | 21        | 0.18%   |
| 5.17.1  | 20        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 2211      | 19.7%   |
| 5.15    | 1371      | 12.22%  |
| 5.10    | 781       | 6.96%   |
| 5.8     | 714       | 6.36%   |
| 5.13    | 674       | 6.01%   |
| 5.11    | 668       | 5.95%   |
| 4.15    | 607       | 5.41%   |
| 5.19    | 521       | 4.64%   |
| 5.3     | 458       | 4.08%   |
| 6.1     | 380       | 3.39%   |
| 5.16    | 355       | 3.16%   |
| 6.2     | 336       | 2.99%   |
| 4.18    | 279       | 2.49%   |
| 5.0     | 258       | 2.3%    |
| 6.0     | 193       | 1.72%   |
| 5.9     | 133       | 1.19%   |
| 4.9     | 128       | 1.14%   |
| 5.14    | 127       | 1.13%   |
| 6.3     | 123       | 1.1%    |
| 5.6     | 123       | 1.1%    |
| 4.19    | 118       | 1.05%   |
| 5.17    | 117       | 1.04%   |
| 5.18    | 111       | 0.99%   |
| 5.12    | 80        | 0.71%   |
| 5.7     | 71        | 0.63%   |
| 6.4     | 62        | 0.55%   |
| 5.5     | 52        | 0.46%   |
| 4.4     | 31        | 0.28%   |
| 5.1     | 25        | 0.22%   |
| 4.1     | 22        | 0.2%    |
| 4.13    | 19        | 0.17%   |
| 5.2     | 18        | 0.16%   |
| 4.12    | 16        | 0.14%   |
| 4.14    | 10        | 0.09%   |
| 4.20    | 7         | 0.06%   |
| 4.8     | 4         | 0.04%   |
| 4.17    | 4         | 0.04%   |
| 3.10    | 4         | 0.04%   |
| 4.11    | 3         | 0.03%   |
| 4.10    | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 9728      | 96.63%  |
| i686    | 330       | 3.28%   |
| aarch64 | 4         | 0.04%   |
| ppc     | 3         | 0.03%   |
| armv7l  | 2         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 4191      | 40.01%  |
| KDE5              | 1775      | 16.94%  |
| X-Cinnamon        | 1206      | 11.51%  |
| Unknown           | 1003      | 9.57%   |
| XFCE              | 865       | 8.26%   |
| MATE              | 325       | 3.1%    |
| KDE               | 228       | 2.18%   |
| Cinnamon          | 174       | 1.66%   |
| KDE4              | 106       | 1.01%   |
| Pantheon          | 101       | 0.96%   |
| LXQt              | 87        | 0.83%   |
| Budgie            | 79        | 0.75%   |
| i3                | 66        | 0.63%   |
| Unity             | 57        | 0.54%   |
| LXDE              | 47        | 0.45%   |
| GNOME Flashback   | 24        | 0.23%   |
| Deepin            | 22        | 0.21%   |
| sway              | 15        | 0.14%   |
| lightdm-xsession  | 15        | 0.14%   |
| awesome           | 14        | 0.13%   |
| GNOME Classic     | 12        | 0.11%   |
| openbox           | 6         | 0.06%   |
| bspwm             | 6         | 0.06%   |
| xmonad            | 5         | 0.05%   |
| herbstluftwm      | 5         | 0.05%   |
| Trinity           | 4         | 0.04%   |
| Hyprland          | 4         | 0.04%   |
| Enlightenment     | 4         | 0.04%   |
| qtile             | 3         | 0.03%   |
| leftwm            | 3         | 0.03%   |
| icewm             | 3         | 0.03%   |
| DWM               | 3         | 0.03%   |
| chadwm            | 3         | 0.03%   |
| x-session-manager | 2         | 0.02%   |
| fluxbox           | 2         | 0.02%   |
| default           | 2         | 0.02%   |
| xubuntu           | 1         | 0.01%   |
| river             | 1         | 0.01%   |
| nxde              | 1         | 0.01%   |
| KDE:old           | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 8080      | 78.14%  |
| Wayland     | 1608      | 15.55%  |
| Unknown     | 545       | 5.27%   |
| Tty         | 106       | 1.03%   |
| Unspecified | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4888      | 46.72%  |
| SDDM    | 1522      | 14.55%  |
| LightDM | 1318      | 12.6%   |
| GDM3    | 1235      | 11.8%   |
| GDM     | 968       | 9.25%   |
| TDM     | 366       | 3.5%    |
| KDM     | 108       | 1.03%   |
| XDM     | 17        | 0.16%   |
| SLiM    | 16        | 0.15%   |
| LXDM    | 9         | 0.09%   |
| NODM    | 5         | 0.05%   |
| GREETD  | 5         | 0.05%   |
| Ly      | 3         | 0.03%   |
| MDM     | 2         | 0.02%   |
| LY-DM   | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| de_DE      | 6544      | 63.69%  |
| en_US      | 1958      | 19.06%  |
| Unknown    | 1095      | 10.66%  |
| en_GB      | 181       | 1.76%   |
| C          | 121       | 1.18%   |
| ru_RU      | 63        | 0.61%   |
| en_DE      | 35        | 0.34%   |
| pl_PL      | 34        | 0.33%   |
| it_IT      | 23        | 0.22%   |
| POSIX      | 18        | 0.18%   |
| fr_FR      | 17        | 0.17%   |
| es_ES      | 14        | 0.14%   |
| hu_HU      | 11        | 0.11%   |
| de_AT      | 11        | 0.11%   |
| C.UTF8     | 9         | 0.09%   |
| ru_UA      | 8         | 0.08%   |
| ro_RO      | 8         | 0.08%   |
| nl_NL      | 8         | 0.08%   |
| en_CA      | 8         | 0.08%   |
| en_IN      | 7         | 0.07%   |
| en_IE      | 7         | 0.07%   |
| de_CH      | 7         | 0.07%   |
| tr_TR      | 6         | 0.06%   |
| pt_BR      | 6         | 0.06%   |
| en_DK      | 6         | 0.06%   |
| en_AG      | 6         | 0.06%   |
| en_AU      | 5         | 0.05%   |
| sk_SK      | 4         | 0.04%   |
| bg_BG      | 4         | 0.04%   |
| uk_UA      | 3         | 0.03%   |
| nds_DE     | 3         | 0.03%   |
| de_BE      | 3         | 0.03%   |
| sl_SI      | 2         | 0.02%   |
| pt_PT      | 2         | 0.02%   |
| ja_JP      | 2         | 0.02%   |
| eo         | 2         | 0.02%   |
| en_US-UTF8 | 2         | 0.02%   |
| en_SG      | 2         | 0.02%   |
| el_GR      | 2         | 0.02%   |
| de_LI      | 2         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 5204      | 50.62%  |
| EFI  | 5077      | 49.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 7955      | 77.35%  |
| Btrfs    | 862       | 8.38%   |
| Overlay  | 761       | 7.4%    |
| Unknown  | 344       | 3.34%   |
| Tmpfs    | 148       | 1.44%   |
| Xfs      | 98        | 0.95%   |
| Zfs      | 57        | 0.55%   |
| Ext2     | 23        | 0.22%   |
| F2fs     | 16        | 0.16%   |
| Ext3     | 12        | 0.12%   |
| Rootfs   | 2         | 0.02%   |
| Reiserfs | 2         | 0.02%   |
| Aufs     | 2         | 0.02%   |
| XXXXXXX  | 1         | 0.01%   |
| XXXfs    | 1         | 0.01%   |
| OveXlay  | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 5367      | 52.04%  |
| GPT     | 3788      | 36.73%  |
| MBR     | 1158      | 11.23%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 8933      | 87.47%  |
| Yes       | 1280      | 12.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7644      | 74.85%  |
| Yes       | 2568      | 25.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2621      | 26.05%  |
| Hewlett-Packard     | 1470      | 14.61%  |
| Dell                | 1172      | 11.65%  |
| Acer                | 1085      | 10.79%  |
| ASUSTek Computer    | 846       | 8.41%   |
| Medion              | 311       | 3.09%   |
| Toshiba             | 261       | 2.59%   |
| Fujitsu             | 252       | 2.5%    |
| Apple               | 234       | 2.33%   |
| Samsung Electronics | 210       | 2.09%   |
| TUXEDO              | 207       | 2.06%   |
| Sony                | 170       | 1.69%   |
| MSI                 | 158       | 1.57%   |
| HUAWEI              | 118       | 1.17%   |
| Notebook            | 94        | 0.93%   |
| Fujitsu Siemens     | 91        | 0.9%    |
| Valve               | 90        | 0.89%   |
| Packard Bell        | 82        | 0.82%   |
| Schenker            | 73        | 0.73%   |
| Unknown             | 45        | 0.45%   |
| Wortmann AG         | 42        | 0.42%   |
| Google              | 25        | 0.25%   |
| Gigabyte Technology | 23        | 0.23%   |
| TrekStor            | 22        | 0.22%   |
| IBM                 | 17        | 0.17%   |
| Clevo               | 17        | 0.17%   |
| Timi                | 16        | 0.16%   |
| AXDIA International | 16        | 0.16%   |
| Alienware           | 16        | 0.16%   |
| eMachines           | 15        | 0.15%   |
| Razer               | 14        | 0.14%   |
| Panasonic           | 13        | 0.13%   |
| LG Electronics      | 13        | 0.13%   |
| Framework           | 12        | 0.12%   |
| Chuwi               | 12        | 0.12%   |
| Tactus              | 9         | 0.09%   |
| LincPlus            | 9         | 0.09%   |
| AMI                 | 9         | 0.09%   |
| VALE                | 6         | 0.06%   |
| CSL-Computer        | 6         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 114       | 1.13%   |
| Valve Jupiter                 | 90        | 0.89%   |
| HP Notebook                   | 51        | 0.51%   |
| Lenovo IdeaPad 5 15ARE05 81YQ | 30        | 0.3%    |
| ASUS P50IJ                    | 29        | 0.29%   |
| HP 255 G7 Notebook PC         | 27        | 0.27%   |
| Dell Latitude E6420           | 24        | 0.24%   |
| HP Laptop 15s-eq2xxx          | 23        | 0.23%   |
| Dell Latitude E6430           | 22        | 0.22%   |
| Dell Latitude E6410           | 22        | 0.22%   |
| Dell XPS 15 9570              | 21        | 0.21%   |
| Acer Swift SF114-34           | 21        | 0.21%   |
| HP EliteBook 8470p            | 19        | 0.19%   |
| HP 250 G7 Notebook PC         | 19        | 0.19%   |
| Dell XPS 15 7590              | 19        | 0.19%   |
| Dell XPS 13 9370              | 19        | 0.19%   |
| HP Pavilion Notebook          | 18        | 0.18%   |
| HP Pavilion dv7               | 18        | 0.18%   |
| HP Pavilion 17                | 18        | 0.18%   |
| HP Laptop 17-ca1xxx           | 18        | 0.18%   |
| HP Laptop 17-ca0xxx           | 18        | 0.18%   |
| Dell XPS 13 7390              | 18        | 0.18%   |
| Dell Latitude E7470           | 18        | 0.18%   |
| Apple MacBookPro9,2           | 18        | 0.18%   |
| TUXEDO Pulse 15 Gen1          | 17        | 0.17%   |
| Lenovo G50-70 20351           | 17        | 0.17%   |
| HP Pavilion g6                | 17        | 0.17%   |
| HP EliteBook 8460p            | 17        | 0.17%   |
| HP EliteBook 840 G3           | 17        | 0.17%   |
| Dell XPS 15 9500              | 17        | 0.17%   |
| Dell Latitude E6540           | 17        | 0.17%   |
| Apple MacBookPro8,1           | 17        | 0.17%   |
| Acer Aspire 7750G             | 17        | 0.17%   |
| HUAWEI NBLK-WAX9X             | 16        | 0.16%   |
| HP ProBook 650 G1             | 16        | 0.16%   |
| HP Pavilion g7                | 16        | 0.16%   |
| HP Pavilion dv6               | 16        | 0.16%   |
| HP EliteBook 8440p            | 16        | 0.16%   |
| Dell Latitude E6520           | 16        | 0.16%   |
| HP Laptop 17-bs0xx            | 15        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 1740      | 17.3%   |
| Acer Aspire              | 741       | 7.37%   |
| Dell Latitude            | 536       | 5.33%   |
| Lenovo IdeaPad           | 404       | 4.02%   |
| HP EliteBook             | 320       | 3.18%   |
| HP Laptop                | 243       | 2.42%   |
| Fujitsu LIFEBOOK         | 239       | 2.38%   |
| HP Pavilion              | 218       | 2.17%   |
| Toshiba Satellite        | 212       | 2.11%   |
| Dell XPS                 | 195       | 1.94%   |
| HP ProBook               | 185       | 1.84%   |
| Dell Inspiron            | 165       | 1.64%   |
| Dell Precision           | 141       | 1.4%    |
| Unknown                  | 114       | 1.13%   |
| Acer Swift               | 109       | 1.08%   |
| ASUS VivoBook            | 104       | 1.03%   |
| HP Compaq                | 91        | 0.9%    |
| Valve Jupiter            | 90        | 0.89%   |
| Acer TravelMate          | 84        | 0.83%   |
| Packard Bell EasyNote    | 73        | 0.73%   |
| HP 255                   | 64        | 0.64%   |
| Medion Akoya             | 63        | 0.63%   |
| ASUS ZenBook             | 61        | 0.61%   |
| HP ZBook                 | 59        | 0.59%   |
| Dell Vostro              | 59        | 0.59%   |
| HP 250                   | 57        | 0.57%   |
| Lenovo Yoga              | 54        | 0.54%   |
| HP Notebook              | 51        | 0.51%   |
| TUXEDO InfinityBook      | 45        | 0.45%   |
| Lenovo Legion            | 42        | 0.42%   |
| Acer Extensa             | 40        | 0.4%    |
| Fujitsu Siemens AMILO    | 38        | 0.38%   |
| Schenker XMG             | 37        | 0.37%   |
| Lenovo ThinkBook         | 37        | 0.37%   |
| Acer Nitro               | 37        | 0.37%   |
| HP ENVY                  | 35        | 0.35%   |
| ASUS ROG                 | 34        | 0.34%   |
| Apple MacBookPro11       | 33        | 0.33%   |
| Fujitsu Siemens LIFEBOOK | 29        | 0.29%   |
| ASUS P50IJ               | 29        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 882       | 8.77%   |
| 2012    | 839       | 8.34%   |
| 2019    | 831       | 8.26%   |
| 2011    | 804       | 7.99%   |
| 2018    | 785       | 7.8%    |
| 2021    | 710       | 7.06%   |
| 2013    | 666       | 6.62%   |
| 2010    | 622       | 6.18%   |
| 2014    | 582       | 5.79%   |
| 2017    | 561       | 5.58%   |
| 2016    | 533       | 5.3%    |
| 2015    | 532       | 5.29%   |
| 2008    | 468       | 4.65%   |
| 2009    | 424       | 4.21%   |
| 2022    | 366       | 3.64%   |
| 2007    | 238       | 2.37%   |
| 2006    | 111       | 1.1%    |
| 2005    | 42        | 0.42%   |
| 2023    | 26        | 0.26%   |
| Unknown | 21        | 0.21%   |
| 2004    | 10        | 0.1%    |
| 2003    | 3         | 0.03%   |
| 2002    | 2         | 0.02%   |
| 2000    | 1         | 0.01%   |
| 1999    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 10060     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 9161      | 90.24%  |
| Enabled  | 991       | 9.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 10013     | 99.53%  |
| Yes  | 47        | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2880      | 28.29%  |
| 3.01-4.0    | 2312      | 22.71%  |
| 8.01-16.0   | 1824      | 17.92%  |
| 16.01-24.0  | 1557      | 15.29%  |
| 32.01-64.0  | 658       | 6.46%   |
| 1.01-2.0    | 427       | 4.19%   |
| 2.01-3.0    | 184       | 1.81%   |
| 64.01-256.0 | 127       | 1.25%   |
| 24.01-32.0  | 119       | 1.17%   |
| 0.51-1.0    | 84        | 0.83%   |
| 0.01-0.5    | 7         | 0.07%   |
| Unknown     | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 4553      | 40.85%  |
| 2.01-3.0   | 2730      | 24.49%  |
| 3.01-4.0   | 1260      | 11.3%   |
| 4.01-8.0   | 1259      | 11.3%   |
| 0.51-1.0   | 795       | 7.13%   |
| 8.01-16.0  | 361       | 3.24%   |
| 0.01-0.5   | 121       | 1.09%   |
| 16.01-24.0 | 44        | 0.39%   |
| 24.01-32.0 | 16        | 0.14%   |
| 32.01-64.0 | 3         | 0.03%   |
| Unknown    | 3         | 0.03%   |
| 0          | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 7573      | 73.5%   |
| 2      | 2306      | 22.38%  |
| 3      | 280       | 2.72%   |
| 0      | 87        | 0.84%   |
| 4      | 45        | 0.44%   |
| 6      | 5         | 0.05%   |
| 5      | 4         | 0.04%   |
| 7      | 2         | 0.02%   |
| 9      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 5744      | 56.74%  |
| Yes       | 4380      | 43.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8511      | 84.28%  |
| No        | 1587      | 15.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 9888      | 98.2%   |
| No        | 181       | 1.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7497      | 73.27%  |
| No        | 2735      | 26.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Germany | 10060     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Berlin               | 963       | 8.81%   |
| Munich               | 517       | 4.73%   |
| Hamburg              | 400       | 3.66%   |
| Frankfurt am Main    | 330       | 3.02%   |
| Cologne              | 258       | 2.36%   |
| Stuttgart            | 217       | 1.99%   |
| Leipzig              | 173       | 1.58%   |
| Dresden              | 136       | 1.24%   |
| Nuremberg            | 127       | 1.16%   |
| Düsseldorf          | 121       | 1.11%   |
| Essen                | 114       | 1.04%   |
| Mannheim             | 108       | 0.99%   |
| Karlsruhe            | 99        | 0.91%   |
| Dortmund             | 93        | 0.85%   |
| Duisburg             | 80        | 0.73%   |
| Bremen               | 76        | 0.7%    |
| Bonn                 | 74        | 0.68%   |
| Hanover              | 70        | 0.64%   |
| Bielefeld            | 69        | 0.63%   |
| Wuppertal            | 66        | 0.6%    |
| Darmstadt            | 61        | 0.56%   |
| Münster             | 59        | 0.54%   |
| Augsburg             | 58        | 0.53%   |
| Braunschweig         | 56        | 0.51%   |
| Wiesbaden            | 54        | 0.49%   |
| Bochum               | 53        | 0.48%   |
| Mainz                | 50        | 0.46%   |
| Regensburg           | 49        | 0.45%   |
| Chemnitz             | 48        | 0.44%   |
| Kiel                 | 46        | 0.42%   |
| Aachen               | 46        | 0.42%   |
| Halle                | 42        | 0.38%   |
| Freiburg im Breisgau | 42        | 0.38%   |
| Bamberg              | 39        | 0.36%   |
| Erfurt               | 36        | 0.33%   |
| Ulm                  | 34        | 0.31%   |
| Garbsen              | 34        | 0.31%   |
| Heilbronn            | 33        | 0.3%    |
| Reutlingen           | 32        | 0.29%   |
| Offenbach            | 31        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2705      | 3634   | 21.97%  |
| WDC                         | 1230      | 1578   | 9.99%   |
| Seagate                     | 1109      | 1436   | 9.01%   |
| SanDisk                     | 1021      | 1379   | 8.29%   |
| Toshiba                     | 926       | 1185   | 7.52%   |
| Unknown                     | 683       | 937    | 5.55%   |
| SK hynix                    | 505       | 630    | 4.1%    |
| Crucial                     | 471       | 619    | 3.83%   |
| Hitachi                     | 385       | 470    | 3.13%   |
| Kingston                    | 376       | 465    | 3.05%   |
| Intel                       | 354       | 462    | 2.88%   |
| Micron Technology           | 335       | 422    | 2.72%   |
| Intenso                     | 306       | 390    | 2.49%   |
| HGST                        | 238       | 303    | 1.93%   |
| Fujitsu                     | 109       | 139    | 0.89%   |
| Apple                       | 99        | 124    | 0.8%    |
| KIOXIA                      | 98        | 122    | 0.8%    |
| Transcend                   | 81        | 100    | 0.66%   |
| Phison                      | 79        | 102    | 0.64%   |
| LITEON                      | 75        | 78     | 0.61%   |
| A-DATA Technology           | 64        | 73     | 0.52%   |
| Unknown                     | 61        | 66     | 0.5%    |
| LITEONIT                    | 47        | 58     | 0.38%   |
| China                       | 43        | 50     | 0.35%   |
| Phison Electronics          | 42        | 47     | 0.34%   |
| Micron/Crucial Technology   | 42        | 46     | 0.34%   |
| Kingston Technology Company | 38        | 45     | 0.31%   |
| SPCC                        | 36        | 40     | 0.29%   |
| OCZ                         | 36        | 48     | 0.29%   |
| JMicron Technology          | 32        | 32     | 0.26%   |
| Silicon Motion              | 30        | 37     | 0.24%   |
| Patriot                     | 26        | 30     | 0.21%   |
| UMIS                        | 24        | 39     | 0.19%   |
| Netac                       | 23        | 33     | 0.19%   |
| ASMT                        | 23        | 28     | 0.19%   |
| Lenovo                      | 22        | 26     | 0.18%   |
| INNOVATION IT               | 22        | 29     | 0.18%   |
| Leven                       | 21        | 32     | 0.17%   |
| Union Memory (Shenzhen)     | 17        | 28     | 0.14%   |
| PNY                         | 16        | 21     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 136       | 1.06%   |
| Unknown MMC Card  32GB                              | 124       | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 119       | 0.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 116       | 0.9%    |
| Samsung SSD 850 EVO 500GB                           | 116       | 0.9%    |
| Samsung SSD 860 EVO 500GB                           | 111       | 0.86%   |
| Samsung SSD 850 EVO 250GB                           | 105       | 0.82%   |
| Unknown MMC Card  64GB                              | 101       | 0.79%   |
| Samsung NVMe SSD Drive 512GB                        | 99        | 0.77%   |
| SanDisk NVMe SSD Drive 512GB                        | 98        | 0.76%   |
| Seagate ST9500325AS 500GB                           | 92        | 0.72%   |
| Seagate ST1000LM035-1RK172 1TB                      | 92        | 0.72%   |
| Crucial CT500MX500SSD1 500GB                        | 78        | 0.61%   |
| Toshiba MQ01ABF050 500GB                            | 73        | 0.57%   |
| SanDisk SSD PLUS 240GB                              | 71        | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 69        | 0.54%   |
| Unknown MMC Card  128GB                             | 64        | 0.5%    |
| Samsung SSD 860 EVO 1TB                             | 64        | 0.5%    |
| SK hynix NVMe SSD Drive 512GB                       | 63        | 0.49%   |
| Unknown                                             | 61        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 60        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 60        | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 59        | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 56        | 0.44%   |
| SanDisk SSD PLUS 1000GB                             | 56        | 0.44%   |
| Samsung NVMe SSD Drive 1024GB                       | 56        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 56        | 0.44%   |
| Samsung NVMe SSD Drive 256GB                        | 54        | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 51        | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB                        | 50        | 0.39%   |
| Intel NVMe SSD Drive 512GB                          | 49        | 0.38%   |
| Crucial CT240BX500SSD1 240GB                        | 49        | 0.38%   |
| Samsung SSD 840 EVO 250GB                           | 47        | 0.37%   |
| HGST HTS725050A7E630 500GB                          | 47        | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 46        | 0.36%   |
| Samsung NVMe SSD Drive 500GB                        | 44        | 0.34%   |
| Samsung SSD 840 EVO 500GB                           | 43        | 0.33%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.33%   |
| Intenso SSD SATAIII 128GB                           | 43        | 0.33%   |
| HGST HTS541010A9E680 1TB                            | 43        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1075      | 1392   | 31.02%  |
| WDC                 | 819       | 1065   | 23.63%  |
| Toshiba             | 573       | 725    | 16.53%  |
| Hitachi             | 385       | 470    | 11.11%  |
| HGST                | 238       | 303    | 6.87%   |
| Samsung Electronics | 116       | 149    | 3.35%   |
| Fujitsu             | 109       | 139    | 3.14%   |
| Unknown             | 33        | 72     | 0.95%   |
| Intenso             | 24        | 31     | 0.69%   |
| JMicron Technology  | 22        | 23     | 0.63%   |
| ASMT                | 16        | 20     | 0.46%   |
| Apple               | 9         | 9      | 0.26%   |
| USB3.0              | 8         | 9      | 0.23%   |
| IBM/Hitachi         | 8         | 8      | 0.23%   |
| ASMedia             | 8         | 9      | 0.23%   |
| USB                 | 3         | 3      | 0.09%   |
| External            | 3         | 3      | 0.09%   |
| SILICONMOTION       | 2         | 3      | 0.06%   |
| LIO-ORG             | 2         | 8      | 0.06%   |
| HGST HTS            | 2         | 2      | 0.06%   |
| WD_BLACK            | 1         | 1      | 0.03%   |
| WD MediaMax         | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| SSK                 | 1         | 1      | 0.03%   |
| LaCie               | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| IB-AC703            | 1         | 1      | 0.03%   |
| Dell                | 1         | 1      | 0.03%   |
| ASUSTOR             | 1         | 2      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1480      | 1948   | 32.19%  |
| SanDisk             | 703       | 985    | 15.29%  |
| Crucial             | 438       | 582    | 9.53%   |
| Kingston            | 244       | 315    | 5.31%   |
| Intenso             | 233       | 292    | 5.07%   |
| WDC                 | 163       | 201    | 3.55%   |
| Micron Technology   | 144       | 173    | 3.13%   |
| Toshiba             | 132       | 160    | 2.87%   |
| SK hynix            | 116       | 138    | 2.52%   |
| Intel               | 114       | 145    | 2.48%   |
| Transcend           | 79        | 98     | 1.72%   |
| LITEON              | 70        | 73     | 1.52%   |
| Apple               | 70        | 81     | 1.52%   |
| A-DATA Technology   | 52        | 59     | 1.13%   |
| LITEONIT            | 47        | 58     | 1.02%   |
| China               | 43        | 50     | 0.94%   |
| OCZ                 | 36        | 48     | 0.78%   |
| SPCC                | 32        | 35     | 0.7%    |
| Patriot             | 26        | 30     | 0.57%   |
| Netac               | 23        | 33     | 0.5%    |
| INNOVATION IT       | 22        | 29     | 0.48%   |
| Phison              | 20        | 22     | 0.43%   |
| Leven               | 20        | 31     | 0.43%   |
| Unknown             | 19        | 20     | 0.41%   |
| Apacer              | 14        | 18     | 0.3%    |
| Hewlett-Packard     | 13        | 14     | 0.28%   |
| PNY                 | 12        | 16     | 0.26%   |
| Verbatim            | 11        | 18     | 0.24%   |
| Unknown             | 11        | 11     | 0.24%   |
| Emtec               | 11        | 12     | 0.24%   |
| Seagate             | 10        | 12     | 0.22%   |
| KingSpec            | 10        | 13     | 0.22%   |
| Dogfish             | 10        | 18     | 0.22%   |
| Corsair             | 8         | 9      | 0.17%   |
| Lexar               | 7         | 9      | 0.15%   |
| KingDian            | 7         | 8      | 0.15%   |
| TrekStor            | 6         | 8      | 0.13%   |
| GOODRAM             | 6         | 6      | 0.13%   |
| BIWIN               | 6         | 6      | 0.13%   |
| TO Exter            | 5         | 6      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 4294      | 5947   | 36.49%  |
| HDD     | 3344      | 4455   | 28.42%  |
| NVMe    | 3274      | 4437   | 27.82%  |
| MMC     | 691       | 914    | 5.87%   |
| Unknown | 164       | 209    | 1.39%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6895      | 10037  | 61.18%  |
| NVMe | 3266      | 4416   | 28.98%  |
| MMC  | 691       | 914    | 6.13%   |
| SAS  | 418       | 595    | 3.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5365      | 7396   | 70.72%  |
| 0.51-1.0   | 1971      | 2658   | 25.98%  |
| 1.01-2.0   | 205       | 271    | 2.7%    |
| 4.01-10.0  | 23        | 36     | 0.3%    |
| 3.01-4.0   | 21        | 39     | 0.28%   |
| 2.01-3.0   | 1         | 2      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 3160      | 29.63%  |
| 251-500        | 2767      | 25.95%  |
| 501-1000       | 1574      | 14.76%  |
| 1-20           | 769       | 7.21%   |
| 51-100         | 700       | 6.56%   |
| 1001-2000      | 578       | 5.42%   |
| 21-50          | 417       | 3.91%   |
| Unknown        | 328       | 3.08%   |
| More than 3000 | 223       | 2.09%   |
| 2001-3000      | 148       | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 4337      | 38.84%  |
| 21-50          | 2128      | 19.06%  |
| 101-250        | 1448      | 12.97%  |
| 51-100         | 1381      | 12.37%  |
| 251-500        | 826       | 7.4%    |
| 501-1000       | 424       | 3.8%    |
| Unknown        | 328       | 2.94%   |
| 1001-2000      | 198       | 1.77%   |
| More than 3000 | 56        | 0.5%    |
| 2001-3000      | 36        | 0.32%   |
| 0              | 3         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                                          | 12        | 15     | 2.34%   |
| Seagate ST9500325AS 500GB                                       | 10        | 14     | 1.95%   |
| Seagate ST9320325AS 320GB                                       | 9         | 10     | 1.75%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 9         | 9      | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 9         | 12     | 1.75%   |
| Seagate ST500LT012-1DG142 500GB                                 | 8         | 8      | 1.56%   |
| HGST HTS725050A7E630 500GB                                      | 8         | 8      | 1.56%   |
| Seagate ST500LT012-9WS142 500GB                                 | 7         | 8      | 1.36%   |
| Seagate ST500LM000-SSHD-8GB                                     | 7         | 7      | 1.36%   |
| HGST HTS545050A7E680 500GB                                      | 7         | 11     | 1.36%   |
| Seagate ST500LM000-1EJ162 500GB                                 | 6         | 9      | 1.17%   |
| HGST HTS541010A9E680 1TB                                        | 6         | 6      | 1.17%   |
| Hitachi HTS547575A9E384 752GB                                   | 5         | 5      | 0.97%   |
| Crucial M4-CT256M4SSD3 256GB                                    | 5         | 5      | 0.97%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 4         | 4      | 0.78%   |
| Seagate ST9500420AS 500GB                                       | 4         | 4      | 0.78%   |
| Seagate ST9250315AS 250GB                                       | 4         | 5      | 0.78%   |
| SanDisk SSD PLUS 1000GB                                         | 4         | 5      | 0.78%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD             | 4         | 4      | 0.78%   |
| Hitachi HTS547564A9E384 640GB                                   | 4         | 4      | 0.78%   |
| Hitachi HTS545050A7E380 500GB                                   | 4         | 4      | 0.78%   |
| Hitachi HTS541616J9SA00 160GB                                   | 4         | 5      | 0.78%   |
| HGST HTS545050A7E380 500GB                                      | 4         | 7      | 0.78%   |
| Fujitsu MHZ2320BH G2 320GB                                      | 4         | 5      | 0.78%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                                | 3         | 3      | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB                                        | 3         | 4      | 0.58%   |
| Toshiba MQ01ACF050 500GB                                        | 3         | 3      | 0.58%   |
| Toshiba MQ01ABD075 752GB                                        | 3         | 4      | 0.58%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD                         | 3         | 3      | 0.58%   |
| Seagate ST9750423AS 752GB                                       | 3         | 4      | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB                                  | 3         | 3      | 0.58%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 3      | 0.58%   |
| Samsung Electronics HM160HI 160GB                               | 3         | 7      | 0.58%   |
| Hitachi HTS723232A7A364 320GB                                   | 3         | 3      | 0.58%   |
| Hitachi HTS545032B9A300 320GB                                   | 3         | 3      | 0.58%   |
| Hitachi HTS545025B9A300 250GB                                   | 3         | 3      | 0.58%   |
| Hitachi HTS543232A7A384 320GB                                   | 3         | 3      | 0.58%   |
| HGST HTS721010A9E630 1TB                                        | 3         | 4      | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 2         | 2      | 0.39%   |
| WDC WD7500BPVX-22JC3T0 752GB                                    | 2         | 2      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 121       | 142    | 23.73%  |
| WDC                 | 62        | 69     | 12.16%  |
| Hitachi             | 60        | 66     | 11.76%  |
| Toshiba             | 52        | 59     | 10.2%   |
| Samsung Electronics | 43        | 50     | 8.43%   |
| HGST                | 30        | 38     | 5.88%   |
| SanDisk             | 25        | 30     | 4.9%    |
| SK hynix            | 21        | 24     | 4.12%   |
| Crucial             | 17        | 18     | 3.33%   |
| Micron Technology   | 16        | 19     | 3.14%   |
| Fujitsu             | 16        | 18     | 3.14%   |
| Intel               | 12        | 12     | 2.35%   |
| Kingston            | 8         | 8      | 1.57%   |
| Transcend           | 5         | 5      | 0.98%   |
| Intenso             | 3         | 3      | 0.59%   |
| China               | 3         | 3      | 0.59%   |
| A-DATA Technology   | 3         | 4      | 0.59%   |
| PNY                 | 2         | 3      | 0.39%   |
| LITEONIT            | 2         | 5      | 0.39%   |
| LITEON              | 2         | 2      | 0.39%   |
| Apple               | 2         | 2      | 0.39%   |
| Phison              | 1         | 1      | 0.2%    |
| OCZ                 | 1         | 1      | 0.2%    |
| IBM/Hitachi         | 1         | 1      | 0.2%    |
| ASMedia             | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 141    | 35.09%  |
| Hitachi             | 60        | 66     | 17.54%  |
| WDC                 | 51        | 58     | 14.91%  |
| Toshiba             | 46        | 51     | 13.45%  |
| HGST                | 30        | 38     | 8.77%   |
| Samsung Electronics | 17        | 21     | 4.97%   |
| Fujitsu             | 16        | 18     | 4.68%   |
| IBM/Hitachi         | 1         | 1      | 0.29%   |
| ASMedia             | 1         | 1      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 340       | 395    | 67.06%  |
| SSD  | 140       | 156    | 27.61%  |
| NVMe | 27        | 34     | 5.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-00A0RT0 500GB                   | 1         | 1      | 8.33%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB           | 1         | 1      | 8.33%   |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 8.33%   |
| Toshiba MK1059GSM 1TB                          | 1         | 1      | 8.33%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 980 1TB                | 1         | 1      | 8.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 8.33%   |
| Intel SSDSCKGF256A5 SATA 256GB                 | 1         | 1      | 8.33%   |
| Intel SSDSA2BW160G3 160GB                      | 1         | 1      | 8.33%   |
| Hitachi HTS541010G9SA00 100GB                  | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 16.67%  |
| Toshiba             | 2         | 2      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Intel               | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Micron Technology   | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 6182      | 10092  | 58.25%  |
| Works    | 3914      | 5273   | 36.88%  |
| Malfunc  | 504       | 585    | 4.75%   |
| Failed   | 12        | 12     | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 6975      | 60.49%  |
| Samsung Electronics                     | 1240      | 10.75%  |
| AMD                                     | 1105      | 9.58%   |
| SanDisk                                 | 550       | 4.77%   |
| SK hynix                                | 372       | 3.23%   |
| Toshiba America Info Systems            | 225       | 1.95%   |
| Micron Technology                       | 192       | 1.67%   |
| Kingston Technology Company             | 166       | 1.44%   |
| Phison Electronics                      | 107       | 0.93%   |
| Nvidia                                  | 106       | 0.92%   |
| KIOXIA                                  | 104       | 0.9%    |
| Micron/Crucial Technology               | 73        | 0.63%   |
| Union Memory (Shenzhen)                 | 46        | 0.4%    |
| Silicon Motion                          | 35        | 0.3%    |
| Silicon Integrated Systems [SiS]        | 28        | 0.24%   |
| Solid State Storage Technology          | 23        | 0.2%    |
| Lenovo                                  | 22        | 0.19%   |
| ADATA Technology                        | 21        | 0.18%   |
| Apple                                   | 17        | 0.15%   |
| VIA Technologies                        | 16        | 0.14%   |
| Lite-On Technology                      | 14        | 0.12%   |
| Silicon Image                           | 13        | 0.11%   |
| Seagate Technology                      | 12        | 0.1%    |
| O2 Micro                                | 11        | 0.1%    |
| Marvell Technology Group                | 11        | 0.1%    |
| JMicron Technology                      | 9         | 0.08%   |
| Shenzhen Longsys Electronics            | 8         | 0.07%   |
| Realtek Semiconductor                   | 8         | 0.07%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.05%   |
| ASMedia Technology                      | 4         | 0.03%   |
| Yangtze Memory Technologies             | 3         | 0.03%   |
| ULi Electronics                         | 3         | 0.03%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| INNOGRIT                                | 1         | 0.01%   |
| Biwin Storage Technology                | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 877       | 7.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 850       | 6.86%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 756       | 6.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 655       | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 637       | 5.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 492       | 3.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 438       | 3.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 373       | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 330       | 2.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 330       | 2.66%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 280       | 2.26%   |
| Samsung NVMe SSD Controller 980                                                  | 266       | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 218       | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 212       | 1.71%   |
| Intel Volume Management Device NVMe RAID Controller                              | 204       | 1.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 186       | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 185       | 1.49%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 179       | 1.44%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 152       | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 151       | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 142       | 1.15%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 142       | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 142       | 1.15%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 119       | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 114       | 0.92%   |
| Intel SSD 660P Series                                                            | 114       | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 103       | 0.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 95        | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 94        | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 93        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 91        | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 89        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 88        | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 86        | 0.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 85        | 0.69%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 84        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 77        | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 70        | 0.56%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 68        | 0.55%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 62        | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 7138      | 59.73%  |
| NVMe | 3290      | 27.53%  |
| IDE  | 854       | 7.15%   |
| RAID | 668       | 5.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 8174      | 81.25%  |
| AMD          | 1875      | 18.64%  |
| ARM          | 4         | 0.04%   |
| Unknown      | 2         | 0.02%   |
| QUALCOMM     | 1         | 0.01%   |
| PowerBook5,6 | 1         | 0.01%   |
| PowerBook5,4 | 1         | 0.01%   |
| PowerBook3,4 | 1         | 0.01%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz             | 161       | 1.6%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 160       | 1.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 153       | 1.52%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 134       | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 134       | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 131       | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 119       | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 118       | 1.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 118       | 1.17%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 113       | 1.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 113       | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 111       | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 109       | 1.08%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 99        | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 98        | 0.97%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 96        | 0.95%   |
| AMD Custom APU 0405                           | 90        | 0.89%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 89        | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 79        | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 79        | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 75        | 0.74%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 71        | 0.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 70        | 0.69%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 70        | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 69        | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 68        | 0.68%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 67        | 0.67%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 67        | 0.67%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 66        | 0.66%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 64        | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 64        | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 64        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 62        | 0.62%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 62        | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 60        | 0.6%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 58        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 57        | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 55        | 0.55%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 55        | 0.55%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 54        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2603      | 25.86%  |
| Intel Core i7                  | 2108      | 20.94%  |
| Other                          | 696       | 6.92%   |
| Intel Core i3                  | 673       | 6.69%   |
| Intel Core 2 Duo               | 656       | 6.52%   |
| AMD Ryzen 5                    | 439       | 4.36%   |
| Intel Celeron                  | 417       | 4.14%   |
| AMD Ryzen 7                    | 406       | 4.03%   |
| Intel Pentium                  | 354       | 3.52%   |
| Intel Atom                     | 235       | 2.33%   |
| AMD Ryzen 7 PRO                | 121       | 1.2%    |
| Intel Pentium Dual-Core        | 113       | 1.12%   |
| AMD A6                         | 91        | 0.9%    |
| AMD Ryzen 3                    | 81        | 0.8%    |
| AMD E                          | 75        | 0.75%   |
| Intel Pentium Silver           | 74        | 0.74%   |
| AMD A4                         | 71        | 0.71%   |
| AMD A8                         | 65        | 0.65%   |
| Intel Core 2                   | 64        | 0.64%   |
| Intel Genuine                  | 63        | 0.63%   |
| Intel Pentium Dual             | 59        | 0.59%   |
| AMD Ryzen 9                    | 51        | 0.51%   |
| Intel Pentium M                | 44        | 0.44%   |
| AMD Turion 64 X2 Mobile        | 44        | 0.44%   |
| AMD E2                         | 44        | 0.44%   |
| AMD Ryzen 5 PRO                | 32        | 0.32%   |
| AMD A10                        | 29        | 0.29%   |
| Intel Core i9                  | 28        | 0.28%   |
| AMD E1                         | 26        | 0.26%   |
| AMD Athlon                     | 25        | 0.25%   |
| Intel Celeron M                | 24        | 0.24%   |
| AMD Athlon II                  | 21        | 0.21%   |
| Intel Core M                   | 19        | 0.19%   |
| AMD Athlon X2                  | 19        | 0.19%   |
| Intel Xeon                     | 15        | 0.15%   |
| AMD Athlon 64 X2               | 13        | 0.13%   |
| Intel Core m5                  | 12        | 0.12%   |
| Intel Core m3                  | 12        | 0.12%   |
| AMD Turion 64 Mobile           | 12        | 0.12%   |
| AMD Turion X2 Dual-Core Mobile | 10        | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 5278      | 52.42%  |
| 4       | 3131      | 31.1%   |
| 6       | 600       | 5.96%   |
| 8       | 589       | 5.85%   |
| 1       | 292       | 2.9%    |
| 14      | 63        | 0.63%   |
| 12      | 52        | 0.52%   |
| 10      | 38        | 0.38%   |
| Unknown | 15        | 0.15%   |
| 5       | 4         | 0.04%   |
| 24      | 3         | 0.03%   |
| 16      | 3         | 0.03%   |
| 3       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 10055     | 99.95%  |
| 2       | 2         | 0.02%   |
| Unknown | 2         | 0.02%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7239      | 71.87%  |
| 1       | 2813      | 27.93%  |
| Unknown | 15        | 0.15%   |
| 4       | 3         | 0.03%   |
| 8       | 2         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9755      | 96.79%  |
| 32-bit         | 171       | 1.7%    |
| Unknown        | 150       | 1.49%   |
| 64-bit         | 3         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2478      | 23.76%  |
| 0x206a7    | 660       | 6.33%   |
| 0x306a9    | 650       | 6.23%   |
| 0x1067a    | 390       | 3.74%   |
| 0x40651    | 324       | 3.11%   |
| 0x406e3    | 315       | 3.02%   |
| 0x806ea    | 309       | 2.96%   |
| 0x806ec    | 294       | 2.82%   |
| 0x306c3    | 291       | 2.79%   |
| 0x20655    | 286       | 2.74%   |
| 0x806c1    | 264       | 2.53%   |
| 0x306d4    | 246       | 2.36%   |
| 0x806e9    | 236       | 2.26%   |
| 0x906ea    | 200       | 1.92%   |
| 0x10676    | 164       | 1.57%   |
| 0x6fd      | 160       | 1.53%   |
| 0x0a50000c | 144       | 1.38%   |
| 0x08108102 | 138       | 1.32%   |
| 0x30678    | 136       | 1.3%    |
| 0x08600106 | 131       | 1.26%   |
| 0x08608103 | 129       | 1.24%   |
| 0x20652    | 126       | 1.21%   |
| 0x08108109 | 114       | 1.09%   |
| 0x806eb    | 108       | 1.04%   |
| 0xa0652    | 101       | 0.97%   |
| 0x506e3    | 100       | 0.96%   |
| 0x406c4    | 97        | 0.93%   |
| 0x906e9    | 93        | 0.89%   |
| 0x706e5    | 87        | 0.83%   |
| 0x08600103 | 78        | 0.75%   |
| 0x06006705 | 71        | 0.68%   |
| 0x906a3    | 70        | 0.67%   |
| 0x506c9    | 70        | 0.67%   |
| 0x706a1    | 66        | 0.63%   |
| 0x05000119 | 66        | 0.63%   |
| 0x106ca    | 56        | 0.54%   |
| 0x07030105 | 54        | 0.52%   |
| 0x406c3    | 53        | 0.51%   |
| 0x106c2    | 50        | 0.48%   |
| 0x706a8    | 48        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1640      | 16.29%  |
| SandyBridge      | 829       | 8.23%   |
| IvyBridge        | 815       | 8.09%   |
| Haswell          | 785       | 7.8%    |
| Penryn           | 644       | 6.4%    |
| Skylake          | 560       | 5.56%   |
| Westmere         | 524       | 5.2%    |
| Unknown          | 423       | 4.2%    |
| Silvermont       | 361       | 3.59%   |
| Zen 2            | 341       | 3.39%   |
| Core             | 332       | 3.3%    |
| TigerLake        | 331       | 3.29%   |
| Broadwell        | 319       | 3.17%   |
| Zen+             | 290       | 2.88%   |
| Zen 3            | 215       | 2.14%   |
| IceLake          | 159       | 1.58%   |
| Goldmont plus    | 147       | 1.46%   |
| CometLake        | 142       | 1.41%   |
| Bonnell          | 121       | 1.2%    |
| Excavator        | 114       | 1.13%   |
| Alderlake Hybrid | 111       | 1.1%    |
| Bobcat           | 109       | 1.08%   |
| P6               | 107       | 1.06%   |
| Puma             | 96        | 0.95%   |
| Goldmont         | 89        | 0.88%   |
| K8 Hammer        | 85        | 0.84%   |
| Zen              | 81        | 0.8%    |
| Jaguar           | 48        | 0.48%   |
| K10              | 46        | 0.46%   |
| Piledriver       | 43        | 0.43%   |
| Nehalem          | 37        | 0.37%   |
| K8 & K10 hybrid  | 37        | 0.37%   |
| K10 Llano        | 36        | 0.36%   |
| Tremont          | 29        | 0.29%   |
| Steamroller      | 14        | 0.14%   |
| NetBurst         | 6         | 0.06%   |
| K6               | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7166      | 58.07%  |
| Nvidia                           | 2593      | 21.01%  |
| AMD                              | 2553      | 20.69%  |
| Silicon Integrated Systems [SiS] | 14        | 0.11%   |
| VIA Technologies                 | 10        | 0.08%   |
| S3 Graphics                      | 4         | 0.03%   |
| Neomagic                         | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 776       | 6.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 715       | 5.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 400       | 3.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 370       | 2.9%    |
| Intel UHD Graphics 620                                                                   | 368       | 2.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 366       | 2.87%   |
| AMD Renoir                                                                               | 336       | 2.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 333       | 2.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 326       | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 299       | 2.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 294       | 2.31%   |
| Intel HD Graphics 620                                                                    | 276       | 2.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 271       | 2.12%   |
| Intel HD Graphics 5500                                                                   | 255       | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 254       | 1.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 208       | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 189       | 1.48%   |
| AMD Lucienne                                                                             | 181       | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 172       | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 161       | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 133       | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 133       | 1.04%   |
| Intel HD Graphics 530                                                                    | 123       | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 122       | 0.96%   |
| Intel HD Graphics 630                                                                    | 115       | 0.9%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 110       | 0.86%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 109       | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 107       | 0.84%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 94        | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 91        | 0.71%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 90        | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 78        | 0.61%   |
| Nvidia GP108M [GeForce MX150]                                                            | 77        | 0.6%    |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 75        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 74        | 0.58%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 73        | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 70        | 0.55%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 70        | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 69        | 0.54%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 64        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 5004      | 49.63%  |
| 1 x AMD            | 1905      | 18.89%  |
| Intel + Nvidia     | 1782      | 17.67%  |
| 1 x Nvidia         | 657       | 6.52%   |
| Intel + AMD        | 359       | 3.56%   |
| 2 x AMD            | 149       | 1.48%   |
| AMD + Nvidia       | 144       | 1.43%   |
| 2 x Intel          | 22        | 0.22%   |
| 2 x Nvidia         | 17        | 0.17%   |
| Other              | 14        | 0.14%   |
| 1 x SiS            | 14        | 0.14%   |
| 1 x VIA            | 10        | 0.1%    |
| 1 x S3 Graphics    | 4         | 0.04%   |
| 1 x Neomagic       | 1         | 0.01%   |
| Intel + 2 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 8744      | 85.73%  |
| Proprietary | 1134      | 11.12%  |
| Unknown     | 322       | 3.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 6420      | 62.05%  |
| 0.01-0.5       | 1374      | 13.28%  |
| 1.01-2.0       | 1205      | 11.65%  |
| 0.51-1.0       | 686       | 6.63%   |
| 3.01-4.0       | 439       | 4.24%   |
| 5.01-6.0       | 119       | 1.15%   |
| 7.01-8.0       | 74        | 0.72%   |
| 2.01-3.0       | 15        | 0.14%   |
| 8.01-16.0      | 13        | 0.13%   |
| More than 64.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2226      | 20.01%  |
| LG Display              | 1754      | 15.77%  |
| Chimei Innolux          | 1363      | 12.25%  |
| BOE                     | 1157      | 10.4%   |
| Samsung Electronics     | 1102      | 9.91%   |
| Lenovo                  | 389       | 3.5%    |
| Chi Mei Optoelectronics | 286       | 2.57%   |
| Sharp                   | 280       | 2.52%   |
| Dell                    | 280       | 2.52%   |
| Apple                   | 239       | 2.15%   |
| Goldstar                | 174       | 1.56%   |
| BenQ                    | 134       | 1.2%    |
| PANDA                   | 131       | 1.18%   |
| LG Philips              | 129       | 1.16%   |
| Hewlett-Packard         | 111       | 1%      |
| Acer                    | 103       | 0.93%   |
| Ancor Communications    | 87        | 0.78%   |
| InfoVision              | 82        | 0.74%   |
| CSO                     | 70        | 0.63%   |
| AOC                     | 66        | 0.59%   |
| Philips                 | 61        | 0.55%   |
| Iiyama                  | 60        | 0.54%   |
| CPT                     | 57        | 0.51%   |
| Sony                    | 54        | 0.49%   |
| Eizo                    | 54        | 0.49%   |
| Valve                   | 52        | 0.47%   |
| Fujitsu Siemens         | 46        | 0.41%   |
| HannStar                | 45        | 0.4%    |
| Panasonic               | 35        | 0.31%   |
| LGD                     | 32        | 0.29%   |
| Seiko/Epson             | 31        | 0.28%   |
| Analogix                | 23        | 0.21%   |
| Toshiba                 | 22        | 0.2%    |
| Medion                  | 22        | 0.2%    |
| ASUSTek Computer        | 21        | 0.19%   |
| Vestel Elektronik       | 20        | 0.18%   |
| Quanta Display          | 19        | 0.17%   |
| Unknown                 | 18        | 0.16%   |
| ViewSonic               | 17        | 0.15%   |
| IBM                     | 17        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 83        | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 71        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 70        | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 66        | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 62        | 0.55%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 59        | 0.52%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 57        | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 56        | 0.5%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 53        | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 52        | 0.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 50        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 50        | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 48        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 47        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 45        | 0.4%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch            | 45        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 45        | 0.4%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 44        | 0.39%   |
| BOE LCD Monitor BOE0660 1600x900 382x215mm 17.3-inch                      | 42        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 41        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 41        | 0.36%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 40        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 39        | 0.35%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 39        | 0.35%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 38        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 37        | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 36        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 36        | 0.32%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 36        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 35        | 0.31%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 35        | 0.31%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 35        | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 35        | 0.31%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 34        | 0.3%    |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 34        | 0.3%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 32        | 0.28%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 32        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 32        | 0.28%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch            | 32        | 0.28%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 32        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4467      | 42.34%  |
| 1366x768 (WXGA)    | 2317      | 21.96%  |
| 1600x900 (HD+)     | 1042      | 9.88%   |
| 1280x800 (WXGA)    | 500       | 4.74%   |
| 3840x2160 (4K)     | 386       | 3.66%   |
| 2560x1440 (QHD)    | 341       | 3.23%   |
| 1440x900 (WXGA+)   | 250       | 2.37%   |
| 1920x1200 (WUXGA)  | 229       | 2.17%   |
| 1680x1050 (WSXGA+) | 151       | 1.43%   |
| 2560x1600          | 85        | 0.81%   |
| 1024x600           | 81        | 0.77%   |
| 2880x1800          | 77        | 0.73%   |
| 800x1280           | 71        | 0.67%   |
| 1280x1024 (SXGA)   | 64        | 0.61%   |
| 3440x1440          | 62        | 0.59%   |
| 3840x2400          | 47        | 0.45%   |
| 2160x1440          | 33        | 0.31%   |
| 3200x1800 (QHD+)   | 32        | 0.3%    |
| Unknown            | 28        | 0.27%   |
| 2560x1080          | 27        | 0.26%   |
| 1024x768 (XGA)     | 26        | 0.25%   |
| 2256x1504          | 22        | 0.21%   |
| 1680x945           | 21        | 0.2%    |
| 3840x1080          | 20        | 0.19%   |
| 1920x540           | 17        | 0.16%   |
| 1360x768           | 15        | 0.14%   |
| 1920x1280          | 12        | 0.11%   |
| 3000x2000          | 11        | 0.1%    |
| 1600x1200          | 10        | 0.09%   |
| 1400x1050          | 10        | 0.09%   |
| 2520x1680          | 8         | 0.08%   |
| 3840x1600          | 7         | 0.07%   |
| 3072x1920          | 7         | 0.07%   |
| 1280x720 (HD)      | 7         | 0.07%   |
| 2288x1287          | 6         | 0.06%   |
| 2304x1440          | 5         | 0.05%   |
| 1280x768           | 5         | 0.05%   |
| 2240x1400          | 4         | 0.04%   |
| 1920x515           | 4         | 0.04%   |
| 3840x1200          | 3         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 4173      | 37.52%  |
| 17      | 1438      | 12.93%  |
| 13      | 1305      | 11.73%  |
| 14      | 1290      | 11.6%   |
| 24      | 435       | 3.91%   |
| 27      | 401       | 3.61%   |
| 12      | 394       | 3.54%   |
| 23      | 239       | 2.15%   |
| Unknown | 191       | 1.72%   |
| 11      | 168       | 1.51%   |
| 21      | 137       | 1.23%   |
| 16      | 112       | 1.01%   |
| 10      | 102       | 0.92%   |
| 18      | 92        | 0.83%   |
| 34      | 74        | 0.67%   |
| 31      | 74        | 0.67%   |
| 22      | 64        | 0.58%   |
| 19      | 63        | 0.57%   |
| 7       | 53        | 0.48%   |
| 84      | 38        | 0.34%   |
| 25      | 26        | 0.23%   |
| 40      | 24        | 0.22%   |
| 72      | 23        | 0.21%   |
| 3       | 23        | 0.21%   |
| 20      | 22        | 0.2%    |
| 54      | 21        | 0.19%   |
| 32      | 20        | 0.18%   |
| 28      | 14        | 0.13%   |
| 26      | 14        | 0.13%   |
| 48      | 11        | 0.1%    |
| 8       | 9         | 0.08%   |
| 37      | 8         | 0.07%   |
| 52      | 7         | 0.06%   |
| 33      | 7         | 0.06%   |
| 142     | 6         | 0.05%   |
| 49      | 6         | 0.05%   |
| 35      | 6         | 0.05%   |
| 36      | 5         | 0.04%   |
| 65      | 4         | 0.04%   |
| 55      | 4         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 6014      | 54.5%   |
| 351-400        | 1635      | 14.82%  |
| 201-300        | 1364      | 12.36%  |
| 501-600        | 1010      | 9.15%   |
| 401-500        | 330       | 2.99%   |
| Unknown        | 191       | 1.73%   |
| 601-700        | 130       | 1.18%   |
| 701-800        | 107       | 0.97%   |
| 1-100          | 71        | 0.64%   |
| 1501-2000      | 60        | 0.54%   |
| 1001-1500      | 59        | 0.53%   |
| 801-900        | 40        | 0.36%   |
| 101-200        | 10        | 0.09%   |
| 901-1000       | 8         | 0.07%   |
| More than 2000 | 6         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 8048      | 80.77%  |
| 16/10   | 1332      | 13.37%  |
| Unknown | 142       | 1.43%   |
| 3/2     | 123       | 1.23%   |
| 21/9    | 92        | 0.92%   |
| 5/4     | 59        | 0.59%   |
| 0.67    | 52        | 0.52%   |
| 4/3     | 50        | 0.5%    |
| 6/5     | 28        | 0.28%   |
| 32/9    | 20        | 0.2%    |
| 1.00    | 6         | 0.06%   |
| 3.73    | 4         | 0.04%   |
| 0.62    | 3         | 0.03%   |
| 3.40    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.65    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 4168      | 37.53%  |
| 81-90          | 2038      | 18.35%  |
| 121-130        | 1217      | 10.96%  |
| 201-250        | 660       | 5.94%   |
| 71-80          | 542       | 4.88%   |
| 301-350        | 412       | 3.71%   |
| 61-70          | 388       | 3.49%   |
| 131-140        | 208       | 1.87%   |
| 351-500        | 191       | 1.72%   |
| 251-300        | 191       | 1.72%   |
| Unknown        | 191       | 1.72%   |
| 51-60          | 171       | 1.54%   |
| 151-200        | 134       | 1.21%   |
| More than 1000 | 107       | 0.96%   |
| 141-150        | 102       | 0.92%   |
| 41-50          | 100       | 0.9%    |
| 111-120        | 96        | 0.86%   |
| 1-40           | 81        | 0.73%   |
| 501-1000       | 65        | 0.59%   |
| 91-100         | 44        | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 4484      | 41.08%  |
| 101-120       | 3205      | 29.36%  |
| 51-100        | 1791      | 16.41%  |
| 161-240       | 828       | 7.59%   |
| More than 240 | 341       | 3.12%   |
| Unknown       | 191       | 1.75%   |
| 1-50          | 75        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 8309      | 80.46%  |
| 2     | 1473      | 14.26%  |
| 0     | 321       | 3.11%   |
| 3     | 208       | 2.01%   |
| 4     | 15        | 0.15%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 5740      | 35.27%  |
| Realtek Semiconductor             | 4813      | 29.57%  |
| Qualcomm Atheros                  | 2196      | 13.49%  |
| Broadcom                          | 1093      | 6.72%   |
| Broadcom Limited                  | 250       | 1.54%   |
| Marvell Technology Group          | 231       | 1.42%   |
| Sierra Wireless                   | 202       | 1.24%   |
| MediaTek                          | 181       | 1.11%   |
| Ericsson Business Mobile Networks | 181       | 1.11%   |
| Dell                              | 165       | 1.01%   |
| Ralink                            | 118       | 0.73%   |
| ASIX Electronics                  | 116       | 0.71%   |
| Lenovo                            | 109       | 0.67%   |
| Hewlett-Packard                   | 75        | 0.46%   |
| Nvidia                            | 74        | 0.45%   |
| TP-Link                           | 65        | 0.4%    |
| DisplayLink                       | 61        | 0.37%   |
| Huawei Technologies               | 60        | 0.37%   |
| Ralink Technology                 | 55        | 0.34%   |
| Fibocom                           | 48        | 0.29%   |
| Samsung Electronics               | 40        | 0.25%   |
| JMicron Technology                | 31        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 25        | 0.15%   |
| Qualcomm                          | 25        | 0.15%   |
| Edimax Technology                 | 23        | 0.14%   |
| ASUSTek Computer                  | 22        | 0.14%   |
| AVM                               | 19        | 0.12%   |
| Xiaomi                            | 17        | 0.1%    |
| NetGear                           | 15        | 0.09%   |
| VIA Technologies                  | 13        | 0.08%   |
| Qualcomm Atheros Communications   | 13        | 0.08%   |
| D-Link                            | 12        | 0.07%   |
| D-Link System                     | 11        | 0.07%   |
| Attansic Technology               | 11        | 0.07%   |
| Apple                             | 11        | 0.07%   |
| U-Blox                            | 9         | 0.06%   |
| Google                            | 9         | 0.06%   |
| Microsoft                         | 7         | 0.04%   |
| Arduino SA                        | 7         | 0.04%   |
| AMD                               | 7         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 3103      | 15.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 616       | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 579       | 2.88%   |
| Intel Wi-Fi 6 AX200                                                     | 538       | 2.68%   |
| Intel Wireless 8265 / 8275                                              | 466       | 2.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 442       | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 418       | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 402       | 2%      |
| Intel Wireless 7260                                                     | 402       | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 347       | 1.73%   |
| Intel Wireless 8260                                                     | 329       | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 300       | 1.49%   |
| Intel Wireless 7265                                                     | 278       | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 262       | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 241       | 1.2%    |
| Intel Wi-Fi 6 AX201                                                     | 228       | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 209       | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 202       | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 186       | 0.93%   |
| Intel 82577LM Gigabit Network Connection                                | 174       | 0.87%   |
| Intel Centrino Ultimate-N 6300                                          | 173       | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 160       | 0.8%    |
| Intel Ethernet Connection I219-LM                                       | 157       | 0.78%   |
| Intel Wireless 3160                                                     | 156       | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 155       | 0.77%   |
| Intel Wireless 3165                                                     | 153       | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 153       | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 150       | 0.75%   |
| Intel WiFi Link 5100                                                    | 149       | 0.74%   |
| Intel Wireless-AC 9260                                                  | 148       | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 148       | 0.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 144       | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 137       | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 136       | 0.68%   |
| Intel Ethernet Connection I217-LM                                       | 135       | 0.67%   |
| Intel 82567LM Gigabit Network Connection                                | 135       | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 133       | 0.66%   |
| Intel Ethernet Connection I218-LM                                       | 131       | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                   | 124       | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                    | 123       | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 5464      | 51.48%  |
| Qualcomm Atheros                  | 1821      | 17.16%  |
| Realtek Semiconductor             | 1476      | 13.91%  |
| Broadcom                          | 766       | 7.22%   |
| Sierra Wireless                   | 202       | 1.9%    |
| MediaTek                          | 177       | 1.67%   |
| Broadcom Limited                  | 128       | 1.21%   |
| Ralink                            | 118       | 1.11%   |
| Dell                              | 83        | 0.78%   |
| TP-Link                           | 57        | 0.54%   |
| Ralink Technology                 | 55        | 0.52%   |
| Fibocom                           | 48        | 0.45%   |
| Ericsson Business Mobile Networks | 26        | 0.24%   |
| Edimax Technology                 | 23        | 0.22%   |
| ASUSTek Computer                  | 22        | 0.21%   |
| Qualcomm                          | 20        | 0.19%   |
| AVM                               | 19        | 0.18%   |
| Hewlett-Packard                   | 17        | 0.16%   |
| NetGear                           | 14        | 0.13%   |
| Qualcomm Atheros Communications   | 13        | 0.12%   |
| D-Link System                     | 11        | 0.1%    |
| D-Link                            | 11        | 0.1%    |
| Microsoft                         | 6         | 0.06%   |
| ZyDAS                             | 5         | 0.05%   |
| Belkin Components                 | 4         | 0.04%   |
| Winbond Electronics               | 3         | 0.03%   |
| Wacom                             | 3         | 0.03%   |
| Fujitsu Siemens Computers         | 3         | 0.03%   |
| ZyXEL Communications              | 2         | 0.02%   |
| Texas Instruments                 | 2         | 0.02%   |
| Sitecom Europe                    | 2         | 0.02%   |
| Samsung Electronics               | 2         | 0.02%   |
| Quectel Wireless Solutions        | 2         | 0.02%   |
| Micro Star International          | 2         | 0.02%   |
| Linksys                           | 2         | 0.02%   |
| Qcom                              | 1         | 0.01%   |
| Marvell Technology Group          | 1         | 0.01%   |
| BUFFALO                           | 1         | 0.01%   |
| Acer NeWeb                        | 1         | 0.01%   |
| AboCom Systems                    | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 538       | 5.04%   |
| Intel Wireless 8265 / 8275                                              | 466       | 4.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 418       | 3.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 402       | 3.77%   |
| Intel Wireless 7260                                                     | 402       | 3.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 347       | 3.25%   |
| Intel Wireless 8260                                                     | 329       | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 300       | 2.81%   |
| Intel Wireless 7265                                                     | 278       | 2.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 262       | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 241       | 2.26%   |
| Intel Wi-Fi 6 AX201                                                     | 228       | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 209       | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 202       | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 186       | 1.74%   |
| Intel Centrino Ultimate-N 6300                                          | 173       | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 160       | 1.5%    |
| Intel Wireless 3160                                                     | 156       | 1.46%   |
| Intel Wireless 3165                                                     | 153       | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                           | 153       | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 150       | 1.41%   |
| Intel WiFi Link 5100                                                    | 149       | 1.4%    |
| Intel Wireless-AC 9260                                                  | 148       | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 148       | 1.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 144       | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 137       | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 136       | 1.27%   |
| Intel Centrino Advanced-N 6200                                          | 133       | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 120       | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 120       | 1.12%   |
| Intel Centrino Wireless-N 2230                                          | 116       | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 115       | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 110       | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 92        | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 91        | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 90        | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 87        | 0.82%   |
| Intel Centrino Advanced-N 6235                                          | 85        | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 83        | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 79        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 4248      | 47.86%  |
| Intel                                  | 2506      | 28.23%  |
| Qualcomm Atheros                       | 680       | 7.66%   |
| Broadcom                               | 480       | 5.41%   |
| Marvell Technology Group               | 230       | 2.59%   |
| Broadcom Limited                       | 129       | 1.45%   |
| ASIX Electronics                       | 116       | 1.31%   |
| Lenovo                                 | 109       | 1.23%   |
| Nvidia                                 | 74        | 0.83%   |
| DisplayLink                            | 61        | 0.69%   |
| JMicron Technology                     | 31        | 0.35%   |
| Samsung Electronics                    | 25        | 0.28%   |
| Silicon Integrated Systems [SiS]       | 23        | 0.26%   |
| Huawei Technologies                    | 22        | 0.25%   |
| Hewlett-Packard                        | 19        | 0.21%   |
| Xiaomi                                 | 17        | 0.19%   |
| VIA Technologies                       | 13        | 0.15%   |
| Attansic Technology                    | 11        | 0.12%   |
| Apple                                  | 11        | 0.12%   |
| Google                                 | 9         | 0.1%    |
| TP-Link                                | 8         | 0.09%   |
| Qualcomm                               | 5         | 0.06%   |
| Microchip Technology                   | 5         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.05%   |
| HMD Global                             | 4         | 0.05%   |
| ULi Electronics                        | 3         | 0.03%   |
| T & A Mobile Phones                    | 3         | 0.03%   |
| OPPO Electronics                       | 3         | 0.03%   |
| MosChip Semiconductor                  | 3         | 0.03%   |
| MediaTek                               | 3         | 0.03%   |
| ICS Advent                             | 3         | 0.03%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.02%   |
| Davicom Semiconductor                  | 2         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.01%   |
| Research In Motion                     | 1         | 0.01%   |
| Promise Technology                     | 1         | 0.01%   |
| NetGear                                | 1         | 0.01%   |
| National Semiconductor                 | 1         | 0.01%   |
| Motorola PCS                           | 1         | 0.01%   |
| Microsoft                              | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 3103      | 34.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 616       | 6.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 579       | 6.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 442       | 4.93%   |
| Intel 82577LM Gigabit Network Connection                                       | 174       | 1.94%   |
| Intel Ethernet Connection I219-LM                                              | 157       | 1.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 155       | 1.73%   |
| Intel Ethernet Connection I217-LM                                              | 135       | 1.5%    |
| Intel 82567LM Gigabit Network Connection                                       | 135       | 1.5%    |
| Intel Ethernet Connection I218-LM                                              | 131       | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                                          | 124       | 1.38%   |
| Intel Ethernet Connection (4) I219-V                                           | 123       | 1.37%   |
| Intel Ethernet Connection (3) I218-LM                                          | 115       | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 104       | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 98        | 1.09%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 74        | 0.82%   |
| Intel Ethernet Connection I219-V                                               | 74        | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 74        | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 68        | 0.76%   |
| Intel 82579V Gigabit Network Connection                                        | 66        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                           | 62        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 54        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 54        | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 54        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 53        | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 50        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                          | 49        | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 46        | 0.51%   |
| Intel 82566MM Gigabit Network Connection                                       | 46        | 0.51%   |
| Realtek RTL8125 2.5GbE Controller                                              | 45        | 0.5%    |
| Nvidia MCP79 Ethernet                                                          | 45        | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 45        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                                          | 44        | 0.49%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 43        | 0.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 42        | 0.47%   |
| Intel Ethernet Connection (10) I219-V                                          | 42        | 0.47%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 40        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 39        | 0.43%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 39        | 0.43%   |
| Intel Ethernet Connection (5) I219-LM                                          | 36        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9887      | 52.52%  |
| Ethernet | 8502      | 45.16%  |
| Modem    | 421       | 2.24%   |
| Unknown  | 16        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7925      | 73.25%  |
| Ethernet | 2893      | 26.74%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 7810      | 77.54%  |
| 1     | 2050      | 20.35%  |
| 0     | 120       | 1.19%   |
| 3     | 89        | 0.88%   |
| 4     | 2         | 0.02%   |
| 5     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 6743      | 64.94%  |
| Yes  | 3640      | 35.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3668      | 48.43%  |
| Realtek Semiconductor           | 843       | 11.13%  |
| Broadcom                        | 545       | 7.2%    |
| Qualcomm Atheros Communications | 414       | 5.47%   |
| Foxconn / Hon Hai               | 369       | 4.87%   |
| Lite-On Technology              | 368       | 4.86%   |
| IMC Networks                    | 322       | 4.25%   |
| Apple                           | 213       | 2.81%   |
| Dell                            | 187       | 2.47%   |
| Cambridge Silicon Radio         | 156       | 2.06%   |
| Hewlett-Packard                 | 100       | 1.32%   |
| Toshiba                         | 73        | 0.96%   |
| Realtek                         | 59        | 0.78%   |
| Foxconn International           | 44        | 0.58%   |
| ASUSTek Computer                | 35        | 0.46%   |
| Alps Electric                   | 32        | 0.42%   |
| Askey Computer                  | 31        | 0.41%   |
| Ralink                          | 23        | 0.3%    |
| Taiyo Yuden                     | 18        | 0.24%   |
| Chicony Electronics             | 13        | 0.17%   |
| USI                             | 9         | 0.12%   |
| Ralink Technology               | 9         | 0.12%   |
| Qcom                            | 7         | 0.09%   |
| Fujitsu                         | 7         | 0.09%   |
| MediaTek                        | 6         | 0.08%   |
| Belkin Components               | 6         | 0.08%   |
| TP-Link                         | 4         | 0.05%   |
| Edimax Technology               | 4         | 0.05%   |
| Syntek                          | 1         | 0.01%   |
| Sitecom Europe                  | 1         | 0.01%   |
| SINO WEALTH                     | 1         | 0.01%   |
| Roper                           | 1         | 0.01%   |
| Micro Star International        | 1         | 0.01%   |
| Logitech                        | 1         | 0.01%   |
| Integrated System Solution      | 1         | 0.01%   |
| Fujitsu Siemens Computers       | 1         | 0.01%   |
| Unknown                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1634      | 21.56%  |
| Intel AX201 Bluetooth                               | 542       | 7.15%   |
| Realtek Bluetooth Radio                             | 514       | 6.78%   |
| Intel AX200 Bluetooth                               | 512       | 6.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 384       | 5.07%   |
| Realtek  Bluetooth 4.2 Adapter                      | 222       | 2.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 181       | 2.39%   |
| IMC Networks Bluetooth Radio                        | 165       | 2.18%   |
| Qualcomm Atheros  Bluetooth Device                  | 164       | 2.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 156       | 2.06%   |
| Broadcom BCM2045B (BDC-2.1)                         | 138       | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 135       | 1.78%   |
| Apple Bluetooth Host Controller                     | 124       | 1.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 117       | 1.54%   |
| Lite-On Bluetooth Device                            | 107       | 1.41%   |
| Foxconn / Hon Hai Bluetooth Device                  | 107       | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 106       | 1.4%    |
| Intel Bluetooth Device                              | 90        | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 79        | 1.04%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 79        | 1.04%   |
| Dell DW375 Bluetooth Module                         | 77        | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 71        | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 71        | 0.94%   |
| Lite-On Atheros AR3012 Bluetooth                    | 68        | 0.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 63        | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 62        | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 61        | 0.8%    |
| Intel AX210 Bluetooth                               | 59        | 0.78%   |
| IMC Networks Bluetooth Device                       | 59        | 0.78%   |
| Realtek 802.11ac WLAN Adapter                       | 57        | 0.75%   |
| Foxconn / Hon Hai BCM20702A0                        | 49        | 0.65%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 49        | 0.65%   |
| Apple Bluetooth USB Host Controller                 | 47        | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 46        | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                    | 46        | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module   | 44        | 0.58%   |
| Broadcom BCM2045 Bluetooth                          | 43        | 0.57%   |
| IMC Networks Wireless_Device                        | 40        | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 39        | 0.51%   |
| Lite-On Wireless_Device                             | 38        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 7934      | 64.53%  |
| AMD                              | 2179      | 17.72%  |
| Nvidia                           | 1287      | 10.47%  |
| Lenovo                           | 123       | 1%      |
| C-Media Electronics              | 99        | 0.81%   |
| GN Netcom                        | 94        | 0.76%   |
| Realtek Semiconductor            | 78        | 0.63%   |
| Logitech                         | 58        | 0.47%   |
| Plantronics                      | 38        | 0.31%   |
| Silicon Integrated Systems [SiS] | 28        | 0.23%   |
| Texas Instruments                | 26        | 0.21%   |
| Hewlett-Packard                  | 23        | 0.19%   |
| JMTek                            | 19        | 0.15%   |
| Focusrite-Novation               | 18        | 0.15%   |
| Generalplus Technology           | 17        | 0.14%   |
| Sennheiser Communications        | 15        | 0.12%   |
| Conexant Systems                 | 15        | 0.12%   |
| VIA Technologies                 | 14        | 0.11%   |
| Razer USA                        | 13        | 0.11%   |
| Creative Technology              | 13        | 0.11%   |
| Kingston Technology              | 12        | 0.1%    |
| RODE Microphones                 | 11        | 0.09%   |
| Apple                            | 9         | 0.07%   |
| DSEA A/S                         | 8         | 0.07%   |
| Dell                             | 8         | 0.07%   |
| SteelSeries ApS                  | 7         | 0.06%   |
| TerraTec Electronic              | 6         | 0.05%   |
| Corsair                          | 6         | 0.05%   |
| Yamaha                           | 5         | 0.04%   |
| No brand                         | 5         | 0.04%   |
| Native Instruments               | 5         | 0.04%   |
| M-Audio                          | 5         | 0.04%   |
| Fujitsu                          | 5         | 0.04%   |
| Blue Microphones                 | 5         | 0.04%   |
| BEHRINGER International          | 5         | 0.04%   |
| SAVITECH                         | 4         | 0.03%   |
| GYROCOM C&C                      | 4         | 0.03%   |
| Cambridge Silicon Radio          | 4         | 0.03%   |
| ULi Electronics                  | 3         | 0.02%   |
| Sony                             | 3         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 1119      | 7.51%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1116      | 7.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 929       | 6.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 714       | 4.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 657       | 4.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 570       | 3.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 561       | 3.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 405       | 2.72%   |
| Intel 8 Series HD Audio Controller                                                                | 403       | 2.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 379       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 355       | 2.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 331       | 2.22%   |
| Intel Broadwell-U Audio Controller                                                                | 319       | 2.14%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 317       | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 314       | 2.11%   |
| Intel Cannon Lake PCH cAVS                                                                        | 292       | 1.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 285       | 1.91%   |
| AMD FCH Azalia Controller                                                                         | 268       | 1.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 233       | 1.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 218       | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 218       | 1.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 196       | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 171       | 1.15%   |
| AMD Kabini HDMI/DP Audio                                                                          | 166       | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 154       | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 149       | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 147       | 0.99%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 142       | 0.95%   |
| Intel CM238 HD Audio Controller                                                                   | 138       | 0.93%   |
| Intel Comet Lake PCH cAVS                                                                         | 134       | 0.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 127       | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 113       | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 110       | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 100       | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 94        | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 92        | 0.62%   |
| AMD High Definition Audio Controller                                                              | 91        | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 88        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 81        | 0.54%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 81        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1964      | 32.31%  |
| SK hynix            | 1393      | 22.92%  |
| Micron Technology   | 716       | 11.78%  |
| Unknown             | 472       | 7.77%   |
| Kingston            | 445       | 7.32%   |
| Crucial             | 268       | 4.41%   |
| Ramaxel Technology  | 169       | 2.78%   |
| Elpida              | 136       | 2.24%   |
| A-DATA Technology   | 85        | 1.4%    |
| Corsair             | 78        | 1.28%   |
| Nanya Technology    | 70        | 1.15%   |
| Unknown (ABCD)      | 60        | 0.99%   |
| G.Skill             | 35        | 0.58%   |
| Unknown             | 25        | 0.41%   |
| Transcend           | 22        | 0.36%   |
| ASint Technology    | 17        | 0.28%   |
| 48spaces            | 11        | 0.18%   |
| Avant               | 9         | 0.15%   |
| GOODRAM             | 8         | 0.13%   |
| Team                | 7         | 0.12%   |
| Toshiba             | 6         | 0.1%    |
| SHARETRONIC         | 6         | 0.1%    |
| CSX                 | 6         | 0.1%    |
| Qimonda             | 5         | 0.08%   |
| Patriot             | 5         | 0.08%   |
| Timetec             | 3         | 0.05%   |
| PNY                 | 3         | 0.05%   |
| Neo Forza           | 3         | 0.05%   |
| Lexar               | 3         | 0.05%   |
| Apacer              | 3         | 0.05%   |
| Unknown (8ECE)      | 2         | 0.03%   |
| GSkill              | 2         | 0.03%   |
| Goldkey             | 2         | 0.03%   |
| GeIL                | 2         | 0.03%   |
| ff                  | 2         | 0.03%   |
| fef5                | 2         | 0.03%   |
| Aeneon              | 2         | 0.03%   |
| 4ea5                | 2         | 0.03%   |
| ZIFEI               | 1         | 0.02%   |
| Wilk                | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 94        | 1.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 86        | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 80        | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 76        | 1.17%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 75        | 1.16%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 69        | 1.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 68        | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 66        | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 63        | 0.97%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 59        | 0.91%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 58        | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 55        | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 55        | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 54        | 0.83%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 52        | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 48        | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 48        | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 47        | 0.72%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 47        | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 46        | 0.71%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 45        | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 44        | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 44        | 0.68%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 41        | 0.63%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 40        | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 38        | 0.59%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 38        | 0.59%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 37        | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 37        | 0.57%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 35        | 0.54%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 35        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 35        | 0.54%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 34        | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 34        | 0.52%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 33        | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 33        | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 33        | 0.51%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 32        | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.49%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 30        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2360      | 45.26%  |
| DDR3    | 1891      | 36.27%  |
| DDR2    | 265       | 5.08%   |
| LPDDR4  | 250       | 4.79%   |
| LPDDR3  | 154       | 2.95%   |
| SDRAM   | 109       | 2.09%   |
| LPDDR5  | 58        | 1.11%   |
| DDR5    | 39        | 0.75%   |
| Unknown | 37        | 0.71%   |
| DDR     | 32        | 0.61%   |
| DRAM    | 19        | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 4685      | 89.31%  |
| Row Of Chips | 453       | 8.64%   |
| Chip         | 65        | 1.24%   |
| DIMM         | 29        | 0.55%   |
| Unknown      | 14        | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 2163      | 38.27%  |
| 4096  | 1657      | 29.32%  |
| 16384 | 793       | 14.03%  |
| 2048  | 676       | 11.96%  |
| 1024  | 173       | 3.06%   |
| 32768 | 159       | 2.81%   |
| 512   | 22        | 0.39%   |
| 256   | 4         | 0.07%   |
| 128   | 4         | 0.07%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 1234      | 22.04%  |
| 2667    | 1087      | 19.41%  |
| 3200    | 969       | 17.3%   |
| 2400    | 372       | 6.64%   |
| 1334    | 325       | 5.8%    |
| 2133    | 237       | 4.23%   |
| 1333    | 223       | 3.98%   |
| Unknown | 151       | 2.7%    |
| 667     | 139       | 2.48%   |
| 1067    | 136       | 2.43%   |
| 4267    | 101       | 1.8%    |
| 1867    | 84        | 1.5%    |
| 800     | 68        | 1.21%   |
| 3266    | 63        | 1.13%   |
| 4199    | 61        | 1.09%   |
| 6400    | 53        | 0.95%   |
| 1066    | 42        | 0.75%   |
| 4800    | 41        | 0.73%   |
| 4266    | 36        | 0.64%   |
| 8400    | 34        | 0.61%   |
| 2048    | 28        | 0.5%    |
| 975     | 28        | 0.5%    |
| 533     | 22        | 0.39%   |
| 1866    | 13        | 0.23%   |
| 3733    | 12        | 0.21%   |
| 333     | 10        | 0.18%   |
| 2933    | 6         | 0.11%   |
| 3000    | 4         | 0.07%   |
| 2267    | 3         | 0.05%   |
| 400     | 3         | 0.05%   |
| 5500    | 2         | 0.04%   |
| 1639    | 2         | 0.04%   |
| 666     | 2         | 0.04%   |
| 266     | 2         | 0.04%   |
| 166     | 2         | 0.04%   |
| 3600    | 1         | 0.02%   |
| 2800    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 200     | 1         | 0.02%   |
| 100     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 58        | 32.58%  |
| Canon                 | 34        | 19.1%   |
| Brother Industries    | 30        | 16.85%  |
| Samsung Electronics   | 20        | 11.24%  |
| Seiko Epson           | 15        | 8.43%   |
| Kyocera               | 7         | 3.93%   |
| Prolific Technology   | 5         | 2.81%   |
| QinHeng Electronics   | 2         | 1.12%   |
| Lexmark International | 2         | 1.12%   |
| Dymo-CoStar           | 2         | 1.12%   |
| STMicroelectronics    | 1         | 0.56%   |
| Oki Data              | 1         | 0.56%   |
| MIIIW                 | 1         | 0.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon PIXMA MX920 Series                                  | 6         | 3.37%   |
| Samsung M2020 Series                                      | 5         | 2.81%   |
| Prolific PL2305 Parallel Port                             | 5         | 2.81%   |
| HP Deskjet 2540 series                                    | 4         | 2.25%   |
| Brother DCP-7055W                                         | 4         | 2.25%   |
| Kyocera Mita FS-820                                       | 3         | 1.69%   |
| HP ENVY 4520 series                                       | 3         | 1.69%   |
| HP Deskjet 2050 J510                                      | 3         | 1.69%   |
| HP Deskjet 1050 J410                                      | 3         | 1.69%   |
| Brother MFC-L3750CDW                                      | 3         | 1.69%   |
| Seiko Epson XP-4100 Series                                | 2         | 1.12%   |
| Seiko Epson WF-2510 Series                                | 2         | 1.12%   |
| Samsung CLX-3300 Series                                   | 2         | 1.12%   |
| QinHeng CH340S                                            | 2         | 1.12%   |
| Lexmark International E360d                               | 2         | 1.12%   |
| Kyocera FS-1030D printer                                  | 2         | 1.12%   |
| HP Officejet 4620 series                                  | 2         | 1.12%   |
| HP LaserJet 200 colorMFP M275nw                           | 2         | 1.12%   |
| HP EWS UPD                                                | 2         | 1.12%   |
| HP ENVY 4500 series                                       | 2         | 1.12%   |
| HP DeskJet 3630 series                                    | 2         | 1.12%   |
| HP DeskJet 2700 series                                    | 2         | 1.12%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 1.12%   |
| HP Deskjet 1000 J110 series                               | 2         | 1.12%   |
| Canon TS700 series                                        | 2         | 1.12%   |
| Canon TR8500 series                                       | 2         | 1.12%   |
| Canon PIXMA MG3600 Series                                 | 2         | 1.12%   |
| Canon Pixma iP4500 Printer                                | 2         | 1.12%   |
| Brother MFC-L2710DW series                                | 2         | 1.12%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.56%   |
| Seiko Epson XP-3100 Series                                | 1         | 0.56%   |
| Seiko Epson XP-2100 Series                                | 1         | 0.56%   |
| Seiko Epson WF-2530 Series                                | 1         | 0.56%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.56%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.56%   |
| Seiko Epson Printer                                       | 1         | 0.56%   |
| Seiko Epson L4260 Series                                  | 1         | 0.56%   |
| Seiko Epson ET-2720 Series                                | 1         | 0.56%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.56%   |
| Seiko Epson Epson Stylus Photo 1500                       | 1         | 0.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 30        | 75%     |
| Seiko Epson                                    | 5         | 12.5%   |
| Siemens Information and Communication Products | 1         | 2.5%    |
| Plustek                                        | 1         | 2.5%    |
| Mustek Systems                                 | 1         | 2.5%    |
| Hewlett-Packard                                | 1         | 2.5%    |
| AGFA-Gevaert NV                                | 1         | 2.5%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Notebooks | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                         | 5         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20                                              | 4         | 10%     |
| Canon CanoScan LiDE 110                                                         | 4         | 10%     |
| Canon CanoScan LIDE 25                                                          | 3         | 7.5%    |
| Canon CanoScan LiDE 90                                                          | 2         | 5%      |
| Canon CanoScan LiDE 500F                                                        | 2         | 5%      |
| Canon CanoScan LiDE 210                                                         | 2         | 5%      |
| Canon CanoScan LiDE 100                                                         | 2         | 5%      |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 2.5%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                         | 1         | 2.5%    |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                         | 1         | 2.5%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                        | 1         | 2.5%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                              | 1         | 2.5%    |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                               | 1         | 2.5%    |
| Plustek OpticPro UT12/16/24 Scanner                                             | 1         | 2.5%    |
| Mustek Systems SNAPSCAN e22                                                     | 1         | 2.5%    |
| HP HP4470C                                                                      | 1         | 2.5%    |
| Canon CanoScan LiDE 600F                                                        | 1         | 2.5%    |
| Canon CanoScan LiDE 60                                                          | 1         | 2.5%    |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                          | 1         | 2.5%    |
| Canon CanoScan LiDE 200                                                         | 1         | 2.5%    |
| Canon CanoScan LiDE 120                                                         | 1         | 2.5%    |
| Canon CanoScan 3200F                                                            | 1         | 2.5%    |
| AGFA-Gevaert NV SnapScan 1212U (?)                                              | 1         | 2.5%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2611      | 30.27%  |
| IMC Networks                           | 798       | 9.25%   |
| Realtek Semiconductor                  | 590       | 6.84%   |
| Microdia                               | 579       | 6.71%   |
| Bison Electronics                      | 484       | 5.61%   |
| Quanta                                 | 418       | 4.85%   |
| Sunplus Innovation Technology          | 386       | 4.48%   |
| Cheng Uei Precision Industry (Foxlink) | 336       | 3.9%    |
| Suyin                                  | 335       | 3.88%   |
| Acer                                   | 298       | 3.46%   |
| Lite-On Technology                     | 223       | 2.59%   |
| Syntek                                 | 197       | 2.28%   |
| Apple                                  | 174       | 2.02%   |
| Logitech                               | 153       | 1.77%   |
| Silicon Motion                         | 117       | 1.36%   |
| Ricoh                                  | 111       | 1.29%   |
| Alcor Micro                            | 110       | 1.28%   |
| Luxvisions Innotech Limited            | 99        | 1.15%   |
| Lenovo                                 | 97        | 1.12%   |
| Z-Star Microelectronics                | 57        | 0.66%   |
| ALi                                    | 56        | 0.65%   |
| Samsung Electronics                    | 37        | 0.43%   |
| Primax Electronics                     | 36        | 0.42%   |
| DigiTech                               | 29        | 0.34%   |
| Importek                               | 27        | 0.31%   |
| Sonix Technology                       | 22        | 0.26%   |
| SunplusIT                              | 20        | 0.23%   |
| Microsoft                              | 18        | 0.21%   |
| Sunplus Technology                     | 15        | 0.17%   |
| Generalplus Technology                 | 14        | 0.16%   |
| Genesys Logic                          | 11        | 0.13%   |
| icSpring                               | 10        | 0.12%   |
| OmniVision Technologies                | 9         | 0.1%    |
| eMPIA Technology                       | 9         | 0.1%    |
| Y Media                                | 8         | 0.09%   |
| Intel                                  | 8         | 0.09%   |
| Creative Technology                    | 7         | 0.08%   |
| Alpha Imaging Technology               | 7         | 0.08%   |
| ARC International                      | 6         | 0.07%   |
| KYE Systems (Mouse Systems)            | 5         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 560       | 6.46%   |
| IMC Networks Integrated Camera                   | 291       | 3.36%   |
| Chicony HD WebCam                                | 276       | 3.19%   |
| Microdia Integrated_Webcam_HD                    | 206       | 2.38%   |
| IMC Networks USB2.0 HD UVC WebCam                | 154       | 1.78%   |
| Realtek Integrated_Webcam_HD                     | 148       | 1.71%   |
| Chicony USB2.0 Camera                            | 137       | 1.58%   |
| Chicony FJ Camera                                | 132       | 1.52%   |
| Syntek Integrated Camera                         | 109       | 1.26%   |
| Acer Integrated Camera                           | 109       | 1.26%   |
| Lite-On Integrated Camera                        | 100       | 1.15%   |
| Bison Integrated Camera                          | 100       | 1.15%   |
| Sunplus HD WebCam                                | 91        | 1.05%   |
| Chicony USB 2.0 Camera                           | 88        | 1.02%   |
| Microdia Integrated Webcam                       | 86        | 0.99%   |
| Quanta HD User Facing                            | 80        | 0.92%   |
| Chicony HP HD Camera                             | 77        | 0.89%   |
| Sunplus Integrated_Webcam_HD                     | 76        | 0.88%   |
| Chicony USB2.0 HD UVC WebCam                     | 76        | 0.88%   |
| Chicony HD User Facing                           | 75        | 0.87%   |
| Bison SunplusIT Integrated Camera                | 73        | 0.84%   |
| Chicony Integrated Camera (1280x720@30)          | 67        | 0.77%   |
| Quanta HP Webcam                                 | 63        | 0.73%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 63        | 0.73%   |
| Realtek USB Camera                               | 62        | 0.72%   |
| Chicony Integrated IR Camera                     | 60        | 0.69%   |
| Chicony HP Webcam                                | 60        | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 59        | 0.68%   |
| Chicony TOSHIBA Web Camera - HD                  | 59        | 0.68%   |
| Apple Built-in iSight                            | 59        | 0.68%   |
| Quanta HP HD Camera                              | 57        | 0.66%   |
| Bison Lenovo EasyCamera                          | 56        | 0.65%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 55        | 0.63%   |
| Bison BisonCam, NB Pro                           | 55        | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 54        | 0.62%   |
| Chicony HP TrueVision HD Camera                  | 50        | 0.58%   |
| Chicony VGA Webcam                               | 49        | 0.57%   |
| Apple FaceTime HD Camera                         | 49        | 0.57%   |
| Realtek Lenovo EasyCamera                        | 48        | 0.55%   |
| Bison Lenovo Integrated Webcam                   | 48        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 683       | 32.1%   |
| Synaptics                          | 545       | 25.61%  |
| Shenzhen Goodix Technology         | 266       | 12.5%   |
| AuthenTec                          | 198       | 9.3%    |
| Upek                               | 160       | 7.52%   |
| LighTuning Technology              | 134       | 6.3%    |
| Elan Microelectronics              | 84        | 3.95%   |
| STMicroelectronics                 | 37        | 1.74%   |
| HOLTEK                             | 10        | 0.47%   |
| Realtek USB2.0 Finger Print Bridge | 7         | 0.33%   |
| Focal-systems.Corp                 | 2         | 0.09%   |
| Samsung Electronics                | 1         | 0.05%   |
| Next Biometrics                    | 1         | 0.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 234       | 11%     |
| Shenzhen Goodix  Fingerprint Device                                        | 165       | 7.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 150       | 7.05%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 134       | 6.3%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 115       | 5.4%    |
| Validity Sensors Synaptics WBDI                                            | 83        | 3.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 82        | 3.85%   |
| AuthenTec AES2810                                                          | 71        | 3.34%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 67        | 3.15%   |
| Shenzhen Goodix Fingerprint Reader                                         | 60        | 2.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 59        | 2.77%   |
| Elan ELAN:Fingerprint                                                      | 51        | 2.4%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 46        | 2.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 45        | 2.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 45        | 2.11%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 43        | 2.02%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 42        | 1.97%   |
| Shenzhen Goodix FingerPrint                                                | 41        | 1.93%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 40        | 1.88%   |
| STMicroelectronics Fingerprint Reader                                      | 37        | 1.74%   |
| Validity Sensors VFS491                                                    | 33        | 1.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 31        | 1.46%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 31        | 1.46%   |
| Elan ELAN:ARM-M4                                                           | 31        | 1.46%   |
| Synaptics Fingerprint reader [HP G6]                                       | 30        | 1.41%   |
| AuthenTec Fingerprint Sensor                                               | 30        | 1.41%   |
| AuthenTec AES1600                                                          | 30        | 1.41%   |
| LighTuning Fingerprint Reader                                              | 29        | 1.36%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 27        | 1.27%   |
| Synaptics UWP WBDI                                                         | 24        | 1.13%   |
| Unknown                                                                    | 22        | 1.03%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 20        | 0.94%   |
| Validity Sensors Fingerprint scanner                                       | 19        | 0.89%   |
| Synaptics UWP WBDI Device                                                  | 17        | 0.8%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 15        | 0.7%    |
| Synaptics  WBDI                                                            | 14        | 0.66%   |
| Synaptics WBDI Device                                                      | 13        | 0.61%   |
| Synaptics WBDI                                                             | 13        | 0.61%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 12        | 0.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 11        | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 519       | 40.77%  |
| Broadcom                  | 388       | 30.48%  |
| O2 Micro                  | 119       | 9.35%   |
| Lenovo                    | 109       | 8.56%   |
| Upek                      | 78        | 6.13%   |
| Gemalto (was Gemplus)     | 16        | 1.26%   |
| Yubico.com                | 12        | 0.94%   |
| OmniKey                   | 7         | 0.55%   |
| Clay Logic                | 6         | 0.47%   |
| SCM Microsystems          | 4         | 0.31%   |
| Reiner SCT Kartensysteme  | 4         | 0.31%   |
| Cherry                    | 3         | 0.24%   |
| NXP Semiconductors        | 2         | 0.16%   |
| Realtek Semiconductor     | 1         | 0.08%   |
| Purism, SPC               | 1         | 0.08%   |
| Microchip Technology      | 1         | 0.08%   |
| Kobil Systems             | 1         | 0.08%   |
| In Focus Systems          | 1         | 0.08%   |
| Fujitsu Siemens Computers | 1         | 0.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 519       | 40.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 158       | 12.41%  |
| Lenovo Integrated Smart Card Reader                                          | 109       | 8.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 107       | 8.41%   |
| Broadcom 5880                                                                | 86        | 6.76%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 78        | 6.13%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 77        | 6.05%   |
| Broadcom 58200                                                               | 61        | 4.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 12        | 0.94%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 9         | 0.71%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 9         | 0.71%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 0.55%   |
| Clay Logic Nitrokey Pro                                                      | 6         | 0.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 6         | 0.47%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.24%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 3         | 0.24%   |
| OmniKey CardMan 4321                                                         | 3         | 0.24%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 3         | 0.24%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.16%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.16%   |
| NXP Semiconductors PR533                                                     | 2         | 0.16%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.08%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.08%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.08%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.08%   |
| Purism, SPC Librem Key                                                       | 1         | 0.08%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.08%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.08%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.08%   |
| Kobil Systems Smart Token                                                    | 1         | 0.08%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.08%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 5857      | 56.64%  |
| 1     | 3313      | 32.04%  |
| 2     | 939       | 9.08%   |
| 3     | 172       | 1.66%   |
| 4     | 35        | 0.34%   |
| 5     | 17        | 0.16%   |
| 6     | 4         | 0.04%   |
| 7     | 3         | 0.03%   |
| 9     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 2101      | 36.4%   |
| Chipcard                 | 1136      | 19.68%  |
| Graphics card            | 973       | 16.86%  |
| Net/wireless             | 537       | 9.3%    |
| Multimedia controller    | 268       | 4.64%   |
| Camera                   | 146       | 2.53%   |
| Storage                  | 144       | 2.49%   |
| Communication controller | 114       | 1.98%   |
| Card reader              | 91        | 1.58%   |
| Bluetooth                | 91        | 1.58%   |
| Sound                    | 45        | 0.78%   |
| Modem                    | 44        | 0.76%   |
| Net/ethernet             | 31        | 0.54%   |
| Network                  | 17        | 0.29%   |
| Flash memory             | 11        | 0.19%   |
| Unassigned class         | 5         | 0.09%   |
| Storage/ide              | 5         | 0.09%   |
| Firewire controller      | 5         | 0.09%   |
| Dvb card                 | 3         | 0.05%   |
| Storage/raid             | 2         | 0.03%   |
| Tv card                  | 1         | 0.02%   |
| Storage/nvme             | 1         | 0.02%   |
| Storage/ata              | 1         | 0.02%   |


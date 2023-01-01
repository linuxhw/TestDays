SteamOS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for SteamOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/SteamOS/Desktop/README.md) and [notebooks](/Dist/SteamOS/Notebook/README.md).

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

Total: 663

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Valve         | Jupiter                     | Notebook    | [97da60caa9](https://linux-hardware.org/?probe=97da60caa9) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [1922673e86](https://linux-hardware.org/?probe=1922673e86) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [b5b95e62a1](https://linux-hardware.org/?probe=b5b95e62a1) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [206fed6963](https://linux-hardware.org/?probe=206fed6963) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [61cb7375d1](https://linux-hardware.org/?probe=61cb7375d1) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [294144217a](https://linux-hardware.org/?probe=294144217a) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d66944e019](https://linux-hardware.org/?probe=d66944e019) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [7efd41e9e3](https://linux-hardware.org/?probe=7efd41e9e3) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d35711a607](https://linux-hardware.org/?probe=d35711a607) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [617508d444](https://linux-hardware.org/?probe=617508d444) | Dec 30, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [d8b5801637](https://linux-hardware.org/?probe=d8b5801637) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [ba8c4aff6e](https://linux-hardware.org/?probe=ba8c4aff6e) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [6723dd2f21](https://linux-hardware.org/?probe=6723dd2f21) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [0842d26251](https://linux-hardware.org/?probe=0842d26251) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [d91b55f9f1](https://linux-hardware.org/?probe=d91b55f9f1) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [6201ddc028](https://linux-hardware.org/?probe=6201ddc028) | Dec 30, 2022 |
| Anbernic      | Win600                      | Notebook    | [db576ded28](https://linux-hardware.org/?probe=db576ded28) | Dec 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [135a0237fc](https://linux-hardware.org/?probe=135a0237fc) | Dec 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [a89e87f342](https://linux-hardware.org/?probe=a89e87f342) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [08161cc2cd](https://linux-hardware.org/?probe=08161cc2cd) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [42288a62eb](https://linux-hardware.org/?probe=42288a62eb) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [bcdce3240d](https://linux-hardware.org/?probe=bcdce3240d) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [db0586ef7b](https://linux-hardware.org/?probe=db0586ef7b) | Dec 27, 2022 |
| Teclast       | TbooK 16 Power              | Tablet      | [c8a0dcd956](https://linux-hardware.org/?probe=c8a0dcd956) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [a1ab930dc6](https://linux-hardware.org/?probe=a1ab930dc6) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [d244a4aa10](https://linux-hardware.org/?probe=d244a4aa10) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [894e79d316](https://linux-hardware.org/?probe=894e79d316) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [488d26f3e8](https://linux-hardware.org/?probe=488d26f3e8) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [add22bd3b7](https://linux-hardware.org/?probe=add22bd3b7) | Dec 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c516dc209](https://linux-hardware.org/?probe=1c516dc209) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [32b2d1e76f](https://linux-hardware.org/?probe=32b2d1e76f) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [b0805a1b7c](https://linux-hardware.org/?probe=b0805a1b7c) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [fff4225748](https://linux-hardware.org/?probe=fff4225748) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [bb4ffda53d](https://linux-hardware.org/?probe=bb4ffda53d) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9811949dd](https://linux-hardware.org/?probe=e9811949dd) | Dec 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8194c72bb9](https://linux-hardware.org/?probe=8194c72bb9) | Dec 25, 2022 |
| Anbernic      | Win600                      | Notebook    | [f7759a13d8](https://linux-hardware.org/?probe=f7759a13d8) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [1aae0084d4](https://linux-hardware.org/?probe=1aae0084d4) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [f30e8d06be](https://linux-hardware.org/?probe=f30e8d06be) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [10e4624475](https://linux-hardware.org/?probe=10e4624475) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [91be8cc560](https://linux-hardware.org/?probe=91be8cc560) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [f8ff1f6342](https://linux-hardware.org/?probe=f8ff1f6342) | Dec 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [003a215a22](https://linux-hardware.org/?probe=003a215a22) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [5b87445985](https://linux-hardware.org/?probe=5b87445985) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [1f016d2cf5](https://linux-hardware.org/?probe=1f016d2cf5) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [f500094797](https://linux-hardware.org/?probe=f500094797) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [a38f241e2e](https://linux-hardware.org/?probe=a38f241e2e) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [91952198ca](https://linux-hardware.org/?probe=91952198ca) | Dec 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [934295d2a1](https://linux-hardware.org/?probe=934295d2a1) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [87476c80d3](https://linux-hardware.org/?probe=87476c80d3) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [5ba4679f20](https://linux-hardware.org/?probe=5ba4679f20) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0bea978cf7](https://linux-hardware.org/?probe=0bea978cf7) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [81b966f449](https://linux-hardware.org/?probe=81b966f449) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [90331ea7da](https://linux-hardware.org/?probe=90331ea7da) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [9a358caee7](https://linux-hardware.org/?probe=9a358caee7) | Dec 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [0c29352a52](https://linux-hardware.org/?probe=0c29352a52) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [74518c805f](https://linux-hardware.org/?probe=74518c805f) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [dc2e1253e8](https://linux-hardware.org/?probe=dc2e1253e8) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f061a6d8d](https://linux-hardware.org/?probe=2f061a6d8d) | Dec 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [51f420480a](https://linux-hardware.org/?probe=51f420480a) | Dec 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [c50891856e](https://linux-hardware.org/?probe=c50891856e) | Dec 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [154e9217e5](https://linux-hardware.org/?probe=154e9217e5) | Dec 19, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [59bf36837d](https://linux-hardware.org/?probe=59bf36837d) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [b62a6e3e64](https://linux-hardware.org/?probe=b62a6e3e64) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c513daaf3](https://linux-hardware.org/?probe=9c513daaf3) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [5fee494e26](https://linux-hardware.org/?probe=5fee494e26) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [a560caaec5](https://linux-hardware.org/?probe=a560caaec5) | Dec 17, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [d5279b915a](https://linux-hardware.org/?probe=d5279b915a) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [d47eae36fe](https://linux-hardware.org/?probe=d47eae36fe) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [26aae3342c](https://linux-hardware.org/?probe=26aae3342c) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [8d134a7f1e](https://linux-hardware.org/?probe=8d134a7f1e) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [2014e95862](https://linux-hardware.org/?probe=2014e95862) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [70f2102c25](https://linux-hardware.org/?probe=70f2102c25) | Dec 16, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [0e70489d5c](https://linux-hardware.org/?probe=0e70489d5c) | Dec 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [bb07a9abda](https://linux-hardware.org/?probe=bb07a9abda) | Dec 16, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [bc3635620b](https://linux-hardware.org/?probe=bc3635620b) | Dec 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [24182862cd](https://linux-hardware.org/?probe=24182862cd) | Dec 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [f89644c711](https://linux-hardware.org/?probe=f89644c711) | Dec 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [db677ea07b](https://linux-hardware.org/?probe=db677ea07b) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [cfe8d55199](https://linux-hardware.org/?probe=cfe8d55199) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f2528fad3](https://linux-hardware.org/?probe=2f2528fad3) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [9330717977](https://linux-hardware.org/?probe=9330717977) | Dec 14, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [39a9464c10](https://linux-hardware.org/?probe=39a9464c10) | Dec 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [e5d3f1d216](https://linux-hardware.org/?probe=e5d3f1d216) | Dec 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [a2f1af21a0](https://linux-hardware.org/?probe=a2f1af21a0) | Dec 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [a505c76dfa](https://linux-hardware.org/?probe=a505c76dfa) | Dec 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [008a4d9a91](https://linux-hardware.org/?probe=008a4d9a91) | Dec 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [5236eb1349](https://linux-hardware.org/?probe=5236eb1349) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [6d937728a7](https://linux-hardware.org/?probe=6d937728a7) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [708d1f0ed9](https://linux-hardware.org/?probe=708d1f0ed9) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [ce3ee9584d](https://linux-hardware.org/?probe=ce3ee9584d) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb1fa1afb7](https://linux-hardware.org/?probe=eb1fa1afb7) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [0dcaa4653d](https://linux-hardware.org/?probe=0dcaa4653d) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [fae62b5114](https://linux-hardware.org/?probe=fae62b5114) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [26c1e67dff](https://linux-hardware.org/?probe=26c1e67dff) | Dec 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [e143b181a1](https://linux-hardware.org/?probe=e143b181a1) | Dec 11, 2022 |
| ASUSTek       | M80CJ-O                     | Desktop     | [2375dfe19f](https://linux-hardware.org/?probe=2375dfe19f) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [71cc18156c](https://linux-hardware.org/?probe=71cc18156c) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [dd762c59e0](https://linux-hardware.org/?probe=dd762c59e0) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [a863b95a85](https://linux-hardware.org/?probe=a863b95a85) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e314d59ee](https://linux-hardware.org/?probe=1e314d59ee) | Dec 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [8a3cf19a14](https://linux-hardware.org/?probe=8a3cf19a14) | Dec 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [d41bef1f84](https://linux-hardware.org/?probe=d41bef1f84) | Dec 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [bb28de043b](https://linux-hardware.org/?probe=bb28de043b) | Dec 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [9fc6ea26bb](https://linux-hardware.org/?probe=9fc6ea26bb) | Dec 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [70cd36710e](https://linux-hardware.org/?probe=70cd36710e) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [6fcb4cb441](https://linux-hardware.org/?probe=6fcb4cb441) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [a609c3558a](https://linux-hardware.org/?probe=a609c3558a) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [f8d6f4c18b](https://linux-hardware.org/?probe=f8d6f4c18b) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [19f5d58b52](https://linux-hardware.org/?probe=19f5d58b52) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [989c933ecf](https://linux-hardware.org/?probe=989c933ecf) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [69e8f9815d](https://linux-hardware.org/?probe=69e8f9815d) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [dfbfb35d21](https://linux-hardware.org/?probe=dfbfb35d21) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [13c990586f](https://linux-hardware.org/?probe=13c990586f) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [6f8cd51355](https://linux-hardware.org/?probe=6f8cd51355) | Dec 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [65ccd1da0e](https://linux-hardware.org/?probe=65ccd1da0e) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [51e2277a91](https://linux-hardware.org/?probe=51e2277a91) | Dec 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8890572a5](https://linux-hardware.org/?probe=d8890572a5) | Dec 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [68e389a838](https://linux-hardware.org/?probe=68e389a838) | Dec 03, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c2c53a959d](https://linux-hardware.org/?probe=c2c53a959d) | Dec 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [f54147a5ba](https://linux-hardware.org/?probe=f54147a5ba) | Dec 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [4f32d4f1c2](https://linux-hardware.org/?probe=4f32d4f1c2) | Dec 02, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3f642a7844](https://linux-hardware.org/?probe=3f642a7844) | Dec 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [ec26a28bff](https://linux-hardware.org/?probe=ec26a28bff) | Dec 01, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f00a357dbe](https://linux-hardware.org/?probe=f00a357dbe) | Nov 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [a9299c074e](https://linux-hardware.org/?probe=a9299c074e) | Nov 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0f40429822](https://linux-hardware.org/?probe=0f40429822) | Nov 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [de1a950876](https://linux-hardware.org/?probe=de1a950876) | Nov 29, 2022 |
| MSI           | 970A-G46                    | Desktop     | [3cd88e88d3](https://linux-hardware.org/?probe=3cd88e88d3) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [637e97b132](https://linux-hardware.org/?probe=637e97b132) | Nov 28, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [8263c8ba6f](https://linux-hardware.org/?probe=8263c8ba6f) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [f0d9943604](https://linux-hardware.org/?probe=f0d9943604) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [81b0ea6c7a](https://linux-hardware.org/?probe=81b0ea6c7a) | Nov 27, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [1d12c5839a](https://linux-hardware.org/?probe=1d12c5839a) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee2852cb0](https://linux-hardware.org/?probe=bee2852cb0) | Nov 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea37f7d713](https://linux-hardware.org/?probe=ea37f7d713) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [caf4a9c4d8](https://linux-hardware.org/?probe=caf4a9c4d8) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [c17d27ef9b](https://linux-hardware.org/?probe=c17d27ef9b) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [0a172d85fd](https://linux-hardware.org/?probe=0a172d85fd) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [5751db0994](https://linux-hardware.org/?probe=5751db0994) | Nov 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [29f6c597e4](https://linux-hardware.org/?probe=29f6c597e4) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [6049221fab](https://linux-hardware.org/?probe=6049221fab) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c3a9fe5ae](https://linux-hardware.org/?probe=4c3a9fe5ae) | Nov 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [575ab984df](https://linux-hardware.org/?probe=575ab984df) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e7b9730a4](https://linux-hardware.org/?probe=1e7b9730a4) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9f2caddf6](https://linux-hardware.org/?probe=e9f2caddf6) | Nov 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [dd6f589d44](https://linux-hardware.org/?probe=dd6f589d44) | Nov 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [c278b19567](https://linux-hardware.org/?probe=c278b19567) | Nov 20, 2022 |
| HP            | 8626                        | Desktop     | [f2098a2414](https://linux-hardware.org/?probe=f2098a2414) | Nov 19, 2022 |
| HP            | 8626                        | Desktop     | [05ebc14932](https://linux-hardware.org/?probe=05ebc14932) | Nov 19, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1d4d49c9e4](https://linux-hardware.org/?probe=1d4d49c9e4) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [c89535828a](https://linux-hardware.org/?probe=c89535828a) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [5932954a14](https://linux-hardware.org/?probe=5932954a14) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [d7c9c529b6](https://linux-hardware.org/?probe=d7c9c529b6) | Nov 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [d008ed40fe](https://linux-hardware.org/?probe=d008ed40fe) | Nov 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [01e0010535](https://linux-hardware.org/?probe=01e0010535) | Nov 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [48916ecbfa](https://linux-hardware.org/?probe=48916ecbfa) | Nov 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [92eb4009f3](https://linux-hardware.org/?probe=92eb4009f3) | Nov 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [0bd1833d8c](https://linux-hardware.org/?probe=0bd1833d8c) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [f90da254ff](https://linux-hardware.org/?probe=f90da254ff) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [0046f0e15d](https://linux-hardware.org/?probe=0046f0e15d) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [649043bb19](https://linux-hardware.org/?probe=649043bb19) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c1a39b012](https://linux-hardware.org/?probe=5c1a39b012) | Nov 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [62e925fd8a](https://linux-hardware.org/?probe=62e925fd8a) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [829b573205](https://linux-hardware.org/?probe=829b573205) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [85ef5eaf43](https://linux-hardware.org/?probe=85ef5eaf43) | Nov 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [54bca16c61](https://linux-hardware.org/?probe=54bca16c61) | Nov 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [34582d82a1](https://linux-hardware.org/?probe=34582d82a1) | Nov 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [6227fbbebb](https://linux-hardware.org/?probe=6227fbbebb) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [2067c76d7b](https://linux-hardware.org/?probe=2067c76d7b) | Nov 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [340ef95fd9](https://linux-hardware.org/?probe=340ef95fd9) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [5673f6f505](https://linux-hardware.org/?probe=5673f6f505) | Nov 08, 2022 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [71a3658f21](https://linux-hardware.org/?probe=71a3658f21) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [020eadb15a](https://linux-hardware.org/?probe=020eadb15a) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [1991a35643](https://linux-hardware.org/?probe=1991a35643) | Nov 08, 2022 |
| GPD           | G1619-04                    | Notebook    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [88af410b70](https://linux-hardware.org/?probe=88af410b70) | Nov 07, 2022 |
| GPD           | G1619-04                    | Notebook    | [ce6d16840e](https://linux-hardware.org/?probe=ce6d16840e) | Nov 07, 2022 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [de347eb300](https://linux-hardware.org/?probe=de347eb300) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [695f4b6a83](https://linux-hardware.org/?probe=695f4b6a83) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [9e7987531b](https://linux-hardware.org/?probe=9e7987531b) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [2cc3a0b5de](https://linux-hardware.org/?probe=2cc3a0b5de) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [df94c19aa6](https://linux-hardware.org/?probe=df94c19aa6) | Nov 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [55420be889](https://linux-hardware.org/?probe=55420be889) | Nov 05, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [a0b134897f](https://linux-hardware.org/?probe=a0b134897f) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [f23e197251](https://linux-hardware.org/?probe=f23e197251) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [946d382a37](https://linux-hardware.org/?probe=946d382a37) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b4f9d04f4d](https://linux-hardware.org/?probe=b4f9d04f4d) | Nov 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [1757bc1f5a](https://linux-hardware.org/?probe=1757bc1f5a) | Nov 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [f6295954bc](https://linux-hardware.org/?probe=f6295954bc) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [13e280e72f](https://linux-hardware.org/?probe=13e280e72f) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [cf9998e9b9](https://linux-hardware.org/?probe=cf9998e9b9) | Nov 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [9d237f0d30](https://linux-hardware.org/?probe=9d237f0d30) | Oct 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [92b732ad9a](https://linux-hardware.org/?probe=92b732ad9a) | Oct 31, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [7712ce88c4](https://linux-hardware.org/?probe=7712ce88c4) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c562a178](https://linux-hardware.org/?probe=d4c562a178) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d381c1626](https://linux-hardware.org/?probe=2d381c1626) | Oct 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [dfc3eee826](https://linux-hardware.org/?probe=dfc3eee826) | Oct 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0405c29890](https://linux-hardware.org/?probe=0405c29890) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [b4ba1b8d5a](https://linux-hardware.org/?probe=b4ba1b8d5a) | Oct 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [127bd00558](https://linux-hardware.org/?probe=127bd00558) | Oct 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [7cc988201b](https://linux-hardware.org/?probe=7cc988201b) | Oct 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [746fdbcdec](https://linux-hardware.org/?probe=746fdbcdec) | Oct 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [088235cbff](https://linux-hardware.org/?probe=088235cbff) | Oct 26, 2022 |
| Google        | Droid                       | Notebook    | [c8e4007ce4](https://linux-hardware.org/?probe=c8e4007ce4) | Oct 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [dc86de125e](https://linux-hardware.org/?probe=dc86de125e) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [98a9dbc46f](https://linux-hardware.org/?probe=98a9dbc46f) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [c12839567e](https://linux-hardware.org/?probe=c12839567e) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ed87cbcfb](https://linux-hardware.org/?probe=6ed87cbcfb) | Oct 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [fe664e172e](https://linux-hardware.org/?probe=fe664e172e) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [1963771551](https://linux-hardware.org/?probe=1963771551) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [e474d0929b](https://linux-hardware.org/?probe=e474d0929b) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e4712d276](https://linux-hardware.org/?probe=6e4712d276) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [719742423c](https://linux-hardware.org/?probe=719742423c) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e696c2b87](https://linux-hardware.org/?probe=3e696c2b87) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [b05efe341f](https://linux-hardware.org/?probe=b05efe341f) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [39c064d0df](https://linux-hardware.org/?probe=39c064d0df) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [998e544711](https://linux-hardware.org/?probe=998e544711) | Oct 22, 2022 |
| ADVANCE       | PS5077                      | Notebook    | [97bfff0fc6](https://linux-hardware.org/?probe=97bfff0fc6) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [13c98e0adc](https://linux-hardware.org/?probe=13c98e0adc) | Oct 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [2582be110d](https://linux-hardware.org/?probe=2582be110d) | Oct 21, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [9485d1e744](https://linux-hardware.org/?probe=9485d1e744) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [7cb825e738](https://linux-hardware.org/?probe=7cb825e738) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea0d3e9186](https://linux-hardware.org/?probe=ea0d3e9186) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [a314a908eb](https://linux-hardware.org/?probe=a314a908eb) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [53e7ae8cd4](https://linux-hardware.org/?probe=53e7ae8cd4) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdca0279e2](https://linux-hardware.org/?probe=bdca0279e2) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [3fada6964f](https://linux-hardware.org/?probe=3fada6964f) | Oct 19, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [59904b8a87](https://linux-hardware.org/?probe=59904b8a87) | Oct 19, 2022 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | Notebook    | [429cfdd3df](https://linux-hardware.org/?probe=429cfdd3df) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e000a30c5](https://linux-hardware.org/?probe=1e000a30c5) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [a52a79aad6](https://linux-hardware.org/?probe=a52a79aad6) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [0a198cb541](https://linux-hardware.org/?probe=0a198cb541) | Oct 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [fb6fa1c746](https://linux-hardware.org/?probe=fb6fa1c746) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c513b151b](https://linux-hardware.org/?probe=1c513b151b) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [992d2b539a](https://linux-hardware.org/?probe=992d2b539a) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [0526c93d55](https://linux-hardware.org/?probe=0526c93d55) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [8a5f4671f1](https://linux-hardware.org/?probe=8a5f4671f1) | Oct 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [281229d9ba](https://linux-hardware.org/?probe=281229d9ba) | Oct 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [dde3144879](https://linux-hardware.org/?probe=dde3144879) | Oct 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [7559400f9a](https://linux-hardware.org/?probe=7559400f9a) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [022a7cab63](https://linux-hardware.org/?probe=022a7cab63) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [bd47ebea62](https://linux-hardware.org/?probe=bd47ebea62) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [627b9225cb](https://linux-hardware.org/?probe=627b9225cb) | Oct 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ed7280a28](https://linux-hardware.org/?probe=9ed7280a28) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d38b191e7](https://linux-hardware.org/?probe=2d38b191e7) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [e5f2c8aaae](https://linux-hardware.org/?probe=e5f2c8aaae) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [261a0464f4](https://linux-hardware.org/?probe=261a0464f4) | Oct 14, 2022 |
| AZW           | MINI S                      | Notebook    | [d12969169f](https://linux-hardware.org/?probe=d12969169f) | Oct 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [cb0355ddf3](https://linux-hardware.org/?probe=cb0355ddf3) | Oct 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [ec6c38cc2e](https://linux-hardware.org/?probe=ec6c38cc2e) | Oct 13, 2022 |
| HP            | 8433 11                     | Desktop     | [fed45efc8d](https://linux-hardware.org/?probe=fed45efc8d) | Oct 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [62bdf474b3](https://linux-hardware.org/?probe=62bdf474b3) | Oct 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [6da0b199d1](https://linux-hardware.org/?probe=6da0b199d1) | Oct 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [c06c56de15](https://linux-hardware.org/?probe=c06c56de15) | Oct 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c324f424d](https://linux-hardware.org/?probe=4c324f424d) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2e1db47b63](https://linux-hardware.org/?probe=2e1db47b63) | Oct 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [a5c71515b9](https://linux-hardware.org/?probe=a5c71515b9) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb5a512250](https://linux-hardware.org/?probe=eb5a512250) | Oct 09, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [9873ba1845](https://linux-hardware.org/?probe=9873ba1845) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [34b991043f](https://linux-hardware.org/?probe=34b991043f) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [c5c31bcc13](https://linux-hardware.org/?probe=c5c31bcc13) | Oct 08, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [f2b2df8e8c](https://linux-hardware.org/?probe=f2b2df8e8c) | Oct 08, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [b161e7fe73](https://linux-hardware.org/?probe=b161e7fe73) | Oct 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [30d44ab77b](https://linux-hardware.org/?probe=30d44ab77b) | Oct 08, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [4bea37497e](https://linux-hardware.org/?probe=4bea37497e) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d8b46d523](https://linux-hardware.org/?probe=2d8b46d523) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [e064c0c3be](https://linux-hardware.org/?probe=e064c0c3be) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [ee7a8c8340](https://linux-hardware.org/?probe=ee7a8c8340) | Oct 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [1ebf39c097](https://linux-hardware.org/?probe=1ebf39c097) | Oct 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c1c51b96ef](https://linux-hardware.org/?probe=c1c51b96ef) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [8dcc3b36a0](https://linux-hardware.org/?probe=8dcc3b36a0) | Oct 06, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [2e6852099a](https://linux-hardware.org/?probe=2e6852099a) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [28900801aa](https://linux-hardware.org/?probe=28900801aa) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [9222d376ab](https://linux-hardware.org/?probe=9222d376ab) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [4905b59499](https://linux-hardware.org/?probe=4905b59499) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [64f5b28613](https://linux-hardware.org/?probe=64f5b28613) | Oct 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [641bcdd8c5](https://linux-hardware.org/?probe=641bcdd8c5) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [2f421c5aa6](https://linux-hardware.org/?probe=2f421c5aa6) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [c1206634aa](https://linux-hardware.org/?probe=c1206634aa) | Oct 05, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [150cd334ca](https://linux-hardware.org/?probe=150cd334ca) | Oct 05, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [7ac647f707](https://linux-hardware.org/?probe=7ac647f707) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [9dd9e70e1f](https://linux-hardware.org/?probe=9dd9e70e1f) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [70f65d68fc](https://linux-hardware.org/?probe=70f65d68fc) | Oct 04, 2022 |
| AOKZOE        | A1 AR07                     | Tablet      | [2163cddbe4](https://linux-hardware.org/?probe=2163cddbe4) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [aee559f8bf](https://linux-hardware.org/?probe=aee559f8bf) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [4bc40da6ce](https://linux-hardware.org/?probe=4bc40da6ce) | Oct 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [047b9291b1](https://linux-hardware.org/?probe=047b9291b1) | Oct 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [6bc437ef3d](https://linux-hardware.org/?probe=6bc437ef3d) | Oct 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [c411f31824](https://linux-hardware.org/?probe=c411f31824) | Oct 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [e051d6a0a9](https://linux-hardware.org/?probe=e051d6a0a9) | Oct 02, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f5e8b6c1eb](https://linux-hardware.org/?probe=f5e8b6c1eb) | Oct 02, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [8e5a2bb3a6](https://linux-hardware.org/?probe=8e5a2bb3a6) | Oct 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [5692645981](https://linux-hardware.org/?probe=5692645981) | Oct 02, 2022 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [3e25da0356](https://linux-hardware.org/?probe=3e25da0356) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [12f0d9358a](https://linux-hardware.org/?probe=12f0d9358a) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ea6c15d28](https://linux-hardware.org/?probe=9ea6c15d28) | Oct 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [dab0a00c02](https://linux-hardware.org/?probe=dab0a00c02) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [4d1b722861](https://linux-hardware.org/?probe=4d1b722861) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9737fcadf](https://linux-hardware.org/?probe=e9737fcadf) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [5e7ec518d4](https://linux-hardware.org/?probe=5e7ec518d4) | Sep 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [a031955ffb](https://linux-hardware.org/?probe=a031955ffb) | Sep 30, 2022 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [5746aa7609](https://linux-hardware.org/?probe=5746aa7609) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [66731152dd](https://linux-hardware.org/?probe=66731152dd) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [679b3600fa](https://linux-hardware.org/?probe=679b3600fa) | Sep 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [92b774ed77](https://linux-hardware.org/?probe=92b774ed77) | Sep 29, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [46e48bc4c1](https://linux-hardware.org/?probe=46e48bc4c1) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| GPD           | G1619-04                    | Notebook    | [9e99ae15fb](https://linux-hardware.org/?probe=9e99ae15fb) | Sep 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [9a2af6352a](https://linux-hardware.org/?probe=9a2af6352a) | Sep 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [0f1c8fad1c](https://linux-hardware.org/?probe=0f1c8fad1c) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3305d9bff](https://linux-hardware.org/?probe=c3305d9bff) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8c94cd9bd3](https://linux-hardware.org/?probe=8c94cd9bd3) | Sep 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [315719a312](https://linux-hardware.org/?probe=315719a312) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [f5183f3eed](https://linux-hardware.org/?probe=f5183f3eed) | Sep 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ddd668003](https://linux-hardware.org/?probe=6ddd668003) | Sep 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [b70be12594](https://linux-hardware.org/?probe=b70be12594) | Sep 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [5d02471757](https://linux-hardware.org/?probe=5d02471757) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [d03b845c90](https://linux-hardware.org/?probe=d03b845c90) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca6d2abcd9](https://linux-hardware.org/?probe=ca6d2abcd9) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b88f458d2](https://linux-hardware.org/?probe=0b88f458d2) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [ce15d6d4bb](https://linux-hardware.org/?probe=ce15d6d4bb) | Sep 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [f9230d9e82](https://linux-hardware.org/?probe=f9230d9e82) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [a39be03b34](https://linux-hardware.org/?probe=a39be03b34) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [7bc45b1077](https://linux-hardware.org/?probe=7bc45b1077) | Sep 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [721ede2e11](https://linux-hardware.org/?probe=721ede2e11) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [83ed33f7e6](https://linux-hardware.org/?probe=83ed33f7e6) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [e60653a4c7](https://linux-hardware.org/?probe=e60653a4c7) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [090e33f643](https://linux-hardware.org/?probe=090e33f643) | Sep 20, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [8d8440548e](https://linux-hardware.org/?probe=8d8440548e) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [919ae4fe6c](https://linux-hardware.org/?probe=919ae4fe6c) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [5ed6e54010](https://linux-hardware.org/?probe=5ed6e54010) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [84051314e8](https://linux-hardware.org/?probe=84051314e8) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [de74f87be5](https://linux-hardware.org/?probe=de74f87be5) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [8273135785](https://linux-hardware.org/?probe=8273135785) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [4b802a9fe9](https://linux-hardware.org/?probe=4b802a9fe9) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [e65c41605f](https://linux-hardware.org/?probe=e65c41605f) | Sep 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [b667f00856](https://linux-hardware.org/?probe=b667f00856) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [221fd3ae1c](https://linux-hardware.org/?probe=221fd3ae1c) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [c4dd2bf91f](https://linux-hardware.org/?probe=c4dd2bf91f) | Sep 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [0db4b64dcd](https://linux-hardware.org/?probe=0db4b64dcd) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [4540c4e930](https://linux-hardware.org/?probe=4540c4e930) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [47ac328960](https://linux-hardware.org/?probe=47ac328960) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [28a40721a8](https://linux-hardware.org/?probe=28a40721a8) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [f686754b27](https://linux-hardware.org/?probe=f686754b27) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [9adc000021](https://linux-hardware.org/?probe=9adc000021) | Sep 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9493095ab1](https://linux-hardware.org/?probe=9493095ab1) | Sep 15, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9919cebdfe](https://linux-hardware.org/?probe=9919cebdfe) | Sep 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9817414c4e](https://linux-hardware.org/?probe=9817414c4e) | Sep 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [0925a55100](https://linux-hardware.org/?probe=0925a55100) | Sep 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2b312e843](https://linux-hardware.org/?probe=b2b312e843) | Sep 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [694e9a60ad](https://linux-hardware.org/?probe=694e9a60ad) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [438ec3fe41](https://linux-hardware.org/?probe=438ec3fe41) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| MSI           | 970A-G46                    | Desktop     | [5f7482fe88](https://linux-hardware.org/?probe=5f7482fe88) | Sep 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c95ed7c92](https://linux-hardware.org/?probe=2c95ed7c92) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [17eea2b641](https://linux-hardware.org/?probe=17eea2b641) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df4850fe](https://linux-hardware.org/?probe=48df4850fe) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [c63b3ff391](https://linux-hardware.org/?probe=c63b3ff391) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [cb5ede9c6f](https://linux-hardware.org/?probe=cb5ede9c6f) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [9fce9d23c8](https://linux-hardware.org/?probe=9fce9d23c8) | Sep 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d45c49609](https://linux-hardware.org/?probe=7d45c49609) | Sep 08, 2022 |
| Microsoft     | Surface Pro 8               | Tablet      | [e450ddeea6](https://linux-hardware.org/?probe=e450ddeea6) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | Notebook    | [041c6dac05](https://linux-hardware.org/?probe=041c6dac05) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3c4865fc8c](https://linux-hardware.org/?probe=3c4865fc8c) | Sep 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [1669287cbb](https://linux-hardware.org/?probe=1669287cbb) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [47baad2eed](https://linux-hardware.org/?probe=47baad2eed) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb15307366](https://linux-hardware.org/?probe=eb15307366) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [8cd669599d](https://linux-hardware.org/?probe=8cd669599d) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [090d406ac3](https://linux-hardware.org/?probe=090d406ac3) | Sep 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [3f0eb4cd71](https://linux-hardware.org/?probe=3f0eb4cd71) | Sep 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [04c7e44198](https://linux-hardware.org/?probe=04c7e44198) | Sep 05, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fc14fdd03a](https://linux-hardware.org/?probe=fc14fdd03a) | Sep 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [584ea1ade0](https://linux-hardware.org/?probe=584ea1ade0) | Sep 05, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [2d99107aa6](https://linux-hardware.org/?probe=2d99107aa6) | Sep 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [bf34e42b02](https://linux-hardware.org/?probe=bf34e42b02) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [f9942c8a6b](https://linux-hardware.org/?probe=f9942c8a6b) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3ac55201b6](https://linux-hardware.org/?probe=3ac55201b6) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [93771f5a6b](https://linux-hardware.org/?probe=93771f5a6b) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [08728d3dc1](https://linux-hardware.org/?probe=08728d3dc1) | Sep 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [a8038907ed](https://linux-hardware.org/?probe=a8038907ed) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [f35ef3a2e1](https://linux-hardware.org/?probe=f35ef3a2e1) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [e12248df34](https://linux-hardware.org/?probe=e12248df34) | Sep 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [f4142b2ff8](https://linux-hardware.org/?probe=f4142b2ff8) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [c0094f39c5](https://linux-hardware.org/?probe=c0094f39c5) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [b3b1ffd7ff](https://linux-hardware.org/?probe=b3b1ffd7ff) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [3fdc8df5b2](https://linux-hardware.org/?probe=3fdc8df5b2) | Sep 02, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bdae2c60cd](https://linux-hardware.org/?probe=bdae2c60cd) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [c89533e9a2](https://linux-hardware.org/?probe=c89533e9a2) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [c348c06118](https://linux-hardware.org/?probe=c348c06118) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [5a2483051c](https://linux-hardware.org/?probe=5a2483051c) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b928ad313](https://linux-hardware.org/?probe=0b928ad313) | Aug 31, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1f4a6a9ec3](https://linux-hardware.org/?probe=1f4a6a9ec3) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [dbc549504c](https://linux-hardware.org/?probe=dbc549504c) | Aug 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [1b38f48059](https://linux-hardware.org/?probe=1b38f48059) | Aug 30, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [6d2717b230](https://linux-hardware.org/?probe=6d2717b230) | Aug 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [40b9dd39a6](https://linux-hardware.org/?probe=40b9dd39a6) | Aug 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [ea6506cc93](https://linux-hardware.org/?probe=ea6506cc93) | Aug 30, 2022 |
| MSI           | MS-B9201                    | Desktop     | [b5c80c8c2c](https://linux-hardware.org/?probe=b5c80c8c2c) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [844a0c00e2](https://linux-hardware.org/?probe=844a0c00e2) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [830c22afde](https://linux-hardware.org/?probe=830c22afde) | Aug 29, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [1763ee1dd0](https://linux-hardware.org/?probe=1763ee1dd0) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [43ec7fb445](https://linux-hardware.org/?probe=43ec7fb445) | Aug 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [3848655fce](https://linux-hardware.org/?probe=3848655fce) | Aug 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [9e3df56c3b](https://linux-hardware.org/?probe=9e3df56c3b) | Aug 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [cd6744821b](https://linux-hardware.org/?probe=cd6744821b) | Aug 27, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [521dd85c98](https://linux-hardware.org/?probe=521dd85c98) | Aug 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [8027445785](https://linux-hardware.org/?probe=8027445785) | Aug 26, 2022 |
| Dell          | Precision 7720              | Notebook    | [7fafc0e50b](https://linux-hardware.org/?probe=7fafc0e50b) | Aug 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [447edaff49](https://linux-hardware.org/?probe=447edaff49) | Aug 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [67b791eb17](https://linux-hardware.org/?probe=67b791eb17) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebd183fc4b](https://linux-hardware.org/?probe=ebd183fc4b) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [b74760105e](https://linux-hardware.org/?probe=b74760105e) | Aug 25, 2022 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [663bc0a517](https://linux-hardware.org/?probe=663bc0a517) | Aug 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [5064c9f57b](https://linux-hardware.org/?probe=5064c9f57b) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [fbef109b91](https://linux-hardware.org/?probe=fbef109b91) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [de49ccefa5](https://linux-hardware.org/?probe=de49ccefa5) | Aug 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c88b729d3](https://linux-hardware.org/?probe=4c88b729d3) | Aug 23, 2022 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e934af2a60](https://linux-hardware.org/?probe=e934af2a60) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ba1940016e](https://linux-hardware.org/?probe=ba1940016e) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [161cc0c135](https://linux-hardware.org/?probe=161cc0c135) | Aug 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [078b8e8ff1](https://linux-hardware.org/?probe=078b8e8ff1) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [04b0de9007](https://linux-hardware.org/?probe=04b0de9007) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c25a3bf8a](https://linux-hardware.org/?probe=1c25a3bf8a) | Aug 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [bc83cf9f77](https://linux-hardware.org/?probe=bc83cf9f77) | Aug 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [36124147ef](https://linux-hardware.org/?probe=36124147ef) | Aug 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [d6b92d1aa0](https://linux-hardware.org/?probe=d6b92d1aa0) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [bff4d1ca46](https://linux-hardware.org/?probe=bff4d1ca46) | Aug 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9661c799c9](https://linux-hardware.org/?probe=9661c799c9) | Aug 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [87f3603202](https://linux-hardware.org/?probe=87f3603202) | Aug 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [f0dc30e9f8](https://linux-hardware.org/?probe=f0dc30e9f8) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [af4a593873](https://linux-hardware.org/?probe=af4a593873) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [c395a0f9db](https://linux-hardware.org/?probe=c395a0f9db) | Aug 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [90ac03e747](https://linux-hardware.org/?probe=90ac03e747) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [53429d945b](https://linux-hardware.org/?probe=53429d945b) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [9ab7a2b695](https://linux-hardware.org/?probe=9ab7a2b695) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [2adcfce1c0](https://linux-hardware.org/?probe=2adcfce1c0) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [a5b1950761](https://linux-hardware.org/?probe=a5b1950761) | Aug 14, 2022 |
| MSI           | MS-B9351                    | Desktop     | [fbf08d2d76](https://linux-hardware.org/?probe=fbf08d2d76) | Aug 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [e9f1f10a4c](https://linux-hardware.org/?probe=e9f1f10a4c) | Aug 14, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dcd9be004c](https://linux-hardware.org/?probe=dcd9be004c) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [50596cb93b](https://linux-hardware.org/?probe=50596cb93b) | Aug 13, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [54ea6926a0](https://linux-hardware.org/?probe=54ea6926a0) | Aug 13, 2022 |
| HP            | 2B3E                        | All in one  | [1ba4759f2c](https://linux-hardware.org/?probe=1ba4759f2c) | Aug 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [3a1e95f5d5](https://linux-hardware.org/?probe=3a1e95f5d5) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [b63f9aedab](https://linux-hardware.org/?probe=b63f9aedab) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [822737452b](https://linux-hardware.org/?probe=822737452b) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [9839802d27](https://linux-hardware.org/?probe=9839802d27) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [6b9bfad898](https://linux-hardware.org/?probe=6b9bfad898) | Aug 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [c6e02c54e7](https://linux-hardware.org/?probe=c6e02c54e7) | Aug 11, 2022 |
| HP            | Laptop 14z-fq0000           | Notebook    | [9c62f8d392](https://linux-hardware.org/?probe=9c62f8d392) | Aug 11, 2022 |
| Microsoft     | Surface Pro 8               | Tablet      | [a5f743f641](https://linux-hardware.org/?probe=a5f743f641) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [90e751b5cf](https://linux-hardware.org/?probe=90e751b5cf) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [6223a43fe2](https://linux-hardware.org/?probe=6223a43fe2) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [2cec170e55](https://linux-hardware.org/?probe=2cec170e55) | Aug 10, 2022 |
| AMI           | Unknown                     | Notebook    | [5cee81ed21](https://linux-hardware.org/?probe=5cee81ed21) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [68214f1af2](https://linux-hardware.org/?probe=68214f1af2) | Aug 10, 2022 |
| AMI           | Unknown                     | Notebook    | [7752037bab](https://linux-hardware.org/?probe=7752037bab) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4914b879a](https://linux-hardware.org/?probe=e4914b879a) | Aug 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [a5b1208abc](https://linux-hardware.org/?probe=a5b1208abc) | Aug 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [a50e78265a](https://linux-hardware.org/?probe=a50e78265a) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8ef9609a7](https://linux-hardware.org/?probe=d8ef9609a7) | Aug 07, 2022 |
| Dell          | 00F82W A00                  | Desktop     | [8e74c57731](https://linux-hardware.org/?probe=8e74c57731) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [64a0d92417](https://linux-hardware.org/?probe=64a0d92417) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [b6c7ee76fa](https://linux-hardware.org/?probe=b6c7ee76fa) | Aug 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [6bbc4f3d0a](https://linux-hardware.org/?probe=6bbc4f3d0a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [d15c62e29a](https://linux-hardware.org/?probe=d15c62e29a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [6f76f9d91a](https://linux-hardware.org/?probe=6f76f9d91a) | Aug 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [4403a80bdc](https://linux-hardware.org/?probe=4403a80bdc) | Aug 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [8689254ee7](https://linux-hardware.org/?probe=8689254ee7) | Aug 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [bfddbf1d22](https://linux-hardware.org/?probe=bfddbf1d22) | Aug 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [fdb514a999](https://linux-hardware.org/?probe=fdb514a999) | Aug 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [e4c6300b68](https://linux-hardware.org/?probe=e4c6300b68) | Aug 01, 2022 |
| Gigabyte      | H310M S2V                   | Desktop     | [329d2071a9](https://linux-hardware.org/?probe=329d2071a9) | Aug 01, 2022 |
| GPD           | G1619-02                    | Notebook    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [ee3b662083](https://linux-hardware.org/?probe=ee3b662083) | Jul 30, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [9a18d7476f](https://linux-hardware.org/?probe=9a18d7476f) | Jul 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [225e2c825e](https://linux-hardware.org/?probe=225e2c825e) | Jul 29, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [4a6c9ef157](https://linux-hardware.org/?probe=4a6c9ef157) | Jul 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [dffaa71aed](https://linux-hardware.org/?probe=dffaa71aed) | Jul 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [35608b206c](https://linux-hardware.org/?probe=35608b206c) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [e35fa6e699](https://linux-hardware.org/?probe=e35fa6e699) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [f43cbe28e9](https://linux-hardware.org/?probe=f43cbe28e9) | Jul 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4e4413f9b](https://linux-hardware.org/?probe=d4e4413f9b) | Jul 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [9c34e91c79](https://linux-hardware.org/?probe=9c34e91c79) | Jul 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [b605f923c6](https://linux-hardware.org/?probe=b605f923c6) | Jul 25, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [6b300beb70](https://linux-hardware.org/?probe=6b300beb70) | Jul 25, 2022 |
| ASRock        | A520M-ITX/ac                | Desktop     | [876c779461](https://linux-hardware.org/?probe=876c779461) | Jul 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f2172999c8](https://linux-hardware.org/?probe=f2172999c8) | Jul 24, 2022 |
| ONE-NETBOO... | ONE XPLAYER                 | Tablet      | [ce14e41b96](https://linux-hardware.org/?probe=ce14e41b96) | Jul 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e7b7cb8cd](https://linux-hardware.org/?probe=3e7b7cb8cd) | Jul 23, 2022 |
| Alienware     | m17                         | Notebook    | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [ca07489d53](https://linux-hardware.org/?probe=ca07489d53) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [1860c6d71f](https://linux-hardware.org/?probe=1860c6d71f) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [2d0db23de3](https://linux-hardware.org/?probe=2d0db23de3) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [4aece18875](https://linux-hardware.org/?probe=4aece18875) | Jul 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [44dca72cbb](https://linux-hardware.org/?probe=44dca72cbb) | Jul 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [96af389676](https://linux-hardware.org/?probe=96af389676) | Jul 22, 2022 |
| ASRock        | X570 Extreme4 WiFi ax       | Notebook    | [bc52038c74](https://linux-hardware.org/?probe=bc52038c74) | Jul 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [0cd166bdb1](https://linux-hardware.org/?probe=0cd166bdb1) | Jul 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [02c47a57e5](https://linux-hardware.org/?probe=02c47a57e5) | Jul 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [2c1ad04467](https://linux-hardware.org/?probe=2c1ad04467) | Jul 18, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [7f27efe00e](https://linux-hardware.org/?probe=7f27efe00e) | Jul 17, 2022 |
| HP            | Pavilion 17                 | Notebook    | [722f4eb4a9](https://linux-hardware.org/?probe=722f4eb4a9) | Jul 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [b639365efd](https://linux-hardware.org/?probe=b639365efd) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [eec9897935](https://linux-hardware.org/?probe=eec9897935) | Jul 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4be0d94b4](https://linux-hardware.org/?probe=d4be0d94b4) | Jul 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [d2f117e7f3](https://linux-hardware.org/?probe=d2f117e7f3) | Jul 14, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e157e6d524](https://linux-hardware.org/?probe=e157e6d524) | Jul 14, 2022 |
| AYANEO        | NEXT Pro                    | Tablet      | [12b2ede47c](https://linux-hardware.org/?probe=12b2ede47c) | Jul 12, 2022 |
| AYANEO        | NEXT Pro                    | Tablet      | [4dc9fd4b9e](https://linux-hardware.org/?probe=4dc9fd4b9e) | Jul 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [f7d66c8d35](https://linux-hardware.org/?probe=f7d66c8d35) | Jul 10, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [0c2ea27c49](https://linux-hardware.org/?probe=0c2ea27c49) | Jul 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [98711d54c1](https://linux-hardware.org/?probe=98711d54c1) | Jul 08, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [c3c73948f5](https://linux-hardware.org/?probe=c3c73948f5) | Jul 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3ede093138](https://linux-hardware.org/?probe=3ede093138) | Jul 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [458276506d](https://linux-hardware.org/?probe=458276506d) | Jul 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [663562cc6b](https://linux-hardware.org/?probe=663562cc6b) | Jul 06, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [61eaf99aca](https://linux-hardware.org/?probe=61eaf99aca) | Jul 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [812733dd89](https://linux-hardware.org/?probe=812733dd89) | Jul 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [e640bab55c](https://linux-hardware.org/?probe=e640bab55c) | Jul 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [0bd46afcda](https://linux-hardware.org/?probe=0bd46afcda) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [ac0c161f66](https://linux-hardware.org/?probe=ac0c161f66) | Jul 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [c591d23b4d](https://linux-hardware.org/?probe=c591d23b4d) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [e98c07bc79](https://linux-hardware.org/?probe=e98c07bc79) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [261590e542](https://linux-hardware.org/?probe=261590e542) | Jun 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [7c233f0a07](https://linux-hardware.org/?probe=7c233f0a07) | Jun 29, 2022 |
| HP            | x2 210 G2                   | Tablet      | [812530aed8](https://linux-hardware.org/?probe=812530aed8) | Jun 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [e80815c8d4](https://linux-hardware.org/?probe=e80815c8d4) | Jun 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [e51f5d8645](https://linux-hardware.org/?probe=e51f5d8645) | Jun 26, 2022 |
| Alienware     | 02XRCM A01                  | Desktop     | [c70647bab0](https://linux-hardware.org/?probe=c70647bab0) | Jun 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [b4dd19f939](https://linux-hardware.org/?probe=b4dd19f939) | Jun 25, 2022 |
| AZW           | SER V01                     | Mini pc     | [295a32d26e](https://linux-hardware.org/?probe=295a32d26e) | Jun 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [c9ed3cf311](https://linux-hardware.org/?probe=c9ed3cf311) | Jun 23, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [1a568c2e5f](https://linux-hardware.org/?probe=1a568c2e5f) | Jun 23, 2022 |
| ASUSTek       | Q524UQK                     | Convertible | [fd5f128747](https://linux-hardware.org/?probe=fd5f128747) | Jun 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [9c5777f505](https://linux-hardware.org/?probe=9c5777f505) | Jun 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [213fbe4dd2](https://linux-hardware.org/?probe=213fbe4dd2) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [262a7f0cd4](https://linux-hardware.org/?probe=262a7f0cd4) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [f8722866b2](https://linux-hardware.org/?probe=f8722866b2) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [aa18022bce](https://linux-hardware.org/?probe=aa18022bce) | Jun 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [000682313d](https://linux-hardware.org/?probe=000682313d) | Jun 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [363ab9e4ea](https://linux-hardware.org/?probe=363ab9e4ea) | Jun 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [dd5765a418](https://linux-hardware.org/?probe=dd5765a418) | Jun 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [8e293bb4b1](https://linux-hardware.org/?probe=8e293bb4b1) | Jun 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [ff0ce08944](https://linux-hardware.org/?probe=ff0ce08944) | Jun 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [68a581ae0b](https://linux-hardware.org/?probe=68a581ae0b) | Jun 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [df3f1b5d8f](https://linux-hardware.org/?probe=df3f1b5d8f) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [17406c8741](https://linux-hardware.org/?probe=17406c8741) | Jun 11, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [7ccfe2d3a7](https://linux-hardware.org/?probe=7ccfe2d3a7) | Jun 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [715e914cba](https://linux-hardware.org/?probe=715e914cba) | Jun 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [2fb1bfad12](https://linux-hardware.org/?probe=2fb1bfad12) | Jun 04, 2022 |
| Valve         | Jupiter                     | Notebook    | [322bdc2ce3](https://linux-hardware.org/?probe=322bdc2ce3) | Jun 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [780d6b923a](https://linux-hardware.org/?probe=780d6b923a) | Jun 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b3a08001ed](https://linux-hardware.org/?probe=b3a08001ed) | Jun 01, 2022 |
| ASRock        | B550 PG Velocita            | Desktop     | [0d7f71a24d](https://linux-hardware.org/?probe=0d7f71a24d) | May 30, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [afc161c6fb](https://linux-hardware.org/?probe=afc161c6fb) | May 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [e415de106f](https://linux-hardware.org/?probe=e415de106f) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [0af4b9c805](https://linux-hardware.org/?probe=0af4b9c805) | May 29, 2022 |
| Valve         | Jupiter                     | Notebook    | [06b56d54d4](https://linux-hardware.org/?probe=06b56d54d4) | May 28, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [1e966da4f8](https://linux-hardware.org/?probe=1e966da4f8) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [c716690aa2](https://linux-hardware.org/?probe=c716690aa2) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [43f315aa0c](https://linux-hardware.org/?probe=43f315aa0c) | May 27, 2022 |
| Valve         | Jupiter                     | Notebook    | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [d4bef1e450](https://linux-hardware.org/?probe=d4bef1e450) | May 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b672eefb50](https://linux-hardware.org/?probe=b672eefb50) | May 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [dee0bbedd1](https://linux-hardware.org/?probe=dee0bbedd1) | May 25, 2022 |
| HP            | 8158 A01                    | Mini pc     | [0d32a2b2e3](https://linux-hardware.org/?probe=0d32a2b2e3) | May 24, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [da9b5c2be2](https://linux-hardware.org/?probe=da9b5c2be2) | May 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [c34173715a](https://linux-hardware.org/?probe=c34173715a) | May 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [6ca95b630c](https://linux-hardware.org/?probe=6ca95b630c) | May 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [7d3f9c0a5f](https://linux-hardware.org/?probe=7d3f9c0a5f) | May 23, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [b5d37bf4f2](https://linux-hardware.org/?probe=b5d37bf4f2) | May 22, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fc970670a8](https://linux-hardware.org/?probe=fc970670a8) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [595b06f6c9](https://linux-hardware.org/?probe=595b06f6c9) | May 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [d706d00651](https://linux-hardware.org/?probe=d706d00651) | May 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [317e492fa3](https://linux-hardware.org/?probe=317e492fa3) | May 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [79f6db1d69](https://linux-hardware.org/?probe=79f6db1d69) | May 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [771539d18d](https://linux-hardware.org/?probe=771539d18d) | May 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [19d2c51aa6](https://linux-hardware.org/?probe=19d2c51aa6) | May 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c826aed5e](https://linux-hardware.org/?probe=1c826aed5e) | Apr 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c43342014](https://linux-hardware.org/?probe=4c43342014) | Apr 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [8564bded7f](https://linux-hardware.org/?probe=8564bded7f) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [d761657c3a](https://linux-hardware.org/?probe=d761657c3a) | Apr 21, 2022 |
| Valve         | Jupiter                     | Notebook    | [f2e59fcb97](https://linux-hardware.org/?probe=f2e59fcb97) | Apr 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [4f23fab4fd](https://linux-hardware.org/?probe=4f23fab4fd) | Apr 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [ed07e93435](https://linux-hardware.org/?probe=ed07e93435) | Apr 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [48aacdeee8](https://linux-hardware.org/?probe=48aacdeee8) | Apr 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [6a042646dd](https://linux-hardware.org/?probe=6a042646dd) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [d4c9dba2a1](https://linux-hardware.org/?probe=d4c9dba2a1) | Apr 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [852b6fb53a](https://linux-hardware.org/?probe=852b6fb53a) | Apr 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [6129b15fb5](https://linux-hardware.org/?probe=6129b15fb5) | Apr 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [ec05067a1d](https://linux-hardware.org/?probe=ec05067a1d) | Apr 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [180c84c856](https://linux-hardware.org/?probe=180c84c856) | Apr 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [d181a912af](https://linux-hardware.org/?probe=d181a912af) | Mar 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [0b6a21cf35](https://linux-hardware.org/?probe=0b6a21cf35) | Mar 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [85328e8f3d](https://linux-hardware.org/?probe=85328e8f3d) | Mar 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [023aea75e1](https://linux-hardware.org/?probe=023aea75e1) | Mar 14, 2022 |
| Valve         | Jupiter                     | Notebook    | [c7f6388908](https://linux-hardware.org/?probe=c7f6388908) | Mar 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/SteamOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| SteamOS 3.3.2                | 116       | 21.36%  |
| SteamOS 3.3.1                | 107       | 19.71%  |
| SteamOS 3.3                  | 87        | 16.02%  |
| SteamOS 3.2                  | 59        | 10.87%  |
| SteamOS 3.4                  | 45        | 8.29%   |
| SteamOS Snapshot             | 26        | 4.79%   |
| SteamOS 3.4.2                | 21        | 3.87%   |
| SteamOS 3.3.3                | 14        | 2.58%   |
| SteamOS 3.2 (steamdeck-main) | 14        | 2.58%   |
| SteamOS 3.1                  | 13        | 2.39%   |
| SteamOS 3.4.4                | 10        | 1.84%   |
| SteamOS                      | 10        | 1.84%   |
| SteamOS Rolling              | 9         | 1.66%   |
| SteamOS 3.4.3                | 7         | 1.29%   |
| SteamOS 3.5                  | 4         | 0.74%   |
| SteamOS 4                    | 1         | 0.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SteamOS | 515       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                            | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| 5.13.0-valve21.3-1-neptune                         | 142       | 26.2%   |
| 5.13.0-valve21.1-1-neptune-02211-gc54cda5a36f3     | 110       | 20.3%   |
| 5.13.0-valve15-1-neptune-02197-gf6ec7ad3762a       | 54        | 9.96%   |
| 5.13.0-valve36-1-neptune                           | 38        | 7.01%   |
| 5.13.0-valve21-1-neptune-02209-g2a5bdc1102a0       | 36        | 6.64%   |
| 5.13.0-valve24-1-neptune-02226-g5b8545e4c5a1       | 31        | 5.72%   |
| 5.13.0-valve10.1-2-neptune-dri-02144-g7fffaf925dfb | 24        | 4.43%   |
| 5.13.0-valve10.1-1-neptune-02144-g7fffaf925dfb     | 16        | 2.95%   |
| 5.13.0-valve10.3-1-neptune-02176-g5fe416c4acd8     | 15        | 2.77%   |
| 5.13.0-valve22-1-neptune-02213-gb68995364335       | 12        | 2.21%   |
| 5.13.0-valve31-1-neptune                           | 11        | 2.03%   |
| 5.18.1-arch1_testHoloISO_20220606.1811             | 9         | 1.66%   |
| 5.13.0-valve35-1-neptune                           | 9         | 1.66%   |
| 5.13.0-valve24-1-neptune                           | 7         | 1.29%   |
| 5.13.0-valve21.2-1-neptune                         | 6         | 1.11%   |
| 5.13.0-valve14-1-neptune-02195-g5b0f749d00fa       | 5         | 0.92%   |
| 5.13.0-valve20-1-neptune-02207-gbd986a7e1c7f       | 4         | 0.74%   |
| 5.13.0-valve21-2-neptune-02209-g2a5bdc1102a0       | 3         | 0.55%   |
| 5.15.79-1-lts                                      | 2         | 0.37%   |
| 5.15.60-1-lts                                      | 2         | 0.37%   |
| 5.15.54-1-lts                                      | 2         | 0.37%   |
| 5.13.0-valve23-1-neptune-02219-gf0b4ecc8cab6       | 2         | 0.37%   |
| 6.0.7-zen3-xanmod1-1                               | 1         | 0.18%   |
| 5.16.2-arch1-1                                     | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 501       | 96.72%  |
| 5.18.1  | 9         | 1.74%   |
| 5.15.79 | 2         | 0.39%   |
| 5.15.60 | 2         | 0.39%   |
| 5.15.54 | 2         | 0.39%   |
| 6.0.7   | 1         | 0.19%   |
| 5.16.2  | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 501       | 96.72%  |
| 5.18    | 9         | 1.74%   |
| 5.15    | 6         | 1.16%   |
| 6.0     | 1         | 0.19%   |
| 5.16    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 515       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| KDE5      | 510       | 98.84%  |
| Unknown   | 3         | 0.58%   |
| gamescope | 2         | 0.39%   |
| GNOME     | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 509       | 98.64%  |
| Wayland | 3         | 0.58%   |
| Tty     | 2         | 0.39%   |
| Unknown | 2         | 0.39%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 507       | 98.45%  |
| SDDM    | 8         | 1.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_US        | 440       | 85.11%  |
| en_GB        | 12        | 2.32%   |
| de_DE        | 12        | 2.32%   |
| fr_FR        | 10        | 1.93%   |
| en_DE        | 5         | 0.97%   |
| an_ES        | 5         | 0.97%   |
| zh_CN        | 3         | 0.58%   |
| ru_RU        | 3         | 0.58%   |
| es_ES        | 3         | 0.58%   |
| pt_PT        | 2         | 0.39%   |
| it_IT        | 2         | 0.39%   |
| en_NL        | 2         | 0.39%   |
| sk_SK        | 1         | 0.19%   |
| pt_BR        | 1         | 0.19%   |
| pl_PL        | 1         | 0.19%   |
| nl_NL        | 1         | 0.19%   |
| nl_BE        | 1         | 0.19%   |
| ksh_DE       | 1         | 0.19%   |
| hr_HR        | 1         | 0.19%   |
| fr_BE        | 1         | 0.19%   |
| et_EE        | 1         | 0.19%   |
| es_MX        | 1         | 0.19%   |
| en_SE        | 1         | 0.19%   |
| en_IE        | 1         | 0.19%   |
| en_HK        | 1         | 0.19%   |
| en_GB.UTF-12 | 1         | 0.19%   |
| en_CA        | 1         | 0.19%   |
| de_AT        | 1         | 0.19%   |
| C            | 1         | 0.19%   |
| ba_RU        | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 504       | 97.86%  |
| EFI  | 11        | 2.14%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 514       | 99.81%  |
| Ext4  | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 504       | 97.67%  |
| GPT     | 12        | 2.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 508       | 98.64%  |
| Yes       | 7         | 1.36%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 513       | 99.61%  |
| Yes       | 2         | 0.39%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Valve                  | 407       | 79.03%  |
| ASUSTek Computer       | 22        | 4.27%   |
| Gigabyte Technology    | 13        | 2.52%   |
| Hewlett-Packard        | 11        | 2.14%   |
| Lenovo                 | 9         | 1.75%   |
| MSI                    | 8         | 1.55%   |
| Dell                   | 7         | 1.36%   |
| Apple                  | 7         | 1.36%   |
| ASRock                 | 6         | 1.17%   |
| GPD                    | 4         | 0.78%   |
| AOKZOE                 | 3         | 0.58%   |
| AZW                    | 2         | 0.39%   |
| Alienware              | 2         | 0.39%   |
| Acer                   | 2         | 0.39%   |
| Teclast                | 1         | 0.19%   |
| Samsung Electronics    | 1         | 0.19%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.19%   |
| Microsoft              | 1         | 0.19%   |
| Intel                  | 1         | 0.19%   |
| GPU Company            | 1         | 0.19%   |
| Google                 | 1         | 0.19%   |
| AYANEO                 | 1         | 0.19%   |
| Anbernic               | 1         | 0.19%   |
| AMI                    | 1         | 0.19%   |
| ADVANCE                | 1         | 0.19%   |
| Unknown                | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Valve Jupiter                          | 407       | 79.03%  |
| GPD G1619-04                           | 3         | 0.58%   |
| ASUS All Series                        | 3         | 0.58%   |
| AOKZOE A1 AR07                         | 3         | 0.58%   |
| HP Pavilion 17                         | 2         | 0.39%   |
| Gigabyte B450 AORUS M                  | 2         | 0.39%   |
| ASUS ROG STRIX B550-F GAMING           | 2         | 0.39%   |
| Apple Macmini7,1                       | 2         | 0.39%   |
| Unknown                                | 2         | 0.39%   |
| Teclast TbooK 16 Power                 | 1         | 0.19%   |
| Samsung 950XDB/951XDB/950XDY           | 1         | 0.19%   |
| ONE-NETBOOK TECHNOLOGY ONE XPLAYER     | 1         | 0.19%   |
| MSI MS-7C02                            | 1         | 0.19%   |
| MSI MS-7B79                            | 1         | 0.19%   |
| MSI MS-7B09                            | 1         | 0.19%   |
| MSI MS-7A33                            | 1         | 0.19%   |
| MSI MS-7693                            | 1         | 0.19%   |
| MSI MPG H510 Trident 3 (MS-B935)       | 1         | 0.19%   |
| MSI H310 Gaming Trident3 (MS-B920)     | 1         | 0.19%   |
| MSI GP66 Leopard 11UH                  | 1         | 0.19%   |
| Microsoft Surface Pro 8                | 1         | 0.19%   |
| Lenovo ThinkCentre M920x 10S2S00V00    | 1         | 0.19%   |
| Lenovo ThinkCentre M720q 10T700A9UK    | 1         | 0.19%   |
| Lenovo ThinkCentre M720q 10T7002CUS    | 1         | 0.19%   |
| Lenovo ThinkBook 13s G3 ACN 20YA       | 1         | 0.19%   |
| Lenovo Legion Y740-15IRHg 81UH         | 1         | 0.19%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2    | 1         | 0.19%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 1         | 0.19%   |
| Lenovo IdeaPad 1 14IAU7 82QC           | 1         | 0.19%   |
| Intel NUC8i7HVK                        | 1         | 0.19%   |
| HP x2 210 G2                           | 1         | 0.19%   |
| HP t630 Thin Client                    | 1         | 0.19%   |
| HP ProDesk 405 G4 Desktop Mini         | 1         | 0.19%   |
| HP Pavilion x360 Convertible 14-dy0xxx | 1         | 0.19%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 1         | 0.19%   |
| HP Pavilion Gaming Laptop 15-dk0xxx    | 1         | 0.19%   |
| HP Pavilion Gaming Desktop 690-00xx    | 1         | 0.19%   |
| HP Laptop 14z-fq0000                   | 1         | 0.19%   |
| HP 27-p055na                           | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Valve Jupiter              | 407       | 79.03%  |
| HP Pavilion                | 6         | 1.17%   |
| ASUS ROG                   | 5         | 0.97%   |
| ASUS PRIME                 | 4         | 0.78%   |
| Lenovo ThinkCentre         | 3         | 0.58%   |
| Lenovo IdeaPad             | 3         | 0.58%   |
| GPD G1619-04               | 3         | 0.58%   |
| ASUS All                   | 3         | 0.58%   |
| AOKZOE A1                  | 3         | 0.58%   |
| Gigabyte X570              | 2         | 0.39%   |
| Gigabyte B450M             | 2         | 0.39%   |
| Gigabyte B450              | 2         | 0.39%   |
| Dell XPS                   | 2         | 0.39%   |
| Dell Precision             | 2         | 0.39%   |
| Dell OptiPlex              | 2         | 0.39%   |
| ASUS TUF                   | 2         | 0.39%   |
| ASRock X570                | 2         | 0.39%   |
| Apple Macmini7             | 2         | 0.39%   |
| Apple MacBookAir6          | 2         | 0.39%   |
| Acer Aspire                | 2         | 0.39%   |
| Unknown                    | 2         | 0.39%   |
| Teclast TbooK              | 1         | 0.19%   |
| Samsung 950XDB             | 1         | 0.19%   |
| ONE-NETBOOK TECHNOLOGY ONE | 1         | 0.19%   |
| MSI MS-7C02                | 1         | 0.19%   |
| MSI MS-7B79                | 1         | 0.19%   |
| MSI MS-7B09                | 1         | 0.19%   |
| MSI MS-7A33                | 1         | 0.19%   |
| MSI MS-7693                | 1         | 0.19%   |
| MSI MPG                    | 1         | 0.19%   |
| MSI H310                   | 1         | 0.19%   |
| MSI GP66                   | 1         | 0.19%   |
| Microsoft Surface          | 1         | 0.19%   |
| Lenovo ThinkBook           | 1         | 0.19%   |
| Lenovo Legion              | 1         | 0.19%   |
| Lenovo IdeaPadFlex         | 1         | 0.19%   |
| Intel NUC8i7HVK            | 1         | 0.19%   |
| HP x2                      | 1         | 0.19%   |
| HP t630                    | 1         | 0.19%   |
| HP ProDesk                 | 1         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 410       | 79.61%  |
| 2021    | 23        | 4.47%   |
| 2020    | 15        | 2.91%   |
| 2019    | 12        | 2.33%   |
| Unknown | 12        | 2.33%   |
| 2018    | 11        | 2.14%   |
| 2017    | 8         | 1.55%   |
| 2016    | 8         | 1.55%   |
| 2013    | 7         | 1.36%   |
| 2015    | 4         | 0.78%   |
| 2014    | 2         | 0.39%   |
| 2012    | 2         | 0.39%   |
| 2011    | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 445       | 86.41%  |
| Desktop     | 48        | 9.32%   |
| Mini pc     | 9         | 1.75%   |
| Tablet      | 8         | 1.55%   |
| Convertible | 3         | 0.58%   |
| All in one  | 2         | 0.39%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 515       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 514       | 99.81%  |
| Yes  | 1         | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 428       | 83.11%  |
| 16.01-24.0  | 37        | 7.18%   |
| 4.01-8.0    | 20        | 3.88%   |
| 32.01-64.0  | 13        | 2.52%   |
| 24.01-32.0  | 8         | 1.55%   |
| 64.01-256.0 | 5         | 0.97%   |
| 3.01-4.0    | 4         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 271       | 50.65%  |
| 3.01-4.0  | 125       | 23.36%  |
| 4.01-8.0  | 74        | 13.83%  |
| 1.01-2.0  | 62        | 11.59%  |
| 8.01-16.0 | 3         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 2      | 292       | 55.83%  |
| 1      | 190       | 36.33%  |
| 3      | 26        | 4.97%   |
| 4      | 7         | 1.34%   |
| 5      | 3         | 0.57%   |
| 0      | 2         | 0.38%   |
| 11     | 1         | 0.19%   |
| 7      | 1         | 0.19%   |
| 6      | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 500       | 97.09%  |
| Yes       | 15        | 2.91%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 313       | 60.19%  |
| Yes       | 207       | 39.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 494       | 95.92%  |
| No        | 21        | 4.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 479       | 92.83%  |
| No        | 37        | 7.17%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 227       | 43.99%  |
| UK          | 62        | 12.02%  |
| Germany     | 51        | 9.88%   |
| Canada      | 21        | 4.07%   |
| France      | 20        | 3.88%   |
| Spain       | 18        | 3.49%   |
| Netherlands | 12        | 2.33%   |
| Poland      | 9         | 1.74%   |
| Russia      | 6         | 1.16%   |
| China       | 6         | 1.16%   |
| Brazil      | 6         | 1.16%   |
| Austria     | 6         | 1.16%   |
| Sweden      | 5         | 0.97%   |
| Romania     | 5         | 0.97%   |
| Italy       | 5         | 0.97%   |
| Denmark     | 4         | 0.78%   |
| Belgium     | 4         | 0.78%   |
| Australia   | 4         | 0.78%   |
| Mexico      | 3         | 0.58%   |
| Hong Kong   | 3         | 0.58%   |
| Czechia     | 3         | 0.58%   |
| Slovakia    | 2         | 0.39%   |
| Portugal    | 2         | 0.39%   |
| Oman        | 2         | 0.39%   |
| Moldova     | 2         | 0.39%   |
| Latvia      | 2         | 0.39%   |
| Ireland     | 2         | 0.39%   |
| Hungary     | 2         | 0.39%   |
| Estonia     | 2         | 0.39%   |
| Bulgaria    | 2         | 0.39%   |
| Vietnam     | 1         | 0.19%   |
| UAE         | 1         | 0.19%   |
| Turkey      | 1         | 0.19%   |
| Switzerland | 1         | 0.19%   |
| South Korea | 1         | 0.19%   |
| Peru        | 1         | 0.19%   |
| Palestine   | 1         | 0.19%   |
| Malaysia    | 1         | 0.19%   |
| Kuwait      | 1         | 0.19%   |
| Japan       | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Austin              | 5         | 0.94%   |
| Seattle             | 4         | 0.75%   |
| Portland            | 4         | 0.75%   |
| Madrid              | 4         | 0.75%   |
| Los Angeles         | 4         | 0.75%   |
| London              | 4         | 0.75%   |
| Valencia            | 3         | 0.56%   |
| Nottingham          | 3         | 0.56%   |
| Newcastle upon Tyne | 3         | 0.56%   |
| Kansas City         | 3         | 0.56%   |
| Colorado Springs    | 3         | 0.56%   |
| Cologne             | 3         | 0.56%   |
| Brooklyn            | 3         | 0.56%   |
| Berlin              | 3         | 0.56%   |
| Washington          | 2         | 0.38%   |
| Warsaw              | 2         | 0.38%   |
| Sunnyvale           | 2         | 0.38%   |
| Stuttgart           | 2         | 0.38%   |
| Stockholm           | 2         | 0.38%   |
| South Holland       | 2         | 0.38%   |
| Sao Paulo           | 2         | 0.38%   |
| San Antonio         | 2         | 0.38%   |
| Rotterdam           | 2         | 0.38%   |
| Riga                | 2         | 0.38%   |
| Queens              | 2         | 0.38%   |
| Prague              | 2         | 0.38%   |
| Phoenix             | 2         | 0.38%   |
| Paris               | 2         | 0.38%   |
| Oxford              | 2         | 0.38%   |
| Oklahoma City       | 2         | 0.38%   |
| Norwich             | 2         | 0.38%   |
| North Shields       | 2         | 0.38%   |
| Norfolk             | 2         | 0.38%   |
| Muscat              | 2         | 0.38%   |
| Moscow              | 2         | 0.38%   |
| Mississauga         | 2         | 0.38%   |
| Minneapolis         | 2         | 0.38%   |
| Miami               | 2         | 0.38%   |
| Manchester          | 2         | 0.38%   |
| Leipzig             | 2         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Unknown                        | 227       | 251    | 25.36%  |
| Kingston                       | 86        | 94     | 9.61%   |
| Samsung Electronics            | 81        | 100    | 9.05%   |
| Phison                         | 80        | 83     | 8.94%   |
| Kingston Technology Company    | 71        | 74     | 7.93%   |
| Phison Electronics             | 58        | 65     | 6.48%   |
| Unknown                        | 58        | 63     | 6.48%   |
| O2 Micro                       | 44        | 47     | 4.92%   |
| Sandisk                        | 29        | 34     | 3.24%   |
| Silicon Motion                 | 22        | 24     | 2.46%   |
| Seagate                        | 20        | 25     | 2.23%   |
| SK hynix                       | 12        | 17     | 1.34%   |
| WDC                            | 10        | 13     | 1.12%   |
| Crucial                        | 9         | 11     | 1.01%   |
| Toshiba                        | 8         | 10     | 0.89%   |
| KIOXIA                         | 8         | 9      | 0.89%   |
| PNY                            | 7         | 8      | 0.78%   |
| A-DATA Technology              | 7         | 7      | 0.78%   |
| Apple                          | 6         | 9      | 0.67%   |
| Intel                          | 5         | 5      | 0.56%   |
| Solid State Storage Technology | 4         | 5      | 0.45%   |
| Micron/Crucial Technology      | 4         | 4      | 0.45%   |
| JMicron Technology             | 3         | 3      | 0.34%   |
| China                          | 3         | 6      | 0.34%   |
| Biwin Storage Technology       | 3         | 3      | 0.34%   |
| ADATA Technology               | 3         | 4      | 0.34%   |
| Realtek Semiconductor          | 2         | 2      | 0.22%   |
| Realtek                        | 2         | 2      | 0.22%   |
| KingSpec                       | 2         | 2      | 0.22%   |
| ASMT                           | 2         | 2      | 0.22%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.11%   |
| W800S                          | 1         | 1      | 0.11%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.11%   |
| TrekStor                       | 1         | 1      | 0.11%   |
| SSK                            | 1         | 1      | 0.11%   |
| SPCC                           | 1         | 2      | 0.11%   |
| NGFF                           | 1         | 1      | 0.11%   |
| Mushkin                        | 1         | 1      | 0.11%   |
| Micron Technology              | 1         | 1      | 0.11%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown MMC Card  512GB                                | 92        | 9.96%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB                | 70        | 7.58%   |
| Unknown                                                | 58        | 6.28%   |
| Phison PS5013 E13 NVMe Controller 512GB                | 56        | 6.06%   |
| Phison NVMe SSD Drive 512GB                            | 55        | 5.95%   |
| Unknown MMC Card  256GB                                | 48        | 5.19%   |
| Kingston NVMe SSD Drive 512GB                          | 42        | 4.55%   |
| Unknown MMC Card  128GB                                | 33        | 3.57%   |
| Kingston NVMe SSD Drive 256GB                          | 32        | 3.46%   |
| O2 Micro E2M2 64GB                                     | 30        | 3.25%   |
| Samsung MZ9LQ512HBLU-00BVL 512GB                       | 18        | 1.95%   |
| Samsung MZ9LQ256HBJD-00BVL 256GB                       | 18        | 1.95%   |
| Phison NVMe SSD Drive 256GB                            | 18        | 1.95%   |
| O2 Micro NVMe SSD Drive 64GB                           | 15        | 1.62%   |
| Unknown MMC Card  393GB                                | 11        | 1.19%   |
| Unknown MMC Card  64GB                                 | 10        | 1.08%   |
| Unknown MMC Card  32GB                                 | 9         | 0.97%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 8         | 0.87%   |
| Silicon Motion NVMe SSD Drive 512GB                    | 8         | 0.87%   |
| Silicon Motion NVMe SSD Drive 256GB                    | 5         | 0.54%   |
| Sandisk WDC PC SN530 SDBPTPZ-1T00 1024GB               | 5         | 0.54%   |
| Samsung NVMe SSD Drive 512GB                           | 5         | 0.54%   |
| Samsung NVMe SSD Drive 1TB                             | 5         | 0.54%   |
| Unknown MMC Card  500GB                                | 4         | 0.43%   |
| SK hynix BC711 NVMe 256GB                              | 4         | 0.43%   |
| Crucial CT1000BX500SSD1 1TB                            | 4         | 0.43%   |
| Unknown MMC Card  498GB                                | 3         | 0.32%   |
| Unknown MMC Card  16GB                                 | 3         | 0.32%   |
| Sandisk PC SN530 NVMe WDC 256GB                        | 3         | 0.32%   |
| Samsung NVMe SSD Drive 1024GB                          | 3         | 0.32%   |
| Unknown MMC Card  250GB                                | 2         | 0.22%   |
| Unknown MMC Card  196GB                                | 2         | 0.22%   |
| Unknown MMC Card  1073GB                               | 2         | 0.22%   |
| Toshiba MQ01ABD100 1TB                                 | 2         | 0.22%   |
| SK hynix NVMe SSD Drive 256GB                          | 2         | 0.22%   |
| SK hynix NVMe SSD Drive 1024GB                         | 2         | 0.22%   |
| Seagate ST1000LM014-1EJ164 1TB                         | 2         | 0.22%   |
| Sandisk WDC PC SN530 SDBPMPZ-256G-1101 256GB           | 2         | 0.22%   |
| SanDisk NVMe SSD Drive 512GB                           | 2         | 0.22%   |
| SanDisk NVMe SSD Drive 500GB                           | 2         | 0.22%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 19        | 24     | 54.29%  |
| WDC     | 6         | 8      | 17.14%  |
| Toshiba | 6         | 8      | 17.14%  |
| Apple   | 3         | 6      | 8.57%   |
| ASMT    | 1         | 1      | 2.86%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 28     | 25%     |
| Crucial             | 9         | 11     | 11.84%  |
| PNY                 | 7         | 8      | 9.21%   |
| Kingston            | 7         | 8      | 9.21%   |
| SanDisk             | 6         | 7      | 7.89%   |
| A-DATA Technology   | 5         | 5      | 6.58%   |
| WDC                 | 4         | 4      | 5.26%   |
| China               | 3         | 6      | 3.95%   |
| KingSpec            | 2         | 2      | 2.63%   |
| JMicron Technology  | 2         | 2      | 2.63%   |
| Apple               | 2         | 2      | 2.63%   |
| TrekStor            | 1         | 1      | 1.32%   |
| SPCC                | 1         | 2      | 1.32%   |
| NGFF                | 1         | 1      | 1.32%   |
| Mushkin             | 1         | 1      | 1.32%   |
| Lexar 25            | 1         | 1      | 1.32%   |
| Intenso             | 1         | 1      | 1.32%   |
| Intel               | 1         | 1      | 1.32%   |
| HP Phison           | 1         | 1      | 1.32%   |
| Corsair             | 1         | 1      | 1.32%   |
| ASMT                | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 477       | 544    | 55.85%  |
| MMC     | 279       | 309    | 32.67%  |
| SSD     | 59        | 94     | 6.91%   |
| HDD     | 31        | 47     | 3.63%   |
| Unknown | 8         | 9      | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 477       | 539    | 56.58%  |
| MMC  | 279       | 309    | 33.1%   |
| SATA | 65        | 125    | 7.71%   |
| SAS  | 22        | 30     | 2.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 72     | 49.47%  |
| 0.51-1.0   | 34        | 48     | 35.79%  |
| 1.01-2.0   | 7         | 11     | 7.37%   |
| 3.01-4.0   | 4         | 6      | 4.21%   |
| 2.01-3.0   | 2         | 3      | 2.11%   |
| 4.01-10.0  | 1         | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 234       | 44.83%  |
| 101-250        | 152       | 29.12%  |
| 501-1000       | 59        | 11.3%   |
| 51-100         | 42        | 8.05%   |
| 1001-2000      | 24        | 4.6%    |
| More than 3000 | 7         | 1.34%   |
| 2001-3000      | 3         | 0.57%   |
| 21-50          | 1         | 0.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 176       | 33.21%  |
| 251-500        | 127       | 23.96%  |
| 21-50          | 73        | 13.77%  |
| 1-20           | 68        | 12.83%  |
| 51-100         | 60        | 11.32%  |
| 501-1000       | 18        | 3.4%    |
| 1001-2000      | 5         | 0.94%   |
| More than 3000 | 2         | 0.38%   |
| 2001-3000      | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

Zero info for selected period =(

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

Zero info for selected period =(

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

Zero info for selected period =(

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

Zero info for selected period =(

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 510       | 988    | 97.89%  |
| Works    | 11        | 15     | 2.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Kingston Technology Company    | 145       | 25.44%  |
| Phison Electronics             | 135       | 23.68%  |
| Samsung Electronics            | 66        | 11.58%  |
| O2 Micro                       | 44        | 7.72%   |
| Intel                          | 42        | 7.37%   |
| AMD                            | 41        | 7.19%   |
| SanDisk                        | 25        | 4.39%   |
| Silicon Motion                 | 22        | 3.86%   |
| SK hynix                       | 12        | 2.11%   |
| KIOXIA                         | 8         | 1.4%    |
| ADATA Technology               | 5         | 0.88%   |
| Solid State Storage Technology | 4         | 0.7%    |
| Micron/Crucial Technology      | 4         | 0.7%    |
| Biwin Storage Technology       | 4         | 0.7%    |
| Toshiba America Info Systems   | 3         | 0.53%   |
| Realtek Semiconductor          | 2         | 0.35%   |
| Yangtze Memory Technologies    | 1         | 0.18%   |
| Union Memory (Shenzhen)        | 1         | 0.18%   |
| Seagate Technology             | 1         | 0.18%   |
| Micron Technology              | 1         | 0.18%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.18%   |
| Marvell Technology Group       | 1         | 0.18%   |
| INNOGRIT                       | 1         | 0.18%   |
| Apple                          | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Kingston Company OM3PDP3 NVMe SSD                                              | 140       | 23.73%  |
| Phison PS5013 E13 NVMe Controller                                              | 127       | 21.53%  |
| Samsung NVMe SSD Controller 980                                                | 53        | 8.98%   |
| O2 Micro Non-Volatile memory controller                                        | 44        | 7.46%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 4.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 21        | 3.56%   |
| SanDisk Non-Volatile memory controller                                         | 16        | 2.71%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 10        | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.36%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 7         | 1.19%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 1.02%   |
| Phison E12 NVMe Controller                                                     | 5         | 0.85%   |
| Solid State Storage Non-Volatile memory controller                             | 4         | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 0.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.68%   |
| Biwin Storage Non-Volatile memory controller                                   | 4         | 0.68%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.51%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.51%   |
| Intel SSD 660P Series                                                          | 3         | 0.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 0.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 0.51%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.51%   |
| ADATA Non-Volatile memory controller                                           | 3         | 0.51%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 0.34%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.34%   |
| SanDisk PC SN530 NVMe SSD                                                      | 2         | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.34%   |
| Phison Electronics Non-Volatile memory controller                              | 2         | 0.34%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                             | 2         | 0.34%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.34%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 0.34%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 2         | 0.34%   |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 0.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.34%   |
| AMD FCH SATA Controller D                                                      | 2         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 477       | 84.88%  |
| SATA | 75        | 13.35%  |
| RAID | 9         | 1.6%    |
| IDE  | 1         | 0.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 462       | 89.71%  |
| Intel  | 53        | 10.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| AMD Custom APU 0405                      | 407       | 79.03%  |
| AMD Ryzen 7 6800U with Radeon Graphics   | 6         | 1.17%   |
| AMD Ryzen 9 3900X 12-Core Processor      | 4         | 0.78%   |
| AMD Ryzen 9 5900X 12-Core Processor      | 3         | 0.58%   |
| AMD Ryzen 7 4800U with Radeon Graphics   | 3         | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 2         | 0.39%   |
| Intel Core i7-6700K CPU @ 4.00GHz        | 2         | 0.39%   |
| Intel Core i5-4260U CPU @ 1.40GHz        | 2         | 0.39%   |
| Intel Atom x7-Z8750 CPU @ 1.60GHz        | 2         | 0.39%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 0.39%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 2         | 0.39%   |
| AMD Ryzen 7 3700X 8-Core Processor       | 2         | 0.39%   |
| AMD Ryzen 5 5600H with Radeon Graphics   | 2         | 0.39%   |
| AMD Ryzen 5 5600G with Radeon Graphics   | 2         | 0.39%   |
| AMD Ryzen 5 4500U with Radeon Graphics   | 2         | 0.39%   |
| AMD Ryzen 5 3600X 6-Core Processor       | 2         | 0.39%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 2         | 0.39%   |
| Intel Xeon W-3223 CPU @ 3.50GHz          | 1         | 0.19%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz      | 1         | 0.19%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz      | 1         | 0.19%   |
| Intel Xeon CPU E3-1575M v5 @ 3.00GHz     | 1         | 0.19%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.19%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 1         | 0.19%   |
| Intel Core i7-8809G CPU @ 3.10GHz        | 1         | 0.19%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 1         | 0.19%   |
| Intel Core i7-7700K CPU @ 4.20GHz        | 1         | 0.19%   |
| Intel Core i7-7560U CPU @ 2.40GHz        | 1         | 0.19%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 0.19%   |
| Intel Core i7-4578U CPU @ 3.00GHz        | 1         | 0.19%   |
| Intel Core i7-10870H CPU @ 2.20GHz       | 1         | 0.19%   |
| Intel Core i5-9400 CPU @ 2.90GHz         | 1         | 0.19%   |
| Intel Core i5-9300H CPU @ 2.40GHz        | 1         | 0.19%   |
| Intel Core i5-8600T CPU @ 2.30GHz        | 1         | 0.19%   |
| Intel Core i5-8500T CPU @ 2.10GHz        | 1         | 0.19%   |
| Intel Core i5-8400T CPU @ 1.70GHz        | 1         | 0.19%   |
| Intel Core i5-8259U CPU @ 2.30GHz        | 1         | 0.19%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz       | 1         | 0.19%   |
| Intel Core i5-6600 CPU @ 3.30GHz         | 1         | 0.19%   |
| Intel Core i5-6400T CPU @ 2.20GHz        | 1         | 0.19%   |
| Intel Core i5-4590S CPU @ 3.00GHz        | 1         | 0.19%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Other                  | 418       | 81.17%  |
| Intel Core i5          | 19        | 3.69%   |
| AMD Ryzen 7            | 18        | 3.5%    |
| AMD Ryzen 5            | 18        | 3.5%    |
| Intel Core i7          | 12        | 2.33%   |
| AMD Ryzen 9            | 9         | 1.75%   |
| Intel Xeon             | 4         | 0.78%   |
| Intel Atom             | 3         | 0.58%   |
| Intel Core i3          | 2         | 0.39%   |
| AMD FX                 | 2         | 0.39%   |
| AMD Athlon             | 2         | 0.39%   |
| Intel Pentium Silver   | 1         | 0.19%   |
| Intel Celeron          | 1         | 0.19%   |
| AMD Ryzen Threadripper | 1         | 0.19%   |
| AMD Ryzen 7 PRO        | 1         | 0.19%   |
| AMD Ryzen 5 PRO        | 1         | 0.19%   |
| AMD Embedded           | 1         | 0.19%   |
| AMD A8                 | 1         | 0.19%   |
| AMD A10                | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 439       | 85.24%  |
| 8      | 26        | 5.05%   |
| 6      | 25        | 4.85%   |
| 2      | 16        | 3.11%   |
| 12     | 8         | 1.55%   |
| 3      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 515       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 493       | 95.36%  |
| 1      | 24        | 4.64%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 515       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 504       | 97.86%  |
| 0x08900201 | 7         | 1.36%   |
| 0x906e9    | 1         | 0.19%   |
| 0x0a50000c | 1         | 0.19%   |
| 0x0a404102 | 1         | 0.19%   |
| 0x08600106 | 1         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 420       | 81.55%  |
| KabyLake      | 17        | 3.3%    |
| Zen 2         | 15        | 2.91%   |
| Zen 3         | 14        | 2.72%   |
| Zen+          | 9         | 1.75%   |
| Haswell       | 9         | 1.75%   |
| TigerLake     | 6         | 1.17%   |
| Skylake       | 6         | 1.17%   |
| Zen           | 5         | 0.97%   |
| Piledriver    | 4         | 0.78%   |
| Silvermont    | 3         | 0.58%   |
| SandyBridge   | 2         | 0.39%   |
| IvyBridge     | 2         | 0.39%   |
| Goldmont plus | 1         | 0.19%   |
| Excavator     | 1         | 0.19%   |
| CometLake     | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| AMD    | 466       | 87.43%  |
| Intel  | 36        | 6.75%   |
| Nvidia | 31        | 5.82%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 407       | 76.36%  |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.13%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 1.13%   |
| AMD Renoir                                                                               | 5         | 0.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 0.94%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 4         | 0.75%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 4         | 0.75%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 0.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.56%   |
| Intel HD Graphics 530                                                                    | 3         | 0.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.56%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.38%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.38%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.38%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 2         | 0.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.38%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.38%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 2         | 0.38%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 2         | 0.38%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.38%   |
| Nvidia TU117M                                                                            | 1         | 0.19%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.19%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                                       | 1         | 0.19%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.19%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.19%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.19%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 1         | 0.19%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                                   | 1         | 0.19%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.19%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.19%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.19%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.19%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.19%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.19%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.19%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 460       | 89.15%  |
| 1 x Intel      | 22        | 4.26%   |
| 1 x Nvidia     | 19        | 3.68%   |
| Intel + Nvidia | 8         | 1.55%   |
| AMD + Nvidia   | 5         | 0.97%   |
| Other          | 1         | 0.19%   |
| Intel + AMD    | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 490       | 95.15%  |
| Proprietary | 25        | 4.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 486       | 94.19%  |
| 7.01-8.0   | 7         | 1.36%   |
| 3.01-4.0   | 6         | 1.16%   |
| 0.51-1.0   | 6         | 1.16%   |
| 5.01-6.0   | 3         | 0.58%   |
| 1.01-2.0   | 2         | 0.39%   |
| 8.01-16.0  | 2         | 0.39%   |
| 0.01-0.5   | 2         | 0.39%   |
| 2.01-3.0   | 1         | 0.19%   |
| 16.01-24.0 | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| ANX                  | 189       | 29.67%  |
| Analogix             | 154       | 24.18%  |
| Valve                | 74        | 11.62%  |
| Samsung Electronics  | 25        | 3.92%   |
| Goldstar             | 22        | 3.45%   |
| Dell                 | 13        | 2.04%   |
| Ancor Communications | 10        | 1.57%   |
| Hewlett-Packard      | 8         | 1.26%   |
| BOE                  | 8         | 1.26%   |
| ASUSTek Computer     | 8         | 1.26%   |
| AOC                  | 8         | 1.26%   |
| Acer                 | 8         | 1.26%   |
| Vizio                | 6         | 0.94%   |
| Sony                 | 6         | 0.94%   |
| RTK                  | 6         | 0.94%   |
| Philips              | 6         | 0.94%   |
| Chimei Innolux       | 6         | 0.94%   |
| ViewSonic            | 5         | 0.78%   |
| BenQ                 | 5         | 0.78%   |
| AU Optronics         | 5         | 0.78%   |
| LG Display           | 4         | 0.63%   |
| Apple                | 4         | 0.63%   |
| Sharp                | 3         | 0.47%   |
| Pixio                | 3         | 0.47%   |
| MSI                  | 3         | 0.47%   |
| Lenovo               | 3         | 0.47%   |
| JDI                  | 3         | 0.47%   |
| Hitachi              | 3         | 0.47%   |
| Sun                  | 2         | 0.31%   |
| MSF                  | 2         | 0.31%   |
| Microsoft            | 2         | 0.31%   |
| Insignia             | 2         | 0.31%   |
| Huion                | 2         | 0.31%   |
| ___                  | 1         | 0.16%   |
| ZSC                  | 1         | 0.16%   |
| YTH                  | 1         | 0.16%   |
| Wacom                | 1         | 0.16%   |
| Unknown              | 1         | 0.16%   |
| Toshiba              | 1         | 0.16%   |
| TCL                  | 1         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| ANX ANX7530 U ANX7539 800x1280                                          | 189       | 29.39%  |
| Analogix ANX7530 U ANX7539 800x1280                                     | 154       | 23.95%  |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 74        | 11.51%  |
| RTK 7911D RTK2A3B 720x1280 720x1280mm 57.8-inch                         | 5         | 0.78%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                     | 4         | 0.62%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                      | 3         | 0.47%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                     | 2         | 0.31%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch                  | 2         | 0.31%   |
| Sony TV *00 SNY7A04 3840x2160 1218x685mm 55.0-inch                      | 2         | 0.31%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 1872x1053mm 84.6-inch | 2         | 0.31%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 2         | 0.31%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch      | 2         | 0.31%   |
| MSF W0550U99GE-D MSF1003 1080x1920                                      | 2         | 0.31%   |
| Microsoft Xbox One MSH0001 1920x1080 520x290mm 23.4-inch                | 2         | 0.31%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                   | 2         | 0.31%   |
| Goldstar ULTRAWIDE GSM5AFB 2560x1080 798x334mm 34.1-inch                | 2         | 0.31%   |
| Goldstar ULTRAGEAR GSM774A 3440x1440 800x335mm 34.1-inch                | 2         | 0.31%   |
| Goldstar 27GN7 GSM5B8D 1920x1080 600x303mm 26.5-inch                    | 2         | 0.31%   |
| Dell S2721DS DELA19D 2560x1440 597x336mm 27.0-inch                      | 2         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch        | 2         | 0.31%   |
| Ancor Communications MX279 ACI27C3 1920x1080 598x336mm 27.0-inch        | 2         | 0.31%   |
| Ancor Communications ASUS VH242H ACI24F3 1920x1080 521x293mm 23.5-inch  | 2         | 0.31%   |
| ___ LCDTV16 ___9000 1360x768                                            | 1         | 0.16%   |
| ZSC FHD HDR ZSCBC32 1920x1080 344x195mm 15.6-inch                       | 1         | 0.16%   |
| YTH HS133PC YTH1330 1920x1080 255x220mm 13.3-inch                       | 1         | 0.16%   |
| Wacom CintiqPro24P WAC1063 3840x2160 522x293mm 23.6-inch                | 1         | 0.16%   |
| Vizio VW37L HDTV40A VIZ0035 1366x768 780x520mm 36.9-inch                | 1         | 0.16%   |
| Vizio M65Q6-J09 VIZ1039 3840x2160 1428x803mm 64.5-inch                  | 1         | 0.16%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.16%   |
| Vizio D24f4-J01 VIZ1044 1920x1080 527x296mm 23.8-inch                   | 1         | 0.16%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch              | 1         | 0.16%   |
| ViewSonic VX2858Sml VSCD02F 1920x1080 621x341mm 27.9-inch               | 1         | 0.16%   |
| ViewSonic VX2758 Series VSC35DD 1920x1080 597x336mm 27.0-inch           | 1         | 0.16%   |
| ViewSonic VX2718-2KPC VSCB73A 2560x1440 598x336mm 27.0-inch             | 1         | 0.16%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch           | 1         | 0.16%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.16%   |
| Toshiba TV TSB010E 1920x1080 1014x573mm 45.9-inch                       | 1         | 0.16%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                     | 1         | 0.16%   |
| Sony TV SNYEE01 1920x1080                                               | 1         | 0.16%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                      | 1         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 800x1280           | 402       | 64.94%  |
| 1920x1080 (FHD)    | 104       | 16.8%   |
| 3840x2160 (4K)     | 38        | 6.14%   |
| 2560x1440 (QHD)    | 24        | 3.88%   |
| 3440x1440          | 10        | 1.62%   |
| 2560x1080          | 7         | 1.13%   |
| 2560x1600          | 5         | 0.81%   |
| 1366x768 (WXGA)    | 5         | 0.81%   |
| 3840x1080          | 3         | 0.48%   |
| 1440x900 (WXGA+)   | 3         | 0.48%   |
| 1920x1200 (WUXGA)  | 2         | 0.32%   |
| 1600x900 (HD+)     | 2         | 0.32%   |
| 1600x2560          | 2         | 0.32%   |
| 1280x800 (WXGA)    | 2         | 0.32%   |
| 1024x768 (XGA)     | 2         | 0.32%   |
| 3840x1600          | 1         | 0.16%   |
| 3200x1800 (QHD+)   | 1         | 0.16%   |
| 2880x1920          | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1680x1050 (WSXGA+) | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1360x768           | 1         | 0.16%   |
| 1280x1024 (SXGA)   | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 340       | 53.88%  |
| 7       | 75        | 11.89%  |
| 27      | 37        | 5.86%   |
| 15      | 23        | 3.65%   |
| 23      | 20        | 3.17%   |
| 24      | 18        | 2.85%   |
| 34      | 14        | 2.22%   |
| 21      | 12        | 1.9%    |
| 13      | 8         | 1.27%   |
| 84      | 7         | 1.11%   |
| 57      | 7         | 1.11%   |
| 31      | 7         | 1.11%   |
| 72      | 6         | 0.95%   |
| 17      | 6         | 0.95%   |
| 14      | 6         | 0.95%   |
| 49      | 4         | 0.63%   |
| 40      | 4         | 0.63%   |
| 36      | 3         | 0.48%   |
| 32      | 3         | 0.48%   |
| 8       | 3         | 0.48%   |
| 65      | 2         | 0.32%   |
| 64      | 2         | 0.32%   |
| 55      | 2         | 0.32%   |
| 54      | 2         | 0.32%   |
| 48      | 2         | 0.32%   |
| 46      | 2         | 0.32%   |
| 86      | 1         | 0.16%   |
| 75      | 1         | 0.16%   |
| 69      | 1         | 0.16%   |
| 61      | 1         | 0.16%   |
| 52      | 1         | 0.16%   |
| 47      | 1         | 0.16%   |
| 43      | 1         | 0.16%   |
| 42      | 1         | 0.16%   |
| 37      | 1         | 0.16%   |
| 35      | 1         | 0.16%   |
| 28      | 1         | 0.16%   |
| 26      | 1         | 0.16%   |
| 19      | 1         | 0.16%   |
| 18      | 1         | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 340       | 54.14%  |
| 1-100       | 74        | 11.78%  |
| 501-600     | 68        | 10.83%  |
| 301-350     | 30        | 4.78%   |
| 701-800     | 25        | 3.98%   |
| 1001-1500   | 20        | 3.18%   |
| 1501-2000   | 16        | 2.55%   |
| 601-700     | 14        | 2.23%   |
| 401-500     | 14        | 2.23%   |
| 201-300     | 10        | 1.59%   |
| 801-900     | 6         | 0.96%   |
| 351-400     | 5         | 0.8%    |
| 101-200     | 4         | 0.64%   |
| 901-1000    | 2         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 0.62  | 339       | 54.59%  |
| 16/9  | 167       | 26.89%  |
| 0.67  | 74        | 11.92%  |
| 21/9  | 16        | 2.58%   |
| 16/10 | 9         | 1.45%   |
| 0.56  | 5         | 0.81%   |
| 32/9  | 4         | 0.64%   |
| 3/2   | 2         | 0.32%   |
| 0.58  | 2         | 0.32%   |
| 5/4   | 1         | 0.16%   |
| 4/3   | 1         | 0.16%   |
| 1.00  | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 340       | 53.88%  |
| 1-40           | 78        | 12.36%  |
| 201-250        | 41        | 6.5%    |
| 301-350        | 38        | 6.02%   |
| More than 1000 | 35        | 5.55%   |
| 351-500        | 27        | 4.28%   |
| 101-110        | 22        | 3.49%   |
| 501-1000       | 15        | 2.38%   |
| 251-300        | 9         | 1.43%   |
| 81-90          | 8         | 1.27%   |
| 71-80          | 5         | 0.79%   |
| 121-130        | 5         | 0.79%   |
| 151-200        | 2         | 0.32%   |
| 141-150        | 2         | 0.32%   |
| 91-100         | 2         | 0.32%   |
| 51-60          | 1         | 0.16%   |
| 41-50          | 1         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 340       | 54.57%  |
| 51-100        | 88        | 14.13%  |
| 161-240       | 84        | 13.48%  |
| 101-120       | 48        | 7.7%    |
| 121-160       | 37        | 5.94%   |
| 1-50          | 23        | 3.69%   |
| More than 240 | 3         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 408       | 78.31%  |
| 2     | 108       | 20.73%  |
| 3     | 4         | 0.77%   |
| 4     | 1         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 462       | 71.19%  |
| ASIX Electronics              | 67        | 10.32%  |
| Intel                         | 55        | 8.47%   |
| Broadcom                      | 9         | 1.39%   |
| Qualcomm Atheros              | 8         | 1.23%   |
| MediaTek                      | 8         | 1.23%   |
| Microsoft                     | 7         | 1.08%   |
| TP-Link                       | 6         | 0.92%   |
| DisplayLink                   | 4         | 0.62%   |
| Broadcom Limited              | 4         | 0.62%   |
| Ralink Technology             | 3         | 0.46%   |
| Google                        | 3         | 0.46%   |
| Samsung Electronics           | 2         | 0.31%   |
| Lenovo                        | 2         | 0.31%   |
| OPPO Electronics              | 1         | 0.15%   |
| OnePlus Technology (Shenzhen) | 1         | 0.15%   |
| Huawei Technologies           | 1         | 0.15%   |
| Edimax Technology             | 1         | 0.15%   |
| Dell                          | 1         | 0.15%   |
| D-Link                        | 1         | 0.15%   |
| AVM                           | 1         | 0.15%   |
| Aquantia                      | 1         | 0.15%   |
| Apple                         | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 407       | 55.6%   |
| ASIX AX88179 Gigabit Ethernet                                     | 67        | 9.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 7.51%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 5.33%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 1.91%   |
| Intel I211 Gigabit Network Connection                             | 8         | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 0.96%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 6         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.68%   |
| Microsoft XBOX ACC                                                | 5         | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.55%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.55%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 0.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.41%   |
| Intel Wireless 7265                                               | 3         | 0.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.27%   |
| Realtek 802.11ac NIC                                              | 2         | 0.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.27%   |
| Intel Wireless 8260                                               | 2         | 0.27%   |
| Intel Wireless 3165                                               | 2         | 0.27%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.27%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.27%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.27%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.27%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 2         | 0.27%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                        | 1         | 0.14%   |
| TP-Link Archer T4U ver.3                                          | 1         | 0.14%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.14%   |
| TP-Link 802.11ac NIC                                              | 1         | 0.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 1         | 0.14%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 417       | 82.25%  |
| Intel                 | 44        | 8.68%   |
| MediaTek              | 8         | 1.58%   |
| Qualcomm Atheros      | 7         | 1.38%   |
| Microsoft             | 7         | 1.38%   |
| Broadcom              | 7         | 1.38%   |
| TP-Link               | 6         | 1.18%   |
| Broadcom Limited      | 4         | 0.79%   |
| Ralink Technology     | 3         | 0.59%   |
| Edimax Technology     | 1         | 0.2%    |
| Dell                  | 1         | 0.2%    |
| D-Link                | 1         | 0.2%    |
| AVM                   | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 407       | 80.28%  |
| Intel Wi-Fi 6 AX200                                                                           | 14        | 2.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                        | 7         | 1.38%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                       | 6         | 1.18%   |
| Microsoft XBOX ACC                                                                            | 5         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 4         | 0.79%   |
| Intel Wi-Fi 6 AX201                                                                           | 4         | 0.79%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                    | 4         | 0.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 3         | 0.59%   |
| Intel Wireless 7265                                                                           | 3         | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 2         | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                            | 2         | 0.39%   |
| Realtek 802.11ac NIC                                                                          | 2         | 0.39%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                 | 2         | 0.39%   |
| Intel Wireless 8260                                                                           | 2         | 0.39%   |
| Intel Wireless 3165                                                                           | 2         | 0.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                               | 2         | 0.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 2         | 0.39%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                            | 2         | 0.39%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                                    | 1         | 0.2%    |
| TP-Link Archer T4U ver.3                                                                      | 1         | 0.2%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 0.2%    |
| TP-Link 802.11ac NIC                                                                          | 1         | 0.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.2%    |
| Realtek Realtek Network controller                                                            | 1         | 0.2%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.2%    |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                                                        | 1         | 0.2%    |
| Ralink RT5372 Wireless Adapter                                                                | 1         | 0.2%    |
| Ralink RT5370 Wireless Adapter                                                                | 1         | 0.2%    |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 1         | 0.2%    |
| Microsoft Xbox 360 Wireless Adapter                                                           | 1         | 0.2%    |
| Microsoft Wireless XBox Controller Dongle                                                     | 1         | 0.2%    |
| Intel Wireless 8265 / 8275                                                                    | 1         | 0.2%    |
| Intel WiFi Link 5100                                                                          | 1         | 0.2%    |
| Intel Gemini Lake PCH CNVi WiFi                                                               | 1         | 0.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 1         | 0.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                                | 1         | 0.2%    |
| Intel Centrino Wireless-N 2230                                                                | 1         | 0.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 105       | 47.51%  |
| ASIX Electronics              | 67        | 30.32%  |
| Intel                         | 27        | 12.22%  |
| DisplayLink                   | 4         | 1.81%   |
| Broadcom                      | 4         | 1.81%   |
| Qualcomm Atheros              | 3         | 1.36%   |
| Google                        | 3         | 1.36%   |
| Samsung Electronics           | 2         | 0.9%    |
| Lenovo                        | 2         | 0.9%    |
| OPPO Electronics              | 1         | 0.45%   |
| OnePlus Technology (Shenzhen) | 1         | 0.45%   |
| Huawei Technologies           | 1         | 0.45%   |
| Aquantia                      | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| ASIX AX88179 Gigabit Ethernet                                     | 67        | 29.91%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 55        | 24.55%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 17.41%  |
| Intel I211 Gigabit Network Connection                             | 8         | 3.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.23%   |
| Intel Ethernet Controller I225-V                                  | 5         | 2.23%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 2.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 1.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 1.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.89%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.89%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.89%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.89%   |
| DisplayLink Dell Universal Dock D6000                             | 2         | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.45%   |
| OPPO RMX3263                                                      | 1         | 0.45%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.45%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.45%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.45%   |
| Huawei STK-L21                                                    | 1         | 0.45%   |
| Google Pixel 6a                                                   | 1         | 0.45%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 0.45%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.45%   |
| DisplayLink ThinkPad USB 3.0 Ultra Dock                           | 1         | 0.45%   |
| DisplayLink 6950                                                  | 1         | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.45%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 494       | 70.47%  |
| Ethernet | 206       | 29.39%  |
| Modem    | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 446       | 80.65%  |
| Ethernet | 107       | 19.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 464       | 90.1%   |
| 2     | 45        | 8.74%   |
| 3     | 4         | 0.78%   |
| 0     | 2         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 337       | 64.81%  |
| Yes  | 183       | 35.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| IMC Networks                    | 408       | 84.47%  |
| Intel                           | 40        | 8.28%   |
| Realtek Semiconductor           | 6         | 1.24%   |
| Apple                           | 6         | 1.24%   |
| Qualcomm Atheros Communications | 5         | 1.04%   |
| MediaTek                        | 4         | 0.83%   |
| ASUSTek Computer                | 4         | 0.83%   |
| Cambridge Silicon Radio         | 3         | 0.62%   |
| Broadcom                        | 2         | 0.41%   |
| TP-Link                         | 1         | 0.21%   |
| SINO WEALTH                     | 1         | 0.21%   |
| Lite-On Technology              | 1         | 0.21%   |
| Integrated System Solution      | 1         | 0.21%   |
| Foxconn / Hon Hai               | 1         | 0.21%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks Bluetooth Radio                          | 407       | 84.27%  |
| Intel AX200 Bluetooth                                 | 12        | 2.48%   |
| Intel Bluetooth wireless interface                    | 10        | 2.07%   |
| Intel AX210 Bluetooth                                 | 7         | 1.45%   |
| Intel AX201 Bluetooth                                 | 5         | 1.04%   |
| MediaTek Wireless_Device                              | 4         | 0.83%   |
| Realtek Bluetooth Radio                               | 3         | 0.62%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 0.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3         | 0.62%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 3         | 0.62%   |
| Apple Bluetooth USB Host Controller                   | 3         | 0.62%   |
| Apple Bluetooth Host Controller                       | 3         | 0.62%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 0.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.41%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 2         | 0.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2         | 0.41%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2         | 0.41%   |
| ASUS Bluetooth Device                                 | 2         | 0.41%   |
| TP-Link UB500 Adapter                                 | 1         | 0.21%   |
| SINO WEALTH RK Bluetooth Keyboar                      | 1         | 0.21%   |
| Realtek Bluetooth 5.1 Radio                           | 1         | 0.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1         | 0.21%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1         | 0.21%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.21%   |
| IMC Networks Bluetooth Device                         | 1         | 0.21%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| AMD                         | 475       | 78.38%  |
| Intel                       | 49        | 8.09%   |
| Nvidia                      | 28        | 4.62%   |
| Logitech                    | 7         | 1.16%   |
| Realtek Semiconductor       | 5         | 0.83%   |
| Corsair                     | 4         | 0.66%   |
| Lenovo                      | 3         | 0.5%    |
| Kingston Technology         | 3         | 0.5%    |
| JMTek                       | 3         | 0.5%    |
| C-Media Electronics         | 3         | 0.5%    |
| Tenx Technology             | 2         | 0.33%   |
| SteelSeries ApS             | 2         | 0.33%   |
| Sony                        | 2         | 0.33%   |
| GN Netcom                   | 2         | 0.33%   |
| Generalplus Technology      | 2         | 0.33%   |
| FiiO Electronics Technology | 2         | 0.33%   |
| Blue Microphones            | 2         | 0.33%   |
| Apple                       | 2         | 0.33%   |
| Valve Software              | 1         | 0.17%   |
| Razer USA                   | 1         | 0.17%   |
| Quanta                      | 1         | 0.17%   |
| Plantronics                 | 1         | 0.17%   |
| Nreal                       | 1         | 0.17%   |
| MosArt Semiconductor        | 1         | 0.17%   |
| KTMicro                     | 1         | 0.17%   |
| Hewlett-Packard             | 1         | 0.17%   |
| Creative Labs               | 1         | 0.17%   |
| Alesis                      | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt Radeon High Definition Audio Controller                      | 413       | 62.77%  |
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 4.1%    |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 2.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 2.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 11        | 1.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 1.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8         | 1.22%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 0.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 0.91%   |
| AMD Navi 10 HDMI Audio                                                     | 6         | 0.91%   |
| Realtek Semiconductor USB Audio                                            | 5         | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 0.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 0.61%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.46%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.46%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.46%   |
| JMTek USB PnP Audio Device                                                 | 3         | 0.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 0.46%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.46%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.46%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 0.46%   |
| Tenx Technology USB AUDIO                                                  | 2         | 0.3%    |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.3%    |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.3%    |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 2         | 0.3%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 0.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 2         | 0.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 0.3%    |
| Generalplus Technology USB Audio Device                                    | 2         | 0.3%    |
| FiiO Electronics Technology FiiO K5 Pro                                    | 2         | 0.3%    |
| Corsair HS45 Surround USB Sound Adapter                                    | 2         | 0.3%    |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.3%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 8         | 61.54%  |
| SK hynix            | 1         | 7.69%   |
| Samsung Electronics | 1         | 7.69%   |
| Micron Technology   | 1         | 7.69%   |
| G.Skill             | 1         | 7.69%   |
| Crucial             | 1         | 7.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 8         | 61.54%  |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 1         | 7.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s  | 1         | 7.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s   | 1         | 7.69%   |
| G.Skill RAM F4-2666C19-16GRS 16GB SODIMM DDR4 2667MT/s | 1         | 7.69%   |
| Crucial RAM CT8G4SFS832A.C8FR 8GB SODIMM DDR4 3200MT/s | 1         | 7.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| LPDDR5  | 7         | 58.33%  |
| DDR4    | 4         | 33.33%  |
| Unknown | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| SODIMM | 12        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 8         | 66.67%  |
| 8192  | 3         | 25%     |
| 16384 | 1         | 8.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 4266  | 7         | 58.33%  |
| 3200  | 3         | 25%     |
| 6400  | 1         | 8.33%   |
| 2667  | 1         | 8.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Dymo-CoStar     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| HP Laserjet CP1525nw        | 1         | 50%     |
| Dymo-CoStar LabelWriter 400 | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 15.38%  |
| Logitech                               | 6         | 11.54%  |
| Apple                                  | 5         | 9.62%   |
| Microdia                               | 4         | 7.69%   |
| Tripath Technology                     | 3         | 5.77%   |
| Sunplus Innovation Technology          | 3         | 5.77%   |
| Realtek Semiconductor                  | 3         | 5.77%   |
| Quanta                                 | 3         | 5.77%   |
| Acer                                   | 3         | 5.77%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.85%   |
| Valve Software                         | 1         | 1.92%   |
| Unknown                                | 1         | 1.92%   |
| Tobii Technology AB                    | 1         | 1.92%   |
| Syntek                                 | 1         | 1.92%   |
| Suyin                                  | 1         | 1.92%   |
| SunplusIT                              | 1         | 1.92%   |
| Samsung Electronics                    | 1         | 1.92%   |
| Magic Control Technology               | 1         | 1.92%   |
| Luxvisions Innotech Limited            | 1         | 1.92%   |
| IMC Networks                           | 1         | 1.92%   |
| Generalplus Technology                 | 1         | 1.92%   |
| AVerMedia Technologies                 | 1         | 1.92%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Tripath PC Camera                                                             | 3         | 5.77%   |
| Apple iPhone5/5C/5S/6                                                         | 3         | 5.77%   |
| Microdia Webcam Vitade AF                                                     | 2         | 3.85%   |
| Microdia Integrated_Webcam_HD                                                 | 2         | 3.85%   |
| Logitech HD Pro Webcam C920                                                   | 2         | 3.85%   |
| Chicony HD User Facing                                                        | 2         | 3.85%   |
| Acer Integrated Camera                                                        | 2         | 3.85%   |
| Valve Software 3D Camera                                                      | 1         | 1.92%   |
| Unknown 720p HD Camera                                                        | 1         | 1.92%   |
| Tobii AB EyeChip                                                              | 1         | 1.92%   |
| Syntek Integrated Camera                                                      | 1         | 1.92%   |
| Suyin HP Truevision HD                                                        | 1         | 1.92%   |
| SunplusIT CODi A05020 Webcam                                                  | 1         | 1.92%   |
| Sunplus USB 2.0 Camera                                                        | 1         | 1.92%   |
| Sunplus Integrated_Webcam_FHD                                                 | 1         | 1.92%   |
| Sunplus Asus Webcam                                                           | 1         | 1.92%   |
| Samsung Galaxy A5 (MTP)                                                       | 1         | 1.92%   |
| Realtek USB2.0 camera                                                         | 1         | 1.92%   |
| Realtek NexiGo N660P FHD Webcam                                               | 1         | 1.92%   |
| Realtek Integrated_Webcam_HD                                                  | 1         | 1.92%   |
| Quanta VGA WebCam                                                             | 1         | 1.92%   |
| Quanta HP Wide Vision HD Camera                                               | 1         | 1.92%   |
| Quanta HD Camera                                                              | 1         | 1.92%   |
| Magic Control j5 WebCam JVCU100                                               | 1         | 1.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                           | 1         | 1.92%   |
| Logitech Webcam C930e                                                         | 1         | 1.92%   |
| Logitech HD Webcam C615                                                       | 1         | 1.92%   |
| Logitech HD Webcam C525                                                       | 1         | 1.92%   |
| Logitech CrystalCam                                                           | 1         | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                                             | 1         | 1.92%   |
| Generalplus GENERAL WEBCAM                                                    | 1         | 1.92%   |
| Chicony USB2.0 HD UVC WebCam                                                  | 1         | 1.92%   |
| Chicony Integrated Camera (1280x720@30)                                       | 1         | 1.92%   |
| Chicony Integrated Camera                                                     | 1         | 1.92%   |
| Chicony HP Wide Vision HD Camera                                              | 1         | 1.92%   |
| Chicony HP TrueVision HD Camera                                               | 1         | 1.92%   |
| Chicony HP High Definition 1MP Webcam                                         | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) SunplusIT INC. HP Truevision HD Webcam | 1         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD                       | 1         | 1.92%   |
| AVerMedia Live Streamer CAM 313                                               | 1         | 1.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 1         | 25%     |
| Shenzhen Goodix Technology | 1         | 25%     |
| Focal-systems.Corp         | 1         | 25%     |
| Elan Microelectronics      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device         | 1         | 25%     |
| Focal-systems.Corp FT9201Fingerprint.       | 1         | 25%     |
| Elan fingerprint sensor [FeinTech FPS00200] | 1         | 25%     |
| Unknown                                     | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| SCM Microsystems | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| SCM Microsystems SCR3500 A Contact Reader | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 473       | 91.84%  |
| 1     | 31        | 6.02%   |
| 2     | 10        | 1.94%   |
| 4     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Multimedia controller | 19        | 35.85%  |
| Net/wireless          | 18        | 33.96%  |
| Graphics card         | 4         | 7.55%   |
| Fingerprint reader    | 4         | 7.55%   |
| Unassigned class      | 3         | 5.66%   |
| Storage/nvme          | 1         | 1.89%   |
| Sound                 | 1         | 1.89%   |
| Net/ethernet          | 1         | 1.89%   |
| Modem                 | 1         | 1.89%   |
| Chipcard              | 1         | 1.89%   |


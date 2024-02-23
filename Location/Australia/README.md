Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 6383

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [75c314c9bb](https://linux-hardware.org/?probe=75c314c9bb) | Feb 02, 2024 |
| Lenovo        | ThinkPad T580 20LAS3NJ0T    | Notebook    | [17e848cdcf](https://linux-hardware.org/?probe=17e848cdcf) | Feb 02, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [1579230b7f](https://linux-hardware.org/?probe=1579230b7f) | Feb 02, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [656bb7827a](https://linux-hardware.org/?probe=656bb7827a) | Feb 02, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [6d6e6af46b](https://linux-hardware.org/?probe=6d6e6af46b) | Feb 02, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [62dc25b8b6](https://linux-hardware.org/?probe=62dc25b8b6) | Feb 02, 2024 |
| COM1          | E15-5A165-BM (9)            | Notebook    | [41d123782c](https://linux-hardware.org/?probe=41d123782c) | Feb 01, 2024 |
| HP            | 843B                        | Desktop     | [161ffc2ea0](https://linux-hardware.org/?probe=161ffc2ea0) | Feb 01, 2024 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7bbfc4d26a](https://linux-hardware.org/?probe=7bbfc4d26a) | Feb 01, 2024 |
| Dell          | 0TDG4V A01                  | Desktop     | [d921cc13e3](https://linux-hardware.org/?probe=d921cc13e3) | Feb 01, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f659cc07fc](https://linux-hardware.org/?probe=f659cc07fc) | Feb 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [653f9c5fa5](https://linux-hardware.org/?probe=653f9c5fa5) | Feb 01, 2024 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [aaec148c06](https://linux-hardware.org/?probe=aaec148c06) | Feb 01, 2024 |
| Gigabyte      | G41MT-D3                    | Desktop     | [88c563b03e](https://linux-hardware.org/?probe=88c563b03e) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7adc6ac4b3](https://linux-hardware.org/?probe=7adc6ac4b3) | Feb 01, 2024 |
| HP            | 8598                        | Desktop     | [cc6faa2bfa](https://linux-hardware.org/?probe=cc6faa2bfa) | Feb 01, 2024 |
| Intel         | NUC8i7HNB J68197-602        | Mini pc     | [b3b6728f99](https://linux-hardware.org/?probe=b3b6728f99) | Feb 01, 2024 |
| Acer          | Veriton X4620G v1.0         | Desktop     | [0ce3db389e](https://linux-hardware.org/?probe=0ce3db389e) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [4e6e527f34](https://linux-hardware.org/?probe=4e6e527f34) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [16a348ccd1](https://linux-hardware.org/?probe=16a348ccd1) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [fc52040fc1](https://linux-hardware.org/?probe=fc52040fc1) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f833c48d57](https://linux-hardware.org/?probe=f833c48d57) | Feb 01, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [bc7890c0fe](https://linux-hardware.org/?probe=bc7890c0fe) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ef62bb8257](https://linux-hardware.org/?probe=ef62bb8257) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [841cef0b98](https://linux-hardware.org/?probe=841cef0b98) | Feb 01, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [7d06efe302](https://linux-hardware.org/?probe=7d06efe302) | Jan 31, 2024 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [ccf29ffd3d](https://linux-hardware.org/?probe=ccf29ffd3d) | Jan 31, 2024 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [aabd02c85c](https://linux-hardware.org/?probe=aabd02c85c) | Jan 30, 2024 |
| Dell          | 0TDG4V A01                  | Desktop     | [240d51778b](https://linux-hardware.org/?probe=240d51778b) | Jan 30, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [fd88489b46](https://linux-hardware.org/?probe=fd88489b46) | Jan 30, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [648e9e296d](https://linux-hardware.org/?probe=648e9e296d) | Jan 30, 2024 |
| HP            | 1495                        | Desktop     | [4fe224eb89](https://linux-hardware.org/?probe=4fe224eb89) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [cecfacb5dc](https://linux-hardware.org/?probe=cecfacb5dc) | Jan 29, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [f46d220d2e](https://linux-hardware.org/?probe=f46d220d2e) | Jan 28, 2024 |
| HP            | ProLiant ML10 v2            | Desktop     | [b16f323611](https://linux-hardware.org/?probe=b16f323611) | Jan 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f6021e243](https://linux-hardware.org/?probe=2f6021e243) | Jan 28, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [5116ee6ad3](https://linux-hardware.org/?probe=5116ee6ad3) | Jan 28, 2024 |
| Gigabyte      | P35-DS3P                    | Desktop     | [43b4bbf15f](https://linux-hardware.org/?probe=43b4bbf15f) | Jan 28, 2024 |
| Acer          | Spin SP314-21N              | Convertible | [e90ff686ca](https://linux-hardware.org/?probe=e90ff686ca) | Jan 28, 2024 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b86ad488c7](https://linux-hardware.org/?probe=b86ad488c7) | Jan 28, 2024 |
| Gigabyte      | X79-UP4                     | Desktop     | [32cafc74cf](https://linux-hardware.org/?probe=32cafc74cf) | Jan 28, 2024 |
| Medion        | D3F3-EM                     | Desktop     | [b49f3c529a](https://linux-hardware.org/?probe=b49f3c529a) | Jan 28, 2024 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [59ce08f802](https://linux-hardware.org/?probe=59ce08f802) | Jan 28, 2024 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [618155f762](https://linux-hardware.org/?probe=618155f762) | Jan 27, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e20cfe6ad1](https://linux-hardware.org/?probe=e20cfe6ad1) | Jan 27, 2024 |
| MSI           | Z97 PC Mate                 | Desktop     | [f4242c1634](https://linux-hardware.org/?probe=f4242c1634) | Jan 27, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7c90f3665f](https://linux-hardware.org/?probe=7c90f3665f) | Jan 27, 2024 |
| Gigabyte      | G41MT-D3                    | Desktop     | [327217e107](https://linux-hardware.org/?probe=327217e107) | Jan 27, 2024 |
| Dell          | 0HD5W2 A00                  | Desktop     | [9f1b82d7b4](https://linux-hardware.org/?probe=9f1b82d7b4) | Jan 26, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [b010be0d2f](https://linux-hardware.org/?probe=b010be0d2f) | Jan 26, 2024 |
| Dell          | Latitude 5500               | Notebook    | [870e89a969](https://linux-hardware.org/?probe=870e89a969) | Jan 26, 2024 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [f59710809d](https://linux-hardware.org/?probe=f59710809d) | Jan 26, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [ac31169eb1](https://linux-hardware.org/?probe=ac31169eb1) | Jan 25, 2024 |
| ASUSTek       | X507UA                      | Notebook    | [ebf2dc120a](https://linux-hardware.org/?probe=ebf2dc120a) | Jan 24, 2024 |
| Dell          | Latitude 7410               | Notebook    | [cbb6638a4d](https://linux-hardware.org/?probe=cbb6638a4d) | Jan 24, 2024 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [013bd103c2](https://linux-hardware.org/?probe=013bd103c2) | Jan 23, 2024 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ff02cafda6](https://linux-hardware.org/?probe=ff02cafda6) | Jan 23, 2024 |
| HP            | 843B                        | Desktop     | [cd727d0994](https://linux-hardware.org/?probe=cd727d0994) | Jan 23, 2024 |
| HP            | Compaq CQ45                 | Notebook    | [4ab36cf29f](https://linux-hardware.org/?probe=4ab36cf29f) | Jan 23, 2024 |
| Apple         | MacBookPro10,2              | Notebook    | [db7e0a0c8a](https://linux-hardware.org/?probe=db7e0a0c8a) | Jan 22, 2024 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [2c38517137](https://linux-hardware.org/?probe=2c38517137) | Jan 22, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [dfd9b8e3b0](https://linux-hardware.org/?probe=dfd9b8e3b0) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [52783252de](https://linux-hardware.org/?probe=52783252de) | Jan 21, 2024 |
| Panasonic     | FZG1-4                      | Notebook    | [78a30df588](https://linux-hardware.org/?probe=78a30df588) | Jan 21, 2024 |
| Lenovo        | ThinkPad T480 20L6S3C100    | Notebook    | [ef29c6e451](https://linux-hardware.org/?probe=ef29c6e451) | Jan 20, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [e9c31264ef](https://linux-hardware.org/?probe=e9c31264ef) | Jan 20, 2024 |
| HP            | 8055                        | Desktop     | [e895f1b502](https://linux-hardware.org/?probe=e895f1b502) | Jan 20, 2024 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [1fa1595fb5](https://linux-hardware.org/?probe=1fa1595fb5) | Jan 20, 2024 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [7c13b83bff](https://linux-hardware.org/?probe=7c13b83bff) | Jan 20, 2024 |
| Gigabyte      | 970A-D3P                    | Desktop     | [08462b24ba](https://linux-hardware.org/?probe=08462b24ba) | Jan 19, 2024 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [9e1182e93f](https://linux-hardware.org/?probe=9e1182e93f) | Jan 19, 2024 |
| HP            | 84EF 01100                  | All in one  | [b752ce050e](https://linux-hardware.org/?probe=b752ce050e) | Jan 19, 2024 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [11f478f041](https://linux-hardware.org/?probe=11f478f041) | Jan 18, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [6c329db1cf](https://linux-hardware.org/?probe=6c329db1cf) | Jan 18, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [16f764cb39](https://linux-hardware.org/?probe=16f764cb39) | Jan 18, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [624cf621cc](https://linux-hardware.org/?probe=624cf621cc) | Jan 18, 2024 |
| Dell          | Latitude 5500               | Notebook    | [eb9de73fa4](https://linux-hardware.org/?probe=eb9de73fa4) | Jan 18, 2024 |
| Dell          | Inspiron MM061              | Notebook    | [6415c1e543](https://linux-hardware.org/?probe=6415c1e543) | Jan 18, 2024 |
| Alienware     | 14                          | Notebook    | [a0109babcd](https://linux-hardware.org/?probe=a0109babcd) | Jan 18, 2024 |
| ASRock        | AD2700-ITX                  | Desktop     | [93eee675be](https://linux-hardware.org/?probe=93eee675be) | Jan 18, 2024 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [3c5d80f1e7](https://linux-hardware.org/?probe=3c5d80f1e7) | Jan 18, 2024 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [42e7298c19](https://linux-hardware.org/?probe=42e7298c19) | Jan 17, 2024 |
| Sony          | VPCEB46FG                   | Notebook    | [0e2c2caced](https://linux-hardware.org/?probe=0e2c2caced) | Jan 17, 2024 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [9d8436f707](https://linux-hardware.org/?probe=9d8436f707) | Jan 17, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJ00... | Convertible | [b0ea28a06c](https://linux-hardware.org/?probe=b0ea28a06c) | Jan 16, 2024 |
| Dell          | Inspiron N311z              | Notebook    | [e4163cacc4](https://linux-hardware.org/?probe=e4163cacc4) | Jan 16, 2024 |
| ASRock        | Z390 Taichi                 | Desktop     | [84a79a7e97](https://linux-hardware.org/?probe=84a79a7e97) | Jan 16, 2024 |
| Dell          | Inspiron 7570               | Notebook    | [bdea5ae4df](https://linux-hardware.org/?probe=bdea5ae4df) | Jan 16, 2024 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [636ad953ab](https://linux-hardware.org/?probe=636ad953ab) | Jan 16, 2024 |
| ASUSTek       | X580VD                      | Notebook    | [bf7addfd46](https://linux-hardware.org/?probe=bf7addfd46) | Jan 15, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [465e84985e](https://linux-hardware.org/?probe=465e84985e) | Jan 15, 2024 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [530c5882b9](https://linux-hardware.org/?probe=530c5882b9) | Jan 15, 2024 |
| Intel         | NUC7JYB J67970-402          | Mini pc     | [56ace1ed4a](https://linux-hardware.org/?probe=56ace1ed4a) | Jan 15, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a4234528de](https://linux-hardware.org/?probe=a4234528de) | Jan 14, 2024 |
| Dell          | 0TDG4V A01                  | Desktop     | [41ac0edbe0](https://linux-hardware.org/?probe=41ac0edbe0) | Jan 14, 2024 |
| ASRock        | B85M Pro3                   | Desktop     | [4c6a4813b0](https://linux-hardware.org/?probe=4c6a4813b0) | Jan 14, 2024 |
| MSI           | GP62M 7REX                  | Notebook    | [23c4fd0913](https://linux-hardware.org/?probe=23c4fd0913) | Jan 14, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [55b05d17b6](https://linux-hardware.org/?probe=55b05d17b6) | Jan 14, 2024 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [17dc5fdc19](https://linux-hardware.org/?probe=17dc5fdc19) | Jan 13, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [4560285085](https://linux-hardware.org/?probe=4560285085) | Jan 13, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [5f11aaf980](https://linux-hardware.org/?probe=5f11aaf980) | Jan 12, 2024 |
| HP            | 8055                        | Desktop     | [f92ba3c747](https://linux-hardware.org/?probe=f92ba3c747) | Jan 12, 2024 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [75a6760096](https://linux-hardware.org/?probe=75a6760096) | Jan 12, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [579cc62424](https://linux-hardware.org/?probe=579cc62424) | Jan 11, 2024 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [8a634f1a99](https://linux-hardware.org/?probe=8a634f1a99) | Jan 11, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [86f3a39f11](https://linux-hardware.org/?probe=86f3a39f11) | Jan 11, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [508859d8fd](https://linux-hardware.org/?probe=508859d8fd) | Jan 11, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [64df689564](https://linux-hardware.org/?probe=64df689564) | Jan 11, 2024 |
| MSI           | Bravo 15 C7VEK              | Notebook    | [d759cfb72e](https://linux-hardware.org/?probe=d759cfb72e) | Jan 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S3C100    | Notebook    | [c54acdce25](https://linux-hardware.org/?probe=c54acdce25) | Jan 10, 2024 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b48b4a8698](https://linux-hardware.org/?probe=b48b4a8698) | Jan 10, 2024 |
| HP            | Spectre x360 Convertible    | Convertible | [9b3c3e8174](https://linux-hardware.org/?probe=9b3c3e8174) | Jan 09, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [fc9099926d](https://linux-hardware.org/?probe=fc9099926d) | Jan 09, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [81043fcda6](https://linux-hardware.org/?probe=81043fcda6) | Jan 09, 2024 |
| Acer          | TM8573T                     | Notebook    | [69f3a0a145](https://linux-hardware.org/?probe=69f3a0a145) | Jan 09, 2024 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b0ac8e8208](https://linux-hardware.org/?probe=b0ac8e8208) | Jan 09, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [0d909c4177](https://linux-hardware.org/?probe=0d909c4177) | Jan 08, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8b1e8e6fe4](https://linux-hardware.org/?probe=8b1e8e6fe4) | Jan 08, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS3... | Convertible | [5a278ad2e2](https://linux-hardware.org/?probe=5a278ad2e2) | Jan 08, 2024 |
| ASUSTek       | ROG STRIX B350-I GAMING     | Desktop     | [d0756ed224](https://linux-hardware.org/?probe=d0756ed224) | Jan 08, 2024 |
| Dell          | Precision 5680              | Notebook    | [047734c28f](https://linux-hardware.org/?probe=047734c28f) | Jan 08, 2024 |
| Dell          | Precision 5570              | Notebook    | [acc6213478](https://linux-hardware.org/?probe=acc6213478) | Jan 08, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [d9208968c5](https://linux-hardware.org/?probe=d9208968c5) | Jan 08, 2024 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [8362692262](https://linux-hardware.org/?probe=8362692262) | Jan 08, 2024 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [56376a3558](https://linux-hardware.org/?probe=56376a3558) | Jan 07, 2024 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [96907e78c1](https://linux-hardware.org/?probe=96907e78c1) | Jan 07, 2024 |
| Dell          | Precision 5680              | Notebook    | [0d58e93f98](https://linux-hardware.org/?probe=0d58e93f98) | Jan 06, 2024 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dda07da31a](https://linux-hardware.org/?probe=dda07da31a) | Jan 06, 2024 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [d273ae013f](https://linux-hardware.org/?probe=d273ae013f) | Jan 06, 2024 |
| Gigabyte      | G41MT-D3                    | Desktop     | [a78a3d75b9](https://linux-hardware.org/?probe=a78a3d75b9) | Jan 06, 2024 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [e131bcc2a6](https://linux-hardware.org/?probe=e131bcc2a6) | Jan 06, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [0d79087015](https://linux-hardware.org/?probe=0d79087015) | Jan 05, 2024 |
| MSI           | MS-7142                     | Desktop     | [f2d4db6983](https://linux-hardware.org/?probe=f2d4db6983) | Jan 05, 2024 |
| ASUSTek       | PN52                        | Mini pc     | [5c770765da](https://linux-hardware.org/?probe=5c770765da) | Jan 05, 2024 |
| MSI           | MS-7142                     | Desktop     | [679ea97c9a](https://linux-hardware.org/?probe=679ea97c9a) | Jan 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [3d47c0ba48](https://linux-hardware.org/?probe=3d47c0ba48) | Jan 04, 2024 |
| ASUSTek       | TUF B360M-E GAMING          | Desktop     | [453e5e7b1a](https://linux-hardware.org/?probe=453e5e7b1a) | Jan 04, 2024 |
| ASUSTek       | X705UDR                     | Notebook    | [02cec34b2e](https://linux-hardware.org/?probe=02cec34b2e) | Jan 04, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a83656b1fd](https://linux-hardware.org/?probe=a83656b1fd) | Jan 04, 2024 |
| Gigabyte      | G31M-S2L                    | Desktop     | [14ef56bddf](https://linux-hardware.org/?probe=14ef56bddf) | Jan 03, 2024 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [73c3f784f9](https://linux-hardware.org/?probe=73c3f784f9) | Jan 03, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [71d03730b7](https://linux-hardware.org/?probe=71d03730b7) | Jan 03, 2024 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [59769c2318](https://linux-hardware.org/?probe=59769c2318) | Jan 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [d29c58fd8a](https://linux-hardware.org/?probe=d29c58fd8a) | Jan 03, 2024 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [2b1a79920a](https://linux-hardware.org/?probe=2b1a79920a) | Jan 03, 2024 |
| Dell          | Inspiron MM061              | Notebook    | [34d48e27b3](https://linux-hardware.org/?probe=34d48e27b3) | Jan 03, 2024 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [9712812ff0](https://linux-hardware.org/?probe=9712812ff0) | Jan 03, 2024 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0f0e24cce5](https://linux-hardware.org/?probe=0f0e24cce5) | Jan 03, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [f115f9696c](https://linux-hardware.org/?probe=f115f9696c) | Jan 02, 2024 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [240b255830](https://linux-hardware.org/?probe=240b255830) | Jan 02, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [e5c35b5d54](https://linux-hardware.org/?probe=e5c35b5d54) | Jan 02, 2024 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [db100cd948](https://linux-hardware.org/?probe=db100cd948) | Jan 02, 2024 |
| System76      | Oryx Pro                    | Notebook    | [07e4e6a0a8](https://linux-hardware.org/?probe=07e4e6a0a8) | Jan 02, 2024 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [82877fbf5e](https://linux-hardware.org/?probe=82877fbf5e) | Jan 01, 2024 |
| Acer          | Spin SP314-21N              | Convertible | [a58ed9a59b](https://linux-hardware.org/?probe=a58ed9a59b) | Jan 01, 2024 |
| MSI           | B250M PRO-VD                | Desktop     | [f0cb030b5f](https://linux-hardware.org/?probe=f0cb030b5f) | Jan 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [b16497fbfc](https://linux-hardware.org/?probe=b16497fbfc) | Jan 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [3be8582d82](https://linux-hardware.org/?probe=3be8582d82) | Jan 01, 2024 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [553c16eb6c](https://linux-hardware.org/?probe=553c16eb6c) | Jan 01, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ab74a1228a](https://linux-hardware.org/?probe=ab74a1228a) | Jan 01, 2024 |
| Apple         | MacBookPro10,2              | Notebook    | [386449d6f7](https://linux-hardware.org/?probe=386449d6f7) | Dec 31, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [586b998af3](https://linux-hardware.org/?probe=586b998af3) | Dec 31, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [a68ce92fec](https://linux-hardware.org/?probe=a68ce92fec) | Dec 31, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [83ef33bf03](https://linux-hardware.org/?probe=83ef33bf03) | Dec 31, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [daee98e116](https://linux-hardware.org/?probe=daee98e116) | Dec 31, 2023 |
| Lenovo        | ThinkPad P43s 20RHCTO1WW    | Notebook    | [7b1fe348e4](https://linux-hardware.org/?probe=7b1fe348e4) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | Notebook    | [7130d1a699](https://linux-hardware.org/?probe=7130d1a699) | Dec 31, 2023 |
| Acer          | Nitro AN16-41               | Notebook    | [d04c4d749f](https://linux-hardware.org/?probe=d04c4d749f) | Dec 31, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [5ded7ca887](https://linux-hardware.org/?probe=5ded7ca887) | Dec 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [090ed6d6f3](https://linux-hardware.org/?probe=090ed6d6f3) | Dec 30, 2023 |
| Acer          | Spin SP314-21N              | Convertible | [4605e31e7d](https://linux-hardware.org/?probe=4605e31e7d) | Dec 30, 2023 |
| Acer          | Spin SP314-21N              | Convertible | [4f7ad65c82](https://linux-hardware.org/?probe=4f7ad65c82) | Dec 30, 2023 |
| Metabox       | Alpha-X NH58HP              | Notebook    | [983844e1c8](https://linux-hardware.org/?probe=983844e1c8) | Dec 30, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [442c87e7d9](https://linux-hardware.org/?probe=442c87e7d9) | Dec 30, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [3296b05cf8](https://linux-hardware.org/?probe=3296b05cf8) | Dec 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c607e5ffec](https://linux-hardware.org/?probe=c607e5ffec) | Dec 29, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0060... | Notebook    | [485c94e992](https://linux-hardware.org/?probe=485c94e992) | Dec 29, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [d91ba814ed](https://linux-hardware.org/?probe=d91ba814ed) | Dec 29, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [3357d873d5](https://linux-hardware.org/?probe=3357d873d5) | Dec 28, 2023 |
| HP            | 8055                        | Desktop     | [0829ea2c26](https://linux-hardware.org/?probe=0829ea2c26) | Dec 28, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [5ef2e29839](https://linux-hardware.org/?probe=5ef2e29839) | Dec 27, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [d476db4ac3](https://linux-hardware.org/?probe=d476db4ac3) | Dec 27, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [282f8845af](https://linux-hardware.org/?probe=282f8845af) | Dec 27, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [8625448d34](https://linux-hardware.org/?probe=8625448d34) | Dec 27, 2023 |
| Shuttle       | DS10U                       | Desktop     | [333bcd6641](https://linux-hardware.org/?probe=333bcd6641) | Dec 26, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [22b65c12f2](https://linux-hardware.org/?probe=22b65c12f2) | Dec 26, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [53f503a6e5](https://linux-hardware.org/?probe=53f503a6e5) | Dec 26, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [4736deb84b](https://linux-hardware.org/?probe=4736deb84b) | Dec 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0W32L    | Notebook    | [55200b6aa5](https://linux-hardware.org/?probe=55200b6aa5) | Dec 26, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [3fd8513ee7](https://linux-hardware.org/?probe=3fd8513ee7) | Dec 26, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [96c4736340](https://linux-hardware.org/?probe=96c4736340) | Dec 26, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [1003211f6d](https://linux-hardware.org/?probe=1003211f6d) | Dec 26, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [034adc4ac8](https://linux-hardware.org/?probe=034adc4ac8) | Dec 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2a8ca288fb](https://linux-hardware.org/?probe=2a8ca288fb) | Dec 25, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [22bbfabce0](https://linux-hardware.org/?probe=22bbfabce0) | Dec 25, 2023 |
| Acer          | Aspire A5SP14-51MTN         | Convertible | [873ace2728](https://linux-hardware.org/?probe=873ace2728) | Dec 25, 2023 |
| sunxi         | Unknown                     | Soc         | [fb46535d30](https://linux-hardware.org/?probe=fb46535d30) | Dec 25, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [357709050e](https://linux-hardware.org/?probe=357709050e) | Dec 25, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [b29541d467](https://linux-hardware.org/?probe=b29541d467) | Dec 24, 2023 |
| Panasonic     | FZG1-4                      | Notebook    | [f6c98a5b67](https://linux-hardware.org/?probe=f6c98a5b67) | Dec 24, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [cccb18ead9](https://linux-hardware.org/?probe=cccb18ead9) | Dec 24, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [334b43f409](https://linux-hardware.org/?probe=334b43f409) | Dec 24, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [7f4061fd49](https://linux-hardware.org/?probe=7f4061fd49) | Dec 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [51eda90982](https://linux-hardware.org/?probe=51eda90982) | Dec 23, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [dd2248530b](https://linux-hardware.org/?probe=dd2248530b) | Dec 23, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [da46ad37d3](https://linux-hardware.org/?probe=da46ad37d3) | Dec 23, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7cf925bed4](https://linux-hardware.org/?probe=7cf925bed4) | Dec 23, 2023 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [05b49062ef](https://linux-hardware.org/?probe=05b49062ef) | Dec 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4da8d961c0](https://linux-hardware.org/?probe=4da8d961c0) | Dec 23, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [d7f5fd2175](https://linux-hardware.org/?probe=d7f5fd2175) | Dec 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9e269e6a94](https://linux-hardware.org/?probe=9e269e6a94) | Dec 23, 2023 |
| HP            | ENVY 15                     | Notebook    | [2997ffe5cf](https://linux-hardware.org/?probe=2997ffe5cf) | Dec 22, 2023 |
| Framework     | Laptop (13th Gen Intel C... | Notebook    | [fa4275395f](https://linux-hardware.org/?probe=fa4275395f) | Dec 22, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [1a4d75f062](https://linux-hardware.org/?probe=1a4d75f062) | Dec 22, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [f3f83a4f0a](https://linux-hardware.org/?probe=f3f83a4f0a) | Dec 22, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [9acf6baf05](https://linux-hardware.org/?probe=9acf6baf05) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [55109c1bbc](https://linux-hardware.org/?probe=55109c1bbc) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [bbd22340fc](https://linux-hardware.org/?probe=bbd22340fc) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [6911b47a19](https://linux-hardware.org/?probe=6911b47a19) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [fd80bdeaed](https://linux-hardware.org/?probe=fd80bdeaed) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [ac7383c630](https://linux-hardware.org/?probe=ac7383c630) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [7b862a6a81](https://linux-hardware.org/?probe=7b862a6a81) | Dec 22, 2023 |
| Intel         | S1200SP H57532-210          | Server      | [8edff49a96](https://linux-hardware.org/?probe=8edff49a96) | Dec 22, 2023 |
| Intel         | S1200RP_SE G62252-408       | Server      | [3e27ac63c6](https://linux-hardware.org/?probe=3e27ac63c6) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [17dd42b383](https://linux-hardware.org/?probe=17dd42b383) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [e50bd82756](https://linux-hardware.org/?probe=e50bd82756) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [2194b0ad9c](https://linux-hardware.org/?probe=2194b0ad9c) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [c334514b1f](https://linux-hardware.org/?probe=c334514b1f) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [761eebee94](https://linux-hardware.org/?probe=761eebee94) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [b6608c7603](https://linux-hardware.org/?probe=b6608c7603) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [33bccf75e0](https://linux-hardware.org/?probe=33bccf75e0) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [59b5ebb0c3](https://linux-hardware.org/?probe=59b5ebb0c3) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [0c51eb213d](https://linux-hardware.org/?probe=0c51eb213d) | Dec 22, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [347eec7ee9](https://linux-hardware.org/?probe=347eec7ee9) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [561a4c0809](https://linux-hardware.org/?probe=561a4c0809) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [27115feb62](https://linux-hardware.org/?probe=27115feb62) | Dec 22, 2023 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [3ce597e06a](https://linux-hardware.org/?probe=3ce597e06a) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [be34427eb1](https://linux-hardware.org/?probe=be34427eb1) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [496ad2d93b](https://linux-hardware.org/?probe=496ad2d93b) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [d0bce14740](https://linux-hardware.org/?probe=d0bce14740) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5fb5668250](https://linux-hardware.org/?probe=5fb5668250) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [caad19d314](https://linux-hardware.org/?probe=caad19d314) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [b1c0126e05](https://linux-hardware.org/?probe=b1c0126e05) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [d1c63c1a0b](https://linux-hardware.org/?probe=d1c63c1a0b) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [a42bd5e717](https://linux-hardware.org/?probe=a42bd5e717) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [a75998d2da](https://linux-hardware.org/?probe=a75998d2da) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [b55f33d76e](https://linux-hardware.org/?probe=b55f33d76e) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [49e9a2f26f](https://linux-hardware.org/?probe=49e9a2f26f) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [8c3370c21e](https://linux-hardware.org/?probe=8c3370c21e) | Dec 22, 2023 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [94de79174c](https://linux-hardware.org/?probe=94de79174c) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [59bc9b5d02](https://linux-hardware.org/?probe=59bc9b5d02) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [87af1005b8](https://linux-hardware.org/?probe=87af1005b8) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [55570e65a7](https://linux-hardware.org/?probe=55570e65a7) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [eea4397d45](https://linux-hardware.org/?probe=eea4397d45) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [b32df5066d](https://linux-hardware.org/?probe=b32df5066d) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [a949e7fa06](https://linux-hardware.org/?probe=a949e7fa06) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [e2b4e10140](https://linux-hardware.org/?probe=e2b4e10140) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [87c9436145](https://linux-hardware.org/?probe=87c9436145) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [b3a3b91d1d](https://linux-hardware.org/?probe=b3a3b91d1d) | Dec 22, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [0ae8561f0a](https://linux-hardware.org/?probe=0ae8561f0a) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [2f23b66d3b](https://linux-hardware.org/?probe=2f23b66d3b) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [617899113a](https://linux-hardware.org/?probe=617899113a) | Dec 22, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [3092182d1d](https://linux-hardware.org/?probe=3092182d1d) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [3f48c50868](https://linux-hardware.org/?probe=3f48c50868) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [cac98c44ed](https://linux-hardware.org/?probe=cac98c44ed) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [6d0e82b783](https://linux-hardware.org/?probe=6d0e82b783) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [afd422517d](https://linux-hardware.org/?probe=afd422517d) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [1db23ed649](https://linux-hardware.org/?probe=1db23ed649) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [8ed791bd6d](https://linux-hardware.org/?probe=8ed791bd6d) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5a63cf039d](https://linux-hardware.org/?probe=5a63cf039d) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [46e2b13b34](https://linux-hardware.org/?probe=46e2b13b34) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [d09a9c1d0b](https://linux-hardware.org/?probe=d09a9c1d0b) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [9181bd8696](https://linux-hardware.org/?probe=9181bd8696) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [67188e1b67](https://linux-hardware.org/?probe=67188e1b67) | Dec 22, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [75e2601753](https://linux-hardware.org/?probe=75e2601753) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [83d6013a05](https://linux-hardware.org/?probe=83d6013a05) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [86e58bba42](https://linux-hardware.org/?probe=86e58bba42) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [6b6c41afa2](https://linux-hardware.org/?probe=6b6c41afa2) | Dec 22, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [635fdfc9be](https://linux-hardware.org/?probe=635fdfc9be) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [057ea7f38a](https://linux-hardware.org/?probe=057ea7f38a) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [0318224393](https://linux-hardware.org/?probe=0318224393) | Dec 22, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [6f2b8275b2](https://linux-hardware.org/?probe=6f2b8275b2) | Dec 22, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [4cd5825edf](https://linux-hardware.org/?probe=4cd5825edf) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [3e070bb5d3](https://linux-hardware.org/?probe=3e070bb5d3) | Dec 22, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [c3140237d9](https://linux-hardware.org/?probe=c3140237d9) | Dec 22, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [2169da8737](https://linux-hardware.org/?probe=2169da8737) | Dec 22, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [968400d838](https://linux-hardware.org/?probe=968400d838) | Dec 22, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [18fc29611b](https://linux-hardware.org/?probe=18fc29611b) | Dec 22, 2023 |
| Gigabyte      | MZ72-HB0-00 01020102        | Server      | [771f7edd98](https://linux-hardware.org/?probe=771f7edd98) | Dec 22, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [49e514e9c4](https://linux-hardware.org/?probe=49e514e9c4) | Dec 21, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [0cf7feafe8](https://linux-hardware.org/?probe=0cf7feafe8) | Dec 21, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [dca266a251](https://linux-hardware.org/?probe=dca266a251) | Dec 21, 2023 |
| sunxi         | Unknown                     | Soc         | [07307d0820](https://linux-hardware.org/?probe=07307d0820) | Dec 21, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [b9409f01d5](https://linux-hardware.org/?probe=b9409f01d5) | Dec 21, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [3a065e8d32](https://linux-hardware.org/?probe=3a065e8d32) | Dec 21, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [47d1d26375](https://linux-hardware.org/?probe=47d1d26375) | Dec 21, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [70147072be](https://linux-hardware.org/?probe=70147072be) | Dec 21, 2023 |
| Dell          | Precision 5680              | Notebook    | [b8b5bc0292](https://linux-hardware.org/?probe=b8b5bc0292) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [bc7fc2be74](https://linux-hardware.org/?probe=bc7fc2be74) | Dec 20, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [58517da295](https://linux-hardware.org/?probe=58517da295) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [11f3b9c9d6](https://linux-hardware.org/?probe=11f3b9c9d6) | Dec 20, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [6a962e40ec](https://linux-hardware.org/?probe=6a962e40ec) | Dec 19, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [925bd9bbac](https://linux-hardware.org/?probe=925bd9bbac) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [1bd33b2c6b](https://linux-hardware.org/?probe=1bd33b2c6b) | Dec 18, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [c66e6657fe](https://linux-hardware.org/?probe=c66e6657fe) | Dec 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6db91b5eb2](https://linux-hardware.org/?probe=6db91b5eb2) | Dec 18, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [8629995933](https://linux-hardware.org/?probe=8629995933) | Dec 17, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [02e1fcae39](https://linux-hardware.org/?probe=02e1fcae39) | Dec 17, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [c878de7adb](https://linux-hardware.org/?probe=c878de7adb) | Dec 17, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [941de66870](https://linux-hardware.org/?probe=941de66870) | Dec 17, 2023 |
| Toshiba       | PORTEGE Z20t-C              | Notebook    | [eb941689a4](https://linux-hardware.org/?probe=eb941689a4) | Dec 17, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [9f0d5821e3](https://linux-hardware.org/?probe=9f0d5821e3) | Dec 16, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [adc736fc8d](https://linux-hardware.org/?probe=adc736fc8d) | Dec 16, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [6458d64d28](https://linux-hardware.org/?probe=6458d64d28) | Dec 16, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [39e7517ac6](https://linux-hardware.org/?probe=39e7517ac6) | Dec 16, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJ00... | Convertible | [5382e06902](https://linux-hardware.org/?probe=5382e06902) | Dec 16, 2023 |
| Dell          | 0RY007                      | Desktop     | [162add826a](https://linux-hardware.org/?probe=162add826a) | Dec 16, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [68a9708e6a](https://linux-hardware.org/?probe=68a9708e6a) | Dec 16, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [34a66d3cef](https://linux-hardware.org/?probe=34a66d3cef) | Dec 15, 2023 |
| Gigabyte      | B760M D3H DDR4              | Desktop     | [339b5b1b33](https://linux-hardware.org/?probe=339b5b1b33) | Dec 15, 2023 |
| Shuttle       | DS10U                       | Desktop     | [2b28414f3d](https://linux-hardware.org/?probe=2b28414f3d) | Dec 14, 2023 |
| Shuttle       | DS10U                       | Desktop     | [0a9d211454](https://linux-hardware.org/?probe=0a9d211454) | Dec 14, 2023 |
| HP            | 212B                        | Desktop     | [1ce8b8d929](https://linux-hardware.org/?probe=1ce8b8d929) | Dec 14, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f170615f49](https://linux-hardware.org/?probe=f170615f49) | Dec 14, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [27c22f0c94](https://linux-hardware.org/?probe=27c22f0c94) | Dec 14, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [b5b534e106](https://linux-hardware.org/?probe=b5b534e106) | Dec 14, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [6da01d5871](https://linux-hardware.org/?probe=6da01d5871) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [7c84d77c07](https://linux-hardware.org/?probe=7c84d77c07) | Dec 14, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [0a2b707101](https://linux-hardware.org/?probe=0a2b707101) | Dec 13, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [e49be74129](https://linux-hardware.org/?probe=e49be74129) | Dec 13, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [017252c955](https://linux-hardware.org/?probe=017252c955) | Dec 13, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [5fc8de17bb](https://linux-hardware.org/?probe=5fc8de17bb) | Dec 13, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [625439b5a5](https://linux-hardware.org/?probe=625439b5a5) | Dec 13, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [25a03e3488](https://linux-hardware.org/?probe=25a03e3488) | Dec 13, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [12c2204715](https://linux-hardware.org/?probe=12c2204715) | Dec 12, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [45cc0c507d](https://linux-hardware.org/?probe=45cc0c507d) | Dec 12, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [7471a7b26e](https://linux-hardware.org/?probe=7471a7b26e) | Dec 12, 2023 |
| ASUSTek       | Maximus V GENE              | Desktop     | [fb88caee81](https://linux-hardware.org/?probe=fb88caee81) | Dec 12, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [dceaa713f6](https://linux-hardware.org/?probe=dceaa713f6) | Dec 12, 2023 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [514227865f](https://linux-hardware.org/?probe=514227865f) | Dec 12, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [90fce6c777](https://linux-hardware.org/?probe=90fce6c777) | Dec 11, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [d22fb3a791](https://linux-hardware.org/?probe=d22fb3a791) | Dec 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [b78720dbf3](https://linux-hardware.org/?probe=b78720dbf3) | Dec 11, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [f706bd9261](https://linux-hardware.org/?probe=f706bd9261) | Dec 11, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [6c83c2bec6](https://linux-hardware.org/?probe=6c83c2bec6) | Dec 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [4e40941aef](https://linux-hardware.org/?probe=4e40941aef) | Dec 11, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [069b020cd5](https://linux-hardware.org/?probe=069b020cd5) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [2aef9deafb](https://linux-hardware.org/?probe=2aef9deafb) | Dec 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [99fa9c84ca](https://linux-hardware.org/?probe=99fa9c84ca) | Dec 10, 2023 |
| LattePanda    | Sigma                       | Desktop     | [4c33e7d514](https://linux-hardware.org/?probe=4c33e7d514) | Dec 10, 2023 |
| Gigabyte      | P55A-UD4                    | Desktop     | [f7a1a6172f](https://linux-hardware.org/?probe=f7a1a6172f) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e35af0e70a](https://linux-hardware.org/?probe=e35af0e70a) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9f3fb37b64](https://linux-hardware.org/?probe=9f3fb37b64) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | Desktop     | [26c99ed573](https://linux-hardware.org/?probe=26c99ed573) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [634d1d56b8](https://linux-hardware.org/?probe=634d1d56b8) | Dec 09, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [0ee42c0440](https://linux-hardware.org/?probe=0ee42c0440) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [afc78e9ba2](https://linux-hardware.org/?probe=afc78e9ba2) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [a6b0055398](https://linux-hardware.org/?probe=a6b0055398) | Dec 08, 2023 |
| Lenovo        | ThinkPad Mini10 3507A31     | Notebook    | [1229fd52f5](https://linux-hardware.org/?probe=1229fd52f5) | Dec 08, 2023 |
| Acer          | Extensa 4210                | Notebook    | [4f8a82394a](https://linux-hardware.org/?probe=4f8a82394a) | Dec 07, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [7843d89bd3](https://linux-hardware.org/?probe=7843d89bd3) | Dec 07, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [5183612439](https://linux-hardware.org/?probe=5183612439) | Dec 07, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [fc9cdcbc63](https://linux-hardware.org/?probe=fc9cdcbc63) | Dec 07, 2023 |
| Samsung       | Galaxy TabPro S             | Tablet      | [ca9c01eb88](https://linux-hardware.org/?probe=ca9c01eb88) | Dec 06, 2023 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [086d8b6cd1](https://linux-hardware.org/?probe=086d8b6cd1) | Dec 06, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [fb50a6bd26](https://linux-hardware.org/?probe=fb50a6bd26) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bed4fa69c4](https://linux-hardware.org/?probe=bed4fa69c4) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [52cdd2c7b2](https://linux-hardware.org/?probe=52cdd2c7b2) | Dec 06, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [12c6da7b14](https://linux-hardware.org/?probe=12c6da7b14) | Dec 05, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [7b0120def9](https://linux-hardware.org/?probe=7b0120def9) | Dec 05, 2023 |
| ASUSTek       | V-P7H55E                    | Desktop     | [c20a63636f](https://linux-hardware.org/?probe=c20a63636f) | Dec 05, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [3681f281ac](https://linux-hardware.org/?probe=3681f281ac) | Dec 05, 2023 |
| Dell          | Latitude E6410              | Notebook    | [65b6e47cf8](https://linux-hardware.org/?probe=65b6e47cf8) | Dec 04, 2023 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [aeae361474](https://linux-hardware.org/?probe=aeae361474) | Dec 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [4e67d597e1](https://linux-hardware.org/?probe=4e67d597e1) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4c8abee905](https://linux-hardware.org/?probe=4c8abee905) | Dec 03, 2023 |
| Dell          | 07F37C A00                  | Desktop     | [685253bf96](https://linux-hardware.org/?probe=685253bf96) | Dec 03, 2023 |
| HP            | 3397                        | Desktop     | [b6c4db2738](https://linux-hardware.org/?probe=b6c4db2738) | Dec 03, 2023 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [94317ffd1f](https://linux-hardware.org/?probe=94317ffd1f) | Dec 02, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [a827e0cc16](https://linux-hardware.org/?probe=a827e0cc16) | Dec 02, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [0d2ac061a9](https://linux-hardware.org/?probe=0d2ac061a9) | Dec 02, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5b61695af2](https://linux-hardware.org/?probe=5b61695af2) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [a9f72ce2ae](https://linux-hardware.org/?probe=a9f72ce2ae) | Dec 01, 2023 |
| HP            | 805D                        | Desktop     | [4733a9082a](https://linux-hardware.org/?probe=4733a9082a) | Dec 01, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [44ad415f8f](https://linux-hardware.org/?probe=44ad415f8f) | Dec 01, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [23e7e70bc6](https://linux-hardware.org/?probe=23e7e70bc6) | Dec 01, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [0ed139ee9c](https://linux-hardware.org/?probe=0ed139ee9c) | Dec 01, 2023 |
| Dell          | 014GRG A03                  | Desktop     | [581d6ec42f](https://linux-hardware.org/?probe=581d6ec42f) | Nov 30, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [215e772a98](https://linux-hardware.org/?probe=215e772a98) | Nov 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [f71053bf5c](https://linux-hardware.org/?probe=f71053bf5c) | Nov 30, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [81aca77f2e](https://linux-hardware.org/?probe=81aca77f2e) | Nov 30, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b23f24b006](https://linux-hardware.org/?probe=b23f24b006) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming FX705DU_FX705... | Notebook    | [c781f63b2a](https://linux-hardware.org/?probe=c781f63b2a) | Nov 30, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [be4ecb6dfa](https://linux-hardware.org/?probe=be4ecb6dfa) | Nov 29, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [bf583ba008](https://linux-hardware.org/?probe=bf583ba008) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [e6c589b9b0](https://linux-hardware.org/?probe=e6c589b9b0) | Nov 29, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [028d79b006](https://linux-hardware.org/?probe=028d79b006) | Nov 29, 2023 |
| Dell          | 0V0D45 A01                  | All in one  | [1976be5d27](https://linux-hardware.org/?probe=1976be5d27) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [62cb0079ed](https://linux-hardware.org/?probe=62cb0079ed) | Nov 29, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [bb86b33f71](https://linux-hardware.org/?probe=bb86b33f71) | Nov 28, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [b2dd77b768](https://linux-hardware.org/?probe=b2dd77b768) | Nov 28, 2023 |
| HP            | 8055                        | Desktop     | [a35b553ba1](https://linux-hardware.org/?probe=a35b553ba1) | Nov 28, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [88bee4d4f2](https://linux-hardware.org/?probe=88bee4d4f2) | Nov 28, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [20e52e5c9b](https://linux-hardware.org/?probe=20e52e5c9b) | Nov 28, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [09dfe90de1](https://linux-hardware.org/?probe=09dfe90de1) | Nov 28, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [0a8209a7e9](https://linux-hardware.org/?probe=0a8209a7e9) | Nov 28, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [9b85473f0f](https://linux-hardware.org/?probe=9b85473f0f) | Nov 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [aadba04a83](https://linux-hardware.org/?probe=aadba04a83) | Nov 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [4d59532412](https://linux-hardware.org/?probe=4d59532412) | Nov 27, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [af4437b421](https://linux-hardware.org/?probe=af4437b421) | Nov 27, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [2bb0010426](https://linux-hardware.org/?probe=2bb0010426) | Nov 27, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b71948f3b9](https://linux-hardware.org/?probe=b71948f3b9) | Nov 27, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [1256303ece](https://linux-hardware.org/?probe=1256303ece) | Nov 26, 2023 |
| HP            | 245 G6 Notebook PC          | Notebook    | [0b00139036](https://linux-hardware.org/?probe=0b00139036) | Nov 26, 2023 |
| Shenzhen M... | F7BSC                       | Mini pc     | [ea77c54dd3](https://linux-hardware.org/?probe=ea77c54dd3) | Nov 26, 2023 |
| Gigabyte      | B560M DS3H AC               | Desktop     | [906f471cf6](https://linux-hardware.org/?probe=906f471cf6) | Nov 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e09777761c](https://linux-hardware.org/?probe=e09777761c) | Nov 26, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [4b886fb042](https://linux-hardware.org/?probe=4b886fb042) | Nov 26, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [4f4c868c9a](https://linux-hardware.org/?probe=4f4c868c9a) | Nov 26, 2023 |
| Dell          | Vostro 3401                 | Notebook    | [3496a45338](https://linux-hardware.org/?probe=3496a45338) | Nov 25, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [f8200e619a](https://linux-hardware.org/?probe=f8200e619a) | Nov 25, 2023 |
| Dell          | 0XDN97 A02                  | Server      | [0f4391e6bf](https://linux-hardware.org/?probe=0f4391e6bf) | Nov 25, 2023 |
| Matsushita... | CF-30FCDALAM                | Notebook    | [94d60b91d5](https://linux-hardware.org/?probe=94d60b91d5) | Nov 25, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [7e541895b2](https://linux-hardware.org/?probe=7e541895b2) | Nov 25, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [39af83330a](https://linux-hardware.org/?probe=39af83330a) | Nov 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [436499a8a7](https://linux-hardware.org/?probe=436499a8a7) | Nov 25, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [6a4204f060](https://linux-hardware.org/?probe=6a4204f060) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [145e6fbb42](https://linux-hardware.org/?probe=145e6fbb42) | Nov 24, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a4af0718ed](https://linux-hardware.org/?probe=a4af0718ed) | Nov 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [b3287ea2f2](https://linux-hardware.org/?probe=b3287ea2f2) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [dbce2ba706](https://linux-hardware.org/?probe=dbce2ba706) | Nov 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [a4f7cad00f](https://linux-hardware.org/?probe=a4f7cad00f) | Nov 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [bdb118e120](https://linux-hardware.org/?probe=bdb118e120) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [6ca712a0bb](https://linux-hardware.org/?probe=6ca712a0bb) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [09108a2bc4](https://linux-hardware.org/?probe=09108a2bc4) | Nov 22, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [abb0181b70](https://linux-hardware.org/?probe=abb0181b70) | Nov 22, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [07b43fd48f](https://linux-hardware.org/?probe=07b43fd48f) | Nov 22, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [9eb5267c48](https://linux-hardware.org/?probe=9eb5267c48) | Nov 22, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [d38bf64de1](https://linux-hardware.org/?probe=d38bf64de1) | Nov 22, 2023 |
| Supermicro    | X10SDV-8C-TLN4F             | Server      | [4b79ce361d](https://linux-hardware.org/?probe=4b79ce361d) | Nov 21, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [be841a1ee6](https://linux-hardware.org/?probe=be841a1ee6) | Nov 19, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [cc99141ae2](https://linux-hardware.org/?probe=cc99141ae2) | Nov 19, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [ac3283c49b](https://linux-hardware.org/?probe=ac3283c49b) | Nov 19, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [737ddab002](https://linux-hardware.org/?probe=737ddab002) | Nov 19, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2ccdec1495](https://linux-hardware.org/?probe=2ccdec1495) | Nov 19, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [253859ae2a](https://linux-hardware.org/?probe=253859ae2a) | Nov 19, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [866a100b18](https://linux-hardware.org/?probe=866a100b18) | Nov 19, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [507f6c2a0d](https://linux-hardware.org/?probe=507f6c2a0d) | Nov 19, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [8ebb2df251](https://linux-hardware.org/?probe=8ebb2df251) | Nov 18, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [80f392bd0d](https://linux-hardware.org/?probe=80f392bd0d) | Nov 18, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [77b9c09532](https://linux-hardware.org/?probe=77b9c09532) | Nov 18, 2023 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [2565965b03](https://linux-hardware.org/?probe=2565965b03) | Nov 18, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [aebca817af](https://linux-hardware.org/?probe=aebca817af) | Nov 18, 2023 |
| Toshiba       | PORTEGE Z20t-B              | Notebook    | [052540adc3](https://linux-hardware.org/?probe=052540adc3) | Nov 18, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [dc208dca03](https://linux-hardware.org/?probe=dc208dca03) | Nov 18, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [fb9543ab29](https://linux-hardware.org/?probe=fb9543ab29) | Nov 17, 2023 |
| HP            | 83E2                        | Desktop     | [89267eedbb](https://linux-hardware.org/?probe=89267eedbb) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [11a05c0944](https://linux-hardware.org/?probe=11a05c0944) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | Notebook    | [f61bc8d881](https://linux-hardware.org/?probe=f61bc8d881) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [3486cc9544](https://linux-hardware.org/?probe=3486cc9544) | Nov 17, 2023 |
| Lenovo        | ThinkPad T590 20N4S02F00    | Notebook    | [53dd735333](https://linux-hardware.org/?probe=53dd735333) | Nov 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [24ea543d99](https://linux-hardware.org/?probe=24ea543d99) | Nov 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [029e25867a](https://linux-hardware.org/?probe=029e25867a) | Nov 17, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [d7673aaf5a](https://linux-hardware.org/?probe=d7673aaf5a) | Nov 17, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [f072eeb8d6](https://linux-hardware.org/?probe=f072eeb8d6) | Nov 17, 2023 |
| Dell          | 0HGFJM A00                  | Desktop     | [7ef2b1b168](https://linux-hardware.org/?probe=7ef2b1b168) | Nov 17, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [ce6593b1f0](https://linux-hardware.org/?probe=ce6593b1f0) | Nov 17, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [19753f50b2](https://linux-hardware.org/?probe=19753f50b2) | Nov 16, 2023 |
| Lenovo        | ThinkPad E550 20DF001HAU    | Notebook    | [44968b500c](https://linux-hardware.org/?probe=44968b500c) | Nov 16, 2023 |
| HP            | 1998                        | Desktop     | [eb9bb55c96](https://linux-hardware.org/?probe=eb9bb55c96) | Nov 16, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1c21a56b5c](https://linux-hardware.org/?probe=1c21a56b5c) | Nov 15, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f4cd8d065](https://linux-hardware.org/?probe=3f4cd8d065) | Nov 14, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [c33072abbc](https://linux-hardware.org/?probe=c33072abbc) | Nov 14, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [121f68381f](https://linux-hardware.org/?probe=121f68381f) | Nov 14, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [95eda79d27](https://linux-hardware.org/?probe=95eda79d27) | Nov 14, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [3ad9fc243a](https://linux-hardware.org/?probe=3ad9fc243a) | Nov 14, 2023 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [73ef67d393](https://linux-hardware.org/?probe=73ef67d393) | Nov 13, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [bd156c9515](https://linux-hardware.org/?probe=bd156c9515) | Nov 13, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [f886eb50fa](https://linux-hardware.org/?probe=f886eb50fa) | Nov 13, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [d0809a2221](https://linux-hardware.org/?probe=d0809a2221) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [47d681f4e6](https://linux-hardware.org/?probe=47d681f4e6) | Nov 13, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [4e24a48715](https://linux-hardware.org/?probe=4e24a48715) | Nov 13, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [474f3dea0b](https://linux-hardware.org/?probe=474f3dea0b) | Nov 13, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | Desktop     | [27f69cd90a](https://linux-hardware.org/?probe=27f69cd90a) | Nov 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [018fda89b5](https://linux-hardware.org/?probe=018fda89b5) | Nov 12, 2023 |
| Intel         | NUC5i5RYB H40999-505        | Mini pc     | [26e08a35c7](https://linux-hardware.org/?probe=26e08a35c7) | Nov 12, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [d9b24edac8](https://linux-hardware.org/?probe=d9b24edac8) | Nov 11, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [687a21becc](https://linux-hardware.org/?probe=687a21becc) | Nov 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [8cffc9f03f](https://linux-hardware.org/?probe=8cffc9f03f) | Nov 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [fbdbf6175e](https://linux-hardware.org/?probe=fbdbf6175e) | Nov 11, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a49fe13ac0](https://linux-hardware.org/?probe=a49fe13ac0) | Nov 11, 2023 |
| HP            | Pavilion g6                 | Notebook    | [1215d8475b](https://linux-hardware.org/?probe=1215d8475b) | Nov 11, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [36bbafb1f9](https://linux-hardware.org/?probe=36bbafb1f9) | Nov 11, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [9fcef5c1ff](https://linux-hardware.org/?probe=9fcef5c1ff) | Nov 10, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [ecc5d08bd8](https://linux-hardware.org/?probe=ecc5d08bd8) | Nov 10, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [62ccd07f15](https://linux-hardware.org/?probe=62ccd07f15) | Nov 10, 2023 |
| HP            | 8054                        | Desktop     | [6883c29ae6](https://linux-hardware.org/?probe=6883c29ae6) | Nov 10, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [ab3577cc31](https://linux-hardware.org/?probe=ab3577cc31) | Nov 09, 2023 |
| HP            | 3397                        | Desktop     | [67e178009d](https://linux-hardware.org/?probe=67e178009d) | Nov 09, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [b1610ff76c](https://linux-hardware.org/?probe=b1610ff76c) | Nov 09, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [27e7e9866d](https://linux-hardware.org/?probe=27e7e9866d) | Nov 09, 2023 |
| Dell          | Precision 5520              | Notebook    | [1166f1d95d](https://linux-hardware.org/?probe=1166f1d95d) | Nov 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [751f4b0d96](https://linux-hardware.org/?probe=751f4b0d96) | Nov 08, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [cf1d5863ed](https://linux-hardware.org/?probe=cf1d5863ed) | Nov 08, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [fa4f95f3e2](https://linux-hardware.org/?probe=fa4f95f3e2) | Nov 08, 2023 |
| Microsoft     | Surface Book                | Tablet      | [67575d0e41](https://linux-hardware.org/?probe=67575d0e41) | Nov 08, 2023 |
| Apple         | MacBookPro13,1              | Notebook    | [e5ae7e8a94](https://linux-hardware.org/?probe=e5ae7e8a94) | Nov 07, 2023 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [ef772812b1](https://linux-hardware.org/?probe=ef772812b1) | Nov 07, 2023 |
| Dell          | G7 7700                     | Notebook    | [0fc7811fdd](https://linux-hardware.org/?probe=0fc7811fdd) | Nov 07, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [3f60e901a4](https://linux-hardware.org/?probe=3f60e901a4) | Nov 07, 2023 |
| Acer          | TM8573T                     | Notebook    | [d78cdb2bdc](https://linux-hardware.org/?probe=d78cdb2bdc) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [94fdbbd7bd](https://linux-hardware.org/?probe=94fdbbd7bd) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [231b5b8ef8](https://linux-hardware.org/?probe=231b5b8ef8) | Nov 06, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [b88b3757af](https://linux-hardware.org/?probe=b88b3757af) | Nov 06, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [bfe1423965](https://linux-hardware.org/?probe=bfe1423965) | Nov 06, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [c8e2ba1336](https://linux-hardware.org/?probe=c8e2ba1336) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | Notebook    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e1d50d8743](https://linux-hardware.org/?probe=e1d50d8743) | Nov 05, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2cc662a279](https://linux-hardware.org/?probe=2cc662a279) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d74f909776](https://linux-hardware.org/?probe=d74f909776) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| HP            | 83E1                        | Desktop     | [c82d34ebac](https://linux-hardware.org/?probe=c82d34ebac) | Nov 04, 2023 |
| Sony          | SVE15137CGW                 | Notebook    | [5d2a4746af](https://linux-hardware.org/?probe=5d2a4746af) | Nov 04, 2023 |
| HP            | 843B                        | Desktop     | [8fdaf74414](https://linux-hardware.org/?probe=8fdaf74414) | Nov 03, 2023 |
| HP            | 843B                        | Desktop     | [ba22079238](https://linux-hardware.org/?probe=ba22079238) | Nov 03, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [9d9b09db51](https://linux-hardware.org/?probe=9d9b09db51) | Nov 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [3a4be91563](https://linux-hardware.org/?probe=3a4be91563) | Nov 03, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [044aa1f9b5](https://linux-hardware.org/?probe=044aa1f9b5) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [75a224b797](https://linux-hardware.org/?probe=75a224b797) | Nov 02, 2023 |
| Dell          | 0WPG9H A00                  | All in one  | [30565eabec](https://linux-hardware.org/?probe=30565eabec) | Nov 02, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [ae11e0443c](https://linux-hardware.org/?probe=ae11e0443c) | Nov 02, 2023 |
| Dell          | 03KWTV A00                  | Desktop     | [4bce32e210](https://linux-hardware.org/?probe=4bce32e210) | Nov 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d73c8ca742](https://linux-hardware.org/?probe=d73c8ca742) | Nov 01, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [92b5f4172e](https://linux-hardware.org/?probe=92b5f4172e) | Nov 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [168597b33e](https://linux-hardware.org/?probe=168597b33e) | Nov 01, 2023 |
| HP            | 2AF7                        | Desktop     | [0a2c239b75](https://linux-hardware.org/?probe=0a2c239b75) | Nov 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [b5bd58d350](https://linux-hardware.org/?probe=b5bd58d350) | Oct 31, 2023 |
| MSI           | Creator 15 A11UE            | Notebook    | [e8b0c2a2b5](https://linux-hardware.org/?probe=e8b0c2a2b5) | Oct 31, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [90fc87e07a](https://linux-hardware.org/?probe=90fc87e07a) | Oct 31, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [5d99367248](https://linux-hardware.org/?probe=5d99367248) | Oct 31, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [e131dccf11](https://linux-hardware.org/?probe=e131dccf11) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | Notebook    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [e73e0881d6](https://linux-hardware.org/?probe=e73e0881d6) | Oct 30, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ab707308db](https://linux-hardware.org/?probe=ab707308db) | Oct 30, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [649b911963](https://linux-hardware.org/?probe=649b911963) | Oct 29, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [bc2ed6322b](https://linux-hardware.org/?probe=bc2ed6322b) | Oct 29, 2023 |
| Gigabyte      | B450 GAMING X               | Desktop     | [c1785bec94](https://linux-hardware.org/?probe=c1785bec94) | Oct 29, 2023 |
| Google        | Taniks                      | Notebook    | [c864f19e03](https://linux-hardware.org/?probe=c864f19e03) | Oct 28, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [944bb2ecb2](https://linux-hardware.org/?probe=944bb2ecb2) | Oct 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [96b76fc377](https://linux-hardware.org/?probe=96b76fc377) | Oct 28, 2023 |
| HP            | 158A                        | Desktop     | [f8fe5be681](https://linux-hardware.org/?probe=f8fe5be681) | Oct 28, 2023 |
| HP            | 8399                        | Desktop     | [35351ed170](https://linux-hardware.org/?probe=35351ed170) | Oct 27, 2023 |
| Dell          | Latitude 5430               | Notebook    | [af33081c9b](https://linux-hardware.org/?probe=af33081c9b) | Oct 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [db2952a9d8](https://linux-hardware.org/?probe=db2952a9d8) | Oct 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [3bc6d6cfda](https://linux-hardware.org/?probe=3bc6d6cfda) | Oct 27, 2023 |
| HP            | 21B4 A01                    | Desktop     | [8f2a8dec3a](https://linux-hardware.org/?probe=8f2a8dec3a) | Oct 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [755d25d933](https://linux-hardware.org/?probe=755d25d933) | Oct 26, 2023 |
| HP            | 158A                        | Desktop     | [86f988197b](https://linux-hardware.org/?probe=86f988197b) | Oct 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d69762902a](https://linux-hardware.org/?probe=d69762902a) | Oct 25, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [1fde726024](https://linux-hardware.org/?probe=1fde726024) | Oct 25, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [455780b267](https://linux-hardware.org/?probe=455780b267) | Oct 25, 2023 |
| Acer          | Veriton N4640G              | Desktop     | [ccba40d7a9](https://linux-hardware.org/?probe=ccba40d7a9) | Oct 24, 2023 |
| Acer          | Aspire V3-572               | Notebook    | [f873d7efd9](https://linux-hardware.org/?probe=f873d7efd9) | Oct 24, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [279929b8c5](https://linux-hardware.org/?probe=279929b8c5) | Oct 24, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [833d4435d4](https://linux-hardware.org/?probe=833d4435d4) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | Notebook    | [5fbee8e341](https://linux-hardware.org/?probe=5fbee8e341) | Oct 24, 2023 |
| MSI           | GP62M 7REX                  | Notebook    | [a95ab8b563](https://linux-hardware.org/?probe=a95ab8b563) | Oct 24, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [492563a83c](https://linux-hardware.org/?probe=492563a83c) | Oct 24, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3e4b32b047](https://linux-hardware.org/?probe=3e4b32b047) | Oct 24, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f15ecd1759](https://linux-hardware.org/?probe=f15ecd1759) | Oct 24, 2023 |
| Acer          | Aspire V3-572               | Notebook    | [974d64f7a8](https://linux-hardware.org/?probe=974d64f7a8) | Oct 23, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [932adc1d60](https://linux-hardware.org/?probe=932adc1d60) | Oct 23, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [d21c4ec9dd](https://linux-hardware.org/?probe=d21c4ec9dd) | Oct 23, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [7c86d9f1e5](https://linux-hardware.org/?probe=7c86d9f1e5) | Oct 23, 2023 |
| HP            | 8055                        | Desktop     | [aeee934c45](https://linux-hardware.org/?probe=aeee934c45) | Oct 23, 2023 |
| Dell          | Latitude 5430               | Notebook    | [8d552380c4](https://linux-hardware.org/?probe=8d552380c4) | Oct 23, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [ce5ff412d1](https://linux-hardware.org/?probe=ce5ff412d1) | Oct 23, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [1f16388df7](https://linux-hardware.org/?probe=1f16388df7) | Oct 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6b90afaeb1](https://linux-hardware.org/?probe=6b90afaeb1) | Oct 22, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [dac0aa7f70](https://linux-hardware.org/?probe=dac0aa7f70) | Oct 22, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [310d794691](https://linux-hardware.org/?probe=310d794691) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| HP            | ProBook 4340s               | Notebook    | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| Unknown       | GB01                        | Desktop     | [5c0f72d3f0](https://linux-hardware.org/?probe=5c0f72d3f0) | Oct 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [2fc9736b9e](https://linux-hardware.org/?probe=2fc9736b9e) | Oct 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7514db3c84](https://linux-hardware.org/?probe=7514db3c84) | Oct 22, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [218908299a](https://linux-hardware.org/?probe=218908299a) | Oct 21, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [85894d27fe](https://linux-hardware.org/?probe=85894d27fe) | Oct 21, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [8b5e97d193](https://linux-hardware.org/?probe=8b5e97d193) | Oct 21, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [984eba244a](https://linux-hardware.org/?probe=984eba244a) | Oct 20, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [7cd181ad3b](https://linux-hardware.org/?probe=7cd181ad3b) | Oct 20, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [09ad44bf2e](https://linux-hardware.org/?probe=09ad44bf2e) | Oct 19, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [8f7a837f4f](https://linux-hardware.org/?probe=8f7a837f4f) | Oct 19, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [0c16d31374](https://linux-hardware.org/?probe=0c16d31374) | Oct 18, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [71eba7e232](https://linux-hardware.org/?probe=71eba7e232) | Oct 18, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ffeb95bd95](https://linux-hardware.org/?probe=ffeb95bd95) | Oct 17, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [b605b832db](https://linux-hardware.org/?probe=b605b832db) | Oct 16, 2023 |
| Shuttle       | FD37V10                     | Desktop     | [929e944dd3](https://linux-hardware.org/?probe=929e944dd3) | Oct 15, 2023 |
| Shuttle       | FD37V10                     | Desktop     | [d9043c11bd](https://linux-hardware.org/?probe=d9043c11bd) | Oct 15, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [27881eaaac](https://linux-hardware.org/?probe=27881eaaac) | Oct 15, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [cf477f62d0](https://linux-hardware.org/?probe=cf477f62d0) | Oct 15, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [4e585c2b99](https://linux-hardware.org/?probe=4e585c2b99) | Oct 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [9d77b16e0b](https://linux-hardware.org/?probe=9d77b16e0b) | Oct 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [618fcf6a1e](https://linux-hardware.org/?probe=618fcf6a1e) | Oct 14, 2023 |
| HP            | Laptop 15s-du4xxx           | Notebook    | [8bec0ea3db](https://linux-hardware.org/?probe=8bec0ea3db) | Oct 14, 2023 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [f35263745a](https://linux-hardware.org/?probe=f35263745a) | Oct 14, 2023 |
| ASRock        | H87 Performance             | Desktop     | [5d1713de03](https://linux-hardware.org/?probe=5d1713de03) | Oct 13, 2023 |
| HP            | Notebook                    | Notebook    | [221bc048b5](https://linux-hardware.org/?probe=221bc048b5) | Oct 13, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [107524e9ec](https://linux-hardware.org/?probe=107524e9ec) | Oct 12, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [f9fee05f72](https://linux-hardware.org/?probe=f9fee05f72) | Oct 12, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [c6c1d1b3d1](https://linux-hardware.org/?probe=c6c1d1b3d1) | Oct 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | Notebook    | [e6c5f903ce](https://linux-hardware.org/?probe=e6c5f903ce) | Oct 12, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| ASUSTek       | K42F                        | Notebook    | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [73219cd20b](https://linux-hardware.org/?probe=73219cd20b) | Oct 10, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8091bb0ceb](https://linux-hardware.org/?probe=8091bb0ceb) | Oct 10, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53a1dce896](https://linux-hardware.org/?probe=53a1dce896) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [2d033cba6c](https://linux-hardware.org/?probe=2d033cba6c) | Oct 08, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [e66ce305a4](https://linux-hardware.org/?probe=e66ce305a4) | Oct 08, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [8ea6db3dbb](https://linux-hardware.org/?probe=8ea6db3dbb) | Oct 08, 2023 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [335b7035bc](https://linux-hardware.org/?probe=335b7035bc) | Oct 08, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [6a98464415](https://linux-hardware.org/?probe=6a98464415) | Oct 07, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [d2f93dac29](https://linux-hardware.org/?probe=d2f93dac29) | Oct 07, 2023 |
| HP            | 158A                        | Desktop     | [c2cb1b9180](https://linux-hardware.org/?probe=c2cb1b9180) | Oct 07, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [59c96d1008](https://linux-hardware.org/?probe=59c96d1008) | Oct 07, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d8d241531e](https://linux-hardware.org/?probe=d8d241531e) | Oct 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [9b6cb6738d](https://linux-hardware.org/?probe=9b6cb6738d) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [ad60cd6e18](https://linux-hardware.org/?probe=ad60cd6e18) | Oct 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [dd213b27e1](https://linux-hardware.org/?probe=dd213b27e1) | Oct 06, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [d8f9e7b32a](https://linux-hardware.org/?probe=d8f9e7b32a) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [ae798c007e](https://linux-hardware.org/?probe=ae798c007e) | Oct 05, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [3aea9e7d2f](https://linux-hardware.org/?probe=3aea9e7d2f) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [1deaeb248b](https://linux-hardware.org/?probe=1deaeb248b) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [226b534a32](https://linux-hardware.org/?probe=226b534a32) | Oct 04, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [08f5cef7f3](https://linux-hardware.org/?probe=08f5cef7f3) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dfec5c18d5](https://linux-hardware.org/?probe=dfec5c18d5) | Oct 04, 2023 |
| MSI           | PR600                       | Notebook    | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| Dell          | Latitude E7440              | Notebook    | [3cb4fc2857](https://linux-hardware.org/?probe=3cb4fc2857) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [efcc70945c](https://linux-hardware.org/?probe=efcc70945c) | Oct 03, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [42b70488ca](https://linux-hardware.org/?probe=42b70488ca) | Oct 03, 2023 |
| HP            | 802E                        | Desktop     | [2d84b83c17](https://linux-hardware.org/?probe=2d84b83c17) | Oct 03, 2023 |
| HP            | 802E                        | Desktop     | [10fcb68621](https://linux-hardware.org/?probe=10fcb68621) | Oct 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [66ee93331d](https://linux-hardware.org/?probe=66ee93331d) | Oct 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b992cbe7ae](https://linux-hardware.org/?probe=b992cbe7ae) | Oct 02, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b5fcc0da7b](https://linux-hardware.org/?probe=b5fcc0da7b) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [a7374560fe](https://linux-hardware.org/?probe=a7374560fe) | Oct 02, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2c55283681](https://linux-hardware.org/?probe=2c55283681) | Oct 02, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [5488654867](https://linux-hardware.org/?probe=5488654867) | Oct 02, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [2f046de8e8](https://linux-hardware.org/?probe=2f046de8e8) | Oct 02, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [e26d66c131](https://linux-hardware.org/?probe=e26d66c131) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [21f405ccbe](https://linux-hardware.org/?probe=21f405ccbe) | Oct 01, 2023 |
| Toshiba       | Satellite P750              | Notebook    | [6edbfaa1b1](https://linux-hardware.org/?probe=6edbfaa1b1) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [def4633785](https://linux-hardware.org/?probe=def4633785) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c99f28b27d](https://linux-hardware.org/?probe=c99f28b27d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288f5f8266](https://linux-hardware.org/?probe=288f5f8266) | Sep 30, 2023 |
| Metabox       | Prime-X X170KM              | Notebook    | [8ab33a8bd3](https://linux-hardware.org/?probe=8ab33a8bd3) | Sep 30, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [751b4d268a](https://linux-hardware.org/?probe=751b4d268a) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [f1cc7e5a93](https://linux-hardware.org/?probe=f1cc7e5a93) | Sep 30, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [51d10770c6](https://linux-hardware.org/?probe=51d10770c6) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [c69ab4bc0f](https://linux-hardware.org/?probe=c69ab4bc0f) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [4a7b1ee936](https://linux-hardware.org/?probe=4a7b1ee936) | Sep 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c25eeffab1](https://linux-hardware.org/?probe=c25eeffab1) | Sep 28, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [001231c730](https://linux-hardware.org/?probe=001231c730) | Sep 28, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b0c2b630a6](https://linux-hardware.org/?probe=b0c2b630a6) | Sep 28, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [1331a57778](https://linux-hardware.org/?probe=1331a57778) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [7b6ee612cf](https://linux-hardware.org/?probe=7b6ee612cf) | Sep 27, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [a4d1820df5](https://linux-hardware.org/?probe=a4d1820df5) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60600b4f0](https://linux-hardware.org/?probe=c60600b4f0) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [5bf8234727](https://linux-hardware.org/?probe=5bf8234727) | Sep 25, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [c834abf6b2](https://linux-hardware.org/?probe=c834abf6b2) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [bf8f7a55ae](https://linux-hardware.org/?probe=bf8f7a55ae) | Sep 24, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [a426f4a94e](https://linux-hardware.org/?probe=a426f4a94e) | Sep 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [25c109d366](https://linux-hardware.org/?probe=25c109d366) | Sep 24, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3346cccd71](https://linux-hardware.org/?probe=3346cccd71) | Sep 24, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [ade3d11822](https://linux-hardware.org/?probe=ade3d11822) | Sep 24, 2023 |
| HP            | 843B                        | Desktop     | [4e11e8ae1a](https://linux-hardware.org/?probe=4e11e8ae1a) | Sep 24, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [919d36ddd8](https://linux-hardware.org/?probe=919d36ddd8) | Sep 24, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | 1905                        | Desktop     | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| Panasonic     | FZG1-4                      | Notebook    | [bb4677655e](https://linux-hardware.org/?probe=bb4677655e) | Sep 23, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [2867e39109](https://linux-hardware.org/?probe=2867e39109) | Sep 23, 2023 |
| HP            | 3397                        | Desktop     | [fa230ba389](https://linux-hardware.org/?probe=fa230ba389) | Sep 23, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ce0f2babca](https://linux-hardware.org/?probe=ce0f2babca) | Sep 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Dell          | Precision 5680              | Notebook    | [55deb46665](https://linux-hardware.org/?probe=55deb46665) | Sep 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [a879a0a88f](https://linux-hardware.org/?probe=a879a0a88f) | Sep 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [3762f344e9](https://linux-hardware.org/?probe=3762f344e9) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c5e9108ee7](https://linux-hardware.org/?probe=c5e9108ee7) | Sep 20, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [af48b03e82](https://linux-hardware.org/?probe=af48b03e82) | Sep 20, 2023 |
| Dell          | Precision 5560              | Notebook    | [456e9e2c78](https://linux-hardware.org/?probe=456e9e2c78) | Sep 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [624ebbd6c1](https://linux-hardware.org/?probe=624ebbd6c1) | Sep 20, 2023 |
| Dell          | Precision 5680              | Notebook    | [a75a75f080](https://linux-hardware.org/?probe=a75a75f080) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [7a6c8c1d0a](https://linux-hardware.org/?probe=7a6c8c1d0a) | Sep 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6f7974b0f0](https://linux-hardware.org/?probe=6f7974b0f0) | Sep 20, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [01e90212e5](https://linux-hardware.org/?probe=01e90212e5) | Sep 20, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [71d11373aa](https://linux-hardware.org/?probe=71d11373aa) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [1bd6653d3e](https://linux-hardware.org/?probe=1bd6653d3e) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [eeeb11e211](https://linux-hardware.org/?probe=eeeb11e211) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | Notebook    | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Framework     | Laptop                      | Notebook    | [f379873c4b](https://linux-hardware.org/?probe=f379873c4b) | Sep 19, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [39d6e8a728](https://linux-hardware.org/?probe=39d6e8a728) | Sep 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [7e05f3299f](https://linux-hardware.org/?probe=7e05f3299f) | Sep 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [82e9cc2c9a](https://linux-hardware.org/?probe=82e9cc2c9a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | Notebook    | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [91a3ecf449](https://linux-hardware.org/?probe=91a3ecf449) | Sep 18, 2023 |
| HP            | 8158 A01                    | Mini pc     | [bd8aa3d09c](https://linux-hardware.org/?probe=bd8aa3d09c) | Sep 18, 2023 |
| HP            | 1998                        | Desktop     | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ab8cb379a8](https://linux-hardware.org/?probe=ab8cb379a8) | Sep 17, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [42bb973998](https://linux-hardware.org/?probe=42bb973998) | Sep 16, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [d5c797d43b](https://linux-hardware.org/?probe=d5c797d43b) | Sep 16, 2023 |
| Dell          | 0Y56T3 A01                  | Desktop     | [0ecd730eca](https://linux-hardware.org/?probe=0ecd730eca) | Sep 16, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LHS... | Convertible | [e18d005071](https://linux-hardware.org/?probe=e18d005071) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| Lenovo        | ThinkCentre M58 7360BB6     | Desktop     | [cb32849dcc](https://linux-hardware.org/?probe=cb32849dcc) | Sep 16, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [7c2d7aeafa](https://linux-hardware.org/?probe=7c2d7aeafa) | Sep 15, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [f76358580b](https://linux-hardware.org/?probe=f76358580b) | Sep 15, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [e9d6d94486](https://linux-hardware.org/?probe=e9d6d94486) | Sep 15, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dd637b6425](https://linux-hardware.org/?probe=dd637b6425) | Sep 15, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [7d79af3d22](https://linux-hardware.org/?probe=7d79af3d22) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [20ec05f55b](https://linux-hardware.org/?probe=20ec05f55b) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [172b7a1d48](https://linux-hardware.org/?probe=172b7a1d48) | Sep 13, 2023 |
| Dell          | XPS L322X                   | Notebook    | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| ASRock        | B360M-HDV                   | Desktop     | [d4b0ae4d0c](https://linux-hardware.org/?probe=d4b0ae4d0c) | Sep 11, 2023 |
| Dell          | XPS L322X                   | Notebook    | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| Dell          | 0GM819                      | Desktop     | [f7d8bdb2a3](https://linux-hardware.org/?probe=f7d8bdb2a3) | Sep 10, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [a875b11982](https://linux-hardware.org/?probe=a875b11982) | Sep 10, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | Desktop     | [5cb0ed682a](https://linux-hardware.org/?probe=5cb0ed682a) | Sep 10, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [5b2fda7ad6](https://linux-hardware.org/?probe=5b2fda7ad6) | Sep 09, 2023 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [0e97d18f32](https://linux-hardware.org/?probe=0e97d18f32) | Sep 09, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [7b02c70750](https://linux-hardware.org/?probe=7b02c70750) | Sep 09, 2023 |
| Gigabyte      | Q87M-MK                     | Desktop     | [1c45c834fe](https://linux-hardware.org/?probe=1c45c834fe) | Sep 09, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [0940dc7ebd](https://linux-hardware.org/?probe=0940dc7ebd) | Sep 08, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [fac3b5ba62](https://linux-hardware.org/?probe=fac3b5ba62) | Sep 08, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [6bea6e300b](https://linux-hardware.org/?probe=6bea6e300b) | Sep 07, 2023 |
| Dell          | 0J37VM A01                  | Desktop     | [7781be38be](https://linux-hardware.org/?probe=7781be38be) | Sep 07, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [43f205483a](https://linux-hardware.org/?probe=43f205483a) | Sep 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [d4ca58e970](https://linux-hardware.org/?probe=d4ca58e970) | Sep 07, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6cbfa96139](https://linux-hardware.org/?probe=6cbfa96139) | Sep 07, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [f0c3188082](https://linux-hardware.org/?probe=f0c3188082) | Sep 07, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [2285c5c493](https://linux-hardware.org/?probe=2285c5c493) | Sep 06, 2023 |
| Dell          | 0PC5F7 A00                  | Desktop     | [9ffb575d81](https://linux-hardware.org/?probe=9ffb575d81) | Sep 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [c43f7a6e53](https://linux-hardware.org/?probe=c43f7a6e53) | Sep 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f421de992d](https://linux-hardware.org/?probe=f421de992d) | Sep 06, 2023 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [9dd5c2a861](https://linux-hardware.org/?probe=9dd5c2a861) | Sep 06, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [10bb2b77f8](https://linux-hardware.org/?probe=10bb2b77f8) | Sep 06, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [7db6779b5c](https://linux-hardware.org/?probe=7db6779b5c) | Sep 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [51b40f3137](https://linux-hardware.org/?probe=51b40f3137) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [0fa982f7ad](https://linux-hardware.org/?probe=0fa982f7ad) | Sep 05, 2023 |
| ASRock        | AD525PV3                    | Desktop     | [9ab25d4913](https://linux-hardware.org/?probe=9ab25d4913) | Sep 05, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [d20cf2e835](https://linux-hardware.org/?probe=d20cf2e835) | Sep 05, 2023 |
| Gigabyte      | Z590 AORUS MASTER           | Desktop     | [40785211e9](https://linux-hardware.org/?probe=40785211e9) | Sep 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [318d03cfad](https://linux-hardware.org/?probe=318d03cfad) | Sep 04, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [362e60bccc](https://linux-hardware.org/?probe=362e60bccc) | Sep 04, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [ae41ba8b62](https://linux-hardware.org/?probe=ae41ba8b62) | Sep 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6cbaac077e](https://linux-hardware.org/?probe=6cbaac077e) | Sep 03, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [16b96480a2](https://linux-hardware.org/?probe=16b96480a2) | Sep 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [bf3a5838f0](https://linux-hardware.org/?probe=bf3a5838f0) | Sep 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [b53cd78958](https://linux-hardware.org/?probe=b53cd78958) | Sep 02, 2023 |
| Dell          | G15 5520                    | Notebook    | [796ae7cf79](https://linux-hardware.org/?probe=796ae7cf79) | Sep 02, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [7cfd1c36d1](https://linux-hardware.org/?probe=7cfd1c36d1) | Sep 02, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [59677d7116](https://linux-hardware.org/?probe=59677d7116) | Sep 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [da8d60051c](https://linux-hardware.org/?probe=da8d60051c) | Sep 02, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [9a208331c5](https://linux-hardware.org/?probe=9a208331c5) | Sep 01, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [f3c99a0cc5](https://linux-hardware.org/?probe=f3c99a0cc5) | Sep 01, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [17e3dd86e8](https://linux-hardware.org/?probe=17e3dd86e8) | Sep 01, 2023 |
| Dell          | Latitude E7470              | Notebook    | [0580f1c293](https://linux-hardware.org/?probe=0580f1c293) | Sep 01, 2023 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [1c496aba4a](https://linux-hardware.org/?probe=1c496aba4a) | Sep 01, 2023 |
| Lenovo        | Legion Slim 7 16IRH8 82Y... | Notebook    | [ab14d9d9bb](https://linux-hardware.org/?probe=ab14d9d9bb) | Aug 31, 2023 |
| Dell          | Latitude 7340               | Notebook    | [d6d1df94f5](https://linux-hardware.org/?probe=d6d1df94f5) | Aug 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [a99931801d](https://linux-hardware.org/?probe=a99931801d) | Aug 31, 2023 |
| HP            | ENVY m6                     | Notebook    | [eea19d891e](https://linux-hardware.org/?probe=eea19d891e) | Aug 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [84ed05802d](https://linux-hardware.org/?probe=84ed05802d) | Aug 31, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [9a459d2372](https://linux-hardware.org/?probe=9a459d2372) | Aug 31, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ffb1e72844](https://linux-hardware.org/?probe=ffb1e72844) | Aug 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [3aaefe5b81](https://linux-hardware.org/?probe=3aaefe5b81) | Aug 31, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [7741e9850b](https://linux-hardware.org/?probe=7741e9850b) | Aug 31, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [4f320554b6](https://linux-hardware.org/?probe=4f320554b6) | Aug 31, 2023 |
| HP            | 843B                        | Desktop     | [472228092a](https://linux-hardware.org/?probe=472228092a) | Aug 31, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [21ec7587ed](https://linux-hardware.org/?probe=21ec7587ed) | Aug 30, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9782f69f43](https://linux-hardware.org/?probe=9782f69f43) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [ea2ba90391](https://linux-hardware.org/?probe=ea2ba90391) | Aug 30, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [13b77d8273](https://linux-hardware.org/?probe=13b77d8273) | Aug 30, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [77cdb6f4a4](https://linux-hardware.org/?probe=77cdb6f4a4) | Aug 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [6eca0a231c](https://linux-hardware.org/?probe=6eca0a231c) | Aug 30, 2023 |
| Dell          | Latitude 3350               | Notebook    | [4fa556a69f](https://linux-hardware.org/?probe=4fa556a69f) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [dc4910965c](https://linux-hardware.org/?probe=dc4910965c) | Aug 29, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [a2f594cf56](https://linux-hardware.org/?probe=a2f594cf56) | Aug 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [43db739186](https://linux-hardware.org/?probe=43db739186) | Aug 29, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4cdf174574](https://linux-hardware.org/?probe=4cdf174574) | Aug 29, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4c46f7ae80](https://linux-hardware.org/?probe=4c46f7ae80) | Aug 28, 2023 |
| Intel         | NUC11PABi7 K90104-302       | Mini pc     | [ee8ee6bf06](https://linux-hardware.org/?probe=ee8ee6bf06) | Aug 28, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ed544a4405](https://linux-hardware.org/?probe=ed544a4405) | Aug 28, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [5cd969711d](https://linux-hardware.org/?probe=5cd969711d) | Aug 28, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [714c46e2fd](https://linux-hardware.org/?probe=714c46e2fd) | Aug 28, 2023 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [c96c172d03](https://linux-hardware.org/?probe=c96c172d03) | Aug 27, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [00a28522c2](https://linux-hardware.org/?probe=00a28522c2) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [883d4fbfeb](https://linux-hardware.org/?probe=883d4fbfeb) | Aug 27, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d80e4744e9](https://linux-hardware.org/?probe=d80e4744e9) | Aug 27, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ea6d90ba09](https://linux-hardware.org/?probe=ea6d90ba09) | Aug 27, 2023 |
| HP            | Compaq 6710b (GE822PA#AB... | Notebook    | [134d0685ff](https://linux-hardware.org/?probe=134d0685ff) | Aug 26, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [6edcb45992](https://linux-hardware.org/?probe=6edcb45992) | Aug 26, 2023 |
| ASUSTek       | P5K-E                       | Desktop     | [aa48da4e34](https://linux-hardware.org/?probe=aa48da4e34) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | Desktop     | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [e78b6b1077](https://linux-hardware.org/?probe=e78b6b1077) | Aug 26, 2023 |
| Acer          | Predator G9-793             | Notebook    | [531f857477](https://linux-hardware.org/?probe=531f857477) | Aug 26, 2023 |
| HP            | ProBook 450 15.6 inch G1... | Notebook    | [973d7867a4](https://linux-hardware.org/?probe=973d7867a4) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [fc8e4dd4ff](https://linux-hardware.org/?probe=fc8e4dd4ff) | Aug 25, 2023 |
| Gigabyte      | Z68MX-UD2H-B3               | Desktop     | [93cce7551b](https://linux-hardware.org/?probe=93cce7551b) | Aug 25, 2023 |
| Dell          | 02C2CP A06                  | Server      | [dad6e7b74c](https://linux-hardware.org/?probe=dad6e7b74c) | Aug 25, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [93fec269da](https://linux-hardware.org/?probe=93fec269da) | Aug 25, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [58ae6791f0](https://linux-hardware.org/?probe=58ae6791f0) | Aug 25, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [96018ae096](https://linux-hardware.org/?probe=96018ae096) | Aug 24, 2023 |
| Dell          | 06D7TR A02                  | Desktop     | [d0b04a9056](https://linux-hardware.org/?probe=d0b04a9056) | Aug 24, 2023 |
| AZW           | SER                         | Mini pc     | [309bc27af7](https://linux-hardware.org/?probe=309bc27af7) | Aug 24, 2023 |
| Lenovo        | ThinkPad R61 7732NDG        | Notebook    | [b0d510a7ad](https://linux-hardware.org/?probe=b0d510a7ad) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [a06cf8de37](https://linux-hardware.org/?probe=a06cf8de37) | Aug 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [b6591e9fd9](https://linux-hardware.org/?probe=b6591e9fd9) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [5a6247f9b2](https://linux-hardware.org/?probe=5a6247f9b2) | Aug 24, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [a1bdeba9c8](https://linux-hardware.org/?probe=a1bdeba9c8) | Aug 23, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [c5484868fd](https://linux-hardware.org/?probe=c5484868fd) | Aug 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [68d3bc88e4](https://linux-hardware.org/?probe=68d3bc88e4) | Aug 23, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [e9b32aa827](https://linux-hardware.org/?probe=e9b32aa827) | Aug 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [38fbd02f14](https://linux-hardware.org/?probe=38fbd02f14) | Aug 23, 2023 |
| HP            | 212B                        | Desktop     | [a186c2ccf3](https://linux-hardware.org/?probe=a186c2ccf3) | Aug 23, 2023 |
| Fujitsu       | S6420                       | Notebook    | [044d4185b7](https://linux-hardware.org/?probe=044d4185b7) | Aug 22, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [b40144bd93](https://linux-hardware.org/?probe=b40144bd93) | Aug 22, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [17d3cd9a3c](https://linux-hardware.org/?probe=17d3cd9a3c) | Aug 22, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [0f5028d5fc](https://linux-hardware.org/?probe=0f5028d5fc) | Aug 22, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [527a0d3cba](https://linux-hardware.org/?probe=527a0d3cba) | Aug 20, 2023 |
| Kogan         | KAL14N360PA                 | Notebook    | [b7cecb1518](https://linux-hardware.org/?probe=b7cecb1518) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| HP            | 158A                        | Desktop     | [ba0211611f](https://linux-hardware.org/?probe=ba0211611f) | Aug 19, 2023 |
| HP            | 158A                        | Desktop     | [25e8725a35](https://linux-hardware.org/?probe=25e8725a35) | Aug 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [c642878288](https://linux-hardware.org/?probe=c642878288) | Aug 19, 2023 |
| Lenovo        | Yoga 7 14IAL7 82QE          | Convertible | [dc5d42e6cb](https://linux-hardware.org/?probe=dc5d42e6cb) | Aug 19, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [6a155984af](https://linux-hardware.org/?probe=6a155984af) | Aug 19, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [b42f885e14](https://linux-hardware.org/?probe=b42f885e14) | Aug 18, 2023 |
| Toshiba       | Satellite L550              | Notebook    | [4c331017e2](https://linux-hardware.org/?probe=4c331017e2) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [8a924c30e6](https://linux-hardware.org/?probe=8a924c30e6) | Aug 17, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [1d389611a3](https://linux-hardware.org/?probe=1d389611a3) | Aug 16, 2023 |
| HP            | Elite Dragonfly             | Convertible | [7419fe990e](https://linux-hardware.org/?probe=7419fe990e) | Aug 16, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [59b0f15b1d](https://linux-hardware.org/?probe=59b0f15b1d) | Aug 16, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [122b800eae](https://linux-hardware.org/?probe=122b800eae) | Aug 16, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [3372d46d8c](https://linux-hardware.org/?probe=3372d46d8c) | Aug 16, 2023 |
| Google        | Phaser360                   | Notebook    | [3c248cc2c8](https://linux-hardware.org/?probe=3c248cc2c8) | Aug 16, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [881b50cb6f](https://linux-hardware.org/?probe=881b50cb6f) | Aug 16, 2023 |
| Dell          | Precision 5520              | Notebook    | [0516c33229](https://linux-hardware.org/?probe=0516c33229) | Aug 16, 2023 |
| Dell          | Precision 5520              | Notebook    | [b9a35fa791](https://linux-hardware.org/?probe=b9a35fa791) | Aug 16, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [6242833326](https://linux-hardware.org/?probe=6242833326) | Aug 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [22252eb1d9](https://linux-hardware.org/?probe=22252eb1d9) | Aug 15, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [290298fd99](https://linux-hardware.org/?probe=290298fd99) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b62ff7f358](https://linux-hardware.org/?probe=b62ff7f358) | Aug 14, 2023 |
| HP            | Notebook                    | Notebook    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [fd93a82029](https://linux-hardware.org/?probe=fd93a82029) | Aug 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b950177908](https://linux-hardware.org/?probe=b950177908) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [dc696b572c](https://linux-hardware.org/?probe=dc696b572c) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [d2ccdc066b](https://linux-hardware.org/?probe=d2ccdc066b) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [c939a92f1d](https://linux-hardware.org/?probe=c939a92f1d) | Aug 14, 2023 |
| Apple         | Mac-F223BEC8                | Desktop     | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [56efab026f](https://linux-hardware.org/?probe=56efab026f) | Aug 14, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [9a8e4bc08d](https://linux-hardware.org/?probe=9a8e4bc08d) | Aug 14, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [5d7e68e3ae](https://linux-hardware.org/?probe=5d7e68e3ae) | Aug 14, 2023 |
| Dell          | Latitude E7470              | Notebook    | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6602bb3d0a](https://linux-hardware.org/?probe=6602bb3d0a) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5a809fe1c3](https://linux-hardware.org/?probe=5a809fe1c3) | Aug 13, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [1de4045fb5](https://linux-hardware.org/?probe=1de4045fb5) | Aug 13, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3ac1be3b93](https://linux-hardware.org/?probe=3ac1be3b93) | Aug 13, 2023 |
| HP            | ProBook 6450b               | Notebook    | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c28cbbd2a1](https://linux-hardware.org/?probe=c28cbbd2a1) | Aug 13, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [6d1e3a24e8](https://linux-hardware.org/?probe=6d1e3a24e8) | Aug 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [551d8f3fc8](https://linux-hardware.org/?probe=551d8f3fc8) | Aug 13, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8ed9952374](https://linux-hardware.org/?probe=8ed9952374) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [b6b99bf7bd](https://linux-hardware.org/?probe=b6b99bf7bd) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [f4d0fd6811](https://linux-hardware.org/?probe=f4d0fd6811) | Aug 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [a5681e12d3](https://linux-hardware.org/?probe=a5681e12d3) | Aug 12, 2023 |
| Panasonic     | CF-19ADNAXDA                | Notebook    | [d96cf2b13c](https://linux-hardware.org/?probe=d96cf2b13c) | Aug 12, 2023 |
| Dell          | G7 7790                     | Notebook    | [b5062f0928](https://linux-hardware.org/?probe=b5062f0928) | Aug 12, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [422a91a4eb](https://linux-hardware.org/?probe=422a91a4eb) | Aug 12, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [359d84713c](https://linux-hardware.org/?probe=359d84713c) | Aug 11, 2023 |
| Acer          | TMP255-M                    | Notebook    | [0b1adaea4e](https://linux-hardware.org/?probe=0b1adaea4e) | Aug 11, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [75d63c7495](https://linux-hardware.org/?probe=75d63c7495) | Aug 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [93a61b62a5](https://linux-hardware.org/?probe=93a61b62a5) | Aug 11, 2023 |
| Leader        | SC404PRO                    | Notebook    | [6f24ee5e0c](https://linux-hardware.org/?probe=6f24ee5e0c) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [025afcb20d](https://linux-hardware.org/?probe=025afcb20d) | Aug 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [2f64f3ee9a](https://linux-hardware.org/?probe=2f64f3ee9a) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [5264c46571](https://linux-hardware.org/?probe=5264c46571) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [84c3eefc94](https://linux-hardware.org/?probe=84c3eefc94) | Aug 08, 2023 |
| Dell          | Vostro 5581                 | Notebook    | [b4495daa07](https://linux-hardware.org/?probe=b4495daa07) | Aug 08, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [f4c69a94e9](https://linux-hardware.org/?probe=f4c69a94e9) | Aug 08, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e5efd1b16c](https://linux-hardware.org/?probe=e5efd1b16c) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [ab74b5c684](https://linux-hardware.org/?probe=ab74b5c684) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [e8524b0045](https://linux-hardware.org/?probe=e8524b0045) | Aug 08, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [85ffbedac4](https://linux-hardware.org/?probe=85ffbedac4) | Aug 08, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [ffd0be48c6](https://linux-hardware.org/?probe=ffd0be48c6) | Aug 08, 2023 |
| HP            | 212B                        | Desktop     | [b7de4a2b0a](https://linux-hardware.org/?probe=b7de4a2b0a) | Aug 07, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [51c3d4511a](https://linux-hardware.org/?probe=51c3d4511a) | Aug 07, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [fb1aaeae43](https://linux-hardware.org/?probe=fb1aaeae43) | Aug 07, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [d6a978f124](https://linux-hardware.org/?probe=d6a978f124) | Aug 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [f2d72fe710](https://linux-hardware.org/?probe=f2d72fe710) | Aug 07, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3b589d53bc](https://linux-hardware.org/?probe=3b589d53bc) | Aug 06, 2023 |
| Dell          | 08VT7V A01                  | Server      | [422a30cacf](https://linux-hardware.org/?probe=422a30cacf) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | Notebook    | [853567f156](https://linux-hardware.org/?probe=853567f156) | Aug 06, 2023 |
| MSI           | P65 Creator 8RE             | Notebook    | [f26344a920](https://linux-hardware.org/?probe=f26344a920) | Aug 05, 2023 |
| Dell          | Latitude E6220              | Notebook    | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b9d8025a54](https://linux-hardware.org/?probe=b9d8025a54) | Aug 05, 2023 |
| Acer          | AS E5-523G                  | Notebook    | [b37e833d1e](https://linux-hardware.org/?probe=b37e833d1e) | Aug 05, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | Desktop     | [f5ebaad3b1](https://linux-hardware.org/?probe=f5ebaad3b1) | Aug 05, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [dd1767aec1](https://linux-hardware.org/?probe=dd1767aec1) | Aug 04, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [15fb5d0baf](https://linux-hardware.org/?probe=15fb5d0baf) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [fe0a1dbc45](https://linux-hardware.org/?probe=fe0a1dbc45) | Aug 04, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [fedb43e298](https://linux-hardware.org/?probe=fedb43e298) | Aug 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [90aecb9ada](https://linux-hardware.org/?probe=90aecb9ada) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S84H0... | Notebook    | [d64e9809fa](https://linux-hardware.org/?probe=d64e9809fa) | Aug 04, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [ad51d2548b](https://linux-hardware.org/?probe=ad51d2548b) | Aug 03, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e5649696d0](https://linux-hardware.org/?probe=e5649696d0) | Aug 03, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [c96666b80d](https://linux-hardware.org/?probe=c96666b80d) | Aug 03, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1eb6fd9620](https://linux-hardware.org/?probe=1eb6fd9620) | Aug 02, 2023 |
| HP            | 2B2C                        | Desktop     | [3f0b3f8811](https://linux-hardware.org/?probe=3f0b3f8811) | Aug 01, 2023 |
| Dell          | 06NWYK A00                  | Desktop     | [1c3a3db0ec](https://linux-hardware.org/?probe=1c3a3db0ec) | Aug 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [43624df7d4](https://linux-hardware.org/?probe=43624df7d4) | Jul 30, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [60bf32a368](https://linux-hardware.org/?probe=60bf32a368) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [bc18b4b7ed](https://linux-hardware.org/?probe=bc18b4b7ed) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | Notebook    | [9b4b9b9d59](https://linux-hardware.org/?probe=9b4b9b9d59) | Jul 29, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [e4efeb0276](https://linux-hardware.org/?probe=e4efeb0276) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| ASUSTek       | WS C246 PRO                 | Desktop     | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b04075e09](https://linux-hardware.org/?probe=0b04075e09) | Jul 27, 2023 |
| Acer          | TMP255-M                    | Notebook    | [25d376a674](https://linux-hardware.org/?probe=25d376a674) | Jul 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| Google        | Sumo                        | Desktop     | [71a7167d22](https://linux-hardware.org/?probe=71a7167d22) | Jul 25, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [c4bfc82a98](https://linux-hardware.org/?probe=c4bfc82a98) | Jul 24, 2023 |
| Acer          | TMP255-M                    | Notebook    | [7a57ee89af](https://linux-hardware.org/?probe=7a57ee89af) | Jul 24, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [97f835b6ca](https://linux-hardware.org/?probe=97f835b6ca) | Jul 24, 2023 |
| Intel         | NUC11PABi7 M68262-501       | Mini pc     | [f3d1b0d511](https://linux-hardware.org/?probe=f3d1b0d511) | Jul 24, 2023 |
| ASUSTek       | PN61                        | Mini pc     | [78418a9a7f](https://linux-hardware.org/?probe=78418a9a7f) | Jul 24, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [579d5d5771](https://linux-hardware.org/?probe=579d5d5771) | Jul 24, 2023 |
| Dell          | Latitude 5410               | Notebook    | [29261ea2bb](https://linux-hardware.org/?probe=29261ea2bb) | Jul 24, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [a4b823b309](https://linux-hardware.org/?probe=a4b823b309) | Jul 23, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [a3350e1d80](https://linux-hardware.org/?probe=a3350e1d80) | Jul 23, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bcfc5b64f4](https://linux-hardware.org/?probe=bcfc5b64f4) | Jul 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [f525252834](https://linux-hardware.org/?probe=f525252834) | Jul 23, 2023 |
| MSI           | MEGA BOOK GX620             | Notebook    | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 441       | 10.34%  |
| Ubuntu 22.04       | 223       | 5.23%   |
| Ubuntu 18.04       | 174       | 4.08%   |
| Pop!_OS 22.04      | 132       | 3.1%    |
| Debian 11          | 113       | 2.65%   |
| Arch Rolling       | 92        | 2.16%   |
| Fedora 38          | 82        | 1.92%   |
| CentOS 7           | 80        | 1.88%   |
| Linux Mint 20.3    | 79        | 1.85%   |
| Zorin 16           | 75        | 1.76%   |
| OpenMandriva 4.3   | 75        | 1.76%   |
| KDE neon 20.04     | 71        | 1.67%   |
| Fedora 36          | 66        | 1.55%   |
| Pop!_OS 21.04      | 64        | 1.5%    |
| OpenMandriva 4.2   | 56        | 1.31%   |
| Fedora 37          | 55        | 1.29%   |
| ArcoLinux Rolling  | 55        | 1.29%   |
| Linux Mint 21.2    | 52        | 1.22%   |
| Pop!_OS 20.04      | 51        | 1.2%    |
| Manjaro            | 51        | 1.2%    |
| Linux Mint 21.1    | 51        | 1.2%    |
| Linux Mint 20.2    | 50        | 1.17%   |
| Pop!_OS 20.10      | 48        | 1.13%   |
| Fedora 39          | 47        | 1.1%    |
| Ubuntu 21.10       | 46        | 1.08%   |
| Arch               | 44        | 1.03%   |
| Linux Mint 20.1    | 43        | 1.01%   |
| Fedora 35          | 43        | 1.01%   |
| Debian 12          | 42        | 0.99%   |
| Ubuntu 19.04       | 41        | 0.96%   |
| Fedora 33          | 41        | 0.96%   |
| Ubuntu 20.10       | 39        | 0.91%   |
| Ubuntu 23.04       | 38        | 0.89%   |
| Fedora 34          | 38        | 0.89%   |
| Ubuntu 21.04       | 37        | 0.87%   |
| Ubuntu 19.10       | 37        | 0.87%   |
| Linux Mint 19.3    | 36        | 0.84%   |
| OpenMandriva 23.03 | 33        | 0.77%   |
| Linux Mint 20      | 33        | 0.77%   |
| OpenMandriva 23.08 | 31        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1084      | 27.46%  |
| Linux Mint    | 375       | 9.5%    |
| Fedora        | 330       | 8.36%   |
| Pop!_OS       | 312       | 7.9%    |
| OpenMandriva  | 249       | 6.31%   |
| Debian        | 204       | 5.17%   |
| Arch          | 134       | 3.39%   |
| Zorin         | 115       | 2.91%   |
| Manjaro       | 108       | 2.74%   |
| KDE neon      | 106       | 2.69%   |
| Xubuntu       | 88        | 2.23%   |
| Kubuntu       | 86        | 2.18%   |
| CentOS        | 84        | 2.13%   |
| ArcoLinux     | 57        | 1.44%   |
| Kali          | 42        | 1.06%   |
| Elementary    | 41        | 1.04%   |
| openSUSE      | 40        | 1.01%   |
| Gentoo        | 34        | 0.86%   |
| ROSA          | 29        | 0.73%   |
| Ubuntu MATE   | 28        | 0.71%   |
| Clear Linux   | 27        | 0.68%   |
| MX            | 25        | 0.63%   |
| Lubuntu       | 23        | 0.58%   |
| EndeavourOS   | 23        | 0.58%   |
| ClearOS       | 23        | 0.58%   |
| SteamOS       | 19        | 0.48%   |
| BlackPanther  | 19        | 0.48%   |
| LMDE          | 18        | 0.46%   |
| Endless       | 18        | 0.46%   |
| Ubuntu Unity  | 15        | 0.38%   |
| Ubuntu Budgie | 14        | 0.35%   |
| Parrot        | 13        | 0.33%   |
| Nobara        | 12        | 0.3%    |
| Raspbian      | 10        | 0.25%   |
| NixOS         | 8         | 0.2%    |
| Garuda Linux  | 8         | 0.2%    |
| Feren OS      | 8         | 0.2%    |
| Xero          | 7         | 0.18%   |
| Rocky Linux   | 7         | 0.18%   |
| LinuxFX       | 7         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003      | 72        | 1.45%   |
| 5.4.0-42-generic             | 64        | 1.29%   |
| 5.10.14-desktop-1omv4002     | 52        | 1.05%   |
| 3.10.0-1160.102.1.el7.x86_64 | 44        | 0.89%   |
| 5.15.0-56-generic            | 32        | 0.64%   |
| 6.2.6-desktop-1omv2390       | 31        | 0.62%   |
| 5.4.0-40-generic             | 30        | 0.6%    |
| 5.11.0-7620-generic          | 30        | 0.6%    |
| 6.1.1-desktop-1omv2290       | 29        | 0.58%   |
| 5.4.0-58-generic             | 29        | 0.58%   |
| 6.4.11-desktop-1omv2390      | 27        | 0.54%   |
| 5.4.0-48-generic             | 27        | 0.54%   |
| 5.15.0-58-generic            | 25        | 0.5%    |
| 5.15.0-52-generic            | 25        | 0.5%    |
| 5.4.0-26-generic             | 24        | 0.48%   |
| 5.3.0-46-generic             | 24        | 0.48%   |
| 6.2.6-76060206-generic       | 23        | 0.46%   |
| 5.4.0-52-generic             | 23        | 0.46%   |
| 5.11.0-37-generic            | 23        | 0.46%   |
| 6.2.0-39-generic             | 22        | 0.44%   |
| 5.4.0-29-generic             | 22        | 0.44%   |
| 5.3.0-40-generic             | 22        | 0.44%   |
| 5.3.0-28-generic             | 22        | 0.44%   |
| 5.17.5-76051705-generic      | 22        | 0.44%   |
| 5.15.0-48-generic            | 21        | 0.42%   |
| 6.2.0-20-generic             | 20        | 0.4%    |
| 5.11.0-27-generic            | 20        | 0.4%    |
| 5.4.0-7634-generic           | 19        | 0.38%   |
| 5.15.0-46-generic            | 19        | 0.38%   |
| 5.4.0-74-generic             | 18        | 0.36%   |
| 5.4.0-47-generic             | 18        | 0.36%   |
| 6.2.0-26-generic             | 17        | 0.34%   |
| 5.19.0-38-generic            | 17        | 0.34%   |
| 5.13.0-7620-generic          | 17        | 0.34%   |
| 6.5.0-14-generic             | 16        | 0.32%   |
| 6.0.12-76060006-generic      | 16        | 0.32%   |
| 5.8.0-7630-generic           | 16        | 0.32%   |
| 5.8.0-44-generic             | 16        | 0.32%   |
| 5.4.0-91-generic             | 16        | 0.32%   |
| 5.4.0-65-generic             | 16        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 577       | 12.53%  |
| 5.15.0  | 354       | 7.69%   |
| 5.11.0  | 228       | 4.95%   |
| 5.13.0  | 192       | 4.17%   |
| 5.8.0   | 181       | 3.93%   |
| 4.15.0  | 163       | 3.54%   |
| 6.2.0   | 137       | 2.97%   |
| 5.19.0  | 135       | 2.93%   |
| 5.3.0   | 128       | 2.78%   |
| 5.10.0  | 115       | 2.5%    |
| 3.10.0  | 101       | 2.19%   |
| 5.0.0   | 86        | 1.87%   |
| 5.16.7  | 73        | 1.58%   |
| 4.18.0  | 65        | 1.41%   |
| 6.2.6   | 56        | 1.22%   |
| 5.10.14 | 52        | 1.13%   |
| 6.1.0   | 51        | 1.11%   |
| 6.5.0   | 47        | 1.02%   |
| 6.1.1   | 36        | 0.78%   |
| 4.19.0  | 36        | 0.78%   |
| 6.4.11  | 34        | 0.74%   |
| 5.17.5  | 32        | 0.69%   |
| 6.0.12  | 23        | 0.5%    |
| 6.0.0   | 22        | 0.48%   |
| 6.5.6   | 20        | 0.43%   |
| 6.6.2   | 19        | 0.41%   |
| 6.5.5   | 19        | 0.41%   |
| 5.14.0  | 18        | 0.39%   |
| 6.5.11  | 17        | 0.37%   |
| 6.4.6   | 17        | 0.37%   |
| 5.18.0  | 17        | 0.37%   |
| 6.0.7   | 14        | 0.3%    |
| 5.16.11 | 14        | 0.3%    |
| 6.6.9   | 13        | 0.28%   |
| 5.18.10 | 13        | 0.28%   |
| 5.16.0  | 13        | 0.28%   |
| 4.4.0   | 13        | 0.28%   |
| 6.6.6   | 11        | 0.24%   |
| 6.4.10  | 11        | 0.24%   |
| 5.6.14  | 11        | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 629       | 14.11%  |
| 5.15    | 468       | 10.5%   |
| 5.11    | 267       | 5.99%   |
| 6.2     | 242       | 5.43%   |
| 5.13    | 238       | 5.34%   |
| 5.10    | 229       | 5.14%   |
| 5.8     | 228       | 5.12%   |
| 5.19    | 184       | 4.13%   |
| 6.1     | 168       | 3.77%   |
| 4.15    | 163       | 3.66%   |
| 5.16    | 155       | 3.48%   |
| 5.3     | 143       | 3.21%   |
| 6.5     | 135       | 3.03%   |
| 6.4     | 117       | 2.63%   |
| 6.0     | 111       | 2.49%   |
| 3.10    | 101       | 2.27%   |
| 5.0     | 95        | 2.13%   |
| 6.6     | 87        | 1.95%   |
| 5.17    | 84        | 1.88%   |
| 5.18    | 82        | 1.84%   |
| 4.18    | 78        | 1.75%   |
| 6.3     | 64        | 1.44%   |
| 5.14    | 55        | 1.23%   |
| 5.6     | 47        | 1.05%   |
| 5.12    | 46        | 1.03%   |
| 4.19    | 46        | 1.03%   |
| 5.9     | 38        | 0.85%   |
| 4.9     | 30        | 0.67%   |
| 5.5     | 26        | 0.58%   |
| 5.7     | 25        | 0.56%   |
| 5.2     | 17        | 0.38%   |
| 4.4     | 14        | 0.31%   |
| 6.7     | 11        | 0.25%   |
| 5.1     | 9         | 0.2%    |
| 4.1     | 4         | 0.09%   |
| 4.20    | 3         | 0.07%   |
| 4.14    | 3         | 0.07%   |
| 4.13    | 3         | 0.07%   |
| 4.8     | 2         | 0.04%   |
| 3.16    | 2         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3648      | 97.2%   |
| i686    | 52        | 1.39%   |
| aarch64 | 34        | 0.91%   |
| armv7l  | 13        | 0.35%   |
| riscv64 | 2         | 0.05%   |
| i586    | 2         | 0.05%   |
| armv6l  | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 1763      | 44.36%  |
| KDE5             | 660       | 16.61%  |
| Unknown          | 416       | 10.47%  |
| X-Cinnamon       | 317       | 7.98%   |
| XFCE             | 287       | 7.22%   |
| MATE             | 115       | 2.89%   |
| KDE              | 101       | 2.54%   |
| Cinnamon         | 70        | 1.76%   |
| Pantheon         | 39        | 0.98%   |
| LXQt             | 32        | 0.81%   |
| Budgie           | 25        | 0.63%   |
| i3               | 21        | 0.53%   |
| Unity            | 20        | 0.5%    |
| LXDE             | 20        | 0.5%    |
| KDE4             | 18        | 0.45%   |
| GNOME Classic    | 8         | 0.2%    |
| Deepin           | 8         | 0.2%    |
| awesome          | 8         | 0.2%    |
| Openbox          | 7         | 0.18%   |
| Hyprland         | 7         | 0.18%   |
| GNOME Flashback  | 4         | 0.1%    |
| xmonad           | 3         | 0.08%   |
| BunsenLabs       | 3         | 0.08%   |
| bspwm            | 3         | 0.08%   |
| qtile-default    | 2         | 0.05%   |
| qtile            | 2         | 0.05%   |
| dwm              | 2         | 0.05%   |
| Trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| pop              | 1         | 0.03%   |
| Phosh:GNOME      | 1         | 0.03%   |
| LXDE-pi-wayfire  | 1         | 0.03%   |
| lightdm-xsession | 1         | 0.03%   |
| LeftWM           | 1         | 0.03%   |
| icewm            | 1         | 0.03%   |
| herbstluftwm     | 1         | 0.03%   |
| GNUstep          | 1         | 0.03%   |
| fluxbox          | 1         | 0.03%   |
| dusk             | 1         | 0.03%   |
| DDE              | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2896      | 74.2%   |
| Wayland | 673       | 17.24%  |
| Unknown | 188       | 4.82%   |
| Tty     | 144       | 3.69%   |
| Web     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1958      | 49.85%  |
| SDDM    | 559       | 14.23%  |
| GDM     | 446       | 11.35%  |
| LightDM | 431       | 10.97%  |
| GDM3    | 411       | 10.46%  |
| TDM     | 85        | 2.16%   |
| KDM     | 17        | 0.43%   |
| SLiM    | 7         | 0.18%   |
| LXDM    | 5         | 0.13%   |
| XDM     | 4         | 0.1%    |
| LY-DM   | 2         | 0.05%   |
| Ly      | 2         | 0.05%   |
| GREETD  | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| en_AU        | 2684      | 69.03%  |
| en_US        | 608       | 15.64%  |
| Unknown      | 399       | 10.26%  |
| C            | 94        | 2.42%   |
| en_GB        | 72        | 1.85%   |
| C.UTF8       | 6         | 0.15%   |
| POSIX        | 4         | 0.1%    |
| zh_CN        | 3         | 0.08%   |
| de_DE        | 3         | 0.08%   |
| en_CA        | 2         | 0.05%   |
| ru_RU        | 1         | 0.03%   |
| it_IT        | 1         | 0.03%   |
| fr_FR        | 1         | 0.03%   |
| es_ES        | 1         | 0.03%   |
| en_ZA        | 1         | 0.03%   |
| en_US.utf-8  | 1         | 0.03%   |
| en_NZ        | 1         | 0.03%   |
| en_IN        | 1         | 0.03%   |
| en_GB.UTF-12 | 1         | 0.03%   |
| en_DK        | 1         | 0.03%   |
| en_BW        | 1         | 0.03%   |
| en_AU.UFT-8  | 1         | 0.03%   |
| en-AU        | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1940      | 50.35%  |
| EFI  | 1913      | 49.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2762      | 71.2%   |
| Btrfs    | 406       | 10.47%  |
| Overlay  | 264       | 6.81%   |
| Tmpfs    | 121       | 3.12%   |
| Xfs      | 107       | 2.76%   |
| Unknown  | 100       | 2.58%   |
| Zfs      | 60        | 1.55%   |
| Ext3     | 37        | 0.95%   |
| Ext2     | 10        | 0.26%   |
| XXXXXXX  | 4         | 0.1%    |
| F2fs     | 4         | 0.1%    |
| Reiserfs | 2         | 0.05%   |
| Jfs      | 1         | 0.03%   |
| Aufs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1986      | 51.24%  |
| GPT     | 1505      | 38.83%  |
| MBR     | 385       | 9.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3258      | 84.76%  |
| Yes       | 586       | 15.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2862      | 74.57%  |
| Yes       | 976       | 25.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 539       | 14.38%  |
| Hewlett-Packard                      | 482       | 12.86%  |
| Dell                                 | 476       | 12.7%   |
| Gigabyte Technology                  | 452       | 12.06%  |
| Lenovo                               | 398       | 10.62%  |
| MSI                                  | 274       | 7.31%   |
| Apple                                | 190       | 5.07%   |
| Acer                                 | 181       | 4.83%   |
| ASRock                               | 136       | 3.63%   |
| Toshiba                              | 110       | 2.94%   |
| Intel                                | 102       | 2.72%   |
| Microsoft                            | 44        | 1.17%   |
| Raspberry Pi Foundation              | 32        | 0.85%   |
| Unknown                              | 24        | 0.64%   |
| Alienware                            | 22        | 0.59%   |
| Samsung Electronics                  | 18        | 0.48%   |
| Sony                                 | 12        | 0.32%   |
| Valve                                | 11        | 0.29%   |
| Pegatron                             | 11        | 0.29%   |
| AMI                                  | 11        | 0.29%   |
| Notebook                             | 10        | 0.27%   |
| Google                               | 10        | 0.27%   |
| Panasonic                            | 9         | 0.24%   |
| Medion                               | 9         | 0.24%   |
| Timi                                 | 8         | 0.21%   |
| Metabox                              | 8         | 0.21%   |
| Supermicro                           | 7         | 0.19%   |
| IT Channel Pty                       | 7         | 0.19%   |
| IBM                                  | 7         | 0.19%   |
| HUAWEI                               | 7         | 0.19%   |
| Framework                            | 7         | 0.19%   |
| Shuttle                              | 6         | 0.16%   |
| Razer                                | 6         | 0.16%   |
| Kogan                                | 6         | 0.16%   |
| Fanless Mini PC                      | 6         | 0.16%   |
| ECS                                  | 6         | 0.16%   |
| System76                             | 5         | 0.13%   |
| Shenzhen Meigao Electronic Equipment | 5         | 0.13%   |
| Pine Microsystems                    | 5         | 0.13%   |
| Intel Client Systems                 | 5         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 36        | 0.96%   |
| Dell OptiPlex 9020                     | 32        | 0.85%   |
| Unknown                                | 30        | 0.8%    |
| HP Pavilion dv6                        | 18        | 0.48%   |
| Gigabyte H81M-S2H                      | 16        | 0.43%   |
| MSI MS-7C31                            | 15        | 0.4%    |
| HP Notebook                            | 14        | 0.37%   |
| HP Pavilion g6                         | 13        | 0.35%   |
| Apple MacBookAir7,2                    | 12        | 0.32%   |
| Valve Jupiter                          | 11        | 0.29%   |
| MSI MS-7B89                            | 11        | 0.29%   |
| Gigabyte 970A-D3P                      | 11        | 0.29%   |
| Dell OptiPlex 780                      | 11        | 0.29%   |
| RPi Raspberry Pi                       | 10        | 0.27%   |
| MSI MS-7A15                            | 10        | 0.27%   |
| Apple MacBookPro9,2                    | 10        | 0.27%   |
| Apple MacBookPro8,1                    | 10        | 0.27%   |
| Apple MacBookPro10,1                   | 10        | 0.27%   |
| Apple iMac12,2                         | 10        | 0.27%   |
| MSI MS-7C37                            | 9         | 0.24%   |
| MSI MS-7817                            | 9         | 0.24%   |
| HP Pavilion 15                         | 9         | 0.24%   |
| MSI MS-7C94                            | 8         | 0.21%   |
| Dell XPS 13 9360                       | 8         | 0.21%   |
| MSI MS-7C84                            | 7         | 0.19%   |
| MSI MS-7C02                            | 7         | 0.19%   |
| MSI MS-7A74                            | 7         | 0.19%   |
| Gigabyte X58A-UD3R                     | 7         | 0.19%   |
| Gigabyte B75M-D3H                      | 7         | 0.19%   |
| Dell XPS 15 9570                       | 7         | 0.19%   |
| Dell XPS 15 9560                       | 7         | 0.19%   |
| Dell OptiPlex 990                      | 7         | 0.19%   |
| Toshiba Satellite L850                 | 6         | 0.16%   |
| MSI MS-7B86                            | 6         | 0.16%   |
| MSI MS-7B53                            | 6         | 0.16%   |
| MSI MS-7A38                            | 6         | 0.16%   |
| Microsoft Surface Pro 3                | 6         | 0.16%   |
| Microsoft Surface Laptop 3             | 6         | 0.16%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 6         | 0.16%   |
| HP Compaq 8200 Elite SFF PC            | 6         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 187       | 4.99%   |
| Acer Aspire         | 120       | 3.2%    |
| Dell OptiPlex       | 115       | 3.07%   |
| Dell Latitude       | 98        | 2.62%   |
| HP Pavilion         | 94        | 2.51%   |
| Dell Inspiron       | 87        | 2.32%   |
| Toshiba Satellite   | 84        | 2.24%   |
| ASUS PRIME          | 79        | 2.11%   |
| ASUS ROG            | 75        | 2%      |
| Dell XPS            | 73        | 1.95%   |
| HP EliteBook        | 64        | 1.71%   |
| Lenovo IdeaPad      | 54        | 1.44%   |
| Dell Precision      | 50        | 1.33%   |
| HP Compaq           | 47        | 1.25%   |
| Microsoft Surface   | 44        | 1.17%   |
| ASUS TUF            | 43        | 1.15%   |
| Lenovo ThinkCentre  | 42        | 1.12%   |
| Lenovo Yoga         | 41        | 1.09%   |
| HP ProBook          | 38        | 1.01%   |
| ASUS All            | 36        | 0.96%   |
| RPi Raspberry       | 32        | 0.85%   |
| Unknown             | 30        | 0.8%    |
| HP Laptop           | 29        | 0.77%   |
| Gigabyte X570       | 25        | 0.67%   |
| HP ENVY             | 24        | 0.64%   |
| ASUS ZenBook        | 21        | 0.56%   |
| Gigabyte B450       | 19        | 0.51%   |
| Dell Vostro         | 19        | 0.51%   |
| ASUS VivoBook       | 18        | 0.48%   |
| Gigabyte H81M-S2H   | 16        | 0.43%   |
| Gigabyte B450M      | 16        | 0.43%   |
| Toshiba PORTEGE     | 15        | 0.4%    |
| MSI MS-7C31         | 15        | 0.4%    |
| Apple MacBookPro10  | 15        | 0.4%    |
| HP Notebook         | 14        | 0.37%   |
| Apple iMac12        | 14        | 0.37%   |
| HP Spectre          | 13        | 0.35%   |
| HP ProDesk          | 13        | 0.35%   |
| Lenovo ThinkStation | 12        | 0.32%   |
| HP EliteDesk        | 12        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 346       | 9.23%   |
| 2018    | 341       | 9.1%    |
| 2020    | 306       | 8.17%   |
| 2012    | 303       | 8.09%   |
| 2013    | 263       | 7.02%   |
| 2011    | 256       | 6.83%   |
| 2021    | 253       | 6.75%   |
| 2014    | 245       | 6.54%   |
| 2017    | 243       | 6.49%   |
| 2016    | 222       | 5.92%   |
| 2015    | 195       | 5.2%    |
| 2010    | 168       | 4.48%   |
| 2022    | 138       | 3.68%   |
| 2008    | 129       | 3.44%   |
| 2009    | 126       | 3.36%   |
| 2007    | 78        | 2.08%   |
| 2023    | 50        | 1.33%   |
| Unknown | 47        | 1.25%   |
| 2006    | 21        | 0.56%   |
| 2005    | 13        | 0.35%   |
| 2004    | 2         | 0.05%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1692      | 45.16%  |
| Notebook       | 1584      | 42.27%  |
| Convertible    | 132       | 3.52%   |
| Mini pc        | 104       | 2.78%   |
| All in one     | 91        | 2.43%   |
| Tablet         | 63        | 1.68%   |
| System on chip | 41        | 1.09%   |
| Server         | 34        | 0.91%   |
| Phone          | 3         | 0.08%   |
| Stick pc       | 3         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3497      | 92.61%  |
| Enabled  | 279       | 7.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3731      | 99.57%  |
| Yes  | 16        | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 914       | 23.82%  |
| 4.01-8.0        | 852       | 22.2%   |
| 8.01-16.0       | 621       | 16.18%  |
| 3.01-4.0        | 563       | 14.67%  |
| 32.01-64.0      | 495       | 12.9%   |
| 64.01-256.0     | 158       | 4.12%   |
| 1.01-2.0        | 105       | 2.74%   |
| 24.01-32.0      | 77        | 2.01%   |
| 2.01-3.0        | 22        | 0.57%   |
| 0.51-1.0        | 15        | 0.39%   |
| 0.01-0.5        | 8         | 0.21%   |
| More than 256.0 | 6         | 0.16%   |
| Unknown         | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1367      | 31.59%  |
| 2.01-3.0    | 1095      | 25.3%   |
| 4.01-8.0    | 676       | 15.62%  |
| 3.01-4.0    | 581       | 13.42%  |
| 0.51-1.0    | 270       | 6.24%   |
| 8.01-16.0   | 218       | 5.04%   |
| 0.01-0.5    | 55        | 1.27%   |
| 16.01-24.0  | 37        | 0.85%   |
| 24.01-32.0  | 15        | 0.35%   |
| 32.01-64.0  | 7         | 0.16%   |
| 64.01-256.0 | 3         | 0.07%   |
| 0           | 2         | 0.05%   |
| Unknown     | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2157      | 54.58%  |
| 2       | 940       | 23.79%  |
| 3       | 369       | 9.34%   |
| 4       | 221       | 5.59%   |
| 5       | 99        | 2.51%   |
| 6       | 55        | 1.39%   |
| 0       | 37        | 0.94%   |
| 7       | 28        | 0.71%   |
| 8       | 23        | 0.58%   |
| 9       | 9         | 0.23%   |
| 10      | 5         | 0.13%   |
| 13      | 3         | 0.08%   |
| 11      | 2         | 0.05%   |
| 36      | 1         | 0.03%   |
| 14      | 1         | 0.03%   |
| 12      | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2373      | 62.53%  |
| Yes       | 1422      | 37.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3242      | 86.29%  |
| No        | 515       | 13.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2770      | 73.05%  |
| No        | 1022      | 26.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2203      | 57.85%  |
| No        | 1605      | 42.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 3747      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 1035      | 25.8%   |
| Melbourne      | 884       | 22.04%  |
| Brisbane       | 563       | 14.04%  |
| Perth          | 329       | 8.2%    |
| Adelaide       | 242       | 6.03%   |
| Canberra       | 90        | 2.24%   |
| Wahroonga      | 39        | 0.97%   |
| Hobart         | 36        | 0.9%    |
| Launceston     | 29        | 0.72%   |
| Gold Coast     | 21        | 0.52%   |
| Alexandria     | 21        | 0.52%   |
| Surry Hills    | 17        | 0.42%   |
| Richmond       | 16        | 0.4%    |
| Geelong        | 16        | 0.4%    |
| Central Coast  | 16        | 0.4%    |
| Newcastle      | 13        | 0.32%   |
| Lane Cove      | 12        | 0.3%    |
| Woolloongabba  | 11        | 0.27%   |
| Mitcham        | 11        | 0.27%   |
| Southport      | 10        | 0.25%   |
| Nyngan         | 10        | 0.25%   |
| Leinster       | 9         | 0.22%   |
| Campbellfield  | 9         | 0.22%   |
| Brighton       | 9         | 0.22%   |
| Wollongong     | 8         | 0.2%    |
| Traralgon      | 8         | 0.2%    |
| Townsville     | 8         | 0.2%    |
| Parramatta     | 7         | 0.17%   |
| North Sydney   | 7         | 0.17%   |
| Mandurah       | 7         | 0.17%   |
| Macquarie Park | 7         | 0.17%   |
| Geraldton      | 7         | 0.17%   |
| Artarmon       | 7         | 0.17%   |
| West End       | 6         | 0.15%   |
| Warragul       | 6         | 0.15%   |
| Sunshine West  | 6         | 0.15%   |
| Point Cook     | 6         | 0.15%   |
| Mount Waverley | 6         | 0.15%   |
| Spring Field   | 5         | 0.12%   |
| Ringwood East  | 5         | 0.12%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1047      | 1955   | 18%     |
| WDC                         | 914       | 1714   | 15.71%  |
| Seagate                     | 904       | 1753   | 15.54%  |
| Crucial                     | 311       | 475    | 5.35%   |
| Toshiba                     | 283       | 407    | 4.87%   |
| Kingston                    | 260       | 341    | 4.47%   |
| SanDisk                     | 257       | 343    | 4.42%   |
| Unknown                     | 220       | 328    | 3.78%   |
| Intel                       | 203       | 379    | 3.49%   |
| Hitachi                     | 164       | 272    | 2.82%   |
| SK hynix                    | 126       | 153    | 2.17%   |
| Apple                       | 111       | 149    | 1.91%   |
| Micron Technology           | 86        | 109    | 1.48%   |
| HGST                        | 85        | 130    | 1.46%   |
| Micron/Crucial Technology   | 76        | 109    | 1.31%   |
| SPCC                        | 43        | 54     | 0.74%   |
| Phison                      | 39        | 61     | 0.67%   |
| OCZ                         | 38        | 55     | 0.65%   |
| Phison Electronics          | 37        | 49     | 0.64%   |
| KIOXIA                      | 35        | 42     | 0.6%    |
| A-DATA Technology           | 33        | 46     | 0.57%   |
| Kingston Technology Company | 26        | 31     | 0.45%   |
| JMicron Technology          | 26        | 32     | 0.45%   |
| LITEONIT                    | 22        | 32     | 0.38%   |
| Corsair                     | 22        | 37     | 0.38%   |
| ASMT                        | 22        | 30     | 0.38%   |
| Unknown                     | 21        | 23     | 0.36%   |
| LITEON                      | 20        | 35     | 0.34%   |
| KingSpec                    | 19        | 44     | 0.33%   |
| Fujitsu                     | 18        | 23     | 0.31%   |
| China                       | 17        | 22     | 0.29%   |
| Transcend                   | 16        | 23     | 0.28%   |
| Patriot                     | 15        | 22     | 0.26%   |
| Gigabyte Technology         | 14        | 17     | 0.24%   |
| Silicon Motion              | 13        | 25     | 0.22%   |
| LaCie                       | 13        | 20     | 0.22%   |
| Realtek Semiconductor       | 12        | 15     | 0.21%   |
| Maxtor                      | 12        | 16     | 0.21%   |
| Hewlett-Packard             | 10        | 14     | 0.17%   |
| USB                         | 9         | 11     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 67        | 1%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 65        | 0.97%   |
| Samsung SSD 850 EVO 250GB                           | 53        | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 48        | 0.72%   |
| Crucial CT500MX500SSD1 500GB                        | 46        | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB                      | 42        | 0.63%   |
| Crucial CT240BX500SSD1 240GB                        | 41        | 0.61%   |
| Unknown MMC Card  64GB                              | 40        | 0.6%    |
| Unknown MMC Card  32GB                              | 39        | 0.58%   |
| Samsung SSD 850 EVO 500GB                           | 39        | 0.58%   |
| Kingston SA400S37240G 240GB SSD                     | 38        | 0.57%   |
| Seagate Expansion 1TB                               | 37        | 0.55%   |
| Samsung SSD 860 EVO 1TB                             | 37        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB                     | 35        | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB                      | 35        | 0.52%   |
| Seagate ST2000DM008-2FR102 2TB                      | 35        | 0.52%   |
| Seagate Expansion Desk 8TB                          | 35        | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB                      | 33        | 0.49%   |
| Samsung NVMe SSD Drive 1TB                          | 32        | 0.48%   |
| Seagate ST2000DM001-1CH164 2TB                      | 30        | 0.45%   |
| Crucial CT480BX500SSD1 480GB                        | 29        | 0.43%   |
| Crucial CT1000MX500SSD1 1TB                         | 29        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.42%   |
| Samsung NVMe SSD Drive 500GB                        | 28        | 0.42%   |
| Seagate ST3500418AS 500GB                           | 27        | 0.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 27        | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 27        | 0.4%    |
| Kingston SA400S37480G 480GB SSD                     | 27        | 0.4%    |
| Crucial CT1000BX500SSD1 1TB                         | 26        | 0.39%   |
| Toshiba MQ01ABD100 1TB                              | 25        | 0.37%   |
| Samsung SSD 860 QVO 1TB                             | 25        | 0.37%   |
| Unknown SD/MMC/MS PRO 256GB                         | 24        | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 24        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD                    | 24        | 0.36%   |
| Seagate ST31000528AS 1TB                            | 23        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                      | 23        | 0.34%   |
| Seagate ST2000DL003-9VT166 2TB                      | 23        | 0.34%   |
| Seagate ST1000LM035-1RK172 1TB                      | 23        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 23        | 0.34%   |
| Unknown MMC Card  128GB                             | 22        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 887       | 1705   | 38.25%  |
| WDC                 | 750       | 1430   | 32.34%  |
| Toshiba             | 186       | 283    | 8.02%   |
| Hitachi             | 163       | 270    | 7.03%   |
| Samsung Electronics | 96        | 277    | 4.14%   |
| HGST                | 83        | 128    | 3.58%   |
| Apple               | 28        | 34     | 1.21%   |
| Unknown             | 26        | 38     | 1.12%   |
| JMicron Technology  | 17        | 21     | 0.73%   |
| Fujitsu             | 17        | 22     | 0.73%   |
| Maxtor              | 12        | 16     | 0.52%   |
| LaCie               | 10        | 16     | 0.43%   |
| ASMT                | 9         | 16     | 0.39%   |
| TO Exter            | 8         | 8      | 0.34%   |
| USB                 | 5         | 6      | 0.22%   |
| Hewlett-Packard     | 4         | 5      | 0.17%   |
| External            | 3         | 4      | 0.13%   |
| USB3.0              | 2         | 3      | 0.09%   |
| KESU                | 2         | 2      | 0.09%   |
| HGST HUS            | 2         | 2      | 0.09%   |
| SABRENT             | 1         | 1      | 0.04%   |
| QNAP                | 1         | 2      | 0.04%   |
| MaxDigital          | 1         | 1      | 0.04%   |
| IET                 | 1         | 1      | 0.04%   |
| IBM/Hitachi         | 1         | 1      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| Hajaan              | 1         | 1      | 0.04%   |
| DAS                 | 1         | 1      | 0.04%   |
| AAPL                | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 582       | 983    | 30.27%  |
| Crucial             | 267       | 419    | 13.88%  |
| Kingston            | 182       | 235    | 9.46%   |
| SanDisk             | 149       | 186    | 7.75%   |
| WDC                 | 145       | 195    | 7.54%   |
| Intel               | 101       | 221    | 5.25%   |
| Apple               | 60        | 69     | 3.12%   |
| SK hynix            | 41        | 48     | 2.13%   |
| OCZ                 | 38        | 55     | 1.98%   |
| SPCC                | 37        | 46     | 1.92%   |
| Micron Technology   | 32        | 38     | 1.66%   |
| Toshiba             | 31        | 43     | 1.61%   |
| LITEONIT            | 22        | 32     | 1.14%   |
| A-DATA Technology   | 20        | 26     | 1.04%   |
| LITEON              | 18        | 33     | 0.94%   |
| KingSpec            | 18        | 43     | 0.94%   |
| China               | 17        | 22     | 0.88%   |
| Transcend           | 16        | 23     | 0.83%   |
| Patriot             | 15        | 22     | 0.78%   |
| Corsair             | 14        | 28     | 0.73%   |
| Seagate             | 12        | 19     | 0.62%   |
| Gigabyte Technology | 8         | 8      | 0.42%   |
| Team                | 7         | 11     | 0.36%   |
| OWC                 | 7         | 18     | 0.36%   |
| ASMT                | 6         | 7      | 0.31%   |
| Plextor             | 5         | 17     | 0.26%   |
| Lexar               | 5         | 5      | 0.26%   |
| PNY                 | 4         | 6      | 0.21%   |
| KingFast            | 4         | 4      | 0.21%   |
| Vaseky              | 3         | 8      | 0.16%   |
| SABRENT             | 3         | 3      | 0.16%   |
| USB                 | 2         | 2      | 0.1%    |
| T-CREATE            | 2         | 2      | 0.1%    |
| NGFF                | 2         | 2      | 0.1%    |
| Hajaan              | 2         | 2      | 0.1%    |
| FORESEE             | 2         | 2      | 0.1%    |
| Apacer              | 2         | 3      | 0.1%    |
| 2.0TB               | 2         | 4      | 0.1%    |
| ZXFZ                | 1         | 1      | 0.05%   |
| XPG                 | 1         | 1      | 0.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1880      | 4296   | 36.77%  |
| SSD     | 1653      | 2942   | 32.33%  |
| NVMe    | 1294      | 2063   | 25.31%  |
| MMC     | 196       | 271    | 3.83%   |
| Unknown | 90        | 130    | 1.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2756      | 6838   | 60.25%  |
| NVMe | 1294      | 2053   | 28.29%  |
| SAS  | 328       | 540    | 7.17%   |
| MMC  | 196       | 271    | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1951      | 3756   | 50.68%  |
| 0.51-1.0   | 1077      | 1901   | 27.97%  |
| 1.01-2.0   | 434       | 821    | 11.27%  |
| 3.01-4.0   | 145       | 318    | 3.77%   |
| 4.01-10.0  | 139       | 272    | 3.61%   |
| 2.01-3.0   | 92        | 155    | 2.39%   |
| 10.01-20.0 | 11        | 14     | 0.29%   |
| 0          | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 895       | 21.92%  |
| 251-500        | 817       | 20.01%  |
| 501-1000       | 690       | 16.9%   |
| 1001-2000      | 374       | 9.16%   |
| More than 3000 | 346       | 8.47%   |
| 1-20           | 319       | 7.81%   |
| 51-100         | 259       | 6.34%   |
| 2001-3000      | 151       | 3.7%    |
| Unknown        | 120       | 2.94%   |
| 21-50          | 112       | 2.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1560      | 36.42%  |
| 21-50          | 711       | 16.6%   |
| 101-250        | 500       | 11.67%  |
| 51-100         | 459       | 10.72%  |
| 251-500        | 342       | 7.99%   |
| 501-1000       | 232       | 5.42%   |
| 1001-2000      | 159       | 3.71%   |
| More than 3000 | 132       | 3.08%   |
| Unknown        | 120       | 2.8%    |
| 2001-3000      | 65        | 1.52%   |
| 0              | 3         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 8         | 47     | 2.31%   |
| Seagate ST500DM002-1BD142 500GB         | 6         | 19     | 1.73%   |
| WDC WD40EFRX-68N32N0 4TB                | 5         | 5      | 1.45%   |
| Seagate ST3500418AS 500GB               | 5         | 15     | 1.45%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 1.45%   |
| Seagate ST2000DM001-1CH164 2TB          | 4         | 4      | 1.16%   |
| Samsung Electronics HD501LJ 500GB       | 4         | 38     | 1.16%   |
| Maxtor 6Y080L0 82GB                     | 4         | 7      | 1.16%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 4      | 1.16%   |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 0.87%   |
| WDC WD2002FAEX-007BA0 2TB               | 3         | 4      | 0.87%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 3      | 0.87%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 0.87%   |
| Seagate ST31000528AS 1TB                | 3         | 3      | 0.87%   |
| Seagate ST2000DM001-9YN164 2TB          | 3         | 3      | 0.87%   |
| Seagate ST2000DM001-1ER164 2TB          | 3         | 3      | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 0.87%   |
| Seagate ST1000DM003-1ER162 1TB          | 3         | 8      | 0.87%   |
| Maxtor 6L200M0 200GB                    | 3         | 4      | 0.87%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 3         | 3      | 0.87%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 0.87%   |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 0.87%   |
| Crucial CT525MX300SSD1 528GB            | 3         | 5      | 0.87%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.58%   |
| WDC WD5000AVCS-632DY1 500GB             | 2         | 6      | 0.58%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.58%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 3      | 0.58%   |
| WDC WD20EARS-00MVWB0 2TB                | 2         | 2      | 0.58%   |
| WDC WD20EARS-00J2GB0 2TB                | 2         | 3      | 0.58%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 6      | 0.58%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 2         | 2      | 0.58%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.58%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.58%   |
| WDC WD10EARS-00Y5B1 1TB                 | 2         | 2      | 0.58%   |
| WDC WD10EADS-11M2B1 1TB                 | 2         | 2      | 0.58%   |
| WDC WD10EADS-00P8B0 1TB                 | 2         | 2      | 0.58%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 3      | 0.58%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.58%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 0.58%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 82        | 131    | 25%     |
| WDC                      | 70        | 117    | 21.34%  |
| Samsung Electronics      | 33        | 92     | 10.06%  |
| Hitachi                  | 24        | 30     | 7.32%   |
| Intel                    | 23        | 81     | 7.01%   |
| Toshiba                  | 15        | 19     | 4.57%   |
| Kingston                 | 13        | 13     | 3.96%   |
| HGST                     | 9         | 10     | 2.74%   |
| Sandisk                  | 8         | 8      | 2.44%   |
| Crucial                  | 8         | 10     | 2.44%   |
| Maxtor                   | 7         | 11     | 2.13%   |
| SK hynix                 | 5         | 5      | 1.52%   |
| Micron Technology        | 5         | 5      | 1.52%   |
| Fujitsu                  | 5         | 5      | 1.52%   |
| Corsair                  | 4         | 5      | 1.22%   |
| Apple                    | 3         | 3      | 0.91%   |
| Transcend                | 1         | 1      | 0.3%    |
| SPCC                     | 1         | 1      | 0.3%    |
| Realtek Semiconductor    | 1         | 2      | 0.3%    |
| OCZ                      | 1         | 1      | 0.3%    |
| Netac                    | 1         | 1      | 0.3%    |
| MaxDigital               | 1         | 1      | 0.3%    |
| KingSpec                 | 1         | 3      | 0.3%    |
| KingFast                 | 1         | 1      | 0.3%    |
| HPE                      | 1         | 1      | 0.3%    |
| Hewlett-Packard          | 1         | 2      | 0.3%    |
| Gigabyte Technology      | 1         | 1      | 0.3%    |
| Biwin Storage Technology | 1         | 1      | 0.3%    |
| ASMT                     | 1         | 1      | 0.3%    |
| A-DATA Technology        | 1         | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 131    | 35.65%  |
| WDC                 | 68        | 113    | 29.57%  |
| Hitachi             | 24        | 30     | 10.43%  |
| Samsung Electronics | 16        | 74     | 6.96%   |
| Toshiba             | 13        | 17     | 5.65%   |
| HGST                | 9         | 10     | 3.91%   |
| Maxtor              | 7         | 11     | 3.04%   |
| Fujitsu             | 5         | 5      | 2.17%   |
| Apple               | 2         | 2      | 0.87%   |
| MaxDigital          | 1         | 1      | 0.43%   |
| HPE                 | 1         | 1      | 0.43%   |
| Hewlett-Packard     | 1         | 2      | 0.43%   |
| ASMT                | 1         | 1      | 0.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 204       | 398    | 67.55%  |
| SSD  | 82        | 145    | 27.15%  |
| NVMe | 16        | 20     | 5.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB                 | 1         | 1      | 25%     |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 25%     |
| Hitachi HDS721010DLE630 1TB                 | 1         | 10     | 25%     |
| Apple HDD HTS541010A9E662 1TB               | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 1         | 1      | 25%     |
| SK hynix | 1         | 1      | 25%     |
| Hitachi  | 1         | 10     | 25%     |
| Apple    | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2322      | 5459   | 56.77%  |
| Works    | 1473      | 3667   | 36.01%  |
| Malfunc  | 291       | 563    | 7.11%   |
| Failed   | 4         | 13     | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2486      | 50.09%  |
| AMD                                     | 706       | 14.23%  |
| Samsung Electronics                     | 511       | 10.3%   |
| SanDisk                                 | 161       | 3.24%   |
| Micron/Crucial Technology               | 122       | 2.46%   |
| Kingston Technology Company             | 106       | 2.14%   |
| Marvell Technology Group                | 102       | 2.06%   |
| ASMedia Technology                      | 101       | 2.04%   |
| Phison Electronics                      | 90        | 1.81%   |
| SK hynix                                | 86        | 1.73%   |
| JMicron Technology                      | 77        | 1.55%   |
| Toshiba America Info Systems            | 66        | 1.33%   |
| Micron Technology                       | 55        | 1.11%   |
| KIOXIA                                  | 35        | 0.71%   |
| Nvidia                                  | 29        | 0.58%   |
| ADATA Technology                        | 26        | 0.52%   |
| Silicon Motion                          | 23        | 0.46%   |
| Apple                                   | 23        | 0.46%   |
| LSI Logic / Symbios Logic               | 22        | 0.44%   |
| Realtek Semiconductor                   | 17        | 0.34%   |
| Broadcom / LSI                          | 15        | 0.3%    |
| VIA Technologies                        | 12        | 0.24%   |
| Seagate Technology                      | 12        | 0.24%   |
| MAXIO Technology (Hangzhou)             | 11        | 0.22%   |
| Integrated Technology Express           | 10        | 0.2%    |
| Solid State Storage Technology          | 7         | 0.14%   |
| Silicon Image                           | 6         | 0.12%   |
| Hewlett-Packard                         | 6         | 0.12%   |
| Shenzhen Longsys Electronics            | 5         | 0.1%    |
| Lite-On Technology                      | 5         | 0.1%    |
| Union Memory (Shenzhen)                 | 4         | 0.08%   |
| Adaptec                                 | 4         | 0.08%   |
| ULi Electronics                         | 3         | 0.06%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.06%   |
| Lenovo                                  | 3         | 0.06%   |
| 3ware                                   | 3         | 0.06%   |
| O2 Micro                                | 2         | 0.04%   |
| Biwin Storage Technology                | 2         | 0.04%   |
| Solidigm                                | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 473       | 8.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 247       | 4.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 212       | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 143       | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 135       | 2.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 120       | 2.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 115       | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 115       | 2.01%   |
| Intel SATA Controller [RAID mode]                                                       | 107       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 107       | 1.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 95        | 1.66%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 87        | 1.52%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 84        | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 82        | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 82        | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 79        | 1.38%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 75        | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 74        | 1.29%   |
| AMD 500 Series Chipset SATA Controller                                                  | 74        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 71        | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 68        | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 66        | 1.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 63        | 1.1%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 59        | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 57        | 1%      |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 54        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 53        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 50        | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 48        | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 39        | 0.68%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 38        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 38        | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 37        | 0.65%   |
| Intel SSD 660P Series                                                                   | 36        | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 36        | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 36        | 0.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 34        | 0.59%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton2]                                              | 33        | 0.58%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 33        | 0.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 33        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2676      | 55.01%  |
| NVMe | 1300      | 26.72%  |
| IDE  | 492       | 10.11%  |
| RAID | 358       | 7.36%   |
| SAS  | 29        | 0.6%    |
| SCSI | 10        | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2862      | 76.38%  |
| AMD           | 834       | 22.26%  |
| ARM           | 48        | 1.28%   |
| sifive,u74-mc | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |
| Unknown       | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 46        | 1.23%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 39        | 1.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 37        | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 35        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 34        | 0.91%   |
| ARM Processor                           | 34        | 0.91%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 33        | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 32        | 0.85%   |
| Intel Core i5-4460 CPU @ 3.20GHz        | 32        | 0.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 30        | 0.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 30        | 0.8%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 29        | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 29        | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 28        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 28        | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 26        | 0.69%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 26        | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 25        | 0.67%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 25        | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 25        | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 25        | 0.67%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 25        | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 25        | 0.67%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 24        | 0.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 23        | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 23        | 0.61%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 23        | 0.61%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 22        | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 21        | 0.56%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 21        | 0.56%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 21        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 20        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 20        | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 19        | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 19        | 0.51%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 18        | 0.48%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 18        | 0.48%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 18        | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 18        | 0.48%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 17        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 946       | 25.22%  |
| Intel Core i5           | 887       | 23.65%  |
| Other                   | 297       | 7.92%   |
| AMD Ryzen 5             | 217       | 5.79%   |
| AMD Ryzen 7             | 171       | 4.56%   |
| Intel Core i3           | 147       | 3.92%   |
| Intel Core 2 Duo        | 144       | 3.84%   |
| Intel Celeron           | 131       | 3.49%   |
| Intel Xeon              | 111       | 2.96%   |
| AMD Ryzen 9             | 94        | 2.51%   |
| Intel Pentium           | 55        | 1.47%   |
| AMD FX                  | 49        | 1.31%   |
| Intel Atom              | 33        | 0.88%   |
| AMD A6                  | 32        | 0.85%   |
| AMD A4                  | 30        | 0.8%    |
| AMD Ryzen 3             | 29        | 0.77%   |
| Intel Core i9           | 27        | 0.72%   |
| Intel Core 2 Quad       | 26        | 0.69%   |
| Intel Core 2            | 26        | 0.69%   |
| AMD A8                  | 23        | 0.61%   |
| Intel Pentium Dual-Core | 19        | 0.51%   |
| AMD Phenom II X4        | 17        | 0.45%   |
| AMD E2                  | 17        | 0.45%   |
| AMD A10                 | 16        | 0.43%   |
| ARM BCM                 | 12        | 0.32%   |
| AMD Ryzen Threadripper  | 12        | 0.32%   |
| AMD Ryzen 7 PRO         | 12        | 0.32%   |
| Intel Core m3           | 10        | 0.27%   |
| AMD Phenom II X6        | 10        | 0.27%   |
| Intel Pentium Dual      | 9         | 0.24%   |
| AMD Athlon              | 9         | 0.24%   |
| Intel Genuine           | 8         | 0.21%   |
| Intel Core M            | 8         | 0.21%   |
| AMD E1                  | 8         | 0.21%   |
| Intel Pentium D         | 7         | 0.19%   |
| AMD Phenom II X2        | 6         | 0.16%   |
| AMD Athlon II X2        | 6         | 0.16%   |
| Intel Pentium Silver    | 5         | 0.13%   |
| Intel Pentium 4         | 5         | 0.13%   |
| AMD Sempron             | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1486      | 39.56%  |
| 2       | 1194      | 31.79%  |
| 6       | 461       | 12.27%  |
| 8       | 290       | 7.72%   |
| 12      | 96        | 2.56%   |
| 1       | 62        | 1.65%   |
| 16      | 58        | 1.54%   |
| 10      | 35        | 0.93%   |
| 14      | 27        | 0.72%   |
| 3       | 19        | 0.51%   |
| 24      | 11        | 0.29%   |
| Unknown | 8         | 0.21%   |
| 32      | 4         | 0.11%   |
| 128     | 2         | 0.05%   |
| 40      | 2         | 0.05%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3685      | 98.32%  |
| 2       | 54        | 1.44%   |
| Unknown | 8         | 0.21%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2566      | 68.34%  |
| 1       | 1176      | 31.32%  |
| Unknown | 8         | 0.21%   |
| 4       | 3         | 0.08%   |
| 8       | 2         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3655      | 97.26%  |
| Unknown        | 72        | 1.92%   |
| 32-bit         | 24        | 0.64%   |
| 64-bit         | 7         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1335      | 33.85%  |
| 0x206a7    | 187       | 4.74%   |
| 0x306c3    | 177       | 4.49%   |
| 0x306a9    | 170       | 4.31%   |
| 0x906ea    | 105       | 2.66%   |
| 0x1067a    | 97        | 2.46%   |
| 0x906e9    | 92        | 2.33%   |
| 0x506e3    | 75        | 1.9%    |
| 0x806e9    | 66        | 1.67%   |
| 0x08701021 | 65        | 1.65%   |
| 0x406e3    | 61        | 1.55%   |
| 0x806ec    | 58        | 1.47%   |
| 0x806ea    | 58        | 1.47%   |
| 0x40651    | 58        | 1.47%   |
| 0x806c1    | 53        | 1.34%   |
| 0x306d4    | 49        | 1.24%   |
| 0x20655    | 47        | 1.19%   |
| 0x08701013 | 35        | 0.89%   |
| 0x106e5    | 34        | 0.86%   |
| 0x0800820d | 34        | 0.86%   |
| 0x10676    | 31        | 0.79%   |
| 0x0a50000c | 30        | 0.76%   |
| 0x30678    | 27        | 0.68%   |
| 0x20652    | 26        | 0.66%   |
| 0x906ed    | 25        | 0.63%   |
| 0x06006705 | 24        | 0.61%   |
| 0x06000852 | 24        | 0.61%   |
| 0x010000c8 | 23        | 0.58%   |
| 0xa0652    | 22        | 0.56%   |
| 0x706e5    | 22        | 0.56%   |
| 0x0a201016 | 22        | 0.56%   |
| 0x08108109 | 22        | 0.56%   |
| 0x106a5    | 21        | 0.53%   |
| 0x806eb    | 20        | 0.51%   |
| 0x6fb      | 20        | 0.51%   |
| 0x6fd      | 18        | 0.46%   |
| 0x07030105 | 18        | 0.46%   |
| 0x06001119 | 18        | 0.46%   |
| 0x6f6      | 17        | 0.43%   |
| 0x406c4    | 17        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 628       | 16.71%  |
| Haswell          | 391       | 10.4%   |
| IvyBridge        | 281       | 7.48%   |
| SandyBridge      | 273       | 7.26%   |
| Skylake          | 225       | 5.99%   |
| Zen 2            | 185       | 4.92%   |
| Unknown          | 178       | 4.74%   |
| Penryn           | 160       | 4.26%   |
| Zen 3            | 143       | 3.81%   |
| Westmere         | 119       | 3.17%   |
| Zen+             | 92        | 2.45%   |
| TigerLake        | 84        | 2.24%   |
| Broadwell        | 84        | 2.24%   |
| Core             | 83        | 2.21%   |
| CometLake        | 82        | 2.18%   |
| Alderlake Hybrid | 77        | 2.05%   |
| Zen              | 75        | 2%      |
| Nehalem          | 72        | 1.92%   |
| Silvermont       | 71        | 1.89%   |
| Icelake          | 64        | 1.7%    |
| Piledriver       | 60        | 1.6%    |
| K10              | 56        | 1.49%   |
| Excavator        | 47        | 1.25%   |
| Goldmont plus    | 42        | 1.12%   |
| Goldmont         | 25        | 0.67%   |
| Puma             | 24        | 0.64%   |
| Steamroller      | 18        | 0.48%   |
| Jaguar           | 16        | 0.43%   |
| Bonnell          | 16        | 0.43%   |
| P6               | 14        | 0.37%   |
| NetBurst         | 14        | 0.37%   |
| Bulldozer        | 14        | 0.37%   |
| K8 Hammer        | 13        | 0.35%   |
| K10 Llano        | 13        | 0.35%   |
| Bobcat           | 9         | 0.24%   |
| Tremont          | 7         | 0.19%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2054      | 46.93%  |
| Nvidia                           | 1304      | 29.79%  |
| AMD                              | 976       | 22.3%   |
| Matrox Electronics Systems       | 28        | 0.64%   |
| VIA Technologies                 | 5         | 0.11%   |
| ASPEED Technology                | 5         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Neomagic                         | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 184       | 4.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 131       | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 122       | 2.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 99        | 2.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 91        | 2.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 90        | 1.99%   |
| Intel UHD Graphics 620                                                                   | 88        | 1.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 78        | 1.73%   |
| Intel HD Graphics 630                                                                    | 74        | 1.64%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 74        | 1.64%   |
| Intel HD Graphics 620                                                                    | 71        | 1.57%   |
| Intel HD Graphics 530                                                                    | 69        | 1.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 60        | 1.33%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 57        | 1.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 54        | 1.2%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 51        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 49        | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 46        | 1.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 45        | 1%      |
| Intel HD Graphics 5500                                                                   | 43        | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 38        | 0.84%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 38        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 37        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 36        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 33        | 0.73%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 32        | 0.71%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 32        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 31        | 0.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 28        | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 28        | 0.62%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 27        | 0.6%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 25        | 0.55%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 24        | 0.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 24        | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 23        | 0.51%   |
| Intel HD Graphics 500                                                                    | 22        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1469      | 38.61%  |
| 1 x Nvidia               | 810       | 21.29%  |
| 1 x AMD                  | 759       | 19.95%  |
| Intel + Nvidia           | 424       | 11.14%  |
| Intel + AMD              | 92        | 2.42%   |
| 2 x AMD                  | 70        | 1.84%   |
| AMD + Nvidia             | 60        | 1.58%   |
| Other                    | 51        | 1.34%   |
| 1 x Matrox               | 23        | 0.6%    |
| 2 x Nvidia               | 11        | 0.29%   |
| 2 x Intel                | 11        | 0.29%   |
| 1 x VIA                  | 5         | 0.13%   |
| Nvidia + Matrox          | 5         | 0.13%   |
| 1 x SiS                  | 3         | 0.08%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.08%   |
| 1 x ASPEED               | 3         | 0.08%   |
| Nvidia + ASPEED          | 2         | 0.05%   |
| 1 x Neomagic             | 2         | 0.05%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + 2 x AMD          | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2928      | 76.07%  |
| Proprietary | 734       | 19.07%  |
| Unknown     | 187       | 4.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2179      | 55.96%  |
| 1.01-2.0   | 450       | 11.56%  |
| 0.01-0.5   | 315       | 8.09%   |
| 0.51-1.0   | 274       | 7.04%   |
| 3.01-4.0   | 256       | 6.57%   |
| 7.01-8.0   | 210       | 5.39%   |
| 5.01-6.0   | 89        | 2.29%   |
| 8.01-16.0  | 66        | 1.69%   |
| 2.01-3.0   | 32        | 0.82%   |
| 16.01-24.0 | 20        | 0.51%   |
| 4.01-5.0   | 2         | 0.05%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 507       | 12.17%  |
| AU Optronics            | 410       | 9.84%   |
| Dell                    | 319       | 7.66%   |
| LG Display              | 286       | 6.87%   |
| Chimei Innolux          | 226       | 5.42%   |
| Acer                    | 204       | 4.9%    |
| BOE                     | 198       | 4.75%   |
| Goldstar                | 179       | 4.3%    |
| Apple                   | 164       | 3.94%   |
| Hewlett-Packard         | 162       | 3.89%   |
| BenQ                    | 149       | 3.58%   |
| Philips                 | 136       | 3.26%   |
| AOC                     | 120       | 2.88%   |
| Ancor Communications    | 113       | 2.71%   |
| Sharp                   | 95        | 2.28%   |
| ViewSonic               | 88        | 2.11%   |
| Lenovo                  | 84        | 2.02%   |
| Unknown                 | 63        | 1.51%   |
| ASUSTek Computer        | 50        | 1.2%    |
| Chi Mei Optoelectronics | 49        | 1.18%   |
| Sony                    | 45        | 1.08%   |
| Panasonic               | 32        | 0.77%   |
| ___                     | 31        | 0.74%   |
| Kogan                   | 30        | 0.72%   |
| LG Electronics          | 27        | 0.65%   |
| PANDA                   | 26        | 0.62%   |
| GKK                     | 19        | 0.46%   |
| Gigabyte Technology     | 19        | 0.46%   |
| MSI                     | 17        | 0.41%   |
| Toshiba                 | 16        | 0.38%   |
| Hitachi                 | 15        | 0.36%   |
| Unknown (XXX)           | 14        | 0.34%   |
| Valve                   | 13        | 0.31%   |
| InfoVision              | 13        | 0.31%   |
| SAC                     | 12        | 0.29%   |
| MiTAC                   | 12        | 0.29%   |
| CVT                     | 10        | 0.24%   |
| CSO                     | 10        | 0.24%   |
| TCL                     | 9         | 0.22%   |
| MStar                   | 9         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch   | 21        | 0.48%   |
| ___ LCD TV ___0101 1920x1080                                          | 19        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 19        | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 18        | 0.41%   |
| ___ LCDTV16 ___9000 1360x768                                          | 14        | 0.32%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 14        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 14        | 0.32%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch             | 13        | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 12        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 12        | 0.27%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 11        | 0.25%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 11        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 11        | 0.25%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 10        | 0.23%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                   | 10        | 0.23%   |
| Unknown (XXX) Beyond TV XXX2851 2560x1440 1209x680mm 54.6-inch        | 10        | 0.23%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 10        | 0.23%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 10        | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 10        | 0.23%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 10        | 0.23%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 9         | 0.2%    |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                    | 9         | 0.2%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 9         | 0.2%    |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                      | 9         | 0.2%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 9         | 0.2%    |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 9         | 0.2%    |
| Unknown                                                               | 9         | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 8         | 0.18%   |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch  | 8         | 0.18%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                 | 8         | 0.18%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 8         | 0.18%   |
| CVT CVTE TV CVT0003 1360x768 575x323mm 26.0-inch                      | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 8         | 0.18%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 8         | 0.18%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 8         | 0.18%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                       | 8         | 0.18%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 8         | 0.18%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch             | 7         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1684      | 42.39%  |
| 1366x768 (WXGA)    | 551       | 13.87%  |
| 3840x2160 (4K)     | 355       | 8.94%   |
| 2560x1440 (QHD)    | 235       | 5.91%   |
| 1680x1050 (WSXGA+) | 134       | 3.37%   |
| 1920x1200 (WUXGA)  | 123       | 3.1%    |
| 1280x1024 (SXGA)   | 116       | 2.92%   |
| 1440x900 (WXGA+)   | 109       | 2.74%   |
| 1600x900 (HD+)     | 82        | 2.06%   |
| 1280x800 (WXGA)    | 74        | 1.86%   |
| 3440x1440          | 69        | 1.74%   |
| Unknown            | 61        | 1.54%   |
| 2560x1600          | 48        | 1.21%   |
| 3840x1080          | 32        | 0.81%   |
| 2880x1800          | 29        | 0.73%   |
| 2560x1080          | 28        | 0.7%    |
| 1360x768           | 26        | 0.65%   |
| 3840x2400          | 18        | 0.45%   |
| 2736x1824          | 14        | 0.35%   |
| 1920x540           | 13        | 0.33%   |
| 800x1280           | 11        | 0.28%   |
| 2160x1440          | 10        | 0.25%   |
| 3200x1800 (QHD+)   | 9         | 0.23%   |
| 1280x768           | 9         | 0.23%   |
| 2256x1504          | 8         | 0.2%    |
| 1920x1280          | 8         | 0.2%    |
| 1280x720 (HD)      | 8         | 0.2%    |
| 3840x1600          | 7         | 0.18%   |
| 3200x2000          | 6         | 0.15%   |
| 1024x768 (XGA)     | 6         | 0.15%   |
| 1024x600           | 6         | 0.15%   |
| 3072x1920          | 5         | 0.13%   |
| 2288x1287          | 5         | 0.13%   |
| 5760x2160          | 4         | 0.1%    |
| 5120x1440          | 4         | 0.1%    |
| 4480x1440          | 4         | 0.1%    |
| 3600x1080          | 4         | 0.1%    |
| 3200x1080          | 4         | 0.1%    |
| 2240x1400          | 4         | 0.1%    |
| 1600x1200          | 4         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 751       | 18.05%  |
| 27      | 435       | 10.46%  |
| 13      | 363       | 8.73%   |
| 24      | 350       | 8.41%   |
| 23      | 305       | 7.33%   |
| Unknown | 247       | 5.94%   |
| 14      | 242       | 5.82%   |
| 21      | 226       | 5.43%   |
| 17      | 148       | 3.56%   |
| 19      | 142       | 3.41%   |
| 31      | 141       | 3.39%   |
| 22      | 99        | 2.38%   |
| 34      | 83        | 2%      |
| 12      | 74        | 1.78%   |
| 72      | 59        | 1.42%   |
| 11      | 56        | 1.35%   |
| 20      | 52        | 1.25%   |
| 18      | 42        | 1.01%   |
| 16      | 31        | 0.75%   |
| 84      | 30        | 0.72%   |
| 32      | 26        | 0.63%   |
| 54      | 25        | 0.6%    |
| 40      | 20        | 0.48%   |
| 26      | 20        | 0.48%   |
| 52      | 18        | 0.43%   |
| 48      | 17        | 0.41%   |
| 42      | 15        | 0.36%   |
| 37      | 13        | 0.31%   |
| 25      | 13        | 0.31%   |
| 10      | 11        | 0.26%   |
| 7       | 11        | 0.26%   |
| 29      | 10        | 0.24%   |
| 35      | 9         | 0.22%   |
| 55      | 8         | 0.19%   |
| 63      | 7         | 0.17%   |
| 46      | 7         | 0.17%   |
| 49      | 6         | 0.14%   |
| 36      | 6         | 0.14%   |
| 28      | 5         | 0.12%   |
| 142     | 4         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1144      | 28.2%   |
| 501-600        | 982       | 24.21%  |
| 401-500        | 457       | 11.26%  |
| 201-300        | 384       | 9.47%   |
| Unknown        | 247       | 6.09%   |
| 351-400        | 236       | 5.82%   |
| 601-700        | 216       | 5.32%   |
| 701-800        | 114       | 2.81%   |
| 1001-1500      | 101       | 2.49%   |
| 1501-2000      | 95        | 2.34%   |
| 801-900        | 46        | 1.13%   |
| 901-1000       | 18        | 0.44%   |
| 1-100          | 11        | 0.27%   |
| More than 2000 | 4         | 0.1%    |
| 101-200        | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2642      | 71.27%  |
| 16/10   | 525       | 14.16%  |
| Unknown | 206       | 5.56%   |
| 5/4     | 105       | 2.83%   |
| 21/9    | 101       | 2.72%   |
| 3/2     | 52        | 1.4%    |
| 4/3     | 24        | 0.65%   |
| 32/9    | 19        | 0.51%   |
| 6/5     | 12        | 0.32%   |
| 0.67    | 11        | 0.3%    |
| 1.00    | 4         | 0.11%   |
| 0.56    | 3         | 0.08%   |
| 3.40    | 2         | 0.05%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 788       | 19.25%  |
| 101-110        | 744       | 18.17%  |
| 301-350        | 450       | 10.99%  |
| 81-90          | 420       | 10.26%  |
| 351-500        | 265       | 6.47%   |
| 151-200        | 247       | 6.03%   |
| Unknown        | 247       | 6.03%   |
| 71-80          | 187       | 4.57%   |
| More than 1000 | 171       | 4.18%   |
| 251-300        | 125       | 3.05%   |
| 121-130        | 104       | 2.54%   |
| 501-1000       | 85        | 2.08%   |
| 61-70          | 60        | 1.47%   |
| 51-60          | 60        | 1.47%   |
| 141-150        | 52        | 1.27%   |
| 111-120        | 35        | 0.85%   |
| 131-140        | 17        | 0.42%   |
| 91-100         | 14        | 0.34%   |
| 1-40           | 13        | 0.32%   |
| 41-50          | 10        | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1416      | 35.89%  |
| 101-120       | 923       | 23.4%   |
| 121-160       | 792       | 20.08%  |
| 161-240       | 293       | 7.43%   |
| Unknown       | 247       | 6.26%   |
| 1-50          | 139       | 3.52%   |
| More than 240 | 135       | 3.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2899      | 74.11%  |
| 2     | 655       | 16.74%  |
| 0     | 263       | 6.72%   |
| 3     | 83        | 2.12%   |
| 4     | 11        | 0.28%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1944      | 33.84%  |
| Realtek Semiconductor           | 1910      | 33.25%  |
| Qualcomm Atheros                | 560       | 9.75%   |
| Broadcom                        | 394       | 6.86%   |
| Broadcom Limited                | 84        | 1.46%   |
| Marvell Technology Group        | 74        | 1.29%   |
| MediaTek                        | 66        | 1.15%   |
| Ralink                          | 61        | 1.06%   |
| TP-Link                         | 54        | 0.94%   |
| Ralink Technology               | 54        | 0.94%   |
| Samsung Electronics             | 39        | 0.68%   |
| Sierra Wireless                 | 31        | 0.54%   |
| DisplayLink                     | 31        | 0.54%   |
| NetGear                         | 30        | 0.52%   |
| Aquantia                        | 24        | 0.42%   |
| ASIX Electronics                | 23        | 0.4%    |
| Huawei Technologies             | 22        | 0.38%   |
| Nvidia                          | 20        | 0.35%   |
| D-Link                          | 20        | 0.35%   |
| Microsoft                       | 19        | 0.33%   |
| Dell                            | 18        | 0.31%   |
| Edimax Technology               | 17        | 0.3%    |
| D-Link System                   | 17        | 0.3%    |
| Apple                           | 15        | 0.26%   |
| ZTE WCDMA Technologies MSM      | 14        | 0.24%   |
| Lenovo                          | 14        | 0.24%   |
| Hewlett-Packard                 | 13        | 0.23%   |
| ASUSTek Computer                | 13        | 0.23%   |
| Qualcomm Atheros Communications | 11        | 0.19%   |
| Qualcomm                        | 10        | 0.17%   |
| Motorola PCS                    | 10        | 0.17%   |
| Google                          | 10        | 0.17%   |
| OPPO Electronics                | 9         | 0.16%   |
| VIA Technologies                | 8         | 0.14%   |
| Mellanox Technologies           | 6         | 0.1%    |
| ICS Advent                      | 6         | 0.1%    |
| Standard Microsystems           | 5         | 0.09%   |
| JMicron Technology              | 5         | 0.09%   |
| Arduino SA                      | 5         | 0.09%   |
| Xiaomi                          | 4         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1268      | 18.78%  |
| Intel Wi-Fi 6 AX200                                                    | 180       | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 147       | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 146       | 2.16%   |
| Intel I211 Gigabit Network Connection                                  | 141       | 2.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 136       | 2.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 123       | 1.82%   |
| Intel Wireless 8265 / 8275                                             | 107       | 1.58%   |
| Intel Wireless 8260                                                    | 86        | 1.27%   |
| Intel Ethernet Connection I217-LM                                      | 75        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 72        | 1.07%   |
| Intel Ethernet Connection (2) I219-V                                   | 72        | 1.07%   |
| Intel Wireless 7260                                                    | 71        | 1.05%   |
| Intel Wi-Fi 6 AX201                                                    | 66        | 0.98%   |
| Intel Ethernet Controller I225-V                                       | 66        | 0.98%   |
| Intel Wireless 7265                                                    | 65        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 64        | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 61        | 0.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 57        | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 56        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 54        | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 51        | 0.76%   |
| Intel Wireless 3165                                                    | 51        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 51        | 0.76%   |
| Intel Ethernet Connection (7) I219-V                                   | 50        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 49        | 0.73%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 47        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 46        | 0.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 44        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                  | 44        | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 44        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 43        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 42        | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 42        | 0.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 42        | 0.62%   |
| Intel Ethernet Connection I219-LM                                      | 40        | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 39        | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 38        | 0.56%   |
| Realtek 802.11ac NIC                                                   | 36        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 36        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1364      | 46.07%  |
| Qualcomm Atheros                | 420       | 14.18%  |
| Realtek Semiconductor           | 419       | 14.15%  |
| Broadcom                        | 262       | 8.85%   |
| Broadcom Limited                | 62        | 2.09%   |
| Ralink                          | 61        | 2.06%   |
| MediaTek                        | 61        | 2.06%   |
| Ralink Technology               | 54        | 1.82%   |
| TP-Link                         | 52        | 1.76%   |
| Sierra Wireless                 | 31        | 1.05%   |
| NetGear                         | 28        | 0.95%   |
| Marvell Technology Group        | 28        | 0.95%   |
| Edimax Technology               | 17        | 0.57%   |
| Microsoft                       | 13        | 0.44%   |
| ASUSTek Computer                | 13        | 0.44%   |
| D-Link System                   | 12        | 0.41%   |
| D-Link                          | 12        | 0.41%   |
| Qualcomm Atheros Communications | 11        | 0.37%   |
| Dell                            | 11        | 0.37%   |
| Qualcomm                        | 7         | 0.24%   |
| Hewlett-Packard                 | 4         | 0.14%   |
| BUFFALO                         | 4         | 0.14%   |
| Belkin Components               | 4         | 0.14%   |
| Wacom                           | 2         | 0.07%   |
| Linksys                         | 2         | 0.07%   |
| AVM                             | 2         | 0.07%   |
| Xiaomi                          | 1         | 0.03%   |
| Wilocity                        | 1         | 0.03%   |
| Toshiba                         | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 180       | 6.05%   |
| Intel Wireless 8265 / 8275                                           | 107       | 3.59%   |
| Intel Wireless 8260                                                  | 86        | 2.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 72        | 2.42%   |
| Intel Wireless 7260                                                  | 71        | 2.38%   |
| Intel Wi-Fi 6 AX201                                                  | 66        | 2.22%   |
| Intel Wireless 7265                                                  | 65        | 2.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 64        | 2.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 61        | 2.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 57        | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 56        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 54        | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 51        | 1.71%   |
| Intel Wireless 3165                                                  | 51        | 1.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 51        | 1.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 49        | 1.65%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 47        | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 46        | 1.55%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 44        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 44        | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 43        | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 42        | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 42        | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 39        | 1.31%   |
| Realtek 802.11ac NIC                                                 | 36        | 1.21%   |
| Intel Centrino Ultimate-N 6300                                       | 35        | 1.18%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 30        | 1.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 30        | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 29        | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 29        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 28        | 0.94%   |
| Intel Wireless 3160                                                  | 28        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 27        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 27        | 0.91%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                    | 27        | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 23        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 22        | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 21        | 0.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 21        | 0.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 20        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1694      | 47.4%   |
| Intel                            | 1107      | 30.97%  |
| Broadcom                         | 203       | 5.68%   |
| Qualcomm Atheros                 | 197       | 5.51%   |
| Marvell Technology Group         | 46        | 1.29%   |
| Samsung Electronics              | 39        | 1.09%   |
| DisplayLink                      | 31        | 0.87%   |
| Aquantia                         | 24        | 0.67%   |
| ASIX Electronics                 | 23        | 0.64%   |
| Broadcom Limited                 | 22        | 0.62%   |
| Nvidia                           | 20        | 0.56%   |
| Huawei Technologies              | 17        | 0.48%   |
| Apple                            | 15        | 0.42%   |
| ZTE WCDMA Technologies MSM       | 14        | 0.39%   |
| Lenovo                           | 14        | 0.39%   |
| Google                           | 10        | 0.28%   |
| OPPO Electronics                 | 9         | 0.25%   |
| VIA Technologies                 | 8         | 0.22%   |
| D-Link                           | 8         | 0.22%   |
| Motorola PCS                     | 6         | 0.17%   |
| ICS Advent                       | 6         | 0.17%   |
| Standard Microsystems            | 5         | 0.14%   |
| Microsoft                        | 5         | 0.14%   |
| JMicron Technology               | 5         | 0.14%   |
| D-Link System                    | 5         | 0.14%   |
| Microchip Technology             | 4         | 0.11%   |
| MediaTek                         | 4         | 0.11%   |
| Xiaomi                           | 3         | 0.08%   |
| QLogic                           | 3         | 0.08%   |
| NetGear                          | 3         | 0.08%   |
| IBM                              | 3         | 0.08%   |
| Hewlett-Packard                  | 3         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Qualcomm                         | 2         | 0.06%   |
| Mellanox Technologies            | 2         | 0.06%   |
| HMD Global                       | 2         | 0.06%   |
| Dell                             | 2         | 0.06%   |
| vivo                             | 1         | 0.03%   |
| TP-Link                          | 1         | 0.03%   |
| T & A Mobile Phones              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1268      | 34.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 147       | 3.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 146       | 3.95%   |
| Intel I211 Gigabit Network Connection                                          | 141       | 3.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 136       | 3.68%   |
| Realtek RTL8125 2.5GbE Controller                                              | 123       | 3.33%   |
| Intel Ethernet Connection I217-LM                                              | 75        | 2.03%   |
| Intel Ethernet Connection (2) I219-V                                           | 72        | 1.95%   |
| Intel Ethernet Controller I225-V                                               | 66        | 1.79%   |
| Intel Ethernet Connection (7) I219-V                                           | 50        | 1.35%   |
| Intel Ethernet Connection (2) I219-LM                                          | 44        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 42        | 1.14%   |
| Intel Ethernet Connection I219-LM                                              | 40        | 1.08%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 38        | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 36        | 0.97%   |
| Intel 82579V Gigabit Network Connection                                        | 31        | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 29        | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 28        | 0.76%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 28        | 0.76%   |
| Intel Ethernet Connection I217-V                                               | 26        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                                          | 26        | 0.7%    |
| Intel 82574L Gigabit Network Connection                                        | 26        | 0.7%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 25        | 0.68%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 24        | 0.65%   |
| Intel I210 Gigabit Network Connection                                          | 23        | 0.62%   |
| Intel Ethernet Connection (2) I218-V                                           | 22        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                       | 21        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 19        | 0.51%   |
| Intel Ethernet Connection I218-LM                                              | 18        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                           | 18        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                                           | 18        | 0.49%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 18        | 0.49%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 18        | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 17        | 0.46%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 15        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 14        | 0.38%   |
| Intel Ethernet Connection (10) I219-V                                          | 14        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 13        | 0.35%   |
| Intel Ethernet Connection I219-V                                               | 13        | 0.35%   |
| Intel Ethernet Connection (3) I218-LM                                          | 13        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3230      | 53.21%  |
| WiFi     | 2763      | 45.52%  |
| Modem    | 59        | 0.97%   |
| Unknown  | 18        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2082      | 53.19%  |
| Ethernet | 1831      | 46.78%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1980      | 52.3%   |
| 1     | 1526      | 40.31%  |
| 3     | 147       | 3.88%   |
| 0     | 84        | 2.22%   |
| 4     | 30        | 0.79%   |
| 5     | 12        | 0.32%   |
| 6     | 4         | 0.11%   |
| 8     | 2         | 0.05%   |
| 9     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3279      | 85.86%  |
| Yes  | 540       | 14.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1123      | 50.09%  |
| Apple                           | 170       | 7.58%   |
| Realtek Semiconductor           | 147       | 6.56%   |
| Broadcom                        | 137       | 6.11%   |
| Qualcomm Atheros Communications | 136       | 6.07%   |
| Cambridge Silicon Radio         | 130       | 5.8%    |
| IMC Networks                    | 74        | 3.3%    |
| Foxconn / Hon Hai               | 54        | 2.41%   |
| Lite-On Technology              | 53        | 2.36%   |
| Toshiba                         | 39        | 1.74%   |
| ASUSTek Computer                | 30        | 1.34%   |
| Marvell Semiconductor           | 26        | 1.16%   |
| Hewlett-Packard                 | 22        | 0.98%   |
| MediaTek                        | 19        | 0.85%   |
| Dell                            | 18        | 0.8%    |
| Ralink                          | 17        | 0.76%   |
| TP-Link                         | 9         | 0.4%    |
| Alps Electric                   | 8         | 0.36%   |
| Realtek                         | 6         | 0.27%   |
| Edimax Technology               | 5         | 0.22%   |
| USI                             | 4         | 0.18%   |
| Ralink Technology               | 4         | 0.18%   |
| Micro Star International        | 2         | 0.09%   |
| Logitech                        | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Belkin Components               | 2         | 0.09%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 384       | 17.1%   |
| Intel AX201 Bluetooth                               | 197       | 8.78%   |
| Intel AX200 Bluetooth                               | 172       | 7.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 130       | 5.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 127       | 5.66%   |
| Realtek Bluetooth Radio                             | 94        | 4.19%   |
| Apple Bluetooth Host Controller                     | 75        | 3.34%   |
| Intel Bluetooth Device                              | 74        | 3.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 59        | 2.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 54        | 2.41%   |
| Intel Wireless-AC 3168 Bluetooth                    | 51        | 2.27%   |
| Intel AX210 Bluetooth                               | 50        | 2.23%   |
| Apple Bluetooth USB Host Controller                 | 48        | 2.14%   |
| Realtek  Bluetooth 4.2 Adapter                      | 45        | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 1.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 34        | 1.51%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 32        | 1.43%   |
| IMC Networks Bluetooth Radio                        | 31        | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 28        | 1.25%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 24        | 1.07%   |
| Marvell Bluetooth and Wireless LAN Composite        | 20        | 0.89%   |
| MediaTek Wireless_Device                            | 19        | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 19        | 0.85%   |
| IMC Networks Wireless_Device                        | 18        | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                  | 18        | 0.8%    |
| Ralink RT3290 Bluetooth                             | 17        | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.71%   |
| Apple Bluetooth HCI                                 | 15        | 0.67%   |
| Toshiba Bluetooth Device                            | 13        | 0.58%   |
| Lite-On Bluetooth Device                            | 13        | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 0.53%   |
| Broadcom HP Portable Bumble Bee                     | 11        | 0.49%   |
| TP-Link UB500 Adapter                               | 9         | 0.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.4%    |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.36%   |
| IMC Networks Bluetooth Device                       | 8         | 0.36%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2743      | 49.73%  |
| AMD                                  | 1096      | 19.87%  |
| Nvidia                               | 1005      | 18.22%  |
| C-Media Electronics                  | 74        | 1.34%   |
| Logitech                             | 65        | 1.18%   |
| Realtek Semiconductor                | 32        | 0.58%   |
| Creative Labs                        | 32        | 0.58%   |
| GN Netcom                            | 25        | 0.45%   |
| Razer USA                            | 21        | 0.38%   |
| Kingston Technology                  | 21        | 0.38%   |
| Texas Instruments                    | 20        | 0.36%   |
| Generalplus Technology               | 20        | 0.36%   |
| Plantronics                          | 18        | 0.33%   |
| Apple                                | 18        | 0.33%   |
| Creative Technology                  | 17        | 0.31%   |
| Corsair                              | 15        | 0.27%   |
| RODE Microphones                     | 14        | 0.25%   |
| SteelSeries ApS                      | 12        | 0.22%   |
| Micro Star International             | 11        | 0.2%    |
| Lenovo                               | 11        | 0.2%    |
| JMTek                                | 11        | 0.2%    |
| ASUSTek Computer                     | 9         | 0.16%   |
| VIA Technologies                     | 8         | 0.15%   |
| Hewlett-Packard                      | 8         | 0.15%   |
| DSEA A/S                             | 8         | 0.15%   |
| Blue Microphones                     | 8         | 0.15%   |
| Astro Gaming                         | 8         | 0.15%   |
| M-Audio                              | 7         | 0.13%   |
| Focusrite-Novation                   | 7         | 0.13%   |
| Dell                                 | 7         | 0.13%   |
| Audio-Technica                       | 7         | 0.13%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.11%   |
| Sony                                 | 6         | 0.11%   |
| Microsoft                            | 6         | 0.11%   |
| Cambridge Silicon Radio              | 6         | 0.11%   |
| Samson Technologies                  | 5         | 0.09%   |
| OPPO Electronics                     | 5         | 0.09%   |
| Giga-Byte Technology                 | 5         | 0.09%   |
| PreSonus Audio Electronics           | 4         | 0.07%   |
| Native Instruments                   | 4         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 285       | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 267       | 4.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 245       | 3.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 238       | 3.68%   |
| AMD Family 17h/19h HD Audio Controller                                     | 230       | 3.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 223       | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 176       | 2.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 156       | 2.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 139       | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 136       | 2.1%    |
| Intel 200 Series PCH HD Audio                                              | 105       | 1.62%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 104       | 1.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 101       | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 98        | 1.52%   |
| AMD FCH Azalia Controller                                                  | 98        | 1.52%   |
| Intel 8 Series HD Audio Controller                                         | 94        | 1.45%   |
| Intel Haswell-ULT HD Audio Controller                                      | 93        | 1.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 86        | 1.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 83        | 1.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 79        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 78        | 1.21%   |
| Intel Broadwell-U Audio Controller                                         | 72        | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 71        | 1.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 65        | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 64        | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 63        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 63        | 0.97%   |
| Nvidia GP104 High Definition Audio Controller                              | 60        | 0.93%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 60        | 0.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 0.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 55        | 0.85%   |
| Intel Comet Lake PCH-LP cAVS                                               | 54        | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 54        | 0.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 52        | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 51        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                              | 49        | 0.76%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 48        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 47        | 0.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 47        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 447       | 20.62%  |
| SK hynix                                | 361       | 16.65%  |
| Kingston                                | 254       | 11.72%  |
| Micron Technology                       | 218       | 10.06%  |
| Corsair                                 | 188       | 8.67%   |
| Unknown                                 | 165       | 7.61%   |
| Crucial                                 | 142       | 6.55%   |
| G.Skill                                 | 126       | 5.81%   |
| Team                                    | 40        | 1.85%   |
| Elpida                                  | 34        | 1.57%   |
| Nanya Technology                        | 27        | 1.25%   |
| A-DATA Technology                       | 20        | 0.92%   |
| Ramaxel Technology                      | 17        | 0.78%   |
| Patriot                                 | 17        | 0.78%   |
| GeIL                                    | 13        | 0.6%    |
| Apacer                                  | 13        | 0.6%    |
| Unknown                                 | 13        | 0.6%    |
| Transcend                               | 10        | 0.46%   |
| Unknown (ABCD)                          | 9         | 0.42%   |
| Silicon Power                           | 5         | 0.23%   |
| Strontium                               | 4         | 0.18%   |
| Neo Forza                               | 4         | 0.18%   |
| Hewlett-Packard                         | 4         | 0.18%   |
| PNY                                     | 3         | 0.14%   |
| Unknown (0x873E)                        | 2         | 0.09%   |
| Toshiba                                 | 2         | 0.09%   |
| Smart                                   | 2         | 0.09%   |
| pqi                                     | 2         | 0.09%   |
| Goldenmars                              | 2         | 0.09%   |
| Avant                                   | 2         | 0.09%   |
| ASint Technology                        | 2         | 0.09%   |
| Wodposit                                | 1         | 0.05%   |
| Unknown (0x89AD)                        | 1         | 0.05%   |
| Unknown (0x0562)                        | 1         | 0.05%   |
| Undefi                                  | 1         | 0.05%   |
| Timetec                                 | 1         | 0.05%   |
| Silicon Power Computer & Communications | 1         | 0.05%   |
| Qimonda                                 | 1         | 0.05%   |
| Princeton                               | 1         | 0.05%   |
| Netlist                                 | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 20        | 0.86%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 17        | 0.73%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s         | 17        | 0.73%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s         | 17        | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 16        | 0.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 14        | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 13        | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 13        | 0.56%   |
| Unknown                                                       | 13        | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 12        | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s      | 12        | 0.51%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 11        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 11        | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 11        | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 11        | 0.47%   |
| Kingston RAM CL16-16-16 D4-2400 8192MB DIMM DDR4 2400MT/s     | 11        | 0.47%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 10        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 10        | 0.43%   |
| GeIL RAM CL11-11-11 D3-1600 4GB DIMM 1600MT/s                 | 10        | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3800MT/s        | 10        | 0.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 9         | 0.39%   |
| G.Skill RAM F4-2666C19-8GIS 8GB DIMM DDR4 3200MT/s            | 9         | 0.39%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 8         | 0.34%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 8         | 0.34%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 8         | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 8         | 0.34%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s      | 8         | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 8         | 0.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 0.34%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 8         | 0.34%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 8         | 0.34%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                        | 7         | 0.3%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 7         | 0.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 7         | 0.3%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 7         | 0.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 7         | 0.3%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 7         | 0.3%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s         | 7         | 0.3%    |
| G.Skill RAM F3-1600C11-8GNT 8GB DIMM DDR3 1600MT/s            | 7         | 0.3%    |
| Crucial RAM CT8G4DFD8213.C16FBD2 8192MB DIMM DDR4 2500MT/s    | 7         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 891       | 46.7%   |
| DDR3    | 628       | 32.91%  |
| LPDDR3  | 82        | 4.3%    |
| Unknown | 78        | 4.09%   |
| DDR2    | 65        | 3.41%   |
| LPDDR4  | 61        | 3.2%    |
| DDR5    | 39        | 2.04%   |
| SDRAM   | 25        | 1.31%   |
| LPDDR5  | 24        | 1.26%   |
| DDR     | 12        | 0.63%   |
| DRAM    | 3         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 912       | 48%     |
| DIMM         | 815       | 42.89%  |
| Row Of Chips | 154       | 8.11%   |
| Chip         | 12        | 0.63%   |
| FB-DIMM      | 3         | 0.16%   |
| Unknown      | 3         | 0.16%   |
| RIMM         | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 842       | 41.34%  |
| 4096  | 484       | 23.76%  |
| 16384 | 348       | 17.08%  |
| 2048  | 217       | 10.65%  |
| 32768 | 88        | 4.32%   |
| 1024  | 42        | 2.06%   |
| 512   | 10        | 0.49%   |
| 65536 | 3         | 0.15%   |
| 49152 | 1         | 0.05%   |
| 1536  | 1         | 0.05%   |
| 256   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 424       | 20.44%  |
| 2667    | 275       | 13.26%  |
| 3200    | 249       | 12.01%  |
| 1333    | 152       | 7.33%   |
| 2400    | 145       | 6.99%   |
| 2133    | 127       | 6.12%   |
| 3600    | 68        | 3.28%   |
| 1334    | 61        | 2.94%   |
| 1867    | 50        | 2.41%   |
| 800     | 48        | 2.31%   |
| 667     | 44        | 2.12%   |
| 4800    | 34        | 1.64%   |
| 4267    | 27        | 1.3%    |
| 6400    | 26        | 1.25%   |
| 1067    | 23        | 1.11%   |
| Unknown | 23        | 1.11%   |
| 3733    | 19        | 0.92%   |
| 3000    | 19        | 0.92%   |
| 3533    | 18        | 0.87%   |
| 3800    | 17        | 0.82%   |
| 3400    | 17        | 0.82%   |
| 1866    | 15        | 0.72%   |
| 1066    | 15        | 0.72%   |
| 3266    | 14        | 0.68%   |
| 2666    | 12        | 0.58%   |
| 1800    | 12        | 0.58%   |
| 2933    | 11        | 0.53%   |
| 4266    | 8         | 0.39%   |
| 8400    | 7         | 0.34%   |
| 3866    | 7         | 0.34%   |
| 2500    | 7         | 0.34%   |
| 5600    | 6         | 0.29%   |
| 4000    | 6         | 0.29%   |
| 2800    | 6         | 0.29%   |
| 533     | 6         | 0.29%   |
| 3666    | 5         | 0.24%   |
| 3100    | 5         | 0.24%   |
| 2048    | 5         | 0.24%   |
| 400     | 5         | 0.24%   |
| 5200    | 4         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 39        | 28.89%  |
| Hewlett-Packard        | 31        | 22.96%  |
| Canon                  | 23        | 17.04%  |
| Seiko Epson            | 9         | 6.67%   |
| Fuji Xerox             | 8         | 5.93%   |
| Samsung Electronics    | 6         | 4.44%   |
| Prolific Technology    | 6         | 4.44%   |
| Dymo-CoStar            | 4         | 2.96%   |
| Lexmark International  | 2         | 1.48%   |
| Kyocera                | 2         | 1.48%   |
| Zebra                  | 1         | 0.74%   |
| Xerox                  | 1         | 0.74%   |
| Ricoh                  | 1         | 0.74%   |
| Custom Engineering SPA | 1         | 0.74%   |
| BIXOLON                | 1         | 0.74%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2600 series                       | 8         | 5.76%   |
| Prolific PL2305 Parallel Port                | 6         | 4.32%   |
| Brother HL-2130 series                       | 5         | 3.6%    |
| Brother HL-1110 series                       | 5         | 3.6%    |
| HP DeskJet 2130 series                       | 4         | 2.88%   |
| Brother HL-1210W series                      | 4         | 2.88%   |
| HP ENVY 5000 series                          | 3         | 2.16%   |
| HP DeskJet F2100 Printer series              | 3         | 2.16%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 2.16%   |
| Canon TS3100 series                          | 3         | 2.16%   |
| Canon LiDE 400                               | 3         | 2.16%   |
| Brother HL-L3230CDW series                   | 3         | 2.16%   |
| HP OfficeJet 5200 series                     | 2         | 1.44%   |
| HP DeskJet 3630 series                       | 2         | 1.44%   |
| Fuji Xerox DocuPrint P205 b                  | 2         | 1.44%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 2         | 1.44%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo       | 2         | 1.44%   |
| Canon TR8500 series                          | 2         | 1.44%   |
| Canon PIXMA MX920 Series                     | 2         | 1.44%   |
| Canon PIXMA MG5600 Series                    | 2         | 1.44%   |
| Canon PIXMA MG2500 Series                    | 2         | 1.44%   |
| Brother QL-570 Label Printer                 | 2         | 1.44%   |
| Brother Printer                              | 2         | 1.44%   |
| Brother MFC-L8690CDW series                  | 2         | 1.44%   |
| Brother MFC-1810                             | 2         | 1.44%   |
| Brother HL-L2305 series                      | 2         | 1.44%   |
| Zebra ZTC LP2844-Z-200dpi                    | 1         | 0.72%   |
| Xerox Phaser 8400N                           | 1         | 0.72%   |
| Seiko Epson XP-4100 Series                   | 1         | 0.72%   |
| Seiko Epson XP-240 Series                    | 1         | 0.72%   |
| Seiko Epson WF-5190 Series                   | 1         | 0.72%   |
| Seiko Epson WF-4830 Series                   | 1         | 0.72%   |
| Seiko Epson WF-2830 Series                   | 1         | 0.72%   |
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 0.72%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.72%   |
| Seiko Epson L3250 Series                     | 1         | 0.72%   |
| Seiko Epson ET-2820 Series                   | 1         | 0.72%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 0.72%   |
| Samsung ML-1865                              | 1         | 0.72%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.72%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Canon            | 13        | 65%     |
| Seiko Epson      | 4         | 20%     |
| Syscan           | 1         | 5%      |
| Salix Technology | 1         | 5%      |
| Mustek Systems   | 1         | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                 | 3         | 15%     |
| Canon CanoScan LIDE 25                                  | 2         | 10%     |
| Syscan TravelScan 460/464                               | 1         | 5%      |
| Seiko Epson Scanner                                     | 1         | 5%      |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 5%      |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 5%      |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 5%      |
| Salix USB Scanner.                                      | 1         | 5%      |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 5%      |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 5%      |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 5%      |
| Canon CanoScan LiDE 500F                                | 1         | 5%      |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 5%      |
| Canon CanoScan LiDE 220                                 | 1         | 5%      |
| Canon CanoScan LiDE 200                                 | 1         | 5%      |
| Canon CanoScan LiDE 110                                 | 1         | 5%      |
| Canon CanoScan 1220U                                    | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 427       | 21.09%  |
| Logitech                               | 197       | 9.73%   |
| Microdia                               | 164       | 8.1%    |
| Apple                                  | 150       | 7.41%   |
| Realtek Semiconductor                  | 144       | 7.11%   |
| IMC Networks                           | 130       | 6.42%   |
| Sunplus Innovation Technology          | 126       | 6.22%   |
| Bison Electronics                      | 78        | 3.85%   |
| Quanta                                 | 76        | 3.75%   |
| Cheng Uei Precision Industry (Foxlink) | 66        | 3.26%   |
| Suyin                                  | 59        | 2.91%   |
| Microsoft                              | 53        | 2.62%   |
| Acer                                   | 47        | 2.32%   |
| Lite-On Technology                     | 31        | 1.53%   |
| Samsung Electronics                    | 29        | 1.43%   |
| Syntek                                 | 28        | 1.38%   |
| Luxvisions Innotech Limited            | 24        | 1.19%   |
| Silicon Motion                         | 14        | 0.69%   |
| Alcor Micro                            | 13        | 0.64%   |
| Sonix Technology                       | 12        | 0.59%   |
| Importek                               | 12        | 0.59%   |
| Ricoh                                  | 11        | 0.54%   |
| Razer USA                              | 10        | 0.49%   |
| Lenovo                                 | 9         | 0.44%   |
| Primax Electronics                     | 7         | 0.35%   |
| GEMBIRD                                | 7         | 0.35%   |
| Z-Star Microelectronics                | 6         | 0.3%    |
| OPPO Electronics                       | 6         | 0.3%    |
| OmniVision Technologies                | 6         | 0.3%    |
| LG Electronics                         | 6         | 0.3%    |
| Generalplus Technology                 | 6         | 0.3%    |
| Magic Control Technology               | 5         | 0.25%   |
| USB Camera                             | 4         | 0.2%    |
| Genesys Logic                          | 4         | 0.2%    |
| DigiTech                               | 4         | 0.2%    |
| Cubeternet                             | 4         | 0.2%    |
| ALi                                    | 4         | 0.2%    |
| webcamvendor                           | 3         | 0.15%   |
| MacroSilicon                           | 3         | 0.15%   |
| SunplusIT                              | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 79        | 3.82%   |
| Chicony Integrated Camera                               | 76        | 3.67%   |
| Apple FaceTime HD Camera (Built-in)                     | 53        | 2.56%   |
| Realtek Integrated_Webcam_HD                            | 48        | 2.32%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 38        | 1.84%   |
| Chicony HD Webcam                                       | 35        | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 34        | 1.64%   |
| Apple Built-in iSight                                   | 34        | 1.64%   |
| Sunplus Integrated_Webcam_HD                            | 33        | 1.59%   |
| IMC Networks Integrated Camera                          | 32        | 1.55%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 29        | 1.4%    |
| Chicony TOSHIBA Web Camera - HD                         | 28        | 1.35%   |
| Bison Integrated Camera                                 | 28        | 1.35%   |
| Logitech Webcam C270                                    | 27        | 1.3%    |
| Logitech HD Pro Webcam C920                             | 26        | 1.26%   |
| Logitech C922 Pro Stream Webcam                         | 23        | 1.11%   |
| Realtek USB Camera                                      | 22        | 1.06%   |
| Syntek Integrated Camera                                | 19        | 0.92%   |
| Apple FaceTime HD Camera                                | 19        | 0.92%   |
| Chicony HP TrueVision HD Camera                         | 18        | 0.87%   |
| Chicony HP HD Camera                                    | 18        | 0.87%   |
| Chicony HP TrueVision HD                                | 17        | 0.82%   |
| Chicony HD User Facing                                  | 17        | 0.82%   |
| Sunplus HD WebCam                                       | 15        | 0.72%   |
| Logitech HD Webcam C615                                 | 14        | 0.68%   |
| Chicony USB 2.0 Camera                                  | 14        | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.68%   |
| Quanta HD User Facing                                   | 13        | 0.63%   |
| Microsoft LifeCam HD-3000                               | 13        | 0.63%   |
| Chicony EasyCamera                                      | 13        | 0.63%   |
| Suyin HP Truevision HD                                  | 12        | 0.58%   |
| Logitech Webcam C930e                                   | 12        | 0.58%   |
| Logitech StreamCam                                      | 12        | 0.58%   |
| Lite-On Integrated Camera                               | 12        | 0.58%   |
| Acer Integrated Camera                                  | 12        | 0.58%   |
| Quanta HP TrueVision HD Camera                          | 11        | 0.53%   |
| Microdia Integrated_Webcam_FHD                          | 11        | 0.53%   |
| Chicony USB2.0 Camera                                   | 11        | 0.53%   |
| Chicony Integrated Camera (1280x720@30)                 | 11        | 0.53%   |
| Chicony CNF9055 Toshiba Webcam                          | 11        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 159       | 42.06%  |
| Synaptics                          | 93        | 24.6%   |
| Shenzhen Goodix Technology         | 44        | 11.64%  |
| LighTuning Technology              | 23        | 6.08%   |
| Elan Microelectronics              | 18        | 4.76%   |
| AuthenTec                          | 18        | 4.76%   |
| Upek                               | 14        | 3.7%    |
| STMicroelectronics                 | 7         | 1.85%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.26%   |
| Focal-systems.Corp                 | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 7.94%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 7.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 5.29%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 3.97%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 3.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 13        | 3.44%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 3.44%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 3.44%   |
| Validity Sensors VFS491                                                    | 12        | 3.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 3.17%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.17%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.17%   |
| Synaptics  WBDI                                                            | 11        | 2.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 2.91%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 2.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 10        | 2.65%   |
| Synaptics WBDI                                                             | 9         | 2.38%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.38%   |
| Elan ELAN:ARM-M4                                                           | 9         | 2.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.12%   |
| Validity Sensors VFS Fingerprint sensor                                    | 8         | 2.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.85%   |
| Synaptics UWP WBDI                                                         | 7         | 1.85%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 1.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.59%   |
| Synaptics WBDI Device                                                      | 5         | 1.32%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.06%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.06%   |
| AuthenTec AES1600                                                          | 4         | 1.06%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.79%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.79%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 0.53%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.53%   |
| Synaptics TouchPad                                                         | 2         | 0.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 41        | 57.75%  |
| Alcor Micro           | 16        | 22.54%  |
| Upek                  | 4         | 5.63%   |
| Lenovo                | 3         | 4.23%   |
| Advanced Card Systems | 3         | 4.23%   |
| O2 Micro              | 2         | 2.82%   |
| Microchip Technology  | 1         | 1.41%   |
| Gemalto (was Gemplus) | 1         | 1.41%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 25.35%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 22.54%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 11.27%  |
| Broadcom 58200                                                               | 8         | 11.27%  |
| Broadcom 5880                                                                | 7         | 9.86%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.63%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.23%   |
| Advanced Card Systems ACR122U                                                | 3         | 4.23%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.82%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 1.41%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.41%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2712      | 69.61%  |
| 1     | 971       | 24.92%  |
| 2     | 170       | 4.36%   |
| 3     | 30        | 0.77%   |
| 4     | 11        | 0.28%   |
| 7     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 375       | 27.31%  |
| Graphics card            | 321       | 23.38%  |
| Net/wireless             | 199       | 14.49%  |
| Multimedia controller    | 95        | 6.92%   |
| Chipcard                 | 64        | 4.66%   |
| Communication controller | 62        | 4.52%   |
| Camera                   | 47        | 3.42%   |
| Bluetooth                | 44        | 3.2%    |
| Unassigned class         | 38        | 2.77%   |
| Net/ethernet             | 29        | 2.11%   |
| Sound                    | 23        | 1.68%   |
| Storage                  | 19        | 1.38%   |
| Modem                    | 11        | 0.8%    |
| Network                  | 10        | 0.73%   |
| Card reader              | 9         | 0.66%   |
| Dvb card                 | 8         | 0.58%   |
| Storage/raid             | 6         | 0.44%   |
| Video                    | 3         | 0.22%   |
| Firewire controller      | 3         | 0.22%   |
| Storage/ata              | 2         | 0.15%   |
| Unclassified device      | 1         | 0.07%   |
| Tv card                  | 1         | 0.07%   |
| Storage/nvme             | 1         | 0.07%   |
| Storage/ide              | 1         | 0.07%   |
| Flash memory             | 1         | 0.07%   |


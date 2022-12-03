Linux in Bulgaria - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bulgaria/Desktop/README.md) and [notebooks](/Location/Bulgaria/Notebook/README.md).

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

Total: 1275

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [2d4a014ef1](https://linux-hardware.org/?probe=2d4a014ef1) | Dec 01, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [e1cec664eb](https://linux-hardware.org/?probe=e1cec664eb) | Dec 01, 2022 |
| Acer          | AO756                       | Notebook    | [c1ff6fe10c](https://linux-hardware.org/?probe=c1ff6fe10c) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [1424a94eb0](https://linux-hardware.org/?probe=1424a94eb0) | Nov 29, 2022 |
| Acer          | AO756                       | Notebook    | [fa5c9df13a](https://linux-hardware.org/?probe=fa5c9df13a) | Nov 27, 2022 |
| Acer          | AO756                       | Notebook    | [d390d588fe](https://linux-hardware.org/?probe=d390d588fe) | Nov 27, 2022 |
| HP            | 1589                        | Desktop     | [4e67735055](https://linux-hardware.org/?probe=4e67735055) | Nov 27, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d480b7ef56](https://linux-hardware.org/?probe=d480b7ef56) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d3b2f8aaf7](https://linux-hardware.org/?probe=d3b2f8aaf7) | Nov 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [797ac58b69](https://linux-hardware.org/?probe=797ac58b69) | Nov 23, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [210dd0f9f5](https://linux-hardware.org/?probe=210dd0f9f5) | Nov 20, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [faa15c49ae](https://linux-hardware.org/?probe=faa15c49ae) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6c5f37f683](https://linux-hardware.org/?probe=6c5f37f683) | Nov 19, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [ea1dbc4f7c](https://linux-hardware.org/?probe=ea1dbc4f7c) | Nov 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [d053fe8efe](https://linux-hardware.org/?probe=d053fe8efe) | Nov 16, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [5468f11c01](https://linux-hardware.org/?probe=5468f11c01) | Nov 15, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | Notebook    | [f77af97294](https://linux-hardware.org/?probe=f77af97294) | Nov 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [cca85a282e](https://linux-hardware.org/?probe=cca85a282e) | Nov 09, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [b1a9ec43d4](https://linux-hardware.org/?probe=b1a9ec43d4) | Nov 07, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [519c833f31](https://linux-hardware.org/?probe=519c833f31) | Nov 06, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f57f494508](https://linux-hardware.org/?probe=f57f494508) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Dell          | Vostro 1310                 | Notebook    | [0ae18c6c3b](https://linux-hardware.org/?probe=0ae18c6c3b) | Nov 03, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | Notebook    | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [ded0ce1d3e](https://linux-hardware.org/?probe=ded0ce1d3e) | Oct 29, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [73f4952d74](https://linux-hardware.org/?probe=73f4952d74) | Oct 29, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [1b3bb91776](https://linux-hardware.org/?probe=1b3bb91776) | Oct 29, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [ced3daa1b6](https://linux-hardware.org/?probe=ced3daa1b6) | Oct 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [81231e9517](https://linux-hardware.org/?probe=81231e9517) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| HP            | 8061                        | Desktop     | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| Acer          | Aspire 5830T                | Notebook    | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Toshiba       | Satellite L775-125          | Notebook    | [fbe4f1922c](https://linux-hardware.org/?probe=fbe4f1922c) | Oct 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [17c133e933](https://linux-hardware.org/?probe=17c133e933) | Oct 15, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [b50165d9c9](https://linux-hardware.org/?probe=b50165d9c9) | Oct 11, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [1f2485fab4](https://linux-hardware.org/?probe=1f2485fab4) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Intel         | D34010WYK H14771-303        | Desktop     | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8f41682975](https://linux-hardware.org/?probe=8f41682975) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Samsung       | Galaxy TabPro S             | Tablet      | [25deda3e27](https://linux-hardware.org/?probe=25deda3e27) | Oct 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [cb134441f2](https://linux-hardware.org/?probe=cb134441f2) | Sep 13, 2022 |
| HP            | 3047h                       | Desktop     | [097b5b2f29](https://linux-hardware.org/?probe=097b5b2f29) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [8afd29a71f](https://linux-hardware.org/?probe=8afd29a71f) | Sep 09, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [611d7b9001](https://linux-hardware.org/?probe=611d7b9001) | Sep 07, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3438959476](https://linux-hardware.org/?probe=3438959476) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Dell          | Latitude E5270              | Notebook    | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [3239a22fc0](https://linux-hardware.org/?probe=3239a22fc0) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [e4cdaf6b35](https://linux-hardware.org/?probe=e4cdaf6b35) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c8244526c](https://linux-hardware.org/?probe=5c8244526c) | Aug 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [8047eeecb4](https://linux-hardware.org/?probe=8047eeecb4) | Aug 20, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | Notebook    | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c92d457cd6](https://linux-hardware.org/?probe=c92d457cd6) | Aug 13, 2022 |
| ASUSTek       | M2VTVM-VM890                | Desktop     | [8a822a57e8](https://linux-hardware.org/?probe=8a822a57e8) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [747ba68b28](https://linux-hardware.org/?probe=747ba68b28) | Aug 10, 2022 |
| Apple         | MacBookPro16,4              | Notebook    | [7571d6d783](https://linux-hardware.org/?probe=7571d6d783) | Aug 09, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1b55fc7b56](https://linux-hardware.org/?probe=1b55fc7b56) | Aug 09, 2022 |
| Lenovo        | Unknown                     | Notebook    | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [616c57c367](https://linux-hardware.org/?probe=616c57c367) | Aug 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [e0129903ae](https://linux-hardware.org/?probe=e0129903ae) | Aug 04, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [7e9c9d2fc4](https://linux-hardware.org/?probe=7e9c9d2fc4) | Jul 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [faf9360275](https://linux-hardware.org/?probe=faf9360275) | Jul 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| HP            | 1495                        | Desktop     | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | Desktop     | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [69bd504820](https://linux-hardware.org/?probe=69bd504820) | Jul 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | Notebook    | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | Desktop     | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [2c0dd875b3](https://linux-hardware.org/?probe=2c0dd875b3) | Jun 21, 2022 |
| HP            | ProLiant ML350 G5           | Desktop     | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [489dd3049e](https://linux-hardware.org/?probe=489dd3049e) | Jun 13, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| HP            | 872D                        | Desktop     | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | Notebook    | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | Notebook    | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| Acer          | Predator G3-605             | Desktop     | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| Gigabyte      | H97N                        | Desktop     | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [ff7adfb82a](https://linux-hardware.org/?probe=ff7adfb82a) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [c40273d0bc](https://linux-hardware.org/?probe=c40273d0bc) | Apr 29, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| MSI           | PRO B660-A DDR4             | Desktop     | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | Notebook    | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [86aeb14193](https://linux-hardware.org/?probe=86aeb14193) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| Dell          | Precision M6800             | Notebook    | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | Notebook    | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | Notebook    | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | Notebook    | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5914978461](https://linux-hardware.org/?probe=5914978461) | Mar 04, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [43f47c3d8e](https://linux-hardware.org/?probe=43f47c3d8e) | Feb 28, 2022 |
| ASUSTek       | N551VW                      | Notebook    | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [dc3262a408](https://linux-hardware.org/?probe=dc3262a408) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | Notebook    | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | Desktop     | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [2024310fec](https://linux-hardware.org/?probe=2024310fec) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [88a943ec80](https://linux-hardware.org/?probe=88a943ec80) | Feb 16, 2022 |
| Dell          | Latitude E6330              | Notebook    | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | Notebook    | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| Dell          | Inspiron 5482               | Convertible | [17584ae0e4](https://linux-hardware.org/?probe=17584ae0e4) | Feb 12, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V                    | Desktop     | [d00c78fd08](https://linux-hardware.org/?probe=d00c78fd08) | Feb 08, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Intel         | X99                         | Desktop     | [f4a0c1aaaa](https://linux-hardware.org/?probe=f4a0c1aaaa) | Jan 20, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [821f3261c2](https://linux-hardware.org/?probe=821f3261c2) | Jan 18, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [d027268e2b](https://linux-hardware.org/?probe=d027268e2b) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [a9ed1157c0](https://linux-hardware.org/?probe=a9ed1157c0) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | Notebook    | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f23503b603](https://linux-hardware.org/?probe=f23503b603) | Jan 10, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [7add8fadfa](https://linux-hardware.org/?probe=7add8fadfa) | Jan 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e8cfb51ca5](https://linux-hardware.org/?probe=e8cfb51ca5) | Jan 04, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| HP            | 3397                        | Desktop     | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| ASUSTek       | P5E                         | Desktop     | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | Notebook    | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | Notebook    | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [65ec484cf7](https://linux-hardware.org/?probe=65ec484cf7) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ab70f6516f](https://linux-hardware.org/?probe=ab70f6516f) | Dec 16, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| HP            | ProBook 4540s               | Notebook    | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | Notebook    | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | Notebook    | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Acer          | Predator G3-605             | Desktop     | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | Notebook    | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | Notebook    | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8cae94b7f8](https://linux-hardware.org/?probe=8cae94b7f8) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3ab004eed4](https://linux-hardware.org/?probe=3ab004eed4) | Oct 17, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| ASRock        | H81M-HDS                    | Desktop     | [300c7e725d](https://linux-hardware.org/?probe=300c7e725d) | Oct 10, 2021 |
| HP            | Pavilion dv7                | Notebook    | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [637dbbacba](https://linux-hardware.org/?probe=637dbbacba) | Oct 08, 2021 |
| Acer          | Aspire A515-52G             | Notebook    | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| Acer          | Extensa 5630                | Notebook    | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | Notebook    | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| Lenovo        | ThinkStation D20 4158E93    | Desktop     | [fde770f309](https://linux-hardware.org/?probe=fde770f309) | Sep 11, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [a95e304baf](https://linux-hardware.org/?probe=a95e304baf) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [a37b749b27](https://linux-hardware.org/?probe=a37b749b27) | Sep 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [92e21fb915](https://linux-hardware.org/?probe=92e21fb915) | Sep 06, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | Notebook    | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [7c76ac10d8](https://linux-hardware.org/?probe=7c76ac10d8) | Sep 04, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d831e8693d](https://linux-hardware.org/?probe=d831e8693d) | Sep 04, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [7d634f76ad](https://linux-hardware.org/?probe=7d634f76ad) | Aug 31, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [8f10e30326](https://linux-hardware.org/?probe=8f10e30326) | Aug 28, 2021 |
| HP            | 18E4                        | Desktop     | [81c51891c9](https://linux-hardware.org/?probe=81c51891c9) | Aug 27, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [257e2c9dd4](https://linux-hardware.org/?probe=257e2c9dd4) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [59f5bb4379](https://linux-hardware.org/?probe=59f5bb4379) | Aug 18, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3bfb2e6910](https://linux-hardware.org/?probe=3bfb2e6910) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [4c3bedddac](https://linux-hardware.org/?probe=4c3bedddac) | Aug 14, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [4fce5e2d88](https://linux-hardware.org/?probe=4fce5e2d88) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [0c191944fc](https://linux-hardware.org/?probe=0c191944fc) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [a08f9bd38d](https://linux-hardware.org/?probe=a08f9bd38d) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | Notebook    | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| HP            | ProBook 6450b               | Notebook    | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [5d62f330ba](https://linux-hardware.org/?probe=5d62f330ba) | Jul 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | Notebook    | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [d3f2c6d8d8](https://linux-hardware.org/?probe=d3f2c6d8d8) | Jul 13, 2021 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [5ce964530d](https://linux-hardware.org/?probe=5ce964530d) | Jul 13, 2021 |
| Acer          | Predator G9-792             | Notebook    | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | Notebook    | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [13af782a58](https://linux-hardware.org/?probe=13af782a58) | Jun 29, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [d791d77acc](https://linux-hardware.org/?probe=d791d77acc) | Jun 28, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| HP            | 1493                        | Desktop     | [cd54c7db25](https://linux-hardware.org/?probe=cd54c7db25) | Jun 26, 2021 |
| HP            | 1493                        | Desktop     | [5b7dd91534](https://linux-hardware.org/?probe=5b7dd91534) | Jun 26, 2021 |
| Dell          | Latitude 5410               | Notebook    | [9b8e7a4fc4](https://linux-hardware.org/?probe=9b8e7a4fc4) | Jun 25, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [614eb34061](https://linux-hardware.org/?probe=614eb34061) | Jun 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9b92db3a47](https://linux-hardware.org/?probe=9b92db3a47) | Jun 24, 2021 |
| Acer          | Aspire VN7-592G             | Notebook    | [2b00566646](https://linux-hardware.org/?probe=2b00566646) | Jun 23, 2021 |
| MSI           | MS-N033                     | Notebook    | [3ba725911d](https://linux-hardware.org/?probe=3ba725911d) | Jun 22, 2021 |
| MSI           | MS-N033                     | Notebook    | [db865cd4b0](https://linux-hardware.org/?probe=db865cd4b0) | Jun 22, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e7e3e4138d](https://linux-hardware.org/?probe=e7e3e4138d) | Jun 20, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [c4f55611e4](https://linux-hardware.org/?probe=c4f55611e4) | Jun 20, 2021 |
| Acer          | Extensa 5630                | Notebook    | [a56495c8ee](https://linux-hardware.org/?probe=a56495c8ee) | Jun 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ddbd903ae7](https://linux-hardware.org/?probe=ddbd903ae7) | Jun 11, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [f200ec0bda](https://linux-hardware.org/?probe=f200ec0bda) | Jun 08, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [9a2b696908](https://linux-hardware.org/?probe=9a2b696908) | Jun 05, 2021 |
| HP            | Pavilion dv5                | Notebook    | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Dell          | Latitude 5500               | Notebook    | [4eb777675a](https://linux-hardware.org/?probe=4eb777675a) | Jun 03, 2021 |
| ASUSTek       | TP300LA                     | Notebook    | [1c4ff3ec3c](https://linux-hardware.org/?probe=1c4ff3ec3c) | Jun 02, 2021 |
| ASUSTek       | TP300LA                     | Notebook    | [aa03d405bc](https://linux-hardware.org/?probe=aa03d405bc) | May 31, 2021 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [6bc1b9dcc9](https://linux-hardware.org/?probe=6bc1b9dcc9) | May 31, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [c050f79e2b](https://linux-hardware.org/?probe=c050f79e2b) | May 29, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [7f510d13fb](https://linux-hardware.org/?probe=7f510d13fb) | May 28, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [660a6b9e20](https://linux-hardware.org/?probe=660a6b9e20) | May 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [d0705ef193](https://linux-hardware.org/?probe=d0705ef193) | May 23, 2021 |
| HP            | ProBook 4540s               | Notebook    | [08209a81e4](https://linux-hardware.org/?probe=08209a81e4) | May 23, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [eccabc11a1](https://linux-hardware.org/?probe=eccabc11a1) | May 21, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2fd0c6a88a](https://linux-hardware.org/?probe=2fd0c6a88a) | May 21, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [493f6f8057](https://linux-hardware.org/?probe=493f6f8057) | May 18, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [c6ddc776ea](https://linux-hardware.org/?probe=c6ddc776ea) | May 18, 2021 |
| Dell          | Studio 1535                 | Notebook    | [90762831e7](https://linux-hardware.org/?probe=90762831e7) | May 17, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [4d5f23e6ba](https://linux-hardware.org/?probe=4d5f23e6ba) | May 17, 2021 |
| Dell          | Studio 1535                 | Notebook    | [9d034e29dc](https://linux-hardware.org/?probe=9d034e29dc) | May 16, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [14ea7483bc](https://linux-hardware.org/?probe=14ea7483bc) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [8dac91acc9](https://linux-hardware.org/?probe=8dac91acc9) | May 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [22657f3929](https://linux-hardware.org/?probe=22657f3929) | May 15, 2021 |
| HP            | 3396                        | Desktop     | [ed3fa57f54](https://linux-hardware.org/?probe=ed3fa57f54) | May 15, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [133c3509a5](https://linux-hardware.org/?probe=133c3509a5) | May 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [67bde80034](https://linux-hardware.org/?probe=67bde80034) | May 04, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [3ad2c89a0a](https://linux-hardware.org/?probe=3ad2c89a0a) | May 03, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [59d8b5d3fe](https://linux-hardware.org/?probe=59d8b5d3fe) | May 02, 2021 |
| HP            | Pavilion dv5                | Notebook    | [f75415bbd7](https://linux-hardware.org/?probe=f75415bbd7) | May 01, 2021 |
| ASRock        | X79 Extreme4                | Desktop     | [d3383d57ef](https://linux-hardware.org/?probe=d3383d57ef) | May 01, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [37b746015a](https://linux-hardware.org/?probe=37b746015a) | Apr 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [03b6a0117c](https://linux-hardware.org/?probe=03b6a0117c) | Apr 26, 2021 |
| ASUSTek       | Amberine M                  | Desktop     | [9eeaeb53fc](https://linux-hardware.org/?probe=9eeaeb53fc) | Apr 26, 2021 |
| HP            | Notebook                    | Notebook    | [3cc10cc5f1](https://linux-hardware.org/?probe=3cc10cc5f1) | Apr 24, 2021 |
| Lenovo        | ThinkPad X230 232425U       | Notebook    | [69e5ab7b60](https://linux-hardware.org/?probe=69e5ab7b60) | Apr 24, 2021 |
| ASRock        | B360M Pro4                  | Desktop     | [b1f9a4880e](https://linux-hardware.org/?probe=b1f9a4880e) | Apr 22, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [fb1ce94b02](https://linux-hardware.org/?probe=fb1ce94b02) | Apr 16, 2021 |
| Toshiba       | Satellite U400              | Notebook    | [159d86eda9](https://linux-hardware.org/?probe=159d86eda9) | Apr 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [e6cc5fbf7f](https://linux-hardware.org/?probe=e6cc5fbf7f) | Apr 15, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [a7b1f80885](https://linux-hardware.org/?probe=a7b1f80885) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [8c83051b44](https://linux-hardware.org/?probe=8c83051b44) | Apr 12, 2021 |
| ASRock        | Z68 Extreme7 Gen3           | Desktop     | [d8e2ac9e9b](https://linux-hardware.org/?probe=d8e2ac9e9b) | Apr 11, 2021 |
| Dell          | Vostro 3558                 | Notebook    | [025fc515fe](https://linux-hardware.org/?probe=025fc515fe) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [891b52b28e](https://linux-hardware.org/?probe=891b52b28e) | Apr 08, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [bce1022d19](https://linux-hardware.org/?probe=bce1022d19) | Apr 07, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [996a7d6ddd](https://linux-hardware.org/?probe=996a7d6ddd) | Apr 06, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [929d29d6a1](https://linux-hardware.org/?probe=929d29d6a1) | Apr 04, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [ba65bedf97](https://linux-hardware.org/?probe=ba65bedf97) | Apr 04, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [658ec2843e](https://linux-hardware.org/?probe=658ec2843e) | Apr 03, 2021 |
| HP            | 1850                        | Desktop     | [517c6137a3](https://linux-hardware.org/?probe=517c6137a3) | Apr 01, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [333c645cc4](https://linux-hardware.org/?probe=333c645cc4) | Apr 01, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [b5fd8765a4](https://linux-hardware.org/?probe=b5fd8765a4) | Mar 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0d90d26719](https://linux-hardware.org/?probe=0d90d26719) | Mar 31, 2021 |
| Packard Be... | EasyNote TK87               | Notebook    | [f7a63e6a25](https://linux-hardware.org/?probe=f7a63e6a25) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | Notebook    | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | Notebook    | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [129caa2510](https://linux-hardware.org/?probe=129caa2510) | Mar 27, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [bd779f8e4e](https://linux-hardware.org/?probe=bd779f8e4e) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [072483c895](https://linux-hardware.org/?probe=072483c895) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [11e59c84c6](https://linux-hardware.org/?probe=11e59c84c6) | Mar 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [11a2b81dd1](https://linux-hardware.org/?probe=11a2b81dd1) | Mar 24, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [f6eae97e20](https://linux-hardware.org/?probe=f6eae97e20) | Mar 24, 2021 |
| Acer          | TravelMate 8571             | Notebook    | [a4f34315e7](https://linux-hardware.org/?probe=a4f34315e7) | Mar 23, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [f7c456b329](https://linux-hardware.org/?probe=f7c456b329) | Mar 22, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [f4b00c40b9](https://linux-hardware.org/?probe=f4b00c40b9) | Mar 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| Seco          | C40 C                       | Desktop     | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [2cad1297af](https://linux-hardware.org/?probe=2cad1297af) | Mar 19, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [5318792cf8](https://linux-hardware.org/?probe=5318792cf8) | Mar 19, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [e5f799a9f1](https://linux-hardware.org/?probe=e5f799a9f1) | Mar 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [1b40fb1844](https://linux-hardware.org/?probe=1b40fb1844) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d2d43a5a92](https://linux-hardware.org/?probe=d2d43a5a92) | Mar 17, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ef2bfba994](https://linux-hardware.org/?probe=ef2bfba994) | Mar 17, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [39fb7fbfdd](https://linux-hardware.org/?probe=39fb7fbfdd) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [30047ff89f](https://linux-hardware.org/?probe=30047ff89f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [3fc42af6ee](https://linux-hardware.org/?probe=3fc42af6ee) | Mar 13, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [3403829400](https://linux-hardware.org/?probe=3403829400) | Mar 13, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [e2bd9d6df8](https://linux-hardware.org/?probe=e2bd9d6df8) | Mar 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5ff3194762](https://linux-hardware.org/?probe=5ff3194762) | Mar 10, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c685612dc3](https://linux-hardware.org/?probe=c685612dc3) | Mar 09, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a76ade188b](https://linux-hardware.org/?probe=a76ade188b) | Mar 07, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [b3a1ae5051](https://linux-hardware.org/?probe=b3a1ae5051) | Mar 06, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [f14a8d2de0](https://linux-hardware.org/?probe=f14a8d2de0) | Mar 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b7a83e1d4a](https://linux-hardware.org/?probe=b7a83e1d4a) | Mar 05, 2021 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [871b9656f1](https://linux-hardware.org/?probe=871b9656f1) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ee7f196bf2](https://linux-hardware.org/?probe=ee7f196bf2) | Feb 28, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Fujitsu       | CELSIUS H720                | Notebook    | [ebed3a7dfe](https://linux-hardware.org/?probe=ebed3a7dfe) | Feb 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [a95dd47eb7](https://linux-hardware.org/?probe=a95dd47eb7) | Feb 25, 2021 |
| Intel         | X99 V102                    | Desktop     | [e4884fdd22](https://linux-hardware.org/?probe=e4884fdd22) | Feb 25, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [afb4a1cd76](https://linux-hardware.org/?probe=afb4a1cd76) | Feb 24, 2021 |
| HP            | 3396                        | Desktop     | [dd8601c672](https://linux-hardware.org/?probe=dd8601c672) | Feb 24, 2021 |
| HP            | 3396                        | Desktop     | [5c5fde40cd](https://linux-hardware.org/?probe=5c5fde40cd) | Feb 24, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [53d26490a1](https://linux-hardware.org/?probe=53d26490a1) | Feb 23, 2021 |
| Dell          | Inspiron 3584               | Notebook    | [5db4b64bf0](https://linux-hardware.org/?probe=5db4b64bf0) | Feb 23, 2021 |
| HP            | 1494                        | Desktop     | [c369d28059](https://linux-hardware.org/?probe=c369d28059) | Feb 23, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [5ad971da58](https://linux-hardware.org/?probe=5ad971da58) | Feb 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [544bcae58c](https://linux-hardware.org/?probe=544bcae58c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [698bd7ab9c](https://linux-hardware.org/?probe=698bd7ab9c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [e5ae830bbf](https://linux-hardware.org/?probe=e5ae830bbf) | Feb 21, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [b9b1df7b2d](https://linux-hardware.org/?probe=b9b1df7b2d) | Feb 21, 2021 |
| ASUSTek       | G752VL                      | Notebook    | [3c853cb10a](https://linux-hardware.org/?probe=3c853cb10a) | Feb 21, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [6606087332](https://linux-hardware.org/?probe=6606087332) | Feb 17, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [71a10bba93](https://linux-hardware.org/?probe=71a10bba93) | Feb 16, 2021 |
| Toshiba       | TECRA A11                   | Notebook    | [96fc158d33](https://linux-hardware.org/?probe=96fc158d33) | Feb 16, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f858e68811](https://linux-hardware.org/?probe=f858e68811) | Feb 15, 2021 |
| MSI           | MS-7250                     | Desktop     | [e1f266f412](https://linux-hardware.org/?probe=e1f266f412) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4dd2d0ba4d](https://linux-hardware.org/?probe=4dd2d0ba4d) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9d43f3047b](https://linux-hardware.org/?probe=9d43f3047b) | Feb 15, 2021 |
| MSI           | H61M-P31                    | Desktop     | [256f5dc934](https://linux-hardware.org/?probe=256f5dc934) | Feb 14, 2021 |
| ASUSTek       | A8N-E                       | Desktop     | [a35eff4bb9](https://linux-hardware.org/?probe=a35eff4bb9) | Feb 14, 2021 |
| iEi           | B202 V1.0                   | Desktop     | [3dce687709](https://linux-hardware.org/?probe=3dce687709) | Feb 14, 2021 |
| Gigabyte      | H81M-HD3                    | Desktop     | [b6b357f26c](https://linux-hardware.org/?probe=b6b357f26c) | Feb 14, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [476cc70c3f](https://linux-hardware.org/?probe=476cc70c3f) | Feb 13, 2021 |
| ASRock        | 890GX Extreme3              | Desktop     | [1168daa7de](https://linux-hardware.org/?probe=1168daa7de) | Feb 13, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [aa7fb32dfe](https://linux-hardware.org/?probe=aa7fb32dfe) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [dc1822ee72](https://linux-hardware.org/?probe=dc1822ee72) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [8fedc4a9c1](https://linux-hardware.org/?probe=8fedc4a9c1) | Feb 12, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [2d6363ed19](https://linux-hardware.org/?probe=2d6363ed19) | Feb 10, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [b3a0df6f88](https://linux-hardware.org/?probe=b3a0df6f88) | Feb 10, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [12349b18fb](https://linux-hardware.org/?probe=12349b18fb) | Feb 10, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [32fe0edcd8](https://linux-hardware.org/?probe=32fe0edcd8) | Feb 07, 2021 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [e196e2ba5d](https://linux-hardware.org/?probe=e196e2ba5d) | Feb 07, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ea03b28712](https://linux-hardware.org/?probe=ea03b28712) | Feb 06, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [a327d5e0ca](https://linux-hardware.org/?probe=a327d5e0ca) | Feb 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0SY0... | Notebook    | [26dbb68145](https://linux-hardware.org/?probe=26dbb68145) | Feb 05, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [43384d51bb](https://linux-hardware.org/?probe=43384d51bb) | Feb 04, 2021 |
| HP            | ProBook 6460b               | Notebook    | [e531fae869](https://linux-hardware.org/?probe=e531fae869) | Feb 02, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [154f183a32](https://linux-hardware.org/?probe=154f183a32) | Feb 01, 2021 |
| ASRock        | FM2A85X Extreme4            | Desktop     | [2f1725cb23](https://linux-hardware.org/?probe=2f1725cb23) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [0d28bdf0d4](https://linux-hardware.org/?probe=0d28bdf0d4) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [566ca9b700](https://linux-hardware.org/?probe=566ca9b700) | Jan 30, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d566b4292e](https://linux-hardware.org/?probe=d566b4292e) | Jan 30, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [c0670e9519](https://linux-hardware.org/?probe=c0670e9519) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [5e824ae0f4](https://linux-hardware.org/?probe=5e824ae0f4) | Jan 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [c8df50c9cc](https://linux-hardware.org/?probe=c8df50c9cc) | Jan 28, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [752f448ced](https://linux-hardware.org/?probe=752f448ced) | Jan 25, 2021 |
| ASRock        | H87M Pro4                   | Desktop     | [88e1834599](https://linux-hardware.org/?probe=88e1834599) | Jan 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2fef9954bb](https://linux-hardware.org/?probe=2fef9954bb) | Jan 24, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [194dbb8e46](https://linux-hardware.org/?probe=194dbb8e46) | Jan 24, 2021 |
| Gigabyte      | M68M-S2P                    | Desktop     | [bdee5c1907](https://linux-hardware.org/?probe=bdee5c1907) | Jan 23, 2021 |
| ASRock        | H110M-HDV                   | Desktop     | [6eecfdfd4b](https://linux-hardware.org/?probe=6eecfdfd4b) | Jan 21, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [e10b7bc8cf](https://linux-hardware.org/?probe=e10b7bc8cf) | Jan 21, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [2f0ad65f95](https://linux-hardware.org/?probe=2f0ad65f95) | Jan 16, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [676959ecd5](https://linux-hardware.org/?probe=676959ecd5) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [782581f6ad](https://linux-hardware.org/?probe=782581f6ad) | Jan 15, 2021 |
| MiTAC         | E220 6A7                    | Desktop     | [0d75e5ba34](https://linux-hardware.org/?probe=0d75e5ba34) | Jan 14, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [839dd41ca6](https://linux-hardware.org/?probe=839dd41ca6) | Jan 13, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [1c8eedbc0f](https://linux-hardware.org/?probe=1c8eedbc0f) | Jan 11, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [947ae48eec](https://linux-hardware.org/?probe=947ae48eec) | Jan 10, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [20416ee115](https://linux-hardware.org/?probe=20416ee115) | Jan 10, 2021 |
| HP            | EliteBook 1050 G1           | Notebook    | [34b72d5988](https://linux-hardware.org/?probe=34b72d5988) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [9cd4e14d95](https://linux-hardware.org/?probe=9cd4e14d95) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [d0a18fe6bf](https://linux-hardware.org/?probe=d0a18fe6bf) | Jan 09, 2021 |
| Sony          | VPCEA3L1E                   | Notebook    | [5d9e8a1b24](https://linux-hardware.org/?probe=5d9e8a1b24) | Jan 08, 2021 |
| Sony          | VPCEA3L1E                   | Notebook    | [251d4f6677](https://linux-hardware.org/?probe=251d4f6677) | Jan 07, 2021 |
| Dell          | Latitude E5440              | Notebook    | [b207a3f9fc](https://linux-hardware.org/?probe=b207a3f9fc) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [67484b4909](https://linux-hardware.org/?probe=67484b4909) | Jan 06, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [1c948eea28](https://linux-hardware.org/?probe=1c948eea28) | Jan 05, 2021 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [13e7f80b8f](https://linux-hardware.org/?probe=13e7f80b8f) | Jan 03, 2021 |
| Packard Be... | EasyNote TK87               | Notebook    | [c56d5ed89f](https://linux-hardware.org/?probe=c56d5ed89f) | Jan 03, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [5232dd577c](https://linux-hardware.org/?probe=5232dd577c) | Jan 03, 2021 |
| Dell          | Latitude E6410              | Notebook    | [0a272a215c](https://linux-hardware.org/?probe=0a272a215c) | Jan 02, 2021 |
| Dell          | Latitude E6410              | Notebook    | [38d452be3e](https://linux-hardware.org/?probe=38d452be3e) | Jan 02, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [50edfe4e5e](https://linux-hardware.org/?probe=50edfe4e5e) | Jan 01, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [05fcb61de6](https://linux-hardware.org/?probe=05fcb61de6) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [b1855e2094](https://linux-hardware.org/?probe=b1855e2094) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [5d028d0524](https://linux-hardware.org/?probe=5d028d0524) | Dec 29, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [83cb7ff036](https://linux-hardware.org/?probe=83cb7ff036) | Dec 28, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [55bd66c418](https://linux-hardware.org/?probe=55bd66c418) | Dec 27, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b2e6caf193](https://linux-hardware.org/?probe=b2e6caf193) | Dec 25, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [06f63c2119](https://linux-hardware.org/?probe=06f63c2119) | Dec 24, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [fed52f343a](https://linux-hardware.org/?probe=fed52f343a) | Dec 24, 2020 |
| MiTAC         | E220 6A7                    | Desktop     | [e051bc126d](https://linux-hardware.org/?probe=e051bc126d) | Dec 23, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [d04453166b](https://linux-hardware.org/?probe=d04453166b) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | Notebook    | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Dell          | 0K240Y A02                  | Desktop     | [d522c503da](https://linux-hardware.org/?probe=d522c503da) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [ad3ac7bcee](https://linux-hardware.org/?probe=ad3ac7bcee) | Dec 19, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [17dc1d498a](https://linux-hardware.org/?probe=17dc1d498a) | Dec 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e665e888af](https://linux-hardware.org/?probe=e665e888af) | Dec 16, 2020 |
| Unknown       | GSUO H61                    | Desktop     | [3c4c6c8bd0](https://linux-hardware.org/?probe=3c4c6c8bd0) | Dec 14, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [eb181ebb12](https://linux-hardware.org/?probe=eb181ebb12) | Dec 14, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [8e26299b90](https://linux-hardware.org/?probe=8e26299b90) | Dec 13, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [d0388f0066](https://linux-hardware.org/?probe=d0388f0066) | Dec 12, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [2f0d63f9a3](https://linux-hardware.org/?probe=2f0d63f9a3) | Dec 12, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [0236c0854e](https://linux-hardware.org/?probe=0236c0854e) | Dec 12, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [2c39a254ee](https://linux-hardware.org/?probe=2c39a254ee) | Dec 11, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [d4d7a977db](https://linux-hardware.org/?probe=d4d7a977db) | Dec 07, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6502e1050d](https://linux-hardware.org/?probe=6502e1050d) | Dec 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [a388c1bf1e](https://linux-hardware.org/?probe=a388c1bf1e) | Dec 05, 2020 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [b7e98a5926](https://linux-hardware.org/?probe=b7e98a5926) | Dec 04, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [ef428fdd17](https://linux-hardware.org/?probe=ef428fdd17) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [d12dc95e76](https://linux-hardware.org/?probe=d12dc95e76) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [02c7320eaf](https://linux-hardware.org/?probe=02c7320eaf) | Dec 03, 2020 |
| ASRock        | G41M-S3                     | Desktop     | [1f91a14ff2](https://linux-hardware.org/?probe=1f91a14ff2) | Dec 03, 2020 |
| Dell          | Latitude 5591               | Notebook    | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| Dell          | Vostro 3580                 | Notebook    | [a3342731b8](https://linux-hardware.org/?probe=a3342731b8) | Dec 01, 2020 |
| Cube          | i16-L                       | Notebook    | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | Notebook    | [f5481042a6](https://linux-hardware.org/?probe=f5481042a6) | Nov 30, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | Notebook    | [911676a550](https://linux-hardware.org/?probe=911676a550) | Nov 30, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [7b8b964ce4](https://linux-hardware.org/?probe=7b8b964ce4) | Nov 29, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [0b050dca43](https://linux-hardware.org/?probe=0b050dca43) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a5669b915e](https://linux-hardware.org/?probe=a5669b915e) | Nov 25, 2020 |
| Dell          | 0K240Y A02                  | Desktop     | [6f8d2322b6](https://linux-hardware.org/?probe=6f8d2322b6) | Nov 25, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [f0cf2d64a6](https://linux-hardware.org/?probe=f0cf2d64a6) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | Notebook    | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [ed63cb31af](https://linux-hardware.org/?probe=ed63cb31af) | Nov 18, 2020 |
| HP            | 2B56                        | All in one  | [3db64c4252](https://linux-hardware.org/?probe=3db64c4252) | Nov 17, 2020 |
| HP            | 2B56                        | All in one  | [1eb0afe0ed](https://linux-hardware.org/?probe=1eb0afe0ed) | Nov 17, 2020 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a2ac4f643a](https://linux-hardware.org/?probe=a2ac4f643a) | Nov 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [ca8ffcb464](https://linux-hardware.org/?probe=ca8ffcb464) | Nov 15, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [f934cc994f](https://linux-hardware.org/?probe=f934cc994f) | Nov 14, 2020 |
| Acer          | Aspire E5-572G              | Notebook    | [aa4817a78d](https://linux-hardware.org/?probe=aa4817a78d) | Nov 12, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [7698cbedd0](https://linux-hardware.org/?probe=7698cbedd0) | Nov 12, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1df930d7e](https://linux-hardware.org/?probe=c1df930d7e) | Nov 10, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1b21b64248](https://linux-hardware.org/?probe=1b21b64248) | Nov 08, 2020 |
| Dell          | Inspiron 5370               | Notebook    | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [9f2d169081](https://linux-hardware.org/?probe=9f2d169081) | Nov 06, 2020 |
| Acer          | Aspire V3-772               | Notebook    | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| HP            | ProBook 6470b               | Notebook    | [18f5fab938](https://linux-hardware.org/?probe=18f5fab938) | Oct 31, 2020 |
| ASUSTek       | V222GA                      | All in one  | [6792dcd0de](https://linux-hardware.org/?probe=6792dcd0de) | Oct 30, 2020 |
| iEi           | B202 V1.0                   | Desktop     | [ad705b0098](https://linux-hardware.org/?probe=ad705b0098) | Oct 29, 2020 |
| Dell          | Vostro 3580                 | Notebook    | [a0e40c6f16](https://linux-hardware.org/?probe=a0e40c6f16) | Oct 29, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [a4497b52bb](https://linux-hardware.org/?probe=a4497b52bb) | Oct 28, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [4643cfe86d](https://linux-hardware.org/?probe=4643cfe86d) | Oct 27, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [da5ad20c60](https://linux-hardware.org/?probe=da5ad20c60) | Oct 27, 2020 |
| Dell          | Latitude 5480               | Notebook    | [4191db79b7](https://linux-hardware.org/?probe=4191db79b7) | Oct 25, 2020 |
| Toshiba       | Satellite S70-B             | Notebook    | [a6521e505a](https://linux-hardware.org/?probe=a6521e505a) | Oct 25, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [89f32e3856](https://linux-hardware.org/?probe=89f32e3856) | Oct 23, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [76852e9990](https://linux-hardware.org/?probe=76852e9990) | Oct 22, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [74b57e7887](https://linux-hardware.org/?probe=74b57e7887) | Oct 21, 2020 |
| Packard Be... | IMEDIA S2185                | Desktop     | [5fd02031d2](https://linux-hardware.org/?probe=5fd02031d2) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a1a02fe851](https://linux-hardware.org/?probe=a1a02fe851) | Oct 18, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [dd68c7b3f6](https://linux-hardware.org/?probe=dd68c7b3f6) | Oct 18, 2020 |
| Dell          | 0XHGV1 A00                  | Desktop     | [d1f3fe93be](https://linux-hardware.org/?probe=d1f3fe93be) | Oct 16, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [fdc8cb1b11](https://linux-hardware.org/?probe=fdc8cb1b11) | Oct 16, 2020 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [f5c8360ae3](https://linux-hardware.org/?probe=f5c8360ae3) | Oct 15, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f72e0309a](https://linux-hardware.org/?probe=3f72e0309a) | Oct 15, 2020 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [bfe71baced](https://linux-hardware.org/?probe=bfe71baced) | Oct 14, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [ba66ad5205](https://linux-hardware.org/?probe=ba66ad5205) | Oct 12, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [5e14548b50](https://linux-hardware.org/?probe=5e14548b50) | Oct 12, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [bbae413f9c](https://linux-hardware.org/?probe=bbae413f9c) | Oct 10, 2020 |
| ASUSTek       | K53U                        | Notebook    | [59444922e7](https://linux-hardware.org/?probe=59444922e7) | Oct 10, 2020 |
| ASUSTek       | K53U                        | Notebook    | [5c5b3815f7](https://linux-hardware.org/?probe=5c5b3815f7) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [25fb29514f](https://linux-hardware.org/?probe=25fb29514f) | Oct 10, 2020 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [61b3d8f426](https://linux-hardware.org/?probe=61b3d8f426) | Oct 09, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [b178beac46](https://linux-hardware.org/?probe=b178beac46) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [86c3c25832](https://linux-hardware.org/?probe=86c3c25832) | Oct 05, 2020 |
| ASUSTek       | P10S-V Series               | Desktop     | [ab381f976a](https://linux-hardware.org/?probe=ab381f976a) | Oct 04, 2020 |
| HP            | 250 G3                      | Notebook    | [ab75ccc4f8](https://linux-hardware.org/?probe=ab75ccc4f8) | Oct 02, 2020 |
| Dell          | Inspiron 3583               | Notebook    | [419cd76be1](https://linux-hardware.org/?probe=419cd76be1) | Oct 01, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [18199ffdaf](https://linux-hardware.org/?probe=18199ffdaf) | Sep 30, 2020 |
| Gigabyte      | P35-S3G                     | Desktop     | [c55cb88668](https://linux-hardware.org/?probe=c55cb88668) | Sep 30, 2020 |
| Dell          | G7 7588                     | Notebook    | [0d38edaf0c](https://linux-hardware.org/?probe=0d38edaf0c) | Sep 28, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [33020554c0](https://linux-hardware.org/?probe=33020554c0) | Sep 27, 2020 |
| Acer          | EG43M                       | Desktop     | [f70bf9f37f](https://linux-hardware.org/?probe=f70bf9f37f) | Sep 26, 2020 |
| Acer          | EG43M                       | Desktop     | [93fe9368c0](https://linux-hardware.org/?probe=93fe9368c0) | Sep 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [e330dd752b](https://linux-hardware.org/?probe=e330dd752b) | Sep 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [18afb6b15d](https://linux-hardware.org/?probe=18afb6b15d) | Sep 22, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [c078093e0f](https://linux-hardware.org/?probe=c078093e0f) | Sep 22, 2020 |
| HP            | Compaq tc4400 (RH489ES#A... | Notebook    | [c0305edfae](https://linux-hardware.org/?probe=c0305edfae) | Sep 20, 2020 |
| ASUSTek       | K50C                        | Notebook    | [d4e11f2289](https://linux-hardware.org/?probe=d4e11f2289) | Sep 18, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [db3c1d0348](https://linux-hardware.org/?probe=db3c1d0348) | Sep 13, 2020 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [7ab72b120c](https://linux-hardware.org/?probe=7ab72b120c) | Sep 12, 2020 |
| Acer          | Extensa 5630                | Notebook    | [9040e8e334](https://linux-hardware.org/?probe=9040e8e334) | Sep 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [a66f1b519a](https://linux-hardware.org/?probe=a66f1b519a) | Sep 10, 2020 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [fd2b790572](https://linux-hardware.org/?probe=fd2b790572) | Sep 09, 2020 |
| Shuttle       | FH81                        | Desktop     | [f7d3c868f1](https://linux-hardware.org/?probe=f7d3c868f1) | Sep 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| HP            | ENVY x360 m Convertible     | Convertible | [03ff5b116c](https://linux-hardware.org/?probe=03ff5b116c) | Sep 03, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [bc5ee009b9](https://linux-hardware.org/?probe=bc5ee009b9) | Aug 29, 2020 |
| Lenovo        | ThinkPad X250 20CLS2YH00    | Notebook    | [cee4231640](https://linux-hardware.org/?probe=cee4231640) | Aug 29, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [9820c3c8bd](https://linux-hardware.org/?probe=9820c3c8bd) | Aug 28, 2020 |
| HP            | 0AA4h                       | Desktop     | [e1d187b146](https://linux-hardware.org/?probe=e1d187b146) | Aug 24, 2020 |
| Dell          | Precision M4800             | Notebook    | [4765bc9ec2](https://linux-hardware.org/?probe=4765bc9ec2) | Aug 19, 2020 |
| Dell          | Precision M4800             | Notebook    | [eee5b97967](https://linux-hardware.org/?probe=eee5b97967) | Aug 19, 2020 |
| HP            | 250 G3                      | Notebook    | [ff5c3ce273](https://linux-hardware.org/?probe=ff5c3ce273) | Aug 19, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [bf7ae9d5bf](https://linux-hardware.org/?probe=bf7ae9d5bf) | Aug 19, 2020 |
| HP            | 250 G3                      | Notebook    | [01f2866b5c](https://linux-hardware.org/?probe=01f2866b5c) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [1619b6bb6c](https://linux-hardware.org/?probe=1619b6bb6c) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [65cf550e5a](https://linux-hardware.org/?probe=65cf550e5a) | Aug 16, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b636cd4fc2](https://linux-hardware.org/?probe=b636cd4fc2) | Aug 10, 2020 |
| Lenovo        | ThinkCentre M90p 5864BQ9    | Desktop     | [2f13897020](https://linux-hardware.org/?probe=2f13897020) | Aug 06, 2020 |
| HP            | 1632                        | Desktop     | [051549bbcd](https://linux-hardware.org/?probe=051549bbcd) | Aug 03, 2020 |
| HP            | 1496                        | Desktop     | [814a9396ee](https://linux-hardware.org/?probe=814a9396ee) | Aug 01, 2020 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [d6af935ba5](https://linux-hardware.org/?probe=d6af935ba5) | Jul 30, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [ec4e8d2f6b](https://linux-hardware.org/?probe=ec4e8d2f6b) | Jul 30, 2020 |
| ASRock        | ConRoe945PL-GLAN            | Desktop     | [006d3a68b4](https://linux-hardware.org/?probe=006d3a68b4) | Jul 30, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [18c07b157f](https://linux-hardware.org/?probe=18c07b157f) | Jul 29, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [8051286600](https://linux-hardware.org/?probe=8051286600) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [974c9ebd9c](https://linux-hardware.org/?probe=974c9ebd9c) | Jul 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [511636781f](https://linux-hardware.org/?probe=511636781f) | Jul 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [06120056c3](https://linux-hardware.org/?probe=06120056c3) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [2afa9387d5](https://linux-hardware.org/?probe=2afa9387d5) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [8ced06cd1f](https://linux-hardware.org/?probe=8ced06cd1f) | Jul 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8d593715c](https://linux-hardware.org/?probe=e8d593715c) | Jul 25, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [7b8022aa05](https://linux-hardware.org/?probe=7b8022aa05) | Jul 23, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [42fc06b0e4](https://linux-hardware.org/?probe=42fc06b0e4) | Jul 23, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | Desktop     | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [1de3848a94](https://linux-hardware.org/?probe=1de3848a94) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | Notebook    | [223cceb869](https://linux-hardware.org/?probe=223cceb869) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | Notebook    | [699033745c](https://linux-hardware.org/?probe=699033745c) | Jul 19, 2020 |
| Acer          | E5-575G                     | Notebook    | [9fb1e1bee4](https://linux-hardware.org/?probe=9fb1e1bee4) | Jul 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee5e7f9151](https://linux-hardware.org/?probe=ee5e7f9151) | Jul 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [968247c419](https://linux-hardware.org/?probe=968247c419) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2298274454](https://linux-hardware.org/?probe=2298274454) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c1fb882fc5](https://linux-hardware.org/?probe=c1fb882fc5) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2f5df8729a](https://linux-hardware.org/?probe=2f5df8729a) | Jul 17, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ac0d845ddb](https://linux-hardware.org/?probe=ac0d845ddb) | Jul 13, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [54f20878cf](https://linux-hardware.org/?probe=54f20878cf) | Jul 12, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7387ae682a](https://linux-hardware.org/?probe=7387ae682a) | Jul 10, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [46702d58d5](https://linux-hardware.org/?probe=46702d58d5) | Jul 04, 2020 |
| Lenovo        | ThinkPad T590 20N5S2BP00    | Notebook    | [16f6fb2756](https://linux-hardware.org/?probe=16f6fb2756) | Jul 02, 2020 |
| Fujitsu Si... | AMILO L Series              | Notebook    | [33762202ef](https://linux-hardware.org/?probe=33762202ef) | Jul 01, 2020 |
| MSI           | B150 GAMING M3              | Desktop     | [4e837b8686](https://linux-hardware.org/?probe=4e837b8686) | Jul 01, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [9b54e3f16c](https://linux-hardware.org/?probe=9b54e3f16c) | Jun 30, 2020 |
| ASUSTek       | P8H61-I LX R2.0/RM/SI       | Desktop     | [a5f5e5572b](https://linux-hardware.org/?probe=a5f5e5572b) | Jun 30, 2020 |
| Dell          | Latitude E6410              | Notebook    | [79c1af2581](https://linux-hardware.org/?probe=79c1af2581) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [078efbe676](https://linux-hardware.org/?probe=078efbe676) | Jun 29, 2020 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [a79843ff43](https://linux-hardware.org/?probe=a79843ff43) | Jun 27, 2020 |
| Acer          | Swift SF314-57G             | Notebook    | [9bd6123d76](https://linux-hardware.org/?probe=9bd6123d76) | Jun 25, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [5d93931a70](https://linux-hardware.org/?probe=5d93931a70) | Jun 21, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d318a0db0](https://linux-hardware.org/?probe=6d318a0db0) | Jun 21, 2020 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f2f35bedba](https://linux-hardware.org/?probe=f2f35bedba) | Jun 20, 2020 |
| Toshiba       | Satellite C55-A-1HL         | Notebook    | [c6d6bb3ba1](https://linux-hardware.org/?probe=c6d6bb3ba1) | Jun 18, 2020 |
| Toshiba       | Satellite C55-A-1HL         | Notebook    | [d16857f500](https://linux-hardware.org/?probe=d16857f500) | Jun 17, 2020 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [22ca9e31e5](https://linux-hardware.org/?probe=22ca9e31e5) | Jun 15, 2020 |
| ASRock        | H110M-HDV                   | Desktop     | [9a04c60269](https://linux-hardware.org/?probe=9a04c60269) | Jun 15, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [1b58de62cc](https://linux-hardware.org/?probe=1b58de62cc) | Jun 14, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [5a279c96a5](https://linux-hardware.org/?probe=5a279c96a5) | Jun 13, 2020 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [7a3bd1d810](https://linux-hardware.org/?probe=7a3bd1d810) | Jun 10, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1e9b7bd7d0](https://linux-hardware.org/?probe=1e9b7bd7d0) | Jun 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [65f523b6f2](https://linux-hardware.org/?probe=65f523b6f2) | Jun 06, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [c8ddcb0ec8](https://linux-hardware.org/?probe=c8ddcb0ec8) | Jun 06, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d23bc12452](https://linux-hardware.org/?probe=d23bc12452) | Jun 04, 2020 |
| ASRock        | 970M Pro3                   | Desktop     | [f40c51e426](https://linux-hardware.org/?probe=f40c51e426) | Jun 03, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [efa59eef1c](https://linux-hardware.org/?probe=efa59eef1c) | Jun 01, 2020 |
| HP            | 250 G3                      | Notebook    | [99be1919b2](https://linux-hardware.org/?probe=99be1919b2) | Jun 01, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [8eb9fa72de](https://linux-hardware.org/?probe=8eb9fa72de) | May 31, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [6860a03dd0](https://linux-hardware.org/?probe=6860a03dd0) | May 31, 2020 |
| HP            | 250 G3                      | Notebook    | [a4e1d1f904](https://linux-hardware.org/?probe=a4e1d1f904) | May 29, 2020 |
| Lenovo        | ThinkPad T495 20NJ0010BM    | Notebook    | [6974ca5761](https://linux-hardware.org/?probe=6974ca5761) | May 29, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [edcc0b8c05](https://linux-hardware.org/?probe=edcc0b8c05) | May 29, 2020 |
| ASUSTek       | X540LJ                      | Notebook    | [67a3981fe5](https://linux-hardware.org/?probe=67a3981fe5) | May 27, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | Desktop     | [9c341d7259](https://linux-hardware.org/?probe=9c341d7259) | May 25, 2020 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [5bd26cbc33](https://linux-hardware.org/?probe=5bd26cbc33) | May 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| ASUSTek       | X705UNR                     | Notebook    | [015957a390](https://linux-hardware.org/?probe=015957a390) | May 22, 2020 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [34d65fc5b5](https://linux-hardware.org/?probe=34d65fc5b5) | May 22, 2020 |
| HP            | ProBook 6460b               | Notebook    | [babf988605](https://linux-hardware.org/?probe=babf988605) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| HP            | 1496                        | Desktop     | [64b345823f](https://linux-hardware.org/?probe=64b345823f) | May 18, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | Desktop     | [5d67f4aace](https://linux-hardware.org/?probe=5d67f4aace) | May 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [33722345b4](https://linux-hardware.org/?probe=33722345b4) | May 13, 2020 |
| HP            | 255 G2                      | Notebook    | [ad9ef87735](https://linux-hardware.org/?probe=ad9ef87735) | May 13, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [f27a7b8301](https://linux-hardware.org/?probe=f27a7b8301) | May 13, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [88fc8f3bc8](https://linux-hardware.org/?probe=88fc8f3bc8) | May 13, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d4a5246eaa](https://linux-hardware.org/?probe=d4a5246eaa) | May 12, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [2dec87937c](https://linux-hardware.org/?probe=2dec87937c) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [715f4fa65b](https://linux-hardware.org/?probe=715f4fa65b) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [96cd96c818](https://linux-hardware.org/?probe=96cd96c818) | May 12, 2020 |
| HP            | ProBook 4710s               | Notebook    | [b2680d0881](https://linux-hardware.org/?probe=b2680d0881) | May 11, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [6da190e95d](https://linux-hardware.org/?probe=6da190e95d) | May 10, 2020 |
| HP            | 255 G2                      | Notebook    | [ee5dcad518](https://linux-hardware.org/?probe=ee5dcad518) | May 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| Dell          | Latitude 7490               | Notebook    | [94b949eb90](https://linux-hardware.org/?probe=94b949eb90) | May 08, 2020 |
| Acer          | E5-575G                     | Notebook    | [4de3c815fd](https://linux-hardware.org/?probe=4de3c815fd) | May 08, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [3b379abf6a](https://linux-hardware.org/?probe=3b379abf6a) | May 07, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| HP            | 255 G2                      | Notebook    | [162f37494e](https://linux-hardware.org/?probe=162f37494e) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ea793cbae5](https://linux-hardware.org/?probe=ea793cbae5) | May 06, 2020 |
| Dell          | Latitude E4300              | Notebook    | [8b26d2727c](https://linux-hardware.org/?probe=8b26d2727c) | May 06, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [cbcdbbc816](https://linux-hardware.org/?probe=cbcdbbc816) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [72e18e38ce](https://linux-hardware.org/?probe=72e18e38ce) | May 04, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [35d925dbae](https://linux-hardware.org/?probe=35d925dbae) | May 04, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [02c7c61130](https://linux-hardware.org/?probe=02c7c61130) | May 03, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [d987f6c242](https://linux-hardware.org/?probe=d987f6c242) | May 03, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [029da6ffcc](https://linux-hardware.org/?probe=029da6ffcc) | May 03, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | Notebook    | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [c3b3575e58](https://linux-hardware.org/?probe=c3b3575e58) | May 02, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [77202c9853](https://linux-hardware.org/?probe=77202c9853) | May 02, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [f74dab71c3](https://linux-hardware.org/?probe=f74dab71c3) | May 01, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [7ac5247653](https://linux-hardware.org/?probe=7ac5247653) | May 01, 2020 |
| MSI           | MS-7368                     | Desktop     | [090e6cd15c](https://linux-hardware.org/?probe=090e6cd15c) | May 01, 2020 |
| MSI           | MS-7368                     | Desktop     | [308c2e01f6](https://linux-hardware.org/?probe=308c2e01f6) | Apr 30, 2020 |
| ASUSTek       | M2N68-CM                    | Desktop     | [6f787e35a1](https://linux-hardware.org/?probe=6f787e35a1) | Apr 27, 2020 |
| Acer          | Aspire 3830G                | Notebook    | [1af95987d0](https://linux-hardware.org/?probe=1af95987d0) | Apr 26, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7dceeca2dd](https://linux-hardware.org/?probe=7dceeca2dd) | Apr 24, 2020 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [2dde18f51f](https://linux-hardware.org/?probe=2dde18f51f) | Apr 24, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [2d93805421](https://linux-hardware.org/?probe=2d93805421) | Apr 23, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [155a39180a](https://linux-hardware.org/?probe=155a39180a) | Apr 23, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [28fa6e8b6e](https://linux-hardware.org/?probe=28fa6e8b6e) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [73f401be06](https://linux-hardware.org/?probe=73f401be06) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [562403e85f](https://linux-hardware.org/?probe=562403e85f) | Apr 21, 2020 |
| Gigabyte      | P85-D3                      | Desktop     | [5972095107](https://linux-hardware.org/?probe=5972095107) | Apr 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee479d0e5d](https://linux-hardware.org/?probe=ee479d0e5d) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [a78b041d0c](https://linux-hardware.org/?probe=a78b041d0c) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [fbfdc3b5e3](https://linux-hardware.org/?probe=fbfdc3b5e3) | Apr 20, 2020 |
| Sony          | VPCEB4L1E                   | Notebook    | [f1a3807b60](https://linux-hardware.org/?probe=f1a3807b60) | Apr 20, 2020 |
| Compal        | HEL80I                      | Notebook    | [41fd098e10](https://linux-hardware.org/?probe=41fd098e10) | Apr 20, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [00cedd86e4](https://linux-hardware.org/?probe=00cedd86e4) | Apr 19, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6b8e555d43](https://linux-hardware.org/?probe=6b8e555d43) | Apr 18, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [f3b92c302c](https://linux-hardware.org/?probe=f3b92c302c) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [d1e3e7d629](https://linux-hardware.org/?probe=d1e3e7d629) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [a9b4abdd56](https://linux-hardware.org/?probe=a9b4abdd56) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [43f93a43d6](https://linux-hardware.org/?probe=43f93a43d6) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [20b4b0a6ad](https://linux-hardware.org/?probe=20b4b0a6ad) | Apr 16, 2020 |
| Dell          | 08NPPY A00                  | Desktop     | [895a4ce7cb](https://linux-hardware.org/?probe=895a4ce7cb) | Apr 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [02d576419f](https://linux-hardware.org/?probe=02d576419f) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5fc32fd27b](https://linux-hardware.org/?probe=5fc32fd27b) | Apr 12, 2020 |
| Shuttle       | FH81                        | Desktop     | [61209bcee3](https://linux-hardware.org/?probe=61209bcee3) | Apr 11, 2020 |
| ASRock        | 890GX Extreme3              | Desktop     | [2f70e1ae2c](https://linux-hardware.org/?probe=2f70e1ae2c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [53b2f1863a](https://linux-hardware.org/?probe=53b2f1863a) | Apr 07, 2020 |
| ASRock        | 970 Extreme3                | Desktop     | [679cdbade2](https://linux-hardware.org/?probe=679cdbade2) | Apr 05, 2020 |
| HP            | 0A64h                       | Desktop     | [79aa6d6301](https://linux-hardware.org/?probe=79aa6d6301) | Apr 05, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [6b0efa548b](https://linux-hardware.org/?probe=6b0efa548b) | Apr 04, 2020 |
| ASUSTek       | P5K                         | Desktop     | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [a7f7938a12](https://linux-hardware.org/?probe=a7f7938a12) | Apr 02, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [4db785101b](https://linux-hardware.org/?probe=4db785101b) | Apr 01, 2020 |
| HP            | ProBook 4540s               | Notebook    | [e3c52f3d96](https://linux-hardware.org/?probe=e3c52f3d96) | Apr 01, 2020 |
| Dell          | 0DR845                      | Desktop     | [c1582b3202](https://linux-hardware.org/?probe=c1582b3202) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [cbc70bfce5](https://linux-hardware.org/?probe=cbc70bfce5) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [d018206f33](https://linux-hardware.org/?probe=d018206f33) | Mar 31, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [5038965b3b](https://linux-hardware.org/?probe=5038965b3b) | Mar 30, 2020 |
| HP            | ProBook 4540s               | Notebook    | [6b9b373a1f](https://linux-hardware.org/?probe=6b9b373a1f) | Mar 30, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [99865fe49f](https://linux-hardware.org/?probe=99865fe49f) | Mar 29, 2020 |
| ASUSTek       | P5K SE                      | Desktop     | [8492263fc0](https://linux-hardware.org/?probe=8492263fc0) | Mar 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c7eda36111](https://linux-hardware.org/?probe=c7eda36111) | Mar 28, 2020 |
| Acer          | Predator G3-572             | Notebook    | [9434c59ae1](https://linux-hardware.org/?probe=9434c59ae1) | Mar 28, 2020 |
| Acer          | Predator G3-572             | Notebook    | [11828122f2](https://linux-hardware.org/?probe=11828122f2) | Mar 28, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | Notebook    | [edf4388f6a](https://linux-hardware.org/?probe=edf4388f6a) | Mar 26, 2020 |
| ASUSTek       | P5K SE                      | Desktop     | [fd766dda01](https://linux-hardware.org/?probe=fd766dda01) | Mar 26, 2020 |
| HP            | 620                         | Notebook    | [633afcbbef](https://linux-hardware.org/?probe=633afcbbef) | Mar 25, 2020 |
| HP            | 620                         | Notebook    | [8487590fa2](https://linux-hardware.org/?probe=8487590fa2) | Mar 25, 2020 |
| ASRock        | G41M-S3                     | Desktop     | [19c0625a28](https://linux-hardware.org/?probe=19c0625a28) | Mar 24, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c63e1ec4fd](https://linux-hardware.org/?probe=c63e1ec4fd) | Mar 23, 2020 |
| ASUSTek       | M4A3000E                    | Desktop     | [76ec7cf71b](https://linux-hardware.org/?probe=76ec7cf71b) | Mar 23, 2020 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [0d2e81fb9b](https://linux-hardware.org/?probe=0d2e81fb9b) | Mar 20, 2020 |
| ASUSTek       | P5K                         | Desktop     | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | Desktop     | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [b343a21e42](https://linux-hardware.org/?probe=b343a21e42) | Mar 17, 2020 |
| Lenovo        | ThinkPad T470p 20J6S0A30... | Notebook    | [b02f5ffeeb](https://linux-hardware.org/?probe=b02f5ffeeb) | Mar 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [14544480a5](https://linux-hardware.org/?probe=14544480a5) | Mar 16, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 111       | 12.31%  |
| Ubuntu 18.04                 | 78        | 8.65%   |
| OpenMandriva 4.2             | 29        | 3.22%   |
| Ubuntu 22.04                 | 26        | 2.88%   |
| Debian 11                    | 22        | 2.44%   |
| OpenMandriva 4.3             | 19        | 2.11%   |
| ROSA R11                     | 18        | 2%      |
| Manjaro                      | 17        | 1.88%   |
| Linux Mint 20.1              | 17        | 1.88%   |
| KDE neon 20.04               | 17        | 1.88%   |
| ROSA R10                     | 16        | 1.77%   |
| Arch                         | 16        | 1.77%   |
| Linux Mint 20.3              | 14        | 1.55%   |
| Linux Mint 19.3              | 14        | 1.55%   |
| Ubuntu 19.04                 | 13        | 1.44%   |
| Zorin 15                     | 12        | 1.33%   |
| Xubuntu 18.04                | 12        | 1.33%   |
| Linux Mint 20.2              | 12        | 1.33%   |
| Linux Mint 20                | 12        | 1.33%   |
| Kubuntu 20.04                | 12        | 1.33%   |
| Ubuntu 19.10                 | 11        | 1.22%   |
| ArcoLinux Rolling            | 11        | 1.22%   |
| Xubuntu 20.04                | 10        | 1.11%   |
| Pop!_OS 20.10                | 10        | 1.11%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 1.11%   |
| Fedora 33                    | 10        | 1.11%   |
| Zorin 16                     | 9         | 1%      |
| Ubuntu 20.10                 | 9         | 1%      |
| LMDE 4                       | 9         | 1%      |
| Ubuntu 16.04                 | 7         | 0.78%   |
| ROSA R9                      | 7         | 0.78%   |
| Pop!_OS 20.04                | 7         | 0.78%   |
| Fedora 36                    | 7         | 0.78%   |
| Fedora 35                    | 7         | 0.78%   |
| Fedora 34                    | 7         | 0.78%   |
| Fedora 31                    | 7         | 0.78%   |
| Ubuntu 22.10                 | 6         | 0.67%   |
| Ubuntu 21.10                 | 6         | 0.67%   |
| ROSA R11.1                   | 6         | 0.67%   |
| Pop!_OS 21.10                | 6         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 259       | 31.32%  |
| Linux Mint    | 72        | 8.71%   |
| OpenMandriva  | 53        | 6.41%   |
| ROSA          | 47        | 5.68%   |
| Manjaro       | 38        | 4.59%   |
| Fedora        | 37        | 4.47%   |
| Debian        | 33        | 3.99%   |
| Pop!_OS       | 31        | 3.75%   |
| Endless       | 27        | 3.26%   |
| Xubuntu       | 25        | 3.02%   |
| KDE neon      | 23        | 2.78%   |
| Zorin         | 21        | 2.54%   |
| Arch          | 21        | 2.54%   |
| Kubuntu       | 19        | 2.3%    |
| ArcoLinux     | 13        | 1.57%   |
| Kali          | 12        | 1.45%   |
| Clear Linux   | 12        | 1.45%   |
| Ubuntu Unity  | 11        | 1.33%   |
| openSUSE      | 11        | 1.33%   |
| LMDE          | 9         | 1.09%   |
| Lubuntu       | 7         | 0.85%   |
| CentOS        | 7         | 0.85%   |
| Elementary    | 5         | 0.6%    |
| Artix         | 4         | 0.48%   |
| Void Linux    | 3         | 0.36%   |
| Ubuntu MATE   | 3         | 0.36%   |
| Gentoo        | 3         | 0.36%   |
| Parrot        | 2         | 0.24%   |
| Novos         | 2         | 0.24%   |
| EndeavourOS   | 2         | 0.24%   |
| Ubuntu Studio | 1         | 0.12%   |
| Ubuntu Budgie | 1         | 0.12%   |
| Slackware     | 1         | 0.12%   |
| RHEL          | 1         | 0.12%   |
| Q4OS          | 1         | 0.12%   |
| PureOS        | 1         | 0.12%   |
| Peppermint    | 1         | 0.12%   |
| Oracle Linux  | 1         | 0.12%   |
| MX            | 1         | 0.12%   |
| Mageia        | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 29        | 2.93%   |
| 5.16.7-desktop-1omv4003         | 19        | 1.92%   |
| 5.4.0-42-generic                | 17        | 1.72%   |
| 5.4.0-58-generic                | 13        | 1.31%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 13        | 1.31%   |
| 5.3.0-40-generic                | 10        | 1.01%   |
| 5.9.16-1-MANJARO                | 8         | 0.81%   |
| 5.4.0-26-generic                | 8         | 0.81%   |
| 5.4.0-48-generic                | 7         | 0.71%   |
| 5.4.0-29-generic                | 7         | 0.71%   |
| 5.3.0-28-generic                | 7         | 0.71%   |
| 5.10.0-8-amd64                  | 7         | 0.71%   |
| 5.0.0-37-generic                | 7         | 0.71%   |
| 5.8.0-14-generic                | 6         | 0.61%   |
| 5.4.0-65-generic                | 6         | 0.61%   |
| 5.4.0-56-generic                | 6         | 0.61%   |
| 5.4.0-40-generic                | 6         | 0.61%   |
| 5.3.0-46-generic                | 6         | 0.61%   |
| 5.3.0-42-generic                | 6         | 0.61%   |
| 5.11.0-37-generic               | 6         | 0.61%   |
| 5.11.0-27-generic               | 6         | 0.61%   |
| 5.0.0-23-generic                | 6         | 0.61%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 6         | 0.61%   |
| 4.15.0-20-generic               | 6         | 0.61%   |
| 5.8.0-7642-generic              | 5         | 0.51%   |
| 5.8.0-43-generic                | 5         | 0.51%   |
| 5.4.0-91-generic                | 5         | 0.51%   |
| 5.4.0-77-generic                | 5         | 0.51%   |
| 5.4.0-67-generic                | 5         | 0.51%   |
| 5.4.0-19-generic                | 5         | 0.51%   |
| 5.19.0-23-generic               | 5         | 0.51%   |
| 5.15.0-46-generic               | 5         | 0.51%   |
| 5.13.0-28-generic               | 5         | 0.51%   |
| 5.0.0-32-generic                | 5         | 0.51%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 5         | 0.51%   |
| 4.18.0-25-generic               | 5         | 0.51%   |
| 5.8.0-40-generic                | 4         | 0.4%    |
| 5.4.0-90-generic                | 4         | 0.4%    |
| 5.4.0-81-generic                | 4         | 0.4%    |
| 5.4.0-74-generic                | 4         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 164       | 17.56%  |
| 4.15.0  | 79        | 8.46%   |
| 5.8.0   | 53        | 5.67%   |
| 5.3.0   | 49        | 5.25%   |
| 5.15.0  | 44        | 4.71%   |
| 5.11.0  | 39        | 4.18%   |
| 5.0.0   | 37        | 3.96%   |
| 5.13.0  | 33        | 3.53%   |
| 5.10.14 | 30        | 3.21%   |
| 5.10.0  | 26        | 2.78%   |
| 4.18.0  | 23        | 2.46%   |
| 5.16.7  | 19        | 2.03%   |
| 4.19.0  | 13        | 1.39%   |
| 5.9.16  | 11        | 1.18%   |
| 5.19.0  | 11        | 1.18%   |
| 4.9.20  | 9         | 0.96%   |
| 5.17.5  | 6         | 0.64%   |
| 4.9.60  | 6         | 0.64%   |
| 4.4.0   | 6         | 0.64%   |
| 5.8.18  | 5         | 0.54%   |
| 5.18.0  | 5         | 0.54%   |
| 4.9.124 | 5         | 0.54%   |
| 5.8.11  | 4         | 0.43%   |
| 5.6.8   | 4         | 0.43%   |
| 5.6.0   | 4         | 0.43%   |
| 5.16.0  | 4         | 0.43%   |
| 5.14.0  | 4         | 0.43%   |
| 5.12.4  | 4         | 0.43%   |
| 5.11.12 | 4         | 0.43%   |
| 5.7.6   | 3         | 0.32%   |
| 5.7.19  | 3         | 0.32%   |
| 5.3.16  | 3         | 0.32%   |
| 5.17.9  | 3         | 0.32%   |
| 5.17.6  | 3         | 0.32%   |
| 5.17.11 | 3         | 0.32%   |
| 5.16.15 | 3         | 0.32%   |
| 5.16.11 | 3         | 0.32%   |
| 5.15.8  | 3         | 0.32%   |
| 5.12.14 | 3         | 0.32%   |
| 5.10.74 | 3         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 174       | 19.1%   |
| 5.10    | 79        | 8.67%   |
| 4.15    | 79        | 8.67%   |
| 5.8     | 66        | 7.24%   |
| 5.15    | 66        | 7.24%   |
| 5.3     | 58        | 6.37%   |
| 5.11    | 51        | 5.6%    |
| 5.0     | 40        | 4.39%   |
| 5.13    | 39        | 4.28%   |
| 5.16    | 37        | 4.06%   |
| 4.9     | 26        | 2.85%   |
| 4.18    | 24        | 2.63%   |
| 5.19    | 19        | 2.09%   |
| 5.17    | 18        | 1.98%   |
| 4.19    | 18        | 1.98%   |
| 5.9     | 17        | 1.87%   |
| 5.6     | 16        | 1.76%   |
| 5.7     | 12        | 1.32%   |
| 5.12    | 11        | 1.21%   |
| 5.18    | 10        | 1.1%    |
| 5.14    | 10        | 1.1%    |
| 6.0     | 7         | 0.77%   |
| 5.5     | 7         | 0.77%   |
| 4.4     | 6         | 0.66%   |
| 5.2     | 5         | 0.55%   |
| 4.1     | 4         | 0.44%   |
| 5.1     | 3         | 0.33%   |
| 3.10    | 3         | 0.33%   |
| 4.7     | 1         | 0.11%   |
| 4.20    | 1         | 0.11%   |
| 4.13    | 1         | 0.11%   |
| 4.10    | 1         | 0.11%   |
| 3.13    | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 762       | 96.46%  |
| i686   | 28        | 3.54%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 306       | 36.26%  |
| KDE5             | 136       | 16.11%  |
| Unknown          | 122       | 14.45%  |
| XFCE             | 78        | 9.24%   |
| X-Cinnamon       | 54        | 6.4%    |
| KDE4             | 33        | 3.91%   |
| KDE              | 28        | 3.32%   |
| MATE             | 23        | 2.73%   |
| Cinnamon         | 15        | 1.78%   |
| Unity            | 11        | 1.3%    |
| LXQt             | 7         | 0.83%   |
| Pantheon         | 5         | 0.59%   |
| GNOME Flashback  | 5         | 0.59%   |
| i3               | 3         | 0.36%   |
| Budgie           | 3         | 0.36%   |
| bspwm            | 3         | 0.36%   |
| xmonad           | 2         | 0.24%   |
| lightdm-xsession | 2         | 0.24%   |
| Deepin           | 2         | 0.24%   |
| trinity          | 1         | 0.12%   |
| qtile            | 1         | 0.12%   |
| LXDE             | 1         | 0.12%   |
| GNOME Classic    | 1         | 0.12%   |
| DWM              | 1         | 0.12%   |
| awesome          | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 673       | 82.27%  |
| Wayland | 71        | 8.68%   |
| Unknown | 64        | 7.82%   |
| Tty     | 10        | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 439       | 53.21%  |
| SDDM    | 133       | 16.12%  |
| LightDM | 68        | 8.24%   |
| GDM     | 66        | 8%      |
| GDM3    | 51        | 6.18%   |
| TDM     | 33        | 4%      |
| KDM     | 32        | 3.88%   |
| XDM     | 2         | 0.24%   |
| MDM     | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 476       | 57.91%  |
| bg_BG   | 152       | 18.49%  |
| Unknown | 143       | 17.4%   |
| en_GB   | 19        | 2.31%   |
| C       | 14        | 1.7%    |
| de_DE   | 6         | 0.73%   |
| ru_RU   | 5         | 0.61%   |
| POSIX   | 1         | 0.12%   |
| it_IT   | 1         | 0.12%   |
| fr_FR   | 1         | 0.12%   |
| en_DK   | 1         | 0.12%   |
| en_CA   | 1         | 0.12%   |
| Default | 1         | 0.12%   |
| C.UTF8  | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 478       | 59.01%  |
| EFI  | 332       | 40.99%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 624       | 76.56%  |
| Overlay | 61        | 7.48%   |
| Unknown | 56        | 6.87%   |
| Btrfs   | 42        | 5.15%   |
| Xfs     | 15        | 1.84%   |
| Zfs     | 6         | 0.74%   |
| Tmpfs   | 3         | 0.37%   |
| Ext3    | 3         | 0.37%   |
| Ext2    | 3         | 0.37%   |
| Jfs     | 1         | 0.12%   |
| F2fs    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 471       | 58.08%  |
| GPT     | 227       | 27.99%  |
| MBR     | 113       | 13.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 687       | 85.02%  |
| Yes       | 121       | 14.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 554       | 68.99%  |
| Yes       | 249       | 31.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 146       | 18.53%  |
| ASUSTek Computer    | 141       | 17.89%  |
| Hewlett-Packard     | 113       | 14.34%  |
| Dell                | 95        | 12.06%  |
| ASRock              | 57        | 7.23%   |
| Acer                | 53        | 6.73%   |
| Gigabyte Technology | 44        | 5.58%   |
| Toshiba             | 29        | 3.68%   |
| MSI                 | 26        | 3.3%    |
| Fujitsu             | 14        | 1.78%   |
| Intel               | 9         | 1.14%   |
| Apple               | 8         | 1.02%   |
| Fujitsu Siemens     | 6         | 0.76%   |
| Foxconn             | 5         | 0.63%   |
| Samsung Electronics | 4         | 0.51%   |
| AMI                 | 4         | 0.51%   |
| Unknown             | 4         | 0.51%   |
| Pegatron            | 3         | 0.38%   |
| Packard Bell        | 3         | 0.38%   |
| Wibtek              | 2         | 0.25%   |
| TUXEDO              | 2         | 0.25%   |
| Sony                | 2         | 0.25%   |
| Medion              | 2         | 0.25%   |
| HUAWEI              | 2         | 0.25%   |
| Thecus              | 1         | 0.13%   |
| Supermicro          | 1         | 0.13%   |
| Shuttle             | 1         | 0.13%   |
| Seco                | 1         | 0.13%   |
| Razer               | 1         | 0.13%   |
| Notebook            | 1         | 0.13%   |
| MiTAC               | 1         | 0.13%   |
| LG Electronics      | 1         | 0.13%   |
| iEi                 | 1         | 0.13%   |
| IBM                 | 1         | 0.13%   |
| ECS                 | 1         | 0.13%   |
| Cube                | 1         | 0.13%   |
| Compal              | 1         | 0.13%   |
| BESSTAR Tech        | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 8         | 1.02%   |
| ASUS All Series                            | 5         | 0.63%   |
| Lenovo H520S 2561                          | 4         | 0.51%   |
| Lenovo G500 20236                          | 4         | 0.51%   |
| HP ProBook 4540s                           | 4         | 0.51%   |
| HP ProBook 450 G0                          | 3         | 0.38%   |
| Dell Latitude E6410                        | 3         | 0.38%   |
| Dell Inspiron N5110                        | 3         | 0.38%   |
| ASUS X541NA                                | 3         | 0.38%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.38%   |
| ASUS N551VW                                | 3         | 0.38%   |
| ASRock Z97 Anniversary                     | 3         | 0.38%   |
| Acer Aspire 5738                           | 3         | 0.38%   |
| Wibtek H61-M HDMI2                         | 2         | 0.25%   |
| Toshiba Satellite L300                     | 2         | 0.25%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.25%   |
| Toshiba Satellite A200                     | 2         | 0.25%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.25%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.25%   |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.25%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.25%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.25%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.25%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.25%   |
| Lenovo ThinkPad T14 Gen 1 20S0000NBM       | 2         | 0.25%   |
| Lenovo ThinkPad L590 20Q700AWBM            | 2         | 0.25%   |
| Lenovo ThinkPad E480 20KN005CBM            | 2         | 0.25%   |
| Lenovo ThinkBook 13s-IML 20RR              | 2         | 0.25%   |
| Lenovo Legion Y740-17IRHg 81UJ             | 2         | 0.25%   |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.25%   |
| Lenovo IdeaPad Y510P 20217                 | 2         | 0.25%   |
| Lenovo IdeaPad Y500 20193                  | 2         | 0.25%   |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.25%   |
| Lenovo H520e 10159                         | 2         | 0.25%   |
| Lenovo G50-80 80E5                         | 2         | 0.25%   |
| HP ProBook 6470b                           | 2         | 0.25%   |
| HP ProBook 455 G8 Notebook PC              | 2         | 0.25%   |
| HP ProBook 450 G8 Notebook PC              | 2         | 0.25%   |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.25%   |
| HP Pavilion Gaming Laptop 17-cd0xxx        | 2         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 67        | 8.5%    |
| Acer Aspire           | 35        | 4.44%   |
| Dell Latitude         | 30        | 3.81%   |
| Dell Inspiron         | 26        | 3.3%    |
| Lenovo IdeaPad        | 24        | 3.05%   |
| HP ProBook            | 24        | 3.05%   |
| Toshiba Satellite     | 23        | 2.92%   |
| HP Pavilion           | 21        | 2.66%   |
| HP Compaq             | 20        | 2.54%   |
| HP EliteBook          | 19        | 2.41%   |
| ASUS VivoBook         | 15        | 1.9%    |
| ASUS PRIME            | 11        | 1.4%    |
| Dell Vostro           | 10        | 1.27%   |
| Dell OptiPlex         | 9         | 1.14%   |
| Fujitsu ESPRIMO       | 8         | 1.02%   |
| ASUS ROG              | 8         | 1.02%   |
| Unknown               | 8         | 1.02%   |
| Lenovo ThinkCentre    | 7         | 0.89%   |
| Lenovo Legion         | 7         | 0.89%   |
| Dell Precision        | 7         | 0.89%   |
| Lenovo Yoga           | 5         | 0.63%   |
| HP Laptop             | 5         | 0.63%   |
| Dell XPS              | 5         | 0.63%   |
| ASUS All              | 5         | 0.63%   |
| MSI Modern            | 4         | 0.51%   |
| Lenovo ThinkBook      | 4         | 0.51%   |
| Lenovo H520S          | 4         | 0.51%   |
| Lenovo G500           | 4         | 0.51%   |
| HP 250                | 4         | 0.51%   |
| ASUS TUF              | 4         | 0.51%   |
| ASUS P5K              | 4         | 0.51%   |
| Acer Predator         | 4         | 0.51%   |
| Acer Nitro            | 4         | 0.51%   |
| MSI GF63              | 3         | 0.38%   |
| Gigabyte X570         | 3         | 0.38%   |
| Fujitsu Siemens AMILO | 3         | 0.38%   |
| Fujitsu LIFEBOOK      | 3         | 0.38%   |
| Dell Studio           | 3         | 0.38%   |
| ASUS ZenBook          | 3         | 0.38%   |
| ASUS X541NA           | 3         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 72        | 9.14%   |
| 2012 | 70        | 8.88%   |
| 2019 | 69        | 8.76%   |
| 2013 | 65        | 8.25%   |
| 2017 | 62        | 7.87%   |
| 2018 | 60        | 7.61%   |
| 2020 | 57        | 7.23%   |
| 2014 | 52        | 6.6%    |
| 2015 | 49        | 6.22%   |
| 2010 | 46        | 5.84%   |
| 2008 | 42        | 5.33%   |
| 2021 | 32        | 4.06%   |
| 2009 | 32        | 4.06%   |
| 2007 | 28        | 3.55%   |
| 2016 | 26        | 3.3%    |
| 2006 | 13        | 1.65%   |
| 2022 | 8         | 1.02%   |
| 2005 | 3         | 0.38%   |
| 2004 | 2         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 479       | 60.79%  |
| Desktop     | 288       | 36.55%  |
| Convertible | 8         | 1.02%   |
| Mini pc     | 7         | 0.89%   |
| All in one  | 4         | 0.51%   |
| Tablet      | 2         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 751       | 94.94%  |
| Enabled  | 40        | 5.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 787       | 99.87%  |
| Yes  | 1         | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 208       | 25.62%  |
| 3.01-4.0    | 177       | 21.8%   |
| 8.01-16.0   | 153       | 18.84%  |
| 16.01-24.0  | 127       | 15.64%  |
| 32.01-64.0  | 62        | 7.64%   |
| 1.01-2.0    | 32        | 3.94%   |
| 2.01-3.0    | 20        | 2.46%   |
| 24.01-32.0  | 16        | 1.97%   |
| 64.01-256.0 | 13        | 1.6%    |
| 0.51-1.0    | 4         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 312       | 34.51%  |
| 2.01-3.0   | 242       | 26.77%  |
| 4.01-8.0   | 126       | 13.94%  |
| 3.01-4.0   | 113       | 12.5%   |
| 0.51-1.0   | 71        | 7.85%   |
| 8.01-16.0  | 30        | 3.32%   |
| 0.01-0.5   | 6         | 0.66%   |
| 16.01-24.0 | 2         | 0.22%   |
| 24.01-32.0 | 1         | 0.11%   |
| Unknown    | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 499       | 61.38%  |
| 2      | 216       | 26.57%  |
| 3      | 48        | 5.9%    |
| 4      | 16        | 1.97%   |
| 5      | 13        | 1.6%    |
| 6      | 8         | 0.98%   |
| 0      | 7         | 0.86%   |
| 8      | 2         | 0.25%   |
| 7      | 2         | 0.25%   |
| 11     | 1         | 0.12%   |
| 9      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 448       | 55.93%  |
| Yes       | 353       | 44.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 719       | 91.01%  |
| No        | 71        | 8.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 569       | 71.75%  |
| No        | 224       | 28.25%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 446       | 55.61%  |
| No        | 356       | 44.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Bulgaria | 788       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sofia          | 416       | 50.61%  |
| Varna          | 68        | 8.27%   |
| Plovdiv        | 52        | 6.33%   |
| Burgas         | 31        | 3.77%   |
| Stara Zagora   | 22        | 2.68%   |
| Rousse         | 14        | 1.7%    |
| Pernik         | 14        | 1.7%    |
| Pleven         | 11        | 1.34%   |
| Yambol         | 10        | 1.22%   |
| Veliko Tarnovo | 10        | 1.22%   |
| Haskovo        | 9         | 1.09%   |
| Sliven         | 8         | 0.97%   |
| Kazanlak       | 8         | 0.97%   |
| Shumen         | 7         | 0.85%   |
| Dobrich        | 7         | 0.85%   |
| Asenovgrad     | 6         | 0.73%   |
| Vidin          | 4         | 0.49%   |
| Razgrad        | 4         | 0.49%   |
| Pazardzhik     | 4         | 0.49%   |
| Montana        | 4         | 0.49%   |
| Gabrovo        | 4         | 0.49%   |
| Blagoevgrad    | 4         | 0.49%   |
| Svoge          | 3         | 0.36%   |
| Svilengrad     | 3         | 0.36%   |
| Sistov         | 3         | 0.36%   |
| Silistra       | 3         | 0.36%   |
| Kyustendil     | 3         | 0.36%   |
| Vratsa         | 2         | 0.24%   |
| Targovishte    | 2         | 0.24%   |
| Smolyan        | 2         | 0.24%   |
| Slashten       | 2         | 0.24%   |
| Sevlievo       | 2         | 0.24%   |
| Popovo         | 2         | 0.24%   |
| Omurtag        | 2         | 0.24%   |
| Novi Pazar     | 2         | 0.24%   |
| Novi Iskar     | 2         | 0.24%   |
| Nane           | 2         | 0.24%   |
| Mezdra         | 2         | 0.24%   |
| Krumovgrad     | 2         | 0.24%   |
| Karlovo        | 2         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 174       | 260    | 15.41%  |
| WDC                     | 168       | 250    | 14.88%  |
| Samsung Electronics     | 158       | 233    | 13.99%  |
| Toshiba                 | 102       | 136    | 9.03%   |
| Hitachi                 | 70        | 93     | 6.2%    |
| Kingston                | 67        | 99     | 5.93%   |
| SanDisk                 | 42        | 55     | 3.72%   |
| A-DATA Technology       | 41        | 56     | 3.63%   |
| Intel                   | 35        | 51     | 3.1%    |
| HGST                    | 35        | 52     | 3.1%    |
| Unknown                 | 28        | 37     | 2.48%   |
| SK hynix                | 18        | 21     | 1.59%   |
| Team                    | 17        | 18     | 1.51%   |
| Crucial                 | 17        | 28     | 1.51%   |
| SPCC                    | 12        | 14     | 1.06%   |
| China                   | 11        | 14     | 0.97%   |
| Micron Technology       | 10        | 11     | 0.89%   |
| KIOXIA                  | 10        | 11     | 0.89%   |
| Transcend               | 8         | 9      | 0.71%   |
| Phison                  | 7         | 7      | 0.62%   |
| Patriot                 | 7         | 8      | 0.62%   |
| KingSpec                | 7         | 8      | 0.62%   |
| Fujitsu                 | 6         | 9      | 0.53%   |
| Realtek Semiconductor   | 5         | 7      | 0.44%   |
| Maxtor                  | 5         | 9      | 0.44%   |
| LITEON                  | 5         | 6      | 0.44%   |
| Apple                   | 5         | 7      | 0.44%   |
| Silicon Motion          | 4         | 7      | 0.35%   |
| Intenso                 | 4         | 4      | 0.35%   |
| XPG                     | 3         | 5      | 0.27%   |
| TO Exter                | 3         | 3      | 0.27%   |
| PNY                     | 3         | 3      | 0.27%   |
| LITEONIT                | 3         | 3      | 0.27%   |
| ExcelStor               | 3         | 7      | 0.27%   |
| AMD                     | 3         | 5      | 0.27%   |
| Union Memory (Shenzhen) | 2         | 5      | 0.18%   |
| Teclast                 | 2         | 2      | 0.18%   |
| Realtek                 | 2         | 2      | 0.18%   |
| OCZ                     | 2         | 2      | 0.18%   |
| JMicron Technology      | 2         | 3      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 17        | 1.38%   |
| Seagate ST500DM002-1BD142 500GB    | 16        | 1.3%    |
| Kingston SA400S37120G 120GB SSD    | 15        | 1.22%   |
| Toshiba MQ01ABF050 500GB           | 14        | 1.14%   |
| Samsung SSD 860 EVO 250GB          | 14        | 1.14%   |
| Toshiba MQ01ABD100 1TB             | 13        | 1.05%   |
| HGST HTS721010A9E630 1TB           | 13        | 1.05%   |
| Samsung SSD 850 EVO 250GB          | 12        | 0.97%   |
| Samsung NVMe SSD Drive 512GB       | 12        | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 11        | 0.89%   |
| Samsung SSD 860 EVO 500GB          | 10        | 0.81%   |
| Kingston SA400S37480G 480GB SSD    | 9         | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 8         | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB     | 8         | 0.65%   |
| SanDisk NVMe SSD Drive 512GB       | 8         | 0.65%   |
| Kingston SA400S37240G 240GB SSD    | 8         | 0.65%   |
| Toshiba DT01ACA100 1TB             | 7         | 0.57%   |
| Seagate ST1000DM003-1ER162 1TB     | 7         | 0.57%   |
| Samsung NVMe SSD Drive 500GB       | 7         | 0.57%   |
| HGST HTS541010A9E680 1TB           | 7         | 0.57%   |
| WDC WD10SPZX-21Z10T0 1TB           | 6         | 0.49%   |
| Unknown MMC Card  32GB             | 6         | 0.49%   |
| Toshiba DT01ACA050 500GB           | 6         | 0.49%   |
| Samsung SSD 970 EVO 250GB          | 6         | 0.49%   |
| Samsung SSD 850 PRO 256GB          | 6         | 0.49%   |
| Kingston SV300S37A120G 120GB SSD   | 6         | 0.49%   |
| A-DATA SU650 240GB SSD             | 6         | 0.49%   |
| Unknown MMC Card  64GB             | 5         | 0.41%   |
| Toshiba NVMe SSD Drive 256GB       | 5         | 0.41%   |
| Toshiba MQ04ABF100 1TB             | 5         | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB     | 5         | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB     | 5         | 0.41%   |
| Samsung SSD 860 EVO 1TB            | 5         | 0.41%   |
| Samsung SSD 850 EVO 500GB          | 5         | 0.41%   |
| Samsung NVMe SSD Drive 1024GB      | 5         | 0.41%   |
| Intel SSDSC2CW120A3 120GB          | 5         | 0.41%   |
| Intel NVMe SSD Drive 512GB         | 5         | 0.41%   |
| Hitachi HTS547575A9E384 752GB      | 5         | 0.41%   |
| Hitachi HDS721050CLA362 500GB      | 5         | 0.41%   |
| Hitachi HDP725050GLA360 500GB      | 5         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 172       | 256    | 32.21%  |
| WDC                 | 146       | 214    | 27.34%  |
| Toshiba             | 82        | 109    | 15.36%  |
| Hitachi             | 70        | 93     | 13.11%  |
| HGST                | 35        | 52     | 6.55%   |
| Samsung Electronics | 7         | 10     | 1.31%   |
| Fujitsu             | 6         | 9      | 1.12%   |
| Maxtor              | 5         | 9      | 0.94%   |
| ExcelStor           | 3         | 7      | 0.56%   |
| Unknown             | 2         | 3      | 0.37%   |
| JMicron Technology  | 1         | 2      | 0.19%   |
| IBM/Hitachi         | 1         | 2      | 0.19%   |
| HGST HTS            | 1         | 1      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| ASMedia             | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 88        | 109    | 24.24%  |
| Kingston            | 52        | 71     | 14.33%  |
| A-DATA Technology   | 34        | 47     | 9.37%   |
| SanDisk             | 26        | 32     | 7.16%   |
| WDC                 | 17        | 25     | 4.68%   |
| Team                | 17        | 18     | 4.68%   |
| Intel               | 17        | 24     | 4.68%   |
| Crucial             | 16        | 26     | 4.41%   |
| SPCC                | 11        | 13     | 3.03%   |
| China               | 11        | 14     | 3.03%   |
| Transcend           | 7         | 8      | 1.93%   |
| Patriot             | 7         | 8      | 1.93%   |
| Toshiba             | 6         | 6      | 1.65%   |
| KingSpec            | 6         | 7      | 1.65%   |
| Micron Technology   | 5         | 5      | 1.38%   |
| LITEON              | 5         | 6      | 1.38%   |
| Intenso             | 4         | 4      | 1.1%    |
| TO Exter            | 3         | 3      | 0.83%   |
| PNY                 | 3         | 3      | 0.83%   |
| LITEONIT            | 3         | 3      | 0.83%   |
| Apple               | 3         | 5      | 0.83%   |
| AMD                 | 3         | 5      | 0.83%   |
| Teclast             | 2         | 2      | 0.55%   |
| OCZ                 | 2         | 2      | 0.55%   |
| Unknown             | 1         | 1      | 0.28%   |
| SK hynix            | 1         | 1      | 0.28%   |
| Seagate             | 1         | 2      | 0.28%   |
| OCZ-VERTEX3         | 1         | 1      | 0.28%   |
| Netac               | 1         | 3      | 0.28%   |
| Lexar               | 1         | 1      | 0.28%   |
| JMicron Technology  | 1         | 1      | 0.28%   |
| HS-SSD-C100         | 1         | 1      | 0.28%   |
| GOODRAM             | 1         | 1      | 0.28%   |
| Gigabyte Technology | 1         | 8      | 0.28%   |
| FORESEE             | 1         | 1      | 0.28%   |
| Emtec               | 1         | 1      | 0.28%   |
| EDGE                | 1         | 1      | 0.28%   |
| Corsair             | 1         | 1      | 0.28%   |
| ATP                 | 1         | 2      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 464       | 770    | 45.22%  |
| SSD     | 326       | 472    | 31.77%  |
| NVMe    | 204       | 313    | 19.88%  |
| MMC     | 23        | 28     | 2.24%   |
| Unknown | 9         | 10     | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 644       | 1222   | 71.71%  |
| NVMe | 203       | 311    | 22.61%  |
| SAS  | 28        | 32     | 3.12%   |
| MMC  | 23        | 28     | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 492       | 767    | 61.58%  |
| 0.51-1.0   | 242       | 365    | 30.29%  |
| 1.01-2.0   | 33        | 49     | 4.13%   |
| 3.01-4.0   | 12        | 28     | 1.5%    |
| 2.01-3.0   | 10        | 17     | 1.25%   |
| 4.01-10.0  | 6         | 8      | 0.75%   |
| 10.01-20.0 | 4         | 8      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 229       | 27.2%   |
| 251-500        | 185       | 21.97%  |
| 501-1000       | 129       | 15.32%  |
| 1001-2000      | 76        | 9.03%   |
| 1-20           | 68        | 8.08%   |
| 51-100         | 57        | 6.77%   |
| 21-50          | 37        | 4.39%   |
| More than 3000 | 28        | 3.33%   |
| Unknown        | 20        | 2.38%   |
| 2001-3000      | 13        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 355       | 39.36%  |
| 21-50          | 145       | 16.08%  |
| 101-250        | 121       | 13.41%  |
| 51-100         | 110       | 12.2%   |
| 251-500        | 55        | 6.1%    |
| 501-1000       | 51        | 5.65%   |
| 1001-2000      | 27        | 2.99%   |
| Unknown        | 20        | 2.22%   |
| More than 3000 | 10        | 1.11%   |
| 2001-3000      | 8         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 3         | 3      | 3.49%   |
| WDC WD6000HLHX-01JJPV0 600GB          | 2         | 3      | 2.33%   |
| WDC WD5000AAKX-603CA0 500GB           | 2         | 6      | 2.33%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 2.33%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 2.33%   |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 2.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 2.33%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 2.33%   |
| WDC WDS100T2B0B-00YS70 1TB SSD        | 1         | 1      | 1.16%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 1         | 1      | 1.16%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 1.16%   |
| WDC WD5000AACS-00G8B1 500GB           | 1         | 1      | 1.16%   |
| WDC WD3200BEVT-80A0RT0 320GB          | 1         | 1      | 1.16%   |
| WDC WD3200AAJS-07M0A0 320GB           | 1         | 2      | 1.16%   |
| WDC WD2500JS-00MHB0 250GB             | 1         | 1      | 1.16%   |
| WDC WD1600BEVT-80A23T0 160GB          | 1         | 1      | 1.16%   |
| WDC WD15EARS-00S8B1 1TB               | 1         | 1      | 1.16%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 1.16%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.16%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 1.16%   |
| Toshiba MK2552GSX 250GB               | 1         | 3      | 1.16%   |
| Toshiba MK1637GSX 160GB               | 1         | 1      | 1.16%   |
| Toshiba DT01ACA300 3TB                | 1         | 1      | 1.16%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.16%   |
| Seagate ST9500420AS 500GB             | 1         | 2      | 1.16%   |
| Seagate ST94019A 40GB                 | 1         | 1      | 1.16%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.16%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.16%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 1      | 1.16%   |
| Seagate ST380215A 80GB                | 1         | 1      | 1.16%   |
| Seagate ST3500830AS 500GB             | 1         | 1      | 1.16%   |
| Seagate ST3320311CS 320GB             | 1         | 1      | 1.16%   |
| Seagate ST31000333AS 1TB              | 1         | 1      | 1.16%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 1      | 1.16%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.16%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.16%   |
| SanDisk SDSSDX480GG25 480GB           | 1         | 1      | 1.16%   |
| SanDisk SDSSDH3250G 250GB             | 1         | 1      | 1.16%   |
| Samsung Electronics SSD 970 EVO 250GB | 1         | 1      | 1.16%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 1.16%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 24.42%  |
| WDC                 | 14        | 21     | 16.28%  |
| Hitachi             | 11        | 12     | 12.79%  |
| Toshiba             | 8         | 10     | 9.3%    |
| A-DATA Technology   | 7         | 7      | 8.14%   |
| Intel               | 5         | 6      | 5.81%   |
| Kingston            | 4         | 4      | 4.65%   |
| Samsung Electronics | 3         | 4      | 3.49%   |
| Maxtor              | 3         | 3      | 3.49%   |
| SanDisk             | 2         | 2      | 2.33%   |
| KingSpec            | 2         | 2      | 2.33%   |
| ExcelStor           | 2         | 3      | 2.33%   |
| Patriot             | 1         | 1      | 1.16%   |
| HGST                | 1         | 1      | 1.16%   |
| Fujitsu             | 1         | 2      | 1.16%   |
| China               | 1         | 1      | 1.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 21        | 22     | 35%     |
| WDC       | 13        | 20     | 21.67%  |
| Hitachi   | 11        | 12     | 18.33%  |
| Toshiba   | 8         | 10     | 13.33%  |
| Maxtor    | 3         | 3      | 5%      |
| ExcelStor | 2         | 3      | 3.33%   |
| HGST      | 1         | 1      | 1.67%   |
| Fujitsu   | 1         | 2      | 1.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 57        | 73     | 69.51%  |
| SSD  | 23        | 25     | 28.05%  |
| NVMe | 2         | 3      | 2.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 50%     |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 497       | 981    | 57.59%  |
| Works    | 287       | 509    | 33.26%  |
| Malfunc  | 77        | 101    | 8.92%   |
| Failed   | 2         | 2      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 583       | 60.04%  |
| AMD                              | 126       | 12.98%  |
| Samsung Electronics              | 82        | 8.44%   |
| SanDisk                          | 25        | 2.57%   |
| SK hynix                         | 17        | 1.75%   |
| JMicron Technology               | 17        | 1.75%   |
| Nvidia                           | 16        | 1.65%   |
| Kingston Technology Company      | 16        | 1.65%   |
| KIOXIA                           | 13        | 1.34%   |
| Toshiba America Info Systems     | 12        | 1.24%   |
| ASMedia Technology               | 10        | 1.03%   |
| Realtek Semiconductor            | 9         | 0.93%   |
| Phison Electronics               | 8         | 0.82%   |
| Marvell Technology Group         | 8         | 0.82%   |
| ADATA Technology                 | 8         | 0.82%   |
| Silicon Motion                   | 5         | 0.51%   |
| Micron Technology                | 5         | 0.51%   |
| Union Memory (Shenzhen)          | 2         | 0.21%   |
| Micron/Crucial Technology        | 2         | 0.21%   |
| VIA Technologies                 | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Lenovo                           | 1         | 0.1%    |
| Integrated Technology Express    | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| Chelsio Communications           | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 81        | 7.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 52        | 4.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 52        | 4.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 37        | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 35        | 3.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 33        | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 33        | 2.9%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24        | 2.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 24        | 2.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 23        | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 18        | 1.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 18        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17        | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 16        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 16        | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 15        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 13        | 1.14%   |
| Intel SATA Controller [RAID mode]                                                       | 12        | 1.05%   |
| Samsung NVMe SSD Controller 980                                                         | 11        | 0.97%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 11        | 0.97%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 11        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 11        | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 11        | 0.97%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11        | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 10        | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10        | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 10        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 0.88%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 10        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 10        | 0.88%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 9         | 0.79%   |
| Intel SSD 660P Series                                                                   | 9         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 0.7%    |
| Nvidia MCP61 SATA Controller                                                            | 8         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8         | 0.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 7         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 563       | 57.1%   |
| NVMe | 208       | 21.1%   |
| IDE  | 154       | 15.62%  |
| RAID | 58        | 5.88%   |
| SAS  | 2         | 0.2%    |
| SCSI | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 626       | 79.44%  |
| AMD    | 162       | 20.56%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz        | 11        | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 10        | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 9         | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 9         | 1.14%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 9         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 8         | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 7         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 7         | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 7         | 0.88%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 6         | 0.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 6         | 0.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 0.76%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 6         | 0.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 6         | 0.76%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 5         | 0.63%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 5         | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 5         | 0.63%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 5         | 0.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 5         | 0.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 5         | 0.63%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 5         | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 5         | 0.63%   |
| AMD Ryzen 5 1600 Six-Core Processor      | 5         | 0.63%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 5         | 0.63%   |
| Intel Pentium CPU G645 @ 2.90GHz         | 4         | 0.51%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 0.51%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 4         | 0.51%   |
| Intel Core i7-5600U CPU @ 2.60GHz        | 4         | 0.51%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 4         | 0.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 4         | 0.51%   |
| Intel Core i5-5300U CPU @ 2.30GHz        | 4         | 0.51%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 4         | 0.51%   |
| Intel Core i5-3340M CPU @ 2.70GHz        | 4         | 0.51%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 4         | 0.51%   |
| Intel Core i3-5005U CPU @ 2.00GHz        | 4         | 0.51%   |
| Intel Core i3-3110M CPU @ 2.40GHz        | 4         | 0.51%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 4         | 0.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 4         | 0.51%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz     | 4         | 0.51%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 4         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 170       | 21.49%  |
| Intel Core i7           | 165       | 20.86%  |
| Intel Core i3           | 59        | 7.46%   |
| Intel Core 2 Duo        | 44        | 5.56%   |
| Intel Pentium           | 38        | 4.8%    |
| Intel Celeron           | 37        | 4.68%   |
| AMD Ryzen 5             | 36        | 4.55%   |
| AMD Ryzen 7             | 27        | 3.41%   |
| Other                   | 24        | 3.03%   |
| Intel Xeon              | 17        | 2.15%   |
| Intel Pentium Dual-Core | 12        | 1.52%   |
| Intel Core 2 Quad       | 12        | 1.52%   |
| Intel Atom              | 11        | 1.39%   |
| AMD Ryzen 3             | 10        | 1.26%   |
| AMD Athlon 64 X2        | 10        | 1.26%   |
| Intel Pentium Dual      | 8         | 1.01%   |
| Intel Core 2            | 7         | 0.88%   |
| AMD Ryzen 9             | 7         | 0.88%   |
| AMD FX                  | 7         | 0.88%   |
| Intel Pentium Silver    | 5         | 0.63%   |
| Intel Core i9           | 5         | 0.63%   |
| AMD Ryzen 7 PRO         | 5         | 0.63%   |
| AMD Athlon II X2        | 5         | 0.63%   |
| AMD Athlon 64           | 5         | 0.63%   |
| AMD A8                  | 5         | 0.63%   |
| AMD Ryzen 5 PRO         | 4         | 0.51%   |
| AMD Phenom II X4        | 4         | 0.51%   |
| AMD E1                  | 4         | 0.51%   |
| AMD Sempron             | 3         | 0.38%   |
| AMD Athlon II X4        | 3         | 0.38%   |
| AMD A6                  | 3         | 0.38%   |
| Intel Pentium M         | 2         | 0.25%   |
| Intel Pentium Gold      | 2         | 0.25%   |
| Intel Genuine           | 2         | 0.25%   |
| Intel Core m3           | 2         | 0.25%   |
| AMD Phenom II X6        | 2         | 0.25%   |
| AMD Phenom II X2        | 2         | 0.25%   |
| AMD Phenom              | 2         | 0.25%   |
| AMD Athlon X4           | 2         | 0.25%   |
| AMD A10                 | 2         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 362       | 45.71%  |
| 4       | 266       | 33.59%  |
| 6       | 74        | 9.34%   |
| 8       | 40        | 5.05%   |
| 1       | 23        | 2.9%    |
| 12      | 9         | 1.14%   |
| 3       | 9         | 1.14%   |
| 16      | 3         | 0.38%   |
| 14      | 2         | 0.25%   |
| Unknown | 2         | 0.25%   |
| 18      | 1         | 0.13%   |
| 10      | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 786       | 99.75%  |
| 2      | 2         | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 489       | 61.74%  |
| 1       | 301       | 38.01%  |
| Unknown | 2         | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 759       | 95.35%  |
| Unknown        | 26        | 3.27%   |
| 32-bit         | 11        | 1.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 178       | 21.63%  |
| 0x306a9    | 60        | 7.29%   |
| 0x206a7    | 59        | 7.17%   |
| 0x306c3    | 45        | 5.47%   |
| 0x1067a    | 34        | 4.13%   |
| 0x906ea    | 25        | 3.04%   |
| 0x806ec    | 25        | 3.04%   |
| 0x306d4    | 22        | 2.67%   |
| 0x506e3    | 20        | 2.43%   |
| 0x906e9    | 18        | 2.19%   |
| 0x20655    | 18        | 2.19%   |
| 0x406e3    | 17        | 2.07%   |
| 0x40651    | 17        | 2.07%   |
| 0x6fd      | 16        | 1.94%   |
| 0x806ea    | 14        | 1.7%    |
| 0x10676    | 12        | 1.46%   |
| 0x706a1    | 11        | 1.34%   |
| 0x806c1    | 10        | 1.22%   |
| 0x506c9    | 10        | 1.22%   |
| 0x010000c8 | 10        | 1.22%   |
| 0x08108109 | 9         | 1.09%   |
| 0x6fb      | 8         | 0.97%   |
| 0x806e9    | 7         | 0.85%   |
| 0x08108102 | 7         | 0.85%   |
| 0x6f6      | 6         | 0.73%   |
| 0x406c3    | 6         | 0.73%   |
| 0x306f2    | 6         | 0.73%   |
| 0x08608103 | 6         | 0.73%   |
| 0xa0652    | 5         | 0.61%   |
| 0x806eb    | 5         | 0.61%   |
| 0x706e5    | 5         | 0.61%   |
| 0x08600106 | 5         | 0.61%   |
| 0x08600103 | 5         | 0.61%   |
| 0x0800820d | 5         | 0.61%   |
| 0x106e5    | 4         | 0.49%   |
| 0x106c2    | 4         | 0.49%   |
| 0x0a50000c | 4         | 0.49%   |
| 0x0a201009 | 4         | 0.49%   |
| 0x0700010f | 4         | 0.49%   |
| 0x06000852 | 4         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 119       | 15.06%  |
| Haswell          | 81        | 10.25%  |
| IvyBridge        | 76        | 9.62%   |
| SandyBridge      | 71        | 8.99%   |
| Penryn           | 56        | 7.09%   |
| Skylake          | 40        | 5.06%   |
| Core             | 35        | 4.43%   |
| Zen+             | 26        | 3.29%   |
| Zen 2            | 26        | 3.29%   |
| Broadwell        | 26        | 3.29%   |
| Westmere         | 25        | 3.16%   |
| K10              | 22        | 2.78%   |
| Zen 3            | 20        | 2.53%   |
| K8 Hammer        | 18        | 2.28%   |
| TigerLake        | 13        | 1.65%   |
| Silvermont       | 13        | 1.65%   |
| Goldmont plus    | 13        | 1.65%   |
| Unknown          | 13        | 1.65%   |
| Zen              | 12        | 1.52%   |
| Piledriver       | 11        | 1.39%   |
| CometLake        | 11        | 1.39%   |
| IceLake          | 10        | 1.27%   |
| Goldmont         | 10        | 1.27%   |
| Bonnell          | 7         | 0.89%   |
| P6               | 5         | 0.63%   |
| Nehalem          | 5         | 0.63%   |
| Jaguar           | 4         | 0.51%   |
| Excavator        | 4         | 0.51%   |
| Alderlake Hybrid | 4         | 0.51%   |
| Steamroller      | 3         | 0.38%   |
| K10 Llano        | 3         | 0.38%   |
| Puma             | 2         | 0.25%   |
| NetBurst         | 2         | 0.25%   |
| Bobcat           | 2         | 0.25%   |
| K8 & K10 hybrid  | 1         | 0.13%   |
| Bulldozer        | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 481       | 48.98%  |
| Nvidia                           | 279       | 28.41%  |
| AMD                              | 221       | 22.51%  |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 51        | 5.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 51        | 5.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 24        | 2.38%   |
| Intel HD Graphics 5500                                                                   | 23        | 2.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 1.98%   |
| AMD Renoir                                                                               | 19        | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 1.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.78%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 17        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 1.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 1.49%   |
| Intel HD Graphics 630                                                                    | 15        | 1.49%   |
| Intel UHD Graphics 620                                                                   | 14        | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.29%   |
| Intel HD Graphics 530                                                                    | 12        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.79%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 0.79%   |
| Intel HD Graphics 620                                                                    | 8         | 0.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 0.69%   |
| AMD Lucienne                                                                             | 7         | 0.69%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 0.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 0.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 0.59%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 6         | 0.59%   |
| Nvidia TU117M                                                                            | 5         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 304       | 38%     |
| 1 x AMD        | 172       | 21.5%   |
| Intel + Nvidia | 136       | 17%     |
| 1 x Nvidia     | 134       | 16.75%  |
| Intel + AMD    | 32        | 4%      |
| AMD + Nvidia   | 11        | 1.38%   |
| 2 x AMD        | 10        | 1.25%   |
| 1 x SiS        | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 621       | 77.14%  |
| Proprietary | 149       | 18.51%  |
| Unknown     | 35        | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 416       | 50.42%  |
| 1.01-2.0   | 138       | 16.73%  |
| 0.01-0.5   | 88        | 10.67%  |
| 3.01-4.0   | 71        | 8.61%   |
| 0.51-1.0   | 61        | 7.39%   |
| 7.01-8.0   | 27        | 3.27%   |
| 5.01-6.0   | 13        | 1.58%   |
| 2.01-3.0   | 5         | 0.61%   |
| 8.01-16.0  | 5         | 0.61%   |
| 16.01-24.0 | 1         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 140       | 16.47%  |
| AU Optronics            | 88        | 10.35%  |
| Samsung Electronics     | 87        | 10.24%  |
| Chimei Innolux          | 62        | 7.29%   |
| Dell                    | 58        | 6.82%   |
| BOE                     | 56        | 6.59%   |
| Goldstar                | 38        | 4.47%   |
| Philips                 | 34        | 4%      |
| Acer                    | 31        | 3.65%   |
| Hewlett-Packard         | 24        | 2.82%   |
| Lenovo                  | 23        | 2.71%   |
| Ancor Communications    | 23        | 2.71%   |
| AOC                     | 18        | 2.12%   |
| Chi Mei Optoelectronics | 17        | 2%      |
| BenQ                    | 15        | 1.76%   |
| PANDA                   | 9         | 1.06%   |
| LG Philips              | 9         | 1.06%   |
| Sharp                   | 7         | 0.82%   |
| LG Electronics          | 7         | 0.82%   |
| Fujitsu Siemens         | 7         | 0.82%   |
| Sony                    | 6         | 0.71%   |
| Panasonic               | 6         | 0.71%   |
| HannStar                | 6         | 0.71%   |
| NEC Computers           | 5         | 0.59%   |
| Apple                   | 5         | 0.59%   |
| MSI                     | 4         | 0.47%   |
| Eizo                    | 4         | 0.47%   |
| CPT                     | 4         | 0.47%   |
| ViewSonic               | 3         | 0.35%   |
| Vestel Elektronik       | 3         | 0.35%   |
| Unknown                 | 3         | 0.35%   |
| Iiyama                  | 3         | 0.35%   |
| WST                     | 2         | 0.24%   |
| Vestel                  | 2         | 0.24%   |
| Toshiba                 | 2         | 0.24%   |
| Lenovo Group Limited    | 2         | 0.24%   |
| InnoLux Display         | 2         | 0.24%   |
| Gigabyte Technology     | 2         | 0.24%   |
| Belinea                 | 2         | 0.24%   |
| ASUSTek Computer        | 2         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 1.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.8%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 4         | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.46%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.46%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 4         | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.46%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 4         | 0.46%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.46%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 3         | 0.34%   |
| Samsung Electronics SMXL2370HD SAM072B 1920x1080 510x287mm 23.0-inch     | 3         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 3         | 0.34%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.34%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch              | 3         | 0.34%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 3         | 0.34%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 3         | 0.34%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 3         | 0.34%   |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                        | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.34%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 3         | 0.34%   |
| Acer G257HL ACR0415 1920x1080 553x309mm 24.9-inch                        | 3         | 0.34%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.23%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 2         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 366       | 45.02%  |
| 1366x768 (WXGA)    | 150       | 18.45%  |
| 1280x1024 (SXGA)   | 36        | 4.43%   |
| 1680x1050 (WSXGA+) | 35        | 4.31%   |
| 1600x900 (HD+)     | 34        | 4.18%   |
| 3840x2160 (4K)     | 31        | 3.81%   |
| 2560x1440 (QHD)    | 31        | 3.81%   |
| 1280x800 (WXGA)    | 25        | 3.08%   |
| 1440x900 (WXGA+)   | 17        | 2.09%   |
| 1920x1200 (WUXGA)  | 16        | 1.97%   |
| Unknown            | 13        | 1.6%    |
| 2560x1080          | 7         | 0.86%   |
| 3440x1440          | 5         | 0.62%   |
| 2560x1600          | 5         | 0.62%   |
| 1024x600           | 5         | 0.62%   |
| 3840x1080          | 4         | 0.49%   |
| 1024x768 (XGA)     | 4         | 0.49%   |
| 3840x1200          | 3         | 0.37%   |
| 1600x1200          | 3         | 0.37%   |
| 1360x768           | 3         | 0.37%   |
| 1280x720 (HD)      | 3         | 0.37%   |
| 3200x1080          | 2         | 0.25%   |
| 1400x1050          | 2         | 0.25%   |
| 6784x2160          | 1         | 0.12%   |
| 6400x1080          | 1         | 0.12%   |
| 5120x1080          | 1         | 0.12%   |
| 4240x1440          | 1         | 0.12%   |
| 3600x1200          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3000x2000          | 1         | 0.12%   |
| 2880x1800          | 1         | 0.12%   |
| 2160x1440          | 1         | 0.12%   |
| 2048x1152          | 1         | 0.12%   |
| 1921x1080          | 1         | 0.12%   |
| 1920x540           | 1         | 0.12%   |
| 1820x1023          | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 272       | 32%     |
| 24      | 61        | 7.18%   |
| 13      | 60        | 7.06%   |
| 17      | 54        | 6.35%   |
| 23      | 53        | 6.24%   |
| 14      | 52        | 6.12%   |
| 21      | 48        | 5.65%   |
| Unknown | 42        | 4.94%   |
| 27      | 38        | 4.47%   |
| 19      | 26        | 3.06%   |
| 12      | 22        | 2.59%   |
| 22      | 21        | 2.47%   |
| 20      | 15        | 1.76%   |
| 84      | 10        | 1.18%   |
| 34      | 10        | 1.18%   |
| 18      | 10        | 1.18%   |
| 31      | 9         | 1.06%   |
| 54      | 6         | 0.71%   |
| 25      | 6         | 0.71%   |
| 10      | 6         | 0.71%   |
| 16      | 5         | 0.59%   |
| 11      | 5         | 0.59%   |
| 40      | 4         | 0.47%   |
| 72      | 3         | 0.35%   |
| 26      | 2         | 0.24%   |
| 75      | 1         | 0.12%   |
| 65      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 37      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 32      | 1         | 0.12%   |
| 30      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |
| 28      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 374       | 44.31%  |
| 501-600     | 147       | 17.42%  |
| 401-500     | 104       | 12.32%  |
| 351-400     | 60        | 7.11%   |
| 201-300     | 58        | 6.87%   |
| Unknown     | 42        | 4.98%   |
| 601-700     | 19        | 2.25%   |
| 1501-2000   | 14        | 1.66%   |
| 701-800     | 12        | 1.42%   |
| 1001-1500   | 9         | 1.07%   |
| 801-900     | 5         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 566       | 73.51%  |
| 16/10   | 103       | 13.38%  |
| Unknown | 38        | 4.94%   |
| 5/4     | 34        | 4.42%   |
| 21/9    | 12        | 1.56%   |
| 4/3     | 11        | 1.43%   |
| 3/2     | 4         | 0.52%   |
| 6/5     | 1         | 0.13%   |
| 32/9    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 271       | 32.26%  |
| 201-250        | 143       | 17.02%  |
| 81-90          | 91        | 10.83%  |
| 151-200        | 54        | 6.43%   |
| Unknown        | 42        | 5%      |
| 301-350        | 41        | 4.88%   |
| 121-130        | 32        | 3.81%   |
| 251-300        | 27        | 3.21%   |
| 141-150        | 26        | 3.1%    |
| 71-80          | 23        | 2.74%   |
| More than 1000 | 22        | 2.62%   |
| 351-500        | 22        | 2.62%   |
| 61-70          | 20        | 2.38%   |
| 41-50          | 6         | 0.71%   |
| 501-1000       | 6         | 0.71%   |
| 51-60          | 5         | 0.6%    |
| 131-140        | 4         | 0.48%   |
| 111-120        | 4         | 0.48%   |
| 91-100         | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 272       | 33.09%  |
| 121-160       | 244       | 29.68%  |
| 101-120       | 206       | 25.06%  |
| Unknown       | 42        | 5.11%   |
| 161-240       | 32        | 3.89%   |
| 1-50          | 16        | 1.95%   |
| More than 240 | 10        | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 648       | 79.51%  |
| 2     | 112       | 13.74%  |
| 0     | 42        | 5.15%   |
| 3     | 12        | 1.47%   |
| 4     | 1         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 413       | 34.13%  |
| Intel                             | 389       | 32.15%  |
| Qualcomm Atheros                  | 145       | 11.98%  |
| Broadcom                          | 60        | 4.96%   |
| Broadcom Limited                  | 25        | 2.07%   |
| Ralink                            | 19        | 1.57%   |
| TP-Link                           | 18        | 1.49%   |
| Nvidia                            | 16        | 1.32%   |
| Marvell Technology Group          | 14        | 1.16%   |
| Ralink Technology                 | 13        | 1.07%   |
| Qualcomm Atheros Communications   | 11        | 0.91%   |
| Sierra Wireless                   | 10        | 0.83%   |
| MediaTek                          | 10        | 0.83%   |
| Ericsson Business Mobile Networks | 10        | 0.83%   |
| Sundance Technology Inc / IC Plus | 4         | 0.33%   |
| Huawei Technologies               | 4         | 0.33%   |
| Hewlett-Packard                   | 4         | 0.33%   |
| Dell                              | 4         | 0.33%   |
| D-Link                            | 4         | 0.33%   |
| Xiaomi                            | 3         | 0.25%   |
| Microsoft                         | 3         | 0.25%   |
| AMD                               | 3         | 0.25%   |
| Toshiba                           | 2         | 0.17%   |
| Motorola PCS                      | 2         | 0.17%   |
| Davicom Semiconductor             | 2         | 0.17%   |
| D-Link System                     | 2         | 0.17%   |
| Chelsio Communications            | 2         | 0.17%   |
| Aquantia                          | 2         | 0.17%   |
| Samsung Electronics               | 1         | 0.08%   |
| Razer USA                         | 1         | 0.08%   |
| Quectel Wireless Solutions        | 1         | 0.08%   |
| NetGear                           | 1         | 0.08%   |
| Micro Star International          | 1         | 0.08%   |
| Linksys                           | 1         | 0.08%   |
| Lenovo                            | 1         | 0.08%   |
| JMicron Technology                | 1         | 0.08%   |
| ICS Advent                        | 1         | 0.08%   |
| Google                            | 1         | 0.08%   |
| Gemtek                            | 1         | 0.08%   |
| DisplayLink                       | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 276       | 19.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 58        | 4.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 45        | 3.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 25        | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 25        | 1.77%   |
| Intel Wi-Fi 6 AX200                                               | 23        | 1.63%   |
| Intel Wireless 8265 / 8275                                        | 21        | 1.48%   |
| Intel Wireless 7260                                               | 21        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 20        | 1.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 1.34%   |
| Intel Wireless 7265                                               | 19        | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 19        | 1.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 14        | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 13        | 0.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 0.92%   |
| Intel Wireless 3160                                               | 12        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 12        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 11        | 0.78%   |
| Intel I211 Gigabit Network Connection                             | 11        | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 10        | 0.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                   | 10        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 0.71%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.71%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.64%   |
| Intel WiFi Link 5100                                              | 9         | 0.64%   |
| Intel Centrino Ultimate-N 6300                                    | 9         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.57%   |
| Nvidia MCP61 Ethernet                                             | 8         | 0.57%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 8         | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 8         | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 291       | 48.02%  |
| Qualcomm Atheros                | 104       | 17.16%  |
| Realtek Semiconductor           | 78        | 12.87%  |
| Broadcom                        | 38        | 6.27%   |
| Ralink                          | 19        | 3.14%   |
| TP-Link                         | 14        | 2.31%   |
| Ralink Technology               | 13        | 2.15%   |
| Qualcomm Atheros Communications | 11        | 1.82%   |
| Sierra Wireless                 | 10        | 1.65%   |
| MediaTek                        | 9         | 1.49%   |
| Broadcom Limited                | 8         | 1.32%   |
| Microsoft                       | 3         | 0.5%    |
| Quectel Wireless Solutions      | 1         | 0.17%   |
| NetGear                         | 1         | 0.17%   |
| Micro Star International        | 1         | 0.17%   |
| Linksys                         | 1         | 0.17%   |
| Hewlett-Packard                 | 1         | 0.17%   |
| Gemtek                          | 1         | 0.17%   |
| Dell                            | 1         | 0.17%   |
| D-Link                          | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 25        | 4.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 25        | 4.11%   |
| Intel Wi-Fi 6 AX200                                            | 23        | 3.78%   |
| Intel Wireless 8265 / 8275                                     | 21        | 3.45%   |
| Intel Wireless 7260                                            | 21        | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 20        | 3.29%   |
| Intel Wireless 7265                                            | 19        | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 19        | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14        | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 13        | 2.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 2.14%   |
| Intel Wireless 3160                                            | 12        | 1.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 1.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 1.81%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 1.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 10        | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                | 10        | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 1.64%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 1.48%   |
| Intel WiFi Link 5100                                           | 9         | 1.48%   |
| Intel Centrino Ultimate-N 6300                                 | 9         | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.32%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 8         | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 7         | 1.15%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 7         | 1.15%   |
| Intel Wireless-AC 9260                                         | 7         | 1.15%   |
| Intel Wireless 8260                                            | 7         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.15%   |
| Sierra Wireless EM7345 4G LTE                                  | 6         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 0.99%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 375       | 49.08%  |
| Intel                             | 222       | 29.06%  |
| Qualcomm Atheros                  | 57        | 7.46%   |
| Broadcom                          | 25        | 3.27%   |
| Broadcom Limited                  | 17        | 2.23%   |
| Nvidia                            | 16        | 2.09%   |
| Marvell Technology Group          | 14        | 1.83%   |
| TP-Link                           | 4         | 0.52%   |
| Sundance Technology Inc / IC Plus | 4         | 0.52%   |
| Xiaomi                            | 3         | 0.39%   |
| Huawei Technologies               | 3         | 0.39%   |
| D-Link                            | 3         | 0.39%   |
| Motorola PCS                      | 2         | 0.26%   |
| Davicom Semiconductor             | 2         | 0.26%   |
| D-Link System                     | 2         | 0.26%   |
| Chelsio Communications            | 2         | 0.26%   |
| Aquantia                          | 2         | 0.26%   |
| Samsung Electronics               | 1         | 0.13%   |
| MediaTek                          | 1         | 0.13%   |
| Lenovo                            | 1         | 0.13%   |
| JMicron Technology                | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| Google                            | 1         | 0.13%   |
| DisplayLink                       | 1         | 0.13%   |
| Cypress Semiconductor             | 1         | 0.13%   |
| Attansic Technology               | 1         | 0.13%   |
| ASIX Electronics                  | 1         | 0.13%   |
| Apple                             | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 276       | 35.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 58        | 7.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 45        | 5.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 19        | 2.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 15        | 1.92%   |
| Intel Ethernet Connection I217-LM                                          | 12        | 1.54%   |
| Intel Ethernet Connection (2) I219-V                                       | 12        | 1.54%   |
| Intel I211 Gigabit Network Connection                                      | 11        | 1.41%   |
| Intel Ethernet Connection (3) I218-LM                                      | 11        | 1.41%   |
| Intel 82579V Gigabit Network Connection                                    | 11        | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                     | 10        | 1.28%   |
| Nvidia MCP61 Ethernet                                                      | 8         | 1.02%   |
| Intel Ethernet Controller I225-V                                           | 8         | 1.02%   |
| Intel Ethernet Connection I218-LM                                          | 8         | 1.02%   |
| Intel Ethernet Connection (7) I219-V                                       | 8         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                   | 8         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                          | 7         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 7         | 0.9%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 7         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                                       | 7         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                                   | 7         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 6         | 0.77%   |
| Intel Ethernet Connection I217-V                                           | 6         | 0.77%   |
| Intel Ethernet Connection (2) I218-V                                       | 6         | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 5         | 0.64%   |
| Intel Ethernet Connection I219-LM                                          | 5         | 0.64%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 5         | 0.64%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                    | 5         | 0.64%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 4         | 0.51%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 4         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 4         | 0.51%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                 | 4         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                                      | 4         | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                                      | 4         | 0.51%   |
| Intel Ethernet Connection (10) I219-V                                      | 4         | 0.51%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 4         | 0.51%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 4         | 0.51%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                            | 4         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 3         | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 3         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 719       | 54.72%  |
| WiFi     | 569       | 43.3%   |
| Modem    | 26        | 1.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 454       | 54.96%  |
| Ethernet | 372       | 45.04%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 471       | 59.39%  |
| 1     | 300       | 37.83%  |
| 3     | 12        | 1.51%   |
| 0     | 7         | 0.88%   |
| 7     | 1         | 0.13%   |
| 5     | 1         | 0.13%   |
| 4     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 778       | 98.23%  |
| Yes  | 14        | 1.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 201       | 44.18%  |
| Qualcomm Atheros Communications | 35        | 7.69%   |
| Realtek Semiconductor           | 32        | 7.03%   |
| Cambridge Silicon Radio         | 30        | 6.59%   |
| Broadcom                        | 26        | 5.71%   |
| IMC Networks                    | 23        | 5.05%   |
| Lite-On Technology              | 18        | 3.96%   |
| Foxconn / Hon Hai               | 14        | 3.08%   |
| Dell                            | 13        | 2.86%   |
| Toshiba                         | 12        | 2.64%   |
| Hewlett-Packard                 | 12        | 2.64%   |
| Ralink                          | 9         | 1.98%   |
| Integrated System Solution      | 7         | 1.54%   |
| Apple                           | 7         | 1.54%   |
| Foxconn International           | 5         | 1.1%    |
| ASUSTek Computer                | 5         | 1.1%    |
| MediaTek                        | 3         | 0.66%   |
| Ralink Technology               | 2         | 0.44%   |
| Realtek                         | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 79        | 17.36%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 37        | 8.13%   |
| Intel AX201 Bluetooth                                 | 32        | 7.03%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 30        | 6.59%   |
| Realtek Bluetooth Radio                               | 25        | 5.49%   |
| Intel AX200 Bluetooth                                 | 23        | 5.05%   |
| Qualcomm Atheros  Bluetooth Device                    | 22        | 4.84%   |
| IMC Networks Bluetooth Radio                          | 12        | 2.64%   |
| Ralink RT3290 Bluetooth                               | 9         | 1.98%   |
| Lite-On Bluetooth Device                              | 8         | 1.76%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 8         | 1.76%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 7         | 1.54%   |
| Foxconn / Hon Hai Bluetooth Device                    | 7         | 1.54%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 6         | 1.32%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 6         | 1.32%   |
| IMC Networks Bluetooth Device                         | 6         | 1.32%   |
| Toshiba Integrated Bluetooth HCI                      | 5         | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 5         | 1.1%    |
| Intel AX210 Bluetooth                                 | 5         | 1.1%    |
| HP Broadcom 2070 Bluetooth Combo                      | 5         | 1.1%    |
| Foxconn International BCM43142A0 Bluetooth module     | 5         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                           | 5         | 1.1%    |
| Realtek  Bluetooth 4.2 Adapter                        | 4         | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4         | 0.88%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4         | 0.88%   |
| IMC Networks Wireless_Device                          | 4         | 0.88%   |
| Foxconn / Hon Hai BCM20702A0                          | 4         | 0.88%   |
| Dell DW375 Bluetooth Module                           | 4         | 0.88%   |
| Apple Bluetooth Host Controller                       | 4         | 0.88%   |
| Toshiba Bluetooth Device                              | 3         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                      | 3         | 0.66%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 0.66%   |
| Integrated System Solution Bluetooth Device           | 3         | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                      | 3         | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 3         | 0.66%   |
| Broadcom BCM2045 Bluetooth                            | 3         | 0.66%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)            | 2         | 0.44%   |
| Realtek RTL8723B Bluetooth                            | 2         | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 606       | 55.39%  |
| AMD                                  | 209       | 19.1%   |
| Nvidia                               | 181       | 16.54%  |
| C-Media Electronics                  | 18        | 1.65%   |
| Creative Labs                        | 13        | 1.19%   |
| Razer USA                            | 7         | 0.64%   |
| GN Netcom                            | 7         | 0.64%   |
| Logitech                             | 5         | 0.46%   |
| Texas Instruments                    | 4         | 0.37%   |
| Plantronics                          | 4         | 0.37%   |
| Creative Technology                  | 4         | 0.37%   |
| ASUSTek Computer                     | 4         | 0.37%   |
| Realtek Semiconductor                | 3         | 0.27%   |
| Lenovo                               | 3         | 0.27%   |
| Generalplus Technology               | 3         | 0.27%   |
| VIA Technologies                     | 2         | 0.18%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.18%   |
| Tenx Technology                      | 2         | 0.18%   |
| JMTek                                | 2         | 0.18%   |
| BEHRINGER International              | 2         | 0.18%   |
| ZOOM                                 | 1         | 0.09%   |
| SteelSeries ApS                      | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.09%   |
| Sennheiser Communications            | 1         | 0.09%   |
| Samson Technologies                  | 1         | 0.09%   |
| NAD Electronics                      | 1         | 0.09%   |
| M-Audio                              | 1         | 0.09%   |
| FiiO Electronics Technology          | 1         | 0.09%   |
| Evolution Electronics                | 1         | 0.09%   |
| ESS Technology                       | 1         | 0.09%   |
| Dell                                 | 1         | 0.09%   |
| Corsair                              | 1         | 0.09%   |
| Apple                                | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 70        | 5.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 70        | 5.4%    |
| AMD Family 17h/19h HD Audio Controller                                     | 59        | 4.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 46        | 3.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 44        | 3.4%    |
| Intel Sunrise Point-LP HD Audio                                            | 43        | 3.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 3.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 2.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 29        | 2.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 29        | 2.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 27        | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 27        | 2.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 26        | 2.01%   |
| Intel Broadwell-U Audio Controller                                         | 26        | 2.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23        | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                      | 22        | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 22        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18        | 1.39%   |
| AMD Starship/Matisse HD Audio Controller                                   | 18        | 1.39%   |
| AMD FCH Azalia Controller                                                  | 18        | 1.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 17        | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 15        | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                              | 14        | 1.08%   |
| Intel 200 Series PCH HD Audio                                              | 14        | 1.08%   |
| Nvidia GF119 HDMI Audio Controller                                         | 13        | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 1%      |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 1%      |
| Intel CM238 HD Audio Controller                                            | 13        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 1%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 13        | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 12        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 10        | 0.77%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 10        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 10        | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 0.69%   |
| Nvidia High Definition Audio Controller                                    | 9         | 0.69%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 97        | 20.08%  |
| SK hynix                                | 88        | 18.22%  |
| Kingston                                | 67        | 13.87%  |
| Unknown                                 | 49        | 10.14%  |
| Micron Technology                       | 39        | 8.07%   |
| Corsair                                 | 25        | 5.18%   |
| A-DATA Technology                       | 25        | 5.18%   |
| Ramaxel Technology                      | 19        | 3.93%   |
| Nanya Technology                        | 12        | 2.48%   |
| Team                                    | 9         | 1.86%   |
| Crucial                                 | 9         | 1.86%   |
| Transcend                               | 8         | 1.66%   |
| Elpida                                  | 7         | 1.45%   |
| G.Skill                                 | 6         | 1.24%   |
| Goodram                                 | 3         | 0.62%   |
| Apacer                                  | 3         | 0.62%   |
| Silicon Power                           | 2         | 0.41%   |
| pqi                                     | 2         | 0.41%   |
| Atermiter                               | 2         | 0.41%   |
| ASint Technology                        | 2         | 0.41%   |
| Unknown (ABCD)                          | 1         | 0.21%   |
| Unifosa                                 | 1         | 0.21%   |
| Thermaltake                             | 1         | 0.21%   |
| Silicon Power Computer & Communications | 1         | 0.21%   |
| Qimonda                                 | 1         | 0.21%   |
| HBS                                     | 1         | 0.21%   |
| CSX                                     | 1         | 0.21%   |
| A Force                                 | 1         | 0.21%   |
| Unknown                                 | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 8         | 1.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 7         | 1.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 6         | 1.15%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s  | 5         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 4         | 0.77%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 4         | 0.77%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 4         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s     | 4         | 0.77%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 4         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 4         | 0.77%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s   | 4         | 0.77%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s               | 3         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 3         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 3         | 0.57%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 3         | 0.57%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s     | 3         | 0.57%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 0.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 3         | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s     | 3         | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 3         | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 3         | 0.57%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s | 3         | 0.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 3         | 0.57%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 3         | 0.57%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s         | 3         | 0.57%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s     | 3         | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2         | 0.38%   |
| Unknown RAM Module 4096MB DIMM SDRAM                      | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 2         | 0.38%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 2         | 0.38%   |
| Unknown RAM Module 2048MB DIMM SDRAM                      | 2         | 0.38%   |
| Unknown RAM Module 1024MB SODIMM DDR                      | 2         | 0.38%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s       | 2         | 0.38%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s      | 2         | 0.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s              | 2         | 0.38%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                | 2         | 0.38%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s             | 2         | 0.38%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.38%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 168       | 42%     |
| DDR4    | 163       | 40.75%  |
| DDR2    | 25        | 6.25%   |
| SDRAM   | 14        | 3.5%    |
| Unknown | 13        | 3.25%   |
| LPDDR3  | 6         | 1.5%    |
| DDR     | 5         | 1.25%   |
| LPDDR4  | 3         | 0.75%   |
| DRAM    | 2         | 0.5%    |
| LPDDR5  | 1         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 236       | 59.75%  |
| DIMM         | 145       | 36.71%  |
| Row Of Chips | 8         | 2.03%   |
| Chip         | 4         | 1.01%   |
| RIMM         | 1         | 0.25%   |
| FB-DIMM      | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 148       | 34.42%  |
| 8192    | 130       | 30.23%  |
| 2048    | 57        | 13.26%  |
| 16384   | 55        | 12.79%  |
| 1024    | 20        | 4.65%   |
| 32768   | 15        | 3.49%   |
| 512     | 3         | 0.7%    |
| 256     | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 110       | 24.89%  |
| 2667    | 67        | 15.16%  |
| 3200    | 44        | 9.95%   |
| 1333    | 38        | 8.6%    |
| 2400    | 28        | 6.33%   |
| 1334    | 24        | 5.43%   |
| 2133    | 16        | 3.62%   |
| 800     | 15        | 3.39%   |
| Unknown | 14        | 3.17%   |
| 667     | 12        | 2.71%   |
| 3600    | 10        | 2.26%   |
| 1867    | 6         | 1.36%   |
| 3266    | 5         | 1.13%   |
| 3466    | 4         | 0.9%    |
| 3000    | 4         | 0.9%    |
| 333     | 4         | 0.9%    |
| 3800    | 3         | 0.68%   |
| 2666    | 3         | 0.68%   |
| 1067    | 3         | 0.68%   |
| 1066    | 3         | 0.68%   |
| 4199    | 2         | 0.45%   |
| 3400    | 2         | 0.45%   |
| 3333    | 2         | 0.45%   |
| 2933    | 2         | 0.45%   |
| 2800    | 2         | 0.45%   |
| 1866    | 2         | 0.45%   |
| 1800    | 2         | 0.45%   |
| 975     | 2         | 0.45%   |
| 57535   | 1         | 0.23%   |
| 6400    | 1         | 0.23%   |
| 4267    | 1         | 0.23%   |
| 3733    | 1         | 0.23%   |
| 3467    | 1         | 0.23%   |
| 3066    | 1         | 0.23%   |
| 2481    | 1         | 0.23%   |
| 2200    | 1         | 0.23%   |
| 2048    | 1         | 0.23%   |
| 2000    | 1         | 0.23%   |
| 1639    | 1         | 0.23%   |
| 533     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 33.33%  |
| Brother Industries  | 4         | 22.22%  |
| Samsung Electronics | 3         | 16.67%  |
| Xerox               | 2         | 11.11%  |
| Kyocera             | 1         | 5.56%   |
| Canon               | 1         | 5.56%   |
| ATEN International  | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP LaserJet 1020                         | 2         | 11.11%  |
| Xerox Phaser 3140 and 3155               | 1         | 5.56%   |
| Xerox Phaser 3020                        | 1         | 5.56%   |
| Samsung ML-2010P Mono Laser Printer      | 1         | 5.56%   |
| Samsung M332x 382x 402x Series           | 1         | 5.56%   |
| Samsung M267x 287x Series                | 1         | 5.56%   |
| Kyocera ECOSYS P2040dn                   | 1         | 5.56%   |
| HP LaserJet Professional P1566           | 1         | 5.56%   |
| HP LaserJet P1102                        | 1         | 5.56%   |
| HP LaserJet 4350                         | 1         | 5.56%   |
| HP DeskJet 4530 series                   | 1         | 5.56%   |
| Canon PIXMA MP240                        | 1         | 5.56%   |
| Brother Printer                          | 1         | 5.56%   |
| Brother MFC-B7715DW series               | 1         | 5.56%   |
| Brother DCP-T300                         | 1         | 5.56%   |
| Brother DCP-7055 scanner/printer         | 1         | 5.56%   |
| ATEN International UC-1284B Printer Port | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 2         | 66.67%  |
| Mustek Systems | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22        | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 110            | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 123       | 25.63%  |
| IMC Networks                           | 53        | 11.04%  |
| Microdia                               | 44        | 9.17%   |
| Realtek Semiconductor                  | 40        | 8.33%   |
| Acer                                   | 38        | 7.92%   |
| Sunplus Innovation Technology          | 29        | 6.04%   |
| Quanta                                 | 23        | 4.79%   |
| Lite-On Technology                     | 15        | 3.13%   |
| Suyin                                  | 13        | 2.71%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 2.71%   |
| Logitech                               | 12        | 2.5%    |
| Syntek                                 | 10        | 2.08%   |
| Z-Star Microelectronics                | 9         | 1.88%   |
| Alcor Micro                            | 7         | 1.46%   |
| Microsoft                              | 6         | 1.25%   |
| Silicon Motion                         | 5         | 1.04%   |
| Apple                                  | 5         | 1.04%   |
| Samsung Electronics                    | 3         | 0.63%   |
| Luxvisions Innotech Limited            | 3         | 0.63%   |
| DJKANA19IDX53W                         | 3         | 0.63%   |
| Ricoh                                  | 2         | 0.42%   |
| Lenovo                                 | 2         | 0.42%   |
| Importek                               | 2         | 0.42%   |
| Hewlett-Packard                        | 2         | 0.42%   |
| Creative Technology                    | 2         | 0.42%   |
| Alpha Imaging Technology               | 2         | 0.42%   |
| Unknown                                | 1         | 0.21%   |
| Sunplus Technology                     | 1         | 0.21%   |
| Sonix Technology                       | 1         | 0.21%   |
| Razer USA                              | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| Pixart Imaging                         | 1         | 0.21%   |
| Google                                 | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |
| GEMBIRD                                | 1         | 0.21%   |
| Divio                                  | 1         | 0.21%   |
| Aveo Technology                        | 1         | 0.21%   |
| Arkmicro Technologies                  | 1         | 0.21%   |
| ALi                                    | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 24        | 5%      |
| IMC Networks USB2.0 VGA UVC WebCam       | 19        | 3.96%   |
| IMC Networks Integrated Camera           | 16        | 3.33%   |
| Chicony HD Webcam                        | 14        | 2.92%   |
| Realtek Integrated_Webcam_HD             | 11        | 2.29%   |
| Microdia Integrated_Webcam_HD            | 10        | 2.08%   |
| Acer Integrated Camera                   | 9         | 1.88%   |
| Sunplus Integrated_Webcam_HD             | 8         | 1.67%   |
| Acer SunplusIT Integrated Camera         | 8         | 1.67%   |
| Realtek Lenovo EasyCamera                | 7         | 1.46%   |
| Chicony TOSHIBA Web Camera - HD          | 7         | 1.46%   |
| Chicony USB 2.0 Camera                   | 6         | 1.25%   |
| Acer Lenovo EasyCamera                   | 6         | 1.25%   |
| Quanta HP HD Camera                      | 5         | 1.04%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 5         | 1.04%   |
| Chicony HD WebCam (Asus N-series)        | 5         | 1.04%   |
| Z-Star A4 TECH HD PC Camera              | 4         | 0.83%   |
| Quanta HP TrueVision HD Camera           | 4         | 0.83%   |
| Quanta HD Webcam                         | 4         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_HD     | 4         | 0.83%   |
| Microdia Integrated Webcam               | 4         | 0.83%   |
| Logitech Webcam C270                     | 4         | 0.83%   |
| Lite-On Integrated Camera                | 4         | 0.83%   |
| Lite-On HP HD Webcam                     | 4         | 0.83%   |
| IMC Networks USB2.0 HD UVC WebCam        | 4         | 0.83%   |
| Chicony USB2.0 VGA UVC WebCam            | 4         | 0.83%   |
| Chicony Lenovo EasyCamera                | 4         | 0.83%   |
| Chicony HP HD Webcam                     | 4         | 0.83%   |
| Alcor Micro Acer Integrated Webcam       | 4         | 0.83%   |
| Z-Star Venus USB2.0 Camera               | 3         | 0.63%   |
| Syntek Lenovo EasyCamera                 | 3         | 0.63%   |
| Syntek Integrated Camera                 | 3         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 3         | 0.63%   |
| Sunplus Laptop Integrated Webcam HD      | 3         | 0.63%   |
| Sunplus HP HD Webcam [Fixed]             | 3         | 0.63%   |
| Sunplus HD WebCam                        | 3         | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)  | 3         | 0.63%   |
| Quanta HD User Facing                    | 3         | 0.63%   |
| Microsoft LifeCam HD-3000                | 3         | 0.63%   |
| Microdia Dell Integrated HD Webcam       | 3         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 37        | 39.78%  |
| Synaptics                  | 25        | 26.88%  |
| AuthenTec                  | 12        | 12.9%   |
| Shenzhen Goodix Technology | 6         | 6.45%   |
| Elan Microelectronics      | 5         | 5.38%   |
| Upek                       | 4         | 4.3%    |
| LighTuning Technology      | 3         | 3.23%   |
| STMicroelectronics         | 1         | 1.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 12.9%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 10.75%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 5.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 5.38%   |
| AuthenTec AES2810                                                          | 5         | 5.38%   |
| Unknown                                                                    | 5         | 5.38%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 4.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.3%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 4.3%    |
| AuthenTec Fingerprint Sensor                                               | 4         | 4.3%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.23%   |
| Elan ELAN:ARM-M4                                                           | 3         | 3.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 2.15%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.15%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.15%   |
| Validity Sensors VFS491                                                    | 2         | 2.15%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.15%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.15%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.15%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.15%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.15%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.08%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.08%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 1.08%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.08%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.08%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.08%   |
| AuthenTec AES1600                                                          | 1         | 1.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 36.21%  |
| Alcor Micro           | 19        | 32.76%  |
| O2 Micro              | 5         | 8.62%   |
| Lenovo                | 4         | 6.9%    |
| Upek                  | 3         | 5.17%   |
| SCM Microsystems      | 2         | 3.45%   |
| OmniKey               | 2         | 3.45%   |
| Advanced Card Systems | 2         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 32.76%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 15.52%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 8.62%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.9%    |
| Broadcom 5880                                                                | 4         | 6.9%    |
| Broadcom 58200                                                               | 4         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.17%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 3.45%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 3.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.72%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.72%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 551       | 67.86%  |
| 1     | 205       | 25.25%  |
| 2     | 51        | 6.28%   |
| 3     | 3         | 0.37%   |
| 7     | 1         | 0.12%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 93        | 30.39%  |
| Graphics card            | 64        | 20.92%  |
| Chipcard                 | 46        | 15.03%  |
| Net/wireless             | 24        | 7.84%   |
| Multimedia controller    | 16        | 5.23%   |
| Bluetooth                | 13        | 4.25%   |
| Unassigned class         | 8         | 2.61%   |
| Storage                  | 8         | 2.61%   |
| Communication controller | 8         | 2.61%   |
| Camera                   | 7         | 2.29%   |
| Card reader              | 5         | 1.63%   |
| Net/ethernet             | 4         | 1.31%   |
| Sound                    | 3         | 0.98%   |
| Firewire controller      | 3         | 0.98%   |
| Modem                    | 2         | 0.65%   |
| Storage/ata              | 1         | 0.33%   |
| Flash memory             | 1         | 0.33%   |


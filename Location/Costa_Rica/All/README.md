Linux in Costa Rica - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Costa_Rica/Desktop/README.md) and [notebooks](/Location/Costa_Rica/Notebook/README.md).

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

Total: 515

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [a40f8a9531](https://linux-hardware.org/?probe=a40f8a9531) | Jan 05, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [b2c0345c76](https://linux-hardware.org/?probe=b2c0345c76) | Dec 24, 2024 |
| Unknown       | ROUTER                      | Desktop     | [c6bf9058fa](https://linux-hardware.org/?probe=c6bf9058fa) | Dec 10, 2024 |
| Acer          | Aspire V5-472               | Notebook    | [4f7f3b1702](https://linux-hardware.org/?probe=4f7f3b1702) | Dec 05, 2024 |
| Acer          | Aspire V5-472               | Notebook    | [f653a24c52](https://linux-hardware.org/?probe=f653a24c52) | Dec 05, 2024 |
| Raspberry ... | Raspberry Pi                | Soc         | [e8945744cb](https://linux-hardware.org/?probe=e8945744cb) | Dec 03, 2024 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [916a95ba5f](https://linux-hardware.org/?probe=916a95ba5f) | Dec 03, 2024 |
| Google        | Kefka                       | Notebook    | [1bab1809fc](https://linux-hardware.org/?probe=1bab1809fc) | Nov 27, 2024 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [073b6e567f](https://linux-hardware.org/?probe=073b6e567f) | Nov 26, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6a69e8dd2b](https://linux-hardware.org/?probe=6a69e8dd2b) | Nov 14, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [c3a615acb3](https://linux-hardware.org/?probe=c3a615acb3) | Nov 12, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [cb6f1609b1](https://linux-hardware.org/?probe=cb6f1609b1) | Oct 27, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [6028ccb88f](https://linux-hardware.org/?probe=6028ccb88f) | Oct 25, 2024 |
| Dell          | Latitude E5470              | Notebook    | [430ace52f3](https://linux-hardware.org/?probe=430ace52f3) | Oct 24, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [6e69e5e4a4](https://linux-hardware.org/?probe=6e69e5e4a4) | Oct 23, 2024 |
| HP            | ProBook 4510s               | Notebook    | [82921bfaa3](https://linux-hardware.org/?probe=82921bfaa3) | Oct 16, 2024 |
| HP            | Notebook                    | Notebook    | [5d34e36859](https://linux-hardware.org/?probe=5d34e36859) | Oct 12, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [f6fa0c5195](https://linux-hardware.org/?probe=f6fa0c5195) | Oct 12, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [8867a3f043](https://linux-hardware.org/?probe=8867a3f043) | Oct 05, 2024 |
| Dell          | Latitude 7420               | Notebook    | [bdec0be003](https://linux-hardware.org/?probe=bdec0be003) | Sep 30, 2024 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [00f803e8a2](https://linux-hardware.org/?probe=00f803e8a2) | Sep 18, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [9facb5b04a](https://linux-hardware.org/?probe=9facb5b04a) | Sep 17, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [a60bab1d76](https://linux-hardware.org/?probe=a60bab1d76) | Sep 16, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [a2e4ae9bf4](https://linux-hardware.org/?probe=a2e4ae9bf4) | Sep 16, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [606582cd82](https://linux-hardware.org/?probe=606582cd82) | Sep 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b92c75fb55](https://linux-hardware.org/?probe=b92c75fb55) | Aug 26, 2024 |
| HP            | EliteBook 8540w             | Notebook    | [37bf22daf9](https://linux-hardware.org/?probe=37bf22daf9) | Aug 16, 2024 |
| HP            | EliteBook 8540w             | Notebook    | [e96ce0732d](https://linux-hardware.org/?probe=e96ce0732d) | Aug 16, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3b88a5d126](https://linux-hardware.org/?probe=3b88a5d126) | Aug 14, 2024 |
| Pegatron      | 2AE4                        | Desktop     | [db698b9ba0](https://linux-hardware.org/?probe=db698b9ba0) | Jul 31, 2024 |
| Acer          | Aspire 5742                 | Notebook    | [280430e59d](https://linux-hardware.org/?probe=280430e59d) | Jul 30, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ed33f895c9](https://linux-hardware.org/?probe=ed33f895c9) | Jul 28, 2024 |
| Samsung       | 700T1C                      | Notebook    | [33a6415fdc](https://linux-hardware.org/?probe=33a6415fdc) | Jul 07, 2024 |
| Toshiba       | Satellite L755              | Notebook    | [f146c7cd82](https://linux-hardware.org/?probe=f146c7cd82) | Jul 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [845660f83a](https://linux-hardware.org/?probe=845660f83a) | Jul 06, 2024 |
| Acer          | Aspire E1-431               | Notebook    | [7927c359f4](https://linux-hardware.org/?probe=7927c359f4) | Jul 05, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [b749879a8b](https://linux-hardware.org/?probe=b749879a8b) | Jul 04, 2024 |
| TCL Commun... | 8085                        | Notebook    | [e0f28c27e1](https://linux-hardware.org/?probe=e0f28c27e1) | Jul 03, 2024 |
| TCL Commun... | 8085                        | Notebook    | [9163504543](https://linux-hardware.org/?probe=9163504543) | Jul 03, 2024 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [91276fd4b3](https://linux-hardware.org/?probe=91276fd4b3) | Jul 02, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7c6efb1095](https://linux-hardware.org/?probe=7c6efb1095) | Jun 30, 2024 |
| Dell          | Inspiron N4010              | Notebook    | [dad60b8122](https://linux-hardware.org/?probe=dad60b8122) | Jun 20, 2024 |
| Gigabyte      | B560M GAMING HD             | Desktop     | [c93b542abf](https://linux-hardware.org/?probe=c93b542abf) | Jun 19, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [2639f09193](https://linux-hardware.org/?probe=2639f09193) | Jun 19, 2024 |
| HP            | 83F2                        | Desktop     | [e802a9a41a](https://linux-hardware.org/?probe=e802a9a41a) | Jun 03, 2024 |
| Dell          | Latitude 7410               | Notebook    | [51a29349b7](https://linux-hardware.org/?probe=51a29349b7) | Jun 02, 2024 |
| Dell          | Latitude E5470              | Notebook    | [0471527291](https://linux-hardware.org/?probe=0471527291) | May 30, 2024 |
| Dell          | Latitude E5470              | Notebook    | [cb017d9ab6](https://linux-hardware.org/?probe=cb017d9ab6) | May 29, 2024 |
| Dell          | 0VD5HY A07                  | Desktop     | [a64b949879](https://linux-hardware.org/?probe=a64b949879) | May 28, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [35684afb98](https://linux-hardware.org/?probe=35684afb98) | May 28, 2024 |
| Unknown       | Unknown                     | Notebook    | [c9abc346e8](https://linux-hardware.org/?probe=c9abc346e8) | May 27, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [134bad9ba1](https://linux-hardware.org/?probe=134bad9ba1) | May 25, 2024 |
| Samsung       | 930X2K/931X2K               | Notebook    | [f69d6ceb2c](https://linux-hardware.org/?probe=f69d6ceb2c) | May 23, 2024 |
| Samsung       | 930X2K/931X2K               | Notebook    | [032615adcb](https://linux-hardware.org/?probe=032615adcb) | May 23, 2024 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [001ab54ab1](https://linux-hardware.org/?probe=001ab54ab1) | May 23, 2024 |
| Dell          | 0HD5K4 A00                  | All in one  | [894acb25c5](https://linux-hardware.org/?probe=894acb25c5) | May 20, 2024 |
| HP            | Notebook                    | Notebook    | [143a137ce0](https://linux-hardware.org/?probe=143a137ce0) | May 17, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [94f1e2e58a](https://linux-hardware.org/?probe=94f1e2e58a) | May 16, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [c3d53b2f3a](https://linux-hardware.org/?probe=c3d53b2f3a) | May 13, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | Notebook    | [a0a81ab433](https://linux-hardware.org/?probe=a0a81ab433) | May 11, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [ac1a840bb3](https://linux-hardware.org/?probe=ac1a840bb3) | May 10, 2024 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [a79d33d7cf](https://linux-hardware.org/?probe=a79d33d7cf) | May 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [f6c6a3c2cb](https://linux-hardware.org/?probe=f6c6a3c2cb) | Apr 28, 2024 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [a9c83df6f3](https://linux-hardware.org/?probe=a9c83df6f3) | Apr 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | Notebook    | [0ccf03f0d9](https://linux-hardware.org/?probe=0ccf03f0d9) | Apr 13, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [ab1cbc61a9](https://linux-hardware.org/?probe=ab1cbc61a9) | Mar 30, 2024 |
| Valve         | Jupiter                     | Notebook    | [a4d5199429](https://linux-hardware.org/?probe=a4d5199429) | Mar 23, 2024 |
| Unknown       | WY133A                      | Notebook    | [de159f4170](https://linux-hardware.org/?probe=de159f4170) | Mar 20, 2024 |
| Unknown       | WY133A                      | Notebook    | [1abe291a71](https://linux-hardware.org/?probe=1abe291a71) | Mar 20, 2024 |
| Dell          | 0WMJ54 A00                  | Desktop     | [306aac13ae](https://linux-hardware.org/?probe=306aac13ae) | Mar 18, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [4cfd0ba254](https://linux-hardware.org/?probe=4cfd0ba254) | Mar 13, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [5035a532a3](https://linux-hardware.org/?probe=5035a532a3) | Mar 11, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JSS... | Notebook    | [b136a57d61](https://linux-hardware.org/?probe=b136a57d61) | Mar 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [644841f4df](https://linux-hardware.org/?probe=644841f4df) | Mar 07, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [abfba381b6](https://linux-hardware.org/?probe=abfba381b6) | Mar 02, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5d03e50172](https://linux-hardware.org/?probe=5d03e50172) | Mar 02, 2024 |
| EVOO          | EV-C-125-3                  | Notebook    | [d452f3776a](https://linux-hardware.org/?probe=d452f3776a) | Feb 26, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [997fde90ec](https://linux-hardware.org/?probe=997fde90ec) | Feb 26, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [49371cd72c](https://linux-hardware.org/?probe=49371cd72c) | Feb 23, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7f26beabd5](https://linux-hardware.org/?probe=7f26beabd5) | Feb 17, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [496f8751d2](https://linux-hardware.org/?probe=496f8751d2) | Feb 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [8888984d3d](https://linux-hardware.org/?probe=8888984d3d) | Feb 14, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [d72d6f6951](https://linux-hardware.org/?probe=d72d6f6951) | Feb 09, 2024 |
| Intel         | NUC13SBBi7 M89885-303       | Mini pc     | [f096c5fea7](https://linux-hardware.org/?probe=f096c5fea7) | Feb 09, 2024 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [ff633ac02f](https://linux-hardware.org/?probe=ff633ac02f) | Feb 07, 2024 |
| Acer          | Aspire E5-473               | Notebook    | [0a294c97ee](https://linux-hardware.org/?probe=0a294c97ee) | Jan 31, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d1065a1aca](https://linux-hardware.org/?probe=d1065a1aca) | Jan 30, 2024 |
| HP            | Pavilion g4                 | Notebook    | [1edc58a524](https://linux-hardware.org/?probe=1edc58a524) | Jan 22, 2024 |
| ZOTAC         | NM10                        | Desktop     | [e185a9b292](https://linux-hardware.org/?probe=e185a9b292) | Jan 18, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [f118f7960d](https://linux-hardware.org/?probe=f118f7960d) | Jan 18, 2024 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [bece296ba4](https://linux-hardware.org/?probe=bece296ba4) | Jan 15, 2024 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [6eb80a3aae](https://linux-hardware.org/?probe=6eb80a3aae) | Jan 15, 2024 |
| GPU Compan... | GWTN141-10                  | Notebook    | [cd417ed644](https://linux-hardware.org/?probe=cd417ed644) | Jan 10, 2024 |
| GPU Compan... | GWTN141-10                  | Notebook    | [443e0e2a67](https://linux-hardware.org/?probe=443e0e2a67) | Jan 04, 2024 |
| HP            | G60                         | Notebook    | [a151a8084c](https://linux-hardware.org/?probe=a151a8084c) | Jan 01, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4e00c088e8](https://linux-hardware.org/?probe=4e00c088e8) | Dec 29, 2023 |
| Lenovo        | Annapurna CRB NO DPK        | Desktop     | [7d003c702a](https://linux-hardware.org/?probe=7d003c702a) | Dec 27, 2023 |
| Lenovo        | ThinkPad T420 4236DA4       | Notebook    | [1188c1619d](https://linux-hardware.org/?probe=1188c1619d) | Dec 20, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| Dell          | G15 5515                    | Notebook    | [259739c8b5](https://linux-hardware.org/?probe=259739c8b5) | Dec 14, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [a73b0c39f2](https://linux-hardware.org/?probe=a73b0c39f2) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [b569f37962](https://linux-hardware.org/?probe=b569f37962) | Dec 11, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6b350f2aaf](https://linux-hardware.org/?probe=6b350f2aaf) | Dec 11, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c723bcc62a](https://linux-hardware.org/?probe=c723bcc62a) | Dec 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [7d8d9279cd](https://linux-hardware.org/?probe=7d8d9279cd) | Nov 21, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [7045b84f52](https://linux-hardware.org/?probe=7045b84f52) | Nov 21, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [af8edff0b6](https://linux-hardware.org/?probe=af8edff0b6) | Nov 15, 2023 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [d7e062f534](https://linux-hardware.org/?probe=d7e062f534) | Nov 15, 2023 |
| Toshiba       | Satellite L845              | Notebook    | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| ZOTAC         | NM10                        | Desktop     | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [9266111091](https://linux-hardware.org/?probe=9266111091) | Oct 27, 2023 |
| HP            | 3047h                       | Desktop     | [cdd7fbc37f](https://linux-hardware.org/?probe=cdd7fbc37f) | Oct 25, 2023 |
| HP            | 3047h                       | Desktop     | [4235f287b2](https://linux-hardware.org/?probe=4235f287b2) | Oct 25, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| ZOTAC         | NM10                        | Desktop     | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d8335b95a8](https://linux-hardware.org/?probe=d8335b95a8) | Oct 19, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [d1d30ae371](https://linux-hardware.org/?probe=d1d30ae371) | Oct 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ae4ee327c0](https://linux-hardware.org/?probe=ae4ee327c0) | Oct 06, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [14ac97b405](https://linux-hardware.org/?probe=14ac97b405) | Oct 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [92e214fb3e](https://linux-hardware.org/?probe=92e214fb3e) | Oct 04, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [a814d9fa4b](https://linux-hardware.org/?probe=a814d9fa4b) | Sep 25, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [ef531e70d1](https://linux-hardware.org/?probe=ef531e70d1) | Sep 22, 2023 |
| HP            | Mini 110-1000               | Notebook    | [dda4d7a910](https://linux-hardware.org/?probe=dda4d7a910) | Sep 18, 2023 |
| HP            | Mini 110-1000               | Notebook    | [ee2d142228](https://linux-hardware.org/?probe=ee2d142228) | Sep 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c7b5f9224a](https://linux-hardware.org/?probe=c7b5f9224a) | Sep 17, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [a66fcc9edb](https://linux-hardware.org/?probe=a66fcc9edb) | Sep 11, 2023 |
| Sony          | SVE14123CLW                 | Notebook    | [2fffba7739](https://linux-hardware.org/?probe=2fffba7739) | Sep 08, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [3b740d65f2](https://linux-hardware.org/?probe=3b740d65f2) | Sep 04, 2023 |
| Dell          | 0RW203 A00                  | Desktop     | [0c76c5a1a7](https://linux-hardware.org/?probe=0c76c5a1a7) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [40693c0171](https://linux-hardware.org/?probe=40693c0171) | Aug 29, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [65bf0970da](https://linux-hardware.org/?probe=65bf0970da) | Aug 27, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ae48a8c618](https://linux-hardware.org/?probe=ae48a8c618) | Aug 26, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d25700c10e](https://linux-hardware.org/?probe=d25700c10e) | Aug 16, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [9c2b1b1da7](https://linux-hardware.org/?probe=9c2b1b1da7) | Aug 06, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [a0394c8f0b](https://linux-hardware.org/?probe=a0394c8f0b) | Jul 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [ec5a50d1d8](https://linux-hardware.org/?probe=ec5a50d1d8) | Jul 29, 2023 |
| ASUSTek       | Q551LN                      | Notebook    | [ad2abcddcf](https://linux-hardware.org/?probe=ad2abcddcf) | Jul 27, 2023 |
| Foxconn       | nT-iBT18/nT-iBT19/nT-iBT... | Desktop     | [23633cafce](https://linux-hardware.org/?probe=23633cafce) | Jul 27, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4e99483733](https://linux-hardware.org/?probe=4e99483733) | Jul 13, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [cb309977d0](https://linux-hardware.org/?probe=cb309977d0) | Jul 08, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [607d40a328](https://linux-hardware.org/?probe=607d40a328) | Jul 04, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [7dffb9055b](https://linux-hardware.org/?probe=7dffb9055b) | Jun 29, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [638d6b4ef3](https://linux-hardware.org/?probe=638d6b4ef3) | Jun 27, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [06f1256f88](https://linux-hardware.org/?probe=06f1256f88) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [3e3987b43f](https://linux-hardware.org/?probe=3e3987b43f) | Jun 20, 2023 |
| HP            | ENVY 15                     | Notebook    | [101fb8810b](https://linux-hardware.org/?probe=101fb8810b) | Jun 19, 2023 |
| HP            | Notebook                    | Notebook    | [42558904aa](https://linux-hardware.org/?probe=42558904aa) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1aa286ccff](https://linux-hardware.org/?probe=1aa286ccff) | Jun 03, 2023 |
| HP            | Notebook                    | Notebook    | [c246477ea2](https://linux-hardware.org/?probe=c246477ea2) | May 31, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [360e8fd5e5](https://linux-hardware.org/?probe=360e8fd5e5) | May 30, 2023 |
| HP            | Notebook                    | Notebook    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [5875771b0c](https://linux-hardware.org/?probe=5875771b0c) | May 24, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [50283ef123](https://linux-hardware.org/?probe=50283ef123) | May 24, 2023 |
| ZOTAC         | NM10                        | Desktop     | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ba104d9250](https://linux-hardware.org/?probe=ba104d9250) | May 10, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b06388c1f4](https://linux-hardware.org/?probe=b06388c1f4) | May 09, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| HP            | ProBook 6570b               | Notebook    | [2b01f67020](https://linux-hardware.org/?probe=2b01f67020) | Apr 14, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [126c7a430c](https://linux-hardware.org/?probe=126c7a430c) | Apr 13, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [80d44eb98b](https://linux-hardware.org/?probe=80d44eb98b) | Apr 12, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [8b4666305d](https://linux-hardware.org/?probe=8b4666305d) | Apr 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| Google        | Snappy                      | Notebook    | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| ASRock        | 970 Extreme3                | Desktop     | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Acer          | Aspire E1-431               | Notebook    | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [d8fee2b6b1](https://linux-hardware.org/?probe=d8fee2b6b1) | Mar 08, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [3479df4ab9](https://linux-hardware.org/?probe=3479df4ab9) | Feb 26, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [b02e34a7f9](https://linux-hardware.org/?probe=b02e34a7f9) | Feb 25, 2023 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [0649eea8a9](https://linux-hardware.org/?probe=0649eea8a9) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [d6fea43eb5](https://linux-hardware.org/?probe=d6fea43eb5) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [4995c8c687](https://linux-hardware.org/?probe=4995c8c687) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cc2d26e52e](https://linux-hardware.org/?probe=cc2d26e52e) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8761a4096a](https://linux-hardware.org/?probe=8761a4096a) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7099ccff2f](https://linux-hardware.org/?probe=7099ccff2f) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [927415e3d5](https://linux-hardware.org/?probe=927415e3d5) | Jan 07, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [46ea5b81b7](https://linux-hardware.org/?probe=46ea5b81b7) | Jan 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| Jumper        | EZpad                       | Tablet      | [cfa761d534](https://linux-hardware.org/?probe=cfa761d534) | Jan 03, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [b1a7532cf1](https://linux-hardware.org/?probe=b1a7532cf1) | Dec 23, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [173dde2177](https://linux-hardware.org/?probe=173dde2177) | Dec 14, 2022 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [09129dad50](https://linux-hardware.org/?probe=09129dad50) | Nov 28, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [88ca303518](https://linux-hardware.org/?probe=88ca303518) | Nov 28, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [f278eb7e59](https://linux-hardware.org/?probe=f278eb7e59) | Nov 27, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | Notebook    | [a6f536ca3d](https://linux-hardware.org/?probe=a6f536ca3d) | Oct 25, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | Notebook    | [813bd112f8](https://linux-hardware.org/?probe=813bd112f8) | Oct 25, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [5d789a1783](https://linux-hardware.org/?probe=5d789a1783) | Sep 28, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [1bb8ad599d](https://linux-hardware.org/?probe=1bb8ad599d) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [b49d726ab0](https://linux-hardware.org/?probe=b49d726ab0) | Sep 03, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [ee80be714e](https://linux-hardware.org/?probe=ee80be714e) | Sep 03, 2022 |
| ASRock        | N68-S UCC                   | Desktop     | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | G3 3579                     | Notebook    | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fb77adfb99](https://linux-hardware.org/?probe=fb77adfb99) | Aug 16, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad        | Unknown                     | Notebook    | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo        | ThinkPad P50 20EN001PUS     | Notebook    | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [46afe6a354](https://linux-hardware.org/?probe=46afe6a354) | Jun 02, 2022 |
| Lenovo        | ThinkPad T440s 20ARS29U0... | Notebook    | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Dell          | Latitude 7400               | Notebook    | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Lenovo        | ThinkPad L420 7829AA4       | Notebook    | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP            | 0AECh D                     | Desktop     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| HP            | 83EE                        | Desktop     | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Latitude E5500              | Notebook    | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell          | Latitude E5500              | Notebook    | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony          | SVD13215PLB                 | Notebook    | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Samsung       | 930QAA                      | Convertible | [56758d8bfb](https://linux-hardware.org/?probe=56758d8bfb) | Jan 10, 2022 |
| Samsung       | 930QAA                      | Convertible | [206f508be5](https://linux-hardware.org/?probe=206f508be5) | Jan 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6837cca618](https://linux-hardware.org/?probe=6837cca618) | Jan 02, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                    | Desktop     | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                        | Desktop     | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                        | Desktop     | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                    | Desktop     | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| Dell          | Latitude 5490               | Notebook    | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell          | Inspiron 3595               | Notebook    | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell          | Latitude D620               | Notebook    | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| ZOTAC         | NM10                        | Desktop     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [29a6b45091](https://linux-hardware.org/?probe=29a6b45091) | Sep 26, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [5ed9f083e1](https://linux-hardware.org/?probe=5ed9f083e1) | Sep 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI           | GF75 Thin 9SD               | Notebook    | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                      | Desktop     | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Olivetti      | CL133A                      | Notebook    | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW           | GT-R                        | Notebook    | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Olivetti      | CL133A                      | Notebook    | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek       | U46E                        | Notebook    | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP            | ProBook 6460b               | Notebook    | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell          | G3 3590                     | Notebook    | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti      | CL133A                      | Notebook    | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | Notebook    | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [9e01fd5e8c](https://linux-hardware.org/?probe=9e01fd5e8c) | Jun 20, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [e937e8ba7e](https://linux-hardware.org/?probe=e937e8ba7e) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [2d1d9030e8](https://linux-hardware.org/?probe=2d1d9030e8) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Intel         | D33217CK G76541-302         | Desktop     | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                       | Desktop     | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Dell          | G3 3590                     | Notebook    | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP            | Pavilion g4                 | Notebook    | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown       | Unknown                     | Notebook    | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google        | Celes                       | Notebook    | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell          | Precision M4800             | Notebook    | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP            | Laptop 14-bp0xx             | Notebook    | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01                  | Desktop     | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell          | Latitude 7480               | Notebook    | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell          | Latitude 7480               | Notebook    | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| HP            | 2B54 100                    | All in one  | [161455efd7](https://linux-hardware.org/?probe=161455efd7) | Oct 17, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell          | G3 3590                     | Notebook    | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP            | Unknown                     | Notebook    | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | 2B54 100                    | All in one  | [8e21d2bb01](https://linux-hardware.org/?probe=8e21d2bb01) | Sep 06, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Acer          | Aspire 4739Z                | Notebook    | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Dell          | Latitude E5440              | Notebook    | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Gateway       | FMCP7AM                     | Desktop     | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                    | Desktop     | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| Dell          | G3 3590                     | Notebook    | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| ASRock        | B450 Steel Legend           | Desktop     | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| HP            | ProBook 455 G4              | Notebook    | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [3c2d508fc2](https://linux-hardware.org/?probe=3c2d508fc2) | Apr 23, 2020 |
| HP            | Notebook                    | Notebook    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer          | Aspire V3-471               | Notebook    | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell          | G3 3590                     | Notebook    | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [fcea840696](https://linux-hardware.org/?probe=fcea840696) | Mar 04, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [9398ebaa03](https://linux-hardware.org/?probe=9398ebaa03) | Feb 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [1419b6c5e7](https://linux-hardware.org/?probe=1419b6c5e7) | Feb 29, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP            | ProBook 6460b               | Notebook    | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell          | Latitude 5500               | Notebook    | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek       | K52F                        | Notebook    | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [750ccde7c5](https://linux-hardware.org/?probe=750ccde7c5) | Jan 19, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [5662d620a5](https://linux-hardware.org/?probe=5662d620a5) | Jan 03, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [bd9a062902](https://linux-hardware.org/?probe=bd9a062902) | Jan 03, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| Dell          | 042P49 A01                  | Desktop     | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| System76      | Lemur                       | Notebook    | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| HP            | ProBook 450 G2              | Notebook    | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP            | Notebook                    | Notebook    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76      | Lemur                       | Notebook    | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP            | Notebook                    | Notebook    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP            | Notebook                    | Notebook    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell          | Latitude E5450              | Notebook    | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba       | Satellite A305D             | Notebook    | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer          | SW5-017P                    | Notebook    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell          | Latitude 5480               | Notebook    | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell          | Latitude 5480               | Notebook    | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Lenovo        | SHARKBAY 31900003 STD       | Desktop     | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek       | X555LAB                     | Notebook    | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba       | Satellite C645D             | Notebook    | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Costa_Rica/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 25        | 6.76%   |
| Ubuntu 22.04                 | 21        | 5.68%   |
| Ubuntu 18.04                 | 18        | 4.86%   |
| OpenMandriva 4.2             | 16        | 4.32%   |
| Debian 12                    | 12        | 3.24%   |
| Zorin 16                     | 9         | 2.43%   |
| OpenMandriva 4.3             | 7         | 1.89%   |
| OpenMandriva 23.03           | 7         | 1.89%   |
| OpenMandriva 23.01           | 7         | 1.89%   |
| Zorin 17                     | 5         | 1.35%   |
| Ubuntu 24.04                 | 5         | 1.35%   |
| Lubuntu 22.04                | 5         | 1.35%   |
| Fedora 38                    | 5         | 1.35%   |
| Debian 11                    | 5         | 1.35%   |
| Ubuntu 19.04                 | 4         | 1.08%   |
| Pop!_OS 22.04                | 4         | 1.08%   |
| OpenMandriva 23.08           | 4         | 1.08%   |
| Manjaro                      | 4         | 1.08%   |
| Lubuntu 24.04                | 4         | 1.08%   |
| Lubuntu 21.10                | 4         | 1.08%   |
| Linux Mint 20.2              | 4         | 1.08%   |
| Linux Mint 19.3              | 4         | 1.08%   |
| Kubuntu 23.10                | 4         | 1.08%   |
| Fedora 36                    | 4         | 1.08%   |
| Ubuntu 23.04                 | 3         | 0.81%   |
| Ubuntu 22.10                 | 3         | 0.81%   |
| Raspbian 11                  | 3         | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.81%   |
| Lubuntu 22.10                | 3         | 0.81%   |
| Lubuntu 21.04                | 3         | 0.81%   |
| Kubuntu 22.04                | 3         | 0.81%   |
| KDE neon 22.04               | 3         | 0.81%   |
| Debian 10                    | 3         | 0.81%   |
| ArcoLinux Rolling            | 3         | 0.81%   |
| Arch Rolling                 | 3         | 0.81%   |
| Zorin 15                     | 2         | 0.54%   |
| Xubuntu 22.04                | 2         | 0.54%   |
| Xubuntu 20.04                | 2         | 0.54%   |
| UbuntuDDE 20.04              | 2         | 0.54%   |
| Ubuntu Studio 20.04          | 2         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 83        | 25.15%  |
| OpenMandriva     | 46        | 13.94%  |
| Debian           | 22        | 6.67%   |
| Linux Mint       | 21        | 6.36%   |
| Fedora           | 21        | 6.36%   |
| Zorin            | 16        | 4.85%   |
| Manjaro          | 15        | 4.55%   |
| Lubuntu          | 12        | 3.64%   |
| Pop!_OS          | 10        | 3.03%   |
| Kubuntu          | 9         | 2.73%   |
| ROSA             | 8         | 2.42%   |
| KDE neon         | 6         | 1.82%   |
| Xubuntu          | 5         | 1.52%   |
| Arch             | 5         | 1.52%   |
| Elementary       | 4         | 1.21%   |
| ArcoLinux        | 4         | 1.21%   |
| Raspbian         | 3         | 0.91%   |
| openSUSE         | 3         | 0.91%   |
| Kali             | 3         | 0.91%   |
| UbuntuDDE        | 2         | 0.61%   |
| Ubuntu Unity     | 2         | 0.61%   |
| Ubuntu Studio    | 2         | 0.61%   |
| Ubuntu MATE      | 2         | 0.61%   |
| Ubuntu Budgie    | 2         | 0.61%   |
| Parrot           | 2         | 0.61%   |
| Nobara           | 2         | 0.61%   |
| Endless          | 2         | 0.61%   |
| EndeavourOS      | 2         | 0.61%   |
| SteamOS          | 1         | 0.3%    |
| Rocky Linux      | 1         | 0.3%    |
| Reborn OS        | 1         | 0.3%    |
| PureOS           | 1         | 0.3%    |
| Peppermint       | 1         | 0.3%    |
| org.kde.Platform | 1         | 0.3%    |
| Mageia           | 1         | 0.3%    |
| LMDE             | 1         | 0.3%    |
| LinuxFX          | 1         | 0.3%    |
| Crystal Linux    | 1         | 0.3%    |
| Clear Linux      | 1         | 0.3%    |
| ChimeraOS        | 1         | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                           | Computers | Percent |
|-----------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002          | 16        | 3.86%   |
| 6.2.6-desktop-1omv2390            | 7         | 1.69%   |
| 5.16.7-desktop-1omv4003           | 7         | 1.69%   |
| 6.4.11-desktop-1omv2390           | 6         | 1.45%   |
| 5.4.0-42-generic                  | 5         | 1.21%   |
| 6.1.1-desktop-1omv2290            | 4         | 0.97%   |
| 5.4.0-70-generic                  | 4         | 0.97%   |
| 5.13.0-16-generic                 | 4         | 0.97%   |
| 5.11.0-27-generic                 | 4         | 0.97%   |
| 5.0.0-23-generic                  | 4         | 0.97%   |
| 6.8.0-31-generic                  | 3         | 0.72%   |
| 6.7.4-custom                      | 3         | 0.72%   |
| 6.6.2-desktop-1omv2390            | 3         | 0.72%   |
| 6.5.0-41-generic                  | 3         | 0.72%   |
| 6.3.8-200.fc38.x86_64             | 3         | 0.72%   |
| 5.8.0-50-generic                  | 3         | 0.72%   |
| 5.4.0-77-generic                  | 3         | 0.72%   |
| 5.19.0-32-generic                 | 3         | 0.72%   |
| 5.19.0-26-generic                 | 3         | 0.72%   |
| 5.15.0-91-generic                 | 3         | 0.72%   |
| 5.15.0-52-generic                 | 3         | 0.72%   |
| 5.0.0-25-generic                  | 3         | 0.72%   |
| 6.8.0-36-generic                  | 2         | 0.48%   |
| 6.6.21-generic-8rosa2021.1-x86_64 | 2         | 0.48%   |
| 6.6.19-1-MANJARO                  | 2         | 0.48%   |
| 6.5.0-5-generic                   | 2         | 0.48%   |
| 6.5.0-35-generic                  | 2         | 0.48%   |
| 6.5.0-21-generic                  | 2         | 0.48%   |
| 6.2.0-26-generic                  | 2         | 0.48%   |
| 6.2.0-20-generic                  | 2         | 0.48%   |
| 6.2.0-18-generic                  | 2         | 0.48%   |
| 6.11.0-9-generic                  | 2         | 0.48%   |
| 6.10.0-desktop-1omv2490           | 2         | 0.48%   |
| 6.1.4-desktop-1omv2301            | 2         | 0.48%   |
| 6.1.0-10-amd64                    | 2         | 0.48%   |
| 6.0.6-76060006-generic            | 2         | 0.48%   |
| 5.9.16-1-MANJARO                  | 2         | 0.48%   |
| 5.8.0-7630-generic                | 2         | 0.48%   |
| 5.4.0-52-generic                  | 2         | 0.48%   |
| 5.4.0-29-generic                  | 2         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 38        | 9.64%   |
| 5.15.0  | 33        | 8.38%   |
| 6.5.0   | 16        | 4.06%   |
| 5.10.14 | 16        | 4.06%   |
| 5.19.0  | 15        | 3.81%   |
| 5.11.0  | 15        | 3.81%   |
| 6.1.0   | 12        | 3.05%   |
| 4.15.0  | 12        | 3.05%   |
| 6.8.0   | 11        | 2.79%   |
| 6.2.0   | 10        | 2.54%   |
| 5.3.0   | 10        | 2.54%   |
| 5.13.0  | 10        | 2.54%   |
| 5.8.0   | 9         | 2.28%   |
| 5.0.0   | 9         | 2.28%   |
| 5.10.0  | 8         | 2.03%   |
| 6.2.6   | 7         | 1.78%   |
| 5.16.7  | 7         | 1.78%   |
| 6.4.11  | 6         | 1.52%   |
| 6.1.1   | 6         | 1.52%   |
| 6.11.0  | 5         | 1.27%   |
| 6.6.2   | 4         | 1.02%   |
| 6.7.4   | 3         | 0.76%   |
| 6.3.8   | 3         | 0.76%   |
| 5.18.13 | 3         | 0.76%   |
| 4.19.0  | 3         | 0.76%   |
| 6.9.7   | 2         | 0.51%   |
| 6.7.0   | 2         | 0.51%   |
| 6.6.63  | 2         | 0.51%   |
| 6.6.21  | 2         | 0.51%   |
| 6.6.19  | 2         | 0.51%   |
| 6.6.0   | 2         | 0.51%   |
| 6.4.6   | 2         | 0.51%   |
| 6.3.6   | 2         | 0.51%   |
| 6.12.1  | 2         | 0.51%   |
| 6.11.3  | 2         | 0.51%   |
| 6.10.0  | 2         | 0.51%   |
| 6.1.4   | 2         | 0.51%   |
| 6.1.2   | 2         | 0.51%   |
| 6.0.6   | 2         | 0.51%   |
| 5.9.16  | 2         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 41        | 10.54%  |
| 5.4     | 39        | 10.03%  |
| 5.10    | 31        | 7.97%   |
| 6.1     | 27        | 6.94%   |
| 6.5     | 19        | 4.88%   |
| 6.2     | 19        | 4.88%   |
| 5.19    | 19        | 4.88%   |
| 5.11    | 19        | 4.88%   |
| 6.6     | 16        | 4.11%   |
| 6.8     | 13        | 3.34%   |
| 4.15    | 12        | 3.08%   |
| 5.13    | 11        | 2.83%   |
| 5.8     | 10        | 2.57%   |
| 5.3     | 10        | 2.57%   |
| 5.0     | 10        | 2.57%   |
| 6.4     | 8         | 2.06%   |
| 6.3     | 8         | 2.06%   |
| 6.11    | 7         | 1.8%    |
| 6.0     | 7         | 1.8%    |
| 5.16    | 7         | 1.8%    |
| 6.9     | 6         | 1.54%   |
| 6.7     | 6         | 1.54%   |
| 5.18    | 6         | 1.54%   |
| 6.10    | 5         | 1.29%   |
| 5.9     | 5         | 1.29%   |
| 5.6     | 4         | 1.03%   |
| 4.19    | 4         | 1.03%   |
| 6.12    | 3         | 0.77%   |
| 5.14    | 3         | 0.77%   |
| 5.12    | 3         | 0.77%   |
| 4.18    | 3         | 0.77%   |
| 5.7     | 2         | 0.51%   |
| 5.17    | 2         | 0.51%   |
| 4.1     | 2         | 0.51%   |
| 5.2     | 1         | 0.26%   |
| 4.9     | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 300       | 97.09%  |
| i686   | 6         | 1.94%   |
| armv6l | 2         | 0.65%   |
| armv7l | 1         | 0.32%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 145       | 44.62%  |
| KDE5          | 66        | 20.31%  |
| Unknown       | 26        | 8%      |
| XFCE          | 17        | 5.23%   |
| LXQt          | 15        | 4.62%   |
| X-Cinnamon    | 12        | 3.69%   |
| MATE          | 9         | 2.77%   |
| KDE6          | 5         | 1.54%   |
| KDE           | 5         | 1.54%   |
| Pantheon      | 4         | 1.23%   |
| LXDE          | 4         | 1.23%   |
| Deepin        | 3         | 0.92%   |
| Unity         | 2         | 0.62%   |
| Openbox       | 2         | 0.62%   |
| i3            | 2         | 0.62%   |
| Cinnamon      | 2         | 0.62%   |
| Budgie        | 2         | 0.62%   |
| onyx:GNOME    | 1         | 0.31%   |
| Hyprland      | 1         | 0.31%   |
| GNOME Classic | 1         | 0.31%   |
| DDE           | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 216       | 67.5%   |
| Wayland | 89        | 27.81%  |
| Unknown | 8         | 2.5%    |
| Tty     | 7         | 2.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 38.2%   |
| SDDM    | 84        | 26.09%  |
| GDM3    | 42        | 13.04%  |
| LightDM | 31        | 9.63%   |
| GDM     | 31        | 9.63%   |
| TDM     | 11        | 3.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 147       | 45.37%  |
| es_CR   | 114       | 35.19%  |
| es_ES   | 20        | 6.17%   |
| Unknown | 19        | 5.86%   |
| es_MX   | 13        | 4.01%   |
| en_GB   | 3         | 0.93%   |
| C       | 3         | 0.93%   |
| fr_FR   | 2         | 0.62%   |
| es_EC   | 1         | 0.31%   |
| en_AG   | 1         | 0.31%   |
| de_DE   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 168       | 52.66%  |
| BIOS | 151       | 47.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 214       | 66.46%  |
| Overlay | 42        | 13.04%  |
| Btrfs   | 39        | 12.11%  |
| Tmpfs   | 19        | 5.9%    |
| Unknown | 5         | 1.55%   |
| Xfs     | 3         | 0.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 152       | 47.65%  |
| Unknown | 133       | 41.69%  |
| MBR     | 34        | 10.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 268       | 84.54%  |
| Yes       | 49        | 15.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 64.38%  |
| Yes       | 114       | 35.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 61        | 19.74%  |
| Hewlett-Packard         | 53        | 17.15%  |
| Lenovo                  | 38        | 12.3%   |
| ASUSTek Computer        | 32        | 10.36%  |
| MSI                     | 17        | 5.5%    |
| Acer                    | 16        | 5.18%   |
| Toshiba                 | 15        | 4.85%   |
| Gigabyte Technology     | 15        | 4.85%   |
| Apple                   | 9         | 2.91%   |
| ASRock                  | 8         | 2.59%   |
| Unknown                 | 6         | 1.94%   |
| Intel                   | 5         | 1.62%   |
| Samsung Electronics     | 4         | 1.29%   |
| Raspberry Pi Foundation | 3         | 0.97%   |
| Google                  | 3         | 0.97%   |
| Sony                    | 2         | 0.65%   |
| ZOTAC                   | 1         | 0.32%   |
| Valve                   | 1         | 0.32%   |
| TPV-INVENTA             | 1         | 0.32%   |
| TCL Communication       | 1         | 0.32%   |
| System76                | 1         | 0.32%   |
| Supermicro              | 1         | 0.32%   |
| Purism                  | 1         | 0.32%   |
| Pegatron                | 1         | 0.32%   |
| Olivetti                | 1         | 0.32%   |
| Microsoft               | 1         | 0.32%   |
| MACHINIST               | 1         | 0.32%   |
| Jumper                  | 1         | 0.32%   |
| HUAWEI                  | 1         | 0.32%   |
| GPU Company             | 1         | 0.32%   |
| Gateway                 | 1         | 0.32%   |
| Foxconn                 | 1         | 0.32%   |
| EVOO                    | 1         | 0.32%   |
| Deffad                  | 1         | 0.32%   |
| Biostar                 | 1         | 0.32%   |
| AZW                     | 1         | 0.32%   |
| Alienware               | 1         | 0.32%   |
| ABIT                    | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 9         | 2.91%   |
| Dell OptiPlex 3020             | 6         | 1.94%   |
| HP Notebook                    | 4         | 1.29%   |
| Dell Inspiron 7506 2n1         | 4         | 1.29%   |
| Apple MacBookPro8,1            | 4         | 1.29%   |
| MSI MS-7C51                    | 3         | 0.97%   |
| HP Laptop 15-da0xxx            | 3         | 0.97%   |
| Dell Inspiron 5584             | 3         | 0.97%   |
| ASUS PRIME A320M-K             | 3         | 0.97%   |
| Toshiba Satellite L755         | 2         | 0.65%   |
| RPi Raspberry Pi Model B Rev 2 | 2         | 0.65%   |
| Intel NUC12WSHi7               | 2         | 0.65%   |
| HP ProBook 6460b               | 2         | 0.65%   |
| HP Pavilion Notebook           | 2         | 0.65%   |
| HP Pavilion g4                 | 2         | 0.65%   |
| HP Laptop 14-ck0xxx            | 2         | 0.65%   |
| HP EliteBook 840 G6            | 2         | 0.65%   |
| Gigabyte H110M-H               | 2         | 0.65%   |
| Gigabyte B250M-DS3H            | 2         | 0.65%   |
| Dell OptiPlex 7040             | 2         | 0.65%   |
| Dell Latitude E5470            | 2         | 0.65%   |
| ASUS TUF Gaming X570-PLUS      | 2         | 0.65%   |
| ASUS PRIME H310M-E R2.0        | 2         | 0.65%   |
| ASUS All Series                | 2         | 0.65%   |
| ASRock B450 Steel Legend       | 2         | 0.65%   |
| ZOTAC NM10                     | 1         | 0.32%   |
| Valve Jupiter                  | 1         | 0.32%   |
| TPV-INVENTA 18-2003LA          | 1         | 0.32%   |
| Toshiba Satellite X205         | 1         | 0.32%   |
| Toshiba Satellite S55-A        | 1         | 0.32%   |
| Toshiba Satellite L845         | 1         | 0.32%   |
| Toshiba Satellite L655         | 1         | 0.32%   |
| Toshiba Satellite L45-B        | 1         | 0.32%   |
| Toshiba Satellite C855D        | 1         | 0.32%   |
| Toshiba Satellite C845         | 1         | 0.32%   |
| Toshiba Satellite C645D        | 1         | 0.32%   |
| Toshiba Satellite C55-C        | 1         | 0.32%   |
| Toshiba Satellite C55-B        | 1         | 0.32%   |
| Toshiba Satellite C45-A        | 1         | 0.32%   |
| Toshiba Satellite A305D        | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 22        | 7.12%   |
| Dell Inspiron          | 20        | 6.47%   |
| Dell Latitude          | 16        | 5.18%   |
| Toshiba Satellite      | 14        | 4.53%   |
| Acer Aspire            | 14        | 4.53%   |
| Dell OptiPlex          | 12        | 3.88%   |
| HP EliteBook           | 11        | 3.56%   |
| Lenovo IdeaPad         | 9         | 2.91%   |
| HP Pavilion            | 9         | 2.91%   |
| HP Laptop              | 9         | 2.91%   |
| Unknown                | 9         | 2.91%   |
| HP ProBook             | 6         | 1.94%   |
| ASUS PRIME             | 6         | 1.94%   |
| HP Notebook            | 4         | 1.29%   |
| Dell XPS               | 4         | 1.29%   |
| Dell Precision         | 4         | 1.29%   |
| ASUS VivoBook          | 4         | 1.29%   |
| ASUS TUF               | 4         | 1.29%   |
| Apple MacBookPro8      | 4         | 1.29%   |
| RPi Raspberry          | 3         | 0.97%   |
| MSI MS-7C51            | 3         | 0.97%   |
| Lenovo ThinkCentre     | 2         | 0.65%   |
| Lenovo IdeaPadFlex     | 2         | 0.65%   |
| Intel NUC12WSHi7       | 2         | 0.65%   |
| HP ProDesk             | 2         | 0.65%   |
| Gigabyte H110M-H       | 2         | 0.65%   |
| Gigabyte B250M-DS3H    | 2         | 0.65%   |
| Dell G3                | 2         | 0.65%   |
| ASUS Strix             | 2         | 0.65%   |
| ASUS SABERTOOTH        | 2         | 0.65%   |
| ASUS All               | 2         | 0.65%   |
| ASRock B450            | 2         | 0.65%   |
| ZOTAC NM10             | 1         | 0.32%   |
| Valve Jupiter          | 1         | 0.32%   |
| TPV-INVENTA 18-2003LA  | 1         | 0.32%   |
| Toshiba QOSMIO         | 1         | 0.32%   |
| TCL Communication 8085 | 1         | 0.32%   |
| System76 Lemur         | 1         | 0.32%   |
| Supermicro X9DAi       | 1         | 0.32%   |
| Sony SVE14123CLW       | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 35        | 11.33%  |
| 2020    | 27        | 8.74%   |
| 2018    | 27        | 8.74%   |
| 2016    | 25        | 8.09%   |
| 2014    | 25        | 8.09%   |
| 2012    | 23        | 7.44%   |
| 2011    | 22        | 7.12%   |
| 2013    | 19        | 6.15%   |
| 2015    | 18        | 5.83%   |
| 2021    | 15        | 4.85%   |
| 2017    | 14        | 4.53%   |
| 2022    | 13        | 4.21%   |
| 2010    | 10        | 3.24%   |
| 2009    | 8         | 2.59%   |
| 2023    | 7         | 2.27%   |
| 2008    | 7         | 2.27%   |
| 2007    | 5         | 1.62%   |
| 2006    | 3         | 0.97%   |
| Unknown | 3         | 0.97%   |
| 2005    | 2         | 0.65%   |
| 2024    | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 193       | 62.46%  |
| Desktop        | 93        | 30.1%   |
| Convertible    | 8         | 2.59%   |
| All in one     | 5         | 1.62%   |
| System on chip | 3         | 0.97%   |
| Tablet         | 3         | 0.97%   |
| Mini pc        | 3         | 0.97%   |
| Server         | 1         | 0.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 286       | 91.96%  |
| Enabled  | 25        | 8.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 305       | 98.71%  |
| Yes  | 4         | 1.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 70        | 22.01%  |
| 8.01-16.0       | 66        | 20.75%  |
| 16.01-24.0      | 61        | 19.18%  |
| 3.01-4.0        | 58        | 18.24%  |
| 32.01-64.0      | 28        | 8.81%   |
| 1.01-2.0        | 10        | 3.14%   |
| 64.01-256.0     | 9         | 2.83%   |
| 24.01-32.0      | 6         | 1.89%   |
| 2.01-3.0        | 5         | 1.57%   |
| 0.51-1.0        | 2         | 0.63%   |
| 0.01-0.5        | 2         | 0.63%   |
| More than 256.0 | 1         | 0.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 130       | 37.36%  |
| 2.01-3.0   | 82        | 23.56%  |
| 4.01-8.0   | 54        | 15.52%  |
| 3.01-4.0   | 43        | 12.36%  |
| 0.51-1.0   | 15        | 4.31%   |
| 8.01-16.0  | 12        | 3.45%   |
| 0.01-0.5   | 6         | 1.72%   |
| 16.01-24.0 | 5         | 1.44%   |
| 24.01-32.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 203       | 64.04%  |
| 2      | 81        | 25.55%  |
| 3      | 17        | 5.36%   |
| 4      | 10        | 3.15%   |
| 5      | 2         | 0.63%   |
| 9      | 1         | 0.32%   |
| 8      | 1         | 0.32%   |
| 7      | 1         | 0.32%   |
| 6      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 193       | 61.46%  |
| Yes       | 121       | 38.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 268       | 86.73%  |
| No        | 41        | 13.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 246       | 78.85%  |
| No        | 66        | 21.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 60.13%  |
| No        | 126       | 39.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Costa Rica | 309       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San José     | 151       | 43.64%  |
| Heredia       | 51        | 14.74%  |
| Alajuela      | 21        | 6.07%   |
| Grecia        | 16        | 4.62%   |
| Escazu        | 11        | 3.18%   |
| Cartago       | 10        | 2.89%   |
| Rio Segundo   | 6         | 1.73%   |
| Quesada       | 5         | 1.45%   |
| Puntarenas    | 5         | 1.45%   |
| Pavas         | 5         | 1.45%   |
| Santa Fe      | 4         | 1.16%   |
| San Ramon     | 4         | 1.16%   |
| Perez Zeledon | 4         | 1.16%   |
| Liberia       | 4         | 1.16%   |
| Siquirres     | 3         | 0.87%   |
| Santa Cruz    | 3         | 0.87%   |
| Santa Ana     | 3         | 0.87%   |
| San Pedro     | 3         | 0.87%   |
| Naranjo       | 3         | 0.87%   |
| Esparza       | 3         | 0.87%   |
| Tres Rios     | 2         | 0.58%   |
| Palmares      | 2         | 0.58%   |
| Nosara        | 2         | 0.58%   |
| Curridabat    | 2         | 0.58%   |
| Colon         | 2         | 0.58%   |
| Bagaces       | 2         | 0.58%   |
| Zarcero       | 1         | 0.29%   |
| Tibas         | 1         | 0.29%   |
| Santo Domingo | 1         | 0.29%   |
| Santiago      | 1         | 0.29%   |
| San Rafael    | 1         | 0.29%   |
| San Pablo     | 1         | 0.29%   |
| San Juan      | 1         | 0.29%   |
| San Francisco | 1         | 0.29%   |
| San Felipe    | 1         | 0.29%   |
| Quepos        | 1         | 0.29%   |
| Mercedes      | 1         | 0.29%   |
| La Fortuna    | 1         | 0.29%   |
| Guapiles      | 1         | 0.29%   |
| Guacima       | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 63        | 98     | 14.06%  |
| WDC                         | 56        | 87     | 12.5%   |
| Toshiba                     | 41        | 48     | 9.15%   |
| Samsung Electronics         | 40        | 70     | 8.93%   |
| Kingston                    | 35        | 47     | 7.81%   |
| A-DATA Technology           | 24        | 25     | 5.36%   |
| Unknown                     | 22        | 30     | 4.91%   |
| Intel                       | 20        | 51     | 4.46%   |
| Patriot                     | 12        | 14     | 2.68%   |
| HGST                        | 12        | 13     | 2.68%   |
| SanDisk                     | 11        | 13     | 2.46%   |
| Hitachi                     | 9         | 12     | 2.01%   |
| Crucial                     | 9         | 9      | 2.01%   |
| SK hynix                    | 8         | 15     | 1.79%   |
| JMicron Technology          | 7         | 7      | 1.56%   |
| Team                        | 5         | 5      | 1.12%   |
| Realtek Semiconductor       | 5         | 7      | 1.12%   |
| Netac                       | 5         | 7      | 1.12%   |
| Micron Technology           | 5         | 6      | 1.12%   |
| KIOXIA                      | 5         | 7      | 1.12%   |
| XPG                         | 4         | 4      | 0.89%   |
| Mushkin                     | 3         | 3      | 0.67%   |
| LITEON                      | 3         | 3      | 0.67%   |
| Kingston Technology Company | 3         | 6      | 0.67%   |
| ADATA Technology            | 3         | 3      | 0.67%   |
| ZOTAC                       | 2         | 3      | 0.45%   |
| Silicon Motion              | 2         | 2      | 0.45%   |
| Phison Electronics          | 2         | 2      | 0.45%   |
| Maxtor                      | 2         | 2      | 0.45%   |
| LITEONIT                    | 2         | 2      | 0.45%   |
| Gigabyte Technology         | 2         | 3      | 0.45%   |
| ASMedia                     | 2         | 2      | 0.45%   |
| Apple                       | 2         | 3      | 0.45%   |
| Unknown                     | 2         | 2      | 0.45%   |
| Zheino                      | 1         | 1      | 0.22%   |
| Wibtek                      | 1         | 1      | 0.22%   |
| WD MediaMax                 | 1         | 1      | 0.22%   |
| UMIS                        | 1         | 1      | 0.22%   |
| Transcend                   | 1         | 1      | 0.22%   |
| T-FORCE                     | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD             | 12        | 2.47%   |
| Toshiba MQ01ABD100 1TB                      | 8         | 1.65%   |
| Toshiba MQ01ABF050 500GB                    | 7         | 1.44%   |
| Seagate ST1000LM035-1RK172 1TB              | 7         | 1.44%   |
| JMicron Generic 500GB                       | 7         | 1.44%   |
| Toshiba DT01ACA100 1TB                      | 6         | 1.23%   |
| A-DATA SU630 480GB SSD                      | 6         | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 5         | 1.03%   |
| Kingston SV300S37A120G 120GB SSD            | 5         | 1.03%   |
| A-DATA SU650 120GB SSD                      | 5         | 1.03%   |
| Unknown MMC Card  32GB                      | 4         | 0.82%   |
| Seagate ST1000DM003-1CH162 1TB              | 4         | 0.82%   |
| Kingston SA400S37480G 480GB SSD             | 4         | 0.82%   |
| Intel H10 HBRPEKNX0203AO NVMe 32GB          | 4         | 0.82%   |
| Intel H10 HBRPEKNX0203A NVMe 1TB            | 4         | 0.82%   |
| HGST HTS541075A9E680 752GB                  | 4         | 0.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD            | 3         | 0.62%   |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 3         | 0.62%   |
| WDC WD10EZEX-75WN4A1 1TB                    | 3         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB                    | 3         | 0.62%   |
| Unknown MMC Card  128GB                     | 3         | 0.62%   |
| Toshiba KBG30ZMS256G NVMe 256GB             | 3         | 0.62%   |
| Seagate ST500LT012-1DG142 500GB             | 3         | 0.62%   |
| Seagate ST2000LM007-1R8174 2TB              | 3         | 0.62%   |
| Realtek RTS5763DL NVMe SSD Controller 256GB | 3         | 0.62%   |
| Patriot P210 256GB SSD                      | 3         | 0.62%   |
| Kingston SA400S37960G 960GB SSD             | 3         | 0.62%   |
| Intel SSDSC2MH250A2 250GB                   | 3         | 0.62%   |
| Intel SSDSC2BF180A4H 180GB                  | 3         | 0.62%   |
| Intel SSDSA2CW300G3 304GB                   | 3         | 0.62%   |
| HGST HTS541010A9E680 1TB                    | 3         | 0.62%   |
| XPG GAMMIX S11 Pro 512GB                    | 2         | 0.41%   |
| WDC WDS200T2B0B-00YS70 2TB SSD              | 2         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                | 2         | 0.41%   |
| WDC WD5000LPCX-60VHAT0 500GB                | 2         | 0.41%   |
| WDC WD20SPZX-08UA7 2TB                      | 2         | 0.41%   |
| Unknown MMC Card  64GB                      | 2         | 0.41%   |
| Unknown 00000  32GB                         | 2         | 0.41%   |
| Toshiba NVMe SSD Drive 256GB                | 2         | 0.41%   |
| Team T253X1240G 240GB SSD                   | 2         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 94     | 33.9%   |
| WDC                 | 43        | 52     | 24.29%  |
| Toshiba             | 35        | 38     | 19.77%  |
| HGST                | 12        | 13     | 6.78%   |
| Hitachi             | 9         | 12     | 5.08%   |
| JMicron Technology  | 7         | 7      | 3.95%   |
| Samsung Electronics | 2         | 2      | 1.13%   |
| Maxtor              | 2         | 2      | 1.13%   |
| ASMedia             | 2         | 2      | 1.13%   |
| Apple               | 2         | 2      | 1.13%   |
| Unknown             | 1         | 2      | 0.56%   |
| SABRENT             | 1         | 1      | 0.56%   |
| Fujitsu             | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 32        | 39     | 22.07%  |
| A-DATA Technology   | 19        | 20     | 13.1%   |
| Samsung Electronics | 14        | 32     | 9.66%   |
| WDC                 | 12        | 30     | 8.28%   |
| Patriot             | 10        | 12     | 6.9%    |
| Intel               | 10        | 30     | 6.9%    |
| Crucial             | 7         | 7      | 4.83%   |
| SanDisk             | 6         | 8      | 4.14%   |
| Team                | 4         | 4      | 2.76%   |
| Netac               | 4         | 5      | 2.76%   |
| Micron Technology   | 4         | 4      | 2.76%   |
| Mushkin             | 3         | 3      | 2.07%   |
| LITEON              | 3         | 3      | 2.07%   |
| ZOTAC               | 2         | 3      | 1.38%   |
| LITEONIT            | 2         | 2      | 1.38%   |
| Gigabyte Technology | 2         | 3      | 1.38%   |
| Wibtek              | 1         | 1      | 0.69%   |
| Unknown             | 1         | 1      | 0.69%   |
| Transcend           | 1         | 1      | 0.69%   |
| ShiJi               | 1         | 1      | 0.69%   |
| Seagate             | 1         | 1      | 0.69%   |
| FORESEE             | 1         | 4      | 0.69%   |
| CT120BX5            | 1         | 1      | 0.69%   |
| China               | 1         | 1      | 0.69%   |
| BP4                 | 1         | 1      | 0.69%   |
| Biostar             | 1         | 1      | 0.69%   |
| Acer                | 1         | 1      | 0.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 153       | 228    | 38.15%  |
| SSD     | 130       | 219    | 32.42%  |
| NVMe    | 90        | 151    | 22.44%  |
| MMC     | 21        | 28     | 5.24%   |
| Unknown | 7         | 8      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 243       | 427    | 64.97%  |
| NVMe | 89        | 150    | 23.8%   |
| SAS  | 21        | 29     | 5.61%   |
| MMC  | 21        | 28     | 5.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 171       | 263    | 58.76%  |
| 0.51-1.0   | 88        | 132    | 30.24%  |
| 1.01-2.0   | 18        | 28     | 6.19%   |
| 4.01-10.0  | 5         | 13     | 1.72%   |
| 3.01-4.0   | 4         | 4      | 1.37%   |
| 2.01-3.0   | 4         | 6      | 1.37%   |
| 10.01-20.0 | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 87        | 25.82%  |
| 501-1000       | 61        | 18.1%   |
| 251-500        | 60        | 17.8%   |
| 1-20           | 33        | 9.79%   |
| 1001-2000      | 29        | 8.61%   |
| 51-100         | 24        | 7.12%   |
| 21-50          | 17        | 5.04%   |
| More than 3000 | 14        | 4.15%   |
| 2001-3000      | 6         | 1.78%   |
| Unknown        | 6         | 1.78%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 147       | 41.76%  |
| 21-50          | 58        | 16.48%  |
| 101-250        | 42        | 11.93%  |
| 51-100         | 36        | 10.23%  |
| 251-500        | 34        | 9.66%   |
| 501-1000       | 17        | 4.83%   |
| Unknown        | 6         | 1.7%    |
| More than 3000 | 5         | 1.42%   |
| 1001-2000      | 5         | 1.42%   |
| 2001-3000      | 2         | 0.57%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Intel H10 HBRPEKNX0203A NVMe 1TB                    | 4         | 4      | 10.81%  |
| Seagate ST1000DM003-1CH162 1TB                      | 2         | 2      | 5.41%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 2      | 5.41%   |
| A-DATA Technology SX8100NP 256GB                    | 2         | 2      | 5.41%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 2.7%    |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 2.7%    |
| Unknown MB3000EBKAB 3TB                             | 1         | 1      | 2.7%    |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.7%    |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 2.7%    |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 2.7%    |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 2.7%    |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 2.7%    |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 2      | 2.7%    |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2.7%    |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 2      | 2.7%    |
| Netac SSD 120GB                                     | 1         | 2      | 2.7%    |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.7%    |
| Maxtor STM3160215AS 160GB                           | 1         | 1      | 2.7%    |
| Kingston SA400S37480G 480GB SSD                     | 1         | 1      | 2.7%    |
| Kingston SA400S37240G 240GB SSD                     | 1         | 1      | 2.7%    |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 2.7%    |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 2.7%    |
| Hitachi HDE721010SLA330 1TB                         | 1         | 1      | 2.7%    |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.7%    |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 2.7%    |
| Apple HDD HTS541010A9E662 1TB                       | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 9         | 10     | 24.32%  |
| Toshiba           | 5         | 5      | 13.51%  |
| Intel             | 5         | 5      | 13.51%  |
| Kingston          | 4         | 4      | 10.81%  |
| WDC               | 2         | 2      | 5.41%   |
| Hitachi           | 2         | 3      | 5.41%   |
| HGST              | 2         | 2      | 5.41%   |
| A-DATA Technology | 2         | 2      | 5.41%   |
| Unknown           | 1         | 1      | 2.7%    |
| SanDisk           | 1         | 2      | 2.7%    |
| Netac             | 1         | 2      | 2.7%    |
| Micron Technology | 1         | 1      | 2.7%    |
| Maxtor            | 1         | 1      | 2.7%    |
| Apple             | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 9         | 10     | 39.13%  |
| Toshiba | 5         | 5      | 21.74%  |
| WDC     | 2         | 2      | 8.7%    |
| Hitachi | 2         | 3      | 8.7%    |
| HGST    | 2         | 2      | 8.7%    |
| Unknown | 1         | 1      | 4.35%   |
| Maxtor  | 1         | 1      | 4.35%   |
| Apple   | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 25     | 61.11%  |
| SSD  | 8         | 10     | 22.22%  |
| NVMe | 6         | 6      | 16.67%  |

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
| Detected | 177       | 318    | 51.01%  |
| Works    | 136       | 275    | 39.19%  |
| Malfunc  | 34        | 41     | 9.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 215       | 56.73%  |
| AMD                          | 56        | 14.78%  |
| Samsung Electronics          | 24        | 6.33%   |
| SanDisk                      | 8         | 2.11%   |
| Realtek Semiconductor        | 8         | 2.11%   |
| ASMedia Technology           | 8         | 2.11%   |
| ADATA Technology             | 8         | 2.11%   |
| SK hynix                     | 7         | 1.85%   |
| Toshiba America Info Systems | 6         | 1.58%   |
| Kingston Technology Company  | 6         | 1.58%   |
| Nvidia                       | 5         | 1.32%   |
| KIOXIA                       | 4         | 1.06%   |
| Silicon Motion               | 3         | 0.79%   |
| Phison Electronics           | 3         | 0.79%   |
| Micron/Crucial Technology    | 3         | 0.79%   |
| Micron Technology            | 2         | 0.53%   |
| LSI Logic / Symbios Logic    | 2         | 0.53%   |
| INNOGRIT                     | 2         | 0.53%   |
| Union Memory (Shenzhen)      | 1         | 0.26%   |
| Solidigm                     | 1         | 0.26%   |
| Silicon Image                | 1         | 0.26%   |
| OCZ Technology Group         | 1         | 0.26%   |
| O2 Micro                     | 1         | 0.26%   |
| Marvell Technology Group     | 1         | 0.26%   |
| JMicron Technology           | 1         | 0.26%   |
| Hosin Global Electronics     | 1         | 0.26%   |
| Apple                        | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 35        | 8.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 18        | 4.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 18        | 4.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 18        | 4.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 16        | 3.84%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 14        | 3.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 11        | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 10        | 2.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 2.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 2.16%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 1.92%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                          | 8         | 1.92%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                           | 8         | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 6         | 1.44%   |
| Realtek RTS5762 NVMe SSD Controller                                                    | 6         | 1.44%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                     | 6         | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.44%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 6         | 1.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 5         | 1.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 5         | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 1.2%    |
| Intel SATA Controller [RAID mode]                                                      | 5         | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 5         | 1.2%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 4         | 0.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 4         | 0.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 4         | 0.96%   |
| AMD 400 Series Chipset SATA Controller                                                 | 4         | 0.96%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)                    | 3         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 3         | 0.72%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                  | 3         | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.72%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                     | 3         | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 3         | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 228       | 59.84%  |
| NVMe | 90        | 23.62%  |
| RAID | 31        | 8.14%   |
| IDE  | 30        | 7.87%   |
| SAS  | 1         | 0.26%   |
| SCSI | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 240       | 77.67%  |
| AMD    | 66        | 21.36%  |
| ARM    | 3         | 0.97%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 7         | 2.27%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 6         | 1.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 1.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 4         | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 1.29%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.29%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 4         | 1.29%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 4         | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4         | 1.29%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4         | 1.29%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 3         | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.97%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 3         | 0.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3         | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 0.97%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 3         | 0.97%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 0.97%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 3         | 0.97%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 0.97%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 0.97%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 3         | 0.97%   |
| Intel 12th Gen Core i7-1260P                | 3         | 0.97%   |
| ARM BCM2835 Processor                       | 3         | 0.97%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 2         | 0.65%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 0.65%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 0.65%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 2         | 0.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 0.65%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 2         | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.65%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 2         | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 0.65%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 0.65%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 0.65%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 2         | 0.65%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 69        | 22.33%  |
| Intel Core i7                  | 52        | 16.83%  |
| Intel Core i3                  | 30        | 9.71%   |
| Other                          | 29        | 9.39%   |
| Intel Celeron                  | 24        | 7.77%   |
| AMD Ryzen 7                    | 14        | 4.53%   |
| AMD Ryzen 5                    | 13        | 4.21%   |
| AMD Ryzen 3                    | 8         | 2.59%   |
| Intel Xeon                     | 7         | 2.27%   |
| Intel Pentium                  | 6         | 1.94%   |
| Intel Core 2 Duo               | 6         | 1.94%   |
| Intel Atom                     | 5         | 1.62%   |
| AMD FX                         | 5         | 1.62%   |
| Intel Core 2                   | 4         | 1.29%   |
| AMD E1                         | 4         | 1.29%   |
| ARM BCM                        | 3         | 0.97%   |
| AMD A8                         | 3         | 0.97%   |
| AMD A10                        | 3         | 0.97%   |
| Intel Pentium Dual-Core        | 2         | 0.65%   |
| Intel Genuine                  | 2         | 0.65%   |
| AMD Athlon II X2               | 2         | 0.65%   |
| Intel Xeon Silver              | 1         | 0.32%   |
| Intel Pentium Silver           | 1         | 0.32%   |
| Intel Pentium 4                | 1         | 0.32%   |
| Intel Core M                   | 1         | 0.32%   |
| Intel Core i9                  | 1         | 0.32%   |
| Intel Core 2 Quad              | 1         | 0.32%   |
| AMD V120                       | 1         | 0.32%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.32%   |
| AMD Turion 64 X2               | 1         | 0.32%   |
| AMD Sempron                    | 1         | 0.32%   |
| AMD Ryzen 7 PRO                | 1         | 0.32%   |
| AMD Ryzen 5 PRO                | 1         | 0.32%   |
| AMD PRO A10                    | 1         | 0.32%   |
| AMD Phenom II X4               | 1         | 0.32%   |
| AMD E2                         | 1         | 0.32%   |
| AMD E                          | 1         | 0.32%   |
| AMD Athlon                     | 1         | 0.32%   |
| AMD A4                         | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 137       | 44.34%  |
| 4      | 105       | 33.98%  |
| 6      | 26        | 8.41%   |
| 8      | 19        | 6.15%   |
| 1      | 9         | 2.91%   |
| 12     | 4         | 1.29%   |
| 10     | 3         | 0.97%   |
| 16     | 2         | 0.65%   |
| 24     | 1         | 0.32%   |
| 20     | 1         | 0.32%   |
| 14     | 1         | 0.32%   |
| 3      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 307       | 99.35%  |
| 2      | 2         | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 192       | 62.14%  |
| 1      | 117       | 37.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 301       | 97.1%   |
| Unknown        | 6         | 1.94%   |
| 32-bit         | 3         | 0.97%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 36.7%   |
| 0x306c3    | 15        | 4.59%   |
| 0x206a7    | 14        | 4.28%   |
| 0x306a9    | 12        | 3.67%   |
| 0x08108109 | 9         | 2.75%   |
| 0x806c1    | 7         | 2.14%   |
| 0x40651    | 7         | 2.14%   |
| 0x306d4    | 7         | 2.14%   |
| 0x906e9    | 6         | 1.83%   |
| 0x806e9    | 6         | 1.83%   |
| 0x506e3    | 6         | 1.83%   |
| 0x406e3    | 6         | 1.83%   |
| 0x406c4    | 6         | 1.83%   |
| 0x906ea    | 5         | 1.53%   |
| 0x806ec    | 5         | 1.53%   |
| 0x806ea    | 4         | 1.22%   |
| 0x706a1    | 4         | 1.22%   |
| 0x1067a    | 4         | 1.22%   |
| 0x08701021 | 4         | 1.22%   |
| 0x05000119 | 4         | 1.22%   |
| 0x806eb    | 3         | 0.92%   |
| 0x30678    | 3         | 0.92%   |
| 0x20655    | 3         | 0.92%   |
| 0x010000c8 | 3         | 0.92%   |
| 0x906eb    | 2         | 0.61%   |
| 0x706a8    | 2         | 0.61%   |
| 0x6fd      | 2         | 0.61%   |
| 0x6f6      | 2         | 0.61%   |
| 0x506c9    | 2         | 0.61%   |
| 0x306e4    | 2         | 0.61%   |
| 0x10676    | 2         | 0.61%   |
| 0x0a50000d | 2         | 0.61%   |
| 0x08600106 | 2         | 0.61%   |
| 0x08600104 | 2         | 0.61%   |
| 0x08101016 | 2         | 0.61%   |
| 0x07030105 | 2         | 0.61%   |
| 0x06001119 | 2         | 0.61%   |
| 0x06000852 | 2         | 0.61%   |
| 0xf49      | 1         | 0.31%   |
| 0xf29      | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 48        | 15.48%  |
| Haswell          | 28        | 9.03%   |
| SandyBridge      | 24        | 7.74%   |
| IvyBridge        | 21        | 6.77%   |
| Skylake          | 19        | 6.13%   |
| Unknown          | 15        | 4.84%   |
| Zen+             | 13        | 4.19%   |
| TigerLake        | 12        | 3.87%   |
| Silvermont       | 12        | 3.87%   |
| Zen 2            | 11        | 3.55%   |
| Broadwell        | 11        | 3.55%   |
| Penryn           | 9         | 2.9%    |
| Goldmont plus    | 9         | 2.9%    |
| Zen 3            | 8         | 2.58%   |
| Alderlake Hybrid | 8         | 2.58%   |
| Westmere         | 7         | 2.26%   |
| Piledriver       | 7         | 2.26%   |
| Core             | 6         | 1.94%   |
| K10              | 5         | 1.61%   |
| IceLake          | 5         | 1.61%   |
| Excavator        | 4         | 1.29%   |
| Bobcat           | 4         | 1.29%   |
| Goldmont         | 3         | 0.97%   |
| CometLake        | 3         | 0.97%   |
| Zen              | 2         | 0.65%   |
| Puma             | 2         | 0.65%   |
| NetBurst         | 2         | 0.65%   |
| Nehalem          | 2         | 0.65%   |
| Bonnell          | 2         | 0.65%   |
| Tremont          | 1         | 0.32%   |
| P6               | 1         | 0.32%   |
| K8 Hammer        | 1         | 0.32%   |
| K8 & K10 hybrid  | 1         | 0.32%   |
| K10 Llano        | 1         | 0.32%   |
| Jaguar           | 1         | 0.32%   |
| Gracemont        | 1         | 0.32%   |
| Bulldozer        | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 210       | 59.49%  |
| Nvidia | 74        | 20.96%  |
| AMD    | 69        | 19.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 5.41%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 3.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 3.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 2.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.43%   |
| Intel HD Graphics 620                                                                    | 9         | 2.43%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 2.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2.43%   |
| Intel HD Graphics 5500                                                                   | 8         | 2.16%   |
| Intel HD Graphics 530                                                                    | 8         | 2.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.16%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.16%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.62%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 6         | 1.62%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.35%   |
| Intel HD Graphics 630                                                                    | 5         | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 5         | 1.35%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.08%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.08%   |
| Intel DG1 [Iris Xe MAX Graphics]                                                         | 4         | 1.08%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.08%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 3         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.81%   |
| Intel HD Graphics 500                                                                    | 3         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.81%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.81%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.81%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 168       | 53.5%   |
| 1 x AMD        | 52        | 16.56%  |
| 1 x Nvidia     | 38        | 12.1%   |
| Intel + Nvidia | 31        | 9.87%   |
| 2 x AMD        | 7         | 2.23%   |
| AMD + Nvidia   | 6         | 1.91%   |
| Other          | 4         | 1.27%   |
| 2 x Intel      | 4         | 1.27%   |
| Intel + AMD    | 4         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 265       | 84.13%  |
| Proprietary | 39        | 12.38%  |
| Unknown     | 11        | 3.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 212       | 66.25%  |
| 1.01-2.0   | 36        | 11.25%  |
| 0.01-0.5   | 25        | 7.81%   |
| 3.01-4.0   | 17        | 5.31%   |
| 0.51-1.0   | 17        | 5.31%   |
| 5.01-6.0   | 7         | 2.19%   |
| 7.01-8.0   | 4         | 1.25%   |
| 8.01-16.0  | 2         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 13.75%  |
| LG Display              | 42        | 11.32%  |
| BOE                     | 34        | 9.16%   |
| AOC                     | 34        | 9.16%   |
| Samsung Electronics     | 30        | 8.09%   |
| Dell                    | 27        | 7.28%   |
| Chimei Innolux          | 23        | 6.2%    |
| Goldstar                | 18        | 4.85%   |
| Hewlett-Packard         | 16        | 4.31%   |
| Apple                   | 9         | 2.43%   |
| Acer                    | 9         | 2.43%   |
| ViewSonic               | 6         | 1.62%   |
| Sony                    | 5         | 1.35%   |
| BenQ                    | 5         | 1.35%   |
| Lenovo                  | 4         | 1.08%   |
| Chi Mei Optoelectronics | 4         | 1.08%   |
| AGO                     | 4         | 1.08%   |
| PANDA                   | 3         | 0.81%   |
| Panasonic               | 3         | 0.81%   |
| MSI                     | 3         | 0.81%   |
| ITE                     | 3         | 0.81%   |
| ASUSTek Computer        | 3         | 0.81%   |
| Ancor Communications    | 3         | 0.81%   |
| Sharp                   | 2         | 0.54%   |
| RTK                     | 2         | 0.54%   |
| Hitachi                 | 2         | 0.54%   |
| CPT                     | 2         | 0.54%   |
| Xerox                   | 1         | 0.27%   |
| Valve                   | 1         | 0.27%   |
| Unknown (XXX)           | 1         | 0.27%   |
| Sun                     | 1         | 0.27%   |
| Royal Information       | 1         | 0.27%   |
| RGT                     | 1         | 0.27%   |
| PRISM+                  | 1         | 0.27%   |
| Philips                 | 1         | 0.27%   |
| PAR                     | 1         | 0.27%   |
| Mi                      | 1         | 0.27%   |
| LTM                     | 1         | 0.27%   |
| LG Philips              | 1         | 0.27%   |
| LED                     | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 9         | 2.34%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 5         | 1.3%    |
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5         | 1.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 4         | 1.04%   |
| AU Optronics LCD Monitor AUO35EB 3840x2160 344x193mm 15.5-inch       | 4         | 1.04%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 4         | 1.04%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 4         | 1.04%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 4         | 1.04%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 3         | 0.78%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 0.78%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.78%   |
| Sony TV SNY1B02 1360x768                                             | 2         | 0.52%   |
| Sony TV SNY0902 1920x1080                                            | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2         | 0.52%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                       | 2         | 0.52%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch         | 2         | 0.52%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 2         | 0.52%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.52%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 2         | 0.52%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.52%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch          | 2         | 0.52%   |
| ITE VirtualScreen ITE6564 1920x1080 341x192mm 15.4-inch              | 2         | 0.52%   |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2         | 0.52%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2         | 0.52%   |
| Hewlett-Packard E232 HWP3279 1920x1080 509x286mm 23.0-inch           | 2         | 0.52%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.52%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                 | 2         | 0.52%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 2         | 0.52%   |
| Dell E207WFP DELD011 1680x1050 430x270mm 20.0-inch                   | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.52%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 2         | 0.52%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 132       | 37.61%  |
| 1366x768 (WXGA)    | 99        | 28.21%  |
| 3840x2160 (4K)     | 25        | 7.12%   |
| 1600x900 (HD+)     | 20        | 5.7%    |
| 1440x900 (WXGA+)   | 12        | 3.42%   |
| 1280x800 (WXGA)    | 11        | 3.13%   |
| 1280x1024 (SXGA)   | 11        | 3.13%   |
| 2560x1440 (QHD)    | 10        | 2.85%   |
| 1920x1200 (WUXGA)  | 6         | 1.71%   |
| 1680x1050 (WSXGA+) | 3         | 0.85%   |
| 1360x768           | 3         | 0.85%   |
| 3286x1080          | 2         | 0.57%   |
| 2944x1080          | 2         | 0.57%   |
| 2560x1080          | 2         | 0.57%   |
| 1280x720 (HD)      | 2         | 0.57%   |
| Unknown            | 2         | 0.57%   |
| 800x1280           | 1         | 0.28%   |
| 3840x2400          | 1         | 0.28%   |
| 3440x1440          | 1         | 0.28%   |
| 3200x2000          | 1         | 0.28%   |
| 2880x1800          | 1         | 0.28%   |
| 2560x1600          | 1         | 0.28%   |
| 1400x1050          | 1         | 0.28%   |
| 1280x960           | 1         | 0.28%   |
| 1024x576           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 100       | 26.74%  |
| 14      | 44        | 11.76%  |
| 13      | 36        | 9.63%   |
| 23      | 22        | 5.88%   |
| 24      | 21        | 5.61%   |
| 21      | 21        | 5.61%   |
| 19      | 20        | 5.35%   |
| 17      | 14        | 3.74%   |
| 18      | 13        | 3.48%   |
| 27      | 12        | 3.21%   |
| 31      | 9         | 2.41%   |
| Unknown | 9         | 2.41%   |
| 12      | 7         | 1.87%   |
| 72      | 6         | 1.6%    |
| 11      | 6         | 1.6%    |
| 84      | 5         | 1.34%   |
| 20      | 5         | 1.34%   |
| 34      | 3         | 0.8%    |
| 16      | 3         | 0.8%    |
| 57      | 2         | 0.53%   |
| 43      | 2         | 0.53%   |
| 40      | 2         | 0.53%   |
| 32      | 2         | 0.53%   |
| 26      | 2         | 0.53%   |
| 58      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 49      | 1         | 0.27%   |
| 39      | 1         | 0.27%   |
| 36      | 1         | 0.27%   |
| 22      | 1         | 0.27%   |
| 10      | 1         | 0.27%   |
| 7       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 176       | 47.57%  |
| 501-600     | 56        | 15.14%  |
| 401-500     | 55        | 14.86%  |
| 201-300     | 25        | 6.76%   |
| 351-400     | 12        | 3.24%   |
| 1501-2000   | 11        | 2.97%   |
| 601-700     | 9         | 2.43%   |
| Unknown     | 9         | 2.43%   |
| 701-800     | 7         | 1.89%   |
| 1001-1500   | 4         | 1.08%   |
| 801-900     | 3         | 0.81%   |
| 901-1000    | 2         | 0.54%   |
| 1-100       | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 253       | 78.57%  |
| 16/10   | 37        | 11.49%  |
| 5/4     | 10        | 3.11%   |
| Unknown | 9         | 2.8%    |
| 4/3     | 7         | 2.17%   |
| 21/9    | 3         | 0.93%   |
| 32/9    | 1         | 0.31%   |
| 0.67    | 1         | 0.31%   |
| 0.56    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 26.54%  |
| 81-90          | 75        | 20.11%  |
| 201-250        | 46        | 12.33%  |
| 151-200        | 33        | 8.85%   |
| 141-150        | 17        | 4.56%   |
| More than 1000 | 15        | 4.02%   |
| 351-500        | 14        | 3.75%   |
| 301-350        | 13        | 3.49%   |
| 251-300        | 13        | 3.49%   |
| Unknown        | 9         | 2.41%   |
| 71-80          | 8         | 2.14%   |
| 501-1000       | 7         | 1.88%   |
| 51-60          | 6         | 1.61%   |
| 121-130        | 6         | 1.61%   |
| 111-120        | 4         | 1.07%   |
| 61-70          | 3         | 0.8%    |
| 131-140        | 2         | 0.54%   |
| 41-50          | 1         | 0.27%   |
| 1-40           | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 121       | 33.52%  |
| 51-100        | 109       | 30.19%  |
| 121-160       | 85        | 23.55%  |
| 161-240       | 14        | 3.88%   |
| 1-50          | 13        | 3.6%    |
| More than 240 | 10        | 2.77%   |
| Unknown       | 9         | 2.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 242       | 74.01%  |
| 2     | 69        | 21.1%   |
| 0     | 10        | 3.06%   |
| 3     | 6         | 1.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 183       | 38.45%  |
| Intel                           | 127       | 26.68%  |
| Qualcomm Atheros                | 58        | 12.18%  |
| Broadcom                        | 34        | 7.14%   |
| TP-Link                         | 13        | 2.73%   |
| Broadcom Limited                | 9         | 1.89%   |
| MediaTek                        | 8         | 1.68%   |
| Nvidia                          | 5         | 1.05%   |
| ASIX Electronics                | 4         | 0.84%   |
| Aquantia                        | 4         | 0.84%   |
| Xiaomi                          | 3         | 0.63%   |
| Ralink                          | 3         | 0.63%   |
| Microchip Technology            | 3         | 0.63%   |
| Huawei Technologies             | 3         | 0.63%   |
| Ralink Technology               | 2         | 0.42%   |
| Marvell Technology Group        | 2         | 0.42%   |
| Linksys                         | 2         | 0.42%   |
| Lenovo                          | 2         | 0.42%   |
| D-Link                          | 2         | 0.42%   |
| Qualcomm Atheros Communications | 1         | 0.21%   |
| Qualcomm                        | 1         | 0.21%   |
| JMicron Technology              | 1         | 0.21%   |
| Hewlett-Packard                 | 1         | 0.21%   |
| DisplayLink                     | 1         | 0.21%   |
| Dell                            | 1         | 0.21%   |
| Davicom Semiconductor           | 1         | 0.21%   |
| D-Link System                   | 1         | 0.21%   |
| Apple                           | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 108       | 19.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 31        | 5.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 17        | 3%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 12        | 2.12%   |
| Intel Wireless 7265                                                    | 10        | 1.77%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 1.77%   |
| Intel Wi-Fi 6 AX201                                                    | 9         | 1.59%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 8         | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 1.41%   |
| Intel Wireless 7260                                                    | 8         | 1.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.06%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 6         | 1.06%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 6         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.88%   |
| Intel Wireless 8260                                                    | 5         | 0.88%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 5         | 0.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 4         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4         | 0.71%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 4         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.71%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 4         | 0.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 4         | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.53%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                              | 3         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 0.53%   |
| Realtek 802.11ac NIC                                                   | 3         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 37.45%  |
| Realtek Semiconductor           | 54        | 20.85%  |
| Qualcomm Atheros                | 44        | 16.99%  |
| Broadcom                        | 25        | 9.65%   |
| TP-Link                         | 13        | 5.02%   |
| Broadcom Limited                | 7         | 2.7%    |
| MediaTek                        | 6         | 2.32%   |
| Ralink                          | 3         | 1.16%   |
| Ralink Technology               | 2         | 0.77%   |
| Linksys                         | 2         | 0.77%   |
| D-Link                          | 2         | 0.77%   |
| Qualcomm Atheros Communications | 1         | 0.39%   |
| Qualcomm                        | 1         | 0.39%   |
| Dell                            | 1         | 0.39%   |
| D-Link System                   | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 4.56%   |
| Intel Wireless 7265                                            | 10        | 3.8%    |
| Intel Wi-Fi 6 AX200                                            | 10        | 3.8%    |
| Intel Wi-Fi 6 AX201                                            | 9         | 3.42%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 8         | 3.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 3.04%   |
| Intel Wireless 7260                                            | 8         | 3.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 8         | 3.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 2.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.28%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 2.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.9%    |
| Intel Wireless 8260                                            | 5         | 1.9%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 1.9%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4         | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.52%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 3         | 1.14%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.14%   |
| Realtek 802.11ac NIC                                           | 3         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.14%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.14%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3         | 1.14%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.14%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3         | 1.14%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.76%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 0.76%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.76%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.76%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.76%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 2         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 160       | 54.79%  |
| Intel                    | 63        | 21.58%  |
| Broadcom                 | 18        | 6.16%   |
| Qualcomm Atheros         | 17        | 5.82%   |
| Nvidia                   | 5         | 1.71%   |
| ASIX Electronics         | 4         | 1.37%   |
| Aquantia                 | 4         | 1.37%   |
| Xiaomi                   | 3         | 1.03%   |
| Microchip Technology     | 3         | 1.03%   |
| Huawei Technologies      | 3         | 1.03%   |
| MediaTek                 | 2         | 0.68%   |
| Marvell Technology Group | 2         | 0.68%   |
| Lenovo                   | 2         | 0.68%   |
| Broadcom Limited         | 2         | 0.68%   |
| JMicron Technology       | 1         | 0.34%   |
| DisplayLink              | 1         | 0.34%   |
| Davicom Semiconductor    | 1         | 0.34%   |
| Apple                    | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller          | 108       | 35.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                           | 31        | 10.26%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                        | 17        | 5.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                           | 10        | 3.31%   |
| Realtek RTL8125 2.5GbE Controller                                               | 6         | 1.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                      | 6         | 1.99%   |
| Intel Ethernet Controller I225-V                                                | 5         | 1.66%   |
| Intel Ethernet Connection (2) I219-LM                                           | 5         | 1.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                               | 5         | 1.66%   |
| Intel Ethernet Connection I217-LM                                               | 4         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                  | 3         | 0.99%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                      | 3         | 0.99%   |
| Intel Ethernet Connection I218-LM                                               | 3         | 0.99%   |
| Intel Ethernet Connection (6) I219-LM                                           | 3         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                                           | 3         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                            | 3         | 0.99%   |
| Intel 82579V Gigabit Network Connection                                         | 3         | 0.99%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                                | 3         | 0.99%   |
| ASIX AX88179 Gigabit Ethernet                                                   | 3         | 0.99%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                       | 2         | 0.66%   |
| Nvidia MCP79 Ethernet                                                           | 2         | 0.66%   |
| Nvidia MCP61 Ethernet                                                           | 2         | 0.66%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                   | 2         | 0.66%   |
| Intel I211 Gigabit Network Connection                                           | 2         | 0.66%   |
| Intel Ethernet Controller I226-V                                                | 2         | 0.66%   |
| Intel Ethernet Connection (7) I219-LM                                           | 2         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                           | 2         | 0.66%   |
| Intel 82599 10 Gigabit Network Connection                                       | 2         | 0.66%   |
| Huawei FOA-LX9                                                                  | 2         | 0.66%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                               | 2         | 0.66%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                               | 2         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                 | 2         | 0.66%   |
| Aquantia AQtion AQC100S NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2         | 0.66%   |
| Realtek USB 10/100/1G/2.5G LAN                                                  | 1         | 0.33%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                      | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                           | 1         | 0.33%   |
| Realtek PCIe GbE Family Controller                                              | 1         | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                       | 1         | 0.33%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                       | 1         | 0.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                           | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 267       | 51.95%  |
| WiFi     | 246       | 47.86%  |
| Modem    | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 185       | 57.28%  |
| Ethernet | 138       | 42.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 181       | 57.64%  |
| 1     | 112       | 35.67%  |
| 0     | 10        | 3.18%   |
| 3     | 9         | 2.87%   |
| 4     | 2         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 299       | 95.22%  |
| Yes  | 15        | 4.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 79        | 41.15%  |
| Realtek Semiconductor           | 24        | 12.5%   |
| Qualcomm Atheros Communications | 20        | 10.42%  |
| Cambridge Silicon Radio         | 13        | 6.77%   |
| Broadcom                        | 12        | 6.25%   |
| Apple                           | 9         | 4.69%   |
| Lite-On Technology              | 7         | 3.65%   |
| Foxconn / Hon Hai               | 6         | 3.13%   |
| IMC Networks                    | 5         | 2.6%    |
| Hewlett-Packard                 | 4         | 2.08%   |
| Toshiba                         | 3         | 1.56%   |
| ASUSTek Computer                | 3         | 1.56%   |
| MediaTek                        | 2         | 1.04%   |
| Dell                            | 2         | 1.04%   |
| TP-Link                         | 1         | 0.52%   |
| Realtek                         | 1         | 0.52%   |
| Marvell Semiconductor           | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 14.06%  |
| Intel AX201 Bluetooth                               | 13        | 6.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 6.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 6.25%   |
| Realtek Bluetooth Radio                             | 11        | 5.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 5.73%   |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 5.21%   |
| Intel AX200 Bluetooth                               | 10        | 5.21%   |
| Intel AX211 Bluetooth                               | 7         | 3.65%   |
| Apple Bluetooth Host Controller                     | 5         | 2.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.08%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 2.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.56%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.56%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.56%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.56%   |
| Toshiba Bluetooth Device                            | 2         | 1.04%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.04%   |
| MediaTek Wireless_Device                            | 2         | 1.04%   |
| Lite-On Wireless_Device                             | 2         | 1.04%   |
| Lite-On Bluetooth Device                            | 2         | 1.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.04%   |
| Intel AX210 Bluetooth                               | 2         | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.04%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.04%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 0.52%   |
| Toshiba BCM43142A0                                  | 1         | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.52%   |
| Realtek Bluetooth Radio                             | 1         | 0.52%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.52%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.52%   |
| IMC Networks Wireless_Device                        | 1         | 0.52%   |
| IMC Networks Bluetooth                              | 1         | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 234       | 56.52%  |
| AMD                     | 76        | 18.36%  |
| Nvidia                  | 57        | 13.77%  |
| C-Media Electronics     | 6         | 1.45%   |
| Realtek Semiconductor   | 4         | 0.97%   |
| Logitech                | 4         | 0.97%   |
| GN Netcom               | 4         | 0.97%   |
| Generalplus Technology  | 3         | 0.72%   |
| Unknown                 | 2         | 0.48%   |
| Sony                    | 2         | 0.48%   |
| Plantronics             | 2         | 0.48%   |
| Lenovo                  | 2         | 0.48%   |
| KTMicro                 | 2         | 0.48%   |
| JMTek                   | 2         | 0.48%   |
| Soundprese              | 1         | 0.24%   |
| Medeli Electronics      | 1         | 0.24%   |
| Kingston Technology     | 1         | 0.24%   |
| Hewlett-Packard         | 1         | 0.24%   |
| Ensoniq                 | 1         | 0.24%   |
| Creative Labs           | 1         | 0.24%   |
| Corsair                 | 1         | 0.24%   |
| CMX Systems             | 1         | 0.24%   |
| Blue Microphones        | 1         | 0.24%   |
| BEHRINGER International | 1         | 0.24%   |
| Astro Gaming            | 1         | 0.24%   |
| Argosy Research         | 1         | 0.24%   |
| Afatech                 | 1         | 0.24%   |
| A-DATA Technology       | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 28        | 5.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 4.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 4.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 3.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 3.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 2.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 2.42%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.22%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 2.02%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 9         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.81%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.81%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.61%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 1.61%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.21%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.21%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.81%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.81%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4         | 0.81%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 0.81%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.6%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 52        | 23.53%  |
| SK hynix            | 37        | 16.74%  |
| Kingston            | 29        | 13.12%  |
| Micron Technology   | 27        | 12.22%  |
| Crucial             | 17        | 7.69%   |
| A-DATA Technology   | 11        | 4.98%   |
| Unknown             | 8         | 3.62%   |
| Corsair             | 8         | 3.62%   |
| G.Skill             | 7         | 3.17%   |
| Ramaxel Technology  | 5         | 2.26%   |
| Nanya Technology    | 5         | 2.26%   |
| Team                | 4         | 1.81%   |
| Unknown (ABCD)      | 3         | 1.36%   |
| Patriot             | 2         | 0.9%    |
| V-Color             | 1         | 0.45%   |
| Transcend           | 1         | 0.45%   |
| Super Talent        | 1         | 0.45%   |
| Kimtigo             | 1         | 0.45%   |
| fef5                | 1         | 0.45%   |
| Unknown             | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.02%   |
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 5         | 2.02%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 4         | 1.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.61%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 1.61%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 4         | 1.61%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 1.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 3         | 1.21%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.21%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s            | 3         | 1.21%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 0.81%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.81%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.81%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.81%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.81%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.81%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.81%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s             | 2         | 0.81%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s        | 2         | 0.81%   |
| A-DATA RAM Module 16GB DIMM DDR4 2667MT/s                        | 2         | 0.81%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 2         | 0.81%   |
| V-Color RAM TN4G8C11-H11 4GB DIMM DDR3 1600MT/s                  | 1         | 0.4%    |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.4%    |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.4%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 82        | 44.57%  |
| DDR3    | 68        | 36.96%  |
| LPDDR4  | 11        | 5.98%   |
| SDRAM   | 7         | 3.8%    |
| DDR5    | 5         | 2.72%   |
| DDR2    | 5         | 2.72%   |
| LPDDR5  | 3         | 1.63%   |
| Unknown | 2         | 1.09%   |
| LPDDR3  | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 63.89%  |
| DIMM         | 49        | 27.22%  |
| Row Of Chips | 14        | 7.78%   |
| Chip         | 1         | 0.56%   |
| Unknown      | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 80        | 38.28%  |
| 4096  | 71        | 33.97%  |
| 16384 | 24        | 11.48%  |
| 2048  | 17        | 8.13%   |
| 32768 | 15        | 7.18%   |
| 1024  | 2         | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 24.06%  |
| 2667    | 37        | 17.45%  |
| 3200    | 22        | 10.38%  |
| 1333    | 13        | 6.13%   |
| 2400    | 12        | 5.66%   |
| 2133    | 8         | 3.77%   |
| 1334    | 8         | 3.77%   |
| 3600    | 7         | 3.3%    |
| 4267    | 5         | 2.36%   |
| 3266    | 5         | 2.36%   |
| 667     | 5         | 2.36%   |
| 2933    | 4         | 1.89%   |
| 6400    | 3         | 1.42%   |
| 4800    | 3         | 1.42%   |
| 1867    | 3         | 1.42%   |
| Unknown | 3         | 1.42%   |
| 5600    | 2         | 0.94%   |
| 4199    | 2         | 0.94%   |
| 1067    | 2         | 0.94%   |
| 8400    | 1         | 0.47%   |
| 4000    | 1         | 0.47%   |
| 3866    | 1         | 0.47%   |
| 3666    | 1         | 0.47%   |
| 3466    | 1         | 0.47%   |
| 3400    | 1         | 0.47%   |
| 3100    | 1         | 0.47%   |
| 3066    | 1         | 0.47%   |
| 2934    | 1         | 0.47%   |
| 2666    | 1         | 0.47%   |
| 2465    | 1         | 0.47%   |
| 2448    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 2000    | 1         | 0.47%   |
| 1866    | 1         | 0.47%   |
| 1800    | 1         | 0.47%   |
| 800     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 4         | 44.44%  |
| Seiko Epson     | 3         | 33.33%  |
| Canon           | 2         | 22.22%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L382 Series            | 1         | 11.11%  |
| Seiko Epson L360 Series            | 1         | 11.11%  |
| Seiko Epson L3110 Series           | 1         | 11.11%  |
| HP Ink Tank Wireless 410 series    | 1         | 11.11%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 11.11%  |
| HP DeskJet 2130 series             | 1         | 11.11%  |
| HP Deskjet 2050 J510               | 1         | 11.11%  |
| Canon G2000 series                 | 1         | 11.11%  |
| Canon E400 series                  | 1         | 11.11%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 19.05%  |
| Microdia                               | 24        | 11.43%  |
| Realtek Semiconductor                  | 20        | 9.52%   |
| Sunplus Innovation Technology          | 17        | 8.1%    |
| IMC Networks                           | 15        | 7.14%   |
| Apple                                  | 10        | 4.76%   |
| Logitech                               | 9         | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.81%   |
| Quanta                                 | 7         | 3.33%   |
| Lite-On Technology                     | 7         | 3.33%   |
| Bison Electronics                      | 6         | 2.86%   |
| Microsoft                              | 5         | 2.38%   |
| Alcor Micro                            | 5         | 2.38%   |
| Syntek                                 | 4         | 1.9%    |
| Silicon Motion                         | 4         | 1.9%    |
| Primax Electronics                     | 4         | 1.9%    |
| Luxvisions Innotech Limited            | 4         | 1.9%    |
| Suyin                                  | 3         | 1.43%   |
| Z-Star Microelectronics                | 2         | 0.95%   |
| TANDBERG                               | 1         | 0.48%   |
| Sonix Technology                       | 1         | 0.48%   |
| Samsung Electronics                    | 1         | 0.48%   |
| Philips (or NXP)                       | 1         | 0.48%   |
| LG Electronics                         | 1         | 0.48%   |
| Jieli Technology                       | 1         | 0.48%   |
| Importek                               | 1         | 0.48%   |
| Huawei Technologies                    | 1         | 0.48%   |
| GEMBIRD                                | 1         | 0.48%   |
| Creative Technology                    | 1         | 0.48%   |
| BRS 2Mp Camera                         | 1         | 0.48%   |
| Aveo Technology                        | 1         | 0.48%   |
| Arkmicro Technologies                  | 1         | 0.48%   |
| Alpha Imaging Technology               | 1         | 0.48%   |
| ALi                                    | 1         | 0.48%   |
| Acer                                   | 1         | 0.48%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 14        | 6.51%   |
| Chicony Integrated Camera                           | 9         | 4.19%   |
| Realtek Integrated_Webcam_HD                        | 8         | 3.72%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 2.79%   |
| Sunplus HD WebCam                                   | 5         | 2.33%   |
| IMC Networks Integrated Camera                      | 5         | 2.33%   |
| Apple FaceTime HD Camera                            | 5         | 2.33%   |
| Alcor Micro USB 2.0 Camera                          | 4         | 1.86%   |
| Realtek Integrated Webcam                           | 3         | 1.4%    |
| Primax HP HD Webcam [Fixed]                         | 3         | 1.4%    |
| Microsoft LifeCam HD-3000                           | 3         | 1.4%    |
| Microdia Integrated Camera                          | 3         | 1.4%    |
| Logitech Webcam C270                                | 3         | 1.4%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 1.4%    |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 1.4%    |
| Chicony HP HD Camera                                | 3         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 3         | 1.4%    |
| Syntek Integrated Camera                            | 2         | 0.93%   |
| Syntek EasyCamera                                   | 2         | 0.93%   |
| Sunplus HP HD Webcam [Fixed]                        | 2         | 0.93%   |
| Realtek USB2.0 camera                               | 2         | 0.93%   |
| Realtek Integrated Webcam HD                        | 2         | 0.93%   |
| Quanta HP TrueVision HD Camera                      | 2         | 0.93%   |
| Quanta HD WebCam                                    | 2         | 0.93%   |
| Microdia USB 2.0 Camera                             | 2         | 0.93%   |
| Microdia Integrated Webcam                          | 2         | 0.93%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.93%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 0.93%   |
| Lite-On HP HD Camera                                | 2         | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 0.93%   |
| Chicony USB 2.0 Camera                              | 2         | 0.93%   |
| Chicony Integrated HP HD Webcam                     | 2         | 0.93%   |
| Chicony HP Truevision HD                            | 2         | 0.93%   |
| Chicony HP HD Webcam                                | 2         | 0.93%   |
| Chicony HD WebCam                                   | 2         | 0.93%   |
| Chicony 720p HD Camera                              | 2         | 0.93%   |
| Bison Integrated Camera                             | 2         | 0.93%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 0.93%   |
| Z-Star Vimicro USB Camera (Altair)                  | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 43.59%  |
| Synaptics                  | 11        | 28.21%  |
| Shenzhen Goodix Technology | 4         | 10.26%  |
| Elan Microelectronics      | 2         | 5.13%   |
| Upek                       | 1         | 2.56%   |
| STMicroelectronics         | 1         | 2.56%   |
| Samsung Electronics        | 1         | 2.56%   |
| LighTuning Technology      | 1         | 2.56%   |
| AuthenTec                  | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 10.26%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 10.26%  |
| Shenzhen Goodix  FingerPrint Device                    | 4         | 10.26%  |
| Validity Sensors VFS491                                | 3         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 5.13%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 5.13%   |
| Validity Sensors Synaptics WBDI                        | 2         | 5.13%   |
| Synaptics WBDI                                         | 2         | 5.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 5.13%   |
| Synaptics Fingerprint reader [HP G6]                   | 2         | 5.13%   |
| Elan ELAN:ARM-M4                                       | 2         | 5.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.56%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.56%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.56%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 2.56%   |
| Synaptics Prometheus Fingerprint Reader                | 1         | 2.56%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 2.56%   |
| Samsung Fingerprint Device                             | 1         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.56%   |
| AuthenTec AES1600                                      | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 5         | 33.33%  |
| Athena Smartcard Solutions | 4         | 26.67%  |
| O2 Micro                   | 3         | 20%     |
| SCM Microsystems           | 1         | 6.67%   |
| OmniKey                    | 1         | 6.67%   |
| Alcor Micro                | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Athena Smartcard Solutions ASEDrive V3C                                      | 4         | 26.67%  |
| Broadcom 5880                                                                | 3         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 13.33%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 6.67%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 6.67%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| Broadcom 58200                                                               | 1         | 6.67%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 216       | 67.92%  |
| 1     | 86        | 27.04%  |
| 2     | 10        | 3.14%   |
| 3     | 6         | 1.89%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 30.89%  |
| Graphics card            | 29        | 23.58%  |
| Net/wireless             | 22        | 17.89%  |
| Chipcard                 | 12        | 9.76%   |
| Communication controller | 5         | 4.07%   |
| Multimedia controller    | 4         | 3.25%   |
| Sound                    | 2         | 1.63%   |
| Firewire controller      | 2         | 1.63%   |
| Camera                   | 2         | 1.63%   |
| Unassigned class         | 1         | 0.81%   |
| Storage/raid             | 1         | 0.81%   |
| Storage                  | 1         | 0.81%   |
| Network                  | 1         | 0.81%   |
| Net/ethernet             | 1         | 0.81%   |
| Card reader              | 1         | 0.81%   |
| Bluetooth                | 1         | 0.81%   |


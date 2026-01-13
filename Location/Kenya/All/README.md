Linux in Kenya - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Kenya.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Kenya/Desktop/README.md) and [notebooks](/Location/Kenya/Notebook/README.md).

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

Total: 574

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G5            | Notebook    | [6cc9c29ba1](https://linux-hardware.org/?probe=6cc9c29ba1) | Dec 30, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [b50814f0fe](https://linux-hardware.org/?probe=b50814f0fe) | Dec 30, 2025 |
| HP            | ProBook 4540s               | Notebook    | [efe3c0406d](https://linux-hardware.org/?probe=efe3c0406d) | Dec 27, 2025 |
| MSI           | MAG X870 TOMAHAWK WIFI      | Desktop     | [c10f04886b](https://linux-hardware.org/?probe=c10f04886b) | Dec 12, 2025 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [13134d9da7](https://linux-hardware.org/?probe=13134d9da7) | Dec 08, 2025 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [22f1cd6ce3](https://linux-hardware.org/?probe=22f1cd6ce3) | Dec 08, 2025 |
| Dell          | Latitude 3510               | Notebook    | [870c170439](https://linux-hardware.org/?probe=870c170439) | Nov 26, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [54225e4f3f](https://linux-hardware.org/?probe=54225e4f3f) | Nov 22, 2025 |
| HP            | EliteBook x360 1040 G5      | Convertible | [1d9c3c8541](https://linux-hardware.org/?probe=1d9c3c8541) | Nov 20, 2025 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [e2e023ad8f](https://linux-hardware.org/?probe=e2e023ad8f) | Nov 17, 2025 |
| HP            | EliteBook x360 1040 G5      | Convertible | [3e603ea699](https://linux-hardware.org/?probe=3e603ea699) | Nov 13, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [df2324b246](https://linux-hardware.org/?probe=df2324b246) | Oct 18, 2025 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [125ec15e32](https://linux-hardware.org/?probe=125ec15e32) | Oct 06, 2025 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [5b23458051](https://linux-hardware.org/?probe=5b23458051) | Sep 28, 2025 |
| Dell          | Vostro 3420                 | Notebook    | [26cbd343be](https://linux-hardware.org/?probe=26cbd343be) | Sep 25, 2025 |
| Gigabyte      | B650M DS3H                  | Desktop     | [d868136c6f](https://linux-hardware.org/?probe=d868136c6f) | Sep 12, 2025 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [f181067304](https://linux-hardware.org/?probe=f181067304) | Sep 09, 2025 |
| Dell          | Latitude 7280               | Notebook    | [0ec6b0a54d](https://linux-hardware.org/?probe=0ec6b0a54d) | Aug 27, 2025 |
| Dell          | Latitude 7280               | Notebook    | [63529d09a8](https://linux-hardware.org/?probe=63529d09a8) | Aug 27, 2025 |
| HP            | 18E7                        | Desktop     | [6269efd6b1](https://linux-hardware.org/?probe=6269efd6b1) | Aug 21, 2025 |
| HP            | 245 14 inch G10 Notebook... | Notebook    | [43d5b2db82](https://linux-hardware.org/?probe=43d5b2db82) | Aug 17, 2025 |
| HP            | EliteBook 840 G1            | Notebook    | [dd3aa85220](https://linux-hardware.org/?probe=dd3aa85220) | Jul 22, 2025 |
| Dell          | Precision 5530              | Notebook    | [9c04b30b38](https://linux-hardware.org/?probe=9c04b30b38) | Jul 17, 2025 |
| HP            | EliteBook 8440p             | Notebook    | [977e01cfb6](https://linux-hardware.org/?probe=977e01cfb6) | Jul 14, 2025 |
| Colorful T... | CVN B450M GAMING V14        | Desktop     | [fe34223992](https://linux-hardware.org/?probe=fe34223992) | Jul 14, 2025 |
| Colorful T... | CVN B450M GAMING V14        | Desktop     | [077f3fc1f6](https://linux-hardware.org/?probe=077f3fc1f6) | Jul 14, 2025 |
| Gigabyte      | B650M K                     | Desktop     | [755e2969c6](https://linux-hardware.org/?probe=755e2969c6) | Jul 09, 2025 |
| Dell          | Latitude E6400              | Notebook    | [a32c34ab17](https://linux-hardware.org/?probe=a32c34ab17) | Jul 09, 2025 |
| Dell          | Latitude E6400              | Notebook    | [62a8583a23](https://linux-hardware.org/?probe=62a8583a23) | Jul 09, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [f0b2c77a35](https://linux-hardware.org/?probe=f0b2c77a35) | Jun 25, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [57bdbc6c0a](https://linux-hardware.org/?probe=57bdbc6c0a) | Jun 20, 2025 |
| HP            | EliteBook 820 G3            | Notebook    | [7425928cb9](https://linux-hardware.org/?probe=7425928cb9) | Jun 16, 2025 |
| Dell          | G15 5530                    | Notebook    | [f91cfbf2c0](https://linux-hardware.org/?probe=f91cfbf2c0) | Jun 12, 2025 |
| HP            | 815A                        | Mini pc     | [cc20e2207b](https://linux-hardware.org/?probe=cc20e2207b) | Jun 02, 2025 |
| Lenovo        | ThinkPad T440s 20ARS2980... | Notebook    | [fe6788baff](https://linux-hardware.org/?probe=fe6788baff) | Jun 02, 2025 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [ea01944914](https://linux-hardware.org/?probe=ea01944914) | May 25, 2025 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f5080090c9](https://linux-hardware.org/?probe=f5080090c9) | May 17, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [57abebc292](https://linux-hardware.org/?probe=57abebc292) | May 16, 2025 |
| HP            | Notebook                    | Notebook    | [926c89d26a](https://linux-hardware.org/?probe=926c89d26a) | Apr 27, 2025 |
| Gigabyte      | B450 AORUS M                | Desktop     | [35bc3f038e](https://linux-hardware.org/?probe=35bc3f038e) | Apr 27, 2025 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [df0fce7dd7](https://linux-hardware.org/?probe=df0fce7dd7) | Apr 25, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [611457c5a3](https://linux-hardware.org/?probe=611457c5a3) | Apr 24, 2025 |
| HP            | 2B43                        | Desktop     | [c0c5b8ea1e](https://linux-hardware.org/?probe=c0c5b8ea1e) | Apr 17, 2025 |
| Dell          | Latitude 7320               | Convertible | [7488a3da19](https://linux-hardware.org/?probe=7488a3da19) | Apr 15, 2025 |
| Dell          | XPS 9320                    | Notebook    | [210fd65a00](https://linux-hardware.org/?probe=210fd65a00) | Apr 08, 2025 |
| AZW           | Gemini T34                  | Desktop     | [d4cf24657d](https://linux-hardware.org/?probe=d4cf24657d) | Apr 06, 2025 |
| HP            | Laptop 15-bs1xx             | Notebook    | [6a462d107b](https://linux-hardware.org/?probe=6a462d107b) | Mar 19, 2025 |
| HP            | Laptop 15-bs1xx             | Notebook    | [638f91092d](https://linux-hardware.org/?probe=638f91092d) | Mar 19, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [816accfc42](https://linux-hardware.org/?probe=816accfc42) | Mar 06, 2025 |
| ASUSTek       | UX305CA                     | Notebook    | [97cda9f826](https://linux-hardware.org/?probe=97cda9f826) | Feb 28, 2025 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [4c0f1295a2](https://linux-hardware.org/?probe=4c0f1295a2) | Feb 18, 2025 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [4a0b4ecde1](https://linux-hardware.org/?probe=4a0b4ecde1) | Feb 16, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [5637a1738f](https://linux-hardware.org/?probe=5637a1738f) | Feb 13, 2025 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [14d7214f50](https://linux-hardware.org/?probe=14d7214f50) | Feb 09, 2025 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cbe8bc394e](https://linux-hardware.org/?probe=cbe8bc394e) | Feb 01, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [47ce128cf7](https://linux-hardware.org/?probe=47ce128cf7) | Jan 25, 2025 |
| Dell          | 0XR1GT A00                  | Desktop     | [455ec3b313](https://linux-hardware.org/?probe=455ec3b313) | Jan 20, 2025 |
| Toshiba       | dynabook R73/H              | Notebook    | [8e9f89b0cf](https://linux-hardware.org/?probe=8e9f89b0cf) | Jan 17, 2025 |
| HP            | ProBook 650 G2              | Notebook    | [473fc7db12](https://linux-hardware.org/?probe=473fc7db12) | Jan 14, 2025 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [83cadd4c99](https://linux-hardware.org/?probe=83cadd4c99) | Jan 13, 2025 |
| Lenovo        | ThinkPad X280 20KES91F00    | Notebook    | [ba9b318a26](https://linux-hardware.org/?probe=ba9b318a26) | Jan 13, 2025 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [dd7ea1bfca](https://linux-hardware.org/?probe=dd7ea1bfca) | Jan 03, 2025 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [fa670e4eca](https://linux-hardware.org/?probe=fa670e4eca) | Dec 29, 2024 |
| Acer          | Predator PT516-51s          | Notebook    | [ba15b5dd07](https://linux-hardware.org/?probe=ba15b5dd07) | Dec 27, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [4804abe046](https://linux-hardware.org/?probe=4804abe046) | Dec 26, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [cf6ba1ead2](https://linux-hardware.org/?probe=cf6ba1ead2) | Dec 25, 2024 |
| Dell          | Latitude 7420               | Notebook    | [754cef3d2f](https://linux-hardware.org/?probe=754cef3d2f) | Dec 20, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [7d0e5bbe48](https://linux-hardware.org/?probe=7d0e5bbe48) | Dec 14, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [747ae84f9e](https://linux-hardware.org/?probe=747ae84f9e) | Dec 12, 2024 |
| HP            | ProBook 430 G2              | Notebook    | [7d778aaa23](https://linux-hardware.org/?probe=7d778aaa23) | Dec 04, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [83b3abf058](https://linux-hardware.org/?probe=83b3abf058) | Dec 02, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [cf93e45cdf](https://linux-hardware.org/?probe=cf93e45cdf) | Dec 02, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [c791f3500c](https://linux-hardware.org/?probe=c791f3500c) | Dec 02, 2024 |
| HP            | ProBook 6560b               | Notebook    | [a7224d17ca](https://linux-hardware.org/?probe=a7224d17ca) | Dec 01, 2024 |
| Jemper        | EZPAD WS_reserve            | Notebook    | [120200526f](https://linux-hardware.org/?probe=120200526f) | Nov 23, 2024 |
| HP            | 86E9 A                      | Desktop     | [276cb1d5a9](https://linux-hardware.org/?probe=276cb1d5a9) | Nov 22, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [71d4704433](https://linux-hardware.org/?probe=71d4704433) | Nov 18, 2024 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [102430b4e4](https://linux-hardware.org/?probe=102430b4e4) | Nov 18, 2024 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [6c93a82662](https://linux-hardware.org/?probe=6c93a82662) | Nov 12, 2024 |
| HP            | EliteBook x360 1030 G2      | Convertible | [4c4d795e04](https://linux-hardware.org/?probe=4c4d795e04) | Nov 11, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [f4d3b8c11f](https://linux-hardware.org/?probe=f4d3b8c11f) | Nov 06, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [2bc5e66879](https://linux-hardware.org/?probe=2bc5e66879) | Nov 04, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [237d42f7fc](https://linux-hardware.org/?probe=237d42f7fc) | Nov 04, 2024 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [386606f6bd](https://linux-hardware.org/?probe=386606f6bd) | Nov 04, 2024 |
| Dell          | 0C3YXR A00                  | Desktop     | [e681ee2258](https://linux-hardware.org/?probe=e681ee2258) | Nov 03, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [170e80b380](https://linux-hardware.org/?probe=170e80b380) | Oct 23, 2024 |
| TECNO         | WinPad 2                    | Notebook    | [1cb685a8f9](https://linux-hardware.org/?probe=1cb685a8f9) | Oct 19, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [738c69c20e](https://linux-hardware.org/?probe=738c69c20e) | Oct 10, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [ce808338c2](https://linux-hardware.org/?probe=ce808338c2) | Oct 03, 2024 |
| HP            | 843B                        | Desktop     | [78e41c4cf2](https://linux-hardware.org/?probe=78e41c4cf2) | Oct 01, 2024 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [d8bf22df1c](https://linux-hardware.org/?probe=d8bf22df1c) | Sep 29, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [55eb1cb193](https://linux-hardware.org/?probe=55eb1cb193) | Sep 28, 2024 |
| SLIMBOOK      | Executive                   | Notebook    | [bf66c459b2](https://linux-hardware.org/?probe=bf66c459b2) | Sep 27, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [915bab9e91](https://linux-hardware.org/?probe=915bab9e91) | Sep 27, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [d28a7d92f7](https://linux-hardware.org/?probe=d28a7d92f7) | Sep 08, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [375da72314](https://linux-hardware.org/?probe=375da72314) | Sep 08, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [9a594bf56d](https://linux-hardware.org/?probe=9a594bf56d) | Sep 06, 2024 |
| HP            | EliteBook 850 G5            | Notebook    | [a8047158de](https://linux-hardware.org/?probe=a8047158de) | Aug 31, 2024 |
| HP            | ProBook 6470b               | Notebook    | [0f3e431d44](https://linux-hardware.org/?probe=0f3e431d44) | Aug 27, 2024 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [84cb8afc07](https://linux-hardware.org/?probe=84cb8afc07) | Aug 18, 2024 |
| Dell          | Latitude D430               | Notebook    | [4346500f96](https://linux-hardware.org/?probe=4346500f96) | Aug 16, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [9d398bbfc9](https://linux-hardware.org/?probe=9d398bbfc9) | Aug 13, 2024 |
| Lenovo        | B51-30 80LK                 | Notebook    | [e4f72a3222](https://linux-hardware.org/?probe=e4f72a3222) | Aug 08, 2024 |
| Lenovo        | B51-30 80LK                 | Notebook    | [8003cbb98e](https://linux-hardware.org/?probe=8003cbb98e) | Aug 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [4f54877e82](https://linux-hardware.org/?probe=4f54877e82) | Aug 06, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [d9b8f3df7b](https://linux-hardware.org/?probe=d9b8f3df7b) | Aug 02, 2024 |
| HP            | 89B4 A                      | Desktop     | [1180efce7b](https://linux-hardware.org/?probe=1180efce7b) | Jul 30, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [92d14a9e27](https://linux-hardware.org/?probe=92d14a9e27) | Jul 28, 2024 |
| Dell          | 06X1TJ A00                  | Desktop     | [e4ada8d19e](https://linux-hardware.org/?probe=e4ada8d19e) | Jul 26, 2024 |
| HP            | 09CCh                       | Desktop     | [ee256569f1](https://linux-hardware.org/?probe=ee256569f1) | Jul 18, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [d243d082ff](https://linux-hardware.org/?probe=d243d082ff) | Jul 13, 2024 |
| Toshiba       | TECRA X40-E                 | Notebook    | [f8de6267c6](https://linux-hardware.org/?probe=f8de6267c6) | Jul 12, 2024 |
| Dell          | 0XR1GT A00                  | Desktop     | [a2aa1e0463](https://linux-hardware.org/?probe=a2aa1e0463) | Jul 08, 2024 |
| Dell          | Latitude E7450              | Notebook    | [13e9eb3e22](https://linux-hardware.org/?probe=13e9eb3e22) | Jul 05, 2024 |
| HP            | Laptop 15-da1xxx            | Notebook    | [99828b86d7](https://linux-hardware.org/?probe=99828b86d7) | Jun 28, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [7ab8af1195](https://linux-hardware.org/?probe=7ab8af1195) | Jun 21, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [ae95ca44f4](https://linux-hardware.org/?probe=ae95ca44f4) | Jun 21, 2024 |
| HP            | 630                         | Notebook    | [8b8b94da0e](https://linux-hardware.org/?probe=8b8b94da0e) | Jun 18, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES4... | Convertible | [da632f0b9d](https://linux-hardware.org/?probe=da632f0b9d) | Jun 11, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [011ca73a2d](https://linux-hardware.org/?probe=011ca73a2d) | Jun 09, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [89ea334b6b](https://linux-hardware.org/?probe=89ea334b6b) | Jun 08, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [9ffce6984c](https://linux-hardware.org/?probe=9ffce6984c) | Jun 07, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [f655bfbf19](https://linux-hardware.org/?probe=f655bfbf19) | May 31, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [e4bd2bd16c](https://linux-hardware.org/?probe=e4bd2bd16c) | May 30, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [b1cb90274b](https://linux-hardware.org/?probe=b1cb90274b) | May 29, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [9f1460dd7f](https://linux-hardware.org/?probe=9f1460dd7f) | May 19, 2024 |
| Toshiba       | TECRA X40-E                 | Notebook    | [e5f6efb109](https://linux-hardware.org/?probe=e5f6efb109) | May 14, 2024 |
| HP            | 815A                        | Mini pc     | [44b77bda73](https://linux-hardware.org/?probe=44b77bda73) | May 07, 2024 |
| HP            | 1494                        | Desktop     | [7b5806585f](https://linux-hardware.org/?probe=7b5806585f) | May 04, 2024 |
| Lenovo        | ThinkPad P72 20MCS1A400     | Notebook    | [2fb5a9e91b](https://linux-hardware.org/?probe=2fb5a9e91b) | May 02, 2024 |
| Lenovo        | ThinkPad P72 20MCS1A400     | Notebook    | [11cfebd1f9](https://linux-hardware.org/?probe=11cfebd1f9) | May 02, 2024 |
| Dell          | 0KRC95 A00                  | Desktop     | [72ba135dda](https://linux-hardware.org/?probe=72ba135dda) | May 01, 2024 |
| Dell          | 0WWJRX A01                  | Desktop     | [21af8ccdc8](https://linux-hardware.org/?probe=21af8ccdc8) | Apr 27, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [9ad3b0be60](https://linux-hardware.org/?probe=9ad3b0be60) | Apr 24, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [290ea848f0](https://linux-hardware.org/?probe=290ea848f0) | Apr 19, 2024 |
| HP            | ZBook 15 G6                 | Notebook    | [e8ad21a64f](https://linux-hardware.org/?probe=e8ad21a64f) | Apr 11, 2024 |
| HP            | EliteBook 2760p             | Notebook    | [438956801b](https://linux-hardware.org/?probe=438956801b) | Apr 09, 2024 |
| HP            | EliteBook 2760p             | Notebook    | [9ab7018eab](https://linux-hardware.org/?probe=9ab7018eab) | Apr 04, 2024 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [558856655f](https://linux-hardware.org/?probe=558856655f) | Mar 21, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [7ac30f9e22](https://linux-hardware.org/?probe=7ac30f9e22) | Mar 18, 2024 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [3bb66ce50a](https://linux-hardware.org/?probe=3bb66ce50a) | Mar 12, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [29aa21542a](https://linux-hardware.org/?probe=29aa21542a) | Feb 22, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [4a3954a4c1](https://linux-hardware.org/?probe=4a3954a4c1) | Feb 02, 2024 |
| HP            | ProBook 440 G1              | Notebook    | [1a7d0f5488](https://linux-hardware.org/?probe=1a7d0f5488) | Feb 01, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [130befb564](https://linux-hardware.org/?probe=130befb564) | Jan 16, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [385ad48703](https://linux-hardware.org/?probe=385ad48703) | Jan 16, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [20eede7cbf](https://linux-hardware.org/?probe=20eede7cbf) | Jan 12, 2024 |
| ASUSTek       | X540NA                      | Notebook    | [1f6d0e42df](https://linux-hardware.org/?probe=1f6d0e42df) | Jan 10, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [01a010ceeb](https://linux-hardware.org/?probe=01a010ceeb) | Jan 02, 2024 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [81e91658c9](https://linux-hardware.org/?probe=81e91658c9) | Dec 30, 2023 |
| HP            | 0968h                       | Desktop     | [b1fb94198e](https://linux-hardware.org/?probe=b1fb94198e) | Dec 10, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [a1a93224e4](https://linux-hardware.org/?probe=a1a93224e4) | Dec 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [d24b2b8298](https://linux-hardware.org/?probe=d24b2b8298) | Nov 28, 2023 |
| HP            | ProBook 4540s               | Notebook    | [6f65f2ceeb](https://linux-hardware.org/?probe=6f65f2ceeb) | Nov 26, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [17b5d35090](https://linux-hardware.org/?probe=17b5d35090) | Nov 19, 2023 |
| Dell          | Latitude 5300               | Notebook    | [8f1ed5747c](https://linux-hardware.org/?probe=8f1ed5747c) | Nov 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [48705484f5](https://linux-hardware.org/?probe=48705484f5) | Nov 15, 2023 |
| HP            | ProBook 4540s               | Notebook    | [f8e4ef7043](https://linux-hardware.org/?probe=f8e4ef7043) | Nov 14, 2023 |
| Dell          | Latitude 3380               | Notebook    | [f88c4741cc](https://linux-hardware.org/?probe=f88c4741cc) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [f01a35c9a7](https://linux-hardware.org/?probe=f01a35c9a7) | Nov 06, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2430... | Notebook    | [658d6f150e](https://linux-hardware.org/?probe=658d6f150e) | Nov 05, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | Notebook    | [8df2c91111](https://linux-hardware.org/?probe=8df2c91111) | Oct 29, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1f244ed949](https://linux-hardware.org/?probe=1f244ed949) | Oct 19, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [5921ebc3f7](https://linux-hardware.org/?probe=5921ebc3f7) | Oct 18, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [b6619c64fd](https://linux-hardware.org/?probe=b6619c64fd) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [407b6f9273](https://linux-hardware.org/?probe=407b6f9273) | Oct 15, 2023 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [85caa55933](https://linux-hardware.org/?probe=85caa55933) | Oct 14, 2023 |
| HP            | 18E7                        | Desktop     | [855ab006c1](https://linux-hardware.org/?probe=855ab006c1) | Oct 13, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [9f4ab6a725](https://linux-hardware.org/?probe=9f4ab6a725) | Oct 11, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a6ac161796](https://linux-hardware.org/?probe=a6ac161796) | Sep 24, 2023 |
| Endless       | EF20EA                      | Notebook    | [492a9e4f5e](https://linux-hardware.org/?probe=492a9e4f5e) | Sep 23, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [fd6d63df98](https://linux-hardware.org/?probe=fd6d63df98) | Sep 15, 2023 |
| MSI           | MPG Z690 EDGE WIFI          | Desktop     | [2ad1c71fce](https://linux-hardware.org/?probe=2ad1c71fce) | Sep 13, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c549b7a562](https://linux-hardware.org/?probe=c549b7a562) | Sep 12, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [26fe63f6ba](https://linux-hardware.org/?probe=26fe63f6ba) | Sep 12, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [c8ef60f2e0](https://linux-hardware.org/?probe=c8ef60f2e0) | Sep 12, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [c8e3010177](https://linux-hardware.org/?probe=c8e3010177) | Sep 10, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [f898a390e2](https://linux-hardware.org/?probe=f898a390e2) | Sep 09, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [71dad1a9b9](https://linux-hardware.org/?probe=71dad1a9b9) | Sep 09, 2023 |
| Lenovo        | NOK                         | Desktop     | [30f2c89249](https://linux-hardware.org/?probe=30f2c89249) | Sep 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [1d1c8e33ff](https://linux-hardware.org/?probe=1d1c8e33ff) | Sep 06, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0fe16a99d6](https://linux-hardware.org/?probe=0fe16a99d6) | Sep 03, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [b3a358a06f](https://linux-hardware.org/?probe=b3a358a06f) | Sep 03, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [40f2588fd0](https://linux-hardware.org/?probe=40f2588fd0) | Aug 31, 2023 |
| HP            | Notebook                    | Notebook    | [6404f1dc3a](https://linux-hardware.org/?probe=6404f1dc3a) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | Notebook    | [e632335144](https://linux-hardware.org/?probe=e632335144) | Aug 25, 2023 |
| HP            | Notebook                    | Notebook    | [1d3025a033](https://linux-hardware.org/?probe=1d3025a033) | Aug 24, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [24a2760d65](https://linux-hardware.org/?probe=24a2760d65) | Aug 20, 2023 |
| HP            | ProBook 4540s               | Notebook    | [c965074769](https://linux-hardware.org/?probe=c965074769) | Aug 17, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [080867b516](https://linux-hardware.org/?probe=080867b516) | Aug 16, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [837cbb2cf1](https://linux-hardware.org/?probe=837cbb2cf1) | Aug 13, 2023 |
| Lenovo        | Legion S7 15ARH5 82HM       | Notebook    | [044df6f82e](https://linux-hardware.org/?probe=044df6f82e) | Aug 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c24d904ffb](https://linux-hardware.org/?probe=c24d904ffb) | Aug 06, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [68734d9dfa](https://linux-hardware.org/?probe=68734d9dfa) | Aug 04, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [695a7fad0f](https://linux-hardware.org/?probe=695a7fad0f) | Aug 03, 2023 |
| HP            | Notebook                    | Notebook    | [0e8585ef71](https://linux-hardware.org/?probe=0e8585ef71) | Aug 02, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [fef5d6f571](https://linux-hardware.org/?probe=fef5d6f571) | Jul 26, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cafa1082f8](https://linux-hardware.org/?probe=cafa1082f8) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [31b0d46f32](https://linux-hardware.org/?probe=31b0d46f32) | Jul 22, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [352cc6e31d](https://linux-hardware.org/?probe=352cc6e31d) | Jul 17, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [556ef4473f](https://linux-hardware.org/?probe=556ef4473f) | Jul 11, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [b815c86777](https://linux-hardware.org/?probe=b815c86777) | Jul 07, 2023 |
| HP            | ENVY 15                     | Notebook    | [d519c2699c](https://linux-hardware.org/?probe=d519c2699c) | Jul 06, 2023 |
| HP            | 3047h                       | Desktop     | [e60df0b6d1](https://linux-hardware.org/?probe=e60df0b6d1) | Jun 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88d7f8992f](https://linux-hardware.org/?probe=88d7f8992f) | Jun 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [88e2f62c6d](https://linux-hardware.org/?probe=88e2f62c6d) | Jun 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93587f51a9](https://linux-hardware.org/?probe=93587f51a9) | Jun 19, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [04329cdc14](https://linux-hardware.org/?probe=04329cdc14) | Jun 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6f4c06d514](https://linux-hardware.org/?probe=6f4c06d514) | Jun 14, 2023 |
| HP            | ProBook 4530s               | Notebook    | [bdb6739deb](https://linux-hardware.org/?probe=bdb6739deb) | Jun 07, 2023 |
| Dell          | Latitude E5510              | Notebook    | [353a2174af](https://linux-hardware.org/?probe=353a2174af) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cdbebd8a7e](https://linux-hardware.org/?probe=cdbebd8a7e) | Jun 04, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | Notebook    | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [f876b5169a](https://linux-hardware.org/?probe=f876b5169a) | May 25, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [08a1ae22b7](https://linux-hardware.org/?probe=08a1ae22b7) | May 25, 2023 |
| HP            | 15                          | Notebook    | [b62229cac1](https://linux-hardware.org/?probe=b62229cac1) | May 24, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [46015ea246](https://linux-hardware.org/?probe=46015ea246) | May 10, 2023 |
| Fujitsu       | T900                        | Notebook    | [d0233bc511](https://linux-hardware.org/?probe=d0233bc511) | May 06, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [b5602599f8](https://linux-hardware.org/?probe=b5602599f8) | May 06, 2023 |
| HP            | Notebook                    | Notebook    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | Notebook    | [082029ecf5](https://linux-hardware.org/?probe=082029ecf5) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | Notebook    | [e2f37d94cd](https://linux-hardware.org/?probe=e2f37d94cd) | May 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [c8b979d035](https://linux-hardware.org/?probe=c8b979d035) | Apr 30, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [95b5e79487](https://linux-hardware.org/?probe=95b5e79487) | Apr 30, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [7f30bca791](https://linux-hardware.org/?probe=7f30bca791) | Apr 28, 2023 |
| Dell          | Latitude E6410              | Notebook    | [52ada88fb1](https://linux-hardware.org/?probe=52ada88fb1) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [37eee19e22](https://linux-hardware.org/?probe=37eee19e22) | Apr 15, 2023 |
| Unknown       | Q-790                       | Desktop     | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [c90d525ee8](https://linux-hardware.org/?probe=c90d525ee8) | Mar 31, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [d5ba09feb1](https://linux-hardware.org/?probe=d5ba09feb1) | Mar 27, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [d1ba8cb8e9](https://linux-hardware.org/?probe=d1ba8cb8e9) | Mar 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [049eafecc8](https://linux-hardware.org/?probe=049eafecc8) | Mar 20, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [599f8de7ba](https://linux-hardware.org/?probe=599f8de7ba) | Mar 11, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [8e12f88524](https://linux-hardware.org/?probe=8e12f88524) | Mar 11, 2023 |
| ASUSTek       | UX32LA                      | Notebook    | [3432e951dd](https://linux-hardware.org/?probe=3432e951dd) | Mar 06, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | E51-80 80QB                 | Notebook    | [73794bde33](https://linux-hardware.org/?probe=73794bde33) | Mar 03, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f492107b66](https://linux-hardware.org/?probe=f492107b66) | Feb 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c9f0a04fcf](https://linux-hardware.org/?probe=c9f0a04fcf) | Feb 10, 2023 |
| HP            | 3047h                       | Desktop     | [bdb6af834f](https://linux-hardware.org/?probe=bdb6af834f) | Feb 08, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [311514a737](https://linux-hardware.org/?probe=311514a737) | Feb 07, 2023 |
| Toshiba       | Satellite C850D-B615        | Notebook    | [66a7f0123f](https://linux-hardware.org/?probe=66a7f0123f) | Feb 07, 2023 |
| Dell          | 0C8810                      | Desktop     | [1df9a88e4a](https://linux-hardware.org/?probe=1df9a88e4a) | Feb 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [caedc4c130](https://linux-hardware.org/?probe=caedc4c130) | Jan 29, 2023 |
| HP            | 630                         | Notebook    | [837878455e](https://linux-hardware.org/?probe=837878455e) | Jan 28, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5ad0221a16](https://linux-hardware.org/?probe=5ad0221a16) | Jan 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [d0fe42d2fd](https://linux-hardware.org/?probe=d0fe42d2fd) | Jan 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [940d192ea9](https://linux-hardware.org/?probe=940d192ea9) | Jan 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3bc61d7363](https://linux-hardware.org/?probe=3bc61d7363) | Jan 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cae0a5557a](https://linux-hardware.org/?probe=cae0a5557a) | Jan 12, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [00780c7a70](https://linux-hardware.org/?probe=00780c7a70) | Jan 11, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [54eaec4178](https://linux-hardware.org/?probe=54eaec4178) | Jan 10, 2023 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [29654c0c64](https://linux-hardware.org/?probe=29654c0c64) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [56e25a5805](https://linux-hardware.org/?probe=56e25a5805) | Dec 28, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [199df541f2](https://linux-hardware.org/?probe=199df541f2) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [856515e522](https://linux-hardware.org/?probe=856515e522) | Dec 19, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [3e518355b6](https://linux-hardware.org/?probe=3e518355b6) | Dec 17, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [eccd29cfac](https://linux-hardware.org/?probe=eccd29cfac) | Dec 17, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [0de958194e](https://linux-hardware.org/?probe=0de958194e) | Dec 15, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [84c7e04946](https://linux-hardware.org/?probe=84c7e04946) | Dec 08, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [580fb6172f](https://linux-hardware.org/?probe=580fb6172f) | Dec 07, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [645418a0dd](https://linux-hardware.org/?probe=645418a0dd) | Nov 30, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [2a4bb490d0](https://linux-hardware.org/?probe=2a4bb490d0) | Nov 29, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [a05b99b00e](https://linux-hardware.org/?probe=a05b99b00e) | Nov 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [21cd2084c5](https://linux-hardware.org/?probe=21cd2084c5) | Nov 16, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c42e078d94](https://linux-hardware.org/?probe=c42e078d94) | Nov 04, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [713f71652e](https://linux-hardware.org/?probe=713f71652e) | Nov 04, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [34d3046ea4](https://linux-hardware.org/?probe=34d3046ea4) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430s 23539KU      | Notebook    | [ff4e869df2](https://linux-hardware.org/?probe=ff4e869df2) | Nov 03, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [c3049c59a8](https://linux-hardware.org/?probe=c3049c59a8) | Oct 30, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [daae18ab91](https://linux-hardware.org/?probe=daae18ab91) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2ceb11d7b3](https://linux-hardware.org/?probe=2ceb11d7b3) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5c3d640129](https://linux-hardware.org/?probe=5c3d640129) | Oct 29, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [7654e5f9c4](https://linux-hardware.org/?probe=7654e5f9c4) | Oct 26, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [7848c6d520](https://linux-hardware.org/?probe=7848c6d520) | Oct 26, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [6a9b93fdeb](https://linux-hardware.org/?probe=6a9b93fdeb) | Oct 16, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [43ce2df718](https://linux-hardware.org/?probe=43ce2df718) | Oct 12, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dc3347c309](https://linux-hardware.org/?probe=dc3347c309) | Oct 10, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [85f2638273](https://linux-hardware.org/?probe=85f2638273) | Oct 05, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [77f9a2e79a](https://linux-hardware.org/?probe=77f9a2e79a) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [921b395e9c](https://linux-hardware.org/?probe=921b395e9c) | Oct 02, 2022 |
| HP            | 15                          | Notebook    | [28e8e01768](https://linux-hardware.org/?probe=28e8e01768) | Sep 28, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [e2232c49ca](https://linux-hardware.org/?probe=e2232c49ca) | Sep 25, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [20d37d51bd](https://linux-hardware.org/?probe=20d37d51bd) | Sep 21, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cabebaa0e6](https://linux-hardware.org/?probe=cabebaa0e6) | Sep 21, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1796a51c0c](https://linux-hardware.org/?probe=1796a51c0c) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f7189849b4](https://linux-hardware.org/?probe=f7189849b4) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [6d7ce1962d](https://linux-hardware.org/?probe=6d7ce1962d) | Aug 24, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [f85ff90a58](https://linux-hardware.org/?probe=f85ff90a58) | Aug 22, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [3842f0e711](https://linux-hardware.org/?probe=3842f0e711) | Aug 22, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [1fa4b8b58a](https://linux-hardware.org/?probe=1fa4b8b58a) | Aug 21, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [e9bcb08163](https://linux-hardware.org/?probe=e9bcb08163) | Aug 21, 2022 |
| HP            | ENVY 15                     | Notebook    | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| HP            | 097Ch                       | Desktop     | [ac391817bc](https://linux-hardware.org/?probe=ac391817bc) | Aug 19, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [c37ee0a700](https://linux-hardware.org/?probe=c37ee0a700) | Aug 08, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| HP            | 1493                        | Desktop     | [2925e7a321](https://linux-hardware.org/?probe=2925e7a321) | Aug 01, 2022 |
| HP            | Unknown                     | Notebook    | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Unknown                     | Notebook    | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | 15                          | Notebook    | [91c97ad34a](https://linux-hardware.org/?probe=91c97ad34a) | Jun 24, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| HP            | 3397                        | Desktop     | [0679103825](https://linux-hardware.org/?probe=0679103825) | Jun 13, 2022 |
| HP            | 3397                        | Desktop     | [e86ba79fcf](https://linux-hardware.org/?probe=e86ba79fcf) | Jun 09, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [1f7a666022](https://linux-hardware.org/?probe=1f7a666022) | Jun 02, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Lenovo        | NOK                         | Desktop     | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Notebook      | P65xHP                      | Notebook    | [b1205b8ca1](https://linux-hardware.org/?probe=b1205b8ca1) | May 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9d0ee854e4](https://linux-hardware.org/?probe=9d0ee854e4) | May 10, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [691a4c0ca5](https://linux-hardware.org/?probe=691a4c0ca5) | May 08, 2022 |
| Acer          | Aspire 5920G                | Notebook    | [b2ffc81ed6](https://linux-hardware.org/?probe=b2ffc81ed6) | May 07, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [94684071ed](https://linux-hardware.org/?probe=94684071ed) | May 05, 2022 |
| Dell          | Latitude 3340               | Notebook    | [b724073bff](https://linux-hardware.org/?probe=b724073bff) | May 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Dell          | Latitude 3340               | Notebook    | [e6aa31da26](https://linux-hardware.org/?probe=e6aa31da26) | Apr 23, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [64e00f7a40](https://linux-hardware.org/?probe=64e00f7a40) | Apr 12, 2022 |
| HP            | EliteBook x360 1030 G8 N... | Convertible | [ef1693c88f](https://linux-hardware.org/?probe=ef1693c88f) | Apr 07, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [a83be65e4f](https://linux-hardware.org/?probe=a83be65e4f) | Apr 02, 2022 |
| HP            | EliteBook Folio 9480m       | Notebook    | [5bb1b6ca04](https://linux-hardware.org/?probe=5bb1b6ca04) | Apr 02, 2022 |
| Lenovo        | ThinkPad X131e 33672T5      | Notebook    | [277143e66b](https://linux-hardware.org/?probe=277143e66b) | Mar 26, 2022 |
| HP            | 83EB                        | All in one  | [26fea5e4f7](https://linux-hardware.org/?probe=26fea5e4f7) | Mar 19, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [ec8ec429fc](https://linux-hardware.org/?probe=ec8ec429fc) | Mar 07, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c66cc8aa4e](https://linux-hardware.org/?probe=c66cc8aa4e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [a2e640db60](https://linux-hardware.org/?probe=a2e640db60) | Feb 08, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [05f63f2396](https://linux-hardware.org/?probe=05f63f2396) | Feb 04, 2022 |
| Lenovo        | ThinkPad T490s 20NYS8J90... | Notebook    | [c1aee9b559](https://linux-hardware.org/?probe=c1aee9b559) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| Lenovo        | V14-IGL 82C2                | Notebook    | [c90b300aea](https://linux-hardware.org/?probe=c90b300aea) | Jan 16, 2022 |
| HP            | Presario CQ56               | Notebook    | [8d03d80424](https://linux-hardware.org/?probe=8d03d80424) | Jan 14, 2022 |
| HP            | 83E0                        | Desktop     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fac2fc3940](https://linux-hardware.org/?probe=fac2fc3940) | Jan 13, 2022 |
| Lenovo        | ThinkPad X240 20AL00CQAU    | Notebook    | [9f36bf55ba](https://linux-hardware.org/?probe=9f36bf55ba) | Jan 11, 2022 |
| HP            | Presario CQ56               | Notebook    | [a0bc0364a8](https://linux-hardware.org/?probe=a0bc0364a8) | Jan 08, 2022 |
| Lenovo        | ThinkPad X250 20CLA21MJP    | Notebook    | [850c0ae1da](https://linux-hardware.org/?probe=850c0ae1da) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [c08374a615](https://linux-hardware.org/?probe=c08374a615) | Dec 30, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [30756486fd](https://linux-hardware.org/?probe=30756486fd) | Dec 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01b4efe7c0](https://linux-hardware.org/?probe=01b4efe7c0) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [dff30c5ec8](https://linux-hardware.org/?probe=dff30c5ec8) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | Notebook    | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b159811d48](https://linux-hardware.org/?probe=b159811d48) | Dec 12, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [2197770fd0](https://linux-hardware.org/?probe=2197770fd0) | Dec 12, 2021 |
| Chuwi         | HeroBook Air                | Notebook    | [dd5567d4dc](https://linux-hardware.org/?probe=dd5567d4dc) | Dec 08, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [64521297e2](https://linux-hardware.org/?probe=64521297e2) | Dec 07, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [b6a5bb8982](https://linux-hardware.org/?probe=b6a5bb8982) | Dec 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [2b0946038d](https://linux-hardware.org/?probe=2b0946038d) | Nov 18, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [e1597401db](https://linux-hardware.org/?probe=e1597401db) | Nov 16, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [820951b4af](https://linux-hardware.org/?probe=820951b4af) | Nov 16, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [022146ab90](https://linux-hardware.org/?probe=022146ab90) | Nov 14, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [c5620beab2](https://linux-hardware.org/?probe=c5620beab2) | Nov 07, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [94ac3dba1a](https://linux-hardware.org/?probe=94ac3dba1a) | Nov 07, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [516eabe645](https://linux-hardware.org/?probe=516eabe645) | Nov 02, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [f40d5fd5a7](https://linux-hardware.org/?probe=f40d5fd5a7) | Oct 27, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [170dd8b241](https://linux-hardware.org/?probe=170dd8b241) | Oct 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [5e542184d8](https://linux-hardware.org/?probe=5e542184d8) | Oct 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [5a23abfa74](https://linux-hardware.org/?probe=5a23abfa74) | Sep 29, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [0646fc1739](https://linux-hardware.org/?probe=0646fc1739) | Sep 27, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Apple         | MacBookPro16,1              | Notebook    | [ab55e1ade6](https://linux-hardware.org/?probe=ab55e1ade6) | Sep 22, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [40bf0d5bb0](https://linux-hardware.org/?probe=40bf0d5bb0) | Sep 17, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [b5a01103fd](https://linux-hardware.org/?probe=b5a01103fd) | Sep 14, 2021 |
| Dell          | 0R790T A00                  | Desktop     | [a5290e7cb6](https://linux-hardware.org/?probe=a5290e7cb6) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Insyde        | i101c                       | Notebook    | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [27b0daea73](https://linux-hardware.org/?probe=27b0daea73) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | EliteBook Folio 9480m       | Notebook    | [b89fc8114f](https://linux-hardware.org/?probe=b89fc8114f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c642d92231](https://linux-hardware.org/?probe=c642d92231) | Jul 31, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c374609a3e](https://linux-hardware.org/?probe=c374609a3e) | Jul 29, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [c9de881b72](https://linux-hardware.org/?probe=c9de881b72) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3QC0... | Notebook    | [10e46eeaf3](https://linux-hardware.org/?probe=10e46eeaf3) | Jul 25, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [88afb2e5a1](https://linux-hardware.org/?probe=88afb2e5a1) | Jul 23, 2021 |
| Acer          | Veriton X680G               | Desktop     | [3b8774337b](https://linux-hardware.org/?probe=3b8774337b) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [b3a36bf681](https://linux-hardware.org/?probe=b3a36bf681) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [0f54d945d0](https://linux-hardware.org/?probe=0f54d945d0) | Jul 21, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [daa99f3a24](https://linux-hardware.org/?probe=daa99f3a24) | Jul 15, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [6c9393a9d6](https://linux-hardware.org/?probe=6c9393a9d6) | Jul 08, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [e60c71a5e1](https://linux-hardware.org/?probe=e60c71a5e1) | Jun 25, 2021 |
| IBM           | Node 1, Processor Card      | Server      | [be2298910b](https://linux-hardware.org/?probe=be2298910b) | Jun 24, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8513c961a4](https://linux-hardware.org/?probe=8513c961a4) | Jun 21, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [9d9ecee1b9](https://linux-hardware.org/?probe=9d9ecee1b9) | Jun 20, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e9d94e06f1](https://linux-hardware.org/?probe=e9d94e06f1) | Jun 18, 2021 |
| Unknown       | Unknown                     | Phone       | [7948d69684](https://linux-hardware.org/?probe=7948d69684) | Jun 05, 2021 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [549f1c8bd1](https://linux-hardware.org/?probe=549f1c8bd1) | May 25, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [304747e4c6](https://linux-hardware.org/?probe=304747e4c6) | May 23, 2021 |
| IP3 Tech      | AB1                         | Mini pc     | [b2cc37b9ac](https://linux-hardware.org/?probe=b2cc37b9ac) | May 21, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [2c35ee27d9](https://linux-hardware.org/?probe=2c35ee27d9) | May 20, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [11b99bedb6](https://linux-hardware.org/?probe=11b99bedb6) | May 13, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [a71cb329b2](https://linux-hardware.org/?probe=a71cb329b2) | May 12, 2021 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [dc61da2d5e](https://linux-hardware.org/?probe=dc61da2d5e) | May 09, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e177523d81](https://linux-hardware.org/?probe=e177523d81) | May 03, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [e8771a4577](https://linux-hardware.org/?probe=e8771a4577) | May 01, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ee57ec30cd](https://linux-hardware.org/?probe=ee57ec30cd) | Apr 28, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [95c380139d](https://linux-hardware.org/?probe=95c380139d) | Apr 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b35c15fb6b](https://linux-hardware.org/?probe=b35c15fb6b) | Apr 25, 2021 |
| Toshiba       | dynabook R731/E             | Notebook    | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [561287f5a8](https://linux-hardware.org/?probe=561287f5a8) | Apr 06, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [ecac5c48dc](https://linux-hardware.org/?probe=ecac5c48dc) | Apr 02, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [95f53c1b72](https://linux-hardware.org/?probe=95f53c1b72) | Mar 19, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [585322e740](https://linux-hardware.org/?probe=585322e740) | Mar 19, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [b345b644ae](https://linux-hardware.org/?probe=b345b644ae) | Mar 18, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [89e652d12d](https://linux-hardware.org/?probe=89e652d12d) | Mar 18, 2021 |
| Dell          | 0773VG A02                  | Desktop     | [a4d5cb7e11](https://linux-hardware.org/?probe=a4d5cb7e11) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | Notebook    | [31915e8c0b](https://linux-hardware.org/?probe=31915e8c0b) | Mar 10, 2021 |
| Toshiba       | dynabook Satellite B554/... | Notebook    | [e166e551cd](https://linux-hardware.org/?probe=e166e551cd) | Mar 09, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [10c98c982d](https://linux-hardware.org/?probe=10c98c982d) | Mar 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [09037a0a1b](https://linux-hardware.org/?probe=09037a0a1b) | Mar 06, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| HP            | ProBook 430 G6              | Notebook    | [5ed6cc994b](https://linux-hardware.org/?probe=5ed6cc994b) | Mar 05, 2021 |
| Dell          | Inspiron N5030              | Notebook    | [47077a37f2](https://linux-hardware.org/?probe=47077a37f2) | Feb 25, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [c4ab183609](https://linux-hardware.org/?probe=c4ab183609) | Feb 24, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [55c54121f8](https://linux-hardware.org/?probe=55c54121f8) | Feb 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [3311619921](https://linux-hardware.org/?probe=3311619921) | Feb 18, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [b573c1e746](https://linux-hardware.org/?probe=b573c1e746) | Feb 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [eda69993ed](https://linux-hardware.org/?probe=eda69993ed) | Feb 17, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [66c8150e0d](https://linux-hardware.org/?probe=66c8150e0d) | Feb 14, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96be56a30d](https://linux-hardware.org/?probe=96be56a30d) | Feb 13, 2021 |
| TECNO         | WinPad 2                    | Notebook    | [336989b30d](https://linux-hardware.org/?probe=336989b30d) | Feb 10, 2021 |
| TECNO         | WinPad 2                    | Notebook    | [439563e244](https://linux-hardware.org/?probe=439563e244) | Feb 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [38d7cb1271](https://linux-hardware.org/?probe=38d7cb1271) | Feb 06, 2021 |
| Dell          | Inspiron 3580               | Notebook    | [417752f660](https://linux-hardware.org/?probe=417752f660) | Jan 30, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f56f2da985](https://linux-hardware.org/?probe=f56f2da985) | Jan 28, 2021 |
| Lenovo        | ThinkPad P52s 20LB0021US    | Notebook    | [4e50af07df](https://linux-hardware.org/?probe=4e50af07df) | Jan 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [671c83ebf7](https://linux-hardware.org/?probe=671c83ebf7) | Jan 27, 2021 |
| HP            | ProBook 6560b               | Notebook    | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [e2f7ccd4ad](https://linux-hardware.org/?probe=e2f7ccd4ad) | Jan 14, 2021 |
| ASUSTek       | X540NA                      | Notebook    | [9b2af2d13c](https://linux-hardware.org/?probe=9b2af2d13c) | Jan 13, 2021 |
| HP            | ProBook 6560b               | Notebook    | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [013db2cd8e](https://linux-hardware.org/?probe=013db2cd8e) | Dec 25, 2020 |
| Endless       | EF20EA                      | Notebook    | [c216bffe9d](https://linux-hardware.org/?probe=c216bffe9d) | Dec 20, 2020 |
| Endless       | EF20EA                      | Notebook    | [e2409b47e2](https://linux-hardware.org/?probe=e2409b47e2) | Dec 20, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [c3c7909b48](https://linux-hardware.org/?probe=c3c7909b48) | Dec 20, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c764c0655e](https://linux-hardware.org/?probe=c764c0655e) | Dec 16, 2020 |
| Lenovo        | ThinkPad T470s 20HGS6PF0... | Notebook    | [2f91f2576d](https://linux-hardware.org/?probe=2f91f2576d) | Dec 14, 2020 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [98d5a20a00](https://linux-hardware.org/?probe=98d5a20a00) | Dec 12, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [885a64d9d3](https://linux-hardware.org/?probe=885a64d9d3) | Dec 12, 2020 |
| ASUSTek       | X202EV                      | Notebook    | [b3b2381999](https://linux-hardware.org/?probe=b3b2381999) | Nov 25, 2020 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Lenovo        | ThinkPad X240 20AMS4J900    | Notebook    | [8a54e51f5a](https://linux-hardware.org/?probe=8a54e51f5a) | Nov 17, 2020 |
| HP            | Laptop 15-da1xxx            | Notebook    | [7c1f9ebdef](https://linux-hardware.org/?probe=7c1f9ebdef) | Nov 12, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [ccefa81140](https://linux-hardware.org/?probe=ccefa81140) | Nov 12, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [5c863855cc](https://linux-hardware.org/?probe=5c863855cc) | Nov 11, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [372e62dd5a](https://linux-hardware.org/?probe=372e62dd5a) | Nov 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [6b0122d8c2](https://linux-hardware.org/?probe=6b0122d8c2) | Nov 06, 2020 |
| HP            | 3396                        | Desktop     | [12e6dc258e](https://linux-hardware.org/?probe=12e6dc258e) | Oct 31, 2020 |
| HP            | 3396                        | Desktop     | [876ee024dc](https://linux-hardware.org/?probe=876ee024dc) | Oct 31, 2020 |
| HP            | Spectre x360 Convertible    | Convertible | [b4e75e63fb](https://linux-hardware.org/?probe=b4e75e63fb) | Oct 30, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e1f1909639](https://linux-hardware.org/?probe=e1f1909639) | Oct 25, 2020 |
| Dell          | Latitude E6420              | Notebook    | [e1bbf1beb6](https://linux-hardware.org/?probe=e1bbf1beb6) | Oct 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [a2eb617037](https://linux-hardware.org/?probe=a2eb617037) | Oct 16, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6ea891ad6b](https://linux-hardware.org/?probe=6ea891ad6b) | Oct 13, 2020 |
| Dell          | 0773VG A02                  | Desktop     | [8307343ab3](https://linux-hardware.org/?probe=8307343ab3) | Oct 09, 2020 |
| Dell          | 0773VG A02                  | Desktop     | [2c6d570678](https://linux-hardware.org/?probe=2c6d570678) | Oct 09, 2020 |
| Unknown       | Unknown                     | Phone       | [6f31ab4962](https://linux-hardware.org/?probe=6f31ab4962) | Oct 03, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [5b0c257b43](https://linux-hardware.org/?probe=5b0c257b43) | Oct 02, 2020 |
| Dell          | Latitude D820               | Notebook    | [ae1fa80f73](https://linux-hardware.org/?probe=ae1fa80f73) | Oct 02, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [47a129fdd0](https://linux-hardware.org/?probe=47a129fdd0) | Sep 28, 2020 |
| Dell          | Inspiron 3543               | Notebook    | [ebcb037006](https://linux-hardware.org/?probe=ebcb037006) | Sep 28, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8232648226](https://linux-hardware.org/?probe=8232648226) | Sep 20, 2020 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [37985e0340](https://linux-hardware.org/?probe=37985e0340) | Sep 19, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [92ee6a03be](https://linux-hardware.org/?probe=92ee6a03be) | Sep 14, 2020 |
| ASUSTek       | UX305CA                     | Notebook    | [f51d9347e3](https://linux-hardware.org/?probe=f51d9347e3) | Sep 10, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [6e6f79b651](https://linux-hardware.org/?probe=6e6f79b651) | Sep 10, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc38793462](https://linux-hardware.org/?probe=dc38793462) | Sep 08, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [4d64af6a38](https://linux-hardware.org/?probe=4d64af6a38) | Sep 07, 2020 |
| ASUSTek       | X551MA                      | Notebook    | [6e93ef18ce](https://linux-hardware.org/?probe=6e93ef18ce) | Sep 03, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [19a0f0bfdc](https://linux-hardware.org/?probe=19a0f0bfdc) | Sep 03, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [9c70b1dad4](https://linux-hardware.org/?probe=9c70b1dad4) | Sep 02, 2020 |
| MSI           | 0A90                        | Desktop     | [4f8d53458d](https://linux-hardware.org/?probe=4f8d53458d) | Aug 11, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [31f100c680](https://linux-hardware.org/?probe=31f100c680) | Aug 10, 2020 |
| MSI           | 0A90                        | Desktop     | [04bdc6569a](https://linux-hardware.org/?probe=04bdc6569a) | Aug 09, 2020 |
| MSI           | 2AE0                        | Desktop     | [54a32fea6e](https://linux-hardware.org/?probe=54a32fea6e) | Aug 02, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [2a88596017](https://linux-hardware.org/?probe=2a88596017) | Jul 30, 2020 |
| HP            | Pavilion Laptop 15t-cs20... | Notebook    | [f778796026](https://linux-hardware.org/?probe=f778796026) | Jul 16, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [551521f7c9](https://linux-hardware.org/?probe=551521f7c9) | Jul 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [a1265cca74](https://linux-hardware.org/?probe=a1265cca74) | Jul 11, 2020 |
| Dell          | 0VNP2H A00                  | Desktop     | [de21e4bff4](https://linux-hardware.org/?probe=de21e4bff4) | Jul 04, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [412f31bc06](https://linux-hardware.org/?probe=412f31bc06) | Jul 01, 2020 |
| Lenovo        | ThinkPad L480 20LTS1RE0Y    | Notebook    | [76ef35dd77](https://linux-hardware.org/?probe=76ef35dd77) | Jun 26, 2020 |
| HP            | 0AA8h                       | Desktop     | [e60c30f572](https://linux-hardware.org/?probe=e60c30f572) | Jun 25, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4f747e9c8a](https://linux-hardware.org/?probe=4f747e9c8a) | Jun 25, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [21efc22417](https://linux-hardware.org/?probe=21efc22417) | Jun 21, 2020 |
| Dell          | Latitude 3150               | Notebook    | [0299c15a34](https://linux-hardware.org/?probe=0299c15a34) | Jun 20, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [6277131dfd](https://linux-hardware.org/?probe=6277131dfd) | Jun 20, 2020 |
| HP            | 0AA8h                       | Desktop     | [4017115305](https://linux-hardware.org/?probe=4017115305) | Jun 19, 2020 |
| HP            | 0AA8h                       | Desktop     | [752505c134](https://linux-hardware.org/?probe=752505c134) | Jun 17, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | Notebook    | [f16d9a4077](https://linux-hardware.org/?probe=f16d9a4077) | Jun 17, 2020 |
| ASUSTek       | X540NA                      | Notebook    | [530934acb0](https://linux-hardware.org/?probe=530934acb0) | Jun 17, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [0e66f9df2c](https://linux-hardware.org/?probe=0e66f9df2c) | Jun 16, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [620453a9dc](https://linux-hardware.org/?probe=620453a9dc) | Jun 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS1DH01    | Notebook    | [483d2473b0](https://linux-hardware.org/?probe=483d2473b0) | Jun 15, 2020 |
| Getac         | V110                        | Notebook    | [4e3a330cb5](https://linux-hardware.org/?probe=4e3a330cb5) | Jun 13, 2020 |
| HP            | 3032h                       | Desktop     | [8aa1dd8ecd](https://linux-hardware.org/?probe=8aa1dd8ecd) | Jun 13, 2020 |
| Toshiba       | R84SAU2                     | Notebook    | [d59976ae7f](https://linux-hardware.org/?probe=d59976ae7f) | Jun 10, 2020 |
| Acer          | Aspire A315-33              | Notebook    | [c0eeb5a67b](https://linux-hardware.org/?probe=c0eeb5a67b) | Jun 03, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [e903b1af8a](https://linux-hardware.org/?probe=e903b1af8a) | May 31, 2020 |
| Dell          | 0PU052                      | Desktop     | [5d99be49f0](https://linux-hardware.org/?probe=5d99be49f0) | May 31, 2020 |
| Lenovo        | ThinkPad E520 1143ADU       | Notebook    | [75e6d735a0](https://linux-hardware.org/?probe=75e6d735a0) | May 31, 2020 |
| Dell          | 0PU052                      | Desktop     | [6b4292fc06](https://linux-hardware.org/?probe=6b4292fc06) | May 30, 2020 |
| Dell          | Inspiron 5767               | Notebook    | [bdab68c78a](https://linux-hardware.org/?probe=bdab68c78a) | May 25, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [8240cd4643](https://linux-hardware.org/?probe=8240cd4643) | May 17, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [227b4dc4ec](https://linux-hardware.org/?probe=227b4dc4ec) | May 15, 2020 |
| Apple         | MacBookPro3,1               | Notebook    | [5ca063ed58](https://linux-hardware.org/?probe=5ca063ed58) | May 11, 2020 |
| Dell          | Latitude E6410              | Notebook    | [7a885b703e](https://linux-hardware.org/?probe=7a885b703e) | May 10, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [0420235572](https://linux-hardware.org/?probe=0420235572) | May 08, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0G214D A00                  | Desktop     | [a8caa085de](https://linux-hardware.org/?probe=a8caa085de) | May 04, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | Notebook    | [85b487e27d](https://linux-hardware.org/?probe=85b487e27d) | May 02, 2020 |
| Dell          | Inspiron 5767               | Notebook    | [32e3129638](https://linux-hardware.org/?probe=32e3129638) | May 02, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cc8b2bc724](https://linux-hardware.org/?probe=cc8b2bc724) | Apr 30, 2020 |
| Lenovo        | ThinkPad T440p 20AWS5D20... | Notebook    | [6cf30d2192](https://linux-hardware.org/?probe=6cf30d2192) | Apr 26, 2020 |
| HP            | ProBook 6470b               | Notebook    | [a6132519cf](https://linux-hardware.org/?probe=a6132519cf) | Apr 21, 2020 |
| HP            | ProBook 6470b               | Notebook    | [255652dcf4](https://linux-hardware.org/?probe=255652dcf4) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [a26feb7507](https://linux-hardware.org/?probe=a26feb7507) | Apr 18, 2020 |
| HP            | 15 Notebook PC              | Notebook    | [120e9af4f0](https://linux-hardware.org/?probe=120e9af4f0) | Apr 11, 2020 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [04ee092498](https://linux-hardware.org/?probe=04ee092498) | Apr 08, 2020 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [ecef1f0fcb](https://linux-hardware.org/?probe=ecef1f0fcb) | Apr 07, 2020 |
| ASUSTek       | X540SAA                     | Notebook    | [f5e7614710](https://linux-hardware.org/?probe=f5e7614710) | Mar 14, 2020 |
| HP            | 0B4Ch D                     | Desktop     | [2807f4c586](https://linux-hardware.org/?probe=2807f4c586) | Mar 12, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [b634560d95](https://linux-hardware.org/?probe=b634560d95) | Mar 01, 2020 |
| HP            | 09F0h                       | Desktop     | [bff6b4f556](https://linux-hardware.org/?probe=bff6b4f556) | Jan 21, 2020 |
| HP            | 09F0h                       | Desktop     | [ad09a9a9d4](https://linux-hardware.org/?probe=ad09a9a9d4) | Jan 21, 2020 |
| HP            | ENVY TS 15                  | Notebook    | [eb1591f00c](https://linux-hardware.org/?probe=eb1591f00c) | Dec 23, 2019 |
| HP            | Spectre x360 Convertible    | Convertible | [6f8fd31c2c](https://linux-hardware.org/?probe=6f8fd31c2c) | Dec 19, 2019 |
| HP            | Spectre x360 Convertible    | Convertible | [a18a54d051](https://linux-hardware.org/?probe=a18a54d051) | Oct 30, 2019 |
| Dell          | Latitude E6220              | Notebook    | [37cf274f19](https://linux-hardware.org/?probe=37cf274f19) | Oct 30, 2019 |
| HP            | EliteBook 820 G2            | Notebook    | [05b4f35642](https://linux-hardware.org/?probe=05b4f35642) | Oct 11, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [f0f19467e3](https://linux-hardware.org/?probe=f0f19467e3) | Sep 04, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [2ec595f039](https://linux-hardware.org/?probe=2ec595f039) | Sep 03, 2019 |
| HP            | ENVY TS 15                  | Notebook    | [054a6961ec](https://linux-hardware.org/?probe=054a6961ec) | Aug 18, 2019 |
| Panasonic     | CF-SX2JDQZF5                | Notebook    | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| EVOC          | P7xxTM1-(G)                 | Notebook    | [f9f9fbd6bd](https://linux-hardware.org/?probe=f9f9fbd6bd) | Aug 06, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [e2c04796a0](https://linux-hardware.org/?probe=e2c04796a0) | Jul 25, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [c4f5abc453](https://linux-hardware.org/?probe=c4f5abc453) | Jul 12, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [70e21ebad0](https://linux-hardware.org/?probe=70e21ebad0) | Jun 30, 2019 |
| HP            | EliteBook 840 G1            | Notebook    | [25b5bf978a](https://linux-hardware.org/?probe=25b5bf978a) | Jun 29, 2019 |
| HP            | 0AA0h                       | Desktop     | [1787c13656](https://linux-hardware.org/?probe=1787c13656) | Jun 15, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [8f23861866](https://linux-hardware.org/?probe=8f23861866) | Jun 04, 2019 |
| Unknown       | Unknown                     | Notebook    | [57dd20a793](https://linux-hardware.org/?probe=57dd20a793) | Jun 03, 2019 |
| Dell          | Inspiron 5570               | Notebook    | [86722cf4ab](https://linux-hardware.org/?probe=86722cf4ab) | May 05, 2019 |
| HP            | Notebook                    | Notebook    | [ca99cb8e00](https://linux-hardware.org/?probe=ca99cb8e00) | Apr 10, 2019 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [2f1b160149](https://linux-hardware.org/?probe=2f1b160149) | Nov 19, 2018 |
| Clevo         | P7xxDM2-(G)                 | Notebook    | [9cfa1aef75](https://linux-hardware.org/?probe=9cfa1aef75) | Jun 20, 2018 |
| EUROCOM       | Q6                          | Notebook    | [001ab8c139](https://linux-hardware.org/?probe=001ab8c139) | Jun 02, 2018 |
| EUROCOM       | Q6                          | Notebook    | [15b4e0daf2](https://linux-hardware.org/?probe=15b4e0daf2) | Jun 02, 2018 |
| Clevo         | P7xxDM2-(G)                 | Notebook    | [9fcaed033f](https://linux-hardware.org/?probe=9fcaed033f) | Mar 09, 2018 |
| Sony          | VGN-NS295J                  | Notebook    | [9d2ccc3bc1](https://linux-hardware.org/?probe=9d2ccc3bc1) | Dec 20, 2017 |
| Sony          | VGN-NS295J                  | Notebook    | [08cfe3b021](https://linux-hardware.org/?probe=08cfe3b021) | Dec 20, 2017 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [304aa59840](https://linux-hardware.org/?probe=304aa59840) | Dec 14, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Kenya/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 48        | 10.96%  |
| Ubuntu 22.04                 | 43        | 9.82%   |
| Ubuntu 24.04                 | 21        | 4.79%   |
| Ubuntu 18.04                 | 19        | 4.34%   |
| Arch Rolling                 | 15        | 3.42%   |
| Zorin 16                     | 8         | 1.83%   |
| Fedora 40                    | 8         | 1.83%   |
| Debian 12                    | 8         | 1.83%   |
| Manjaro                      | 7         | 1.6%    |
| Linux Mint 20.3              | 7         | 1.6%    |
| Fedora 38                    | 7         | 1.6%    |
| Fedora 36                    | 7         | 1.6%    |
| ArcoLinux Rolling            | 7         | 1.6%    |
| Zorin 15                     | 6         | 1.37%   |
| Fedora 41                    | 6         | 1.37%   |
| Zorin 17                     | 5         | 1.14%   |
| Ubuntu 23.04                 | 5         | 1.14%   |
| Pop!_OS 20.04                | 5         | 1.14%   |
| OpenMandriva 4.2             | 5         | 1.14%   |
| Arch                         | 5         | 1.14%   |
| Ubuntu 20.10                 | 4         | 0.91%   |
| Ubuntu 19.04                 | 4         | 0.91%   |
| Pop!_OS 22.04                | 4         | 0.91%   |
| OpenMandriva 25.06           | 4         | 0.91%   |
| Linux Mint 21                | 4         | 0.91%   |
| Fedora 37                    | 4         | 0.91%   |
| Debian 11                    | 4         | 0.91%   |
| Ubuntu 21.10                 | 3         | 0.68%   |
| Ubuntu 21.04                 | 3         | 0.68%   |
| Q4OS 3                       | 3         | 0.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.68%   |
| OpenMandriva 25.90           | 3         | 0.68%   |
| Linux Mint 22.1              | 3         | 0.68%   |
| Linux Mint 21.2              | 3         | 0.68%   |
| Linux Mint 20.2              | 3         | 0.68%   |
| Kali 2023.3                  | 3         | 0.68%   |
| Fedora 43                    | 3         | 0.68%   |
| Fedora 42                    | 3         | 0.68%   |
| Fedora 35                    | 3         | 0.68%   |
| Fedora 33                    | 3         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 151       | 36.65%  |
| Fedora           | 46        | 11.17%  |
| Linux Mint       | 25        | 6.07%   |
| OpenMandriva     | 21        | 5.1%    |
| Arch             | 20        | 4.85%   |
| Zorin            | 19        | 4.61%   |
| Kali             | 16        | 3.88%   |
| Debian           | 13        | 3.16%   |
| Manjaro          | 12        | 2.91%   |
| Endless          | 12        | 2.91%   |
| Pop!_OS          | 11        | 2.67%   |
| Parrot           | 9         | 2.18%   |
| ArcoLinux        | 7         | 1.7%    |
| Elementary       | 5         | 1.21%   |
| openSUSE         | 4         | 0.97%   |
| Q4OS             | 3         | 0.73%   |
| Ubuntu MATE      | 2         | 0.49%   |
| Ubuntu Budgie    | 2         | 0.49%   |
| ROSA             | 2         | 0.49%   |
| RHEL             | 2         | 0.49%   |
| Lubuntu          | 2         | 0.49%   |
| KDE neon         | 2         | 0.49%   |
| Garuda Linux     | 2         | 0.49%   |
| Deepin           | 2         | 0.49%   |
| CentOS           | 2         | 0.49%   |
| blendOS          | 2         | 0.49%   |
| BlackPanther     | 2         | 0.49%   |
| Android          | 2         | 0.49%   |
| Xubuntu          | 1         | 0.24%   |
| Ubuntu Unity     | 1         | 0.24%   |
| Ubuntu Studio    | 1         | 0.24%   |
| Rocky Linux      | 1         | 0.24%   |
| org.kde.Platform | 1         | 0.24%   |
| Nobara           | 1         | 0.24%   |
| MX               | 1         | 0.24%   |
| Mageia           | 1         | 0.24%   |
| LMDE             | 1         | 0.24%   |
| Lilidog          | 1         | 0.24%   |
| EndeavourOS      | 1         | 0.24%   |
| Bazzite          | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.14.2-desktop-3omv2590  | 7         | 1.5%    |
| 5.8.0-14-generic         | 6         | 1.28%   |
| 6.8.0-51-generic         | 5         | 1.07%   |
| 5.4.0-42-generic         | 5         | 1.07%   |
| 5.15.0-58-generic        | 5         | 1.07%   |
| 5.15.0-52-generic        | 5         | 1.07%   |
| 5.15.0-41-generic        | 5         | 1.07%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.07%   |
| 6.8.0-45-generic         | 4         | 0.86%   |
| 5.4.0-52-generic         | 4         | 0.86%   |
| 5.19.0-41-generic        | 4         | 0.86%   |
| 5.11.0-38-generic        | 4         | 0.86%   |
| 6.8.0-31-generic         | 3         | 0.64%   |
| 6.3.0-kali1-amd64        | 3         | 0.64%   |
| 6.2.0-32-generic         | 3         | 0.64%   |
| 5.8.0-43-generic         | 3         | 0.64%   |
| 5.4.0-58-generic         | 3         | 0.64%   |
| 5.4.0-45-generic         | 3         | 0.64%   |
| 5.4.0-37-generic         | 3         | 0.64%   |
| 5.4.0-137-generic        | 3         | 0.64%   |
| 5.3.0-28-generic         | 3         | 0.64%   |
| 5.19.0-38-generic        | 3         | 0.64%   |
| 5.19.0-35-generic        | 3         | 0.64%   |
| 5.15.0-53-generic        | 3         | 0.64%   |
| 6.8.9-arch1-2            | 2         | 0.43%   |
| 6.8.11-300.fc40.x86_64   | 2         | 0.43%   |
| 6.8.0-52-generic         | 2         | 0.43%   |
| 6.8.0-49-generic         | 2         | 0.43%   |
| 6.8.0-48-generic         | 2         | 0.43%   |
| 6.6.9-amd64              | 2         | 0.43%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.43%   |
| 6.5.0-41-generic         | 2         | 0.43%   |
| 6.5.0-27-generic         | 2         | 0.43%   |
| 6.5.0-10-generic         | 2         | 0.43%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.43%   |
| 6.14.0-35-generic        | 2         | 0.43%   |
| 6.14.0-15-generic        | 2         | 0.43%   |
| 6.12.1-desktop-1omv2490  | 2         | 0.43%   |
| 6.11.2-amd64             | 2         | 0.43%   |
| 6.1.0-kali7-amd64        | 2         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 11.41%  |
| 5.15.0  | 32        | 7.16%   |
| 6.8.0   | 29        | 6.49%   |
| 5.8.0   | 24        | 5.37%   |
| 5.11.0  | 17        | 3.8%    |
| 6.5.0   | 14        | 3.13%   |
| 6.1.0   | 13        | 2.91%   |
| 5.19.0  | 12        | 2.68%   |
| 5.13.0  | 12        | 2.68%   |
| 4.15.0  | 12        | 2.68%   |
| 5.3.0   | 10        | 2.24%   |
| 6.2.0   | 9         | 2.01%   |
| 5.0.0   | 9         | 2.01%   |
| 6.14.2  | 8         | 1.79%   |
| 6.14.0  | 6         | 1.34%   |
| 5.10.0  | 6         | 1.34%   |
| 6.11.0  | 5         | 1.12%   |
| 5.10.14 | 5         | 1.12%   |
| 5.18.0  | 4         | 0.89%   |
| 5.14.0  | 4         | 0.89%   |
| 4.19.0  | 4         | 0.89%   |
| 4.18.0  | 4         | 0.89%   |
| 6.8.11  | 3         | 0.67%   |
| 6.4.8   | 3         | 0.67%   |
| 6.3.0   | 3         | 0.67%   |
| 5.19.9  | 3         | 0.67%   |
| 5.16.7  | 3         | 0.67%   |
| 6.8.9   | 2         | 0.45%   |
| 6.6.9   | 2         | 0.45%   |
| 6.6.2   | 2         | 0.45%   |
| 6.5.6   | 2         | 0.45%   |
| 6.3.4   | 2         | 0.45%   |
| 6.17.9  | 2         | 0.45%   |
| 6.15.6  | 2         | 0.45%   |
| 6.12.1  | 2         | 0.45%   |
| 6.11.6  | 2         | 0.45%   |
| 6.11.2  | 2         | 0.45%   |
| 6.10.10 | 2         | 0.45%   |
| 6.1.52  | 2         | 0.45%   |
| 5.9.13  | 2         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 51        | 11.51%  |
| 6.8     | 37        | 8.35%   |
| 5.15    | 37        | 8.35%   |
| 5.8     | 27        | 6.09%   |
| 6.1     | 21        | 4.74%   |
| 5.19    | 21        | 4.74%   |
| 6.5     | 19        | 4.29%   |
| 5.11    | 18        | 4.06%   |
| 6.14    | 16        | 3.61%   |
| 5.10    | 15        | 3.39%   |
| 6.11    | 14        | 3.16%   |
| 5.13    | 14        | 3.16%   |
| 6.2     | 13        | 2.93%   |
| 4.15    | 12        | 2.71%   |
| 6.6     | 11        | 2.48%   |
| 5.3     | 10        | 2.26%   |
| 5.0     | 10        | 2.26%   |
| 6.3     | 8         | 1.81%   |
| 6.12    | 8         | 1.81%   |
| 5.14    | 8         | 1.81%   |
| 5.16    | 7         | 1.58%   |
| 6.4     | 6         | 1.35%   |
| 5.18    | 6         | 1.35%   |
| 4.18    | 6         | 1.35%   |
| 6.10    | 5         | 1.13%   |
| 4.19    | 5         | 1.13%   |
| 6.17    | 4         | 0.9%    |
| 6.0     | 4         | 0.9%    |
| 6.9     | 3         | 0.68%   |
| 5.9     | 3         | 0.68%   |
| 5.6     | 3         | 0.68%   |
| 5.17    | 3         | 0.68%   |
| 4.9     | 3         | 0.68%   |
| 6.15    | 2         | 0.45%   |
| 5.2     | 2         | 0.45%   |
| 5.12    | 2         | 0.45%   |
| 6.16    | 1         | 0.23%   |
| 6.13    | 1         | 0.23%   |
| 5.7     | 1         | 0.23%   |
| 5.5     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 390       | 97.5%   |
| i686    | 7         | 1.75%   |
| aarch64 | 2         | 0.5%    |
| armv8l  | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 241       | 58.07%  |
| KDE5            | 41        | 9.88%   |
| Unknown         | 33        | 7.95%   |
| X-Cinnamon      | 22        | 5.3%    |
| XFCE            | 20        | 4.82%   |
| KDE6            | 14        | 3.37%   |
| MATE            | 12        | 2.89%   |
| Pantheon        | 5         | 1.2%    |
| KDE             | 4         | 0.96%   |
| Hyprland        | 4         | 0.96%   |
| LXQt            | 2         | 0.48%   |
| KDE4            | 2         | 0.48%   |
| GNOME Flashback | 2         | 0.48%   |
| Cinnamon        | 2         | 0.48%   |
| awesome         | 2         | 0.48%   |
| Unity           | 1         | 0.24%   |
| qtile           | 1         | 0.24%   |
| openbox         | 1         | 0.24%   |
| LXDE-pi-wayfire | 1         | 0.24%   |
| Endless:GNOME   | 1         | 0.24%   |
| DWM             | 1         | 0.24%   |
| Deepin          | 1         | 0.24%   |
| DDE             | 1         | 0.24%   |
| Budgie          | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 242       | 58.74%  |
| Wayland | 146       | 35.44%  |
| Unknown | 19        | 4.61%   |
| Tty     | 5         | 1.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 164       | 39.9%   |
| GDM3    | 86        | 20.92%  |
| SDDM    | 60        | 14.6%   |
| GDM     | 48        | 11.68%  |
| LightDM | 44        | 10.71%  |
| TDM     | 5         | 1.22%   |
| KDM     | 2         | 0.49%   |
| GREETD  | 2         | 0.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 316       | 77.83%  |
| en_GB   | 45        | 11.08%  |
| Unknown | 30        | 7.39%   |
| C       | 14        | 3.45%   |
| en_AG   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 209       | 51.23%  |
| EFI  | 199       | 48.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 284       | 69.95%  |
| Btrfs   | 57        | 14.04%  |
| Tmpfs   | 30        | 7.39%   |
| Overlay | 24        | 5.91%   |
| Xfs     | 5         | 1.23%   |
| Unknown | 5         | 1.23%   |
| Zfs     | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 186       | 45.7%   |
| Unknown | 171       | 42.01%  |
| MBR     | 50        | 12.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 356       | 88.56%  |
| Yes       | 46        | 11.44%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 279       | 68.72%  |
| Yes       | 127       | 31.28%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 182       | 45.5%   |
| Lenovo                      | 70        | 17.5%   |
| Dell                        | 59        | 14.75%  |
| ASUSTek Computer            | 14        | 3.5%    |
| Toshiba                     | 11        | 2.75%   |
| MSI                         | 7         | 1.75%   |
| Gigabyte Technology         | 7         | 1.75%   |
| Acer                        | 6         | 1.5%    |
| Apple                       | 4         | 1%      |
| Unknown                     | 4         | 1%      |
| Samsung Electronics         | 3         | 0.75%   |
| TECNO                       | 2         | 0.5%    |
| SLIMBOOK                    | 2         | 0.5%    |
| Foxconn                     | 2         | 0.5%    |
| Endless                     | 2         | 0.5%    |
| Chuwi                       | 2         | 0.5%    |
| ASRock                      | 2         | 0.5%    |
| Sony                        | 1         | 0.25%   |
| Raspberry Pi Foundation     | 1         | 0.25%   |
| Panasonic                   | 1         | 0.25%   |
| Notebook                    | 1         | 0.25%   |
| LG Electronics              | 1         | 0.25%   |
| Jemper                      | 1         | 0.25%   |
| IP3 Tech                    | 1         | 0.25%   |
| Intel                       | 1         | 0.25%   |
| Insyde                      | 1         | 0.25%   |
| IBM                         | 1         | 0.25%   |
| I-Life Digital Technologies | 1         | 0.25%   |
| HUAWEI                      | 1         | 0.25%   |
| Getac                       | 1         | 0.25%   |
| Fujitsu                     | 1         | 0.25%   |
| EVOC                        | 1         | 0.25%   |
| EUROCOM                     | 1         | 0.25%   |
| Eluktronics                 | 1         | 0.25%   |
| Colorful Technology         | 1         | 0.25%   |
| Clevo                       | 1         | 0.25%   |
| AZW                         | 1         | 0.25%   |
| AMI                         | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| HP EliteBook 840 G1                        | 11        | 2.75%   |
| HP EliteBook Folio 9480m                   | 6         | 1.5%    |
| Unknown                                    | 6         | 1.5%    |
| HP EliteBook Folio 9470m                   | 5         | 1.25%   |
| HP EliteBook 840 G3                        | 5         | 1.25%   |
| HP ProBook 4540s                           | 4         | 1%      |
| HP Notebook                                | 4         | 1%      |
| HP ENVY Laptop 16-h0xxx                    | 4         | 1%      |
| HP EliteBook 8460p                         | 4         | 1%      |
| HP EliteBook 840 G5                        | 4         | 1%      |
| HP EliteBook 820 G3                        | 4         | 1%      |
| Dell XPS 13 9310                           | 4         | 1%      |
| Dell OptiPlex 7010                         | 4         | 1%      |
| HP ProBook 6560b                           | 3         | 0.75%   |
| HP EliteBook 8440p                         | 3         | 0.75%   |
| HP EliteBook 840 G2                        | 3         | 0.75%   |
| HP EliteBook 2570p                         | 3         | 0.75%   |
| HP 630                                     | 3         | 0.75%   |
| HP 15                                      | 3         | 0.75%   |
| ASUS X540NA                                | 3         | 0.75%   |
| Toshiba TECRA X40-E                        | 2         | 0.5%    |
| Toshiba Satellite C660                     | 2         | 0.5%    |
| TECNO WinPad 2                             | 2         | 0.5%    |
| MSI MS-7C02                                | 2         | 0.5%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00FPUS | 2         | 0.5%    |
| Lenovo IdeaPad S340-14IIL 81VV             | 2         | 0.5%    |
| Lenovo IdeaPad 3 14ITL6 82H7               | 2         | 0.5%    |
| Lenovo IdeaPad 3 14IIL05 81WD              | 2         | 0.5%    |
| Lenovo G50-80 80E5                         | 2         | 0.5%    |
| HP Spectre x360 Convertible 13-ae0xx       | 2         | 0.5%    |
| HP Spectre x360 Convertible                | 2         | 0.5%    |
| HP ProDesk 600 G1 TWR                      | 2         | 0.5%    |
| HP ProBook 650 G2                          | 2         | 0.5%    |
| HP ProBook 6470b                           | 2         | 0.5%    |
| HP ProBook 640 G1                          | 2         | 0.5%    |
| HP ProBook 450 G6                          | 2         | 0.5%    |
| HP ProBook 440 G5                          | 2         | 0.5%    |
| HP Pavilion Laptop 15-cs3xxx               | 2         | 0.5%    |
| HP Laptop 15-da1xxx                        | 2         | 0.5%    |
| HP ENVY x360 Convertible 15m-dr0xxx        | 2         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| HP EliteBook        | 68        | 17%     |
| Lenovo ThinkPad     | 36        | 9%      |
| HP ProBook          | 30        | 7.5%    |
| Dell Latitude       | 19        | 4.75%   |
| HP ENVY             | 16        | 4%      |
| Dell OptiPlex       | 16        | 4%      |
| Lenovo IdeaPad      | 15        | 3.75%   |
| HP Compaq           | 13        | 3.25%   |
| HP Pavilion         | 11        | 2.75%   |
| Dell Inspiron       | 11        | 2.75%   |
| HP Laptop           | 8         | 2%      |
| Dell XPS            | 7         | 1.75%   |
| Unknown             | 6         | 1.5%    |
| HP Spectre          | 5         | 1.25%   |
| HP 15               | 5         | 1.25%   |
| Toshiba Satellite   | 4         | 1%      |
| Lenovo Legion       | 4         | 1%      |
| HP Notebook         | 4         | 1%      |
| Acer Aspire         | 4         | 1%      |
| Toshiba TECRA       | 3         | 0.75%   |
| Toshiba dynabook    | 3         | 0.75%   |
| HP ZBook            | 3         | 0.75%   |
| HP 630              | 3         | 0.75%   |
| Dell Precision      | 3         | 0.75%   |
| ASUS X540NA         | 3         | 0.75%   |
| TECNO WinPad        | 2         | 0.5%    |
| MSI MS-7C02         | 2         | 0.5%    |
| Lenovo Yoga         | 2         | 0.5%    |
| Lenovo ThinkCentre  | 2         | 0.5%    |
| Lenovo G50-80       | 2         | 0.5%    |
| HP ProDesk          | 2         | 0.5%    |
| Gigabyte B650M      | 2         | 0.5%    |
| Gigabyte B450       | 2         | 0.5%    |
| Endless EF20EA      | 2         | 0.5%    |
| Dell Vostro         | 2         | 0.5%    |
| ASUS ZenBook        | 2         | 0.5%    |
| ASUS UX305CA        | 2         | 0.5%    |
| Toshiba R84SAU2     | 1         | 0.25%   |
| Sony VGN-NS295J     | 1         | 0.25%   |
| SLIMBOOK PROX14-AMD | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 42        | 10.5%   |
| 2013    | 38        | 9.5%    |
| 2019    | 33        | 8.25%   |
| 2016    | 32        | 8%      |
| 2020    | 31        | 7.75%   |
| 2015    | 30        | 7.5%    |
| 2012    | 29        | 7.25%   |
| 2017    | 28        | 7%      |
| 2014    | 28        | 7%      |
| 2011    | 26        | 6.5%    |
| 2021    | 17        | 4.25%   |
| 2022    | 16        | 4%      |
| 2010    | 13        | 3.25%   |
| 2008    | 8         | 2%      |
| 2009    | 6         | 1.5%    |
| 2007    | 6         | 1.5%    |
| Unknown | 4         | 1%      |
| 2023    | 3         | 0.75%   |
| 2006    | 3         | 0.75%   |
| 2005    | 3         | 0.75%   |
| 2024    | 2         | 0.5%    |
| 2004    | 2         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 295       | 73.75%  |
| Desktop        | 65        | 16.25%  |
| Convertible    | 32        | 8%      |
| Mini pc        | 3         | 0.75%   |
| Phone          | 2         | 0.5%    |
| System on chip | 1         | 0.25%   |
| All in one     | 1         | 0.25%   |
| Server         | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 373       | 92.1%   |
| Enabled  | 32        | 7.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 400       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 111       | 27.27%  |
| 3.01-4.0        | 82        | 20.15%  |
| 16.01-24.0      | 75        | 18.43%  |
| 8.01-16.0       | 70        | 17.2%   |
| 32.01-64.0      | 24        | 5.9%    |
| 1.01-2.0        | 24        | 5.9%    |
| 64.01-256.0     | 7         | 1.72%   |
| 24.01-32.0      | 6         | 1.47%   |
| 0.51-1.0        | 4         | 0.98%   |
| 2.01-3.0        | 3         | 0.74%   |
| More than 256.0 | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 113       | 25.45%  |
| 1.01-2.0    | 101       | 22.75%  |
| 4.01-8.0    | 96        | 21.62%  |
| 3.01-4.0    | 82        | 18.47%  |
| 8.01-16.0   | 23        | 5.18%   |
| 0.51-1.0    | 23        | 5.18%   |
| 0.01-0.5    | 3         | 0.68%   |
| 64.01-256.0 | 1         | 0.23%   |
| 16.01-24.0  | 1         | 0.23%   |
| Unknown     | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 306       | 75.18%  |
| 2      | 77        | 18.92%  |
| 3      | 9         | 2.21%   |
| 4      | 6         | 1.47%   |
| 0      | 5         | 1.23%   |
| 10     | 1         | 0.25%   |
| 8      | 1         | 0.25%   |
| 6      | 1         | 0.25%   |
| 5      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 276       | 69%     |
| Yes       | 124       | 31%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 319       | 79.75%  |
| No        | 81        | 20.25%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 350       | 87.28%  |
| No        | 51        | 12.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 70.62%  |
| No        | 119       | 29.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Kenya   | 400       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Nairobi      | 364       | 88.56%  |
| Mombasa      | 12        | 2.92%   |
| Kiambu       | 4         | 0.97%   |
| Nakuru       | 3         | 0.73%   |
| Machakos     | 3         | 0.73%   |
| Embakasi     | 3         | 0.73%   |
| Nyeri        | 2         | 0.49%   |
| Nyahururu    | 2         | 0.49%   |
| Kikuyu       | 2         | 0.49%   |
| Kericho      | 2         | 0.49%   |
| Eldoret      | 2         | 0.49%   |
| Wote         | 1         | 0.24%   |
| Rongai       | 1         | 0.24%   |
| Narok        | 1         | 0.24%   |
| Nanyuki      | 1         | 0.24%   |
| Murang'a     | 1         | 0.24%   |
| Maralal      | 1         | 0.24%   |
| Mairo Inya   | 1         | 0.24%   |
| Loglogo      | 1         | 0.24%   |
| Kisii        | 1         | 0.24%   |
| Kabarnet     | 1         | 0.24%   |
| Diani        | 1         | 0.24%   |
| Archers Post | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 106       | 134    | 21.46%  |
| Samsung Electronics          | 61        | 83     | 12.35%  |
| Toshiba                      | 55        | 64     | 11.13%  |
| WDC                          | 53        | 64     | 10.73%  |
| Unknown                      | 24        | 33     | 4.86%   |
| HGST                         | 23        | 36     | 4.66%   |
| SanDisk                      | 22        | 25     | 4.45%   |
| Micron Technology            | 13        | 15     | 2.63%   |
| Hitachi                      | 13        | 16     | 2.63%   |
| SK hynix                     | 12        | 14     | 2.43%   |
| Intel                        | 11        | 16     | 2.23%   |
| Lexar                        | 8         | 8      | 1.62%   |
| Crucial                      | 7         | 9      | 1.42%   |
| KIOXIA                       | 6         | 6      | 1.21%   |
| China                        | 6         | 6      | 1.21%   |
| SPCC                         | 5         | 9      | 1.01%   |
| Silicon Motion               | 5         | 6      | 1.01%   |
| MARSHAL                      | 5         | 5      | 1.01%   |
| LITEON                       | 4         | 5      | 0.81%   |
| Kingston                     | 4         | 6      | 0.81%   |
| ADATA Technology             | 4         | 4      | 0.81%   |
| Unknown                      | 4         | 4      | 0.81%   |
| Team                         | 3         | 4      | 0.61%   |
| Micron/Crucial Technology    | 3         | 4      | 0.61%   |
| Maxtor                       | 3         | 3      | 0.61%   |
| Apple                        | 3         | 3      | 0.61%   |
| A-DATA Technology            | 3         | 3      | 0.61%   |
| HUAWEI                       | 2         | 2      | 0.4%    |
| Hjwdz                        | 2         | 2      | 0.4%    |
| Gritronix                    | 2         | 3      | 0.4%    |
| Dahua                        | 2         | 2      | 0.4%    |
| Union Memory                 | 1         | 1      | 0.2%    |
| TCSUNBOW                     | 1         | 1      | 0.2%    |
| Shenzhen Longsys Electronics | 1         | 1      | 0.2%    |
| PUSKILL                      | 1         | 2      | 0.2%    |
| Plextor                      | 1         | 1      | 0.2%    |
| Phison Electronics           | 1         | 2      | 0.2%    |
| Netac                        | 1         | 1      | 0.2%    |
| MAXIO Technology (Hangzhou)  | 1         | 1      | 0.2%    |
| MAX                          | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 17        | 3.29%   |
| Unknown MMC Card  64GB                                | 9         | 1.74%   |
| Toshiba MQ04ABF100 1TB                                | 9         | 1.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 8         | 1.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 8         | 1.55%   |
| HGST HTS725050A7E630 500GB                            | 8         | 1.55%   |
| Seagate ST500LT012-9WS142 500GB                       | 7         | 1.36%   |
| Toshiba MQ01ABF050 500GB                              | 6         | 1.16%   |
| Toshiba MQ01ABD050V 500GB                             | 6         | 1.16%   |
| Seagate ST9500325AS 500GB                             | 6         | 1.16%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 6         | 1.16%   |
| Seagate ST500VT000-1DK142 500GB                       | 5         | 0.97%   |
| Seagate ST500LT012-1DG142 500GB                       | 5         | 0.97%   |
| Seagate ST500DM002-1BD142 500GB                       | 5         | 0.97%   |
| Samsung NVMe SSD Drive 512GB                          | 5         | 0.97%   |
| Toshiba MQ01ABD100 1TB                                | 4         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 4         | 0.78%   |
| Seagate ST500LM021-1KJ152 500GB                       | 4         | 0.78%   |
| Samsung SSD 960 EVO 1TB                               | 4         | 0.78%   |
| ADATA LEGEND 710 512GB                                | 4         | 0.78%   |
| Unknown                                               | 4         | 0.78%   |
| WDC WD5000LPCX-60VHAT0 500GB                          | 3         | 0.58%   |
| WDC WD3200AAJS-56M0A0 320GB                           | 3         | 0.58%   |
| WDC PC SN730 NVMe 512GB                               | 3         | 0.58%   |
| Unknown MMC Card  32GB                                | 3         | 0.58%   |
| Toshiba DT01ACA100 1TB                                | 3         | 0.58%   |
| SPCC M.2 PCIe SSD 512GB                               | 3         | 0.58%   |
| Seagate ST500LM000-1EJ162 500GB                       | 3         | 0.58%   |
| Seagate ST3320418AS 320GB                             | 3         | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB                        | 3         | 0.58%   |
| MARSHAL MAL2500SA-T54L 500GB                          | 3         | 0.58%   |
| HGST HTS541010A9E680 1TB                              | 3         | 0.58%   |
| Crucial CT2050MX300SSD1 2TB                           | 3         | 0.58%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 2         | 0.39%   |
| WDC WD5000LPCX-24VHAT0 500GB                          | 2         | 0.39%   |
| WDC WD5000LPCX-24C6HT0 500GB                          | 2         | 0.39%   |
| WDC WD2500BEKT-75PVMT0 250GB                          | 2         | 0.39%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 2         | 0.39%   |
| WDC WD10SPZX-08Z10 1TB                                | 2         | 0.39%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 105       | 133    | 43.03%  |
| Toshiba             | 45        | 54     | 18.44%  |
| WDC                 | 43        | 52     | 17.62%  |
| HGST                | 23        | 36     | 9.43%   |
| Hitachi             | 13        | 16     | 5.33%   |
| MARSHAL             | 5         | 5      | 2.05%   |
| Samsung Electronics | 3         | 3      | 1.23%   |
| Maxtor              | 3         | 3      | 1.23%   |
| Unknown             | 1         | 1      | 0.41%   |
| JMicron Technology  | 1         | 1      | 0.41%   |
| ASMT                | 1         | 1      | 0.41%   |
| Unknown             | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 21     | 15.96%  |
| SanDisk             | 14        | 15     | 14.89%  |
| Micron Technology   | 6         | 7      | 6.38%   |
| Crucial             | 6         | 8      | 6.38%   |
| Lexar               | 5         | 5      | 5.32%   |
| China               | 5         | 5      | 5.32%   |
| Toshiba             | 4         | 4      | 4.26%   |
| LITEON              | 4         | 5      | 4.26%   |
| WDC                 | 3         | 4      | 3.19%   |
| SK hynix            | 3         | 3      | 3.19%   |
| Kingston            | 3         | 5      | 3.19%   |
| Intel               | 3         | 5      | 3.19%   |
| Team                | 2         | 2      | 2.13%   |
| SPCC                | 2         | 3      | 2.13%   |
| Gritronix           | 2         | 3      | 2.13%   |
| Apple               | 2         | 2      | 2.13%   |
| A-DATA Technology   | 2         | 2      | 2.13%   |
| Unknown             | 2         | 2      | 2.13%   |
| TCSUNBOW            | 1         | 1      | 1.06%   |
| Plextor             | 1         | 1      | 1.06%   |
| Netac               | 1         | 1      | 1.06%   |
| MAX                 | 1         | 1      | 1.06%   |
| LITEONIT            | 1         | 1      | 1.06%   |
| KINGBANK            | 1         | 1      | 1.06%   |
| GOODRAM             | 1         | 1      | 1.06%   |
| Golden              | 1         | 1      | 1.06%   |
| FZ                  | 1         | 2      | 1.06%   |
| Eluktro             | 1         | 1      | 1.06%   |
| Dahua               | 1         | 1      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 221       | 306    | 47.94%  |
| NVMe    | 121       | 161    | 26.25%  |
| SSD     | 89        | 113    | 19.31%  |
| MMC     | 23        | 31     | 4.99%   |
| Unknown | 7         | 12     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 283       | 423    | 65.06%  |
| NVMe | 121       | 161    | 27.82%  |
| MMC  | 23        | 31     | 5.29%   |
| SAS  | 8         | 8      | 1.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 207       | 281    | 66.56%  |
| 0.51-1.0   | 86        | 105    | 27.65%  |
| 1.01-2.0   | 12        | 23     | 3.86%   |
| 3.01-4.0   | 2         | 5      | 0.64%   |
| 2.01-3.0   | 2         | 2      | 0.64%   |
| 4.01-10.0  | 2         | 3      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 119       | 28.13%  |
| 101-250        | 97        | 22.93%  |
| 501-1000       | 75        | 17.73%  |
| 51-100         | 37        | 8.75%   |
| 1001-2000      | 25        | 5.91%   |
| Unknown        | 19        | 4.49%   |
| 1-20           | 18        | 4.26%   |
| More than 3000 | 12        | 2.84%   |
| 2001-3000      | 11        | 2.6%    |
| 21-50          | 10        | 2.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 114       | 26.33%  |
| 101-250        | 79        | 18.24%  |
| 21-50          | 75        | 17.32%  |
| 51-100         | 61        | 14.09%  |
| 251-500        | 47        | 10.85%  |
| 501-1000       | 20        | 4.62%   |
| Unknown        | 19        | 4.39%   |
| 1001-2000      | 13        | 3%      |
| More than 3000 | 4         | 0.92%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050V 500GB             | 5         | 5      | 8.62%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 6.9%    |
| WDC WD2500BEKT-75PVMT0 250GB          | 2         | 2      | 3.45%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 3.45%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 3.45%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 3.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 3.45%   |
| HGST HTS725050A7E630 500GB            | 2         | 2      | 3.45%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 1.72%   |
| WDC WD5000AZLX-08K2TA0 500GB          | 1         | 1      | 1.72%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 1.72%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 1      | 1.72%   |
| WDC WD10JPVX-60JC3T1 1TB              | 1         | 1      | 1.72%   |
| WDC WD10JPVX-22JC3T0 1TB              | 1         | 1      | 1.72%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.72%   |
| Toshiba MK8009GAH 80GB                | 1         | 1      | 1.72%   |
| Toshiba MK3263GSX 320GB               | 1         | 1      | 1.72%   |
| Toshiba MK3252GSX 320GB               | 1         | 1      | 1.72%   |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 1.72%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.72%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 1.72%   |
| Seagate ST500VT000-1DK142 500GB       | 1         | 1      | 1.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.72%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.72%   |
| Seagate ST3500418AS 500GB             | 1         | 1      | 1.72%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 1.72%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 1.72%   |
| Samsung Electronics HM250HI 250GB     | 1         | 1      | 1.72%   |
| MARSHAL MAL2750SA-T54 752GB           | 1         | 1      | 1.72%   |
| MARSHAL MAL2500SA-T54L 500GB          | 1         | 1      | 1.72%   |
| Hitachi HTS545032B9A300 320GB         | 1         | 1      | 1.72%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 2      | 1.72%   |
| HGST HTS725032A7E630 320GB            | 1         | 1      | 1.72%   |
| HGST HTS721010A9 1TB                  | 1         | 2      | 1.72%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 1.72%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 1.72%   |
| HGST HTS541515A9E630 1TB              | 1         | 2      | 1.72%   |
| HGST HTS541010A9E680 1TB              | 1         | 2      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 20     | 35.09%  |
| Toshiba             | 13        | 13     | 22.81%  |
| WDC                 | 8         | 8      | 14.04%  |
| HGST                | 7         | 11     | 12.28%  |
| MARSHAL             | 2         | 2      | 3.51%   |
| Hitachi             | 2         | 3      | 3.51%   |
| SK hynix            | 1         | 1      | 1.75%   |
| Samsung Electronics | 1         | 1      | 1.75%   |
| Crucial             | 1         | 2      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| Unknown             | 1         | 1      | 1.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 20     | 37.04%  |
| Toshiba             | 13        | 13     | 24.07%  |
| WDC                 | 8         | 8      | 14.81%  |
| HGST                | 7         | 11     | 12.96%  |
| MARSHAL             | 2         | 2      | 3.7%    |
| Hitachi             | 2         | 3      | 3.7%    |
| Samsung Electronics | 1         | 1      | 1.85%   |
| Unknown             | 1         | 1      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 59     | 94.64%  |
| SSD  | 3         | 4      | 5.36%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| SK hynix | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 220       | 335    | 52.76%  |
| Works    | 141       | 224    | 33.81%  |
| Malfunc  | 55        | 63     | 13.19%  |
| Failed   | 1         | 1      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                    | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Intel                                     | 311       | 66.74%  |
| Samsung Electronics                       | 47        | 10.09%  |
| AMD                                       | 23        | 4.94%   |
| SanDisk                                   | 16        | 3.43%   |
| SK hynix                                  | 9         | 1.93%   |
| Silicon Motion                            | 9         | 1.93%   |
| Micron Technology                         | 7         | 1.5%    |
| Toshiba America Info Systems              | 6         | 1.29%   |
| KIOXIA                                    | 6         | 1.29%   |
| Micron/Crucial Technology                 | 4         | 0.86%   |
| MAXIO Technology (Hangzhou)               | 4         | 0.86%   |
| ASMedia Technology                        | 4         | 0.86%   |
| ADATA Technology                          | 4         | 0.86%   |
| Shenzhen Longsys Electronics              | 3         | 0.64%   |
| Marvell Technology Group                  | 2         | 0.43%   |
| LSI Logic / Symbios Logic                 | 2         | 0.43%   |
| Union Memory (Shenzhen)                   | 1         | 0.21%   |
| Tata Power Strategic Electronics Division | 1         | 0.21%   |
| Realtek Semiconductor                     | 1         | 0.21%   |
| Phison Electronics                        | 1         | 0.21%   |
| Lite-On Technology                        | 1         | 0.21%   |
| Kingston Technology Company               | 1         | 0.21%   |
| JMicron Technology                        | 1         | 0.21%   |
| Broadcom / LSI                            | 1         | 0.21%   |
| Apple                                     | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 47        | 9.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 30        | 5.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 23        | 4.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 23        | 4.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 20        | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 20        | 3.96%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 18        | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 17        | 3.37%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 15        | 2.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 14        | 2.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 9         | 1.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 9         | 1.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 9         | 1.78%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 8         | 1.58%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 7         | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 7         | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 6         | 1.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.19%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 6         | 1.19%   |
| AMD 400 Series Chipset SATA Controller                                                 | 6         | 1.19%   |
| Intel SATA Controller [RAID mode]                                                      | 5         | 0.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 5         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 5         | 0.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 0.99%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 4         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 4         | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 4         | 0.79%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 4         | 0.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 4         | 0.79%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less) | 4         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 3         | 0.59%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 3         | 0.59%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                   | 3         | 0.59%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 3         | 0.59%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                               | 3         | 0.59%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 3         | 0.59%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 3         | 0.59%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                     | 3         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 269       | 57.48%  |
| NVMe | 121       | 25.85%  |
| RAID | 47        | 10.04%  |
| IDE  | 30        | 6.41%   |
| SCSI | 1         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 363       | 90.75%  |
| AMD    | 34        | 8.5%    |
| ARM    | 3         | 0.75%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 2.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 10        | 2.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 8         | 2%      |
| Intel Core i7-4600U CPU @ 2.10GHz       | 7         | 1.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 1.75%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 7         | 1.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 7         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 1.5%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 6         | 1.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 6         | 1.5%    |
| Intel Core i5-8350U CPU @ 1.70GHz       | 6         | 1.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 6         | 1.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 1.5%    |
| Intel Core i7-8650U CPU @ 1.90GHz       | 5         | 1.25%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 1.25%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 1.25%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 5         | 1.25%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 5         | 1.25%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 4         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz      | 4         | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 1%      |
| Intel Core i5-4310U CPU @ 2.00GHz       | 4         | 1%      |
| Intel Core i5-4200U CPU @ 1.60GHz       | 4         | 1%      |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 1%      |
| Intel Core i5-2540M CPU @ 2.60GHz       | 4         | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 1%      |
| Intel Celeron N4020 CPU @ 1.10GHz       | 4         | 1%      |
| Intel 12th Gen Core i7-12700H           | 4         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 0.75%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 3         | 0.75%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 3         | 0.75%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 3         | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 0.75%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 3         | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 0.75%   |
| Intel Core i5-3427U CPU @ 1.80GHz       | 3         | 0.75%   |
| Intel Core i5-3360M CPU @ 2.80GHz       | 3         | 0.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 0.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 131       | 32.75%  |
| Intel Core i7           | 88        | 22%     |
| Other                   | 38        | 9.5%    |
| Intel Core i3           | 30        | 7.5%    |
| Intel Celeron           | 26        | 6.5%    |
| AMD Ryzen 7             | 12        | 3%      |
| Intel Atom              | 11        | 2.75%   |
| Intel Core 2 Duo        | 9         | 2.25%   |
| AMD Ryzen 5             | 8         | 2%      |
| Intel Pentium 4         | 6         | 1.5%    |
| Intel Pentium           | 6         | 1.5%    |
| Intel Xeon              | 4         | 1%      |
| Intel Pentium Dual-Core | 3         | 0.75%   |
| Intel Core i9           | 3         | 0.75%   |
| Intel Core 2            | 3         | 0.75%   |
| Intel Core m3           | 2         | 0.5%    |
| Intel Core 2 Quad       | 2         | 0.5%    |
| AMD Ryzen 9             | 2         | 0.5%    |
| AMD FX                  | 2         | 0.5%    |
| AMD A10                 | 2         | 0.5%    |
| Intel Pentium Gold      | 1         | 0.25%   |
| Intel Pentium Dual      | 1         | 0.25%   |
| Intel Genuine           | 1         | 0.25%   |
| ARM AArch64             | 1         | 0.25%   |
| AMD Ryzen Threadripper  | 1         | 0.25%   |
| AMD Ryzen 7 PRO         | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Ryzen 3 PRO         | 1         | 0.25%   |
| AMD PRO A8              | 1         | 0.25%   |
| AMD Phenom II X3        | 1         | 0.25%   |
| AMD E2                  | 1         | 0.25%   |
| AMD A4                  | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 207       | 51.62%  |
| 4       | 124       | 30.92%  |
| 6       | 22        | 5.49%   |
| 8       | 17        | 4.24%   |
| 1       | 9         | 2.24%   |
| 14      | 6         | 1.5%    |
| 12      | 5         | 1.25%   |
| 3       | 3         | 0.75%   |
| 16      | 2         | 0.5%    |
| 10      | 2         | 0.5%    |
| Unknown | 2         | 0.5%    |
| 32      | 1         | 0.25%   |
| 20      | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 397       | 99.25%  |
| 2       | 2         | 0.5%    |
| Unknown | 1         | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 313       | 78.05%  |
| 1       | 86        | 21.45%  |
| Unknown | 2         | 0.5%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 395       | 98.75%  |
| 32-bit         | 3         | 0.75%   |
| 64-bit         | 1         | 0.25%   |
| Unknown        | 1         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 197       | 47.24%  |
| 0x306a9    | 27        | 6.47%   |
| 0x206a7    | 21        | 5.04%   |
| 0x40651    | 16        | 3.84%   |
| 0x406e3    | 14        | 3.36%   |
| 0x306c3    | 11        | 2.64%   |
| 0x806ea    | 9         | 2.16%   |
| 0x806c1    | 9         | 2.16%   |
| 0x306d4    | 8         | 1.92%   |
| 0x906ea    | 7         | 1.68%   |
| 0x806ec    | 7         | 1.68%   |
| 0x30678    | 6         | 1.44%   |
| 0x20655    | 6         | 1.44%   |
| 0x1067a    | 6         | 1.44%   |
| 0x706e5    | 5         | 1.2%    |
| 0x506e3    | 4         | 0.96%   |
| 0x406c4    | 4         | 0.96%   |
| 0x806e9    | 3         | 0.72%   |
| 0x706a8    | 3         | 0.72%   |
| 0x6fd      | 3         | 0.72%   |
| 0x0800820d | 3         | 0.72%   |
| 0xf49      | 2         | 0.48%   |
| 0x906e9    | 2         | 0.48%   |
| 0x806eb    | 2         | 0.48%   |
| 0x706a1    | 2         | 0.48%   |
| 0x6f6      | 2         | 0.48%   |
| 0x406c3    | 2         | 0.48%   |
| 0x106c2    | 2         | 0.48%   |
| 0x10676    | 2         | 0.48%   |
| 0x08608103 | 2         | 0.48%   |
| 0x08600106 | 2         | 0.48%   |
| 0xf65      | 1         | 0.24%   |
| 0xf43      | 1         | 0.24%   |
| 0xf41      | 1         | 0.24%   |
| 0xb0671    | 1         | 0.24%   |
| 0xa0652    | 1         | 0.24%   |
| 0x906ec    | 1         | 0.24%   |
| 0x906a4    | 1         | 0.24%   |
| 0x90661    | 1         | 0.24%   |
| 0x806c2    | 1         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 79        | 19.75%  |
| Haswell          | 52        | 13%     |
| Skylake          | 34        | 8.5%    |
| IvyBridge        | 34        | 8.5%    |
| SandyBridge      | 28        | 7%      |
| TigerLake        | 22        | 5.5%    |
| Silvermont       | 19        | 4.75%   |
| Broadwell        | 17        | 4.25%   |
| Westmere         | 12        | 3%      |
| Unknown          | 12        | 3%      |
| IceLake          | 10        | 2.5%    |
| Alderlake Hybrid | 10        | 2.5%    |
| Penryn           | 9         | 2.25%   |
| Core             | 9         | 2.25%   |
| Zen+             | 8         | 2%      |
| Zen 2            | 7         | 1.75%   |
| NetBurst         | 6         | 1.5%    |
| Goldmont plus    | 6         | 1.5%    |
| Zen 3            | 5         | 1.25%   |
| Goldmont         | 5         | 1.25%   |
| Excavator        | 3         | 0.75%   |
| CometLake        | 3         | 0.75%   |
| Piledriver       | 2         | 0.5%    |
| Bonnell          | 2         | 0.5%    |
| Zen              | 1         | 0.25%   |
| Tremont          | 1         | 0.25%   |
| Steamroller      | 1         | 0.25%   |
| P6               | 1         | 0.25%   |
| K10              | 1         | 0.25%   |
| Bobcat           | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 331       | 73.72%  |
| Nvidia                     | 62        | 13.81%  |
| AMD                        | 55        | 12.25%  |
| Matrox Electronics Systems | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 6.72%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 27        | 5.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 5.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 5.21%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 22        | 4.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 4.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 4.12%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 16        | 3.47%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 15        | 3.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 2.39%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 2.39%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.3%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 1.3%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 5         | 1.08%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.08%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 5         | 1.08%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 5         | 1.08%   |
| Intel DG2 [Arc A370M]                                                                    | 4         | 0.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 3         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.65%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.65%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 0.65%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.65%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.65%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.65%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.65%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.65%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.65%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 0.65%   |
| AMD Barcelo                                                                              | 3         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 278       | 69.15%  |
| 1 x AMD        | 36        | 8.96%   |
| 1 x Nvidia     | 29        | 7.21%   |
| Intel + Nvidia | 29        | 7.21%   |
| Intel + AMD    | 16        | 3.98%   |
| 2 x Intel      | 7         | 1.74%   |
| Other          | 3         | 0.75%   |
| AMD + Nvidia   | 2         | 0.5%    |
| 2 x AMD        | 1         | 0.25%   |
| 1 x Matrox     | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 362       | 89.83%  |
| Proprietary | 25        | 6.2%    |
| Unknown     | 16        | 3.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 323       | 79.95%  |
| 1.01-2.0   | 26        | 6.44%   |
| 0.01-0.5   | 20        | 4.95%   |
| 3.01-4.0   | 13        | 3.22%   |
| 0.51-1.0   | 8         | 1.98%   |
| 7.01-8.0   | 7         | 1.73%   |
| 5.01-6.0   | 4         | 0.99%   |
| 8.01-16.0  | 2         | 0.5%    |
| 16.01-24.0 | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 91        | 21.06%  |
| Chimei Innolux          | 55        | 12.73%  |
| BOE                     | 54        | 12.5%   |
| LG Display              | 47        | 10.88%  |
| Hewlett-Packard         | 42        | 9.72%   |
| Samsung Electronics     | 33        | 7.64%   |
| Dell                    | 18        | 4.17%   |
| Lenovo                  | 11        | 2.55%   |
| InfoVision              | 11        | 2.55%   |
| Sharp                   | 10        | 2.31%   |
| Sony                    | 6         | 1.39%   |
| Chi Mei Optoelectronics | 5         | 1.16%   |
| Apple                   | 5         | 1.16%   |
| CSO                     | 4         | 0.93%   |
| Unknown (XXX)           | 3         | 0.69%   |
| LG Philips              | 3         | 0.69%   |
| KDC                     | 3         | 0.69%   |
| HannStar                | 3         | 0.69%   |
| Goldstar                | 3         | 0.69%   |
| Unknown                 | 2         | 0.46%   |
| NEC Computers           | 2         | 0.46%   |
| Hitachi                 | 2         | 0.46%   |
| BenQ                    | 2         | 0.46%   |
| Acer                    | 2         | 0.46%   |
| VIE                     | 1         | 0.23%   |
| UTV                     | 1         | 0.23%   |
| Toshiba                 | 1         | 0.23%   |
| Sceptre Tech            | 1         | 0.23%   |
| S2-Tek                  | 1         | 0.23%   |
| RGT                     | 1         | 0.23%   |
| Planar                  | 1         | 0.23%   |
| MTK                     | 1         | 0.23%   |
| HKC                     | 1         | 0.23%   |
| Gigabyte Technology     | 1         | 0.23%   |
| Eizo                    | 1         | 0.23%   |
| CVT                     | 1         | 0.23%   |
| AOC                     | 1         | 0.23%   |
| Ancor Communications    | 1         | 0.23%   |
| Unknown                 | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 5         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch      | 5         | 1.14%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch       | 5         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch     | 4         | 0.91%   |
| BOE LCD Monitor BOE0A4A 2560x1600 345x215mm 16.0-inch                | 4         | 0.91%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 4         | 0.91%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch        | 4         | 0.91%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch       | 4         | 0.91%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch              | 3         | 0.68%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch | 3         | 0.68%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch          | 3         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch      | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch     | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO233E 1600x900 309x174mm 14.0-inch        | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch       | 3         | 0.68%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch       | 2         | 0.46%   |
| Sony TV SNY6F02 1360x768                                             | 2         | 0.46%   |
| Samsung Electronics S22E450 SAM0C7A 1920x1080 477x268mm 21.5-inch    | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4942 1366x768 309x174mm 14.0-inch | 2         | 0.46%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch         | 2         | 0.46%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch         | 2         | 0.46%   |
| LG Display LCD Monitor LGD0504 1366x768 340x190mm 15.3-inch          | 2         | 0.46%   |
| Lenovo T2224zD LEN60CB 1920x1080 476x267mm 21.5-inch                 | 2         | 0.46%   |
| Lenovo LEN LI1931ewA LEN65A1 1366x768 409x230mm 18.5-inch            | 2         | 0.46%   |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                 | 2         | 0.46%   |
| Hewlett-Packard Z22i HWP308B 1920x1080 477x268mm 21.5-inch           | 2         | 0.46%   |
| Hewlett-Packard V214a HPN348C 1920x1080 458x258mm 20.7-inch          | 2         | 0.46%   |
| Hewlett-Packard M27f FHD HPN370A 1920x1080 597x336mm 27.0-inch       | 2         | 0.46%   |
| Hewlett-Packard LE2002x HWP2963 1600x900 443x249mm 20.0-inch         | 2         | 0.46%   |
| Hewlett-Packard E222 HWP3262 1920x1080 476x268mm 21.5-inch           | 2         | 0.46%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 2         | 0.46%   |
| Dell E1910H DELD023 1366x768 410x230mm 18.5-inch                     | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch      | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1512 1920x1080 344x193mm 15.5-inch     | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 154       | 37.2%   |
| 1366x768 (WXGA)    | 137       | 33.09%  |
| 1600x900 (HD+)     | 26        | 6.28%   |
| 3840x2160 (4K)     | 15        | 3.62%   |
| 1280x1024 (SXGA)   | 11        | 2.66%   |
| 1920x1200 (WUXGA)  | 10        | 2.42%   |
| 1280x800 (WXGA)    | 9         | 2.17%   |
| 2560x1440 (QHD)    | 8         | 1.93%   |
| 2560x1600          | 7         | 1.69%   |
| 1440x900 (WXGA+)   | 7         | 1.69%   |
| 1680x1050 (WSXGA+) | 6         | 1.45%   |
| 1360x768           | 3         | 0.72%   |
| 3840x2400          | 2         | 0.48%   |
| 3440x1440          | 2         | 0.48%   |
| 3200x1800 (QHD+)   | 2         | 0.48%   |
| 2560x1080          | 2         | 0.48%   |
| 1024x768 (XGA)     | 2         | 0.48%   |
| 1024x600           | 2         | 0.48%   |
| Unknown            | 2         | 0.48%   |
| 3840x1600          | 1         | 0.24%   |
| 3200x1080          | 1         | 0.24%   |
| 3072x1920          | 1         | 0.24%   |
| 2288x1287          | 1         | 0.24%   |
| 2160x1440          | 1         | 0.24%   |
| 1920x1280          | 1         | 0.24%   |
| 1600x1200          | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 112       | 25.99%  |
| 13      | 82        | 19.03%  |
| 14      | 78        | 18.1%   |
| 12      | 19        | 4.41%   |
| 27      | 16        | 3.71%   |
| 21      | 15        | 3.48%   |
| 19      | 11        | 2.55%   |
| 17      | 11        | 2.55%   |
| 24      | 10        | 2.32%   |
| 18      | 9         | 2.09%   |
| 11      | 9         | 2.09%   |
| 23      | 7         | 1.62%   |
| 20      | 7         | 1.62%   |
| 16      | 7         | 1.62%   |
| 84      | 5         | 1.16%   |
| 72      | 5         | 1.16%   |
| 22      | 4         | 0.93%   |
| 63      | 3         | 0.7%    |
| 34      | 3         | 0.7%    |
| 31      | 3         | 0.7%    |
| 10      | 3         | 0.7%    |
| Unknown | 3         | 0.7%    |
| 46      | 2         | 0.46%   |
| 142     | 1         | 0.23%   |
| 86      | 1         | 0.23%   |
| 54      | 1         | 0.23%   |
| 42      | 1         | 0.23%   |
| 40      | 1         | 0.23%   |
| 32      | 1         | 0.23%   |
| 26      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 239       | 56.24%  |
| 201-300        | 72        | 16.94%  |
| 401-500        | 34        | 8%      |
| 501-600        | 33        | 7.76%   |
| 351-400        | 16        | 3.76%   |
| 1501-2000      | 10        | 2.35%   |
| 1001-1500      | 6         | 1.41%   |
| 601-700        | 4         | 0.94%   |
| 801-900        | 3         | 0.71%   |
| Unknown        | 3         | 0.71%   |
| 701-800        | 2         | 0.47%   |
| 901-1000       | 2         | 0.47%   |
| More than 2000 | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 332       | 83.21%  |
| 16/10   | 44        | 11.03%  |
| 5/4     | 11        | 2.76%   |
| 21/9    | 3         | 0.75%   |
| Unknown | 3         | 0.75%   |
| 4/3     | 2         | 0.5%    |
| 3/2     | 2         | 0.5%    |
| 1.00    | 1         | 0.25%   |
| 0.56    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 121       | 28.21%  |
| 101-110        | 111       | 25.87%  |
| 71-80          | 39        | 9.09%   |
| 201-250        | 25        | 5.83%   |
| 151-200        | 22        | 5.13%   |
| 61-70          | 19        | 4.43%   |
| More than 1000 | 16        | 3.73%   |
| 301-350        | 16        | 3.73%   |
| 141-150        | 13        | 3.03%   |
| 51-60          | 9         | 2.1%    |
| 351-500        | 7         | 1.63%   |
| 251-300        | 7         | 1.63%   |
| 111-120        | 7         | 1.63%   |
| 121-130        | 5         | 1.17%   |
| 501-1000       | 4         | 0.93%   |
| 41-50          | 3         | 0.7%    |
| Unknown        | 3         | 0.7%    |
| 131-140        | 1         | 0.23%   |
| 91-100         | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 138       | 32.78%  |
| 101-120       | 129       | 30.64%  |
| 51-100        | 83        | 19.71%  |
| 161-240       | 45        | 10.69%  |
| 1-50          | 13        | 3.09%   |
| More than 240 | 10        | 2.38%   |
| Unknown       | 3         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 336       | 82.15%  |
| 2     | 60        | 14.67%  |
| 0     | 12        | 2.93%   |
| 3     | 1         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 256       | 42.67%  |
| Realtek Semiconductor             | 168       | 28%     |
| Qualcomm Atheros                  | 51        | 8.5%    |
| Broadcom                          | 31        | 5.17%   |
| MediaTek                          | 12        | 2%      |
| Samsung Electronics               | 11        | 1.83%   |
| Broadcom Limited                  | 11        | 1.83%   |
| OPPO Electronics                  | 10        | 1.67%   |
| Hewlett-Packard                   | 9         | 1.5%    |
| Ralink                            | 6         | 1%      |
| Sierra Wireless                   | 4         | 0.67%   |
| Ralink Technology                 | 4         | 0.67%   |
| Huawei Technologies               | 4         | 0.67%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.5%    |
| Xiaomi                            | 3         | 0.5%    |
| Shenzhen Goodix Technology        | 3         | 0.5%    |
| Marvell Technology Group          | 3         | 0.5%    |
| T & A Mobile Phones               | 2         | 0.33%   |
| Spreadtrum Communications         | 2         | 0.33%   |
| Ericsson Business Mobile Networks | 2         | 0.33%   |
| VIA Technologies                  | 1         | 0.17%   |
| Qualcomm Technologies             | 1         | 0.17%   |
| Qualcomm                          | 1         | 0.17%   |
| LSI                               | 1         | 0.17%   |
| IBM                               | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 93        | 12.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 34        | 4.53%   |
| Intel Wireless 7260                                                    | 30        | 3.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 3.33%   |
| Intel Wireless 8265 / 8275                                             | 24        | 3.2%    |
| Intel Ethernet Connection I218-LM                                      | 24        | 3.2%    |
| Intel Wireless 8260                                                    | 19        | 2.53%   |
| Intel Wi-Fi 6 AX201                                                    | 17        | 2.26%   |
| Intel Ethernet Connection I219-LM                                      | 16        | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 1.86%   |
| Intel Wireless 7265                                                    | 14        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 14        | 1.86%   |
| Intel Wi-Fi 6 AX200                                                    | 13        | 1.73%   |
| Intel Ethernet Connection (4) I219-LM                                  | 13        | 1.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 12        | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 11        | 1.46%   |
| OPPO Ace 3V                                                            | 9         | 1.2%    |
| MediaTek Infinix HOT 50i                                               | 9         | 1.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 1.07%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 8         | 1.07%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 8         | 1.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 8         | 1.07%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.8%    |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.8%    |
| Intel Centrino Advanced-N 6200                                         | 6         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.8%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 5         | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 5         | 0.67%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 5         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 211       | 57.49%  |
| Realtek Semiconductor | 63        | 17.17%  |
| Qualcomm Atheros      | 45        | 12.26%  |
| Broadcom              | 23        | 6.27%   |
| Ralink                | 6         | 1.63%   |
| Hewlett-Packard       | 5         | 1.36%   |
| Sierra Wireless       | 4         | 1.09%   |
| Ralink Technology     | 4         | 1.09%   |
| Broadcom Limited      | 4         | 1.09%   |
| MediaTek              | 2         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 30        | 8.17%   |
| Intel Wireless 8265 / 8275                                     | 24        | 6.54%   |
| Intel Wireless 8260                                            | 19        | 5.18%   |
| Intel Wi-Fi 6 AX201                                            | 17        | 4.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 3.81%   |
| Intel Wireless 7265                                            | 14        | 3.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 14        | 3.81%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 3.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12        | 3.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 3%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 11        | 3%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 2.18%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 8         | 2.18%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 8         | 2.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 2.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.63%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 1.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 1.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.36%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 5         | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 1.09%   |
| Intel Wireless 3160                                            | 4         | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.09%   |
| HP lt4112 Gobi 4G Module Network Device                        | 4         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.09%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 0.82%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 0.82%   |
| Intel Wireless 3165                                            | 3         | 0.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 0.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 3         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 0.82%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.82%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 3         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 155       | 42.12%  |
| Realtek Semiconductor     | 136       | 36.96%  |
| Samsung Electronics       | 11        | 2.99%   |
| OPPO Electronics          | 10        | 2.72%   |
| MediaTek                  | 10        | 2.72%   |
| Qualcomm Atheros          | 9         | 2.45%   |
| Broadcom                  | 9         | 2.45%   |
| Broadcom Limited          | 7         | 1.9%    |
| Hewlett-Packard           | 4         | 1.09%   |
| Xiaomi                    | 3         | 0.82%   |
| Marvell Technology Group  | 3         | 0.82%   |
| T & A Mobile Phones       | 2         | 0.54%   |
| Spreadtrum Communications | 2         | 0.54%   |
| Huawei Technologies       | 2         | 0.54%   |
| VIA Technologies          | 1         | 0.27%   |
| Qualcomm Technologies     | 1         | 0.27%   |
| Qualcomm                  | 1         | 0.27%   |
| LSI                       | 1         | 0.27%   |
| IBM                       | 1         | 0.27%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 93        | 24.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 34        | 9.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 6.68%   |
| Intel Ethernet Connection I218-LM                                      | 24        | 6.42%   |
| Intel Ethernet Connection I219-LM                                      | 16        | 4.28%   |
| Intel Ethernet Connection (4) I219-LM                                  | 13        | 3.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 12        | 3.21%   |
| OPPO Ace 3V                                                            | 9         | 2.41%   |
| MediaTek Infinix HOT 50i                                               | 9         | 2.41%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.87%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 1.87%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 1.6%    |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 1.6%    |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 5         | 1.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 1.34%   |
| Intel Ethernet Connection I219-V                                       | 4         | 1.07%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.07%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 1.07%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 1.07%   |
| Broadcom Limited NetXtreme BCM5751 Gigabit Ethernet PCI Express        | 4         | 1.07%   |
| Intel I211 Gigabit Network Connection                                  | 3         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.8%    |
| HP HP lt4120 Snapdragon X5 LTE                                         | 3         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.53%   |
| T & A Mobile Phones AQUOS V6                                           | 2         | 0.53%   |
| Spreadtrum Android                                                     | 2         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.53%   |
| MediaTek A015                                                          | 2         | 0.53%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 0.53%   |
| Intel Ethernet Controller I225-V                                       | 2         | 0.53%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 2         | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 0.53%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2         | 0.53%   |
| Huawei E353/E3131                                                      | 2         | 0.53%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 350       | 51.62%  |
| Ethernet | 318       | 46.9%   |
| Modem    | 10        | 1.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 292       | 73%     |
| Ethernet | 106       | 26.5%   |
| Modem    | 2         | 0.5%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 246       | 61.04%  |
| 1     | 136       | 33.75%  |
| 0     | 14        | 3.47%   |
| 3     | 5         | 1.24%   |
| 6     | 1         | 0.25%   |
| 4     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 385       | 96.25%  |
| Yes  | 15        | 3.75%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 176       | 60.69%  |
| Realtek Semiconductor           | 27        | 9.31%   |
| Qualcomm Atheros Communications | 27        | 9.31%   |
| Broadcom                        | 16        | 5.52%   |
| Hewlett-Packard                 | 7         | 2.41%   |
| Cambridge Silicon Radio         | 6         | 2.07%   |
| Ralink                          | 5         | 1.72%   |
| Lite-On Technology              | 4         | 1.38%   |
| IMC Networks                    | 4         | 1.38%   |
| Apple                           | 3         | 1.03%   |
| Unknown                         | 3         | 1.03%   |
| Toshiba                         | 2         | 0.69%   |
| Foxconn / Hon Hai               | 2         | 0.69%   |
| Dell                            | 2         | 0.69%   |
| Actions                         | 2         | 0.69%   |
| Taiyo Yuden                     | 1         | 0.34%   |
| SiW                             | 1         | 0.34%   |
| Realtek                         | 1         | 0.34%   |
| Alps Electric                   | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 88        | 30.34%  |
| Intel AX201 Bluetooth                               | 30        | 10.34%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 20        | 6.9%    |
| Realtek Bluetooth Radio                             | 19        | 6.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 4.83%   |
| Intel AX200 Bluetooth                               | 13        | 4.48%   |
| Intel Bluetooth Device                              | 10        | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.07%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 2.07%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 2.07%   |
| Ralink RT3290 Bluetooth                             | 5         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.72%   |
| Broadcom HP Portable SoftSailing                    | 5         | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.38%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 1.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.03%   |
| Intel AX210 Bluetooth                               | 3         | 1.03%   |
| IMC Networks Bluetooth Device                       | 3         | 1.03%   |
| Unknown                                             | 3         | 1.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.69%   |
| Lite-On Bluetooth Device                            | 2         | 0.69%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.69%   |
| Actions general adapter                             | 2         | 0.69%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.34%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.34%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.34%   |
| SiW SiW                                             | 1         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.34%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.34%   |
| Realtek Bluetooth Radio                             | 1         | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.34%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.34%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.34%   |
| IMC Networks Bluetooth                              | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 350       | 75.59%  |
| AMD                         | 43        | 9.29%   |
| Nvidia                      | 40        | 8.64%   |
| Realtek Semiconductor       | 5         | 1.08%   |
| Generalplus Technology      | 4         | 0.86%   |
| Texas Instruments           | 3         | 0.65%   |
| Micro Star International    | 3         | 0.65%   |
| C-Media Electronics         | 3         | 0.65%   |
| Lenovo                      | 2         | 0.43%   |
| Turtle Beach                | 1         | 0.22%   |
| Toshiba                     | 1         | 0.22%   |
| Medeli Electronics          | 1         | 0.22%   |
| Logitech                    | 1         | 0.22%   |
| JMTek                       | 1         | 0.22%   |
| GN Netcom                   | 1         | 0.22%   |
| Giga-Byte Technology        | 1         | 0.22%   |
| FiiO Electronics Technology | 1         | 0.22%   |
| Blue Microphones            | 1         | 0.22%   |
| Apple                       | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 68        | 12.25%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 5.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 5.59%   |
| Intel 8 Series HD Audio Controller                                                                | 30        | 5.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 5.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 3.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 3.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 3.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 19        | 3.42%   |
| AMD Ryzen HD Audio Controller                                                                     | 18        | 3.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 3.06%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 3.06%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 11        | 1.98%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 1.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.9%    |
| Realtek Semiconductor HP Banff                                                                    | 4         | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.72%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.72%   |
| Generalplus Technology USB Audio Device                                                           | 4         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.54%   |
| Micro Star International USB Audio                                                                | 3         | 0.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.54%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.54%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 30.69%  |
| SK hynix            | 76        | 26.21%  |
| Micron Technology   | 34        | 11.72%  |
| Kingston            | 17        | 5.86%   |
| Unknown             | 15        | 5.17%   |
| Crucial             | 13        | 4.48%   |
| Ramaxel Technology  | 8         | 2.76%   |
| Elpida              | 7         | 2.41%   |
| Unknown             | 6         | 2.07%   |
| A-DATA Technology   | 4         | 1.38%   |
| Team                | 3         | 1.03%   |
| Lexar               | 3         | 1.03%   |
| Timetec             | 2         | 0.69%   |
| G.Skill             | 2         | 0.69%   |
| Apacer              | 2         | 0.69%   |
| Wilk                | 1         | 0.34%   |
| Unknown (ABCD)      | 1         | 0.34%   |
| TwinMOS             | 1         | 0.34%   |
| Transcend           | 1         | 0.34%   |
| Qimonda             | 1         | 0.34%   |
| Patriot             | 1         | 0.34%   |
| Nanya Technology    | 1         | 0.34%   |
| Corsair             | 1         | 0.34%   |
| Avant               | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 9         | 2.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 6         | 1.99%   |
| Unknown                                                      | 6         | 1.99%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 5         | 1.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s       | 5         | 1.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                  | 5         | 1.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 4         | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s        | 4         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 4         | 1.32%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s      | 4         | 1.32%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 4         | 1.32%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 3         | 0.99%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s          | 3         | 0.99%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 3         | 0.99%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.99%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 3         | 0.99%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.99%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s  | 3         | 0.99%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s        | 3         | 0.99%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s        | 3         | 0.99%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s        | 3         | 0.99%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 2         | 0.66%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 2         | 0.66%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.66%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 0.66%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.66%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                  | 2         | 0.66%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 2         | 0.66%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s | 2         | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 93        | 40.61%  |
| DDR3   | 91        | 39.74%  |
| LPDDR4 | 12        | 5.24%   |
| DDR5   | 10        | 4.37%   |
| DDR2   | 7         | 3.06%   |
| SDRAM  | 6         | 2.62%   |
| LPDDR3 | 6         | 2.62%   |
| DDR    | 3         | 1.31%   |
| LPDDR5 | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 169       | 72.22%  |
| DIMM         | 31        | 13.25%  |
| Row Of Chips | 27        | 11.54%  |
| Chip         | 7         | 2.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 88        | 34.11%  |
| 4096  | 83        | 32.17%  |
| 16384 | 38        | 14.73%  |
| 2048  | 28        | 10.85%  |
| 32768 | 12        | 4.65%   |
| 1024  | 8         | 3.1%    |
| 512   | 1         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 72        | 28.35%  |
| 2667    | 51        | 20.08%  |
| 3200    | 27        | 10.63%  |
| 2133    | 21        | 8.27%   |
| 4267    | 11        | 4.33%   |
| 1333    | 11        | 4.33%   |
| 2400    | 9         | 3.54%   |
| 1334    | 7         | 2.76%   |
| 4800    | 5         | 1.97%   |
| 1867    | 4         | 1.57%   |
| 667     | 4         | 1.57%   |
| 8400    | 3         | 1.18%   |
| 5600    | 2         | 0.79%   |
| 3600    | 2         | 0.79%   |
| 3266    | 2         | 0.79%   |
| 2666    | 2         | 0.79%   |
| 1067    | 2         | 0.79%   |
| 800     | 2         | 0.79%   |
| 533     | 2         | 0.79%   |
| Unknown | 2         | 0.79%   |
| 6400    | 1         | 0.39%   |
| 6000    | 1         | 0.39%   |
| 5800    | 1         | 0.39%   |
| 5200    | 1         | 0.39%   |
| 4199    | 1         | 0.39%   |
| 3800    | 1         | 0.39%   |
| 2465    | 1         | 0.39%   |
| 2000    | 1         | 0.39%   |
| 1800    | 1         | 0.39%   |
| 1648    | 1         | 0.39%   |
| 1639    | 1         | 0.39%   |
| 400     | 1         | 0.39%   |
| 333     | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP HP LaserJet M101-M106 | 1         | 100%    |

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
| Chicony Electronics                    | 97        | 31.09%  |
| Cheng Uei Precision Industry (Foxlink) | 40        | 12.82%  |
| Lite-On Technology                     | 21        | 6.73%   |
| Realtek Semiconductor                  | 18        | 5.77%   |
| Bison Electronics                      | 18        | 5.77%   |
| Sunplus Innovation Technology          | 17        | 5.45%   |
| IMC Networks                           | 14        | 4.49%   |
| Syntek                                 | 12        | 3.85%   |
| Microdia                               | 12        | 3.85%   |
| Quanta                                 | 11        | 3.53%   |
| Samsung Electronics                    | 6         | 1.92%   |
| Luxvisions Innotech Limited            | 6         | 1.92%   |
| Logitech                               | 5         | 1.6%    |
| Apple                                  | 5         | 1.6%    |
| Suyin                                  | 4         | 1.28%   |
| Silicon Motion                         | 4         | 1.28%   |
| Alcor Micro                            | 3         | 0.96%   |
| Unknown                                | 2         | 0.64%   |
| Ricoh                                  | 2         | 0.64%   |
| Importek                               | 2         | 0.64%   |
| Acer                                   | 2         | 0.64%   |
| Z-Star Microelectronics                | 1         | 0.32%   |
| Xiaomi                                 | 1         | 0.32%   |
| SunplusIT                              | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| MacroSilicon                           | 1         | 0.32%   |
| LG Electronics                         | 1         | 0.32%   |
| icSpring                               | 1         | 0.32%   |
| DigiTech                               | 1         | 0.32%   |
| Cubeternet                             | 1         | 0.32%   |
| ALi                                    | 1         | 0.32%   |
| Unknown                                | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 22        | 6.96%   |
| Chicony HP HD Webcam                                                       | 13        | 4.11%   |
| Lite-On HP HD Camera                                                       | 12        | 3.8%    |
| Chicony HP HD Camera                                                       | 12        | 3.8%    |
| Realtek Integrated_Webcam_HD                                               | 9         | 2.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 9         | 2.85%   |
| Syntek Integrated Camera                                                   | 8         | 2.53%   |
| Lite-On HP HD Webcam                                                       | 7         | 2.22%   |
| Chicony HP HD Webcam [Fixed]                                               | 7         | 2.22%   |
| Microdia Integrated_Webcam_HD                                              | 6         | 1.9%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 6         | 1.9%    |
| Bison Integrated Camera                                                    | 6         | 1.9%    |
| Sunplus Integrated_Webcam_HD                                               | 5         | 1.58%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 5         | 1.58%   |
| Chicony USB 2.0 Camera                                                     | 5         | 1.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 5         | 1.58%   |
| Sunplus HP HD Webcam [Fixed]                                               | 4         | 1.27%   |
| Quanta HP True Vision 5MP Camera                                           | 4         | 1.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 1.27%   |
| Chicony Integrated HP HD Webcam                                            | 4         | 1.27%   |
| Chicony HP Wide Vision HD Camera                                           | 4         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed]                | 4         | 1.27%   |
| Realtek Integrated Webcam                                                  | 3         | 0.95%   |
| Quanta HP HD Camera                                                        | 3         | 0.95%   |
| IMC Networks Integrated Camera                                             | 3         | 0.95%   |
| Chicony TOSHIBA Web Camera - HD                                            | 3         | 0.95%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.95%   |
| Chicony HP TrueVision HD Camera                                            | 3         | 0.95%   |
| Chicony HD Webcam                                                          | 3         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 3         | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam   | 3         | 0.95%   |
| Bison ThinkPad P50 Integrated Camera                                       | 3         | 0.95%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 3         | 0.95%   |
| Unknown USB Camera                                                         | 2         | 0.63%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.63%   |
| Syntek EasyCamera                                                          | 2         | 0.63%   |
| Suyin Asus Integrated Webcam                                               | 2         | 0.63%   |
| Sunplus HP Truevision Full HD                                              | 2         | 0.63%   |
| Silicon Motion 300k Pixel Camera                                           | 2         | 0.63%   |
| Realtek USB Camera                                                         | 2         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 67        | 62.62%  |
| Synaptics                  | 29        | 27.1%   |
| Shenzhen Goodix Technology | 7         | 6.54%   |
| AuthenTec                  | 2         | 1.87%   |
| LighTuning Technology      | 1         | 0.93%   |
| Elan Microelectronics      | 1         | 0.93%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 21.5%   |
| Validity Sensors VFS491                                                    | 11        | 10.28%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 7.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 6.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 4.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.67%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 4.67%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.74%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 3.74%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 3.74%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 3.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.8%    |
| Synaptics WBDI Device                                                      | 3         | 2.8%    |
| Synaptics UWP WBDI                                                         | 3         | 2.8%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.87%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.87%   |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1.87%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 1.87%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.93%   |
| Synaptics WBDI                                                             | 1         | 0.93%   |
| Synaptics  WBDI                                                            | 1         | 0.93%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.93%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.93%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.93%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.93%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.93%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.93%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 47.62%  |
| Alcor Micro | 7         | 33.33%  |
| Upek        | 2         | 9.52%   |
| O2 Micro    | 2         | 9.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 19.05%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 9.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 9.52%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 9.52%   |
| Broadcom 5880                                                                | 2         | 9.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 249       | 61.79%  |
| 1     | 126       | 31.27%  |
| 2     | 26        | 6.45%   |
| 3     | 2         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 105       | 57.07%  |
| Graphics card            | 22        | 11.96%  |
| Chipcard                 | 19        | 10.33%  |
| Net/wireless             | 9         | 4.89%   |
| Multimedia controller    | 7         | 3.8%    |
| Bluetooth                | 6         | 3.26%   |
| Net/ethernet             | 4         | 2.17%   |
| Camera                   | 4         | 2.17%   |
| Storage                  | 3         | 1.63%   |
| Communication controller | 3         | 1.63%   |
| Unassigned class         | 1         | 0.54%   |
| Sound                    | 1         | 0.54%   |


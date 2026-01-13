Ubuntu 23.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_23.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_23.04/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 2381

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5285               | Tablet      | [9a9b4a5979](https://linux-hardware.org/?probe=9a9b4a5979) | Sep 23, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f191f87d7d](https://linux-hardware.org/?probe=f191f87d7d) | Sep 05, 2025 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [2e0813494e](https://linux-hardware.org/?probe=2e0813494e) | Jul 29, 2025 |
| Pegatron      | A15                         | Notebook    | [5b0b8980a4](https://linux-hardware.org/?probe=5b0b8980a4) | Jul 28, 2025 |
| KUU           | Andes II                    | Notebook    | [fc5f731545](https://linux-hardware.org/?probe=fc5f731545) | Jul 27, 2025 |
| Foxconn       | 2AB1                        | Desktop     | [c5631aa660](https://linux-hardware.org/?probe=c5631aa660) | May 26, 2025 |
| ASUSTek       | P9D-I Series                | Server      | [2d9837a264](https://linux-hardware.org/?probe=2d9837a264) | Mar 17, 2025 |
| ASUSTek       | P9D-I Series                | Server      | [a67c20717f](https://linux-hardware.org/?probe=a67c20717f) | Mar 17, 2025 |
| Gigabyte      | Z97-HD3                     | Desktop     | [0d7ede0a93](https://linux-hardware.org/?probe=0d7ede0a93) | Feb 12, 2025 |
| Dell          | Latitude 5285               | Tablet      | [ac7333f2f2](https://linux-hardware.org/?probe=ac7333f2f2) | Feb 11, 2025 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [5c48a6cbc6](https://linux-hardware.org/?probe=5c48a6cbc6) | Feb 10, 2025 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [b886c494b6](https://linux-hardware.org/?probe=b886c494b6) | Feb 07, 2025 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [0231737737](https://linux-hardware.org/?probe=0231737737) | Jan 18, 2025 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2abcf6cc31](https://linux-hardware.org/?probe=2abcf6cc31) | Jan 10, 2025 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [39f87e2ae9](https://linux-hardware.org/?probe=39f87e2ae9) | Jan 10, 2025 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [73563fa71e](https://linux-hardware.org/?probe=73563fa71e) | Jan 09, 2025 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [6462e457e9](https://linux-hardware.org/?probe=6462e457e9) | Dec 09, 2024 |
| MSI           | MS-7369                     | Desktop     | [fbfb1c6e78](https://linux-hardware.org/?probe=fbfb1c6e78) | Dec 06, 2024 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [19d479aa20](https://linux-hardware.org/?probe=19d479aa20) | Nov 29, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [eebf56fc6a](https://linux-hardware.org/?probe=eebf56fc6a) | Nov 27, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4a7b0a2801](https://linux-hardware.org/?probe=4a7b0a2801) | Nov 27, 2024 |
| HP            | Notebook                    | Notebook    | [f69f443717](https://linux-hardware.org/?probe=f69f443717) | Nov 24, 2024 |
| HP            | Notebook                    | Notebook    | [d7db4f31e7](https://linux-hardware.org/?probe=d7db4f31e7) | Nov 23, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [451e240ca8](https://linux-hardware.org/?probe=451e240ca8) | Nov 22, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d9617a8ee3](https://linux-hardware.org/?probe=d9617a8ee3) | Nov 09, 2024 |
| HP            | Laptop 15-da2xxx            | Notebook    | [2993fbf2fd](https://linux-hardware.org/?probe=2993fbf2fd) | Oct 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [03eebd41be](https://linux-hardware.org/?probe=03eebd41be) | Oct 18, 2024 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [4408efdf19](https://linux-hardware.org/?probe=4408efdf19) | Oct 15, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f45d5fb501](https://linux-hardware.org/?probe=f45d5fb501) | Oct 12, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e6b4955912](https://linux-hardware.org/?probe=e6b4955912) | Oct 11, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d6b18ca125](https://linux-hardware.org/?probe=d6b18ca125) | Oct 04, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [120c77e7c3](https://linux-hardware.org/?probe=120c77e7c3) | Sep 26, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [398aa74a06](https://linux-hardware.org/?probe=398aa74a06) | Sep 26, 2024 |
| Dell          | Studio XPS 1340             | Notebook    | [f9c9d55cef](https://linux-hardware.org/?probe=f9c9d55cef) | Sep 23, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [7e6ff11505](https://linux-hardware.org/?probe=7e6ff11505) | Sep 21, 2024 |
| Dell          | Studio XPS 1340             | Notebook    | [f0b700fa8a](https://linux-hardware.org/?probe=f0b700fa8a) | Sep 17, 2024 |
| HP            | 8653 A                      | Desktop     | [7d784dded4](https://linux-hardware.org/?probe=7d784dded4) | Sep 12, 2024 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [8a90694fa1](https://linux-hardware.org/?probe=8a90694fa1) | Sep 11, 2024 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [b8ebd625a7](https://linux-hardware.org/?probe=b8ebd625a7) | Sep 07, 2024 |
| ASRockRack    | E3C246D4U2-2T               | Desktop     | [5e5d56e397](https://linux-hardware.org/?probe=5e5d56e397) | Sep 03, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [36293285f3](https://linux-hardware.org/?probe=36293285f3) | Aug 21, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [7297672016](https://linux-hardware.org/?probe=7297672016) | Aug 15, 2024 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [2b45b0ddf3](https://linux-hardware.org/?probe=2b45b0ddf3) | Aug 14, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [e5f519edd5](https://linux-hardware.org/?probe=e5f519edd5) | Aug 03, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [0185457c65](https://linux-hardware.org/?probe=0185457c65) | Jul 30, 2024 |
| Intel         | X99-P4 V5.1                 | Desktop     | [def260ec4e](https://linux-hardware.org/?probe=def260ec4e) | Jul 28, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ffa823879e](https://linux-hardware.org/?probe=ffa823879e) | Jul 25, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b3ded0b9fe](https://linux-hardware.org/?probe=b3ded0b9fe) | Jul 25, 2024 |
| HP            | Notebook                    | Notebook    | [923154387f](https://linux-hardware.org/?probe=923154387f) | Jul 23, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d8431d5193](https://linux-hardware.org/?probe=d8431d5193) | Jul 22, 2024 |
| Toshiba       | Satellite L750              | Notebook    | [402a15076f](https://linux-hardware.org/?probe=402a15076f) | Jul 01, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [807461b683](https://linux-hardware.org/?probe=807461b683) | Jul 01, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [d85522ab8f](https://linux-hardware.org/?probe=d85522ab8f) | Jun 27, 2024 |
| TUXEDO        | N85_N87,HJ,HJ1,HK1          | Notebook    | [578491026d](https://linux-hardware.org/?probe=578491026d) | Jun 27, 2024 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [20fbc33751](https://linux-hardware.org/?probe=20fbc33751) | Jun 25, 2024 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [acd559a149](https://linux-hardware.org/?probe=acd559a149) | Jun 25, 2024 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [901ec74a46](https://linux-hardware.org/?probe=901ec74a46) | Jun 24, 2024 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [2c09a7ed14](https://linux-hardware.org/?probe=2c09a7ed14) | Jun 23, 2024 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [9dd13ddffa](https://linux-hardware.org/?probe=9dd13ddffa) | Jun 23, 2024 |
| HP            | 843B                        | Desktop     | [5a704db5ca](https://linux-hardware.org/?probe=5a704db5ca) | Jun 22, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [1705a51bab](https://linux-hardware.org/?probe=1705a51bab) | Jun 19, 2024 |
| Positivo      | POS-PIB150DT                | Desktop     | [7e1dc46d4f](https://linux-hardware.org/?probe=7e1dc46d4f) | Jun 11, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [9f5b783071](https://linux-hardware.org/?probe=9f5b783071) | Jun 08, 2024 |
| HP            | 1998                        | Desktop     | [00c947e607](https://linux-hardware.org/?probe=00c947e607) | Jun 05, 2024 |
| HP            | 1998                        | Desktop     | [04e116c090](https://linux-hardware.org/?probe=04e116c090) | Jun 05, 2024 |
| HP            | 1998                        | Desktop     | [bf50a71cc6](https://linux-hardware.org/?probe=bf50a71cc6) | Jun 05, 2024 |
| MSI           | MAG B560M MORTAR            | Desktop     | [d3b39f4086](https://linux-hardware.org/?probe=d3b39f4086) | Jun 05, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [bf9bc5df80](https://linux-hardware.org/?probe=bf9bc5df80) | May 23, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [dc23737df9](https://linux-hardware.org/?probe=dc23737df9) | May 12, 2024 |
| ASUSTek       | TUF Gaming B760-PLUS WIF... | Desktop     | [775f9b664d](https://linux-hardware.org/?probe=775f9b664d) | May 12, 2024 |
| Lenovo        | 318D                        | All in one  | [c80ee9b90b](https://linux-hardware.org/?probe=c80ee9b90b) | May 11, 2024 |
| Fujitsu       | D3402-B2 S26361-D3402-B2    | Desktop     | [57bfc992d9](https://linux-hardware.org/?probe=57bfc992d9) | May 10, 2024 |
| Dell          | Latitude 5490               | Notebook    | [a8db3589fb](https://linux-hardware.org/?probe=a8db3589fb) | May 02, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [aded29632d](https://linux-hardware.org/?probe=aded29632d) | Apr 28, 2024 |
| Lenovo        | 318D                        | All in one  | [c85d113322](https://linux-hardware.org/?probe=c85d113322) | Apr 27, 2024 |
| Lenovo        | 318D                        | All in one  | [0d2c921580](https://linux-hardware.org/?probe=0d2c921580) | Apr 27, 2024 |
| ASRock        | Z77 Extreme3                | Desktop     | [83083ad34f](https://linux-hardware.org/?probe=83083ad34f) | Apr 26, 2024 |
| HP            | Notebook                    | Notebook    | [982806e31a](https://linux-hardware.org/?probe=982806e31a) | Apr 19, 2024 |
| Acer          | Aspire E1-571               | Notebook    | [f7a83b5113](https://linux-hardware.org/?probe=f7a83b5113) | Apr 17, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [9e81741e0e](https://linux-hardware.org/?probe=9e81741e0e) | Apr 14, 2024 |
| Lenovo        | ThinkPad X220 42913J9       | Notebook    | [b3eb1ea727](https://linux-hardware.org/?probe=b3eb1ea727) | Apr 11, 2024 |
| Maibenben     | Typhoon Series              | Notebook    | [f2ecb7a366](https://linux-hardware.org/?probe=f2ecb7a366) | Apr 07, 2024 |
| Dell          | Latitude 5480               | Notebook    | [26d58cfc3d](https://linux-hardware.org/?probe=26d58cfc3d) | Apr 04, 2024 |
| Gigabyte      | B760M AORUS ELITE           | Desktop     | [abd7f2bfbc](https://linux-hardware.org/?probe=abd7f2bfbc) | Apr 03, 2024 |
| Dell          | Latitude 5480               | Notebook    | [199495c670](https://linux-hardware.org/?probe=199495c670) | Mar 30, 2024 |
| Lenovo        | ThinkPad T470 20HD0001MH    | Notebook    | [5999aa3b46](https://linux-hardware.org/?probe=5999aa3b46) | Mar 26, 2024 |
| HP            | EliteBook x360 1040 G5      | Convertible | [99a87a4f89](https://linux-hardware.org/?probe=99a87a4f89) | Mar 18, 2024 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | Notebook    | [f2bbb15237](https://linux-hardware.org/?probe=f2bbb15237) | Mar 13, 2024 |
| Lenovo        | 318D                        | All in one  | [034a272f81](https://linux-hardware.org/?probe=034a272f81) | Mar 12, 2024 |
| Lenovo        | 318D                        | All in one  | [2ea0575aec](https://linux-hardware.org/?probe=2ea0575aec) | Mar 11, 2024 |
| Acer          | Aspire Lite AL15-41         | Notebook    | [720c77ea8e](https://linux-hardware.org/?probe=720c77ea8e) | Mar 10, 2024 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [6ce6fdc6b2](https://linux-hardware.org/?probe=6ce6fdc6b2) | Mar 04, 2024 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [4630b4cee6](https://linux-hardware.org/?probe=4630b4cee6) | Mar 04, 2024 |
| HP            | 843B                        | Desktop     | [8d6b0674a6](https://linux-hardware.org/?probe=8d6b0674a6) | Feb 29, 2024 |
| Supermicro    | X10DRH-CT                   | Desktop     | [085564adc0](https://linux-hardware.org/?probe=085564adc0) | Feb 24, 2024 |
| Medion        | B360H4-EM V1.0              | Desktop     | [45981f1ad4](https://linux-hardware.org/?probe=45981f1ad4) | Feb 23, 2024 |
| Lenovo        | ThinkPad E450c 20EH0001C... | Notebook    | [75c5905fab](https://linux-hardware.org/?probe=75c5905fab) | Feb 21, 2024 |
| Lenovo        | ThinkPad T570 20H9001EMD    | Notebook    | [0841df80ee](https://linux-hardware.org/?probe=0841df80ee) | Feb 21, 2024 |
| HP            | Stream Notebook PC 13       | Notebook    | [1df20b4ef4](https://linux-hardware.org/?probe=1df20b4ef4) | Feb 21, 2024 |
| HP            | EliteBook 8730w             | Notebook    | [f49b3c47c3](https://linux-hardware.org/?probe=f49b3c47c3) | Feb 19, 2024 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [f253025d97](https://linux-hardware.org/?probe=f253025d97) | Feb 17, 2024 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [2b1227aff7](https://linux-hardware.org/?probe=2b1227aff7) | Feb 17, 2024 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [0a9db7ec56](https://linux-hardware.org/?probe=0a9db7ec56) | Feb 16, 2024 |
| Gigabyte      | H81ND2H                     | Desktop     | [eca344c342](https://linux-hardware.org/?probe=eca344c342) | Feb 09, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [6b8c1318cc](https://linux-hardware.org/?probe=6b8c1318cc) | Feb 09, 2024 |
| ASRock        | Z270 Gaming-ITX/ac          | Desktop     | [b417d2ae80](https://linux-hardware.org/?probe=b417d2ae80) | Feb 07, 2024 |
| Shuttle       | FH87                        | Desktop     | [3f1a7051b6](https://linux-hardware.org/?probe=3f1a7051b6) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1268b55429](https://linux-hardware.org/?probe=1268b55429) | Feb 04, 2024 |
| Shuttle       | FH87                        | Desktop     | [781377b2cd](https://linux-hardware.org/?probe=781377b2cd) | Feb 04, 2024 |
| ASUSTek       | P5K                         | Desktop     | [2596e1adb2](https://linux-hardware.org/?probe=2596e1adb2) | Jan 29, 2024 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [42e8e68344](https://linux-hardware.org/?probe=42e8e68344) | Jan 26, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [18fc8668de](https://linux-hardware.org/?probe=18fc8668de) | Jan 25, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [2bfb559750](https://linux-hardware.org/?probe=2bfb559750) | Jan 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [606adf78f9](https://linux-hardware.org/?probe=606adf78f9) | Jan 24, 2024 |
| ASUSTek       | ROG Rampage VI EXTREME E... | Desktop     | [299dd0311b](https://linux-hardware.org/?probe=299dd0311b) | Jan 24, 2024 |
| HP            | ProBook 455 G1              | Notebook    | [224d863e1d](https://linux-hardware.org/?probe=224d863e1d) | Jan 23, 2024 |
| Google        | Woomax                      | Notebook    | [8b76a06477](https://linux-hardware.org/?probe=8b76a06477) | Jan 23, 2024 |
| ASUSTek       | X99-A/USB                   | Desktop     | [c07863641d](https://linux-hardware.org/?probe=c07863641d) | Jan 22, 2024 |
| Lenovo        | ThinkPad T420 4238AC6       | Notebook    | [8c171e6ffa](https://linux-hardware.org/?probe=8c171e6ffa) | Jan 22, 2024 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ec13e42e3a](https://linux-hardware.org/?probe=ec13e42e3a) | Jan 20, 2024 |
| Gigabyte      | A520M S2H                   | Desktop     | [cf1f6f18f3](https://linux-hardware.org/?probe=cf1f6f18f3) | Jan 17, 2024 |
| ONDA          | H61V Ver:4.01               | Desktop     | [83030b6f99](https://linux-hardware.org/?probe=83030b6f99) | Jan 16, 2024 |
| Packard Be... | EasyNote TJ65               | Notebook    | [bcf20a0a9c](https://linux-hardware.org/?probe=bcf20a0a9c) | Jan 16, 2024 |
| Dell          | Inspiron 7570               | Notebook    | [bdea5ae4df](https://linux-hardware.org/?probe=bdea5ae4df) | Jan 16, 2024 |
| Lenovo        | ThinkPad T460p 20FXS1G70... | Notebook    | [519458acdc](https://linux-hardware.org/?probe=519458acdc) | Jan 15, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [696f5dd9e3](https://linux-hardware.org/?probe=696f5dd9e3) | Jan 12, 2024 |
| Dell          | 0K1D6X A00                  | Desktop     | [a47ccd2cfe](https://linux-hardware.org/?probe=a47ccd2cfe) | Jan 11, 2024 |
| Dell          | 0K1D6X A00                  | Desktop     | [5fc28b03c2](https://linux-hardware.org/?probe=5fc28b03c2) | Jan 11, 2024 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9b3ca5c984](https://linux-hardware.org/?probe=9b3ca5c984) | Jan 11, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [92202ac225](https://linux-hardware.org/?probe=92202ac225) | Jan 11, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [e34d332260](https://linux-hardware.org/?probe=e34d332260) | Jan 10, 2024 |
| ASUSTek       | X542UA                      | Notebook    | [028b7c4d83](https://linux-hardware.org/?probe=028b7c4d83) | Jan 08, 2024 |
| Intel         | JSL MRD                     | Desktop     | [546cbf14b5](https://linux-hardware.org/?probe=546cbf14b5) | Jan 06, 2024 |
| HP            | ProBook 4530s               | Notebook    | [0fe11a7b3d](https://linux-hardware.org/?probe=0fe11a7b3d) | Jan 05, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [0e3e8e1d4a](https://linux-hardware.org/?probe=0e3e8e1d4a) | Jan 05, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [5e4cd95800](https://linux-hardware.org/?probe=5e4cd95800) | Jan 05, 2024 |
| ASUSTek       | X542UA                      | Notebook    | [5d7b076a1c](https://linux-hardware.org/?probe=5d7b076a1c) | Jan 05, 2024 |
| Samsung       | DP700A3D-X01PL SEC_SW_RE... | All in one  | [d46262e2ef](https://linux-hardware.org/?probe=d46262e2ef) | Jan 04, 2024 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [9a18a450f2](https://linux-hardware.org/?probe=9a18a450f2) | Jan 04, 2024 |
| Dell          | 0M858N A01                  | Desktop     | [9f73363db2](https://linux-hardware.org/?probe=9f73363db2) | Jan 04, 2024 |
| Dell          | Inspiron 5749               | Notebook    | [de1b1d1851](https://linux-hardware.org/?probe=de1b1d1851) | Jan 04, 2024 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [6a25b4f0dc](https://linux-hardware.org/?probe=6a25b4f0dc) | Jan 03, 2024 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | Desktop     | [2b1a79920a](https://linux-hardware.org/?probe=2b1a79920a) | Jan 03, 2024 |
| Positivo B... | VJFE42F11X-B2891H           | Notebook    | [47c3c6c806](https://linux-hardware.org/?probe=47c3c6c806) | Jan 03, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [31f27ced42](https://linux-hardware.org/?probe=31f27ced42) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Notebook    | [ec8f742a7f](https://linux-hardware.org/?probe=ec8f742a7f) | Dec 31, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Toshiba       | Satellite P70-B             | Notebook    | [2a5acedd16](https://linux-hardware.org/?probe=2a5acedd16) | Dec 29, 2023 |
| Dell          | Latitude E7450              | Notebook    | [50b3989c19](https://linux-hardware.org/?probe=50b3989c19) | Dec 28, 2023 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [e0bfd9face](https://linux-hardware.org/?probe=e0bfd9face) | Dec 28, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [d132700b11](https://linux-hardware.org/?probe=d132700b11) | Dec 28, 2023 |
| Dell          | Latitude 5420               | Notebook    | [07b64f5dfe](https://linux-hardware.org/?probe=07b64f5dfe) | Dec 27, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a82bef9300](https://linux-hardware.org/?probe=a82bef9300) | Dec 25, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [a1945990cc](https://linux-hardware.org/?probe=a1945990cc) | Dec 24, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [e02428db4a](https://linux-hardware.org/?probe=e02428db4a) | Dec 24, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [a70e7da743](https://linux-hardware.org/?probe=a70e7da743) | Dec 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ab3cc8a89c](https://linux-hardware.org/?probe=ab3cc8a89c) | Dec 23, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [bc65f1d620](https://linux-hardware.org/?probe=bc65f1d620) | Dec 21, 2023 |
| Supermicro    | X9DRD-7LN4F                 | Desktop     | [56a303c264](https://linux-hardware.org/?probe=56a303c264) | Dec 20, 2023 |
| Lenovo        | 330B SDK0T76530 WIN 3556... | Mini pc     | [97d6dd408b](https://linux-hardware.org/?probe=97d6dd408b) | Dec 19, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [6c0f2ad0c9](https://linux-hardware.org/?probe=6c0f2ad0c9) | Dec 18, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [0ae780878c](https://linux-hardware.org/?probe=0ae780878c) | Dec 18, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [458a8fb3f1](https://linux-hardware.org/?probe=458a8fb3f1) | Dec 18, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [ad8a2053bc](https://linux-hardware.org/?probe=ad8a2053bc) | Dec 17, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [43602a664e](https://linux-hardware.org/?probe=43602a664e) | Dec 17, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [dde306e444](https://linux-hardware.org/?probe=dde306e444) | Dec 17, 2023 |
| ASUSTek       | X456UB                      | Notebook    | [5a4a0662e1](https://linux-hardware.org/?probe=5a4a0662e1) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [f46b47b272](https://linux-hardware.org/?probe=f46b47b272) | Dec 16, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [dc5e6d8ad5](https://linux-hardware.org/?probe=dc5e6d8ad5) | Dec 16, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [20a11e4c01](https://linux-hardware.org/?probe=20a11e4c01) | Dec 15, 2023 |
| ASUSTek       | P5E WS Pro                  | Desktop     | [9c68d265b1](https://linux-hardware.org/?probe=9c68d265b1) | Dec 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8d9963d61d](https://linux-hardware.org/?probe=8d9963d61d) | Dec 11, 2023 |
| Dell          | Latitude 5400               | Notebook    | [6e887e1547](https://linux-hardware.org/?probe=6e887e1547) | Dec 11, 2023 |
| MSI           | MS-AA811 100                | All in one  | [ce3691f366](https://linux-hardware.org/?probe=ce3691f366) | Dec 08, 2023 |
| MSI           | Katana 17 B13VGK            | Notebook    | [e91a23fa88](https://linux-hardware.org/?probe=e91a23fa88) | Dec 08, 2023 |
| Dell          | Latitude E7470              | Notebook    | [81a17083f6](https://linux-hardware.org/?probe=81a17083f6) | Dec 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e0f14fb199](https://linux-hardware.org/?probe=e0f14fb199) | Dec 07, 2023 |
| Google        | Chell                       | Notebook    | [b19b6452e3](https://linux-hardware.org/?probe=b19b6452e3) | Dec 07, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bd9d40cd17](https://linux-hardware.org/?probe=bd9d40cd17) | Dec 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6aaaa355d3](https://linux-hardware.org/?probe=6aaaa355d3) | Dec 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [21c49766ca](https://linux-hardware.org/?probe=21c49766ca) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bed4fa69c4](https://linux-hardware.org/?probe=bed4fa69c4) | Dec 06, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [52cdd2c7b2](https://linux-hardware.org/?probe=52cdd2c7b2) | Dec 06, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [12c6da7b14](https://linux-hardware.org/?probe=12c6da7b14) | Dec 05, 2023 |
| LG Electro... | 16Z90R-G.AA76G              | Notebook    | [5ac1d1605a](https://linux-hardware.org/?probe=5ac1d1605a) | Dec 05, 2023 |
| HP            | 1497                        | Desktop     | [d6ef1fa27d](https://linux-hardware.org/?probe=d6ef1fa27d) | Dec 04, 2023 |
| Huanan        | X99-F8D PLUS V1.3           | Desktop     | [848f3c01c3](https://linux-hardware.org/?probe=848f3c01c3) | Dec 03, 2023 |
| ONDA          | H81M                        | Desktop     | [76c44af7fc](https://linux-hardware.org/?probe=76c44af7fc) | Dec 02, 2023 |
| HP            | 82B4                        | Desktop     | [fae1e016be](https://linux-hardware.org/?probe=fae1e016be) | Dec 02, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [9560de18b6](https://linux-hardware.org/?probe=9560de18b6) | Dec 01, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [55c38cfaa9](https://linux-hardware.org/?probe=55c38cfaa9) | Dec 01, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8b41445765](https://linux-hardware.org/?probe=8b41445765) | Nov 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [cfeac0b40f](https://linux-hardware.org/?probe=cfeac0b40f) | Nov 30, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [e9f95fd344](https://linux-hardware.org/?probe=e9f95fd344) | Nov 29, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [44dd5b984b](https://linux-hardware.org/?probe=44dd5b984b) | Nov 28, 2023 |
| MSI           | Z97 PC Mate                 | Desktop     | [3bc66597b8](https://linux-hardware.org/?probe=3bc66597b8) | Nov 27, 2023 |
| Biostar       | A78MD                       | Desktop     | [c7e8dd6939](https://linux-hardware.org/?probe=c7e8dd6939) | Nov 27, 2023 |
| Lenovo        | ThinkPad X201 3323RKG       | Notebook    | [71242a9bc0](https://linux-hardware.org/?probe=71242a9bc0) | Nov 26, 2023 |
| HP            | ENVY 15                     | Notebook    | [66a7391daf](https://linux-hardware.org/?probe=66a7391daf) | Nov 25, 2023 |
| Acer          | TravelMate P215-51          | Notebook    | [fd03901ed8](https://linux-hardware.org/?probe=fd03901ed8) | Nov 25, 2023 |
| FUTOPIA GL... | ULTIMUS PRO                 | Notebook    | [96b6b163d8](https://linux-hardware.org/?probe=96b6b163d8) | Nov 24, 2023 |
| HP            | 340S G7 Notebook PC         | Notebook    | [5f8d3105b5](https://linux-hardware.org/?probe=5f8d3105b5) | Nov 22, 2023 |
| HP            | 1825                        | Desktop     | [78c3833b1a](https://linux-hardware.org/?probe=78c3833b1a) | Nov 21, 2023 |
| Dell          | Latitude 5400               | Notebook    | [a2994234ca](https://linux-hardware.org/?probe=a2994234ca) | Nov 21, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [00a6933cf0](https://linux-hardware.org/?probe=00a6933cf0) | Nov 20, 2023 |
| Dell          | Latitude E5500              | Notebook    | [657426e5e9](https://linux-hardware.org/?probe=657426e5e9) | Nov 20, 2023 |
| eMachines     | EL1360G                     | Desktop     | [5b2ab65e0a](https://linux-hardware.org/?probe=5b2ab65e0a) | Nov 20, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [d0f4cc3a98](https://linux-hardware.org/?probe=d0f4cc3a98) | Nov 19, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bab0d77625](https://linux-hardware.org/?probe=bab0d77625) | Nov 19, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [c11c5d127d](https://linux-hardware.org/?probe=c11c5d127d) | Nov 18, 2023 |
| Notebook      | W54_55SU1,SUW               | Notebook    | [12a0c7cc59](https://linux-hardware.org/?probe=12a0c7cc59) | Nov 18, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [28440e547a](https://linux-hardware.org/?probe=28440e547a) | Nov 18, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [eeda9a88f3](https://linux-hardware.org/?probe=eeda9a88f3) | Nov 18, 2023 |
| ONDA          | H61V Ver:4.01               | Desktop     | [9686807789](https://linux-hardware.org/?probe=9686807789) | Nov 18, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9e5738b77f](https://linux-hardware.org/?probe=9e5738b77f) | Nov 18, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [093edd002d](https://linux-hardware.org/?probe=093edd002d) | Nov 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [70ca4894ab](https://linux-hardware.org/?probe=70ca4894ab) | Nov 18, 2023 |
| Lenovo        | ThinkPad T420 4180ED3       | Notebook    | [f963bd64fa](https://linux-hardware.org/?probe=f963bd64fa) | Nov 16, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [ab7968d6da](https://linux-hardware.org/?probe=ab7968d6da) | Nov 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [95f01d6e47](https://linux-hardware.org/?probe=95f01d6e47) | Nov 15, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [d702c8d829](https://linux-hardware.org/?probe=d702c8d829) | Nov 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [09ef1df759](https://linux-hardware.org/?probe=09ef1df759) | Nov 14, 2023 |
| HP            | ENVY dv6                    | Notebook    | [f86a52da6d](https://linux-hardware.org/?probe=f86a52da6d) | Nov 14, 2023 |
| Dell          | Latitude E5500              | Notebook    | [f6a14cca8f](https://linux-hardware.org/?probe=f6a14cca8f) | Nov 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [46cfd3f6bf](https://linux-hardware.org/?probe=46cfd3f6bf) | Nov 13, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [46e69016d1](https://linux-hardware.org/?probe=46e69016d1) | Nov 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [8e86232d90](https://linux-hardware.org/?probe=8e86232d90) | Nov 11, 2023 |
| Gigabyte      | H610M H V2 DDR4             | Desktop     | [bafab6bf21](https://linux-hardware.org/?probe=bafab6bf21) | Nov 10, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2788382d20](https://linux-hardware.org/?probe=2788382d20) | Nov 10, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [a6a53a60f0](https://linux-hardware.org/?probe=a6a53a60f0) | Nov 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [33e3267f6a](https://linux-hardware.org/?probe=33e3267f6a) | Nov 10, 2023 |
| Dell          | Latitude 13                 | Notebook    | [4999e3eba9](https://linux-hardware.org/?probe=4999e3eba9) | Nov 09, 2023 |
| Lenovo        | ThinkCentre M58e 7514A2U    | Desktop     | [59554fada7](https://linux-hardware.org/?probe=59554fada7) | Nov 09, 2023 |
| Dell          | Latitude 13                 | Notebook    | [acb0bd4f9d](https://linux-hardware.org/?probe=acb0bd4f9d) | Nov 09, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d566deea22](https://linux-hardware.org/?probe=d566deea22) | Nov 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f8b6335bea](https://linux-hardware.org/?probe=f8b6335bea) | Nov 08, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5a6cfb8bce](https://linux-hardware.org/?probe=5a6cfb8bce) | Nov 07, 2023 |
| HP            | 2AF3                        | Desktop     | [19333e743d](https://linux-hardware.org/?probe=19333e743d) | Nov 07, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [c98cdea69b](https://linux-hardware.org/?probe=c98cdea69b) | Nov 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bcd7a71a14](https://linux-hardware.org/?probe=bcd7a71a14) | Nov 06, 2023 |
| HP            | 8594                        | Desktop     | [d51c507511](https://linux-hardware.org/?probe=d51c507511) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [9655bf2db1](https://linux-hardware.org/?probe=9655bf2db1) | Nov 06, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [ce6a053669](https://linux-hardware.org/?probe=ce6a053669) | Nov 06, 2023 |
| HP            | Pavilion 17                 | Notebook    | [50a9cf65b3](https://linux-hardware.org/?probe=50a9cf65b3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | Notebook    | [56d9dc4a36](https://linux-hardware.org/?probe=56d9dc4a36) | Nov 05, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [257e40f6bd](https://linux-hardware.org/?probe=257e40f6bd) | Nov 05, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [fac63c4d5c](https://linux-hardware.org/?probe=fac63c4d5c) | Nov 05, 2023 |
| ASRockRack    | EPC602D8A                   | Desktop     | [c1b6c06dc5](https://linux-hardware.org/?probe=c1b6c06dc5) | Nov 05, 2023 |
| Sony          | SVE15137CGW                 | Notebook    | [5d2a4746af](https://linux-hardware.org/?probe=5d2a4746af) | Nov 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [3d8056e30e](https://linux-hardware.org/?probe=3d8056e30e) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [546178d07d](https://linux-hardware.org/?probe=546178d07d) | Nov 04, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [f029848e7d](https://linux-hardware.org/?probe=f029848e7d) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [abe3da8a30](https://linux-hardware.org/?probe=abe3da8a30) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7ccaf83d7](https://linux-hardware.org/?probe=e7ccaf83d7) | Nov 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [baf30122ca](https://linux-hardware.org/?probe=baf30122ca) | Nov 03, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [387194bdf6](https://linux-hardware.org/?probe=387194bdf6) | Nov 03, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [157f3bd86a](https://linux-hardware.org/?probe=157f3bd86a) | Nov 03, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [48103e7e91](https://linux-hardware.org/?probe=48103e7e91) | Nov 03, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [328a40f6fe](https://linux-hardware.org/?probe=328a40f6fe) | Nov 03, 2023 |
| HP            | 0AECh D                     | Desktop     | [2ddad2bbf2](https://linux-hardware.org/?probe=2ddad2bbf2) | Nov 03, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [e972336105](https://linux-hardware.org/?probe=e972336105) | Nov 03, 2023 |
| Dell          | Vostro 5590                 | Notebook    | [aa355fcc89](https://linux-hardware.org/?probe=aa355fcc89) | Nov 02, 2023 |
| Chuwi         | CoreBook Pro                | Notebook    | [ac0f4a1ea9](https://linux-hardware.org/?probe=ac0f4a1ea9) | Nov 01, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [d3d4d3dea3](https://linux-hardware.org/?probe=d3d4d3dea3) | Nov 01, 2023 |
| MSI           | Titan GT77HX 13VI           | Notebook    | [1fb8b0ccb3](https://linux-hardware.org/?probe=1fb8b0ccb3) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f557533925](https://linux-hardware.org/?probe=f557533925) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [50880de513](https://linux-hardware.org/?probe=50880de513) | Nov 01, 2023 |
| Lenovo        | 3647 SDK0J40709 WIN 3259... | All in one  | [4f99b79f9e](https://linux-hardware.org/?probe=4f99b79f9e) | Nov 01, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [69d243d2db](https://linux-hardware.org/?probe=69d243d2db) | Nov 01, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [9eed6b298a](https://linux-hardware.org/?probe=9eed6b298a) | Oct 31, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [01ba7dff2f](https://linux-hardware.org/?probe=01ba7dff2f) | Oct 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [18398fe53c](https://linux-hardware.org/?probe=18398fe53c) | Oct 31, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [f1d5844389](https://linux-hardware.org/?probe=f1d5844389) | Oct 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [4aa5e757eb](https://linux-hardware.org/?probe=4aa5e757eb) | Oct 31, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [e5a9bbe278](https://linux-hardware.org/?probe=e5a9bbe278) | Oct 31, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [55f20f6750](https://linux-hardware.org/?probe=55f20f6750) | Oct 31, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [90fc87e07a](https://linux-hardware.org/?probe=90fc87e07a) | Oct 31, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [5d99367248](https://linux-hardware.org/?probe=5d99367248) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [32d642cc3b](https://linux-hardware.org/?probe=32d642cc3b) | Oct 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [309695dc7e](https://linux-hardware.org/?probe=309695dc7e) | Oct 30, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [173639f83c](https://linux-hardware.org/?probe=173639f83c) | Oct 30, 2023 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [49eeb546b4](https://linux-hardware.org/?probe=49eeb546b4) | Oct 30, 2023 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [9b470b594c](https://linux-hardware.org/?probe=9b470b594c) | Oct 30, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [2310075f2d](https://linux-hardware.org/?probe=2310075f2d) | Oct 30, 2023 |
| Dell          | Latitude 5400               | Notebook    | [e7f91d1c69](https://linux-hardware.org/?probe=e7f91d1c69) | Oct 30, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d8590bb026](https://linux-hardware.org/?probe=d8590bb026) | Oct 30, 2023 |
| Intel         | H61                         | Desktop     | [0f282da58e](https://linux-hardware.org/?probe=0f282da58e) | Oct 30, 2023 |
| HP            | ProBook 6570b               | Notebook    | [5b574791fa](https://linux-hardware.org/?probe=5b574791fa) | Oct 30, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | Notebook    | [8df2c91111](https://linux-hardware.org/?probe=8df2c91111) | Oct 29, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [bda6b9ff10](https://linux-hardware.org/?probe=bda6b9ff10) | Oct 29, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | Notebook    | [c410852108](https://linux-hardware.org/?probe=c410852108) | Oct 29, 2023 |
| Dell          | Latitude E5450              | Notebook    | [64e3601d4c](https://linux-hardware.org/?probe=64e3601d4c) | Oct 29, 2023 |
| Lenovo        | ThinkPad T450s 20BWS58K0... | Notebook    | [11b2f76301](https://linux-hardware.org/?probe=11b2f76301) | Oct 29, 2023 |
| Dell          | Latitude E5450              | Notebook    | [aebf2cd9fb](https://linux-hardware.org/?probe=aebf2cd9fb) | Oct 29, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [7f556dd124](https://linux-hardware.org/?probe=7f556dd124) | Oct 28, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [7c4b363241](https://linux-hardware.org/?probe=7c4b363241) | Oct 28, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [9659254017](https://linux-hardware.org/?probe=9659254017) | Oct 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [773814f03f](https://linux-hardware.org/?probe=773814f03f) | Oct 27, 2023 |
| ASRock        | Z790 PG SONIC               | Desktop     | [3d8af896cc](https://linux-hardware.org/?probe=3d8af896cc) | Oct 27, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [d4b3f62ecb](https://linux-hardware.org/?probe=d4b3f62ecb) | Oct 27, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [44b772393d](https://linux-hardware.org/?probe=44b772393d) | Oct 27, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [9444fd16a7](https://linux-hardware.org/?probe=9444fd16a7) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [b6925d5638](https://linux-hardware.org/?probe=b6925d5638) | Oct 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4b51bd3321](https://linux-hardware.org/?probe=4b51bd3321) | Oct 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA            | Notebook    | [f321493adb](https://linux-hardware.org/?probe=f321493adb) | Oct 25, 2023 |
| GEEKOM        | A5                          | Desktop     | [2a6fe744c1](https://linux-hardware.org/?probe=2a6fe744c1) | Oct 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fc849b0e23](https://linux-hardware.org/?probe=fc849b0e23) | Oct 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [3a0c166a2f](https://linux-hardware.org/?probe=3a0c166a2f) | Oct 25, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [74e623d263](https://linux-hardware.org/?probe=74e623d263) | Oct 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [3ce0f8310d](https://linux-hardware.org/?probe=3ce0f8310d) | Oct 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e622e81e16](https://linux-hardware.org/?probe=e622e81e16) | Oct 24, 2023 |
| Dell          | Latitude E7270              | Notebook    | [07d72d2a9d](https://linux-hardware.org/?probe=07d72d2a9d) | Oct 24, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [9664d44f1e](https://linux-hardware.org/?probe=9664d44f1e) | Oct 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [a5c5c4cd3d](https://linux-hardware.org/?probe=a5c5c4cd3d) | Oct 24, 2023 |
| HP            | 339A                        | Desktop     | [2e0eb78de2](https://linux-hardware.org/?probe=2e0eb78de2) | Oct 24, 2023 |
| Lenovo        | ThinkPad T480 20L6S5FF0S    | Notebook    | [4a4fe99b2d](https://linux-hardware.org/?probe=4a4fe99b2d) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f45a5143fc](https://linux-hardware.org/?probe=f45a5143fc) | Oct 23, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [6f746b3af3](https://linux-hardware.org/?probe=6f746b3af3) | Oct 23, 2023 |
| Intel Clie... | LAPAC71H                    | Notebook    | [257d890bfb](https://linux-hardware.org/?probe=257d890bfb) | Oct 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [17e7fcc400](https://linux-hardware.org/?probe=17e7fcc400) | Oct 23, 2023 |
| Dell          | 0VD5HY A07                  | Desktop     | [5e68194dd0](https://linux-hardware.org/?probe=5e68194dd0) | Oct 23, 2023 |
| HP            | Pavilion 17                 | Notebook    | [7e822923ca](https://linux-hardware.org/?probe=7e822923ca) | Oct 23, 2023 |
| HP            | 18E7                        | Desktop     | [eec2c6a2fd](https://linux-hardware.org/?probe=eec2c6a2fd) | Oct 23, 2023 |
| MSI           | X58 Pro SLI                 | Desktop     | [e127c69a3f](https://linux-hardware.org/?probe=e127c69a3f) | Oct 23, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [04dd8d9baf](https://linux-hardware.org/?probe=04dd8d9baf) | Oct 23, 2023 |
| GPU Compan... | GWTC116-2                   | Convertible | [8daced51b5](https://linux-hardware.org/?probe=8daced51b5) | Oct 22, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [bbe3093cb4](https://linux-hardware.org/?probe=bbe3093cb4) | Oct 22, 2023 |
| HP            | 18E7                        | Desktop     | [18f7dbf492](https://linux-hardware.org/?probe=18f7dbf492) | Oct 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60926fccde](https://linux-hardware.org/?probe=60926fccde) | Oct 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6ef86fc1b9](https://linux-hardware.org/?probe=6ef86fc1b9) | Oct 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | Notebook    | [735bb309a1](https://linux-hardware.org/?probe=735bb309a1) | Oct 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [9dae3fabcb](https://linux-hardware.org/?probe=9dae3fabcb) | Oct 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [38fcbd8bc7](https://linux-hardware.org/?probe=38fcbd8bc7) | Oct 21, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8ceed23497](https://linux-hardware.org/?probe=8ceed23497) | Oct 21, 2023 |
| Dell          | Latitude 7420               | Notebook    | [33e4aebc37](https://linux-hardware.org/?probe=33e4aebc37) | Oct 21, 2023 |
| Gigabyte      | B85M-D2V                    | Desktop     | [f7b3792e3e](https://linux-hardware.org/?probe=f7b3792e3e) | Oct 21, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [336cca4c8b](https://linux-hardware.org/?probe=336cca4c8b) | Oct 21, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [2aea2077db](https://linux-hardware.org/?probe=2aea2077db) | Oct 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [2f7b2cf78e](https://linux-hardware.org/?probe=2f7b2cf78e) | Oct 20, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [d3036ca319](https://linux-hardware.org/?probe=d3036ca319) | Oct 20, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [1b518a8409](https://linux-hardware.org/?probe=1b518a8409) | Oct 20, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ed9af05f78](https://linux-hardware.org/?probe=ed9af05f78) | Oct 20, 2023 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [73592fa9fb](https://linux-hardware.org/?probe=73592fa9fb) | Oct 20, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e07bf20a8a](https://linux-hardware.org/?probe=e07bf20a8a) | Oct 20, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [4f6fad364d](https://linux-hardware.org/?probe=4f6fad364d) | Oct 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b7e0b6aac3](https://linux-hardware.org/?probe=b7e0b6aac3) | Oct 19, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ca05cc8c35](https://linux-hardware.org/?probe=ca05cc8c35) | Oct 19, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [eb391611f3](https://linux-hardware.org/?probe=eb391611f3) | Oct 19, 2023 |
| ASRock        | Z370 Taichi                 | Desktop     | [ca57155c40](https://linux-hardware.org/?probe=ca57155c40) | Oct 19, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [8d58200a98](https://linux-hardware.org/?probe=8d58200a98) | Oct 19, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [0815767d1d](https://linux-hardware.org/?probe=0815767d1d) | Oct 18, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [728b29b59d](https://linux-hardware.org/?probe=728b29b59d) | Oct 18, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [df408e2203](https://linux-hardware.org/?probe=df408e2203) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [417e10e47c](https://linux-hardware.org/?probe=417e10e47c) | Oct 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [686e5c87a9](https://linux-hardware.org/?probe=686e5c87a9) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b28a7b8c25](https://linux-hardware.org/?probe=b28a7b8c25) | Oct 17, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [da4ea80916](https://linux-hardware.org/?probe=da4ea80916) | Oct 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [96f3c530df](https://linux-hardware.org/?probe=96f3c530df) | Oct 17, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [3bdd0db02e](https://linux-hardware.org/?probe=3bdd0db02e) | Oct 17, 2023 |
| Gigabyte      | H110M-D2P-WG-CF             | Desktop     | [113b3d362d](https://linux-hardware.org/?probe=113b3d362d) | Oct 17, 2023 |
| Google        | Bobba                       | Notebook    | [f8cdd51f65](https://linux-hardware.org/?probe=f8cdd51f65) | Oct 17, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [58e17c747d](https://linux-hardware.org/?probe=58e17c747d) | Oct 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [3597183b2f](https://linux-hardware.org/?probe=3597183b2f) | Oct 17, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [fcd9389f36](https://linux-hardware.org/?probe=fcd9389f36) | Oct 17, 2023 |
| Lenovo        | ThinkPad T590 20N5S56P00    | Notebook    | [913c616ff6](https://linux-hardware.org/?probe=913c616ff6) | Oct 17, 2023 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [abfbdc1640](https://linux-hardware.org/?probe=abfbdc1640) | Oct 17, 2023 |
| Gigabyte      | AORUS 15G XB                | Notebook    | [9e4c6d48d4](https://linux-hardware.org/?probe=9e4c6d48d4) | Oct 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [07b407d18a](https://linux-hardware.org/?probe=07b407d18a) | Oct 16, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [52a3f75a39](https://linux-hardware.org/?probe=52a3f75a39) | Oct 16, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [8f5d44a983](https://linux-hardware.org/?probe=8f5d44a983) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [cb6f45e005](https://linux-hardware.org/?probe=cb6f45e005) | Oct 16, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3120810bcd](https://linux-hardware.org/?probe=3120810bcd) | Oct 15, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [3a8e72ab3b](https://linux-hardware.org/?probe=3a8e72ab3b) | Oct 15, 2023 |
| Trigkey       | S5 V2.0                     | Mini pc     | [5639ebab82](https://linux-hardware.org/?probe=5639ebab82) | Oct 15, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [1f718e54bf](https://linux-hardware.org/?probe=1f718e54bf) | Oct 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [079342de2b](https://linux-hardware.org/?probe=079342de2b) | Oct 15, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [6c14bb7f6c](https://linux-hardware.org/?probe=6c14bb7f6c) | Oct 15, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [cfc646c366](https://linux-hardware.org/?probe=cfc646c366) | Oct 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [70c2a81f9f](https://linux-hardware.org/?probe=70c2a81f9f) | Oct 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [d83bb1e709](https://linux-hardware.org/?probe=d83bb1e709) | Oct 14, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [10b572c94a](https://linux-hardware.org/?probe=10b572c94a) | Oct 14, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [1d1e26c1fe](https://linux-hardware.org/?probe=1d1e26c1fe) | Oct 14, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [a4ed11bb84](https://linux-hardware.org/?probe=a4ed11bb84) | Oct 14, 2023 |
| Dell          | 0K3CM7 A00                  | Desktop     | [35d569ea79](https://linux-hardware.org/?probe=35d569ea79) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [dd056a62d3](https://linux-hardware.org/?probe=dd056a62d3) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [584433cc95](https://linux-hardware.org/?probe=584433cc95) | Oct 14, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [d634013b16](https://linux-hardware.org/?probe=d634013b16) | Oct 13, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [d9361064fd](https://linux-hardware.org/?probe=d9361064fd) | Oct 13, 2023 |
| ASRockRack    | EPC602D8A                   | Desktop     | [a47c7098c0](https://linux-hardware.org/?probe=a47c7098c0) | Oct 13, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [53c0055ced](https://linux-hardware.org/?probe=53c0055ced) | Oct 13, 2023 |
| Lenovo        | 15ARE05 81W4                | Notebook    | [c0066cda83](https://linux-hardware.org/?probe=c0066cda83) | Oct 13, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [95b2484948](https://linux-hardware.org/?probe=95b2484948) | Oct 13, 2023 |
| Panasonic     | CF-C1AD06GDE                | Notebook    | [473265139b](https://linux-hardware.org/?probe=473265139b) | Oct 13, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [e66e176aac](https://linux-hardware.org/?probe=e66e176aac) | Oct 13, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [ab55bb1001](https://linux-hardware.org/?probe=ab55bb1001) | Oct 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [7901d1df27](https://linux-hardware.org/?probe=7901d1df27) | Oct 12, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [1e08b73cc3](https://linux-hardware.org/?probe=1e08b73cc3) | Oct 12, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [2869814e7d](https://linux-hardware.org/?probe=2869814e7d) | Oct 12, 2023 |
| HP            | 89E8 0100                   | All in one  | [d77da738f7](https://linux-hardware.org/?probe=d77da738f7) | Oct 12, 2023 |
| HP            | 2B5E                        | Desktop     | [9dff375d05](https://linux-hardware.org/?probe=9dff375d05) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8368fe3d29](https://linux-hardware.org/?probe=8368fe3d29) | Oct 12, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [a549a213f1](https://linux-hardware.org/?probe=a549a213f1) | Oct 12, 2023 |
| Acer          | Swift SF315-41              | Notebook    | [804f28fe5b](https://linux-hardware.org/?probe=804f28fe5b) | Oct 12, 2023 |
| HP            | 805D                        | Desktop     | [8fb0d8213e](https://linux-hardware.org/?probe=8fb0d8213e) | Oct 12, 2023 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [9ca6bc0b08](https://linux-hardware.org/?probe=9ca6bc0b08) | Oct 11, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [77ff5b185a](https://linux-hardware.org/?probe=77ff5b185a) | Oct 11, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [4bb651a7a6](https://linux-hardware.org/?probe=4bb651a7a6) | Oct 11, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [c83831e304](https://linux-hardware.org/?probe=c83831e304) | Oct 11, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [52bbb0243a](https://linux-hardware.org/?probe=52bbb0243a) | Oct 11, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [cca48ceee9](https://linux-hardware.org/?probe=cca48ceee9) | Oct 11, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [83ed978b53](https://linux-hardware.org/?probe=83ed978b53) | Oct 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [cc8161a063](https://linux-hardware.org/?probe=cc8161a063) | Oct 11, 2023 |
| HP            | 18E7                        | Desktop     | [fd71ca186e](https://linux-hardware.org/?probe=fd71ca186e) | Oct 11, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [22df79ec5d](https://linux-hardware.org/?probe=22df79ec5d) | Oct 11, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [c95c8a8a2e](https://linux-hardware.org/?probe=c95c8a8a2e) | Oct 11, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [b31403a384](https://linux-hardware.org/?probe=b31403a384) | Oct 11, 2023 |
| Intel         | H61 V1.5                    | Desktop     | [ed796dbba7](https://linux-hardware.org/?probe=ed796dbba7) | Oct 11, 2023 |
| Quanta        | 2ABB 101                    | Desktop     | [1ae3a7098e](https://linux-hardware.org/?probe=1ae3a7098e) | Oct 11, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [2ed8ec821a](https://linux-hardware.org/?probe=2ed8ec821a) | Oct 10, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [875dd4eedb](https://linux-hardware.org/?probe=875dd4eedb) | Oct 10, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [9799f9f959](https://linux-hardware.org/?probe=9799f9f959) | Oct 10, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [fed7f26361](https://linux-hardware.org/?probe=fed7f26361) | Oct 10, 2023 |
| MSI           | MS-7125                     | Desktop     | [2e6837be6d](https://linux-hardware.org/?probe=2e6837be6d) | Oct 10, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9e03b4745f](https://linux-hardware.org/?probe=9e03b4745f) | Oct 10, 2023 |
| MSI           | MS-7380                     | Desktop     | [b2c3a106ca](https://linux-hardware.org/?probe=b2c3a106ca) | Oct 10, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5b710d03c5](https://linux-hardware.org/?probe=5b710d03c5) | Oct 09, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [5513cf503c](https://linux-hardware.org/?probe=5513cf503c) | Oct 09, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [2fc37ab8c6](https://linux-hardware.org/?probe=2fc37ab8c6) | Oct 09, 2023 |
| ASUSTek       | PRIME B365M-K               | Desktop     | [e5e897e96a](https://linux-hardware.org/?probe=e5e897e96a) | Oct 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [d6b0808093](https://linux-hardware.org/?probe=d6b0808093) | Oct 09, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [29af84698a](https://linux-hardware.org/?probe=29af84698a) | Oct 09, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [38a83d68e5](https://linux-hardware.org/?probe=38a83d68e5) | Oct 09, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [fd663ca7fa](https://linux-hardware.org/?probe=fd663ca7fa) | Oct 09, 2023 |
| HP            | 845A                        | Desktop     | [b3bd3f3036](https://linux-hardware.org/?probe=b3bd3f3036) | Oct 09, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [98784d1e51](https://linux-hardware.org/?probe=98784d1e51) | Oct 08, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [b197f3a0b2](https://linux-hardware.org/?probe=b197f3a0b2) | Oct 08, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 3 ... | Convertible | [b3f3a17f8c](https://linux-hardware.org/?probe=b3f3a17f8c) | Oct 08, 2023 |
| HP            | EliteBook 745 G4            | Notebook    | [8a9290f8a1](https://linux-hardware.org/?probe=8a9290f8a1) | Oct 08, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [69383bf7da](https://linux-hardware.org/?probe=69383bf7da) | Oct 08, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [d8cf994cfe](https://linux-hardware.org/?probe=d8cf994cfe) | Oct 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [dae43772d4](https://linux-hardware.org/?probe=dae43772d4) | Oct 08, 2023 |
| PC Special... | P65_P67RGRERA               | Notebook    | [c2779bc01c](https://linux-hardware.org/?probe=c2779bc01c) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [0d2d2cf2ae](https://linux-hardware.org/?probe=0d2d2cf2ae) | Oct 08, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [a95183052c](https://linux-hardware.org/?probe=a95183052c) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [a07ec0ee55](https://linux-hardware.org/?probe=a07ec0ee55) | Oct 08, 2023 |
| Lenovo        | ThinkPad T420s 4171CTO      | Notebook    | [334da57291](https://linux-hardware.org/?probe=334da57291) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [1a179deb84](https://linux-hardware.org/?probe=1a179deb84) | Oct 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [687287904f](https://linux-hardware.org/?probe=687287904f) | Oct 08, 2023 |
| HP            | 14                          | Notebook    | [3d65da2b45](https://linux-hardware.org/?probe=3d65da2b45) | Oct 08, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [3d7751b41e](https://linux-hardware.org/?probe=3d7751b41e) | Oct 08, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [8ea6db3dbb](https://linux-hardware.org/?probe=8ea6db3dbb) | Oct 08, 2023 |
| GIADA         | Braswell JHS60S             | Desktop     | [ed113a0bc0](https://linux-hardware.org/?probe=ed113a0bc0) | Oct 08, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [5e51e3dabc](https://linux-hardware.org/?probe=5e51e3dabc) | Oct 08, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [93e4a63cfa](https://linux-hardware.org/?probe=93e4a63cfa) | Oct 08, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4ab4a75cc2](https://linux-hardware.org/?probe=4ab4a75cc2) | Oct 08, 2023 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [7b7ac9e326](https://linux-hardware.org/?probe=7b7ac9e326) | Oct 07, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [9f94f8934f](https://linux-hardware.org/?probe=9f94f8934f) | Oct 07, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5324f47bcf](https://linux-hardware.org/?probe=5324f47bcf) | Oct 07, 2023 |
| HP            | ENVY 15                     | Notebook    | [082502c7d2](https://linux-hardware.org/?probe=082502c7d2) | Oct 07, 2023 |
| Acer          | Swift SF313-52G             | Notebook    | [754ae78e39](https://linux-hardware.org/?probe=754ae78e39) | Oct 07, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [59c96d1008](https://linux-hardware.org/?probe=59c96d1008) | Oct 07, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [00fa623097](https://linux-hardware.org/?probe=00fa623097) | Oct 07, 2023 |
| HP            | 18E7                        | Desktop     | [4d548e9668](https://linux-hardware.org/?probe=4d548e9668) | Oct 06, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0a4d13a8f8](https://linux-hardware.org/?probe=0a4d13a8f8) | Oct 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [fbd07d95c2](https://linux-hardware.org/?probe=fbd07d95c2) | Oct 06, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [634ca46a18](https://linux-hardware.org/?probe=634ca46a18) | Oct 06, 2023 |
| Lenovo        | ThinkPad T460 20FN003HUK    | Notebook    | [fd35988069](https://linux-hardware.org/?probe=fd35988069) | Oct 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [21d197e617](https://linux-hardware.org/?probe=21d197e617) | Oct 05, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ddadccf492](https://linux-hardware.org/?probe=ddadccf492) | Oct 05, 2023 |
| Dell          | Latitude 3420               | Notebook    | [c5a2d75e6c](https://linux-hardware.org/?probe=c5a2d75e6c) | Oct 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [3b55566de3](https://linux-hardware.org/?probe=3b55566de3) | Oct 05, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [6a56e8a819](https://linux-hardware.org/?probe=6a56e8a819) | Oct 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [25826e46a6](https://linux-hardware.org/?probe=25826e46a6) | Oct 05, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [a2af980b4f](https://linux-hardware.org/?probe=a2af980b4f) | Oct 04, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [529f4a7005](https://linux-hardware.org/?probe=529f4a7005) | Oct 04, 2023 |
| Intel         | X79M-S                      | Desktop     | [a62dc4f931](https://linux-hardware.org/?probe=a62dc4f931) | Oct 04, 2023 |
| SHANGZHAOY... | H97M-PRO V1.0               | Desktop     | [0056cb50c2](https://linux-hardware.org/?probe=0056cb50c2) | Oct 04, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [9dc3e0f9f9](https://linux-hardware.org/?probe=9dc3e0f9f9) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [e590e7eb2c](https://linux-hardware.org/?probe=e590e7eb2c) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [bdfa072267](https://linux-hardware.org/?probe=bdfa072267) | Oct 04, 2023 |
| Google        | Fleex                       | Notebook    | [534bbe966a](https://linux-hardware.org/?probe=534bbe966a) | Oct 04, 2023 |
| Dell          | 0J051K A01                  | Server      | [d3dfb8b571](https://linux-hardware.org/?probe=d3dfb8b571) | Oct 04, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [49b19b9f02](https://linux-hardware.org/?probe=49b19b9f02) | Oct 03, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [f93ae6a15c](https://linux-hardware.org/?probe=f93ae6a15c) | Oct 03, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [eebbbc30b8](https://linux-hardware.org/?probe=eebbbc30b8) | Oct 03, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [f332024d38](https://linux-hardware.org/?probe=f332024d38) | Oct 03, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eb2d379320](https://linux-hardware.org/?probe=eb2d379320) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [98961e6b78](https://linux-hardware.org/?probe=98961e6b78) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [332fe81da5](https://linux-hardware.org/?probe=332fe81da5) | Oct 03, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [b4dc684d6a](https://linux-hardware.org/?probe=b4dc684d6a) | Oct 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [ff7dc27288](https://linux-hardware.org/?probe=ff7dc27288) | Oct 03, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [251b560f75](https://linux-hardware.org/?probe=251b560f75) | Oct 03, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [45ec0b8337](https://linux-hardware.org/?probe=45ec0b8337) | Oct 03, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [27eac828a3](https://linux-hardware.org/?probe=27eac828a3) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [880b4780ee](https://linux-hardware.org/?probe=880b4780ee) | Oct 03, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [30ff6af03d](https://linux-hardware.org/?probe=30ff6af03d) | Oct 03, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [1959705750](https://linux-hardware.org/?probe=1959705750) | Oct 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [0df81159a2](https://linux-hardware.org/?probe=0df81159a2) | Oct 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [d4fcdc44c7](https://linux-hardware.org/?probe=d4fcdc44c7) | Oct 03, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [dff87c66a9](https://linux-hardware.org/?probe=dff87c66a9) | Oct 03, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d6298eb43](https://linux-hardware.org/?probe=9d6298eb43) | Oct 03, 2023 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [a30a4e0d2e](https://linux-hardware.org/?probe=a30a4e0d2e) | Oct 03, 2023 |
| ASUSTek       | Pro Q670M-C                 | Desktop     | [8bbc915322](https://linux-hardware.org/?probe=8bbc915322) | Oct 03, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [d7108a55e5](https://linux-hardware.org/?probe=d7108a55e5) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [06f658c722](https://linux-hardware.org/?probe=06f658c722) | Oct 02, 2023 |
| Dell          | Latitude E6410              | Notebook    | [4e19cdbfe7](https://linux-hardware.org/?probe=4e19cdbfe7) | Oct 02, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cf79594d59](https://linux-hardware.org/?probe=cf79594d59) | Oct 02, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [93abdf2d50](https://linux-hardware.org/?probe=93abdf2d50) | Oct 02, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cb7ac852c](https://linux-hardware.org/?probe=9cb7ac852c) | Oct 02, 2023 |
| Dell          | Latitude E6410              | Notebook    | [76cbbaf618](https://linux-hardware.org/?probe=76cbbaf618) | Oct 02, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [e261210eb7](https://linux-hardware.org/?probe=e261210eb7) | Oct 02, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [21e6d88bd9](https://linux-hardware.org/?probe=21e6d88bd9) | Oct 02, 2023 |
| Dell          | Precision 5530              | Notebook    | [3df6ff5560](https://linux-hardware.org/?probe=3df6ff5560) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [2b0868267b](https://linux-hardware.org/?probe=2b0868267b) | Oct 02, 2023 |
| Intel         | DP45SG AAE27733-404         | Desktop     | [d8e6101d6d](https://linux-hardware.org/?probe=d8e6101d6d) | Oct 02, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [be587ff5b8](https://linux-hardware.org/?probe=be587ff5b8) | Oct 02, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [4e0f7a8051](https://linux-hardware.org/?probe=4e0f7a8051) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [be49d6acd9](https://linux-hardware.org/?probe=be49d6acd9) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [0236b6af15](https://linux-hardware.org/?probe=0236b6af15) | Oct 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [975e318361](https://linux-hardware.org/?probe=975e318361) | Oct 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [a566eb0467](https://linux-hardware.org/?probe=a566eb0467) | Oct 01, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [8cb6a92a75](https://linux-hardware.org/?probe=8cb6a92a75) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [e26d66c131](https://linux-hardware.org/?probe=e26d66c131) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [21f405ccbe](https://linux-hardware.org/?probe=21f405ccbe) | Oct 01, 2023 |
| Intel         | NUC5i3RYB H41000-506        | Mini pc     | [d95636108b](https://linux-hardware.org/?probe=d95636108b) | Oct 01, 2023 |
| ASUSTek       | G73Jh                       | Notebook    | [0b9b84be03](https://linux-hardware.org/?probe=0b9b84be03) | Oct 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [ec90ed2076](https://linux-hardware.org/?probe=ec90ed2076) | Oct 01, 2023 |
| NZXT          | N7 B550                     | Desktop     | [53a99b69e6](https://linux-hardware.org/?probe=53a99b69e6) | Sep 30, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [da117a4e6a](https://linux-hardware.org/?probe=da117a4e6a) | Sep 30, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0b4432877e](https://linux-hardware.org/?probe=0b4432877e) | Sep 30, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [d39169bf21](https://linux-hardware.org/?probe=d39169bf21) | Sep 30, 2023 |
| ASUSTek       | CG8480                      | Desktop     | [dc174e8f73](https://linux-hardware.org/?probe=dc174e8f73) | Sep 30, 2023 |
| Lenovo        | ThinkCentre M58e 7514A2U    | Desktop     | [68f162bf42](https://linux-hardware.org/?probe=68f162bf42) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [770e7037d3](https://linux-hardware.org/?probe=770e7037d3) | Sep 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b3617a1e58](https://linux-hardware.org/?probe=b3617a1e58) | Sep 30, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [7b4a0099a9](https://linux-hardware.org/?probe=7b4a0099a9) | Sep 29, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [55ea55a771](https://linux-hardware.org/?probe=55ea55a771) | Sep 29, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [3e1448c388](https://linux-hardware.org/?probe=3e1448c388) | Sep 29, 2023 |
| GEEKOM        | Mini IT 8                   | Desktop     | [fc5d6092da](https://linux-hardware.org/?probe=fc5d6092da) | Sep 29, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [16dabb2f6e](https://linux-hardware.org/?probe=16dabb2f6e) | Sep 29, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0c29af254c](https://linux-hardware.org/?probe=0c29af254c) | Sep 29, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [6f19668c91](https://linux-hardware.org/?probe=6f19668c91) | Sep 29, 2023 |
| Lenovo        | 1031 SBB0J05441 WIN 3305... | Desktop     | [26580dc672](https://linux-hardware.org/?probe=26580dc672) | Sep 29, 2023 |
| HP            | 8923 00100                  | All in one  | [31d524cec8](https://linux-hardware.org/?probe=31d524cec8) | Sep 28, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [0005d20c0d](https://linux-hardware.org/?probe=0005d20c0d) | Sep 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [27d7959e57](https://linux-hardware.org/?probe=27d7959e57) | Sep 28, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [6def421696](https://linux-hardware.org/?probe=6def421696) | Sep 28, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [a70543ae67](https://linux-hardware.org/?probe=a70543ae67) | Sep 28, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e7fb14ee98](https://linux-hardware.org/?probe=e7fb14ee98) | Sep 28, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [f436f21240](https://linux-hardware.org/?probe=f436f21240) | Sep 27, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [6eefb5fdd2](https://linux-hardware.org/?probe=6eefb5fdd2) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [50c8df3b79](https://linux-hardware.org/?probe=50c8df3b79) | Sep 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [6cfd6e2b34](https://linux-hardware.org/?probe=6cfd6e2b34) | Sep 27, 2023 |
| HP            | 8594                        | Desktop     | [374067df48](https://linux-hardware.org/?probe=374067df48) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | Desktop     | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [72bb0c5858](https://linux-hardware.org/?probe=72bb0c5858) | Sep 27, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [af863ee3d6](https://linux-hardware.org/?probe=af863ee3d6) | Sep 27, 2023 |
| Intel         | X79F1 V2.0                  | Desktop     | [919b208284](https://linux-hardware.org/?probe=919b208284) | Sep 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c60600b4f0](https://linux-hardware.org/?probe=c60600b4f0) | Sep 27, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [812b06784e](https://linux-hardware.org/?probe=812b06784e) | Sep 27, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ded4cabd95](https://linux-hardware.org/?probe=ded4cabd95) | Sep 26, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [ab5af00a13](https://linux-hardware.org/?probe=ab5af00a13) | Sep 26, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [45b934b885](https://linux-hardware.org/?probe=45b934b885) | Sep 26, 2023 |
| Infinix       | INBOOK Y1 PLUS NEO          | Notebook    | [30998449af](https://linux-hardware.org/?probe=30998449af) | Sep 26, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b5951d8a34](https://linux-hardware.org/?probe=b5951d8a34) | Sep 26, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ee86e0d81e](https://linux-hardware.org/?probe=ee86e0d81e) | Sep 26, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [1630b56fe3](https://linux-hardware.org/?probe=1630b56fe3) | Sep 26, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [fc79d63b87](https://linux-hardware.org/?probe=fc79d63b87) | Sep 26, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf4e6d50dd](https://linux-hardware.org/?probe=cf4e6d50dd) | Sep 26, 2023 |
| HP            | G62                         | Notebook    | [50fef7b3fa](https://linux-hardware.org/?probe=50fef7b3fa) | Sep 26, 2023 |
| AZW           | GTR V01                     | Mini pc     | [07e408ce48](https://linux-hardware.org/?probe=07e408ce48) | Sep 25, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3e5c047af](https://linux-hardware.org/?probe=f3e5c047af) | Sep 25, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [285eb8a521](https://linux-hardware.org/?probe=285eb8a521) | Sep 25, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [ec5aecc69d](https://linux-hardware.org/?probe=ec5aecc69d) | Sep 25, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| ASUSTek       | M51AC                       | Desktop     | [b4bd7fad24](https://linux-hardware.org/?probe=b4bd7fad24) | Sep 25, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a1e01ab80d](https://linux-hardware.org/?probe=a1e01ab80d) | Sep 25, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [8895bccd1c](https://linux-hardware.org/?probe=8895bccd1c) | Sep 25, 2023 |
| Infinix       | INBOOK X1 SLIM              | Notebook    | [bd6f358c7f](https://linux-hardware.org/?probe=bd6f358c7f) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [38b5be59cc](https://linux-hardware.org/?probe=38b5be59cc) | Sep 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [2e717c304e](https://linux-hardware.org/?probe=2e717c304e) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS0EXOO    | Notebook    | [0818b5e737](https://linux-hardware.org/?probe=0818b5e737) | Sep 24, 2023 |
| HP            | 3047h                       | Desktop     | [03fd91188a](https://linux-hardware.org/?probe=03fd91188a) | Sep 24, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [25c109d366](https://linux-hardware.org/?probe=25c109d366) | Sep 24, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [5df1a942d9](https://linux-hardware.org/?probe=5df1a942d9) | Sep 24, 2023 |
| Acer          | Aspire 5520                 | Notebook    | [5bcc67211c](https://linux-hardware.org/?probe=5bcc67211c) | Sep 24, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [8a1af94640](https://linux-hardware.org/?probe=8a1af94640) | Sep 24, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [8d87ce31c5](https://linux-hardware.org/?probe=8d87ce31c5) | Sep 24, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [10dfbbd349](https://linux-hardware.org/?probe=10dfbbd349) | Sep 24, 2023 |
| HP            | EliteBook 6930p (KK082AV... | Notebook    | [5e61b319b6](https://linux-hardware.org/?probe=5e61b319b6) | Sep 23, 2023 |
| Dell          | Latitude E7450              | Notebook    | [6ba017a802](https://linux-hardware.org/?probe=6ba017a802) | Sep 23, 2023 |
| Lenovo        | ThinkPad W550s 20E1S0VW0... | Notebook    | [e5c12ca1ce](https://linux-hardware.org/?probe=e5c12ca1ce) | Sep 23, 2023 |
| Dell          | Latitude 9430               | Convertible | [d9199fcb7a](https://linux-hardware.org/?probe=d9199fcb7a) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [da277c4d5a](https://linux-hardware.org/?probe=da277c4d5a) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [3b18f2e874](https://linux-hardware.org/?probe=3b18f2e874) | Sep 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [45c1c156af](https://linux-hardware.org/?probe=45c1c156af) | Sep 23, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [9b814d0254](https://linux-hardware.org/?probe=9b814d0254) | Sep 23, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | Desktop     | [41ac03cc3a](https://linux-hardware.org/?probe=41ac03cc3a) | Sep 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [898219c64a](https://linux-hardware.org/?probe=898219c64a) | Sep 23, 2023 |
| Google        | Asuka                       | Notebook    | [cf59aebc4c](https://linux-hardware.org/?probe=cf59aebc4c) | Sep 23, 2023 |
| Panasonic     | CF-31JHG8M1M                | Notebook    | [3dc21238c6](https://linux-hardware.org/?probe=3dc21238c6) | Sep 23, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2a0c1d15f9](https://linux-hardware.org/?probe=2a0c1d15f9) | Sep 23, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [c601e6192f](https://linux-hardware.org/?probe=c601e6192f) | Sep 23, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [3580b7d8d6](https://linux-hardware.org/?probe=3580b7d8d6) | Sep 22, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [ce054bb837](https://linux-hardware.org/?probe=ce054bb837) | Sep 22, 2023 |
| Acer          | Aspire 5520                 | Notebook    | [8329086779](https://linux-hardware.org/?probe=8329086779) | Sep 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3bb5a0e5a0](https://linux-hardware.org/?probe=3bb5a0e5a0) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [347b768d57](https://linux-hardware.org/?probe=347b768d57) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6ae9f9d9f2](https://linux-hardware.org/?probe=6ae9f9d9f2) | Sep 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [e63d1ae740](https://linux-hardware.org/?probe=e63d1ae740) | Sep 22, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [adf0d97721](https://linux-hardware.org/?probe=adf0d97721) | Sep 22, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [be07169f5c](https://linux-hardware.org/?probe=be07169f5c) | Sep 22, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [9fbc54dcb7](https://linux-hardware.org/?probe=9fbc54dcb7) | Sep 22, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [a8c067b868](https://linux-hardware.org/?probe=a8c067b868) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [01f346ff26](https://linux-hardware.org/?probe=01f346ff26) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ba1ec3eb6d](https://linux-hardware.org/?probe=ba1ec3eb6d) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [a204305d1e](https://linux-hardware.org/?probe=a204305d1e) | Sep 22, 2023 |
| AZW           | GTR V21                     | Desktop     | [c3da1f2fd5](https://linux-hardware.org/?probe=c3da1f2fd5) | Sep 22, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [d43d654621](https://linux-hardware.org/?probe=d43d654621) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [290e0fd96b](https://linux-hardware.org/?probe=290e0fd96b) | Sep 21, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [16f768ab94](https://linux-hardware.org/?probe=16f768ab94) | Sep 21, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [9d97540a6e](https://linux-hardware.org/?probe=9d97540a6e) | Sep 21, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [966f802eb6](https://linux-hardware.org/?probe=966f802eb6) | Sep 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [c933105cd8](https://linux-hardware.org/?probe=c933105cd8) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [dd328a6f1f](https://linux-hardware.org/?probe=dd328a6f1f) | Sep 21, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [895d259026](https://linux-hardware.org/?probe=895d259026) | Sep 21, 2023 |
| Dell          | Precision 5550              | Notebook    | [c5183a7443](https://linux-hardware.org/?probe=c5183a7443) | Sep 21, 2023 |
| Dell          | Precision 5550              | Notebook    | [3d927d3dee](https://linux-hardware.org/?probe=3d927d3dee) | Sep 21, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [bd096f1ae3](https://linux-hardware.org/?probe=bd096f1ae3) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e04968b0ab](https://linux-hardware.org/?probe=e04968b0ab) | Sep 20, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [5c5a2a36e2](https://linux-hardware.org/?probe=5c5a2a36e2) | Sep 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f65b051dc9](https://linux-hardware.org/?probe=f65b051dc9) | Sep 20, 2023 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [f8f954cde7](https://linux-hardware.org/?probe=f8f954cde7) | Sep 20, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d630bfea5b](https://linux-hardware.org/?probe=d630bfea5b) | Sep 20, 2023 |
| VPU Compan... | VWNC71429                   | Notebook    | [4dd816ef81](https://linux-hardware.org/?probe=4dd816ef81) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0c71c0240e](https://linux-hardware.org/?probe=0c71c0240e) | Sep 20, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [2d3de22b4b](https://linux-hardware.org/?probe=2d3de22b4b) | Sep 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [32cf98639a](https://linux-hardware.org/?probe=32cf98639a) | Sep 20, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [b66d6be0cf](https://linux-hardware.org/?probe=b66d6be0cf) | Sep 19, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [43f5468ce8](https://linux-hardware.org/?probe=43f5468ce8) | Sep 19, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [139fc573bf](https://linux-hardware.org/?probe=139fc573bf) | Sep 19, 2023 |
| Supermicro    | X11DPi-N 123456789          | Server      | [ab60e84146](https://linux-hardware.org/?probe=ab60e84146) | Sep 19, 2023 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [f832424d90](https://linux-hardware.org/?probe=f832424d90) | Sep 19, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [d8166ef941](https://linux-hardware.org/?probe=d8166ef941) | Sep 19, 2023 |
| Acer          | Aspire 7715Z                | Notebook    | [7abea387dc](https://linux-hardware.org/?probe=7abea387dc) | Sep 19, 2023 |
| Sony          | SVE15137CGW                 | Notebook    | [b454be55a2](https://linux-hardware.org/?probe=b454be55a2) | Sep 19, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [5f584efb57](https://linux-hardware.org/?probe=5f584efb57) | Sep 19, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [7dfeb3f7ff](https://linux-hardware.org/?probe=7dfeb3f7ff) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [acd1c47b9d](https://linux-hardware.org/?probe=acd1c47b9d) | Sep 19, 2023 |
| Lenovo        | IdeaCentre K320 10031       | Desktop     | [35cbc95f9e](https://linux-hardware.org/?probe=35cbc95f9e) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [bb285c7da5](https://linux-hardware.org/?probe=bb285c7da5) | Sep 18, 2023 |
| Lenovo        | IdeaCentre K320 10031       | Desktop     | [bc9d2f6691](https://linux-hardware.org/?probe=bc9d2f6691) | Sep 18, 2023 |
| KUU           | Andes II                    | Notebook    | [a104ad8142](https://linux-hardware.org/?probe=a104ad8142) | Sep 18, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [f9c346c325](https://linux-hardware.org/?probe=f9c346c325) | Sep 18, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8f32398315](https://linux-hardware.org/?probe=8f32398315) | Sep 18, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [11d6fae345](https://linux-hardware.org/?probe=11d6fae345) | Sep 18, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [0578825483](https://linux-hardware.org/?probe=0578825483) | Sep 18, 2023 |
| ASUSTek       | X450CA                      | Notebook    | [b43a3aa61c](https://linux-hardware.org/?probe=b43a3aa61c) | Sep 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [60e5e9a3db](https://linux-hardware.org/?probe=60e5e9a3db) | Sep 18, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [c323f31788](https://linux-hardware.org/?probe=c323f31788) | Sep 17, 2023 |
| ASRock        | Z77 Pro4                    | Desktop     | [13f3de6336](https://linux-hardware.org/?probe=13f3de6336) | Sep 17, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [1e61961aef](https://linux-hardware.org/?probe=1e61961aef) | Sep 17, 2023 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [77c0a6ded9](https://linux-hardware.org/?probe=77c0a6ded9) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [88a398f990](https://linux-hardware.org/?probe=88a398f990) | Sep 17, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cdfa321c48](https://linux-hardware.org/?probe=cdfa321c48) | Sep 17, 2023 |
| HP            | 86C6 0010                   | All in one  | [1a9df16f39](https://linux-hardware.org/?probe=1a9df16f39) | Sep 16, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [9720b79b9d](https://linux-hardware.org/?probe=9720b79b9d) | Sep 16, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [1212656ddf](https://linux-hardware.org/?probe=1212656ddf) | Sep 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d37d40b74c](https://linux-hardware.org/?probe=d37d40b74c) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [0c7cb04f38](https://linux-hardware.org/?probe=0c7cb04f38) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [c47a157971](https://linux-hardware.org/?probe=c47a157971) | Sep 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [10e74a88da](https://linux-hardware.org/?probe=10e74a88da) | Sep 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [bdfc48de30](https://linux-hardware.org/?probe=bdfc48de30) | Sep 16, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [2dae5fb442](https://linux-hardware.org/?probe=2dae5fb442) | Sep 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [3e8e61353c](https://linux-hardware.org/?probe=3e8e61353c) | Sep 15, 2023 |
| HP            | 829A                        | Mini pc     | [d42ad3bd44](https://linux-hardware.org/?probe=d42ad3bd44) | Sep 15, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [a3d82edc9c](https://linux-hardware.org/?probe=a3d82edc9c) | Sep 15, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [601a3eed6e](https://linux-hardware.org/?probe=601a3eed6e) | Sep 15, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [aca0ed1105](https://linux-hardware.org/?probe=aca0ed1105) | Sep 15, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [d1ef9fa580](https://linux-hardware.org/?probe=d1ef9fa580) | Sep 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [27d7589428](https://linux-hardware.org/?probe=27d7589428) | Sep 15, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [35d0557ca0](https://linux-hardware.org/?probe=35d0557ca0) | Sep 14, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [ca5dd06f20](https://linux-hardware.org/?probe=ca5dd06f20) | Sep 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3b71101d09](https://linux-hardware.org/?probe=3b71101d09) | Sep 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [6d61c93aef](https://linux-hardware.org/?probe=6d61c93aef) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [fd2d28b8af](https://linux-hardware.org/?probe=fd2d28b8af) | Sep 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [dc3d71404d](https://linux-hardware.org/?probe=dc3d71404d) | Sep 14, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | Notebook    | [e7463cdeb1](https://linux-hardware.org/?probe=e7463cdeb1) | Sep 14, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [0a5342952c](https://linux-hardware.org/?probe=0a5342952c) | Sep 14, 2023 |
| Lenovo        | ThinkPad T570 20H90011ZA    | Notebook    | [f59a257ab5](https://linux-hardware.org/?probe=f59a257ab5) | Sep 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a9cdcdc284](https://linux-hardware.org/?probe=a9cdcdc284) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [1cf96bfa0e](https://linux-hardware.org/?probe=1cf96bfa0e) | Sep 14, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [14874e9d32](https://linux-hardware.org/?probe=14874e9d32) | Sep 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [3c09b49188](https://linux-hardware.org/?probe=3c09b49188) | Sep 14, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [4f9a4f7031](https://linux-hardware.org/?probe=4f9a4f7031) | Sep 14, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [7056e15dc2](https://linux-hardware.org/?probe=7056e15dc2) | Sep 14, 2023 |
| KUU           | Andes II                    | Notebook    | [6270750e1e](https://linux-hardware.org/?probe=6270750e1e) | Sep 14, 2023 |
| Notebook      | NJ5x_NJ7xLU                 | Notebook    | [7ee403f2a2](https://linux-hardware.org/?probe=7ee403f2a2) | Sep 13, 2023 |
| Lenovo        | ThinkPad E14 20RA005MMX     | Notebook    | [d9d0c012b3](https://linux-hardware.org/?probe=d9d0c012b3) | Sep 13, 2023 |
| ASRock        | H97 Anniversary             | Desktop     | [37014ea895](https://linux-hardware.org/?probe=37014ea895) | Sep 13, 2023 |
| Intel         | X99H                        | Desktop     | [e38e67a30c](https://linux-hardware.org/?probe=e38e67a30c) | Sep 13, 2023 |
| HUAWEI        | WRT-WX9                     | Notebook    | [6bc54e3a67](https://linux-hardware.org/?probe=6bc54e3a67) | Sep 13, 2023 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [ca3874e5b8](https://linux-hardware.org/?probe=ca3874e5b8) | Sep 13, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [138dfabe47](https://linux-hardware.org/?probe=138dfabe47) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [380736a3f4](https://linux-hardware.org/?probe=380736a3f4) | Sep 13, 2023 |
| AZW           | SER V01                     | Mini pc     | [bbbc14d0c3](https://linux-hardware.org/?probe=bbbc14d0c3) | Sep 13, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [79a3f818f2](https://linux-hardware.org/?probe=79a3f818f2) | Sep 12, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [4318e0630c](https://linux-hardware.org/?probe=4318e0630c) | Sep 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0180... | Notebook    | [2f123cee8b](https://linux-hardware.org/?probe=2f123cee8b) | Sep 12, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [4ab8e8a944](https://linux-hardware.org/?probe=4ab8e8a944) | Sep 12, 2023 |
| Dell          | Precision 3571              | Notebook    | [cf2bec0e5b](https://linux-hardware.org/?probe=cf2bec0e5b) | Sep 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2a15e9a8e0](https://linux-hardware.org/?probe=2a15e9a8e0) | Sep 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [74914c875f](https://linux-hardware.org/?probe=74914c875f) | Sep 12, 2023 |
| Lenovo        | Yoga Pro 14s IAH7 82TK      | Notebook    | [53961bd222](https://linux-hardware.org/?probe=53961bd222) | Sep 12, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [09ae29ce64](https://linux-hardware.org/?probe=09ae29ce64) | Sep 12, 2023 |
| HP            | 829A                        | Mini pc     | [dcb9e7ae5b](https://linux-hardware.org/?probe=dcb9e7ae5b) | Sep 11, 2023 |
| HP            | Unknown                     | Notebook    | [defc1de0cf](https://linux-hardware.org/?probe=defc1de0cf) | Sep 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [4070a28418](https://linux-hardware.org/?probe=4070a28418) | Sep 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [3abcd33b9c](https://linux-hardware.org/?probe=3abcd33b9c) | Sep 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [005f0b4e53](https://linux-hardware.org/?probe=005f0b4e53) | Sep 11, 2023 |
| ASRock        | B360M-HDV                   | Desktop     | [d4b0ae4d0c](https://linux-hardware.org/?probe=d4b0ae4d0c) | Sep 11, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7e57362cdc](https://linux-hardware.org/?probe=7e57362cdc) | Sep 11, 2023 |
| Login Info... | LOG-H61H2-M2                | Desktop     | [fa6e51b9bf](https://linux-hardware.org/?probe=fa6e51b9bf) | Sep 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [772c3204b4](https://linux-hardware.org/?probe=772c3204b4) | Sep 10, 2023 |
| Positivo      | C464F                       | Notebook    | [e8154e06d4](https://linux-hardware.org/?probe=e8154e06d4) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [0562141e37](https://linux-hardware.org/?probe=0562141e37) | Sep 10, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [80b1b18a60](https://linux-hardware.org/?probe=80b1b18a60) | Sep 10, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [3b642be7da](https://linux-hardware.org/?probe=3b642be7da) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [978f30c076](https://linux-hardware.org/?probe=978f30c076) | Sep 10, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [71f9c8579d](https://linux-hardware.org/?probe=71f9c8579d) | Sep 10, 2023 |
| ASRock        | H81 Pro BTC                 | Desktop     | [33891eebf8](https://linux-hardware.org/?probe=33891eebf8) | Sep 10, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [5fc8984800](https://linux-hardware.org/?probe=5fc8984800) | Sep 10, 2023 |
| Dell          | Latitude 7280               | Notebook    | [fb9b253bd8](https://linux-hardware.org/?probe=fb9b253bd8) | Sep 10, 2023 |
| Dell          | Latitude 7280               | Notebook    | [936b42d3f3](https://linux-hardware.org/?probe=936b42d3f3) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [9f3f71e147](https://linux-hardware.org/?probe=9f3f71e147) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [f56c6e875b](https://linux-hardware.org/?probe=f56c6e875b) | Sep 10, 2023 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [03ce2f9b74](https://linux-hardware.org/?probe=03ce2f9b74) | Sep 09, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [58e321a88b](https://linux-hardware.org/?probe=58e321a88b) | Sep 09, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [e8f4b3bf42](https://linux-hardware.org/?probe=e8f4b3bf42) | Sep 09, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [69458a43ef](https://linux-hardware.org/?probe=69458a43ef) | Sep 09, 2023 |
| Dell          | G15 5511                    | Notebook    | [c382a29576](https://linux-hardware.org/?probe=c382a29576) | Sep 09, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [198d33eff6](https://linux-hardware.org/?probe=198d33eff6) | Sep 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [ae24b6af25](https://linux-hardware.org/?probe=ae24b6af25) | Sep 09, 2023 |
| ONDA          | H61V Ver:4.01               | Desktop     | [7423e0ce99](https://linux-hardware.org/?probe=7423e0ce99) | Sep 09, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [4a63a68d47](https://linux-hardware.org/?probe=4a63a68d47) | Sep 09, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cdf1a3f17b](https://linux-hardware.org/?probe=cdf1a3f17b) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [625b62078a](https://linux-hardware.org/?probe=625b62078a) | Sep 09, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [440c9854ff](https://linux-hardware.org/?probe=440c9854ff) | Sep 09, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [af11868673](https://linux-hardware.org/?probe=af11868673) | Sep 09, 2023 |
| HP            | Pavilion dv9700             | Notebook    | [a747d33ab9](https://linux-hardware.org/?probe=a747d33ab9) | Sep 09, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [db1e55d494](https://linux-hardware.org/?probe=db1e55d494) | Sep 08, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [1e817297bb](https://linux-hardware.org/?probe=1e817297bb) | Sep 08, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [c1dae32be6](https://linux-hardware.org/?probe=c1dae32be6) | Sep 08, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [3ab6390052](https://linux-hardware.org/?probe=3ab6390052) | Sep 08, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [b4ef54e230](https://linux-hardware.org/?probe=b4ef54e230) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | Notebook    | [cefbf3383a](https://linux-hardware.org/?probe=cefbf3383a) | Sep 08, 2023 |
| Notebook      | W65_67SC                    | Notebook    | [73eae4d8a0](https://linux-hardware.org/?probe=73eae4d8a0) | Sep 08, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [e392e78b0d](https://linux-hardware.org/?probe=e392e78b0d) | Sep 08, 2023 |
| HP            | 82B4                        | Desktop     | [e702194024](https://linux-hardware.org/?probe=e702194024) | Sep 08, 2023 |
| HP            | 82B4                        | Desktop     | [5c85d3bf3c](https://linux-hardware.org/?probe=5c85d3bf3c) | Sep 08, 2023 |
| Intel         | H61                         | Desktop     | [929cfae9af](https://linux-hardware.org/?probe=929cfae9af) | Sep 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [08cdf9f2f5](https://linux-hardware.org/?probe=08cdf9f2f5) | Sep 08, 2023 |
| ASUSTek       | M51AC                       | Desktop     | [2cd8d3959a](https://linux-hardware.org/?probe=2cd8d3959a) | Sep 07, 2023 |
| Shenzhen M... | AHBAA OEM                   | Desktop     | [d4e6f24af3](https://linux-hardware.org/?probe=d4e6f24af3) | Sep 07, 2023 |
| HP            | ENVY 15                     | Notebook    | [996948fd3c](https://linux-hardware.org/?probe=996948fd3c) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d095848fec](https://linux-hardware.org/?probe=d095848fec) | Sep 06, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c9f30a2b26](https://linux-hardware.org/?probe=c9f30a2b26) | Sep 06, 2023 |
| HP            | 844C                        | Desktop     | [6f4911cda7](https://linux-hardware.org/?probe=6f4911cda7) | Sep 06, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [583006d2de](https://linux-hardware.org/?probe=583006d2de) | Sep 06, 2023 |
| Lenovo        | ThinkPad T16 Gen 2 21HH0... | Notebook    | [94c99c8274](https://linux-hardware.org/?probe=94c99c8274) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [b6b2af8418](https://linux-hardware.org/?probe=b6b2af8418) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [89767db9e4](https://linux-hardware.org/?probe=89767db9e4) | Sep 06, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [7bfb24d8e3](https://linux-hardware.org/?probe=7bfb24d8e3) | Sep 06, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7fa390fcc4](https://linux-hardware.org/?probe=7fa390fcc4) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [aa37593b87](https://linux-hardware.org/?probe=aa37593b87) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [230cd8c32e](https://linux-hardware.org/?probe=230cd8c32e) | Sep 06, 2023 |
| Dell          | Precision 5570              | Notebook    | [9baca62616](https://linux-hardware.org/?probe=9baca62616) | Sep 06, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [8d550b32d9](https://linux-hardware.org/?probe=8d550b32d9) | Sep 06, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [208f21a716](https://linux-hardware.org/?probe=208f21a716) | Sep 05, 2023 |
| Biostar       | TB360-BTC Expert            | Desktop     | [650e71b107](https://linux-hardware.org/?probe=650e71b107) | Sep 05, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [5971b283b6](https://linux-hardware.org/?probe=5971b283b6) | Sep 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [40098c0a79](https://linux-hardware.org/?probe=40098c0a79) | Sep 05, 2023 |
| Dell          | G5 5590                     | Notebook    | [1af9fd689a](https://linux-hardware.org/?probe=1af9fd689a) | Sep 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [acdd8a41d9](https://linux-hardware.org/?probe=acdd8a41d9) | Sep 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [606f54ecca](https://linux-hardware.org/?probe=606f54ecca) | Sep 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [9f577988e1](https://linux-hardware.org/?probe=9f577988e1) | Sep 04, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [d082fdd668](https://linux-hardware.org/?probe=d082fdd668) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9accfe317a](https://linux-hardware.org/?probe=9accfe317a) | Sep 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [daeb81e2f6](https://linux-hardware.org/?probe=daeb81e2f6) | Sep 04, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b7d2eae326](https://linux-hardware.org/?probe=b7d2eae326) | Sep 04, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [464ff29a95](https://linux-hardware.org/?probe=464ff29a95) | Sep 04, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [06571c70a0](https://linux-hardware.org/?probe=06571c70a0) | Sep 04, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [1f2c94fe31](https://linux-hardware.org/?probe=1f2c94fe31) | Sep 03, 2023 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | Notebook    | [f9ae8ae2db](https://linux-hardware.org/?probe=f9ae8ae2db) | Sep 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a135074689](https://linux-hardware.org/?probe=a135074689) | Sep 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [e335c8210f](https://linux-hardware.org/?probe=e335c8210f) | Sep 03, 2023 |
| ASUSTek       | X55A                        | Notebook    | [da721dec12](https://linux-hardware.org/?probe=da721dec12) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [75c1744e6f](https://linux-hardware.org/?probe=75c1744e6f) | Sep 03, 2023 |
| HUAWEI        | FRD-WX9                     | Notebook    | [5831652a84](https://linux-hardware.org/?probe=5831652a84) | Sep 03, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [499d13e212](https://linux-hardware.org/?probe=499d13e212) | Sep 03, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [69b91f1c46](https://linux-hardware.org/?probe=69b91f1c46) | Sep 03, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [93b9808859](https://linux-hardware.org/?probe=93b9808859) | Sep 03, 2023 |
| VENEZOLANA... | VIT P2460-02                | Notebook    | [9c1d875ec4](https://linux-hardware.org/?probe=9c1d875ec4) | Sep 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c5787921e3](https://linux-hardware.org/?probe=c5787921e3) | Sep 03, 2023 |
| ASRock        | Z790 PG SONIC               | Desktop     | [72f1cf1ac0](https://linux-hardware.org/?probe=72f1cf1ac0) | Sep 02, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [762498a914](https://linux-hardware.org/?probe=762498a914) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ddae17d733](https://linux-hardware.org/?probe=ddae17d733) | Sep 02, 2023 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [1283f01588](https://linux-hardware.org/?probe=1283f01588) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | IdeaPad Slim 5 16IAH8 83... | Notebook    | [2cfbf5b20c](https://linux-hardware.org/?probe=2cfbf5b20c) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60889fc028](https://linux-hardware.org/?probe=60889fc028) | Sep 02, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [aab4c37d85](https://linux-hardware.org/?probe=aab4c37d85) | Sep 02, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [193a173166](https://linux-hardware.org/?probe=193a173166) | Sep 02, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [bb268c3828](https://linux-hardware.org/?probe=bb268c3828) | Sep 02, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [9b802cfff6](https://linux-hardware.org/?probe=9b802cfff6) | Sep 02, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [af7d9b26da](https://linux-hardware.org/?probe=af7d9b26da) | Sep 01, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [bfb348ab81](https://linux-hardware.org/?probe=bfb348ab81) | Sep 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [238b7ca83d](https://linux-hardware.org/?probe=238b7ca83d) | Sep 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7940f23184](https://linux-hardware.org/?probe=7940f23184) | Sep 01, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [cb4847f435](https://linux-hardware.org/?probe=cb4847f435) | Sep 01, 2023 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [78cb25f581](https://linux-hardware.org/?probe=78cb25f581) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [d0a3fefd23](https://linux-hardware.org/?probe=d0a3fefd23) | Aug 31, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [987f4bab43](https://linux-hardware.org/?probe=987f4bab43) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [710315c4f1](https://linux-hardware.org/?probe=710315c4f1) | Aug 31, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [2ffc319636](https://linux-hardware.org/?probe=2ffc319636) | Aug 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [23242fe856](https://linux-hardware.org/?probe=23242fe856) | Aug 31, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8c1eeceddd](https://linux-hardware.org/?probe=8c1eeceddd) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f01ca37e4c](https://linux-hardware.org/?probe=f01ca37e4c) | Aug 31, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [d4f09e50b2](https://linux-hardware.org/?probe=d4f09e50b2) | Aug 30, 2023 |
| ASUSTek       | Zenbook UX6404VV_UX6404V... | Notebook    | [b7be264a8d](https://linux-hardware.org/?probe=b7be264a8d) | Aug 30, 2023 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | Desktop     | [5de56db01e](https://linux-hardware.org/?probe=5de56db01e) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [58446213e2](https://linux-hardware.org/?probe=58446213e2) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [272508eb60](https://linux-hardware.org/?probe=272508eb60) | Aug 30, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c051ef93ac](https://linux-hardware.org/?probe=c051ef93ac) | Aug 30, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [2a5e5f7d35](https://linux-hardware.org/?probe=2a5e5f7d35) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1964cb4738](https://linux-hardware.org/?probe=1964cb4738) | Aug 30, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7176f2933c](https://linux-hardware.org/?probe=7176f2933c) | Aug 30, 2023 |
| HP            | Dragonfly Pro Laptop PC     | Notebook    | [2b08121ea1](https://linux-hardware.org/?probe=2b08121ea1) | Aug 30, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [93fd8245ab](https://linux-hardware.org/?probe=93fd8245ab) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [fafc374d46](https://linux-hardware.org/?probe=fafc374d46) | Aug 29, 2023 |
| ASUSTek       | Zenbook UP5401ZA_UP5401Z... | Convertible | [63414c002c](https://linux-hardware.org/?probe=63414c002c) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [8a7f22304b](https://linux-hardware.org/?probe=8a7f22304b) | Aug 29, 2023 |
| Dell          | Inspiron 16 7635 2-in-1     | Convertible | [3ebe1769c0](https://linux-hardware.org/?probe=3ebe1769c0) | Aug 29, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [bdaea6156d](https://linux-hardware.org/?probe=bdaea6156d) | Aug 29, 2023 |
| Dell          | Inspiron 16 7635 2-in-1     | Convertible | [2e6f42e754](https://linux-hardware.org/?probe=2e6f42e754) | Aug 29, 2023 |
| HP            | EliteBook x360 1040 G6      | Convertible | [e4b73c6be1](https://linux-hardware.org/?probe=e4b73c6be1) | Aug 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [863b7d7901](https://linux-hardware.org/?probe=863b7d7901) | Aug 29, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [e5923577ad](https://linux-hardware.org/?probe=e5923577ad) | Aug 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [b70096c6f9](https://linux-hardware.org/?probe=b70096c6f9) | Aug 28, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [08229cf960](https://linux-hardware.org/?probe=08229cf960) | Aug 28, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [ed544a4405](https://linux-hardware.org/?probe=ed544a4405) | Aug 28, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [c6e30be0e9](https://linux-hardware.org/?probe=c6e30be0e9) | Aug 27, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [cd64a75511](https://linux-hardware.org/?probe=cd64a75511) | Aug 27, 2023 |
| HP            | Compaq nx6325 (EN188UT#A... | Notebook    | [4324feffa1](https://linux-hardware.org/?probe=4324feffa1) | Aug 27, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [9dddd0c80b](https://linux-hardware.org/?probe=9dddd0c80b) | Aug 27, 2023 |
| LG Electro... | White Tip Mountain FAB3     | All in one  | [91204c1c19](https://linux-hardware.org/?probe=91204c1c19) | Aug 27, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [0f05e92358](https://linux-hardware.org/?probe=0f05e92358) | Aug 27, 2023 |
| Dell          | 0FGCC7 A02                  | Server      | [dc59cd86a0](https://linux-hardware.org/?probe=dc59cd86a0) | Aug 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [0fd39b7eb6](https://linux-hardware.org/?probe=0fd39b7eb6) | Aug 27, 2023 |
| Lenovo        | ThinkPad X200 7459ED2       | Notebook    | [4885ef4597](https://linux-hardware.org/?probe=4885ef4597) | Aug 27, 2023 |
| HP            | 843C                        | Desktop     | [6ad21e7d94](https://linux-hardware.org/?probe=6ad21e7d94) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [f108558763](https://linux-hardware.org/?probe=f108558763) | Aug 27, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [f153f48649](https://linux-hardware.org/?probe=f153f48649) | Aug 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7a67556942](https://linux-hardware.org/?probe=7a67556942) | Aug 27, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [623f136c0f](https://linux-hardware.org/?probe=623f136c0f) | Aug 27, 2023 |
| HP            | 2000                        | Notebook    | [a63dd6e0f1](https://linux-hardware.org/?probe=a63dd6e0f1) | Aug 26, 2023 |
| Dell          | Latitude 7380               | Notebook    | [396738805e](https://linux-hardware.org/?probe=396738805e) | Aug 26, 2023 |
| Dell          | Latitude 7380               | Notebook    | [4a0db5ad8a](https://linux-hardware.org/?probe=4a0db5ad8a) | Aug 26, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [033994cebf](https://linux-hardware.org/?probe=033994cebf) | Aug 26, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ea7c3580b](https://linux-hardware.org/?probe=4ea7c3580b) | Aug 26, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [206043f3a7](https://linux-hardware.org/?probe=206043f3a7) | Aug 26, 2023 |
| Dell          | 07PR60 A00                  | Desktop     | [6f26d24018](https://linux-hardware.org/?probe=6f26d24018) | Aug 26, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [a8d794f4bb](https://linux-hardware.org/?probe=a8d794f4bb) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [a305956d47](https://linux-hardware.org/?probe=a305956d47) | Aug 26, 2023 |
| HP            | ProLiant ML10 v2            | Desktop     | [86cb962a7d](https://linux-hardware.org/?probe=86cb962a7d) | Aug 26, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ca90d2134f](https://linux-hardware.org/?probe=ca90d2134f) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [04426b4b83](https://linux-hardware.org/?probe=04426b4b83) | Aug 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [25c5011587](https://linux-hardware.org/?probe=25c5011587) | Aug 25, 2023 |
| Casper        | NIRVANA NB X400             | Notebook    | [e8aa46ffbc](https://linux-hardware.org/?probe=e8aa46ffbc) | Aug 25, 2023 |
| Dell          | G3 3579                     | Notebook    | [843084a77c](https://linux-hardware.org/?probe=843084a77c) | Aug 25, 2023 |
| HP            | Notebook                    | Notebook    | [6404f1dc3a](https://linux-hardware.org/?probe=6404f1dc3a) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [aa3de32445](https://linux-hardware.org/?probe=aa3de32445) | Aug 25, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [cee65701f2](https://linux-hardware.org/?probe=cee65701f2) | Aug 25, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [de7752b138](https://linux-hardware.org/?probe=de7752b138) | Aug 25, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [116561b889](https://linux-hardware.org/?probe=116561b889) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [3ce0d3817d](https://linux-hardware.org/?probe=3ce0d3817d) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90039U... | Notebook    | [e632335144](https://linux-hardware.org/?probe=e632335144) | Aug 25, 2023 |
| Dell          | Latitude E5570              | Notebook    | [2694b6c409](https://linux-hardware.org/?probe=2694b6c409) | Aug 24, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582HM_... | Notebook    | [2281d96afb](https://linux-hardware.org/?probe=2281d96afb) | Aug 24, 2023 |
| HP            | ENVY 15                     | Notebook    | [6367186102](https://linux-hardware.org/?probe=6367186102) | Aug 24, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [b7ab89701b](https://linux-hardware.org/?probe=b7ab89701b) | Aug 24, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [85e74676ed](https://linux-hardware.org/?probe=85e74676ed) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9a98c147d4](https://linux-hardware.org/?probe=9a98c147d4) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3723979edb](https://linux-hardware.org/?probe=3723979edb) | Aug 24, 2023 |
| HP            | Notebook                    | Notebook    | [1d3025a033](https://linux-hardware.org/?probe=1d3025a033) | Aug 24, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [c2e1396370](https://linux-hardware.org/?probe=c2e1396370) | Aug 23, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a5357a41b4](https://linux-hardware.org/?probe=a5357a41b4) | Aug 23, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [536f3c29b6](https://linux-hardware.org/?probe=536f3c29b6) | Aug 23, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [a8fb075a9a](https://linux-hardware.org/?probe=a8fb075a9a) | Aug 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1d0505af7f](https://linux-hardware.org/?probe=1d0505af7f) | Aug 23, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [09820a2ab9](https://linux-hardware.org/?probe=09820a2ab9) | Aug 23, 2023 |
| Biostar       | B450MH                      | Desktop     | [21f8924d2c](https://linux-hardware.org/?probe=21f8924d2c) | Aug 23, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [297d07a2e3](https://linux-hardware.org/?probe=297d07a2e3) | Aug 22, 2023 |
| Dell          | Latitude E6430              | Notebook    | [8125ef4bf1](https://linux-hardware.org/?probe=8125ef4bf1) | Aug 22, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [7cf233eb4d](https://linux-hardware.org/?probe=7cf233eb4d) | Aug 22, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [cc07dc8140](https://linux-hardware.org/?probe=cc07dc8140) | Aug 22, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | Notebook    | [f30e9be6d0](https://linux-hardware.org/?probe=f30e9be6d0) | Aug 22, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [210e9d3b38](https://linux-hardware.org/?probe=210e9d3b38) | Aug 21, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [75776f43bf](https://linux-hardware.org/?probe=75776f43bf) | Aug 21, 2023 |
| Intel         | NUC7i3BNB J22859-314        | Mini pc     | [ce4752c5b7](https://linux-hardware.org/?probe=ce4752c5b7) | Aug 21, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [81bc5661ca](https://linux-hardware.org/?probe=81bc5661ca) | Aug 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a7cd220563](https://linux-hardware.org/?probe=a7cd220563) | Aug 21, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [c2ca279bdd](https://linux-hardware.org/?probe=c2ca279bdd) | Aug 21, 2023 |
| Medion        | WIM2210                     | Notebook    | [5ef8675128](https://linux-hardware.org/?probe=5ef8675128) | Aug 21, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [d59b79adfe](https://linux-hardware.org/?probe=d59b79adfe) | Aug 21, 2023 |
| HP            | EliteBook 835 13 inch G9... | Notebook    | [f973c9678d](https://linux-hardware.org/?probe=f973c9678d) | Aug 20, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [bca7b6990c](https://linux-hardware.org/?probe=bca7b6990c) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [b9701cd43c](https://linux-hardware.org/?probe=b9701cd43c) | Aug 20, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [e3f7de5c66](https://linux-hardware.org/?probe=e3f7de5c66) | Aug 20, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [158cc5fe6f](https://linux-hardware.org/?probe=158cc5fe6f) | Aug 20, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [872053c50b](https://linux-hardware.org/?probe=872053c50b) | Aug 20, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [fee22676ae](https://linux-hardware.org/?probe=fee22676ae) | Aug 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5ca28d9b12](https://linux-hardware.org/?probe=5ca28d9b12) | Aug 20, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a11383f5b3](https://linux-hardware.org/?probe=a11383f5b3) | Aug 19, 2023 |
| ASRock        | Q1900M                      | Desktop     | [1e1e781c93](https://linux-hardware.org/?probe=1e1e781c93) | Aug 19, 2023 |
| Foxconn       | A74MX-S/A74MX-K             | Desktop     | [1cd8a1d54a](https://linux-hardware.org/?probe=1cd8a1d54a) | Aug 19, 2023 |
| Samsung       | DP500A2D-A01UK SEC_SW_RE... | All in one  | [f56bdd302b](https://linux-hardware.org/?probe=f56bdd302b) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [b52dbe962f](https://linux-hardware.org/?probe=b52dbe962f) | Aug 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [816ff5d908](https://linux-hardware.org/?probe=816ff5d908) | Aug 19, 2023 |
| ECS           | 7AT-3LB                     | Desktop     | [fe545a2a23](https://linux-hardware.org/?probe=fe545a2a23) | Aug 19, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a75b18f36c](https://linux-hardware.org/?probe=a75b18f36c) | Aug 19, 2023 |
| Lenovo        | V320-17ISK 81B6             | Notebook    | [cc96bcc8d9](https://linux-hardware.org/?probe=cc96bcc8d9) | Aug 19, 2023 |
| Acer          | Veriton M2611G v1.0         | Desktop     | [1527c20b46](https://linux-hardware.org/?probe=1527c20b46) | Aug 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [b7347b4f7c](https://linux-hardware.org/?probe=b7347b4f7c) | Aug 19, 2023 |
| Intel         | DH67CL AAG10212-205         | Desktop     | [329cfbcae1](https://linux-hardware.org/?probe=329cfbcae1) | Aug 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [950ffc31ff](https://linux-hardware.org/?probe=950ffc31ff) | Aug 18, 2023 |
| Dell          | 0X8582                      | Desktop     | [c9661782e6](https://linux-hardware.org/?probe=c9661782e6) | Aug 18, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [c6918bacbd](https://linux-hardware.org/?probe=c6918bacbd) | Aug 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [e37325dbc2](https://linux-hardware.org/?probe=e37325dbc2) | Aug 18, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79d5cb1a00](https://linux-hardware.org/?probe=79d5cb1a00) | Aug 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [0edbb9bdf1](https://linux-hardware.org/?probe=0edbb9bdf1) | Aug 17, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [ed669d11d8](https://linux-hardware.org/?probe=ed669d11d8) | Aug 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [645171b203](https://linux-hardware.org/?probe=645171b203) | Aug 17, 2023 |
| Acer          | Aspire Z5710                | All in one  | [10e9ce60c2](https://linux-hardware.org/?probe=10e9ce60c2) | Aug 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b65293c5a8](https://linux-hardware.org/?probe=b65293c5a8) | Aug 17, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [0e1961a9b3](https://linux-hardware.org/?probe=0e1961a9b3) | Aug 17, 2023 |
| Acer          | Swift SF314-510G            | Notebook    | [11a4bc0bac](https://linux-hardware.org/?probe=11a4bc0bac) | Aug 16, 2023 |
| Dell          | Precision 7530              | Notebook    | [dfaa8829e1](https://linux-hardware.org/?probe=dfaa8829e1) | Aug 16, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [68639ddf06](https://linux-hardware.org/?probe=68639ddf06) | Aug 16, 2023 |
| ASUSTek       | X55A                        | Notebook    | [03099661ec](https://linux-hardware.org/?probe=03099661ec) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [4c4e9222ce](https://linux-hardware.org/?probe=4c4e9222ce) | Aug 16, 2023 |
| Shuttle       | NC03U                       | Notebook    | [91097c1ebf](https://linux-hardware.org/?probe=91097c1ebf) | Aug 16, 2023 |
| Acer          | Aspire V5-571               | Notebook    | [bb39a5a125](https://linux-hardware.org/?probe=bb39a5a125) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [c4b30192fa](https://linux-hardware.org/?probe=c4b30192fa) | Aug 15, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [529613b5c7](https://linux-hardware.org/?probe=529613b5c7) | Aug 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [ea9845e55b](https://linux-hardware.org/?probe=ea9845e55b) | Aug 15, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [fd5dd48ab1](https://linux-hardware.org/?probe=fd5dd48ab1) | Aug 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [088582c57c](https://linux-hardware.org/?probe=088582c57c) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [bf2f7b52d1](https://linux-hardware.org/?probe=bf2f7b52d1) | Aug 15, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [7b94897e1a](https://linux-hardware.org/?probe=7b94897e1a) | Aug 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [caa5e1d37a](https://linux-hardware.org/?probe=caa5e1d37a) | Aug 14, 2023 |
| AK3V          | 1.0                         | Desktop     | [02b6f071a6](https://linux-hardware.org/?probe=02b6f071a6) | Aug 14, 2023 |
| HP            | 21F5 0A                     | Desktop     | [7a8b1ea89a](https://linux-hardware.org/?probe=7a8b1ea89a) | Aug 14, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [0e51f02009](https://linux-hardware.org/?probe=0e51f02009) | Aug 14, 2023 |
| MSI           | Stealth 14Studio A13VG      | Notebook    | [a8035775f2](https://linux-hardware.org/?probe=a8035775f2) | Aug 14, 2023 |
| Panasonic     | CF-SX1WEVHR                 | Notebook    | [9a680df78d](https://linux-hardware.org/?probe=9a680df78d) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | Desktop     | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| Alienware     | m15 R7                      | Notebook    | [a501a43d37](https://linux-hardware.org/?probe=a501a43d37) | Aug 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [da23ffa8ca](https://linux-hardware.org/?probe=da23ffa8ca) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3decac5b92](https://linux-hardware.org/?probe=3decac5b92) | Aug 13, 2023 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [74e54546c6](https://linux-hardware.org/?probe=74e54546c6) | Aug 13, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [e069c1f3d5](https://linux-hardware.org/?probe=e069c1f3d5) | Aug 13, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [c94361f09d](https://linux-hardware.org/?probe=c94361f09d) | Aug 13, 2023 |
| Acer          | Extensa 5220                | Notebook    | [fb3e613b5c](https://linux-hardware.org/?probe=fb3e613b5c) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [396327d1fa](https://linux-hardware.org/?probe=396327d1fa) | Aug 13, 2023 |
| Dell          | Inspiron 14 7435 2-in-1     | Convertible | [ee7ca4926f](https://linux-hardware.org/?probe=ee7ca4926f) | Aug 13, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b232e62577](https://linux-hardware.org/?probe=b232e62577) | Aug 13, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [bcf7b9bd8f](https://linux-hardware.org/?probe=bcf7b9bd8f) | Aug 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [e52e8ee5df](https://linux-hardware.org/?probe=e52e8ee5df) | Aug 13, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [fee93b31f5](https://linux-hardware.org/?probe=fee93b31f5) | Aug 13, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [2996bc5d6c](https://linux-hardware.org/?probe=2996bc5d6c) | Aug 13, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4d954b8546](https://linux-hardware.org/?probe=4d954b8546) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7d7349fef7](https://linux-hardware.org/?probe=7d7349fef7) | Aug 12, 2023 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [eb228fe415](https://linux-hardware.org/?probe=eb228fe415) | Aug 12, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [61f00a0418](https://linux-hardware.org/?probe=61f00a0418) | Aug 12, 2023 |
| Acer          | TravelMate Spin P414RN-5... | Convertible | [68175aa949](https://linux-hardware.org/?probe=68175aa949) | Aug 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 569       | 30.87%  |
| 6.2.0-26-generic        | 113       | 6.13%   |
| 6.2.0-27-generic        | 111       | 6.02%   |
| 6.2.0-25-generic        | 103       | 5.59%   |
| 6.2.0-39-generic        | 102       | 5.53%   |
| 6.2.0-33-generic        | 99        | 5.37%   |
| 6.2.0-24-generic        | 98        | 5.32%   |
| 6.2.0-32-generic        | 95        | 5.15%   |
| 6.2.0-34-generic        | 92        | 4.99%   |
| 6.2.0-23-generic        | 82        | 4.45%   |
| 6.2.0-35-generic        | 54        | 2.93%   |
| 6.2.0-31-generic        | 51        | 2.77%   |
| 6.2.0-36-generic        | 48        | 2.6%    |
| 5.19.0-21-generic       | 20        | 1.09%   |
| 6.2.0-37-generic        | 15        | 0.81%   |
| 6.2.0-18-generic        | 13        | 0.71%   |
| 6.4.0-060400-generic    | 8         | 0.43%   |
| 5.19.0-41-generic       | 8         | 0.43%   |
| 6.3.2-060302-generic    | 6         | 0.33%   |
| 6.1.0-16-generic        | 5         | 0.27%   |
| 5.19.0-46-generic       | 5         | 0.27%   |
| 6.5.0-14-generic        | 4         | 0.22%   |
| 6.3.4-060304-generic    | 4         | 0.22%   |
| 6.2.0-1004-raspi        | 4         | 0.22%   |
| 6.5.0-060500-generic    | 3         | 0.16%   |
| 6.3.6-060306-generic    | 3         | 0.16%   |
| 6.2.9-060209-generic    | 3         | 0.16%   |
| 6.2.0-38-generic        | 3         | 0.16%   |
| 6.2.0-1007-lowlatency   | 3         | 0.16%   |
| 6.2.0-1003-lowlatency   | 3         | 0.16%   |
| 5.19.0-40-generic       | 3         | 0.16%   |
| 5.19.0-31-generic       | 3         | 0.16%   |
| 5.19.0-28-generic       | 3         | 0.16%   |
| 6.5.1-060501-generic    | 2         | 0.11%   |
| 6.5.0-060500rc5-generic | 2         | 0.11%   |
| 6.4.7-t2-lunar          | 2         | 0.11%   |
| 6.4.6-060406-generic    | 2         | 0.11%   |
| 6.4.3-060403-generic    | 2         | 0.11%   |
| 6.4.12-060412-generic   | 2         | 0.11%   |
| 6.3.7-060307-generic    | 2         | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 1558      | 90.48%  |
| 5.19.0  | 57        | 3.31%   |
| 6.5.0   | 10        | 0.58%   |
| 6.4.0   | 10        | 0.58%   |
| 6.3.2   | 6         | 0.35%   |
| 6.1.0   | 6         | 0.35%   |
| 6.3.0   | 5         | 0.29%   |
| 6.3.4   | 4         | 0.23%   |
| 5.14.0  | 4         | 0.23%   |
| 6.5.1   | 3         | 0.17%   |
| 6.4.7   | 3         | 0.17%   |
| 6.3.6   | 3         | 0.17%   |
| 6.2.9   | 3         | 0.17%   |
| 6.2.16  | 3         | 0.17%   |
| 6.6.0   | 2         | 0.12%   |
| 6.5.5   | 2         | 0.12%   |
| 6.5.3   | 2         | 0.12%   |
| 6.4.8   | 2         | 0.12%   |
| 6.4.6   | 2         | 0.12%   |
| 6.4.3   | 2         | 0.12%   |
| 6.4.12  | 2         | 0.12%   |
| 6.3.7   | 2         | 0.12%   |
| 6.3.5   | 2         | 0.12%   |
| 6.3.1   | 2         | 0.12%   |
| 6.2.12  | 2         | 0.12%   |
| 6.2.11  | 2         | 0.12%   |
| 5.15.0  | 2         | 0.12%   |
| 6.9.11  | 1         | 0.06%   |
| 6.5.9   | 1         | 0.06%   |
| 6.5.7   | 1         | 0.06%   |
| 6.5.6   | 1         | 0.06%   |
| 6.5.4   | 1         | 0.06%   |
| 6.5.2   | 1         | 0.06%   |
| 6.4.5   | 1         | 0.06%   |
| 6.4.2   | 1         | 0.06%   |
| 6.4.11  | 1         | 0.06%   |
| 6.3.8   | 1         | 0.06%   |
| 6.3.3   | 1         | 0.06%   |
| 6.2.6   | 1         | 0.06%   |
| 6.2.10  | 1         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 1569      | 91.43%  |
| 5.19    | 59        | 3.44%   |
| 6.3     | 26        | 1.52%   |
| 6.4     | 22        | 1.28%   |
| 6.5     | 20        | 1.17%   |
| 6.1     | 7         | 0.41%   |
| 5.14    | 4         | 0.23%   |
| 5.15    | 3         | 0.17%   |
| 6.6     | 2         | 0.12%   |
| 6.9     | 1         | 0.06%   |
| 6.0     | 1         | 0.06%   |
| 5.17    | 1         | 0.06%   |
| 5.11    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1694      | 99.41%  |
| aarch64 | 8         | 0.47%   |
| riscv64 | 1         | 0.06%   |
| armv7l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1635      | 95.89%  |
| X-Cinnamon      | 25        | 1.47%   |
| Unknown         | 24        | 1.41%   |
| GNOME Flashback | 6         | 0.35%   |
| DDE             | 5         | 0.29%   |
| i3              | 4         | 0.23%   |
| sway            | 3         | 0.18%   |
| GNOME Classic   | 2         | 0.12%   |
| mwm             | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 1125      | 65.07%  |
| X11     | 562       | 32.5%   |
| Unknown | 23        | 1.33%   |
| Tty     | 19        | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM3    | 1504      | 88.16%  |
| Unknown | 157       | 9.2%    |
| LightDM | 38        | 2.23%   |
| GDM     | 4         | 0.23%   |
| SDDM    | 2         | 0.12%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 785       | 45.83%  |
| de_DE   | 194       | 11.33%  |
| fr_FR   | 102       | 5.95%   |
| C       | 78        | 4.55%   |
| es_ES   | 60        | 3.5%    |
| pt_BR   | 58        | 3.39%   |
| it_IT   | 56        | 3.27%   |
| en_GB   | 49        | 2.86%   |
| ru_RU   | 47        | 2.74%   |
| en_CA   | 27        | 1.58%   |
| pl_PL   | 23        | 1.34%   |
| en_AU   | 21        | 1.23%   |
| en_IN   | 17        | 0.99%   |
| nl_NL   | 15        | 0.88%   |
| hu_HU   | 11        | 0.64%   |
| fr_CA   | 11        | 0.64%   |
| cs_CZ   | 10        | 0.58%   |
| Unknown | 10        | 0.58%   |
| sv_SE   | 9         | 0.53%   |
| zh_CN   | 8         | 0.47%   |
| ja_JP   | 7         | 0.41%   |
| fi_FI   | 7         | 0.41%   |
| es_MX   | 7         | 0.41%   |
| el_GR   | 7         | 0.41%   |
| de_AT   | 7         | 0.41%   |
| bg_BG   | 7         | 0.41%   |
| pt_PT   | 6         | 0.35%   |
| en_ZA   | 6         | 0.35%   |
| tr_TR   | 5         | 0.29%   |
| nb_NO   | 4         | 0.23%   |
| en_NZ   | 4         | 0.23%   |
| da_DK   | 4         | 0.23%   |
| ro_RO   | 3         | 0.18%   |
| en_IL   | 3         | 0.18%   |
| de_CH   | 3         | 0.18%   |
| ca_ES   | 3         | 0.18%   |
| zh_TW   | 2         | 0.12%   |
| sk_SK   | 2         | 0.12%   |
| lt_LT   | 2         | 0.12%   |
| ko_KR   | 2         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1061      | 61.69%  |
| EFI  | 659       | 38.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Tmpfs   | 927       | 54.08%  |
| Ext4    | 721       | 42.07%  |
| Overlay | 33        | 1.93%   |
| Btrfs   | 17        | 0.99%   |
| Zfs     | 11        | 0.64%   |
| XXX4    | 2         | 0.12%   |
| Xfs     | 2         | 0.12%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1473      | 86.24%  |
| Unknown | 137       | 8.02%   |
| MBR     | 98        | 5.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1496      | 87.13%  |
| Yes       | 221       | 12.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1109      | 64.44%  |
| Yes       | 612       | 35.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 273       | 16.02%  |
| ASUSTek Computer                     | 270       | 15.85%  |
| Hewlett-Packard                      | 252       | 14.79%  |
| Dell                                 | 211       | 12.38%  |
| MSI                                  | 93        | 5.46%   |
| Acer                                 | 92        | 5.4%    |
| Gigabyte Technology                  | 80        | 4.69%   |
| Apple                                | 63        | 3.7%    |
| ASRock                               | 41        | 2.41%   |
| Intel                                | 37        | 2.17%   |
| HUAWEI                               | 35        | 2.05%   |
| Unknown                              | 19        | 1.12%   |
| Samsung Electronics                  | 18        | 1.06%   |
| Toshiba                              | 17        | 1%      |
| Fujitsu                              | 13        | 0.76%   |
| Google                               | 12        | 0.7%    |
| Raspberry Pi Foundation              | 9         | 0.53%   |
| Notebook                             | 9         | 0.53%   |
| Microsoft                            | 9         | 0.53%   |
| Timi                                 | 8         | 0.47%   |
| Sony                                 | 8         | 0.47%   |
| AZW                                  | 7         | 0.41%   |
| Packard Bell                         | 5         | 0.29%   |
| Medion                               | 5         | 0.29%   |
| Biostar                              | 5         | 0.29%   |
| Supermicro                           | 4         | 0.23%   |
| Razer                                | 4         | 0.23%   |
| Positivo                             | 4         | 0.23%   |
| Panasonic                            | 4         | 0.23%   |
| Infinix                              | 4         | 0.23%   |
| Shuttle                              | 3         | 0.18%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.18%   |
| Shanghai Zhaoxin Semiconductor       | 3         | 0.18%   |
| Pegatron                             | 3         | 0.18%   |
| Huanan                               | 3         | 0.18%   |
| Gateway                              | 3         | 0.18%   |
| Foxconn                              | 3         | 0.18%   |
| Chuwi                                | 3         | 0.18%   |
| ASRockRack                           | 3         | 0.18%   |
| Alienware                            | 3         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 24        | 1.41%   |
| ASUS All Series                  | 10        | 0.59%   |
| HP EliteBook 840 G6              | 7         | 0.41%   |
| HP Notebook                      | 6         | 0.35%   |
| Apple MacBookPro9,2              | 6         | 0.35%   |
| Dell Latitude 7480               | 5         | 0.29%   |
| MSI MS-7C95                      | 4         | 0.23%   |
| MSI MS-7B86                      | 4         | 0.23%   |
| HUAWEI KLVL-WXX9                 | 4         | 0.23%   |
| HUAWEI KLVD-WXX9                 | 4         | 0.23%   |
| HUAWEI BOM-WXX9                  | 4         | 0.23%   |
| HP EliteBook 840 G5              | 4         | 0.23%   |
| Dell Latitude 5400               | 4         | 0.23%   |
| Dell Inspiron 5521               | 4         | 0.23%   |
| Dell G5 5590                     | 4         | 0.23%   |
| Apple MacBookAir7,2              | 4         | 0.23%   |
| Shanghai Zhaoxin ZXE CRB         | 3         | 0.18%   |
| MSI MS-7C37                      | 3         | 0.18%   |
| MSI MS-7721                      | 3         | 0.18%   |
| MSI Modern 14 A10M               | 3         | 0.18%   |
| Microsoft Surface Pro 7          | 3         | 0.18%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7 | 3         | 0.18%   |
| Lenovo IdeaPad 5 14ALC05 82LM    | 3         | 0.18%   |
| Lenovo G50-70 20351              | 3         | 0.18%   |
| Intel H61                        | 3         | 0.18%   |
| HUAWEI BOHB-WAX9                 | 3         | 0.18%   |
| HP ZBook Studio G3               | 3         | 0.18%   |
| HP Pavilion dv6                  | 3         | 0.18%   |
| HP ENVY 15                       | 3         | 0.18%   |
| HP EliteDesk 800 G1 SFF          | 3         | 0.18%   |
| HP EliteBook 840 G3              | 3         | 0.18%   |
| Gigabyte B450M DS3H              | 3         | 0.18%   |
| Dell XPS 15 9500                 | 3         | 0.18%   |
| Dell Precision 5570              | 3         | 0.18%   |
| Dell OptiPlex 790                | 3         | 0.18%   |
| Dell OptiPlex 3010               | 3         | 0.18%   |
| Dell Latitude E6420              | 3         | 0.18%   |
| Dell Latitude 7420               | 3         | 0.18%   |
| Dell Latitude 5490               | 3         | 0.18%   |
| Dell Latitude 5480               | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 121       | 7.1%    |
| Dell Latitude       | 65        | 3.81%   |
| Acer Aspire         | 52        | 3.05%   |
| Lenovo IdeaPad      | 50        | 2.93%   |
| Dell Inspiron       | 48        | 2.82%   |
| HP EliteBook        | 46        | 2.7%    |
| ASUS PRIME          | 41        | 2.41%   |
| ASUS ROG            | 34        | 2%      |
| HP Pavilion         | 33        | 1.94%   |
| Dell XPS            | 30        | 1.76%   |
| HP ENVY             | 28        | 1.64%   |
| HP Laptop           | 27        | 1.58%   |
| ASUS VivoBook       | 27        | 1.58%   |
| ASUS ZenBook        | 26        | 1.53%   |
| ASUS TUF            | 25        | 1.47%   |
| Dell OptiPlex       | 24        | 1.41%   |
| Unknown             | 24        | 1.41%   |
| Lenovo ThinkCentre  | 20        | 1.17%   |
| HP ProBook          | 20        | 1.17%   |
| Lenovo Yoga         | 18        | 1.06%   |
| Dell Precision      | 18        | 1.06%   |
| Acer Swift          | 15        | 0.88%   |
| HP EliteDesk        | 13        | 0.76%   |
| ASUS ASUS           | 13        | 0.76%   |
| Acer Nitro          | 13        | 0.76%   |
| Toshiba Satellite   | 12        | 0.7%    |
| Lenovo Legion       | 11        | 0.65%   |
| Lenovo IdeaPadFlex  | 11        | 0.65%   |
| Dell Vostro         | 10        | 0.59%   |
| ASUS All            | 10        | 0.59%   |
| RPi Raspberry       | 9         | 0.53%   |
| Microsoft Surface   | 9         | 0.53%   |
| HP ProDesk          | 9         | 0.53%   |
| HP Compaq           | 9         | 0.53%   |
| Apple MacBookPro9   | 7         | 0.41%   |
| Lenovo ThinkBook    | 6         | 0.35%   |
| Lenovo IdeaCentre   | 6         | 0.35%   |
| HP Notebook         | 6         | 0.35%   |
| MSI Stealth         | 5         | 0.29%   |
| Lenovo ThinkStation | 5         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 208       | 12.21%  |
| 2022    | 200       | 11.74%  |
| 2020    | 161       | 9.45%   |
| 2019    | 137       | 8.04%   |
| 2018    | 110       | 6.46%   |
| 2012    | 102       | 5.99%   |
| 2017    | 100       | 5.87%   |
| 2014    | 94        | 5.52%   |
| 2023    | 91        | 5.34%   |
| 2016    | 90        | 5.28%   |
| 2015    | 88        | 5.16%   |
| 2013    | 88        | 5.16%   |
| 2011    | 81        | 4.75%   |
| 2010    | 61        | 3.58%   |
| 2009    | 37        | 2.17%   |
| 2008    | 27        | 1.58%   |
| 2007    | 10        | 0.59%   |
| Unknown | 9         | 0.53%   |
| 2006    | 8         | 0.47%   |
| 2024    | 1         | 0.06%   |
| 2005    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 934       | 54.81%  |
| Desktop        | 554       | 32.51%  |
| Convertible    | 100       | 5.87%   |
| Mini pc        | 36        | 2.11%   |
| All in one     | 33        | 1.94%   |
| Tablet         | 27        | 1.58%   |
| System on chip | 10        | 0.59%   |
| Server         | 10        | 0.59%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1551      | 90.65%  |
| Enabled  | 160       | 9.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1690      | 99.18%  |
| Yes  | 14        | 0.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 443       | 25.88%  |
| 16.01-24.0      | 380       | 22.2%   |
| 8.01-16.0       | 291       | 17%     |
| 32.01-64.0      | 215       | 12.56%  |
| 3.01-4.0        | 214       | 12.5%   |
| 64.01-256.0     | 85        | 4.96%   |
| 24.01-32.0      | 56        | 3.27%   |
| 1.01-2.0        | 15        | 0.88%   |
| 2.01-3.0        | 7         | 0.41%   |
| More than 256.0 | 4         | 0.23%   |
| 0.51-1.0        | 1         | 0.06%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 565       | 31.6%   |
| 1.01-2.0   | 422       | 23.6%   |
| 4.01-8.0   | 378       | 21.14%  |
| 3.01-4.0   | 305       | 17.06%  |
| 8.01-16.0  | 82        | 4.59%   |
| 16.01-24.0 | 14        | 0.78%   |
| 24.01-32.0 | 7         | 0.39%   |
| 32.01-64.0 | 6         | 0.34%   |
| 0.51-1.0   | 6         | 0.34%   |
| 0.01-0.5   | 3         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1124      | 65.01%  |
| 2      | 374       | 21.63%  |
| 3      | 119       | 6.88%   |
| 4      | 50        | 2.89%   |
| 5      | 25        | 1.45%   |
| 6      | 18        | 1.04%   |
| 0      | 7         | 0.4%    |
| 8      | 5         | 0.29%   |
| 7      | 3         | 0.17%   |
| 101    | 1         | 0.06%   |
| 12     | 1         | 0.06%   |
| 11     | 1         | 0.06%   |
| 9      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1258      | 73.57%  |
| Yes       | 452       | 26.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1339      | 78.35%  |
| No        | 370       | 21.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1378      | 80.68%  |
| No        | 330       | 19.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1225      | 71.39%  |
| No        | 491       | 28.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 298       | 17.47%  |
| Germany      | 221       | 12.95%  |
| France       | 108       | 6.33%   |
| Italy        | 83        | 4.87%   |
| Canada       | 80        | 4.69%   |
| Brazil       | 80        | 4.69%   |
| Russia       | 70        | 4.1%    |
| UK           | 68        | 3.99%   |
| India        | 45        | 2.64%   |
| Australia    | 38        | 2.23%   |
| Spain        | 37        | 2.17%   |
| Netherlands  | 36        | 2.11%   |
| Poland       | 28        | 1.64%   |
| Sweden       | 22        | 1.29%   |
| Norway       | 22        | 1.29%   |
| Switzerland  | 21        | 1.23%   |
| Mexico       | 20        | 1.17%   |
| Czechia      | 19        | 1.11%   |
| Turkey       | 18        | 1.06%   |
| Romania      | 18        | 1.06%   |
| Austria      | 18        | 1.06%   |
| Hungary      | 17        | 1%      |
| Finland      | 17        | 1%      |
| Portugal     | 16        | 0.94%   |
| China        | 16        | 0.94%   |
| Belgium      | 15        | 0.88%   |
| Greece       | 14        | 0.82%   |
| South Africa | 12        | 0.7%    |
| Chile        | 11        | 0.64%   |
| Pakistan     | 10        | 0.59%   |
| Japan        | 10        | 0.59%   |
| Israel       | 10        | 0.59%   |
| Argentina    | 10        | 0.59%   |
| Indonesia    | 9         | 0.53%   |
| Serbia       | 8         | 0.47%   |
| Philippines  | 8         | 0.47%   |
| Ireland      | 8         | 0.47%   |
| Denmark      | 8         | 0.47%   |
| Bulgaria     | 8         | 0.47%   |
| New Zealand  | 7         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 20        | 1.14%   |
| Moscow            | 20        | 1.14%   |
| Berlin            | 16        | 0.91%   |
| St Petersburg     | 13        | 0.74%   |
| Montreal          | 13        | 0.74%   |
| Melbourne         | 12        | 0.68%   |
| Helsinki          | 12        | 0.68%   |
| Toronto           | 10        | 0.57%   |
| Prague            | 10        | 0.57%   |
| Oslo              | 10        | 0.57%   |
| Warsaw            | 9         | 0.51%   |
| Munich            | 9         | 0.51%   |
| Hamburg           | 9         | 0.51%   |
| Paris             | 8         | 0.46%   |
| Brisbane          | 8         | 0.46%   |
| Barcelona         | 8         | 0.46%   |
| Vienna            | 7         | 0.4%    |
| Rome              | 7         | 0.4%    |
| Oshawa            | 7         | 0.4%    |
| Milan             | 7         | 0.4%    |
| Budapest          | 7         | 0.4%    |
| Atlanta           | 7         | 0.4%    |
| Valencia          | 6         | 0.34%   |
| Sydney            | 6         | 0.34%   |
| Leipzig           | 6         | 0.34%   |
| Frankfurt am Main | 6         | 0.34%   |
| Bucharest         | 6         | 0.34%   |
| Brussels          | 6         | 0.34%   |
| Belgrade          | 6         | 0.34%   |
| Tokyo             | 5         | 0.29%   |
| Tehran            | 5         | 0.29%   |
| Sofia             | 5         | 0.29%   |
| Seattle           | 5         | 0.29%   |
| Santiago          | 5         | 0.29%   |
| Rio de Janeiro    | 5         | 0.29%   |
| Québec           | 5         | 0.29%   |
| Perth             | 5         | 0.29%   |
| New York          | 5         | 0.29%   |
| Nairobi           | 5         | 0.29%   |
| Milano            | 5         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 426       | 564    | 17.74%  |
| Seagate                     | 267       | 374    | 11.12%  |
| WDC                         | 246       | 369    | 10.24%  |
| SanDisk                     | 162       | 200    | 6.74%   |
| Kingston                    | 128       | 150    | 5.33%   |
| Toshiba                     | 100       | 121    | 4.16%   |
| SK hynix                    | 96        | 106    | 4%      |
| Unknown                     | 86        | 116    | 3.58%   |
| Crucial                     | 85        | 100    | 3.54%   |
| Micron Technology           | 83        | 105    | 3.46%   |
| Intel                       | 79        | 95     | 3.29%   |
| Hitachi                     | 44        | 56     | 1.83%   |
| KIOXIA                      | 38        | 42     | 1.58%   |
| Phison Electronics          | 33        | 41     | 1.37%   |
| Apple                       | 32        | 41     | 1.33%   |
| Kingston Technology Company | 26        | 34     | 1.08%   |
| HGST                        | 26        | 60     | 1.08%   |
| China                       | 26        | 32     | 1.08%   |
| Micron/Crucial Technology   | 25        | 29     | 1.04%   |
| A-DATA Technology           | 19        | 25     | 0.79%   |
| Silicon Motion              | 16        | 16     | 0.67%   |
| Unknown                     | 15        | 21     | 0.62%   |
| Phison                      | 14        | 15     | 0.58%   |
| Intenso                     | 14        | 19     | 0.58%   |
| PNY                         | 11        | 15     | 0.46%   |
| SPCC                        | 10        | 11     | 0.42%   |
| Patriot                     | 10        | 10     | 0.42%   |
| Hewlett-Packard             | 9         | 14     | 0.37%   |
| Netac                       | 8         | 8      | 0.33%   |
| LITEON                      | 8         | 11     | 0.33%   |
| Lexar                       | 8         | 8      | 0.33%   |
| Gigabyte Technology         | 8         | 8      | 0.33%   |
| ADATA Technology            | 8         | 10     | 0.33%   |
| SABRENT                     | 7         | 10     | 0.29%   |
| OCZ                         | 7         | 8      | 0.29%   |
| MAXIO Technology (Hangzhou) | 7         | 9      | 0.29%   |
| FORESEE                     | 7         | 8      | 0.29%   |
| ASMT                        | 7         | 9      | 0.29%   |
| Transcend                   | 6         | 6      | 0.25%   |
| Realtek Semiconductor       | 6         | 7      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 58        | 2.21%   |
| Kingston SA400S37240G 240GB SSD                       | 31        | 1.18%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 28        | 1.07%   |
| Unknown MMC Card  64GB                                | 23        | 0.88%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 22        | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                        | 20        | 0.76%   |
| Kingston SA400S37480G 480GB SSD                       | 18        | 0.69%   |
| Samsung SSD 850 EVO 250GB                             | 17        | 0.65%   |
| Samsung SSD 980 1TB                                   | 16        | 0.61%   |
| Unknown                                               | 15        | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 14        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                        | 14        | 0.53%   |
| Samsung SSD 860 EVO 500GB                             | 14        | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 14        | 0.53%   |
| Unknown MMC Card  128GB                               | 13        | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 13        | 0.49%   |
| Phison E12 NVMe Controller 1TB                        | 13        | 0.49%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 12        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                          | 12        | 0.46%   |
| Toshiba MQ01ABF050 500GB                              | 11        | 0.42%   |
| Samsung SSD 870 EVO 1TB                               | 11        | 0.42%   |
| Unknown MMC Card  32GB                                | 10        | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB                        | 10        | 0.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 10        | 0.38%   |
| SanDisk NVMe SSD Drive 512GB                          | 10        | 0.38%   |
| Samsung SSD 870 EVO 500GB                             | 10        | 0.38%   |
| Crucial CT240BX500SSD1 240GB                          | 10        | 0.38%   |
| Seagate ST500LT012-1DG142 500GB                       | 9         | 0.34%   |
| SanDisk NVMe SSD Drive 1TB                            | 9         | 0.34%   |
| Samsung SSD 860 EVO 250GB                             | 9         | 0.34%   |
| Samsung SSD 860 EVO 1TB                               | 9         | 0.34%   |
| Samsung SSD 850 EVO 500GB                             | 9         | 0.34%   |
| Phison PS5013 E13 NVMe Controller 500GB               | 9         | 0.34%   |
| Kingston Company SNV2S1000G 1TB                       | 9         | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                      | 9         | 0.34%   |
| Intel SSD 660P Series 512GB                           | 9         | 0.34%   |
| HGST HTS721010A9E630 1TB                              | 9         | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                           | 9         | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 8         | 0.3%    |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 8         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 255       | 360    | 39.17%  |
| WDC                 | 189       | 288    | 29.03%  |
| Toshiba             | 69        | 87     | 10.6%   |
| Hitachi             | 44        | 56     | 6.76%   |
| Samsung Electronics | 27        | 31     | 4.15%   |
| HGST                | 26        | 38     | 3.99%   |
| Apple               | 8         | 10     | 1.23%   |
| Unknown             | 7         | 8      | 1.08%   |
| Hewlett-Packard     | 4         | 9      | 0.61%   |
| USB3.0              | 3         | 3      | 0.46%   |
| Maxtor              | 2         | 3      | 0.31%   |
| JMicron Technology  | 2         | 2      | 0.31%   |
| Intenso             | 2         | 2      | 0.31%   |
| HGST HTS            | 2         | 2      | 0.31%   |
| ASMT                | 2         | 4      | 0.31%   |
| WD MediaMax         | 1         | 1      | 0.15%   |
| USB                 | 1         | 1      | 0.15%   |
| TO Exter            | 1         | 1      | 0.15%   |
| Shenzhen            | 1         | 2      | 0.15%   |
| OOS16000            | 1         | 1      | 0.15%   |
| NETAPP              | 1         | 12     | 0.15%   |
| Fujitsu             | 1         | 1      | 0.15%   |
| ASMedia             | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 164       | 214    | 21.69%  |
| Kingston            | 95        | 112    | 12.57%  |
| Crucial             | 71        | 83     | 9.39%   |
| SanDisk             | 69        | 83     | 9.13%   |
| WDC                 | 38        | 46     | 5.03%   |
| China               | 26        | 32     | 3.44%   |
| SK hynix            | 19        | 21     | 2.51%   |
| Intel               | 18        | 21     | 2.38%   |
| Apple               | 17        | 19     | 2.25%   |
| Micron Technology   | 16        | 25     | 2.12%   |
| A-DATA Technology   | 13        | 18     | 1.72%   |
| Intenso             | 11        | 15     | 1.46%   |
| PNY                 | 10        | 13     | 1.32%   |
| Patriot             | 10        | 10     | 1.32%   |
| LITEON              | 8         | 11     | 1.06%   |
| Unknown             | 8         | 8      | 1.06%   |
| SPCC                | 7         | 7      | 0.93%   |
| SABRENT             | 7         | 10     | 0.93%   |
| OCZ                 | 7         | 8      | 0.93%   |
| Toshiba             | 6         | 7      | 0.79%   |
| LITEONIT            | 6         | 7      | 0.79%   |
| Gigabyte Technology | 6         | 6      | 0.79%   |
| Apacer              | 6         | 7      | 0.79%   |
| Team                | 5         | 5      | 0.66%   |
| Netac               | 5         | 5      | 0.66%   |
| Lexar               | 5         | 5      | 0.66%   |
| KingSpec            | 5         | 6      | 0.66%   |
| GOODRAM             | 5         | 6      | 0.66%   |
| ASMT                | 5         | 5      | 0.66%   |
| Transcend           | 4         | 4      | 0.53%   |
| OWC                 | 4         | 8      | 0.53%   |
| Hewlett-Packard     | 4         | 4      | 0.53%   |
| Smartbuy            | 3         | 4      | 0.4%    |
| Verbatim            | 2         | 7      | 0.26%   |
| Vaseky              | 2         | 2      | 0.26%   |
| Plextor             | 2         | 2      | 0.26%   |
| KingDian            | 2         | 2      | 0.26%   |
| Kingchuxing         | 2         | 2      | 0.26%   |
| INNOVATION IT       | 2         | 2      | 0.26%   |
| Gigastone           | 2         | 2      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 846       | 1096   | 38.72%  |
| SSD     | 667       | 919    | 30.53%  |
| HDD     | 563       | 924    | 25.77%  |
| MMC     | 77        | 98     | 3.52%   |
| Unknown | 32        | 75     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 997       | 1718   | 49.21%  |
| NVMe | 844       | 1083   | 41.66%  |
| SAS  | 108       | 213    | 5.33%   |
| MMC  | 77        | 98     | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 712       | 997    | 54.9%   |
| 0.51-1.0   | 367       | 460    | 28.3%   |
| 1.01-2.0   | 114       | 164    | 8.79%   |
| 3.01-4.0   | 51        | 82     | 3.93%   |
| 4.01-10.0  | 28        | 67     | 2.16%   |
| 2.01-3.0   | 17        | 20     | 1.31%   |
| 10.01-20.0 | 8         | 53     | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 480       | 27.49%  |
| 251-500        | 458       | 26.23%  |
| 501-1000       | 312       | 17.87%  |
| 1001-2000      | 122       | 6.99%   |
| 51-100         | 89        | 5.1%    |
| More than 3000 | 87        | 4.98%   |
| 1-20           | 80        | 4.58%   |
| 2001-3000      | 55        | 3.15%   |
| 21-50          | 52        | 2.98%   |
| Unknown        | 11        | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 526       | 29.65%  |
| 21-50          | 462       | 26.04%  |
| 101-250        | 226       | 12.74%  |
| 51-100         | 226       | 12.74%  |
| 251-500        | 145       | 8.17%   |
| 501-1000       | 78        | 4.4%    |
| 1001-2000      | 42        | 2.37%   |
| More than 3000 | 35        | 1.97%   |
| 2001-3000      | 23        | 1.3%    |
| Unknown        | 11        | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB            | 3         | 3      | 3.95%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 2      | 2.63%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 2      | 2.63%   |
| WDC WD6400AACS-00G8B1 640GB         | 1         | 1      | 1.32%   |
| WDC WD60EFRX-68L0BN1 6TB            | 1         | 1      | 1.32%   |
| WDC WD5000LPCX-75VHAT0 500GB        | 1         | 1      | 1.32%   |
| WDC WD5000HHTZ-04N21V0 500GB        | 1         | 1      | 1.32%   |
| WDC WD5000AZLX-22JKKA0 500GB        | 1         | 1      | 1.32%   |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1      | 1.32%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 1.32%   |
| WDC WD2500AAKX-753CA1 250GB         | 1         | 1      | 1.32%   |
| WDC WD2500AAJS-75M0A0 249GB         | 1         | 1      | 1.32%   |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 1.32%   |
| WDC WD10EZRZ-00HTKB0 1TB            | 1         | 1      | 1.32%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1         | 1      | 1.32%   |
| WDC WD10EZEX-22MFCA0 1TB            | 1         | 2      | 1.32%   |
| WDC WD10EARS-22Y5B1 1TB             | 1         | 1      | 1.32%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 1      | 1.32%   |
| WDC WD1003FBYX-01Y7B0 1TB           | 1         | 1      | 1.32%   |
| WDC WD Green M.2 2280 240GB         | 1         | 1      | 1.32%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.32%   |
| Toshiba MK6475GSX 640GB             | 1         | 1      | 1.32%   |
| Toshiba MK5065GSXF 500GB            | 1         | 1      | 1.32%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 1.32%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1      | 1.32%   |
| SSSTC CA6-8D2048-Q11 NVMe 2048GB    | 1         | 1      | 1.32%   |
| SK hynix SC308 SATA 256GB SSD       | 1         | 1      | 1.32%   |
| SK hynix PC711 HFS001TDE9X073N 1TB  | 1         | 1      | 1.32%   |
| SK hynix BC711 HFM001TD3JX013N 1TB  | 1         | 1      | 1.32%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 1.32%   |
| Seagate ST8000DM0004-1ZC11G 8TB     | 1         | 1      | 1.32%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.32%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.32%   |
| Seagate ST3500418AS 500GB           | 1         | 1      | 1.32%   |
| Seagate ST320LT007-9ZV142 320GB     | 1         | 1      | 1.32%   |
| Seagate ST2000LX001-1RG174 2TB      | 1         | 1      | 1.32%   |
| Seagate ST2000LM007-1R8174 2TB      | 1         | 1      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 18     | 22.37%  |
| Seagate             | 14        | 14     | 18.42%  |
| Toshiba             | 7         | 7      | 9.21%   |
| Hitachi             | 5         | 6      | 6.58%   |
| HGST                | 5         | 5      | 6.58%   |
| SanDisk             | 4         | 4      | 5.26%   |
| Samsung Electronics | 4         | 4      | 5.26%   |
| Crucial             | 4         | 4      | 5.26%   |
| SK hynix            | 3         | 3      | 3.95%   |
| Kingston            | 3         | 3      | 3.95%   |
| Intel               | 2         | 2      | 2.63%   |
| SSSTC               | 1         | 1      | 1.32%   |
| Patriot             | 1         | 1      | 1.32%   |
| Neo                 | 1         | 2      | 1.32%   |
| Maxtor              | 1         | 2      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| Gigabyte Technology | 1         | 1      | 1.32%   |
| Fujitsu             | 1         | 1      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 17     | 31.37%  |
| Seagate             | 14        | 14     | 27.45%  |
| Toshiba             | 7         | 7      | 13.73%  |
| Hitachi             | 5         | 6      | 9.8%    |
| HGST                | 5         | 5      | 9.8%    |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Maxtor              | 1         | 2      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 54     | 66.67%  |
| SSD  | 20        | 21     | 26.67%  |
| NVMe | 5         | 5      | 6.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba NVMe SSD Drive 256GB    | 1         | 1      | 20%     |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 20%     |
| Seagate ST31000528AS 1TB        | 1         | 1      | 20%     |
| KingDian S400 120GB             | 1         | 1      | 20%     |
| Hitachi HUS724040ALE640 4TB     | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 40%     |
| Toshiba  | 1         | 1      | 20%     |
| KingDian | 1         | 1      | 20%     |
| Hitachi  | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1153      | 2158   | 64.34%  |
| Works    | 563       | 869    | 31.42%  |
| Malfunc  | 71        | 80     | 3.96%   |
| Failed   | 5         | 5      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1078      | 46.75%  |
| AMD                                     | 280       | 12.14%  |
| Samsung Electronics                     | 267       | 11.58%  |
| Sandisk                                 | 123       | 5.33%   |
| SK hynix                                | 76        | 3.3%    |
| Micron Technology                       | 67        | 2.91%   |
| Kingston Technology Company             | 57        | 2.47%   |
| Phison Electronics                      | 54        | 2.34%   |
| Micron/Crucial Technology               | 41        | 1.78%   |
| KIOXIA                                  | 35        | 1.52%   |
| Toshiba America Info Systems            | 30        | 1.3%    |
| ASMedia Technology                      | 27        | 1.17%   |
| Silicon Motion                          | 18        | 0.78%   |
| Nvidia                                  | 15        | 0.65%   |
| Marvell Technology Group                | 14        | 0.61%   |
| ADATA Technology                        | 14        | 0.61%   |
| Union Memory (Shenzhen)                 | 11        | 0.48%   |
| Shenzhen Longsys Electronics            | 11        | 0.48%   |
| MAXIO Technology (Hangzhou)             | 11        | 0.48%   |
| JMicron Technology                      | 11        | 0.48%   |
| Realtek Semiconductor                   | 10        | 0.43%   |
| Apple                                   | 8         | 0.35%   |
| Solid State Storage Technology          | 7         | 0.3%    |
| Seagate Technology                      | 7         | 0.3%    |
| LSI Logic / Symbios Logic               | 5         | 0.22%   |
| Broadcom / LSI                          | 4         | 0.17%   |
| Zhaoxin                                 | 3         | 0.13%   |
| Yangtze Memory Technologies             | 3         | 0.13%   |
| Solidigm                                | 3         | 0.13%   |
| Netac Technology                        | 3         | 0.13%   |
| Lenovo                                  | 3         | 0.13%   |
| Hewlett-Packard                         | 2         | 0.09%   |
| VIA Technologies                        | 1         | 0.04%   |
| Transcend                               | 1         | 0.04%   |
| Silicon Image                           | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| OCZ Technology Group                    | 1         | 0.04%   |
| Lite-On Technology                      | 1         | 0.04%   |
| INNOGRIT                                | 1         | 0.04%   |
| Biwin Storage Technology                | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 173       | 6.77%   |
| Intel Volume Management Device NVMe RAID Controller                            | 114       | 4.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 101       | 3.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 93        | 3.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 64        | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 61        | 2.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 59        | 2.31%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 54        | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 48        | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 44        | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 35        | 1.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 35        | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 35        | 1.37%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 33        | 1.29%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 32        | 1.25%   |
| AMD 500 Series Chipset SATA Controller                                         | 32        | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 30        | 1.17%   |
| AMD 600 Series Chipset SATA Controller                                         | 30        | 1.17%   |
| AMD 400 Series Chipset SATA Controller                                         | 30        | 1.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 29        | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 28        | 1.1%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 28        | 1.1%    |
| Intel SATA Controller [RAID mode]                                              | 26        | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 26        | 1.02%   |
| Intel Tiger Lake-LP SATA Controller                                            | 25        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                          | 25        | 0.98%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 25        | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 23        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 23        | 0.9%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 21        | 0.82%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 21        | 0.82%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 20        | 0.78%   |
| Intel RST Volume Management Device Controller                                  | 20        | 0.78%   |
| Phison E12 NVMe Controller                                                     | 19        | 0.74%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 19        | 0.74%   |
| Intel SSD 660P Series                                                          | 19        | 0.74%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 18        | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 0.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 17        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1140      | 49.33%  |
| NVMe | 842       | 36.43%  |
| RAID | 217       | 9.39%   |
| IDE  | 107       | 4.63%   |
| SAS  | 4         | 0.17%   |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 1286      | 75.47%  |
| AMD           | 405       | 23.77%  |
| ARM           | 9         | 0.53%   |
| CentaurHauls  | 3         | 0.18%   |
| sifive,u74-mc | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 27        | 1.58%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 27        | 1.58%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 20        | 1.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 19        | 1.11%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 16        | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 15        | 0.88%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 15        | 0.88%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 14        | 0.82%   |
| Intel 12th Gen Core i7-12700H           | 14        | 0.82%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 14        | 0.82%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 13        | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 13        | 0.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 13        | 0.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 12        | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 12        | 0.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 12        | 0.7%    |
| AMD Ryzen 5 3600 6-Core Processor       | 12        | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 11        | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 11        | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 11        | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 11        | 0.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 11        | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 0.59%   |
| Intel 12th Gen Core i5-1240P            | 10        | 0.59%   |
| AMD Ryzen 5 5625U with Radeon Graphics  | 10        | 0.59%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 10        | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 9         | 0.53%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 9         | 0.53%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 9         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 9         | 0.53%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 9         | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 9         | 0.53%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 9         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 8         | 0.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 8         | 0.47%   |
| Intel 12th Gen Core i7-1260P            | 8         | 0.47%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 8         | 0.47%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 8         | 0.47%   |
| ARM Processor                           | 8         | 0.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 8         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 397       | 23.28%  |
| Other                   | 290       | 17.01%  |
| Intel Core i7           | 277       | 16.25%  |
| AMD Ryzen 5             | 113       | 6.63%   |
| AMD Ryzen 7             | 112       | 6.57%   |
| Intel Core i3           | 104       | 6.1%    |
| Intel Celeron           | 62        | 3.64%   |
| AMD Ryzen 9             | 49        | 2.87%   |
| Intel Core 2 Duo        | 48        | 2.82%   |
| Intel Xeon              | 46        | 2.7%    |
| Intel Pentium           | 25        | 1.47%   |
| AMD Ryzen 3             | 18        | 1.06%   |
| AMD A8                  | 15        | 0.88%   |
| AMD Ryzen 7 PRO         | 10        | 0.59%   |
| Intel Pentium Silver    | 9         | 0.53%   |
| Intel Pentium Dual-Core | 9         | 0.53%   |
| AMD Ryzen 5 PRO         | 9         | 0.53%   |
| Intel Atom              | 8         | 0.47%   |
| AMD FX                  | 7         | 0.41%   |
| AMD A4                  | 7         | 0.41%   |
| AMD A10                 | 7         | 0.41%   |
| Intel Core i9           | 6         | 0.35%   |
| Intel Core 2 Quad       | 6         | 0.35%   |
| AMD Athlon II X2        | 6         | 0.35%   |
| AMD A6                  | 6         | 0.35%   |
| AMD E2                  | 5         | 0.29%   |
| AMD Phenom II X4        | 4         | 0.23%   |
| AMD Athlon X4           | 4         | 0.23%   |
| Intel Pentium Dual      | 3         | 0.18%   |
| Intel Core M            | 3         | 0.18%   |
| AMD Ryzen Threadripper  | 3         | 0.18%   |
| AMD E                   | 3         | 0.18%   |
| AMD Athlon 64 X2        | 3         | 0.18%   |
| AMD Athlon              | 3         | 0.18%   |
| Intel Genuine           | 2         | 0.12%   |
| Intel Core 2            | 2         | 0.12%   |
| AMD Turion 64 X2 Mobile | 2         | 0.12%   |
| AMD Phenom II X6        | 2         | 0.12%   |
| AMD Phenom II X2        | 2         | 0.12%   |
| Intel Xeon Silver       | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 576       | 33.78%  |
| 2       | 540       | 31.67%  |
| 6       | 207       | 12.14%  |
| 8       | 179       | 10.5%   |
| 12      | 69        | 4.05%   |
| 14      | 43        | 2.52%   |
| 10      | 32        | 1.88%   |
| 16      | 19        | 1.11%   |
| 24      | 11        | 0.65%   |
| 1       | 8         | 0.47%   |
| 3       | 5         | 0.29%   |
| Unknown | 5         | 0.29%   |
| 32      | 4         | 0.23%   |
| 20      | 2         | 0.12%   |
| 52      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |
| 7       | 1         | 0.06%   |
| 5       | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1681      | 98.65%  |
| 2       | 18        | 1.06%   |
| Unknown | 5         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1249      | 73.26%  |
| 1       | 451       | 26.45%  |
| Unknown | 5         | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1700      | 99.77%  |
| 64-bit         | 2         | 0.12%   |
| Unknown        | 2         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1488      | 87.02%  |
| 0x0a50000d | 31        | 1.81%   |
| 0x0a601203 | 22        | 1.29%   |
| 0x08608103 | 17        | 0.99%   |
| 0x0a50000c | 14        | 0.82%   |
| 0x0a404102 | 14        | 0.82%   |
| 0x08600106 | 12        | 0.7%    |
| 0x906a3    | 5         | 0.29%   |
| 0x0a404101 | 5         | 0.29%   |
| 0x0a20120a | 5         | 0.29%   |
| 0x08701021 | 5         | 0.29%   |
| 0x08108109 | 5         | 0.29%   |
| 0x0a704101 | 4         | 0.23%   |
| 0x0800820d | 4         | 0.23%   |
| 0x010000c8 | 4         | 0.23%   |
| 0x806ec    | 3         | 0.18%   |
| 0x08a00006 | 3         | 0.18%   |
| 0x08608104 | 3         | 0.18%   |
| 0x08608102 | 3         | 0.18%   |
| 0x08600109 | 3         | 0.18%   |
| 0x08600104 | 3         | 0.18%   |
| 0x08101016 | 3         | 0.18%   |
| 0x306a9    | 2         | 0.12%   |
| 0x0a704103 | 2         | 0.12%   |
| 0x0a50000b | 2         | 0.12%   |
| 0x0a201025 | 2         | 0.12%   |
| 0x08a00008 | 2         | 0.12%   |
| 0x08701030 | 2         | 0.12%   |
| 0x08600103 | 2         | 0.12%   |
| 0x08200103 | 2         | 0.12%   |
| 0x08108102 | 2         | 0.12%   |
| 0x0810100b | 2         | 0.12%   |
| 0x08101007 | 2         | 0.12%   |
| 0x07030105 | 2         | 0.12%   |
| 0x06001119 | 2         | 0.12%   |
| 0xf64      | 1         | 0.06%   |
| 0x906ea    | 1         | 0.06%   |
| 0x90675    | 1         | 0.06%   |
| 0x806eb    | 1         | 0.06%   |
| 0x806d1    | 1         | 0.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 265       | 15.49%  |
| Unknown          | 217       | 12.68%  |
| Haswell          | 131       | 7.66%   |
| Skylake          | 116       | 6.78%   |
| IvyBridge        | 105       | 6.14%   |
| Zen 3            | 99        | 5.79%   |
| TigerLake        | 99        | 5.79%   |
| SandyBridge      | 92        | 5.38%   |
| Alderlake Hybrid | 85        | 4.97%   |
| Zen 2            | 64        | 3.74%   |
| Penryn           | 56        | 3.27%   |
| Broadwell        | 50        | 2.92%   |
| CometLake        | 34        | 1.99%   |
| Zen+             | 32        | 1.87%   |
| Icelake          | 32        | 1.87%   |
| Westmere         | 30        | 1.75%   |
| Goldmont plus    | 30        | 1.75%   |
| Silvermont       | 26        | 1.52%   |
| Piledriver       | 21        | 1.23%   |
| Zen              | 18        | 1.05%   |
| K10              | 18        | 1.05%   |
| Core             | 16        | 0.94%   |
| Excavator        | 13        | 0.76%   |
| Nehalem          | 12        | 0.7%    |
| Goldmont         | 10        | 0.58%   |
| Puma             | 7         | 0.41%   |
| K8 Hammer        | 6         | 0.35%   |
| Jaguar           | 5         | 0.29%   |
| Steamroller      | 4         | 0.23%   |
| K10 Llano        | 4         | 0.23%   |
| Bobcat           | 4         | 0.23%   |
| Tremont          | 3         | 0.18%   |
| NetBurst         | 2         | 0.12%   |
| Gracemont        | 2         | 0.12%   |
| Bulldozer        | 2         | 0.12%   |
| Bonnell          | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1047      | 51.22%  |
| Nvidia                     | 502       | 24.56%  |
| AMD                        | 477       | 23.34%  |
| Matrox Electronics Systems | 9         | 0.44%   |
| ASPEED Technology          | 5         | 0.24%   |
| Zhaoxin                    | 3         | 0.15%   |
| Silicon Motion             | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 82        | 3.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 70        | 3.38%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 56        | 2.7%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 48        | 2.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 45        | 2.17%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                     | 45        | 2.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 45        | 2.17%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 41        | 1.98%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 41        | 1.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 35        | 1.69%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 35        | 1.69%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 33        | 1.59%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 33        | 1.59%   |
| AMD Lucienne                                                                | 33        | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 32        | 1.54%   |
| AMD Rembrandt [Radeon 680M]                                                 | 29        | 1.4%    |
| AMD Raphael                                                                 | 28        | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 27        | 1.3%    |
| AMD Barcelo                                                                 | 27        | 1.3%    |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 26        | 1.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 26        | 1.25%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 25        | 1.21%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 23        | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 21        | 1.01%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 21        | 1.01%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 18        | 0.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 18        | 0.87%   |
| Intel Core Processor Integrated Graphics Controller                         | 17        | 0.82%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 16        | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 16        | 0.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 15        | 0.72%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 15        | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 15        | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 15        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 15        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 14        | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 14        | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 13        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 13        | 0.63%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 12        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| 1 x Intel           | 749       | 43.85%  |
| 1 x AMD             | 369       | 21.6%   |
| Intel + Nvidia      | 230       | 13.47%  |
| 1 x Nvidia          | 208       | 12.18%  |
| AMD + Nvidia        | 54        | 3.16%   |
| Intel + AMD         | 41        | 2.4%    |
| 2 x AMD             | 13        | 0.76%   |
| Other               | 12        | 0.7%    |
| 2 x Intel           | 7         | 0.41%   |
| 1 x Matrox          | 7         | 0.41%   |
| 2 x Nvidia          | 3         | 0.18%   |
| 1 x Zhaoxin         | 3         | 0.18%   |
| Intel + 2 x Nvidia  | 3         | 0.18%   |
| Nvidia + Matrox     | 2         | 0.12%   |
| Intel + ASPEED      | 2         | 0.12%   |
| 1 x ASPEED          | 2         | 0.12%   |
| 2 x Intel + 1 x AMD | 1         | 0.06%   |
| 1 x Silicon Motion  | 1         | 0.06%   |
| AMD + ASPEED        | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1403      | 81.81%  |
| Proprietary | 256       | 14.93%  |
| Unknown     | 56        | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1386      | 80.77%  |
| 0.01-0.5   | 117       | 6.82%   |
| 1.01-2.0   | 72        | 4.2%    |
| 3.01-4.0   | 45        | 2.62%   |
| 0.51-1.0   | 37        | 2.16%   |
| 7.01-8.0   | 32        | 1.86%   |
| 5.01-6.0   | 11        | 0.64%   |
| 8.01-16.0  | 8         | 0.47%   |
| 16.01-24.0 | 7         | 0.41%   |
| 2.01-3.0   | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 238       | 12.58%  |
| Samsung Electronics     | 223       | 11.79%  |
| BOE                     | 205       | 10.84%  |
| Chimei Innolux          | 158       | 8.35%   |
| LG Display              | 139       | 7.35%   |
| Dell                    | 106       | 5.6%    |
| Goldstar                | 103       | 5.44%   |
| Hewlett-Packard         | 63        | 3.33%   |
| Acer                    | 58        | 3.07%   |
| Apple                   | 50        | 2.64%   |
| Sharp                   | 40        | 2.11%   |
| AOC                     | 39        | 2.06%   |
| Philips                 | 36        | 1.9%    |
| Ancor Communications    | 36        | 1.9%    |
| Lenovo                  | 31        | 1.64%   |
| BenQ                    | 31        | 1.64%   |
| Iiyama                  | 29        | 1.53%   |
| CSO                     | 21        | 1.11%   |
| InfoVision              | 20        | 1.06%   |
| PANDA                   | 19        | 1%      |
| ASUSTek Computer        | 19        | 1%      |
| ViewSonic               | 18        | 0.95%   |
| Sony                    | 14        | 0.74%   |
| Chi Mei Optoelectronics | 11        | 0.58%   |
| MSI                     | 10        | 0.53%   |
| HKC                     | 8         | 0.42%   |
| Panasonic               | 7         | 0.37%   |
| Unknown                 | 6         | 0.32%   |
| MiTAC                   | 6         | 0.32%   |
| Vestel Elektronik       | 5         | 0.26%   |
| NEC Computers           | 5         | 0.26%   |
| Medion                  | 5         | 0.26%   |
| Hitachi                 | 5         | 0.26%   |
| Fujitsu Siemens         | 5         | 0.26%   |
| TMX                     | 4         | 0.21%   |
| Mi                      | 4         | 0.21%   |
| LG Philips              | 4         | 0.21%   |
| Eizo                    | 4         | 0.21%   |
| Denver                  | 4         | 0.21%   |
| Unknown                 | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 12        | 0.62%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 10        | 0.52%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 8         | 0.41%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 8         | 0.41%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 7         | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.36%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                    | 7         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 7         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 6         | 0.31%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch     | 5         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 5         | 0.26%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 5         | 0.26%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 5         | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                    | 5         | 0.26%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch    | 4         | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 4         | 0.21%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.21%   |
| MiTAC MTC26T42 MTC0B01 1280x720 708x398mm 32.0-inch                      | 4         | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 4         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                  | 4         | 0.21%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                       | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch          | 4         | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 4         | 0.21%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                    | 4         | 0.21%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 4         | 0.21%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 4         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 818       | 45.65%  |
| 1366x768 (WXGA)    | 252       | 14.06%  |
| 3840x2160 (4K)     | 158       | 8.82%   |
| 2560x1440 (QHD)    | 108       | 6.03%   |
| 1920x1200 (WUXGA)  | 65        | 3.63%   |
| 1600x900 (HD+)     | 51        | 2.85%   |
| 2560x1600          | 39        | 2.18%   |
| 1440x900 (WXGA+)   | 37        | 2.06%   |
| 2880x1800          | 31        | 1.73%   |
| 3440x1440          | 30        | 1.67%   |
| 1680x1050 (WSXGA+) | 28        | 1.56%   |
| 1280x800 (WXGA)    | 25        | 1.4%    |
| 1280x1024 (SXGA)   | 19        | 1.06%   |
| 3840x2400          | 17        | 0.95%   |
| 2560x1080          | 12        | 0.67%   |
| 2160x1440          | 11        | 0.61%   |
| 2880x1920          | 9         | 0.5%    |
| 3840x1080          | 8         | 0.45%   |
| 1920x540           | 8         | 0.45%   |
| 3840x1600          | 5         | 0.28%   |
| 2240x1400          | 5         | 0.28%   |
| Unknown            | 5         | 0.28%   |
| 3456x2160          | 4         | 0.22%   |
| 3000x2000          | 4         | 0.22%   |
| 2256x1504          | 4         | 0.22%   |
| 1920x1280          | 4         | 0.22%   |
| 1360x768           | 4         | 0.22%   |
| 1280x720 (HD)      | 4         | 0.22%   |
| 1024x768 (XGA)     | 4         | 0.22%   |
| 3200x1800 (QHD+)   | 3         | 0.17%   |
| 3200x2000          | 2         | 0.11%   |
| 3072x1920          | 2         | 0.11%   |
| 2736x1824          | 2         | 0.11%   |
| 2520x1680          | 2         | 0.11%   |
| 5760x2160          | 1         | 0.06%   |
| 3600x1080          | 1         | 0.06%   |
| 3240x2160          | 1         | 0.06%   |
| 2880x1620          | 1         | 0.06%   |
| 2304x1440          | 1         | 0.06%   |
| 2160x1350          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 432       | 22.92%  |
| 13      | 229       | 12.15%  |
| 14      | 192       | 10.19%  |
| 27      | 155       | 8.22%   |
| 24      | 129       | 6.84%   |
| 23      | 105       | 5.57%   |
| 17      | 84        | 4.46%   |
| 21      | 81        | 4.3%    |
| 31      | 72        | 3.82%   |
| 16      | 43        | 2.28%   |
| 34      | 34        | 1.8%    |
| Unknown | 33        | 1.75%   |
| 19      | 30        | 1.59%   |
| 12      | 29        | 1.54%   |
| 20      | 27        | 1.43%   |
| 18      | 23        | 1.22%   |
| 84      | 22        | 1.17%   |
| 22      | 21        | 1.11%   |
| 11      | 20        | 1.06%   |
| 40      | 12        | 0.64%   |
| 32      | 11        | 0.58%   |
| 25      | 10        | 0.53%   |
| 72      | 9         | 0.48%   |
| 65      | 7         | 0.37%   |
| 48      | 7         | 0.37%   |
| 26      | 7         | 0.37%   |
| 54      | 6         | 0.32%   |
| 28      | 6         | 0.32%   |
| 49      | 5         | 0.27%   |
| 35      | 5         | 0.27%   |
| 42      | 4         | 0.21%   |
| 37      | 4         | 0.21%   |
| 29      | 4         | 0.21%   |
| 63      | 3         | 0.16%   |
| 52      | 3         | 0.16%   |
| 46      | 3         | 0.16%   |
| 60      | 2         | 0.11%   |
| 47      | 2         | 0.11%   |
| 10      | 2         | 0.11%   |
| 7       | 2         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 736       | 39.66%  |
| 501-600     | 371       | 19.99%  |
| 201-300     | 198       | 10.67%  |
| 401-500     | 170       | 9.16%   |
| 351-400     | 102       | 5.5%    |
| 601-700     | 95        | 5.12%   |
| 701-800     | 47        | 2.53%   |
| 1001-1500   | 40        | 2.16%   |
| 1501-2000   | 33        | 1.78%   |
| Unknown     | 33        | 1.78%   |
| 801-900     | 21        | 1.13%   |
| 901-1000    | 6         | 0.32%   |
| 101-200     | 4         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1268      | 75.07%  |
| 16/10   | 269       | 15.93%  |
| 21/9    | 45        | 2.66%   |
| 3/2     | 40        | 2.37%   |
| Unknown | 23        | 1.36%   |
| 5/4     | 21        | 1.24%   |
| 32/9    | 13        | 0.77%   |
| 4/3     | 8         | 0.47%   |
| 6/5     | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 433       | 23.07%  |
| 81-90          | 315       | 16.78%  |
| 201-250        | 255       | 13.59%  |
| 301-350        | 161       | 8.58%   |
| 351-500        | 129       | 6.87%   |
| 71-80          | 101       | 5.38%   |
| 151-200        | 83        | 4.42%   |
| 121-130        | 67        | 3.57%   |
| 251-300        | 65        | 3.46%   |
| More than 1000 | 60        | 3.2%    |
| 111-120        | 39        | 2.08%   |
| 501-1000       | 35        | 1.86%   |
| Unknown        | 33        | 1.76%   |
| 141-150        | 29        | 1.55%   |
| 61-70          | 28        | 1.49%   |
| 51-60          | 21        | 1.12%   |
| 131-140        | 10        | 0.53%   |
| 91-100         | 8         | 0.43%   |
| 1-40           | 3         | 0.16%   |
| 41-50          | 2         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 547       | 29.87%  |
| 121-160       | 531       | 29%     |
| 101-120       | 396       | 21.63%  |
| 161-240       | 200       | 10.92%  |
| More than 240 | 88        | 4.81%   |
| 1-50          | 36        | 1.97%   |
| Unknown       | 33        | 1.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1342      | 77.71%  |
| 2     | 264       | 15.29%  |
| 0     | 81        | 4.69%   |
| 3     | 37        | 2.14%   |
| 4     | 3         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 897       | 35.11%  |
| Intel                             | 882       | 34.52%  |
| Qualcomm Atheros                  | 184       | 7.2%    |
| Broadcom                          | 131       | 5.13%   |
| MediaTek                          | 107       | 4.19%   |
| TP-Link                           | 36        | 1.41%   |
| Broadcom Limited                  | 25        | 0.98%   |
| ASIX Electronics                  | 23        | 0.9%    |
| Ralink Technology                 | 20        | 0.78%   |
| Marvell Technology Group          | 20        | 0.78%   |
| Ralink                            | 15        | 0.59%   |
| DisplayLink                       | 15        | 0.59%   |
| Lenovo                            | 13        | 0.51%   |
| Nvidia                            | 12        | 0.47%   |
| Shenzhen Goodix Technology        | 11        | 0.43%   |
| Sierra Wireless                   | 10        | 0.39%   |
| Xiaomi                            | 9         | 0.35%   |
| Samsung Electronics               | 9         | 0.35%   |
| NetGear                           | 9         | 0.35%   |
| Microsoft                         | 8         | 0.31%   |
| D-Link                            | 8         | 0.31%   |
| Aquantia                          | 8         | 0.31%   |
| Qualcomm                          | 7         | 0.27%   |
| Huawei Technologies               | 6         | 0.23%   |
| Qualcomm Atheros Communications   | 5         | 0.2%    |
| Google                            | 5         | 0.2%    |
| Edimax Technology                 | 5         | 0.2%    |
| Dell                              | 5         | 0.2%    |
| D-Link System                     | 5         | 0.2%    |
| ASUSTek Computer                  | 5         | 0.2%    |
| Apple                             | 5         | 0.2%    |
| Hewlett-Packard                   | 4         | 0.16%   |
| Ericsson Business Mobile Networks | 4         | 0.16%   |
| Dresden Elektronik                | 4         | 0.16%   |
| Mellanox Technologies             | 3         | 0.12%   |
| JMicron Technology                | 3         | 0.12%   |
| TRENDnet                          | 2         | 0.08%   |
| QinHeng Electronics               | 2         | 0.08%   |
| Motorola PCS                      | 2         | 0.08%   |
| AVM                               | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 545       | 18.2%   |
| Intel Wi-Fi 6 AX201                                                    | 81        | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 74        | 2.47%   |
| Intel Wireless 8265 / 8275                                             | 69        | 2.3%    |
| Intel Wi-Fi 6 AX200                                                    | 69        | 2.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 66        | 2.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 59        | 1.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 59        | 1.97%   |
| Realtek RTL8125 2.5GbE Controller                                      | 55        | 1.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 45        | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 1.4%    |
| Intel Wireless 7265                                                    | 39        | 1.3%    |
| Intel Wireless 8260                                                    | 37        | 1.24%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 36        | 1.2%    |
| Intel Ethernet Controller I225-V                                       | 34        | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 33        | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 32        | 1.07%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 30        | 1%      |
| Intel Ethernet Connection (4) I219-LM                                  | 29        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 29        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 28        | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 28        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 27        | 0.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 23        | 0.77%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 23        | 0.77%   |
| Intel Ethernet Connection I219-LM                                      | 23        | 0.77%   |
| Intel Ethernet Connection I217-LM                                      | 23        | 0.77%   |
| Intel I211 Gigabit Network Connection                                  | 22        | 0.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 22        | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                          | 22        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 21        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 21        | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 20        | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 20        | 0.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 19        | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 18        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 17        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                          | 16        | 0.53%   |
| Realtek Killer E2600 GbE Controller                                    | 15        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 677       | 46.72%  |
| Realtek Semiconductor           | 258       | 17.81%  |
| Qualcomm Atheros                | 156       | 10.77%  |
| MediaTek                        | 97        | 6.69%   |
| Broadcom                        | 91        | 6.28%   |
| TP-Link                         | 34        | 2.35%   |
| Ralink Technology               | 20        | 1.38%   |
| Broadcom Limited                | 19        | 1.31%   |
| Ralink                          | 15        | 1.04%   |
| Sierra Wireless                 | 10        | 0.69%   |
| NetGear                         | 9         | 0.62%   |
| Microsoft                       | 8         | 0.55%   |
| D-Link                          | 8         | 0.55%   |
| Qualcomm                        | 6         | 0.41%   |
| Qualcomm Atheros Communications | 5         | 0.35%   |
| Edimax Technology               | 5         | 0.35%   |
| ASUSTek Computer                | 5         | 0.35%   |
| Marvell Technology Group        | 3         | 0.21%   |
| Dell                            | 3         | 0.21%   |
| D-Link System                   | 3         | 0.21%   |
| AVM                             | 2         | 0.14%   |
| ZyXEL Communications            | 1         | 0.07%   |
| ZyDAS                           | 1         | 0.07%   |
| Z-Com                           | 1         | 0.07%   |
| TRENDnet                        | 1         | 0.07%   |
| Tenda                           | 1         | 0.07%   |
| Quectel Wireless Solutions      | 1         | 0.07%   |
| Qualcomm Technologies           | 1         | 0.07%   |
| Philips (or NXP)                | 1         | 0.07%   |
| Linksys                         | 1         | 0.07%   |
| IMC Networks                    | 1         | 0.07%   |
| Hewlett-Packard                 | 1         | 0.07%   |
| Guillemot                       | 1         | 0.07%   |
| Fibocom                         | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| AboCom Systems                  | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 81        | 5.54%   |
| Intel Wireless 8265 / 8275                                           | 69        | 4.72%   |
| Intel Wi-Fi 6 AX200                                                  | 69        | 4.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 59        | 4.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 39        | 2.67%   |
| Intel Wireless 7265                                                  | 39        | 2.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 39        | 2.67%   |
| Intel Wireless 8260                                                  | 37        | 2.53%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 36        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 32        | 2.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 31        | 2.12%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 30        | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 29        | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 28        | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 28        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 27        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 23        | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 22        | 1.5%    |
| Intel Raptor Lake PCH CNVi WiFi                                      | 21        | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 21        | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 21        | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 20        | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 20        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 18        | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 17        | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                        | 16        | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 15        | 1.03%   |
| Intel Wireless 7260                                                  | 15        | 1.03%   |
| Realtek 802.11ac NIC                                                 | 14        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 14        | 0.96%   |
| Intel Wireless 3165                                                  | 13        | 0.89%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 13        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 12        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 12        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 12        | 0.82%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 10        | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 10        | 0.68%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 10        | 0.68%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 10        | 0.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 10        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 769       | 52.56%  |
| Intel                                  | 427       | 29.19%  |
| Broadcom                               | 61        | 4.17%   |
| Qualcomm Atheros                       | 44        | 3.01%   |
| ASIX Electronics                       | 23        | 1.57%   |
| Marvell Technology Group               | 17        | 1.16%   |
| DisplayLink                            | 15        | 1.03%   |
| Lenovo                                 | 13        | 0.89%   |
| Nvidia                                 | 12        | 0.82%   |
| MediaTek                               | 10        | 0.68%   |
| Xiaomi                                 | 9         | 0.62%   |
| Samsung Electronics                    | 9         | 0.62%   |
| Aquantia                               | 8         | 0.55%   |
| Broadcom Limited                       | 7         | 0.48%   |
| Google                                 | 5         | 0.34%   |
| Huawei Technologies                    | 4         | 0.27%   |
| Apple                                  | 4         | 0.27%   |
| TP-Link                                | 3         | 0.21%   |
| Mellanox Technologies                  | 3         | 0.21%   |
| JMicron Technology                     | 3         | 0.21%   |
| Motorola PCS                           | 2         | 0.14%   |
| D-Link System                          | 2         | 0.14%   |
| American Megatrends                    | 2         | 0.14%   |
| Vimtron Electronics                    | 1         | 0.07%   |
| TRENDnet                               | 1         | 0.07%   |
| Toshiba                                | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Qualcomm                               | 1         | 0.07%   |
| OPPO Electronics                       | 1         | 0.07%   |
| MosChip Semiconductor                  | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |
| ICS Advent                             | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| 3Com                                   | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 545       | 36.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 74        | 4.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 66        | 4.4%    |
| Realtek RTL8125 2.5GbE Controller                                      | 55        | 3.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 42        | 2.8%    |
| Intel Ethernet Controller I225-V                                       | 34        | 2.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 29        | 1.93%   |
| Intel Ethernet Connection I219-LM                                      | 23        | 1.53%   |
| Intel Ethernet Connection I217-LM                                      | 23        | 1.53%   |
| Intel I211 Gigabit Network Connection                                  | 22        | 1.47%   |
| ASIX AX88179 Gigabit Ethernet                                          | 22        | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 20        | 1.33%   |
| Intel Ethernet Connection (2) I219-V                                   | 19        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 1.07%   |
| Realtek Killer E2600 GbE Controller                                    | 15        | 1%      |
| Intel Ethernet Connection (7) I219-LM                                  | 12        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 0.73%   |
| Intel 82579V Gigabit Network Connection                                | 11        | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 11        | 0.73%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 0.67%   |
| Intel I210 Gigabit Network Connection                                  | 10        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 10        | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                                  | 10        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 0.67%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 8         | 0.53%   |
| Nvidia MCP79 Ethernet                                                  | 8         | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 0.53%   |
| Intel Ethernet Connection (17) I219-V                                  | 8         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                               | 8         | 0.53%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 8         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.47%   |
| Intel Ethernet Connection I217-V                                       | 7         | 0.47%   |
| Intel Ethernet Connection (2) I218-V                                   | 7         | 0.47%   |
| Intel Ethernet Connection (13) I219-V                                  | 7         | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 7         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 7         | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 6         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1376      | 50.11%  |
| Ethernet | 1337      | 48.69%  |
| Modem    | 33        | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1057      | 59.75%  |
| Ethernet | 712       | 40.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 843       | 49.36%  |
| 1     | 786       | 46.02%  |
| 3     | 46        | 2.69%   |
| 0     | 26        | 1.52%   |
| 4     | 3         | 0.18%   |
| 6     | 2         | 0.12%   |
| 5     | 2         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1145      | 66.61%  |
| Yes  | 574       | 33.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 621       | 50%     |
| Realtek Semiconductor           | 145       | 11.67%  |
| Qualcomm Atheros Communications | 68        | 5.48%   |
| Foxconn / Hon Hai               | 58        | 4.67%   |
| IMC Networks                    | 56        | 4.51%   |
| Apple                           | 54        | 4.35%   |
| Cambridge Silicon Radio         | 51        | 4.11%   |
| Broadcom                        | 36        | 2.9%    |
| Lite-On Technology              | 32        | 2.58%   |
| MediaTek                        | 24        | 1.93%   |
| Realtek                         | 22        | 1.77%   |
| ASUSTek Computer                | 16        | 1.29%   |
| TP-Link                         | 10        | 0.81%   |
| Dell                            | 9         | 0.72%   |
| Hewlett-Packard                 | 7         | 0.56%   |
| Toshiba                         | 5         | 0.4%    |
| Ralink                          | 5         | 0.4%    |
| USI                             | 3         | 0.24%   |
| Marvell Semiconductor           | 3         | 0.24%   |
| Opticis                         | 2         | 0.16%   |
| Fujitsu                         | 2         | 0.16%   |
| Edimax Technology               | 2         | 0.16%   |
| Chicony Electronics             | 2         | 0.16%   |
| Alps Electric                   | 2         | 0.16%   |
| Ralink Technology               | 1         | 0.08%   |
| Logitech                        | 1         | 0.08%   |
| Integrated System Solution      | 1         | 0.08%   |
| HTC (High Tech Computer)        | 1         | 0.08%   |
| Dynex                           | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |
| Actions                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 176       | 14.15%  |
| Intel AX201 Bluetooth                               | 163       | 13.1%   |
| Realtek Bluetooth Radio                             | 116       | 9.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 83        | 6.67%   |
| Intel Bluetooth Device                              | 74        | 5.95%   |
| Intel AX200 Bluetooth                               | 64        | 5.14%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 51        | 4.1%    |
| Foxconn / Hon Hai Wireless_Device                   | 29        | 2.33%   |
| Intel AX210 Bluetooth                               | 26        | 2.09%   |
| IMC Networks Wireless_Device                        | 26        | 2.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 25        | 2.01%   |
| MediaTek Wireless_Device                            | 24        | 1.93%   |
| Apple Bluetooth Host Controller                     | 23        | 1.85%   |
| Realtek Bluetooth Radio                             | 22        | 1.77%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.45%   |
| Apple Bluetooth USB Host Controller                 | 16        | 1.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 1.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 13        | 1.05%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 0.88%   |
| TP-Link TP-T@- UB500 Adapter                        | 10        | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 0.8%    |
| Lite-On Bluetooth Device                            | 10        | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.8%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 10        | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Device                  | 9         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.64%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 6         | 0.48%   |
| ASUS ASUS USB-BT500                                 | 6         | 0.48%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.4%    |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.4%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 0.4%    |
| Apple Bluetooth HCI                                 | 5         | 0.4%    |
| Lite-On Wireless_Device                             | 4         | 0.32%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1244      | 52.38%  |
| AMD                                             | 481       | 20.25%  |
| Nvidia                                          | 377       | 15.87%  |
| C-Media Electronics                             | 39        | 1.64%   |
| Logitech                                        | 20        | 0.84%   |
| GN Netcom                                       | 19        | 0.8%    |
| Realtek Semiconductor                           | 18        | 0.76%   |
| ASUSTek Computer                                | 16        | 0.67%   |
| Plantronics                                     | 11        | 0.46%   |
| Lenovo                                          | 11        | 0.46%   |
| Kingston Technology                             | 8         | 0.34%   |
| Texas Instruments                               | 7         | 0.29%   |
| Generalplus Technology                          | 7         | 0.29%   |
| Razer USA                                       | 6         | 0.25%   |
| Micro Star International                        | 6         | 0.25%   |
| VIA Technologies                                | 5         | 0.21%   |
| JMTek                                           | 5         | 0.21%   |
| Sony                                            | 4         | 0.17%   |
| Native Instruments                              | 4         | 0.17%   |
| Hewlett-Packard                                 | 4         | 0.17%   |
| Focusrite-Novation                              | 4         | 0.17%   |
| Creative Labs                                   | 4         | 0.17%   |
| BEHRINGER International                         | 4         | 0.17%   |
| Apple                                           | 4         | 0.17%   |
| Zoran Co. Personal Media Division (Nogatech)    | 3         | 0.13%   |
| Zhaoxin                                         | 3         | 0.13%   |
| SteelSeries ApS                                 | 3         | 0.13%   |
| KORG                                            | 3         | 0.13%   |
| Jieli Technology                                | 3         | 0.13%   |
| DSEA A/S                                        | 3         | 0.13%   |
| Creative Technology                             | 3         | 0.13%   |
| Samson Technologies                             | 2         | 0.08%   |
| PreSonus Audio Electronics                      | 2         | 0.08%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.08%   |
| KTMicro                                         | 2         | 0.08%   |
| Giga-Byte Technology                            | 2         | 0.08%   |
| Corsair                                         | 2         | 0.08%   |
| Blue Microphones                                | 2         | 0.08%   |
| Yamaha                                          | 1         | 0.04%   |
| XMOS                                            | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 233       | 8.17%   |
| Intel Sunrise Point-LP HD Audio                                            | 153       | 5.36%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 134       | 4.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 99        | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 93        | 3.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 91        | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 69        | 2.42%   |
| AMD Radeon High Definition Audio Controller                                | 69        | 2.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 68        | 2.38%   |
| Intel Cannon Lake PCH cAVS                                                 | 59        | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 58        | 2.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 49        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48        | 1.68%   |
| Intel Broadwell-U Audio Controller                                         | 44        | 1.54%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 41        | 1.44%   |
| AMD FCH Azalia Controller                                                  | 40        | 1.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.3%    |
| Intel 200 Series PCH HD Audio                                              | 34        | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                               | 33        | 1.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 32        | 1.12%   |
| Intel 8 Series HD Audio Controller                                         | 32        | 1.12%   |
| Nvidia GA106 High Definition Audio Controller                              | 31        | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 31        | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 30        | 1.05%   |
| Intel Alder Lake-S HD Audio Controller                                     | 30        | 1.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 30        | 1.05%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 28        | 0.98%   |
| Nvidia GP107GL High Definition Audio Controller                            | 27        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 26        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 26        | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 25        | 0.88%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 25        | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 25        | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 24        | 0.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 23        | 0.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 23        | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 22        | 0.77%   |
| Intel Comet Lake PCH cAVS                                                  | 21        | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 19        | 0.67%   |
| Nvidia GP104 High Definition Audio Controller                              | 18        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 229       | 24.76%  |
| SK hynix               | 160       | 17.3%   |
| Micron Technology      | 128       | 13.84%  |
| Kingston               | 94        | 10.16%  |
| Crucial                | 57        | 6.16%   |
| Unknown                | 45        | 4.86%   |
| Corsair                | 35        | 3.78%   |
| G.Skill                | 28        | 3.03%   |
| A-DATA Technology      | 20        | 2.16%   |
| Ramaxel Technology     | 15        | 1.62%   |
| Unknown                | 12        | 1.3%    |
| Unknown (ABCD)         | 11        | 1.19%   |
| Elpida                 | 10        | 1.08%   |
| Smart                  | 9         | 0.97%   |
| Team                   | 8         | 0.86%   |
| Transcend              | 6         | 0.65%   |
| Patriot                | 5         | 0.54%   |
| Nanya Technology       | 5         | 0.54%   |
| GOODRAM                | 4         | 0.43%   |
| Timetec                | 3         | 0.32%   |
| Shenzhen WODPOSIT      | 3         | 0.32%   |
| PNY                    | 3         | 0.32%   |
| Wodposit               | 2         | 0.22%   |
| Patriot Memory         | 2         | 0.22%   |
| Hewlett-Packard        | 2         | 0.22%   |
| ASint Technology       | 2         | 0.22%   |
| Apacer                 | 2         | 0.22%   |
| Unknown (AB)           | 1         | 0.11%   |
| Unknown (0x9801)       | 1         | 0.11%   |
| Unknown (0x0CDC)       | 1         | 0.11%   |
| Unknown (0x0C26)       | 1         | 0.11%   |
| Unknown (0B85)         | 1         | 0.11%   |
| Unknown (0000000080CE) | 1         | 0.11%   |
| Unifosa                | 1         | 0.11%   |
| Teikon                 | 1         | 0.11%   |
| Strontium              | 1         | 0.11%   |
| Sesame                 | 1         | 0.11%   |
| Saikano                | 1         | 0.11%   |
| PUSKILL                | 1         | 0.11%   |
| Lexar                  | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 12        | 1.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.03%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 0.93%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 8         | 0.82%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 7         | 0.72%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.62%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.62%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 6         | 0.62%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 0.62%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 5         | 0.51%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.51%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.51%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.51%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 5         | 0.51%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s           | 5         | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.51%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 4         | 0.41%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 4         | 0.41%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.41%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 4         | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.41%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s      | 4         | 0.41%   |
| Samsung RAM K4UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s     | 4         | 0.41%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.41%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s            | 4         | 0.41%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 4000MT/s              | 4         | 0.41%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 405       | 49.57%  |
| DDR3    | 161       | 19.71%  |
| DDR5    | 69        | 8.45%   |
| LPDDR4  | 65        | 7.96%   |
| LPDDR5  | 46        | 5.63%   |
| LPDDR3  | 28        | 3.43%   |
| SDRAM   | 18        | 2.2%    |
| DDR2    | 13        | 1.59%   |
| Unknown | 8         | 0.98%   |
| DRAM    | 2         | 0.24%   |
| DDR     | 2         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 472       | 57.91%  |
| DIMM         | 200       | 24.54%  |
| Row Of Chips | 129       | 15.83%  |
| Chip         | 8         | 0.98%   |
| Unknown      | 6         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 393       | 44.76%  |
| 4096  | 179       | 20.39%  |
| 16384 | 169       | 19.25%  |
| 32768 | 68        | 7.74%   |
| 2048  | 52        | 5.92%   |
| 1024  | 14        | 1.59%   |
| 49152 | 1         | 0.11%   |
| 1536  | 1         | 0.11%   |
| 512   | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 204       | 23.58%  |
| 1600    | 120       | 13.87%  |
| 2667    | 101       | 11.68%  |
| 2400    | 61        | 7.05%   |
| 6400    | 45        | 5.2%    |
| 2133    | 45        | 5.2%    |
| 4800    | 38        | 4.39%   |
| 4267    | 33        | 3.82%   |
| 1333    | 22        | 2.54%   |
| 3600    | 20        | 2.31%   |
| 1867    | 18        | 2.08%   |
| 5600    | 12        | 1.39%   |
| 1334    | 12        | 1.39%   |
| 3733    | 11        | 1.27%   |
| 800     | 10        | 1.16%   |
| 6000    | 8         | 0.92%   |
| 4000    | 8         | 0.92%   |
| Unknown | 8         | 0.92%   |
| 8400    | 7         | 0.81%   |
| 4266    | 6         | 0.69%   |
| 2666    | 6         | 0.69%   |
| 667     | 6         | 0.69%   |
| 3800    | 5         | 0.58%   |
| 5200    | 4         | 0.46%   |
| 3400    | 4         | 0.46%   |
| 2048    | 4         | 0.46%   |
| 6200    | 3         | 0.35%   |
| 4199    | 3         | 0.35%   |
| 3466    | 3         | 0.35%   |
| 3266    | 3         | 0.35%   |
| 2933    | 3         | 0.35%   |
| 1067    | 3         | 0.35%   |
| 12800   | 2         | 0.23%   |
| 5500    | 2         | 0.23%   |
| 1866    | 2         | 0.23%   |
| 1800    | 2         | 0.23%   |
| 975     | 2         | 0.23%   |
| 533     | 2         | 0.23%   |
| 400     | 2         | 0.23%   |
| 7500    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 23.08%  |
| Brother Industries    | 9         | 23.08%  |
| Seiko Epson           | 6         | 15.38%  |
| Samsung Electronics   | 6         | 15.38%  |
| Canon                 | 4         | 10.26%  |
| Pantum                | 2         | 5.13%   |
| QinHeng Electronics   | 1         | 2.56%   |
| Lexmark International | 1         | 2.56%   |
| Dymo-CoStar           | 1         | 2.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson XP-2200 Series                   | 1         | 2.56%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 2.56%   |
| Seiko Epson ET-8550 Series                   | 1         | 2.56%   |
| Seiko Epson ET-3750 Series                   | 1         | 2.56%   |
| Seiko Epson ET-2820 Series                   | 1         | 2.56%   |
| Seiko Epson ET-2810 Series                   | 1         | 2.56%   |
| Samsung SCX-4623 Series                      | 1         | 2.56%   |
| Samsung SCX-3400 Series                      | 1         | 2.56%   |
| Samsung ML-216x Series Laser Printer         | 1         | 2.56%   |
| Samsung M2020 Series                         | 1         | 2.56%   |
| Samsung CLX-3170 Series                      | 1         | 2.56%   |
| Samsung C1860 Series                         | 1         | 2.56%   |
| QinHeng CH340S                               | 1         | 2.56%   |
| Pantum P2200 series                          | 1         | 2.56%   |
| Pantum M6550NW series                        | 1         | 2.56%   |
| Lexmark International MC3326adwe             | 1         | 2.56%   |
| HP OfficeJet 5200 series                     | 1         | 2.56%   |
| HP LaserJet Pro M201dw                       | 1         | 2.56%   |
| HP LaserJet P2055 series                     | 1         | 2.56%   |
| HP LaserJet P2015 series                     | 1         | 2.56%   |
| HP DeskJet 960c                              | 1         | 2.56%   |
| HP DeskJet 4100 series                       | 1         | 2.56%   |
| HP DeskJet 3830 series                       | 1         | 2.56%   |
| HP ColorLaserJet M253-M254                   | 1         | 2.56%   |
| HP Color LaserJet Pro M453-4                 | 1         | 2.56%   |
| Dymo-CoStar DYMO LabelWriter 4XL             | 1         | 2.56%   |
| Canon TS3100 series                          | 1         | 2.56%   |
| Canon TR4500 series                          | 1         | 2.56%   |
| Canon iP90                                   | 1         | 2.56%   |
| Canon iP7200 series                          | 1         | 2.56%   |
| Brother MFC-J6530DW                          | 1         | 2.56%   |
| Brother MFC-J1010DW                          | 1         | 2.56%   |
| Brother MFC-9330CDW                          | 1         | 2.56%   |
| Brother HL-L5000D series                     | 1         | 2.56%   |
| Brother HL-52x0 series                       | 1         | 2.56%   |
| Brother HL-2250DN Laser Printer              | 1         | 2.56%   |
| Brother HL-2030 Laser Printer                | 1         | 2.56%   |
| Brother DCP-7055W                            | 1         | 2.56%   |
| Brother DCP-1610W                            | 1         | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Canon   | 5         | 83.33%  |
| Plustek | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100            | 2         | 33.33%  |
| Plustek 600dpi USB Scanner         | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 16.67%  |
| Canon CanoScan LiDE 120            | 1         | 16.67%  |
| Canon CanoScan 8800F               | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 227       | 20.66%  |
| IMC Networks                           | 104       | 9.46%   |
| Microdia                               | 99        | 9.01%   |
| Quanta                                 | 80        | 7.28%   |
| Realtek Semiconductor                  | 77        | 7.01%   |
| Bison Electronics                      | 67        | 6.1%    |
| Logitech                               | 51        | 4.64%   |
| Apple                                  | 50        | 4.55%   |
| Sunplus Innovation Technology          | 49        | 4.46%   |
| Luxvisions Innotech Limited            | 40        | 3.64%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 3.46%   |
| Syntek                                 | 28        | 2.55%   |
| Lite-On Technology                     | 23        | 2.09%   |
| Sonix Technology                       | 20        | 1.82%   |
| Suyin                                  | 13        | 1.18%   |
| Silicon Motion                         | 13        | 1.18%   |
| Samsung Electronics                    | 12        | 1.09%   |
| Microsoft                              | 10        | 0.91%   |
| Alcor Micro                            | 9         | 0.82%   |
| SunplusIT                              | 8         | 0.73%   |
| Importek                               | 8         | 0.73%   |
| Acer                                   | 7         | 0.64%   |
| ShineTech                              | 6         | 0.55%   |
| Z-Star Microelectronics                | 4         | 0.36%   |
| Ricoh                                  | 4         | 0.36%   |
| Shine-optics                           | 3         | 0.27%   |
| Razer USA                              | 3         | 0.27%   |
| Lenovo                                 | 3         | 0.27%   |
| icSpring                               | 3         | 0.27%   |
| Generalplus Technology                 | 3         | 0.27%   |
| ARC International                      | 3         | 0.27%   |
| Trust                                  | 2         | 0.18%   |
| Pixart Imaging                         | 2         | 0.18%   |
| Hewlett-Packard                        | 2         | 0.18%   |
| Google                                 | 2         | 0.18%   |
| Unknown                                | 2         | 0.18%   |
| webcam                                 | 1         | 0.09%   |
| WCM_USB                                | 1         | 0.09%   |
| WaveRider Communications               | 1         | 0.09%   |
| Sunplus Technology                     | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 66        | 5.91%   |
| Microdia Integrated_Webcam_HD                       | 48        | 4.3%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 34        | 3.05%   |
| IMC Networks Integrated Camera                      | 30        | 2.69%   |
| Realtek Integrated_Webcam_HD                        | 24        | 2.15%   |
| Chicony HP HD Camera                                | 24        | 2.15%   |
| Bison Integrated Camera                             | 23        | 2.06%   |
| Syntek Integrated Camera                            | 21        | 1.88%   |
| Chicony HD WebCam                                   | 17        | 1.52%   |
| Apple Built-in iSight                               | 15        | 1.34%   |
| Sunplus Integrated_Webcam_HD                        | 13        | 1.16%   |
| Logitech Webcam C270                                | 13        | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 13        | 1.16%   |
| Samsung Galaxy series, misc. (MTP mode)             | 12        | 1.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 1.08%   |
| Chicony HP Wide Vision HD Camera                    | 11        | 0.99%   |
| Apple FaceTime HD Camera (Built-in)                 | 11        | 0.99%   |
| Sonix USB2.0 HD UVC WebCam                          | 10        | 0.9%    |
| Quanta HD User Facing                               | 10        | 0.9%    |
| Logitech HD Pro Webcam C920                         | 10        | 0.9%    |
| Lite-On Integrated Camera                           | 10        | 0.9%    |
| Chicony HP Truevision HD                            | 10        | 0.9%    |
| Chicony HD User Facing                              | 10        | 0.9%    |
| Sonix USB2.0 FHD UVC WebCam                         | 9         | 0.81%   |
| Quanta HP TrueVision HD Camera                      | 9         | 0.81%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 9         | 0.81%   |
| Apple FaceTime HD Camera                            | 9         | 0.81%   |
| Quanta ov9734_techfront_camera                      | 8         | 0.72%   |
| Quanta HD Camera                                    | 8         | 0.72%   |
| Microdia Integrated_Webcam_FHD                      | 8         | 0.72%   |
| Luxvisions Innotech Limited Integrated Camera       | 8         | 0.72%   |
| IMC Networks HD Camera                              | 8         | 0.72%   |
| Chicony HP TrueVision HD Camera                     | 8         | 0.72%   |
| Realtek USB Camera                                  | 7         | 0.63%   |
| Realtek Integrated Webcam_HD                        | 7         | 0.63%   |
| Realtek Integrated Webcam HD                        | 7         | 0.63%   |
| Quanta HP HD Camera                                 | 7         | 0.63%   |
| Quanta HD Webcam                                    | 7         | 0.63%   |
| Microdia USB 2.0 Camera                             | 7         | 0.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 71        | 28.98%  |
| Synaptics                          | 64        | 26.12%  |
| Shenzhen Goodix Technology         | 61        | 24.9%   |
| Elan Microelectronics              | 17        | 6.94%   |
| LighTuning Technology              | 10        | 4.08%   |
| Upek                               | 8         | 3.27%   |
| Realtek USB2.0 Finger Print Bridge | 6         | 2.45%   |
| AuthenTec                          | 6         | 2.45%   |
| STMicroelectronics                 | 1         | 0.41%   |
| Focal-systems.Corp                 | 1         | 0.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 16.73%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 5.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 4.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 4.49%   |
| Elan ELAN:ARM-M4                                                           | 11        | 4.49%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 4.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 3.27%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 3.27%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 3.27%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 3.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.86%   |
| Synaptics WBDI                                                             | 7         | 2.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 2.45%   |
| Synaptics UWP WBDI Device                                                  | 6         | 2.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 6         | 2.45%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.45%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.04%   |
| Synaptics Prometheus Fingerprint Reader                                    | 5         | 2.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 1.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.63%   |
| Synaptics UWP WBDI                                                         | 4         | 1.63%   |
| Synaptics  WBDI                                                            | 4         | 1.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.63%   |
| AuthenTec AES2810                                                          | 4         | 1.63%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.22%   |
| LighTuning Fingerprint Sensor                                              | 3         | 1.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.41%   |
| Validity Sensors VFS491                                                    | 1         | 0.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.41%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.41%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.41%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.41%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.41%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.41%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 39        | 53.42%  |
| Alcor Micro           | 26        | 35.62%  |
| Upek                  | 3         | 4.11%   |
| Realtek Semiconductor | 1         | 1.37%   |
| OmniKey               | 1         | 1.37%   |
| Lenovo                | 1         | 1.37%   |
| Hewlett-Packard       | 1         | 1.37%   |
| Advanced Card Systems | 1         | 1.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 34.25%  |
| Broadcom 5880                                                                | 17        | 23.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 10.96%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 7         | 9.59%   |
| Broadcom 58200                                                               | 5         | 6.85%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 4.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.74%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.37%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.37%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 1.37%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.37%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.37%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1140      | 66.05%  |
| 1     | 460       | 26.65%  |
| 2     | 98        | 5.68%   |
| 3     | 15        | 0.87%   |
| 4     | 7         | 0.41%   |
| 6     | 3         | 0.17%   |
| 10    | 1         | 0.06%   |
| 7     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 244       | 34.37%  |
| Graphics card            | 163       | 22.96%  |
| Chipcard                 | 69        | 9.72%   |
| Net/wireless             | 49        | 6.9%    |
| Multimedia controller    | 46        | 6.48%   |
| Camera                   | 44        | 6.2%    |
| Communication controller | 23        | 3.24%   |
| Unassigned class         | 22        | 3.1%    |
| Sound                    | 13        | 1.83%   |
| Bluetooth                | 11        | 1.55%   |
| Storage                  | 6         | 0.85%   |
| Card reader              | 6         | 0.85%   |
| Network                  | 5         | 0.7%    |
| Net/ethernet             | 5         | 0.7%    |
| Modem                    | 2         | 0.28%   |
| Storage/ide              | 1         | 0.14%   |
| Dvb card                 | 1         | 0.14%   |


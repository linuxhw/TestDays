Ubuntu Budgie 22.04 - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie_22.04/Notebook/README.md).

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

Total: 119

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [8c6fb84b12](https://linux-hardware.org/?probe=8c6fb84b12) | Feb 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0e931084a7](https://linux-hardware.org/?probe=0e931084a7) | Feb 05, 2023 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [de3f21b51b](https://linux-hardware.org/?probe=de3f21b51b) | Jan 28, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [329e7b7105](https://linux-hardware.org/?probe=329e7b7105) | Jan 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [831fd897ec](https://linux-hardware.org/?probe=831fd897ec) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0c8a9895bd](https://linux-hardware.org/?probe=0c8a9895bd) | Jan 25, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [b3bc8de731](https://linux-hardware.org/?probe=b3bc8de731) | Jan 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [38ff99d952](https://linux-hardware.org/?probe=38ff99d952) | Jan 10, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a5e1965b89](https://linux-hardware.org/?probe=a5e1965b89) | Jan 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP14... | Convertible | [195eb3e6eb](https://linux-hardware.org/?probe=195eb3e6eb) | Dec 31, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | Notebook    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Dell          | 0RW199                      | Desktop     | [2a2fa5baf8](https://linux-hardware.org/?probe=2a2fa5baf8) | Nov 20, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [afb716fb12](https://linux-hardware.org/?probe=afb716fb12) | Nov 18, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [0f94a77355](https://linux-hardware.org/?probe=0f94a77355) | Nov 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0e8db93a43](https://linux-hardware.org/?probe=0e8db93a43) | Oct 30, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | Notebook    | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | Notebook    | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| Dell          | Latitude E5420              | Notebook    | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | Notebook    | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | Notebook    | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [55db3c3775](https://linux-hardware.org/?probe=55db3c3775) | Sep 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [da53115e6b](https://linux-hardware.org/?probe=da53115e6b) | Sep 15, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [1a5358a3c1](https://linux-hardware.org/?probe=1a5358a3c1) | Sep 14, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [19a21d721c](https://linux-hardware.org/?probe=19a21d721c) | Sep 07, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [f42f75038e](https://linux-hardware.org/?probe=f42f75038e) | Sep 03, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [548332086b](https://linux-hardware.org/?probe=548332086b) | Sep 02, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [922554664a](https://linux-hardware.org/?probe=922554664a) | Aug 25, 2022 |
| Google        | Rabbid                      | Notebook    | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Intel         | X79M-S                      | Desktop     | [49a7d62fe8](https://linux-hardware.org/?probe=49a7d62fe8) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| HP            | 828A                        | Desktop     | [f42b1efd1e](https://linux-hardware.org/?probe=f42b1efd1e) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | Notebook    | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| Dell          | Inspiron 3793               | Notebook    | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| Intel         | STK1A32SC H95551-301        | Desktop     | [ea91c7805d](https://linux-hardware.org/?probe=ea91c7805d) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | Notebook    | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [b48ce81bfa](https://linux-hardware.org/?probe=b48ce81bfa) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f6faa2d944](https://linux-hardware.org/?probe=f6faa2d944) | Jun 25, 2022 |
| HP            | ElitePad 1000 G2            | Notebook    | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| MSI           | GL62 6QF                    | Notebook    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | Notebook    | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [261466af7b](https://linux-hardware.org/?probe=261466af7b) | Jun 17, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [fc9dd3db05](https://linux-hardware.org/?probe=fc9dd3db05) | May 26, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9acb45109f](https://linux-hardware.org/?probe=9acb45109f) | May 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | Notebook    | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [4ab84df25d](https://linux-hardware.org/?probe=4ab84df25d) | May 10, 2022 |
| MSI           | Modern 15 A10M              | Notebook    | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| HP            | 1825                        | Desktop     | [fe93966c1c](https://linux-hardware.org/?probe=fe93966c1c) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | Notebook    | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Samsung       | 740U3M                      | Convertible | [4ba9324ca5](https://linux-hardware.org/?probe=4ba9324ca5) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| HP            | 8446                        | All in one  | [b13e626d1a](https://linux-hardware.org/?probe=b13e626d1a) | May 02, 2022 |
| HP            | 8446                        | All in one  | [14d68e146a](https://linux-hardware.org/?probe=14d68e146a) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-27-generic      | 11        | 11.22%  |
| 5.15.0-52-generic      | 9         | 9.18%   |
| 5.15.0-50-generic      | 7         | 7.14%   |
| 5.15.0-48-generic      | 6         | 6.12%   |
| 5.15.0-30-generic      | 6         | 6.12%   |
| 5.15.0-46-generic      | 5         | 5.1%    |
| 5.15.0-43-generic      | 5         | 5.1%    |
| 5.15.0-39-generic      | 5         | 5.1%    |
| 5.15.0-56-generic      | 4         | 4.08%   |
| 5.15.0-33-generic      | 4         | 4.08%   |
| 5.15.0-25-generic      | 4         | 4.08%   |
| 5.15.0-53-generic      | 3         | 3.06%   |
| 5.15.0-47-generic      | 3         | 3.06%   |
| 5.15.0-40-generic      | 3         | 3.06%   |
| 5.15.0-58-generic      | 2         | 2.04%   |
| 5.15.0-57-generic      | 2         | 2.04%   |
| 5.15.0-41-generic      | 2         | 2.04%   |
| 5.19.0-051900-generic  | 1         | 1.02%   |
| 5.17.2-051702-generic  | 1         | 1.02%   |
| 5.16.2                 | 1         | 1.02%   |
| 5.15.92-051592-generic | 1         | 1.02%   |
| 5.15.0-60-generic      | 1         | 1.02%   |
| 5.15.0-52-lowlatency   | 1         | 1.02%   |
| 5.15.0-47-lowlatency   | 1         | 1.02%   |
| 5.15.0-35-generic      | 1         | 1.02%   |
| 5.15.0-18-generic      | 1         | 1.02%   |
| 5.15.0-10058-tuxedo    | 1         | 1.02%   |
| 5.15.0-10056-tuxedo    | 1         | 1.02%   |
| 5.15.0-10052-tuxedo    | 1         | 1.02%   |
| 5.15.0-10047-tuxedo    | 1         | 1.02%   |
| 5.15.0-10041-tuxedo    | 1         | 1.02%   |
| 5.13.0-44-generic      | 1         | 1.02%   |
| 5.13.0-35-generic      | 1         | 1.02%   |
| 5.13.0-19-generic      | 1         | 1.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 86        | 92.47%  |
| 5.13.0  | 3         | 3.23%   |
| 5.19.0  | 1         | 1.08%   |
| 5.17.2  | 1         | 1.08%   |
| 5.16.2  | 1         | 1.08%   |
| 5.15.92 | 1         | 1.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 87        | 93.55%  |
| 5.13    | 3         | 3.23%   |
| 5.19    | 1         | 1.08%   |
| 5.17    | 1         | 1.08%   |
| 5.16    | 1         | 1.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 93        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 90        | 96.77%  |
| GNOME  | 3         | 3.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 91        | 97.85%  |
| Wayland | 2         | 2.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 65        | 69.89%  |
| Unknown | 20        | 21.51%  |
| GDM3    | 7         | 7.53%   |
| GDM     | 1         | 1.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 35        | 37.63%  |
| de_DE | 14        | 15.05%  |
| fr_FR | 9         | 9.68%   |
| pt_BR | 6         | 6.45%   |
| en_GB | 6         | 6.45%   |
| en_CA | 3         | 3.23%   |
| ru_RU | 2         | 2.15%   |
| it_IT | 2         | 2.15%   |
| hu_HU | 2         | 2.15%   |
| es_MX | 2         | 2.15%   |
| es_ES | 2         | 2.15%   |
| mt_MT | 1         | 1.08%   |
| fr_BE | 1         | 1.08%   |
| es_PE | 1         | 1.08%   |
| es_EC | 1         | 1.08%   |
| es_CL | 1         | 1.08%   |
| en_NZ | 1         | 1.08%   |
| en_IE | 1         | 1.08%   |
| el_GR | 1         | 1.08%   |
| cs_CZ | 1         | 1.08%   |
| C     | 1         | 1.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 56        | 59.57%  |
| EFI  | 38        | 40.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 83        | 89.25%  |
| Overlay | 5         | 5.38%   |
| Btrfs   | 3         | 3.23%   |
| Zfs     | 1         | 1.08%   |
| Xfs     | 1         | 1.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 53        | 56.99%  |
| Unknown | 37        | 39.78%  |
| MBR     | 3         | 3.23%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 81.72%  |
| Yes       | 17        | 18.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 70.21%  |
| Yes       | 28        | 29.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 15        | 16.13%  |
| Hewlett-Packard        | 14        | 15.05%  |
| Dell                   | 12        | 12.9%   |
| ASUSTek Computer       | 9         | 9.68%   |
| Gigabyte Technology    | 8         | 8.6%    |
| MSI                    | 6         | 6.45%   |
| TUXEDO                 | 5         | 5.38%   |
| Apple                  | 5         | 5.38%   |
| Intel                  | 3         | 3.23%   |
| Google                 | 2         | 2.15%   |
| Fujitsu                | 2         | 2.15%   |
| ASRock                 | 2         | 2.15%   |
| Toshiba                | 1         | 1.08%   |
| Timi                   | 1         | 1.08%   |
| Samsung Electronics    | 1         | 1.08%   |
| Razer                  | 1         | 1.08%   |
| Digibras               | 1         | 1.08%   |
| Chuwi                  | 1         | 1.08%   |
| Biostar                | 1         | 1.08%   |
| AXIOO                  | 1         | 1.08%   |
| Avell High Performance | 1         | 1.08%   |
| Acer                   | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1.08%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1.08%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 1.08%   |
| TUXEDO Book BA1510                                   | 1         | 1.08%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 1.08%   |
| Toshiba Satellite A505                               | 1         | 1.08%   |
| Timi TM1604                                          | 1         | 1.08%   |
| Samsung 740U3M                                       | 1         | 1.08%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1.08%   |
| MSI MS-7C95                                          | 1         | 1.08%   |
| MSI MS-7B86                                          | 1         | 1.08%   |
| MSI MS-7A32                                          | 1         | 1.08%   |
| MSI MS-7885                                          | 1         | 1.08%   |
| MSI Modern 15 A10M                                   | 1         | 1.08%   |
| MSI GL62 6QF                                         | 1         | 1.08%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1.08%   |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 1.08%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1.08%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1.08%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1.08%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1.08%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1.08%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1.08%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9                     | 1         | 1.08%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1.08%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1.08%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1.08%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1.08%   |
| Lenovo G500 20236                                    | 1         | 1.08%   |
| Lenovo G50-45 80E3                                   | 1         | 1.08%   |
| Intel STK1A32SC                                      | 1         | 1.08%   |
| Intel NUC12WSKi7                                     | 1         | 1.08%   |
| Intel DP55WB AAE64798-206                            | 1         | 1.08%   |
| HP Z440 Workstation                                  | 1         | 1.08%   |
| HP Spectre x360 Convertible 15t-df100                | 1         | 1.08%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1.08%   |
| HP ProBook 450 G7                                    | 1         | 1.08%   |
| HP ProBook 445 G7                                    | 1         | 1.08%   |
| HP Pavilion x360 Convertible 14-dy1xxx               | 1         | 1.08%   |
| HP Pavilion g6                                       | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 5         | 5.38%   |
| Lenovo IdeaPad      | 4         | 4.3%    |
| Dell Inspiron       | 4         | 4.3%    |
| HP ProBook          | 3         | 3.23%   |
| ASUS VivoBook       | 3         | 3.23%   |
| TUXEDO Book         | 2         | 2.15%   |
| HP Pavilion         | 2         | 2.15%   |
| Dell XPS            | 2         | 2.15%   |
| Dell Precision      | 2         | 2.15%   |
| Dell Latitude       | 2         | 2.15%   |
| TUXEDO Polaris      | 1         | 1.08%   |
| TUXEDO InfinityBook | 1         | 1.08%   |
| TUXEDO Aura         | 1         | 1.08%   |
| Toshiba Satellite   | 1         | 1.08%   |
| Timi TM1604         | 1         | 1.08%   |
| Samsung 740U3M      | 1         | 1.08%   |
| Razer Blade         | 1         | 1.08%   |
| MSI MS-7C95         | 1         | 1.08%   |
| MSI MS-7B86         | 1         | 1.08%   |
| MSI MS-7A32         | 1         | 1.08%   |
| MSI MS-7885         | 1         | 1.08%   |
| MSI Modern          | 1         | 1.08%   |
| MSI GL62            | 1         | 1.08%   |
| Lenovo V15          | 1         | 1.08%   |
| Lenovo ThinkStation | 1         | 1.08%   |
| Lenovo Legion       | 1         | 1.08%   |
| Lenovo IdeaPadFlex  | 1         | 1.08%   |
| Lenovo G500         | 1         | 1.08%   |
| Lenovo G50-45       | 1         | 1.08%   |
| Intel STK1A32SC     | 1         | 1.08%   |
| Intel NUC12WSKi7    | 1         | 1.08%   |
| Intel DP55WB        | 1         | 1.08%   |
| HP Z440             | 1         | 1.08%   |
| HP Spectre          | 1         | 1.08%   |
| HP ENVY             | 1         | 1.08%   |
| HP ElitePad         | 1         | 1.08%   |
| HP EliteDesk        | 1         | 1.08%   |
| HP EliteBook        | 1         | 1.08%   |
| HP Elite            | 1         | 1.08%   |
| HP All-in-One       | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 14        | 15.05%  |
| 2020 | 14        | 15.05%  |
| 2018 | 9         | 9.68%   |
| 2019 | 8         | 8.6%    |
| 2014 | 8         | 8.6%    |
| 2016 | 7         | 7.53%   |
| 2010 | 5         | 5.38%   |
| 2022 | 4         | 4.3%    |
| 2017 | 4         | 4.3%    |
| 2013 | 4         | 4.3%    |
| 2011 | 4         | 4.3%    |
| 2015 | 3         | 3.23%   |
| 2012 | 3         | 3.23%   |
| 2009 | 3         | 3.23%   |
| 2008 | 3         | 3.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 55        | 59.14%  |
| Desktop     | 27        | 29.03%  |
| Convertible | 6         | 6.45%   |
| Mini pc     | 2         | 2.15%   |
| All in one  | 2         | 2.15%   |
| Tablet      | 1         | 1.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 87        | 93.55%  |
| Enabled  | 6         | 6.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 91        | 97.85%  |
| Yes  | 2         | 2.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 27        | 29.03%  |
| 4.01-8.0        | 26        | 27.96%  |
| 8.01-16.0       | 17        | 18.28%  |
| 32.01-64.0      | 8         | 8.6%    |
| 3.01-4.0        | 8         | 8.6%    |
| 64.01-256.0     | 3         | 3.23%   |
| 1.01-2.0        | 2         | 2.15%   |
| More than 256.0 | 1         | 1.08%   |
| 24.01-32.0      | 1         | 1.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 31        | 32.29%  |
| 2.01-3.0   | 30        | 31.25%  |
| 4.01-8.0   | 20        | 20.83%  |
| 3.01-4.0   | 7         | 7.29%   |
| 8.01-16.0  | 6         | 6.25%   |
| 24.01-32.0 | 1         | 1.04%   |
| 16.01-24.0 | 1         | 1.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 54        | 57.45%  |
| 2      | 28        | 29.79%  |
| 3      | 5         | 5.32%   |
| 4      | 3         | 3.19%   |
| 6      | 2         | 2.13%   |
| 8      | 1         | 1.06%   |
| 7      | 1         | 1.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 69        | 74.19%  |
| Yes       | 24        | 25.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 78.49%  |
| No        | 20        | 21.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 83.87%  |
| No        | 15        | 16.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 67        | 72.04%  |
| No        | 26        | 27.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 21        | 22.58%  |
| Germany            | 13        | 13.98%  |
| France             | 9         | 9.68%   |
| Brazil             | 7         | 7.53%   |
| UK                 | 3         | 3.23%   |
| Switzerland        | 2         | 2.15%   |
| Slovenia           | 2         | 2.15%   |
| Mexico             | 2         | 2.15%   |
| Italy              | 2         | 2.15%   |
| Hungary            | 2         | 2.15%   |
| Greece             | 2         | 2.15%   |
| Canada             | 2         | 2.15%   |
| Austria            | 2         | 2.15%   |
| Sweden             | 1         | 1.08%   |
| Spain              | 1         | 1.08%   |
| Saudi Arabia       | 1         | 1.08%   |
| Russia             | 1         | 1.08%   |
| Romania            | 1         | 1.08%   |
| Poland             | 1         | 1.08%   |
| Peru               | 1         | 1.08%   |
| Norway             | 1         | 1.08%   |
| New Zealand        | 1         | 1.08%   |
| Netherlands        | 1         | 1.08%   |
| Malta              | 1         | 1.08%   |
| Ireland            | 1         | 1.08%   |
| Indonesia          | 1         | 1.08%   |
| Ghana              | 1         | 1.08%   |
| Ecuador            | 1         | 1.08%   |
| Dominican Republic | 1         | 1.08%   |
| Czechia            | 1         | 1.08%   |
| Croatia            | 1         | 1.08%   |
| Chile              | 1         | 1.08%   |
| Cabo Verde         | 1         | 1.08%   |
| Belgium            | 1         | 1.08%   |
| Belarus            | 1         | 1.08%   |
| Argentina          | 1         | 1.08%   |
| Algeria            | 1         | 1.08%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milwaukee             | 2         | 2.13%   |
| Budapest              | 2         | 2.13%   |
| Athens                | 2         | 2.13%   |
| Zurich                | 1         | 1.06%   |
| West Lafayette        | 1         | 1.06%   |
| Wertheim am Main      | 1         | 1.06%   |
| Weisswasser           | 1         | 1.06%   |
| Weilheim              | 1         | 1.06%   |
| Warsaw                | 1         | 1.06%   |
| Walled Lake           | 1         | 1.06%   |
| Vienna                | 1         | 1.06%   |
| Victoria              | 1         | 1.06%   |
| Venray                | 1         | 1.06%   |
| Trondheim             | 1         | 1.06%   |
| Tocantins             | 1         | 1.06%   |
| Targu Frumos          | 1         | 1.06%   |
| Tarakan               | 1         | 1.06%   |
| Tann                  | 1         | 1.06%   |
| Tampa                 | 1         | 1.06%   |
| Sunnyvale             | 1         | 1.06%   |
| St Petersburg         | 1         | 1.06%   |
| Siegen                | 1         | 1.06%   |
| Sétif                | 1         | 1.06%   |
| Seelze                | 1         | 1.06%   |
| Seattle               | 1         | 1.06%   |
| Sao Paulo             | 1         | 1.06%   |
| Sao Bernardo do Campo | 1         | 1.06%   |
| Santo Domingo Este    | 1         | 1.06%   |
| Santiago              | 1         | 1.06%   |
| San Luis Potosí City | 1         | 1.06%   |
| Saint-Gilles          | 1         | 1.06%   |
| Rueil-Malmaison       | 1         | 1.06%   |
| Recife                | 1         | 1.06%   |
| Queens                | 1         | 1.06%   |
| Pula                  | 1         | 1.06%   |
| Puebla City           | 1         | 1.06%   |
| Praia                 | 1         | 1.06%   |
| Postojna              | 1         | 1.06%   |
| Pine Island           | 1         | 1.06%   |
| Ostrava               | 1         | 1.06%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 24        | 44     | 17.02%  |
| Seagate                        | 14        | 20     | 9.93%   |
| Unknown                        | 11        | 11     | 7.8%    |
| WDC                            | 10        | 12     | 7.09%   |
| Toshiba                        | 10        | 11     | 7.09%   |
| Crucial                        | 8         | 9      | 5.67%   |
| Micron Technology              | 7         | 7      | 4.96%   |
| SK hynix                       | 6         | 6      | 4.26%   |
| Sandisk                        | 5         | 6      | 3.55%   |
| Intel                          | 5         | 7      | 3.55%   |
| Kingston                       | 4         | 5      | 2.84%   |
| SPCC                           | 3         | 3      | 2.13%   |
| JMicron Technology             | 3         | 3      | 2.13%   |
| China                          | 3         | 4      | 2.13%   |
| Phison                         | 2         | 2      | 1.42%   |
| OCZ                            | 2         | 2      | 1.42%   |
| A-DATA Technology              | 2         | 2      | 1.42%   |
| Zheino                         | 1         | 1      | 0.71%   |
| VISIPRO                        | 1         | 1      | 0.71%   |
| Union Memory                   | 1         | 1      | 0.71%   |
| Transcend                      | 1         | 1      | 0.71%   |
| TO Exter                       | 1         | 1      | 0.71%   |
| Solid State Storage Technology | 1         | 1      | 0.71%   |
| SABRENT                        | 1         | 1      | 0.71%   |
| Realtek Semiconductor          | 1         | 1      | 0.71%   |
| PNY                            | 1         | 1      | 0.71%   |
| Phison Electronics             | 1         | 1      | 0.71%   |
| OWC                            | 1         | 1      | 0.71%   |
| Netac                          | 1         | 1      | 0.71%   |
| Mushkin                        | 1         | 1      | 0.71%   |
| Maxtor                         | 1         | 1      | 0.71%   |
| LITEON                         | 1         | 1      | 0.71%   |
| KIOXIA                         | 1         | 1      | 0.71%   |
| HGST                           | 1         | 1      | 0.71%   |
| Hewlett-Packard                | 1         | 1      | 0.71%   |
| Corsair                        | 1         | 2      | 0.71%   |
| ASMT109x                       | 1         | 1      | 0.71%   |
| Apple                          | 1         | 1      | 0.71%   |
| Unknown                        | 1         | 1      | 0.71%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.28%   |
| Unknown SD64G  64GB                    | 2         | 1.28%   |
| Unknown SD/MMC/MS PRO 16GB             | 2         | 1.28%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 1.28%   |
| SanDisk SDSSDA120G 120GB               | 2         | 1.28%   |
| Samsung SSD 980 PRO 2TB                | 2         | 1.28%   |
| Samsung SSD 980 500GB                  | 2         | 1.28%   |
| Samsung SSD 870 EVO 250GB              | 2         | 1.28%   |
| Samsung SSD 860 EVO M.2 500GB          | 2         | 1.28%   |
| Samsung SSD 850 PRO 256GB              | 2         | 1.28%   |
| Samsung SSD 850 EVO 500GB              | 2         | 1.28%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 1.28%   |
| Samsung MZVLQ512HALU-000H1 512GB       | 2         | 1.28%   |
| JMicron Generic 200GB                  | 2         | 1.28%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 1.28%   |
| Crucial CT1000MX500SSD1 1TB            | 2         | 1.28%   |
| Zheino CHN-25SATAC3-120 120GB          | 1         | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.64%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.64%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1         | 0.64%   |
| WDC WD3200LPVX-22V0TT0 320GB           | 1         | 0.64%   |
| WDC WD1600AAJS-60WAA0 160GB            | 1         | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB               | 1         | 0.64%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.64%   |
| WDC WD10EADS-00M2B0 1TB                | 1         | 0.64%   |
| WDC PC SN730 NVMe 256GB                | 1         | 0.64%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB   | 1         | 0.64%   |
| VISIPRO SSD 256GB                      | 1         | 0.64%   |
| Unknown SL128  128GB                   | 1         | 0.64%   |
| Unknown SA16G  16GB                    | 1         | 0.64%   |
| Unknown NCard  4GB                     | 1         | 0.64%   |
| Unknown MMC128  128GB                  | 1         | 0.64%   |
| Unknown MMC Card  64GB                 | 1         | 0.64%   |
| Unknown MMC Card  128GB                | 1         | 0.64%   |
| Unknown 00000  64GB                    | 1         | 0.64%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 0.64%   |
| Transcend TS128GMTE110S 128GB          | 1         | 0.64%   |
| Toshiba XG6 NVMe SSD Controller 512GB  | 1         | 0.64%   |
| Toshiba TR150 480GB SSD                | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 19     | 37.84%  |
| WDC                 | 8         | 9      | 21.62%  |
| Toshiba             | 5         | 5      | 13.51%  |
| Unknown             | 2         | 2      | 5.41%   |
| Samsung Electronics | 2         | 3      | 5.41%   |
| JMicron Technology  | 2         | 2      | 5.41%   |
| SABRENT             | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| ASMT109x            | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 25     | 21.28%  |
| Crucial             | 8         | 9      | 17.02%  |
| Micron Technology   | 3         | 3      | 6.38%   |
| China               | 3         | 4      | 6.38%   |
| SPCC                | 2         | 2      | 4.26%   |
| SanDisk             | 2         | 2      | 4.26%   |
| Zheino              | 1         | 1      | 2.13%   |
| WDC                 | 1         | 1      | 2.13%   |
| VISIPRO             | 1         | 1      | 2.13%   |
| Union Memory        | 1         | 1      | 2.13%   |
| Toshiba             | 1         | 1      | 2.13%   |
| TO Exter            | 1         | 1      | 2.13%   |
| SK hynix            | 1         | 1      | 2.13%   |
| PNY                 | 1         | 1      | 2.13%   |
| OWC                 | 1         | 1      | 2.13%   |
| OCZ                 | 1         | 1      | 2.13%   |
| Netac               | 1         | 1      | 2.13%   |
| Mushkin             | 1         | 1      | 2.13%   |
| LITEON              | 1         | 1      | 2.13%   |
| Kingston            | 1         | 2      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| Hewlett-Packard     | 1         | 1      | 2.13%   |
| Corsair             | 1         | 2      | 2.13%   |
| Apple               | 1         | 1      | 2.13%   |
| A-DATA Technology   | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 43        | 53     | 34.68%  |
| SSD     | 41        | 66     | 33.06%  |
| HDD     | 28        | 44     | 22.58%  |
| MMC     | 11        | 13     | 8.87%   |
| Unknown | 1         | 1      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 103    | 47.86%  |
| NVMe | 43        | 53     | 36.75%  |
| MMC  | 11        | 13     | 9.4%    |
| SAS  | 7         | 8      | 5.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 50        | 75     | 64.94%  |
| 0.51-1.0   | 17        | 23     | 22.08%  |
| 1.01-2.0   | 5         | 6      | 6.49%   |
| 3.01-4.0   | 4         | 4      | 5.19%   |
| 4.01-10.0  | 1         | 2      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 30.11%  |
| 251-500        | 27        | 29.03%  |
| 51-100         | 11        | 11.83%  |
| 501-1000       | 7         | 7.53%   |
| 1001-2000      | 6         | 6.45%   |
| 1-20           | 5         | 5.38%   |
| More than 3000 | 4         | 4.3%    |
| 21-50          | 4         | 4.3%    |
| 2001-3000      | 1         | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 26        | 27.66%  |
| 21-50          | 25        | 26.6%   |
| 101-250        | 15        | 15.96%  |
| 51-100         | 13        | 13.83%  |
| 251-500        | 7         | 7.45%   |
| 501-1000       | 4         | 4.26%   |
| 1001-2000      | 2         | 2.13%   |
| More than 3000 | 1         | 1.06%   |
| 2001-3000      | 1         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 50%     |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2         | 2      | 100%    |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 60        | 110    | 58.82%  |
| Works    | 40        | 65     | 39.22%  |
| Malfunc  | 2         | 2      | 1.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 55        | 45.83%  |
| AMD                            | 18        | 15%     |
| Samsung Electronics            | 14        | 11.67%  |
| SanDisk                        | 4         | 3.33%   |
| Micron Technology              | 4         | 3.33%   |
| Toshiba America Info Systems   | 3         | 2.5%    |
| SK hynix                       | 3         | 2.5%    |
| Phison Electronics             | 3         | 2.5%    |
| Nvidia                         | 3         | 2.5%    |
| Kingston Technology Company    | 3         | 2.5%    |
| KIOXIA                         | 2         | 1.67%   |
| Transcend                      | 1         | 0.83%   |
| Solid State Storage Technology | 1         | 0.83%   |
| Seagate Technology             | 1         | 0.83%   |
| Realtek Semiconductor          | 1         | 0.83%   |
| OCZ Technology Group           | 1         | 0.83%   |
| Marvell Technology Group       | 1         | 0.83%   |
| JMicron Technology             | 1         | 0.83%   |
| ADATA Technology               | 1         | 0.83%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 12        | 8.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 5.15%   |
| Samsung NVMe SSD Controller 980                                              | 5         | 3.68%   |
| Intel Volume Management Device NVMe RAID Controller                          | 5         | 3.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 4         | 2.94%   |
| Micron Non-Volatile memory controller                                        | 4         | 2.94%   |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 2.94%   |
| Intel Non-Volatile memory controller                                         | 3         | 2.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 2.21%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 3         | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 1.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.47%   |
| Phison PS5013 E13 NVMe Controller                                            | 2         | 1.47%   |
| Nvidia MCP79 AHCI Controller                                                 | 2         | 1.47%   |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 1.47%   |
| Intel Tiger Lake-LP SATA Controller                                          | 2         | 1.47%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                   | 2         | 1.47%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]             | 2         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode] | 2         | 1.47%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 2         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 2         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 2         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 2         | 1.47%   |
| AMD FCH IDE Controller                                                       | 2         | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                       | 2         | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                       | 2         | 1.47%   |
| Transcend Non-Volatile memory controller                                     | 1         | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.74%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.74%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.74%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 0.74%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 0.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 0.74%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.74%   |
| Seagate Non-Volatile memory controller                                       | 1         | 0.74%   |
| SanDisk WD Blue SN570 NVMe SSD                                               | 1         | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 1         | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                    | 1         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 64        | 51.61%  |
| NVMe | 43        | 34.68%  |
| IDE  | 10        | 8.06%   |
| RAID | 7         | 5.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 71        | 76.34%  |
| AMD    | 22        | 23.66%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 5.38%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 3.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 3.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2.15%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 2.15%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 2.15%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2.15%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2.15%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2.15%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 2.15%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.15%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 2.15%   |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 1.08%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 1.08%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 1.08%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 1.08%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1.08%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1.08%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1.08%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.08%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 1         | 1.08%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1.08%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1.08%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 1.08%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 1.08%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 1.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1.08%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.08%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 1         | 1.08%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 1.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 1.08%   |
| Intel Core i5-3470T CPU @ 2.90GHz             | 1         | 1.08%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 21        | 22.58%  |
| Other                | 13        | 13.98%  |
| Intel Core i7        | 12        | 12.9%   |
| AMD Ryzen 5          | 9         | 9.68%   |
| Intel Celeron        | 6         | 6.45%   |
| Intel Xeon           | 4         | 4.3%    |
| Intel Core i3        | 4         | 4.3%    |
| Intel Atom           | 4         | 4.3%    |
| Intel Core 2 Duo     | 3         | 3.23%   |
| AMD Ryzen 7          | 3         | 3.23%   |
| Intel Pentium Silver | 1         | 1.08%   |
| Intel Pentium        | 1         | 1.08%   |
| Intel Core i9        | 1         | 1.08%   |
| Intel Core 2 Quad    | 1         | 1.08%   |
| AMD Ryzen 9          | 1         | 1.08%   |
| AMD Ryzen 3          | 1         | 1.08%   |
| AMD Phenom II X4     | 1         | 1.08%   |
| AMD FX               | 1         | 1.08%   |
| AMD Athlon X4        | 1         | 1.08%   |
| AMD Athlon II X3     | 1         | 1.08%   |
| AMD Athlon           | 1         | 1.08%   |
| AMD A8               | 1         | 1.08%   |
| AMD A4               | 1         | 1.08%   |
| AMD A10              | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 40        | 43.01%  |
| 2      | 31        | 33.33%  |
| 8      | 8         | 8.6%    |
| 6      | 8         | 8.6%    |
| 12     | 2         | 2.15%   |
| 16     | 1         | 1.08%   |
| 10     | 1         | 1.08%   |
| 3      | 1         | 1.08%   |
| 1      | 1         | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 91        | 97.85%  |
| 2      | 2         | 2.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 67        | 72.04%  |
| 1      | 26        | 27.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 93        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 52.63%  |
| 0x806ec    | 4         | 4.21%   |
| 0x806c1    | 3         | 3.16%   |
| 0x306a9    | 3         | 3.16%   |
| 0x206a7    | 3         | 3.16%   |
| 0x08600106 | 3         | 3.16%   |
| 0x08108102 | 3         | 3.16%   |
| 0x706a8    | 2         | 2.11%   |
| 0x406f1    | 2         | 2.11%   |
| 0x0a50000c | 2         | 2.11%   |
| 0xa0671    | 1         | 1.05%   |
| 0x906eb    | 1         | 1.05%   |
| 0x906ea    | 1         | 1.05%   |
| 0x906a3    | 1         | 1.05%   |
| 0x806eb    | 1         | 1.05%   |
| 0x806e9    | 1         | 1.05%   |
| 0x806d1    | 1         | 1.05%   |
| 0x506c9    | 1         | 1.05%   |
| 0x406c4    | 1         | 1.05%   |
| 0x40651    | 1         | 1.05%   |
| 0x306d4    | 1         | 1.05%   |
| 0x30678    | 1         | 1.05%   |
| 0x20655    | 1         | 1.05%   |
| 0x106e5    | 1         | 1.05%   |
| 0x1067a    | 1         | 1.05%   |
| 0x10677    | 1         | 1.05%   |
| 0x08608104 | 1         | 1.05%   |
| 0x08108109 | 1         | 1.05%   |
| 0x07030104 | 1         | 1.05%   |
| 0x06001119 | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 18.28%  |
| TigerLake        | 8         | 8.6%    |
| Zen+             | 6         | 6.45%   |
| IvyBridge        | 6         | 6.45%   |
| Unknown          | 6         | 6.45%   |
| Penryn           | 5         | 5.38%   |
| Zen 3            | 4         | 4.3%    |
| Skylake          | 4         | 4.3%    |
| Silvermont       | 4         | 4.3%    |
| Haswell          | 4         | 4.3%    |
| Zen 2            | 3         | 3.23%   |
| SandyBridge      | 3         | 3.23%   |
| Icelake          | 3         | 3.23%   |
| Goldmont plus    | 3         | 3.23%   |
| Broadwell        | 3         | 3.23%   |
| Westmere         | 2         | 2.15%   |
| Nehalem          | 2         | 2.15%   |
| K10              | 2         | 2.15%   |
| Steamroller      | 1         | 1.08%   |
| Puma             | 1         | 1.08%   |
| Piledriver       | 1         | 1.08%   |
| Goldmont         | 1         | 1.08%   |
| Excavator        | 1         | 1.08%   |
| CometLake        | 1         | 1.08%   |
| Bulldozer        | 1         | 1.08%   |
| Alderlake Hybrid | 1         | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 59        | 54.13%  |
| Nvidia | 26        | 23.85%  |
| AMD    | 24        | 22.02%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 7.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 4.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 4.5%    |
| Intel UHD Graphics 620                                                    | 4         | 3.6%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 2.7%    |
| Intel HD Graphics 620                                                     | 3         | 2.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.7%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 2.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.7%    |
| AMD Renoir                                                                | 3         | 2.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 2.7%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.8%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.8%    |
| Intel JasperLake [UHD Graphics]                                           | 2         | 1.8%    |
| Intel HD Graphics 530                                                     | 2         | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.8%    |
| AMD Lucienne                                                              | 2         | 1.8%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2         | 1.8%    |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.9%    |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.9%    |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.9%    |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.9%    |
| Nvidia GP104GL [Quadro P4000]                                             | 1         | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.9%    |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.9%    |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.9%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 0.9%    |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.9%    |
| Nvidia GK110 [GeForce GTX 780]                                            | 1         | 0.9%    |
| Nvidia GK106 [GeForce GTX 660]                                            | 1         | 0.9%    |
| Nvidia GK106 [GeForce GTX 650 Ti]                                         | 1         | 0.9%    |
| Nvidia GF110 [GeForce GTX 570]                                            | 1         | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.9%    |
| Nvidia GA107GLM [RTX A2000 Mobile]                                        | 1         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 43        | 46.24%  |
| 1 x AMD        | 19        | 20.43%  |
| 1 x Nvidia     | 13        | 13.98%  |
| Intel + Nvidia | 11        | 11.83%  |
| Intel + AMD    | 2         | 2.15%   |
| AMD + Nvidia   | 2         | 2.15%   |
| Other          | 1         | 1.08%   |
| 2 x Intel      | 1         | 1.08%   |
| 2 x AMD        | 1         | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 79        | 84.95%  |
| Proprietary | 12        | 12.9%   |
| Unknown     | 2         | 2.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 75.27%  |
| 1.01-2.0   | 8         | 8.6%    |
| 0.01-0.5   | 7         | 7.53%   |
| 7.01-8.0   | 3         | 3.23%   |
| 0.51-1.0   | 3         | 3.23%   |
| 3.01-4.0   | 2         | 2.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 18        | 17.65%  |
| Chimei Innolux          | 17        | 16.67%  |
| BOE                     | 17        | 16.67%  |
| AU Optronics            | 7         | 6.86%   |
| LG Display              | 6         | 5.88%   |
| Apple                   | 5         | 4.9%    |
| Hewlett-Packard         | 4         | 3.92%   |
| Sharp                   | 3         | 2.94%   |
| Philips                 | 3         | 2.94%   |
| SANYO                   | 2         | 1.96%   |
| Goldstar                | 2         | 1.96%   |
| AOC                     | 2         | 1.96%   |
| Vestel Elektronik       | 1         | 0.98%   |
| Unknown (XXX)           | 1         | 0.98%   |
| Unknown (AAA)           | 1         | 0.98%   |
| Sony                    | 1         | 0.98%   |
| Panasonic               | 1         | 0.98%   |
| ONN                     | 1         | 0.98%   |
| MStar                   | 1         | 0.98%   |
| LG Electronics          | 1         | 0.98%   |
| Lenovo                  | 1         | 0.98%   |
| IBM                     | 1         | 0.98%   |
| HKC                     | 1         | 0.98%   |
| Fujitsu Siemens         | 1         | 0.98%   |
| Denver                  | 1         | 0.98%   |
| Dell                    | 1         | 0.98%   |
| Chi Mei Optoelectronics | 1         | 0.98%   |
| BenQ                    | 1         | 0.98%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 1.94%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                       | 1         | 0.97%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 0.97%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 0.97%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.97%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 0.97%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 0.97%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.97%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                 | 1         | 0.97%   |
| SANYO LCD SAN0A12 1920x540                                             | 1         | 0.97%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1         | 0.97%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch   | 1         | 0.97%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.97%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1         | 0.97%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch      | 1         | 0.97%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1         | 0.97%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch    | 1         | 0.97%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.97%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch      | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 0.97%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.97%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch      | 1         | 0.97%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 0.97%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 0.97%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch               | 1         | 0.97%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch                | 1         | 0.97%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                    | 1         | 0.97%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                                | 1         | 0.97%   |
| ONN ONN50 ONN3458 3840x2160 575x323mm 26.0-inch                        | 1         | 0.97%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 0.97%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.97%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.97%   |
| LG Display LCD Monitor LGD056F 2736x1824 260x173mm 12.3-inch           | 1         | 0.97%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 43        | 44.33%  |
| 1366x768 (WXGA)    | 16        | 16.49%  |
| 3840x2160 (4K)     | 8         | 8.25%   |
| 2560x1440 (QHD)    | 5         | 5.15%   |
| 1920x1200 (WUXGA)  | 4         | 4.12%   |
| 1920x540           | 3         | 3.09%   |
| 1680x1050 (WSXGA+) | 3         | 3.09%   |
| 1600x900 (HD+)     | 3         | 3.09%   |
| 1280x800 (WXGA)    | 3         | 3.09%   |
| 3456x2160          | 1         | 1.03%   |
| 3440x1440          | 1         | 1.03%   |
| 2880x1800          | 1         | 1.03%   |
| 2736x1824          | 1         | 1.03%   |
| 2560x1600          | 1         | 1.03%   |
| 2240x1400          | 1         | 1.03%   |
| 1440x900 (WXGA+)   | 1         | 1.03%   |
| 1360x768           | 1         | 1.03%   |
| 1280x1024 (SXGA)   | 1         | 1.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 26.47%  |
| 13      | 16        | 15.69%  |
| 24      | 7         | 6.86%   |
| 14      | 7         | 6.86%   |
| 27      | 6         | 5.88%   |
| 23      | 5         | 4.9%    |
| 21      | 5         | 4.9%    |
| 17      | 5         | 4.9%    |
| Unknown | 4         | 3.92%   |
| 40      | 3         | 2.94%   |
| 11      | 3         | 2.94%   |
| 31      | 2         | 1.96%   |
| 84      | 1         | 0.98%   |
| 72      | 1         | 0.98%   |
| 60      | 1         | 0.98%   |
| 54      | 1         | 0.98%   |
| 47      | 1         | 0.98%   |
| 34      | 1         | 0.98%   |
| 33      | 1         | 0.98%   |
| 28      | 1         | 0.98%   |
| 26      | 1         | 0.98%   |
| 18      | 1         | 0.98%   |
| 12      | 1         | 0.98%   |
| 10      | 1         | 0.98%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 42        | 41.58%  |
| 501-600     | 17        | 16.83%  |
| 201-300     | 12        | 11.88%  |
| 401-500     | 7         | 6.93%   |
| 351-400     | 6         | 5.94%   |
| Unknown     | 4         | 3.96%   |
| 801-900     | 3         | 2.97%   |
| 601-700     | 3         | 2.97%   |
| 1001-1500   | 3         | 2.97%   |
| 701-800     | 2         | 1.98%   |
| 1501-2000   | 2         | 1.98%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 71        | 77.17%  |
| 16/10   | 14        | 15.22%  |
| 3/2     | 2         | 2.17%   |
| Unknown | 2         | 2.17%   |
| 4/3     | 1         | 1.09%   |
| 32/9    | 1         | 1.09%   |
| 21/9    | 1         | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 27%     |
| 81-90          | 19        | 19%     |
| 201-250        | 12        | 12%     |
| 301-350        | 6         | 6%      |
| 351-500        | 5         | 5%      |
| More than 1000 | 4         | 4%      |
| 71-80          | 4         | 4%      |
| 121-130        | 4         | 4%      |
| 501-1000       | 4         | 4%      |
| Unknown        | 4         | 4%      |
| 51-60          | 3         | 3%      |
| 251-300        | 3         | 3%      |
| 151-200        | 2         | 2%      |
| 61-70          | 1         | 1%      |
| 41-50          | 1         | 1%      |
| 141-150        | 1         | 1%      |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 31%     |
| 51-100        | 22        | 22%     |
| 101-120       | 21        | 21%     |
| 161-240       | 10        | 10%     |
| More than 240 | 6         | 6%      |
| 1-50          | 6         | 6%      |
| Unknown       | 4         | 4%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 80        | 85.11%  |
| 2     | 13        | 13.83%  |
| 0     | 1         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 37.31%  |
| Realtek Semiconductor | 46        | 34.33%  |
| Qualcomm Atheros      | 11        | 8.21%   |
| Broadcom              | 9         | 6.72%   |
| MediaTek              | 5         | 3.73%   |
| Nvidia                | 3         | 2.24%   |
| Broadcom Limited      | 3         | 2.24%   |
| Hewlett-Packard       | 2         | 1.49%   |
| ASIX Electronics      | 2         | 1.49%   |
| Ralink Technology     | 1         | 0.75%   |
| Microsoft             | 1         | 0.75%   |
| Huawei Technologies   | 1         | 0.75%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 17.09%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.8%    |
| Intel Wi-Fi 6 AX201                                               | 6         | 3.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 3.16%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.16%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 2.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.9%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.27%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.27%   |
| Intel Wireless 8260                                               | 2         | 1.27%   |
| Intel Wireless 7265                                               | 2         | 1.27%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.27%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.27%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.27%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.27%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.63%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.63%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.63%   |
| Realtek 802.11ac NIC                                              | 1         | 0.63%   |
| Ralink RT3072 Wireless Adapter                                    | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 50%     |
| Realtek Semiconductor | 16        | 20%     |
| Qualcomm Atheros      | 8         | 10%     |
| Broadcom              | 8         | 10%     |
| MediaTek              | 4         | 5%      |
| Ralink Technology     | 1         | 1.25%   |
| Microsoft             | 1         | 1.25%   |
| Hewlett-Packard       | 1         | 1.25%   |
| Broadcom Limited      | 1         | 1.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 6         | 7.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 6.25%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 6.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 5%      |
| Intel Wireless 8265 / 8275                                              | 3         | 3.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 2.5%    |
| Intel Wireless 8260                                                     | 2         | 2.5%    |
| Intel Wireless 7265                                                     | 2         | 2.5%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.5%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.5%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 2.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 2.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.25%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.25%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.25%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.25%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.25%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.25%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.25%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.25%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.25%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.25%   |
| Microsoft Wireless XBox Controller Dongle                               | 1         | 1.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 1.25%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.25%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.25%   |
| Intel Wireless 7260                                                     | 1         | 1.25%   |
| Intel Wireless 3165                                                     | 1         | 1.25%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 1.25%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 1.25%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 1         | 1.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1         | 1.25%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 54.05%  |
| Intel                 | 18        | 24.32%  |
| Broadcom              | 4         | 5.41%   |
| Qualcomm Atheros      | 3         | 4.05%   |
| Nvidia                | 3         | 4.05%   |
| Broadcom Limited      | 2         | 2.7%    |
| ASIX Electronics      | 2         | 2.7%    |
| MediaTek              | 1         | 1.35%   |
| Hewlett-Packard       | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 27        | 35.06%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 7.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.6%    |
| Nvidia MCP79 Ethernet                                             | 2         | 2.6%    |
| Intel I211 Gigabit Network Connection                             | 2         | 2.6%    |
| Intel Ethernet Controller I225-V                                  | 2         | 2.6%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.3%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.3%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.3%    |
| Nvidia MCP61 Ethernet                                             | 1         | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 1.3%    |
| Intel I210 Gigabit Network Connection                             | 1         | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.3%    |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.3%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.3%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.3%    |
| Intel 82578DC Gigabit Network Connection                          | 1         | 1.3%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.3%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.3%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.3%    |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.3%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.3%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 1.3%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.3%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1         | 1.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 78        | 51.66%  |
| Ethernet | 72        | 47.68%  |
| Modem    | 1         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 65.96%  |
| Ethernet | 32        | 34.04%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 50        | 53.76%  |
| 1     | 39        | 41.94%  |
| 0     | 4         | 4.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 71.58%  |
| Yes  | 27        | 28.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 52.24%  |
| Realtek Semiconductor           | 6         | 8.96%   |
| Qualcomm Atheros Communications | 5         | 7.46%   |
| Apple                           | 5         | 7.46%   |
| Broadcom                        | 4         | 5.97%   |
| IMC Networks                    | 3         | 4.48%   |
| Dell                            | 2         | 2.99%   |
| Cambridge Silicon Radio         | 2         | 2.99%   |
| Unknown                         | 1         | 1.49%   |
| MediaTek                        | 1         | 1.49%   |
| Lite-On Technology              | 1         | 1.49%   |
| Foxconn International           | 1         | 1.49%   |
| Foxconn / Hon Hai               | 1         | 1.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 11        | 16.42%  |
| Intel Bluetooth wireless interface                  | 10        | 14.93%  |
| Intel AX200 Bluetooth                               | 5         | 7.46%   |
| Realtek Bluetooth Radio                             | 4         | 5.97%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 5.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4.48%   |
| Apple Bluetooth USB Host Controller                 | 3         | 4.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.99%   |
| Intel AX210 Bluetooth                               | 2         | 2.99%   |
| IMC Networks Wireless_Device                        | 2         | 2.99%   |
| Dell DW375 Bluetooth Module                         | 2         | 2.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.99%   |
| Apple Bluetooth Host Controller                     | 2         | 2.99%   |
| Unknown Bluetooth Device                            | 1         | 1.49%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.49%   |
| MediaTek Wireless_Device                            | 1         | 1.49%   |
| Lite-On Bluetooth Radio                             | 1         | 1.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.49%   |
| Intel Bluetooth Device                              | 1         | 1.49%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.49%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.49%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.49%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 56.14%  |
| AMD                   | 25        | 21.93%  |
| Nvidia                | 18        | 15.79%  |
| Plantronics           | 2         | 1.75%   |
| Texas Instruments     | 1         | 0.88%   |
| Realtek Semiconductor | 1         | 0.88%   |
| Logitech              | 1         | 0.88%   |
| LINE TECH INDUSTRIAL  | 1         | 0.88%   |
| Apple                 | 1         | 0.88%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 9.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 10        | 7.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 5.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 5.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 4.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.94%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.21%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 2.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.21%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.47%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.47%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.47%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.47%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.47%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.74%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.74%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 0.74%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.74%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.74%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.74%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GF110 High Definition Audio Controller                              | 1         | 0.74%   |
| Logitech Logitech G PRO X Gaming Headset                                   | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 24.62%  |
| SK hynix            | 15        | 23.08%  |
| Kingston            | 9         | 13.85%  |
| Crucial             | 6         | 9.23%   |
| Micron Technology   | 5         | 7.69%   |
| Unknown (ABCD)      | 2         | 3.08%   |
| Ramaxel Technology  | 2         | 3.08%   |
| Elpida              | 2         | 3.08%   |
| Unknown             | 1         | 1.54%   |
| Transcend           | 1         | 1.54%   |
| Teikon              | 1         | 1.54%   |
| fef5                | 1         | 1.54%   |
| Corsair             | 1         | 1.54%   |
| A-DATA Technology   | 1         | 1.54%   |
| 8945000080AD        | 1         | 1.54%   |
| Unknown             | 1         | 1.54%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.94%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 2.94%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 2.94%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.47%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 1.47%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.47%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.47%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 1.47%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 1.47%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.47%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.47%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.47%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.47%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.47%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.47%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.47%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.47%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.47%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.47%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.47%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.47%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s             | 1         | 1.47%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.47%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.47%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.47%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.47%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.47%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 30        | 55.56%  |
| DDR3    | 14        | 25.93%  |
| LPDDR4  | 7         | 12.96%  |
| SDRAM   | 1         | 1.85%   |
| LPDDR3  | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 35        | 67.31%  |
| DIMM         | 10        | 19.23%  |
| Row Of Chips | 5         | 9.62%   |
| Chip         | 1         | 1.92%   |
| Unknown      | 1         | 1.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 43.64%  |
| 4096  | 13        | 23.64%  |
| 16384 | 9         | 16.36%  |
| 32768 | 4         | 7.27%   |
| 2048  | 4         | 7.27%   |
| 1024  | 1         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 13        | 22.41%  |
| 2667  | 10        | 17.24%  |
| 1600  | 10        | 17.24%  |
| 2400  | 9         | 15.52%  |
| 4267  | 3         | 5.17%   |
| 1333  | 3         | 5.17%   |
| 2133  | 2         | 3.45%   |
| 1067  | 2         | 3.45%   |
| 1066  | 2         | 3.45%   |
| 3600  | 1         | 1.72%   |
| 3266  | 1         | 1.72%   |
| 1867  | 1         | 1.72%   |
| 1334  | 1         | 1.72%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung ML-1510 Laser Printer | 1         | 33.33%  |
| HP LaserJet 1320              | 1         | 33.33%  |
| Canon LiDE 400                | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 22.03%  |
| IMC Networks                           | 8         | 13.56%  |
| Realtek Semiconductor                  | 5         | 8.47%   |
| Apple                                  | 5         | 8.47%   |
| Luxvisions Innotech Limited            | 4         | 6.78%   |
| Acer                                   | 4         | 6.78%   |
| Syntek                                 | 3         | 5.08%   |
| Sunplus Innovation Technology          | 3         | 5.08%   |
| Microdia                               | 3         | 5.08%   |
| Logitech                               | 3         | 5.08%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.39%   |
| Unknown                                | 1         | 1.69%   |
| Samsung Electronics                    | 1         | 1.69%   |
| Quanta                                 | 1         | 1.69%   |
| Polycom                                | 1         | 1.69%   |
| Alcor Micro                            | 1         | 1.69%   |
| Unknown                                | 1         | 1.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 5.08%   |
| Logitech HD Pro Webcam C920                                                | 3         | 5.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 5.08%   |
| IMC Networks Integrated Camera                                             | 3         | 5.08%   |
| Syntek Integrated Camera                                                   | 2         | 3.39%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 3.39%   |
| Chicony USB2.0 Camera                                                      | 2         | 3.39%   |
| Chicony Integrated Camera                                                  | 2         | 3.39%   |
| Chicony HD Webcam                                                          | 2         | 3.39%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.39%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 3.39%   |
| Unknown ATIV VGA CAMERA                                                    | 1         | 1.69%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.69%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.69%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.69%   |
| Sunplus HD WebCam                                                          | 1         | 1.69%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.69%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.69%   |
| Realtek Integrated Webcam                                                  | 1         | 1.69%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 1.69%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 1.69%   |
| Microdia Integrated_Webcam_HD                                              | 1         | 1.69%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.69%   |
| Microdia Camera                                                            | 1         | 1.69%   |
| Luxvisions Innotech Limited Integrated Camera                              | 1         | 1.69%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.69%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 1.69%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.69%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 1         | 1.69%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.69%   |
| Chicony HP Wide Vision FHD Camera                                          | 1         | 1.69%   |
| Chicony HP Truevision HD camera                                            | 1         | 1.69%   |
| Chicony HP Integrated Webcam                                               | 1         | 1.69%   |
| Chicony HP HD Camera                                                       | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 1         | 1.69%   |
| Apple iSight in LED Cinema Display                                         | 1         | 1.69%   |
| Apple FaceTime HD Camera (Built-in)                                        | 1         | 1.69%   |
| Apple Built-in iSight                                                      | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 35.71%  |
| Shenzhen Goodix Technology | 5         | 35.71%  |
| Validity Sensors           | 2         | 14.29%  |
| Elan Microelectronics      | 2         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                       | 2         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 14.29%  |
| Unknown                                                   | 2         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 7.14%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                               | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                     | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                          | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 62        | 66.67%  |
| 1     | 21        | 22.58%  |
| 2     | 7         | 7.53%   |
| 6     | 1         | 1.08%   |
| 4     | 1         | 1.08%   |
| 3     | 1         | 1.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 31.71%  |
| Net/wireless             | 5         | 12.2%   |
| Graphics card            | 5         | 12.2%   |
| Sound                    | 4         | 9.76%   |
| Unassigned class         | 3         | 7.32%   |
| Communication controller | 3         | 7.32%   |
| Chipcard                 | 2         | 4.88%   |
| Camera                   | 2         | 4.88%   |
| Bluetooth                | 2         | 4.88%   |
| Net/ethernet             | 1         | 2.44%   |
| Multimedia controller    | 1         | 2.44%   |


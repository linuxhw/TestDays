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

Total: 132

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3543               | Notebook    | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| Dell          | Latitude 7480               | Notebook    | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d73bb5ec34](https://linux-hardware.org/?probe=d73bb5ec34) | Mar 15, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | Notebook    | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-27-generic      | 11        | 10.38%  |
| 5.15.0-52-generic      | 9         | 8.49%   |
| 5.15.0-50-generic      | 7         | 6.6%    |
| 5.15.0-48-generic      | 6         | 5.66%   |
| 5.15.0-30-generic      | 6         | 5.66%   |
| 5.15.0-46-generic      | 5         | 4.72%   |
| 5.15.0-43-generic      | 5         | 4.72%   |
| 5.15.0-39-generic      | 5         | 4.72%   |
| 5.19.0-35-generic      | 4         | 3.77%   |
| 5.15.0-56-generic      | 4         | 3.77%   |
| 5.15.0-33-generic      | 4         | 3.77%   |
| 5.15.0-25-generic      | 4         | 3.77%   |
| 5.15.0-57-generic      | 3         | 2.83%   |
| 5.15.0-53-generic      | 3         | 2.83%   |
| 5.15.0-47-generic      | 3         | 2.83%   |
| 5.15.0-40-generic      | 3         | 2.83%   |
| 5.15.0-67-generic      | 2         | 1.89%   |
| 5.15.0-58-generic      | 2         | 1.89%   |
| 5.15.0-41-generic      | 2         | 1.89%   |
| 6.1.0-060100-generic   | 1         | 0.94%   |
| 5.19.0-051900-generic  | 1         | 0.94%   |
| 5.17.2-051702-generic  | 1         | 0.94%   |
| 5.16.2                 | 1         | 0.94%   |
| 5.15.92-051592-generic | 1         | 0.94%   |
| 5.15.0-60-generic      | 1         | 0.94%   |
| 5.15.0-52-lowlatency   | 1         | 0.94%   |
| 5.15.0-47-lowlatency   | 1         | 0.94%   |
| 5.15.0-35-generic      | 1         | 0.94%   |
| 5.15.0-18-generic      | 1         | 0.94%   |
| 5.15.0-10058-tuxedo    | 1         | 0.94%   |
| 5.15.0-10056-tuxedo    | 1         | 0.94%   |
| 5.15.0-10052-tuxedo    | 1         | 0.94%   |
| 5.15.0-10047-tuxedo    | 1         | 0.94%   |
| 5.15.0-10041-tuxedo    | 1         | 0.94%   |
| 5.13.0-44-generic      | 1         | 0.94%   |
| 5.13.0-35-generic      | 1         | 0.94%   |
| 5.13.0-19-generic      | 1         | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 89        | 88.12%  |
| 5.19.0  | 5         | 4.95%   |
| 5.13.0  | 3         | 2.97%   |
| 6.1.0   | 1         | 0.99%   |
| 5.17.2  | 1         | 0.99%   |
| 5.16.2  | 1         | 0.99%   |
| 5.15.92 | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 90        | 89.11%  |
| 5.19    | 5         | 4.95%   |
| 5.13    | 3         | 2.97%   |
| 6.1     | 1         | 0.99%   |
| 5.17    | 1         | 0.99%   |
| 5.16    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 97        | 97%     |
| GNOME  | 3         | 3%      |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 98        | 98%     |
| Wayland | 2         | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 70        | 70%     |
| Unknown | 21        | 21%     |
| GDM3    | 8         | 8%      |
| GDM     | 1         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 38        | 38%     |
| de_DE | 14        | 14%     |
| fr_FR | 9         | 9%      |
| en_GB | 7         | 7%      |
| pt_BR | 6         | 6%      |
| it_IT | 3         | 3%      |
| en_CA | 3         | 3%      |
| ru_RU | 2         | 2%      |
| hu_HU | 2         | 2%      |
| fr_BE | 2         | 2%      |
| es_MX | 2         | 2%      |
| es_ES | 2         | 2%      |
| mt_MT | 1         | 1%      |
| ja_JP | 1         | 1%      |
| es_PE | 1         | 1%      |
| es_EC | 1         | 1%      |
| es_CL | 1         | 1%      |
| en_NZ | 1         | 1%      |
| en_IE | 1         | 1%      |
| el_GR | 1         | 1%      |
| cs_CZ | 1         | 1%      |
| C     | 1         | 1%      |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 62        | 61.39%  |
| EFI  | 39        | 38.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 89        | 89%     |
| Overlay | 5         | 5%      |
| Btrfs   | 3         | 3%      |
| Zfs     | 2         | 2%      |
| Xfs     | 1         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 58        | 58%     |
| Unknown | 38        | 38%     |
| MBR     | 4         | 4%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 83%     |
| Yes       | 17        | 17%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 70        | 69.31%  |
| Yes       | 31        | 30.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 16        | 16%     |
| Hewlett-Packard        | 14        | 14%     |
| Dell                   | 14        | 14%     |
| ASUSTek Computer       | 11        | 11%     |
| Gigabyte Technology    | 8         | 8%      |
| MSI                    | 7         | 7%      |
| Apple                  | 6         | 6%      |
| TUXEDO                 | 5         | 5%      |
| Intel                  | 3         | 3%      |
| Google                 | 2         | 2%      |
| Fujitsu                | 2         | 2%      |
| ASRock                 | 2         | 2%      |
| Toshiba                | 1         | 1%      |
| Timi                   | 1         | 1%      |
| Samsung Electronics    | 1         | 1%      |
| Razer                  | 1         | 1%      |
| Digibras               | 1         | 1%      |
| Chuwi                  | 1         | 1%      |
| Biostar                | 1         | 1%      |
| AXIOO                  | 1         | 1%      |
| Avell High Performance | 1         | 1%      |
| Acer                   | 1         | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 1%      |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 1%      |
| TUXEDO Book XUX7 Gen11                               | 1         | 1%      |
| TUXEDO Book BA1510                                   | 1         | 1%      |
| TUXEDO Aura 15 Gen1                                  | 1         | 1%      |
| Toshiba Satellite A505                               | 1         | 1%      |
| Timi TM1604                                          | 1         | 1%      |
| Samsung 740U3M                                       | 1         | 1%      |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 1%      |
| MSI MS-7C95                                          | 1         | 1%      |
| MSI MS-7B86                                          | 1         | 1%      |
| MSI MS-7A32                                          | 1         | 1%      |
| MSI MS-7885                                          | 1         | 1%      |
| MSI Modern 15 A10M                                   | 1         | 1%      |
| MSI GL62 6QF                                         | 1         | 1%      |
| MSI Alpha 15 B5EEK                                   | 1         | 1%      |
| Lenovo V15 G2 ALC 82KD                               | 1         | 1%      |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 1%      |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 1%      |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 1%      |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 1%      |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 1%      |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 1%      |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 1%      |
| Lenovo IdeaPadFlex 5 14ALC7 82R9                     | 1         | 1%      |
| Lenovo IdeaPad Z500 20202                            | 1         | 1%      |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 1%      |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 1%      |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 1%      |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 1%      |
| Lenovo G500 20236                                    | 1         | 1%      |
| Lenovo G50-45 80E3                                   | 1         | 1%      |
| Intel STK1A32SC                                      | 1         | 1%      |
| Intel NUC12WSKi7                                     | 1         | 1%      |
| Intel DP55WB AAE64798-206                            | 1         | 1%      |
| HP Z440 Workstation                                  | 1         | 1%      |
| HP Spectre x360 Convertible 15t-df100                | 1         | 1%      |
| HP ProBook 450 G8 Notebook PC                        | 1         | 1%      |
| HP ProBook 450 G7                                    | 1         | 1%      |
| HP ProBook 445 G7                                    | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 5         | 5%      |
| Lenovo IdeaPad      | 5         | 5%      |
| Dell Inspiron       | 5         | 5%      |
| HP ProBook          | 3         | 3%      |
| Dell Latitude       | 3         | 3%      |
| ASUS VivoBook       | 3         | 3%      |
| TUXEDO Book         | 2         | 2%      |
| HP Pavilion         | 2         | 2%      |
| Dell XPS            | 2         | 2%      |
| Dell Precision      | 2         | 2%      |
| TUXEDO Polaris      | 1         | 1%      |
| TUXEDO InfinityBook | 1         | 1%      |
| TUXEDO Aura         | 1         | 1%      |
| Toshiba Satellite   | 1         | 1%      |
| Timi TM1604         | 1         | 1%      |
| Samsung 740U3M      | 1         | 1%      |
| Razer Blade         | 1         | 1%      |
| MSI MS-7C95         | 1         | 1%      |
| MSI MS-7B86         | 1         | 1%      |
| MSI MS-7A32         | 1         | 1%      |
| MSI MS-7885         | 1         | 1%      |
| MSI Modern          | 1         | 1%      |
| MSI GL62            | 1         | 1%      |
| MSI Alpha           | 1         | 1%      |
| Lenovo V15          | 1         | 1%      |
| Lenovo ThinkStation | 1         | 1%      |
| Lenovo Legion       | 1         | 1%      |
| Lenovo IdeaPadFlex  | 1         | 1%      |
| Lenovo G500         | 1         | 1%      |
| Lenovo G50-45       | 1         | 1%      |
| Intel STK1A32SC     | 1         | 1%      |
| Intel NUC12WSKi7    | 1         | 1%      |
| Intel DP55WB        | 1         | 1%      |
| HP Z440             | 1         | 1%      |
| HP Spectre          | 1         | 1%      |
| HP ENVY             | 1         | 1%      |
| HP ElitePad         | 1         | 1%      |
| HP EliteDesk        | 1         | 1%      |
| HP EliteBook        | 1         | 1%      |
| HP Elite            | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 15        | 15%     |
| 2020 | 14        | 14%     |
| 2014 | 10        | 10%     |
| 2018 | 9         | 9%      |
| 2019 | 8         | 8%      |
| 2016 | 7         | 7%      |
| 2017 | 5         | 5%      |
| 2010 | 5         | 5%      |
| 2022 | 4         | 4%      |
| 2015 | 4         | 4%      |
| 2013 | 4         | 4%      |
| 2012 | 4         | 4%      |
| 2011 | 4         | 4%      |
| 2009 | 4         | 4%      |
| 2008 | 3         | 3%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 61        | 61%     |
| Desktop     | 27        | 27%     |
| Convertible | 6         | 6%      |
| Mini pc     | 3         | 3%      |
| All in one  | 2         | 2%      |
| Tablet      | 1         | 1%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 94        | 94%     |
| Enabled  | 6         | 6%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 98%     |
| Yes  | 2         | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 30        | 29.7%   |
| 16.01-24.0      | 29        | 28.71%  |
| 8.01-16.0       | 18        | 17.82%  |
| 3.01-4.0        | 9         | 8.91%   |
| 32.01-64.0      | 8         | 7.92%   |
| 64.01-256.0     | 3         | 2.97%   |
| 1.01-2.0        | 2         | 1.98%   |
| More than 256.0 | 1         | 0.99%   |
| 24.01-32.0      | 1         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 35        | 33.65%  |
| 1.01-2.0   | 31        | 29.81%  |
| 4.01-8.0   | 20        | 19.23%  |
| 3.01-4.0   | 9         | 8.65%   |
| 8.01-16.0  | 7         | 6.73%   |
| 24.01-32.0 | 1         | 0.96%   |
| 16.01-24.0 | 1         | 0.96%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 60        | 58.82%  |
| 2      | 30        | 29.41%  |
| 3      | 5         | 4.9%    |
| 4      | 3         | 2.94%   |
| 6      | 2         | 1.96%   |
| 8      | 1         | 0.98%   |
| 7      | 1         | 0.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 72%     |
| Yes       | 28        | 28%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 79%     |
| No        | 21        | 21%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 86%     |
| No        | 14        | 14%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 73%     |
| No        | 27        | 27%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 23        | 23%     |
| Germany            | 13        | 13%     |
| France             | 9         | 9%      |
| Brazil             | 7         | 7%      |
| UK                 | 4         | 4%      |
| Italy              | 3         | 3%      |
| Switzerland        | 2         | 2%      |
| Slovenia           | 2         | 2%      |
| Netherlands        | 2         | 2%      |
| Mexico             | 2         | 2%      |
| Hungary            | 2         | 2%      |
| Greece             | 2         | 2%      |
| Canada             | 2         | 2%      |
| Belgium            | 2         | 2%      |
| Austria            | 2         | 2%      |
| Sweden             | 1         | 1%      |
| Spain              | 1         | 1%      |
| Saudi Arabia       | 1         | 1%      |
| Russia             | 1         | 1%      |
| Romania            | 1         | 1%      |
| Poland             | 1         | 1%      |
| Peru               | 1         | 1%      |
| Norway             | 1         | 1%      |
| New Zealand        | 1         | 1%      |
| Malta              | 1         | 1%      |
| Japan              | 1         | 1%      |
| Ireland            | 1         | 1%      |
| Indonesia          | 1         | 1%      |
| Ghana              | 1         | 1%      |
| Ecuador            | 1         | 1%      |
| Dominican Republic | 1         | 1%      |
| Czechia            | 1         | 1%      |
| Croatia            | 1         | 1%      |
| Chile              | 1         | 1%      |
| Cabo Verde         | 1         | 1%      |
| Belarus            | 1         | 1%      |
| Argentina          | 1         | 1%      |
| Algeria            | 1         | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Milwaukee             | 2         | 1.98%   |
| Budapest              | 2         | 1.98%   |
| Athens                | 2         | 1.98%   |
| Zurich                | 1         | 0.99%   |
| West Lafayette        | 1         | 0.99%   |
| Wertheim am Main      | 1         | 0.99%   |
| Weisswasser           | 1         | 0.99%   |
| Weilheim              | 1         | 0.99%   |
| Warsaw                | 1         | 0.99%   |
| Walled Lake           | 1         | 0.99%   |
| Vienna                | 1         | 0.99%   |
| Victoria              | 1         | 0.99%   |
| Venray                | 1         | 0.99%   |
| Vasto                 | 1         | 0.99%   |
| Trondheim             | 1         | 0.99%   |
| Tocantins             | 1         | 0.99%   |
| Targu Frumos          | 1         | 0.99%   |
| Tarakan               | 1         | 0.99%   |
| Tann                  | 1         | 0.99%   |
| Tampa                 | 1         | 0.99%   |
| Sunnyvale             | 1         | 0.99%   |
| St Petersburg         | 1         | 0.99%   |
| Siegen                | 1         | 0.99%   |
| Sétif                | 1         | 0.99%   |
| Seelze                | 1         | 0.99%   |
| Seattle               | 1         | 0.99%   |
| Sao Paulo             | 1         | 0.99%   |
| Sao Bernardo do Campo | 1         | 0.99%   |
| Santo Domingo Este    | 1         | 0.99%   |
| Santiago              | 1         | 0.99%   |
| San Luis Potosí City | 1         | 0.99%   |
| Saint-Gilles          | 1         | 0.99%   |
| Rueil-Malmaison       | 1         | 0.99%   |
| Rotterdam             | 1         | 0.99%   |
| Renton                | 1         | 0.99%   |
| Recife                | 1         | 0.99%   |
| Queens                | 1         | 0.99%   |
| Pula                  | 1         | 0.99%   |
| Puebla City           | 1         | 0.99%   |
| Praia                 | 1         | 0.99%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 24        | 44     | 16%     |
| Seagate                        | 16        | 22     | 10.67%  |
| Toshiba                        | 12        | 14     | 8%      |
| Unknown                        | 11        | 11     | 7.33%   |
| WDC                            | 10        | 12     | 6.67%   |
| Micron Technology              | 9         | 9      | 6%      |
| Crucial                        | 9         | 10     | 6%      |
| SK hynix                       | 6         | 6      | 4%      |
| Sandisk                        | 5         | 6      | 3.33%   |
| Intel                          | 5         | 7      | 3.33%   |
| Kingston                       | 4         | 5      | 2.67%   |
| SPCC                           | 3         | 3      | 2%      |
| OCZ                            | 3         | 3      | 2%      |
| JMicron Technology             | 3         | 3      | 2%      |
| China                          | 3         | 4      | 2%      |
| Phison                         | 2         | 2      | 1.33%   |
| Apple                          | 2         | 2      | 1.33%   |
| A-DATA Technology              | 2         | 2      | 1.33%   |
| Zheino                         | 1         | 1      | 0.67%   |
| VISIPRO                        | 1         | 1      | 0.67%   |
| Union Memory                   | 1         | 1      | 0.67%   |
| Transcend                      | 1         | 1      | 0.67%   |
| TO Exter                       | 1         | 1      | 0.67%   |
| Solid State Storage Technology | 1         | 1      | 0.67%   |
| SABRENT                        | 1         | 1      | 0.67%   |
| Realtek Semiconductor          | 1         | 1      | 0.67%   |
| PNY                            | 1         | 1      | 0.67%   |
| Phison Electronics             | 1         | 1      | 0.67%   |
| OWC                            | 1         | 1      | 0.67%   |
| Netac                          | 1         | 1      | 0.67%   |
| Mushkin                        | 1         | 1      | 0.67%   |
| Maxtor                         | 1         | 1      | 0.67%   |
| LITEON                         | 1         | 1      | 0.67%   |
| KIOXIA                         | 1         | 1      | 0.67%   |
| HGST                           | 1         | 1      | 0.67%   |
| Hewlett-Packard                | 1         | 1      | 0.67%   |
| Corsair                        | 1         | 2      | 0.67%   |
| ASMT109x                       | 1         | 1      | 0.67%   |
| Unknown                        | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 1.82%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 1.82%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.21%   |
| Unknown SD64G  64GB                    | 2         | 1.21%   |
| Unknown SD/MMC/MS PRO 64GB             | 2         | 1.21%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 1.21%   |
| Seagate ST1000LM014-1EJ164 1TB         | 2         | 1.21%   |
| SanDisk SDSSDA120G 120GB               | 2         | 1.21%   |
| Samsung SSD 980 PRO 2TB                | 2         | 1.21%   |
| Samsung SSD 980 500GB                  | 2         | 1.21%   |
| Samsung SSD 870 EVO 250GB              | 2         | 1.21%   |
| Samsung SSD 860 EVO M.2 500GB          | 2         | 1.21%   |
| Samsung SSD 850 PRO 256GB              | 2         | 1.21%   |
| Samsung SSD 850 EVO 500GB              | 2         | 1.21%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 1.21%   |
| Samsung MZVLQ512HALU-000H1 512GB       | 2         | 1.21%   |
| JMicron Generic 500GB                  | 2         | 1.21%   |
| Crucial CT1000MX500SSD1 1TB            | 2         | 1.21%   |
| Zheino CHN-25SATAC3-120 120GB          | 1         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.61%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.61%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1         | 0.61%   |
| WDC WD3200LPVX-22V0TT0 320GB           | 1         | 0.61%   |
| WDC WD1600AAJS-60WAA0 160GB            | 1         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB               | 1         | 0.61%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.61%   |
| WDC WD10EADS-00M2B0 1TB                | 1         | 0.61%   |
| WDC PC SN730 NVMe 256GB                | 1         | 0.61%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB   | 1         | 0.61%   |
| VISIPRO SSD 256GB                      | 1         | 0.61%   |
| Unknown SL128  128GB                   | 1         | 0.61%   |
| Unknown SA16G  16GB                    | 1         | 0.61%   |
| Unknown NCard  4GB                     | 1         | 0.61%   |
| Unknown MMC128  128GB                  | 1         | 0.61%   |
| Unknown MMC Card  64GB                 | 1         | 0.61%   |
| Unknown MMC Card  128GB                | 1         | 0.61%   |
| Unknown 00000  64GB                    | 1         | 0.61%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 0.61%   |
| Transcend TS128GMTE110S 128GB          | 1         | 0.61%   |
| Toshiba XG6 NVMe SSD Controller 512GB  | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 21     | 40%     |
| WDC                 | 8         | 9      | 20%     |
| Toshiba             | 7         | 7      | 17.5%   |
| Unknown             | 2         | 2      | 5%      |
| Samsung Electronics | 2         | 3      | 5%      |
| SABRENT             | 1         | 1      | 2.5%    |
| Maxtor              | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| ASMT109x            | 1         | 1      | 2.5%    |
| Apple               | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 25     | 19.23%  |
| Crucial             | 9         | 10     | 17.31%  |
| Micron Technology   | 4         | 4      | 7.69%   |
| China               | 3         | 4      | 5.77%   |
| SPCC                | 2         | 2      | 3.85%   |
| SanDisk             | 2         | 2      | 3.85%   |
| OCZ                 | 2         | 2      | 3.85%   |
| JMicron Technology  | 2         | 2      | 3.85%   |
| Zheino              | 1         | 1      | 1.92%   |
| WDC                 | 1         | 1      | 1.92%   |
| VISIPRO             | 1         | 1      | 1.92%   |
| Union Memory        | 1         | 1      | 1.92%   |
| Toshiba             | 1         | 1      | 1.92%   |
| TO Exter            | 1         | 1      | 1.92%   |
| SK hynix            | 1         | 1      | 1.92%   |
| PNY                 | 1         | 1      | 1.92%   |
| OWC                 | 1         | 1      | 1.92%   |
| Netac               | 1         | 1      | 1.92%   |
| Mushkin             | 1         | 1      | 1.92%   |
| LITEON              | 1         | 1      | 1.92%   |
| Kingston            | 1         | 2      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| Hewlett-Packard     | 1         | 1      | 1.92%   |
| Corsair             | 1         | 2      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |
| A-DATA Technology   | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 44        | 55     | 33.33%  |
| SSD     | 44        | 71     | 33.33%  |
| HDD     | 32        | 47     | 24.24%  |
| MMC     | 11        | 13     | 8.33%   |
| Unknown | 1         | 1      | 0.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 63        | 111    | 50.4%   |
| NVMe | 44        | 55     | 35.2%   |
| MMC  | 11        | 13     | 8.8%    |
| SAS  | 7         | 8      | 5.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 77     | 61.63%  |
| 0.51-1.0   | 23        | 29     | 26.74%  |
| 1.01-2.0   | 5         | 6      | 5.81%   |
| 3.01-4.0   | 4         | 4      | 4.65%   |
| 4.01-10.0  | 1         | 2      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 30        | 30%     |
| 101-250        | 29        | 29%     |
| 51-100         | 11        | 11%     |
| 501-1000       | 10        | 10%     |
| 1001-2000      | 6         | 6%      |
| 1-20           | 5         | 5%      |
| More than 3000 | 4         | 4%      |
| 21-50          | 4         | 4%      |
| 2001-3000      | 1         | 1%      |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 27        | 26.73%  |
| 1-20           | 27        | 26.73%  |
| 101-250        | 16        | 15.84%  |
| 51-100         | 15        | 14.85%  |
| 251-500        | 8         | 7.92%   |
| 501-1000       | 4         | 3.96%   |
| 1001-2000      | 2         | 1.98%   |
| More than 3000 | 1         | 0.99%   |
| 2001-3000      | 1         | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 33.33%  |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Apple  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 65        | 115    | 59.09%  |
| Works    | 41        | 68     | 37.27%  |
| Malfunc  | 3         | 3      | 2.73%   |
| Failed   | 1         | 1      | 0.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 61        | 48.03%  |
| AMD                            | 18        | 14.17%  |
| Samsung Electronics            | 14        | 11.02%  |
| Micron Technology              | 5         | 3.94%   |
| SanDisk                        | 4         | 3.15%   |
| Toshiba America Info Systems   | 3         | 2.36%   |
| SK hynix                       | 3         | 2.36%   |
| Phison Electronics             | 3         | 2.36%   |
| Nvidia                         | 3         | 2.36%   |
| Kingston Technology Company    | 3         | 2.36%   |
| KIOXIA                         | 2         | 1.57%   |
| Transcend                      | 1         | 0.79%   |
| Solid State Storage Technology | 1         | 0.79%   |
| Seagate Technology             | 1         | 0.79%   |
| Realtek Semiconductor          | 1         | 0.79%   |
| OCZ Technology Group           | 1         | 0.79%   |
| Marvell Technology Group       | 1         | 0.79%   |
| JMicron Technology             | 1         | 0.79%   |
| ADATA Technology               | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 12        | 8.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 7         | 4.9%    |
| Samsung NVMe SSD Controller 980                                              | 5         | 3.5%    |
| Intel Volume Management Device NVMe RAID Controller                          | 5         | 3.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 3.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 4         | 2.8%    |
| Micron NVMe Storage Controller                                               | 4         | 2.8%    |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 2.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 2.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.4%    |
| Phison PS5013 E13 NVMe Controller                                            | 2         | 1.4%    |
| Nvidia MCP79 AHCI Controller                                                 | 2         | 1.4%    |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                          | 2         | 1.4%    |
| Intel NVMe Controller                                                        | 2         | 1.4%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                   | 2         | 1.4%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]             | 2         | 1.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode] | 2         | 1.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 2         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 2         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 1.4%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 2         | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 2         | 1.4%    |
| AMD FCH IDE Controller                                                       | 2         | 1.4%    |
| AMD 500 Series Chipset SATA Controller                                       | 2         | 1.4%    |
| AMD 400 Series Chipset SATA Controller                                       | 2         | 1.4%    |
| Transcend Non-Volatile memory controller                                     | 1         | 0.7%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.7%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.7%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.7%    |
| Solid State Storage Non-Volatile memory controller                           | 1         | 0.7%    |
| SK hynix Non-Volatile memory controller                                      | 1         | 0.7%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.7%    |
| Seagate Non-Volatile memory controller                                       | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 69        | 52.67%  |
| NVMe | 44        | 33.59%  |
| IDE  | 10        | 7.63%   |
| RAID | 8         | 6.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 77        | 77%     |
| AMD    | 23        | 23%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 5%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 3%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 3%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 2%      |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 2%      |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 2%      |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 2%      |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 2%      |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 2%      |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 2%      |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 2%      |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 2%      |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2%      |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 2%      |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 1%      |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 1%      |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 1%      |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 1%      |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 1%      |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1%      |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 1%      |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1%      |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 1%      |
| Intel Core i7-5820K CPU @ 3.30GHz             | 1         | 1%      |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 1%      |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 1%      |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 1%      |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 1%      |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 1%      |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 1%      |
| Intel Core i5-8350U CPU @ 1.70GHz             | 1         | 1%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1%      |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 1%      |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 1%      |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 1%      |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 21        | 21%     |
| Intel Core i7        | 15        | 15%     |
| Other                | 13        | 13%     |
| AMD Ryzen 5          | 9         | 9%      |
| Intel Core i3        | 6         | 6%      |
| Intel Celeron        | 6         | 6%      |
| Intel Xeon           | 4         | 4%      |
| Intel Atom           | 4         | 4%      |
| AMD Ryzen 7          | 4         | 4%      |
| Intel Core 2 Duo     | 3         | 3%      |
| Intel Pentium        | 2         | 2%      |
| Intel Pentium Silver | 1         | 1%      |
| Intel Core i9        | 1         | 1%      |
| Intel Core 2 Quad    | 1         | 1%      |
| AMD Ryzen 9          | 1         | 1%      |
| AMD Ryzen 3          | 1         | 1%      |
| AMD Phenom II X4     | 1         | 1%      |
| AMD FX               | 1         | 1%      |
| AMD Athlon X4        | 1         | 1%      |
| AMD Athlon II X3     | 1         | 1%      |
| AMD Athlon           | 1         | 1%      |
| AMD A8               | 1         | 1%      |
| AMD A4               | 1         | 1%      |
| AMD A10              | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 42        | 42%     |
| 2      | 35        | 35%     |
| 8      | 9         | 9%      |
| 6      | 8         | 8%      |
| 12     | 2         | 2%      |
| 16     | 1         | 1%      |
| 10     | 1         | 1%      |
| 3      | 1         | 1%      |
| 1      | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 98        | 98%     |
| 2      | 2         | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 73        | 73%     |
| 1      | 27        | 27%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 54.37%  |
| 0x806ec    | 4         | 3.88%   |
| 0x306a9    | 4         | 3.88%   |
| 0x806c1    | 3         | 2.91%   |
| 0x206a7    | 3         | 2.91%   |
| 0x08600106 | 3         | 2.91%   |
| 0x08108102 | 3         | 2.91%   |
| 0x706a8    | 2         | 1.94%   |
| 0x406f1    | 2         | 1.94%   |
| 0x20655    | 2         | 1.94%   |
| 0x0a50000c | 2         | 1.94%   |
| 0xa0671    | 1         | 0.97%   |
| 0x906eb    | 1         | 0.97%   |
| 0x906ea    | 1         | 0.97%   |
| 0x906a3    | 1         | 0.97%   |
| 0x806eb    | 1         | 0.97%   |
| 0x806e9    | 1         | 0.97%   |
| 0x806d1    | 1         | 0.97%   |
| 0x506c9    | 1         | 0.97%   |
| 0x406c4    | 1         | 0.97%   |
| 0x40651    | 1         | 0.97%   |
| 0x306d4    | 1         | 0.97%   |
| 0x30678    | 1         | 0.97%   |
| 0x106e5    | 1         | 0.97%   |
| 0x1067a    | 1         | 0.97%   |
| 0x10677    | 1         | 0.97%   |
| 0x08608104 | 1         | 0.97%   |
| 0x08108109 | 1         | 0.97%   |
| 0x07030104 | 1         | 0.97%   |
| 0x06001119 | 1         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 18%     |
| TigerLake        | 8         | 8%      |
| IvyBridge        | 8         | 8%      |
| Zen+             | 6         | 6%      |
| Unknown          | 6         | 6%      |
| Zen 3            | 5         | 5%      |
| Penryn           | 5         | 5%      |
| Broadwell        | 5         | 5%      |
| Skylake          | 4         | 4%      |
| Silvermont       | 4         | 4%      |
| Haswell          | 4         | 4%      |
| Zen 2            | 3         | 3%      |
| Westmere         | 3         | 3%      |
| SandyBridge      | 3         | 3%      |
| Icelake          | 3         | 3%      |
| Goldmont plus    | 3         | 3%      |
| Nehalem          | 2         | 2%      |
| K10              | 2         | 2%      |
| Steamroller      | 1         | 1%      |
| Puma             | 1         | 1%      |
| Piledriver       | 1         | 1%      |
| Goldmont         | 1         | 1%      |
| Excavator        | 1         | 1%      |
| CometLake        | 1         | 1%      |
| Bulldozer        | 1         | 1%      |
| Alderlake Hybrid | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 65        | 55.56%  |
| Nvidia | 27        | 23.08%  |
| AMD    | 25        | 21.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 6.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 4.17%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 4.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 4.17%   |
| Intel UHD Graphics 620                                                    | 4         | 3.33%   |
| Intel HD Graphics 620                                                     | 4         | 3.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.33%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 2.5%    |
| Intel HD Graphics 5500                                                    | 3         | 2.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 3         | 2.5%    |
| AMD Renoir                                                                | 3         | 2.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 1.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.67%   |
| Intel JasperLake [UHD Graphics]                                           | 2         | 1.67%   |
| Intel HD Graphics 530                                                     | 2         | 1.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.67%   |
| AMD Lucienne                                                              | 2         | 1.67%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2         | 1.67%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.83%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.83%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.83%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.83%   |
| Nvidia GP104GL [Quadro P4000]                                             | 1         | 0.83%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.83%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.83%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 0.83%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.83%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.83%   |
| Nvidia GK110 [GeForce GTX 780]                                            | 1         | 0.83%   |
| Nvidia GK106 [GeForce GTX 660]                                            | 1         | 0.83%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                         | 1         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 48%     |
| 1 x AMD        | 19        | 19%     |
| 1 x Nvidia     | 13        | 13%     |
| Intel + Nvidia | 12        | 12%     |
| 2 x AMD        | 2         | 2%      |
| Intel + AMD    | 2         | 2%      |
| AMD + Nvidia   | 2         | 2%      |
| Other          | 1         | 1%      |
| 2 x Intel      | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 85        | 85%     |
| Proprietary | 13        | 13%     |
| Unknown     | 2         | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 77%     |
| 1.01-2.0   | 8         | 8%      |
| 0.01-0.5   | 7         | 7%      |
| 7.01-8.0   | 3         | 3%      |
| 0.51-1.0   | 3         | 3%      |
| 3.01-4.0   | 2         | 2%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 19        | 17.27%  |
| Chimei Innolux          | 18        | 16.36%  |
| BOE                     | 17        | 15.45%  |
| AU Optronics            | 10        | 9.09%   |
| LG Display              | 8         | 7.27%   |
| Apple                   | 5         | 4.55%   |
| Hewlett-Packard         | 4         | 3.64%   |
| Sharp                   | 3         | 2.73%   |
| Philips                 | 3         | 2.73%   |
| SANYO                   | 2         | 1.82%   |
| Goldstar                | 2         | 1.82%   |
| Dell                    | 2         | 1.82%   |
| AOC                     | 2         | 1.82%   |
| Vestel Elektronik       | 1         | 0.91%   |
| Unknown (XXX)           | 1         | 0.91%   |
| Unknown (AAA)           | 1         | 0.91%   |
| Sony                    | 1         | 0.91%   |
| Panasonic               | 1         | 0.91%   |
| ONN                     | 1         | 0.91%   |
| MStar                   | 1         | 0.91%   |
| LG Electronics          | 1         | 0.91%   |
| Lenovo                  | 1         | 0.91%   |
| IBM                     | 1         | 0.91%   |
| HKC                     | 1         | 0.91%   |
| Fujitsu Siemens         | 1         | 0.91%   |
| Denver                  | 1         | 0.91%   |
| Chi Mei Optoelectronics | 1         | 0.91%   |
| BenQ                    | 1         | 0.91%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 1.79%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.89%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 0.89%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 0.89%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.89%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 0.89%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 0.89%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.89%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                 | 1         | 0.89%   |
| SANYO LCD SAN0A12 1920x540                                             | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch   | 1         | 0.89%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.89%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1         | 0.89%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch      | 1         | 0.89%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1         | 0.89%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch    | 1         | 0.89%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.89%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch      | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 0.89%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.89%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch      | 1         | 0.89%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 0.89%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 0.89%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch               | 1         | 0.89%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch                | 1         | 0.89%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                    | 1         | 0.89%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                                | 1         | 0.89%   |
| ONN ONN50 ONN3458 3840x2160 575x323mm 26.0-inch                        | 1         | 0.89%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 0.89%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.89%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.89%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.89%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 42.45%  |
| 1366x768 (WXGA)    | 20        | 18.87%  |
| 3840x2160 (4K)     | 9         | 8.49%   |
| 2560x1440 (QHD)    | 6         | 5.66%   |
| 1920x1200 (WUXGA)  | 5         | 4.72%   |
| 1920x540           | 3         | 2.83%   |
| 1680x1050 (WSXGA+) | 3         | 2.83%   |
| 1600x900 (HD+)     | 3         | 2.83%   |
| 1280x800 (WXGA)    | 3         | 2.83%   |
| 3456x2160          | 1         | 0.94%   |
| 3440x1440          | 1         | 0.94%   |
| 2880x1800          | 1         | 0.94%   |
| 2736x1824          | 1         | 0.94%   |
| 2560x1600          | 1         | 0.94%   |
| 2240x1400          | 1         | 0.94%   |
| 1440x900 (WXGA+)   | 1         | 0.94%   |
| 1360x768           | 1         | 0.94%   |
| 1280x1024 (SXGA)   | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 32        | 28.83%  |
| 13      | 16        | 14.41%  |
| 24      | 8         | 7.21%   |
| 14      | 8         | 7.21%   |
| 27      | 7         | 6.31%   |
| 23      | 5         | 4.5%    |
| 21      | 5         | 4.5%    |
| 17      | 5         | 4.5%    |
| Unknown | 4         | 3.6%    |
| 40      | 3         | 2.7%    |
| 11      | 3         | 2.7%    |
| 84      | 2         | 1.8%    |
| 31      | 2         | 1.8%    |
| 72      | 1         | 0.9%    |
| 60      | 1         | 0.9%    |
| 54      | 1         | 0.9%    |
| 47      | 1         | 0.9%    |
| 34      | 1         | 0.9%    |
| 33      | 1         | 0.9%    |
| 28      | 1         | 0.9%    |
| 26      | 1         | 0.9%    |
| 18      | 1         | 0.9%    |
| 12      | 1         | 0.9%    |
| 10      | 1         | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 44.04%  |
| 501-600     | 18        | 16.51%  |
| 201-300     | 12        | 11.01%  |
| 401-500     | 7         | 6.42%   |
| 351-400     | 6         | 5.5%    |
| Unknown     | 4         | 3.67%   |
| 801-900     | 3         | 2.75%   |
| 601-700     | 3         | 2.75%   |
| 1501-2000   | 3         | 2.75%   |
| 1001-1500   | 3         | 2.75%   |
| 701-800     | 2         | 1.83%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 78        | 78%     |
| 16/10   | 15        | 15%     |
| 3/2     | 2         | 2%      |
| Unknown | 2         | 2%      |
| 4/3     | 1         | 1%      |
| 32/9    | 1         | 1%      |
| 21/9    | 1         | 1%      |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 29.36%  |
| 81-90          | 20        | 18.35%  |
| 201-250        | 12        | 11.01%  |
| 301-350        | 7         | 6.42%   |
| More than 1000 | 5         | 4.59%   |
| 351-500        | 5         | 4.59%   |
| 71-80          | 4         | 3.67%   |
| 251-300        | 4         | 3.67%   |
| 121-130        | 4         | 3.67%   |
| 501-1000       | 4         | 3.67%   |
| Unknown        | 4         | 3.67%   |
| 51-60          | 3         | 2.75%   |
| 151-200        | 2         | 1.83%   |
| 61-70          | 1         | 0.92%   |
| 41-50          | 1         | 0.92%   |
| 141-150        | 1         | 0.92%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 33        | 30.28%  |
| 101-120       | 26        | 23.85%  |
| 51-100        | 24        | 22.02%  |
| 161-240       | 10        | 9.17%   |
| More than 240 | 6         | 5.5%    |
| 1-50          | 6         | 5.5%    |
| Unknown       | 4         | 3.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 85        | 84.16%  |
| 2     | 15        | 14.85%  |
| 0     | 1         | 0.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 52        | 35.62%  |
| Realtek Semiconductor | 50        | 34.25%  |
| Qualcomm Atheros      | 12        | 8.22%   |
| Broadcom              | 11        | 7.53%   |
| MediaTek              | 6         | 4.11%   |
| Nvidia                | 3         | 2.05%   |
| Broadcom Limited      | 3         | 2.05%   |
| Hewlett-Packard       | 2         | 1.37%   |
| ASIX Electronics      | 2         | 1.37%   |
| TP-Link               | 1         | 0.68%   |
| Ralink Technology     | 1         | 0.68%   |
| Microsoft             | 1         | 0.68%   |
| JMicron Technology    | 1         | 0.68%   |
| Huawei Technologies   | 1         | 0.68%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 16.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 4.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.47%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.89%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.31%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 2.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.73%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.73%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.16%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.16%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.16%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.16%   |
| Intel Wireless 8260                                               | 2         | 1.16%   |
| Intel Wireless 7265                                               | 2         | 1.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.16%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.16%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.16%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.16%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.58%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.58%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.58%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.58%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 47.19%  |
| Realtek Semiconductor | 17        | 19.1%   |
| Broadcom              | 10        | 11.24%  |
| Qualcomm Atheros      | 9         | 10.11%  |
| MediaTek              | 6         | 6.74%   |
| TP-Link               | 1         | 1.12%   |
| Ralink Technology     | 1         | 1.12%   |
| Microsoft             | 1         | 1.12%   |
| Hewlett-Packard       | 1         | 1.12%   |
| Broadcom Limited      | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 6         | 6.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 5.62%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 5.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 5.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.49%   |
| Intel Wireless 8265 / 8275                                              | 4         | 4.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 4.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 3.37%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 3.37%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 3.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.25%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 2.25%   |
| Intel Wireless 8260                                                     | 2         | 2.25%   |
| Intel Wireless 7265                                                     | 2         | 2.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 2.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.25%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.12%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.12%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.12%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.12%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.12%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.12%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.12%   |
| Microsoft Wireless XBox Controller Dongle                               | 1         | 1.12%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.12%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.12%   |
| Intel Wireless 7260                                                     | 1         | 1.12%   |
| Intel Wireless 3165                                                     | 1         | 1.12%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.12%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 55%     |
| Intel                 | 19        | 23.75%  |
| Broadcom              | 5         | 6.25%   |
| Qualcomm Atheros      | 3         | 3.75%   |
| Nvidia                | 3         | 3.75%   |
| Broadcom Limited      | 2         | 2.5%    |
| ASIX Electronics      | 2         | 2.5%    |
| JMicron Technology    | 1         | 1.25%   |
| Hewlett-Packard       | 1         | 1.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 34.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 8.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 7.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.41%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.41%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.41%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.41%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.41%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 2.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.2%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.2%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.2%    |
| Nvidia MCP61 Ethernet                                             | 1         | 1.2%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.2%    |
| Intel I210 Gigabit Network Connection                             | 1         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.2%    |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.2%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.2%    |
| Intel 82578DC Gigabit Network Connection                          | 1         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.2%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.2%    |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.2%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 1.2%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.2%    |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1         | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 52.12%  |
| Ethernet | 78        | 47.27%  |
| Modem    | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 69        | 68.32%  |
| Ethernet | 32        | 31.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 57        | 57%     |
| 1     | 39        | 39%     |
| 0     | 4         | 4%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 74        | 72.55%  |
| Yes  | 28        | 27.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 50.68%  |
| Realtek Semiconductor           | 6         | 8.22%   |
| Apple                           | 6         | 8.22%   |
| Qualcomm Atheros Communications | 5         | 6.85%   |
| Broadcom                        | 5         | 6.85%   |
| IMC Networks                    | 3         | 4.11%   |
| MediaTek                        | 2         | 2.74%   |
| Dell                            | 2         | 2.74%   |
| Cambridge Silicon Radio         | 2         | 2.74%   |
| Smart Modular Technologies      | 1         | 1.37%   |
| Realtek                         | 1         | 1.37%   |
| Lite-On Technology              | 1         | 1.37%   |
| Foxconn International           | 1         | 1.37%   |
| Foxconn / Hon Hai               | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 15.07%  |
| Intel AX201 Bluetooth                               | 11        | 15.07%  |
| Intel AX200 Bluetooth                               | 5         | 6.85%   |
| Realtek Bluetooth Radio                             | 4         | 5.48%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 5.48%   |
| Apple Bluetooth USB Host Controller                 | 4         | 5.48%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4.11%   |
| MediaTek Wireless_Device                            | 2         | 2.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.74%   |
| Intel AX210 Bluetooth                               | 2         | 2.74%   |
| IMC Networks Wireless_Device                        | 2         | 2.74%   |
| Dell DW375 Bluetooth Module                         | 2         | 2.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.74%   |
| Apple Bluetooth Host Controller                     | 2         | 2.74%   |
| Smart Modular Bluetooth Device                      | 1         | 1.37%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.37%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.37%   |
| Realtek Bluetooth Radio                             | 1         | 1.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.37%   |
| Lite-On Bluetooth Radio                             | 1         | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.37%   |
| Intel Bluetooth Device                              | 1         | 1.37%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.37%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.37%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.37%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.37%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 57.85%  |
| AMD                   | 26        | 21.49%  |
| Nvidia                | 18        | 14.88%  |
| Plantronics           | 2         | 1.65%   |
| Texas Instruments     | 1         | 0.83%   |
| Realtek Semiconductor | 1         | 0.83%   |
| Logitech              | 1         | 0.83%   |
| LINE TECH INDUSTRIAL  | 1         | 0.83%   |
| Apple                 | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 9.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 7.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 6.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 5.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.44%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.4%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.72%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 2.04%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 2.04%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 3         | 2.04%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.36%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.36%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.36%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.36%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.36%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.68%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.68%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 0.68%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.68%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.68%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.68%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 16        | 23.53%  |
| Samsung Electronics | 16        | 23.53%  |
| Kingston            | 10        | 14.71%  |
| Micron Technology   | 6         | 8.82%   |
| Crucial             | 6         | 8.82%   |
| Elpida              | 3         | 4.41%   |
| Unknown (ABCD)      | 2         | 2.94%   |
| Ramaxel Technology  | 2         | 2.94%   |
| Unknown             | 1         | 1.47%   |
| Transcend           | 1         | 1.47%   |
| Teikon              | 1         | 1.47%   |
| fef5                | 1         | 1.47%   |
| Corsair             | 1         | 1.47%   |
| A-DATA Technology   | 1         | 1.47%   |
| 8945000080AD        | 1         | 1.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.82%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 2.82%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 2.82%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 2.82%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.41%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 1.41%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.41%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.41%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 1.41%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 1.41%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.41%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.41%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.41%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.41%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.41%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.41%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.41%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.41%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 1         | 1.41%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.41%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s             | 1         | 1.41%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.41%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 1         | 1.41%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.41%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 30        | 53.57%  |
| DDR3    | 16        | 28.57%  |
| LPDDR4  | 7         | 12.5%   |
| SDRAM   | 1         | 1.79%   |
| LPDDR3  | 1         | 1.79%   |
| Unknown | 1         | 1.79%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 68.52%  |
| DIMM         | 10        | 18.52%  |
| Row Of Chips | 5         | 9.26%   |
| Chip         | 1         | 1.85%   |
| Unknown      | 1         | 1.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 43.86%  |
| 4096  | 14        | 24.56%  |
| 16384 | 9         | 15.79%  |
| 32768 | 4         | 7.02%   |
| 2048  | 4         | 7.02%   |
| 1024  | 1         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 13        | 21.31%  |
| 1600  | 12        | 19.67%  |
| 2667  | 10        | 16.39%  |
| 2400  | 9         | 14.75%  |
| 4267  | 3         | 4.92%   |
| 1333  | 3         | 4.92%   |
| 2133  | 2         | 3.28%   |
| 1334  | 2         | 3.28%   |
| 1067  | 2         | 3.28%   |
| 1066  | 2         | 3.28%   |
| 3600  | 1         | 1.64%   |
| 3266  | 1         | 1.64%   |
| 1867  | 1         | 1.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Dymo-CoStar         | 1         | 25%     |
| Canon               | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung ML-1510 Laser Printer | 1         | 25%     |
| HP LaserJet 1320              | 1         | 25%     |
| Dymo-CoStar LabelWriter 450   | 1         | 25%     |
| Canon LiDE 400                | 1         | 25%     |

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
| Chicony Electronics                    | 16        | 24.62%  |
| IMC Networks                           | 8         | 12.31%  |
| Realtek Semiconductor                  | 6         | 9.23%   |
| Luxvisions Innotech Limited            | 5         | 7.69%   |
| Apple                                  | 5         | 7.69%   |
| Microdia                               | 4         | 6.15%   |
| Acer                                   | 4         | 6.15%   |
| Syntek                                 | 3         | 4.62%   |
| Sunplus Innovation Technology          | 3         | 4.62%   |
| Logitech                               | 3         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.08%   |
| Unknown                                | 1         | 1.54%   |
| Samsung Electronics                    | 1         | 1.54%   |
| Quanta                                 | 1         | 1.54%   |
| Polycom                                | 1         | 1.54%   |
| Alcor Micro                            | 1         | 1.54%   |
| Unknown                                | 1         | 1.54%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 3         | 4.62%   |
| Logitech HD Pro Webcam C920                                                | 3         | 4.62%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 3         | 4.62%   |
| IMC Networks Integrated Camera                                             | 3         | 4.62%   |
| Syntek Integrated Camera                                                   | 2         | 3.08%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 3.08%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 3.08%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 3.08%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 3.08%   |
| Chicony USB2.0 Camera                                                      | 2         | 3.08%   |
| Chicony Integrated Camera                                                  | 2         | 3.08%   |
| Apple FaceTime HD Camera                                                   | 2         | 3.08%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 3.08%   |
| Unknown ATIV VGA CAMERA                                                    | 1         | 1.54%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.54%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.54%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.54%   |
| Sunplus HD WebCam                                                          | 1         | 1.54%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.54%   |
| Realtek Lenovo EasyCamera                                                  | 1         | 1.54%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.54%   |
| Realtek Integrated Webcam                                                  | 1         | 1.54%   |
| Quanta USB2.0 HD UVC WebCam                                                | 1         | 1.54%   |
| Polycom Poly Studio P5 webcam                                              | 1         | 1.54%   |
| Microdia Integrated Webcam HD                                              | 1         | 1.54%   |
| Microdia Camera                                                            | 1         | 1.54%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 1.54%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.54%   |
| IMC Networks Integrated RGB Camera                                         | 1         | 1.54%   |
| Chicony XiaoMi USB 2.0 Webcam                                              | 1         | 1.54%   |
| Chicony USB2.0 UVC WebCam                                                  | 1         | 1.54%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.54%   |
| Chicony Lenovo EasyCamera                                                  | 1         | 1.54%   |
| Chicony Integrated IR Camera                                               | 1         | 1.54%   |
| Chicony HP Wide Vision FHD Camera                                          | 1         | 1.54%   |
| Chicony HP Truevision HD camera                                            | 1         | 1.54%   |
| Chicony HP Integrated Webcam                                               | 1         | 1.54%   |
| Chicony HP HD Camera                                                       | 1         | 1.54%   |
| Chicony HD Webcam                                                          | 1         | 1.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 35.71%  |
| Shenzhen Goodix Technology | 5         | 35.71%  |
| Validity Sensors           | 2         | 14.29%  |
| Elan Microelectronics      | 2         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                       | 2         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 7.14%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 7.14%   |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 7.14%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 1         | 7.14%   |
| Shenzhen Goodix FingerPrint                               | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                     | 1         | 7.14%   |
| Elan ELAN:ARM-M4                                          | 1         | 7.14%   |
| Unknown                                                   | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 33.33%  |
| Broadcom 5880                                  | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 68        | 68%     |
| 1     | 21        | 21%     |
| 2     | 8         | 8%      |
| 6     | 1         | 1%      |
| 4     | 1         | 1%      |
| 3     | 1         | 1%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 30.23%  |
| Graphics card            | 6         | 13.95%  |
| Net/wireless             | 5         | 11.63%  |
| Sound                    | 4         | 9.3%    |
| Unassigned class         | 3         | 6.98%   |
| Communication controller | 3         | 6.98%   |
| Chipcard                 | 3         | 6.98%   |
| Camera                   | 2         | 4.65%   |
| Bluetooth                | 2         | 4.65%   |
| Net/ethernet             | 1         | 2.33%   |
| Multimedia controller    | 1         | 2.33%   |


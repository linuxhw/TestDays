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

Total: 139

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b3ac75c53e](https://linux-hardware.org/?probe=b3ac75c53e) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [f87233a295](https://linux-hardware.org/?probe=f87233a295) | Apr 29, 2023 |
| Intel         | H61                         | Desktop     | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [090405a4a7](https://linux-hardware.org/?probe=090405a4a7) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-27-generic      | 11        | 9.82%   |
| 5.15.0-52-generic      | 9         | 8.04%   |
| 5.15.0-50-generic      | 7         | 6.25%   |
| 5.15.0-48-generic      | 6         | 5.36%   |
| 5.15.0-30-generic      | 6         | 5.36%   |
| 5.15.0-46-generic      | 5         | 4.46%   |
| 5.15.0-43-generic      | 5         | 4.46%   |
| 5.15.0-39-generic      | 5         | 4.46%   |
| 5.19.0-35-generic      | 4         | 3.57%   |
| 5.15.0-56-generic      | 4         | 3.57%   |
| 5.15.0-33-generic      | 4         | 3.57%   |
| 5.15.0-25-generic      | 4         | 3.57%   |
| 5.15.0-57-generic      | 3         | 2.68%   |
| 5.15.0-53-generic      | 3         | 2.68%   |
| 5.15.0-47-generic      | 3         | 2.68%   |
| 5.15.0-40-generic      | 3         | 2.68%   |
| 5.19.0-40-generic      | 2         | 1.79%   |
| 5.19.0-38-generic      | 2         | 1.79%   |
| 5.15.0-67-generic      | 2         | 1.79%   |
| 5.15.0-58-generic      | 2         | 1.79%   |
| 5.15.0-41-generic      | 2         | 1.79%   |
| 6.1.0-060100-generic   | 1         | 0.89%   |
| 5.19.0-41-generic      | 1         | 0.89%   |
| 5.19.0-051900-generic  | 1         | 0.89%   |
| 5.17.2-051702-generic  | 1         | 0.89%   |
| 5.16.2                 | 1         | 0.89%   |
| 5.15.92-051592-generic | 1         | 0.89%   |
| 5.15.0-69-generic      | 1         | 0.89%   |
| 5.15.0-60-generic      | 1         | 0.89%   |
| 5.15.0-52-lowlatency   | 1         | 0.89%   |
| 5.15.0-47-lowlatency   | 1         | 0.89%   |
| 5.15.0-35-generic      | 1         | 0.89%   |
| 5.15.0-18-generic      | 1         | 0.89%   |
| 5.15.0-10058-tuxedo    | 1         | 0.89%   |
| 5.15.0-10056-tuxedo    | 1         | 0.89%   |
| 5.15.0-10052-tuxedo    | 1         | 0.89%   |
| 5.15.0-10047-tuxedo    | 1         | 0.89%   |
| 5.15.0-10041-tuxedo    | 1         | 0.89%   |
| 5.13.0-44-generic      | 1         | 0.89%   |
| 5.13.0-35-generic      | 1         | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 90        | 84.11%  |
| 5.19.0  | 10        | 9.35%   |
| 5.13.0  | 3         | 2.8%    |
| 6.1.0   | 1         | 0.93%   |
| 5.17.2  | 1         | 0.93%   |
| 5.16.2  | 1         | 0.93%   |
| 5.15.92 | 1         | 0.93%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 91        | 85.05%  |
| 5.19    | 10        | 9.35%   |
| 5.13    | 3         | 2.8%    |
| 6.1     | 1         | 0.93%   |
| 5.17    | 1         | 0.93%   |
| 5.16    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 106       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 103       | 97.17%  |
| GNOME  | 3         | 2.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 104       | 98.11%  |
| Wayland | 2         | 1.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 74        | 69.81%  |
| Unknown | 23        | 21.7%   |
| GDM3    | 8         | 7.55%   |
| GDM     | 1         | 0.94%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 40        | 37.74%  |
| de_DE | 14        | 13.21%  |
| fr_FR | 10        | 9.43%   |
| pt_BR | 7         | 6.6%    |
| en_GB | 7         | 6.6%    |
| it_IT | 3         | 2.83%   |
| en_CA | 3         | 2.83%   |
| ru_RU | 2         | 1.89%   |
| hu_HU | 2         | 1.89%   |
| fr_BE | 2         | 1.89%   |
| es_MX | 2         | 1.89%   |
| es_ES | 2         | 1.89%   |
| en_IE | 2         | 1.89%   |
| pl_PL | 1         | 0.94%   |
| mt_MT | 1         | 0.94%   |
| ja_JP | 1         | 0.94%   |
| es_PE | 1         | 0.94%   |
| es_EC | 1         | 0.94%   |
| es_CL | 1         | 0.94%   |
| en_NZ | 1         | 0.94%   |
| el_GR | 1         | 0.94%   |
| cs_CZ | 1         | 0.94%   |
| C     | 1         | 0.94%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 66        | 61.68%  |
| EFI  | 41        | 38.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 95        | 89.62%  |
| Overlay | 5         | 4.72%   |
| Btrfs   | 3         | 2.83%   |
| Zfs     | 2         | 1.89%   |
| Xfs     | 1         | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 62        | 58.49%  |
| Unknown | 40        | 37.74%  |
| MBR     | 4         | 3.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 87        | 82.08%  |
| Yes       | 19        | 17.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 74        | 69.16%  |
| Yes       | 33        | 30.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 17        | 16.04%  |
| Hewlett-Packard        | 15        | 14.15%  |
| Dell                   | 14        | 13.21%  |
| ASUSTek Computer       | 14        | 13.21%  |
| Gigabyte Technology    | 8         | 7.55%   |
| MSI                    | 7         | 6.6%    |
| Apple                  | 6         | 5.66%   |
| TUXEDO                 | 5         | 4.72%   |
| Intel                  | 4         | 3.77%   |
| Google                 | 2         | 1.89%   |
| Fujitsu                | 2         | 1.89%   |
| ASRock                 | 2         | 1.89%   |
| Toshiba                | 1         | 0.94%   |
| Timi                   | 1         | 0.94%   |
| Samsung Electronics    | 1         | 0.94%   |
| Razer                  | 1         | 0.94%   |
| Digibras               | 1         | 0.94%   |
| Chuwi                  | 1         | 0.94%   |
| Biostar                | 1         | 0.94%   |
| AXIOO                  | 1         | 0.94%   |
| Avell High Performance | 1         | 0.94%   |
| Acer                   | 1         | 0.94%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 0.94%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 0.94%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 0.94%   |
| TUXEDO Book BA1510                                   | 1         | 0.94%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 0.94%   |
| Toshiba Satellite A505                               | 1         | 0.94%   |
| Timi TM1604                                          | 1         | 0.94%   |
| Samsung 740U3M                                       | 1         | 0.94%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 0.94%   |
| MSI MS-7C95                                          | 1         | 0.94%   |
| MSI MS-7B86                                          | 1         | 0.94%   |
| MSI MS-7A32                                          | 1         | 0.94%   |
| MSI MS-7885                                          | 1         | 0.94%   |
| MSI Modern 15 A10M                                   | 1         | 0.94%   |
| MSI GL62 6QF                                         | 1         | 0.94%   |
| MSI Alpha 15 B5EEK                                   | 1         | 0.94%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 0.94%   |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 0.94%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 0.94%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 0.94%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 0.94%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 0.94%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 0.94%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 0.94%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 0.94%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9                     | 1         | 0.94%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 0.94%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 0.94%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 0.94%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 0.94%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 0.94%   |
| Lenovo G500 20236                                    | 1         | 0.94%   |
| Lenovo G50-45 80E3                                   | 1         | 0.94%   |
| Intel STK1A32SC                                      | 1         | 0.94%   |
| Intel NUC12WSKi7                                     | 1         | 0.94%   |
| Intel H61                                            | 1         | 0.94%   |
| Intel DP55WB AAE64798-206                            | 1         | 0.94%   |
| HP Z440 Workstation                                  | 1         | 0.94%   |
| HP Spectre x360 Convertible 15t-df100                | 1         | 0.94%   |
| HP ProBook 450 G8 Notebook PC                        | 1         | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 6         | 5.66%   |
| Lenovo IdeaPad      | 5         | 4.72%   |
| Dell Inspiron       | 5         | 4.72%   |
| ASUS VivoBook       | 4         | 3.77%   |
| HP ProBook          | 3         | 2.83%   |
| Dell Latitude       | 3         | 2.83%   |
| TUXEDO Book         | 2         | 1.89%   |
| HP Pavilion         | 2         | 1.89%   |
| HP EliteBook        | 2         | 1.89%   |
| Dell XPS            | 2         | 1.89%   |
| Dell Precision      | 2         | 1.89%   |
| TUXEDO Polaris      | 1         | 0.94%   |
| TUXEDO InfinityBook | 1         | 0.94%   |
| TUXEDO Aura         | 1         | 0.94%   |
| Toshiba Satellite   | 1         | 0.94%   |
| Timi TM1604         | 1         | 0.94%   |
| Samsung 740U3M      | 1         | 0.94%   |
| Razer Blade         | 1         | 0.94%   |
| MSI MS-7C95         | 1         | 0.94%   |
| MSI MS-7B86         | 1         | 0.94%   |
| MSI MS-7A32         | 1         | 0.94%   |
| MSI MS-7885         | 1         | 0.94%   |
| MSI Modern          | 1         | 0.94%   |
| MSI GL62            | 1         | 0.94%   |
| MSI Alpha           | 1         | 0.94%   |
| Lenovo V15          | 1         | 0.94%   |
| Lenovo ThinkStation | 1         | 0.94%   |
| Lenovo Legion       | 1         | 0.94%   |
| Lenovo IdeaPadFlex  | 1         | 0.94%   |
| Lenovo G500         | 1         | 0.94%   |
| Lenovo G50-45       | 1         | 0.94%   |
| Intel STK1A32SC     | 1         | 0.94%   |
| Intel NUC12WSKi7    | 1         | 0.94%   |
| Intel H61           | 1         | 0.94%   |
| Intel DP55WB        | 1         | 0.94%   |
| HP Z440             | 1         | 0.94%   |
| HP Spectre          | 1         | 0.94%   |
| HP ENVY             | 1         | 0.94%   |
| HP ElitePad         | 1         | 0.94%   |
| HP EliteDesk        | 1         | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 15        | 14.15%  |
| 2020 | 15        | 14.15%  |
| 2018 | 10        | 9.43%   |
| 2014 | 10        | 9.43%   |
| 2019 | 8         | 7.55%   |
| 2016 | 7         | 6.6%    |
| 2017 | 6         | 5.66%   |
| 2015 | 6         | 5.66%   |
| 2022 | 5         | 4.72%   |
| 2010 | 5         | 4.72%   |
| 2013 | 4         | 3.77%   |
| 2012 | 4         | 3.77%   |
| 2011 | 4         | 3.77%   |
| 2009 | 4         | 3.77%   |
| 2008 | 3         | 2.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 65        | 61.32%  |
| Desktop     | 29        | 27.36%  |
| Convertible | 6         | 5.66%   |
| Mini pc     | 3         | 2.83%   |
| All in one  | 2         | 1.89%   |
| Tablet      | 1         | 0.94%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 100       | 94.34%  |
| Enabled  | 6         | 5.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 104       | 98.11%  |
| Yes  | 2         | 1.89%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 33        | 30.84%  |
| 16.01-24.0      | 31        | 28.97%  |
| 8.01-16.0       | 18        | 16.82%  |
| 3.01-4.0        | 9         | 8.41%   |
| 32.01-64.0      | 8         | 7.48%   |
| 64.01-256.0     | 4         | 3.74%   |
| 1.01-2.0        | 2         | 1.87%   |
| More than 256.0 | 1         | 0.93%   |
| 24.01-32.0      | 1         | 0.93%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 36        | 32.73%  |
| 1.01-2.0   | 31        | 28.18%  |
| 4.01-8.0   | 23        | 20.91%  |
| 3.01-4.0   | 11        | 10%     |
| 8.01-16.0  | 7         | 6.36%   |
| 24.01-32.0 | 1         | 0.91%   |
| 16.01-24.0 | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 59.26%  |
| 2      | 31        | 28.7%   |
| 3      | 6         | 5.56%   |
| 4      | 3         | 2.78%   |
| 6      | 2         | 1.85%   |
| 8      | 1         | 0.93%   |
| 7      | 1         | 0.93%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 78        | 73.58%  |
| Yes       | 28        | 26.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 79.25%  |
| No        | 22        | 20.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 85.85%  |
| No        | 15        | 14.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 73.58%  |
| No        | 28        | 26.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 24        | 22.64%  |
| Germany            | 13        | 12.26%  |
| France             | 10        | 9.43%   |
| Brazil             | 8         | 7.55%   |
| UK                 | 4         | 3.77%   |
| Italy              | 3         | 2.83%   |
| Switzerland        | 2         | 1.89%   |
| Slovenia           | 2         | 1.89%   |
| Poland             | 2         | 1.89%   |
| Netherlands        | 2         | 1.89%   |
| Mexico             | 2         | 1.89%   |
| Ireland            | 2         | 1.89%   |
| Hungary            | 2         | 1.89%   |
| Greece             | 2         | 1.89%   |
| Canada             | 2         | 1.89%   |
| Belgium            | 2         | 1.89%   |
| Austria            | 2         | 1.89%   |
| Sweden             | 1         | 0.94%   |
| Spain              | 1         | 0.94%   |
| Saudi Arabia       | 1         | 0.94%   |
| Russia             | 1         | 0.94%   |
| Romania            | 1         | 0.94%   |
| Peru               | 1         | 0.94%   |
| Norway             | 1         | 0.94%   |
| New Zealand        | 1         | 0.94%   |
| Malta              | 1         | 0.94%   |
| Japan              | 1         | 0.94%   |
| Indonesia          | 1         | 0.94%   |
| Ghana              | 1         | 0.94%   |
| Ecuador            | 1         | 0.94%   |
| Dominican Republic | 1         | 0.94%   |
| Czechia            | 1         | 0.94%   |
| Croatia            | 1         | 0.94%   |
| Chile              | 1         | 0.94%   |
| Cabo Verde         | 1         | 0.94%   |
| Bulgaria           | 1         | 0.94%   |
| Belarus            | 1         | 0.94%   |
| Argentina          | 1         | 0.94%   |
| Algeria            | 1         | 0.94%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 1.87%   |
| Milwaukee             | 2         | 1.87%   |
| Dublin                | 2         | 1.87%   |
| Budapest              | 2         | 1.87%   |
| Brasília             | 2         | 1.87%   |
| Athens                | 2         | 1.87%   |
| Zurich                | 1         | 0.93%   |
| West Lafayette        | 1         | 0.93%   |
| Wertheim am Main      | 1         | 0.93%   |
| Weisswasser           | 1         | 0.93%   |
| Weilheim              | 1         | 0.93%   |
| Walled Lake           | 1         | 0.93%   |
| Vienna                | 1         | 0.93%   |
| Victoria              | 1         | 0.93%   |
| Venray                | 1         | 0.93%   |
| Vasto                 | 1         | 0.93%   |
| Trondheim             | 1         | 0.93%   |
| Tocantins             | 1         | 0.93%   |
| Targu Frumos          | 1         | 0.93%   |
| Tarakan               | 1         | 0.93%   |
| Tann                  | 1         | 0.93%   |
| Tampa                 | 1         | 0.93%   |
| Sunnyvale             | 1         | 0.93%   |
| St Petersburg         | 1         | 0.93%   |
| Sofia                 | 1         | 0.93%   |
| Siegen                | 1         | 0.93%   |
| Sétif                | 1         | 0.93%   |
| Seelze                | 1         | 0.93%   |
| Seattle               | 1         | 0.93%   |
| Sao Paulo             | 1         | 0.93%   |
| Sao Bernardo do Campo | 1         | 0.93%   |
| Santo Domingo Este    | 1         | 0.93%   |
| Santiago              | 1         | 0.93%   |
| San Luis Potosí City | 1         | 0.93%   |
| San Diego             | 1         | 0.93%   |
| Saint-Gilles          | 1         | 0.93%   |
| Rueil-Malmaison       | 1         | 0.93%   |
| Rotterdam             | 1         | 0.93%   |
| Renton                | 1         | 0.93%   |
| Recife                | 1         | 0.93%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 26        | 47     | 16.46%  |
| Seagate                        | 18        | 24     | 11.39%  |
| Toshiba                        | 12        | 14     | 7.59%   |
| WDC                            | 11        | 13     | 6.96%   |
| Unknown                        | 11        | 11     | 6.96%   |
| Micron Technology              | 9         | 9      | 5.7%    |
| Crucial                        | 9         | 10     | 5.7%    |
| SK hynix                       | 6         | 6      | 3.8%    |
| SanDisk                        | 6         | 7      | 3.8%    |
| Intel                          | 6         | 8      | 3.8%    |
| Kingston                       | 4         | 5      | 2.53%   |
| SPCC                           | 3         | 3      | 1.9%    |
| OCZ                            | 3         | 3      | 1.9%    |
| JMicron Technology             | 3         | 3      | 1.9%    |
| China                          | 3         | 4      | 1.9%    |
| Phison                         | 2         | 2      | 1.27%   |
| Apple                          | 2         | 2      | 1.27%   |
| A-DATA Technology              | 2         | 2      | 1.27%   |
| Zheino                         | 1         | 1      | 0.63%   |
| VISIPRO                        | 1         | 1      | 0.63%   |
| Union Memory                   | 1         | 1      | 0.63%   |
| Transcend                      | 1         | 1      | 0.63%   |
| TO Exter                       | 1         | 1      | 0.63%   |
| Solid State Storage Technology | 1         | 1      | 0.63%   |
| SABRENT                        | 1         | 1      | 0.63%   |
| Realtek Semiconductor          | 1         | 1      | 0.63%   |
| PNY                            | 1         | 1      | 0.63%   |
| Phison Electronics             | 1         | 1      | 0.63%   |
| OWC                            | 1         | 1      | 0.63%   |
| Netac                          | 1         | 1      | 0.63%   |
| Mushkin                        | 1         | 1      | 0.63%   |
| Maxtor                         | 1         | 1      | 0.63%   |
| LITEON                         | 1         | 1      | 0.63%   |
| KIOXIA                         | 1         | 1      | 0.63%   |
| HGST                           | 1         | 1      | 0.63%   |
| Hewlett-Packard                | 1         | 1      | 0.63%   |
| Corsair                        | 1         | 2      | 0.63%   |
| ASMT109x                       | 1         | 1      | 0.63%   |
| 4Life                          | 1         | 1      | 0.63%   |
| Unknown                        | 1         | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 1.72%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 1.72%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 1.15%   |
| Unknown SD64G  64GB                    | 2         | 1.15%   |
| Unknown SD/MMC/MS PRO 249GB            | 2         | 1.15%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 1.15%   |
| Seagate ST1000LM014-1EJ164 1TB         | 2         | 1.15%   |
| SanDisk SDSSDA120G 120GB               | 2         | 1.15%   |
| Samsung SSD 980 PRO 2TB                | 2         | 1.15%   |
| Samsung SSD 980 500GB                  | 2         | 1.15%   |
| Samsung SSD 870 EVO 250GB              | 2         | 1.15%   |
| Samsung SSD 860 EVO M.2 500GB          | 2         | 1.15%   |
| Samsung SSD 850 PRO 256GB              | 2         | 1.15%   |
| Samsung SSD 850 EVO 500GB              | 2         | 1.15%   |
| Samsung NVMe SSD Drive 256GB           | 2         | 1.15%   |
| Samsung MZVLQ512HALU-000H1 512GB       | 2         | 1.15%   |
| JMicron Generic 1TB                    | 2         | 1.15%   |
| Crucial CT1000MX500SSD1 1TB            | 2         | 1.15%   |
| Zheino CHN-25SATAC3-120 120GB          | 1         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.57%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 1         | 0.57%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1         | 0.57%   |
| WDC WD3200LPVX-22V0TT0 320GB           | 1         | 0.57%   |
| WDC WD1600AAJS-60WAA0 160GB            | 1         | 0.57%   |
| WDC WD10JPVX-75JC3T0 1TB               | 1         | 0.57%   |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.57%   |
| WDC WD10EADS-00M2B0 1TB                | 1         | 0.57%   |
| WDC PC SN730 NVMe 256GB                | 1         | 0.57%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB   | 1         | 0.57%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB   | 1         | 0.57%   |
| VISIPRO SSD 256GB                      | 1         | 0.57%   |
| Unknown SL128  128GB                   | 1         | 0.57%   |
| Unknown SA16G  16GB                    | 1         | 0.57%   |
| Unknown NCard  4GB                     | 1         | 0.57%   |
| Unknown MMC128  128GB                  | 1         | 0.57%   |
| Unknown MMC Card  64GB                 | 1         | 0.57%   |
| Unknown MMC Card  128GB                | 1         | 0.57%   |
| Unknown 00000  64GB                    | 1         | 0.57%   |
| Union Memory RTOTJ128VGD2EYX 128GB SSD | 1         | 0.57%   |
| Transcend TS128GMTE110S 128GB          | 1         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 23     | 41.86%  |
| WDC                 | 8         | 9      | 18.6%   |
| Toshiba             | 7         | 7      | 16.28%  |
| Unknown             | 2         | 2      | 4.65%   |
| Samsung Electronics | 2         | 3      | 4.65%   |
| JMicron Technology  | 2         | 2      | 4.65%   |
| Maxtor              | 1         | 1      | 2.33%   |
| HGST                | 1         | 1      | 2.33%   |
| ASMT109x            | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 27     | 22.22%  |
| Crucial             | 9         | 10     | 16.67%  |
| Micron Technology   | 4         | 4      | 7.41%   |
| SanDisk             | 3         | 3      | 5.56%   |
| China               | 3         | 4      | 5.56%   |
| SPCC                | 2         | 2      | 3.7%    |
| OCZ                 | 2         | 2      | 3.7%    |
| Zheino              | 1         | 1      | 1.85%   |
| WDC                 | 1         | 1      | 1.85%   |
| VISIPRO             | 1         | 1      | 1.85%   |
| Union Memory        | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| TO Exter            | 1         | 1      | 1.85%   |
| SK hynix            | 1         | 1      | 1.85%   |
| PNY                 | 1         | 1      | 1.85%   |
| OWC                 | 1         | 1      | 1.85%   |
| Netac               | 1         | 1      | 1.85%   |
| Mushkin             | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| Kingston            | 1         | 2      | 1.85%   |
| Intel               | 1         | 1      | 1.85%   |
| Hewlett-Packard     | 1         | 1      | 1.85%   |
| Corsair             | 1         | 2      | 1.85%   |
| Apple               | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |
| 4Life               | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 48        | 73     | 34.04%  |
| NVMe    | 47        | 59     | 33.33%  |
| HDD     | 34        | 50     | 24.11%  |
| MMC     | 11        | 13     | 7.8%    |
| Unknown | 1         | 1      | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 117    | 50.76%  |
| NVMe | 47        | 58     | 35.61%  |
| MMC  | 11        | 13     | 8.33%   |
| SAS  | 7         | 8      | 5.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 77     | 59.34%  |
| 0.51-1.0   | 26        | 32     | 28.57%  |
| 3.01-4.0   | 5         | 6      | 5.49%   |
| 1.01-2.0   | 5         | 6      | 5.49%   |
| 4.01-10.0  | 1         | 2      | 1.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 29.25%  |
| 101-250        | 31        | 29.25%  |
| 501-1000       | 11        | 10.38%  |
| 51-100         | 11        | 10.38%  |
| 1001-2000      | 7         | 6.6%    |
| More than 3000 | 5         | 4.72%   |
| 1-20           | 5         | 4.72%   |
| 21-50          | 4         | 3.77%   |
| 2001-3000      | 1         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 26.17%  |
| 21-50          | 27        | 25.23%  |
| 101-250        | 18        | 16.82%  |
| 51-100         | 16        | 14.95%  |
| 251-500        | 9         | 8.41%   |
| 501-1000       | 4         | 3.74%   |
| 1001-2000      | 3         | 2.8%    |
| More than 3000 | 1         | 0.93%   |
| 2001-3000      | 1         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 1      | 33.33%  |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 33.33%  |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Apple  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 70        | 123    | 60.34%  |
| Works    | 42        | 69     | 36.21%  |
| Malfunc  | 3         | 3      | 2.59%   |
| Failed   | 1         | 1      | 0.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 65        | 48.51%  |
| AMD                            | 19        | 14.18%  |
| Samsung Electronics            | 15        | 11.19%  |
| SanDisk                        | 5         | 3.73%   |
| Micron Technology              | 5         | 3.73%   |
| Toshiba America Info Systems   | 3         | 2.24%   |
| SK hynix                       | 3         | 2.24%   |
| Phison Electronics             | 3         | 2.24%   |
| Nvidia                         | 3         | 2.24%   |
| Kingston Technology Company    | 3         | 2.24%   |
| KIOXIA                         | 2         | 1.49%   |
| Transcend                      | 1         | 0.75%   |
| Solid State Storage Technology | 1         | 0.75%   |
| Seagate Technology             | 1         | 0.75%   |
| Realtek Semiconductor          | 1         | 0.75%   |
| OCZ Technology Group           | 1         | 0.75%   |
| Marvell Technology Group       | 1         | 0.75%   |
| JMicron Technology             | 1         | 0.75%   |
| ADATA Technology               | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                          | 13        | 8.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 9         | 5.92%   |
| Samsung NVMe SSD Controller 980                                              | 6         | 3.95%   |
| Intel Volume Management Device NVMe RAID Controller                          | 6         | 3.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 3.29%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 4         | 2.63%   |
| Micron NVMe Storage Controller                                               | 4         | 2.63%   |
| Intel Comet Lake SATA AHCI Controller                                        | 4         | 2.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 3         | 1.97%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 1.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 3         | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 1.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 2         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 2         | 1.32%   |
| Phison PS5013 E13 NVMe Controller                                            | 2         | 1.32%   |
| Nvidia MCP79 AHCI Controller                                                 | 2         | 1.32%   |
| KIOXIA NVMe SSD Controller BG4                                               | 2         | 1.32%   |
| Intel NVMe Controller                                                        | 2         | 1.32%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                   | 2         | 1.32%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]             | 2         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.32%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode] | 2         | 1.32%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                         | 2         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                | 2         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 2         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                | 2         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 2         | 1.32%   |
| AMD FCH IDE Controller                                                       | 2         | 1.32%   |
| AMD 500 Series Chipset SATA Controller                                       | 2         | 1.32%   |
| AMD 400 Series Chipset SATA Controller                                       | 2         | 1.32%   |
| Transcend Non-Volatile memory controller                                     | 1         | 0.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 1         | 0.66%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                         | 1         | 0.66%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                         | 1         | 0.66%   |
| Solid State Storage Non-Volatile memory controller                           | 1         | 0.66%   |
| SK hynix Non-Volatile memory controller                                      | 1         | 0.66%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                               | 1         | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive                                        | 1         | 0.66%   |
| Seagate Non-Volatile memory controller                                       | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 74        | 52.86%  |
| NVMe | 47        | 33.57%  |
| IDE  | 10        | 7.14%   |
| RAID | 9         | 6.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 82        | 77.36%  |
| AMD    | 24        | 22.64%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 4.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.89%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.89%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.89%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.89%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 1.89%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.89%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 1.89%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.89%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.89%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.89%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.89%   |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 0.94%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.94%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 0.94%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 0.94%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.94%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.94%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.94%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.94%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.94%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 1         | 0.94%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.94%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 0.94%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.94%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 0.94%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.94%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.94%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.94%   |
| Intel Core i5-7360U CPU @ 2.30GHz             | 1         | 0.94%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1         | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 23        | 21.7%   |
| Intel Core i7        | 17        | 16.04%  |
| Other                | 14        | 13.21%  |
| AMD Ryzen 5          | 9         | 8.49%   |
| Intel Core i3        | 6         | 5.66%   |
| Intel Celeron        | 6         | 5.66%   |
| Intel Xeon           | 4         | 3.77%   |
| Intel Atom           | 4         | 3.77%   |
| AMD Ryzen 7          | 4         | 3.77%   |
| Intel Core 2 Duo     | 3         | 2.83%   |
| Intel Pentium        | 2         | 1.89%   |
| AMD Ryzen 9          | 2         | 1.89%   |
| Intel Pentium Silver | 1         | 0.94%   |
| Intel Core i9        | 1         | 0.94%   |
| Intel Core 2 Quad    | 1         | 0.94%   |
| AMD Ryzen 3          | 1         | 0.94%   |
| AMD Phenom II X4     | 1         | 0.94%   |
| AMD FX               | 1         | 0.94%   |
| AMD Athlon X4        | 1         | 0.94%   |
| AMD Athlon II X3     | 1         | 0.94%   |
| AMD Athlon           | 1         | 0.94%   |
| AMD A8               | 1         | 0.94%   |
| AMD A4               | 1         | 0.94%   |
| AMD A10              | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 45        | 42.45%  |
| 2      | 37        | 34.91%  |
| 8      | 9         | 8.49%   |
| 6      | 8         | 7.55%   |
| 12     | 3         | 2.83%   |
| 16     | 1         | 0.94%   |
| 10     | 1         | 0.94%   |
| 3      | 1         | 0.94%   |
| 1      | 1         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 98.11%  |
| 2      | 2         | 1.89%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 79        | 74.53%  |
| 1      | 27        | 25.47%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 106       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 55.05%  |
| 0x806ec    | 4         | 3.67%   |
| 0x806c1    | 4         | 3.67%   |
| 0x306a9    | 4         | 3.67%   |
| 0x206a7    | 3         | 2.75%   |
| 0x08600106 | 3         | 2.75%   |
| 0x08108102 | 3         | 2.75%   |
| 0x706a8    | 2         | 1.83%   |
| 0x406f1    | 2         | 1.83%   |
| 0x20655    | 2         | 1.83%   |
| 0x0a50000c | 2         | 1.83%   |
| 0xa0671    | 1         | 0.92%   |
| 0x906eb    | 1         | 0.92%   |
| 0x906ea    | 1         | 0.92%   |
| 0x906a3    | 1         | 0.92%   |
| 0x806eb    | 1         | 0.92%   |
| 0x806ea    | 1         | 0.92%   |
| 0x806e9    | 1         | 0.92%   |
| 0x806d1    | 1         | 0.92%   |
| 0x506c9    | 1         | 0.92%   |
| 0x406c4    | 1         | 0.92%   |
| 0x40651    | 1         | 0.92%   |
| 0x306d4    | 1         | 0.92%   |
| 0x30678    | 1         | 0.92%   |
| 0x106e5    | 1         | 0.92%   |
| 0x1067a    | 1         | 0.92%   |
| 0x10677    | 1         | 0.92%   |
| 0x08608104 | 1         | 0.92%   |
| 0x08108109 | 1         | 0.92%   |
| 0x07030104 | 1         | 0.92%   |
| 0x06001119 | 1         | 0.92%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 19        | 17.92%  |
| TigerLake        | 9         | 8.49%   |
| IvyBridge        | 8         | 7.55%   |
| Unknown          | 7         | 6.6%    |
| Zen+             | 6         | 5.66%   |
| Skylake          | 6         | 5.66%   |
| Zen 3            | 5         | 4.72%   |
| Penryn           | 5         | 4.72%   |
| Broadwell        | 5         | 4.72%   |
| Silvermont       | 4         | 3.77%   |
| SandyBridge      | 4         | 3.77%   |
| Haswell          | 4         | 3.77%   |
| Zen 2            | 3         | 2.83%   |
| Westmere         | 3         | 2.83%   |
| Icelake          | 3         | 2.83%   |
| Goldmont plus    | 3         | 2.83%   |
| Nehalem          | 2         | 1.89%   |
| K10              | 2         | 1.89%   |
| Steamroller      | 1         | 0.94%   |
| Puma             | 1         | 0.94%   |
| Piledriver       | 1         | 0.94%   |
| Goldmont         | 1         | 0.94%   |
| Excavator        | 1         | 0.94%   |
| CometLake        | 1         | 0.94%   |
| Bulldozer        | 1         | 0.94%   |
| Alderlake Hybrid | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 70        | 56.91%  |
| Nvidia | 28        | 22.76%  |
| AMD    | 25        | 20.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 7.14%   |
| Intel UHD Graphics 620                                                    | 5         | 3.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 3.97%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 3.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 3.17%   |
| Intel HD Graphics 620                                                     | 4         | 3.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.17%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 2.38%   |
| Intel HD Graphics 5500                                                    | 3         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 3         | 2.38%   |
| AMD Renoir                                                                | 3         | 2.38%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 2         | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller          | 2         | 1.59%   |
| Intel JasperLake [UHD Graphics]                                           | 2         | 1.59%   |
| Intel HD Graphics 530                                                     | 2         | 1.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.59%   |
| AMD Lucienne                                                              | 2         | 1.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2         | 1.59%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                    | 1         | 0.79%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.79%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.79%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.79%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.79%   |
| Nvidia GP104GL [Quadro P4000]                                             | 1         | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.79%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.79%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 0.79%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.79%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.79%   |
| Nvidia GK110 [GeForce GTX 780]                                            | 1         | 0.79%   |
| Nvidia GK106 [GeForce GTX 660]                                            | 1         | 0.79%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                         | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 50%     |
| 1 x AMD        | 19        | 17.92%  |
| 1 x Nvidia     | 14        | 13.21%  |
| Intel + Nvidia | 12        | 11.32%  |
| 2 x AMD        | 2         | 1.89%   |
| Intel + AMD    | 2         | 1.89%   |
| AMD + Nvidia   | 2         | 1.89%   |
| Other          | 1         | 0.94%   |
| 2 x Intel      | 1         | 0.94%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 90        | 84.91%  |
| Proprietary | 14        | 13.21%  |
| Unknown     | 2         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 78.3%   |
| 1.01-2.0   | 8         | 7.55%   |
| 0.01-0.5   | 7         | 6.6%    |
| 7.01-8.0   | 3         | 2.83%   |
| 0.51-1.0   | 3         | 2.83%   |
| 3.01-4.0   | 2         | 1.89%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 20        | 17.09%  |
| Samsung Electronics     | 19        | 16.24%  |
| BOE                     | 18        | 15.38%  |
| AU Optronics            | 10        | 8.55%   |
| LG Display              | 8         | 6.84%   |
| Apple                   | 5         | 4.27%   |
| Hewlett-Packard         | 4         | 3.42%   |
| AOC                     | 4         | 3.42%   |
| Sharp                   | 3         | 2.56%   |
| Philips                 | 3         | 2.56%   |
| SANYO                   | 2         | 1.71%   |
| Goldstar                | 2         | 1.71%   |
| Dell                    | 2         | 1.71%   |
| Vestel Elektronik       | 1         | 0.85%   |
| Unknown (XXX)           | 1         | 0.85%   |
| Unknown (AAA)           | 1         | 0.85%   |
| Sony                    | 1         | 0.85%   |
| Panasonic               | 1         | 0.85%   |
| ONN                     | 1         | 0.85%   |
| MStar                   | 1         | 0.85%   |
| LG Electronics          | 1         | 0.85%   |
| Lenovo                  | 1         | 0.85%   |
| KDC                     | 1         | 0.85%   |
| IBM                     | 1         | 0.85%   |
| HKC                     | 1         | 0.85%   |
| Fujitsu Siemens         | 1         | 0.85%   |
| Denver                  | 1         | 0.85%   |
| Daewoo                  | 1         | 0.85%   |
| Chi Mei Optoelectronics | 1         | 0.85%   |
| BenQ                    | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch        | 2         | 1.68%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.84%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch          | 1         | 0.84%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch               | 1         | 0.84%   |
| Sony TV SNYEE01 1920x1080                                              | 1         | 0.84%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                | 1         | 0.84%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                | 1         | 0.84%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.84%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                 | 1         | 0.84%   |
| SANYO LCD SAN0A12 1920x540                                             | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch   | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch   | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.84%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch      | 1         | 0.84%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch      | 1         | 0.84%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch      | 1         | 0.84%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch    | 1         | 0.84%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.84%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch      | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch   | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 1         | 0.84%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 797x333mm 34.0-inch      | 1         | 0.84%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 1         | 0.84%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                | 1         | 0.84%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch               | 1         | 0.84%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch                | 1         | 0.84%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                    | 1         | 0.84%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                                | 1         | 0.84%   |
| ONN ONN50 ONN3458 3840x2160 575x323mm 26.0-inch                        | 1         | 0.84%   |
| MStar LCD TV MST9000 1360x768                                          | 1         | 0.84%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                       | 1         | 0.84%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.84%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 50        | 44.64%  |
| 1366x768 (WXGA)    | 20        | 17.86%  |
| 3840x2160 (4K)     | 9         | 8.04%   |
| 2560x1440 (QHD)    | 6         | 5.36%   |
| 1920x1200 (WUXGA)  | 5         | 4.46%   |
| 1920x540           | 3         | 2.68%   |
| 1680x1050 (WSXGA+) | 3         | 2.68%   |
| 1600x900 (HD+)     | 3         | 2.68%   |
| 1280x800 (WXGA)    | 3         | 2.68%   |
| 3440x1440          | 2         | 1.79%   |
| 3456x2160          | 1         | 0.89%   |
| 2880x1800          | 1         | 0.89%   |
| 2736x1824          | 1         | 0.89%   |
| 2560x1600          | 1         | 0.89%   |
| 2240x1400          | 1         | 0.89%   |
| 1440x900 (WXGA+)   | 1         | 0.89%   |
| 1360x768           | 1         | 0.89%   |
| 1280x1024 (SXGA)   | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 28.81%  |
| 13      | 18        | 15.25%  |
| 24      | 8         | 6.78%   |
| 14      | 8         | 6.78%   |
| 27      | 7         | 5.93%   |
| 23      | 7         | 5.93%   |
| 21      | 5         | 4.24%   |
| 17      | 5         | 4.24%   |
| Unknown | 4         | 3.39%   |
| 40      | 3         | 2.54%   |
| 11      | 3         | 2.54%   |
| 84      | 2         | 1.69%   |
| 34      | 2         | 1.69%   |
| 31      | 2         | 1.69%   |
| 72      | 1         | 0.85%   |
| 60      | 1         | 0.85%   |
| 54      | 1         | 0.85%   |
| 47      | 1         | 0.85%   |
| 33      | 1         | 0.85%   |
| 28      | 1         | 0.85%   |
| 26      | 1         | 0.85%   |
| 18      | 1         | 0.85%   |
| 12      | 1         | 0.85%   |
| 10      | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 43.97%  |
| 501-600     | 20        | 17.24%  |
| 201-300     | 13        | 11.21%  |
| 401-500     | 7         | 6.03%   |
| 351-400     | 6         | 5.17%   |
| Unknown     | 4         | 3.45%   |
| 801-900     | 3         | 2.59%   |
| 701-800     | 3         | 2.59%   |
| 601-700     | 3         | 2.59%   |
| 1501-2000   | 3         | 2.59%   |
| 1001-1500   | 3         | 2.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 83        | 78.3%   |
| 16/10   | 15        | 14.15%  |
| 3/2     | 2         | 1.89%   |
| 21/9    | 2         | 1.89%   |
| Unknown | 2         | 1.89%   |
| 4/3     | 1         | 0.94%   |
| 32/9    | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 29.31%  |
| 81-90          | 21        | 18.1%   |
| 201-250        | 14        | 12.07%  |
| 301-350        | 7         | 6.03%   |
| 351-500        | 6         | 5.17%   |
| More than 1000 | 5         | 4.31%   |
| 71-80          | 5         | 4.31%   |
| 251-300        | 4         | 3.45%   |
| 121-130        | 4         | 3.45%   |
| 501-1000       | 4         | 3.45%   |
| Unknown        | 4         | 3.45%   |
| 51-60          | 3         | 2.59%   |
| 151-200        | 2         | 1.72%   |
| 61-70          | 1         | 0.86%   |
| 41-50          | 1         | 0.86%   |
| 141-150        | 1         | 0.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 36        | 31.03%  |
| 51-100        | 27        | 23.28%  |
| 101-120       | 26        | 22.41%  |
| 161-240       | 11        | 9.48%   |
| More than 240 | 6         | 5.17%   |
| 1-50          | 6         | 5.17%   |
| Unknown       | 4         | 3.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 90        | 84.11%  |
| 2     | 16        | 14.95%  |
| 0     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 37.01%  |
| Realtek Semiconductor | 51        | 33.12%  |
| Qualcomm Atheros      | 12        | 7.79%   |
| Broadcom              | 11        | 7.14%   |
| MediaTek              | 6         | 3.9%    |
| Nvidia                | 3         | 1.95%   |
| Broadcom Limited      | 3         | 1.95%   |
| ASIX Electronics      | 3         | 1.95%   |
| Hewlett-Packard       | 2         | 1.3%    |
| TP-Link               | 1         | 0.65%   |
| Ralink Technology     | 1         | 0.65%   |
| Microsoft             | 1         | 0.65%   |
| JMicron Technology    | 1         | 0.65%   |
| Huawei Technologies   | 1         | 0.65%   |
| Fibocom               | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 16.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.8%    |
| Intel Wi-Fi 6 AX201                                               | 7         | 3.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.72%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.72%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 2.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.63%   |
| Intel Wireless 8260                                               | 3         | 1.63%   |
| Intel Wireless 7265                                               | 3         | 1.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 1.63%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.09%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.09%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.09%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.54%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.54%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.54%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 49.47%  |
| Realtek Semiconductor | 17        | 17.89%  |
| Broadcom              | 10        | 10.53%  |
| Qualcomm Atheros      | 9         | 9.47%   |
| MediaTek              | 6         | 6.32%   |
| TP-Link               | 1         | 1.05%   |
| Ralink Technology     | 1         | 1.05%   |
| Microsoft             | 1         | 1.05%   |
| Hewlett-Packard       | 1         | 1.05%   |
| Fibocom               | 1         | 1.05%   |
| Broadcom Limited      | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 7         | 7.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 5.26%   |
| Intel Wireless 8265 / 8275                                              | 5         | 5.26%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 5.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 4.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 4.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 3.16%   |
| Intel Wireless 8260                                                     | 3         | 3.16%   |
| Intel Wireless 7265                                                     | 3         | 3.16%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 3.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 3.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 2.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 2.11%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 2.11%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 1.05%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 1.05%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.05%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 1.05%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 1.05%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.05%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.05%   |
| Microsoft Wireless XBox Controller Dongle                               | 1         | 1.05%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 1.05%   |
| Intel Wireless-AC 9260                                                  | 1         | 1.05%   |
| Intel Wireless 7260                                                     | 1         | 1.05%   |
| Intel Wireless 3165                                                     | 1         | 1.05%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 1.05%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 1.05%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 45        | 52.94%  |
| Intel                 | 22        | 25.88%  |
| Broadcom              | 5         | 5.88%   |
| Qualcomm Atheros      | 3         | 3.53%   |
| Nvidia                | 3         | 3.53%   |
| ASIX Electronics      | 3         | 3.53%   |
| Broadcom Limited      | 2         | 2.35%   |
| JMicron Technology    | 1         | 1.18%   |
| Hewlett-Packard       | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 34.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.95%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.82%   |
| Intel Ethernet Controller I225-V                                  | 3         | 3.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.27%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.27%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.27%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 2.27%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.14%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.14%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.14%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.14%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.14%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.14%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.14%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.14%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.14%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.14%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.14%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.14%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 1.14%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.14%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.14%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.14%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.14%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 1.14%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.14%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1         | 1.14%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 52%     |
| Ethernet | 83        | 47.43%  |
| Modem    | 1         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 67.89%  |
| Ethernet | 35        | 32.11%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 60        | 56.6%   |
| 1     | 42        | 39.62%  |
| 0     | 4         | 3.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 76        | 70.37%  |
| Yes  | 32        | 29.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 53.85%  |
| Realtek Semiconductor           | 6         | 7.69%   |
| Apple                           | 6         | 7.69%   |
| Qualcomm Atheros Communications | 5         | 6.41%   |
| Broadcom                        | 5         | 6.41%   |
| IMC Networks                    | 3         | 3.85%   |
| MediaTek                        | 2         | 2.56%   |
| Dell                            | 2         | 2.56%   |
| Cambridge Silicon Radio         | 2         | 2.56%   |
| Smart Modular Technologies      | 1         | 1.28%   |
| Realtek                         | 1         | 1.28%   |
| Lite-On Technology              | 1         | 1.28%   |
| Foxconn International           | 1         | 1.28%   |
| Foxconn / Hon Hai               | 1         | 1.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 14        | 17.95%  |
| Intel AX201 Bluetooth                               | 12        | 15.38%  |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 6.41%   |
| Intel AX200 Bluetooth                               | 5         | 6.41%   |
| Realtek Bluetooth Radio                             | 4         | 5.13%   |
| Apple Bluetooth USB Host Controller                 | 4         | 5.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 3.85%   |
| Intel AX210 Bluetooth                               | 3         | 3.85%   |
| MediaTek Wireless_Device                            | 2         | 2.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.56%   |
| IMC Networks Wireless_Device                        | 2         | 2.56%   |
| Dell DW375 Bluetooth Module                         | 2         | 2.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.56%   |
| Apple Bluetooth Host Controller                     | 2         | 2.56%   |
| Smart Modular Bluetooth Device                      | 1         | 1.28%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.28%   |
| Realtek Bluetooth Radio                             | 1         | 1.28%   |
| Lite-On Bluetooth Radio                             | 1         | 1.28%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.28%   |
| Intel Bluetooth Device                              | 1         | 1.28%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.28%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.28%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.28%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.28%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.28%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.28%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 58.14%  |
| AMD                   | 26        | 20.16%  |
| Nvidia                | 19        | 14.73%  |
| Plantronics           | 2         | 1.55%   |
| Texas Instruments     | 1         | 0.78%   |
| Shure                 | 1         | 0.78%   |
| Realtek Semiconductor | 1         | 0.78%   |
| Logitech              | 1         | 0.78%   |
| LINE TECH INDUSTRIAL  | 1         | 0.78%   |
| ASUSTek Computer      | 1         | 0.78%   |
| Apple                 | 1         | 0.78%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 9.03%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 9.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 5.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 5.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 3.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 3.23%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.58%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.58%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.94%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.94%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.94%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.29%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.29%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.29%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 2         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.29%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.29%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.29%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.65%   |
| Shure MV88+                                                                | 1         | 0.65%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.65%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 0.65%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.65%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.65%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GM204 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 25.35%  |
| SK hynix            | 17        | 23.94%  |
| Kingston            | 10        | 14.08%  |
| Micron Technology   | 6         | 8.45%   |
| Crucial             | 6         | 8.45%   |
| Elpida              | 3         | 4.23%   |
| Unknown (ABCD)      | 2         | 2.82%   |
| Ramaxel Technology  | 2         | 2.82%   |
| Unknown             | 1         | 1.41%   |
| Transcend           | 1         | 1.41%   |
| Teikon              | 1         | 1.41%   |
| fef5                | 1         | 1.41%   |
| Corsair             | 1         | 1.41%   |
| A-DATA Technology   | 1         | 1.41%   |
| 8945000080AD        | 1         | 1.41%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 2.7%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.7%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 2.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.7%    |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 2.7%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 2.7%    |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.35%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 1.35%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.35%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 1.35%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 1.35%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.35%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.35%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.35%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.35%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.35%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.35%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.35%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.35%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.35%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s             | 1         | 1.35%   |
| Samsung RAM M393A1K43BB0-CRC 8GB DIMM DDR4 2400MT/s              | 1         | 1.35%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                  | 1         | 1.35%   |
| Samsung RAM INSPIRON 5566 8GB SODIMM DDR4 2400MT/s               | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 32        | 55.17%  |
| DDR3    | 16        | 27.59%  |
| LPDDR4  | 7         | 12.07%  |
| SDRAM   | 1         | 1.72%   |
| LPDDR3  | 1         | 1.72%   |
| Unknown | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 39        | 69.64%  |
| DIMM         | 10        | 17.86%  |
| Row Of Chips | 5         | 8.93%   |
| Chip         | 1         | 1.79%   |
| Unknown      | 1         | 1.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 44.07%  |
| 4096  | 14        | 23.73%  |
| 16384 | 10        | 16.95%  |
| 32768 | 4         | 6.78%   |
| 2048  | 4         | 6.78%   |
| 1024  | 1         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 14        | 22.22%  |
| 1600  | 12        | 19.05%  |
| 2667  | 11        | 17.46%  |
| 2400  | 9         | 14.29%  |
| 4267  | 3         | 4.76%   |
| 1333  | 3         | 4.76%   |
| 2133  | 2         | 3.17%   |
| 1334  | 2         | 3.17%   |
| 1067  | 2         | 3.17%   |
| 1066  | 2         | 3.17%   |
| 3600  | 1         | 1.59%   |
| 3266  | 1         | 1.59%   |
| 1867  | 1         | 1.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Dymo-CoStar         | 1         | 25%     |
| Canon               | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 23.61%  |
| IMC Networks                           | 9         | 12.5%   |
| Realtek Semiconductor                  | 7         | 9.72%   |
| Luxvisions Innotech Limited            | 5         | 6.94%   |
| Apple                                  | 5         | 6.94%   |
| Sunplus Innovation Technology          | 4         | 5.56%   |
| Microdia                               | 4         | 5.56%   |
| Bison Electronics                      | 4         | 5.56%   |
| Syntek                                 | 3         | 4.17%   |
| Logitech                               | 3         | 4.17%   |
| Samsung Electronics                    | 2         | 2.78%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.78%   |
| Unknown                                | 1         | 1.39%   |
| Quanta                                 | 1         | 1.39%   |
| Polycom                                | 1         | 1.39%   |
| Generalplus Technology                 | 1         | 1.39%   |
| Alcor Micro                            | 1         | 1.39%   |
| Acer                                   | 1         | 1.39%   |
| Unknown                                | 1         | 1.39%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 5.56%   |
| Realtek Integrated_Webcam_HD                         | 3         | 4.17%   |
| Logitech HD Pro Webcam C920                          | 3         | 4.17%   |
| IMC Networks Integrated Camera                       | 3         | 4.17%   |
| Bison SunplusIT Integrated Camera                    | 3         | 4.17%   |
| Syntek Integrated Camera                             | 2         | 2.78%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 2.78%   |
| Microdia Integrated_Webcam_HD                        | 2         | 2.78%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 2.78%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 2.78%   |
| Chicony USB2.0 Camera                                | 2         | 2.78%   |
| Chicony Integrated Camera                            | 2         | 2.78%   |
| Chicony HP HD Camera                                 | 2         | 2.78%   |
| Chicony HD Webcam                                    | 2         | 2.78%   |
| Apple FaceTime HD Camera                             | 2         | 2.78%   |
| Unknown ATIV VGA CAMERA                              | 1         | 1.39%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.39%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.39%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.39%   |
| Sunplus HD WebCam                                    | 1         | 1.39%   |
| Sunplus FHD Camera Microphone                        | 1         | 1.39%   |
| Realtek USB2.0 HD UVC WebCam                         | 1         | 1.39%   |
| Realtek Lenovo EasyCamera                            | 1         | 1.39%   |
| Realtek Integrated Webcam HD                         | 1         | 1.39%   |
| Realtek Integrated Webcam                            | 1         | 1.39%   |
| Quanta USB2.0 HD UVC WebCam                          | 1         | 1.39%   |
| Polycom Poly Studio P5 webcam                        | 1         | 1.39%   |
| Microdia Integrated Webcam HD                        | 1         | 1.39%   |
| Microdia Camera                                      | 1         | 1.39%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.39%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.39%   |
| IMC Networks Integrated RGB Camera                   | 1         | 1.39%   |
| Generalplus 808 Camera                               | 1         | 1.39%   |
| Chicony XiaoMi USB 2.0 Webcam                        | 1         | 1.39%   |
| Chicony USB2.0 UVC WebCam                            | 1         | 1.39%   |
| Chicony USB2.0 0.3M UVC WebCam                       | 1         | 1.39%   |
| Chicony Lenovo EasyCamera                            | 1         | 1.39%   |
| Chicony HP Wide Vision FHD Camera                    | 1         | 1.39%   |
| Chicony HP Truevision HD camera                      | 1         | 1.39%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 37.5%   |
| Shenzhen Goodix Technology | 5         | 31.25%  |
| Validity Sensors           | 3         | 18.75%  |
| Elan Microelectronics      | 2         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 12.5%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 6.25%   |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 6.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 6.25%   |
| Shenzhen Goodix FingerPrint                               | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                     | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                          | 1         | 6.25%   |
| Unknown                                                   | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 25%     |
| Broadcom 5880                                  | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 72        | 67.92%  |
| 1     | 23        | 21.7%   |
| 2     | 8         | 7.55%   |
| 6     | 1         | 0.94%   |
| 4     | 1         | 0.94%   |
| 3     | 1         | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 33.33%  |
| Net/wireless             | 5         | 11.11%  |
| Graphics card            | 5         | 11.11%  |
| Sound                    | 4         | 8.89%   |
| Chipcard                 | 4         | 8.89%   |
| Unassigned class         | 3         | 6.67%   |
| Communication controller | 3         | 6.67%   |
| Camera                   | 2         | 4.44%   |
| Bluetooth                | 2         | 4.44%   |
| Net/ethernet             | 1         | 2.22%   |
| Multimedia controller    | 1         | 2.22%   |


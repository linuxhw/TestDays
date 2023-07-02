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

Total: 159

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| BANGHO        | BES G0304                   | Notebook    | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4622902df7](https://linux-hardware.org/?probe=4622902df7) | Jun 17, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [f04b28a0e5](https://linux-hardware.org/?probe=f04b28a0e5) | Jun 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASUSTek       | UX303UA                     | Notebook    | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Gigabyte      | H310M HD2                   | Desktop     | [b28787ecb7](https://linux-hardware.org/?probe=b28787ecb7) | Jun 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [d12d9a4fc2](https://linux-hardware.org/?probe=d12d9a4fc2) | May 29, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [9cbdd21a81](https://linux-hardware.org/?probe=9cbdd21a81) | May 28, 2023 |
| Dell          | Latitude 5521               | Notebook    | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [51c520b6e6](https://linux-hardware.org/?probe=51c520b6e6) | May 25, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | Notebook    | [741d6fe6d2](https://linux-hardware.org/?probe=741d6fe6d2) | May 19, 2023 |
| HP            | Bloog                       | Notebook    | [4673a7630e](https://linux-hardware.org/?probe=4673a7630e) | May 16, 2023 |
| HP            | Bloog                       | Notebook    | [1c91d5ef51](https://linux-hardware.org/?probe=1c91d5ef51) | May 16, 2023 |
| Dell          | Latitude E5420              | Notebook    | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| TUXEDO        | Book XP1511                 | Notebook    | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [8a80fd7103](https://linux-hardware.org/?probe=8a80fd7103) | May 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3198c997b2](https://linux-hardware.org/?probe=3198c997b2) | May 04, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-27-generic      | 11        | 8.59%   |
| 5.15.0-52-generic      | 9         | 7.03%   |
| 5.15.0-50-generic      | 7         | 5.47%   |
| 5.15.0-48-generic      | 6         | 4.69%   |
| 5.15.0-30-generic      | 6         | 4.69%   |
| 5.15.0-46-generic      | 5         | 3.91%   |
| 5.15.0-43-generic      | 5         | 3.91%   |
| 5.15.0-39-generic      | 5         | 3.91%   |
| 5.19.0-35-generic      | 4         | 3.13%   |
| 5.15.0-57-generic      | 4         | 3.13%   |
| 5.15.0-56-generic      | 4         | 3.13%   |
| 5.15.0-33-generic      | 4         | 3.13%   |
| 5.15.0-25-generic      | 4         | 3.13%   |
| 5.19.0-41-generic      | 3         | 2.34%   |
| 5.19.0-40-generic      | 3         | 2.34%   |
| 5.15.0-58-generic      | 3         | 2.34%   |
| 5.15.0-53-generic      | 3         | 2.34%   |
| 5.15.0-47-generic      | 3         | 2.34%   |
| 5.15.0-40-generic      | 3         | 2.34%   |
| 6.2.0-10007-tuxedo     | 2         | 1.56%   |
| 5.19.0-45-generic      | 2         | 1.56%   |
| 5.19.0-42-generic      | 2         | 1.56%   |
| 5.19.0-38-generic      | 2         | 1.56%   |
| 5.15.0-67-generic      | 2         | 1.56%   |
| 5.15.0-41-generic      | 2         | 1.56%   |
| 6.3.1-060301-generic   | 1         | 0.78%   |
| 6.1.0-060100-generic   | 1         | 0.78%   |
| 5.19.0-32-generic      | 1         | 0.78%   |
| 5.19.0-051900-generic  | 1         | 0.78%   |
| 5.17.2-051702-generic  | 1         | 0.78%   |
| 5.16.2                 | 1         | 0.78%   |
| 5.15.92-051592-generic | 1         | 0.78%   |
| 5.15.0-73-generic      | 1         | 0.78%   |
| 5.15.0-72-generic      | 1         | 0.78%   |
| 5.15.0-71-generic      | 1         | 0.78%   |
| 5.15.0-69-generic      | 1         | 0.78%   |
| 5.15.0-60-generic      | 1         | 0.78%   |
| 5.15.0-52-lowlatency   | 1         | 0.78%   |
| 5.15.0-47-lowlatency   | 1         | 0.78%   |
| 5.15.0-35-generic      | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 95        | 77.87%  |
| 5.19.0  | 17        | 13.93%  |
| 5.13.0  | 3         | 2.46%   |
| 6.2.0   | 2         | 1.64%   |
| 6.3.1   | 1         | 0.82%   |
| 6.1.0   | 1         | 0.82%   |
| 5.17.2  | 1         | 0.82%   |
| 5.16.2  | 1         | 0.82%   |
| 5.15.92 | 1         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 96        | 78.69%  |
| 5.19    | 17        | 13.93%  |
| 5.13    | 3         | 2.46%   |
| 6.2     | 2         | 1.64%   |
| 6.3     | 1         | 0.82%   |
| 6.1     | 1         | 0.82%   |
| 5.17    | 1         | 0.82%   |
| 5.16    | 1         | 0.82%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 118       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 114       | 96.61%  |
| GNOME  | 4         | 3.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 116       | 98.31%  |
| Wayland | 2         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 83        | 70.34%  |
| Unknown | 23        | 19.49%  |
| GDM3    | 11        | 9.32%   |
| GDM     | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 46        | 38.98%  |
| de_DE | 15        | 12.71%  |
| fr_FR | 10        | 8.47%   |
| pt_BR | 8         | 6.78%   |
| en_GB | 8         | 6.78%   |
| it_IT | 3         | 2.54%   |
| fr_BE | 3         | 2.54%   |
| es_ES | 3         | 2.54%   |
| en_CA | 3         | 2.54%   |
| ru_RU | 2         | 1.69%   |
| hu_HU | 2         | 1.69%   |
| es_MX | 2         | 1.69%   |
| en_IE | 2         | 1.69%   |
| pl_PL | 1         | 0.85%   |
| mt_MT | 1         | 0.85%   |
| ja_JP | 1         | 0.85%   |
| es_PE | 1         | 0.85%   |
| es_EC | 1         | 0.85%   |
| es_CL | 1         | 0.85%   |
| en_ZA | 1         | 0.85%   |
| en_NZ | 1         | 0.85%   |
| el_GR | 1         | 0.85%   |
| cs_CZ | 1         | 0.85%   |
| C     | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 70        | 58.82%  |
| EFI  | 49        | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 104       | 86.67%  |
| Overlay | 6         | 5%      |
| Zfs     | 3         | 2.5%    |
| Tmpfs   | 3         | 2.5%    |
| Btrfs   | 3         | 2.5%    |
| Xfs     | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 74        | 62.18%  |
| Unknown | 40        | 33.61%  |
| MBR     | 5         | 4.2%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 83.9%   |
| Yes       | 19        | 16.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 82        | 68.91%  |
| Yes       | 37        | 31.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 18        | 15.25%  |
| Hewlett-Packard        | 16        | 13.56%  |
| Dell                   | 15        | 12.71%  |
| ASUSTek Computer       | 14        | 11.86%  |
| Gigabyte Technology    | 9         | 7.63%   |
| TUXEDO                 | 7         | 5.93%   |
| MSI                    | 7         | 5.93%   |
| Apple                  | 7         | 5.93%   |
| Intel                  | 4         | 3.39%   |
| Fujitsu                | 3         | 2.54%   |
| ASRock                 | 3         | 2.54%   |
| Google                 | 2         | 1.69%   |
| Toshiba                | 1         | 0.85%   |
| Timi                   | 1         | 0.85%   |
| Samsung Electronics    | 1         | 0.85%   |
| Razer                  | 1         | 0.85%   |
| HUAWEI                 | 1         | 0.85%   |
| Digibras               | 1         | 0.85%   |
| Chuwi                  | 1         | 0.85%   |
| Biostar                | 1         | 0.85%   |
| BANGHO                 | 1         | 0.85%   |
| AZW                    | 1         | 0.85%   |
| AXIOO                  | 1         | 0.85%   |
| Avell High Performance | 1         | 0.85%   |
| Acer                   | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| TUXEDO Polaris Intel Gen3 (TGL)                      | 1         | 0.85%   |
| TUXEDO InfinityBook S 15 Gen6                        | 1         | 0.85%   |
| TUXEDO InfinityBook Pro 14 v4                        | 1         | 0.85%   |
| TUXEDO Book XUX7 Gen11                               | 1         | 0.85%   |
| TUXEDO Book XP1511                                   | 1         | 0.85%   |
| TUXEDO Book BA1510                                   | 1         | 0.85%   |
| TUXEDO Aura 15 Gen1                                  | 1         | 0.85%   |
| Toshiba Satellite A505                               | 1         | 0.85%   |
| Timi TM1604                                          | 1         | 0.85%   |
| Samsung 740U3M                                       | 1         | 0.85%   |
| Razer Blade 15 Advanced Model (Mid 2021) - RZ09-0409 | 1         | 0.85%   |
| MSI MS-7C95                                          | 1         | 0.85%   |
| MSI MS-7B86                                          | 1         | 0.85%   |
| MSI MS-7A32                                          | 1         | 0.85%   |
| MSI MS-7885                                          | 1         | 0.85%   |
| MSI Modern 15 A10M                                   | 1         | 0.85%   |
| MSI GL62 6QF                                         | 1         | 0.85%   |
| MSI Alpha 15 B5EEK                                   | 1         | 0.85%   |
| Lenovo V15 G2 ALC 82KD                               | 1         | 0.85%   |
| Lenovo ThinkStation C20 4263BA7                      | 1         | 0.85%   |
| Lenovo ThinkPad T500 2242CTO                         | 1         | 0.85%   |
| Lenovo ThinkPad T480s 20L8SF1X00                     | 1         | 0.85%   |
| Lenovo ThinkPad T480 20L6SDR21A                      | 1         | 0.85%   |
| Lenovo ThinkPad T440 20B7S0F100                      | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 3 21AHCTO1WW                 | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 2i 20W000Q4GE                | 1         | 0.85%   |
| Lenovo ThinkPad E15 20RD003KHV                       | 1         | 0.85%   |
| Lenovo Legion Y530-15ICH 81FV                        | 1         | 0.85%   |
| Lenovo IdeaPadFlex 5 14ALC7 82R9                     | 1         | 0.85%   |
| Lenovo IdeaPad Z500 20202                            | 1         | 0.85%   |
| Lenovo IdeaPad S145-14IWL 81MU                       | 1         | 0.85%   |
| Lenovo IdeaPad C340-14API 81N6                       | 1         | 0.85%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                        | 1         | 0.85%   |
| Lenovo IdeaPad 330-15IKB 81FE                        | 1         | 0.85%   |
| Lenovo G500 20236                                    | 1         | 0.85%   |
| Lenovo G50-45 80E3                                   | 1         | 0.85%   |
| Intel STK1A32SC                                      | 1         | 0.85%   |
| Intel NUC12WSKi7                                     | 1         | 0.85%   |
| Intel H61                                            | 1         | 0.85%   |
| Intel DP55WB AAE64798-206                            | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 7         | 5.93%   |
| Lenovo IdeaPad      | 5         | 4.24%   |
| Dell Inspiron       | 5         | 4.24%   |
| Dell Latitude       | 4         | 3.39%   |
| ASUS VivoBook       | 4         | 3.39%   |
| TUXEDO Book         | 3         | 2.54%   |
| HP ProBook          | 3         | 2.54%   |
| TUXEDO InfinityBook | 2         | 1.69%   |
| HP Pavilion         | 2         | 1.69%   |
| HP EliteBook        | 2         | 1.69%   |
| Fujitsu ESPRIMO     | 2         | 1.69%   |
| Dell XPS            | 2         | 1.69%   |
| Dell Precision      | 2         | 1.69%   |
| TUXEDO Polaris      | 1         | 0.85%   |
| TUXEDO Aura         | 1         | 0.85%   |
| Toshiba Satellite   | 1         | 0.85%   |
| Timi TM1604         | 1         | 0.85%   |
| Samsung 740U3M      | 1         | 0.85%   |
| Razer Blade         | 1         | 0.85%   |
| MSI MS-7C95         | 1         | 0.85%   |
| MSI MS-7B86         | 1         | 0.85%   |
| MSI MS-7A32         | 1         | 0.85%   |
| MSI MS-7885         | 1         | 0.85%   |
| MSI Modern          | 1         | 0.85%   |
| MSI GL62            | 1         | 0.85%   |
| MSI Alpha           | 1         | 0.85%   |
| Lenovo V15          | 1         | 0.85%   |
| Lenovo ThinkStation | 1         | 0.85%   |
| Lenovo Legion       | 1         | 0.85%   |
| Lenovo IdeaPadFlex  | 1         | 0.85%   |
| Lenovo G500         | 1         | 0.85%   |
| Lenovo G50-45       | 1         | 0.85%   |
| Intel STK1A32SC     | 1         | 0.85%   |
| Intel NUC12WSKi7    | 1         | 0.85%   |
| Intel H61           | 1         | 0.85%   |
| Intel DP55WB        | 1         | 0.85%   |
| HUAWEI HKD-WXX      | 1         | 0.85%   |
| HP Z440             | 1         | 0.85%   |
| HP Spectre          | 1         | 0.85%   |
| HP ENVY             | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 17        | 14.41%  |
| 2020 | 16        | 13.56%  |
| 2018 | 12        | 10.17%  |
| 2014 | 11        | 9.32%   |
| 2019 | 9         | 7.63%   |
| 2022 | 8         | 6.78%   |
| 2016 | 7         | 5.93%   |
| 2015 | 7         | 5.93%   |
| 2017 | 6         | 5.08%   |
| 2013 | 5         | 4.24%   |
| 2010 | 5         | 4.24%   |
| 2012 | 4         | 3.39%   |
| 2011 | 4         | 3.39%   |
| 2009 | 4         | 3.39%   |
| 2008 | 3         | 2.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 73        | 61.86%  |
| Desktop     | 32        | 27.12%  |
| Convertible | 6         | 5.08%   |
| Mini pc     | 4         | 3.39%   |
| All in one  | 2         | 1.69%   |
| Tablet      | 1         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 111       | 94.07%  |
| Enabled  | 7         | 5.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 115       | 97.46%  |
| Yes  | 3         | 2.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 34        | 28.57%  |
| 16.01-24.0      | 34        | 28.57%  |
| 8.01-16.0       | 19        | 15.97%  |
| 3.01-4.0        | 11        | 9.24%   |
| 32.01-64.0      | 10        | 8.4%    |
| 64.01-256.0     | 5         | 4.2%    |
| 24.01-32.0      | 3         | 2.52%   |
| 1.01-2.0        | 2         | 1.68%   |
| More than 256.0 | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 42        | 33.6%   |
| 1.01-2.0   | 34        | 27.2%   |
| 4.01-8.0   | 23        | 18.4%   |
| 3.01-4.0   | 14        | 11.2%   |
| 8.01-16.0  | 8         | 6.4%    |
| 24.01-32.0 | 2         | 1.6%    |
| 16.01-24.0 | 2         | 1.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 60.83%  |
| 2      | 32        | 26.67%  |
| 3      | 8         | 6.67%   |
| 4      | 3         | 2.5%    |
| 6      | 2         | 1.67%   |
| 8      | 1         | 0.83%   |
| 7      | 1         | 0.83%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 76.27%  |
| Yes       | 28        | 23.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 78.15%  |
| No        | 26        | 21.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 85.59%  |
| No        | 17        | 14.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 73.73%  |
| No        | 31        | 26.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 25        | 21.19%  |
| Germany            | 15        | 12.71%  |
| France             | 10        | 8.47%   |
| Brazil             | 9         | 7.63%   |
| UK                 | 5         | 4.24%   |
| Poland             | 3         | 2.54%   |
| Italy              | 3         | 2.54%   |
| Belgium            | 3         | 2.54%   |
| Austria            | 3         | 2.54%   |
| Switzerland        | 2         | 1.69%   |
| Spain              | 2         | 1.69%   |
| Slovenia           | 2         | 1.69%   |
| Romania            | 2         | 1.69%   |
| Netherlands        | 2         | 1.69%   |
| Mexico             | 2         | 1.69%   |
| Ireland            | 2         | 1.69%   |
| Hungary            | 2         | 1.69%   |
| Greece             | 2         | 1.69%   |
| Canada             | 2         | 1.69%   |
| Argentina          | 2         | 1.69%   |
| Sweden             | 1         | 0.85%   |
| South Africa       | 1         | 0.85%   |
| Saudi Arabia       | 1         | 0.85%   |
| Russia             | 1         | 0.85%   |
| Peru               | 1         | 0.85%   |
| Norway             | 1         | 0.85%   |
| New Zealand        | 1         | 0.85%   |
| Malta              | 1         | 0.85%   |
| Japan              | 1         | 0.85%   |
| Indonesia          | 1         | 0.85%   |
| Ghana              | 1         | 0.85%   |
| Ecuador            | 1         | 0.85%   |
| Dominican Republic | 1         | 0.85%   |
| Czechia            | 1         | 0.85%   |
| Croatia            | 1         | 0.85%   |
| Chile              | 1         | 0.85%   |
| Cabo Verde         | 1         | 0.85%   |
| Bulgaria           | 1         | 0.85%   |
| Belarus            | 1         | 0.85%   |
| Algeria            | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Warsaw                | 2         | 1.64%   |
| Vienna                | 2         | 1.64%   |
| Milwaukee             | 2         | 1.64%   |
| London                | 2         | 1.64%   |
| Dublin                | 2         | 1.64%   |
| Budapest              | 2         | 1.64%   |
| Brasília             | 2         | 1.64%   |
| Berlin                | 2         | 1.64%   |
| Athens                | 2         | 1.64%   |
| Zurich                | 1         | 0.82%   |
| West Lafayette        | 1         | 0.82%   |
| Wertheim am Main      | 1         | 0.82%   |
| Weisswasser           | 1         | 0.82%   |
| Weilheim              | 1         | 0.82%   |
| Washington            | 1         | 0.82%   |
| Walled Lake           | 1         | 0.82%   |
| Victoria              | 1         | 0.82%   |
| Venray                | 1         | 0.82%   |
| Trondheim             | 1         | 0.82%   |
| Torun                 | 1         | 0.82%   |
| Tocantins             | 1         | 0.82%   |
| Targu Frumos          | 1         | 0.82%   |
| Tarakan               | 1         | 0.82%   |
| Tann                  | 1         | 0.82%   |
| Tampa                 | 1         | 0.82%   |
| Sunnyvale             | 1         | 0.82%   |
| St Petersburg         | 1         | 0.82%   |
| Sofia                 | 1         | 0.82%   |
| Siegen                | 1         | 0.82%   |
| Shirakuni             | 1         | 0.82%   |
| Sétif                | 1         | 0.82%   |
| Seelze                | 1         | 0.82%   |
| Seattle               | 1         | 0.82%   |
| Sao Paulo             | 1         | 0.82%   |
| Sao Bernardo do Campo | 1         | 0.82%   |
| Santo Domingo Este    | 1         | 0.82%   |
| Santiago              | 1         | 0.82%   |
| San Luis Potosí City | 1         | 0.82%   |
| San Diego             | 1         | 0.82%   |
| Saint-Gilles          | 1         | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 30        | 53     | 17.34%  |
| Seagate                        | 19        | 27     | 10.98%  |
| WDC                            | 13        | 15     | 7.51%   |
| Unknown                        | 12        | 12     | 6.94%   |
| Toshiba                        | 12        | 15     | 6.94%   |
| Crucial                        | 10        | 12     | 5.78%   |
| Micron Technology              | 9         | 9      | 5.2%    |
| SK hynix                       | 6         | 6      | 3.47%   |
| SanDisk                        | 6         | 7      | 3.47%   |
| Intel                          | 6         | 8      | 3.47%   |
| Kingston                       | 5         | 6      | 2.89%   |
| China                          | 4         | 5      | 2.31%   |
| SPCC                           | 3         | 3      | 1.73%   |
| OCZ                            | 3         | 3      | 1.73%   |
| JMicron Technology             | 3         | 3      | 1.73%   |
| Apple                          | 3         | 3      | 1.73%   |
| Phison                         | 2         | 2      | 1.16%   |
| A-DATA Technology              | 2         | 2      | 1.16%   |
| Zheino                         | 1         | 1      | 0.58%   |
| YMTC                           | 1         | 1      | 0.58%   |
| VISIPRO                        | 1         | 1      | 0.58%   |
| Union Memory                   | 1         | 1      | 0.58%   |
| Transcend                      | 1         | 1      | 0.58%   |
| TO Exter                       | 1         | 1      | 0.58%   |
| Solid State Storage Technology | 1         | 1      | 0.58%   |
| SABRENT                        | 1         | 1      | 0.58%   |
| Realtek Semiconductor          | 1         | 1      | 0.58%   |
| PNY                            | 1         | 1      | 0.58%   |
| Phison Electronics             | 1         | 1      | 0.58%   |
| OWC                            | 1         | 1      | 0.58%   |
| Netac                          | 1         | 1      | 0.58%   |
| Mushkin                        | 1         | 1      | 0.58%   |
| MicroFrom                      | 1         | 1      | 0.58%   |
| Maxtor                         | 1         | 1      | 0.58%   |
| LITEON                         | 1         | 1      | 0.58%   |
| KIOXIA                         | 1         | 1      | 0.58%   |
| Kingston Technology Company    | 1         | 1      | 0.58%   |
| HGST                           | 1         | 1      | 0.58%   |
| Hewlett-Packard                | 1         | 1      | 0.58%   |
| Corsair                        | 1         | 2      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 1.58%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 1.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 1.05%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.05%   |
| Unknown SD64G  64GB                                 | 2         | 1.05%   |
| Unknown SD/MMC/MS PRO 250GB                         | 2         | 1.05%   |
| Unknown MMC Card  128GB                             | 2         | 1.05%   |
| Seagate ST3500418AS 500GB                           | 2         | 1.05%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 1.05%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2         | 1.05%   |
| SanDisk SDSSDA120G 120GB                            | 2         | 1.05%   |
| Samsung SSD 980 PRO 2TB                             | 2         | 1.05%   |
| Samsung SSD 980 500GB                               | 2         | 1.05%   |
| Samsung SSD 870 EVO 250GB                           | 2         | 1.05%   |
| Samsung SSD 860 EVO M.2 500GB                       | 2         | 1.05%   |
| Samsung SSD 850 PRO 256GB                           | 2         | 1.05%   |
| Samsung SSD 850 EVO 500GB                           | 2         | 1.05%   |
| Samsung NVMe SSD Drive 256GB                        | 2         | 1.05%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 2         | 1.05%   |
| JMicron Generic 240GB                               | 2         | 1.05%   |
| Crucial CT480BX500SSD1 480GB                        | 2         | 1.05%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.05%   |
| Zheino CHN-25SATAC3-120 120GB SSD                   | 1         | 0.53%   |
| YMTC PC005 1TB                                      | 1         | 0.53%   |
| WDC WD40PURZ-85TTDY0 4TB                            | 1         | 0.53%   |
| WDC WD3200LPVX-22V0TT0 320GB                        | 1         | 0.53%   |
| WDC WD1600AAJS-60WAA0 160GB                         | 1         | 0.53%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 1         | 0.53%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1         | 0.53%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 0.53%   |
| WDC PC SN730 NVMe 256GB                             | 1         | 0.53%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.53%   |
| WDC PC SN520 SDAPNUW-512G-1002 512GB                | 1         | 0.53%   |
| VISIPRO SSD 256GB                                   | 1         | 0.53%   |
| Unknown SL128  128GB                                | 1         | 0.53%   |
| Unknown SA16G  16GB                                 | 1         | 0.53%   |
| Unknown NCard  4GB                                  | 1         | 0.53%   |
| Unknown MMC128  128GB                               | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 26     | 44.19%  |
| WDC                 | 9         | 10     | 20.93%  |
| Toshiba             | 7         | 7      | 16.28%  |
| Unknown             | 2         | 2      | 4.65%   |
| Samsung Electronics | 2         | 3      | 4.65%   |
| Maxtor              | 1         | 1      | 2.33%   |
| HGST                | 1         | 1      | 2.33%   |
| ASMT109x            | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 28     | 20%     |
| Crucial             | 10        | 12     | 16.67%  |
| Micron Technology   | 4         | 4      | 6.67%   |
| China               | 4         | 5      | 6.67%   |
| SanDisk             | 3         | 3      | 5%      |
| WDC                 | 2         | 2      | 3.33%   |
| SPCC                | 2         | 2      | 3.33%   |
| OCZ                 | 2         | 2      | 3.33%   |
| Kingston            | 2         | 3      | 3.33%   |
| Apple               | 2         | 2      | 3.33%   |
| Zheino              | 1         | 1      | 1.67%   |
| VISIPRO             | 1         | 1      | 1.67%   |
| Union Memory        | 1         | 1      | 1.67%   |
| Toshiba             | 1         | 1      | 1.67%   |
| TO Exter            | 1         | 1      | 1.67%   |
| SK hynix            | 1         | 1      | 1.67%   |
| PNY                 | 1         | 1      | 1.67%   |
| OWC                 | 1         | 1      | 1.67%   |
| Netac               | 1         | 1      | 1.67%   |
| Mushkin             | 1         | 1      | 1.67%   |
| MicroFrom           | 1         | 1      | 1.67%   |
| LITEON              | 1         | 1      | 1.67%   |
| Intel               | 1         | 1      | 1.67%   |
| Hewlett-Packard     | 1         | 1      | 1.67%   |
| Corsair             | 1         | 2      | 1.67%   |
| A-DATA Technology   | 1         | 1      | 1.67%   |
| 4Life               | 1         | 1      | 1.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 54        | 69     | 34.84%  |
| SSD     | 53        | 81     | 34.19%  |
| HDD     | 35        | 52     | 22.58%  |
| MMC     | 12        | 14     | 7.74%   |
| Unknown | 1         | 1      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 72        | 129    | 50%     |
| NVMe | 53        | 66     | 36.81%  |
| MMC  | 12        | 14     | 8.33%   |
| SAS  | 7         | 8      | 4.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 86     | 61.05%  |
| 0.51-1.0   | 25        | 32     | 26.32%  |
| 1.01-2.0   | 6         | 7      | 6.32%   |
| 3.01-4.0   | 5         | 6      | 5.26%   |
| 4.01-10.0  | 1         | 2      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 30.51%  |
| 251-500        | 32        | 27.12%  |
| 501-1000       | 12        | 10.17%  |
| 51-100         | 12        | 10.17%  |
| 1001-2000      | 8         | 6.78%   |
| 1-20           | 6         | 5.08%   |
| More than 3000 | 5         | 4.24%   |
| 21-50          | 5         | 4.24%   |
| 2001-3000      | 2         | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 27.27%  |
| 21-50          | 31        | 25.62%  |
| 101-250        | 19        | 15.7%   |
| 51-100         | 18        | 14.88%  |
| 251-500        | 9         | 7.44%   |
| 1001-2000      | 5         | 4.13%   |
| 501-1000       | 4         | 3.31%   |
| More than 3000 | 1         | 0.83%   |
| 2001-3000      | 1         | 0.83%   |

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
| Detected | 74        | 132    | 57.81%  |
| Works    | 50        | 81     | 39.06%  |
| Malfunc  | 3         | 3      | 2.34%   |
| Failed   | 1         | 1      | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 71        | 47.97%  |
| AMD                            | 20        | 13.51%  |
| Samsung Electronics            | 19        | 12.84%  |
| SanDisk                        | 5         | 3.38%   |
| Micron Technology              | 5         | 3.38%   |
| Kingston Technology Company    | 4         | 2.7%    |
| Toshiba America Info Systems   | 3         | 2.03%   |
| SK hynix                       | 3         | 2.03%   |
| Phison Electronics             | 3         | 2.03%   |
| Nvidia                         | 3         | 2.03%   |
| Marvell Technology Group       | 2         | 1.35%   |
| KIOXIA                         | 2         | 1.35%   |
| Yangtze Memory Technologies    | 1         | 0.68%   |
| Transcend                      | 1         | 0.68%   |
| Solid State Storage Technology | 1         | 0.68%   |
| Seagate Technology             | 1         | 0.68%   |
| Realtek Semiconductor          | 1         | 0.68%   |
| OCZ Technology Group           | 1         | 0.68%   |
| JMicron Technology             | 1         | 0.68%   |
| ADATA Technology               | 1         | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 13        | 7.83%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 5.42%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 3.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 3.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 2.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.41%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 2.41%   |
| Micron NVMe Storage Controller                                                 | 3         | 1.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.81%   |
| AMD 400 Series Chipset SATA Controller                                         | 3         | 1.81%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 1.2%    |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.2%    |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.2%    |
| Intel NVMe Controller                                                          | 2         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.2%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 1.2%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 1.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 2         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 2         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.2%    |
| AMD FCH IDE Controller                                                         | 2         | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.2%    |
| Yangtze Memory Non-Volatile memory controller                                  | 1         | 0.6%    |
| Transcend Non-Volatile memory controller                                       | 1         | 0.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.6%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.6%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.6%    |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 82        | 53.25%  |
| NVMe | 53        | 34.42%  |
| IDE  | 10        | 6.49%   |
| RAID | 9         | 5.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 77.97%  |
| AMD    | 26        | 22.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 4.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 2.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.54%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 2         | 1.69%   |
| Intel Core i5-4590T CPU @ 2.00GHz             | 2         | 1.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.69%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 1.69%   |
| Intel Celeron N4500 @ 1.10GHz                 | 2         | 1.69%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.69%   |
| Intel Atom CPU Z3795 @ 1.60GHz                | 2         | 1.69%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 1.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.69%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 2         | 1.69%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.69%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.69%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 2         | 1.69%   |
| Intel Xeon CPU X5492 @ 3.40GHz                | 1         | 0.85%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.85%   |
| Intel Xeon CPU E5-2697A v4 @ 2.60GHz          | 1         | 0.85%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz           | 1         | 0.85%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.85%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.85%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.85%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.85%   |
| Intel Core i7-5820K CPU @ 3.30GHz             | 1         | 0.85%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-3615QM CPU @ 2.30GHz            | 1         | 0.85%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.85%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 1         | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 1         | 0.85%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.85%   |
| Intel Core i7 CPU 860 @ 2.80GHz               | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 26        | 22.03%  |
| Intel Core i7        | 20        | 16.95%  |
| Other                | 17        | 14.41%  |
| AMD Ryzen 5          | 11        | 9.32%   |
| Intel Core i3        | 6         | 5.08%   |
| Intel Celeron        | 6         | 5.08%   |
| Intel Xeon           | 4         | 3.39%   |
| Intel Atom           | 4         | 3.39%   |
| AMD Ryzen 7          | 4         | 3.39%   |
| Intel Core 2 Duo     | 3         | 2.54%   |
| Intel Pentium Silver | 2         | 1.69%   |
| Intel Pentium        | 2         | 1.69%   |
| AMD Ryzen 9          | 2         | 1.69%   |
| Intel Core i9        | 1         | 0.85%   |
| Intel Core 2 Quad    | 1         | 0.85%   |
| AMD Ryzen 3          | 1         | 0.85%   |
| AMD Phenom II X4     | 1         | 0.85%   |
| AMD FX               | 1         | 0.85%   |
| AMD Athlon X4        | 1         | 0.85%   |
| AMD Athlon II X3     | 1         | 0.85%   |
| AMD Athlon           | 1         | 0.85%   |
| AMD A8               | 1         | 0.85%   |
| AMD A4               | 1         | 0.85%   |
| AMD A10              | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 50        | 42.37%  |
| 2      | 38        | 32.2%   |
| 6      | 12        | 10.17%  |
| 8      | 10        | 8.47%   |
| 12     | 3         | 2.54%   |
| 10     | 2         | 1.69%   |
| 16     | 1         | 0.85%   |
| 3      | 1         | 0.85%   |
| 1      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 116       | 98.31%  |
| 2      | 2         | 1.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 88        | 74.58%  |
| 1      | 30        | 25.42%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 118       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 54.1%   |
| 0x806c1    | 5         | 4.1%    |
| 0x806ec    | 4         | 3.28%   |
| 0x306a9    | 4         | 3.28%   |
| 0x706a8    | 3         | 2.46%   |
| 0x206a7    | 3         | 2.46%   |
| 0x08600106 | 3         | 2.46%   |
| 0x08108102 | 3         | 2.46%   |
| 0x806d1    | 2         | 1.64%   |
| 0x406f1    | 2         | 1.64%   |
| 0x306c3    | 2         | 1.64%   |
| 0x20655    | 2         | 1.64%   |
| 0x0a50000c | 2         | 1.64%   |
| 0xa0671    | 1         | 0.82%   |
| 0x906eb    | 1         | 0.82%   |
| 0x906ea    | 1         | 0.82%   |
| 0x906a3    | 1         | 0.82%   |
| 0x806eb    | 1         | 0.82%   |
| 0x806ea    | 1         | 0.82%   |
| 0x806e9    | 1         | 0.82%   |
| 0x506c9    | 1         | 0.82%   |
| 0x406c4    | 1         | 0.82%   |
| 0x40651    | 1         | 0.82%   |
| 0x306d4    | 1         | 0.82%   |
| 0x30678    | 1         | 0.82%   |
| 0x106e5    | 1         | 0.82%   |
| 0x1067a    | 1         | 0.82%   |
| 0x10677    | 1         | 0.82%   |
| 0x0a201205 | 1         | 0.82%   |
| 0x08608104 | 1         | 0.82%   |
| 0x08608103 | 1         | 0.82%   |
| 0x08108109 | 1         | 0.82%   |
| 0x07030104 | 1         | 0.82%   |
| 0x06001119 | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 17.8%   |
| TigerLake        | 10        | 8.47%   |
| Unknown          | 9         | 7.63%   |
| IvyBridge        | 8         | 6.78%   |
| Haswell          | 7         | 5.93%   |
| Zen+             | 6         | 5.08%   |
| Zen 3            | 6         | 5.08%   |
| Skylake          | 6         | 5.08%   |
| Penryn           | 5         | 4.24%   |
| Broadwell        | 5         | 4.24%   |
| Silvermont       | 4         | 3.39%   |
| SandyBridge      | 4         | 3.39%   |
| Icelake          | 4         | 3.39%   |
| Goldmont plus    | 4         | 3.39%   |
| Zen 2            | 3         | 2.54%   |
| Westmere         | 3         | 2.54%   |
| Nehalem          | 2         | 1.69%   |
| K10              | 2         | 1.69%   |
| CometLake        | 2         | 1.69%   |
| Steamroller      | 1         | 0.85%   |
| Puma             | 1         | 0.85%   |
| Piledriver       | 1         | 0.85%   |
| Goldmont         | 1         | 0.85%   |
| Excavator        | 1         | 0.85%   |
| Bulldozer        | 1         | 0.85%   |
| Alderlake Hybrid | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 79        | 57.66%  |
| Nvidia | 32        | 23.36%  |
| AMD    | 26        | 18.98%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 10        | 7.14%   |
| Intel UHD Graphics 620                                                      | 5         | 3.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 3.57%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 3.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 4         | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.86%   |
| Intel HD Graphics 620                                                       | 4         | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.86%   |
| Intel HD Graphics 5500                                                      | 3         | 2.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 2.14%   |
| AMD Renoir                                                                  | 3         | 2.14%   |
| AMD Lucienne                                                                | 3         | 2.14%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.43%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 2         | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.43%   |
| Intel JasperLake [UHD Graphics]                                             | 2         | 1.43%   |
| Intel HD Graphics 530                                                       | 2         | 1.43%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 2         | 1.43%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.43%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.43%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2         | 1.43%   |
| Nvidia TU117M [GeForce MX450]                                               | 1         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                     | 1         | 0.71%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                       | 1         | 0.71%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                      | 1         | 0.71%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX250]                                               | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX230]                                               | 1         | 0.71%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.71%   |
| Nvidia GP104GL [Quadro P4000]                                               | 1         | 0.71%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 60        | 50.85%  |
| 1 x AMD        | 20        | 16.95%  |
| 1 x Nvidia     | 16        | 13.56%  |
| Intel + Nvidia | 14        | 11.86%  |
| 2 x AMD        | 2         | 1.69%   |
| Intel + AMD    | 2         | 1.69%   |
| AMD + Nvidia   | 2         | 1.69%   |
| Other          | 1         | 0.85%   |
| 2 x Intel      | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 99        | 83.19%  |
| Proprietary | 18        | 15.13%  |
| Unknown     | 2         | 1.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 77.12%  |
| 1.01-2.0   | 8         | 6.78%   |
| 0.01-0.5   | 7         | 5.93%   |
| 7.01-8.0   | 5         | 4.24%   |
| 3.01-4.0   | 3         | 2.54%   |
| 0.51-1.0   | 3         | 2.54%   |
| 2.01-3.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 21        | 15.79%  |
| Samsung Electronics     | 20        | 15.04%  |
| BOE                     | 20        | 15.04%  |
| AU Optronics            | 11        | 8.27%   |
| LG Display              | 8         | 6.02%   |
| Apple                   | 6         | 4.51%   |
| Goldstar                | 5         | 3.76%   |
| AOC                     | 5         | 3.76%   |
| Hewlett-Packard         | 4         | 3.01%   |
| Sharp                   | 3         | 2.26%   |
| Philips                 | 3         | 2.26%   |
| BenQ                    | 3         | 2.26%   |
| SANYO                   | 2         | 1.5%    |
| Lenovo                  | 2         | 1.5%    |
| HKC                     | 2         | 1.5%    |
| Fujitsu Siemens         | 2         | 1.5%    |
| Dell                    | 2         | 1.5%    |
| Vestel Elektronik       | 1         | 0.75%   |
| Unknown (XXX)           | 1         | 0.75%   |
| Unknown (AAA)           | 1         | 0.75%   |
| TMX                     | 1         | 0.75%   |
| Sony                    | 1         | 0.75%   |
| Panasonic               | 1         | 0.75%   |
| ONN                     | 1         | 0.75%   |
| MStar                   | 1         | 0.75%   |
| LG Electronics          | 1         | 0.75%   |
| KDC                     | 1         | 0.75%   |
| IBM                     | 1         | 0.75%   |
| Denver                  | 1         | 0.75%   |
| Daewoo                  | 1         | 0.75%   |
| Chi Mei Optoelectronics | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 2         | 1.47%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch    | 1         | 0.74%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 1         | 0.74%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch                | 1         | 0.74%   |
| TMX TL142GDXP02-0 TMX1420 2520x1680 300x200mm 14.2-inch                 | 1         | 0.74%   |
| Sony TV SNYEE01 1920x1080                                               | 1         | 0.74%   |
| Sharp LQ156T1JW03 SHP1529 2560x1440 344x194mm 15.5-inch                 | 1         | 0.74%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.74%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                 | 1         | 0.74%   |
| SANYO LCD-24XH7** SAN0B92 1920x540 531x299mm 24.0-inch                  | 1         | 0.74%   |
| SANYO LCD SAN0A12 1920x540                                              | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM060C 1920x1080 510x290mm 23.1-inch    | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM0346 1680x1050 459x296mm 21.5-inch    | 1         | 0.74%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch    | 1         | 0.74%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.74%   |
| Samsung Electronics S24C450 SAM09CF 1920x1200 518x324mm 24.1-inch       | 1         | 0.74%   |
| Samsung Electronics LU28R55 SAM1018 3840x2160 632x360mm 28.6-inch       | 1         | 0.74%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch     | 1         | 0.74%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 530x300mm 24.0-inch       | 1         | 0.74%   |
| Samsung Electronics LF22T35 SAM707B 1920x1080 477x268mm 21.5-inch       | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC414F 3456x2160 288x180mm 13.4-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch   | 1         | 0.74%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch     | 1         | 0.74%   |
| Samsung Electronics C34J79x SAM0F1C 3440x1440 800x330mm 34.1-inch       | 1         | 0.74%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 1         | 0.74%   |
| Philips PHL 276B1 PHL0947 2560x1440 597x336mm 27.0-inch                 | 1         | 0.74%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch                | 1         | 0.74%   |
| Philips PHL 233V5 PHLC0D0 1920x1080 509x286mm 23.0-inch                 | 1         | 0.74%   |
| Philips 273EL PHLC07C 1920x1080 598x336mm 27.0-inch                     | 1         | 0.74%   |
| Panasonic PanasonicTV0 MEIA0D7 1920x540                                 | 1         | 0.74%   |
| ONN ONN50 ONN3458 3840x2160 575x323mm 26.0-inch                         | 1         | 0.74%   |
| MStar LCD TV MST9000 1360x768                                           | 1         | 0.74%   |
| LG Electronics LCD Monitor LG Ultra HD 3840x2160                        | 1         | 0.74%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch            | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 44.44%  |
| 1366x768 (WXGA)    | 22        | 17.46%  |
| 3840x2160 (4K)     | 10        | 7.94%   |
| 2560x1440 (QHD)    | 6         | 4.76%   |
| 1920x1200 (WUXGA)  | 6         | 4.76%   |
| 1920x540           | 3         | 2.38%   |
| 1680x1050 (WSXGA+) | 3         | 2.38%   |
| 1600x900 (HD+)     | 3         | 2.38%   |
| 1280x800 (WXGA)    | 3         | 2.38%   |
| 3440x1440          | 2         | 1.59%   |
| 2560x1080          | 2         | 1.59%   |
| 1440x900 (WXGA+)   | 2         | 1.59%   |
| 3456x2160          | 1         | 0.79%   |
| 2880x1800          | 1         | 0.79%   |
| 2736x1824          | 1         | 0.79%   |
| 2560x1600          | 1         | 0.79%   |
| 2520x1680          | 1         | 0.79%   |
| 2240x1400          | 1         | 0.79%   |
| 1360x768           | 1         | 0.79%   |
| 1280x1024 (SXGA)   | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 26.87%  |
| 13      | 21        | 15.67%  |
| 24      | 11        | 8.21%   |
| 14      | 11        | 8.21%   |
| 27      | 9         | 6.72%   |
| 23      | 7         | 5.22%   |
| 21      | 6         | 4.48%   |
| 17      | 5         | 3.73%   |
| 34      | 4         | 2.99%   |
| Unknown | 4         | 2.99%   |
| 40      | 3         | 2.24%   |
| 11      | 3         | 2.24%   |
| 84      | 2         | 1.49%   |
| 31      | 2         | 1.49%   |
| 72      | 1         | 0.75%   |
| 60      | 1         | 0.75%   |
| 54      | 1         | 0.75%   |
| 47      | 1         | 0.75%   |
| 33      | 1         | 0.75%   |
| 28      | 1         | 0.75%   |
| 26      | 1         | 0.75%   |
| 18      | 1         | 0.75%   |
| 12      | 1         | 0.75%   |
| 10      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 56        | 42.42%  |
| 501-600     | 24        | 18.18%  |
| 201-300     | 16        | 12.12%  |
| 401-500     | 8         | 6.06%   |
| 351-400     | 6         | 4.55%   |
| 701-800     | 5         | 3.79%   |
| 601-700     | 4         | 3.03%   |
| Unknown     | 4         | 3.03%   |
| 801-900     | 3         | 2.27%   |
| 1501-2000   | 3         | 2.27%   |
| 1001-1500   | 3         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 92        | 76.67%  |
| 16/10   | 17        | 14.17%  |
| 21/9    | 4         | 3.33%   |
| 3/2     | 3         | 2.5%    |
| Unknown | 2         | 1.67%   |
| 4/3     | 1         | 0.83%   |
| 32/9    | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 27.27%  |
| 81-90          | 25        | 18.94%  |
| 201-250        | 17        | 12.88%  |
| 301-350        | 9         | 6.82%   |
| 351-500        | 8         | 6.06%   |
| 71-80          | 6         | 4.55%   |
| More than 1000 | 5         | 3.79%   |
| 251-300        | 4         | 3.03%   |
| 121-130        | 4         | 3.03%   |
| 501-1000       | 4         | 3.03%   |
| Unknown        | 4         | 3.03%   |
| 51-60          | 3         | 2.27%   |
| 151-200        | 3         | 2.27%   |
| 61-70          | 1         | 0.76%   |
| 41-50          | 1         | 0.76%   |
| 141-150        | 1         | 0.76%   |
| 91-100         | 1         | 0.76%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 30.3%   |
| 51-100        | 33        | 25%     |
| 101-120       | 29        | 21.97%  |
| 161-240       | 13        | 9.85%   |
| More than 240 | 7         | 5.3%    |
| 1-50          | 6         | 4.55%   |
| Unknown       | 4         | 3.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 97        | 81.51%  |
| 2     | 21        | 17.65%  |
| 0     | 1         | 0.84%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 37.79%  |
| Realtek Semiconductor | 58        | 33.72%  |
| Qualcomm Atheros      | 12        | 6.98%   |
| Broadcom              | 11        | 6.4%    |
| MediaTek              | 6         | 3.49%   |
| Broadcom Limited      | 4         | 2.33%   |
| Nvidia                | 3         | 1.74%   |
| ASIX Electronics      | 3         | 1.74%   |
| Hewlett-Packard       | 2         | 1.16%   |
| Xiaomi                | 1         | 0.58%   |
| TP-Link               | 1         | 0.58%   |
| Ralink Technology     | 1         | 0.58%   |
| Microsoft             | 1         | 0.58%   |
| Lenovo                | 1         | 0.58%   |
| JMicron Technology    | 1         | 0.58%   |
| Huawei Technologies   | 1         | 0.58%   |
| Fibocom               | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 17.07%  |
| Intel Wi-Fi 6 AX201                                               | 8         | 3.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.41%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 3.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.93%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.95%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.46%   |
| Intel Wireless 8260                                               | 3         | 1.46%   |
| Intel Wireless 7265                                               | 3         | 1.46%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.46%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.98%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.98%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.98%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.98%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.49%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.49%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter               | 1         | 0.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 51.43%  |
| Realtek Semiconductor | 19        | 18.1%   |
| Broadcom              | 10        | 9.52%   |
| Qualcomm Atheros      | 9         | 8.57%   |
| MediaTek              | 6         | 5.71%   |
| Broadcom Limited      | 2         | 1.9%    |
| TP-Link               | 1         | 0.95%   |
| Ralink Technology     | 1         | 0.95%   |
| Microsoft             | 1         | 0.95%   |
| Hewlett-Packard       | 1         | 0.95%   |
| Fibocom               | 1         | 0.95%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 8         | 7.62%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 6.67%   |
| Intel Wireless 8265 / 8275                                              | 6         | 5.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 4.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 4.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 3.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 3.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 3.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 2.86%   |
| Intel Wireless 8260                                                     | 3         | 2.86%   |
| Intel Wireless 7265                                                     | 3         | 2.86%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 2.86%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.9%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 2         | 1.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 1.9%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.95%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.95%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.95%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.95%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 1         | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.95%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.95%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.95%   |
| Ralink RT3072 Wireless Adapter                                          | 1         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.95%   |
| Microsoft Wireless XBox Controller Dongle                               | 1         | 0.95%   |
| MediaTek 802.11 n WLAN                                                  | 1         | 0.95%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.95%   |
| Intel Wireless 7260                                                     | 1         | 0.95%   |
| Intel Wireless 3165                                                     | 1         | 0.95%   |
| Intel Wireless 3160                                                     | 1         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 50        | 52.08%  |
| Intel                 | 26        | 27.08%  |
| Broadcom              | 5         | 5.21%   |
| Qualcomm Atheros      | 3         | 3.13%   |
| Nvidia                | 3         | 3.13%   |
| ASIX Electronics      | 3         | 3.13%   |
| Broadcom Limited      | 2         | 2.08%   |
| Xiaomi                | 1         | 1.04%   |
| Lenovo                | 1         | 1.04%   |
| JMicron Technology    | 1         | 1.04%   |
| Hewlett-Packard       | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 35        | 35.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.06%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 4.04%   |
| Intel Ethernet Controller I225-V                                  | 3         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.03%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 2.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 2.02%   |
| Nvidia MCP79 Ethernet                                             | 2         | 2.02%   |
| Intel I211 Gigabit Network Connection                             | 2         | 2.02%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 2.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.01%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.01%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 1.01%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.01%   |
| Nvidia MCP61 Ethernet                                             | 1         | 1.01%   |
| Lenovo ThinkPad Lan                                               | 1         | 1.01%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 1.01%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.01%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.01%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.01%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.01%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 1.01%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.01%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.01%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 1.01%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.01%   |
| Intel 82578DC Gigabit Network Connection                          | 1         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.01%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.01%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 1.01%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 1         | 1.01%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 1.01%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express   | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 52.06%  |
| Ethernet | 92        | 47.42%  |
| Modem    | 1         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 65.29%  |
| Ethernet | 42        | 34.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 66        | 55.93%  |
| 1     | 48        | 40.68%  |
| 0     | 4         | 3.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 86        | 71.07%  |
| Yes  | 35        | 28.93%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 56.32%  |
| Realtek Semiconductor           | 7         | 8.05%   |
| Apple                           | 7         | 8.05%   |
| Qualcomm Atheros Communications | 5         | 5.75%   |
| Broadcom                        | 5         | 5.75%   |
| IMC Networks                    | 3         | 3.45%   |
| MediaTek                        | 2         | 2.3%    |
| Dell                            | 2         | 2.3%    |
| Cambridge Silicon Radio         | 2         | 2.3%    |
| Smart Modular Technologies      | 1         | 1.15%   |
| Realtek                         | 1         | 1.15%   |
| Lite-On Technology              | 1         | 1.15%   |
| Foxconn International           | 1         | 1.15%   |
| Foxconn / Hon Hai               | 1         | 1.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 16        | 18.39%  |
| Intel AX201 Bluetooth                               | 13        | 14.94%  |
| Intel AX200 Bluetooth                               | 7         | 8.05%   |
| Realtek Bluetooth Radio                             | 5         | 5.75%   |
| Apple Bluetooth USB Host Controller                 | 5         | 5.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 4.6%    |
| Intel AX210 Bluetooth                               | 4         | 4.6%    |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 3.45%   |
| MediaTek Wireless_Device                            | 2         | 2.3%    |
| Intel Bluetooth Device                              | 2         | 2.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 2.3%    |
| IMC Networks Wireless_Device                        | 2         | 2.3%    |
| Dell DW375 Bluetooth Module                         | 2         | 2.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.3%    |
| Apple Bluetooth Host Controller                     | 2         | 2.3%    |
| Smart Modular Bluetooth Device                      | 1         | 1.15%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.15%   |
| Realtek Bluetooth Radio                             | 1         | 1.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.15%   |
| Lite-On Bluetooth Radio                             | 1         | 1.15%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.15%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.15%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.15%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.15%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.15%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 1.15%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.15%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.15%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.15%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 85        | 58.22%  |
| AMD                   | 28        | 19.18%  |
| Nvidia                | 22        | 15.07%  |
| Plantronics           | 3         | 2.05%   |
| Texas Instruments     | 1         | 0.68%   |
| Shure                 | 1         | 0.68%   |
| Realtek Semiconductor | 1         | 0.68%   |
| Logitech              | 1         | 0.68%   |
| LINE TECH INDUSTRIAL  | 1         | 0.68%   |
| DSEA A/S              | 1         | 0.68%   |
| ASUSTek Computer      | 1         | 0.68%   |
| Apple                 | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 8.52%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 7.95%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 5.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 5.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.55%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 2.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.27%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 2.27%   |
| AMD FCH Azalia Controller                                                  | 4         | 2.27%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.7%    |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.7%    |
| Intel C610/X99 series chipset HD Audio Controller                          | 3         | 1.7%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.7%    |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.14%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.14%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.14%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 1.14%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.14%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 1.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 1.14%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.14%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.57%   |
| Shure MV88+                                                                | 1         | 0.57%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.57%   |
| Plantronics HD1                                                            | 1         | 0.57%   |
| Plantronics Blackwire 5220 Series                                          | 1         | 0.57%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.57%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 25%     |
| SK hynix            | 18        | 22.5%   |
| Kingston            | 10        | 12.5%   |
| Crucial             | 8         | 10%     |
| Micron Technology   | 7         | 8.75%   |
| Elpida              | 4         | 5%      |
| Unknown (ABCD)      | 2         | 2.5%    |
| Ramaxel Technology  | 2         | 2.5%    |
| Unknown             | 1         | 1.25%   |
| Transcend           | 1         | 1.25%   |
| Teikon              | 1         | 1.25%   |
| Magnum Tech         | 1         | 1.25%   |
| fef5                | 1         | 1.25%   |
| Corsair             | 1         | 1.25%   |
| ChangXin Memory     | 1         | 1.25%   |
| A-DATA Technology   | 1         | 1.25%   |
| 8945000080AD        | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 3         | 3.49%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 2.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.33%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 2.33%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 2.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 1.16%   |
| Transcend RAM TS256MLK64V3U 2GB DIMM DDR3 1066MT/s               | 1         | 1.16%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.16%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 1.16%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR3 1867MT/s             | 1         | 1.16%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 1.16%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 1         | 1.16%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.16%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s             | 1         | 1.16%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.16%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.16%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.16%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.16%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.16%   |
| SK hynix RAM HMA41GR7AFR4N-UH 8GB DIMM DDR4 2400MT/s             | 1         | 1.16%   |
| SK hynix RAM H9HCNNN8KUMLHR 1GB 2400MT/s                         | 1         | 1.16%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.16%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.16%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.16%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.16%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.16%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.16%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.16%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.16%   |
| Samsung RAM M393A4K40CB1-CRC 32GB DIMM DDR4 2400MT/s             | 1         | 1.16%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 37        | 55.22%  |
| DDR3    | 18        | 26.87%  |
| LPDDR4  | 9         | 13.43%  |
| SDRAM   | 1         | 1.49%   |
| LPDDR3  | 1         | 1.49%   |
| Unknown | 1         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 69.23%  |
| DIMM         | 11        | 16.92%  |
| Row Of Chips | 6         | 9.23%   |
| Unknown      | 2         | 3.08%   |
| Chip         | 1         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 28        | 41.18%  |
| 4096  | 14        | 20.59%  |
| 16384 | 12        | 17.65%  |
| 32768 | 6         | 8.82%   |
| 2048  | 6         | 8.82%   |
| 1024  | 2         | 2.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 18        | 24.66%  |
| 1600  | 14        | 19.18%  |
| 2667  | 12        | 16.44%  |
| 2400  | 10        | 13.7%   |
| 4267  | 3         | 4.11%   |
| 1333  | 3         | 4.11%   |
| 2133  | 2         | 2.74%   |
| 1334  | 2         | 2.74%   |
| 1067  | 2         | 2.74%   |
| 1066  | 2         | 2.74%   |
| 3733  | 1         | 1.37%   |
| 3600  | 1         | 1.37%   |
| 3266  | 1         | 1.37%   |
| 2933  | 1         | 1.37%   |
| 1867  | 1         | 1.37%   |

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
| Chicony Electronics                    | 18        | 23.08%  |
| IMC Networks                           | 9         | 11.54%  |
| Realtek Semiconductor                  | 7         | 8.97%   |
| Luxvisions Innotech Limited            | 6         | 7.69%   |
| Sunplus Innovation Technology          | 5         | 6.41%   |
| Bison Electronics                      | 5         | 6.41%   |
| Apple                                  | 5         | 6.41%   |
| Microdia                               | 4         | 5.13%   |
| Syntek                                 | 3         | 3.85%   |
| Logitech                               | 3         | 3.85%   |
| Samsung Electronics                    | 2         | 2.56%   |
| Quanta                                 | 2         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.56%   |
| Unknown (3730304231385631394831)       | 1         | 1.28%   |
| Unknown                                | 1         | 1.28%   |
| Polycom                                | 1         | 1.28%   |
| Generalplus Technology                 | 1         | 1.28%   |
| Alcor Micro                            | 1         | 1.28%   |
| Acer                                   | 1         | 1.28%   |
| Unknown                                | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 5.13%   |
| Realtek Integrated_Webcam_HD                         | 3         | 3.85%   |
| Logitech HD Pro Webcam C920                          | 3         | 3.85%   |
| IMC Networks Integrated Camera                       | 3         | 3.85%   |
| Chicony USB2.0 Camera                                | 3         | 3.85%   |
| Bison SunplusIT Integrated Camera                    | 3         | 3.85%   |
| Syntek Integrated Camera                             | 2         | 2.56%   |
| Sunplus FHD Camera Microphone                        | 2         | 2.56%   |
| Samsung Galaxy A5 (MTP)                              | 2         | 2.56%   |
| Microdia Integrated_Webcam_HD                        | 2         | 2.56%   |
| Luxvisions Innotech Limited Integrated Camera        | 2         | 2.56%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 2.56%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 2.56%   |
| Chicony Integrated Camera                            | 2         | 2.56%   |
| Chicony HP HD Camera                                 | 2         | 2.56%   |
| Apple FaceTime HD Camera                             | 2         | 2.56%   |
| Unknown ATIV VGA CAMERA                              | 1         | 1.28%   |
| Unknown (3730304231385631394831) USB Camera          | 1         | 1.28%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.28%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 1.28%   |
| Sunplus HD WebCam                                    | 1         | 1.28%   |
| Realtek USB2.0 HD UVC WebCam                         | 1         | 1.28%   |
| Realtek Lenovo EasyCamera                            | 1         | 1.28%   |
| Realtek Integrated Webcam HD                         | 1         | 1.28%   |
| Realtek Integrated Webcam                            | 1         | 1.28%   |
| Quanta USB2.0 HD UVC WebCam                          | 1         | 1.28%   |
| Quanta HP Wide Vision HD Camera                      | 1         | 1.28%   |
| Polycom Poly Studio P5 webcam                        | 1         | 1.28%   |
| Microdia Integrated Webcam HD                        | 1         | 1.28%   |
| Microdia Camera                                      | 1         | 1.28%   |
| Luxvisions Innotech Limited Integrated RGB Camera    | 1         | 1.28%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 1         | 1.28%   |
| IMC Networks Integrated RGB Camera                   | 1         | 1.28%   |
| Generalplus 808 Camera #9 (web-cam mode)             | 1         | 1.28%   |
| Chicony XiaoMi USB 2.0 Webcam                        | 1         | 1.28%   |
| Chicony USB2.0 UVC WebCam                            | 1         | 1.28%   |
| Chicony USB2.0 0.3M UVC WebCam                       | 1         | 1.28%   |
| Chicony Lenovo EasyCamera                            | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 40%     |
| Shenzhen Goodix Technology | 6         | 30%     |
| Validity Sensors           | 3         | 15%     |
| Elan Microelectronics      | 2         | 10%     |
| LighTuning Technology      | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                       | 3         | 15%     |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 10%     |
| Shenzhen Goodix Fingerprint Reader                        | 2         | 10%     |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 5%      |
| Synaptics WBDI Fingerprint Reader USB 102                 | 1         | 5%      |
| Synaptics UWP WBDI Device                                 | 1         | 5%      |
| Synaptics UWP WBDI                                        | 1         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 1         | 5%      |
| Shenzhen Goodix FingerPrint                               | 1         | 5%      |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 1         | 5%      |
| Elan ELAN:Fingerprint                                     | 1         | 5%      |
| Elan ELAN:ARM-M4                                          | 1         | 5%      |
| Unknown                                                   | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Alcor Micro | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 79        | 65.83%  |
| 1     | 27        | 22.5%   |
| 2     | 10        | 8.33%   |
| 3     | 2         | 1.67%   |
| 7     | 1         | 0.83%   |
| 4     | 1         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 34.55%  |
| Net/wireless             | 6         | 10.91%  |
| Graphics card            | 5         | 9.09%   |
| Sound                    | 4         | 7.27%   |
| Communication controller | 4         | 7.27%   |
| Chipcard                 | 4         | 7.27%   |
| Unassigned class         | 3         | 5.45%   |
| Camera                   | 3         | 5.45%   |
| Multimedia controller    | 2         | 3.64%   |
| Card reader              | 2         | 3.64%   |
| Bluetooth                | 2         | 3.64%   |
| Net/ethernet             | 1         | 1.82%   |


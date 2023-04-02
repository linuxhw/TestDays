Linux in Malaysia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Malaysia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Malaysia/Desktop/README.md) and [notebooks](/Location/Malaysia/Notebook/README.md).

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

Total: 561

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | B450M-A PRO MAX             | Desktop     | [54789b15f3](https://linux-hardware.org/?probe=54789b15f3) | Mar 29, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [798462942d](https://linux-hardware.org/?probe=798462942d) | Mar 25, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [eb1d734a53](https://linux-hardware.org/?probe=eb1d734a53) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Biostar       | G41D3+                      | Desktop     | [ebb9a17568](https://linux-hardware.org/?probe=ebb9a17568) | Mar 23, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [b54b641b36](https://linux-hardware.org/?probe=b54b641b36) | Mar 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| Dell          | 084J0R A00                  | Desktop     | [dcde5e81ed](https://linux-hardware.org/?probe=dcde5e81ed) | Mar 04, 2023 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [c9b32e7136](https://linux-hardware.org/?probe=c9b32e7136) | Mar 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| Unknown       | J3160-4L                    | Desktop     | [8089ba23b4](https://linux-hardware.org/?probe=8089ba23b4) | Mar 01, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [1a5ffd0fc4](https://linux-hardware.org/?probe=1a5ffd0fc4) | Mar 01, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [59d082bd5f](https://linux-hardware.org/?probe=59d082bd5f) | Feb 26, 2023 |
| ASUSTek       | ZenBook UX462DA             | Convertible | [4f45a3b6bd](https://linux-hardware.org/?probe=4f45a3b6bd) | Feb 25, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [8f202b88fa](https://linux-hardware.org/?probe=8f202b88fa) | Feb 16, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [c812182e32](https://linux-hardware.org/?probe=c812182e32) | Feb 16, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [9ad890517a](https://linux-hardware.org/?probe=9ad890517a) | Feb 16, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [9763d78500](https://linux-hardware.org/?probe=9763d78500) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [43bd1ca5e1](https://linux-hardware.org/?probe=43bd1ca5e1) | Feb 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [27fa84ce56](https://linux-hardware.org/?probe=27fa84ce56) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [8895a873ab](https://linux-hardware.org/?probe=8895a873ab) | Feb 14, 2023 |
| ASRockRack    | ROMED8-2T                   | Server      | [0a0e30ba0a](https://linux-hardware.org/?probe=0a0e30ba0a) | Feb 14, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [fb00615692](https://linux-hardware.org/?probe=fb00615692) | Feb 14, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [ae563f7bfe](https://linux-hardware.org/?probe=ae563f7bfe) | Feb 14, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| HP            | 18E4                        | Desktop     | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| HP            | ENVY 4                      | Notebook    | [0344f89eea](https://linux-hardware.org/?probe=0344f89eea) | Feb 07, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [56e5f689ab](https://linux-hardware.org/?probe=56e5f689ab) | Feb 06, 2023 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | Notebook    | [5260560c15](https://linux-hardware.org/?probe=5260560c15) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [2d40451b53](https://linux-hardware.org/?probe=2d40451b53) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [903e8715e4](https://linux-hardware.org/?probe=903e8715e4) | Feb 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6013489300](https://linux-hardware.org/?probe=6013489300) | Feb 03, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a195487665](https://linux-hardware.org/?probe=a195487665) | Jan 30, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [d356c9846a](https://linux-hardware.org/?probe=d356c9846a) | Jan 30, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [e660f922a4](https://linux-hardware.org/?probe=e660f922a4) | Jan 27, 2023 |
| HP            | ENVY 4                      | Notebook    | [55ee9d4ca9](https://linux-hardware.org/?probe=55ee9d4ca9) | Jan 27, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [cb932accdb](https://linux-hardware.org/?probe=cb932accdb) | Jan 24, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [d3e44e2970](https://linux-hardware.org/?probe=d3e44e2970) | Jan 20, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [d16f5ca08a](https://linux-hardware.org/?probe=d16f5ca08a) | Jan 19, 2023 |
| Dell          | Latitude 3410               | Notebook    | [187aebc2cd](https://linux-hardware.org/?probe=187aebc2cd) | Jan 19, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [0fe4db1f37](https://linux-hardware.org/?probe=0fe4db1f37) | Jan 16, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [20e990e236](https://linux-hardware.org/?probe=20e990e236) | Jan 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [5d228e798d](https://linux-hardware.org/?probe=5d228e798d) | Jan 16, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [4acb924b75](https://linux-hardware.org/?probe=4acb924b75) | Jan 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [f34e2c982f](https://linux-hardware.org/?probe=f34e2c982f) | Jan 13, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [72a6b9a90b](https://linux-hardware.org/?probe=72a6b9a90b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a712e2524b](https://linux-hardware.org/?probe=a712e2524b) | Jan 09, 2023 |
| HP            | 2B2C                        | Desktop     | [1a74d92aaf](https://linux-hardware.org/?probe=1a74d92aaf) | Jan 08, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [f82bf510be](https://linux-hardware.org/?probe=f82bf510be) | Dec 31, 2022 |
| Dell          | Latitude 5420               | Notebook    | [06dc453cbc](https://linux-hardware.org/?probe=06dc453cbc) | Dec 27, 2022 |
| HP            | Notebook                    | Notebook    | [8ba42c8ebc](https://linux-hardware.org/?probe=8ba42c8ebc) | Dec 27, 2022 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [44d3b06704](https://linux-hardware.org/?probe=44d3b06704) | Dec 23, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [fd4611b301](https://linux-hardware.org/?probe=fd4611b301) | Dec 21, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4efe19137d](https://linux-hardware.org/?probe=4efe19137d) | Dec 21, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [2b0d31db9d](https://linux-hardware.org/?probe=2b0d31db9d) | Dec 18, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [e482b827aa](https://linux-hardware.org/?probe=e482b827aa) | Dec 17, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1550136432](https://linux-hardware.org/?probe=1550136432) | Dec 06, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [10a6f30aeb](https://linux-hardware.org/?probe=10a6f30aeb) | Dec 04, 2022 |
| Acer          | Aspire V5-471G              | Notebook    | [725404aadb](https://linux-hardware.org/?probe=725404aadb) | Dec 04, 2022 |
| Sony          | VPCEG16EG                   | Notebook    | [ee22559858](https://linux-hardware.org/?probe=ee22559858) | Nov 23, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| HP            | 2B2C                        | Desktop     | [91862a2497](https://linux-hardware.org/?probe=91862a2497) | Nov 19, 2022 |
| Dell          | Latitude E6220              | Notebook    | [c92cd25690](https://linux-hardware.org/?probe=c92cd25690) | Nov 19, 2022 |
| HP            | 2B2C                        | Desktop     | [2eb8311f18](https://linux-hardware.org/?probe=2eb8311f18) | Nov 16, 2022 |
| Lenovo        | ThinkPad T450 20BUS1S81K    | Notebook    | [ee3fb9c9d2](https://linux-hardware.org/?probe=ee3fb9c9d2) | Nov 14, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1fef4a8aa5](https://linux-hardware.org/?probe=1fef4a8aa5) | Nov 13, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [29641e8b7c](https://linux-hardware.org/?probe=29641e8b7c) | Nov 09, 2022 |
| Dell          | 0V52N7 A02                  | Server      | [3151a21ebf](https://linux-hardware.org/?probe=3151a21ebf) | Nov 09, 2022 |
| Dell          | Latitude E6230              | Notebook    | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b39c12a9a4](https://linux-hardware.org/?probe=b39c12a9a4) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| NEC Comput... | PC-VK27MXZCG                | Notebook    | [04c88c4087](https://linux-hardware.org/?probe=04c88c4087) | Oct 24, 2022 |
| Dell          | Precision 3561              | Notebook    | [dcf74e5715](https://linux-hardware.org/?probe=dcf74e5715) | Oct 22, 2022 |
| Dell          | Precision 3561              | Notebook    | [f514228295](https://linux-hardware.org/?probe=f514228295) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| ASUSTek       | UN65U                       | Mini pc     | [f0bab8d97c](https://linux-hardware.org/?probe=f0bab8d97c) | Oct 06, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1cceb45dea](https://linux-hardware.org/?probe=1cceb45dea) | Oct 04, 2022 |
| HP            | 2B2C                        | Desktop     | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | Notebook    | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3e5af3e86c](https://linux-hardware.org/?probe=3e5af3e86c) | Sep 25, 2022 |
| HP            | 18E7                        | Desktop     | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [3f33a64102](https://linux-hardware.org/?probe=3f33a64102) | Sep 21, 2022 |
| ASUSTek       | PN51                        | Mini pc     | [0d8e7f2e92](https://linux-hardware.org/?probe=0d8e7f2e92) | Sep 21, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [48479f01c1](https://linux-hardware.org/?probe=48479f01c1) | Sep 19, 2022 |
| Alienware     | M14xR1                      | Notebook    | [a4064c0342](https://linux-hardware.org/?probe=a4064c0342) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [3162a68bf5](https://linux-hardware.org/?probe=3162a68bf5) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | Notebook    | [d764e72d74](https://linux-hardware.org/?probe=d764e72d74) | Sep 12, 2022 |
| Alienware     | M14xR1                      | Notebook    | [ea2adf914b](https://linux-hardware.org/?probe=ea2adf914b) | Sep 10, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [3310a4c592](https://linux-hardware.org/?probe=3310a4c592) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [25e7e97937](https://linux-hardware.org/?probe=25e7e97937) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [9b0e2c480f](https://linux-hardware.org/?probe=9b0e2c480f) | Aug 28, 2022 |
| Alienware     | M14xR1                      | Notebook    | [498d5f5254](https://linux-hardware.org/?probe=498d5f5254) | Aug 27, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [398f6d4b78](https://linux-hardware.org/?probe=398f6d4b78) | Aug 25, 2022 |
| Dell          | 0PU052                      | Desktop     | [2bffd37724](https://linux-hardware.org/?probe=2bffd37724) | Aug 24, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [23316377ee](https://linux-hardware.org/?probe=23316377ee) | Aug 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [9630e2d4f5](https://linux-hardware.org/?probe=9630e2d4f5) | Aug 21, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [ee6cfb6de5](https://linux-hardware.org/?probe=ee6cfb6de5) | Aug 19, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [cb26c73037](https://linux-hardware.org/?probe=cb26c73037) | Aug 16, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [0aefa0613d](https://linux-hardware.org/?probe=0aefa0613d) | Aug 15, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [d000ce4d8c](https://linux-hardware.org/?probe=d000ce4d8c) | Aug 15, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [66a759db9c](https://linux-hardware.org/?probe=66a759db9c) | Aug 14, 2022 |
| Acer          | Peppy                       | Notebook    | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [30715e2f04](https://linux-hardware.org/?probe=30715e2f04) | Aug 01, 2022 |
| GPD           | G1619-02                    | Notebook    | [c61c4280c8](https://linux-hardware.org/?probe=c61c4280c8) | Jul 31, 2022 |
| Lenovo        | ThinkCentre M58 7359DHJ     | Desktop     | [46c2c1db62](https://linux-hardware.org/?probe=46c2c1db62) | Jul 26, 2022 |
| ONDA          | H110-MINI V3.00 Ver:3.00    | Desktop     | [62b2a7897b](https://linux-hardware.org/?probe=62b2a7897b) | Jul 24, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8dd3e52620](https://linux-hardware.org/?probe=8dd3e52620) | Jul 21, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [82b077a668](https://linux-hardware.org/?probe=82b077a668) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [aa2a721361](https://linux-hardware.org/?probe=aa2a721361) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [1c3c80b88e](https://linux-hardware.org/?probe=1c3c80b88e) | Jul 13, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [0287348f80](https://linux-hardware.org/?probe=0287348f80) | Jul 12, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [616a2b7524](https://linux-hardware.org/?probe=616a2b7524) | Jul 12, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [71758de9e1](https://linux-hardware.org/?probe=71758de9e1) | Jul 06, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [39c0379cee](https://linux-hardware.org/?probe=39c0379cee) | Jul 04, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [5540b74d09](https://linux-hardware.org/?probe=5540b74d09) | Jul 03, 2022 |
| ASUSTek       | K401UQK                     | Notebook    | [c793608515](https://linux-hardware.org/?probe=c793608515) | Jul 03, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [4857a7b7bf](https://linux-hardware.org/?probe=4857a7b7bf) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [c5a5b25674](https://linux-hardware.org/?probe=c5a5b25674) | Jun 28, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [c292904665](https://linux-hardware.org/?probe=c292904665) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | Desktop     | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [0b792ecaef](https://linux-hardware.org/?probe=0b792ecaef) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [9dae5c70a5](https://linux-hardware.org/?probe=9dae5c70a5) | Jun 14, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [1d0ca4cb7a](https://linux-hardware.org/?probe=1d0ca4cb7a) | Jun 12, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [ded6b87e98](https://linux-hardware.org/?probe=ded6b87e98) | Jun 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [568b23271e](https://linux-hardware.org/?probe=568b23271e) | Jun 11, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [4692c93a71](https://linux-hardware.org/?probe=4692c93a71) | Jun 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [bc911a9c04](https://linux-hardware.org/?probe=bc911a9c04) | May 21, 2022 |
| ASUSTek       | K42Jc                       | Notebook    | [29538e9e80](https://linux-hardware.org/?probe=29538e9e80) | May 21, 2022 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [e0aab70a85](https://linux-hardware.org/?probe=e0aab70a85) | May 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d525e0eb0c](https://linux-hardware.org/?probe=d525e0eb0c) | May 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [0a9f8b0a4a](https://linux-hardware.org/?probe=0a9f8b0a4a) | May 09, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [f34555b3d6](https://linux-hardware.org/?probe=f34555b3d6) | Apr 30, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [43adb86887](https://linux-hardware.org/?probe=43adb86887) | Apr 25, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [ba9b8d5ac1](https://linux-hardware.org/?probe=ba9b8d5ac1) | Apr 25, 2022 |
| ECS           | Iris8                       | Desktop     | [1cff4313c1](https://linux-hardware.org/?probe=1cff4313c1) | Apr 23, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [c4456aaa4f](https://linux-hardware.org/?probe=c4456aaa4f) | Apr 19, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6dd82e724](https://linux-hardware.org/?probe=c6dd82e724) | Apr 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [e525a26ca8](https://linux-hardware.org/?probe=e525a26ca8) | Apr 14, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [fc21d0150f](https://linux-hardware.org/?probe=fc21d0150f) | Apr 10, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [9ddd1338d3](https://linux-hardware.org/?probe=9ddd1338d3) | Apr 08, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [7ec10d98e3](https://linux-hardware.org/?probe=7ec10d98e3) | Apr 03, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [6cd967267b](https://linux-hardware.org/?probe=6cd967267b) | Mar 31, 2022 |
| Lenovo        | 30D9 NOK                    | Desktop     | [c378cd6fd3](https://linux-hardware.org/?probe=c378cd6fd3) | Mar 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [d9e3d65314](https://linux-hardware.org/?probe=d9e3d65314) | Mar 24, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Inspiron 15 5501            | Notebook    | [1865c91af0](https://linux-hardware.org/?probe=1865c91af0) | Mar 20, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a1c0612337](https://linux-hardware.org/?probe=a1c0612337) | Mar 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [d52d9feb9e](https://linux-hardware.org/?probe=d52d9feb9e) | Mar 09, 2022 |
| Dell          | Precision 7730              | Notebook    | [9e9710e890](https://linux-hardware.org/?probe=9e9710e890) | Mar 08, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [8d3f72c54f](https://linux-hardware.org/?probe=8d3f72c54f) | Mar 03, 2022 |
| Biostar       | G41D3+                      | Desktop     | [62ba30cf71](https://linux-hardware.org/?probe=62ba30cf71) | Mar 02, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [bbedea92ea](https://linux-hardware.org/?probe=bbedea92ea) | Mar 01, 2022 |
| Dell          | 0D441T A03                  | Desktop     | [297c168632](https://linux-hardware.org/?probe=297c168632) | Mar 01, 2022 |
| Shuttle       | FH170                       | Desktop     | [768e13fd34](https://linux-hardware.org/?probe=768e13fd34) | Feb 25, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [1dec2ddfad](https://linux-hardware.org/?probe=1dec2ddfad) | Feb 19, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [747515703c](https://linux-hardware.org/?probe=747515703c) | Jan 25, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5d1c8ba7f2](https://linux-hardware.org/?probe=5d1c8ba7f2) | Jan 18, 2022 |
| Dell          | Precision 5550              | Notebook    | [6b866b7c2f](https://linux-hardware.org/?probe=6b866b7c2f) | Jan 18, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [7e0ee3374e](https://linux-hardware.org/?probe=7e0ee3374e) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [ff2f0db3fe](https://linux-hardware.org/?probe=ff2f0db3fe) | Jan 09, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | Latitude 7490               | Notebook    | [4ac5151ac0](https://linux-hardware.org/?probe=4ac5151ac0) | Dec 29, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | Notebook    | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9fe5f60531](https://linux-hardware.org/?probe=9fe5f60531) | Dec 26, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c8ca1c8cc8](https://linux-hardware.org/?probe=c8ca1c8cc8) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [c748f77108](https://linux-hardware.org/?probe=c748f77108) | Dec 12, 2021 |
| HP            | 2B44                        | Desktop     | [b62df43777](https://linux-hardware.org/?probe=b62df43777) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [faf1be45ae](https://linux-hardware.org/?probe=faf1be45ae) | Dec 03, 2021 |
| Dell          | Latitude E6520              | Notebook    | [16b69bfefc](https://linux-hardware.org/?probe=16b69bfefc) | Dec 01, 2021 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [eb4fb496ae](https://linux-hardware.org/?probe=eb4fb496ae) | Dec 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5c4ae3bd8c](https://linux-hardware.org/?probe=5c4ae3bd8c) | Nov 30, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [c731d25471](https://linux-hardware.org/?probe=c731d25471) | Nov 30, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [6e5e669c60](https://linux-hardware.org/?probe=6e5e669c60) | Nov 25, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [644d197332](https://linux-hardware.org/?probe=644d197332) | Nov 17, 2021 |
| Lenovo        | ThinkPad T460 20FMA0J6MY    | Notebook    | [bece194d5a](https://linux-hardware.org/?probe=bece194d5a) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [b5393ad660](https://linux-hardware.org/?probe=b5393ad660) | Nov 12, 2021 |
| ASUSTek       | T200TA                      | Notebook    | [1f55c83774](https://linux-hardware.org/?probe=1f55c83774) | Nov 04, 2021 |
| ASUSTek       | M2N32-SLI DELUXE            | Desktop     | [87fff05f0f](https://linux-hardware.org/?probe=87fff05f0f) | Nov 03, 2021 |
| Lenovo        | U310                        | Notebook    | [986ba47618](https://linux-hardware.org/?probe=986ba47618) | Oct 24, 2021 |
| Lenovo        | U310                        | Notebook    | [c74a07756c](https://linux-hardware.org/?probe=c74a07756c) | Oct 24, 2021 |
| Intel         | B75                         | Desktop     | [fef715f491](https://linux-hardware.org/?probe=fef715f491) | Oct 23, 2021 |
| Dell          | Latitude 7390 2-in-1        | Convertible | [ccd587fde5](https://linux-hardware.org/?probe=ccd587fde5) | Oct 21, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | Notebook                    | Notebook    | [2761140513](https://linux-hardware.org/?probe=2761140513) | Oct 14, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [8fee3106f7](https://linux-hardware.org/?probe=8fee3106f7) | Oct 12, 2021 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [f79000e059](https://linux-hardware.org/?probe=f79000e059) | Oct 12, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Biostar       | G41D3C                      | Desktop     | [433bc7cf78](https://linux-hardware.org/?probe=433bc7cf78) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [09b2cd1736](https://linux-hardware.org/?probe=09b2cd1736) | Oct 06, 2021 |
| Biostar       | G41D3C                      | Desktop     | [90dc88db01](https://linux-hardware.org/?probe=90dc88db01) | Oct 02, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| HP            | Notebook                    | Notebook    | [32d9b71796](https://linux-hardware.org/?probe=32d9b71796) | Sep 25, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [1292424ff8](https://linux-hardware.org/?probe=1292424ff8) | Sep 17, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9de4382874](https://linux-hardware.org/?probe=9de4382874) | Sep 15, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [7441498212](https://linux-hardware.org/?probe=7441498212) | Sep 14, 2021 |
| Lenovo        | Flex 6-11IGM 81A7           | Convertible | [17e78af479](https://linux-hardware.org/?probe=17e78af479) | Sep 14, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [c2533e9d48](https://linux-hardware.org/?probe=c2533e9d48) | Sep 11, 2021 |
| MSI           | H81M-P33                    | Desktop     | [92b799f852](https://linux-hardware.org/?probe=92b799f852) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [8137e09a97](https://linux-hardware.org/?probe=8137e09a97) | Sep 08, 2021 |
| Biostar       | G41D3C                      | Desktop     | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9c46f65e1d](https://linux-hardware.org/?probe=9c46f65e1d) | Sep 06, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| HP            | ENVY 4                      | Notebook    | [b61e9946e0](https://linux-hardware.org/?probe=b61e9946e0) | Sep 04, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5377e486bc](https://linux-hardware.org/?probe=5377e486bc) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [acc6c11a97](https://linux-hardware.org/?probe=acc6c11a97) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7b28a98a35](https://linux-hardware.org/?probe=7b28a98a35) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [7fada0ab8c](https://linux-hardware.org/?probe=7fada0ab8c) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a61ee6d83a](https://linux-hardware.org/?probe=a61ee6d83a) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a1ec21ae3f](https://linux-hardware.org/?probe=a1ec21ae3f) | Aug 29, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [cac6720bff](https://linux-hardware.org/?probe=cac6720bff) | Aug 29, 2021 |
| Lenovo        | G400s VILG1                 | Notebook    | [20d6b25fd3](https://linux-hardware.org/?probe=20d6b25fd3) | Aug 29, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [777faedb05](https://linux-hardware.org/?probe=777faedb05) | Aug 27, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [906a3e006c](https://linux-hardware.org/?probe=906a3e006c) | Aug 24, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f369218ff](https://linux-hardware.org/?probe=9f369218ff) | Aug 24, 2021 |
| Gigabyte      | B450M S2H V2                | Desktop     | [9e8fa8f32d](https://linux-hardware.org/?probe=9e8fa8f32d) | Aug 23, 2021 |
| HP            | Notebook                    | Notebook    | [4028a5fb73](https://linux-hardware.org/?probe=4028a5fb73) | Aug 21, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [de1fa2ccc0](https://linux-hardware.org/?probe=de1fa2ccc0) | Aug 20, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [bb82d97c94](https://linux-hardware.org/?probe=bb82d97c94) | Aug 10, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [38abf3b8e9](https://linux-hardware.org/?probe=38abf3b8e9) | Aug 10, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [89188fe3ca](https://linux-hardware.org/?probe=89188fe3ca) | Aug 08, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e56e95f2f](https://linux-hardware.org/?probe=3e56e95f2f) | Aug 05, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [b10f021bef](https://linux-hardware.org/?probe=b10f021bef) | Aug 01, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [36562061d6](https://linux-hardware.org/?probe=36562061d6) | Jul 30, 2021 |
| Lenovo        | ThinkPad X131e 33682YU      | Notebook    | [4cf28c3600](https://linux-hardware.org/?probe=4cf28c3600) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| HP            | Notebook                    | Notebook    | [458741e8e2](https://linux-hardware.org/?probe=458741e8e2) | Jul 23, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [e71a7fc65b](https://linux-hardware.org/?probe=e71a7fc65b) | Jul 23, 2021 |
| HP            | Pavilion 14                 | Notebook    | [0556a517ff](https://linux-hardware.org/?probe=0556a517ff) | Jul 23, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [fe43d29e0e](https://linux-hardware.org/?probe=fe43d29e0e) | Jul 22, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [3e66028cf8](https://linux-hardware.org/?probe=3e66028cf8) | Jul 22, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3c81cd98ac](https://linux-hardware.org/?probe=3c81cd98ac) | Jul 21, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [2e26e3540a](https://linux-hardware.org/?probe=2e26e3540a) | Jul 20, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [b74062f49d](https://linux-hardware.org/?probe=b74062f49d) | Jul 20, 2021 |
| ASUSTek       | K43SA                       | Notebook    | [3da0ea28fa](https://linux-hardware.org/?probe=3da0ea28fa) | Jul 20, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [ce3ef21b15](https://linux-hardware.org/?probe=ce3ef21b15) | Jul 19, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [70e6e81263](https://linux-hardware.org/?probe=70e6e81263) | Jul 19, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [5a349c4952](https://linux-hardware.org/?probe=5a349c4952) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [275304e806](https://linux-hardware.org/?probe=275304e806) | Jul 19, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [99df792e3b](https://linux-hardware.org/?probe=99df792e3b) | Jul 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [02dc77286f](https://linux-hardware.org/?probe=02dc77286f) | Jul 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [9ffbb5bc79](https://linux-hardware.org/?probe=9ffbb5bc79) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [0e8b29c721](https://linux-hardware.org/?probe=0e8b29c721) | Jul 15, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [da8679ccca](https://linux-hardware.org/?probe=da8679ccca) | Jul 14, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [2495cf9be5](https://linux-hardware.org/?probe=2495cf9be5) | Jul 12, 2021 |
| HP            | Compaq 6530b (VA036PA#UU... | Notebook    | [ac0b6b96cc](https://linux-hardware.org/?probe=ac0b6b96cc) | Jul 11, 2021 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b551baea7d](https://linux-hardware.org/?probe=b551baea7d) | Jul 11, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [477a92a37e](https://linux-hardware.org/?probe=477a92a37e) | Jul 11, 2021 |
| HP            | Notebook                    | Notebook    | [2f040042a3](https://linux-hardware.org/?probe=2f040042a3) | Jul 10, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [82c73cf6be](https://linux-hardware.org/?probe=82c73cf6be) | Jul 09, 2021 |
| ASUSTek       | X556UR                      | Notebook    | [4e555accb1](https://linux-hardware.org/?probe=4e555accb1) | Jul 08, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [416014c8b8](https://linux-hardware.org/?probe=416014c8b8) | Jul 07, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [a630867e0a](https://linux-hardware.org/?probe=a630867e0a) | Jul 06, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [e8965c736d](https://linux-hardware.org/?probe=e8965c736d) | Jul 05, 2021 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [e1a02c3dcb](https://linux-hardware.org/?probe=e1a02c3dcb) | Jul 04, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [939fe39f71](https://linux-hardware.org/?probe=939fe39f71) | Jul 01, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [44c1472c85](https://linux-hardware.org/?probe=44c1472c85) | Jun 30, 2021 |
| AZW           | GT-R                        | Notebook    | [feaf90902f](https://linux-hardware.org/?probe=feaf90902f) | Jun 28, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [de1dbcbd7f](https://linux-hardware.org/?probe=de1dbcbd7f) | Jun 27, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [ddb8152ea4](https://linux-hardware.org/?probe=ddb8152ea4) | Jun 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [1104a3ca5a](https://linux-hardware.org/?probe=1104a3ca5a) | Jun 26, 2021 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [a5a80d3f13](https://linux-hardware.org/?probe=a5a80d3f13) | Jun 24, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [d9270ab2c1](https://linux-hardware.org/?probe=d9270ab2c1) | Jun 23, 2021 |
| Lenovo        | ThinkPad X201 3626RZ4       | Notebook    | [737819a617](https://linux-hardware.org/?probe=737819a617) | Jun 22, 2021 |
| HP            | Notebook                    | Notebook    | [0f663cf796](https://linux-hardware.org/?probe=0f663cf796) | Jun 20, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [9a397ba3b9](https://linux-hardware.org/?probe=9a397ba3b9) | Jun 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [0183eeb644](https://linux-hardware.org/?probe=0183eeb644) | Jun 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b0ded1652a](https://linux-hardware.org/?probe=b0ded1652a) | Jun 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e4a2d2d3c9](https://linux-hardware.org/?probe=e4a2d2d3c9) | Jun 06, 2021 |
| MSI           | H81M-P33                    | Desktop     | [69a8b43e74](https://linux-hardware.org/?probe=69a8b43e74) | Jun 02, 2021 |
| MSI           | H81M-P33                    | Desktop     | [a67e6bcfce](https://linux-hardware.org/?probe=a67e6bcfce) | Jun 02, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [49a2755ccd](https://linux-hardware.org/?probe=49a2755ccd) | May 31, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [00658a23ab](https://linux-hardware.org/?probe=00658a23ab) | May 27, 2021 |
| Lenovo        | ThinkPad X120e 0611CTO      | Notebook    | [72608b2ea0](https://linux-hardware.org/?probe=72608b2ea0) | May 27, 2021 |
| ASUSTek       | H97M-E                      | Desktop     | [5f39051050](https://linux-hardware.org/?probe=5f39051050) | May 26, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [1a314f201b](https://linux-hardware.org/?probe=1a314f201b) | May 26, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4c5c7570f6](https://linux-hardware.org/?probe=4c5c7570f6) | May 25, 2021 |
| HP            | Notebook                    | Notebook    | [a075cb3a8d](https://linux-hardware.org/?probe=a075cb3a8d) | May 24, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [2b0de1ba10](https://linux-hardware.org/?probe=2b0de1ba10) | May 21, 2021 |
| HP            | Pavilion dv6                | Notebook    | [021e17aa96](https://linux-hardware.org/?probe=021e17aa96) | May 19, 2021 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [0cd0f0c51f](https://linux-hardware.org/?probe=0cd0f0c51f) | May 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [71f7778600](https://linux-hardware.org/?probe=71f7778600) | May 13, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [d6ab5352b8](https://linux-hardware.org/?probe=d6ab5352b8) | May 10, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [67e6985b08](https://linux-hardware.org/?probe=67e6985b08) | May 02, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [8624f1c148](https://linux-hardware.org/?probe=8624f1c148) | Apr 30, 2021 |
| HP            | 0AA8h                       | Desktop     | [5f350b471f](https://linux-hardware.org/?probe=5f350b471f) | Apr 29, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [6bb8ea7872](https://linux-hardware.org/?probe=6bb8ea7872) | Apr 23, 2021 |
| System76      | Galago Pro                  | Notebook    | [e712e1fadc](https://linux-hardware.org/?probe=e712e1fadc) | Apr 21, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [07efcf431f](https://linux-hardware.org/?probe=07efcf431f) | Apr 14, 2021 |
| Gigabyte      | Z97X-Gaming G1              | Desktop     | [9f265d798d](https://linux-hardware.org/?probe=9f265d798d) | Apr 14, 2021 |
| AMI           | Cherry Trail Tablet         | Desktop     | [87041c97fb](https://linux-hardware.org/?probe=87041c97fb) | Apr 14, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [6d3642385e](https://linux-hardware.org/?probe=6d3642385e) | Apr 11, 2021 |
| HP            | 2B1C MVB,A                  | All in one  | [ea47f5adbe](https://linux-hardware.org/?probe=ea47f5adbe) | Apr 05, 2021 |
| Dell          | XPS L412Z                   | Notebook    | [e383c24416](https://linux-hardware.org/?probe=e383c24416) | Apr 01, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [006be2bbab](https://linux-hardware.org/?probe=006be2bbab) | Mar 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [1a6bdfe860](https://linux-hardware.org/?probe=1a6bdfe860) | Mar 22, 2021 |
| Dell          | Inspiron 5548               | Notebook    | [7a17fa61d9](https://linux-hardware.org/?probe=7a17fa61d9) | Mar 17, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [d476794634](https://linux-hardware.org/?probe=d476794634) | Mar 16, 2021 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [fc405347a5](https://linux-hardware.org/?probe=fc405347a5) | Mar 12, 2021 |
| Sony          | VPCEA42EG                   | Notebook    | [e49095cfef](https://linux-hardware.org/?probe=e49095cfef) | Mar 09, 2021 |
| ASUSTek       | S550CM                      | Notebook    | [5ac3e9de20](https://linux-hardware.org/?probe=5ac3e9de20) | Mar 08, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [597b4f88b9](https://linux-hardware.org/?probe=597b4f88b9) | Mar 08, 2021 |
| HP            | Presario CQ43               | Notebook    | [4f9c0e744c](https://linux-hardware.org/?probe=4f9c0e744c) | Feb 28, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [082f8fd3e5](https://linux-hardware.org/?probe=082f8fd3e5) | Feb 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [1555ed8743](https://linux-hardware.org/?probe=1555ed8743) | Feb 27, 2021 |
| ASUSTek       | H110M-D                     | Desktop     | [19e3cff2be](https://linux-hardware.org/?probe=19e3cff2be) | Feb 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [4f82ee745a](https://linux-hardware.org/?probe=4f82ee745a) | Feb 25, 2021 |
| HP            | Presario CQ43               | Notebook    | [e6e7199511](https://linux-hardware.org/?probe=e6e7199511) | Feb 22, 2021 |
| ASUSTek       | X456UF                      | Notebook    | [f69a109f5c](https://linux-hardware.org/?probe=f69a109f5c) | Feb 14, 2021 |
| HP            | G42                         | Notebook    | [7e1ebb9cf3](https://linux-hardware.org/?probe=7e1ebb9cf3) | Feb 13, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [6c0820678b](https://linux-hardware.org/?probe=6c0820678b) | Feb 13, 2021 |
| HP            | Pavilion dv6                | Notebook    | [92518dacfe](https://linux-hardware.org/?probe=92518dacfe) | Feb 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4f8464acc9](https://linux-hardware.org/?probe=4f8464acc9) | Feb 10, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [ea93e4d3cd](https://linux-hardware.org/?probe=ea93e4d3cd) | Feb 09, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [b50872caf4](https://linux-hardware.org/?probe=b50872caf4) | Feb 07, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [7daa68908c](https://linux-hardware.org/?probe=7daa68908c) | Feb 06, 2021 |
| Acer          | MCP73VE NVIDIA MCP73        | Desktop     | [acb369859f](https://linux-hardware.org/?probe=acb369859f) | Feb 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [aa40d0ff2b](https://linux-hardware.org/?probe=aa40d0ff2b) | Feb 04, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [d6126d9f25](https://linux-hardware.org/?probe=d6126d9f25) | Jan 27, 2021 |
| Acer          | Veriton X6630G V:1.0        | Desktop     | [9e5a28d45d](https://linux-hardware.org/?probe=9e5a28d45d) | Jan 27, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [9b13ab689f](https://linux-hardware.org/?probe=9b13ab689f) | Jan 24, 2021 |
| Dell          | Latitude E6440              | Notebook    | [31faebfa48](https://linux-hardware.org/?probe=31faebfa48) | Jan 23, 2021 |
| Dell          | Latitude 3440               | Notebook    | [ba52d4afcf](https://linux-hardware.org/?probe=ba52d4afcf) | Jan 22, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [353fb07166](https://linux-hardware.org/?probe=353fb07166) | Jan 20, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [dd87c824a0](https://linux-hardware.org/?probe=dd87c824a0) | Jan 18, 2021 |
| HP            | G42                         | Notebook    | [b4a8c3727b](https://linux-hardware.org/?probe=b4a8c3727b) | Jan 13, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [9e291d5782](https://linux-hardware.org/?probe=9e291d5782) | Jan 12, 2021 |
| HP            | Notebook                    | Notebook    | [6bb93d5d1d](https://linux-hardware.org/?probe=6bb93d5d1d) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [d410f07eef](https://linux-hardware.org/?probe=d410f07eef) | Jan 03, 2021 |
| HP            | Presario CQ43               | Notebook    | [15ba146bfe](https://linux-hardware.org/?probe=15ba146bfe) | Jan 03, 2021 |
| Intel         | DH77KC AAG39641-400         | Desktop     | [f3c691cbf8](https://linux-hardware.org/?probe=f3c691cbf8) | Jan 01, 2021 |
| MSI           | H81M-P33                    | Desktop     | [e8d73a49e5](https://linux-hardware.org/?probe=e8d73a49e5) | Dec 30, 2020 |
| HP            | Pavilion g4                 | Notebook    | [c495b342b0](https://linux-hardware.org/?probe=c495b342b0) | Dec 30, 2020 |
| ASUSTek       | TP500LN                     | Notebook    | [36ae52e7d3](https://linux-hardware.org/?probe=36ae52e7d3) | Dec 27, 2020 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [fa76a31b79](https://linux-hardware.org/?probe=fa76a31b79) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [7e473c8d12](https://linux-hardware.org/?probe=7e473c8d12) | Dec 24, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [645dfe5a80](https://linux-hardware.org/?probe=645dfe5a80) | Dec 23, 2020 |
| Dell          | 0PU052                      | Desktop     | [520a4ef3d0](https://linux-hardware.org/?probe=520a4ef3d0) | Dec 23, 2020 |
| Biostar       | A320MH                      | Desktop     | [a6b1134a37](https://linux-hardware.org/?probe=a6b1134a37) | Dec 18, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [41d76fb580](https://linux-hardware.org/?probe=41d76fb580) | Dec 17, 2020 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [a0b90b128d](https://linux-hardware.org/?probe=a0b90b128d) | Dec 16, 2020 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [9af064ae47](https://linux-hardware.org/?probe=9af064ae47) | Dec 16, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [414fc579a1](https://linux-hardware.org/?probe=414fc579a1) | Dec 02, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [4d1d3b1722](https://linux-hardware.org/?probe=4d1d3b1722) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [cf6242caca](https://linux-hardware.org/?probe=cf6242caca) | Dec 02, 2020 |
| Intel         | DH61WW AAG23116-300         | Desktop     | [afbf8ce7bc](https://linux-hardware.org/?probe=afbf8ce7bc) | Dec 01, 2020 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [967bb7f4d6](https://linux-hardware.org/?probe=967bb7f4d6) | Nov 30, 2020 |
| HP            | 2B1C MVB,A                  | All in one  | [400561434f](https://linux-hardware.org/?probe=400561434f) | Nov 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [151262b7a2](https://linux-hardware.org/?probe=151262b7a2) | Nov 26, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [eecae3dcbf](https://linux-hardware.org/?probe=eecae3dcbf) | Nov 26, 2020 |
| Dell          | G3 3590                     | Notebook    | [d76accb676](https://linux-hardware.org/?probe=d76accb676) | Nov 18, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [c323f09a39](https://linux-hardware.org/?probe=c323f09a39) | Nov 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [db8eeca79f](https://linux-hardware.org/?probe=db8eeca79f) | Nov 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [f617d36143](https://linux-hardware.org/?probe=f617d36143) | Nov 12, 2020 |
| Gigabyte      | Z490 VISION D               | Desktop     | [af58d1579d](https://linux-hardware.org/?probe=af58d1579d) | Nov 09, 2020 |
| Acer          | TM4750                      | Notebook    | [8380f08a89](https://linux-hardware.org/?probe=8380f08a89) | Nov 07, 2020 |
| HP            | Compaq Presario CQ60        | Notebook    | [4c1052e401](https://linux-hardware.org/?probe=4c1052e401) | Nov 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [b2a86aaf94](https://linux-hardware.org/?probe=b2a86aaf94) | Nov 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [50772450d3](https://linux-hardware.org/?probe=50772450d3) | Nov 04, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [1a5aef928b](https://linux-hardware.org/?probe=1a5aef928b) | Nov 01, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5021546be8](https://linux-hardware.org/?probe=5021546be8) | Oct 30, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [adc51544ee](https://linux-hardware.org/?probe=adc51544ee) | Oct 29, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | Notebook    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Acer          | TM4750                      | Notebook    | [2f46c4d024](https://linux-hardware.org/?probe=2f46c4d024) | Oct 27, 2020 |
| Acer          | TM4750                      | Notebook    | [29124f29f8](https://linux-hardware.org/?probe=29124f29f8) | Oct 23, 2020 |
| Dell          | G3 3590                     | Notebook    | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6aa803efb](https://linux-hardware.org/?probe=b6aa803efb) | Oct 21, 2020 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [02a2657831](https://linux-hardware.org/?probe=02a2657831) | Oct 20, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [5c8d0c0991](https://linux-hardware.org/?probe=5c8d0c0991) | Oct 15, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1a37736727](https://linux-hardware.org/?probe=1a37736727) | Oct 13, 2020 |
| Dell          | 06D7TR A02                  | Desktop     | [1fff522fa1](https://linux-hardware.org/?probe=1fff522fa1) | Oct 13, 2020 |
| Dell          | 09WH54 A00                  | Desktop     | [e8e5a3c2ac](https://linux-hardware.org/?probe=e8e5a3c2ac) | Oct 12, 2020 |
| Sony          | VGN-Z27GN_X                 | Notebook    | [a9230212d3](https://linux-hardware.org/?probe=a9230212d3) | Oct 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [80297bebea](https://linux-hardware.org/?probe=80297bebea) | Sep 17, 2020 |
| HP            | Pavilion dv6                | Notebook    | [f48a018bbb](https://linux-hardware.org/?probe=f48a018bbb) | Sep 16, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [5eaf26f820](https://linux-hardware.org/?probe=5eaf26f820) | Sep 15, 2020 |
| ASUSTek       | K45VD                       | Notebook    | [4e3ee75e9b](https://linux-hardware.org/?probe=4e3ee75e9b) | Sep 15, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f7f932b330](https://linux-hardware.org/?probe=f7f932b330) | Sep 14, 2020 |
| Acer          | Aspire ES1-420              | Notebook    | [730ae12528](https://linux-hardware.org/?probe=730ae12528) | Sep 10, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [828c695fab](https://linux-hardware.org/?probe=828c695fab) | Sep 06, 2020 |
| HP            | Pavilion dv6                | Notebook    | [47c4b0fdaa](https://linux-hardware.org/?probe=47c4b0fdaa) | Sep 03, 2020 |
| Dell          | Inspiron 5482               | Convertible | [4085a729ac](https://linux-hardware.org/?probe=4085a729ac) | Sep 03, 2020 |
| Dell          | 0RW203                      | Desktop     | [594ab9e6d3](https://linux-hardware.org/?probe=594ab9e6d3) | Sep 02, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [0930a62ca5](https://linux-hardware.org/?probe=0930a62ca5) | Aug 21, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| ASUSTek       | VivoBook S15 X530UN         | Notebook    | [64e65fe674](https://linux-hardware.org/?probe=64e65fe674) | Aug 11, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [bc44361c47](https://linux-hardware.org/?probe=bc44361c47) | Aug 02, 2020 |
| ASUSTek       | H110M-D                     | Desktop     | [e8cc620228](https://linux-hardware.org/?probe=e8cc620228) | Aug 02, 2020 |
| Unknown       | Unknown                     | Phone       | [38378b572a](https://linux-hardware.org/?probe=38378b572a) | Aug 01, 2020 |
| HP            | Presario CQ43               | Notebook    | [df780756ee](https://linux-hardware.org/?probe=df780756ee) | Jul 31, 2020 |
| HP            | Presario CQ43               | Notebook    | [102ab797a7](https://linux-hardware.org/?probe=102ab797a7) | Jul 31, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f99c1674c](https://linux-hardware.org/?probe=3f99c1674c) | Jul 30, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [dbbc5219fd](https://linux-hardware.org/?probe=dbbc5219fd) | Jul 27, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [c85ae35bff](https://linux-hardware.org/?probe=c85ae35bff) | Jul 25, 2020 |
| Dell          | Latitude 7285               | Tablet      | [ed3aa05fd5](https://linux-hardware.org/?probe=ed3aa05fd5) | Jul 25, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [81e5774167](https://linux-hardware.org/?probe=81e5774167) | Jul 24, 2020 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [1856c4ccbf](https://linux-hardware.org/?probe=1856c4ccbf) | Jul 23, 2020 |
| Dell          | Latitude 7480               | Notebook    | [7fa880215f](https://linux-hardware.org/?probe=7fa880215f) | Jul 21, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2bfaffc9c5](https://linux-hardware.org/?probe=2bfaffc9c5) | Jul 21, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [7b83e5785f](https://linux-hardware.org/?probe=7b83e5785f) | Jul 19, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [d45acf2543](https://linux-hardware.org/?probe=d45acf2543) | Jul 18, 2020 |
| Unknown       | Unknown                     | Phone       | [c0d8474803](https://linux-hardware.org/?probe=c0d8474803) | Jul 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [4b144fb616](https://linux-hardware.org/?probe=4b144fb616) | Jul 14, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7d9a43933e](https://linux-hardware.org/?probe=7d9a43933e) | Jul 14, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [48cdbb3d36](https://linux-hardware.org/?probe=48cdbb3d36) | Jul 11, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [f5ff1447a7](https://linux-hardware.org/?probe=f5ff1447a7) | Jul 08, 2020 |
| Biostar       | H81MHV3                     | Desktop     | [a97a2e14e2](https://linux-hardware.org/?probe=a97a2e14e2) | Jul 06, 2020 |
| ILLEGEAR      | RAVEN SE                    | Notebook    | [0aa18d5241](https://linux-hardware.org/?probe=0aa18d5241) | Jul 05, 2020 |
| Dell          | Latitude E6440              | Notebook    | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5d32eb1d75](https://linux-hardware.org/?probe=5d32eb1d75) | Jun 30, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [33534eca13](https://linux-hardware.org/?probe=33534eca13) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6ae79e439f](https://linux-hardware.org/?probe=6ae79e439f) | Jun 28, 2020 |
| Acer          | Aspire 4738                 | Notebook    | [519a7577c0](https://linux-hardware.org/?probe=519a7577c0) | Jun 28, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [0cd3f983c9](https://linux-hardware.org/?probe=0cd3f983c9) | Jun 26, 2020 |
| Acer          | Aspire 4730Z                | Notebook    | [bad4de6363](https://linux-hardware.org/?probe=bad4de6363) | Jun 26, 2020 |
| Dell          | Latitude E6440              | Notebook    | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4833031b9b](https://linux-hardware.org/?probe=4833031b9b) | Jun 23, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [99ff555015](https://linux-hardware.org/?probe=99ff555015) | Jun 21, 2020 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [05556ef252](https://linux-hardware.org/?probe=05556ef252) | Jun 19, 2020 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0a15b3f355](https://linux-hardware.org/?probe=0a15b3f355) | Jun 18, 2020 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [eac1260628](https://linux-hardware.org/?probe=eac1260628) | Jun 17, 2020 |
| Unknown       | Unknown                     | Phone       | [6566b884d6](https://linux-hardware.org/?probe=6566b884d6) | Jun 15, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [3ab69ab51e](https://linux-hardware.org/?probe=3ab69ab51e) | Jun 10, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [ba4a677fab](https://linux-hardware.org/?probe=ba4a677fab) | Jun 10, 2020 |
| HP            | 14                          | Notebook    | [5a36b38b50](https://linux-hardware.org/?probe=5a36b38b50) | Jun 07, 2020 |
| Fujitsu       | LIFEBOOK S761               | Notebook    | [7d4e0682de](https://linux-hardware.org/?probe=7d4e0682de) | Jun 07, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [6c1d889b0d](https://linux-hardware.org/?probe=6c1d889b0d) | Jun 06, 2020 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [709dcae624](https://linux-hardware.org/?probe=709dcae624) | Jun 06, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [11c6b72a1b](https://linux-hardware.org/?probe=11c6b72a1b) | Jun 03, 2020 |
| MSI           | A320M-A PRO MAX             | Desktop     | [ecf8e72f94](https://linux-hardware.org/?probe=ecf8e72f94) | May 31, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [b335d617f7](https://linux-hardware.org/?probe=b335d617f7) | May 26, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [865933043f](https://linux-hardware.org/?probe=865933043f) | May 26, 2020 |
| Acer          | EQ45M                       | Desktop     | [a682473a39](https://linux-hardware.org/?probe=a682473a39) | May 23, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d2113ac640](https://linux-hardware.org/?probe=d2113ac640) | May 21, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [1882c535de](https://linux-hardware.org/?probe=1882c535de) | May 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [445fc4fef9](https://linux-hardware.org/?probe=445fc4fef9) | May 19, 2020 |
| Dell          | 0PU052                      | Desktop     | [40ab4a84b5](https://linux-hardware.org/?probe=40ab4a84b5) | May 18, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8156a3eef6](https://linux-hardware.org/?probe=8156a3eef6) | May 11, 2020 |
| SNS Networ... | JOI Book 150                | Notebook    | [3d61c3722c](https://linux-hardware.org/?probe=3d61c3722c) | May 11, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [f92d9768ce](https://linux-hardware.org/?probe=f92d9768ce) | May 07, 2020 |
| Sony          | VPCSB26FG                   | Notebook    | [b119ccc5f2](https://linux-hardware.org/?probe=b119ccc5f2) | May 07, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4893a0cfcd](https://linux-hardware.org/?probe=4893a0cfcd) | May 06, 2020 |
| Dell          | 0RY007                      | Desktop     | [4d44e2723d](https://linux-hardware.org/?probe=4d44e2723d) | May 04, 2020 |
| HP            | 14                          | Notebook    | [c0318bc179](https://linux-hardware.org/?probe=c0318bc179) | Apr 30, 2020 |
| Acer          | EQ45M                       | Desktop     | [03e154e2dc](https://linux-hardware.org/?probe=03e154e2dc) | Apr 21, 2020 |
| Dell          | 0C3YXR A01                  | Desktop     | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| BUSH          | Windows tablet              | Notebook    | [a25abad9de](https://linux-hardware.org/?probe=a25abad9de) | Apr 18, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [9c68002e3d](https://linux-hardware.org/?probe=9c68002e3d) | Apr 13, 2020 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [0444963962](https://linux-hardware.org/?probe=0444963962) | Apr 12, 2020 |
| MSI           | B150M Night Elf             | Desktop     | [01013b611d](https://linux-hardware.org/?probe=01013b611d) | Apr 11, 2020 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [1211d7770c](https://linux-hardware.org/?probe=1211d7770c) | Mar 15, 2020 |
| Acer          | TM4750                      | Notebook    | [bedf724360](https://linux-hardware.org/?probe=bedf724360) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [db9b7453f2](https://linux-hardware.org/?probe=db9b7453f2) | Mar 11, 2020 |
| Acer          | TM4750                      | Notebook    | [69bbe5f0ee](https://linux-hardware.org/?probe=69bbe5f0ee) | Mar 11, 2020 |
| Dell          | Inspiron 1464               | Notebook    | [d6a38ddcea](https://linux-hardware.org/?probe=d6a38ddcea) | Mar 08, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [46ad418d75](https://linux-hardware.org/?probe=46ad418d75) | Feb 24, 2020 |
| Dell          | 0JWGHC A01                  | All in one  | [c1b65d99ff](https://linux-hardware.org/?probe=c1b65d99ff) | Feb 23, 2020 |
| Teclast       | F5                          | Convertible | [23690a5a6e](https://linux-hardware.org/?probe=23690a5a6e) | Feb 16, 2020 |
| Acer          | Aspire 4736Z                | Notebook    | [a6e2ff9c02](https://linux-hardware.org/?probe=a6e2ff9c02) | Feb 15, 2020 |
| ASUSTek       | P6T SE                      | Desktop     | [05737b4c23](https://linux-hardware.org/?probe=05737b4c23) | Feb 11, 2020 |
| HP            | 3647h                       | Desktop     | [06df72e240](https://linux-hardware.org/?probe=06df72e240) | Feb 08, 2020 |
| HP            | ProBook 645 G1              | Notebook    | [18fb680615](https://linux-hardware.org/?probe=18fb680615) | Feb 04, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [5ab23205d8](https://linux-hardware.org/?probe=5ab23205d8) | Jan 21, 2020 |
| ASUSTek       | P8Z77-M                     | Desktop     | [9247337003](https://linux-hardware.org/?probe=9247337003) | Jan 20, 2020 |
| Apple         | MacBookPro8,2               | Notebook    | [1b04478121](https://linux-hardware.org/?probe=1b04478121) | Jan 14, 2020 |
| Chuwi         | LapBook Pro                 | Notebook    | [f9d248ac7c](https://linux-hardware.org/?probe=f9d248ac7c) | Jan 03, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3b64de1ec8](https://linux-hardware.org/?probe=3b64de1ec8) | Dec 31, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [31643f4ace](https://linux-hardware.org/?probe=31643f4ace) | Dec 31, 2019 |
| Lenovo        | G500s 20245                 | Notebook    | [82346138d0](https://linux-hardware.org/?probe=82346138d0) | Dec 30, 2019 |
| HP            | ProBook 4545s               | Notebook    | [66e278f8a6](https://linux-hardware.org/?probe=66e278f8a6) | Dec 29, 2019 |
| HP            | ProBook 4545s               | Notebook    | [7c1a6a786f](https://linux-hardware.org/?probe=7c1a6a786f) | Dec 29, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [02d013ad00](https://linux-hardware.org/?probe=02d013ad00) | Dec 20, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c0c7973b78](https://linux-hardware.org/?probe=c0c7973b78) | Nov 20, 2019 |
| Supermicro    | K1SPE-IN001                 | Server      | [5f6d0233a8](https://linux-hardware.org/?probe=5f6d0233a8) | Nov 18, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [9e78c03471](https://linux-hardware.org/?probe=9e78c03471) | Nov 17, 2019 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [875f14ed53](https://linux-hardware.org/?probe=875f14ed53) | Nov 13, 2019 |
| Dell          | Vostro V130                 | Notebook    | [ca716fdbad](https://linux-hardware.org/?probe=ca716fdbad) | Nov 09, 2019 |
| Dell          | Vostro V130                 | Notebook    | [0ba8558483](https://linux-hardware.org/?probe=0ba8558483) | Nov 08, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [7ce70fa206](https://linux-hardware.org/?probe=7ce70fa206) | Oct 25, 2019 |
| Acer          | Swift SF314-55G             | Notebook    | [8526e89541](https://linux-hardware.org/?probe=8526e89541) | Oct 16, 2019 |
| ASUSTek       | X456URK                     | Notebook    | [03b7432783](https://linux-hardware.org/?probe=03b7432783) | Oct 10, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [b37e090603](https://linux-hardware.org/?probe=b37e090603) | Oct 06, 2019 |
| HP            | 0AA8h                       | Desktop     | [a60543a450](https://linux-hardware.org/?probe=a60543a450) | Sep 07, 2019 |
| HP            | ZBook 15                    | Notebook    | [f9aaccbfe0](https://linux-hardware.org/?probe=f9aaccbfe0) | Sep 06, 2019 |
| Dell          | Latitude E7440              | Notebook    | [04bd492077](https://linux-hardware.org/?probe=04bd492077) | Sep 06, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [ae117eb491](https://linux-hardware.org/?probe=ae117eb491) | Sep 03, 2019 |
| Dell          | 0RY007                      | Desktop     | [576ec7dcd0](https://linux-hardware.org/?probe=576ec7dcd0) | Aug 22, 2019 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [d9d789a4f2](https://linux-hardware.org/?probe=d9d789a4f2) | Aug 21, 2019 |
| MSI           | GP70 2PE                    | Notebook    | [3442bbe40c](https://linux-hardware.org/?probe=3442bbe40c) | Aug 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [f8d49fa793](https://linux-hardware.org/?probe=f8d49fa793) | Aug 03, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [46b9ff1fff](https://linux-hardware.org/?probe=46b9ff1fff) | Aug 03, 2019 |
| ASUSTek       | P6T SE                      | Desktop     | [a91c21a426](https://linux-hardware.org/?probe=a91c21a426) | Aug 02, 2019 |
| HP            | ProLiant DL60 Gen9          | Server      | [140daf886e](https://linux-hardware.org/?probe=140daf886e) | Jul 24, 2019 |
| ASUSTek       | H81M-C                      | Desktop     | [38a96dff85](https://linux-hardware.org/?probe=38a96dff85) | Jul 02, 2019 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [62b0b05a66](https://linux-hardware.org/?probe=62b0b05a66) | Jul 01, 2019 |
| ASUSTek       | X450CP                      | Notebook    | [2931234c98](https://linux-hardware.org/?probe=2931234c98) | May 02, 2019 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c7b00947af](https://linux-hardware.org/?probe=c7b00947af) | Apr 30, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [35e3cab7fd](https://linux-hardware.org/?probe=35e3cab7fd) | Apr 24, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3783735e9b](https://linux-hardware.org/?probe=3783735e9b) | Apr 23, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [672cf7aa7f](https://linux-hardware.org/?probe=672cf7aa7f) | Apr 20, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [5202aae85e](https://linux-hardware.org/?probe=5202aae85e) | Feb 26, 2019 |
| ASUSTek       | X101H                       | Notebook    | [bfa018d76d](https://linux-hardware.org/?probe=bfa018d76d) | Jan 21, 2019 |
| ASUSTek       | X550DP                      | Notebook    | [323f6e2eeb](https://linux-hardware.org/?probe=323f6e2eeb) | Dec 17, 2018 |
| ASRock        | X79 Extreme9                | Desktop     | [c96c05c47b](https://linux-hardware.org/?probe=c96c05c47b) | Nov 30, 2018 |
| Dell          | XPS L521X                   | Notebook    | [3f3c8f2571](https://linux-hardware.org/?probe=3f3c8f2571) | Nov 25, 2018 |
| Dell          | Latitude E6520              | Notebook    | [166d529d12](https://linux-hardware.org/?probe=166d529d12) | Nov 12, 2018 |
| HP            | 2820h                       | Desktop     | [1f42af0283](https://linux-hardware.org/?probe=1f42af0283) | Dec 17, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [8381b26177](https://linux-hardware.org/?probe=8381b26177) | Jan 27, 2017 |
| Dell          | XPS L412Z                   | Notebook    | [799ee32fce](https://linux-hardware.org/?probe=799ee32fce) | Jan 21, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Malaysia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 60        | 14.49%  |
| Ubuntu 18.04        | 24        | 5.8%    |
| Ubuntu 22.04        | 18        | 4.35%   |
| Debian 11           | 14        | 3.38%   |
| OpenMandriva 4.2    | 11        | 2.66%   |
| Zorin 16            | 10        | 2.42%   |
| Pop!_OS 20.10       | 10        | 2.42%   |
| OpenMandriva 4.3    | 10        | 2.42%   |
| Pop!_OS 21.04       | 9         | 2.17%   |
| OpenMandriva 4.50   | 9         | 2.17%   |
| OpenMandriva 23.01  | 9         | 2.17%   |
| KDE neon 20.04      | 9         | 2.17%   |
| Pop!_OS 22.04       | 8         | 1.93%   |
| Pop!_OS 20.04       | 8         | 1.93%   |
| Fedora 33           | 8         | 1.93%   |
| ArcoLinux Rolling   | 8         | 1.93%   |
| Ubuntu 19.04        | 7         | 1.69%   |
| Linux Mint 19.3     | 6         | 1.45%   |
| Fedora 34           | 6         | 1.45%   |
| Fedora 37           | 5         | 1.21%   |
| Arch                | 5         | 1.21%   |
| Zorin 15            | 4         | 0.97%   |
| Ubuntu 21.04        | 4         | 0.97%   |
| Ubuntu 20.10        | 4         | 0.97%   |
| Ubuntu 19.10        | 4         | 0.97%   |
| Ubuntu 16.04        | 4         | 0.97%   |
| Manjaro             | 4         | 0.97%   |
| Linux Mint 21.1     | 4         | 0.97%   |
| Linux Mint 20.2     | 4         | 0.97%   |
| EndeavourOS Rolling | 4         | 0.97%   |
| Elementary 6.1      | 4         | 0.97%   |
| Elementary 5.1.7    | 4         | 0.97%   |
| Xubuntu 22.04       | 3         | 0.72%   |
| Xubuntu 18.04       | 3         | 0.72%   |
| Ubuntu 21.10        | 3         | 0.72%   |
| Linux Mint 20.1     | 3         | 0.72%   |
| KDE neon 22.04      | 3         | 0.72%   |
| Arch Rolling        | 3         | 0.72%   |
| Android             | 3         | 0.72%   |
| Ubuntu Unity 16.04  | 2         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu            | 125       | 31.73%  |
| OpenMandriva      | 36        | 9.14%   |
| Pop!_OS           | 33        | 8.38%   |
| Fedora            | 24        | 6.09%   |
| Linux Mint        | 21        | 5.33%   |
| Debian            | 16        | 4.06%   |
| Zorin             | 15        | 3.81%   |
| Manjaro           | 13        | 3.3%    |
| KDE neon          | 13        | 3.3%    |
| Elementary        | 11        | 2.79%   |
| Endless           | 8         | 2.03%   |
| ArcoLinux         | 8         | 2.03%   |
| Arch              | 8         | 2.03%   |
| Xubuntu           | 7         | 1.78%   |
| Lubuntu           | 7         | 1.78%   |
| Kubuntu           | 5         | 1.27%   |
| Kali              | 5         | 1.27%   |
| EndeavourOS       | 5         | 1.27%   |
| CentOS            | 4         | 1.02%   |
| SteamOS           | 3         | 0.76%   |
| Android           | 3         | 0.76%   |
| Ubuntu Unity      | 2         | 0.51%   |
| Ubuntu MATE       | 2         | 0.51%   |
| Ubuntu Budgie     | 2         | 0.51%   |
| ROSA              | 2         | 0.51%   |
| openSUSE          | 2         | 0.51%   |
| Gentoo            | 2         | 0.51%   |
| Xero              | 1         | 0.25%   |
| Ultramarine Linux | 1         | 0.25%   |
| Rocky Linux       | 1         | 0.25%   |
| Reborn OS         | 1         | 0.25%   |
| Raspbian          | 1         | 0.25%   |
| Peppermint        | 1         | 0.25%   |
| MX                | 1         | 0.25%   |
| LMDE              | 1         | 0.25%   |
| Linux Lite        | 1         | 0.25%   |
| BuildRoot         | 1         | 0.25%   |
| Axyl              | 1         | 0.25%   |
| Archcraft         | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 10        | 2.26%   |
| 5.4.0-58-generic         | 8         | 1.81%   |
| 5.4.0-42-generic         | 8         | 1.81%   |
| 5.16.7-desktop-1omv4003  | 8         | 1.81%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.36%   |
| 5.15.0-58-generic        | 6         | 1.36%   |
| 5.15.0-52-generic        | 6         | 1.36%   |
| 5.13.19-6-pve            | 6         | 1.36%   |
| 5.11.0-7620-generic      | 6         | 1.36%   |
| 5.12.4-desktop-1omv4050  | 5         | 1.13%   |
| 5.11.0-27-generic        | 5         | 1.13%   |
| 5.4.0-7634-generic       | 4         | 0.9%    |
| 5.4.0-40-generic         | 4         | 0.9%    |
| 5.15.0-56-generic        | 4         | 0.9%    |
| 5.0.0-37-generic         | 4         | 0.9%    |
| 6.0.12-76060006-generic  | 3         | 0.68%   |
| 5.8.0-7642-generic       | 3         | 0.68%   |
| 5.8.0-7630-generic       | 3         | 0.68%   |
| 5.4.0-54-generic         | 3         | 0.68%   |
| 5.4.0-52-generic         | 3         | 0.68%   |
| 5.4.0-48-generic         | 3         | 0.68%   |
| 5.4.0-37-generic         | 3         | 0.68%   |
| 5.3.0-53-generic         | 3         | 0.68%   |
| 5.3.0-46-generic         | 3         | 0.68%   |
| 5.19.0-32-generic        | 3         | 0.68%   |
| 5.16.3-desktop-2omv4050  | 3         | 0.68%   |
| 5.15.0-46-generic        | 3         | 0.68%   |
| 5.15.0-40-generic        | 3         | 0.68%   |
| 5.15.0-39-generic        | 3         | 0.68%   |
| 5.15.0-25-generic        | 3         | 0.68%   |
| 5.13.0-7614-generic      | 3         | 0.68%   |
| 5.13.0-22-generic        | 3         | 0.68%   |
| 5.11.0-7614-generic      | 3         | 0.68%   |
| 5.11.0-46-generic        | 3         | 0.68%   |
| 5.11.0-43-generic        | 3         | 0.68%   |
| 5.11.0-34-generic        | 3         | 0.68%   |
| 5.0.0-32-generic         | 3         | 0.68%   |
| 5.0.0-25-generic         | 3         | 0.68%   |
| 5.0.0-23-generic         | 3         | 0.68%   |
| 4.15.0-76-generic        | 3         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 68        | 16.23%  |
| 5.15.0  | 34        | 8.11%   |
| 5.11.0  | 30        | 7.16%   |
| 5.8.0   | 26        | 6.21%   |
| 4.15.0  | 20        | 4.77%   |
| 5.3.0   | 19        | 4.53%   |
| 5.13.0  | 19        | 4.53%   |
| 5.0.0   | 18        | 4.3%    |
| 5.10.14 | 10        | 2.39%   |
| 5.19.0  | 8         | 1.91%   |
| 5.16.7  | 8         | 1.91%   |
| 6.1.1   | 7         | 1.67%   |
| 5.10.0  | 7         | 1.67%   |
| 5.13.19 | 6         | 1.43%   |
| 4.18.0  | 6         | 1.43%   |
| 5.17.1  | 5         | 1.19%   |
| 5.12.4  | 5         | 1.19%   |
| 6.0.12  | 4         | 0.95%   |
| 5.18.0  | 4         | 0.95%   |
| 5.9.0   | 3         | 0.72%   |
| 5.16.3  | 3         | 0.72%   |
| 5.16.15 | 3         | 0.72%   |
| 6.1.4   | 2         | 0.48%   |
| 5.9.1   | 2         | 0.48%   |
| 5.19.9  | 2         | 0.48%   |
| 5.19.12 | 2         | 0.48%   |
| 5.17.6  | 2         | 0.48%   |
| 5.17.5  | 2         | 0.48%   |
| 5.15.35 | 2         | 0.48%   |
| 5.14.18 | 2         | 0.48%   |
| 5.14.0  | 2         | 0.48%   |
| 5.13.13 | 2         | 0.48%   |
| 5.12.9  | 2         | 0.48%   |
| 5.12.7  | 2         | 0.48%   |
| 5.12.15 | 2         | 0.48%   |
| 5.11.18 | 2         | 0.48%   |
| 5.10.79 | 2         | 0.48%   |
| 5.10.42 | 2         | 0.48%   |
| 5.10.13 | 2         | 0.48%   |
| 4.4.0   | 2         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 16.43%  |
| 5.15    | 46        | 11.11%  |
| 5.11    | 35        | 8.45%   |
| 5.8     | 33        | 7.97%   |
| 5.13    | 28        | 6.76%   |
| 5.10    | 27        | 6.52%   |
| 4.15    | 20        | 4.83%   |
| 5.3     | 19        | 4.59%   |
| 5.0     | 18        | 4.35%   |
| 5.16    | 16        | 3.86%   |
| 5.19    | 15        | 3.62%   |
| 5.12    | 13        | 3.14%   |
| 6.1     | 11        | 2.66%   |
| 5.18    | 9         | 2.17%   |
| 5.17    | 9         | 2.17%   |
| 6.0     | 8         | 1.93%   |
| 5.9     | 8         | 1.93%   |
| 5.14    | 8         | 1.93%   |
| 4.18    | 6         | 1.45%   |
| 3.10    | 3         | 0.72%   |
| 6.2     | 2         | 0.48%   |
| 5.7     | 2         | 0.48%   |
| 5.6     | 2         | 0.48%   |
| 4.4     | 2         | 0.48%   |
| 3.18    | 2         | 0.48%   |
| 4.9     | 1         | 0.24%   |
| 4.19    | 1         | 0.24%   |
| 4.10    | 1         | 0.24%   |
| 4.1     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 365       | 97.33%  |
| i686   | 5         | 1.33%   |
| armv8l | 3         | 0.8%    |
| armv7l | 2         | 0.53%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 176       | 44.78%  |
| KDE5          | 70        | 17.81%  |
| Unknown       | 40        | 10.18%  |
| XFCE          | 25        | 6.36%   |
| X-Cinnamon    | 18        | 4.58%   |
| KDE           | 13        | 3.31%   |
| Pantheon      | 11        | 2.8%    |
| Openbox       | 11        | 2.8%    |
| MATE          | 10        | 2.54%   |
| LXQt          | 6         | 1.53%   |
| Unity         | 2         | 0.51%   |
| LXDE          | 2         | 0.51%   |
| GNOME Classic | 2         | 0.51%   |
| Budgie        | 2         | 0.51%   |
| Peppermint    | 1         | 0.25%   |
| i3            | 1         | 0.25%   |
| Hyprland      | 1         | 0.25%   |
| Cinnamon      | 1         | 0.25%   |
| bspwm         | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 306       | 78.66%  |
| Wayland | 52        | 13.37%  |
| Unknown | 20        | 5.14%   |
| Tty     | 11        | 2.83%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 213       | 55.04%  |
| SDDM    | 67        | 17.31%  |
| GDM3    | 36        | 9.3%    |
| GDM     | 34        | 8.79%   |
| LightDM | 30        | 7.75%   |
| TDM     | 5         | 1.29%   |
| LXDM    | 2         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 293       | 76.9%   |
| Unknown | 31        | 8.14%   |
| en_GB   | 27        | 7.09%   |
| en_SG   | 15        | 3.94%   |
| en_AU   | 3         | 0.79%   |
| C       | 3         | 0.79%   |
| zh_CN   | 2         | 0.52%   |
| ms_MY   | 2         | 0.52%   |
| en_MY   | 2         | 0.52%   |
| ja_JP   | 1         | 0.26%   |
| id_ID   | 1         | 0.26%   |
| en_HK   | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 204       | 53.54%  |
| EFI  | 177       | 46.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 285       | 74.41%  |
| Overlay | 32        | 8.36%   |
| Btrfs   | 29        | 7.57%   |
| Zfs     | 13        | 3.39%   |
| Unknown | 12        | 3.13%   |
| Xfs     | 9         | 2.35%   |
| Ext2    | 2         | 0.52%   |
| Ext3    | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 222       | 57.81%  |
| GPT     | 113       | 29.43%  |
| MBR     | 49        | 12.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 309       | 80.47%  |
| Yes       | 75        | 19.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 259       | 67.62%  |
| Yes       | 124       | 32.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 71        | 18.93%  |
| Dell                    | 67        | 17.87%  |
| Hewlett-Packard         | 49        | 13.07%  |
| Lenovo                  | 35        | 9.33%   |
| Gigabyte Technology     | 29        | 7.73%   |
| MSI                     | 23        | 6.13%   |
| Acer                    | 22        | 5.87%   |
| Intel                   | 15        | 4%      |
| Apple                   | 8         | 2.13%   |
| ASRock                  | 6         | 1.6%    |
| Unknown                 | 6         | 1.6%    |
| Biostar                 | 5         | 1.33%   |
| Sony                    | 4         | 1.07%   |
| Fujitsu                 | 3         | 0.8%    |
| Samsung Electronics     | 2         | 0.53%   |
| Raspberry Pi Foundation | 2         | 0.53%   |
| ILLEGEAR                | 2         | 0.53%   |
| HUAWEI                  | 2         | 0.53%   |
| ECS                     | 2         | 0.53%   |
| Acidanthera             | 2         | 0.53%   |
| Vorke                   | 1         | 0.27%   |
| Valve                   | 1         | 0.27%   |
| Toshiba                 | 1         | 0.27%   |
| Timi                    | 1         | 0.27%   |
| Teclast                 | 1         | 0.27%   |
| System76                | 1         | 0.27%   |
| Supermicro              | 1         | 0.27%   |
| SNS Network (M)         | 1         | 0.27%   |
| Shuttle                 | 1         | 0.27%   |
| Seco                    | 1         | 0.27%   |
| ONDA                    | 1         | 0.27%   |
| NEC Computers           | 1         | 0.27%   |
| HONOR                   | 1         | 0.27%   |
| GPD                     | 1         | 0.27%   |
| Chuwi                   | 1         | 0.27%   |
| BUSH                    | 1         | 0.27%   |
| AZW                     | 1         | 0.27%   |
| ASRockRack              | 1         | 0.27%   |
| AMI                     | 1         | 0.27%   |
| Alienware               | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel DH61WW AAG23116-204         | 7         | 1.87%   |
| ASUS All Series                   | 7         | 1.87%   |
| Unknown                           | 6         | 1.6%    |
| Gigabyte B85M-D3H                 | 5         | 1.33%   |
| MSI MS-7C52                       | 4         | 1.07%   |
| HP Notebook                       | 4         | 1.07%   |
| MSI MS-7817                       | 3         | 0.8%    |
| Intel DH61WW AAG23116-300         | 3         | 0.8%    |
| Dell OptiPlex 755                 | 3         | 0.8%    |
| MSI MS-7C81                       | 2         | 0.53%   |
| MSI MS-7B89                       | 2         | 0.53%   |
| MSI Modern 14 B5M                 | 2         | 0.53%   |
| Intel MAHOBAY                     | 2         | 0.53%   |
| HP Pavilion dv6                   | 2         | 0.53%   |
| HP Laptop 15-bs0xx                | 2         | 0.53%   |
| HP ENVY 4                         | 2         | 0.53%   |
| HP EliteBook 8470p                | 2         | 0.53%   |
| HP EliteBook 840 G2               | 2         | 0.53%   |
| HP Compaq Presario CQ40           | 2         | 0.53%   |
| Gigabyte X570 UD                  | 2         | 0.53%   |
| Gigabyte B450M S2H                | 2         | 0.53%   |
| Dell XPS 8940                     | 2         | 0.53%   |
| Dell XPS 15 7590                  | 2         | 0.53%   |
| Dell OptiPlex 990                 | 2         | 0.53%   |
| Dell Latitude E6520               | 2         | 0.53%   |
| Dell Latitude E6440               | 2         | 0.53%   |
| Dell Latitude 3410                | 2         | 0.53%   |
| Biostar G41D3C                    | 2         | 0.53%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI   | 2         | 0.53%   |
| ASUS P8Z77-V LX                   | 2         | 0.53%   |
| ASUS K45VD                        | 2         | 0.53%   |
| ASUS K43SD                        | 2         | 0.53%   |
| Apple MacBookPro8,1               | 2         | 0.53%   |
| Vorke V1 Plus                     | 1         | 0.27%   |
| Valve Jupiter                     | 1         | 0.27%   |
| Toshiba dynabook Satellite B552/H | 1         | 0.27%   |
| Timi RedmiBook 14 II              | 1         | 0.27%   |
| Teclast F5                        | 1         | 0.27%   |
| System76 Galago Pro               | 1         | 0.27%   |
| Supermicro PIO-5038K-I-IN001      | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Latitude       | 20        | 5.33%   |
| Dell Inspiron       | 18        | 4.8%    |
| Lenovo ThinkPad     | 16        | 4.27%   |
| Acer Aspire         | 13        | 3.47%   |
| Intel DH61WW        | 10        | 2.67%   |
| Dell OptiPlex       | 10        | 2.67%   |
| HP Pavilion         | 8         | 2.13%   |
| HP Compaq           | 8         | 2.13%   |
| Dell XPS            | 8         | 2.13%   |
| HP EliteBook        | 7         | 1.87%   |
| Dell Precision      | 7         | 1.87%   |
| ASUS All            | 7         | 1.87%   |
| Unknown             | 6         | 1.6%    |
| HP Laptop           | 5         | 1.33%   |
| Gigabyte B85M-D3H   | 5         | 1.33%   |
| ASUS ROG            | 5         | 1.33%   |
| MSI MS-7C52         | 4         | 1.07%   |
| HP Notebook         | 4         | 1.07%   |
| Gigabyte X570       | 4         | 1.07%   |
| ASUS VivoBook       | 4         | 1.07%   |
| ASUS TUF            | 4         | 1.07%   |
| MSI MS-7817         | 3         | 0.8%    |
| Lenovo ThinkStation | 3         | 0.8%    |
| Lenovo ThinkCentre  | 3         | 0.8%    |
| Lenovo IdeaPad      | 3         | 0.8%    |
| Gigabyte B450M      | 3         | 0.8%    |
| Fujitsu LIFEBOOK    | 3         | 0.8%    |
| ASUS P8B75-M        | 3         | 0.8%    |
| Apple MacBookPro8   | 3         | 0.8%    |
| RPi Raspberry       | 2         | 0.53%   |
| MSI MS-7C81         | 2         | 0.53%   |
| MSI MS-7B89         | 2         | 0.53%   |
| MSI Modern          | 2         | 0.53%   |
| Lenovo Yoga         | 2         | 0.53%   |
| Intel MAHOBAY       | 2         | 0.53%   |
| HP ProLiant         | 2         | 0.53%   |
| HP ProBook          | 2         | 0.53%   |
| HP ENVY             | 2         | 0.53%   |
| Biostar G41D3C      | 2         | 0.53%   |
| ASUS ZenBook        | 2         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 42        | 11.2%   |
| 2013    | 39        | 10.4%   |
| 2019    | 38        | 10.13%  |
| 2018    | 33        | 8.8%    |
| 2020    | 30        | 8%      |
| 2012    | 30        | 8%      |
| 2021    | 27        | 7.2%    |
| 2015    | 22        | 5.87%   |
| 2017    | 21        | 5.6%    |
| 2010    | 20        | 5.33%   |
| 2008    | 15        | 4%      |
| 2014    | 14        | 3.73%   |
| 2009    | 12        | 3.2%    |
| 2016    | 10        | 2.67%   |
| 2007    | 10        | 2.67%   |
| 2022    | 7         | 1.87%   |
| Unknown | 4         | 1.07%   |
| 2006    | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 194       | 51.73%  |
| Desktop        | 148       | 39.47%  |
| Convertible    | 9         | 2.4%    |
| All in one     | 7         | 1.87%   |
| Server         | 5         | 1.33%   |
| Tablet         | 4         | 1.07%   |
| Phone          | 3         | 0.8%    |
| Mini pc        | 3         | 0.8%    |
| System on chip | 2         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 351       | 93.6%   |
| Enabled  | 24        | 6.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 373       | 99.47%  |
| Yes  | 2         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 86        | 22.69%  |
| 3.01-4.0    | 75        | 19.79%  |
| 8.01-16.0   | 74        | 19.53%  |
| 16.01-24.0  | 69        | 18.21%  |
| 32.01-64.0  | 30        | 7.92%   |
| 1.01-2.0    | 17        | 4.49%   |
| 64.01-256.0 | 14        | 3.69%   |
| 2.01-3.0    | 7         | 1.85%   |
| 24.01-32.0  | 5         | 1.32%   |
| 0.51-1.0    | 2         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 136       | 32.46%  |
| 2.01-3.0    | 121       | 28.88%  |
| 3.01-4.0    | 63        | 15.04%  |
| 4.01-8.0    | 42        | 10.02%  |
| 0.51-1.0    | 29        | 6.92%   |
| 8.01-16.0   | 14        | 3.34%   |
| 32.01-64.0  | 4         | 0.95%   |
| 0.01-0.5    | 4         | 0.95%   |
| 24.01-32.0  | 2         | 0.48%   |
| 64.01-256.0 | 2         | 0.48%   |
| 16.01-24.0  | 1         | 0.24%   |
| Unknown     | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 209       | 54.29%  |
| 2      | 106       | 27.53%  |
| 3      | 31        | 8.05%   |
| 4      | 16        | 4.16%   |
| 5      | 9         | 2.34%   |
| 7      | 6         | 1.56%   |
| 8      | 4         | 1.04%   |
| 6      | 4         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 245       | 64.99%  |
| Yes       | 132       | 35.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 318       | 84.8%   |
| No        | 57        | 15.2%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 305       | 80.69%  |
| No        | 73        | 19.31%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 62.07%  |
| No        | 143       | 37.93%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Malaysia | 375       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Kuala Lumpur           | 138       | 34.24%  |
| Petaling Jaya          | 45        | 11.17%  |
| Shah Alam              | 16        | 3.97%   |
| Johor Bahru            | 15        | 3.72%   |
| Puchong Batu Dua Belas | 14        | 3.47%   |
| Subang Jaya            | 11        | 2.73%   |
| George Town            | 11        | 2.73%   |
| Sungai Buloh           | 9         | 2.23%   |
| Kota Kinabalu          | 9         | 2.23%   |
| Kota Bharu             | 9         | 2.23%   |
| Ipoh                   | 9         | 2.23%   |
| Seremban               | 8         | 1.99%   |
| Malacca                | 8         | 1.99%   |
| Kajang                 | 7         | 1.74%   |
| Kulim                  | 5         | 1.24%   |
| Kuching                | 5         | 1.24%   |
| Tawau                  | 4         | 0.99%   |
| Skudai                 | 4         | 0.99%   |
| Marabu                 | 4         | 0.99%   |
| Kulai                  | 4         | 0.99%   |
| Klang                  | 4         | 0.99%   |
| Cyberjaya              | 4         | 0.99%   |
| Butterworth            | 4         | 0.99%   |
| Ampang                 | 4         | 0.99%   |
| Sungai Petani          | 3         | 0.74%   |
| Seri Kembangan         | 3         | 0.74%   |
| Putrajaya              | 3         | 0.74%   |
| Cheras                 | 3         | 0.74%   |
| Bayan Lepas            | 3         | 0.74%   |
| Rawang                 | 2         | 0.5%    |
| Nibong Tebal           | 2         | 0.5%    |
| Long Seridan           | 2         | 0.5%    |
| Bukit Mertajam         | 2         | 0.5%    |
| Ayer Itam              | 2         | 0.5%    |
| Alor Star              | 2         | 0.5%    |
| Taiping                | 1         | 0.25%   |
| Sibu                   | 1         | 0.25%   |
| Sepang                 | 1         | 0.25%   |
| Semenyih               | 1         | 0.25%   |
| Perai                  | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 109       | 163    | 18.02%  |
| WDC                         | 91        | 154    | 15.04%  |
| Kingston                    | 50        | 68     | 8.26%   |
| Samsung Electronics         | 47        | 69     | 7.77%   |
| Toshiba                     | 44        | 52     | 7.27%   |
| SanDisk                     | 25        | 34     | 4.13%   |
| Unknown                     | 24        | 32     | 3.97%   |
| HGST                        | 17        | 20     | 2.81%   |
| Intel                       | 16        | 24     | 2.64%   |
| A-DATA Technology           | 16        | 24     | 2.64%   |
| PNY                         | 12        | 34     | 1.98%   |
| Crucial                     | 12        | 20     | 1.98%   |
| Apacer                      | 11        | 17     | 1.82%   |
| SK hynix                    | 9         | 9      | 1.49%   |
| Hitachi                     | 8         | 13     | 1.32%   |
| Phison                      | 7         | 10     | 1.16%   |
| Micron Technology           | 7         | 11     | 1.16%   |
| KIOXIA                      | 7         | 8      | 1.16%   |
| China                       | 6         | 6      | 0.99%   |
| Transcend                   | 5         | 6      | 0.83%   |
| TO Exter                    | 4         | 6      | 0.66%   |
| SPCC                        | 4         | 5      | 0.66%   |
| Silicon Motion              | 4         | 5      | 0.66%   |
| Patriot                     | 4         | 5      | 0.66%   |
| Hewlett-Packard             | 4         | 4      | 0.66%   |
| Corsair                     | 4         | 12     | 0.66%   |
| Phison Electronics          | 3         | 4      | 0.5%    |
| Kingston Technology Company | 3         | 3      | 0.5%    |
| Gigabyte Technology         | 3         | 3      | 0.5%    |
| XPG                         | 2         | 3      | 0.33%   |
| Verbatim                    | 2         | 2      | 0.33%   |
| Plextor                     | 2         | 2      | 0.33%   |
| Micron/Crucial Technology   | 2         | 3      | 0.33%   |
| KIOXIA-EXCERIA              | 2         | 4      | 0.33%   |
| Kingchuxing                 | 2         | 2      | 0.33%   |
| JMicron Technology          | 2         | 2      | 0.33%   |
| Fujitsu                     | 2         | 2      | 0.33%   |
| External                    | 2         | 2      | 0.33%   |
| Colorful                    | 2         | 2      | 0.33%   |
| ASMT                        | 2         | 3      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 13        | 1.95%   |
| Toshiba MQ01ABD100 1TB             | 8         | 1.2%    |
| Seagate ST2000DM008-2UB102 2TB     | 7         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7         | 1.05%   |
| Seagate ST1000DM010-2EP102 1TB     | 7         | 1.05%   |
| Toshiba MQ04ABF100 1TB             | 6         | 0.9%    |
| PNY 1TB SATA SSD                   | 6         | 0.9%    |
| Crucial CT500MX500SSD1 500GB       | 6         | 0.9%    |
| WDC WD5000AAKX-00ERMA0 500GB       | 5         | 0.75%   |
| WDC WD20EZRX-00D8PB0 2TB           | 5         | 0.75%   |
| Unknown MMC Card  32GB             | 5         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB    | 5         | 0.75%   |
| Seagate ST380815AS 80GB            | 5         | 0.75%   |
| Samsung HD103SJ 1TB                | 5         | 0.75%   |
| HGST HTS545050A7E680 500GB         | 5         | 0.75%   |
| Apacer AS340 120GB SSD             | 5         | 0.75%   |
| TO Exter nal USB 3.0 1TB           | 4         | 0.6%    |
| Seagate ST500DM002-1BC142 500GB    | 4         | 0.6%    |
| Seagate ST3160815AS 160GB          | 4         | 0.6%    |
| Seagate ST1000LM048-2E7172 1TB     | 4         | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 0.6%    |
| SanDisk SSD PLUS 240GB             | 4         | 0.6%    |
| Samsung SSD 860 EVO 250GB          | 4         | 0.6%    |
| Kingston SV300S37A120G 120GB SSD   | 4         | 0.6%    |
| Kingston SA400S37480G 480GB SSD    | 4         | 0.6%    |
| Corsair Force MP510 240GB          | 4         | 0.6%    |
| A-DATA SX8200PNP 256GB             | 4         | 0.6%    |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 3         | 0.45%   |
| WDC WD3200AAKS-00SBA0 320GB        | 3         | 0.45%   |
| WDC WD20EZAZ-00GGJB0 2TB           | 3         | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.45%   |
| Unknown MMC Card  64GB             | 3         | 0.45%   |
| Unknown MMC Card                   | 3         | 0.45%   |
| SK hynix NVMe SSD Drive 512GB      | 3         | 0.45%   |
| Seagate ST9320325AS 320GB          | 3         | 0.45%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 0.45%   |
| Seagate ST320LT020-9YG142 320GB    | 3         | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB     | 3         | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB     | 3         | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 160    | 39.7%   |
| WDC                 | 78        | 141    | 29.21%  |
| Toshiba             | 37        | 44     | 13.86%  |
| HGST                | 17        | 20     | 6.37%   |
| Samsung Electronics | 10        | 16     | 3.75%   |
| Hitachi             | 8         | 13     | 3%      |
| Hewlett-Packard     | 2         | 2      | 0.75%   |
| Fujitsu             | 2         | 2      | 0.75%   |
| ASMT                | 2         | 3      | 0.75%   |
| USB3.0              | 1         | 1      | 0.37%   |
| Unknown             | 1         | 1      | 0.37%   |
| Maxtor              | 1         | 2      | 0.37%   |
| JMicron Technology  | 1         | 1      | 0.37%   |
| Apple               | 1         | 1      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 41        | 53     | 21.93%  |
| Samsung Electronics | 21        | 31     | 11.23%  |
| SanDisk             | 15        | 19     | 8.02%   |
| Crucial             | 12        | 20     | 6.42%   |
| PNY                 | 11        | 33     | 5.88%   |
| Apacer              | 11        | 17     | 5.88%   |
| A-DATA Technology   | 8         | 8      | 4.28%   |
| Intel               | 6         | 9      | 3.21%   |
| China               | 6         | 6      | 3.21%   |
| WDC                 | 5         | 5      | 2.67%   |
| Transcend           | 5         | 5      | 2.67%   |
| TO Exter            | 4         | 6      | 2.14%   |
| SPCC                | 4         | 5      | 2.14%   |
| Patriot             | 4         | 5      | 2.14%   |
| Micron Technology   | 4         | 8      | 2.14%   |
| Verbatim            | 2         | 2      | 1.07%   |
| Toshiba             | 2         | 2      | 1.07%   |
| Seagate             | 2         | 2      | 1.07%   |
| Plextor             | 2         | 2      | 1.07%   |
| KIOXIA-EXCERIA      | 2         | 4      | 1.07%   |
| Colorful            | 2         | 2      | 1.07%   |
| Teclast             | 1         | 1      | 0.53%   |
| sk600               | 1         | 1      | 0.53%   |
| SK hynix            | 1         | 1      | 0.53%   |
| SATAFIRM            | 1         | 1      | 0.53%   |
| Pioneer             | 1         | 1      | 0.53%   |
| OCZ                 | 1         | 1      | 0.53%   |
| Netac               | 1         | 1      | 0.53%   |
| LS                  | 1         | 1      | 0.53%   |
| LITEON              | 1         | 1      | 0.53%   |
| Kingmax             | 1         | 1      | 0.53%   |
| KimMiDi             | 1         | 1      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| Hikvision           | 1         | 2      | 0.53%   |
| Hewlett-Packard     | 1         | 1      | 0.53%   |
| Gigabyte Technology | 1         | 1      | 0.53%   |
| FORESEE             | 1         | 1      | 0.53%   |
| Apple               | 1         | 2      | 0.53%   |
| Unknown             | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 225       | 407    | 43.44%  |
| SSD     | 160       | 264    | 30.89%  |
| NVMe    | 100       | 166    | 19.31%  |
| MMC     | 21        | 28     | 4.05%   |
| Unknown | 12        | 15     | 2.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 306       | 657    | 67.85%  |
| NVMe | 99        | 163    | 21.95%  |
| SAS  | 25        | 32     | 5.54%   |
| MMC  | 21        | 28     | 4.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 236       | 382    | 59.6%   |
| 0.51-1.0   | 121       | 208    | 30.56%  |
| 1.01-2.0   | 32        | 65     | 8.08%   |
| 3.01-4.0   | 4         | 12     | 1.01%   |
| 4.01-10.0  | 2         | 3      | 0.51%   |
| 2.01-3.0   | 1         | 1      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 109       | 27.25%  |
| 251-500        | 90        | 22.5%   |
| 501-1000       | 51        | 12.75%  |
| 1-20           | 36        | 9%      |
| 51-100         | 29        | 7.25%   |
| 1001-2000      | 27        | 6.75%   |
| 21-50          | 22        | 5.5%    |
| Unknown        | 18        | 4.5%    |
| More than 3000 | 11        | 2.75%   |
| 2001-3000      | 7         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 180       | 44.01%  |
| 21-50          | 62        | 15.16%  |
| 101-250        | 47        | 11.49%  |
| 51-100         | 39        | 9.54%   |
| 251-500        | 30        | 7.33%   |
| Unknown        | 18        | 4.4%    |
| 501-1000       | 14        | 3.42%   |
| 1001-2000      | 9         | 2.2%    |
| More than 3000 | 6         | 1.47%   |
| 2001-3000      | 3         | 0.73%   |
| 0              | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 2      | 5%      |
| Seagate ST9320325AS 320GB                      | 2         | 2      | 5%      |
| Seagate ST3500414CS 500GB                      | 2         | 3      | 5%      |
| WDC WDS480G2G0A-00JH30 480GB SSD               | 1         | 1      | 2.5%    |
| WDC WD800AAJS-00PSA0 80GB                      | 1         | 1      | 2.5%    |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 2.5%    |
| WDC WD5000AAKX-75U6AA0 500GB                   | 1         | 1      | 2.5%    |
| WDC WD5000AAKX-753CA1 500GB                    | 1         | 1      | 2.5%    |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1         | 1      | 2.5%    |
| WDC WD5000AADS-00S9B0 500GB                    | 1         | 1      | 2.5%    |
| WDC WD10JPVX-22JC3T0 1TB                       | 1         | 1      | 2.5%    |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 2.5%    |
| WDC WD10EZEX-60WN4A0 1TB                       | 1         | 1      | 2.5%    |
| WDC WD10EZEX-08WN4A0 1TB                       | 1         | 1      | 2.5%    |
| Toshiba MK5065GSX 500GB                        | 1         | 1      | 2.5%    |
| Toshiba MK1059GSMP 1TB                         | 1         | 1      | 2.5%    |
| SPCC Solid State Disk 256GB                    | 1         | 1      | 2.5%    |
| Seagate ST9750420AS 752GB                      | 1         | 1      | 2.5%    |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.5%    |
| Seagate ST380211AS 80GB                        | 1         | 1      | 2.5%    |
| Seagate ST3320620A 320GB                       | 1         | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 2.5%    |
| Samsung Electronics SSD PM830 2.5 7mm 512GB    | 1         | 1      | 2.5%    |
| Samsung Electronics HM160HI 160GB              | 1         | 1      | 2.5%    |
| PNY 1TB SATA SSD                               | 1         | 6      | 2.5%    |
| Micron/Crucial Technology P1 NVMe PCIe SSD 1TB | 1         | 2      | 2.5%    |
| Micron Technology 1100 SATA 512GB SSD          | 1         | 1      | 2.5%    |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 2.5%    |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS547575A9E384 752GB                  | 1         | 3      | 2.5%    |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 2.5%    |
| Hitachi HDS721050CLA362 500GB                  | 1         | 1      | 2.5%    |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 2.5%    |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 2.5%    |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 2.5%    |
| Hewlett-Packard SSD S700 120GB                 | 1         | 1      | 2.5%    |
| Unknown                                        | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 11        | 11     | 28.21%  |
| Seagate                   | 8         | 10     | 20.51%  |
| Toshiba                   | 4         | 4      | 10.26%  |
| Hitachi                   | 4         | 6      | 10.26%  |
| HGST                      | 3         | 3      | 7.69%   |
| Samsung Electronics       | 2         | 2      | 5.13%   |
| SPCC                      | 1         | 1      | 2.56%   |
| PNY                       | 1         | 6      | 2.56%   |
| Micron/Crucial Technology | 1         | 2      | 2.56%   |
| Micron Technology         | 1         | 1      | 2.56%   |
| Kingston                  | 1         | 1      | 2.56%   |
| Hewlett-Packard           | 1         | 1      | 2.56%   |
| Unknown                   | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 33.33%  |
| Seagate             | 8         | 10     | 26.67%  |
| Toshiba             | 4         | 4      | 13.33%  |
| Hitachi             | 4         | 6      | 13.33%  |
| HGST                | 3         | 3      | 10%     |
| Samsung Electronics | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 34     | 76.32%  |
| SSD  | 8         | 13     | 21.05%  |
| NVMe | 1         | 2      | 2.63%   |

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
| Detected | 246       | 562    | 59.85%  |
| Works    | 128       | 269    | 31.14%  |
| Malfunc  | 37        | 49     | 9%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 271       | 58.79%  |
| AMD                          | 58        | 12.58%  |
| SanDisk                      | 18        | 3.9%    |
| Samsung Electronics          | 18        | 3.9%    |
| Phison Electronics           | 17        | 3.69%   |
| Kingston Technology Company  | 12        | 2.6%    |
| SK hynix                     | 8         | 1.74%   |
| ASMedia Technology           | 8         | 1.74%   |
| ADATA Technology             | 8         | 1.74%   |
| Silicon Motion               | 7         | 1.52%   |
| Nvidia                       | 7         | 1.52%   |
| KIOXIA                       | 7         | 1.52%   |
| Toshiba America Info Systems | 5         | 1.08%   |
| Marvell Technology Group     | 4         | 0.87%   |
| JMicron Technology           | 4         | 0.87%   |
| Micron Technology            | 3         | 0.65%   |
| Micron/Crucial Technology    | 2         | 0.43%   |
| Silicon Image                | 1         | 0.22%   |
| Lite-On IT Corp. / Plextor   | 1         | 0.22%   |
| Hewlett-Packard              | 1         | 0.22%   |
| Biwin Storage Technology     | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 46        | 8.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 24        | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 22        | 4.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 18        | 3.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 3.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 15        | 2.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 10        | 1.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 1.67%   |
| Phison E12 NVMe Controller                                                     | 9         | 1.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 1.67%   |
| Intel SATA Controller [RAID mode]                                              | 9         | 1.67%   |
| AMD 400 Series Chipset SATA Controller                                         | 9         | 1.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 1.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.49%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 8         | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 1.3%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 1.3%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.93%   |
| Intel SSD 660P Series                                                          | 5         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 0.93%   |
| Intel 82Q35 Express PT IDER Controller                                         | 5         | 0.93%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 5         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.93%   |
| AMD FCH SATA Controller D                                                      | 5         | 0.93%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 0.74%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 4         | 0.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 268       | 59.03%  |
| NVMe | 99        | 21.81%  |
| IDE  | 46        | 10.13%  |
| RAID | 41        | 9.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 293       | 78.13%  |
| AMD    | 77        | 20.53%  |
| ARM    | 5         | 1.33%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium CPU G620 @ 2.60GHz              | 8         | 2.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 2.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.33%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 5         | 1.33%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 5         | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.06%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 4         | 1.06%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 1.06%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 1.06%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 4         | 1.06%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor             | 4         | 1.06%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.06%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 1.06%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 3         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 3         | 0.8%    |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 0.8%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 0.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.8%    |
| Intel Core i5-3570 CPU @ 3.40GHz              | 3         | 0.8%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.8%    |
| Intel Celeron N4100 CPU @ 1.10GHz             | 3         | 0.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.8%    |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.8%    |
| Intel Xeon CPU X5450 @ 3.00GHz                | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 2         | 0.53%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.53%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 0.53%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.53%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.53%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 2         | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.53%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.53%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.53%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 101       | 26.79%  |
| Intel Core i7           | 58        | 15.38%  |
| Intel Core i3           | 36        | 9.55%   |
| AMD Ryzen 5             | 27        | 7.16%   |
| Intel Core 2 Duo        | 21        | 5.57%   |
| Other                   | 19        | 5.04%   |
| Intel Pentium           | 17        | 4.51%   |
| Intel Celeron           | 14        | 3.71%   |
| Intel Xeon              | 12        | 3.18%   |
| AMD Ryzen 7             | 11        | 2.92%   |
| Intel Atom              | 6         | 1.59%   |
| Intel Pentium Dual-Core | 5         | 1.33%   |
| Intel Core 2 Quad       | 5         | 1.33%   |
| AMD Ryzen 9             | 5         | 1.33%   |
| AMD Ryzen 3             | 4         | 1.06%   |
| AMD A6                  | 4         | 1.06%   |
| AMD Ryzen Threadripper  | 3         | 0.8%    |
| AMD Athlon              | 3         | 0.8%    |
| AMD A10                 | 3         | 0.8%    |
| Intel Core i9           | 2         | 0.53%   |
| ARM BCM                 | 2         | 0.53%   |
| AMD Ryzen 7 PRO         | 2         | 0.53%   |
| AMD FX                  | 2         | 0.53%   |
| AMD E                   | 2         | 0.53%   |
| AMD Athlon 64 X2        | 2         | 0.53%   |
| AMD A4                  | 2         | 0.53%   |
| AMD A12                 | 2         | 0.53%   |
| Intel Pentium Dual      | 1         | 0.27%   |
| Intel Genuine           | 1         | 0.27%   |
| ARM AArch64             | 1         | 0.27%   |
| AMD Ryzen Embedded      | 1         | 0.27%   |
| AMD Phenom II X6        | 1         | 0.27%   |
| AMD EPYC                | 1         | 0.27%   |
| AMD Athlon X2           | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 164       | 43.62%  |
| 4      | 130       | 34.57%  |
| 6      | 41        | 10.9%   |
| 8      | 20        | 5.32%   |
| 16     | 7         | 1.86%   |
| 1      | 5         | 1.33%   |
| 12     | 4         | 1.06%   |
| 10     | 2         | 0.53%   |
| 64     | 1         | 0.27%   |
| 14     | 1         | 0.27%   |
| 3      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 371       | 98.93%  |
| 2      | 4         | 1.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 243       | 64.46%  |
| 1      | 133       | 35.28%  |
| 4      | 1         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 371       | 98.67%  |
| Unknown        | 5         | 1.33%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 21.08%  |
| 0x206a7    | 35        | 9%      |
| 0x306c3    | 29        | 7.46%   |
| 0x306a9    | 28        | 7.2%    |
| 0x1067a    | 17        | 4.37%   |
| 0x906ea    | 11        | 2.83%   |
| 0x806e9    | 10        | 2.57%   |
| 0x40651    | 8         | 2.06%   |
| 0x08108109 | 8         | 2.06%   |
| 0x306d4    | 7         | 1.8%    |
| 0x506e3    | 6         | 1.54%   |
| 0x406e3    | 6         | 1.54%   |
| 0x20655    | 6         | 1.54%   |
| 0x806ea    | 5         | 1.29%   |
| 0x6fb      | 5         | 1.29%   |
| 0x20652    | 5         | 1.29%   |
| 0x08701021 | 5         | 1.29%   |
| 0xa0652    | 4         | 1.03%   |
| 0x906e9    | 4         | 1.03%   |
| 0x806ec    | 4         | 1.03%   |
| 0x806eb    | 4         | 1.03%   |
| 0x806c1    | 4         | 1.03%   |
| 0x706a1    | 4         | 1.03%   |
| 0x6fd      | 4         | 1.03%   |
| 0x10676    | 4         | 1.03%   |
| 0x08600104 | 4         | 1.03%   |
| 0x06001119 | 4         | 1.03%   |
| 0xa0653    | 3         | 0.77%   |
| 0x90672    | 3         | 0.77%   |
| 0x406c4    | 3         | 0.77%   |
| 0x30678    | 3         | 0.77%   |
| 0x0a50000b | 3         | 0.77%   |
| 0x0a20120a | 3         | 0.77%   |
| 0xa0671    | 2         | 0.51%   |
| 0xa0655    | 2         | 0.51%   |
| 0x906eb    | 2         | 0.51%   |
| 0x806d1    | 2         | 0.51%   |
| 0x706e5    | 2         | 0.51%   |
| 0x406c3    | 2         | 0.51%   |
| 0x106e5    | 2         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 48        | 12.8%   |
| SandyBridge      | 45        | 12%     |
| Haswell          | 44        | 11.73%  |
| IvyBridge        | 35        | 9.33%   |
| Penryn           | 25        | 6.67%   |
| Zen+             | 16        | 4.27%   |
| Zen 2            | 15        | 4%      |
| Skylake          | 15        | 4%      |
| Zen 3            | 14        | 3.73%   |
| Unknown          | 14        | 3.73%   |
| Westmere         | 13        | 3.47%   |
| CometLake        | 11        | 2.93%   |
| Core             | 10        | 2.67%   |
| Silvermont       | 9         | 2.4%    |
| Broadwell        | 8         | 2.13%   |
| Zen              | 7         | 1.87%   |
| TigerLake        | 6         | 1.6%    |
| Piledriver       | 5         | 1.33%   |
| Goldmont plus    | 5         | 1.33%   |
| Alderlake Hybrid | 5         | 1.33%   |
| Icelake          | 4         | 1.07%   |
| Nehalem          | 3         | 0.8%    |
| Excavator        | 3         | 0.8%    |
| Steamroller      | 2         | 0.53%   |
| K8 Hammer        | 2         | 0.53%   |
| K10              | 2         | 0.53%   |
| Jaguar           | 2         | 0.53%   |
| Bonnell          | 2         | 0.53%   |
| Bobcat           | 2         | 0.53%   |
| K8 & K10 hybrid  | 1         | 0.27%   |
| K10 Llano        | 1         | 0.27%   |
| Goldmont         | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 222       | 47.95%  |
| Nvidia                     | 131       | 28.29%  |
| AMD                        | 104       | 22.46%  |
| ASPEED Technology          | 4         | 0.86%   |
| Matrox Electronics Systems | 2         | 0.43%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 32        | 6.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 4.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 2.32%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 11        | 2.32%   |
| Intel HD Graphics 620                                                                    | 10        | 2.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 1.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 9         | 1.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 1.48%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7         | 1.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.27%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 6         | 1.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.27%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 1.27%   |
| AMD Renoir                                                                               | 6         | 1.27%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 5         | 1.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.05%   |
| Intel HD Graphics 530                                                                    | 5         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.05%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 1.05%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 4         | 0.84%   |
| Intel HD Graphics 630                                                                    | 4         | 0.84%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.84%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4         | 0.84%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.63%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.63%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 3         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 139       | 36.87%  |
| 1 x AMD              | 71        | 18.83%  |
| 1 x Nvidia           | 66        | 17.51%  |
| Intel + Nvidia       | 55        | 14.59%  |
| Intel + AMD          | 20        | 5.31%   |
| 2 x AMD              | 8         | 2.12%   |
| AMD + Nvidia         | 6         | 1.59%   |
| Other                | 5         | 1.33%   |
| Nvidia + ASPEED      | 3         | 0.8%    |
| 1 x Matrox           | 2         | 0.53%   |
| 2 x AMD + 3 x Nvidia | 1         | 0.27%   |
| 1 x ASPEED           | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 296       | 77.69%  |
| Proprietary | 71        | 18.64%  |
| Unknown     | 14        | 3.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 199       | 52.09%  |
| 1.01-2.0   | 64        | 16.75%  |
| 0.51-1.0   | 35        | 9.16%   |
| 0.01-0.5   | 30        | 7.85%   |
| 3.01-4.0   | 29        | 7.59%   |
| 7.01-8.0   | 14        | 3.66%   |
| 5.01-6.0   | 5         | 1.31%   |
| 8.01-16.0  | 4         | 1.05%   |
| 2.01-3.0   | 2         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 49        | 12.44%  |
| Samsung Electronics     | 43        | 10.91%  |
| Dell                    | 39        | 9.9%    |
| Chimei Innolux          | 36        | 9.14%   |
| LG Display              | 32        | 8.12%   |
| BOE                     | 28        | 7.11%   |
| Acer                    | 21        | 5.33%   |
| Hewlett-Packard         | 19        | 4.82%   |
| Goldstar                | 16        | 4.06%   |
| BenQ                    | 16        | 4.06%   |
| AOC                     | 15        | 3.81%   |
| Sharp                   | 11        | 2.79%   |
| Philips                 | 9         | 2.28%   |
| ViewSonic               | 7         | 1.78%   |
| Apple                   | 7         | 1.78%   |
| Lenovo                  | 5         | 1.27%   |
| Chi Mei Optoelectronics | 4         | 1.02%   |
| Toshiba                 | 3         | 0.76%   |
| ASUSTek Computer        | 3         | 0.76%   |
| Unknown                 | 2         | 0.51%   |
| PANDA                   | 2         | 0.51%   |
| Panasonic               | 2         | 0.51%   |
| LG Electronics          | 2         | 0.51%   |
| InnoLux Display         | 2         | 0.51%   |
| Denver                  | 2         | 0.51%   |
| Unknown                 | 2         | 0.51%   |
| Xiaomi                  | 1         | 0.25%   |
| Valve                   | 1         | 0.25%   |
| TRI                     | 1         | 0.25%   |
| Sony                    | 1         | 0.25%   |
| MStar                   | 1         | 0.25%   |
| MSI                     | 1         | 0.25%   |
| LTM                     | 1         | 0.25%   |
| LG Philips              | 1         | 0.25%   |
| InfoVision              | 1         | 0.25%   |
| HUYINIUDA               | 1         | 0.25%   |
| EXP                     | 1         | 0.25%   |
| Envision Peripherals    | 1         | 0.25%   |
| Eizo                    | 1         | 0.25%   |
| Dinner                  | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 7         | 1.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 4         | 0.99%   |
| Dell E2720HS DELA15E 1920x1080 598x336mm 27.0-inch                        | 4         | 0.99%   |
| BenQ EX3203R BNQ7F66 2560x1440 698x393mm 31.5-inch                        | 4         | 0.99%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch      | 3         | 0.74%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                   | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 3         | 0.74%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 3         | 0.74%   |
| BenQ GW2270 BNQ78DB 1920x1080 476x268mm 21.5-inch                         | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch             | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 3         | 0.74%   |
| Acer K242HL ACR03E3 1920x1080 531x299mm 24.0-inch                         | 3         | 0.74%   |
| Sharp LCD SHP10C9 1920x540                                                | 2         | 0.49%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch         | 2         | 0.49%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 2         | 0.49%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch          | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch      | 2         | 0.49%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                        | 2         | 0.49%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 0.49%   |
| InnoLux Display LCD Monitor INL0016 1366x768 309x174mm 14.0-inch          | 2         | 0.49%   |
| Hewlett-Packard LCD Monitor P221                                          | 2         | 0.49%   |
| Hewlett-Packard L1506 HWP265B 1024x768 300x220mm 14.6-inch                | 2         | 0.49%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 2         | 0.49%   |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                        | 2         | 0.49%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.49%   |
| Dell LCD Monitor E2720HS 1920x1080                                        | 2         | 0.49%   |
| Dell 2007FP DELA021 1600x1200 367x275mm 18.1-inch                         | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch           | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch           | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch           | 2         | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.49%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                        | 2         | 0.49%   |
| BenQ LCD Monitor GW2270 1920x1080                                         | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 153       | 40.05%  |
| 1366x768 (WXGA)    | 113       | 29.58%  |
| 3840x2160 (4K)     | 22        | 5.76%   |
| 2560x1440 (QHD)    | 16        | 4.19%   |
| 1600x900 (HD+)     | 14        | 3.66%   |
| 1280x800 (WXGA)    | 9         | 2.36%   |
| 2560x1080          | 6         | 1.57%   |
| 1440x900 (WXGA+)   | 6         | 1.57%   |
| 1920x1200 (WUXGA)  | 5         | 1.31%   |
| Unknown            | 5         | 1.31%   |
| 1360x768           | 4         | 1.05%   |
| 1280x1024 (SXGA)   | 3         | 0.79%   |
| 1024x768 (XGA)     | 3         | 0.79%   |
| 5760x1080          | 2         | 0.52%   |
| 2160x1440          | 2         | 0.52%   |
| 1920x540           | 2         | 0.52%   |
| 1680x1050 (WSXGA+) | 2         | 0.52%   |
| 1600x1200          | 2         | 0.52%   |
| 800x1280           | 1         | 0.26%   |
| 5440x1080          | 1         | 0.26%   |
| 5120x1440          | 1         | 0.26%   |
| 3840x1080          | 1         | 0.26%   |
| 3440x1440          | 1         | 0.26%   |
| 3120x1600          | 1         | 0.26%   |
| 3000x2000          | 1         | 0.26%   |
| 2880x1920          | 1         | 0.26%   |
| 2240x1400          | 1         | 0.26%   |
| 1360x765           | 1         | 0.26%   |
| 1280x960           | 1         | 0.26%   |
| 1280x720 (HD)      | 1         | 0.26%   |
| 1024x600           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 74        | 18.83%  |
| 14      | 51        | 12.98%  |
| 13      | 41        | 10.43%  |
| 24      | 30        | 7.63%   |
| 23      | 30        | 7.63%   |
| 21      | 22        | 5.6%    |
| 27      | 21        | 5.34%   |
| 18      | 21        | 5.34%   |
| Unknown | 19        | 4.83%   |
| 31      | 13        | 3.31%   |
| 19      | 12        | 3.05%   |
| 17      | 10        | 2.54%   |
| 12      | 7         | 1.78%   |
| 32      | 6         | 1.53%   |
| 20      | 6         | 1.53%   |
| 11      | 6         | 1.53%   |
| 34      | 4         | 1.02%   |
| 84      | 2         | 0.51%   |
| 72      | 2         | 0.51%   |
| 52      | 2         | 0.51%   |
| 28      | 2         | 0.51%   |
| 25      | 2         | 0.51%   |
| 22      | 2         | 0.51%   |
| 7       | 2         | 0.51%   |
| 65      | 1         | 0.25%   |
| 55      | 1         | 0.25%   |
| 39      | 1         | 0.25%   |
| 29      | 1         | 0.25%   |
| 16      | 1         | 0.25%   |
| 10      | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 153       | 39.13%  |
| 501-600     | 77        | 19.69%  |
| 401-500     | 62        | 15.86%  |
| 201-300     | 28        | 7.16%   |
| 601-700     | 19        | 4.86%   |
| Unknown     | 19        | 4.86%   |
| 351-400     | 12        | 3.07%   |
| 701-800     | 10        | 2.56%   |
| 1501-2000   | 4         | 1.02%   |
| 1001-1500   | 4         | 1.02%   |
| 801-900     | 1         | 0.26%   |
| 101-200     | 1         | 0.26%   |
| 1-100       | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 287       | 80.85%  |
| 16/10   | 25        | 7.04%   |
| Unknown | 17        | 4.79%   |
| 21/9    | 7         | 1.97%   |
| 3/2     | 6         | 1.69%   |
| 5/4     | 5         | 1.41%   |
| 4/3     | 4         | 1.13%   |
| 32/9    | 2         | 0.56%   |
| 1.00    | 1         | 0.28%   |
| 0.67    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 81        | 20.72%  |
| 101-110        | 75        | 19.18%  |
| 201-250        | 72        | 18.41%  |
| 151-200        | 24        | 6.14%   |
| 351-500        | 23        | 5.88%   |
| 301-350        | 22        | 5.63%   |
| 141-150        | 22        | 5.63%   |
| Unknown        | 19        | 4.86%   |
| 71-80          | 11        | 2.81%   |
| 251-300        | 10        | 2.56%   |
| More than 1000 | 8         | 2.05%   |
| 61-70          | 7         | 1.79%   |
| 121-130        | 7         | 1.79%   |
| 51-60          | 6         | 1.53%   |
| 1-40           | 2         | 0.51%   |
| 41-50          | 1         | 0.26%   |
| 501-1000       | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 138       | 35.94%  |
| 101-120       | 115       | 29.95%  |
| 121-160       | 88        | 22.92%  |
| Unknown       | 19        | 4.95%   |
| 161-240       | 12        | 3.13%   |
| 1-50          | 9         | 2.34%   |
| More than 240 | 3         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 305       | 80.47%  |
| 2     | 52        | 13.72%  |
| 0     | 20        | 5.28%   |
| 3     | 2         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 195       | 31.91%  |
| Intel                             | 179       | 29.3%   |
| Qualcomm Atheros                  | 82        | 13.42%  |
| Broadcom                          | 38        | 6.22%   |
| TP-Link                           | 22        | 3.6%    |
| Ralink Technology                 | 19        | 3.11%   |
| D-Link                            | 11        | 1.8%    |
| Xiaomi                            | 9         | 1.47%   |
| Qualcomm Atheros Communications   | 8         | 1.31%   |
| MediaTek                          | 6         | 0.98%   |
| Ralink                            | 5         | 0.82%   |
| Nvidia                            | 5         | 0.82%   |
| Broadcom Limited                  | 5         | 0.82%   |
| ASIX Electronics                  | 4         | 0.65%   |
| Huawei Technologies               | 3         | 0.49%   |
| Samsung Electronics               | 2         | 0.33%   |
| OPPO Electronics                  | 2         | 0.33%   |
| InterBiometrics                   | 2         | 0.33%   |
| Aquantia                          | 2         | 0.33%   |
| Tehuti Networks                   | 1         | 0.16%   |
| Sundance Technology Inc / IC Plus | 1         | 0.16%   |
| Marvell Technology Group          | 1         | 0.16%   |
| JMicron Technology                | 1         | 0.16%   |
| Hewlett-Packard                   | 1         | 0.16%   |
| DisplayLink                       | 1         | 0.16%   |
| D-Link System                     | 1         | 0.16%   |
| Attansic Technology               | 1         | 0.16%   |
| ASUSTek Computer                  | 1         | 0.16%   |
| Apple                             | 1         | 0.16%   |
| American Megatrends               | 1         | 0.16%   |
| AboCom Systems                    | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 131       | 18.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 3.29%   |
| Intel Wi-Fi 6 AX200                                               | 15        | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.57%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 1.43%   |
| TP-Link Archer T4U ver.3                                          | 9         | 1.29%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.29%   |
| Realtek 802.11ac NIC                                              | 9         | 1.29%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 1.29%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 1.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 8         | 1.14%   |
| TP-Link 802.11n NIC                                               | 7         | 1%      |
| Ralink RT2870/RT3070 Wireless Adapter                             | 7         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 1%      |
| Intel Ethernet Connection I217-LM                                 | 7         | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.86%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 6         | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.86%   |
| Intel Wireless 7265                                               | 6         | 0.86%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 6         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5         | 0.71%   |
| Intel Wireless 3165                                               | 5         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.71%   |
| Intel I211 Gigabit Network Connection                             | 5         | 0.71%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 119       | 35.63%  |
| Qualcomm Atheros                | 65        | 19.46%  |
| Realtek Semiconductor           | 48        | 14.37%  |
| Broadcom                        | 24        | 7.19%   |
| TP-Link                         | 22        | 6.59%   |
| Ralink Technology               | 19        | 5.69%   |
| D-Link                          | 11        | 3.29%   |
| Qualcomm Atheros Communications | 8         | 2.4%    |
| MediaTek                        | 6         | 1.8%    |
| Ralink                          | 5         | 1.5%    |
| Broadcom Limited                | 4         | 1.2%    |
| D-Link System                   | 1         | 0.3%    |
| ASUSTek Computer                | 1         | 0.3%    |
| AboCom Systems                  | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Computers | Percent |
|--------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                  | 15        | 4.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                           | 12        | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 11        | 3.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 11        | 3.25%   |
| Intel Wireless 8265 / 8275                                                           | 11        | 3.25%   |
| TP-Link Archer T4U ver.3                                                             | 9         | 2.66%   |
| Realtek 802.11ac NIC                                                                 | 9         | 2.66%   |
| Ralink MT7601U Wireless Adapter                                                      | 9         | 2.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 8         | 2.37%   |
| TP-Link 802.11n NIC                                                                  | 7         | 2.07%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 7         | 2.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 7         | 2.07%   |
| Intel Comet Lake PCH CNVi WiFi                                                       | 7         | 2.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                         | 7         | 2.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                             | 6         | 1.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 6         | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                           | 6         | 1.78%   |
| Intel Wireless 7265                                                                  | 6         | 1.78%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                       | 6         | 1.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 5         | 1.48%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 5         | 1.48%   |
| Intel Wireless 3165                                                                  | 5         | 1.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                               | 5         | 1.48%   |
| Intel Centrino Wireless-N 2230                                                       | 5         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                             | 5         | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                             | 4         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                      | 4         | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                           | 4         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                        | 4         | 1.18%   |
| Intel Wireless-AC 9260                                                               | 4         | 1.18%   |
| Intel Wireless 7260                                                                  | 4         | 1.18%   |
| Intel Wireless 3160                                                                  | 4         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                                  | 4         | 1.18%   |
| Intel Centrino Ultimate-N 6300                                                       | 4         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                                      | 4         | 1.18%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                                   | 4         | 1.18%   |
| Ralink RT5572 Wireless Adapter                                                       | 3         | 0.89%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 3         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                       | 3         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 3         | 0.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 174       | 49.86%  |
| Intel                             | 99        | 28.37%  |
| Qualcomm Atheros                  | 22        | 6.3%    |
| Broadcom                          | 18        | 5.16%   |
| Xiaomi                            | 9         | 2.58%   |
| Nvidia                            | 5         | 1.43%   |
| ASIX Electronics                  | 4         | 1.15%   |
| Huawei Technologies               | 3         | 0.86%   |
| Samsung Electronics               | 2         | 0.57%   |
| OPPO Electronics                  | 2         | 0.57%   |
| Aquantia                          | 2         | 0.57%   |
| Tehuti Networks                   | 1         | 0.29%   |
| Sundance Technology Inc / IC Plus | 1         | 0.29%   |
| Marvell Technology Group          | 1         | 0.29%   |
| JMicron Technology                | 1         | 0.29%   |
| DisplayLink                       | 1         | 0.29%   |
| Broadcom Limited                  | 1         | 0.29%   |
| Attansic Technology               | 1         | 0.29%   |
| Apple                             | 1         | 0.29%   |
| American Megatrends               | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 131       | 36.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 6.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 4.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 2.51%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 2.51%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 1.39%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 4         | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.11%   |
| Intel Ethernet Connection (11) I219-V                             | 4         | 1.11%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.11%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 4         | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.84%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 0.84%   |
| Huawei ANA-NX9                                                    | 3         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.56%   |
| OPPO RMX3263                                                      | 2         | 0.56%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.56%   |
| Intel I350 Gigabit Fiber Network Connection                       | 2         | 0.56%   |
| Intel Ethernet Controller X550                                    | 2         | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 317       | 50.72%  |
| WiFi     | 305       | 48.8%   |
| Modem    | 3         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 246       | 64.74%  |
| Ethernet | 134       | 35.26%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 205       | 54.52%  |
| 1     | 134       | 35.64%  |
| 0     | 22        | 5.85%   |
| 3     | 11        | 2.93%   |
| 4     | 2         | 0.53%   |
| 9     | 1         | 0.27%   |
| 8     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 280       | 72.16%  |
| Yes  | 108       | 27.84%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 39.5%   |
| Cambridge Silicon Radio         | 23        | 9.66%   |
| Realtek Semiconductor           | 18        | 7.56%   |
| Qualcomm Atheros Communications | 18        | 7.56%   |
| IMC Networks                    | 14        | 5.88%   |
| Broadcom                        | 14        | 5.88%   |
| Foxconn / Hon Hai               | 12        | 5.04%   |
| Apple                           | 12        | 5.04%   |
| Lite-On Technology              | 10        | 4.2%    |
| Dell                            | 5         | 2.1%    |
| Hewlett-Packard                 | 4         | 1.68%   |
| Realtek                         | 3         | 1.26%   |
| TP-Link                         | 2         | 0.84%   |
| Ralink                          | 2         | 0.84%   |
| MediaTek                        | 2         | 0.84%   |
| Ralink Technology               | 1         | 0.42%   |
| D-Link                          | 1         | 0.42%   |
| ASUSTek Computer                | 1         | 0.42%   |
| Askey Computer                  | 1         | 0.42%   |
| Alps Electric                   | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 31        | 13.03%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 23        | 9.66%   |
| Intel AX200 Bluetooth                                                               | 16        | 6.72%   |
| Intel AX201 Bluetooth                                                               | 14        | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 4.62%   |
| Realtek Bluetooth Radio                                                             | 10        | 4.2%    |
| Apple Bluetooth Host Controller                                                     | 9         | 3.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 2.94%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 2.52%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 2.1%    |
| Intel AX210 Bluetooth                                                               | 5         | 2.1%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.68%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.68%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.68%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.26%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.26%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.26%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.26%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.26%   |
| TP-Link UB500 Adapter                                                               | 2         | 0.84%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.84%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.84%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.84%   |
| Intel Bluetooth Device                                                              | 2         | 0.84%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.84%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.84%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.84%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.84%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.84%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.84%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.84%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 276       | 54.22%  |
| AMD                         | 98        | 19.25%  |
| Nvidia                      | 93        | 18.27%  |
| C-Media Electronics         | 8         | 1.57%   |
| Logitech                    | 7         | 1.38%   |
| JMTek                       | 4         | 0.79%   |
| ASUSTek Computer            | 3         | 0.59%   |
| Samsung Electronics         | 2         | 0.39%   |
| RODE Microphones            | 2         | 0.39%   |
| Realtek Semiconductor       | 2         | 0.39%   |
| Generalplus Technology      | 2         | 0.39%   |
| Texas Instruments           | 1         | 0.2%    |
| Setek Elektronik            | 1         | 0.2%    |
| Razer USA                   | 1         | 0.2%    |
| Plantronics                 | 1         | 0.2%    |
| MVSILICON.INC.              | 1         | 0.2%    |
| MosArt Semiconductor        | 1         | 0.2%    |
| GYROCOM C&C                 | 1         | 0.2%    |
| GN Netcom                   | 1         | 0.2%    |
| FiiO Electronics Technology | 1         | 0.2%    |
| Creative Labs               | 1         | 0.2%    |
| Cooler Master               | 1         | 0.2%    |
| Cambridge Audio             | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 40        | 6.69%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 35        | 5.85%   |
| AMD Family 17h/19h HD Audio Controller                                            | 33        | 5.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 27        | 4.52%   |
| Intel Sunrise Point-LP HD Audio                                                   | 26        | 4.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 18        | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 17        | 2.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 17        | 2.84%   |
| Nvidia GF108 High Definition Audio Controller                                     | 15        | 2.51%   |
| AMD Starship/Matisse HD Audio Controller                                          | 15        | 2.51%   |
| Intel Cannon Lake PCH cAVS                                                        | 14        | 2.34%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 14        | 2.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 13        | 2.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 9         | 1.51%   |
| Intel 8 Series HD Audio Controller                                                | 9         | 1.51%   |
| AMD FCH Azalia Controller                                                         | 9         | 1.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 9         | 1.51%   |
| Intel Haswell-ULT HD Audio Controller                                             | 8         | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 8         | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 7         | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 7         | 1.17%   |
| Intel Broadwell-U Audio Controller                                                | 7         | 1.17%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 6         | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 6         | 1%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 1%      |
| Intel Comet Lake PCH cAVS                                                         | 6         | 1%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 6         | 1%      |
| Nvidia GP107GL High Definition Audio Controller                                   | 5         | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5         | 0.84%   |
| Nvidia GA106 High Definition Audio Controller                                     | 5         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 5         | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                          | 5         | 0.84%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 5         | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 5         | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                     | 4         | 0.67%   |
| Nvidia High Definition Audio Controller                                           | 4         | 0.67%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 61        | 27.6%   |
| Samsung Electronics | 41        | 18.55%  |
| SK hynix            | 37        | 16.74%  |
| Micron Technology   | 14        | 6.33%   |
| Corsair             | 12        | 5.43%   |
| Unknown             | 10        | 4.52%   |
| Nanya Technology    | 7         | 3.17%   |
| A-DATA Technology   | 7         | 3.17%   |
| Ramaxel Technology  | 4         | 1.81%   |
| Kingmax             | 4         | 1.81%   |
| Apacer              | 4         | 1.81%   |
| Team                | 3         | 1.36%   |
| Crucial             | 3         | 1.36%   |
| Unknown (ABCD)      | 2         | 0.9%    |
| Silicon Power       | 2         | 0.9%    |
| Kimtigo             | 2         | 0.9%    |
| Elpida              | 2         | 0.9%    |
| SemsoTai            | 1         | 0.45%   |
| PNY                 | 1         | 0.45%   |
| Patriot Memory      | 1         | 0.45%   |
| Kinlstuo            | 1         | 0.45%   |
| Hewlett-Packard     | 1         | 0.45%   |
| G.Skill             | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 5         | 2.12%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.69%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 4         | 1.69%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 3         | 1.27%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.27%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 3         | 1.27%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 2         | 0.85%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.85%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.85%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.85%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.85%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Micron RAM 8ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.85%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 2         | 0.85%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3266MT/s            | 2         | 0.85%   |
| Kingston RAM 99U5428-082.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.85%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| Kingmax RAM FLFE85F-C8KL9 2GB DIMM DDR3 1333MT/s                 | 2         | 0.85%   |
| Kimtigo RAM KT8GS3EDF 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.85%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.85%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3400MT/s                      | 2         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.42%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR3 1067MT/s                        | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 1         | 0.42%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s     | 1         | 0.42%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s               | 1         | 0.42%   |
| Team RAM Elite-800 2048MB DIMM SDRAM 2048MT/s                    | 1         | 0.42%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 80        | 43.72%  |
| DDR4    | 77        | 42.08%  |
| SDRAM   | 8         | 4.37%   |
| DDR2    | 6         | 3.28%   |
| LPDDR4  | 4         | 2.19%   |
| LPDDR3  | 4         | 2.19%   |
| Unknown | 2         | 1.09%   |
| DDR5    | 1         | 0.55%   |
| DDR     | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 104       | 57.46%  |
| DIMM         | 69        | 38.12%  |
| Row Of Chips | 7         | 3.87%   |
| FB-DIMM      | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 67        | 33.17%  |
| 8192  | 63        | 31.19%  |
| 2048  | 31        | 15.35%  |
| 16384 | 21        | 10.4%   |
| 32768 | 15        | 7.43%   |
| 1024  | 5         | 2.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 48        | 23.88%  |
| 3200    | 28        | 13.93%  |
| 2667    | 27        | 13.43%  |
| 1334    | 15        | 7.46%   |
| 1333    | 15        | 7.46%   |
| 2400    | 13        | 6.47%   |
| 2133    | 8         | 3.98%   |
| 3600    | 5         | 2.49%   |
| 800     | 5         | 2.49%   |
| 667     | 5         | 2.49%   |
| Unknown | 5         | 2.49%   |
| 1067    | 4         | 1.99%   |
| 3266    | 3         | 1.49%   |
| 4267    | 2         | 1%      |
| 4199    | 2         | 1%      |
| 3400    | 2         | 1%      |
| 1867    | 2         | 1%      |
| 1800    | 2         | 1%      |
| 1066    | 2         | 1%      |
| 4800    | 1         | 0.5%    |
| 3534    | 1         | 0.5%    |
| 3466    | 1         | 0.5%    |
| 3000    | 1         | 0.5%    |
| 2933    | 1         | 0.5%    |
| 2134    | 1         | 0.5%    |
| 2048    | 1         | 0.5%    |
| 1866    | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 3         | 21.43%  |
| Samsung Electronics | 3         | 21.43%  |
| Canon               | 3         | 21.43%  |
| Brother Industries  | 3         | 21.43%  |
| Prolific Technology | 1         | 7.14%   |
| Hewlett-Packard     | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-3400 Series       | 3         | 21.43%  |
| Canon E410 series             | 2         | 14.29%  |
| Seiko Epson L310 Series       | 1         | 7.14%   |
| Seiko Epson L210 Series       | 1         | 7.14%   |
| Seiko Epson ET-2710 Series    | 1         | 7.14%   |
| Prolific PL2305 Parallel Port | 1         | 7.14%   |
| HP Ink Tank 110 series        | 1         | 7.14%   |
| Canon LBP6030w/6018w          | 1         | 7.14%   |
| Brother DCP-J105              | 1         | 7.14%   |
| Brother DCP-1610W             | 1         | 7.14%   |
| Brother DCP-1510              | 1         | 7.14%   |

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
| Chicony Electronics                    | 36        | 17.22%  |
| Microdia                               | 25        | 11.96%  |
| IMC Networks                           | 18        | 8.61%   |
| Realtek Semiconductor                  | 17        | 8.13%   |
| Sunplus Innovation Technology          | 16        | 7.66%   |
| Acer                                   | 12        | 5.74%   |
| Suyin                                  | 11        | 5.26%   |
| Logitech                               | 11        | 5.26%   |
| Apple                                  | 10        | 4.78%   |
| Generalplus Technology                 | 7         | 3.35%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.35%   |
| Quanta                                 | 5         | 2.39%   |
| Alcor Micro                            | 4         | 1.91%   |
| YGTek                                  | 3         | 1.44%   |
| Syntek                                 | 3         | 1.44%   |
| Luxvisions Innotech Limited            | 3         | 1.44%   |
| Lite-On Technology                     | 3         | 1.44%   |
| Silicon Motion                         | 2         | 0.96%   |
| Lenovo                                 | 2         | 0.96%   |
| Z-Star Microelectronics                | 1         | 0.48%   |
| WCM_USB                                | 1         | 0.48%   |
| vivo                                   | 1         | 0.48%   |
| USB Camera                             | 1         | 0.48%   |
| Sonix Technology                       | 1         | 0.48%   |
| Samsung Electronics                    | 1         | 0.48%   |
| Ricoh                                  | 1         | 0.48%   |
| Primax Electronics                     | 1         | 0.48%   |
| OmniVision Technologies                | 1         | 0.48%   |
| Jieli Technology                       | 1         | 0.48%   |
| eMPIA Technology                       | 1         | 0.48%   |
| Cubeternet                             | 1         | 0.48%   |
| Bison Electronics                      | 1         | 0.48%   |
| ARC International                      | 1         | 0.48%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 11        | 5.26%   |
| Chicony USB2.0 VGA UVC WebCam                           | 8         | 3.83%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 2.39%   |
| Generalplus GENERAL WEBCAM                              | 5         | 2.39%   |
| Chicony HD WebCam                                       | 5         | 2.39%   |
| Realtek Integrated_Webcam_HD                            | 4         | 1.91%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 4         | 1.91%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.91%   |
| Chicony Integrated Camera                               | 4         | 1.91%   |
| YGTek Webcam                                            | 3         | 1.44%   |
| Microdia USB 2.0 Camera                                 | 3         | 1.44%   |
| Logitech HD Pro Webcam C920                             | 3         | 1.44%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 1.44%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.44%   |
| Chicony HP HD Webcam                                    | 3         | 1.44%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.44%   |
| Apple FaceTime HD Camera                                | 3         | 1.44%   |
| Acer Lenovo Integrated Webcam                           | 3         | 1.44%   |
| Suyin Laptop_Integrated_Webcam_HD                       | 2         | 0.96%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 2         | 0.96%   |
| Suyin 1.3M HD WebCam                                    | 2         | 0.96%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 0.96%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 0.96%   |
| Realtek USB Camera                                      | 2         | 0.96%   |
| Realtek HD WebCam                                       | 2         | 0.96%   |
| Quanta HP TrueVision HD Camera                          | 2         | 0.96%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.96%   |
| Logitech Webcam C270                                    | 2         | 0.96%   |
| Logitech Webcam C170                                    | 2         | 0.96%   |
| Lite-On Integrated Camera                               | 2         | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 0.96%   |
| IMC Networks Integrated Camera                          | 2         | 0.96%   |
| IMC Networks HD Camera                                  | 2         | 0.96%   |
| Generalplus 808 Camera #9 (web-cam mode)                | 2         | 0.96%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 2         | 0.96%   |
| Apple FaceTime HD Camera (Built-in)                     | 2         | 0.96%   |
| Apple Built-in iSight                                   | 2         | 0.96%   |
| Alcor Micro Asus Integrated Webcam                      | 2         | 0.96%   |
| Acer Integrated Camera                                  | 2         | 0.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 26.67%  |
| Synaptics                  | 7         | 23.33%  |
| Shenzhen Goodix Technology | 5         | 16.67%  |
| Elan Microelectronics      | 3         | 10%     |
| AuthenTec                  | 3         | 10%     |
| Upek                       | 2         | 6.67%   |
| LighTuning Technology      | 1         | 3.33%   |
| Focal-systems.Corp         | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix Fingerprint Reader                          | 3         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                  | 2         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 2         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 2         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 2         | 6.67%   |
| Elan ELAN:ARM-M4                                            | 2         | 6.67%   |
| Validity Sensors VFS491                                     | 1         | 3.33%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 1         | 3.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 1         | 3.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 3.33%   |
| Validity Sensors Fingerprint scanner                        | 1         | 3.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                   | 1         | 3.33%   |
| Synaptics  WBDI                                             | 1         | 3.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 3.33%   |
| Shenzhen Goodix  Fingerprint Device                         | 1         | 3.33%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 1         | 3.33%   |
| Focal-systems.Corp FT9201Fingerprint.                       | 1         | 3.33%   |
| Elan ELAN:Fingerprint                                       | 1         | 3.33%   |
| AuthenTec Fingerprint Sensor                                | 1         | 3.33%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 1         | 3.33%   |
| AuthenTec AES1660 Fingerprint Sensor                        | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 81.82%  |
| O2 Micro    | 1         | 9.09%   |
| Alcor Micro | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 36.36%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 9.09%   |
| Broadcom 5880                                                                | 1         | 9.09%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 280       | 73.3%   |
| 1     | 86        | 22.51%  |
| 2     | 12        | 3.14%   |
| 3     | 2         | 0.52%   |
| 6     | 1         | 0.26%   |
| 4     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 25.64%  |
| Graphics card            | 26        | 22.22%  |
| Net/wireless             | 22        | 18.8%   |
| Chipcard                 | 9         | 7.69%   |
| Multimedia controller    | 8         | 6.84%   |
| Communication controller | 5         | 4.27%   |
| Unassigned class         | 3         | 2.56%   |
| Storage                  | 3         | 2.56%   |
| Bluetooth                | 3         | 2.56%   |
| Storage/ide              | 2         | 1.71%   |
| Sound                    | 2         | 1.71%   |
| Net/ethernet             | 2         | 1.71%   |
| Network                  | 1         | 0.85%   |
| Card reader              | 1         | 0.85%   |


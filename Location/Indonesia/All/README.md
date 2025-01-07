Linux in Indonesia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Indonesia/Desktop/README.md) and [notebooks](/Location/Indonesia/Notebook/README.md).

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

Total: 2492

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G40-45 80E1                 | Notebook    | [ac16ada090](https://linux-hardware.org/?probe=ac16ada090) | Jan 06, 2025 |
| HP            | 2B12                        | Desktop     | [f9594ff416](https://linux-hardware.org/?probe=f9594ff416) | Jan 05, 2025 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [3b654f1020](https://linux-hardware.org/?probe=3b654f1020) | Jan 05, 2025 |
| Unknown       | FP7R2AIO                    | All in one  | [7c37fce41a](https://linux-hardware.org/?probe=7c37fce41a) | Jan 04, 2025 |
| Unknown       | FP7R2AIO                    | All in one  | [d64e3db9ce](https://linux-hardware.org/?probe=d64e3db9ce) | Jan 04, 2025 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [d36b787d21](https://linux-hardware.org/?probe=d36b787d21) | Jan 04, 2025 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [a73526a4ad](https://linux-hardware.org/?probe=a73526a4ad) | Jan 04, 2025 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9bb39e061b](https://linux-hardware.org/?probe=9bb39e061b) | Jan 04, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [895f91d18f](https://linux-hardware.org/?probe=895f91d18f) | Jan 03, 2025 |
| Acer          | Aspire E5-552G              | Notebook    | [97430826f3](https://linux-hardware.org/?probe=97430826f3) | Jan 03, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [621ced80c1](https://linux-hardware.org/?probe=621ced80c1) | Jan 03, 2025 |
| Acer          | Aspire E5-552G              | Notebook    | [9b3e1c7a27](https://linux-hardware.org/?probe=9b3e1c7a27) | Jan 02, 2025 |
| Acer          | Aspire E5-552G              | Notebook    | [2cd3af691f](https://linux-hardware.org/?probe=2cd3af691f) | Jan 02, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [54b1993e1c](https://linux-hardware.org/?probe=54b1993e1c) | Jan 02, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [60d8cda1ee](https://linux-hardware.org/?probe=60d8cda1ee) | Jan 02, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [3bb27ee500](https://linux-hardware.org/?probe=3bb27ee500) | Jan 02, 2025 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9829e4ea09](https://linux-hardware.org/?probe=9829e4ea09) | Jan 01, 2025 |
| Dell          | 033FF6 A00                  | Desktop     | [d8f0132e52](https://linux-hardware.org/?probe=d8f0132e52) | Jan 01, 2025 |
| Lenovo        | No DPK                      | Desktop     | [0a59c75def](https://linux-hardware.org/?probe=0a59c75def) | Dec 28, 2024 |
| MSI           | Z97-G43 GAMING              | Desktop     | [28be42de72](https://linux-hardware.org/?probe=28be42de72) | Dec 28, 2024 |
| Dell          | 07HXY6 A01                  | Desktop     | [05efb343fe](https://linux-hardware.org/?probe=05efb343fe) | Dec 28, 2024 |
| MSI           | Katana A15 AI B8VE          | Notebook    | [2dc1c3f9ae](https://linux-hardware.org/?probe=2dc1c3f9ae) | Dec 27, 2024 |
| MSI           | Katana A15 AI B8VE          | Notebook    | [ae92e3f945](https://linux-hardware.org/?probe=ae92e3f945) | Dec 27, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [283f8d39eb](https://linux-hardware.org/?probe=283f8d39eb) | Dec 27, 2024 |
| HP            | ProBook 440 G5              | Notebook    | [eb07190046](https://linux-hardware.org/?probe=eb07190046) | Dec 27, 2024 |
| Fujitsu       | FARQ17004                   | Tablet      | [a8c473704c](https://linux-hardware.org/?probe=a8c473704c) | Dec 27, 2024 |
| ASUSTek       | X455LD                      | Notebook    | [0695dcd803](https://linux-hardware.org/?probe=0695dcd803) | Dec 26, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9930026b7c](https://linux-hardware.org/?probe=9930026b7c) | Dec 25, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [69227251ee](https://linux-hardware.org/?probe=69227251ee) | Dec 25, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [15ca1a3986](https://linux-hardware.org/?probe=15ca1a3986) | Dec 25, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [bc75be3895](https://linux-hardware.org/?probe=bc75be3895) | Dec 25, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [fab3c1d036](https://linux-hardware.org/?probe=fab3c1d036) | Dec 25, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [b5f8afb7e9](https://linux-hardware.org/?probe=b5f8afb7e9) | Dec 24, 2024 |
| Lenovo        | ThinkCentre A70 7099S3A     | Desktop     | [1ed214159d](https://linux-hardware.org/?probe=1ed214159d) | Dec 24, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e3ecdfe665](https://linux-hardware.org/?probe=e3ecdfe665) | Dec 23, 2024 |
| Unknown       | Unknown                     | Soc         | [4839a778ab](https://linux-hardware.org/?probe=4839a778ab) | Dec 22, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [d884bdac45](https://linux-hardware.org/?probe=d884bdac45) | Dec 19, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [013dec6bfc](https://linux-hardware.org/?probe=013dec6bfc) | Dec 19, 2024 |
| Lenovo        | ThinkPad X260 20F5S0D501    | Notebook    | [d1c3cc5bc7](https://linux-hardware.org/?probe=d1c3cc5bc7) | Dec 18, 2024 |
| HP            | Notebook                    | Notebook    | [17804122c5](https://linux-hardware.org/?probe=17804122c5) | Dec 18, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [eee288c125](https://linux-hardware.org/?probe=eee288c125) | Dec 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [eaa6397d5e](https://linux-hardware.org/?probe=eaa6397d5e) | Dec 16, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [b200a9d4f6](https://linux-hardware.org/?probe=b200a9d4f6) | Dec 16, 2024 |
| Dell          | Latitude E7450              | Notebook    | [18a5e779b9](https://linux-hardware.org/?probe=18a5e779b9) | Dec 16, 2024 |
| Biostar       | IH61MF-Q5                   | Desktop     | [4ff0b038b3](https://linux-hardware.org/?probe=4ff0b038b3) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [98e4e31c99](https://linux-hardware.org/?probe=98e4e31c99) | Dec 15, 2024 |
| ASUSTek       | X202E                       | Notebook    | [ff5d34316c](https://linux-hardware.org/?probe=ff5d34316c) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [8c4e0cc970](https://linux-hardware.org/?probe=8c4e0cc970) | Dec 15, 2024 |
| Lenovo        | G41-35 80M7                 | Notebook    | [771258a66a](https://linux-hardware.org/?probe=771258a66a) | Dec 14, 2024 |
| Sony          | VPCYB15AG                   | Notebook    | [2b66b4ead4](https://linux-hardware.org/?probe=2b66b4ead4) | Dec 14, 2024 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [de007da665](https://linux-hardware.org/?probe=de007da665) | Dec 13, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [4333cd141f](https://linux-hardware.org/?probe=4333cd141f) | Dec 13, 2024 |
| ASUSTek       | X450CP                      | Notebook    | [920b185ab5](https://linux-hardware.org/?probe=920b185ab5) | Dec 13, 2024 |
| Dell          | G3 3590                     | Notebook    | [9559e19b33](https://linux-hardware.org/?probe=9559e19b33) | Dec 12, 2024 |
| ADVAN         | 1405                        | Notebook    | [0c35574db2](https://linux-hardware.org/?probe=0c35574db2) | Dec 10, 2024 |
| Acer          | Swift SF314-56G             | Notebook    | [64815f9248](https://linux-hardware.org/?probe=64815f9248) | Dec 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [cbd8da337a](https://linux-hardware.org/?probe=cbd8da337a) | Dec 09, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [1b7baa72c2](https://linux-hardware.org/?probe=1b7baa72c2) | Dec 06, 2024 |
| Lenovo        | ThinkPad L480 20LTA02MJP    | Notebook    | [5816a82f83](https://linux-hardware.org/?probe=5816a82f83) | Dec 05, 2024 |
| AXIOO         | EduBook Air                 | Notebook    | [54b6286adc](https://linux-hardware.org/?probe=54b6286adc) | Dec 05, 2024 |
| AXIOO         | EduBook Air                 | Notebook    | [f71d5640ed](https://linux-hardware.org/?probe=f71d5640ed) | Dec 05, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [f28ca4079c](https://linux-hardware.org/?probe=f28ca4079c) | Dec 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [456d3c7b2d](https://linux-hardware.org/?probe=456d3c7b2d) | Nov 30, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [a176cb1cfa](https://linux-hardware.org/?probe=a176cb1cfa) | Nov 30, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [0709f67f61](https://linux-hardware.org/?probe=0709f67f61) | Nov 29, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [3943e4d18a](https://linux-hardware.org/?probe=3943e4d18a) | Nov 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [d10b86c991](https://linux-hardware.org/?probe=d10b86c991) | Nov 29, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3757df02d2](https://linux-hardware.org/?probe=3757df02d2) | Nov 28, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [e7ffb651be](https://linux-hardware.org/?probe=e7ffb651be) | Nov 26, 2024 |
| HP            | EliteBook 8560w             | Notebook    | [5c651293f0](https://linux-hardware.org/?probe=5c651293f0) | Nov 25, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [616dd41a0d](https://linux-hardware.org/?probe=616dd41a0d) | Nov 25, 2024 |
| Lenovo        | ThinkPad X270 20HMS2JD03    | Notebook    | [9cc08cb72c](https://linux-hardware.org/?probe=9cc08cb72c) | Nov 25, 2024 |
| AXIOO         | Hype 5 G12                  | Notebook    | [c05b80051b](https://linux-hardware.org/?probe=c05b80051b) | Nov 25, 2024 |
| Dell          | Latitude D620               | Notebook    | [b6bcc2c7f0](https://linux-hardware.org/?probe=b6bcc2c7f0) | Nov 25, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [2dc26b3608](https://linux-hardware.org/?probe=2dc26b3608) | Nov 22, 2024 |
| ASUSTek       | GL553VD                     | Notebook    | [05198e67f4](https://linux-hardware.org/?probe=05198e67f4) | Nov 22, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [f3bc755a64](https://linux-hardware.org/?probe=f3bc755a64) | Nov 21, 2024 |
| Acer          | Aspire A514-54G             | Notebook    | [90415bf718](https://linux-hardware.org/?probe=90415bf718) | Nov 21, 2024 |
| Acer          | Aspire E1-531G              | Notebook    | [0dc612c4a9](https://linux-hardware.org/?probe=0dc612c4a9) | Nov 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [48d4b2b2d6](https://linux-hardware.org/?probe=48d4b2b2d6) | Nov 18, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | Notebook    | [4966e097ee](https://linux-hardware.org/?probe=4966e097ee) | Nov 17, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | Notebook    | [f32f6badec](https://linux-hardware.org/?probe=f32f6badec) | Nov 17, 2024 |
| Acer          | Aspire A514-54G             | Notebook    | [a965ec6798](https://linux-hardware.org/?probe=a965ec6798) | Nov 16, 2024 |
| ASRock        | X600-ITX                    | Desktop     | [00b43dd980](https://linux-hardware.org/?probe=00b43dd980) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [e42cce2813](https://linux-hardware.org/?probe=e42cce2813) | Nov 15, 2024 |
| Dell          | 0YF8P5 A00                  | Desktop     | [e872037135](https://linux-hardware.org/?probe=e872037135) | Nov 14, 2024 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [f6ebfc4fcb](https://linux-hardware.org/?probe=f6ebfc4fcb) | Nov 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3a28af2ad6](https://linux-hardware.org/?probe=3a28af2ad6) | Nov 13, 2024 |
| MSI           | ZH77A-G43                   | Desktop     | [6e7a02926e](https://linux-hardware.org/?probe=6e7a02926e) | Nov 12, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [582c75cc01](https://linux-hardware.org/?probe=582c75cc01) | Nov 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [467624f847](https://linux-hardware.org/?probe=467624f847) | Nov 08, 2024 |
| AXIOO         | Mybook-14E                  | Notebook    | [32f6d232e2](https://linux-hardware.org/?probe=32f6d232e2) | Nov 07, 2024 |
| Unknown       | G41 A01                     | Desktop     | [b2d92f4da8](https://linux-hardware.org/?probe=b2d92f4da8) | Nov 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [2be2989e95](https://linux-hardware.org/?probe=2be2989e95) | Nov 05, 2024 |
| ASUSTek       | TP300LD                     | Notebook    | [3a6d49031d](https://linux-hardware.org/?probe=3a6d49031d) | Nov 04, 2024 |
| ASUSTek       | TP300LD                     | Notebook    | [551c5bff17](https://linux-hardware.org/?probe=551c5bff17) | Nov 03, 2024 |
| Acer          | Aspire A314-42P             | Notebook    | [3b985cceae](https://linux-hardware.org/?probe=3b985cceae) | Nov 03, 2024 |
| Acer          | Nitro ANV15-51              | Notebook    | [c135e3383d](https://linux-hardware.org/?probe=c135e3383d) | Nov 03, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0c49f1f721](https://linux-hardware.org/?probe=0c49f1f721) | Nov 03, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [1e174054d4](https://linux-hardware.org/?probe=1e174054d4) | Nov 01, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [e49936d823](https://linux-hardware.org/?probe=e49936d823) | Nov 01, 2024 |
| Intel         | H61                         | Desktop     | [0e1936ef18](https://linux-hardware.org/?probe=0e1936ef18) | Oct 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e9762f3377](https://linux-hardware.org/?probe=e9762f3377) | Oct 31, 2024 |
| ASUSTek       | K46CB                       | Notebook    | [e081c9ab8c](https://linux-hardware.org/?probe=e081c9ab8c) | Oct 30, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [ef419e7dda](https://linux-hardware.org/?probe=ef419e7dda) | Oct 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d46929135e](https://linux-hardware.org/?probe=d46929135e) | Oct 25, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [5dc0afb6b3](https://linux-hardware.org/?probe=5dc0afb6b3) | Oct 24, 2024 |
| HP            | G60                         | Notebook    | [34dc5984dc](https://linux-hardware.org/?probe=34dc5984dc) | Oct 23, 2024 |
| ASUSTek       | X441UV                      | Notebook    | [d5527bcd69](https://linux-hardware.org/?probe=d5527bcd69) | Oct 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2b9158e95b](https://linux-hardware.org/?probe=2b9158e95b) | Oct 22, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [1e81679f39](https://linux-hardware.org/?probe=1e81679f39) | Oct 22, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [cfd54e896b](https://linux-hardware.org/?probe=cfd54e896b) | Oct 22, 2024 |
| Lenovo        | ThinkPad X230 2325YF3       | Notebook    | [b10ade1b28](https://linux-hardware.org/?probe=b10ade1b28) | Oct 19, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7d19f92203](https://linux-hardware.org/?probe=7d19f92203) | Oct 18, 2024 |
| Microsoft     | Surface Book 2              | Tablet      | [58861dc8f9](https://linux-hardware.org/?probe=58861dc8f9) | Oct 17, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | Notebook    | [a15c3e921c](https://linux-hardware.org/?probe=a15c3e921c) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | Notebook    | [d8b92ea891](https://linux-hardware.org/?probe=d8b92ea891) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | Notebook    | [b99b7f9e7a](https://linux-hardware.org/?probe=b99b7f9e7a) | Oct 16, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [fe47439b78](https://linux-hardware.org/?probe=fe47439b78) | Oct 15, 2024 |
| Acer          | Aspire A314-32              | Notebook    | [f0e0f318dd](https://linux-hardware.org/?probe=f0e0f318dd) | Oct 14, 2024 |
| HP            | 89B3 A                      | Desktop     | [95660e69d1](https://linux-hardware.org/?probe=95660e69d1) | Oct 12, 2024 |
| Lenovo        | ThinkPad L512 4444PL4       | Notebook    | [2df5620570](https://linux-hardware.org/?probe=2df5620570) | Oct 12, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [bcada5cbe6](https://linux-hardware.org/?probe=bcada5cbe6) | Oct 10, 2024 |
| HP            | 2B12                        | Desktop     | [dc89c52ca5](https://linux-hardware.org/?probe=dc89c52ca5) | Oct 10, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [7bf1c31e28](https://linux-hardware.org/?probe=7bf1c31e28) | Oct 10, 2024 |
| HP            | 2B12                        | Desktop     | [af8c8f5046](https://linux-hardware.org/?probe=af8c8f5046) | Oct 09, 2024 |
| ASRock        | H170 Performance            | Desktop     | [333e0c72e5](https://linux-hardware.org/?probe=333e0c72e5) | Oct 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b02ac16d4e](https://linux-hardware.org/?probe=b02ac16d4e) | Oct 08, 2024 |
| HP            | Laptop 14-em0xxx            | Notebook    | [f0fb885887](https://linux-hardware.org/?probe=f0fb885887) | Oct 07, 2024 |
| ASUSTek       | X555DG                      | Notebook    | [c602f86121](https://linux-hardware.org/?probe=c602f86121) | Oct 06, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [b1fff870c3](https://linux-hardware.org/?probe=b1fff870c3) | Oct 05, 2024 |
| Dell          | Inspiron 5379               | Notebook    | [d4ec7c3588](https://linux-hardware.org/?probe=d4ec7c3588) | Oct 05, 2024 |
| Intel         | H81                         | Desktop     | [9792775b83](https://linux-hardware.org/?probe=9792775b83) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [ba0935bde6](https://linux-hardware.org/?probe=ba0935bde6) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | Notebook    | [f3c50b490a](https://linux-hardware.org/?probe=f3c50b490a) | Oct 05, 2024 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [cd6776c30a](https://linux-hardware.org/?probe=cd6776c30a) | Oct 04, 2024 |
| Unknown       | Unknown                     | Notebook    | [cb3c212bc9](https://linux-hardware.org/?probe=cb3c212bc9) | Oct 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8f6ef31fc0](https://linux-hardware.org/?probe=8f6ef31fc0) | Oct 01, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [605995ef0d](https://linux-hardware.org/?probe=605995ef0d) | Oct 01, 2024 |
| Dell          | Latitude 3420               | Notebook    | [d7672fb8f4](https://linux-hardware.org/?probe=d7672fb8f4) | Sep 29, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [8815e16a5e](https://linux-hardware.org/?probe=8815e16a5e) | Sep 29, 2024 |
| Acer          | Okinawa                     | Notebook    | [dd1134eda8](https://linux-hardware.org/?probe=dd1134eda8) | Sep 28, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [2b9c6f05fe](https://linux-hardware.org/?probe=2b9c6f05fe) | Sep 28, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [5adcba6b0e](https://linux-hardware.org/?probe=5adcba6b0e) | Sep 27, 2024 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [7b4b348c98](https://linux-hardware.org/?probe=7b4b348c98) | Sep 27, 2024 |
| Google        | Fleex                       | Notebook    | [05a6990467](https://linux-hardware.org/?probe=05a6990467) | Sep 27, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | Notebook    | [fe8af671af](https://linux-hardware.org/?probe=fe8af671af) | Sep 26, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [24a8743042](https://linux-hardware.org/?probe=24a8743042) | Sep 24, 2024 |
| Intel         | B75                         | Desktop     | [17dd91b6f2](https://linux-hardware.org/?probe=17dd91b6f2) | Sep 24, 2024 |
| Dell          | Inspiron 5491 2n1           | Convertible | [8dda5a0bc7](https://linux-hardware.org/?probe=8dda5a0bc7) | Sep 23, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [fd06da7fc1](https://linux-hardware.org/?probe=fd06da7fc1) | Sep 22, 2024 |
| Lenovo        | ThinkPad X100e 2876CTO      | Notebook    | [7282bf9e1e](https://linux-hardware.org/?probe=7282bf9e1e) | Sep 22, 2024 |
| Dell          | Latitude 3420               | Notebook    | [91dbcf2851](https://linux-hardware.org/?probe=91dbcf2851) | Sep 21, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [7259f3460a](https://linux-hardware.org/?probe=7259f3460a) | Sep 21, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [126bd31450](https://linux-hardware.org/?probe=126bd31450) | Sep 20, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [96ebcfea10](https://linux-hardware.org/?probe=96ebcfea10) | Sep 18, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | Notebook    | [ffe3da2a61](https://linux-hardware.org/?probe=ffe3da2a61) | Sep 17, 2024 |
| AXIOO         | MyBook Hype 5               | Notebook    | [d6b2a6bbbe](https://linux-hardware.org/?probe=d6b2a6bbbe) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b105d16e70](https://linux-hardware.org/?probe=b105d16e70) | Sep 13, 2024 |
| Dell          | Latitude E7250              | Notebook    | [f5079722a9](https://linux-hardware.org/?probe=f5079722a9) | Sep 11, 2024 |
| Lenovo        | ThinkPad T480s 20L8S6360... | Notebook    | [488ff39e81](https://linux-hardware.org/?probe=488ff39e81) | Sep 10, 2024 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [5645aa8848](https://linux-hardware.org/?probe=5645aa8848) | Sep 05, 2024 |
| Dell          | XPS 9320                    | Notebook    | [27298b827b](https://linux-hardware.org/?probe=27298b827b) | Sep 03, 2024 |
| AYANEO        | GEEK                        | Tablet      | [33569d4ee1](https://linux-hardware.org/?probe=33569d4ee1) | Sep 03, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ab21866554](https://linux-hardware.org/?probe=ab21866554) | Sep 03, 2024 |
| ASUSTek       | E5402WHA                    | All in one  | [f9654565db](https://linux-hardware.org/?probe=f9654565db) | Sep 02, 2024 |
| Gigabyte      | G31M-S2C                    | Desktop     | [29671c0af6](https://linux-hardware.org/?probe=29671c0af6) | Sep 02, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [45cfeca88a](https://linux-hardware.org/?probe=45cfeca88a) | Aug 31, 2024 |
| AXIOO         | PICO CJW                    | Notebook    | [3c7b0a8d95](https://linux-hardware.org/?probe=3c7b0a8d95) | Aug 31, 2024 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [b0e323ae58](https://linux-hardware.org/?probe=b0e323ae58) | Aug 31, 2024 |
| AXIOO         | PICO CJW                    | Notebook    | [6ba416a56c](https://linux-hardware.org/?probe=6ba416a56c) | Aug 31, 2024 |
| Gigabyte      | P55-UD3P                    | Desktop     | [80da5ed3a8](https://linux-hardware.org/?probe=80da5ed3a8) | Aug 29, 2024 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [8886ae523e](https://linux-hardware.org/?probe=8886ae523e) | Aug 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [5502afcee2](https://linux-hardware.org/?probe=5502afcee2) | Aug 29, 2024 |
| ASUSTek       | K30AM-J                     | Desktop     | [912c2ae503](https://linux-hardware.org/?probe=912c2ae503) | Aug 29, 2024 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [7dfa339f21](https://linux-hardware.org/?probe=7dfa339f21) | Aug 29, 2024 |
| ASUSTek       | X455LF                      | Notebook    | [2ebd2ae224](https://linux-hardware.org/?probe=2ebd2ae224) | Aug 28, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [9d5c4db3d1](https://linux-hardware.org/?probe=9d5c4db3d1) | Aug 27, 2024 |
| Acer          | Aspire 4743                 | Notebook    | [2407fc17fc](https://linux-hardware.org/?probe=2407fc17fc) | Aug 27, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ae159e1811](https://linux-hardware.org/?probe=ae159e1811) | Aug 27, 2024 |
| PT. Zyrexi... | Zyrex Notebook Cruiser 2... | Convertible | [4c1b9f22d2](https://linux-hardware.org/?probe=4c1b9f22d2) | Aug 24, 2024 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [98393b8796](https://linux-hardware.org/?probe=98393b8796) | Aug 23, 2024 |
| Dell          | Latitude 14 Rugged (5404... | Notebook    | [8457bf32ea](https://linux-hardware.org/?probe=8457bf32ea) | Aug 23, 2024 |
| Dell          | Latitude 3410               | Notebook    | [0b09307b53](https://linux-hardware.org/?probe=0b09307b53) | Aug 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [59afcb4476](https://linux-hardware.org/?probe=59afcb4476) | Aug 21, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [6ce7717ab8](https://linux-hardware.org/?probe=6ce7717ab8) | Aug 20, 2024 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [dd86f2e3f4](https://linux-hardware.org/?probe=dd86f2e3f4) | Aug 20, 2024 |
| Toshiba       | TECRA Z40-A                 | Notebook    | [24e6b94f55](https://linux-hardware.org/?probe=24e6b94f55) | Aug 20, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [571b1e7cf5](https://linux-hardware.org/?probe=571b1e7cf5) | Aug 20, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ca11b9e447](https://linux-hardware.org/?probe=ca11b9e447) | Aug 20, 2024 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [c395b3e28c](https://linux-hardware.org/?probe=c395b3e28c) | Aug 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0b49e3d246](https://linux-hardware.org/?probe=0b49e3d246) | Aug 16, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [39611ab403](https://linux-hardware.org/?probe=39611ab403) | Aug 16, 2024 |
| Lenovo        | ThinkPad X240 20AMA3AECD    | Notebook    | [ca3f5f8a59](https://linux-hardware.org/?probe=ca3f5f8a59) | Aug 15, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [54b3658243](https://linux-hardware.org/?probe=54b3658243) | Aug 15, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [0e2d15df7c](https://linux-hardware.org/?probe=0e2d15df7c) | Aug 15, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [2a780be401](https://linux-hardware.org/?probe=2a780be401) | Aug 14, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [aee1dc9bfe](https://linux-hardware.org/?probe=aee1dc9bfe) | Aug 13, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [e322a156a0](https://linux-hardware.org/?probe=e322a156a0) | Aug 13, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [fe32237e3a](https://linux-hardware.org/?probe=fe32237e3a) | Aug 12, 2024 |
| Gigabyte      | B75M-HD3                    | Desktop     | [39efa072bc](https://linux-hardware.org/?probe=39efa072bc) | Aug 12, 2024 |
| ASUSTek       | H61M-E                      | Desktop     | [c18e02345c](https://linux-hardware.org/?probe=c18e02345c) | Aug 12, 2024 |
| HP            | 198E                        | Desktop     | [21d03f44b1](https://linux-hardware.org/?probe=21d03f44b1) | Aug 11, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [f11d04ee8e](https://linux-hardware.org/?probe=f11d04ee8e) | Aug 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [e6c64713c1](https://linux-hardware.org/?probe=e6c64713c1) | Aug 08, 2024 |
| HP            | Compaq 435                  | Notebook    | [4911c70481](https://linux-hardware.org/?probe=4911c70481) | Aug 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [6afe9c392f](https://linux-hardware.org/?probe=6afe9c392f) | Aug 04, 2024 |
| Intel         | H110 Series                 | Desktop     | [ba2023d022](https://linux-hardware.org/?probe=ba2023d022) | Aug 03, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [ffa298e6de](https://linux-hardware.org/?probe=ffa298e6de) | Aug 03, 2024 |
| Intel         | DH61WW AAG23116-303         | Desktop     | [f46309dc1c](https://linux-hardware.org/?probe=f46309dc1c) | Aug 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [1bae3fe2d4](https://linux-hardware.org/?probe=1bae3fe2d4) | Aug 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [058fa0e4aa](https://linux-hardware.org/?probe=058fa0e4aa) | Aug 01, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0d84b625a7](https://linux-hardware.org/?probe=0d84b625a7) | Jul 30, 2024 |
| ASUSTek       | H61M-E                      | Desktop     | [368a1a7088](https://linux-hardware.org/?probe=368a1a7088) | Jul 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [1329ba82ac](https://linux-hardware.org/?probe=1329ba82ac) | Jul 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [637e807f6a](https://linux-hardware.org/?probe=637e807f6a) | Jul 28, 2024 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [2e993c4215](https://linux-hardware.org/?probe=2e993c4215) | Jul 27, 2024 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [a9d457cbfe](https://linux-hardware.org/?probe=a9d457cbfe) | Jul 27, 2024 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [0dbc5b0c8a](https://linux-hardware.org/?probe=0dbc5b0c8a) | Jul 26, 2024 |
| HP            | ProBook 440 G4              | Notebook    | [a2ffdc1d34](https://linux-hardware.org/?probe=a2ffdc1d34) | Jul 26, 2024 |
| Dell          | Inspiron 14-3462            | Notebook    | [13234332e1](https://linux-hardware.org/?probe=13234332e1) | Jul 25, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [67670a0f4a](https://linux-hardware.org/?probe=67670a0f4a) | Jul 25, 2024 |
| Valve         | Jupiter                     | Notebook    | [79e199cee3](https://linux-hardware.org/?probe=79e199cee3) | Jul 24, 2024 |
| MSI           | B550M PRO-VDH               | Desktop     | [e20f83dc61](https://linux-hardware.org/?probe=e20f83dc61) | Jul 23, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e09128a4ab](https://linux-hardware.org/?probe=e09128a4ab) | Jul 22, 2024 |
| HP            | 14                          | Notebook    | [f418deebad](https://linux-hardware.org/?probe=f418deebad) | Jul 22, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L1400CDA... | Notebook    | [0ff73e973a](https://linux-hardware.org/?probe=0ff73e973a) | Jul 22, 2024 |
| Lenovo        | ThinkPad X230 2306A27       | Notebook    | [07e6f1b674](https://linux-hardware.org/?probe=07e6f1b674) | Jul 22, 2024 |
| Toshiba       | Satellite L510              | Notebook    | [97e25526be](https://linux-hardware.org/?probe=97e25526be) | Jul 21, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [2baabb5540](https://linux-hardware.org/?probe=2baabb5540) | Jul 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de93837a91](https://linux-hardware.org/?probe=de93837a91) | Jul 20, 2024 |
| Intel         | H61                         | Desktop     | [79cbc35474](https://linux-hardware.org/?probe=79cbc35474) | Jul 20, 2024 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [12bf57a78e](https://linux-hardware.org/?probe=12bf57a78e) | Jul 19, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [04a35f754e](https://linux-hardware.org/?probe=04a35f754e) | Jul 17, 2024 |
| ADVAN         | 1405                        | Notebook    | [fd0d652727](https://linux-hardware.org/?probe=fd0d652727) | Jul 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP34... | Convertible | [b32ef428be](https://linux-hardware.org/?probe=b32ef428be) | Jul 16, 2024 |
| Toshiba       | Satellite L645              | Notebook    | [7c46019cc3](https://linux-hardware.org/?probe=7c46019cc3) | Jul 16, 2024 |
| ASUSTek       | X455LJ                      | Notebook    | [560bb80195](https://linux-hardware.org/?probe=560bb80195) | Jul 15, 2024 |
| ASUSTek       | X455LJ                      | Notebook    | [6364ad10c5](https://linux-hardware.org/?probe=6364ad10c5) | Jul 15, 2024 |
| Acer          | Aspire E5-475G              | Notebook    | [18965ce4ea](https://linux-hardware.org/?probe=18965ce4ea) | Jul 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S1F20F    | Notebook    | [b9445ad087](https://linux-hardware.org/?probe=b9445ad087) | Jul 15, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | Notebook    | [9033123c38](https://linux-hardware.org/?probe=9033123c38) | Jul 15, 2024 |
| HP            | Laptop 14-bs1xx             | Notebook    | [cf4f3c0bb8](https://linux-hardware.org/?probe=cf4f3c0bb8) | Jul 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5482a0b3dc](https://linux-hardware.org/?probe=5482a0b3dc) | Jul 15, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [a7d115c7d5](https://linux-hardware.org/?probe=a7d115c7d5) | Jul 15, 2024 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [8e7672b34e](https://linux-hardware.org/?probe=8e7672b34e) | Jul 14, 2024 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [39b464c39e](https://linux-hardware.org/?probe=39b464c39e) | Jul 14, 2024 |
| HP            | Notebook                    | Notebook    | [76d1a8c671](https://linux-hardware.org/?probe=76d1a8c671) | Jul 14, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [d9aeff835a](https://linux-hardware.org/?probe=d9aeff835a) | Jul 13, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [a87baa98b1](https://linux-hardware.org/?probe=a87baa98b1) | Jul 11, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0837d07786](https://linux-hardware.org/?probe=0837d07786) | Jul 11, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c5a2c8ebb0](https://linux-hardware.org/?probe=c5a2c8ebb0) | Jul 09, 2024 |
| ASRock        | B650M PG Lightning          | Desktop     | [94eff09933](https://linux-hardware.org/?probe=94eff09933) | Jul 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [4da248e266](https://linux-hardware.org/?probe=4da248e266) | Jul 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [5c863e0d7c](https://linux-hardware.org/?probe=5c863e0d7c) | Jul 08, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [79a2ee9967](https://linux-hardware.org/?probe=79a2ee9967) | Jul 07, 2024 |
| HP            | Pavilion g4                 | Notebook    | [7dc29fa0b4](https://linux-hardware.org/?probe=7dc29fa0b4) | Jul 07, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [c5062c2b4e](https://linux-hardware.org/?probe=c5062c2b4e) | Jul 07, 2024 |
| ECS           | H61H2-M12                   | Desktop     | [7bcab0a14c](https://linux-hardware.org/?probe=7bcab0a14c) | Jul 07, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [7910b13b30](https://linux-hardware.org/?probe=7910b13b30) | Jul 06, 2024 |
| ASUSTek       | X201EV                      | Notebook    | [f02eb29877](https://linux-hardware.org/?probe=f02eb29877) | Jul 06, 2024 |
| Panasonic     | CFSZ6-2                     | Notebook    | [09991bde50](https://linux-hardware.org/?probe=09991bde50) | Jul 06, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [5988ce94ee](https://linux-hardware.org/?probe=5988ce94ee) | Jul 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [9d7278dbe4](https://linux-hardware.org/?probe=9d7278dbe4) | Jul 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [54e71c6699](https://linux-hardware.org/?probe=54e71c6699) | Jul 06, 2024 |
| Gigabyte      | 970A-D3P                    | Desktop     | [1aba817d5d](https://linux-hardware.org/?probe=1aba817d5d) | Jul 05, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | Notebook    | [5b5cf02ccc](https://linux-hardware.org/?probe=5b5cf02ccc) | Jul 05, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [6e79e0bd1e](https://linux-hardware.org/?probe=6e79e0bd1e) | Jul 04, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [83aba2641e](https://linux-hardware.org/?probe=83aba2641e) | Jul 04, 2024 |
| HP            | 8169                        | Desktop     | [c45572c08d](https://linux-hardware.org/?probe=c45572c08d) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [a12c62a640](https://linux-hardware.org/?probe=a12c62a640) | Jul 04, 2024 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [2e09a7f7bd](https://linux-hardware.org/?probe=2e09a7f7bd) | Jul 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9f0a26445e](https://linux-hardware.org/?probe=9f0a26445e) | Jul 04, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [16545a1d8f](https://linux-hardware.org/?probe=16545a1d8f) | Jul 02, 2024 |
| ADVAN         | 1701                        | Notebook    | [74128c428a](https://linux-hardware.org/?probe=74128c428a) | Jul 01, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [68fff6c23b](https://linux-hardware.org/?probe=68fff6c23b) | Jul 01, 2024 |
| Dell          | 0Y2MRG A00                  | Desktop     | [cab50448b9](https://linux-hardware.org/?probe=cab50448b9) | Jun 30, 2024 |
| Lenovo        | ThinkPad T520 423953J       | Notebook    | [01e5062809](https://linux-hardware.org/?probe=01e5062809) | Jun 29, 2024 |
| ASRock        | X370M Pro4                  | Desktop     | [65e29ff944](https://linux-hardware.org/?probe=65e29ff944) | Jun 29, 2024 |
| HP            | 87F3 0100                   | All in one  | [5738460f11](https://linux-hardware.org/?probe=5738460f11) | Jun 28, 2024 |
| ADVAN         | 1701                        | Notebook    | [983e29b86d](https://linux-hardware.org/?probe=983e29b86d) | Jun 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [6dd3ef98e9](https://linux-hardware.org/?probe=6dd3ef98e9) | Jun 26, 2024 |
| AVITA         | NE14A2                      | Notebook    | [36e93c620c](https://linux-hardware.org/?probe=36e93c620c) | Jun 25, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [4d278d12d7](https://linux-hardware.org/?probe=4d278d12d7) | Jun 25, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [186d1f827c](https://linux-hardware.org/?probe=186d1f827c) | Jun 24, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [ab244cc45f](https://linux-hardware.org/?probe=ab244cc45f) | Jun 24, 2024 |
| Valve         | Jupiter                     | Notebook    | [49ade9d97b](https://linux-hardware.org/?probe=49ade9d97b) | Jun 24, 2024 |
| Acer          | Aspire MC605 v1.0           | Desktop     | [412057df6b](https://linux-hardware.org/?probe=412057df6b) | Jun 23, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [347663d539](https://linux-hardware.org/?probe=347663d539) | Jun 23, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | Notebook    | [52e6290d5d](https://linux-hardware.org/?probe=52e6290d5d) | Jun 20, 2024 |
| Dell          | 0D24M8 A01                  | Desktop     | [2cdf2b71a1](https://linux-hardware.org/?probe=2cdf2b71a1) | Jun 20, 2024 |
| Lenovo        | ThinkPad L570 20J9S34000    | Notebook    | [a600d8246f](https://linux-hardware.org/?probe=a600d8246f) | Jun 18, 2024 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [9726e3b312](https://linux-hardware.org/?probe=9726e3b312) | Jun 17, 2024 |
| Valve         | Jupiter                     | Notebook    | [f2f1d90b24](https://linux-hardware.org/?probe=f2f1d90b24) | Jun 16, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | Notebook    | [66051331fd](https://linux-hardware.org/?probe=66051331fd) | Jun 11, 2024 |
| TriGem Com... | H61H2-TM7                   | Desktop     | [7deb9d1c5a](https://linux-hardware.org/?probe=7deb9d1c5a) | Jun 11, 2024 |
| Toshiba       | dynabook R734/M             | Notebook    | [c8a799a398](https://linux-hardware.org/?probe=c8a799a398) | Jun 10, 2024 |
| HP            | Notebook                    | Notebook    | [4bbae416f7](https://linux-hardware.org/?probe=4bbae416f7) | Jun 09, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [d66cae1613](https://linux-hardware.org/?probe=d66cae1613) | Jun 08, 2024 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [fd48784b0f](https://linux-hardware.org/?probe=fd48784b0f) | Jun 08, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6cf80a06d1](https://linux-hardware.org/?probe=6cf80a06d1) | Jun 07, 2024 |
| AIO           | DynaBook e5                 | Notebook    | [0e4ad04db5](https://linux-hardware.org/?probe=0e4ad04db5) | Jun 06, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [9d0db9afbe](https://linux-hardware.org/?probe=9d0db9afbe) | Jun 06, 2024 |
| Unknown       | G41 Series                  | Desktop     | [f9b4dbc607](https://linux-hardware.org/?probe=f9b4dbc607) | Jun 05, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [be344b10dc](https://linux-hardware.org/?probe=be344b10dc) | Jun 05, 2024 |
| Toshiba       | dynabook R734/M             | Notebook    | [f539a0d213](https://linux-hardware.org/?probe=f539a0d213) | Jun 04, 2024 |
| Acer          | Veriton L4620G v1.0         | Desktop     | [24db2893da](https://linux-hardware.org/?probe=24db2893da) | Jun 04, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [00dc39a0b7](https://linux-hardware.org/?probe=00dc39a0b7) | Jun 03, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [0941f7e44b](https://linux-hardware.org/?probe=0941f7e44b) | Jun 03, 2024 |
| Toshiba       | dynabook R731/C             | Notebook    | [e8f41ce95d](https://linux-hardware.org/?probe=e8f41ce95d) | Jun 02, 2024 |
| Toshiba       | dynabook R731/C             | Notebook    | [421ef5ca84](https://linux-hardware.org/?probe=421ef5ca84) | Jun 02, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [e29deb87ee](https://linux-hardware.org/?probe=e29deb87ee) | May 28, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [060ce09ffd](https://linux-hardware.org/?probe=060ce09ffd) | May 27, 2024 |
| Toshiba       | Satellite L740              | Notebook    | [af075df4bd](https://linux-hardware.org/?probe=af075df4bd) | May 25, 2024 |
| ASUSTek       | X200CA                      | Notebook    | [b4af45240b](https://linux-hardware.org/?probe=b4af45240b) | May 25, 2024 |
| Panasonic     | CFSZ5-2                     | Notebook    | [dd94dab0da](https://linux-hardware.org/?probe=dd94dab0da) | May 24, 2024 |
| Toshiba       | Satellite L740              | Notebook    | [471713a2b2](https://linux-hardware.org/?probe=471713a2b2) | May 24, 2024 |
| Chuwi         | FreeBook                    | Notebook    | [6cd2de3abd](https://linux-hardware.org/?probe=6cd2de3abd) | May 23, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [ba3f755558](https://linux-hardware.org/?probe=ba3f755558) | May 23, 2024 |
| Acer          | Swift SF313-51              | Notebook    | [80ad889357](https://linux-hardware.org/?probe=80ad889357) | May 20, 2024 |
| Acer          | Swift SF313-51              | Notebook    | [79d8372cf3](https://linux-hardware.org/?probe=79d8372cf3) | May 20, 2024 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [0c62b9f67c](https://linux-hardware.org/?probe=0c62b9f67c) | May 20, 2024 |
| Acer          | Aspire E5-471G              | Notebook    | [6ad4e168d9](https://linux-hardware.org/?probe=6ad4e168d9) | May 20, 2024 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [c761a6d766](https://linux-hardware.org/?probe=c761a6d766) | May 19, 2024 |
| AIO           | DynaBook e5                 | Notebook    | [061663a80d](https://linux-hardware.org/?probe=061663a80d) | May 15, 2024 |
| Dell          | 0JH35T A00                  | Mini pc     | [b82c8fc7c5](https://linux-hardware.org/?probe=b82c8fc7c5) | May 15, 2024 |
| Lenovo        | ThinkPad X200 MFG_IN       | Notebook    | [2cd87a7d08](https://linux-hardware.org/?probe=2cd87a7d08) | May 14, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [bda1d0daa6](https://linux-hardware.org/?probe=bda1d0daa6) | May 13, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4f54cca705](https://linux-hardware.org/?probe=4f54cca705) | May 12, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [5dbd877390](https://linux-hardware.org/?probe=5dbd877390) | May 12, 2024 |
| HP            | Pavilion g4                 | Notebook    | [e4d725eba3](https://linux-hardware.org/?probe=e4d725eba3) | May 11, 2024 |
| Acer          | Aspire E5-411G              | Notebook    | [82675c702e](https://linux-hardware.org/?probe=82675c702e) | May 10, 2024 |
| HP            | Laptop 14-bw0xx             | Notebook    | [33b98e985f](https://linux-hardware.org/?probe=33b98e985f) | May 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10c139f22b](https://linux-hardware.org/?probe=10c139f22b) | May 08, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [73ee3d2b74](https://linux-hardware.org/?probe=73ee3d2b74) | May 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [0ef70379ee](https://linux-hardware.org/?probe=0ef70379ee) | May 07, 2024 |
| ADVAN         | 1701                        | Notebook    | [e0928a1604](https://linux-hardware.org/?probe=e0928a1604) | May 06, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [7ad59bc402](https://linux-hardware.org/?probe=7ad59bc402) | May 05, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [a88155be11](https://linux-hardware.org/?probe=a88155be11) | May 05, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [80f71c25c1](https://linux-hardware.org/?probe=80f71c25c1) | May 05, 2024 |
| Unknown       | G41 A01                     | Desktop     | [537cc137bd](https://linux-hardware.org/?probe=537cc137bd) | May 04, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [e200a00e5a](https://linux-hardware.org/?probe=e200a00e5a) | May 02, 2024 |
| realme        | CloudProXXXX                | Notebook    | [4a04219fcc](https://linux-hardware.org/?probe=4a04219fcc) | May 01, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [29d73efd4a](https://linux-hardware.org/?probe=29d73efd4a) | Apr 30, 2024 |
| ASUSTek       | X202E                       | Notebook    | [f782bac9e8](https://linux-hardware.org/?probe=f782bac9e8) | Apr 28, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [309c38a064](https://linux-hardware.org/?probe=309c38a064) | Apr 22, 2024 |
| ASUSTek       | X441SA                      | Notebook    | [4ebc6f3907](https://linux-hardware.org/?probe=4ebc6f3907) | Apr 22, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [802dfe39ec](https://linux-hardware.org/?probe=802dfe39ec) | Apr 20, 2024 |
| Acer          | Aspire A314-22              | Notebook    | [cb041e53b1](https://linux-hardware.org/?probe=cb041e53b1) | Apr 20, 2024 |
| ADVAN         | 1701                        | Notebook    | [a55c0ef710](https://linux-hardware.org/?probe=a55c0ef710) | Apr 19, 2024 |
| AXIOO         | NEON RNE                    | Notebook    | [a9f58cb42f](https://linux-hardware.org/?probe=a9f58cb42f) | Apr 16, 2024 |
| AXIOO         | NEON RNE                    | Notebook    | [e650f6d340](https://linux-hardware.org/?probe=e650f6d340) | Apr 16, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [97e9e0c7a1](https://linux-hardware.org/?probe=97e9e0c7a1) | Apr 13, 2024 |
| Lenovo        | 3306 SDK0T76528 WIN 3556... | All in one  | [06b63083c7](https://linux-hardware.org/?probe=06b63083c7) | Apr 10, 2024 |
| ASUSTek       | GL502VMZ                    | Notebook    | [6b670ef81e](https://linux-hardware.org/?probe=6b670ef81e) | Apr 10, 2024 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [74499eab00](https://linux-hardware.org/?probe=74499eab00) | Apr 07, 2024 |
| Dell          | Latitude 7400               | Notebook    | [063a09c041](https://linux-hardware.org/?probe=063a09c041) | Apr 05, 2024 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [285b9be78c](https://linux-hardware.org/?probe=285b9be78c) | Apr 05, 2024 |
| Dell          | 0C1GJ7 A00                  | All in one  | [f501017a54](https://linux-hardware.org/?probe=f501017a54) | Apr 04, 2024 |
| ASUSTek       | X456UQ                      | Notebook    | [e7ae74a0ed](https://linux-hardware.org/?probe=e7ae74a0ed) | Apr 03, 2024 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [9bda4cf2a7](https://linux-hardware.org/?probe=9bda4cf2a7) | Apr 01, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [1e27980b1d](https://linux-hardware.org/?probe=1e27980b1d) | Apr 01, 2024 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [d9af69f439](https://linux-hardware.org/?probe=d9af69f439) | Apr 01, 2024 |
| ASUSTek       | K46CM                       | Notebook    | [81723c2d41](https://linux-hardware.org/?probe=81723c2d41) | Mar 27, 2024 |
| Intel         | H81                         | Desktop     | [e734609a4c](https://linux-hardware.org/?probe=e734609a4c) | Mar 26, 2024 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [d71f48c168](https://linux-hardware.org/?probe=d71f48c168) | Mar 25, 2024 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [208a49a1cc](https://linux-hardware.org/?probe=208a49a1cc) | Mar 24, 2024 |
| ECS           | H61H2-MV                    | Desktop     | [2ab5b82fb2](https://linux-hardware.org/?probe=2ab5b82fb2) | Mar 21, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [dbb5c1fe9f](https://linux-hardware.org/?probe=dbb5c1fe9f) | Mar 20, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [03556f08ce](https://linux-hardware.org/?probe=03556f08ce) | Mar 19, 2024 |
| HP            | Pavilion 15                 | Notebook    | [a9bc9facce](https://linux-hardware.org/?probe=a9bc9facce) | Mar 19, 2024 |
| ASRock        | B550M Steel Legend          | Desktop     | [a1762528fb](https://linux-hardware.org/?probe=a1762528fb) | Mar 17, 2024 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [a781e10290](https://linux-hardware.org/?probe=a781e10290) | Mar 16, 2024 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [0018e3e74d](https://linux-hardware.org/?probe=0018e3e74d) | Mar 16, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c63d09f5fa](https://linux-hardware.org/?probe=c63d09f5fa) | Mar 15, 2024 |
| Google        | Coral                       | Notebook    | [415209f979](https://linux-hardware.org/?probe=415209f979) | Mar 15, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [3f7ac15be0](https://linux-hardware.org/?probe=3f7ac15be0) | Mar 15, 2024 |
| Dell          | Latitude 7480               | Notebook    | [13613ddbb8](https://linux-hardware.org/?probe=13613ddbb8) | Mar 14, 2024 |
| HP            | 248 G1                      | Notebook    | [918afcb1a0](https://linux-hardware.org/?probe=918afcb1a0) | Mar 07, 2024 |
| ADVAN         | 1405                        | Notebook    | [f11d45ddde](https://linux-hardware.org/?probe=f11d45ddde) | Mar 07, 2024 |
| AIO           | DynaBook e5                 | Notebook    | [877e963f0b](https://linux-hardware.org/?probe=877e963f0b) | Mar 06, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d9770af085](https://linux-hardware.org/?probe=d9770af085) | Mar 06, 2024 |
| ASUSTek       | X453MA                      | Notebook    | [e1e03429e2](https://linux-hardware.org/?probe=e1e03429e2) | Mar 05, 2024 |
| Intel         | H61                         | Desktop     | [2577e168b3](https://linux-hardware.org/?probe=2577e168b3) | Mar 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b11673c68a](https://linux-hardware.org/?probe=b11673c68a) | Mar 05, 2024 |
| HP            | 240 G7 Notebook PC          | Notebook    | [7556bb7dcb](https://linux-hardware.org/?probe=7556bb7dcb) | Mar 04, 2024 |
| ADVAN         | 1701                        | Notebook    | [c956a2409c](https://linux-hardware.org/?probe=c956a2409c) | Mar 03, 2024 |
| Intel         | H81                         | Desktop     | [4f0a4894dc](https://linux-hardware.org/?probe=4f0a4894dc) | Mar 03, 2024 |
| AIO           | DynaBook e5                 | Notebook    | [733a714da6](https://linux-hardware.org/?probe=733a714da6) | Mar 02, 2024 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [223fbfa988](https://linux-hardware.org/?probe=223fbfa988) | Feb 29, 2024 |
| Dell          | Latitude 7300               | Notebook    | [21fe8b5d70](https://linux-hardware.org/?probe=21fe8b5d70) | Feb 29, 2024 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [a685c7e5d5](https://linux-hardware.org/?probe=a685c7e5d5) | Feb 28, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [385221c459](https://linux-hardware.org/?probe=385221c459) | Feb 28, 2024 |
| Lenovo        | 3102 NOK                    | Desktop     | [b343ea038a](https://linux-hardware.org/?probe=b343ea038a) | Feb 27, 2024 |
| Intel         | intibook                    | Notebook    | [7668db4bcd](https://linux-hardware.org/?probe=7668db4bcd) | Feb 27, 2024 |
| ASUSTek       | X441UA                      | Notebook    | [1185900ace](https://linux-hardware.org/?probe=1185900ace) | Feb 26, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [df12996678](https://linux-hardware.org/?probe=df12996678) | Feb 25, 2024 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4dd27fbd4e](https://linux-hardware.org/?probe=4dd27fbd4e) | Feb 23, 2024 |
| Dell          | Vostro 1014                 | Notebook    | [5fcabcc564](https://linux-hardware.org/?probe=5fcabcc564) | Feb 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [da357b8940](https://linux-hardware.org/?probe=da357b8940) | Feb 22, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [627c4721b6](https://linux-hardware.org/?probe=627c4721b6) | Feb 21, 2024 |
| ASUSTek       | G501JW                      | Notebook    | [fc8be1147a](https://linux-hardware.org/?probe=fc8be1147a) | Feb 21, 2024 |
| HP            | 1998                        | Desktop     | [ea2b04fb8f](https://linux-hardware.org/?probe=ea2b04fb8f) | Feb 20, 2024 |
| ASRock        | X99 Taichi                  | Desktop     | [98640d2d16](https://linux-hardware.org/?probe=98640d2d16) | Feb 19, 2024 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [fc0eb603fc](https://linux-hardware.org/?probe=fc0eb603fc) | Feb 18, 2024 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [13adc3e2df](https://linux-hardware.org/?probe=13adc3e2df) | Feb 18, 2024 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [5c7e2b278a](https://linux-hardware.org/?probe=5c7e2b278a) | Feb 17, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [129718807d](https://linux-hardware.org/?probe=129718807d) | Feb 17, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [7f6526b0a1](https://linux-hardware.org/?probe=7f6526b0a1) | Feb 17, 2024 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [a44e202559](https://linux-hardware.org/?probe=a44e202559) | Feb 17, 2024 |
| Dell          | Vostro 1540                 | Notebook    | [ed9ed14ad8](https://linux-hardware.org/?probe=ed9ed14ad8) | Feb 14, 2024 |
| AXIOO         | Slimbook 13                 | Notebook    | [6699ab5560](https://linux-hardware.org/?probe=6699ab5560) | Feb 14, 2024 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [1809bea252](https://linux-hardware.org/?probe=1809bea252) | Feb 14, 2024 |
| Lenovo        | G470 20078                  | Notebook    | [03e084a881](https://linux-hardware.org/?probe=03e084a881) | Feb 14, 2024 |
| ASUSTek       | GL552VW                     | Notebook    | [3d01ffb3f6](https://linux-hardware.org/?probe=3d01ffb3f6) | Feb 13, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [7fe62a177a](https://linux-hardware.org/?probe=7fe62a177a) | Feb 10, 2024 |
| Lenovo        | S10-3                       | Notebook    | [e9d3156b70](https://linux-hardware.org/?probe=e9d3156b70) | Feb 09, 2024 |
| MSI           | Modern 14 B11MOU            | Notebook    | [da8a74088f](https://linux-hardware.org/?probe=da8a74088f) | Feb 09, 2024 |
| Acer          | Aspire A515-56              | Notebook    | [0786192aa8](https://linux-hardware.org/?probe=0786192aa8) | Feb 07, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0f58d5d24e](https://linux-hardware.org/?probe=0f58d5d24e) | Feb 06, 2024 |
| realme        | CloudProXXXX                | Notebook    | [1299621a5e](https://linux-hardware.org/?probe=1299621a5e) | Feb 01, 2024 |
| Lenovo        | G405 20239                  | Notebook    | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [98de51c101](https://linux-hardware.org/?probe=98de51c101) | Jan 31, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [348c7c4e82](https://linux-hardware.org/?probe=348c7c4e82) | Jan 31, 2024 |
| Intel         | H81                         | Desktop     | [fac0a305d4](https://linux-hardware.org/?probe=fac0a305d4) | Jan 29, 2024 |
| Lenovo        | ThinkPad L440 20ASS01400    | Notebook    | [c8fad8ec59](https://linux-hardware.org/?probe=c8fad8ec59) | Jan 28, 2024 |
| Dell          | XPS 9320                    | Notebook    | [0214714fb9](https://linux-hardware.org/?probe=0214714fb9) | Jan 27, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [931f000daf](https://linux-hardware.org/?probe=931f000daf) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e6681b71bc](https://linux-hardware.org/?probe=e6681b71bc) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [65a3715aa3](https://linux-hardware.org/?probe=65a3715aa3) | Jan 25, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [fe98e7026e](https://linux-hardware.org/?probe=fe98e7026e) | Jan 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [0e4d078f49](https://linux-hardware.org/?probe=0e4d078f49) | Jan 25, 2024 |
| Lenovo        | ThinkPad T480 20L6S3L400    | Notebook    | [3861071640](https://linux-hardware.org/?probe=3861071640) | Jan 24, 2024 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [b8fc987633](https://linux-hardware.org/?probe=b8fc987633) | Jan 24, 2024 |
| Clevo         | M720SRS                     | Notebook    | [c0f6248edd](https://linux-hardware.org/?probe=c0f6248edd) | Jan 24, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [8edec841f0](https://linux-hardware.org/?probe=8edec841f0) | Jan 22, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [2097e4f7e6](https://linux-hardware.org/?probe=2097e4f7e6) | Jan 22, 2024 |
| Gigabyte      | F2A58M-DS2                  | Desktop     | [2b604752a0](https://linux-hardware.org/?probe=2b604752a0) | Jan 21, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [92f943771a](https://linux-hardware.org/?probe=92f943771a) | Jan 19, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | Notebook    | [9efd333805](https://linux-hardware.org/?probe=9efd333805) | Jan 18, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [040715bf2d](https://linux-hardware.org/?probe=040715bf2d) | Jan 17, 2024 |
| Dell          | 0MHWCY A00                  | All in one  | [021cf9cd7c](https://linux-hardware.org/?probe=021cf9cd7c) | Jan 17, 2024 |
| Microsoft     | Surface Pro 8               | Tablet      | [0a7cafc47f](https://linux-hardware.org/?probe=0a7cafc47f) | Jan 16, 2024 |
| ECS           | H61H2-MV                    | Desktop     | [09c20c7740](https://linux-hardware.org/?probe=09c20c7740) | Jan 15, 2024 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [22802134b7](https://linux-hardware.org/?probe=22802134b7) | Jan 15, 2024 |
| Lenovo        | ThinkPad T420 4180PV4       | Notebook    | [3277e75c3e](https://linux-hardware.org/?probe=3277e75c3e) | Jan 15, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1af5c7bda4](https://linux-hardware.org/?probe=1af5c7bda4) | Jan 15, 2024 |
| HP            | 81B4 01                     | Desktop     | [2a8624aed6](https://linux-hardware.org/?probe=2a8624aed6) | Jan 15, 2024 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [7b76b0de4f](https://linux-hardware.org/?probe=7b76b0de4f) | Jan 13, 2024 |
| HP            | 250 G5 Notebook PC          | Notebook    | [8fb1c8650f](https://linux-hardware.org/?probe=8fb1c8650f) | Jan 12, 2024 |
| Dell          | Vostro 3401                 | Notebook    | [cd47812859](https://linux-hardware.org/?probe=cd47812859) | Jan 11, 2024 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [8431e0e3d7](https://linux-hardware.org/?probe=8431e0e3d7) | Jan 10, 2024 |
| Unknown       | Unknown                     | Notebook    | [2d74d756b3](https://linux-hardware.org/?probe=2d74d756b3) | Jan 10, 2024 |
| Unknown       | DS16                        | Notebook    | [1951d37c43](https://linux-hardware.org/?probe=1951d37c43) | Jan 10, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [9cfcebcd8c](https://linux-hardware.org/?probe=9cfcebcd8c) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [0306a42404](https://linux-hardware.org/?probe=0306a42404) | Jan 09, 2024 |
| ASUSTek       | TP410UR                     | Convertible | [3063278c30](https://linux-hardware.org/?probe=3063278c30) | Jan 09, 2024 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [825a5ed72b](https://linux-hardware.org/?probe=825a5ed72b) | Jan 08, 2024 |
| Dell          | Inspiron 3576               | Notebook    | [ff3dc4d39e](https://linux-hardware.org/?probe=ff3dc4d39e) | Jan 08, 2024 |
| HP            | Presario CQ42               | Notebook    | [6addf001a5](https://linux-hardware.org/?probe=6addf001a5) | Jan 08, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4572d32ab9](https://linux-hardware.org/?probe=4572d32ab9) | Jan 06, 2024 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [416bb92e6e](https://linux-hardware.org/?probe=416bb92e6e) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [afb1d878cd](https://linux-hardware.org/?probe=afb1d878cd) | Jan 04, 2024 |
| Lenovo        | ThinkPad X250 20CL001LUS    | Notebook    | [f0f3c9a66c](https://linux-hardware.org/?probe=f0f3c9a66c) | Jan 04, 2024 |
| Acidanther... | MacBookPro16,4              | Notebook    | [3c8c520472](https://linux-hardware.org/?probe=3c8c520472) | Jan 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | Notebook    | [6ea14ec02e](https://linux-hardware.org/?probe=6ea14ec02e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | Notebook    | [29ab65f09e](https://linux-hardware.org/?probe=29ab65f09e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | Notebook    | [3afdb557c8](https://linux-hardware.org/?probe=3afdb557c8) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | Notebook    | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [0d985ff465](https://linux-hardware.org/?probe=0d985ff465) | Dec 31, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [32ce52498b](https://linux-hardware.org/?probe=32ce52498b) | Dec 28, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [f54cfd23ee](https://linux-hardware.org/?probe=f54cfd23ee) | Dec 28, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [977367b99e](https://linux-hardware.org/?probe=977367b99e) | Dec 26, 2023 |
| AZW           | MINI S 10                   | Desktop     | [fbeeeb79f5](https://linux-hardware.org/?probe=fbeeeb79f5) | Dec 25, 2023 |
| Intel         | B75                         | Desktop     | [65bfc8c4cf](https://linux-hardware.org/?probe=65bfc8c4cf) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [3bd91ab067](https://linux-hardware.org/?probe=3bd91ab067) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [d49a8fe4d4](https://linux-hardware.org/?probe=d49a8fe4d4) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [f1c9eab3f4](https://linux-hardware.org/?probe=f1c9eab3f4) | Dec 24, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [04e5c55b92](https://linux-hardware.org/?probe=04e5c55b92) | Dec 23, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [88cad415fb](https://linux-hardware.org/?probe=88cad415fb) | Dec 21, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [95bd5100ac](https://linux-hardware.org/?probe=95bd5100ac) | Dec 20, 2023 |
| Dell          | Latitude E6400              | Notebook    | [67d4d37a04](https://linux-hardware.org/?probe=67d4d37a04) | Dec 20, 2023 |
| Unknown       | Unknown                     | Other       | [92d87c0e52](https://linux-hardware.org/?probe=92d87c0e52) | Dec 19, 2023 |
| Lenovo        | ThinkPad T590 20N5S44300    | Notebook    | [5a90e712d1](https://linux-hardware.org/?probe=5a90e712d1) | Dec 19, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [97e3b8d570](https://linux-hardware.org/?probe=97e3b8d570) | Dec 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a6d28b0e6a](https://linux-hardware.org/?probe=a6d28b0e6a) | Dec 18, 2023 |
| Medion        | S17403                      | Notebook    | [250e479ad5](https://linux-hardware.org/?probe=250e479ad5) | Dec 18, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [9afc3e4d49](https://linux-hardware.org/?probe=9afc3e4d49) | Dec 16, 2023 |
| ASUSTek       | UX490UAR                    | Notebook    | [e8aa69b910](https://linux-hardware.org/?probe=e8aa69b910) | Dec 16, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [25c5c9bb33](https://linux-hardware.org/?probe=25c5c9bb33) | Dec 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b7194dbbb8](https://linux-hardware.org/?probe=b7194dbbb8) | Dec 15, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [f4af1a07e3](https://linux-hardware.org/?probe=f4af1a07e3) | Dec 15, 2023 |
| Lenovo        | ThinkPad L330 34701V0       | Notebook    | [d418989434](https://linux-hardware.org/?probe=d418989434) | Dec 15, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | Notebook    | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Dell          | Latitude E7240              | Notebook    | [4fcd011c61](https://linux-hardware.org/?probe=4fcd011c61) | Dec 13, 2023 |
| ASUSTek       | TP410UR                     | Convertible | [2442ce24b5](https://linux-hardware.org/?probe=2442ce24b5) | Dec 11, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [e7bbe1d5e7](https://linux-hardware.org/?probe=e7bbe1d5e7) | Dec 10, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [72c0c4e3a0](https://linux-hardware.org/?probe=72c0c4e3a0) | Dec 09, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f4aeac8ca](https://linux-hardware.org/?probe=0f4aeac8ca) | Dec 09, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [4167bf6fe4](https://linux-hardware.org/?probe=4167bf6fe4) | Dec 08, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [29a2194396](https://linux-hardware.org/?probe=29a2194396) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1b3b476186](https://linux-hardware.org/?probe=1b3b476186) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [58547d36b7](https://linux-hardware.org/?probe=58547d36b7) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [b5430476af](https://linux-hardware.org/?probe=b5430476af) | Dec 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6e61bec2ab](https://linux-hardware.org/?probe=6e61bec2ab) | Dec 06, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [becdc5222d](https://linux-hardware.org/?probe=becdc5222d) | Dec 05, 2023 |
| ASUSTek       | X441BA                      | Notebook    | [272c82d8eb](https://linux-hardware.org/?probe=272c82d8eb) | Dec 05, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [b3a0f94dfd](https://linux-hardware.org/?probe=b3a0f94dfd) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| Xiaomi        | Redmi 2 (Wingtech WT8804... | Soc         | [a35cc27d50](https://linux-hardware.org/?probe=a35cc27d50) | Dec 03, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [9a4c0266e8](https://linux-hardware.org/?probe=9a4c0266e8) | Dec 02, 2023 |
| Intel         | H61                         | Desktop     | [9951d7579f](https://linux-hardware.org/?probe=9951d7579f) | Dec 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [92a2b35bc8](https://linux-hardware.org/?probe=92a2b35bc8) | Dec 01, 2023 |
| Intel         | H61                         | Desktop     | [a0a26787ca](https://linux-hardware.org/?probe=a0a26787ca) | Nov 30, 2023 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [f43aaf1d39](https://linux-hardware.org/?probe=f43aaf1d39) | Nov 29, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [96bb14bbf4](https://linux-hardware.org/?probe=96bb14bbf4) | Nov 25, 2023 |
| Minix         | H61M-USB3 V1.2              | Desktop     | [2024379183](https://linux-hardware.org/?probe=2024379183) | Nov 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [dbfedd49f8](https://linux-hardware.org/?probe=dbfedd49f8) | Nov 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [a6240c8d6a](https://linux-hardware.org/?probe=a6240c8d6a) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | Notebook    | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [95624a1d82](https://linux-hardware.org/?probe=95624a1d82) | Nov 18, 2023 |
| Dell          | XPS 9320                    | Notebook    | [04760461ba](https://linux-hardware.org/?probe=04760461ba) | Nov 17, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [39c7028c1e](https://linux-hardware.org/?probe=39c7028c1e) | Nov 15, 2023 |
| ADVAN         | 1405                        | Notebook    | [55a639a506](https://linux-hardware.org/?probe=55a639a506) | Nov 14, 2023 |
| ASUSTek       | T100TAS                     | Notebook    | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [be4c8862d0](https://linux-hardware.org/?probe=be4c8862d0) | Nov 11, 2023 |
| Khadas        | VIM2                        | Soc         | [3db877cd01](https://linux-hardware.org/?probe=3db877cd01) | Nov 09, 2023 |
| Lenovo        | 0x36C6                      | All in one  | [8a4dfa9648](https://linux-hardware.org/?probe=8a4dfa9648) | Nov 09, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ba5db231dd](https://linux-hardware.org/?probe=ba5db231dd) | Nov 08, 2023 |
| Dell          | 0HH807                      | Desktop     | [300ee3d8f5](https://linux-hardware.org/?probe=300ee3d8f5) | Nov 08, 2023 |
| Lenovo        | ThinkPad Edge E465 BE465... | Notebook    | [54b9aa1cac](https://linux-hardware.org/?probe=54b9aa1cac) | Nov 07, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [1e2ba13164](https://linux-hardware.org/?probe=1e2ba13164) | Nov 06, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04327aa85c](https://linux-hardware.org/?probe=04327aa85c) | Nov 06, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [61828bc39f](https://linux-hardware.org/?probe=61828bc39f) | Nov 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [669430e32e](https://linux-hardware.org/?probe=669430e32e) | Nov 04, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | Notebook    | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [2b76c45313](https://linux-hardware.org/?probe=2b76c45313) | Nov 02, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [fffa5fb420](https://linux-hardware.org/?probe=fffa5fb420) | Nov 02, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [a7f47546e5](https://linux-hardware.org/?probe=a7f47546e5) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [8901bca741](https://linux-hardware.org/?probe=8901bca741) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [5787618dae](https://linux-hardware.org/?probe=5787618dae) | Oct 31, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [bc8c6e67a9](https://linux-hardware.org/?probe=bc8c6e67a9) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [220dddac59](https://linux-hardware.org/?probe=220dddac59) | Oct 28, 2023 |
| Dell          | Precision 5530              | Notebook    | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| Dell          | 0HH807                      | Desktop     | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| HP            | Notebook                    | Notebook    | [1f270f615f](https://linux-hardware.org/?probe=1f270f615f) | Oct 27, 2023 |
| Acer          | EG31M R01-C3                | Desktop     | [8a4232c8f0](https://linux-hardware.org/?probe=8a4232c8f0) | Oct 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a70d4b8a0d](https://linux-hardware.org/?probe=a70d4b8a0d) | Oct 25, 2023 |
| HP            | 198E                        | Desktop     | [3102593d74](https://linux-hardware.org/?probe=3102593d74) | Oct 25, 2023 |
| Dell          | Inspiron One 2310           | Notebook    | [1a8d313e86](https://linux-hardware.org/?probe=1a8d313e86) | Oct 25, 2023 |
| Dell          | Latitude 5285               | Notebook    | [9af5195620](https://linux-hardware.org/?probe=9af5195620) | Oct 24, 2023 |
| Dell          | Latitude 5320               | Notebook    | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [5b608b97fc](https://linux-hardware.org/?probe=5b608b97fc) | Oct 23, 2023 |
| Dell          | Latitude 5285               | Notebook    | [9552613f54](https://linux-hardware.org/?probe=9552613f54) | Oct 23, 2023 |
| Dell          | Latitude E6320              | Notebook    | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| Dell          | Inspiron 3458               | Notebook    | [ff4adff045](https://linux-hardware.org/?probe=ff4adff045) | Oct 21, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [fe4a9ec4d0](https://linux-hardware.org/?probe=fe4a9ec4d0) | Oct 20, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [1c0c1df851](https://linux-hardware.org/?probe=1c0c1df851) | Oct 20, 2023 |
| MSI           | 770T-C45                    | Desktop     | [bbe901612f](https://linux-hardware.org/?probe=bbe901612f) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | Notebook    | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| HP            | Notebook                    | Notebook    | [3fb8313450](https://linux-hardware.org/?probe=3fb8313450) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [71ffea0397](https://linux-hardware.org/?probe=71ffea0397) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [9ab2c722a5](https://linux-hardware.org/?probe=9ab2c722a5) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| Acer          | Aspire E3-112M              | Notebook    | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [0270e71d5e](https://linux-hardware.org/?probe=0270e71d5e) | Oct 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [329a5f99e0](https://linux-hardware.org/?probe=329a5f99e0) | Oct 18, 2023 |
| MicroByte     | ezbook                      | Notebook    | [c67055c10c](https://linux-hardware.org/?probe=c67055c10c) | Oct 17, 2023 |
| MicroByte     | ezbook                      | Notebook    | [5018eaffae](https://linux-hardware.org/?probe=5018eaffae) | Oct 17, 2023 |
| Toshiba       | Satellite L645              | Notebook    | [5bea545bf5](https://linux-hardware.org/?probe=5bea545bf5) | Oct 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [ec059c9ea7](https://linux-hardware.org/?probe=ec059c9ea7) | Oct 15, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [3d63dd4590](https://linux-hardware.org/?probe=3d63dd4590) | Oct 13, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [c1e1d017af](https://linux-hardware.org/?probe=c1e1d017af) | Oct 13, 2023 |
| Toshiba       | Satellite C55D-C            | Notebook    | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| HP            | 430                         | Notebook    | [e62771b9a7](https://linux-hardware.org/?probe=e62771b9a7) | Oct 09, 2023 |
| HP            | 430                         | Notebook    | [71211a4eda](https://linux-hardware.org/?probe=71211a4eda) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f3348806a2](https://linux-hardware.org/?probe=f3348806a2) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [1bb42f8755](https://linux-hardware.org/?probe=1bb42f8755) | Oct 09, 2023 |
| Acer          | Swift SF314-56G             | Notebook    | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| Acidanther... | MacBookPro16,4              | Notebook    | [c40356b94d](https://linux-hardware.org/?probe=c40356b94d) | Oct 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d48122086b](https://linux-hardware.org/?probe=d48122086b) | Oct 04, 2023 |
| Acer          | Swift SF314-56G             | Notebook    | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [0df81159a2](https://linux-hardware.org/?probe=0df81159a2) | Oct 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a3773ae099](https://linux-hardware.org/?probe=a3773ae099) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [25211e6ce1](https://linux-hardware.org/?probe=25211e6ce1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| ASRock        | A88M-G                      | Desktop     | [a918b08771](https://linux-hardware.org/?probe=a918b08771) | Sep 30, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [79b4f4f30e](https://linux-hardware.org/?probe=79b4f4f30e) | Sep 30, 2023 |
| Gigabyte      | P31-ES3G                    | Desktop     | [bee14e504c](https://linux-hardware.org/?probe=bee14e504c) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | Notebook    | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [7c8b825512](https://linux-hardware.org/?probe=7c8b825512) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| ZOTAC         | NM10                        | Desktop     | [8932b16aa1](https://linux-hardware.org/?probe=8932b16aa1) | Sep 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Acer          | Aspire M5910                | Desktop     | [5b44d1de35](https://linux-hardware.org/?probe=5b44d1de35) | Sep 25, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6383f263a8](https://linux-hardware.org/?probe=6383f263a8) | Sep 25, 2023 |
| Toshiba       | dynabook R632/H             | Notebook    | [7279759e40](https://linux-hardware.org/?probe=7279759e40) | Sep 25, 2023 |
| Acer          | Aspire S3                   | Notebook    | [4b2b76bdb3](https://linux-hardware.org/?probe=4b2b76bdb3) | Sep 24, 2023 |
| Acer          | Aspire S3                   | Notebook    | [723a872112](https://linux-hardware.org/?probe=723a872112) | Sep 24, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [4c12bddd77](https://linux-hardware.org/?probe=4c12bddd77) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [80e28a9df2](https://linux-hardware.org/?probe=80e28a9df2) | Sep 22, 2023 |
| HP            | Laptop 14-ep0xxx            | Notebook    | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | Notebook    | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [efafe71bd6](https://linux-hardware.org/?probe=efafe71bd6) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [a1356bddb2](https://linux-hardware.org/?probe=a1356bddb2) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [77e008b6d9](https://linux-hardware.org/?probe=77e008b6d9) | Sep 20, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [09433de4b0](https://linux-hardware.org/?probe=09433de4b0) | Sep 20, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a8995def08](https://linux-hardware.org/?probe=a8995def08) | Sep 19, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | Notebook    | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [877e70bb6f](https://linux-hardware.org/?probe=877e70bb6f) | Sep 14, 2023 |
| MSI           | MS-B9091                    | Desktop     | [5b1250945b](https://linux-hardware.org/?probe=5b1250945b) | Sep 11, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [16c285bb07](https://linux-hardware.org/?probe=16c285bb07) | Sep 10, 2023 |
| Samsung       | RV413/RV513                 | Notebook    | [c59551fc6f](https://linux-hardware.org/?probe=c59551fc6f) | Sep 09, 2023 |
| MSI           | MS-B9091                    | Desktop     | [226300a88d](https://linux-hardware.org/?probe=226300a88d) | Sep 09, 2023 |
| ASUSTek       | X450CC                      | Notebook    | [5564e70c85](https://linux-hardware.org/?probe=5564e70c85) | Sep 09, 2023 |
| ASUSTek       | X201EP                      | Notebook    | [a714c5a35a](https://linux-hardware.org/?probe=a714c5a35a) | Sep 09, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [34e95a943a](https://linux-hardware.org/?probe=34e95a943a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [89b56b4baf](https://linux-hardware.org/?probe=89b56b4baf) | Sep 06, 2023 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [d75c936b50](https://linux-hardware.org/?probe=d75c936b50) | Sep 06, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [56f00eec4a](https://linux-hardware.org/?probe=56f00eec4a) | Sep 05, 2023 |
| Sony          | VGN-CS108D                  | Notebook    | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Acer          | Veriton M480                | Desktop     | [0c97015cce](https://linux-hardware.org/?probe=0c97015cce) | Sep 05, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [1a1c5e43bc](https://linux-hardware.org/?probe=1a1c5e43bc) | Sep 05, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [4b4c5fb5f8](https://linux-hardware.org/?probe=4b4c5fb5f8) | Sep 04, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [6edc4e910d](https://linux-hardware.org/?probe=6edc4e910d) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | Notebook    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | Notebook    | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [2180bc1b72](https://linux-hardware.org/?probe=2180bc1b72) | Sep 01, 2023 |
| Acer          | Aspire E5-475G              | Notebook    | [55542f9b89](https://linux-hardware.org/?probe=55542f9b89) | Aug 31, 2023 |
| Dell          | Latitude E6410              | Notebook    | [c2337bbe75](https://linux-hardware.org/?probe=c2337bbe75) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [f7a484830d](https://linux-hardware.org/?probe=f7a484830d) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2a2adfdc2e](https://linux-hardware.org/?probe=2a2adfdc2e) | Aug 30, 2023 |
| Fujitsu       | FMVU14003                   | Notebook    | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [5b334ec725](https://linux-hardware.org/?probe=5b334ec725) | Aug 27, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [f79de96905](https://linux-hardware.org/?probe=f79de96905) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Dell          | Latitude E6410              | Notebook    | [fbaef9218f](https://linux-hardware.org/?probe=fbaef9218f) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [1d023bc980](https://linux-hardware.org/?probe=1d023bc980) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c47971e406](https://linux-hardware.org/?probe=c47971e406) | Aug 21, 2023 |
| Intel         | H81                         | Desktop     | [70d2da2312](https://linux-hardware.org/?probe=70d2da2312) | Aug 20, 2023 |
| Lenovo        | ThinkPad T540p 20BFS02S0... | Notebook    | [2f59ec7141](https://linux-hardware.org/?probe=2f59ec7141) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [7f7f077fda](https://linux-hardware.org/?probe=7f7f077fda) | Aug 18, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [2c4ded9440](https://linux-hardware.org/?probe=2c4ded9440) | Aug 18, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| MSI           | 3666h                       | Desktop     | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [857539aaba](https://linux-hardware.org/?probe=857539aaba) | Aug 14, 2023 |
| Dell          | 03015M A01                  | Server      | [82a456951b](https://linux-hardware.org/?probe=82a456951b) | Aug 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0ecb69efbc](https://linux-hardware.org/?probe=0ecb69efbc) | Aug 14, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2a753fd907](https://linux-hardware.org/?probe=2a753fd907) | Aug 14, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [182445f47d](https://linux-hardware.org/?probe=182445f47d) | Aug 13, 2023 |
| MSI           | Katana GF66 11UD            | Notebook    | [e7e9bfd605](https://linux-hardware.org/?probe=e7e9bfd605) | Aug 13, 2023 |
| Samsung       | 960XFH                      | Notebook    | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [f78ce03ad4](https://linux-hardware.org/?probe=f78ce03ad4) | Aug 08, 2023 |
| ASRock        | H61M-HVGS                   | Desktop     | [60d9dcfa89](https://linux-hardware.org/?probe=60d9dcfa89) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [8491f5fc3b](https://linux-hardware.org/?probe=8491f5fc3b) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | Notebook    | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [738a42f72e](https://linux-hardware.org/?probe=738a42f72e) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [50be5e5725](https://linux-hardware.org/?probe=50be5e5725) | Aug 05, 2023 |
| Dell          | Latitude E6410              | Notebook    | [ad46549b01](https://linux-hardware.org/?probe=ad46549b01) | Aug 04, 2023 |
| Dell          | Latitude E6410              | Notebook    | [e2364d5aac](https://linux-hardware.org/?probe=e2364d5aac) | Aug 04, 2023 |
| MSI           | H81M-E35 V2                 | Desktop     | [2e72dc6560](https://linux-hardware.org/?probe=2e72dc6560) | Aug 04, 2023 |
| Dell          | 0GTK4K A10                  | Desktop     | [b6586709f2](https://linux-hardware.org/?probe=b6586709f2) | Aug 03, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | Notebook    | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| Unknown       | Unknown                     | Other       | [db0911c516](https://linux-hardware.org/?probe=db0911c516) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming FX505DD          | Notebook    | [e965235133](https://linux-hardware.org/?probe=e965235133) | Jul 29, 2023 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [7642eb12d5](https://linux-hardware.org/?probe=7642eb12d5) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [6632226064](https://linux-hardware.org/?probe=6632226064) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [bf88e1114e](https://linux-hardware.org/?probe=bf88e1114e) | Jul 25, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [69b707119e](https://linux-hardware.org/?probe=69b707119e) | Jul 25, 2023 |
| Lenovo        | ThinkPad X230 23246V9       | Notebook    | [e7bc7dac48](https://linux-hardware.org/?probe=e7bc7dac48) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c78c35de44](https://linux-hardware.org/?probe=c78c35de44) | Jul 23, 2023 |
| Unknown       | Unknown                     | Other       | [18c7d0154b](https://linux-hardware.org/?probe=18c7d0154b) | Jul 22, 2023 |
| HP            | 2187 A01                    | Desktop     | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| Fujitsu       | FMVNC4BC4                   | Notebook    | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [462a41184d](https://linux-hardware.org/?probe=462a41184d) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| MSI           | 2A9C                        | Desktop     | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [c1c039384c](https://linux-hardware.org/?probe=c1c039384c) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Unknown       | Unknown                     | Other       | [a5da218315](https://linux-hardware.org/?probe=a5da218315) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | Notebook    | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| HP            | ProBook 4420s               | Notebook    | [51e917f03e](https://linux-hardware.org/?probe=51e917f03e) | Jul 09, 2023 |
| Gigabyte      | P55-USB3L                   | Desktop     | [b225c530bd](https://linux-hardware.org/?probe=b225c530bd) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | Notebook    | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| Lenovo        | Unknown                     | Convertible | [7c4ddbebf7](https://linux-hardware.org/?probe=7c4ddbebf7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Unknown       | Unknown                     | Soc         | [e31f4bb359](https://linux-hardware.org/?probe=e31f4bb359) | Jul 08, 2023 |
| Toshiba       | PORTEGE R30-C               | Notebook    | [f07f4d423b](https://linux-hardware.org/?probe=f07f4d423b) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [680f3038da](https://linux-hardware.org/?probe=680f3038da) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| AZW           | Z85                         | Notebook    | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| Acer          | Aspire V5-471G              | Notebook    | [6dd5e93eea](https://linux-hardware.org/?probe=6dd5e93eea) | Jul 05, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [f1ad74f37a](https://linux-hardware.org/?probe=f1ad74f37a) | Jul 05, 2023 |
| Dell          | Latitude E6540              | Notebook    | [17ec85df62](https://linux-hardware.org/?probe=17ec85df62) | Jul 05, 2023 |
| Dell          | Latitude 3410               | Notebook    | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| HP            | 8061                        | Desktop     | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | Notebook    | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| Microsoft     | Surface Pro 2               | Tablet      | [5b92d42213](https://linux-hardware.org/?probe=5b92d42213) | Jun 29, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| Intel         | Unknown                     | Desktop     | [3c85a0c7b9](https://linux-hardware.org/?probe=3c85a0c7b9) | Jun 28, 2023 |
| Intel         | Unknown                     | Desktop     | [dbfbe4b6aa](https://linux-hardware.org/?probe=dbfbe4b6aa) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [9ab87d56a7](https://linux-hardware.org/?probe=9ab87d56a7) | Jun 22, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [0cad0d9955](https://linux-hardware.org/?probe=0cad0d9955) | Jun 22, 2023 |
| Notebook      | P870DM                      | Notebook    | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [9bcbbbd906](https://linux-hardware.org/?probe=9bcbbbd906) | Jun 21, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [d432122ffe](https://linux-hardware.org/?probe=d432122ffe) | Jun 21, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [2d8b92b0e6](https://linux-hardware.org/?probe=2d8b92b0e6) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [5296ca6ae2](https://linux-hardware.org/?probe=5296ca6ae2) | Jun 19, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b1d6af488d](https://linux-hardware.org/?probe=b1d6af488d) | Jun 18, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [76c1fcc4e5](https://linux-hardware.org/?probe=76c1fcc4e5) | Jun 14, 2023 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [3e4b7afb1e](https://linux-hardware.org/?probe=3e4b7afb1e) | Jun 10, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [9770971a47](https://linux-hardware.org/?probe=9770971a47) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Infinix       | INBook X1 Pro               | Notebook    | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| AXIOO         | Mybook-14E                  | Notebook    | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [6de2588617](https://linux-hardware.org/?probe=6de2588617) | May 29, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [369aa4fc93](https://linux-hardware.org/?probe=369aa4fc93) | May 29, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| AVITA         | NE14A2                      | Notebook    | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [b88a90f9d3](https://linux-hardware.org/?probe=b88a90f9d3) | May 25, 2023 |
| Panasonic     | CFSZ5-2                     | Notebook    | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| MSI           | 2A9C                        | Desktop     | [acaff65dda](https://linux-hardware.org/?probe=acaff65dda) | May 24, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [cfdb07c9ca](https://linux-hardware.org/?probe=cfdb07c9ca) | May 21, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | Notebook    | [379bcdafa9](https://linux-hardware.org/?probe=379bcdafa9) | May 21, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | Notebook    | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| MSI           | 2A9C                        | Desktop     | [78d54a3ebf](https://linux-hardware.org/?probe=78d54a3ebf) | May 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [59902928be](https://linux-hardware.org/?probe=59902928be) | May 18, 2023 |
| ASUSTek       | V241EA                      | All in one  | [e4f05ea74b](https://linux-hardware.org/?probe=e4f05ea74b) | May 16, 2023 |
| Acer          | One Z1402                   | Notebook    | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| Lenovo        | ThinkCentre M90z 5205CTO    | All in one  | [6353fe7194](https://linux-hardware.org/?probe=6353fe7194) | May 16, 2023 |
| ASUSTek       | GL502VMK                    | Notebook    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Infinix       | INBook X1                   | Notebook    | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| HP            | 83EB                        | All in one  | [0abdbdd77b](https://linux-hardware.org/?probe=0abdbdd77b) | May 10, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [036d26ffb3](https://linux-hardware.org/?probe=036d26ffb3) | May 10, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [e8f10d5f7e](https://linux-hardware.org/?probe=e8f10d5f7e) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [5491fd5858](https://linux-hardware.org/?probe=5491fd5858) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Dell          | Latitude D630               | Notebook    | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| Dell          | Latitude D630               | Notebook    | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [f1537beedf](https://linux-hardware.org/?probe=f1537beedf) | May 01, 2023 |
| Acer          | Aspire A514-54G             | Notebook    | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| Dell          | Latitude 7300               | Notebook    | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | Notebook    | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [fc811580c9](https://linux-hardware.org/?probe=fc811580c9) | Apr 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [ca58518a03](https://linux-hardware.org/?probe=ca58518a03) | Apr 09, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| AZW           | U59                         | Desktop     | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| HP            | Notebook                    | Notebook    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | Notebook    | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Acer          | EG31M R01-C3                | Desktop     | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| Toshiba       | Satellite L640              | Notebook    | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | Notebook    | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | Notebook    | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | Notebook    | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c59398619e](https://linux-hardware.org/?probe=c59398619e) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | Desktop     | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | Notebook    | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | Notebook    | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Gigabyte      | P41T-D3                     | Desktop     | [2941019778](https://linux-hardware.org/?probe=2941019778) | Mar 29, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | Notebook    | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | Notebook    | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [8e9a11831c](https://linux-hardware.org/?probe=8e9a11831c) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [4b6ecef29b](https://linux-hardware.org/?probe=4b6ecef29b) | Mar 19, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | Notebook    | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | Notebook    | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | Notebook    | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | Notebook    | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | Notebook    | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| GALAX         | B550M                       | Desktop     | [7b8e9c7506](https://linux-hardware.org/?probe=7b8e9c7506) | Mar 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | Notebook    | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | Notebook    | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | Notebook    | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | Notebook    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | Notebook    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | Notebook    | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| Foxconn       | G31MX Series                | Desktop     | [79ee8e5da3](https://linux-hardware.org/?probe=79ee8e5da3) | Feb 28, 2023 |
| Intel         | H61                         | Desktop     | [b61ef1ed65](https://linux-hardware.org/?probe=b61ef1ed65) | Feb 27, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [b13f16cb2f](https://linux-hardware.org/?probe=b13f16cb2f) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASRock        | 970A-G                      | Desktop     | [bfdb227a9d](https://linux-hardware.org/?probe=bfdb227a9d) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| ASRock        | A88M-G                      | Desktop     | [917526ad4d](https://linux-hardware.org/?probe=917526ad4d) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | Notebook    | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | Notebook    | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [e9cfac6aa3](https://linux-hardware.org/?probe=e9cfac6aa3) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | Notebook    | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | Notebook    | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| AZW           | U59                         | Desktop     | [24ccf521f0](https://linux-hardware.org/?probe=24ccf521f0) | Feb 11, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Intel         | H61                         | Desktop     | [e07896a0a6](https://linux-hardware.org/?probe=e07896a0a6) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | Notebook    | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | Notebook    | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | Notebook    | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | 198E                        | Desktop     | [7dedbbef80](https://linux-hardware.org/?probe=7dedbbef80) | Feb 04, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | Notebook    | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [d98f389956](https://linux-hardware.org/?probe=d98f389956) | Jan 28, 2023 |
| OEM           | M882CWP                     | Tablet      | [152e24910a](https://linux-hardware.org/?probe=152e24910a) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [dac4a44a62](https://linux-hardware.org/?probe=dac4a44a62) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | Notebook    | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | Notebook    | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | Notebook    | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [92d2b62680](https://linux-hardware.org/?probe=92d2b62680) | Jan 22, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [292ff62f4c](https://linux-hardware.org/?probe=292ff62f4c) | Jan 22, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | Notebook    | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [e2486858b9](https://linux-hardware.org/?probe=e2486858b9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | 3102 NO DPK                 | Desktop     | [fa7b131a50](https://linux-hardware.org/?probe=fa7b131a50) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Unknown       | Unknown                     | Phone       | [71abbc8c47](https://linux-hardware.org/?probe=71abbc8c47) | Jan 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7fefb8d34c](https://linux-hardware.org/?probe=7fefb8d34c) | Jan 15, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | Notebook    | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Intel         | Unknown                     | Desktop     | [6928fe7911](https://linux-hardware.org/?probe=6928fe7911) | Jan 11, 2023 |
| Acer          | AO756                       | Notebook    | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 169       | 9.04%   |
| Ubuntu 18.04                 | 106       | 5.67%   |
| Ubuntu 22.04                 | 104       | 5.56%   |
| OpenMandriva 4.3             | 61        | 3.26%   |
| Arch Rolling                 | 57        | 3.05%   |
| Pop!_OS 22.04                | 44        | 2.35%   |
| Debian 12                    | 37        | 1.98%   |
| OpenMandriva 4.2             | 32        | 1.71%   |
| ArcoLinux Rolling            | 31        | 1.66%   |
| Ubuntu 24.04                 | 29        | 1.55%   |
| KDE neon 20.04               | 26        | 1.39%   |
| Fedora 40                    | 25        | 1.34%   |
| Fedora 38                    | 24        | 1.28%   |
| Zorin 15                     | 23        | 1.23%   |
| Zorin 17                     | 22        | 1.18%   |
| Arch                         | 22        | 1.18%   |
| Manjaro                      | 21        | 1.12%   |
| Fedora 36                    | 21        | 1.12%   |
| Zorin 16                     | 20        | 1.07%   |
| OpenMandriva 23.08           | 20        | 1.07%   |
| Elementary 6.1               | 19        | 1.02%   |
| Pop!_OS 20.04                | 18        | 0.96%   |
| OpenMandriva 5.0             | 18        | 0.96%   |
| EndeavourOS Rolling          | 18        | 0.96%   |
| OpenMandriva 23.03           | 17        | 0.91%   |
| Fedora 35                    | 17        | 0.91%   |
| Debian 11                    | 17        | 0.91%   |
| Ubuntu 21.10                 | 16        | 0.86%   |
| Linux Mint 21.1              | 16        | 0.86%   |
| Linux Mint 20.3              | 16        | 0.86%   |
| Ubuntu 19.10                 | 15        | 0.8%    |
| openSUSE Tumbleweed-XXXXXXXX | 15        | 0.8%    |
| Fedora 37                    | 15        | 0.8%    |
| OpenMandriva 23.01           | 14        | 0.75%   |
| Linux Mint 19.3              | 14        | 0.75%   |
| KDE neon 22.04               | 14        | 0.75%   |
| Xubuntu 20.04                | 13        | 0.7%    |
| Linux Mint 22                | 13        | 0.7%    |
| Kubuntu 22.04                | 13        | 0.7%    |
| Fedora 39                    | 13        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 475       | 26.81%  |
| OpenMandriva  | 193       | 10.89%  |
| Fedora        | 133       | 7.51%   |
| Linux Mint    | 111       | 6.26%   |
| Arch          | 79        | 4.46%   |
| Pop!_OS       | 77        | 4.35%   |
| Debian        | 70        | 3.95%   |
| Zorin         | 69        | 3.89%   |
| Manjaro       | 57        | 3.22%   |
| Elementary    | 52        | 2.93%   |
| KDE neon      | 41        | 2.31%   |
| Kubuntu       | 39        | 2.2%    |
| Kali          | 36        | 2.03%   |
| Endless       | 34        | 1.92%   |
| ArcoLinux     | 32        | 1.81%   |
| Xubuntu       | 29        | 1.64%   |
| Lubuntu       | 23        | 1.3%    |
| openSUSE      | 18        | 1.02%   |
| EndeavourOS   | 18        | 1.02%   |
| ROSA          | 17        | 0.96%   |
| Ubuntu MATE   | 12        | 0.68%   |
| MX            | 11        | 0.62%   |
| Ubuntu Unity  | 10        | 0.56%   |
| SteamOS       | 10        | 0.56%   |
| Nobara        | 10        | 0.56%   |
| LMDE          | 8         | 0.45%   |
| Clear Linux   | 8         | 0.45%   |
| Parrot        | 7         | 0.4%    |
| Gentoo        | 7         | 0.4%    |
| Deepin        | 7         | 0.4%    |
| CentOS        | 5         | 0.28%   |
| Android       | 5         | 0.28%   |
| Ubuntu Budgie | 4         | 0.23%   |
| Rocky Linux   | 4         | 0.23%   |
| Garuda Linux  | 4         | 0.23%   |
| Artix         | 4         | 0.23%   |
| Xero          | 3         | 0.17%   |
| Sparky        | 3         | 0.17%   |
| Solus         | 3         | 0.17%   |
| NixOS         | 3         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 60        | 3%      |
| 5.10.14-desktop-1omv4002 | 29        | 1.45%   |
| 5.4.0-42-generic         | 28        | 1.4%    |
| 6.6.2-desktop-1omv2390   | 23        | 1.15%   |
| 5.15.0-56-generic        | 22        | 1.1%    |
| 5.4.0-26-generic         | 18        | 0.9%    |
| 6.4.11-desktop-1omv2390  | 17        | 0.85%   |
| 6.2.6-desktop-1omv2390   | 16        | 0.8%    |
| 5.4.0-52-generic         | 16        | 0.8%    |
| 5.4.0-58-generic         | 15        | 0.75%   |
| 6.1.1-desktop-1omv2290   | 12        | 0.6%    |
| 4.18.0-15-generic        | 12        | 0.6%    |
| 5.15.0-41-generic        | 11        | 0.55%   |
| 5.0.0-25-generic         | 11        | 0.55%   |
| 6.12.1-desktop-1omv2490  | 10        | 0.5%    |
| 5.15.0-48-generic        | 10        | 0.5%    |
| 5.15.0-46-generic        | 10        | 0.5%    |
| 5.15.0-43-generic        | 10        | 0.5%    |
| 6.9.3-76060903-generic   | 9         | 0.45%   |
| 6.8.0-49-generic         | 9         | 0.45%   |
| 6.8.0-45-generic         | 9         | 0.45%   |
| 5.4.0-80-generic         | 9         | 0.45%   |
| 5.15.0-47-generic        | 9         | 0.45%   |
| 5.11.0-37-generic        | 9         | 0.45%   |
| 6.5.0-35-generic         | 8         | 0.4%    |
| 5.4.0-54-generic         | 8         | 0.4%    |
| 5.3.0-46-generic         | 8         | 0.4%    |
| 5.3.0-40-generic         | 8         | 0.4%    |
| 5.19.0-46-generic        | 8         | 0.4%    |
| 5.15.0-91-generic        | 8         | 0.4%    |
| 5.15.0-58-generic        | 8         | 0.4%    |
| 6.8.0-41-generic         | 7         | 0.35%   |
| 6.8.0-40-generic         | 7         | 0.35%   |
| 6.2.0-39-generic         | 7         | 0.35%   |
| 6.2.0-26-generic         | 7         | 0.35%   |
| 5.8.0-48-generic         | 7         | 0.35%   |
| 5.8.0-14-generic         | 7         | 0.35%   |
| 5.19.0-35-generic        | 7         | 0.35%   |
| 5.15.0-52-generic        | 7         | 0.35%   |
| 5.11.0-43-generic        | 7         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 214       | 11.07%  |
| 5.15.0  | 159       | 8.22%   |
| 5.11.0  | 74        | 3.83%   |
| 6.8.0   | 68        | 3.52%   |
| 5.16.7  | 62        | 3.21%   |
| 5.8.0   | 61        | 3.15%   |
| 6.5.0   | 58        | 3%      |
| 4.15.0  | 56        | 2.9%    |
| 5.13.0  | 53        | 2.74%   |
| 5.3.0   | 51        | 2.64%   |
| 6.1.0   | 47        | 2.43%   |
| 6.2.0   | 45        | 2.33%   |
| 5.0.0   | 43        | 2.22%   |
| 5.19.0  | 36        | 1.86%   |
| 5.10.0  | 33        | 1.71%   |
| 4.18.0  | 32        | 1.65%   |
| 5.10.14 | 30        | 1.55%   |
| 6.6.2   | 23        | 1.19%   |
| 6.4.11  | 20        | 1.03%   |
| 6.2.6   | 20        | 1.03%   |
| 6.1.1   | 18        | 0.93%   |
| 6.5.5   | 15        | 0.78%   |
| 4.19.0  | 15        | 0.78%   |
| 5.14.0  | 11        | 0.57%   |
| 6.9.7   | 10        | 0.52%   |
| 6.9.3   | 10        | 0.52%   |
| 6.12.1  | 10        | 0.52%   |
| 5.17.5  | 8         | 0.41%   |
| 4.4.0   | 8         | 0.41%   |
| 6.6.9   | 7         | 0.36%   |
| 6.5.6   | 7         | 0.36%   |
| 6.4.6   | 7         | 0.36%   |
| 6.10.0  | 7         | 0.36%   |
| 6.8.5   | 6         | 0.31%   |
| 6.6.8   | 6         | 0.31%   |
| 6.5.3   | 6         | 0.31%   |
| 6.4.8   | 6         | 0.31%   |
| 5.16.0  | 6         | 0.31%   |
| 6.3.5   | 5         | 0.26%   |
| 6.2.8   | 5         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 224       | 11.76%  |
| 5.15    | 186       | 9.77%   |
| 5.10    | 100       | 5.25%   |
| 6.1     | 96        | 5.04%   |
| 6.5     | 95        | 4.99%   |
| 6.8     | 87        | 4.57%   |
| 5.16    | 85        | 4.46%   |
| 5.11    | 84        | 4.41%   |
| 6.2     | 83        | 4.36%   |
| 5.8     | 76        | 3.99%   |
| 6.6     | 68        | 3.57%   |
| 5.13    | 61        | 3.2%    |
| 4.15    | 56        | 2.94%   |
| 5.3     | 55        | 2.89%   |
| 5.19    | 52        | 2.73%   |
| 6.4     | 51        | 2.68%   |
| 5.0     | 45        | 2.36%   |
| 4.18    | 35        | 1.84%   |
| 6.9     | 34        | 1.79%   |
| 6.10    | 33        | 1.73%   |
| 6.0     | 32        | 1.68%   |
| 5.14    | 27        | 1.42%   |
| 6.3     | 25        | 1.31%   |
| 5.17    | 22        | 1.16%   |
| 6.11    | 21        | 1.1%    |
| 5.18    | 19        | 1%      |
| 4.19    | 19        | 1%      |
| 6.12    | 18        | 0.95%   |
| 5.9     | 16        | 0.84%   |
| 6.7     | 15        | 0.79%   |
| 4.9     | 14        | 0.74%   |
| 5.12    | 12        | 0.63%   |
| 5.7     | 10        | 0.53%   |
| 5.6     | 10        | 0.53%   |
| 4.4     | 10        | 0.53%   |
| 5.5     | 6         | 0.32%   |
| 5.2     | 3         | 0.16%   |
| 4.13    | 3         | 0.16%   |
| 4.14    | 2         | 0.11%   |
| 4.10    | 2         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1665      | 97.37%  |
| i686    | 31        | 1.81%   |
| aarch64 | 8         | 0.47%   |
| armv8l  | 3         | 0.18%   |
| armv7l  | 3         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 745       | 41.83%  |
| KDE5              | 335       | 18.81%  |
| Unknown           | 181       | 10.16%  |
| XFCE              | 137       | 7.69%   |
| X-Cinnamon        | 100       | 5.61%   |
| Pantheon          | 50        | 2.81%   |
| LXQt              | 39        | 2.19%   |
| MATE              | 32        | 1.8%    |
| KDE6              | 30        | 1.68%   |
| KDE               | 22        | 1.24%   |
| Cinnamon          | 16        | 0.9%    |
| Budgie            | 11        | 0.62%   |
| Unity             | 10        | 0.56%   |
| i3                | 8         | 0.45%   |
| Deepin            | 8         | 0.45%   |
| Hyprland          | 7         | 0.39%   |
| KDE4              | 5         | 0.28%   |
| GNOME Flashback   | 5         | 0.28%   |
| DWM               | 5         | 0.28%   |
| Bspwm             | 5         | 0.28%   |
| sway              | 3         | 0.17%   |
| LXDE              | 3         | 0.17%   |
| lightdm-xsession  | 3         | 0.17%   |
| ICEWM             | 3         | 0.17%   |
| Cutefish          | 3         | 0.17%   |
| Yaru:ubuntu:GNOME | 2         | 0.11%   |
| xmonad            | 2         | 0.11%   |
| qtile             | 2         | 0.11%   |
| DDE               | 2         | 0.11%   |
| Phosh:GNOME       | 1         | 0.06%   |
| Peux Gnome        | 1         | 0.06%   |
| openbox           | 1         | 0.06%   |
| Lubuntu           | 1         | 0.06%   |
| GNOME Classic     | 1         | 0.06%   |
| awesomeminimal    | 1         | 0.06%   |
| awesome           | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1177      | 66.5%   |
| Wayland | 453       | 25.59%  |
| Unknown | 111       | 6.27%   |
| Tty     | 29        | 1.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 755       | 42.63%  |
| SDDM    | 339       | 19.14%  |
| GDM3    | 218       | 12.31%  |
| GDM     | 210       | 11.86%  |
| LightDM | 200       | 11.29%  |
| TDM     | 37        | 2.09%   |
| KDM     | 5         | 0.28%   |
| SLiM    | 3         | 0.17%   |
| Ly      | 2         | 0.11%   |
| LY-DM   | 1         | 0.06%   |
| LXDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1413      | 81.3%   |
| Unknown | 128       | 7.36%   |
| id_ID   | 110       | 6.33%   |
| C       | 35        | 2.01%   |
| en_GB   | 20        | 1.15%   |
| en_AU   | 6         | 0.35%   |
| en_SG   | 5         | 0.29%   |
| en_AG   | 5         | 0.29%   |
| de_DE   | 3         | 0.17%   |
| ru_RU   | 2         | 0.12%   |
| fr_FR   | 2         | 0.12%   |
| en_IN   | 2         | 0.12%   |
| en_CA   | 2         | 0.12%   |
| jv_ID   | 1         | 0.06%   |
| it_IT   | 1         | 0.06%   |
| de_CH   | 1         | 0.06%   |
| Default | 1         | 0.06%   |
| C.UTF8  | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 936       | 53.58%  |
| BIOS | 811       | 46.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1266      | 72.43%  |
| Btrfs   | 202       | 11.56%  |
| Overlay | 136       | 7.78%   |
| Tmpfs   | 57        | 3.26%   |
| Unknown | 45        | 2.57%   |
| Xfs     | 23        | 1.32%   |
| Zfs     | 7         | 0.4%    |
| F2fs    | 5         | 0.29%   |
| Ext2    | 5         | 0.29%   |
| Ext3    | 2         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 787       | 45.02%  |
| Unknown | 749       | 42.85%  |
| MBR     | 212       | 12.13%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1504      | 86.44%  |
| Yes       | 236       | 13.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1030      | 59.03%  |
| Yes       | 715       | 40.97%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 356       | 20.82%  |
| ASUSTek Computer        | 332       | 19.42%  |
| Hewlett-Packard         | 228       | 13.33%  |
| Acer                    | 170       | 9.94%   |
| Dell                    | 132       | 7.72%   |
| MSI                     | 70        | 4.09%   |
| Gigabyte Technology     | 60        | 3.51%   |
| ASRock                  | 55        | 3.22%   |
| Toshiba                 | 39        | 2.28%   |
| Intel                   | 33        | 1.93%   |
| Apple                   | 22        | 1.29%   |
| Unknown                 | 21        | 1.23%   |
| ECS                     | 19        | 1.11%   |
| Biostar                 | 19        | 1.11%   |
| AXIOO                   | 18        | 1.05%   |
| Fujitsu                 | 12        | 0.7%    |
| Sony                    | 11        | 0.64%   |
| Samsung Electronics     | 9         | 0.53%   |
| ADVAN                   | 7         | 0.41%   |
| Valve                   | 6         | 0.35%   |
| Infinix                 | 5         | 0.29%   |
| HUAWEI                  | 5         | 0.29%   |
| Clevo                   | 5         | 0.29%   |
| AZW                     | 5         | 0.29%   |
| Panasonic               | 4         | 0.23%   |
| realme                  | 3         | 0.18%   |
| Microsoft               | 3         | 0.18%   |
| Google                  | 3         | 0.18%   |
| Foxconn                 | 3         | 0.18%   |
| Timi                    | 2         | 0.12%   |
| Supermicro              | 2         | 0.12%   |
| Raspberry Pi Foundation | 2         | 0.12%   |
| Pegatron                | 2         | 0.12%   |
| OEM                     | 2         | 0.12%   |
| LORD ELECTRONICS        | 2         | 0.12%   |
| Langchao                | 2         | 0.12%   |
| Chuwi                   | 2         | 0.12%   |
| AVITA                   | 2         | 0.12%   |
| Acidanthera             | 2         | 0.12%   |
| ZYREX COMPUTER SYSTEMS  | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 28        | 1.64%   |
| HP Notebook                             | 14        | 0.82%   |
| Lenovo IdeaPad 330-14AST 81D5           | 12        | 0.7%    |
| Lenovo G40-45 80E1                      | 12        | 0.7%    |
| Intel H61                               | 10        | 0.58%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 9         | 0.53%   |
| Lenovo G400 20235                       | 8         | 0.47%   |
| Acer Swift SF314-71                     | 8         | 0.47%   |
| Acer Aspire 4752                        | 8         | 0.47%   |
| Lenovo IdeaPad S340-14API 81NB          | 7         | 0.41%   |
| HP Pavilion g4                          | 7         | 0.41%   |
| HP Laptop 14-bw0xx                      | 7         | 0.41%   |
| HP 14                                   | 7         | 0.41%   |
| Valve Jupiter                           | 6         | 0.35%   |
| HP Laptop 14-bs0xx                      | 6         | 0.35%   |
| ASUS X455LF                             | 6         | 0.35%   |
| ASUS GL553VD                            | 6         | 0.35%   |
| ASUS All Series                         | 6         | 0.35%   |
| Acer Aspire 4750                        | 6         | 0.35%   |
| Lenovo IdeaPad 320-14AST 80XU           | 5         | 0.29%   |
| ASUS X455YA                             | 5         | 0.29%   |
| ASUS X441BA                             | 5         | 0.29%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.29%   |
| ASRock A320M-HDV R4.0                   | 5         | 0.29%   |
| Apple MacBookPro12,1                    | 5         | 0.29%   |
| Acer Swift SFX14-41G                    | 5         | 0.29%   |
| Acer Swift SF314-56G                    | 5         | 0.29%   |
| Acer One Z1402                          | 5         | 0.29%   |
| Acer Aspire E5-475G                     | 5         | 0.29%   |
| Lenovo Yoga C640-13IML 81UE             | 4         | 0.23%   |
| Lenovo V310-14ISK 80SX                  | 4         | 0.23%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 4         | 0.23%   |
| Lenovo G400s 20244                      | 4         | 0.23%   |
| Lenovo G40-30 80FY                      | 4         | 0.23%   |
| HP Pavilion 14                          | 4         | 0.23%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.23%   |
| HP EliteBook 2570p                      | 4         | 0.23%   |
| HP 1000                                 | 4         | 0.23%   |
| Gigabyte H61M-DS2                       | 4         | 0.23%   |
| Dell OptiPlex 7010                      | 4         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 120       | 7.02%   |
| Lenovo IdeaPad     | 105       | 6.14%   |
| Acer Aspire        | 98        | 5.73%   |
| ASUS VivoBook      | 63        | 3.68%   |
| HP Laptop          | 47        | 2.75%   |
| Dell Latitude      | 47        | 2.75%   |
| HP Pavilion        | 45        | 2.63%   |
| Dell Inspiron      | 32        | 1.87%   |
| Unknown            | 28        | 1.64%   |
| Acer Swift         | 27        | 1.58%   |
| HP EliteBook       | 26        | 1.52%   |
| Toshiba Satellite  | 24        | 1.4%    |
| ASUS ASUS          | 18        | 1.05%   |
| Dell OptiPlex      | 17        | 0.99%   |
| Lenovo Yoga        | 16        | 0.94%   |
| Dell Vostro        | 16        | 0.94%   |
| HP Notebook        | 14        | 0.82%   |
| ASUS ROG           | 14        | 0.82%   |
| Lenovo ThinkCentre | 13        | 0.76%   |
| Lenovo G40-45      | 12        | 0.7%    |
| ASUS TUF           | 12        | 0.7%    |
| Acer Nitro         | 12        | 0.7%    |
| HP ProBook         | 11        | 0.64%   |
| Intel H61          | 10        | 0.58%   |
| HP ENVY            | 10        | 0.58%   |
| ASUS PRIME         | 10        | 0.58%   |
| Lenovo ThinkBook   | 9         | 0.53%   |
| Lenovo G400        | 8         | 0.47%   |
| Toshiba PORTEGE    | 7         | 0.41%   |
| MSI Modern         | 7         | 0.41%   |
| Lenovo IdeaPadFlex | 7         | 0.41%   |
| HP Compaq          | 7         | 0.41%   |
| HP 14              | 7         | 0.41%   |
| ASRock A320M-HDV   | 7         | 0.41%   |
| Valve Jupiter      | 6         | 0.35%   |
| Lenovo ThinkSystem | 6         | 0.35%   |
| Lenovo Legion      | 6         | 0.35%   |
| AXIOO Mybook       | 6         | 0.35%   |
| ASUS X455LF        | 6         | 0.35%   |
| ASUS GL553VD       | 6         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 159       | 9.3%    |
| 2019    | 152       | 8.89%   |
| 2013    | 138       | 8.07%   |
| 2021    | 136       | 7.95%   |
| 2020    | 129       | 7.54%   |
| 2012    | 127       | 7.43%   |
| 2017    | 125       | 7.31%   |
| 2011    | 123       | 7.19%   |
| 2014    | 118       | 6.9%    |
| 2015    | 96        | 5.61%   |
| 2010    | 89        | 5.2%    |
| 2016    | 77        | 4.5%    |
| 2022    | 58        | 3.39%   |
| 2023    | 47        | 2.75%   |
| 2009    | 44        | 2.57%   |
| 2008    | 43        | 2.51%   |
| 2007    | 19        | 1.11%   |
| Unknown | 13        | 0.76%   |
| 2024    | 12        | 0.7%    |
| 2006    | 5         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1187      | 69.42%  |
| Desktop        | 393       | 22.98%  |
| Convertible    | 49        | 2.87%   |
| All in one     | 25        | 1.46%   |
| Server         | 21        | 1.23%   |
| Tablet         | 12        | 0.7%    |
| Mini pc        | 9         | 0.53%   |
| System on chip | 8         | 0.47%   |
| Phone          | 5         | 0.29%   |
| Other          | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1595      | 92.52%  |
| Enabled  | 129       | 7.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1706      | 99.77%  |
| Yes  | 4         | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 517       | 29.88%  |
| 3.01-4.0        | 408       | 23.58%  |
| 8.01-16.0       | 322       | 18.61%  |
| 16.01-24.0      | 240       | 13.87%  |
| 1.01-2.0        | 111       | 6.42%   |
| 32.01-64.0      | 68        | 3.93%   |
| 24.01-32.0      | 23        | 1.33%   |
| 2.01-3.0        | 17        | 0.98%   |
| 64.01-256.0     | 15        | 0.87%   |
| 0.51-1.0        | 8         | 0.46%   |
| More than 256.0 | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 621       | 32.87%  |
| 2.01-3.0   | 523       | 27.69%  |
| 4.01-8.0   | 290       | 15.35%  |
| 3.01-4.0   | 276       | 14.61%  |
| 0.51-1.0   | 108       | 5.72%   |
| 8.01-16.0  | 48        | 2.54%   |
| 0.01-0.5   | 10        | 0.53%   |
| 16.01-24.0 | 9         | 0.48%   |
| 24.01-32.0 | 2         | 0.11%   |
| 32.01-64.0 | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1151      | 65.7%   |
| 2       | 469       | 26.77%  |
| 3       | 81        | 4.62%   |
| 4       | 24        | 1.37%   |
| 0       | 11        | 0.63%   |
| 5       | 8         | 0.46%   |
| 6       | 3         | 0.17%   |
| 15      | 1         | 0.06%   |
| 12      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |
| 7       | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1220      | 70.68%  |
| Yes       | 506       | 29.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1388      | 81.12%  |
| No        | 323       | 18.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1480      | 86.05%  |
| No        | 240       | 13.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1141      | 66.03%  |
| No        | 587       | 33.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Indonesia | 1710      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Jakarta         | 469       | 25.12%  |
| Surabaya        | 158       | 8.46%   |
| Bandung         | 149       | 7.98%   |
| Yogyakarta      | 78        | 4.18%   |
| Semarang        | 57        | 3.05%   |
| Bogor           | 56        | 3%      |
| Bekasi          | 55        | 2.95%   |
| Tangerang       | 50        | 2.68%   |
| Malang          | 46        | 2.46%   |
| Medan           | 42        | 2.25%   |
| Denpasar        | 42        | 2.25%   |
| South Tangerang | 40        | 2.14%   |
| Depok           | 28        | 1.5%    |
| Palembang       | 23        | 1.23%   |
| Makassar        | 23        | 1.23%   |
| Banjarmasin     | 19        | 1.02%   |
| Sleman          | 15        | 0.8%    |
| Balikpapan      | 14        | 0.75%   |
| Tasikmalaya     | 13        | 0.7%    |
| Samarinda       | 13        | 0.7%    |
| Surakarta       | 11        | 0.59%   |
| Pontianak       | 11        | 0.59%   |
| Magelang        | 11        | 0.59%   |
| Gresik          | 11        | 0.59%   |
| Blitar          | 11        | 0.59%   |
| Kediri          | 10        | 0.54%   |
| Batam           | 10        | 0.54%   |
| Banda Aceh      | 10        | 0.54%   |
| Pekanbaru       | 9         | 0.48%   |
| Pasuruan        | 9         | 0.48%   |
| Cirebon         | 9         | 0.48%   |
| Mataram         | 8         | 0.43%   |
| Jember          | 8         | 0.43%   |
| Brebes          | 8         | 0.43%   |
| Sukabumi        | 7         | 0.37%   |
| Bandar Lampung  | 7         | 0.37%   |
| Purwokerto      | 6         | 0.32%   |
| Padang          | 6         | 0.32%   |
| Kudus           | 6         | 0.32%   |
| Klaten          | 6         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 410       | 555    | 17.71%  |
| WDC                         | 298       | 394    | 12.87%  |
| Samsung Electronics         | 208       | 277    | 8.98%   |
| Toshiba                     | 183       | 205    | 7.9%    |
| Sandisk                     | 89        | 108    | 3.84%   |
| HGST                        | 83        | 97     | 3.59%   |
| Unknown                     | 82        | 108    | 3.54%   |
| Hitachi                     | 76        | 95     | 3.28%   |
| Intel                       | 65        | 85     | 2.81%   |
| V-GeN                       | 59        | 65     | 2.55%   |
| A-DATA Technology           | 56        | 68     | 2.42%   |
| SK hynix                    | 54        | 62     | 2.33%   |
| Micron Technology           | 53        | 68     | 2.29%   |
| Kingston                    | 49        | 60     | 2.12%   |
| MidasForce                  | 42        | 49     | 1.81%   |
| Unknown                     | 37        | 41     | 1.6%    |
| Silicon Motion              | 30        | 35     | 1.3%    |
| China                       | 30        | 37     | 1.3%    |
| Team                        | 20        | 24     | 0.86%   |
| Apacer                      | 19        | 22     | 0.82%   |
| RX7                         | 17        | 21     | 0.73%   |
| JMicron Technology          | 17        | 18     | 0.73%   |
| VISIPRO                     | 15        | 19     | 0.65%   |
| Patriot                     | 15        | 30     | 0.65%   |
| ADATA Technology            | 15        | 28     | 0.65%   |
| KIOXIA                      | 13        | 16     | 0.56%   |
| Fujitsu                     | 13        | 14     | 0.56%   |
| EYOTA                       | 13        | 17     | 0.56%   |
| Crucial                     | 12        | 14     | 0.52%   |
| Apple                       | 12        | 14     | 0.52%   |
| Realtek Semiconductor       | 10        | 10     | 0.43%   |
| Hewlett-Packard             | 9         | 11     | 0.39%   |
| Transcend                   | 8         | 12     | 0.35%   |
| Phison Electronics          | 8         | 10     | 0.35%   |
| PNY                         | 7         | 8      | 0.3%    |
| XPG                         | 6         | 9      | 0.26%   |
| Pioneer                     | 6         | 6      | 0.26%   |
| Kingston Technology Company | 6         | 6      | 0.26%   |
| External                    | 6         | 6      | 0.26%   |
| Wellcomm                    | 5         | 5      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                       | 51        | 2.08%   |
| Seagate ST1000LM035-1RK172 1TB                        | 49        | 2%      |
| Unknown                                               | 37        | 1.51%   |
| Toshiba MQ01ABF050 500GB                              | 35        | 1.43%   |
| Toshiba MQ04ABF100 1TB                                | 33        | 1.35%   |
| Seagate ST3500312CS 500GB                             | 24        | 0.98%   |
| Toshiba MQ01ABD100 1TB                                | 23        | 0.94%   |
| Seagate ST500DM002-1BD142 500GB                       | 23        | 0.94%   |
| A-DATA SU650 120GB SSD                                | 23        | 0.94%   |
| HGST HTS545050A7E680 500GB                            | 22        | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 15        | 0.61%   |
| MidasForce SSD 128GB                                  | 15        | 0.61%   |
| Hitachi HTS543232A7A384 320GB                         | 15        | 0.61%   |
| Seagate ST500LT012-9WS142 500GB                       | 14        | 0.57%   |
| HGST HTS721010A9E630 1TB                              | 14        | 0.57%   |
| Unknown MMC Card  32GB                                | 12        | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 12        | 0.49%   |
| A-DATA SU650 240GB SSD                                | 12        | 0.49%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 11        | 0.45%   |
| Unknown MMC Card  64GB                                | 11        | 0.45%   |
| Seagate ST9500325AS 500GB                             | 11        | 0.45%   |
| Seagate ST9320325AS 320GB                             | 11        | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11        | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB                        | 11        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB                          | 11        | 0.45%   |
| Samsung SSD 860 EVO 250GB                             | 11        | 0.45%   |
| Samsung SSD 850 EVO 250GB                             | 11        | 0.45%   |
| JMicron Generic 500GB                                 | 11        | 0.45%   |
| Intel SSDPEKNW512G8 512GB                             | 11        | 0.45%   |
| Hitachi HTS545050A7E380 500GB                         | 11        | 0.45%   |
| HGST HTS545050A7E380 500GB                            | 11        | 0.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 10        | 0.41%   |
| Unknown MMC Card  128GB                               | 10        | 0.41%   |
| Seagate ST3250318AS 250GB                             | 10        | 0.41%   |
| Seagate ST1000LM049-2GH172 1TB                        | 10        | 0.41%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 10        | 0.41%   |
| HGST HTS725050A7E630 500GB                            | 10        | 0.41%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 9         | 0.37%   |
| MidasForce SSD 120GB                                  | 9         | 0.37%   |
| Kingston SA400S37120G 120GB SSD                       | 9         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 406       | 547    | 39.23%  |
| WDC                 | 235       | 311    | 22.71%  |
| Toshiba             | 160       | 177    | 15.46%  |
| HGST                | 83        | 97     | 8.02%   |
| Hitachi             | 76        | 95     | 7.34%   |
| Samsung Electronics | 13        | 13     | 1.26%   |
| JMicron Technology  | 12        | 12     | 1.16%   |
| Fujitsu             | 11        | 11     | 1.06%   |
| Unknown             | 9         | 10     | 0.87%   |
| Hewlett-Packard     | 7         | 9      | 0.68%   |
| External            | 6         | 6      | 0.58%   |
| Maxtor              | 4         | 4      | 0.39%   |
| Apple               | 4         | 4      | 0.39%   |
| TO Exter            | 2         | 2      | 0.19%   |
| Unknown             | 2         | 2      | 0.19%   |
| SYMTEC              | 1         | 1      | 0.1%    |
| HGST HTS            | 1         | 3      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| CLOVER              | 1         | 1      | 0.1%    |
| ASMT                | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 92        | 125    | 14.65%  |
| A-DATA Technology   | 42        | 51     | 6.69%   |
| SanDisk             | 41        | 54     | 6.53%   |
| MidasForce          | 41        | 48     | 6.53%   |
| WDC                 | 39        | 50     | 6.21%   |
| V-GeN               | 39        | 44     | 6.21%   |
| Kingston            | 32        | 36     | 5.1%    |
| China               | 30        | 37     | 4.78%   |
| Unknown             | 22        | 23     | 3.5%    |
| Apacer              | 19        | 22     | 3.03%   |
| Patriot             | 15        | 30     | 2.39%   |
| Team                | 12        | 16     | 1.91%   |
| VISIPRO             | 11        | 15     | 1.75%   |
| RX7                 | 11        | 12     | 1.75%   |
| EYOTA               | 11        | 14     | 1.75%   |
| Toshiba             | 10        | 11     | 1.59%   |
| Intel               | 10        | 14     | 1.59%   |
| Crucial             | 10        | 12     | 1.59%   |
| Micron Technology   | 8         | 12     | 1.27%   |
| Apple               | 7         | 8      | 1.11%   |
| Transcend           | 6         | 9      | 0.96%   |
| Seagate             | 6         | 6      | 0.96%   |
| Pioneer             | 6         | 6      | 0.96%   |
| Wellcomm            | 5         | 5      | 0.8%    |
| SK hynix            | 5         | 6      | 0.8%    |
| Ramos Technology    | 5         | 18     | 0.8%    |
| LITEONIT            | 5         | 6      | 0.8%    |
| LITEON              | 5         | 7      | 0.8%    |
| Unknown             | 4         | 5      | 0.64%   |
| PNY                 | 4         | 4      | 0.64%   |
| XSTAR               | 3         | 3      | 0.48%   |
| Varro               | 3         | 3      | 0.48%   |
| USB3.0              | 3         | 3      | 0.48%   |
| OCZ                 | 3         | 3      | 0.48%   |
| Netac               | 3         | 3      | 0.48%   |
| Lexar               | 3         | 3      | 0.48%   |
| Kingmax             | 3         | 3      | 0.48%   |
| GALAX               | 3         | 3      | 0.48%   |
| FORESEE             | 3         | 3      | 0.48%   |
| Colorful            | 3         | 3      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 920       | 1307   | 43.4%   |
| SSD     | 573       | 787    | 27.03%  |
| NVMe    | 497       | 660    | 23.44%  |
| Unknown | 66        | 77     | 3.11%   |
| MMC     | 64        | 89     | 3.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1279      | 2082   | 66.61%  |
| NVMe | 497       | 656    | 25.89%  |
| SAS  | 80        | 93     | 4.17%   |
| MMC  | 64        | 89     | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 978       | 1448   | 66.94%  |
| 0.51-1.0   | 393       | 516    | 26.9%   |
| 1.01-2.0   | 63        | 97     | 4.31%   |
| 3.01-4.0   | 11        | 16     | 0.75%   |
| 2.01-3.0   | 8         | 8      | 0.55%   |
| 4.01-10.0  | 7         | 8      | 0.48%   |
| 10.01-20.0 | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 511       | 28.31%  |
| 251-500        | 449       | 24.88%  |
| 501-1000       | 214       | 11.86%  |
| 51-100         | 180       | 9.97%   |
| 1-20           | 132       | 7.31%   |
| 1001-2000      | 117       | 6.48%   |
| 21-50          | 109       | 6.04%   |
| Unknown        | 37        | 2.05%   |
| More than 3000 | 33        | 1.83%   |
| 2001-3000      | 23        | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 701       | 37.37%  |
| 21-50          | 345       | 18.39%  |
| 101-250        | 259       | 13.81%  |
| 51-100         | 229       | 12.21%  |
| 251-500        | 159       | 8.48%   |
| 501-1000       | 94        | 5.01%   |
| Unknown        | 37        | 1.97%   |
| 1001-2000      | 29        | 1.55%   |
| More than 3000 | 13        | 0.69%   |
| 2001-3000      | 9         | 0.48%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                 | Computers | Drives | Percent |
|-------------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                       | 9         | 11     | 3.44%   |
| HGST HTS545050A7E680 500GB                            | 9         | 10     | 3.44%   |
| Seagate ST500LT012-1DG142 500GB                       | 8         | 9      | 3.05%   |
| Seagate ST500LT012-9WS142 500GB                       | 7         | 7      | 2.67%   |
| Seagate ST9500325AS 500GB                             | 5         | 5      | 1.91%   |
| HGST HTS545050A7E380 500GB                            | 5         | 6      | 1.91%   |
| Toshiba MQ01ABF050 500GB                              | 4         | 4      | 1.53%   |
| Seagate ST9320325AS 320GB                             | 4         | 4      | 1.53%   |
| Unknown                                               | 4         | 4      | 1.53%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 3         | 4      | 1.15%   |
| Toshiba MQ01ABD050 500GB                              | 3         | 3      | 1.15%   |
| Toshiba MQ01ABD032 320GB                              | 3         | 3      | 1.15%   |
| Seagate ST320LT012-9WS14C 320GB                       | 3         | 3      | 1.15%   |
| Seagate ST1000LX015-1U7172 1TB                        | 3         | 4      | 1.15%   |
| Seagate ST1000LM035-1RK172 1TB                        | 3         | 3      | 1.15%   |
| Hitachi HTS545050B9A300 500GB                         | 3         | 4      | 1.15%   |
| Hitachi HTS545050A7E380 500GB                         | 3         | 3      | 1.15%   |
| Hitachi HTS545032B9A300 320GB                         | 3         | 3      | 1.15%   |
| Hitachi HTS543232A7A384 320GB                         | 3         | 3      | 1.15%   |
| HGST HTS725050A7E630 500GB                            | 3         | 3      | 1.15%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2         | 2      | 0.76%   |
| WDC WD800JD-08LSA0 80GB                               | 2         | 2      | 0.76%   |
| WDC WD3200BEKT-60V5T1 320GB                           | 2         | 2      | 0.76%   |
| WDC WD3200AAKS-61L9A0 320GB                           | 2         | 3      | 0.76%   |
| WDC WD2000FYYZ-01UL1B1 2TB                            | 2         | 3      | 0.76%   |
| WDC WD10JPVX-60JC3T1 1TB                              | 2         | 2      | 0.76%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 2         | 4      | 0.76%   |
| WDC WD10EZEX-08M2NA0 1TB                              | 2         | 2      | 0.76%   |
| Toshiba MQ01ABD100 1TB                                | 2         | 2      | 0.76%   |
| Toshiba MK5059GSXP 500GB                              | 2         | 2      | 0.76%   |
| Toshiba MK3265GSX 320GB                               | 2         | 3      | 0.76%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                  | 2         | 2      | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 2      | 0.76%   |
| Seagate ST9500420AS 500GB                             | 2         | 2      | 0.76%   |
| Seagate ST9250410AS 250GB                             | 2         | 2      | 0.76%   |
| Seagate ST3500418AS 500GB                             | 2         | 2      | 0.76%   |
| Seagate ST250DM000-1BD141 250GB                       | 2         | 2      | 0.76%   |
| Seagate ST1000DM003-1ER162 1TB                        | 2         | 2      | 0.76%   |
| SanDisk SSD PLUS 120 GB                               | 2         | 2      | 0.76%   |
| Hitachi HTS545016B9A300 160GB                         | 2         | 2      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 88     | 28.46%  |
| WDC                 | 54        | 66     | 21.34%  |
| Toshiba             | 28        | 30     | 11.07%  |
| Hitachi             | 24        | 25     | 9.49%   |
| HGST                | 22        | 25     | 8.7%    |
| Samsung Electronics | 6         | 7      | 2.37%   |
| SanDisk             | 4         | 4      | 1.58%   |
| Micron Technology   | 4         | 4      | 1.58%   |
| A-DATA Technology   | 4         | 6      | 1.58%   |
| Unknown             | 4         | 4      | 1.58%   |
| Kingston            | 3         | 3      | 1.19%   |
| China               | 3         | 6      | 1.19%   |
| SK hynix            | 2         | 2      | 0.79%   |
| Silicon Motion      | 2         | 2      | 0.79%   |
| KLEVV               | 2         | 2      | 0.79%   |
| Fujitsu             | 2         | 2      | 0.79%   |
| Crucial             | 2         | 2      | 0.79%   |
| Apacer              | 2         | 3      | 0.79%   |
| WellcommMaster      | 1         | 1      | 0.4%    |
| Wellcomm            | 1         | 1      | 0.4%    |
| VISIPRO             | 1         | 3      | 0.4%    |
| ValueTech           | 1         | 1      | 0.4%    |
| V-GeN               | 1         | 1      | 0.4%    |
| Unknown             | 1         | 1      | 0.4%    |
| T-FORCE             | 1         | 1      | 0.4%    |
| RX7                 | 1         | 1      | 0.4%    |
| Maxtor              | 1         | 1      | 0.4%    |
| Intel               | 1         | 1      | 0.4%    |
| EYOTA               | 1         | 1      | 0.4%    |
| CLOVER              | 1         | 1      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 88     | 34.62%  |
| WDC                 | 52        | 64     | 25%     |
| Toshiba             | 28        | 30     | 13.46%  |
| Hitachi             | 24        | 25     | 11.54%  |
| HGST                | 22        | 25     | 10.58%  |
| Samsung Electronics | 3         | 3      | 1.44%   |
| Fujitsu             | 2         | 2      | 0.96%   |
| Unknown             | 1         | 1      | 0.48%   |
| Maxtor              | 1         | 1      | 0.48%   |
| CLOVER              | 1         | 1      | 0.48%   |
| Apple               | 1         | 1      | 0.48%   |
| Unknown             | 1         | 1      | 0.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 193       | 242    | 81.43%  |
| SSD  | 37        | 46     | 15.61%  |
| NVMe | 7         | 8      | 2.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB         | 2         | 2      | 25%     |
| WDC WD5000BPVT-60HXZT1 500GB      | 1         | 1      | 12.5%   |
| Toshiba MK2575GSX 250GB           | 1         | 1      | 12.5%   |
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 12.5%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 12.5%   |
| Hitachi HTS543232A7A384 320GB     | 1         | 1      | 12.5%   |
| A-DATA Technology SX8200PNP 256GB | 1         | 1      | 12.5%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 3         | 3      | 37.5%   |
| Hitachi           | 2         | 2      | 25%     |
| WDC               | 1         | 1      | 12.5%   |
| Toshiba           | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 902       | 1469   | 47.95%  |
| Works    | 740       | 1147   | 39.34%  |
| Malfunc  | 231       | 296    | 12.28%  |
| Failed   | 8         | 8      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1167      | 57.46%  |
| AMD                              | 332       | 16.35%  |
| Samsung Electronics              | 113       | 5.56%   |
| SanDisk                          | 74        | 3.64%   |
| SK hynix                         | 48        | 2.36%   |
| Micron Technology                | 45        | 2.22%   |
| Silicon Motion                   | 42        | 2.07%   |
| ADATA Technology                 | 33        | 1.62%   |
| Kingston Technology Company      | 23        | 1.13%   |
| Phison Electronics               | 22        | 1.08%   |
| Realtek Semiconductor            | 16        | 0.79%   |
| KIOXIA                           | 14        | 0.69%   |
| ASMedia Technology               | 13        | 0.64%   |
| Toshiba America Info Systems     | 12        | 0.59%   |
| MAXIO Technology (Hangzhou)      | 8         | 0.39%   |
| JMicron Technology               | 8         | 0.39%   |
| Union Memory (Shenzhen)          | 6         | 0.3%    |
| Broadcom / LSI                   | 6         | 0.3%    |
| Silicon Integrated Systems [SiS] | 5         | 0.25%   |
| Nvidia                           | 5         | 0.25%   |
| VIA Technologies                 | 4         | 0.2%    |
| Shenzhen Shichuangyi Electronics | 4         | 0.2%    |
| Micron/Crucial Technology        | 4         | 0.2%    |
| Hewlett-Packard                  | 4         | 0.2%    |
| Shenzhen Longsys Electronics     | 3         | 0.15%   |
| Marvell Technology Group         | 3         | 0.15%   |
| INNOGRIT                         | 3         | 0.15%   |
| O2 Micro                         | 2         | 0.1%    |
| LSI Logic / Symbios Logic        | 2         | 0.1%    |
| Adaptec                          | 2         | 0.1%    |
| Solidigm                         | 1         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Hosin Global Electronics         | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| Unknown                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 256       | 11.19%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 117       | 5.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 109       | 4.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 62        | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 61        | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 57        | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 54        | 2.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 50        | 2.19%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 49        | 2.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 47        | 2.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 42        | 1.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 41        | 1.79%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 38        | 1.66%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 35        | 1.53%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 32        | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 31        | 1.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 29        | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 26        | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 25        | 1.09%   |
| Intel SSD 660P Series                                                                   | 25        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 25        | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 25        | 1.09%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 24        | 1.05%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 24        | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 23        | 1.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 21        | 0.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 21        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 21        | 0.92%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 20        | 0.87%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 19        | 0.83%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 18        | 0.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 18        | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 17        | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 17        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 17        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17        | 0.74%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 16        | 0.7%    |
| AMD FCH IDE Controller                                                                  | 16        | 0.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 15        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1267      | 60.59%  |
| NVMe | 497       | 23.77%  |
| IDE  | 185       | 8.85%   |
| RAID | 138       | 6.6%    |
| SAS  | 3         | 0.14%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1271      | 74.33%  |
| AMD      | 425       | 24.85%  |
| ARM      | 10        | 0.58%   |
| QUALCOMM | 4         | 0.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 19        | 1.11%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 19        | 1.11%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 18        | 1.05%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 17        | 0.99%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 17        | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 0.93%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 16        | 0.93%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 15        | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 14        | 0.82%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 14        | 0.82%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 14        | 0.82%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 14        | 0.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 0.76%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 0.76%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 13        | 0.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 12        | 0.7%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 12        | 0.7%    |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 12        | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 11        | 0.64%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 11        | 0.64%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 0.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 11        | 0.64%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 11        | 0.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 0.64%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 11        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 0.58%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 10        | 0.58%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 10        | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 9         | 0.53%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 9         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 385       | 22.48%  |
| Intel Core i3           | 225       | 13.13%  |
| Intel Core i7           | 205       | 11.97%  |
| Other                   | 171       | 9.98%   |
| Intel Celeron           | 120       | 7.01%   |
| AMD Ryzen 5             | 107       | 6.25%   |
| Intel Core 2 Duo        | 61        | 3.56%   |
| AMD Ryzen 3             | 48        | 2.8%    |
| AMD Ryzen 7             | 46        | 2.69%   |
| Intel Pentium           | 37        | 2.16%   |
| AMD A8                  | 31        | 1.81%   |
| Intel Xeon              | 28        | 1.63%   |
| Intel Atom              | 23        | 1.34%   |
| Intel Pentium Dual-Core | 18        | 1.05%   |
| AMD A4                  | 18        | 1.05%   |
| AMD A6                  | 17        | 0.99%   |
| AMD FX                  | 12        | 0.7%    |
| AMD Athlon              | 12        | 0.7%    |
| Intel Core 2 Quad       | 11        | 0.64%   |
| AMD Ryzen 9             | 11        | 0.64%   |
| AMD E1                  | 11        | 0.64%   |
| AMD E                   | 11        | 0.64%   |
| AMD A10                 | 10        | 0.58%   |
| AMD Ryzen 5 PRO         | 9         | 0.53%   |
| Intel Core 2            | 8         | 0.47%   |
| Intel Genuine           | 7         | 0.41%   |
| AMD E2                  | 7         | 0.41%   |
| Intel Pentium Dual      | 6         | 0.35%   |
| AMD Athlon II X2        | 6         | 0.35%   |
| Intel Xeon Bronze       | 4         | 0.23%   |
| AMD Phenom II X6        | 4         | 0.23%   |
| AMD Athlon X4           | 4         | 0.23%   |
| QUALCOMM AArch64        | 3         | 0.18%   |
| Intel Pentium Silver    | 3         | 0.18%   |
| Intel Pentium Gold      | 3         | 0.18%   |
| AMD Phenom II X4        | 3         | 0.18%   |
| AMD C-60                | 3         | 0.18%   |
| Intel Xeon Silver       | 2         | 0.12%   |
| Intel Pentium D         | 2         | 0.12%   |
| Intel Core              | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 910       | 53.12%  |
| 4       | 512       | 29.89%  |
| 6       | 142       | 8.29%   |
| 8       | 73        | 4.26%   |
| 10      | 23        | 1.34%   |
| 12      | 18        | 1.05%   |
| 1       | 18        | 1.05%   |
| 14      | 6         | 0.35%   |
| 16      | 4         | 0.23%   |
| 3       | 3         | 0.18%   |
| Unknown | 3         | 0.18%   |
| 44      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1694      | 99.06%  |
| 2       | 11        | 0.64%   |
| Unknown | 3         | 0.18%   |
| 3       | 2         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1139      | 66.57%  |
| 1       | 569       | 33.26%  |
| Unknown | 3         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1679      | 98.19%  |
| Unknown        | 22        | 1.29%   |
| 64-bit         | 5         | 0.29%   |
| 32-bit         | 4         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 645       | 36.26%  |
| 0x206a7    | 92        | 5.17%   |
| 0x306a9    | 88        | 4.95%   |
| 0x1067a    | 50        | 2.81%   |
| 0x40651    | 44        | 2.47%   |
| 0x306c3    | 44        | 2.47%   |
| 0x806ec    | 34        | 1.91%   |
| 0x806ea    | 34        | 1.91%   |
| 0x306d4    | 34        | 1.91%   |
| 0x906ea    | 31        | 1.74%   |
| 0x08108109 | 30        | 1.69%   |
| 0x06006705 | 30        | 1.69%   |
| 0x806c1    | 27        | 1.52%   |
| 0x406e3    | 27        | 1.52%   |
| 0x806e9    | 26        | 1.46%   |
| 0x20655    | 24        | 1.35%   |
| 0x0a50000c | 21        | 1.18%   |
| 0x906e9    | 20        | 1.12%   |
| 0x08108102 | 19        | 1.07%   |
| 0x6fd      | 18        | 1.01%   |
| 0x806eb    | 16        | 0.9%    |
| 0x07030105 | 16        | 0.9%    |
| 0x20652    | 15        | 0.84%   |
| 0x706a8    | 14        | 0.79%   |
| 0x08608103 | 14        | 0.79%   |
| 0x706e5    | 13        | 0.73%   |
| 0x30678    | 13        | 0.73%   |
| 0x406c4    | 12        | 0.67%   |
| 0x06001119 | 12        | 0.67%   |
| 0x506e3    | 11        | 0.62%   |
| 0x0810100b | 11        | 0.62%   |
| 0x406c3    | 10        | 0.56%   |
| 0x08600104 | 10        | 0.56%   |
| 0x10676    | 9         | 0.51%   |
| 0x706a1    | 8         | 0.45%   |
| 0x0700010f | 8         | 0.45%   |
| 0x906a3    | 7         | 0.39%   |
| 0x6fb      | 7         | 0.39%   |
| 0x08101007 | 7         | 0.39%   |
| 0x05000119 | 7         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 259       | 15.14%  |
| SandyBridge      | 140       | 8.18%   |
| IvyBridge        | 140       | 8.18%   |
| Haswell          | 123       | 7.19%   |
| Unknown          | 93        | 5.44%   |
| Skylake          | 73        | 4.27%   |
| Penryn           | 73        | 4.27%   |
| Zen+             | 68        | 3.97%   |
| Westmere         | 65        | 3.8%    |
| Excavator        | 61        | 3.57%   |
| Silvermont       | 55        | 3.21%   |
| Broadwell        | 55        | 3.21%   |
| TigerLake        | 53        | 3.1%    |
| Zen 3            | 45        | 2.63%   |
| Zen 2            | 39        | 2.28%   |
| Core             | 37        | 2.16%   |
| Alderlake Hybrid | 37        | 2.16%   |
| Zen              | 36        | 2.1%    |
| Goldmont plus    | 35        | 2.05%   |
| Puma             | 31        | 1.81%   |
| IceLake          | 31        | 1.81%   |
| Piledriver       | 25        | 1.46%   |
| CometLake        | 24        | 1.4%    |
| Bobcat           | 19        | 1.11%   |
| K10              | 14        | 0.82%   |
| Goldmont         | 13        | 0.76%   |
| Jaguar           | 11        | 0.64%   |
| Bonnell          | 11        | 0.64%   |
| Nehalem          | 10        | 0.58%   |
| Steamroller      | 8         | 0.47%   |
| K10 Llano        | 8         | 0.47%   |
| Tremont          | 7         | 0.41%   |
| K8 Hammer        | 4         | 0.23%   |
| P6               | 2         | 0.12%   |
| NetBurst         | 2         | 0.12%   |
| Gracemont        | 2         | 0.12%   |
| Bulldozer        | 2         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1110      | 53.42%  |
| AMD                              | 520       | 25.02%  |
| Nvidia                           | 423       | 20.36%  |
| Matrox Electronics Systems       | 14        | 0.67%   |
| Silicon Integrated Systems [SiS] | 5         | 0.24%   |
| ASPEED Technology                | 5         | 0.24%   |
| Silicon Motion                   | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 118       | 5.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 91        | 4.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 64        | 2.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 61        | 2.84%   |
| Intel UHD Graphics 620                                                                   | 53        | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 51        | 2.37%   |
| Intel HD Graphics 620                                                                    | 47        | 2.19%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 45        | 2.09%   |
| Intel HD Graphics 5500                                                                   | 44        | 2.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 42        | 1.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 39        | 1.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 1.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 33        | 1.53%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 32        | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 1.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 1.35%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 29        | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.3%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 27        | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 1.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 27        | 1.26%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27        | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26        | 1.21%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 25        | 1.16%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 25        | 1.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 24        | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 22        | 1.02%   |
| AMD Lucienne                                                                             | 21        | 0.98%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 20        | 0.93%   |
| Intel HD Graphics 630                                                                    | 20        | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 0.79%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 17        | 0.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.74%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 15        | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 15        | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                               | 14        | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.65%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 14        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 774       | 44.95%  |
| 1 x AMD                | 367       | 21.31%  |
| Intel + Nvidia         | 251       | 14.58%  |
| 1 x Nvidia             | 121       | 7.03%   |
| Intel + AMD            | 63        | 3.66%   |
| AMD + Nvidia           | 46        | 2.67%   |
| 2 x AMD                | 45        | 2.61%   |
| Other                  | 16        | 0.93%   |
| 1 x Matrox             | 14        | 0.81%   |
| 2 x Intel              | 11        | 0.64%   |
| 1 x SiS                | 5         | 0.29%   |
| 1 x ASPEED             | 4         | 0.23%   |
| 2 x Nvidia             | 2         | 0.12%   |
| 1 x Silicon Motion     | 1         | 0.06%   |
| Nvidia + ASPEED        | 1         | 0.06%   |
| 1 x Intel + 4 x Nvidia | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1452      | 83.54%  |
| Proprietary | 212       | 12.2%   |
| Unknown     | 74        | 4.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1077      | 61.33%  |
| 1.01-2.0   | 247       | 14.07%  |
| 0.01-0.5   | 202       | 11.5%   |
| 0.51-1.0   | 104       | 5.92%   |
| 3.01-4.0   | 74        | 4.21%   |
| 7.01-8.0   | 20        | 1.14%   |
| 5.01-6.0   | 18        | 1.03%   |
| 8.01-16.0  | 8         | 0.46%   |
| 2.01-3.0   | 6         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 271       | 15.63%  |
| Chimei Innolux          | 261       | 15.05%  |
| BOE                     | 227       | 13.09%  |
| LG Display              | 162       | 9.34%   |
| Samsung Electronics     | 161       | 9.28%   |
| Goldstar                | 133       | 7.67%   |
| Dell                    | 63        | 3.63%   |
| Lenovo                  | 55        | 3.17%   |
| Hewlett-Packard         | 33        | 1.9%    |
| InfoVision              | 28        | 1.61%   |
| AOC                     | 28        | 1.61%   |
| Sharp                   | 21        | 1.21%   |
| PANDA                   | 21        | 1.21%   |
| Apple                   | 21        | 1.21%   |
| Acer                    | 21        | 1.21%   |
| ViewSonic               | 18        | 1.04%   |
| Philips                 | 17        | 0.98%   |
| BenQ                    | 13        | 0.75%   |
| Chi Mei Optoelectronics | 12        | 0.69%   |
| InnoLux Display         | 10        | 0.58%   |
| Toshiba                 | 9         | 0.52%   |
| LG Electronics          | 9         | 0.52%   |
| Mi                      | 8         | 0.46%   |
| Ancor Communications    | 8         | 0.46%   |
| Valve                   | 6         | 0.35%   |
| Panasonic               | 6         | 0.35%   |
| LG Philips              | 6         | 0.35%   |
| HKC                     | 6         | 0.35%   |
| CPT                     | 6         | 0.35%   |
| KDC                     | 5         | 0.29%   |
| HannStar                | 5         | 0.29%   |
| Unknown                 | 4         | 0.23%   |
| Sony                    | 4         | 0.23%   |
| RTK                     | 4         | 0.23%   |
| Quanta Display          | 4         | 0.23%   |
| QCM                     | 3         | 0.17%   |
| MSI                     | 3         | 0.17%   |
| KDB                     | 3         | 0.17%   |
| JRY                     | 3         | 0.17%   |
| CSO                     | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 26        | 1.48%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 22        | 1.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 21        | 1.2%    |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 21        | 1.2%    |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 19        | 1.08%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 18        | 1.02%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 17        | 0.97%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 16        | 0.91%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 15        | 0.85%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 15        | 0.85%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 14        | 0.8%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 13        | 0.74%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 13        | 0.74%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 13        | 0.74%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 12        | 0.68%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 11        | 0.63%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 11        | 0.63%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 11        | 0.63%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 10        | 0.57%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 9         | 0.51%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 9         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 8         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 8         | 0.46%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 8         | 0.46%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 8         | 0.46%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 7         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 7         | 0.4%    |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                  | 7         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.4%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.34%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 6         | 0.34%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 6         | 0.34%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 6         | 0.34%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 6         | 0.34%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                  | 6         | 0.34%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 6         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 717       | 42.73%  |
| 1920x1080 (FHD)    | 585       | 34.86%  |
| 3840x2160 (4K)     | 54        | 3.22%   |
| 1920x1200 (WUXGA)  | 49        | 2.92%   |
| 1440x900 (WXGA+)   | 42        | 2.5%    |
| 1600x900 (HD+)     | 39        | 2.32%   |
| 2560x1440 (QHD)    | 32        | 1.91%   |
| 1280x800 (WXGA)    | 31        | 1.85%   |
| 1360x768           | 21        | 1.25%   |
| 2880x1800          | 18        | 1.07%   |
| 1280x1024 (SXGA)   | 12        | 0.72%   |
| 2560x1600          | 11        | 0.66%   |
| 2560x1080          | 9         | 0.54%   |
| 800x1280           | 7         | 0.42%   |
| 3440x1440          | 6         | 0.36%   |
| 1680x1050 (WSXGA+) | 4         | 0.24%   |
| 1024x768 (XGA)     | 4         | 0.24%   |
| 1024x600           | 4         | 0.24%   |
| 2800x1752          | 3         | 0.18%   |
| 2160x1440          | 3         | 0.18%   |
| 1920x1280          | 3         | 0.18%   |
| 1280x720 (HD)      | 3         | 0.18%   |
| Unknown            | 3         | 0.18%   |
| 3840x2400          | 2         | 0.12%   |
| 3840x1080          | 2         | 0.12%   |
| 640x480            | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 3456x2160          | 1         | 0.06%   |
| 3200x1800 (QHD+)   | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |
| 2966x900           | 1         | 0.06%   |
| 2880x1920          | 1         | 0.06%   |
| 2736x1824          | 1         | 0.06%   |
| 2288x1287          | 1         | 0.06%   |
| 2256x1504          | 1         | 0.06%   |
| 2240x1400          | 1         | 0.06%   |
| 1920x550           | 1         | 0.06%   |
| 1280x960           | 1         | 0.06%   |
| 1152x864           | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 409       | 23.56%  |
| 14      | 388       | 22.35%  |
| 15      | 284       | 16.36%  |
| 18      | 104       | 5.99%   |
| 23      | 81        | 4.67%   |
| 21      | 66        | 3.8%    |
| 12      | 61        | 3.51%   |
| 24      | 48        | 2.76%   |
| 11      | 45        | 2.59%   |
| 19      | 43        | 2.48%   |
| 31      | 33        | 1.9%    |
| 27      | 32        | 1.84%   |
| Unknown | 31        | 1.79%   |
| 17      | 16        | 0.92%   |
| 34      | 13        | 0.75%   |
| 40      | 11        | 0.63%   |
| 16      | 10        | 0.58%   |
| 20      | 7         | 0.4%    |
| 7       | 7         | 0.4%    |
| 84      | 4         | 0.23%   |
| 48      | 4         | 0.23%   |
| 22      | 4         | 0.23%   |
| 10      | 4         | 0.23%   |
| 67      | 3         | 0.17%   |
| 52      | 3         | 0.17%   |
| 42      | 3         | 0.17%   |
| 72      | 2         | 0.12%   |
| 60      | 2         | 0.12%   |
| 54      | 2         | 0.12%   |
| 37      | 2         | 0.12%   |
| 32      | 2         | 0.12%   |
| 142     | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 57      | 1         | 0.06%   |
| 49      | 1         | 0.06%   |
| 46      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 35      | 1         | 0.06%   |
| 28      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 971       | 56.49%  |
| 401-500        | 211       | 12.27%  |
| 201-300        | 211       | 12.27%  |
| 501-600        | 156       | 9.08%   |
| 601-700        | 39        | 2.27%   |
| 351-400        | 34        | 1.98%   |
| Unknown        | 31        | 1.8%    |
| 701-800        | 20        | 1.16%   |
| 801-900        | 15        | 0.87%   |
| 1001-1500      | 14        | 0.81%   |
| 1501-2000      | 6         | 0.35%   |
| 1-100          | 6         | 0.35%   |
| 901-1000       | 3         | 0.17%   |
| More than 2000 | 1         | 0.06%   |
| 101-200        | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1376      | 85.68%  |
| 16/10   | 141       | 8.78%   |
| Unknown | 28        | 1.74%   |
| 21/9    | 15        | 0.93%   |
| 3/2     | 12        | 0.75%   |
| 5/4     | 11        | 0.68%   |
| 4/3     | 9         | 0.56%   |
| 0.67    | 6         | 0.37%   |
| 0.45    | 3         | 0.19%   |
| 32/9    | 2         | 0.12%   |
| 1.00    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |
| 0.56    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 711       | 41.1%   |
| 101-110        | 278       | 16.07%  |
| 201-250        | 156       | 9.02%   |
| 141-150        | 106       | 6.13%   |
| 71-80          | 77        | 4.45%   |
| 151-200        | 73        | 4.22%   |
| 61-70          | 59        | 3.41%   |
| 351-500        | 48        | 2.77%   |
| 51-60          | 45        | 2.6%    |
| 301-350        | 33        | 1.91%   |
| Unknown        | 31        | 1.79%   |
| More than 1000 | 23        | 1.33%   |
| 251-300        | 22        | 1.27%   |
| 501-1000       | 20        | 1.16%   |
| 91-100         | 13        | 0.75%   |
| 111-120        | 9         | 0.52%   |
| 121-130        | 8         | 0.46%   |
| 1-40           | 7         | 0.4%    |
| 131-140        | 6         | 0.35%   |
| 41-50          | 5         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 647       | 37.73%  |
| 121-160       | 471       | 27.46%  |
| 51-100        | 400       | 23.32%  |
| 161-240       | 108       | 6.3%    |
| Unknown       | 31        | 1.81%   |
| More than 240 | 30        | 1.75%   |
| 1-50          | 28        | 1.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1495      | 85.77%  |
| 2     | 161       | 9.24%   |
| 0     | 81        | 4.65%   |
| 3     | 6         | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1041      | 39.08%  |
| Intel                                  | 631       | 23.69%  |
| Qualcomm Atheros                       | 418       | 15.69%  |
| Broadcom                               | 150       | 5.63%   |
| MediaTek                               | 63        | 2.36%   |
| Ralink Technology                      | 55        | 2.06%   |
| TP-Link                                | 54        | 2.03%   |
| Xiaomi                                 | 38        | 1.43%   |
| Samsung Electronics                    | 27        | 1.01%   |
| Broadcom Limited                       | 22        | 0.83%   |
| Ralink                                 | 19        | 0.71%   |
| Qualcomm Atheros Communications        | 18        | 0.68%   |
| OPPO Electronics                       | 16        | 0.6%    |
| Marvell Technology Group               | 14        | 0.53%   |
| ASIX Electronics                       | 10        | 0.38%   |
| JMicron Technology                     | 8         | 0.3%    |
| Qualcomm                               | 7         | 0.26%   |
| IBM                                    | 6         | 0.23%   |
| Huawei Technologies                    | 6         | 0.23%   |
| D-Link                                 | 5         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.15%   |
| Sierra Wireless                        | 4         | 0.15%   |
| Nvidia                                 | 4         | 0.15%   |
| ICS Advent                             | 4         | 0.15%   |
| Ericsson Business Mobile Networks      | 4         | 0.15%   |
| D-Link System                          | 4         | 0.15%   |
| Attansic Technology                    | 3         | 0.11%   |
| AboCom Systems                         | 3         | 0.11%   |
| ZTopInc                                | 2         | 0.08%   |
| Lenovo                                 | 2         | 0.08%   |
| HMD Global                             | 2         | 0.08%   |
| Hewlett-Packard                        | 2         | 0.08%   |
| Edimax Technology                      | 2         | 0.08%   |
| ASUSTek Computer                       | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| vivo                                   | 1         | 0.04%   |
| VIA Technologies                       | 1         | 0.04%   |
| U-Blox                                 | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 667       | 21.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 189       | 6.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 100       | 3.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 85        | 2.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 72        | 2.3%    |
| Intel Wireless 8265 / 8275                                             | 55        | 1.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 55        | 1.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 53        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 45        | 1.44%   |
| Intel Wireless 7265                                                    | 43        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 40        | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 39        | 1.25%   |
| Ralink MT7601U Wireless Adapter                                        | 39        | 1.25%   |
| Intel Wi-Fi 6 AX201                                                    | 34        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 34        | 1.09%   |
| Intel Wi-Fi 6 AX200                                                    | 32        | 1.02%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 31        | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 31        | 0.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 30        | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 29        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 29        | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 28        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 26        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 26        | 0.83%   |
| Intel Wireless 7260                                                    | 25        | 0.8%    |
| Intel Wireless 8260                                                    | 24        | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 24        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                          | 24        | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 22        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 21        | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 21        | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 19        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                        | 18        | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 18        | 0.58%   |
| Intel Wireless 3165                                                    | 18        | 0.58%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 17        | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 17        | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                                  | 17        | 0.54%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 518       | 33.14%  |
| Qualcomm Atheros                | 360       | 23.03%  |
| Realtek Semiconductor           | 351       | 22.46%  |
| Broadcom                        | 101       | 6.46%   |
| Ralink Technology               | 55        | 3.52%   |
| MediaTek                        | 51        | 3.26%   |
| TP-Link                         | 47        | 3.01%   |
| Ralink                          | 19        | 1.22%   |
| Qualcomm Atheros Communications | 18        | 1.15%   |
| Broadcom Limited                | 18        | 1.15%   |
| D-Link                          | 5         | 0.32%   |
| Sierra Wireless                 | 4         | 0.26%   |
| AboCom Systems                  | 3         | 0.19%   |
| ZTopInc                         | 2         | 0.13%   |
| Edimax Technology               | 2         | 0.13%   |
| D-Link System                   | 2         | 0.13%   |
| Mercucys                        | 1         | 0.06%   |
| Marvell Technology Group        | 1         | 0.06%   |
| Linksys                         | 1         | 0.06%   |
| Fibocom                         | 1         | 0.06%   |
| Dell                            | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |
| ASUSTek Computer                | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 100       | 6.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 85        | 5.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 72        | 4.57%   |
| Intel Wireless 8265 / 8275                                     | 55        | 3.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 53        | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 45        | 2.86%   |
| Intel Wireless 7265                                            | 43        | 2.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 40        | 2.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 39        | 2.47%   |
| Ralink MT7601U Wireless Adapter                                | 39        | 2.47%   |
| Intel Wi-Fi 6 AX201                                            | 34        | 2.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 34        | 2.16%   |
| Intel Wi-Fi 6 AX200                                            | 32        | 2.03%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 31        | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 31        | 1.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 30        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 29        | 1.84%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 28        | 1.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 26        | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 26        | 1.65%   |
| Intel Wireless 7260                                            | 25        | 1.59%   |
| Intel Wireless 8260                                            | 24        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 24        | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                  | 24        | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21        | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 21        | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                | 18        | 1.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 18        | 1.14%   |
| Intel Wireless 3165                                            | 18        | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 16        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 16        | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 15        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 14        | 0.89%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 14        | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 11        | 0.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 11        | 0.7%    |
| Realtek 802.11n WLAN Adapter                                   | 10        | 0.63%   |
| Realtek 802.11ac NIC                                           | 10        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 901       | 59.59%  |
| Intel                                  | 267       | 17.66%  |
| Qualcomm Atheros                       | 105       | 6.94%   |
| Broadcom                               | 62        | 4.1%    |
| Xiaomi                                 | 38        | 2.51%   |
| Samsung Electronics                    | 19        | 1.26%   |
| OPPO Electronics                       | 16        | 1.06%   |
| MediaTek                               | 13        | 0.86%   |
| Marvell Technology Group               | 13        | 0.86%   |
| ASIX Electronics                       | 10        | 0.66%   |
| JMicron Technology                     | 8         | 0.53%   |
| TP-Link                                | 7         | 0.46%   |
| Qualcomm                               | 7         | 0.46%   |
| IBM                                    | 6         | 0.4%    |
| Broadcom Limited                       | 6         | 0.4%    |
| Silicon Integrated Systems [SiS]       | 4         | 0.26%   |
| Nvidia                                 | 4         | 0.26%   |
| ICS Advent                             | 4         | 0.26%   |
| Attansic Technology                    | 3         | 0.2%    |
| Lenovo                                 | 2         | 0.13%   |
| Huawei Technologies                    | 2         | 0.13%   |
| HMD Global                             | 2         | 0.13%   |
| Hewlett-Packard                        | 2         | 0.13%   |
| D-Link System                          | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.07%   |
| vivo                                   | 1         | 0.07%   |
| VIA Technologies                       | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| QinHeng Electronics                    | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |
| HTC (High Tech Computer)               | 1         | 0.07%   |
| Foxconn / Hon Hai                      | 1         | 0.07%   |
| ASUSTek Computer                       | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 667       | 43.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 189       | 12.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 55        | 3.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 29        | 1.89%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 21        | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 19        | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 19        | 1.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 17        | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                                  | 17        | 1.11%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 1.04%   |
| Realtek RTL8125 2.5GbE Controller                                      | 14        | 0.91%   |
| OPPO OnePlus Nord 4                                                    | 14        | 0.91%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 11        | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 10        | 0.65%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 9         | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9         | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 8         | 0.52%   |
| MediaTek Infinix SMART 5                                               | 8         | 0.52%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                               | 8         | 0.52%   |
| Intel 82574L Gigabit Network Connection                                | 8         | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                                  | 7         | 0.46%   |
| Intel 82579V Gigabit Network Connection                                | 7         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 6         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 6         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 6         | 0.39%   |
| Qualcomm Airtel 4G                                                     | 6         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 6         | 0.39%   |
| Intel Ethernet Controller I225-V                                       | 6         | 0.39%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                                   | 6         | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1480      | 51.32%  |
| Ethernet | 1387      | 48.09%  |
| Modem    | 17        | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1248      | 73.58%  |
| Ethernet | 445       | 26.24%  |
| Modem    | 3         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 996       | 58.08%  |
| 1     | 649       | 37.84%  |
| 0     | 35        | 2.04%   |
| 3     | 22        | 1.28%   |
| 4     | 11        | 0.64%   |
| 8     | 1         | 0.06%   |
| 6     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1587      | 91.58%  |
| Yes  | 146       | 8.42%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 425       | 36.92%  |
| Realtek Semiconductor           | 192       | 16.68%  |
| IMC Networks                    | 121       | 10.51%  |
| Qualcomm Atheros Communications | 94        | 8.17%   |
| Lite-On Technology              | 75        | 6.52%   |
| Cambridge Silicon Radio         | 59        | 5.13%   |
| Broadcom                        | 57        | 4.95%   |
| Foxconn / Hon Hai               | 40        | 3.48%   |
| Apple                           | 20        | 1.74%   |
| Toshiba                         | 16        | 1.39%   |
| Dell                            | 11        | 0.96%   |
| Ralink                          | 7         | 0.61%   |
| MediaTek                        | 7         | 0.61%   |
| Hewlett-Packard                 | 7         | 0.61%   |
| Foxconn International           | 5         | 0.43%   |
| Realtek                         | 3         | 0.26%   |
| ASUSTek Computer                | 3         | 0.26%   |
| Micro Star International        | 2         | 0.17%   |
| Marvell Semiconductor           | 2         | 0.17%   |
| Actions                         | 2         | 0.17%   |
| SINO WEALTH                     | 1         | 0.09%   |
| Chicony Electronics             | 1         | 0.09%   |
| Alps Electric                   | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 162       | 14.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 98        | 8.51%   |
| Realtek Bluetooth Radio                             | 88        | 7.65%   |
| Intel AX201 Bluetooth                               | 67        | 5.82%   |
| IMC Networks Bluetooth Device                       | 64        | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 59        | 5.13%   |
| Realtek  Bluetooth 4.2 Adapter                      | 47        | 4.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 47        | 4.08%   |
| Intel AX200 Bluetooth                               | 32        | 2.78%   |
| Lite-On Bluetooth Device                            | 27        | 2.35%   |
| IMC Networks Bluetooth Radio                        | 21        | 1.82%   |
| Intel AX211 Bluetooth                               | 20        | 1.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 1.65%   |
| IMC Networks Wireless_Device                        | 19        | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.56%   |
| Realtek 802.11ac WLAN Adapter                       | 17        | 1.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 1.48%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.48%   |
| Realtek RTL8723B Bluetooth                          | 14        | 1.22%   |
| Realtek RTL8821A Bluetooth                          | 13        | 1.13%   |
| Lite-On Wireless_Device                             | 13        | 1.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 1.13%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 11        | 0.96%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 10        | 0.87%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 10        | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.78%   |
| Lite-On Atheros Bluetooth                           | 8         | 0.7%    |
| Intel AX210 Bluetooth                               | 8         | 0.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 8         | 0.7%    |
| Ralink RT3290 Bluetooth                             | 7         | 0.61%   |
| MediaTek Wireless_Device                            | 7         | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 0.61%   |
| Apple Bluetooth Host Controller                     | 7         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.43%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                        | 5         | 0.43%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1226      | 60.84%  |
| AMD                                  | 479       | 23.77%  |
| Nvidia                               | 218       | 10.82%  |
| C-Media Electronics                  | 15        | 0.74%   |
| Generalplus Technology               | 11        | 0.55%   |
| JMTek                                | 8         | 0.4%    |
| Silicon Integrated Systems [SiS]     | 5         | 0.25%   |
| Logitech                             | 5         | 0.25%   |
| Texas Instruments                    | 4         | 0.2%    |
| Samson Technologies                  | 4         | 0.2%    |
| Creative Labs                        | 4         | 0.2%    |
| Jieli Technology                     | 3         | 0.15%   |
| ASUSTek Computer                     | 3         | 0.15%   |
| Yamaha                               | 2         | 0.1%    |
| STMicroelectronics                   | 2         | 0.1%    |
| SteelSeries ApS                      | 2         | 0.1%    |
| Samsung Electronics                  | 2         | 0.1%    |
| Razer USA                            | 2         | 0.1%    |
| KTMicro                              | 2         | 0.1%    |
| Barco Display Systems                | 2         | 0.1%    |
| Weltrend Semiconductor               | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| Solid State Logic                    | 1         | 0.05%   |
| SAVITECH                             | 1         | 0.05%   |
| Realtek Semiconductor                | 1         | 0.05%   |
| Nordic Semiconductor ASA             | 1         | 0.05%   |
| Kingston Technology                  | 1         | 0.05%   |
| Huawei Technologies                  | 1         | 0.05%   |
| Hewlett-Packard                      | 1         | 0.05%   |
| GYROCOM C&C                          | 1         | 0.05%   |
| GS3                                  | 1         | 0.05%   |
| Dell                                 | 1         | 0.05%   |
| Creative Technology                  | 1         | 0.05%   |
| Cooler Master                        | 1         | 0.05%   |
| Conexant Systems                     | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 207       | 8.15%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 148       | 5.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 136       | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 134       | 5.27%   |
| AMD FCH Azalia Controller                                                                         | 87        | 3.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 81        | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 77        | 3.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 68        | 2.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 61        | 2.4%    |
| Intel 8 Series HD Audio Controller                                                                | 61        | 2.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 59        | 2.32%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 57        | 2.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 56        | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 55        | 2.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 53        | 2.09%   |
| Intel Broadwell-U Audio Controller                                                                | 51        | 2.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 50        | 1.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 46        | 1.81%   |
| Intel Cannon Lake PCH cAVS                                                                        | 46        | 1.81%   |
| AMD High Definition Audio Controller                                                              | 45        | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 41        | 1.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 35        | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 1.38%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 33        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 32        | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 31        | 1.22%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 30        | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 26        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 25        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 22        | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 20        | 0.79%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 20        | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 19        | 0.75%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 19        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 18        | 0.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 341       | 27.04%  |
| SK hynix                                | 242       | 19.19%  |
| Micron Technology                       | 137       | 10.86%  |
| Kingston                                | 108       | 8.56%   |
| Unknown                                 | 105       | 8.33%   |
| Team                                    | 54        | 4.28%   |
| Corsair                                 | 53        | 4.2%    |
| V-GeN                                   | 37        | 2.93%   |
| Ramaxel Technology                      | 26        | 2.06%   |
| Elpida                                  | 25        | 1.98%   |
| Unknown                                 | 19        | 1.51%   |
| Nanya Technology                        | 15        | 1.19%   |
| Unknown (ABCD)                          | 12        | 0.95%   |
| A-DATA Technology                       | 12        | 0.95%   |
| G.Skill                                 | 9         | 0.71%   |
| Crucial                                 | 8         | 0.63%   |
| Transcend                               | 6         | 0.48%   |
| Apacer                                  | 4         | 0.32%   |
| Visipro                                 | 3         | 0.24%   |
| SHARETRONIC                             | 3         | 0.24%   |
| Patriot                                 | 3         | 0.24%   |
| Lexar                                   | 3         | 0.24%   |
| ASint Technology                        | 3         | 0.24%   |
| Unknown (0x0DD5)                        | 2         | 0.16%   |
| Shenzhen SCY                            | 2         | 0.16%   |
| KLEVV                                   | 2         | 0.16%   |
| Kingmax                                 | 2         | 0.16%   |
| Hewlett-Packard                         | 2         | 0.16%   |
| A Force                                 | 2         | 0.16%   |
| Unknown (940A)                          | 1         | 0.08%   |
| Unknown (8AA1)                          | 1         | 0.08%   |
| Unknown (8A02)                          | 1         | 0.08%   |
| Unknown (0x0080)                        | 1         | 0.08%   |
| Toshiba                                 | 1         | 0.08%   |
| Teikon                                  | 1         | 0.08%   |
| Super Talent                            | 1         | 0.08%   |
| Strontium                               | 1         | 0.08%   |
| Silicon Power Computer & Communications | 1         | 0.08%   |
| Silicon Power                           | 1         | 0.08%   |
| Qumo                                    | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 1.78%   |
| Unknown                                                          | 19        | 1.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.11%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 1.11%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 1.04%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 12        | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 12        | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.89%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 12        | 0.89%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 12        | 0.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 11        | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.67%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 9         | 0.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.67%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 9         | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.67%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 8         | 0.59%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 8         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 8         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 8         | 0.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.59%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s            | 8         | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.52%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 7         | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.52%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 6         | 0.45%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 6         | 0.45%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 6         | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.45%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 6         | 0.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 5         | 0.37%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 5         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 464       | 45.76%  |
| DDR3    | 379       | 37.38%  |
| LPDDR4  | 43        | 4.24%   |
| DDR2    | 34        | 3.35%   |
| SDRAM   | 27        | 2.66%   |
| LPDDR5  | 20        | 1.97%   |
| Unknown | 16        | 1.58%   |
| DDR5    | 14        | 1.38%   |
| LPDDR3  | 13        | 1.28%   |
| DRAM    | 2         | 0.2%    |
| DDR     | 2         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 726       | 72.67%  |
| DIMM         | 192       | 19.22%  |
| Row Of Chips | 70        | 7.01%   |
| Chip         | 6         | 0.6%    |
| Unknown      | 5         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 401       | 34.81%  |
| 8192  | 395       | 34.29%  |
| 2048  | 165       | 14.32%  |
| 16384 | 115       | 9.98%   |
| 32768 | 51        | 4.43%   |
| 1024  | 21        | 1.82%   |
| 512   | 2         | 0.17%   |
| 65536 | 1         | 0.09%   |
| 6144  | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 254       | 22.07%  |
| 3200    | 181       | 15.73%  |
| 2667    | 176       | 15.29%  |
| 2400    | 100       | 8.69%   |
| 1333    | 80        | 6.95%   |
| 2133    | 52        | 4.52%   |
| 1334    | 40        | 3.48%   |
| 3266    | 24        | 2.09%   |
| 1067    | 23        | 2%      |
| 800     | 22        | 1.91%   |
| Unknown | 21        | 1.82%   |
| 6400    | 16        | 1.39%   |
| 667     | 15        | 1.3%    |
| 4267    | 12        | 1.04%   |
| 3600    | 10        | 0.87%   |
| 1867    | 10        | 0.87%   |
| 4266    | 9         | 0.78%   |
| 3800    | 9         | 0.78%   |
| 1800    | 9         | 0.78%   |
| 8400    | 8         | 0.7%    |
| 4199    | 8         | 0.7%    |
| 5600    | 6         | 0.52%   |
| 4800    | 6         | 0.52%   |
| 3733    | 5         | 0.43%   |
| 2666    | 5         | 0.43%   |
| 1866    | 5         | 0.43%   |
| 1066    | 4         | 0.35%   |
| 533     | 4         | 0.35%   |
| 7500    | 3         | 0.26%   |
| 3400    | 3         | 0.26%   |
| 333     | 3         | 0.26%   |
| 5200    | 2         | 0.17%   |
| 3666    | 2         | 0.17%   |
| 3151    | 2         | 0.17%   |
| 2048    | 2         | 0.17%   |
| 975     | 2         | 0.17%   |
| 50410   | 1         | 0.09%   |
| 5500    | 1         | 0.09%   |
| 4040    | 1         | 0.09%   |
| 3866    | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 23        | 60.53%  |
| Hewlett-Packard    | 6         | 15.79%  |
| Canon              | 3         | 7.89%   |
| Brother Industries | 3         | 7.89%   |
| STMicroelectronics | 2         | 5.26%   |
| Fuji Xerox         | 1         | 2.63%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seiko Epson L120 Series             | 6         | 15.79%  |
| Seiko Epson L360 Series             | 5         | 13.16%  |
| Seiko Epson L312 Series             | 3         | 7.89%   |
| Seiko Epson L3210 Series            | 2         | 5.26%   |
| Seiko Epson L3110 Series            | 2         | 5.26%   |
| Seiko Epson L300 Series             | 2         | 5.26%   |
| Canon iP2700 series                 | 2         | 5.26%   |
| Brother DCP-T300                    | 2         | 5.26%   |
| STMicroelectronics USB Printer Port | 1         | 2.63%   |
| STMicroelectronics JRSVC Printer    | 1         | 2.63%   |
| Seiko Epson L386 Series             | 1         | 2.63%   |
| Seiko Epson L355 Series             | 1         | 2.63%   |
| Seiko Epson L1300 Series            | 1         | 2.63%   |
| HP LaserJet P1102                   | 1         | 2.63%   |
| HP LaserJet P1006                   | 1         | 2.63%   |
| HP LaserJet M101-M106               | 1         | 2.63%   |
| HP Ink Tank 110 series              | 1         | 2.63%   |
| HP DeskJet 5820 series              | 1         | 2.63%   |
| HP DeskJet 2130 series              | 1         | 2.63%   |
| Fuji Xerox DocuPrint M205 b         | 1         | 2.63%   |
| Canon CanoScan LiDE 300             | 1         | 2.63%   |
| Brother DCP-T310                    | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LIDE 25  | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |
| Canon CanoScan 4400F    | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 314       | 26.21%  |
| IMC Networks                           | 168       | 14.02%  |
| Realtek Semiconductor                  | 104       | 8.68%   |
| Bison Electronics                      | 79        | 6.59%   |
| Sunplus Innovation Technology          | 64        | 5.34%   |
| Quanta                                 | 60        | 5.01%   |
| Microdia                               | 57        | 4.76%   |
| Syntek                                 | 54        | 4.51%   |
| Cheng Uei Precision Industry (Foxlink) | 49        | 4.09%   |
| Suyin                                  | 28        | 2.34%   |
| Alcor Micro                            | 26        | 2.17%   |
| Luxvisions Innotech Limited            | 21        | 1.75%   |
| Lite-On Technology                     | 21        | 1.75%   |
| Acer                                   | 19        | 1.59%   |
| Apple                                  | 17        | 1.42%   |
| Sonix Technology                       | 16        | 1.34%   |
| Logitech                               | 12        | 1%      |
| Silicon Motion                         | 7         | 0.58%   |
| Ricoh                                  | 7         | 0.58%   |
| Lenovo                                 | 6         | 0.5%    |
| Importek                               | 6         | 0.5%    |
| Shinetech                              | 5         | 0.42%   |
| ANYKA                                  | 5         | 0.42%   |
| Samsung Electronics                    | 4         | 0.33%   |
| Primax Electronics                     | 4         | 0.33%   |
| Jieli Technology                       | 4         | 0.33%   |
| SunplusIT                              | 3         | 0.25%   |
| Generalplus Technology                 | 3         | 0.25%   |
| GEMBIRD                                | 3         | 0.25%   |
| Z-Star Microelectronics                | 2         | 0.17%   |
| Sunplus Technology                     | 2         | 0.17%   |
| SN0002                                 | 2         | 0.17%   |
| OPPO Electronics                       | 2         | 0.17%   |
| Huawei Technologies                    | 2         | 0.17%   |
| Cubeternet                             | 2         | 0.17%   |
| ALi                                    | 2         | 0.17%   |
| 2M UVC CAMERA                          | 2         | 0.17%   |
| Unknown                                | 2         | 0.17%   |
| WCM_USB                                | 1         | 0.08%   |
| vivo                                   | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 54        | 4.48%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 48        | 3.98%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 39        | 3.24%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 36        | 2.99%   |
| Chicony HD WebCam                                               | 36        | 2.99%   |
| Syntek Integrated Camera                                        | 33        | 2.74%   |
| IMC Networks Integrated Camera                                  | 27        | 2.24%   |
| Microdia Integrated_Webcam_HD                                   | 20        | 1.66%   |
| Chicony HP Truevision HD camera                                 | 20        | 1.66%   |
| Bison Integrated Camera                                         | 19        | 1.58%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 18        | 1.49%   |
| Realtek Integrated_Webcam_HD                                    | 18        | 1.49%   |
| Chicony USB2.0 HD UVC WebCam                                    | 18        | 1.49%   |
| Bison Lenovo EasyCamera                                         | 17        | 1.41%   |
| IMC Networks EasyCamera                                         | 14        | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 14        | 1.16%   |
| Sonix USB2.0 HD UVC WebCam                                      | 13        | 1.08%   |
| Quanta HD User Facing                                           | 12        | 1%      |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1%      |
| Chicony HP Truevision HD                                        | 11        | 0.91%   |
| Syntek EasyCamera                                               | 10        | 0.83%   |
| Sunplus Asus Webcam                                             | 10        | 0.83%   |
| Chicony Lenovo EasyCamera                                       | 10        | 0.83%   |
| Chicony EasyCamera                                              | 10        | 0.83%   |
| Syntek Lenovo EasyCamera                                        | 9         | 0.75%   |
| Sunplus Integrated_Webcam_HD                                    | 9         | 0.75%   |
| Realtek USB2.0 HD UVC WebCam                                    | 9         | 0.75%   |
| Realtek USB2.0 camera                                           | 9         | 0.75%   |
| Realtek USB Camera                                              | 9         | 0.75%   |
| Microdia Integrated Webcam                                      | 9         | 0.75%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 9         | 0.75%   |
| Chicony HD User Facing                                          | 9         | 0.75%   |
| Alcor Micro USB 2.0 Camera                                      | 9         | 0.75%   |
| Sunplus HD WebCam                                               | 8         | 0.66%   |
| Quanta VGA WebCam                                               | 8         | 0.66%   |
| Lite-On Integrated Camera                                       | 8         | 0.66%   |
| Chicony TOSHIBA Web Camera - HD                                 | 8         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 8         | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                              | 8         | 0.66%   |
| Suyin 1.3M HD WebCam                                            | 7         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 57        | 28.5%   |
| Synaptics                  | 47        | 23.5%   |
| Elan Microelectronics      | 34        | 17%     |
| Shenzhen Goodix Technology | 23        | 11.5%   |
| LighTuning Technology      | 14        | 7%      |
| AuthenTec                  | 11        | 5.5%    |
| Upek                       | 6         | 3%      |
| STMicroelectronics         | 4         | 2%      |
| Focal-systems.Corp         | 3         | 1.5%    |
| DigitalPersona             | 1         | 0.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 17        | 8.5%    |
| Elan ELAN:ARM-M4                                                           | 16        | 8%      |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 7.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 6.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 6.5%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 6.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 5.5%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 5.5%    |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 3.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 3%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 3%      |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 2.5%    |
| Synaptics WBDI                                                             | 5         | 2.5%    |
| Synaptics  WBDI                                                            | 5         | 2.5%    |
| Validity Sensors VFS491                                                    | 4         | 2%      |
| Synaptics UWP WBDI                                                         | 4         | 2%      |
| STMicroelectronics Fingerprint Reader                                      | 4         | 2%      |
| AuthenTec Fingerprint Sensor                                               | 4         | 2%      |
| AuthenTec AES1600                                                          | 4         | 2%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.5%    |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 3         | 1.5%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 1%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1%      |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1%      |
| Synaptics Prometheus Fingerprint Reader                                    | 2         | 1%      |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1%      |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.5%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.5%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.5%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.5%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.5%    |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.5%    |
| AuthenTec AES2810                                                          | 1         | 0.5%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 25        | 50%     |
| Alcor Micro | 11        | 22%     |
| O2 Micro    | 8         | 16%     |
| Upek        | 4         | 8%      |
| Lenovo      | 2         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 26%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 22%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 14%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 12%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 8%      |
| Broadcom 5880                                                                | 3         | 6%      |
| Broadcom 58200                                                               | 3         | 6%      |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4%      |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1250      | 71.67%  |
| 1     | 393       | 22.53%  |
| 2     | 81        | 4.64%   |
| 3     | 11        | 0.63%   |
| 4     | 6         | 0.34%   |
| 6     | 2         | 0.11%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 196       | 33.05%  |
| Graphics card            | 133       | 22.43%  |
| Net/wireless             | 74        | 12.48%  |
| Chipcard                 | 46        | 7.76%   |
| Multimedia controller    | 38        | 6.41%   |
| Communication controller | 27        | 4.55%   |
| Bluetooth                | 23        | 3.88%   |
| Camera                   | 14        | 2.36%   |
| Net/ethernet             | 12        | 2.02%   |
| Unassigned class         | 11        | 1.85%   |
| Storage                  | 4         | 0.67%   |
| Sound                    | 3         | 0.51%   |
| Flash memory             | 3         | 0.51%   |
| Storage/ide              | 2         | 0.34%   |
| Card reader              | 2         | 0.34%   |
| Wireless                 | 1         | 0.17%   |
| Video                    | 1         | 0.17%   |
| Network                  | 1         | 0.17%   |
| Modem                    | 1         | 0.17%   |
| Firewire controller      | 1         | 0.17%   |


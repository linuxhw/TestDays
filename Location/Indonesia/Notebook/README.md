Linux in Indonesia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Indonesia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 1739

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G40-45 80E1                 | [ac16ada090](https://linux-hardware.org/?probe=ac16ada090) | Jan 06, 2025 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | [a73526a4ad](https://linux-hardware.org/?probe=a73526a4ad) | Jan 04, 2025 |
| HP            | Pavilion Laptop 14-ec0xx... | [9bb39e061b](https://linux-hardware.org/?probe=9bb39e061b) | Jan 04, 2025 |
| Acer          | Aspire E5-552G              | [97430826f3](https://linux-hardware.org/?probe=97430826f3) | Jan 03, 2025 |
| Acer          | Aspire E5-552G              | [9b3e1c7a27](https://linux-hardware.org/?probe=9b3e1c7a27) | Jan 02, 2025 |
| Acer          | Aspire E5-552G              | [2cd3af691f](https://linux-hardware.org/?probe=2cd3af691f) | Jan 02, 2025 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [54b1993e1c](https://linux-hardware.org/?probe=54b1993e1c) | Jan 02, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3bb27ee500](https://linux-hardware.org/?probe=3bb27ee500) | Jan 02, 2025 |
| HP            | ProBook 440 G8 Notebook ... | [9829e4ea09](https://linux-hardware.org/?probe=9829e4ea09) | Jan 01, 2025 |
| MSI           | Katana A15 AI B8VE          | [2dc1c3f9ae](https://linux-hardware.org/?probe=2dc1c3f9ae) | Dec 27, 2024 |
| MSI           | Katana A15 AI B8VE          | [ae92e3f945](https://linux-hardware.org/?probe=ae92e3f945) | Dec 27, 2024 |
| HP            | ProBook 440 G5              | [eb07190046](https://linux-hardware.org/?probe=eb07190046) | Dec 27, 2024 |
| ASUSTek       | X455LD                      | [0695dcd803](https://linux-hardware.org/?probe=0695dcd803) | Dec 26, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [bc75be3895](https://linux-hardware.org/?probe=bc75be3895) | Dec 25, 2024 |
| HP            | Victus by Gaming Laptop ... | [e3ecdfe665](https://linux-hardware.org/?probe=e3ecdfe665) | Dec 23, 2024 |
| HP            | ProBook 450 G5              | [d884bdac45](https://linux-hardware.org/?probe=d884bdac45) | Dec 19, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [013dec6bfc](https://linux-hardware.org/?probe=013dec6bfc) | Dec 19, 2024 |
| Lenovo        | ThinkPad X260 20F5S0D501    | [d1c3cc5bc7](https://linux-hardware.org/?probe=d1c3cc5bc7) | Dec 18, 2024 |
| HP            | Notebook                    | [17804122c5](https://linux-hardware.org/?probe=17804122c5) | Dec 18, 2024 |
| HP            | Laptop 14-ck0xxx            | [eee288c125](https://linux-hardware.org/?probe=eee288c125) | Dec 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [eaa6397d5e](https://linux-hardware.org/?probe=eaa6397d5e) | Dec 16, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b200a9d4f6](https://linux-hardware.org/?probe=b200a9d4f6) | Dec 16, 2024 |
| Dell          | Latitude E7450              | [18a5e779b9](https://linux-hardware.org/?probe=18a5e779b9) | Dec 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [98e4e31c99](https://linux-hardware.org/?probe=98e4e31c99) | Dec 15, 2024 |
| ASUSTek       | X202E                       | [ff5d34316c](https://linux-hardware.org/?probe=ff5d34316c) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [8c4e0cc970](https://linux-hardware.org/?probe=8c4e0cc970) | Dec 15, 2024 |
| Lenovo        | G41-35 80M7                 | [771258a66a](https://linux-hardware.org/?probe=771258a66a) | Dec 14, 2024 |
| Sony          | VPCYB15AG                   | [2b66b4ead4](https://linux-hardware.org/?probe=2b66b4ead4) | Dec 14, 2024 |
| Fujitsu       | LIFEBOOK S762               | [de007da665](https://linux-hardware.org/?probe=de007da665) | Dec 13, 2024 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [4333cd141f](https://linux-hardware.org/?probe=4333cd141f) | Dec 13, 2024 |
| ASUSTek       | X450CP                      | [920b185ab5](https://linux-hardware.org/?probe=920b185ab5) | Dec 13, 2024 |
| Dell          | G3 3590                     | [9559e19b33](https://linux-hardware.org/?probe=9559e19b33) | Dec 12, 2024 |
| ADVAN         | 1405                        | [0c35574db2](https://linux-hardware.org/?probe=0c35574db2) | Dec 10, 2024 |
| Acer          | Swift SF314-56G             | [64815f9248](https://linux-hardware.org/?probe=64815f9248) | Dec 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [cbd8da337a](https://linux-hardware.org/?probe=cbd8da337a) | Dec 09, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [1b7baa72c2](https://linux-hardware.org/?probe=1b7baa72c2) | Dec 06, 2024 |
| Lenovo        | ThinkPad L480 20LTA02MJP    | [5816a82f83](https://linux-hardware.org/?probe=5816a82f83) | Dec 05, 2024 |
| AXIOO         | EduBook Air                 | [54b6286adc](https://linux-hardware.org/?probe=54b6286adc) | Dec 05, 2024 |
| AXIOO         | EduBook Air                 | [f71d5640ed](https://linux-hardware.org/?probe=f71d5640ed) | Dec 05, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [f28ca4079c](https://linux-hardware.org/?probe=f28ca4079c) | Dec 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [456d3c7b2d](https://linux-hardware.org/?probe=456d3c7b2d) | Nov 30, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | [a176cb1cfa](https://linux-hardware.org/?probe=a176cb1cfa) | Nov 30, 2024 |
| HP            | 250 G8 Notebook PC          | [0709f67f61](https://linux-hardware.org/?probe=0709f67f61) | Nov 29, 2024 |
| HP            | 250 G8 Notebook PC          | [3943e4d18a](https://linux-hardware.org/?probe=3943e4d18a) | Nov 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [d10b86c991](https://linux-hardware.org/?probe=d10b86c991) | Nov 29, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3757df02d2](https://linux-hardware.org/?probe=3757df02d2) | Nov 28, 2024 |
| HP            | EliteBook 840 G2            | [e7ffb651be](https://linux-hardware.org/?probe=e7ffb651be) | Nov 26, 2024 |
| HP            | EliteBook 8560w             | [5c651293f0](https://linux-hardware.org/?probe=5c651293f0) | Nov 25, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | [616dd41a0d](https://linux-hardware.org/?probe=616dd41a0d) | Nov 25, 2024 |
| Lenovo        | ThinkPad X270 20HMS2JD03    | [9cc08cb72c](https://linux-hardware.org/?probe=9cc08cb72c) | Nov 25, 2024 |
| AXIOO         | Hype 5 G12                  | [c05b80051b](https://linux-hardware.org/?probe=c05b80051b) | Nov 25, 2024 |
| Dell          | Latitude D620               | [b6bcc2c7f0](https://linux-hardware.org/?probe=b6bcc2c7f0) | Nov 25, 2024 |
| ASUSTek       | GL553VD                     | [2dc26b3608](https://linux-hardware.org/?probe=2dc26b3608) | Nov 22, 2024 |
| ASUSTek       | GL553VD                     | [05198e67f4](https://linux-hardware.org/?probe=05198e67f4) | Nov 22, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | [f3bc755a64](https://linux-hardware.org/?probe=f3bc755a64) | Nov 21, 2024 |
| Acer          | Aspire A514-54G             | [90415bf718](https://linux-hardware.org/?probe=90415bf718) | Nov 21, 2024 |
| Acer          | Aspire E1-531G              | [0dc612c4a9](https://linux-hardware.org/?probe=0dc612c4a9) | Nov 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [48d4b2b2d6](https://linux-hardware.org/?probe=48d4b2b2d6) | Nov 18, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | [4966e097ee](https://linux-hardware.org/?probe=4966e097ee) | Nov 17, 2024 |
| Lenovo        | ThinkPad 20NMS0C900         | [f32f6badec](https://linux-hardware.org/?probe=f32f6badec) | Nov 17, 2024 |
| Acer          | Aspire A514-54G             | [a965ec6798](https://linux-hardware.org/?probe=a965ec6798) | Nov 16, 2024 |
| Lenovo        | V330-14IKB 81B0             | [f6ebfc4fcb](https://linux-hardware.org/?probe=f6ebfc4fcb) | Nov 13, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3a28af2ad6](https://linux-hardware.org/?probe=3a28af2ad6) | Nov 13, 2024 |
| Acer          | Swift SF314-71              | [582c75cc01](https://linux-hardware.org/?probe=582c75cc01) | Nov 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [467624f847](https://linux-hardware.org/?probe=467624f847) | Nov 08, 2024 |
| AXIOO         | Mybook-14E                  | [32f6d232e2](https://linux-hardware.org/?probe=32f6d232e2) | Nov 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [2be2989e95](https://linux-hardware.org/?probe=2be2989e95) | Nov 05, 2024 |
| ASUSTek       | TP300LD                     | [3a6d49031d](https://linux-hardware.org/?probe=3a6d49031d) | Nov 04, 2024 |
| ASUSTek       | TP300LD                     | [551c5bff17](https://linux-hardware.org/?probe=551c5bff17) | Nov 03, 2024 |
| Acer          | Aspire A314-42P             | [3b985cceae](https://linux-hardware.org/?probe=3b985cceae) | Nov 03, 2024 |
| Acer          | Nitro ANV15-51              | [c135e3383d](https://linux-hardware.org/?probe=c135e3383d) | Nov 03, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0c49f1f721](https://linux-hardware.org/?probe=0c49f1f721) | Nov 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e9762f3377](https://linux-hardware.org/?probe=e9762f3377) | Oct 31, 2024 |
| ASUSTek       | K46CB                       | [e081c9ab8c](https://linux-hardware.org/?probe=e081c9ab8c) | Oct 30, 2024 |
| ASUSTek       | X441UV                      | [ef419e7dda](https://linux-hardware.org/?probe=ef419e7dda) | Oct 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d46929135e](https://linux-hardware.org/?probe=d46929135e) | Oct 25, 2024 |
| Acer          | Aspire AL14-31P             | [5dc0afb6b3](https://linux-hardware.org/?probe=5dc0afb6b3) | Oct 24, 2024 |
| HP            | G60                         | [34dc5984dc](https://linux-hardware.org/?probe=34dc5984dc) | Oct 23, 2024 |
| ASUSTek       | X441UV                      | [d5527bcd69](https://linux-hardware.org/?probe=d5527bcd69) | Oct 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2b9158e95b](https://linux-hardware.org/?probe=2b9158e95b) | Oct 22, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | [cfd54e896b](https://linux-hardware.org/?probe=cfd54e896b) | Oct 22, 2024 |
| Lenovo        | ThinkPad X230 2325YF3       | [b10ade1b28](https://linux-hardware.org/?probe=b10ade1b28) | Oct 19, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [7d19f92203](https://linux-hardware.org/?probe=7d19f92203) | Oct 18, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | [a15c3e921c](https://linux-hardware.org/?probe=a15c3e921c) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | [d8b92ea891](https://linux-hardware.org/?probe=d8b92ea891) | Oct 17, 2024 |
| itel Mobil... | Epic 1                      | [b99b7f9e7a](https://linux-hardware.org/?probe=b99b7f9e7a) | Oct 16, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | [fe47439b78](https://linux-hardware.org/?probe=fe47439b78) | Oct 15, 2024 |
| Acer          | Aspire A314-32              | [f0e0f318dd](https://linux-hardware.org/?probe=f0e0f318dd) | Oct 14, 2024 |
| Lenovo        | ThinkPad L512 4444PL4       | [2df5620570](https://linux-hardware.org/?probe=2df5620570) | Oct 12, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | [bcada5cbe6](https://linux-hardware.org/?probe=bcada5cbe6) | Oct 10, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | [7bf1c31e28](https://linux-hardware.org/?probe=7bf1c31e28) | Oct 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [b02ac16d4e](https://linux-hardware.org/?probe=b02ac16d4e) | Oct 08, 2024 |
| HP            | Laptop 14-em0xxx            | [f0fb885887](https://linux-hardware.org/?probe=f0fb885887) | Oct 07, 2024 |
| ASUSTek       | X555DG                      | [c602f86121](https://linux-hardware.org/?probe=c602f86121) | Oct 06, 2024 |
| Acer          | Aspire AL14-31P             | [b1fff870c3](https://linux-hardware.org/?probe=b1fff870c3) | Oct 05, 2024 |
| Dell          | Inspiron 5379               | [d4ec7c3588](https://linux-hardware.org/?probe=d4ec7c3588) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | [ba0935bde6](https://linux-hardware.org/?probe=ba0935bde6) | Oct 05, 2024 |
| Acer          | Aspire AG14-31P             | [f3c50b490a](https://linux-hardware.org/?probe=f3c50b490a) | Oct 05, 2024 |
| Dell          | Venue 11 Pro 7140           | [cd6776c30a](https://linux-hardware.org/?probe=cd6776c30a) | Oct 04, 2024 |
| Unknown       | Unknown                     | [cb3c212bc9](https://linux-hardware.org/?probe=cb3c212bc9) | Oct 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [8f6ef31fc0](https://linux-hardware.org/?probe=8f6ef31fc0) | Oct 01, 2024 |
| HP            | Victus by Gaming Laptop ... | [605995ef0d](https://linux-hardware.org/?probe=605995ef0d) | Oct 01, 2024 |
| Dell          | Latitude 3420               | [d7672fb8f4](https://linux-hardware.org/?probe=d7672fb8f4) | Sep 29, 2024 |
| Acer          | Predator PHN16-71           | [8815e16a5e](https://linux-hardware.org/?probe=8815e16a5e) | Sep 29, 2024 |
| Acer          | Okinawa                     | [dd1134eda8](https://linux-hardware.org/?probe=dd1134eda8) | Sep 28, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | [5adcba6b0e](https://linux-hardware.org/?probe=5adcba6b0e) | Sep 27, 2024 |
| Fujitsu       | LIFEBOOK T902               | [7b4b348c98](https://linux-hardware.org/?probe=7b4b348c98) | Sep 27, 2024 |
| Google        | Fleex                       | [05a6990467](https://linux-hardware.org/?probe=05a6990467) | Sep 27, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | [fe8af671af](https://linux-hardware.org/?probe=fe8af671af) | Sep 26, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [24a8743042](https://linux-hardware.org/?probe=24a8743042) | Sep 24, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [fd06da7fc1](https://linux-hardware.org/?probe=fd06da7fc1) | Sep 22, 2024 |
| Lenovo        | ThinkPad X100e 2876CTO      | [7282bf9e1e](https://linux-hardware.org/?probe=7282bf9e1e) | Sep 22, 2024 |
| Dell          | Latitude 3420               | [91dbcf2851](https://linux-hardware.org/?probe=91dbcf2851) | Sep 21, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [126bd31450](https://linux-hardware.org/?probe=126bd31450) | Sep 20, 2024 |
| Lenovo        | G400 20235                  | [96ebcfea10](https://linux-hardware.org/?probe=96ebcfea10) | Sep 18, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5R0U    | [ffe3da2a61](https://linux-hardware.org/?probe=ffe3da2a61) | Sep 17, 2024 |
| AXIOO         | MyBook Hype 5               | [d6b2a6bbbe](https://linux-hardware.org/?probe=d6b2a6bbbe) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [b105d16e70](https://linux-hardware.org/?probe=b105d16e70) | Sep 13, 2024 |
| Dell          | Latitude E7250              | [f5079722a9](https://linux-hardware.org/?probe=f5079722a9) | Sep 11, 2024 |
| Lenovo        | ThinkPad T480s 20L8S6360... | [488ff39e81](https://linux-hardware.org/?probe=488ff39e81) | Sep 10, 2024 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [5645aa8848](https://linux-hardware.org/?probe=5645aa8848) | Sep 05, 2024 |
| Dell          | XPS 9320                    | [27298b827b](https://linux-hardware.org/?probe=27298b827b) | Sep 03, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [45cfeca88a](https://linux-hardware.org/?probe=45cfeca88a) | Aug 31, 2024 |
| AXIOO         | PICO CJW                    | [3c7b0a8d95](https://linux-hardware.org/?probe=3c7b0a8d95) | Aug 31, 2024 |
| AXIOO         | PICO CJW                    | [6ba416a56c](https://linux-hardware.org/?probe=6ba416a56c) | Aug 31, 2024 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [8886ae523e](https://linux-hardware.org/?probe=8886ae523e) | Aug 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [5502afcee2](https://linux-hardware.org/?probe=5502afcee2) | Aug 29, 2024 |
| ASUSTek       | X455LF                      | [2ebd2ae224](https://linux-hardware.org/?probe=2ebd2ae224) | Aug 28, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [9d5c4db3d1](https://linux-hardware.org/?probe=9d5c4db3d1) | Aug 27, 2024 |
| Acer          | Aspire 4743                 | [2407fc17fc](https://linux-hardware.org/?probe=2407fc17fc) | Aug 27, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [98393b8796](https://linux-hardware.org/?probe=98393b8796) | Aug 23, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [8457bf32ea](https://linux-hardware.org/?probe=8457bf32ea) | Aug 23, 2024 |
| Dell          | Latitude 3410               | [0b09307b53](https://linux-hardware.org/?probe=0b09307b53) | Aug 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [59afcb4476](https://linux-hardware.org/?probe=59afcb4476) | Aug 21, 2024 |
| Toshiba       | TECRA Z40-A                 | [24e6b94f55](https://linux-hardware.org/?probe=24e6b94f55) | Aug 20, 2024 |
| Lenovo        | ThinkPad T61 7658CTO        | [c395b3e28c](https://linux-hardware.org/?probe=c395b3e28c) | Aug 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0b49e3d246](https://linux-hardware.org/?probe=0b49e3d246) | Aug 16, 2024 |
| Lenovo        | ThinkPad X240 20AMA3AECD    | [ca3f5f8a59](https://linux-hardware.org/?probe=ca3f5f8a59) | Aug 15, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [0e2d15df7c](https://linux-hardware.org/?probe=0e2d15df7c) | Aug 15, 2024 |
| ASUSTek       | GL552VW                     | [2a780be401](https://linux-hardware.org/?probe=2a780be401) | Aug 14, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [aee1dc9bfe](https://linux-hardware.org/?probe=aee1dc9bfe) | Aug 13, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [e322a156a0](https://linux-hardware.org/?probe=e322a156a0) | Aug 13, 2024 |
| Apple         | MacBookPro11,2              | [f11d04ee8e](https://linux-hardware.org/?probe=f11d04ee8e) | Aug 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [e6c64713c1](https://linux-hardware.org/?probe=e6c64713c1) | Aug 08, 2024 |
| HP            | Compaq 435                  | [4911c70481](https://linux-hardware.org/?probe=4911c70481) | Aug 08, 2024 |
| Valve         | Jupiter                     | [6afe9c392f](https://linux-hardware.org/?probe=6afe9c392f) | Aug 04, 2024 |
| Lenovo        | G400 20235                  | [ffa298e6de](https://linux-hardware.org/?probe=ffa298e6de) | Aug 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [1bae3fe2d4](https://linux-hardware.org/?probe=1bae3fe2d4) | Aug 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [058fa0e4aa](https://linux-hardware.org/?probe=058fa0e4aa) | Aug 01, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0d84b625a7](https://linux-hardware.org/?probe=0d84b625a7) | Jul 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [1329ba82ac](https://linux-hardware.org/?probe=1329ba82ac) | Jul 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [637e807f6a](https://linux-hardware.org/?probe=637e807f6a) | Jul 28, 2024 |
| Lenovo        | Y720-15IKB 80VR             | [0dbc5b0c8a](https://linux-hardware.org/?probe=0dbc5b0c8a) | Jul 26, 2024 |
| HP            | ProBook 440 G4              | [a2ffdc1d34](https://linux-hardware.org/?probe=a2ffdc1d34) | Jul 26, 2024 |
| Dell          | Inspiron 14-3462            | [13234332e1](https://linux-hardware.org/?probe=13234332e1) | Jul 25, 2024 |
| Lenovo        | G460 20041                  | [67670a0f4a](https://linux-hardware.org/?probe=67670a0f4a) | Jul 25, 2024 |
| Valve         | Jupiter                     | [79e199cee3](https://linux-hardware.org/?probe=79e199cee3) | Jul 24, 2024 |
| HP            | Laptop 15-bw0xx             | [e09128a4ab](https://linux-hardware.org/?probe=e09128a4ab) | Jul 22, 2024 |
| HP            | 14                          | [f418deebad](https://linux-hardware.org/?probe=f418deebad) | Jul 22, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L1400CDA... | [0ff73e973a](https://linux-hardware.org/?probe=0ff73e973a) | Jul 22, 2024 |
| Lenovo        | ThinkPad X230 2306A27       | [07e6f1b674](https://linux-hardware.org/?probe=07e6f1b674) | Jul 22, 2024 |
| Toshiba       | Satellite L510              | [97e25526be](https://linux-hardware.org/?probe=97e25526be) | Jul 21, 2024 |
| Lenovo        | G460 20041                  | [2baabb5540](https://linux-hardware.org/?probe=2baabb5540) | Jul 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [de93837a91](https://linux-hardware.org/?probe=de93837a91) | Jul 20, 2024 |
| Apple         | MacBookPro14,1              | [04a35f754e](https://linux-hardware.org/?probe=04a35f754e) | Jul 17, 2024 |
| ADVAN         | 1405                        | [fd0d652727](https://linux-hardware.org/?probe=fd0d652727) | Jul 17, 2024 |
| Toshiba       | Satellite L645              | [7c46019cc3](https://linux-hardware.org/?probe=7c46019cc3) | Jul 16, 2024 |
| ASUSTek       | X455LJ                      | [560bb80195](https://linux-hardware.org/?probe=560bb80195) | Jul 15, 2024 |
| ASUSTek       | X455LJ                      | [6364ad10c5](https://linux-hardware.org/?probe=6364ad10c5) | Jul 15, 2024 |
| Acer          | Aspire E5-475G              | [18965ce4ea](https://linux-hardware.org/?probe=18965ce4ea) | Jul 15, 2024 |
| Lenovo        | ThinkPad T480 20L6S1F20F    | [b9445ad087](https://linux-hardware.org/?probe=b9445ad087) | Jul 15, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | [9033123c38](https://linux-hardware.org/?probe=9033123c38) | Jul 15, 2024 |
| HP            | Laptop 14-bs1xx             | [cf4f3c0bb8](https://linux-hardware.org/?probe=cf4f3c0bb8) | Jul 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5482a0b3dc](https://linux-hardware.org/?probe=5482a0b3dc) | Jul 15, 2024 |
| Dell          | Latitude 5290 2-in-1        | [a7d115c7d5](https://linux-hardware.org/?probe=a7d115c7d5) | Jul 15, 2024 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [8e7672b34e](https://linux-hardware.org/?probe=8e7672b34e) | Jul 14, 2024 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [39b464c39e](https://linux-hardware.org/?probe=39b464c39e) | Jul 14, 2024 |
| HP            | Notebook                    | [76d1a8c671](https://linux-hardware.org/?probe=76d1a8c671) | Jul 14, 2024 |
| Acer          | Nitro AN515-58              | [d9aeff835a](https://linux-hardware.org/?probe=d9aeff835a) | Jul 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0837d07786](https://linux-hardware.org/?probe=0837d07786) | Jul 11, 2024 |
| Lenovo        | G40-45 80E1                 | [c5a2c8ebb0](https://linux-hardware.org/?probe=c5a2c8ebb0) | Jul 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [4da248e266](https://linux-hardware.org/?probe=4da248e266) | Jul 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [5c863e0d7c](https://linux-hardware.org/?probe=5c863e0d7c) | Jul 08, 2024 |
| Apple         | MacBookPro5,3               | [79a2ee9967](https://linux-hardware.org/?probe=79a2ee9967) | Jul 07, 2024 |
| HP            | Pavilion g4                 | [7dc29fa0b4](https://linux-hardware.org/?probe=7dc29fa0b4) | Jul 07, 2024 |
| Acer          | Swift SF314-71              | [7910b13b30](https://linux-hardware.org/?probe=7910b13b30) | Jul 06, 2024 |
| ASUSTek       | X201EV                      | [f02eb29877](https://linux-hardware.org/?probe=f02eb29877) | Jul 06, 2024 |
| Panasonic     | CFSZ6-2                     | [09991bde50](https://linux-hardware.org/?probe=09991bde50) | Jul 06, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [5988ce94ee](https://linux-hardware.org/?probe=5988ce94ee) | Jul 06, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | [5b5cf02ccc](https://linux-hardware.org/?probe=5b5cf02ccc) | Jul 05, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [6e79e0bd1e](https://linux-hardware.org/?probe=6e79e0bd1e) | Jul 04, 2024 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [83aba2641e](https://linux-hardware.org/?probe=83aba2641e) | Jul 04, 2024 |
| ADVAN         | 1701                        | [74128c428a](https://linux-hardware.org/?probe=74128c428a) | Jul 01, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [68fff6c23b](https://linux-hardware.org/?probe=68fff6c23b) | Jul 01, 2024 |
| Lenovo        | ThinkPad T520 423953J       | [01e5062809](https://linux-hardware.org/?probe=01e5062809) | Jun 29, 2024 |
| ADVAN         | 1701                        | [983e29b86d](https://linux-hardware.org/?probe=983e29b86d) | Jun 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [6dd3ef98e9](https://linux-hardware.org/?probe=6dd3ef98e9) | Jun 26, 2024 |
| AVITA         | NE14A2                      | [36e93c620c](https://linux-hardware.org/?probe=36e93c620c) | Jun 25, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [186d1f827c](https://linux-hardware.org/?probe=186d1f827c) | Jun 24, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [ab244cc45f](https://linux-hardware.org/?probe=ab244cc45f) | Jun 24, 2024 |
| Valve         | Jupiter                     | [49ade9d97b](https://linux-hardware.org/?probe=49ade9d97b) | Jun 24, 2024 |
| Lenovo        | ThinkPad T430 23476W7       | [52e6290d5d](https://linux-hardware.org/?probe=52e6290d5d) | Jun 20, 2024 |
| Lenovo        | ThinkPad L570 20J9S34000    | [a600d8246f](https://linux-hardware.org/?probe=a600d8246f) | Jun 18, 2024 |
| Valve         | Jupiter                     | [f2f1d90b24](https://linux-hardware.org/?probe=f2f1d90b24) | Jun 16, 2024 |
| ASUSTek       | ASUS Zenbook S 13 UX5304... | [66051331fd](https://linux-hardware.org/?probe=66051331fd) | Jun 11, 2024 |
| Toshiba       | dynabook R734/M             | [c8a799a398](https://linux-hardware.org/?probe=c8a799a398) | Jun 10, 2024 |
| HP            | Notebook                    | [4bbae416f7](https://linux-hardware.org/?probe=4bbae416f7) | Jun 09, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [d66cae1613](https://linux-hardware.org/?probe=d66cae1613) | Jun 08, 2024 |
| HP            | Laptop 14s-cf3xxx           | [fd48784b0f](https://linux-hardware.org/?probe=fd48784b0f) | Jun 08, 2024 |
| HP            | Victus by Gaming Laptop ... | [6cf80a06d1](https://linux-hardware.org/?probe=6cf80a06d1) | Jun 07, 2024 |
| AIO           | DynaBook e5                 | [0e4ad04db5](https://linux-hardware.org/?probe=0e4ad04db5) | Jun 06, 2024 |
| HP            | Laptop 14-bs0xx             | [9d0db9afbe](https://linux-hardware.org/?probe=9d0db9afbe) | Jun 06, 2024 |
| Apple         | MacBookPro9,2               | [be344b10dc](https://linux-hardware.org/?probe=be344b10dc) | Jun 05, 2024 |
| Toshiba       | dynabook R734/M             | [f539a0d213](https://linux-hardware.org/?probe=f539a0d213) | Jun 04, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [00dc39a0b7](https://linux-hardware.org/?probe=00dc39a0b7) | Jun 03, 2024 |
| Toshiba       | dynabook R731/C             | [e8f41ce95d](https://linux-hardware.org/?probe=e8f41ce95d) | Jun 02, 2024 |
| Toshiba       | dynabook R731/C             | [421ef5ca84](https://linux-hardware.org/?probe=421ef5ca84) | Jun 02, 2024 |
| ASUSTek       | GL552VW                     | [e29deb87ee](https://linux-hardware.org/?probe=e29deb87ee) | May 28, 2024 |
| Toshiba       | Satellite L740              | [af075df4bd](https://linux-hardware.org/?probe=af075df4bd) | May 25, 2024 |
| ASUSTek       | X200CA                      | [b4af45240b](https://linux-hardware.org/?probe=b4af45240b) | May 25, 2024 |
| Panasonic     | CFSZ5-2                     | [dd94dab0da](https://linux-hardware.org/?probe=dd94dab0da) | May 24, 2024 |
| Toshiba       | Satellite L740              | [471713a2b2](https://linux-hardware.org/?probe=471713a2b2) | May 24, 2024 |
| Chuwi         | FreeBook                    | [6cd2de3abd](https://linux-hardware.org/?probe=6cd2de3abd) | May 23, 2024 |
| HP            | Laptop 14-bs0xx             | [ba3f755558](https://linux-hardware.org/?probe=ba3f755558) | May 23, 2024 |
| Acer          | Swift SF313-51              | [80ad889357](https://linux-hardware.org/?probe=80ad889357) | May 20, 2024 |
| Acer          | Swift SF313-51              | [79d8372cf3](https://linux-hardware.org/?probe=79d8372cf3) | May 20, 2024 |
| Acer          | Aspire E5-471G              | [6ad4e168d9](https://linux-hardware.org/?probe=6ad4e168d9) | May 20, 2024 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [c761a6d766](https://linux-hardware.org/?probe=c761a6d766) | May 19, 2024 |
| AIO           | DynaBook e5                 | [061663a80d](https://linux-hardware.org/?probe=061663a80d) | May 15, 2024 |
| Lenovo        | ThinkPad X200 MFG_IN       | [2cd87a7d08](https://linux-hardware.org/?probe=2cd87a7d08) | May 14, 2024 |
| Lenovo        | IdeaPad S410p 20296         | [bda1d0daa6](https://linux-hardware.org/?probe=bda1d0daa6) | May 13, 2024 |
| HP            | Pavilion g4                 | [e4d725eba3](https://linux-hardware.org/?probe=e4d725eba3) | May 11, 2024 |
| Acer          | Aspire E5-411G              | [82675c702e](https://linux-hardware.org/?probe=82675c702e) | May 10, 2024 |
| HP            | Laptop 14-bw0xx             | [33b98e985f](https://linux-hardware.org/?probe=33b98e985f) | May 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [10c139f22b](https://linux-hardware.org/?probe=10c139f22b) | May 08, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [73ee3d2b74](https://linux-hardware.org/?probe=73ee3d2b74) | May 08, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [0ef70379ee](https://linux-hardware.org/?probe=0ef70379ee) | May 07, 2024 |
| ADVAN         | 1701                        | [e0928a1604](https://linux-hardware.org/?probe=e0928a1604) | May 06, 2024 |
| HP            | EliteBook 830 G5            | [7ad59bc402](https://linux-hardware.org/?probe=7ad59bc402) | May 05, 2024 |
| HP            | EliteBook 830 G5            | [a88155be11](https://linux-hardware.org/?probe=a88155be11) | May 05, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | [80f71c25c1](https://linux-hardware.org/?probe=80f71c25c1) | May 05, 2024 |
| HP            | EliteBook 840 G5            | [e200a00e5a](https://linux-hardware.org/?probe=e200a00e5a) | May 02, 2024 |
| realme        | CloudProXXXX                | [4a04219fcc](https://linux-hardware.org/?probe=4a04219fcc) | May 01, 2024 |
| ASUSTek       | X202E                       | [f782bac9e8](https://linux-hardware.org/?probe=f782bac9e8) | Apr 28, 2024 |
| HP            | 240 G8 Notebook PC          | [309c38a064](https://linux-hardware.org/?probe=309c38a064) | Apr 22, 2024 |
| ASUSTek       | X441SA                      | [4ebc6f3907](https://linux-hardware.org/?probe=4ebc6f3907) | Apr 22, 2024 |
| Apple         | MacBookPro11,2              | [802dfe39ec](https://linux-hardware.org/?probe=802dfe39ec) | Apr 20, 2024 |
| Acer          | Aspire A314-22              | [cb041e53b1](https://linux-hardware.org/?probe=cb041e53b1) | Apr 20, 2024 |
| ADVAN         | 1701                        | [a55c0ef710](https://linux-hardware.org/?probe=a55c0ef710) | Apr 19, 2024 |
| AXIOO         | NEON RNE                    | [a9f58cb42f](https://linux-hardware.org/?probe=a9f58cb42f) | Apr 16, 2024 |
| AXIOO         | NEON RNE                    | [e650f6d340](https://linux-hardware.org/?probe=e650f6d340) | Apr 16, 2024 |
| ASUSTek       | GL502VMZ                    | [6b670ef81e](https://linux-hardware.org/?probe=6b670ef81e) | Apr 10, 2024 |
| Lenovo        | V310-14ISK 80SX             | [74499eab00](https://linux-hardware.org/?probe=74499eab00) | Apr 07, 2024 |
| Dell          | Latitude 7400               | [063a09c041](https://linux-hardware.org/?probe=063a09c041) | Apr 05, 2024 |
| Lenovo        | IdeaPad S410p 20296         | [285b9be78c](https://linux-hardware.org/?probe=285b9be78c) | Apr 05, 2024 |
| ASUSTek       | X456UQ                      | [e7ae74a0ed](https://linux-hardware.org/?probe=e7ae74a0ed) | Apr 03, 2024 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [9bda4cf2a7](https://linux-hardware.org/?probe=9bda4cf2a7) | Apr 01, 2024 |
| Lenovo        | G460 20041                  | [1e27980b1d](https://linux-hardware.org/?probe=1e27980b1d) | Apr 01, 2024 |
| Clevo         | W240HU/W250HUQ              | [d9af69f439](https://linux-hardware.org/?probe=d9af69f439) | Apr 01, 2024 |
| ASUSTek       | K46CM                       | [81723c2d41](https://linux-hardware.org/?probe=81723c2d41) | Mar 27, 2024 |
| Lenovo        | ThinkPad T430 2342A19       | [d71f48c168](https://linux-hardware.org/?probe=d71f48c168) | Mar 25, 2024 |
| HP            | EliteBook 840 G6            | [dbb5c1fe9f](https://linux-hardware.org/?probe=dbb5c1fe9f) | Mar 20, 2024 |
| HP            | Victus by Gaming Laptop ... | [03556f08ce](https://linux-hardware.org/?probe=03556f08ce) | Mar 19, 2024 |
| HP            | Pavilion 15                 | [a9bc9facce](https://linux-hardware.org/?probe=a9bc9facce) | Mar 19, 2024 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [a781e10290](https://linux-hardware.org/?probe=a781e10290) | Mar 16, 2024 |
| Lenovo        | V310-14IKB 80T2             | [0018e3e74d](https://linux-hardware.org/?probe=0018e3e74d) | Mar 16, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c63d09f5fa](https://linux-hardware.org/?probe=c63d09f5fa) | Mar 15, 2024 |
| Google        | Coral                       | [415209f979](https://linux-hardware.org/?probe=415209f979) | Mar 15, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [3f7ac15be0](https://linux-hardware.org/?probe=3f7ac15be0) | Mar 15, 2024 |
| Dell          | Latitude 7480               | [13613ddbb8](https://linux-hardware.org/?probe=13613ddbb8) | Mar 14, 2024 |
| HP            | 248 G1                      | [918afcb1a0](https://linux-hardware.org/?probe=918afcb1a0) | Mar 07, 2024 |
| ADVAN         | 1405                        | [f11d45ddde](https://linux-hardware.org/?probe=f11d45ddde) | Mar 07, 2024 |
| AIO           | DynaBook e5                 | [877e963f0b](https://linux-hardware.org/?probe=877e963f0b) | Mar 06, 2024 |
| ASUSTek       | X453MA                      | [e1e03429e2](https://linux-hardware.org/?probe=e1e03429e2) | Mar 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [b11673c68a](https://linux-hardware.org/?probe=b11673c68a) | Mar 05, 2024 |
| HP            | 240 G7 Notebook PC          | [7556bb7dcb](https://linux-hardware.org/?probe=7556bb7dcb) | Mar 04, 2024 |
| ADVAN         | 1701                        | [c956a2409c](https://linux-hardware.org/?probe=c956a2409c) | Mar 03, 2024 |
| AIO           | DynaBook e5                 | [733a714da6](https://linux-hardware.org/?probe=733a714da6) | Mar 02, 2024 |
| Dell          | Latitude 7300               | [21fe8b5d70](https://linux-hardware.org/?probe=21fe8b5d70) | Feb 29, 2024 |
| Toshiba       | PORTEGE Z30-A               | [a685c7e5d5](https://linux-hardware.org/?probe=a685c7e5d5) | Feb 28, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [385221c459](https://linux-hardware.org/?probe=385221c459) | Feb 28, 2024 |
| Intel         | intibook                    | [7668db4bcd](https://linux-hardware.org/?probe=7668db4bcd) | Feb 27, 2024 |
| ASUSTek       | X441UA                      | [1185900ace](https://linux-hardware.org/?probe=1185900ace) | Feb 26, 2024 |
| Lenovo        | G40-45 80E1                 | [df12996678](https://linux-hardware.org/?probe=df12996678) | Feb 25, 2024 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4dd27fbd4e](https://linux-hardware.org/?probe=4dd27fbd4e) | Feb 23, 2024 |
| Dell          | Vostro 1014                 | [5fcabcc564](https://linux-hardware.org/?probe=5fcabcc564) | Feb 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [da357b8940](https://linux-hardware.org/?probe=da357b8940) | Feb 22, 2024 |
| Apple         | MacBookAir7,2               | [627c4721b6](https://linux-hardware.org/?probe=627c4721b6) | Feb 21, 2024 |
| ASUSTek       | G501JW                      | [fc8be1147a](https://linux-hardware.org/?probe=fc8be1147a) | Feb 21, 2024 |
| HP            | Laptop 14s-dq3xxx           | [fc0eb603fc](https://linux-hardware.org/?probe=fc0eb603fc) | Feb 18, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [129718807d](https://linux-hardware.org/?probe=129718807d) | Feb 17, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [7f6526b0a1](https://linux-hardware.org/?probe=7f6526b0a1) | Feb 17, 2024 |
| Dell          | Vostro 1540                 | [ed9ed14ad8](https://linux-hardware.org/?probe=ed9ed14ad8) | Feb 14, 2024 |
| AXIOO         | Slimbook 13                 | [6699ab5560](https://linux-hardware.org/?probe=6699ab5560) | Feb 14, 2024 |
| Lenovo        | G470 20078                  | [03e084a881](https://linux-hardware.org/?probe=03e084a881) | Feb 14, 2024 |
| ASUSTek       | GL552VW                     | [3d01ffb3f6](https://linux-hardware.org/?probe=3d01ffb3f6) | Feb 13, 2024 |
| Acer          | Swift SF314-71              | [7fe62a177a](https://linux-hardware.org/?probe=7fe62a177a) | Feb 10, 2024 |
| Lenovo        | S10-3                       | [e9d3156b70](https://linux-hardware.org/?probe=e9d3156b70) | Feb 09, 2024 |
| MSI           | Modern 14 B11MOU            | [da8a74088f](https://linux-hardware.org/?probe=da8a74088f) | Feb 09, 2024 |
| Acer          | Aspire A515-56              | [0786192aa8](https://linux-hardware.org/?probe=0786192aa8) | Feb 07, 2024 |
| Lenovo        | G40-45 80E1                 | [0f58d5d24e](https://linux-hardware.org/?probe=0f58d5d24e) | Feb 06, 2024 |
| realme        | CloudProXXXX                | [1299621a5e](https://linux-hardware.org/?probe=1299621a5e) | Feb 01, 2024 |
| Lenovo        | G405 20239                  | [7afc820794](https://linux-hardware.org/?probe=7afc820794) | Feb 01, 2024 |
| Lenovo        | ThinkPad L440 20ASS01400    | [c8fad8ec59](https://linux-hardware.org/?probe=c8fad8ec59) | Jan 28, 2024 |
| Dell          | XPS 9320                    | [0214714fb9](https://linux-hardware.org/?probe=0214714fb9) | Jan 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e6681b71bc](https://linux-hardware.org/?probe=e6681b71bc) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [65a3715aa3](https://linux-hardware.org/?probe=65a3715aa3) | Jan 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | [0e4d078f49](https://linux-hardware.org/?probe=0e4d078f49) | Jan 25, 2024 |
| Lenovo        | ThinkPad T480 20L6S3L400    | [3861071640](https://linux-hardware.org/?probe=3861071640) | Jan 24, 2024 |
| Clevo         | M720SRS                     | [c0f6248edd](https://linux-hardware.org/?probe=c0f6248edd) | Jan 24, 2024 |
| Lenovo        | G400 20235                  | [2097e4f7e6](https://linux-hardware.org/?probe=2097e4f7e6) | Jan 22, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [92f943771a](https://linux-hardware.org/?probe=92f943771a) | Jan 19, 2024 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | [9efd333805](https://linux-hardware.org/?probe=9efd333805) | Jan 18, 2024 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [22802134b7](https://linux-hardware.org/?probe=22802134b7) | Jan 15, 2024 |
| Lenovo        | ThinkPad T420 4180PV4       | [3277e75c3e](https://linux-hardware.org/?probe=3277e75c3e) | Jan 15, 2024 |
| HP            | 250 G5 Notebook PC          | [8fb1c8650f](https://linux-hardware.org/?probe=8fb1c8650f) | Jan 12, 2024 |
| Dell          | Vostro 3401                 | [cd47812859](https://linux-hardware.org/?probe=cd47812859) | Jan 11, 2024 |
| Unknown       | Unknown                     | [2d74d756b3](https://linux-hardware.org/?probe=2d74d756b3) | Jan 10, 2024 |
| Unknown       | DS16                        | [1951d37c43](https://linux-hardware.org/?probe=1951d37c43) | Jan 10, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9cfcebcd8c](https://linux-hardware.org/?probe=9cfcebcd8c) | Jan 09, 2024 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [0306a42404](https://linux-hardware.org/?probe=0306a42404) | Jan 09, 2024 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [825a5ed72b](https://linux-hardware.org/?probe=825a5ed72b) | Jan 08, 2024 |
| Dell          | Inspiron 3576               | [ff3dc4d39e](https://linux-hardware.org/?probe=ff3dc4d39e) | Jan 08, 2024 |
| HP            | Presario CQ42               | [6addf001a5](https://linux-hardware.org/?probe=6addf001a5) | Jan 08, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4572d32ab9](https://linux-hardware.org/?probe=4572d32ab9) | Jan 06, 2024 |
| HP            | Laptop 14s-cf3xxx           | [416bb92e6e](https://linux-hardware.org/?probe=416bb92e6e) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [afb1d878cd](https://linux-hardware.org/?probe=afb1d878cd) | Jan 04, 2024 |
| Lenovo        | ThinkPad X250 20CL001LUS    | [f0f3c9a66c](https://linux-hardware.org/?probe=f0f3c9a66c) | Jan 04, 2024 |
| Acidanther... | MacBookPro16,4              | [3c8c520472](https://linux-hardware.org/?probe=3c8c520472) | Jan 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | [6ea14ec02e](https://linux-hardware.org/?probe=6ea14ec02e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | [29ab65f09e](https://linux-hardware.org/?probe=29ab65f09e) | Jan 01, 2024 |
| Lenovo        | G400s 20244                 | [3afdb557c8](https://linux-hardware.org/?probe=3afdb557c8) | Jan 01, 2024 |
| Lenovo        | ThinkPad P50 20EQS3YS00     | [34294e5b8b](https://linux-hardware.org/?probe=34294e5b8b) | Dec 31, 2023 |
| ASUSTek       | X450CC                      | [0d985ff465](https://linux-hardware.org/?probe=0d985ff465) | Dec 31, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | [1192d8e746](https://linux-hardware.org/?probe=1192d8e746) | Dec 27, 2023 |
| Lenovo        | ThinkPad X220 4291G75       | [3fdb3a1cc7](https://linux-hardware.org/?probe=3fdb3a1cc7) | Dec 27, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [3bd91ab067](https://linux-hardware.org/?probe=3bd91ab067) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [d49a8fe4d4](https://linux-hardware.org/?probe=d49a8fe4d4) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [f1c9eab3f4](https://linux-hardware.org/?probe=f1c9eab3f4) | Dec 24, 2023 |
| ASUSTek       | X441BA                      | [04e5c55b92](https://linux-hardware.org/?probe=04e5c55b92) | Dec 23, 2023 |
| Dell          | Latitude E6400              | [67d4d37a04](https://linux-hardware.org/?probe=67d4d37a04) | Dec 20, 2023 |
| Lenovo        | ThinkPad T590 20N5S44300    | [5a90e712d1](https://linux-hardware.org/?probe=5a90e712d1) | Dec 19, 2023 |
| Lenovo        | V14-ADA 82C6                | [ec237cc638](https://linux-hardware.org/?probe=ec237cc638) | Dec 19, 2023 |
| Medion        | S17403                      | [250e479ad5](https://linux-hardware.org/?probe=250e479ad5) | Dec 18, 2023 |
| ASUSTek       | UX490UAR                    | [e8aa69b910](https://linux-hardware.org/?probe=e8aa69b910) | Dec 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b7194dbbb8](https://linux-hardware.org/?probe=b7194dbbb8) | Dec 15, 2023 |
| Acer          | Aspire E5-411G              | [f4af1a07e3](https://linux-hardware.org/?probe=f4af1a07e3) | Dec 15, 2023 |
| Lenovo        | ThinkPad L330 34701V0       | [d418989434](https://linux-hardware.org/?probe=d418989434) | Dec 15, 2023 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [e7d5f85bea](https://linux-hardware.org/?probe=e7d5f85bea) | Dec 13, 2023 |
| Dell          | Latitude E7240              | [4fcd011c61](https://linux-hardware.org/?probe=4fcd011c61) | Dec 13, 2023 |
| Lenovo        | V110-14IAP 80TF             | [e7bbe1d5e7](https://linux-hardware.org/?probe=e7bbe1d5e7) | Dec 10, 2023 |
| Acer          | Aspire E5-411G              | [72c0c4e3a0](https://linux-hardware.org/?probe=72c0c4e3a0) | Dec 09, 2023 |
| Dell          | Latitude E6400              | [0f4aeac8ca](https://linux-hardware.org/?probe=0f4aeac8ca) | Dec 09, 2023 |
| HP            | EliteBook 745 G6            | [29a2194396](https://linux-hardware.org/?probe=29a2194396) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1b3b476186](https://linux-hardware.org/?probe=1b3b476186) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [58547d36b7](https://linux-hardware.org/?probe=58547d36b7) | Dec 06, 2023 |
| Acer          | Aspire A314-22              | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [becdc5222d](https://linux-hardware.org/?probe=becdc5222d) | Dec 05, 2023 |
| ASUSTek       | X441BA                      | [272c82d8eb](https://linux-hardware.org/?probe=272c82d8eb) | Dec 05, 2023 |
| HP            | Laptop 14-em0xxx            | [b3a0f94dfd](https://linux-hardware.org/?probe=b3a0f94dfd) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [b3bc756e27](https://linux-hardware.org/?probe=b3bc756e27) | Dec 04, 2023 |
| Lenovo        | G400 20235                  | [9af224bc40](https://linux-hardware.org/?probe=9af224bc40) | Dec 04, 2023 |
| ASUSTek       | X441NA                      | [9a4c0266e8](https://linux-hardware.org/?probe=9a4c0266e8) | Dec 02, 2023 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | [f43aaf1d39](https://linux-hardware.org/?probe=f43aaf1d39) | Nov 29, 2023 |
| HP            | EliteBook 840 G2            | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| Valve         | Jupiter                     | [a6240c8d6a](https://linux-hardware.org/?probe=a6240c8d6a) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [95624a1d82](https://linux-hardware.org/?probe=95624a1d82) | Nov 18, 2023 |
| Dell          | XPS 9320                    | [04760461ba](https://linux-hardware.org/?probe=04760461ba) | Nov 17, 2023 |
| Acer          | Nitro AN515-57              | [39c7028c1e](https://linux-hardware.org/?probe=39c7028c1e) | Nov 15, 2023 |
| ADVAN         | 1405                        | [55a639a506](https://linux-hardware.org/?probe=55a639a506) | Nov 14, 2023 |
| ASUSTek       | T100TAS                     | [ff4068e60a](https://linux-hardware.org/?probe=ff4068e60a) | Nov 12, 2023 |
| Acer          | Swift SFX14-41G             | [be4c8862d0](https://linux-hardware.org/?probe=be4c8862d0) | Nov 11, 2023 |
| Acer          | Swift SF314-511             | [ba5db231dd](https://linux-hardware.org/?probe=ba5db231dd) | Nov 08, 2023 |
| Lenovo        | ThinkPad Edge E465 BE465... | [54b9aa1cac](https://linux-hardware.org/?probe=54b9aa1cac) | Nov 07, 2023 |
| Acer          | Swift SF314-511             | [1e2ba13164](https://linux-hardware.org/?probe=1e2ba13164) | Nov 06, 2023 |
| Lenovo        | IdeaPad S410p 20296         | [61828bc39f](https://linux-hardware.org/?probe=61828bc39f) | Nov 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [669430e32e](https://linux-hardware.org/?probe=669430e32e) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| Lenovo        | G40-45 80E1                 | [fffa5fb420](https://linux-hardware.org/?probe=fffa5fb420) | Nov 02, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [a7f47546e5](https://linux-hardware.org/?probe=a7f47546e5) | Nov 01, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [8901bca741](https://linux-hardware.org/?probe=8901bca741) | Nov 01, 2023 |
| HP            | EliteBook 2570p             | [bc8c6e67a9](https://linux-hardware.org/?probe=bc8c6e67a9) | Oct 28, 2023 |
| Acer          | Swift SFX14-41G             | [63b5c65c01](https://linux-hardware.org/?probe=63b5c65c01) | Oct 28, 2023 |
| Acer          | Aspire E5-411G              | [220dddac59](https://linux-hardware.org/?probe=220dddac59) | Oct 28, 2023 |
| Dell          | Precision 5530              | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| HP            | Notebook                    | [1f270f615f](https://linux-hardware.org/?probe=1f270f615f) | Oct 27, 2023 |
| Dell          | Inspiron One 2310           | [1a8d313e86](https://linux-hardware.org/?probe=1a8d313e86) | Oct 25, 2023 |
| Dell          | Latitude 5285               | [9af5195620](https://linux-hardware.org/?probe=9af5195620) | Oct 24, 2023 |
| Dell          | Latitude 5320               | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [5b608b97fc](https://linux-hardware.org/?probe=5b608b97fc) | Oct 23, 2023 |
| Dell          | Latitude 5285               | [9552613f54](https://linux-hardware.org/?probe=9552613f54) | Oct 23, 2023 |
| Dell          | Latitude E6320              | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| Dell          | Inspiron 3458               | [ff4adff045](https://linux-hardware.org/?probe=ff4adff045) | Oct 21, 2023 |
| Acer          | Aspire E5-411G              | [fe4a9ec4d0](https://linux-hardware.org/?probe=fe4a9ec4d0) | Oct 20, 2023 |
| ASUSTek       | S400CA                      | [1c0c1df851](https://linux-hardware.org/?probe=1c0c1df851) | Oct 20, 2023 |
| Toshiba       | dynabook R732/H             | [4852b6da95](https://linux-hardware.org/?probe=4852b6da95) | Oct 20, 2023 |
| HP            | Notebook                    | [3fb8313450](https://linux-hardware.org/?probe=3fb8313450) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | [71ffea0397](https://linux-hardware.org/?probe=71ffea0397) | Oct 19, 2023 |
| ASUSTek       | GL553VD                     | [9ab2c722a5](https://linux-hardware.org/?probe=9ab2c722a5) | Oct 19, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [459dc02cda](https://linux-hardware.org/?probe=459dc02cda) | Oct 18, 2023 |
| Acer          | Aspire E3-112M              | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [329a5f99e0](https://linux-hardware.org/?probe=329a5f99e0) | Oct 18, 2023 |
| MicroByte     | ezbook                      | [c67055c10c](https://linux-hardware.org/?probe=c67055c10c) | Oct 17, 2023 |
| MicroByte     | ezbook                      | [5018eaffae](https://linux-hardware.org/?probe=5018eaffae) | Oct 17, 2023 |
| Toshiba       | Satellite L645              | [5bea545bf5](https://linux-hardware.org/?probe=5bea545bf5) | Oct 16, 2023 |
| Valve         | Jupiter                     | [ec059c9ea7](https://linux-hardware.org/?probe=ec059c9ea7) | Oct 15, 2023 |
| Acer          | Swift SF314-511             | [3d63dd4590](https://linux-hardware.org/?probe=3d63dd4590) | Oct 13, 2023 |
| Toshiba       | Satellite C55D-C            | [e083a8012f](https://linux-hardware.org/?probe=e083a8012f) | Oct 11, 2023 |
| HP            | 430                         | [e62771b9a7](https://linux-hardware.org/?probe=e62771b9a7) | Oct 09, 2023 |
| HP            | 430                         | [71211a4eda](https://linux-hardware.org/?probe=71211a4eda) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f3348806a2](https://linux-hardware.org/?probe=f3348806a2) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | G40-45 80E1                 | [1bb42f8755](https://linux-hardware.org/?probe=1bb42f8755) | Oct 09, 2023 |
| Acer          | Swift SF314-56G             | [2696a8d9c0](https://linux-hardware.org/?probe=2696a8d9c0) | Oct 08, 2023 |
| Acidanther... | MacBookPro16,4              | [c40356b94d](https://linux-hardware.org/?probe=c40356b94d) | Oct 05, 2023 |
| Acer          | Swift SF314-56G             | [15b613a264](https://linux-hardware.org/?probe=15b613a264) | Oct 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [0df81159a2](https://linux-hardware.org/?probe=0df81159a2) | Oct 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a3773ae099](https://linux-hardware.org/?probe=a3773ae099) | Oct 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [25211e6ce1](https://linux-hardware.org/?probe=25211e6ce1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [810959ffa7](https://linux-hardware.org/?probe=810959ffa7) | Oct 01, 2023 |
| Acer          | Aspire E5-411G              | [80ac43658d](https://linux-hardware.org/?probe=80ac43658d) | Sep 30, 2023 |
| Lenovo        | ThinkPad L530 24783R8       | [eda040f456](https://linux-hardware.org/?probe=eda040f456) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| Acer          | Aspire E5-411G              | [eeb582da25](https://linux-hardware.org/?probe=eeb582da25) | Sep 28, 2023 |
| Dell          | Latitude 7490               | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| Dell          | Latitude 7490               | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Acer          | Nitro AN515-54              | [6383f263a8](https://linux-hardware.org/?probe=6383f263a8) | Sep 25, 2023 |
| Toshiba       | dynabook R632/H             | [7279759e40](https://linux-hardware.org/?probe=7279759e40) | Sep 25, 2023 |
| Acer          | Aspire S3                   | [4b2b76bdb3](https://linux-hardware.org/?probe=4b2b76bdb3) | Sep 24, 2023 |
| Acer          | Aspire S3                   | [723a872112](https://linux-hardware.org/?probe=723a872112) | Sep 24, 2023 |
| HUAWEI        | KPL-W0X                     | [3154e03d3f](https://linux-hardware.org/?probe=3154e03d3f) | Sep 22, 2023 |
| HP            | Laptop 14-ep0xxx            | [ee7b0c8506](https://linux-hardware.org/?probe=ee7b0c8506) | Sep 21, 2023 |
| Lenovo        | V14 G3 IAP 82TS             | [2528381c0e](https://linux-hardware.org/?probe=2528381c0e) | Sep 21, 2023 |
| HUAWEI        | KPL-W0X                     | [efafe71bd6](https://linux-hardware.org/?probe=efafe71bd6) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | [a1356bddb2](https://linux-hardware.org/?probe=a1356bddb2) | Sep 21, 2023 |
| HP            | Laptop 14s-dq3xxx           | [77e008b6d9](https://linux-hardware.org/?probe=77e008b6d9) | Sep 20, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [98a32c8241](https://linux-hardware.org/?probe=98a32c8241) | Sep 19, 2023 |
| HP            | EliteBook 8470p             | [a8995def08](https://linux-hardware.org/?probe=a8995def08) | Sep 19, 2023 |
| Lenovo        | G40-45 80E1                 | [417ad95c4c](https://linux-hardware.org/?probe=417ad95c4c) | Sep 18, 2023 |
| Lenovo        | G40-45 80E1                 | [c27b81ea3e](https://linux-hardware.org/?probe=c27b81ea3e) | Sep 17, 2023 |
| realme        | RMNBXXXX                    | [7f93463d6a](https://linux-hardware.org/?probe=7f93463d6a) | Sep 14, 2023 |
| realme        | RMNBXXXX                    | [a635ea5599](https://linux-hardware.org/?probe=a635ea5599) | Sep 14, 2023 |
| HP            | 245 G7 Notebook PC          | [ab68dea087](https://linux-hardware.org/?probe=ab68dea087) | Sep 14, 2023 |
| HP            | EliteBook 2570p             | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Acer          | Swift SF314-71              | [00e5dd81d7](https://linux-hardware.org/?probe=00e5dd81d7) | Sep 10, 2023 |
| Acer          | Aspire E5-411G              | [16c285bb07](https://linux-hardware.org/?probe=16c285bb07) | Sep 10, 2023 |
| Samsung       | RV413/RV513                 | [c59551fc6f](https://linux-hardware.org/?probe=c59551fc6f) | Sep 09, 2023 |
| ASUSTek       | X450CC                      | [5564e70c85](https://linux-hardware.org/?probe=5564e70c85) | Sep 09, 2023 |
| ASUSTek       | X201EP                      | [a714c5a35a](https://linux-hardware.org/?probe=a714c5a35a) | Sep 09, 2023 |
| HP            | Laptop 15-db1xxx            | [34e95a943a](https://linux-hardware.org/?probe=34e95a943a) | Sep 08, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [cbd5cf3e4b](https://linux-hardware.org/?probe=cbd5cf3e4b) | Sep 08, 2023 |
| Sony          | VGN-CS108D                  | [24bf5bb06c](https://linux-hardware.org/?probe=24bf5bb06c) | Sep 05, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [1a1c5e43bc](https://linux-hardware.org/?probe=1a1c5e43bc) | Sep 05, 2023 |
| AXIOO         | Mybook 14E                  | [b6ddb628dc](https://linux-hardware.org/?probe=b6ddb628dc) | Sep 04, 2023 |
| Acer          | Aspire A314-35              | [6edc4e910d](https://linux-hardware.org/?probe=6edc4e910d) | Sep 04, 2023 |
| HP            | EliteBook Revolve 810 G2    | [3f102b35e3](https://linux-hardware.org/?probe=3f102b35e3) | Sep 04, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [e27673ed4c](https://linux-hardware.org/?probe=e27673ed4c) | Sep 03, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [959fb04734](https://linux-hardware.org/?probe=959fb04734) | Sep 03, 2023 |
| Sony          | VPCYB15AG                   | [e192029ff0](https://linux-hardware.org/?probe=e192029ff0) | Sep 03, 2023 |
| Acer          | Aspire E5-475G              | [55542f9b89](https://linux-hardware.org/?probe=55542f9b89) | Aug 31, 2023 |
| Dell          | Latitude E6410              | [c2337bbe75](https://linux-hardware.org/?probe=c2337bbe75) | Aug 31, 2023 |
| Acer          | Aspire E5-411G              | [13ec5c53cf](https://linux-hardware.org/?probe=13ec5c53cf) | Aug 31, 2023 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [5cfa9a748f](https://linux-hardware.org/?probe=5cfa9a748f) | Aug 31, 2023 |
| Dell          | Inspiron 3585               | [02708536f4](https://linux-hardware.org/?probe=02708536f4) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [aa10544f35](https://linux-hardware.org/?probe=aa10544f35) | Aug 30, 2023 |
| Fujitsu       | FMVU14003                   | [8da3625e06](https://linux-hardware.org/?probe=8da3625e06) | Aug 27, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [5b334ec725](https://linux-hardware.org/?probe=5b334ec725) | Aug 27, 2023 |
| Acer          | Aspire E5-411G              | [1986877980](https://linux-hardware.org/?probe=1986877980) | Aug 25, 2023 |
| HP            | Laptop 15-db1xxx            | [2a72d00223](https://linux-hardware.org/?probe=2a72d00223) | Aug 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [f79de96905](https://linux-hardware.org/?probe=f79de96905) | Aug 23, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [abae84243d](https://linux-hardware.org/?probe=abae84243d) | Aug 23, 2023 |
| Dell          | Latitude E6410              | [fbaef9218f](https://linux-hardware.org/?probe=fbaef9218f) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8fd1db4fee](https://linux-hardware.org/?probe=8fd1db4fee) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2cbbb89cd4](https://linux-hardware.org/?probe=2cbbb89cd4) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [c47971e406](https://linux-hardware.org/?probe=c47971e406) | Aug 21, 2023 |
| Lenovo        | ThinkPad T540p 20BFS02S0... | [2f59ec7141](https://linux-hardware.org/?probe=2f59ec7141) | Aug 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | [f368b5bf17](https://linux-hardware.org/?probe=f368b5bf17) | Aug 18, 2023 |
| Toshiba       | Satellite L510              | [f06d068ca0](https://linux-hardware.org/?probe=f06d068ca0) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [b7a28997df](https://linux-hardware.org/?probe=b7a28997df) | Aug 15, 2023 |
| Acer          | Swift SF314-71              | [b78f4bf01d](https://linux-hardware.org/?probe=b78f4bf01d) | Aug 15, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| MSI           | Katana GF66 11UD            | [e7e9bfd605](https://linux-hardware.org/?probe=e7e9bfd605) | Aug 13, 2023 |
| Samsung       | 960XFH                      | [b7f35fe8b5](https://linux-hardware.org/?probe=b7f35fe8b5) | Aug 13, 2023 |
| HP            | EliteBook 820 G3            | [544810db31](https://linux-hardware.org/?probe=544810db31) | Aug 12, 2023 |
| Acer          | TravelMate B113             | [5d3d27c8bb](https://linux-hardware.org/?probe=5d3d27c8bb) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Lenovo        | G40-45 80E1                 | [49a3480efb](https://linux-hardware.org/?probe=49a3480efb) | Aug 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| Acer          | Aspire 4752                 | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| Acer          | Aspire 4750                 | [8491f5fc3b](https://linux-hardware.org/?probe=8491f5fc3b) | Aug 07, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [eab0544dc6](https://linux-hardware.org/?probe=eab0544dc6) | Aug 06, 2023 |
| HP            | ProBook 440 G3              | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| Dell          | Latitude E6410              | [ad46549b01](https://linux-hardware.org/?probe=ad46549b01) | Aug 04, 2023 |
| Dell          | Latitude E6410              | [e2364d5aac](https://linux-hardware.org/?probe=e2364d5aac) | Aug 04, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [73e1dd94b2](https://linux-hardware.org/?probe=73e1dd94b2) | Aug 02, 2023 |
| Lenovo        | ThinkPad Edge E330 33542... | [a13fd4044e](https://linux-hardware.org/?probe=a13fd4044e) | Aug 01, 2023 |
| ASUSTek       | TUF Gaming FX505DD          | [e965235133](https://linux-hardware.org/?probe=e965235133) | Jul 29, 2023 |
| Acer          | Aspire A315-42              | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [6632226064](https://linux-hardware.org/?probe=6632226064) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [24c092f0b0](https://linux-hardware.org/?probe=24c092f0b0) | Jul 26, 2023 |
| Lenovo        | ThinkPad X230 23246V9       | [e7bc7dac48](https://linux-hardware.org/?probe=e7bc7dac48) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Fujitsu       | FMVNC4BC4                   | [14249b136a](https://linux-hardware.org/?probe=14249b136a) | Jul 19, 2023 |
| Acer          | Aspire E5-476G              | [74af6477be](https://linux-hardware.org/?probe=74af6477be) | Jul 19, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| Acer          | Swift SF314-71              | [462a41184d](https://linux-hardware.org/?probe=462a41184d) | Jul 17, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [de7dbebf49](https://linux-hardware.org/?probe=de7dbebf49) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [fe9bfd5f77](https://linux-hardware.org/?probe=fe9bfd5f77) | Jul 10, 2023 |
| Acer          | Aspire 4937                 | [d4dadd2e77](https://linux-hardware.org/?probe=d4dadd2e77) | Jul 10, 2023 |
| HP            | ProBook 4420s               | [51e917f03e](https://linux-hardware.org/?probe=51e917f03e) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Toshiba       | PORTEGE R30-C               | [f07f4d423b](https://linux-hardware.org/?probe=f07f4d423b) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| Toshiba       | Satellite C640              | [680f3038da](https://linux-hardware.org/?probe=680f3038da) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| AZW           | Z85                         | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| Acer          | Aspire V5-471G              | [6dd5e93eea](https://linux-hardware.org/?probe=6dd5e93eea) | Jul 05, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [f1ad74f37a](https://linux-hardware.org/?probe=f1ad74f37a) | Jul 05, 2023 |
| Dell          | Latitude E6540              | [17ec85df62](https://linux-hardware.org/?probe=17ec85df62) | Jul 05, 2023 |
| Dell          | Latitude 3410               | [11d9814008](https://linux-hardware.org/?probe=11d9814008) | Jul 02, 2023 |
| ASUSTek       | X201EV                      | [a3fe51bc01](https://linux-hardware.org/?probe=a3fe51bc01) | Jun 30, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [14a983e6d3](https://linux-hardware.org/?probe=14a983e6d3) | Jun 30, 2023 |
| ASUSTek       | X201EV                      | [3cffef17f3](https://linux-hardware.org/?probe=3cffef17f3) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5873d04afe](https://linux-hardware.org/?probe=5873d04afe) | Jun 29, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [5f838f5922](https://linux-hardware.org/?probe=5f838f5922) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| Toshiba       | PORTEGE Z930                | [0cad0d9955](https://linux-hardware.org/?probe=0cad0d9955) | Jun 22, 2023 |
| Notebook      | P870DM                      | [cd318aa5a4](https://linux-hardware.org/?probe=cd318aa5a4) | Jun 21, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Lenovo        | IdeaPad S410p 20296         | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [42fd301e8b](https://linux-hardware.org/?probe=42fd301e8b) | Jun 19, 2023 |
| HP            | Laptop 17-ca0xxx            | [5296ca6ae2](https://linux-hardware.org/?probe=5296ca6ae2) | Jun 19, 2023 |
| HP            | Laptop 14s-dk1xxx           | [16bbd0f687](https://linux-hardware.org/?probe=16bbd0f687) | Jun 18, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d7e9625e19](https://linux-hardware.org/?probe=d7e9625e19) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eb0ba3c881](https://linux-hardware.org/?probe=eb0ba3c881) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [78f12c4671](https://linux-hardware.org/?probe=78f12c4671) | Jun 07, 2023 |
| Acer          | Aspire E5-411G              | [9a69b50d97](https://linux-hardware.org/?probe=9a69b50d97) | Jun 07, 2023 |
| Infinix       | INBook X1 Pro               | [c558de3b74](https://linux-hardware.org/?probe=c558de3b74) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Acer          | Swift SF314-511             | [6754a25d1d](https://linux-hardware.org/?probe=6754a25d1d) | Jun 03, 2023 |
| HP            | Laptop 14-bw0xx             | [3958079ad5](https://linux-hardware.org/?probe=3958079ad5) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| AXIOO         | Mybook-14E                  | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| ASUSTek       | X456URK                     | [6de2588617](https://linux-hardware.org/?probe=6de2588617) | May 29, 2023 |
| ASUSTek       | X456URK                     | [369aa4fc93](https://linux-hardware.org/?probe=369aa4fc93) | May 29, 2023 |
| ASUSTek       | X455LF                      | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| AVITA         | NE14A2                      | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [db7d7cf31d](https://linux-hardware.org/?probe=db7d7cf31d) | May 26, 2023 |
| Panasonic     | CFSZ5-2                     | [d5b1455382](https://linux-hardware.org/?probe=d5b1455382) | May 25, 2023 |
| HP            | Laptop 14s-cf2xxx           | [e51dec5daf](https://linux-hardware.org/?probe=e51dec5daf) | May 24, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [e752398b87](https://linux-hardware.org/?probe=e752398b87) | May 23, 2023 |
| HP            | Laptop 14s-dk1xxx           | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | [cfdb07c9ca](https://linux-hardware.org/?probe=cfdb07c9ca) | May 21, 2023 |
| Lenovo        | ThinkPad X260 20F5S53600    | [379bcdafa9](https://linux-hardware.org/?probe=379bcdafa9) | May 21, 2023 |
| Sony          | VPCSB35FG                   | [81d2592989](https://linux-hardware.org/?probe=81d2592989) | May 20, 2023 |
| Sony          | VPCSB35FG                   | [828fb24994](https://linux-hardware.org/?probe=828fb24994) | May 20, 2023 |
| Acer          | One Z1402                   | [390a684064](https://linux-hardware.org/?probe=390a684064) | May 16, 2023 |
| ASUSTek       | GL502VMK                    | [0b7232826d](https://linux-hardware.org/?probe=0b7232826d) | May 13, 2023 |
| HP            | Laptop 14s-cf0xxx           | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Infinix       | INBook X1                   | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Dell          | Inspiron 3505               | [e8f10d5f7e](https://linux-hardware.org/?probe=e8f10d5f7e) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| ASUSTek       | K42Jc                       | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| ASUSTek       | K42Jc                       | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Dell          | Latitude D630               | [0bef13413f](https://linux-hardware.org/?probe=0bef13413f) | May 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| Dell          | Latitude D630               | [d8ee0e7ca8](https://linux-hardware.org/?probe=d8ee0e7ca8) | May 02, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [9035ec79cd](https://linux-hardware.org/?probe=9035ec79cd) | May 02, 2023 |
| Acer          | Aspire A514-54G             | [adbd990ca2](https://linux-hardware.org/?probe=adbd990ca2) | Apr 29, 2023 |
| Dell          | Latitude D630               | [a3c3e09675](https://linux-hardware.org/?probe=a3c3e09675) | Apr 28, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c1616fcd6c](https://linux-hardware.org/?probe=c1616fcd6c) | Apr 28, 2023 |
| Dell          | Latitude D630               | [850df6e76f](https://linux-hardware.org/?probe=850df6e76f) | Apr 26, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [38d6a9b3d2](https://linux-hardware.org/?probe=38d6a9b3d2) | Apr 25, 2023 |
| HP            | Laptop 14-cm0xxx            | [4591d1bf9d](https://linux-hardware.org/?probe=4591d1bf9d) | Apr 24, 2023 |
| Valve         | Jupiter                     | [ff8440808f](https://linux-hardware.org/?probe=ff8440808f) | Apr 22, 2023 |
| Acer          | Swift SF314-511             | [96fd44e94a](https://linux-hardware.org/?probe=96fd44e94a) | Apr 20, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [6cf066b06b](https://linux-hardware.org/?probe=6cf066b06b) | Apr 19, 2023 |
| Acer          | Swift SFX14-41G             | [40ae403838](https://linux-hardware.org/?probe=40ae403838) | Apr 18, 2023 |
| AXIOO         | SlimBook 11                 | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| Dell          | Latitude 7300               | [1064b58edb](https://linux-hardware.org/?probe=1064b58edb) | Apr 13, 2023 |
| HP            | Laptop 14s-cf1xxx           | [76c9bf81a6](https://linux-hardware.org/?probe=76c9bf81a6) | Apr 12, 2023 |
| MSI           | Creator 15 A11UE            | [ca70d48c0e](https://linux-hardware.org/?probe=ca70d48c0e) | Apr 11, 2023 |
| HP            | Notebook                    | [584a741058](https://linux-hardware.org/?probe=584a741058) | Apr 08, 2023 |
| ASUSTek       | K46CM                       | [d878fad4d0](https://linux-hardware.org/?probe=d878fad4d0) | Apr 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [fcfcfdbbe7](https://linux-hardware.org/?probe=fcfcfdbbe7) | Apr 06, 2023 |
| Toshiba       | Satellite L640              | [8009d927db](https://linux-hardware.org/?probe=8009d927db) | Apr 05, 2023 |
| Lenovo        | ThinkPad Edge 0578RZ3       | [d37b6fa47b](https://linux-hardware.org/?probe=d37b6fa47b) | Apr 05, 2023 |
| Timi          | TM1703                      | [54b062157f](https://linux-hardware.org/?probe=54b062157f) | Apr 04, 2023 |
| AXIOO         | MYBOOK-14 .B001             | [edba1216c0](https://linux-hardware.org/?probe=edba1216c0) | Apr 04, 2023 |
| Dell          | Latitude 3410               | [0b29a27e88](https://linux-hardware.org/?probe=0b29a27e88) | Apr 03, 2023 |
| Dell          | Latitude 3410               | [9c8218ebd6](https://linux-hardware.org/?probe=9c8218ebd6) | Apr 03, 2023 |
| Acer          | Swift SFX14-41G             | [e60610d78a](https://linux-hardware.org/?probe=e60610d78a) | Apr 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [45c62cbb5c](https://linux-hardware.org/?probe=45c62cbb5c) | Apr 02, 2023 |
| Acer          | Aspire 4738Z                | [20e13078ef](https://linux-hardware.org/?probe=20e13078ef) | Apr 02, 2023 |
| Acer          | Aspire A515-56              | [a959d79d84](https://linux-hardware.org/?probe=a959d79d84) | Apr 01, 2023 |
| Acer          | Aspire A515-56              | [db53e1a333](https://linux-hardware.org/?probe=db53e1a333) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| MSI           | Bravo 15 B5DD               | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0e8125dc1f](https://linux-hardware.org/?probe=0e8125dc1f) | Mar 28, 2023 |
| Acer          | Aspire E5-411G              | [4ac3cde372](https://linux-hardware.org/?probe=4ac3cde372) | Mar 27, 2023 |
| ASUSTek       | X555BA                      | [f7d51f3c2f](https://linux-hardware.org/?probe=f7d51f3c2f) | Mar 26, 2023 |
| Acer          | Swift SF314-511             | [55c1b171dd](https://linux-hardware.org/?probe=55c1b171dd) | Mar 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ae09be520b](https://linux-hardware.org/?probe=ae09be520b) | Mar 25, 2023 |
| HP            | Pavilion 11 x360 PC         | [2c3c5a65a5](https://linux-hardware.org/?probe=2c3c5a65a5) | Mar 24, 2023 |
| MSI           | GF63 Thin 11SC              | [a63c9ded60](https://linux-hardware.org/?probe=a63c9ded60) | Mar 22, 2023 |
| MSI           | GF63 Thin 11SC              | [cc5ca6f040](https://linux-hardware.org/?probe=cc5ca6f040) | Mar 22, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bc39bd2ce5](https://linux-hardware.org/?probe=bc39bd2ce5) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [063ed79c8f](https://linux-hardware.org/?probe=063ed79c8f) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30t-C              | [7098d7537b](https://linux-hardware.org/?probe=7098d7537b) | Mar 15, 2023 |
| Lenovo        | G400s 20244                 | [fed6bb2c17](https://linux-hardware.org/?probe=fed6bb2c17) | Mar 13, 2023 |
| Dell          | Latitude E5440              | [fe81dc02b0](https://linux-hardware.org/?probe=fe81dc02b0) | Mar 13, 2023 |
| ASUSTek       | X455LF                      | [cda777dad9](https://linux-hardware.org/?probe=cda777dad9) | Mar 13, 2023 |
| AXIOO         | Mybook 14E                  | [1b6c10d1d8](https://linux-hardware.org/?probe=1b6c10d1d8) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2AX0... | [d6854dc15a](https://linux-hardware.org/?probe=d6854dc15a) | Mar 12, 2023 |
| Valve         | Jupiter                     | [f4ad14a82a](https://linux-hardware.org/?probe=f4ad14a82a) | Mar 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [439ea07bc5](https://linux-hardware.org/?probe=439ea07bc5) | Mar 08, 2023 |
| ADVAN         | 1405                        | [7f96f0214f](https://linux-hardware.org/?probe=7f96f0214f) | Mar 08, 2023 |
| Lenovo        | G40-80 80E4                 | [01dae27177](https://linux-hardware.org/?probe=01dae27177) | Mar 07, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [2cdcded03e](https://linux-hardware.org/?probe=2cdcded03e) | Mar 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fa94a404fa](https://linux-hardware.org/?probe=fa94a404fa) | Mar 04, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [9857559bb5](https://linux-hardware.org/?probe=9857559bb5) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [096c600c1d](https://linux-hardware.org/?probe=096c600c1d) | Mar 03, 2023 |
| Lenovo        | ThinkPad T580 20LAS35M00    | [cd8d61c1b6](https://linux-hardware.org/?probe=cd8d61c1b6) | Mar 03, 2023 |
| Google        | Vorticon                    | [7e9f3425ab](https://linux-hardware.org/?probe=7e9f3425ab) | Mar 03, 2023 |
| Google        | Vorticon                    | [aaa620e932](https://linux-hardware.org/?probe=aaa620e932) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cf806f07cb](https://linux-hardware.org/?probe=cf806f07cb) | Mar 02, 2023 |
| ASUSTek       | E202SA                      | [bccde0c9a5](https://linux-hardware.org/?probe=bccde0c9a5) | Feb 28, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| ASUSTek       | GL553VD                     | [302b65ed41](https://linux-hardware.org/?probe=302b65ed41) | Feb 25, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| Dell          | Inspiron 3476               | [58bff0319e](https://linux-hardware.org/?probe=58bff0319e) | Feb 24, 2023 |
| ASUSTek       | X441UA                      | [cd870fc3d3](https://linux-hardware.org/?probe=cd870fc3d3) | Feb 23, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [2953555c08](https://linux-hardware.org/?probe=2953555c08) | Feb 19, 2023 |
| Lenovo        | B40-70 20392                | [7197aacb00](https://linux-hardware.org/?probe=7197aacb00) | Feb 16, 2023 |
| Acer          | Swift SF314-511             | [71778cedf9](https://linux-hardware.org/?probe=71778cedf9) | Feb 16, 2023 |
| ASUSTek       | X200MA                      | [b01624da44](https://linux-hardware.org/?probe=b01624da44) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f6e519323b](https://linux-hardware.org/?probe=f6e519323b) | Feb 15, 2023 |
| Acer          | Aspire 4750                 | [ac80c33464](https://linux-hardware.org/?probe=ac80c33464) | Feb 14, 2023 |
| Acer          | Aspire 4732Z                | [abf9d41a29](https://linux-hardware.org/?probe=abf9d41a29) | Feb 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf015f98c2](https://linux-hardware.org/?probe=bf015f98c2) | Feb 14, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [a8a5ef19de](https://linux-hardware.org/?probe=a8a5ef19de) | Feb 13, 2023 |
| HP            | EliteBook 745 G6            | [9fd578a21d](https://linux-hardware.org/?probe=9fd578a21d) | Feb 13, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [608ce76690](https://linux-hardware.org/?probe=608ce76690) | Feb 13, 2023 |
| Toshiba       | Satellite L510              | [706759d61d](https://linux-hardware.org/?probe=706759d61d) | Feb 12, 2023 |
| Dell          | Vostro 3400                 | [89365a25ee](https://linux-hardware.org/?probe=89365a25ee) | Feb 12, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [f8f0fb1a21](https://linux-hardware.org/?probe=f8f0fb1a21) | Feb 11, 2023 |
| Timi          | RedmiBook 15                | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| Dell          | Studio XPS 1340             | [4c96fdcf99](https://linux-hardware.org/?probe=4c96fdcf99) | Feb 09, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [86297e5638](https://linux-hardware.org/?probe=86297e5638) | Feb 09, 2023 |
| Toshiba       | Satellite L735              | [99f282862c](https://linux-hardware.org/?probe=99f282862c) | Feb 08, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [06ffbacba3](https://linux-hardware.org/?probe=06ffbacba3) | Feb 08, 2023 |
| ASUSTek       | X455LF                      | [d60cd149fb](https://linux-hardware.org/?probe=d60cd149fb) | Feb 07, 2023 |
| ASUSTek       | P453UA                      | [476ff28577](https://linux-hardware.org/?probe=476ff28577) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [6fcc29607c](https://linux-hardware.org/?probe=6fcc29607c) | Feb 06, 2023 |
| Acer          | Aspire E5-476G              | [3b8e69dd3a](https://linux-hardware.org/?probe=3b8e69dd3a) | Feb 06, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [cfc187a64c](https://linux-hardware.org/?probe=cfc187a64c) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [74bf135ed9](https://linux-hardware.org/?probe=74bf135ed9) | Jan 31, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [e0c723e305](https://linux-hardware.org/?probe=e0c723e305) | Jan 31, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| Acer          | Swift SF314-71              | [41c052436a](https://linux-hardware.org/?probe=41c052436a) | Jan 30, 2023 |
| MSI           | Modern 14 A10RB             | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [c47b08d2a9](https://linux-hardware.org/?probe=c47b08d2a9) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [3b41afb262](https://linux-hardware.org/?probe=3b41afb262) | Jan 27, 2023 |
| HP            | 14                          | [53d080d83a](https://linux-hardware.org/?probe=53d080d83a) | Jan 27, 2023 |
| Dell          | Inspiron 3585               | [b41a540bb4](https://linux-hardware.org/?probe=b41a540bb4) | Jan 27, 2023 |
| Lenovo        | ThinkPad W520 4284Y54       | [acf75dbe88](https://linux-hardware.org/?probe=acf75dbe88) | Jan 26, 2023 |
| Acer          | Swift SF314-511             | [9c04ff43a3](https://linux-hardware.org/?probe=9c04ff43a3) | Jan 26, 2023 |
| Acer          | Aspire E1-421               | [16277f992b](https://linux-hardware.org/?probe=16277f992b) | Jan 23, 2023 |
| HP            | EliteBook 745 G3            | [1fda4d1e4a](https://linux-hardware.org/?probe=1fda4d1e4a) | Jan 23, 2023 |
| Acer          | Swift SF314-71              | [9cee6edc8e](https://linux-hardware.org/?probe=9cee6edc8e) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| ASUSTek       | X455LF                      | [9995b86c04](https://linux-hardware.org/?probe=9995b86c04) | Jan 18, 2023 |
| Acer          | Aspire E1-421               | [855c9b8e45](https://linux-hardware.org/?probe=855c9b8e45) | Jan 18, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | [58f2d0e1b4](https://linux-hardware.org/?probe=58f2d0e1b4) | Jan 12, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| ASUSTek       | X456URK                     | [09c6b0ed0a](https://linux-hardware.org/?probe=09c6b0ed0a) | Jan 12, 2023 |
| Acer          | AO756                       | [e0332e892a](https://linux-hardware.org/?probe=e0332e892a) | Jan 11, 2023 |
| HP            | EliteBook 840 G3            | [5de089f4c0](https://linux-hardware.org/?probe=5de089f4c0) | Jan 08, 2023 |
| HP            | EliteBook 840 G3            | [d47b3555d6](https://linux-hardware.org/?probe=d47b3555d6) | Jan 08, 2023 |
| Dell          | Inspiron N4030              | [efaaf759cb](https://linux-hardware.org/?probe=efaaf759cb) | Jan 08, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [8056078760](https://linux-hardware.org/?probe=8056078760) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b8e1b2ec8e](https://linux-hardware.org/?probe=b8e1b2ec8e) | Jan 07, 2023 |
| Acer          | Swift SF314-71              | [7fa69ddddb](https://linux-hardware.org/?probe=7fa69ddddb) | Jan 07, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8ac0b43549](https://linux-hardware.org/?probe=8ac0b43549) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| ASUSTek       | X453MA                      | [1584b0616c](https://linux-hardware.org/?probe=1584b0616c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d99426e3d5](https://linux-hardware.org/?probe=d99426e3d5) | Jan 01, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [7e7df16316](https://linux-hardware.org/?probe=7e7df16316) | Jan 01, 2023 |
| Lenovo        | IdeaPad 320-14AST 80XU      | [56e961b0ca](https://linux-hardware.org/?probe=56e961b0ca) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| Acer          | TravelMate P214             | [436186d9e5](https://linux-hardware.org/?probe=436186d9e5) | Dec 30, 2022 |
| Lenovo        | ThinkPad X240 20AMS1J60B    | [1d8fcd4a75](https://linux-hardware.org/?probe=1d8fcd4a75) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [b6413f9cf2](https://linux-hardware.org/?probe=b6413f9cf2) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [4ddf1fecb8](https://linux-hardware.org/?probe=4ddf1fecb8) | Dec 28, 2022 |
| Lenovo        | V310-14ISK 80SX             | [a1e4dd02b2](https://linux-hardware.org/?probe=a1e4dd02b2) | Dec 27, 2022 |
| Lenovo        | V310-14ISK 80SX             | [cedf39754e](https://linux-hardware.org/?probe=cedf39754e) | Dec 27, 2022 |
| Lenovo        | IdeaPad S110 20126          | [dd7fd03edd](https://linux-hardware.org/?probe=dd7fd03edd) | Dec 24, 2022 |
| Acer          | Swift SF314-71              | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| ASUSTek       | X45C                        | [80377ba23f](https://linux-hardware.org/?probe=80377ba23f) | Dec 17, 2022 |
| MSI           | Modern 14 B4MW              | [19e6ba206d](https://linux-hardware.org/?probe=19e6ba206d) | Dec 16, 2022 |
| Lenovo        | G40-30 80FY                 | [b9184a9ade](https://linux-hardware.org/?probe=b9184a9ade) | Dec 16, 2022 |
| Acer          | EX-215-52                   | [25201732ef](https://linux-hardware.org/?probe=25201732ef) | Dec 14, 2022 |
| Acer          | EX-215-52                   | [4cb72a8770](https://linux-hardware.org/?probe=4cb72a8770) | Dec 14, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [24fefa1408](https://linux-hardware.org/?probe=24fefa1408) | Dec 13, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| Lenovo        | G40-30 80FY                 | [1a330e248d](https://linux-hardware.org/?probe=1a330e248d) | Dec 11, 2022 |
| ASUSTek       | T100TA                      | [efd7016171](https://linux-hardware.org/?probe=efd7016171) | Dec 11, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5250630bdd](https://linux-hardware.org/?probe=5250630bdd) | Dec 09, 2022 |
| Acer          | Unknown                     | [b4eea49cf7](https://linux-hardware.org/?probe=b4eea49cf7) | Dec 09, 2022 |
| Lenovo        | ThinkPad L530 24783R8       | [406c066d36](https://linux-hardware.org/?probe=406c066d36) | Dec 08, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| Acer          | One Z1401                   | [835ad73eff](https://linux-hardware.org/?probe=835ad73eff) | Dec 05, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [897f477f2d](https://linux-hardware.org/?probe=897f477f2d) | Dec 04, 2022 |
| MSI           | Modern 14 B4MW              | [9f512598e2](https://linux-hardware.org/?probe=9f512598e2) | Dec 04, 2022 |
| Dell          | Latitude 3420               | [23e8b890d2](https://linux-hardware.org/?probe=23e8b890d2) | Dec 03, 2022 |
| Lenovo        | B40-70 20392                | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| ASUSTek       | E203NAH                     | [3d091ea214](https://linux-hardware.org/?probe=3d091ea214) | Nov 30, 2022 |
| Dell          | Latitude E6440              | [0c3dd709dd](https://linux-hardware.org/?probe=0c3dd709dd) | Nov 30, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4a49152177](https://linux-hardware.org/?probe=4a49152177) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Laptop 14s-dq5xxx           | [9bb72cb3e8](https://linux-hardware.org/?probe=9bb72cb3e8) | Nov 28, 2022 |
| HP            | Laptop 14s-dq5xxx           | [e5164649e1](https://linux-hardware.org/?probe=e5164649e1) | Nov 27, 2022 |
| Dell          | Inspiron 3521               | [74d291cf07](https://linux-hardware.org/?probe=74d291cf07) | Nov 24, 2022 |
| Dell          | Inspiron 3521               | [4f0d293e99](https://linux-hardware.org/?probe=4f0d293e99) | Nov 24, 2022 |
| Dell          | Latitude E6230              | [28b93e0f7c](https://linux-hardware.org/?probe=28b93e0f7c) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [5f72d40c0e](https://linux-hardware.org/?probe=5f72d40c0e) | Nov 22, 2022 |
| Acer          | Aspire 4736                 | [e6acabebb2](https://linux-hardware.org/?probe=e6acabebb2) | Nov 21, 2022 |
| ASUSTek       | X45C                        | [02a232c4ef](https://linux-hardware.org/?probe=02a232c4ef) | Nov 21, 2022 |
| ASUSTek       | X455YA                      | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Dell          | Latitude E6520              | [855dc4dadd](https://linux-hardware.org/?probe=855dc4dadd) | Nov 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4c05f821c1](https://linux-hardware.org/?probe=4c05f821c1) | Nov 16, 2022 |
| Acer          | Swift SF314-71              | [c1eca34f9c](https://linux-hardware.org/?probe=c1eca34f9c) | Nov 15, 2022 |
| Intel         | SandyBridge Platform        | [7019c7ba85](https://linux-hardware.org/?probe=7019c7ba85) | Nov 13, 2022 |
| Acer          | AO722                       | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [77f7b2ff84](https://linux-hardware.org/?probe=77f7b2ff84) | Nov 10, 2022 |
| Lenovo        | ThinkPad P52s 20LB0026US    | [9443a4ceda](https://linux-hardware.org/?probe=9443a4ceda) | Nov 08, 2022 |
| Toshiba       | Satellite L15-B             | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| GPD           | G1619-04                    | [0c0542ac2e](https://linux-hardware.org/?probe=0c0542ac2e) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [98e419a04d](https://linux-hardware.org/?probe=98e419a04d) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Intel         | SandyBridge Platform        | [88c15d34e4](https://linux-hardware.org/?probe=88c15d34e4) | Nov 03, 2022 |
| Acer          | Aspire A514-55              | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Dell          | Latitude E6540              | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| Acer          | Swift SF314-71              | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| Acer          | Nitro AN515-43              | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| ASUSTek       | K43E                        | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| Acer          | Aspire 4732Z                | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ASUSTek       | K43E                        | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Sony          | VPCEA36FG                   | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Dell          | G3 3579                     | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| HP            | Pavilion g4                 | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| Toshiba       | Satellite C640              | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Acer          | Aspire A314-35              | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| Fujitsu       | FMVS02003                   | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Acer          | AO756                       | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| Acer          | Aspire 4720Z                | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Acer          | Swift SF314-41              | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| Acer          | Aspire A514-54G             | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| Acer          | Aspire V5-431               | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Acer          | Aspire 4720Z                | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | Pavilion 14                 | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| MSI           | GF63 Thin 9SCXR             | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Sony          | VPCSB35FG                   | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| Dell          | Inspiron 13-5368            | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 109       | 8.33%   |
| Ubuntu 22.04                 | 74        | 5.66%   |
| Ubuntu 18.04                 | 61        | 4.66%   |
| Arch Rolling                 | 47        | 3.59%   |
| OpenMandriva 4.3             | 38        | 2.91%   |
| Pop!_OS 22.04                | 34        | 2.6%    |
| OpenMandriva 4.2             | 23        | 1.76%   |
| Ubuntu 24.04                 | 22        | 1.68%   |
| Fedora 40                    | 21        | 1.61%   |
| Debian 12                    | 21        | 1.61%   |
| KDE neon 20.04               | 19        | 1.45%   |
| ArcoLinux Rolling            | 19        | 1.45%   |
| Fedora 38                    | 18        | 1.38%   |
| Fedora 36                    | 18        | 1.38%   |
| Arch                         | 17        | 1.3%    |
| Zorin 17                     | 15        | 1.15%   |
| Manjaro                      | 15        | 1.15%   |
| Zorin 16                     | 14        | 1.07%   |
| Pop!_OS 20.04                | 14        | 1.07%   |
| OpenMandriva 23.08           | 14        | 1.07%   |
| EndeavourOS Rolling          | 14        | 1.07%   |
| Zorin 15                     | 13        | 0.99%   |
| Elementary 6.1               | 13        | 0.99%   |
| Debian 11                    | 13        | 0.99%   |
| Ubuntu 19.10                 | 12        | 0.92%   |
| OpenMandriva 5.0             | 12        | 0.92%   |
| Kubuntu 22.04                | 12        | 0.92%   |
| Fedora 37                    | 12        | 0.92%   |
| Fedora 35                    | 12        | 0.92%   |
| Ubuntu 21.10                 | 11        | 0.84%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 0.84%   |
| OpenMandriva 23.03           | 11        | 0.84%   |
| Linux Mint 22                | 11        | 0.84%   |
| Linux Mint 21.1              | 11        | 0.84%   |
| Linux Mint 20.3              | 11        | 0.84%   |
| KDE neon 22.04               | 11        | 0.84%   |
| Xubuntu 20.04                | 9         | 0.69%   |
| OpenMandriva 24.12           | 9         | 0.69%   |
| OpenMandriva 23.01           | 9         | 0.69%   |
| Kubuntu 20.04                | 9         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 312       | 25.26%  |
| OpenMandriva  | 124       | 10.04%  |
| Fedora        | 99        | 8.02%   |
| Linux Mint    | 75        | 6.07%   |
| Arch          | 64        | 5.18%   |
| Pop!_OS       | 60        | 4.86%   |
| Debian        | 47        | 3.81%   |
| Zorin         | 45        | 3.64%   |
| Manjaro       | 44        | 3.56%   |
| Elementary    | 39        | 3.16%   |
| KDE neon      | 32        | 2.59%   |
| Kubuntu       | 31        | 2.51%   |
| Kali          | 27        | 2.19%   |
| Xubuntu       | 21        | 1.7%    |
| Endless       | 21        | 1.7%    |
| ArcoLinux     | 20        | 1.62%   |
| Lubuntu       | 16        | 1.3%    |
| EndeavourOS   | 14        | 1.13%   |
| ROSA          | 12        | 0.97%   |
| openSUSE      | 12        | 0.97%   |
| Ubuntu MATE   | 11        | 0.89%   |
| Nobara        | 9         | 0.73%   |
| SteamOS       | 8         | 0.65%   |
| Ubuntu Unity  | 6         | 0.49%   |
| Parrot        | 6         | 0.49%   |
| MX            | 6         | 0.49%   |
| LMDE          | 6         | 0.49%   |
| Gentoo        | 6         | 0.49%   |
| Deepin        | 6         | 0.49%   |
| Ubuntu Budgie | 4         | 0.32%   |
| Garuda Linux  | 4         | 0.32%   |
| Artix         | 4         | 0.32%   |
| Xero          | 3         | 0.24%   |
| NixOS         | 3         | 0.24%   |
| Linux Lite    | 3         | 0.24%   |
| Clear Linux   | 3         | 0.24%   |
| AlmaLinux     | 3         | 0.24%   |
| Void Linux    | 2         | 0.16%   |
| Ultramarine   | 2         | 0.16%   |
| TUXEDO OS     | 2         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 38        | 2.72%   |
| 5.10.14-desktop-1omv4002 | 23        | 1.65%   |
| 5.4.0-42-generic         | 16        | 1.15%   |
| 6.6.2-desktop-1omv2390   | 15        | 1.07%   |
| 5.15.0-56-generic        | 13        | 0.93%   |
| 5.4.0-26-generic         | 12        | 0.86%   |
| 6.4.11-desktop-1omv2390  | 11        | 0.79%   |
| 5.15.0-41-generic        | 11        | 0.79%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.72%   |
| 6.8.0-49-generic         | 9         | 0.64%   |
| 6.12.1-desktop-1omv2490  | 9         | 0.64%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.64%   |
| 5.4.0-52-generic         | 9         | 0.64%   |
| 5.15.0-46-generic        | 9         | 0.64%   |
| 5.15.0-48-generic        | 8         | 0.57%   |
| 5.15.0-47-generic        | 8         | 0.57%   |
| 5.0.0-25-generic         | 8         | 0.57%   |
| 4.18.0-15-generic        | 8         | 0.57%   |
| 6.9.3-76060903-generic   | 7         | 0.5%    |
| 5.4.0-58-generic         | 7         | 0.5%    |
| 5.4.0-54-generic         | 7         | 0.5%    |
| 5.15.0-58-generic        | 7         | 0.5%    |
| 5.11.0-37-generic        | 7         | 0.5%    |
| 6.8.0-45-generic         | 6         | 0.43%   |
| 6.8.0-31-generic         | 6         | 0.43%   |
| 6.5.0-35-generic         | 6         | 0.43%   |
| 6.2.0-33-generic         | 6         | 0.43%   |
| 5.8.0-48-generic         | 6         | 0.43%   |
| 5.3.0-46-generic         | 6         | 0.43%   |
| 5.19.0-35-generic        | 6         | 0.43%   |
| 5.15.0-91-generic        | 6         | 0.43%   |
| 5.15.0-52-generic        | 6         | 0.43%   |
| 5.15.0-43-generic        | 6         | 0.43%   |
| 6.8.5-301.fc40.x86_64    | 5         | 0.36%   |
| 6.8.0-48-generic         | 5         | 0.36%   |
| 6.2.0-39-generic         | 5         | 0.36%   |
| 6.2.0-26-generic         | 5         | 0.36%   |
| 5.8.0-41-generic         | 5         | 0.36%   |
| 5.4.0-80-generic         | 5         | 0.36%   |
| 5.4.0-45-generic         | 5         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 137       | 10.16%  |
| 5.15.0  | 119       | 8.83%   |
| 5.11.0  | 55        | 4.08%   |
| 6.8.0   | 52        | 3.86%   |
| 6.5.0   | 44        | 3.26%   |
| 5.8.0   | 41        | 3.04%   |
| 5.16.7  | 39        | 2.89%   |
| 5.13.0  | 37        | 2.74%   |
| 6.2.0   | 35        | 2.6%    |
| 5.3.0   | 33        | 2.45%   |
| 6.1.0   | 32        | 2.37%   |
| 5.0.0   | 30        | 2.23%   |
| 4.15.0  | 30        | 2.23%   |
| 5.19.0  | 26        | 1.93%   |
| 5.10.0  | 25        | 1.85%   |
| 5.10.14 | 24        | 1.78%   |
| 4.18.0  | 17        | 1.26%   |
| 6.6.2   | 15        | 1.11%   |
| 6.4.11  | 14        | 1.04%   |
| 6.2.6   | 13        | 0.96%   |
| 4.19.0  | 13        | 0.96%   |
| 6.1.1   | 12        | 0.89%   |
| 6.5.5   | 10        | 0.74%   |
| 6.12.1  | 9         | 0.67%   |
| 6.9.3   | 8         | 0.59%   |
| 5.14.0  | 8         | 0.59%   |
| 6.9.7   | 6         | 0.45%   |
| 5.17.5  | 6         | 0.45%   |
| 5.16.0  | 6         | 0.45%   |
| 6.8.5   | 5         | 0.37%   |
| 6.4.6   | 5         | 0.37%   |
| 4.4.0   | 5         | 0.37%   |
| 6.9.9   | 4         | 0.3%    |
| 6.8.7   | 4         | 0.3%    |
| 6.6.8   | 4         | 0.3%    |
| 6.5.6   | 4         | 0.3%    |
| 6.5.3   | 4         | 0.3%    |
| 6.4.8   | 4         | 0.3%    |
| 6.11.3  | 4         | 0.3%    |
| 6.10.6  | 4         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 145       | 10.94%  |
| 5.15    | 140       | 10.57%  |
| 5.10    | 73        | 5.51%   |
| 6.8     | 69        | 5.21%   |
| 6.5     | 68        | 5.13%   |
| 6.1     | 68        | 5.13%   |
| 6.2     | 60        | 4.53%   |
| 5.16    | 59        | 4.45%   |
| 5.11    | 59        | 4.45%   |
| 5.8     | 52        | 3.92%   |
| 6.6     | 46        | 3.47%   |
| 5.13    | 41        | 3.09%   |
| 5.19    | 39        | 2.94%   |
| 6.4     | 35        | 2.64%   |
| 5.3     | 35        | 2.64%   |
| 5.0     | 32        | 2.42%   |
| 4.15    | 30        | 2.26%   |
| 6.9     | 24        | 1.81%   |
| 6.10    | 24        | 1.81%   |
| 5.14    | 22        | 1.66%   |
| 6.0     | 20        | 1.51%   |
| 4.18    | 20        | 1.51%   |
| 5.17    | 18        | 1.36%   |
| 4.19    | 17        | 1.28%   |
| 6.11    | 16        | 1.21%   |
| 6.3     | 15        | 1.13%   |
| 5.18    | 15        | 1.13%   |
| 6.12    | 13        | 0.98%   |
| 5.9     | 12        | 0.91%   |
| 6.7     | 9         | 0.68%   |
| 4.9     | 9         | 0.68%   |
| 5.6     | 7         | 0.53%   |
| 5.12    | 6         | 0.45%   |
| 4.4     | 6         | 0.45%   |
| 5.7     | 5         | 0.38%   |
| 5.5     | 5         | 0.38%   |
| 5.2     | 2         | 0.15%   |
| 4.13    | 2         | 0.15%   |
| 4.10    | 2         | 0.15%   |
| 4.1     | 2         | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1165      | 98.15%  |
| i686   | 22        | 1.85%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 517       | 41.56%  |
| KDE5            | 241       | 19.37%  |
| Unknown         | 110       | 8.84%   |
| XFCE            | 97        | 7.8%    |
| X-Cinnamon      | 72        | 5.79%   |
| Pantheon        | 38        | 3.05%   |
| LXQt            | 27        | 2.17%   |
| MATE            | 25        | 2.01%   |
| KDE6            | 21        | 1.69%   |
| KDE             | 18        | 1.45%   |
| Cinnamon        | 12        | 0.96%   |
| Budgie          | 9         | 0.72%   |
| Hyprland        | 7         | 0.56%   |
| Unity           | 6         | 0.48%   |
| i3              | 6         | 0.48%   |
| Deepin          | 5         | 0.4%    |
| GNOME Flashback | 4         | 0.32%   |
| DWM             | 4         | 0.32%   |
| bspwm           | 4         | 0.32%   |
| sway            | 3         | 0.24%   |
| KDE4            | 3         | 0.24%   |
| qtile           | 2         | 0.16%   |
| LXDE            | 2         | 0.16%   |
| ICEWM           | 2         | 0.16%   |
| DDE             | 2         | 0.16%   |
| Cutefish        | 2         | 0.16%   |
| xmonad          | 1         | 0.08%   |
| openbox         | 1         | 0.08%   |
| Lubuntu         | 1         | 0.08%   |
| awesomeminimal  | 1         | 0.08%   |
| awesome         | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 825       | 67.02%  |
| Wayland | 326       | 26.48%  |
| Unknown | 65        | 5.28%   |
| Tty     | 15        | 1.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 490       | 39.87%  |
| SDDM    | 239       | 19.45%  |
| GDM3    | 162       | 13.18%  |
| GDM     | 152       | 12.37%  |
| LightDM | 148       | 12.04%  |
| TDM     | 29        | 2.36%   |
| KDM     | 3         | 0.24%   |
| SLiM    | 2         | 0.16%   |
| Ly      | 2         | 0.16%   |
| LY-DM   | 1         | 0.08%   |
| LXDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 992       | 82.19%  |
| Unknown | 81        | 6.71%   |
| id_ID   | 77        | 6.38%   |
| C       | 23        | 1.91%   |
| en_GB   | 12        | 0.99%   |
| en_AU   | 5         | 0.41%   |
| en_SG   | 4         | 0.33%   |
| en_AG   | 3         | 0.25%   |
| ru_RU   | 2         | 0.17%   |
| fr_FR   | 2         | 0.17%   |
| de_DE   | 2         | 0.17%   |
| jv_ID   | 1         | 0.08%   |
| en_IN   | 1         | 0.08%   |
| de_CH   | 1         | 0.08%   |
| C.UTF8  | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 707       | 58.38%  |
| BIOS | 504       | 41.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 874       | 71.99%  |
| Btrfs   | 156       | 12.85%  |
| Overlay | 89        | 7.33%   |
| Tmpfs   | 37        | 3.05%   |
| Unknown | 25        | 2.06%   |
| Xfs     | 15        | 1.24%   |
| Zfs     | 6         | 0.49%   |
| F2fs    | 5         | 0.41%   |
| Ext2    | 5         | 0.41%   |
| Ext3    | 2         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 579       | 47.69%  |
| Unknown | 493       | 40.61%  |
| MBR     | 142       | 11.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1051      | 86.93%  |
| Yes       | 158       | 13.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 700       | 57.8%   |
| Yes       | 511       | 42.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 295       | 24.85%  |
| ASUSTek Computer    | 261       | 21.99%  |
| Hewlett-Packard     | 182       | 15.33%  |
| Acer                | 159       | 13.4%   |
| Dell                | 96        | 8.09%   |
| Toshiba             | 39        | 3.29%   |
| MSI                 | 23        | 1.94%   |
| AXIOO               | 18        | 1.52%   |
| Apple               | 16        | 1.35%   |
| Sony                | 11        | 0.93%   |
| Fujitsu             | 11        | 0.93%   |
| Samsung Electronics | 8         | 0.67%   |
| ADVAN               | 7         | 0.59%   |
| Valve               | 6         | 0.51%   |
| Infinix             | 5         | 0.42%   |
| HUAWEI              | 5         | 0.42%   |
| Clevo               | 5         | 0.42%   |
| Unknown             | 5         | 0.42%   |
| Panasonic           | 4         | 0.34%   |
| realme              | 3         | 0.25%   |
| Intel               | 3         | 0.25%   |
| Google              | 3         | 0.25%   |
| Timi                | 2         | 0.17%   |
| Gigabyte Technology | 2         | 0.17%   |
| Chuwi               | 2         | 0.17%   |
| AVITA               | 2         | 0.17%   |
| Acidanthera         | 2         | 0.17%   |
| UMAX                | 1         | 0.08%   |
| Sole                | 1         | 0.08%   |
| Phoenix/SiS         | 1         | 0.08%   |
| Notebook            | 1         | 0.08%   |
| MicroByte           | 1         | 0.08%   |
| Medion              | 1         | 0.08%   |
| itel Mobile Limited | 1         | 0.08%   |
| Hampoo              | 1         | 0.08%   |
| GPD                 | 1         | 0.08%   |
| Compal              | 1         | 0.08%   |
| AZW                 | 1         | 0.08%   |
| AIO                 | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Notebook                             | 14        | 1.18%   |
| Lenovo IdeaPad 330-14AST 81D5           | 12        | 1.01%   |
| Lenovo G40-45 80E1                      | 12        | 1.01%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 9         | 0.76%   |
| Lenovo G400 20235                       | 8         | 0.67%   |
| Acer Swift SF314-71                     | 8         | 0.67%   |
| Acer Aspire 4752                        | 8         | 0.67%   |
| Unknown                                 | 8         | 0.67%   |
| Lenovo IdeaPad S340-14API 81NB          | 7         | 0.59%   |
| HP Pavilion g4                          | 7         | 0.59%   |
| HP Laptop 14-bw0xx                      | 7         | 0.59%   |
| HP 14                                   | 7         | 0.59%   |
| Valve Jupiter                           | 6         | 0.51%   |
| HP Laptop 14-bs0xx                      | 6         | 0.51%   |
| ASUS X455LF                             | 6         | 0.51%   |
| ASUS GL553VD                            | 6         | 0.51%   |
| Acer Aspire 4750                        | 6         | 0.51%   |
| Lenovo IdeaPad 320-14AST 80XU           | 5         | 0.42%   |
| ASUS X455YA                             | 5         | 0.42%   |
| ASUS X441BA                             | 5         | 0.42%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.42%   |
| Apple MacBookPro12,1                    | 5         | 0.42%   |
| Acer Swift SFX14-41G                    | 5         | 0.42%   |
| Acer Swift SF314-56G                    | 5         | 0.42%   |
| Acer One Z1402                          | 5         | 0.42%   |
| Acer Aspire E5-475G                     | 5         | 0.42%   |
| Lenovo V310-14ISK 80SX                  | 4         | 0.34%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 4         | 0.34%   |
| Lenovo G400s 20244                      | 4         | 0.34%   |
| Lenovo G40-30 80FY                      | 4         | 0.34%   |
| HP Pavilion 14                          | 4         | 0.34%   |
| HP Laptop 14-cm0xxx                     | 4         | 0.34%   |
| HP EliteBook 2570p                      | 4         | 0.34%   |
| HP 1000                                 | 4         | 0.34%   |
| ASUS X456URK                            | 4         | 0.34%   |
| ASUS X455LD                             | 4         | 0.34%   |
| ASUS X453SA                             | 4         | 0.34%   |
| ASUS X450CC                             | 4         | 0.34%   |
| ASUS X442URR                            | 4         | 0.34%   |
| ASUS X441NA                             | 4         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 114       | 9.6%    |
| Lenovo IdeaPad     | 99        | 8.34%   |
| Acer Aspire        | 94        | 7.92%   |
| ASUS VivoBook      | 62        | 5.22%   |
| HP Laptop          | 47        | 3.96%   |
| Dell Latitude      | 47        | 3.96%   |
| HP Pavilion        | 40        | 3.37%   |
| Acer Swift         | 27        | 2.27%   |
| HP EliteBook       | 25        | 2.11%   |
| Toshiba Satellite  | 24        | 2.02%   |
| Dell Inspiron      | 23        | 1.94%   |
| ASUS ASUS          | 16        | 1.35%   |
| HP Notebook        | 14        | 1.18%   |
| Dell Vostro        | 13        | 1.1%    |
| Lenovo G40-45      | 12        | 1.01%   |
| Acer Nitro         | 12        | 1.01%   |
| HP ProBook         | 11        | 0.93%   |
| ASUS TUF           | 10        | 0.84%   |
| Lenovo ThinkBook   | 9         | 0.76%   |
| Lenovo Yoga        | 8         | 0.67%   |
| Lenovo G400        | 8         | 0.67%   |
| Unknown            | 8         | 0.67%   |
| Toshiba PORTEGE    | 7         | 0.59%   |
| MSI Modern         | 7         | 0.59%   |
| HP 14              | 7         | 0.59%   |
| Valve Jupiter      | 6         | 0.51%   |
| Lenovo Legion      | 6         | 0.51%   |
| AXIOO Mybook       | 6         | 0.51%   |
| ASUS X455LF        | 6         | 0.51%   |
| ASUS ROG           | 6         | 0.51%   |
| ASUS GL553VD       | 6         | 0.51%   |
| Acer One           | 6         | 0.51%   |
| Toshiba dynabook   | 5         | 0.42%   |
| Infinix INBook     | 5         | 0.42%   |
| HP 240             | 5         | 0.42%   |
| ASUS X455YA        | 5         | 0.42%   |
| ASUS X441BA        | 5         | 0.42%   |
| Apple MacBookPro12 | 5         | 0.42%   |
| Lenovo V310-14ISK  | 4         | 0.34%   |
| Lenovo G400s       | 4         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 116       | 9.77%   |
| 2019 | 110       | 9.27%   |
| 2021 | 108       | 9.1%    |
| 2013 | 96        | 8.09%   |
| 2012 | 88        | 7.41%   |
| 2011 | 86        | 7.25%   |
| 2017 | 84        | 7.08%   |
| 2020 | 83        | 6.99%   |
| 2014 | 81        | 6.82%   |
| 2015 | 75        | 6.32%   |
| 2016 | 56        | 4.72%   |
| 2010 | 53        | 4.47%   |
| 2022 | 43        | 3.62%   |
| 2023 | 34        | 2.86%   |
| 2008 | 27        | 2.27%   |
| 2009 | 25        | 2.11%   |
| 2007 | 11        | 0.93%   |
| 2024 | 7         | 0.59%   |
| 2006 | 4         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1187      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1093      | 91.08%  |
| Enabled  | 107       | 8.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1183      | 99.66%  |
| Yes  | 4         | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 393       | 32.75%  |
| 3.01-4.0    | 296       | 24.67%  |
| 8.01-16.0   | 211       | 17.58%  |
| 16.01-24.0  | 142       | 11.83%  |
| 1.01-2.0    | 94        | 7.83%   |
| 32.01-64.0  | 30        | 2.5%    |
| 24.01-32.0  | 15        | 1.25%   |
| 2.01-3.0    | 11        | 0.92%   |
| 0.51-1.0    | 5         | 0.42%   |
| 64.01-256.0 | 3         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 428       | 32.75%  |
| 2.01-3.0   | 360       | 27.54%  |
| 4.01-8.0   | 205       | 15.68%  |
| 3.01-4.0   | 200       | 15.3%   |
| 0.51-1.0   | 67        | 5.13%   |
| 8.01-16.0  | 38        | 2.91%   |
| 0.01-0.5   | 5         | 0.38%   |
| 16.01-24.0 | 3         | 0.23%   |
| 24.01-32.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 856       | 70.69%  |
| 2      | 315       | 26.01%  |
| 3      | 32        | 2.64%   |
| 0      | 5         | 0.41%   |
| 4      | 3         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 826       | 69.06%  |
| Yes       | 370       | 30.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 932       | 78.45%  |
| No        | 256       | 21.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1164      | 97.9%   |
| No        | 25        | 2.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 952       | 79.4%   |
| No        | 247       | 20.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Indonesia | 1187      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Jakarta         | 324       | 24.88%  |
| Surabaya        | 122       | 9.37%   |
| Bandung         | 95        | 7.3%    |
| Bogor           | 47        | 3.61%   |
| Yogyakarta      | 46        | 3.53%   |
| Bekasi          | 43        | 3.3%    |
| Semarang        | 41        | 3.15%   |
| Denpasar        | 34        | 2.61%   |
| Tangerang       | 28        | 2.15%   |
| Malang          | 27        | 2.07%   |
| Medan           | 24        | 1.84%   |
| South Tangerang | 22        | 1.69%   |
| Makassar        | 20        | 1.54%   |
| Depok           | 19        | 1.46%   |
| Palembang       | 15        | 1.15%   |
| Samarinda       | 12        | 0.92%   |
| Banjarmasin     | 12        | 0.92%   |
| Tasikmalaya     | 11        | 0.84%   |
| Sleman          | 11        | 0.84%   |
| Balikpapan      | 11        | 0.84%   |
| Pontianak       | 8         | 0.61%   |
| Magelang        | 8         | 0.61%   |
| Kediri          | 8         | 0.61%   |
| Banda Aceh      | 8         | 0.61%   |
| Surakarta       | 7         | 0.54%   |
| Gresik          | 7         | 0.54%   |
| Brebes          | 7         | 0.54%   |
| Blitar          | 7         | 0.54%   |
| Kudus           | 6         | 0.46%   |
| Jember          | 6         | 0.46%   |
| Jakarta Pusat   | 6         | 0.46%   |
| Cirebon         | 6         | 0.46%   |
| Sukabumi        | 5         | 0.38%   |
| Pekanbaru       | 5         | 0.38%   |
| Pasuruan        | 5         | 0.38%   |
| Mataram         | 5         | 0.38%   |
| Jambi City      | 5         | 0.38%   |
| Demak           | 5         | 0.38%   |
| Batam           | 5         | 0.38%   |
| Purwokerto      | 4         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 217       | 277    | 14.22%  |
| WDC                   | 166       | 195    | 10.88%  |
| Toshiba               | 147       | 160    | 9.63%   |
| Samsung Electronics   | 143       | 193    | 9.37%   |
| HGST                  | 70        | 78     | 4.59%   |
| SanDisk               | 64        | 78     | 4.19%   |
| Unknown               | 55        | 67     | 3.6%    |
| Hitachi               | 54        | 61     | 3.54%   |
| Intel                 | 51        | 70     | 3.34%   |
| Micron Technology     | 50        | 65     | 3.28%   |
| SK hynix              | 46        | 53     | 3.01%   |
| V-GeN                 | 45        | 48     | 2.95%   |
| Kingston              | 37        | 45     | 2.42%   |
| A-DATA Technology     | 31        | 37     | 2.03%   |
| MidasForce            | 30        | 34     | 1.97%   |
| Unknown               | 22        | 26     | 1.44%   |
| China                 | 17        | 21     | 1.11%   |
| Silicon Motion        | 16        | 19     | 1.05%   |
| VISIPRO               | 15        | 19     | 0.98%   |
| Team                  | 15        | 18     | 0.98%   |
| RX7                   | 13        | 15     | 0.85%   |
| JMicron Technology    | 12        | 13     | 0.79%   |
| KIOXIA                | 11        | 14     | 0.72%   |
| Fujitsu               | 11        | 12     | 0.72%   |
| EYOTA                 | 11        | 15     | 0.72%   |
| Crucial               | 11        | 13     | 0.72%   |
| Apacer                | 11        | 11     | 0.72%   |
| Apple                 | 9         | 11     | 0.59%   |
| Phison Electronics    | 7         | 9      | 0.46%   |
| Patriot               | 7         | 11     | 0.46%   |
| Realtek Semiconductor | 6         | 6      | 0.39%   |
| PNY                   | 5         | 5      | 0.33%   |
| Wellcomm              | 4         | 4      | 0.26%   |
| SCY                   | 4         | 6      | 0.26%   |
| LITEONIT              | 4         | 5      | 0.26%   |
| LITEON                | 4         | 5      | 0.26%   |
| FORESEE               | 4         | 4      | 0.26%   |
| External              | 4         | 4      | 0.26%   |
| ADATA Technology      | 4         | 6      | 0.26%   |
| USB3.0                | 3         | 3      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                       | 49        | 3.13%   |
| Seagate ST1000LM035-1RK172 1TB                        | 45        | 2.88%   |
| Toshiba MQ01ABF050 500GB                              | 32        | 2.04%   |
| Toshiba MQ04ABF100 1TB                                | 31        | 1.98%   |
| Unknown                                               | 22        | 1.41%   |
| Toshiba MQ01ABD100 1TB                                | 20        | 1.28%   |
| HGST HTS545050A7E680 500GB                            | 20        | 1.28%   |
| Seagate ST500LT012-9WS142 500GB                       | 13        | 0.83%   |
| A-DATA SU650 120GB SSD                                | 13        | 0.83%   |
| MidasForce SSD 128GB                                  | 11        | 0.7%    |
| Intel SSDPEKNW512G8 512GB                             | 11        | 0.7%    |
| Hitachi HTS543232A7A384 320GB                         | 11        | 0.7%    |
| HGST HTS721010A9E630 1TB                              | 11        | 0.7%    |
| Unknown MMC Card  32GB                                | 10        | 0.64%   |
| Seagate ST9500325AS 500GB                             | 10        | 0.64%   |
| SanDisk NVMe SSD Drive 512GB                          | 10        | 0.64%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 10        | 0.64%   |
| Hitachi HTS545050A7E380 500GB                         | 10        | 0.64%   |
| HGST HTS725050A7E630 500GB                            | 10        | 0.64%   |
| WDC WD5000LPVX-22V0TT0 500GB                          | 9         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 8         | 0.51%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 8         | 0.51%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 8         | 0.51%   |
| Seagate ST9320325AS 320GB                             | 8         | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 8         | 0.51%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 8         | 0.51%   |
| Samsung SSD 850 EVO 250GB                             | 8         | 0.51%   |
| JMicron Generic 500GB                                 | 8         | 0.51%   |
| Seagate ST500LM021-1KJ152 500GB                       | 7         | 0.45%   |
| Seagate ST2000LM007-1R8174 2TB                        | 7         | 0.45%   |
| Seagate ST1000LX015-1U7172 1TB                        | 7         | 0.45%   |
| MidasForce SSD 256GB                                  | 7         | 0.45%   |
| HGST HTS541010A9E680 1TB                              | 7         | 0.45%   |
| A-DATA SU650 240GB SSD                                | 7         | 0.45%   |
| WDC WD5000LPVX-80V0TT0 500GB                          | 6         | 0.38%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 6         | 0.38%   |
| Unknown MMC Card  64GB                                | 6         | 0.38%   |
| Unknown MMC Card  128GB                               | 6         | 0.38%   |
| Seagate ST1000LM049-2GH172 1TB                        | 6         | 0.38%   |
| Samsung SSD 860 EVO 500GB                             | 6         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 214       | 271    | 34.46%  |
| Toshiba             | 126       | 137    | 20.29%  |
| WDC                 | 122       | 138    | 19.65%  |
| HGST                | 70        | 78     | 11.27%  |
| Hitachi             | 54        | 61     | 8.7%    |
| JMicron Technology  | 9         | 9      | 1.45%   |
| Fujitsu             | 9         | 9      | 1.45%   |
| Unknown             | 4         | 4      | 0.64%   |
| Samsung Electronics | 4         | 4      | 0.64%   |
| External            | 4         | 4      | 0.64%   |
| TO Exter            | 1         | 1      | 0.16%   |
| SYMTEC              | 1         | 1      | 0.16%   |
| HGST HTS            | 1         | 3      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |
| Apple               | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 80     | 13.92%  |
| V-GeN               | 31        | 33     | 7.31%   |
| MidasForce          | 30        | 34     | 7.08%   |
| SanDisk             | 26        | 36     | 6.13%   |
| WDC                 | 25        | 35     | 5.9%    |
| A-DATA Technology   | 23        | 28     | 5.42%   |
| Kingston            | 21        | 22     | 4.95%   |
| China               | 17        | 21     | 4.01%   |
| Unknown             | 16        | 17     | 3.77%   |
| VISIPRO             | 11        | 15     | 2.59%   |
| Apacer              | 11        | 11     | 2.59%   |
| Team                | 10        | 13     | 2.36%   |
| EYOTA               | 10        | 13     | 2.36%   |
| Toshiba             | 9         | 10     | 2.12%   |
| RX7                 | 9         | 10     | 2.12%   |
| Crucial             | 9         | 11     | 2.12%   |
| Micron Technology   | 8         | 12     | 1.89%   |
| Intel               | 8         | 12     | 1.89%   |
| Patriot             | 7         | 11     | 1.65%   |
| Apple               | 7         | 8      | 1.65%   |
| Wellcomm            | 4         | 4      | 0.94%   |
| Seagate             | 4         | 4      | 0.94%   |
| LITEONIT            | 4         | 5      | 0.94%   |
| LITEON              | 4         | 5      | 0.94%   |
| USB3.0              | 3         | 3      | 0.71%   |
| SK hynix            | 3         | 3      | 0.71%   |
| Ramos Technology    | 3         | 16     | 0.71%   |
| PNY                 | 3         | 3      | 0.71%   |
| Pioneer             | 3         | 3      | 0.71%   |
| Lexar               | 3         | 3      | 0.71%   |
| FORESEE             | 3         | 3      | 0.71%   |
| XSTAR               | 2         | 2      | 0.47%   |
| Transcend           | 2         | 2      | 0.47%   |
| Smart               | 2         | 2      | 0.47%   |
| Netac               | 2         | 2      | 0.47%   |
| Kingmax             | 2         | 2      | 0.47%   |
| GALAX               | 2         | 2      | 0.47%   |
| DST                 | 2         | 2      | 0.47%   |
| WellcommMaster      | 1         | 1      | 0.24%   |
| Vaseky              | 1         | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 591       | 722    | 40.73%  |
| SSD     | 399       | 525    | 27.5%   |
| NVMe    | 371       | 489    | 25.57%  |
| Unknown | 46        | 54     | 3.17%   |
| MMC     | 44        | 57     | 3.03%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 872       | 1254   | 65.42%  |
| NVMe | 371       | 487    | 27.83%  |
| SAS  | 46        | 49     | 3.45%   |
| MMC  | 44        | 57     | 3.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 653       | 881    | 69.54%  |
| 0.51-1.0   | 265       | 332    | 28.22%  |
| 1.01-2.0   | 18        | 31     | 1.92%   |
| 3.01-4.0   | 2         | 2      | 0.21%   |
| 4.01-10.0  | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 363       | 28.97%  |
| 251-500        | 329       | 26.26%  |
| 501-1000       | 149       | 11.89%  |
| 51-100         | 129       | 10.3%   |
| 1-20           | 89        | 7.1%    |
| 21-50          | 78        | 6.23%   |
| 1001-2000      | 75        | 5.99%   |
| Unknown        | 20        | 1.6%    |
| More than 3000 | 11        | 0.88%   |
| 2001-3000      | 10        | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 471       | 35.93%  |
| 21-50          | 259       | 19.76%  |
| 101-250        | 190       | 14.49%  |
| 51-100         | 168       | 12.81%  |
| 251-500        | 116       | 8.85%   |
| 501-1000       | 65        | 4.96%   |
| Unknown        | 20        | 1.53%   |
| 1001-2000      | 15        | 1.14%   |
| 2001-3000      | 5         | 0.38%   |
| More than 3000 | 2         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB      | 8         | 9      | 5.16%   |
| HGST HTS545050A7E680 500GB           | 8         | 9      | 5.16%   |
| Seagate ST500LT012-9WS142 500GB      | 7         | 7      | 4.52%   |
| Toshiba MQ01ABF050 500GB             | 4         | 4      | 2.58%   |
| Seagate ST9500325AS 500GB            | 4         | 4      | 2.58%   |
| Toshiba MQ01ABD050 500GB             | 3         | 3      | 1.94%   |
| Toshiba MQ01ABD032 320GB             | 3         | 3      | 1.94%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 3      | 1.94%   |
| Hitachi HTS545050A7E380 500GB        | 3         | 3      | 1.94%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 3      | 1.94%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 1.94%   |
| Unknown                              | 3         | 3      | 1.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 1.29%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 2      | 1.29%   |
| WDC WD3200BEKT-60V5T1 320GB          | 2         | 2      | 1.29%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 2      | 1.29%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 4      | 1.29%   |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 1.29%   |
| Toshiba MK5059GSXP 500GB             | 2         | 2      | 1.29%   |
| Toshiba MK3265GSX 320GB              | 2         | 3      | 1.29%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 1.29%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 1.29%   |
| Seagate ST320LT012-9WS14C 320GB      | 2         | 2      | 1.29%   |
| Seagate ST1000LX015-1U7172 1TB       | 2         | 3      | 1.29%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 2      | 1.29%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 2      | 1.29%   |
| HGST HTS545050A7E380 500GB           | 2         | 2      | 1.29%   |
| WellcommMaster 128GB SSD             | 1         | 1      | 0.65%   |
| Wellcomm Master 128GB SSD            | 1         | 1      | 0.65%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 1      | 0.65%   |
| WDC WD5000LPVT-22G33T0 500GB         | 1         | 1      | 0.65%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 1      | 0.65%   |
| WDC WD5000L 500GB                    | 1         | 1      | 0.65%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 1      | 0.65%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 1      | 0.65%   |
| WDC WD5000BPVT-08HXZT3 500GB         | 1         | 2      | 0.65%   |
| WDC WD5000BPVT-00HXZT3 500GB         | 1         | 1      | 0.65%   |
| WDC WD3200BPVT-80JJ5T0 320GB         | 1         | 1      | 0.65%   |
| WDC WD3200BPVT-24ZEST0 320GB         | 1         | 1      | 0.65%   |
| WDC WD3200BEKX-75B7WT0 320GB         | 1         | 1      | 0.65%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 49     | 24.84%  |
| Toshiba             | 27        | 29     | 17.65%  |
| WDC                 | 24        | 27     | 15.69%  |
| HGST                | 17        | 19     | 11.11%  |
| Hitachi             | 16        | 16     | 10.46%  |
| Micron Technology   | 4         | 4      | 2.61%   |
| Samsung Electronics | 3         | 4      | 1.96%   |
| Unknown             | 3         | 3      | 1.96%   |
| SK hynix            | 2         | 2      | 1.31%   |
| SanDisk             | 2         | 2      | 1.31%   |
| KLEVV               | 2         | 2      | 1.31%   |
| Crucial             | 2         | 2      | 1.31%   |
| China               | 2         | 5      | 1.31%   |
| A-DATA Technology   | 2         | 4      | 1.31%   |
| WellcommMaster      | 1         | 1      | 0.65%   |
| Wellcomm            | 1         | 1      | 0.65%   |
| VISIPRO             | 1         | 3      | 0.65%   |
| ValueTech           | 1         | 1      | 0.65%   |
| V-GeN               | 1         | 1      | 0.65%   |
| Silicon Motion      | 1         | 1      | 0.65%   |
| RX7                 | 1         | 1      | 0.65%   |
| Intel               | 1         | 1      | 0.65%   |
| Apacer              | 1         | 1      | 0.65%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 49     | 31.4%   |
| Toshiba             | 27        | 29     | 22.31%  |
| WDC                 | 22        | 25     | 18.18%  |
| HGST                | 17        | 19     | 14.05%  |
| Hitachi             | 16        | 16     | 13.22%  |
| Samsung Electronics | 1         | 1      | 0.83%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 119       | 139    | 78.81%  |
| SSD  | 26        | 33     | 17.22%  |
| NVMe | 6         | 7      | 3.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT1 500GB      | 1         | 1      | 20%     |
| Toshiba MK2575GSX 250GB           | 1         | 1      | 20%     |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 20%     |
| Hitachi HTS543232A7A384 320GB     | 1         | 1      | 20%     |
| A-DATA Technology SX8200PNP 256GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Hitachi           | 2         | 2      | 40%     |
| WDC               | 1         | 1      | 20%     |
| Toshiba           | 1         | 1      | 20%     |
| A-DATA Technology | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 595       | 893    | 46.09%  |
| Works    | 545       | 770    | 42.22%  |
| Malfunc  | 146       | 179    | 11.31%  |
| Failed   | 5         | 5      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 817       | 58.27%  |
| AMD                              | 217       | 15.48%  |
| Samsung Electronics              | 88        | 6.28%   |
| SanDisk                          | 58        | 4.14%   |
| SK hynix                         | 42        | 3%      |
| Micron Technology                | 42        | 3%      |
| Silicon Motion                   | 22        | 1.57%   |
| Kingston Technology Company      | 19        | 1.36%   |
| Phison Electronics               | 16        | 1.14%   |
| KIOXIA                           | 13        | 0.93%   |
| ADATA Technology                 | 11        | 0.78%   |
| Toshiba America Info Systems     | 10        | 0.71%   |
| Realtek Semiconductor            | 9         | 0.64%   |
| Silicon Integrated Systems [SiS] | 5         | 0.36%   |
| Union Memory (Shenzhen)          | 4         | 0.29%   |
| Shenzhen Shichuangyi Electronics | 4         | 0.29%   |
| Shenzhen Longsys Electronics     | 3         | 0.21%   |
| Micron/Crucial Technology        | 3         | 0.21%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.21%   |
| INNOGRIT                         | 3         | 0.21%   |
| O2 Micro                         | 2         | 0.14%   |
| Nvidia                           | 2         | 0.14%   |
| ASMedia Technology               | 2         | 0.14%   |
| Solidigm                         | 1         | 0.07%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Seagate Technology               | 1         | 0.07%   |
| Lenovo                           | 1         | 0.07%   |
| Hosin Global Electronics         | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| Unknown                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 202       | 13.54%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 109       | 7.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 108       | 7.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 62        | 4.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 61        | 4.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 55        | 3.69%   |
| Intel Volume Management Device NVMe RAID Controller                              | 42        | 2.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 41        | 2.75%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 38        | 2.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 35        | 2.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 26        | 1.74%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 26        | 1.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 23        | 1.54%   |
| Intel Tiger Lake-LP SATA Controller                                              | 22        | 1.47%   |
| Intel SSD 660P Series                                                            | 22        | 1.47%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 21        | 1.41%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 21        | 1.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 20        | 1.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 17        | 1.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 1.14%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 16        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 1.07%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 15        | 1.01%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 14        | 0.94%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 14        | 0.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 13        | 0.87%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 12        | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 12        | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 12        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 12        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 11        | 0.74%   |
| SK hynix BC511 NVMe SSD                                                          | 10        | 0.67%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 10        | 0.67%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 9         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 9         | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 9         | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 9         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 8         | 0.54%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 8         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 916       | 63.48%  |
| NVMe | 371       | 25.71%  |
| RAID | 107       | 7.42%   |
| IDE  | 49        | 3.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 895       | 75.4%   |
| AMD    | 292       | 24.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 2.1%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 19        | 1.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 19        | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 1.51%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 17        | 1.43%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 17        | 1.43%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 17        | 1.43%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 1.26%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 15        | 1.26%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 15        | 1.26%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 14        | 1.18%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 14        | 1.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 1.18%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 14        | 1.18%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 1.09%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 13        | 1.09%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 1.09%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 13        | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 1.01%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 12        | 1.01%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 12        | 1.01%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 12        | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 11        | 0.93%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 0.93%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 11        | 0.93%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 11        | 0.93%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 11        | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 9         | 0.76%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 9         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 0.76%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 9         | 0.76%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 9         | 0.76%   |
| Intel 12th Gen Core i5-12500H                 | 9         | 0.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.76%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 9         | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.76%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 286       | 24.05%  |
| Intel Core i3           | 166       | 13.96%  |
| Intel Core i7           | 150       | 12.62%  |
| Other                   | 127       | 10.68%  |
| Intel Celeron           | 108       | 9.08%   |
| AMD Ryzen 5             | 70        | 5.89%   |
| Intel Core 2 Duo        | 35        | 2.94%   |
| AMD Ryzen 3             | 34        | 2.86%   |
| AMD Ryzen 7             | 28        | 2.35%   |
| AMD A8                  | 25        | 2.1%    |
| Intel Pentium           | 20        | 1.68%   |
| Intel Atom              | 15        | 1.26%   |
| AMD A4                  | 15        | 1.26%   |
| AMD E1                  | 11        | 0.93%   |
| AMD E                   | 11        | 0.93%   |
| AMD A6                  | 10        | 0.84%   |
| AMD Athlon              | 9         | 0.76%   |
| AMD A10                 | 8         | 0.67%   |
| Intel Pentium Dual-Core | 7         | 0.59%   |
| AMD Ryzen 5 PRO         | 7         | 0.59%   |
| AMD E2                  | 7         | 0.59%   |
| AMD Ryzen 9             | 6         | 0.5%    |
| Intel Pentium Dual      | 5         | 0.42%   |
| Intel Genuine           | 5         | 0.42%   |
| Intel Core 2            | 4         | 0.34%   |
| AMD FX                  | 4         | 0.34%   |
| Intel Xeon              | 3         | 0.25%   |
| AMD C-60                | 3         | 0.25%   |
| Intel Core              | 2         | 0.17%   |
| AMD A12                 | 2         | 0.17%   |
| Intel Pentium Silver    | 1         | 0.08%   |
| Intel Core M            | 1         | 0.08%   |
| AMD Turion 64 Mobile    | 1         | 0.08%   |
| AMD PRO A10             | 1         | 0.08%   |
| AMD C-50                | 1         | 0.08%   |
| AMD Athlon Neo X2       | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 737       | 61.98%  |
| 4      | 301       | 25.32%  |
| 6      | 77        | 6.48%   |
| 8      | 35        | 2.94%   |
| 12     | 12        | 1.01%   |
| 10     | 12        | 1.01%   |
| 1      | 10        | 0.84%   |
| 14     | 5         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1186      | 99.92%  |
| 2      | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 856       | 72.05%  |
| 1      | 332       | 27.95%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1173      | 98.82%  |
| Unknown        | 11        | 0.93%   |
| 32-bit         | 3         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 450       | 36.47%  |
| 0x206a7    | 69        | 5.59%   |
| 0x306a9    | 57        | 4.62%   |
| 0x40651    | 43        | 3.48%   |
| 0x306d4    | 34        | 2.76%   |
| 0x806ea    | 31        | 2.51%   |
| 0x06006705 | 30        | 2.43%   |
| 0x406e3    | 27        | 2.19%   |
| 0x08108109 | 27        | 2.19%   |
| 0x806ec    | 25        | 2.03%   |
| 0x806e9    | 24        | 1.94%   |
| 0x806c1    | 23        | 1.86%   |
| 0x20655    | 23        | 1.86%   |
| 0x1067a    | 21        | 1.7%    |
| 0x906ea    | 18        | 1.46%   |
| 0x0a50000c | 17        | 1.38%   |
| 0x08108102 | 16        | 1.3%    |
| 0x07030105 | 16        | 1.3%    |
| 0x806eb    | 15        | 1.22%   |
| 0x706e5    | 13        | 1.05%   |
| 0x6fd      | 13        | 1.05%   |
| 0x30678    | 13        | 1.05%   |
| 0x706a8    | 12        | 0.97%   |
| 0x306c3    | 11        | 0.89%   |
| 0x08608103 | 11        | 0.89%   |
| 0x20652    | 10        | 0.81%   |
| 0x406c4    | 9         | 0.73%   |
| 0x906e9    | 8         | 0.65%   |
| 0x406c3    | 8         | 0.65%   |
| 0x08600104 | 8         | 0.65%   |
| 0x0700010f | 7         | 0.57%   |
| 0x06001119 | 7         | 0.57%   |
| 0x05000119 | 7         | 0.57%   |
| 0xa0652    | 6         | 0.49%   |
| 0x906a3    | 6         | 0.49%   |
| 0x10676    | 6         | 0.49%   |
| 0x0810100b | 6         | 0.49%   |
| 0x03000027 | 6         | 0.49%   |
| 0x706a1    | 5         | 0.41%   |
| 0x506e3    | 5         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 196       | 16.5%   |
| SandyBridge      | 95        | 8%      |
| IvyBridge        | 92        | 7.74%   |
| Haswell          | 77        | 6.48%   |
| Excavator        | 56        | 4.71%   |
| Unknown          | 55        | 4.63%   |
| Zen+             | 54        | 4.55%   |
| Skylake          | 54        | 4.55%   |
| Westmere         | 52        | 4.38%   |
| Broadwell        | 51        | 4.29%   |
| Silvermont       | 47        | 3.96%   |
| TigerLake        | 45        | 3.79%   |
| Penryn           | 33        | 2.78%   |
| Puma             | 30        | 2.53%   |
| IceLake          | 29        | 2.44%   |
| Goldmont plus    | 28        | 2.36%   |
| Alderlake Hybrid | 26        | 2.19%   |
| Zen 3            | 25        | 2.1%    |
| Zen 2            | 25        | 2.1%    |
| Core             | 21        | 1.77%   |
| Bobcat           | 18        | 1.52%   |
| Zen              | 14        | 1.18%   |
| Goldmont         | 12        | 1.01%   |
| CometLake        | 10        | 0.84%   |
| Piledriver       | 9         | 0.76%   |
| Jaguar           | 9         | 0.76%   |
| Bonnell          | 7         | 0.59%   |
| K10 Llano        | 6         | 0.51%   |
| Tremont          | 5         | 0.42%   |
| Steamroller      | 2         | 0.17%   |
| P6               | 2         | 0.17%   |
| K8 Hammer        | 2         | 0.17%   |
| Gracemont        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 869       | 57.06%  |
| AMD                              | 354       | 23.24%  |
| Nvidia                           | 294       | 19.3%   |
| Silicon Integrated Systems [SiS] | 5         | 0.33%   |
| Silicon Motion                   | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 91        | 5.73%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 90        | 5.67%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 59        | 3.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 55        | 3.47%   |
| Intel UHD Graphics 620                                                                   | 49        | 3.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 45        | 2.84%   |
| Intel HD Graphics 5500                                                                   | 44        | 2.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 44        | 2.77%   |
| Intel HD Graphics 620                                                                    | 41        | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 39        | 2.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 30        | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 1.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 1.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 27        | 1.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 25        | 1.58%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 25        | 1.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 25        | 1.58%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 25        | 1.58%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 24        | 1.51%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 22        | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 21        | 1.32%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 20        | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 17        | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.07%   |
| AMD Lucienne                                                                             | 17        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 1.01%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 15        | 0.95%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 0.88%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 13        | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.82%   |
| Intel HD Graphics 630                                                                    | 12        | 0.76%   |
| Intel HD Graphics 500                                                                    | 12        | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 12        | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                                            | 11        | 0.69%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 11        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 568       | 47.65%  |
| Intel + Nvidia     | 239       | 20.05%  |
| 1 x AMD            | 216       | 18.12%  |
| Intel + AMD        | 55        | 4.61%   |
| AMD + Nvidia       | 42        | 3.52%   |
| 2 x AMD            | 41        | 3.44%   |
| 1 x Nvidia         | 11        | 0.92%   |
| 2 x Intel          | 10        | 0.84%   |
| 1 x SiS            | 5         | 0.42%   |
| Other              | 2         | 0.17%   |
| 2 x Nvidia         | 2         | 0.17%   |
| 1 x Silicon Motion | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1023      | 84.97%  |
| Proprietary | 147       | 12.21%  |
| Unknown     | 34        | 2.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 778       | 63.88%  |
| 1.01-2.0   | 178       | 14.61%  |
| 0.01-0.5   | 146       | 11.99%  |
| 0.51-1.0   | 53        | 4.35%   |
| 3.01-4.0   | 47        | 3.86%   |
| 5.01-6.0   | 8         | 0.66%   |
| 7.01-8.0   | 5         | 0.41%   |
| 2.01-3.0   | 3         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 253       | 19.94%  |
| Chimei Innolux          | 252       | 19.86%  |
| BOE                     | 215       | 16.94%  |
| LG Display              | 159       | 12.53%  |
| Samsung Electronics     | 103       | 8.12%   |
| Goldstar                | 44        | 3.47%   |
| Lenovo                  | 29        | 2.29%   |
| PANDA                   | 21        | 1.65%   |
| InfoVision              | 21        | 1.65%   |
| Sharp                   | 18        | 1.42%   |
| Apple                   | 16        | 1.26%   |
| Chi Mei Optoelectronics | 12        | 0.95%   |
| InnoLux Display         | 10        | 0.79%   |
| Dell                    | 9         | 0.71%   |
| Acer                    | 8         | 0.63%   |
| ViewSonic               | 7         | 0.55%   |
| AOC                     | 7         | 0.55%   |
| Valve                   | 6         | 0.47%   |
| LG Philips              | 6         | 0.47%   |
| CPT                     | 6         | 0.47%   |
| Philips                 | 5         | 0.39%   |
| KDC                     | 5         | 0.39%   |
| HKC                     | 5         | 0.39%   |
| Toshiba                 | 4         | 0.32%   |
| Quanta Display          | 4         | 0.32%   |
| Mi                      | 4         | 0.32%   |
| Hewlett-Packard         | 4         | 0.32%   |
| HannStar                | 4         | 0.32%   |
| Sony                    | 3         | 0.24%   |
| KDB                     | 3         | 0.24%   |
| CSO                     | 3         | 0.24%   |
| Seiko/Epson             | 2         | 0.16%   |
| Panasonic               | 2         | 0.16%   |
| HJC                     | 2         | 0.16%   |
| BenQ                    | 2         | 0.16%   |
| WST                     | 1         | 0.08%   |
| VIE                     | 1         | 0.08%   |
| Unknown                 | 1         | 0.08%   |
| TMX                     | 1         | 0.08%   |
| SPC                     | 1         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 25        | 1.96%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 22        | 1.73%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 21        | 1.65%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 18        | 1.41%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 15        | 1.18%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 15        | 1.18%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 15        | 1.18%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 15        | 1.18%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 13        | 1.02%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 13        | 1.02%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 13        | 1.02%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 11        | 0.86%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 11        | 0.86%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 11        | 0.86%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 11        | 0.86%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 11        | 0.86%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 11        | 0.86%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 10        | 0.78%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 9         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 8         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 8         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 8         | 0.63%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 8         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7         | 0.55%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 7         | 0.55%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 7         | 0.55%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 7         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch       | 7         | 0.55%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                  | 7         | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.55%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 6         | 0.47%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 6         | 0.47%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch           | 6         | 0.47%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 6         | 0.47%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 6         | 0.47%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                  | 6         | 0.47%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                  | 6         | 0.47%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 6         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 5         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 610       | 50.04%  |
| 1920x1080 (FHD)   | 399       | 32.73%  |
| 1920x1200 (WUXGA) | 44        | 3.61%   |
| 1280x800 (WXGA)   | 31        | 2.54%   |
| 1600x900 (HD+)    | 25        | 2.05%   |
| 2880x1800         | 17        | 1.39%   |
| 3840x2160 (4K)    | 16        | 1.31%   |
| 2560x1440 (QHD)   | 13        | 1.07%   |
| 1440x900 (WXGA+)  | 13        | 1.07%   |
| 2560x1600         | 11        | 0.9%    |
| 1360x768          | 8         | 0.66%   |
| 800x1280          | 6         | 0.49%   |
| 1024x600          | 4         | 0.33%   |
| 2160x1440         | 3         | 0.25%   |
| 3840x2400         | 2         | 0.16%   |
| 3440x1440         | 2         | 0.16%   |
| 2560x1080         | 2         | 0.16%   |
| 1920x1280         | 2         | 0.16%   |
| 3456x2160         | 1         | 0.08%   |
| 3200x1800 (QHD+)  | 1         | 0.08%   |
| 3072x1920         | 1         | 0.08%   |
| 2966x900          | 1         | 0.08%   |
| 2736x1824         | 1         | 0.08%   |
| 2288x1287         | 1         | 0.08%   |
| 2256x1504         | 1         | 0.08%   |
| 2240x1400         | 1         | 0.08%   |
| 1920x550          | 1         | 0.08%   |
| 1024x768 (XGA)    | 1         | 0.08%   |
| Unknown           | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 382       | 30.08%  |
| 14      | 368       | 28.98%  |
| 15      | 247       | 19.45%  |
| 12      | 61        | 4.8%    |
| 11      | 41        | 3.23%   |
| 23      | 35        | 2.76%   |
| 18      | 30        | 2.36%   |
| 24      | 14        | 1.1%    |
| 31      | 11        | 0.87%   |
| 21      | 11        | 0.87%   |
| 19      | 10        | 0.79%   |
| 16      | 9         | 0.71%   |
| 17      | 8         | 0.63%   |
| 40      | 7         | 0.55%   |
| 27      | 6         | 0.47%   |
| 7       | 6         | 0.47%   |
| 34      | 4         | 0.31%   |
| 10      | 4         | 0.31%   |
| Unknown | 4         | 0.31%   |
| 48      | 2         | 0.16%   |
| 20      | 2         | 0.16%   |
| 142     | 1         | 0.08%   |
| 72      | 1         | 0.08%   |
| 60      | 1         | 0.08%   |
| 54      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |
| 26      | 1         | 0.08%   |
| 25      | 1         | 0.08%   |
| 9       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 905       | 71.83%  |
| 201-300        | 186       | 14.76%  |
| 501-600        | 55        | 4.37%   |
| 401-500        | 51        | 4.05%   |
| 351-400        | 22        | 1.75%   |
| 601-700        | 13        | 1.03%   |
| 801-900        | 7         | 0.56%   |
| 1-100          | 6         | 0.48%   |
| 1001-1500      | 5         | 0.4%    |
| 701-800        | 4         | 0.32%   |
| Unknown        | 4         | 0.32%   |
| More than 2000 | 1         | 0.08%   |
| 1501-2000      | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1032      | 88.81%  |
| 16/10   | 102       | 8.78%   |
| 3/2     | 10        | 0.86%   |
| 0.67    | 6         | 0.52%   |
| 21/9    | 4         | 0.34%   |
| 4/3     | 3         | 0.26%   |
| Unknown | 3         | 0.26%   |
| 32/9    | 1         | 0.09%   |
| 1.00    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 681       | 53.75%  |
| 101-110        | 245       | 19.34%  |
| 71-80          | 61        | 4.81%   |
| 61-70          | 59        | 4.66%   |
| 201-250        | 56        | 4.42%   |
| 51-60          | 41        | 3.24%   |
| 141-150        | 30        | 2.37%   |
| 351-500        | 15        | 1.18%   |
| 151-200        | 13        | 1.03%   |
| 91-100         | 9         | 0.71%   |
| 121-130        | 8         | 0.63%   |
| More than 1000 | 7         | 0.55%   |
| 301-350        | 7         | 0.55%   |
| 111-120        | 7         | 0.55%   |
| 501-1000       | 7         | 0.55%   |
| 1-40           | 6         | 0.47%   |
| 41-50          | 5         | 0.39%   |
| 251-300        | 4         | 0.32%   |
| Unknown        | 4         | 0.32%   |
| 131-140        | 2         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 553       | 43.99%  |
| 121-160       | 441       | 35.08%  |
| 51-100        | 139       | 11.06%  |
| 161-240       | 84        | 6.68%   |
| More than 240 | 26        | 2.07%   |
| 1-50          | 10        | 0.8%    |
| Unknown       | 4         | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1059      | 87.38%  |
| 2     | 123       | 10.15%  |
| 0     | 26        | 2.15%   |
| 3     | 4         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 697       | 36.82%  |
| Intel                                  | 468       | 24.72%  |
| Qualcomm Atheros                       | 364       | 19.23%  |
| Broadcom                               | 115       | 6.08%   |
| MediaTek                               | 57        | 3.01%   |
| Xiaomi                                 | 21        | 1.11%   |
| Broadcom Limited                       | 21        | 1.11%   |
| Samsung Electronics                    | 17        | 0.9%    |
| TP-Link                                | 16        | 0.85%   |
| Ralink Technology                      | 16        | 0.85%   |
| OPPO Electronics                       | 14        | 0.74%   |
| Ralink                                 | 11        | 0.58%   |
| Marvell Technology Group               | 11        | 0.58%   |
| Qualcomm Atheros Communications        | 9         | 0.48%   |
| JMicron Technology                     | 8         | 0.42%   |
| ASIX Electronics                       | 6         | 0.32%   |
| Huawei Technologies                    | 5         | 0.26%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.21%   |
| Sierra Wireless                        | 4         | 0.21%   |
| Ericsson Business Mobile Networks      | 4         | 0.21%   |
| Qualcomm                               | 3         | 0.16%   |
| ICS Advent                             | 3         | 0.16%   |
| Attansic Technology                    | 3         | 0.16%   |
| Nvidia                                 | 2         | 0.11%   |
| Hewlett-Packard                        | 2         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Mercucys                               | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| Lenovo                                 | 1         | 0.05%   |
| HTC (High Tech Computer)               | 1         | 0.05%   |
| Foxconn / Hon Hai                      | 1         | 0.05%   |
| Fibocom                                | 1         | 0.05%   |
| Edimax Technology                      | 1         | 0.05%   |
| Dell                                   | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| ASUSTek Computer                       | 1         | 0.05%   |
| AboCom Systems                         | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 423       | 18.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 147       | 6.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 96        | 4.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 77        | 3.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 65        | 2.9%    |
| Intel Wireless 8265 / 8275                                             | 52        | 2.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 44        | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 42        | 1.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 39        | 1.74%   |
| Intel Wireless 7265                                                    | 36        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 35        | 1.56%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 31        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 31        | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 29        | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 28        | 1.25%   |
| Intel Wi-Fi 6 AX201                                                    | 28        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 28        | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 23        | 1.02%   |
| Intel Wireless 7260                                                    | 23        | 1.02%   |
| Intel Wi-Fi 6 AX200                                                    | 23        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 23        | 1.02%   |
| Intel Wireless 8260                                                    | 22        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                          | 22        | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 21        | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 18        | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 18        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 17        | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 17        | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                  | 17        | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 16        | 0.71%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 16        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 15        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 14        | 0.62%   |
| Intel Wireless 3165                                                    | 14        | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 13        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13        | 0.58%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 431       | 35.1%   |
| Qualcomm Atheros                | 330       | 26.87%  |
| Realtek Semiconductor           | 252       | 20.52%  |
| Broadcom                        | 93        | 7.57%   |
| MediaTek                        | 47        | 3.83%   |
| Broadcom Limited                | 17        | 1.38%   |
| Ralink Technology               | 16        | 1.3%    |
| TP-Link                         | 11        | 0.9%    |
| Ralink                          | 11        | 0.9%    |
| Qualcomm Atheros Communications | 9         | 0.73%   |
| Sierra Wireless                 | 4         | 0.33%   |
| Mercucys                        | 1         | 0.08%   |
| Linksys                         | 1         | 0.08%   |
| Fibocom                         | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |
| Dell                            | 1         | 0.08%   |
| D-Link                          | 1         | 0.08%   |
| AboCom Systems                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 96        | 7.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 77        | 6.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 65        | 5.26%   |
| Intel Wireless 8265 / 8275                                     | 52        | 4.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 42        | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 39        | 3.16%   |
| Intel Wireless 7265                                            | 36        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 35        | 2.83%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 31        | 2.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 31        | 2.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 29        | 2.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 28        | 2.27%   |
| Intel Wi-Fi 6 AX201                                            | 28        | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 28        | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 23        | 1.86%   |
| Intel Wireless 7260                                            | 23        | 1.86%   |
| Intel Wi-Fi 6 AX200                                            | 23        | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.86%   |
| Intel Wireless 8260                                            | 22        | 1.78%   |
| Broadcom BCM43142 802.11b/g/n                                  | 22        | 1.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 18        | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 16        | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 1.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 14        | 1.13%   |
| Intel Wireless 3165                                            | 14        | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 1.05%   |
| Ralink MT7601U Wireless Adapter                                | 12        | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 0.97%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 11        | 0.89%   |
| Realtek 802.11n WLAN Adapter                                   | 10        | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                | 9         | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 9         | 0.73%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 9         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 0.73%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 9         | 0.73%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8         | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 8         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 593       | 59.78%  |
| Intel                                  | 169       | 17.04%  |
| Qualcomm Atheros                       | 80        | 8.06%   |
| Broadcom                               | 34        | 3.43%   |
| Xiaomi                                 | 21        | 2.12%   |
| OPPO Electronics                       | 14        | 1.41%   |
| Samsung Electronics                    | 12        | 1.21%   |
| Marvell Technology Group               | 11        | 1.11%   |
| MediaTek                               | 10        | 1.01%   |
| JMicron Technology                     | 8         | 0.81%   |
| Broadcom Limited                       | 6         | 0.6%    |
| ASIX Electronics                       | 6         | 0.6%    |
| TP-Link                                | 5         | 0.5%    |
| Silicon Integrated Systems [SiS]       | 4         | 0.4%    |
| Qualcomm                               | 3         | 0.3%    |
| ICS Advent                             | 3         | 0.3%    |
| Attansic Technology                    | 3         | 0.3%    |
| Nvidia                                 | 2         | 0.2%    |
| Hewlett-Packard                        | 2         | 0.2%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Lenovo                                 | 1         | 0.1%    |
| Huawei Technologies                    | 1         | 0.1%    |
| HTC (High Tech Computer)               | 1         | 0.1%    |
| Foxconn / Hon Hai                      | 1         | 0.1%    |
| ASUSTek Computer                       | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 423       | 42.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 147       | 14.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 44        | 4.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 21        | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 17        | 1.71%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 17        | 1.71%   |
| Intel Ethernet Connection (3) I218-LM                                  | 17        | 1.71%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 1.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 1.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13        | 1.31%   |
| Intel Ethernet Connection I219-LM                                      | 13        | 1.31%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 12        | 1.2%    |
| OPPO OnePlus Nord 4                                                    | 12        | 1.2%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 10        | 1%      |
| Intel Ethernet Connection (4) I219-V                                   | 8         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                               | 8         | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 7         | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 7         | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 6         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 6         | 0.6%    |
| MediaTek Infinix SMART 5                                               | 6         | 0.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 6         | 0.6%    |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.6%    |
| Intel 82567LM Gigabit Network Connection                               | 6         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 0.5%    |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                                  | 5         | 0.5%    |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.5%    |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 4         | 0.4%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 4         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 4         | 0.4%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 4         | 0.4%    |
| Intel Ethernet Connection I219-V                                       | 4         | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.4%    |
| TP-Link USB 10/100 LAN                                                 | 3         | 0.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1164      | 55.22%  |
| Ethernet | 931       | 44.17%  |
| Modem    | 13        | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1021      | 86.02%  |
| Ethernet | 165       | 13.9%   |
| Modem    | 1         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 860       | 72.39%  |
| 1     | 305       | 25.67%  |
| 0     | 17        | 1.43%   |
| 3     | 6         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1091      | 90.31%  |
| Yes  | 117       | 9.69%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 341       | 35.67%  |
| Realtek Semiconductor           | 162       | 16.95%  |
| IMC Networks                    | 115       | 12.03%  |
| Qualcomm Atheros Communications | 84        | 8.79%   |
| Lite-On Technology              | 75        | 7.85%   |
| Broadcom                        | 54        | 5.65%   |
| Foxconn / Hon Hai               | 37        | 3.87%   |
| Toshiba                         | 16        | 1.67%   |
| Apple                           | 14        | 1.46%   |
| Dell                            | 11        | 1.15%   |
| Cambridge Silicon Radio         | 11        | 1.15%   |
| Ralink                          | 7         | 0.73%   |
| Hewlett-Packard                 | 7         | 0.73%   |
| MediaTek                        | 6         | 0.63%   |
| Foxconn International           | 5         | 0.52%   |
| Realtek                         | 3         | 0.31%   |
| ASUSTek Computer                | 3         | 0.31%   |
| Micro Star International        | 2         | 0.21%   |
| Chicony Electronics             | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |
| Actions                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 140       | 14.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 82        | 8.58%   |
| Realtek Bluetooth Radio                             | 71        | 7.43%   |
| IMC Networks Bluetooth Device                       | 59        | 6.17%   |
| Intel AX201 Bluetooth                               | 50        | 5.23%   |
| Qualcomm Atheros  Bluetooth Device                  | 42        | 4.39%   |
| Realtek  Bluetooth 4.2 Adapter                      | 40        | 4.18%   |
| Lite-On Bluetooth Device                            | 27        | 2.82%   |
| Intel AX200 Bluetooth                               | 23        | 2.41%   |
| IMC Networks Bluetooth Radio                        | 20        | 2.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 19        | 1.99%   |
| IMC Networks Wireless_Device                        | 19        | 1.99%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.88%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 1.78%   |
| Realtek 802.11ac WLAN Adapter                       | 16        | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 1.67%   |
| Intel AX211 Bluetooth                               | 15        | 1.57%   |
| Lite-On Wireless_Device                             | 13        | 1.36%   |
| Realtek RTL8821A Bluetooth                          | 12        | 1.26%   |
| Realtek RTL8723B Bluetooth                          | 12        | 1.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 11        | 1.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 1.15%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.94%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.84%   |
| Lite-On Atheros Bluetooth                           | 8         | 0.84%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 8         | 0.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 8         | 0.84%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.73%   |
| Apple Bluetooth Host Controller                     | 7         | 0.73%   |
| MediaTek Wireless_Device                            | 6         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.52%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 5         | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 5         | 0.52%   |
| Foxconn / Hon Hai BCM20702A0                        | 5         | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.52%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.42%   |
| Intel AX210 Bluetooth                               | 4         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 877       | 66.34%  |
| AMD                              | 297       | 22.47%  |
| Nvidia                           | 107       | 8.09%   |
| JMTek                            | 6         | 0.45%   |
| Generalplus Technology           | 6         | 0.45%   |
| Silicon Integrated Systems [SiS] | 5         | 0.38%   |
| C-Media Electronics              | 4         | 0.3%    |
| Samson Technologies              | 3         | 0.23%   |
| Samsung Electronics              | 2         | 0.15%   |
| Logitech                         | 2         | 0.15%   |
| Jieli Technology                 | 2         | 0.15%   |
| ASUSTek Computer                 | 2         | 0.15%   |
| STMicroelectronics               | 1         | 0.08%   |
| SAVITECH                         | 1         | 0.08%   |
| Realtek Semiconductor            | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |
| GS3                              | 1         | 0.08%   |
| Dell                             | 1         | 0.08%   |
| Cooler Master                    | 1         | 0.08%   |
| Conexant Systems                 | 1         | 0.08%   |
| Barco Display Systems            | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 154       | 8.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 138       | 8.04%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 114       | 6.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 71        | 4.14%   |
| AMD FCH Azalia Controller                                                                         | 62        | 3.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 59        | 3.44%   |
| Intel 8 Series HD Audio Controller                                                                | 59        | 3.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 59        | 3.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 59        | 3.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 56        | 3.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 52        | 3.03%   |
| Intel Broadwell-U Audio Controller                                                                | 51        | 2.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 51        | 2.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 50        | 2.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 45        | 2.62%   |
| AMD High Definition Audio Controller                                                              | 44        | 2.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 39        | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                                        | 29        | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 28        | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 27        | 1.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 26        | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 1.34%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 23        | 1.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 23        | 1.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 1.05%   |
| AMD Wrestler HDMI Audio                                                                           | 17        | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15        | 0.87%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 0.87%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 0.76%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 12        | 0.7%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 0.64%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 11        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 10        | 0.58%   |
| AMD Trinity HDMI Audio Controller                                                                 | 9         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 293       | 31.1%   |
| SK hynix                                | 190       | 20.17%  |
| Micron Technology                       | 121       | 12.85%  |
| Kingston                                | 72        | 7.64%   |
| Unknown                                 | 55        | 5.84%   |
| Team                                    | 34        | 3.61%   |
| Corsair                                 | 31        | 3.29%   |
| V-GeN                                   | 24        | 2.55%   |
| Ramaxel Technology                      | 22        | 2.34%   |
| Elpida                                  | 16        | 1.7%    |
| Nanya Technology                        | 14        | 1.49%   |
| Unknown (ABCD)                          | 12        | 1.27%   |
| A-DATA Technology                       | 9         | 0.96%   |
| Unknown                                 | 6         | 0.64%   |
| Transcend                               | 4         | 0.42%   |
| Crucial                                 | 4         | 0.42%   |
| Apacer                                  | 4         | 0.42%   |
| SHARETRONIC                             | 3         | 0.32%   |
| ASint Technology                        | 3         | 0.32%   |
| Visipro                                 | 2         | 0.21%   |
| Shenzhen SCY                            | 2         | 0.21%   |
| Lexar                                   | 2         | 0.21%   |
| A Force                                 | 2         | 0.21%   |
| Unknown (940A)                          | 1         | 0.11%   |
| Unknown (8A02)                          | 1         | 0.11%   |
| Unknown (0x0080)                        | 1         | 0.11%   |
| Teikon                                  | 1         | 0.11%   |
| Strontium                               | 1         | 0.11%   |
| Silicon Power Computer & Communications | 1         | 0.11%   |
| Silicon Power                           | 1         | 0.11%   |
| Qumo                                    | 1         | 0.11%   |
| Patriot                                 | 1         | 0.11%   |
| Kingmax                                 | 1         | 0.11%   |
| Hikvision                               | 1         | 0.11%   |
| GOODRAM                                 | 1         | 0.11%   |
| Goldkey                                 | 1         | 0.11%   |
| G.Skill                                 | 1         | 0.11%   |
| Foxline                                 | 1         | 0.11%   |
| ff                                      | 1         | 0.11%   |
| 4ea5                                    | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 20        | 1.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.49%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 1.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 14        | 1.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 1.29%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 12        | 1.19%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.19%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 12        | 1.19%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 11        | 1.09%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 11        | 1.09%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 9         | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.89%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 9         | 0.89%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.89%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 8         | 0.79%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 8         | 0.79%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 8         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 8         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.79%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 3200MT/s            | 8         | 0.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 7         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.7%    |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 6         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.6%    |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 6         | 0.6%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 6         | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.6%    |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 6         | 0.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.6%    |
| Unknown                                                          | 6         | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.5%    |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 3200MT/s            | 5         | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.5%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.5%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 340       | 46.13%  |
| DDR3    | 281       | 38.13%  |
| LPDDR4  | 39        | 5.29%   |
| LPDDR5  | 20        | 2.71%   |
| DDR2    | 20        | 2.71%   |
| LPDDR3  | 12        | 1.63%   |
| SDRAM   | 11        | 1.49%   |
| DDR5    | 9         | 1.22%   |
| Unknown | 3         | 0.41%   |
| DRAM    | 2         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 661       | 90.55%  |
| Row Of Chips | 58        | 7.95%   |
| Chip         | 6         | 0.82%   |
| Unknown      | 5         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 318       | 37.41%  |
| 8192  | 295       | 34.71%  |
| 2048  | 106       | 12.47%  |
| 16384 | 88        | 10.35%  |
| 32768 | 28        | 3.29%   |
| 1024  | 13        | 1.53%   |
| 6144  | 1         | 0.12%   |
| 512   | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 198       | 23.38%  |
| 2667    | 153       | 18.06%  |
| 3200    | 142       | 16.77%  |
| 2400    | 81        | 9.56%   |
| 2133    | 41        | 4.84%   |
| 1334    | 40        | 4.72%   |
| 1333    | 38        | 4.49%   |
| 3266    | 20        | 2.36%   |
| 1067    | 18        | 2.13%   |
| 6400    | 16        | 1.89%   |
| 800     | 11        | 1.3%    |
| Unknown | 11        | 1.3%    |
| 4267    | 10        | 1.18%   |
| 4266    | 9         | 1.06%   |
| 667     | 9         | 1.06%   |
| 8400    | 8         | 0.94%   |
| 4199    | 8         | 0.94%   |
| 1867    | 7         | 0.83%   |
| 5600    | 5         | 0.59%   |
| 4800    | 4         | 0.47%   |
| 7500    | 3         | 0.35%   |
| 533     | 3         | 0.35%   |
| 2048    | 2         | 0.24%   |
| 1866    | 2         | 0.24%   |
| 1066    | 2         | 0.24%   |
| 975     | 2         | 0.24%   |
| 5500    | 1         | 0.12%   |
| 3333    | 1         | 0.12%   |
| 1776    | 1         | 0.12%   |
| 333     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 8         | 57.14%  |
| Canon              | 3         | 21.43%  |
| Brother Industries | 2         | 14.29%  |
| STMicroelectronics | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seiko Epson L360 Series             | 2         | 14.29%  |
| Seiko Epson L312 Series             | 2         | 14.29%  |
| Canon iP2700 series                 | 2         | 14.29%  |
| Brother DCP-T300                    | 2         | 14.29%  |
| STMicroelectronics USB Printer Port | 1         | 7.14%   |
| Seiko Epson L386 Series             | 1         | 7.14%   |
| Seiko Epson L355 Series             | 1         | 7.14%   |
| Seiko Epson L3210 Series            | 1         | 7.14%   |
| Seiko Epson L120 Series             | 1         | 7.14%   |
| Canon CanoScan LiDE 300             | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4400F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 290       | 27.23%  |
| IMC Networks                           | 158       | 14.84%  |
| Realtek Semiconductor                  | 95        | 8.92%   |
| Bison Electronics                      | 73        | 6.85%   |
| Sunplus Innovation Technology          | 60        | 5.63%   |
| Quanta                                 | 55        | 5.16%   |
| Microdia                               | 50        | 4.69%   |
| Syntek                                 | 46        | 4.32%   |
| Cheng Uei Precision Industry (Foxlink) | 46        | 4.32%   |
| Suyin                                  | 28        | 2.63%   |
| Alcor Micro                            | 26        | 2.44%   |
| Acer                                   | 19        | 1.78%   |
| Lite-On Technology                     | 18        | 1.69%   |
| Luxvisions Innotech Limited            | 17        | 1.6%    |
| Sonix Technology                       | 14        | 1.31%   |
| Apple                                  | 9         | 0.85%   |
| Silicon Motion                         | 7         | 0.66%   |
| Ricoh                                  | 7         | 0.66%   |
| Lenovo                                 | 6         | 0.56%   |
| Importek                               | 6         | 0.56%   |
| Shinetech                              | 5         | 0.47%   |
| Primax Electronics                     | 4         | 0.38%   |
| SunplusIT                              | 3         | 0.28%   |
| Sunplus Technology                     | 2         | 0.19%   |
| Samsung Electronics                    | 2         | 0.19%   |
| Jieli Technology                       | 2         | 0.19%   |
| ALi                                    | 2         | 0.19%   |
| 2M UVC CAMERA                          | 2         | 0.19%   |
| Unknown                                | 2         | 0.19%   |
| vivo                                   | 1         | 0.09%   |
| Tripath Technology                     | 1         | 0.09%   |
| Pixart Imaging                         | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| Omnivision                             | 1         | 0.09%   |
| Logitech                               | 1         | 0.09%   |
| Huawei Technologies                    | 1         | 0.09%   |
| Genesys Logic                          | 1         | 0.09%   |
| GEMBIRD                                | 1         | 0.09%   |
| eMPIA Technology                       | 1         | 0.09%   |
| DigiTech                               | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 47        | 4.4%    |
| Chicony Integrated Camera                                       | 42        | 3.93%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 39        | 3.65%   |
| Chicony HD WebCam                                               | 36        | 3.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 33        | 3.09%   |
| Syntek Integrated Camera                                        | 26        | 2.43%   |
| IMC Networks Integrated Camera                                  | 26        | 2.43%   |
| Chicony HP Truevision HD camera                                 | 20        | 1.87%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 18        | 1.69%   |
| Microdia Integrated_Webcam_HD                                   | 18        | 1.69%   |
| Chicony USB2.0 HD UVC WebCam                                    | 18        | 1.69%   |
| Bison Lenovo EasyCamera                                         | 17        | 1.59%   |
| Realtek Integrated_Webcam_HD                                    | 16        | 1.5%    |
| IMC Networks EasyCamera                                         | 14        | 1.31%   |
| Sonix USB2.0 HD UVC WebCam                                      | 13        | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 13        | 1.22%   |
| Bison Integrated Camera                                         | 13        | 1.22%   |
| Quanta HD User Facing                                           | 12        | 1.12%   |
| IMC Networks Lenovo EasyCamera                                  | 12        | 1.12%   |
| Chicony HP Truevision HD                                        | 11        | 1.03%   |
| Syntek EasyCamera                                               | 10        | 0.94%   |
| Sunplus Asus Webcam                                             | 10        | 0.94%   |
| Chicony Lenovo EasyCamera                                       | 10        | 0.94%   |
| Syntek Lenovo EasyCamera                                        | 9         | 0.84%   |
| Realtek USB Camera                                              | 9         | 0.84%   |
| Microdia Integrated Webcam                                      | 9         | 0.84%   |
| Chicony HD User Facing                                          | 9         | 0.84%   |
| Chicony EasyCamera                                              | 9         | 0.84%   |
| Alcor Micro USB 2.0 Camera                                      | 9         | 0.84%   |
| Sunplus Integrated_Webcam_HD                                    | 8         | 0.75%   |
| Sunplus HD WebCam                                               | 8         | 0.75%   |
| Realtek USB2.0 HD UVC WebCam                                    | 8         | 0.75%   |
| Realtek USB2.0 camera                                           | 8         | 0.75%   |
| Quanta VGA WebCam                                               | 8         | 0.75%   |
| Lite-On Integrated Camera                                       | 8         | 0.75%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 8         | 0.75%   |
| Chicony TOSHIBA Web Camera - HD                                 | 8         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 8         | 0.75%   |
| Suyin 1.3M HD WebCam                                            | 7         | 0.66%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 57        | 33.33%  |
| Synaptics                  | 32        | 18.71%  |
| Elan Microelectronics      | 32        | 18.71%  |
| LighTuning Technology      | 14        | 8.19%   |
| Shenzhen Goodix Technology | 13        | 7.6%    |
| AuthenTec                  | 11        | 6.43%   |
| Upek                       | 6         | 3.51%   |
| Focal-systems.Corp         | 3         | 1.75%   |
| STMicroelectronics         | 2         | 1.17%   |
| DigitalPersona             | 1         | 0.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 16        | 9.36%   |
| Elan ELAN:ARM-M4                                                           | 15        | 8.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 7.6%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 7.6%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 7.02%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 11        | 6.43%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 4.68%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 4.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 4.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 3.51%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 3.51%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 2.92%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 2.92%   |
| Validity Sensors VFS491                                                    | 4         | 2.34%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 2.34%   |
| AuthenTec AES1600                                                          | 4         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.75%   |
| Synaptics  WBDI                                                            | 3         | 1.75%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 3         | 1.75%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.17%   |
| Synaptics UWP WBDI                                                         | 2         | 1.17%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.17%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.17%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 1.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.58%   |
| Synaptics WBDI                                                             | 1         | 0.58%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.58%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 0.58%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.58%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.58%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.58%   |
| AuthenTec AES2810                                                          | 1         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 50%     |
| Alcor Micro | 10        | 20.83%  |
| O2 Micro    | 8         | 16.67%  |
| Upek        | 4         | 8.33%   |
| Lenovo      | 2         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 27.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 20.83%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 14.58%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 8.33%   |
| Broadcom 58200                                                               | 3         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.17%   |
| Broadcom 5880                                                                | 2         | 4.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 828       | 68.2%   |
| 1     | 306       | 25.21%  |
| 2     | 70        | 5.77%   |
| 3     | 8         | 0.66%   |
| 6     | 1         | 0.08%   |
| 5     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 168       | 36.68%  |
| Graphics card            | 104       | 22.71%  |
| Net/wireless             | 50        | 10.92%  |
| Chipcard                 | 45        | 9.83%   |
| Multimedia controller    | 30        | 6.55%   |
| Bluetooth                | 22        | 4.8%    |
| Camera                   | 11        | 2.4%    |
| Communication controller | 8         | 1.75%   |
| Net/ethernet             | 6         | 1.31%   |
| Storage                  | 4         | 0.87%   |
| Flash memory             | 3         | 0.66%   |
| Sound                    | 2         | 0.44%   |
| Card reader              | 2         | 0.44%   |
| Video                    | 1         | 0.22%   |
| Network                  | 1         | 0.22%   |
| Modem                    | 1         | 0.22%   |


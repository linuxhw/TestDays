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

Total: 1362

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A514-55              | Notebook    | [391048b46f](https://linux-hardware.org/?probe=391048b46f) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [49d6eb853f](https://linux-hardware.org/?probe=49d6eb853f) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [5de7efb403](https://linux-hardware.org/?probe=5de7efb403) | Nov 01, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [142e1c0695](https://linux-hardware.org/?probe=142e1c0695) | Oct 31, 2022 |
| Acer          | Aspire A514-55              | Notebook    | [87f4a137dc](https://linux-hardware.org/?probe=87f4a137dc) | Oct 31, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da3e45d6c3](https://linux-hardware.org/?probe=da3e45d6c3) | Oct 29, 2022 |
| AXIOO         | Mybook 14H                  | Notebook    | [f8a7c19640](https://linux-hardware.org/?probe=f8a7c19640) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [0084d271e4](https://linux-hardware.org/?probe=0084d271e4) | Oct 28, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a490ccddeb](https://linux-hardware.org/?probe=a490ccddeb) | Oct 25, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [0ceb92e552](https://linux-hardware.org/?probe=0ceb92e552) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [669c715fa8](https://linux-hardware.org/?probe=669c715fa8) | Oct 20, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6d5c1da4b7](https://linux-hardware.org/?probe=6d5c1da4b7) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3b87b259c8](https://linux-hardware.org/?probe=3b87b259c8) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [e438393dca](https://linux-hardware.org/?probe=e438393dca) | Oct 19, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [7891f1e18c](https://linux-hardware.org/?probe=7891f1e18c) | Oct 18, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [b7a14994b1](https://linux-hardware.org/?probe=b7a14994b1) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [d78ecde0a2](https://linux-hardware.org/?probe=d78ecde0a2) | Oct 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [adda30ef79](https://linux-hardware.org/?probe=adda30ef79) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 3 11IGL05 82... | Convertible | [6e32a194d3](https://linux-hardware.org/?probe=6e32a194d3) | Oct 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [665763812f](https://linux-hardware.org/?probe=665763812f) | Oct 16, 2022 |
| Dell          | Latitude 3490               | Notebook    | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [eff5a7242e](https://linux-hardware.org/?probe=eff5a7242e) | Oct 15, 2022 |
| Intel         | SandyBridge Platform        | Notebook    | [3cc3d23297](https://linux-hardware.org/?probe=3cc3d23297) | Oct 14, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [ce1dbed861](https://linux-hardware.org/?probe=ce1dbed861) | Oct 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46bc0c74c6](https://linux-hardware.org/?probe=46bc0c74c6) | Oct 11, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [a6eb228e33](https://linux-hardware.org/?probe=a6eb228e33) | Oct 10, 2022 |
| AXIOO         | Slimbook 13                 | Notebook    | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [ce8e31b40d](https://linux-hardware.org/?probe=ce8e31b40d) | Oct 02, 2022 |
| HP            | Compaq 420                  | Notebook    | [d3e367cedc](https://linux-hardware.org/?probe=d3e367cedc) | Oct 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [25e087916a](https://linux-hardware.org/?probe=25e087916a) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [6f6704ea90](https://linux-hardware.org/?probe=6f6704ea90) | Oct 01, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [5e9a9b60e6](https://linux-hardware.org/?probe=5e9a9b60e6) | Oct 01, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [345600d392](https://linux-hardware.org/?probe=345600d392) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [af7b986ff8](https://linux-hardware.org/?probe=af7b986ff8) | Sep 28, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [4a285e2052](https://linux-hardware.org/?probe=4a285e2052) | Sep 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [b2abaca929](https://linux-hardware.org/?probe=b2abaca929) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [ab84311fcc](https://linux-hardware.org/?probe=ab84311fcc) | Sep 24, 2022 |
| Lenovo        | IdeaPad Geming 3 15ARH05... | Notebook    | [48a40a2f04](https://linux-hardware.org/?probe=48a40a2f04) | Sep 24, 2022 |
| HP            | 198E                        | Desktop     | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [b879e569d1](https://linux-hardware.org/?probe=b879e569d1) | Sep 24, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [79d9dab7dc](https://linux-hardware.org/?probe=79d9dab7dc) | Sep 24, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [64ff44a074](https://linux-hardware.org/?probe=64ff44a074) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f24f78c803](https://linux-hardware.org/?probe=f24f78c803) | Sep 19, 2022 |
| ECS           | A55F2-M4                    | Desktop     | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [fddeb02707](https://linux-hardware.org/?probe=fddeb02707) | Sep 18, 2022 |
| Acer          | Swift SF314-71              | Notebook    | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [26cdf51338](https://linux-hardware.org/?probe=26cdf51338) | Sep 15, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0S10... | Notebook    | [0fd5868b54](https://linux-hardware.org/?probe=0fd5868b54) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | Notebook    | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| Lenovo        | ZHAOYANG E47                | Notebook    | [7f1fab5ff0](https://linux-hardware.org/?probe=7f1fab5ff0) | Sep 11, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [bfa4cc7ddc](https://linux-hardware.org/?probe=bfa4cc7ddc) | Sep 10, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [e1b3cac9d8](https://linux-hardware.org/?probe=e1b3cac9d8) | Sep 07, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [983d14d741](https://linux-hardware.org/?probe=983d14d741) | Sep 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [c430bf0275](https://linux-hardware.org/?probe=c430bf0275) | Sep 03, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [1fee695aec](https://linux-hardware.org/?probe=1fee695aec) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [5ac694007d](https://linux-hardware.org/?probe=5ac694007d) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [b8c22aafab](https://linux-hardware.org/?probe=b8c22aafab) | Sep 01, 2022 |
| Lenovo        | ThinkPad L512 259756M       | Notebook    | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [75a6e1e9a1](https://linux-hardware.org/?probe=75a6e1e9a1) | Aug 29, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Dell          | Latitude 7280               | Notebook    | [d214e30b1e](https://linux-hardware.org/?probe=d214e30b1e) | Aug 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| Intel         | H61                         | Desktop     | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | Notebook    | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | One Z1402                   | Notebook    | [d4b5a11843](https://linux-hardware.org/?probe=d4b5a11843) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [9ac20fda5a](https://linux-hardware.org/?probe=9ac20fda5a) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [0b95f78b15](https://linux-hardware.org/?probe=0b95f78b15) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [903fda443e](https://linux-hardware.org/?probe=903fda443e) | Aug 14, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [a7d615e104](https://linux-hardware.org/?probe=a7d615e104) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| HP            | 14                          | Notebook    | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | Desktop     | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| ASUSTek       | K43E                        | Notebook    | [fc2d9e330c](https://linux-hardware.org/?probe=fc2d9e330c) | Aug 11, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [7dbc1a26ca](https://linux-hardware.org/?probe=7dbc1a26ca) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [6dbb0a4eb9](https://linux-hardware.org/?probe=6dbb0a4eb9) | Aug 06, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [1c95e4f03d](https://linux-hardware.org/?probe=1c95e4f03d) | Aug 04, 2022 |
| ASUSTek       | K43E                        | Notebook    | [373d77aec0](https://linux-hardware.org/?probe=373d77aec0) | Aug 04, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [9c842ec71c](https://linux-hardware.org/?probe=9c842ec71c) | Aug 03, 2022 |
| HP            | 431                         | Notebook    | [2f6caa3d47](https://linux-hardware.org/?probe=2f6caa3d47) | Aug 02, 2022 |
| HP            | 431                         | Notebook    | [68fa0d3ebc](https://linux-hardware.org/?probe=68fa0d3ebc) | Aug 02, 2022 |
| Lenovo        | ThinkPad X230 23245NJ       | Notebook    | [3c85e43b86](https://linux-hardware.org/?probe=3c85e43b86) | Aug 01, 2022 |
| HP            | 240 G8 Notebook PC          | Notebook    | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Acer          | Z476                        | Notebook    | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2dd83a16c7](https://linux-hardware.org/?probe=2dd83a16c7) | Aug 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [6c742b6234](https://linux-hardware.org/?probe=6c742b6234) | Jul 30, 2022 |
| ASUSTek       | K43E                        | Notebook    | [f6d8225dd6](https://linux-hardware.org/?probe=f6d8225dd6) | Jul 28, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [3d23b4bbdc](https://linux-hardware.org/?probe=3d23b4bbdc) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [527b25a7f3](https://linux-hardware.org/?probe=527b25a7f3) | Jul 25, 2022 |
| Dell          | G3 3579                     | Notebook    | [96fab186c3](https://linux-hardware.org/?probe=96fab186c3) | Jul 24, 2022 |
| MSI           | 2A9C                        | Desktop     | [b0441c833d](https://linux-hardware.org/?probe=b0441c833d) | Jul 24, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | Notebook    | [a6e3ee128e](https://linux-hardware.org/?probe=a6e3ee128e) | Jul 20, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [6dcb934555](https://linux-hardware.org/?probe=6dcb934555) | Jul 17, 2022 |
| Acer          | Aspire E5-475G              | Notebook    | [1f7429b29d](https://linux-hardware.org/?probe=1f7429b29d) | Jul 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [54c99c7f2f](https://linux-hardware.org/?probe=54c99c7f2f) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [cf41c08ea5](https://linux-hardware.org/?probe=cf41c08ea5) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [d651eb1f7d](https://linux-hardware.org/?probe=d651eb1f7d) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b04b2741a0](https://linux-hardware.org/?probe=b04b2741a0) | Jul 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [b00361cdbd](https://linux-hardware.org/?probe=b00361cdbd) | Jul 13, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [cde5f69fef](https://linux-hardware.org/?probe=cde5f69fef) | Jul 13, 2022 |
| Dell          | 0WCWFJ A00                  | All in one  | [89a6f4711c](https://linux-hardware.org/?probe=89a6f4711c) | Jul 11, 2022 |
| HP            | Pavilion g4                 | Notebook    | [87a044a9c7](https://linux-hardware.org/?probe=87a044a9c7) | Jul 11, 2022 |
| Dell          | Latitude E6440              | Notebook    | [495237a0b0](https://linux-hardware.org/?probe=495237a0b0) | Jul 09, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [01dccaff29](https://linux-hardware.org/?probe=01dccaff29) | Jul 07, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [80e2fc79da](https://linux-hardware.org/?probe=80e2fc79da) | Jul 07, 2022 |
| Toshiba       | Satellite C640              | Notebook    | [cd8f69d739](https://linux-hardware.org/?probe=cd8f69d739) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [356272d726](https://linux-hardware.org/?probe=356272d726) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Laptop 14s-cf2xxx           | Notebook    | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Lenovo        | ThinkPad L412 0585E86       | Notebook    | [ad82717c98](https://linux-hardware.org/?probe=ad82717c98) | Jul 01, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [1bf580aa91](https://linux-hardware.org/?probe=1bf580aa91) | Jun 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [97d88d7e00](https://linux-hardware.org/?probe=97d88d7e00) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [3cec3cffbb](https://linux-hardware.org/?probe=3cec3cffbb) | Jun 30, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [bac4b49e55](https://linux-hardware.org/?probe=bac4b49e55) | Jun 30, 2022 |
| Biostar       | A68N-5600E                  | Desktop     | [d5cfa78343](https://linux-hardware.org/?probe=d5cfa78343) | Jun 29, 2022 |
| Acer          | Aspire A314-35              | Notebook    | [dfdd48254c](https://linux-hardware.org/?probe=dfdd48254c) | Jun 29, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| HP            | Pavilion g4                 | Notebook    | [d0c8c06219](https://linux-hardware.org/?probe=d0c8c06219) | Jun 24, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [30692c3fdb](https://linux-hardware.org/?probe=30692c3fdb) | Jun 23, 2022 |
| Fujitsu       | FMVS02003                   | Notebook    | [3536a9951f](https://linux-hardware.org/?probe=3536a9951f) | Jun 23, 2022 |
| Dell          | Precision M4500             | Notebook    | [e41b9f3386](https://linux-hardware.org/?probe=e41b9f3386) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [00a254b4ff](https://linux-hardware.org/?probe=00a254b4ff) | Jun 21, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [4ca3721cbb](https://linux-hardware.org/?probe=4ca3721cbb) | Jun 20, 2022 |
| MSI           | 2A9C                        | Desktop     | [73dd2172d3](https://linux-hardware.org/?probe=73dd2172d3) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [4d5fb8a789](https://linux-hardware.org/?probe=4d5fb8a789) | Jun 20, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [9f7b97f22f](https://linux-hardware.org/?probe=9f7b97f22f) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| AXIOO         | Mybook 14E                  | Notebook    | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [b71d801e61](https://linux-hardware.org/?probe=b71d801e61) | Jun 18, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [a6cc4351be](https://linux-hardware.org/?probe=a6cc4351be) | Jun 17, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [fe4f649d9b](https://linux-hardware.org/?probe=fe4f649d9b) | Jun 17, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [b131cd7e0d](https://linux-hardware.org/?probe=b131cd7e0d) | Jun 16, 2022 |
| Wearnes       | T1550-A1                    | Desktop     | [002ebf8c70](https://linux-hardware.org/?probe=002ebf8c70) | Jun 15, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| HP            | 2B43                        | Desktop     | [6f36772b0c](https://linux-hardware.org/?probe=6f36772b0c) | Jun 10, 2022 |
| Acer          | AO756                       | Notebook    | [008fa33f13](https://linux-hardware.org/?probe=008fa33f13) | Jun 09, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [a74cd897c5](https://linux-hardware.org/?probe=a74cd897c5) | Jun 09, 2022 |
| MSI           | Prestige 14 A11SC           | Notebook    | [ea39fa65a1](https://linux-hardware.org/?probe=ea39fa65a1) | Jun 09, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [bdb3bbe37f](https://linux-hardware.org/?probe=bdb3bbe37f) | Jun 07, 2022 |
| Lenovo        | Z41-70 80K5                 | Notebook    | [3419d2fd18](https://linux-hardware.org/?probe=3419d2fd18) | Jun 06, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5e4d9a126e](https://linux-hardware.org/?probe=5e4d9a126e) | Jun 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| MSI           | H81I                        | Desktop     | [6b4e34a35e](https://linux-hardware.org/?probe=6b4e34a35e) | Jun 01, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [1019de0d68](https://linux-hardware.org/?probe=1019de0d68) | Jun 01, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| ASRock        | A88M-G                      | Desktop     | [9b82b09acc](https://linux-hardware.org/?probe=9b82b09acc) | May 30, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [a1dd5003f5](https://linux-hardware.org/?probe=a1dd5003f5) | May 30, 2022 |
| AXIOO         | NEON HNM MODEL              | Notebook    | [0fbd1cf4af](https://linux-hardware.org/?probe=0fbd1cf4af) | May 30, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| Lenovo        | G400 20235                  | Notebook    | [351b94ec15](https://linux-hardware.org/?probe=351b94ec15) | May 25, 2022 |
| HP            | 1000                        | Notebook    | [e83bc1e8fe](https://linux-hardware.org/?probe=e83bc1e8fe) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [2e27b6fac9](https://linux-hardware.org/?probe=2e27b6fac9) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [b80588cbea](https://linux-hardware.org/?probe=b80588cbea) | May 21, 2022 |
| ASUSTek       | K43U                        | Notebook    | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| MSI           | Modern 14 B11MO             | Notebook    | [c3b01c8c1b](https://linux-hardware.org/?probe=c3b01c8c1b) | May 20, 2022 |
| ASRock        | A88M-G                      | Desktop     | [e2baae7114](https://linux-hardware.org/?probe=e2baae7114) | May 19, 2022 |
| ASUSTek       | K43U                        | Notebook    | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c5cdf9ba52](https://linux-hardware.org/?probe=c5cdf9ba52) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [cfba770336](https://linux-hardware.org/?probe=cfba770336) | May 17, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [c19acfde6f](https://linux-hardware.org/?probe=c19acfde6f) | May 17, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [e633129a51](https://linux-hardware.org/?probe=e633129a51) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [98b0999339](https://linux-hardware.org/?probe=98b0999339) | May 12, 2022 |
| Acer          | Aspire E5-476G              | Notebook    | [c4e0e740bb](https://linux-hardware.org/?probe=c4e0e740bb) | May 12, 2022 |
| Acer          | V1.24                       | Notebook    | [186531d4d8](https://linux-hardware.org/?probe=186531d4d8) | May 11, 2022 |
| Sony          | SVS13137PGB                 | Notebook    | [6dd2b49c52](https://linux-hardware.org/?probe=6dd2b49c52) | May 10, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [19345cd924](https://linux-hardware.org/?probe=19345cd924) | May 10, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [108b57a5a7](https://linux-hardware.org/?probe=108b57a5a7) | May 10, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [ec1fa8e360](https://linux-hardware.org/?probe=ec1fa8e360) | May 08, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [56cecf6472](https://linux-hardware.org/?probe=56cecf6472) | May 07, 2022 |
| MSI           | H55M-P33                    | Desktop     | [0f6b0dc134](https://linux-hardware.org/?probe=0f6b0dc134) | May 07, 2022 |
| Acer          | Aspire A514-54G             | Notebook    | [b4b52aad69](https://linux-hardware.org/?probe=b4b52aad69) | May 07, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [c0bfa1dddf](https://linux-hardware.org/?probe=c0bfa1dddf) | May 06, 2022 |
| Acer          | Aspire V5-431               | Notebook    | [04db0db85f](https://linux-hardware.org/?probe=04db0db85f) | May 05, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [4dcc86a60e](https://linux-hardware.org/?probe=4dcc86a60e) | May 03, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [db2efb40d4](https://linux-hardware.org/?probe=db2efb40d4) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [f93f8fcb35](https://linux-hardware.org/?probe=f93f8fcb35) | Apr 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [9f98b410f6](https://linux-hardware.org/?probe=9f98b410f6) | Apr 26, 2022 |
| Gigabyte      | M912                        | Notebook    | [fd0834889a](https://linux-hardware.org/?probe=fd0834889a) | Apr 25, 2022 |
| ASUSTek       | X450LCP                     | Notebook    | [a2ed4903be](https://linux-hardware.org/?probe=a2ed4903be) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [d52bc41f4c](https://linux-hardware.org/?probe=d52bc41f4c) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85b4ecf9d3](https://linux-hardware.org/?probe=85b4ecf9d3) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | Desktop     | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [345734b3fd](https://linux-hardware.org/?probe=345734b3fd) | Apr 07, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [eb44050489](https://linux-hardware.org/?probe=eb44050489) | Apr 07, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [cf17e2bba2](https://linux-hardware.org/?probe=cf17e2bba2) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ca7ee75e52](https://linux-hardware.org/?probe=ca7ee75e52) | Apr 01, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [c3651e4d3d](https://linux-hardware.org/?probe=c3651e4d3d) | Apr 01, 2022 |
| Dell          | Latitude E6230              | Notebook    | [c45161f6f3](https://linux-hardware.org/?probe=c45161f6f3) | Mar 31, 2022 |
| HP            | 3641h                       | Desktop     | [d50fc13ff0](https://linux-hardware.org/?probe=d50fc13ff0) | Mar 30, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [84625838c2](https://linux-hardware.org/?probe=84625838c2) | Mar 30, 2022 |
| Lenovo        | 36F2 SDK0Q55754 WIN 3273... | All in one  | [64bc773e5b](https://linux-hardware.org/?probe=64bc773e5b) | Mar 30, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Infinix       | INBook X1                   | Notebook    | [a06d137316](https://linux-hardware.org/?probe=a06d137316) | Mar 28, 2022 |
| Koloe         | X58                         | Desktop     | [8025987817](https://linux-hardware.org/?probe=8025987817) | Mar 27, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [46acaeb2db](https://linux-hardware.org/?probe=46acaeb2db) | Mar 27, 2022 |
| Dell          | Latitude E7240              | Notebook    | [02c34ca310](https://linux-hardware.org/?probe=02c34ca310) | Mar 25, 2022 |
| ASUSTek       | X455YA                      | Notebook    | [b0469d5342](https://linux-hardware.org/?probe=b0469d5342) | Mar 25, 2022 |
| Colorful T... | C.H110M-K D3 PLUS V20       | Desktop     | [191dfebc88](https://linux-hardware.org/?probe=191dfebc88) | Mar 23, 2022 |
| Sony          | VPCSB35FG                   | Notebook    | [79d0465072](https://linux-hardware.org/?probe=79d0465072) | Mar 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3f4f125a64](https://linux-hardware.org/?probe=3f4f125a64) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [1b7f98b34d](https://linux-hardware.org/?probe=1b7f98b34d) | Mar 23, 2022 |
| ASUSTek       | X456UQK                     | Notebook    | [863693cc0a](https://linux-hardware.org/?probe=863693cc0a) | Mar 23, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [7977e70f86](https://linux-hardware.org/?probe=7977e70f86) | Mar 22, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [f0047d02ea](https://linux-hardware.org/?probe=f0047d02ea) | Mar 22, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [dd7543bdb3](https://linux-hardware.org/?probe=dd7543bdb3) | Mar 21, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [d98411620e](https://linux-hardware.org/?probe=d98411620e) | Mar 21, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [08985cbe9e](https://linux-hardware.org/?probe=08985cbe9e) | Mar 21, 2022 |
| Intel         | H55                         | Desktop     | [baff4758b7](https://linux-hardware.org/?probe=baff4758b7) | Mar 21, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [991793e09e](https://linux-hardware.org/?probe=991793e09e) | Mar 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8793c924fe](https://linux-hardware.org/?probe=8793c924fe) | Mar 19, 2022 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [222cbe9b4e](https://linux-hardware.org/?probe=222cbe9b4e) | Mar 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [fa74626a55](https://linux-hardware.org/?probe=fa74626a55) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| ASUSTek       | X441NA                      | Notebook    | [b7cf53ebcc](https://linux-hardware.org/?probe=b7cf53ebcc) | Mar 15, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c334e9a1f6](https://linux-hardware.org/?probe=c334e9a1f6) | Mar 14, 2022 |
| HP            | Notebook                    | Notebook    | [6ae78b432d](https://linux-hardware.org/?probe=6ae78b432d) | Mar 12, 2022 |
| ZYREX COMP... | TACTICAL                    | Desktop     | [73a4735670](https://linux-hardware.org/?probe=73a4735670) | Mar 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f2a82ddf3b](https://linux-hardware.org/?probe=f2a82ddf3b) | Mar 11, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [5e43e1dd7b](https://linux-hardware.org/?probe=5e43e1dd7b) | Mar 11, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [ed4db5233e](https://linux-hardware.org/?probe=ed4db5233e) | Mar 10, 2022 |
| ASUSTek       | X450EA                      | Notebook    | [a7394d72a0](https://linux-hardware.org/?probe=a7394d72a0) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [2f6380807c](https://linux-hardware.org/?probe=2f6380807c) | Mar 09, 2022 |
| MSI           | 2A9C                        | Desktop     | [4702507c0f](https://linux-hardware.org/?probe=4702507c0f) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3ff8cf8ed0](https://linux-hardware.org/?probe=3ff8cf8ed0) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| Sony          | VPCSB35FG                   | Notebook    | [b8a266ddc0](https://linux-hardware.org/?probe=b8a266ddc0) | Mar 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS35500    | Notebook    | [af08ab87c5](https://linux-hardware.org/?probe=af08ab87c5) | Mar 07, 2022 |
| Toshiba       | PORTEGE R835                | Notebook    | [67e8021c81](https://linux-hardware.org/?probe=67e8021c81) | Mar 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7d5945f3d](https://linux-hardware.org/?probe=e7d5945f3d) | Mar 05, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [28f40df81d](https://linux-hardware.org/?probe=28f40df81d) | Mar 04, 2022 |
| ASUSTek       | UL20A                       | Notebook    | [c4efddb6b4](https://linux-hardware.org/?probe=c4efddb6b4) | Mar 02, 2022 |
| Fujitsu       | Unknown                     | Notebook    | [bc81b988ce](https://linux-hardware.org/?probe=bc81b988ce) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [621999b245](https://linux-hardware.org/?probe=621999b245) | Feb 24, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [3b3c38ec7d](https://linux-hardware.org/?probe=3b3c38ec7d) | Feb 24, 2022 |
| Acer          | Aspire M3970                | Desktop     | [ba6546f689](https://linux-hardware.org/?probe=ba6546f689) | Feb 24, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [cdc3afd163](https://linux-hardware.org/?probe=cdc3afd163) | Feb 24, 2022 |
| Dell          | 0GM819                      | Desktop     | [28011d003e](https://linux-hardware.org/?probe=28011d003e) | Feb 23, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [5ba37db2b4](https://linux-hardware.org/?probe=5ba37db2b4) | Feb 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [eba3609129](https://linux-hardware.org/?probe=eba3609129) | Feb 19, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | Notebook    | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| Acer          | One Z1402                   | Notebook    | [8746e0e3e7](https://linux-hardware.org/?probe=8746e0e3e7) | Feb 18, 2022 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1582806778](https://linux-hardware.org/?probe=1582806778) | Feb 17, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [b2efca795b](https://linux-hardware.org/?probe=b2efca795b) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [e3dfc424ca](https://linux-hardware.org/?probe=e3dfc424ca) | Feb 16, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [1e54431036](https://linux-hardware.org/?probe=1e54431036) | Feb 15, 2022 |
| Fujitsu       | FMVNA1SE                    | Notebook    | [e2cd0bdcb5](https://linux-hardware.org/?probe=e2cd0bdcb5) | Feb 14, 2022 |
| Khadas        | VIM2                        | Soc         | [c3e2b43e74](https://linux-hardware.org/?probe=c3e2b43e74) | Feb 13, 2022 |
| ECS           | A58F2P-M4                   | Desktop     | [bae5185ab0](https://linux-hardware.org/?probe=bae5185ab0) | Feb 13, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [3a6bb92957](https://linux-hardware.org/?probe=3a6bb92957) | Feb 13, 2022 |
| Toshiba       | Satellite C840              | Notebook    | [cb53c43003](https://linux-hardware.org/?probe=cb53c43003) | Feb 13, 2022 |
| Lenovo        | IdeaPad S205 Brazos         | Notebook    | [402bdafb5f](https://linux-hardware.org/?probe=402bdafb5f) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [46d98c991e](https://linux-hardware.org/?probe=46d98c991e) | Feb 12, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [5d4b14e3e0](https://linux-hardware.org/?probe=5d4b14e3e0) | Feb 12, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [eea0ec2b64](https://linux-hardware.org/?probe=eea0ec2b64) | Feb 12, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [276233dff5](https://linux-hardware.org/?probe=276233dff5) | Feb 11, 2022 |
| Biostar       | A68MHE                      | Desktop     | [d66f9ea911](https://linux-hardware.org/?probe=d66f9ea911) | Feb 10, 2022 |
| Biostar       | A68MHE                      | Desktop     | [edc710a49e](https://linux-hardware.org/?probe=edc710a49e) | Feb 10, 2022 |
| Toshiba       | Satellite C800D             | Notebook    | [5cdc03cbdf](https://linux-hardware.org/?probe=5cdc03cbdf) | Feb 10, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [54e246f496](https://linux-hardware.org/?probe=54e246f496) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [aa037a1c8c](https://linux-hardware.org/?probe=aa037a1c8c) | Feb 09, 2022 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [0de3e1022e](https://linux-hardware.org/?probe=0de3e1022e) | Feb 09, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [5e0e5de165](https://linux-hardware.org/?probe=5e0e5de165) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [aaceb070e8](https://linux-hardware.org/?probe=aaceb070e8) | Feb 07, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [324512f303](https://linux-hardware.org/?probe=324512f303) | Feb 06, 2022 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [f9eb52038d](https://linux-hardware.org/?probe=f9eb52038d) | Feb 01, 2022 |
| Dell          | Inspiron 5480               | Notebook    | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | Notebook    | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [774625ff90](https://linux-hardware.org/?probe=774625ff90) | Jan 24, 2022 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [e7c5bda932](https://linux-hardware.org/?probe=e7c5bda932) | Jan 24, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [3f431523c1](https://linux-hardware.org/?probe=3f431523c1) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Sony          | SVE14A15FGB                 | Notebook    | [c35af68d7b](https://linux-hardware.org/?probe=c35af68d7b) | Jan 21, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [a7c6bed4e1](https://linux-hardware.org/?probe=a7c6bed4e1) | Jan 21, 2022 |
| Sony          | SVD13213SGW                 | Notebook    | [ee9e63ab7c](https://linux-hardware.org/?probe=ee9e63ab7c) | Jan 21, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [e4791d09ec](https://linux-hardware.org/?probe=e4791d09ec) | Jan 20, 2022 |
| Lenovo        | IdeaPad 305-14IBD 80R1      | Notebook    | [f963f78bc6](https://linux-hardware.org/?probe=f963f78bc6) | Jan 20, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [ae605d8a23](https://linux-hardware.org/?probe=ae605d8a23) | Jan 18, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c021e3bb40](https://linux-hardware.org/?probe=c021e3bb40) | Jan 18, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [bf81e9a289](https://linux-hardware.org/?probe=bf81e9a289) | Jan 17, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [6df479c161](https://linux-hardware.org/?probe=6df479c161) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | Notebook    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Lenovo        | G400s 20244                 | Notebook    | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Dell          | Vostro 5581                 | Notebook    | [45f89f3b39](https://linux-hardware.org/?probe=45f89f3b39) | Jan 13, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [4822adcbc3](https://linux-hardware.org/?probe=4822adcbc3) | Jan 09, 2022 |
| MSI           | GL65 9SC                    | Notebook    | [24c204f7cf](https://linux-hardware.org/?probe=24c204f7cf) | Jan 09, 2022 |
| Dell          | Latitude E7250              | Notebook    | [e586dba516](https://linux-hardware.org/?probe=e586dba516) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [2268237364](https://linux-hardware.org/?probe=2268237364) | Jan 08, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [ea82b6b417](https://linux-hardware.org/?probe=ea82b6b417) | Jan 08, 2022 |
| ASUSTek       | N43SL                       | Notebook    | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| Lenovo        | U310                        | Notebook    | [47b64f9b71](https://linux-hardware.org/?probe=47b64f9b71) | Jan 04, 2022 |
| ASUSTek       | TP300LD                     | Notebook    | [2048e4ff56](https://linux-hardware.org/?probe=2048e4ff56) | Jan 04, 2022 |
| Biostar       | H81MHV3                     | Desktop     | [897c4f4fa5](https://linux-hardware.org/?probe=897c4f4fa5) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [954bd9f15e](https://linux-hardware.org/?probe=954bd9f15e) | Jan 03, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [5a0df8b1d8](https://linux-hardware.org/?probe=5a0df8b1d8) | Jan 03, 2022 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [af3d4f8c4d](https://linux-hardware.org/?probe=af3d4f8c4d) | Jan 02, 2022 |
| Acer          | Aspire 4720Z                | Notebook    | [1928762a58](https://linux-hardware.org/?probe=1928762a58) | Jan 02, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [ad8cdd464b](https://linux-hardware.org/?probe=ad8cdd464b) | Jan 01, 2022 |
| ASUSTek       | TP300LD                     | Notebook    | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [2956508483](https://linux-hardware.org/?probe=2956508483) | Dec 31, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| HP            | Pavilion 14                 | Notebook    | [b212043e80](https://linux-hardware.org/?probe=b212043e80) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [b5cd12bc15](https://linux-hardware.org/?probe=b5cd12bc15) | Dec 24, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [25ca0533b3](https://linux-hardware.org/?probe=25ca0533b3) | Dec 24, 2021 |
| Fujitsu       | FMVNA7BEC                   | Notebook    | [5a7719cad2](https://linux-hardware.org/?probe=5a7719cad2) | Dec 23, 2021 |
| Acer          | Aspire E1-471G              | Notebook    | [93b181f3fd](https://linux-hardware.org/?probe=93b181f3fd) | Dec 21, 2021 |
| Dell          | Latitude E5400              | Notebook    | [ea58337ba8](https://linux-hardware.org/?probe=ea58337ba8) | Dec 20, 2021 |
| Toshiba       | Dakar10FW8                  | Notebook    | [937d3de436](https://linux-hardware.org/?probe=937d3de436) | Dec 19, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [f279fb7b6f](https://linux-hardware.org/?probe=f279fb7b6f) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [635ec3d5d2](https://linux-hardware.org/?probe=635ec3d5d2) | Dec 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ee7ae7b860](https://linux-hardware.org/?probe=ee7ae7b860) | Dec 06, 2021 |
| ASUSTek       | UX360UAK                    | Convertible | [76fcef9590](https://linux-hardware.org/?probe=76fcef9590) | Dec 05, 2021 |
| Foxconn       | 17A0                        | Desktop     | [f3b593c1cf](https://linux-hardware.org/?probe=f3b593c1cf) | Dec 04, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c81483b4db](https://linux-hardware.org/?probe=c81483b4db) | Dec 04, 2021 |
| Samsung       | 700T                        | Notebook    | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [473e7afa6d](https://linux-hardware.org/?probe=473e7afa6d) | Dec 01, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [8fcb88c027](https://linux-hardware.org/?probe=8fcb88c027) | Nov 30, 2021 |
| Foxconn       | 17A0                        | Desktop     | [9683f8f23c](https://linux-hardware.org/?probe=9683f8f23c) | Nov 29, 2021 |
| Lenovo        | ThinkCentre M58p 6137BG5    | Desktop     | [f5f0997eca](https://linux-hardware.org/?probe=f5f0997eca) | Nov 28, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [faf9c22988](https://linux-hardware.org/?probe=faf9c22988) | Nov 26, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [8cffa892b2](https://linux-hardware.org/?probe=8cffa892b2) | Nov 26, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [7376dc0d58](https://linux-hardware.org/?probe=7376dc0d58) | Nov 25, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [d020b5f5c5](https://linux-hardware.org/?probe=d020b5f5c5) | Nov 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a87f01aa8a](https://linux-hardware.org/?probe=a87f01aa8a) | Nov 25, 2021 |
| HP            | EliteBook x360 830 G7 No... | Convertible | [4c596fa022](https://linux-hardware.org/?probe=4c596fa022) | Nov 24, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [09cc50e9eb](https://linux-hardware.org/?probe=09cc50e9eb) | Nov 23, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [34d8f7fdbb](https://linux-hardware.org/?probe=34d8f7fdbb) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [4a655e0c04](https://linux-hardware.org/?probe=4a655e0c04) | Nov 22, 2021 |
| Acer          | Swift SF514-53T             | Notebook    | [dbca729f8c](https://linux-hardware.org/?probe=dbca729f8c) | Nov 20, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [e84acf2bba](https://linux-hardware.org/?probe=e84acf2bba) | Nov 19, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [6d67037961](https://linux-hardware.org/?probe=6d67037961) | Nov 16, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | Notebook    | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Dell          | Vostro 3400                 | Notebook    | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| Foxconn       | 17A0                        | Desktop     | [ed1128211e](https://linux-hardware.org/?probe=ed1128211e) | Nov 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Notebook      | P870DM                      | Notebook    | [7681edf3ee](https://linux-hardware.org/?probe=7681edf3ee) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [fa2cb4cfff](https://linux-hardware.org/?probe=fa2cb4cfff) | Nov 12, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [53cf9a7e19](https://linux-hardware.org/?probe=53cf9a7e19) | Nov 12, 2021 |
| Acer          | Swift SF514-52T             | Notebook    | [020a93edbc](https://linux-hardware.org/?probe=020a93edbc) | Nov 10, 2021 |
| MSI           | GL62M 7RDX                  | Notebook    | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [b27a794243](https://linux-hardware.org/?probe=b27a794243) | Nov 09, 2021 |
| Foxconn       | 17A0                        | Desktop     | [17ff85bc35](https://linux-hardware.org/?probe=17ff85bc35) | Nov 09, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| HP            | Notebook                    | Notebook    | [9334c94844](https://linux-hardware.org/?probe=9334c94844) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | Notebook    | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [a6cafee332](https://linux-hardware.org/?probe=a6cafee332) | Nov 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3a0bd3fa08](https://linux-hardware.org/?probe=3a0bd3fa08) | Nov 01, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| MSI           | B350M MORTAR                | Desktop     | [bab0e06723](https://linux-hardware.org/?probe=bab0e06723) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | Desktop     | [4fa9117126](https://linux-hardware.org/?probe=4fa9117126) | Oct 29, 2021 |
| MSI           | A520M-A PRO                 | Desktop     | [e4fc3665f7](https://linux-hardware.org/?probe=e4fc3665f7) | Oct 29, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [93b56b7543](https://linux-hardware.org/?probe=93b56b7543) | Oct 29, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0cdc6e9d84](https://linux-hardware.org/?probe=0cdc6e9d84) | Oct 28, 2021 |
| MSI           | B350M MORTAR                | Desktop     | [e94404d654](https://linux-hardware.org/?probe=e94404d654) | Oct 26, 2021 |
| Dell          | Latitude E6440              | Notebook    | [00e8b6e3fd](https://linux-hardware.org/?probe=00e8b6e3fd) | Oct 24, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [afa573d049](https://linux-hardware.org/?probe=afa573d049) | Oct 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [78738c3586](https://linux-hardware.org/?probe=78738c3586) | Oct 22, 2021 |
| Dell          | G7 7588                     | Notebook    | [af1479f2fe](https://linux-hardware.org/?probe=af1479f2fe) | Oct 20, 2021 |
| Dell          | G7 7588                     | Notebook    | [0464fb8af6](https://linux-hardware.org/?probe=0464fb8af6) | Oct 20, 2021 |
| Pegatron      | 2AD4                        | Desktop     | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| HPE           | ProLiant DL360 Gen10        | Server      | [7ab4f05613](https://linux-hardware.org/?probe=7ab4f05613) | Oct 18, 2021 |
| Dell          | Inspiron 1440               | Notebook    | [9e9967a3fa](https://linux-hardware.org/?probe=9e9967a3fa) | Oct 17, 2021 |
| Acer          | Aspire 4738Z                | Notebook    | [8962990035](https://linux-hardware.org/?probe=8962990035) | Oct 16, 2021 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [ee1862fa4f](https://linux-hardware.org/?probe=ee1862fa4f) | Oct 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [9d1380f4a8](https://linux-hardware.org/?probe=9d1380f4a8) | Oct 15, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| Dell          | 0773VG A01                  | Desktop     | [84fc704eaa](https://linux-hardware.org/?probe=84fc704eaa) | Oct 09, 2021 |
| ASUSTek       | K43SV                       | Notebook    | [6c0858f414](https://linux-hardware.org/?probe=6c0858f414) | Oct 08, 2021 |
| ASUSTek       | K43SV                       | Notebook    | [cff7419d9e](https://linux-hardware.org/?probe=cff7419d9e) | Oct 08, 2021 |
| Lenovo        | H310                        | Desktop     | [ce491df5a4](https://linux-hardware.org/?probe=ce491df5a4) | Oct 06, 2021 |
| HP            | Pavilion 14                 | Notebook    | [0c0ee7fe52](https://linux-hardware.org/?probe=0c0ee7fe52) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5856720999](https://linux-hardware.org/?probe=5856720999) | Oct 04, 2021 |
| ASUSTek       | X441BA                      | Notebook    | [ae6206875f](https://linux-hardware.org/?probe=ae6206875f) | Oct 03, 2021 |
| ASUSTek       | X441BA                      | Notebook    | [692a1a1a57](https://linux-hardware.org/?probe=692a1a1a57) | Oct 03, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [1c4d130d6a](https://linux-hardware.org/?probe=1c4d130d6a) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [4038d4a0a6](https://linux-hardware.org/?probe=4038d4a0a6) | Sep 29, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [5854a1e114](https://linux-hardware.org/?probe=5854a1e114) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [410a604bab](https://linux-hardware.org/?probe=410a604bab) | Sep 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1f251e5ba2](https://linux-hardware.org/?probe=1f251e5ba2) | Sep 29, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [28d13c49b3](https://linux-hardware.org/?probe=28d13c49b3) | Sep 28, 2021 |
| HP            | EliteBook 8440p (SH923UC... | Notebook    | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [f8fd88bca1](https://linux-hardware.org/?probe=f8fd88bca1) | Sep 26, 2021 |
| Acer          | Swift SFX14-41G             | Notebook    | [cb763824f9](https://linux-hardware.org/?probe=cb763824f9) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | Notebook    | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c5758f5a05](https://linux-hardware.org/?probe=c5758f5a05) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Foxconn       | 17A0                        | Desktop     | [06052023d3](https://linux-hardware.org/?probe=06052023d3) | Sep 14, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e84546c757](https://linux-hardware.org/?probe=e84546c757) | Sep 14, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [2cc8dabf64](https://linux-hardware.org/?probe=2cc8dabf64) | Sep 11, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [5d60817fb5](https://linux-hardware.org/?probe=5d60817fb5) | Sep 11, 2021 |
| HP            | Compaq Presario CQ40        | Notebook    | [62284df376](https://linux-hardware.org/?probe=62284df376) | Sep 10, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| HP            | Convertible x360 11-ab1X... | Convertible | [5863fa858f](https://linux-hardware.org/?probe=5863fa858f) | Sep 07, 2021 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a629879646](https://linux-hardware.org/?probe=a629879646) | Sep 06, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [82904dfc03](https://linux-hardware.org/?probe=82904dfc03) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | Notebook    | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | 14                          | Notebook    | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [541ab60180](https://linux-hardware.org/?probe=541ab60180) | Sep 04, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [ddd7b7b87f](https://linux-hardware.org/?probe=ddd7b7b87f) | Sep 02, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [16c3c01bcd](https://linux-hardware.org/?probe=16c3c01bcd) | Sep 02, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0bfcbeeab5](https://linux-hardware.org/?probe=0bfcbeeab5) | Sep 02, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [808ff28683](https://linux-hardware.org/?probe=808ff28683) | Aug 31, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [9ab0b9612a](https://linux-hardware.org/?probe=9ab0b9612a) | Aug 30, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [924e556648](https://linux-hardware.org/?probe=924e556648) | Aug 28, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [246709cb9b](https://linux-hardware.org/?probe=246709cb9b) | Aug 27, 2021 |
| ASUSTek       | GL553VD                     | Notebook    | [d6a7f7807d](https://linux-hardware.org/?probe=d6a7f7807d) | Aug 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [6e6129ddbe](https://linux-hardware.org/?probe=6e6129ddbe) | Aug 26, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [83393788bf](https://linux-hardware.org/?probe=83393788bf) | Aug 26, 2021 |
| HP            | ProBook 4430s               | Notebook    | [e764612d91](https://linux-hardware.org/?probe=e764612d91) | Aug 25, 2021 |
| Gigabyte      | EP45-DS3                    | Desktop     | [a2a6e3ee32](https://linux-hardware.org/?probe=a2a6e3ee32) | Aug 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [49aac2eefe](https://linux-hardware.org/?probe=49aac2eefe) | Aug 24, 2021 |
| Acer          | Aspire V3-371               | Notebook    | [d34df8e36e](https://linux-hardware.org/?probe=d34df8e36e) | Aug 23, 2021 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [781fc26452](https://linux-hardware.org/?probe=781fc26452) | Aug 23, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [b57e843f46](https://linux-hardware.org/?probe=b57e843f46) | Aug 22, 2021 |
| ECS           | A960M-MV                    | Desktop     | [684f50eff8](https://linux-hardware.org/?probe=684f50eff8) | Aug 18, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [34d2f87751](https://linux-hardware.org/?probe=34d2f87751) | Aug 18, 2021 |
| HP            | 2B3C                        | Desktop     | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| Fujitsu       | FMVNA6HG                    | Notebook    | [3af7eec32c](https://linux-hardware.org/?probe=3af7eec32c) | Aug 16, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [2aa00ea596](https://linux-hardware.org/?probe=2aa00ea596) | Aug 15, 2021 |
| Toshiba       | Satellite R630              | Notebook    | [b2b7f07b7a](https://linux-hardware.org/?probe=b2b7f07b7a) | Aug 12, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [2da83ae7b5](https://linux-hardware.org/?probe=2da83ae7b5) | Aug 12, 2021 |
| HP            | ENVY Notebook               | Notebook    | [f2dea0236d](https://linux-hardware.org/?probe=f2dea0236d) | Aug 11, 2021 |
| HP            | ENVY Notebook               | Notebook    | [ce3be0798b](https://linux-hardware.org/?probe=ce3be0798b) | Aug 11, 2021 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [557e4010c3](https://linux-hardware.org/?probe=557e4010c3) | Aug 11, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3d8ebc06f6](https://linux-hardware.org/?probe=3d8ebc06f6) | Aug 10, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [bb3eb06270](https://linux-hardware.org/?probe=bb3eb06270) | Aug 09, 2021 |
| Acer          | Nitro AN515-56              | Notebook    | [867c7e2bb4](https://linux-hardware.org/?probe=867c7e2bb4) | Aug 09, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [a9947e6264](https://linux-hardware.org/?probe=a9947e6264) | Aug 08, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6d691b88f0](https://linux-hardware.org/?probe=6d691b88f0) | Aug 08, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [16f9fcdeed](https://linux-hardware.org/?probe=16f9fcdeed) | Aug 08, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [4f141cc864](https://linux-hardware.org/?probe=4f141cc864) | Aug 07, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [31e6bda7a8](https://linux-hardware.org/?probe=31e6bda7a8) | Aug 07, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [346da0d23a](https://linux-hardware.org/?probe=346da0d23a) | Aug 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6a935239e8](https://linux-hardware.org/?probe=6a935239e8) | Aug 05, 2021 |
| ASUSTek       | X455YA                      | Notebook    | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [506b637bd3](https://linux-hardware.org/?probe=506b637bd3) | Aug 05, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [26d0a4788c](https://linux-hardware.org/?probe=26d0a4788c) | Aug 03, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [47a05531da](https://linux-hardware.org/?probe=47a05531da) | Aug 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1a72340ff4](https://linux-hardware.org/?probe=1a72340ff4) | Aug 01, 2021 |
| Lenovo        | G400s 20244                 | Notebook    | [43fe80380d](https://linux-hardware.org/?probe=43fe80380d) | Aug 01, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | Notebook    | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [597f4ff063](https://linux-hardware.org/?probe=597f4ff063) | Jul 29, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [b4a1e99fc0](https://linux-hardware.org/?probe=b4a1e99fc0) | Jul 28, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [cc1c71078c](https://linux-hardware.org/?probe=cc1c71078c) | Jul 28, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [20dc9f0df4](https://linux-hardware.org/?probe=20dc9f0df4) | Jul 27, 2021 |
| Dell          | Inspiron 3458               | Notebook    | [43d4236000](https://linux-hardware.org/?probe=43d4236000) | Jul 27, 2021 |
| Dell          | Vostro 14-3468              | Notebook    | [c222cecae0](https://linux-hardware.org/?probe=c222cecae0) | Jul 27, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [85fddcd068](https://linux-hardware.org/?probe=85fddcd068) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [d59705a499](https://linux-hardware.org/?probe=d59705a499) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad X220 4291G75       | Notebook    | [fc0c3340bd](https://linux-hardware.org/?probe=fc0c3340bd) | Jul 25, 2021 |
| Acer          | Veriton L4630G V:1.0        | Desktop     | [c486fbf03f](https://linux-hardware.org/?probe=c486fbf03f) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Toshiba       | PORTEGE M800                | Notebook    | [6de34f58af](https://linux-hardware.org/?probe=6de34f58af) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c989b48f08](https://linux-hardware.org/?probe=c989b48f08) | Jul 24, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [fec68f6675](https://linux-hardware.org/?probe=fec68f6675) | Jul 23, 2021 |
| ECS           | G41T-M12                    | Desktop     | [bc6dbc46b6](https://linux-hardware.org/?probe=bc6dbc46b6) | Jul 23, 2021 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [a8970607e0](https://linux-hardware.org/?probe=a8970607e0) | Jul 23, 2021 |
| Biostar       | H61MH                       | Desktop     | [adca68749a](https://linux-hardware.org/?probe=adca68749a) | Jul 23, 2021 |
| Biostar       | H61MH                       | Desktop     | [2c690e433f](https://linux-hardware.org/?probe=2c690e433f) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Acer          | Aspire V5-431               | Notebook    | [0616ef50a5](https://linux-hardware.org/?probe=0616ef50a5) | Jul 22, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [7f0ce9114c](https://linux-hardware.org/?probe=7f0ce9114c) | Jul 21, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [22a976ce11](https://linux-hardware.org/?probe=22a976ce11) | Jul 21, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c6b76cb1f9](https://linux-hardware.org/?probe=c6b76cb1f9) | Jul 21, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [714ce6dfc9](https://linux-hardware.org/?probe=714ce6dfc9) | Jul 19, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [e1d1356c93](https://linux-hardware.org/?probe=e1d1356c93) | Jul 19, 2021 |
| Acer          | Aspire V5-431               | Notebook    | [e0519d6c32](https://linux-hardware.org/?probe=e0519d6c32) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [d3561fadd3](https://linux-hardware.org/?probe=d3561fadd3) | Jul 18, 2021 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6cc56f596f](https://linux-hardware.org/?probe=6cc56f596f) | Jul 17, 2021 |
| Lenovo        | ThinkPad X250 20CLA200ID    | Notebook    | [28c05ab175](https://linux-hardware.org/?probe=28c05ab175) | Jul 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [1d1680d9c3](https://linux-hardware.org/?probe=1d1680d9c3) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4e75379022](https://linux-hardware.org/?probe=4e75379022) | Jul 16, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [eea8e3b740](https://linux-hardware.org/?probe=eea8e3b740) | Jul 14, 2021 |
| Dell          | 0YXT71 A03                  | Desktop     | [e363457394](https://linux-hardware.org/?probe=e363457394) | Jul 13, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | Desktop     | [533da05156](https://linux-hardware.org/?probe=533da05156) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [e336800a84](https://linux-hardware.org/?probe=e336800a84) | Jul 10, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [bdce45de75](https://linux-hardware.org/?probe=bdce45de75) | Jul 10, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9765ba93ab](https://linux-hardware.org/?probe=9765ba93ab) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [3e43acf8af](https://linux-hardware.org/?probe=3e43acf8af) | Jul 08, 2021 |
| Lenovo        | ThinkPad T430 2349SU6       | Notebook    | [9cd74fc6d1](https://linux-hardware.org/?probe=9cd74fc6d1) | Jul 08, 2021 |
| Lenovo        | ThinkPad X61 7676A12        | Notebook    | [196e6c6ec4](https://linux-hardware.org/?probe=196e6c6ec4) | Jul 08, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [064817cd28](https://linux-hardware.org/?probe=064817cd28) | Jul 05, 2021 |
| ASUSTek       | K84L                        | Notebook    | [01c9e0cbe1](https://linux-hardware.org/?probe=01c9e0cbe1) | Jul 03, 2021 |
| Acer          | Aspire A515-45              | Notebook    | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c980ba6ae7](https://linux-hardware.org/?probe=c980ba6ae7) | Jul 02, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [67c143c435](https://linux-hardware.org/?probe=67c143c435) | Jul 01, 2021 |
| Dell          | Latitude E5410              | Notebook    | [b047bdb721](https://linux-hardware.org/?probe=b047bdb721) | Jun 25, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [16a063ab28](https://linux-hardware.org/?probe=16a063ab28) | Jun 24, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e135f49903](https://linux-hardware.org/?probe=e135f49903) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [0d6df01751](https://linux-hardware.org/?probe=0d6df01751) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| MSI           | 870A-G54                    | Desktop     | [b1b8e74ea3](https://linux-hardware.org/?probe=b1b8e74ea3) | Jun 16, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [c1c0f815dc](https://linux-hardware.org/?probe=c1c0f815dc) | Jun 15, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [7572d1aea9](https://linux-hardware.org/?probe=7572d1aea9) | Jun 13, 2021 |
| Biostar       | TA870+                      | Desktop     | [c86568a140](https://linux-hardware.org/?probe=c86568a140) | Jun 09, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [a3cef73da9](https://linux-hardware.org/?probe=a3cef73da9) | Jun 09, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | Desktop     | [414008f0a3](https://linux-hardware.org/?probe=414008f0a3) | Jun 08, 2021 |
| Lenovo        | 3102 SDK0K13455 WIN 3273... | Desktop     | [744392b18f](https://linux-hardware.org/?probe=744392b18f) | Jun 08, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [9551aa9271](https://linux-hardware.org/?probe=9551aa9271) | Jun 06, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [6d45501f90](https://linux-hardware.org/?probe=6d45501f90) | Jun 05, 2021 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [8af935f813](https://linux-hardware.org/?probe=8af935f813) | Jun 02, 2021 |
| HP            | 85A2                        | All in one  | [f0691e6eda](https://linux-hardware.org/?probe=f0691e6eda) | Jun 02, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [0a074f7196](https://linux-hardware.org/?probe=0a074f7196) | Jun 02, 2021 |
| HP            | 1906                        | Desktop     | [bf20783dee](https://linux-hardware.org/?probe=bf20783dee) | Jun 02, 2021 |
| Acer          | Aspire E5-476G              | Notebook    | [ecbaba7315](https://linux-hardware.org/?probe=ecbaba7315) | May 31, 2021 |
| ECS           | G41T-M12                    | Desktop     | [086ce490f7](https://linux-hardware.org/?probe=086ce490f7) | May 29, 2021 |
| ECS           | A55F2-M4                    | Desktop     | [b08197df02](https://linux-hardware.org/?probe=b08197df02) | May 29, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [3e6a2f7b59](https://linux-hardware.org/?probe=3e6a2f7b59) | May 27, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Dell          | Latitude E6410              | Notebook    | [7e35c63842](https://linux-hardware.org/?probe=7e35c63842) | May 26, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [7ca3035a20](https://linux-hardware.org/?probe=7ca3035a20) | May 26, 2021 |
| Gigabyte      | P85-D3                      | Desktop     | [a85613d8a6](https://linux-hardware.org/?probe=a85613d8a6) | May 24, 2021 |
| ECS           | H61H2-M2                    | Desktop     | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [c75161deac](https://linux-hardware.org/?probe=c75161deac) | May 20, 2021 |
| ASUSTek       | X550JX                      | Notebook    | [c837a795d7](https://linux-hardware.org/?probe=c837a795d7) | May 19, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [8f39af876c](https://linux-hardware.org/?probe=8f39af876c) | May 19, 2021 |
| Acer          | Okinawa                     | Notebook    | [9579ede8a9](https://linux-hardware.org/?probe=9579ede8a9) | May 19, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | Notebook    | [1ad049bf43](https://linux-hardware.org/?probe=1ad049bf43) | May 17, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [b26958098c](https://linux-hardware.org/?probe=b26958098c) | May 14, 2021 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [80070c566e](https://linux-hardware.org/?probe=80070c566e) | May 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [f900105a8a](https://linux-hardware.org/?probe=f900105a8a) | May 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [9a69a064a2](https://linux-hardware.org/?probe=9a69a064a2) | May 08, 2021 |
| Acer          | Veriton M2611 v1.0          | Desktop     | [82b2ea1868](https://linux-hardware.org/?probe=82b2ea1868) | May 06, 2021 |
| Acer          | Veriton M2611 v1.0          | Desktop     | [218de62b27](https://linux-hardware.org/?probe=218de62b27) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [0d732d9421](https://linux-hardware.org/?probe=0d732d9421) | May 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [327d214403](https://linux-hardware.org/?probe=327d214403) | May 04, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0beb84ac05](https://linux-hardware.org/?probe=0beb84ac05) | Apr 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2fddce1bd1](https://linux-hardware.org/?probe=2fddce1bd1) | Apr 29, 2021 |
| ASUSTek       | X453SA                      | Notebook    | [e72a666c50](https://linux-hardware.org/?probe=e72a666c50) | Apr 28, 2021 |
| ECS           | 945GCT-M2                   | Desktop     | [3f73514b16](https://linux-hardware.org/?probe=3f73514b16) | Apr 26, 2021 |
| ECS           | 945GCT-M2                   | Desktop     | [289b6cba53](https://linux-hardware.org/?probe=289b6cba53) | Apr 25, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [dcfd3e0bb5](https://linux-hardware.org/?probe=dcfd3e0bb5) | Apr 24, 2021 |
| Acer          | Aspire 4750                 | Notebook    | [5b1db085fc](https://linux-hardware.org/?probe=5b1db085fc) | Apr 24, 2021 |
| Dell          | Latitude 5400               | Notebook    | [a2fb8a380a](https://linux-hardware.org/?probe=a2fb8a380a) | Apr 23, 2021 |
| Dell          | Latitude 5400               | Notebook    | [e4a0edd922](https://linux-hardware.org/?probe=e4a0edd922) | Apr 23, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [ca62d8f11b](https://linux-hardware.org/?probe=ca62d8f11b) | Apr 21, 2021 |
| MSI           | Z97-G43 GAMING              | Desktop     | [f71c55764e](https://linux-hardware.org/?probe=f71c55764e) | Apr 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [2352caa9cf](https://linux-hardware.org/?probe=2352caa9cf) | Apr 19, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [47d0215e94](https://linux-hardware.org/?probe=47d0215e94) | Apr 17, 2021 |
| Lenovo        | ThinkCentre A70 7099S3A     | Desktop     | [2fd4915fe8](https://linux-hardware.org/?probe=2fd4915fe8) | Apr 16, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [fde9376452](https://linux-hardware.org/?probe=fde9376452) | Apr 16, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [9f50b41201](https://linux-hardware.org/?probe=9f50b41201) | Apr 16, 2021 |
| ASUSTek       | X441UV                      | Notebook    | [8ee5e69c11](https://linux-hardware.org/?probe=8ee5e69c11) | Apr 16, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [9a5ad3016a](https://linux-hardware.org/?probe=9a5ad3016a) | Apr 15, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [dbc22d503d](https://linux-hardware.org/?probe=dbc22d503d) | Apr 12, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c6ef5b093d](https://linux-hardware.org/?probe=c6ef5b093d) | Apr 12, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [b14a1a07ac](https://linux-hardware.org/?probe=b14a1a07ac) | Apr 11, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [2dd67dae79](https://linux-hardware.org/?probe=2dd67dae79) | Apr 11, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [059aa32bb7](https://linux-hardware.org/?probe=059aa32bb7) | Apr 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [4a05cec425](https://linux-hardware.org/?probe=4a05cec425) | Apr 10, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [cf750140a8](https://linux-hardware.org/?probe=cf750140a8) | Apr 10, 2021 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | Notebook    | [156c9db184](https://linux-hardware.org/?probe=156c9db184) | Apr 10, 2021 |
| ASRock        | B560M Pro4                  | Desktop     | [d4484f50cd](https://linux-hardware.org/?probe=d4484f50cd) | Apr 08, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [cd260eee11](https://linux-hardware.org/?probe=cd260eee11) | Apr 08, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [e83e7312c9](https://linux-hardware.org/?probe=e83e7312c9) | Apr 08, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [bf0490433a](https://linux-hardware.org/?probe=bf0490433a) | Apr 07, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [803bcbb44c](https://linux-hardware.org/?probe=803bcbb44c) | Apr 05, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [2fc41158d5](https://linux-hardware.org/?probe=2fc41158d5) | Apr 05, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [22fc47b193](https://linux-hardware.org/?probe=22fc47b193) | Apr 05, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [44efde8890](https://linux-hardware.org/?probe=44efde8890) | Apr 05, 2021 |
| HP            | 1000                        | Notebook    | [be995ccb43](https://linux-hardware.org/?probe=be995ccb43) | Apr 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [941b588cf9](https://linux-hardware.org/?probe=941b588cf9) | Apr 03, 2021 |
| MSI           | B550-A PRO                  | Desktop     | [f7ddac6f83](https://linux-hardware.org/?probe=f7ddac6f83) | Apr 02, 2021 |
| Acer          | Aspire 4739                 | Notebook    | [19ba24510c](https://linux-hardware.org/?probe=19ba24510c) | Apr 02, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [c41ba66f79](https://linux-hardware.org/?probe=c41ba66f79) | Apr 01, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [463bdc0444](https://linux-hardware.org/?probe=463bdc0444) | Apr 01, 2021 |
| ASUSTek       | X550VX                      | Notebook    | [4d95cd31eb](https://linux-hardware.org/?probe=4d95cd31eb) | Mar 27, 2021 |
| Dell          | Latitude 5400               | Notebook    | [5cab0ca67e](https://linux-hardware.org/?probe=5cab0ca67e) | Mar 26, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [adae4537c5](https://linux-hardware.org/?probe=adae4537c5) | Mar 25, 2021 |
| ASUSTek       | K45VD                       | Notebook    | [74592068ee](https://linux-hardware.org/?probe=74592068ee) | Mar 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [3d99b46431](https://linux-hardware.org/?probe=3d99b46431) | Mar 25, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [a5d5c057c0](https://linux-hardware.org/?probe=a5d5c057c0) | Mar 24, 2021 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [1ce5b4161e](https://linux-hardware.org/?probe=1ce5b4161e) | Mar 24, 2021 |
| ASUSTek       | X45U                        | Notebook    | [05632e634d](https://linux-hardware.org/?probe=05632e634d) | Mar 23, 2021 |
| MSI           | B460M PRO                   | Desktop     | [3a26303ce0](https://linux-hardware.org/?probe=3a26303ce0) | Mar 21, 2021 |
| MSI           | B460M PRO                   | Desktop     | [82bf6fd41b](https://linux-hardware.org/?probe=82bf6fd41b) | Mar 21, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [ed1a952ed3](https://linux-hardware.org/?probe=ed1a952ed3) | Mar 17, 2021 |
| Dell          | Vostro 3481                 | Notebook    | [63b8942776](https://linux-hardware.org/?probe=63b8942776) | Mar 12, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [abec8a4c19](https://linux-hardware.org/?probe=abec8a4c19) | Mar 08, 2021 |
| HP            | 85A2                        | All in one  | [7ff2ebf89e](https://linux-hardware.org/?probe=7ff2ebf89e) | Mar 08, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [461b5d7b4b](https://linux-hardware.org/?probe=461b5d7b4b) | Mar 06, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [cb688e237f](https://linux-hardware.org/?probe=cb688e237f) | Mar 06, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [50a76385ba](https://linux-hardware.org/?probe=50a76385ba) | Mar 05, 2021 |
| Unknown       | Unknown                     | Desktop     | [b4b92701a0](https://linux-hardware.org/?probe=b4b92701a0) | Mar 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [68d0129e2d](https://linux-hardware.org/?probe=68d0129e2d) | Mar 05, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [404bdce056](https://linux-hardware.org/?probe=404bdce056) | Mar 05, 2021 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [80ce017529](https://linux-hardware.org/?probe=80ce017529) | Mar 04, 2021 |
| ASUSTek       | X442URR                     | Notebook    | [d8e04d832e](https://linux-hardware.org/?probe=d8e04d832e) | Mar 03, 2021 |
| Supermicro    | X10DRG-O+-CPU               | Server      | [822418675e](https://linux-hardware.org/?probe=822418675e) | Mar 02, 2021 |
| ASUSTek       | UX303UB                     | Notebook    | [c4867a5743](https://linux-hardware.org/?probe=c4867a5743) | Mar 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [a5f08bd719](https://linux-hardware.org/?probe=a5f08bd719) | Mar 01, 2021 |
| Biostar       | H61MGV3                     | Desktop     | [85e0a1cacc](https://linux-hardware.org/?probe=85e0a1cacc) | Mar 01, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [b59c5fdb8a](https://linux-hardware.org/?probe=b59c5fdb8a) | Feb 28, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a0a4dfe970](https://linux-hardware.org/?probe=a0a4dfe970) | Feb 28, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [17cc827fb6](https://linux-hardware.org/?probe=17cc827fb6) | Feb 28, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [95c5fe898a](https://linux-hardware.org/?probe=95c5fe898a) | Feb 27, 2021 |
| Lenovo        | Unknown                     | Desktop     | [0ca27a0ce2](https://linux-hardware.org/?probe=0ca27a0ce2) | Feb 24, 2021 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [d3f1f06d5d](https://linux-hardware.org/?probe=d3f1f06d5d) | Feb 22, 2021 |
| HP            | Notebook                    | Notebook    | [e718153751](https://linux-hardware.org/?probe=e718153751) | Feb 22, 2021 |
| ASUSTek       | K42F                        | Notebook    | [2380c82b48](https://linux-hardware.org/?probe=2380c82b48) | Feb 20, 2021 |
| HP            | Notebook                    | Notebook    | [326de2e4f5](https://linux-hardware.org/?probe=326de2e4f5) | Feb 19, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [fe95f7aef8](https://linux-hardware.org/?probe=fe95f7aef8) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [b1edb9db86](https://linux-hardware.org/?probe=b1edb9db86) | Feb 19, 2021 |
| Biostar       | Hi-Fi A68U3P                | Desktop     | [abc0ef8bc7](https://linux-hardware.org/?probe=abc0ef8bc7) | Feb 19, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [f9abaeb3f9](https://linux-hardware.org/?probe=f9abaeb3f9) | Feb 18, 2021 |
| HP            | Laptop 14-bw0xx             | Notebook    | [1a3e26503a](https://linux-hardware.org/?probe=1a3e26503a) | Feb 17, 2021 |
| Acer          | Aspire E5-471G              | Notebook    | [3b58cbf4e6](https://linux-hardware.org/?probe=3b58cbf4e6) | Feb 17, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | Notebook    | [5a09ac2a06](https://linux-hardware.org/?probe=5a09ac2a06) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMS0PB11    | Notebook    | [9805e3bcb5](https://linux-hardware.org/?probe=9805e3bcb5) | Feb 16, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a0537ad7d5](https://linux-hardware.org/?probe=a0537ad7d5) | Feb 16, 2021 |
| Toshiba       | Satellite C855              | Notebook    | [60adcbc05d](https://linux-hardware.org/?probe=60adcbc05d) | Feb 16, 2021 |
| Timi          | TM1703                      | Notebook    | [4d64e40cca](https://linux-hardware.org/?probe=4d64e40cca) | Feb 14, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [e4657a221a](https://linux-hardware.org/?probe=e4657a221a) | Feb 13, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| ASUSTek       | X456UQK                     | Notebook    | [f0380f099d](https://linux-hardware.org/?probe=f0380f099d) | Feb 12, 2021 |
| ASUSTek       | K43E                        | Notebook    | [1604193c0f](https://linux-hardware.org/?probe=1604193c0f) | Feb 11, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [704dbacb0d](https://linux-hardware.org/?probe=704dbacb0d) | Feb 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [ec95272afa](https://linux-hardware.org/?probe=ec95272afa) | Feb 10, 2021 |
| Lenovo        | ThinkPad X131e 33741E0      | Notebook    | [4c52c9aa29](https://linux-hardware.org/?probe=4c52c9aa29) | Feb 06, 2021 |
| Acer          | NXHATSN00190808A906600      | Notebook    | [2ed3d18f0a](https://linux-hardware.org/?probe=2ed3d18f0a) | Feb 05, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [d56280ec33](https://linux-hardware.org/?probe=d56280ec33) | Feb 05, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [f48cf2f332](https://linux-hardware.org/?probe=f48cf2f332) | Feb 05, 2021 |
| Compal        | PBL10                       | Notebook    | [5cf67578d7](https://linux-hardware.org/?probe=5cf67578d7) | Feb 04, 2021 |
| Compal        | PBL10                       | Notebook    | [a20e9d9588](https://linux-hardware.org/?probe=a20e9d9588) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | Notebook    | [f79d79fd99](https://linux-hardware.org/?probe=f79d79fd99) | Feb 04, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [502bc7eb2a](https://linux-hardware.org/?probe=502bc7eb2a) | Feb 04, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [15b84d2abc](https://linux-hardware.org/?probe=15b84d2abc) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [8d369a84ce](https://linux-hardware.org/?probe=8d369a84ce) | Feb 04, 2021 |
| Gigabyte      | B460M DS3H                  | Desktop     | [95883e3fff](https://linux-hardware.org/?probe=95883e3fff) | Feb 04, 2021 |
| ASUSTek       | X442UQ                      | Notebook    | [9b722252fa](https://linux-hardware.org/?probe=9b722252fa) | Feb 04, 2021 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [2365556c9d](https://linux-hardware.org/?probe=2365556c9d) | Jan 31, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [cebba8a2a8](https://linux-hardware.org/?probe=cebba8a2a8) | Jan 30, 2021 |
| Lenovo        | ThinkPad X280 20KES7YB00    | Notebook    | [b498c0fcba](https://linux-hardware.org/?probe=b498c0fcba) | Jan 29, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [2e5b64f391](https://linux-hardware.org/?probe=2e5b64f391) | Jan 27, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [f068345e45](https://linux-hardware.org/?probe=f068345e45) | Jan 27, 2021 |
| Acer          | AOD255E                     | Notebook    | [b346230927](https://linux-hardware.org/?probe=b346230927) | Jan 27, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [e6d527734c](https://linux-hardware.org/?probe=e6d527734c) | Jan 27, 2021 |
| Acer          | One Z1402                   | Notebook    | [1b8a4dfe38](https://linux-hardware.org/?probe=1b8a4dfe38) | Jan 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [d18f1e2124](https://linux-hardware.org/?probe=d18f1e2124) | Jan 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [16b5d3f4ca](https://linux-hardware.org/?probe=16b5d3f4ca) | Jan 23, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1af669260c](https://linux-hardware.org/?probe=1af669260c) | Jan 22, 2021 |
| Acer          | Swift SF514-52T             | Notebook    | [be049e723f](https://linux-hardware.org/?probe=be049e723f) | Jan 21, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [81c592d723](https://linux-hardware.org/?probe=81c592d723) | Jan 21, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [dc16c8d7a4](https://linux-hardware.org/?probe=dc16c8d7a4) | Jan 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f9b1a75983](https://linux-hardware.org/?probe=f9b1a75983) | Jan 19, 2021 |
| Lenovo        | ThinkPad T480 20L5A02JID    | Notebook    | [0599ce4883](https://linux-hardware.org/?probe=0599ce4883) | Jan 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f34a9b325b](https://linux-hardware.org/?probe=f34a9b325b) | Jan 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [be559d7b11](https://linux-hardware.org/?probe=be559d7b11) | Jan 17, 2021 |
| Lenovo        | IdeaPad Z370                | Notebook    | [728438c7eb](https://linux-hardware.org/?probe=728438c7eb) | Jan 16, 2021 |
| Lenovo        | IdeaPad Z370                | Notebook    | [6e3c415308](https://linux-hardware.org/?probe=6e3c415308) | Jan 16, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [78a8b317d6](https://linux-hardware.org/?probe=78a8b317d6) | Jan 16, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [82728c7a68](https://linux-hardware.org/?probe=82728c7a68) | Jan 15, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [8e785a29dd](https://linux-hardware.org/?probe=8e785a29dd) | Jan 15, 2021 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [bb99db17ed](https://linux-hardware.org/?probe=bb99db17ed) | Jan 15, 2021 |
| HP            | G42                         | Notebook    | [63dd848e66](https://linux-hardware.org/?probe=63dd848e66) | Jan 14, 2021 |
| HP            | 834F                        | Desktop     | [c849bbc95a](https://linux-hardware.org/?probe=c849bbc95a) | Jan 14, 2021 |
| Lenovo        | 36EB SDK0Q55726 WIN 3273... | Desktop     | [ace52f974e](https://linux-hardware.org/?probe=ace52f974e) | Jan 13, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [0cfe91c011](https://linux-hardware.org/?probe=0cfe91c011) | Jan 13, 2021 |
| Acer          | Spin SP111-34N              | Convertible | [5012e25bd9](https://linux-hardware.org/?probe=5012e25bd9) | Jan 12, 2021 |
| Qualcomm T... | SDM670 PM660 + PM660L MT... | Phone       | [15c5b077ba](https://linux-hardware.org/?probe=15c5b077ba) | Jan 10, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [da387b9871](https://linux-hardware.org/?probe=da387b9871) | Jan 09, 2021 |
| ASUSTek       | G750JM                      | Notebook    | [794d86e07e](https://linux-hardware.org/?probe=794d86e07e) | Jan 07, 2021 |
| ASUSTek       | G750JM                      | Notebook    | [a32f193a0d](https://linux-hardware.org/?probe=a32f193a0d) | Jan 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [692f320444](https://linux-hardware.org/?probe=692f320444) | Jan 07, 2021 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [414638f163](https://linux-hardware.org/?probe=414638f163) | Jan 07, 2021 |
| Lenovo        | C-Notebook XXXX 3000 G40... | Notebook    | [8a573087bd](https://linux-hardware.org/?probe=8a573087bd) | Jan 07, 2021 |
| MSI           | Modern 15 A10RBS            | Notebook    | [d4ded10aed](https://linux-hardware.org/?probe=d4ded10aed) | Jan 06, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [ea36c16e10](https://linux-hardware.org/?probe=ea36c16e10) | Jan 05, 2021 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [89d2d898df](https://linux-hardware.org/?probe=89d2d898df) | Jan 05, 2021 |
| ASUSTek       | K43SD                       | Notebook    | [79f04bb2b4](https://linux-hardware.org/?probe=79f04bb2b4) | Jan 04, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [6ebc8c1b1c](https://linux-hardware.org/?probe=6ebc8c1b1c) | Jan 03, 2021 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [9fe6d5b992](https://linux-hardware.org/?probe=9fe6d5b992) | Jan 02, 2021 |
| ASUSTek       | X455LAB                     | Notebook    | [1c55bbde2e](https://linux-hardware.org/?probe=1c55bbde2e) | Jan 01, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [010abb3a8f](https://linux-hardware.org/?probe=010abb3a8f) | Jan 01, 2021 |
| HP            | 1000                        | Notebook    | [981fa79f13](https://linux-hardware.org/?probe=981fa79f13) | Jan 01, 2021 |
| MSI           | G41M-P26                    | Desktop     | [8d7a10a828](https://linux-hardware.org/?probe=8d7a10a828) | Dec 31, 2020 |
| ASUSTek       | X455LAB                     | Notebook    | [8cbb6c5afe](https://linux-hardware.org/?probe=8cbb6c5afe) | Dec 31, 2020 |
| Sole          | Unknown                     | Notebook    | [04bc36aa05](https://linux-hardware.org/?probe=04bc36aa05) | Dec 30, 2020 |
| HP            | ZBook 15 G2                 | Notebook    | [87757ee4f2](https://linux-hardware.org/?probe=87757ee4f2) | Dec 30, 2020 |
| Dell          | Vostro A840                 | Notebook    | [76e7e81662](https://linux-hardware.org/?probe=76e7e81662) | Dec 28, 2020 |
| MSI           | 760GM-P23                   | Desktop     | [9ea9c09319](https://linux-hardware.org/?probe=9ea9c09319) | Dec 27, 2020 |
| Lenovo        | ThinkPad T530 24294V4       | Notebook    | [50625b08c9](https://linux-hardware.org/?probe=50625b08c9) | Dec 26, 2020 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [405b8ef206](https://linux-hardware.org/?probe=405b8ef206) | Dec 25, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5bd5d77342](https://linux-hardware.org/?probe=5bd5d77342) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | Notebook    | [a53bf69f31](https://linux-hardware.org/?probe=a53bf69f31) | Dec 24, 2020 |
| Lenovo        | ThinkPad SL400 27439MA      | Notebook    | [7f1872861c](https://linux-hardware.org/?probe=7f1872861c) | Dec 24, 2020 |
| ASUSTek       | UX370UAF                    | Convertible | [c1e1c56c70](https://linux-hardware.org/?probe=c1e1c56c70) | Dec 24, 2020 |
| Acer          | Aspire 4738Z                | Notebook    | [26c4af7060](https://linux-hardware.org/?probe=26c4af7060) | Dec 22, 2020 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [be0654391c](https://linux-hardware.org/?probe=be0654391c) | Dec 21, 2020 |
| MSI           | 870A-G54                    | Desktop     | [479ee62f9f](https://linux-hardware.org/?probe=479ee62f9f) | Dec 21, 2020 |
| Unknown       | Unknown                     | Phone       | [9771bde74e](https://linux-hardware.org/?probe=9771bde74e) | Dec 20, 2020 |
| HP            | 1497                        | Desktop     | [1bfa453ea4](https://linux-hardware.org/?probe=1bfa453ea4) | Dec 19, 2020 |
| HP            | 1497                        | Desktop     | [9b292e4071](https://linux-hardware.org/?probe=9b292e4071) | Dec 19, 2020 |
| Phoenix/Si... | M720SR                      | Notebook    | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Dell          | 0W6TWP A01                  | Server      | [e24d0e827b](https://linux-hardware.org/?probe=e24d0e827b) | Dec 18, 2020 |
| Lenovo        | C-Notebook XXXX 3000 G40... | Notebook    | [23766674a9](https://linux-hardware.org/?probe=23766674a9) | Dec 18, 2020 |
| ASUSTek       | K55DR                       | Notebook    | [86bca93d29](https://linux-hardware.org/?probe=86bca93d29) | Dec 16, 2020 |
| ASUSTek       | K55DR                       | Notebook    | [300d21973e](https://linux-hardware.org/?probe=300d21973e) | Dec 16, 2020 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| ASUSTek       | 1015BX                      | Notebook    | [5cb5d5f2a8](https://linux-hardware.org/?probe=5cb5d5f2a8) | Dec 15, 2020 |
| HP            | ProLiant DL380 G6           | Server      | [514aa3a7fc](https://linux-hardware.org/?probe=514aa3a7fc) | Dec 14, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [406d93673b](https://linux-hardware.org/?probe=406d93673b) | Dec 13, 2020 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [785196a6d7](https://linux-hardware.org/?probe=785196a6d7) | Dec 13, 2020 |
| MSI           | B360 GAMING PLUS            | Desktop     | [7a77cc7ec2](https://linux-hardware.org/?probe=7a77cc7ec2) | Dec 12, 2020 |
| ASUSTek       | P9D-X Series                | Server      | [72dff1bd7f](https://linux-hardware.org/?probe=72dff1bd7f) | Dec 12, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | Notebook    | [8a32a0ec2e](https://linux-hardware.org/?probe=8a32a0ec2e) | Dec 08, 2020 |
| Lenovo        | ThinkPad 11e 20DAS15V00     | Notebook    | [318416a95a](https://linux-hardware.org/?probe=318416a95a) | Dec 08, 2020 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [d4c5036cd3](https://linux-hardware.org/?probe=d4c5036cd3) | Dec 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [5f56870146](https://linux-hardware.org/?probe=5f56870146) | Dec 04, 2020 |
| LORD ELECT... | LORD G4x 775 ICH7 8712 A... | Desktop     | [3e44b38d7f](https://linux-hardware.org/?probe=3e44b38d7f) | Dec 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2a305a9be7](https://linux-hardware.org/?probe=2a305a9be7) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [cf81aea5fe](https://linux-hardware.org/?probe=cf81aea5fe) | Dec 02, 2020 |
| Qualcomm T... | SDM670 PM660 + PM660L MT... | Phone       | [fdb97e12b2](https://linux-hardware.org/?probe=fdb97e12b2) | Nov 30, 2020 |
| ASUSTek       | X456URK                     | Notebook    | [be6b2ec83a](https://linux-hardware.org/?probe=be6b2ec83a) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| ASRock        | H67M                        | Desktop     | [11ccd3281d](https://linux-hardware.org/?probe=11ccd3281d) | Nov 28, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [b664b71a15](https://linux-hardware.org/?probe=b664b71a15) | Nov 28, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | Notebook    | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| Acer          | NXHATSN00190808A906600      | Notebook    | [402e6fe81a](https://linux-hardware.org/?probe=402e6fe81a) | Nov 26, 2020 |
| Acer          | Aspire M3970                | Desktop     | [7350b05e56](https://linux-hardware.org/?probe=7350b05e56) | Nov 25, 2020 |
| Acer          | Aspire M3970                | Desktop     | [f380a566c2](https://linux-hardware.org/?probe=f380a566c2) | Nov 25, 2020 |
| Toshiba       | Satellite L40               | Notebook    | [ffafc05e1f](https://linux-hardware.org/?probe=ffafc05e1f) | Nov 25, 2020 |
| Acer          | Veriton X4610G              | Desktop     | [e9ace7d042](https://linux-hardware.org/?probe=e9ace7d042) | Nov 24, 2020 |
| HP            | 14                          | Notebook    | [1a02430025](https://linux-hardware.org/?probe=1a02430025) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | Notebook    | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | Notebook    | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [b17dd2d085](https://linux-hardware.org/?probe=b17dd2d085) | Nov 21, 2020 |
| Dell          | 08HPGT A01                  | Desktop     | [d5ae57d261](https://linux-hardware.org/?probe=d5ae57d261) | Nov 20, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [25abf7a587](https://linux-hardware.org/?probe=25abf7a587) | Nov 19, 2020 |
| HP            | 14                          | Notebook    | [548056d4e9](https://linux-hardware.org/?probe=548056d4e9) | Nov 18, 2020 |
| HP            | 14                          | Notebook    | [a08766aff4](https://linux-hardware.org/?probe=a08766aff4) | Nov 18, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [3d65def3ce](https://linux-hardware.org/?probe=3d65def3ce) | Nov 16, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [82dbd47dff](https://linux-hardware.org/?probe=82dbd47dff) | Nov 15, 2020 |
| Dell          | XPS 13 7390                 | Notebook    | [8844beb362](https://linux-hardware.org/?probe=8844beb362) | Nov 14, 2020 |
| Lenovo        | ThinkPad T410s 2904CGU      | Notebook    | [271f9ac078](https://linux-hardware.org/?probe=271f9ac078) | Nov 14, 2020 |
| ASRock        | B450 Pro4                   | Desktop     | [f24f7ba17e](https://linux-hardware.org/?probe=f24f7ba17e) | Nov 13, 2020 |
| Acer          | Aspire V5-132               | Notebook    | [166921ade6](https://linux-hardware.org/?probe=166921ade6) | Nov 13, 2020 |
| Acer          | Aspire E5-421               | Notebook    | [625727a34f](https://linux-hardware.org/?probe=625727a34f) | Nov 12, 2020 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [0b2411ab89](https://linux-hardware.org/?probe=0b2411ab89) | Nov 12, 2020 |
| Lenovo        | G400 20235                  | Notebook    | [e8b5212a0b](https://linux-hardware.org/?probe=e8b5212a0b) | Nov 11, 2020 |
| HP            | 84DE                        | All in one  | [758fe8c860](https://linux-hardware.org/?probe=758fe8c860) | Nov 11, 2020 |
| Dell          | 0GY6Y8 A00                  | Desktop     | [613e036e8d](https://linux-hardware.org/?probe=613e036e8d) | Nov 11, 2020 |
| Acer          | Aspire E5-475G              | Notebook    | [1d195bfc21](https://linux-hardware.org/?probe=1d195bfc21) | Nov 10, 2020 |
| MSI           | H410M PRO-VH                | Desktop     | [e5603638aa](https://linux-hardware.org/?probe=e5603638aa) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [579f942204](https://linux-hardware.org/?probe=579f942204) | Nov 09, 2020 |
| MSI           | 870A-G54                    | Desktop     | [d14df17124](https://linux-hardware.org/?probe=d14df17124) | Nov 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [923558f59a](https://linux-hardware.org/?probe=923558f59a) | Nov 08, 2020 |
| HP            | 304Ah                       | Desktop     | [530cc628fb](https://linux-hardware.org/?probe=530cc628fb) | Nov 07, 2020 |
| HP            | 304Ah                       | Desktop     | [0ed06ad934](https://linux-hardware.org/?probe=0ed06ad934) | Nov 04, 2020 |
| ASUSTek       | X453SA                      | Notebook    | [1bb7c5cfe5](https://linux-hardware.org/?probe=1bb7c5cfe5) | Nov 03, 2020 |
| Gigabyte      | H81M-Gaming 3               | Desktop     | [8d7b38dbf3](https://linux-hardware.org/?probe=8d7b38dbf3) | Nov 03, 2020 |
| Gigabyte      | H81M-Gaming 3               | Desktop     | [0c6140c86e](https://linux-hardware.org/?probe=0c6140c86e) | Nov 03, 2020 |
| ASUSTek       | X442UQR                     | Notebook    | [98225dbf74](https://linux-hardware.org/?probe=98225dbf74) | Nov 03, 2020 |
| Unknown       | Unknown                     | Notebook    | [4c80913adb](https://linux-hardware.org/?probe=4c80913adb) | Nov 02, 2020 |
| Lenovo        | G40-30 80FY                 | Notebook    | [7bc709a3cd](https://linux-hardware.org/?probe=7bc709a3cd) | Nov 01, 2020 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [5cc15ed0be](https://linux-hardware.org/?probe=5cc15ed0be) | Oct 31, 2020 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [c1553eecd9](https://linux-hardware.org/?probe=c1553eecd9) | Oct 31, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [64b38989db](https://linux-hardware.org/?probe=64b38989db) | Oct 30, 2020 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [516ff504f0](https://linux-hardware.org/?probe=516ff504f0) | Oct 29, 2020 |
| MSI           | B85M GAMING                 | Desktop     | [b2b720adf7](https://linux-hardware.org/?probe=b2b720adf7) | Oct 28, 2020 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | Notebook    | [45b0065d49](https://linux-hardware.org/?probe=45b0065d49) | Oct 28, 2020 |
| HP            | Notebook                    | Notebook    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| HP            | 1493                        | Desktop     | [cf9c3c195a](https://linux-hardware.org/?probe=cf9c3c195a) | Oct 24, 2020 |
| Clevo         | M7x0S                       | Notebook    | [8559d7b074](https://linux-hardware.org/?probe=8559d7b074) | Oct 24, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [3b60701957](https://linux-hardware.org/?probe=3b60701957) | Oct 23, 2020 |
| Quanta        | 2B03 110                    | Desktop     | [afa8ef9dda](https://linux-hardware.org/?probe=afa8ef9dda) | Oct 20, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [0a1f42ff5e](https://linux-hardware.org/?probe=0a1f42ff5e) | Oct 18, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [327a983226](https://linux-hardware.org/?probe=327a983226) | Oct 18, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| ASRock        | X99 Taichi                  | Desktop     | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [646054c190](https://linux-hardware.org/?probe=646054c190) | Oct 08, 2020 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [f02492e188](https://linux-hardware.org/?probe=f02492e188) | Oct 08, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [5e9f9ee314](https://linux-hardware.org/?probe=5e9f9ee314) | Oct 06, 2020 |
| ASUSTek       | V221IC                      | All in one  | [8d09076156](https://linux-hardware.org/?probe=8d09076156) | Oct 05, 2020 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [805323645e](https://linux-hardware.org/?probe=805323645e) | Oct 04, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [57e753215c](https://linux-hardware.org/?probe=57e753215c) | Oct 04, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [36a5cbc73c](https://linux-hardware.org/?probe=36a5cbc73c) | Oct 03, 2020 |
| Lenovo        | IdeaPad Z480                | Notebook    | [f7282459cf](https://linux-hardware.org/?probe=f7282459cf) | Oct 03, 2020 |
| Acer          | NXHATSN00190808A906600      | Notebook    | [ece82b096b](https://linux-hardware.org/?probe=ece82b096b) | Oct 01, 2020 |
| HP            | Pavilion x2 Detachable      | Notebook    | [d4078124eb](https://linux-hardware.org/?probe=d4078124eb) | Sep 30, 2020 |
| ASUSTek       | X450EA                      | Notebook    | [2646942e92](https://linux-hardware.org/?probe=2646942e92) | Sep 30, 2020 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [e937cdfcbc](https://linux-hardware.org/?probe=e937cdfcbc) | Sep 28, 2020 |
| MSI           | B360 GAMING PLUS            | Desktop     | [6b3915fc77](https://linux-hardware.org/?probe=6b3915fc77) | Sep 28, 2020 |
| HP            | 430                         | Notebook    | [9eef183864](https://linux-hardware.org/?probe=9eef183864) | Sep 27, 2020 |
| ASRock        | B365M Phantom Gaming 4      | Desktop     | [9f213e1442](https://linux-hardware.org/?probe=9f213e1442) | Sep 25, 2020 |
| Toshiba       | Satellite L730              | Notebook    | [28ff46aa6b](https://linux-hardware.org/?probe=28ff46aa6b) | Sep 25, 2020 |
| Lenovo        | ThinkCentre M57p 9193A11    | Desktop     | [4d8a70073f](https://linux-hardware.org/?probe=4d8a70073f) | Sep 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [24b078a7f0](https://linux-hardware.org/?probe=24b078a7f0) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| ASUSTek       | X455YA                      | Notebook    | [0959901fca](https://linux-hardware.org/?probe=0959901fca) | Sep 23, 2020 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [ed83ee1e30](https://linux-hardware.org/?probe=ed83ee1e30) | Sep 22, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [4a9dbc9937](https://linux-hardware.org/?probe=4a9dbc9937) | Sep 19, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [0e2694227b](https://linux-hardware.org/?probe=0e2694227b) | Sep 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [d766064036](https://linux-hardware.org/?probe=d766064036) | Sep 17, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [32b487459e](https://linux-hardware.org/?probe=32b487459e) | Sep 16, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [8be0a34480](https://linux-hardware.org/?probe=8be0a34480) | Sep 16, 2020 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [b5438c62fc](https://linux-hardware.org/?probe=b5438c62fc) | Sep 16, 2020 |
| ECS           | Z97M-PK                     | Desktop     | [888e740324](https://linux-hardware.org/?probe=888e740324) | Sep 13, 2020 |
| HP            | 430                         | Notebook    | [bfb152e615](https://linux-hardware.org/?probe=bfb152e615) | Sep 10, 2020 |
| MSI           | B360 GAMING PLUS            | Desktop     | [6c5d768e02](https://linux-hardware.org/?probe=6c5d768e02) | Sep 10, 2020 |
| ASUSTek       | GL503VD                     | Notebook    | [820f4da953](https://linux-hardware.org/?probe=820f4da953) | Sep 09, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [c363153de4](https://linux-hardware.org/?probe=c363153de4) | Sep 08, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [d545f007f9](https://linux-hardware.org/?probe=d545f007f9) | Sep 05, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [7e0202ac18](https://linux-hardware.org/?probe=7e0202ac18) | Sep 04, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [152a400df9](https://linux-hardware.org/?probe=152a400df9) | Sep 04, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [712ec86d11](https://linux-hardware.org/?probe=712ec86d11) | Sep 04, 2020 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [5bcdd6aa5a](https://linux-hardware.org/?probe=5bcdd6aa5a) | Sep 03, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [ebcd809d62](https://linux-hardware.org/?probe=ebcd809d62) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [8b75181a08](https://linux-hardware.org/?probe=8b75181a08) | Sep 03, 2020 |
| Lenovo        | G405 20239                  | Notebook    | [518d27feca](https://linux-hardware.org/?probe=518d27feca) | Sep 03, 2020 |
| ASUSTek       | X441BA                      | Notebook    | [e244d30598](https://linux-hardware.org/?probe=e244d30598) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2325WLB       | Notebook    | [e558c503f8](https://linux-hardware.org/?probe=e558c503f8) | Sep 03, 2020 |
| Lenovo        | ThinkPad X230 2324AS7       | Notebook    | [676f1b8dce](https://linux-hardware.org/?probe=676f1b8dce) | Sep 03, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [24bdd07050](https://linux-hardware.org/?probe=24bdd07050) | Sep 02, 2020 |
| HP            | Pavilion dm1                | Notebook    | [1723b44134](https://linux-hardware.org/?probe=1723b44134) | Sep 02, 2020 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0c63fa76a6](https://linux-hardware.org/?probe=0c63fa76a6) | Sep 01, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [a70aa343a9](https://linux-hardware.org/?probe=a70aa343a9) | Aug 31, 2020 |
| HP            | Pavilion g4                 | Notebook    | [cf281b97df](https://linux-hardware.org/?probe=cf281b97df) | Aug 31, 2020 |
| HP            | Pavilion g4                 | Notebook    | [4ae31fc59f](https://linux-hardware.org/?probe=4ae31fc59f) | Aug 30, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6d06e18252](https://linux-hardware.org/?probe=6d06e18252) | Aug 30, 2020 |
| MSI           | B75MA-P33                   | Desktop     | [05483ed2c3](https://linux-hardware.org/?probe=05483ed2c3) | Aug 28, 2020 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [687538cadf](https://linux-hardware.org/?probe=687538cadf) | Aug 24, 2020 |
| MSI           | 870A-G54                    | Desktop     | [727980a18d](https://linux-hardware.org/?probe=727980a18d) | Aug 23, 2020 |
| Lenovo        | G400 20235                  | Notebook    | [f209fc4fd1](https://linux-hardware.org/?probe=f209fc4fd1) | Aug 22, 2020 |
| SPECTRUM U... | VA 880G                     | Desktop     | [ef0b289382](https://linux-hardware.org/?probe=ef0b289382) | Aug 21, 2020 |
| ASUSTek       | X550IK                      | Notebook    | [70aa141880](https://linux-hardware.org/?probe=70aa141880) | Aug 21, 2020 |
| ASRock        | A300M-STX                   | Desktop     | [0aeef3e18b](https://linux-hardware.org/?probe=0aeef3e18b) | Aug 19, 2020 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f205ba371e](https://linux-hardware.org/?probe=f205ba371e) | Aug 19, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [cd7328883c](https://linux-hardware.org/?probe=cd7328883c) | Aug 18, 2020 |
| MSI           | 870A-G54                    | Desktop     | [292a02f724](https://linux-hardware.org/?probe=292a02f724) | Aug 17, 2020 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [977a611718](https://linux-hardware.org/?probe=977a611718) | Aug 16, 2020 |
| Dell          | Latitude E6400              | Notebook    | [177b63fda5](https://linux-hardware.org/?probe=177b63fda5) | Aug 15, 2020 |
| Biostar       | H310MHC                     | Desktop     | [4331ff5e27](https://linux-hardware.org/?probe=4331ff5e27) | Aug 14, 2020 |
| Dell          | 0D28YY A01                  | Desktop     | [6740e51a94](https://linux-hardware.org/?probe=6740e51a94) | Aug 14, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [5291acaadc](https://linux-hardware.org/?probe=5291acaadc) | Aug 14, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [191f1be39f](https://linux-hardware.org/?probe=191f1be39f) | Aug 14, 2020 |
| Dell          | Latitude E6230              | Notebook    | [da6d9fdf1d](https://linux-hardware.org/?probe=da6d9fdf1d) | Aug 14, 2020 |
| HP            | Notebook                    | Notebook    | [8e7a53706c](https://linux-hardware.org/?probe=8e7a53706c) | Aug 13, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [c34e36f36e](https://linux-hardware.org/?probe=c34e36f36e) | Aug 10, 2020 |
| HP            | ProBook 440 G4              | Notebook    | [5b6c3861bb](https://linux-hardware.org/?probe=5b6c3861bb) | Aug 10, 2020 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [74050bb5dd](https://linux-hardware.org/?probe=74050bb5dd) | Aug 10, 2020 |
| NEC Comput... | MS-7264LW                   | Desktop     | [63f1552717](https://linux-hardware.org/?probe=63f1552717) | Aug 09, 2020 |
| NEC Comput... | MS-7264LW                   | Desktop     | [bc4eab7fa3](https://linux-hardware.org/?probe=bc4eab7fa3) | Aug 09, 2020 |
| MSI           | B85M GAMING                 | Desktop     | [984c0ed0a7](https://linux-hardware.org/?probe=984c0ed0a7) | Aug 07, 2020 |
| HP            | Pavilion g4                 | Notebook    | [0ea8276f60](https://linux-hardware.org/?probe=0ea8276f60) | Aug 07, 2020 |
| HP            | Pavilion g4                 | Notebook    | [227e2e8de7](https://linux-hardware.org/?probe=227e2e8de7) | Aug 07, 2020 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [d948bfbb09](https://linux-hardware.org/?probe=d948bfbb09) | Aug 07, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [8a63857dec](https://linux-hardware.org/?probe=8a63857dec) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [99bb1cd9d9](https://linux-hardware.org/?probe=99bb1cd9d9) | Aug 06, 2020 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [87a26416b1](https://linux-hardware.org/?probe=87a26416b1) | Aug 06, 2020 |
| MSI           | H81M-P33                    | Desktop     | [f9cb52c02a](https://linux-hardware.org/?probe=f9cb52c02a) | Aug 05, 2020 |
| Dell          | Latitude E6400              | Notebook    | [a1d10698bc](https://linux-hardware.org/?probe=a1d10698bc) | Aug 05, 2020 |
| Toshiba       | Satellite L745              | Notebook    | [4770498bee](https://linux-hardware.org/?probe=4770498bee) | Aug 02, 2020 |
| Toshiba       | Satellite L745              | Notebook    | [8f86800c3c](https://linux-hardware.org/?probe=8f86800c3c) | Aug 02, 2020 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [ecd5a9cdd0](https://linux-hardware.org/?probe=ecd5a9cdd0) | Aug 01, 2020 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [f95e229d75](https://linux-hardware.org/?probe=f95e229d75) | Aug 01, 2020 |
| ASUSTek       | N46VM                       | Notebook    | [d5866f9f0f](https://linux-hardware.org/?probe=d5866f9f0f) | Jul 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [81ca2030be](https://linux-hardware.org/?probe=81ca2030be) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| ASUSTek       | K43E                        | Notebook    | [47067cf62f](https://linux-hardware.org/?probe=47067cf62f) | Jul 29, 2020 |
| ASUSTek       | K43E                        | Notebook    | [5cc61ff85e](https://linux-hardware.org/?probe=5cc61ff85e) | Jul 29, 2020 |
| MSI           | B85M GAMING                 | Desktop     | [ca027f475e](https://linux-hardware.org/?probe=ca027f475e) | Jul 28, 2020 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [5a271f15c2](https://linux-hardware.org/?probe=5a271f15c2) | Jul 28, 2020 |
| ASUSTek       | N46VM                       | Notebook    | [b9abcbb0ca](https://linux-hardware.org/?probe=b9abcbb0ca) | Jul 27, 2020 |
| ASUSTek       | N46VM                       | Notebook    | [864b3c0808](https://linux-hardware.org/?probe=864b3c0808) | Jul 27, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | Desktop     | [f34a4c062d](https://linux-hardware.org/?probe=f34a4c062d) | Jul 26, 2020 |
| Lenovo        | ThinkCentre M58p 6137BG5    | Desktop     | [1d18d6d402](https://linux-hardware.org/?probe=1d18d6d402) | Jul 25, 2020 |
| ASUSTek       | N43SN                       | Notebook    | [8652a9c307](https://linux-hardware.org/?probe=8652a9c307) | Jul 24, 2020 |
| MSI           | B85M GAMING                 | Desktop     | [29191c1b1e](https://linux-hardware.org/?probe=29191c1b1e) | Jul 24, 2020 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [bdbd588c54](https://linux-hardware.org/?probe=bdbd588c54) | Jul 24, 2020 |
| ASUSTek       | N43SN                       | Notebook    | [6417be2a1c](https://linux-hardware.org/?probe=6417be2a1c) | Jul 24, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Indonesia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 148       | 14.6%   |
| Ubuntu 18.04        | 99        | 9.76%   |
| OpenMandriva 4.3    | 46        | 4.54%   |
| OpenMandriva 4.2    | 32        | 3.16%   |
| KDE neon 20.04      | 26        | 2.56%   |
| Ubuntu 22.04        | 24        | 2.37%   |
| Zorin 15            | 23        | 2.27%   |
| Arch                | 22        | 2.17%   |
| Fedora 36           | 20        | 1.97%   |
| Pop!_OS 20.04       | 18        | 1.78%   |
| Ubuntu 21.10        | 16        | 1.58%   |
| Fedora 35           | 16        | 1.58%   |
| Ubuntu 19.10        | 15        | 1.48%   |
| Manjaro             | 15        | 1.48%   |
| Elementary 6.1      | 15        | 1.48%   |
| Linux Mint 19.3     | 14        | 1.38%   |
| Arch Rolling        | 14        | 1.38%   |
| Xubuntu 20.04       | 13        | 1.28%   |
| Linux Mint 20.3     | 13        | 1.28%   |
| ArcoLinux Rolling   | 12        | 1.18%   |
| Debian 11           | 11        | 1.08%   |
| Fedora 32           | 10        | 0.99%   |
| Pop!_OS 21.04       | 9         | 0.89%   |
| Linux Mint 20       | 9         | 0.89%   |
| Kubuntu 20.04       | 9         | 0.89%   |
| Fedora 33           | 9         | 0.89%   |
| Debian 10           | 9         | 0.89%   |
| Zorin 16            | 8         | 0.79%   |
| Ubuntu 21.04        | 8         | 0.79%   |
| Ubuntu 16.04        | 8         | 0.79%   |
| Linux Mint 20.2     | 8         | 0.79%   |
| Fedora 34           | 8         | 0.79%   |
| Ubuntu 19.04        | 7         | 0.69%   |
| Pop!_OS 22.04       | 7         | 0.69%   |
| Linux Mint 20.1     | 7         | 0.69%   |
| Xubuntu 18.04       | 6         | 0.59%   |
| Ubuntu 20.10        | 6         | 0.59%   |
| EndeavourOS Rolling | 6         | 0.59%   |
| Elementary 6        | 6         | 0.59%   |
| Elementary 5.1.7    | 6         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 319       | 32.72%  |
| OpenMandriva  | 84        | 8.62%   |
| Fedora        | 62        | 6.36%   |
| Linux Mint    | 52        | 5.33%   |
| Manjaro       | 42        | 4.31%   |
| Pop!_OS       | 40        | 4.1%    |
| Arch          | 37        | 3.79%   |
| Zorin         | 35        | 3.59%   |
| Elementary    | 33        | 3.38%   |
| KDE neon      | 28        | 2.87%   |
| Endless       | 28        | 2.87%   |
| Xubuntu       | 27        | 2.77%   |
| Debian        | 24        | 2.46%   |
| Kubuntu       | 21        | 2.15%   |
| ROSA          | 14        | 1.44%   |
| Kali          | 14        | 1.44%   |
| ArcoLinux     | 13        | 1.33%   |
| Lubuntu       | 10        | 1.03%   |
| Ubuntu Unity  | 7         | 0.72%   |
| Clear Linux   | 7         | 0.72%   |
| Ubuntu MATE   | 6         | 0.62%   |
| openSUSE      | 6         | 0.62%   |
| EndeavourOS   | 6         | 0.62%   |
| Deepin        | 5         | 0.51%   |
| Parrot        | 4         | 0.41%   |
| MX            | 4         | 0.41%   |
| CentOS        | 4         | 0.41%   |
| Artix         | 4         | 0.41%   |
| Android       | 4         | 0.41%   |
| Ubuntu Budgie | 3         | 0.31%   |
| LMDE          | 3         | 0.31%   |
| UbuntuDDE     | 2         | 0.21%   |
| Sparky        | 2         | 0.21%   |
| Solus         | 2         | 0.21%   |
| Gentoo        | 2         | 0.21%   |
| Devuan        | 2         | 0.21%   |
| Chrome OS     | 2         | 0.21%   |
| BlackPanther  | 2         | 0.21%   |
| Void Linux    | 1         | 0.1%    |
| Ubuntu Studio | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 45        | 4.17%   |
| 5.10.14-desktop-1omv4002 | 29        | 2.69%   |
| 5.4.0-42-generic         | 27        | 2.5%    |
| 5.4.0-26-generic         | 17        | 1.58%   |
| 5.4.0-52-generic         | 16        | 1.48%   |
| 5.4.0-58-generic         | 15        | 1.39%   |
| 4.18.0-15-generic        | 12        | 1.11%   |
| 5.0.0-25-generic         | 11        | 1.02%   |
| 5.15.0-48-generic        | 10        | 0.93%   |
| 5.15.0-46-generic        | 10        | 0.93%   |
| 5.4.0-80-generic         | 9         | 0.83%   |
| 5.11.0-37-generic        | 9         | 0.83%   |
| 5.4.0-54-generic         | 8         | 0.74%   |
| 5.3.0-46-generic         | 8         | 0.74%   |
| 5.3.0-40-generic         | 8         | 0.74%   |
| 5.8.0-48-generic         | 7         | 0.65%   |
| 5.8.0-14-generic         | 7         | 0.65%   |
| 5.15.0-41-generic        | 7         | 0.65%   |
| 5.11.0-40-generic        | 7         | 0.65%   |
| 5.11.0-27-generic        | 7         | 0.65%   |
| 5.4.0-33-generic         | 6         | 0.56%   |
| 5.11.0-7620-generic      | 6         | 0.56%   |
| 5.11.0-43-generic        | 6         | 0.56%   |
| 5.11.0-38-generic        | 6         | 0.56%   |
| 5.0.0-32-generic         | 6         | 0.56%   |
| 5.0.0-23-generic         | 6         | 0.56%   |
| 5.8.0-41-generic         | 5         | 0.46%   |
| 5.4.0-81-generic         | 5         | 0.46%   |
| 5.4.0-65-generic         | 5         | 0.46%   |
| 5.4.0-48-generic         | 5         | 0.46%   |
| 5.4.0-45-generic         | 5         | 0.46%   |
| 5.4.0-37-generic         | 5         | 0.46%   |
| 5.3.0-28-generic         | 5         | 0.46%   |
| 5.3.0-26-generic         | 5         | 0.46%   |
| 5.13.0-41-generic        | 5         | 0.46%   |
| 5.0.0-37-generic         | 5         | 0.46%   |
| 5.0.0-20-generic         | 5         | 0.46%   |
| 5.8.0-63-generic         | 4         | 0.37%   |
| 5.8.0-59-generic         | 4         | 0.37%   |
| 5.8.0-55-generic         | 4         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 196       | 18.85%  |
| 5.11.0  | 69        | 6.63%   |
| 5.8.0   | 61        | 5.87%   |
| 5.15.0  | 57        | 5.48%   |
| 5.3.0   | 51        | 4.9%    |
| 5.13.0  | 49        | 4.71%   |
| 4.15.0  | 49        | 4.71%   |
| 5.16.7  | 47        | 4.52%   |
| 5.0.0   | 44        | 4.23%   |
| 4.18.0  | 32        | 3.08%   |
| 5.10.14 | 30        | 2.88%   |
| 5.10.0  | 21        | 2.02%   |
| 4.19.0  | 13        | 1.25%   |
| 5.17.5  | 7         | 0.67%   |
| 5.16.0  | 6         | 0.58%   |
| 5.14.0  | 6         | 0.58%   |
| 4.4.0   | 6         | 0.58%   |
| 5.9.16  | 5         | 0.48%   |
| 5.16.12 | 5         | 0.48%   |
| 5.8.12  | 4         | 0.38%   |
| 5.18.0  | 4         | 0.38%   |
| 5.15.12 | 4         | 0.38%   |
| 5.14.16 | 4         | 0.38%   |
| 5.11.11 | 4         | 0.38%   |
| 4.9.20  | 4         | 0.38%   |
| 5.9.11  | 3         | 0.29%   |
| 5.9.1   | 3         | 0.29%   |
| 5.8.5   | 3         | 0.29%   |
| 5.19.16 | 3         | 0.29%   |
| 5.19.15 | 3         | 0.29%   |
| 5.19.12 | 3         | 0.29%   |
| 5.18.16 | 3         | 0.29%   |
| 5.17.6  | 3         | 0.29%   |
| 5.17.0  | 3         | 0.29%   |
| 5.15.32 | 3         | 0.29%   |
| 5.14.11 | 3         | 0.29%   |
| 5.13.4  | 3         | 0.29%   |
| 5.11.12 | 3         | 0.29%   |
| 5.10.53 | 3         | 0.29%   |
| 5.10.5  | 3         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 206       | 20.04%  |
| 5.10    | 89        | 8.66%   |
| 5.15    | 81        | 7.88%   |
| 5.11    | 78        | 7.59%   |
| 5.8     | 76        | 7.39%   |
| 5.16    | 68        | 6.61%   |
| 5.13    | 57        | 5.54%   |
| 5.3     | 55        | 5.35%   |
| 4.15    | 49        | 4.77%   |
| 5.0     | 46        | 4.47%   |
| 4.18    | 35        | 3.4%    |
| 5.14    | 22        | 2.14%   |
| 5.17    | 21        | 2.04%   |
| 5.18    | 19        | 1.85%   |
| 4.19    | 18        | 1.75%   |
| 5.19    | 17        | 1.65%   |
| 5.9     | 16        | 1.56%   |
| 5.12    | 12        | 1.17%   |
| 4.9     | 11        | 1.07%   |
| 5.7     | 10        | 0.97%   |
| 5.6     | 10        | 0.97%   |
| 4.4     | 8         | 0.78%   |
| 5.5     | 6         | 0.58%   |
| 5.2     | 3         | 0.29%   |
| 4.14    | 2         | 0.19%   |
| 4.13    | 2         | 0.19%   |
| 4.10    | 2         | 0.19%   |
| 4.1     | 2         | 0.19%   |
| 6.0     | 1         | 0.1%    |
| 5.1     | 1         | 0.1%    |
| 5       | 1         | 0.1%    |
| 4.3     | 1         | 0.1%    |
| 4.17    | 1         | 0.1%    |
| 3.16    | 1         | 0.1%    |
| 3.10    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 913       | 96.61%  |
| i686    | 26        | 2.75%   |
| armv8l  | 3         | 0.32%   |
| aarch64 | 2         | 0.21%   |
| armv7l  | 1         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 409       | 42.03%  |
| KDE5              | 166       | 17.06%  |
| Unknown           | 123       | 12.64%  |
| XFCE              | 76        | 7.81%   |
| X-Cinnamon        | 46        | 4.73%   |
| Pantheon          | 31        | 3.19%   |
| KDE               | 21        | 2.16%   |
| MATE              | 20        | 2.06%   |
| Cinnamon          | 12        | 1.23%   |
| LXQt              | 10        | 1.03%   |
| Deepin            | 8         | 0.82%   |
| Unity             | 7         | 0.72%   |
| Budgie            | 7         | 0.72%   |
| KDE4              | 5         | 0.51%   |
| i3                | 4         | 0.41%   |
| sway              | 3         | 0.31%   |
| ICEWM             | 3         | 0.31%   |
| GNOME Flashback   | 3         | 0.31%   |
| Cutefish          | 3         | 0.31%   |
| bspwm             | 3         | 0.31%   |
| xmonad            | 2         | 0.21%   |
| qtile             | 2         | 0.21%   |
| DWM               | 2         | 0.21%   |
| Yaru:ubuntu:GNOME | 1         | 0.1%    |
| Peux Gnome        | 1         | 0.1%    |
| openbox           | 1         | 0.1%    |
| LXDE              | 1         | 0.1%    |
| Lubuntu           | 1         | 0.1%    |
| lightdm-xsession  | 1         | 0.1%    |
| awesomeminimal    | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 756       | 78.75%  |
| Wayland | 113       | 11.77%  |
| Unknown | 84        | 8.75%   |
| Tty     | 7         | 0.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 504       | 51.8%   |
| SDDM    | 160       | 16.44%  |
| GDM     | 139       | 14.29%  |
| LightDM | 75        | 7.71%   |
| GDM3    | 49        | 5.04%   |
| TDM     | 37        | 3.8%    |
| KDM     | 5         | 0.51%   |
| SLiM    | 2         | 0.21%   |
| Ly      | 1         | 0.1%    |
| LXDM    | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 737       | 76.93%  |
| Unknown | 121       | 12.63%  |
| id_ID   | 67        | 6.99%   |
| en_GB   | 11        | 1.15%   |
| C       | 10        | 1.04%   |
| en_AG   | 3         | 0.31%   |
| en_SG   | 2         | 0.21%   |
| jv_ID   | 1         | 0.1%    |
| it_IT   | 1         | 0.1%    |
| en_IN   | 1         | 0.1%    |
| en_CA   | 1         | 0.1%    |
| en_AU   | 1         | 0.1%    |
| de_CH   | 1         | 0.1%    |
| Default | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 489       | 50.62%  |
| BIOS | 477       | 49.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 749       | 78.18%  |
| Overlay | 73        | 7.62%   |
| Btrfs   | 73        | 7.62%   |
| Unknown | 44        | 4.59%   |
| Xfs     | 8         | 0.84%   |
| Zfs     | 4         | 0.42%   |
| Ext2    | 4         | 0.42%   |
| Ext3    | 2         | 0.21%   |
| F2fs    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 529       | 55.28%  |
| GPT     | 298       | 31.14%  |
| MBR     | 130       | 13.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 838       | 87.66%  |
| Yes       | 118       | 12.34%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 546       | 56.76%  |
| Yes       | 416       | 43.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 194       | 20.53%  |
| Lenovo                  | 191       | 20.21%  |
| Hewlett-Packard         | 126       | 13.33%  |
| Acer                    | 103       | 10.9%   |
| Dell                    | 69        | 7.3%    |
| MSI                     | 43        | 4.55%   |
| Gigabyte Technology     | 36        | 3.81%   |
| ASRock                  | 29        | 3.07%   |
| Toshiba                 | 21        | 2.22%   |
| Biostar                 | 17        | 1.8%    |
| ECS                     | 16        | 1.69%   |
| Intel                   | 15        | 1.59%   |
| Apple                   | 14        | 1.48%   |
| Sony                    | 8         | 0.85%   |
| AXIOO                   | 8         | 0.85%   |
| Unknown                 | 8         | 0.85%   |
| Fujitsu                 | 7         | 0.74%   |
| Clevo                   | 3         | 0.32%   |
| Supermicro              | 2         | 0.21%   |
| Samsung Electronics     | 2         | 0.21%   |
| Pegatron                | 2         | 0.21%   |
| LORD ELECTRONICS        | 2         | 0.21%   |
| Infinix                 | 2         | 0.21%   |
| HUAWEI                  | 2         | 0.21%   |
| Foxconn                 | 2         | 0.21%   |
| ZYREX COMPUTER SYSTEMS  | 1         | 0.11%   |
| Wearnes                 | 1         | 0.11%   |
| Timi                    | 1         | 0.11%   |
| SPECTRUM UTAMA          | 1         | 0.11%   |
| Sole                    | 1         | 0.11%   |
| Raspberry Pi Foundation | 1         | 0.11%   |
| Quanta                  | 1         | 0.11%   |
| Qualcomm Technologies   | 1         | 0.11%   |
| Phoenix/SiS             | 1         | 0.11%   |
| Panasonic               | 1         | 0.11%   |
| OEM                     | 1         | 0.11%   |
| Nvidia                  | 1         | 0.11%   |
| Notebook                | 1         | 0.11%   |
| NEC Computers           | 1         | 0.11%   |
| Koloe                   | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 13        | 1.38%   |
| Lenovo G40-45 80E1                      | 9         | 0.95%   |
| HP Notebook                             | 8         | 0.85%   |
| Lenovo IdeaPad 330-14AST 81D5           | 7         | 0.74%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 6         | 0.63%   |
| HP 14                                   | 6         | 0.63%   |
| Acer Aspire 4752                        | 6         | 0.63%   |
| Lenovo IdeaPad S340-14API 81NB          | 5         | 0.53%   |
| Lenovo G400 20235                       | 5         | 0.53%   |
| HP Pavilion g4                          | 5         | 0.53%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 5         | 0.53%   |
| ASUS All Series                         | 5         | 0.53%   |
| Apple MacBookPro12,1                    | 5         | 0.53%   |
| Lenovo Yoga C640-13IML 81UE             | 4         | 0.42%   |
| HP Pavilion 14                          | 4         | 0.42%   |
| HP Laptop 14-bw0xx                      | 4         | 0.42%   |
| HP Laptop 14-bs0xx                      | 4         | 0.42%   |
| HP 1000                                 | 4         | 0.42%   |
| Dell OptiPlex 7010                      | 4         | 0.42%   |
| ASUS X455YA                             | 4         | 0.42%   |
| ASUS X453SA                             | 4         | 0.42%   |
| Acer Aspire E5-475G                     | 4         | 0.42%   |
| Acer Aspire 4750                        | 4         | 0.42%   |
| Lenovo ThinkBook 14 G3 ACL 21A2         | 3         | 0.32%   |
| Lenovo IdeaPad C340-14IWL 81N4          | 3         | 0.32%   |
| Lenovo IdeaPad 320-14ISK 80XG           | 3         | 0.32%   |
| Lenovo IdeaPad 320-14AST 80XU           | 3         | 0.32%   |
| Lenovo G400s 20244                      | 3         | 0.32%   |
| HP Laptop 14-cm0xxx                     | 3         | 0.32%   |
| ECS H61H2-MV                            | 3         | 0.32%   |
| ASUS X455LD                             | 3         | 0.32%   |
| ASUS X450EA                             | 3         | 0.32%   |
| ASUS X442URR                            | 3         | 0.32%   |
| ASUS X441BA                             | 3         | 0.32%   |
| ASUS X200MA                             | 3         | 0.32%   |
| ASUS VivoBook_ASUSLaptop X412DA_A412DA  | 3         | 0.32%   |
| ASUS P5KPL-AM SE                        | 3         | 0.32%   |
| ASUS K43E                               | 3         | 0.32%   |
| ASUS GL553VD                            | 3         | 0.32%   |
| ASRock B450 Pro4                        | 3         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 66        | 6.98%   |
| Acer Aspire        | 63        | 6.67%   |
| Lenovo ThinkPad    | 55        | 5.82%   |
| ASUS VivoBook      | 27        | 2.86%   |
| HP Pavilion        | 24        | 2.54%   |
| HP Laptop          | 23        | 2.43%   |
| Dell Latitude      | 22        | 2.33%   |
| Dell Inspiron      | 16        | 1.69%   |
| Toshiba Satellite  | 15        | 1.59%   |
| Acer Swift         | 13        | 1.38%   |
| Unknown            | 13        | 1.38%   |
| HP EliteBook       | 12        | 1.27%   |
| Dell OptiPlex      | 12        | 1.27%   |
| Lenovo Yoga        | 10        | 1.06%   |
| Dell Vostro        | 10        | 1.06%   |
| Lenovo ThinkCentre | 9         | 0.95%   |
| Lenovo G40-45      | 9         | 0.95%   |
| HP Notebook        | 8         | 0.85%   |
| HP ENVY            | 8         | 0.85%   |
| Acer Nitro         | 8         | 0.85%   |
| Lenovo ThinkBook   | 7         | 0.74%   |
| ASUS TUF           | 7         | 0.74%   |
| HP Compaq          | 6         | 0.63%   |
| HP 14              | 6         | 0.63%   |
| ASUS ROG           | 6         | 0.63%   |
| Lenovo G400        | 5         | 0.53%   |
| HP ProBook         | 5         | 0.53%   |
| ASUS PRIME         | 5         | 0.53%   |
| ASUS P5KPL-AM      | 5         | 0.53%   |
| ASUS All           | 5         | 0.53%   |
| Apple MacBookPro12 | 5         | 0.53%   |
| Toshiba PORTEGE    | 4         | 0.42%   |
| MSI Modern         | 4         | 0.42%   |
| HP ProLiant        | 4         | 0.42%   |
| HP 1000            | 4         | 0.42%   |
| ASUS ZenBook       | 4         | 0.42%   |
| ASUS X455YA        | 4         | 0.42%   |
| ASUS X453SA        | 4         | 0.42%   |
| ASRock A320M-HDV   | 4         | 0.42%   |
| Lenovo Legion      | 3         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 104       | 11.01%  |
| 2019    | 97        | 10.26%  |
| 2018    | 92        | 9.74%   |
| 2011    | 87        | 9.21%   |
| 2012    | 78        | 8.25%   |
| 2014    | 71        | 7.51%   |
| 2020    | 65        | 6.88%   |
| 2017    | 61        | 6.46%   |
| 2015    | 56        | 5.93%   |
| 2010    | 53        | 5.61%   |
| 2016    | 50        | 5.29%   |
| 2021    | 47        | 4.97%   |
| 2009    | 29        | 3.07%   |
| 2008    | 29        | 3.07%   |
| 2007    | 14        | 1.48%   |
| Unknown | 5         | 0.53%   |
| 2022    | 4         | 0.42%   |
| 2006    | 3         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 651       | 68.89%  |
| Desktop        | 237       | 25.08%  |
| Convertible    | 23        | 2.43%   |
| All in one     | 10        | 1.06%   |
| Server         | 10        | 1.06%   |
| Mini pc        | 5         | 0.53%   |
| Phone          | 4         | 0.42%   |
| Tablet         | 3         | 0.32%   |
| System on chip | 2         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 880       | 92.44%  |
| Enabled  | 72        | 7.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 945       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 280       | 29.38%  |
| 3.01-4.0        | 255       | 26.76%  |
| 8.01-16.0       | 167       | 17.52%  |
| 16.01-24.0      | 119       | 12.49%  |
| 1.01-2.0        | 78        | 8.18%   |
| 32.01-64.0      | 20        | 2.1%    |
| 2.01-3.0        | 13        | 1.36%   |
| 24.01-32.0      | 7         | 0.73%   |
| 64.01-256.0     | 7         | 0.73%   |
| 0.51-1.0        | 6         | 0.63%   |
| More than 256.0 | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 390       | 37.83%  |
| 2.01-3.0   | 292       | 28.32%  |
| 3.01-4.0   | 133       | 12.9%   |
| 4.01-8.0   | 123       | 11.93%  |
| 0.51-1.0   | 68        | 6.6%    |
| 8.01-16.0  | 16        | 1.55%   |
| 0.01-0.5   | 6         | 0.58%   |
| 16.01-24.0 | 2         | 0.19%   |
| Unknown    | 1         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 650       | 67.43%  |
| 2       | 244       | 25.31%  |
| 3       | 44        | 4.56%   |
| 4       | 13        | 1.35%   |
| 0       | 8         | 0.83%   |
| 5       | 3         | 0.31%   |
| 15      | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 602       | 62.97%  |
| Yes       | 354       | 37.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 807       | 85.31%  |
| No        | 139       | 14.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 811       | 85.37%  |
| No        | 139       | 14.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 580       | 60.99%  |
| No        | 371       | 39.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Indonesia | 945       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Jakarta         | 291       | 28.78%  |
| Surabaya        | 100       | 9.89%   |
| Bandung         | 79        | 7.81%   |
| Yogyakarta      | 38        | 3.76%   |
| Semarang        | 33        | 3.26%   |
| Bogor           | 31        | 3.07%   |
| Tangerang       | 29        | 2.87%   |
| Bekasi          | 24        | 2.37%   |
| Medan           | 21        | 2.08%   |
| Malang          | 20        | 1.98%   |
| Denpasar        | 18        | 1.78%   |
| South Tangerang | 16        | 1.58%   |
| Makassar        | 14        | 1.38%   |
| Palembang       | 12        | 1.19%   |
| Banjarmasin     | 11        | 1.09%   |
| Tasikmalaya     | 9         | 0.89%   |
| Sleman          | 9         | 0.89%   |
| Gresik          | 9         | 0.89%   |
| Depok           | 9         | 0.89%   |
| Banda Aceh      | 8         | 0.79%   |
| Surakarta       | 6         | 0.59%   |
| Samarinda       | 6         | 0.59%   |
| Pontianak       | 6         | 0.59%   |
| Mataram         | 6         | 0.59%   |
| Brebes          | 6         | 0.59%   |
| Blitar          | 6         | 0.59%   |
| Batam           | 6         | 0.59%   |
| Pekan Baru      | 5         | 0.49%   |
| Cirebon         | 5         | 0.49%   |
| Balikpapan      | 5         | 0.49%   |
| Tanjung Pinang  | 4         | 0.4%    |
| Pasuruan        | 4         | 0.4%    |
| Bantabantaeng   | 4         | 0.4%    |
| Tegal           | 3         | 0.3%    |
| Sukabumi        | 3         | 0.3%    |
| South Jakarta   | 3         | 0.3%    |
| Salatiga        | 3         | 0.3%    |
| Purwokerto      | 3         | 0.3%    |
| Magelang        | 3         | 0.3%    |
| Kudus           | 3         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 270       | 347    | 21.86%  |
| WDC                   | 187       | 244    | 15.14%  |
| Samsung Electronics   | 111       | 143    | 8.99%   |
| Toshiba               | 102       | 112    | 8.26%   |
| HGST                  | 54        | 60     | 4.37%   |
| Hitachi               | 49        | 56     | 3.97%   |
| Unknown               | 44        | 57     | 3.56%   |
| SanDisk               | 40        | 51     | 3.24%   |
| Kingston              | 30        | 38     | 2.43%   |
| V-GeN                 | 29        | 31     | 2.35%   |
| Intel                 | 29        | 44     | 2.35%   |
| A-DATA Technology     | 29        | 32     | 2.35%   |
| SK hynix              | 25        | 30     | 2.02%   |
| Micron Technology     | 18        | 20     | 1.46%   |
| MidasForce            | 14        | 15     | 1.13%   |
| China                 | 14        | 14     | 1.13%   |
| JMicron Technology    | 12        | 13     | 0.97%   |
| Apacer                | 12        | 13     | 0.97%   |
| Fujitsu               | 10        | 11     | 0.81%   |
| Silicon Motion        | 9         | 10     | 0.73%   |
| Patriot               | 9         | 13     | 0.73%   |
| Apple                 | 8         | 9      | 0.65%   |
| Unknown               | 8         | 8      | 0.65%   |
| Transcend             | 6         | 10     | 0.49%   |
| Team                  | 6         | 9      | 0.49%   |
| Pioneer               | 6         | 6      | 0.49%   |
| Crucial               | 6         | 7      | 0.49%   |
| XPG                   | 5         | 8      | 0.4%    |
| RX7                   | 4         | 4      | 0.32%   |
| Phison                | 4         | 5      | 0.32%   |
| EYOTA                 | 4         | 4      | 0.32%   |
| VISIPRO               | 3         | 3      | 0.24%   |
| Smart                 | 3         | 3      | 0.24%   |
| Realtek Semiconductor | 3         | 3      | 0.24%   |
| OCZ                   | 3         | 3      | 0.24%   |
| Maxtor                | 3         | 3      | 0.24%   |
| LITEONIT              | 3         | 3      | 0.24%   |
| LITEON                | 3         | 4      | 0.24%   |
| Hewlett-Packard       | 3         | 3      | 0.24%   |
| GALAX                 | 3         | 3      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 32        | 2.44%   |
| Seagate ST500LT012-1DG142 500GB    | 31        | 2.36%   |
| Toshiba MQ01ABF050 500GB           | 17        | 1.3%    |
| Toshiba MQ01ABD100 1TB             | 17        | 1.3%    |
| Seagate ST500DM002-1BD142 500GB    | 17        | 1.3%    |
| A-DATA SU650 120GB SSD             | 17        | 1.3%    |
| Seagate ST3500312CS 500GB          | 16        | 1.22%   |
| Toshiba MQ04ABF100 1TB             | 15        | 1.14%   |
| HGST HTS545050A7E680 500GB         | 14        | 1.07%   |
| Seagate ST9500325AS 500GB          | 10        | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 9         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB     | 9         | 0.69%   |
| SanDisk NVMe SSD Drive 512GB       | 9         | 0.69%   |
| Samsung SSD 850 EVO 250GB          | 9         | 0.69%   |
| Intel SSDPEKNW512G8 512GB          | 9         | 0.69%   |
| Hitachi HTS545050A7E380 500GB      | 9         | 0.69%   |
| HGST HTS725050A7E630 500GB         | 9         | 0.69%   |
| HGST HTS721010A9E630 1TB           | 9         | 0.69%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 8         | 0.61%   |
| Seagate ST9320325AS 320GB          | 8         | 0.61%   |
| Seagate ST3250318AS 250GB          | 8         | 0.61%   |
| Hitachi HTS543232A7A384 320GB      | 8         | 0.61%   |
| Unknown                            | 8         | 0.61%   |
| Seagate ST500LT012-9WS142 500GB    | 7         | 0.53%   |
| Seagate ST1000LM049-2GH172 1TB     | 7         | 0.53%   |
| Samsung SSD 860 EVO 250GB          | 7         | 0.53%   |
| JMicron Generic 500GB              | 7         | 0.53%   |
| Intel NVMe SSD Drive 512GB         | 7         | 0.53%   |
| HGST HTS545050A7E380 500GB         | 7         | 0.53%   |
| Apacer AS340 240GB SSD             | 7         | 0.53%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 6         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB           | 6         | 0.46%   |
| Unknown MMC Card  32GB             | 6         | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB     | 6         | 0.46%   |
| Samsung SSD 860 EVO 500GB          | 6         | 0.46%   |
| Samsung NVMe SSD Drive 512GB       | 6         | 0.46%   |
| HGST HTS541010A9E680 1TB           | 6         | 0.46%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 5         | 0.38%   |
| WDC WD10JPCX-24UE4T0 1TB           | 5         | 0.38%   |
| Unknown MMC Card  128GB            | 5         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 268       | 341    | 41.23%  |
| WDC                 | 151       | 195    | 23.23%  |
| Toshiba             | 92        | 102    | 14.15%  |
| HGST                | 54        | 60     | 8.31%   |
| Hitachi             | 49        | 56     | 7.54%   |
| Samsung Electronics | 12        | 12     | 1.85%   |
| Fujitsu             | 8         | 8      | 1.23%   |
| Unknown             | 5         | 5      | 0.77%   |
| Maxtor              | 3         | 3      | 0.46%   |
| Hewlett-Packard     | 2         | 2      | 0.31%   |
| Apple               | 2         | 2      | 0.31%   |
| USB3.0              | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| HGST HTS            | 1         | 3      | 0.15%   |
| ExcelStor           | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 76     | 19.11%  |
| WDC                 | 23        | 30     | 7.32%   |
| SanDisk             | 23        | 31     | 7.32%   |
| A-DATA Technology   | 23        | 25     | 7.32%   |
| Kingston            | 17        | 19     | 5.41%   |
| V-GeN               | 14        | 16     | 4.46%   |
| MidasForce          | 14        | 15     | 4.46%   |
| China               | 14        | 14     | 4.46%   |
| Apacer              | 12        | 13     | 3.82%   |
| Patriot             | 9         | 13     | 2.87%   |
| Intel               | 8         | 12     | 2.55%   |
| Pioneer             | 6         | 6      | 1.91%   |
| Crucial             | 6         | 7      | 1.91%   |
| Unknown             | 6         | 6      | 1.91%   |
| Seagate             | 5         | 5      | 1.59%   |
| Apple               | 5         | 5      | 1.59%   |
| Transcend           | 4         | 7      | 1.27%   |
| Team                | 4         | 7      | 1.27%   |
| VISIPRO             | 3         | 3      | 0.96%   |
| Unknown             | 3         | 4      | 0.96%   |
| Toshiba             | 3         | 3      | 0.96%   |
| OCZ                 | 3         | 3      | 0.96%   |
| Micron Technology   | 3         | 4      | 0.96%   |
| LITEONIT            | 3         | 3      | 0.96%   |
| LITEON              | 3         | 4      | 0.96%   |
| GALAX               | 3         | 3      | 0.96%   |
| TO Exter            | 2         | 2      | 0.64%   |
| SPCC                | 2         | 2      | 0.64%   |
| Smart               | 2         | 2      | 0.64%   |
| SK hynix            | 2         | 3      | 0.64%   |
| RX7                 | 2         | 2      | 0.64%   |
| Memory              | 2         | 2      | 0.64%   |
| Lexar               | 2         | 2      | 0.64%   |
| EYOTA               | 2         | 2      | 0.64%   |
| Biostar             | 2         | 3      | 0.64%   |
| XSTAR               | 1         | 1      | 0.32%   |
| WellcommMaster      | 1         | 1      | 0.32%   |
| Wellcomm            | 1         | 1      | 0.32%   |
| Verbatim            | 1         | 1      | 0.32%   |
| Vaseky              | 1         | 2      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 598       | 792    | 51.73%  |
| SSD     | 291       | 377    | 25.17%  |
| NVMe    | 200       | 260    | 17.3%   |
| Unknown | 36        | 43     | 3.11%   |
| MMC     | 31        | 42     | 2.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 775       | 1175   | 74.59%  |
| NVMe | 192       | 249    | 18.48%  |
| SAS  | 41        | 48     | 3.95%   |
| MMC  | 31        | 42     | 2.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 580       | 803    | 66.67%  |
| 0.51-1.0   | 240       | 299    | 27.59%  |
| 1.01-2.0   | 38        | 53     | 4.37%   |
| 3.01-4.0   | 6         | 8      | 0.69%   |
| 2.01-3.0   | 4         | 4      | 0.46%   |
| 4.01-10.0  | 2         | 2      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 270       | 27.58%  |
| 251-500        | 243       | 24.82%  |
| 51-100         | 115       | 11.75%  |
| 501-1000       | 105       | 10.73%  |
| 1-20           | 77        | 7.87%   |
| 1001-2000      | 64        | 6.54%   |
| 21-50          | 62        | 6.33%   |
| Unknown        | 16        | 1.63%   |
| More than 3000 | 14        | 1.43%   |
| 2001-3000      | 13        | 1.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 412       | 40.35%  |
| 21-50          | 180       | 17.63%  |
| 51-100         | 126       | 12.34%  |
| 101-250        | 121       | 11.85%  |
| 251-500        | 83        | 8.13%   |
| 501-1000       | 58        | 5.68%   |
| 1001-2000      | 17        | 1.67%   |
| Unknown        | 16        | 1.57%   |
| More than 3000 | 5         | 0.49%   |
| 2001-3000      | 3         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB | 6         | 8      | 4.58%   |
| HGST HTS545050A7E680 500GB      | 5         | 5      | 3.82%   |
| Seagate ST9500325AS 500GB       | 4         | 4      | 3.05%   |
| WDC WD5000LPVX-22V0TT0 500GB    | 3         | 3      | 2.29%   |
| Toshiba MQ01ABD032 320GB        | 3         | 3      | 2.29%   |
| Seagate ST500LT012-9WS142 500GB | 3         | 3      | 2.29%   |
| Seagate ST500LT012-1DG142 500GB | 3         | 3      | 2.29%   |
| Seagate ST1000LM035-1RK172 1TB  | 3         | 3      | 2.29%   |
| Hitachi HTS545050A7E380 500GB   | 3         | 3      | 2.29%   |
| WDC WD10JPCX-24UE4T0 1TB        | 2         | 2      | 1.53%   |
| WDC WD10EZEX-08M2NA0 1TB        | 2         | 2      | 1.53%   |
| Toshiba MK3265GSX 320GB         | 2         | 2      | 1.53%   |
| Seagate ST9500420AS 500GB       | 2         | 2      | 1.53%   |
| Seagate ST9250410AS 250GB       | 2         | 2      | 1.53%   |
| Seagate ST1000LX015-1U7172 1TB  | 2         | 3      | 1.53%   |
| Hitachi HTS545016B9A300 160GB   | 2         | 2      | 1.53%   |
| HGST HTS725050A7E630 500GB      | 2         | 2      | 1.53%   |
| HGST HTS545050A7E380 500GB      | 2         | 2      | 1.53%   |
| WellcommMaster 128GB SSD        | 1         | 1      | 0.76%   |
| WDC WD7500BPVT-55HXZT4 752GB    | 1         | 1      | 0.76%   |
| WDC WD6400AADS-00M2B0 640GB     | 1         | 1      | 0.76%   |
| WDC WD5000LPVX-80V0TT0 500GB    | 1         | 1      | 0.76%   |
| WDC WD5000LPCX-22VHAT0 500GB    | 1         | 1      | 0.76%   |
| WDC WD5000L 500GB               | 1         | 1      | 0.76%   |
| WDC WD5000BPVT-60HXZT3 500GB    | 1         | 1      | 0.76%   |
| WDC WD5000BPVT-08HXZT3 500GB    | 1         | 1      | 0.76%   |
| WDC WD5000AZLX-00JKKA0 500GB    | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-08ERMA0 500GB    | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-083CA1 500GB     | 1         | 1      | 0.76%   |
| WDC WD5000AAKX-001CA0 500GB     | 1         | 1      | 0.76%   |
| WDC WD5000AACS-00G8B0 500GB     | 1         | 1      | 0.76%   |
| WDC WD40EZRX-00SPEB0 4TB        | 1         | 1      | 0.76%   |
| WDC WD3200JS-63PDB1 320GB       | 1         | 1      | 0.76%   |
| WDC WD3200BPVT-00HXZT1 320GB    | 1         | 1      | 0.76%   |
| WDC WD3200BEKT-60V5T1 320GB     | 1         | 1      | 0.76%   |
| WDC WD3200AVJS-63B6A0 320GB     | 1         | 1      | 0.76%   |
| WDC WD3200AAJS-08B4A0 320GB     | 1         | 1      | 0.76%   |
| WDC WD30EZRZ-00Z5HB0 3TB        | 1         | 1      | 0.76%   |
| WDC WD30EFRX-68AX9N0 3TB        | 1         | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 49     | 29.84%  |
| WDC                 | 28        | 33     | 22.58%  |
| Hitachi             | 14        | 14     | 11.29%  |
| Toshiba             | 13        | 14     | 10.48%  |
| HGST                | 11        | 11     | 8.87%   |
| Samsung Electronics | 5         | 5      | 4.03%   |
| SanDisk             | 3         | 3      | 2.42%   |
| Micron Technology   | 2         | 2      | 1.61%   |
| China               | 2         | 2      | 1.61%   |
| A-DATA Technology   | 2         | 2      | 1.61%   |
| WellcommMaster      | 1         | 1      | 0.81%   |
| VISIPRO             | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 1      | 0.81%   |
| Kingston            | 1         | 1      | 0.81%   |
| Intel               | 1         | 1      | 0.81%   |
| Crucial             | 1         | 1      | 0.81%   |
| Apacer              | 1         | 2      | 0.81%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 49     | 34.58%  |
| WDC                 | 28        | 33     | 26.17%  |
| Hitachi             | 14        | 14     | 13.08%  |
| Toshiba             | 13        | 14     | 12.15%  |
| HGST                | 11        | 11     | 10.28%  |
| Samsung Electronics | 3         | 3      | 2.8%    |
| Maxtor              | 1         | 1      | 0.93%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 101       | 125    | 86.32%  |
| SSD  | 15        | 17     | 12.82%  |
| NVMe | 1         | 1      | 0.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| WDC WD5000BPVT-60HXZT1 500GB  | 1         | 1      | 33.33%  |
| Seagate ST3250318AS 250GB     | 1         | 1      | 33.33%  |
| Hitachi HTS545050A7E380 500GB | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| Hitachi | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 560       | 880    | 55.12%  |
| Works    | 336       | 488    | 33.07%  |
| Malfunc  | 117       | 143    | 11.52%  |
| Failed   | 3         | 3      | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 662       | 61.01%  |
| AMD                              | 203       | 18.71%  |
| Samsung Electronics              | 47        | 4.33%   |
| SanDisk                          | 32        | 2.95%   |
| SK hynix                         | 22        | 2.03%   |
| Micron Technology                | 15        | 1.38%   |
| Silicon Motion                   | 13        | 1.2%    |
| Kingston Technology Company      | 13        | 1.2%    |
| ADATA Technology                 | 13        | 1.2%    |
| ASMedia Technology               | 9         | 0.83%   |
| Phison Electronics               | 8         | 0.74%   |
| Toshiba America Info Systems     | 6         | 0.55%   |
| Realtek Semiconductor            | 5         | 0.46%   |
| JMicron Technology               | 5         | 0.46%   |
| VIA Technologies                 | 4         | 0.37%   |
| Union Memory (Shenzhen)          | 4         | 0.37%   |
| Silicon Integrated Systems [SiS] | 4         | 0.37%   |
| Nvidia                           | 4         | 0.37%   |
| Hewlett-Packard                  | 4         | 0.37%   |
| KIOXIA                           | 3         | 0.28%   |
| Marvell Technology Group         | 2         | 0.18%   |
| LSI Logic / Symbios Logic        | 2         | 0.18%   |
| Adaptec                          | 2         | 0.18%   |
| Lenovo                           | 1         | 0.09%   |
| Broadcom / LSI                   | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 163       | 13.13%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 67        | 5.4%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 59        | 4.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 46        | 3.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 39        | 3.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 39        | 3.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 34        | 2.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 32        | 2.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 28        | 2.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24        | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 24        | 1.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 21        | 1.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18        | 1.45%   |
| Samsung NVMe SSD Controller 980                                                         | 17        | 1.37%   |
| Intel SSD 660P Series                                                                   | 17        | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 17        | 1.37%   |
| Micron Non-Volatile memory controller                                                   | 15        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 14        | 1.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 14        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 13        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13        | 1.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 12        | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 12        | 0.97%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 12        | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 11        | 0.89%   |
| AMD FCH IDE Controller                                                                  | 11        | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 10        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 10        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10        | 0.81%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 10        | 0.81%   |
| SK hynix BC511                                                                          | 9         | 0.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 9         | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 9         | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9         | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 9         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 744       | 66.13%  |
| NVMe | 192       | 17.07%  |
| IDE  | 130       | 11.56%  |
| RAID | 55        | 4.89%   |
| SAS  | 3         | 0.27%   |
| SCSI | 1         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 705       | 74.6%   |
| AMD      | 234       | 24.76%  |
| QUALCOMM | 3         | 0.32%   |
| ARM      | 3         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.37%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 1.37%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 12        | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 1.16%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 11        | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.95%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 8         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 8         | 0.85%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 8         | 0.85%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.85%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 8         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.74%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 7         | 0.74%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.74%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 7         | 0.74%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 7         | 0.74%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 7         | 0.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 7         | 0.74%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 7         | 0.74%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 7         | 0.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.63%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.63%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 0.63%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.63%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 6         | 0.63%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 0.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 0.63%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 5         | 0.53%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.53%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 5         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 235       | 24.84%  |
| Intel Core i7           | 130       | 13.74%  |
| Intel Core i3           | 130       | 13.74%  |
| AMD Ryzen 5             | 55        | 5.81%   |
| Intel Celeron           | 52        | 5.5%    |
| Intel Core 2 Duo        | 46        | 4.86%   |
| Other                   | 40        | 4.23%   |
| AMD Ryzen 3             | 26        | 2.75%   |
| Intel Pentium           | 24        | 2.54%   |
| AMD A8                  | 23        | 2.43%   |
| AMD Ryzen 7             | 17        | 1.8%    |
| Intel Xeon              | 16        | 1.69%   |
| Intel Atom              | 13        | 1.37%   |
| AMD A4                  | 13        | 1.37%   |
| AMD A6                  | 12        | 1.27%   |
| Intel Pentium Dual-Core | 10        | 1.06%   |
| Intel Core 2 Quad       | 8         | 0.85%   |
| AMD E1                  | 8         | 0.85%   |
| AMD A10                 | 7         | 0.74%   |
| Intel Genuine           | 6         | 0.63%   |
| AMD Ryzen 9             | 6         | 0.63%   |
| AMD FX                  | 6         | 0.63%   |
| AMD E                   | 6         | 0.63%   |
| AMD Athlon II X2        | 6         | 0.63%   |
| Intel Pentium Dual      | 5         | 0.53%   |
| AMD E2                  | 5         | 0.53%   |
| Intel Core 2            | 4         | 0.42%   |
| AMD Phenom II X6        | 4         | 0.42%   |
| AMD Athlon              | 4         | 0.42%   |
| QUALCOMM AArch64        | 3         | 0.32%   |
| AMD Phenom II X4        | 3         | 0.32%   |
| AMD C-60                | 3         | 0.32%   |
| Intel Pentium Silver    | 2         | 0.21%   |
| AMD Ryzen 5 PRO         | 2         | 0.21%   |
| AMD Athlon X4           | 2         | 0.21%   |
| AMD A12                 | 2         | 0.21%   |
| Intel Xeon Silver       | 1         | 0.11%   |
| Intel Pentium Gold      | 1         | 0.11%   |
| Intel Pentium D         | 1         | 0.11%   |
| Intel Core 2 Extreme    | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 543       | 57.4%   |
| 4      | 282       | 29.81%  |
| 6      | 69        | 7.29%   |
| 8      | 28        | 2.96%   |
| 1      | 13        | 1.37%   |
| 12     | 4         | 0.42%   |
| 10     | 2         | 0.21%   |
| 3      | 2         | 0.21%   |
| 44     | 1         | 0.11%   |
| 16     | 1         | 0.11%   |
| 14     | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 935       | 98.94%  |
| 2      | 8         | 0.85%   |
| 3      | 2         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 617       | 65.29%  |
| 1      | 328       | 34.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 920       | 97.35%  |
| Unknown        | 20        | 2.12%   |
| 32-bit         | 4         | 0.42%   |
| 64-bit         | 1         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 142       | 14.58%  |
| 0x206a7    | 79        | 8.11%   |
| 0x306a9    | 70        | 7.19%   |
| 0x1067a    | 42        | 4.31%   |
| 0x306c3    | 38        | 3.9%    |
| 0x40651    | 35        | 3.59%   |
| 0x306d4    | 28        | 2.87%   |
| 0x906ea    | 25        | 2.57%   |
| 0x806ec    | 25        | 2.57%   |
| 0x806e9    | 24        | 2.46%   |
| 0x806ea    | 23        | 2.36%   |
| 0x20655    | 20        | 2.05%   |
| 0x08108109 | 18        | 1.85%   |
| 0x06006705 | 18        | 1.85%   |
| 0x906e9    | 16        | 1.64%   |
| 0x406e3    | 16        | 1.64%   |
| 0x806eb    | 14        | 1.44%   |
| 0x08108102 | 14        | 1.44%   |
| 0x806c1    | 13        | 1.33%   |
| 0x6fd      | 13        | 1.33%   |
| 0x0a50000c | 13        | 1.33%   |
| 0x07030105 | 13        | 1.33%   |
| 0x506e3    | 11        | 1.13%   |
| 0x20652    | 11        | 1.13%   |
| 0x706e5    | 10        | 1.03%   |
| 0x406c3    | 10        | 1.03%   |
| 0x0810100b | 10        | 1.03%   |
| 0x06001119 | 10        | 1.03%   |
| 0x30678    | 9         | 0.92%   |
| 0x10676    | 8         | 0.82%   |
| 0x08600104 | 8         | 0.82%   |
| 0x6fb      | 7         | 0.72%   |
| 0x406c4    | 7         | 0.72%   |
| 0x08101007 | 7         | 0.72%   |
| 0x03000027 | 7         | 0.72%   |
| 0x706a8    | 6         | 0.62%   |
| 0x08608103 | 6         | 0.62%   |
| 0x0700010f | 6         | 0.62%   |
| 0x05000119 | 6         | 0.62%   |
| 0x706a1    | 5         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 151       | 15.98%  |
| SandyBridge      | 94        | 9.95%   |
| Haswell          | 87        | 9.21%   |
| IvyBridge        | 81        | 8.57%   |
| Penryn           | 52        | 5.5%    |
| Westmere         | 38        | 4.02%   |
| Zen+             | 36        | 3.81%   |
| Broadwell        | 34        | 3.6%    |
| Excavator        | 33        | 3.49%   |
| Skylake          | 31        | 3.28%   |
| Silvermont       | 31        | 3.28%   |
| Zen              | 29        | 3.07%   |
| Core             | 26        | 2.75%   |
| Zen 2            | 22        | 2.33%   |
| Puma             | 20        | 2.12%   |
| Zen 3            | 17        | 1.8%    |
| Unknown          | 16        | 1.69%   |
| Piledriver       | 15        | 1.59%   |
| TigerLake        | 14        | 1.48%   |
| K10              | 14        | 1.48%   |
| CometLake        | 14        | 1.48%   |
| Goldmont plus    | 13        | 1.38%   |
| Bobcat           | 13        | 1.38%   |
| IceLake          | 12        | 1.27%   |
| Jaguar           | 9         | 0.95%   |
| K10 Llano        | 8         | 0.85%   |
| Steamroller      | 7         | 0.74%   |
| Nehalem          | 7         | 0.74%   |
| Bonnell          | 7         | 0.74%   |
| Goldmont         | 4         | 0.42%   |
| Alderlake Hybrid | 3         | 0.32%   |
| P6               | 2         | 0.21%   |
| K8 Hammer        | 2         | 0.21%   |
| Tremont          | 1         | 0.11%   |
| NetBurst         | 1         | 0.11%   |
| Bulldozer        | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 609       | 52.27%  |
| AMD                              | 308       | 26.44%  |
| Nvidia                           | 237       | 20.34%  |
| Matrox Electronics Systems       | 5         | 0.43%   |
| Silicon Integrated Systems [SiS] | 4         | 0.34%   |
| ASPEED Technology                | 2         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 80        | 6.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 54        | 4.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 41        | 3.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 2.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 30        | 2.46%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 2.13%   |
| Intel HD Graphics 620                                                                    | 26        | 2.13%   |
| Intel HD Graphics 5500                                                                   | 26        | 2.13%   |
| Intel UHD Graphics 620                                                                   | 25        | 2.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 23        | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 20        | 1.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 18        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 1.48%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 1.48%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 18        | 1.48%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 16        | 1.31%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 1.31%   |
| AMD Cezanne                                                                              | 16        | 1.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 15        | 1.23%   |
| AMD Renoir                                                                               | 15        | 1.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 12        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 12        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 12        | 0.99%   |
| Intel HD Graphics 630                                                                    | 12        | 0.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 0.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.74%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 9         | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.66%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 8         | 0.66%   |
| Intel HD Graphics 530                                                                    | 8         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 409       | 43.05%  |
| 1 x AMD                | 207       | 21.79%  |
| Intel + Nvidia         | 147       | 15.47%  |
| 1 x Nvidia             | 66        | 6.95%   |
| Intel + AMD            | 46        | 4.84%   |
| 2 x AMD                | 35        | 3.68%   |
| AMD + Nvidia           | 20        | 2.11%   |
| Other                  | 6         | 0.63%   |
| 1 x Matrox             | 5         | 0.53%   |
| 1 x SiS                | 4         | 0.42%   |
| 2 x Nvidia             | 1         | 0.11%   |
| 2 x Intel              | 1         | 0.11%   |
| Nvidia + ASPEED        | 1         | 0.11%   |
| 1 x Intel + 4 x Nvidia | 1         | 0.11%   |
| 1 x ASPEED             | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 811       | 84.39%  |
| Proprietary | 122       | 12.7%   |
| Unknown     | 28        | 2.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 531       | 54.8%   |
| 1.01-2.0   | 169       | 17.44%  |
| 0.01-0.5   | 117       | 12.07%  |
| 0.51-1.0   | 75        | 7.74%   |
| 3.01-4.0   | 53        | 5.47%   |
| 5.01-6.0   | 12        | 1.24%   |
| 7.01-8.0   | 8         | 0.83%   |
| 8.01-16.0  | 3         | 0.31%   |
| 2.01-3.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 170       | 17.62%  |
| Chimei Innolux          | 137       | 14.2%   |
| BOE                     | 107       | 11.09%  |
| LG Display              | 96        | 9.95%   |
| Samsung Electronics     | 93        | 9.64%   |
| Goldstar                | 90        | 9.33%   |
| Dell                    | 40        | 4.15%   |
| Lenovo                  | 25        | 2.59%   |
| Hewlett-Packard         | 20        | 2.07%   |
| AOC                     | 16        | 1.66%   |
| Acer                    | 14        | 1.45%   |
| Philips                 | 13        | 1.35%   |
| Apple                   | 13        | 1.35%   |
| PANDA                   | 11        | 1.14%   |
| ViewSonic               | 10        | 1.04%   |
| InfoVision              | 10        | 1.04%   |
| Sharp                   | 9         | 0.93%   |
| BenQ                    | 8         | 0.83%   |
| Toshiba                 | 7         | 0.73%   |
| LG Electronics          | 7         | 0.73%   |
| InnoLux Display         | 7         | 0.73%   |
| Chi Mei Optoelectronics | 7         | 0.73%   |
| LG Philips              | 5         | 0.52%   |
| Ancor Communications    | 5         | 0.52%   |
| Sony                    | 3         | 0.31%   |
| Quanta Display          | 3         | 0.31%   |
| QCM                     | 3         | 0.31%   |
| Panasonic               | 3         | 0.31%   |
| HannStar                | 3         | 0.31%   |
| CPT                     | 3         | 0.31%   |
| Unknown                 | 2         | 0.21%   |
| Seiko/Epson             | 2         | 0.21%   |
| RTK                     | 2         | 0.21%   |
| GDH                     | 2         | 0.21%   |
| ASUSTek Computer        | 2         | 0.21%   |
| Xiaomi                  | 1         | 0.1%    |
| Tech Concepts           | 1         | 0.1%    |
| TCH                     | 1         | 0.1%    |
| SPC                     | 1         | 0.1%    |
| S2-Tek                  | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 15        | 1.54%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch      | 14        | 1.43%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 13        | 1.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 12        | 1.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 12        | 1.23%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 11        | 1.13%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 11        | 1.13%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch      | 11        | 1.13%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 10        | 1.02%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 9         | 0.92%   |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch        | 9         | 0.92%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 9         | 0.92%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 8         | 0.82%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                 | 8         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 7         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1480 1366x768 309x174mm 14.0-inch      | 7         | 0.72%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch        | 7         | 0.72%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 6         | 0.61%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 6         | 0.61%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 5         | 0.51%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 5         | 0.51%   |
| LG Display LCD Monitor LGD018B 1366x768 309x174mm 14.0-inch          | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch     | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch      | 5         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch      | 5         | 0.51%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                 | 5         | 0.51%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 5         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch | 4         | 0.41%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch              | 4         | 0.41%   |
| LG Display LCD Monitor LGD06B9 1920x1200 286x179mm 13.3-inch         | 4         | 0.41%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch         | 4         | 0.41%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 4         | 0.41%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 4         | 0.41%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 4         | 0.41%   |
| Goldstar HD PLUS GSM5AC5 1600x900 440x250mm 19.9-inch                | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 4         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 446       | 48.01%  |
| 1920x1080 (FHD)    | 306       | 32.94%  |
| 3840x2160 (4K)     | 29        | 3.12%   |
| 1600x900 (HD+)     | 27        | 2.91%   |
| 1280x800 (WXGA)    | 22        | 2.37%   |
| 1440x900 (WXGA+)   | 21        | 2.26%   |
| 1360x768           | 11        | 1.18%   |
| 2560x1440 (QHD)    | 10        | 1.08%   |
| 2560x1600          | 6         | 0.65%   |
| 1920x1200 (WUXGA)  | 6         | 0.65%   |
| 1280x1024 (SXGA)   | 6         | 0.65%   |
| 2560x1080          | 5         | 0.54%   |
| 1024x600           | 4         | 0.43%   |
| 3440x1440          | 3         | 0.32%   |
| 2880x1800          | 3         | 0.32%   |
| 2800x1752          | 3         | 0.32%   |
| 1024x768 (XGA)     | 3         | 0.32%   |
| Unknown            | 3         | 0.32%   |
| 3840x2400          | 2         | 0.22%   |
| 3840x1080          | 2         | 0.22%   |
| 1680x1050 (WSXGA+) | 2         | 0.22%   |
| 640x480            | 1         | 0.11%   |
| 5760x2160          | 1         | 0.11%   |
| 3200x1800 (QHD+)   | 1         | 0.11%   |
| 2966x900           | 1         | 0.11%   |
| 2736x1824          | 1         | 0.11%   |
| 1600x1200          | 1         | 0.11%   |
| 1280x960           | 1         | 0.11%   |
| 1280x720 (HD)      | 1         | 0.11%   |
| 1152x864           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 227       | 23.67%  |
| 14      | 205       | 21.38%  |
| 15      | 168       | 17.52%  |
| 18      | 68        | 7.09%   |
| 21      | 58        | 6.05%   |
| 23      | 47        | 4.9%    |
| 12      | 31        | 3.23%   |
| 19      | 23        | 2.4%    |
| Unknown | 23        | 2.4%    |
| 11      | 20        | 2.09%   |
| 24      | 19        | 1.98%   |
| 27      | 11        | 1.15%   |
| 17      | 11        | 1.15%   |
| 34      | 6         | 0.63%   |
| 31      | 5         | 0.52%   |
| 40      | 4         | 0.42%   |
| 10      | 4         | 0.42%   |
| 66      | 3         | 0.31%   |
| 48      | 3         | 0.31%   |
| 20      | 3         | 0.31%   |
| 16      | 3         | 0.31%   |
| 60      | 2         | 0.21%   |
| 37      | 2         | 0.21%   |
| 22      | 2         | 0.21%   |
| 84      | 1         | 0.1%    |
| 72      | 1         | 0.1%    |
| 65      | 1         | 0.1%    |
| 54      | 1         | 0.1%    |
| 52      | 1         | 0.1%    |
| 46      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 39      | 1         | 0.1%    |
| 35      | 1         | 0.1%    |
| 32      | 1         | 0.1%    |
| 9       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 537       | 56.47%  |
| 401-500     | 148       | 15.56%  |
| 201-300     | 110       | 11.57%  |
| 501-600     | 75        | 7.89%   |
| Unknown     | 23        | 2.42%   |
| 351-400     | 21        | 2.21%   |
| 601-700     | 10        | 1.05%   |
| 1001-1500   | 9         | 0.95%   |
| 801-900     | 8         | 0.84%   |
| 701-800     | 7         | 0.74%   |
| 1501-2000   | 2         | 0.21%   |
| 901-1000    | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 778       | 87.71%  |
| 16/10   | 63        | 7.1%    |
| Unknown | 22        | 2.48%   |
| 21/9    | 7         | 0.79%   |
| 5/4     | 6         | 0.68%   |
| 4/3     | 6         | 0.68%   |
| 0.45    | 3         | 0.34%   |
| 3/2     | 2         | 0.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 385       | 40.15%  |
| 101-110        | 163       | 17%     |
| 201-250        | 107       | 11.16%  |
| 141-150        | 71        | 7.4%    |
| 71-80          | 44        | 4.59%   |
| 151-200        | 41        | 4.28%   |
| 61-70          | 30        | 3.13%   |
| Unknown        | 23        | 2.4%    |
| 51-60          | 20        | 2.09%   |
| More than 1000 | 13        | 1.36%   |
| 351-500        | 13        | 1.36%   |
| 301-350        | 11        | 1.15%   |
| 501-1000       | 9         | 0.94%   |
| 91-100         | 7         | 0.73%   |
| 41-50          | 5         | 0.52%   |
| 251-300        | 5         | 0.52%   |
| 111-120        | 5         | 0.52%   |
| 121-130        | 4         | 0.42%   |
| 131-140        | 3         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 406       | 42.78%  |
| 121-160       | 233       | 24.55%  |
| 51-100        | 211       | 22.23%  |
| 161-240       | 45        | 4.74%   |
| Unknown       | 23        | 2.42%   |
| 1-50          | 18        | 1.9%    |
| More than 240 | 13        | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 826       | 85.95%  |
| 2     | 93        | 9.68%   |
| 0     | 39        | 4.06%   |
| 3     | 3         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 596       | 39.71%  |
| Intel                             | 318       | 21.19%  |
| Qualcomm Atheros                  | 271       | 18.05%  |
| Broadcom                          | 88        | 5.86%   |
| Ralink Technology                 | 34        | 2.27%   |
| TP-Link                           | 27        | 1.8%    |
| Xiaomi                            | 20        | 1.33%   |
| MediaTek                          | 20        | 1.33%   |
| Samsung Electronics               | 16        | 1.07%   |
| Broadcom Limited                  | 16        | 1.07%   |
| Ralink                            | 12        | 0.8%    |
| Qualcomm Atheros Communications   | 12        | 0.8%    |
| Marvell Technology Group          | 9         | 0.6%    |
| OPPO Electronics                  | 7         | 0.47%   |
| JMicron Technology                | 5         | 0.33%   |
| Huawei Technologies               | 5         | 0.33%   |
| ASIX Electronics                  | 5         | 0.33%   |
| Qualcomm                          | 4         | 0.27%   |
| D-Link System                     | 4         | 0.27%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.2%    |
| Nvidia                            | 3         | 0.2%    |
| D-Link                            | 3         | 0.2%    |
| Attansic Technology               | 3         | 0.2%    |
| AboCom Systems                    | 3         | 0.2%    |
| Sierra Wireless                   | 2         | 0.13%   |
| Lenovo                            | 2         | 0.13%   |
| HMD Global                        | 2         | 0.13%   |
| Ericsson Business Mobile Networks | 2         | 0.13%   |
| vivo                              | 1         | 0.07%   |
| VIA Technologies                  | 1         | 0.07%   |
| QinHeng Electronics               | 1         | 0.07%   |
| ICS Advent                        | 1         | 0.07%   |
| IBM                               | 1         | 0.07%   |
| HTC (High Tech Computer)          | 1         | 0.07%   |
| Hewlett-Packard                   | 1         | 0.07%   |
| Foxconn / Hon Hai                 | 1         | 0.07%   |
| ASUSTek Computer                  | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 395       | 22.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 119       | 6.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 65        | 3.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 63        | 3.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 37        | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 1.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 27        | 1.54%   |
| Intel Wireless 8265 / 8275                                        | 25        | 1.43%   |
| Intel Wireless 7265                                               | 22        | 1.26%   |
| Ralink MT7601U Wireless Adapter                                   | 21        | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 19        | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 19        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 17        | 0.97%   |
| Intel Wireless 7260                                               | 17        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 16        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 16        | 0.91%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 15        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                     | 15        | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 14        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                   | 12        | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 12        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 11        | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 11        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.51%   |
| Intel Wireless 8260                                               | 9         | 0.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 9         | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 8         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 256       | 30.26%  |
| Qualcomm Atheros                | 234       | 27.66%  |
| Realtek Semiconductor           | 176       | 20.8%   |
| Broadcom                        | 62        | 7.33%   |
| Ralink Technology               | 34        | 4.02%   |
| TP-Link                         | 23        | 2.72%   |
| MediaTek                        | 15        | 1.77%   |
| Ralink                          | 12        | 1.42%   |
| Qualcomm Atheros Communications | 12        | 1.42%   |
| Broadcom Limited                | 12        | 1.42%   |
| D-Link                          | 3         | 0.35%   |
| AboCom Systems                  | 3         | 0.35%   |
| Sierra Wireless                 | 2         | 0.24%   |
| D-Link System                   | 2         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 65        | 7.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 63        | 7.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 37        | 4.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 32        | 3.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 27        | 3.17%   |
| Intel Wireless 8265 / 8275                                     | 25        | 2.93%   |
| Intel Wireless 7265                                            | 22        | 2.58%   |
| Ralink MT7601U Wireless Adapter                                | 21        | 2.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 2.35%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 19        | 2.23%   |
| Intel Wi-Fi 6 AX200                                            | 19        | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 17        | 2%      |
| Intel Wireless 7260                                            | 17        | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 16        | 1.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 16        | 1.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 15        | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 1.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 15        | 1.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14        | 1.64%   |
| Qualcomm Atheros AR9271 802.11n                                | 12        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 12        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 11        | 1.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 11        | 1.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.06%   |
| Intel Wireless 8260                                            | 9         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 9         | 1.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 8         | 0.94%   |
| Realtek 802.11n WLAN Adapter                                   | 8         | 0.94%   |
| Intel Wireless 3165                                            | 8         | 0.94%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 7         | 0.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.82%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 7         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.7%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 5         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 534       | 60.54%  |
| Intel                            | 135       | 15.31%  |
| Qualcomm Atheros                 | 71        | 8.05%   |
| Broadcom                         | 35        | 3.97%   |
| Xiaomi                           | 20        | 2.27%   |
| Samsung Electronics              | 16        | 1.81%   |
| Marvell Technology Group         | 9         | 1.02%   |
| OPPO Electronics                 | 7         | 0.79%   |
| Broadcom Limited                 | 6         | 0.68%   |
| MediaTek                         | 5         | 0.57%   |
| JMicron Technology               | 5         | 0.57%   |
| ASIX Electronics                 | 5         | 0.57%   |
| TP-Link                          | 4         | 0.45%   |
| Qualcomm                         | 4         | 0.45%   |
| Silicon Integrated Systems [SiS] | 3         | 0.34%   |
| Nvidia                           | 3         | 0.34%   |
| Attansic Technology              | 3         | 0.34%   |
| Lenovo                           | 2         | 0.23%   |
| Huawei Technologies              | 2         | 0.23%   |
| HMD Global                       | 2         | 0.23%   |
| D-Link System                    | 2         | 0.23%   |
| vivo                             | 1         | 0.11%   |
| VIA Technologies                 | 1         | 0.11%   |
| QinHeng Electronics              | 1         | 0.11%   |
| ICS Advent                       | 1         | 0.11%   |
| IBM                              | 1         | 0.11%   |
| HTC (High Tech Computer)         | 1         | 0.11%   |
| Hewlett-Packard                  | 1         | 0.11%   |
| Foxconn / Hon Hai                | 1         | 0.11%   |
| ASUSTek Computer                 | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 395       | 44.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 119       | 13.33%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 3.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 14        | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 1.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 1.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 1.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.78%   |
| OPPO RMX2180                                                      | 7         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 7         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 6         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 0.67%   |
| Intel I211 Gigabit Network Connection                             | 6         | 0.67%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 5         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.45%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.45%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                  | 4         | 0.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.45%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 3         | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.34%   |
| Qualcomm Mobile Router                                            | 3         | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 3         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.34%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 3         | 0.34%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.34%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.34%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 811       | 50%     |
| Ethernet | 806       | 49.69%  |
| Modem    | 5         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 685       | 73.58%  |
| Ethernet | 245       | 26.32%  |
| Modem    | 1         | 0.11%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 574       | 60.61%  |
| 1     | 337       | 35.59%  |
| 0     | 17        | 1.8%    |
| 4     | 9         | 0.95%   |
| 3     | 9         | 0.95%   |
| 8     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 918       | 96.63%  |
| Yes  | 32        | 3.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 195       | 33.51%  |
| Realtek Semiconductor           | 91        | 15.64%  |
| Qualcomm Atheros Communications | 65        | 11.17%  |
| IMC Networks                    | 51        | 8.76%   |
| Lite-On Technology              | 47        | 8.08%   |
| Broadcom                        | 38        | 6.53%   |
| Cambridge Silicon Radio         | 28        | 4.81%   |
| Foxconn / Hon Hai               | 23        | 3.95%   |
| Apple                           | 12        | 2.06%   |
| Toshiba                         | 8         | 1.37%   |
| Dell                            | 5         | 0.86%   |
| Ralink                          | 4         | 0.69%   |
| Hewlett-Packard                 | 4         | 0.69%   |
| Foxconn International           | 3         | 0.52%   |
| Realtek                         | 2         | 0.34%   |
| Micro Star International        | 2         | 0.34%   |
| ASUSTek Computer                | 2         | 0.34%   |
| MediaTek                        | 1         | 0.17%   |
| Chicony Electronics             | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 81        | 13.92%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 55        | 9.45%   |
| Realtek Bluetooth Radio                             | 40        | 6.87%   |
| IMC Networks Bluetooth Device                       | 31        | 5.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 28        | 4.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 4.81%   |
| Realtek  Bluetooth 4.2 Adapter                      | 26        | 4.47%   |
| Intel AX201 Bluetooth                               | 19        | 3.26%   |
| Intel AX200 Bluetooth                               | 19        | 3.26%   |
| Lite-On Bluetooth Device                            | 18        | 3.09%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 2.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 2.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 1.72%   |
| Realtek RTL8723B Bluetooth                          | 9         | 1.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 1.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 1.37%   |
| Realtek RTL8821A Bluetooth                          | 8         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.2%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 7         | 1.2%    |
| Lite-On Wireless_Device                             | 6         | 1.03%   |
| Lite-On Atheros Bluetooth                           | 6         | 1.03%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 1.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.03%   |
| Apple Bluetooth Host Controller                     | 6         | 1.03%   |
| IMC Networks Bluetooth Radio                        | 5         | 0.86%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.86%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.69%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.69%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.69%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.69%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.52%   |
| Foxconn / Hon Hai Acer Module                       | 3         | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.52%   |
| Broadcom BCM20702A0                                 | 3         | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 682       | 61.66%  |
| AMD                              | 269       | 24.32%  |
| Nvidia                           | 113       | 10.22%  |
| Generalplus Technology           | 8         | 0.72%   |
| C-Media Electronics              | 7         | 0.63%   |
| JMTek                            | 5         | 0.45%   |
| Silicon Integrated Systems [SiS] | 4         | 0.36%   |
| Samson Technologies              | 3         | 0.27%   |
| Samsung Electronics              | 2         | 0.18%   |
| Logitech                         | 2         | 0.18%   |
| Creative Labs                    | 2         | 0.18%   |
| Texas Instruments                | 1         | 0.09%   |
| SteelSeries ApS                  | 1         | 0.09%   |
| SAVITECH                         | 1         | 0.09%   |
| Hewlett-Packard                  | 1         | 0.09%   |
| GS3                              | 1         | 0.09%   |
| Creative Technology              | 1         | 0.09%   |
| Cooler Master                    | 1         | 0.09%   |
| Barco Display Systems            | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 97        | 6.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 89        | 6.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 81        | 5.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 72        | 5.09%   |
| AMD FCH Azalia Controller                                                                         | 65        | 4.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 3.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 41        | 2.9%    |
| Intel 8 Series HD Audio Controller                                                                | 41        | 2.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 40        | 2.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 40        | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 39        | 2.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 38        | 2.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 33        | 2.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 31        | 2.19%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 2.19%   |
| Intel Broadwell-U Audio Controller                                                                | 31        | 2.19%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 30        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 29        | 2.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 27        | 1.91%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 23        | 1.63%   |
| AMD High Definition Audio Controller                                                              | 23        | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 1.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 13        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 12        | 0.85%   |
| AMD Wrestler HDMI Audio                                                                           | 12        | 0.85%   |
| AMD Trinity HDMI Audio Controller                                                                 | 12        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 0.78%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 10        | 0.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 10        | 0.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 10        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 9         | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 171       | 27.14%  |
| SK hynix            | 120       | 19.05%  |
| Unknown             | 60        | 9.52%   |
| Micron Technology   | 59        | 9.37%   |
| Kingston            | 58        | 9.21%   |
| Corsair             | 31        | 4.92%   |
| Team                | 20        | 3.17%   |
| V-GeN               | 16        | 2.54%   |
| Elpida              | 16        | 2.54%   |
| Ramaxel Technology  | 15        | 2.38%   |
| Nanya Technology    | 9         | 1.43%   |
| A-DATA Technology   | 8         | 1.27%   |
| G.Skill             | 5         | 0.79%   |
| Unknown             | 5         | 0.79%   |
| Unknown (ABCD)      | 4         | 0.63%   |
| Apacer              | 4         | 0.63%   |
| Visipro             | 3         | 0.48%   |
| Transcend           | 3         | 0.48%   |
| Crucial             | 3         | 0.48%   |
| Patriot             | 2         | 0.32%   |
| Hewlett-Packard     | 2         | 0.32%   |
| ASint Technology    | 2         | 0.32%   |
| A Force             | 2         | 0.32%   |
| Unknown (8A02)      | 1         | 0.16%   |
| Super Talent        | 1         | 0.16%   |
| Strontium           | 1         | 0.16%   |
| Silicon Power       | 1         | 0.16%   |
| SHARETRONIC         | 1         | 0.16%   |
| Qumo                | 1         | 0.16%   |
| Lexar               | 1         | 0.16%   |
| HPE                 | 1         | 0.16%   |
| GOODRAM             | 1         | 0.16%   |
| Goldkey             | 1         | 0.16%   |
| Essencore           | 1         | 0.16%   |
| 04?@                | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 2.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 11        | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.32%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 9         | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.32%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 7         | 1.02%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.02%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.88%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 6         | 0.88%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.73%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.73%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.73%   |
| Unknown                                                          | 5         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 4         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 4         | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.59%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.59%   |
| Samsung RAM M471A5143EB1-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 0.59%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.59%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.59%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 4         | 0.59%   |
| Nanya RAM NT2GC64B88G0NS-CG 2048MB SODIMM DDR3 1600MT/s          | 4         | 0.59%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.59%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 4         | 0.59%   |
| Kingston RAM 9905625-004.A03LF 8GB SODIMM DDR4 2933MT/s          | 4         | 0.59%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.59%   |
| V-GeN RAM D4R8GS24A8R 8GB SODIMM DDR4 2400MT/s                   | 3         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 3         | 0.44%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.44%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.44%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.44%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 219       | 43.8%   |
| DDR4    | 214       | 42.8%   |
| DDR2    | 21        | 4.2%    |
| SDRAM   | 13        | 2.6%    |
| LPDDR4  | 13        | 2.6%    |
| Unknown | 10        | 2%      |
| LPDDR3  | 7         | 1.4%    |
| LPDDR5  | 1         | 0.2%    |
| DRAM    | 1         | 0.2%    |
| DDR     | 1         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 374       | 74.5%   |
| DIMM         | 101       | 20.12%  |
| Row Of Chips | 22        | 4.38%   |
| Chip         | 5         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 241       | 43.04%  |
| 8192  | 160       | 28.57%  |
| 2048  | 98        | 17.5%   |
| 16384 | 35        | 6.25%   |
| 1024  | 15        | 2.68%   |
| 32768 | 9         | 1.61%   |
| 65536 | 1         | 0.18%   |
| 512   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 163       | 28.1%   |
| 2667    | 92        | 15.86%  |
| 3200    | 58        | 10%     |
| 2400    | 52        | 8.97%   |
| 1333    | 41        | 7.07%   |
| 2133    | 25        | 4.31%   |
| 1334    | 24        | 4.14%   |
| 3266    | 16        | 2.76%   |
| 1067    | 13        | 2.24%   |
| 800     | 13        | 2.24%   |
| 667     | 10        | 1.72%   |
| Unknown | 10        | 1.72%   |
| 1867    | 6         | 1.03%   |
| 4266    | 5         | 0.86%   |
| 8400    | 4         | 0.69%   |
| 2933    | 4         | 0.69%   |
| 4199    | 3         | 0.52%   |
| 3600    | 3         | 0.52%   |
| 2666    | 3         | 0.52%   |
| 1800    | 3         | 0.52%   |
| 1066    | 3         | 0.52%   |
| 533     | 3         | 0.52%   |
| 333     | 3         | 0.52%   |
| 4267    | 2         | 0.34%   |
| 3800    | 2         | 0.34%   |
| 3151    | 2         | 0.34%   |
| 3000    | 2         | 0.34%   |
| 2048    | 2         | 0.34%   |
| 1866    | 2         | 0.34%   |
| 6400    | 1         | 0.17%   |
| 4040    | 1         | 0.17%   |
| 3866    | 1         | 0.17%   |
| 3466    | 1         | 0.17%   |
| 3400    | 1         | 0.17%   |
| 2934    | 1         | 0.17%   |
| 2733    | 1         | 0.17%   |
| 2465    | 1         | 0.17%   |
| 2200    | 1         | 0.17%   |
| 1776    | 1         | 0.17%   |
| 975     | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 20        | 62.5%   |
| Hewlett-Packard    | 5         | 15.63%  |
| Canon              | 3         | 9.38%   |
| Brother Industries | 2         | 6.25%   |
| STMicroelectronics | 1         | 3.13%   |
| Fuji Xerox         | 1         | 3.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L120 Series          | 6         | 18.75%  |
| Seiko Epson L222 Series          | 5         | 15.63%  |
| Seiko Epson L312 Series          | 3         | 9.38%   |
| Seiko Epson L3110 Series         | 2         | 6.25%   |
| Canon iP2700 series              | 2         | 6.25%   |
| Brother DCP-T300                 | 2         | 6.25%   |
| STMicroelectronics JRSVC Printer | 1         | 3.13%   |
| Seiko Epson L405 Series          | 1         | 3.13%   |
| Seiko Epson L355 Series          | 1         | 3.13%   |
| Seiko Epson L300 Series          | 1         | 3.13%   |
| Seiko Epson L1300 Series         | 1         | 3.13%   |
| HP LaserJet P1102                | 1         | 3.13%   |
| HP LaserJet P1006                | 1         | 3.13%   |
| HP LaserJet M101-M106            | 1         | 3.13%   |
| HP Ink Tank 110 series           | 1         | 3.13%   |
| HP DeskJet 5820 series           | 1         | 3.13%   |
| Fuji Xerox DocuPrint M205 b      | 1         | 3.13%   |
| Canon CanoScan LiDE 300          | 1         | 3.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 50%     |
| Canon CanoScan 4400F   | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 179       | 27.45%  |
| IMC Networks                           | 89        | 13.65%  |
| Realtek Semiconductor                  | 59        | 9.05%   |
| Acer                                   | 53        | 8.13%   |
| Sunplus Innovation Technology          | 38        | 5.83%   |
| Quanta                                 | 35        | 5.37%   |
| Syntek                                 | 31        | 4.75%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 4.45%   |
| Microdia                               | 24        | 3.68%   |
| Alcor Micro                            | 20        | 3.07%   |
| Suyin                                  | 18        | 2.76%   |
| Lite-On Technology                     | 10        | 1.53%   |
| Apple                                  | 10        | 1.53%   |
| Logitech                               | 5         | 0.77%   |
| Importek                               | 5         | 0.77%   |
| Ricoh                                  | 4         | 0.61%   |
| Jieli Technology                       | 4         | 0.61%   |
| Silicon Motion                         | 3         | 0.46%   |
| Luxvisions Innotech Limited            | 3         | 0.46%   |
| Lenovo                                 | 3         | 0.46%   |
| Generalplus Technology                 | 3         | 0.46%   |
| Sonix Technology                       | 2         | 0.31%   |
| Primax Electronics                     | 2         | 0.31%   |
| Huawei Technologies                    | 2         | 0.31%   |
| GEMBIRD                                | 2         | 0.31%   |
| Cubeternet                             | 2         | 0.31%   |
| Unknown                                | 2         | 0.31%   |
| Z-Star Microelectronics                | 1         | 0.15%   |
| WCM_USB                                | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| SN0002                                 | 1         | 0.15%   |
| Pixart Imaging                         | 1         | 0.15%   |
| Omnivision                             | 1         | 0.15%   |
| MacroSilicon                           | 1         | 0.15%   |
| Genesys Logic                          | 1         | 0.15%   |
| eMPIA Technology                       | 1         | 0.15%   |
| DigiTech                               | 1         | 0.15%   |
| Arkmicro Technologies                  | 1         | 0.15%   |
| ANYKA                                  | 1         | 0.15%   |
| ALi                                    | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony integrated camera                                       | 28        | 4.27%   |
| Chicony HD WebCam                                               | 28        | 4.27%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 26        | 3.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 19        | 2.9%    |
| Syntek Integrated Camera                                        | 18        | 2.74%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 18        | 2.74%   |
| Chicony USB2.0 HD UVC WebCam                                    | 15        | 2.29%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 12        | 1.83%   |
| Acer Lenovo EasyCamera                                          | 12        | 1.83%   |
| Acer Integrated Camera                                          | 11        | 1.68%   |
| Realtek Integrated_Webcam_HD                                    | 10        | 1.52%   |
| IMC Networks Lenovo EasyCamera                                  | 10        | 1.52%   |
| IMC Networks Integrated Camera                                  | 10        | 1.52%   |
| Microdia Integrated_Webcam_HD                                   | 9         | 1.37%   |
| IMC Networks EasyCamera                                         | 9         | 1.37%   |
| Chicony Lenovo EasyCamera                                       | 9         | 1.37%   |
| Sunplus Asus Webcam                                             | 8         | 1.22%   |
| Sunplus Integrated_Webcam_HD                                    | 7         | 1.07%   |
| Realtek USB Camera                                              | 7         | 1.07%   |
| Quanta HD User Facing                                           | 7         | 1.07%   |
| Chicony HP TrueVision HD Camera                                 | 7         | 1.07%   |
| Chicony HP Truevision HD                                        | 7         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 7         | 1.07%   |
| Alcor Micro Asus Integrated Webcam                              | 7         | 1.07%   |
| Syntek EasyCamera                                               | 6         | 0.91%   |
| Realtek USB2.0 HD UVC WebCam                                    | 6         | 0.91%   |
| Quanta HP TrueVision HD Camera                                  | 6         | 0.91%   |
| Microdia Integrated Webcam                                      | 6         | 0.91%   |
| Chicony EasyCamera                                              | 6         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 6         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.91%   |
| Syntek Lenovo EasyCamera                                        | 5         | 0.76%   |
| Suyin 1.3M HD WebCam                                            | 5         | 0.76%   |
| Quanta VGA WebCam                                               | 5         | 0.76%   |
| Lite-On Integrated Camera                                       | 5         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 5         | 0.76%   |
| Acer HD Webcam                                                  | 5         | 0.76%   |
| Acer EasyCamera                                                 | 5         | 0.76%   |
| Acer BisonCam, NB Pro                                           | 5         | 0.76%   |
| Sunplus HP TrueVision HD Camera                                 | 4         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 30        | 28.85%  |
| Elan Microelectronics      | 20        | 19.23%  |
| Synaptics                  | 19        | 18.27%  |
| Shenzhen Goodix Technology | 13        | 12.5%   |
| LighTuning Technology      | 11        | 10.58%  |
| AuthenTec                  | 5         | 4.81%   |
| Upek                       | 4         | 3.85%   |
| STMicroelectronics         | 2         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                      | 11        | 10.58%  |
| LighTuning EgisTec Touch Fingerprint Sensor                | 10        | 9.62%   |
| Unknown                                                    | 9         | 8.65%   |
| Shenzhen Goodix Fingerprint Reader                         | 8         | 7.69%   |
| Elan ELAN:ARM-M4                                           | 8         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 7         | 6.73%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 5         | 4.81%   |
| Shenzhen Goodix  Fingerprint Device                        | 5         | 4.81%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 4         | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 3.85%   |
| Synaptics  WBDI                                            | 4         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 2.88%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 3         | 2.88%   |
| Validity Sensors VFS Fingerprint sensor                    | 3         | 2.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 3         | 2.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 1.92%   |
| Validity Sensors VFS491                                    | 2         | 1.92%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 1.92%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 2         | 1.92%   |
| AuthenTec AES1600                                          | 2         | 1.92%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 1         | 0.96%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.96%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 0.96%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 0.96%   |
| LighTuning EgisTec_ES603                                   | 1         | 0.96%   |
| Elan fingerprint sensor [FeinTech FPS00200]                | 1         | 0.96%   |
| AuthenTec AES2810                                          | 1         | 0.96%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 13        | 52%     |
| Upek        | 4         | 16%     |
| Alcor Micro | 4         | 16%     |
| O2 Micro    | 2         | 8%      |
| Lenovo      | 2         | 8%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 28%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 16%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 16%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 8%      |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8%      |
| Broadcom 58200                                                               | 2         | 8%      |
| Broadcom 5880                                                                | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 706       | 73.47%  |
| 1     | 200       | 20.81%  |
| 2     | 46        | 4.79%   |
| 3     | 6         | 0.62%   |
| 6     | 2         | 0.21%   |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 104       | 34.32%  |
| Graphics card            | 71        | 23.43%  |
| Net/wireless             | 35        | 11.55%  |
| Chipcard                 | 23        | 7.59%   |
| Bluetooth                | 15        | 4.95%   |
| Multimedia controller    | 14        | 4.62%   |
| Communication controller | 11        | 3.63%   |
| Camera                   | 7         | 2.31%   |
| Net/ethernet             | 6         | 1.98%   |
| Unassigned class         | 5         | 1.65%   |
| Storage                  | 3         | 0.99%   |
| Flash memory             | 2         | 0.66%   |
| Card reader              | 2         | 0.66%   |
| Wireless                 | 1         | 0.33%   |
| Video                    | 1         | 0.33%   |
| Storage/ide              | 1         | 0.33%   |
| Sound                    | 1         | 0.33%   |
| Network                  | 1         | 0.33%   |


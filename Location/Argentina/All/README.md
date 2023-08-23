Linux in Argentina - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Argentina.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Argentina/Desktop/README.md) and [notebooks](/Location/Argentina/Notebook/README.md).

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

Total: 2751

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | A55M-E33                    | Desktop     | [7d538db764](https://linux-hardware.org/?probe=7d538db764) | Aug 12, 2023 |
| MSI           | A55M-E33                    | Desktop     | [9e64865fbc](https://linux-hardware.org/?probe=9e64865fbc) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [607103b8f5](https://linux-hardware.org/?probe=607103b8f5) | Aug 11, 2023 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [88fcbf292a](https://linux-hardware.org/?probe=88fcbf292a) | Aug 10, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [4661b7a0f7](https://linux-hardware.org/?probe=4661b7a0f7) | Aug 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| Exo           | Smart Serie LT              | Notebook    | [08d7c1d923](https://linux-hardware.org/?probe=08d7c1d923) | Aug 09, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [b21781af81](https://linux-hardware.org/?probe=b21781af81) | Aug 08, 2023 |
| MSI           | Z270 PC MATE                | Desktop     | [aa107173a1](https://linux-hardware.org/?probe=aa107173a1) | Aug 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [40b0ea74b1](https://linux-hardware.org/?probe=40b0ea74b1) | Aug 07, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [4323af2ade](https://linux-hardware.org/?probe=4323af2ade) | Aug 07, 2023 |
| Sony          | VAIO                        | All in one  | [e924df8ac8](https://linux-hardware.org/?probe=e924df8ac8) | Aug 07, 2023 |
| Sony          | VAIO                        | All in one  | [8349b185e4](https://linux-hardware.org/?probe=8349b185e4) | Aug 07, 2023 |
| Acer          | Aspire 5551                 | Notebook    | [4db1866796](https://linux-hardware.org/?probe=4db1866796) | Aug 06, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [763d98ad86](https://linux-hardware.org/?probe=763d98ad86) | Aug 06, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [6622cd2887](https://linux-hardware.org/?probe=6622cd2887) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [44556227ff](https://linux-hardware.org/?probe=44556227ff) | Aug 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [e2dee68ce7](https://linux-hardware.org/?probe=e2dee68ce7) | Aug 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fafbd706de](https://linux-hardware.org/?probe=fafbd706de) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Toshiba       | Satellite L505              | Notebook    | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| ASUSTek       | M4A785T-M                   | Desktop     | [f297c8efa8](https://linux-hardware.org/?probe=f297c8efa8) | Aug 04, 2023 |
| GFAST         | N150                        | Notebook    | [bccc2874df](https://linux-hardware.org/?probe=bccc2874df) | Aug 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8767df67f4](https://linux-hardware.org/?probe=8767df67f4) | Aug 02, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [8c4c50cef9](https://linux-hardware.org/?probe=8c4c50cef9) | Aug 02, 2023 |
| System76      | Lemur Pro                   | Notebook    | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [483fbca861](https://linux-hardware.org/?probe=483fbca861) | Jul 31, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| Gigabyte      | B550M AORUS PRO AX          | Desktop     | [f53eed4658](https://linux-hardware.org/?probe=f53eed4658) | Jul 28, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [37440e19b5](https://linux-hardware.org/?probe=37440e19b5) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f321614376](https://linux-hardware.org/?probe=f321614376) | Jul 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| Positivo      | G800                        | Notebook    | [5dd0f188f8](https://linux-hardware.org/?probe=5dd0f188f8) | Jul 25, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [849a99d897](https://linux-hardware.org/?probe=849a99d897) | Jul 25, 2023 |
| Dell          | Latitude E5410              | Notebook    | [e26148754b](https://linux-hardware.org/?probe=e26148754b) | Jul 25, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | Notebook    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [be58f943df](https://linux-hardware.org/?probe=be58f943df) | Jul 22, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [b6432541ed](https://linux-hardware.org/?probe=b6432541ed) | Jul 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| ECS           | H61H2-MV                    | Desktop     | [69a0cd41e0](https://linux-hardware.org/?probe=69a0cd41e0) | Jul 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [e41e794381](https://linux-hardware.org/?probe=e41e794381) | Jul 20, 2023 |
| Dell          | Latitude 3520               | Notebook    | [bd2589c749](https://linux-hardware.org/?probe=bd2589c749) | Jul 20, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e6bbbc4d41](https://linux-hardware.org/?probe=e6bbbc4d41) | Jul 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2f067394f6](https://linux-hardware.org/?probe=2f067394f6) | Jul 19, 2023 |
| Dell          | XPS L501X                   | Notebook    | [0879ff6b9d](https://linux-hardware.org/?probe=0879ff6b9d) | Jul 18, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [b986a103da](https://linux-hardware.org/?probe=b986a103da) | Jul 18, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [801b25d335](https://linux-hardware.org/?probe=801b25d335) | Jul 18, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a58b13cf37](https://linux-hardware.org/?probe=a58b13cf37) | Jul 17, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [692ba8a4af](https://linux-hardware.org/?probe=692ba8a4af) | Jul 17, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [2294cf035b](https://linux-hardware.org/?probe=2294cf035b) | Jul 16, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [b26a172e92](https://linux-hardware.org/?probe=b26a172e92) | Jul 16, 2023 |
| HP            | 3396                        | Desktop     | [5713dca497](https://linux-hardware.org/?probe=5713dca497) | Jul 15, 2023 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [dc0f48314d](https://linux-hardware.org/?probe=dc0f48314d) | Jul 15, 2023 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [571080a9d5](https://linux-hardware.org/?probe=571080a9d5) | Jul 14, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [cbdd93f7d6](https://linux-hardware.org/?probe=cbdd93f7d6) | Jul 14, 2023 |
| AIR           | CX30500                     | Notebook    | [ee0b27d980](https://linux-hardware.org/?probe=ee0b27d980) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d16093199e](https://linux-hardware.org/?probe=d16093199e) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [0549d09ceb](https://linux-hardware.org/?probe=0549d09ceb) | Jul 11, 2023 |
| Acer          | SF714-52T                   | Notebook    | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [8fb942eccd](https://linux-hardware.org/?probe=8fb942eccd) | Jul 10, 2023 |
| Gateway       | ZX4250                      | All in one  | [ff650dc0df](https://linux-hardware.org/?probe=ff650dc0df) | Jul 10, 2023 |
| Dell          | Latitude 3490               | Notebook    | [67de502259](https://linux-hardware.org/?probe=67de502259) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e394b88e49](https://linux-hardware.org/?probe=e394b88e49) | Jul 08, 2023 |
| Alienware     | 17                          | Notebook    | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7cbaa33271](https://linux-hardware.org/?probe=7cbaa33271) | Jul 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e9709930a9](https://linux-hardware.org/?probe=e9709930a9) | Jul 07, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [4b952291ac](https://linux-hardware.org/?probe=4b952291ac) | Jul 07, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [dcf48c7be4](https://linux-hardware.org/?probe=dcf48c7be4) | Jul 07, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [e9b7499b4d](https://linux-hardware.org/?probe=e9b7499b4d) | Jul 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [818272b52c](https://linux-hardware.org/?probe=818272b52c) | Jul 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [ab0a17ec87](https://linux-hardware.org/?probe=ab0a17ec87) | Jul 04, 2023 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | Notebook    | [f897f42089](https://linux-hardware.org/?probe=f897f42089) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [ec9ab3662c](https://linux-hardware.org/?probe=ec9ab3662c) | Jul 01, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [2ee9ffdaa0](https://linux-hardware.org/?probe=2ee9ffdaa0) | Jun 30, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [6ab7575bed](https://linux-hardware.org/?probe=6ab7575bed) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [196daaa768](https://linux-hardware.org/?probe=196daaa768) | Jun 30, 2023 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [8e7db66929](https://linux-hardware.org/?probe=8e7db66929) | Jun 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [5d632e53c6](https://linux-hardware.org/?probe=5d632e53c6) | Jun 30, 2023 |
| Acer          | Aspire 5551                 | Notebook    | [0b4df3165f](https://linux-hardware.org/?probe=0b4df3165f) | Jun 30, 2023 |
| BANGHO        | BES G0304                   | Notebook    | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a5af3e134e](https://linux-hardware.org/?probe=a5af3e134e) | Jun 30, 2023 |
| Acer          | Aspire 5551                 | Notebook    | [73a0f2fd37](https://linux-hardware.org/?probe=73a0f2fd37) | Jun 30, 2023 |
| Dell          | Inspiron 7373               | Convertible | [e7edaad244](https://linux-hardware.org/?probe=e7edaad244) | Jun 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [725b89a524](https://linux-hardware.org/?probe=725b89a524) | Jun 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ef275e1249](https://linux-hardware.org/?probe=ef275e1249) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14s-IML 20RS      | Notebook    | [e3d095fc9f](https://linux-hardware.org/?probe=e3d095fc9f) | Jun 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| ASUSTek       | K53E                        | Notebook    | [8e1f4ee31f](https://linux-hardware.org/?probe=8e1f4ee31f) | Jun 27, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [f94b4ddd1b](https://linux-hardware.org/?probe=f94b4ddd1b) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [d2d1f5b2a5](https://linux-hardware.org/?probe=d2d1f5b2a5) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [d6a1e61945](https://linux-hardware.org/?probe=d6a1e61945) | Jun 26, 2023 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [824c084cce](https://linux-hardware.org/?probe=824c084cce) | Jun 26, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [c3e666ed19](https://linux-hardware.org/?probe=c3e666ed19) | Jun 26, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a31908b24b](https://linux-hardware.org/?probe=a31908b24b) | Jun 25, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a6c7992001](https://linux-hardware.org/?probe=a6c7992001) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [ed70d540cd](https://linux-hardware.org/?probe=ed70d540cd) | Jun 24, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [dd17969875](https://linux-hardware.org/?probe=dd17969875) | Jun 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [bd39971c52](https://linux-hardware.org/?probe=bd39971c52) | Jun 23, 2023 |
| Dell          | Latitude 3520               | Notebook    | [ada304545e](https://linux-hardware.org/?probe=ada304545e) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | Satellite-L845              | Notebook    | [cfe5a81354](https://linux-hardware.org/?probe=cfe5a81354) | Jun 18, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [f7dd657c90](https://linux-hardware.org/?probe=f7dd657c90) | Jun 17, 2023 |
| Dell          | Inspiron 5535               | Notebook    | [88a1d18ea0](https://linux-hardware.org/?probe=88a1d18ea0) | Jun 17, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [47f4fd7822](https://linux-hardware.org/?probe=47f4fd7822) | Jun 17, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [269309f364](https://linux-hardware.org/?probe=269309f364) | Jun 16, 2023 |
| BANGHO        | MAX L5                      | Notebook    | [5027ce5059](https://linux-hardware.org/?probe=5027ce5059) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [fe65868ffe](https://linux-hardware.org/?probe=fe65868ffe) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [affb2b7e01](https://linux-hardware.org/?probe=affb2b7e01) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [850c71b72c](https://linux-hardware.org/?probe=850c71b72c) | Jun 15, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [cc77cad35d](https://linux-hardware.org/?probe=cc77cad35d) | Jun 14, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [7ffe62cc40](https://linux-hardware.org/?probe=7ffe62cc40) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [2ecd3dd29b](https://linux-hardware.org/?probe=2ecd3dd29b) | Jun 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e676294e36](https://linux-hardware.org/?probe=e676294e36) | Jun 13, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d22b8a57cf](https://linux-hardware.org/?probe=d22b8a57cf) | Jun 13, 2023 |
| Unknown       | Unknown                     | Other       | [00ad49fe2f](https://linux-hardware.org/?probe=00ad49fe2f) | Jun 12, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6b1f9dec93](https://linux-hardware.org/?probe=6b1f9dec93) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0d07b35562](https://linux-hardware.org/?probe=0d07b35562) | Jun 11, 2023 |
| ECS           | G41T-M                      | Desktop     | [2c148573fc](https://linux-hardware.org/?probe=2c148573fc) | Jun 11, 2023 |
| Exo           | Smart Serie LT              | Notebook    | [bbecad1cea](https://linux-hardware.org/?probe=bbecad1cea) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [fc025a599d](https://linux-hardware.org/?probe=fc025a599d) | Jun 10, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [f32fbdf6ea](https://linux-hardware.org/?probe=f32fbdf6ea) | Jun 10, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [abc3a3d8a1](https://linux-hardware.org/?probe=abc3a3d8a1) | Jun 09, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [fc826b3cb1](https://linux-hardware.org/?probe=fc826b3cb1) | Jun 09, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [b457e63434](https://linux-hardware.org/?probe=b457e63434) | Jun 09, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [fd3b70424a](https://linux-hardware.org/?probe=fd3b70424a) | Jun 09, 2023 |
| HP            | Notebook                    | Notebook    | [e292bb9d5a](https://linux-hardware.org/?probe=e292bb9d5a) | Jun 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [24f6f6e727](https://linux-hardware.org/?probe=24f6f6e727) | Jun 08, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [931b9e2b05](https://linux-hardware.org/?probe=931b9e2b05) | Jun 08, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [8d4e2bedde](https://linux-hardware.org/?probe=8d4e2bedde) | Jun 08, 2023 |
| Colorful T... | A520M-K PRO V14             | Desktop     | [48c4aa3d8c](https://linux-hardware.org/?probe=48c4aa3d8c) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| Intel         | HURONRIVER                  | Notebook    | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e45ed702a4](https://linux-hardware.org/?probe=e45ed702a4) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | Desktop     | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [43cffb0d0f](https://linux-hardware.org/?probe=43cffb0d0f) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [cef2bf28c9](https://linux-hardware.org/?probe=cef2bf28c9) | Jun 04, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [e6492d37d8](https://linux-hardware.org/?probe=e6492d37d8) | Jun 03, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [5e3ae671cc](https://linux-hardware.org/?probe=5e3ae671cc) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Positivo      | C500                        | Notebook    | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [670044aef5](https://linux-hardware.org/?probe=670044aef5) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1ea9c869ff](https://linux-hardware.org/?probe=1ea9c869ff) | May 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| PCBOX         | Kant                        | Notebook    | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [21261aa270](https://linux-hardware.org/?probe=21261aa270) | May 28, 2023 |
| Intel         | X99                         | Desktop     | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bbd09f3d8f](https://linux-hardware.org/?probe=bbd09f3d8f) | May 27, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | Notebook    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [63ba811050](https://linux-hardware.org/?probe=63ba811050) | May 25, 2023 |
| ASUSTek       | P5QPL-VM EPU                | Desktop     | [380b9a5005](https://linux-hardware.org/?probe=380b9a5005) | May 25, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a4690b7476](https://linux-hardware.org/?probe=a4690b7476) | May 25, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8fb981666f](https://linux-hardware.org/?probe=8fb981666f) | May 24, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e4c9c425f8](https://linux-hardware.org/?probe=e4c9c425f8) | May 23, 2023 |
| MSI           | B460M PRO                   | Desktop     | [94ce62125f](https://linux-hardware.org/?probe=94ce62125f) | May 23, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [069d442d0d](https://linux-hardware.org/?probe=069d442d0d) | May 22, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [cb61728cb7](https://linux-hardware.org/?probe=cb61728cb7) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [1dda8d01ad](https://linux-hardware.org/?probe=1dda8d01ad) | May 20, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [fe4d0a2ec3](https://linux-hardware.org/?probe=fe4d0a2ec3) | May 20, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c571a25585](https://linux-hardware.org/?probe=c571a25585) | May 19, 2023 |
| Lenovo        | IdeaPad U530 Touch 20289    | Notebook    | [72e254e4ee](https://linux-hardware.org/?probe=72e254e4ee) | May 19, 2023 |
| Philco        | PHN14C                      | Notebook    | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [bd7e95bf66](https://linux-hardware.org/?probe=bd7e95bf66) | May 18, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [ca3fda27b5](https://linux-hardware.org/?probe=ca3fda27b5) | May 18, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [f720713dda](https://linux-hardware.org/?probe=f720713dda) | May 13, 2023 |
| HP            | 339A                        | Desktop     | [2ba14f8397](https://linux-hardware.org/?probe=2ba14f8397) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1713b94d26](https://linux-hardware.org/?probe=1713b94d26) | May 12, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [81711fd069](https://linux-hardware.org/?probe=81711fd069) | May 11, 2023 |
| Unknown       | M-140BI3                    | Notebook    | [eb6507c151](https://linux-hardware.org/?probe=eb6507c151) | May 11, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | Desktop     | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [efca4bf9af](https://linux-hardware.org/?probe=efca4bf9af) | May 10, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [35750a650a](https://linux-hardware.org/?probe=35750a650a) | May 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [813acd1225](https://linux-hardware.org/?probe=813acd1225) | May 10, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [fbe7b6d2bf](https://linux-hardware.org/?probe=fbe7b6d2bf) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [89ccdd7262](https://linux-hardware.org/?probe=89ccdd7262) | May 08, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Toshiba       | Satellite L50-C             | Notebook    | [67b9224d87](https://linux-hardware.org/?probe=67b9224d87) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e5488a0dc9](https://linux-hardware.org/?probe=e5488a0dc9) | May 06, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d41ef08f2](https://linux-hardware.org/?probe=2d41ef08f2) | May 05, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7cf447e261](https://linux-hardware.org/?probe=7cf447e261) | May 05, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2e4e7c801d](https://linux-hardware.org/?probe=2e4e7c801d) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [1f3953650c](https://linux-hardware.org/?probe=1f3953650c) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| MSI           | 760GM-P34                   | Desktop     | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| Intel         | DG43GT AAE62768-300         | Desktop     | [e0f10df0f9](https://linux-hardware.org/?probe=e0f10df0f9) | May 03, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2fabcbe5dc](https://linux-hardware.org/?probe=2fabcbe5dc) | May 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fa453d9183](https://linux-hardware.org/?probe=fa453d9183) | May 02, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [f62abcbed6](https://linux-hardware.org/?probe=f62abcbed6) | May 02, 2023 |
| ASUSTek       | A55M-E                      | Desktop     | [927efc8106](https://linux-hardware.org/?probe=927efc8106) | May 02, 2023 |
| iQual         | NQ4X                        | Notebook    | [256ae92f40](https://linux-hardware.org/?probe=256ae92f40) | May 02, 2023 |
| ASUSTek       | A55M-E                      | Desktop     | [ee1054dc5c](https://linux-hardware.org/?probe=ee1054dc5c) | May 01, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [67da6cebd3](https://linux-hardware.org/?probe=67da6cebd3) | Apr 29, 2023 |
| HP            | Unknown                     | Notebook    | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Dell          | Latitude E5410              | Notebook    | [1efb62110c](https://linux-hardware.org/?probe=1efb62110c) | Apr 27, 2023 |
| Dell          | Latitude E5410              | Notebook    | [02be2c8f0b](https://linux-hardware.org/?probe=02be2c8f0b) | Apr 26, 2023 |
| HP            | 81BB                        | All in one  | [65fb6f51d1](https://linux-hardware.org/?probe=65fb6f51d1) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9e926f5c65](https://linux-hardware.org/?probe=9e926f5c65) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| HP            | 090Ch                       | Desktop     | [01d609bbab](https://linux-hardware.org/?probe=01d609bbab) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [c8ec222920](https://linux-hardware.org/?probe=c8ec222920) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2a02b4695b](https://linux-hardware.org/?probe=2a02b4695b) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [32ba023e2a](https://linux-hardware.org/?probe=32ba023e2a) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [f89cce4966](https://linux-hardware.org/?probe=f89cce4966) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f5da23bee0](https://linux-hardware.org/?probe=f5da23bee0) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | Notebook    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Dell          | Latitude E6440              | Notebook    | [027d51d72d](https://linux-hardware.org/?probe=027d51d72d) | Apr 19, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [b4e51d0af3](https://linux-hardware.org/?probe=b4e51d0af3) | Apr 17, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6ba0d9290](https://linux-hardware.org/?probe=a6ba0d9290) | Apr 17, 2023 |
| iQual         | NQ4X                        | Notebook    | [425ccf4057](https://linux-hardware.org/?probe=425ccf4057) | Apr 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7b5363bc3e](https://linux-hardware.org/?probe=7b5363bc3e) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c5f2678609](https://linux-hardware.org/?probe=c5f2678609) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [9d18bebcd7](https://linux-hardware.org/?probe=9d18bebcd7) | Apr 15, 2023 |
| Gigabyte      | B365 HD3                    | Desktop     | [921a57413c](https://linux-hardware.org/?probe=921a57413c) | Apr 15, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [d1ed9e6040](https://linux-hardware.org/?probe=d1ed9e6040) | Apr 14, 2023 |
| HP            | Compaq Presario F700        | Notebook    | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Latitude 5490               | Notebook    | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| HP            | 81BB                        | All in one  | [ef22a07523](https://linux-hardware.org/?probe=ef22a07523) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [1649a1f9b5](https://linux-hardware.org/?probe=1649a1f9b5) | Apr 12, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [497756c5ab](https://linux-hardware.org/?probe=497756c5ab) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [dc55b7997e](https://linux-hardware.org/?probe=dc55b7997e) | Apr 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b35d9a7487](https://linux-hardware.org/?probe=b35d9a7487) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | Notebook    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Positivo      | A1000BW                     | Notebook    | [02295facdc](https://linux-hardware.org/?probe=02295facdc) | Apr 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [916db99ea5](https://linux-hardware.org/?probe=916db99ea5) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5a900adcdc](https://linux-hardware.org/?probe=5a900adcdc) | Apr 07, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [91fcea0b0f](https://linux-hardware.org/?probe=91fcea0b0f) | Apr 07, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [bb95a52e54](https://linux-hardware.org/?probe=bb95a52e54) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [9f251621b1](https://linux-hardware.org/?probe=9f251621b1) | Apr 04, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f801258fa5](https://linux-hardware.org/?probe=f801258fa5) | Apr 04, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [47c6d88922](https://linux-hardware.org/?probe=47c6d88922) | Apr 03, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 80XB     | Convertible | [1e1b34725b](https://linux-hardware.org/?probe=1e1b34725b) | Apr 03, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [71f34e6ebc](https://linux-hardware.org/?probe=71f34e6ebc) | Apr 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [676156b5df](https://linux-hardware.org/?probe=676156b5df) | Apr 02, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [5fc258772a](https://linux-hardware.org/?probe=5fc258772a) | Apr 01, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [2addcb84c6](https://linux-hardware.org/?probe=2addcb84c6) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [3c163a3b34](https://linux-hardware.org/?probe=3c163a3b34) | Mar 31, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [8d2858a444](https://linux-hardware.org/?probe=8d2858a444) | Mar 31, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [45a242d18f](https://linux-hardware.org/?probe=45a242d18f) | Mar 31, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [193d27ceac](https://linux-hardware.org/?probe=193d27ceac) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| AIR           | CX30500                     | Notebook    | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [41a76fad3f](https://linux-hardware.org/?probe=41a76fad3f) | Mar 30, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [1e510aad42](https://linux-hardware.org/?probe=1e510aad42) | Mar 30, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [25cc7bfca2](https://linux-hardware.org/?probe=25cc7bfca2) | Mar 28, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b6184e813b](https://linux-hardware.org/?probe=b6184e813b) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | Notebook    | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [709242697d](https://linux-hardware.org/?probe=709242697d) | Mar 27, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a9ca07dc80](https://linux-hardware.org/?probe=a9ca07dc80) | Mar 27, 2023 |
| Sony          | VJFE52A0711H                | Notebook    | [f2186a4bc4](https://linux-hardware.org/?probe=f2186a4bc4) | Mar 27, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [dca4079e12](https://linux-hardware.org/?probe=dca4079e12) | Mar 26, 2023 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [c671afb118](https://linux-hardware.org/?probe=c671afb118) | Mar 26, 2023 |
| HP            | G42                         | Notebook    | [f1b5695907](https://linux-hardware.org/?probe=f1b5695907) | Mar 25, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [3677f24e87](https://linux-hardware.org/?probe=3677f24e87) | Mar 25, 2023 |
| Dell          | Latitude 5480               | Notebook    | [5886784510](https://linux-hardware.org/?probe=5886784510) | Mar 22, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| Juana Mans... | SF20GM7                     | Notebook    | [708f22e8d7](https://linux-hardware.org/?probe=708f22e8d7) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [0ac96925cd](https://linux-hardware.org/?probe=0ac96925cd) | Mar 16, 2023 |
| ECS           | A55F-M4                     | Desktop     | [eaee63c0f9](https://linux-hardware.org/?probe=eaee63c0f9) | Mar 14, 2023 |
| ECS           | A55F-M4                     | Desktop     | [667ab38865](https://linux-hardware.org/?probe=667ab38865) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | Notebook    | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Exo           | Smart XS1                   | Notebook    | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [97504eea44](https://linux-hardware.org/?probe=97504eea44) | Mar 13, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e035b82dec](https://linux-hardware.org/?probe=e035b82dec) | Mar 13, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [07ebf171d6](https://linux-hardware.org/?probe=07ebf171d6) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| Intel         | H61                         | Desktop     | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [284d2d79f0](https://linux-hardware.org/?probe=284d2d79f0) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | Desktop     | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [1815783cfe](https://linux-hardware.org/?probe=1815783cfe) | Mar 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [7236313c80](https://linux-hardware.org/?probe=7236313c80) | Mar 09, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [bb3776e45d](https://linux-hardware.org/?probe=bb3776e45d) | Mar 09, 2023 |
| eMachines     | eME730                      | Notebook    | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | Notebook    | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | Notebook    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Exo           | Smart Serie M               | Notebook    | [99c93d693a](https://linux-hardware.org/?probe=99c93d693a) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5523730c91](https://linux-hardware.org/?probe=5523730c91) | Mar 04, 2023 |
| Exo           | Smart Serie M               | Notebook    | [e7b817f5ed](https://linux-hardware.org/?probe=e7b817f5ed) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [abb62fe86f](https://linux-hardware.org/?probe=abb62fe86f) | Mar 04, 2023 |
| ASRock        | N68-VS3 FX                  | Desktop     | [3c2ed7f053](https://linux-hardware.org/?probe=3c2ed7f053) | Mar 04, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ae8045e8dd](https://linux-hardware.org/?probe=ae8045e8dd) | Mar 04, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [aefca0b663](https://linux-hardware.org/?probe=aefca0b663) | Feb 28, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [12ccf2fe8b](https://linux-hardware.org/?probe=12ccf2fe8b) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [c7bb2ebe8b](https://linux-hardware.org/?probe=c7bb2ebe8b) | Feb 24, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [916f372721](https://linux-hardware.org/?probe=916f372721) | Feb 24, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [6e82a5c5d6](https://linux-hardware.org/?probe=6e82a5c5d6) | Feb 24, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f7d34fdd3a](https://linux-hardware.org/?probe=f7d34fdd3a) | Feb 24, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [a37b20471b](https://linux-hardware.org/?probe=a37b20471b) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a5f65720f5](https://linux-hardware.org/?probe=a5f65720f5) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [cfcf2ff473](https://linux-hardware.org/?probe=cfcf2ff473) | Feb 21, 2023 |
| Exo           | Smart XL4                   | Notebook    | [6e97a3ff67](https://linux-hardware.org/?probe=6e97a3ff67) | Feb 21, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [bbef057c8f](https://linux-hardware.org/?probe=bbef057c8f) | Feb 21, 2023 |
| Dell          | Inspiron 3502               | Notebook    | [224f4edab7](https://linux-hardware.org/?probe=224f4edab7) | Feb 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [008d5e19e1](https://linux-hardware.org/?probe=008d5e19e1) | Feb 20, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b4b87d47fb](https://linux-hardware.org/?probe=b4b87d47fb) | Feb 17, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [38a92c4ace](https://linux-hardware.org/?probe=38a92c4ace) | Feb 15, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [ba53e8885b](https://linux-hardware.org/?probe=ba53e8885b) | Feb 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| BANGHO        | GM-15Z11 GF1650 i5          | Notebook    | [6cdb04950c](https://linux-hardware.org/?probe=6cdb04950c) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f8de6e450a](https://linux-hardware.org/?probe=f8de6e450a) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | Notebook    | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASRock        | B560 Pro4                   | Desktop     | [0243fe3621](https://linux-hardware.org/?probe=0243fe3621) | Feb 07, 2023 |
| Lenovo        | G470 20078                  | Notebook    | [eca9b95b61](https://linux-hardware.org/?probe=eca9b95b61) | Feb 07, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a1f33b7267](https://linux-hardware.org/?probe=a1f33b7267) | Feb 06, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [5ae73f08c5](https://linux-hardware.org/?probe=5ae73f08c5) | Feb 06, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [32f4028033](https://linux-hardware.org/?probe=32f4028033) | Feb 05, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [93ee4435a2](https://linux-hardware.org/?probe=93ee4435a2) | Feb 03, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [86667a843f](https://linux-hardware.org/?probe=86667a843f) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [03540bd8e5](https://linux-hardware.org/?probe=03540bd8e5) | Feb 02, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [a6584159ac](https://linux-hardware.org/?probe=a6584159ac) | Feb 02, 2023 |
| ECS           | P4M800PRO-M                 | Desktop     | [f446d61863](https://linux-hardware.org/?probe=f446d61863) | Feb 02, 2023 |
| ECS           | A55F-M4                     | Desktop     | [08af507321](https://linux-hardware.org/?probe=08af507321) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [f6d37d568c](https://linux-hardware.org/?probe=f6d37d568c) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [9fab32d6a5](https://linux-hardware.org/?probe=9fab32d6a5) | Feb 01, 2023 |
| Samsung       | SQ35S                       | Notebook    | [7ad1c8a94b](https://linux-hardware.org/?probe=7ad1c8a94b) | Feb 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [298b411767](https://linux-hardware.org/?probe=298b411767) | Jan 31, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5abc8dccdb](https://linux-hardware.org/?probe=5abc8dccdb) | Jan 31, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [e8f09a159a](https://linux-hardware.org/?probe=e8f09a159a) | Jan 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [5122097b1e](https://linux-hardware.org/?probe=5122097b1e) | Jan 29, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [d25a13d2c4](https://linux-hardware.org/?probe=d25a13d2c4) | Jan 28, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b2c04ca4b9](https://linux-hardware.org/?probe=b2c04ca4b9) | Jan 26, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [055d033d99](https://linux-hardware.org/?probe=055d033d99) | Jan 24, 2023 |
| Sony          | VPCEA30EL                   | Notebook    | [7de250ffe6](https://linux-hardware.org/?probe=7de250ffe6) | Jan 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [058de08b2b](https://linux-hardware.org/?probe=058de08b2b) | Jan 24, 2023 |
| ECS           | A55F-M4                     | Desktop     | [db65e68855](https://linux-hardware.org/?probe=db65e68855) | Jan 23, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [458bb94702](https://linux-hardware.org/?probe=458bb94702) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| ASRock        | N68-S UCC                   | Desktop     | [cb4c89a390](https://linux-hardware.org/?probe=cb4c89a390) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| BANGHO        | MOV                         | Notebook    | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [212fa962a2](https://linux-hardware.org/?probe=212fa962a2) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [ca60f249a9](https://linux-hardware.org/?probe=ca60f249a9) | Jan 13, 2023 |
| ECS           | H81H3-M4                    | Desktop     | [08638b9441](https://linux-hardware.org/?probe=08638b9441) | Jan 13, 2023 |
| Lenovo        | 36DC SDK0J40709 WIN 3259... | All in one  | [4a07474fa4](https://linux-hardware.org/?probe=4a07474fa4) | Jan 12, 2023 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [8243f25120](https://linux-hardware.org/?probe=8243f25120) | Jan 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [86a6601ce5](https://linux-hardware.org/?probe=86a6601ce5) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [46679246b9](https://linux-hardware.org/?probe=46679246b9) | Jan 11, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8c480c028a](https://linux-hardware.org/?probe=8c480c028a) | Jan 10, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [ff6c949737](https://linux-hardware.org/?probe=ff6c949737) | Jan 09, 2023 |
| Dell          | Latitude 3490               | Notebook    | [7cf81f6b69](https://linux-hardware.org/?probe=7cf81f6b69) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4334ec8d00](https://linux-hardware.org/?probe=4334ec8d00) | Jan 08, 2023 |
| ASUSTek       | M2N68-AM SE                 | Desktop     | [52a0fe59db](https://linux-hardware.org/?probe=52a0fe59db) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| HP            | 240 G8                      | Notebook    | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [290ccc3261](https://linux-hardware.org/?probe=290ccc3261) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [95db7fffba](https://linux-hardware.org/?probe=95db7fffba) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [aa23d3d6f0](https://linux-hardware.org/?probe=aa23d3d6f0) | Jan 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4473dafda](https://linux-hardware.org/?probe=a4473dafda) | Jan 03, 2023 |
| Positivo      | Z100                        | Notebook    | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [c6c0626dd1](https://linux-hardware.org/?probe=c6c0626dd1) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [97f08bd689](https://linux-hardware.org/?probe=97f08bd689) | Dec 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [24574296e5](https://linux-hardware.org/?probe=24574296e5) | Dec 29, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7a7f335c4a](https://linux-hardware.org/?probe=7a7f335c4a) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| Acer          | AO756                       | Notebook    | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [8cbb4aa960](https://linux-hardware.org/?probe=8cbb4aa960) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [d6e7a07be2](https://linux-hardware.org/?probe=d6e7a07be2) | Dec 28, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [6d56c4c392](https://linux-hardware.org/?probe=6d56c4c392) | Dec 27, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [d6a12148ec](https://linux-hardware.org/?probe=d6a12148ec) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| Exo           | Smart Serie M               | Notebook    | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [5004189ba4](https://linux-hardware.org/?probe=5004189ba4) | Dec 26, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [ff69d47b58](https://linux-hardware.org/?probe=ff69d47b58) | Dec 24, 2022 |
| ASRock        | FM2A78M-HD+ R2.0            | Desktop     | [696403dae4](https://linux-hardware.org/?probe=696403dae4) | Dec 24, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7de172c3b1](https://linux-hardware.org/?probe=7de172c3b1) | Dec 23, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d592546f0a](https://linux-hardware.org/?probe=d592546f0a) | Dec 23, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [52f1e32fc8](https://linux-hardware.org/?probe=52f1e32fc8) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [1f8d567742](https://linux-hardware.org/?probe=1f8d567742) | Dec 20, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [97aa100931](https://linux-hardware.org/?probe=97aa100931) | Dec 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [33bbc3a179](https://linux-hardware.org/?probe=33bbc3a179) | Dec 18, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [ccb746cd73](https://linux-hardware.org/?probe=ccb746cd73) | Dec 15, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f18234034f](https://linux-hardware.org/?probe=f18234034f) | Dec 15, 2022 |
| Dell          | Latitude 5520               | Notebook    | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| Exo           | Smart Serie M               | Notebook    | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [9866855d37](https://linux-hardware.org/?probe=9866855d37) | Dec 13, 2022 |
| Clevo         | M740TU/M760TU               | Notebook    | [5f1a4b58fb](https://linux-hardware.org/?probe=5f1a4b58fb) | Dec 13, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [260a382d54](https://linux-hardware.org/?probe=260a382d54) | Dec 12, 2022 |
| MSI           | A55M-E33                    | Desktop     | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | Latitude E6430              | Notebook    | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| ASRock        | 945GCM-S                    | Desktop     | [926787ea67](https://linux-hardware.org/?probe=926787ea67) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| Dell          | G15 5515                    | Notebook    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| HP            | Notebook                    | Notebook    | [37eead7e86](https://linux-hardware.org/?probe=37eead7e86) | Dec 07, 2022 |
| BANGHO        | BES T5                      | Notebook    | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7d42818fc5](https://linux-hardware.org/?probe=7d42818fc5) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Dell          | Latitude E5450              | Notebook    | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| Lenovo        | ThinkCentre M70e 0809D1Y    | Desktop     | [0cd85fa9f3](https://linux-hardware.org/?probe=0cd85fa9f3) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [81eca2f60e](https://linux-hardware.org/?probe=81eca2f60e) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | Notebook    | [5841aa11f1](https://linux-hardware.org/?probe=5841aa11f1) | Nov 30, 2022 |
| Positivo      | i500pro                     | Notebook    | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3f545fe7c9](https://linux-hardware.org/?probe=3f545fe7c9) | Nov 29, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Foxconn       | A74ML-K                     | Desktop     | [438e3ff761](https://linux-hardware.org/?probe=438e3ff761) | Nov 27, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5f1188d448](https://linux-hardware.org/?probe=5f1188d448) | Nov 26, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [771019bcc6](https://linux-hardware.org/?probe=771019bcc6) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | Notebook    | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [036dcac9fa](https://linux-hardware.org/?probe=036dcac9fa) | Nov 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [eca478ef1d](https://linux-hardware.org/?probe=eca478ef1d) | Nov 23, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [fdafa2db2a](https://linux-hardware.org/?probe=fdafa2db2a) | Nov 22, 2022 |
| HP            | Notebook                    | Notebook    | [ab824250b9](https://linux-hardware.org/?probe=ab824250b9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [498c078586](https://linux-hardware.org/?probe=498c078586) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [abda5b4aaf](https://linux-hardware.org/?probe=abda5b4aaf) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7ffd8149f4](https://linux-hardware.org/?probe=7ffd8149f4) | Nov 21, 2022 |
| Dell          | Latitude E6510              | Notebook    | [c8b9fa9d0a](https://linux-hardware.org/?probe=c8b9fa9d0a) | Nov 20, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [d22a7fff30](https://linux-hardware.org/?probe=d22a7fff30) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| Exo           | Smart XS1                   | Notebook    | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [3964f95a8c](https://linux-hardware.org/?probe=3964f95a8c) | Nov 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Intel         | D946GZIS AAD66165-302       | Desktop     | [ef34a2a126](https://linux-hardware.org/?probe=ef34a2a126) | Nov 16, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [d82617ae65](https://linux-hardware.org/?probe=d82617ae65) | Nov 15, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [83e4ef99fb](https://linux-hardware.org/?probe=83e4ef99fb) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| ASUSTek       | UX410UAK                    | Notebook    | [6653b6c4a5](https://linux-hardware.org/?probe=6653b6c4a5) | Nov 13, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [842f768168](https://linux-hardware.org/?probe=842f768168) | Nov 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [19dc931962](https://linux-hardware.org/?probe=19dc931962) | Nov 10, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [9b43ddbe11](https://linux-hardware.org/?probe=9b43ddbe11) | Nov 09, 2022 |
| Lenovo        | ThinkPad W541 20EGS0V700    | Notebook    | [d03ec65abc](https://linux-hardware.org/?probe=d03ec65abc) | Nov 08, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d71ebfae8b](https://linux-hardware.org/?probe=d71ebfae8b) | Nov 07, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8e89ed396e](https://linux-hardware.org/?probe=8e89ed396e) | Nov 05, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | Notebook    | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [f427764e2c](https://linux-hardware.org/?probe=f427764e2c) | Nov 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [deac1b706f](https://linux-hardware.org/?probe=deac1b706f) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| ECS           | H81H3-M4                    | Desktop     | [a4e0449df5](https://linux-hardware.org/?probe=a4e0449df5) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [9cf3beb13f](https://linux-hardware.org/?probe=9cf3beb13f) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | Notebook    | [36b3303b35](https://linux-hardware.org/?probe=36b3303b35) | Oct 30, 2022 |
| ASUSTek       | TUF H370-PRO GAMING WIFI    | Desktop     | [48cbfa7a78](https://linux-hardware.org/?probe=48cbfa7a78) | Oct 28, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97ee92b9d1](https://linux-hardware.org/?probe=97ee92b9d1) | Oct 28, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [3eeb2624bf](https://linux-hardware.org/?probe=3eeb2624bf) | Oct 27, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bc5db124b](https://linux-hardware.org/?probe=1bc5db124b) | Oct 27, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [9c19f9e755](https://linux-hardware.org/?probe=9c19f9e755) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | Notebook    | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [eca0e58bd8](https://linux-hardware.org/?probe=eca0e58bd8) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [c6cfa3f96d](https://linux-hardware.org/?probe=c6cfa3f96d) | Oct 25, 2022 |
| Dell          | Precision 5560              | Notebook    | [e0dce17c1f](https://linux-hardware.org/?probe=e0dce17c1f) | Oct 25, 2022 |
| ASRock        | N68-S                       | Desktop     | [f1f502f834](https://linux-hardware.org/?probe=f1f502f834) | Oct 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [0c60239460](https://linux-hardware.org/?probe=0c60239460) | Oct 25, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3749438ef1](https://linux-hardware.org/?probe=3749438ef1) | Oct 24, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [25db15ea87](https://linux-hardware.org/?probe=25db15ea87) | Oct 24, 2022 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [8f793706c2](https://linux-hardware.org/?probe=8f793706c2) | Oct 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | Notebook    | [4a17b0a89d](https://linux-hardware.org/?probe=4a17b0a89d) | Oct 22, 2022 |
| Intel         | Montevina CRB               | Notebook    | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [c8a0b8e94f](https://linux-hardware.org/?probe=c8a0b8e94f) | Oct 20, 2022 |
| MSI           | Modern 15 A11MU             | Notebook    | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [d565cdf4a5](https://linux-hardware.org/?probe=d565cdf4a5) | Oct 19, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [3b8ac4e243](https://linux-hardware.org/?probe=3b8ac4e243) | Oct 19, 2022 |
| Positivo      | AT300i                      | Notebook    | [02190f570b](https://linux-hardware.org/?probe=02190f570b) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1be458024b](https://linux-hardware.org/?probe=1be458024b) | Oct 15, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [603fc4f4cd](https://linux-hardware.org/?probe=603fc4f4cd) | Oct 15, 2022 |
| Dell          | Latitude E5450              | Notebook    | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| A-DATA Tec... | XENIA 14                    | Notebook    | [85f4236c50](https://linux-hardware.org/?probe=85f4236c50) | Oct 15, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [28a0b7d55f](https://linux-hardware.org/?probe=28a0b7d55f) | Oct 14, 2022 |
| BANGHO        | B801 IP-M23.62.06           | All in one  | [5a66a855a8](https://linux-hardware.org/?probe=5a66a855a8) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASRock        | AM2NF6G-VSTA                | Desktop     | [6a810d253c](https://linux-hardware.org/?probe=6a810d253c) | Oct 13, 2022 |
| Dell          | Latitude 7420               | Convertible | [dade6a2b21](https://linux-hardware.org/?probe=dade6a2b21) | Oct 13, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | Notebook    | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7dcd7050ae](https://linux-hardware.org/?probe=7dcd7050ae) | Oct 10, 2022 |
| Positivo      | AT300i                      | Notebook    | [62b9d61028](https://linux-hardware.org/?probe=62b9d61028) | Oct 09, 2022 |
| Positivo      | AT300i                      | Notebook    | [8bbd312832](https://linux-hardware.org/?probe=8bbd312832) | Oct 09, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [6ea2c2d73b](https://linux-hardware.org/?probe=6ea2c2d73b) | Oct 08, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [7f78dda318](https://linux-hardware.org/?probe=7f78dda318) | Oct 07, 2022 |
| HP            | 339A                        | Desktop     | [0cb27058b8](https://linux-hardware.org/?probe=0cb27058b8) | Oct 07, 2022 |
| ASUSTek       | X505BP                      | Notebook    | [3ebba89d5e](https://linux-hardware.org/?probe=3ebba89d5e) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [11ed7b9f37](https://linux-hardware.org/?probe=11ed7b9f37) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [a4c0e2324f](https://linux-hardware.org/?probe=a4c0e2324f) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [51a7f36a69](https://linux-hardware.org/?probe=51a7f36a69) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Biostar       | H55 HD                      | Desktop     | [bde8e0a133](https://linux-hardware.org/?probe=bde8e0a133) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [d5a4d2ae41](https://linux-hardware.org/?probe=d5a4d2ae41) | Sep 28, 2022 |
| Positivo      | SW6H                        | Notebook    | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| System76      | Lemur Pro                   | Notebook    | [35340e6221](https://linux-hardware.org/?probe=35340e6221) | Sep 26, 2022 |
| NSX           | Celeron 14                  | Notebook    | [b8fdb14beb](https://linux-hardware.org/?probe=b8fdb14beb) | Sep 25, 2022 |
| NSX           | Celeron 14                  | Notebook    | [1d358a2828](https://linux-hardware.org/?probe=1d358a2828) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [f038a5908f](https://linux-hardware.org/?probe=f038a5908f) | Sep 23, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| BANGHO        | BES G1529                   | Notebook    | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [75854836f7](https://linux-hardware.org/?probe=75854836f7) | Sep 20, 2022 |
| Intel         | HURONRIVER                  | Desktop     | [e4e09c23e5](https://linux-hardware.org/?probe=e4e09c23e5) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [b3350b3f69](https://linux-hardware.org/?probe=b3350b3f69) | Sep 17, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Exo           | Smart XL4                   | Notebook    | [96f159b86f](https://linux-hardware.org/?probe=96f159b86f) | Sep 14, 2022 |
| Exo           | H310CH5-M2                  | Desktop     | [9154b5149b](https://linux-hardware.org/?probe=9154b5149b) | Sep 14, 2022 |
| HP            | Pavilion 17                 | Notebook    | [5d9be9b086](https://linux-hardware.org/?probe=5d9be9b086) | Sep 13, 2022 |
| Dell          | Precision 5550              | Notebook    | [82eebd67fd](https://linux-hardware.org/?probe=82eebd67fd) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [105dae5731](https://linux-hardware.org/?probe=105dae5731) | Sep 11, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [c9b78bb640](https://linux-hardware.org/?probe=c9b78bb640) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [7d108d27ee](https://linux-hardware.org/?probe=7d108d27ee) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [86af6e4676](https://linux-hardware.org/?probe=86af6e4676) | Sep 08, 2022 |
| HP            | 245 G6                      | Notebook    | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [35ead5350d](https://linux-hardware.org/?probe=35ead5350d) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fc5e3d8261](https://linux-hardware.org/?probe=fc5e3d8261) | Sep 05, 2022 |
| Intel         | powered classmate PC        | Notebook    | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [115b09b849](https://linux-hardware.org/?probe=115b09b849) | Aug 30, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | Notebook    | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| Exo           | Smart Serie L               | Notebook    | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [9fe64d4a60](https://linux-hardware.org/?probe=9fe64d4a60) | Aug 27, 2022 |
| HP            | Notebook                    | Notebook    | [2d11bc2975](https://linux-hardware.org/?probe=2d11bc2975) | Aug 26, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Standard      | AHV                         | Notebook    | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [c3ddddae2c](https://linux-hardware.org/?probe=c3ddddae2c) | Aug 24, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6c0183592b](https://linux-hardware.org/?probe=6c0183592b) | Aug 23, 2022 |
| Sony          | VGN-NR210FH                 | Notebook    | [8c007bfa55](https://linux-hardware.org/?probe=8c007bfa55) | Aug 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [d4a7a111a7](https://linux-hardware.org/?probe=d4a7a111a7) | Aug 21, 2022 |
| Novatech      | C141WP-I5HS                 | Notebook    | [767c02caeb](https://linux-hardware.org/?probe=767c02caeb) | Aug 20, 2022 |
| Compaq        | Presario 21 VerX            | Notebook    | [97aa39b2ca](https://linux-hardware.org/?probe=97aa39b2ca) | Aug 19, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | Notebook    | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [58f88a4494](https://linux-hardware.org/?probe=58f88a4494) | Aug 17, 2022 |
| HP            | Notebook                    | Notebook    | [784ad31f68](https://linux-hardware.org/?probe=784ad31f68) | Aug 17, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [e68b5affa4](https://linux-hardware.org/?probe=e68b5affa4) | Aug 16, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| PCBOX         | Kant                        | Notebook    | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2a4c496cce](https://linux-hardware.org/?probe=2a4c496cce) | Aug 15, 2022 |
| ASRock        | H55M                        | Desktop     | [8d0bd0d2d2](https://linux-hardware.org/?probe=8d0bd0d2d2) | Aug 15, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [c001e6e62b](https://linux-hardware.org/?probe=c001e6e62b) | Aug 12, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [6b5082a45c](https://linux-hardware.org/?probe=6b5082a45c) | Aug 12, 2022 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d77caddb55](https://linux-hardware.org/?probe=d77caddb55) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| HP            | Pavilion 17                 | Notebook    | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [a6f68827fb](https://linux-hardware.org/?probe=a6f68827fb) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | Notebook    | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [b07157a232](https://linux-hardware.org/?probe=b07157a232) | Aug 08, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [18d8a04343](https://linux-hardware.org/?probe=18d8a04343) | Aug 08, 2022 |
| Toshiba       | Satellite Pro L300D         | Notebook    | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| MSI           | CR620                       | Notebook    | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| Intel         | 945GCT-M                    | Desktop     | [0481d5180e](https://linux-hardware.org/?probe=0481d5180e) | Aug 06, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [ab52d0fc52](https://linux-hardware.org/?probe=ab52d0fc52) | Aug 05, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [0b4eaa2b43](https://linux-hardware.org/?probe=0b4eaa2b43) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | Notebook    | [beaaaa6f6e](https://linux-hardware.org/?probe=beaaaa6f6e) | Aug 03, 2022 |
| LG Electro... | R480-L.B211P1               | Notebook    | [307f422c53](https://linux-hardware.org/?probe=307f422c53) | Aug 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| Intel         | DH55HC AAE70933-502         | Desktop     | [a484fb9cc8](https://linux-hardware.org/?probe=a484fb9cc8) | Aug 02, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | Notebook    | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Toshiba       | Satellite-C845              | Notebook    | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [047d3c88ad](https://linux-hardware.org/?probe=047d3c88ad) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [14bbcb7e47](https://linux-hardware.org/?probe=14bbcb7e47) | Jul 30, 2022 |
| ASRock        | Z97 Pro4                    | Desktop     | [0db03812df](https://linux-hardware.org/?probe=0db03812df) | Jul 29, 2022 |
| MSI           | Z370 GAMING M5              | Desktop     | [b9ec9e3dd4](https://linux-hardware.org/?probe=b9ec9e3dd4) | Jul 28, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [eb92148078](https://linux-hardware.org/?probe=eb92148078) | Jul 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | Notebook    | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [cea12b9c9c](https://linux-hardware.org/?probe=cea12b9c9c) | Jul 27, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [a2c2f04e29](https://linux-hardware.org/?probe=a2c2f04e29) | Jul 26, 2022 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [88b45b1956](https://linux-hardware.org/?probe=88b45b1956) | Jul 26, 2022 |
| ASUSTek       | X550ZA                      | Notebook    | [00126a3052](https://linux-hardware.org/?probe=00126a3052) | Jul 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7ffde486ac](https://linux-hardware.org/?probe=7ffde486ac) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f84af529bb](https://linux-hardware.org/?probe=f84af529bb) | Jul 24, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [df98c1834c](https://linux-hardware.org/?probe=df98c1834c) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [73a12fbe59](https://linux-hardware.org/?probe=73a12fbe59) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [6f5d960fdc](https://linux-hardware.org/?probe=6f5d960fdc) | Jul 21, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [2543aa4d88](https://linux-hardware.org/?probe=2543aa4d88) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Dell          | 0DR845                      | Desktop     | [cf4bcf9de8](https://linux-hardware.org/?probe=cf4bcf9de8) | Jul 19, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48d9b9f502](https://linux-hardware.org/?probe=48d9b9f502) | Jul 18, 2022 |
| Toshiba       | Satellite C55-B             | Notebook    | [70c17c522d](https://linux-hardware.org/?probe=70c17c522d) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5089cb3d81](https://linux-hardware.org/?probe=5089cb3d81) | Jul 17, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [3e2c54f9f1](https://linux-hardware.org/?probe=3e2c54f9f1) | Jul 17, 2022 |
| NSX           | SB142G                      | Notebook    | [12329702b6](https://linux-hardware.org/?probe=12329702b6) | Jul 15, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [0c08648c4d](https://linux-hardware.org/?probe=0c08648c4d) | Jul 15, 2022 |
| ASRock        | A55M-VS                     | Desktop     | [844ac53526](https://linux-hardware.org/?probe=844ac53526) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | Desktop     | [3b8f491017](https://linux-hardware.org/?probe=3b8f491017) | Jul 14, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c90a0cbab7](https://linux-hardware.org/?probe=c90a0cbab7) | Jul 13, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [87fa08ea59](https://linux-hardware.org/?probe=87fa08ea59) | Jul 13, 2022 |
| Standard      | AHV                         | Notebook    | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Lenovo        | ThinkPad L470 20J5S01L00    | Notebook    | [401e13e2a6](https://linux-hardware.org/?probe=401e13e2a6) | Jul 12, 2022 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [46d0d5dccc](https://linux-hardware.org/?probe=46d0d5dccc) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [4f064a8dbc](https://linux-hardware.org/?probe=4f064a8dbc) | Jul 10, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3aee4d5b24](https://linux-hardware.org/?probe=3aee4d5b24) | Jul 09, 2022 |
| ECS           | H110M4-C23                  | Desktop     | [4a4af6d2e9](https://linux-hardware.org/?probe=4a4af6d2e9) | Jul 08, 2022 |
| Dell          | Latitude 3520               | Notebook    | [8439c98834](https://linux-hardware.org/?probe=8439c98834) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [5b90bd12c7](https://linux-hardware.org/?probe=5b90bd12c7) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [9c2136e4eb](https://linux-hardware.org/?probe=9c2136e4eb) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [244b168c32](https://linux-hardware.org/?probe=244b168c32) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [95e6ec0822](https://linux-hardware.org/?probe=95e6ec0822) | Jul 05, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [147320c75c](https://linux-hardware.org/?probe=147320c75c) | Jul 04, 2022 |
| NSX           | SB142G                      | Notebook    | [58158ab261](https://linux-hardware.org/?probe=58158ab261) | Jul 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [2a161e0d10](https://linux-hardware.org/?probe=2a161e0d10) | Jul 04, 2022 |
| Novatech      | C141WP-I5HS                 | Notebook    | [c487164618](https://linux-hardware.org/?probe=c487164618) | Jul 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [28429fdd32](https://linux-hardware.org/?probe=28429fdd32) | Jul 02, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ad993981af](https://linux-hardware.org/?probe=ad993981af) | Jul 02, 2022 |
| Intel         | DX58SO AAE29331-703         | Desktop     | [3b22974574](https://linux-hardware.org/?probe=3b22974574) | Jul 01, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [c38c4e9cb9](https://linux-hardware.org/?probe=c38c4e9cb9) | Jun 30, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [28479b3edf](https://linux-hardware.org/?probe=28479b3edf) | Jun 30, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [8d9a85c7f3](https://linux-hardware.org/?probe=8d9a85c7f3) | Jun 30, 2022 |
| MSI           | CR620                       | Notebook    | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ddfd26738](https://linux-hardware.org/?probe=8ddfd26738) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | Notebook    | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Dell          | Latitude 3410               | Notebook    | [050678128c](https://linux-hardware.org/?probe=050678128c) | Jun 29, 2022 |
| Dell          | Latitude 3590               | Notebook    | [b5d4509068](https://linux-hardware.org/?probe=b5d4509068) | Jun 29, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [ff60a3cb61](https://linux-hardware.org/?probe=ff60a3cb61) | Jun 28, 2022 |
| HP            | ProBook 455 G4              | Notebook    | [f54297787f](https://linux-hardware.org/?probe=f54297787f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [ec155fca3f](https://linux-hardware.org/?probe=ec155fca3f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [016ee6ec73](https://linux-hardware.org/?probe=016ee6ec73) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [af267c59cd](https://linux-hardware.org/?probe=af267c59cd) | Jun 28, 2022 |
| HP            | 8054                        | Desktop     | [82dd44f05f](https://linux-hardware.org/?probe=82dd44f05f) | Jun 26, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [90c166f77b](https://linux-hardware.org/?probe=90c166f77b) | Jun 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [21d2b9f0fb](https://linux-hardware.org/?probe=21d2b9f0fb) | Jun 23, 2022 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [92944b1e97](https://linux-hardware.org/?probe=92944b1e97) | Jun 22, 2022 |
| HP            | 3646h                       | Desktop     | [d27deccf27](https://linux-hardware.org/?probe=d27deccf27) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| HP            | 255 G3                      | Notebook    | [def96ad707](https://linux-hardware.org/?probe=def96ad707) | Jun 21, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [465ffdd126](https://linux-hardware.org/?probe=465ffdd126) | Jun 21, 2022 |
| Dell          | Latitude 3590               | Notebook    | [fdfd4be1e2](https://linux-hardware.org/?probe=fdfd4be1e2) | Jun 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
| ASUSTek       | UX410UAK                    | Notebook    | [0d2e384ebf](https://linux-hardware.org/?probe=0d2e384ebf) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [4e35a154b5](https://linux-hardware.org/?probe=4e35a154b5) | Jun 18, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [a56ff0b014](https://linux-hardware.org/?probe=a56ff0b014) | Jun 18, 2022 |
| ASRock        | G41M-GS                     | Desktop     | [9167934132](https://linux-hardware.org/?probe=9167934132) | Jun 18, 2022 |
| HP            | 0A60h                       | Desktop     | [cb42238223](https://linux-hardware.org/?probe=cb42238223) | Jun 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [9481bad179](https://linux-hardware.org/?probe=9481bad179) | Jun 17, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| Lenovo        | B40-70 80F3                 | Notebook    | [41495c085a](https://linux-hardware.org/?probe=41495c085a) | Jun 16, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [4e33fa1a1d](https://linux-hardware.org/?probe=4e33fa1a1d) | Jun 15, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [71f9801165](https://linux-hardware.org/?probe=71f9801165) | Jun 15, 2022 |
| MSI           | 3664h                       | Desktop     | [5fbb22c653](https://linux-hardware.org/?probe=5fbb22c653) | Jun 15, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [9916ed24a9](https://linux-hardware.org/?probe=9916ed24a9) | Jun 15, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [a3f29fd594](https://linux-hardware.org/?probe=a3f29fd594) | Jun 14, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [c8b26ae553](https://linux-hardware.org/?probe=c8b26ae553) | Jun 13, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [cae8181e7d](https://linux-hardware.org/?probe=cae8181e7d) | Jun 11, 2022 |
| Gadnic        | NOT00A1                     | Notebook    | [d63fbf4c2e](https://linux-hardware.org/?probe=d63fbf4c2e) | Jun 10, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [9ae6cc8594](https://linux-hardware.org/?probe=9ae6cc8594) | Jun 07, 2022 |
| ASRock        | H55M                        | Desktop     | [058eceb951](https://linux-hardware.org/?probe=058eceb951) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [ea589a3279](https://linux-hardware.org/?probe=ea589a3279) | Jun 07, 2022 |
| ASRock        | Z97M Anniversary            | Desktop     | [1855124dd3](https://linux-hardware.org/?probe=1855124dd3) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [09d190612b](https://linux-hardware.org/?probe=09d190612b) | Jun 06, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b3a7546aa9](https://linux-hardware.org/?probe=b3a7546aa9) | Jun 06, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [6c408a6fd7](https://linux-hardware.org/?probe=6c408a6fd7) | Jun 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [da04a03393](https://linux-hardware.org/?probe=da04a03393) | Jun 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [321300f927](https://linux-hardware.org/?probe=321300f927) | Jun 01, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [94a496851b](https://linux-hardware.org/?probe=94a496851b) | Jun 01, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [ec364402d8](https://linux-hardware.org/?probe=ec364402d8) | May 31, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Positivo      | ONE700                      | All in one  | [0675afbbfb](https://linux-hardware.org/?probe=0675afbbfb) | May 29, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [30be732591](https://linux-hardware.org/?probe=30be732591) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | Notebook    | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [8546d9cf10](https://linux-hardware.org/?probe=8546d9cf10) | May 27, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [bb0591d5c8](https://linux-hardware.org/?probe=bb0591d5c8) | May 26, 2022 |
| Juana Mans... | SF20GM7                     | Notebook    | [2078b0ab3f](https://linux-hardware.org/?probe=2078b0ab3f) | May 26, 2022 |
| American M... | K7S41GX                     | Desktop     | [b311270c22](https://linux-hardware.org/?probe=b311270c22) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | Desktop     | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [36e5918bc8](https://linux-hardware.org/?probe=36e5918bc8) | May 25, 2022 |
| Positivo      | AT510                       | Notebook    | [2845c5ebd6](https://linux-hardware.org/?probe=2845c5ebd6) | May 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0754e1c6e6](https://linux-hardware.org/?probe=0754e1c6e6) | May 23, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [e59616f367](https://linux-hardware.org/?probe=e59616f367) | May 23, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [2cd1f7fd5e](https://linux-hardware.org/?probe=2cd1f7fd5e) | May 23, 2022 |
| Toshiba       | Unknown                     | Notebook    | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [900181bbff](https://linux-hardware.org/?probe=900181bbff) | May 22, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6d384d3502](https://linux-hardware.org/?probe=6d384d3502) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa4b76df10](https://linux-hardware.org/?probe=aa4b76df10) | May 21, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [830532746e](https://linux-hardware.org/?probe=830532746e) | May 20, 2022 |
| Dell          | Inspiron 3502               | Notebook    | [0d26fe46da](https://linux-hardware.org/?probe=0d26fe46da) | May 19, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [27289062cb](https://linux-hardware.org/?probe=27289062cb) | May 19, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | Desktop     | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [66a07f5e71](https://linux-hardware.org/?probe=66a07f5e71) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [3856a337bb](https://linux-hardware.org/?probe=3856a337bb) | May 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [2b8318661b](https://linux-hardware.org/?probe=2b8318661b) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [09c8ff393f](https://linux-hardware.org/?probe=09c8ff393f) | May 16, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [5af3adc742](https://linux-hardware.org/?probe=5af3adc742) | May 13, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | Notebook    | [40d9831b29](https://linux-hardware.org/?probe=40d9831b29) | May 12, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [d3088d7665](https://linux-hardware.org/?probe=d3088d7665) | May 11, 2022 |
| Positivo      | AT300b                      | Notebook    | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [ba9835cb43](https://linux-hardware.org/?probe=ba9835cb43) | May 10, 2022 |
| Dell          | Latitude E6430              | Notebook    | [a188e200b3](https://linux-hardware.org/?probe=a188e200b3) | May 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b9437261b7](https://linux-hardware.org/?probe=b9437261b7) | May 10, 2022 |
| Foxconn       | LIMA                        | Desktop     | [fc4662a00e](https://linux-hardware.org/?probe=fc4662a00e) | May 09, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ed1e3083d6](https://linux-hardware.org/?probe=ed1e3083d6) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [f84e562503](https://linux-hardware.org/?probe=f84e562503) | May 06, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [76e6cc98aa](https://linux-hardware.org/?probe=76e6cc98aa) | May 05, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3be0a0d66d](https://linux-hardware.org/?probe=3be0a0d66d) | May 03, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [8a7d82f85b](https://linux-hardware.org/?probe=8a7d82f85b) | May 03, 2022 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [f3791f34b1](https://linux-hardware.org/?probe=f3791f34b1) | May 02, 2022 |
| Intel         | powered classmate PC        | Tablet      | [61790801c2](https://linux-hardware.org/?probe=61790801c2) | May 01, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [dc1b877e42](https://linux-hardware.org/?probe=dc1b877e42) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| NSX           | SB1402                      | Notebook    | [c9d79a4fe5](https://linux-hardware.org/?probe=c9d79a4fe5) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d3872db37e](https://linux-hardware.org/?probe=d3872db37e) | Apr 29, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [2cfdf9b28a](https://linux-hardware.org/?probe=2cfdf9b28a) | Apr 29, 2022 |
| Dell          | Latitude 5411               | Notebook    | [34c470e595](https://linux-hardware.org/?probe=34c470e595) | Apr 28, 2022 |
| Dell          | 01HYR7 A01                  | Desktop     | [d7757bf097](https://linux-hardware.org/?probe=d7757bf097) | Apr 27, 2022 |
| NOBLEX        | N14WD21                     | Notebook    | [a8a7a4e1d5](https://linux-hardware.org/?probe=a8a7a4e1d5) | Apr 27, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [bf0a56358c](https://linux-hardware.org/?probe=bf0a56358c) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [00728feb75](https://linux-hardware.org/?probe=00728feb75) | Apr 26, 2022 |
| Lenovo        | ThinkPad E470 20H1A01YAC    | Notebook    | [cd8726de3c](https://linux-hardware.org/?probe=cd8726de3c) | Apr 26, 2022 |
| Dell          | Studio 1558                 | Notebook    | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | Notebook                    | Notebook    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [fb612cbcd5](https://linux-hardware.org/?probe=fb612cbcd5) | Apr 24, 2022 |
| ASUSTek       | X556UB                      | Notebook    | [a9d2922649](https://linux-hardware.org/?probe=a9d2922649) | Apr 23, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [86f45617ad](https://linux-hardware.org/?probe=86f45617ad) | Apr 22, 2022 |
| ASUSTek       | K53E                        | Notebook    | [14e628cbba](https://linux-hardware.org/?probe=14e628cbba) | Apr 22, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [d66e41c50e](https://linux-hardware.org/?probe=d66e41c50e) | Apr 22, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [c021555957](https://linux-hardware.org/?probe=c021555957) | Apr 21, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e7b66178ce](https://linux-hardware.org/?probe=e7b66178ce) | Apr 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c00611352d](https://linux-hardware.org/?probe=c00611352d) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f28318e17b](https://linux-hardware.org/?probe=f28318e17b) | Apr 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [2d0ac286da](https://linux-hardware.org/?probe=2d0ac286da) | Apr 14, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [624c5a033e](https://linux-hardware.org/?probe=624c5a033e) | Apr 14, 2022 |
| Dell          | Latitude 3520               | Notebook    | [8003f0258a](https://linux-hardware.org/?probe=8003f0258a) | Apr 14, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [a5a366f7e7](https://linux-hardware.org/?probe=a5a366f7e7) | Apr 13, 2022 |
| MSI           | H81M-E33                    | Desktop     | [460099f77f](https://linux-hardware.org/?probe=460099f77f) | Apr 13, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [9bcf0f1e4f](https://linux-hardware.org/?probe=9bcf0f1e4f) | Apr 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [52e0e2e934](https://linux-hardware.org/?probe=52e0e2e934) | Apr 12, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [d93ab23121](https://linux-hardware.org/?probe=d93ab23121) | Apr 10, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [de3e230ca3](https://linux-hardware.org/?probe=de3e230ca3) | Apr 10, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [cfa5407b7f](https://linux-hardware.org/?probe=cfa5407b7f) | Apr 10, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [48e5060f20](https://linux-hardware.org/?probe=48e5060f20) | Apr 10, 2022 |
| Unknown       | P4M800CE-8237               | Desktop     | [4c6b9a3f5e](https://linux-hardware.org/?probe=4c6b9a3f5e) | Apr 06, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [a19db5a006](https://linux-hardware.org/?probe=a19db5a006) | Apr 05, 2022 |
| Advantec      | CX23500W                    | Notebook    | [a3152e0a0f](https://linux-hardware.org/?probe=a3152e0a0f) | Apr 02, 2022 |
| Advantec      | CX23500W                    | Notebook    | [feb5c20169](https://linux-hardware.org/?probe=feb5c20169) | Apr 02, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [ddfbf2df5e](https://linux-hardware.org/?probe=ddfbf2df5e) | Apr 01, 2022 |
| CX / Air C... | CX-H87-M1                   | Desktop     | [5a8ee938ce](https://linux-hardware.org/?probe=5a8ee938ce) | Apr 01, 2022 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [1110b2974c](https://linux-hardware.org/?probe=1110b2974c) | Mar 31, 2022 |
| Exo           | Smart XQ5c                  | Notebook    | [5653a02bd3](https://linux-hardware.org/?probe=5653a02bd3) | Mar 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [14bd2cc137](https://linux-hardware.org/?probe=14bd2cc137) | Mar 31, 2022 |
| Dell          | Latitude 3410               | Notebook    | [fd37f4137d](https://linux-hardware.org/?probe=fd37f4137d) | Mar 30, 2022 |
| MSI           | MS-7388                     | Desktop     | [d5eabb8266](https://linux-hardware.org/?probe=d5eabb8266) | Mar 30, 2022 |
| Kanji         | Tamura MAX DUO              | Convertible | [1434c90e55](https://linux-hardware.org/?probe=1434c90e55) | Mar 30, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | Notebook    | [38700103d3](https://linux-hardware.org/?probe=38700103d3) | Mar 29, 2022 |
| Toshiba       | PORTEGE R935                | Notebook    | [b209a8e000](https://linux-hardware.org/?probe=b209a8e000) | Mar 28, 2022 |
| HP            | 81BB                        | All in one  | [cb07426c3e](https://linux-hardware.org/?probe=cb07426c3e) | Mar 28, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [dfc5a02c31](https://linux-hardware.org/?probe=dfc5a02c31) | Mar 28, 2022 |
| Gigabyte      | Z490 AORUS ELITE            | Desktop     | [f8c03d6697](https://linux-hardware.org/?probe=f8c03d6697) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [dd1e7b6c4d](https://linux-hardware.org/?probe=dd1e7b6c4d) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| HP            | 81BB                        | All in one  | [d3fec7d8f4](https://linux-hardware.org/?probe=d3fec7d8f4) | Mar 28, 2022 |
| Positivo      | Z100                        | Notebook    | [5577927db3](https://linux-hardware.org/?probe=5577927db3) | Mar 27, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Intel         | DN2820FYB H24582-205        | Desktop     | [87a81b14f0](https://linux-hardware.org/?probe=87a81b14f0) | Mar 25, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b5ee1f293e](https://linux-hardware.org/?probe=b5ee1f293e) | Mar 25, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [d809ca0f7a](https://linux-hardware.org/?probe=d809ca0f7a) | Mar 25, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [2e006b534b](https://linux-hardware.org/?probe=2e006b534b) | Mar 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [984b59ccb9](https://linux-hardware.org/?probe=984b59ccb9) | Mar 24, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [90ce7b8310](https://linux-hardware.org/?probe=90ce7b8310) | Mar 24, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [d3623fd756](https://linux-hardware.org/?probe=d3623fd756) | Mar 24, 2022 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [1057b723a8](https://linux-hardware.org/?probe=1057b723a8) | Mar 24, 2022 |
| BGH e-Nova    | Unknown                     | Notebook    | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| HP            | 8054                        | Desktop     | [38288fadf8](https://linux-hardware.org/?probe=38288fadf8) | Mar 21, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [c845b9c738](https://linux-hardware.org/?probe=c845b9c738) | Mar 21, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [0008f2b843](https://linux-hardware.org/?probe=0008f2b843) | Mar 20, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [34d7600473](https://linux-hardware.org/?probe=34d7600473) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [bd7accdfd5](https://linux-hardware.org/?probe=bd7accdfd5) | Mar 20, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [116074683a](https://linux-hardware.org/?probe=116074683a) | Mar 19, 2022 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [2e70de8c8d](https://linux-hardware.org/?probe=2e70de8c8d) | Mar 19, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [74bdda89c3](https://linux-hardware.org/?probe=74bdda89c3) | Mar 18, 2022 |
| NSX           | SB142G                      | Notebook    | [0a13591ca3](https://linux-hardware.org/?probe=0a13591ca3) | Mar 18, 2022 |
| ASUSTek       | X505BP                      | Notebook    | [3dc5b19d13](https://linux-hardware.org/?probe=3dc5b19d13) | Mar 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b2ec039a2e](https://linux-hardware.org/?probe=b2ec039a2e) | Mar 17, 2022 |
| Positivo      | VJF155F11UAR                | Notebook    | [39b60a2ef4](https://linux-hardware.org/?probe=39b60a2ef4) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [25c0bbffe2](https://linux-hardware.org/?probe=25c0bbffe2) | Mar 15, 2022 |
| Lenovo        | Edge 15 80H1                | Notebook    | [bd2b981053](https://linux-hardware.org/?probe=bd2b981053) | Mar 14, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7e32829960](https://linux-hardware.org/?probe=7e32829960) | Mar 13, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [c31b5d363f](https://linux-hardware.org/?probe=c31b5d363f) | Mar 10, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [fc3707d356](https://linux-hardware.org/?probe=fc3707d356) | Mar 09, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [5aa4d54781](https://linux-hardware.org/?probe=5aa4d54781) | Mar 09, 2022 |
| NOBLEX        | N14WD21                     | Notebook    | [c166ec8175](https://linux-hardware.org/?probe=c166ec8175) | Mar 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [7708a6ffb9](https://linux-hardware.org/?probe=7708a6ffb9) | Mar 07, 2022 |
| ASRock        | G41M-S3                     | Desktop     | [a5d8ab9493](https://linux-hardware.org/?probe=a5d8ab9493) | Mar 07, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | Notebook    | [3a01549416](https://linux-hardware.org/?probe=3a01549416) | Mar 06, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | Notebook    | [48d2d5d234](https://linux-hardware.org/?probe=48d2d5d234) | Mar 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [52a16c13b1](https://linux-hardware.org/?probe=52a16c13b1) | Mar 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [eca1413f3f](https://linux-hardware.org/?probe=eca1413f3f) | Mar 04, 2022 |
| Nvidia        | Tegra                       | Soc         | [904f2d4f21](https://linux-hardware.org/?probe=904f2d4f21) | Feb 28, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e79a48e141](https://linux-hardware.org/?probe=e79a48e141) | Feb 27, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [65eae3fe4c](https://linux-hardware.org/?probe=65eae3fe4c) | Feb 25, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [bf565614ca](https://linux-hardware.org/?probe=bf565614ca) | Feb 24, 2022 |
| ASRock        | G31M-S                      | Desktop     | [1ecf0fe3af](https://linux-hardware.org/?probe=1ecf0fe3af) | Feb 24, 2022 |
| Lenovo        | ChiefRiver                  | All in one  | [019a150df4](https://linux-hardware.org/?probe=019a150df4) | Feb 23, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [3f99c8072a](https://linux-hardware.org/?probe=3f99c8072a) | Feb 23, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | Notebook    | [6d10cb57e1](https://linux-hardware.org/?probe=6d10cb57e1) | Feb 23, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [09aca1c435](https://linux-hardware.org/?probe=09aca1c435) | Feb 22, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [35c00d5889](https://linux-hardware.org/?probe=35c00d5889) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [265235f4f4](https://linux-hardware.org/?probe=265235f4f4) | Feb 21, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [747899db53](https://linux-hardware.org/?probe=747899db53) | Feb 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [2a57fc9391](https://linux-hardware.org/?probe=2a57fc9391) | Feb 20, 2022 |
| ASUSTek       | X55C                        | Notebook    | [ae05784a4a](https://linux-hardware.org/?probe=ae05784a4a) | Feb 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Argentina/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 248       | 12.55%  |
| Ubuntu 18.04                 | 176       | 8.91%   |
| Ubuntu 22.04                 | 107       | 5.41%   |
| Debian 11                    | 68        | 3.44%   |
| OpenMandriva 4.3             | 56        | 2.83%   |
| OpenMandriva 4.2             | 56        | 2.83%   |
| Zorin 16                     | 37        | 1.87%   |
| Zorin 15                     | 37        | 1.87%   |
| Manjaro                      | 31        | 1.57%   |
| Linux Mint 20.2              | 31        | 1.57%   |
| Arch Rolling                 | 31        | 1.57%   |
| Linux Mint 20.3              | 29        | 1.47%   |
| Xubuntu 20.04                | 26        | 1.32%   |
| Linux Mint 20.1              | 26        | 1.32%   |
| Linux Mint 20                | 26        | 1.32%   |
| KDE neon 20.04               | 25        | 1.27%   |
| Linux Mint 19.3              | 24        | 1.21%   |
| Fedora 36                    | 24        | 1.21%   |
| BlackPanther 18.1            | 24        | 1.21%   |
| Pop!_OS 22.04                | 23        | 1.16%   |
| ArcoLinux Rolling            | 23        | 1.16%   |
| Ubuntu 19.04                 | 21        | 1.06%   |
| Linux Mint 21.1              | 21        | 1.06%   |
| Arch                         | 20        | 1.01%   |
| OpenMandriva 23.03           | 19        | 0.96%   |
| Xubuntu 18.04                | 18        | 0.91%   |
| Fedora 33                    | 18        | 0.91%   |
| Ubuntu 19.10                 | 16        | 0.81%   |
| Pop!_OS 21.04                | 16        | 0.81%   |
| Kubuntu 20.04                | 16        | 0.81%   |
| Ubuntu MATE 20.04            | 15        | 0.76%   |
| Ubuntu 21.10                 | 14        | 0.71%   |
| Ubuntu 21.04                 | 14        | 0.71%   |
| openSUSE Tumbleweed-XXXXXXXX | 14        | 0.71%   |
| Fedora 38                    | 14        | 0.71%   |
| Fedora 37                    | 14        | 0.71%   |
| Fedora 34                    | 14        | 0.71%   |
| Fedora 32                    | 14        | 0.71%   |
| Debian 10                    | 14        | 0.71%   |
| Ubuntu 18.10                 | 13        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 620       | 32.89%  |
| Linux Mint    | 177       | 9.39%   |
| OpenMandriva  | 138       | 7.32%   |
| Fedora        | 107       | 5.68%   |
| Debian        | 106       | 5.62%   |
| Zorin         | 76        | 4.03%   |
| Pop!_OS       | 65        | 3.45%   |
| Xubuntu       | 58        | 3.08%   |
| Manjaro       | 54        | 2.86%   |
| Arch          | 49        | 2.6%    |
| Endless       | 40        | 2.12%   |
| Kubuntu       | 36        | 1.91%   |
| KDE neon      | 34        | 1.8%    |
| Elementary    | 25        | 1.33%   |
| BlackPanther  | 24        | 1.27%   |
| ArcoLinux     | 24        | 1.27%   |
| ROSA          | 23        | 1.22%   |
| Ubuntu MATE   | 21        | 1.11%   |
| Lubuntu       | 20        | 1.06%   |
| openSUSE      | 16        | 0.85%   |
| Nobara        | 15        | 0.8%    |
| Ubuntu Budgie | 13        | 0.69%   |
| Ubuntu Unity  | 11        | 0.58%   |
| LMDE          | 11        | 0.58%   |
| Clear Linux   | 11        | 0.58%   |
| EndeavourOS   | 9         | 0.48%   |
| Peppermint    | 7         | 0.37%   |
| Kali          | 7         | 0.37%   |
| Gentoo        | 7         | 0.37%   |
| MX            | 6         | 0.32%   |
| UbuntuDDE     | 5         | 0.27%   |
| Huayra        | 5         | 0.27%   |
| Xero          | 4         | 0.21%   |
| LinuxFX       | 4         | 0.21%   |
| Void Linux    | 3         | 0.16%   |
| Solus         | 3         | 0.16%   |
| RHEL          | 3         | 0.16%   |
| Parrot        | 3         | 0.16%   |
| Deepin        | 3         | 0.16%   |
| Artix         | 3         | 0.16%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 54        | 2.52%   |
| 5.16.7-desktop-1omv4003  | 53        | 2.47%   |
| 5.4.0-42-generic         | 44        | 2.05%   |
| 5.4.0-26-generic         | 25        | 1.17%   |
| 4.18.16-desktop-1bP      | 23        | 1.07%   |
| 5.4.0-52-generic         | 20        | 0.93%   |
| 5.4.0-48-generic         | 20        | 0.93%   |
| 6.2.6-desktop-1omv2390   | 18        | 0.84%   |
| 5.3.0-40-generic         | 17        | 0.79%   |
| 5.15.0-41-generic        | 16        | 0.75%   |
| 5.15.0-52-generic        | 15        | 0.7%    |
| 5.4.0-91-generic         | 14        | 0.65%   |
| 5.4.0-40-generic         | 14        | 0.65%   |
| 5.4.0-37-generic         | 14        | 0.65%   |
| 5.3.0-28-generic         | 14        | 0.65%   |
| 5.4.0-74-generic         | 13        | 0.61%   |
| 5.3.0-46-generic         | 13        | 0.61%   |
| 5.15.0-56-generic        | 13        | 0.61%   |
| 5.8.0-53-generic         | 12        | 0.56%   |
| 5.4.0-72-generic         | 12        | 0.56%   |
| 5.4.0-58-generic         | 12        | 0.56%   |
| 5.4.0-29-generic         | 12        | 0.56%   |
| 5.3.0-53-generic         | 12        | 0.56%   |
| 5.15.0-46-generic        | 12        | 0.56%   |
| 5.11.0-27-generic        | 12        | 0.56%   |
| 5.4.0-80-generic         | 11        | 0.51%   |
| 5.4.0-47-generic         | 11        | 0.51%   |
| 5.4.0-19-generic         | 11        | 0.51%   |
| 5.19.0-35-generic        | 11        | 0.51%   |
| 5.15.0-48-generic        | 11        | 0.51%   |
| 5.13.0-28-generic        | 11        | 0.51%   |
| 5.8.0-43-generic         | 10        | 0.47%   |
| 5.4.0-45-generic         | 10        | 0.47%   |
| 5.11.0-37-generic        | 10        | 0.47%   |
| 4.18.0-15-generic        | 10        | 0.47%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.42%   |
| 5.8.0-7630-generic       | 9         | 0.42%   |
| 5.8.0-59-generic         | 9         | 0.42%   |
| 5.8.0-14-generic         | 9         | 0.42%   |
| 5.4.0-65-generic         | 9         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 378       | 18.74%  |
| 5.15.0  | 173       | 8.58%   |
| 4.15.0  | 121       | 6%      |
| 5.8.0   | 97        | 4.81%   |
| 5.3.0   | 96        | 4.76%   |
| 5.10.0  | 78        | 3.87%   |
| 5.11.0  | 77        | 3.82%   |
| 5.13.0  | 73        | 3.62%   |
| 5.19.0  | 62        | 3.07%   |
| 5.10.14 | 55        | 2.73%   |
| 5.0.0   | 55        | 2.73%   |
| 5.16.7  | 53        | 2.63%   |
| 4.18.0  | 51        | 2.53%   |
| 4.19.0  | 28        | 1.39%   |
| 6.2.6   | 25        | 1.24%   |
| 4.18.16 | 24        | 1.19%   |
| 6.1.0   | 16        | 0.79%   |
| 6.2.0   | 12        | 0.59%   |
| 6.1.1   | 11        | 0.55%   |
| 5.14.0  | 10        | 0.5%    |
| 5.17.5  | 8         | 0.4%    |
| 6.3.5   | 7         | 0.35%   |
| 6.2.8   | 7         | 0.35%   |
| 5.15.5  | 7         | 0.35%   |
| 5.11.12 | 7         | 0.35%   |
| 4.4.0   | 7         | 0.35%   |
| 6.0.8   | 6         | 0.3%    |
| 5.18.0  | 6         | 0.3%    |
| 5.13.13 | 6         | 0.3%    |
| 6.0.9   | 5         | 0.25%   |
| 5.18.5  | 5         | 0.25%   |
| 5.18.16 | 5         | 0.25%   |
| 5.12.4  | 5         | 0.25%   |
| 4.9.20  | 5         | 0.25%   |
| 6.3.1   | 4         | 0.2%    |
| 6.0.15  | 4         | 0.2%    |
| 6.0.12  | 4         | 0.2%    |
| 6.0.10  | 4         | 0.2%    |
| 6.0.0   | 4         | 0.2%    |
| 5.9.16  | 4         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 393       | 19.77%  |
| 5.15    | 215       | 10.81%  |
| 5.10    | 165       | 8.3%    |
| 4.15    | 121       | 6.09%   |
| 5.8     | 120       | 6.04%   |
| 5.3     | 98        | 4.93%   |
| 5.11    | 98        | 4.93%   |
| 5.13    | 94        | 4.73%   |
| 5.19    | 86        | 4.33%   |
| 5.16    | 77        | 3.87%   |
| 4.18    | 77        | 3.87%   |
| 6.2     | 59        | 2.97%   |
| 5.0     | 59        | 2.97%   |
| 6.1     | 46        | 2.31%   |
| 5.18    | 37        | 1.86%   |
| 6.0     | 34        | 1.71%   |
| 4.19    | 31        | 1.56%   |
| 5.17    | 24        | 1.21%   |
| 6.3     | 21        | 1.06%   |
| 5.14    | 19        | 0.96%   |
| 5.9     | 18        | 0.91%   |
| 4.9     | 18        | 0.91%   |
| 5.6     | 16        | 0.8%    |
| 5.7     | 12        | 0.6%    |
| 5.12    | 12        | 0.6%    |
| 6.4     | 8         | 0.4%    |
| 4.4     | 8         | 0.4%    |
| 5.5     | 6         | 0.3%    |
| 4.1     | 3         | 0.15%   |
| 6.5     | 2         | 0.1%    |
| 4.20    | 2         | 0.1%    |
| 4.13    | 2         | 0.1%    |
| 3.10    | 2         | 0.1%    |
| 5.2     | 1         | 0.05%   |
| 5.1     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |
| 3.16    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1728      | 94.84%  |
| i686    | 90        | 4.94%   |
| armv7l  | 2         | 0.11%   |
| aarch64 | 2         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 770       | 40.72%  |
| KDE5             | 306       | 16.18%  |
| Unknown          | 205       | 10.84%  |
| XFCE             | 194       | 10.26%  |
| X-Cinnamon       | 119       | 6.29%   |
| MATE             | 86        | 4.55%   |
| KDE              | 42        | 2.22%   |
| LXQt             | 23        | 1.22%   |
| Pantheon         | 22        | 1.16%   |
| LXDE             | 18        | 0.95%   |
| Cinnamon         | 17        | 0.9%    |
| Budgie           | 15        | 0.79%   |
| KDE4             | 14        | 0.74%   |
| i3               | 12        | 0.63%   |
| Unity            | 11        | 0.58%   |
| Deepin           | 8         | 0.42%   |
| xmonad           | 3         | 0.16%   |
| Qtile            | 3         | 0.16%   |
| GNOME Flashback  | 3         | 0.16%   |
| bspwm            | 3         | 0.16%   |
| lightdm-xsession | 2         | 0.11%   |
| i3-with-shmlog   | 2         | 0.11%   |
| DWM              | 2         | 0.11%   |
| Cutefish         | 2         | 0.11%   |
| UKUI             | 1         | 0.05%   |
| trinity          | 1         | 0.05%   |
| sway             | 1         | 0.05%   |
| openbox          | 1         | 0.05%   |
| icewm            | 1         | 0.05%   |
| Hyprland         | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |
| BunsenLabs       | 1         | 0.05%   |
| awesome          | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1472      | 79.05%  |
| Wayland | 261       | 14.02%  |
| Unknown | 111       | 5.96%   |
| Tty     | 18        | 0.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1008      | 53.56%  |
| SDDM    | 280       | 14.88%  |
| LightDM | 178       | 9.46%   |
| GDM     | 173       | 9.19%   |
| GDM3    | 167       | 8.87%   |
| TDM     | 49        | 2.6%    |
| KDM     | 14        | 0.74%   |
| LXDM    | 4         | 0.21%   |
| SLiM    | 3         | 0.16%   |
| XDM     | 2         | 0.11%   |
| GREETD  | 2         | 0.11%   |
| SLIMSKI | 1         | 0.05%   |
| Ly      | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| es_AR       | 1022      | 54.54%  |
| en_US       | 423       | 22.57%  |
| Unknown     | 207       | 11.05%  |
| es_ES       | 110       | 5.87%   |
| es_MX       | 44        | 2.35%   |
| C           | 30        | 1.6%    |
| en_GB       | 12        | 0.64%   |
| pt_BR       | 5         | 0.27%   |
| es_CL       | 3         | 0.16%   |
| POSIX       | 2         | 0.11%   |
| it_IT       | 2         | 0.11%   |
| es_UY       | 2         | 0.11%   |
| es_US       | 2         | 0.11%   |
| UTF-8       | 1         | 0.05%   |
| ru_RU       | 1         | 0.05%   |
| fr_FR       | 1         | 0.05%   |
| es_DO       | 1         | 0.05%   |
| es_AR.UtF-8 | 1         | 0.05%   |
| en_UTF-8    | 1         | 0.05%   |
| en_US.UTF8  | 1         | 0.05%   |
| en_CA       | 1         | 0.05%   |
| en_AG       | 1         | 0.05%   |
| C.UTF8      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1066      | 57.19%  |
| EFI  | 798       | 42.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1451      | 77.8%   |
| Overlay | 168       | 9.01%   |
| Btrfs   | 127       | 6.81%   |
| Unknown | 52        | 2.79%   |
| Tmpfs   | 27        | 1.45%   |
| Xfs     | 23        | 1.23%   |
| Zfs     | 6         | 0.32%   |
| Ext2    | 5         | 0.27%   |
| Ext3    | 3         | 0.16%   |
| F2fs    | 2         | 0.11%   |
| Aufs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1061      | 57.07%  |
| GPT     | 566       | 30.45%  |
| MBR     | 232       | 12.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1584      | 85.71%  |
| Yes       | 264       | 14.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1258      | 67.89%  |
| Yes       | 595       | 32.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 338       | 18.55%  |
| Lenovo                  | 248       | 13.61%  |
| Gigabyte Technology     | 225       | 12.35%  |
| Hewlett-Packard         | 157       | 8.62%   |
| Dell                    | 142       | 7.79%   |
| MSI                     | 111       | 6.09%   |
| ASRock                  | 100       | 5.49%   |
| Intel                   | 52        | 2.85%   |
| Acer                    | 52        | 2.85%   |
| BANGHO                  | 48        | 2.63%   |
| Toshiba                 | 33        | 1.81%   |
| Exo                     | 33        | 1.81%   |
| Samsung Electronics     | 28        | 1.54%   |
| Positivo                | 26        | 1.43%   |
| ECS                     | 20        | 1.1%    |
| Sony                    | 18        | 0.99%   |
| Apple                   | 18        | 0.99%   |
| Unknown                 | 16        | 0.88%   |
| Biostar                 | 11        | 0.6%    |
| AMI                     | 9         | 0.49%   |
| Compal                  | 8         | 0.44%   |
| Coradir                 | 7         | 0.38%   |
| Clevo                   | 7         | 0.38%   |
| Foxconn                 | 6         | 0.33%   |
| Standard                | 5         | 0.27%   |
| Quanta                  | 5         | 0.27%   |
| NOBLEX                  | 5         | 0.27%   |
| Advantec                | 5         | 0.27%   |
| System76                | 4         | 0.22%   |
| NSX                     | 4         | 0.22%   |
| Juana Manso             | 4         | 0.22%   |
| HUAWEI                  | 4         | 0.22%   |
| A-DATA Technology       | 4         | 0.22%   |
| PCBOX                   | 3         | 0.16%   |
| Kanji                   | 3         | 0.16%   |
| Raspberry Pi Foundation | 2         | 0.11%   |
| Radio Victoria Fueguina | 2         | 0.11%   |
| Pegatron                | 2         | 0.11%   |
| PCChips                 | 2         | 0.11%   |
| Packard Bell            | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 30        | 1.65%   |
| MSI MS-7721                            | 23        | 1.26%   |
| ASUS All Series                        | 19        | 1.04%   |
| Gigabyte F2A68HM-H                     | 14        | 0.77%   |
| ASUS PRIME A320M-K                     | 14        | 0.77%   |
| Gigabyte H81M-H                        | 10        | 0.55%   |
| Lenovo V330-15IKB 81AX                 | 9         | 0.49%   |
| BANGHO MOV                             | 9         | 0.49%   |
| HP Notebook                            | 8         | 0.44%   |
| Gigabyte M68MT-S2                      | 8         | 0.44%   |
| Gigabyte A320M-S2H                     | 8         | 0.44%   |
| BANGHO Suma 1025                       | 8         | 0.44%   |
| ASUS PRIME B450M-A                     | 8         | 0.44%   |
| ASUS P5KPL-AM SE                       | 8         | 0.44%   |
| MSI MS-7C52                            | 7         | 0.38%   |
| Lenovo ThinkPad L15 Gen 2 20X4S27200   | 7         | 0.38%   |
| Lenovo G470 20078                      | 7         | 0.38%   |
| HP Laptop 15-bs0xx                     | 7         | 0.38%   |
| Gigabyte H61M-S1                       | 7         | 0.38%   |
| Gigabyte H110M-H                       | 7         | 0.38%   |
| Coradir Coradir/ES10IS5                | 7         | 0.38%   |
| MSI MS-7A15                            | 6         | 0.33%   |
| Intel powered classmate PC             | 6         | 0.33%   |
| Gigabyte F2A55M-HD2                    | 6         | 0.33%   |
| Gigabyte A320M-H                       | 6         | 0.33%   |
| BANGHO MAX G0101                       | 6         | 0.33%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA | 6         | 0.33%   |
| ASUS ROG STRIX B550-F GAMING           | 6         | 0.33%   |
| ASUS H61M-K                            | 6         | 0.33%   |
| ASRock N68-VS3 FX                      | 6         | 0.33%   |
| ASRock FM2A68M-DG3+                    | 6         | 0.33%   |
| HP Pavilion dv6                        | 5         | 0.27%   |
| Gigabyte A320M-S2H V2                  | 5         | 0.27%   |
| Exo CloudbookE15                       | 5         | 0.27%   |
| ECS H81H3-M4                           | 5         | 0.27%   |
| Dell Latitude 3520                     | 5         | 0.27%   |
| Dell Inspiron 1525                     | 5         | 0.27%   |
| BANGHO W240HU/W250HUQ                  | 5         | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR   | 5         | 0.27%   |
| ASUS K53E                              | 5         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 85        | 4.67%   |
| Dell Inspiron      | 68        | 3.73%   |
| ASUS PRIME         | 56        | 3.07%   |
| Lenovo IdeaPad     | 49        | 2.69%   |
| Dell Latitude      | 47        | 2.58%   |
| Acer Aspire        | 43        | 2.36%   |
| HP Pavilion        | 42        | 2.31%   |
| ASUS VivoBook      | 38        | 2.09%   |
| Unknown            | 30        | 1.65%   |
| MSI MS-7721        | 23        | 1.26%   |
| HP Laptop          | 22        | 1.21%   |
| Toshiba Satellite  | 20        | 1.1%    |
| ASUS All           | 19        | 1.04%   |
| HP Compaq          | 16        | 0.88%   |
| Gigabyte F2A68HM-H | 14        | 0.77%   |
| Exo Smart          | 14        | 0.77%   |
| ASUS ROG           | 14        | 0.77%   |
| Lenovo ThinkBook   | 13        | 0.71%   |
| Gigabyte A320M-S2H | 13        | 0.71%   |
| HP 250             | 11        | 0.6%    |
| Dell OptiPlex      | 11        | 0.6%    |
| BANGHO MAX         | 11        | 0.6%    |
| Lenovo ThinkCentre | 10        | 0.55%   |
| Gigabyte H81M-H    | 10        | 0.55%   |
| ASUS M5A78L-M      | 10        | 0.55%   |
| Lenovo V330-15IKB  | 9         | 0.49%   |
| HP EliteBook       | 9         | 0.49%   |
| BANGHO Suma        | 9         | 0.49%   |
| BANGHO MOV         | 9         | 0.49%   |
| Lenovo Yoga        | 8         | 0.44%   |
| HP Notebook        | 8         | 0.44%   |
| Gigabyte M68MT-S2  | 8         | 0.44%   |
| Gigabyte B450      | 8         | 0.44%   |
| ASUS TUF           | 8         | 0.44%   |
| ASUS P5KPL-AM      | 8         | 0.44%   |
| ASRock N68-VS3     | 8         | 0.44%   |
| MSI MS-7C52        | 7         | 0.38%   |
| Lenovo G470        | 7         | 0.38%   |
| HP ENVY            | 7         | 0.38%   |
| Gigabyte H61M-S1   | 7         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 162       | 8.89%   |
| 2012    | 162       | 8.89%   |
| 2018    | 138       | 7.57%   |
| 2011    | 134       | 7.35%   |
| 2020    | 131       | 7.19%   |
| 2021    | 127       | 6.97%   |
| 2019    | 127       | 6.97%   |
| 2014    | 126       | 6.92%   |
| 2013    | 122       | 6.7%    |
| 2010    | 113       | 6.2%    |
| 2015    | 109       | 5.98%   |
| 2016    | 89        | 4.88%   |
| 2009    | 77        | 4.23%   |
| 2008    | 77        | 4.23%   |
| 2007    | 53        | 2.91%   |
| 2006    | 36        | 1.98%   |
| 2022    | 19        | 1.04%   |
| Unknown | 10        | 0.55%   |
| 2004    | 5         | 0.27%   |
| 2005    | 3         | 0.16%   |
| 2023    | 1         | 0.05%   |
| 2001    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 971       | 53.29%  |
| Desktop        | 772       | 42.37%  |
| Convertible    | 29        | 1.59%   |
| Tablet         | 16        | 0.88%   |
| Mini pc        | 15        | 0.82%   |
| All in one     | 14        | 0.77%   |
| System on chip | 3         | 0.16%   |
| Other          | 1         | 0.05%   |
| Server         | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1712      | 93.35%  |
| Enabled  | 122       | 6.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1820      | 99.89%  |
| Yes  | 2         | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 451       | 24.42%  |
| 4.01-8.0    | 442       | 23.93%  |
| 8.01-16.0   | 343       | 18.57%  |
| 16.01-24.0  | 261       | 14.13%  |
| 1.01-2.0    | 155       | 8.39%   |
| 32.01-64.0  | 89        | 4.82%   |
| 2.01-3.0    | 41        | 2.22%   |
| 0.51-1.0    | 28        | 1.52%   |
| 24.01-32.0  | 23        | 1.25%   |
| 64.01-256.0 | 13        | 0.7%    |
| 0.01-0.5    | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 730       | 36.59%  |
| 2.01-3.0   | 483       | 24.21%  |
| 4.01-8.0   | 256       | 12.83%  |
| 3.01-4.0   | 228       | 11.43%  |
| 0.51-1.0   | 184       | 9.22%   |
| 8.01-16.0  | 75        | 3.76%   |
| 0.01-0.5   | 29        | 1.45%   |
| 16.01-24.0 | 9         | 0.45%   |
| 24.01-32.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1167      | 62.51%  |
| 2      | 468       | 25.07%  |
| 3      | 144       | 7.71%   |
| 4      | 56        | 3%      |
| 5      | 13        | 0.7%    |
| 0      | 11        | 0.59%   |
| 7      | 3         | 0.16%   |
| 6      | 3         | 0.16%   |
| 28     | 1         | 0.05%   |
| 20     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1166      | 63.44%  |
| Yes       | 672       | 36.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1626      | 89.14%  |
| No        | 198       | 10.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1351      | 73.42%  |
| No        | 489       | 26.58%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 973       | 52.94%  |
| Yes       | 865       | 47.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Argentina | 1822      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Buenos Aires                | 428       | 22.46%  |
| Córdoba                    | 126       | 6.61%   |
| Rosario                     | 81        | 4.25%   |
| La Plata                    | 51        | 2.68%   |
| Mar del Plata               | 48        | 2.52%   |
| Lanus                       | 27        | 1.42%   |
| San Miguel de Tucumán      | 26        | 1.36%   |
| Corrientes                  | 25        | 1.31%   |
| Avellaneda                  | 25        | 1.31%   |
| Mendoza                     | 24        | 1.26%   |
| Quilmes                     | 20        | 1.05%   |
| Lomas de Zamora             | 20        | 1.05%   |
| Ituzaingo                   | 17        | 0.89%   |
| Santa Fe                    | 16        | 0.84%   |
| Resistencia                 | 16        | 0.84%   |
| Paraná                     | 16        | 0.84%   |
| Bahía Blanca               | 16        | 0.84%   |
| Salta                       | 15        | 0.79%   |
| Ramos Mejia                 | 15        | 0.79%   |
| Villa Ballester             | 14        | 0.73%   |
| Florencio Varela            | 14        | 0.73%   |
| Viedma                      | 13        | 0.68%   |
| Tandil                      | 13        | 0.68%   |
| Posadas                     | 13        | 0.68%   |
| Olivos                      | 13        | 0.68%   |
| Neuquén                    | 13        | 0.68%   |
| Burzaco                     | 11        | 0.58%   |
| San Telmo                   | 10        | 0.52%   |
| San Juan                    | 10        | 0.52%   |
| Pilar                       | 10        | 0.52%   |
| Caseros                     | 10        | 0.52%   |
| Bariloche                   | 10        | 0.52%   |
| Villa Nueva                 | 9         | 0.47%   |
| San Nicolás de los Arroyos | 9         | 0.47%   |
| San Martín de los Andes    | 9         | 0.47%   |
| Godoy Cruz                  | 9         | 0.47%   |
| Yerba Buena                 | 8         | 0.42%   |
| Tigre                       | 8         | 0.42%   |
| San Luis                    | 8         | 0.42%   |
| San Justo                   | 8         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 696       | 1044   | 27.73%  |
| Seagate                   | 337       | 436    | 13.43%  |
| Kingston                  | 333       | 417    | 13.27%  |
| Samsung Electronics       | 220       | 301    | 8.76%   |
| Toshiba                   | 204       | 254    | 8.13%   |
| Hitachi                   | 85        | 96     | 3.39%   |
| Sandisk                   | 72        | 103    | 2.87%   |
| Unknown                   | 66        | 83     | 2.63%   |
| HGST                      | 55        | 60     | 2.19%   |
| A-DATA Technology         | 46        | 52     | 1.83%   |
| SK hynix                  | 42        | 47     | 1.67%   |
| Gigabyte Technology       | 41        | 65     | 1.63%   |
| Crucial                   | 41        | 60     | 1.63%   |
| Intel                     | 21        | 40     | 0.84%   |
| Micron Technology         | 18        | 22     | 0.72%   |
| Hewlett-Packard           | 18        | 25     | 0.72%   |
| Maxtor                    | 14        | 15     | 0.56%   |
| Corsair                   | 13        | 13     | 0.52%   |
| PNY                       | 11        | 21     | 0.44%   |
| China                     | 11        | 13     | 0.44%   |
| Realtek Semiconductor     | 10        | 12     | 0.4%    |
| KIOXIA                    | 10        | 10     | 0.4%    |
| XPG                       | 9         | 11     | 0.36%   |
| Silicon Motion            | 7         | 8      | 0.28%   |
| Patriot                   | 7         | 9      | 0.28%   |
| Kimtigo                   | 7         | 7      | 0.28%   |
| ADATA Technology          | 7         | 8      | 0.28%   |
| Lexar                     | 6         | 7      | 0.24%   |
| HS-SSD-C100               | 6         | 9      | 0.24%   |
| Colorful                  | 6         | 7      | 0.24%   |
| Phison                    | 5         | 6      | 0.2%    |
| Micron/Crucial Technology | 5         | 7      | 0.2%    |
| Union Memory              | 4         | 4      | 0.16%   |
| Phison Electronics        | 4         | 5      | 0.16%   |
| Neo                       | 4         | 4      | 0.16%   |
| Hikvision                 | 4         | 4      | 0.16%   |
| FORESEE                   | 4         | 4      | 0.16%   |
| Unknown                   | 4         | 4      | 0.16%   |
| Team                      | 3         | 3      | 0.12%   |
| OCZ                       | 3         | 3      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD      | 103       | 3.73%   |
| Kingston SA400S37480G 480GB SSD      | 61        | 2.21%   |
| Seagate ST1000LM035-1RK172 1TB       | 46        | 1.67%   |
| WDC WD10EZEX-08WN4A0 1TB             | 40        | 1.45%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 36        | 1.3%    |
| Kingston SA400S37120G 120GB SSD      | 32        | 1.16%   |
| Toshiba MQ01ABF050 500GB             | 30        | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 28        | 1.01%   |
| Toshiba MQ01ABD100 1TB               | 27        | 0.98%   |
| Seagate ST1000DM010-2EP102 1TB       | 26        | 0.94%   |
| Seagate ST500DM002-1BD142 500GB      | 25        | 0.91%   |
| Kingston SV300S37A120G 120GB SSD     | 23        | 0.83%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 20        | 0.72%   |
| WDC WD5000AAKX-001CA0 500GB          | 20        | 0.72%   |
| WDC WD10EZEX-00BN5A0 1TB             | 18        | 0.65%   |
| Unknown MMC Card  32GB               | 18        | 0.65%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 17        | 0.62%   |
| Toshiba MQ04ABF100 1TB               | 15        | 0.54%   |
| Kingston SV300S37A240G 240GB SSD     | 15        | 0.54%   |
| Kingston SA400S37960G 960GB SSD      | 15        | 0.54%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 14        | 0.51%   |
| Toshiba DT01ACA100 1TB               | 14        | 0.51%   |
| Seagate ST500LM030-2E717D 500GB      | 14        | 0.51%   |
| Kingston SUV400S37240G 240GB SSD     | 14        | 0.51%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 14        | 0.51%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 13        | 0.47%   |
| WDC WD1600AABS-00PRA0 160GB          | 13        | 0.47%   |
| Toshiba DT01ACA050 500GB             | 13        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB      | 13        | 0.47%   |
| Gigabyte GP-GSTFS31240GNTD 240GB SSD | 13        | 0.47%   |
| Toshiba MQ01ABD032 320GB             | 12        | 0.43%   |
| Crucial CT240BX500SSD1 240GB         | 12        | 0.43%   |
| A-DATA SU630 240GB SSD               | 12        | 0.43%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 11        | 0.4%    |
| WDC WD20EZRX-00D8PB0 2TB             | 11        | 0.4%    |
| WDC WD10EZEX-21WN4A0 1TB             | 11        | 0.4%    |
| WDC WD1003FZEX-00MK2A0 1TB           | 11        | 0.4%    |
| HGST HTS721010A9E630 1TB             | 11        | 0.4%    |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 10        | 0.36%   |
| WDC WD10EZEX-00WN4A0 1TB             | 10        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 586       | 848    | 42.62%  |
| Seagate             | 331       | 428    | 24.07%  |
| Toshiba             | 185       | 231    | 13.45%  |
| Samsung Electronics | 108       | 147    | 7.85%   |
| Hitachi             | 85        | 96     | 6.18%   |
| HGST                | 55        | 60     | 4%      |
| Maxtor              | 11        | 11     | 0.8%    |
| Unknown             | 6         | 6      | 0.44%   |
| Fujitsu             | 3         | 3      | 0.22%   |
| USB3.0              | 1         | 1      | 0.07%   |
| Quantum             | 1         | 1      | 0.07%   |
| JMicron Technology  | 1         | 1      | 0.07%   |
| ExcelStor           | 1         | 1      | 0.07%   |
| ASMT                | 1         | 2      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 298       | 375    | 40.11%  |
| WDC                 | 113       | 142    | 15.21%  |
| Samsung Electronics | 43        | 66     | 5.79%   |
| Crucial             | 39        | 58     | 5.25%   |
| A-DATA Technology   | 39        | 43     | 5.25%   |
| SanDisk             | 36        | 45     | 4.85%   |
| Gigabyte Technology | 36        | 60     | 4.85%   |
| PNY                 | 11        | 21     | 1.48%   |
| Hewlett-Packard     | 11        | 15     | 1.48%   |
| Corsair             | 10        | 10     | 1.35%   |
| SK hynix            | 9         | 10     | 1.21%   |
| China               | 8         | 10     | 1.08%   |
| Kimtigo             | 7         | 7      | 0.94%   |
| Lexar               | 6         | 7      | 0.81%   |
| Intel               | 6         | 7      | 0.81%   |
| Colorful            | 6         | 7      | 0.81%   |
| Toshiba             | 5         | 5      | 0.67%   |
| Patriot             | 5         | 7      | 0.67%   |
| Micron Technology   | 5         | 7      | 0.67%   |
| Seagate             | 4         | 6      | 0.54%   |
| FORESEE             | 4         | 4      | 0.54%   |
| Team                | 3         | 3      | 0.4%    |
| OCZ                 | 3         | 3      | 0.4%    |
| Netac               | 3         | 5      | 0.4%    |
| Maxtor              | 3         | 4      | 0.4%    |
| LITEONIT            | 3         | 3      | 0.4%    |
| Hikvision           | 3         | 3      | 0.4%    |
| WDC WDS2            | 2         | 2      | 0.27%   |
| SPCC                | 2         | 2      | 0.27%   |
| HS-SSD-C100         | 2         | 5      | 0.27%   |
| Apple               | 2         | 2      | 0.27%   |
| Unknown             | 2         | 2      | 0.27%   |
| XrayDisk            | 1         | 1      | 0.13%   |
| Transcend           | 1         | 1      | 0.13%   |
| tecmiyo             | 1         | 3      | 0.13%   |
| Super Talent        | 1         | 1      | 0.13%   |
| SMI                 | 1         | 1      | 0.13%   |
| Ramaxel Technology  | 1         | 1      | 0.13%   |
| NGFF                | 1         | 2      | 0.13%   |
| Neo                 | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1191      | 1836   | 51.94%  |
| SSD     | 695       | 974    | 30.31%  |
| NVMe    | 325       | 462    | 14.17%  |
| MMC     | 62        | 80     | 2.7%    |
| Unknown | 20        | 18     | 0.87%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1567      | 2796   | 79.1%   |
| NVMe | 325       | 462    | 16.41%  |
| MMC  | 62        | 80     | 3.13%   |
| SAS  | 27        | 32     | 1.36%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1201      | 1820   | 64.02%  |
| 0.51-1.0        | 542       | 783    | 28.89%  |
| 1.01-2.0        | 88        | 123    | 4.69%   |
| 3.01-4.0        | 18        | 28     | 0.96%   |
| 4.01-10.0       | 13        | 21     | 0.69%   |
| 2.01-3.0        | 12        | 15     | 0.64%   |
| More than 100.0 | 1         | 1      | 0.05%   |
| 10.01-20.0      | 1         | 19     | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 564       | 29.15%  |
| 251-500        | 453       | 23.41%  |
| 501-1000       | 293       | 15.14%  |
| 1001-2000      | 151       | 7.8%    |
| 1-20           | 134       | 6.93%   |
| 51-100         | 122       | 6.3%    |
| 21-50          | 92        | 4.75%   |
| Unknown        | 45        | 2.33%   |
| 2001-3000      | 43        | 2.22%   |
| More than 3000 | 38        | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 802       | 40.3%   |
| 21-50          | 341       | 17.14%  |
| 101-250        | 265       | 13.32%  |
| 51-100         | 226       | 11.36%  |
| 251-500        | 147       | 7.39%   |
| 501-1000       | 96        | 4.82%   |
| 1001-2000      | 49        | 2.46%   |
| Unknown        | 45        | 2.26%   |
| 2001-3000      | 10        | 0.5%    |
| More than 3000 | 9         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB        | 7         | 9      | 3.18%   |
| Seagate ST1000LM035-1RK172 1TB     | 7         | 7      | 3.18%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 4         | 4      | 1.82%   |
| WDC WD10EZEX-00BN5A0 1TB           | 4         | 4      | 1.82%   |
| WDC WD10EARS-00Y5B1 1TB            | 4         | 4      | 1.82%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 3         | 3      | 1.36%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 3         | 3      | 1.36%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 3      | 1.36%   |
| Toshiba MQ01ABF050 500GB           | 3         | 3      | 1.36%   |
| Toshiba MQ01ABD100 1TB             | 3         | 6      | 1.36%   |
| Toshiba MK1665GSX 160GB            | 3         | 3      | 1.36%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 4      | 1.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.36%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 3      | 1.36%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.36%   |
| WDC WD5000AAKX-08ERMA0 500GB       | 2         | 2      | 0.91%   |
| WDC WD3200AAKS-00L9A0 320GB        | 2         | 2      | 0.91%   |
| WDC WD20EZRX-00D8PB0 2TB           | 2         | 2      | 0.91%   |
| WDC WD1003FZEX-00K3CA0 1TB         | 2         | 2      | 0.91%   |
| WDC WD1002FAEX-00Y9A0 1TB          | 2         | 2      | 0.91%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 0.91%   |
| Toshiba MK7559GSXP 752GB           | 2         | 2      | 0.91%   |
| Seagate ST9500325AS 500GB          | 2         | 2      | 0.91%   |
| Seagate ST9250315AS 250GB          | 2         | 2      | 0.91%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 5      | 0.91%   |
| Seagate ST500LM030-2E717D 500GB    | 2         | 2      | 0.91%   |
| Seagate ST1500DL003-9VT16L 1TB     | 2         | 2      | 0.91%   |
| Seagate ST1000DM003-9YN162 1TB     | 2         | 2      | 0.91%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 2      | 0.91%   |
| Samsung Electronics SP0411N 40GB   | 2         | 3      | 0.91%   |
| Samsung Electronics HN-M101MBB 1TB | 2         | 2      | 0.91%   |
| Samsung Electronics HD322HJ 320GB  | 2         | 2      | 0.91%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 2      | 0.91%   |
| Kingston SUV400S37240G 240GB SSD   | 2         | 2      | 0.91%   |
| HGST HTS725050A7E630 500GB         | 2         | 2      | 0.91%   |
| HGST HTS721010A9E630 1TB           | 2         | 4      | 0.91%   |
| HGST HTS541075A9E680 752GB         | 2         | 2      | 0.91%   |
| XPG SPECTRIX S40G 1TB              | 1         | 1      | 0.45%   |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 4      | 0.45%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 1      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 81        | 99     | 38.76%  |
| Seagate             | 44        | 50     | 21.05%  |
| Toshiba             | 24        | 27     | 11.48%  |
| Samsung Electronics | 19        | 21     | 9.09%   |
| Hitachi             | 11        | 13     | 5.26%   |
| HGST                | 11        | 13     | 5.26%   |
| Kingston            | 9         | 9      | 4.31%   |
| A-DATA Technology   | 3         | 3      | 1.44%   |
| Maxtor              | 2         | 2      | 0.96%   |
| XPG                 | 1         | 1      | 0.48%   |
| tecmiyo             | 1         | 3      | 0.48%   |
| SMI                 | 1         | 1      | 0.48%   |
| Quantum             | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 75        | 90     | 40.76%  |
| Seagate             | 44        | 50     | 23.91%  |
| Toshiba             | 24        | 27     | 13.04%  |
| Samsung Electronics | 16        | 18     | 8.7%    |
| Hitachi             | 11        | 13     | 5.98%   |
| HGST                | 11        | 13     | 5.98%   |
| Maxtor              | 2         | 2      | 1.09%   |
| Quantum             | 1         | 1      | 0.54%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 173       | 214    | 87.37%  |
| SSD  | 22        | 27     | 11.11%  |
| NVMe | 3         | 3      | 1.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB       | 2         | 2      | 28.57%  |
| WDC WD1600BEVT-80A23T0 160GB      | 1         | 1      | 14.29%  |
| Toshiba MK6475GSX 640GB           | 1         | 1      | 14.29%  |
| Toshiba MK1665GSX 160GB           | 1         | 1      | 14.29%  |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 14.29%  |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Toshiba             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1132      | 2063   | 57.9%   |
| Works    | 621       | 1056   | 31.76%  |
| Malfunc  | 195       | 244    | 9.97%   |
| Failed   | 7         | 7      | 0.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1156      | 55.71%  |
| AMD                              | 416       | 20.05%  |
| Nvidia                           | 81        | 3.9%    |
| Samsung Electronics              | 75        | 3.61%   |
| SanDisk                          | 71        | 3.42%   |
| Kingston Technology Company      | 40        | 1.93%   |
| SK hynix                         | 33        | 1.59%   |
| VIA Technologies                 | 28        | 1.35%   |
| Realtek Semiconductor            | 19        | 0.92%   |
| Phison Electronics               | 18        | 0.87%   |
| Toshiba America Info Systems     | 15        | 0.72%   |
| Silicon Integrated Systems [SiS] | 15        | 0.72%   |
| Silicon Motion                   | 13        | 0.63%   |
| ASMedia Technology               | 13        | 0.63%   |
| Micron Technology                | 12        | 0.58%   |
| KIOXIA                           | 12        | 0.58%   |
| JMicron Technology               | 12        | 0.58%   |
| Marvell Technology Group         | 11        | 0.53%   |
| ADATA Technology                 | 10        | 0.48%   |
| Micron/Crucial Technology        | 7         | 0.34%   |
| Union Memory (Shenzhen)          | 6         | 0.29%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.14%   |
| Silicon Image                    | 2         | 0.1%    |
| Promise Technology               | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| INNOGRIT                         | 1         | 0.05%   |
| Broadcom / LSI                   | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| Adaptec                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 263       | 10.3%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 125       | 4.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 95        | 3.72%   |
| Nvidia MCP61 SATA Controller                                                            | 68        | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 66        | 2.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 65        | 2.55%   |
| Nvidia MCP61 IDE                                                                        | 58        | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 58        | 2.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 57        | 2.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 56        | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 54        | 2.12%   |
| AMD FCH SATA Controller D                                                               | 51        | 2%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 46        | 1.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 44        | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 42        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 40        | 1.57%   |
| AMD 400 Series Chipset SATA Controller                                                  | 36        | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 33        | 1.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 32        | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 31        | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 31        | 1.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 31        | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 30        | 1.18%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 29        | 1.14%   |
| AMD FCH IDE Controller                                                                  | 29        | 1.14%   |
| Samsung NVMe SSD Controller 980                                                         | 28        | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 28        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 28        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 27        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 26        | 1.02%   |
| AMD 500 Series Chipset SATA Controller                                                  | 26        | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 22        | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 22        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 22        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 22        | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 20        | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 19        | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 19        | 0.74%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 18        | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 18        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1329      | 61.64%  |
| IDE  | 400       | 18.55%  |
| NVMe | 327       | 15.17%  |
| RAID | 99        | 4.59%   |
| SCSI | 1         | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1281      | 70.27%  |
| AMD    | 538       | 29.51%  |
| ARM    | 4         | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 29        | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 1.48%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 19        | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 18        | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 16        | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.88%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.88%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 16        | 0.88%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 15        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.77%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 0.77%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 14        | 0.77%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 14        | 0.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.77%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 14        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.66%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 12        | 0.66%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 11        | 0.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 0.6%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 11        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 0.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 10        | 0.55%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 10        | 0.55%   |
| AMD Athlon II X2 250 Processor                | 10        | 0.55%   |
| AMD A4-4000 APU with Radeon HD Graphics       | 10        | 0.55%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 9         | 0.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 0.49%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 9         | 0.49%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 9         | 0.49%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 9         | 0.49%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 9         | 0.49%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 9         | 0.49%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.49%   |
| AMD FX-6300 Six-Core Processor                | 9         | 0.49%   |
| AMD A8-9600 RADEON R7, 10 COMPUTE CORES 4C+6G | 9         | 0.49%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 8         | 0.44%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz        | 8         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 347       | 19.01%  |
| Intel Core i7           | 237       | 12.99%  |
| Intel Core i3           | 183       | 10.03%  |
| Intel Celeron           | 139       | 7.62%   |
| AMD Ryzen 5             | 93        | 5.1%    |
| Other                   | 91        | 4.99%   |
| Intel Pentium           | 59        | 3.23%   |
| Intel Atom              | 59        | 3.23%   |
| AMD Ryzen 7             | 59        | 3.23%   |
| Intel Core 2 Duo        | 52        | 2.85%   |
| Intel Pentium Dual-Core | 43        | 2.36%   |
| AMD A8                  | 40        | 2.19%   |
| AMD FX                  | 37        | 2.03%   |
| AMD A6                  | 33        | 1.81%   |
| AMD Ryzen 3             | 32        | 1.75%   |
| AMD A4                  | 26        | 1.42%   |
| AMD A10                 | 26        | 1.42%   |
| Intel Pentium Dual      | 25        | 1.37%   |
| AMD Athlon II X2        | 25        | 1.37%   |
| AMD Athlon 64 X2        | 22        | 1.21%   |
| AMD Sempron             | 18        | 0.99%   |
| AMD Athlon              | 18        | 0.99%   |
| AMD Phenom II X4        | 15        | 0.82%   |
| Intel Core 2            | 11        | 0.6%    |
| AMD Ryzen 9             | 11        | 0.6%    |
| Intel Pentium 4         | 10        | 0.55%   |
| Intel Pentium D         | 9         | 0.49%   |
| Intel Genuine           | 9         | 0.49%   |
| AMD Phenom II X6        | 8         | 0.44%   |
| AMD Athlon II X4        | 8         | 0.44%   |
| AMD A12                 | 6         | 0.33%   |
| Intel Xeon              | 5         | 0.27%   |
| Intel Core 2 Quad       | 5         | 0.27%   |
| AMD E1                  | 5         | 0.27%   |
| AMD Athlon II X3        | 5         | 0.27%   |
| AMD Athlon II           | 5         | 0.27%   |
| Intel Pentium Gold      | 4         | 0.22%   |
| AMD Phenom              | 4         | 0.22%   |
| Intel Core i9           | 3         | 0.16%   |
| AMD Ryzen 7 PRO         | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 934       | 51.18%  |
| 4       | 544       | 29.81%  |
| 1       | 115       | 6.3%    |
| 6       | 111       | 6.08%   |
| 8       | 81        | 4.44%   |
| 3       | 20        | 1.1%    |
| 10      | 6         | 0.33%   |
| 12      | 5         | 0.27%   |
| 16      | 4         | 0.22%   |
| Unknown | 3         | 0.16%   |
| 24      | 1         | 0.05%   |
| 14      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1818      | 99.78%  |
| 2       | 3         | 0.16%   |
| Unknown | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1096      | 60.05%  |
| 1       | 726       | 39.78%  |
| Unknown | 3         | 0.16%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1768      | 96.77%  |
| Unknown        | 32        | 1.75%   |
| 32-bit         | 20        | 1.09%   |
| 64-bit         | 7         | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 428       | 22.53%  |
| 0x306a9    | 102       | 5.37%   |
| 0x206a7    | 99        | 5.21%   |
| 0x306c3    | 67        | 3.53%   |
| 0x1067a    | 62        | 3.26%   |
| 0x806e9    | 47        | 2.47%   |
| 0x806ec    | 46        | 2.42%   |
| 0x806c1    | 38        | 2%      |
| 0x6fd      | 36        | 1.89%   |
| 0x406e3    | 36        | 1.89%   |
| 0x906e9    | 35        | 1.84%   |
| 0x08108109 | 35        | 1.84%   |
| 0x010000c8 | 35        | 1.84%   |
| 0x806ea    | 32        | 1.68%   |
| 0x30678    | 31        | 1.63%   |
| 0x306d4    | 30        | 1.58%   |
| 0x06001119 | 29        | 1.53%   |
| 0x906ea    | 28        | 1.47%   |
| 0x20655    | 27        | 1.42%   |
| 0x506e3    | 26        | 1.37%   |
| 0x40651    | 26        | 1.37%   |
| 0x06003106 | 24        | 1.26%   |
| 0x406c4    | 22        | 1.16%   |
| 0x706e5    | 20        | 1.05%   |
| 0x08701021 | 20        | 1.05%   |
| 0x106ca    | 19        | 1%      |
| 0x506c9    | 16        | 0.84%   |
| 0x706a1    | 15        | 0.79%   |
| 0x30661    | 14        | 0.74%   |
| 0x0a50000c | 14        | 0.74%   |
| 0x08101016 | 14        | 0.74%   |
| 0x06000852 | 14        | 0.74%   |
| 0x706a8    | 13        | 0.68%   |
| 0x0800820d | 13        | 0.68%   |
| 0x0600611a | 13        | 0.68%   |
| 0x06006118 | 13        | 0.68%   |
| 0xa0653    | 12        | 0.63%   |
| 0x20652    | 12        | 0.63%   |
| 0x10676    | 12        | 0.63%   |
| 0x0600063e | 12        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 259       | 14.2%   |
| IvyBridge        | 123       | 6.74%   |
| SandyBridge      | 120       | 6.58%   |
| Haswell          | 114       | 6.25%   |
| Penryn           | 93        | 5.1%    |
| K10              | 93        | 5.1%    |
| Silvermont       | 84        | 4.61%   |
| Skylake          | 77        | 4.22%   |
| Zen+             | 69        | 3.78%   |
| Core             | 61        | 3.34%   |
| Piledriver       | 58        | 3.18%   |
| TigerLake        | 54        | 2.96%   |
| Zen 2            | 47        | 2.58%   |
| Westmere         | 45        | 2.47%   |
| Excavator        | 45        | 2.47%   |
| Zen              | 40        | 2.19%   |
| Zen 3            | 38        | 2.08%   |
| Bonnell          | 38        | 2.08%   |
| Steamroller      | 37        | 2.03%   |
| Goldmont plus    | 36        | 1.97%   |
| K8 Hammer        | 35        | 1.92%   |
| IceLake          | 34        | 1.86%   |
| CometLake        | 34        | 1.86%   |
| Broadwell        | 34        | 1.86%   |
| Unknown          | 29        | 1.59%   |
| NetBurst         | 22        | 1.21%   |
| Goldmont         | 18        | 0.99%   |
| Bulldozer        | 16        | 0.88%   |
| K10 Llano        | 14        | 0.77%   |
| P6               | 11        | 0.6%    |
| Jaguar           | 11        | 0.6%    |
| Bobcat           | 9         | 0.49%   |
| Nehalem          | 8         | 0.44%   |
| Puma             | 7         | 0.38%   |
| Alderlake Hybrid | 7         | 0.38%   |
| K8 & K10 hybrid  | 2         | 0.11%   |
| K6               | 2         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1094      | 54.67%  |
| AMD                              | 506       | 25.29%  |
| Nvidia                           | 376       | 18.79%  |
| Silicon Integrated Systems [SiS] | 12        | 0.6%    |
| VIA Technologies                 | 11        | 0.55%   |
| ATI Technologies                 | 2         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 109       | 5.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 77        | 3.72%   |
| Intel HD Graphics 620                                                                    | 60        | 2.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 48        | 2.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 2.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 46        | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 45        | 2.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 42        | 2.03%   |
| Intel UHD Graphics 620                                                                   | 40        | 1.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 38        | 1.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 37        | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 1.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 35        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 33        | 1.6%    |
| Intel HD Graphics 5500                                                                   | 32        | 1.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 1.5%    |
| Intel HD Graphics 630                                                                    | 29        | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 29        | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 1.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.35%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 25        | 1.21%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 23        | 1.11%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 22        | 1.06%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 21        | 1.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 21        | 1.02%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 20        | 0.97%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 0.97%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 20        | 0.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 20        | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 19        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 19        | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 18        | 0.87%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 18        | 0.87%   |
| Intel HD Graphics 530                                                                    | 18        | 0.87%   |
| Intel HD Graphics 500                                                                    | 18        | 0.87%   |
| AMD Renoir                                                                               | 18        | 0.87%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 0.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 0.82%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 16        | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 16        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 937       | 51.17%  |
| 1 x AMD        | 428       | 23.38%  |
| 1 x Nvidia     | 243       | 13.27%  |
| Intel + Nvidia | 108       | 5.9%    |
| Intel + AMD    | 39        | 2.13%   |
| 2 x AMD        | 24        | 1.31%   |
| AMD + Nvidia   | 21        | 1.15%   |
| 1 x SiS        | 12        | 0.66%   |
| 1 x VIA        | 11        | 0.6%    |
| Other          | 4         | 0.22%   |
| 2 x Nvidia     | 2         | 0.11%   |
| 2 x Intel      | 2         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1575      | 85.74%  |
| Proprietary | 171       | 9.31%   |
| Unknown     | 91        | 4.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1112      | 59.47%  |
| 0.01-0.5   | 234       | 12.51%  |
| 1.01-2.0   | 207       | 11.07%  |
| 0.51-1.0   | 146       | 7.81%   |
| 3.01-4.0   | 100       | 5.35%   |
| 7.01-8.0   | 33        | 1.76%   |
| 5.01-6.0   | 21        | 1.12%   |
| 2.01-3.0   | 9         | 0.48%   |
| 8.01-16.0  | 8         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 467       | 24.13%  |
| Goldstar                | 219       | 11.32%  |
| AU Optronics            | 195       | 10.08%  |
| Chimei Innolux          | 181       | 9.35%   |
| BOE                     | 170       | 8.79%   |
| LG Display              | 132       | 6.82%   |
| InfoVision              | 41        | 2.12%   |
| Dell                    | 39        | 2.02%   |
| ViewSonic               | 34        | 1.76%   |
| Philips                 | 33        | 1.71%   |
| BenQ                    | 29        | 1.5%    |
| Hitachi                 | 23        | 1.19%   |
| Hewlett-Packard         | 23        | 1.19%   |
| SKY                     | 21        | 1.09%   |
| Lenovo                  | 20        | 1.03%   |
| Chi Mei Optoelectronics | 20        | 1.03%   |
| LG Electronics          | 19        | 0.98%   |
| Apple                   | 18        | 0.93%   |
| PANDA                   | 15        | 0.78%   |
| Unknown                 | 13        | 0.67%   |
| LG Philips              | 12        | 0.62%   |
| AOC                     | 12        | 0.62%   |
| InnoLux Display         | 11        | 0.57%   |
| SAC                     | 9         | 0.47%   |
| HannStar                | 9         | 0.47%   |
| ASUSTek Computer        | 9         | 0.47%   |
| STA                     | 8         | 0.41%   |
| Sharp                   | 8         | 0.41%   |
| Sony                    | 7         | 0.36%   |
| CPT                     | 7         | 0.36%   |
| Acer                    | 7         | 0.36%   |
| MStar                   | 6         | 0.31%   |
| HKC                     | 6         | 0.31%   |
| Unknown (XXX)           | 5         | 0.26%   |
| KDC                     | 5         | 0.26%   |
| UTV                     | 4         | 0.21%   |
| SANYO                   | 4         | 0.21%   |
| JRY                     | 4         | 0.21%   |
| ITE                     | 4         | 0.21%   |
| GDH                     | 4         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 23        | 1.15%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 21        | 1.05%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 18        | 0.9%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 18        | 0.9%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 17        | 0.85%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 480x270mm 21.7-inch    | 15        | 0.75%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 15        | 0.75%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 14        | 0.7%    |
| Hitachi HDMI HEC0088 1920x540                                        | 14        | 0.7%    |
| SKY TV-monitor SKY0001 1360x768 890x500mm 40.2-inch                  | 12        | 0.6%    |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                 | 12        | 0.6%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 11        | 0.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 11        | 0.55%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 11        | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch    | 10        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 10        | 0.5%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 10        | 0.5%    |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 9         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 9         | 0.45%   |
| Samsung Electronics S19D300 SAM0B36 1366x768 410x230mm 18.5-inch     | 9         | 0.45%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 9         | 0.45%   |
| Goldstar 23EA53 GSM59A9 1920x1080 510x290mm 23.1-inch                | 9         | 0.45%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 8         | 0.4%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 8         | 0.4%    |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch          | 8         | 0.4%    |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 8         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 8         | 0.4%    |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 8         | 0.4%    |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch    | 7         | 0.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 7         | 0.35%   |
| Goldstar E2340 GSM57C7 1920x1080 510x290mm 23.1-inch                 | 7         | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 7         | 0.35%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch    | 6         | 0.3%    |
| Samsung Electronics S19D300 SAM0B35 1366x768 410x230mm 18.5-inch     | 6         | 0.3%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch    | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                 | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 6         | 0.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch              | 6         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 669       | 35.83%  |
| 1366x768 (WXGA)    | 652       | 34.92%  |
| 1280x1024 (SXGA)   | 65        | 3.48%   |
| 3840x2160 (4K)     | 64        | 3.43%   |
| 1600x900 (HD+)     | 62        | 3.32%   |
| 1440x900 (WXGA+)   | 50        | 2.68%   |
| 1360x768           | 50        | 2.68%   |
| 1280x800 (WXGA)    | 49        | 2.62%   |
| 1680x1050 (WSXGA+) | 46        | 2.46%   |
| 1920x1200 (WUXGA)  | 25        | 1.34%   |
| 1920x540           | 19        | 1.02%   |
| 2560x1440 (QHD)    | 12        | 0.64%   |
| 1024x600           | 12        | 0.64%   |
| Unknown            | 11        | 0.59%   |
| 2560x1080          | 10        | 0.54%   |
| 1024x768 (XGA)     | 10        | 0.54%   |
| 1280x720 (HD)      | 7         | 0.37%   |
| 3200x1800 (QHD+)   | 5         | 0.27%   |
| 2288x1287          | 4         | 0.21%   |
| 1152x864           | 4         | 0.21%   |
| 3840x2400          | 3         | 0.16%   |
| 3840x1080          | 3         | 0.16%   |
| 3440x1440          | 3         | 0.16%   |
| 2880x1800          | 3         | 0.16%   |
| 2560x1600          | 3         | 0.16%   |
| 3456x2160          | 2         | 0.11%   |
| 2160x1440          | 2         | 0.11%   |
| 2048x1152          | 2         | 0.11%   |
| 1280x960           | 2         | 0.11%   |
| 4093x4093          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3600x1200          | 1         | 0.05%   |
| 3286x1080          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |
| 3072x1920          | 1         | 0.05%   |
| 3046x1050          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 2880x1620          | 1         | 0.05%   |
| 2736x1824          | 1         | 0.05%   |
| 2646x1024          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 521       | 26.64%  |
| 14      | 198       | 10.12%  |
| 13      | 184       | 9.41%   |
| 23      | 154       | 7.87%   |
| 21      | 151       | 7.72%   |
| 18      | 132       | 6.75%   |
| 17      | 67        | 3.43%   |
| Unknown | 61        | 3.12%   |
| 24      | 60        | 3.07%   |
| 19      | 56        | 2.86%   |
| 20      | 49        | 2.51%   |
| 27      | 47        | 2.4%    |
| 40      | 36        | 1.84%   |
| 10      | 28        | 1.43%   |
| 22      | 20        | 1.02%   |
| 31      | 18        | 0.92%   |
| 16      | 18        | 0.92%   |
| 52      | 17        | 0.87%   |
| 48      | 17        | 0.87%   |
| 12      | 17        | 0.87%   |
| 11      | 16        | 0.82%   |
| 84      | 15        | 0.77%   |
| 32      | 12        | 0.61%   |
| 46      | 11        | 0.56%   |
| 34      | 11        | 0.56%   |
| 54      | 10        | 0.51%   |
| 142     | 4         | 0.2%    |
| 72      | 3         | 0.15%   |
| 65      | 3         | 0.15%   |
| 39      | 3         | 0.15%   |
| 26      | 3         | 0.15%   |
| 55      | 2         | 0.1%    |
| 47      | 2         | 0.1%    |
| 30      | 2         | 0.1%    |
| 25      | 2         | 0.1%    |
| 64      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 41      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 869       | 45%     |
| 401-500        | 392       | 20.3%   |
| 501-600        | 248       | 12.84%  |
| 201-300        | 110       | 5.7%    |
| 351-400        | 74        | 3.83%   |
| 1001-1500      | 63        | 3.26%   |
| Unknown        | 61        | 3.16%   |
| 801-900        | 40        | 2.07%   |
| 601-700        | 26        | 1.35%   |
| 701-800        | 23        | 1.19%   |
| 1501-2000      | 18        | 0.93%   |
| More than 2000 | 4         | 0.21%   |
| 901-1000       | 3         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1396      | 80.23%  |
| 16/10   | 159       | 9.14%   |
| Unknown | 53        | 3.05%   |
| 5/4     | 45        | 2.59%   |
| 4/3     | 43        | 2.47%   |
| 1.96    | 14        | 0.8%    |
| 21/9    | 12        | 0.69%   |
| 3/2     | 10        | 0.57%   |
| 1.00    | 4         | 0.23%   |
| 32/9    | 2         | 0.11%   |
| 3.40    | 1         | 0.06%   |
| 0.89    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 501       | 25.86%  |
| 81-90          | 343       | 17.71%  |
| 201-250        | 342       | 17.66%  |
| 141-150        | 157       | 8.11%   |
| 151-200        | 135       | 6.97%   |
| 501-1000       | 70        | 3.61%   |
| Unknown        | 61        | 3.15%   |
| More than 1000 | 56        | 2.89%   |
| 301-350        | 49        | 2.53%   |
| 351-500        | 43        | 2.22%   |
| 71-80          | 37        | 1.91%   |
| 121-130        | 32        | 1.65%   |
| 111-120        | 31        | 1.6%    |
| 41-50          | 28        | 1.45%   |
| 51-60          | 17        | 0.88%   |
| 61-70          | 12        | 0.62%   |
| 251-300        | 10        | 0.52%   |
| 131-140        | 7         | 0.36%   |
| 91-100         | 6         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 731       | 38.51%  |
| 51-100        | 646       | 34.04%  |
| 121-160       | 306       | 16.12%  |
| 1-50          | 99        | 5.22%   |
| Unknown       | 61        | 3.21%   |
| 161-240       | 37        | 1.95%   |
| More than 240 | 18        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1499      | 80.33%  |
| 2     | 277       | 14.84%  |
| 0     | 74        | 3.97%   |
| 3     | 15        | 0.8%    |
| 5     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1201      | 44.5%   |
| Intel                                 | 560       | 20.75%  |
| Qualcomm Atheros                      | 332       | 12.3%   |
| Broadcom                              | 96        | 3.56%   |
| TP-Link                               | 74        | 2.74%   |
| Nvidia                                | 71        | 2.63%   |
| Ralink Technology                     | 44        | 1.63%   |
| Broadcom Limited                      | 34        | 1.26%   |
| Marvell Technology Group              | 33        | 1.22%   |
| Qualcomm Atheros Communications       | 32        | 1.19%   |
| JMicron Technology                    | 25        | 0.93%   |
| Ralink                                | 24        | 0.89%   |
| Samsung Electronics                   | 23        | 0.85%   |
| VIA Technologies                      | 20        | 0.74%   |
| MediaTek                              | 16        | 0.59%   |
| Silicon Integrated Systems [SiS]      | 15        | 0.56%   |
| Motorola PCS                          | 15        | 0.56%   |
| Microsoft                             | 9         | 0.33%   |
| ASIX Electronics                      | 7         | 0.26%   |
| Xiaomi                                | 4         | 0.15%   |
| NetGear                               | 4         | 0.15%   |
| D-Link System                         | 4         | 0.15%   |
| Sundance Technology Inc / IC Plus     | 3         | 0.11%   |
| ICS Advent                            | 3         | 0.11%   |
| Ericsson Business Mobile Networks     | 3         | 0.11%   |
| DisplayLink                           | 3         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.11%   |
| 3Com                                  | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.07%   |
| T & A Mobile Phones                   | 2         | 0.07%   |
| Standard Microsystems                 | 2         | 0.07%   |
| Ovislink                              | 2         | 0.07%   |
| Linksys                               | 2         | 0.07%   |
| LG Electronics                        | 2         | 0.07%   |
| Lenovo                                | 2         | 0.07%   |
| Huawei Technologies                   | 2         | 0.07%   |
| Encore Electronics                    | 2         | 0.07%   |
| Davicom Semiconductor                 | 2         | 0.07%   |
| D-Link                                | 2         | 0.07%   |
| Arduino SA                            | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 820       | 25.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 182       | 5.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 63        | 1.98%   |
| Nvidia MCP61 Ethernet                                             | 62        | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 51        | 1.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 47        | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 44        | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 44        | 1.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 42        | 1.32%   |
| Intel Wi-Fi 6 AX201                                               | 37        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 35        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 35        | 1.1%    |
| Intel Wi-Fi 6 AX200                                               | 35        | 1.1%    |
| Intel Wireless 3160                                               | 32        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 31        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 31        | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                   | 29        | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 28        | 0.88%   |
| Intel Wireless 3165                                               | 28        | 0.88%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 0.75%   |
| Intel Wireless 8265 / 8275                                        | 24        | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 24        | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 23        | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 23        | 0.72%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 22        | 0.69%   |
| Ralink MT7601U Wireless Adapter                                   | 22        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 0.69%   |
| Intel Wireless 7260                                               | 22        | 0.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 0.69%   |
| Intel I211 Gigabit Network Connection                             | 21        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 20        | 0.63%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 19        | 0.6%    |
| Intel Wireless 7265                                               | 19        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 19        | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 0.57%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16        | 0.5%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 16        | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 440       | 31.05%  |
| Realtek Semiconductor                 | 387       | 27.31%  |
| Qualcomm Atheros                      | 276       | 19.48%  |
| Broadcom                              | 81        | 5.72%   |
| TP-Link                               | 65        | 4.59%   |
| Ralink Technology                     | 44        | 3.11%   |
| Qualcomm Atheros Communications       | 32        | 2.26%   |
| Ralink                                | 24        | 1.69%   |
| Broadcom Limited                      | 19        | 1.34%   |
| MediaTek                              | 12        | 0.85%   |
| Microsoft                             | 8         | 0.56%   |
| NetGear                               | 4         | 0.28%   |
| Marvell Technology Group              | 4         | 0.28%   |
| D-Link System                         | 4         | 0.28%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.21%   |
| Ovislink                              | 2         | 0.14%   |
| Linksys                               | 2         | 0.14%   |
| Encore Electronics                    | 2         | 0.14%   |
| D-Link                                | 2         | 0.14%   |
| ZyDAS                                 | 1         | 0.07%   |
| Sierra Wireless                       | 1         | 0.07%   |
| Samsung Electronics                   | 1         | 0.07%   |
| Ericsson Business Mobile Networks     | 1         | 0.07%   |
| Dell                                  | 1         | 0.07%   |
| Cisco Aironet Wireless Communications | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 63        | 4.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 51        | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 47        | 3.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 44        | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 44        | 3.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 42        | 2.94%   |
| Intel Wi-Fi 6 AX201                                                     | 37        | 2.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 2.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 35        | 2.45%   |
| Intel Wi-Fi 6 AX200                                                     | 35        | 2.45%   |
| Intel Wireless 3160                                                     | 32        | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 2.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 2.17%   |
| Qualcomm Atheros AR9271 802.11n                                         | 29        | 2.03%   |
| Intel Wireless 3165                                                     | 28        | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 24        | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 1.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 23        | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 22        | 1.54%   |
| Ralink MT7601U Wireless Adapter                                         | 22        | 1.54%   |
| Intel Wireless 7260                                                     | 22        | 1.54%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 20        | 1.4%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 19        | 1.33%   |
| Intel Wireless 7265                                                     | 19        | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 19        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 1.26%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 16        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 1.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 15        | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 1.05%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 14        | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 14        | 0.98%   |
| Intel Wireless 8260                                                     | 14        | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 13        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 0.91%   |
| Realtek 802.11n WLAN Adapter                                            | 12        | 0.84%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 12        | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.84%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 12        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1066      | 62.09%  |
| Intel                             | 244       | 14.21%  |
| Qualcomm Atheros                  | 118       | 6.87%   |
| Nvidia                            | 71        | 4.14%   |
| Marvell Technology Group          | 29        | 1.69%   |
| Broadcom                          | 27        | 1.57%   |
| JMicron Technology                | 25        | 1.46%   |
| VIA Technologies                  | 20        | 1.16%   |
| Samsung Electronics               | 20        | 1.16%   |
| Silicon Integrated Systems [SiS]  | 15        | 0.87%   |
| Broadcom Limited                  | 15        | 0.87%   |
| Motorola PCS                      | 13        | 0.76%   |
| TP-Link                           | 10        | 0.58%   |
| ASIX Electronics                  | 7         | 0.41%   |
| Xiaomi                            | 4         | 0.23%   |
| MediaTek                          | 4         | 0.23%   |
| Sundance Technology Inc / IC Plus | 3         | 0.17%   |
| ICS Advent                        | 3         | 0.17%   |
| DisplayLink                       | 3         | 0.17%   |
| 3Com                              | 3         | 0.17%   |
| T & A Mobile Phones               | 2         | 0.12%   |
| Standard Microsystems             | 2         | 0.12%   |
| Lenovo                            | 2         | 0.12%   |
| Davicom Semiconductor             | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| Spreadtrum Communications         | 1         | 0.06%   |
| Microsoft                         | 1         | 0.06%   |
| Macronix [MXIC]                   | 1         | 0.06%   |
| LG Electronics                    | 1         | 0.06%   |
| Huawei Technologies               | 1         | 0.06%   |
| Digitech Systems                  | 1         | 0.06%   |
| Aquantia                          | 1         | 0.06%   |
| 3DSP                              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 820       | 47.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 182       | 10.5%   |
| Nvidia MCP61 Ethernet                                             | 62        | 3.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 28        | 1.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 24        | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 1.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 23        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 21        | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 1.15%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 16        | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 0.92%   |
| Intel Ethernet Controller I225-V                                  | 16        | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 0.75%   |
| Motorola PCS XT1032                                               | 13        | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.75%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 12        | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.63%   |
| Intel Ethernet Connection (10) I219-V                             | 11        | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 9         | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.4%    |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 7         | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 6         | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.35%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 6         | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.35%   |
| Intel PRO/100 VE Network Connection                               | 6         | 0.35%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.35%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.35%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1625      | 54.26%  |
| WiFi     | 1350      | 45.08%  |
| Modem    | 17        | 0.57%   |
| Unknown  | 3         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1112      | 59.47%  |
| Ethernet | 757       | 40.48%  |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 961       | 52.48%  |
| 1     | 795       | 43.42%  |
| 0     | 48        | 2.62%   |
| 3     | 23        | 1.26%   |
| 4     | 2         | 0.11%   |
| 32    | 1         | 0.05%   |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1606      | 87%     |
| Yes  | 240       | 13%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 356       | 40.92%  |
| Realtek Semiconductor           | 158       | 18.16%  |
| Qualcomm Atheros Communications | 70        | 8.05%   |
| Cambridge Silicon Radio         | 60        | 6.9%    |
| IMC Networks                    | 47        | 5.4%    |
| Broadcom                        | 42        | 4.83%   |
| Lite-On Technology              | 34        | 3.91%   |
| Foxconn / Hon Hai               | 22        | 2.53%   |
| Apple                           | 16        | 1.84%   |
| Dell                            | 13        | 1.49%   |
| Toshiba                         | 10        | 1.15%   |
| ASUSTek Computer                | 8         | 0.92%   |
| Ralink                          | 7         | 0.8%    |
| Integrated System Solution      | 5         | 0.57%   |
| TP-Link                         | 4         | 0.46%   |
| Hewlett-Packard                 | 3         | 0.34%   |
| USI                             | 2         | 0.23%   |
| Qcom                            | 2         | 0.23%   |
| Marvell Semiconductor           | 2         | 0.23%   |
| Alps Electric                   | 2         | 0.23%   |
| Syntek                          | 1         | 0.11%   |
| Roper                           | 1         | 0.11%   |
| Realtek                         | 1         | 0.11%   |
| Logitech                        | 1         | 0.11%   |
| Foxconn International           | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Conwise Technology              | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 143       | 16.42%  |
| Realtek Bluetooth Radio                             | 90        | 10.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 64        | 7.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 60        | 6.89%   |
| Intel AX201 Bluetooth                               | 58        | 6.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 5.05%   |
| Qualcomm Atheros  Bluetooth Device                  | 36        | 4.13%   |
| Intel AX200 Bluetooth                               | 36        | 4.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 19        | 2.18%   |
| Realtek RTL8723B Bluetooth                          | 18        | 2.07%   |
| IMC Networks Bluetooth Radio                        | 18        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 1.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 15        | 1.72%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.38%   |
| IMC Networks Bluetooth Device                       | 12        | 1.38%   |
| Lite-On Bluetooth Device                            | 11        | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.92%   |
| Toshiba Bluetooth USB Host Controller               | 7         | 0.8%    |
| Ralink RT3290 Bluetooth                             | 7         | 0.8%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.8%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 7         | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 0.69%   |
| IMC Networks Wireless_Device                        | 6         | 0.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.69%   |
| Apple Bluetooth USB Host Controller                 | 6         | 0.69%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 5         | 0.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.57%   |
| Intel AX210 Bluetooth                               | 5         | 0.57%   |
| Dell Wireless 365 Bluetooth                         | 5         | 0.57%   |
| TP-Link UB500 Adapter                               | 4         | 0.46%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.46%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 4         | 0.46%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.46%   |
| Apple Bluetooth HCI                                 | 4         | 0.46%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.34%   |
| Lite-On Bluetooth Radio                             | 3         | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 1223      | 54.07%  |
| AMD                                             | 530       | 23.43%  |
| Nvidia                                          | 287       | 12.69%  |
| Logitech                                        | 39        | 1.72%   |
| C-Media Electronics                             | 31        | 1.37%   |
| VIA Technologies                                | 18        | 0.8%    |
| Silicon Integrated Systems [SiS]                | 15        | 0.66%   |
| Kingston Technology                             | 15        | 0.66%   |
| Generalplus Technology                          | 9         | 0.4%    |
| Texas Instruments                               | 8         | 0.35%   |
| Creative Labs                                   | 8         | 0.35%   |
| Focusrite-Novation                              | 7         | 0.31%   |
| Plantronics                                     | 6         | 0.27%   |
| M-Audio                                         | 4         | 0.18%   |
| GN Netcom                                       | 4         | 0.18%   |
| Elite Silicon                                   | 4         | 0.18%   |
| Samson Technologies                             | 3         | 0.13%   |
| Fry's Electronics                               | 3         | 0.13%   |
| ESI Audiotechnik                                | 3         | 0.13%   |
| Creative Technology                             | 3         | 0.13%   |
| ATI Technologies                                | 3         | 0.13%   |
| ASUSTek Computer                                | 3         | 0.13%   |
| Astro Gaming                                    | 3         | 0.13%   |
| Realtek Semiconductor                           | 2         | 0.09%   |
| Razer USA                                       | 2         | 0.09%   |
| Microsoft                                       | 2         | 0.09%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.09%   |
| Lenovo                                          | 2         | 0.09%   |
| JMTek                                           | 2         | 0.09%   |
| Ensoniq                                         | 2         | 0.09%   |
| Corsair                                         | 2         | 0.09%   |
| BEHRINGER International                         | 2         | 0.09%   |
| Yamaha                                          | 1         | 0.04%   |
| TEAC                                            | 1         | 0.04%   |
| Samsung Electronics                             | 1         | 0.04%   |
| Pro-Ject                                        | 1         | 0.04%   |
| Micro Star International                        | 1         | 0.04%   |
| Holtek Semiconductor                            | 1         | 0.04%   |
| Hewlett-Packard                                 | 1         | 0.04%   |
| Giga-Byte Technology                            | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 148       | 5.36%   |
| AMD Family 17h/19h HD Audio Controller                                     | 135       | 4.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 132       | 4.78%   |
| AMD FCH Azalia Controller                                                  | 115       | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 109       | 3.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 108       | 3.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 86        | 3.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 76        | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 67        | 2.43%   |
| Nvidia MCP61 High Definition Audio                                         | 65        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 54        | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 54        | 1.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52        | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 52        | 1.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 46        | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 44        | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 44        | 1.59%   |
| AMD Starship/Matisse HD Audio Controller                                   | 43        | 1.56%   |
| AMD Kabini HDMI/DP Audio                                                   | 41        | 1.48%   |
| Intel Comet Lake PCH-LP cAVS                                               | 38        | 1.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 38        | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 36        | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 34        | 1.23%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 1.2%    |
| Intel Haswell-ULT HD Audio Controller                                      | 32        | 1.16%   |
| Intel 8 Series HD Audio Controller                                         | 32        | 1.16%   |
| AMD Trinity HDMI Audio Controller                                          | 32        | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 30        | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 30        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 29        | 1.05%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 29        | 1.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 28        | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 1.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 28        | 1.01%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 27        | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 27        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 26        | 0.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 0.91%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 24        | 0.87%   |
| Nvidia High Definition Audio Controller                                    | 23        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Kingston                                         | 267       | 24.12%  |
| Samsung Electronics                              | 197       | 17.8%   |
| SK hynix                                         | 133       | 12.01%  |
| Unknown                                          | 122       | 11.02%  |
| Micron Technology                                | 60        | 5.42%   |
| Crucial                                          | 57        | 5.15%   |
| A-DATA Technology                                | 42        | 3.79%   |
| Corsair                                          | 36        | 3.25%   |
| Unknown (ABCD)                                   | 15        | 1.36%   |
| Nanya Technology                                 | 14        | 1.26%   |
| Magnum Tech                                      | 14        | 1.26%   |
| Novatech                                         | 11        | 0.99%   |
| G.Skill                                          | 10        | 0.9%    |
| Elpida                                           | 10        | 0.9%    |
| Unknown                                          | 10        | 0.9%    |
| Goldkey                                          | 9         | 0.81%   |
| Avant                                            | 9         | 0.81%   |
| Ramaxel Technology                               | 8         | 0.72%   |
| Patriot                                          | 8         | 0.72%   |
| Saikano                                          | 6         | 0.54%   |
| Transcend                                        | 5         | 0.45%   |
| Super Talent                                     | 5         | 0.45%   |
| Memox                                            | 5         | 0.45%   |
| Hewlett-Packard                                  | 5         | 0.45%   |
| Team                                             | 4         | 0.36%   |
| PNY                                              | 4         | 0.36%   |
| Neo Forza                                        | 3         | 0.27%   |
| Kingmax                                          | 3         | 0.27%   |
| CSX                                              | 3         | 0.27%   |
| Apacer                                           | 3         | 0.27%   |
| 48spaces                                         | 3         | 0.27%   |
| Teikon                                           | 2         | 0.18%   |
| Ramos Technology                                 | 2         | 0.18%   |
| Netac                                            | 2         | 0.18%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.09%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.09%   |
| Unknown (07D5)                                   | 1         | 0.09%   |
| Toshiba                                          | 1         | 0.09%   |
| Thermaltake                                      | 1         | 0.09%   |
| SHARETRONIC                                      | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 1.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 14        | 1.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.17%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s              | 13        | 1.08%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 1%      |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1%      |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.92%   |
| Unknown                                                          | 10        | 0.83%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 9         | 0.75%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 9         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.67%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 8         | 0.67%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 8         | 0.67%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 7         | 0.58%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 6         | 0.5%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.5%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 6         | 0.5%    |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s              | 6         | 0.5%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.42%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 5         | 0.42%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.42%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.42%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                      | 5         | 0.42%   |
| Kingston RAM KHX1866C10D3/ 8GB DIMM DDR3 1866MT/s                | 5         | 0.42%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 5         | 0.42%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 5         | 0.42%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 5         | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 333MT/s                         | 4         | 0.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 4         | 0.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.33%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 409       | 44.12%  |
| DDR3    | 347       | 37.43%  |
| DDR2    | 50        | 5.39%   |
| Unknown | 42        | 4.53%   |
| LPDDR4  | 27        | 2.91%   |
| SDRAM   | 22        | 2.37%   |
| LPDDR3  | 12        | 1.29%   |
| DDR     | 9         | 0.97%   |
| DRAM    | 4         | 0.43%   |
| LPDDR5  | 3         | 0.32%   |
| DDR5    | 2         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 522       | 56.37%  |
| DIMM         | 356       | 38.44%  |
| Row Of Chips | 45        | 4.86%   |
| Chip         | 2         | 0.22%   |
| Unknown      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 403       | 38.24%  |
| 4096  | 316       | 29.98%  |
| 2048  | 158       | 14.99%  |
| 16384 | 112       | 10.63%  |
| 1024  | 35        | 3.32%   |
| 32768 | 23        | 2.18%   |
| 512   | 5         | 0.47%   |
| 6144  | 1         | 0.09%   |
| 256   | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 205       | 19.52%  |
| 2667    | 162       | 15.43%  |
| 3200    | 136       | 12.95%  |
| 1333    | 113       | 10.76%  |
| 2400    | 86        | 8.19%   |
| 2133    | 47        | 4.48%   |
| 1334    | 36        | 3.43%   |
| Unknown | 32        | 3.05%   |
| 667     | 25        | 2.38%   |
| 3600    | 21        | 2%      |
| 800     | 16        | 1.52%   |
| 3266    | 15        | 1.43%   |
| 1067    | 12        | 1.14%   |
| 1066    | 12        | 1.14%   |
| 3400    | 11        | 1.05%   |
| 1866    | 11        | 1.05%   |
| 533     | 11        | 1.05%   |
| 2666    | 10        | 0.95%   |
| 3466    | 9         | 0.86%   |
| 333     | 8         | 0.76%   |
| 4199    | 7         | 0.67%   |
| 3000    | 7         | 0.67%   |
| 2933    | 6         | 0.57%   |
| 400     | 6         | 0.57%   |
| 1867    | 5         | 0.48%   |
| 4267    | 4         | 0.38%   |
| 2800    | 4         | 0.38%   |
| 975     | 4         | 0.38%   |
| 6400    | 3         | 0.29%   |
| 2048    | 3         | 0.29%   |
| 8400    | 2         | 0.19%   |
| 4800    | 2         | 0.19%   |
| 3933    | 2         | 0.19%   |
| 3151    | 2         | 0.19%   |
| 3007    | 2         | 0.19%   |
| 4266    | 1         | 0.1%    |
| 3866    | 1         | 0.1%    |
| 3733    | 1         | 0.1%    |
| 3533    | 1         | 0.1%    |
| 3500    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 29        | 48.33%  |
| Brother Industries  | 17        | 28.33%  |
| Seiko Epson         | 5         | 8.33%   |
| Samsung Electronics | 3         | 5%      |
| Ricoh               | 1         | 1.67%   |
| QinHeng Electronics | 1         | 1.67%   |
| Pantum              | 1         | 1.67%   |
| NXP Semiconductors  | 1         | 1.67%   |
| Kyocera             | 1         | 1.67%   |
| Graphtec America    | 1         | 1.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| HP LaserJet Professional P1102w               | 5         | 8.33%   |
| Brother HL-1200 series                        | 4         | 6.67%   |
| Brother HL-1110 series                        | 4         | 6.67%   |
| HP LaserJet Professional P 1102w              | 3         | 5%      |
| Brother HL-1210W series                       | 3         | 5%      |
| Samsung M2020 Series                          | 2         | 3.33%   |
| HP LaserJet P1006                             | 2         | 3.33%   |
| HP LaserJet P1005                             | 2         | 3.33%   |
| HP Ink Tank 110 series                        | 2         | 3.33%   |
| Brother HL-2130 series                        | 2         | 3.33%   |
| Brother DCP-7055 scanner/printer              | 2         | 3.33%   |
| Seiko Epson XP-240 Series                     | 1         | 1.67%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 1.67%   |
| Seiko Epson L355 Series                       | 1         | 1.67%   |
| Seiko Epson L120 Series                       | 1         | 1.67%   |
| Seiko Epson ET-2700 Series                    | 1         | 1.67%   |
| Samsung Xerox Phaser 3117 Laser Printer       | 1         | 1.67%   |
| Ricoh Printing Support                        | 1         | 1.67%   |
| QinHeng CH340S                                | 1         | 1.67%   |
| Pantum P2500W series                          | 1         | 1.67%   |
| NXP Semiconductors Printer-80                 | 1         | 1.67%   |
| Kyocera ECOSYS M3550idn                       | 1         | 1.67%   |
| HP PSC 1400                                   | 1         | 1.67%   |
| HP Officejet 4500 G510a-f                     | 1         | 1.67%   |
| HP Laserjet P1505                             | 1         | 1.67%   |
| HP LaserJet M203-M206                         | 1         | 1.67%   |
| HP LaserJet 3050                              | 1         | 1.67%   |
| HP LaserJet 1020                              | 1         | 1.67%   |
| HP Ink Tank Wireless 410 series               | 1         | 1.67%   |
| HP DeskJet F4100 Printer series               | 1         | 1.67%   |
| HP DeskJet F300 series                        | 1         | 1.67%   |
| HP DeskJet 810c/812c                          | 1         | 1.67%   |
| HP DeskJet 3630 series                        | 1         | 1.67%   |
| HP Deskjet 3050 J610 series                   | 1         | 1.67%   |
| HP DeskJet 2620 All-in-One Printer            | 1         | 1.67%   |
| HP Deskjet 2050 J510                          | 1         | 1.67%   |
| HP Color LaserJet Pro M478f-9f                | 1         | 1.67%   |
| Graphtec America Graphtec Printer             | 1         | 1.67%   |
| Brother DCP-1610NW                            | 1         | 1.67%   |
| Brother DCP-1600                              | 1         | 1.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 220       | 20.33%  |
| IMC Networks                           | 99        | 9.15%   |
| Realtek Semiconductor                  | 85        | 7.86%   |
| Microdia                               | 82        | 7.58%   |
| Bison Electronics                      | 71        | 6.56%   |
| Logitech                               | 46        | 4.25%   |
| Syntek                                 | 41        | 3.79%   |
| Sunplus Innovation Technology          | 39        | 3.6%    |
| Quanta                                 | 39        | 3.6%    |
| Suyin                                  | 35        | 3.23%   |
| Alcor Micro                            | 34        | 3.14%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 3.05%   |
| Silicon Motion                         | 32        | 2.96%   |
| Acer                                   | 31        | 2.87%   |
| Apple                                  | 20        | 1.85%   |
| Samsung Electronics                    | 18        | 1.66%   |
| Z-Star Microelectronics                | 14        | 1.29%   |
| Luxvisions Innotech Limited            | 13        | 1.2%    |
| KYE Systems (Mouse Systems)            | 13        | 1.2%    |
| Generalplus Technology                 | 13        | 1.2%    |
| Ricoh                                  | 12        | 1.11%   |
| Lite-On Technology                     | 12        | 1.11%   |
| OmniVision Technologies                | 7         | 0.65%   |
| Microsoft                              | 7         | 0.65%   |
| Sonix Technology                       | 6         | 0.55%   |
| Jieli Technology                       | 6         | 0.55%   |
| SunplusIT                              | 5         | 0.46%   |
| icSpring                               | 5         | 0.46%   |
| GEMBIRD                                | 4         | 0.37%   |
| Cubeternet                             | 4         | 0.37%   |
| ALi                                    | 4         | 0.37%   |
| Y Media                                | 3         | 0.28%   |
| Pixart Imaging                         | 3         | 0.28%   |
| MacroSilicon                           | 3         | 0.28%   |
| Lenovo                                 | 3         | 0.28%   |
| Razer USA                              | 2         | 0.18%   |
| Intel                                  | 2         | 0.18%   |
| Importek                               | 2         | 0.18%   |
| Genesys Logic                          | 2         | 0.18%   |
| Aveo Technology                        | 2         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony USB 2.0 camera                                         | 36        | 3.31%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 32        | 2.94%   |
| IMC Networks Integrated Camera                                 | 28        | 2.57%   |
| Alcor Micro USB 2.0 Camera                                     | 24        | 2.21%   |
| Microdia Integrated_Webcam_HD                                  | 23        | 2.11%   |
| Realtek Integrated_Webcam_HD                                   | 21        | 1.93%   |
| Chicony Integrated Camera                                      | 20        | 1.84%   |
| Realtek USB Camera                                             | 18        | 1.65%   |
| Bison Integrated Camera                                        | 18        | 1.65%   |
| Acer Integrated Camera                                         | 18        | 1.65%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 17        | 1.56%   |
| Syntek Integrated Camera                                       | 16        | 1.47%   |
| Chicony Lenovo EasyCamera                                      | 15        | 1.38%   |
| Chicony USB2.0 Camera                                          | 14        | 1.29%   |
| Logitech Webcam C270                                           | 13        | 1.19%   |
| Chicony HD Webcam                                              | 13        | 1.19%   |
| Sunplus Integrated_Webcam_HD                                   | 12        | 1.1%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 11        | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                                | 11        | 1.01%   |
| Logitech C922 Pro Stream Webcam                                | 10        | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 10        | 0.92%   |
| Luxvisions Innotech Limited Integrated Camera                  | 9         | 0.83%   |
| Chicony HP Wide Vision HD Camera                               | 9         | 0.83%   |
| Bison USB Camera                                               | 9         | 0.83%   |
| Bison Lenovo EasyCamera                                        | 9         | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 9         | 0.83%   |
| Syntek EasyCamera                                              | 8         | 0.74%   |
| Silicon Motion WebCam SC-0311139N                              | 8         | 0.74%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 8         | 0.74%   |
| Bison SunplusIT Integrated Camera                              | 8         | 0.74%   |
| Bison HD Webcam                                                | 8         | 0.74%   |
| Microdia Webcam Vitade AF                                      | 7         | 0.64%   |
| Generalplus GENERAL WEBCAM                                     | 7         | 0.64%   |
| Chicony Integrated Camera (1280x720@30)                        | 7         | 0.64%   |
| Chicony HP TrueVision HD Camera                                | 7         | 0.64%   |
| Bison BisonCam, NB Pro                                         | 7         | 0.64%   |
| Alcor Micro USB 2.0 PC Camera                                  | 7         | 0.64%   |
| Z-Star Webcam                                                  | 6         | 0.55%   |
| Syntek Lenovo EasyCamera                                       | 6         | 0.55%   |
| Sunplus Asus Webcam                                            | 6         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 46        | 34.59%  |
| Validity Sensors                   | 34        | 25.56%  |
| Shenzhen Goodix Technology         | 25        | 18.8%   |
| Elan Microelectronics              | 7         | 5.26%   |
| AuthenTec                          | 7         | 5.26%   |
| Upek                               | 5         | 3.76%   |
| LighTuning Technology              | 5         | 3.76%   |
| STMicroelectronics                 | 1         | 0.75%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.75%   |
| Focal-systems.Corp                 | 1         | 0.75%   |
| DigitalPersona                     | 1         | 0.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 15.04%  |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 13.53%  |
| Synaptics  WBDI                                                            | 13        | 9.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 7.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 4.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 3.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 3.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.01%   |
| Synaptics WBDI                                                             | 4         | 3.01%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.01%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 2.26%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.5%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.5%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.5%    |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.5%    |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.5%    |
| AuthenTec AES2810                                                          | 2         | 1.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.75%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.75%   |
| Synaptics UWP WBDI                                                         | 1         | 0.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.75%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.75%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.75%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.75%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.75%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.75%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.75%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.75%   |
| Unknown                                                                    | 1         | 0.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 63.89%  |
| Upek        | 9         | 25%     |
| Lenovo      | 2         | 5.56%   |
| O2 Micro    | 1         | 2.78%   |
| Alcor Micro | 1         | 2.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 19.44%  |
| Broadcom 58200                                                               | 7         | 19.44%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 16.67%  |
| Broadcom 5880                                                                | 3         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.78%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 2.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1407      | 75.85%  |
| 1     | 391       | 21.08%  |
| 2     | 49        | 2.64%   |
| 3     | 5         | 0.27%   |
| 8     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 151       | 29.9%   |
| Fingerprint reader       | 132       | 26.14%  |
| Net/wireless             | 80        | 15.84%  |
| Chipcard                 | 34        | 6.73%   |
| Camera                   | 23        | 4.55%   |
| Multimedia controller    | 17        | 3.37%   |
| Communication controller | 14        | 2.77%   |
| Bluetooth                | 14        | 2.77%   |
| Sound                    | 10        | 1.98%   |
| Net/ethernet             | 9         | 1.78%   |
| Modem                    | 5         | 0.99%   |
| Network                  | 4         | 0.79%   |
| Unassigned class         | 3         | 0.59%   |
| Storage/ide              | 2         | 0.4%    |
| Flash memory             | 2         | 0.4%    |
| Firewire controller      | 2         | 0.4%    |
| Card reader              | 2         | 0.4%    |
| Dvb card                 | 1         | 0.2%    |


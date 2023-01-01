Linux in Slovenia - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovenia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Slovenia/Desktop/README.md) and [notebooks](/Location/Slovenia/Notebook/README.md).

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

Total: 481

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [9e269ee2a4](https://linux-hardware.org/?probe=9e269ee2a4) | Dec 24, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3948dcc7ef](https://linux-hardware.org/?probe=3948dcc7ef) | Dec 23, 2022 |
| HP            | 8594                        | Desktop     | [de0b36257e](https://linux-hardware.org/?probe=de0b36257e) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cb70181c3a](https://linux-hardware.org/?probe=cb70181c3a) | Dec 21, 2022 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [01b7250cea](https://linux-hardware.org/?probe=01b7250cea) | Dec 19, 2022 |
| Gigabyte      | B650M GAMING X AX           | Desktop     | [999cbfe9f7](https://linux-hardware.org/?probe=999cbfe9f7) | Dec 19, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [1bb0000755](https://linux-hardware.org/?probe=1bb0000755) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [a7b446df37](https://linux-hardware.org/?probe=a7b446df37) | Dec 08, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [59118a0638](https://linux-hardware.org/?probe=59118a0638) | Dec 07, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [a214979767](https://linux-hardware.org/?probe=a214979767) | Dec 07, 2022 |
| Toshiba       | Satellite R630              | Notebook    | [3826be6846](https://linux-hardware.org/?probe=3826be6846) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | Notebook    | [eebafcab9e](https://linux-hardware.org/?probe=eebafcab9e) | Dec 06, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [9d2066a479](https://linux-hardware.org/?probe=9d2066a479) | Dec 03, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [f19b2c0b81](https://linux-hardware.org/?probe=f19b2c0b81) | Dec 03, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [87f1b143de](https://linux-hardware.org/?probe=87f1b143de) | Nov 27, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [5271fa9ef9](https://linux-hardware.org/?probe=5271fa9ef9) | Nov 26, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [673c961915](https://linux-hardware.org/?probe=673c961915) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| HP            | 8591                        | Desktop     | [98bde1bd5a](https://linux-hardware.org/?probe=98bde1bd5a) | Nov 01, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [10d2346f7c](https://linux-hardware.org/?probe=10d2346f7c) | Oct 30, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [1af8ca0ac9](https://linux-hardware.org/?probe=1af8ca0ac9) | Oct 27, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [de0b3e96fa](https://linux-hardware.org/?probe=de0b3e96fa) | Oct 23, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [b91eedb26a](https://linux-hardware.org/?probe=b91eedb26a) | Oct 23, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [9e7b79bfbb](https://linux-hardware.org/?probe=9e7b79bfbb) | Oct 20, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a2e0ee2043](https://linux-hardware.org/?probe=a2e0ee2043) | Oct 15, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| Toshiba       | Satellite A100              | Notebook    | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5348794267](https://linux-hardware.org/?probe=5348794267) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| HP            | 18E4                        | Desktop     | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [660419ed49](https://linux-hardware.org/?probe=660419ed49) | Sep 27, 2022 |
| HP            | Pavilion g7                 | Notebook    | [19b206ba2f](https://linux-hardware.org/?probe=19b206ba2f) | Sep 25, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [0306edc8ba](https://linux-hardware.org/?probe=0306edc8ba) | Sep 22, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [56d6df17b5](https://linux-hardware.org/?probe=56d6df17b5) | Sep 22, 2022 |
| HP            | ProBook 4340s               | Notebook    | [668ffa05ea](https://linux-hardware.org/?probe=668ffa05ea) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | ProBook 4340s               | Notebook    | [1abbd84e9c](https://linux-hardware.org/?probe=1abbd84e9c) | Sep 18, 2022 |
| Toshiba       | TECRA S10                   | Notebook    | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [600ef31484](https://linux-hardware.org/?probe=600ef31484) | Sep 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | Notebook    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| HP            | Unknown                     | Notebook    | [692825c1eb](https://linux-hardware.org/?probe=692825c1eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | Notebook    | [c55fef18c3](https://linux-hardware.org/?probe=c55fef18c3) | Sep 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4c7f501c2b](https://linux-hardware.org/?probe=4c7f501c2b) | Sep 02, 2022 |
| HP            | 8053                        | Desktop     | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | Notebook    | [273e5229a4](https://linux-hardware.org/?probe=273e5229a4) | Aug 30, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [adae304d62](https://linux-hardware.org/?probe=adae304d62) | Aug 24, 2022 |
| Supermicro    | X7SBi-LN4                   | Desktop     | [ec37ffcc15](https://linux-hardware.org/?probe=ec37ffcc15) | Aug 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| Framework     | Laptop                      | Notebook    | [c52019fe10](https://linux-hardware.org/?probe=c52019fe10) | Aug 07, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [b9c35e80d2](https://linux-hardware.org/?probe=b9c35e80d2) | Aug 06, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [c301219c25](https://linux-hardware.org/?probe=c301219c25) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [6ab4942a20](https://linux-hardware.org/?probe=6ab4942a20) | Jul 16, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [0e195b05bf](https://linux-hardware.org/?probe=0e195b05bf) | Jul 13, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [d9573dc3e6](https://linux-hardware.org/?probe=d9573dc3e6) | Jul 08, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [f6efa72c1f](https://linux-hardware.org/?probe=f6efa72c1f) | Jul 01, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d59692d648](https://linux-hardware.org/?probe=d59692d648) | Jun 29, 2022 |
| ASRock        | H61M-ITX                    | Desktop     | [4afafc5b76](https://linux-hardware.org/?probe=4afafc5b76) | Jun 29, 2022 |
| IBM           | 00AM527                     | Server      | [8af3a08c43](https://linux-hardware.org/?probe=8af3a08c43) | Jun 26, 2022 |
| HP            | 212B                        | Desktop     | [a163af0cb5](https://linux-hardware.org/?probe=a163af0cb5) | Jun 21, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [cae0332804](https://linux-hardware.org/?probe=cae0332804) | Jun 17, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [e65ead281f](https://linux-hardware.org/?probe=e65ead281f) | Jun 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc2e6a1605](https://linux-hardware.org/?probe=cc2e6a1605) | Jun 17, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [28c5fad176](https://linux-hardware.org/?probe=28c5fad176) | Jun 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f4c9e8f3f2](https://linux-hardware.org/?probe=f4c9e8f3f2) | May 30, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [14ebca03fe](https://linux-hardware.org/?probe=14ebca03fe) | May 30, 2022 |
| Toshiba       | Satellite Pro U400          | Notebook    | [4aeeca648d](https://linux-hardware.org/?probe=4aeeca648d) | May 24, 2022 |
| Intel         | CM-iAM/SBC-FITPC2i          | Desktop     | [cbfe433386](https://linux-hardware.org/?probe=cbfe433386) | May 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [33a6047c0b](https://linux-hardware.org/?probe=33a6047c0b) | May 14, 2022 |
| ASUSTek       | N71Vg                       | Notebook    | [86d9e911f1](https://linux-hardware.org/?probe=86d9e911f1) | May 13, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [86d60d0227](https://linux-hardware.org/?probe=86d60d0227) | May 12, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [934d403a31](https://linux-hardware.org/?probe=934d403a31) | May 04, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [373f22a70f](https://linux-hardware.org/?probe=373f22a70f) | May 03, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [91a367d874](https://linux-hardware.org/?probe=91a367d874) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [965985d6f4](https://linux-hardware.org/?probe=965985d6f4) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [81409450dc](https://linux-hardware.org/?probe=81409450dc) | Apr 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [f727388ac8](https://linux-hardware.org/?probe=f727388ac8) | Apr 17, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c1102c77ec](https://linux-hardware.org/?probe=c1102c77ec) | Apr 17, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d7b7a81cbb](https://linux-hardware.org/?probe=d7b7a81cbb) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [76a5225b83](https://linux-hardware.org/?probe=76a5225b83) | Apr 16, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [0dd1b326c0](https://linux-hardware.org/?probe=0dd1b326c0) | Apr 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [8570b5ab84](https://linux-hardware.org/?probe=8570b5ab84) | Apr 12, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [222189213d](https://linux-hardware.org/?probe=222189213d) | Apr 11, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | Notebook    | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [0813d4bc9e](https://linux-hardware.org/?probe=0813d4bc9e) | Mar 31, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [defac75126](https://linux-hardware.org/?probe=defac75126) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [da62c7238d](https://linux-hardware.org/?probe=da62c7238d) | Mar 28, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [1260b540e7](https://linux-hardware.org/?probe=1260b540e7) | Mar 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1eebe899b0](https://linux-hardware.org/?probe=1eebe899b0) | Mar 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [f0efa22aa2](https://linux-hardware.org/?probe=f0efa22aa2) | Mar 27, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [0bf3028253](https://linux-hardware.org/?probe=0bf3028253) | Mar 27, 2022 |
| Dell          | Precision 5540              | Notebook    | [38d9bed727](https://linux-hardware.org/?probe=38d9bed727) | Mar 21, 2022 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [55da3ab4e0](https://linux-hardware.org/?probe=55da3ab4e0) | Mar 09, 2022 |
| Supermicro    | X11SCAA                     | Server      | [b850cd60f6](https://linux-hardware.org/?probe=b850cd60f6) | Mar 08, 2022 |
| HP            | Compaq nw8440 (RH415EA#A... | Notebook    | [55a6d982b3](https://linux-hardware.org/?probe=55a6d982b3) | Mar 07, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| HP            | kip                         | Notebook    | [4d6e1264c7](https://linux-hardware.org/?probe=4d6e1264c7) | Mar 02, 2022 |
| HP            | kip                         | Notebook    | [a6ab5d4d8a](https://linux-hardware.org/?probe=a6ab5d4d8a) | Mar 01, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9d5d5c0ffb](https://linux-hardware.org/?probe=9d5d5c0ffb) | Feb 26, 2022 |
| HP            | Pavilion dv7                | Notebook    | [46280b758c](https://linux-hardware.org/?probe=46280b758c) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1c8a37fb2f](https://linux-hardware.org/?probe=1c8a37fb2f) | Feb 24, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [202fc1f0b9](https://linux-hardware.org/?probe=202fc1f0b9) | Feb 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [fd1bbe1769](https://linux-hardware.org/?probe=fd1bbe1769) | Feb 21, 2022 |
| HP            | Pavilion dv7                | Notebook    | [da9449422c](https://linux-hardware.org/?probe=da9449422c) | Feb 21, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [0ee9dcd568](https://linux-hardware.org/?probe=0ee9dcd568) | Feb 20, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5ffa4bce13](https://linux-hardware.org/?probe=5ffa4bce13) | Feb 19, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [5ee5668ab1](https://linux-hardware.org/?probe=5ee5668ab1) | Feb 19, 2022 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [5323885713](https://linux-hardware.org/?probe=5323885713) | Feb 17, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [cad9a70c49](https://linux-hardware.org/?probe=cad9a70c49) | Feb 16, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [676d121bda](https://linux-hardware.org/?probe=676d121bda) | Feb 13, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [df5a829402](https://linux-hardware.org/?probe=df5a829402) | Feb 09, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [239eb94a17](https://linux-hardware.org/?probe=239eb94a17) | Feb 07, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [ec43c5baa2](https://linux-hardware.org/?probe=ec43c5baa2) | Feb 07, 2022 |
| ASUSTek       | X750LN                      | Notebook    | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [901d568e70](https://linux-hardware.org/?probe=901d568e70) | Jan 31, 2022 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [621d099786](https://linux-hardware.org/?probe=621d099786) | Jan 31, 2022 |
| HP            | 1589                        | Desktop     | [41dbcb78cb](https://linux-hardware.org/?probe=41dbcb78cb) | Jan 30, 2022 |
| Pegatron      | EVE                         | Desktop     | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [81e03a6b48](https://linux-hardware.org/?probe=81e03a6b48) | Jan 21, 2022 |
| Pegatron      | EVE                         | Desktop     | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [faba7de732](https://linux-hardware.org/?probe=faba7de732) | Jan 17, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [f2bae7651d](https://linux-hardware.org/?probe=f2bae7651d) | Jan 16, 2022 |
| ASRock        | B85M-HDS                    | Desktop     | [77cb3218a8](https://linux-hardware.org/?probe=77cb3218a8) | Jan 12, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [b9b69a73a3](https://linux-hardware.org/?probe=b9b69a73a3) | Jan 09, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [22e51b8b41](https://linux-hardware.org/?probe=22e51b8b41) | Jan 06, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [52db8d0bbf](https://linux-hardware.org/?probe=52db8d0bbf) | Jan 06, 2022 |
| Lenovo        | ThinkPad T590 20N5S0MR00    | Notebook    | [29040ecce5](https://linux-hardware.org/?probe=29040ecce5) | Jan 01, 2022 |
| MSI           | U210                        | Notebook    | [24eb05a4d9](https://linux-hardware.org/?probe=24eb05a4d9) | Dec 29, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| Lenovo        | ThinkCentre M57e 9439WHV    | Desktop     | [a9b2163945](https://linux-hardware.org/?probe=a9b2163945) | Dec 25, 2021 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [97ec4e3d99](https://linux-hardware.org/?probe=97ec4e3d99) | Dec 25, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [ee70d6b4b4](https://linux-hardware.org/?probe=ee70d6b4b4) | Dec 24, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [8887022aa7](https://linux-hardware.org/?probe=8887022aa7) | Dec 23, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6b40a0f2c5](https://linux-hardware.org/?probe=6b40a0f2c5) | Dec 21, 2021 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [31c2b40e84](https://linux-hardware.org/?probe=31c2b40e84) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [6238c622ad](https://linux-hardware.org/?probe=6238c622ad) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [6aee0ff442](https://linux-hardware.org/?probe=6aee0ff442) | Dec 15, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [45ac665485](https://linux-hardware.org/?probe=45ac665485) | Dec 10, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6649bea1f8](https://linux-hardware.org/?probe=6649bea1f8) | Dec 04, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [723e2a158a](https://linux-hardware.org/?probe=723e2a158a) | Dec 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [6d9c31a411](https://linux-hardware.org/?probe=6d9c31a411) | Nov 28, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [e005ddb405](https://linux-hardware.org/?probe=e005ddb405) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | EliteBook 8760w             | Notebook    | [febc9d2faa](https://linux-hardware.org/?probe=febc9d2faa) | Nov 28, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [df3010e1b8](https://linux-hardware.org/?probe=df3010e1b8) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6016236fad](https://linux-hardware.org/?probe=6016236fad) | Nov 24, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [97409a8d1c](https://linux-hardware.org/?probe=97409a8d1c) | Nov 22, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [e0e4ee802a](https://linux-hardware.org/?probe=e0e4ee802a) | Nov 22, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [e898d8c017](https://linux-hardware.org/?probe=e898d8c017) | Nov 20, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [e37febb0b3](https://linux-hardware.org/?probe=e37febb0b3) | Nov 18, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [163092e4b9](https://linux-hardware.org/?probe=163092e4b9) | Nov 18, 2021 |
| HP            | 250 G3                      | Notebook    | [8d370cbb27](https://linux-hardware.org/?probe=8d370cbb27) | Nov 16, 2021 |
| HP            | 250 G3                      | Notebook    | [fb9fe2f3fb](https://linux-hardware.org/?probe=fb9fe2f3fb) | Nov 16, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [c4e6de1315](https://linux-hardware.org/?probe=c4e6de1315) | Nov 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0f6c2b21cf](https://linux-hardware.org/?probe=0f6c2b21cf) | Nov 14, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [01c20231f2](https://linux-hardware.org/?probe=01c20231f2) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3c3e5bc872](https://linux-hardware.org/?probe=3c3e5bc872) | Nov 08, 2021 |
| HP            | EliteBook 8760w             | Notebook    | [99fb47dc2b](https://linux-hardware.org/?probe=99fb47dc2b) | Oct 28, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [4e5da9e4d3](https://linux-hardware.org/?probe=4e5da9e4d3) | Oct 24, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f66ba65dc8](https://linux-hardware.org/?probe=f66ba65dc8) | Oct 22, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1d50915627](https://linux-hardware.org/?probe=1d50915627) | Oct 21, 2021 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a11d4b7c50](https://linux-hardware.org/?probe=a11d4b7c50) | Oct 20, 2021 |
| Lenovo        | ThinkPad 10 20C10025SC      | Tablet      | [7d6ab19f8d](https://linux-hardware.org/?probe=7d6ab19f8d) | Oct 20, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [f18e793687](https://linux-hardware.org/?probe=f18e793687) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [065ee91163](https://linux-hardware.org/?probe=065ee91163) | Oct 17, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [2cbf85194c](https://linux-hardware.org/?probe=2cbf85194c) | Oct 14, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [cd738f5036](https://linux-hardware.org/?probe=cd738f5036) | Oct 11, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [bc1fd03a63](https://linux-hardware.org/?probe=bc1fd03a63) | Oct 10, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [6ec6ce5c81](https://linux-hardware.org/?probe=6ec6ce5c81) | Oct 10, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [f424437bd1](https://linux-hardware.org/?probe=f424437bd1) | Oct 01, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c85622ebee](https://linux-hardware.org/?probe=c85622ebee) | Sep 29, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [9813ead17b](https://linux-hardware.org/?probe=9813ead17b) | Sep 23, 2021 |
| Medion        | Akoya E7226                 | Desktop     | [9367472acb](https://linux-hardware.org/?probe=9367472acb) | Sep 18, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284c0763b3](https://linux-hardware.org/?probe=284c0763b3) | Sep 09, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [934d0576e0](https://linux-hardware.org/?probe=934d0576e0) | Aug 27, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [b2de2ea1ab](https://linux-hardware.org/?probe=b2de2ea1ab) | Aug 22, 2021 |
| Lenovo        | ThinkPad T460s 20FAS7XT0... | Notebook    | [9da6a33d24](https://linux-hardware.org/?probe=9da6a33d24) | Aug 22, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [8c7e729202](https://linux-hardware.org/?probe=8c7e729202) | Aug 19, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [0fccd48745](https://linux-hardware.org/?probe=0fccd48745) | Aug 13, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [8cc7d05010](https://linux-hardware.org/?probe=8cc7d05010) | Aug 12, 2021 |
| HP            | 2000                        | Notebook    | [2909375db3](https://linux-hardware.org/?probe=2909375db3) | Aug 06, 2021 |
| HP            | 2000                        | Notebook    | [df5d5e05c6](https://linux-hardware.org/?probe=df5d5e05c6) | Aug 06, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| HP            | 2000                        | Notebook    | [9fbfcf95d2](https://linux-hardware.org/?probe=9fbfcf95d2) | Jul 29, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [13aaafccdb](https://linux-hardware.org/?probe=13aaafccdb) | Jul 22, 2021 |
| HP            | 2000                        | Notebook    | [f3c7f85988](https://linux-hardware.org/?probe=f3c7f85988) | Jul 21, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e6e223209a](https://linux-hardware.org/?probe=e6e223209a) | Jul 20, 2021 |
| MSI           | H61M-P31                    | Desktop     | [ccd9d80d59](https://linux-hardware.org/?probe=ccd9d80d59) | Jul 18, 2021 |
| Pegatron      | 2A73                        | Desktop     | [2bff425af7](https://linux-hardware.org/?probe=2bff425af7) | Jul 14, 2021 |
| Pegatron      | 2A73                        | Desktop     | [44ea7169ef](https://linux-hardware.org/?probe=44ea7169ef) | Jul 14, 2021 |
| HP            | 2000                        | Notebook    | [e6019f1bd3](https://linux-hardware.org/?probe=e6019f1bd3) | Jul 12, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bc18a23953](https://linux-hardware.org/?probe=bc18a23953) | Jun 28, 2021 |
| HP            | 2000                        | Notebook    | [6a169f2d87](https://linux-hardware.org/?probe=6a169f2d87) | Jun 22, 2021 |
| HP            | 2000                        | Notebook    | [b2e5075aaf](https://linux-hardware.org/?probe=b2e5075aaf) | Jun 17, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [330d2214c6](https://linux-hardware.org/?probe=330d2214c6) | Jun 10, 2021 |
| HP            | 2000                        | Notebook    | [6a1c91ae8d](https://linux-hardware.org/?probe=6a1c91ae8d) | Jun 07, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [c79b400454](https://linux-hardware.org/?probe=c79b400454) | Jun 06, 2021 |
| Lenovo        | ThinkPad T61 8897CTO        | Notebook    | [6cfc0271ba](https://linux-hardware.org/?probe=6cfc0271ba) | Jun 03, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [02bf919368](https://linux-hardware.org/?probe=02bf919368) | Jun 02, 2021 |
| Acer          | Aspire Z5610                | All in one  | [b24fdb7446](https://linux-hardware.org/?probe=b24fdb7446) | May 28, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [92d97521bc](https://linux-hardware.org/?probe=92d97521bc) | May 21, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [32951a000f](https://linux-hardware.org/?probe=32951a000f) | May 21, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [76598a468f](https://linux-hardware.org/?probe=76598a468f) | May 20, 2021 |
| HP            | 2000                        | Notebook    | [1469c94a5f](https://linux-hardware.org/?probe=1469c94a5f) | May 17, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [a4b9bc232a](https://linux-hardware.org/?probe=a4b9bc232a) | May 15, 2021 |
| HP            | EliteBook 830 G6            | Notebook    | [8fcf99f057](https://linux-hardware.org/?probe=8fcf99f057) | May 12, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [3e6d98fe9c](https://linux-hardware.org/?probe=3e6d98fe9c) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [f67c550f8e](https://linux-hardware.org/?probe=f67c550f8e) | Apr 27, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [0876a200b7](https://linux-hardware.org/?probe=0876a200b7) | Apr 27, 2021 |
| ASRock        | B560 Pro4                   | Desktop     | [ddd384c6cb](https://linux-hardware.org/?probe=ddd384c6cb) | Apr 26, 2021 |
| Lenovo        | ThinkCentre M55e 9389WEG    | Desktop     | [66c2003859](https://linux-hardware.org/?probe=66c2003859) | Apr 20, 2021 |
| HP            | 1905                        | Desktop     | [e0fc243f47](https://linux-hardware.org/?probe=e0fc243f47) | Apr 19, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [c59fd76192](https://linux-hardware.org/?probe=c59fd76192) | Apr 14, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [d0a4124a2a](https://linux-hardware.org/?probe=d0a4124a2a) | Apr 10, 2021 |
| HP            | ProBook 4515s (VC377ES#A... | Notebook    | [2c84f60b0d](https://linux-hardware.org/?probe=2c84f60b0d) | Apr 09, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| HP            | ProBook 4740s               | Notebook    | [cf941af09e](https://linux-hardware.org/?probe=cf941af09e) | Apr 08, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | Desktop     | [325f4ca461](https://linux-hardware.org/?probe=325f4ca461) | Apr 05, 2021 |
| ASUSTek       | P5Q SE                      | Desktop     | [1c3958d998](https://linux-hardware.org/?probe=1c3958d998) | Apr 05, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [1038d58fea](https://linux-hardware.org/?probe=1038d58fea) | Mar 25, 2021 |
| Dell          | Latitude 5501               | Notebook    | [474510883b](https://linux-hardware.org/?probe=474510883b) | Mar 22, 2021 |
| Lenovo        | ThinkStation S20 4157ZSK    | Desktop     | [8b28b318fd](https://linux-hardware.org/?probe=8b28b318fd) | Mar 19, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [453120855b](https://linux-hardware.org/?probe=453120855b) | Mar 18, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [49b951896d](https://linux-hardware.org/?probe=49b951896d) | Mar 17, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [2d9ae8527d](https://linux-hardware.org/?probe=2d9ae8527d) | Mar 11, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [e434a21940](https://linux-hardware.org/?probe=e434a21940) | Mar 04, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [6fdf12c20c](https://linux-hardware.org/?probe=6fdf12c20c) | Feb 28, 2021 |
| Apple         | Mac-F4208DA9 PVT            | Desktop     | [4ab255096c](https://linux-hardware.org/?probe=4ab255096c) | Feb 28, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [9dc547fceb](https://linux-hardware.org/?probe=9dc547fceb) | Feb 26, 2021 |
| Dell          | 0C27VV A02                  | Desktop     | [49cd056ca4](https://linux-hardware.org/?probe=49cd056ca4) | Feb 24, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [8e84f252bc](https://linux-hardware.org/?probe=8e84f252bc) | Feb 20, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [bd76fdbde8](https://linux-hardware.org/?probe=bd76fdbde8) | Feb 20, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [153bb12a6a](https://linux-hardware.org/?probe=153bb12a6a) | Feb 19, 2021 |
| MSI           | H61M-P31                    | Desktop     | [a0192f9d6e](https://linux-hardware.org/?probe=a0192f9d6e) | Feb 17, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [106c66da60](https://linux-hardware.org/?probe=106c66da60) | Feb 14, 2021 |
| Lenovo        | ThinkCentre M90p 5498PK8    | Desktop     | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [45025e2399](https://linux-hardware.org/?probe=45025e2399) | Feb 13, 2021 |
| Lenovo        | ThinkPad L520 785958G       | Notebook    | [be03f382e6](https://linux-hardware.org/?probe=be03f382e6) | Feb 09, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [e40fe3768d](https://linux-hardware.org/?probe=e40fe3768d) | Feb 09, 2021 |
| Panasonic     | CF-53SWWZ5MG                | Notebook    | [d1ade3e39d](https://linux-hardware.org/?probe=d1ade3e39d) | Feb 08, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [a31754db23](https://linux-hardware.org/?probe=a31754db23) | Feb 08, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [95958aa225](https://linux-hardware.org/?probe=95958aa225) | Feb 08, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [0e552a01e6](https://linux-hardware.org/?probe=0e552a01e6) | Feb 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [1f3dc6c825](https://linux-hardware.org/?probe=1f3dc6c825) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [7e828e295f](https://linux-hardware.org/?probe=7e828e295f) | Jan 20, 2021 |
| Pegatron      | 2A73                        | Desktop     | [4c2042c088](https://linux-hardware.org/?probe=4c2042c088) | Jan 18, 2021 |
| Pegatron      | 2A73                        | Desktop     | [c6cf8a7efe](https://linux-hardware.org/?probe=c6cf8a7efe) | Jan 18, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [812e100310](https://linux-hardware.org/?probe=812e100310) | Jan 12, 2021 |
| HP            | ZBook 15u G3                | Notebook    | [30332e1d71](https://linux-hardware.org/?probe=30332e1d71) | Jan 12, 2021 |
| MSI           | H55M-P31                    | Desktop     | [3313a8aba5](https://linux-hardware.org/?probe=3313a8aba5) | Jan 12, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8227f44e5c](https://linux-hardware.org/?probe=8227f44e5c) | Jan 10, 2021 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [60d8b9344b](https://linux-hardware.org/?probe=60d8b9344b) | Jan 09, 2021 |
| HP            | ProBook 4730s               | Notebook    | [e7ab1bcd89](https://linux-hardware.org/?probe=e7ab1bcd89) | Jan 06, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [e9c1683321](https://linux-hardware.org/?probe=e9c1683321) | Jan 04, 2021 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [b6c93666ee](https://linux-hardware.org/?probe=b6c93666ee) | Dec 29, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [7905034ba5](https://linux-hardware.org/?probe=7905034ba5) | Dec 29, 2020 |
| ASUSTek       | UX31E                       | Notebook    | [912f3fe702](https://linux-hardware.org/?probe=912f3fe702) | Dec 25, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [d759211bb6](https://linux-hardware.org/?probe=d759211bb6) | Dec 24, 2020 |
| Lenovo        | ThinkPad T420 4236A78       | Notebook    | [f98c371e7f](https://linux-hardware.org/?probe=f98c371e7f) | Dec 24, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [71370e1dd8](https://linux-hardware.org/?probe=71370e1dd8) | Dec 19, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [6c3965a41f](https://linux-hardware.org/?probe=6c3965a41f) | Dec 18, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [87bd14894c](https://linux-hardware.org/?probe=87bd14894c) | Dec 18, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [b103133d69](https://linux-hardware.org/?probe=b103133d69) | Dec 16, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [def1b6fff4](https://linux-hardware.org/?probe=def1b6fff4) | Dec 13, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [edd5100ec5](https://linux-hardware.org/?probe=edd5100ec5) | Dec 13, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [4260174285](https://linux-hardware.org/?probe=4260174285) | Dec 11, 2020 |
| Lenovo        | ThinkPad T500 2055WYX       | Notebook    | [6f04a45e2e](https://linux-hardware.org/?probe=6f04a45e2e) | Dec 11, 2020 |
| Lenovo        | 3135                        | Mini pc     | [b16b2d9bd5](https://linux-hardware.org/?probe=b16b2d9bd5) | Dec 11, 2020 |
| Lenovo        | ThinkPad T410 2522A92       | Notebook    | [dd93682c3c](https://linux-hardware.org/?probe=dd93682c3c) | Dec 09, 2020 |
| Dell          | Latitude D630               | Notebook    | [92ccc6100c](https://linux-hardware.org/?probe=92ccc6100c) | Dec 05, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [e2ffbd65b4](https://linux-hardware.org/?probe=e2ffbd65b4) | Dec 04, 2020 |
| Pegatron      | EVE                         | Desktop     | [08ced52205](https://linux-hardware.org/?probe=08ced52205) | Nov 29, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [44642a5ed8](https://linux-hardware.org/?probe=44642a5ed8) | Nov 27, 2020 |
| Apple         | Mac-F2218EA9                | All in one  | [201739da91](https://linux-hardware.org/?probe=201739da91) | Nov 25, 2020 |
| Apple         | Mac-F2218EA9                | All in one  | [abd1a36454](https://linux-hardware.org/?probe=abd1a36454) | Nov 23, 2020 |
| Acer          | Aspire A315-42              | Notebook    | [1b5583ba18](https://linux-hardware.org/?probe=1b5583ba18) | Nov 23, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1bc0a5a430](https://linux-hardware.org/?probe=1bc0a5a430) | Nov 23, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc3c7d8910](https://linux-hardware.org/?probe=bc3c7d8910) | Nov 22, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [db1f0e1247](https://linux-hardware.org/?probe=db1f0e1247) | Nov 22, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [5978ba6a13](https://linux-hardware.org/?probe=5978ba6a13) | Nov 22, 2020 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [505fb108f7](https://linux-hardware.org/?probe=505fb108f7) | Nov 21, 2020 |
| HP            | 470 G7 Notebook PC          | Notebook    | [f0d3574818](https://linux-hardware.org/?probe=f0d3574818) | Nov 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8783481f8a](https://linux-hardware.org/?probe=8783481f8a) | Nov 15, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [1298138505](https://linux-hardware.org/?probe=1298138505) | Nov 13, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [c3df499de1](https://linux-hardware.org/?probe=c3df499de1) | Nov 12, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e05c144d2f](https://linux-hardware.org/?probe=e05c144d2f) | Nov 12, 2020 |
| HP            | ProBook 4720s               | Notebook    | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Lenovo        | ThinkCentre M55e 9389WEG    | Desktop     | [2462c80a14](https://linux-hardware.org/?probe=2462c80a14) | Nov 10, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e8f7b6ef7e](https://linux-hardware.org/?probe=e8f7b6ef7e) | Nov 07, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [7e9d52855a](https://linux-hardware.org/?probe=7e9d52855a) | Nov 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3ecd75648c](https://linux-hardware.org/?probe=3ecd75648c) | Nov 06, 2020 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [b9007f3b4f](https://linux-hardware.org/?probe=b9007f3b4f) | Nov 05, 2020 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1e6ba50614](https://linux-hardware.org/?probe=1e6ba50614) | Nov 04, 2020 |
| Intel         | DH87RL AAG74240-403         | Desktop     | [caa0e9c93b](https://linux-hardware.org/?probe=caa0e9c93b) | Nov 02, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b3fe9a6f2](https://linux-hardware.org/?probe=0b3fe9a6f2) | Nov 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [49bc5032be](https://linux-hardware.org/?probe=49bc5032be) | Nov 01, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [9c9e8ac41c](https://linux-hardware.org/?probe=9c9e8ac41c) | Oct 24, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [d336eeaa8d](https://linux-hardware.org/?probe=d336eeaa8d) | Oct 21, 2020 |
| Lenovo        | 3098 NOK                    | Desktop     | [2c592ebb94](https://linux-hardware.org/?probe=2c592ebb94) | Oct 19, 2020 |
| Lenovo        | 3098 NOK                    | Desktop     | [92a22bd753](https://linux-hardware.org/?probe=92a22bd753) | Oct 19, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [2e8b092dbc](https://linux-hardware.org/?probe=2e8b092dbc) | Oct 12, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [3ad72de5c7](https://linux-hardware.org/?probe=3ad72de5c7) | Oct 09, 2020 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [da4740881e](https://linux-hardware.org/?probe=da4740881e) | Oct 04, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2c625d510e](https://linux-hardware.org/?probe=2c625d510e) | Oct 03, 2020 |
| Pegatron      | 2A94h                       | Desktop     | [3a1ede6188](https://linux-hardware.org/?probe=3a1ede6188) | Oct 03, 2020 |
| Unknown       | Unknown                     | Phone       | [f4bd5779b6](https://linux-hardware.org/?probe=f4bd5779b6) | Oct 02, 2020 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [1d3401ff46](https://linux-hardware.org/?probe=1d3401ff46) | Oct 02, 2020 |
| Intel         | NUC7i3BNB J22859-302        | Mini pc     | [afa81d3409](https://linux-hardware.org/?probe=afa81d3409) | Oct 01, 2020 |
| Lenovo        | ThinkPad P53 20QN000DGE     | Notebook    | [3a0bc546cc](https://linux-hardware.org/?probe=3a0bc546cc) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [1a20b51c58](https://linux-hardware.org/?probe=1a20b51c58) | Sep 24, 2020 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | Notebook    | [ca8c660b91](https://linux-hardware.org/?probe=ca8c660b91) | Sep 24, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8bba4f976e](https://linux-hardware.org/?probe=8bba4f976e) | Sep 20, 2020 |
| Intel         | DQ35JO AAD82085-801         | Desktop     | [51c42a0f25](https://linux-hardware.org/?probe=51c42a0f25) | Sep 17, 2020 |
| Dell          | Vostro 3550                 | Notebook    | [ef71fe525d](https://linux-hardware.org/?probe=ef71fe525d) | Sep 17, 2020 |
| Unknown       | Unknown                     | Phone       | [e49d4429f4](https://linux-hardware.org/?probe=e49d4429f4) | Sep 15, 2020 |
| Unknown       | Unknown                     | Phone       | [6354f593f4](https://linux-hardware.org/?probe=6354f593f4) | Sep 15, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [85ab9de98f](https://linux-hardware.org/?probe=85ab9de98f) | Sep 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [94e860aade](https://linux-hardware.org/?probe=94e860aade) | Sep 03, 2020 |
| PC Special... | Fusion IV                   | Notebook    | [55da1618ab](https://linux-hardware.org/?probe=55da1618ab) | Aug 30, 2020 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | Notebook    | [a87567fe16](https://linux-hardware.org/?probe=a87567fe16) | Aug 27, 2020 |
| HP            | ProBook 4540s               | Notebook    | [32346e7861](https://linux-hardware.org/?probe=32346e7861) | Aug 26, 2020 |
| Pegatron      | 2A73                        | Desktop     | [a4607af679](https://linux-hardware.org/?probe=a4607af679) | Aug 25, 2020 |
| Pegatron      | 2A73                        | Desktop     | [f2c225880d](https://linux-hardware.org/?probe=f2c225880d) | Aug 25, 2020 |
| HP            | 3048h                       | Desktop     | [0bc2b9bafc](https://linux-hardware.org/?probe=0bc2b9bafc) | Aug 17, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [438b0df832](https://linux-hardware.org/?probe=438b0df832) | Jul 21, 2020 |
| HP            | 2000                        | Notebook    | [1facf761c9](https://linux-hardware.org/?probe=1facf761c9) | Jul 19, 2020 |
| Lenovo        | ThinkPad T420 423662G       | Notebook    | [f0e52bdb36](https://linux-hardware.org/?probe=f0e52bdb36) | Jul 10, 2020 |
| Lenovo        | ThinkPad E15 20RD0011SC     | Notebook    | [b78049616e](https://linux-hardware.org/?probe=b78049616e) | Jul 09, 2020 |
| Lenovo        | ThinkPad T480 20L6S01W00    | Notebook    | [758a8710d7](https://linux-hardware.org/?probe=758a8710d7) | Jun 29, 2020 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [c323481902](https://linux-hardware.org/?probe=c323481902) | Jun 14, 2020 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [6889f53e3b](https://linux-hardware.org/?probe=6889f53e3b) | Jun 13, 2020 |
| HP            | ProBook 4540s               | Notebook    | [98a9e4902b](https://linux-hardware.org/?probe=98a9e4902b) | Jun 08, 2020 |
| ASRock        | X570 Extreme4               | Desktop     | [add6daf97a](https://linux-hardware.org/?probe=add6daf97a) | Jun 07, 2020 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [d7dee77bfc](https://linux-hardware.org/?probe=d7dee77bfc) | Jun 04, 2020 |
| HP            | ProBook 4540s               | Notebook    | [2b515ca642](https://linux-hardware.org/?probe=2b515ca642) | May 31, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [a8e5567ca8](https://linux-hardware.org/?probe=a8e5567ca8) | May 30, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [03b36ff9c1](https://linux-hardware.org/?probe=03b36ff9c1) | May 28, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [bea6687b8b](https://linux-hardware.org/?probe=bea6687b8b) | May 27, 2020 |
| ASRock        | Z390 Pro4                   | Desktop     | [e1c0c74ca6](https://linux-hardware.org/?probe=e1c0c74ca6) | May 25, 2020 |
| Acer          | Aspire V3-771               | Notebook    | [910279b054](https://linux-hardware.org/?probe=910279b054) | May 25, 2020 |
| Lenovo        | ThinkPad X250 20CM004ESC    | Notebook    | [793c164825](https://linux-hardware.org/?probe=793c164825) | May 25, 2020 |
| MSI           | H61M-P31                    | Desktop     | [870b2534d7](https://linux-hardware.org/?probe=870b2534d7) | May 22, 2020 |
| HP            | ProBook 470 G2              | Notebook    | [d39ca7c5fa](https://linux-hardware.org/?probe=d39ca7c5fa) | May 15, 2020 |
| MSI           | H110M ECO                   | Desktop     | [fe6009a465](https://linux-hardware.org/?probe=fe6009a465) | May 15, 2020 |
| HP            | 15                          | Notebook    | [fa65501be6](https://linux-hardware.org/?probe=fa65501be6) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [91d3944426](https://linux-hardware.org/?probe=91d3944426) | May 10, 2020 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ee92e64256](https://linux-hardware.org/?probe=ee92e64256) | May 07, 2020 |
| HP            | ProBook 4515s (VC377ES#A... | Notebook    | [3ec25a2e7a](https://linux-hardware.org/?probe=3ec25a2e7a) | May 01, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [a1de2f2fe9](https://linux-hardware.org/?probe=a1de2f2fe9) | Apr 18, 2020 |
| Lenovo        | ThinkCentre M55e 9389W11    | Desktop     | [f148017266](https://linux-hardware.org/?probe=f148017266) | Apr 12, 2020 |
| Lenovo        | ThinkPad T590 20N5S0YN00    | Notebook    | [0efab1d69f](https://linux-hardware.org/?probe=0efab1d69f) | Apr 08, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [f9c3afb706](https://linux-hardware.org/?probe=f9c3afb706) | Apr 08, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [17dd7e6ddb](https://linux-hardware.org/?probe=17dd7e6ddb) | Apr 05, 2020 |
| Lenovo        | ThinkCentre M57e 9356W2K    | Desktop     | [663d112138](https://linux-hardware.org/?probe=663d112138) | Apr 02, 2020 |
| ASUSTek       | X750LB                      | Notebook    | [a7c5fb20f8](https://linux-hardware.org/?probe=a7c5fb20f8) | Mar 28, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [ff84ae40b8](https://linux-hardware.org/?probe=ff84ae40b8) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [0877aa97e7](https://linux-hardware.org/?probe=0877aa97e7) | Mar 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5555        | Notebook    | [677f41b346](https://linux-hardware.org/?probe=677f41b346) | Mar 21, 2020 |
| HP            | 0A58h                       | Desktop     | [0734e4224d](https://linux-hardware.org/?probe=0734e4224d) | Mar 16, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | Notebook    | [48cd703e5b](https://linux-hardware.org/?probe=48cd703e5b) | Mar 05, 2020 |
| Lenovo        | ThinkPad P52 20MAS5XN00     | Notebook    | [e6a4ad2c61](https://linux-hardware.org/?probe=e6a4ad2c61) | Mar 04, 2020 |
| HP            | EliteBook 8760w             | Notebook    | [624fd6f7fa](https://linux-hardware.org/?probe=624fd6f7fa) | Mar 01, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [9a43e8f82a](https://linux-hardware.org/?probe=9a43e8f82a) | Feb 26, 2020 |
| ASUSTek       | H110M-A                     | Desktop     | [0722f7ccf8](https://linux-hardware.org/?probe=0722f7ccf8) | Feb 22, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [608fef5510](https://linux-hardware.org/?probe=608fef5510) | Feb 03, 2020 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [44e0ce8fc8](https://linux-hardware.org/?probe=44e0ce8fc8) | Jan 24, 2020 |
| Medion        | MS-7707                     | Desktop     | [3feacd8f08](https://linux-hardware.org/?probe=3feacd8f08) | Jan 19, 2020 |
| Medion        | MS-7707                     | Desktop     | [5d5096c9a8](https://linux-hardware.org/?probe=5d5096c9a8) | Jan 18, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [3f28da0706](https://linux-hardware.org/?probe=3f28da0706) | Jan 17, 2020 |
| HP            | 829B                        | All in one  | [d626be0762](https://linux-hardware.org/?probe=d626be0762) | Jan 09, 2020 |
| Lenovo        | ThinkPad E590 20NB002BSC    | Notebook    | [b20e37d478](https://linux-hardware.org/?probe=b20e37d478) | Jan 06, 2020 |
| Dell          | Latitude 5500               | Notebook    | [84e2b9bc59](https://linux-hardware.org/?probe=84e2b9bc59) | Jan 03, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [0d7f336b82](https://linux-hardware.org/?probe=0d7f336b82) | Jan 03, 2020 |
| Dell          | Latitude 5500               | Notebook    | [0d946e75f9](https://linux-hardware.org/?probe=0d946e75f9) | Jan 03, 2020 |
| Dell          | Latitude 5500               | Notebook    | [be70af9da7](https://linux-hardware.org/?probe=be70af9da7) | Jan 03, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [980b5da590](https://linux-hardware.org/?probe=980b5da590) | Jan 02, 2020 |
| Biostar       | TH55B HD                    | Desktop     | [e13730f188](https://linux-hardware.org/?probe=e13730f188) | Dec 25, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [d853ff31e4](https://linux-hardware.org/?probe=d853ff31e4) | Dec 08, 2019 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [25e0799d44](https://linux-hardware.org/?probe=25e0799d44) | Dec 08, 2019 |
| HP            | 1495                        | Desktop     | [d56240bfb5](https://linux-hardware.org/?probe=d56240bfb5) | Dec 07, 2019 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [de68096cdc](https://linux-hardware.org/?probe=de68096cdc) | Nov 27, 2019 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [7ad66ff018](https://linux-hardware.org/?probe=7ad66ff018) | Nov 23, 2019 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [837d7c2621](https://linux-hardware.org/?probe=837d7c2621) | Nov 23, 2019 |
| HP            | 1495                        | Desktop     | [7517e7c74d](https://linux-hardware.org/?probe=7517e7c74d) | Nov 20, 2019 |
| HP            | 1495                        | Desktop     | [b4598c0e73](https://linux-hardware.org/?probe=b4598c0e73) | Nov 19, 2019 |
| HP            | 1495                        | Desktop     | [ab3f7ddb42](https://linux-hardware.org/?probe=ab3f7ddb42) | Nov 05, 2019 |
| MSI           | GP60 2OD                    | Notebook    | [f450b0d5d4](https://linux-hardware.org/?probe=f450b0d5d4) | Oct 20, 2019 |
| HP            | 1495                        | Desktop     | [75e4e80f87](https://linux-hardware.org/?probe=75e4e80f87) | Oct 04, 2019 |
| HP            | EliteBook 6930p             | Notebook    | [b11cbf51cb](https://linux-hardware.org/?probe=b11cbf51cb) | Sep 28, 2019 |
| HP            | 1495                        | Desktop     | [470c7daaaa](https://linux-hardware.org/?probe=470c7daaaa) | Sep 20, 2019 |
| HP            | 1495                        | Desktop     | [4f34ee60db](https://linux-hardware.org/?probe=4f34ee60db) | Sep 17, 2019 |
| Lenovo        | G585 20137                  | Notebook    | [084d318c5c](https://linux-hardware.org/?probe=084d318c5c) | Sep 16, 2019 |
| Acer          | Aspire E5-573G              | Notebook    | [d2242a3cd4](https://linux-hardware.org/?probe=d2242a3cd4) | Sep 02, 2019 |
| eMachines     | G730                        | Notebook    | [af8b954f82](https://linux-hardware.org/?probe=af8b954f82) | Aug 29, 2019 |
| ASUSTek       | G751JT                      | Notebook    | [a5f96019bd](https://linux-hardware.org/?probe=a5f96019bd) | Aug 04, 2019 |
| Medion        | MS-7707                     | Desktop     | [9b50675efd](https://linux-hardware.org/?probe=9b50675efd) | Aug 03, 2019 |
| eMachines     | G730                        | Notebook    | [5073ea0163](https://linux-hardware.org/?probe=5073ea0163) | Aug 02, 2019 |
| eMachines     | G730                        | Notebook    | [4f0fa60c8d](https://linux-hardware.org/?probe=4f0fa60c8d) | Jul 31, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [4a2455eae6](https://linux-hardware.org/?probe=4a2455eae6) | Jul 28, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8d117b8f35](https://linux-hardware.org/?probe=8d117b8f35) | Jul 28, 2019 |
| HP            | Pavilion 15                 | Notebook    | [edf229fa5e](https://linux-hardware.org/?probe=edf229fa5e) | Jul 22, 2019 |
| Toshiba       | QOSMIO X500                 | Notebook    | [34905cb301](https://linux-hardware.org/?probe=34905cb301) | Jul 15, 2019 |
| ASUSTek       | G751JT                      | Notebook    | [3a17d38bdd](https://linux-hardware.org/?probe=3a17d38bdd) | Jul 09, 2019 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [ab7980dba3](https://linux-hardware.org/?probe=ab7980dba3) | Jul 01, 2019 |
| Lenovo        | ThinkPad T410 2522A92       | Notebook    | [68640c00d9](https://linux-hardware.org/?probe=68640c00d9) | Jun 09, 2019 |
| Medion        | MS-7707                     | Desktop     | [b843e52e30](https://linux-hardware.org/?probe=b843e52e30) | Jun 03, 2019 |
| HP            | Compaq 325                  | Notebook    | [4161a93030](https://linux-hardware.org/?probe=4161a93030) | May 16, 2019 |
| HP            | ProBook 4710s               | Notebook    | [54ed79f58d](https://linux-hardware.org/?probe=54ed79f58d) | May 15, 2019 |
| HP            | Compaq 325                  | Notebook    | [b9dadeece3](https://linux-hardware.org/?probe=b9dadeece3) | May 12, 2019 |
| HP            | Compaq 6720s                | Notebook    | [0e2550055b](https://linux-hardware.org/?probe=0e2550055b) | May 07, 2019 |
| Gigabyte      | P65                         | Notebook    | [6dfb59f508](https://linux-hardware.org/?probe=6dfb59f508) | May 07, 2019 |
| Lenovo        | ThinkCentre M57 6072VAM     | Desktop     | [c399cbb5f3](https://linux-hardware.org/?probe=c399cbb5f3) | May 04, 2019 |
| HP            | ZBook 14 G2                 | Notebook    | [e1463c9ca8](https://linux-hardware.org/?probe=e1463c9ca8) | Apr 23, 2019 |
| Lenovo        | ThinkPad W530 24479K4       | Notebook    | [7d56ca80ca](https://linux-hardware.org/?probe=7d56ca80ca) | Apr 22, 2019 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8ad90844e8](https://linux-hardware.org/?probe=8ad90844e8) | Apr 16, 2019 |
| Medion        | MS-7707                     | Desktop     | [71684dcee4](https://linux-hardware.org/?probe=71684dcee4) | Apr 12, 2019 |
| ASUSTek       | X751NV                      | Notebook    | [a189d47b9a](https://linux-hardware.org/?probe=a189d47b9a) | Apr 09, 2019 |
| HP            | 82C0                        | Mini pc     | [1ecda8c9db](https://linux-hardware.org/?probe=1ecda8c9db) | Apr 06, 2019 |
| HP            | 82C0                        | Mini pc     | [134dd6a268](https://linux-hardware.org/?probe=134dd6a268) | Apr 06, 2019 |
| HP            | 0A68h                       | Desktop     | [fa9c3d044f](https://linux-hardware.org/?probe=fa9c3d044f) | Mar 13, 2019 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [d304d79466](https://linux-hardware.org/?probe=d304d79466) | Mar 10, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [8348d3c21e](https://linux-hardware.org/?probe=8348d3c21e) | Feb 23, 2019 |
| Dell          | Latitude E6500              | Notebook    | [abdbb02998](https://linux-hardware.org/?probe=abdbb02998) | Feb 23, 2019 |
| HP            | 82A2                        | Desktop     | [0f9aa13b55](https://linux-hardware.org/?probe=0f9aa13b55) | Feb 21, 2019 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [0407ee67e9](https://linux-hardware.org/?probe=0407ee67e9) | Feb 11, 2019 |
| Medion        | E7218                       | Notebook    | [5d97b97758](https://linux-hardware.org/?probe=5d97b97758) | Dec 16, 2018 |
| HP            | 0A68h                       | Desktop     | [7b0d921779](https://linux-hardware.org/?probe=7b0d921779) | Dec 15, 2018 |
| HP            | 0A68h                       | Desktop     | [b773c3a27d](https://linux-hardware.org/?probe=b773c3a27d) | Dec 15, 2018 |
| HP            | 0A68h                       | Desktop     | [11bcd6f218](https://linux-hardware.org/?probe=11bcd6f218) | Dec 15, 2018 |
| HP            | Unknown                     | Notebook    | [696e11ac42](https://linux-hardware.org/?probe=696e11ac42) | Nov 29, 2018 |
| HP            | Unknown                     | Notebook    | [121bf767df](https://linux-hardware.org/?probe=121bf767df) | Nov 29, 2018 |
| Lenovo        | ThinkPad Edge 326054G       | Notebook    | [6754682a3b](https://linux-hardware.org/?probe=6754682a3b) | Sep 16, 2017 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [d48dca3ee3](https://linux-hardware.org/?probe=d48dca3ee3) | Feb 18, 2017 |
| Lenovo        | ThinkPad Edge 326054G       | Notebook    | [c208f4b144](https://linux-hardware.org/?probe=c208f4b144) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 58        | 17.42%  |
| Ubuntu 18.04                 | 24        | 7.21%   |
| Ubuntu 22.04                 | 14        | 4.2%    |
| OpenMandriva 4.3             | 11        | 3.3%    |
| KDE neon 20.04               | 10        | 3%      |
| Debian 11                    | 10        | 3%      |
| Zorin 16                     | 9         | 2.7%    |
| Ubuntu 20.10                 | 8         | 2.4%    |
| Xubuntu 20.04                | 7         | 2.1%    |
| Ubuntu 19.10                 | 6         | 1.8%    |
| ArcoLinux Rolling            | 6         | 1.8%    |
| Kubuntu 22.04                | 5         | 1.5%    |
| Kubuntu 20.04                | 5         | 1.5%    |
| Fedora 34                    | 5         | 1.5%    |
| Arch                         | 5         | 1.5%    |
| Zorin 15                     | 4         | 1.2%    |
| Pop!_OS 20.04                | 4         | 1.2%    |
| Manjaro                      | 4         | 1.2%    |
| Linux Mint 19.3              | 4         | 1.2%    |
| Linux Mint 19.1              | 4         | 1.2%    |
| Fedora 33                    | 4         | 1.2%    |
| Ubuntu Unity 16.04           | 3         | 0.9%    |
| Ubuntu 21.10                 | 3         | 0.9%    |
| Pop!_OS 21.10                | 3         | 0.9%    |
| OpenMandriva 4.2             | 3         | 0.9%    |
| Kubuntu 21.10                | 3         | 0.9%    |
| Gentoo 2.6                   | 3         | 0.9%    |
| Fedora 35                    | 3         | 0.9%    |
| EndeavourOS                  | 3         | 0.9%    |
| Debian Testing               | 3         | 0.9%    |
| Ubuntu Budgie 22.04          | 2         | 0.6%    |
| Ubuntu 21.04                 | 2         | 0.6%    |
| Ubuntu 18.10                 | 2         | 0.6%    |
| ROSA R8                      | 2         | 0.6%    |
| Pop!_OS 22.04                | 2         | 0.6%    |
| Pop!_OS 21.04                | 2         | 0.6%    |
| Pop!_OS 20.10                | 2         | 0.6%    |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.6%    |
| OpenMandriva 4.50            | 2         | 0.6%    |
| Manjaro 20.2                 | 2         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 114       | 35.85%  |
| Linux Mint    | 17        | 5.35%   |
| Kubuntu       | 17        | 5.35%   |
| Fedora        | 16        | 5.03%   |
| OpenMandriva  | 15        | 4.72%   |
| Debian        | 15        | 4.72%   |
| Pop!_OS       | 13        | 4.09%   |
| Manjaro       | 13        | 4.09%   |
| Zorin         | 12        | 3.77%   |
| KDE neon      | 11        | 3.46%   |
| Xubuntu       | 10        | 3.14%   |
| Endless       | 10        | 3.14%   |
| ArcoLinux     | 6         | 1.89%   |
| Arch          | 6         | 1.89%   |
| Gentoo        | 5         | 1.57%   |
| EndeavourOS   | 5         | 1.57%   |
| Ubuntu Unity  | 4         | 1.26%   |
| Ubuntu Budgie | 3         | 0.94%   |
| Lubuntu       | 3         | 0.94%   |
| Elementary    | 3         | 0.94%   |
| ROSA          | 2         | 0.63%   |
| openSUSE      | 2         | 0.63%   |
| BlackPanther  | 2         | 0.63%   |
| Android       | 2         | 0.63%   |
| Ubuntu MATE   | 1         | 0.31%   |
| Ubuntu Kylin  | 1         | 0.31%   |
| RHEL          | 1         | 0.31%   |
| Q4OS          | 1         | 0.31%   |
| Mageia        | 1         | 0.31%   |
| LMDE          | 1         | 0.31%   |
| Kali          | 1         | 0.31%   |
| Garuda Linux  | 1         | 0.31%   |
| Clear Linux   | 1         | 0.31%   |
| Chrome OS     | 1         | 0.31%   |
| CentOS        | 1         | 0.31%   |
| Artix         | 1         | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 11        | 3.03%   |
| 5.4.0-48-generic         | 7         | 1.93%   |
| 4.18.0-15-generic        | 6         | 1.65%   |
| 5.4.0-42-generic         | 5         | 1.38%   |
| 5.3.0-40-generic         | 5         | 1.38%   |
| 5.13.0-30-generic        | 5         | 1.38%   |
| 5.8.0-41-generic         | 4         | 1.1%    |
| 5.15.0-56-generic        | 4         | 1.1%    |
| 5.15.0-47-generic        | 4         | 1.1%    |
| 5.15.0-46-generic        | 4         | 1.1%    |
| 5.15.0-25-generic        | 4         | 1.1%    |
| 5.13.0-41-generic        | 4         | 1.1%    |
| 5.13.0-28-generic        | 4         | 1.1%    |
| 5.11.0-43-generic        | 4         | 1.1%    |
| 5.11.0-40-generic        | 4         | 1.1%    |
| 5.8.0-43-generic         | 3         | 0.83%   |
| 5.8.0-36-generic         | 3         | 0.83%   |
| 5.8.0-14-generic         | 3         | 0.83%   |
| 5.4.0-70-generic         | 3         | 0.83%   |
| 5.4.0-60-generic         | 3         | 0.83%   |
| 5.4.0-54-generic         | 3         | 0.83%   |
| 5.4.0-52-generic         | 3         | 0.83%   |
| 5.4.0-31-generic         | 3         | 0.83%   |
| 5.4.0-29-generic         | 3         | 0.83%   |
| 5.4.0-26-generic         | 3         | 0.83%   |
| 5.3.0-26-generic         | 3         | 0.83%   |
| 5.15.0-43-generic        | 3         | 0.83%   |
| 5.13.0-21-generic        | 3         | 0.83%   |
| 5.10.14-desktop-1omv4002 | 3         | 0.83%   |
| 4.18.0-17-generic        | 3         | 0.83%   |
| 5.9.2-arch1-1            | 2         | 0.55%   |
| 5.8.0-7630-generic       | 2         | 0.55%   |
| 5.8.0-53-generic         | 2         | 0.55%   |
| 5.8.0-44-generic         | 2         | 0.55%   |
| 5.6.14-desktop-2bP       | 2         | 0.55%   |
| 5.6.0-1-amd64            | 2         | 0.55%   |
| 5.4.0-90-generic         | 2         | 0.55%   |
| 5.4.0-89-generic         | 2         | 0.55%   |
| 5.4.0-7642-generic       | 2         | 0.55%   |
| 5.4.0-66-generic         | 2         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 67        | 19.48%  |
| 5.8.0   | 28        | 8.14%   |
| 5.15.0  | 28        | 8.14%   |
| 5.13.0  | 26        | 7.56%   |
| 5.11.0  | 20        | 5.81%   |
| 4.15.0  | 17        | 4.94%   |
| 5.3.0   | 16        | 4.65%   |
| 4.18.0  | 16        | 4.65%   |
| 5.16.7  | 12        | 3.49%   |
| 5.10.0  | 10        | 2.91%   |
| 5.0.0   | 6         | 1.74%   |
| 5.10.14 | 5         | 1.45%   |
| 5.6.0   | 4         | 1.16%   |
| 6.0.11  | 2         | 0.58%   |
| 5.9.2   | 2         | 0.58%   |
| 5.9.15  | 2         | 0.58%   |
| 5.6.14  | 2         | 0.58%   |
| 5.17.5  | 2         | 0.58%   |
| 5.16.15 | 2         | 0.58%   |
| 5.15.2  | 2         | 0.58%   |
| 5.14.16 | 2         | 0.58%   |
| 5.14.0  | 2         | 0.58%   |
| 5.13.19 | 2         | 0.58%   |
| 5.12.8  | 2         | 0.58%   |
| 5.12.4  | 2         | 0.58%   |
| 5.10.30 | 2         | 0.58%   |
| 4.18.16 | 2         | 0.58%   |
| 6.0.7   | 1         | 0.29%   |
| 6.0.13  | 1         | 0.29%   |
| 6.0.12  | 1         | 0.29%   |
| 5.9.8   | 1         | 0.29%   |
| 5.9.14  | 1         | 0.29%   |
| 5.8.8   | 1         | 0.29%   |
| 5.8.6   | 1         | 0.29%   |
| 5.8.5   | 1         | 0.29%   |
| 5.8.18  | 1         | 0.29%   |
| 5.8.10  | 1         | 0.29%   |
| 5.7.13  | 1         | 0.29%   |
| 5.7.0   | 1         | 0.29%   |
| 5.5.15  | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 70        | 20.59%  |
| 5.15    | 36        | 10.59%  |
| 5.8     | 33        | 9.71%   |
| 5.13    | 30        | 8.82%   |
| 5.11    | 23        | 6.76%   |
| 5.16    | 19        | 5.59%   |
| 5.10    | 18        | 5.29%   |
| 4.18    | 18        | 5.29%   |
| 5.3     | 17        | 5%      |
| 4.15    | 17        | 5%      |
| 5.12    | 7         | 2.06%   |
| 5.6     | 6         | 1.76%   |
| 5.17    | 6         | 1.76%   |
| 5.14    | 6         | 1.76%   |
| 5.0     | 6         | 1.76%   |
| 6.0     | 5         | 1.47%   |
| 5.9     | 5         | 1.47%   |
| 5.19    | 3         | 0.88%   |
| 5.7     | 2         | 0.59%   |
| 5.5     | 2         | 0.59%   |
| 5.18    | 2         | 0.59%   |
| 4.19    | 2         | 0.59%   |
| 4.1     | 2         | 0.59%   |
| 3.18    | 2         | 0.59%   |
| 4.9     | 1         | 0.29%   |
| 4.20    | 1         | 0.29%   |
| 4.14    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 291       | 95.41%  |
| i686    | 7         | 2.3%    |
| aarch64 | 5         | 1.64%   |
| armv8l  | 2         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 133       | 41.43%  |
| KDE5            | 57        | 17.76%  |
| Unknown         | 47        | 14.64%  |
| XFCE            | 28        | 8.72%   |
| X-Cinnamon      | 12        | 3.74%   |
| KDE             | 9         | 2.8%    |
| Cinnamon        | 6         | 1.87%   |
| LXQt            | 5         | 1.56%   |
| Unity           | 4         | 1.25%   |
| Pantheon        | 3         | 0.93%   |
| MATE            | 3         | 0.93%   |
| Budgie          | 3         | 0.93%   |
| LXDE            | 2         | 0.62%   |
| DWM             | 2         | 0.62%   |
| UKUI            | 1         | 0.31%   |
| Trinity         | 1         | 0.31%   |
| Openbox         | 1         | 0.31%   |
| NsCDE           | 1         | 0.31%   |
| KDE4            | 1         | 0.31%   |
| i3              | 1         | 0.31%   |
| GNOME Flashback | 1         | 0.31%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 241       | 76.27%  |
| Wayland | 34        | 10.76%  |
| Unknown | 32        | 10.13%  |
| Tty     | 9         | 2.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 162       | 50.63%  |
| SDDM    | 52        | 16.25%  |
| GDM     | 36        | 11.25%  |
| LightDM | 30        | 9.38%   |
| GDM3    | 24        | 7.5%    |
| TDM     | 14        | 4.38%   |
| XDM     | 1         | 0.31%   |
| KDM     | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 153       | 49.04%  |
| sl_SI   | 83        | 26.6%   |
| Unknown | 45        | 14.42%  |
| en_GB   | 13        | 4.17%   |
| C       | 6         | 1.92%   |
| en_SI   | 4         | 1.28%   |
| it_IT   | 3         | 0.96%   |
| pt_PT   | 1         | 0.32%   |
| nl_NL   | 1         | 0.32%   |
| hr_HR   | 1         | 0.32%   |
| de_DE   | 1         | 0.32%   |
| de_AT   | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 158       | 50.32%  |
| BIOS | 156       | 49.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 242       | 77.56%  |
| Overlay | 28        | 8.97%   |
| Btrfs   | 17        | 5.45%   |
| Unknown | 16        | 5.13%   |
| Zfs     | 5         | 1.6%    |
| Xfs     | 3         | 0.96%   |
| Ext2    | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 175       | 56.09%  |
| GPT     | 102       | 32.69%  |
| MBR     | 35        | 11.22%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 271       | 86.86%  |
| Yes       | 41        | 13.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 222       | 71.61%  |
| Yes       | 88        | 28.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 68        | 22.3%   |
| ASUSTek Computer        | 58        | 19.02%  |
| Lenovo                  | 55        | 18.03%  |
| Gigabyte Technology     | 22        | 7.21%   |
| Dell                    | 18        | 5.9%    |
| ASRock                  | 15        | 4.92%   |
| MSI                     | 14        | 4.59%   |
| Toshiba                 | 8         | 2.62%   |
| Intel                   | 7         | 2.3%    |
| Acer                    | 6         | 1.97%   |
| Raspberry Pi Foundation | 5         | 1.64%   |
| Pegatron                | 4         | 1.31%   |
| Apple                   | 4         | 1.31%   |
| Medion                  | 3         | 0.98%   |
| Supermicro              | 2         | 0.66%   |
| Fujitsu                 | 2         | 0.66%   |
| Unknown                 | 2         | 0.66%   |
| TUXEDO                  | 1         | 0.33%   |
| Razer                   | 1         | 0.33%   |
| PC Specialist           | 1         | 0.33%   |
| Panasonic               | 1         | 0.33%   |
| Microsoft               | 1         | 0.33%   |
| IBM                     | 1         | 0.33%   |
| HUAWEI                  | 1         | 0.33%   |
| Fujitsu Siemens         | 1         | 0.33%   |
| Framework               | 1         | 0.33%   |
| eMachines               | 1         | 0.33%   |
| Biostar                 | 1         | 0.33%   |
| Acidanthera             | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 4         | 1.31%   |
| MSI MS-7C02                                | 3         | 0.98%   |
| HP 255 G7 Notebook PC                      | 3         | 0.98%   |
| Toshiba Satellite L750                     | 2         | 0.66%   |
| RPi Raspberry Pi 400 Rev 1.0               | 2         | 0.66%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 2         | 0.66%   |
| Pegatron FL308AA-ABD IQ512de               | 2         | 0.66%   |
| MSI MS-7C37                                | 2         | 0.66%   |
| MSI MS-7788                                | 2         | 0.66%   |
| Lenovo ThinkPad T410 2522A92               | 2         | 0.66%   |
| HP Spectre x360 Convertible 13-ae0xx       | 2         | 0.66%   |
| HP EliteBook 8760w                         | 2         | 0.66%   |
| Gigabyte F2A88XM-D3HP                      | 2         | 0.66%   |
| Gigabyte B450M DS3H                        | 2         | 0.66%   |
| Dell Inspiron 5570                         | 2         | 0.66%   |
| Dell Inspiron 1501                         | 2         | 0.66%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 2         | 0.66%   |
| ASUS TUF B450-PLUS GAMING                  | 2         | 0.66%   |
| ASUS ROG STRIX Z370-F GAMING               | 2         | 0.66%   |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.66%   |
| ASUS PRIME B350-PLUS                       | 2         | 0.66%   |
| ASUS PRIME A320M-K                         | 2         | 0.66%   |
| ASUS P7H55-M SI                            | 2         | 0.66%   |
| TUXEDO Aura 15 Gen1                        | 1         | 0.33%   |
| Toshiba TECRA S10                          | 1         | 0.33%   |
| Toshiba TECRA A11                          | 1         | 0.33%   |
| Toshiba Satellite R630                     | 1         | 0.33%   |
| Toshiba Satellite Pro U400                 | 1         | 0.33%   |
| Toshiba Satellite A100                     | 1         | 0.33%   |
| Toshiba QOSMIO X500                        | 1         | 0.33%   |
| Supermicro X7SBi-LN4                       | 1         | 0.33%   |
| Supermicro PCplus T600-C246                | 1         | 0.33%   |
| Razer Blade 14 - RZ09-0370                 | 1         | 0.33%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 (DT)    | 1         | 0.33%   |
| Pegatron Pro 3010 Microtower PC            | 1         | 0.33%   |
| Pegatron 2A73                              | 1         | 0.33%   |
| PC Specialist Fusion IV                    | 1         | 0.33%   |
| Panasonic CF-53SWWZ5MG                     | 1         | 0.33%   |
| MSI U210                                   | 1         | 0.33%   |
| MSI MS-7C91                                | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 32        | 10.49%  |
| ASUS PRIME            | 12        | 3.93%   |
| HP EliteBook          | 11        | 3.61%   |
| HP ProBook            | 10        | 3.28%   |
| Dell Inspiron         | 8         | 2.62%   |
| Lenovo ThinkCentre    | 7         | 2.3%    |
| ASUS ROG              | 7         | 2.3%    |
| HP Compaq             | 6         | 1.97%   |
| ASUS TUF              | 6         | 1.97%   |
| Toshiba Satellite     | 5         | 1.64%   |
| RPi Raspberry         | 5         | 1.64%   |
| Lenovo IdeaPad        | 5         | 1.64%   |
| HP ZBook              | 5         | 1.64%   |
| HP Pavilion           | 4         | 1.31%   |
| HP 255                | 4         | 1.31%   |
| HP 250                | 4         | 1.31%   |
| Dell Latitude         | 4         | 1.31%   |
| ASUS VivoBook         | 4         | 1.31%   |
| Acer Aspire           | 4         | 1.31%   |
| Unknown               | 4         | 1.31%   |
| MSI MS-7C02           | 3         | 0.98%   |
| HP EliteDesk          | 3         | 0.98%   |
| Gigabyte B450M        | 3         | 0.98%   |
| ASUS ASUS             | 3         | 0.98%   |
| Toshiba TECRA         | 2         | 0.66%   |
| Pegatron FL308AA-ABD  | 2         | 0.66%   |
| MSI MS-7C37           | 2         | 0.66%   |
| MSI MS-7788           | 2         | 0.66%   |
| Lenovo Yoga           | 2         | 0.66%   |
| Lenovo ThinkStation   | 2         | 0.66%   |
| HP Spectre            | 2         | 0.66%   |
| HP Laptop             | 2         | 0.66%   |
| Gigabyte F2A88XM-D3HP | 2         | 0.66%   |
| Dell XPS              | 2         | 0.66%   |
| Dell Precision        | 2         | 0.66%   |
| ASUS SABERTOOTH       | 2         | 0.66%   |
| ASUS P7H55-M          | 2         | 0.66%   |
| TUXEDO Aura           | 1         | 0.33%   |
| Toshiba QOSMIO        | 1         | 0.33%   |
| Supermicro X7SBi-LN4  | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 33        | 10.82%  |
| 2020    | 27        | 8.85%   |
| 2018    | 27        | 8.85%   |
| 2017    | 27        | 8.85%   |
| 2011    | 25        | 8.2%    |
| 2009    | 21        | 6.89%   |
| 2013    | 20        | 6.56%   |
| 2015    | 19        | 6.23%   |
| 2010    | 17        | 5.57%   |
| 2014    | 15        | 4.92%   |
| 2012    | 15        | 4.92%   |
| 2008    | 13        | 4.26%   |
| 2021    | 11        | 3.61%   |
| 2016    | 10        | 3.28%   |
| 2007    | 8         | 2.62%   |
| 2006    | 8         | 2.62%   |
| Unknown | 7         | 2.3%    |
| 2022    | 2         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 158       | 51.8%   |
| Desktop        | 120       | 39.34%  |
| All in one     | 6         | 1.97%   |
| System on chip | 5         | 1.64%   |
| Mini pc        | 5         | 1.64%   |
| Tablet         | 3         | 0.98%   |
| Convertible    | 3         | 0.98%   |
| Server         | 3         | 0.98%   |
| Phone          | 2         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 287       | 93.18%  |
| Enabled  | 21        | 6.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 304       | 99.67%  |
| Yes  | 1         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 68        | 22.15%  |
| 16.01-24.0      | 65        | 21.17%  |
| 8.01-16.0       | 64        | 20.85%  |
| 4.01-8.0        | 48        | 15.64%  |
| 32.01-64.0      | 31        | 10.1%   |
| 1.01-2.0        | 10        | 3.26%   |
| 2.01-3.0        | 8         | 2.61%   |
| 64.01-256.0     | 6         | 1.95%   |
| 24.01-32.0      | 5         | 1.63%   |
| More than 256.0 | 1         | 0.33%   |
| 0.51-1.0        | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 116       | 34.12%  |
| 2.01-3.0   | 81        | 23.82%  |
| 4.01-8.0   | 51        | 15%     |
| 3.01-4.0   | 39        | 11.47%  |
| 0.51-1.0   | 23        | 6.76%   |
| 8.01-16.0  | 18        | 5.29%   |
| 0.01-0.5   | 7         | 2.06%   |
| 16.01-24.0 | 4         | 1.18%   |
| 24.01-32.0 | 1         | 0.29%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 186       | 59.62%  |
| 2      | 73        | 23.4%   |
| 3      | 24        | 7.69%   |
| 4      | 10        | 3.21%   |
| 0      | 5         | 1.6%    |
| 6      | 4         | 1.28%   |
| 5      | 4         | 1.28%   |
| 8      | 3         | 0.96%   |
| 7      | 2         | 0.64%   |
| 11     | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 173       | 56.54%  |
| Yes       | 133       | 43.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 273       | 89.22%  |
| No        | 33        | 10.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 67.1%   |
| No        | 101       | 32.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 55.05%  |
| No        | 138       | 44.95%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Slovenia | 305       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Ljubljana               | 114       | 34.65%  |
| Kranj                   | 9         | 2.74%   |
| Celje                   | 9         | 2.74%   |
| Vrhnika                 | 8         | 2.43%   |
| Maribor                 | 8         | 2.43%   |
| Koper                   | 7         | 2.13%   |
| Novo Mesto              | 6         | 1.82%   |
| Trzin                   | 5         | 1.52%   |
| Grosuplje               | 5         | 1.52%   |
| Slovenske Konjice       | 4         | 1.22%   |
| Rence                   | 4         | 1.22%   |
| Portorož               | 4         | 1.22%   |
| Poljane nad Skofjo Loko | 4         | 1.22%   |
| Kamnik                  | 4         | 1.22%   |
| Ajdovščina            | 4         | 1.22%   |
| Žalec                  | 3         | 0.91%   |
| Škofja Loka            | 3         | 0.91%   |
| Radovljica              | 3         | 0.91%   |
| Ptuj                    | 3         | 0.91%   |
| Pragersko               | 3         | 0.91%   |
| Petrovce                | 3         | 0.91%   |
| Nova Gorica             | 3         | 0.91%   |
| Murska Sobota           | 3         | 0.91%   |
| Logatec                 | 3         | 0.91%   |
| Ziri                    | 2         | 0.61%   |
| Zgornja Besnica         | 2         | 0.61%   |
| Velike Lašče          | 2         | 0.61%   |
| Velenje                 | 2         | 0.61%   |
| Smarje pri Jelsah       | 2         | 0.61%   |
| Slovenj Gradec          | 2         | 0.61%   |
| Šentjur pri Celju      | 2         | 0.61%   |
| Sempeter pri Gorici     | 2         | 0.61%   |
| Puconci                 | 2         | 0.61%   |
| Postojna                | 2         | 0.61%   |
| Oplotnica               | 2         | 0.61%   |
| Muta                    | 2         | 0.61%   |
| Loski Potok             | 2         | 0.61%   |
| Ljutomer                | 2         | 0.61%   |
| Izola                   | 2         | 0.61%   |
| Domžale                | 2         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 79        | 136    | 17.95%  |
| Samsung Electronics     | 62        | 101    | 14.09%  |
| Seagate                 | 48        | 74     | 10.91%  |
| Toshiba                 | 36        | 49     | 8.18%   |
| Kingston                | 32        | 43     | 7.27%   |
| Crucial                 | 30        | 42     | 6.82%   |
| SanDisk                 | 20        | 24     | 4.55%   |
| Unknown                 | 17        | 20     | 3.86%   |
| SK hynix                | 13        | 16     | 2.95%   |
| Hitachi                 | 12        | 15     | 2.73%   |
| HGST                    | 11        | 12     | 2.5%    |
| Intel                   | 8         | 9      | 1.82%   |
| Intenso                 | 6         | 8      | 1.36%   |
| Corsair                 | 6         | 8      | 1.36%   |
| OCZ                     | 4         | 7      | 0.91%   |
| Transcend               | 3         | 4      | 0.68%   |
| Silicon Motion          | 3         | 4      | 0.68%   |
| PNY                     | 3         | 3      | 0.68%   |
| Patriot                 | 3         | 5      | 0.68%   |
| KIOXIA                  | 3         | 3      | 0.68%   |
| Fujitsu                 | 3         | 4      | 0.68%   |
| Apacer                  | 3         | 4      | 0.68%   |
| Team                    | 2         | 2      | 0.45%   |
| Micron Technology       | 2         | 2      | 0.45%   |
| LITEONIT                | 2         | 3      | 0.45%   |
| LITEON                  | 2         | 2      | 0.45%   |
| Lenovo                  | 2         | 2      | 0.45%   |
| JMicron Technology      | 2         | 2      | 0.45%   |
| Hewlett-Packard         | 2         | 2      | 0.45%   |
| Gigabyte Technology     | 2         | 4      | 0.45%   |
| China                   | 2         | 2      | 0.45%   |
| Apple                   | 2         | 3      | 0.45%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.23%   |
| TS512GMT                | 1         | 3      | 0.23%   |
| SPCC                    | 1         | 2      | 0.23%   |
| SABRENT                 | 1         | 1      | 0.23%   |
| Realtek                 | 1         | 1      | 0.23%   |
| Phison                  | 1         | 1      | 0.23%   |
| Maxtor                  | 1         | 1      | 0.23%   |
| Leven                   | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 9         | 1.8%    |
| Crucial CT240BX500SSD1 240GB           | 8         | 1.6%    |
| Toshiba DT01ACA100 1TB                 | 6         | 1.2%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 6         | 1.2%    |
| Samsung SSD 850 EVO 250GB              | 5         | 1%      |
| Samsung NVMe SSD Drive 512GB           | 5         | 1%      |
| HGST HTS721010A9E630 1TB               | 5         | 1%      |
| WDC WD10EARS-00Y5B1 1TB                | 4         | 0.8%    |
| Unknown MMC Card  16GB                 | 4         | 0.8%    |
| Toshiba HDWD120 2TB                    | 4         | 0.8%    |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.8%    |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3         | 0.6%    |
| Unknown MMC Card  32GB                 | 3         | 0.6%    |
| Toshiba DT01ACA200 2TB                 | 3         | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 0.6%    |
| SanDisk SSD PLUS 1000GB                | 3         | 0.6%    |
| SanDisk NVMe SSD Drive 512GB           | 3         | 0.6%    |
| SanDisk NVMe SSD Drive 500GB           | 3         | 0.6%    |
| Samsung SSD 980 1TB                    | 3         | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB         | 3         | 0.6%    |
| Samsung SSD 860 EVO 1TB                | 3         | 0.6%    |
| Kingston SUV400S37240G 240GB SSD       | 3         | 0.6%    |
| Hitachi HTS547575A9E384 752GB          | 3         | 0.6%    |
| HGST HTS545050A7E680 500GB             | 3         | 0.6%    |
| Crucial CT500MX500SSD1 500GB           | 3         | 0.6%    |
| Crucial CT1000MX500SSD1 1TB            | 3         | 0.6%    |
| WDC WDS500G3X0C-00SJG0 500GB           | 2         | 0.4%    |
| WDC WDS500G2B0A 500GB SSD              | 2         | 0.4%    |
| WDC WDS480G2G0A-00JH30 480GB SSD       | 2         | 0.4%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 2         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 2         | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB            | 2         | 0.4%    |
| WDC WD5000AADS-00S9B0 500GB            | 2         | 0.4%    |
| WDC WD5000AACS-00G8B1 500GB            | 2         | 0.4%    |
| WDC WD40PURZ-85TTDY0 4TB               | 2         | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB               | 2         | 0.4%    |
| WDC WD40EFRX-68N32N0 4TB               | 2         | 0.4%    |
| WDC WD20PURZ-85GU6Y0 2TB               | 2         | 0.4%    |
| WDC WD15EARS-00MVWB0 1TB               | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 61        | 109    | 35.88%  |
| Seagate             | 46        | 70     | 27.06%  |
| Toshiba             | 27        | 37     | 15.88%  |
| Hitachi             | 12        | 15     | 7.06%   |
| HGST                | 11        | 12     | 6.47%   |
| Fujitsu             | 3         | 4      | 1.76%   |
| Samsung Electronics | 2         | 2      | 1.18%   |
| Unknown             | 1         | 1      | 0.59%   |
| SABRENT             | 1         | 1      | 0.59%   |
| Maxtor              | 1         | 1      | 0.59%   |
| Intenso             | 1         | 1      | 0.59%   |
| IBM-ESXS            | 1         | 1      | 0.59%   |
| HGST HTS            | 1         | 1      | 0.59%   |
| ASMT109x            | 1         | 1      | 0.59%   |
| Apple               | 1         | 2      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 43     | 17.9%   |
| Kingston            | 28        | 35     | 17.28%  |
| Crucial             | 28        | 40     | 17.28%  |
| WDC                 | 17        | 19     | 10.49%  |
| SanDisk             | 12        | 15     | 7.41%   |
| Intel               | 5         | 6      | 3.09%   |
| SK hynix            | 4         | 4      | 2.47%   |
| OCZ                 | 4         | 7      | 2.47%   |
| Corsair             | 4         | 6      | 2.47%   |
| Transcend           | 3         | 4      | 1.85%   |
| PNY                 | 3         | 3      | 1.85%   |
| Patriot             | 3         | 5      | 1.85%   |
| Intenso             | 3         | 3      | 1.85%   |
| Toshiba             | 2         | 2      | 1.23%   |
| LITEONIT            | 2         | 3      | 1.23%   |
| LITEON              | 2         | 2      | 1.23%   |
| China               | 2         | 2      | 1.23%   |
| Apacer              | 2         | 3      | 1.23%   |
| Team                | 1         | 1      | 0.62%   |
| Micron Technology   | 1         | 1      | 0.62%   |
| Leven               | 1         | 1      | 0.62%   |
| KingDian            | 1         | 1      | 0.62%   |
| JMicron Technology  | 1         | 1      | 0.62%   |
| Integral            | 1         | 1      | 0.62%   |
| GOODRAM             | 1         | 1      | 0.62%   |
| Gigabyte Technology | 1         | 2      | 0.62%   |
| A-DATA Technology   | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 146       | 258    | 36.32%  |
| SSD     | 139       | 212    | 34.58%  |
| NVMe    | 96        | 134    | 23.88%  |
| MMC     | 14        | 17     | 3.48%   |
| Unknown | 7         | 12     | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 230       | 458    | 64.25%  |
| NVMe | 96        | 133    | 26.82%  |
| SAS  | 18        | 25     | 5.03%   |
| MMC  | 14        | 17     | 3.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 175       | 273    | 57.95%  |
| 0.51-1.0   | 84        | 134    | 27.81%  |
| 1.01-2.0   | 23        | 30     | 7.62%   |
| 3.01-4.0   | 9         | 17     | 2.98%   |
| 4.01-10.0  | 6         | 10     | 1.99%   |
| 2.01-3.0   | 3         | 4      | 0.99%   |
| 10.01-20.0 | 2         | 2      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 81        | 24.92%  |
| 251-500        | 74        | 22.77%  |
| 501-1000       | 42        | 12.92%  |
| 1001-2000      | 31        | 9.54%   |
| 1-20           | 29        | 8.92%   |
| 51-100         | 18        | 5.54%   |
| 21-50          | 15        | 4.62%   |
| 2001-3000      | 14        | 4.31%   |
| Unknown        | 11        | 3.38%   |
| More than 3000 | 10        | 3.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 133       | 40.43%  |
| 21-50          | 45        | 13.68%  |
| 51-100         | 44        | 13.37%  |
| 101-250        | 41        | 12.46%  |
| 251-500        | 22        | 6.69%   |
| 501-1000       | 13        | 3.95%   |
| 1001-2000      | 12        | 3.65%   |
| Unknown        | 11        | 3.34%   |
| 2001-3000      | 6         | 1.82%   |
| More than 3000 | 2         | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB               | 2         | 2      | 5.71%   |
| WDC WDS480G2G0A-00JH30 480GB SSD         | 1         | 1      | 2.86%   |
| WDC WD5000AADS-00S9B0 500GB              | 1         | 1      | 2.86%   |
| WDC WD40EFRX-68N32N0 4TB                 | 1         | 1      | 2.86%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 2.86%   |
| WDC WD20EFRX-68EUZN0 2TB                 | 1         | 1      | 2.86%   |
| Toshiba Q300. 240GB SSD                  | 1         | 1      | 2.86%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 5      | 2.86%   |
| Toshiba DT01ACA300 3TB                   | 1         | 1      | 2.86%   |
| SK hynix HFS256G32MND-2200A 256GB SSD    | 1         | 1      | 2.86%   |
| Seagate ST9750420AS 752GB                | 1         | 1      | 2.86%   |
| Seagate ST9500423AS 500GB                | 1         | 1      | 2.86%   |
| Seagate ST9500325AS 500GB                | 1         | 2      | 2.86%   |
| Seagate ST3500514NS 500GB                | 1         | 1      | 2.86%   |
| Seagate ST3500320NS 500GB                | 1         | 1      | 2.86%   |
| Seagate ST3320620AS 320GB                | 1         | 1      | 2.86%   |
| Seagate ST3200822AS 200GB                | 1         | 1      | 2.86%   |
| Seagate ST2000DM001-1CH164 2TB           | 1         | 1      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 2.86%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 1      | 2.86%   |
| SanDisk SSD PLUS 240GB                   | 1         | 1      | 2.86%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 1      | 2.86%   |
| SanDisk SD7SB2Q512G1001 512GB SSD        | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 970 EVO 1TB      | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 2.86%   |
| OCZ VERTEX3 120GB SSD                    | 1         | 1      | 2.86%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 1      | 2.86%   |
| Kingston SA400S37240G 240GB SSD          | 1         | 1      | 2.86%   |
| Intel SSDSA2M160G2GC 160GB               | 1         | 1      | 2.86%   |
| Hitachi HTS727550A9E364 500GB            | 1         | 1      | 2.86%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 2.86%   |
| Hewlett-Packard SSD EX900 500GB          | 1         | 1      | 2.86%   |
| Crucial M4-CT128M4SSD2 128GB             | 1         | 1      | 2.86%   |
| Crucial CT120M500SSD1 120GB              | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 11     | 25%     |
| WDC                 | 4         | 5      | 12.5%   |
| Toshiba             | 3         | 7      | 9.38%   |
| SanDisk             | 3         | 3      | 9.38%   |
| HGST                | 3         | 3      | 9.38%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| Kingston            | 2         | 2      | 6.25%   |
| Crucial             | 2         | 2      | 6.25%   |
| SK hynix            | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Hitachi             | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 11     | 47.06%  |
| WDC     | 3         | 4      | 17.65%  |
| HGST    | 3         | 3      | 17.65%  |
| Toshiba | 2         | 6      | 11.76%  |
| Hitachi | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 25     | 51.72%  |
| SSD  | 12        | 13     | 41.38%  |
| NVMe | 2         | 2      | 6.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                   | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba MK6465GSX 640GB | 1         | 2      | 50%     |
| SPCC M.2 PCIe SSD 2TB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 2      | 50%     |
| SPCC    | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 187       | 342    | 56.16%  |
| Works    | 115       | 248    | 34.53%  |
| Malfunc  | 29        | 40     | 8.71%   |
| Failed   | 2         | 3      | 0.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 207       | 53.08%  |
| AMD                              | 58        | 14.87%  |
| Samsung Electronics              | 41        | 10.51%  |
| SanDisk                          | 16        | 4.1%    |
| SK hynix                         | 9         | 2.31%   |
| Toshiba America Info Systems     | 8         | 2.05%   |
| Silicon Motion                   | 6         | 1.54%   |
| Kingston Technology Company      | 6         | 1.54%   |
| Phison Electronics               | 5         | 1.28%   |
| Marvell Technology Group         | 5         | 1.28%   |
| JMicron Technology               | 5         | 1.28%   |
| ASMedia Technology               | 5         | 1.28%   |
| KIOXIA                           | 3         | 0.77%   |
| Micron/Crucial Technology        | 2         | 0.51%   |
| Lenovo                           | 2         | 0.51%   |
| Union Memory (Shenzhen)          | 1         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Silicon Image                    | 1         | 0.26%   |
| Shenzhen Longsys Electronics     | 1         | 0.26%   |
| Seagate Technology               | 1         | 0.26%   |
| OCZ Technology Group             | 1         | 0.26%   |
| Nvidia                           | 1         | 0.26%   |
| Micron Technology                | 1         | 0.26%   |
| LSI Logic / Symbios Logic        | 1         | 0.26%   |
| Integrated Technology Express    | 1         | 0.26%   |
| Hewlett-Packard                  | 1         | 0.26%   |
| Broadcom / LSI                   | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 40        | 8.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 24        | 5.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 14        | 3.07%   |
| AMD 400 Series Chipset SATA Controller                                                  | 12        | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 2.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 2.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 10        | 2.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 9         | 1.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 1.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 7         | 1.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 7         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 1.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5         | 1.1%    |
| Samsung NVMe SSD Controller 980                                                         | 5         | 1.1%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 5         | 1.1%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 5         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5         | 1.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 1.1%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 4         | 0.88%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4         | 0.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 0.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 0.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 0.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 4         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 214       | 55.15%  |
| NVMe | 100       | 25.77%  |
| IDE  | 53        | 13.66%  |
| RAID | 18        | 4.64%   |
| SAS  | 2         | 0.52%   |
| SCSI | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 233       | 76.39%  |
| AMD    | 65        | 21.31%  |
| ARM    | 7         | 2.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.64%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.64%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 1.64%   |
| ARM Processor                                 | 5         | 1.64%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 4         | 1.31%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.98%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 3         | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.98%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 0.98%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.98%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 0.98%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 0.98%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.98%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.66%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.66%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.66%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.66%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 2         | 0.66%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 2         | 0.66%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.66%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.66%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 2         | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.66%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.66%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.66%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 0.66%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.66%   |
| Intel Core i5-3550 CPU @ 3.30GHz              | 2         | 0.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.66%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.66%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.66%   |
| Intel Core i5 CPU 760 @ 2.80GHz               | 2         | 0.66%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 2         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 72        | 23.61%  |
| Intel Core i7           | 60        | 19.67%  |
| Intel Core 2 Duo        | 26        | 8.52%   |
| Intel Core i3           | 22        | 7.21%   |
| AMD Ryzen 5             | 20        | 6.56%   |
| Other                   | 14        | 4.59%   |
| Intel Xeon              | 11        | 3.61%   |
| Intel Celeron           | 11        | 3.61%   |
| AMD Ryzen 7             | 11        | 3.61%   |
| AMD Ryzen 9             | 9         | 2.95%   |
| Intel Pentium           | 8         | 2.62%   |
| AMD Ryzen 3             | 7         | 2.3%    |
| Intel Core 2            | 4         | 1.31%   |
| Intel Core 2 Quad       | 3         | 0.98%   |
| Intel Atom              | 3         | 0.98%   |
| AMD FX                  | 2         | 0.66%   |
| Intel Pentium Silver    | 1         | 0.33%   |
| Intel Pentium Dual      | 1         | 0.33%   |
| Intel Pentium D         | 1         | 0.33%   |
| Intel Genuine           | 1         | 0.33%   |
| Intel Core i9           | 1         | 0.33%   |
| ARM AArch64             | 1         | 0.33%   |
| AMD Turion II Dual-Core | 1         | 0.33%   |
| AMD Turion II           | 1         | 0.33%   |
| AMD Ryzen 3 PRO         | 1         | 0.33%   |
| AMD Phenom II X6        | 1         | 0.33%   |
| AMD Phenom II X4        | 1         | 0.33%   |
| AMD Mobile Sempron      | 1         | 0.33%   |
| AMD E1                  | 1         | 0.33%   |
| AMD E                   | 1         | 0.33%   |
| AMD C-60                | 1         | 0.33%   |
| AMD Athlon X4           | 1         | 0.33%   |
| AMD Athlon Neo          | 1         | 0.33%   |
| AMD Athlon II X2        | 1         | 0.33%   |
| AMD Athlon 64 X2        | 1         | 0.33%   |
| AMD A8                  | 1         | 0.33%   |
| AMD A6                  | 1         | 0.33%   |
| AMD A10                 | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 123       | 40.33%  |
| 2      | 116       | 38.03%  |
| 6      | 35        | 11.48%  |
| 8      | 19        | 6.23%   |
| 12     | 7         | 2.3%    |
| 1      | 4         | 1.31%   |
| 16     | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 300       | 98.36%  |
| 2      | 5         | 1.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 187       | 61.31%  |
| 1      | 118       | 38.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 291       | 94.79%  |
| Unknown        | 14        | 4.56%   |
| 32-bit         | 2         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 19.81%  |
| 0x206a7    | 17        | 5.35%   |
| 0x306a9    | 16        | 5.03%   |
| 0x306c3    | 13        | 4.09%   |
| 0x906ea    | 11        | 3.46%   |
| 0x906e9    | 11        | 3.46%   |
| 0x806ec    | 10        | 3.14%   |
| 0x40651    | 9         | 2.83%   |
| 0x1067a    | 9         | 2.83%   |
| 0x806ea    | 8         | 2.52%   |
| 0x506e3    | 8         | 2.52%   |
| 0x30678    | 8         | 2.52%   |
| 0x20655    | 8         | 2.52%   |
| 0x10676    | 8         | 2.52%   |
| 0x6fd      | 7         | 2.2%    |
| 0x106e5    | 7         | 2.2%    |
| 0x806c1    | 6         | 1.89%   |
| 0x906ed    | 5         | 1.57%   |
| 0x08108102 | 5         | 1.57%   |
| 0x6fb      | 4         | 1.26%   |
| 0x306d4    | 4         | 1.26%   |
| 0x20652    | 4         | 1.26%   |
| 0x0a201016 | 4         | 1.26%   |
| 0x0800820d | 4         | 1.26%   |
| 0x406e3    | 3         | 0.94%   |
| 0x0a201009 | 3         | 0.94%   |
| 0x08600106 | 3         | 0.94%   |
| 0x08108109 | 3         | 0.94%   |
| 0x0810100b | 3         | 0.94%   |
| 0x08001138 | 3         | 0.94%   |
| 0xa0671    | 2         | 0.63%   |
| 0x906eb    | 2         | 0.63%   |
| 0x706e5    | 2         | 0.63%   |
| 0x706a1    | 2         | 0.63%   |
| 0x506c9    | 2         | 0.63%   |
| 0x206d7    | 2         | 0.63%   |
| 0x08701021 | 2         | 0.63%   |
| 0x08001137 | 2         | 0.63%   |
| 0x06001119 | 2         | 0.63%   |
| 0x05000119 | 2         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 57        | 18.69%  |
| Haswell       | 26        | 8.52%   |
| SandyBridge   | 22        | 7.21%   |
| Penryn        | 19        | 6.23%   |
| IvyBridge     | 19        | 6.23%   |
| Core          | 17        | 5.57%   |
| Zen+          | 13        | 4.26%   |
| Westmere      | 13        | 4.26%   |
| Skylake       | 13        | 4.26%   |
| Unknown       | 13        | 4.26%   |
| Zen 3         | 12        | 3.93%   |
| Zen 2         | 9         | 2.95%   |
| Zen           | 9         | 2.95%   |
| Silvermont    | 9         | 2.95%   |
| Nehalem       | 8         | 2.62%   |
| Broadwell     | 8         | 2.62%   |
| TigerLake     | 6         | 1.97%   |
| K10           | 5         | 1.64%   |
| Piledriver    | 4         | 1.31%   |
| IceLake       | 4         | 1.31%   |
| K8 Hammer     | 3         | 0.98%   |
| Goldmont plus | 3         | 0.98%   |
| CometLake     | 3         | 0.98%   |
| Goldmont      | 2         | 0.66%   |
| Bobcat        | 2         | 0.66%   |
| Steamroller   | 1         | 0.33%   |
| P6            | 1         | 0.33%   |
| NetBurst      | 1         | 0.33%   |
| Jaguar        | 1         | 0.33%   |
| Excavator     | 1         | 0.33%   |
| Bonnell       | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 160       | 44.69%  |
| Nvidia                           | 102       | 28.49%  |
| AMD                              | 93        | 25.98%  |
| Matrox Electronics Systems       | 2         | 0.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 14        | 3.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 11        | 3.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 9         | 2.46%   |
| Intel UHD Graphics 620                                                                | 9         | 2.46%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 9         | 2.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 8         | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 8         | 2.19%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 8         | 2.19%   |
| Intel HD Graphics 630                                                                 | 7         | 1.91%   |
| Intel Core Processor Integrated Graphics Controller                                   | 7         | 1.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 1.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 6         | 1.64%   |
| AMD Renoir                                                                            | 6         | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 5         | 1.37%   |
| Intel HD Graphics 5500                                                                | 5         | 1.37%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 5         | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 5         | 1.37%   |
| Nvidia GP108M [GeForce MX250]                                                         | 4         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 4         | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 4         | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.09%   |
| AMD Lucienne                                                                          | 4         | 1.09%   |
| AMD Juniper XT [Radeon HD 5770]                                                       | 4         | 1.09%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                    | 4         | 1.09%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 3         | 0.82%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 3         | 0.82%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 3         | 0.82%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 3         | 0.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 3         | 0.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 3         | 0.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 3         | 0.82%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.55%   |
| Nvidia GP107M [GeForce MX350]                                                         | 2         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 0.55%   |
| Nvidia GP107 [GeForce GTX 1050]                                                       | 2         | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 0.55%   |
| Nvidia GM204 [GeForce GTX 970]                                                        | 2         | 0.55%   |
| Nvidia GM108M [GeForce 940M]                                                          | 2         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 36.16%  |
| 1 x AMD        | 67        | 21.82%  |
| 1 x Nvidia     | 62        | 20.2%   |
| Intel + Nvidia | 31        | 10.1%   |
| Intel + AMD    | 14        | 4.56%   |
| AMD + Nvidia   | 9         | 2.93%   |
| Other          | 7         | 2.28%   |
| 2 x AMD        | 3         | 0.98%   |
| 1 x Matrox     | 2         | 0.65%   |
| 1 x SiS        | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 236       | 76.38%  |
| Proprietary | 54        | 17.48%  |
| Unknown     | 19        | 6.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 170       | 53.8%   |
| 1.01-2.0   | 49        | 15.51%  |
| 0.01-0.5   | 28        | 8.86%   |
| 0.51-1.0   | 23        | 7.28%   |
| 3.01-4.0   | 16        | 5.06%   |
| 7.01-8.0   | 14        | 4.43%   |
| 5.01-6.0   | 8         | 2.53%   |
| 8.01-16.0  | 4         | 1.27%   |
| 2.01-3.0   | 3         | 0.95%   |
| 4.01-5.0   | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 49        | 14.41%  |
| AU Optronics            | 46        | 13.53%  |
| Dell                    | 36        | 10.59%  |
| LG Display              | 24        | 7.06%   |
| AOC                     | 24        | 7.06%   |
| Chimei Innolux          | 20        | 5.88%   |
| Goldstar                | 18        | 5.29%   |
| BOE                     | 17        | 5%      |
| Philips                 | 15        | 4.41%   |
| Lenovo                  | 14        | 4.12%   |
| Hewlett-Packard         | 10        | 2.94%   |
| Chi Mei Optoelectronics | 7         | 2.06%   |
| Acer                    | 5         | 1.47%   |
| Sony                    | 4         | 1.18%   |
| Ancor Communications    | 4         | 1.18%   |
| ViewSonic               | 3         | 0.88%   |
| Unknown                 | 3         | 0.88%   |
| Sharp                   | 3         | 0.88%   |
| LG Philips              | 3         | 0.88%   |
| Iiyama                  | 3         | 0.88%   |
| HannStar                | 3         | 0.88%   |
| Apple                   | 3         | 0.88%   |
| TMX                     | 2         | 0.59%   |
| PANDA                   | 2         | 0.59%   |
| CSO                     | 2         | 0.59%   |
| BenQ                    | 2         | 0.59%   |
| ASUSTek Computer        | 2         | 0.59%   |
| Vestel Elektronik       | 1         | 0.29%   |
| Unknown (XXX)           | 1         | 0.29%   |
| RS                      | 1         | 0.29%   |
| NEC Computers           | 1         | 0.29%   |
| Medion                  | 1         | 0.29%   |
| LGD                     | 1         | 0.29%   |
| InfoVision              | 1         | 0.29%   |
| IBM                     | 1         | 0.29%   |
| Grundig                 | 1         | 0.29%   |
| Gericom                 | 1         | 0.29%   |
| FUN                     | 1         | 0.29%   |
| Eizo                    | 1         | 0.29%   |
| DIF                     | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 7         | 1.96%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 4         | 1.12%   |
| Philips LCD Monitor FTV 1920x1080                                         | 3         | 0.84%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                        | 3         | 0.84%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 0.84%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                  | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 3         | 0.84%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                       | 3         | 0.84%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 2         | 0.56%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch      | 2         | 0.56%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch      | 2         | 0.56%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch      | 2         | 0.56%   |
| Samsung Electronics SyncMaster SAM026F 1280x1024 376x301mm 19.0-inch      | 2         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 2         | 0.56%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                       | 2         | 0.56%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch               | 2         | 0.56%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch              | 2         | 0.56%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch                  | 2         | 0.56%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                   | 2         | 0.56%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                   | 2         | 0.56%   |
| Goldstar ULTRAWIDE GSM5AE2 1920x1080 800x335mm 34.1-inch                  | 2         | 0.56%   |
| Dell U2515H DELD06E 2560x1440 553x311mm 25.0-inch                         | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1376 1920x1080 293x165mm 13.2-inch          | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 2         | 0.56%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                     | 2         | 0.56%   |
| BOE LCD Monitor BOE0869 1920x1080 344x194mm 15.5-inch                     | 2         | 0.56%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 0.56%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO479D 1920x1080 382x215mm 17.3-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO129E 1600x900 382x214mm 17.2-inch             | 2         | 0.56%   |
| AOC LCD Monitor AG251FWG2 1920x1080                                       | 2         | 0.56%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                           | 2         | 0.56%   |
| ViewSonic VX3211-4K VSCC336 3840x2160 698x393mm 31.5-inch                 | 1         | 0.28%   |
| ViewSonic VG2448 VSC3B35 1920x1080 527x296mm 23.8-inch                    | 1         | 0.28%   |
| ViewSonic VA2406-FHD VSC3B66 1920x1080 527x296mm 23.8-inch                | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 139       | 42.9%   |
| 1366x768 (WXGA)    | 36        | 11.11%  |
| 3840x2160 (4K)     | 23        | 7.1%    |
| 2560x1440 (QHD)    | 20        | 6.17%   |
| 1600x900 (HD+)     | 20        | 6.17%   |
| 1680x1050 (WSXGA+) | 15        | 4.63%   |
| 1920x1200 (WUXGA)  | 14        | 4.32%   |
| 1280x1024 (SXGA)   | 13        | 4.01%   |
| 3440x1440          | 9         | 2.78%   |
| 1440x900 (WXGA+)   | 6         | 1.85%   |
| 1280x800 (WXGA)    | 6         | 1.85%   |
| 2560x1080          | 4         | 1.23%   |
| 2560x1600          | 3         | 0.93%   |
| 2288x1287          | 2         | 0.62%   |
| Unknown            | 2         | 0.62%   |
| 3840x1600          | 1         | 0.31%   |
| 3840x1200          | 1         | 0.31%   |
| 3840x1080          | 1         | 0.31%   |
| 2736x1824          | 1         | 0.31%   |
| 2560x1024          | 1         | 0.31%   |
| 2520x1680          | 1         | 0.31%   |
| 2256x1504          | 1         | 0.31%   |
| 2048x1152          | 1         | 0.31%   |
| 1400x1050          | 1         | 0.31%   |
| 1280x960           | 1         | 0.31%   |
| 1280x720 (HD)      | 1         | 0.31%   |
| 1024x768 (XGA)     | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 81        | 23.62%  |
| 24      | 32        | 9.33%   |
| 17      | 29        | 8.45%   |
| 23      | 26        | 7.58%   |
| 27      | 23        | 6.71%   |
| 21      | 21        | 6.12%   |
| 13      | 17        | 4.96%   |
| 14      | 16        | 4.66%   |
| Unknown | 16        | 4.66%   |
| 34      | 13        | 3.79%   |
| 22      | 9         | 2.62%   |
| 19      | 8         | 2.33%   |
| 31      | 7         | 2.04%   |
| 18      | 6         | 1.75%   |
| 20      | 5         | 1.46%   |
| 12      | 5         | 1.46%   |
| 65      | 4         | 1.17%   |
| 54      | 3         | 0.87%   |
| 33      | 3         | 0.87%   |
| 142     | 2         | 0.58%   |
| 84      | 2         | 0.58%   |
| 72      | 2         | 0.58%   |
| 32      | 2         | 0.58%   |
| 25      | 2         | 0.58%   |
| 55      | 1         | 0.29%   |
| 49      | 1         | 0.29%   |
| 39      | 1         | 0.29%   |
| 37      | 1         | 0.29%   |
| 29      | 1         | 0.29%   |
| 28      | 1         | 0.29%   |
| 16      | 1         | 0.29%   |
| 11      | 1         | 0.29%   |
| 10      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 105       | 31.25%  |
| 501-600        | 74        | 22.02%  |
| 401-500        | 38        | 11.31%  |
| 351-400        | 37        | 11.01%  |
| 201-300        | 19        | 5.65%   |
| 701-800        | 18        | 5.36%   |
| Unknown        | 16        | 4.76%   |
| 601-700        | 12        | 3.57%   |
| 1001-1500      | 9         | 2.68%   |
| 1501-2000      | 4         | 1.19%   |
| More than 2000 | 2         | 0.6%    |
| 801-900        | 2         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 220       | 70.97%  |
| 16/10   | 40        | 12.9%   |
| 21/9    | 14        | 4.52%   |
| 5/4     | 13        | 4.19%   |
| Unknown | 13        | 4.19%   |
| 3/2     | 4         | 1.29%   |
| 4/3     | 3         | 0.97%   |
| 1.00    | 2         | 0.65%   |
| 32/9    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 23.53%  |
| 201-250        | 66        | 19.41%  |
| 351-500        | 27        | 7.94%   |
| 121-130        | 24        | 7.06%   |
| 301-350        | 23        | 6.76%   |
| 81-90          | 22        | 6.47%   |
| 151-200        | 22        | 6.47%   |
| Unknown        | 16        | 4.71%   |
| 251-300        | 15        | 4.41%   |
| More than 1000 | 14        | 4.12%   |
| 71-80          | 10        | 2.94%   |
| 141-150        | 6         | 1.76%   |
| 61-70          | 5         | 1.47%   |
| 501-1000       | 3         | 0.88%   |
| 131-140        | 2         | 0.59%   |
| 91-100         | 2         | 0.59%   |
| 51-60          | 1         | 0.29%   |
| 41-50          | 1         | 0.29%   |
| 111-120        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 112       | 34.36%  |
| 121-160       | 84        | 25.77%  |
| 101-120       | 79        | 24.23%  |
| 161-240       | 17        | 5.21%   |
| Unknown       | 16        | 4.91%   |
| 1-50          | 13        | 3.99%   |
| More than 240 | 5         | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 243       | 77.14%  |
| 2     | 56        | 17.78%  |
| 0     | 12        | 3.81%   |
| 3     | 3         | 0.95%   |
| 6     | 1         | 0.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 151       | 34.95%  |
| Intel                             | 151       | 34.95%  |
| Qualcomm Atheros                  | 41        | 9.49%   |
| Broadcom                          | 29        | 6.71%   |
| Ralink                            | 8         | 1.85%   |
| Ralink Technology                 | 6         | 1.39%   |
| Marvell Technology Group          | 5         | 1.16%   |
| ASUSTek Computer                  | 5         | 1.16%   |
| Samsung Electronics               | 3         | 0.69%   |
| Huawei Technologies               | 3         | 0.69%   |
| Hewlett-Packard                   | 3         | 0.69%   |
| Ericsson Business Mobile Networks | 3         | 0.69%   |
| Sierra Wireless                   | 2         | 0.46%   |
| MediaTek                          | 2         | 0.46%   |
| Linksys                           | 2         | 0.46%   |
| Broadcom Limited                  | 2         | 0.46%   |
| ZyDAS Technology                  | 1         | 0.23%   |
| VIA Technologies                  | 1         | 0.23%   |
| TP-Link                           | 1         | 0.23%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.23%   |
| Qualcomm Atheros Communications   | 1         | 0.23%   |
| Nvidia                            | 1         | 0.23%   |
| Microsoft                         | 1         | 0.23%   |
| Lenovo                            | 1         | 0.23%   |
| JMicron Technology                | 1         | 0.23%   |
| IMC Networks                      | 1         | 0.23%   |
| IBM                               | 1         | 0.23%   |
| D-Link System                     | 1         | 0.23%   |
| D-Link                            | 1         | 0.23%   |
| Compal Electronics                | 1         | 0.23%   |
| Belkin Components                 | 1         | 0.23%   |
| ASIX Electronics                  | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 21.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 3.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.71%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.52%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 1.94%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.74%   |
| Intel I211 Gigabit Network Connection                             | 9         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.55%   |
| Intel Wireless 7260                                               | 8         | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.16%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.97%   |
| Intel Wireless 7265                                               | 5         | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 3         | 0.58%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 0.58%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.58%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.58%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 45.37%  |
| Qualcomm Atheros                | 33        | 15.28%  |
| Realtek Semiconductor           | 29        | 13.43%  |
| Broadcom                        | 20        | 9.26%   |
| Ralink                          | 8         | 3.7%    |
| Ralink Technology               | 6         | 2.78%   |
| ASUSTek Computer                | 5         | 2.31%   |
| Sierra Wireless                 | 2         | 0.93%   |
| MediaTek                        | 2         | 0.93%   |
| Hewlett-Packard                 | 2         | 0.93%   |
| Broadcom Limited                | 2         | 0.93%   |
| ZyDAS Technology                | 1         | 0.46%   |
| TP-Link                         | 1         | 0.46%   |
| Qualcomm Atheros Communications | 1         | 0.46%   |
| Marvell Technology Group        | 1         | 0.46%   |
| Linksys                         | 1         | 0.46%   |
| IMC Networks                    | 1         | 0.46%   |
| D-Link System                   | 1         | 0.46%   |
| D-Link                          | 1         | 0.46%   |
| Belkin Components               | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 5.99%   |
| Intel Wireless 8265 / 8275                                              | 9         | 4.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.69%   |
| Intel Wireless 7260                                                     | 8         | 3.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.3%    |
| Intel Wireless 7265                                                     | 5         | 2.3%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.84%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 1.38%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.38%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.38%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.38%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.38%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.92%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 2         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.92%   |
| Intel Wireless 8260                                                     | 2         | 0.92%   |
| Intel Wireless 3165                                                     | 2         | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.92%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.92%   |
| HP lt4112 Gobi 4G Module Network Device                                 | 2         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 141       | 48.45%  |
| Intel                            | 103       | 35.4%   |
| Broadcom                         | 14        | 4.81%   |
| Qualcomm Atheros                 | 13        | 4.47%   |
| Marvell Technology Group         | 4         | 1.37%   |
| Samsung Electronics              | 3         | 1.03%   |
| Huawei Technologies              | 3         | 1.03%   |
| VIA Technologies                 | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Nvidia                           | 1         | 0.34%   |
| Microsoft                        | 1         | 0.34%   |
| Linksys                          | 1         | 0.34%   |
| Lenovo                           | 1         | 0.34%   |
| JMicron Technology               | 1         | 0.34%   |
| IBM                              | 1         | 0.34%   |
| Compal Electronics               | 1         | 0.34%   |
| ASIX Electronics                 | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 37.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 5.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 4.75%   |
| Intel Ethernet Connection (2) I219-V                              | 10        | 3.39%   |
| Intel I211 Gigabit Network Connection                             | 9         | 3.05%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 2.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.69%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.36%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.36%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.36%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.02%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.02%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.02%   |
| Intel 82562GT 10/100 Network Connection                           | 3         | 1.02%   |
| Huawei STK-L21                                                    | 3         | 1.02%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.68%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.68%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.68%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.68%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.68%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 2         | 0.68%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2         | 0.68%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.68%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.34%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 273       | 56.52%  |
| WiFi     | 206       | 42.65%  |
| Modem    | 4         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 159       | 51.96%  |
| WiFi     | 147       | 48.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 169       | 55.05%  |
| 1     | 121       | 39.41%  |
| 0     | 11        | 3.58%   |
| 3     | 3         | 0.98%   |
| 4     | 2         | 0.65%   |
| 5     | 1         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 291       | 93.57%  |
| Yes  | 20        | 6.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 42.11%  |
| IMC Networks                    | 15        | 8.77%   |
| Broadcom                        | 14        | 8.19%   |
| Realtek Semiconductor           | 13        | 7.6%    |
| Qualcomm Atheros Communications | 12        | 7.02%   |
| Cambridge Silicon Radio         | 9         | 5.26%   |
| Hewlett-Packard                 | 7         | 4.09%   |
| ASUSTek Computer                | 7         | 4.09%   |
| Lite-On Technology              | 4         | 2.34%   |
| Toshiba                         | 3         | 1.75%   |
| Ralink                          | 3         | 1.75%   |
| Apple                           | 3         | 1.75%   |
| Edimax Technology               | 2         | 1.17%   |
| Ralink Technology               | 1         | 0.58%   |
| Qcom                            | 1         | 0.58%   |
| Marvell Semiconductor           | 1         | 0.58%   |
| Integrated System Solution      | 1         | 0.58%   |
| Foxconn International           | 1         | 0.58%   |
| Foxconn / Hon Hai               | 1         | 0.58%   |
| Chicony Electronics             | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 25        | 14.62%  |
| Intel AX201 Bluetooth                               | 15        | 8.77%   |
| Intel AX200 Bluetooth                               | 13        | 7.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 5.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 5.26%   |
| Realtek Bluetooth Radio                             | 8         | 4.68%   |
| IMC Networks Bluetooth Radio                        | 7         | 4.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 2.34%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 2.34%   |
| Intel AX210 Bluetooth                               | 4         | 2.34%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 2.34%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.75%   |
| IMC Networks Bluetooth Device                       | 3         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.75%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.17%   |
| Lite-On Bluetooth Device                            | 2         | 1.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.17%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 1.17%   |
| Edimax Bluetooth Adapter                            | 2         | 1.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.17%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.17%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.17%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 2         | 1.17%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 1.17%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 1.17%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.58%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.58%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.58%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.58%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.58%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.58%   |
| Integrated System Solution Bluetooth Device         | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 222       | 52.86%  |
| AMD                              | 89        | 21.19%  |
| Nvidia                           | 74        | 17.62%  |
| C-Media Electronics              | 5         | 1.19%   |
| Logitech                         | 4         | 0.95%   |
| JMTek                            | 3         | 0.71%   |
| ASUSTek Computer                 | 3         | 0.71%   |
| Texas Instruments                | 2         | 0.48%   |
| BEHRINGER International          | 2         | 0.48%   |
| Yamaha                           | 1         | 0.24%   |
| Textech International            | 1         | 0.24%   |
| Syntek                           | 1         | 0.24%   |
| Sony                             | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| PreSonus Audio Electronics       | 1         | 0.24%   |
| Nam Tai E&E Products             | 1         | 0.24%   |
| Mackie Designs                   | 1         | 0.24%   |
| Lenovo                           | 1         | 0.24%   |
| Kingston Technology              | 1         | 0.24%   |
| iCreate Technologies             | 1         | 0.24%   |
| Hewlett-Packard                  | 1         | 0.24%   |
| FiiO Electronics Technology      | 1         | 0.24%   |
| DSEA A/S                         | 1         | 0.24%   |
| Creative Labs                    | 1         | 0.24%   |
| AKAI Professional M.I.           | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 25        | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 22        | 4.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 19        | 3.89%   |
| Intel Cannon Lake PCH cAVS                                                        | 15        | 3.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 15        | 3.07%   |
| Intel Sunrise Point-LP HD Audio                                                   | 14        | 2.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 14        | 2.86%   |
| AMD Starship/Matisse HD Audio Controller                                          | 12        | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 11        | 2.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 11        | 2.25%   |
| Intel 200 Series PCH HD Audio                                                     | 11        | 2.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 11        | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 10        | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 10        | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 10        | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 10        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                             | 9         | 1.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 9         | 1.84%   |
| Intel 8 Series HD Audio Controller                                                | 9         | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 9         | 1.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 8         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 7         | 1.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 7         | 1.43%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 7         | 1.43%   |
| Intel Broadwell-U Audio Controller                                                | 7         | 1.43%   |
| Nvidia GP106 High Definition Audio Controller                                     | 6         | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 6         | 1.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 6         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 6         | 1.23%   |
| AMD FCH Azalia Controller                                                         | 6         | 1.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 6         | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                                     | 5         | 1.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 5         | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                                     | 4         | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 4         | 0.82%   |
| Nvidia GM206 High Definition Audio Controller                                     | 4         | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                                     | 4         | 0.82%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 4         | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 4         | 0.82%   |
| Nvidia GP102 HDMI Audio Controller                                                | 3         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 41        | 20.6%   |
| Samsung Electronics | 33        | 16.58%  |
| Kingston            | 22        | 11.06%  |
| Crucial             | 22        | 11.06%  |
| Micron Technology   | 21        | 10.55%  |
| Unknown             | 14        | 7.04%   |
| G.Skill             | 13        | 6.53%   |
| Corsair             | 6         | 3.02%   |
| Elpida              | 5         | 2.51%   |
| Nanya Technology    | 4         | 2.01%   |
| Team                | 3         | 1.51%   |
| Ramaxel Technology  | 3         | 1.51%   |
| Patriot             | 3         | 1.51%   |
| A-DATA Technology   | 3         | 1.51%   |
| TakeMS              | 2         | 1.01%   |
| Transcend           | 1         | 0.5%    |
| Qimonda             | 1         | 0.5%    |
| GOODRAM             | 1         | 0.5%    |
| ChangXin Memory     | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                        | 3         | 1.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 3         | 1.38%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s           | 2         | 0.92%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 2         | 0.92%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 2         | 0.92%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.92%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.92%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 2         | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 2         | 0.92%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s    | 2         | 0.92%   |
| Samsung RAM M393B1G70QH0-CMA 8GB DIMM DDR3 1867MT/s       | 2         | 0.92%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4096MB SODIMM DDR3 1334MT/s   | 2         | 0.92%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s    | 2         | 0.92%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 2         | 0.92%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 2         | 0.92%   |
| Crucial RAM CT16G4SFD8266.M16FJ 16GB SODIMM DDR4 2667MT/s | 2         | 0.92%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                 | 1         | 0.46%   |
| Unknown RAM Module 8GB Chip DDR4 2133MT/s                 | 1         | 0.46%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s              | 1         | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR 1600MT/s               | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.46%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                       | 1         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DRAM                     | 1         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 1         | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s               | 1         | 0.46%   |
| Unknown RAM Module 2048MB Chip DDR3 1066MT/s              | 1         | 0.46%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s     | 1         | 0.46%   |
| Transcend RAM JM800QLU-2G 2048MB DIMM DDR 2048MT/s        | 1         | 0.46%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s        | 1         | 0.46%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s        | 1         | 0.46%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s        | 1         | 0.46%   |
| TakeMS RAM TMS4GB364F081139EM 4096MB DIMM DDR3 1333MT/s   | 1         | 0.46%   |
| TakeMS RAM TMS4GB364E081139PP 4GB DIMM DDR3 1333MT/s      | 1         | 0.46%   |
| TakeMS RAM TMS2GB264D081805EV 2048MB DIMM DDR2 800MT/s    | 1         | 0.46%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s              | 1         | 0.46%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s              | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 86        | 50.29%  |
| DDR3    | 52        | 30.41%  |
| DDR2    | 15        | 8.77%   |
| SDRAM   | 7         | 4.09%   |
| LPDDR3  | 4         | 2.34%   |
| LPDDR4  | 3         | 1.75%   |
| Unknown | 2         | 1.17%   |
| DRAM    | 1         | 0.58%   |
| DDR     | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 90        | 53.25%  |
| DIMM         | 68        | 40.24%  |
| Row Of Chips | 8         | 4.73%   |
| Chip         | 2         | 1.18%   |
| FB-DIMM      | 1         | 0.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 65        | 37.14%  |
| 4096  | 42        | 24%     |
| 16384 | 31        | 17.71%  |
| 2048  | 24        | 13.71%  |
| 1024  | 7         | 4%      |
| 32768 | 5         | 2.86%   |
| 512   | 1         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 16.93%  |
| 2667    | 28        | 14.81%  |
| 3200    | 23        | 12.17%  |
| 2400    | 15        | 7.94%   |
| 2133    | 12        | 6.35%   |
| 1333    | 10        | 5.29%   |
| 1334    | 8         | 4.23%   |
| 667     | 8         | 4.23%   |
| 3600    | 5         | 2.65%   |
| 1867    | 5         | 2.65%   |
| 800     | 5         | 2.65%   |
| 3733    | 4         | 2.12%   |
| Unknown | 4         | 2.12%   |
| 2048    | 3         | 1.59%   |
| 1067    | 3         | 1.59%   |
| 4267    | 2         | 1.06%   |
| 4199    | 2         | 1.06%   |
| 3800    | 2         | 1.06%   |
| 3000    | 2         | 1.06%   |
| 2800    | 2         | 1.06%   |
| 1800    | 2         | 1.06%   |
| 49926   | 1         | 0.53%   |
| 8400    | 1         | 0.53%   |
| 4133    | 1         | 0.53%   |
| 3866    | 1         | 0.53%   |
| 3466    | 1         | 0.53%   |
| 3333    | 1         | 0.53%   |
| 2866    | 1         | 0.53%   |
| 1866    | 1         | 0.53%   |
| 1639    | 1         | 0.53%   |
| 1066    | 1         | 0.53%   |
| 975     | 1         | 0.53%   |
| 533     | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 27.27%  |
| Xerox               | 2         | 18.18%  |
| Canon               | 2         | 18.18%  |
| Seiko Epson         | 1         | 9.09%   |
| Samsung Electronics | 1         | 9.09%   |
| Datamax-O'Neil      | 1         | 9.09%   |
| Brother Industries  | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Xerox Phaser 3140 and 3155         | 1         | 9.09%   |
| Xerox Phaser 3010                  | 1         | 9.09%   |
| Seiko Epson L3160 Series           | 1         | 9.09%   |
| Samsung M2070 Series               | 1         | 9.09%   |
| HP DeskJet F4200 series            | 1         | 9.09%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 9.09%   |
| HP Color LaserJet 2605dn           | 1         | 9.09%   |
| Datamax-O'Neil Datamax E-4304      | 1         | 9.09%   |
| Canon PIXMA MX390 Series           | 1         | 9.09%   |
| Canon PIXMA MP250                  | 1         | 9.09%   |
| Brother DCP-L2530DW series         | 1         | 9.09%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 4         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 25%     |
| Canon CanoScan LiDE 700F           | 1         | 25%     |
| Canon CanoScan LiDE 220            | 1         | 25%     |
| Canon CanoScan 4200F               | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 46        | 28.93%  |
| IMC Networks                           | 18        | 11.32%  |
| Realtek Semiconductor                  | 11        | 6.92%   |
| Sunplus Innovation Technology          | 9         | 5.66%   |
| Quanta                                 | 9         | 5.66%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.66%   |
| Acer                                   | 9         | 5.66%   |
| Microdia                               | 8         | 5.03%   |
| Logitech                               | 8         | 5.03%   |
| Lite-On Technology                     | 6         | 3.77%   |
| Apple                                  | 4         | 2.52%   |
| Suyin                                  | 3         | 1.89%   |
| Lenovo                                 | 3         | 1.89%   |
| Syntek                                 | 2         | 1.26%   |
| Samsung Electronics                    | 2         | 1.26%   |
| Primax Electronics                     | 2         | 1.26%   |
| Generalplus Technology                 | 2         | 1.26%   |
| Z-Star Microelectronics                | 1         | 0.63%   |
| Unknown (3730304231393931415053)       | 1         | 0.63%   |
| Sony                                   | 1         | 0.63%   |
| Ricoh                                  | 1         | 0.63%   |
| Pixart Imaging                         | 1         | 0.63%   |
| MacroSilicon                           | 1         | 0.63%   |
| DJJHFA1BIF5595                         | 1         | 0.63%   |
| Cubeternet                             | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                        | 9         | 5.56%   |
| Microdia Integrated_Webcam_HD                                    | 7         | 4.32%   |
| IMC Networks Integrated Camera                                   | 6         | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                | 4         | 2.47%   |
| Acer Integrated Camera                                           | 4         | 2.47%   |
| Sunplus HP HD Webcam [Fixed]                                     | 3         | 1.85%   |
| Realtek USB Camera                                               | 3         | 1.85%   |
| Lite-On HP HD Webcam                                             | 3         | 1.85%   |
| Chicony USB2.0 HD UVC WebCam                                     | 3         | 1.85%   |
| Chicony HP HD Webcam                                             | 3         | 1.85%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                 | 3         | 1.85%   |
| Syntek Lenovo EasyCamera                                         | 2         | 1.23%   |
| Sunplus HD WebCam                                                | 2         | 1.23%   |
| Samsung Galaxy A5 (MTP)                                          | 2         | 1.23%   |
| Realtek Integrated_Webcam_HD                                     | 2         | 1.23%   |
| Realtek Asus laptop camera                                       | 2         | 1.23%   |
| Quanta HP Webcam                                                 | 2         | 1.23%   |
| Quanta HP TrueVision HD Camera                                   | 2         | 1.23%   |
| Quanta HP HD Camera                                              | 2         | 1.23%   |
| Primax HP HD Webcam [Fixed]                                      | 2         | 1.23%   |
| Logitech Webcam C310                                             | 2         | 1.23%   |
| Lite-On HP HD Camera                                             | 2         | 1.23%   |
| Lenovo Integrated Webcam [R5U877]                                | 2         | 1.23%   |
| IMC Networks USB2.0 VGA UVC WebCam                               | 2         | 1.23%   |
| IMC Networks Integrated Webcam                                   | 2         | 1.23%   |
| Generalplus GENERAL WEBCAM                                       | 2         | 1.23%   |
| Chicony USB2.0 VGA UVC WebCam                                    | 2         | 1.23%   |
| Chicony USB2.0 UVC WebCam                                        | 2         | 1.23%   |
| Chicony Lenovo EasyCamera                                        | 2         | 1.23%   |
| Chicony Integrated Camera [ThinkPad]                             | 2         | 1.23%   |
| Chicony Integrated Camera (1280x720@30)                          | 2         | 1.23%   |
| Chicony HP Wide Vision HD Camera                                 | 2         | 1.23%   |
| Chicony HP Webcam                                                | 2         | 1.23%   |
| Chicony HP TrueVision HD Camera                                  | 2         | 1.23%   |
| Chicony CNF7042                                                  | 2         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision FHD Camera | 2         | 1.23%   |
| Apple FaceTime HD Camera (Built-in)                              | 2         | 1.23%   |
| Acer Integrated IR Camera                                        | 2         | 1.23%   |
| Z-Star Venus USB2.0 Camera                                       | 1         | 0.62%   |
| Unknown (3730304231393931415053) USB Camera                      | 1         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 17        | 35.42%  |
| Validity Sensors           | 14        | 29.17%  |
| AuthenTec                  | 6         | 12.5%   |
| Upek                       | 4         | 8.33%   |
| Shenzhen Goodix Technology | 4         | 8.33%   |
| Elan Microelectronics      | 2         | 4.17%   |
| STMicroelectronics         | 1         | 2.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 6         | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 6         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 8.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 4         | 8.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                        | 3         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 4.17%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 4.17%   |
| AuthenTec AES2810                                          | 2         | 4.17%   |
| Unknown                                                    | 2         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 1         | 2.08%   |
| Validity Sensors VFS491                                    | 1         | 2.08%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.08%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.08%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.08%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.08%   |
| Elan fingerprint sensor [FeinTech FPS00200]                | 1         | 2.08%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.08%   |
| AuthenTec Fingerprint Sensor                               | 1         | 2.08%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 2.08%   |
| AuthenTec AES1600                                          | 1         | 2.08%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Alcor Micro      | 7         | 50%     |
| Broadcom         | 3         | 21.43%  |
| O2 Micro         | 2         | 14.29%  |
| Upek             | 1         | 7.14%   |
| SCM Microsystems | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 7         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader                       | 2         | 14.29%  |
| Broadcom 58200                                             | 2         | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 7.14%   |
| SCM Microsystems uTrust 3512 SAM slot Token                | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 210       | 68.18%  |
| 1     | 74        | 24.03%  |
| 2     | 23        | 7.47%   |
| 3     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 48        | 39.67%  |
| Graphics card            | 24        | 19.83%  |
| Chipcard                 | 14        | 11.57%  |
| Net/wireless             | 11        | 9.09%   |
| Multimedia controller    | 8         | 6.61%   |
| Communication controller | 4         | 3.31%   |
| Bluetooth                | 4         | 3.31%   |
| Storage                  | 3         | 2.48%   |
| Unassigned class         | 1         | 0.83%   |
| Net/ethernet             | 1         | 0.83%   |
| Dvb card                 | 1         | 0.83%   |
| Card reader              | 1         | 0.83%   |
| Camera                   | 1         | 0.83%   |


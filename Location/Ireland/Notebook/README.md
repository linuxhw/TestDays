Linux in Ireland - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ireland.

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

Total: 409

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | InfinityBook Pro 14 Gen6    | [946e66e35e](https://linux-hardware.org/?probe=946e66e35e) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [90fcc2d8d5](https://linux-hardware.org/?probe=90fcc2d8d5) | Nov 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [2c077b8cde](https://linux-hardware.org/?probe=2c077b8cde) | Nov 23, 2022 |
| Acer          | Aspire A514-55              | [7bf0186e00](https://linux-hardware.org/?probe=7bf0186e00) | Nov 18, 2022 |
| Chuwi         | X312B                       | [b0c9263212](https://linux-hardware.org/?probe=b0c9263212) | Nov 17, 2022 |
| Chuwi         | X312B                       | [7583d01bd8](https://linux-hardware.org/?probe=7583d01bd8) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [a174d2b2b3](https://linux-hardware.org/?probe=a174d2b2b3) | Nov 12, 2022 |
| Valve         | Jupiter                     | [ed3f6fb61d](https://linux-hardware.org/?probe=ed3f6fb61d) | Nov 12, 2022 |
| Valve         | Jupiter                     | [c1805091ef](https://linux-hardware.org/?probe=c1805091ef) | Nov 12, 2022 |
| Chuwi         | X312B                       | [0e6a368329](https://linux-hardware.org/?probe=0e6a368329) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5d2ae18b0a](https://linux-hardware.org/?probe=5d2ae18b0a) | Nov 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [51a3c87183](https://linux-hardware.org/?probe=51a3c87183) | Nov 10, 2022 |
| Lenovo        | ThinkPad A275 20KDS01S00    | [a8eacd4e3a](https://linux-hardware.org/?probe=a8eacd4e3a) | Nov 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [bf3996f87d](https://linux-hardware.org/?probe=bf3996f87d) | Nov 03, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [1d4a6dc6dc](https://linux-hardware.org/?probe=1d4a6dc6dc) | Oct 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [a1694d3adc](https://linux-hardware.org/?probe=a1694d3adc) | Oct 29, 2022 |
| Dell          | Inspiron 15-7568            | [ae536fa220](https://linux-hardware.org/?probe=ae536fa220) | Oct 27, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| Dell          | Latitude E6440              | [692b716621](https://linux-hardware.org/?probe=692b716621) | Oct 23, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [e03569f758](https://linux-hardware.org/?probe=e03569f758) | Oct 20, 2022 |
| Lenovo        | ThinkPad P52 20MAS17205     | [be48cfe3be](https://linux-hardware.org/?probe=be48cfe3be) | Oct 20, 2022 |
| Dell          | Latitude 7400               | [3b340aa7d4](https://linux-hardware.org/?probe=3b340aa7d4) | Oct 12, 2022 |
| Dell          | Latitude 7400               | [159021ed29](https://linux-hardware.org/?probe=159021ed29) | Oct 12, 2022 |
| Toshiba       | PORTEGE R830                | [ffda659565](https://linux-hardware.org/?probe=ffda659565) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| Timi          | TM1709                      | [33022811a8](https://linux-hardware.org/?probe=33022811a8) | Oct 01, 2022 |
| Dell          | Latitude 7420               | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [099ffbf0bc](https://linux-hardware.org/?probe=099ffbf0bc) | Sep 10, 2022 |
| HP            | Pavilion m6                 | [83b6eb0119](https://linux-hardware.org/?probe=83b6eb0119) | Sep 01, 2022 |
| Medion        | E6227                       | [e6ca2257e7](https://linux-hardware.org/?probe=e6ca2257e7) | Sep 01, 2022 |
| Dell          | XPS 9320                    | [7fe70d3907](https://linux-hardware.org/?probe=7fe70d3907) | Aug 30, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| HP            | Pavilion g6                 | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| HP            | EliteBook 755 G5            | [795c2046ba](https://linux-hardware.org/?probe=795c2046ba) | Aug 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 9320                    | [bdb29b0481](https://linux-hardware.org/?probe=bdb29b0481) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [1d0ef5711d](https://linux-hardware.org/?probe=1d0ef5711d) | Aug 11, 2022 |
| HP            | Pavilion g6                 | [3f462439ed](https://linux-hardware.org/?probe=3f462439ed) | Aug 11, 2022 |
| Samsung       | 935XDB                      | [fcfe8368c6](https://linux-hardware.org/?probe=fcfe8368c6) | Aug 08, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Jumper        | EZbook                      | [5e7336ee93](https://linux-hardware.org/?probe=5e7336ee93) | Jul 02, 2022 |
| Dell          | XPS 15 9520                 | [ca7efa311a](https://linux-hardware.org/?probe=ca7efa311a) | Jul 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [282d2ad16b](https://linux-hardware.org/?probe=282d2ad16b) | Jun 29, 2022 |
| ASUSTek       | X411UN                      | [d4543f64dc](https://linux-hardware.org/?probe=d4543f64dc) | Jun 24, 2022 |
| ASUSTek       | X411UN                      | [57e0198d3a](https://linux-hardware.org/?probe=57e0198d3a) | Jun 23, 2022 |
| Samsung       | 935XDB                      | [7089a0f6bc](https://linux-hardware.org/?probe=7089a0f6bc) | Jun 20, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [5caa4002f1](https://linux-hardware.org/?probe=5caa4002f1) | Jun 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [d9ac2ec5c8](https://linux-hardware.org/?probe=d9ac2ec5c8) | Jun 08, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a38fb61dfb](https://linux-hardware.org/?probe=a38fb61dfb) | Jun 08, 2022 |
| Samsung       | 935XDB                      | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Dell          | Precision M4800             | [3bd843466c](https://linux-hardware.org/?probe=3bd843466c) | Jun 04, 2022 |
| Dell          | Latitude 9420               | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [0a87c33624](https://linux-hardware.org/?probe=0a87c33624) | Jun 01, 2022 |
| HP            | EliteBook 840 G1            | [07b116767e](https://linux-hardware.org/?probe=07b116767e) | May 27, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| ASUSTek       | UX330UAK                    | [7b50efe523](https://linux-hardware.org/?probe=7b50efe523) | May 19, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f71977d1fa](https://linux-hardware.org/?probe=f71977d1fa) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| MSI           | Stealth GS66 12UGS          | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| Dell          | Inspiron 7577               | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | Laptop 14-ck0xxx            | [02dd52b3b5](https://linux-hardware.org/?probe=02dd52b3b5) | Apr 21, 2022 |
| Dell          | Latitude E6230              | [617c507040](https://linux-hardware.org/?probe=617c507040) | Apr 19, 2022 |
| Dell          | Latitude E6230              | [98f4014ead](https://linux-hardware.org/?probe=98f4014ead) | Apr 19, 2022 |
| Packard Be... | EasyNote TK85               | [c20035dfb3](https://linux-hardware.org/?probe=c20035dfb3) | Apr 16, 2022 |
| Dell          | Latitude E6520              | [b10c0f8457](https://linux-hardware.org/?probe=b10c0f8457) | Apr 14, 2022 |
| Packard Be... | EasyNote TK85               | [c0eb727f3c](https://linux-hardware.org/?probe=c0eb727f3c) | Apr 12, 2022 |
| Packard Be... | EasyNote TK85               | [13d6da4ad9](https://linux-hardware.org/?probe=13d6da4ad9) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Dell          | Latitude 5420               | [75963e8b7d](https://linux-hardware.org/?probe=75963e8b7d) | Apr 01, 2022 |
| Dell          | Latitude E5440              | [82d2c39d98](https://linux-hardware.org/?probe=82d2c39d98) | Mar 30, 2022 |
| Dell          | Latitude E6430              | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| PC Special... | NH5xAx                      | [ebf60d959f](https://linux-hardware.org/?probe=ebf60d959f) | Mar 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | [e7c5306c00](https://linux-hardware.org/?probe=e7c5306c00) | Mar 10, 2022 |
| Dell          | Latitude 9420               | [355f64f6a7](https://linux-hardware.org/?probe=355f64f6a7) | Mar 03, 2022 |
| ASUSTek       | GL753VE                     | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Dell          | Precision M4600             | [9f1f4fcf9c](https://linux-hardware.org/?probe=9f1f4fcf9c) | Feb 18, 2022 |
| Acer          | Predator PH317-54           | [8fb9ac25be](https://linux-hardware.org/?probe=8fb9ac25be) | Feb 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Lenovo        | ThinkPad T480s 20L7S0VJ0... | [7535369bb0](https://linux-hardware.org/?probe=7535369bb0) | Jan 31, 2022 |
| Dell          | XPS 13 9310                 | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Toshiba       | PORTEGE R830                | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| Dell          | Latitude 5411               | [2064d78411](https://linux-hardware.org/?probe=2064d78411) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291W99       | [ead56def80](https://linux-hardware.org/?probe=ead56def80) | Dec 26, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [609264397b](https://linux-hardware.org/?probe=609264397b) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Lenovo        | ThinkPad E560 20EV000TUK    | [eefaa1b951](https://linux-hardware.org/?probe=eefaa1b951) | Dec 18, 2021 |
| AVITA         | NS14A8                      | [0ae2523309](https://linux-hardware.org/?probe=0ae2523309) | Dec 18, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [86d1d49f33](https://linux-hardware.org/?probe=86d1d49f33) | Dec 09, 2021 |
| Acer          | AOD255                      | [eae98753db](https://linux-hardware.org/?probe=eae98753db) | Dec 03, 2021 |
| Acer          | AOD255                      | [d2e31c1441](https://linux-hardware.org/?probe=d2e31c1441) | Dec 02, 2021 |
| Acer          | Aspire A315-51              | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Sony          | VPCCB35FG                   | [6e46b79e09](https://linux-hardware.org/?probe=6e46b79e09) | Nov 27, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| HP            | Laptop 17-cn0xxx            | [291a2a17e2](https://linux-hardware.org/?probe=291a2a17e2) | Nov 21, 2021 |
| Dell          | Inspiron MM061              | [0424bd331e](https://linux-hardware.org/?probe=0424bd331e) | Nov 10, 2021 |
| HP            | Notebook                    | [65c122fe69](https://linux-hardware.org/?probe=65c122fe69) | Oct 31, 2021 |
| Dell          | XPS 13 9310                 | [22bc284f45](https://linux-hardware.org/?probe=22bc284f45) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | [7105829e72](https://linux-hardware.org/?probe=7105829e72) | Oct 25, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Lenovo        | G550 2958                   | [b9412e1ab2](https://linux-hardware.org/?probe=b9412e1ab2) | Oct 23, 2021 |
| Lenovo        | G550 2958                   | [a0ff38d606](https://linux-hardware.org/?probe=a0ff38d606) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c11c89f0d4](https://linux-hardware.org/?probe=c11c89f0d4) | Oct 19, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| Toshiba       | PORTEGE R830                | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| Acer          | Nitro AN515-45              | [f564d05797](https://linux-hardware.org/?probe=f564d05797) | Oct 05, 2021 |
| Apple         | MacBookPro5,3               | [b0ea83da4d](https://linux-hardware.org/?probe=b0ea83da4d) | Oct 02, 2021 |
| Lenovo        | ThinkPad X230 Tablet 343... | [ddcd85bbe5](https://linux-hardware.org/?probe=ddcd85bbe5) | Oct 02, 2021 |
| Timi          | TM1607                      | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| HP            | Notebook                    | [9c7d616423](https://linux-hardware.org/?probe=9c7d616423) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Dell          | Inspiron 3585               | [3a55618aee](https://linux-hardware.org/?probe=3a55618aee) | Sep 10, 2021 |
| Lenovo        | ThinkPad E15 20RD0015FR     | [8a229968ef](https://linux-hardware.org/?probe=8a229968ef) | Sep 06, 2021 |
| Samsung       | 550P5C/550P7C               | [c483c45fc4](https://linux-hardware.org/?probe=c483c45fc4) | Sep 03, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Toshiba       | Satellite A300              | [c5391fae24](https://linux-hardware.org/?probe=c5391fae24) | Aug 27, 2021 |
| Dell          | Precision 5550              | [705dbe4068](https://linux-hardware.org/?probe=705dbe4068) | Aug 21, 2021 |
| Medion        | Akoya E6239                 | [e22d5c4b21](https://linux-hardware.org/?probe=e22d5c4b21) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Sony          | VPCCB35FG                   | [6550f39d03](https://linux-hardware.org/?probe=6550f39d03) | Aug 10, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Acer          | Swift SF313-53              | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [73902de0d8](https://linux-hardware.org/?probe=73902de0d8) | Jul 31, 2021 |
| Dell          | Studio XPS 1640             | [00d5936a25](https://linux-hardware.org/?probe=00d5936a25) | Jul 22, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [1046a771fd](https://linux-hardware.org/?probe=1046a771fd) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [77ab0c578d](https://linux-hardware.org/?probe=77ab0c578d) | Jul 17, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [06ba47ee9a](https://linux-hardware.org/?probe=06ba47ee9a) | Jul 17, 2021 |
| Dell          | Latitude 7370               | [4fc6100966](https://linux-hardware.org/?probe=4fc6100966) | Jul 03, 2021 |
| Dell          | Latitude 7370               | [2acd089f78](https://linux-hardware.org/?probe=2acd089f78) | Jul 03, 2021 |
| Entroware     | Apollo                      | [3cbf412b11](https://linux-hardware.org/?probe=3cbf412b11) | Jul 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fff9c1a758](https://linux-hardware.org/?probe=fff9c1a758) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [3980434b64](https://linux-hardware.org/?probe=3980434b64) | Jun 19, 2021 |
| Dell          | Inspiron 1525               | [511a525213](https://linux-hardware.org/?probe=511a525213) | Jun 11, 2021 |
| Dell          | XPS 13 9300                 | [63f094943a](https://linux-hardware.org/?probe=63f094943a) | Jun 07, 2021 |
| Dell          | Latitude C810               | [f379321c88](https://linux-hardware.org/?probe=f379321c88) | Jun 05, 2021 |
| Dell          | Inspiron MM061              | [62b30f282d](https://linux-hardware.org/?probe=62b30f282d) | Jun 04, 2021 |
| Dell          | Latitude C810               | [23e6f5572a](https://linux-hardware.org/?probe=23e6f5572a) | Jun 04, 2021 |
| Toshiba       | TECRA M4                    | [3ac511cc5f](https://linux-hardware.org/?probe=3ac511cc5f) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [6fff0f3407](https://linux-hardware.org/?probe=6fff0f3407) | Jun 03, 2021 |
| Lenovo        | B50-30 80ES                 | [cfa1b1a4fd](https://linux-hardware.org/?probe=cfa1b1a4fd) | Jun 03, 2021 |
| Dell          | Inspiron 1764               | [a41c941365](https://linux-hardware.org/?probe=a41c941365) | Jun 02, 2021 |
| Entroware     | Proteus                     | [0ecc547a14](https://linux-hardware.org/?probe=0ecc547a14) | May 31, 2021 |
| HP            | Pavilion 15                 | [14128860c2](https://linux-hardware.org/?probe=14128860c2) | May 27, 2021 |
| HP            | ProBook 6550b               | [523c397ab6](https://linux-hardware.org/?probe=523c397ab6) | May 27, 2021 |
| Dell          | XPS 13 7390                 | [e7292a5491](https://linux-hardware.org/?probe=e7292a5491) | May 26, 2021 |
| HP            | Pavilion Notebook           | [bb6ab823e7](https://linux-hardware.org/?probe=bb6ab823e7) | May 23, 2021 |
| HP            | 15                          | [ab211b6ad8](https://linux-hardware.org/?probe=ab211b6ad8) | May 21, 2021 |
| HP            | 15                          | [d285154a2b](https://linux-hardware.org/?probe=d285154a2b) | May 21, 2021 |
| Entroware     | Proteus                     | [98be1903c4](https://linux-hardware.org/?probe=98be1903c4) | May 17, 2021 |
| Lenovo        | V145-15AST 81MT             | [80f0e0228b](https://linux-hardware.org/?probe=80f0e0228b) | May 16, 2021 |
| Dell          | Latitude 5520               | [34c3dc01e9](https://linux-hardware.org/?probe=34c3dc01e9) | May 07, 2021 |
| HP            | HDX 18                      | [dead2b5b56](https://linux-hardware.org/?probe=dead2b5b56) | May 07, 2021 |
| HP            | EliteBook Folio G1          | [f3bdc3e991](https://linux-hardware.org/?probe=f3bdc3e991) | Apr 24, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9c0bbd0e0c](https://linux-hardware.org/?probe=9c0bbd0e0c) | Apr 18, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [51b67b480d](https://linux-hardware.org/?probe=51b67b480d) | Apr 05, 2021 |
| HP            | Pavilion g6                 | [726040b78b](https://linux-hardware.org/?probe=726040b78b) | Apr 03, 2021 |
| Acer          | Aspire 5920G                | [9976792f0f](https://linux-hardware.org/?probe=9976792f0f) | Mar 26, 2021 |
| Lenovo        | ThinkPad W530 24491D1       | [31a4336d63](https://linux-hardware.org/?probe=31a4336d63) | Mar 25, 2021 |
| Microtech     | e-book Lite                 | [85b6d19466](https://linux-hardware.org/?probe=85b6d19466) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [488904f6d8](https://linux-hardware.org/?probe=488904f6d8) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [7fbf31af63](https://linux-hardware.org/?probe=7fbf31af63) | Mar 18, 2021 |
| ASUSTek       | X540LA                      | [8b0145ff0c](https://linux-hardware.org/?probe=8b0145ff0c) | Mar 13, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| Chuwi         | GemiBook Pro                | [f2f15e9ef1](https://linux-hardware.org/?probe=f2f15e9ef1) | Mar 10, 2021 |
| HP            | Pavilion m6                 | [578aad5ad5](https://linux-hardware.org/?probe=578aad5ad5) | Feb 24, 2021 |
| HP            | Notebook                    | [21ead6ec52](https://linux-hardware.org/?probe=21ead6ec52) | Feb 22, 2021 |
| Chuwi         | GemiBook Pro                | [7dbba6ee59](https://linux-hardware.org/?probe=7dbba6ee59) | Feb 21, 2021 |
| HP            | Compaq 6530b (GW688AV)      | [2812d098fd](https://linux-hardware.org/?probe=2812d098fd) | Feb 20, 2021 |
| HP            | Stream Laptop 11-y0XX       | [ce0aecd52b](https://linux-hardware.org/?probe=ce0aecd52b) | Feb 20, 2021 |
| HP            | EliteBook 745 G6            | [3bf39bac3e](https://linux-hardware.org/?probe=3bf39bac3e) | Feb 19, 2021 |
| Apple         | MacBookPro2,2               | [52f24b3228](https://linux-hardware.org/?probe=52f24b3228) | Feb 19, 2021 |
| Acer          | Aspire F5-573G              | [6fad2f0ade](https://linux-hardware.org/?probe=6fad2f0ade) | Feb 14, 2021 |
| Chuwi         | GemiBook Pro                | [46556ad380](https://linux-hardware.org/?probe=46556ad380) | Feb 14, 2021 |
| ASUSTek       | ZenBook S UX391UA           | [ec083139fc](https://linux-hardware.org/?probe=ec083139fc) | Feb 05, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [b1ed72b941](https://linux-hardware.org/?probe=b1ed72b941) | Feb 04, 2021 |
| Lenovo        | ThinkPad P52 20MAS17205     | [0a2ca85ddc](https://linux-hardware.org/?probe=0a2ca85ddc) | Jan 22, 2021 |
| Lenovo        | V110-15ISK 80TL             | [9f3cf476f3](https://linux-hardware.org/?probe=9f3cf476f3) | Jan 19, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [e8cd5368b0](https://linux-hardware.org/?probe=e8cd5368b0) | Jan 14, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Dell          | System XPS L502X            | [8b67c2132b](https://linux-hardware.org/?probe=8b67c2132b) | Jan 13, 2021 |
| Dell          | Precision 5550              | [ba201aad9e](https://linux-hardware.org/?probe=ba201aad9e) | Jan 11, 2021 |
| HUAWEI        | BOHL-WXX9                   | [5845d9565c](https://linux-hardware.org/?probe=5845d9565c) | Jan 05, 2021 |
| ASUSTek       | X550CC                      | [40ae1409a4](https://linux-hardware.org/?probe=40ae1409a4) | Jan 05, 2021 |
| Entroware     | Proteus                     | [7d71ef8a53](https://linux-hardware.org/?probe=7d71ef8a53) | Jan 05, 2021 |
| Samsung       | N150/N210/N220              | [e556ab958b](https://linux-hardware.org/?probe=e556ab958b) | Jan 02, 2021 |
| Samsung       | N150/N210/N220              | [adc4530996](https://linux-hardware.org/?probe=adc4530996) | Jan 01, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [b34a40d6b3](https://linux-hardware.org/?probe=b34a40d6b3) | Dec 31, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [8740e02802](https://linux-hardware.org/?probe=8740e02802) | Dec 29, 2020 |
| Dell          | System XPS L502X            | [dda884ab5b](https://linux-hardware.org/?probe=dda884ab5b) | Dec 20, 2020 |
| Acer          | Aspire 5551                 | [cb35dac70b](https://linux-hardware.org/?probe=cb35dac70b) | Dec 09, 2020 |
| HP            | Notebook                    | [2564f14d0b](https://linux-hardware.org/?probe=2564f14d0b) | Dec 06, 2020 |
| Lenovo        | G580 20157                  | [325dd21da3](https://linux-hardware.org/?probe=325dd21da3) | Nov 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [703167df7b](https://linux-hardware.org/?probe=703167df7b) | Nov 24, 2020 |
| Dell          | Inspiron 15-3567            | [04e06f0e3b](https://linux-hardware.org/?probe=04e06f0e3b) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| HP            | EliteBook 8740w             | [f30611840c](https://linux-hardware.org/?probe=f30611840c) | Nov 23, 2020 |
| PC Special... | PCX0DX                      | [b4498047ef](https://linux-hardware.org/?probe=b4498047ef) | Nov 22, 2020 |
| Apple         | MacBookPro5,4               | [a7492067f0](https://linux-hardware.org/?probe=a7492067f0) | Nov 21, 2020 |
| HP            | EliteBook 820 G1            | [4db5c39f50](https://linux-hardware.org/?probe=4db5c39f50) | Nov 21, 2020 |
| Lenovo        | ThinkPad T400 64754G7       | [770660037c](https://linux-hardware.org/?probe=770660037c) | Nov 21, 2020 |
| HP            | EliteBook 8740w             | [072b557a79](https://linux-hardware.org/?probe=072b557a79) | Nov 20, 2020 |
| Lenovo        | G580 20157                  | [58fc01c757](https://linux-hardware.org/?probe=58fc01c757) | Nov 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [578d1badca](https://linux-hardware.org/?probe=578d1badca) | Nov 18, 2020 |
| Alienware     | 17 R4                       | [8b7402a4e7](https://linux-hardware.org/?probe=8b7402a4e7) | Nov 16, 2020 |
| Alienware     | 17 R4                       | [62e5ac4fd3](https://linux-hardware.org/?probe=62e5ac4fd3) | Nov 16, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [7132bcc66d](https://linux-hardware.org/?probe=7132bcc66d) | Nov 15, 2020 |
| Dell          | Latitude E6420              | [f542aafd19](https://linux-hardware.org/?probe=f542aafd19) | Nov 13, 2020 |
| Notebook      | NL40_50CU                   | [893477956d](https://linux-hardware.org/?probe=893477956d) | Nov 10, 2020 |
| Toshiba       | Satellite Pro R50-B         | [418e9ce805](https://linux-hardware.org/?probe=418e9ce805) | Nov 06, 2020 |
| Toshiba       | Satellite Pro R50-B         | [7780f8f320](https://linux-hardware.org/?probe=7780f8f320) | Nov 06, 2020 |
| System76      | Galago Pro                  | [79822a5348](https://linux-hardware.org/?probe=79822a5348) | Nov 04, 2020 |
| Dell          | XPS M1530                   | [bc52d9b9a4](https://linux-hardware.org/?probe=bc52d9b9a4) | Nov 03, 2020 |
| Medion        | E6239 MD99452               | [2496b738ac](https://linux-hardware.org/?probe=2496b738ac) | Oct 29, 2020 |
| Medion        | E6239 MD99452               | [f875a122f9](https://linux-hardware.org/?probe=f875a122f9) | Oct 29, 2020 |
| PC Special... | TF                          | [e651ccb88e](https://linux-hardware.org/?probe=e651ccb88e) | Oct 29, 2020 |
| HP            | ZBook 15 G2                 | [0b113f8315](https://linux-hardware.org/?probe=0b113f8315) | Oct 29, 2020 |
| PC Special... | TF                          | [ba278ca133](https://linux-hardware.org/?probe=ba278ca133) | Oct 29, 2020 |
| HP            | Laptop 14-bs0xx             | [0e16f54971](https://linux-hardware.org/?probe=0e16f54971) | Oct 28, 2020 |
| Toshiba       | Satellite C50-B             | [0edec7c57f](https://linux-hardware.org/?probe=0edec7c57f) | Oct 27, 2020 |
| Toshiba       | Satellite C50-B             | [21e26c80bc](https://linux-hardware.org/?probe=21e26c80bc) | Oct 27, 2020 |
| Dell          | Vostro 3700                 | [5493bcf45a](https://linux-hardware.org/?probe=5493bcf45a) | Oct 26, 2020 |
| ASUSTek       | E200HA                      | [2db5bc3b28](https://linux-hardware.org/?probe=2db5bc3b28) | Oct 23, 2020 |
| ASUSTek       | E200HA                      | [acc7a651ac](https://linux-hardware.org/?probe=acc7a651ac) | Oct 23, 2020 |
| TUXEDO        | InfinityBook Pro 15 v5      | [6aea9a482c](https://linux-hardware.org/?probe=6aea9a482c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [96ff229c4c](https://linux-hardware.org/?probe=96ff229c4c) | Oct 17, 2020 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [a0292a1315](https://linux-hardware.org/?probe=a0292a1315) | Oct 15, 2020 |
| Apple         | MacBook5,1                  | [598a9af3a1](https://linux-hardware.org/?probe=598a9af3a1) | Oct 12, 2020 |
| Dell          | XPS 13 9360                 | [1554f3d77d](https://linux-hardware.org/?probe=1554f3d77d) | Oct 05, 2020 |
| Toshiba       | Satellite L50-B             | [58ce88778b](https://linux-hardware.org/?probe=58ce88778b) | Sep 23, 2020 |
| HP            | G70                         | [198fd94bda](https://linux-hardware.org/?probe=198fd94bda) | Sep 13, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| HP            | 255 G2                      | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Lenovo        | U410                        | [ad05692bf0](https://linux-hardware.org/?probe=ad05692bf0) | Sep 02, 2020 |
| HP            | Laptop 14-bs0xx             | [0eaa4ae12f](https://linux-hardware.org/?probe=0eaa4ae12f) | Aug 09, 2020 |
| Lenovo        | ThinkPad T430 2349G4G       | [db1ba375f2](https://linux-hardware.org/?probe=db1ba375f2) | Aug 08, 2020 |
| Acer          | Aspire 5349                 | [fdae61b8d4](https://linux-hardware.org/?probe=fdae61b8d4) | Aug 07, 2020 |
| ASUSTek       | E200HA                      | [d702543fbb](https://linux-hardware.org/?probe=d702543fbb) | Aug 06, 2020 |
| Dell          | Latitude E7450              | [e0eee5c0fc](https://linux-hardware.org/?probe=e0eee5c0fc) | Aug 01, 2020 |
| Dell          | Latitude E7450              | [a8695dbee5](https://linux-hardware.org/?probe=a8695dbee5) | Aug 01, 2020 |
| PC Special... | N150CU                      | [6d19fc4569](https://linux-hardware.org/?probe=6d19fc4569) | Aug 01, 2020 |
| Lenovo        | ThinkPad T430 2349KB4       | [291151dae1](https://linux-hardware.org/?probe=291151dae1) | Jul 31, 2020 |
| MSI           | WS65 9TK                    | [e9feed814f](https://linux-hardware.org/?probe=e9feed814f) | Jul 29, 2020 |
| MSI           | WS65 9TK                    | [b296acb26a](https://linux-hardware.org/?probe=b296acb26a) | Jul 29, 2020 |
| HP            | Pavilion dm1                | [cc8ed632dc](https://linux-hardware.org/?probe=cc8ed632dc) | Jul 25, 2020 |
| Dell          | Latitude 5480               | [e06096d959](https://linux-hardware.org/?probe=e06096d959) | Jul 24, 2020 |
| Lenovo        | V110-15ISK 80TL             | [a8709e5362](https://linux-hardware.org/?probe=a8709e5362) | Jul 23, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [bdf2ff973b](https://linux-hardware.org/?probe=bdf2ff973b) | Jul 20, 2020 |
| Dell          | Latitude 5400               | [11473792e0](https://linux-hardware.org/?probe=11473792e0) | Jul 19, 2020 |
| HP            | 255 G2                      | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | G500 VIWGP                  | [37286d3145](https://linux-hardware.org/?probe=37286d3145) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Apple         | MacBookPro8,3               | [2a16561ffa](https://linux-hardware.org/?probe=2a16561ffa) | Jun 28, 2020 |
| Apple         | MacBookPro8,3               | [8ba0fcfe7c](https://linux-hardware.org/?probe=8ba0fcfe7c) | Jun 28, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [a36f83366b](https://linux-hardware.org/?probe=a36f83366b) | Jun 21, 2020 |
| Dell          | Inspiron 15-3552            | [168dcc66c7](https://linux-hardware.org/?probe=168dcc66c7) | Jun 17, 2020 |
| Timi          | TM1703                      | [d3d89dc21d](https://linux-hardware.org/?probe=d3d89dc21d) | Jun 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [1cfb078c4e](https://linux-hardware.org/?probe=1cfb078c4e) | Jun 13, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3443C... | [18230e354a](https://linux-hardware.org/?probe=18230e354a) | Jun 13, 2020 |
| SLIMBOOK      | PROX15                      | [a4e6b0723d](https://linux-hardware.org/?probe=a4e6b0723d) | Jun 12, 2020 |
| ASUSTek       | G750JW                      | [cc02e1e15c](https://linux-hardware.org/?probe=cc02e1e15c) | Jun 10, 2020 |
| Dell          | Latitude E5420              | [eb3a4e918a](https://linux-hardware.org/?probe=eb3a4e918a) | Jun 08, 2020 |
| Lenovo        | ThinkPad X1 Carbon 34431... | [c5d45645b7](https://linux-hardware.org/?probe=c5d45645b7) | Jun 01, 2020 |
| Acer          | Aspire V3-571G              | [fbef0c90d4](https://linux-hardware.org/?probe=fbef0c90d4) | May 28, 2020 |
| Lenovo        | ThinkPad T410s 2904HDU      | [b1eb7716ed](https://linux-hardware.org/?probe=b1eb7716ed) | May 26, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Lenovo        | ThinkPad P52 20MAS17205     | [4547e0d6fe](https://linux-hardware.org/?probe=4547e0d6fe) | May 25, 2020 |
| Chuwi         | LapBook SE                  | [c144d3a1bc](https://linux-hardware.org/?probe=c144d3a1bc) | May 24, 2020 |
| Lenovo        | V145-15AST 81MT             | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| Dell          | Vostro 5490                 | [9000fa541e](https://linux-hardware.org/?probe=9000fa541e) | May 18, 2020 |
| Dell          | Latitude E5420              | [5519dbffbc](https://linux-hardware.org/?probe=5519dbffbc) | May 18, 2020 |
| Lenovo        | ThinkPad T520 424329U       | [bf1c52908b](https://linux-hardware.org/?probe=bf1c52908b) | May 16, 2020 |
| System76      | Galago Pro                  | [3ae6d02922](https://linux-hardware.org/?probe=3ae6d02922) | May 14, 2020 |
| HP            | EliteBook 8560w             | [f05f9404d0](https://linux-hardware.org/?probe=f05f9404d0) | May 11, 2020 |
| Gigabyte      | P15FV7                      | [a7031c2684](https://linux-hardware.org/?probe=a7031c2684) | May 09, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [702d00f33c](https://linux-hardware.org/?probe=702d00f33c) | May 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6f82171699](https://linux-hardware.org/?probe=6f82171699) | May 06, 2020 |
| Dell          | Latitude E7240              | [6f9d4efc51](https://linux-hardware.org/?probe=6f9d4efc51) | May 06, 2020 |
| Dell          | Latitude E7240              | [9e5819a0bc](https://linux-hardware.org/?probe=9e5819a0bc) | May 06, 2020 |
| Acer          | Okinawa                     | [9e22849a3a](https://linux-hardware.org/?probe=9e22849a3a) | May 03, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e356fece67](https://linux-hardware.org/?probe=e356fece67) | May 01, 2020 |
| Dell          | XPS M1530                   | [ef2ddf50e9](https://linux-hardware.org/?probe=ef2ddf50e9) | Apr 28, 2020 |
| Dell          | XPS M1530                   | [9d8053a9f5](https://linux-hardware.org/?probe=9d8053a9f5) | Apr 28, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [e6010acabe](https://linux-hardware.org/?probe=e6010acabe) | Apr 28, 2020 |
| Dell          | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Dell          | Latitude E5570              | [4c46b3c18d](https://linux-hardware.org/?probe=4c46b3c18d) | Apr 27, 2020 |
| Dell          | XPS 13 9300                 | [9b6c98e396](https://linux-hardware.org/?probe=9b6c98e396) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [0d9716a2e8](https://linux-hardware.org/?probe=0d9716a2e8) | Apr 26, 2020 |
| Dell          | XPS 13 7390                 | [951197ee19](https://linux-hardware.org/?probe=951197ee19) | Apr 25, 2020 |
| Dell          | Inspiron 15-3552            | [64015bca38](https://linux-hardware.org/?probe=64015bca38) | Apr 24, 2020 |
| Acer          | Aspire 7741                 | [85a10d5a0c](https://linux-hardware.org/?probe=85a10d5a0c) | Apr 24, 2020 |
| Dell          | XPS M1530                   | [0d21d60816](https://linux-hardware.org/?probe=0d21d60816) | Apr 22, 2020 |
| HP            | Presario F500 (GH835EA#A... | [9e0244765a](https://linux-hardware.org/?probe=9e0244765a) | Apr 21, 2020 |
| Medion        | Erazer X7843 MD99945        | [f63ebecfac](https://linux-hardware.org/?probe=f63ebecfac) | Apr 20, 2020 |
| Medion        | Erazer X7843 MD99945        | [caa46f1899](https://linux-hardware.org/?probe=caa46f1899) | Apr 20, 2020 |
| Dell          | Latitude E5450              | [a0de4692f3](https://linux-hardware.org/?probe=a0de4692f3) | Apr 12, 2020 |
| Dell          | Latitude E5450              | [b934bac9f3](https://linux-hardware.org/?probe=b934bac9f3) | Apr 12, 2020 |
| Apple         | MacBook6,1                  | [7eae555356](https://linux-hardware.org/?probe=7eae555356) | Apr 11, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [75cee4eeef](https://linux-hardware.org/?probe=75cee4eeef) | Apr 08, 2020 |
| eMachines     | E627                        | [395c0dace2](https://linux-hardware.org/?probe=395c0dace2) | Apr 07, 2020 |
| Dell          | XPS M1530                   | [daf947b1f0](https://linux-hardware.org/?probe=daf947b1f0) | Apr 07, 2020 |
| HP            | Pavilion dv6                | [5ae586911d](https://linux-hardware.org/?probe=5ae586911d) | Apr 05, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4151ed01a0](https://linux-hardware.org/?probe=4151ed01a0) | Apr 01, 2020 |
| HP            | EliteBook 2560p             | [1b7dfeda09](https://linux-hardware.org/?probe=1b7dfeda09) | Mar 30, 2020 |
| HP            | EliteBook 2560p             | [c32ad7e810](https://linux-hardware.org/?probe=c32ad7e810) | Mar 30, 2020 |
| ASUSTek       | X550CC                      | [9d50122997](https://linux-hardware.org/?probe=9d50122997) | Mar 30, 2020 |
| Lenovo        | ThinkPad X260 20F5S13K00    | [b2b7dfbc87](https://linux-hardware.org/?probe=b2b7dfbc87) | Mar 29, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ec4f08053a](https://linux-hardware.org/?probe=ec4f08053a) | Mar 23, 2020 |
| Dell          | Inspiron 13-5378            | [087223b15f](https://linux-hardware.org/?probe=087223b15f) | Mar 20, 2020 |
| Dell          | Inspiron 13-5378            | [9225b58c75](https://linux-hardware.org/?probe=9225b58c75) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [1287493f4e](https://linux-hardware.org/?probe=1287493f4e) | Mar 18, 2020 |
| HP            | EliteBook 840 G6            | [989982faa3](https://linux-hardware.org/?probe=989982faa3) | Mar 18, 2020 |
| Dell          | Precision M6300             | [6e9681a74e](https://linux-hardware.org/?probe=6e9681a74e) | Feb 18, 2020 |
| Dell          | Precision M6300             | [e45c0c7fc9](https://linux-hardware.org/?probe=e45c0c7fc9) | Feb 18, 2020 |
| Dell          | Inspiron 13-5378            | [46dd15e54f](https://linux-hardware.org/?probe=46dd15e54f) | Feb 18, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [b7a710c050](https://linux-hardware.org/?probe=b7a710c050) | Feb 10, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | E402BA                      | [ef0178479b](https://linux-hardware.org/?probe=ef0178479b) | Feb 08, 2020 |
| Lenovo        | ThinkPad X250 20CLS3ST01    | [51d20a3d12](https://linux-hardware.org/?probe=51d20a3d12) | Feb 06, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [917f6c18a4](https://linux-hardware.org/?probe=917f6c18a4) | Feb 05, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8143d2c859](https://linux-hardware.org/?probe=8143d2c859) | Dec 23, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [0f6f830f1b](https://linux-hardware.org/?probe=0f6f830f1b) | Dec 21, 2019 |
| Acer          | Aspire 8930                 | [3bd04b5cd7](https://linux-hardware.org/?probe=3bd04b5cd7) | Dec 09, 2019 |
| Lenovo        | ThinkPad T410 2539W4Y       | [009c5c142e](https://linux-hardware.org/?probe=009c5c142e) | Dec 06, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [706aee4776](https://linux-hardware.org/?probe=706aee4776) | Dec 04, 2019 |
| Apple         | MacBookPro5,2               | [3b3fd20d67](https://linux-hardware.org/?probe=3b3fd20d67) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [4918587a5c](https://linux-hardware.org/?probe=4918587a5c) | Dec 01, 2019 |
| Apple         | MacBookPro5,2               | [0ef52aaec2](https://linux-hardware.org/?probe=0ef52aaec2) | Dec 01, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [187a7265f0](https://linux-hardware.org/?probe=187a7265f0) | Dec 01, 2019 |
| System76      | Galago Pro                  | [15393d43e8](https://linux-hardware.org/?probe=15393d43e8) | Nov 25, 2019 |
| Dell          | Latitude 7490               | [4c5f40f7f3](https://linux-hardware.org/?probe=4c5f40f7f3) | Oct 18, 2019 |
| System76      | Galago Pro                  | [463dd28c7d](https://linux-hardware.org/?probe=463dd28c7d) | Oct 17, 2019 |
| Acer          | Aspire 5736Z                | [5ba5b7d13a](https://linux-hardware.org/?probe=5ba5b7d13a) | Oct 17, 2019 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [a2da44ce3d](https://linux-hardware.org/?probe=a2da44ce3d) | Oct 15, 2019 |
| Alienware     | 17 R4                       | [fa39f4bdb4](https://linux-hardware.org/?probe=fa39f4bdb4) | Oct 04, 2019 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b17cca251b](https://linux-hardware.org/?probe=b17cca251b) | Sep 30, 2019 |
| System76      | Galago Pro                  | [8122dc5996](https://linux-hardware.org/?probe=8122dc5996) | Sep 25, 2019 |
| Alienware     | 17 R4                       | [5287c00902](https://linux-hardware.org/?probe=5287c00902) | Sep 15, 2019 |
| System76      | Galago Pro                  | [7c1dbad22c](https://linux-hardware.org/?probe=7c1dbad22c) | Sep 11, 2019 |
| Acer          | Aspire ES1-512              | [6b82a86df6](https://linux-hardware.org/?probe=6b82a86df6) | Sep 08, 2019 |
| Lenovo        | V145-15AST 81MT             | [e5fc9849a0](https://linux-hardware.org/?probe=e5fc9849a0) | Aug 30, 2019 |
| Acer          | Aspire ES1-512              | [11727f9491](https://linux-hardware.org/?probe=11727f9491) | Aug 19, 2019 |
| Acer          | Aspire ES1-512              | [6a08c4afd1](https://linux-hardware.org/?probe=6a08c4afd1) | Aug 17, 2019 |
| Toshiba       | Satellite L500              | [5819f81be3](https://linux-hardware.org/?probe=5819f81be3) | Aug 16, 2019 |
| Acer          | Aspire E1-572               | [96bf232f30](https://linux-hardware.org/?probe=96bf232f30) | Aug 03, 2019 |
| Advent        | Roma                        | [a7ec10f5ee](https://linux-hardware.org/?probe=a7ec10f5ee) | Jul 21, 2019 |
| System76      | Bonobo Extreme              | [aa49d07bb2](https://linux-hardware.org/?probe=aa49d07bb2) | Jul 05, 2019 |
| System76      | Bonobo Extreme              | [f867ec3a39](https://linux-hardware.org/?probe=f867ec3a39) | Jul 05, 2019 |
| Toshiba       | TECRA R850                  | [4398e73607](https://linux-hardware.org/?probe=4398e73607) | Jul 04, 2019 |
| HP            | Pavilion dv6                | [6cfff2060e](https://linux-hardware.org/?probe=6cfff2060e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [90df3b230e](https://linux-hardware.org/?probe=90df3b230e) | Jun 16, 2019 |
| HP            | Pavilion dv6                | [694239801c](https://linux-hardware.org/?probe=694239801c) | Jun 16, 2019 |
| Toshiba       | Satellite L500              | [7fcd49c923](https://linux-hardware.org/?probe=7fcd49c923) | Jun 08, 2019 |
| ASUSTek       | S550CA                      | [469e04e0d5](https://linux-hardware.org/?probe=469e04e0d5) | May 26, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [a151a65fee](https://linux-hardware.org/?probe=a151a65fee) | May 21, 2019 |
| Lenovo        | ThinkPad T420 4236RN1       | [ba564750a2](https://linux-hardware.org/?probe=ba564750a2) | May 21, 2019 |
| ASUSTek       | K53U                        | [24a0045ecc](https://linux-hardware.org/?probe=24a0045ecc) | May 18, 2019 |
| ASUSTek       | K53U                        | [0f7bf61a9d](https://linux-hardware.org/?probe=0f7bf61a9d) | May 17, 2019 |
| ASUSTek       | S550CA                      | [afe6d9bfe2](https://linux-hardware.org/?probe=afe6d9bfe2) | Apr 28, 2019 |
| ASUSTek       | T100TA                      | [5025b4af94](https://linux-hardware.org/?probe=5025b4af94) | Apr 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S1G40L    | [47b05c165f](https://linux-hardware.org/?probe=47b05c165f) | Apr 24, 2019 |
| Toshiba       | Satellite L50-C             | [ffca1399e5](https://linux-hardware.org/?probe=ffca1399e5) | Apr 17, 2019 |
| Dell          | Inspiron ME051              | [6d096d9aa6](https://linux-hardware.org/?probe=6d096d9aa6) | Mar 30, 2019 |
| Dell          | Inspiron ME051              | [a41940bc7f](https://linux-hardware.org/?probe=a41940bc7f) | Mar 30, 2019 |
| eMachines     | eM350                       | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Dell          | Latitude E6400              | [75df21c3fd](https://linux-hardware.org/?probe=75df21c3fd) | Jan 25, 2019 |
| Toshiba       | Satellite Pro C660          | [9b641633c5](https://linux-hardware.org/?probe=9b641633c5) | Nov 17, 2018 |
| Acer          | Swift SF114-31              | [96142e3044](https://linux-hardware.org/?probe=96142e3044) | Nov 01, 2018 |
| Dell          | Latitude E6230              | [889c4720de](https://linux-hardware.org/?probe=889c4720de) | Mar 31, 2018 |
| Acer          | Aspire E5-575G              | [5d4b293327](https://linux-hardware.org/?probe=5d4b293327) | Feb 07, 2018 |
| Dell          | Latitude E6230              | [70a07251da](https://linux-hardware.org/?probe=70a07251da) | Oct 21, 2017 |
| Dell          | Latitude D620               | [6652d3973b](https://linux-hardware.org/?probe=6652d3973b) | Sep 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 45        | 15.15%  |
| Ubuntu 18.04       | 28        | 9.43%   |
| Ubuntu 22.04       | 10        | 3.37%   |
| Debian 11          | 9         | 3.03%   |
| Fedora 36          | 7         | 2.36%   |
| Debian 10          | 7         | 2.36%   |
| Zorin 16           | 6         | 2.02%   |
| OpenMandriva 4.2   | 6         | 2.02%   |
| Ubuntu 19.10       | 5         | 1.68%   |
| Manjaro            | 5         | 1.68%   |
| Linux Mint 20.2    | 5         | 1.68%   |
| KDE neon 20.04     | 5         | 1.68%   |
| ArcoLinux Rolling  | 5         | 1.68%   |
| Ubuntu 21.10       | 4         | 1.35%   |
| Ubuntu 19.04       | 4         | 1.35%   |
| Pop!_OS 22.04      | 4         | 1.35%   |
| Pop!_OS 21.10      | 4         | 1.35%   |
| Pop!_OS 20.04      | 4         | 1.35%   |
| Lubuntu 20.04      | 4         | 1.35%   |
| Linux Mint 20.3    | 4         | 1.35%   |
| Linux Mint 20      | 4         | 1.35%   |
| Linux Mint 19.3    | 4         | 1.35%   |
| Fedora 34          | 4         | 1.35%   |
| Debian Unstable    | 4         | 1.35%   |
| BlackPanther 18.1  | 4         | 1.35%   |
| Arch               | 4         | 1.35%   |
| Zorin 15           | 3         | 1.01%   |
| ROSA R10           | 3         | 1.01%   |
| Pop!_OS 20.10      | 3         | 1.01%   |
| Linux Mint 21      | 3         | 1.01%   |
| Linux Mint 19.2    | 3         | 1.01%   |
| Kubuntu 20.04      | 3         | 1.01%   |
| Fedora 33          | 3         | 1.01%   |
| Arch Rolling       | 3         | 1.01%   |
| Ubuntu Unity 16.04 | 2         | 0.67%   |
| Ubuntu MATE 20.04  | 2         | 0.67%   |
| Ubuntu 16.04       | 2         | 0.67%   |
| ROSA R9            | 2         | 0.67%   |
| Pop!_OS 21.04      | 2         | 0.67%   |
| Manjaro 21.0.7     | 2         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 99        | 34.86%  |
| Linux Mint    | 27        | 9.51%   |
| Debian        | 20        | 7.04%   |
| Fedora        | 19        | 6.69%   |
| Pop!_OS       | 17        | 5.99%   |
| Manjaro       | 12        | 4.23%   |
| Kubuntu       | 11        | 3.87%   |
| Zorin         | 9         | 3.17%   |
| OpenMandriva  | 7         | 2.46%   |
| Arch          | 7         | 2.46%   |
| ROSA          | 6         | 2.11%   |
| Lubuntu       | 6         | 2.11%   |
| KDE neon      | 5         | 1.76%   |
| ArcoLinux     | 5         | 1.76%   |
| Elementary    | 4         | 1.41%   |
| BlackPanther  | 4         | 1.41%   |
| Ubuntu Unity  | 3         | 1.06%   |
| Ubuntu MATE   | 3         | 1.06%   |
| openSUSE      | 3         | 1.06%   |
| Endless       | 3         | 1.06%   |
| Xubuntu       | 2         | 0.7%    |
| Ubuntu Budgie | 2         | 0.7%    |
| LMDE          | 2         | 0.7%    |
| Clear Linux   | 2         | 0.7%    |
| CentOS        | 2         | 0.7%    |
| SteamOS       | 1         | 0.35%   |
| RHEL          | 1         | 0.35%   |
| Peppermint    | 1         | 0.35%   |
| Chrome OS     | 1         | 0.35%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.3.0-46-generic         | 8         | 2.48%   |
| 5.4.0-42-generic         | 6         | 1.86%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.86%   |
| 5.4.0-52-generic         | 5         | 1.55%   |
| 5.15.0-52-generic        | 5         | 1.55%   |
| 5.15.0-46-generic        | 5         | 1.55%   |
| 5.4.0-26-generic         | 4         | 1.24%   |
| 5.15.0-48-generic        | 4         | 1.24%   |
| 5.4.0-31-generic         | 3         | 0.93%   |
| 5.4.0-29-generic         | 3         | 0.93%   |
| 5.15.0-40-generic        | 3         | 0.93%   |
| 5.11.0-27-generic        | 3         | 0.93%   |
| 5.10.0-14-amd64          | 3         | 0.93%   |
| 4.19.0-9-amd64           | 3         | 0.93%   |
| 4.18.16-desktop-1bP      | 3         | 0.93%   |
| 5.8.0-7625-generic       | 2         | 0.62%   |
| 5.8.0-53-generic         | 2         | 0.62%   |
| 5.8.0-43-generic         | 2         | 0.62%   |
| 5.4.0-91-generic         | 2         | 0.62%   |
| 5.4.0-80-generic         | 2         | 0.62%   |
| 5.4.0-7634-generic       | 2         | 0.62%   |
| 5.4.0-73-generic         | 2         | 0.62%   |
| 5.4.0-72-generic         | 2         | 0.62%   |
| 5.4.0-65-generic         | 2         | 0.62%   |
| 5.4.0-62-generic         | 2         | 0.62%   |
| 5.4.0-58-generic         | 2         | 0.62%   |
| 5.4.0-56-generic         | 2         | 0.62%   |
| 5.4.0-54-generic         | 2         | 0.62%   |
| 5.4.0-53-generic         | 2         | 0.62%   |
| 5.4.0-40-generic         | 2         | 0.62%   |
| 5.3.0-40-generic         | 2         | 0.62%   |
| 5.3.0-18-generic         | 2         | 0.62%   |
| 5.19.0-76051900-generic  | 2         | 0.62%   |
| 5.18.17-200.fc36.x86_64  | 2         | 0.62%   |
| 5.15.0-50-generic        | 2         | 0.62%   |
| 5.13.0-40-generic        | 2         | 0.62%   |
| 5.13.0-21-generic        | 2         | 0.62%   |
| 5.11.0-41-generic        | 2         | 0.62%   |
| 5.11.0-40-generic        | 2         | 0.62%   |
| 5.11.0-38-generic        | 2         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 67        | 22.56%  |
| 4.15.0  | 23        | 7.74%   |
| 5.15.0  | 21        | 7.07%   |
| 5.3.0   | 17        | 5.72%   |
| 5.11.0  | 17        | 5.72%   |
| 5.8.0   | 15        | 5.05%   |
| 5.13.0  | 11        | 3.7%    |
| 5.10.0  | 10        | 3.37%   |
| 5.0.0   | 8         | 2.69%   |
| 4.19.0  | 8         | 2.69%   |
| 5.10.14 | 6         | 2.02%   |
| 4.18.0  | 5         | 1.68%   |
| 5.19.0  | 3         | 1.01%   |
| 4.18.16 | 3         | 1.01%   |
| 5.7.9   | 2         | 0.67%   |
| 5.6.7   | 2         | 0.67%   |
| 5.6.15  | 2         | 0.67%   |
| 5.6.0   | 2         | 0.67%   |
| 5.19.1  | 2         | 0.67%   |
| 5.18.17 | 2         | 0.67%   |
| 5.18.0  | 2         | 0.67%   |
| 5.17.5  | 2         | 0.67%   |
| 5.16.11 | 2         | 0.67%   |
| 5.10.42 | 2         | 0.67%   |
| 4.9.60  | 2         | 0.67%   |
| 4.9.41  | 2         | 0.67%   |
| 4.12.14 | 2         | 0.67%   |
| 3.10.0  | 2         | 0.67%   |
| 6.0.5   | 1         | 0.34%   |
| 6.0.2   | 1         | 0.34%   |
| 6.0.10  | 1         | 0.34%   |
| 5.9.16  | 1         | 0.34%   |
| 5.9.11  | 1         | 0.34%   |
| 5.9.1   | 1         | 0.34%   |
| 5.9.0   | 1         | 0.34%   |
| 5.8.18  | 1         | 0.34%   |
| 5.8.14  | 1         | 0.34%   |
| 5.7.7   | 1         | 0.34%   |
| 5.7.12  | 1         | 0.34%   |
| 5.6.14  | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 70        | 23.81%  |
| 5.15    | 26        | 8.84%   |
| 4.15    | 23        | 7.82%   |
| 5.10    | 22        | 7.48%   |
| 5.3     | 18        | 6.12%   |
| 5.8     | 17        | 5.78%   |
| 5.11    | 17        | 5.78%   |
| 5.13    | 13        | 4.42%   |
| 4.19    | 9         | 3.06%   |
| 5.19    | 8         | 2.72%   |
| 5.0     | 8         | 2.72%   |
| 4.18    | 8         | 2.72%   |
| 5.6     | 7         | 2.38%   |
| 5.18    | 6         | 2.04%   |
| 5.17    | 6         | 2.04%   |
| 4.9     | 5         | 1.7%    |
| 5.9     | 4         | 1.36%   |
| 5.7     | 4         | 1.36%   |
| 5.14    | 4         | 1.36%   |
| 5.12    | 4         | 1.36%   |
| 6.0     | 3         | 1.02%   |
| 5.16    | 3         | 1.02%   |
| 4.12    | 2         | 0.68%   |
| 3.10    | 2         | 0.68%   |
| 5.2     | 1         | 0.34%   |
| 4.4     | 1         | 0.34%   |
| 4.14    | 1         | 0.34%   |
| 4.13    | 1         | 0.34%   |
| 4.10    | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 262       | 95.62%  |
| i686   | 12        | 4.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 134       | 46.37%  |
| Unknown         | 40        | 13.84%  |
| KDE5            | 36        | 12.46%  |
| X-Cinnamon      | 18        | 6.23%   |
| XFCE            | 16        | 5.54%   |
| KDE             | 11        | 3.81%   |
| LXQt            | 6         | 2.08%   |
| MATE            | 5         | 1.73%   |
| Cinnamon        | 5         | 1.73%   |
| Pantheon        | 4         | 1.38%   |
| i3              | 4         | 1.38%   |
| Unity           | 3         | 1.04%   |
| KDE4            | 2         | 0.69%   |
| GNOME Classic   | 2         | 0.69%   |
| Budgie          | 2         | 0.69%   |
| GNOME Flashback | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 223       | 79.93%  |
| Wayland | 31        | 11.11%  |
| Unknown | 22        | 7.89%   |
| Tty     | 3         | 1.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 154       | 54.61%  |
| GDM     | 39        | 13.83%  |
| SDDM    | 32        | 11.35%  |
| LightDM | 24        | 8.51%   |
| GDM3    | 19        | 6.74%   |
| TDM     | 12        | 4.26%   |
| KDM     | 2         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_IE   | 137       | 48.41%  |
| en_US   | 44        | 15.55%  |
| en_GB   | 42        | 14.84%  |
| Unknown | 35        | 12.37%  |
| pl_PL   | 10        | 3.53%   |
| en_CA   | 2         | 0.71%   |
| bg_BG   | 2         | 0.71%   |
| zh_CN   | 1         | 0.35%   |
| pt_PT   | 1         | 0.35%   |
| it_IT   | 1         | 0.35%   |
| ga_IE   | 1         | 0.35%   |
| fr_FR   | 1         | 0.35%   |
| fr_BE   | 1         | 0.35%   |
| es_ES   | 1         | 0.35%   |
| en_ZA   | 1         | 0.35%   |
| en_IN   | 1         | 0.35%   |
| en_DE   | 1         | 0.35%   |
| C       | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 144       | 51.8%   |
| BIOS | 134       | 48.2%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ext4                | 218       | 78.42%  |
| Btrfs               | 22        | 7.91%   |
| Overlay             | 16        | 5.76%   |
| Unknown             | 14        | 5.04%   |
| Xfs                 | 4         | 1.44%   |
| Zfs                 | 3         | 1.08%   |
| Fuse.fuse-overlayfs | 1         | 0.36%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 164       | 58.78%  |
| GPT     | 86        | 30.82%  |
| MBR     | 29        | 10.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 245       | 88.77%  |
| Yes       | 31        | 11.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 210       | 75.81%  |
| Yes       | 67        | 24.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 67        | 24.45%  |
| Dell                | 60        | 21.9%   |
| Hewlett-Packard     | 37        | 13.5%   |
| ASUSTek Computer    | 20        | 7.3%    |
| Acer                | 20        | 7.3%    |
| Toshiba             | 10        | 3.65%   |
| Apple               | 9         | 3.28%   |
| Samsung Electronics | 5         | 1.82%   |
| TUXEDO              | 4         | 1.46%   |
| PC Specialist       | 4         | 1.46%   |
| Medion              | 4         | 1.46%   |
| Timi                | 3         | 1.09%   |
| Notebook            | 3         | 1.09%   |
| MSI                 | 3         | 1.09%   |
| Chuwi               | 3         | 1.09%   |
| System76            | 2         | 0.73%   |
| HUAWEI              | 2         | 0.73%   |
| Fujitsu Siemens     | 2         | 0.73%   |
| Entroware           | 2         | 0.73%   |
| eMachines           | 2         | 0.73%   |
| Valve               | 1         | 0.36%   |
| Sony                | 1         | 0.36%   |
| SLIMBOOK            | 1         | 0.36%   |
| Schenker            | 1         | 0.36%   |
| Packard Bell        | 1         | 0.36%   |
| Microtech           | 1         | 0.36%   |
| Jumper              | 1         | 0.36%   |
| Gigabyte Technology | 1         | 0.36%   |
| Framework           | 1         | 0.36%   |
| AVITA               | 1         | 0.36%   |
| Alienware           | 1         | 0.36%   |
| Advent              | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Lenovo V145-15AST 81MT            | 3         | 1.09%   |
| TUXEDO Pulse 15 Gen1              | 2         | 0.73%   |
| Lenovo ThinkPad X1 Carbon 3443CTO | 2         | 0.73%   |
| Lenovo IdeaPad 510-15ISK 80SR     | 2         | 0.73%   |
| HP Pavilion g6                    | 2         | 0.73%   |
| HP Notebook                       | 2         | 0.73%   |
| Dell XPS 9320                     | 2         | 0.73%   |
| Dell XPS 13 9310                  | 2         | 0.73%   |
| Dell XPS 13 9300                  | 2         | 0.73%   |
| Dell XPS 13 7390                  | 2         | 0.73%   |
| Dell Precision 5550               | 2         | 0.73%   |
| Dell Latitude E6230               | 2         | 0.73%   |
| Dell Inspiron 13-5378             | 2         | 0.73%   |
| Apple MacBook6,1                  | 2         | 0.73%   |
| Acer Aspire E5-575G               | 2         | 0.73%   |
| Valve Jupiter                     | 1         | 0.36%   |
| TUXEDO InfinityBook Pro 15 v5     | 1         | 0.36%   |
| TUXEDO InfinityBook Pro 14 Gen6   | 1         | 0.36%   |
| Toshiba TECRA R850                | 1         | 0.36%   |
| Toshiba TECRA M4                  | 1         | 0.36%   |
| Toshiba Satellite Pro R50-B       | 1         | 0.36%   |
| Toshiba Satellite Pro C660        | 1         | 0.36%   |
| Toshiba Satellite L500            | 1         | 0.36%   |
| Toshiba Satellite L50-C           | 1         | 0.36%   |
| Toshiba Satellite L50-B           | 1         | 0.36%   |
| Toshiba Satellite C50-B           | 1         | 0.36%   |
| Toshiba Satellite A300            | 1         | 0.36%   |
| Toshiba PORTEGE R830              | 1         | 0.36%   |
| Timi TM1709                       | 1         | 0.36%   |
| Timi TM1703                       | 1         | 0.36%   |
| Timi TM1607                       | 1         | 0.36%   |
| System76 Galago Pro               | 1         | 0.36%   |
| System76 Bonobo Extreme           | 1         | 0.36%   |
| Sony VPCCB35FG                    | 1         | 0.36%   |
| SLIMBOOK PROX15                   | 1         | 0.36%   |
| Schenker XMG NEO (TGL/M21)        | 1         | 0.36%   |
| Samsung RC420/RC520/RC720         | 1         | 0.36%   |
| Samsung N150/N210/N220            | 1         | 0.36%   |
| Samsung 935XDB                    | 1         | 0.36%   |
| Samsung 550P5C/550P7C             | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 37        | 13.5%   |
| Dell Latitude         | 26        | 9.49%   |
| Acer Aspire           | 15        | 5.47%   |
| Lenovo IdeaPad        | 14        | 5.11%   |
| Dell XPS              | 12        | 4.38%   |
| Dell Inspiron         | 12        | 4.38%   |
| HP EliteBook          | 10        | 3.65%   |
| HP Pavilion           | 9         | 3.28%   |
| Toshiba Satellite     | 7         | 2.55%   |
| Dell Precision        | 6         | 2.19%   |
| Lenovo V145-15AST     | 3         | 1.09%   |
| Lenovo ThinkBook      | 3         | 1.09%   |
| HP Presario           | 3         | 1.09%   |
| HP Laptop             | 3         | 1.09%   |
| Apple MacBookPro5     | 3         | 1.09%   |
| TUXEDO Pulse          | 2         | 0.73%   |
| TUXEDO InfinityBook   | 2         | 0.73%   |
| Toshiba TECRA         | 2         | 0.73%   |
| HP ProBook            | 2         | 0.73%   |
| HP Notebook           | 2         | 0.73%   |
| Fujitsu Siemens AMILO | 2         | 0.73%   |
| Dell Vostro           | 2         | 0.73%   |
| ASUS ZenBook          | 2         | 0.73%   |
| ASUS TUF              | 2         | 0.73%   |
| ASUS ROG              | 2         | 0.73%   |
| Apple MacBook6        | 2         | 0.73%   |
| Valve Jupiter         | 1         | 0.36%   |
| Toshiba PORTEGE       | 1         | 0.36%   |
| Timi TM1709           | 1         | 0.36%   |
| Timi TM1703           | 1         | 0.36%   |
| Timi TM1607           | 1         | 0.36%   |
| System76 Galago       | 1         | 0.36%   |
| System76 Bonobo       | 1         | 0.36%   |
| Sony VPCCB35FG        | 1         | 0.36%   |
| SLIMBOOK PROX15       | 1         | 0.36%   |
| Schenker XMG          | 1         | 0.36%   |
| Samsung RC420         | 1         | 0.36%   |
| Samsung N150          | 1         | 0.36%   |
| Samsung 935XDB        | 1         | 0.36%   |
| Samsung 550P5C        | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 30        | 10.95%  |
| 2019 | 29        | 10.58%  |
| 2017 | 22        | 8.03%   |
| 2013 | 22        | 8.03%   |
| 2021 | 19        | 6.93%   |
| 2012 | 19        | 6.93%   |
| 2011 | 19        | 6.93%   |
| 2018 | 18        | 6.57%   |
| 2016 | 17        | 6.2%    |
| 2015 | 14        | 5.11%   |
| 2009 | 14        | 5.11%   |
| 2010 | 12        | 4.38%   |
| 2008 | 12        | 4.38%   |
| 2014 | 9         | 3.28%   |
| 2007 | 7         | 2.55%   |
| 2022 | 6         | 2.19%   |
| 2006 | 3         | 1.09%   |
| 2005 | 1         | 0.36%   |
| 2003 | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 274       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 241       | 86.69%  |
| Enabled  | 37        | 13.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 274       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 83        | 29.86%  |
| 3.01-4.0    | 54        | 19.42%  |
| 16.01-24.0  | 51        | 18.35%  |
| 8.01-16.0   | 41        | 14.75%  |
| 32.01-64.0  | 25        | 8.99%   |
| 1.01-2.0    | 11        | 3.96%   |
| 2.01-3.0    | 5         | 1.8%    |
| 64.01-256.0 | 3         | 1.08%   |
| 24.01-32.0  | 2         | 0.72%   |
| 0.51-1.0    | 2         | 0.72%   |
| 0.01-0.5    | 1         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 95        | 31.56%  |
| 2.01-3.0   | 75        | 24.92%  |
| 3.01-4.0   | 54        | 17.94%  |
| 4.01-8.0   | 42        | 13.95%  |
| 0.51-1.0   | 22        | 7.31%   |
| 8.01-16.0  | 8         | 2.66%   |
| 16.01-24.0 | 3         | 1%      |
| 0.01-0.5   | 2         | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 209       | 73.59%  |
| 2      | 63        | 22.18%  |
| 3      | 10        | 3.52%   |
| 0      | 2         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 63.54%  |
| Yes       | 101       | 36.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 221       | 80.36%  |
| No        | 54        | 19.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 271       | 98.55%  |
| No        | 4         | 1.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 76.09%  |
| No        | 66        | 23.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ireland | 274       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dublin              | 159       | 56.79%  |
| Cork                | 18        | 6.43%   |
| Galway              | 12        | 4.29%   |
| Limerick            | 9         | 3.21%   |
| Naas                | 7         | 2.5%    |
| Drogheda            | 6         | 2.14%   |
| Ennis               | 5         | 1.79%   |
| Navan               | 4         | 1.43%   |
| Enniscorthy         | 3         | 1.07%   |
| Dún Laoghaire      | 3         | 1.07%   |
| Wexford             | 2         | 0.71%   |
| Westport            | 2         | 0.71%   |
| Waterford           | 2         | 0.71%   |
| Portlaoise          | 2         | 0.71%   |
| Nenagh              | 2         | 0.71%   |
| Loughrea            | 2         | 0.71%   |
| Kilkenny            | 2         | 0.71%   |
| Clonakilty          | 2         | 0.71%   |
| Clane               | 2         | 0.71%   |
| Athlone             | 2         | 0.71%   |
| Youghal             | 1         | 0.36%   |
| Wicklow             | 1         | 0.36%   |
| Tullow              | 1         | 0.36%   |
| Tullamore           | 1         | 0.36%   |
| Tobercurry          | 1         | 0.36%   |
| Sligo               | 1         | 0.36%   |
| Slane               | 1         | 0.36%   |
| Scarriff            | 1         | 0.36%   |
| Santry              | 1         | 0.36%   |
| Newmarket on Fergus | 1         | 0.36%   |
| Newcastle           | 1         | 0.36%   |
| New Ross            | 1         | 0.36%   |
| Midleton            | 1         | 0.36%   |
| Maynooth            | 1         | 0.36%   |
| Mallow              | 1         | 0.36%   |
| Letterkenny         | 1         | 0.36%   |
| Leixlip             | 1         | 0.36%   |
| Kilrush             | 1         | 0.36%   |
| Killorglin          | 1         | 0.36%   |
| Kenmare             | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 68        | 94     | 20.12%  |
| WDC                         | 44        | 52     | 13.02%  |
| Seagate                     | 28        | 36     | 8.28%   |
| Toshiba                     | 25        | 29     | 7.4%    |
| Unknown                     | 24        | 33     | 7.1%    |
| SanDisk                     | 24        | 24     | 7.1%    |
| Hitachi                     | 19        | 22     | 5.62%   |
| Crucial                     | 15        | 22     | 4.44%   |
| Micron Technology           | 10        | 11     | 2.96%   |
| Intel                       | 10        | 13     | 2.96%   |
| Kingston                    | 9         | 11     | 2.66%   |
| HGST                        | 9         | 10     | 2.66%   |
| SK hynix                    | 8         | 8      | 2.37%   |
| Fujitsu                     | 6         | 7      | 1.78%   |
| PNY                         | 3         | 3      | 0.89%   |
| KIOXIA                      | 3         | 3      | 0.89%   |
| Silicon Motion              | 2         | 3      | 0.59%   |
| LITEONIT                    | 2         | 2      | 0.59%   |
| KingSpec                    | 2         | 2      | 0.59%   |
| Apple                       | 2         | 2      | 0.59%   |
| A-DATA Technology           | 2         | 2      | 0.59%   |
| Zheino                      | 1         | 1      | 0.3%    |
| W800S                       | 1         | 2      | 0.3%    |
| Verbatim                    | 1         | 1      | 0.3%    |
| Union Memory                | 1         | 1      | 0.3%    |
| ShanDianZhe                 | 1         | 1      | 0.3%    |
| SABRENT                     | 1         | 2      | 0.3%    |
| QNAP                        | 1         | 1      | 0.3%    |
| Plextor                     | 1         | 1      | 0.3%    |
| Phison                      | 1         | 1      | 0.3%    |
| OCZ                         | 1         | 1      | 0.3%    |
| Micron/Crucial Technology   | 1         | 1      | 0.3%    |
| LITEON                      | 1         | 1      | 0.3%    |
| LaCie                       | 1         | 1      | 0.3%    |
| Kingston Technology Company | 1         | 1      | 0.3%    |
| Integral                    | 1         | 1      | 0.3%    |
| GOODRAM                     | 1         | 1      | 0.3%    |
| FORESEE                     | 1         | 1      | 0.3%    |
| faspeed                     | 1         | 1      | 0.3%    |
| Emtec                       | 1         | 2      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB           | 6         | 1.7%    |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.42%   |
| Unknown MMC Card  64GB                 | 4         | 1.14%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 1.14%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 4         | 1.14%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 1.14%   |
| Crucial CT1000MX500SSD1 1TB            | 4         | 1.14%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 3         | 0.85%   |
| Unknown MMC Card  32GB                 | 3         | 0.85%   |
| Samsung SSD 860 EVO 500GB              | 3         | 0.85%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.85%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.85%   |
| Samsung NVMe SSD Drive 500GB           | 3         | 0.85%   |
| PNY CS900 120GB SSD                    | 3         | 0.85%   |
| Hitachi HTS723232A7A364 320GB          | 3         | 0.85%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.85%   |
| HGST HTS545050A7E680 500GB             | 3         | 0.85%   |
| Crucial M4-CT128M4SSD2 128GB           | 3         | 0.85%   |
| WDC WDS100T1B0A-00H9H0 1TB SSD         | 2         | 0.57%   |
| WDC WD10JPVX-00JC3T0 1TB               | 2         | 0.57%   |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 0.57%   |
| Unknown SL16G  16GB                    | 2         | 0.57%   |
| Unknown HBG4a2  32GB                   | 2         | 0.57%   |
| Toshiba MQ04ABF100 1TB                 | 2         | 0.57%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.57%   |
| SK hynix NVMe SSD Drive 2TB            | 2         | 0.57%   |
| Seagate ST9500420ASG 500GB             | 2         | 0.57%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 2         | 0.57%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.57%   |
| Seagate ST500LM000-1EJ162 500GB        | 2         | 0.57%   |
| Seagate ST2000LM003 HN-M201RAD 2TB     | 2         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.57%   |
| SanDisk X400 2.5 7MM 256GB SSD         | 2         | 0.57%   |
| SanDisk SD5SG2128G1052E 128GB SSD      | 2         | 0.57%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB         | 2         | 0.57%   |
| Samsung SSD 840 EVO 250GB              | 2         | 0.57%   |
| Samsung NVMe SSD Drive 250GB           | 2         | 0.57%   |
| Samsung MZVLB512HBJQ-000L7 512GB       | 2         | 0.57%   |
| Micron 2300 NVMe 512GB                 | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 32     | 25.89%  |
| Seagate             | 28        | 36     | 25%     |
| Hitachi             | 19        | 22     | 16.96%  |
| Toshiba             | 14        | 15     | 12.5%   |
| HGST                | 9         | 10     | 8.04%   |
| Fujitsu             | 6         | 7      | 5.36%   |
| Samsung Electronics | 3         | 4      | 2.68%   |
| SABRENT             | 1         | 2      | 0.89%   |
| QNAP                | 1         | 1      | 0.89%   |
| LaCie               | 1         | 1      | 0.89%   |
| Apple               | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 36     | 29.81%  |
| SanDisk             | 15        | 15     | 14.42%  |
| Crucial             | 14        | 21     | 13.46%  |
| Kingston            | 9         | 11     | 8.65%   |
| WDC                 | 5         | 8      | 4.81%   |
| Toshiba             | 3         | 5      | 2.88%   |
| PNY                 | 3         | 3      | 2.88%   |
| Micron Technology   | 2         | 2      | 1.92%   |
| LITEONIT            | 2         | 2      | 1.92%   |
| KingSpec            | 2         | 2      | 1.92%   |
| Intel               | 2         | 2      | 1.92%   |
| Zheino              | 1         | 1      | 0.96%   |
| W800S               | 1         | 2      | 0.96%   |
| Verbatim            | 1         | 1      | 0.96%   |
| SK hynix            | 1         | 1      | 0.96%   |
| Plextor             | 1         | 1      | 0.96%   |
| OCZ                 | 1         | 1      | 0.96%   |
| LITEON              | 1         | 1      | 0.96%   |
| Integral            | 1         | 1      | 0.96%   |
| GOODRAM             | 1         | 1      | 0.96%   |
| FORESEE             | 1         | 1      | 0.96%   |
| faspeed             | 1         | 1      | 0.96%   |
| Emtec               | 1         | 2      | 0.96%   |
| Dogfish             | 1         | 1      | 0.96%   |
| China               | 1         | 5      | 0.96%   |
| Apple               | 1         | 1      | 0.96%   |
| A-DATA Technology   | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 105       | 131    | 32.81%  |
| SSD     | 96        | 129    | 30%     |
| NVMe    | 92        | 123    | 28.75%  |
| MMC     | 23        | 32     | 7.19%   |
| Unknown | 4         | 4      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 187       | 256    | 60.91%  |
| NVMe | 92        | 123    | 29.97%  |
| MMC  | 23        | 32     | 7.49%   |
| SAS  | 5         | 8      | 1.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 135       | 176    | 67.84%  |
| 0.51-1.0   | 58        | 74     | 29.15%  |
| 1.01-2.0   | 3         | 6      | 1.51%   |
| 20.01-50.0 | 1         | 1      | 0.5%    |
| 3.01-4.0   | 1         | 1      | 0.5%    |
| 4.01-10.0  | 1         | 2      | 0.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 82        | 28.98%  |
| 251-500        | 78        | 27.56%  |
| 501-1000       | 33        | 11.66%  |
| 1-20           | 25        | 8.83%   |
| 51-100         | 25        | 8.83%   |
| 1001-2000      | 17        | 6.01%   |
| Unknown        | 10        | 3.53%   |
| 21-50          | 8         | 2.83%   |
| More than 3000 | 3         | 1.06%   |
| 2001-3000      | 2         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 118       | 39.33%  |
| 101-250        | 49        | 16.33%  |
| 21-50          | 47        | 15.67%  |
| 51-100         | 40        | 13.33%  |
| 251-500        | 20        | 6.67%   |
| 501-1000       | 11        | 3.67%   |
| Unknown        | 10        | 3.33%   |
| 1001-2000      | 4         | 1.33%   |
| More than 3000 | 1         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Hitachi HTS723232A7A364 320GB                  | 2         | 2      | 12.5%   |
| WDC WD2500BEVT-22A23T0 250GB                   | 1         | 1      | 6.25%   |
| Toshiba MQ01ABF050H 500GB                      | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 6.25%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 6.25%   |
| Seagate ST910021AS 100GB                       | 1         | 1      | 6.25%   |
| SanDisk SSD PLUS 240GB                         | 1         | 1      | 6.25%   |
| Samsung Electronics HM120JC 120GB              | 1         | 1      | 6.25%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 6.25%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 6.25%   |
| Hitachi HTS545025B9SA02 250GB                  | 1         | 2      | 6.25%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 6.25%   |
| Hitachi DK23CA-30 32GB                         | 1         | 1      | 6.25%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 6.25%   |
| Fujitsu MHJ2181AT 18GB                         | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 7      | 37.5%   |
| Toshiba             | 3         | 3      | 18.75%  |
| WDC                 | 1         | 1      | 6.25%   |
| Seagate             | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 6         | 7      | 42.86%  |
| Toshiba             | 3         | 3      | 21.43%  |
| WDC                 | 1         | 1      | 7.14%   |
| Seagate             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 15     | 84.62%  |
| SSD  | 2         | 2      | 15.38%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD1200BEVS-22UST0 120GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 175       | 266    | 60.55%  |
| Works    | 100       | 135    | 34.6%   |
| Malfunc  | 13        | 17     | 4.5%    |
| Failed   | 1         | 1      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 188       | 58.39%  |
| Samsung Electronics          | 36        | 11.18%  |
| AMD                          | 33        | 10.25%  |
| SanDisk                      | 20        | 6.21%   |
| Toshiba America Info Systems | 8         | 2.48%   |
| Nvidia                       | 8         | 2.48%   |
| Micron Technology            | 8         | 2.48%   |
| SK hynix                     | 7         | 2.17%   |
| KIOXIA                       | 3         | 0.93%   |
| Union Memory (Shenzhen)      | 2         | 0.62%   |
| Silicon Motion               | 2         | 0.62%   |
| Micron/Crucial Technology    | 2         | 0.62%   |
| Silicon Image                | 1         | 0.31%   |
| Phison Electronics           | 1         | 0.31%   |
| Kingston Technology Company  | 1         | 0.31%   |
| ADATA Technology             | 1         | 0.31%   |
| Adaptec                      | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 8.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 27        | 7.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 5.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 4.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 3.75%   |
| Samsung NVMe SSD Controller 980                                                | 10        | 2.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 10        | 2.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 2.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 2.59%   |
| Micron Non-Volatile memory controller                                          | 8         | 2.31%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 2.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 2.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 1.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 6         | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 1.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.44%   |
| Nvidia MCP79 AHCI Controller                                                   | 5         | 1.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 1.44%   |
| SanDisk PC SN520 NVMe SSD                                                      | 4         | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.15%   |
| Intel SSD 660P Series                                                          | 4         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.15%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 4         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.15%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 0.86%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.86%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.86%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.86%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.86%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 3         | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.86%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 192       | 58.01%  |
| NVMe | 93        | 28.1%   |
| RAID | 23        | 6.95%   |
| IDE  | 22        | 6.65%   |
| SCSI | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 226       | 82.48%  |
| AMD    | 48        | 17.52%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 2.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 5         | 1.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 5         | 1.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.82%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 5         | 1.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.46%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.46%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.09%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 3         | 1.09%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.09%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.09%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.09%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz          | 3         | 1.09%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 3         | 1.09%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.09%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.09%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 3         | 1.09%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 2         | 0.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.73%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.73%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.73%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.73%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 2         | 0.73%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.73%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.73%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.73%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.73%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.73%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.73%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 63        | 22.99%  |
| Intel Core i5           | 59        | 21.53%  |
| Other                   | 29        | 10.58%  |
| Intel Core 2 Duo        | 18        | 6.57%   |
| Intel Celeron           | 18        | 6.57%   |
| Intel Core i3           | 17        | 6.2%    |
| AMD Ryzen 5             | 9         | 3.28%   |
| AMD Ryzen 7             | 8         | 2.92%   |
| Intel Atom              | 6         | 2.19%   |
| Intel Pentium           | 5         | 1.82%   |
| AMD A8                  | 4         | 1.46%   |
| Intel Core 2            | 3         | 1.09%   |
| Intel Pentium Dual-Core | 2         | 0.73%   |
| Intel Core i9           | 2         | 0.73%   |
| Intel Celeron Dual-Core | 2         | 0.73%   |
| AMD Ryzen 9             | 2         | 0.73%   |
| AMD Ryzen 7 PRO         | 2         | 0.73%   |
| AMD Ryzen 5 PRO         | 2         | 0.73%   |
| AMD E2                  | 2         | 0.73%   |
| Intel Pentium M         | 1         | 0.36%   |
| Intel Pentium III       | 1         | 0.36%   |
| Intel Genuine           | 1         | 0.36%   |
| Intel Core m7           | 1         | 0.36%   |
| Intel Core m5           | 1         | 0.36%   |
| Intel Core m3           | 1         | 0.36%   |
| Intel Core 2 Extreme    | 1         | 0.36%   |
| Intel Celeron M         | 1         | 0.36%   |
| AMD Turion 64 X2 Mobile | 1         | 0.36%   |
| AMD Sempron             | 1         | 0.36%   |
| AMD Ryzen 3 PRO         | 1         | 0.36%   |
| AMD Ryzen 3             | 1         | 0.36%   |
| AMD PRO A10             | 1         | 0.36%   |
| AMD Phenom II           | 1         | 0.36%   |
| AMD FX                  | 1         | 0.36%   |
| AMD E1                  | 1         | 0.36%   |
| AMD E                   | 1         | 0.36%   |
| AMD Athlon 64 X2        | 1         | 0.36%   |
| AMD Athlon              | 1         | 0.36%   |
| AMD A6                  | 1         | 0.36%   |
| AMD A10                 | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 139       | 50.73%  |
| 4      | 92        | 33.58%  |
| 8      | 14        | 5.11%   |
| 6      | 12        | 4.38%   |
| 1      | 10        | 3.65%   |
| 14     | 4         | 1.46%   |
| 12     | 1         | 0.36%   |
| 10     | 1         | 0.36%   |
| 3      | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 274       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 197       | 71.9%   |
| 1      | 77        | 28.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 265       | 96.01%  |
| Unknown        | 8         | 2.9%    |
| 32-bit         | 3         | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 22.42%  |
| 0x306a9    | 16        | 5.69%   |
| 0x806ec    | 14        | 4.98%   |
| 0x806c1    | 13        | 4.63%   |
| 0x806e9    | 12        | 4.27%   |
| 0x206a7    | 12        | 4.27%   |
| 0x1067a    | 12        | 4.27%   |
| 0x40651    | 9         | 3.2%    |
| 0x806ea    | 7         | 2.49%   |
| 0x406e3    | 7         | 2.49%   |
| 0xa0652    | 6         | 2.14%   |
| 0x306d4    | 6         | 2.14%   |
| 0x906ea    | 5         | 1.78%   |
| 0x306c3    | 5         | 1.78%   |
| 0x30678    | 5         | 1.78%   |
| 0x20655    | 5         | 1.78%   |
| 0x10676    | 5         | 1.78%   |
| 0x06006705 | 5         | 1.78%   |
| 0x906e9    | 4         | 1.42%   |
| 0x6fd      | 4         | 1.42%   |
| 0x406c4    | 4         | 1.42%   |
| 0x08108102 | 4         | 1.42%   |
| 0x806d1    | 3         | 1.07%   |
| 0x706e5    | 3         | 1.07%   |
| 0x106ca    | 3         | 1.07%   |
| 0x0a50000c | 3         | 1.07%   |
| 0x08108109 | 3         | 1.07%   |
| 0x906a3    | 2         | 0.71%   |
| 0x6f6      | 2         | 0.71%   |
| 0x6d8      | 2         | 0.71%   |
| 0x506e3    | 2         | 0.71%   |
| 0x20652    | 2         | 0.71%   |
| 0x08600106 | 2         | 0.71%   |
| 0x08600103 | 2         | 0.71%   |
| 0x07030106 | 2         | 0.71%   |
| 0x06001119 | 2         | 0.71%   |
| 0x906ed    | 1         | 0.36%   |
| 0x706a8    | 1         | 0.36%   |
| 0x706a1    | 1         | 0.36%   |
| 0x6fb      | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 18.61%  |
| IvyBridge        | 21        | 7.66%   |
| SandyBridge      | 18        | 6.57%   |
| Penryn           | 17        | 6.2%    |
| Skylake          | 16        | 5.84%   |
| Haswell          | 16        | 5.84%   |
| TigerLake        | 15        | 5.47%   |
| Silvermont       | 13        | 4.74%   |
| Westmere         | 10        | 3.65%   |
| Core             | 10        | 3.65%   |
| Zen+             | 8         | 2.92%   |
| Zen 2            | 8         | 2.92%   |
| Excavator        | 8         | 2.92%   |
| IceLake          | 7         | 2.55%   |
| Broadwell        | 7         | 2.55%   |
| CometLake        | 6         | 2.19%   |
| Unknown          | 5         | 1.82%   |
| Zen 3            | 4         | 1.46%   |
| Zen              | 4         | 1.46%   |
| P6               | 4         | 1.46%   |
| Goldmont plus    | 4         | 1.46%   |
| Puma             | 3         | 1.09%   |
| K8 Hammer        | 3         | 1.09%   |
| Bonnell          | 3         | 1.09%   |
| Bobcat           | 3         | 1.09%   |
| Piledriver       | 2         | 0.73%   |
| K10              | 2         | 0.73%   |
| Goldmont         | 2         | 0.73%   |
| Alderlake Hybrid | 2         | 0.73%   |
| Nehalem          | 1         | 0.36%   |
| Jaguar           | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 195       | 58.73%  |
| Nvidia | 85        | 25.6%   |
| AMD    | 52        | 15.66%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 5.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.79%   |
| Intel HD Graphics 620                                                                    | 12        | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.92%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.04%   |
| AMD Renoir                                                                               | 7         | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.75%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.75%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 1.46%   |
| Intel HD Graphics 630                                                                    | 5         | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.46%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.17%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.17%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.17%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.87%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.87%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.87%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.87%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.87%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.58%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 2         | 0.58%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.58%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 143       | 52.19%  |
| Intel + Nvidia | 50        | 18.25%  |
| 1 x AMD        | 39        | 14.23%  |
| 1 x Nvidia     | 28        | 10.22%  |
| AMD + Nvidia   | 6         | 2.19%   |
| 2 x AMD        | 5         | 1.82%   |
| Intel + AMD    | 2         | 0.73%   |
| 2 x Nvidia     | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 224       | 80.87%  |
| Proprietary | 44        | 15.88%  |
| Unknown     | 9         | 3.25%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 169       | 60.14%  |
| 0.01-0.5   | 43        | 15.3%   |
| 1.01-2.0   | 23        | 8.19%   |
| 3.01-4.0   | 21        | 7.47%   |
| 0.51-1.0   | 16        | 5.69%   |
| 5.01-6.0   | 4         | 1.42%   |
| 7.01-8.0   | 3         | 1.07%   |
| 2.01-3.0   | 2         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 56        | 18.18%  |
| LG Display              | 51        | 16.56%  |
| BOE                     | 37        | 12.01%  |
| Chimei Innolux          | 33        | 10.71%  |
| Samsung Electronics     | 26        | 8.44%   |
| Sharp                   | 19        | 6.17%   |
| Dell                    | 16        | 5.19%   |
| Apple                   | 8         | 2.6%    |
| Lenovo                  | 7         | 2.27%   |
| Chi Mei Optoelectronics | 7         | 2.27%   |
| PANDA                   | 6         | 1.95%   |
| Philips                 | 5         | 1.62%   |
| Hewlett-Packard         | 4         | 1.3%    |
| Goldstar                | 4         | 1.3%    |
| Acer                    | 4         | 1.3%    |
| LG Philips              | 3         | 0.97%   |
| AOC                     | 3         | 0.97%   |
| ViewSonic               | 2         | 0.65%   |
| InfoVision              | 2         | 0.65%   |
| CPT                     | 2         | 0.65%   |
| BOE Technology Group    | 2         | 0.65%   |
| ___                     | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| Toshiba                 | 1         | 0.32%   |
| Quanta Display          | 1         | 0.32%   |
| MSI                     | 1         | 0.32%   |
| LGD                     | 1         | 0.32%   |
| Lenovo Group Limited    | 1         | 0.32%   |
| Iiyama                  | 1         | 0.32%   |
| CSO                     | 1         | 0.32%   |
| BenQ                    | 1         | 0.32%   |
| Analogix                | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.26%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 3         | 0.95%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch         | 3         | 0.95%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch          | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch       | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 3         | 0.95%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 2         | 0.63%   |
| Sharp LCD Monitor SHP1547 1920x1200 288x180mm 13.4-inch              | 2         | 0.63%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch              | 2         | 0.63%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch              | 2         | 0.63%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch              | 2         | 0.63%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch              | 2         | 0.63%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 2         | 0.63%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch        | 2         | 0.63%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch         | 2         | 0.63%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 2         | 0.63%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 2         | 0.63%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.63%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch              | 2         | 0.63%   |
| Hewlett-Packard Z34c HWP3201 3440x1440 797x333mm 34.0-inch           | 2         | 0.63%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 2         | 0.63%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 2         | 0.63%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch        | 2         | 0.63%   |
| ___ LCD TV ___9000 1360x768                                          | 1         | 0.32%   |
| ViewSonic VX2858Sml VSCD02F 1920x1080 621x341mm 27.9-inch            | 1         | 0.32%   |
| ViewSonic VP2756-2K VSCE63B 2560x1440 597x336mm 27.0-inch            | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 128       | 43.39%  |
| 1366x768 (WXGA)    | 78        | 26.44%  |
| 1600x900 (HD+)     | 14        | 4.75%   |
| 1280x800 (WXGA)    | 13        | 4.41%   |
| 3840x2160 (4K)     | 12        | 4.07%   |
| 1920x1200 (WUXGA)  | 10        | 3.39%   |
| 1440x900 (WXGA+)   | 9         | 3.05%   |
| 2560x1440 (QHD)    | 7         | 2.37%   |
| 3440x1440          | 4         | 1.36%   |
| 3840x2400          | 3         | 1.02%   |
| 1024x600           | 3         | 1.02%   |
| 3200x1800 (QHD+)   | 2         | 0.68%   |
| 2560x1600          | 2         | 0.68%   |
| 1600x1200          | 2         | 0.68%   |
| 1360x768           | 2         | 0.68%   |
| 800x1280           | 1         | 0.34%   |
| 3456x2160          | 1         | 0.34%   |
| 2256x1504          | 1         | 0.34%   |
| 2160x1440          | 1         | 0.34%   |
| 1680x1050 (WSXGA+) | 1         | 0.34%   |
| 1280x1024 (SXGA)   | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 130       | 41.4%   |
| 14      | 46        | 14.65%  |
| 13      | 39        | 12.42%  |
| 27      | 15        | 4.78%   |
| 17      | 15        | 4.78%   |
| 12      | 13        | 4.14%   |
| 24      | 11        | 3.5%    |
| Unknown | 9         | 2.87%   |
| 23      | 7         | 2.23%   |
| 21      | 7         | 2.23%   |
| 34      | 5         | 1.59%   |
| 11      | 4         | 1.27%   |
| 18      | 3         | 0.96%   |
| 10      | 3         | 0.96%   |
| 31      | 2         | 0.64%   |
| 72      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 29      | 1         | 0.32%   |
| 25      | 1         | 0.32%   |
| 20      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 186       | 60%     |
| 201-300     | 45        | 14.52%  |
| 501-600     | 27        | 8.71%   |
| 351-400     | 18        | 5.81%   |
| 401-500     | 11        | 3.55%   |
| Unknown     | 9         | 2.9%    |
| 601-700     | 7         | 2.26%   |
| 701-800     | 5         | 1.61%   |
| 801-900     | 1         | 0.32%   |
| 1501-2000   | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 222       | 80.43%  |
| 16/10   | 35        | 12.68%  |
| Unknown | 7         | 2.54%   |
| 21/9    | 5         | 1.81%   |
| 3/2     | 3         | 1.09%   |
| 4/3     | 2         | 0.72%   |
| 5/4     | 1         | 0.36%   |
| 0.62    | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 128       | 40.89%  |
| 81-90          | 64        | 20.45%  |
| 71-80          | 22        | 7.03%   |
| 201-250        | 20        | 6.39%   |
| 301-350        | 15        | 4.79%   |
| 61-70          | 12        | 3.83%   |
| 121-130        | 11        | 3.51%   |
| Unknown        | 9         | 2.88%   |
| 351-500        | 8         | 2.56%   |
| 51-60          | 4         | 1.28%   |
| 251-300        | 4         | 1.28%   |
| 141-150        | 4         | 1.28%   |
| 41-50          | 3         | 0.96%   |
| 131-140        | 3         | 0.96%   |
| 151-200        | 2         | 0.64%   |
| More than 1000 | 1         | 0.32%   |
| 111-120        | 1         | 0.32%   |
| 501-1000       | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 129       | 42.02%  |
| 101-120       | 90        | 29.32%  |
| 51-100        | 44        | 14.33%  |
| 161-240       | 23        | 7.49%   |
| More than 240 | 10        | 3.26%   |
| Unknown       | 9         | 2.93%   |
| 1-50          | 2         | 0.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 220       | 78.57%  |
| 2     | 44        | 15.71%  |
| 0     | 9         | 3.21%   |
| 3     | 6         | 2.14%   |
| 4     | 1         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 156       | 35.45%  |
| Realtek Semiconductor             | 133       | 30.23%  |
| Qualcomm Atheros                  | 50        | 11.36%  |
| Broadcom                          | 36        | 8.18%   |
| Broadcom Limited                  | 9         | 2.05%   |
| Nvidia                            | 8         | 1.82%   |
| Ralink Technology                 | 5         | 1.14%   |
| Marvell Technology Group          | 5         | 1.14%   |
| Ericsson Business Mobile Networks | 5         | 1.14%   |
| Samsung Electronics               | 4         | 0.91%   |
| MediaTek                          | 4         | 0.91%   |
| Ralink                            | 3         | 0.68%   |
| Lenovo                            | 3         | 0.68%   |
| ASIX Electronics                  | 2         | 0.45%   |
| Xilinx                            | 1         | 0.23%   |
| Xiaomi                            | 1         | 0.23%   |
| TP-Link                           | 1         | 0.23%   |
| Toshiba                           | 1         | 0.23%   |
| T & A Mobile Phones               | 1         | 0.23%   |
| Qualcomm                          | 1         | 0.23%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.23%   |
| NetGear                           | 1         | 0.23%   |
| Microsoft                         | 1         | 0.23%   |
| LSI                               | 1         | 0.23%   |
| ICS Advent                        | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| DisplayLink                       | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| Bose                              | 1         | 0.23%   |
| Apple                             | 1         | 0.23%   |
| 3Com                              | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 14.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 5.05%   |
| Intel Wi-Fi 6 AX200                                               | 19        | 3.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 12        | 2.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 2.06%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.06%   |
| Intel Wireless 7260                                               | 11        | 2.06%   |
| Intel Wireless 8260                                               | 8         | 1.5%    |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.12%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.12%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 1.12%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.93%   |
| Intel Wireless 7265                                               | 5         | 0.93%   |
| Intel Wireless 3165                                               | 5         | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.93%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.75%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.56%   |
| Intel Wireless 3160                                               | 3         | 0.56%   |
| Intel WiFi Link 5100                                              | 3         | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 152       | 53.52%  |
| Qualcomm Atheros      | 43        | 15.14%  |
| Realtek Semiconductor | 40        | 14.08%  |
| Broadcom              | 29        | 10.21%  |
| Ralink Technology     | 5         | 1.76%   |
| MediaTek              | 4         | 1.41%   |
| Ralink                | 3         | 1.06%   |
| Broadcom Limited      | 3         | 1.06%   |
| TP-Link               | 1         | 0.35%   |
| Qualcomm              | 1         | 0.35%   |
| NetGear               | 1         | 0.35%   |
| Dell                  | 1         | 0.35%   |
| Apple                 | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 19        | 6.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 5.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 4.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 4.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.85%   |
| Intel Wireless 8265 / 8275                                              | 11        | 3.85%   |
| Intel Wireless 7260                                                     | 11        | 3.85%   |
| Intel Wireless 8260                                                     | 8         | 2.8%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 2.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.75%   |
| Intel Wireless 7265                                                     | 5         | 1.75%   |
| Intel Wireless 3165                                                     | 5         | 1.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 5         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.75%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.4%    |
| Intel Centrino Ultimate-N 6300                                          | 4         | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.05%   |
| Intel Wireless 3160                                                     | 3         | 1.05%   |
| Intel WiFi Link 5100                                                    | 3         | 1.05%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 3         | 1.05%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.05%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.7%    |
| Realtek 802.11n                                                         | 2         | 0.7%    |
| Realtek 802.11ac NIC                                                    | 2         | 0.7%    |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 117       | 49.79%  |
| Intel                         | 58        | 24.68%  |
| Qualcomm Atheros              | 13        | 5.53%   |
| Broadcom                      | 10        | 4.26%   |
| Nvidia                        | 8         | 3.4%    |
| Broadcom Limited              | 7         | 2.98%   |
| Marvell Technology Group      | 5         | 2.13%   |
| Samsung Electronics           | 4         | 1.7%    |
| Lenovo                        | 3         | 1.28%   |
| ASIX Electronics              | 2         | 0.85%   |
| Xilinx                        | 1         | 0.43%   |
| Xiaomi                        | 1         | 0.43%   |
| T & A Mobile Phones           | 1         | 0.43%   |
| OnePlus Technology (Shenzhen) | 1         | 0.43%   |
| Microsoft                     | 1         | 0.43%   |
| ICS Advent                    | 1         | 0.43%   |
| DisplayLink                   | 1         | 0.43%   |
| 3Com                          | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 32.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 11.34%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 7.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 5.04%   |
| Nvidia MCP79 Ethernet                                             | 6         | 2.52%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.52%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 1.26%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.26%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.26%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 1.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.84%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.84%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.84%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.84%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2         | 0.84%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.84%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.84%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.84%   |
| Xilinx Ethernet controller                                        | 1         | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.42%   |
| T & A Mobile Phones QM215-QRD _SN:6B7D8716                        | 1         | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.42%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.42%   |
| OnePlus (Shenzhen) AC2003                                         | 1         | 0.42%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 271       | 53.88%  |
| Ethernet | 221       | 43.94%  |
| Modem    | 11        | 2.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 221       | 77.27%  |
| Ethernet | 65        | 22.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 203       | 73.82%  |
| 1     | 67        | 24.36%  |
| 0     | 3         | 1.09%   |
| 3     | 2         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 244       | 87.77%  |
| Yes  | 34        | 12.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 53.33%  |
| Realtek Semiconductor           | 21        | 10%     |
| Broadcom                        | 15        | 7.14%   |
| Lite-On Technology              | 12        | 5.71%   |
| IMC Networks                    | 12        | 5.71%   |
| Qualcomm Atheros Communications | 11        | 5.24%   |
| Apple                           | 7         | 3.33%   |
| Dell                            | 6         | 2.86%   |
| Hewlett-Packard                 | 5         | 2.38%   |
| Toshiba                         | 2         | 0.95%   |
| Realtek                         | 2         | 0.95%   |
| Cambridge Silicon Radio         | 2         | 0.95%   |
| Ralink                          | 1         | 0.48%   |
| Foxconn International           | 1         | 0.48%   |
| Foxconn / Hon Hai               | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 47        | 22.38%  |
| Intel AX201 Bluetooth                                       | 19        | 9.05%   |
| Intel AX200 Bluetooth                                       | 18        | 8.57%   |
| Realtek Bluetooth Radio                                     | 15        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 11        | 5.24%   |
| Qualcomm Atheros  Bluetooth Device                          | 6         | 2.86%   |
| IMC Networks Bluetooth Radio                                | 6         | 2.86%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 6         | 2.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 5         | 2.38%   |
| Intel AX210 Bluetooth                                       | 5         | 2.38%   |
| Apple Bluetooth Host Controller                             | 5         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 1.9%    |
| Broadcom BCM2045B (BDC-2.1)                                 | 4         | 1.9%    |
| Realtek RTL8821A Bluetooth                                  | 3         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.43%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 3         | 1.43%   |
| Intel Bluetooth Device                                      | 3         | 1.43%   |
| HP Broadcom 2070 Bluetooth Combo                            | 3         | 1.43%   |
| Realtek Bluetooth Radio                                     | 2         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 0.95%   |
| Lite-On Wireless_Device                                     | 2         | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 0.95%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 0.95%   |
| IMC Networks Wireless_Device                                | 2         | 0.95%   |
| IMC Networks Bluetooth Device                               | 2         | 0.95%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 0.95%   |
| Dell Wireless 355 Bluetooth                                 | 2         | 0.95%   |
| Dell DW375 Bluetooth Module                                 | 2         | 0.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0                           | 2         | 0.95%   |
| Toshiba Bluetooth Device                                    | 1         | 0.48%   |
| Toshiba BCM43142A0                                          | 1         | 0.48%   |
| Ralink RT3290 Bluetooth                                     | 1         | 0.48%   |
| Lite-On Bluetooth Radio                                     | 1         | 0.48%   |
| Lite-On BCM43142A0                                          | 1         | 0.48%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.48%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.48%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 215       | 63.42%  |
| Nvidia                | 55        | 16.22%  |
| AMD                   | 51        | 15.04%  |
| Realtek Semiconductor | 3         | 0.88%   |
| GN Netcom             | 3         | 0.88%   |
| RODE Microphones      | 2         | 0.59%   |
| Lenovo                | 2         | 0.59%   |
| C-Media Electronics   | 2         | 0.59%   |
| VIA Technologies      | 1         | 0.29%   |
| No brand              | 1         | 0.29%   |
| Logitech              | 1         | 0.29%   |
| ESS Technology        | 1         | 0.29%   |
| Creative Technology   | 1         | 0.29%   |
| AUDIOLAB              | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 35        | 8.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 5.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 5.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 4.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 3.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 3.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 2.51%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.51%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.26%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.01%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 2.01%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.75%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.75%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 1.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.5%    |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.25%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.25%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1%      |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1%      |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 1%      |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1%      |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 49        | 29.34%  |
| SK hynix            | 32        | 19.16%  |
| Micron Technology   | 21        | 12.57%  |
| Unknown             | 14        | 8.38%   |
| Kingston            | 14        | 8.38%   |
| Crucial             | 9         | 5.39%   |
| Corsair             | 6         | 3.59%   |
| Ramaxel Technology  | 5         | 2.99%   |
| Elpida              | 4         | 2.4%    |
| Unknown (ABCD)      | 3         | 1.8%    |
| Nanya Technology    | 3         | 1.8%    |
| Transcend           | 1         | 0.6%    |
| SHARETRONIC         | 1         | 0.6%    |
| Patriot             | 1         | 0.6%    |
| G.Skill             | 1         | 0.6%    |
| CSX                 | 1         | 0.6%    |
| Apacer              | 1         | 0.6%    |
| A Force             | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 2.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.69%   |
| Corsair RAM CM4X16GE2666C18S4 16GB SODIMM DDR4 2667MT/s          | 3         | 1.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.13%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.13%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.13%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.13%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.13%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.13%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.13%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s            | 2         | 1.13%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 1.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.13%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.13%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.13%   |
| Micron RAM 8ATF1G64HZ-2G3E1 8GB SODIMM DDR4 2400MT/s             | 2         | 1.13%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.13%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.13%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.13%   |
| Elpida RAM EBJ41UF8BDU0-DJ-F 4GB Chip DDR3 1333MT/s              | 2         | 1.13%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 1.13%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.56%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1867MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR4 2133MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM 800MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.56%   |
| Unknown RAM Module 256MB SODIMM DRAM                             | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 1GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.56%   |
| Unknown RAM Module 128MB SODIMM DRAM                             | 1         | 0.56%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                           | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 73        | 49.66%  |
| DDR3    | 40        | 27.21%  |
| LPDDR4  | 10        | 6.8%    |
| DDR2    | 9         | 6.12%   |
| LPDDR3  | 5         | 3.4%    |
| SDRAM   | 4         | 2.72%   |
| DDR     | 2         | 1.36%   |
| Unknown | 2         | 1.36%   |
| DRAM    | 1         | 0.68%   |
| DDR5    | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 86.09%  |
| Row Of Chips | 16        | 10.6%   |
| Chip         | 4         | 2.65%   |
| Unknown      | 1         | 0.66%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 34.59%  |
| 4096  | 44        | 27.67%  |
| 16384 | 26        | 16.35%  |
| 2048  | 19        | 11.95%  |
| 1024  | 7         | 4.4%    |
| 32768 | 6         | 3.77%   |
| 256   | 1         | 0.63%   |
| 128   | 1         | 0.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 30        | 18.99%  |
| 1600    | 25        | 15.82%  |
| 3200    | 22        | 13.92%  |
| 2400    | 15        | 9.49%   |
| 2133    | 12        | 7.59%   |
| 1334    | 8         | 5.06%   |
| 4267    | 6         | 3.8%    |
| 3266    | 5         | 3.16%   |
| 1333    | 5         | 3.16%   |
| 800     | 5         | 3.16%   |
| 667     | 5         | 3.16%   |
| 1067    | 4         | 2.53%   |
| 1867    | 3         | 1.9%    |
| 8400    | 2         | 1.27%   |
| 4800    | 2         | 1.27%   |
| 4199    | 2         | 1.27%   |
| 975     | 2         | 1.27%   |
| Unknown | 2         | 1.27%   |
| 2267    | 1         | 0.63%   |
| 2048    | 1         | 0.63%   |
| 533     | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| STMicroelectronics | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 50%     |
| Brother HL-L2340D series                                  | 1         | 50%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 59        | 24.48%  |
| Realtek Semiconductor                  | 32        | 13.28%  |
| IMC Networks                           | 25        | 10.37%  |
| Acer                                   | 24        | 9.96%   |
| Microdia                               | 22        | 9.13%   |
| Quanta                                 | 10        | 4.15%   |
| Sunplus Innovation Technology          | 8         | 3.32%   |
| Logitech                               | 7         | 2.9%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.9%    |
| Apple                                  | 7         | 2.9%    |
| Suyin                                  | 6         | 2.49%   |
| Samsung Electronics                    | 5         | 2.07%   |
| ALi                                    | 5         | 2.07%   |
| Syntek                                 | 4         | 1.66%   |
| Silicon Motion                         | 4         | 1.66%   |
| Lite-On Technology                     | 4         | 1.66%   |
| Ricoh                                  | 3         | 1.24%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| Y Media                                | 1         | 0.41%   |
| Unknown                                | 1         | 0.41%   |
| Trust                                  | 1         | 0.41%   |
| Nikon                                  | 1         | 0.41%   |
| Luxvisions Innotech Limited            | 1         | 0.41%   |
| Lenovo                                 | 1         | 0.41%   |
| DigiTech                               | 1         | 0.41%   |
| Alcor Micro                            | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD               | 12        | 4.94%   |
| Microdia Integrated_Webcam_HD              | 10        | 4.12%   |
| IMC Networks Integrated Camera             | 10        | 4.12%   |
| Chicony Integrated Camera                  | 9         | 3.7%    |
| Acer Integrated Camera                     | 8         | 3.29%   |
| Chicony USB2.0 Camera                      | 7         | 2.88%   |
| Chicony HD Webcam                          | 7         | 2.88%   |
| Apple Built-in iSight                      | 6         | 2.47%   |
| Samsung Galaxy series, misc. (MTP mode)    | 5         | 2.06%   |
| Microdia Integrated Webcam                 | 4         | 1.65%   |
| IMC Networks USB2.0 HD UVC WebCam          | 4         | 1.65%   |
| Acer EasyCamera                            | 4         | 1.65%   |
| Sunplus Integrated_Webcam_HD               | 3         | 1.23%   |
| Realtek USB Camera                         | 3         | 1.23%   |
| Realtek Integrated Webcam HD               | 3         | 1.23%   |
| Lite-On HP HD Camera                       | 3         | 1.23%   |
| Chicony Lenovo EasyCamera                  | 3         | 1.23%   |
| ALi WebCam                                 | 3         | 1.23%   |
| Acer BisonCam, NB Pro                      | 3         | 1.23%   |
| Syntek Integrated Camera                   | 2         | 0.82%   |
| Syntek EasyCamera                          | 2         | 0.82%   |
| Suyin HP Truevision HD                     | 2         | 0.82%   |
| Realtek USB2.0 HD UVC WebCam               | 2         | 0.82%   |
| Realtek HP Truevision HD integrated webcam | 2         | 0.82%   |
| Realtek HD WebCam                          | 2         | 0.82%   |
| Quanta HP Webcam                           | 2         | 0.82%   |
| Logitech HD Pro Webcam C920                | 2         | 0.82%   |
| Logitech B525 HD Webcam                    | 2         | 0.82%   |
| IMC Networks USB2.0 VGA UVC WebCam         | 2         | 0.82%   |
| IMC Networks TOSHIBA Web Camera - HD       | 2         | 0.82%   |
| IMC Networks EasyCamera                    | 2         | 0.82%   |
| Chicony USB2.0 HD UVC WebCam               | 2         | 0.82%   |
| Chicony USB 2.0 Camera                     | 2         | 0.82%   |
| Chicony thinkpad t430s camera              | 2         | 0.82%   |
| Chicony Lenovo Integrated Camera (0.3MP)   | 2         | 0.82%   |
| Chicony Integrated Camera (1280x720@30)    | 2         | 0.82%   |
| Chicony HP Wide Vision HD Camera           | 2         | 0.82%   |
| Chicony HP TrueVision HD Camera            | 2         | 0.82%   |
| Chicony HP Truevision HD                   | 2         | 0.82%   |
| Chicony EasyCamera                         | 2         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 31.58%  |
| Validity Sensors           | 17        | 29.82%  |
| Shenzhen Goodix Technology | 11        | 19.3%   |
| Upek                       | 4         | 7.02%   |
| LighTuning Technology      | 2         | 3.51%   |
| AuthenTec                  | 2         | 3.51%   |
| STMicroelectronics         | 1         | 1.75%   |
| Focal-systems.Corp         | 1         | 1.75%   |
| Elan Microelectronics      | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown                                                    | 8         | 14.04%  |
| Shenzhen Goodix FingerPrint                                | 6         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 4         | 7.02%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 7.02%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 4         | 7.02%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 2         | 3.51%   |
| Validity Sensors VFS451 Fingerprint Reader                 | 2         | 3.51%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 3.51%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 3.51%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 3.51%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 2         | 3.51%   |
| AuthenTec Fingerprint Sensor                               | 2         | 3.51%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 1.75%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 1.75%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 1.75%   |
| Validity Sensors VFS300 Fingerprint Reader                 | 1         | 1.75%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 1.75%   |
| Validity Sensors Synaptics WBDI                            | 1         | 1.75%   |
| Validity Sensors Fingerprint scanner                       | 1         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.75%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 1.75%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.75%   |
| Elan ELAN:Fingerprint                                      | 1         | 1.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 19        | 52.78%  |
| Alcor Micro | 7         | 19.44%  |
| Upek        | 5         | 13.89%  |
| O2 Micro    | 4         | 11.11%  |
| Lenovo      | 1         | 2.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 7         | 19.44%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 19.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 13.89%  |
| Broadcom 5880                                                                | 4         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.78%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 156       | 54.93%  |
| 1     | 102       | 35.92%  |
| 2     | 20        | 7.04%   |
| 3     | 6         | 2.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 37.33%  |
| Chipcard                 | 31        | 20.67%  |
| Net/wireless             | 20        | 13.33%  |
| Graphics card            | 20        | 13.33%  |
| Multimedia controller    | 5         | 3.33%   |
| Camera                   | 5         | 3.33%   |
| Storage                  | 4         | 2.67%   |
| Communication controller | 3         | 2%      |
| Card reader              | 3         | 2%      |
| Bluetooth                | 2         | 1.33%   |
| Modem                    | 1         | 0.67%   |


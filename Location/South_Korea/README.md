Linux in South Korea - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in South Korea.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/South_Korea/Desktop/README.md) and [notebooks](/Location/South_Korea/Notebook/README.md).

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

Total: 471

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B250M Pro4                  | Desktop     | [59704c823a](https://linux-hardware.org/?probe=59704c823a) | Jul 29, 2022 |
| PCPartner     | MILANO-P Rev.00             | Desktop     | [1b6d72c5ac](https://linux-hardware.org/?probe=1b6d72c5ac) | Jul 18, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5bdae5b8f7](https://linux-hardware.org/?probe=5bdae5b8f7) | Jul 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YJC... | Notebook    | [ce2df1e866](https://linux-hardware.org/?probe=ce2df1e866) | Jul 18, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf71ced9a0](https://linux-hardware.org/?probe=cf71ced9a0) | Jul 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [cf470317b1](https://linux-hardware.org/?probe=cf470317b1) | Jul 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [87edfcaadf](https://linux-hardware.org/?probe=87edfcaadf) | Jul 09, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [8971b67abc](https://linux-hardware.org/?probe=8971b67abc) | Jul 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [251bc4d58d](https://linux-hardware.org/?probe=251bc4d58d) | Jul 04, 2022 |
| Gigabyte      | C621-SD8 M18802             | Server      | [52aeaedd47](https://linux-hardware.org/?probe=52aeaedd47) | Jun 30, 2022 |
| Gigabyte      | MQLP5AP-00                  | Desktop     | [8014a14842](https://linux-hardware.org/?probe=8014a14842) | Jun 30, 2022 |
| LG Electro... | 14T90N-VR56K                | Convertible | [22f978c26c](https://linux-hardware.org/?probe=22f978c26c) | Jun 26, 2022 |
| Lenovo        | ThinkPad S2 20GJA00S00      | Notebook    | [44eb58334d](https://linux-hardware.org/?probe=44eb58334d) | Jun 24, 2022 |
| LG Electro... | 14Z90N-VA76K                | Notebook    | [9e606a176f](https://linux-hardware.org/?probe=9e606a176f) | Jun 24, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [b93d65dd64](https://linux-hardware.org/?probe=b93d65dd64) | Jun 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3e3fb0129e](https://linux-hardware.org/?probe=3e3fb0129e) | Jun 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [f909fc87b9](https://linux-hardware.org/?probe=f909fc87b9) | Jun 12, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [95ec23c2e9](https://linux-hardware.org/?probe=95ec23c2e9) | Jun 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [014c9a184e](https://linux-hardware.org/?probe=014c9a184e) | Jun 06, 2022 |
| LG Electro... | Z360-GH6SK                  | Notebook    | [cb91c2c2bd](https://linux-hardware.org/?probe=cb91c2c2bd) | Jun 02, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [9b67243691](https://linux-hardware.org/?probe=9b67243691) | May 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f941ba9fe](https://linux-hardware.org/?probe=4f941ba9fe) | May 24, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [617edab20c](https://linux-hardware.org/?probe=617edab20c) | May 20, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [6aea229376](https://linux-hardware.org/?probe=6aea229376) | May 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [feb7ce77bf](https://linux-hardware.org/?probe=feb7ce77bf) | May 18, 2022 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [2d23125cd0](https://linux-hardware.org/?probe=2d23125cd0) | May 15, 2022 |
| LG Electro... | 15Z990-HA50K                | Notebook    | [e5cf57d2f4](https://linux-hardware.org/?probe=e5cf57d2f4) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [7286fd4e36](https://linux-hardware.org/?probe=7286fd4e36) | May 11, 2022 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [55f1cc4480](https://linux-hardware.org/?probe=55f1cc4480) | May 10, 2022 |
| Lenovo        | ThinkPad 8 20BN0002KR       | Tablet      | [8e59716f95](https://linux-hardware.org/?probe=8e59716f95) | May 07, 2022 |
| Alienware     | 0CPDXD A00                  | Desktop     | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [80bdc044eb](https://linux-hardware.org/?probe=80bdc044eb) | May 01, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [6df44e9098](https://linux-hardware.org/?probe=6df44e9098) | Apr 29, 2022 |
| Teclast       | tPAD                        | Notebook    | [2b86292373](https://linux-hardware.org/?probe=2b86292373) | Apr 20, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [a4d7160eb9](https://linux-hardware.org/?probe=a4d7160eb9) | Apr 17, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [71624fff28](https://linux-hardware.org/?probe=71624fff28) | Apr 17, 2022 |
| Wolfnfox      | WF-TBAT                     | Notebook    | [7d04cc8361](https://linux-hardware.org/?probe=7d04cc8361) | Apr 13, 2022 |
| Teclast       | tPAD                        | Notebook    | [a9f93e289b](https://linux-hardware.org/?probe=a9f93e289b) | Apr 13, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [9a15614b1e](https://linux-hardware.org/?probe=9a15614b1e) | Apr 13, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [ed880374c4](https://linux-hardware.org/?probe=ed880374c4) | Apr 10, 2022 |
| MECHREVO      | Taitan Series GM7TG0M       | Notebook    | [948d29a218](https://linux-hardware.org/?probe=948d29a218) | Apr 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [ccbdd7504c](https://linux-hardware.org/?probe=ccbdd7504c) | Apr 08, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [14b7f50736](https://linux-hardware.org/?probe=14b7f50736) | Apr 08, 2022 |
| Teclast       | tPAD                        | Notebook    | [5eddc816df](https://linux-hardware.org/?probe=5eddc816df) | Apr 07, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [1874ac7edf](https://linux-hardware.org/?probe=1874ac7edf) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [f22fa67906](https://linux-hardware.org/?probe=f22fa67906) | Apr 01, 2022 |
| HP            | Stream Notebook PC 11       | Notebook    | [8fc09857a6](https://linux-hardware.org/?probe=8fc09857a6) | Apr 01, 2022 |
| Intel         | powered classmate PC        | Notebook    | [8ce4fa1757](https://linux-hardware.org/?probe=8ce4fa1757) | Apr 01, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [90aa422ea2](https://linux-hardware.org/?probe=90aa422ea2) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6c36c54313](https://linux-hardware.org/?probe=6c36c54313) | Mar 31, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a8cacc7845](https://linux-hardware.org/?probe=a8cacc7845) | Mar 27, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [fa4526e9f3](https://linux-hardware.org/?probe=fa4526e9f3) | Mar 24, 2022 |
| MSI           | GF75 Thin 9SCXR             | Notebook    | [df19241968](https://linux-hardware.org/?probe=df19241968) | Mar 20, 2022 |
| ECS           | PB02CF                      | Server      | [0600880dba](https://linux-hardware.org/?probe=0600880dba) | Mar 19, 2022 |
| MSI           | GF75 Thin 9SCXR             | Notebook    | [b3458eda8f](https://linux-hardware.org/?probe=b3458eda8f) | Mar 14, 2022 |
| Hardkernel    | Odroid XU4                  | Soc         | [4d5412852b](https://linux-hardware.org/?probe=4d5412852b) | Mar 13, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [05cdb119e9](https://linux-hardware.org/?probe=05cdb119e9) | Mar 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [95ff70277e](https://linux-hardware.org/?probe=95ff70277e) | Feb 24, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [bb04a03420](https://linux-hardware.org/?probe=bb04a03420) | Feb 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [38ad42c186](https://linux-hardware.org/?probe=38ad42c186) | Feb 22, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [968b189e38](https://linux-hardware.org/?probe=968b189e38) | Feb 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [d8f6d95994](https://linux-hardware.org/?probe=d8f6d95994) | Feb 14, 2022 |
| HANSUNG CO... | EX58                        | Notebook    | [7c2a023530](https://linux-hardware.org/?probe=7c2a023530) | Feb 10, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [ed95e4c1c7](https://linux-hardware.org/?probe=ed95e4c1c7) | Feb 09, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [a597b083c9](https://linux-hardware.org/?probe=a597b083c9) | Feb 08, 2022 |
| Google        | Ampton                      | Notebook    | [0f1564bb4a](https://linux-hardware.org/?probe=0f1564bb4a) | Feb 06, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [7742fa4642](https://linux-hardware.org/?probe=7742fa4642) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [65a6ca3880](https://linux-hardware.org/?probe=65a6ca3880) | Feb 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [144717a1f1](https://linux-hardware.org/?probe=144717a1f1) | Feb 04, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [14f8855baa](https://linux-hardware.org/?probe=14f8855baa) | Feb 03, 2022 |
| ECS           | PB02CF                      | Server      | [9f7f807004](https://linux-hardware.org/?probe=9f7f807004) | Jan 30, 2022 |
| ECS           | PB02CF                      | Server      | [594030dfa1](https://linux-hardware.org/?probe=594030dfa1) | Jan 30, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [7f9793a709](https://linux-hardware.org/?probe=7f9793a709) | Jan 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [2c22ac6a5f](https://linux-hardware.org/?probe=2c22ac6a5f) | Jan 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [882dab7b0e](https://linux-hardware.org/?probe=882dab7b0e) | Jan 22, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [c081d60b2a](https://linux-hardware.org/?probe=c081d60b2a) | Jan 22, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [11d1870f98](https://linux-hardware.org/?probe=11d1870f98) | Jan 21, 2022 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [d0d21d2892](https://linux-hardware.org/?probe=d0d21d2892) | Jan 18, 2022 |
| LG Electro... | 16ZD90P-GX7LK               | Notebook    | [0870fd8772](https://linux-hardware.org/?probe=0870fd8772) | Dec 29, 2021 |
| Lenovo        | G480 20149                  | Notebook    | [08a0d07d28](https://linux-hardware.org/?probe=08a0d07d28) | Dec 28, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [23e536f087](https://linux-hardware.org/?probe=23e536f087) | Dec 28, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [1f4a9c160f](https://linux-hardware.org/?probe=1f4a9c160f) | Dec 28, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [a8fbe33d19](https://linux-hardware.org/?probe=a8fbe33d19) | Dec 26, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [7843ddc3fb](https://linux-hardware.org/?probe=7843ddc3fb) | Dec 24, 2021 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [151434ab61](https://linux-hardware.org/?probe=151434ab61) | Dec 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [ff620ffdcd](https://linux-hardware.org/?probe=ff620ffdcd) | Dec 07, 2021 |
| ECS           | PB02CF                      | Server      | [ac300533fe](https://linux-hardware.org/?probe=ac300533fe) | Dec 04, 2021 |
| Jooyontech... | J3GP Pro                    | Notebook    | [6f13d68344](https://linux-hardware.org/?probe=6f13d68344) | Dec 04, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | Notebook    | [c7cc850f29](https://linux-hardware.org/?probe=c7cc850f29) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | Notebook    | [901fdc3726](https://linux-hardware.org/?probe=901fdc3726) | Dec 03, 2021 |
| Lenovo        | 1036 SDK0T76457 WIN 3915... | Desktop     | [f894442edc](https://linux-hardware.org/?probe=f894442edc) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [4d11bd6b59](https://linux-hardware.org/?probe=4d11bd6b59) | Nov 20, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [b4c7522ea3](https://linux-hardware.org/?probe=b4c7522ea3) | Nov 15, 2021 |
| Samsung       | 950QDA                      | Convertible | [45d49f2001](https://linux-hardware.org/?probe=45d49f2001) | Nov 13, 2021 |
| LG Electro... | 15Z990-HA50K                | Notebook    | [6f5255e0f2](https://linux-hardware.org/?probe=6f5255e0f2) | Nov 01, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [70074ebee1](https://linux-hardware.org/?probe=70074ebee1) | Nov 01, 2021 |
| ASUSTek       | X556URK                     | Notebook    | [212240b258](https://linux-hardware.org/?probe=212240b258) | Oct 29, 2021 |
| LG Electro... | 17ZD90P-GX7LK               | Notebook    | [23aa2c83ae](https://linux-hardware.org/?probe=23aa2c83ae) | Oct 27, 2021 |
| Intel         | NUC11PABi7 K90104-303       | Mini pc     | [0279a35638](https://linux-hardware.org/?probe=0279a35638) | Oct 27, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [19eba77c24](https://linux-hardware.org/?probe=19eba77c24) | Oct 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2f6634b953](https://linux-hardware.org/?probe=2f6634b953) | Oct 22, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fb8b55960a](https://linux-hardware.org/?probe=fb8b55960a) | Oct 20, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | Notebook    | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [e93b95fc3c](https://linux-hardware.org/?probe=e93b95fc3c) | Sep 30, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fbc7a613a6](https://linux-hardware.org/?probe=fbc7a613a6) | Sep 29, 2021 |
| HANSUNG CO... | TFX4150H                    | Notebook    | [11f2fbef85](https://linux-hardware.org/?probe=11f2fbef85) | Sep 29, 2021 |
| ASUSTek       | U36JC                       | Notebook    | [c6e87f1fb7](https://linux-hardware.org/?probe=c6e87f1fb7) | Sep 23, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| Samsung       | 730QCJ/730QCR               | Notebook    | [54cd6887df](https://linux-hardware.org/?probe=54cd6887df) | Sep 21, 2021 |
| Clevo         | M740T/M760T                 | Notebook    | [7731b8340f](https://linux-hardware.org/?probe=7731b8340f) | Sep 17, 2021 |
| Samsung       | 400B4C/400B5C/200B4C/200... | Notebook    | [581ab7ecde](https://linux-hardware.org/?probe=581ab7ecde) | Sep 17, 2021 |
| LG Electro... | 16TD90P-GX56K               | Convertible | [448fe0cf6a](https://linux-hardware.org/?probe=448fe0cf6a) | Sep 11, 2021 |
| ECS           | PB02CF                      | Server      | [6aeb74b9f1](https://linux-hardware.org/?probe=6aeb74b9f1) | Sep 03, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [24de612862](https://linux-hardware.org/?probe=24de612862) | Aug 31, 2021 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [33233b370e](https://linux-hardware.org/?probe=33233b370e) | Aug 30, 2021 |
| LG Electro... | 14Z90N-VA76K                | Notebook    | [df36a7a61c](https://linux-hardware.org/?probe=df36a7a61c) | Aug 22, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [3abd60af90](https://linux-hardware.org/?probe=3abd60af90) | Aug 22, 2021 |
| Lenovo        | XiaoXin Air 13IWL 81J8      | Notebook    | [e68dfe0824](https://linux-hardware.org/?probe=e68dfe0824) | Aug 19, 2021 |
| Apple         | MacBookPro15,2              | Notebook    | [c722c00c56](https://linux-hardware.org/?probe=c722c00c56) | Aug 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e47beb0587](https://linux-hardware.org/?probe=e47beb0587) | Aug 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e7997203d4](https://linux-hardware.org/?probe=e7997203d4) | Aug 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [3147760301](https://linux-hardware.org/?probe=3147760301) | Aug 07, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [e523ad86d2](https://linux-hardware.org/?probe=e523ad86d2) | Aug 02, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [1e96b02bf3](https://linux-hardware.org/?probe=1e96b02bf3) | Jul 28, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [dc6d809e73](https://linux-hardware.org/?probe=dc6d809e73) | Jul 23, 2021 |
| LG Electro... | 17UD70P-PX76K               | Notebook    | [c0869b1919](https://linux-hardware.org/?probe=c0869b1919) | Jul 23, 2021 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [972c061d3c](https://linux-hardware.org/?probe=972c061d3c) | Jul 22, 2021 |
| Gigabyte      | Z390 D                      | Desktop     | [8bf86066a5](https://linux-hardware.org/?probe=8bf86066a5) | Jul 22, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4c15433f48](https://linux-hardware.org/?probe=4c15433f48) | Jul 21, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [2392366002](https://linux-hardware.org/?probe=2392366002) | Jul 16, 2021 |
| Dell          | 04WYPY A04                  | Server      | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | 3397                        | Desktop     | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae45f90535](https://linux-hardware.org/?probe=ae45f90535) | Jul 05, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| Lenovo        | 14ARE05 81X2                | Convertible | [3cd1b703c4](https://linux-hardware.org/?probe=3cd1b703c4) | Jun 28, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| ASRockRack    | WC621D8A-2T                 | Desktop     | [d9c47162dc](https://linux-hardware.org/?probe=d9c47162dc) | Jun 25, 2021 |
| ASRockRack    | WC621D8A-2T                 | Desktop     | [b568edaa5e](https://linux-hardware.org/?probe=b568edaa5e) | Jun 25, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [9c2b77b3c6](https://linux-hardware.org/?probe=9c2b77b3c6) | Jun 24, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [99b25335b3](https://linux-hardware.org/?probe=99b25335b3) | Jun 22, 2021 |
| WB            | J3160                       | All in one  | [88c472d69e](https://linux-hardware.org/?probe=88c472d69e) | Jun 18, 2021 |
| WB            | J3160                       | All in one  | [b889890a54](https://linux-hardware.org/?probe=b889890a54) | Jun 11, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [98faadcfa3](https://linux-hardware.org/?probe=98faadcfa3) | Jun 10, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a19b25100c](https://linux-hardware.org/?probe=a19b25100c) | Jun 08, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [9aaad9b2d4](https://linux-hardware.org/?probe=9aaad9b2d4) | Jun 07, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [be07a70b2e](https://linux-hardware.org/?probe=be07a70b2e) | May 27, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [2aca6cd805](https://linux-hardware.org/?probe=2aca6cd805) | May 27, 2021 |
| Dell          | Latitude E6400              | Notebook    | [2a4c5f6eec](https://linux-hardware.org/?probe=2a4c5f6eec) | May 25, 2021 |
| Samsung       | R440/R480                   | Notebook    | [777c05d80b](https://linux-hardware.org/?probe=777c05d80b) | May 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [15a742842f](https://linux-hardware.org/?probe=15a742842f) | May 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f3cb68f8cf](https://linux-hardware.org/?probe=f3cb68f8cf) | May 13, 2021 |
| HP            | EliteBook 8540p (WQ983PA... | Notebook    | [28b1df49ae](https://linux-hardware.org/?probe=28b1df49ae) | May 11, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [3d6a52dd8e](https://linux-hardware.org/?probe=3d6a52dd8e) | May 11, 2021 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [a9245eb585](https://linux-hardware.org/?probe=a9245eb585) | May 11, 2021 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [965bc51c8d](https://linux-hardware.org/?probe=965bc51c8d) | May 06, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [035481a413](https://linux-hardware.org/?probe=035481a413) | May 05, 2021 |
| ASRock        | A75M-ITX                    | Desktop     | [1ad3e30eec](https://linux-hardware.org/?probe=1ad3e30eec) | May 03, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [473f17b0f1](https://linux-hardware.org/?probe=473f17b0f1) | May 01, 2021 |
| LG Electro... | 15ND530-GX30K               | Notebook    | [9d700ce0b6](https://linux-hardware.org/?probe=9d700ce0b6) | Apr 30, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [84f31a5fd7](https://linux-hardware.org/?probe=84f31a5fd7) | Apr 28, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [167aa11de4](https://linux-hardware.org/?probe=167aa11de4) | Apr 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [72d14b2ed7](https://linux-hardware.org/?probe=72d14b2ed7) | Apr 23, 2021 |
| Lenovo        | ThinkPad Edge E145 20BC0... | Notebook    | [410e4fd232](https://linux-hardware.org/?probe=410e4fd232) | Apr 22, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2300013263](https://linux-hardware.org/?probe=2300013263) | Apr 18, 2021 |
| HP            | Stream Notebook PC 13       | Notebook    | [0bf3f6f761](https://linux-hardware.org/?probe=0bf3f6f761) | Apr 15, 2021 |
| ASRock        | FM2A88M-HD+ R2.0            | Desktop     | [fdac2fa1fd](https://linux-hardware.org/?probe=fdac2fa1fd) | Apr 14, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [b17bb9b31a](https://linux-hardware.org/?probe=b17bb9b31a) | Apr 12, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a0686a3f62](https://linux-hardware.org/?probe=a0686a3f62) | Apr 11, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e77253d59](https://linux-hardware.org/?probe=7e77253d59) | Apr 11, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [c5e7a3d16e](https://linux-hardware.org/?probe=c5e7a3d16e) | Apr 09, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [7cac175bde](https://linux-hardware.org/?probe=7cac175bde) | Apr 07, 2021 |
| Gigabyte      | 945GCMX-S2                  | Desktop     | [d4399ab9d0](https://linux-hardware.org/?probe=d4399ab9d0) | Apr 06, 2021 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [51931e3821](https://linux-hardware.org/?probe=51931e3821) | Apr 05, 2021 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [b36716f462](https://linux-hardware.org/?probe=b36716f462) | Apr 02, 2021 |
| Samsung       | 400B4B/400B5B/200B4B/200... | Notebook    | [af785987c5](https://linux-hardware.org/?probe=af785987c5) | Mar 29, 2021 |
| LG Electro... | Z435-GE40K                  | Notebook    | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Lenovo        | ThinkPad 10 20C1001VKR      | Tablet      | [9b7a2a3d3b](https://linux-hardware.org/?probe=9b7a2a3d3b) | Mar 25, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [b55dc75624](https://linux-hardware.org/?probe=b55dc75624) | Mar 20, 2021 |
| Gigabyte      | B360M DS3H                  | Desktop     | [f7740321e0](https://linux-hardware.org/?probe=f7740321e0) | Mar 18, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [e459ded47c](https://linux-hardware.org/?probe=e459ded47c) | Mar 10, 2021 |
| Alienware     | m15 R4                      | Notebook    | [33977ceca8](https://linux-hardware.org/?probe=33977ceca8) | Mar 08, 2021 |
| Notebook      | W330SU2                     | Notebook    | [e5e71a4e94](https://linux-hardware.org/?probe=e5e71a4e94) | Mar 05, 2021 |
| Dell          | Inspiron 5590               | Notebook    | [94e3d38a99](https://linux-hardware.org/?probe=94e3d38a99) | Mar 04, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [15c42588c8](https://linux-hardware.org/?probe=15c42588c8) | Mar 04, 2021 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [541a436664](https://linux-hardware.org/?probe=541a436664) | Mar 02, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [8e6128682d](https://linux-hardware.org/?probe=8e6128682d) | Feb 28, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [778fcc3093](https://linux-hardware.org/?probe=778fcc3093) | Feb 28, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8dd1ebdfb8](https://linux-hardware.org/?probe=8dd1ebdfb8) | Feb 25, 2021 |
| Notebook      | N650DU                      | Notebook    | [beef9a4540](https://linux-hardware.org/?probe=beef9a4540) | Feb 24, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [7ffa9ae08a](https://linux-hardware.org/?probe=7ffa9ae08a) | Feb 17, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a222f11ebf](https://linux-hardware.org/?probe=a222f11ebf) | Feb 09, 2021 |
| ECS           | PB02CF                      | Server      | [598d43b1f2](https://linux-hardware.org/?probe=598d43b1f2) | Feb 08, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [0de61d3d11](https://linux-hardware.org/?probe=0de61d3d11) | Feb 06, 2021 |
| ASUSTek       | Z170-A                      | Desktop     | [65aa2efd23](https://linux-hardware.org/?probe=65aa2efd23) | Feb 05, 2021 |
| ASRock        | H110M-HDVP2                 | Desktop     | [27d324f7e1](https://linux-hardware.org/?probe=27d324f7e1) | Feb 04, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [fc703c19dd](https://linux-hardware.org/?probe=fc703c19dd) | Feb 02, 2021 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [ba5f1e074b](https://linux-hardware.org/?probe=ba5f1e074b) | Feb 02, 2021 |
| MSI           | B360M PRO-VDH               | Desktop     | [59b7bd58df](https://linux-hardware.org/?probe=59b7bd58df) | Jan 30, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [a29449d114](https://linux-hardware.org/?probe=a29449d114) | Jan 27, 2021 |
| ECS           | PB02CF                      | Server      | [4c644b0fa9](https://linux-hardware.org/?probe=4c644b0fa9) | Jan 26, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [9595d4107b](https://linux-hardware.org/?probe=9595d4107b) | Jan 26, 2021 |
| sunxi         | Unknown                     | Soc         | [49e15041c4](https://linux-hardware.org/?probe=49e15041c4) | Jan 26, 2021 |
| HP            | Pavilion dv3                | Notebook    | [d563465019](https://linux-hardware.org/?probe=d563465019) | Jan 23, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a6226b7401](https://linux-hardware.org/?probe=a6226b7401) | Jan 20, 2021 |
| HP            | Pavilion dv3                | Notebook    | [7140d63f79](https://linux-hardware.org/?probe=7140d63f79) | Jan 16, 2021 |
| LG Electro... | 13Z940-MF6BL                | Notebook    | [ee9f312333](https://linux-hardware.org/?probe=ee9f312333) | Jan 16, 2021 |
| ECS           | PB02CF                      | Server      | [79ed88ad12](https://linux-hardware.org/?probe=79ed88ad12) | Jan 13, 2021 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [ffa2d06213](https://linux-hardware.org/?probe=ffa2d06213) | Jan 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [28d2ddf944](https://linux-hardware.org/?probe=28d2ddf944) | Jan 04, 2021 |
| HP            | 18E7                        | Desktop     | [e9590ba71a](https://linux-hardware.org/?probe=e9590ba71a) | Jan 01, 2021 |
| LG Electro... | 10T370-L860K                | Tablet      | [a6ab074bb5](https://linux-hardware.org/?probe=a6ab074bb5) | Jan 01, 2021 |
| LG Electro... | 10T370-L860K                | Tablet      | [7a21765d3b](https://linux-hardware.org/?probe=7a21765d3b) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming FA706II_FA706... | Notebook    | [cbc872e471](https://linux-hardware.org/?probe=cbc872e471) | Dec 29, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [4f038027ac](https://linux-hardware.org/?probe=4f038027ac) | Dec 27, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [659c45927e](https://linux-hardware.org/?probe=659c45927e) | Dec 26, 2020 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [deb549d3e1](https://linux-hardware.org/?probe=deb549d3e1) | Dec 21, 2020 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4245e53af4](https://linux-hardware.org/?probe=4245e53af4) | Dec 20, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [77ad294d93](https://linux-hardware.org/?probe=77ad294d93) | Dec 20, 2020 |
| HP            | Pavilion g6                 | Notebook    | [9b2e1ccb17](https://linux-hardware.org/?probe=9b2e1ccb17) | Dec 15, 2020 |
| HP            | Pavilion g6                 | Notebook    | [01bd113f0d](https://linux-hardware.org/?probe=01bd113f0d) | Dec 15, 2020 |
| MSI           | PS42 Modern 8MO             | Notebook    | [c469679bd0](https://linux-hardware.org/?probe=c469679bd0) | Dec 14, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [ae9a14bb34](https://linux-hardware.org/?probe=ae9a14bb34) | Dec 11, 2020 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [9ff7890a24](https://linux-hardware.org/?probe=9ff7890a24) | Dec 11, 2020 |
| Gigabyte      | C621-SU8 M18818             | Server      | [7e93e1b694](https://linux-hardware.org/?probe=7e93e1b694) | Dec 11, 2020 |
| Gigabyte      | C621-SU8 M18818             | Server      | [6343846b09](https://linux-hardware.org/?probe=6343846b09) | Dec 11, 2020 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [b1476b4c51](https://linux-hardware.org/?probe=b1476b4c51) | Dec 09, 2020 |
| Samsung       | 760XBE                      | Notebook    | [7b117d1e93](https://linux-hardware.org/?probe=7b117d1e93) | Dec 08, 2020 |
| Samsung       | R440/R480                   | Notebook    | [2c57659a41](https://linux-hardware.org/?probe=2c57659a41) | Dec 06, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [a706242b44](https://linux-hardware.org/?probe=a706242b44) | Dec 05, 2020 |
| MSI           | B360M PRO-VDH               | Desktop     | [f16f5d30de](https://linux-hardware.org/?probe=f16f5d30de) | Dec 05, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [425fda9034](https://linux-hardware.org/?probe=425fda9034) | Dec 04, 2020 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [e6f9b2cf07](https://linux-hardware.org/?probe=e6f9b2cf07) | Dec 04, 2020 |
| Acer          | Swift SF314-54              | Notebook    | [e387afac15](https://linux-hardware.org/?probe=e387afac15) | Nov 29, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| Apple         | MacBookPro10,1              | Notebook    | [ecfaa7232b](https://linux-hardware.org/?probe=ecfaa7232b) | Nov 28, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [eb842cd3c4](https://linux-hardware.org/?probe=eb842cd3c4) | Nov 25, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [2a9cc167d3](https://linux-hardware.org/?probe=2a9cc167d3) | Nov 25, 2020 |
| ASRock        | B85M Pro4                   | Desktop     | [0354f4d9bc](https://linux-hardware.org/?probe=0354f4d9bc) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| ASRock        | B85M Pro4                   | Desktop     | [8dcc7ce213](https://linux-hardware.org/?probe=8dcc7ce213) | Nov 22, 2020 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f9b97f5918](https://linux-hardware.org/?probe=f9b97f5918) | Nov 22, 2020 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [e4a465ff4c](https://linux-hardware.org/?probe=e4a465ff4c) | Nov 15, 2020 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [8a39cadb17](https://linux-hardware.org/?probe=8a39cadb17) | Nov 14, 2020 |
| ECS           | G31T-M7                     | Desktop     | [f93ce4415e](https://linux-hardware.org/?probe=f93ce4415e) | Nov 12, 2020 |
| PC Partner... | A236 0A                     | Desktop     | [14030da2e5](https://linux-hardware.org/?probe=14030da2e5) | Nov 10, 2020 |
| PC Partner... | A236 0A                     | Desktop     | [fc118d784c](https://linux-hardware.org/?probe=fc118d784c) | Nov 10, 2020 |
| ASUSTek       | P7P55D                      | Desktop     | [11e315efbd](https://linux-hardware.org/?probe=11e315efbd) | Nov 07, 2020 |
| Samsung       | SX11S                       | Notebook    | [7946db3be4](https://linux-hardware.org/?probe=7946db3be4) | Nov 05, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [9b33944102](https://linux-hardware.org/?probe=9b33944102) | Nov 04, 2020 |
| Samsung       | 930QAA                      | Convertible | [ed50ef80ea](https://linux-hardware.org/?probe=ed50ef80ea) | Nov 01, 2020 |
| Lenovo        | ThinkPad T580 20L9S06H00    | Notebook    | [4cda554e60](https://linux-hardware.org/?probe=4cda554e60) | Oct 31, 2020 |
| Samsung       | 930QAA                      | Convertible | [e0defd416b](https://linux-hardware.org/?probe=e0defd416b) | Oct 31, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [7184b7e890](https://linux-hardware.org/?probe=7184b7e890) | Oct 29, 2020 |
| HANSUNG CO... | TFX5470H                    | Notebook    | [7a0c7ef25d](https://linux-hardware.org/?probe=7a0c7ef25d) | Oct 22, 2020 |
| ECS           | PB02CF                      | Server      | [d2a218790a](https://linux-hardware.org/?probe=d2a218790a) | Oct 18, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [39cc53a5e3](https://linux-hardware.org/?probe=39cc53a5e3) | Oct 13, 2020 |
| ECS           | PB02CF                      | Server      | [872240bfee](https://linux-hardware.org/?probe=872240bfee) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [57c9a2fdbb](https://linux-hardware.org/?probe=57c9a2fdbb) | Oct 12, 2020 |
| Acer          | Aspire A514-52              | Notebook    | [151c57e477](https://linux-hardware.org/?probe=151c57e477) | Oct 11, 2020 |
| ECS           | PB02CF                      | Server      | [ee5e0d54ac](https://linux-hardware.org/?probe=ee5e0d54ac) | Oct 10, 2020 |
| ECS           | PB02CF                      | Server      | [2584572329](https://linux-hardware.org/?probe=2584572329) | Oct 10, 2020 |
| ECS           | PB02CF                      | Server      | [9ff606fe05](https://linux-hardware.org/?probe=9ff606fe05) | Oct 09, 2020 |
| Lenovo        | ThinkPad E595 20NFS01P00    | Notebook    | [5cce7e56d5](https://linux-hardware.org/?probe=5cce7e56d5) | Oct 02, 2020 |
| MSI           | MS-16F1                     | Notebook    | [94a744ecb7](https://linux-hardware.org/?probe=94a744ecb7) | Oct 01, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [3aba059c2c](https://linux-hardware.org/?probe=3aba059c2c) | Sep 24, 2020 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [c535500f86](https://linux-hardware.org/?probe=c535500f86) | Sep 24, 2020 |
| ASRock        | H310M-STX/COM               | Desktop     | [5b22b538ee](https://linux-hardware.org/?probe=5b22b538ee) | Sep 23, 2020 |
| MSI           | GE75 Raider 10SF            | Notebook    | [c5f31d8ff8](https://linux-hardware.org/?probe=c5f31d8ff8) | Sep 21, 2020 |
| MSI           | GE75 Raider 10SF            | Notebook    | [80b54a584c](https://linux-hardware.org/?probe=80b54a584c) | Sep 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [335490808b](https://linux-hardware.org/?probe=335490808b) | Sep 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [611b4d4515](https://linux-hardware.org/?probe=611b4d4515) | Sep 12, 2020 |
| Samsung       | SX11S                       | Notebook    | [de5f3f5244](https://linux-hardware.org/?probe=de5f3f5244) | Sep 10, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [56efa94b22](https://linux-hardware.org/?probe=56efa94b22) | Sep 09, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [00f5eba2ea](https://linux-hardware.org/?probe=00f5eba2ea) | Sep 09, 2020 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [e9eb75e83c](https://linux-hardware.org/?probe=e9eb75e83c) | Sep 09, 2020 |
| Gigabyte      | B75M-D3H                    | Desktop     | [934bb9c2ef](https://linux-hardware.org/?probe=934bb9c2ef) | Sep 09, 2020 |
| ASRock        | H310CM-HDV                  | Desktop     | [7acf41575b](https://linux-hardware.org/?probe=7acf41575b) | Sep 09, 2020 |
| ASRock        | H81M-HDS                    | Desktop     | [8b55873fbd](https://linux-hardware.org/?probe=8b55873fbd) | Sep 07, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [0ed21172b2](https://linux-hardware.org/?probe=0ed21172b2) | Sep 07, 2020 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [56e8c74784](https://linux-hardware.org/?probe=56e8c74784) | Sep 05, 2020 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [5b29fd8262](https://linux-hardware.org/?probe=5b29fd8262) | Sep 05, 2020 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [226702f09a](https://linux-hardware.org/?probe=226702f09a) | Sep 05, 2020 |
| LG Electro... | 15ND530-GX30K               | Notebook    | [8f8a5ce10c](https://linux-hardware.org/?probe=8f8a5ce10c) | Sep 04, 2020 |
| Foxconn       | H61MXE                      | Desktop     | [7a31014e98](https://linux-hardware.org/?probe=7a31014e98) | Sep 04, 2020 |
| ECS           | PB02CF                      | Server      | [4d441244a7](https://linux-hardware.org/?probe=4d441244a7) | Sep 03, 2020 |
| Lenovo        | ThinkPad X390 20SCCTO1WW    | Notebook    | [765a0cde4c](https://linux-hardware.org/?probe=765a0cde4c) | Sep 03, 2020 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2ef3a6b6c8](https://linux-hardware.org/?probe=2ef3a6b6c8) | Sep 03, 2020 |
| Acer          | Swift SF315-41              | Notebook    | [c57a2c8249](https://linux-hardware.org/?probe=c57a2c8249) | Aug 26, 2020 |
| LG Electro... | A520-DEHRK                  | Notebook    | [33e6f6950c](https://linux-hardware.org/?probe=33e6f6950c) | Aug 20, 2020 |
| LG Electro... | ZD360-GD30K                 | Notebook    | [5f695a5cfd](https://linux-hardware.org/?probe=5f695a5cfd) | Aug 19, 2020 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [4eb75f039b](https://linux-hardware.org/?probe=4eb75f039b) | Aug 17, 2020 |
| Lenovo        | ThinkPad L420 7829AZ2       | Notebook    | [af5c485d91](https://linux-hardware.org/?probe=af5c485d91) | Aug 17, 2020 |
| ASUSTek       | UX31E                       | Notebook    | [107d53bd73](https://linux-hardware.org/?probe=107d53bd73) | Aug 14, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | Notebook    | [e2a554e507](https://linux-hardware.org/?probe=e2a554e507) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [4657a3e758](https://linux-hardware.org/?probe=4657a3e758) | Aug 11, 2020 |
| Lenovo        | ThinkPad T420s 417429U      | Notebook    | [a0cc9e062e](https://linux-hardware.org/?probe=a0cc9e062e) | Aug 09, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [dabfcf887e](https://linux-hardware.org/?probe=dabfcf887e) | Aug 05, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [806b0f6ffc](https://linux-hardware.org/?probe=806b0f6ffc) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [03dcb81800](https://linux-hardware.org/?probe=03dcb81800) | Aug 04, 2020 |
| Nvidia        | Tegra                       | Soc         | [db3eb249a1](https://linux-hardware.org/?probe=db3eb249a1) | Aug 02, 2020 |
| Nvidia        | Tegra                       | Soc         | [ce759d1ef8](https://linux-hardware.org/?probe=ce759d1ef8) | Aug 02, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [953e68f29d](https://linux-hardware.org/?probe=953e68f29d) | Jul 29, 2020 |
| ASRock        | H61M-HVGS                   | Desktop     | [36c19012ed](https://linux-hardware.org/?probe=36c19012ed) | Jul 25, 2020 |
| ASRock        | H61M-HVGS                   | Desktop     | [ea9287adc1](https://linux-hardware.org/?probe=ea9287adc1) | Jul 25, 2020 |
| Samsung       | X120/X170/X171              | Notebook    | [d52c424e0f](https://linux-hardware.org/?probe=d52c424e0f) | Jul 12, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [1f2f8bb2cf](https://linux-hardware.org/?probe=1f2f8bb2cf) | Jul 06, 2020 |
| MSI           | PS63 Modern 8RC             | Notebook    | [ed2dc1f4eb](https://linux-hardware.org/?probe=ed2dc1f4eb) | Jul 05, 2020 |
| Sony          | SVF1421ESGW                 | Notebook    | [025b1a05fe](https://linux-hardware.org/?probe=025b1a05fe) | Jun 29, 2020 |
| ASRock        | Z390 Taichi                 | Desktop     | [ce94a11d8b](https://linux-hardware.org/?probe=ce94a11d8b) | Jun 26, 2020 |
| Huanan        | X99-F8                      | Desktop     | [74f9976527](https://linux-hardware.org/?probe=74f9976527) | Jun 25, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [cbd4390e56](https://linux-hardware.org/?probe=cbd4390e56) | Jun 23, 2020 |
| ASUSTek       | X553SA                      | Notebook    | [de56d8fe26](https://linux-hardware.org/?probe=de56d8fe26) | Jun 23, 2020 |
| ASRock        | Z390 Taichi                 | Desktop     | [6989759d9c](https://linux-hardware.org/?probe=6989759d9c) | Jun 21, 2020 |
| ASRock        | Z390M Pro4                  | Desktop     | [eb53bb80ea](https://linux-hardware.org/?probe=eb53bb80ea) | Jun 20, 2020 |
| ECS           | H81H3-MV                    | Desktop     | [d39e7a605d](https://linux-hardware.org/?probe=d39e7a605d) | Jun 20, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [c05f965fec](https://linux-hardware.org/?probe=c05f965fec) | Jun 17, 2020 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [835aa152dd](https://linux-hardware.org/?probe=835aa152dd) | Jun 16, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [41702d8f8c](https://linux-hardware.org/?probe=41702d8f8c) | Jun 14, 2020 |
| MSI           | GX60 3CC                    | Notebook    | [16345ce4e3](https://linux-hardware.org/?probe=16345ce4e3) | Jun 14, 2020 |
| TG            | NXI-A7000 Series            | Notebook    | [20018e6c2a](https://linux-hardware.org/?probe=20018e6c2a) | Jun 07, 2020 |
| Dell          | G3 3579                     | Notebook    | [f21ec2528f](https://linux-hardware.org/?probe=f21ec2528f) | Jun 06, 2020 |
| ECS           | PB02CF                      | Server      | [e4fe65609d](https://linux-hardware.org/?probe=e4fe65609d) | May 28, 2020 |
| ECS           | PB02CF                      | Server      | [277941a55d](https://linux-hardware.org/?probe=277941a55d) | May 27, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | Notebook    | [bd7072c5e9](https://linux-hardware.org/?probe=bd7072c5e9) | May 27, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [229612b5fa](https://linux-hardware.org/?probe=229612b5fa) | May 26, 2020 |
| LG Electro... | 17UD790-PX76K               | Notebook    | [ac4f8e9cc6](https://linux-hardware.org/?probe=ac4f8e9cc6) | May 24, 2020 |
| LG Electro... | 17UD790-PX76K               | Notebook    | [9bb4fea940](https://linux-hardware.org/?probe=9bb4fea940) | May 24, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [65f85ef8e9](https://linux-hardware.org/?probe=65f85ef8e9) | May 20, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [b3a561d5db](https://linux-hardware.org/?probe=b3a561d5db) | May 20, 2020 |
| Unknown       | Unknown                     | Desktop     | [e6e0a356a2](https://linux-hardware.org/?probe=e6e0a356a2) | May 19, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [69c9f3bce6](https://linux-hardware.org/?probe=69c9f3bce6) | May 17, 2020 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [e526204afd](https://linux-hardware.org/?probe=e526204afd) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | Notebook    | [435579b481](https://linux-hardware.org/?probe=435579b481) | May 16, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [24ce1a41e9](https://linux-hardware.org/?probe=24ce1a41e9) | May 16, 2020 |
| Samsung       | 570Z5E/580Z5E               | Notebook    | [5e2ed0ac77](https://linux-hardware.org/?probe=5e2ed0ac77) | May 16, 2020 |
| LG Electro... | 14ZB990-GP70ML              | Notebook    | [dc05f2344d](https://linux-hardware.org/?probe=dc05f2344d) | May 16, 2020 |
| Lenovo        | ThinkPad 8 20BNA00GKR       | Tablet      | [344a9c1bfa](https://linux-hardware.org/?probe=344a9c1bfa) | May 14, 2020 |
| HP            | 158A                        | Desktop     | [344194646f](https://linux-hardware.org/?probe=344194646f) | May 14, 2020 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [5919a15425](https://linux-hardware.org/?probe=5919a15425) | May 11, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [d5b8f91a79](https://linux-hardware.org/?probe=d5b8f91a79) | May 10, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [c259824b35](https://linux-hardware.org/?probe=c259824b35) | May 09, 2020 |
| ASRock        | X470 Taichi                 | Desktop     | [261241bb2f](https://linux-hardware.org/?probe=261241bb2f) | May 07, 2020 |
| Biostar       | H61MH                       | Desktop     | [aacc6bcb68](https://linux-hardware.org/?probe=aacc6bcb68) | May 07, 2020 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [36cbf906a0](https://linux-hardware.org/?probe=36cbf906a0) | May 07, 2020 |
| Lenovo        | ThinkPad X220 4290P39       | Notebook    | [1b5c469306](https://linux-hardware.org/?probe=1b5c469306) | May 02, 2020 |
| Gigabyte      | B75M-D3V                    | Desktop     | [a4130d0549](https://linux-hardware.org/?probe=a4130d0549) | Apr 29, 2020 |
| ASRock        | G31M-S                      | Desktop     | [6a55997759](https://linux-hardware.org/?probe=6a55997759) | Apr 28, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [0bbf773840](https://linux-hardware.org/?probe=0bbf773840) | Apr 27, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [5348bea534](https://linux-hardware.org/?probe=5348bea534) | Apr 27, 2020 |
| Lenovo        | ThinkPad X230 2325KZ5       | Notebook    | [150d9801f0](https://linux-hardware.org/?probe=150d9801f0) | Apr 21, 2020 |
| ASUSTek       | B85M-G                      | Desktop     | [5d58ef4cec](https://linux-hardware.org/?probe=5d58ef4cec) | Apr 19, 2020 |
| Lenovo        | ThinkPad E495 20NES0WU00    | Notebook    | [fb49bbe9f1](https://linux-hardware.org/?probe=fb49bbe9f1) | Apr 18, 2020 |
| Lenovo        | ThinkPad 8 20BNA00GKR       | Tablet      | [aa72454483](https://linux-hardware.org/?probe=aa72454483) | Apr 16, 2020 |
| Dell          | Latitude D630               | Notebook    | [0540c0a191](https://linux-hardware.org/?probe=0540c0a191) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [4d5a5a3a34](https://linux-hardware.org/?probe=4d5a5a3a34) | Apr 14, 2020 |
| MSI           | B250M PRO-VD                | Desktop     | [d797379451](https://linux-hardware.org/?probe=d797379451) | Apr 13, 2020 |
| LG Electro... | 15U340-LT1FK                | Tablet      | [b78bd157c9](https://linux-hardware.org/?probe=b78bd157c9) | Apr 12, 2020 |
| LG Electro... | 15U340-LT1FK                | Tablet      | [29cad9bafb](https://linux-hardware.org/?probe=29cad9bafb) | Apr 12, 2020 |
| Gigabyte      | TRX40 AORUS XTREME          | Desktop     | [0f078bd16f](https://linux-hardware.org/?probe=0f078bd16f) | Apr 11, 2020 |
| Dell          | 0Y2MRG A01                  | Desktop     | [053b33bcbc](https://linux-hardware.org/?probe=053b33bcbc) | Apr 05, 2020 |
| ASUSTek       | P5K                         | Desktop     | [8ec1f94a9f](https://linux-hardware.org/?probe=8ec1f94a9f) | Apr 05, 2020 |
| ASUSTek       | H110M-F                     | Desktop     | [c5861fb518](https://linux-hardware.org/?probe=c5861fb518) | Mar 31, 2020 |
| LG Electro... | R490-KR6WK                  | Notebook    | [b0c23e23f7](https://linux-hardware.org/?probe=b0c23e23f7) | Mar 21, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [c54c1dcc2f](https://linux-hardware.org/?probe=c54c1dcc2f) | Mar 18, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [de7d898371](https://linux-hardware.org/?probe=de7d898371) | Mar 16, 2020 |
| Hanis         | Rugged86H                   | Tablet      | [f85527148f](https://linux-hardware.org/?probe=f85527148f) | Mar 16, 2020 |
| Hanis         | Rugged86H                   | Tablet      | [9526ed2d93](https://linux-hardware.org/?probe=9526ed2d93) | Mar 16, 2020 |
| ECS           | PB02CF                      | Server      | [68979eba8f](https://linux-hardware.org/?probe=68979eba8f) | Mar 15, 2020 |
| ECS           | PB02CF                      | Server      | [351516c86f](https://linux-hardware.org/?probe=351516c86f) | Mar 14, 2020 |
| ECS           | PB02CF                      | Server      | [fc1afc7ed7](https://linux-hardware.org/?probe=fc1afc7ed7) | Mar 12, 2020 |
| HP            | Pavilion dv7                | Notebook    | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| ECS           | PB02CF                      | Server      | [9d62420812](https://linux-hardware.org/?probe=9d62420812) | Mar 09, 2020 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [b5def2acfb](https://linux-hardware.org/?probe=b5def2acfb) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [ca363a8ddc](https://linux-hardware.org/?probe=ca363a8ddc) | Mar 03, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [2b56d27ead](https://linux-hardware.org/?probe=2b56d27ead) | Mar 02, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [8b42886c6f](https://linux-hardware.org/?probe=8b42886c6f) | Mar 02, 2020 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [fd4e08618e](https://linux-hardware.org/?probe=fd4e08618e) | Feb 28, 2020 |
| ECS           | PB02CF                      | Server      | [8553d515a9](https://linux-hardware.org/?probe=8553d515a9) | Feb 27, 2020 |
| LG Electro... | A505-K.AFC4L                | Notebook    | [33b72b423b](https://linux-hardware.org/?probe=33b72b423b) | Feb 26, 2020 |
| ECS           | PB02CF                      | Server      | [7b029b9193](https://linux-hardware.org/?probe=7b029b9193) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [82e1b966c4](https://linux-hardware.org/?probe=82e1b966c4) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [c81fd255b8](https://linux-hardware.org/?probe=c81fd255b8) | Feb 25, 2020 |
| ECS           | PB02CF                      | Server      | [855276d27c](https://linux-hardware.org/?probe=855276d27c) | Feb 22, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [8212e2eb65](https://linux-hardware.org/?probe=8212e2eb65) | Feb 13, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [00af81dd32](https://linux-hardware.org/?probe=00af81dd32) | Feb 12, 2020 |
| MSI           | Prestige 14 A10SC           | Notebook    | [dac2e1709e](https://linux-hardware.org/?probe=dac2e1709e) | Feb 12, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [9496a3ac2c](https://linux-hardware.org/?probe=9496a3ac2c) | Feb 10, 2020 |
| LattePanda    | Alpha                       | Desktop     | [eb27db2005](https://linux-hardware.org/?probe=eb27db2005) | Feb 01, 2020 |
| LattePanda    | Alpha                       | Desktop     | [72a1cd44a0](https://linux-hardware.org/?probe=72a1cd44a0) | Feb 01, 2020 |
| MSI           | GF63 Thin 9SC               | Notebook    | [47b9bc192c](https://linux-hardware.org/?probe=47b9bc192c) | Jan 29, 2020 |
| Nvidia        | Tegra                       | Soc         | [7d929b52dc](https://linux-hardware.org/?probe=7d929b52dc) | Jan 29, 2020 |
| MSI           | GF63 Thin 9SC               | Notebook    | [21dbcd5aca](https://linux-hardware.org/?probe=21dbcd5aca) | Jan 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [6515ce1c97](https://linux-hardware.org/?probe=6515ce1c97) | Jan 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [3f4a3ca42f](https://linux-hardware.org/?probe=3f4a3ca42f) | Jan 19, 2020 |
| MSI           | B350M MORTAR                | Desktop     | [f53a75b96e](https://linux-hardware.org/?probe=f53a75b96e) | Jan 10, 2020 |
| ASUSTek       | P5B-PLUS Series             | Desktop     | [b0a90d8478](https://linux-hardware.org/?probe=b0a90d8478) | Jan 02, 2020 |
| HP            | ProBook 453                 | Notebook    | [ad3d1ff0fc](https://linux-hardware.org/?probe=ad3d1ff0fc) | Dec 27, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2fb35125e3](https://linux-hardware.org/?probe=2fb35125e3) | Dec 22, 2019 |
| Lenovo        | ThinkPad E565 20EYA007KD    | Notebook    | [c1c9dd614a](https://linux-hardware.org/?probe=c1c9dd614a) | Dec 17, 2019 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [61765ee913](https://linux-hardware.org/?probe=61765ee913) | Dec 11, 2019 |
| HP            | Laptop 14s-cf1xxx           | Notebook    | [fa008b24fc](https://linux-hardware.org/?probe=fa008b24fc) | Dec 11, 2019 |
| Gigabyte      | 945GM-S2                    | Desktop     | [c6b23ec021](https://linux-hardware.org/?probe=c6b23ec021) | Dec 07, 2019 |
| HP            | Pavilion 15                 | Notebook    | [5f9b510e87](https://linux-hardware.org/?probe=5f9b510e87) | Oct 28, 2019 |
| ECS           | H81H3-M4                    | Desktop     | [2a11653db0](https://linux-hardware.org/?probe=2a11653db0) | Oct 05, 2019 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [37c348afcc](https://linux-hardware.org/?probe=37c348afcc) | Sep 11, 2019 |
| MSI           | MS-1675                     | Notebook    | [c5bf6f209a](https://linux-hardware.org/?probe=c5bf6f209a) | Sep 07, 2019 |
| MSI           | MS-1675                     | Notebook    | [be1db420ea](https://linux-hardware.org/?probe=be1db420ea) | Sep 07, 2019 |
| Hanis         | RuggedPadY16                | Tablet      | [70f839c5cb](https://linux-hardware.org/?probe=70f839c5cb) | Sep 04, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [caaebe3071](https://linux-hardware.org/?probe=caaebe3071) | Sep 01, 2019 |
| AMI           | Cherry Trail CR             | Notebook    | [5637a7d5ca](https://linux-hardware.org/?probe=5637a7d5ca) | Sep 01, 2019 |
| ASUSTek       | T101HA                      | Tablet      | [b08e9c4371](https://linux-hardware.org/?probe=b08e9c4371) | Aug 31, 2019 |
| Lenovo        | U41-70 80JV                 | Notebook    | [0af65c15a0](https://linux-hardware.org/?probe=0af65c15a0) | Aug 30, 2019 |
| ECS           | G41T-M6                     | Desktop     | [91cafa3b5b](https://linux-hardware.org/?probe=91cafa3b5b) | Aug 30, 2019 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [68069aeff1](https://linux-hardware.org/?probe=68069aeff1) | Aug 21, 2019 |
| IMUZ          | StormBook 15                | Notebook    | [daf3b9ea48](https://linux-hardware.org/?probe=daf3b9ea48) | Aug 07, 2019 |
| Supermicro    | X11DPG-OT-CPU               | Server      | [8e73f804f5](https://linux-hardware.org/?probe=8e73f804f5) | Jul 16, 2019 |
| ASRock        | Z390 Extreme4               | Desktop     | [8c8af8b557](https://linux-hardware.org/?probe=8c8af8b557) | Jul 13, 2019 |
| ASRock        | AB350M Pro4                 | Desktop     | [88354e515f](https://linux-hardware.org/?probe=88354e515f) | Jul 08, 2019 |
| ASRock        | AB350M Pro4                 | Desktop     | [7506cb2993](https://linux-hardware.org/?probe=7506cb2993) | Jul 08, 2019 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [727b2b7099](https://linux-hardware.org/?probe=727b2b7099) | Jun 27, 2019 |
| AMD           | R690A-M2T                   | Desktop     | [da36474b90](https://linux-hardware.org/?probe=da36474b90) | Jun 18, 2019 |
| Gigabyte      | AB350M-DS2-CF               | Desktop     | [553908ddb3](https://linux-hardware.org/?probe=553908ddb3) | Jun 09, 2019 |
| ASUSTek       | PRIME X399-A                | Desktop     | [ae94045380](https://linux-hardware.org/?probe=ae94045380) | May 29, 2019 |
| Lenovo        | NO DPK                      | Desktop     | [b89b8c9364](https://linux-hardware.org/?probe=b89b8c9364) | May 27, 2019 |
| Samsung       | 800G5M/800G5W               | Notebook    | [01cb2e9401](https://linux-hardware.org/?probe=01cb2e9401) | May 22, 2019 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e318a9dac5](https://linux-hardware.org/?probe=e318a9dac5) | May 10, 2019 |
| ASRock        | H61M-DGS                    | Desktop     | [6dc8ccd0f6](https://linux-hardware.org/?probe=6dc8ccd0f6) | May 08, 2019 |
| Sony          | VPCEA36FK                   | Notebook    | [6c4b2a047b](https://linux-hardware.org/?probe=6c4b2a047b) | May 01, 2019 |
| Foxconn       | P35A01                      | Desktop     | [f2685edfa8](https://linux-hardware.org/?probe=f2685edfa8) | Apr 21, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [fb5730a29c](https://linux-hardware.org/?probe=fb5730a29c) | Apr 17, 2019 |
| Apple         | MacBookPro14,1              | Notebook    | [606c70c0db](https://linux-hardware.org/?probe=606c70c0db) | Apr 15, 2019 |
| Dell          | Inspiron 7570               | Notebook    | [f46c9c93f9](https://linux-hardware.org/?probe=f46c9c93f9) | Apr 12, 2019 |
| Dell          | Inspiron 7570               | Notebook    | [e1c522656b](https://linux-hardware.org/?probe=e1c522656b) | Apr 12, 2019 |
| ASUSTek       | Z170-A                      | Desktop     | [322d76fe62](https://linux-hardware.org/?probe=322d76fe62) | Apr 04, 2019 |
| ASUSTek       | Z170-A                      | Desktop     | [0fa2f9b10a](https://linux-hardware.org/?probe=0fa2f9b10a) | Apr 04, 2019 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [8e21d7bf0c](https://linux-hardware.org/?probe=8e21d7bf0c) | Mar 30, 2019 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [45f363040f](https://linux-hardware.org/?probe=45f363040f) | Mar 30, 2019 |
| Lenovo        | ThinkPad P52s 20LBCTO1WW    | Notebook    | [ed9f709e73](https://linux-hardware.org/?probe=ed9f709e73) | Feb 20, 2019 |
| HP            | ProLiant DL380 Gen9         | Server      | [c9d389b2a3](https://linux-hardware.org/?probe=c9d389b2a3) | Jan 26, 2019 |
| ASRock        | P55 Pro                     | Desktop     | [041e899a1b](https://linux-hardware.org/?probe=041e899a1b) | Jan 15, 2019 |
| Gigabyte      | H55M-S2V                    | Desktop     | [36d1703d67](https://linux-hardware.org/?probe=36d1703d67) | Dec 23, 2018 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [4a0abda7de](https://linux-hardware.org/?probe=4a0abda7de) | Dec 14, 2018 |
| LattePanda    | Alpha                       | Desktop     | [287f0d8110](https://linux-hardware.org/?probe=287f0d8110) | Nov 27, 2018 |
| LattePanda    | Alpha                       | Desktop     | [37c9db1d31](https://linux-hardware.org/?probe=37c9db1d31) | Nov 27, 2018 |
| AVERATEC      | 6600                        | Notebook    | [a55a983b35](https://linux-hardware.org/?probe=a55a983b35) | Nov 11, 2018 |
| AVERATEC      | 6600                        | Notebook    | [8ca54d992c](https://linux-hardware.org/?probe=8ca54d992c) | Nov 11, 2018 |
| Dell          | XPS 15 9560                 | Notebook    | [d5d9e2cef1](https://linux-hardware.org/?probe=d5d9e2cef1) | Nov 04, 2018 |
| LG Electro... | R510                        | Notebook    | [f7b3f1d4a5](https://linux-hardware.org/?probe=f7b3f1d4a5) | Oct 13, 2018 |
| Gigabyte      | P55-US3L                    | Desktop     | [e216d60f26](https://linux-hardware.org/?probe=e216d60f26) | Sep 19, 2018 |
| Gigabyte      | B75M-D3H                    | Desktop     | [08f9437e06](https://linux-hardware.org/?probe=08f9437e06) | Jul 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [16f456428f](https://linux-hardware.org/?probe=16f456428f) | May 10, 2018 |
| ECS           | A55F2-M3                    | Desktop     | [e4af897158](https://linux-hardware.org/?probe=e4af897158) | May 10, 2018 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [f3036847e4](https://linux-hardware.org/?probe=f3036847e4) | May 10, 2018 |
| ECS           | A55F2-M3                    | Desktop     | [eb58cea516](https://linux-hardware.org/?probe=eb58cea516) | May 10, 2018 |
| ASRock        | G41M-VS3                    | Desktop     | [18d59d7ea8](https://linux-hardware.org/?probe=18d59d7ea8) | Apr 13, 2018 |
| ASUSTek       | N56JR                       | Notebook    | [27253306bc](https://linux-hardware.org/?probe=27253306bc) | Dec 28, 2017 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 87        | 25%     |
| Ubuntu 18.04                 | 46        | 13.22%  |
| Ubuntu 22.04                 | 11        | 3.16%   |
| Ubuntu 21.10                 | 9         | 2.59%   |
| Ubuntu 19.10                 | 9         | 2.59%   |
| Arch                         | 9         | 2.59%   |
| Ubuntu 20.10                 | 8         | 2.3%    |
| Ubuntu 16.04                 | 7         | 2.01%   |
| Fedora 32                    | 7         | 2.01%   |
| Ubuntu 19.04                 | 6         | 1.72%   |
| Linux Mint 20.1              | 6         | 1.72%   |
| Arch Rolling                 | 6         | 1.72%   |
| HamoniKR 4.0                 | 5         | 1.44%   |
| Gooroom                      | 5         | 1.44%   |
| Fedora 34                    | 5         | 1.44%   |
| Debian 10                    | 5         | 1.44%   |
| Zorin 15                     | 4         | 1.15%   |
| OpenMandriva 4.2             | 4         | 1.15%   |
| Linux Mint 20.3              | 4         | 1.15%   |
| Linux Mint 20                | 4         | 1.15%   |
| ROSA R11                     | 3         | 0.86%   |
| ROSA R10                     | 3         | 0.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.86%   |
| No1 2022 kde plasma te       | 3         | 0.86%   |
| No1 2020 te                  | 3         | 0.86%   |
| No1 2018                     | 3         | 0.86%   |
| Linux Mint 20.2              | 3         | 0.86%   |
| Linux Mint 19.3              | 3         | 0.86%   |
| HamoniKR 5.0                 | 3         | 0.86%   |
| Fedora 33                    | 3         | 0.86%   |
| CentOS 8                     | 3         | 0.86%   |
| CentOS 7                     | 3         | 0.86%   |
| Ubuntu MATE 18.04            | 2         | 0.57%   |
| RHEL 8                       | 2         | 0.57%   |
| Pop!_OS 21.10                | 2         | 0.57%   |
| Pop!_OS 20.04                | 2         | 0.57%   |
| OpenMandriva 4.50            | 2         | 0.57%   |
| Manjaro 21.3.0               | 2         | 0.57%   |
| Manjaro 20.2.1               | 2         | 0.57%   |
| Lubuntu 18.04                | 2         | 0.57%   |
| KDE neon 20.04               | 2         | 0.57%   |
| HamoniKR                     | 2         | 0.57%   |
| Endless 3.8.5                | 2         | 0.57%   |
| Debian 11                    | 2         | 0.57%   |
| Chrome OS                    | 2         | 0.57%   |
| CentOS 6.9                   | 2         | 0.57%   |
| Xubuntu 20.04                | 1         | 0.29%   |
| Ubuntu 21.04                 | 1         | 0.29%   |
| Ubuntu 18.10                 | 1         | 0.29%   |
| Ubuntu 17.10                 | 1         | 0.29%   |
| Ubuntu                       | 1         | 0.29%   |
| TmaxOS 21.12.02              | 1         | 0.29%   |
| Pop!_OS 22.04                | 1         | 0.29%   |
| Pop!_OS 21.04                | 1         | 0.29%   |
| Pop!_OS 20.10                | 1         | 0.29%   |
| Manjaro 21.1.6               | 1         | 0.29%   |
| Manjaro 21.1.3               | 1         | 0.29%   |
| Manjaro 20.1                 | 1         | 0.29%   |
| Manjaro 19.0.2               | 1         | 0.29%   |
| Manjaro 18.1.0               | 1         | 0.29%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 183       | 54.46%  |
| Linux Mint   | 19        | 5.65%   |
| Fedora       | 17        | 5.06%   |
| Arch         | 13        | 3.87%   |
| Manjaro      | 10        | 2.98%   |
| HamoniKR     | 9         | 2.68%   |
| Endless      | 8         | 2.38%   |
| Debian       | 8         | 2.38%   |
| CentOS       | 8         | 2.38%   |
| No1          | 7         | 2.08%   |
| ROSA         | 6         | 1.79%   |
| OpenMandriva | 6         | 1.79%   |
| Pop!_OS      | 5         | 1.49%   |
| Gooroom      | 5         | 1.49%   |
| Zorin        | 4         | 1.19%   |
| Kubuntu      | 4         | 1.19%   |
| openSUSE     | 3         | 0.89%   |
| KDE neon     | 3         | 0.89%   |
| Ubuntu MATE  | 2         | 0.6%    |
| RHEL         | 2         | 0.6%    |
| Lubuntu      | 2         | 0.6%    |
| EndeavourOS  | 2         | 0.6%    |
| Chrome OS    | 2         | 0.6%    |
| Xubuntu      | 1         | 0.3%    |
| TmaxOS       | 1         | 0.3%    |
| LMDE         | 1         | 0.3%    |
| Gentoo       | 1         | 0.3%    |
| Garuda Linux | 1         | 0.3%    |
| Devuan       | 1         | 0.3%    |
| BlackPanther | 1         | 0.3%    |
| Alpine       | 1         | 0.3%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.3.0-40-generic                | 8         | 2.13%   |
| 5.4.0-42-generic                | 7         | 1.86%   |
| 5.4.0-29-generic                | 6         | 1.6%    |
| 5.4.0-26-generic                | 6         | 1.6%    |
| 5.4.0-58-generic                | 5         | 1.33%   |
| 5.4.0-56-generic                | 5         | 1.33%   |
| 5.15.0-41-generic               | 4         | 1.06%   |
| 5.0.0-25-generic                | 4         | 1.06%   |
| 5.8.0-59-generic                | 3         | 0.8%    |
| 5.8.0-50-generic                | 3         | 0.8%    |
| 5.8.0-38-generic                | 3         | 0.8%    |
| 5.4.0-91-generic                | 3         | 0.8%    |
| 5.4.0-81-generic                | 3         | 0.8%    |
| 5.4.0-54-generic                | 3         | 0.8%    |
| 5.4.0-52-generic                | 3         | 0.8%    |
| 5.4.0-47-generic                | 3         | 0.8%    |
| 5.4.0-37-generic                | 3         | 0.8%    |
| 5.4.0-33-generic                | 3         | 0.8%    |
| 5.3.0-46-generic                | 3         | 0.8%    |
| 5.13.0-39-generic               | 3         | 0.8%    |
| 5.11.0-37-generic               | 3         | 0.8%    |
| 5.10.14-desktop-1omv4002        | 3         | 0.8%    |
| 5.0.0-27-generic                | 3         | 0.8%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 3         | 0.8%    |
| 4.19.0-9-amd64                  | 3         | 0.8%    |
| 4.19.0-14-amd64                 | 3         | 0.8%    |
| 4.18.0-25-generic               | 3         | 0.8%    |
| 4.15.0-desktop-45.1rosa-x86_64  | 3         | 0.8%    |
| 5.8.4-200.fc32.x86_64           | 2         | 0.53%   |
| 5.8.16-300.fc33.x86_64          | 2         | 0.53%   |
| 5.8.0-55-generic                | 2         | 0.53%   |
| 5.8.0-53-generic                | 2         | 0.53%   |
| 5.8.0-48-generic                | 2         | 0.53%   |
| 5.8.0-43-generic                | 2         | 0.53%   |
| 5.8.0-41-generic                | 2         | 0.53%   |
| 5.8.0-32-generic                | 2         | 0.53%   |
| 5.8.0-14-generic                | 2         | 0.53%   |
| 5.4.0-89-generic                | 2         | 0.53%   |
| 5.4.0-79-generic                | 2         | 0.53%   |
| 5.4.0-7642-generic              | 2         | 0.53%   |
| 5.4.0-74-generic                | 2         | 0.53%   |
| 5.4.0-72-generic                | 2         | 0.53%   |
| 5.4.0-70-generic                | 2         | 0.53%   |
| 5.4.0-66-generic                | 2         | 0.53%   |
| 5.4.0-65-generic                | 2         | 0.53%   |
| 5.4.0-48-generic                | 2         | 0.53%   |
| 5.4.0-39-generic                | 2         | 0.53%   |
| 5.4.0-31-generic                | 2         | 0.53%   |
| 5.4.0-21-generic                | 2         | 0.53%   |
| 5.4.0-107-generic               | 2         | 0.53%   |
| 5.4.0-105-generic               | 2         | 0.53%   |
| 5.3.0-59-generic                | 2         | 0.53%   |
| 5.3.0-51-generic                | 2         | 0.53%   |
| 5.3.0-28-generic                | 2         | 0.53%   |
| 5.3.0-24-generic                | 2         | 0.53%   |
| 5.18.5-1-MANJARO                | 2         | 0.53%   |
| 5.16.19-no1linux5               | 2         | 0.53%   |
| 5.15.0-33-generic               | 2         | 0.53%   |
| 5.15.0-30-generic               | 2         | 0.53%   |
| 5.15.0-27-generic               | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 89        | 25%     |
| 5.8.0   | 30        | 8.43%   |
| 4.15.0  | 28        | 7.87%   |
| 5.3.0   | 23        | 6.46%   |
| 5.13.0  | 19        | 5.34%   |
| 4.18.0  | 17        | 4.78%   |
| 5.15.0  | 13        | 3.65%   |
| 5.11.0  | 13        | 3.65%   |
| 5.0.0   | 12        | 3.37%   |
| 4.19.0  | 10        | 2.81%   |
| 5.16.19 | 5         | 1.4%    |
| 5.18.5  | 3         | 0.84%   |
| 5.10.14 | 3         | 0.84%   |
| 5.10.0  | 3         | 0.84%   |
| 4.9.60  | 3         | 0.84%   |
| 5.8.4   | 2         | 0.56%   |
| 5.8.16  | 2         | 0.56%   |
| 5.15.8  | 2         | 0.56%   |
| 5.15.11 | 2         | 0.56%   |
| 5.14.6  | 2         | 0.56%   |
| 5.14.0  | 2         | 0.56%   |
| 5.12.4  | 2         | 0.56%   |
| 5.11.12 | 2         | 0.56%   |
| 5.10.4  | 2         | 0.56%   |
| 4.9.140 | 2         | 0.56%   |
| 4.18.16 | 2         | 0.56%   |
| 4.15.8  | 2         | 0.56%   |
| 4.13.0  | 2         | 0.56%   |
| 3.10.0  | 2         | 0.56%   |
| 2.6.32  | 2         | 0.56%   |
| 5.9.9   | 1         | 0.28%   |
| 5.9.0   | 1         | 0.28%   |
| 5.8.7   | 1         | 0.28%   |
| 5.8.5   | 1         | 0.28%   |
| 5.8.18  | 1         | 0.28%   |
| 5.8.15  | 1         | 0.28%   |
| 5.8.10  | 1         | 0.28%   |
| 5.7.17  | 1         | 0.28%   |
| 5.7.16  | 1         | 0.28%   |
| 5.6.6   | 1         | 0.28%   |
| 5.6.12  | 1         | 0.28%   |
| 5.6.11  | 1         | 0.28%   |
| 5.6.0   | 1         | 0.28%   |
| 5.5.2   | 1         | 0.28%   |
| 5.4.61  | 1         | 0.28%   |
| 5.4.55  | 1         | 0.28%   |
| 5.4.25  | 1         | 0.28%   |
| 5.4.2   | 1         | 0.28%   |
| 5.4.167 | 1         | 0.28%   |
| 5.3.7   | 1         | 0.28%   |
| 5.2.11  | 1         | 0.28%   |
| 5.18.9  | 1         | 0.28%   |
| 5.18.3  | 1         | 0.28%   |
| 5.16.8  | 1         | 0.28%   |
| 5.16.5  | 1         | 0.28%   |
| 5.16.1  | 1         | 0.28%   |
| 5.15.38 | 1         | 0.28%   |
| 5.15.2  | 1         | 0.28%   |
| 5.15.16 | 1         | 0.28%   |
| 5.15.15 | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 94        | 26.48%  |
| 5.8     | 39        | 10.99%  |
| 4.15    | 30        | 8.45%   |
| 5.3     | 24        | 6.76%   |
| 5.15    | 22        | 6.2%    |
| 5.13    | 20        | 5.63%   |
| 5.11    | 20        | 5.63%   |
| 4.18    | 19        | 5.35%   |
| 5.0     | 13        | 3.66%   |
| 4.19    | 12        | 3.38%   |
| 5.10    | 11        | 3.1%    |
| 5.16    | 8         | 2.25%   |
| 5.14    | 7         | 1.97%   |
| 5.12    | 6         | 1.69%   |
| 4.9     | 6         | 1.69%   |
| 5.18    | 5         | 1.41%   |
| 5.6     | 4         | 1.13%   |
| 5.9     | 2         | 0.56%   |
| 5.7     | 2         | 0.56%   |
| 4.13    | 2         | 0.56%   |
| 3.10    | 2         | 0.56%   |
| 2.6     | 2         | 0.56%   |
| 5.5     | 1         | 0.28%   |
| 5.2     | 1         | 0.28%   |
| 4.4     | 1         | 0.28%   |
| 4.17    | 1         | 0.28%   |
| 4.16    | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 318       | 96.66%  |
| aarch64 | 7         | 2.13%   |
| i686    | 3         | 0.91%   |
| armv7l  | 1         | 0.3%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 174       | 51.79%  |
| Unknown         | 61        | 18.15%  |
| KDE5            | 32        | 9.52%   |
| X-Cinnamon      | 20        | 5.95%   |
| XFCE            | 10        | 2.98%   |
| Cinnamon        | 8         | 2.38%   |
| Unity           | 6         | 1.79%   |
| KDE             | 5         | 1.49%   |
| GNOME Flashback | 5         | 1.49%   |
| LXDE            | 4         | 1.19%   |
| KDE4            | 4         | 1.19%   |
| MATE            | 2         | 0.6%    |
| i3              | 2         | 0.6%    |
| TOS:GNOME       | 1         | 0.3%    |
| sway            | 1         | 0.3%    |
| GNOME Classic   | 1         | 0.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 240       | 72.51%  |
| Unknown | 42        | 12.69%  |
| Wayland | 40        | 12.08%  |
| Tty     | 9         | 2.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 198       | 58.24%  |
| GDM     | 53        | 15.59%  |
| SDDM    | 31        | 9.12%   |
| GDM3    | 20        | 5.88%   |
| LightDM | 17        | 5%      |
| TDM     | 16        | 4.71%   |
| KDM     | 3         | 0.88%   |
| XDM     | 1         | 0.29%   |
| SLiM    | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| ko_KR       | 146       | 43.32%  |
| en_US       | 107       | 31.75%  |
| Unknown     | 60        | 17.8%   |
| C           | 4         | 1.19%   |
| zh_CN       | 3         | 0.89%   |
| id_ID       | 3         | 0.89%   |
| pt_BR       | 2         | 0.59%   |
| fr_FR       | 2         | 0.59%   |
| en_GB       | 2         | 0.59%   |
| en_CA       | 2         | 0.59%   |
| vi_VN       | 1         | 0.3%    |
| ru_RU       | 1         | 0.3%    |
| ko_KR.euckr | 1         | 0.3%    |
| en_NZ       | 1         | 0.3%    |
| en_AU       | 1         | 0.3%    |
| ar_EG       | 1         | 0.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 203       | 61.33%  |
| BIOS | 128       | 38.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 281       | 84.13%  |
| Unknown | 17        | 5.09%   |
| Btrfs   | 15        | 4.49%   |
| Overlay | 9         | 2.69%   |
| Xfs     | 8         | 2.4%    |
| Zfs     | 4         | 1.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 198       | 59.46%  |
| GPT     | 112       | 33.63%  |
| MBR     | 23        | 6.91%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 295       | 89.12%  |
| Yes       | 36        | 10.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 227       | 67.76%  |
| Yes       | 108       | 32.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 49        | 14.89%  |
| Lenovo                  | 43        | 13.07%  |
| Gigabyte Technology     | 31        | 9.42%   |
| Samsung Electronics     | 28        | 8.51%   |
| ASRock                  | 26        | 7.9%    |
| Hewlett-Packard         | 25        | 7.6%    |
| LG Electronics          | 21        | 6.38%   |
| MSI                     | 20        | 6.08%   |
| Dell                    | 14        | 4.26%   |
| ECS                     | 10        | 3.04%   |
| Apple                   | 5         | 1.52%   |
| HANSUNG COMPUTER        | 4         | 1.22%   |
| Raspberry Pi Foundation | 3         | 0.91%   |
| Notebook                | 3         | 0.91%   |
| Intel                   | 3         | 0.91%   |
| Foxconn                 | 3         | 0.91%   |
| Acer                    | 3         | 0.91%   |
| Toshiba                 | 2         | 0.61%   |
| Quanta                  | 2         | 0.61%   |
| Nvidia                  | 2         | 0.61%   |
| LattePanda              | 2         | 0.61%   |
| Hanis                   | 2         | 0.61%   |
| Alienware               | 2         | 0.61%   |
| Wolfnfox                | 1         | 0.3%    |
| WB                      | 1         | 0.3%    |
| TG                      | 1         | 0.3%    |
| Teclast                 | 1         | 0.3%    |
| Supermicro              | 1         | 0.3%    |
| sunxi                   | 1         | 0.3%    |
| Sony                    | 1         | 0.3%    |
| SLIMBOOK                | 1         | 0.3%    |
| Pine Microsystems       | 1         | 0.3%    |
| PCPartner               | 1         | 0.3%    |
| PC Partner Limited      | 1         | 0.3%    |
| Microsoft               | 1         | 0.3%    |
| MECHREVO                | 1         | 0.3%    |
| Jooyontech Computer     | 1         | 0.3%    |
| IMUZ                    | 1         | 0.3%    |
| Huanan                  | 1         | 0.3%    |
| Hardkernel              | 1         | 0.3%    |
| Google                  | 1         | 0.3%    |
| Clevo                   | 1         | 0.3%    |
| Chuwi                   | 1         | 0.3%    |
| Biostar                 | 1         | 0.3%    |
| AVERATEC                | 1         | 0.3%    |
| ASRockRack              | 1         | 0.3%    |
| AMI                     | 1         | 0.3%    |
| AMD                     | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Samsung DeskTop System                            | 4         | 1.22%   |
| ECS LIVA Q2                                       | 3         | 0.91%   |
| ASUS PRIME B350M-A                                | 3         | 0.91%   |
| Samsung Galaxy Book 12 LTE                        | 2         | 0.61%   |
| Samsung 950XCJ/951XCJ/950XCR                      | 2         | 0.61%   |
| Quanta QSSC-98J_C2                                | 2         | 0.61%   |
| Nvidia Tegra                                      | 2         | 0.61%   |
| Lenovo ThinkPad L14 Gen 1 20U5S01S00              | 2         | 0.61%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2                 | 2         | 0.61%   |
| LattePanda Alpha                                  | 2         | 0.61%   |
| HP Stream Notebook PC 13                          | 2         | 0.61%   |
| HP Laptop 15-db1xxx                               | 2         | 0.61%   |
| HANSUNG COMPUTER TFX5470H                         | 2         | 0.61%   |
| Gigabyte TRX40 AORUS XTREME                       | 2         | 0.61%   |
| Gigabyte H81M-DS2V                                | 2         | 0.61%   |
| Gigabyte B75M-D3V                                 | 2         | 0.61%   |
| Gigabyte B75M-D3H                                 | 2         | 0.61%   |
| Dell XPS 15 7590                                  | 2         | 0.61%   |
| ASUS ROG STRIX Z690-A GAMING WIFI D4              | 2         | 0.61%   |
| ASUS PRIME A320M-K                                | 2         | 0.61%   |
| ASUS EX-A320M-GAMING                              | 2         | 0.61%   |
| ASUS All Series                                   | 2         | 0.61%   |
| ASRock H81M-DGS R2.0                              | 2         | 0.61%   |
| ASRock AB350M Pro4                                | 2         | 0.61%   |
| Unknown                                           | 2         | 0.61%   |
| Wolfnfox WF-TBAT                                  | 1         | 0.3%    |
| WB AIO                                            | 1         | 0.3%    |
| Toshiba Satellite P50-B-103                       | 1         | 0.3%    |
| Toshiba Satellite L655                            | 1         | 0.3%    |
| TG NXI-A7000 Series                               | 1         | 0.3%    |
| Teclast tPAD                                      | 1         | 0.3%    |
| Supermicro SYS-4029GP-TRT2                        | 1         | 0.3%    |
| Sony VPCEA36FK                                    | 1         | 0.3%    |
| SLIMBOOK PROX15-AMD                               | 1         | 0.3%    |
| Samsung X120/X170/X171                            | 1         | 0.3%    |
| Samsung SX11S                                     | 1         | 0.3%    |
| Samsung RC420/RC520/RC720                         | 1         | 0.3%    |
| Samsung R59P/R60P/R61P                            | 1         | 0.3%    |
| Samsung R440/R480                                 | 1         | 0.3%    |
| Samsung 950XDB/951XDB/950XDY                      | 1         | 0.3%    |
| Samsung 950QDA                                    | 1         | 0.3%    |
| Samsung 930QAA                                    | 1         | 0.3%    |
| Samsung 905S3G/906S3G/915S3G                      | 1         | 0.3%    |
| Samsung 800G5M/800G5W                             | 1         | 0.3%    |
| Samsung 760XBE                                    | 1         | 0.3%    |
| Samsung 730QCJ/730QCR                             | 1         | 0.3%    |
| Samsung 670Z5E                                    | 1         | 0.3%    |
| Samsung 570Z5E/580Z5E                             | 1         | 0.3%    |
| Samsung 530U3BI/530U4BI/530U4BH                   | 1         | 0.3%    |
| Samsung 500T8A/500S8A/500T9A/500S9A               | 1         | 0.3%    |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.3%    |
| Samsung 400B4C/400B5C/200B4C/200B5C               | 1         | 0.3%    |
| Samsung 400B4B/400B5B/200B4B/200B5B               | 1         | 0.3%    |
| Samsung 270E5J/2570EJ                             | 1         | 0.3%    |
| RPi Raspberry Pi 4 Model B Rev 1.4                | 1         | 0.3%    |
| RPi Raspberry Pi 3 Model B Rev 1.2                | 1         | 0.3%    |
| RPi Raspberry Pi                                  | 1         | 0.3%    |
| Pine Microsystems Pine64 Pinebook Pro             | 1         | 0.3%    |
| PCPartner DREAMSYS                                | 1         | 0.3%    |
| PC Partner Limited S70BS.AH3511                   | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 27        | 8.21%   |
| ASUS PRIME                 | 11        | 3.34%   |
| HP Pavilion                | 7         | 2.13%   |
| ASUS VivoBook              | 7         | 2.13%   |
| ASUS ROG                   | 5         | 1.52%   |
| Samsung DeskTop            | 4         | 1.22%   |
| Lenovo IdeaPad             | 4         | 1.22%   |
| HP Laptop                  | 4         | 1.22%   |
| Dell XPS                   | 4         | 1.22%   |
| Dell Inspiron              | 4         | 1.22%   |
| RPi Raspberry              | 3         | 0.91%   |
| HP Stream                  | 3         | 0.91%   |
| HP EliteBook               | 3         | 0.91%   |
| ECS LIVA                   | 3         | 0.91%   |
| Toshiba Satellite          | 2         | 0.61%   |
| Samsung Galaxy             | 2         | 0.61%   |
| Samsung 950XCJ             | 2         | 0.61%   |
| Quanta QSSC-98J            | 2         | 0.61%   |
| Nvidia Tegra               | 2         | 0.61%   |
| MSI Prestige               | 2         | 0.61%   |
| Lenovo ThinkStation        | 2         | 0.61%   |
| Lenovo IdeaPadFlex         | 2         | 0.61%   |
| LattePanda Alpha           | 2         | 0.61%   |
| HP ProBook                 | 2         | 0.61%   |
| HANSUNG COMPUTER TFX5470H  | 2         | 0.61%   |
| Gigabyte Z390              | 2         | 0.61%   |
| Gigabyte X570              | 2         | 0.61%   |
| Gigabyte TRX40             | 2         | 0.61%   |
| Gigabyte H81M-DS2V         | 2         | 0.61%   |
| Gigabyte B75M-D3V          | 2         | 0.61%   |
| Gigabyte B75M-D3H          | 2         | 0.61%   |
| Dell Vostro                | 2         | 0.61%   |
| Dell Latitude              | 2         | 0.61%   |
| ASUS TUF                   | 2         | 0.61%   |
| ASUS EX-A320M-GAMING       | 2         | 0.61%   |
| ASUS All                   | 2         | 0.61%   |
| ASRock Z390                | 2         | 0.61%   |
| ASRock H81M-DGS            | 2         | 0.61%   |
| ASRock FM2A88M-HD+         | 2         | 0.61%   |
| ASRock AB350M              | 2         | 0.61%   |
| Apple MacBookPro5          | 2         | 0.61%   |
| Acer Swift                 | 2         | 0.61%   |
| Unknown                    | 2         | 0.61%   |
| Wolfnfox WF-TBAT           | 1         | 0.3%    |
| WB AIO                     | 1         | 0.3%    |
| TG NXI-A7000               | 1         | 0.3%    |
| Teclast tPAD               | 1         | 0.3%    |
| Supermicro SYS-4029GP-TRT2 | 1         | 0.3%    |
| Sony VPCEA36FK             | 1         | 0.3%    |
| SLIMBOOK PROX15-AMD        | 1         | 0.3%    |
| Samsung X120               | 1         | 0.3%    |
| Samsung SX11S              | 1         | 0.3%    |
| Samsung RC420              | 1         | 0.3%    |
| Samsung R59P               | 1         | 0.3%    |
| Samsung R440               | 1         | 0.3%    |
| Samsung 950XDB             | 1         | 0.3%    |
| Samsung 950QDA             | 1         | 0.3%    |
| Samsung 930QAA             | 1         | 0.3%    |
| Samsung 905S3G             | 1         | 0.3%    |
| Samsung 800G5M             | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 44        | 13.37%  |
| 2018    | 39        | 11.85%  |
| 2019    | 37        | 11.25%  |
| 2021    | 26        | 7.9%    |
| 2017    | 24        | 7.29%   |
| 2012    | 24        | 7.29%   |
| 2014    | 23        | 6.99%   |
| 2013    | 21        | 6.38%   |
| 2011    | 14        | 4.26%   |
| 2016    | 13        | 3.95%   |
| 2015    | 13        | 3.95%   |
| 2010    | 13        | 3.95%   |
| 2009    | 11        | 3.34%   |
| 2008    | 10        | 3.04%   |
| 2007    | 6         | 1.82%   |
| Unknown | 6         | 1.82%   |
| 2006    | 3         | 0.91%   |
| 2022    | 1         | 0.3%    |
| 2005    | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 159       | 48.33%  |
| Desktop        | 128       | 38.91%  |
| Tablet         | 11        | 3.34%   |
| Convertible    | 10        | 3.04%   |
| Server         | 10        | 3.04%   |
| System on chip | 7         | 2.13%   |
| Mini pc        | 3         | 0.91%   |
| All in one     | 1         | 0.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 307       | 92.75%  |
| Enabled  | 24        | 7.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 328       | 99.7%   |
| Yes  | 1         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 69        | 20.66%  |
| 16.01-24.0      | 61        | 18.26%  |
| 8.01-16.0       | 59        | 17.66%  |
| 3.01-4.0        | 56        | 16.77%  |
| 32.01-64.0      | 30        | 8.98%   |
| 64.01-256.0     | 23        | 6.89%   |
| 1.01-2.0        | 20        | 5.99%   |
| 24.01-32.0      | 7         | 2.1%    |
| More than 256.0 | 4         | 1.2%    |
| 2.01-3.0        | 3         | 0.9%    |
| 0.51-1.0        | 1         | 0.3%    |
| 0.01-0.5        | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 121       | 33.89%  |
| 2.01-3.0   | 75        | 21.01%  |
| 3.01-4.0   | 58        | 16.25%  |
| 4.01-8.0   | 51        | 14.29%  |
| 0.51-1.0   | 24        | 6.72%   |
| 8.01-16.0  | 13        | 3.64%   |
| 16.01-24.0 | 5         | 1.4%    |
| 0.01-0.5   | 4         | 1.12%   |
| 32.01-64.0 | 3         | 0.84%   |
| Unknown    | 2         | 0.56%   |
| 24.01-32.0 | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 184       | 54.6%   |
| 2       | 99        | 29.38%  |
| 3       | 26        | 7.72%   |
| 4       | 12        | 3.56%   |
| 5       | 6         | 1.78%   |
| 6       | 3         | 0.89%   |
| 0       | 2         | 0.59%   |
| 10      | 1         | 0.3%    |
| 9       | 1         | 0.3%    |
| 8       | 1         | 0.3%    |
| 7       | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 257       | 77.88%  |
| Yes       | 73        | 22.12%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 79.82%  |
| No        | 67        | 20.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 66.36%  |
| No        | 111       | 33.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 61.33%  |
| No        | 128       | 38.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| South Korea | 329       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Seoul          | 47        | 13.43%  |
| Suwon          | 15        | 4.29%   |
| Seongnam-si    | 15        | 4.29%   |
| Gwanak-gu      | 12        | 3.43%   |
| Busan          | 9         | 2.57%   |
| Seocho-gu      | 8         | 2.29%   |
| Cheonan        | 8         | 2.29%   |
| Yongin-si      | 7         | 2%      |
| Incheon        | 7         | 2%      |
| Hwaseong-si    | 7         | 2%      |
| Seo-gu         | 6         | 1.71%   |
| Namyangju      | 6         | 1.71%   |
| Jung-gu        | 6         | 1.71%   |
| Daejeon        | 6         | 1.71%   |
| Anyang-si      | 6         | 1.71%   |
| Yongsan-gu     | 5         | 1.43%   |
| Uiwang         | 5         | 1.43%   |
| Pyeongtaek-si  | 5         | 1.43%   |
| Nam-gu         | 5         | 1.43%   |
| Gwangmyeong    | 5         | 1.43%   |
| Gangseo-gu     | 5         | 1.43%   |
| Gangnam-gu     | 5         | 1.43%   |
| Mapo-gu        | 4         | 1.14%   |
| Goyang-si      | 4         | 1.14%   |
| Dongjak-gu     | 4         | 1.14%   |
| Daegu          | 4         | 1.14%   |
| Bupyeong-gu    | 4         | 1.14%   |
| Buk-gu         | 4         | 1.14%   |
| Bucheon-si     | 4         | 1.14%   |
| Yuseong-gu     | 3         | 0.86%   |
| Yeonsu-gu      | 3         | 0.86%   |
| Yangcheon-gu   | 3         | 0.86%   |
| Siheung-si     | 3         | 0.86%   |
| Seongdong-gu   | 3         | 0.86%   |
| Seongbuk-gu    | 3         | 0.86%   |
| Osan           | 3         | 0.86%   |
| Namdong-gu     | 3         | 0.86%   |
| Jungnang-gu    | 3         | 0.86%   |
| Jeju City      | 3         | 0.86%   |
| Gwangju        | 3         | 0.86%   |
| Guri-si        | 3         | 0.86%   |
| Gimpo-si       | 3         | 0.86%   |
| Geumjeong-gu   | 3         | 0.86%   |
| Changwon       | 3         | 0.86%   |
| Yangp'yong     | 2         | 0.57%   |
| Sacheon-si     | 2         | 0.57%   |
| Pohang         | 2         | 0.57%   |
| Pocheon-si     | 2         | 0.57%   |
| Paju           | 2         | 0.57%   |
| Jeonju         | 2         | 0.57%   |
| Haeundae-gu    | 2         | 0.57%   |
| Gyeyang-gu     | 2         | 0.57%   |
| Gyeongsan-si   | 2         | 0.57%   |
| Gyeonggi-do    | 2         | 0.57%   |
| Gwangsan-gu    | 2         | 0.57%   |
| Gwangmyeong-si | 2         | 0.57%   |
| Geumcheon-gu   | 2         | 0.57%   |
| Dongdaemun-gu  | 2         | 0.57%   |
| Danyang-gun    | 2         | 0.57%   |
| Dalseong-gun   | 2         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 105       | 136    | 21.34%  |
| WDC                       | 79        | 120    | 16.06%  |
| Seagate                   | 52        | 73     | 10.57%  |
| Unknown                   | 38        | 59     | 7.72%   |
| SanDisk                   | 32        | 34     | 6.5%    |
| Toshiba                   | 28        | 43     | 5.69%   |
| Crucial                   | 23        | 28     | 4.67%   |
| SK hynix                  | 17        | 24     | 3.46%   |
| Hitachi                   | 13        | 14     | 2.64%   |
| Intel                     | 10        | 17     | 2.03%   |
| A-DATA Technology         | 9         | 9      | 1.83%   |
| Kingston                  | 7         | 8      | 1.42%   |
| Micron Technology         | 6         | 7      | 1.22%   |
| Transcend                 | 5         | 6      | 1.02%   |
| TAMMUZ                    | 5         | 8      | 1.02%   |
| Phison                    | 5         | 6      | 1.02%   |
| HGST                      | 5         | 6      | 1.02%   |
| Plextor                   | 4         | 6      | 0.81%   |
| SPCC                      | 3         | 3      | 0.61%   |
| Fujitsu                   | 3         | 3      | 0.61%   |
| Union Memory              | 2         | 2      | 0.41%   |
| Silicon Motion            | 2         | 2      | 0.41%   |
| KIOXIA                    | 2         | 3      | 0.41%   |
| KingSpec                  | 2         | 2      | 0.41%   |
| JMicron Technology        | 2         | 2      | 0.41%   |
| Imation                   | 2         | 3      | 0.41%   |
| Hewlett-Packard           | 2         | 2      | 0.41%   |
| China                     | 2         | 2      | 0.41%   |
| Apple                     | 2         | 2      | 0.41%   |
| ZOTAC                     | 1         | 1      | 0.2%    |
| VIVA300s                  | 1         | 1      | 0.2%    |
| VIEW                      | 1         | 1      | 0.2%    |
| Union Memory (Shenzhen)   | 1         | 1      | 0.2%    |
| UMIS                      | 1         | 1      | 0.2%    |
| TYPEC 1T                  | 1         | 1      | 0.2%    |
| Team                      | 1         | 1      | 0.2%    |
| RevuAhn                   | 1         | 1      | 0.2%    |
| Realtek Semiconductor     | 1         | 1      | 0.2%    |
| QNIX                      | 1         | 1      | 0.2%    |
| PHINOCOM                  | 1         | 1      | 0.2%    |
| OCZ                       | 1         | 2      | 0.2%    |
| Micron/Crucial Technology | 1         | 1      | 0.2%    |
| MARVELL                   | 1         | 1      | 0.2%    |
| LITEONIT                  | 1         | 1      | 0.2%    |
| LITEON                    | 1         | 1      | 0.2%    |
| LaCie                     | 1         | 1      | 0.2%    |
| ipTIME                    | 1         | 1      | 0.2%    |
| IPLEX                     | 1         | 1      | 0.2%    |
| GLOWAY                    | 1         | 1      | 0.2%    |
| FORESEE                   | 1         | 1      | 0.2%    |
| External                  | 1         | 1      | 0.2%    |
| ES                        | 1         | 1      | 0.2%    |
| Biostar                   | 1         | 1      | 0.2%    |
| Apacer                    | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown MMC Card  32GB             | 7         | 1.25%   |
| Unknown MMC Card  64GB             | 6         | 1.07%   |
| Toshiba DT01ACA300 3TB             | 6         | 1.07%   |
| Seagate ST500DM002-1BD142 500GB    | 6         | 1.07%   |
| Samsung NVMe SSD Drive 256GB       | 6         | 1.07%   |
| Crucial CT500MX500SSD1 500GB       | 6         | 1.07%   |
| Samsung SSD 850 EVO 120GB          | 5         | 0.89%   |
| Crucial CT240BX500SSD1 240GB       | 5         | 0.89%   |
| Unknown MMC Card  128GB            | 4         | 0.71%   |
| SanDisk NVMe SSD Drive 256GB       | 4         | 0.71%   |
| Samsung SSD 860 EVO 500GB          | 4         | 0.71%   |
| Samsung NVMe SSD Drive 512GB       | 4         | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 3         | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3         | 0.54%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 3         | 0.54%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 3         | 0.54%   |
| WDC WD10EZEX-22MFCA0 1TB           | 3         | 0.54%   |
| Unknown SD/MMC/MS PRO 64GB         | 3         | 0.54%   |
| Toshiba DT01ACA200 2TB             | 3         | 0.54%   |
| Toshiba DT01ACA050 500GB           | 3         | 0.54%   |
| TAMMUZ SSD 128GB                   | 3         | 0.54%   |
| SK hynix SHGP31-1000GM-2 1TB       | 3         | 0.54%   |
| Seagate ST3500418AS 500GB          | 3         | 0.54%   |
| Seagate ST2000DM008-2FR102 2TB     | 3         | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB     | 3         | 0.54%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 3         | 0.54%   |
| Samsung SSD 850 PRO 256GB          | 3         | 0.54%   |
| Samsung NVMe SSD Drive 1TB         | 3         | 0.54%   |
| Intel SSDSA2CW120G3 120GB          | 3         | 0.54%   |
| Crucial CT275MX300SSD4 275GB       | 3         | 0.54%   |
| WDC WDS120G1G0A-00SS50 120GB SSD   | 2         | 0.36%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 2         | 0.36%   |
| WDC WD50 00LPVX-22V0TT0 500GB      | 2         | 0.36%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 0.36%   |
| WDC WD3200AAJS-00L7A0 320GB        | 2         | 0.36%   |
| WDC WD20EARX-00PASB0 2TB           | 2         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.36%   |
| WDC WD10EZEX-00WN4A0 1TB           | 2         | 0.36%   |
| Unknown SU08G  8GB                 | 2         | 0.36%   |
| Unknown SLD64G  64GB               | 2         | 0.36%   |
| Transcend TS240GSSD220S 240GB      | 2         | 0.36%   |
| Toshiba KBG30ZMV256G 256GB         | 2         | 0.36%   |
| Toshiba HDWD120 2TB                | 2         | 0.36%   |
| SK hynix NVMe SSD Drive 256GB      | 2         | 0.36%   |
| Seagate ST2000DM001-1ER164 2TB     | 2         | 0.36%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB     | 2         | 0.36%   |
| SanDisk NVMe SSD Drive 512GB       | 2         | 0.36%   |
| Samsung SSD 860 QVO 1TB            | 2         | 0.36%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.36%   |
| Samsung SSD 860 EVO 1TB            | 2         | 0.36%   |
| Samsung SSD 850 EVO 250GB          | 2         | 0.36%   |
| Samsung SSD 830 Series 256GB       | 2         | 0.36%   |
| Samsung SSD 830 Series 128GB       | 2         | 0.36%   |
| Samsung SSD 750 EVO 120GB          | 2         | 0.36%   |
| Samsung NVMe SSD Drive 2TB         | 2         | 0.36%   |
| Samsung NVMe SSD Drive 1024GB      | 2         | 0.36%   |
| Samsung MZVLB512HAJQ-00000 512GB   | 2         | 0.36%   |
| Samsung MZVLB256HBHQ-00000 256GB   | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 58        | 89     | 35.58%  |
| Seagate             | 48        | 66     | 29.45%  |
| Toshiba             | 20        | 28     | 12.27%  |
| Hitachi             | 13        | 14     | 7.98%   |
| Samsung Electronics | 9         | 10     | 5.52%   |
| HGST                | 5         | 6      | 3.07%   |
| Unknown             | 3         | 4      | 1.84%   |
| Fujitsu             | 3         | 3      | 1.84%   |
| MARVELL             | 1         | 1      | 0.61%   |
| LaCie               | 1         | 1      | 0.61%   |
| ipTIME              | 1         | 1      | 0.61%   |
| Hewlett-Packard     | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 74     | 33.33%  |
| SanDisk             | 21        | 21     | 11.48%  |
| Crucial             | 21        | 26     | 11.48%  |
| WDC                 | 14        | 19     | 7.65%   |
| Intel               | 7         | 10     | 3.83%   |
| A-DATA Technology   | 6         | 6      | 3.28%   |
| Transcend           | 5         | 6      | 2.73%   |
| TAMMUZ              | 5         | 8      | 2.73%   |
| SK hynix            | 4         | 5      | 2.19%   |
| Seagate             | 4         | 5      | 2.19%   |
| Micron Technology   | 4         | 5      | 2.19%   |
| SPCC                | 3         | 3      | 1.64%   |
| Plextor             | 3         | 5      | 1.64%   |
| Kingston            | 3         | 4      | 1.64%   |
| Toshiba             | 2         | 7      | 1.09%   |
| KingSpec            | 2         | 2      | 1.09%   |
| China               | 2         | 2      | 1.09%   |
| VIEW                | 1         | 1      | 0.55%   |
| TYPEC 1T            | 1         | 1      | 0.55%   |
| Team                | 1         | 1      | 0.55%   |
| RevuAhn             | 1         | 1      | 0.55%   |
| QNIX                | 1         | 1      | 0.55%   |
| PHINOCOM            | 1         | 1      | 0.55%   |
| OCZ                 | 1         | 2      | 0.55%   |
| LITEONIT            | 1         | 1      | 0.55%   |
| LITEON              | 1         | 1      | 0.55%   |
| IPLEX               | 1         | 1      | 0.55%   |
| Imation             | 1         | 2      | 0.55%   |
| GLOWAY              | 1         | 1      | 0.55%   |
| FORESEE             | 1         | 1      | 0.55%   |
| Biostar             | 1         | 1      | 0.55%   |
| Apple               | 1         | 1      | 0.55%   |
| Apacer              | 1         | 1      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 161       | 226    | 36.34%  |
| HDD     | 135       | 224    | 30.47%  |
| NVMe    | 107       | 145    | 24.15%  |
| MMC     | 34        | 54     | 7.67%   |
| Unknown | 6         | 7      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 220       | 438    | 58.36%  |
| NVMe | 106       | 144    | 28.12%  |
| MMC  | 34        | 54     | 9.02%   |
| SAS  | 17        | 20     | 4.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 178       | 266    | 58.36%  |
| 0.51-1.0   | 71        | 96     | 23.28%  |
| 1.01-2.0   | 26        | 33     | 8.52%   |
| 3.01-4.0   | 13        | 26     | 4.26%   |
| 2.01-3.0   | 8         | 11     | 2.62%   |
| 4.01-10.0  | 7         | 11     | 2.3%    |
| 10.01-20.0 | 2         | 7      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 107       | 31.2%   |
| 251-500        | 66        | 19.24%  |
| 501-1000       | 44        | 12.83%  |
| 51-100         | 30        | 8.75%   |
| 1001-2000      | 24        | 7%      |
| 21-50          | 22        | 6.41%   |
| More than 3000 | 18        | 5.25%   |
| 2001-3000      | 14        | 4.08%   |
| 1-20           | 12        | 3.5%    |
| Unknown        | 6         | 1.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 144       | 41.03%  |
| 21-50          | 67        | 19.09%  |
| 101-250        | 42        | 11.97%  |
| 51-100         | 32        | 9.12%   |
| 251-500        | 25        | 7.12%   |
| 501-1000       | 15        | 4.27%   |
| 2001-3000      | 7         | 1.99%   |
| 1001-2000      | 7         | 1.99%   |
| More than 3000 | 6         | 1.71%   |
| Unknown        | 6         | 1.71%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB             | 1         | 1      | 4.76%   |
| WDC WD7500AACS-00D6B0 752GB              | 1         | 1      | 4.76%   |
| WDC WD5000AAKX-75U6AA0 500GB             | 1         | 1      | 4.76%   |
| WDC WD1600BEVT-22A23T0 160GB             | 1         | 1      | 4.76%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 4.76%   |
| WDC WD1001FALS-00J7B1 1TB                | 1         | 1      | 4.76%   |
| Toshiba MK5061GSYN 500GB                 | 1         | 1      | 4.76%   |
| Toshiba MK2565GSX 250GB                  | 1         | 1      | 4.76%   |
| SK hynix HFS128G3AMNM-1010A 128GB SSD    | 1         | 1      | 4.76%   |
| Seagate ST4000DM000-1F2168 4TB           | 1         | 1      | 4.76%   |
| Seagate ST3500418AS 500GB                | 1         | 1      | 4.76%   |
| Seagate ST1000DM003-1CH162 1TB           | 1         | 1      | 4.76%   |
| Samsung Electronics SSD 830 Series 512GB | 1         | 1      | 4.76%   |
| Phison ES 512GB                          | 1         | 1      | 4.76%   |
| LITEONIT LMT-256M3M 256GB SSD            | 1         | 1      | 4.76%   |
| LITEON LMH-128V2M 128GB SSD              | 1         | 1      | 4.76%   |
| Kingston SHFS37A120G 120GB SSD           | 1         | 1      | 4.76%   |
| Intel SSDSA2CW120G3 120GB                | 1         | 1      | 4.76%   |
| Hitachi HTS541616J9SA00 160GB            | 1         | 1      | 4.76%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 4.76%   |
| HGST HDN726060ALE610 6TB                 | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 28.57%  |
| Seagate             | 3         | 3      | 14.29%  |
| Toshiba             | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| SK hynix            | 1         | 1      | 4.76%   |
| Samsung Electronics | 1         | 1      | 4.76%   |
| Phison              | 1         | 1      | 4.76%   |
| LITEONIT            | 1         | 1      | 4.76%   |
| LITEON              | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| Intel               | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 6      | 42.86%  |
| Seagate | 3         | 3      | 21.43%  |
| Toshiba | 2         | 2      | 14.29%  |
| HGST    | 2         | 2      | 14.29%  |
| Hitachi | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 14     | 63.16%  |
| SSD  | 6         | 6      | 31.58%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Detected | 215       | 418    | 61.08%  |
| Works    | 118       | 217    | 33.52%  |
| Malfunc  | 19        | 21     | 5.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 201       | 49.51%  |
| AMD                              | 57        | 14.04%  |
| Samsung Electronics              | 44        | 10.84%  |
| SanDisk                          | 20        | 4.93%   |
| SK hynix                         | 12        | 2.96%   |
| ASMedia Technology               | 12        | 2.96%   |
| JMicron Technology               | 9         | 2.22%   |
| Phison Electronics               | 8         | 1.97%   |
| Toshiba America Info Systems     | 6         | 1.48%   |
| Union Memory (Shenzhen)          | 4         | 0.99%   |
| Silicon Motion                   | 4         | 0.99%   |
| Kingston Technology Company      | 4         | 0.99%   |
| Micron/Crucial Technology        | 3         | 0.74%   |
| Marvell Technology Group         | 3         | 0.74%   |
| Broadcom / LSI                   | 3         | 0.74%   |
| ADATA Technology                 | 3         | 0.74%   |
| Nvidia                           | 2         | 0.49%   |
| Micron Technology                | 2         | 0.49%   |
| KIOXIA                           | 2         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Seagate Technology               | 1         | 0.25%   |
| Realtek Semiconductor            | 1         | 0.25%   |
| Lite-On Technology               | 1         | 0.25%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.25%   |
| Hewlett-Packard                  | 1         | 0.25%   |
| Apple                            | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 48        | 10.04%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 26        | 5.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 3.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11        | 2.3%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 11        | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 2.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 9         | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 9         | 1.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 1.88%   |
| AMD 300 Series Chipset SATA Controller                                                  | 9         | 1.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 8         | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 1.67%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 1.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 7         | 1.46%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 7         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.46%   |
| AMD FCH SATA Controller D                                                               | 7         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.26%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.26%   |
| SK hynix Gold P31 SSD                                                                   | 5         | 1.05%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5         | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5         | 1.05%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 5         | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 1.05%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 5         | 1.05%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 5         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1.05%   |
| AMD FCH IDE Controller                                                                  | 5         | 1.05%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 4         | 0.84%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 4         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.63%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.63%   |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.63%   |
| Phison E12 NVMe Controller                                                              | 3         | 0.63%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 0.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.63%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 0.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 0.63%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 0.63%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3         | 0.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.63%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 0.63%   |
| AMD SB600 IDE                                                                           | 3         | 0.63%   |
| SK hynix Non-Volatile memory controller                                                 | 2         | 0.42%   |
| SK hynix BC511                                                                          | 2         | 0.42%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 0.42%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 221       | 56.81%  |
| NVMe | 108       | 27.76%  |
| IDE  | 39        | 10.03%  |
| RAID | 18        | 4.63%   |
| SCSI | 2         | 0.51%   |
| SAS  | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 251       | 76.29%  |
| AMD    | 70        | 21.28%  |
| ARM    | 8         | 2.43%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3570 CPU @ 3.40GHz              | 8         | 2.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 2.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 1.82%   |
| ARM Processor                                 | 6         | 1.82%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 5         | 1.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.52%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 5         | 1.52%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 4         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.22%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 4         | 1.22%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 1.22%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.91%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.91%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 3         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.91%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 3         | 0.91%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 3         | 0.91%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.91%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 0.91%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 3         | 0.91%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.91%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 0.91%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 0.91%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 2         | 0.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.61%   |
| Intel Pentium 4 CPU 3.00GHz                   | 2         | 0.61%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz              | 2         | 0.61%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.61%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.61%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 2         | 0.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.61%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 2         | 0.61%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.61%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 2         | 0.61%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 0.61%   |
| Intel Core i5 CPU 760 @ 2.80GHz               | 2         | 0.61%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.61%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 2         | 0.61%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz         | 2         | 0.61%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.61%   |
| Intel Atom CPU Z3770 @ 1.46GHz                | 2         | 0.61%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 2         | 0.61%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.61%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 2         | 0.61%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 2         | 0.61%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.61%   |
| Intel Xeon W-3275M CPU @ 2.50GHz              | 1         | 0.3%    |
| Intel Xeon W-2133 CPU @ 3.60GHz               | 1         | 0.3%    |
| Intel Xeon Silver 4214 CPU @ 2.20GHz          | 1         | 0.3%    |
| Intel Xeon Silver 4210 CPU @ 2.20GHz          | 1         | 0.3%    |
| Intel Xeon Silver 4114 CPU @ 2.20GHz          | 1         | 0.3%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 70        | 21.28%  |
| Intel Core i7           | 57        | 17.33%  |
| Other                   | 26        | 7.9%    |
| AMD Ryzen 5             | 20        | 6.08%   |
| Intel Core i3           | 19        | 5.78%   |
| AMD Ryzen 7             | 16        | 4.86%   |
| Intel Celeron           | 15        | 4.56%   |
| Intel Xeon              | 12        | 3.65%   |
| Intel Atom              | 10        | 3.04%   |
| Intel Pentium           | 8         | 2.43%   |
| Intel Core i9           | 8         | 2.43%   |
| Intel Core 2 Duo        | 8         | 2.43%   |
| AMD Ryzen 3             | 8         | 2.43%   |
| Intel Core 2 Quad       | 6         | 1.82%   |
| AMD Ryzen Threadripper  | 4         | 1.22%   |
| AMD Ryzen 5 PRO         | 4         | 1.22%   |
| AMD A10                 | 4         | 1.22%   |
| Intel Xeon Silver       | 3         | 0.91%   |
| Intel Core m3           | 3         | 0.91%   |
| AMD Ryzen 9             | 3         | 0.91%   |
| Intel Pentium Silver    | 2         | 0.61%   |
| Intel Pentium Dual-Core | 2         | 0.61%   |
| Intel Pentium 4         | 2         | 0.61%   |
| Intel Genuine           | 2         | 0.61%   |
| Intel Core 2            | 2         | 0.61%   |
| AMD Ryzen 7 PRO         | 2         | 0.61%   |
| AMD A8                  | 2         | 0.61%   |
| AMD A4                  | 2         | 0.61%   |
| Intel Xeon Gold         | 1         | 0.3%    |
| Intel Pentium Gold      | 1         | 0.3%    |
| Intel Pentium Dual      | 1         | 0.3%    |
| ARM AArch64             | 1         | 0.3%    |
| AMD Quad-Core           | 1         | 0.3%    |
| AMD Phenom II X6        | 1         | 0.3%    |
| AMD Phenom              | 1         | 0.3%    |
| AMD Athlon II X2        | 1         | 0.3%    |
| AMD Athlon 64 X2        | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 135       | 41.03%  |
| 2       | 101       | 30.7%   |
| 6       | 34        | 10.33%  |
| 8       | 33        | 10.03%  |
| 12      | 5         | 1.52%   |
| 16      | 4         | 1.22%   |
| 20      | 3         | 0.91%   |
| 10      | 3         | 0.91%   |
| 1       | 3         | 0.91%   |
| 32      | 2         | 0.61%   |
| 64      | 1         | 0.3%    |
| 28      | 1         | 0.3%    |
| 22      | 1         | 0.3%    |
| 18      | 1         | 0.3%    |
| 14      | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 320       | 97.26%  |
| 2      | 9         | 2.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 212       | 64.44%  |
| 1       | 116       | 35.26%  |
| Unknown | 1         | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 318       | 96.36%  |
| Unknown        | 10        | 3.03%   |
| 64-bit         | 1         | 0.3%    |
| 32-bit         | 1         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 16.12%  |
| 0x306a9    | 26        | 7.76%   |
| 0x306c3    | 17        | 5.07%   |
| 0x806c1    | 14        | 4.18%   |
| 0x806ec    | 13        | 3.88%   |
| 0x206a7    | 12        | 3.58%   |
| 0x906e9    | 11        | 3.28%   |
| 0x08600106 | 11        | 3.28%   |
| 0x806e9    | 9         | 2.69%   |
| 0x906ea    | 8         | 2.39%   |
| 0x806ea    | 7         | 2.09%   |
| 0x706a1    | 7         | 2.09%   |
| 0x20655    | 7         | 2.09%   |
| 0x1067a    | 7         | 2.09%   |
| 0x906ed    | 6         | 1.79%   |
| 0x806eb    | 6         | 1.79%   |
| 0x30678    | 5         | 1.49%   |
| 0x106e5    | 5         | 1.49%   |
| 0x706e5    | 4         | 1.19%   |
| 0x40651    | 4         | 1.19%   |
| 0x306f2    | 4         | 1.19%   |
| 0x0a50000c | 4         | 1.19%   |
| 0x08108102 | 4         | 1.19%   |
| 0x0800820d | 4         | 1.19%   |
| 0x08001138 | 4         | 1.19%   |
| 0x08001137 | 4         | 1.19%   |
| 0xa0652    | 3         | 0.9%    |
| 0x6fd      | 3         | 0.9%    |
| 0x6fb      | 3         | 0.9%    |
| 0x50654    | 3         | 0.9%    |
| 0x406c4    | 3         | 0.9%    |
| 0x306d4    | 3         | 0.9%    |
| 0x30673    | 3         | 0.9%    |
| 0x06001119 | 3         | 0.9%    |
| 0xa0660    | 2         | 0.6%    |
| 0xa0655    | 2         | 0.6%    |
| 0x906ec    | 2         | 0.6%    |
| 0x90672    | 2         | 0.6%    |
| 0x706a8    | 2         | 0.6%    |
| 0x506e3    | 2         | 0.6%    |
| 0x406c3    | 2         | 0.6%    |
| 0x206c2    | 2         | 0.6%    |
| 0x20652    | 2         | 0.6%    |
| 0x10676    | 2         | 0.6%    |
| 0x08701021 | 2         | 0.6%    |
| 0x08600103 | 2         | 0.6%    |
| 0x08600102 | 2         | 0.6%    |
| 0x0810100b | 2         | 0.6%    |
| 0x0700010f | 2         | 0.6%    |
| 0xf49      | 1         | 0.3%    |
| 0x806d1    | 1         | 0.3%    |
| 0x6f6      | 1         | 0.3%    |
| 0x6e8      | 1         | 0.3%    |
| 0x50657    | 1         | 0.3%    |
| 0x406f1    | 1         | 0.3%    |
| 0x406e3    | 1         | 0.3%    |
| 0x306e4    | 1         | 0.3%    |
| 0x0a50000b | 1         | 0.3%    |
| 0x0a201009 | 1         | 0.3%    |
| 0x08701013 | 1         | 0.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 66        | 20.06%  |
| Haswell          | 31        | 9.42%   |
| IvyBridge        | 28        | 8.51%   |
| Zen 2            | 23        | 6.99%   |
| Zen              | 16        | 4.86%   |
| Silvermont       | 15        | 4.56%   |
| TigerLake        | 14        | 4.26%   |
| Skylake          | 13        | 3.95%   |
| SandyBridge      | 13        | 3.95%   |
| Penryn           | 13        | 3.95%   |
| Westmere         | 12        | 3.65%   |
| Unknown          | 12        | 3.65%   |
| Zen+             | 10        | 3.04%   |
| Goldmont plus    | 9         | 2.74%   |
| Core             | 8         | 2.43%   |
| Zen 3            | 7         | 2.13%   |
| CometLake        | 7         | 2.13%   |
| Nehalem          | 5         | 1.52%   |
| IceLake          | 5         | 1.52%   |
| Broadwell        | 4         | 1.22%   |
| Piledriver       | 3         | 0.91%   |
| K10              | 3         | 0.91%   |
| Steamroller      | 2         | 0.61%   |
| NetBurst         | 2         | 0.61%   |
| Jaguar           | 2         | 0.61%   |
| P6               | 1         | 0.3%    |
| K8 Hammer        | 1         | 0.3%    |
| K10 Llano        | 1         | 0.3%    |
| Excavator        | 1         | 0.3%    |
| Bonnell          | 1         | 0.3%    |
| Alderlake Hybrid | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 180       | 46.88%  |
| Nvidia                           | 125       | 32.55%  |
| AMD                              | 70        | 18.23%  |
| ASPEED Technology                | 6         | 1.56%   |
| Matrox Electronics Systems       | 2         | 0.52%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 18        | 4.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10        | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 2.56%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.3%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 2.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.79%   |
| Intel UHD Graphics 620                                                                   | 7         | 1.79%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.53%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 6         | 1.53%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 5         | 1.28%   |
| Intel HD Graphics 630                                                                    | 5         | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.02%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 4         | 1.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.02%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.02%   |
| AMD Cezanne                                                                              | 4         | 1.02%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.77%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 3         | 0.77%   |
| Nvidia GT218M [GeForce 310M]                                                             | 3         | 0.77%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 0.77%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 3         | 0.77%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 3         | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.77%   |
| Nvidia GA102 [GeForce RTX 3090]                                                          | 3         | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.77%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.77%   |
| Intel HD Graphics 620                                                                    | 3         | 0.77%   |
| Intel HD Graphics 530                                                                    | 3         | 0.77%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.77%   |
| Nvidia TU117M                                                                            | 2         | 0.51%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.51%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.51%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.51%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 2         | 0.51%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 2         | 0.51%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.51%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 2         | 0.51%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.51%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                                     | 2         | 0.51%   |
| Nvidia GF104 [GeForce GTX 460]                                                           | 2         | 0.51%   |
| Nvidia G98 [GeForce 9300 GS]                                                             | 2         | 0.51%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.51%   |
| Intel HD Graphics 615                                                                    | 2         | 0.51%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.51%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.51%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 0.51%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 127       | 38.48%  |
| 1 x Nvidia      | 77        | 23.33%  |
| 1 x AMD         | 55        | 16.67%  |
| Intel + Nvidia  | 37        | 11.21%  |
| Other           | 8         | 2.42%   |
| Intel + AMD     | 6         | 1.82%   |
| AMD + Nvidia    | 6         | 1.82%   |
| 1 x ASPEED      | 4         | 1.21%   |
| 2 x AMD         | 3         | 0.91%   |
| 2 x Nvidia      | 2         | 0.61%   |
| Nvidia + ASPEED | 2         | 0.61%   |
| 1 x SiS         | 1         | 0.3%    |
| Nvidia + Matrox | 1         | 0.3%    |
| 1 x Matrox      | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 238       | 71.9%   |
| Proprietary | 70        | 21.15%  |
| Unknown     | 23        | 6.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 52.55%  |
| 1.01-2.0   | 36        | 10.81%  |
| 0.01-0.5   | 33        | 9.91%   |
| 0.51-1.0   | 31        | 9.31%   |
| 3.01-4.0   | 25        | 7.51%   |
| 7.01-8.0   | 11        | 3.3%    |
| 5.01-6.0   | 8         | 2.4%    |
| 8.01-16.0  | 7         | 2.1%    |
| 2.01-3.0   | 4         | 1.2%    |
| 16.01-24.0 | 2         | 0.6%    |
| 4.01-5.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 54        | 16.07%  |
| LG Display              | 42        | 12.5%   |
| Goldstar                | 39        | 11.61%  |
| AU Optronics            | 34        | 10.12%  |
| BOE                     | 25        | 7.44%   |
| Chimei Innolux          | 15        | 4.46%   |
| Unknown                 | 10        | 2.98%   |
| Dell                    | 9         | 2.68%   |
| Philips                 | 8         | 2.38%   |
| Sharp                   | 7         | 2.08%   |
| LG Electronics          | 7         | 2.08%   |
| Hewlett-Packard         | 6         | 1.79%   |
| OUT                     | 5         | 1.49%   |
| Apple                   | 5         | 1.49%   |
| AOC                     | 5         | 1.49%   |
| PANDA                   | 4         | 1.19%   |
| BenQ                    | 4         | 1.19%   |
| ALP                     | 4         | 1.19%   |
| PRISM+                  | 3         | 0.89%   |
| JCH                     | 3         | 0.89%   |
| CPT                     | 3         | 0.89%   |
| Ancor Communications    | 3         | 0.89%   |
| MStar                   | 2         | 0.6%    |
| Lenovo                  | 2         | 0.6%    |
| JRY                     | 2         | 0.6%    |
| InfoVision              | 2         | 0.6%    |
| Denver                  | 2         | 0.6%    |
| CSO                     | 2         | 0.6%    |
| Chi Mei Optoelectronics | 2         | 0.6%    |
| VMO                     | 1         | 0.3%    |
| Unknown (ADE)           | 1         | 0.3%    |
| TopView                 | 1         | 0.3%    |
| TMX                     | 1         | 0.3%    |
| TGL                     | 1         | 0.3%    |
| Sony                    | 1         | 0.3%    |
| SiS                     | 1         | 0.3%    |
| SANYO                   | 1         | 0.3%    |
| RTK                     | 1         | 0.3%    |
| RAT                     | 1         | 0.3%    |
| PBK                     | 1         | 0.3%    |
| ORM                     | 1         | 0.3%    |
| OOO                     | 1         | 0.3%    |
| NME                     | 1         | 0.3%    |
| MON                     | 1         | 0.3%    |
| LYC                     | 1         | 0.3%    |
| KVM                     | 1         | 0.3%    |
| KTC                     | 1         | 0.3%    |
| HVT                     | 1         | 0.3%    |
| HKC                     | 1         | 0.3%    |
| HannStar                | 1         | 0.3%    |
| DPL                     | 1         | 0.3%    |
| CVT                     | 1         | 0.3%    |
| CND                     | 1         | 0.3%    |
| CM_                     | 1         | 0.3%    |
| CHR                     | 1         | 0.3%    |
| ADP                     | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch               | 7         | 2.02%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 6         | 1.73%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 3         | 0.86%   |
| OUT HDMI OUT0240 1920x1200 341x256mm 16.8-inch                          | 3         | 0.86%   |
| LG Display LCD Monitor LGD0694 2560x1600 344x215mm 16.0-inch            | 3         | 0.86%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch        | 3         | 0.86%   |
| BOE LCD Monitor BOE0889 1920x1080 344x194mm 15.5-inch                   | 3         | 0.86%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.86%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 2         | 0.58%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch       | 2         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0D42 3840x2160 1872x1053mm 84.6-inch | 2         | 0.58%   |
| LG Display LCD Monitor LGD0644 1920x1080 309x174mm 14.0-inch            | 2         | 0.58%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch            | 2         | 0.58%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 2         | 0.58%   |
| LG Display LCD Monitor LGD03B5 1920x1080 294x165mm 13.3-inch            | 2         | 0.58%   |
| JRY Digital JRY0215 1920x1080 340x255mm 16.7-inch                       | 2         | 0.58%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                    | 2         | 0.58%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 2         | 0.58%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                       | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch        | 2         | 0.58%   |
| BOE LCD Monitor BOE06D7 3840x2160 345x194mm 15.6-inch                   | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch           | 2         | 0.58%   |
| AU Optronics LCD Monitor 1920x1080                                      | 2         | 0.58%   |
| Ancor Communications ASUS PB258 ACI25A1 2560x1440 553x311mm 25.0-inch   | 2         | 0.58%   |
| VMO LCD WQXGA HDM VMO1506 2560x1600 1600x1000mm 74.3-inch               | 1         | 0.29%   |
| Unknown LCD Monitor STD 32Q-HDMI 2560x1440                              | 1         | 0.29%   |
| Unknown LCD Monitor SKYDATA S.P.A. LG TV 1920x1080                      | 1         | 0.29%   |
| Unknown LCD Monitor SAMSUNG 3286x1080                                   | 1         | 0.29%   |
| Unknown LCD Monitor OUT Digital 3200x1080                               | 1         | 0.29%   |
| Unknown LCD Monitor ORC DIGITAL MONITOR 1280x1024                       | 1         | 0.29%   |
| Unknown LCD Monitor NQM NewQ System 1280x1024                           | 1         | 0.29%   |
| Unknown LCD Monitor INN ULTRON 3479UC 4880x2560                         | 1         | 0.29%   |
| Unknown LCD Monitor ICB ULTRON4079 3840x2160                            | 1         | 0.29%   |
| Unknown LCD Monitor Digital Projection Limited DP                       | 1         | 0.29%   |
| Unknown LCD Monitor COZ 27VV IPS 1920x1200                              | 1         | 0.29%   |
| Unknown LCD Monitor Chuntex/CTX NL27 3840x2160                          | 1         | 0.29%   |
| Unknown (ADE) N2413 ADS LED ADE2413 1920x1080 521x293mm 23.5-inch       | 1         | 0.29%   |
| TopView TOPSYNC TOP049B 2560x1440 597x336mm 27.0-inch                   | 1         | 0.29%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                 | 1         | 0.29%   |
| TGL TGL A190 TGL0908 1280x1024 376x301mm 19.0-inch                      | 1         | 0.29%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                   | 1         | 0.29%   |
| SiS DV 24 TV SIS0330 1920x1080 930x530mm 42.1-inch                      | 1         | 0.29%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 380x210mm 17.1-inch                 | 1         | 0.29%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 0.29%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                 | 1         | 0.29%   |
| SANYO LED MONITOR SAN309A 1920x1080 443x249mm 20.0-inch                 | 1         | 0.29%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1         | 0.29%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch       | 1         | 0.29%   |
| Samsung Electronics U32H85x SAM0E3A 3840x2160 697x392mm 31.5-inch       | 1         | 0.29%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch       | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch    | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM04AE 1680x1050 459x296mm 21.5-inch    | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM03F3 1920x1200 518x324mm 24.1-inch    | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 165       | 50.3%   |
| 1366x768 (WXGA)    | 34        | 10.37%  |
| 3840x2160 (4K)     | 29        | 8.84%   |
| 2560x1440 (QHD)    | 19        | 5.79%   |
| 1920x1200 (WUXGA)  | 11        | 3.35%   |
| 1280x1024 (SXGA)   | 11        | 3.35%   |
| 2560x1600          | 9         | 2.74%   |
| 1600x900 (HD+)     | 8         | 2.44%   |
| 1680x1050 (WSXGA+) | 7         | 2.13%   |
| 1280x800 (WXGA)    | 6         | 1.83%   |
| 1440x900 (WXGA+)   | 5         | 1.52%   |
| Unknown            | 5         | 1.52%   |
| 3440x1440          | 4         | 1.22%   |
| 2560x1080          | 4         | 1.22%   |
| 2880x1800          | 3         | 0.91%   |
| 4880x2560          | 1         | 0.3%    |
| 3840x1600          | 1         | 0.3%    |
| 3840x1080          | 1         | 0.3%    |
| 3286x1080          | 1         | 0.3%    |
| 3200x1080          | 1         | 0.3%    |
| 2160x1440          | 1         | 0.3%    |
| 1680x945           | 1         | 0.3%    |
| 1600x1200          | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 77        | 22.92%  |
| 13      | 35        | 10.42%  |
| Unknown | 33        | 9.82%   |
| 14      | 27        | 8.04%   |
| 27      | 24        | 7.14%   |
| 21      | 23        | 6.85%   |
| 24      | 19        | 5.65%   |
| 23      | 18        | 5.36%   |
| 16      | 14        | 4.17%   |
| 17      | 11        | 3.27%   |
| 31      | 9         | 2.68%   |
| 19      | 7         | 2.08%   |
| 34      | 6         | 1.79%   |
| 25      | 3         | 0.89%   |
| 20      | 3         | 0.89%   |
| 18      | 3         | 0.89%   |
| 12      | 3         | 0.89%   |
| 11      | 3         | 0.89%   |
| 84      | 2         | 0.6%    |
| 40      | 2         | 0.6%    |
| 22      | 2         | 0.6%    |
| 10      | 2         | 0.6%    |
| 74      | 1         | 0.3%    |
| 54      | 1         | 0.3%    |
| 49      | 1         | 0.3%    |
| 46      | 1         | 0.3%    |
| 43      | 1         | 0.3%    |
| 42      | 1         | 0.3%    |
| 39      | 1         | 0.3%    |
| 37      | 1         | 0.3%    |
| 33      | 1         | 0.3%    |
| 29      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 126       | 37.95%  |
| 501-600     | 58        | 17.47%  |
| 401-500     | 33        | 9.94%   |
| Unknown     | 33        | 9.94%   |
| 201-300     | 32        | 9.64%   |
| 351-400     | 19        | 5.72%   |
| 601-700     | 12        | 3.61%   |
| 701-800     | 7         | 2.11%   |
| 801-900     | 4         | 1.2%    |
| 1501-2000   | 3         | 0.9%    |
| 1001-1500   | 3         | 0.9%    |
| 901-1000    | 2         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 215       | 69.81%  |
| 16/10   | 34        | 11.04%  |
| Unknown | 31        | 10.06%  |
| 5/4     | 9         | 2.92%   |
| 4/3     | 8         | 2.6%    |
| 21/9    | 8         | 2.6%    |
| 3/2     | 2         | 0.65%   |
| 32/9    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 77        | 23.19%  |
| 201-250        | 53        | 15.96%  |
| 81-90          | 40        | 12.05%  |
| Unknown        | 33        | 9.94%   |
| 301-350        | 25        | 7.53%   |
| 71-80          | 22        | 6.63%   |
| 351-500        | 17        | 5.12%   |
| 151-200        | 11        | 3.31%   |
| 251-300        | 8         | 2.41%   |
| 121-130        | 8         | 2.41%   |
| 111-120        | 7         | 2.11%   |
| 501-1000       | 7         | 2.11%   |
| 131-140        | 6         | 1.81%   |
| 141-150        | 5         | 1.51%   |
| More than 1000 | 4         | 1.2%    |
| 61-70          | 3         | 0.9%    |
| 51-60          | 3         | 0.9%    |
| 41-50          | 2         | 0.6%    |
| 91-100         | 1         | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 95        | 28.79%  |
| 51-100        | 84        | 25.45%  |
| 101-120       | 73        | 22.12%  |
| Unknown       | 33        | 10%     |
| 161-240       | 30        | 9.09%   |
| More than 240 | 11        | 3.33%   |
| 1-50          | 4         | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 259       | 77.08%  |
| 2     | 50        | 14.88%  |
| 0     | 24        | 7.14%   |
| 3     | 3         | 0.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 188       | 40.78%  |
| Intel                             | 166       | 36.01%  |
| Qualcomm Atheros                  | 35        | 7.59%   |
| Broadcom                          | 20        | 4.34%   |
| ASIX Electronics                  | 7         | 1.52%   |
| Marvell Technology Group          | 6         | 1.3%    |
| Ralink Technology                 | 5         | 1.08%   |
| Ralink                            | 4         | 0.87%   |
| MediaTek                          | 4         | 0.87%   |
| U-Blox                            | 3         | 0.65%   |
| Samsung Electronics               | 3         | 0.65%   |
| Broadcom Limited                  | 3         | 0.65%   |
| TP-Link                           | 2         | 0.43%   |
| Nvidia                            | 2         | 0.43%   |
| Lenovo                            | 2         | 0.43%   |
| Exar                              | 2         | 0.43%   |
| D-Link                            | 2         | 0.43%   |
| Van Ooijen Technische Informatica | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.22%   |
| PEAK-System Technik               | 1         | 0.22%   |
| Microchip Technology              | 1         | 0.22%   |
| Comneon                           | 1         | 0.22%   |
| Arduino SA                        | 1         | 0.22%   |
| American Megatrends               | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 147       | 27.43%  |
| Intel Wi-Fi 6 AX200                                               | 24        | 4.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 2.43%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.87%   |
| Intel Wireless 3165                                               | 9         | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.31%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.31%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 1.31%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.12%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.93%   |
| Intel Wireless 7260                                               | 5         | 0.93%   |
| Intel Wireless 3160                                               | 5         | 0.93%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 4         | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.75%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.75%   |
| U-Blox [u-blox 7]                                                 | 3         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 3         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.56%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3         | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.56%   |
| Intel Wireless 7265                                               | 3         | 0.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.56%   |
| Intel Ethernet Controller X550                                    | 3         | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.56%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 3         | 0.56%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.56%   |
| Intel 82576 Gigabit Network Connection                            | 3         | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.37%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 2         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.37%   |
| Realtek 802.11n NIC                                               | 2         | 0.37%   |
| Realtek 802.11ac NIC                                              | 2         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                   | 2         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.37%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 131       | 57.21%  |
| Realtek Semiconductor    | 40        | 17.47%  |
| Qualcomm Atheros         | 24        | 10.48%  |
| Broadcom                 | 14        | 6.11%   |
| Ralink Technology        | 5         | 2.18%   |
| Ralink                   | 4         | 1.75%   |
| MediaTek                 | 4         | 1.75%   |
| TP-Link                  | 2         | 0.87%   |
| D-Link                   | 2         | 0.87%   |
| Broadcom Limited         | 2         | 0.87%   |
| Marvell Technology Group | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 24        | 10.39%  |
| Intel Wi-Fi 6 AX201                                           | 13        | 5.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 10        | 4.33%   |
| Intel Wireless 3165                                           | 9         | 3.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 7         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 7         | 3.03%   |
| Intel Wireless 8265 / 8275                                    | 7         | 3.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 7         | 3.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 5         | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 5         | 2.16%   |
| Intel Wireless 7260                                           | 5         | 2.16%   |
| Intel Wireless 3160                                           | 5         | 2.16%   |
| Intel Gemini Lake PCH CNVi WiFi                               | 5         | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 5         | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 5         | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 4         | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4         | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 4         | 1.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3         | 1.3%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 3         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 3         | 1.3%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 3         | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 1.3%    |
| Intel Wireless 7265                                           | 3         | 1.3%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 3         | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 3         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 3         | 1.3%    |
| Intel Centrino Wireless-N 2230                                | 3         | 1.3%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                  | 3         | 1.3%    |
| Intel Centrino Advanced-N 6235                                | 3         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                 | 3         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 2         | 0.87%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 2         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 2         | 0.87%   |
| Realtek 802.11n NIC                                           | 2         | 0.87%   |
| Realtek 802.11ac NIC                                          | 2         | 0.87%   |
| Ralink MT7601U Wireless Adapter                               | 2         | 0.87%   |
| Intel Wireless-AC 9260                                        | 2         | 0.87%   |
| Intel WiFi Link 5100                                          | 2         | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 2         | 0.87%   |
| Intel Centrino Advanced-N 6200                                | 2         | 0.87%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 2         | 0.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2         | 0.87%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller        | 2         | 0.87%   |
| Broadcom BCM43162 802.11ac Wireless Network Adapter           | 2         | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.43%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                         | 1         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 1         | 0.43%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 1         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 1         | 0.43%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter      | 1         | 0.43%   |
| Ralink RT5572 Wireless Adapter                                | 1         | 0.43%   |
| Ralink RT5372 Wireless Adapter                                | 1         | 0.43%   |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.43%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter        | 1         | 0.43%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                     | 1         | 0.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.43%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                          | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 178       | 63.12%  |
| Intel                            | 62        | 21.99%  |
| Qualcomm Atheros                 | 13        | 4.61%   |
| ASIX Electronics                 | 7         | 2.48%   |
| Broadcom                         | 6         | 2.13%   |
| Marvell Technology Group         | 5         | 1.77%   |
| Samsung Electronics              | 3         | 1.06%   |
| Nvidia                           | 2         | 0.71%   |
| Lenovo                           | 2         | 0.71%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Microchip Technology             | 1         | 0.35%   |
| Broadcom Limited                 | 1         | 0.35%   |
| American Megatrends              | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 147       | 49.66%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 13        | 4.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 12        | 4.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 2.36%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 2.36%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.03%   |
| Intel Ethernet Connection (7) I219-V                                           | 6         | 2.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 4         | 1.35%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.35%   |
| Intel I210 Gigabit Network Connection                                          | 4         | 1.35%   |
| Intel Ethernet Controller I225-V                                               | 4         | 1.35%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.35%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 1.35%   |
| Intel 82574L Gigabit Network Connection                                        | 4         | 1.35%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 1.01%   |
| Intel Ethernet Controller X550                                                 | 3         | 1.01%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 1.01%   |
| Intel 82576 Gigabit Network Connection                                         | 3         | 1.01%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.68%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 2         | 0.68%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.68%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.68%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.68%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.68%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.68%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 1         | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.34%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 1         | 0.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.34%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.34%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.34%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.34%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.34%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.34%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 1         | 0.34%   |
| Lenovo USB-C Dock Ethernet                                                     | 1         | 0.34%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                               | 1         | 0.34%   |
| Intel Ethernet controller                                                      | 1         | 0.34%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                   | 1         | 0.34%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.34%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.34%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.34%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.34%   |
| Intel Ethernet Connection (2) I218-LM                                          | 1         | 0.34%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.34%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 1         | 0.34%   |
| Intel 82575EB Gigabit Network Connection                                       | 1         | 0.34%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.34%   |
| Intel 82557/8/9/0/1 Ethernet Pro 100                                           | 1         | 0.34%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.34%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 264       | 53.77%  |
| WiFi     | 219       | 44.6%   |
| Modem    | 7         | 1.43%   |
| Unknown  | 1         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 178       | 52.05%  |
| WiFi     | 164       | 47.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 164       | 49.85%  |
| 2     | 142       | 43.16%  |
| 0     | 12        | 3.65%   |
| 3     | 8         | 2.43%   |
| 4     | 2         | 0.61%   |
| 5     | 1         | 0.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 328       | 99.7%   |
| Yes  | 1         | 0.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 54.68%  |
| Cambridge Silicon Radio         | 25        | 12.32%  |
| Realtek Semiconductor           | 17        | 8.37%   |
| Broadcom                        | 13        | 6.4%    |
| Qualcomm Atheros Communications | 12        | 5.91%   |
| IMC Networks                    | 9         | 4.43%   |
| Lite-On Technology              | 4         | 1.97%   |
| Foxconn / Hon Hai               | 4         | 1.97%   |
| Apple                           | 3         | 1.48%   |
| ASUSTek Computer                | 2         | 0.99%   |
| Qcom                            | 1         | 0.49%   |
| Micro Star International        | 1         | 0.49%   |
| Marvell Semiconductor           | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 14.78%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 25        | 12.32%  |
| Intel AX201 Bluetooth                                                               | 24        | 11.82%  |
| Intel AX200 Bluetooth                                                               | 24        | 11.82%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 19        | 9.36%   |
| Realtek Bluetooth Radio                                                             | 12        | 5.91%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.43%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.46%   |
| Intel Bluetooth Device                                                              | 4         | 1.97%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.48%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.48%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.48%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 1.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 1.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.48%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.99%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.99%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 2         | 0.99%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.99%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 0.99%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.49%   |
| Realtek CSR BS8510                                                                  | 1         | 0.49%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 1         | 0.49%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.49%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.49%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.49%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.49%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.49%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.49%   |
| Broadcom Bluetooth 2.1 Device                                                       | 1         | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.49%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.49%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 1         | 0.49%   |
| ASUS Bluetooth Radio                                                                | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 233       | 54.57%  |
| Nvidia                           | 90        | 21.08%  |
| AMD                              | 86        | 20.14%  |
| JMTek                            | 3         | 0.7%    |
| Lenovo                           | 2         | 0.47%   |
| Giga-Byte Technology             | 2         | 0.47%   |
| C-Media Electronics              | 2         | 0.47%   |
| ASUSTek Computer                 | 2         | 0.47%   |
| Silicon Integrated Systems [SiS] | 1         | 0.23%   |
| Razer USA                        | 1         | 0.23%   |
| Medeli Electronics               | 1         | 0.23%   |
| Fry's Electronics                | 1         | 0.23%   |
| Dell                             | 1         | 0.23%   |
| Apple                            | 1         | 0.23%   |
| Unknown                          | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 35        | 6.96%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 23        | 4.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 3.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 3.58%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 2.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 2.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 2.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 14        | 2.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 2.39%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.79%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 9         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.79%   |
| Intel 200 Series PCH HD Audio                                                                     | 9         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 1.79%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.59%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.39%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.19%   |
| Nvidia TU102 High Definition Audio Controller                                                     | 5         | 0.99%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.99%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.99%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 5         | 0.99%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.99%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 5         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.8%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 4         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.8%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 0.8%    |
| Nvidia GM206 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.6%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.6%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.6%    |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.6%    |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.6%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.6%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.4%    |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.4%    |
| Nvidia GP102 HDMI Audio Controller                                                                | 2         | 0.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.4%    |
| Nvidia GF104 High Definition Audio Controller                                                     | 2         | 0.4%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.4%    |
| Intel USB PnP Sound Device                                                                        | 2         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 103       | 56.28%  |
| SK hynix            | 31        | 16.94%  |
| Micron Technology   | 9         | 4.92%   |
| Unknown             | 8         | 4.37%   |
| Kingston            | 6         | 3.28%   |
| Team                | 4         | 2.19%   |
| A-DATA Technology   | 3         | 1.64%   |
| Unknown             | 3         | 1.64%   |
| Unknown (ABCD)      | 2         | 1.09%   |
| Ramaxel Technology  | 2         | 1.09%   |
| NOT SUPPORT         | 2         | 1.09%   |
| KLEVV               | 2         | 1.09%   |
| Unknown (09D5)      | 1         | 0.55%   |
| Silicon Power       | 1         | 0.55%   |
| Imation             | 1         | 0.55%   |
| Hewlett-Packard     | 1         | 0.55%   |
| G.Skill             | 1         | 0.55%   |
| Essencore           | 1         | 0.55%   |
| Elpida              | 1         | 0.55%   |
| Crucial             | 1         | 0.55%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 6         | 2.94%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s              | 6         | 2.94%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 4         | 1.96%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 1.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.96%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 4         | 1.96%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 3         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.47%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.47%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s      | 3         | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.47%   |
| Samsung RAM M378B5273EB0-CK0 4GB DIMM DDR3 1800MT/s                 | 3         | 1.47%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1866MT/s                 | 3         | 1.47%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s                 | 3         | 1.47%   |
| Samsung RAM M378A4G43AB2-CWE 32GB DIMM DDR4 3200MT/s                | 3         | 1.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 3         | 1.47%   |
| Unknown                                                             | 3         | 1.47%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                           | 2         | 0.98%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.98%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.98%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 2         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.98%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 2         | 0.98%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1G44AB0-CTD 8GB DDR4 2667MT/s                      | 2         | 0.98%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s                 | 2         | 0.98%   |
| Samsung RAM M378B1G73QH0-CK0 8GB DIMM DDR3 1600MT/s                 | 2         | 0.98%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s                 | 2         | 0.98%   |
| Samsung RAM M378A4G43MB1-CTD 32GB DIMM DDR4 3466MT/s                | 2         | 0.98%   |
| Samsung RAM M378A2K43CB1-CTD 16384MB DIMM DDR4 2667MT/s             | 2         | 0.98%   |
| Samsung RAM M378A2K43BB1-CRC 16GB DIMM DDR4 3200MT/s                | 2         | 0.98%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s                 | 2         | 0.98%   |
| Samsung RAM M378A1K43BB2-CRC 8GB DIMM DDR4 3400MT/s                 | 2         | 0.98%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 2         | 0.98%   |
| NOT SUPPORT RAM Module 4096MB DIMM 1333MT/s                         | 2         | 0.98%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                             | 1         | 0.49%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                | 1         | 0.49%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                    | 1         | 0.49%   |
| Unknown RAM CL22-22-22 D4-3200 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s    | 1         | 0.49%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s      | 1         | 0.49%   |
| Unknown (09D5) RAM Module 16384MB SODIMM DDR4 2400MT/s              | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2667MT/s                  | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD4-2666 16GB DIMM DDR4 3000MT/s                 | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s                  | 1         | 0.49%   |
| Team RAM TEAMGROUP-UD4-2133 8GB DIMM DDR4 2666MT/s                  | 1         | 0.49%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.49%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                     | 1         | 0.49%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                    | 1         | 0.49%   |
| SK hynix RAM HMT451U7BFR8A-PB 4096MB DIMM DDR3 1600MT/s             | 1         | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.49%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.49%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 1         | 0.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 57.76%  |
| DDR3    | 42        | 26.09%  |
| LPDDR4  | 10        | 6.21%   |
| LPDDR3  | 8         | 4.97%   |
| SDRAM   | 4         | 2.48%   |
| Unknown | 3         | 1.86%   |
| DDR2    | 1         | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 76        | 46.91%  |
| DIMM         | 60        | 37.04%  |
| Row Of Chips | 21        | 12.96%  |
| Unknown      | 4         | 2.47%   |
| Chip         | 1         | 0.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 72        | 41.14%  |
| 4096  | 49        | 28%     |
| 16384 | 28        | 16%     |
| 2048  | 12        | 6.86%   |
| 32768 | 10        | 5.71%   |
| 1024  | 3         | 1.71%   |
| 65536 | 1         | 0.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 36        | 20.11%  |
| 2667    | 32        | 17.88%  |
| 1600    | 25        | 13.97%  |
| 2400    | 14        | 7.82%   |
| 2133    | 13        | 7.26%   |
| 4267    | 7         | 3.91%   |
| 3500    | 6         | 3.35%   |
| 1333    | 6         | 3.35%   |
| 1334    | 5         | 2.79%   |
| 3266    | 4         | 2.23%   |
| 2666    | 4         | 2.23%   |
| 3466    | 3         | 1.68%   |
| 1867    | 3         | 1.68%   |
| 1866    | 3         | 1.68%   |
| 1800    | 3         | 1.68%   |
| 3400    | 2         | 1.12%   |
| 2933    | 2         | 1.12%   |
| 1066    | 2         | 1.12%   |
| Unknown | 2         | 1.12%   |
| 8400    | 1         | 0.56%   |
| 4199    | 1         | 0.56%   |
| 3066    | 1         | 0.56%   |
| 3000    | 1         | 0.56%   |
| 2048    | 1         | 0.56%   |
| 1067    | 1         | 0.56%   |
| 800     | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 3         | 42.86%  |
| Seiko Epson         | 1         | 14.29%  |
| Samsung Electronics | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L220 Series  | 1         | 14.29%  |
| Samsung CLX-3180 Series  | 1         | 14.29%  |
| HP OfficeJet 4650 series | 1         | 14.29%  |
| Canon PIXMA MP280        | 1         | 14.29%  |
| Canon G4010 series       | 1         | 14.29%  |
| Canon E560 series        | 1         | 14.29%  |
| Brother DCP-T310         | 1         | 14.29%  |

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
| Chicony Electronics                    | 33        | 20%     |
| IMC Networks                           | 20        | 12.12%  |
| Acer                                   | 15        | 9.09%   |
| Silicon Motion                         | 11        | 6.67%   |
| Realtek Semiconductor                  | 10        | 6.06%   |
| Microdia                               | 9         | 5.45%   |
| Syntek                                 | 7         | 4.24%   |
| Sunplus Innovation Technology          | 7         | 4.24%   |
| Quanta                                 | 7         | 4.24%   |
| Unknown                                | 6         | 3.64%   |
| Suyin                                  | 5         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.03%   |
| Apple                                  | 5         | 3.03%   |
| Z-Star Microelectronics                | 3         | 1.82%   |
| Logitech                               | 3         | 1.82%   |
| Sony                                   | 2         | 1.21%   |
| Samsung Electronics                    | 2         | 1.21%   |
| Microsoft                              | 2         | 1.21%   |
| lihappe8                               | 2         | 1.21%   |
| Canon                                  | 2         | 1.21%   |
| Telmax Communications                  | 1         | 0.61%   |
| Luxvisions Innotech Limited            | 1         | 0.61%   |
| LG Electronics                         | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| Goodong Industry                       | 1         | 0.61%   |
| GEMBIRD                                | 1         | 0.61%   |
| DigiTech                               | 1         | 0.61%   |
| ARC International                      | 1         | 0.61%   |
| Alcor Micro                            | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 9         | 5.36%   |
| IMC Networks Integrated Camera                          | 8         | 4.76%   |
| Unknown 720p HD Camera                                  | 6         | 3.57%   |
| Microdia Integrated_Webcam_HD                           | 6         | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 6         | 3.57%   |
| Syntek Integrated Camera                                | 5         | 2.98%   |
| Chicony HD Webcam                                       | 5         | 2.98%   |
| Silicon Motion LG HD WebCam                             | 4         | 2.38%   |
| Acer HD Webcam                                          | 4         | 2.38%   |
| Suyin HP Truevision HD                                  | 3         | 1.79%   |
| Sunplus Integrated_Webcam_HD                            | 3         | 1.79%   |
| Realtek LG Camera                                       | 3         | 1.79%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.79%   |
| Chicony LG HD WebCam                                    | 3         | 1.79%   |
| Chicony LG Camera                                       | 3         | 1.79%   |
| Acer Integrated Camera                                  | 3         | 1.79%   |
| Z-Star Webcam                                           | 2         | 1.19%   |
| Sony ILCE-7S                                            | 2         | 1.19%   |
| Silicon Motion WebCam SC-10HDP12631N                    | 2         | 1.19%   |
| Samsung Galaxy A5 (MTP)                                 | 2         | 1.19%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.19%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.19%   |
| Quanta LG Webcam                                        | 2         | 1.19%   |
| Logitech C922 Pro Stream Webcam                         | 2         | 1.19%   |
| lihappe8 USB 2.0 Camera                                 | 2         | 1.19%   |
| Chicony USB 2.0 Camera                                  | 2         | 1.19%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.19%   |
| Canon Digital Camera                                    | 2         | 1.19%   |
| Apple iPhone 5/5C/5S/6/SE                               | 2         | 1.19%   |
| Apple Built-in iSight                                   | 2         | 1.19%   |
| Z-Star Vimicro USB Camera (Altair)                      | 1         | 0.6%    |
| Telmax AbleScope                                        | 1         | 0.6%    |
| Syntek Lenovo EasyCamera                                | 1         | 0.6%    |
| Syntek HP Webcam                                        | 1         | 0.6%    |
| Suyin USB 2.0 Camera                                    | 1         | 0.6%    |
| Suyin HP TrueVision Full HD                             | 1         | 0.6%    |
| Sunplus UHD4K                                           | 1         | 0.6%    |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.6%    |
| Sunplus ASUS USB2.0 Webcam                              | 1         | 0.6%    |
| Sunplus ABKO APC930 QHD WEBCAM                          | 1         | 0.6%    |
| Silicon Motion WebCam SC-13HDN10939N                    | 1         | 0.6%    |
| Silicon Motion WebCam SC-13HDL11431N                    | 1         | 0.6%    |
| Silicon Motion WebCam SC-10HDD13335N                    | 1         | 0.6%    |
| Silicon Motion Web Camera                               | 1         | 0.6%    |
| Silicon Motion ATIV VGA Camera                          | 1         | 0.6%    |
| Realtek USB2.0 VGA UVC WebCam                           | 1         | 0.6%    |
| Realtek Integrated Webcam                               | 1         | 0.6%    |
| Realtek HD WebCam                                       | 1         | 0.6%    |
| Quanta USB HD Webcam                                    | 1         | 0.6%    |
| Quanta HP HD Camera                                     | 1         | 0.6%    |
| Microsoft LifeCam VX-2000                               | 1         | 0.6%    |
| Microsoft LifeCam Rear                                  | 1         | 0.6%    |
| Microsoft LifeCam Front                                 | 1         | 0.6%    |
| Microdia Webcam SC-10HDD12636P                          | 1         | 0.6%    |
| Microdia USB 2.0 Camera                                 | 1         | 0.6%    |
| Microdia HP Integrated Webcam                           | 1         | 0.6%    |
| Luxvisions Innotech Limited HP HD Camera                | 1         | 0.6%    |
| Logitech Webcam C110                                    | 1         | 0.6%    |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)   | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 39.02%  |
| Validity Sensors           | 7         | 17.07%  |
| Samsung Electronics        | 6         | 14.63%  |
| Shenzhen Goodix Technology | 4         | 9.76%   |
| Upek                       | 3         | 7.32%   |
| LighTuning Technology      | 2         | 4.88%   |
| Elan Microelectronics      | 2         | 4.88%   |
| AuthenTec                  | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Unknown                                                   | 8         | 19.51%  |
| Samsung Fingerprint Sensor Device - 730B                  | 4         | 9.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 3         | 7.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 7.32%   |
| Shenzhen Goodix Fingerprint Reader                        | 3         | 7.32%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 4.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 4.88%   |
| Samsung Fingerprint Device                                | 2         | 4.88%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 2         | 4.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor         | 1         | 2.44%   |
| Validity Sensors VFS495 Fingerprint Reader                | 1         | 2.44%   |
| Validity Sensors VFS451 Fingerprint Reader                | 1         | 2.44%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 2.44%   |
| Validity Sensors Fingerprint scanner                      | 1         | 2.44%   |
| Synaptics WBDI Device                                     | 1         | 2.44%   |
| Shenzhen Goodix  FingerPrint Device                       | 1         | 2.44%   |
| Elan ELAN:Fingerprint                                     | 1         | 2.44%   |
| Elan ELAN:ARM-M4                                          | 1         | 2.44%   |
| AuthenTec Fingerprint Sensor                              | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 2         | 40%     |
| Upek        | 1         | 20%     |
| O2 Micro    | 1         | 20%     |
| Broadcom    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 227       | 67.56%  |
| 1     | 88        | 26.19%  |
| 2     | 13        | 3.87%   |
| 3     | 4         | 1.19%   |
| 5     | 2         | 0.6%    |
| 4     | 2         | 0.6%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 31.3%   |
| Graphics card            | 31        | 23.66%  |
| Net/wireless             | 19        | 14.5%   |
| Unassigned class         | 11        | 8.4%    |
| Communication controller | 6         | 4.58%   |
| Multimedia controller    | 5         | 3.82%   |
| Chipcard                 | 5         | 3.82%   |
| Camera                   | 5         | 3.82%   |
| Net/ethernet             | 4         | 3.05%   |
| Sound                    | 2         | 1.53%   |
| Network                  | 1         | 0.76%   |
| Bluetooth                | 1         | 0.76%   |

